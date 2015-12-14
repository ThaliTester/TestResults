#### Test 50650278e3ff7c2_thali03_LGE-LG-D855 Logs


```
--------- beginning of main
D/sensors_hal_Time( 1031): tsOffsetIs: Apps: 157525467109; DSPS: 5302555; Offset : -4307664598
,D/AndroidRuntime( 6199): 
D/AndroidRuntime( 6199): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 6199): CheckJNI is OFF
D/AndroidRuntime( 6199): Calling main entry com.android.commands.am.Am
--------- beginning of system
I/ActivityManager( 1031): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
V/SplitWindowPolicy( 1945): checkScreen => return. sourceIntent is null or not support SplitWindow component: ComponentInfo{co..../co.....MainActivity}
D/SplitInfo( 1031): new ActivitySplitInfo : ActivitySplitInfo [screenZone=0/ flag=0/ state=NATIVE]
D/ActivityManager( 1031): setTaskToReturnTo : TaskRecord{34d547e2 #4 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
D/ActivityManager( 1031): setTaskToReturnTo : TaskRecord{34d547e2 #4 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
D/WindowStateEx( 1031): AppWindowTokenEx init.. 
E/GBMv2   (  335): DFP En is all cleared set to be enabled
I/ActivityManager( 1031): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6219 uid=10311 gids={50311, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
D/AndroidRuntime( 6199): Shutting down VM
V/ActivityManager( 1031): Display changed displayId=0
D/DSDPConnection( 1850): Display #0 changed.
D/SplitWindowPolicy( 1945): updateActivityStateChanged: resumed=true, screenId=1, isScreenFull=true
D/SplitWindowPolicy( 1945): topRunningActivity=ActivityInfo{3a20dfc co.....MainActivity}, taskId=4, activityType=0, bIsSplit=false
D/SplitWindowPolicy( 1945): updateActivityStateChanged: resumed=false, screenId=1, isScreenFull=true
D/SplitWindowPolicy( 1945): topRunningActivity=ActivityInfo{392aec85 co.....MainActivity}, taskId=4, activityType=0, bIsSplit=false
D/ContextHelper( 6219): convertTheme. context->name=com.test.thalitest themeResourceId=16973833
,I/WebViewFactory( 6219): Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
I/LibraryLoader( 6219): Loading: webviewchromium
I/LibraryLoader( 6219): Time to load native libraries: 4 ms (timestamps 9966-9970)
I/LibraryLoader( 6219): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 6219): Binding Chromium to main looper Looper (main, tid 1) {3db2ebf1}
I/LibraryLoader( 6219): Expected native library version number "",actual native library version number ""
I/chromium( 6219): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 6219): Initializing chromium process, renderers=0
W/art     ( 6219): Attempt to remove local handle scope entry from IRT, ignoring
W/chromium( 6219): [WARNING:dns_config_service_posix.cc(293)] Failed to read DnsConfig.
V/AudioPolicyService(  317): registerClient() client 0xb57bee80, uid 10311
D/BluetoothManagerService( 1031): Message: 20
D/BluetoothManagerService( 1031): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@2d37d55c:true
W/chromium( 6219): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
D/BluetoothAdapter( 6219): 913839062: getState() :  mService = null. Returning STATE_OFF
I/chromium( 6219): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=32 off=46780 len=2953
I/chromium( 6219): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:33 off:229536 len:643667
I/Adreno-EGL( 6219): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 6219): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 6219): Build Date: 12/12/14 금
I/Adreno-EGL( 6219): Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
I/Adreno-EGL( 6219): Remote Branch: 
I/Adreno-EGL( 6219): Local Patches: 
I/Adreno-EGL( 6219): Reconstruct Branch: 
W/chromium( 6219): [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
W/chromium( 6219): [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
W/art     ( 6219): Attempt to remove local handle scope entry from IRT, ignoring
W/AwContents( 6219): onDetachedFromWindow called when already detached. Ignoring
D/SystemWebViewEngine( 6219): CordovaWebView is running on device made by: LGE
W/art     ( 6219): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 6219): Attempt to remove local handle scope entry from IRT, ignoring
D/OpenGLRenderer( 6219): Render dirty regions requested: true
I/OpenGLRenderer( 6219): Initialized EGL, version 1.4
D/OpenGLRenderer( 6219): Enabling debug mode 0
D/Atlas   ( 6219): Validating map...
D/SplitWindow( 1031): check instance of lgWin Window{27161db6 u0 com.test.thalitest/com.test.thalitest.MainActivity}
D/LgDataFeature( 6219): LgDataFeature() Constructor: none
D/LgDataFeature( 6219): LgDataFeature() Constructor Done, null
I/SystemUI[Framework]( 1031): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x0, pkg=com.android.systemui
W/PhoneWindowManagerEx( 1031): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx( 1031): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx( 1031): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework]( 1031): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@2614c8f6,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework]( 1031): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
D/PhoneStatusBar( 1447): setSystemUiVisibility vis=0 mask=ffffffff oldVal=8000 newVal=0 diff=8000
I/[SystemUI]NavigationThemeResource( 1447): NavigationKey Color is changed(WHITE_WITH_SHADOW -> BLACK)
I/[SystemUI]NavigationThemeResource( 1447):  BarMode=0, Theme=WHITE, LightBackground=false (Transparent)
I/[SystemUI]NavigationThemeResource( 1447): , Keyguard show=false, IME shown=false, Panel expanded=false
I/ActivityManager( 1031): Displayed com.test.thalitest/.MainActivity: +588ms (total +684ms)
I/Timeline( 1031): Timeline: Activity_windows_visible id: ActivityRecord{3582a773 u0 com.test.thalitest/.MainActivity t4} time:160369
I/Timeline( 6219): Timeline: Activity_idle id: android.os.BinderProxy@1a9b1e86 time:160376
I/chromium( 6219): [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
I/chromium( 6219): 
D/JsMessageQueue( 6219): Set native->JS mode to OnlineEventsBridgeMode
D/jxcore_app_log( 6219): JniHelper::setJavaVM(0xb487c280), pthread_self() = -1435069184
D/JX-Cordova( 6219): jxcore cordova android initializing
E/GBMv2   (  335): DFP En is all cleared set to be enabled
E/GBMv2   (  335): Set value is all cleared set the max
I/GBMv2   (  335): DFP Enabled. Ignore VFP set
,W/jxcore-log( 6219): Initializing JXcore engine
W/jxcore-log( 6219): JXcore engine is ready
,W/jxcore-log( 6219): Starting JXcore engine
,W/.test.thalitest( 6219): type=1400 audit(0.0:146): avc: denied { ioctl } for path="socket:[10271]" dev="sockfs" ino=10271 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
,W/.test.thalitest( 6219): type=1400 audit(0.0:147): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3222 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
W/.test.thalitest( 6219): type=1400 audit(0.0:148): avc: denied { ioctl } for path="socket:[9867]" dev="sockfs" ino=9867 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
W/.test.thalitest( 6219): type=1400 audit(0.0:149): avc: denied { ioctl } for path="/cust" dev="mmcblk0p42" ino=2 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=dir
W/.test.thalitest( 6219): type=1400 audit(0.0:150): avc: denied { ioctl } for path="socket:[31107]" dev="sockfs" ino=31107 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
W/jxcore-log( 6219): Platform android
W/jxcore-log( 6219): 
W/jxcore-log( 6219): Process ARCH arm
W/jxcore-log( 6219): 
,I/jxcore-log( 6219): JXcore Cordova bridge is ready!
I/jxcore-log( 6219): 
W/jxcore-log( 6219): JXcore engine is started
,I/jxcore-log( 6219): Toggling radios to true
I/jxcore-log( 6219): 
,D/BluetoothManagerService( 1031): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1031): enable():  mBluetooth =null mBinding = false
D/BluetoothManagerService( 1031): Message: 1
D/BluetoothManagerService( 1031): MESSAGE_ENABLE: mBluetooth = null
D/LocationManagerService( 1031): getAllProviders()=[passive, gps, network]
D/Ulp_jni ( 1031): JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
,D/Ulp_jni ( 1031): JNI:system_update. Event-4
D/WifiService( 1031): New client listening to asynchronous messages
I/ActivityManager( 1031): Start proc com.android.bluetooth for service com.android.bluetooth/.btservice.AdapterService: pid=6290 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008, 4002, 1023} abi=armeabi-v7a
D/WifiServiceImplEx( 1031): setWifiEnabled: true pid=6219, uid=10311, package= com.test.thalitest, App Lable : ThaliTest
D/WifiService( 1031): setWifiEnabled: true pid=6219, uid=10311
E/WifiService( 1031): Invoking mWifiStateMachine.setWifiEnabled
,D/LocationManagerService( 1031): getAllProviders()=[passive, gps, network]
D/Ulp_jni ( 1031): JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 1,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
D/Ulp_jni ( 1031): JNI:system_update. Event-4
E/WifiStateMachine( 1031):  InitialState CMD_START_SUPPLICANT 0 0
I/LGFTMITEM( 1031): [GET_FTM][id=6], offset=12288
D/WifiServiceImplEx( 1031): disconnect pid=6219, uid=10311, packageName=com.test.thalitest
D/WifiServiceImplEx( 1031): reconnect pid=6219, uid=10311, packageName=com.test.thalitest
I/jxcore-log( 6219): Radios toggled
I/jxcore-log( 6219): 
D/BluetoothManagerService( 1031): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/jxcore-log( 6219): Got Device Bluetooth address: 58:3F:54:73:64:C0
I/jxcore-log( 6219): 
I/jxcore-log( 6219): Perf Test app loaded loaded
I/jxcore-log( 6219): 
E/WifiUtil( 1031): wfc_util_ffile_check_copy(): pid[1031] pDestFName[/data/misc/wifi/WCNSS_qcom_cfg.ini] pSourceFName[/system/etc/wifi/WCNSS_qcom_cfg.ini]
E/WifiUtil( 1031): wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
E/WifiUtil( 1031): wfc_util_ffile_check_copy(): pid[1031] pDestFName[/data/misc/wifi/WCNSS_qcom_wlan_nv.bin] pSourceFName[/system/etc/wifi/WCNSS_qcom_wlan_nv.bin]
E/WifiUtil( 1031): wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
I/WifiUtil( 1031): Intf0MacAddress=C49A027B60AC
I/jxcore-log( 6219): check test folder
I/jxcore-log( 6219): 
E/WifiHW  ( 1031): unknown target_country: EU , set to default
E/WifiHW  ( 1031): [wifi_ensure_config_files] default country1 = GB
E/WifiHW  ( 1031): [wifi_ensure_config_files] default country2 = GB
I/WifiUtil( 1031): gEnableBmps=1
,I/jxcore-log( 6219): found test : ./testFindPeers.js
I/jxcore-log( 6219): 
W/ResourcesManager( 6290): Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
W/ResourcesManager( 6290): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 6290): Asset path '/system/framework/com.qcom.bluetooth.jar' does not exist or contains no resources.
W/ResourcesManager( 6290): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
I/jxcore-log( 6219): found test : ./testSendData.js
I/jxcore-log( 6219): 
,D/BluetoothAdapterApp( 6290): Loading JNI Library
,I/chromium( 6219): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,I/chromium( 6219): [INFO:SkFontConfigInterface_android.cpp(247)] ---- failed to open </system/fonts/CutiveMono.ttf> as a font
I/chromium( 6219): 
D/BluetoothAdapterApp( 6290): REFCOUNT: Constructed com.android.bluetooth.btservice.AdapterApp@583ed75 Instance Count = 1
I/chromium( 6219): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,D/BluetoothAdapterApp( 6290): onCreate
,D/Tethering( 1031): sendTetherStateChangedBroadcast 1, 0, 0
D/Tethering( 1031): InitialState.processMessage what=4
D/SoftapController(  313): Softap fwReload - Ok
,D/libc-netbsd(  313): default dns: query_ipv6=0, query_ipv4=0
D/CommandListener(  313): Setting iface cfg
D/CommandListener(  313): Trying to bring down wlan0
D/CommandListener(  313): Clearing all IP addresses on wlan0
D/DSQN    ( 1031): DNSproblemNotiEnabled is disabled ignore DNS fail CB
E/WifiHW  ( 1031): Cannot open "/system/etc/wifi/autojoinconfig.txt": No such file or directory
E/WifiStateMachine( 1031): Couldn't get getWiFiOffloadingIface : 
E/WifiStateMachine( 1031): useWiFiOffloading() : false
E/WifiStateMachine( 1031): CONFIG_LGE_WLAN_PATH : true
D/ProfileConfigQcom( 6290): [BTUI] HeadsetService is supported
D/ProfileConfigQcom( 6290): Adding HeadsetService
D/ProfileConfigQcom( 6290): [BTUI] A2dpService is supported
D/ProfileConfigQcom( 6290): Adding A2dpService
D/ProfileConfigQcom( 6290): [BTUI] HidService is supported
D/ProfileConfigQcom( 6290): Adding HidService
D/ProfileConfigQcom( 6290): [BTUI] HealthService is supported
D/ProfileConfigQcom( 6290): Adding HealthService
D/LGBluetoothFeatureConfig( 6290): isSupportPan() :  mTargetOp=OPEN
D/ProfileConfigQcom( 6290): [BTUI] PanService is supported
,D/ProfileConfigQcom( 6290): Adding PanService
D/ProfileConfigQcom( 6290): [BTUI] GattService is supported
D/ProfileConfigQcom( 6290): Adding GattService
D/ProfileConfigQcom( 6290): [BTUI] BluetoothMapService is supported
D/ProfileConfigQcom( 6290): Adding BluetoothMapService
D/ProfileConfigQcom( 6290): [BTUI] HeadsetClientService is NOT supported
I/ActivityManager( 1031): Start proc com.android.settings for broadcast com.android.settings/.deviceinfo.UsbSettingsReceiver: pid=6324 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
D/Tethering( 1031): sendTetherStateChangedBroadcast 0, 0, 0
W/wpa_supplicant( 6323): type=1400 audit(0.0:151): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
W/wpa_supplicant( 6323): type=1400 audit(0.0:152): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
D/WifiMonitor( 1031): startMonitoring(wlan0) with mConnected = false
D/WifiMonitor( 1031): connecting to supplicant
V/WfdStateTracker( 1945): WfdStateTracker handleDirectStateChangedEvent: 1
I/WifiServerServiceExt( 1031): WIFI_STATE_CHANGED_ACTION [2]
,D/StatusBar.NetworkController( 1447): refreshViews: Data not connected!! Set no data type icon / Roaming
I/wpa_supplicant( 6323): Successfully initialized wpa_supplicant
,D/BluetoothManagerService( 1031): Message: 20
D/BluetoothManagerService( 1031): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@21ac50c1:true
D/BluetoothAdapterState( 6290): make
I/LGFMServiceAdapter( 6290): [FM] LGFMServiceAdapter : create
I/bluedroid-qcom( 6290): init
,I/BluetoothAdapterState( 6290): Entering OffState
W/ResourcesManager( 6324): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6324): Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
W/ResourcesManager( 6324): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 6324): Asset path '/system/framework/com.lge.bluetooth.jar' does not exist or contains no resources.
W/ResourcesManager( 6324): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
W/ResourcesManager( 6324): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
I/bte_conf( 6290): bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,I/bte_conf( 6290): bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
E/bt_osi_config( 6290): config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
I/bte_conf( 6290): bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
D/BTIF_CORE( 6290): [BTUI] lge_load_bluetooth_address
I/bluedroid-qcom( 6290): get_profile_interface socket
I/bluedroid-qcom( 6290): get_profile_interface map_client
W/bdaddr_loader( 6348): type=1400 audit(0.0:153): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
W/bdaddr_loader( 6348): type=1400 audit(0.0:154): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
D/BluetoothManagerService( 1031): BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
D/BluetoothManagerService( 1031): Message: 40
D/BluetoothManagerService( 1031): MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
I/bluedroid-qcom( 6290): config_hci_snoop_log
D/BluetoothManagerService( 1031): Calling onBluetoothServiceUp callbacks
D/BluetoothManagerService( 1031): Broadcasting onBluetoothServiceUp() to 7 receivers.
I/GKI_LINUX( 6290): gki_task_entry task_id=1 [BTIF] starting
D/BluetoothAdapterProperties( 6290): Address is:58:3F:54:73:64:C0
D/lge_bdaddr_loader( 6348): [BTUI] bdaddr_loader ::: START
D/lge_bdaddr_loader( 6348): [BTUI] bluetooth_load_bdaddress
I/LGFTMITEM( 6348): [GET_FTM][id=8], offset=16384
D/BluetoothManagerService( 1031): Bluetooth Adapter name changed to G3-1
D/BluetoothManagerService( 1031): Stored Bluetooth name: G3-1
,D/BluetoothAdapterProperties( 6290): Name is: G3-1
I/wpa_supplicant( 6323): rfkill: Cannot open RFKILL control device
I/wpa_supplicant( 6323): [LGE_PATCH] unset P2P_CAPABLE to ifname wlan0
D/lge_bdaddr_loader( 6348): [BTUI] bdaddr to set in property : 58:3F:54:73:64:C0
V/LGMDMManagerInternal( 6290): Create singleton instance
E/lge_bdaddr_loader( 6348): [BTUI] bluetooth_load_bdaddress : OK => 58:3F:54:73:64:C0
D/lge_bdaddr_loader( 6348): [BTUI] bdaddr_loader ::: END
,D/UsbSettingsReceiver( 6324): [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
D/UsbSettingsReceiver( 6324): [AUTORUN] sys.usb.config = ptp_only,adb
D/UsbSettingsReceiver( 6324): [AUTORUN] sys.usb.state = ptp_only,adb
D/UsbSettingsReceiver( 6324): [AUTORUN] persist.sys.usb.config = ptp_only,adb
,D/UsbSettingsReceiver( 6324): [AUTORUN] onReceive() : app userid = 0, current userid = 0
D/BluetoothAdapterState( 6290): CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
D/BluetoothAdapterProperties( 6290): Setting state to 11
I/BluetoothAdapterState( 6290): Bluetooth adapter state changed: 10-> 11
D/BluetoothManagerService( 1031): Message: 60
D/BluetoothManagerService( 1031): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
D/BluetoothManagerService( 1031): Bluetooth State Change Intent: 10 -> 11
I/[SystemUI]BluetoothHandler( 1447): Receive : BluetoothAdapter.ACTION_STATE_CHANGED
D/LGBluetoothAPIService( 1945): [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
I/LGBluetoothServiceJni( 6290): classInitNative: succeeds
I/wpa_supplicant( 6323): rfkill: Cannot open RFKILL control device
D/BluetoothBondStateMachine( 6290): make
,D/UsbSettingsControl( 6324): [AUTORUN] getUsbConnected() : connected=true
D/UsbSettingsReceiver( 6324): [AUTORUN] onReceive() : availableList=[wlan0]
D/UsbSettingsReceiver( 6324): [AUTORUN] onReceive() : activeList=[]
D/UsbSettingsReceiver( 6324): [AUTORUN] onReceive() : errorList=[]
D/UsbSettingsControl( 6324): [AUTORUN] isAutorunTimer() : mAutorunChanging=false
D/UsbSettingsReceiver( 6324): [AUTORUN] onReceive() : TetherState Changed=wlan0
D/UsbSettingsControl( 6324): [AUTORUN] setTetherStatus() : status=false
I/ActivityManager( 1031): Killing 2191:com.lge.music/u0a34 (adj 15): empty #17
I/BluetoothBondStateMachine( 6290): StableState(): Entering Off State
D/BluetoothAdapterService( 6290): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2076f544
,D/LGBluetoothServiceAdapter( 6290): [BTUI] check adapter is available - false.
D/BluetoothAdapterService( 6290): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2076f544
D/LGBluetoothServiceAdapter( 6290): [BTUI] check adapter is available - true : set adapter available.
D/LGBluetoothSettingsDBObserver( 6290): [BTUI] register observer for LG device name DB
E/BluetoothAdapterService( 6290): File transfer profiles supported!!
,V/AudioFlinger(  317): 2191 died, releasing its sessions
V/AudioFlinger(  317):  pid 1850 @ 0
V/AudioFlinger(  317):  pid 3215 @ 1
V/AudioFlinger(  317):  pid 3215 @ 2
I/wpa_supplicant( 6323): [LGE_WLAN_PATCH]P2P 5GHz support level:2(0:no 1:gconly 2:gconly_UNII1 3:full)
,I/wpa_supplicant( 6323): p2p0: CTRL-EVENT-AVOID-FREQ ranges=
I/wpa_supplicant( 6323): wlan0: CTRL-EVENT-SCAN-STARTED 
E/WifiStateMachine( 1031):  SupplicantStartingState CMD_SET_OPERATIONAL_MODE 1 0
D/WifiMonitor( 1031): Event [IFNAME=p2p0 CTRL-EVENT-AVOID-FREQ ranges=]
D/WifiMonitor( 1031): Dropping event because (p2p0) is stopped
D/WifiMonitor( 1031): Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1031): WifiMonitor:wlan0 cnt=0 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiStateMachine( 1031):  SupplicantStartingState CMD_START_DRIVER 0 0
E/WifiStateMachine( 1031):  SupplicantStartingState CMD_SET_HIGH_PERF_MODE 0 0
E/WifiStateMachine( 1031):  DefaultState CMD_SET_HIGH_PERF_MODE 0 0
,E/WifiStateMachine( 1031):  SupplicantStartingState CMD_DISCONNECT 0 0
E/WifiStateMachine( 1031):  DefaultState CMD_DISCONNECT 0 0
E/WifiMonitor( 1031): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1031): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
E/WifiStateMachine( 1031):  SupplicantStartingState CMD_RECONNECT 0 0
E/WifiStateMachine( 1031):  DefaultState CMD_RECONNECT 0 0
E/WifiStateMachine( 1031):  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1031):  DefaultState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1031):  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1031):  DefaultState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1031):  SupplicantStartingState SUP_CONNECTION_EVENT 0 0
D/WifiNative-wlan0( 1031): doString: [DRIVER MACADDR]
D/WifiNative-wlan0( 1031):    returned Macaddr = c4:9a:02:7b:60:ac
D/WifiStateMachine( 1031): MAC Addr from driver = c4:9a:02:7b:60:ac
D/WifiOffDelayIfNotUsed( 1031): setPowerSaveActivated(false)
V/BluetoothPbapReceiver( 6290): PbapReceiver onReceive 
V/BluetoothPbapReceiver( 6290): ***********action = android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothPbapReceiver( 6290): ***********state = 11
W/libprocessgroup( 1031): failed to open /acct/uid_10034/pid_2191/cgroup.procs: No such file or directory
E/BluetoothAdapterService( 6290): File transfer profiles supported!!
,E/WifiStateMachine( 1031): Couldn't get getWiFiOffloadingIface : 
E/WifiStateMachine( 1031): useWiFiOffloading() : false
E/WifiStateMachine( 1031): CONFIG_LGE_WLAN_PATH : true
W/Settings( 1031): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1031): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiNative-wlan0( 1031): doBoolean: SET update_config 1
D/WifiNative-wlan0( 1031): SET update_config 1: returned true
D/StatusBar.NetworkController( 1447): refreshViews: Data not connected!! Set no data type icon / Roaming
D/WfdService( 1945): Waiting for WifiP2p enabling
D/WifiConfigStore( 1031): Loading config and enabling all networks 
D/WifiNative-wlan0( 1031): doString: [LIST_NETWORKS]
D/WifiNative-wlan0( 1031):    returned network id / ssid / bssid / flags 0	NG700	any	
E/BluetoothAdapterService( 6290): File transfer profiles supported!!
D/BluetoothHeadset( 1850): Proxy object connected
D/HeadsetService( 6290): Received start request. Starting profile...
I/WifiServerServiceExt( 1031): WIFI_STATE_CHANGED_ACTION [3]
I/LGBluetoothHeadsetServiceJni( 6290): classInitNative: succeeds
D/LGBluetoothHfpAdapter( 6290): Version 1.6
D/BluetoothHeadset( 1850): Proxy object connected
D/BluetoothHeadset( 1850): Proxy object connected
D/BluetoothHeadset( 1031): Proxy object connected
E/WifiConfigStore( 1031): readNetworkVariablesFromSupplicantFile key=psk
D/LGBluetoothFeatureConfig( 6290): isPrivacyLogsEnabled : true
I/WifiServerServiceExt( 1031): batteryPsActivateMsgHandler : state:0 event:3
,I/BluetoothHeadsetServiceJni( 6290): classInitNative: succeeds
D/HeadsetStateMachine( 6290): make
,E/WifiConfigStore( 1031): readNetworkVariableFromSupplicantFile ssid=["NG700"] key=psk
E/WifiConfigStore( 1031): Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
D/UsbSettingsReceiver( 6324): [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
D/UsbSettingsReceiver( 6324): [AUTORUN] sys.usb.config = ptp_only,adb
D/UsbSettingsReceiver( 6324): [AUTORUN] sys.usb.state = ptp_only,adb
D/UsbSettingsReceiver( 6324): [AUTORUN] persist.sys.usb.config = ptp_only,adb
D/LgDataFeature( 6290): LgDataFeature() Constructor: none
D/LgDataFeature( 6290): LgDataFeature() Constructor Done, null
,I/ActivityManager( 1031): Start proc com.lge.lifetracker for broadcast com.lge.lifetracker/.receiver.HealthDeviceReceiver: pid=6357 uid=10037 gids={50037, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
,D/WifiStateMachine( 1031): enableVerboseLogging : level 2
,D/WifiNative-wlan0( 1031): doBoolean: SET device_name g3_global_com
D/WifiNative-wlan0( 1031): SET device_name g3_global_com: returned true
D/WifiNative-wlan0( 1031): doBoolean: SET manufacturer LGE
D/WifiNative-wlan0( 1031): SET manufacturer LGE: returned true
D/WifiNative-wlan0( 1031): doBoolean: SET model_name LG-D855
D/WifiNative-wlan0( 1031): SET model_name LG-D855: returned true
D/WifiNative-wlan0( 1031): doBoolean: SET model_number LG-D855
D/UsbSettingsReceiver( 6324): [AUTORUN] onReceive() : app userid = 0, current userid = 0
D/HeadsetStateMachine( 6290): max_hf_connections = 1
I/bluedroid-qcom( 6290): get_profile_interface handsfree
D/WifiNative-wlan0( 1031): SET model_number LG-D855: returned true
D/WifiNative-wlan0( 1031): doBoolean: SET serial_number LGD8553bed2d08
D/WifiNative-wlan0( 1031): SET serial_number LGD8553bed2d08: returned true
D/UsbSettingsControl( 6324): [AUTORUN] getUsbConnected() : connected=true
D/UsbSettingsReceiver( 6324): [AUTORUN] onReceive() : availableList=[]
D/UsbSettingsReceiver( 6324): [AUTORUN] onReceive() : activeList=[]
D/WifiNative-wlan0( 1031): doBoolean: SET config_methods physical_display virtual_push_button
D/UsbSettingsReceiver( 6324): [AUTORUN] onReceive() : errorList=[]
D/UsbSettingsControl( 6324): [AUTORUN] isAutorunTimer() : mAutorunChanging=false
V/ToneGenerator( 6290): ToneGenerator constructor: streamType=8, volume=1.000000
D/WifiNative-wlan0( 1031): SET config_methods physical_display virtual_push_button: returned true
D/WifiNative-wlan0( 1031): doBoolean: SET device_type 10-0050F204-5
D/UsbSettingsControl( 6324): [AUTORUN] setTetherStatus() : status=false
V/AudioPolicyService(  317): registerClient() client 0xb57be860, uid 1002
D/WifiNative-wlan0( 1031): SET device_type 10-0050F204-5: returned true
V/AudioPolicyManager(  317): getOutput() device 2, stream 8, samplingRate 0, format 0, channelMask 3, flags 0
V/AudioPolicyManagerEx(  317): AudioPolicyManagerEx: getOutputForDevice
V/AudioPolicyManagerEx(  317): getOutput() returns output 2
V/AudioSystem( 6290): getOutputSamplingRate() no output descriptor for output 2 in gOutputs
D/WfdsService( 1945): Supplicant Connection state is changed : true
V/AudioFlinger(  317): registerClient() client 0xb5581988, pid 6290
D/WfdsService( 1945): DefaultState - WIFI_SUPPLICANT_CONNECTED
D/WfdsService( 1945): Set the WFDS Monitor: true
D/WfdsMonitor( 1945): WfdsMonitorThread create
,V/AudioSystem(  317): ioConfigChanged() event 0, ioHandle 2
V/AudioSystem(  317): ioConfigChanged() opening already existing output! 2
V/AudioSystem( 1850): ioConfigChanged() event 0, ioHandle 2
V/AudioSystem( 1850): ioConfigChanged() opening already existing output! 2
V/AudioSystem( 3215): ioConfigChanged() event 0, ioHandle 2
V/AudioSystem( 3215): ioConfigChanged() opening already existing output! 2
D/WfdsMonitor( 1945): WFDS Monitor is created and started
D/WfdsService( 1945): WiFi: Supplicant connection re-established
V/AudioSystem( 1031): ioConfigChanged() event 0, ioHandle 2
V/AudioSystem( 1031): ioConfigChanged() opening already existing output! 2
E/CtrlSupplicant( 1945): Access OK "@android:wpa_wlan0"
V/AudioSystem(  317): ioConfigChanged() event 0, ioHandle 4
V/AudioSystem( 6290): ioConfigChanged() event 0, ioHandle 2
E/CtrlSupplicant( 1945): Succeed to open control connection
V/AudioSystem(  317): ioConfigChanged() opening already existing output! 4
V/AudioSystem( 6290): ioConfigChanged() new output samplingRate 48000, format 0x5 channel mask 0x3 frameCount 960 latency 50
V/AudioSystem( 1850): ioConfigChanged() event 0, ioHandle 4
V/AudioSystem( 1850): ioConfigChanged() opening already existing output! 4
V/AudioSystem( 6290): ioConfigChanged() event 0, ioHandle 4
V/AudioSystem( 6290): ioConfigChanged() new output samplingRate 48000, format 0x1 channel mask 0x3 frameCount 960 latency 80
E/CtrlSupplicant( 1945): Succeed to open monitor connection
D/WfdsMonitor( 1945): Supplicant connection established
V/ToneGenerator( 6290): Create Track: 0xb4928080
V/AudioTrack( 6290): set(): streamType 8, sampleRate 0, format 0x1, channelMask 0x1, frameCount 0, flags #4, notificationFrames 0, sessionId 0, transferType 1
V/AudioTrack( 6290): set() streamType 8, sampleRate 0, format 1, frameCount 0, flags 0004
D/WfdsService( 1945): Connected to the supplicant for wfds
V/AudioSystem( 3215): ioConfigChanged() event 0, ioHandle 4
V/AudioSystem( 3215): ioConfigChanged() opening already existing output! 4
V/AudioSystem( 1031): ioConfigChanged() event 0, ioHandle 4
V/AudioSystem( 1031): ioConfigChanged() opening already existing output! 4
V/AudioSystem( 1447): ioConfigChanged() event 0, ioHandle 2
V/AudioSystem( 1447): ioConfigChanged() opening already existing output! 2
V/AudioSystem( 1447): ioConfigChanged() event 0, ioHandle 4
V/AudioSystem( 1447): ioConfigChanged() opening already existing output! 4
V/AudioPolicyManager(  317): getOutputForAttr() usage=3, content=4, tag= flags=00000000
E/BluetoothAdapterService( 6290): File transfer profiles supported!!
V/AudioPolicyManager(  317): getOutputForAttr() device 2, samplingRate 0, format 0, channelMask 3, flags 0
V/AudioPolicyManagerEx(  317): AudioPolicyManagerEx: getOutputForDevice
V/AudioPolicyManagerEx(  317): getOutput() returns output 2
D/WifiStateMachine( 1031): Setting OUI to DA-A1-19
D/WifiNative-wlan0( 1031): doBoolean: SCAN_INTERVAL 120
I/AudioFlinger(  317): isAudioPlaybackHookOn() false
V/AudioPolicyManager(  317): getOutputForAttr() usage=3, content=4, tag= flags=00000000
V/AudioPolicyManager(  317): getOutputForAttr() device 2, samplingRate 48000, format 1, channelMask 1, flags 4
V/AudioPolicyManagerEx(  317): AudioPolicyManagerEx: getOutputForDevice
V/AudioPolicyManagerEx(  317): getOutput() returns output 2
V/AudioSystem( 6290): getLatency() output 2, latency 50
V/AudioSystem( 6290): getFrameCount() output 2, frameCount 960
V/AudioTrack( 6290): createTrack_l() output 2 afLatency 50
V/AudioFlinger(  317): [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
V/AudioFlinger(  317): [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
V/AudioFlinger(  317): [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
V/AudioFlinger(  317): [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
V/AudioFlinger(  317): createTrack() lSessionId: 16
D/WifiNative-wlan0( 1031): SCAN_INTERVAL 120: returned true
D/WifiNative-HAL( 1031): Setting external_sim to 1
D/WifiNative-wlan0( 1031): doBoolean: SET external_sim 1
D/WifiNative-wlan0( 1031): SET external_sim 1: returned true
I/WifiNative-HAL( 1031): startHal
E/wifi    ( 1031): getStaticLongField sWifiHalHandle 0x989418dc
E/WifiHAL ( 1031): Could not connect handle
D/wifi    ( 1031): halHandle = 0x0, mVM = 0xb487c280, mCls = 0x701736
I/WifiNative-HAL( 1031): Could not start hal
D/WifiStateMachine( 1031): Setting OUI to DA-A1-19
I/WifiNative-HAL( 1031): startHal
V/AudioTrack( 6290): AUDIO_OUTPUT_FLAG_FAST successful; frameCount 480
E/wifi    ( 1031): getStaticLongField sWifiHalHandle 0x9894185c
E/WifiHAL ( 1031): Could not connect handle
D/wifi    ( 1031): halHandle = 0x0, mVM = 0xb487c280, mCls = 0x70171a
I/WifiNative-HAL( 1031): Could not start hal
D/WifiNative-wlan0( 1031): doBoolean: STA_AUTOCONNECT 1
V/AudioFlinger(  317): acquiring 16 from 6290, for 6290
V/AudioFlinger(  317):  added new entry for 16
V/ToneGenerator( 6290): ToneGenerator INIT OK, time: 164625
D/BluetoothAdapterService( 6290): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2076f544
D/WifiNative-wlan0( 1031): STA_AUTOCONNECT 1: returned true
D/WifiNative-wlan0( 1031): doBoolean: DRIVER BTCOEXSCAN-STOP
I/wpa_supplicant( 6323): wpa_driver_nl80211_ext_driver_cmd BTCOEXSCAN-STOP
D/HeadsetStateMachine( 6290): Enter Disconnected: -2, size: 0
D/WifiNative-wlan0( 1031): DRIVER BTCOEXSCAN-STOP: returned true
D/HeadsetPhoneState( 6290): [BTUI] listenForPhoneState : start = false
D/LGBluetoothHfpManager( 6290): [BTUI] listenForMultiSimPhoneState : start = false
D/HeadsetStateMachine( 6290): [BTUI] change sampling rate to 8000 when device is disconnected
V/AudioFlinger(  317): setParameters(): io 0, keyvalue bt_samplerate=8000, calling pid 6290
D/audio_hw_primary(  317): adev_set_parameters: enter: bt_samplerate=8000
V/voice   (  317): voice_set_parameters: enter: bt_samplerate=8000
V/compress_voip(  317): voice_extn_compress_voip_set_parameters: enter: bt_samplerate=8000
V/compress_voip(  317): voice_extn_compress_voip_set_parameters: exit
V/voice   (  317): voice_set_parameters: exit with code(0)
V/msm8974_platform_lge(  317): LGE_platform_set_parameters: enter: bt_samplerate=8000
V/msm8974_platform(  317): platform_set_parameters: enter: bt_samplerate=8000
V/msm8974_platform(  317): platform_set_parameters: exit with code(0)
V/lge_audio_loopback(  317): lge_platform_set_loopback_parameters: enter: 
V/audio_hw_primary(  317): adev_set_parameters: exit with code(0)
E/audio_a2dp_hw(  317): adev_set_parameters: ERROR: set param called even when stream out is null
V/ToneGenerator( 6290): ToneGenerator destructor
V/ToneGenerator( 6290): stopTone
V/ToneGenerator( 6290): Delete Track: 0xb4928080
V/AudioTrack( 6290): ~AudioTrack, releasing session id from 6290 on behalf of 6290
V/AudioFlinger(  317): releasing 16 from 6290 for 6290
V/AudioFlinger(  317):  decremented refcount to 0
V/AudioFlinger(  317): purging stale effects
V/AudioPolicyService(  317): AudioCommandThread() adding release output 2
V/AudioPolicyService(  317): inserting command: 6 at index 0, num commands 0
V/AudioPolicyService(  317): AudioCommandThread() waking up
V/AudioPolicyService(  317): AudioCommandThread() processing release output 2
V/AudioPolicyManager(  317): releaseOutput() 2
V/AudioPolicyService(  317): AudioCommandThread() going to sleep
V/AudioFlinger(  317): PlaybackThread::Track destructor
V/AudioFlinger(  317): removeClient_l() pid 6290, calling pid 317
,I/ActivityManager( 1031): Start proc com.lge.formmanager for broadcast com.lge.formmanager/.FormServiceReceiver: pid=6376 uid=10026 gids={50026, 9997, 3003, 1028} abi=armeabi-v7a
D/BluetoothAdapterService( 6290): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2076f544
D/WifiNative-wlan0( 1031): doBoolean: DRIVER RXFILTER-STOP
I/wpa_supplicant( 6323): wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
D/WifiNative-wlan0( 1031): DRIVER RXFILTER-STOP: returned true
D/WifiNative-wlan0( 1031): doBoolean: DRIVER RXFILTER-REMOVE 3
I/wpa_supplicant( 6323): wpa_driver_nl80211_ext_driver_cmd RXFILTER-REMOVE 3
D/BluetoothA2dp( 1031): Proxy object connected
D/WifiNative-wlan0( 1031): DRIVER RXFILTER-REMOVE 3: returned true
D/WifiNative-wlan0( 1031): doBoolean: DRIVER RXFILTER-START
I/wpa_supplicant( 6323): wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
D/WifiNative-wlan0( 1031): DRIVER RXFILTER-START: returned true
D/WifiNative-wlan0( 1031): doBoolean: DRIVER RXFILTER-STOP
I/wpa_supplicant( 6323): wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
D/A2dpService( 6290): Received start request. Starting profile...
D/WifiNative-wlan0( 1031): DRIVER RXFILTER-STOP: returned true
D/WifiNative-wlan0( 1031): doBoolean: DRIVER RXFILTER-REMOVE 2
I/wpa_supplicant( 6323): android_multicast_filter_startstop : multicast filter set
I/BluetoothAvrcpServiceJni( 6290): classInitNative: succeeds
D/WifiNative-wlan0( 1031): DRIVER RXFILTER-REMOVE 2: returned true
D/WifiNative-wlan0( 1031): doBoolean: DRIVER RXFILTER-START
I/wpa_supplicant( 6323): wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
D/WifiNative-wlan0( 1031): DRIVER RXFILTER-START: returned true
V/Avrcp   ( 6290): make
D/Avrcp   ( 6290): [BTUI] Use Native AVRCP : init jni
I/bluedroid-qcom( 6290): get_profile_interface avrcp
E/WifiNative: ( 1031): [164,665,385 us] RECONNECT  stack:logDbg - reconnect - enter - invokeEnterMethods - performTransitions
D/WifiNative-wlan0( 1031): doBoolean: RECONNECT
D/WifiNative-wlan0( 1031): RECONNECT: returned true
D/WifiNative-wlan0( 1031): doString: [STATUS]
D/WifiNative-wlan0( 1031):    returned wpa_state=SCANNING p2p_device_address=02:9a:02:7b:60:ac address=c4:9a:02:7b:60:ac uuid=530d3fd0-1ba3-5409-a336-ff4e42af59a2
D/WifiNative-wlan0( 1031): doBoolean: DRIVER SETSUSPENDMODE 1
I/wpa_supplicant( 6323): wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 1
D/WifiMonitor( 1031): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
E/WifiMonitor( 1031): WifiMonitor:wlan0 cnt=1 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
D/WifiNative-wlan0( 1031): DRIVER SETSUSPENDMODE 1: returned true
D/WifiNative-wlan0( 1031): doBoolean: SET ps 1
D/WifiNative-wlan0( 1031): SET ps 1: returned true
D/LGWifiP2pService( 1031): P2pDisabledState{ when=0 what=131203 target=com.android.internal.util.StateMachine$SmHandler }
I/StatusBar.NetworkController( 1447): networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1447): mWifiConnected = false, mWifiLevel = 0
D/CommandListener(  313): Setting iface cfg
D/CommandListener(  313): Trying to bring up p2p0
D/WifiMonitor( 1031): startMonitoring(p2p0) with mConnected = true
D/LGWifiP2pService( 1031): P2pEnablingState
,D/LGWifiP2pService( 1031): P2pEnablingState{ when=-1ms what=147457 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1031): P2p socket connection successful
D/LGWifiP2pService( 1031): P2pEnabledState
D/LGWifiP2pService( 1031): sending p2p connection changed broadcast
V/WfdStateTracker( 1945): WfdStateTracker handleDirectStateChangedEvent: 2
D/WfdsService( 1945): WifiP2pState is changed : true
D/WifiHS20( 1031): hidePasspointNotification off =false
D/WfdsService( 1945): Receive the WFDS_ENABLE Method
D/WfdsService( 1945): Set the WFDS Monitor: true
D/WfdsService( 1945): Connected to the supplicant for wfds
D/WfdsJNI ( 1945): doCommand: WFDS_SET TRUE
I/wpa_supplicant( 6323): WFDS: wfds_supplicant_wfds_cmd: cmd = SET TRUE
E/BluetoothAdapterService( 6290): File transfer profiles supported!!
D/WfdsJNI ( 1945): doCommand: WFDS_GET_MAC_ADDRESS
I/wpa_supplicant( 6323): WFDS: wfds_supplicant_wfds_cmd: cmd = GET_MAC_ADDRESS
D/WfdsJNI ( 1945): doCommand: IFNAME=wlan0 GET_CAPABILITY channels
D/WfdsService( 1945): selectPreferredScanChannel [36]
D/WfdsService( 1945): STATE : WfdsEnabledState - enter: this device mac 02:9a:02:7b:60:ac
D/WifiNative-p2p0( 1031): doBoolean: SET persistent_reconnect 1
D/WifiNative-p2p0( 1031): SET persistent_reconnect 1: returned true
W/Settings( 1031): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1031): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiNative-p2p0( 1031): doBoolean: SET device_name G3-1
D/WifiOffDelayIfNotUsed( 1031): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
D/WifiNative-p2p0( 1031): SET device_name G3-1: returned true
V/AudioManager( 6290): registerRemoteController: size of Media player list: 0
D/LGWifiP2pService( 1031): [LGE_P2P] initializeP2pSettings() check postfix
D/LGWifiP2pService( 1031): before postfix = G3-1
D/WifiServerServiceExt( 1031): postfix byte check : 4
D/LGWifiP2pService( 1031): after postfix = G3-1
D/WifiNative-p2p0( 1031): doBoolean: SET p2p_ssid_postfix -G3-1
D/WifiNative-p2p0( 1031): SET p2p_ssid_postfix -G3-1: returned true
D/WifiNative-p2p0( 1031): doBoolean: SET device_type 10-0050F204-5
D/WifiNative-p2p0( 1031): SET device_type 10-0050F204-5: returned true
D/WifiNative-p2p0( 1031): doBoolean: SET config_methods virtual_push_button physical_display keypad
D/WifiNative-p2p0( 1031): SET config_methods virtual_push_button physical_display keypad: returned true
D/WifiNative-p2p0( 1031): doBoolean: P2P_SET conc_pref p2p
D/WfdsService( 1945): WIFI_P2P_CONNECTION_CHANGED_ACTION
D/WifiScanningService( 1031): SCAN_AVAILABLE : 3
D/WifiScanningService( 1031): DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
D/WfdsService( 1945): isConnected: false
D/RttService( 1031): SCAN_AVAILABLE : 3
D/StatusBar.NetworkController( 1447): refreshViews: Data not connected!! Set no data type icon / Roaming
E/WifiStateMachine( 1031):  DisconnectedState CMD_SET_OPERATIONAL_MODE 1 0
E/WifiStateMachine( 1031):  DisconnectedState CMD_START_DRIVER 0 0
E/WifiStateMachine( 1031):  ConnectModeState CMD_START_DRIVER 0 0
E/WifiStateMachine( 1031):  DriverStartedState CMD_START_DRIVER 0 0
I/WifiNative-HAL( 1031): startHal
D/RttService( 1031): DefaultState got{ when=-4ms what=160512 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-p2p0( 1031): P2P_SET conc_pref p2p: returned true
E/wifi    ( 1031): getStaticLongField sWifiHalHandle 0x97b2199c
E/WifiHAL ( 1031): Could not connect handle
D/wifi    ( 1031): halHandle = 0x0, mVM = 0xb487c280, mCls = 0x601566
I/WifiNative-HAL( 1031): Could not start hal
,E/WifiScanningService( 1031): could not start HAL
D/WifiNative-HAL( 1031): p2pGetDeviceAddress
D/WifiNative-HAL( 1031): p2pGetDeviceAddress returning 02:9a:02:7b:60:ac
D/LGWifiP2pService( 1031): DeviceAddress: 02:9a:02:7b:60:ac
D/WifiNative-p2p0( 1031): doBoolean: P2P_FLUSH
I/WfdStateTracker( 1945): handleP2pThisDeviceChanged
D/WfdsService( 1945): WIFI_P2P_THIS_DEVICE_CHANGED_ATCION
D/WfdsService( 1945): Update P2p Interface State: 3
D/WifiNative-p2p0( 1031): P2P_FLUSH: returned true
D/WifiNative-p2p0( 1031): doBoolean: P2P_SERVICE_FLUSH
,E/WifiStateMachine( 1031):  DisconnectedState what:132106 1 0
D/WifiNative-p2p0( 1031): P2P_SERVICE_FLUSH: returned true
D/WifiNative-p2p0( 1031): doString: [LIST_NETWORKS]
E/WifiStateMachine( 1031):  ConnectModeState what:132106 1 0
D/WifiNative-p2p0( 1031):    returned network id / ssid / bssid / flags
E/WifiStateMachine( 1031):  DriverStartedState what:132106 1 0
D/WifiNative-p2p0( 1031): doBoolean: SAVE_CONFIG
I/WifiServerServiceExt( 1031): setWifiDualbandAPConnection band : 1
E/wpa_supplicant( 6323): nWIFIDualbandAPConnection: 1
D/WifiNative-p2p0( 1031): SAVE_CONFIG: returned true
D/LGWifiP2pService( 1031): sending p2p persistent groups changed broadcast
E/WifiStateMachine( 1031):  DisconnectedState what:132096 -100 0
D/LGWifiP2pService( 1031): InactiveState
D/LGWifiP2pService( 1031): InactiveState{ when=-10ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1031): P2pEnabledState{ when=-10ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
E/WifiStateMachine( 1031):  ConnectModeState what:132096 -100 0
,D/WifiNative-p2p0( 1031): doBoolean: DRIVER COUNTRY CZ
E/WifiStateMachine( 1031):  DriverStartedState what:132096 -100 0
I/wpa_supplicant( 6323): wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
I/WifiServerServiceExt( 1031): set CMD_DISCONNECT_RSSI_LVL : -100
I/wpa_supplicant( 6323): p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
D/WifiMonitor( 1031): Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
I/wpa_supplicant( 6323): [LGE_PATCH] driver_cmd() country:CZ
E/WifiMonitor( 1031): WifiMonitor:p2p0 cnt=2 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
E/wpa_supplicant( 6323): disconnect_rssi_lvl: -100
E/WifiMonitor( 1031): handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
E/WifiMonitor( 1031): handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
I/wpa_supplicant( 6323): p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
I/wpa_supplicant( 6323): p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
,D/WfdsMonitor( 1945): Event [CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
D/WfdsMonitor( 1945): Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
D/WfdsMonitor( 1945): Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
D/WifiMonitor( 1031): Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
E/WifiMonitor( 1031): WifiMonitor:p2p0 cnt=3 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
E/WifiMonitor( 1031): handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
E/WifiMonitor( 1031): handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
D/WifiMonitor( 1031): Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
E/WifiMonitor( 1031): WifiMonitor:p2p0 cnt=4 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
E/WifiMonitor( 1031): handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
E/WifiMonitor( 1031): handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
D/WifiNative-p2p0( 1031): DRIVER COUNTRY CZ: returned true
D/LGWifiP2pService( 1031): InactiveState{ when=-4ms what=139287 arg2=1 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1031): P2pEnabledState{ when=-4ms what=139287 arg2=1 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1031): DefaultState{ when=-4ms what=139287 arg2=1 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1031): InactiveState{ when=-4ms what=139283 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1031): P2pEnabledState{ when=-4ms what=139283 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1031): DefaultState{ when=-4ms what=139283 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiServerServiceExt( 1031): No p2p device connected
E/WifiStateMachine( 1031):  DisconnectedState CMD_SET_COUNTRY_CODE 1 0 cz
E/WifiStateMachine( 1031):  ConnectModeState CMD_SET_COUNTRY_CODE 1 0 cz
E/WifiStateMachine( 1031):  DriverStartedState CMD_SET_COUNTRY_CODE 1 0 cz
D/WifiNative-wlan0( 1031): doBoolean: DRIVER COUNTRY CZ
I/wpa_supplicant( 6323): wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
I/wpa_supplicant( 6323): wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
D/WifiMonitor( 1031): Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
I/wpa_supplicant( 6323): [LGE_PATCH] driver_cmd() country:CZ
E/WifiMonitor( 1031): WifiMonitor:wlan0 cnt=5 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
I/wpa_supplicant( 6323): p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
E/WifiMonitor( 1031): handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
E/WifiMonitor( 1031): handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
D/WifiMonitor( 1031): Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
E/WifiMonitor( 1031): WifiMonitor:p2p0 cnt=6 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
E/WifiMonitor( 1031): handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
E/WifiMonitor( 1031): handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
D/WifiNative-wlan0( 1031): DRIVER COUNTRY CZ: returned true
I/wpa_supplicant( 6323): p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
D/WifiMonitor( 1031): Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
E/WifiMonitor( 1031): WifiMonitor:p2p0 cnt=7 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
E/WifiMonitor( 1031): handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
E/WifiMonitor( 1031): handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
D/LGWifiP2pService( 1031): InactiveState{ when=0 what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1031): P2pEnabledState{ when=0 what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
D/WfdsMonit,or( 1945): Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
D/WfdsMonitor( 1945): Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
E/WifiStateMachine( 1031):  DisconnectedState CMD_SET_FREQUENCY_BAND 0 0
E/WifiStateMachine( 1031):  ConnectModeState CMD_SET_FREQUENCY_BAND 0 0
E/WifiStateMachine( 1031):  DriverStartedState CMD_SET_FREQUENCY_BAND 0 0
D/WifiNative-wlan0( 1031): doBoolean: DRIVER SETBAND 0
I/wpa_supplicant( 6323): wpa_driver_nl80211_ext_driver_cmd SETBAND 0 - interface name wlan0
I/wpa_supplicant( 6323): wlan0: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
D/WifiMonitor( 1031): Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN]
E/WifiMonitor( 1031): WifiMonitor:wlan0 cnt=8 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
E/WifiMonitor( 1031): handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
E/WifiMonitor( 1031): handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
D/WifiNative-wlan0( 1031): DRIVER SETBAND 0: returned true
D/WifiNative-wlan0( 1031): doBoolean: BSS_FLUSH 0
D/WifiNative-wlan0( 1031): BSS_FLUSH 0: returned true
D/WifiNative-wlan0( 1031): doBoolean: SCAN
D/WifiNative-wlan0( 1031): SCAN: returned false
E/WifiStateMachine( 1031):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 1 0 rt=164725  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
I/StatusBar.NetworkController( 1447): networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1447): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1447): refreshViews: Data not connected!! Set no data type icon / Roaming
,E/WifiStateMachine( 1031):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 1 0 rt=164729  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
E/WifiStateMachine( 1031):  DisconnectedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
E/WifiStateMachine( 1031):  ConnectModeState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
E/WifiStateMachine( 1031):  DriverStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
E/WifiStateMachine( 1031):  SupplicantStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
W/Settings( 1031): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1031): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1031): NETWORK_STATE_CHANGED_ACTION [SCANNING]
E/WifiStateMachine( 1031):  DefaultState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
D/WifiServerServiceExt( 1031): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1031): setSupplicantStateSCANNING
I/art     ( 1031): Explicit concurrent mark sweep GC freed 36725(1790KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 43MB/65MB, paused 1.480ms total 97.862ms
E/AudioManager( 6290): No RCC entry present to update
E/RemoteController( 6290): Cannot set synchronization mode on an unregistered RemoteController
I/BluetoothAvrcpQcomServiceJni( 6290): classInitQcomNative: succeeds
,D/LGBluetoothAvrcpQcomAdapter( 6290): [BTUI] Use QCOM AVRCP 1.5 : init jni, browsing = false
I/BluetoothAvrcpQcomServiceJni( 6290): initQcomNative: succeeds
D/LGWifiP2pService( 1031): InactiveState{ when=0 what=139287 arg2=1 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1031): P2pEnabledState{ when=0 what=139287 arg2=1 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1031): DefaultState{ when=0 what=139287 arg2=1 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiService( 1031): New client listening to asynchronous messages
D/LGWifiP2pService( 1031): InactiveState{ when=0 what=139285 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1031): P2pEnabledState{ when=0 what=139285 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1031): DefaultState{ when=0 what=139285 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
W/WfdsService( 1945): DefaultState - msg [9441285] is not handled
E/BluetoothAdapterService( 6290): File transfer profiles supported!!
D/LGBluetoothAvrcpQcomAdapter( 6290): [BTUI] [+] updateMediaPlayerInfo
E/BluetoothAdapterService( 6290): File transfer profiles supported!!
E/ActivityThread( 6357): Failed to find provider info for com.lge.lgaccount.provider
,W/LG Account v2.2( 6357): No ProfileInfo entries
I/LG Account v2.2( 6357): isEnabled: false
I/Feature ( 6357): [Lifetracker]ver: 4.21.112(40211120)
I/Feature ( 6357): [Lifetracker]Country: EU
I/Feature ( 6357): [Lifetracker]Operator: OPEN
I/Feature ( 6357): [Lifetracker]Ranking support: false
V/LGMDMManager( 6290): Create singleton instance
I/Feature ( 6357): [Lifetracker]Comfort support: false
I/Feature ( 6357): [Lifetracker]Accessory: true
I/Feature ( 6357): [Lifetracker]Health device: true
I/Feature ( 6357): [Lifetracker]Extra Pedometer: false
I/Feature ( 6357): [Lifetracker]Blood glucose device: false
I/Feature ( 6357): [Lifetracker]Device Number: 3
I/BluetoothAdapterState( 6290): Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
D/BluetoothPermissionRequest( 6324): onReceive
D/LGBluetoothFeatureConfig( 6324):  get() - isFeatureLoaded : false
,V/SIM_STK ( 1031): Menu title from STK is T-Mobile
V/SIM_STK ( 1031): Menu title from STK is T-Mobile
,I/ActivityManager( 1031): Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=6403 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,D/BluetoothManagerService( 1031): Message: 20
D/BluetoothManagerService( 1031): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@85c34b4:true
I/art     (  344): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 276us total 12.819ms
V/FormManager( 6376): Network unavailable.
V/FormManager( 6376): Network unavailable.
,I/art     (  344): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 225us total 10.997ms
W/FormManager( 6376): Network not available. Please check & try again.
D/LGBluetoothResetSettingReceiver( 6324): return without doing reset settings.
I/ActivityManager( 1031): Killing 5953:com.google.android.partnersetup/u0a8 (adj 15): empty #17
I/art     (  344): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 244us total 10.507ms
,W/ActivityManager( 1031): getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
,W/libprocessgroup( 1031): failed to open /acct/uid_10008/pid_5953/cgroup.procs: No such file or directory
I/ActivityManager( 1031): Killing 5552:com.lge.appbox.client/u0a11 (adj 15): empty #17
D/LGBluetoothAvrcpQcomAdapter( 6290): [BTUI] installed app name: Music
,D/LGBluetoothAvrcpQcomAdapter( 6290): [BTUI] installed app name: Google Play Music
D/LGBluetoothAvrcpQcomAdapter( 6290): [BTUI] === MediaPlayerInfo (playerId:0) ===
D/LGBluetoothAvrcpQcomAdapter( 6290): [BTUI]          displayName: Music
D/LGBluetoothAvrcpQcomAdapter( 6290): [BTUI]          packageName: com.lge.music
D/LGBluetoothAvrcpQcomAdapter( 6290): [BTUI]          playState: 2 (PAUSED)
D/LGBluetoothAvrcpQcomAdapter( 6290): [BTUI] === MediaPlayerInfo (playerId:1) ===
D/LGBluetoothAvrcpQcomAdapter( 6290): [BTUI]          displayName: Google Play Music
D/LGBluetoothAvrcpQcomAdapter( 6290): [BTUI]          packageName: com.google.android.music
D/LGBluetoothAvrcpQcomAdapter( 6290): [BTUI]          playState: 2 (PAUSED)
D/LGBluetoothAvrcpQcomAdapter( 6290): [BTUI] [-] updateMediaPlayerInfo
I/BluetoothA2dpServiceJni( 6290): classInitNative
I/BluetoothA2dpServiceJni( 6290): classInitNative: succeeds
D/A2dpStateMachine( 6290): make
I/bluedroid-qcom( 6290): get_profile_interface a2dp
I/GKI_LINUX( 6290): gki_task_entry task_id=2 [A2DP-MEDIA] starting
I/LGBluetoothA2dpServiceJni( 6290): classInitNative: succeeds
I/LGBluetoothA2dpAdapter( 6290): [BTUI] getInstance : create [LGBluetoothA2dpAdapter]
D/BluetoothAdapterService( 6290): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2076f544
D/A2dpStateMachine( 6290): Enter Disconnected: -2
I/BluetoothHidServiceJni( 6290): classInitNative: succeeds
D/PCSuite ( 6403): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,D/HidService( 6290): Received start request. Starting profile...
I/bluedroid-qcom( 6290): get_profile_interface hidhost
D/BluetoothAdapterService( 6290): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2076f544
D/HeadsetStateMachine( 6290): Proxy object connected
D/LGBluetoothHfpAdapter( 6290): [BTUI] queryPhoneState
D/LGBluetoothHfpAdapter( 6290): Try to query the phonestate on bind
D/BluetoothPhoneService.BluetoothLTECall( 1850):  call mBluetoothHeadset.phoneStateChanged()
W/BluetoothHeadset( 1850): Proxy not attached to service
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
D/BluetoothAdapterService( 6290): Profile still not running:com.android.bluetooth.gatt.GattService
I/BluetoothHealthServiceJni( 6290): classInitNative: succeeds
D/HealthService( 6290): Received start request. Starting profile...
I/bluedroid-qcom( 6290): get_profile_interface health
I/LGBluetoothHealthServiceJni( 6290): classInitNative: succeeds
D/BluetoothAdapterService( 6290): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2076f544
I/BluetoothPanServiceJni( 6290): classInitNative(L105): succeeds
D/HeadsetStateMachine( 6290): Disconnected process message: 10, size: 0
D/PanService( 6290): Received start request. Starting profile...
D/BluetoothPanServiceJni( 6290): initializeNative(L110): pan
I/bluedroid-qcom( 6290): get_profile_interface pan
D/HeadsetPhoneState( 6290): sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
,D/HeadsetStateMachine( 6290): Disconnected process message: 11, size: 0
W/libprocessgroup( 1031): failed to open /acct/uid_10011/pid_5552/cgroup.procs: No such file or directory
,I/LGBluetoothPanAdapter( 6290): [BTUI] getInstance : create [LGBluetoothPanAdapter]
D/BluetoothAdapterService( 6290): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2076f544
I/BtGatt.JNI( 6290): classInitNative(L901): classInitNative: Success!
D/BtGatt.DebugUtils( 6290): handleDebugAction() action=null
D/BtGatt.GattService( 6290): Received start request. Starting profile...
D/BtGatt.GattService( 6290): start()
I/bluedroid-qcom( 6290): get_profile_interface gatt
D/BtGatt.AdvertiseManager( 6290): advertise manager created
E/WifiMonitor( 1031): WifiMonitor:wlan0 cnt=9 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
E/WifiMonitor( 1031): handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
D/WifiMonitor( 1031): Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
E/WifiMonitor( 1031): WifiMonitor:wlan0 cnt=10 dispatchEvent: WPS-AP-AVAILABLE 
E/wpa_supplicant( 6323): USIM:  scard_init function
I/wpa_supplicant( 6323): Trying to associate with SSID 'NG700'
W/WifiMonitor( 1031): couldn't identify event type - WPS-AP-AVAILABLE 
E/WifiStateMachine( 1031):  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=0 bcn=0
D/WifiMonitor( 1031): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
E/WifiMonitor( 1031): WifiMonitor:wlan0 cnt=11 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
E/WifiStateMachine( 1031):  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=0 bcn=0
E/WifiStateMachine( 1031):  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=0 bcn=0
E/WifiStateMachine( 1031):  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=0 bcn=0
I/WifiNative-HAL( 1031): startHal
E/wifi    ( 1031): getStaticLongField sWifiHalHandle 0x989418cc
E/WifiHAL ( 1031): Could not connect handle
D/wifi    ( 1031): halHandle = 0x0, mVM = 0xb487c280, mCls = 0x2021b6
I/WifiNative-HAL( 1031): Could not start hal
D/WifiNative-wlan0( 1031): doString: [BSS RANGE=0- MASK=0x21987]
D/BluetoothAdapterService( 6290): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2076f544
,E/WifiStateMachine( 1031):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 11 0 rt=165034  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
D/BluetoothAdapterService( 6290): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2076f544
I/LGBluetoothMapAdapter( 6290): [BTUI] getInstance : create [LGBluetoothMapAdapter]
I/StatusBar.NetworkController( 1447): networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1447): mWifiConnected = false, mWifiLevel = 0
V/BluetoothMapService( 6290): BluetoothMapBinder()
D/StatusBar.NetworkController( 1447): refreshViews: Data not connected!! Set no data type icon / Roaming
D/BluetoothMapService( 6290): Received start request. Starting profile...
D/BluetoothMapService( 6290): start()
W/Settings( 1031): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1031): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1031): NETWORK_STATE_CHANGED_ACTION [SCANNING]
E/WifiStateMachine( 1031):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 11 0 rt=165039  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
I/StatusBar.NetworkController( 1447): networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1447): mWifiConnected = false, mWifiLevel = 0
W/Settings( 1031): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1031): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1031): NETWORK_STATE_CHANGED_ACTION [CONNECTING]
D/WifiServerServiceExt( 1031): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1031): setSupplicantStateASSOCIATING
D/BluetoothMapEmailSettingsLoader( 6290): Found 0 applications
D/StatusBar.NetworkController( 1447): refreshViews: Data not connected!! Set no data type icon / Roaming
D/BluetoothMapEmailAppObserver( 6290): createReceiver()
D/BluetoothMapEmailAppObserver( 6290): initObservers()
D/BluetoothMapEmailAppObserver( 6290): getEnabledAccountItems()
V/WiFiOffLoadBroadcast( 6324): WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,D/BluetoothAdapterService( 6290): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2076f544
D/WifiService( 1031): New client listening to asynchronous messages
D/LGBluetoothOppAdapter( 6290): [BTUI] getInstance : create [LGBluetoothOppAdapter]
D/BluetoothAdapterService( 6290): Profile still not running:com.android.bluetooth.gatt.GattService
D/BluetoothAdapterService( 6290): Profile still not running:com.android.bluetooth.gatt.GattService
,D/BluetoothAdapterService( 6290): Profile still not running:com.android.bluetooth.gatt.GattService
,V/PanService( 6290): [BTUI] SIM Extra State :ABSENT
D/BluetoothAdapterService( 6290): Profile still not running:com.android.bluetooth.gatt.GattService
D/BluetoothAdapterService( 6290): Profile still not running:com.android.bluetooth.map.BluetoothMapService
V/BluetoothMapService( 6290): Handler(): got msg=1
D/BluetoothAdapterState( 6290): CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
I/bluedroid-qcom( 6290): enable
I/GKI_LINUX( 6290): gki_task_entry task_id=0 [BTU] starting
I/bt-btu  ( 6290): btu_task pending for preload complete event
I/bt_hci_bdroid( 6290): init
V/BluetoothFtpReceiver( 6290): BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
,I/bt_vendor( 6290): bt-vendor : init
I/bt_vendor( 6290): bt-vendor : get_bt_soc_type
E/bt_vendor( 6290): get_bt_soc_type: Failed to get soc type
I/bt_vendor( 6290): init: Local BD Address : c0:64:73:54:3f:58
D/bt_userial_mct( 6290): userial_init
V/BluetoothSapReceiver( 6290): [BTUI] checkServiceStart
D/bt_hci_bdroid( 6290): set_power 1
I/bt_vendor( 6290): bt-vendor : BT_VND_OP_POWER_CTRL: On
W/sh      ( 6437): type=1400 audit(0.0:155): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
I/bt_vendor( 6290): Starting hciattach daemon
I/bt_vendor( 6290): try to set true
V/BluetoothSapReceiver( 6290): [BTUI] region:EU country:EU
W/sh      ( 6437): type=1400 audit(0.0:156): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
V/BluetoothSapReceiver( 6290): SapReceiver onReceive 
V/BluetoothSapReceiver( 6290): action = android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothSapReceiver( 6290):  Bluetooth Adapter state = 11
D/LgDataFeature( 6324): LgDataFeature() Constructor: none
D/LgDataFeature( 6324): LgDataFeature() Constructor Done, null
,D/WiFiOffLoadUpdatePriority( 6324): remove : truetruetrue
E/WifiStateMachine( 1031):  DisconnectedState CMD_GET_CONFIGURED_NETWORKS uid=1000 1000 0 num=1
I/qcom-bluetooth( 6438): /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  
E/WifiStateMachine( 1031):  ConnectModeState CMD_GET_CONFIGURED_NETWORKS uid=1000 1000 0 num=1
E/WifiStateMachine( 1031):  DisconnectedState CMD_SAVE_CONFIG uid=1000 0 0
E/WifiStateMachine( 1031):  ConnectModeState CMD_SAVE_CONFIG uid=1000 0 0
D/WifiNative-wlan0( 1031): doBoolean: SAVE_CONFIG
,D/WifiNative-wlan0( 1031): SAVE_CONFIG: returned true
D/WiFiOffLoadUpdatePriority( 6324): remove1
V/WiFiOffLoadSharedPrefsUtils( 6324): save remove
D/WiFiOffLoadBroadcast( 6324): mLastConnectedNetwork from SharedPrefsUtils for wifioffloading : null
D/WiFiOffLoadBroadcast( 6324): S: false, R: false
,E/WifiStateMachine( 1031):  DisconnectedState CMD_GET_CONFIGURED_NETWORKS uid=1000 1000 0 num=1
E/WifiStateMachine( 1031):  ConnectModeState CMD_GET_CONFIGURED_NETWORKS uid=1000 1000 0 num=1
D/WiFiOffLoadUpdatePriority( 6324): saved SSID: "NG700"
D/WiFiOffLoadUpdatePriority( 6324): connected SSID: null
D/WiFiOffLoadUpdatePriority( 6324): private wpa: "NG700" 300
I/ActivityManager( 1031): Start proc com.lge.settings.easy for broadcast com.lge.settings.easy/com.lge.settings.bluetooth.LGBluetoothProfileConnectionReceiver: pid=6442 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
D/WifiServiceImplEx( 1031): addOrUpdateNetwork pid=6324, uid=1000, packageName=android.uid.system:1000
E/addOrUpdateNetwork( 1031):  uid = 1000 SSID "NG700" nid=0
E/WifiStateMachine( 1031):  DisconnectedState CMD_ADD_OR_UPDATE_NETWORK uid=1000 0 0 "NG700"WPA_PSK prio=300 status=2
E/WifiStateMachine( 1031):  ConnectModeState CMD_ADD_OR_UPDATE_NETWORK uid=1000 0 0 "NG700"WPA_PSK prio=300 status=2
E/WifiConfigStore( 1031):  key="NG700"WPA_PSK netId=0 uid=0/1000
D/WifiServerServiceExt( 1031): addOrUpdateNetwork: mThisIsFirstEnableing = false
D/WifiNative-wlan0( 1031): doBoolean: SET_NETWORK 0 ssid 4e47373030
D/Tethering( 1031): sendTetherStateChangedBroadcast 1, 0, 0
,D/WifiNative-wlan0( 1031): SET_NETWORK 0 ssid 4e47373030: returned true
D/WifiNative-wlan0( 1031): doBoolean: SET_NETWORK 0 key_mgmt WPA-PSK
,I/qcom-bluetooth( 6462): /system/etc/init.qcom.bt.sh: Transport : smd 
D/WifiMonitor( 1031): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
E/WifiMonitor( 1031): WifiMonitor:wlan0 cnt=12 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
I/wpa_supplicant( 6323): wlan0: Associated with c0:ff:d4:d3:aa:48
D/WifiMonitor( 1031): Event [IFNAME=wlan0 Associated with c0:ff:d4:d3:aa:48]
E/WifiMonitor( 1031): WifiMonitor:wlan0 cnt=13 dispatchEvent: Associated with c0:ff:d4:d3:aa:48
D/WifiMonitor( 1031): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1031): WifiMonitor:wlan0 cnt=14 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/WifiNative-wlan0( 1031): SET_NETWORK 0 key_mgmt WPA-PSK: returned true
D/WifiNative-wlan0( 1031): doBoolean: SET_NETWORK 0 proto WPA RSN
D/WifiNative-wlan0( 1031): SET_NETWORK 0 proto WPA RSN: returned true
D/WifiNative-wlan0( 1031): doBoolean: SET_NETWORK 0 pairwise TKIP CCMP
D/WifiNative-wlan0( 1031): SET_NETWORK 0 pairwise TKIP CCMP: returned true
D/WifiNative-wlan0( 1031): doBoolean: SET_NETWORK 0 group WEP40 WEP104 TKIP CCMP
D/WifiNative-wlan0( 1031): SET_NETWORK 0 group WEP40 WEP104 TKIP CCMP: returned true
D/WifiNative-wlan0( 1031): doBoolean: SET_NETWORK 0 priority 300
D/WifiNative-wlan0( 1031): SET_NETWORK 0 priority 300: returned true
E/WifiConfigStore( 1031): will read network variables netId=0
I/qcom-bluetooth( 6463): /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
D/WifiMonitor( 1031): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1031): WifiMonitor:wlan0 cnt=15 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
I/wpa_supplicant( 6323): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 6323): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
D/WifiMonitor( 1031): Event [IFNAME=wlan0 WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]]
E/WifiMonitor( 1031): WifiMonitor:wlan0 cnt=16 dispatchEvent: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
W/WifiMonitor( 1031): couldn't identify event type - WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
D/WifiMonitor( 1031): Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]]
E/WifiMonitor( 1031): WifiMonitor:wlan0 cnt=17 dispatchEvent: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
E/WifiMonitor( 1031): handleEvent 1  Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
D/WifiMonitor( 1031): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1031): WifiMonitor:wlan0 cnt=18 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
E/WifiConfigStore( 1031): writeIpAndProxyConfigurationsOnChange: "NG700" -> "NG700" path: /data/misc/wifi/ipconfig.txt
E/WifiConfigStore( 1031):  writeKnownNetworkHistory() num networks:1 needWrite=false
,E/WifiStateMachine( 1031):  DisconnectedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1031):  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1031):  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1031):  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1031):  DefaultState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1031):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 12 0 rt=165174  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
D/WiFiOffLoadUpdatePriority( 6324):  ssid "NG700" prio 300
D/WiFiOffLoadUpdatePriority( 6324): configuration updated: 0
E/WifiStateMachine( 1031):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 12 0 rt=165174  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
E/WifiStateMachine( 1031):  DisconnectedState CMD_ASSOCIATED_BSSID 13 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=165175
E/WifiStateMachine( 1031):  ConnectModeState CMD_ASSOCIATED_BSSID 13 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=165175
E/WifiStateMachine( 1031):  DriverStartedState CMD_ASSOCIATED_BSSID 13 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=165175
E/WifiStateMachine( 1031):  SupplicantStartedState CMD_ASSOCIATED_BSSID 13 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=165176
E/WifiStateMachine( 1031):  DefaultState CMD_ASSOCIATED_BSSID 13 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=165176
E/WifiStateMachine( 1031):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 14 0 rt=165176  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: FOUR_WAY_HANDSHAKE
I/StatusBar.NetworkController( 1447): networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1447): mWifiConnected = false, mWifiLevel = 0
W/Settings( 1031): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1031): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1031): NETWORK_STATE_CHANGED_ACTION [CONNECTING]
I/qcom-bluetooth( 6465): /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
E/WifiStateMachine( 1031):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 14 0 rt=165180  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: FOUR_WAY_HANDSHAKE
D/StatusBar.NetworkController( 1447): refreshViews: Data not connected!! Set no data type icon / Roaming
W/Settings( 1031): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1031): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1031): NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
E/WifiStateMachine( 1031):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 15 0 rt=165183  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: GROUP_HANDSHAKE
E/WifiStateMachine( 1031):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 15 0 rt=165183  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: GROUP_HANDSHAKE
,E/WifiStateMachine( 1031):  DisconnectedState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=165183
E/WifiStateMachine( 1031):  ConnectModeState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=165184
D/WifiNative-wlan0( 1031): doString: [STATUS]
I/StatusBar.NetworkController( 1447): networkInfo=[type: WIFI[], state: CONNECTING/AUTHENTICATING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1447): mWifiConnected = false, mWifiLevel = 0
D/WifiMonitor( 1031): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1031): WifiMonitor:wlan0 cnt=19 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
W/ResourcesManager( 6442): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
D/WifiNative-wlan0( 1031):    returned bssid=c0:ff:d4:d3:aa:48 ssid=NG700 id=0 mode=station pairwise_cipher=CCMP group_cipher=CCMP key_mgmt=WPA2-PSK wpa_state=COMPLETED p2p_device_address=02:9a:02:7b:60:ac address=c4:9a:02:7b:60:ac uuid=530d3fd0-1ba3-5409-a336-ff4e42af59a2
I/qcom-bluetooth( 6466): /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> 
I/WifiServiceExtension( 1031): setVHTCapabilityType  : false
D/StatusBar.NetworkController( 1447): refreshViews: Data not connected!! Set no data type icon / Roaming
I/qcom-bluetooth( 6467): /system/etc/init.qcom.bt.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
I/ActivityManager( 1031): Killing 5573:com.android.contacts/u0a19 (adj 15): empty #17
,I/qcom-bluetooth( 6468): /system/etc/init.qcom.bt.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> 
,I/libmdmdetect( 6470): ESOC framework not supported
E/Diag_Lib( 6470):  Diag_LSM_Init: Failed to open handle to diag driver, error = 13
,D/bthci_qcomm_linux( 6470): [BTUI] bt_hci_qcomm_pfal_get_bdaddress: Get BDADDR from bluedroid prop (58:3F:54:73:64:C0)
D/bthci_qcomm_common( 6470): [BTUI] bt_hci_qcomm_init:
D/bthci_qcomm_common( 6470): [BTUI]     BDADDR: 58:3F:54:73:64:C0
D/bthci_qcomm_common( 6470): [BTUI]     BR/EDR: Class 1
D/bthci_qcomm_common( 6470): [BTUI]     LE: Class 2
D/bthci_qcomm_common( 6470): [BTUI]     Ref Clock: 32M
D/btqsocnvmtags( 6470): [BTUI] init_riva_entries: set NORMAL power settings
D/AuthorizationBluetoothService( 2112): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
I/WifiServerServiceExt( 1031): wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
,I/WifiServerServiceExt( 1031): setKeepAlivePacketInterval msec : 60
W/libprocessgroup( 1031): failed to open /acct/uid_10019/pid_5573/cgroup.procs: No such file or directory
,I/StatusBar.NetworkController( 1447): networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1447): mWifiConnected = false, mWifiLevel = 0
W/Settings( 1031): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1031): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1031): NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
D/StatusBar.NetworkController( 1447): refreshViews: Data not connected!! Set no data type icon / Roaming
I/StatusBar.NetworkController( 1447): networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1447): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1447): refreshViews: Data not connected!! Set no data type icon / Roaming
W/Settings( 1031): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1031): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1031): NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
V/AlarmManager( 1031): ELAPSED_WAKEUP set : Alarm{19dc184e type 2 when 160512 com.google.android.gms} when 160512
D/ConnectivityService( 1031): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
,D/ConnectivityService( 1031): Got NetworkAgent Messenger
D/ConnectivityService( 1031): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
D/ConnectivityService( 1031): NetworkAgent connected
E/WifiConfigStore( 1031): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/WifiNative-wlan0( 1031): doBoolean: SET_NETWORK 0 bssid any
D/WifiNative-wlan0( 1031): SET_NETWORK 0 bssid any: returned true
D/WifiNative-wlan0( 1031): doBoolean: SAVE_CONFIG
D/WifiNative-wlan0( 1031): SAVE_CONFIG: returned true
E/WifiConfigStore( 1031): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/WifiNative-wlan0( 1031): doBoolean: SET_NETWORK 0 bssid any
D/WifiNative-wlan0( 1031): SET_NETWORK 0 bssid any: returned true
D/WifiNative-wlan0( 1031): doBoolean: SAVE_CONFIG
D/WifiNative-wlan0( 1031): SAVE_CONFIG: returned true
,D/CommandListener(  313): Setting iface cfg
D/DhcpStateMachine( 1031): StoppedState
E/WifiStateMachine( 1031): Start Dhcp Watchdog 1
D/DhcpStateMachine( 1031): StoppedState{ when=0 what=196609 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine( 1031): WaitBeforeStartState
E/WifiStateMachine( 1031):  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 18 0 rt=165269  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine( 1031):  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 18 0 rt=165270  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine( 1031):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 18 0 rt=165271  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
D/WifiServerServiceExt( 1031): SUPPLICANT_STATE_CHANGED_ACTION
,D/WifiServerServiceExt( 1031): setSupplicantStateASSOCIATED
,E/WifiStateMachine( 1031):  ObtainingIpState CMD_SAVE_CONFIG uid=1000 0 0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_SAVE_CONFIG uid=1000 0 0
E/WifiStateMachine( 1031):  ConnectModeState CMD_SAVE_CONFIG uid=1000 0 0
D/WifiNative-wlan0( 1031): doBoolean: SAVE_CONFIG
I/rmt_storage(  306): rmt_storage_connect_cb: clnt_h=0x5 conn_h=0xb6403090
I/rmt_storage(  306): rmt_storage_rw_iovec_cb: /boot/modem_fs2: clnt_h=0x2: req_h=0x9 msg_id=3: R/W request received
I/rmt_storage(  306): wakelock acquired: 1, error no: 42
I/rmt_storage(  306): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 Unblock worker thread (th_id: -1236806912)
,D/WifiNative-wlan0( 1031): SAVE_CONFIG: returned true
D/WiFiOffLoadUpdatePriority( 6324): configuration saved: true
D/WifiServerServiceExt( 1031): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1031): setSupplicantStateGROUP_HANDSHAKE
,E/WifiStateMachine( 1031):  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 19 0 rt=165336  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
,E/WifiStateMachine( 1031):  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 19 0 rt=165338  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine( 1031):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 19 0 rt=165340  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
D/PCSuite ( 6403): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
E/WifiStateMachine( 1031):  ObtainingIpState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:-1598552902] from screen [on:0 period:-1598552902]
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1598552899]
I/WifiNative-HAL( 1031): startHal
E/wifi    ( 1031): getStaticLongField sWifiHalHandle 0x989418bc
E/WifiHAL ( 1031): Could not connect handle
D/wifi    ( 1031): halHandle = 0x0, mVM = 0xb487c280, mCls = 0x30211e
I/WifiNative-HAL( 1031): Could not start hal
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
V/WiFiOffLoadBroadcast( 6324): WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
W/FormManager( 6376): Network not available. Please check & try again.
,D/StatusBar.NetworkController( 1447): refreshViews: Data not connected!! Set no data type icon / Roaming
D/ConnectivityService( 1031): updateNetworkScore for NetworkAgentInfo [WIFI () - 100] to 60
E/WifiStateMachine( 1031):  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
D/WiFiOffLoadBroadcast( 6324): MCCMNC not supported: null
E/WifiStateMachine( 1031):  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1031):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1031):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
D/LGDMClient( 3941): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
D/LGDMClient( 3941): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
E/WifiStateMachine( 1031):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1031):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
W/ContextImpl( 3941): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
D/ConnectivityService( 1031): Update of LinkProperties for NetworkAgentInfo [WIFI () - 100]; created=false
W/ContextImpl( 3941): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
E/WifiStateMachine( 1031):  ObtainingIpState CMD_PRE_DHCP_ACTION 0 0 txpkts=1,0,0
V/FormManager( 6376): Network unavailable.
E/WifiStateMachine( 1031):  L2ConnectedState CMD_PRE_DHCP_ACTION 0 0 txpkts=1,0,0
D/WifiNative-wlan0( 1031): doBoolean: DRIVER SETSUSPENDMODE 0
D/PostponalbeReceiver( 5174): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,V/FormManager( 6376): Network unavailable.
D/LGDMClient( 3941): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=3, isUserType=1
D/LGDMClient( 3941): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
D/LGDMClient( 3941): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
I/wpa_supplicant( 6323): wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 0
D/WifiNative-wlan0( 1031): DRIVER SETSUSPENDMODE 0: returned true
D/WifiNative-wlan0( 1031): doBoolean: SET ps 0
D/WifiNative-wlan0( 1031): SET ps 0: returned true
D/WifiNative-wlan0( 1031): doBoolean: DRIVER BTCOEXMODE 1
I/wpa_supplicant( 6323): wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 1
D/WifiNative-wlan0( 1031): DRIVER BTCOEXMODE 1: returned true
E/WifiStateMachine( 1031): CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
D/LGWifiP2pService( 1031): InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@606f344 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1031): P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@606f344 target=com.android.internal.util.StateMachine$SmHandler }
V/DhcpStateMachine( 1031): Current State is mWaitBeforeStartState.
D/DhcpStateMachine( 1031): WaitBeforeStartState{ when=0 what=196615 target=com.android.internal.util.StateMachine$SmHandler }
V/LgDhcpStateMachineHelper( 1031): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
V/LgDhcpStateMachineHelper( 1031): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700" is not exist.
D/DhcpStateMachine( 1031): DHCP Start wake lock is acquired.
D/WifiServerServiceExt( 1031): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1031): setSupplicantStateCOMPLETED
I/PCSuite ( 6403): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
,D/WifiServerServiceExt( 1031): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1031): setSupplicantStateCOMPLETED
D/PCSuite ( 6403): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 6403): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
I/rmt_storage(  306): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0x9 msg_id=3: Bytes written = 1572864
I/rmt_storage(  306): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0x9 msg_id=3: Send response: res=0 err=0
I/rmt_storage(  306): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 About to block rmt_storage client thread (th_id: -1236806912) wakelock released: 1, error no: 0
I/rmt_storage(  306): 
V/WiFiOffLoadBroadcast( 6324): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
I/rmt_storage(  306): rmt_storage_disconnect_cb: clnt_h=0x0x5 conn_h=0x0xb6403090
E/Diag_Lib(  898): [IMS_FATAL]| 3347 | 907 |ims-rtp-daemon ims_rtp_qmi_handler_thread_func waiting on select thread>
D/WiFiOffLoadBroadcast( 6324): MCCMNC not supported: null
,I/ActivityManager( 1031): Start proc com.lge.qremote for broadcast com.lge.qremote/.settings.WiFiStateReceiver: pid=6480 uid=10112 gids={50112, 9997, 1028, 1015, 3003, 3002} abi=armeabi
I/ActivityManager( 1031): Killing 5976:com.lge.email/u0a23 (adj 15): empty #17
W/libprocessgroup( 1031): failed to open /acct/uid_10023/pid_5976/cgroup.procs: No such file or directory
,W/ResourcesManager( 6480): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,D/QRemote ( 6480): [QRemoteApplication.java:230:onCreate()] oooooo QRemoteApp onCreate....
,D/DhcpStateMachine( 1031): DHCPV4 request on wlan0
,V/LgDhcpStateMachineHelper( 1031): [bssid] hash key :c0:ff:d4:d3:aa:48
D/LgDhcpStateMachineHelper( 1031): dhcp.ap.macaddress = c0:ff:d4:d3:aa:48
W/dhcpcd  ( 6497): type=1400 audit(0.0:157): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
W/dhcpcd  ( 6497): type=1400 audit(0.0:158): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
D/QRemote ( 6480): [CarrierUtils.java:858:getHardwareSettings()] oooooo qremote android.os.Build.MODEL = LG-D855
,I/QRemote ( 6480): [CarrierUtils.java:859:getHardwareSettings()] oooooo getCountry :: EU
,I/QRemote ( 6480): [CarrierUtils.java:860:getHardwareSettings()] oooooo getCarrier :: OPEN
I/QRemote ( 6480): [CarrierUtils.java:861:getHardwareSettings()] oooooo getArea :: COM
D/QRemote ( 6480): [CarrierUtils.java:862:getHardwareSettings()] oooooo Loading Config...
I/dhcpcd  ( 6497): version 5.5.6 starting
D/QRemote ( 6480): [CarrierUtils.java:876:getHardwareSettings()] oooooo qremote configuration file = R.xml.qremote_conf
E/dhcpcd  ( 6497): get_duid: m
D/dhcpcd  ( 6497): wlan0: using ClientID 01:c4:9a:02:7b:60:ac
D/dhcpcd  ( 6497): wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason PREINIT
D/QRemote ( 6480): [QRemoteApplication.java:701:updateWidget()] oooooo Widget count is [1]. send broadcast
,D/QRemote ( 6480): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,D/QRemote ( 6480): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 6480): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,D/QRemote ( 6480): [QRemoteService.java:196:onCreate()] oooooo 140526:onCreate
V/[BNRBootReceiver]( 6106): boot receiver action = android.net.wifi.p2p.CONNECTION_STATE_CHANGE
D/BNRAndroBeam( 6106): [BnR DirectBeam] Android Direct Beam(NFC) Connection changed
D/QRemote ( 6480): [QRemoteService.java:217:onStartCommand()] oooooo 140526:onStartCommand:action:action.application.oncreate. startId:1, flags:0
V/[BNRBootReceiver]( 6106): Boot Receiver Return
,D/PostponalbeReceiver( 5174): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
V/WiFiOffLoadBroadcast( 6324): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6324): MCCMNC not supported: null
D/dhcpcd  ( 6497): getUsingAPMacAddress: c0:ff:d4:d3:aa:48 , return 1
D/dhcpcd  ( 6497): [read_lease] unlink /data/misc/dhcp/dhcpcd-wlan0.lease, link /data/misc/dhcp/dhcpcd-wlan0-c0:ff:d4:d3:aa:48.lease2
D/dhcpcd  ( 6497): wlan0: reading lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
D/dhcpcd  ( 6497): wlan0: discarding expired lease
I/dhcpcd  ( 6497): wlan0: broadcasting for a lease
D/dhcpcd  ( 6497): wlan0: sending DISCOVER (xid 0x95dcb432), next in 4.73 seconds
,D/QRemote ( 6480): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6480): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 6480): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
V/WiFiOffLoadBroadcast( 6324): WiFiOffLoadBroadcast: android.net.wifi.SCAN_RESULTS
D/WiFiOffLoadBroadcast( 6324): Not supported operator for automatic switch
D/PostponalbeReceiver( 5174): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,V/WiFiOffLoadBroadcast( 6324): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6324): MCCMNC not supported: null
D/QRemote ( 6480): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,D/QRemote ( 6480): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 6480): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
D/PostponalbeReceiver( 5174): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
V/WiFiOffLoadBroadcast( 6324): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6324): MCCMNC not supported: null
D/QRemote ( 6480): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6480): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 6480): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,D/UsbSettingsReceiver( 6324): [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
D/UsbSettingsReceiver( 6324): [AUTORUN] sys.usb.config = ptp_only,adb
D/UsbSettingsReceiver( 6324): [AUTORUN] sys.usb.state = ptp_only,adb
D/UsbSettingsReceiver( 6324): [AUTORUN] persist.sys.usb.config = ptp_only,adb
D/UsbSettingsReceiver( 6324): [AUTORUN] onReceive() : app userid = 0, current userid = 0
D/UsbSettingsControl( 6324): [AUTORUN] getUsbConnected() : connected=true
D/UsbSettingsReceiver( 6324): [AUTORUN] onReceive() : availableList=[wlan0]
D/UsbSettingsReceiver( 6324): [AUTORUN] onReceive() : activeList=[]
,D/UsbSettingsReceiver( 6324): [AUTORUN] onReceive() : errorList=[]
D/UsbSettingsControl( 6324): [AUTORUN] isAutorunTimer() : mAutorunChanging=false
D/UsbSettingsReceiver( 6324): [AUTORUN] onReceive() : TetherState Changed=wlan0
D/UsbSettingsControl( 6324): [AUTORUN] setTetherStatus() : status=false
D/PostponalbeReceiver( 5174): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
V/WiFiOffLoadBroadcast( 6324): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6324): MCCMNC not supported: null
,D/QRemote ( 6480): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,D/QRemote ( 6480): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 6480): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
D/PostponalbeReceiver( 5174): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
V/WiFiOffLoadBroadcast( 6324): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6324): MCCMNC not supported: null
D/QRemote ( 6480): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,D/QRemote ( 6480): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 6480): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
D/PostponalbeReceiver( 5174): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
V/WiFiOffLoadBroadcast( 6324): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6324): MCCMNC not supported: null
D/QRemote ( 6480): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6480): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 6480): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
D/PostponalbeReceiver( 5174): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,V/WiFiOffLoadBroadcast( 6324): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6324): MCCMNC not supported: null
D/QRemote ( 6480): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6480): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 6480): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
D/libc-netbsd(  313): default dns: query_ipv6=0, query_ipv4=0
V/QRemote ( 6480): [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
,D/DSQN    ( 1031): DNSproblemNotiEnabled is disabled ignore DNS fail CB
D/QRemote ( 6480): [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
D/QRemote ( 6480): [QRemoteApplication.java:86:getControlManager()] oooooo mControlManager is null. make new RemoteControlManager
D/LgDataFeature( 6480): LgDataFeature() Constructor: none
,D/LgDataFeature( 6480): LgDataFeature() Constructor Done, null
,V/SoundPool( 6480): SoundPool constructor: maxChannels=2, attr.usage=13, attr.flags=0x0, attr.tags=
V/SoundPool( 6480): load: fd=30, offset=10857164, length=17813, priority=1
V/SoundPool( 6480): create sampleID=1, fd=31, offset=17813 length=10857164
V/SoundPool( 6480): doLoad: loading sample sampleID=1
,V/SoundPool( 6480): Start decode
V/MediaPlayer[Native]( 6480): decode(31, 10857164, 17813)
V/MediaPlayerService(  317): decode(24, 10857164, 17813)
W/BrunchPlayerTypeImpl(  317): [SelectPlayer] LocalType
W/BrunchPlayerTypeImpl(  317): [getMediaType] EXTEND_MEDIA_MIMETYPE = application/ogg
W/BrunchPlayerTypeImpl(  317): [FindUsePlayer] type = [application/ogg]
W/BrunchPlayerTypeImpl(  317): [FindUsePlayer] componentName = [9101]
W/MediaPlayerFactory(  317): [getPlayerType:fd] nType = 3
V/MediaPlayerService(  317): player type = 3
V/AwesomePlayer(  317): AwesomePlayer create()
V/AwesomePlayer(  317): reset_l() 
I/QRemote ( 6480): [RemoteControlManager.java:157:onBindIRService()] oooooo bind
V/AwesomePlayer(  317): cancelPlayerEvents
V/AwesomePlayer(  317): setAudioSink() 
V/AwesomePlayer(  317): reset_l() 
V/AudioCache(  317): notify(0xb5474740, 8, 0, 0)
V/AudioCache(  317): ignored
V/AwesomePlayer(  317): cancelPlayerEvents
D/Utils   (  317): printFileName fd(25) -> /data/preload/LGQRemote/LGQRemote.apk
V/AwesomePlayer(  317): setDataSource_l dataSource
V/LGParserOSAL(  317): SniffLGParser start
V/LGParserOSAL(  317): MainType:5, SubType=0
V/LGParserOSAL(  317): #### check Mime : application/ogg
V/LGParserOSAL(  317): Detector mimeType:application/ogg, Confidence=1.000000
E/MediaExtractor(  317): Use LGExtractor :application/ogg 
D/UEI.SmartControl( 5995): QS Service created
D/QRemote ( 6480): [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
E/QRemote ( 6480): [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
D/QRemote ( 6480): [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
,I/UEI.SmartControl( 5995): Service initServices...,
D/UEI.SmartControl( 5995): QS start get config
V/LGMDMManager( 6480): Create singleton instance
,V/LGParserOSAL(  317): supported mime: application/ogg
V/AwesomePlayer(  317): setDataSource_l() extractor countTracks=1
V/AwesomePlayer(  317): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer(  317): mBitrate = -1 bits/sec
V/AwesomePlayer(  317): AudioTrack Setting
V/AwesomePlayer(  317): AudioTrack Setting channelCount = 2
V/AwesomePlayer(  317): setAudioSource() 
,V/MediaPlayerService(  317): prepare
V/AwesomePlayer(  317): prepareAsync_l() 
V/MediaPlayerService(  317): wait for prepare
V/AwesomePlayer(  317): onPrepareAsyncEvent() 
V/AwesomePlayer(  317): initAudioDecoder() 
W/Utils   (  317): bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
V/AudioSystem(  317): isOffloadSupported()
V/AudioPolicyManager(  317): isOffloadSupported: SR=48000, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
D/AudioPolicyManager(  317): isOffloadSupported: stream_type != MUSIC, returning false
I/AudioFlinger(  317): isAudioPlaybackHookOn() false
V/AwesomePlayer(  317): getUseOffload() = 0 
V/OMXCodec(  317): OMXCodec::Create
V/OMXCodec(  317): findMatchingCodecs()
V/OMXCodec(  317): matching 'OMX.google.vorbis.decoder' quirks 0x00000000
V/OMXCodec(  317): matchingCodecs.size()=1
V/OMXCodec(  317): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
D/OMXCodec(  317): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
V/LGCodecAdapter(  317): LG Codec Adapter start
V/OMXCodec(  317): OMXCodec Createtor
V/OMXCodec(  317): setComponentRole
V/OMXCodec(  317): configureCodec protected=0
V/LGCodecAdapter(  317): called getLGCodecSpecificData
V/LGCodecOSAL(  317): Called LGgetCodecSpecificDataMETA
V/LGCodecOSAL(  317): Called LGconfigureCodecMETA
V/LGCodecOSAL(  317): Called LGconfigureCodecMSG
V/LGCodecOSAL(  317): Not support LGCodec
V/OMXCodec(  317): [OMX.google.vorbis.decoder] initOutputFormat()
V/OMXCodec(  317): Codec outputs a different number of channels than the input stream contains (contains 2 channels, codec outputs 1 channels).
V/OMXCodec(  317): Codec outputs at different sampling rate than what the input stream contains (contains data at 48000 Hz, codec outputs 44100 Hz)
I/AwesomePlayer(  317): Could not offload audio decode, try pcm offload
W/Utils   (  317): bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
V/AudioSystem(  317): isOffloadSupported()
V/AudioPolicyManager(  317): isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
D/AudioPolicyManager(  317): isOffloadSupported: stream_type != MUSIC, returning false
V/OMXCodec(  317): [OMX.google.vorbis.decoder] start mState=1
V/OMXCodec(  317): init()
V/OMXCodec(  317): [OMX.google.vorbis.decoder] setState mState=1 , newState=2
V/OMXCodec(  317): allocateBuffers
V/OMXCodec(  317): allocateBuffersOnPort portIndex=0
V/OMXCodec(  317): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
V/OMXCodec(  317): [OMX.google.vorbis.decoder] allocated buffer 0xb54f7ab0 on input port
V/OMXCodec(  317): [OMX.google.vorbis.decoder] allocated buffer 0xb54f7ba0 on input port
V/OMXCodec(  317): [OMX.google.vorbis.decoder] allocated buffer 0xb54f7bf0 on input port
V/OMXCodec(  317): [OMX.google.vorbis.decoder] allocated buffer 0xb54f7c40 on input port
V/OMXCodec(  317): allocateBuffersOnPort portIndex=1
V/OMXCodec(  317): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
V/OMXCodec(  317): [OMX.google.vorbis.decoder] allocated buffer 0xb54f7c90 on output port
V/OMXCodec(  317): [OMX.google.vorbis.decoder] allocated buffer 0xb54f7d30 on output port
V/OMXCodec(  317): [OMX.google.vorbis.decoder] allocated buffer 0xb54f7d80 on output port
V/OMXCodec(  317): [OMX.google.vorbis.decoder] allocated buffer 0xb57c3330 on output port
V/OMXCodec(  317): init() mAsyncCompletion wait!!! 
V/OMXCodec(  317): [OMX.google.vorbis.decoder] onStateChange 2
V/OMXCodec(  317): [OMX.google.vorbis.decoder] Now Idle.
V/OMXCodec(  317): [OMX.google.vorbis.decoder] setState mState=2 , newState=3
V/OMXCodec(  317): init() mAsyncCompletion wait!!! 
V/OMXCodec(  317): [OMX.google.vorbis.decoder] onStateCh,ange 3
V/OMXCodec(  317): [OMX.google.vorbis.decoder] Now Executing.
V/OMXCodec(  317): [OMX.google.vorbis.decoder] setState mState=3 , newState=4
V/OMXCodec(  317): init() mAsyncCompletion wait free! 
V/AwesomePlayer(  317): finishAsyncPrepare_l() 
V/AudioCache(  317): notify(0xb5474740, 5, 0, 0)
V/AudioCache(  317): ignored
V/AudioCache(  317): notify(0xb5474740, 1, 0, 0)
V/AudioCache(  317): prepared
V/AudioCache(  317): wait - success
V/MediaPlayerService(  317): start
V/AwesomePlayer(  317): play_l() 
V/AwesomePlayer(  317): play_l m_isDivXDRM=0, bpurchasefile:0
V/AwesomePlayer(  317): createAudioPlayer_l
V/AwesomePlayer(  317): seekAudioIfNecessary_l() 
V/AwesomePlayer(  317): startAudioPlayer_l() 
D/AudioPlayer(  317): start of Playback, useOffload 0
V/OMXCodec(  317): [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
V/OMXCodec(  317): [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
V/OMXCodec(  317): [OMX.google.vorbis.decoder] OMX_EventPortSettingsChanged(port=1, data2=0x00000000)
V/OMXCodec(  317): [OMX.google.vorbis.decoder] PORT_SETTINGS_CHANGED(1)
V/OMXCodec(  317): [OMX.google.vorbis.decoder] setState mState=4 , newState=7
V/OMXCodec(  317): [OMX.google.vorbis.decoder] disablePortAsync portIndex=1
V/OMXCodec(  317): [OMX.google.vorbis.decoder] sending OMX_CommandPortDisable(1)
V/OMXCodec(  317): [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
V/OMXCodec(  317): [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041885328
V/OMXCodec(  317): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
V/OMXCodec(  317): [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041885488
V/OMXCodec(  317): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
V/OMXCodec(  317): [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041885568
V/OMXCodec(  317): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
V/OMXCodec(  317): [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3044815664
V/OMXCodec(  317): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
V/OMXCodec(  317): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
V/OMXCodec(  317): [OMX.google.vorbis.decoder] initOutputFormat()
V/OMXCodec(  317): [OMX.google.vorbis.decoder] reconfig handling, formatHasNotablyChanged
V/OMXCodec(  317): [OMX.google.vorbis.decoder] enablePortAsync portIndex=1
V/OMXCodec(  317): [OMX.google.vorbis.decoder] sending OMX_CommandPortEnable(1)
V/OMXCodec(  317): allocateBuffersOnPort portIndex=1
V/OMXCodec(  317): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
V/OMXCodec(  317): [OMX.google.vorbis.decoder] allocated buffer 0xb54f7d80 on output port
V/OMXCodec(  317): [OMX.google.vorbis.decoder] allocated buffer 0xb54f7d30 on output port
V/OMXCodec(  317): [OMX.google.vorbis.decoder] allocated buffer 0xb54f7c90 on output port
V/OMXCodec(  317): [OMX.google.vorbis.decoder] allocated buffer 0xb57c35b0 on output port
V/OMXCodec(  317): [OMX.google.vorbis.decoder] PORT_ENABLED(1)
V/OMXCodec(  317): [OMX.google.vorbis.decoder] setState mState=7 , newState=4
V/AudioCache(  317): open(48000, 2, 0x0, 1, 4)
V/AudioCache(  317): notify(0xb5474740, 6, 0, 0)
V/AudioCache(  317): ignored
V/AudioCache(  317): write(0xb165f000, 4096)
,V/AudioCache(  317): memcpy(0xae806000, 0xb165f000, 4096)
V/MediaPlayerService(  317): wait for playback complete
,V/AudioCache(  317): write(0xb165f000, 4096)
V/AudioCache(  317): memcpy(0xae807000, 0xb165f000, 4096)
V/AudioCache(  317): write(0xb165f000, 4096)
V/AudioCache(  317): memcpy(0xae808000, 0xb165f000, 4096)
V/AudioCache(  317): write(0xb165f000, 4096)
V/AudioCache(  317): memcpy(0xae809000, 0xb165f000, 4096)
V/AudioCache(  317): write(0xb165f000, 4096)
V/AudioCache(  317): memcpy(0xae80a000, 0xb165f000, 4096)
V/AudioCache(  317): write(0xb165f000, 4096)
V/AudioCache(  317): memcpy(0xae80b000, 0xb165f000, 4096)
V/AudioCache(  317): write(0xb165f000, 4096)
V/AudioCache(  317): memcpy(0xae80c000, 0xb165f000, 4096)
V/AudioCache(  317): write(0xb165f000, 4096)
V/AudioCache(  317): memcpy(0xae80d000, 0xb165f000, 4096)
V/AudioCache(  317): write(0xb165f000, 4096)
V/AudioCache(  317): memcpy(0xae80e000, 0xb165f000, 4096)
V/AudioCache(  317): write(0xb165f000, 4096)
V/AudioCache(  317): memcpy(0xae80f000, 0xb165f000, 4096)
V/AudioCache(  317): write(0xb165f000, 4096)
V/AudioCache(  317): memcpy(0xae810000, 0xb165f000, 4096)
V/AudioCache(  317): write(0xb165f000, 4096)
V/AudioCache(  317): memcpy(0xae811000, 0xb165f000, 4096)
V/AudioCache(  317): write(0xb165f000, 4096)
V/AudioCache(  317): memcpy(0xae812000, 0xb165f000, 4096)
V/AudioCache(  317): write(0xb165f000, 4096)
V/AudioCache(  317): memcpy(0xae813000, 0xb165f000, 4096)
V/AudioCache(  317): write(0xb165f000, 4096)
V/AudioCache(  317): memcpy(0xae814000, 0xb165f000, 4096)
,V/AudioCache(  317): write(0xb165f000, 4096)
V/AudioCache(  317): memcpy(0xae815000, 0xb165f000, 4096)
V/AudioCache(  317): write(0xb165f000, 4096)
V/AudioCache(  317): memcpy(0xae816000, 0xb165f000, 4096)
V/AudioCache(  317): write(0xb165f000, 4096)
V/AudioCache(  317): memcpy(0xae817000, 0xb165f000, 4096)
V/AudioCache(  317): write(0xb165f000, 4096)
V/AudioCache(  317): memcpy(0xae818000, 0xb165f000, 4096)
V/AudioCache(  317): write(0xb165f000, 4096)
V/AudioCache(  317): memcpy(0xae819000, 0xb165f000, 4096)
V/AudioCache(  317): write(0xb165f000, 4096)
V/AudioCache(  317): memcpy(0xae81a000, 0xb165f000, 4096)
V/AudioCache(  317): write(0xb165f000, 4096)
V/AudioCache(  317): memcpy(0xae81b000, 0xb165f000, 4096)
V/AudioCache(  317): write(0xb165f000, 4096)
V/AudioCache(  317): memcpy(0xae81c000, 0xb165f000, 4096)
V/AudioCache(  317): write(0xb165f000, 4096)
V/AudioCache(  317): memcpy(0xae81d000, 0xb165f000, 4096)
V/AudioCache(  317): write(0xb165f000, 4096)
V/AudioCache(  317): memcpy(0xae81e000, 0xb165f000, 4096)
V/AudioCache(  317): write(0xb165f000, 4096)
V/AudioCache(  317): memcpy(0xae81f000, 0xb165f000, 4096)
V/AudioCache(  317): write(0xb165f000, 4096)
V/AudioCache(  317): memcpy(0xae820000, 0xb165f000, 4096)
V/AudioCache(  317): write(0xb165f000, 4096)
V/AudioCache(  317): memcpy(0xae821000, 0xb165f000, 4096)
V/AudioCache(  317): write(0xb165f000, 4096)
V/AudioCache(  317): memcpy(0xae822000, 0xb165f000, 4096)
V/AudioCache(  317): write(0xb165f000, 4096)
V/AudioCache(  317): memcpy(0xae823000, 0xb165f000, 4096)
V/AudioCache(  317): write(0xb165f000, 4096)
,V/AudioCache(  317): memcpy(0xae824000, 0xb165f000, 4096)
V/AudioCache(  317): write(0xb165f000, 4096)
V/AudioCache(  317): memcpy(0xae825000, 0xb165f000, 4096)
V/AudioCache(  317): write(0xb165f000, 4096)
V/AudioCache(  317): memcpy(0xae826000, 0xb165f000, 4096)
V/AudioCache(  317): write(0xb165f000, 4096)
V/AudioCache(  317): memcpy(0xae827000, 0xb165f000, 4096)
V/AudioCache(  317): write(0xb165f000, 4096)
V/AudioCache(  317): memcpy(0xae828000, 0xb165f000, 4096)
D/QRemote ( 6480): [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
V/AudioCache(  317): write(0xb165f000, 4096)
V/AudioCache(  317): memcpy(0xae829000, 0xb165f000, 4096)
,D/QRemote ( 6480): [RemoteAppWidgetProvider.java:486:onUpdate()] oooooo 140510:RetrieveDevices is not complete. Just waiting
V/AudioCache(  317): write(0xb165f000, 4096)
V/AudioCache(  317): memcpy(0xae82a000, 0xb165f000, 4096)
V/AudioCache(  317): write(0xb165f000, 4096)
V/AudioCache(  317): memcpy(0xae82b000, 0xb165f000, 4096)
D/QRemote ( 6480): [RemoteAppWidgetProvider.java:499:onUpdate()] oooooo 140514:alarm set after 5000ms:2560
,V/AudioCache(  317): write(0xb165f000, 4096)
V/AudioCache(  317): memcpy(0xae82c000, 0xb165f000, 4096)
,V/AudioCache(  317): write(0xb165f000, 4096),
V/AudioCache(  317): memcpy(0xae82d000, 0xb165f000, 4096)
V/AudioCache(  317): write(0xb165f000, 4096)
V/AudioCache(  317): memcpy(0xae82e000, 0xb165f000, 4096)
V/AudioCache(  317): write(0xb165f000, 4096)
V/AudioCache(  317): memcpy(0xae82f000, 0xb165f000, 4096)
V/AudioCache(  317): write(0xb165f000, 4096)
V/AudioCache(  317): memcpy(0xae830000, 0xb165f000, 4096)
V/AudioCache(  317): write(0xb165f000, 4096)
V/AudioCache(  317): memcpy(0xae831000, 0xb165f000, 4096)
V/AudioCache(  317): write(0xb165f000, 4096)
V/AudioCache(  317): memcpy(0xae832000, 0xb165f000, 4096)
V/AudioCache(  317): write(0xb165f000, 4096)
V/AudioCache(  317): memcpy(0xae833000, 0xb165f000, 4096)
V/AudioCache(  317): write(0xb165f000, 4096)
V/AudioCache(  317): memcpy(0xae834000, 0xb165f000, 4096)
V/AudioCache(  317): write(0xb165f000, 4096)
V/AudioCache(  317): memcpy(0xae835000, 0xb165f000, 4096)
V/AudioCache(  317): write(0xb165f000, 4096)
V/AudioCache(  317): memcpy(0xae836000, 0xb165f000, 4096)
V/AudioCache(  317): write(0xb165f000, 4096)
V/AudioCache(  317): memcpy(0xae837000, 0xb165f000, 4096)
V/OMXCodec(  317): [OMX.google.vorbis.decoder] No more output data.
V/OMXCodec(  317): [OMX.google.vorbis.decoder] There is no more output data available, not calling fillOutputBuffer
V/AwesomePlayer(  317): postAudioEOS() 
V/AudioCache(  317): write(0xb165f000, 280)
V/AudioCache(  317): memcpy(0xae838000, 0xb165f000, 280)
V/AwesomePlayer(  317): postStreamDoneEvent_l() -> status:-1011 
V/AwesomePlayer(  317): onStreamDone
V/AwesomePlayer(  317): MEDIA_PLAYBACK_COMPLETE
V/AudioCache(  317): notify(0xb5474740, 2, 0, 0)
V/AudioCache(  317): playback complete
V/AwesomePlayer(  317): pause_l() 
V/AudioCache(  317): notify(0xb5474740, 7, 0, 0)
V/AudioCache(  317): ignored
V/AwesomePlayer(  317): cancelPlayerEvents
V/AudioCache(  317): wait - success
V/MediaPlayerService(  317): return size 205080, sampleRate=48000, channelCount = 2, format = 1
D/AudioPlayer(  317): Pause Playback at 1068125
V/AwesomePlayer(  317): reset_l() 
V/AudioCache(  317): notify(0xb5474740, 8, 0, 0)
V/AudioCache(  317): ignored
V/AwesomePlayer(  317): cancelPlayerEvents
D/AudioPlayer(  317): reset: mPlaying=0 mReachedEOS=1 useOffload=0
V/OMXCodec(  317): [OMX.google.vorbis.decoder] stop mState=4
V/OMXCodec(  317): [OMX.google.vorbis.decoder] stopOmxComponent_l mState=4
V/OMXCodec(  317): [OMX.google.vorbis.decoder] setState mState=4 , newState=5
V/OMXCodec(  317): [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
V/OMXCodec(  317): [OMX.google.vorbis.decoder] onStateChange 2
V/OMXCodec(  317): [OMX.google.vorbis.decoder] Now Idle.
V/OMXCodec(  317): [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=0
V/OMXCodec(  317): [OMX.google.vorbis.decoder] freeing buffer 0xb54f7c40 on port 0
V/OMXCodec(  317): [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=3
V/OMXCodec(  317): [OMX.google.vorbis.decoder] freeing buffer 0xb54f7bf0 on port 0
V/OMXCodec(  317): [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=2
V/OMXCodec(  317): [OMX.google.vorbis.decoder] freeing buffer 0xb54f7ba0 on port 0
V/OMXCodec(  317): [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=1
V/OMXCodec(  317): [OMX.google.vorbis.decoder] freeing buffer 0xb54f7ab0 on port 0
V/OMXCodec(  317): [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=0
V/OMXCodec(  317): [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
V/OMXCodec(  317): [OMX.google.vorbis.decoder] freeing buffer 0xb57c35b0 on port 1
V/OMXCodec(  317): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=3
V/OMXCodec(  317): [OMX.google.vorbis.decoder] freeing buffer 0xb54f7c90 on port 1
V/OMXCodec(  317): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=2
V/OMXCodec(  317): [OMX.google.vorbis.decoder] freeing buffer 0xb54f7d30 on port 1
V/OMXCodec(  317): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=1
V/OMXCodec(  317): [OMX.google.vorbis.decoder] freeing buffer 0xb54f7d80 on port 1
V/OMXCodec(  317): [OMX,.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
V/OMXCodec(  317): [OMX.google.vorbis.decoder] setState mState=5 , newState=6
V/OMXCodec(  317): [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
V/OMXCodec(  317): [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
V/OMXCodec(  317): [OMX.google.vorbis.decoder] onStateChange 1
V/OMXCodec(  317): [OMX.google.vorbis.decoder] Now Loaded.
V/OMXCodec(  317): [OMX.google.vorbis.decoder] setState mState=6 , newState=1
V/OMXCodec(  317): [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
V/OMXCodec(  317): [OMX.google.vorbis.decoder] stopped in state 1
V/OMXCodec(  317): [OMX.google.vorbis.decoder] ~OMXCodec mstate =1
,V/OMXCodec(  317): [OMX.google.vorbis.decoder] setState mState=1 , newState=0
D/AudioPlayer(  317): AudioPlayer releasing audio source
D/AudioPlayer(  317): AudioPlayer done releasing audio source
V/AwesomePlayer(  317): reset_l() 
V/AwesomePlayer(  317): cancelPlayerEvents
V/AwesomePlayer(  317): ~AwesomePlayer call
V/AwesomePlayer(  317): reset_l() 
V/AwesomePlayer(  317): cancelPlayerEvents
V/SoundPool( 6480): close(31)
V/SoundPool( 6480): pointer = 0x9ff45000, size = 205080, sampleRate = 48000, numChannels = 2
I/ActivityManager( 1031): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.realtimechat.RequestWriter$NetworkStateReceiver: pid=6526 uid=10072 gids={50072, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,E/QC-QMI  ( 6470): qmi_client [6470] 13: failed to locate client data
E/QC-QMI  (  464): qmuxd: RX on fd=32 returned error=0 errno[2:No such file or directory]
E/QC-QMI  (  464): QMUX qmux_client_id=13 not found in qmux client list, unable to remove
,W/ResourcesManager( 6526): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,D/LgDataFeature( 6526): LgDataFeature() Constructor: none
D/LgDataFeature( 6526): LgDataFeature() Constructor Done, null
,I/qcom-bluetooth( 6544): /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 58:3f:54:73:64:c0 
,I/qcom-bluetooth( 6545): /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
I/bt_vendor( 6290): bluetooth satus is on
D/bt_hci_bdroid( 6290): preload
D/bt_userial_mct( 6290): userial_open(port:0)
,I/bt_vendor( 6290): bt-vendor : BT_VND_OP_USERIAL_OPEN
I/bt_vendor( 6290): Done intiailizing UART
I/bt_vendor( 6290): Done intiailizing UART
I/bt_userial_mct( 6290): CMD=66, EVT=66, ACL_Out=67, ACL_In=67
I/bt_vendor( 6290): Bluetooth Firmware and transport layer are initialized
D/bt_userial_mct( 6290): Entering userial_read_thread()
I/bt-btu  ( 6290): btu_task received preload complete event
W/bt-l2cap( 6290): L2CAP - L2CA_Register() called for PSM: 0x0001
W/bt-l2cap( 6290): L2CAP - L2CA_Register() called for PSM: 0x001f
W/bt-l2cap( 6290): L2CAP - L2CA_Register() called for PSM: 0x0003
I/        ( 6290): BTE_InitTraceLevels -- TRC_HCI
I/        ( 6290): BTE_InitTraceLevels -- TRC_L2CAP
I/        ( 6290): BTE_InitTraceLevels -- TRC_RFCOMM
I/        ( 6290): BTE_InitTraceLevels -- TRC_AVDT
I/        ( 6290): BTE_InitTraceLevels -- TRC_AVRC
I/        ( 6290): BTE_InitTraceLevels -- TRC_A2D
I/        ( 6290): BTE_InitTraceLevels -- TRC_BNEP
I/        ( 6290): BTE_InitTraceLevels -- TRC_BTM
I/        ( 6290): BTE_InitTraceLevels -- TRC_HID_HOST
I/        ( 6290): BTE_InitTraceLevels -- TRC_GAP
I/        ( 6290): BTE_InitTraceLevels -- TRC_PAN
I/        ( 6290): BTE_InitTraceLevels -- TRC_SDP
I/        ( 6290): BTE_InitTraceLevels -- TRC_GATT
I/        ( 6290): BTE_InitTraceLevels -- TRC_SMP
I/        ( 6290): BTE_InitTraceLevels -- TRC_BTAPP
I/        ( 6290): BTE_InitTraceLevels -- TRC_BTIF
W/bt-btm  ( 6290): btm_decode_ext_features_page Secure conn Controller support Enabled
E/bt-btm  ( 6290): BTM_SecRegister:p_cb_info->p_le_callback == 0xa01dd061 
E/bt-btm  ( 6290): BTM_SecRegister: btm_cb.api.p_le_callback = 0xa01dd061 
,E/bt-btif ( 6290): Calling BTA_HhEnable
E/bt-btif ( 6290): btif_storage_get_adapter_property service_mask:0x2140040
D/BluetoothAdapterProperties( 6290): Address is:58:3F:54:73:64:C0
W/bt-l2cap( 6290): L2CAP - L2CA_Register() called for PSM: 0x0019
W/bt-l2cap( 6290): L2CAP - L2CA_Register() called for PSM: 0x0017
W/bt-l2cap( 6290): L2CAP - L2CA_Register() called for PSM: 0x001b
W/bt-l2cap( 6290): L2CAP - L2CA_Register() called for PSM: 0x0011
W/bt-l2cap( 6290): L2CAP - L2CA_Register() called for PSM: 0x0013
,D/BluetoothAdapterProperties( 6290): Name is: G3-1
D/BluetoothManagerService( 1031): Bluetooth Adapter name changed to G3-1
D/BluetoothManagerService( 1031): Stored Bluetooth name: G3-1
D/BluetoothAdapterProperties( 6290): Scan Mode:20
D/BluetoothAdapterProperties( 6290): Discoverable Timeout:120
D/bt_hci_bdroid( 6290): postload
D/bt_hci_bdroid( 6290): Used up Tx Cmd credits
W/bt-l2cap( 6290): L2CAP - L2CA_Register() called for PSM: 0x000f
D/bte_conf( 6290): Device ID record 1 : primary
D/bte_conf( 6290):   vendorId            = 00c4
D/bte_conf( 6290):   vendorIdSource      = 0001
D/bte_conf( 6290):   product             = 13a1
D/bte_conf( 6290):   version             = 1000
D/bte_conf( 6290):   clientExecutableURL = 
D/bte_conf( 6290):   serviceDescription  = 
D/bte_conf( 6290):   documentationURL    = 
D/bte_conf( 6290): bte_load_did_conf no section named DID2.
D/BluetoothAdapterState( 6290): CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
D/BluetoothPanServiceJni( 6290): control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
D/BluetoothAdapterProperties( 6290): ScanMode =  20
D/BluetoothAdapterProperties( 6290): State =  11
D/BluetoothAdapterProperties( 6290): mDiscoverableTimeout = 120
V/LGBluetoothServiceAdapter( 6290): [BTUI] state:11, scanmode:20, timeout:120
D/BluetoothAdapterProperties( 6290): Setting state to 12
I/BluetoothAdapterState( 6290): Bluetooth adapter state changed: 11-> 12
D/btif_config_util( 6290): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
D/BluetoothManagerService( 1031): Message: 60
D/BluetoothManagerService( 1031): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
D/BluetoothManagerService( 1031): Broadcasting onBluetoothStateChange(true) to 5 receivers.
I/BluetoothAdapterState( 6290): Entering On State
W/sh      ( 6556): type=1400 audit(0.0:159): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
W/sh      ( 6556): type=1400 audit(0.0:160): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
D/BluetoothHeadset( 1850): onBluetoothStateChange: up=true
D/BluetoothHeadset( 1850): onBluetoothStateChange: up=true
D/BluetoothHeadset( 1031): onBluetoothStateChange: up=true
D/BluetoothA2dp( 1031): onBluetoothStateChange: up=true
D/BluetoothHeadset( 1850): onBluetoothStateChange: up=true
W/bt-smp  ( 6290): Key(LSB ~ MSB) = 0a 3c a6 fe eb 17 6a 79 a6 1f 0a 0b f9 50 a0 5f 
W/bt-smp  ( 6290): Plain text(LSB ~ MSB) = 84 15 70 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 6290): Encrypted text(LSB ~ MSB) = 36 50 b7 a8 c8 ed 63 db 0a 27 12 cb 0e 14 fd dd 
W/bt-btm  ( 6290): Stopping oneshot timer
E/bt_mct  ( 6290): hci lib postload completed
,D/LGBluetoothServiceAdapter( 6290): [BTUI] OnState
D/LGBluetoothServiceAdapter( 6290): [BTUI]         global_name: G3-1
D/LGBluetoothServiceAdapter( 6290): [BTUI]         local_name: G3-1
I/Babel   ( 6526): MmsConfig: mnc/mcc: 0/0
I/Babel   ( 6526): MmsConfig.loadMmsSettings
E/BluetoothManagerService( 1031): Fail to bind to: Intent { act=android.bluetooth.IQBluetooth }
D/BluetoothManagerService( 1031): Bluetooth State Change Intent: 11 -> 12
D/BluetoothAdapterService( 6290): [BTUI] autoConnect() : not allowed
D/BluetoothManagerService( 1031): BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
D/BluetoothManagerService( 1031): Message: 40
D/BluetoothManagerService( 1031): MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
D/LGBluetoothAPIService( 1945): [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
D/LGBluetoothAPIService( 1945): Message: 1
D/LGBluetoothAPIService( 1945): MESSAGE_BOOT_COMPLETED
W/bt-smp  ( 6290): Key(LSB ~ MSB) = 0a 3c a6 fe eb 17 6a 79 a6 1f 0a 0b f9 50 a0 5f 
W/bt-smp  ( 6290): Plain text(LSB ~ MSB) = 36 d9 4c 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 6290): Encrypted text(LSB ~ MSB) = 9e d0 d0 cc e5 34 1a 9b f6 aa cb 3d a6 7f 64 b2 
I/[SystemUI]BluetoothHandler( 1447): Receive : BluetoothAdapter.ACTION_STATE_CHANGED
W/bt-btm  ( 6290): Stopping oneshot timer
I/BluetoothMapService( 6290): onReceive: android.bluetooth.adapter.action.STATE_CHANGED
I/Babel   ( 6526): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D855 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D855-M3-D1.xml
D/BluetoothMapService( 6290): STATE_ON
W/bt-smp  ( 6290): Key(LSB ~ MSB) = 0a 3c a6 fe eb 17 6a 79 a6 1f 0a 0b f9 50 a0 5f 
W/bt-smp  ( 6290): Plain text(LSB ~ MSB) = 44 6e 4d 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 6290): Encrypted text(LSB ~ MSB) = a7 d0 cd ca 35 46 64 ed ef ad e3 cd 9a 60 45 8d 
W/bt-btm  ( 6290): Stopping oneshot timer
I/Babel   ( 6526): MmsConfig.loadFromDatabase
I/LGBluetoothAPIService( 1945): [BTUI] LGBluetoothAPIService Binding Success
W/bt-smp  ( 6290): Key(LSB ~ MSB) = 0a 3c a6 fe eb 17 6a 79 a6 1f 0a 0b f9 50 a0 5f 
W/bt-smp  ( 6290): Plain text(LSB ~ MSB) = 9a 9d 4d 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 6290): Encrypted text(LSB ~ MSB) = 0c 52 3f 41 34 d4 7e 57 33 08 f8 d4 2e 8e a8 7f 
W/bt-btm  ( 6290): Stopping oneshot timer
W/ContextImpl( 6324): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
,I/qcom-bt-wlan-coex( 6567): /system/etc/init.qcom.coex.sh: btwlancoex/abtfilt not available 
,D/LGBluetoothAPIServer( 6290): [BTUI] onCreate()
D/LGBluetoothAPIServer( 6290): [BTUI] onBind()
W/bt-smp  ( 6290): Key(LSB ~ MSB) = 0a 3c a6 fe eb 17 6a 79 a6 1f 0a 0b f9 50 a0 5f 
W/bt-smp  ( 6290): Plain text(LSB ~ MSB) = 05 1b 61 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 6290): Encrypted text(LSB ~ MSB) = ec 82 1c 89 7e 20 8b 57 80 f7 35 9a f2 f8 d2 dd 
W/bt-btm  ( 6290): Stopping oneshot timer
D/LGBluetoothAPIService( 1945): [BTUI] LGBluetoothAPIServiceConnection: connected to LGBluetoothAPIAdapter
D/LGBluetoothAPIService( 1945): Message: 100
D/LGBluetoothAPIService( 1945): MESSAGE_BLUETOOTH_SERVICE_CONNECTED
V/BluetoothMapService( 6290): Handler(): got msg=1
D/BluetoothMapMasInstance( 6290): Map Service startRfcommSocketListener
D/BluetoothMapMasInstance( 6290): MAS initSocket()
D/BluetoothMapMasInstance( 6290):   masId = 00
D/BluetoothMapMasInstance( 6290):   msgTypes = 0e
D/BluetoothMapMasInstance( 6290):   masName = SMS/MMS
D/BluetoothMapMasInstance( 6290):   SDP string = 000eSMS/MMS
D/LocalBluetoothProfileManager( 6324): Adding local A2DP profile
D/BluetoothManagerService( 1031): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/LGBluetoothDeviceModeControllManager( 6290): [BTUI] checkDeviceModeAndSet, sinkMode : false
,D/BluetoothManagerService( 1031): Message: 30
W/BluetoothAdapter( 6290): getBluetoothService() called with no BluetoothManagerCallback
D/BluetoothAdapterService( 6290): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2076f544
V/BluetoothPbapService( 6290): Pbap Service onCreate
V/BluetoothPbapService( 6290): Starting PBAP service
D/BluetoothAdapterProperties( 6290): Discoverable Timeout:120
D/LGBluetoothDeviceModeControllManager( 6290): adapterPropertyChangedCallback on  LGAdapter : do nothing - 9
D/LGBluetoothServiceAdapter( 6290): [BTUI] createSocketChannel FD=73 mFd=0
,D/LocalBluetoothProfileManager( 6324): Adding local HEADSET profile
V/BluetoothMapMasInstance( 6290): Succeed to create listening socket 
D/BluetoothAdapterProperties( 6290): Scan Mode:21
D/LGBluetoothDeviceModeControllManager( 6290): getDeviceMode  deviceMode 0
D/LGBluetoothPbapAdapter( 6290): [BTUI] getInstance : create
V/BluetoothPbapService( 6290): action: android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothPbapService( 6290): state: 12
V/BluetoothPbapReceiver( 6290): PbapReceiver onReceive 
V/BluetoothPbapReceiver( 6290): ***********action = android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothPbapReceiver( 6290): ***********state = 12
D/BluetoothMapMasInstance( 6290): Accepting socket connection...
D/BluetoothManagerService( 1031): Message: 30
V/BluetoothPbapService( 6290): Handler(): got msg=1
V/BluetoothPbapService( 6290): Pbap Service startRfcommSocketListener
V/BluetoothPbapService( 6290): Pbap Service initSocket
D/BluetoothManagerService( 1031): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
W/BluetoothAdapter( 6290): getBluetoothService() called with no BluetoothManagerCallback
,D/LGBluetoothServiceAdapter( 6290): [BTUI] createSocketChannel FD=75 mFd=73
D/BluetoothManagerService( 1031): Message: 30
V/BluetoothPbapService( 6290): Succeed to create listening socket 
V/BluetoothPbapService( 6290): Accepting socket connection...
I/UEI.SmartControl( 5995): Supports setup maps: true
E/Babel   ( 6526): canonicalizeMccMnc: invalid mccmnc 
I/Babel   ( 6526): MmsConfig.loadFromResources
D/UEI.SmartControl( 5995): QS start statue = true Error code = 0
I/UEI.SmartControl( 5995): QS version = v2.7.10.1_RC1
I/UEI.SmartControl( 5995): QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
I/UEI.SmartControl( 5995): ### init IR Blaster...
D/BluetoothManagerService( 1031): Message: 30
E/Babel   ( 6526): canonicalizeMccMnc: invalid mccmnc nullnull
W/Settings( 6526): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/Babel   ( 6526): MmsConfig.loadMmsSettings: mUserAgent=LG-D855 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D855-M3-D1.xml
D/serial_port( 5995): Configuring serial port
E/UEI.SmartControl( 5995): UEIBLaster setting for 616
I/UEI.SmartControl( 5995): Setting serial record hearder size = 2
I/UEI.SmartControl( 5995): configuring settings for MAXQ616
I/UEI.SmartControl( 5995): Get version...
D/LocalBluetoothProfileManager( 6324): Adding local MAP profile
D/BluetoothMap( 6324): Create BluetoothMap proxy object
D/BluetoothManagerService( 1031): Message: 30
,D/BluetoothManagerService( 1031): Message: 30
D/LocalBluetoothProfileManager( 6324): LocalBluetoothProfileManager construction complete
,V/BluetoothPbapService( 6290): Pbap Service onBind
D/LGBluetoothUserBindClient( 6324): [BTUI] initUserBindClient
W/ContextImpl( 6324): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.android.settings.bluetooth.LGBluetoothUserBindClient.initUserBindClient:90 com.android.settings.bluetooth.LGBluetoothUserBindClient.<init>:55 com.android.settings.bluetooth.LGBluetoothUserBindClient.getInstance:47 
D/DockEventReceiver( 6324): finishStartingService: stopping service
D/BluetoothA2dp( 6324): Proxy object connected
D/A2dpProfile( 6324): Bluetooth service connected
D/UEI.SmartControl( 5995): serial port data available: 21
,D/BluetoothHeadset( 6324): Proxy object connected
D/HeadsetProfile( 6324): Bluetooth service connected
D/BluetoothInputDevice( 6324): Proxy object connected
D/HidProfile( 6324): Bluetooth service connected
D/BluetoothPan( 6324): BluetoothPAN Proxy object connected
D/PanProfile( 6324): Bluetooth service connected
W/AudioCapabilities( 6526): Unsupported mime audio/evrc
W/AudioCapabilities( 6526): Unsupported mime audio/qcelp
D/BluetoothMap( 6324): Proxy object connected
D/MapProfile( 6324): Bluetooth service connected
D/BluetoothMap( 6324): getConnectedDevices()
V/BluetoothMapService( 6290): getConnectedDevices()
D/BluetoothPbap( 6324): Proxy object connected
D/PbapServerProfile( 6324): Bluetooth service connected
D/LGBluetoothUserBindClient( 6324): [BTUI] onServiceConnected
W/VideoCapabilities( 6526): Unrecognized profile 2130706433 for video/avc
D/BluetoothPermissionRequest( 6324): onReceive
,D/LGBluetoothFeatureConfig( 6324): isPrivacyLogsEnabled : true
D/LGBluetoothUtils( 6324): [BTUI] FileNotFound: readProperty
D/LGBluetoothResetSettingReceiver( 6324): return without doing reset settings.
,V/BluetoothOppReceiver( 6290): Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_ON
I/LGBluetoothOppAdapter( 6290): [BTUI] startOppService()
W/AudioCapabilities( 6526): Unsupported mime audio/amr-wb-plus
W/AudioCapabilities( 6526): Unsupported mime audio/qcelp
,W/AudioCapabilities( 6526): Unsupported mime audio/evrc
V/BluetoothOppManager( 6290): restoreApplicationData! falsefalsenullnull
D/UEI.SmartControl( 5995): MAXQ616 A2-X4 software.
I/UEI.SmartControl( 5995): IR Blaster version: 256702256704300002
I/UEI.SmartControl( 5995): QS saving settings...
D/UEI.SmartControl( 5995): IR Blaster version: 25672567
D/LGBluetoothFeatureConfig( 6290): isPrivacyLogsEnabled : true
V/BtOppService( 6290): onCreate
W/VideoCapabilities( 6526): Unsupported mime video/x-ms-wmv
,W/VideoCapabilities( 6526): Unsupported mime video/divx
V/BluetoothOppNotification( 6290): send message
V/BtOppService( 6290): Starting RfcommListener
W/VideoCapabilities( 6526): Unsupported mime video/divx311
D/BluetoothOppPreference( 6290): Dumping Names:  
D/BluetoothOppPreference( 6290): {}
D/BluetoothOppPreference( 6290): Dumping Channels:  
D/BluetoothOppPreference( 6290): {}
W/VideoCapabilities( 6526): Unsupported mime video/divx4
D/UEI.SmartControl( 5995): serial port data available: 4
V/BtOppService( 6290): onStartCommand
V/BluetoothFtpReceiver( 6290): BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothFtpReceiver( 6290): BluetoothFtpReceiver Start Service
W/VideoCapabilities( 6526): Unsupported mime video/mp4v-esdp
V/BtOppService( 6290): pendingUpdate is true keepUpdateThread is false sListenStarted is true
V/BluetoothOppProvider( 6290): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
V/BtOppService( 6290): Deleted complete outbound shares, number =  0
V/BluetoothOppNotification( 6290): new notify threadi!
V/BluetoothOppNotification( 6290): send delay message
,V/BtOppService( 6290): start RfcommListener
V/BluetoothOppProvider( 6290): starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
V/BtOppService( 6290): RfcommListener started
V/BluetoothOppProvider( 6290): created cursor android.database.sqlite.SQLiteCursor@2b947dbe on behalf of 
V/BtOppService( 6290): Deleted complete inbound failed shares, number = 0
V/BluetoothOppProvider( 6290): starting query, database is not null; projection[0] is _id; selection is direction=1 AND status=200 AND visibility=1; selectionArgs is null; sort is _id.
V/BluetoothOppProvider( 6290): created cursor android.database.sqlite.SQLiteCursor@b7d9e1f on behalf of 
V/BtOppRfcommListener( 6290): Starting RFCOMM listener....
D/BluetoothManagerService( 1031): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
V/BluetoothOppProvider( 6290): created cursor android.database.sqlite.SQLiteCursor@15a3f56c on behalf of 
W/BluetoothAdapter( 6290): getBluetoothService() called with no BluetoothManagerCallback
V/BluetoothOppNotification( 6290): mUpdateCompleteNotification = true
D/LGBluetoothServiceAdapter( 6290): [BTUI] createSocketChannel FD=80 mFd=75
V/BtOppRfcommListener( 6290): Started RFCOMM listener....
I/BtOppRfcommListener( 6290): Accept thread started.
V/BtOppRfcommListener( 6290): Accepting connection...
V/BluetoothOppProvider( 6290): starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
V/BtOppService( 6290): pendingUpdate is false keepUpdateThread is false sListenStarted is true
V/BluetoothOppProvider( 6290): created cursor android.database.sqlite.SQLiteCursor@291e9735 on behalf of 
V/BluetoothOppNotification( 6290): outbound: succ-0  fail-0
V/BluetoothOppNotification( 6290): outbound notification was removed.
V/BluetoothOppProvider( 6290): starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
V/BluetoothOppProvider( 6290): created cursor android.database.sqlite.SQLiteCursor@3c16b7ca on behalf of 
V/BluetoothOppNotification( 6290): inbound: succ-0  fail-0
,D/BluetoothAdapterService( 6290): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2076f544
V/BluetoothFtpService( 6290): Ftp Service onCreate
I/BluetoothFtpService( 6290): Ftp Service onCreate
V/BtOppService( 6290): ContentObserver received notification
V/BluetoothFtpService( 6290): Ftp Service onStartCommand
V/BluetoothFtpService( 6290): action: android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothFtpService( 6290): Starting Listening on sockets
V/BluetoothSapReceiver( 6290): [BTUI] checkServiceStart
V/BluetoothSapReceiver( 6290): [BTUI] region:EU country:EU
V/BluetoothSapReceiver( 6290): SapReceiver onReceive 
V/BluetoothSapReceiver( 6290): action = android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothSapReceiver( 6290):  Bluetooth Adapter state = 12
V/BluetoothSapReceiver( 6290): Calling SAP service start service with action = null
V/BtOppService( 6290): pendingUpdate is true keepUpdateThread is false sListenStarted is true
V/BluetoothOppProvider( 6290): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
V/BtOppService( 6290): ContentObserver received notification
V/BluetoothFtpService( 6290): Handler(): got msg=1
V/BluetoothOppProvider( 6290): created cursor android.database.sqlite.SQLiteCursor@590fc58 on behalf of 
V/BluetoothFtpService( 6290): Ftp Service startRfcommSocketListener
V/BluetoothFtpService( 6290): Ftp Service initSocket
V/BluetoothOppNotification( 6290): update too frequent, put in queue
V/BtOppService( 6290): pendingUpdate is true keepUpdateThread is false sListenStarted is true
V/BluetoothOppProvider( 6290): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
D/BluetoothManagerService( 1031): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
W/BluetoothAdapter( 6290): getBluetoothService() called with no BluetoothManagerCallback
D/LGBluetoothServiceAdapter( 6290): [BTUI] createSocketChannel FD=81 mFd=80
V/BluetoothFtpService( 6290): Succeed to create listening socket on channel 20
V/BluetoothFtpService:RfcommSocketAcceptThread( 6290): Run Accept thread
V/BluetoothOppProvider( 6290): created cursor android.database.sqlite.SQLiteCursor@fae71b1 on behalf of 
V/BluetoothOppNotification( 6290): update too frequent, put in queue
D/AuthorizationBluetoothService( 2112): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
W/ContextImpl( 5995): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
,V/BtOppService( 6290): pendingUpdate is false keepUpdateThread is false sListenStarted is true
E/UEI.SmartControl( 5995): Services init done
D/UEI.SmartControl( 5995): QS Service init finished
D/UEI.SmartControl( 5995): QS Service version name: 2.1.91
D/UEI.SmartControl( 5995): QS Service version code: 201091
D/UEI.SmartControl( 5995): Service requested: Control
I/UEI.SmartControl( 5995): Device manager: loading config....
V/BluetoothOppNotification( 6290): inbound notification was removed.
D/UEI.SmartControl( 5995): ----------- loading internal config...
V/BluetoothOppProvider( 6290): starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
I/QRemote ( 6480): [RemoteControlManager.java:183:onServiceConnected()] oooooo start
V/BluetoothOppProvider( 6290): created cursor android.database.sqlite.SQLiteCursor@33d08696 on behalf of 
D/UEI.SmartControl( 5995): Internal service binding...
I/UEI.SmartControl( 5995): ------ IControl API: 11
D/UEI.SmartControl( 5995): File observer start...
E/UEI.SmartControl( 5995): IR Port is disabled: false
D/UEI.SmartControl( 5995): Starting file observer...
D/BluetoothAdapterService( 6290): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2076f544
V/BluetoothSapService( 6290): Sap Service onCreate
I/UEI.SmartControl( 5995): Registering callback...
I/UEI.SmartControl( 5995): ------ IControl API: 19
V/BluetoothSapService( 6290): action: android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothSapService( 6290): state: 12
V/BluetoothSapService( 6290): Starting SAP server process
I/UEI.SmartControl( 5995): Registering Services Ready callback...
V/BluetoothSapService( 6290): SAP Service startRfcommListenerThread
V/BluetoothSapService( 6290): Sap Service initRfcommSocket
D/BluetoothManagerService( 1031): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
W/BluetoothAdapter( 6290): getBluetoothService() called with no BluetoothManagerCallback
I/VideoCapabilities( 6526): Unsupported profile 4 for video/mp4v-es
E/UEI.SmartControl( 5995): Loading SETTINGS...
W/sapd    ( 6589): type=1400 audit(0.0:161): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
D/LGBluetoothServiceAdapter( 6290): [BTUI] createSocketChannel FD=82 mFd=81
W/sapd    ( 6589): type=1400 audit(0.0:162): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
V/BluetoothSapService( 6290): Succeed to create listening socket 
V/BluetoothSapService( 6290): Accepting socket connection...
D/UEI.SmartControl( 5995): -- Open brand translation xml: brands_translations_ko
,W/AudioCapabilities( 6526): Unsupported mime audio/eac3
V/BT_SAP  ( 6589): Event pipe created
V/BT_SAP  ( 6589): create_server_socket qcom.sap.server
V/BT_SAP  ( 6589): created socket fd 6
W/AudioCapabilities( 6526): Unsupported mime audio/ac3
W/AudioCapabilities( 6526): Unsupported mime audio/g726
W/AudioCapabilities( 6526): Unsupported mime audio/wma-voice
W/AudioCapabilities( 6526): Unsupported mime audio/x-ms-wma
W/AudioCapabilities( 6526): Unsupported mime audio/adpcm
W/VideoCapabilities( 6526): Unsupported mime video/theora
W/VideoCapabilities( 6526): Unsupported mime video/mjpg
I/UEI.SmartControl( 5995): Notify AllClients services are ready: 0
I/QRemote ( 6480): [RemoteControlManager.java:660:QSSetupIsReady()] oooooo 140517:sdkIsReady callback... get functions. Result:0
,D/UEI.SmartControl( 5995): -----service ready thread exits
D/QRemote ( 6480): [RemoteControlManager.java:388:handleMessage()] oooooo 140510:START_SESSION
D/QRemote ( 6480): [RemoteControlManager.java:394:handleMessage()] oooooo 140510:send retrieve msg
D/QRemote ( 6480): [RemoteControlManager.java:322:handleMessage()] oooooo 140510:handler call retrieveDevices
D/QRemote ( 6480): [RemoteControlManager.java:336:retrieveDevices()] oooooo retrieveDevices: start
I/UEI.SmartControl( 5995): ------ IControl API: 8
D/QRemote ( 6480): [RemoteControlManager.java:340:retrieveDevices()] oooooo retrieveDevices: 0
D/QRemote ( 6480): [RemoteControlManager.java:345:retrieveDevices()] oooooo retrieveDevices complete:true
D/QRemote ( 6480): [RemoteControlManager.java:353:retrieveDevices()] oooooo retrieveDevices: notifyDataSetChanged()
D/QRemote ( 6480): [QRemoteApplication.java:145:onRemoteControlStateChanged()] oooooo onRemoteControlStateChanged called in QRemoteApp
D/QRemote ( 6480): [QRemoteApplication.java:158:onRemoteControlStateChanged()] oooooo Widget count is [1]. send broadcast
D/QRemote ( 6480): [QRemoteApplication.java:160:onRemoteControlStateChanged()] oooooo Widget[0]:3
,D/QRemote ( 6480): [QRemoteApplication.java:188:onRemoteControlStateChanged()] oooooo 140526:onRemoteControlStateChanged&sdkIsReady. stop Service
V/QRemote ( 6480): [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
D/QRemote ( 6480): [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
E/QRemote ( 6480): [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
D/QRemote ( 6480): [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
D/QRemote ( 6480): [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
D/QRemote ( 6480): [RemoteAppWidgetProvider.java:506:onUpdate()] oooooo 140510:RetrieveDevices complete. Start loading
D/QRemote ( 6480): [RemoteAppWidgetProvider.java:508:onUpdate()] oooooo 140510:appWidgetIds[0]:3 loading
D/QRemote ( 6480): [RemoteAppWidgetManager.java:41:startLoading()] oooooo 140518:widgetId[3] loading start at [1450100394433]
D/QRemote ( 6480): [QRemoteService.java:207:onDestroy()] oooooo 140526:onDestroy
I/ActivityManager( 1031): Killing 5876:com.android.defcontainer/u0a4 (adj 15): empty #17
D/QRemote ( 6480): [RemoteAppWidgetManager.java:239:doInBackground()] oooooo 140407:doinBack arr:0
,I/ActivityManager( 1031): Killing 5595:com.android.gallery3d/u0a27 (adj 15): empty #18
,W/libprocessgroup( 1031): failed to open /acct/uid_10004/pid_5876/cgroup.procs: No such file or directory
,W/libprocessgroup( 1031): failed to open /acct/uid_10027/pid_5595/cgroup.procs: No such file or directory
V/QRemote ( 6480): [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.widget_ui_update
E/QRemote ( 6480): [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
D/QRemote ( 6480): [RemoteAppWidgetProvider.java:171:onReceive()] oooooo total:0
D/QRemote ( 6480): [RemoteAppWidgetProvider.java:172:onReceive()] oooooo selected:0
D/QRemote ( 6480): [RemoteAppWidgetProvider.java:173:onReceive()] oooooo arr:[]
D/QRemote ( 6480): [RemoteAppWidgetProvider.java:174:onReceive()] oooooo appWidgetId:3
D/QRemote ( 6480): [RemoteAppWidgetProvider.java:815:updateRemoteViews()] oooooo UpdateRemoteViews3:widgetId:3
D/QRemote ( 6480): [RemoteAppWidgetProvider.java:986:updateRemoteViews()] oooooo updateAppWidget5:widgetId:3]
,E/WifiStateMachine( 1031):  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
,E/WifiStateMachine( 1031):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1031):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1031):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1031):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
,D/ConnectivityService( 1031): Update of LinkProperties for NetworkAgentInfo [WIFI () - 100]; created=false
I/dhcpcd  ( 6497): wlan0: offered 192.168.1.125 from 192.168.1.1
D/dhcpcd  ( 6497): wlan0: sending REQUEST (xid 0x95dcb432), next in 4.74 seconds
,I/dhcpcd  ( 6497): wlan0: acknowledged 192.168.1.125 from 192.168.1.1
,I/dhcpcd  ( 6497): wlan0: leased 192.168.1.125 for 86400 seconds
D/dhcpcd  ( 6497): wlan0: adding IP address 192.168.1.125/24
D/dhcpcd  ( 6497): wlan0: adding route to 192.168.1.0/24
D/dhcpcd  ( 6497): wlan0: adding default route via 192.168.1.1
D/dhcpcd  ( 6497): wlan0: writing lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
D/dhcpcd  ( 6497): getUsingAPMacAddress: c0:ff:d4:d3:aa:48 , return 1
D/dhcpcd  ( 6497): write_lease_ext: /data/misc/dhcp/dhcpcd-wlan0-c0:ff:d4:d3:aa:48.lease2
D/dhcpcd  ( 6497): wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason BOUND
E/WifiStateMachine( 1031):  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1031):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1031):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1031):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1031):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
D/ConnectivityService( 1031): Update of LinkProperties for NetworkAgentInfo [WIFI () - 100]; created=false
D/DhcpStateMachine( 1031): DHCPV4 succeeded on wlan0
D/LgDhcpStateMachineHelper( 1031): CheckDhcpDirectory [Lease File Count] : 3
V/LgDhcpStateMachineHelper( 1031): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
D/LgDhcpStateMachineHelper( 1031): checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.125
,V/LgDhcpStateMachineHelper( 1031): Add DhcpResults: IP address 192.168.1.125/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 86400 seconds
,V/DhcpStateMachine( 1031): Current State is mWaitBeforeStartState.
V/LgDhcpStateMachineHelper( 1031): bShouldSendDhcpAction Result: true
D/DhcpStateMachine( 1031): DHCP Start/Renew wake lock is released.
D/DhcpStateMachine( 1031): RunningState
E/WifiStateMachine( 1031):  ObtainingIpState CMD_POST_DHCP_ACTION 1 0 OK  v4
E/WifiStateMachine( 1031):  L2ConnectedState CMD_POST_DHCP_ACTION 1 0 OK  v4
D/LGWifiP2pService( 1031): InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1031): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0( 1031): doBoolean: DRIVER BTCOEXMODE 2
I/wpa_supplicant( 6323): wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
D/WifiNative-wlan0( 1031): DRIVER BTCOEXMODE 2: returned true
D/WifiNative-wlan0( 1031): doBoolean: DRIVER SETSUSPENDMODE 1
I/wpa_supplicant( 6323): wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 1
,D/WifiNative-wlan0( 1031): DRIVER SETSUSPENDMODE 1: returned true
D/WifiNative-wlan0( 1031): doBoolean: SET ps 1
,D/WifiNative-wlan0( 1031): SET ps 1: returned true
,D/ConnectivityService( 1031): Update of LinkProperties for NetworkAgentInfo [WIFI () - 100]; created=false
E/WifiStateMachine( 1031):  ObtainingIpState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
E/WifiStateMachine( 1031): WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
D/ConnectivityService( 1031): ignoring duplicate network state non-change
,W/Settings( 1031): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1031): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1031): NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
D/ConnectivityService( 1031): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,D/ConnectivityService( 1031): Adding iface wlan0 to network 100
I/StatusBar.NetworkController( 1447): networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/StatusBar.NetworkController( 1447): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1447): refreshViews: Data not connected!! Set no data type icon / Roaming
I/StatusBar.NetworkController( 1447): networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1447): mWifiConnected = false, mWifiLevel = 0
,W/Settings( 1031): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1031): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1031): NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
V/WfdStateTracker( 1945): handleWifiStateChangedEvent: 1
D/PostponalbeReceiver( 5174): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
D/StatusBar.NetworkController( 1447): refreshViews: Data not connected!! Set no data type icon / Roaming
,D/WifiHS20( 1031): [PASSPOINT] passpointNotification: hs20AP list is checked
W/Settings( 1031): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1031): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1031): NETWORK_STATE_CHANGED_ACTION [CONNECTED]
D/WifiHS20( 1031): [PASSPOINT] passpointNotification: hs20AP list is checked
I/StatusBar.NetworkController( 1447): networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
W/Settings( 1031): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1031): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1031): NETWORK_STATE_CHANGED_ACTION [CONNECTED]
I/StatusBar.NetworkController( 1447): mWifiConnected = true, mWifiLevel = 3
,D/StatusBar.NetworkController( 1447): refreshViews: Data not connected!! Set no data type icon / Roaming
I/StatusBar.NetworkController( 1447): networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1447): mWifiConnected = true, mWifiLevel = 3
D/StatusBar.NetworkController( 1447): refreshViews: Data not connected!! Set no data type icon / Roaming
E/ConnectivityService( 1031): Unexpected mtu value: 0, wlan0
D/ConnectivityService( 1031): Adding Route [fe80::/64 -> :: wlan0] to network 100
,D/ConnectivityService( 1031): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 100
D/ConnectivityService( 1031): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 100
D/ConnectivityService( 1031): addLocalRoutetoDefaultNetwork
D/ConnectivityService( 1031): defaultNAI is null or Wi-Fi no need to add Loacal route to default network. WiFi netid = 100
D/ConnectivityService( 1031): Setting Dns servers for network 100 to [/192.168.1.1]
V/WiFiOffLoadBroadcast( 6324): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/Nat464Xlat( 1031): requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
D/ConnectivityService( 1031): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService( 1031): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 100]
,D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1031): DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService( 1031): rematching NetworkAgentInfo [WIFI () - 100]
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1031): Connected
D/ConnectivityService( 1031):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1031): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService( 1031):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1031):     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
D/ConnectivityService( 1031):   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1031):     satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:true
D/ConnectivityService( 1031): currentScore = 0, newScore = 20
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1031): Checking http://clients3.google.com/generate_204 on "NG700"
D/ConnectivityService( 1031):    accepting network in place of null
D/ConnectivityService( 1031): sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    ( 1031): new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    ( 1031):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService( 1031): Setting tx/rx TCP buffers to 524288,1048576,2097152,262144,524288,1048576
D/TelephonyNetworkFactory-1( 1850): new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/TelephonyNetworkFactory-1( 1850):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
V/BluetoothOppNotification( 6290): new notify threadi!
V/BluetoothOppNotification( 6290): send delay message
D/libc-netbsd(  313): res_queryN name = clients3.google.com, class = 1, type = 28
E/ConnectivityService( 1031): [lg_data] Adding agent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::c69a:2ff:fe7b:60ac/64,192.168.1.125/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
D/CSLegacyTypeTracker( 1031): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
D/ConnectivityService( 1031): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
V/BluetoothOppProvider( 6290): starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
D/WiFiOffLoadBroadcast( 6324): MCCMNC not supported: null
,D/LocSvc_java( 1031): Sending msg: 4 arg1:1 arg2:1
D/LocSvc_java( 1031): getAGpsConnectionInfo connType - 4
D/LocSvc_java( 1031): updateNetworkState connTyp: 4 available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java( 1031): ignore wifi update if we are not in OPENING or CLOSING
D/LocSvc_java( 1031): Sending msg: 5 arg1:0 arg2:1
D/libc-netbsd(  313): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  313): res_queryN name = 2.android.pool.ntp.org, class = 1, type = 1
D/ConnectivityService( 1031): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/libc-netbsd(  313): res_queryN name = 2.android.pool.ntp.org., class = 1, type = 1
D/CSLegacyTypeTracker( 1031): [e] list.add(nai) empty : false size: 1
D/ConnectivityService( 1031): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::c69a:2ff:fe7b:60ac/64,192.168.1.125/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
D/DSQN    ( 1031): DNSproblemNotiEnabled is disabled ignore DNS fail CB
D/ConnectivityService( 1031): validation of new default Network = false
D/ConnectivityService( 1031): Default network via Wi-Fi connected. start DSQN
D/DSQN    ( 1031): enableDataServiceNotify 
D/DSQN    ( 1031): start dsqn bin
V/BluetoothOppProvider( 6290): created cursor android.database.sqlite.SQLiteCursor@15867622 on behalf of 
,D/ConnectivityService( 1031): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService( 1031):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1031):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1031): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
W/dsqn    ( 6638): type=1400 audit(0.0:163): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
W/dsqn    ( 6638): type=1400 audit(0.0:164): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
D/ConnectivityManager.CallbackHandler( 1447): CM callback handler got msg 524290
D/libc-netbsd(  313): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  313): res_queryN name = europe.pool.ntp.org, class = 1, type = 1
V/BluetoothOppNotification( 6290): mUpdateCompleteNotification = true
V/BluetoothOppProvider( 6290): starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
V/BluetoothOppProvider( 6290): created cursor android.database.sqlite.SQLiteCursor@228ad8b3 on behalf of 
V/BluetoothOppNotification( 6290): outbound: succ-0  fail-0
V/BluetoothOppNotification( 6290): outbound notification was removed.
V/BluetoothOppProvider( 6290): starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
D/QRemote ( 6480): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6480): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
V/BluetoothOppProvider( 6290): created cursor android.database.sqlite.SQLiteCursor@1096fe70 on behalf of 
V/BluetoothOppNotification( 6290): inbound: succ-0  fail-0
,V/BluetoothOppNotification( 6290): inbound notification was removed.
V/BluetoothOppProvider( 6290): starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
V/BluetoothOppProvider( 6290): created cursor android.database.sqlite.SQLiteCursor@c70a5e9 on behalf of 
E/DSQN    ( 6638): DSQN ssw
V/NetworkPolicy( 1031): [LG_RESTRICTED] checkMobilePolicy_type()
,I/QRemote ( 6480): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,D/TelephonyIcons( 1447): null signal icon name: drawable/stat_sys_signal_null
D/PostponalbeReceiver( 5174): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
D/StatusBar.NetworkController( 1447): refreshViews: Data not connected!! Set no data type icon / Roaming
D/StatusBar.NetworkController( 1447): refreshViews: Data not connected!! Set no data type icon / Roaming
V/WiFiOffLoadBroadcast( 6324): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6324): MCCMNC not supported: null
D/QRemote ( 6480): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6480): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 6480): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,D/PostponalbeReceiver( 5174): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,I/PCSuite ( 6403): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
D/PCSuite ( 6403): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
,V/WiFiOffLoadBroadcast( 6324): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6324): MCCMNC not supported: null
D/QRemote ( 6480): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6480): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,D/QRemote ( 6480): [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
,I/QRemote ( 6480): [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
I/QRemote ( 6480): [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
D/PostponalbeReceiver( 5174): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,I/PCSuite ( 6403): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
D/PCSuite ( 6403): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 6324): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6324): MCCMNC not supported: null
D/QRemote ( 6480): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6480): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,D/QRemote ( 6480): [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
I/QRemote ( 6480): [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
I/QRemote ( 6480): [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1598549883] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:13] from screen [on:0 period:-1598549870] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
D/StatusBar.NetworkController( 1447): refreshViews: Data not connected!! Set no data type icon / Roaming
,I/jxcore-log( 6219): BLE advertisement not supported: MultipleAdvertisement not supported
I/jxcore-log( 6219): 
,V/WifiInternetCheck( 1031): Single check msg out of sync, ignoring.
D/ConnectivityService( 1031): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
D/Tethering( 1031): MasterInitialState.processMessage what=3
,D/libc-netbsd(  313): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  313): res_queryN name = 2.android.pool.ntp.org, class = 1, type = 1
D/GpsLocationProvider( 1031): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,D/PostponalbeReceiver( 5174): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
W/ContextImpl( 5174): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
,I/NetworkMonitor( 5255): type=WIFI subType= reason=null isConnected=true
,I/GoogleURLConnFactory( 2112): Using platform SSLCertificateSocketFactory
,I/ActivityManager( 1031): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=6678 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,D/libc-netbsd(  313): res_queryN name = 2.android.pool.ntp.org succeed
,D/AlarmManagerService( 1031): Setting time of day to sec=1450100399
W/AlarmManagerService( 1031): Unable to set rtc to 1450100399: Invalid argument
,I/ActivityManager( 1031): Start proc com.google.android.apps.books for service com.google.android.apps.books/.service.SyncService: pid=6699 uid=10054 gids={50054, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/AppUp4:AppBoxCP( 6678): onCreate
,W/AppUp4:DB( 6678):  [AppBoxDatabaseHelper] construct
I/ActivityManager( 1031): Start proc com.android.gallery3d for service com.android.gallery3d/com.lge.gallery.picasa.PicasaService: pid=6716 uid=10027 gids={50027, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
,I/SecureClockService( 1945): Intent.ACTION_TIME_CHANGED 
,D/LIA_Informant_Tips_DateChangeManager( 2725): onReceive() : ACTION_TIME_CHANGED
I/LIA_Informant_Tips_LogTracer( 2725): [Log Tracer - Schedule Transition] Time Change Event Received : 2015-12-14 14:39:59...... Request
I/LIA_Informant_Tips_LogTracer( 2725): [Log Tracer - Schedule Transition] UserGuide, DATE_UPDATE : working count : 5, total count : 113, new day : false...... Request
D/LIA_Informant_Tips_DateChangeManager( 2725): DateInfo : SmartTips Total Working Day Count = 113
D/LIA_Informant_Tips_DateChangeManager( 2725): DateInfo : UserGuide Working Duration Count = 5
D/KeyguardUpdateMonitor( 1447): handleTimeUpdate
I/[SystemUI]Clock( 1447): onReceive = android.intent.action.TIME_SET
W/ActivityManager( 1031): getTasks: caller 10029 is using old GET_TASKS but privileged; allowing
V/AlarmManager( 1031): RTC_WAKEUP set : Alarm{7b241a0 type 0 when 1450100399366 com.android.vending} when 1450100399366
I/LgeClockWidgetControlView( 1447): time changed, timezoneChanged : false
D/LIA_Informant_Tips_DateChangeManager( 2725): DateInfo : Last Date Check Time = 2015-12-14 14:39:59
,I/[LGHome]LGDateChangeReceiver( 2067): [LGDateChangeReceiver.java:78:updateCalendarShortcut()]date=14 currentDate=-1 dayofweek=2 currentDayOfWeek=-1
I/[LGHome]LGCalendarIcon( 2067): [LGCalendarIcon.java:214:makeCalendarBitmap()]Locale = en_US dayofweek= Mon date= 14
,I/[LGHome]LGCalendarIcon( 2067): [LGCalendarIcon.java:214:makeCalendarBitmap()]Locale = en_US dayofweek= Mon date= 14
I/[LGHome]Launcher( 2067): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/AppUp4:DB( 6678):  setFingerPrint start
I/AppUp4:DB( 6678):  newfinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys SDK version = 21
,I/AppUp4:DB( 6678):  beforefinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys
I/AppUp4:DB( 6678):  SDK version = 21
I/AppUp4:DB( 6678):  beforefinger == newfinger no write in DB
D/AppUp4:AppBoxApplication( 6678): AppBoxApplication onCreate()
,D/[Concierge]Service( 2603): onStartCommand(). Type : 9
I/NetworkStateForAutoUpdateMonitor( 6678): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 6678): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 6678): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 6678): [onReceive] request level :IDLE....
W/ResourcesManager( 6716): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6716): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 6716): Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
W/ResourcesManager( 6716): Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
I/AppUp4:CustModeStarterReceiver( 6678): onReceive
,V/SIM_STK ( 1031): Menu title from STK is T-Mobile
,D/LgDataFeature( 6678): LgDataFeature() Constructor: none
D/LgDataFeature( 6678): LgDataFeature() Constructor Done, null
,D/AppUp4:CustFacade( 6678): Context : android.app.ReceiverRestrictedContext@34afd657
D/AppUp4:CustFacade( 6678): isCustomizationCompleted : false
D/AppUp4:CustFacade( 6678): isPhone : true
D/AppUp4:CustModeStarterReceiver( 6678): begin check event
I/AppUp4:CustModeStarterReceiver( 6678): Event For GoodConnectivity
D/AppUp4:CustModeStarterReceiver( 6678): runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
I/AppConfig( 6716): Total System Memory = 2995761152
,D/SystemHelper( 6716): region [EU], country [EU], operator [OPEN], sub-operator []
D/AppUp4:CustModeStarterReceiver( 6678): call method handleAsyncCustNotification.
D/AppUp4:CustModeStarterReceiver( 6678): handleAsync isTriedOnce : false
E/AppUp4:CustModeStarterReceiver( 6678): handleAsyncCustNotification do not startCustService
D/LGDMClient( 3941): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 3941): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
W/ContextImpl( 3941): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,W/ContextImpl( 3941): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
D/LGDMClient( 3941): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=3, isUserType=1
V/DownloadManager( 3288): Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 3941): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 3941): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
I/LGDMClient( 3941): [DmServiceProcessor.java] [processNetworkChanged()] : [91] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
V/DownloadManager( 3288): DownloadService onCreate
,I/DownloadManager( 3288): in removeSpuriousFiles
V/DownloadManager( 3288): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3288): created cursor android.database.sqlite.SQLiteCursor@111a74d3 on behalf of 3288
I/DownloadManager( 3288): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGMyGuide_4.40.09_COM_COM_20150430011620058_RELG-D855.apk
I/DownloadManager( 3288): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGBackup_4.50.37_COM_COM_20150608234245157.apk
I/DownloadManager( 3288): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/CalendarProvider_4.2.8_COM_COM_20150304234552863_RELG-D855.apk
I/DownloadManager( 3288): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calendar_4.40.16_COM_COM_20150304234554754_RELG-D855.apk
I/DownloadManager( 3288): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.10_COM_COM_20150521235426173_RELG-D855.apk
I/DownloadManager( 3288): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQVoiceplusN_2.3.3_COM_COM_20150604065210803.apk
I/DownloadManager( 3288): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.11_COM_COM_v2_20150911144028620_RELG-D855_21.apk
I/DownloadManager( 3288): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQMemoplus(LG-D855_user)_20150902050954661.apk
I/DownloadManager( 3288): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/RemoteCall_4.1.10_COM_COM_20150817053748728.apk
I/DownloadManager( 3288): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/rspermlge(6713)_20150901080430397.apk
I/DownloadManager( 3288): in trimDatabase
V/DownloadManager( 3288): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
V/DownloadManager( 3288): created cursor android.database.sqlite.SQLiteCursor@1582ef09 on behalf of 3288
I/ActivityManager( 1031): Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=6743 uid=10023 gids={50023, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,V/DownloadManager( 3288): DownloadService onStartCommand
V/DownloadManager( 3288): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
W/ContextImpl( 3941): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:141 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:180 android.app.IntentService$ServiceHandler.handleMessage:65 
E/LGDMClient( 3941): [DmNotiService.java] [onCreate()] : [148] : DmNotiService.onCreate()
D/LGDMClient( 3941): [DmNotiService.java] [onStartCommand()] : [182] : in the new onStartCommand()
D/LGDMClient( 3941): [DmNotiService.java] [handleStart()] : [203] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
V/DownloadManager( 3288): created cursor android.database.sqlite.SQLiteCursor@d8b2f on behalf of 3288
V/DownloadManager( 3288): processing inserted download 1
V/DownloadManager( 3288): processing inserted download 4
V/DownloadManager( 3288): processing inserted download 7
V/DownloadManager( 3288): processing inserted download 8
V/DownloadManager( 3288): processing inserted download 9
V/DownloadManager( 3288): processing inserted download 10
V/DownloadManager( 3288): processing inserted download 16
V/DownloadManager( 3288): processing inserted download 17
V/DownloadManager( 3288): processing inserted download 18
,V/DownloadManager( 3288): processing inserted download 21
V/DownloadManager( 3288): DownloadService onDestroy
,I/ActivityManager( 1031): Start proc com.android.chrome for service com.android.chrome/com.google.android.apps.chrome.sync.ChromeBrowserSyncAdapterService: pid=6760 uid=10057 gids={50057, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/PowerManagerServiceEx( 1031): acquireWakeLockInternal: lock=257990054, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1031
D/[Concierge]Service( 2603): onStartCommand(). Type : 9
I/VacuumService( 2112): Vacuum at: now=1450100400021 tag=VacuumService
,I/ThermalEngine(  329): Thermal-Server: Thermal received msg from  override
I/Thermal-Lib( 3117): Thermal-Lib-Client: Client request sent
I/art     ( 1031): Explicit concurrent mark sweep GC freed 60255(2MB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 44MB/66MB, paused 1.281ms total 77.266ms
,I/ReaderUtils( 6699): PortraitW 1440 LandscapeW 2392 SmallestSize 1340 LargestSize 2392 textZoom 4.4999995 isTablet false Memory 256
W/ResourcesManager( 6743): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6743): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 6743): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
W/ResourcesManager( 6743): Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
,D/GpsLocationProvider( 1031): updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,W/DriveInitializer( 2350): Background init thread started
E/GpsLocationProvider( 1031): No APN found to select.
,W/GAV2    ( 6699): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,I/ActivityManager( 1031): Killing 6029:com.google.android.apps.docs/u0a61 (adj 15): empty #17
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=2.2, 0.0, 0.0  rx=2.5 bcn=0 [on:0 tx:0 rx:0 period:3918] from screen [on:0 period:-1598545915] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=2.2, 0.0, 0.0  rx=2.5 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-1598545914] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/VoldCmdListener(  278): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  278): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.gms/files/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 2350): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.gms/files
W/DriveInitializer( 2350): Awaiting to be initialized
,W/libprocessgroup( 1031): failed to open /acct/uid_10061/pid_6029/cgroup.procs: No such file or directory
,I/LGEmail ( 6743): [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
I/BooksApp( 6699): Created application version: 3.2.35 (30235)
,V/GLSActivity( 2112): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/LGEmail ( 6743): user build Type == true (at Util.java isUserModeBuildType 3507)[v:6.41.18]
,W/ResourceType( 6743): No package identifier when getting value for resource number 0x00000000
,I/art     ( 2112): Explicit concurrent mark sweep GC freed 19254(1099KB) AllocSpace objects, 2(32KB) LOS objects, 51% free, 30MB/62MB, paused 811us total 24.706ms
W/DriveInitializer( 2350): Background init thread ended
,I/GLSUser ( 2112): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 2112): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2112): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2112): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
D/DelayedSyncController( 6760): Delaying sync.
V/GLSActivity( 2112): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 5667): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 5667): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 5667): [1] 5.onFinished: Scheduling replication attempt 4.
E/Auth.Api.Credentials( 2350): [CredentialSyncAdapter] Unknown sync event.
I/ActivityManager( 1031): Killing 5619:com.lge.lockscreensettings/u0a80 (adj 15): empty #17
,I/BooksSync( 6699): Starting books sync
D/LgDataFeature( 6743): LgDataFeature() Constructor: none
D/LgDataFeature( 6743): LgDataFeature() Constructor Done, null
,D/UEI.SmartControl( 5995): Internal timer expired: 4
D/UEI.SmartControl( 5995): unbind internal service
,W/libprocessgroup( 1031): failed to open /acct/uid_10080/pid_5619/cgroup.procs: No such file or directory
,I/ActivityManager( 1031): Killing 5637:com.google.android.apps.plus/u0a97 (adj 15): empty #17
I/GLSUser ( 2112): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/ads_measurement
I/GLSUser ( 2112): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/ads_measurement without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2112): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2112): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
W/libprocessgroup( 1031): failed to open /acct/uid_10097/pid_5637/cgroup.procs: No such file or directory
,V/GLSActivity( 2112): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
E/Ads     ( 2350): [JAMS] Failed to get OAuth token: com.google.android.gms.auth.ad: BadAuthentication
,D/serial_port( 5995): close(fd = 24)
I/UEI.SmartControl( 5995): Serial port is closed.
I/GoogleURLConnFactory( 2112): Using platform SSLCertificateSocketFactory
,D/eas_req ( 6743): ---addEventToQueue() easCode=2, requestId=0 (at EasSupport.java addEventToQueue 69)
W/Uploader( 2112): No account for auth token provided
D/libc-netbsd(  313): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  313): res_queryN name = play.googleapis.com, class = 1, type = 1
,D/libc-netbsd(  313): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  313): res_queryN name = www.google.com, class = 1, type = 1
I/LgeMiscReceiver( 3215): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 3215): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 3215): networkInfo.isConnected() = true
D/PhoneState( 3215): setPdpRejectCasuse : false
I/HubEmail( 6743): JNI_OnLoad()
I/HubEmail( 6743): -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 6743): registerNatives()
I/HubEmail( 6743): -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 6743): registerNativeMethods()
I/HubEmail( 6743): -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
W/art     ( 6743): JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
D/BooksSync( 6699): started syncMyEbooks
,D/libc-netbsd(  313): res_queryN name = www.google.com succeed
D/libc-netbsd(  313): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  313): res_queryN name = clients3.google.com, class = 1, type = 1
D/libc-netbsd(  313): default dns: query_ipv6=0, query_ipv4=1
,D/libc-netbsd(  313): res_queryN name = static-avc.lglime.com, class = 1, type = 1
I/ActivityManager( 1031): Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=6834 uid=10062 gids={50062, 9997, 4002, 3003, 1028} abi=armeabi-v7a
W/Settings( 6743): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 6743): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/libc-netbsd(  313): res_queryN name = clients3.google.com succeed
D/LGDataListener(  313): argv[0]=dsqncommand
D/LGDataListener(  313): argv[1]=wlan0
D/LGDataListener(  313): argv[2]=1
D/LGDataListener(  313): notifyDSQN DSQN STARTMONITOR wlan0 1
,D/DSQN    ( 1031): DSQM DsqnNotification wlan0  1
D/DSQN    ( 1031): start to monitor internet connection
D/DrmBroadcastReceiver( 6834): Receive CONNECTIVITY_ACTION
D/DrmBroadcastReceiver( 6834): 1  network is available. Sync DRM Time with NTP
V/DrmService( 6834): Service onCreate
D/DrmService( 6834): Received new request = 2
I/DrmSntpClient( 6834): Start Sync process
D/DrmSntpClient( 6834): Server : 0
,D/libc-netbsd(  313): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  313): res_queryN name = pool.ntp.org, class = 1, type = 1
V/WifiInternetCheck( 1031): isHttpConnectionAvailable - We got a valid response : 204
I/ActivityManager( 1031): Start proc com.lge.sizechangable.weather for broadcast com.lge.sizechangable.weather/.layout.WeatherWidget: pid=6855 uid=10085 gids={50085, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,V/GLSActivity( 2112): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/libc-netbsd(  313): res_queryN name = play.googleapis.com succeed
,D/libc-netbsd(  313): res_queryN name = pool.ntp.org succeed
I/GLSUser ( 2112): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 2112): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2112): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2112): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2112): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/art     ( 6855): Almond Protected OAT
,V/NotificationService( 1031): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
V/NotificationService( 1031): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1031): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1031): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1031): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
W/GLSActivity( 2112): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2112): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2112): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2112): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2112): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2112): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2112): 	at android.os.Binder.execTransact(Binder.java:446)
I/LGDrmClient( 6834): _DRM_ServiceGet() : Bind lgdrm service
V/ILGDrmService(  322): eDRM_SetDRMTime +++
I/LGDRM   (  322): [DRM] SET TIME : YR=2015, MON=12, DAY=14
I/LGDRM   (  322): [DRM] SET TIME : HR=13, MIN=39, SEC=59
D/LgeQuickCoverNLService( 1396): onNotificationPosted
D/SmartCoverUpdateMonitor( 1396): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1396): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1396): handleNotificationPosted(true)
D/QuickCircle( 1396): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1396): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1396): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1396): post do just update job
D/LgeQuickCoverNotificationData( 1396): showAll3
D/LgeQuickCoverNotificationData( 1396): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1396): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1396): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1396): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1396): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1396): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1396): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1396): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1396): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1396): isNotificationForCurrentUser : true
,E/LgeQuickCoverOverlayWindow( 1396): updateNotificationData: count=3
V/ILGDrmService(  322): eDRM_SetDRMTime ---
E/BooksAccountManager( 6699): Authentication error
E/BooksAccountManager( 6699): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6699): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6699): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6699): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6699): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6699): 	at android.os.Binder.execTransact(Binder.java:446)
I/DrmSntpClient( 6834): Synched
D/DrmService( 6834): Completed !! request = 2
D/DrmService( 6834): Request count = 0
E/HttpHelper( 6699): null auth token
V/DrmService( 6834): Service onDestroy
I/ActivityManager( 1031): Killing 6083:com.lge.eula/1000 (adj 15): empty #17
D/libc-netbsd(  313): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  313): res_queryN name = www.googleapis.com, class = 1, type = 1
,D/QuickStatusbarLayout( 1396): Notification difference=198
D/QuickStatusbarLayout( 1396): child = android.widget.LinearLayout{b7d9e1f V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
W/libprocessgroup( 1031): failed to open /acct/uid_1000/pid_6083/cgroup.procs: No such file or directory
,D/WeatherApplication( 6855): removeAccount
D/libc-netbsd(  313): res_queryN name = www.googleapis.com succeed
D/WeatherApplication( 6855): Account.length = 0
E/WeatherApplication( 6855): OPERATOR:OPEN
D/WeatherAncestor( 6855): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 14:40:0
D/Weather.Utils( 6855): 2 : the weather widgets(using time tick) are gone.
D/Weather.Utils( 6855): 2 : All the weather widget is gone.
D/UpdateThreadPoolManager( 6855): 2 : This is isUpdating : false
D/WeatherAncestor( 6855): connectivity changed - connection : true
D/WeatherService( 6855): 2 : isServiceAlived():false forecastCache:null
,V/GLSActivity( 2112): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/ForecastDataCache( 6855): 2 : lastUpdatedTime: 1430558561343
D/ForecastDataCache( 6855): 2 : currentPackageVersion: 4.40.4
D/ForecastDataCache( 6855): 2 : Cache is not up-to-date, count: 0
I/GLSUser ( 2112): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.syncadapters.contacts, service: cp
I/GLSUser ( 2112): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> cp without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2112): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2112): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2112): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/Weather_cast( 6855): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherAncestor( 6855): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 14:40:0
D/libc-netbsd(  313): res_queryN name = static-avc.lglime.com succeed
,W/Uploader( 2112): No account for auth token provided
,V/FormManager( 6376): There are no updated forms. The schedule will be deleted.
,V/FormManager( 6376): Alarm would be updated, because LastCheckTime has been updated.
I/art     ( 1031): Explicit concurrent mark sweep GC freed 25649(1132KB) AllocSpace objects, 3(176KB) LOS objects, 33% free, 44MB/66MB, paused 1.868ms total 74.085ms
,I/ActivityManager( 1031): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=6876 uid=10093 gids={50093, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager( 1031): Killing 6125:com.google.android.gms.wearable/u0a5 (adj 15): empty #17
,I/art     (  344): Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 193us total 9.239ms
W/ApiaryClient( 6699): Error response from books API: {
W/ApiaryClient( 6699):  "error": {
W/ApiaryClient( 6699):   "errors": [
W/ApiaryClient( 6699):    {
W/ApiaryClient( 6699):     "domain": "global",
W/ApiaryClient( 6699):     "reason": "required",
W/ApiaryClient( 6699):     "message": "Login Required",
W/ApiaryClient( 6699):     "locationType": "header",
W/ApiaryClient( 6699):     "location": "Authorization"
W/ApiaryClient( 6699):    }
W/ApiaryClient( 6699):   ],
W/ApiaryClient( 6699):   "code": 401,
W/ApiaryClient( 6699):   "message": "Login Required"
W/ApiaryClient( 6699):  }
W/ApiaryClient( 6699): }
W/ApiaryClient( 6699): errCount = 1: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6699): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-2283780106463412008&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6699): Headers:
W/ApiaryClient( 6699): accept-encoding: [gzip]
W/ApiaryClient( 6699): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6699): gdata-version: 2
,I/art     (  344): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 181us total 9.817ms
I/art     (  344): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 182us total 8.838ms
W/libprocessgroup( 1031): failed to open /acct/uid_10005/pid_6125/cgroup.procs: No such file or directory
,I/ActivityManager( 1031): Killing 6106:com.lge.bnr/1000 (adj 15): empty #17
W/Uploader( 2112): No account for auth token provided
I/[SystemUI]TimeTickManager( 1447): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1447): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1447): called onTimeUpdated()
I/[SystemUI]Clock( 1447): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1447): called onTimeUpdated()
I/[SystemUI]DateView( 1447): called onTimeUpdated()
I/[SystemUI]DateView( 1447): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1447): handleTimeUpdate
W/libprocessgroup( 1031): failed to open /acct/uid_1000/pid_6106/cgroup.procs: No such file or directory
,W/Uploader( 2112):  no longer exists, so no auth token.
V/NotificationService( 1031): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1031): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1031): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1031): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1031): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
W/GLSActivity( 2112): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2112): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2112): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2112): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2112): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2112): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2112): 	at android.os.Binder.execTransact(Binder.java:446)
D/LgeQuickCoverNLService( 1396): onNotificationPosted
D/SmartCoverUpdateMonitor( 1396): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1396): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1396): handleNotificationPosted(true)
D/QuickCircle( 1396): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1396): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1396): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1396): post do just update job
D/LgeQuickCoverNotificationData( 1396): showAll3
D/LgeQuickCoverNotificationData( 1396): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1396): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1396): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1396): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1396): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1396): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1396): [native noti] inex =  1
D/ContactsSyncAdapter( 2112): innerSync failed
D/ContactsSyncAdapter( 2112): com.google.wireless.gdata2.client.AuthenticationException: unable to get auth token android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
D/ContactsSyncAdapter( 2112): 	at com.google.android.syncadapters.contacts.AuthInfo.getAuthToken(AuthInfo.java:45)
D/ContactsSyncAdapter( 2112): 	at com.google.android.syncadapters.contacts.ContactsSyncAdapter.innerPerformSync(ContactsSyncAdapter.java:263)
D/ContactsSyncAdapter( 2112): 	at com.google.android.syncadapters.contacts.ContactsSyncAdapter.onPerformLoggedSync(ContactsSyncAdapter.java:168)
D/ContactsSyncAdapter( 2112): 	at com.google.android.common.LoggingThreadedSyncAdapter.onPerformSync(LoggingThreadedSyncAdapter.java:33)
D/ContactsSyncAdapter( 2112): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
D/ContactsSyncAdapter( 2112): Caused by: android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
D/ContactsSyncAdapter( 2112): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
D/ContactsSyncAdapter( 2112): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
D/ContactsSyncAdapter( 2112): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
D/ContactsSyncAdapter( 2112): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
D/ContactsSyncAdapter( 2112): 	at android.os.Binder.execTransact(Binder.java:446)
D/LgeQuickCoverNotificationData( 1396): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindo,w( 1396): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1396): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1396): updateNotificationData: count=3
D/SyncManager( 1031): failed sync operation thalitester@gmail.com u0 (com.google), com.android.contacts, LOCAL, currentRunTime 26290, reason: 10019, SyncResult: stats [ numAuthExceptions: 1]
,D/SyncManager( 1031): not retrying sync operation because the error is a hard error: thalitester@gmail.com u0 (com.google), com.android.contacts, LOCAL, currentRunTime 204528, reason: 10019
,D/QuickStatusbarLayout( 1396): Notification difference=198
D/QuickStatusbarLayout( 1396): child = android.widget.LinearLayout{b7d9e1f V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
E/VoldCmdListener(  278): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  278): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6876): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
,E/VoldCmdListener(  278): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  278): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6876): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
E/VoldCmdListener(  278): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  278): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6876): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
E/VoldCmdListener(  278): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  278): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6876): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
,W/Uploader( 2112): No account for auth token provided
D/DelayedSyncController( 6760): Delaying sync.
,D/ChimeraCfgMgr( 2350): Loading module com.google.android.gms.games from APK com.google.android.gms
,I/GoogleURLConnFactory( 2350): Using platform SSLCertificateSocketFactory
,V/GLSActivity( 2112): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2112): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: mail
,I/GLSUser ( 2112): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> mail without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2112): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2112): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2112): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/WebViewFactory( 6876): Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,V/NotificationService( 1031): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
V/NotificationService( 1031): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1031): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1031): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1031): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
W/GLSActivity( 2112): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2112): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2112): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2112): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2112): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2112): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2112): 	at android.os.Binder.execTransact(Binder.java:446)
D/LgeQuickCoverNLService( 1396): onNotificationPosted
W/SubscribedFeeds( 2350): Hard error,
D/SmartCoverUpdateMonitor( 1396): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1396): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1396): handleNotificationPosted(true)
D/QuickCircle( 1396): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1396): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1396): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1396): post do just update job
D/LgeQuickCoverNotificationData( 1396): showAll3
D/LgeQuickCoverNotificationData( 1396): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1396): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1396): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1396): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1396): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1396): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1396): [native noti] inex =  1
,D/LgeQuickCoverNotificationData( 1396): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1396): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1396): isNotificationForCurrentUser : true
I/LibraryLoader( 6876): Loading: webviewchromium
E/LgeQuickCoverOverlayWindow( 1396): updateNotificationData: count=3
D/SyncManager( 1031): failed sync operation thalitester@gmail.com u0 (com.google), subscribedfeeds, PERIODIC, currentRunTime 39349, reason: Periodic, SyncResult: stats [ numAuthExceptions: 1]
D/SyncManager( 1031): not retrying sync operation because the error is a hard error: thalitester@gmail.com u0 (com.google), subscribedfeeds, PERIODIC, currentRunTime 204350, reason: Periodic
I/LibraryLoader( 6876): Time to load native libraries: 7 ms (timestamps 2522-2529)
I/LibraryLoader( 6876): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 6876): Binding Chromium to main looper Looper (main, tid 1) {e61785e}
I/LibraryLoader( 6876): Expected native library version number "",actual native library version number ""
I/chromium( 6876): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
,D/QuickStatusbarLayout( 1396): Notification difference=198
,D/QuickStatusbarLayout( 1396): child = android.widget.LinearLayout{b7d9e1f V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
I/BrowserStartupController( 6876): Initializing chromium process, renderers=0
W/art     ( 6876): Attempt to remove local handle scope entry from IRT, ignoring
,I/PeopleSync( 2350): onPerformSync() [5005f081]
W/chromium( 6876): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
V/AudioPolicyService(  317): registerClient() client 0xb57befa0, uid 10093
I/chromium( 6876): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=38 off=46780 len=2953
W/AudioManagerAndroid( 6876): Requires BLUETOOTH permission
I/chromium( 6876): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:39 off:229536 len:643667
,I/Adreno-EGL( 6876): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 6876): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 6876): Build Date: 12/12/14 금
I/Adreno-EGL( 6876): Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
I/Adreno-EGL( 6876): Remote Branch: 
I/Adreno-EGL( 6876): Local Patches: 
I/Adreno-EGL( 6876): Reconstruct Branch: 
,I/PeopleDatabaseHelper( 2350): cleanUpNonGplusAccounts done.
,V/GLSActivity( 2112): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/libc-netbsd(  313): res_queryN name = clients3.google.com, class = 1, type = 1
D/libc-netbsd(  313): res_queryN name = clients3.google.com succeed
,I/NSApplication( 6876): Starting up...
D/libc-netbsd(  313): res_queryN name = europe.pool.ntp.org succeed
,D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1031): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Mon, 14 Dec 2015 13:40:01 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1450100401380], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1450100401362]}
,D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1031): Don't send network conditions - lacking user consent.
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1031): Validated
D/ConnectivityService( 1031): Validated NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService( 1031): rematching NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService( 1031):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService( 1031):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1031):     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
D/ConnectivityService( 1031): Network NetworkAgentInfo [WIFI () - 100] was already satisfying request 1. No change.
D/ConnectivityService( 1031): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService( 1031):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1031):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1031): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1031): sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityManager.CallbackHandler( 1447): CM callback handler got msg 524290
D/WIFI    ( 1031): new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1031): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
D/WIFI    ( 1031):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/TelephonyNetworkFactory-1( 1850): new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/TelephonyNetworkFactory-1( 1850):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
I/ActivityManager( 1031): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=6940 uid=10097 gids={50097, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
I/ActivityManager( 1031): Killing 6526:com.google.android.talk/u0a72 (adj 15): empty #17
,D/LocSvc_java( 1031): NTP server : europe.pool.ntp.org
D/LocSvc_java( 1031): NTP server returned: 1450100401452 (Mon Dec 14 14:40:01 GMT+01:00 2015) reference: 172737 certainty: 44 system time offset: 0
,D/LocSvc_java( 1031): Sending msg: 10 arg1:0 arg2:1
W/libprocessgroup( 1031): failed to open /acct/uid_10072/pid_6526/cgroup.procs: No such file or directory
,D/TelephonyIcons( 1447): null signal icon name: drawable/stat_sys_signal_null
D/StatusBar.NetworkController( 1447): refreshViews: Data not connected!! Set no data type icon / Roaming
W/ResourcesManager( 6940): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
D/StatusBar.NetworkController( 1447): refreshViews: Data not connected!! Set no data type icon / Roaming
I/PeopleSync( 2350): Setting subscription: result=true [5005f081]
,I/PeopleSync( 2350): Starting sync, feed=null [5005f081]
,I/art     ( 2350): Explicit concurrent mark sweep GC freed 13656(1114KB) AllocSpace objects, 21(336KB) LOS objects, 49% free, 32MB/64MB, paused 2.501ms total 79.073ms
,V/GLSActivity( 2112): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/BaseAppContext( 2350): Using Auth Proxy for data requests.
,W/BaseAppContext( 2350): Using Auth Proxy for data requests.
,I/GLSUser ( 2112): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 2112): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2112): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2112): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2112): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/BaseAppContext( 2350): Using Auth Proxy for data requests.
,V/NotificationService( 1031): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
V/NotificationService( 1031): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1031): LED remove() : mLights=0|com.google.android.gms|1|null|10005
,D/NotificationServiceEx( 1031): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1031): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1396): onNotificationPosted
D/SmartCoverUpdateMonitor( 1396): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1396): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1396): handleNotificationPosted(true)
,D/QuickCircle( 1396): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1396): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1396): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1396): post do just update job
D/LgeQuickCoverNotificationData( 1396): showAll3
D/LgeQuickCoverNotificationData( 1396): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1396): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1396): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1396): showNotificationWithSetupData: display=false
,D/LgeQuickCoverOverlayWindow( 1396): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1396): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1396): [native noti] inex =  1
W/GLSActivity( 2112): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2112): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2112): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2112): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2112): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2112): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2112): 	at android.os.Binder.execTransact(Binder.java:446)
D/LgeQuickCoverNotificationData( 1396): isNotificationForCurrentUser : true
E/BooksAccountManager( 6699): Authentication error
E/BooksAccountManager( 6699): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6699): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6699): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6699): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6699): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6699): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6699): null auth token
D/LgeQuickCoverOverlayWindow( 1396): [native noti] inex =  2
I/PeopleSync( 2350): Sync start: cannotHavePeople=true isPageExistenceCheckOnly=false
D/LgeQuickCoverNotificationData( 1396): isNotificationForCurrentUser : true
I/iu.SyncManager( 2350): SYNC; picasa accounts
E/LgeQuickCoverOverlayWindow( 1396): updateNotificationData: count=3
,D/NetworkLogImpl( 2350): Loaded NetworkSpeedPredictor
D/QuickStatusbarLayout( 1396): Notification difference=198
D/QuickStatusbarLayout( 1396): child = android.widget.LinearLayout{b7d9e1f V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
I/iu.Environment( 2350): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/iu.UploadsManager( 2350): num queued entries: 0
I/iu.UploadsManager( 2350): num updated entries: 0
,I/iu.SyncManager( 2350): NEXT; no task
D/ChimeraCfgMgr( 2350): Loading module com.google.android.gms.kids from APK com.google.android.gms
I/art     ( 2112): Explicit concurrent mark sweep GC freed 31823(1778KB) AllocSpace objects, 11(1351KB) LOS objects, 50% free, 31MB/63MB, paused 1.428ms total 70.045ms
D/ChimeraCfgMgr( 2350): Loading module com.google.android.gms.kids from APK com.google.android.gms
D/libc-netbsd(  313): default dns: query_ipv6=0, query_ipv4=1
,D/libc-netbsd(  313): res_queryN name = mtalk.google.com, class = 1, type = 1
D/PostponalbeReceiver( 5174): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.intent.action.TIME_SET'.
I/GLSUser ( 2112): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/gcm
I/GLSUser ( 2112): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/gcm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2112): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2112): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,W/ApiaryClient( 6699): Error response from books API: {
W/ApiaryClient( 6699):  "error": {
W/ApiaryClient( 6699):   "errors": [
W/ApiaryClient( 6699):    {
W/ApiaryClient( 6699):     "domain": "global",
W/ApiaryClient( 6699):     "reason": "required",
W/ApiaryClient( 6699):     "message": "Login Required",
W/ApiaryClient( 6699):     "locationType": "header",
W/ApiaryClient( 6699):     "location": "Authorization"
W/ApiaryClient( 6699):    }
W/ApiaryClient( 6699):   ],
W/ApiaryClient( 6699):   "code": 401,
W/ApiaryClient( 6699):   "message": "Login Required"
W/ApiaryClient( 6699):  }
W/ApiaryClient( 6699): }
W/ApiaryClient( 6699): errCount = 2: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6699): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-2283780106463412008&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6699): Headers:
W/ApiaryClient( 6699): accept-encoding: [gzip]
W/ApiaryClient( 6699): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6699): gdata-version: 2
I/GLSActivity( 2112): [ac] getting account id
D/libc-netbsd(  313): res_queryN name = mtalk.google.com succeed
I/ActivityManager( 1031): Start proc com.lge.clock for broadcast com.lge.clock/.alarmclock.ALBootInit: pid=6979 uid=10010 gids={50010, 9997, 3003, 1028, 4002} abi=armeabi-v7a
,V/GLSActivity( 2112): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/GLSUser ( 2112): [t] Fetched account id for thalitester@gmail.com : 105256135866144380227
I/GLSUser ( 2112): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: ac2dm
I/GLSUser ( 2112): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> ac2dm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2112): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2112): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2112): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/GcmGroups( 2350): Failed to subscribe to group.
I/GcmGroups( 2350): com.google.android.gms.auth.ad: BadAuthentication
I/GcmGroups( 2350): 	at com.google.android.gms.auth.p.b(SourceFile:442)
I/GcmGroups( 2350): 	at com.google.android.gms.auth.p.a(SourceFile:365)
I/GcmGroups( 2350): 	at com.google.android.gms.auth.p.a(SourceFile:318)
I/GcmGroups( 2350): 	at com.google.android.gms.gcm.gmsproc.b.a(SourceFile:443)
I/GcmGroups( 2350): 	at com.google.android.gms.gcm.gmsproc.b.a(SourceFile:333)
I/GcmGroups( 2350): 	at com.google.android.gms.gcm.gmsproc.b.a(SourceFile:240)
I/GcmGroups( 2350): 	at com.google.android.gms.gcm.gmsproc.GcmReceiverService.onHandleIntent(SourceFile:50)
I/GcmGroups( 2350): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
I/GcmGroups( 2350): 	at android.os.Handler.dispatchMessage(Handler.java:102)
I/GcmGroups( 2350): 	at android.os.Looper.loop(Looper.java:135)
I/GcmGroups( 2350): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/GcmGroups( 2350): Groups upload failed, retrying in 24000:00:00
,I/GLSUser ( 2112): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.media.upload https://www.googleapis.com/auth/plus.pages.manage https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.profiles.read https://www.googleapis.com/auth/plus.profiles.write https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.peopleapi.readwrite https://www.googleapis.com/auth/plus.applications.manage https://www.googleapis.com/auth/plus.settings
I/GLSUser ( 2112): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.media.upload https://www.googleapis.com/auth/plus.pages.manage https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.profiles.read https://www.googleapis.com/auth/plus.profiles.write https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.peopleapi.readwrite https://www.googleapis.com/auth/plus.applications.manage https://www.googleapis.com/auth/plus.settings without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2112): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2112): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2112): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1031): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1031): pkg=com.google.android.gms canInterrupt=false intercept=true
,I/NotificationServiceEx( 1031): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1031): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1031): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1396): onNotificationPosted
D/SmartCoverUpdateMonitor( 1396): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1396): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1396): handleNotificationPosted(true)
D/QuickCircle( 1396): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1396): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1396): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1396): post do just update job
D/LgeQuickCoverNotificationData( 1396): showAll3
D/LgeQuickCoverNotificationData( 1396): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1396): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1396): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1396): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1396): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1396): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1396): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1396): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1396): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1396): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1396): updateNotificationData: count=3
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
,I/PeopleSync( 2350): Sync finished, successful=false, took 171ms
D/QuickStatusbarLayout( 1396): Notification difference=198
D/QuickStatusbarLayout( 1396): child = android.widget.LinearLayout{b7d9e1f V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,I/PeopleSync( 2350): Cannot authenticate [5005f081]
I/PeopleSync( 2350): com.google.android.gms.auth.ad: BadAuthentication
I/PeopleSync( 2350): 	at com.google.android.gms.auth.p.b(SourceFile:442)
I/PeopleSync( 2350): 	at com.google.android.gms.auth.p.a(SourceFile:365)
I/PeopleSync( 2350): 	at com.google.android.gms.auth.p.a(SourceFile:310)
I/PeopleSync( 2350): 	at com.google.android.gms.common.server.a.a.b(SourceFile:97)
I/PeopleSync( 2350): 	at com.google.android.gms.common.server.c.b(SourceFile:109)
I/PeopleSync( 2350): 	at com.google.android.gms.common.server.o.b(SourceFile:30)
I/PeopleSync( 2350): 	at com.google.android.gms.people.service.g.b(SourceFile:171)
I/PeopleSync( 2350): 	at com.google.android.gms.common.server.o.b(SourceFile:370)
I/PeopleSync( 2350): 	at com.google.android.gms.common.server.o.a(SourceFile:340)
I/PeopleSync( 2350): 	at com.google.android.gms.common.server.o.a(SourceFile:319)
I/PeopleSync( 2350): 	at com.google.android.gms.plus.service.v2whitelisted.b.a(SourceFile:1184)
I/PeopleSync( 2350): 	at com.google.android.gms.people.sync.aa.g(SourceFile:1086)
I/PeopleSync( 2350): 	at com.google.android.gms.people.sync.aa.a(SourceFile:241)
I/PeopleSync( 2350): 	at com.google.android.gms.people.sync.s.a(SourceFile:283)
I/PeopleSync( 2350): 	at com.google.android.gms.people.sync.s.a(SourceFile:191)
I/PeopleSync( 2350): 	at com.google.android.gms.people.sync.s.a(SourceFile:93)
I/PeopleSync( 2350): 	at com.google.android.gms.common.j.a.onPerformSync(SourceFile:81)
I/PeopleSync( 2350): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
,I/art     ( 1031): Explicit concurrent mark sweep GC freed 31497(1417KB) AllocSpace objects, 7(624KB) LOS objects, 33% free, 44MB/66MB, paused 1.676ms total 90.984ms
D/ALBootInit( 6979): ====action==>android.intent.action.TIME_SET
,D/ALBootInit( 6979): Alarm ALBootInit: TIME_SET
D/Alarms  ( 6979): [setNextAlert] start
D/Alarms  ( 6979): [setNextAlert] (1)
D/Alarms  ( 6979):  minTime  = 0
,D/Alarms  ( 6979):  -- OK multi -- 0
E/jeny.kim( 6979): [setNextAlert] setNextAlert  temp_Alarmlink + 
E/jeny.kim( 6979): [setNextAlert]setNextAlert temp_AlarmLinkText + 
I/CommonUtil( 6979): BUILD Country: EU
D/Alarms  ( 6979): broadcastToWidgetProvider : false
,D/GCM     ( 2112): Connected
D/Alarms  ( 6979): Enter formatDayAndTime(final Context context, long timeInMiliSec)
,V/SettingsProvider( 1031): call_put(system:next_alarm_formatted=) for 0 calling package = com.lge.clock
,I/DigitalAppWidgetProvider( 6979): onReceive: android.intent.action.TIME_SET
I/GCM     ( 2112): Ack for not saved message 92
D/GCM     ( 2112): Message class com.google.f.a.a.p
I/PeopleSync( 2350): ***Sync finished***, duration: 1055 [5005f081]
,V/DigitalAppWidgetProvider( 6979): cancelAlarmOnQuarterHour android.app.ReceiverRestrictedContext@2076f544
V/DigitalAppWidgetProvider( 6979): startAlarmOnQuarterHour android.app.ReceiverRestrictedContext@2076f544
D/QuickCoverProvider( 6979): onReceiver
I/indal   ( 1396): SmartCoverWidgetContext createApplicationContext
I/indal   ( 1396): SmartCoverWidgetContext createApplicationContext
,D/WeatherAncestor( 6855): 2 : onReceive, action: android.intent.action.TIME_SET, Time(hour:min:sec) 14:40:2
D/Weather.Utils( 6855): 2 : the weather widgets(using time tick) are gone.
D/Weather.Utils( 6855): 2 : All the weather widget is gone.
D/UpdateThreadPoolManager( 6855): 2 : This is isUpdating : false
,D/WeatherService( 6855): 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@7f9562d
D/ForecastDataCache( 6855): 2 : lastUpdatedTime: 1430558561343
D/ForecastDataCache( 6855): 2 : currentPackageVersion: 4.40.4
D/ForecastDataCache( 6855): 2 : Cache is up-to-date, count: 0
D/Weather_cast( 6855): 2 : set auto-update time : 12/14 17:40
D/SyncManager( 1031): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.gms.people, PERIODIC, currentRunTime 39416, reason: Periodic, SyncResult: stats [ numAuthExceptions: 1]
D/SyncManager( 1031): not retrying sync operation because the error is a hard error: thalitester@gmail.com u0 (com.google), com.google.android.gms.people, PERIODIC, currentRunTime 205014, reason: Periodic
,D/WeatherAncestor( 6855): 2 : onReceive has processed, action: android.intent.action.TIME_SET, Time(hour:min:sec) 14:40:2
I/ActivityManager( 1031): Start proc com.google.android.syncadapters.calendar for service com.google.android.syncadapters.calendar/.CalendarSyncAdapterService: pid=7010 uid=10069 gids={50069, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager( 1031): Start proc com.qualcomm.timeservice for broadcast com.qualcomm.timeservice/.TimeServiceBroadcastReceiver: pid=7027 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
I/ActivityManager( 1031): Killing 6357:com.lge.lifetracker/u0a37 (adj 15): empty #17
,W/libprocessgroup( 1031): failed to open /acct/uid_10037/pid_6357/cgroup.procs: No such file or directory
,D/TimeService( 7027): Receivedandroid.intent.action.TIME_SET intent. Current Time is 1450100402573
,D/        ( 7027): TimeServiceNative: User Time to be set is 1450100402573
,D/QC-time-services( 7027): Lib:time_genoff_operation: pargs->base = 2
D/QC-time-services( 7027): Lib:time_genoff_operation: pargs->operation = 0
D/QC-time-services( 7027): Lib:time_genoff_operation: pargs->ts_val = 1450100402573
D/QC-time-services(  358): Daemon: Connection accepted:time_genoff
D/QC-time-services( 7027): Lib:time_genoff_operation: Send to server  passed!!
D/QC-time-services(  358): Daemon:Received base = 2, unit = 1, operation = 0,value = 1450100402573
D/QC-time-services(  358): Daemon:genoff_opr: Base = 2, val = 1450100402573, operation = 0
D/QC-time-services(  358): Daemon:rtc_get: Time read from RTC -- MM/DD/YY HH:MM:SS3/23/70 6:52:42
D/QC-time-services(  358): Daemon:Value read from RTC seconds = 9701562000
D/QC-time-services(  358): Daemon:new time 1450100402573 
D/QC-time-services(  358): Daemon: delta 1440398840573 genoff 1440398840573 
D/QC-time-services(  358): Daemon:genoff_persistent_update: Writing genoff = 1440398840573 to memory
D/QC-time-services(  358): Daemon:Opening File: /data/time/ats_2
D/QC-time-services(  358): Daemon:time_persistent_memory_opr:Genoff write operation 
D/QC-time-services(  358): Updating the TOD offset
D/QC-time-services(  358): Daemon:genoff_persistent_update: Writing genoff = 1440398840573 to memory
D/QC-time-services(  358): Daemon:Opening File: /data/time/ats_1
D/QC-time-services(  358): Daemon:time_persistent_memory_opr:Genoff write operation 
,E/QC-time-services(  358): Daemon:Update to modem bit set
D/QC-time-services(  358): Daemon:genoff_send_modem: Sending data to MODEM !
D/QC-time-services(  358): Daemon: Base = 2, Value being sent to MODEM = 1124434040573
E/QC-time-services( 7027): Receive Passed == base = 2, unit = 1, operation = 0, result = 0
E/QC-time-services(  358): Daemon:tod_update_ind_cb: Got Update from modem msg_id 40
E/QC-time-services(  358): Daemon: Time-services: Waiting to acceptconnection
W/AbstractGoogleClient( 7010): Application name is not set. Call Builder#setApplicationName.
,I/ActivityManager( 1031): Start proc com.android.calendar for broadcast com.android.calendar/.widget.CalendarAppWidgetProvider: pid=7045 uid=10013 gids={50013, 9997, 3003, 1028, 1015} abi=armeabi
I/ActivityManager( 1031): Killing 6442:com.lge.settings.easy/1000 (adj 15): empty #17
W/libprocessgroup( 1031): failed to open /acct/uid_1000/pid_6442/cgroup.procs: No such file or directory
,W/ResourcesManager( 7045): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/ActivityManager( 1031): Start proc com.android.providers.calendar for content provider com.android.providers.calendar/.CalendarProvider2: pid=7066 uid=10014 gids={50014, 9997, 3003, 1028, 1015} abi=armeabi
,D/CalendarApplication( 7045): CalendarApplication.onCreate()
,D/PreferenceKeysParser( 7045): [debug_displayParseInfos] preference keys.size() = 44
D/PreferenceKeysParser( 7045): [debug_displayParseInfos] preference keys = {lg_preferences_tardis_1=com.android.calendar.adaptation.PreferenceKey$KeyData@21dadd7b, lg_preferences_hide_declined=com.android.calendar.adaptation.PreferenceKey$KeyData@21cdf798, lg_preferences_default_reminder=com.android.calendar.adaptation.PreferenceKey$KeyData@3db2ebf1, lg_preferences_month_view_style=com.android.calendar.adaptation.PreferenceKey$KeyData@367813d6, lg_preferences_alerts_ringtone=com.android.calendar.adaptation.PreferenceKey$KeyData@34afd657, lg_preferences_device_tz=com.android.calendar.adaptation.PreferenceKey$KeyData@2076f544, lg_preferences_debug_datesearch=com.android.calendar.adaptation.PreferenceKey$KeyData@7f9562d, lg_preferences_debug_country=com.android.calendar.adaptation.PreferenceKey$KeyData@31399762, lg_preferences_display_weather_information=com.android.calendar.adaptation.PreferenceKey$KeyData@397180f3, lg_preferences_alerts_vibrateWhen=com.android.calendar.adaptation.PreferenceKey$KeyData@399021b0, lg_preferences_debug_rtl=com.android.calendar.adaptation.PreferenceKey$KeyData@2ac22829, lg_preferences_alerts_type=com.android.calendar.adaptation.PreferenceKey$KeyData@159dc7ae, lg_preferrences_country_code=com.android.calendar.adaptation.PreferenceKey$KeyData@2599394f, lg_preferences_weather_info=com.android.calendar.adaptation.PreferenceKey$KeyData@13cda8dc, lg_preference_holiday_calendar_ver=com.android.calendar.adaptation.PreferenceKey$KeyData@e2c1de5, lg_preferences_show_controls=com.android.calendar.adaptation.PreferenceKey$KeyData@3e02b0ba, lg_preferences_user_select_noti_sound=com.android.calendar.adaptation.PreferenceKey$KeyData@22da1b6b, lg_preference_default_myphonebook=com.android.calendar.adaptation.PreferenceKey$KeyData@2afa76c8, lg_preferences_skip_setup=com.android.calendar.adaptation.PreferenceKey$KeyData@385b361, lg_preferred_startView=com.android.calendar.adaptation.PreferenceKey$KeyData@1a9b1e86, lg_preferences_debug_operator=com.android.calendar.adaptation.PreferenceKey$KeyData@38fd0347, lg_preferences_exclude_sticker_list=com.android.calendar.adaptation.PreferenceKey$KeyData@2aa43774, lg_preferences_writable_calendars_count=com.android.calendar.adaptation.PreferenceKey$KeyData@889249d, lg_preferred_detailedView=com.android.calendar.adaptation.PreferenceKey$KeyData@19fa9d12, lg_preferences_debug_floating=com.android.calendar.adaptation.PreferenceKey$KeyData@397c8ce3, lg_preferences_home_tz=com.android.calendar.adaptation.PreferenceKey$KeyData@78756e0, lg_preferences_home_tz_enabled=com.android.calendar.adaptation.PreferenceKey$KeyData@2586d99, lg_preference_received_provider_reminder_broadcast=com.android.calendar.adaptation.PreferenceKey$KeyData@e61785e, lg_preferences_default_cell_height=com.android.calendar.adaptation.PreferenceKey$KeyData@8e1143f, lg_preferences_notification_type=com.android.calendar.adaptation.PreferenceKey$KeyData@3bb010c, lg_preferences_show_week_num=com.android.calendar.adaptation.PreferenceKey$KeyData@2c394a55, lg_preferences_dont_show_again_no_online_account=com.android.calendar.adaptation.PreferenceKey$KeyData@1bc8bc6a, lg_preferences_alerts_popup=com.android.calendar.adaptation.PreferenceKey$KeyData@21dcb55b, lg_preferences_week_start_day=com.android.calendar.adaptation.PreferenceKey$KeyData@99d21f8, lg_preferences_app_version=com.android.calendar.adaptation.PreferenceKey$KeyData@361136d1, lg_preferences_alerts=com.android.calendar.adaptation.PreferenceKey$KeyData@3aae3536, lg_preferences_select_aux_calendar=com.android.calendar.adaptation.PreferenceKey$KeyData@2e274c37, lg_preferences_widget_info_calendars=com.android.calendar.adaptation.PreferenceKey$KeyData@97e65a4, lg_preferences_alerts_default_ringtone=com.android.calendar.adaptation.PreferenceKey$KeyData@ea16f0d, lg_preference_defaultCalendar=com.android.calendar.adaptation.PreferenceKey$KeyData@1ba06ec2, lg_preferences_alerts_vibratetype=com.android.calendar.adaptation.PreferenceKey$KeyData@111a74d3, lg_preferences_recent_,timezones=com.android.calendar.adaptation.PreferenceKey$KeyData@60e3810, l
D/GeneralPreferenceUtils( 7045): [migratePrefrenceKeys] Exit: Version(44001600) >= 42001300
,D/Config  ( 7045): [init]
,I/Config  ( 7045): LGCalendar ver.4.40.16
I/Config  ( 7045): start check model
I/Config  ( 7045): start check native_ca
I/Config  ( 7045): Config Operator=OPEN, Country=EU
D/Config  ( 7045): [setDefaultValuesToPref]
D/Config  ( 7045): [parseProfiles]
W/ResourcesManager( 7066): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
D/ProfilesParser( 7045): [debug_displayParseInfos] profile.country = null
D/ProfilesParser( 7045): [debug_displayParseInfos] profile.operator = null
D/Config  ( 7045): [updateProfiletoCountryInfo]
D/GeneralPreference( 7045): [checkAndMigrateOldPreference]
,E/AgendaWidgetManager( 7045): [updateWidgets] 
,I/InitNotificationRingtoneService( 7045): Start InitializeAlertRingtoneService.onHandleIntent
I/AlertUtils( 7045): [setFormatNotificationSound] current noti URI = content://media/internal/audio/media/41
D/CalendarProvider2( 7066): [initialize] mInstance = com.android.providers.calendar.CalendarProvider2@583ed75
I/AlertUtils( 7045): [getCalendarNotiSoundURIFromCursor] getCount()= 21
,I/AlertUtils( 7045): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Arpeggio.ogg
I/AlertUtils( 7045): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Country_Blues.ogg
,D/CalendarProvider2( 7066): [getOrCreateCalendarAlarmManager]
I/CalendarProvider2( 7066): Created com.android.providers.calendar.CalendarAlarmManager@367813d6(com.android.providers.calendar.CalendarProvider2@583ed75)
V/GLSActivity( 2112): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/AlertUtils( 7045): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Crystal.ogg
I/AlertUtils( 7045): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Dewdrop.ogg
,I/AlertUtils( 7045): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Ding_Dong.ogg
,I/AlertUtils( 7045): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Echo.ogg
I/GLSUser ( 2112): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2112): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2112): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2112): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
I/AlertUtils( 7045): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Email.ogg
,V/GLSActivity( 2112): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/AlertUtils( 7045): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Game_Over.ogg
I/AlertUtils( 7045): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Gayageum.ogg
,I/AlertUtils( 7045): [getMediaFilepathFromContentUri] filepath = /system/media/audio/alarms/Afternoon_Walk.ogg
I/AlertUtils( 7045): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Harmonics.ogg
I/AlertUtils( 7045): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Idea.ogg
,I/AlertUtils( 7045): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/News.ogg
V/NotificationService( 1031): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,I/AlertUtils( 7045): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Pebble.ogg
V/NotificationService( 1031): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1031): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1031): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1031): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1396): onNotificationPosted
W/GLSActivity( 2112): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2112): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2112): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2112): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2112): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2112): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2112): 	at android.os.Binder.execTransact(Binder.java:446)
I/AlertUtils( 7045): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Schedule.ogg
I/AlertUtils( 7045): [getCalendarNotiSoundURIFromCursor] filePath = /system/media/audio/notifications/Schedule.ogg, new URI = content://media/internal/audio/media/41
,D/SmartCoverUpdateMonitor( 1396): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1396): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1396): handleNotificationPosted(true)
D/QuickCircle( 1396): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1396): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1396): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1396): post do just update job
D/LgeQuickCoverNotificationData( 1396): showAll3
D/LgeQuickCoverNotificationData( 1396): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1396): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1396): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1396): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1396): [native noti] inex =  0
I/AlertUtils( 7045): set default noti to content://media/internal/audio/media/41
D/LgeQuickCoverNotificationData( 1396): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1396): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1396): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1396): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1396): isNotificationForCurrentUser : true
E/BooksAccountManager( 6699): Authentication error
E/BooksAccountManager( 6699): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6699): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6699): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6699): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6699): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6699): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6699): null auth token
E/LgeQuickCoverOverlayWindow( 1396): updateNotificationData: count=3
I/InitNotificationRingtoneService( 7045): End InitializeAlertRingtoneService.onHandleIntent
,D/QuickStatusbarLayout( 1396): Notification difference=198
D/QuickStatusbarLayout( 1396): child = android.widget.LinearLayout{b7d9e1f V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=3.6, 0.0, 0.0  rx=2.8 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1598542908] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=3.6, 0.0, 0.0  rx=2.8 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-1598542907] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,W/HolidayIntentService( 7045): onHandleIntent
D/HolidayDataLoader( 7045): readJsonAsset : holiday.json
D/MonthWidgetProvider( 7045): [onReceive]
D/CalendarWidgetProvider( 7045): [onReceive]
D/CalendarWidgetProvider( 7045): [CalendarWidgetProvider] got the intent: Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.android.calendar/.widget.MonthWidgetProvider }
D/CalendarTypeController( 7045): [onUpdateAndInitCalendarTime]
,D/WeekWidgetProvider( 7045): [onReceive]
D/CalendarWidgetProvider( 7045): [onReceive]
D/CalendarWidgetProvider( 7045): [CalendarWidgetProvider] got the intent: Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.android.calendar/.widget.WeekWidgetProvider }
D/CalendarTypeController( 7045): [onUpdateAndInitCalendarTime]
W/ApiaryClient( 6699): Error response from books API: {
W/ApiaryClient( 6699):  "error": {
W/ApiaryClient( 6699):   "errors": [
W/ApiaryClient( 6699):    {
W/ApiaryClient( 6699):     "domain": "global",
W/ApiaryClient( 6699):     "reason": "required",
W/ApiaryClient( 6699):     "message": "Login Required",
W/ApiaryClient( 6699):     "locationType": "header",
W/ApiaryClient( 6699):     "location": "Authorization"
W/ApiaryClient( 6699):    }
W/ApiaryClient( 6699):   ],
W/ApiaryClient( 6699):   "code": 401,
W/ApiaryClient( 6699):   "message": "Login Required"
W/ApiaryClient( 6699):  }
W/ApiaryClient( 6699): }
,W/ApiaryClient( 6699): errCount = 3: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6699): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-2283780106463412008&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6699): Headers:
W/ApiaryClient( 6699): accept-encoding: [gzip]
W/ApiaryClient( 6699): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6699): gdata-version: 2
V/QRemote ( 6480): [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.wait_loading
D/QRemote ( 6480): [RemoteAppWidgetProvider.java:211:onReceive()] oooooo 140514:alarm msg received!:2560
D/PowerManagerServiceEx( 1031): releaseWakeLockInternal: lock=257990054 [*alarm*], flags=0x0
E/HolidayIntentService( 7045): onHandleIntent:holiday data empty
I/ActivityManager( 1031): Killing 6403:com.lge.sync/1000 (adj 15): empty #17
,W/libprocessgroup( 1031): failed to open /acct/uid_1000/pid_6403/cgroup.procs: No such file or directory
,I/DigitalAppWidgetProvider( 6979): onReceive: android.intent.action.ALARM_CHANGED
,D/GCM     ( 2112): GcmService start Intent { act=com.google.android.gcm.intent.SEND flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.gcm.intent.SEND
,I/GLSUser ( 2112): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.syncadapters.calendar, service: oauth2:https://www.googleapis.com/auth/calendar
,I/GLSUser ( 2112): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/calendar without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2112): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2112): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
I/ActivityManager( 1031): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.realtimechat.RequestWriter$NetworkStateReceiver: pid=7098 uid=10072 gids={50072, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,V/GLSActivity( 2112): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/NotificationService( 1031): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1031): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1031): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1031): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1031): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1396): onNotificationPosted
D/SmartCoverUpdateMonitor( 1396): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1396): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1396): handleNotificationPosted(true)
D/QuickCircle( 1396): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1396): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1396): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1396): post do just update job
D/LgeQuickCoverNotificationData( 1396): showAll3
D/LgeQuickCoverNotificationData( 1396): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1396): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1396): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1396): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1396): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1396): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1396): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1396): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1396): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1396): isNotificationForCurrentUser : true
,E/LgeQuickCoverOverlayWindow( 1396): updateNotificationData: count=3
W/ResourcesManager( 7098): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
E/CalendarSyncAdapter( 7010): Exception in onPerformLoggedSync 
E/CalendarSyncAdapter( 7010): com.google.android.apiary.AuthenticationException: Could not get an auth token
E/CalendarSyncAdapter( 7010): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(GoogleRequestInitializer.java:152)
E/CalendarSyncAdapter( 7010): 	at com.google.android.apiary.GoogleRequestInitializer.intercept(GoogleRequestInitializer.java:89)
E/CalendarSyncAdapter( 7010): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:858)
E/CalendarSyncAdapter( 7010): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(AbstractGoogleClientRequest.java:410)
E/CalendarSyncAdapter( 7010): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(AbstractGoogleClientRequest.java:343)
E/CalendarSyncAdapter( 7010): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(AbstractGoogleClientRequest.java:460)
E/CalendarSyncAdapter( 7010): 	at com.google.android.syncadapters.calendar.CalendarSyncAdapterApiary.processAccountCalendars(CalendarSyncAdapterApiary.java:1510)
E/CalendarSyncAdapter( 7010): 	at com.google.android.syncadapters.calendar.CalendarSyncAdapterApiary.updateCalendarsFromServerFeed(CalendarSyncAdapterApiary.java:1024)
E/CalendarSyncAdapter( 7010): 	at com.google.android.syncadapters.calendar.CalendarSyncAdapterApiary.getServerDiffs(CalendarSyncAdapterApiary.java:906)
E/CalendarSyncAdapter( 7010): 	at com.google.android.syncadapters.calendar.CalendarSyncAdapterApiary.performSync(CalendarSyncAdapterApiary.java:430)
E/CalendarSyncAdapter( 7010): 	at com.google.android.syncadapters.calendar.CalendarSyncAdapterApiary.onPerformLoggedSync(CalendarSyncAdapterApiary.java:335)
E/CalendarSyncAdapter( 7010): 	at com.google.android.common.LoggingThreadedSyncAdapter.onPerformSync(LoggingThreadedSyncAdapter.java:33)
E/CalendarSyncAdapter( 7010): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/CalendarSyncAdapter( 7010): Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/CalendarSyncAdapter( 7010): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/CalendarSyncAdapter( 7010): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/CalendarSyncAdapter( 7010): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(GoogleRequestInitializer.java:140)
E/CalendarSyncAdapter( 7010): 	... 12 more
,I/ActivityManager( 1031): Killing 6324:com.android.settings/1000 (adj 15): empty #17
D/QuickStatusbarLayout( 1396): Notification difference=198
D/QuickStatusbarLayout( 1396): child = android.widget.LinearLayout{b7d9e1f V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
D/WifiService( 1031): Client connection lost with reason: 4
,W/libprocessgroup( 1031): failed to open /acct/uid_1000/pid_6324/cgroup.procs: No such file or directory
,D/SyncManager( 1031): failed sync operation thalitester@gmail.com u0 (com.google), com.android.calendar, PERIODIC, currentRunTime 39469, reason: Periodic, SyncResult: stats [ numAuthExceptions: 1]
D/SyncManager( 1031): not retrying sync operation because the error is a hard error: thalitester@gmail.com u0 (com.google), com.android.calendar, PERIODIC, currentRunTime 207483, reason: Periodic
,I/ActivityManager( 1031): Killing 5667:com.android.vending/u0a44 (adj 15): empty #17
,D/LgDataFeature( 7098): LgDataFeature() Constructor: none
,D/LgDataFeature( 7098): LgDataFeature() Constructor Done, null
W/libprocessgroup( 1031): failed to open /acct/uid_10044/pid_5667/cgroup.procs: No such file or directory
,I/Babel   ( 7098): MmsConfig: mnc/mcc: 0/0
I/Babel   ( 7098): MmsConfig.loadMmsSettings
I/Babel   ( 7098): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D855 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D855-M3-D1.xml
I/Babel   ( 7098): MmsConfig.loadFromDatabase
,E/Babel   ( 7098): canonicalizeMccMnc: invalid mccmnc 
I/Babel   ( 7098): MmsConfig.loadFromResources
E/Babel   ( 7098): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel   ( 7098): MmsConfig.loadMmsSettings: mUserAgent=LG-D855 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D855-M3-D1.xml
,W/Settings( 7098): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/AudioCapabilities( 7098): Unsupported mime audio/evrc
W/AudioCapabilities( 7098): Unsupported mime audio/qcelp
,W/VideoCapabilities( 7098): Unrecognized profile 2130706433 for video/avc
W/AudioCapabilities( 7098): Unsupported mime audio/amr-wb-plus
,W/AudioCapabilities( 7098): Unsupported mime audio/qcelp
W/AudioCapabilities( 7098): Unsupported mime audio/evrc
D/WeatherAncestor( 6855): 2 : onReceive, action: com.lge.sizechangable.weather.action.setweathercast, Time(hour:min:sec) 14:40:3
,I/GCoreUlr( 1812): Uploading GCM registration ID for account#2#
D/Weather.Utils( 6855): 2 : the weather widgets(using time tick) are gone.
D/Weather.Utils( 6855): 2 : All the weather widget is gone.
D/UpdateThreadPoolManager( 6855): 2 : This is isUpdating : false
D/Weather_cast( 6855): 2 : Update is Canceled by com.lge.sizechangable.weather.action.alarm
D/WeatherAncestor( 6855): 2 : onReceive has processed, action: com.lge.sizechangable.weather.action.setweathercast, Time(hour:min:sec) 14:40:4
,W/VideoCapabilities( 7098): Unsupported mime video/x-ms-wmv
W/VideoCapabilities( 7098): Unsupported mime video/divx
W/VideoCapabilities( 7098): Unsupported mime video/divx311
,W/VideoCapabilities( 7098): Unsupported mime video/divx4
W/BaseAppContext( 1812): Using Auth Proxy for data requests.
W/VideoCapabilities( 7098): Unsupported mime video/mp4v-esdp
W/ResourcesManager( 7098): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 7098): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/GLSUser ( 1812): [ChannelManager] Attempting to channel bind connection HttpClient.
I/GLSUser ( 1812): [ChannelManager] Checking whether channelId is enabled. isEnabledGmsCore? false, isEnabledSdk? true, isAtLeastKitKat? true
,I/VideoCapabilities( 7098): Unsupported profile 4 for video/mp4v-es
W/AudioCapabilities( 7098): Unsupported mime audio/eac3
W/AudioCapabilities( 7098): Unsupported mime audio/ac3
W/AudioCapabilities( 7098): Unsupported mime audio/g726
W/AudioCapabilities( 7098): Unsupported mime audio/wma-voice
W/AudioCapabilities( 7098): Unsupported mime audio/x-ms-wma
W/AudioCapabilities( 7098): Unsupported mime audio/adpcm
W/VideoCapabilities( 7098): Unsupported mime video/theora
,W/VideoCapabilities( 7098): Unsupported mime video/mjpg
V/JNIHelp ( 7098): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,W/System  ( 7098): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/system/framework/com.google.android.media.effects.jar", zip file "/system/app/Hangouts/Hangouts.apk"],nativeLibraryDirectories=[/system/app/Hangouts/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 7098): Installed default security provider GmsCore_OpenSSL
,I/art     ( 1031): Explicit concurrent mark sweep GC freed 18095(808KB) AllocSpace objects, 3(304KB) LOS objects, 33% free, 44MB/66MB, paused 1.278ms total 89.995ms
,E/BooksSync( 6699): Soft error: 
E/BooksSync( 6699): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 6699): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-2283780106463412008&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 6699): Headers:
E/BooksSync( 6699): accept-encoding: [gzip]
E/BooksSync( 6699): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 6699): gdata-version: 2
E/BooksSync( 6699): 
E/BooksSync( 6699): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 6699): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 6699): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 6699): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 6699): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 6699): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 6699): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 6699): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 6699): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 6699): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 6699): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 6699): {
E/BooksSync( 6699):  "error": {
E/BooksSync( 6699):   "errors": [
E/BooksSync( 6699):    {
E/BooksSync( 6699):     "domain": "global",
E/BooksSync( 6699):     "reason": "required",
E/BooksSync( 6699):     "message": "Login Required",
E/BooksSync( 6699):     "locationType": "header",
E/BooksSync( 6699):     "location": "Authorization"
E/BooksSync( 6699):    }
E/BooksSync( 6699):   ],
E/BooksSync( 6699):   "code": 401,
E/BooksSync( 6699):   "message": "Login Required"
E/BooksSync( 6699):  }
E/BooksSync( 6699): }
E/BooksSync( 6699): 
E/BooksSync( 6699): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 6699): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 6699): 	... 8 more
E/BooksSync( 6699): Sync error
E/BooksSync( 6699): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 6699): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-2283780106463412008&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 6699): Headers:
E/BooksSync( 6699): accept-encoding: [gzip]
E/BooksSync( 6699): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 6699): gdata-version: 2
E/BooksSync( 6699): 
E/BooksSync( 6699): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 6699): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 6699): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 6699): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 6699): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 6699): 	at com.google.android.apps.books.data.NetworkTas,kQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 6699): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 6699): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 6699): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 6699): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 6699): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 6699): {
E/BooksSync( 6699):  "error": {
E/BooksSync( 6699):   "errors": [
E/BooksSync( 6699):    {
E/BooksSync( 6699):     "domain": "global",
E/BooksSync( 6699):     "reason": "required",
E/BooksSync( 6699):     "message": "Login Required",
E/BooksSync( 6699):     "locationType": "header",
E/BooksSync( 6699):     "location": "Authorization"
E/BooksSync( 6699):    }
E/BooksSync( 6699):   ],
E/BooksSync( 6699):   "code": 401,
E/BooksSync( 6699):   "message": "Login Required"
E/BooksSync( 6699):  }
E/BooksSync( 6699): }
E/BooksSync( 6699): 
E/BooksSync( 6699): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 6699): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 6699): 	... 8 more
I/BooksSync( 6699): Finished books sync
,I/GLSUser ( 2112): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/userlocation.reporting
I/GLSUser ( 2112): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/userlocation.reporting without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2112): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2112): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2112): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/SyncManager( 1031): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 26269, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
I/ActivityManager( 1031): Killing 6678:com.lge.appbox.client/u0a11 (adj 15): empty #17
,W/libprocessgroup( 1031): failed to open /acct/uid_10011/pid_6678/cgroup.procs: No such file or directory
,E/GCoreUlr( 1812): 
E/GCoreUlr( 1812): com.google.android.gms.auth.ad: BadAuthentication
E/GCoreUlr( 1812): 	at com.google.android.gms.auth.p.b(SourceFile:442)
E/GCoreUlr( 1812): 	at com.google.android.gms.auth.p.a(SourceFile:365)
E/GCoreUlr( 1812): 	at com.google.android.gms.auth.p.a(SourceFile:310)
E/GCoreUlr( 1812): 	at com.google.android.gms.common.server.a.a.b(SourceFile:97)
E/GCoreUlr( 1812): 	at com.google.android.gms.common.server.c.b(SourceFile:109)
E/GCoreUlr( 1812): 	at com.google.android.gms.common.server.o.b(SourceFile:30)
E/GCoreUlr( 1812): 	at com.google.android.gms.common.server.o.b(SourceFile:370)
E/GCoreUlr( 1812): 	at com.google.android.gms.common.server.o.a(SourceFile:340)
E/GCoreUlr( 1812): 	at com.google.android.gms.common.server.o.a(SourceFile:319)
E/GCoreUlr( 1812): 	at com.google.android.location.reporting.c.c.a(SourceFile:166)
E/GCoreUlr( 1812): 	at com.google.android.location.reporting.c.g.a(SourceFile:111)
E/GCoreUlr( 1812): 	at com.google.android.location.reporting.service.t.b(SourceFile:220)
E/GCoreUlr( 1812): 	at com.google.android.location.reporting.service.t.a(SourceFile:173)
E/GCoreUlr( 1812): 	at com.google.android.location.reporting.service.s.onPerformSync(SourceFile:149)
E/GCoreUlr( 1812): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
,I/GLSUser ( 2112): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.talk, service: oauth2:https://www.googleapis.com/auth/chat https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/hangouts https://www.googleapis.com/auth/identity.plus.page.impersonation https://www.googleapis.com/auth/chat.native
I/GLSUser ( 2112): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/chat https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/hangouts https://www.googleapis.com/auth/identity.plus.page.impersonation https://www.googleapis.com/auth/chat.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2112): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2112): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2112): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/SyncManager( 1031): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.location.reporting, PERIODIC, currentRunTime 39551, reason: Periodic, SyncResult: stats [ numAuthExceptions: 1]
D/SyncManager( 1031): not retrying sync operation because the error is a hard error: thalitester@gmail.com u0 (com.google), com.google.android.location.reporting, PERIODIC, currentRunTime 207773, reason: Periodic
,I/ActivityManager( 1031): Start proc com.google.android.gm for service com.google.android.gm/.provider.MailSyncAdapterService: pid=7150 uid=10064 gids={50064, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,E/Babel   ( 7098): UserRecoverableAuthException.
E/Babel   ( 7098): cfq: BadAuthentication
E/Babel   ( 7098): 	at cfn.a(Unknown Source)
E/Babel   ( 7098): 	at f.a(PG:191)
E/Babel   ( 7098): 	at ava.a(PG:88)
E/Babel   ( 7098): 	at ava.a(PG:128)
E/Babel   ( 7098): 	at bjs.a(PG:255)
E/Babel   ( 7098): 	at bep.a(PG:602)
E/Babel   ( 7098): 	at bep.a(PG:469)
E/Babel   ( 7098): 	at bpo.run(PG:1141)
E/Babel   ( 7098): Error getting auth token
E/Babel   ( 7098): bxl
E/Babel   ( 7098): 	at f.a(PG:201)
E/Babel   ( 7098): 	at ava.a(PG:88)
E/Babel   ( 7098): 	at ava.a(PG:128)
E/Babel   ( 7098): 	at bjs.a(PG:255)
E/Babel   ( 7098): 	at bep.a(PG:602)
E/Babel   ( 7098): 	at bep.a(PG:469)
E/Babel   ( 7098): 	at bpo.run(PG:1141)
I/Babel_RequestWriter( 7098): error sending REQ[fc:12; creat:1449862485581; type:bev-1021129357]; took 235 ms (error code == 100)
E/Babel   ( 7098): Account registration failedRedacted-21
E/Babel   ( 7098): bph: null -- null
E/Babel   ( 7098): 	at ava.a(PG:120)
E/Babel   ( 7098): 	at ava.a(PG:128)
E/Babel   ( 7098): 	at bjs.a(PG:255)
E/Babel   ( 7098): 	at bep.a(PG:602)
E/Babel   ( 7098): 	at bep.a(PG:469)
E/Babel   ( 7098): 	at bpo.run(PG:1141)
I/Babel   ( 7098): Account setup failed with error state:106 account:Redacted-21
I/Babel   ( 7098): Account sign in complete with state 106account: Redacted-21
I/art     ( 7098): Note: end time exceeds epoch: 
,I/GLSUser ( 2112): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.talk, service: oauth2:https://www.googleapis.com/auth/chat https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/hangouts https://www.googleapis.com/auth/identity.plus.page.impersonation https://www.googleapis.com/auth/chat.native
I/GLSUser ( 2112): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/chat https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/hangouts https://www.googleapis.com/auth/identity.plus.page.impersonation https://www.googleapis.com/auth/chat.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2112): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2112): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2112): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ResourcesManager( 2112): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,V/NotificationService( 1031): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1031): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1031): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1031): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1031): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
E/Babel   ( 7098): Unexpected exception while authenticating.
D/LgeQuickCoverNLService( 1396): onNotificationPosted
E/Babel   ( 7098): cfr: User intervention required. Notification has been pushed.
E/Babel   ( 7098): 	at cfn.b(Unknown Source)
E/Babel   ( 7098): 	at cfn.a(Unknown Source)
E/Babel   ( 7098): 	at f.a(PG:188)
E/Babel   ( 7098): 	at ava.b(PG:143)
E/Babel   ( 7098): 	at bnr.run(PG:5415)
E/Babel   ( 7098): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/Babel   ( 7098): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/Babel   ( 7098): 	at java.lang.Thread.run(Thread.java:818)
D/SmartCoverUpdateMonitor( 1396): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1396): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1396): handleNotificationPosted(true)
D/QuickCircle( 1396): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1396): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1396): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1396): post do just update job
D/LgeQuickCoverNotificationData( 1396): showAll3
D/LgeQuickCoverNotificationData( 1396): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1396): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1396): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1396): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1396): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1396): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1396): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1396): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1396): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1396): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1396): updateNotificationData: count=3
,D/QuickStatusbarLayout( 1396): Notification difference=198
D/QuickStatusbarLayout( 1396): child = android.widget.LinearLayout{b7d9e1f V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
W/ActivityManager( 1031): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,D/ActivityThread( 7150): Loading provider com.google.android.gmail.provider;com.android.mail.notifier;com.google.android.gm.email.provider;com.google.android.gm.email.notifier: com.android.email.provider.EmailProvider
W/ActivityManager( 1031): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
W/ActivityManager( 1031): Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
,W/ActivityManager( 1031): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
W/ActivityManager( 1031): Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
W/ActivityManager( 1031): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,I/Gmail   ( 7150): Observing account changes for notifications
I/Gmail   ( 7150): getAccountsCursor
V/GLSActivity( 2112): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GAV2    ( 7150): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,W/ActivityManager( 1031): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,W/Gmail   ( 7150): Sync started for account: account:61035162
E/Gmail   ( 7150): Error finding the version of the Email provider.....
E/Gmail   ( 7150): android.content.pm.PackageManager$NameNotFoundException: com.google.android.email
E/Gmail   ( 7150): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
E/Gmail   ( 7150): 	at com.google.android.gm.EmailMigrationService.aU(SourceFile:1235)
E/Gmail   ( 7150): 	at com.google.android.gm.EmailMigrationService.onHandleIntent(SourceFile:187)
E/Gmail   ( 7150): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/Gmail   ( 7150): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/Gmail   ( 7150): 	at android.os.Looper.loop(Looper.java:135)
E/Gmail   ( 7150): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,W/EmailMigration( 7150): We do not support migrating this version of the Email provider.
I/Gmail   ( 7150): getAccountsCursor
,V/GLSActivity( 2112): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
E/SQLiteLog( 7150): (283) recovered 768 frames from WAL file /data/data/com.google.android.gm/databases/mailstore.thalitester@gmail.com.db-wal
I/art     ( 2112): Explicit concurrent mark sweep GC freed 32380(1859KB) AllocSpace objects, 16(2MB) LOS objects, 50% free, 30MB/62MB, paused 962us total 35.968ms
,I/GLSUser ( 2112): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/reminders
I/GLSUser ( 2112): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/reminders without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2112): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2112): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2112): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
E/ReminderSync( 2350): AuthError [T SyncAdapterThread-1:id=275:priority=5:group=main]
,D/SyncManager( 1031): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.gms.reminders, PERIODIC, currentRunTime 39654, reason: Periodic, SyncResult: stats [ numAuthExceptions: 1]
D/SyncManager( 1031): not retrying sync operation because the error is a hard error: thalitester@gmail.com u0 (com.google), com.google.android.gms.reminders, PERIODIC, currentRunTime 206171, reason: Periodic
I/Gmail   ( 7150): getAccountsCursor
I/Gmail   ( 7150): notifyAccountChanged
I/Gmail   ( 7150): notifyAccountChanged
,V/GLSActivity( 2112): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/Gmail   ( 7150): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
I/Gmail   ( 7150): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
I/Gmail   ( 7150): calculateUnknownSyncRationalesAndPurgeInBackground: running
,I/Gmail   ( 7150): calculateUnknownSyncRationalesAndPurgeInBackground: running
,I/ActivityManager( 1031): Start proc com.google.android.apps.docs for service com.google.android.apps.docs/.sync.syncadapter.DocsSyncAdapterService: pid=7195 uid=10061 gids={50061, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/Gmail   ( 7150): getAccountsCursor
I/Gmail   ( 7150): MainSyncRequestProto: lowestBkwdConvoId: 0, highestHandledServerOp: 5310, normalSync: true
,V/GLSActivity( 2112): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/DocsApplication( 7195): Installing DEX configuration.
,D/DexInstaller( 7195): Dex configuration file eager_dex_configuration.xml not found. Skipping dex installation.
I/PackageInfoHelper( 7195): Provided clientMode=RELEASE, packageInfo=PackageInfo{583ed75 com.google.android.apps.docs}
D/TAG     ( 7195): onCreate()
,W/ResourcesManager( 7150): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 7150): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
D/CrossAppStateProvider( 7195): Initialized StateProvider with authority: com.google.android.apps.docs.statesyncer
V/JNIHelp ( 7150): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,W/System  ( 7150): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[directory "."],nativeLibraryDirectories=[/vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 7150): Installed default security provider GmsCore_OpenSSL
,V/GLSActivity( 2112): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/GLSUser ( 2112): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gm, service: mail
,I/GLSUser ( 2112): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> mail without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2112): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2112): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2112): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/GAV2    ( 6699): Thread[GAThread,5,main]: No campaign data found.
V/NotificationService( 1031): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1031): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1031): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1031): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1031): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
W/GLSActivity( 2112): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2112): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2112): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2112): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2112): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2112): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2112): 	at android.os.Binder.execTransact(Binder.java:446)
V/GLSActivity( 2112): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     ( 1031): Explicit concurrent mark sweep GC freed 24537(1109KB) AllocSpace objects, 5(336KB) LOS objects, 33% free, 44MB/66MB, paused 1.555ms total 67.059ms
,D/LgeQuickCoverNLService( 1396): onNotificationPosted
D/SmartCoverUpdateMonitor( 1396): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1396): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1396): handleNotificationPosted(true)
D/QuickCircle( 1396): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1396): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1396): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1396): post do just update job
D/LgeQuickCoverNotificationData( 1396): showAll3
D/LgeQuickCoverNotificationData( 1396): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1396): showAll() ID : 1,0|com.google.android.gms|1|null|10005
,D/LgeQuickCoverNotificationData( 1396): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1396): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1396): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1396): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1396): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1396): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1396): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1396): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1396): updateNotificationData: count=3
D/QuickStatusbarLayout( 1396): Notification difference=198
D/QuickStatusbarLayout( 1396): child = android.widget.LinearLayout{b7d9e1f V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
I/GLSUser ( 2112): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gm, service: mail
I/GLSUser ( 2112): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> mail without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2112): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2112): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2112): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/NotificationService( 1031): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
V/NotificationService( 1031): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1031): LED remove() : mLights=0|com.google.android.gms|1|null|10005
,D/NotificationServiceEx( 1031): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1031): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
W/GLSActivity( 2112): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2112): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2112): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2112): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2112): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2112): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2112): 	at android.os.Binder.execTransact(Binder.java:446)
D/LgeQuickCoverNLService( 1396): onNotificationPosted
D/SmartCoverUpdateMonitor( 1396): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1396): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1396): handleNotificationPosted(true)
D/QuickCircle( 1396): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1396): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1396): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1396): post do just update job
D/LgeQuickCoverNotificationData( 1396): showAll3
D/LgeQuickCoverNotificationData( 1396): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1396): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1396): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1396): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1396): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1396): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1396): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1396): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1396): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1396): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1396): updateNotificationData: count=3
I/Gmail   ( 7150): notifyAccountChanged
I/Gmail   ( 7150): getAccountsCursor
,V/GLSActivity( 2112): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/QuickStatusbarLayout( 1396): Notification difference=198
D/QuickStatusbarLayout( 1396): child = android.widget.LinearLayout{b7d9e1f V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
I/Gmail   ( 7150): notifyAccountChanged
,I/Gmail   ( 7150): getAccountsCursor
W/Gmail   ( 7150): Sync complete for account: account:61035162
V/GLSActivity( 2112): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/SyncManager( 1031): failed sync operation thalitester@gmail.com u0 (com.google), gmail-ls, PERIODIC, currentRunTime 39605, reason: Periodic, SyncResult: stats [ numAuthExceptions: 1]
,D/SyncManager( 1031): not retrying sync operation because the error is a hard error: thalitester@gmail.com u0 (com.google), gmail-ls, PERIODIC, currentRunTime 208051, reason: Periodic
I/SyncAdapterService( 6876): Ignoring sync request for non-current account
,I/ActivityManager( 1031): Killing 6376:com.lge.formmanager/u0a26 (adj 15): empty #17
,W/libprocessgroup( 1031): failed to open /acct/uid_10026/pid_6376/cgroup.procs: No such file or directory
,W/BaseAppContext( 2350): Using Auth Proxy for data requests.
,W/BaseAppContext( 2350): Using Auth Proxy for data requests.
W/BaseAppContext( 2350): Using Auth Proxy for data requests.
,W/BaseAppContext( 2350): Using Auth Proxy for data requests.
W/BaseAppContext( 2350): Using Auth Proxy for data requests.
,W/BaseAppContext( 2350): Using Auth Proxy for data requests.
,W/BaseAppContext( 2350): Using Auth Proxy for data requests.
,D/ChimeraCfgMgr( 2350): Loading module com.google.android.gms.games from APK com.google.android.gms
,I/GoogleHttpClient( 5255): Falling back to old http client 0 java.lang.NoSuchMethodException: <init> [class android.content.Context, class java.lang.String, boolean, boolean]
,V/GLSActivity( 2112): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2112): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.music, service: sj
I/GLSUser ( 2112): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> sj without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2112): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2112): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2112): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     ( 2112): Explicit concurrent mark sweep GC freed 13188(730KB) AllocSpace objects, 5(720KB) LOS objects, 50% free, 30MB/62MB, paused 1.868ms total 48.621ms
,D/LgDataFeature( 7195): LgDataFeature() Constructor: none
,D/LgDataFeature( 7195): LgDataFeature() Constructor Done, null
I/GAV4    ( 6876): Thread[GAThread,5,main]: No campaign data found.
V/NotificationService( 1031): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
V/NotificationService( 1031): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1031): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1031): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1031): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1396): onNotificationPosted
,D/SmartCoverUpdateMonitor( 1396): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1396): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1396): handleNotificationPosted(true)
D/QuickCircle( 1396): onNotificationPosted() : isPosted true
,D/LgeQuickCoverNotificationData( 1396): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1396): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1396): post do just update job
D/LgeQuickCoverNotificationData( 1396): showAll3
D/LgeQuickCoverNotificationData( 1396): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1396): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1396): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1396): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1396): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1396): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1396): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1396): isNotificationForCurrentUser : true
W/GLSActivity( 2112): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2112): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2112): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2112): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2112): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2112): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2112): 	at android.os.Binder.execTransact(Binder.java:446)
D/LgeQuickCoverOverlayWindow( 1396): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1396): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1396): updateNotificationData: count=3
W/MusicSyncAdapter( 5255): Sync failed due to an authentication issue.
,D/SyncManager( 1031): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.music.MusicContent, PERIODIC, currentRunTime 39680, reason: Periodic, SyncResult: stats [ numAuthExceptions: 1]
D/QuickStatusbarLayout( 1396): Notification difference=198
D/QuickStatusbarLayout( 1396): child = android.widget.LinearLayout{b7d9e1f V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,D/SyncManager( 1031): not retrying sync operation because the error is a hard error: thalitester@gmail.com u0 (com.google), com.google.android.music.MusicContent, PERIODIC, currentRunTime 209909, reason: Periodic
E/VoldCmdListener(  278): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  278): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 5255): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
E/VoldCmdListener(  278): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  278): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 5255): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
E/VoldCmdListener(  278): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  278): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 5255): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
E/VoldCmdListener(  278): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  278): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 5255): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=34.3, 0.0, 0.0  rx=26.9 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:-1598539895] gl rssi=-45 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=34.3, 0.0, 0.0  rx=26.9 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-1598539894] gl rssi=-45 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,W/ArtDownloadService( 5255): Setting cache size 0
I/ActivityManager( 1031): Start proc com.google.android.videos for service com.google.android.videos/.store.SyncService: pid=7244 uid=10103 gids={50103, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
W/ArtDownloadService( 5255): Setting cache size 0
,I/MusicLeanback( 5255): Conditions not met for autocaching.
I/MusicLeanback( 5255): Stop autocaching.
,D/sensors_hal_Time( 1031): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1031): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1031): tsOffsetIs: Apps: 177527676290; DSPS: 5957988; Offset : -4307687471
,I/ActivityManager( 1031): Start proc com.google.android.gms.wearable for service com.google.android.gms/.wearable.service.WearableService: pid=7264 uid=10005 gids={50005, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
,W/GAV2    ( 7195): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
I/art     (  344): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 217us total 10.111ms
I/art     (  344): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 186us total 9.098ms
,I/art     (  344): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 183us total 8.670ms
,E/VoldCmdListener(  278): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  278): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/cache/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 5255): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/cache
D/WifiService( 1031): acquireWifiLockLocked: WifiLock{SyncManager type=1 binder=android.os.BinderProxy@10d6c93c}
W/ResourcesManager( 7264): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 7264): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
W/ResourcesManager( 7244): Asset path '/system/framework/com.google.widevine.software.drm.jar' does not exist or contains no resources.
,E/VoldCmdListener(  278): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  278): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/cache/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 5255): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/cache
I/MultiDex( 7264): VM with version 2.1.0 has multidex support
I/MultiDex( 7264): install
I/MultiDex( 7264): VM has multidex support, MultiDex support library is disabled.
,V/JNIHelp ( 7264): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,W/ActivityThread( 7264): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 7264): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@3e67c540: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 7264): Installed default security provider GmsCore_OpenSSL
,D/GCM     ( 2112): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
D/AuthorizationBluetoothService( 2112): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
V/GmsCoreStatsServiceLauncher( 2350): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
D/WearableService( 7264): callingUid 10005, callindPid: 7264
,D/LocationInitializer( 2350): Restart initialization of location
,D/WearableClient( 5255): WearableClientImpl.onPostInitHandler: done
,E/MDM     ( 1812): [87] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
D/WearableClient( 5255): WearableClientImpl.onPostInitHandler: done
E/GmsUtils( 5255): Failed to connect to Google API client: ConnectionResult{statusCode=unknown status code 16, resolution=null}
,D/libc-netbsd(  313): default dns: query_ipv6=0, query_ipv4=1
,D/libc-netbsd(  313): res_queryN name = ssl.gstatic.com, class = 1, type = 1
,D/libc-netbsd(  313): res_queryN name = ssl.gstatic.com succeed
,D/LgDataFeature( 7244): LgDataFeature() Constructor: none
D/LgDataFeature( 7244): LgDataFeature() Constructor Done, null
,D/PlayMovies( 7244): PersistentCache.cleanup:103 Cache is below limit, no need to shrink: [size=0, limit=5242880]
,D/PlayMovies( 7244): TransferService.onCreate:52 creating transfer service
,W/AudioCapabilities( 7244): Unsupported mime audio/evrc
W/AudioCapabilities( 7244): Unsupported mime audio/qcelp
W/VideoCapabilities( 7244): Unrecognized profile 2130706433 for video/avc
I/art     ( 2350): Explicit concurrent mark sweep GC freed 11910(773KB) AllocSpace objects, 7(112KB) LOS objects, 49% free, 32MB/64MB, paused 1.310ms total 45.988ms
,E/VoldCmdListener(  278): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  278): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.videos/files/Movies/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7244): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.videos/files/Movies
W/AudioCapabilities( 7244): Unsupported mime audio/amr-wb-plus
,W/AudioCapabilities( 7244): Unsupported mime audio/qcelp
I/ActivityManager( 1031): Killing 6834:com.lge.drmservice/u0a62 (adj 15): empty #17
W/AudioCapabilities( 7244): Unsupported mime audio/evrc
W/VideoCapabilities( 7244): Unsupported mime video/x-ms-wmv
,W/VideoCapabilities( 7244): Unsupported mime video/divx
W/VideoCapabilities( 7244): Unsupported mime video/divx311
,W/VideoCapabilities( 7244): Unsupported mime video/divx4
W/VideoCapabilities( 7244): Unsupported mime video/mp4v-esdp
I/VideoCapabilities( 7244): Unsupported profile 4 for video/mp4v-es
,W/AudioCapabilities( 7244): Unsupported mime audio/eac3
W/AudioCapabilities( 7244): Unsupported mime audio/ac3
W/AudioCapabilities( 7244): Unsupported mime audio/g726
W/AudioCapabilities( 7244): Unsupported mime audio/wma-voice
W/AudioCapabilities( 7244): Unsupported mime audio/x-ms-wma
W/AudioCapabilities( 7244): Unsupported mime audio/adpcm
W/VideoCapabilities( 7244): Unsupported mime video/theora
,W/libprocessgroup( 1031): failed to open /acct/uid_10062/pid_6834/cgroup.procs: No such file or directory
W/VideoCapabilities( 7244): Unsupported mime video/mjpg
V/GLSActivity( 2112): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2112): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.videos, service: oauth2:https://www.googleapis.com/auth/android_video https://www.googleapis.com/auth/youtube https://www.googleapis.com/auth/pos
,I/GLSUser ( 2112): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/android_video https://www.googleapis.com/auth/youtube https://www.googleapis.com/auth/pos without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2112): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2112): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
I/GLSUser ( 2112): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.docs, service: oauth2: https://www.googleapis.com/auth/drive
I/GLSUser ( 2112): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2: https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2112): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2112): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2112): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/GLSActivity( 2112): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/ResourcesManager( 2350): Asset path '/system/framework/com.google.widevine.software.drm.jar' does not exist or contains no resources.
V/NotificationService( 1031): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
V/NotificationService( 1031): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1031): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1031): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1031): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,W/GLSActivity( 2112): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.,
W/GLSActivity( 2112): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2112): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2112): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2112): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2112): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2112): 	at android.os.Binder.execTransact(Binder.java:446)
D/LgeQuickCoverNLService( 1396): onNotificationPosted
W/PsynchoHelperImpl( 7195): Error fetching or saving configuration
W/PsynchoHelperImpl( 7195): java.io.IOException: android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
W/PsynchoHelperImpl( 7195): 	at Op.a(ApiaryPsynchoConfigurationAccessor.java:145)
W/PsynchoHelperImpl( 7195): 	at Op.a(ApiaryPsynchoConfigurationAccessor.java:215)
W/PsynchoHelperImpl( 7195): 	at OQ.a(PsynchoHelperImpl.java:60)
W/PsynchoHelperImpl( 7195): 	at agr.a(DriveSpecificSyncManager.java:27)
W/PsynchoHelperImpl( 7195): 	at agO.a(LegacySyncManager.java:678)
W/PsynchoHelperImpl( 7195): 	at agO.b(LegacySyncManager.java:582)
W/PsynchoHelperImpl( 7195): 	at agO.a(LegacySyncManager.java:467)
W/PsynchoHelperImpl( 7195): 	at agO.a(LegacySyncManager.java:97)
W/PsynchoHelperImpl( 7195): 	at agQ.run(LegacySyncManager.java:419)
W/PsynchoHelperImpl( 7195): 	at ami.a(NetworkUtilitiesImpl.java:31)
W/PsynchoHelperImpl( 7195): 	at agP.run(LegacySyncManager.java:416)
W/PsynchoHelperImpl( 7195): Caused by: android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
W/PsynchoHelperImpl( 7195): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
W/PsynchoHelperImpl( 7195): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
W/PsynchoHelperImpl( 7195): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
W/PsynchoHelperImpl( 7195): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
W/PsynchoHelperImpl( 7195): 	at android.os.Binder.execTransact(Binder.java:446)
D/SmartCoverUpdateMonitor( 1396): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1396): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1396): handleNotificationPosted(true)
D/QuickCircle( 1396): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1396): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1396): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1396): post do just update job
D/LgeQuickCoverNotificationData( 1396): showAll3
D/LgeQuickCoverNotificationData( 1396): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
,D/LgeQuickCoverNotificationData( 1396): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1396): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1396): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1396): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1396): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1396): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1396): isNotificationForCurrentUser : true
,D/LgeQuickCoverOverlayWindow( 1396): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1396): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1396): updateNotificationData: count=3
V/GLSActivity( 2112): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/QuickStatusbarLayout( 1396): Notification difference=198
D/QuickStatusbarLayout( 1396): child = android.widget.LinearLayout{b7d9e1f V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
I/GLSUser ( 2112): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.docs, service: writely
I/GLSUser ( 2112): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> writely without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2112): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2112): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2112): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1031): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
V/NotificationService( 1031): pkg=com.google.android.gms canInterrupt=false intercept=true
I/art     ( 1031): Explicit concurrent mark sweep GC freed 26246(1213KB) AllocSpace objects, 7(496KB) LOS objects, 33% free, 44MB/66MB, paused 1.512ms total 82.261ms
I/NotificationServiceEx( 1031): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1031): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1031): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,E/PlayMovies( 7244): GmsAccountManagerWrapper.blockingGetAuthTokenInternal:100 Cannot get user auth
E/PlayMovies( 7244): com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/PlayMovies( 7244): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/PlayMovies( 7244): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/PlayMovies( 7244): 	at com.google.android.videos.accounts.GmsAccountManagerWrapper.blockingGetAuthTokenInternal(GmsAccountManagerWrapper.java:85)
E/PlayMovies( 7244): 	at com.google.android.videos.accounts.AccountManagerWrapper.blockingGetAuthToken(AccountManagerWrapper.java:186)
E/PlayMovies( 7244): 	at com.google.android.videos.accounts.AccountManagerWrapper.blockingAuthenticate(AccountManagerWrapper.java:162)
E/PlayMovies( 7244): 	at com.google.android.videos.store.SyncService$SyncAdapter.onPerformSync(SyncService.java:225)
E/PlayMovies( 7244): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
D/LgeQuickCoverNLService( 1396): onNotificationPosted
,D/SmartCoverUpdateMonitor( 1396): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1396): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1396): handleNotificationPosted(true)
D/QuickCircle( 1396): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1396): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1396): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1396): post do just update job
D/LgeQuickCoverNotificationData( 1396): showAll3
D/LgeQuickCoverNotificationData( 1396): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1396): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1396): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1396): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1396): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1396): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1396): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1396): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1396): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1396): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1396): updateNotificationData: count=3
V/NotificationService( 1031): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
V/NotificationService( 1031): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1031): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1031): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1031): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
W/GLSActivity( 2112): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2112): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2112): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2112): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2112): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2112): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2112): 	at android.os.Binder.execTransact(Binder.java:446)
D/LgeQuickCoverNLService( 1396): onNotificationPosted
E/HttpIssuerBase( 7195): Attempt to consume entity of HttpIssuer when no request is executing.
,E/HttpIssuerBase( 7195): Attempt to close HttpIssuer when no request is executing.
E/HttpIssuerBase( 7195): java.io.IOException
E/HttpIssuerBase( 7195): 	at TG.b(HttpIssuerBase.java:188)
E/HttpIssuerBase( 7195): 	at Tj.b(DefaultAuthenticatedHttpIssuer.java:151)
E/HttpIssuerBase( 7195): 	at afE.a(AccountMetadataUpdater.java:227)
E/HttpIssuerBase( 7195): 	at afE.a(AccountMetadataUpdater.java:140)
E/HttpIssuerBase( 7195): 	at agO.a(LegacySyncManager.java:828)
E/HttpIssuerBase( 7195): 	at agO.b(LegacySyncManager.java:588)
E/HttpIssuerBase( 7195): 	at agO.a(LegacySyncManager.java:467)
E/HttpIssuerBase( 7195): 	at agO.a(LegacySyncManager.java:97)
E/HttpIssuerBase( 7195): 	at agQ.run(LegacySyncManager.java:419)
E/HttpIssuerBase( 7195): 	at ami.a(NetworkUtilitiesImpl.java:31)
E/HttpIssuerBase( 7195): 	at agP.run(LegacySyncManager.java:416)
E/SyncManager( 7195): AuthenticatorException
E/SyncManager( 7195): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/SyncManager( 7195): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/SyncManager( 7195): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/SyncManager( 7195): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/SyncManager( 7195): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/SyncManager( 7195): 	at android.os.Binder.execTransact(Binder.java:446)
I/ActivityManager( 1031): Killing 6760:com.android.chrome/u0a57 (adj 15): empty #17
D/SyncManager( 1031): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.videos.sync, PERIODIC, currentRunTime 39682, reason: Periodic, SyncResult: stats [ numAuthExceptions: 1]
D/QuickStatusbarLayout( 1396): Notification difference=198
D/QuickStatusbarLayout( 1396): child = android.widget.LinearLayout{b7d9e1f V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
D/SmartCoverUpdateMonitor( 1396): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1396): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1396): handleNotificationPosted(true)
D/QuickCircle( 1396): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1396): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1396): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1396): post do just update job
D/LgeQuickCoverNotificationData( 1396): showAll3
D/LgeQuickCoverNotificationData( 1396): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1396): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1396): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1396): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1396): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1396): isNotificationForCurrentUser : true
D/SyncManager( 1031): not retrying sync operation because the error is a hard error: thalitester@gmail.com u0 (com.google), com.google.android.videos.sync, PERIODIC, currentRunTime 209246, reason: Periodic
D/LgeQuickCoverOverlayWindow( 1396): [native noti] inex =  1
W/GAV2    ( 7195): SyncManager-thalitester@gmail.com: dispatch call queued.  Need to call GAServiceManager.getInstance().initialize().
D/WifiService( 1031): releaseWifiLockLocked: WifiLock{SyncManager type=1 binder=android.os.BinderProxy@10d6c93c}
W/libprocessgroup( 1031): failed to open /acct/uid_10057/pid_6760/cgroup.procs: No such file or directory
D/LgeQuickCoverNotificationData( 1396): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1396): [native noti] inex =  2
,D/LgeQuickCoverNotificationData( 1396): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1396): updateNotificationData: count=3
D/QuickStatusbarLayout( 1396): Notification difference=198
D/QuickStatusbarLayout( 1396): child = android.widget.LinearLayout{b7d9e1f V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
D/SyncManager( 1031): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.docs, PERIODIC, currentRunTime 39661, reason: Periodic, SyncResult: stats [ numAuthExceptions: 1]
I/ActivityManager( 1031): Killing 6716:com.android.gallery3d/u0a27 (adj 15): empty #17
D/SyncManager( 1031): not retrying sync operation because the error is a hard error: thalitester@gmail.com u0 (com.google), com.google.android.apps.docs, PERIODIC, currentRunTime 211545, reason: Periodic
,W/libprocessgroup( 1031): failed to open /acct/uid_10027/pid_6716/cgroup.procs: No such file or directory
,E/Auth.Api.Credentials( 2350): [CredentialSyncAdapter] Unknown sync event.
,V/GLSActivity( 2112): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2112): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.syncadapters.contacts, service: cp
I/GLSUser ( 2112): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> cp without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2112): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2112): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2112): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1031): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1031): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1031): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1031): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1031): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
W/GLSActivity( 2112): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2112): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2112): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2112): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2112): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2112): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2112): 	at android.os.Binder.execTransact(Binder.java:446)
D/ContactsSyncAdapter( 2112): innerSync failed
D/ContactsSyncAdapter( 2112): com.google.wireless.gdata2.client.AuthenticationException: unable to get auth token android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
D/ContactsSyncAdapter( 2112): 	at com.google.android.syncadapters.contacts.AuthInfo.getAuthToken(AuthInfo.java:45)
D/ContactsSyncAdapter( 2112): 	at com.google.android.syncadapters.contacts.ContactsSyncAdapter.innerPerformSync(ContactsSyncAdapter.java:263)
D/ContactsSyncAdapter( 2112): 	at com.google.android.syncadapters.contacts.ContactsSyncAdapter.onPerformLoggedSync(ContactsSyncAdapter.java:168)
D/ContactsSyncAdapter( 2112): 	at com.google.android.common.LoggingThreadedSyncAdapter.onPerformSync(LoggingThreadedSyncAdapter.java:33)
D/ContactsSyncAdapter( 2112): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
D/ContactsSyncAdapter( 2112): Caused by: android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
D/ContactsSyncAdapter( 2112): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
D/ContactsSyncAdapter( 2112): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
D/ContactsSyncAdapter( 2112): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
D/ContactsSyncAdapter( 2112): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
D/ContactsSyncAdapter( 2112): 	at android.os.Binder.execTransact(Binder.java:446)
D/LgeQuickCoverNLService( 1396): onNotificationPosted
D/SmartCoverUpdateMonitor( 1396): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1396): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1396): handleNotificationPosted(true)
D/QuickCircle( 1396): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1396): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1396): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1396): post do just update job
D/LgeQuickCoverNotificationData( 1396): showAll3
D/LgeQuickCoverNotificationData( 1396): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1396): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1396): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1396): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1396): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1396): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1396): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1396): isNotificationForCurrentUser : true
,D/LgeQuickCoverOverlayWindow( 1396): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1396): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1396): updateNotificationData: count=3
D/SyncManager( 1031): failed sync operation thalitester@gmail.com u0 (com.google), com.android.contacts, LOCAL, currentRunTime 204528, reason: 10019, SyncResult: stats [ numAuthExceptions: 1]
,D/QuickStatusbarLayout( 1396): Notification difference=198
D/QuickStatusbarLayout( 1396): child = android.widget.LinearLayout{b7d9e1f V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
I/ThermalEngine(  329): Thermal-Server: Thermal received msg from  override
,I/Thermal-Lib( 3117): Thermal-Lib-Client: Client request sent
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=20.2, 0.0, 0.0  rx=15.9 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1598536880] gl rssi=-45 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=20.2, 0.0, 0.0  rx=15.9 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1598536877] gl rssi=-45 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,I/ActivityManager( 1031): Killing 6743:com.lge.email/u0a23 (adj 15): empty #17
W/libprocessgroup( 1031): failed to open /acct/uid_10023/pid_6743/cgroup.procs: No such file or directory
,I/GAV2    ( 7150): Thread[GAThread,5,main]: No campaign data found.
,I/GAV2    ( 7195): Thread[GAThread,5,main]: No campaign data found.
,I/ActivityManager( 1031): Killing 5174:com.wsandroid.suite.lge/1000 (adj 15): empty #17
,W/libprocessgroup( 1031): failed to open /acct/uid_1000/pid_5174/cgroup.procs: No such file or directory
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=18.6, 0.0, 0.0  rx=15.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1598533853] gl rssi=-45 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=18.6, 0.0, 0.0  rx=15.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1598533850] gl rssi=-45 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=9.8, 0.0, 0.0  rx=8.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1598530826] gl rssi=-45 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=9.8, 0.0, 0.0  rx=8.0 bcn=0 [on:0 tx:0 rx:0 period:14] from screen [on:0 period:-1598530812] gl rssi=-45 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
I/[SystemUI]QPairHandler( 1447): onReceive = android.intent.action.PACKAGE_CHANGED
,D/SplitUIService( 1867): replaced split : contains_com.google.android.talk / true
,I/InputReader( 1031): Reconfiguring input devices.  changes=0x00000010
,I/ActivityManager( 1031): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.manager.PreloadListManagerHelper: pid=7353 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,I/InputReader( 1031): Reconfiguring input devices.  changes=0x00000010
,I/[SystemUI]QSlideListController( 1447): onReceive = android.intent.action.PACKAGE_CHANGED
I/[SystemUI]AppWidgetPanel(QRemoteWidgetPanel)( 1447): onReceive = android.intent.action.PACKAGE_CHANGED, packageName : com.google.android.talk
I/[SystemUI]QPairHandler( 1447): onReceive = android.intent.action.PACKAGE_CHANGED
I/[LGHome]EVENT( 2067): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.talk flg=0x4000010 (has extras) }
,I/[LGHome]EVENT( 2067): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.videos flg=0x4000010 (has extras) }
,D/administrator( 1031): Handling package changes for user 0
I/[SystemUI]QSlideListController( 1447): onReceive = android.intent.action.PACKAGE_CHANGED
I/[SystemUI]AppWidgetPanel(QRemoteWidgetPanel)( 1447): onReceive = android.intent.action.PACKAGE_CHANGED, packageName : com.google.android.videos
,D/SplitUIManager( 1867): split_name #11 / not available #0
I/SplitUIService( 1867): split app #11
,W/ResourcesManager( 2067): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
I/[LGHome]Launcher( 2067): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,I/AppUp4:AppBoxCP( 7353): onCreate
W/AppUp4:DB( 7353):  [AppBoxDatabaseHelper] construct
,I/NotificationService( 1031): action=android.intent.action.PACKAGE_CHANGED queryReplace=false
D/BackupManagerService( 1031): Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.talk flg=0x4000010 (has extras) }
I/AppUp4:DB( 7353):  setFingerPrint start
I/AppUp4:DB( 7353):  newfinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys SDK version = 21
W/ResourcesManager( 1031): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
D/administrator( 1031): Handling package changes for user 0
I/AppUp4:DB( 7353):  beforefinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys
I/AppUp4:DB( 7353):  SDK version = 21
I/AppUp4:DB( 7353):  beforefinger == newfinger no write in DB
D/AppUp4:AppBoxApplication( 7353): AppBoxApplication onCreate()
I/AppUp4:CustModeStarterReceiver( 7353): onReceive
,I/NotificationService( 1031): action=android.intent.action.PACKAGE_CHANGED queryReplace=false
D/BackupManagerService( 1031): Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.videos flg=0x4000010 (has extras) }
I/[LGHome]Launcher( 2067): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,D/LgDataFeature( 7353): LgDataFeature() Constructor: none
D/LgDataFeature( 7353): LgDataFeature() Constructor Done, null
D/AppUp4:CustFacade( 7353): Context : android.app.ReceiverRestrictedContext@21cdf798
D/AppUp4:CustFacade( 7353): isCustomizationCompleted : false
D/AppUp4:CustFacade( 7353): isPhone : true
D/AppUp4:CustModeStarterReceiver( 7353): begin check event
I/AppUp4:CustModeStarterReceiver( 7353): Event For Nothing, skip.
W/ResourcesManager( 1031): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourceType( 1031): Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
I/ActivityManager( 1031): Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=7389 uid=10019 gids={50019, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
,I/ActivityManager( 1031): Killing 7027:com.qualcomm.timeservice/1000 (adj 15): empty #17
W/libprocessgroup( 1031): failed to open /acct/uid_1000/pid_7027/cgroup.procs: No such file or directory
,I/[LGHome]EVENT( 2067): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
,W/ResourceType( 1031): Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
I/[LGHome]EVENT( 2067): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
W/ResourcesManager( 7389): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 7389): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,W/ResourcesManager( 7389): Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
W/ResourcesManager( 7389): Asset path '/system/framework/lghiddenlibs.jar' does not exist or contains no resources.
W/ResourcesManager( 7389): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
I/SystemConfig( 7389): BUILD Country: EU
I/SystemConfig( 7389): BUILD Operator: OPEN
,I/ActivityManager( 1031): Killing 7066:com.android.providers.calendar/u0a14 (adj 15): empty #17
,W/libprocessgroup( 1031): failed to open /acct/uid_10014/pid_7066/cgroup.procs: No such file or directory
,I/ActivityManager( 1031): Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=7408 uid=10027 gids={50027, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
I/SystemConfig( 7389): pm.hasSystemFeature(com.lge.ims.rcs) = false
I/SystemConfig( 7389): existFile = false
I/SystemConfig( 7389): canReadFile = false
I/SystemConfig( 7389): systemFeature RCS result false
D/SystemConfig( 7389): refreshRcsSupport() :false
,W/ResourcesManager( 7408): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 7408): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 7408): Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
W/ResourcesManager( 7408): Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
I/AppConfig( 7408): Total System Memory = 2995761152
,D/SystemHelper( 7408): region [EU], country [EU], operator [OPEN], sub-operator []
,I/ActivityManager( 1031): Killing 7045:com.android.calendar/u0a13 (adj 15): empty #17
,W/libprocessgroup( 1031): failed to open /acct/uid_10013/pid_7045/cgroup.procs: No such file or directory
,I/UpdateIcingCorporaServi( 4228): Updating corpora: APPS=com.google.android.talk, CONTACTS=MAYBE
,I/ActivityManager( 1031): Start proc com.lge.lockscreensettings for broadcast com.lge.lockscreensettings/.PackageIntentReceiver: pid=7435 uid=10080 gids={50080, 9997, 1028, 1015} abi=armeabi-v7a
,V/SIM_STK ( 1031): Menu title from STK is T-Mobile
W/ResourcesManager( 4228): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/UpdateIcingCorporaServi( 4228): UpdateCorporaTask done [took 90 ms] updated apps [took 90 ms] 
I/LockScreenSettings( 7435): Wallpaper base directory = /data/data/com.lge.lockscreensettings/files/
,D/LockScreenSettings( 7435): Quick window widget present in DB = com.lge.clock.quickcover.QuickCoverSettingActivity  true
D/LockScreenSettings( 7435): Quick window widget present in DB = com.lge.camera.app.QuickWindowCameraActivity  true
D/LockScreenSettings( 7435): Quick window widget present in DB = com.android.contacts.activities.QuickCircleActivity  true
,D/LockScreenSettings( 7435): Quick window widget present in DB = com.android.mms.quickcover.QuickCoverActivity  true
D/LockScreenSettings( 7435): Quick window widget present in DB = com.lge.music.MusicQuickCircle  true
D/LockScreenSettings( 7435): Quick window widget present in DB = com.lge.lifetracker.QuickCover  true
I/ActivityManager( 1031): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=7459 uid=10044 gids={50044, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager( 1031): Killing 5995:com.uei.lg.quicksetsdk.maxq616/1000 (adj 15): empty #17
,I/QRemote ( 6480): [RemoteControlManager.java:195:onServiceDisconnected()] oooooo start
W/System.err( 6480): android.os.DeadObjectException
W/System.err( 6480): 	at android.os.BinderProxy.transactNative(Native Method)
W/System.err( 6480): 	at android.os.BinderProxy.transact(Binder.java:496)
W/System.err( 6480): 	at com.uei.control.IControl.unregisterCallback(IControl.java:502)
W/System.err( 6480): 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:199)
W/System.err( 6480): 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
,W/System.err( 6480): 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
,W/System.err( 6480): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 6480): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 6480): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 6480): 	at android.app.ActivityThread.main(ActivityThread.java:5274)
W/System.err( 6480): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 6480): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 6480): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
W/System.err( 6480): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
E/UEI.SmartControl( 6480): IControl.unregisterCallback error: android.os.DeadObjectException
W/System.err( 6480): android.os.DeadObjectException
W/System.err( 6480): 	at android.os.BinderProxy.transactNative(Native Method)
W/System.err( 6480): 	at android.os.BinderProxy.transact(Binder.java:496)
W/System.err( 6480): 	at com.uei.control.IControl.unregisterSetupReadyCallback(IControl.java:818)
W/System.err( 6480): 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:200)
W/System.err( 6480): 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
W/System.err( 6480): 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
W/System.err( 6480): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 6480): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 6480): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 6480): 	at android.app.ActivityThread.main(ActivityThread.java:5274)
W/System.err( 6480): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 6480): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 6480): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
W/System.err( 6480): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
E/UEI.SmartControl( 6480): IControl.unregisterSetupReadyCallback error: android.os.DeadObjectException
I/QRemote ( 6480): [RemoteControlManager.java:203:onServiceDisconnected()] oooooo Control unbind before rebinding.
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=5.4, 0.0, 0.0  rx=4.5 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1598527800] gl rssi=-45 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=5.4, 0.0, 0.0  rx=4.5 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-1598527799] gl rssi=-45 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
W/libprocessgroup( 1031): failed to open /acct/uid_1000/pid_5995/cgroup.procs: No such file or directory
,W/ActivityManager( 1031): Scheduling restart of crashed service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service in 1000ms
,D/QRemote ( 6480): [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]10
I/QRemote ( 6480): [RemoteControlManager.java:157:onBindIRService()] oooooo bind
I/ActivityManager( 1031): Start proc com.uei.lg.quicksetsdk.maxq616 for service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service: pid=7476 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
D/QRemote ( 6480): [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
,D/UEI.SmartControl( 7476): Quickset Services start...
I/UEI.SmartControl( 7476): Manufacture = LGE
D/UEI.SmartControl( 7476): Id = LGNevo
,D/UEI.SmartControl( 7476): File observer start...
E/UEI.SmartControl( 7476): IR Port is disabled: false
,D/UEI.SmartControl( 7476): Starting file observer...
D/UEI.SmartControl( 7476): Extracting JNI libs...
D/UEI.SmartControl( 7476): --- this system supports 32-bit or 64-bit only
D/Finsky  ( 7459): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,D/LgDataFeature( 7459): LgDataFeature() Constructor: none
,D/LgDataFeature( 7459): LgDataFeature() Constructor Done, null
D/UEI.SmartControl( 7476): --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
D/UEI.SmartControl( 7476): --- Checking lib: libqs_armeabi-v7a.zip
D/UEI.SmartControl( 7476): --- Extracting JNI libs: libqs_armeabi-v7a.zip
,I/UEI.SmartControl( 7476): --- Selecting new region: 6
,I/UEI.SmartControl( 7476): Model = LG-D855
D/UEI.SmartControl( 7476): QS Service created
I/UEI.SmartControl( 7476): Service initServices...
,D/UEI.SmartControl( 7476): QS start get config
,D/UEI.SmartControl( 7476): Loading JNI Libs...
,D/Finsky  ( 7459): [1] DailyHygiene.goMakeHygieneIfDirty: Dirty, need more hygiene.
I/ActivityManager( 1031): Start proc com.google.android.gms:car for service com.google.android.gms/.car.CarService: pid=7517 uid=10005 gids={50005, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
,W/Settings( 7459): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 7459): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
W/ResourcesManager( 7517): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 7517): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/DownloadManager( 3288): starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3288): created cursor android.database.sqlite.SQLiteCursor@30e272c5 on behalf of 7459
I/MultiDex( 7517): VM with version 2.1.0 has multidex support
I/MultiDex( 7517): install
I/MultiDex( 7517): VM has multidex support, MultiDex support library is disabled.
,D/Finsky  ( 7459): [1] 2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 7459): [1] 2.run: Finished loading 1 libraries.
D/Finsky  ( 7459): [1] GmsCoreHelper.cleanupNlp: result=false type=4
V/JNIHelp ( 7517): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,D/PackageBroadcastService( 2350): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.talk
,I/AppUp4:CustModeStarterReceiver( 7353): onReceive
D/AppUp4:CustFacade( 7353): Context : android.app.ReceiverRestrictedContext@21cdf798
D/AppUp4:CustFacade( 7353): isCustomizationCompleted : false
D/AppUp4:CustFacade( 7353): isPhone : true
D/AppUp4:CustModeStarterReceiver( 7353): begin check event
I/AppUp4:CustModeStarterReceiver( 7353): Event For Nothing, skip.
I/PeopleContactsSync( 2350): CP2 sync disabled
D/Finsky  ( 7459): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
I/ActivityManager( 1031): Killing 6480:com.lge.qremote/u0a112 (adj 15): empty #17
,W/ActivityThread( 7517): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 7517): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@3e67c540: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 7517): Installed default security provider GmsCore_OpenSSL
I/UEI.SmartControl( 7476): Supports setup maps: true
,D/UEI.SmartControl( 7476): QS start statue = true Error code = 0
I/UEI.SmartControl( 7476): QS version = v2.7.10.1_RC1
I/UEI.SmartControl( 7476): QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
I/UEI.SmartControl( 7476): ### init IR Blaster...
D/serial_port( 7476): Configuring serial port
E/UEI.SmartControl( 7476): UEIBLaster setting for 616
I/UEI.SmartControl( 7476): Setting serial record hearder size = 2
I/UEI.SmartControl( 7476): configuring settings for MAXQ616
,I/UEI.SmartControl( 7476): Get version...
W/libprocessgroup( 1031): failed to open /acct/uid_10112/pid_6480/cgroup.procs: No such file or directory
,D/UEI.SmartControl( 7476): serial port data available: 21
I/UpdateIcingCorporaServi( 4228): Updating corpora: APPS=com.google.android.videos, CONTACTS=MAYBE
,D/LockScreenSettings( 7435): Quick window widget present in DB = com.lge.clock.quickcover.QuickCoverSettingActivity  true
,D/LockScreenSettings( 7435): Quick window widget present in DB = com.lge.camera.app.QuickWindowCameraActivity  true
D/LockScreenSettings( 7435): Quick window widget present in DB = com.android.contacts.activities.QuickCircleActivity  true
D/LockScreenSettings( 7435): Quick window widget present in DB = com.android.mms.quickcover.QuickCoverActivity  true
D/LockScreenSettings( 7435): Quick window widget present in DB = com.lge.music.MusicQuickCircle  true
D/LockScreenSettings( 7435): Quick window widget present in DB = com.lge.lifetracker.QuickCover  true
D/UEI.SmartControl( 7476): MAXQ616 A2-X4 software.
I/UEI.SmartControl( 7476): IR Blaster version: 256702256704300002
I/UEI.SmartControl( 7476): QS saving settings...
,D/UEI.SmartControl( 7476): IR Blaster version: 25672567
V/SIM_STK ( 1031): Menu title from STK is T-Mobile
D/UEI.SmartControl( 7476): serial port data available: 4
,D/PackageBroadcastService( 2350): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.videos
,D/GCM     ( 2112): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
D/AuthorizationBluetoothService( 2112): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
I/PeopleContactsSync( 2350): CP2 sync disabled
,W/ContextImpl( 7476): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
I/UpdateIcingCorporaServi( 4228): UpdateCorporaTask done [took 85 ms] updated apps [took 85 ms] 
I/UEI.SmartControl( 7476): Device manager: loading config....
D/UEI.SmartControl( 7476): ----------- loading internal config...
,E/UEI.SmartControl( 7476): Services init done
D/UEI.SmartControl( 7476): QS Service init finished
D/UEI.SmartControl( 7476): QS Service version name: 2.1.91
D/UEI.SmartControl( 7476): QS Service version code: 201091
D/UEI.SmartControl( 7476): Service requested: Control
V/GmsCoreStatsServiceLauncher( 2350): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
E/UEI.SmartControl( 7476): Loading SETTINGS...
,D/UEI.SmartControl( 7476): Request IControl service: devices are loaded...
D/WearableService( 7264): callingUid 10005, callindPid: 7264
D/UEI.SmartControl( 7476): -- Open brand translation xml: brands_translations_ko
,E/MDM     ( 1812): [97] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
D/UEI.SmartControl( 7476): Service.onUnbind: IControl
D/UEI.SmartControl( 7476): Service.onDestroy
D/UEI.SmartControl( 7476): Lock is in USE false
D/UEI.SmartControl( 7476): unbind internal service
D/serial_port( 7476): close(fd = 25)
I/UEI.SmartControl( 7476): Serial port is closed.
I/UEI.SmartControl( 7476): Serial port is closed.
D/UEI.SmartControl( 7476): Blaster closed
D/UEI.SmartControl( 7476): Shut down QS...
D/UEI.SmartControl( 7476): Stopping QS lib
D/UEI.SmartControl( 7476): QS lib stop result = true
D/UEI.SmartControl( 7476): Stopped QS lib
D/UEI.SmartControl( 7476): Stopped file observer...
D/UEI.SmartControl( 7476): QS shutdown complete
D/LocationInitializer( 2350): Restart initialization of location
I/UEI.SmartControl( 7476): Notify AllClients services are ready: 11
,D/UEI.SmartControl( 7476): -----service ready thread exits
D/UEI.SmartControl( 7476): QS Service created
I/UEI.SmartControl( 7476): Service initServices...
D/UEI.SmartControl( 7476): QS start get config
,V/Finsky  ( 7459): [1] GearheadStateMonitor.onReady: sIsProjecting:false
,I/UEI.SmartControl( 7476): Supports setup maps: true
D/UEI.SmartControl( 7476): QS start statue = true Error code = 0
I/UEI.SmartControl( 7476): QS version = v2.7.10.1_RC1
I/UEI.SmartControl( 7476): QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
I/UEI.SmartControl( 7476): ### init IR Blaster...
,D/serial_port( 7476): Configuring serial port
E/UEI.SmartControl( 7476): UEIBLaster setting for 616
,I/UEI.SmartControl( 7476): Setting serial record hearder size = 2
I/UEI.SmartControl( 7476): configuring settings for MAXQ616
I/UEI.SmartControl( 7476): Get version...
D/UEI.SmartControl( 7476): serial port data available: 21
,D/UEI.SmartControl( 7476): MAXQ616 A2-X4 software.
I/UEI.SmartControl( 7476): IR Blaster version: 256702256704300002
I/UEI.SmartControl( 7476): QS saving settings...
,D/UEI.SmartControl( 7476): IR Blaster version: 25672567
D/UEI.SmartControl( 7476): serial port data available: 4
,W/ContextImpl( 7476): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
,E/UEI.SmartControl( 7476): Services init done
D/UEI.SmartControl( 7476): QS Service init finished
I/UEI.SmartControl( 7476): Device manager: loading config....
D/UEI.SmartControl( 7476): QS Service version name: 2.1.91
D/UEI.SmartControl( 7476): ----------- loading internal config...
,D/UEI.SmartControl( 7476): QS Service version code: 201091
D/UEI.SmartControl( 7476): Service requested: Control
E/UEI.SmartControl( 7476): Loading SETTINGS...
D/UEI.SmartControl( 7476): -- Open brand translation xml: brands_translations_ko
,D/UEI.SmartControl( 7476): Request IControl service: devices are loaded...
,I/ActivityManager( 1031): Killing 6979:com.lge.clock/u0a10 (adj 15): empty #17
I/UEI.SmartControl( 7476): Notify AllClients services are ready: 0
D/UEI.SmartControl( 7476): -----service ready thread exits
,W/libprocessgroup( 1031): failed to open /acct/uid_10010/pid_6979/cgroup.procs: No such file or directory
,E/ActivityThread( 7476): Service com.uei.control.Service has leaked ServiceConnection com.uei.control.g@397180f3 that was originally bound here
E/ActivityThread( 7476): android.app.ServiceConnectionLeaked: Service com.uei.control.Service has leaked ServiceConnection com.uei.control.g@397180f3 that was originally bound here
E/ActivityThread( 7476): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1167)
E/ActivityThread( 7476): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1061)
E/ActivityThread( 7476): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1839)
E/ActivityThread( 7476): 	at android.app.ContextImpl.bindService(ContextImpl.java:1822)
E/ActivityThread( 7476): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 7476): 	at com.uei.control.Service.b(Unknown Source)
E/ActivityThread( 7476): 	at com.uei.control.Service.a(Unknown Source)
E/ActivityThread( 7476): 	at com.uei.control.Service.onCreate(Unknown Source)
E/ActivityThread( 7476): 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:2738)
E/ActivityThread( 7476): 	at android.app.ActivityThread.access$1800(ActivityThread.java:148)
E/ActivityThread( 7476): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1366)
E/ActivityThread( 7476): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 7476): 	at android.os.Looper.loop(Looper.java:135)
E/ActivityThread( 7476): 	at android.app.ActivityThread.main(ActivityThread.java:5274)
E/ActivityThread( 7476): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread( 7476): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread( 7476): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
E/ActivityThread( 7476): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
D/UEI.SmartControl( 7476): Internal service binding...
D/Finsky  ( 7459): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
,V/AlarmManager( 1031): RTC_WAKEUP set : Alarm{c4f1329 type 0 when 1450100419718 com.android.vending} when 1450100419718
V/GLSActivity( 2112): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2112): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 2112): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2112): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2112): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2112): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/Finsky  ( 7459): [1] 1.onErrorResponse: Unable to preload experiments: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,V/GLSActivity( 2112): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/GLSUser ( 2112): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 2112): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2112): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2112): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2112): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 2112): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2112): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 2112): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2112): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2112): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2112): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/Finsky  ( 7459): [1] LibraryUpdateListener.onErrorResponse: Library replication failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,V/SIM_STK ( 1031): Menu title from STK is T-Mobile
,D/UEI.SmartControl( 7476): Internal timer expired: 2
,V/GLSActivity( 2112): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     ( 1031): Explicit concurrent mark sweep GC freed 50846(2MB) AllocSpace objects, 6(480KB) LOS objects, 33% free, 44MB/66MB, paused 1.937ms total 138.136ms
,I/GLSUser ( 2112): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 2112): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2112): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2112): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2112): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/art     ( 2112): Explicit concurrent mark sweep GC freed 23098(1363KB) AllocSpace objects, 14(2016KB) LOS objects, 50% free, 30MB/62MB, paused 1.517ms total 45.700ms
,W/Finsky  ( 7459): [1] 2.onErrorResponse: Update check failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,D/Finsky  ( 7459): [1] DailyHygiene.logDeviceFeaturesAndContinue: Logging device features
D/Finsky  ( 7459): [1] DailyHygiene.flushEventLogsAndContinue: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 7459): [1] DailyHygiene.reschedule: Scheduling new run in 809 minutes (failures=5)
,D/Finsky  ( 7459): [1] VerifyInstalledPackagesReceiver.onReceive: Verify installed apps requested
D/DeviceConnectionService( 1812): client connected with version: 7571000
,D/Finsky  ( 7459): [1] VerifyInstalledPackagesTask.onPreExecute: Verifying installed apps
V/SIM_STK ( 1031): Menu title from STK is T-Mobile
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=2.7, 0.0, 0.0  rx=2.2 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1598524781] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=2.7, 0.0, 0.0  rx=2.2 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1598524778] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/UEI.SmartControl( 7476): file observer is disposed!
,I/ActivityManager( 1031): Killing 7010:com.google.android.syncadapters.calendar/u0a69 (adj 15): empty #17
,W/libprocessgroup( 1031): failed to open /acct/uid_10069/pid_7010/cgroup.procs: No such file or directory
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=1.8, 0.0, 0.0  rx=1.6 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1598521760] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=1.8, 0.0, 0.0  rx=1.6 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-1598521759] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,D/UEI.SmartControl( 7476): Internal timer expired: 3
D/UEI.SmartControl( 7476): unbind internal service
,D/UEI.SmartControl( 7476): Service.onUnbind: IControl
,D/UEI.SmartControl( 7476): Service.onDestroy
D/UEI.SmartControl( 7476): Lock is in USE false
D/UEI.SmartControl( 7476): unbind internal service
W/System.err( 7476): java.lang.IllegalArgumentException: Service not registered: com.uei.control.g@3e02b0ba
W/System.err( 7476): 	at android.app.LoadedApk.forgetServiceDispatcher(LoadedApk.java:1119)
W/System.err( 7476): 	at android.app.ContextImpl.unbindService(ContextImpl.java:1873)
W/System.err( 7476): 	at android.content.ContextWrapper.unbindService(ContextWrapper.java:550)
W/System.err( 7476): 	at com.uei.control.Service.c(Unknown Source)
W/System.err( 7476): 	at com.uei.control.Service.onDestroy(Unknown Source)
W/System.err( 7476): 	at android.app.ActivityThread.handleStopService(ActivityThread.java:2901)
W/System.err( 7476): 	at android.app.ActivityThread.access$2200(ActivityThread.java:148)
W/System.err( 7476): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1386)
W/System.err( 7476): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 7476): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 7476): 	at android.app.ActivityThread.main(ActivityThread.java:5274)
W/System.err( 7476): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 7476): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 7476): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
W/System.err( 7476): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
E/UEI.SmartControl( 7476): java.lang.IllegalArgumentException: Service not registered: com.uei.control.g@3e02b0ba
D/serial_port( 7476): close(fd = 24)
I/UEI.SmartControl( 7476): Serial port is closed.
I/UEI.SmartControl( 7476): Serial port is closed.
D/UEI.SmartControl( 7476): Blaster closed
D/UEI.SmartControl( 7476): Shut down QS...
D/UEI.SmartControl( 7476): Stopping QS lib
D/UEI.SmartControl( 7476): QS lib stop result = true
D/UEI.SmartControl( 7476): Stopped QS lib
D/UEI.SmartControl( 7476): QS shutdown complete
D/sensors_hal_Time( 1031): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1031): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1031): tsOffsetIs: Apps: 197529227793; DSPS: 6613399; Offset : -4307691062
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.9, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1598518740] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.9, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:4] from screen [on:0 period:-1598518736] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,V/AlarmManager( 1031): ELAPSED_WAKEUP set : Alarm{b57235 type 2 when 201297 android} when 201297
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=1.0, 0.0, 0.0  rx=0.9 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1598515708] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0,
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=1.0, 0.0, 0.0  rx=0.9 bcn=0 [on:0 tx:0 rx:0 period:11] from screen [on:0 period:-1598515697] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=1.0, 0.0, 0.0  rx=1.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1598512685] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=1.0, 0.0, 0.0  rx=1.0 bcn=0 [on:0 tx:0 rx:0 period:4] from screen [on:0 period:-1598512681] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 1 0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 1 0
E/WifiStateMachine( 1031):  ConnectModeState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 1 0
E/WifiStateMachine( 1031):  DriverStartedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 1 0
E/WifiStateMachine( 1031):  SupplicantStartedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 1 0
E/WifiStateMachine( 1031):  DefaultState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 1 0
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.5 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1598509655] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.5 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-1598509654] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1598506635] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:4] from screen [on:0 period:-1598506631] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1598503607] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-1598503597] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1598500575] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1598500572] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,D/sensors_hal_Time( 1031): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1031): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1031): tsOffsetIs: Apps: 217531373932; DSPS: 7268829; Offset : -4307683106
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1598497553] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:4] from screen [on:0 period:-1598497549] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1598494530] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1598494527] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,V/AlarmManager( 1031): RTC_WAKEUP set : Alarm{3a6090e9 type 0 when 1450100439983 com.android.vending} when 1450100439983
,V/SIM_STK ( 1031): Menu title from STK is T-Mobile
,V/GLSActivity( 2112): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2112): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 2112): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2112): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2112): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2112): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/Finsky  ( 7459): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 7459): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 7459): [1] 5.onFinished: Scheduling replication attempt 5.
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1598491503] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1598491500] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1598488473] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1598488470] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,I/[SystemUI]TimeTickManager( 1447): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1447): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1447): called onTimeUpdated()
I/[SystemUI]Clock( 1447): called onTimeUpdated()
,D/PowerManagerServiceEx( 1031): acquireWakeLockInternal: lock=257990054, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1031
I/LgeClockWidgetControlView( 1447): called onTimeUpdated()
I/[SystemUI]DateView( 1447): called onTimeUpdated()
I/[SystemUI]DateView( 1447): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1447): handleTimeUpdate
,V/AlarmManager( 1031): ELAPSED_WAKEUP set : Alarm{bd347a3 type 2 when 231323 android} when 231323
D/[Concierge]Service( 2603): onStartCommand(). Type : 9
,D/PowerManagerServiceEx( 1031): releaseWakeLockInternal: lock=257990054 [*alarm*], flags=0x0
,V/GLSActivity( 2112): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/GLSUser ( 2112): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.syncadapters.contacts, service: cp
I/GLSUser ( 2112): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> cp without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2112): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2112): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2112): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1031): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1031): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1031): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1031): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1031): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
W/GLSActivity( 2112): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2112): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2112): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2112): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2112): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2112): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2112): 	at android.os.Binder.execTransact(Binder.java:446)
,W/ResourcesManager( 1396): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 1396): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
D/LgeQuickCoverNLService( 1396): onNotificationPosted
D/SmartCoverUpdateMonitor( 1396): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1396): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1396): handleNotificationPosted(true)
D/QuickCircle( 1396): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1396): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1396): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1396): post do just update job
D/LgeQuickCoverNotificationData( 1396): showAll3
D/LgeQuickCoverNotificationData( 1396): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1396): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1396): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1396): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1396): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1396): isNotificationForCurrentUser : true
W/ResourcesManager( 1396): Asset path '/system/framework/com.lge.systemui.jar' does not exist or contains no resources.
W/ResourcesManager( 1396): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,D/LgeQuickCoverOverlayWindow( 1396): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1396): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1396): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1396): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1396): updateNotificationData: count=3
D/ContactsSyncAdapter( 2112): innerSync failed
D/ContactsSyncAdapter( 2112): com.google.wireless.gdata2.client.AuthenticationException: unable to get auth token android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
D/ContactsSyncAdapter( 2112): 	at com.google.android.syncadapters.contacts.AuthInfo.getAuthToken(AuthInfo.java:45)
D/ContactsSyncAdapter( 2112): 	at com.google.android.syncadapters.contacts.ContactsSyncAdapter.innerPerformSync(ContactsSyncAdapter.java:263)
D/ContactsSyncAdapter( 2112): 	at com.google.android.syncadapters.contacts.ContactsSyncAdapter.onPerformLoggedSync(ContactsSyncAdapter.java:168)
D/ContactsSyncAdapter( 2112): 	at com.google.android.common.LoggingThreadedSyncAdapter.onPerformSync(LoggingThreadedSyncAdapter.java:33)
D/ContactsSyncAdapter( 2112): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
D/ContactsSyncAdapter( 2112): Caused by: android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
D/ContactsSyncAdapter( 2112): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
D/ContactsSyncAdapter( 2112): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
D/ContactsSyncAdapter( 2112): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
D/ContactsSyncAdapter( 2112): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
D/ContactsSyncAdapter( 2112): 	at android.os.Binder.execTransact(Binder.java:446)
D/QuickStatusbarLayout( 1396): Notification difference=198
,D/QuickStatusbarLayout( 1396): child = android.widget.LinearLayout{b7d9e1f V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,D/SyncManager( 1031): failed sync operation thalitester@gmail.com u0 (com.google), com.android.contacts, LOCAL, currentRunTime 204528, reason: 10019, SyncResult: stats [ numAuthExceptions: 1]
,D/SyncManager( 1031): not retrying sync operation because the error is a hard error: thalitester@gmail.com u0 (com.google), com.android.contacts, LOCAL, currentRunTime 296208, reason: 10019
I/BooksSync( 6699): Starting books sync
D/BooksSync( 6699): started syncMyEbooks
,V/GLSActivity( 2112): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2112): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2112): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 2112): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2112): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2112): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1598485442] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:2] from screen [on:0 period:-1598485440] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,V/NotificationService( 1031): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1031): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1031): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1031): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1031): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
W/GLSActivity( 2112): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2112): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2112): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2112): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2112): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2112): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2112): 	at android.os.Binder.execTransact(Binder.java:446)
,D/LgeQuickCoverNLService( 1396): onNotificationPosted
E/BooksAccountManager( 6699): Authentication error
E/BooksAccountManager( 6699): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6699): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6699): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6699): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6699): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6699): 	at android.os.Binder.execTransact(Binder.java:446)
,E/HttpHelper( 6699): null auth token
D/SmartCoverUpdateMonitor( 1396): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1396): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1396): handleNotificationPosted(true)
D/QuickCircle( 1396): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1396): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1396): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1396): post do just update job
D/LgeQuickCoverNotificationData( 1396): showAll3
D/LgeQuickCoverNotificationData( 1396): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1396): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1396): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1396): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1396): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1396): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1396): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1396): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1396): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1396): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1396): updateNotificationData: count=3
D/QuickStatusbarLayout( 1396): Notification difference=198
D/QuickStatusbarLayout( 1396): child = android.widget.LinearLayout{b7d9e1f V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,W/ApiaryClient( 6699): Error response from books API: {
W/ApiaryClient( 6699):  "error": {
W/ApiaryClient( 6699):   "errors": [
W/ApiaryClient( 6699):    {
W/ApiaryClient( 6699):     "domain": "global",
W/ApiaryClient( 6699):     "reason": "required",
W/ApiaryClient( 6699):     "message": "Login Required",
W/ApiaryClient( 6699):     "locationType": "header",
W/ApiaryClient( 6699):     "location": "Authorization"
W/ApiaryClient( 6699):    }
W/ApiaryClient( 6699):   ],
W/ApiaryClient( 6699):   "code": 401,
W/ApiaryClient( 6699):   "message": "Login Required"
W/ApiaryClient( 6699):  }
W/ApiaryClient( 6699): }
,W/ApiaryClient( 6699): errCount = 1: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6699): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=7787987966358995407&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6699): Headers:
W/ApiaryClient( 6699): accept-encoding: [gzip]
W/ApiaryClient( 6699): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6699): gdata-version: 2
,V/GLSActivity( 2112): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2112): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2112): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2112): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2112): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2112): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1031): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1031): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1031): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1031): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1031): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1396): onNotificationPosted
D/SmartCoverUpdateMonitor( 1396): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1396): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1396): handleNotificationPosted(true)
D/QuickCircle( 1396): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1396): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1396): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1396): post do just update job
D/LgeQuickCoverNotificationData( 1396): showAll3
D/LgeQuickCoverNotificationData( 1396): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1396): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1396): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1396): showNotificationWithSetupData: display=false
,D/LgeQuickCoverOverlayWindow( 1396): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1396): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1396): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1396): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1396): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1396): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1396): updateNotificationData: count=3
W/GLSActivity( 2112): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2112): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2112): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2112): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2112): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2112): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2112): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 6699): Authentication error
E/BooksAccountManager( 6699): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6699): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6699): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6699): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6699): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6699): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6699): null auth token
D/QuickStatusbarLayout( 1396): Notification difference=198
D/QuickStatusbarLayout( 1396): child = android.widget.LinearLayout{b7d9e1f V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,W/ApiaryClient( 6699): Error response from books API: {
W/ApiaryClient( 6699):  "error": {
W/ApiaryClient( 6699):   "errors": [
W/ApiaryClient( 6699):    {
W/ApiaryClient( 6699):     "domain": "global",
W/ApiaryClient( 6699):     "reason": "required",
W/ApiaryClient( 6699):     "message": "Login Required",
W/ApiaryClient( 6699):     "locationType": "header",
W/ApiaryClient( 6699):     "location": "Authorization"
W/ApiaryClient( 6699):    }
W/ApiaryClient( 6699):   ],
W/ApiaryClient( 6699):   "code": 401,
W/ApiaryClient( 6699):   "message": "Login Required"
W/ApiaryClient( 6699):  }
W/ApiaryClient( 6699): }
,W/ApiaryClient( 6699): errCount = 2: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6699): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=7787987966358995407&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6699): Headers:
W/ApiaryClient( 6699): accept-encoding: [gzip]
W/ApiaryClient( 6699): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6699): gdata-version: 2
V/GLSActivity( 2112): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2112): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2112): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2112): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2112): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2112): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1031): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1031): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1031): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1031): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1031): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1396): onNotificationPosted
,D/SmartCoverUpdateMonitor( 1396): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1396): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1396): handleNotificationPosted(true)
D/QuickCircle( 1396): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1396): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1396): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1396): post do just update job
D/LgeQuickCoverNotificationData( 1396): showAll3
D/LgeQuickCoverNotificationData( 1396): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1396): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1396): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1396): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1396): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1396): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1396): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1396): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1396): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1396): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1396): updateNotificationData: count=3
W/GLSActivity( 2112): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2112): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2112): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2112): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2112): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2112): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2112): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 6699): Authentication error
E/BooksAccountManager( 6699): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6699): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6699): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6699): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6699): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6699): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6699): null auth token
D/QuickStatusbarLayout( 1396): Notification difference=198
D/QuickStatusbarLayout( 1396): child = android.widget.LinearLayout{b7d9e1f V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,W/ApiaryClient( 6699): Error response from books API: {
W/ApiaryClient( 6699):  "error": {
W/ApiaryClient( 6699):   "errors": [
W/ApiaryClient( 6699):    {
W/ApiaryClient( 6699):     "domain": "global",
W/ApiaryClient( 6699):     "reason": "required",
W/ApiaryClient( 6699):     "message": "Login Required",
W/ApiaryClient( 6699):     "locationType": "header",
W/ApiaryClient( 6699):     "location": "Authorization"
W/ApiaryClient( 6699):    }
W/ApiaryClient( 6699):   ],
W/ApiaryClient( 6699):   "code": 401,
W/ApiaryClient( 6699):   "message": "Login Required"
W/ApiaryClient( 6699):  }
W/ApiaryClient( 6699): }
,W/ApiaryClient( 6699): errCount = 3: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6699): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=7787987966358995407&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6699): Headers:
W/ApiaryClient( 6699): accept-encoding: [gzip]
W/ApiaryClient( 6699): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6699): gdata-version: 2
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1598482412] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1598482409] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/BooksSync( 6699): Soft error: 
E/BooksSync( 6699): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 6699): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=7787987966358995407&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 6699): Headers:
E/BooksSync( 6699): accept-encoding: [gzip]
E/BooksSync( 6699): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 6699): gdata-version: 2
E/BooksSync( 6699): 
E/BooksSync( 6699): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 6699): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 6699): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 6699): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 6699): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 6699): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 6699): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 6699): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 6699): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 6699): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 6699): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 6699): {
E/BooksSync( 6699):  "error": {
E/BooksSync( 6699):   "errors": [
E/BooksSync( 6699):    {
E/BooksSync( 6699):     "domain": "global",
E/BooksSync( 6699):     "reason": "required",
E/BooksSync( 6699):     "message": "Login Required",
E/BooksSync( 6699):     "locationType": "header",
E/BooksSync( 6699):     "location": "Authorization"
E/BooksSync( 6699):    }
E/BooksSync( 6699):   ],
E/BooksSync( 6699):   "code": 401,
E/BooksSync( 6699):   "message": "Login Required"
E/BooksSync( 6699):  }
E/BooksSync( 6699): }
E/BooksSync( 6699): 
E/BooksSync( 6699): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 6699): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 6699): 	... 8 more
,E/BooksSync( 6699): Sync error
E/BooksSync( 6699): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 6699): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=7787987966358995407&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 6699): Headers:
E/BooksSync( 6699): accept-encoding: [gzip]
E/BooksSync( 6699): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 6699): gdata-version: 2
E/BooksSync( 6699): 
E/BooksSync( 6699): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 6699): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 6699): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 6699): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 6699): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 6699): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 6699): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 6699): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 6699): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 6699): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 6699): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 6699): {
E/BooksSync( 6699):  "error": {
E/BooksSync( 6699):   "errors": [
E/BooksSync( 6699):    {
E/BooksSync( 6699):     "domain": "global",
E/BooksSync( 6699):     "reason": "required",
E/BooksSync( 6699):     "message": "Login Required",
E/BooksSync( 6699):     "locationType": "header",
E/BooksSync( 6699):     "location": "Authorization"
E/BooksSync( 6699):    }
E/BooksSync( 6699):   ],
E/BooksSync( 6699):   "code": 401,
E/BooksSync( 6699):   "message": "Login Required"
E/BooksSync( 6699):  }
E/BooksSync( 6699): }
E/BooksSync( 6699): 
E/BooksSync( 6699): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 6699): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 6699): 	... 8 more
I/BooksSync( 6699): Finished books sync
D/SyncManager( 1031): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 208228, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/sensors_hal_Time( 1031): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1031): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1031): tsOffsetIs: Apps: 237533556163; DSPS: 7924261; Offset : -4307698297
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=3.4, 0.0, 0.0  rx=3.4 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1598479383] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=3.4, 0.0, 0.0  rx=3.4 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1598479380] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=2.2, 0.0, 0.0  rx=2.2 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1598476355] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=2.2, 0.0, 0.0  rx=2.2 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1598476352] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=1.1, 0.0, 0.0  rx=1.1 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1598473326] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=1.1, 0.0, 0.0  rx=1.1 bcn=0 [on:0 tx:0 rx:0 period:11] from screen [on:0 period:-1598473315] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
V/AlarmManager( 1031): ELAPSED_WAKEUP set : Alarm{123c8deb type 2 when 240861 android} when 240861
,V/AlarmManager( 1031): RTC_WAKEUP set : Alarm{20c7a9e1 type 0 when 1450100472475 com.android.vending} when 1450100472475
,V/SIM_STK ( 1031): Menu title from STK is T-Mobile
,V/GLSActivity( 2112): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2112): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 2112): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2112): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2112): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2112): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/Finsky  ( 7459): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 7459): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 7459): [1] 5.onFinished: Giving up after 6 failures.
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=1.1, 0.0, 0.0  rx=1.1 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1598470293] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=1.1, 0.0, 0.0  rx=1.1 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1598470290] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=1.0, 0.0, 0.0  rx=1.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1598467262] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=1.0, 0.0, 0.0  rx=1.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1598467259] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.5 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1598464236] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.5 bcn=0 [on:0 tx:0 rx:0 period:12] from screen [on:0 period:-1598464224] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1598461204] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1598461201] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,D/sensors_hal_Time( 1031): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1031): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1031): tsOffsetIs: Apps: 257535465270; DSPS: 8579683; Offset : -4307681150
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1598458173] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1598458170] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,V/AlarmManager( 1031): ELAPSED_WAKEUP set : Alarm{a00c7db type 2 when 261536 android} when 261536
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3000] from screen [on:0 period:-1598455144] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1598455141] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3000] from screen [on:0 period:-1598452119] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-1598452118] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:-1598449100] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1598449097] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1598446073] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1598446070] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1598443045] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1598443042] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1598440016] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:11] from screen [on:0 period:-1598440005] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
D/sensors_hal_Time( 1031): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1031): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1031): tsOffsetIs: Apps: 277537601252; DSPS: 9235113; Offset : -4307681476
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1598436985] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:4] from screen [on:0 period:-1598436981] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1598433956] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:12] from screen [on:0 period:-1598433944] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1598430923] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1598430920] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1598427894] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1598427891] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,I/[SystemUI]TimeTickManager( 1447): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1447): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1447): called onTimeUpdated()
I/[SystemUI]Clock( 1447): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1447): called onTimeUpdated()
I/[SystemUI]DateView( 1447): called onTimeUpdated()
I/[SystemUI]DateView( 1447): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1447): handleTimeUpdate
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1598424864] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1598424861] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1598421834] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1598421831] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,D/sensors_hal_Time( 1031): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1031): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1031): tsOffsetIs: Apps: 297539335723; DSPS: 9890530; Offset : -4307686403
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3000] from screen [on:0 period:-1598418805] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1598418802] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,D/PowerManagerServiceEx( 1031): acquireWakeLockInternal: lock=257990054, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1031
,V/AlarmManager( 1031): ELAPSED_WAKEUP set : Alarm{2d9c0278 type 2 when 300972 android} when 300972
D/[Concierge]Service( 2603): onStartCommand(). Type : 9
,D/PowerManagerServiceEx( 1031): releaseWakeLockInternal: lock=257990054 [*alarm*], flags=0x0
,I/BooksSync( 6699): Starting books sync
,D/BooksSync( 6699): started syncMyEbooks
,V/GLSActivity( 2112): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/GLSUser ( 2112): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2112): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2112): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2112): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2112): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     ( 1031): Explicit concurrent mark sweep GC freed 58703(2MB) AllocSpace objects, 6(608KB) LOS objects, 33% free, 44MB/66MB, paused 2.219ms total 110.626ms
,V/NotificationService( 1031): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1031): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1031): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1031): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1031): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1396): onNotificationPosted
D/SmartCoverUpdateMonitor( 1396): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1396): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1396): handleNotificationPosted(true)
D/QuickCircle( 1396): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1396): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1396): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1396): post do just update job
D/LgeQuickCoverNotificationData( 1396): showAll3
D/LgeQuickCoverNotificationData( 1396): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1396): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1396): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1396): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1396): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1396): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1396): [native noti] inex =  1
,D/LgeQuickCoverNotificationData( 1396): isNotificationForCurrentUser : true
,D/LgeQuickCoverOverlayWindow( 1396): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1396): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1396): updateNotificationData: count=3
W/GLSActivity( 2112): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2112): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2112): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2112): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2112): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2112): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2112): 	at android.os.Binder.execTransact(Binder.java:446)
E/BooksAccountManager( 6699): Authentication error
E/BooksAccountManager( 6699): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6699): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6699): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6699): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6699): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6699): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6699): null auth token
D/QuickStatusbarLayout( 1396): Notification difference=198
D/QuickStatusbarLayout( 1396): child = android.widget.LinearLayout{b7d9e1f V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,W/ApiaryClient( 6699): Error response from books API: {
W/ApiaryClient( 6699):  "error": {
W/ApiaryClient( 6699):   "errors": [
W/ApiaryClient( 6699):    {
W/ApiaryClient( 6699):     "domain": "global",
W/ApiaryClient( 6699):     "reason": "required",
W/ApiaryClient( 6699):     "message": "Login Required",
W/ApiaryClient( 6699):     "locationType": "header",
W/ApiaryClient( 6699):     "location": "Authorization"
W/ApiaryClient( 6699):    }
W/ApiaryClient( 6699):   ],
W/ApiaryClient( 6699):   "code": 401,
W/ApiaryClient( 6699):   "message": "Login Required"
W/ApiaryClient( 6699):  }
W/ApiaryClient( 6699): }
,W/ApiaryClient( 6699): errCount = 1: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6699): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-7305249799772427974&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6699): Headers:
W/ApiaryClient( 6699): accept-encoding: [gzip]
W/ApiaryClient( 6699): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6699): gdata-version: 2
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1598415775] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:9] from screen [on:0 period:-1598415766] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
V/GLSActivity( 2112): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2112): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2112): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2112): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2112): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2112): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1031): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1031): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1031): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1031): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1031): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1396): onNotificationPosted
,D/SmartCoverUpdateMonitor( 1396): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1396): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1396): handleNotificationPosted(true)
D/QuickCircle( 1396): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1396): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1396): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1396): post do just update job
D/LgeQuickCoverNotificationData( 1396): showAll3
D/LgeQuickCoverNotificationData( 1396): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1396): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1396): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1396): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1396): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1396): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1396): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1396): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1396): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1396): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1396): updateNotificationData: count=3
W/GLSActivity( 2112): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2112): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2112): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2112): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2112): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2112): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2112): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 6699): Authentication error
E/BooksAccountManager( 6699): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6699): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6699): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6699): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6699): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6699): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6699): null auth token
D/QuickStatusbarLayout( 1396): Notification difference=198
D/QuickStatusbarLayout( 1396): child = android.widget.LinearLayout{b7d9e1f V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,W/ApiaryClient( 6699): Error response from books API: {
W/ApiaryClient( 6699):  "error": {
W/ApiaryClient( 6699):   "errors": [
W/ApiaryClient( 6699):    {
W/ApiaryClient( 6699):     "domain": "global",
W/ApiaryClient( 6699):     "reason": "required",
W/ApiaryClient( 6699):     "message": "Login Required",
W/ApiaryClient( 6699):     "locationType": "header",
W/ApiaryClient( 6699):     "location": "Authorization"
W/ApiaryClient( 6699):    }
W/ApiaryClient( 6699):   ],
W/ApiaryClient( 6699):   "code": 401,
W/ApiaryClient( 6699):   "message": "Login Required"
W/ApiaryClient( 6699):  }
W/ApiaryClient( 6699): }
,W/ApiaryClient( 6699): errCount = 2: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6699): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-7305249799772427974&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6699): Headers:
W/ApiaryClient( 6699): accept-encoding: [gzip]
W/ApiaryClient( 6699): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6699): gdata-version: 2
V/GLSActivity( 2112): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2112): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2112): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2112): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2112): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2112): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1031): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1031): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1031): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1031): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1031): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1396): onNotificationPosted
,D/SmartCoverUpdateMonitor( 1396): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1396): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1396): handleNotificationPosted(true)
D/QuickCircle( 1396): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1396): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1396): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1396): post do just update job
D/LgeQuickCoverNotificationData( 1396): showAll3
D/LgeQuickCoverNotificationData( 1396): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1396): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1396): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1396): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1396): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1396): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1396): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1396): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1396): [native noti] inex =  2
,D/LgeQuickCoverNotificationData( 1396): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1396): updateNotificationData: count=3
W/GLSActivity( 2112): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2112): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2112): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2112): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2112): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2112): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2112): 	at android.os.Binder.execTransact(Binder.java:446)
E/BooksAccountManager( 6699): Authentication error
E/BooksAccountManager( 6699): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6699): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6699): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6699): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6699): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6699): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6699): null auth token
,D/QuickStatusbarLayout( 1396): Notification difference=198
D/QuickStatusbarLayout( 1396): child = android.widget.LinearLayout{b7d9e1f V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
W/ApiaryClient( 6699): Error response from books API: {
W/ApiaryClient( 6699):  "error": {
W/ApiaryClient( 6699):   "errors": [
W/ApiaryClient( 6699):    {
W/ApiaryClient( 6699):     "domain": "global",
W/ApiaryClient( 6699):     "reason": "required",
W/ApiaryClient( 6699):     "message": "Login Required",
W/ApiaryClient( 6699):     "locationType": "header",
W/ApiaryClient( 6699):     "location": "Authorization"
W/ApiaryClient( 6699):    }
W/ApiaryClient( 6699):   ],
W/ApiaryClient( 6699):   "code": 401,
W/ApiaryClient( 6699):   "message": "Login Required"
W/ApiaryClient( 6699):  }
W/ApiaryClient( 6699): }
,W/ApiaryClient( 6699): errCount = 3: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6699): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-7305249799772427974&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6699): Headers:
W/ApiaryClient( 6699): accept-encoding: [gzip]
W/ApiaryClient( 6699): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6699): gdata-version: 2
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=1.4, 0.0, 0.0  rx=1.4 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1598412755] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=1.4, 0.0, 0.0  rx=1.4 bcn=0 [on:0 tx:0 rx:0 period:4] from screen [on:0 period:-1598412751] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/BooksSync( 6699): Soft error: 
E/BooksSync( 6699): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 6699): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-7305249799772427974&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 6699): Headers:
E/BooksSync( 6699): accept-encoding: [gzip]
E/BooksSync( 6699): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 6699): gdata-version: 2
E/BooksSync( 6699): 
E/BooksSync( 6699): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 6699): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 6699): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 6699): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 6699): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 6699): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 6699): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 6699): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 6699): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 6699): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 6699): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 6699): {
E/BooksSync( 6699):  "error": {
E/BooksSync( 6699):   "errors": [
E/BooksSync( 6699):    {
E/BooksSync( 6699):     "domain": "global",
E/BooksSync( 6699):     "reason": "required",
E/BooksSync( 6699):     "message": "Login Required",
E/BooksSync( 6699):     "locationType": "header",
E/BooksSync( 6699):     "location": "Authorization"
E/BooksSync( 6699):    }
E/BooksSync( 6699):   ],
E/BooksSync( 6699):   "code": 401,
E/BooksSync( 6699):   "message": "Login Required"
E/BooksSync( 6699):  }
E/BooksSync( 6699): }
E/BooksSync( 6699): 
E/BooksSync( 6699): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 6699): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 6699): 	... 8 more
,E/BooksSync( 6699): Sync error
E/BooksSync( 6699): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 6699): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-7305249799772427974&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 6699): Headers:
E/BooksSync( 6699): accept-encoding: [gzip]
E/BooksSync( 6699): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 6699): gdata-version: 2
E/BooksSync( 6699): 
E/BooksSync( 6699): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 6699): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 6699): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 6699): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 6699): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 6699): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 6699): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 6699): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 6699): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 6699): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 6699): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 6699): {
E/BooksSync( 6699):  "error": {
E/BooksSync( 6699):   "errors": [
E/BooksSync( 6699):    {
E/BooksSync( 6699):     "domain": "global",
E/BooksSync( 6699):     "reason": "required",
E/BooksSync( 6699):     "message": "Login Required",
E/BooksSync( 6699):     "locationType": "header",
E/BooksSync( 6699):     "location": "Authorization"
E/BooksSync( 6699):    }
E/BooksSync( 6699):   ],
E/BooksSync( 6699):   "code": 401,
E/BooksSync( 6699):   "message": "Login Required"
E/BooksSync( 6699):  }
E/BooksSync( 6699): }
E/BooksSync( 6699): 
E/BooksSync( 6699): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 6699): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 6699): 	... 8 more
I/BooksSync( 6699): Finished books sync
D/SyncManager( 1031): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 300972, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=3.2, 0.0, 0.0  rx=3.7 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1598409724] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=3.2, 0.0, 0.0  rx=3.7 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1598409721] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,I/[SystemUI]LGPowerUI( 1447): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1447): On Skip Timer : true
,D/LEDHandler( 1945): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1945): Battery Level Remaining: 100%
D/LEDHandler( 1945): Battery Temp: 285, mChargingStatus=5, mChargingStop=false
,D/KeyguardUpdateMonitor( 1447): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 285
I/[SystemUI]LGPowerUI( 1447): onReceive = android.intent.action.BATTERY_CHANGED
D/WifiController( 1031): battery changed pluggedType: 2
I/[SystemUI]BatterySaverHandler( 1447): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings( 1031): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1031): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/HeadsetStateMachine( 6290): Disconnected process message: 10, size: 0
D/LGDMClient( 3941): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.intent.action.BATTERY_CHANGED
D/LGDMClient( 3941): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=2.1, 0.0, 0.0  rx=2.3 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1598406693] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=2.1, 0.0, 0.0  rx=2.3 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1598406690] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=1.0, 0.0, 0.0  rx=1.2 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:-1598403662] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=1.0, 0.0, 0.0  rx=1.2 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1598403659] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=1.0, 0.0, 0.0  rx=1.1 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1598400632] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=1.0, 0.0, 0.0  rx=1.1 bcn=0 [on:0 tx:0 rx:0 period:2] from screen [on:0 period:-1598400630] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,D/sensors_hal_Time( 1031): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1031): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1031): tsOffsetIs: Apps: 317541535612; DSPS: 10545962; Offset : -4307683572
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.5 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1598397602] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.5 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1598397599] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1598394573] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1598394570] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.9, 0.0, 0.0  rx=0.9 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1598391550] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.9, 0.0, 0.0  rx=0.9 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1598391547] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1598388522] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1598388519] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,V/AlarmManager( 1031): ELAPSED_WAKEUP set : Alarm{2ae292a2 type 2 when 331235 android} when 331235
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1598385492] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1598385489] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1598382467] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-1598382457] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
D/sensors_hal_Time( 1031): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1031): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1031): tsOffsetIs: Apps: 337543429198; DSPS: 11201384; Offset : -4307682154
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1598379436] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:9] from screen [on:0 period:-1598379427] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3000] from screen [on:0 period:-1598376407] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:11] from screen [on:0 period:-1598376396] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1598373375] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1598373372] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1598370348] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-1598370338] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1598367317] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:11] from screen [on:0 period:-1598367306] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
I/ActivityManager( 1031): Killing 7098:com.google.android.talk/u0a72 (adj 15): empty #17
,W/libprocessgroup( 1031): failed to open /acct/uid_10072/pid_7098/cgroup.procs: No such file or directory
,D/PowerManagerServiceEx( 1031): acquireWakeLockInternal: lock=257990054, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1031
,D/[Concierge]Service( 2603): onStartCommand(). Type : 9
,I/[SystemUI]TimeTickManager( 1447): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1447): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1447): called onTimeUpdated()
I/[SystemUI]Clock( 1447): called onTimeUpdated()
I/LgeClockWidgetControlView( 1447): called onTimeUpdated()
I/[SystemUI]DateView( 1447): called onTimeUpdated()
I/[SystemUI]DateView( 1447): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1447): handleTimeUpdate
,D/PowerManagerServiceEx( 1031): releaseWakeLockInternal: lock=257990054 [*alarm*], flags=0x0
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1598364285] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:4] from screen [on:0 period:-1598364281] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1598361258] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-1598361248] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
D/sensors_hal_Time( 1031): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1031): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1031): tsOffsetIs: Apps: 357545602888; DSPS: 11856815; Offset : -4307675368
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1598358227] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-1598358217] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1598355196] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:4] from screen [on:0 period:-1598355192] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1598352166] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:11] from screen [on:0 period:-1598352155] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1598349132] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1598349129] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1598346107] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-1598346097] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1598343075] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1598343072] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1598340048] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:8] from screen [on:0 period:-1598340040] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
D/sensors_hal_Time( 1031): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1031): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1031): tsOffsetIs: Apps: 377547494756; DSPS: 12512237; Offset : -4307675512
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1598337018] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:9] from screen [on:0 period:-1598337009] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1598333989] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1598333986] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1598330957] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-1598330947] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1598327927] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:11] from screen [on:0 period:-1598327916] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1598324893] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1598324890] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1598321863] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1598321860] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,D/sensors_hal_Time( 1031): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1031): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1031): tsOffsetIs: Apps: 397548969071; DSPS: 13167646; Offset : -4307696584
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1598318834] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1598318831] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3000] from screen [on:0 period:-1598315806] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:4] from screen [on:0 period:-1598315802] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1598312777] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-1598312767] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1598309747] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-1598309737] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
I/jxcore-log( 6219): Connected to the server!
I/jxcore-log( 6219): 
,I/chromium( 6219): [INFO:CONSOLE(63)] "logCallback Connected to the server", source: file:///android_asset/www/js/thali_main.js (63)
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1598306714] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1598306711] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,I/[SystemUI]TimeTickManager( 1447): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1447): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1447): called onTimeUpdated()
I/[SystemUI]Clock( 1447): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1447): called onTimeUpdated()
I/[SystemUI]DateView( 1447): called onTimeUpdated()
I/[SystemUI]DateView( 1447): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1447): handleTimeUpdate
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=3.7, 0.0, 0.0  rx=3.2 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1598303686] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=3.7, 0.0, 0.0  rx=3.2 bcn=0 [on:0 tx:0 rx:0 period:11] from screen [on:0 period:-1598303675] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=1.8, 0.0, 0.0  rx=1.6 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1598300655] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=1.8, 0.0, 0.0  rx=1.6 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1598300652] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,D/sensors_hal_Time( 1031): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1031): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1031): tsOffsetIs: Apps: 417551793231; DSPS: 13823098; Offset : -4307679859
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=6.9, 0.0, 0.0  rx=8.3 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1598297623] gl rssi=-45 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=6.9, 0.0, 0.0  rx=8.3 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1598297620] gl rssi=-45 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=3.5, 0.0, 0.0  rx=4.1 bcn=0 [on:0 tx:0 rx:0 period:3000] from screen [on:0 period:-1598294592] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=3.5, 0.0, 0.0  rx=4.1 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1598294589] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=3.7, 0.0, 0.0  rx=4.6 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1598291563] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=3.7, 0.0, 0.0  rx=4.6 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1598291560] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=1.9, 0.0, 0.0  rx=2.3 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1598288533] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=1.9, 0.0, 0.0  rx=2.3 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1598288530] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.9, 0.0, 0.0  rx=1.1 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1598285503] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.9, 0.0, 0.0  rx=1.1 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1598285500] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.6 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1598282474] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.6 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1598282471] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,D/PowerManagerServiceEx( 1031): acquireWakeLockInternal: lock=257990054, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1031
,V/AlarmManager( 1031): ELAPSED_WAKEUP set : Alarm{1671fb33 type 2 when 435987 android} when 435987
D/[Concierge]Service( 2603): onStartCommand(). Type : 9
,D/PowerManagerServiceEx( 1031): releaseWakeLockInternal: lock=257990054 [*alarm*], flags=0x0
,I/BooksSync( 6699): Starting books sync
,D/BooksSync( 6699): started syncMyEbooks
,V/GLSActivity( 2112): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/GLSUser ( 2112): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2112): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2112): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2112): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2112): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1031): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1031): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1031): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1031): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1031): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1396): onNotificationPosted
,D/SmartCoverUpdateMonitor( 1396): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1396): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1396): handleNotificationPosted(true)
D/QuickCircle( 1396): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1396): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1396): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1396): post do just update job
D/LgeQuickCoverNotificationData( 1396): showAll3
D/LgeQuickCoverNotificationData( 1396): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1396): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1396): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1396): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1396): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1396): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1396): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1396): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1396): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1396): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1396): updateNotificationData: count=3
W/GLSActivity( 2112): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2112): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2112): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2112): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2112): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2112): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2112): 	at android.os.Binder.execTransact(Binder.java:446)
E/BooksAccountManager( 6699): Authentication error
E/BooksAccountManager( 6699): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6699): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6699): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6699): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6699): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6699): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6699): null auth token
D/QuickStatusbarLayout( 1396): Notification difference=198
D/QuickStatusbarLayout( 1396): child = android.widget.LinearLayout{b7d9e1f V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,W/ApiaryClient( 6699): Error response from books API: {
W/ApiaryClient( 6699):  "error": {
W/ApiaryClient( 6699):   "errors": [
W/ApiaryClient( 6699):    {
W/ApiaryClient( 6699):     "domain": "global",
W/ApiaryClient( 6699):     "reason": "required",
W/ApiaryClient( 6699):     "message": "Login Required",
W/ApiaryClient( 6699):     "locationType": "header",
W/ApiaryClient( 6699):     "location": "Authorization"
W/ApiaryClient( 6699):    }
W/ApiaryClient( 6699):   ],
W/ApiaryClient( 6699):   "code": 401,
W/ApiaryClient( 6699):   "message": "Login Required"
W/ApiaryClient( 6699):  }
W/ApiaryClient( 6699): }
,W/ApiaryClient( 6699): errCount = 1: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6699): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-8221851801717703381&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6699): Headers:
W/ApiaryClient( 6699): accept-encoding: [gzip]
W/ApiaryClient( 6699): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6699): gdata-version: 2
V/GLSActivity( 2112): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2112): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2112): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2112): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2112): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2112): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1031): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,D/sensors_hal_Time( 1031): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1031): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1031): tsOffsetIs: Apps: 437556998379; DSPS: 14478629; Offset : -4307691238
V/NotificationService( 1031): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1031): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1031): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1031): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1396): onNotificationPosted
,D/SmartCoverUpdateMonitor( 1396): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1396): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1396): handleNotificationPosted(true)
D/QuickCircle( 1396): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1396): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1396): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1396): post do just update job
D/LgeQuickCoverNotificationData( 1396): showAll3
D/LgeQuickCoverNotificationData( 1396): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1396): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1396): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1396): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1396): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1396): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1396): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1396): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1396): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1396): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1396): updateNotificationData: count=3
W/GLSActivity( 2112): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2112): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2112): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2112): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2112): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2112): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2112): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 6699): Authentication error
E/BooksAccountManager( 6699): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6699): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6699): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6699): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6699): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6699): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6699): null auth token
D/QuickStatusbarLayout( 1396): Notification difference=198
D/QuickStatusbarLayout( 1396): child = android.widget.LinearLayout{b7d9e1f V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
W/ApiaryClient( 6699): Error response from books API: {
W/ApiaryClient( 6699):  "error": {
W/ApiaryClient( 6699):   "errors": [
W/ApiaryClient( 6699):    {
W/ApiaryClient( 6699):     "domain": "global",
W/ApiaryClient( 6699):     "reason": "required",
W/ApiaryClient( 6699):     "message": "Login Required",
W/ApiaryClient( 6699):     "locationType": "header",
W/ApiaryClient( 6699):     "location": "Authorization"
W/ApiaryClient( 6699):    }
W/ApiaryClient( 6699):   ],
W/ApiaryClient( 6699):   "code": 401,
W/ApiaryClient( 6699):   "message": "Login Required"
W/ApiaryClient( 6699):  }
W/ApiaryClient( 6699): }
,W/ApiaryClient( 6699): errCount = 2: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6699): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-8221851801717703381&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6699): Headers:
W/ApiaryClient( 6699): accept-encoding: [gzip]
W/ApiaryClient( 6699): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6699): gdata-version: 2
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=1.2, 0.0, 0.0  rx=1.3 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1598279443] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=1.2, 0.0, 0.0  rx=1.3 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1598279440] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,V/GLSActivity( 2112): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     ( 2112): Explicit concurrent mark sweep GC freed 30783(1879KB) AllocSpace objects, 20(2MB) LOS objects, 50% free, 30MB/62MB, paused 2.571ms total 63.721ms
,I/GLSUser ( 2112): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 2112): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2112): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2112): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2112): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1031): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1031): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1031): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1031): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1031): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1396): onNotificationPosted
,D/SmartCoverUpdateMonitor( 1396): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1396): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1396): handleNotificationPosted(true)
D/QuickCircle( 1396): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1396): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1396): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1396): post do just update job
D/LgeQuickCoverNotificationData( 1396): showAll3
D/LgeQuickCoverNotificationData( 1396): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1396): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1396): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1396): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1396): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1396): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1396): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1396): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1396): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1396): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1396): updateNotificationData: count=3
,W/GLSActivity( 2112): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2112): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2112): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2112): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2112): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2112): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2112): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 6699): Authentication error
E/BooksAccountManager( 6699): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6699): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6699): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6699): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6699): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6699): 	at android.os.Binder.execTransact(Binder.java:446)
,E/HttpHelper( 6699): null auth token
D/QuickStatusbarLayout( 1396): Notification difference=198
D/QuickStatusbarLayout( 1396): child = android.widget.LinearLayout{b7d9e1f V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
W/ApiaryClient( 6699): Error response from books API: {
W/ApiaryClient( 6699):  "error": {
W/ApiaryClient( 6699):   "errors": [
W/ApiaryClient( 6699):    {
W/ApiaryClient( 6699):     "domain": "global",
W/ApiaryClient( 6699):     "reason": "required",
W/ApiaryClient( 6699):     "message": "Login Required",
W/ApiaryClient( 6699):     "locationType": "header",
W/ApiaryClient( 6699):     "location": "Authorization"
W/ApiaryClient( 6699):    }
W/ApiaryClient( 6699):   ],
W/ApiaryClient( 6699):   "code": 401,
W/ApiaryClient( 6699):   "message": "Login Required"
W/ApiaryClient( 6699):  }
W/ApiaryClient( 6699): }
W/ApiaryClient( 6699): errCount = 3: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6699): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-8221851801717703381&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6699): Headers:
W/ApiaryClient( 6699): accept-encoding: [gzip]
W/ApiaryClient( 6699): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6699): gdata-version: 2
,E/BooksSync( 6699): Soft error: 
E/BooksSync( 6699): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 6699): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-8221851801717703381&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 6699): Headers:
E/BooksSync( 6699): accept-encoding: [gzip]
E/BooksSync( 6699): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 6699): gdata-version: 2
E/BooksSync( 6699): 
E/BooksSync( 6699): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 6699): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 6699): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 6699): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 6699): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 6699): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 6699): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 6699): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 6699): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 6699): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 6699): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 6699): {
E/BooksSync( 6699):  "error": {
E/BooksSync( 6699):   "errors": [
E/BooksSync( 6699):    {
E/BooksSync( 6699):     "domain": "global",
E/BooksSync( 6699):     "reason": "required",
E/BooksSync( 6699):     "message": "Login Required",
E/BooksSync( 6699):     "locationType": "header",
E/BooksSync( 6699):     "location": "Authorization"
E/BooksSync( 6699):    }
E/BooksSync( 6699):   ],
E/BooksSync( 6699):   "code": 401,
E/BooksSync( 6699):   "message": "Login Required"
E/BooksSync( 6699):  }
E/BooksSync( 6699): }
E/BooksSync( 6699): 
E/BooksSync( 6699): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 6699): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 6699): 	... 8 more
,E/BooksSync( 6699): Sync error
E/BooksSync( 6699): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 6699): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-8221851801717703381&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 6699): Headers:
E/BooksSync( 6699): accept-encoding: [gzip]
E/BooksSync( 6699): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 6699): gdata-version: 2
E/BooksSync( 6699): 
E/BooksSync( 6699): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 6699): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 6699): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 6699): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 6699): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 6699): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 6699): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 6699): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 6699): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 6699): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 6699): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 6699): {
E/BooksSync( 6699):  "error": {
E/BooksSync( 6699):   "errors": [
E/BooksSync( 6699):    {
E/BooksSync( 6699):     "domain": "global",
E/BooksSync( 6699):     "reason": "required",
E/BooksSync( 6699):     "message": "Login Required",
E/BooksSync( 6699):     "locationType": "header",
E/BooksSync( 6699):     "location": "Authorization"
E/BooksSync( 6699):    }
E/BooksSync( 6699):   ],
E/BooksSync( 6699):   "code": 401,
E/BooksSync( 6699):   "message": "Login Required"
E/BooksSync( 6699):  }
E/BooksSync( 6699): }
E/BooksSync( 6699): 
E/BooksSync( 6699): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 6699): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 6699): 	... 8 more
I/BooksSync( 6699): Finished books sync
D/SyncManager( 1031): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 435987, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=3.6, 0.0, 0.0  rx=3.6 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:-1598276420] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=3.6, 0.0, 0.0  rx=3.6 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1598276417] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=3.3, 0.0, 0.0  rx=2.8 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:-1598273389] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=3.3, 0.0, 0.0  rx=2.8 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1598273386] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=1.7, 0.0, 0.0  rx=1.4 bcn=0 [on:0 tx:0 rx:0 period:3005] from screen [on:0 period:-1598270363] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=1.7, 0.0, 0.0  rx=1.4 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1598270360] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1598267341] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1598267338] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3000] from screen [on:0 period:-1598264313] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:4] from screen [on:0 period:-1598264309] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.2, 0.0, 0.0  rx=0.2 bcn=0 [on:0 tx:0 rx:0 period:3000] from screen [on:0 period:-1598261284] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.2, 0.0, 0.0  rx=0.2 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1598261281] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,D/sensors_hal_Time( 1031): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1031): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1031): tsOffsetIs: Apps: 457559066496; DSPS: 15134057; Offset : -4307700295
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1598258256] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:12] from screen [on:0 period:-1598258244] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=1.1, 0.0, 0.0  rx=0.5 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1598255223] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=1.1, 0.0, 0.0  rx=0.5 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1598255220] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.3 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1598252194] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.3 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1598252191] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,V/AlarmManager( 1031): ELAPSED_WAKEUP set : Alarm{3c8c8281 type 2 when 466204 android} when 466204
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.3, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1598249165] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.3, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1598249162] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1598246134] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1598246131] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,I/[SystemUI]TimeTickManager( 1447): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1447): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1447): called onTimeUpdated()
I/[SystemUI]Clock( 1447): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1447): called onTimeUpdated()
I/[SystemUI]DateView( 1447): called onTimeUpdated()
I/[SystemUI]DateView( 1447): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1447): handleTimeUpdate
D/PowerManagerServiceEx( 1031): acquireWakeLockInternal: lock=257990054, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1031
,I/ActivityManager( 1031): Start proc com.lge.clock for broadcast com.lge.clock/.widget.DigitalAppWidgetProvider: pid=7750 uid=10010 gids={50010, 9997, 3003, 1028, 4002} abi=armeabi-v7a
,D/[Concierge]Service( 2603): onStartCommand(). Type : 9
,I/DigitalAppWidgetProvider( 7750): onReceive: com.android.deskclock.ON_QUARTER_HOUR
,V/DigitalAppWidgetProvider( 7750): startAlarmOnQuarterHour android.app.ReceiverRestrictedContext@21cdf798
,D/PowerManagerServiceEx( 1031): releaseWakeLockInternal: lock=257990054 [*alarm*], flags=0x0
I/ActivityManager( 1031): Killing 6855:com.lge.sizechangable.weather/u0a85 (adj 15): empty #17
W/libprocessgroup( 1031): failed to open /acct/uid_10085/pid_6855/cgroup.procs: No such file or directory
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1598243098] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:13] from screen [on:0 period:-1598243085] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1598240063] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1598240060] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,D/sensors_hal_Time( 1031): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1031): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1031): tsOffsetIs: Apps: 477561572218; DSPS: 15789499; Offset : -4307697171
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1598237033] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1598237030] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,I/[SystemUI]LGPowerUI( 1447): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1447): On Skip Timer : true
,D/WifiController( 1031): battery changed pluggedType: 2
,D/LEDHandler( 1945): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1945): Battery Level Remaining: 100%
D/LEDHandler( 1945): Battery Temp: 282, mChargingStatus=5, mChargingStop=false
D/KeyguardUpdateMonitor( 1447): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 282
I/[SystemUI]LGPowerUI( 1447): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings( 1031): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1031): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/HeadsetStateMachine( 6290): Disconnected process message: 10, size: 0
I/[SystemUI]BatterySaverHandler( 1447): onReceive = android.intent.action.BATTERY_CHANGED
D/LGDMClient( 3941): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.intent.action.BATTERY_CHANGED
D/LGDMClient( 3941): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1598234004] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1598234001] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=1.5, 0.0, 0.0  rx=1.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1598230981] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=1.5, 0.0, 0.0  rx=1.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1598230978] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.5 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1598227952] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.5 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1598227949] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,V/GLSActivity( 2112): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2112): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 2112): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2112): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2112): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2112): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1031): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1031): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1031): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1031): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1031): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1396): onNotificationPosted
,D/SmartCoverUpdateMonitor( 1396): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1396): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1396): handleNotificationPosted(true)
D/QuickCircle( 1396): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1396): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1396): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1396): post do just update job
D/LgeQuickCoverNotificationData( 1396): showAll3
D/LgeQuickCoverNotificationData( 1396): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1396): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1396): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1396): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1396): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1396): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1396): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1396): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1396): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1396): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1396): updateNotificationData: count=3
W/GLSActivity( 2112): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2112): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2112): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2112): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2112): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2112): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2112): 	at android.os.Binder.execTransact(Binder.java:446)
,E/PlayEventLogger( 7459): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 7459): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 7459): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/PlayEventLogger( 7459): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 7459): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/PlayEventLogger( 7459): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 7459): 	at android.os.Binder.execTransact(Binder.java:446)
D/QuickStatusbarLayout( 1396): Notification difference=198
D/QuickStatusbarLayout( 1396): child = android.widget.LinearLayout{b7d9e1f V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,W/System  ( 7459): Ignoring header User-Agent because its value was null.
,D/libc-netbsd(  313): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  313): res_queryN name = play.googleapis.com, class = 1, type = 1
D/libc-netbsd(  313): res_queryN name = play.googleapis.com succeed
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.3 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1598224923] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.3 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1598224920] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=5.7, 0.0, 0.0  rx=5.1 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1598221892] gl rssi=-45 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=5.7, 0.0, 0.0  rx=5.1 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1598221889] gl rssi=-45 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,D/sensors_hal_Time( 1031): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1031): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1031): tsOffsetIs: Apps: 497563691897; DSPS: 16444928; Offset : -4307683153
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=2.8, 0.0, 0.0  rx=2.6 bcn=0 [on:0 tx:0 rx:0 period:3000] from screen [on:0 period:-1598218863] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=2.8, 0.0, 0.0  rx=2.6 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1598218860] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=1.4, 0.0, 0.0  rx=1.3 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1598215833] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=1.4, 0.0, 0.0  rx=1.3 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1598215830] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.6 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1598212804] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.6 bcn=0 [on:0 tx:0 rx:0 period:4] from screen [on:0 period:-1598212800] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.3 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1598209773] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.3 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1598209770] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.2, 0.0, 0.0  rx=0.2 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1598206744] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.2, 0.0, 0.0  rx=0.2 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1598206741] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=1.1, 0.0, 0.0  rx=0.6 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1598203715] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=1.1, 0.0, 0.0  rx=0.6 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1598203712] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.3 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1598200685] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.3 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1598200682] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,D/sensors_hal_Time( 1031): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1031): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1031): tsOffsetIs: Apps: 517565730067; DSPS: 17100355; Offset : -4307689739
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=1.1 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1598197656] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=1.1 bcn=0 [on:0 tx:0 rx:0 period:11] from screen [on:0 period:-1598197645] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=1.4, 0.0, 0.0  rx=1.6 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:-1598194630] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=1.4, 0.0, 0.0  rx=1.6 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1598194627] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1598191602] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1598191599] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.9 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1598188572] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.9 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1598188569] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,I/[SystemUI]TimeTickManager( 1447): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1447): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1447): called onTimeUpdated()
I/[SystemUI]Clock( 1447): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1447): called onTimeUpdated()
I/[SystemUI]DateView( 1447): called onTimeUpdated()
I/[SystemUI]DateView( 1447): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1447): handleTimeUpdate
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.9, 0.0, 0.0  rx=0.9 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1598185545] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0,
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.9, 0.0, 0.0  rx=0.9 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1598185542] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.5 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1598182513] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.5 bcn=0 [on:0 tx:0 rx:0 period:11] from screen [on:0 period:-1598182502] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
D/sensors_hal_Time( 1031): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1031): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1031): tsOffsetIs: Apps: 537567616830; DSPS: 17755777; Offset : -4307695195
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1598179482] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1598179479] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1598176452] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1598176449] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1598173427] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:14] from screen [on:0 period:-1598173413] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1598170393] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-1598170383] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1598167362] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1598167359] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1598164332] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1598164329] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1598161303] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1598161300] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,D/sensors_hal_Time( 1031): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1031): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1031): tsOffsetIs: Apps: 557569641145; DSPS: 18411203; Offset : -4307684807
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1598158274] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:12] from screen [on:0 period:-1598158262] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1598155243] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1598155240] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1598152212] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1598152209] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1598149183] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1598149180] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1598146155] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1598146152] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1598143125] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:4] from screen [on:0 period:-1598143121] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1598140098] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:9] from screen [on:0 period:-1598140089] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
D/sensors_hal_Time( 1031): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1031): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1031): tsOffsetIs: Apps: 577572650670; DSPS: 19066662; Offset : -4307696599
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3006] from screen [on:0 period:-1598137064] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-1598137054] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1598134038] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-1598134028] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:2987] from screen [on:0 period:-1598131007] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:12] from screen [on:0 period:-1598130995] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1598127973] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1598127970] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,I/[SystemUI]TimeTickManager( 1447): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1447): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1447): called onTimeUpdated()
I/[SystemUI]Clock( 1447): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1447): called onTimeUpdated()
I/[SystemUI]DateView( 1447): called onTimeUpdated()
,I/[SystemUI]DateView( 1447): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1447): handleTimeUpdate
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1598124943] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1598124940] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL],
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1598121912] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1598121909] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,D/sensors_hal_Time( 1031): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1031): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1031): tsOffsetIs: Apps: 597574819464; DSPS: 19722093; Offset : -4307694450
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1598118882] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1598118879] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.9, 0.0, 0.0  rx=0.9 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1598115862] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.9, 0.0, 0.0  rx=0.9 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1598115859] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1598112832] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1598112829] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1598109802] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1598109799] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1598106772] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1598106769] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1598103742] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1598103739] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1598100721] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1598100718] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,D/sensors_hal_Time( 1031): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1031): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1031): tsOffsetIs: Apps: 617580443154; DSPS: 20377637; Offset : -4307686124
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1598097692] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1598097689] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3000] from screen [on:0 period:-1598094667] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:9] from screen [on:0 period:-1598094658] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1598091637] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:11] from screen [on:0 period:-1598091626] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1598088605] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1598088602] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3000] from screen [on:0 period:-1598085586] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:4] from screen [on:0 period:-1598085582] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1598082556] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-1598082546] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
D/sensors_hal_Time( 1031): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1031): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1031): tsOffsetIs: Apps: 637582594969; DSPS: 21033068; Offset : -4307701214
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1598079524] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1598079521] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1598076493] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1598076490] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1598073463] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:4] from screen [on:0 period:-1598073459] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,D/PowerManagerServiceEx( 1031): acquireWakeLockInternal: lock=257990054, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1031
,D/[Concierge]Service( 2603): onStartCommand(). Type : 9
,D/PowerManagerServiceEx( 1031): releaseWakeLockInternal: lock=257990054 [*alarm*], flags=0x0
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1598070441] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1598070438] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3007] from screen [on:0 period:-1598067414] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-1598067404] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
I/[SystemUI]TimeTickManager( 1447): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1447): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1447): called onTimeUpdated()
I/[SystemUI]Clock( 1447): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1447): called onTimeUpdated()
I/[SystemUI]DateView( 1447): called onTimeUpdated()
I/[SystemUI]DateView( 1447): called onTimeUpdated()
,D/KeyguardUpdateMonitor( 1447): handleTimeUpdate
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1598064388] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:9] from screen [on:0 period:-1598064379] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1598061357] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:11] from screen [on:0 period:-1598061346] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
D/sensors_hal_Time( 1031): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1031): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1031): tsOffsetIs: Apps: 657584747774; DSPS: 21688498; Offset : -4307684482
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1598058325] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1598058322] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1598055305] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1598055302] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1598052276] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:9] from screen [on:0 period:-1598052267] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1598049247] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:11] from screen [on:0 period:-1598049236] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1598046215] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1598046212] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1598043185] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1598043182] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3000] from screen [on:0 period:-1598040166] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1598040163] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,D/sensors_hal_Time( 1031): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1031): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1031): tsOffsetIs: Apps: 677586908860; DSPS: 22343929; Offset : -4307690118
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1598037137] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-1598037127] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=1.2, 0.0, 0.0  rx=1.2 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1598034107] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=1.2, 0.0, 0.0  rx=1.2 bcn=0 [on:0 tx:0 rx:0 period:12] from screen [on:0 period:-1598034095] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.6, 0.0, 0.0  rx=0.6 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1598031075] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.6, 0.0, 0.0  rx=0.6 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1598031072] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3000] from screen [on:0 period:-1598028046] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:11] from screen [on:0 period:-1598028035] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.9, 0.0, 0.0  rx=0.9 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1598025021] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.9, 0.0, 0.0  rx=0.9 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1598025018] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.5 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1598021992] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.5 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1598021989] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,D/sensors_hal_Time( 1031): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1031): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1031): tsOffsetIs: Apps: 697588797498; DSPS: 22999351; Offset : -4307693518
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1598018962] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1598018959] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1598015933] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1598015930] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,D/PowerManagerServiceEx( 1031): acquireWakeLockInternal: lock=257990054, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1031
,V/AlarmManager( 1031): ELAPSED_WAKEUP set : Alarm{1b70af7b type 2 when 701862 android} when 701862
D/[Concierge]Service( 2603): onStartCommand(). Type : 9
,D/PowerManagerServiceEx( 1031): releaseWakeLockInternal: lock=257990054 [*alarm*], flags=0x0
,I/BooksSync( 6699): Starting books sync
,D/BooksSync( 6699): started syncMyEbooks
,V/GLSActivity( 2112): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2112): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2112): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2112): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2112): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2112): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1031): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1031): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1031): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1031): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1031): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
W/GLSActivity( 2112): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2112): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2112): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2112): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2112): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2112): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2112): 	at android.os.Binder.execTransact(Binder.java:446)
,D/LgeQuickCoverNLService( 1396): onNotificationPosted
E/BooksAccountManager( 6699): Authentication error
E/BooksAccountManager( 6699): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6699): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6699): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6699): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6699): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6699): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6699): null auth token
D/SmartCoverUpdateMonitor( 1396): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1396): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1396): handleNotificationPosted(true)
D/QuickCircle( 1396): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1396): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1396): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1396): post do just update job
D/LgeQuickCoverNotificationData( 1396): showAll3
D/LgeQuickCoverNotificationData( 1396): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1396): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1396): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1396): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1396): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1396): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1396): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1396): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1396): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1396): isNotificationForCurrentUser : true
,D/libc-netbsd(  313): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  313): res_queryN name = www.googleapis.com, class = 1, type = 1
E/LgeQuickCoverOverlayWindow( 1396): updateNotificationData: count=3
D/QuickStatusbarLayout( 1396): Notification difference=198
D/QuickStatusbarLayout( 1396): child = android.widget.LinearLayout{b7d9e1f V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,D/libc-netbsd(  313): res_queryN name = www.googleapis.com succeed
,W/ApiaryClient( 6699): Error response from books API: {
W/ApiaryClient( 6699):  "error": {
W/ApiaryClient( 6699):   "errors": [
W/ApiaryClient( 6699):    {
W/ApiaryClient( 6699):     "domain": "global",
W/ApiaryClient( 6699):     "reason": "required",
W/ApiaryClient( 6699):     "message": "Login Required",
W/ApiaryClient( 6699):     "locationType": "header",
W/ApiaryClient( 6699):     "location": "Authorization"
W/ApiaryClient( 6699):    }
W/ApiaryClient( 6699):   ],
W/ApiaryClient( 6699):   "code": 401,
W/ApiaryClient( 6699):   "message": "Login Required"
W/ApiaryClient( 6699):  }
W/ApiaryClient( 6699): }
,W/ApiaryClient( 6699): errCount = 1: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6699): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=403983735489463737&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6699): Headers:
W/ApiaryClient( 6699): accept-encoding: [gzip]
W/ApiaryClient( 6699): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6699): gdata-version: 2
V/GLSActivity( 2112): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2112): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 2112): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2112): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2112): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2112): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1031): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1031): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1031): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1031): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1031): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
W/GLSActivity( 2112): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2112): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2112): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2112): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2112): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2112): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2112): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 6699): Authentication error
E/BooksAccountManager( 6699): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6699): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6699): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6699): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6699): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6699): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6699): null auth token
,I/art     ( 1031): Explicit concurrent mark sweep GC freed 130141(5MB) AllocSpace objects, 11(1328KB) LOS objects, 33% free, 44MB/66MB, paused 2.348ms total 167.852ms
,W/ApiaryClient( 6699): Error response from books API: {
W/ApiaryClient( 6699):  "error": {
W/ApiaryClient( 6699):   "errors": [
W/ApiaryClient( 6699):    {
W/ApiaryClient( 6699):     "domain": "global",
W/ApiaryClient( 6699):     "reason": "required",
W/ApiaryClient( 6699):     "message": "Login Required",
W/ApiaryClient( 6699):     "locationType": "header",
W/ApiaryClient( 6699):     "location": "Authorization"
W/ApiaryClient( 6699):    }
W/ApiaryClient( 6699):   ],
W/ApiaryClient( 6699):   "code": 401,
W/ApiaryClient( 6699):   "message": "Login Required"
W/ApiaryClient( 6699):  }
W/ApiaryClient( 6699): }
W/ApiaryClient( 6699): errCount = 2: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6699): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=403983735489463737&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6699): Headers:
W/ApiaryClient( 6699): accept-encoding: [gzip]
W/ApiaryClient( 6699): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6699): gdata-version: 2
,D/LgeQuickCoverNLService( 1396): onNotificationPosted
D/SmartCoverUpdateMonitor( 1396): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1396): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1396): handleNotificationPosted(true)
D/QuickCircle( 1396): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1396): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1396): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1396): post do just update job
D/LgeQuickCoverNotificationData( 1396): showAll3
D/LgeQuickCoverNotificationData( 1396): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1396): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1396): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1396): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1396): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1396): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1396): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1396): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1396): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1396): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1396): updateNotificationData: count=3
D/QuickStatusbarLayout( 1396): Notification difference=198
D/QuickStatusbarLayout( 1396): child = android.widget.LinearLayout{b7d9e1f V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1598012902] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1598012899] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,V/GLSActivity( 2112): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2112): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2112): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2112): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 2112): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2112): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1031): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1031): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1031): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1031): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1031): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1396): onNotificationPosted
,D/SmartCoverUpdateMonitor( 1396): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1396): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1396): handleNotificationPosted(true)
D/QuickCircle( 1396): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1396): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1396): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1396): post do just update job
D/LgeQuickCoverNotificationData( 1396): showAll3
D/LgeQuickCoverNotificationData( 1396): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1396): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1396): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1396): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1396): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1396): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1396): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1396): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1396): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1396): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1396): updateNotificationData: count=3
W/GLSActivity( 2112): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2112): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2112): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2112): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2112): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2112): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2112): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 6699): Authentication error
E/BooksAccountManager( 6699): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6699): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6699): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6699): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6699): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6699): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6699): null auth token
D/QuickStatusbarLayout( 1396): Notification difference=198
D/QuickStatusbarLayout( 1396): child = android.widget.LinearLayout{b7d9e1f V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
W/ApiaryClient( 6699): Error response from books API: {
W/ApiaryClient( 6699):  "error": {
W/ApiaryClient( 6699):   "errors": [
W/ApiaryClient( 6699):    {
W/ApiaryClient( 6699):     "domain": "global",
W/ApiaryClient( 6699):     "reason": "required",
W/ApiaryClient( 6699):     "message": "Login Required",
W/ApiaryClient( 6699):     "locationType": "header",
W/ApiaryClient( 6699):     "location": "Authorization"
W/ApiaryClient( 6699):    }
W/ApiaryClient( 6699):   ],
W/ApiaryClient( 6699):   "code": 401,
W/ApiaryClient( 6699):   "message": "Login Required"
W/ApiaryClient( 6699):  }
W/ApiaryClient( 6699): }
,W/ApiaryClient( 6699): errCount = 3: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6699): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=403983735489463737&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6699): Headers:
W/ApiaryClient( 6699): accept-encoding: [gzip]
W/ApiaryClient( 6699): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6699): gdata-version: 2
E/BooksSync( 6699): Soft error: 
E/BooksSync( 6699): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 6699): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=403983735489463737&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 6699): Headers:
E/BooksSync( 6699): accept-encoding: [gzip]
E/BooksSync( 6699): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 6699): gdata-version: 2
E/BooksSync( 6699): 
E/BooksSync( 6699): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 6699): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 6699): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 6699): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 6699): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 6699): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 6699): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 6699): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 6699): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 6699): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 6699): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 6699): {
E/BooksSync( 6699):  "error": {
E/BooksSync( 6699):   "errors": [
E/BooksSync( 6699):    {
E/BooksSync( 6699):     "domain": "global",
E/BooksSync( 6699):     "reason": "required",
E/BooksSync( 6699):     "message": "Login Required",
E/BooksSync( 6699):     "locationType": "header",
E/BooksSync( 6699):     "location": "Authorization"
E/BooksSync( 6699):    }
E/BooksSync( 6699):   ],
E/BooksSync( 6699):   "code": 401,
E/BooksSync( 6699):   "message": "Login Required"
E/BooksSync( 6699):  }
E/BooksSync( 6699): }
E/BooksSync( 6699): 
E/BooksSync( 6699): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 6699): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 6699): 	... 8 more
,E/BooksSync( 6699): Sync error
E/BooksSync( 6699): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 6699): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=403983735489463737&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 6699): Headers:
E/BooksSync( 6699): accept-encoding: [gzip]
E/BooksSync( 6699): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 6699): gdata-version: 2
E/BooksSync( 6699): 
E/BooksSync( 6699): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 6699): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 6699): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 6699): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 6699): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 6699): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 6699): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 6699): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 6699): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 6699): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 6699): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 6699): {
E/BooksSync( 6699):  "error": {
E/BooksSync( 6699):   "errors": [
E/BooksSync( 6699):    {
E/BooksSync( 6699):     "domain": "global",
E/BooksSync( 6699):     "reason": "required",
E/BooksSync( 6699):     "message": "Login Required",
E/BooksSync( 6699):     "locationType": "header",
E/BooksSync( 6699):     "location": "Authorization"
E/BooksSync( 6699):    }
E/BooksSync( 6699):   ],
E/BooksSync( 6699):   "code": 401,
E/BooksSync( 6699):   "message": "Login Required"
E/BooksSync( 6699):  }
E/BooksSync( 6699): }
E/BooksSync( 6699): 
E/BooksSync( 6699): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 6699): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 6699): 	... 8 more
I/BooksSync( 6699): Finished books sync
D/SyncManager( 1031): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 701862, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=6.3, 0.0, 0.0  rx=6.3 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:-1598009880] gl rssi=-45 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=6.3, 0.0, 0.0  rx=6.3 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1598009877] gl rssi=-45 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=4.2, 0.0, 0.0  rx=4.2 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1598006846] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=4.2, 0.0, 0.0  rx=4.2 bcn=0 [on:0 tx:0 rx:0 period:12] from screen [on:0 period:-1598006834] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
I/[SystemUI]TimeTickManager( 1447): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1447): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1447): called onTimeUpdated()
I/[SystemUI]Clock( 1447): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1447): called onTimeUpdated()
I/[SystemUI]DateView( 1447): called onTimeUpdated()
I/[SystemUI]DateView( 1447): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1447): handleTimeUpdate
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=2.6, 0.0, 0.0  rx=2.6 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1598003813] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=2.6, 0.0, 0.0  rx=2.6 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1598003810] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=1.3, 0.0, 0.0  rx=1.3 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1598000782] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=1.3, 0.0, 0.0  rx=1.3 bcn=0 [on:0 tx:0 rx:0 period:4] from screen [on:0 period:-1598000778] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,D/sensors_hal_Time( 1031): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1031): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1031): tsOffsetIs: Apps: 717591044887; DSPS: 23654785; Offset : -4307704587
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=1.1, 0.0, 0.0  rx=1.1 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1597997752] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=1.1, 0.0, 0.0  rx=1.1 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1597997749] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=1.1, 0.0, 0.0  rx=1.1 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1597994730] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=1.1, 0.0, 0.0  rx=1.1 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1597994727] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.5 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1597991700] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.5 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1597991697] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1597988669] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1597988666] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1597985637] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:11] from screen [on:0 period:-1597985626] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
D/PowerManagerServiceEx( 1031): acquireWakeLockInternal: lock=257990054, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1031
,V/AlarmManager( 1031): ELAPSED_WAKEUP set : Alarm{2c81b10d type 2 when 731955 android} when 731955
D/[Concierge]Service( 2603): onStartCommand(). Type : 9
,D/PowerManagerServiceEx( 1031): releaseWakeLockInternal: lock=257990054 [*alarm*], flags=0x0
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=1.2, 0.0, 0.0  rx=1.2 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1597982605] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=1.2, 0.0, 0.0  rx=1.2 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-1597982595] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
D/sensors_hal_Time( 1031): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1031): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1031): tsOffsetIs: Apps: 737593038265; DSPS: 24310210; Offset : -4307694643
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=1.1, 0.0, 0.0  rx=1.1 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:-1597979580] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=1.1, 0.0, 0.0  rx=1.1 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1597979577] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.5 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1597976551] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.5 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1597976548] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1597973524] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1597973521] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1597970493] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1597970490] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1597967463] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1597967460] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1597964443] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1597964440] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1597961413] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1597961410] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,D/sensors_hal_Time( 1031): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1031): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1031): tsOffsetIs: Apps: 757595562215; DSPS: 24965653; Offset : -4307703886
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1597958382] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1597958379] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1597955352] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1597955349] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3000] from screen [on:0 period:-1597952327] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:11] from screen [on:0 period:-1597952316] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1597949303] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1597949300] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1597946273] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:4] from screen [on:0 period:-1597946269] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,I/[SystemUI]TimeTickManager( 1447): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1447): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1447): called onTimeUpdated()
I/[SystemUI]Clock( 1447): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1447): called onTimeUpdated()
I/[SystemUI]DateView( 1447): called onTimeUpdated()
I/[SystemUI]DateView( 1447): called onTimeUpdated()
,D/KeyguardUpdateMonitor( 1447): handleTimeUpdate,
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1597943243] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1597943240] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1597940212] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1597940209] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,D/sensors_hal_Time( 1031): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1031): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1031): tsOffsetIs: Apps: 777597751113; DSPS: 25621084; Offset : -4307681398
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1597937185] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1597937182] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1597934159] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1597934156] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3000] from screen [on:0 period:-1597931129] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1597931126] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1597928099] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1597928096] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1597925070] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1597925067] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1597922043] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1597922040] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,D/sensors_hal_Time( 1031): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1031): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1031): tsOffsetIs: Apps: 797599858918; DSPS: 26276513; Offset : -4307679697
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1597919018] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:9] from screen [on:0 period:-1597919009] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1597915988] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:11] from screen [on:0 period:-1597915977] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1597912956] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:11] from screen [on:0 period:-1597912945] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1597909924] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1597909921] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1597906894] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1597906891] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:2998] from screen [on:0 period:-1597903864] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1597903861] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1597900836] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:11] from screen [on:0 period:-1597900825] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
D/sensors_hal_Time( 1031): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1031): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1031): tsOffsetIs: Apps: 817603693025; DSPS: 26931999; Offset : -4307690726
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1597897805] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1597897802] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1597894775] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:4] from screen [on:0 period:-1597894771] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1597891746] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:11] from screen [on:0 period:-1597891735] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1597888716] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-1597888706] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
I/[SystemUI]TimeTickManager( 1447): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1447): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1447): called onTimeUpdated()
I/[SystemUI]Clock( 1447): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1447): called onTimeUpdated()
I/[SystemUI]DateView( 1447): called onTimeUpdated()
I/[SystemUI]DateView( 1447): called onTimeUpdated()
,D/KeyguardUpdateMonitor( 1447): handleTimeUpdate
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1597885683] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1597885680] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1597882655] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1597882652] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,D/sensors_hal_Time( 1031): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1031): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1031): tsOffsetIs: Apps: 837605857913; DSPS: 27587430; Offset : -4307692533
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1597879626] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-1597879616] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1597876596] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:11] from screen [on:0 period:-1597876585] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1597873564] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1597873561] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1597870534] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1597870531] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1597867504] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1597867501] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1597864473] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1597864470] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1597861443] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1597861440] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,D/sensors_hal_Time( 1031): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1031): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1031): tsOffsetIs: Apps: 857607993010; DSPS: 28242860; Offset : -4307693823
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1597858412] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1597858409] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1597855383] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1597855380] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1597852353] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1597852350] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1597849323] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1597849320] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1597846292] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1597846289] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1597843268] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:9] from screen [on:0 period:-1597843259] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1597840239] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:11] from screen [on:0 period:-1597840228] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
D/sensors_hal_Time( 1031): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1031): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1031): tsOffsetIs: Apps: 877610745919; DSPS: 28898310; Offset : -4307687262
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1597837206] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:9] from screen [on:0 period:-1597837197] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1597834175] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1597834172] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1597831145] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1597831142] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1597828116] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-1597828106] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
I/[SystemUI]TimeTickManager( 1447): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1447): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1447): called onTimeUpdated()
I/[SystemUI]Clock( 1447): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1447): called onTimeUpdated()
I/[SystemUI]DateView( 1447): called onTimeUpdated()
I/[SystemUI]DateView( 1447): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1447): handleTimeUpdate
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1597825087] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:12] from screen [on:0 period:-1597825075] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1597822054] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1597822051] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,D/sensors_hal_Time( 1031): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1031): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1031): tsOffsetIs: Apps: 897612834401; DSPS: 29553738; Offset : -4307674027
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1597819025] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1597819022] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1597815997] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-1597815987] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1597812964] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1597812961] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1597809933] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1597809930] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1597806902] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1597806899] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1597803877] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-1597803867] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1597800846] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:11] from screen [on:0 period:-1597800835] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
D/sensors_hal_Time( 1031): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1031): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1031): tsOffsetIs: Apps: 917614957883; DSPS: 30209168; Offset : -4307686829
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1597797813] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1597797810] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1597794784] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1597794781] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1597791755] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1597791752] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1597788727] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:11] from screen [on:0 period:-1597788716] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1597785693] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1597785690] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1597782663] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1597782660] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,D/sensors_hal_Time( 1031): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1031): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1031): tsOffsetIs: Apps: 937616900011; DSPS: 30864592; Offset : -4307697799
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1597779635] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1597779632] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1597776606] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1597776603] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1597773578] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-1597773568] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1597770548] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:11] from screen [on:0 period:-1597770537] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=1.8, 0.0, 0.0  rx=2.3 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1597767517] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=1.8, 0.0, 0.0  rx=2.3 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-1597767507] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
I/[SystemUI]TimeTickManager( 1447): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1447): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1447): called onTimeUpdated()
I/[SystemUI]Clock( 1447): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1447): called onTimeUpdated()
I/[SystemUI]DateView( 1447): called onTimeUpdated()
I/[SystemUI]DateView( 1447): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1447): handleTimeUpdate
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.9, 0.0, 0.0  rx=1.2 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1597764484] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.9, 0.0, 0.0  rx=1.2 bcn=0 [on:0 tx:0 rx:0 period:4] from screen [on:0 period:-1597764480] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=1.0, 0.0, 0.0  rx=1.1 bcn=0 [on:0 tx:0 rx:0 period:3005] from screen [on:0 period:-1597761453] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=1.0, 0.0, 0.0  rx=1.1 bcn=0 [on:0 tx:0 rx:0 period:9] from screen [on:0 period:-1597761444] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,D/sensors_hal_Time( 1031): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1031): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1031): tsOffsetIs: Apps: 957619040316; DSPS: 31520022; Offset : -4307693750
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.5 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1597758433] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.5 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1597758430] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1597755403] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1597755400] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.9, 0.0, 0.0  rx=0.9 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1597752377] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.9, 0.0, 0.0  rx=0.9 bcn=0 [on:0 tx:0 rx:0 period:19] from screen [on:0 period:-1597752358] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1597749339] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1597749336] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1597746309] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:11] from screen [on:0 period:-1597746298] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.9, 0.0, 0.0  rx=0.9 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1597743286] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.9, 0.0, 0.0  rx=0.9 bcn=0 [on:0 tx:0 rx:0 period:11] from screen [on:0 period:-1597743275] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:-1597740252] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1597740249] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,D/sensors_hal_Time( 1031): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1031): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1031): tsOffsetIs: Apps: 977621052131; DSPS: 32175448; Offset : -4307695965
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1597737228] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:9] from screen [on:0 period:-1597737219] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1597734202] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:4] from screen [on:0 period:-1597734198] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1597731173] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1597731170] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1597728152] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1597728149] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1597725123] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1597725120] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1597722094] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1597722091] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,D/sensors_hal_Time( 1031): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1031): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1031): tsOffsetIs: Apps: 997623042332; DSPS: 32830873; Offset : -4307689589
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1597719066] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-1597719056] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1597716036] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:12] from screen [on:0 period:-1597716024] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1597713010] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:4] from screen [on:0 period:-1597713006] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1597709979] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1597709976] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1597706945] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1597706942] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,I/[SystemUI]TimeTickManager( 1447): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1447): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1447): called onTimeUpdated()
I/[SystemUI]Clock( 1447): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1447): called onTimeUpdated(),
I/[SystemUI]DateView( 1447): called onTimeUpdated()
I/[SystemUI]DateView( 1447): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1447): handleTimeUpdate
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1597703916] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:13] from screen [on:0 period:-1597703903] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1597700882] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1597700879] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,D/sensors_hal_Time( 1031): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1031): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1031): tsOffsetIs: Apps: 1017625158470; DSPS: 33486302; Offset : -4307678930
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1597697860] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1597697857] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1597694831] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1597694828] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1597691805] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1597691802] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1597688776] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-1597688766] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1597685743] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1597685740] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1597682721] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1597682718] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,D/sensors_hal_Time( 1031): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1031): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1031): tsOffsetIs: Apps: 1037627332577; DSPS: 34141734; Offset : -4307702219
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1597679692] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1597679689] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1597676662] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1597676659] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1597673634] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:4] from screen [on:0 period:-1597673630] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1597670602] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1597670599] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1597667582] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1597667579] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3000] from screen [on:0 period:-1597664555] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-1597664554] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1597661538] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:9] from screen [on:0 period:-1597661529] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
D/sensors_hal_Time( 1031): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1031): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1031): tsOffsetIs: Apps: 1057629492100; DSPS: 34797164; Offset : -4307679057
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1597658508] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:9] from screen [on:0 period:-1597658499] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1597655478] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:9] from screen [on:0 period:-1597655469] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1597652457] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-1597652447] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
D/PowerManagerServiceEx( 1031): acquireWakeLockInternal: lock=257990054, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1031
,V/AlarmManager( 1031): ELAPSED_WAKEUP set : Alarm{343888c2 type 2 when 1066394 com.android.bluetooth} when 1066394
,W/bt-smp  ( 6290): Key(LSB ~ MSB) = 0a 3c a6 fe eb 17 6a 79 a6 1f 0a 0b f9 50 a0 5f 
W/bt-smp  ( 6290): Plain text(LSB ~ MSB) = a5 b6 4f 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 6290): Encrypted text(LSB ~ MSB) = 75 3b 1c b0 86 5d 5a 4a 08 4c 5a 6f d8 44 8f f8 
W/bt-btm  ( 6290): Stopping oneshot timer
D/[Concierge]Service( 2603): onStartCommand(). Type : 9
,D/PowerManagerServiceEx( 1031): releaseWakeLockInternal: lock=257990054 [*alarm*], flags=0x0
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1597649426] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:11] from screen [on:0 period:-1597649415] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1597646393] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:4] from screen [on:0 period:-1597646389] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,I/[SystemUI]TimeTickManager( 1447): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1447): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1447): called onTimeUpdated()
I/[SystemUI]Clock( 1447): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1447): called onTimeUpdated()
I/[SystemUI]DateView( 1447): called onTimeUpdated()
I/[SystemUI]DateView( 1447): called onTimeUpdated()
,D/KeyguardUpdateMonitor( 1447): handleTimeUpdate
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:2999] from screen [on:0 period:-1597643365] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1597643362] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1597640332] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1597640329] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,D/sensors_hal_Time( 1031): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1031): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1031): tsOffsetIs: Apps: 1077631469906; DSPS: 35452589; Offset : -4307684763
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3005] from screen [on:0 period:-1597637309] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1597637306] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1597634283] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1597634280] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1597631252] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1597631249] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1597628222] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1597628219] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1597625195] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1597625192] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1597622174] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1597622171] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,D/sensors_hal_Time( 1031): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1031): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1031): tsOffsetIs: Apps: 1097633632814; DSPS: 36108020; Offset : -4307688733
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3000] from screen [on:0 period:-1597619148] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:9] from screen [on:0 period:-1597619139] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1597616118] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:9] from screen [on:0 period:-1597616109] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3000] from screen [on:0 period:-1597613089] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-1597613079] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1597610060] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1597610057] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,D/PowerManagerServiceEx( 1031): acquireWakeLockInternal: lock=257990054, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1031
,V/AlarmManager( 1031): ELAPSED_WAKEUP set : Alarm{3dc986d3 type 2 when 1073606 com.google.android.gms} when 1073606
D/[Concierge]Service( 2603): onStartCommand(). Type : 9
,D/GCM     ( 2112): Message class com.google.f.a.a.i
,D/PowerManagerServiceEx( 1031): releaseWakeLockInternal: lock=257990054 [*alarm*], flags=0x0
,I/GCM     ( 2350): Message from null null
E/GCM     ( 2350): Dropping message from null
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1597607030] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1597607027] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=1.4, 0.0, 0.0  rx=1.4 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1597604001] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=1.4, 0.0, 0.0  rx=1.4 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1597603998] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=1.2, 0.0, 0.0  rx=1.2 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1597600972] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=1.2, 0.0, 0.0  rx=1.2 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1597600969] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,D/sensors_hal_Time( 1031): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1031): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1031): tsOffsetIs: Apps: 1117635808484; DSPS: 36763451; Offset : -4307679603
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.6, 0.0, 0.0  rx=0.6 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1597597942] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.6, 0.0, 0.0  rx=0.6 bcn=0 [on:0 tx:0 rx:0 period:4] from screen [on:0 period:-1597597938] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1597594912] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1597594909] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.9, 0.0, 0.0  rx=0.9 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1597591887] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.9, 0.0, 0.0  rx=0.9 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-1597591877] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.5 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1597588857] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.5 bcn=0 [on:0 tx:0 rx:0 period:11] from screen [on:0 period:-1597588846] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
I/[SystemUI]TimeTickManager( 1447): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1447): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1447): called onTimeUpdated()
I/[SystemUI]Clock( 1447): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1447): called onTimeUpdated()
I/[SystemUI]DateView( 1447): called onTimeUpdated()
I/[SystemUI]DateView( 1447): called onTimeUpdated()
,D/KeyguardUpdateMonitor( 1447): handleTimeUpdate
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1597585825] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1597585822] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1597582795] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1597582792] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1597579766] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:11] from screen [on:0 period:-1597579755] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
D/sensors_hal_Time( 1031): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1031): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1031): tsOffsetIs: Apps: 1137637867122; DSPS: 37418879; Offset : -4307696265
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1597576734] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1597576731] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1597573705] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:4] from screen [on:0 period:-1597573701] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1597570676] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:11] from screen [on:0 period:-1597570665] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1597567644] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1597567641] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1597564612] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1597564609] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1597561582] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1597561579] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,D/sensors_hal_Time( 1031): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1031): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1031): tsOffsetIs: Apps: 1157640674094; DSPS: 38074331; Offset : -4307696779
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1597558554] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:4] from screen [on:0 period:-1597558550] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1597555524] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1597555521] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3000] from screen [on:0 period:-1597552497] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:11] from screen [on:0 period:-1597552486] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1597549465] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:4] from screen [on:0 period:-1597549461] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1597546434] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1597546431] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1597543405] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1597543402] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1597540373] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1597540370] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,D/sensors_hal_Time( 1031): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1031): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1031): tsOffsetIs: Apps: 1177642213201; DSPS: 38729741; Offset : -4307683759
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1597537345] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:4] from screen [on:0 period:-1597537341] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1597534317] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:11] from screen [on:0 period:-1597534306] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1597531285] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1597531282] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1597528254] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1597528251] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,I/[SystemUI]TimeTickManager( 1447): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1447): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1447): called onTimeUpdated()
I/[SystemUI]Clock( 1447): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1447): called onTimeUpdated()
,I/[SystemUI]DateView( 1447): called onTimeUpdated()
I/[SystemUI]DateView( 1447): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1447): handleTimeUpdate
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1597525227] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-1597525217] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1597522195] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1597522192] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,D/sensors_hal_Time( 1031): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1031): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1031): tsOffsetIs: Apps: 1197644512672; DSPS: 39385176; Offset : -4307673054
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1597519164] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1597519161] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1597516134] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1597516131] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1597513104] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1597513101] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1597510076] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-1597510066] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1597507043] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-1597507033] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1597504018] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:11] from screen [on:0 period:-1597504007] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1597500987] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-1597500977] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
D/sensors_hal_Time( 1031): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1031): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1031): tsOffsetIs: Apps: 1217645901206; DSPS: 40040582; Offset : -4307688304
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1597497956] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:8] from screen [on:0 period:-1597497948] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
I/UsageStatsService( 1031): User[0] Flushing usage stats to disk
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1597494926] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:11] from screen [on:0 period:-1597494915] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1597491894] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1597491891] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1597488864] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1597488861] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,D/PowerManagerServiceEx( 1031): acquireWakeLockInternal: lock=257990054, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1031
,V/AlarmManager( 1031): ELAPSED_WAKEUP set : Alarm{1e255109 type 2 when 1229558 android} when 1229558
D/[Concierge]Service( 2603): onStartCommand(). Type : 9
,D/PowerManagerServiceEx( 1031): releaseWakeLockInternal: lock=257990054 [*alarm*], flags=0x0
,I/BooksSync( 6699): Starting books sync
,D/BooksSync( 6699): started syncMyEbooks
V/GLSActivity( 2112): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2112): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2112): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2112): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2112): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2112): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1031): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1031): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1031): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1031): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1031): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1396): onNotificationPosted
D/SmartCoverUpdateMonitor( 1396): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1396): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1396): handleNotificationPosted(true)
D/QuickCircle( 1396): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1396): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1396): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1396): post do just update job
D/LgeQuickCoverNotificationData( 1396): showAll3
D/LgeQuickCoverNotificationData( 1396): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1396): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1396): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1396): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1396): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1396): isNotificationForCurrentUser : true
,D/LgeQuickCoverOverlayWindow( 1396): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1396): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1396): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1396): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1396): updateNotificationData: count=3
W/GLSActivity( 2112): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2112): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2112): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2112): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2112): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2112): 	,at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2112): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 6699): Authentication error
E/BooksAccountManager( 6699): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6699): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6699): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6699): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6699): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6699): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6699): null auth token
D/libc-netbsd(  313): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  313): res_queryN name = www.googleapis.com, class = 1, type = 1
D/QuickStatusbarLayout( 1396): Notification difference=198
D/QuickStatusbarLayout( 1396): child = android.widget.LinearLayout{b7d9e1f V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,D/libc-netbsd(  313): res_queryN name = www.googleapis.com succeed
,W/ApiaryClient( 6699): Error response from books API: {
W/ApiaryClient( 6699):  "error": {
W/ApiaryClient( 6699):   "errors": [
W/ApiaryClient( 6699):    {
W/ApiaryClient( 6699):     "domain": "global",
W/ApiaryClient( 6699):     "reason": "required",
W/ApiaryClient( 6699):     "message": "Login Required",
W/ApiaryClient( 6699):     "locationType": "header",
W/ApiaryClient( 6699):     "location": "Authorization"
W/ApiaryClient( 6699):    }
W/ApiaryClient( 6699):   ],
W/ApiaryClient( 6699):   "code": 401,
W/ApiaryClient( 6699):   "message": "Login Required"
W/ApiaryClient( 6699):  }
W/ApiaryClient( 6699): }
,W/ApiaryClient( 6699): errCount = 1: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6699): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-3757640433353672208&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6699): Headers:
W/ApiaryClient( 6699): accept-encoding: [gzip]
W/ApiaryClient( 6699): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6699): gdata-version: 2
V/GLSActivity( 2112): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2112): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2112): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2112): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2112): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2112): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1031): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1031): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1031): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1031): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1031): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1396): onNotificationPosted
,D/SmartCoverUpdateMonitor( 1396): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1396): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1396): handleNotificationPosted(true)
D/QuickCircle( 1396): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1396): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1396): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1396): post do just update job
D/LgeQuickCoverNotificationData( 1396): showAll3
D/LgeQuickCoverNotificationData( 1396): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1396): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1396): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1396): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1396): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1396): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1396): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1396): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1396): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1396): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1396): updateNotificationData: count=3
W/GLSActivity( 2112): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2112): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2112): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2112): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2112): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2112): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2112): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 6699): Authentication error
E/BooksAccountManager( 6699): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6699): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6699): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6699): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6699): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6699): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6699): null auth token
D/QuickStatusbarLayout( 1396): Notification difference=198
D/QuickStatusbarLayout( 1396): child = android.widget.LinearLayout{b7d9e1f V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,W/ApiaryClient( 6699): Error response from books API: {
W/ApiaryClient( 6699):  "error": {
W/ApiaryClient( 6699):   "errors": [
W/ApiaryClient( 6699):    {
W/ApiaryClient( 6699):     "domain": "global",
W/ApiaryClient( 6699):     "reason": "required",
W/ApiaryClient( 6699):     "message": "Login Required",
W/ApiaryClient( 6699):     "locationType": "header",
W/ApiaryClient( 6699):     "location": "Authorization"
W/ApiaryClient( 6699):    }
W/ApiaryClient( 6699):   ],
W/ApiaryClient( 6699):   "code": 401,
W/ApiaryClient( 6699):   "message": "Login Required"
W/ApiaryClient( 6699):  }
W/ApiaryClient( 6699): }
,W/ApiaryClient( 6699): errCount = 2: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6699): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-3757640433353672208&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6699): Headers:
W/ApiaryClient( 6699): accept-encoding: [gzip]
W/ApiaryClient( 6699): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6699): gdata-version: 2
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1597485834] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1597485831] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,V/GLSActivity( 2112): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2112): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2112): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2112): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 2112): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2112): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1031): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1031): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1031): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1031): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1031): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1396): onNotificationPosted
,D/SmartCoverUpdateMonitor( 1396): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1396): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1396): handleNotificationPosted(true)
D/QuickCircle( 1396): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1396): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1396): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1396): post do just update job
D/LgeQuickCoverNotificationData( 1396): showAll3
D/LgeQuickCoverNotificationData( 1396): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1396): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1396): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1396): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1396): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1396): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1396): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1396): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1396): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1396): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1396): updateNotificationData: count=3
W/GLSActivity( 2112): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2112): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2112): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2112): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2112): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2112): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2112): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 6699): Authentication error
E/BooksAccountManager( 6699): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6699): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6699): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6699): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6699): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6699): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6699): null auth token
D/QuickStatusbarLayout( 1396): Notification difference=198
D/QuickStatusbarLayout( 1396): child = android.widget.LinearLayout{b7d9e1f V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,W/ApiaryClient( 6699): Error response from books API: {
W/ApiaryClient( 6699):  "error": {
W/ApiaryClient( 6699):   "errors": [
W/ApiaryClient( 6699):    {
W/ApiaryClient( 6699):     "domain": "global",
W/ApiaryClient( 6699):     "reason": "required",
W/ApiaryClient( 6699):     "message": "Login Required",
W/ApiaryClient( 6699):     "locationType": "header",
W/ApiaryClient( 6699):     "location": "Authorization"
W/ApiaryClient( 6699):    }
W/ApiaryClient( 6699):   ],
W/ApiaryClient( 6699):   "code": 401,
W/ApiaryClient( 6699):   "message": "Login Required"
W/ApiaryClient( 6699):  }
W/ApiaryClient( 6699): }
,W/ApiaryClient( 6699): errCount = 3: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6699): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-3757640433353672208&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6699): Headers:
W/ApiaryClient( 6699): accept-encoding: [gzip]
W/ApiaryClient( 6699): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6699): gdata-version: 2
E/BooksSync( 6699): Soft error: 
E/BooksSync( 6699): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 6699): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-3757640433353672208&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 6699): Headers:
E/BooksSync( 6699): accept-encoding: [gzip]
E/BooksSync( 6699): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 6699): gdata-version: 2
E/BooksSync( 6699): 
E/BooksSync( 6699): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 6699): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 6699): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 6699): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 6699): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 6699): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 6699): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 6699): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 6699): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 6699): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 6699): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 6699): {
E/BooksSync( 6699):  "error": {
E/BooksSync( 6699):   "errors": [
E/BooksSync( 6699):    {
E/BooksSync( 6699):     "domain": "global",
E/BooksSync( 6699):     "reason": "required",
E/BooksSync( 6699):     "message": "Login Required",
E/BooksSync( 6699):     "locationType": "header",
E/BooksSync( 6699):     "location": "Authorization"
E/BooksSync( 6699):    }
E/BooksSync( 6699):   ],
E/BooksSync( 6699):   "code": 401,
E/BooksSync( 6699):   "message": "Login Required"
E/BooksSync( 6699):  }
E/BooksSync( 6699): }
E/BooksSync( 6699): 
E/BooksSync( 6699): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 6699): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 6699): 	... 8 more
,E/BooksSync( 6699): Sync error
E/BooksSync( 6699): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 6699): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-3757640433353672208&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 6699): Headers:
E/BooksSync( 6699): accept-encoding: [gzip]
E/BooksSync( 6699): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 6699): gdata-version: 2
E/BooksSync( 6699): 
E/BooksSync( 6699): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 6699): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 6699): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 6699): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 6699): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 6699): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 6699): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 6699): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 6699): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 6699): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 6699): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 6699): {
E/BooksSync( 6699):  "error": {
E/BooksSync( 6699):   "errors": [
E/BooksSync( 6699):    {
E/BooksSync( 6699):     "domain": "global",
E/BooksSync( 6699):     "reason": "required",
E/BooksSync( 6699):     "message": "Login Required",
E/BooksSync( 6699):     "locationType": "header",
E/BooksSync( 6699):     "location": "Authorization"
E/BooksSync( 6699):    }
E/BooksSync( 6699):   ],
E/BooksSync( 6699):   "code": 401,
E/BooksSync( 6699):   "message": "Login Required"
E/BooksSync( 6699):  }
E/BooksSync( 6699): }
E/BooksSync( 6699): 
E/BooksSync( 6699): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 6699): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 6699): 	... 8 more
I/BooksSync( 6699): Finished books sync
D/SyncManager( 1031): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 1229558, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=7.9, 0.0, 0.0  rx=5.4 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1597482813] gl rssi=-45 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=7.9, 0.0, 0.0  rx=5.4 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1597482810] gl rssi=-45 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=6.0, 0.0, 0.0  rx=4.2 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1597479783] gl rssi=-45 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=6.0, 0.0, 0.0  rx=4.2 bcn=0 [on:0 tx:0 rx:0 period:12] from screen [on:0 period:-1597479771] gl rssi=-45 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
D/sensors_hal_Time( 1031): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1031): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1031): tsOffsetIs: Apps: 1237647504636; DSPS: 40695995; Offset : -4307702149
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=3.5, 0.0, 0.0  rx=2.1 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1597476750] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=3.5, 0.0, 0.0  rx=2.1 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1597476747] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=2.2, 0.0, 0.0  rx=1.6 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1597473719] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=2.2, 0.0, 0.0  rx=1.6 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1597473716] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=1.6, 0.0, 0.0  rx=1.3 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1597470689] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=1.6, 0.0, 0.0  rx=1.3 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1597470686] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=1.3, 0.0, 0.0  rx=0.6 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1597467659] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=1.3, 0.0, 0.0  rx=0.6 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1597467656] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
I/[SystemUI]TimeTickManager( 1447): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1447): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1447): called onTimeUpdated()
I/[SystemUI]Clock( 1447): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1447): called onTimeUpdated()
,I/[SystemUI]DateView( 1447): called onTimeUpdated()
,I/[SystemUI]DateView( 1447): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1447): handleTimeUpdate
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=1.2, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1597464627] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=1.2, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:11] from screen [on:0 period:-1597464616] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.6, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1597461595] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.6, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:11] from screen [on:0 period:-1597461584] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
D/sensors_hal_Time( 1031): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1031): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1031): tsOffsetIs: Apps: 1257649640722; DSPS: 41351425; Offset : -4307702631
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1597458563] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1597458560] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,D/PowerManagerServiceEx( 1031): acquireWakeLockInternal: lock=257990054, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1031
,V/AlarmManager( 1031): ELAPSED_WAKEUP set : Alarm{1e9efd2b type 2 when 1259783 android} when 1259783
D/[Concierge]Service( 2603): onStartCommand(). Type : 9
,D/PowerManagerServiceEx( 1031): releaseWakeLockInternal: lock=257990054 [*alarm*], flags=0x0
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=1.4, 0.0, 0.0  rx=0.9 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1597455533] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=1.4, 0.0, 0.0  rx=0.9 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1597455530] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1597452503] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1597452500] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3006] from screen [on:0 period:-1597449481] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1597449478] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.9, 0.0, 0.0  rx=0.9 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:-1597446455] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.9, 0.0, 0.0  rx=0.9 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1597446452] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1597443426] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-1597443416] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1597440394] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1597440391] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,D/sensors_hal_Time( 1031): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1031): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1031): tsOffsetIs: Apps: 1277651610766; DSPS: 42006849; Offset : -4307685478
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1597437364] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1597437361] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3000] from screen [on:0 period:-1597434336] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1597434333] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1597431319] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1597431316] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1597428288] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:11] from screen [on:0 period:-1597428277] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=1.2, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1597425256] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=1.2, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:11] from screen [on:0 period:-1597425245] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.6, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1597422224] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.6, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1597422221] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,D/sensors_hal_Time( 1031): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1031): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1031): tsOffsetIs: Apps: 1297653427790; DSPS: 42662269; Offset : -4307699483
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1597419194] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1597419191] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.9, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1597416173] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.9, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1597416170] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1597413143] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1597413140] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1597410116] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:4] from screen [on:0 period:-1597410112] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1597407087] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-1597407077] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
I/[SystemUI]TimeTickManager( 1447): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1447): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1447): called onTimeUpdated()
I/[SystemUI]Clock( 1447): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1447): called onTimeUpdated()
I/[SystemUI]DateView( 1447): called onTimeUpdated()
I/[SystemUI]DateView( 1447): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1447): handleTimeUpdate
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1597404057] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:13] from screen [on:0 period:-1597404044] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1597401031] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1597401028] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,D/sensors_hal_Time( 1031): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1031): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1031): tsOffsetIs: Apps: 1317655301376; DSPS: 43317690; Offset : -4307687495
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1597398001] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1597397998] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1597394972] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1597394969] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1597391943] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1597391940] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1597388912] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1597388909] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,I/[SystemUI]LGPowerUI( 1447): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1447): On Skip Timer : true
,D/LEDHandler( 1945): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1945): Battery Level Remaining: 100%
D/LEDHandler( 1945): Battery Temp: 278, mChargingStatus=5, mChargingStop=false
,D/KeyguardUpdateMonitor( 1447): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 278
I/[SystemUI]LGPowerUI( 1447): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]BatterySaverHandler( 1447): onReceive = android.intent.action.BATTERY_CHANGED
D/WifiController( 1031): battery changed pluggedType: 2
W/Settings( 1031): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1031): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/HeadsetStateMachine( 6290): Disconnected process message: 10, size: 0
D/LGDMClient( 3941): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.intent.action.BATTERY_CHANGED
D/LGDMClient( 3941): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1597385892] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:4] from screen [on:0 period:-1597385888] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1597382872] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1597382869] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1597379842] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1597379839] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,D/sensors_hal_Time( 1031): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1031): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1031): tsOffsetIs: Apps: 1337657304025; DSPS: 43973116; Offset : -4307699136
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1597376812] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1597376809] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1597373783] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1597373780] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1597370762] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1597370759] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1597367734] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1597367731] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1597364705] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1597364702] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1597361675] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1597361672] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,D/sensors_hal_Time( 1031): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1031): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1031): tsOffsetIs: Apps: 1357659629902; DSPS: 44628552; Offset : -4307692543
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1597358646] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:14] from screen [on:0 period:-1597358632] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1597355619] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-1597355609] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1597352588] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:35] from screen [on:0 period:-1597352553] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:-1597349534] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1597349531] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1597346503] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1597346500] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,I/[SystemUI]TimeTickManager( 1447): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1447): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1447): called onTimeUpdated()
I/[SystemUI]Clock( 1447): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1447): called onTimeUpdated()
,I/[SystemUI]DateView( 1447): called onTimeUpdated()
I/[SystemUI]DateView( 1447): called onTimeUpdated()
,D/KeyguardUpdateMonitor( 1447): handleTimeUpdate
D/PowerManagerServiceEx( 1031): acquireWakeLockInternal: lock=257990054, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1031
,D/[Concierge]Service( 2603): onStartCommand(). Type : 9
,I/DigitalAppWidgetProvider( 7750): onReceive: com.android.deskclock.ON_QUARTER_HOUR
,V/DigitalAppWidgetProvider( 7750): startAlarmOnQuarterHour android.app.ReceiverRestrictedContext@21cdf798
D/PowerManagerServiceEx( 1031): releaseWakeLockInternal: lock=257990054 [*alarm*], flags=0x0
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1597343474] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1597343471] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1597340453] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1597340450] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,D/sensors_hal_Time( 1031): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1031): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1031): tsOffsetIs: Apps: 1377662373072; DSPS: 45284002; Offset : -4307695799
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3000] from screen [on:0 period:-1597337425] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1597337422] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1597334396] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:15] from screen [on:0 period:-1597334381] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1597331363] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:4] from screen [on:0 period:-1597331359] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1597328336] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:11] from screen [on:0 period:-1597328325] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1597325288] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-1597325278] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1597322257] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-1597322247] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
D/sensors_hal_Time( 1031): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1031): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1031): tsOffsetIs: Apps: 1397664182284; DSPS: 45939421; Offset : -4307687254
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1597319225] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:4] from screen [on:0 period:-1597319221] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1597316197] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:12] from screen [on:0 period:-1597316185] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1597313163] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1597313160] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3000] from screen [on:0 period:-1597310134] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1597310131] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1597307106] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-1597307096] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1597304077] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-1597304067] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1597301045] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-1597301035] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
D/sensors_hal_Time( 1031): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1031): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1031): tsOffsetIs: Apps: 1417666477119; DSPS: 46594856; Offset : -4307681134
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1597298014] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1597298011] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1597294984] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1597294981] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1597291954] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1597291951] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1597288926] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:9] from screen [on:0 period:-1597288917] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
I/[SystemUI]TimeTickManager( 1447): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1447): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1447): called onTimeUpdated()
I/[SystemUI]Clock( 1447): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1447): called onTimeUpdated()
I/[SystemUI]DateView( 1447): called onTimeUpdated()
I/[SystemUI]DateView( 1447): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1447): handleTimeUpdate
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1597285894] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1597285891] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1597282865] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:4] from screen [on:0 period:-1597282861] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1597279837] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-1597279827] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
D/sensors_hal_Time( 1031): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1031): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1031): tsOffsetIs: Apps: 1437668499090; DSPS: 47250282; Offset : -4307673375
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1597276805] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1597276802] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1597273776] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:9] from screen [on:0 period:-1597273767] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1597270745] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:12] from screen [on:0 period:-1597270733] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1597267713] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1597267710] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1597264683] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1597264680] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1597261654] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1597261651] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,D/sensors_hal_Time( 1031): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1031): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1031): tsOffsetIs: Apps: 1457671258302; DSPS: 47905733; Offset : -4307691132
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1597258624] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1597258621] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1597255597] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:11] from screen [on:0 period:-1597255586] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1597252567] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:11] from screen [on:0 period:-1597252556] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1597249541] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1597249538] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1597246515] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:4] from screen [on:0 period:-1597246511] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1597243487] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:12] from screen [on:0 period:-1597243475] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=1.4, 0.0, 0.0  rx=1.9 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1597240454] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=1.4, 0.0, 0.0  rx=1.9 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1597240451] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,D/sensors_hal_Time( 1031): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1031): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1031): tsOffsetIs: Apps: 1477673512096; DSPS: 48561167; Offset : -4307695821
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=1.2, 0.0, 0.0  rx=1.4 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1597237426] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=1.2, 0.0, 0.0  rx=1.4 bcn=0 [on:0 tx:0 rx:0 period:11] from screen [on:0 period:-1597237415] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=1.1, 0.0, 0.0  rx=1.2 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1597234395] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=1.1, 0.0, 0.0  rx=1.2 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1597234392] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.6 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1597231365] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.6 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1597231362] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1597228335] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1597228332] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,I/[SystemUI]TimeTickManager( 1447): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1447): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1447): called onTimeUpdated()
I/[SystemUI]Clock( 1447): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1447): called onTimeUpdated()
I/[SystemUI]DateView( 1447): called onTimeUpdated()
I/[SystemUI]DateView( 1447): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1447): handleTimeUpdate
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1597225305] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1597225302] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1597222274] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1597222271] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,D/sensors_hal_Time( 1031): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1031): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1031): tsOffsetIs: Apps: 1497675701933; DSPS: 49216599; Offset : -4307703250
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.9 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1597219246] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.9 bcn=0 [on:0 tx:0 rx:0 period:9] from screen [on:0 period:-1597219237] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1597216216] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:11] from screen [on:0 period:-1597216205] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1597213185] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1597213182] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1597210157] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:11] from screen [on:0 period:-1597210146] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:-1597207122] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1597207119] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1597204081] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1597204078] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1597201051] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1597201048] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,D/sensors_hal_Time( 1031): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1031): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1031): tsOffsetIs: Apps: 1517677849789; DSPS: 49872029; Offset : -4307691572
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1597198022] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:4] from screen [on:0 period:-1597198018] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1597194991] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1597194988] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1597191963] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1597191960] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1597188931] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1597188928] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1597185902] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1597185899] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1597182872] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1597182869] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1597179843] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-1597179833] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
D/sensors_hal_Time( 1031): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1031): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1031): tsOffsetIs: Apps: 1537680121136; DSPS: 50527463; Offset : -4307678735
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1597176812] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:4] from screen [on:0 period:-1597176808] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3017] from screen [on:0 period:-1597173767] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-1597173757] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1597170736] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:11] from screen [on:0 period:-1597170725] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1597167704] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:4] from screen [on:0 period:-1597167700] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,I/[SystemUI]TimeTickManager( 1447): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1447): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1447): called onTimeUpdated()
I/[SystemUI]Clock( 1447): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1447): called onTimeUpdated()
I/[SystemUI]DateView( 1447): called onTimeUpdated()
I/[SystemUI]DateView( 1447): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1447): handleTimeUpdate
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3000] from screen [on:0 period:-1597164674] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1597164671] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3000] from screen [on:0 period:-1597161644] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1597161641] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,D/sensors_hal_Time( 1031): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1031): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1031): tsOffsetIs: Apps: 1557682296441; DSPS: 51182895; Offset : -4307700565
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3000] from screen [on:0 period:-1597158617] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-1597158607] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1597155586] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:11] from screen [on:0 period:-1597155575] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1597152553] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1597152550] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1597149510] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1597149507] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1597146480] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1597146477] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1597143451] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:4] from screen [on:0 period:-1597143447] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1597140420] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1597140417] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,D/sensors_hal_Time( 1031): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1031): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1031): tsOffsetIs: Apps: 1577684308100; DSPS: 51838321; Offset : -4307702858
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1597137390] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:2] from screen [on:0 period:-1597137388] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.9, 0.0, 0.0  rx=0.9 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:-1597134371] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.9, 0.0, 0.0  rx=0.9 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1597134368] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1597131342] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1597131339] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1597128315] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1597128312] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1597125285] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1597125282] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1597122255] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1597122252] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,D/sensors_hal_Time( 1031): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1031): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1031): tsOffsetIs: Apps: 1597685676790; DSPS: 52493725; Offset : -4307677227
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:-1597119232] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1597119229] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1597116203] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:7] from screen [on:0 period:-1597116196] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1597113174] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1597113171] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1597110145] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1597110142] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1597107113] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1597107110] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,I/[SystemUI]TimeTickManager( 1447): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1447): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1447): called onTimeUpdated()
I/[SystemUI]Clock( 1447): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1447): called onTimeUpdated()
,I/[SystemUI]DateView( 1447): called onTimeUpdated()
,I/[SystemUI]DateView( 1447): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1447): handleTimeUpdate
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1597104091] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1597104088] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1597101061] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1597101058] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,D/sensors_hal_Time( 1031): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1031): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1031): tsOffsetIs: Apps: 1617687839126; DSPS: 53149156; Offset : -4307681379
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1597098038] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:9] from screen [on:0 period:-1597098029] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1597095008] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-1597094998] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1597091975] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1597091972] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1597088952] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1597088949] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1597085922] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1597085919] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1597082892] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1597082889] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1597079864] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1597079861] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,D/sensors_hal_Time( 1031): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1031): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1031): tsOffsetIs: Apps: 1637689302087; DSPS: 53804564; Offset : -4307683549
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1597076834] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1597076831] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1597073813] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1597073810] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1597070784] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1597070781] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1597067755] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1597067752] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1597064725] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1597064722] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-46 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1597061696] gl rssi=-46 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-46 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-1597061686] gl rssi=-46 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
D/sensors_hal_Time( 1031): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1031): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1031): tsOffsetIs: Apps: 1657693541091; DSPS: 54460063; Offset : -4307686227
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1597058672] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1597058669] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1597055643] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1597055640] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1597052613] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1597052610] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-46 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1597049582] gl rssi=-46 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-46 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1597049579] gl rssi=-46 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-46 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1597046553] gl rssi=-46 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-46 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:4] from screen [on:0 period:-1597046549] gl rssi=-46 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,I/[SystemUI]TimeTickManager( 1447): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1447): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1447): called onTimeUpdated()
I/[SystemUI]Clock( 1447): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1447): called onTimeUpdated()
I/[SystemUI]DateView( 1447): called onTimeUpdated()
I/[SystemUI]DateView( 1447): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1447): handleTimeUpdate
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-46 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3005] from screen [on:0 period:-1597043528] gl rssi=-46 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-46 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-1597043518] gl rssi=-46 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-46 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1597040496] gl rssi=-46 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-46 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:11] from screen [on:0 period:-1597040485] gl rssi=-46 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
D/sensors_hal_Time( 1031): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1031): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1031): tsOffsetIs: Apps: 1677695729989; DSPS: 55115495; Offset : -4307694751
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-46 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1597037464] gl rssi=-46 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-46 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1597037461] gl rssi=-46 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-46 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:-1597034434] gl rssi=-46 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-46 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:9] from screen [on:0 period:-1597034425] gl rssi=-46 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-46 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1597031403] gl rssi=-46 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-46 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1597031400] gl rssi=-46 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-46 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3000] from screen [on:0 period:-1597028382] gl rssi=-46 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-46 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1597028379] gl rssi=-46 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-46 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1597025352] gl rssi=-46 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-46 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1597025349] gl rssi=-46 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1597022326] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:4] from screen [on:0 period:-1597022322] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,D/sensors_hal_Time( 1031): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1031): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1031): tsOffsetIs: Apps: 1697697935033; DSPS: 55770927; Offset : -4307686869
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1597019298] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:9] from screen [on:0 period:-1597019289] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1597016268] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:11] from screen [on:0 period:-1597016257] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1597013245] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1597013242] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1597010214] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1597010211] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1597007186] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:11] from screen [on:0 period:-1597007175] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1597004155] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1597004152] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1597001124] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1597001121] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,D/sensors_hal_Time( 1031): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1031): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1031): tsOffsetIs: Apps: 1717701275651; DSPS: 56426397; Offset : -4307703158
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1596998095] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1596998092] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1596995063] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1596995060] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1596992033] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1596992030] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1596989002] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1596988999] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1596985973] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:4] from screen [on:0 period:-1596985969] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,I/[SystemUI]TimeTickManager( 1447): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1447): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1447): called onTimeUpdated()
I/[SystemUI]Clock( 1447): called onTimeUpdated()
I/LgeClockWidgetControlView( 1447): called onTimeUpdated()
I/[SystemUI]DateView( 1447): called onTimeUpdated()
I/[SystemUI]DateView( 1447): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1447): handleTimeUpdate
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1596982945] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1596982942] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1596979913] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1596979910] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,D/sensors_hal_Time( 1031): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1031): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1031): tsOffsetIs: Apps: 1737702879758; DSPS: 57081809; Offset : -4307686225
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1596976882] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1596976879] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1596973853] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1596973850] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1596970823] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1596970820] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1596967793] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1596967790] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1596964767] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-1596964757] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1596961737] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-1596961727] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
D/sensors_hal_Time( 1031): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1031): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1031): tsOffsetIs: Apps: 1757705086833; DSPS: 57737241; Offset : -4307676260
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1596958707] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:9] from screen [on:0 period:-1596958698] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1596955677] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:13] from screen [on:0 period:-1596955664] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1596952643] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1596952640] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1596949613] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1596949610] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1596946583] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1596946580] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1596943553] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1596943550] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1596940523] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1596940520] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,D/sensors_hal_Time( 1031): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1031): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1031): tsOffsetIs: Apps: 1777706969951; DSPS: 58392663; Offset : -4307685284
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1596937492] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1596937489] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1596934463] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1596934460] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1596931434] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1596931431] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1596928407] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:11] from screen [on:0 period:-1596928396] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
I/[SystemUI]TimeTickManager( 1447): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1447): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1447): called onTimeUpdated()
I/[SystemUI]Clock( 1447): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1447): called onTimeUpdated()
I/[SystemUI]DateView( 1447): called onTimeUpdated()
I/[SystemUI]DateView( 1447): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1447): handleTimeUpdate
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1596925375] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1596925372] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3000] from screen [on:0 period:-1596922344] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-1596922343] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,D/sensors_hal_Time( 1031): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1031): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1031): tsOffsetIs: Apps: 1797708796557; DSPS: 59048083; Offset : -4307689784
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1596919324] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1596919321] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1596916292] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1596916289] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1596913267] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-1596913257] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1596910238] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:11] from screen [on:0 period:-1596910227] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1596907205] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1596907202] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1596904175] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:4] from screen [on:0 period:-1596904171] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1596901145] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1596901142] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,D/sensors_hal_Time( 1031): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1031): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1031): tsOffsetIs: Apps: 1817711573580; DSPS: 59703534; Offset : -4307689549
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1596898116] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:9] from screen [on:0 period:-1596898107] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1596895084] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1596895081] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1596892056] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:9] from screen [on:0 period:-1596892047] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1596889025] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1596889022] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1596885994] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1596885991] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1596882965] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1596882962] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1596879937] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:11] from screen [on:0 period:-1596879926] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
D/sensors_hal_Time( 1031): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1031): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1031): tsOffsetIs: Apps: 1837713704095; DSPS: 60358964; Offset : -4307695422
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1596876905] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1596876902] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1596873875] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1596873872] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1596870846] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-1596870836] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1596867816] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:11] from screen [on:0 period:-1596867805] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
I/[SystemUI]TimeTickManager( 1447): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1447): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1447): called onTimeUpdated()
I/[SystemUI]Clock( 1447): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1447): called onTimeUpdated()
I/[SystemUI]DateView( 1447): called onTimeUpdated()
I/[SystemUI]DateView( 1447): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1447): handleTimeUpdate
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1596864782] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1596864779] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1596861752] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1596861749] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,D/sensors_hal_Time( 1031): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1031): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1031): tsOffsetIs: Apps: 1857715841691; DSPS: 61014394; Offset : -4307694107
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:-1596858728] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:8] from screen [on:0 period:-1596858720] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1596855699] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1596855696] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1596852667] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-1596852657] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1596849635] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1596849632] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1596846606] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-1596846596] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1596843574] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1596843571] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1596840543] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1596840540] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,D/sensors_hal_Time( 1031): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1031): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1031): tsOffsetIs: Apps: 1877724788246; DSPS: 61670047; Offset : -4307689150
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1596837510] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1596837507] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1596834481] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1596834478] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1596831451] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1596831448] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1596828421] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1596828418] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:-1596825394] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:5] from screen [on:0 period:-1596825389] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-46 f=2412 sc=60 link=72 tx=0.9, 0.0, 0.0  rx=0.9 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1596822382] gl rssi=-46 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-46 f=2412 sc=60 link=72 tx=0.9, 0.0, 0.0  rx=0.9 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1596822379] gl rssi=-46 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,D/sensors_hal_Time( 1031): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1031): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1031): tsOffsetIs: Apps: 1897726834332; DSPS: 62325474; Offset : -4307687691
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-46 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1596819352] gl rssi=-46 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-46 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1596819349] gl rssi=-46 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-46 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:-1596816325] gl rssi=-46 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-46 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1596816322] gl rssi=-46 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-46 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1596813297] gl rssi=-46 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-46 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-1596813287] gl rssi=-46 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-46 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1596810265] gl rssi=-46 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-46 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1596810262] gl rssi=-46 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-46 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1596807245] gl rssi=-46 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-46 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1596807242] gl rssi=-46 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,I/[SystemUI]TimeTickManager( 1447): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1447): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1447): called onTimeUpdated()
I/[SystemUI]Clock( 1447): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1447): called onTimeUpdated()
I/[SystemUI]DateView( 1447): called onTimeUpdated()
I/[SystemUI]DateView( 1447): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1447): handleTimeUpdate
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-46 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1596804214] gl rssi=-46 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-46 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1596804211] gl rssi=-46 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1596801184] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1596801181] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,D/sensors_hal_Time( 1031): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1031): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1031): tsOffsetIs: Apps: 1917729005157; DSPS: 62980905; Offset : -4307683691
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1596798156] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:9] from screen [on:0 period:-1596798147] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1596795125] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1596795122] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1596792102] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1596792099] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1596789075] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1596789072] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1596786046] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:4] from screen [on:0 period:-1596786042] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-46 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1596783017] gl rssi=-46 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-46 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-1596783007] gl rssi=-46 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-46 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1596779986] gl rssi=-46 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-46 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:12] from screen [on:0 period:-1596779974] gl rssi=-46 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
D/sensors_hal_Time( 1031): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1031): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1031): tsOffsetIs: Apps: 1937731864369; DSPS: 63636359; Offset : -4307693028
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-46 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1596776962] gl rssi=-46 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-46 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1596776959] gl rssi=-46 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-46 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1596773932] gl rssi=-46 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-46 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1596773929] gl rssi=-46 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-46 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1596770903] gl rssi=-46 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-46 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1596770900] gl rssi=-46 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-46 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1596767875] gl rssi=-46 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-46 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1596767872] gl rssi=-46 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-46 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1596764847] gl rssi=-46 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-46 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:11] from screen [on:0 period:-1596764836] gl rssi=-46 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-46 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1596761823] gl rssi=-46 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-46 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1596761820] gl rssi=-46 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,D/sensors_hal_Time( 1031): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1031): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1031): tsOffsetIs: Apps: 1957734067590; DSPS: 64291791; Offset : -4307686994
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-46 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1596758793] gl rssi=-46 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-46 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1596758790] gl rssi=-46 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-46 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1596755764] gl rssi=-46 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-46 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1596755761] gl rssi=-46 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-46 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1596752735] gl rssi=-46 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-46 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1596752732] gl rssi=-46 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,D/PowerManagerServiceEx( 1031): acquireWakeLockInternal: lock=257990054, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1031
,V/AlarmManager( 1031): ELAPSED_WAKEUP set : Alarm{1293cb21 type 2 when 1966422 com.android.bluetooth} when 1966422
,W/bt-smp  ( 6290): Key(LSB ~ MSB) = 0a 3c a6 fe eb 17 6a 79 a6 1f 0a 0b f9 50 a0 5f 
W/bt-smp  ( 6290): Plain text(LSB ~ MSB) = de 14 70 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 6290): Encrypted text(LSB ~ MSB) = eb 91 b0 72 2c dc 93 4d d2 a7 f4 f5 37 a6 f2 2a 
W/bt-btm  ( 6290): Stopping oneshot timer
I/ProcessStatsService( 1031): Prepared write state in 16ms
,D/[Concierge]Service( 2603): onStartCommand(). Type : 9
,I/ProcessStatsService( 1031): Prepared write state in 10ms
,D/PowerManagerServiceEx( 1031): releaseWakeLockInternal: lock=257990054 [*alarm*], flags=0x0
,I/ProcessStatsService( 1031): Pruning old procstats: /data/system/procstats/state-2015-12-13-11-43-51.bin
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-46 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1596749706] gl rssi=-46 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-46 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:11] from screen [on:0 period:-1596749695] gl rssi=-46 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-46 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1596746681] gl rssi=-46 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-46 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1596746678] gl rssi=-46 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,I/[SystemUI]TimeTickManager( 1447): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1447): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1447): called onTimeUpdated()
I/[SystemUI]Clock( 1447): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1447): called onTimeUpdated()
I/[SystemUI]DateView( 1447): called onTimeUpdated()
I/[SystemUI]DateView( 1447): called onTimeUpdated()
,D/KeyguardUpdateMonitor( 1447): handleTimeUpdate
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-46 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1596743652] gl rssi=-46 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-46 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1596743649] gl rssi=-46 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-46 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1596740623] gl rssi=-46 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-46 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1596740620] gl rssi=-46 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,D/sensors_hal_Time( 1031): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1031): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1031): tsOffsetIs: Apps: 1977735978780; DSPS: 64947214; Offset : -4307698517
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-46 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1596737593] gl rssi=-46 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-46 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1596737590] gl rssi=-46 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,TIME-OUT KILL (timeout was 1800000ms)
```
