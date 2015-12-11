#### Test 5065027857de7f1_thali03_LGE-LG-D855 Logs


```
--------- beginning of main
D/sensors_hal_Time( 1031): tsOffsetIs: Apps: 272965074886; DSPS: 9085591; Offset : -4322443787
,D/AndroidRuntime( 6144): 
D/AndroidRuntime( 6144): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 6144): CheckJNI is OFF
D/AndroidRuntime( 6144): Calling main entry com.android.commands.am.Am
--------- beginning of system
I/ActivityManager( 1031): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
V/SplitWindowPolicy( 1964): checkScreen => return. sourceIntent is null or not support SplitWindow component: ComponentInfo{co..../co.....MainActivity}
D/SplitInfo( 1031): new ActivitySplitInfo : ActivitySplitInfo [screenZone=0/ flag=0/ state=NATIVE]
D/ActivityManager( 1031): setTaskToReturnTo : TaskRecord{124e866 #4 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
D/ActivityManager( 1031): setTaskToReturnTo : TaskRecord{124e866 #4 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
D/WindowStateEx( 1031): AppWindowTokenEx init.. 
E/GBMv2   (  348): DFP En is all cleared set to be enabled
I/ActivityManager( 1031): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6159 uid=10311 gids={50311, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
D/AndroidRuntime( 6144): Shutting down VM
V/ActivityManager( 1031): Display changed displayId=0
D/DSDPConnection( 1867): Display #0 changed.
D/SplitWindowPolicy( 1964): updateActivityStateChanged: resumed=true, screenId=1, isScreenFull=true
D/SplitWindowPolicy( 1964): topRunningActivity=ActivityInfo{3774663a co.....MainActivity}, taskId=4, activityType=0, bIsSplit=false
D/SplitWindowPolicy( 1964): updateActivityStateChanged: resumed=false, screenId=1, isScreenFull=true
D/SplitWindowPolicy( 1964): topRunningActivity=ActivityInfo{1e9162eb co.....MainActivity}, taskId=4, activityType=0, bIsSplit=false
D/ContextHelper( 6159): convertTheme. context->name=com.test.thalitest themeResourceId=16973833
,I/WebViewFactory( 6159): Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
I/LibraryLoader( 6159): Loading: webviewchromium
I/LibraryLoader( 6159): Time to load native libraries: 4 ms (timestamps 2194-2198)
I/LibraryLoader( 6159): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 6159): Binding Chromium to main looper Looper (main, tid 1) {1c583437}
I/LibraryLoader( 6159): Expected native library version number "",actual native library version number ""
I/chromium( 6159): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 6159): Initializing chromium process, renderers=0
W/art     ( 6159): Attempt to remove local handle scope entry from IRT, ignoring
W/chromium( 6159): [WARNING:dns_config_service_posix.cc(293)] Failed to read DnsConfig.
W/chromium( 6159): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
I/chromium( 6159): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=32 off=46780 len=2953
I/chromium( 6159): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:33 off:229536 len:643667
V/AudioPolicyService(  328): registerClient() client 0xb57f4e00, uid 10311
I/Adreno-EGL( 6159): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 6159): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 6159): Build Date: 12/12/14 금
I/Adreno-EGL( 6159): Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
I/Adreno-EGL( 6159): Remote Branch: 
I/Adreno-EGL( 6159): Local Patches: 
I/Adreno-EGL( 6159): Reconstruct Branch: 
D/BluetoothManagerService( 1031): Message: 20
D/BluetoothManagerService( 1031): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@33a7d1c0:true
D/BluetoothAdapter( 6159): 184626596: getState() :  mService = null. Returning STATE_OFF
W/chromium( 6159): [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
W/chromium( 6159): [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
W/art     ( 6159): Attempt to remove local handle scope entry from IRT, ignoring
W/AwContents( 6159): onDetachedFromWindow called when already detached. Ignoring
D/SystemWebViewEngine( 6159): CordovaWebView is running on device made by: LGE
W/art     ( 6159): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 6159): Attempt to remove local handle scope entry from IRT, ignoring
D/OpenGLRenderer( 6159): Render dirty regions requested: true
I/OpenGLRenderer( 6159): Initialized EGL, version 1.4
D/OpenGLRenderer( 6159): Enabling debug mode 0
D/Atlas   ( 6159): Validating map...
D/SplitWindow( 1031): check instance of lgWin Window{23bb6ffa u0 com.test.thalitest/com.test.thalitest.MainActivity}
D/LgDataFeature( 6159): LgDataFeature() Constructor: none
D/LgDataFeature( 6159): LgDataFeature() Constructor Done, null
I/SystemUI[Framework]( 1031): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x0, pkg=com.android.systemui
D/PhoneStatusBar( 1473): setSystemUiVisibility vis=0 mask=ffffffff oldVal=8000 newVal=0 diff=8000
I/[SystemUI]NavigationThemeResource( 1473): NavigationKey Color is changed(WHITE_WITH_SHADOW -> BLACK)
I/[SystemUI]NavigationThemeResource( 1473):  BarMode=0, Theme=WHITE, LightBackground=false (Transparent)
I/[SystemUI]NavigationThemeResource( 1473): , Keyguard show=false, IME shown=false, Panel expanded=false
W/PhoneWindowManagerEx( 1031): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx( 1031): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx( 1031): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework]( 1031): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@116903d1,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework]( 1031): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
I/ActivityManager( 1031): Displayed com.test.thalitest/.MainActivity: +651ms (total +744ms)
I/Timeline( 1031): Timeline: Activity_windows_visible id: ActivityRecord{206a37a7 u0 com.test.thalitest/.MainActivity t4} time:282675
I/Timeline( 6159): Timeline: Activity_idle id: android.os.BinderProxy@13dd47d4 time:282683
D/JsMessageQueue( 6159): Set native->JS mode to OnlineEventsBridgeMode
E/GBMv2   (  348): DFP En is all cleared set to be enabled
E/GBMv2   (  348): Set value is all cleared set the max
I/GBMv2   (  348): DFP Enabled. Ignore VFP set
D/jxcore_app_log( 6159): JniHelper::setJavaVM(0xb487c280), pthread_self() = -1435094272
,D/JX-Cordova( 6159): jxcore cordova android initializing
W/jxcore-log( 6159): Initializing JXcore engine
W/jxcore-log( 6159): JXcore engine is ready
,W/jxcore-log( 6159): Starting JXcore engine
,W/.test.thalitest( 6159): type=1400 audit(0.0:148): avc: denied { ioctl } for path="socket:[10276]" dev="sockfs" ino=10276 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
,W/.test.thalitest( 6159): type=1400 audit(0.0:149): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3222 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
W/.test.thalitest( 6159): type=1400 audit(0.0:150): avc: denied { ioctl } for path="socket:[9865]" dev="sockfs" ino=9865 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
W/.test.thalitest( 6159): type=1400 audit(0.0:151): avc: denied { ioctl } for path="/cust" dev="mmcblk0p42" ino=2 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=dir
W/.test.thalitest( 6159): type=1400 audit(0.0:152): avc: denied { ioctl } for path="socket:[29323]" dev="sockfs" ino=29323 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
I/art     ( 6159): Background sticky concurrent mark sweep GC freed 123905(12MB) AllocSpace objects, 23(7MB) LOS objects, 28% free, 39MB/55MB, paused 2.064ms total 121.929ms
W/jxcore-log( 6159): Platform android
W/jxcore-log( 6159): 
,W/jxcore-log( 6159): Process ARCH arm
W/jxcore-log( 6159): 
I/jxcore-log( 6159): JXcore Cordova bridge is ready!
I/jxcore-log( 6159): 
W/jxcore-log( 6159): JXcore engine is started
,I/jxcore-log( 6159): Toggling radios to true
I/jxcore-log( 6159): 
,D/BluetoothManagerService( 1031): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1031): enable():  mBluetooth =null mBinding = false
D/BluetoothManagerService( 1031): Message: 1
D/LocationManagerService( 1031): getAllProviders()=[passive, gps, network]
D/Ulp_jni ( 1031): JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
D/Ulp_jni ( 1031): JNI:system_update. Event-4
,D/BluetoothManagerService( 1031): MESSAGE_ENABLE: mBluetooth = null
D/WifiService( 1031): New client listening to asynchronous messages
I/ActivityManager( 1031): Start proc com.android.bluetooth for service com.android.bluetooth/.btservice.AdapterService: pid=6236 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008, 4002, 1023} abi=armeabi-v7a
D/WifiServiceImplEx( 1031): setWifiEnabled: true pid=6159, uid=10311, package= com.test.thalitest, App Lable : ThaliTest
D/WifiService( 1031): setWifiEnabled: true pid=6159, uid=10311
E/WifiService( 1031): Invoking mWifiStateMachine.setWifiEnabled
,E/WifiStateMachine( 1031):  InitialState CMD_START_SUPPLICANT 0 0
I/LGFTMITEM( 1031): [GET_FTM][id=6], offset=12288
,D/LocationManagerService( 1031): getAllProviders()=[passive, gps, network]
E/WifiUtil( 1031): wfc_util_ffile_check_copy(): pid[1031] pDestFName[/data/misc/wifi/WCNSS_qcom_cfg.ini] pSourceFName[/system/etc/wifi/WCNSS_qcom_cfg.ini]
E/WifiUtil( 1031): wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
E/WifiUtil( 1031): wfc_util_ffile_check_copy(): pid[1031] pDestFName[/data/misc/wifi/WCNSS_qcom_wlan_nv.bin] pSourceFName[/system/etc/wifi/WCNSS_qcom_wlan_nv.bin]
E/WifiUtil( 1031): wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
I/WifiUtil( 1031): Intf0MacAddress=C49A027B60AC
D/WifiServiceImplEx( 1031): disconnect pid=6159, uid=10311, packageName=com.test.thalitest
E/WifiHW  ( 1031): unknown target_country: EU , set to default
E/WifiHW  ( 1031): [wifi_ensure_config_files] default country1 = GB
E/WifiHW  ( 1031): [wifi_ensure_config_files] default country2 = GB
I/WifiUtil( 1031): gEnableBmps=1
D/WifiServiceImplEx( 1031): reconnect pid=6159, uid=10311, packageName=com.test.thalitest
D/Ulp_jni ( 1031): JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 1,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
D/Ulp_jni ( 1031): JNI:system_update. Event-4
I/jxcore-log( 6159): Radios toggled
I/jxcore-log( 6159): 
,D/BluetoothManagerService( 1031): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/jxcore-log( 6159): Got Device Bluetooth address: 58:3F:54:73:64:C0
I/jxcore-log( 6159): 
I/jxcore-log( 6159): Perf Test app loaded loaded
I/jxcore-log( 6159): 
I/jxcore-log( 6159): check test folder
I/jxcore-log( 6159): 
I/jxcore-log( 6159): found test : ./testFindPeers.js
I/jxcore-log( 6159): 
,W/ResourcesManager( 6236): Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
W/ResourcesManager( 6236): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 6236): Asset path '/system/framework/com.qcom.bluetooth.jar' does not exist or contains no resources.
W/ResourcesManager( 6236): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,I/jxcore-log( 6159): found test : ./testSendData.js
I/jxcore-log( 6159): 
,D/BluetoothAdapterApp( 6236): Loading JNI Library
,D/BluetoothAdapterApp( 6236): REFCOUNT: Constructed com.android.bluetooth.btservice.AdapterApp@74f1d5b Instance Count = 1
,D/Tethering( 1031): sendTetherStateChangedBroadcast 1, 0, 0
D/SoftapController(  323): Softap fwReload - Ok
,D/libc-netbsd(  323): default dns: query_ipv6=0, query_ipv4=0
D/CommandListener(  323): Setting iface cfg
D/CommandListener(  323): Trying to bring down wlan0
D/DSQN    ( 1031): DNSproblemNotiEnabled is disabled ignore DNS fail CB
D/CommandListener(  323): Clearing all IP addresses on wlan0
E/WifiHW  ( 1031): Cannot open "/system/etc/wifi/autojoinconfig.txt": No such file or directory
E/WifiStateMachine( 1031): Couldn't get getWiFiOffloadingIface : 
E/WifiStateMachine( 1031): useWiFiOffloading() : false
E/WifiStateMachine( 1031): CONFIG_LGE_WLAN_PATH : true
,W/wpa_supplicant( 6274): type=1400 audit(0.0:153): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6828 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
W/wpa_supplicant( 6274): type=1400 audit(0.0:154): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6828 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
I/chromium( 6159): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
I/wpa_supplicant( 6274): Successfully initialized wpa_supplicant
I/chromium( 6159): [INFO:SkFontConfigInterface_android.cpp(247)] ---- failed to open </system/fonts/CutiveMono.ttf> as a font
I/chromium( 6159): 
I/ActivityManager( 1031): Start proc com.android.settings for broadcast com.android.settings/.deviceinfo.UsbSettingsReceiver: pid=6275 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
D/BluetoothAdapterApp( 6236): onCreate
D/WifiMonitor( 1031): startMonitoring(wlan0) with mConnected = false
D/WifiMonitor( 1031): connecting to supplicant
V/WfdStateTracker( 1964): WfdStateTracker handleDirectStateChangedEvent: 1
I/WifiServerServiceExt( 1031): WIFI_STATE_CHANGED_ACTION [2]
,D/StatusBar.NetworkController( 1473): refreshViews: Data not connected!! Set no data type icon / Roaming
D/ProfileConfigQcom( 6236): [BTUI] HeadsetService is supported
D/ProfileConfigQcom( 6236): Adding HeadsetService
D/ProfileConfigQcom( 6236): [BTUI] A2dpService is supported
,D/ProfileConfigQcom( 6236): Adding A2dpService
D/ProfileConfigQcom( 6236): [BTUI] HidService is supported
D/ProfileConfigQcom( 6236): Adding HidService
D/ProfileConfigQcom( 6236): [BTUI] HealthService is supported
D/ProfileConfigQcom( 6236): Adding HealthService
D/LGBluetoothFeatureConfig( 6236): isSupportPan() :  mTargetOp=OPEN
I/chromium( 6159): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
D/ProfileConfigQcom( 6236): [BTUI] PanService is supported
D/ProfileConfigQcom( 6236): Adding PanService
D/ProfileConfigQcom( 6236): [BTUI] GattService is supported
D/ProfileConfigQcom( 6236): Adding GattService
D/ProfileConfigQcom( 6236): [BTUI] BluetoothMapService is supported
D/ProfileConfigQcom( 6236): Adding BluetoothMapService
I/wpa_supplicant( 6274): rfkill: Cannot open RFKILL control device
D/ProfileConfigQcom( 6236): [BTUI] HeadsetClientService is NOT supported
I/wpa_supplicant( 6274): [LGE_PATCH] unset P2P_CAPABLE to ifname wlan0
D/Tethering( 1031): InitialState.processMessage what=4
D/Tethering( 1031): sendTetherStateChangedBroadcast 0, 0, 0
,W/ResourcesManager( 6275): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6275): Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
W/ResourcesManager( 6275): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 6275): Asset path '/system/framework/com.lge.bluetooth.jar' does not exist or contains no resources.
W/ResourcesManager( 6275): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
,W/ResourcesManager( 6275): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,D/BluetoothManagerService( 1031): Message: 20
D/BluetoothManagerService( 1031): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@35420e95:true
D/BluetoothAdapterState( 6236): make
I/LGFMServiceAdapter( 6236): [FM] LGFMServiceAdapter : create
I/bluedroid-qcom( 6236): init
I/BluetoothAdapterState( 6236): Entering OffState
I/bte_conf( 6236): bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
I/bte_conf( 6236): bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
E/bt_osi_config( 6236): config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
I/bte_conf( 6236): bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
D/BTIF_CORE( 6236): [BTUI] lge_load_bluetooth_address
I/bluedroid-qcom( 6236): get_profile_interface socket
I/bluedroid-qcom( 6236): get_profile_interface map_client
I/GKI_LINUX( 6236): gki_task_entry task_id=1 [BTIF] starting
W/bdaddr_loader( 6297): type=1400 audit(0.0:155): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6828 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
W/bdaddr_loader( 6297): type=1400 audit(0.0:156): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6828 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,D/BluetoothManagerService( 1031): BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
D/BluetoothManagerService( 1031): Message: 40
D/BluetoothManagerService( 1031): MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
D/BluetoothAdapterProperties( 6236): Address is:58:3F:54:73:64:C0
I/bluedroid-qcom( 6236): config_hci_snoop_log
D/lge_bdaddr_loader( 6297): [BTUI] bdaddr_loader ::: START
D/lge_bdaddr_loader( 6297): [BTUI] bluetooth_load_bdaddress
I/LGFTMITEM( 6297): [GET_FTM][id=8], offset=16384
D/BluetoothManagerService( 1031): Calling onBluetoothServiceUp callbacks
D/BluetoothManagerService( 1031): Broadcasting onBluetoothServiceUp() to 7 receivers.
D/lge_bdaddr_loader( 6297): [BTUI] bdaddr to set in property : 58:3F:54:73:64:C0
D/BluetoothManagerService( 1031): Bluetooth Adapter name changed to G3-1
D/BluetoothManagerService( 1031): Stored Bluetooth name: G3-1
D/BluetoothAdapterProperties( 6236): Name is: G3-1
V/LGMDMManagerInternal( 6236): Create singleton instance
E/lge_bdaddr_loader( 6297): [BTUI] bluetooth_load_bdaddress : OK => 58:3F:54:73:64:C0
D/lge_bdaddr_loader( 6297): [BTUI] bdaddr_loader ::: END
,D/BluetoothAdapterState( 6236): CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
D/BluetoothAdapterProperties( 6236): Setting state to 11
I/BluetoothAdapterState( 6236): Bluetooth adapter state changed: 10-> 11
D/BluetoothManagerService( 1031): Message: 60
,D/BluetoothManagerService( 1031): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
D/BluetoothManagerService( 1031): Bluetooth State Change Intent: 10 -> 11
I/LGBluetoothServiceJni( 6236): classInitNative: succeeds
D/LGBluetoothAPIService( 1964): [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
I/[SystemUI]BluetoothHandler( 1473): Receive : BluetoothAdapter.ACTION_STATE_CHANGED
D/BluetoothBondStateMachine( 6236): make
,D/BluetoothAdapterService( 6236): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@369476c2
I/BluetoothBondStateMachine( 6236): StableState(): Entering Off State
D/LGBluetoothServiceAdapter( 6236): [BTUI] check adapter is available - false.
D/BluetoothAdapterService( 6236): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@369476c2
D/LGBluetoothServiceAdapter( 6236): [BTUI] check adapter is available - true : set adapter available.
I/wpa_supplicant( 6274): rfkill: Cannot open RFKILL control device
I/chromium( 6159): [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
I/chromium( 6159): 
D/LGBluetoothSettingsDBObserver( 6236): [BTUI] register observer for LG device name DB
E/BluetoothAdapterService( 6236): File transfer profiles supported!!
,E/BluetoothAdapterService( 6236): File transfer profiles supported!!
D/BluetoothHeadset( 1867): Proxy object connected
D/BluetoothHeadset( 1031): Proxy object connected
D/HeadsetService( 6236): Received start request. Starting profile...
D/BluetoothHeadset( 1867): Proxy object connected
D/UsbSettingsReceiver( 6275): [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
D/BluetoothHeadset( 1867): Proxy object connected
D/UsbSettingsReceiver( 6275): [AUTORUN] sys.usb.config = ptp_only,adb
D/UsbSettingsReceiver( 6275): [AUTORUN] sys.usb.state = ptp_only,adb
D/UsbSettingsReceiver( 6275): [AUTORUN] persist.sys.usb.config = ptp_only,adb
I/LGBluetoothHeadsetServiceJni( 6236): classInitNative: succeeds
D/LGBluetoothHfpAdapter( 6236): Version 1.6
D/UsbSettingsReceiver( 6275): [AUTORUN] onReceive() : app userid = 0, current userid = 0
E/BluetoothAdapterService( 6236): File transfer profiles supported!!
D/LGBluetoothFeatureConfig( 6236): isPrivacyLogsEnabled : true
I/BluetoothHeadsetServiceJni( 6236): classInitNative: succeeds
D/HeadsetStateMachine( 6236): make
,E/BluetoothAdapterService( 6236): File transfer profiles supported!!
E/BluetoothAdapterService( 6236): File transfer profiles supported!!
E/BluetoothAdapterService( 6236): File transfer profiles supported!!
,E/BluetoothAdapterService( 6236): File transfer profiles supported!!
D/UsbSettingsControl( 6275): [AUTORUN] getUsbConnected() : connected=true
D/UsbSettingsReceiver( 6275): [AUTORUN] onReceive() : availableList=[wlan0]
D/UsbSettingsReceiver( 6275): [AUTORUN] onReceive() : activeList=[]
D/UsbSettingsReceiver( 6275): [AUTORUN] onReceive() : errorList=[]
D/UsbSettingsControl( 6275): [AUTORUN] isAutorunTimer() : mAutorunChanging=false
D/UsbSettingsReceiver( 6275): [AUTORUN] onReceive() : TetherState Changed=wlan0
,D/UsbSettingsControl( 6275): [AUTORUN] setTetherStatus() : status=false
I/ActivityManager( 1031): Killing 5514:com.lge.appbox.client/u0a11 (adj 15): empty #17
D/LgDataFeature( 6236): LgDataFeature() Constructor: none
D/LgDataFeature( 6236): LgDataFeature() Constructor Done, null
,V/LGMDMManager( 6236): Create singleton instance
I/BluetoothAdapterState( 6236): Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
I/wpa_supplicant( 6274): [LGE_WLAN_PATCH]P2P 5GHz support level:2(0:no 1:gconly 2:gconly_UNII1 3:full)
,I/wpa_supplicant( 6274): p2p0: CTRL-EVENT-AVOID-FREQ ranges=
,I/wpa_supplicant( 6274): wlan0: CTRL-EVENT-SCAN-STARTED 
E/WifiStateMachine( 1031):  SupplicantStartingState CMD_SET_OPERATIONAL_MODE 1 0
E/WifiStateMachine( 1031):  SupplicantStartingState CMD_START_DRIVER 0 0
E/WifiStateMachine( 1031):  SupplicantStartingState CMD_SET_HIGH_PERF_MODE 0 0
E/WifiStateMachine( 1031):  DefaultState CMD_SET_HIGH_PERF_MODE 0 0
E/WifiStateMachine( 1031):  SupplicantStartingState CMD_DISCONNECT 0 0
E/WifiStateMachine( 1031):  DefaultState CMD_DISCONNECT 0 0
E/WifiStateMachine( 1031):  SupplicantStartingState CMD_RECONNECT 0 0
D/WifiMonitor( 1031): Event [IFNAME=p2p0 CTRL-EVENT-AVOID-FREQ ranges=]
E/WifiStateMachine( 1031):  DefaultState CMD_RECONNECT 0 0
D/WifiMonitor( 1031): Dropping event because (p2p0) is stopped
D/WifiMonitor( 1031): Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1031): WifiMonitor:wlan0 cnt=0 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1031): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1031): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
E/WifiStateMachine( 1031):  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1031):  DefaultState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1031):  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
,E/WifiStateMachine( 1031):  DefaultState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1031):  SupplicantStartingState SUP_CONNECTION_EVENT 0 0
D/WifiNative-wlan0( 1031): doString: [DRIVER MACADDR]
D/WifiNative-wlan0( 1031):    returned Macaddr = c4:9a:02:7b:60:ac
D/WifiStateMachine( 1031): MAC Addr from driver = c4:9a:02:7b:60:ac
D/WifiOffDelayIfNotUsed( 1031): setPowerSaveActivated(false)
I/ActivityManager( 1031): Start proc com.lge.formmanager for broadcast com.lge.formmanager/.FormServiceReceiver: pid=6302 uid=10026 gids={50026, 9997, 3003, 1028} abi=armeabi-v7a
W/libprocessgroup( 1031): failed to open /acct/uid_10011/pid_5514/cgroup.procs: No such file or directory
,D/HeadsetStateMachine( 6236): max_hf_connections = 1
I/bluedroid-qcom( 6236): get_profile_interface handsfree
E/WifiStateMachine( 1031): Couldn't get getWiFiOffloadingIface : 
E/WifiStateMachine( 1031): useWiFiOffloading() : false
E/WifiStateMachine( 1031): CONFIG_LGE_WLAN_PATH : true
D/WifiNative-wlan0( 1031): doBoolean: SET update_config 1
D/WifiNative-wlan0( 1031): SET update_config 1: returned true
W/Settings( 1031): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1031): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiConfigStore( 1031): Loading config and enabling all networks 
D/WifiNative-wlan0( 1031): doString: [LIST_NETWORKS]
D/WifiNative-wlan0( 1031):    returned network id / ssid / bssid / flags 0	NG700	any	
V/ToneGenerator( 6236): ToneGenerator constructor: streamType=8, volume=1.000000
D/WfdService( 1964): Waiting for WifiP2p enabling
D/StatusBar.NetworkController( 1473): refreshViews: Data not connected!! Set no data type icon / Roaming
V/AudioPolicyService(  328): registerClient() client 0xb1185d60, uid 1002
V/AudioPolicyManager(  328): getOutput() device 2, stream 8, samplingRate 0, format 0, channelMask 3, flags 0
V/AudioPolicyManagerEx(  328): AudioPolicyManagerEx: getOutputForDevice
V/AudioPolicyManagerEx(  328): getOutput() returns output 2
,V/AudioSystem( 6236): getOutputSamplingRate() no output descriptor for output 2 in gOutputs
V/AudioFlinger(  328): registerClient() client 0xb5581ce8, pid 6236
V/AudioSystem(  328): ioConfigChanged() event 0, ioHandle 2
V/AudioSystem(  328): ioConfigChanged() opening already existing output! 2
V/AudioSystem( 1867): ioConfigChanged() event 0, ioHandle 2
V/AudioSystem( 1867): ioConfigChanged() opening already existing output! 2
V/AudioSystem(  328): ioConfigChanged() event 0, ioHandle 4
V/AudioSystem(  328): ioConfigChanged() opening already existing output! 4
V/AudioSystem( 3306): ioConfigChanged() event 0, ioHandle 2
V/AudioSystem( 3306): ioConfigChanged() opening already existing output! 2
V/AudioSystem( 3306): ioConfigChanged() event 0, ioHandle 4
V/AudioSystem( 3306): ioConfigChanged() opening already existing output! 4
V/AudioSystem( 1473): ioConfigChanged() event 0, ioHandle 2
V/AudioSystem( 1473): ioConfigChanged() opening already existing output! 2
V/AudioSystem( 1473): ioConfigChanged() event 0, ioHandle 4
V/AudioSystem( 1473): ioConfigChanged() opening already existing output! 4
V/AudioSystem( 1867): ioConfigChanged() event 0, ioHandle 4
V/AudioSystem( 1867): ioConfigChanged() opening already existing output! 4
V/AudioSystem( 6236): ioConfigChanged() event 0, ioHandle 2
V/AudioSystem( 1031): ioConfigChanged() event 0, ioHandle 2
V/AudioSystem( 1031): ioConfigChanged() opening already existing output! 2
V/AudioSystem( 1031): ioConfigChanged() event 0, ioHandle 4
V/AudioSystem( 1031): ioConfigChanged() opening already existing output! 4
V/AudioSystem( 6236): ioConfigChanged() new output samplingRate 48000, format 0x5 channel mask 0x3 frameCount 960 latency 50
V/AudioSystem( 6236): ioConfigChanged() event 0, ioHandle 4
V/AudioSystem( 6236): ioConfigChanged() new output samplingRate 48000, format 0x1 channel mask 0x3 frameCount 960 latency 80
V/ToneGenerator( 6236): Create Track: 0xb4928a80
V/AudioTrack( 6236): set(): streamType 8, sampleRate 0, format 0x1, channelMask 0x1, frameCount 0, flags #4, notificationFrames 0, sessionId 0, transferType 1
V/AudioTrack( 6236): set() streamType 8, sampleRate 0, format 1, frameCount 0, flags 0004
V/AudioPolicyManager(  328): getOutputForAttr() usage=3, content=4, tag= flags=00000000
V/AudioPolicyManager(  328): getOutputForAttr() device 2, samplingRate 0, format 0, channelMask 3, flags 0
V/AudioPolicyManagerEx(  328): AudioPolicyManagerEx: getOutputForDevice
V/AudioPolicyManagerEx(  328): getOutput() returns output 2
I/AudioFlinger(  328): isAudioPlaybackHookOn() false
V/AudioPolicyManager(  328): getOutputForAttr() usage=3, content=4, tag= flags=00000000
V/AudioPolicyManager(  328): getOutputForAttr() device 2, samplingRate 48000, format 1, channelMask 1, flags 4
V/AudioPolicyManagerEx(  328): AudioPolicyManagerEx: getOutputForDevice
V/AudioPolicyManagerEx(  328): getOutput() returns output 2
I/WifiServerServiceExt( 1031): WIFI_STATE_CHANGED_ACTION [3]
V/AudioSystem( 6236): getLatency() output 2, latency 50
V/AudioSystem( 6236): getFrameCount() output 2, frameCount 960
V/AudioTrack( 6236): createTrack_l() output 2 afLatency 50
V/AudioFlinger(  328): [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
V/AudioFlinger(  328): [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
V/AudioFlinger(  328): [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
V/AudioFlinger(  328): [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
V/AudioFlinger(  328): createTrack() lSessionId: 16
V/AudioTrack( 6236): AUDIO_OUTPUT_FLAG_FAST successful; frameCount 480
V/AudioFlinger(  328): acquiring 16 from 6236, for 6236
V/AudioFlinger(  328):  added new entry for 16
V/ToneGenerator( 6236): ToneGenerator INIT OK, time: 286551
D/BluetoothAdapterService( 6236): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@369476c2
I/WifiServerServiceExt( 1031): batteryPsActivateMsgHandler : state:0 event:3
D/HeadsetStateMachine( 6236): Enter Disconnected: -2, size: 0
D/HeadsetPhoneState( 6236): [BTUI] listenForPhoneState : start = false
D/LGBluetoothHfpManager( 6236): [BTUI] listenForMultiSimPhoneState : start = false
D/HeadsetStateMachine( 6236): [BTUI] change sampling rate to 8000 when device is disconnected
D/BluetoothAdapterService( 6236): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@369476c2
E/WifiConfigStore( 1031): readNetworkVariablesFromSupplicantFile key=psk
D/BluetoothA2dp( 1031): Proxy object connected
V/AudioFlinger(  328): setParameters(): io 0, keyvalue bt_samplerate=8000, calling pid 6236
D/audio_hw_primary(  328): adev_set_parameters: enter: bt_samplerate=8000
D/A2dpService( 6236): Received start request. Starting profile...
V/voice   (  328): voice_set_parameters: enter: bt_samplerate=8000
V/compress_voip(  328): voice_extn_compress_voip_set_parameters: enter: bt_samplerate=8000
V/compress_voip(  328): voice_extn_compress_voip_set_parameters: exit
V/voice   (  328): voice_set_parameters: exit with code(0)
V/msm8974_platform_lge(  328): LGE_platform_set_parameters: enter: bt_samplerate=8000
V/msm8974_platform(  328): platform_set_parameters: enter: bt_samplerate=8000
V/msm8974_platform(  328): platform_set_parameters: exit with code(0)
V/lge_audio_loopback(  328): lge_platform_set_loopback_parameters: enter: 
V/audio_hw_primary(  328): adev_set_parameters: exit with code(0)
E/audio_a2dp_hw(  328): adev_set_parameters: ERROR: set param called even when stream out is null
I/BluetoothAvrcpServiceJni( 6236): classInitNative: succeeds
V/Avrcp   ( 6236): make
V/ToneGenerator( 6236): ToneGenerator destructor
V/ToneGenerator( 6236): stopTone
V/ToneGenerator( 6236): Delete Track: 0xb4928a80
D/Avrcp   ( 6236): [BTUI] Use Native AVRCP : init jni
I/bluedroid-qcom( 6236): get_profile_interface avrcp
V/AudioTrack( 6236): ~AudioTrack, releasing session id from 6236 on behalf of 6236
V/AudioPolicyService(  328): AudioCommandThread() adding release output 2
V/AudioPolicyService(  328): inserting command: 6 at index 0, num commands 0
V/AudioPolicyService(  328): AudioCommandThread() waking up
V/AudioPolicyService(  328): AudioCommandThread() processing release output 2
V/AudioPolicyManager(  328): releaseOutput() 2
V/AudioPolicyService(  328): AudioCommandThread() going to sleep
V/AudioFlinger(  328): PlaybackThread::Track destructor
V/AudioFlinger(  328): removeClient_l() pid 6236, calling pid 328
V/AudioFlinger(  328): releasing 16 from 6236 for 6236
V/AudioFlinger(  328):  decremented refcount to 0
V/AudioFlinger(  328): purging stale effects
E/WifiConfigStore( 1031): readNetworkVariableFromSupplicantFile ssid=["NG700"] key=psk
E/WifiConfigStore( 1031): Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
D/WifiStateMachine( 1031): enableVerboseLogging : level 2
D/WifiNative-wlan0( 1031): doBoolean: SET device_name g3_global_com
V/AudioManager( 6236): registerRemoteController: size of Media player list: 0
,D/WifiNative-wlan0( 1031): SET device_name g3_global_com: returned true
D/WifiNative-wlan0( 1031): doBoolean: SET manufacturer LGE
D/WifiNative-wlan0( 1031): SET manufacturer LGE: returned true
D/WifiNative-wlan0( 1031): doBoolean: SET model_name LG-D855
D/WifiNative-wlan0( 1031): SET model_name LG-D855: returned true
D/WifiNative-wlan0( 1031): doBoolean: SET model_number LG-D855
D/WifiNative-wlan0( 1031): SET model_number LG-D855: returned true
E/AudioManager( 6236): No RCC entry present to update
E/RemoteController( 6236): Cannot set synchronization mode on an unregistered RemoteController
D/WifiNative-wlan0( 1031): doBoolean: SET serial_number LGD8553bed2d08
D/WifiNative-wlan0( 1031): SET serial_number LGD8553bed2d08: returned true
D/WifiNative-wlan0( 1031): doBoolean: SET config_methods physical_display virtual_push_button
D/WifiNative-wlan0( 1031): SET config_methods physical_display virtual_push_button: returned true
D/WifiNative-wlan0( 1031): doBoolean: SET device_type 10-0050F204-5
D/WifiNative-wlan0( 1031): SET device_type 10-0050F204-5: returned true
D/WifiStateMachine( 1031): Setting OUI to DA-A1-19
D/WifiNative-wlan0( 1031): doBoolean: SCAN_INTERVAL 120
D/WifiNative-wlan0( 1031): SCAN_INTERVAL 120: returned true
D/WifiNative-HAL( 1031): Setting external_sim to 1
I/BluetoothAvrcpQcomServiceJni( 6236): classInitQcomNative: succeeds
D/WifiNative-wlan0( 1031): doBoolean: SET external_sim 1
D/WifiNative-wlan0( 1031): SET external_sim 1: returned true
I/WifiNative-HAL( 1031): startHal
E/wifi    ( 1031): getStaticLongField sWifiHalHandle 0x9893b8dc
E/WifiHAL ( 1031): Could not connect handle
D/wifi    ( 1031): halHandle = 0x0, mVM = 0xb487c280, mCls = 0x601952
I/WifiNative-HAL( 1031): Could not start hal
D/WifiStateMachine( 1031): Setting OUI to DA-A1-19
I/WifiNative-HAL( 1031): startHal
E/wifi    ( 1031): getStaticLongField sWifiHalHandle 0x9893b85c
D/LGBluetoothAvrcpQcomAdapter( 6236): [BTUI] Use QCOM AVRCP 1.5 : init jni, browsing = false
I/BluetoothAvrcpQcomServiceJni( 6236): initQcomNative: succeeds
E/WifiHAL ( 1031): Could not connect handle
D/wifi    ( 1031): halHandle = 0x0, mVM = 0xb487c280, mCls = 0x70187a
I/WifiNative-HAL( 1031): Could not start hal
D/WifiNative-wlan0( 1031): doBoolean: STA_AUTOCONNECT 1
D/WifiNative-wlan0( 1031): STA_AUTOCONNECT 1: returned true
D/WifiNative-wlan0( 1031): doBoolean: DRIVER BTCOEXSCAN-STOP
W/Settings( 6068): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/wpa_supplicant( 6274): wpa_driver_nl80211_ext_driver_cmd BTCOEXSCAN-STOP
D/WifiNative-wlan0( 1031): DRIVER BTCOEXSCAN-STOP: returned true
D/WfdsService( 1964): Supplicant Connection state is changed : true
D/WifiNative-wlan0( 1031): doBoolean: DRIVER RXFILTER-STOP
D/WfdsService( 1964): DefaultState - WIFI_SUPPLICANT_CONNECTED
D/WfdsService( 1964): Set the WFDS Monitor: true
I/wpa_supplicant( 6274): wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
D/WifiNative-wlan0( 1031): DRIVER RXFILTER-STOP: returned true
D/WifiNative-wlan0( 1031): doBoolean: DRIVER RXFILTER-REMOVE 3
I/wpa_supplicant( 6274): wpa_driver_nl80211_ext_driver_cmd RXFILTER-REMOVE 3
D/WifiNative-wlan0( 1031): DRIVER RXFILTER-REMOVE 3: returned true
D/WifiNative-wlan0( 1031): doBoolean: DRIVER RXFILTER-START
I/wpa_supplicant( 6274): wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
D/WifiNative-wlan0( 1031): DRIVER RXFILTER-START: returned true
D/WfdsMonitor( 1964): WfdsMonitorThread create
D/WifiNative-wlan0( 1031): doBoolean: DRIVER RXFILTER-STOP
I/wpa_supplicant( 6274): wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
D/WfdsMonitor( 1964): WFDS Monitor is created and started
D/WfdsService( 1964): WiFi: Supplicant connection re-established
D/WifiNative-wlan0( 1031): DRIVER RXFILTER-STOP: returned true
D/WifiNative-wlan0( 1031): doBoolean: DRIVER RXFILTER-REMOVE 2
I/wpa_supplicant( 6274): android_multicast_filter_startstop : multicast filter set
D/WifiNative-wlan0( 1031): DRIVER RXFILTER-REMOVE 2: returned true
D/WifiNative-wlan0( 1031): doBoolean: DRIVER RXFILTER-START
I/wpa_supplicant( 6274): wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
D/WifiNative-wlan0( 1031): DRIVER RXFILTER-START: returned true
E/WifiNative: ( 1031): [286,570,762 us] RECONNECT  stack:logDbg - reconnect - enter - invokeEnterMethods - performTransitions
D/WifiNative-wlan0( 1031): doBoolean: RECONNECT
D/WifiNative-wlan0( 1031): RECONNECT: returned true
D/WifiNative-wlan0( 1031): doString: [STATUS]
D/WifiMonitor( 1031): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
E/WifiMonitor( 1031): WifiMonitor:wlan0 cnt=1 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
D/WifiNative-wlan0( 1031):    returned wpa_state=SCANNING p2p_device_address=02:9a:02:7b:60:ac address=c4:9a:02:7b:60:ac uuid=530d3fd0-1ba3-5409-a336-ff4e42af59a2
D/WifiNative-wlan0( 1031): doBoolean: DRIVER SETSUSPENDMODE 1
I/wpa_supplicant( 6274): wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 1
D/WifiNative-wlan0( 1031): DRIVER SETSUSPENDMODE 1: returned true
D/WifiNative-wlan0( 1031): doBoolean: SET ps 1
D/LGBluetoothAvrcpQcomAdapter( 6236): [BTUI] [+] updateMediaPlayerInfo
D/WifiHS20( 1031): hidePasspointNotification off =false
D/WifiNative-wlan0( 1031): SET ps 1: returned true
D/LGWifiP2pService( 1031): P2pDisabledState{ when=-1ms what=131203 target=com.android.internal.util.StateMachine$SmHandler }
W/Settings( 1031): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1031): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1031): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
D/CommandListener(  323): Setting iface cfg
D/CommandListener(  323): Trying to bring up p2p0
D/WifiMonitor( 1031): startMonitoring(p2p0) with mConnected = true
D/LGWifiP2pService( 1031): P2pEnablingState
D/LGWifiP2pService( 1031): P2pEnablingState{ when=0 what=147457 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1031): P2p socket connection successful
D/LGWifiP2pService( 1031): P2pEnabledState
E/CtrlSupplicant( 1964): Access OK "@android:wpa_wlan0"
E/CtrlSupplicant( 1964): Succeed to open control connection
E/CtrlSupplicant( 1964): Succeed to open monitor connection
D/WfdsMonitor( 1964): Supplicant connection established
D/WfdsService( 1964): Connected to the supplicant for wfds
,I/StatusBar.NetworkController( 1473): networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1473): mWifiConnected = false, mWifiLevel = 0
D/WifiService( 1031): New client listening to asynchronous messages
D/LGWifiP2pService( 1031): sending p2p connection changed broadcast
,D/WifiNative-p2p0( 1031): doBoolean: SET persistent_reconnect 1
E/WifiStateMachine( 1031):  DisconnectedState CMD_SET_OPERATIONAL_MODE 1 0
E/WifiStateMachine( 1031):  DisconnectedState CMD_START_DRIVER 0 0
E/WifiStateMachine( 1031):  ConnectModeState CMD_START_DRIVER 0 0
E/WifiStateMachine( 1031):  DriverStartedState CMD_START_DRIVER 0 0
D/StatusBar.NetworkController( 1473): refreshViews: Data not connected!! Set no data type icon / Roaming
E/WifiStateMachine( 1031):  DisconnectedState what:132106 1 0
E/WifiStateMachine( 1031):  ConnectModeState what:132106 1 0
E/WifiStateMachine( 1031):  DriverStartedState what:132106 1 0
D/WifiScanningService( 1031): SCAN_AVAILABLE : 3
D/RttService( 1031): SCAN_AVAILABLE : 3
D/WifiScanningService( 1031): DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
I/WifiNative-HAL( 1031): startHal
V/WfdStateTracker( 1964): WfdStateTracker handleDirectStateChangedEvent: 2
D/RttService( 1031): DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
D/WfdsService( 1964): WifiP2pState is changed : true
D/WfdsService( 1964): WIFI_P2P_CONNECTION_CHANGED_ACTION
D/WfdsService( 1964): isConnected: false
D/WfdsService( 1964): Receive the WFDS_ENABLE Method
D/WfdsService( 1964): Set the WFDS Monitor: true
D/WfdsService( 1964): Connected to the supplicant for wfds
D/WfdsJNI ( 1964): doCommand: WFDS_SET TRUE
I/wpa_supplicant( 6274): WFDS: wfds_supplicant_wfds_cmd: cmd = SET TRUE
D/WfdsJNI ( 1964): doCommand: WFDS_GET_MAC_ADDRESS
I/wpa_supplicant( 6274): WFDS: wfds_supplicant_wfds_cmd: cmd = GET_MAC_ADDRESS
D/WfdsJNI ( 1964): doCommand: IFNAME=wlan0 GET_CAPABILITY channels
D/WfdsService( 1964): selectPreferredScanChannel [36]
D/WfdsService( 1964): STATE : WfdsEnabledState - enter: this device mac 02:9a:02:7b:60:ac
D/WifiNative-p2p0( 1031): SET persistent_reconnect 1: returned true
E/wifi    ( 1031): getStaticLongField sWifiHalHandle 0x94f5a99c
D/WifiNative-p2p0( 1031): doBoolean: SET device_name G3-1
E/WifiHAL ( 1031): Could not connect handle
D/wifi    ( 1031): halHandle = 0x0, mVM = 0xb487c280, mCls = 0x401596
I/WifiNative-HAL( 1031): Could not start hal
I/WifiServerServiceExt( 1031): setWifiDualbandAPConnection band : 1
E/WifiScanningService( 1031): could not start HAL
E/wpa_supplicant( 6274): nWIFIDualbandAPConnection: 1
D/WifiNative-p2p0( 1031): SET device_name G3-1: returned true
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
D/WifiNative-p2p0( 1031): P2P_SET conc_pref p2p: returned true
D/WifiNative-HAL( 1031): p2pGetDeviceAddress
E/WifiStateMachine( 1031):  DisconnectedState what:132096 -100 0
E/WifiStateMachine( 1031):  ConnectModeState what:132096 -100 0
D/WifiNative-HAL( 1031): p2pGetDeviceAddress returning 02:9a:02:7b:60:ac
,D/LGWifiP2pService( 1031): DeviceAddress: 02:9a:02:7b:60:ac
D/WifiNative-p2p0( 1031): doBoolean: P2P_FLUSH
D/WifiNative-p2p0( 1031): P2P_FLUSH: returned true
D/WifiNative-p2p0( 1031): doBoolean: P2P_SERVICE_FLUSH
E/WifiStateMachine( 1031):  DriverStartedState what:132096 -100 0
I/WifiServerServiceExt( 1031): set CMD_DISCONNECT_RSSI_LVL : -100
E/wpa_supplicant( 6274): disconnect_rssi_lvl: -100
D/WifiNative-p2p0( 1031): P2P_SERVICE_FLUSH: returned true
D/WifiNative-p2p0( 1031): doString: [LIST_NETWORKS]
E/WifiStateMachine( 1031):  DisconnectedState CMD_SET_COUNTRY_CODE 1 0 cz
E/WifiStateMachine( 1031):  ConnectModeState CMD_SET_COUNTRY_CODE 1 0 cz
E/WifiStateMachine( 1031):  DriverStartedState CMD_SET_COUNTRY_CODE 1 0 cz
D/WifiNative-wlan0( 1031): doBoolean: DRIVER COUNTRY CZ
D/WifiNative-p2p0( 1031):    returned network id / ssid / bssid / flags
D/WifiNative-p2p0( 1031): doBoolean: SAVE_CONFIG
I/WfdStateTracker( 1964): handleP2pThisDeviceChanged
,D/WfdsService( 1964): WIFI_P2P_THIS_DEVICE_CHANGED_ATCION
D/WfdsService( 1964): Update P2p Interface State: 3
D/WifiNative-p2p0( 1031): SAVE_CONFIG: returned true
I/wpa_supplicant( 6274): wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
I/wpa_supplicant( 6274): wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
I/wpa_supplicant( 6274): [LGE_PATCH] driver_cmd() country:CZ
I/wpa_supplicant( 6274): p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
I/wpa_supplicant( 6274): p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
D/WifiMonitor( 1031): Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
E/WifiMonitor( 1031): WifiMonitor:wlan0 cnt=2 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
D/WifiNative-wlan0( 1031): DRIVER COUNTRY CZ: returned true
D/WfdsMonitor( 1964): Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
D/WfdsMonitor( 1964): Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
D/LGWifiP2pService( 1031): sending p2p persistent groups changed broadcast
E/WifiMonitor( 1031): handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
E/WifiMonitor( 1031): handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
D/WifiMonitor( 1031): Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
E/WifiMonitor( 1031): WifiMonitor:p2p0 cnt=3 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
E/WifiMonitor( 1031): handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
E/WifiMonitor( 1031): handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
D/WifiMonitor( 1031): Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
E/WifiMonitor( 1031): WifiMonitor:p2p0 cnt=4 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
E/WifiMonitor( 1031): handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
E/WifiMonitor( 1031): handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
E/WifiStateMachine( 1031):  DisconnectedState CMD_SET_FREQUENCY_BAND 0 0
E/WifiStateMachine( 1031):  ConnectModeState CMD_SET_FREQUENCY_BAND 0 0
E/WifiStateMachine( 1031):  DriverStartedState CMD_SET_FREQUENCY_BAND 0 0
D/WifiNative-wlan0( 1031): doBoolean: DRIVER SETBAND 0
I/wpa_supplicant( 6274): wpa_driver_nl80211_ext_driver_cmd SETBAND 0 - interface name wlan0
I/wpa_supplicant( 6274): wlan0: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
D/WifiMonitor( 1031): Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN]
E/WifiMonitor( 1031): WifiMonitor:wlan0 cnt=5 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
E/WifiMonitor( 1031): handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
E/WifiMonitor( 1031): handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
,D/WifiNative-wlan0( 1031): DRIVER SETBAND 0: returned true
D/WifiNative-wlan0( 1031): doBoolean: BSS_FLUSH 0
D/WifiNative-wlan0( 1031): BSS_FLUSH 0: returned true
D/WifiNative-wlan0( 1031): doBoolean: SCAN
D/WifiNative-wlan0( 1031): SCAN: returned false
E/WifiStateMachine( 1031):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 1 0 rt=286658  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
V/SIM_STK ( 1031): Menu title from STK is T-Mobile
,V/SIM_STK ( 1031): Menu title from STK is T-Mobile
I/ActivityManager( 1031): Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=6328 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
E/WifiStateMachine( 1031):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 1 0 rt=286690  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
E/WifiStateMachine( 1031):  DisconnectedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
E/WifiStateMachine( 1031):  ConnectModeState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
E/WifiStateMachine( 1031):  DriverStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
E/WifiStateMachine( 1031):  SupplicantStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
E/WifiStateMachine( 1031):  DefaultState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
,W/Settings( 1031): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1031): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1031): NETWORK_STATE_CHANGED_ACTION [SCANNING]
I/StatusBar.NetworkController( 1473): networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1473): mWifiConnected = false, mWifiLevel = 0
D/LGWifiP2pService( 1031): InactiveState
D/LGWifiP2pService( 1031): InactiveState{ when=-61ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1031): P2pEnabledState{ when=-61ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-p2p0( 1031): doBoolean: DRIVER COUNTRY CZ
I/wpa_supplicant( 6274): wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
I/wpa_supplicant( 6274): p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
I/wpa_supplicant( 6274): [LGE_PATCH] driver_cmd() country:CZ
I/wpa_supplicant( 6274): p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
D/StatusBar.NetworkController( 1473): refreshViews: Data not connected!! Set no data type icon / Roaming
I/wpa_supplicant( 6274): p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
D/WifiServerServiceExt( 1031): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1031): setSupplicantStateSCANNING
D/WfdsMonitor( 1964): Event [CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
D/WfdsMonitor( 1964): Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
D/WfdsMonitor( 1964): Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
D/WifiMonitor( 1031): Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
E/WifiMonitor( 1031): WifiMonitor:p2p0 cnt=6 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
E/WifiMonitor( 1031): handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
E/WifiMonitor( 1031): handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
D/WifiMonitor( 1031): Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
E/WifiMonitor( 1031): WifiMonitor:p2p0 cnt=7 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
E/WifiMonitor( 1031): handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
E/WifiMonitor( 1031): handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
D/WifiMonitor( 1031): Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
E/WifiMonitor( 1031): WifiMonitor:p2p0 cnt=8 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
E/WifiMonitor( 1031): handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
E/WifiMonitor( 1031): handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
D/WifiNative-p2p0( 1031): DRIVER COUNTRY CZ: returned true
D/LGWifiP2pService( 1031): InactiveState{ when=-48ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1031): P2pEnabledState{ when=-48ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1031): InactiveState{ when=-4ms what=139287 arg2=1 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1031): P2pEnabledState{ when=-4ms what=139287 arg2=1 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1031): DefaultState{ when=-4ms what=139287 arg2=1 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1031): InactiveState{ when=-4ms what=139285 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1031): P2pEnabledState{ when=-4ms what=139285 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
,D/LGWifiP2pService( 1031): DefaultState{ when=-4ms what=139285 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1031): InactiveState{ when=-4ms what=139287 arg2=1 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1031): P2pEnabledState{ when=-5ms what=139287 arg2=1 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1031): DefaultState{ when=-5ms what=139287 arg2=1 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1031): InactiveState{ when=-5ms what=139283 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1031): P2pEnabledState{ when=-5ms what=139283 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1031): DefaultState{ when=-5ms what=139283 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiServerServiceExt( 1031): No p2p device connected
W/WfdsService( 1964): DefaultState - msg [9441285] is not handled
W/FormManager( 6302): Network not available. Please check & try again.
,V/FormManager( 6302): Network unavailable.
V/FormManager( 6302): Network unavailable.
I/ActivityManager( 1031): Killing 5535:com.android.contacts/u0a19 (adj 15): empty #17
,D/PCSuite ( 6328): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,W/ActivityManager( 1031): getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
W/libprocessgroup( 1031): failed to open /acct/uid_10019/pid_5535/cgroup.procs: No such file or directory
D/LGBluetoothAvrcpQcomAdapter( 6236): [BTUI] installed app name: Music
,D/LGBluetoothAvrcpQcomAdapter( 6236): [BTUI] installed app name: Google Play Music
D/LGBluetoothAvrcpQcomAdapter( 6236): [BTUI] === MediaPlayerInfo (playerId:0) ===
D/LGBluetoothAvrcpQcomAdapter( 6236): [BTUI]          displayName: Music
D/LGBluetoothAvrcpQcomAdapter( 6236): [BTUI]          packageName: com.lge.music
D/LGBluetoothAvrcpQcomAdapter( 6236): [BTUI]          playState: 2 (PAUSED)
D/LGBluetoothAvrcpQcomAdapter( 6236): [BTUI] === MediaPlayerInfo (playerId:1) ===
D/LGBluetoothAvrcpQcomAdapter( 6236): [BTUI]          displayName: Google Play Music
D/LGBluetoothAvrcpQcomAdapter( 6236): [BTUI]          packageName: com.google.android.music
D/LGBluetoothAvrcpQcomAdapter( 6236): [BTUI]          playState: 2 (PAUSED)
D/LGBluetoothAvrcpQcomAdapter( 6236): [BTUI] [-] updateMediaPlayerInfo
I/BluetoothA2dpServiceJni( 6236): classInitNative
I/BluetoothA2dpServiceJni( 6236): classInitNative: succeeds
D/A2dpStateMachine( 6236): make
V/WiFiOffLoadBroadcast( 6275): WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
I/bluedroid-qcom( 6236): get_profile_interface a2dp
I/GKI_LINUX( 6236): gki_task_entry task_id=2 [A2DP-MEDIA] starting
I/LGBluetoothA2dpServiceJni( 6236): classInitNative: succeeds
I/LGBluetoothA2dpAdapter( 6236): [BTUI] getInstance : create [LGBluetoothA2dpAdapter]
D/WifiService( 1031): New client listening to asynchronous messages
D/BluetoothAdapterService( 6236): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@369476c2
D/A2dpStateMachine( 6236): Enter Disconnected: -2
I/BluetoothHidServiceJni( 6236): classInitNative: succeeds
,D/HidService( 6236): Received start request. Starting profile...
I/bluedroid-qcom( 6236): get_profile_interface hidhost
D/BluetoothAdapterService( 6236): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@369476c2
I/BluetoothHealthServiceJni( 6236): classInitNative: succeeds
D/HealthService( 6236): Received start request. Starting profile...
I/bluedroid-qcom( 6236): get_profile_interface health
I/LGBluetoothHealthServiceJni( 6236): classInitNative: succeeds
D/BluetoothAdapterService( 6236): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@369476c2
I/BluetoothPanServiceJni( 6236): classInitNative(L105): succeeds
D/PanService( 6236): Received start request. Starting profile...
D/BluetoothPanServiceJni( 6236): initializeNative(L110): pan
I/bluedroid-qcom( 6236): get_profile_interface pan
I/LGBluetoothPanAdapter( 6236): [BTUI] getInstance : create [LGBluetoothPanAdapter]
D/BluetoothAdapterService( 6236): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@369476c2
I/BtGatt.JNI( 6236): classInitNative(L901): classInitNative: Success!
,D/BtGatt.DebugUtils( 6236): handleDebugAction() action=null
D/BtGatt.GattService( 6236): Received start request. Starting profile...
D/BtGatt.GattService( 6236): start()
I/bluedroid-qcom( 6236): get_profile_interface gatt
D/BtGatt.AdvertiseManager( 6236): advertise manager created
D/BluetoothAdapterService( 6236): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@369476c2
D/LgDataFeature( 6275): LgDataFeature() Constructor: none
D/LgDataFeature( 6275): LgDataFeature() Constructor Done, null
D/BluetoothAdapterService( 6236): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@369476c2
I/LGBluetoothMapAdapter( 6236): [BTUI] getInstance : create [LGBluetoothMapAdapter]
,V/BluetoothMapService( 6236): BluetoothMapBinder()
D/BluetoothMapService( 6236): Received start request. Starting profile...
D/BluetoothMapService( 6236): start()
D/BluetoothMapEmailSettingsLoader( 6236): Found 0 applications
D/BluetoothMapEmailAppObserver( 6236): createReceiver()
D/BluetoothMapEmailAppObserver( 6236): initObservers()
D/BluetoothMapEmailAppObserver( 6236): getEnabledAccountItems()
D/WiFiOffLoadUpdatePriority( 6275): remove : truetruetrue
D/BluetoothAdapterService( 6236): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@369476c2
V/BluetoothPbapReceiver( 6236): PbapReceiver onReceive 
V/BluetoothPbapReceiver( 6236): ***********action = android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothPbapReceiver( 6236): ***********state = 11
E/WifiStateMachine( 1031):  DisconnectedState CMD_GET_CONFIGURED_NETWORKS uid=1000 1000 0 num=1
,D/HeadsetStateMachine( 6236): Proxy object connected
E/WifiStateMachine( 1031):  ConnectModeState CMD_GET_CONFIGURED_NETWORKS uid=1000 1000 0 num=1
D/LGBluetoothHfpAdapter( 6236): [BTUI] queryPhoneState
D/LGBluetoothHfpAdapter( 6236): Try to query the phonestate on bind
D/BluetoothPhoneService.BluetoothLTECall( 1867):  call mBluetoothHeadset.phoneStateChanged()
W/BluetoothHeadset( 1867): Proxy not attached to service
D/BluetoothHeadset( 1867): java.lang.Throwable
D/BluetoothHeadset( 1867): 	at android.bluetooth.BluetoothHeadset.phoneStateChanged(BluetoothHeadset.java:826)
D/BluetoothHeadset( 1867): 	at com.android.phone.BluetoothPhoneService$BluetoothLTECall.handleQueryPhoneState(BluetoothPhoneService.java:1527)
D/BluetoothHeadset( 1867): 	at com.android.phone.BluetoothPhoneService$BluetoothLTECall.access$700(BluetoothPhoneService.java:1360)
D/BluetoothHeadset( 1867): 	at com.android.phone.BluetoothPhoneService$1.handleMessage(BluetoothPhoneService.java:268)
D/BluetoothHeadset( 1867): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/BluetoothHeadset( 1867): 	at android.os.Looper.loop(Looper.java:135)
D/BluetoothHeadset( 1867): 	at android.app.ActivityThread.main(ActivityThread.java:5274)
D/BluetoothHeadset( 1867): 	at java.lang.reflect.Method.invoke(Native Method)
D/BluetoothHeadset( 1867): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/BluetoothHeadset( 1867): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
D/BluetoothHeadset( 1867): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
E/WifiStateMachine( 1031):  DisconnectedState CMD_SAVE_CONFIG uid=1000 0 0
D/BluetoothAdapterService( 6236): Profile still not running:com.android.bluetooth.gatt.GattService
E/WifiStateMachine( 1031):  ConnectModeState CMD_SAVE_CONFIG uid=1000 0 0
D/WifiNative-wlan0( 1031): doBoolean: SAVE_CONFIG
D/HeadsetStateMachine( 6236): Disconnected process message: 10, size: 0
D/HeadsetPhoneState( 6236): sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
D/HeadsetStateMachine( 6236): Disconnected process message: 11, size: 0
D/BluetoothAdapterService( 6236): Profile still not running:com.android.bluetooth.gatt.GattService
D/WifiNative-wlan0( 1031): SAVE_CONFIG: returned true
D/WiFiOffLoadUpdatePriority( 6275): remove1
V/WiFiOffLoadSharedPrefsUtils( 6275): save remove
D/BluetoothAdapterService( 6236): Profile still not running:com.android.bluetooth.gatt.GattService
,D/BluetoothAdapterService( 6236): Profile still not running:com.android.bluetooth.gatt.GattService
V/PanService( 6236): [BTUI] SIM Extra State :ABSENT
D/BluetoothAdapterService( 6236): Profile still not running:com.android.bluetooth.gatt.GattService
D/WiFiOffLoadBroadcast( 6275): mLastConnectedNetwork from SharedPrefsUtils for wifioffloading : null
D/WiFiOffLoadBroadcast( 6275): S: false, R: false
E/WifiStateMachine( 1031):  DisconnectedState CMD_GET_CONFIGURED_NETWORKS uid=1000 1000 0 num=1
E/WifiStateMachine( 1031):  ConnectModeState CMD_GET_CONFIGURED_NETWORKS uid=1000 1000 0 num=1
D/BluetoothAdapterService( 6236): Profile still not running:com.android.bluetooth.map.BluetoothMapService
V/BluetoothMapService( 6236): Handler(): got msg=1
D/WiFiOffLoadUpdatePriority( 6275): saved SSID: "NG700"
D/WiFiOffLoadUpdatePriority( 6275): connected SSID: null
D/WiFiOffLoadUpdatePriority( 6275): private wpa: "NG700" 300
D/BluetoothAdapterState( 6236): CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
I/bluedroid-qcom( 6236): enable
,I/GKI_LINUX( 6236): gki_task_entry task_id=0 [BTU] starting
I/bt-btu  ( 6236): btu_task pending for preload complete event
I/bt_hci_bdroid( 6236): init
D/WifiServiceImplEx( 1031): addOrUpdateNetwork pid=6275, uid=1000, packageName=android.uid.system:1000
E/addOrUpdateNetwork( 1031):  uid = 1000 SSID "NG700" nid=0
I/bt_vendor( 6236): bt-vendor : init
I/bt_vendor( 6236): bt-vendor : get_bt_soc_type
E/bt_vendor( 6236): get_bt_soc_type: Failed to get soc type
I/bt_vendor( 6236): init: Local BD Address : c0:64:73:54:3f:58
D/bt_userial_mct( 6236): userial_init
E/WifiStateMachine( 1031):  DisconnectedState CMD_ADD_OR_UPDATE_NETWORK uid=1000 0 0 "NG700"WPA_PSK prio=300 status=2
E/WifiStateMachine( 1031):  ConnectModeState CMD_ADD_OR_UPDATE_NETWORK uid=1000 0 0 "NG700"WPA_PSK prio=300 status=2
E/WifiConfigStore( 1031):  key="NG700"WPA_PSK netId=0 uid=0/1000
D/WifiServerServiceExt( 1031): addOrUpdateNetwork: mThisIsFirstEnableing = false
D/WifiNative-wlan0( 1031): doBoolean: SET_NETWORK 0 ssid 4e47373030
D/bt_hci_bdroid( 6236): set_power 1
I/bt_vendor( 6236): bt-vendor : BT_VND_OP_POWER_CTRL: On
I/bt_vendor( 6236): Starting hciattach daemon
I/bt_vendor( 6236): try to set true
I/ActivityManager( 1031): Start proc com.lge.lifetracker for broadcast com.lge.lifetracker/.receiver.HealthDeviceReceiver: pid=6362 uid=10037 gids={50037, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
W/sh      ( 6363): type=1400 audit(0.0:157): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6828 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
W/sh      ( 6363): type=1400 audit(0.0:158): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6828 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,I/qcom-bluetooth( 6372): /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  
,D/WifiNative-wlan0( 1031): SET_NETWORK 0 ssid 4e47373030: returned true
,D/WifiNative-wlan0( 1031): doBoolean: SET_NETWORK 0 key_mgmt WPA-PSK
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
E/WifiConfigStore( 1031): writeIpAndProxyConfigurationsOnChange: "NG700" -> "NG700" path: /data/misc/wifi/ipconfig.txt
E/WifiConfigStore( 1031):  writeKnownNetworkHistory() num networks:1 needWrite=false
D/WiFiOffLoadUpdatePriority( 6275):  ssid "NG700" prio 300
D/WiFiOffLoadUpdatePriority( 6275): configuration updated: 0
E/WifiStateMachine( 1031):  DisconnectedState CMD_SAVE_CONFIG uid=1000 0 0
E/WifiStateMachine( 1031):  ConnectModeState CMD_SAVE_CONFIG uid=1000 0 0
D/WifiNative-wlan0( 1031): doBoolean: SAVE_CONFIG
,D/WifiNative-wlan0( 1031): SAVE_CONFIG: returned true
D/WiFiOffLoadUpdatePriority( 6275): configuration saved: true
D/UsbSettingsReceiver( 6275): [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
D/UsbSettingsReceiver( 6275): [AUTORUN] sys.usb.config = ptp_only,adb
D/UsbSettingsReceiver( 6275): [AUTORUN] sys.usb.state = ptp_only,adb
D/UsbSettingsReceiver( 6275): [AUTORUN] persist.sys.usb.config = ptp_only,adb
D/UsbSettingsReceiver( 6275): [AUTORUN] onReceive() : app userid = 0, current userid = 0
D/UsbSettingsControl( 6275): [AUTORUN] getUsbConnected() : connected=true
D/UsbSettingsReceiver( 6275): [AUTORUN] onReceive() : availableList=[]
D/UsbSettingsReceiver( 6275): [AUTORUN] onReceive() : activeList=[]
D/UsbSettingsReceiver( 6275): [AUTORUN] onReceive() : errorList=[]
D/UsbSettingsControl( 6275): [AUTORUN] isAutorunTimer() : mAutorunChanging=false
D/UsbSettingsControl( 6275): [AUTORUN] setTetherStatus() : status=false
I/qcom-bluetooth( 6386): /system/etc/init.qcom.bt.sh: Transport : smd 
D/PCSuite ( 6328): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,I/qcom-bluetooth( 6387): /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
V/WiFiOffLoadBroadcast( 6275): WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
W/FormManager( 6302): Network not available. Please check & try again.
V/FormManager( 6302): Network unavailable.
,D/WiFiOffLoadBroadcast( 6275): MCCMNC not supported: null
D/LGDMClient( 3985): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
D/LGDMClient( 3985): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
W/ContextImpl( 3985): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
I/qcom-bluetooth( 6392): /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
W/ContextImpl( 3985): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
I/qcom-bluetooth( 6393): /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> 
,D/LGDMClient( 3985): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=3, isUserType=1
D/PostponalbeReceiver( 5170): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
I/PCSuite ( 6328): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
I/qcom-bluetooth( 6397): /system/etc/init.qcom.bt.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
E/wpa_supplicant( 6274): USIM:  scard_init function
D/LGDMClient( 3985): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
D/LGDMClient( 3985): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
I/wpa_supplicant( 6274): Trying to associate with SSID 'NG700'
E/WifiMonitor( 1031): WifiMonitor:wlan0 cnt=9 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
E/WifiMonitor( 1031): handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
D/WifiMonitor( 1031): Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
E/WifiMonitor( 1031): WifiMonitor:wlan0 cnt=10 dispatchEvent: WPS-AP-AVAILABLE 
W/WifiMonitor( 1031): couldn't identify event type - WPS-AP-AVAILABLE 
D/WifiMonitor( 1031): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
E/WifiMonitor( 1031): WifiMonitor:wlan0 cnt=11 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
V/FormManager( 6302): Network unavailable.
,E/WifiStateMachine( 1031):  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=0 bcn=0
E/WifiStateMachine( 1031):  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=0 bcn=0
,E/WifiStateMachine( 1031):  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=0 bcn=0
E/WifiStateMachine( 1031):  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=0 bcn=0
I/WifiNative-HAL( 1031): startHal
E/wifi    ( 1031): getStaticLongField sWifiHalHandle 0x9893b8cc
E/ActivityThread( 6362): Failed to find provider info for com.lge.lgaccount.provider
E/WifiHAL ( 1031): Could not connect handle
D/wifi    ( 1031): halHandle = 0x0, mVM = 0xb487c280, mCls = 0x700fba
I/WifiNative-HAL( 1031): Could not start hal
D/WifiNative-wlan0( 1031): doString: [BSS RANGE=0- MASK=0x21987]
W/LG Account v2.2( 6362): No ProfileInfo entries
I/LG Account v2.2( 6362): isEnabled: false
I/Feature ( 6362): [Lifetracker]ver: 4.21.112(40211120)
I/Feature ( 6362): [Lifetracker]Country: EU
I/Feature ( 6362): [Lifetracker]Operator: OPEN
I/Feature ( 6362): [Lifetracker]Ranking support: false
I/Feature ( 6362): [Lifetracker]Comfort support: false
I/Feature ( 6362): [Lifetracker]Accessory: true
I/Feature ( 6362): [Lifetracker]Health device: true
I/Feature ( 6362): [Lifetracker]Extra Pedometer: false
I/Feature ( 6362): [Lifetracker]Blood glucose device: false
I/Feature ( 6362): [Lifetracker]Device Number: 3
D/PCSuite ( 6328): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 6328): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
I/qcom-bluetooth( 6400): /system/etc/init.qcom.bt.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> 
E/WifiStateMachine( 1031):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 11 0 rt=286957  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
V/WiFiOffLoadBroadcast( 6275): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
E/WifiStateMachine( 1031):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 11 0 rt=286963  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
,I/libmdmdetect( 6403): ESOC framework not supported
I/ActivityManager( 1031): Killing 5856:com.lge.email/u0a23 (adj 15): empty #17
E/Diag_Lib( 6403):  Diag_LSM_Init: Failed to open handle to diag driver, error = 13
D/WiFiOffLoadBroadcast( 6275): MCCMNC not supported: null
D/bthci_qcomm_linux( 6403): [BTUI] bt_hci_qcomm_pfal_get_bdaddress: Get BDADDR from bluedroid prop (58:3F:54:73:64:C0)
D/bthci_qcomm_common( 6403): [BTUI] bt_hci_qcomm_init:
D/bthci_qcomm_common( 6403): [BTUI]     BDADDR: 58:3F:54:73:64:C0
D/bthci_qcomm_common( 6403): [BTUI]     BR/EDR: Class 1
D/bthci_qcomm_common( 6403): [BTUI]     LE: Class 2
D/bthci_qcomm_common( 6403): [BTUI]     Ref Clock: 32M
D/btqsocnvmtags( 6403): [BTUI] init_riva_entries: set NORMAL power settings
W/libprocessgroup( 1031): failed to open /acct/uid_10023/pid_5856/cgroup.procs: No such file or directory
,I/StatusBar.NetworkController( 1473): networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/StatusBar.NetworkController( 1473): mWifiConnected = false, mWifiLevel = 0
W/Settings( 1031): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1031): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1031): NETWORK_STATE_CHANGED_ACTION [SCANNING]
D/StatusBar.NetworkController( 1473): refreshViews: Data not connected!! Set no data type icon / Roaming
W/Settings( 1031): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1031): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1031): NETWORK_STATE_CHANGED_ACTION [CONNECTING]
D/WifiServerServiceExt( 1031): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1031): setSupplicantStateASSOCIATING
I/StatusBar.NetworkController( 1473): networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1473): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1473): refreshViews: Data not connected!! Set no data type icon / Roaming
D/BluetoothPermissionRequest( 6275): onReceive
D/LGBluetoothFeatureConfig( 6275):  get() - isFeatureLoaded : false
D/BluetoothManagerService( 1031): Message: 20
,D/BluetoothManagerService( 1031): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@17407486:true
I/ActivityManager( 1031): Killing 5561:com.android.gallery3d/u0a27 (adj 15): empty #17
D/LGBluetoothResetSettingReceiver( 6275): return without doing reset settings.
I/wpa_supplicant( 6274): wlan0: Associated with c0:ff:d4:d3:aa:48
,D/WifiMonitor( 1031): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
E/WifiMonitor( 1031): WifiMonitor:wlan0 cnt=12 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
D/WifiMonitor( 1031): Event [IFNAME=wlan0 Associated with c0:ff:d4:d3:aa:48]
E/WifiMonitor( 1031): WifiMonitor:wlan0 cnt=13 dispatchEvent: Associated with c0:ff:d4:d3:aa:48
D/WifiMonitor( 1031): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
,E/WifiMonitor( 1031): WifiMonitor:wlan0 cnt=14 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
,E/WifiStateMachine( 1031):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 12 0 rt=287057  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
E/WifiStateMachine( 1031):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 12 0 rt=287058  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
E/WifiStateMachine( 1031):  DisconnectedState CMD_ASSOCIATED_BSSID 13 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=287058
E/WifiStateMachine( 1031):  ConnectModeState CMD_ASSOCIATED_BSSID 13 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=287059
E/WifiStateMachine( 1031):  DriverStartedState CMD_ASSOCIATED_BSSID 13 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=287059
E/WifiStateMachine( 1031):  SupplicantStartedState CMD_ASSOCIATED_BSSID 13 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=287059
E/WifiStateMachine( 1031):  DefaultState CMD_ASSOCIATED_BSSID 13 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=287059
E/WifiStateMachine( 1031):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 14 0 rt=287060  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: FOUR_WAY_HANDSHAKE
D/WifiMonitor( 1031): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
I/wpa_supplicant( 6274): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
E/WifiMonitor( 1031): WifiMonitor:wlan0 cnt=15 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
I/wpa_supplicant( 6274): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
D/WifiMonitor( 1031): Event [IFNAME=wlan0 WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]]
D/LGBluetoothOppAdapter( 6236): [BTUI] getInstance : create [LGBluetoothOppAdapter]
W/libprocessgroup( 1031): failed to open /acct/uid_10027/pid_5561/cgroup.procs: No such file or directory
E/WifiMonitor( 1031): WifiMonitor:wlan0 cnt=16 dispatchEvent: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
W/WifiMonitor( 1031): couldn't identify event type - WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
I/rmt_storage(  315): rmt_storage_connect_cb: clnt_h=0x5 conn_h=0xb6403090
I/rmt_storage(  315): rmt_storage_rw_iovec_cb: /boot/modem_fs2: clnt_h=0x2: req_h=0x9 msg_id=3: R/W request received
I/rmt_storage(  315): wakelock acquired: 1, error no: 42
,I/rmt_storage(  315): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 Unblock worker thread (th_id: -1236806912)
D/Tethering( 1031): sendTetherStateChangedBroadcast 1, 0, 0
D/WifiMonitor( 1031): Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]]
E/WifiMonitor( 1031): WifiMonitor:wlan0 cnt=17 dispatchEvent: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
E/WifiMonitor( 1031): handleEvent 1  Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
D/WifiMonitor( 1031): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1031): WifiMonitor:wlan0 cnt=18 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
E/WifiStateMachine( 1031):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 14 0 rt=287075  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: FOUR_WAY_HANDSHAKE
I/StatusBar.NetworkController( 1473): networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
W/Settings( 1031): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/StatusBar.NetworkController( 1473): mWifiConnected = false, mWifiLevel = 0
W/Settings( 1031): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1031): NETWORK_STATE_CHANGED_ACTION [CONNECTING]
W/Settings( 1031): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1031): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1031): NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
D/StatusBar.NetworkController( 1473): refreshViews: Data not connected!! Set no data type icon / Roaming
,E/WifiStateMachine( 1031):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 15 0 rt=287086  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: GROUP_HANDSHAKE
I/StatusBar.NetworkController( 1473): networkInfo=[type: WIFI[], state: CONNECTING/AUTHENTICATING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1473): mWifiConnected = false, mWifiLevel = 0
E/WifiStateMachine( 1031):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 15 0 rt=287087  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: GROUP_HANDSHAKE
E/WifiStateMachine( 1031):  DisconnectedState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=287087
E/WifiStateMachine( 1031):  ConnectModeState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=287088
D/StatusBar.NetworkController( 1473): refreshViews: Data not connected!! Set no data type icon / Roaming
D/WifiNative-wlan0( 1031): doString: [STATUS]
D/WifiMonitor( 1031): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
D/WifiServerServiceExt( 1031): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1031): setSupplicantStateASSOCIATED
E/WifiMonitor( 1031): WifiMonitor:wlan0 cnt=19 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/WifiNative-wlan0( 1031):    returned bssid=c0:ff:d4:d3:aa:48 ssid=NG700 id=0 mode=station pairwise_cipher=CCMP group_cipher=CCMP key_mgmt=WPA2-PSK wpa_state=COMPLETED p2p_device_address=02:9a:02:7b:60:ac address=c4:9a:02:7b:60:ac uuid=530d3fd0-1ba3-5409-a336-ff4e42af59a2
I/WifiServiceExtension( 1031): setVHTCapabilityType  : false
I/WifiServerServiceExt( 1031): wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
I/WifiServerServiceExt( 1031): setKeepAlivePacketInterval msec : 60
,V/BluetoothFtpReceiver( 6236): BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
I/StatusBar.NetworkController( 1473): networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1473): mWifiConnected = false, mWifiLevel = 0
W/Settings( 1031): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1031): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1031): NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
D/StatusBar.NetworkController( 1473): refreshViews: Data not connected!! Set no data type icon / Roaming
W/Settings( 1031): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1031): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1031): NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
I/StatusBar.NetworkController( 1473): networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1473): mWifiConnected = false, mWifiLevel = 0
V/BluetoothSapReceiver( 6236): [BTUI] checkServiceStart
D/StatusBar.NetworkController( 1473): refreshViews: Data not connected!! Set no data type icon / Roaming
V/BluetoothSapReceiver( 6236): [BTUI] region:EU country:EU
V/BluetoothSapReceiver( 6236): SapReceiver onReceive 
D/QRemote ( 5995): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
V/BluetoothSapReceiver( 6236): action = android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothSapReceiver( 6236):  Bluetooth Adapter state = 11
D/QRemote ( 5995): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,D/ConnectivityService( 1031): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
D/ConnectivityService( 1031): Got NetworkAgent Messenger
D/ConnectivityService( 1031): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
D/ConnectivityService( 1031): NetworkAgent connected
E/WifiConfigStore( 1031): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/WifiNative-wlan0( 1031): doBoolean: SET_NETWORK 0 bssid any
D/WifiNative-wlan0( 1031): SET_NETWORK 0 bssid any: returned true
D/WifiNative-wlan0( 1031): doBoolean: SAVE_CONFIG
I/rmt_storage(  315): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0x9 msg_id=3: Bytes written = 1572864
I/rmt_storage(  315): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0x9 msg_id=3: Send response: res=0 err=0
I/rmt_storage(  315): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 About to block rmt_storage client thread (th_id: -1236806912) wakelock released: 1, error no: 0
I/rmt_storage(  315): 
,I/rmt_storage(  315): rmt_storage_disconnect_cb: clnt_h=0x0x5 conn_h=0x0xb6403090
E/Diag_Lib(  888): [IMS_FATAL]| 3347 | 908 |ims-rtp-daemon ims_rtp_qmi_handler_thread_func waiting on select thread>
D/WifiNative-wlan0( 1031): SAVE_CONFIG: returned true
E/WifiConfigStore( 1031): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/WifiNative-wlan0( 1031): doBoolean: SET_NETWORK 0 bssid any
D/WifiNative-wlan0( 1031): SET_NETWORK 0 bssid any: returned true
D/WifiNative-wlan0( 1031): doBoolean: SAVE_CONFIG
D/WifiNative-wlan0( 1031): SAVE_CONFIG: returned true
,D/CommandListener(  323): Setting iface cfg
I/ActivityManager( 1031): Start proc com.lge.settings.easy for broadcast com.lge.settings.easy/com.lge.settings.bluetooth.LGBluetoothProfileConnectionReceiver: pid=6411 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,I/QRemote ( 5995): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
E/WifiStateMachine( 1031): Start Dhcp Watchdog 1
D/DhcpStateMachine( 1031): StoppedState
D/DhcpStateMachine( 1031): StoppedState{ when=0 what=196609 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine( 1031): WaitBeforeStartState
E/WifiStateMachine( 1031):  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 18 0 rt=287165  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine( 1031):  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 18 0 rt=287165  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine( 1031):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 18 0 rt=287165  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
V/[BNRBootReceiver]( 5956): boot receiver action = android.net.wifi.p2p.CONNECTION_STATE_CHANGE
D/BNRAndroBeam( 5956): [BnR DirectBeam] Android Direct Beam(NFC) Connection changed
D/WifiServerServiceExt( 1031): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1031): setSupplicantStateFOUR_WAY_HANDSHAKE
E/WifiStateMachine( 1031):  ObtainingIpState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1031):  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1031):  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1031):  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1031):  DefaultState CMD_TETHER_STATE_CHANGE 0 0
D/WifiServerServiceExt( 1031): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1031): setSupplicantStateGROUP_HANDSHAKE
E/WifiStateMachine( 1031):  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 19 0 rt=287172  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
V/[BNRBootReceiver]( 5956): Boot Receiver Return
E/WifiStateMachine( 1031):  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 19 0 rt=287172  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine( 1031):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 19 0 rt=287174  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
,D/PostponalbeReceiver( 5170): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
E/WifiStateMachine( 1031):  ObtainingIpState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:-1866424760] from screen [on:0 period:-1866424760]
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:2] from screen [on:0 period:-1866424758]
I/WifiNative-HAL( 1031): startHal
E/wifi    ( 1031): getStaticLongField sWifiHalHandle 0x9893b8bc
E/WifiHAL ( 1031): Could not connect handle
D/wifi    ( 1031): halHandle = 0x0, mVM = 0xb487c280, mCls = 0x602196
I/WifiNative-HAL( 1031): Could not start hal
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
V/WiFiOffLoadBroadcast( 6275): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
I/art     (  360): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 338us total 16.344ms
D/StatusBar.NetworkController( 1473): refreshViews: Data not connected!! Set no data type icon / Roaming
D/WiFiOffLoadBroadcast( 6275): MCCMNC not supported: null
D/ConnectivityService( 1031): updateNetworkScore for NetworkAgentInfo [WIFI () - 100] to 60
E/WifiStateMachine( 1031):  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
,E/WifiStateMachine( 1031):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1031):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1031):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1031):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
D/ConnectivityService( 1031): Update of LinkProperties for NetworkAgentInfo [WIFI () - 100]; created=false
E/WifiStateMachine( 1031):  ObtainingIpState CMD_PRE_DHCP_ACTION 0 0 txpkts=1,0,0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_PRE_DHCP_ACTION 0 0 txpkts=1,0,0
D/WifiNative-wlan0( 1031): doBoolean: DRIVER SETSUSPENDMODE 0
D/QRemote ( 5995): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 5995): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 5995): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
V/WiFiOffLoadBroadcast( 6275): WiFiOffLoadBroadcast: android.net.wifi.SCAN_RESULTS
D/WiFiOffLoadBroadcast( 6275): Not supported operator for automatic switch
I/art     (  360): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 278us total 14.497ms
D/PostponalbeReceiver( 5170): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,V/WiFiOffLoadBroadcast( 6275): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
I/art     (  360): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 275us total 12.804ms
W/ResourcesManager( 6411): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
D/WiFiOffLoadBroadcast( 6275): MCCMNC not supported: null
I/wpa_supplicant( 6274): wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 0
D/WifiNative-wlan0( 1031): DRIVER SETSUSPENDMODE 0: returned true
D/WifiNative-wlan0( 1031): doBoolean: SET ps 0
,D/WifiNative-wlan0( 1031): SET ps 0: returned true
D/WifiNative-wlan0( 1031): doBoolean: DRIVER BTCOEXMODE 1
I/wpa_supplicant( 6274): wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 1
D/WifiNative-wlan0( 1031): DRIVER BTCOEXMODE 1: returned true
E/WifiStateMachine( 1031): CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
V/DhcpStateMachine( 1031): Current State is mWaitBeforeStartState.
D/LGWifiP2pService( 1031): InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@6c4694b target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1031): P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@6c4694b target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine( 1031): WaitBeforeStartState{ when=0 what=196615 target=com.android.internal.util.StateMachine$SmHandler }
V/LgDhcpStateMachineHelper( 1031): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
V/LgDhcpStateMachineHelper( 1031): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700" is not exist.
D/DhcpStateMachine( 1031): DHCP Start wake lock is acquired.
D/QRemote ( 5995): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 5995): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1031): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1031): setSupplicantStateCOMPLETED
I/QRemote ( 5995): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
D/PostponalbeReceiver( 5170): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
V/WiFiOffLoadBroadcast( 6275): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6275): MCCMNC not supported: null
D/AuthorizationBluetoothService( 2129): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
D/QRemote ( 5995): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 5995): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 5995): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,D/UsbSettingsReceiver( 6275): [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
D/UsbSettingsReceiver( 6275): [AUTORUN] sys.usb.config = ptp_only,adb
D/UsbSettingsReceiver( 6275): [AUTORUN] sys.usb.state = ptp_only,adb
D/UsbSettingsReceiver( 6275): [AUTORUN] persist.sys.usb.config = ptp_only,adb
D/UsbSettingsReceiver( 6275): [AUTORUN] onReceive() : app userid = 0, current userid = 0
D/UsbSettingsControl( 6275): [AUTORUN] getUsbConnected() : connected=true
D/UsbSettingsReceiver( 6275): [AUTORUN] onReceive() : availableList=[wlan0]
D/UsbSettingsReceiver( 6275): [AUTORUN] onReceive() : activeList=[]
D/UsbSettingsReceiver( 6275): [AUTORUN] onReceive() : errorList=[]
D/UsbSettingsControl( 6275): [AUTORUN] isAutorunTimer() : mAutorunChanging=false
D/UsbSettingsReceiver( 6275): [AUTORUN] onReceive() : TetherState Changed=wlan0
D/UsbSettingsControl( 6275): [AUTORUN] setTetherStatus() : status=false
D/PostponalbeReceiver( 5170): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
V/WiFiOffLoadBroadcast( 6275): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6275): MCCMNC not supported: null
D/QRemote ( 5995): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 5995): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 5995): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
D/PostponalbeReceiver( 5170): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
V/WiFiOffLoadBroadcast( 6275): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6275): MCCMNC not supported: null
D/QRemote ( 5995): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 5995): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 5995): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
D/PostponalbeReceiver( 5170): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,V/WiFiOffLoadBroadcast( 6275): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6275): MCCMNC not supported: null
D/QRemote ( 5995): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,D/QRemote ( 5995): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 5995): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,D/PostponalbeReceiver( 5170): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
V/WiFiOffLoadBroadcast( 6275): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6275): MCCMNC not supported: null
D/QRemote ( 5995): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,D/QRemote ( 5995): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 5995): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
I/ActivityManager( 1031): Killing 5759:com.android.defcontainer/u0a4 (adj 15): empty #17
W/libprocessgroup( 1031): failed to open /acct/uid_10004/pid_5759/cgroup.procs: No such file or directory
,D/DhcpStateMachine( 1031): DHCPV4 request on wlan0
,V/LgDhcpStateMachineHelper( 1031): [bssid] hash key :c0:ff:d4:d3:aa:48
D/LgDhcpStateMachineHelper( 1031): dhcp.ap.macaddress = c0:ff:d4:d3:aa:48
W/dhcpcd  ( 6429): type=1400 audit(0.0:159): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6828 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,W/dhcpcd  ( 6429): type=1400 audit(0.0:160): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6828 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
I/dhcpcd  ( 6429): version 5.5.6 starting
E/dhcpcd  ( 6429): get_duid: m
,D/dhcpcd  ( 6429): wlan0: using ClientID 01:c4:9a:02:7b:60:ac
,D/dhcpcd  ( 6429): wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason PREINIT
D/dhcpcd  ( 6429): getUsingAPMacAddress: c0:ff:d4:d3:aa:48 , return 1
,D/dhcpcd  ( 6429): [read_lease] unlink /data/misc/dhcp/dhcpcd-wlan0.lease, link /data/misc/dhcp/dhcpcd-wlan0-c0:ff:d4:d3:aa:48.lease2
D/dhcpcd  ( 6429): wlan0: reading lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
,I/dhcpcd  ( 6429): wlan0: rebinding lease of 192.168.1.125
D/dhcpcd  ( 6429): wlan0: sending REQUEST (xid 0xa2651e1d), next in 4.38 seconds
E/QC-QMI  ( 6403): qmi_client [6403] 13: failed to locate client data
,E/QC-QMI  (  439): qmuxd: RX on fd=32 returned error=0 errno[2:No such file or directory]
E/QC-QMI  (  439): QMUX qmux_client_id=13 not found in qmux client list, unable to remove
I/qcom-bluetooth( 6445): /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 58:3f:54:73:64:c0 
,I/qcom-bluetooth( 6446): /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,I/bt_vendor( 6236): bluetooth satus is on
D/bt_hci_bdroid( 6236): preload
,D/bt_userial_mct( 6236): userial_open(port:0)
I/bt_vendor( 6236): bt-vendor : BT_VND_OP_USERIAL_OPEN
I/bt_vendor( 6236): Done intiailizing UART
I/bt_vendor( 6236): Done intiailizing UART
I/bt_userial_mct( 6236): CMD=66, EVT=66, ACL_Out=67, ACL_In=67
I/bt_vendor( 6236): Bluetooth Firmware and transport layer are initialized
I/bt-btu  ( 6236): btu_task received preload complete event
W/bt-l2cap( 6236): L2CAP - L2CA_Register() called for PSM: 0x0001
W/bt-l2cap( 6236): L2CAP - L2CA_Register() called for PSM: 0x001f
W/bt-l2cap( 6236): L2CAP - L2CA_Register() called for PSM: 0x0003
,D/bt_userial_mct( 6236): Entering userial_read_thread()
I/        ( 6236): BTE_InitTraceLevels -- TRC_HCI
,I/        ( 6236): BTE_InitTraceLevels -- TRC_L2CAP
I/        ( 6236): BTE_InitTraceLevels -- TRC_RFCOMM
I/        ( 6236): BTE_InitTraceLevels -- TRC_AVDT
I/        ( 6236): BTE_InitTraceLevels -- TRC_AVRC
I/        ( 6236): BTE_InitTraceLevels -- TRC_A2D
I/        ( 6236): BTE_InitTraceLevels -- TRC_BNEP
I/        ( 6236): BTE_InitTraceLevels -- TRC_BTM
I/        ( 6236): BTE_InitTraceLevels -- TRC_HID_HOST
I/        ( 6236): BTE_InitTraceLevels -- TRC_GAP
I/        ( 6236): BTE_InitTraceLevels -- TRC_PAN
I/        ( 6236): BTE_InitTraceLevels -- TRC_SDP
I/        ( 6236): BTE_InitTraceLevels -- TRC_GATT
I/        ( 6236): BTE_InitTraceLevels -- TRC_SMP
I/        ( 6236): BTE_InitTraceLevels -- TRC_BTAPP
I/        ( 6236): BTE_InitTraceLevels -- TRC_BTIF
W/bt-btm  ( 6236): btm_decode_ext_features_page Secure conn Controller support Enabled
E/bt-btm  ( 6236): BTM_SecRegister:p_cb_info->p_le_callback == 0xa01da061 
E/bt-btm  ( 6236): BTM_SecRegister: btm_cb.api.p_le_callback = 0xa01da061 
,E/bt-btif ( 6236): Calling BTA_HhEnable
E/bt-btif ( 6236): btif_storage_get_adapter_property service_mask:0x2140040
D/BluetoothAdapterProperties( 6236): Address is:58:3F:54:73:64:C0
D/BluetoothManagerService( 1031): Bluetooth Adapter name changed to G3-1
D/BluetoothManagerService( 1031): Stored Bluetooth name: G3-1
,D/BluetoothAdapterProperties( 6236): Name is: G3-1
D/BluetoothAdapterProperties( 6236): Scan Mode:20
D/BluetoothAdapterProperties( 6236): Discoverable Timeout:120
D/bt_hci_bdroid( 6236): postload
E/bt_mct  ( 6236): hci lib postload completed
D/bte_conf( 6236): Device ID record 1 : primary
D/bte_conf( 6236):   vendorId            = 00c4
D/bte_conf( 6236):   vendorIdSource      = 0001
D/bte_conf( 6236):   product             = 13a1
D/bte_conf( 6236):   version             = 1000
D/bte_conf( 6236):   clientExecutableURL = 
D/bte_conf( 6236):   serviceDescription  = 
D/bte_conf( 6236):   documentationURL    = 
D/bte_conf( 6236): bte_load_did_conf no section named DID2.
W/sh      ( 6450): type=1400 audit(0.0:161): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6828 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,D/BluetoothAdapterState( 6236): CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
D/BluetoothAdapterProperties( 6236): ScanMode =  20
D/BluetoothAdapterProperties( 6236): State =  11
D/BluetoothAdapterProperties( 6236): mDiscoverableTimeout = 120
V/LGBluetoothServiceAdapter( 6236): [BTUI] state:11, scanmode:20, timeout:120
D/BluetoothAdapterProperties( 6236): Setting state to 12
I/BluetoothAdapterState( 6236): Bluetooth adapter state changed: 11-> 12
W/sh      ( 6450): type=1400 audit(0.0:162): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6828 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
D/BluetoothManagerService( 1031): Message: 60
D/BluetoothManagerService( 1031): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
,I/BluetoothAdapterState( 6236): Entering On State
D/btif_config_util( 6236): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,D/LGBluetoothServiceAdapter( 6236): [BTUI] OnState
D/LGBluetoothServiceAdapter( 6236): [BTUI]         global_name: G3-1
D/LGBluetoothServiceAdapter( 6236): [BTUI]         local_name: G3-1
D/BluetoothAdapterService( 6236): [BTUI] autoConnect() : not allowed
D/BluetoothManagerService( 1031): Broadcasting onBluetoothStateChange(true) to 5 receivers.
D/BluetoothHeadset( 1031): onBluetoothStateChange: up=true
D/BluetoothA2dp( 1031): onBluetoothStateChange: up=true
,D/BluetoothHeadset( 1867): onBluetoothStateChange: up=true
D/BluetoothHeadset( 1867): onBluetoothStateChange: up=true
D/BluetoothHeadset( 1867): onBluetoothStateChange: up=true
D/BluetoothManagerService( 1031): BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
,E/BluetoothManagerService( 1031): Fail to bind to: Intent { act=android.bluetooth.IQBluetooth }
D/BluetoothManagerService( 1031): Bluetooth State Change Intent: 11 -> 12
D/LGBluetoothDeviceModeControllManager( 6236): [BTUI] checkDeviceModeAndSet, sinkMode : false
I/[SystemUI]BluetoothHandler( 1473): Receive : BluetoothAdapter.ACTION_STATE_CHANGED
D/LGBluetoothAPIService( 1964): [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
,D/LGBluetoothAPIService( 1964): Message: 1
D/LGBluetoothAPIService( 1964): MESSAGE_BOOT_COMPLETED
D/BluetoothAdapterProperties( 6236): Discoverable Timeout:120
D/LGBluetoothDeviceModeControllManager( 6236): adapterPropertyChangedCallback on  LGAdapter : do nothing - 9
I/BluetoothMapService( 6236): onReceive: android.bluetooth.adapter.action.STATE_CHANGED
D/BluetoothMapService( 6236): STATE_ON
,V/BluetoothMapService( 6236): Handler(): got msg=1
D/BluetoothMapMasInstance( 6236): Map Service startRfcommSocketListener
W/bt-l2cap( 6236): L2CAP - L2CA_Register() called for PSM: 0x0019
W/bt-l2cap( 6236): L2CAP - L2CA_Register() called for PSM: 0x0017
W/bt-l2cap( 6236): L2CAP - L2CA_Register() called for PSM: 0x001b
,W/bt-l2cap( 6236): L2CAP - L2CA_Register() called for PSM: 0x0011
W/bt-l2cap( 6236): L2CAP - L2CA_Register() called for PSM: 0x0013
W/bt-l2cap( 6236): L2CAP - L2CA_Register() called for PSM: 0x000f
D/BluetoothPanServiceJni( 6236): control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
D/BluetoothManagerService( 1031): Message: 40
D/BluetoothManagerService( 1031): MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
D/BluetoothAdapterService( 6236): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@369476c2
V/BluetoothPbapService( 6236): Pbap Service onCreate
V/BluetoothPbapService( 6236): Starting PBAP service
D/LGBluetoothPbapAdapter( 6236): [BTUI] getInstance : create
V/BluetoothPbapService( 6236): action: android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothPbapService( 6236): state: 12
V/BluetoothPbapService( 6236): Handler(): got msg=1
V/BluetoothPbapService( 6236): Pbap Service startRfcommSocketListener
W/bt-smp  ( 6236): Key(LSB ~ MSB) = 0a 3c a6 fe eb 17 6a 79 a6 1f 0a 0b f9 50 a0 5f 
W/bt-smp  ( 6236): Plain text(LSB ~ MSB) = 23 1a 6b 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 6236): Encrypted text(LSB ~ MSB) = 24 88 db 8c a6 3a 89 c6 61 fc d3 b3 0b 77 42 4c 
W/bt-btm  ( 6236): Stopping oneshot timer
D/BluetoothMapMasInstance( 6236): MAS initSocket()
,D/BluetoothMapMasInstance( 6236):   masId = 00
D/BluetoothMapMasInstance( 6236):   msgTypes = 0e
D/BluetoothMapMasInstance( 6236):   masName = SMS/MMS
D/BluetoothMapMasInstance( 6236):   SDP string = 000eSMS/MMS
V/BluetoothPbapService( 6236): Pbap Service initSocket
D/BluetoothManagerService( 1031): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/qcom-bt-wlan-coex( 6469): /system/etc/init.qcom.coex.sh: btwlancoex/abtfilt not available 
D/BluetoothManagerService( 1031): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/LGBluetoothAPIService( 1964): [BTUI] LGBluetoothAPIService Binding Success
,W/bt-smp  ( 6236): Key(LSB ~ MSB) = 0a 3c a6 fe eb 17 6a 79 a6 1f 0a 0b f9 50 a0 5f 
W/bt-smp  ( 6236): Plain text(LSB ~ MSB) = a2 69 41 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 6236): Encrypted text(LSB ~ MSB) = e2 a2 36 60 a7 c0 32 c9 75 89 08 0e 45 c3 ab cd 
W/bt-btm  ( 6236): Stopping oneshot timer
W/BluetoothAdapter( 6236): getBluetoothService() called with no BluetoothManagerCallback
W/BluetoothAdapter( 6236): getBluetoothService() called with no BluetoothManagerCallback
D/LGBluetoothServiceAdapter( 6236): [BTUI] createSocketChannel FD=73 mFd=0
V/BluetoothMapMasInstance( 6236): Succeed to create listening socket 
D/BluetoothMapMasInstance( 6236): Accepting socket connection...
D/BluetoothAdapterProperties( 6236): Scan Mode:21
D/LGBluetoothDeviceModeControllManager( 6236): getDeviceMode  deviceMode 0
D/LGBluetoothServiceAdapter( 6236): [BTUI] createSocketChannel FD=75 mFd=73
V/BluetoothPbapService( 6236): Succeed to create listening socket 
V/BluetoothPbapService( 6236): Accepting socket connection...
D/LGBluetoothAPIServer( 6236): [BTUI] onCreate()
D/LGBluetoothAPIServer( 6236): [BTUI] onBind()
W/bt-smp  ( 6236): Key(LSB ~ MSB) = 0a 3c a6 fe eb 17 6a 79 a6 1f 0a 0b f9 50 a0 5f 
W/bt-smp  ( 6236): Plain text(LSB ~ MSB) = 88 0f 40 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 6236): Encrypted text(LSB ~ MSB) = 6d 97 e7 3f e9 b5 db 9a 8e 2c 5c 67 32 a1 11 dc 
W/bt-btm  ( 6236): Stopping oneshot timer
D/LGBluetoothAPIService( 1964): [BTUI] LGBluetoothAPIServiceConnection: connected to LGBluetoothAPIAdapter
,D/LGBluetoothAPIService( 1964): Message: 100
D/LGBluetoothAPIService( 1964): MESSAGE_BLUETOOTH_SERVICE_CONNECTED
W/bt-smp  ( 6236): Key(LSB ~ MSB) = 0a 3c a6 fe eb 17 6a 79 a6 1f 0a 0b f9 50 a0 5f 
W/bt-smp  ( 6236): Plain text(LSB ~ MSB) = 59 1f 64 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 6236): Encrypted text(LSB ~ MSB) = a1 f9 95 07 4c f6 14 ff e8 b0 86 d1 ae 3d d0 86 
W/bt-btm  ( 6236): Stopping oneshot timer
W/ContextImpl( 6275): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
V/BluetoothPbapReceiver( 6236): PbapReceiver onReceive 
V/BluetoothPbapReceiver( 6236): ***********action = android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothPbapReceiver( 6236): ***********state = 12
W/bt-smp  ( 6236): Key(LSB ~ MSB) = 0a 3c a6 fe eb 17 6a 79 a6 1f 0a 0b f9 50 a0 5f 
W/bt-smp  ( 6236): Plain text(LSB ~ MSB) = c4 1d 6b 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 6236): Encrypted text(LSB ~ MSB) = 21 bc ac 5c b1 98 c5 03 10 89 f3 20 cc 15 3b 02 
W/bt-btm  ( 6236): Stopping oneshot timer
,D/LocalBluetoothProfileManager( 6275): Adding local A2DP profile
D/BluetoothManagerService( 1031): Message: 30
D/LocalBluetoothProfileManager( 6275): Adding local HEADSET profile
,D/BluetoothManagerService( 1031): Message: 30
D/BluetoothManagerService( 1031): Message: 30
D/BluetoothManagerService( 1031): Message: 30
,D/LocalBluetoothProfileManager( 6275): Adding local MAP profile
D/BluetoothMap( 6275): Create BluetoothMap proxy object
D/BluetoothManagerService( 1031): Message: 30
D/BluetoothManagerService( 1031): Message: 30
V/BluetoothPbapService( 6236): Pbap Service onBind
D/LocalBluetoothProfileManager( 6275): LocalBluetoothProfileManager construction complete
D/LGBluetoothUserBindClient( 6275): [BTUI] initUserBindClient
,W/ContextImpl( 6275): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.android.settings.bluetooth.LGBluetoothUserBindClient.initUserBindClient:90 com.android.settings.bluetooth.LGBluetoothUserBindClient.<init>:55 com.android.settings.bluetooth.LGBluetoothUserBindClient.getInstance:47 
,D/DockEventReceiver( 6275): finishStartingService: stopping service
D/BluetoothA2dp( 6275): Proxy object connected
D/A2dpProfile( 6275): Bluetooth service connected
D/BluetoothHeadset( 6275): Proxy object connected
D/HeadsetProfile( 6275): Bluetooth service connected
,D/BluetoothInputDevice( 6275): Proxy object connected
,D/HidProfile( 6275): Bluetooth service connected
D/BluetoothPan( 6275): BluetoothPAN Proxy object connected
D/PanProfile( 6275): Bluetooth service connected
D/BluetoothMap( 6275): Proxy object connected
D/MapProfile( 6275): Bluetooth service connected
D/BluetoothMap( 6275): getConnectedDevices()
V/BluetoothMapService( 6236): getConnectedDevices()
D/BluetoothPbap( 6275): Proxy object connected
,D/PbapServerProfile( 6275): Bluetooth service connected
,D/LGBluetoothUserBindClient( 6275): [BTUI] onServiceConnected
D/BluetoothPermissionRequest( 6275): onReceive
D/LGBluetoothFeatureConfig( 6275): isPrivacyLogsEnabled : true
D/LGBluetoothUtils( 6275): [BTUI] FileNotFound: readProperty
D/LGBluetoothResetSettingReceiver( 6275): return without doing reset settings.
V/BluetoothOppReceiver( 6236): Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_ON
,I/LGBluetoothOppAdapter( 6236): [BTUI] startOppService()
V/BluetoothOppManager( 6236): restoreApplicationData! falsefalsenullnull
,D/LGBluetoothFeatureConfig( 6236): isPrivacyLogsEnabled : true
V/BtOppService( 6236): onCreate
,V/BluetoothOppNotification( 6236): send message
V/BtOppService( 6236): Starting RfcommListener
D/BluetoothOppPreference( 6236): Dumping Names:  
D/BluetoothOppPreference( 6236): {}
D/BluetoothOppPreference( 6236): Dumping Channels:  
D/BluetoothOppPreference( 6236): {}
V/BtOppService( 6236): onStartCommand
,V/BtOppService( 6236): pendingUpdate is true keepUpdateThread is false sListenStarted is true
V/BluetoothFtpReceiver( 6236): BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothFtpReceiver( 6236): BluetoothFtpReceiver Start Service
V/BluetoothOppNotification( 6236): new notify threadi!
V/BluetoothOppNotification( 6236): send delay message
V/BtOppService( 6236): start RfcommListener
,V/BtOppRfcommListener( 6236): Starting RFCOMM listener....
D/BluetoothManagerService( 1031): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
V/BtOppService( 6236): Deleted complete outbound shares, number =  0
V/BtOppService( 6236): RfcommListener started
V/BluetoothOppProvider( 6236): starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
W/BluetoothAdapter( 6236): getBluetoothService() called with no BluetoothManagerCallback
V/BluetoothOppProvider( 6236): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
D/LGBluetoothServiceAdapter( 6236): [BTUI] createSocketChannel FD=79 mFd=75
V/BtOppRfcommListener( 6236): Started RFCOMM listener....
I/BtOppRfcommListener( 6236): Accept thread started.
V/BtOppRfcommListener( 6236): Accepting connection...
V/BluetoothOppProvider( 6236): created cursor android.database.sqlite.SQLiteCursor@3d7861cc on behalf of 
V/BluetoothOppNotification( 6236): mUpdateCompleteNotification = true
V/BtOppService( 6236): Deleted complete inbound failed shares, number = 0
V/BluetoothOppProvider( 6236): starting query, database is not null; projection[0] is _id; selection is direction=1 AND status=200 AND visibility=1; selectionArgs is null; sort is _id.
V/BluetoothOppProvider( 6236): created cursor android.database.sqlite.SQLiteCursor@9d5fc15 on behalf of 
,V/BluetoothOppProvider( 6236): starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
V/BluetoothOppProvider( 6236): created cursor android.database.sqlite.SQLiteCursor@3028eb2a on behalf of 
V/BtOppService( 6236): pendingUpdate is false keepUpdateThread is false sListenStarted is true
V/BluetoothOppProvider( 6236): created cursor android.database.sqlite.SQLiteCursor@58f1d1b on behalf of 
V/BluetoothOppNotification( 6236): outbound: succ-0  fail-0
V/BluetoothOppNotification( 6236): outbound notification was removed.
V/BluetoothOppProvider( 6236): starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
V/BluetoothOppProvider( 6236): created cursor android.database.sqlite.SQLiteCursor@16afceb8 on behalf of 
,V/BluetoothOppNotification( 6236): inbound: succ-0  fail-0
D/BluetoothAdapterService( 6236): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@369476c2
V/BluetoothFtpService( 6236): Ftp Service onCreate
I/BluetoothFtpService( 6236): Ftp Service onCreate
V/BluetoothFtpService( 6236): Ftp Service onStartCommand
V/BluetoothFtpService( 6236): action: android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothFtpService( 6236): Starting Listening on sockets
,V/BluetoothSapReceiver( 6236): [BTUI] checkServiceStart
V/BluetoothSapReceiver( 6236): [BTUI] region:EU country:EU
V/BluetoothSapReceiver( 6236): SapReceiver onReceive 
V/BluetoothSapReceiver( 6236): action = android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothSapReceiver( 6236):  Bluetooth Adapter state = 12
V/BluetoothSapReceiver( 6236): Calling SAP service start service with action = null
V/BluetoothOppNotification( 6236): inbound notification was removed.
V/BluetoothOppProvider( 6236): starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
V/BtOppService( 6236): ContentObserver received notification
V/BtOppService( 6236): ContentObserver received notification
V/BluetoothFtpService( 6236): Handler(): got msg=1
V/BluetoothFtpService( 6236): Ftp Service startRfcommSocketListener
V/BluetoothFtpService( 6236): Ftp Service initSocket
V/BtOppService( 6236): pendingUpdate is true keepUpdateThread is false sListenStarted is true
V/BluetoothOppProvider( 6236): created cursor android.database.sqlite.SQLiteCursor@24c28ff6 on behalf of 
V/BluetoothOppProvider( 6236): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
D/AuthorizationBluetoothService( 2129): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
D/BluetoothManagerService( 1031): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
V/BluetoothOppProvider( 6236): created cursor android.database.sqlite.SQLiteCursor@3cf86ff7 on behalf of 
W/BluetoothAdapter( 6236): getBluetoothService() called with no BluetoothManagerCallback
D/LGBluetoothServiceAdapter( 6236): [BTUI] createSocketChannel FD=81 mFd=79
V/BluetoothFtpService( 6236): Succeed to create listening socket on channel 20
V/BluetoothFtpService:RfcommSocketAcceptThread( 6236): Run Accept thread
,V/BluetoothOppNotification( 6236): update too frequent, put in queue
V/BtOppService( 6236): pendingUpdate is false keepUpdateThread is false sListenStarted is true
D/BluetoothAdapterService( 6236): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@369476c2
V/BluetoothSapService( 6236): Sap Service onCreate
,V/BluetoothSapService( 6236): action: android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothSapService( 6236): state: 12
V/BluetoothSapService( 6236): Starting SAP server process
V/BluetoothSapService( 6236): SAP Service startRfcommListenerThread
V/BluetoothSapService( 6236): Sap Service initRfcommSocket
D/BluetoothManagerService( 1031): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
W/BluetoothAdapter( 6236): getBluetoothService() called with no BluetoothManagerCallback
D/LGBluetoothServiceAdapter( 6236): [BTUI] createSocketChannel FD=82 mFd=81
V/BluetoothSapService( 6236): Succeed to create listening socket 
V/BluetoothSapService( 6236): Accepting socket connection...
,W/sapd    ( 6493): type=1400 audit(0.0:163): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6828 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
W/sapd    ( 6493): type=1400 audit(0.0:164): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6828 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,V/BT_SAP  ( 6493): Event pipe created
,V/BT_SAP  ( 6493): create_server_socket qcom.sap.server
V/BT_SAP  ( 6493): created socket fd 6
,I/dhcpcd  ( 6429): wlan0: acknowledged 192.168.1.125 from 192.168.1.1
,I/dhcpcd  ( 6429): wlan0: leased 192.168.1.125 for 86400 seconds
,D/dhcpcd  ( 6429): wlan0: adding IP address 192.168.1.125/24
D/dhcpcd  ( 6429): wlan0: adding route to 192.168.1.0/24
D/dhcpcd  ( 6429): wlan0: adding default route via 192.168.1.1
D/dhcpcd  ( 6429): wlan0: writing lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
D/dhcpcd  ( 6429): getUsingAPMacAddress: c0:ff:d4:d3:aa:48 , return 1
D/dhcpcd  ( 6429): write_lease_ext: /data/misc/dhcp/dhcpcd-wlan0-c0:ff:d4:d3:aa:48.lease2
D/dhcpcd  ( 6429): wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason REBOOT
,E/WifiStateMachine( 1031):  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1031):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1031):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1031):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1031):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
D/ConnectivityService( 1031): Update of LinkProperties for NetworkAgentInfo [WIFI () - 100]; created=false
E/WifiStateMachine( 1031):  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0 v4
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4
E/WifiStateMachine( 1031):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0 v4
E/WifiStateMachine( 1031):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4
E/WifiStateMachine( 1031):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4
E/WifiStateMachine( 1031):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0 v4
D/ConnectivityService( 1031): Update of LinkProperties for NetworkAgentInfo [WIFI () - 100]; created=false
D/DhcpStateMachine( 1031): DHCPV4 succeeded on wlan0
,D/LgDhcpStateMachineHelper( 1031): CheckDhcpDirectory [Lease File Count] : 3
V/LgDhcpStateMachineHelper( 1031): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
D/LgDhcpStateMachineHelper( 1031): checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.125
V/LgDhcpStateMachineHelper( 1031): Add DhcpResults: IP address 192.168.1.125/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 86400 seconds
V/DhcpStateMachine( 1031): Current State is mWaitBeforeStartState.
V/LgDhcpStateMachineHelper( 1031): bShouldSendDhcpAction Result: true
D/DhcpStateMachine( 1031): DHCP Start/Renew wake lock is released.
E/WifiStateMachine( 1031):  ObtainingIpState CMD_POST_DHCP_ACTION 1 0 OK  v4
D/DhcpStateMachine( 1031): RunningState
E/WifiStateMachine( 1031):  L2ConnectedState CMD_POST_DHCP_ACTION 1 0 OK  v4
D/WifiNative-wlan0( 1031): doBoolean: DRIVER BTCOEXMODE 2
I/wpa_supplicant( 6274): wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
D/LGWifiP2pService( 1031): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1031): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0( 1031): DRIVER BTCOEXMODE 2: returned true
D/WifiNative-wlan0( 1031): doBoolean: DRIVER SETSUSPENDMODE 1
I/wpa_supplicant( 6274): wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 1
D/WifiNative-wlan0( 1031): DRIVER SETSUSPENDMODE 1: returned true
D/WifiNative-wlan0( 1031): doBoolean: SET ps 1
,D/WifiNative-wlan0( 1031): SET ps 1: returned true
D/ConnectivityService( 1031): Update of LinkProperties for NetworkAgentInfo [WIFI () - 100]; created=false
,E/WifiStateMachine( 1031):  ObtainingIpState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
E/WifiStateMachine( 1031): WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
D/ConnectivityService( 1031): ignoring duplicate network state non-change
I/StatusBar.NetworkController( 1473): networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1473): mWifiConnected = false, mWifiLevel = 0
W/Settings( 1031): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1031): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1031): NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
,D/ConnectivityService( 1031): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
D/ConnectivityService( 1031): Adding iface wlan0 to network 100
E/WifiStateMachine( 1031): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,D/StatusBar.NetworkController( 1473): refreshViews: Data not connected!! Set no data type icon / Roaming
W/Settings( 1031): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1031): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1031): NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
D/WifiHS20( 1031): [PASSPOINT] passpointNotification: hs20AP list is checked
,I/StatusBar.NetworkController( 1473): networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1473): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1473): refreshViews: Data not connected!! Set no data type icon / Roaming
I/StatusBar.NetworkController( 1473): networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/ConnectivityService( 1031): Unexpected mtu value: 0, wlan0
D/ConnectivityService( 1031): Adding Route [fe80::/64 -> :: wlan0] to network 100
V/WfdStateTracker( 1964): handleWifiStateChangedEvent: 1
D/ConnectivityService( 1031): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 100
D/ConnectivityService( 1031): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 100
D/ConnectivityService( 1031): addLocalRoutetoDefaultNetwork
D/ConnectivityService( 1031): defaultNAI is null or Wi-Fi no need to add Loacal route to default network. WiFi netid = 100
D/ConnectivityService( 1031): Setting Dns servers for network 100 to [/192.168.1.1]
W/Settings( 1031): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1031): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1031): NETWORK_STATE_CHANGED_ACTION [CONNECTED]
D/WifiHS20( 1031): [PASSPOINT] passpointNotification: hs20AP list is checked
,W/Settings( 1031): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1031): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1031): NETWORK_STATE_CHANGED_ACTION [CONNECTED]
D/Nat464Xlat( 1031): requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
D/ConnectivityService( 1031): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService( 1031): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 100]
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1031): DefaultState{ when=-1ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1031): Connected
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1031): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1031): Checking http://clients3.google.com/generate_204 on "NG700"
D/ConnectivityService( 1031): rematching NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService( 1031):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService( 1031):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1031):     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
D/ConnectivityService( 1031):   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1031):     satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:true
D/ConnectivityService( 1031): currentScore = 0, newScore = 20
D/ConnectivityService( 1031):    accepting network in place of null
D/ConnectivityService( 1031): sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    ( 1031): new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    ( 1031):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/TelephonyNetworkFactory-1( 1867): new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/TelephonyNetworkFactory-1( 1867):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
D/ConnectivityService( 1031): Setting tx/rx TCP buffers to 524288,1048576,2097152,262144,524288,1048576
D/libc-netbsd(  323): res_queryN name = clients3.google.com, class = 1, type = 28
I/StatusBar.NetworkController( 1473): mWifiConnected = true, mWifiLevel = 3
D/StatusBar.NetworkController( 1473): refreshViews: Data not connected!! Set no data type icon / Roaming
,E/ConnectivityService( 1031): [lg_data] Adding agent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.125/24,fe80::c69a:2ff:fe7b:60ac/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
D/CSLegacyTypeTracker( 1031): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
D/ConnectivityService( 1031): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService( 1031): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/CSLegacyTypeTracker( 1031): [e] list.add(nai) empty : false size: 1
D/ConnectivityService( 1031): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.125/24,fe80::c69a:2ff:fe7b:60ac/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
D/ConnectivityService( 1031): validation of new default Network = false
D/ConnectivityService( 1031): Default network via Wi-Fi connected. start DSQN
D/DSQN    ( 1031): enableDataServiceNotify 
D/DSQN    ( 1031): start dsqn bin
,D/libc-netbsd(  323): default dns: query_ipv6=0, query_ipv4=1
,D/libc-netbsd(  323): res_queryN name = 2.android.pool.ntp.org, class = 1, type = 1
D/LocSvc_java( 1031): Sending msg: 4 arg1:1 arg2:1
D/LocSvc_java( 1031): getAGpsConnectionInfo connType - 4
D/LocSvc_java( 1031): updateNetworkState connTyp: 4 available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java( 1031): ignore wifi update if we are not in OPENING or CLOSING
D/LocSvc_java( 1031): Sending msg: 5 arg1:0 arg2:1
D/libc-netbsd(  323): default dns: query_ipv6=0, query_ipv4=1
,D/libc-netbsd(  323): res_queryN name = europe.pool.ntp.org, class = 1, type = 1
D/PostponalbeReceiver( 5170): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
D/ConnectivityService( 1031): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService( 1031):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1031):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
I/StatusBar.NetworkController( 1473): networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1473): mWifiConnected = true, mWifiLevel = 3
D/ConnectivityService( 1031): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
D/StatusBar.NetworkController( 1473): refreshViews: Data not connected!! Set no data type icon / Roaming
D/ConnectivityManager.CallbackHandler( 1473): CM callback handler got msg 524290
W/dsqn    ( 6536): type=1400 audit(0.0:165): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6828 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
W/dsqn    ( 6536): type=1400 audit(0.0:166): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6828 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
D/libc-netbsd(  323): res_queryN name = clients3.google.com, class = 1, type = 1
,D/libc-netbsd(  323): res_queryN name = 2.android.pool.ntp.org succeed
E/DSQN    ( 6536): DSQN ssw
,D/TelephonyIcons( 1473): null signal icon name: drawable/stat_sys_signal_null
D/StatusBar.NetworkController( 1473): refreshViews: Data not connected!! Set no data type icon / Roaming
V/WiFiOffLoadBroadcast( 6275): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/StatusBar.NetworkController( 1473): refreshViews: Data not connected!! Set no data type icon / Roaming
,D/WiFiOffLoadBroadcast( 6275): MCCMNC not supported: null
D/QRemote ( 5995): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 5995): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
D/libc-netbsd(  323): res_queryN name = clients3.google.com succeed
I/QRemote ( 5995): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,D/PostponalbeReceiver( 5170): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
V/WiFiOffLoadBroadcast( 6275): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,V/NetworkPolicy( 1031): [LG_RESTRICTED] checkMobilePolicy_type()
D/libc-netbsd(  323): res_queryN name = europe.pool.ntp.org succeed
D/WiFiOffLoadBroadcast( 6275): MCCMNC not supported: null
D/LGDataListener(  323): argv[0]=dsqncommand
D/LGDataListener(  323): argv[1]=wlan0
D/LGDataListener(  323): argv[2]=1
D/LGDataListener(  323): notifyDSQN DSQN STARTMONITOR wlan0 1
D/DSQN    ( 1031): DSQM DsqnNotification wlan0  1
D/DSQN    ( 1031): start to monitor internet connection
D/QRemote ( 5995): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 5995): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 5995): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,D/PostponalbeReceiver( 5170): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
I/PCSuite ( 6328): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1031): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Fri, 11 Dec 2015 11:15:23 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1449832523371], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1449832523356]}
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1031): Don't send network conditions - lacking user consent.
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
D/ConnectivityService( 1031): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
D/ConnectivityManager.CallbackHandler( 1473): CM callback handler got msg 524290
D/WIFI    ( 1031): new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    ( 1031):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,D/PCSuite ( 6328): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
,D/TelephonyNetworkFactory-1( 1867): new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/TelephonyNetworkFactory-1( 1867):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
V/WiFiOffLoadBroadcast( 6275): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 6275): MCCMNC not supported: null
D/QRemote ( 5995): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 5995): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,D/QRemote ( 5995): [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
I/QRemote ( 5995): [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
I/QRemote ( 5995): [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
D/PostponalbeReceiver( 5170): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,I/PCSuite ( 6328): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
D/TelephonyIcons( 1473): null signal icon name: drawable/stat_sys_signal_null
D/PCSuite ( 6328): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
D/StatusBar.NetworkController( 1473): refreshViews: Data not connected!! Set no data type icon / Roaming
D/StatusBar.NetworkController( 1473): refreshViews: Data not connected!! Set no data type icon / Roaming
V/WiFiOffLoadBroadcast( 6275): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/LocSvc_java( 1031): NTP server : europe.pool.ntp.org
D/LocSvc_java( 1031): NTP server returned: 1449832523647 (Fri Dec 11 12:15:23 GMT+01:00 2015) reference: 289296 certainty: 25 system time offset: 240
D/LocSvc_java( 1031): Sending msg: 10 arg1:0 arg2:1
D/WiFiOffLoadBroadcast( 6275): MCCMNC not supported: null
D/QRemote ( 5995): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,D/QRemote ( 5995): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
D/QRemote ( 5995): [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
I/QRemote ( 5995): [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
I/QRemote ( 5995): [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
V/BluetoothOppNotification( 6236): new notify threadi!
V/BluetoothOppNotification( 6236): send delay message
,V/BluetoothOppProvider( 6236): starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
V/BluetoothOppProvider( 6236): created cursor android.database.sqlite.SQLiteCursor@243a1493 on behalf of 
V/BluetoothOppNotification( 6236): mUpdateCompleteNotification = true
V/BluetoothOppProvider( 6236): starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
,V/BluetoothOppProvider( 6236): created cursor android.database.sqlite.SQLiteCursor@1bb1bcd0 on behalf of 
V/BluetoothOppNotification( 6236): outbound: succ-0  fail-0
V/BluetoothOppNotification( 6236): outbound notification was removed.
V/BluetoothOppProvider( 6236): starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
V/BluetoothOppProvider( 6236): created cursor android.database.sqlite.SQLiteCursor@b14f4c9 on behalf of 
V/BluetoothOppNotification( 6236): inbound: succ-0  fail-0
V/BluetoothOppNotification( 6236): inbound notification was removed.
V/BluetoothOppProvider( 6236): starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
V/BluetoothOppProvider( 6236): created cursor android.database.sqlite.SQLiteCursor@36f7a7ce on behalf of 
I/jxcore-log( 6159): Connected to the server!
I/jxcore-log( 6159): 
,I/chromium( 6159): [INFO:CONSOLE(63)] "logCallback Connected to the server", source: file:///android_asset/www/js/thali_main.js (63)
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-47 f=2412 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1866421749] gl rssi=-47 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-47 f=2412 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1866421746] gl rssi=-47 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,D/StatusBar.NetworkController( 1473): refreshViews: Data not connected!! Set no data type icon / Roaming
,I/jxcore-log( 6159): BLE advertisement not supported: MultipleAdvertisement not supported
I/jxcore-log( 6159): 
,V/WifiInternetCheck( 1031): Single check msg out of sync, ignoring.
,D/ConnectivityService( 1031): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/GpsLocationProvider( 1031): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering( 1031): MasterInitialState.processMessage what=3
,D/AlarmManagerService( 1031): Setting time of day to sec=1449832526
W/AlarmManagerService( 1031): Unable to set rtc to 1449832526: Invalid argument
D/PostponalbeReceiver( 5170): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
,W/ContextImpl( 5170): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
,I/NetworkMonitor( 5239): type=WIFI subType= reason=null isConnected=true
D/PowerManagerServiceEx( 1031): acquireWakeLockInternal: lock=538279423, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1031
,D/LIA_Informant_Tips_DateChangeManager( 2728): onReceive() : ACTION_TIME_CHANGED
I/LIA_Informant_Tips_LogTracer( 2728): [Log Tracer - Schedule Transition] Time Change Event Received : 2015-12-11 12:15:26...... Request
I/LIA_Informant_Tips_LogTracer( 2728): [Log Tracer - Schedule Transition] UserGuide, DATE_UPDATE : working count : 2, total count : 110, new day : false...... Request
D/LIA_Informant_Tips_DateChangeManager( 2728): DateInfo : SmartTips Total Working Day Count = 110
D/LIA_Informant_Tips_DateChangeManager( 2728): DateInfo : UserGuide Working Duration Count = 2
D/LIA_Informant_Tips_DateChangeManager( 2728): DateInfo : Last Date Check Time = 2015-12-11 12:15:26
I/SecureClockService( 1964): Intent.ACTION_TIME_CHANGED 
I/[SystemUI]Clock( 1473): onReceive = android.intent.action.TIME_SET
,I/LgeClockWidgetControlView( 1473): time changed, timezoneChanged : false
W/ActivityManager( 1031): getTasks: caller 10029 is using old GET_TASKS but privileged; allowing
,D/KeyguardUpdateMonitor( 1473): handleTimeUpdate
,I/[LGHome]LGDateChangeReceiver( 2086): [LGDateChangeReceiver.java:78:updateCalendarShortcut()]date=11 currentDate=-1 dayofweek=6 currentDayOfWeek=-1
,I/[LGHome]LGCalendarIcon( 2086): [LGCalendarIcon.java:214:makeCalendarBitmap()]Locale = en_US dayofweek= Fri date= 11
I/[LGHome]LGCalendarIcon( 2086): [LGCalendarIcon.java:214:makeCalendarBitmap()]Locale = en_US dayofweek= Fri date= 11
I/[LGHome]Launcher( 2086): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,D/[Concierge]Service( 2627): onStartCommand(). Type : 9
,D/[Concierge]Service( 2627): onStartCommand(). Type : 9
,I/ActivityManager( 1031): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=6586 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,I/AppUp4:AppBoxCP( 6586): onCreate
W/AppUp4:DB( 6586):  [AppBoxDatabaseHelper] construct
,I/AppUp4:DB( 6586):  setFingerPrint start
I/AppUp4:DB( 6586):  newfinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys SDK version = 21
I/art     ( 1031): Explicit concurrent mark sweep GC freed 76633(3MB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 44MB/66MB, paused 1.282ms total 119.014ms
D/PowerManagerServiceEx( 1031): releaseWakeLockInternal: lock=538279423 [*alarm*], flags=0x0
I/AppUp4:DB( 6586):  beforefinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys
I/AppUp4:DB( 6586):  SDK version = 21
I/AppUp4:DB( 6586):  beforefinger == newfinger no write in DB
,I/ActivityManager( 1031): Start proc com.google.android.apps.books for service com.google.android.apps.books/.service.SyncService: pid=6604 uid=10054 gids={50054, 9997, 3003, 1028, 1015} abi=armeabi-v7a
D/AppUp4:AppBoxApplication( 6586): AppBoxApplication onCreate()
I/NetworkStateForAutoUpdateMonitor( 6586): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 6586): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 6586): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 6586): [onReceive] request level :IDLE....
I/AppUp4:CustModeStarterReceiver( 6586): onReceive
,I/ActivityManager( 1031): Start proc com.android.gallery3d for service com.android.gallery3d/com.lge.gallery.picasa.PicasaService: pid=6624 uid=10027 gids={50027, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
,D/LgDataFeature( 6586): LgDataFeature() Constructor: none
D/LgDataFeature( 6586): LgDataFeature() Constructor Done, null
,D/AppUp4:CustFacade( 6586): Context : android.app.ReceiverRestrictedContext@3c40970d
D/AppUp4:CustFacade( 6586): isCustomizationCompleted : false
D/AppUp4:CustFacade( 6586): isPhone : true
D/AppUp4:CustModeStarterReceiver( 6586): begin check event
,I/AppUp4:CustModeStarterReceiver( 6586): Event For GoodConnectivity
D/AppUp4:CustModeStarterReceiver( 6586): runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
D/AppUp4:CustModeStarterReceiver( 6586): call method handleAsyncCustNotification.
D/AppUp4:CustModeStarterReceiver( 6586): handleAsync isTriedOnce : false
E/AppUp4:CustModeStarterReceiver( 6586): handleAsyncCustNotification do not startCustService
,I/ActivityManager( 1031): Killing 5902:com.google.android.apps.docs/u0a61 (adj 15): empty #17
I/GoogleURLConnFactory( 2129): Using platform SSLCertificateSocketFactory
W/ResourcesManager( 6624): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6624): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,W/ResourcesManager( 6624): Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
W/ResourcesManager( 6624): Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
,W/libprocessgroup( 1031): failed to open /acct/uid_10061/pid_5902/cgroup.procs: No such file or directory
,D/LGDMClient( 3985): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 3985): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
W/ContextImpl( 3985): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
W/ContextImpl( 3985): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
V/GLSActivity( 2129): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/LGDMClient( 3985): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=3, isUserType=1
V/DownloadManager( 3366): Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 3985): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 3985): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
I/LGDMClient( 3985): [DmServiceProcessor.java] [processNetworkChanged()] : [91] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
,I/ActivityManager( 1031): Start proc com.android.chrome for service com.android.chrome/com.google.android.apps.chrome.sync.ChromeBrowserSyncAdapterService: pid=6647 uid=10057 gids={50057, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/AppConfig( 6624): Total System Memory = 2995761152
V/DownloadManager( 3366): DownloadService onCreate
I/DownloadManager( 3366): in removeSpuriousFiles
W/ContextImpl( 3985): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:141 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:180 android.app.IntentService$ServiceHandler.handleMessage:65 
D/SystemHelper( 6624): region [EU], country [EU], operator [OPEN], sub-operator []
,V/DownloadManager( 3366): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 3366): created cursor android.database.sqlite.SQLiteCursor@16b640b3 on behalf of 3366
I/DownloadManager( 3366): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGMyGuide_4.40.09_COM_COM_20150430011620058_RELG-D855.apk
I/DownloadManager( 3366): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGBackup_4.50.37_COM_COM_20150608234245157.apk
I/DownloadManager( 3366): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/CalendarProvider_4.2.8_COM_COM_20150304234552863_RELG-D855.apk
I/DownloadManager( 3366): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calendar_4.40.16_COM_COM_20150304234554754_RELG-D855.apk
I/DownloadManager( 3366): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.10_COM_COM_20150521235426173_RELG-D855.apk
I/DownloadManager( 3366): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQVoiceplusN_2.3.3_COM_COM_20150604065210803.apk
I/DownloadManager( 3366): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.11_COM_COM_v2_20150911144028620_RELG-D855_21.apk
I/DownloadManager( 3366): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQMemoplus(LG-D855_user)_20150902050954661.apk
I/DownloadManager( 3366): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/RemoteCall_4.1.10_COM_COM_20150817053748728.apk
I/DownloadManager( 3366): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/rspermlge(6713)_20150901080430397.apk
I/ActivityManager( 1031): Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=6668 uid=10023 gids={50023, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
I/DownloadManager( 3366): in trimDatabase
V/DownloadManager( 3366): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
,E/LGDMClient( 3985): [DmNotiService.java] [onCreate()] : [148] : DmNotiService.onCreate()
D/LGDMClient( 3985): [DmNotiService.java] [onStartCommand()] : [182] : in the new onStartCommand()
D/LGDMClient( 3985): [DmNotiService.java] [handleStart()] : [203] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
V/DownloadManager( 3366): created cursor android.database.sqlite.SQLiteCursor@1ece4de9 on behalf of 3366
,V/DownloadManager( 3366): DownloadService onStartCommand
V/DownloadManager( 3366): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3366): created cursor android.database.sqlite.SQLiteCursor@30ca350f on behalf of 3366
V/DownloadManager( 3366): processing inserted download 1
,V/DownloadManager( 3366): processing inserted download 4
V/DownloadManager( 3366): processing inserted download 7
V/DownloadManager( 3366): processing inserted download 8
V/DownloadManager( 3366): processing inserted download 9
V/DownloadManager( 3366): processing inserted download 10
V/DownloadManager( 3366): processing inserted download 16
V/DownloadManager( 3366): processing inserted download 17
V/DownloadManager( 3366): processing inserted download 18
,V/DownloadManager( 3366): processing inserted download 21
V/DownloadManager( 3366): DownloadService onDestroy
W/ResourcesManager( 6668): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6668): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 6668): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
W/ResourcesManager( 6668): Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
I/ReaderUtils( 6604): PortraitW 1440 LandscapeW 2392 SmallestSize 1340 LargestSize 2392 textZoom 4.4999995 isTablet false Memory 256
,D/GpsLocationProvider( 1031): updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,W/DriveInitializer( 2345): Background init thread started
,E/GpsLocationProvider( 1031): No APN found to select.
E/VoldCmdListener(  281): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  281): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.gms/files/
W/Vold    (  281): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 2345): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.gms/files
,W/GAV2    ( 6604): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
I/BooksApp( 6604): Created application version: 3.2.35 (30235)
,I/ActivityManager( 1031): Killing 5584:com.lge.lockscreensettings/u0a80 (adj 15): empty #17
,W/DriveInitializer( 2345): Awaiting to be initialized
W/libprocessgroup( 1031): failed to open /acct/uid_10080/pid_5584/cgroup.procs: No such file or directory
,I/LGEmail ( 6668): [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
D/LGEmail ( 6668): user build Type == true (at Util.java isUserModeBuildType 3507)[v:6.41.18]
,W/DriveInitializer( 2345): Background init thread ended
W/ResourceType( 6668): No package identifier when getting value for resource number 0x00000000
,D/PerfProfileCollectorService( 2345): User is not opt-in to Usage & Diagnostics.
D/PerfProfileCollectorService( 2345): removeStateFiles() called
D/PerfProfileCollectorService( 2345): User is not opt-in to Usage & Diagnostics.
,E/Auth.Api.Credentials( 2345): [CredentialSyncAdapter] Unknown sync event.
I/BooksSync( 6604): Starting books sync
D/DelayedSyncController( 6647): Delaying sync.
,D/LgDataFeature( 6668): LgDataFeature() Constructor: none
D/LgDataFeature( 6668): LgDataFeature() Constructor Done, null
I/art     ( 2129): Explicit concurrent mark sweep GC freed 21215(1220KB) AllocSpace objects, 2(32KB) LOS objects, 51% free, 30MB/62MB, paused 1.065ms total 36.017ms
,D/Netstats( 2345): User is not opted-in to Usage & Diagnostics.
,I/ActivityManager( 1031): Killing 5603:com.google.android.apps.plus/u0a97 (adj 15): empty #17
W/libprocessgroup( 1031): failed to open /acct/uid_10097/pid_5603/cgroup.procs: No such file or directory
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-46 f=2412 sc=60 link=72 tx=9.8, 0.0, 0.0  rx=8.5 bcn=0 [on:0 tx:0 rx:0 period:3254] from screen [on:0 period:-1866418466] gl rssi=-46 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-46 f=2412 sc=60 link=72 tx=9.8, 0.0, 0.0  rx=8.5 bcn=0 [on:0 tx:0 rx:0 period:0] from screen [on:0 period:-1866418466] gl rssi=-46 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
D/eas_req ( 6668): ---addEventToQueue() easCode=2, requestId=0 (at EasSupport.java addEventToQueue 69)
,I/LgeMiscReceiver( 3306): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 3306): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 3306): networkInfo.isConnected() = true
D/PhoneState( 3306): setPdpRejectCasuse : false
,I/HubEmail( 6668): JNI_OnLoad()
I/HubEmail( 6668): -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 6668): registerNatives()
I/HubEmail( 6668): -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 6668): registerNativeMethods()
I/HubEmail( 6668): -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
W/art     ( 6668): JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
D/BooksSync( 6604): started syncMyEbooks
,I/ActivityManager( 1031): Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=6729 uid=10062 gids={50062, 9997, 4002, 3003, 1028} abi=armeabi-v7a
W/Settings( 6668): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/libc-netbsd(  323): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  323): res_queryN name = www.google.com, class = 1, type = 1
W/Settings( 6668): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/libc-netbsd(  323): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  323): res_queryN name = static-avc.lglime.com, class = 1, type = 1
,D/libc-netbsd(  323): res_queryN name = www.google.com succeed
D/libc-netbsd(  323): default dns: query_ipv6=0, query_ipv4=1
,D/libc-netbsd(  323): res_queryN name = clients3.google.com, class = 1, type = 1
D/libc-netbsd(  323): res_queryN name = clients3.google.com succeed
D/DrmBroadcastReceiver( 6729): Receive CONNECTIVITY_ACTION
,D/DrmBroadcastReceiver( 6729): 1  network is available. Sync DRM Time with NTP
V/DrmService( 6729): Service onCreate
D/DrmService( 6729): Received new request = 2
I/DrmSntpClient( 6729): Start Sync process
D/DrmSntpClient( 6729): Server : 0
D/libc-netbsd(  323): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  323): res_queryN name = pool.ntp.org, class = 1, type = 1
,V/WifiInternetCheck( 1031): isHttpConnectionAvailable - We got a valid response : 204
D/libc-netbsd(  323): res_queryN name = static-avc.lglime.com succeed
I/ActivityManager( 1031): Start proc com.lge.sizechangable.weather for broadcast com.lge.sizechangable.weather/.layout.WeatherWidget: pid=6755 uid=10085 gids={50085, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/libc-netbsd(  323): res_queryN name = pool.ntp.org succeed
,V/GLSActivity( 2129): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     ( 6755): Almond Protected OAT
V/FormManager( 6302): There are no updated forms. The schedule will be deleted.
V/FormManager( 6302): Alarm would be updated, because LastCheckTime has been updated.
,I/LGDrmClient( 6729): _DRM_ServiceGet() : Bind lgdrm service
V/ILGDrmService(  334): eDRM_SetDRMTime +++
I/LGDRM   (  334): [DRM] SET TIME : YR=2015, MON=12, DAY=11
I/LGDRM   (  334): [DRM] SET TIME : HR=11, MIN=15, SEC=26
V/ILGDrmService(  334): eDRM_SetDRMTime ---
I/DrmSntpClient( 6729): Synched
D/DrmService( 6729): Completed !! request = 2
D/DrmService( 6729): Request count = 0
V/DrmService( 6729): Service onDestroy
I/ActivityManager( 1031): Killing 5939:com.lge.eula/1000 (adj 15): empty #17
,I/GLSUser ( 2129): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2129): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2129): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2129): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
I/art     ( 1031): Explicit concurrent mark sweep GC freed 27082(1207KB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 44MB/66MB, paused 1.578ms total 71.448ms
,W/libprocessgroup( 1031): failed to open /acct/uid_1000/pid_5939/cgroup.procs: No such file or directory
,D/WeatherApplication( 6755): removeAccount
I/ActivityManager( 1031): Killing 5975:com.google.android.gms.wearable/u0a5 (adj 15): empty #17
V/GLSActivity( 2129): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/WeatherApplication( 6755): Account.length = 0
,E/WeatherApplication( 6755): OPERATOR:OPEN
D/WeatherAncestor( 6755): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 12:15:27
D/Weather.Utils( 6755): 2 : the weather widgets(using time tick) are gone.
D/Weather.Utils( 6755): 2 : All the weather widget is gone.
,D/UpdateThreadPoolManager( 6755): 2 : This is isUpdating : false
D/WeatherAncestor( 6755): connectivity changed - connection : true
D/WeatherService( 6755): 2 : isServiceAlived():false forecastCache:null
D/ForecastDataCache( 6755): 2 : lastUpdatedTime: 1430558561343
D/ForecastDataCache( 6755): 2 : currentPackageVersion: 4.40.4
D/ForecastDataCache( 6755): 2 : Cache is not up-to-date, count: 0
,D/Weather_cast( 6755): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherAncestor( 6755): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 12:15:28
,W/libprocessgroup( 1031): failed to open /acct/uid_10005/pid_5975/cgroup.procs: No such file or directory
,I/ActivityManager( 1031): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=6775 uid=10093 gids={50093, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager( 1031): Killing 6068:com.google.android.talk/u0a72 (adj 15): empty #17
,W/libprocessgroup( 1031): failed to open /acct/uid_10072/pid_6068/cgroup.procs: No such file or directory
,V/NotificationService( 1031): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1031): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1031): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1031): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1031): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1415): onNotificationPosted
W/GLSActivity( 2129): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2129): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2129): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2129): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2129): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2129): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2129): 	at android.os.Binder.execTransact(Binder.java:446)
,D/SmartCoverUpdateMonitor( 1415): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1415): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1415): handleNotificationPosted(true)
D/QuickCircle( 1415): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1415): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1415): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1415): post do just update job
D/LgeQuickCoverNotificationData( 1415): showAll3
D/LgeQuickCoverNotificationData( 1415): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1415): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1415): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1415): showNotificationWithSetupData: display=false
,D/LgeQuickCoverOverlayWindow( 1415): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1415): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1415): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1415): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1415): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1415): isNotificationForCurrentUser : true
E/BooksAccountManager( 6604): Authentication error
E/BooksAccountManager( 6604): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6604): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6604): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6604): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6604): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6604): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6604): null auth token
E/LgeQuickCoverOverlayWindow( 1415): updateNotificationData: count=3
D/libc-netbsd(  323): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  323): res_queryN name = www.googleapis.com, class = 1, type = 1
,D/QuickStatusbarLayout( 1415): Notification difference=198
D/QuickStatusbarLayout( 1415): child = android.widget.LinearLayout{9d5fc15 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,I/GLSUser ( 2129): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.syncadapters.contacts, service: cp
I/GLSUser ( 2129): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> cp without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2129): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2129): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2129): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/libc-netbsd(  323): res_queryN name = www.googleapis.com succeed
,V/NotificationService( 1031): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1031): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1031): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1031): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1031): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
W/GLSActivity( 2129): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2129): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2129): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2129): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2129): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2129): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2129): 	at android.os.Binder.execTransact(Binder.java:446)
D/ContactsSyncAdapter( 2129): innerSync failed
D/ContactsSyncAdapter( 2129): com.google.wireless.gdata2.client.AuthenticationException: unable to get auth token android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
D/ContactsSyncAdapter( 2129): 	at com.google.android.syncadapters.contacts.AuthInfo.getAuthToken(AuthInfo.java:45)
D/ContactsSyncAdapter( 2129): 	at com.google.android.syncadapters.contacts.ContactsSyncAdapter.innerPerformSync(ContactsSyncAdapter.java:263)
D/ContactsSyncAdapter( 2129): 	at com.google.android.syncadapters.contacts.ContactsSyncAdapter.onPerformLoggedSync(ContactsSyncAdapter.java:168)
D/ContactsSyncAdapter( 2129): 	at com.google.android.common.LoggingThreadedSyncAdapter.onPerformSync(LoggingThreadedSyncAdapter.java:33)
D/ContactsSyncAdapter( 2129): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
D/ContactsSyncAdapter( 2129): Caused by: android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
D/ContactsSyncAdapter( 2129): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
D/ContactsSyncAdapter( 2129): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
D/ContactsSyncAdapter( 2129): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
D/ContactsSyncAdapter( 2129): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
D/ContactsSyncAdapter( 2129): 	at android.os.Binder.execTransact(Binder.java:446)
D/LgeQuickCoverNLService( 1415): onNotificationPosted
D/SmartCoverUpdateMonitor( 1415): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1415): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1415): handleNotificationPosted(true)
D/QuickCircle( 1415): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1415): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1415): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1415): post do just update job
D/LgeQuickCoverNotificationData( 1415): showAll3
D/LgeQuickCoverNotificationData( 1415): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1415): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1415): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1415): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1415): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1415): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1415): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1415): isNotificationForCurrentUser : true
,D/LgeQuickCoverOverlayWindow( 1415): [native noti] inex =  2
E/VoldCmdListener(  281): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  281): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  281): Returning OperationFailed - no handler for errno 0
,D/LgeQuickCoverNotificationData( 1415): isNotificationForCurrentUser : true
W/ContextImpl( 6775): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
E/VoldCmdListener(  281): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  281): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  281): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6775): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
E/LgeQuickCoverOverlayWindow( 1415): updateNotificationData: count=3
E/VoldCmdListener(  281): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  281): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  281): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6775): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
E/VoldCmdListener(  281): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  281): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  281): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6775): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
D/SyncManager( 1031): failed sync operation thalitester@gmail.com u0 (com.google), com.android.contacts, LOCAL, currentRunTime 26458, reason: 10019, SyncResult: stats [ numAuthExceptions: 1]
D/SyncManager( 1031): not retrying sync operation because the error is a hard error: thalitester@gmail.com u0 (com.google), com.android.contacts, LOCAL, currentRunTime 325217, reason: 10019
D/QuickStatusbarLayout( 1415): Notification difference=198
D/QuickStatusbarLayout( 1415): child = android.widget.LinearLayout{9d5fc15 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,D/DelayedSyncController( 6647): Delaying sync.
,I/WebViewFactory( 6775): Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,I/LibraryLoader( 6775): Loading: webviewchromium
,I/LibraryLoader( 6775): Time to load native libraries: 3 ms (timestamps 4075-4078)
I/LibraryLoader( 6775): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 6775): Binding Chromium to main looper Looper (main, tid 1) {c39bd6c}
I/LibraryLoader( 6775): Expected native library version number "",actual native library version number ""
I/chromium( 6775): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 6775): Initializing chromium process, renderers=0
W/art     ( 6775): Attempt to remove local handle scope entry from IRT, ignoring
W/chromium( 6775): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
I/chromium( 6775): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=38 off=46780 len=2953
V/AudioPolicyService(  328): registerClient() client 0xb1427b40, uid 10093
I/chromium( 6775): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:39 off:229536 len:643667
W/AudioManagerAndroid( 6775): Requires BLUETOOTH permission
,I/Adreno-EGL( 6775): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 6775): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 6775): Build Date: 12/12/14 금
I/Adreno-EGL( 6775): Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
I/Adreno-EGL( 6775): Remote Branch: 
I/Adreno-EGL( 6775): Local Patches: 
I/Adreno-EGL( 6775): Reconstruct Branch: 
,W/ApiaryClient( 6604): Error response from books API: {
W/ApiaryClient( 6604):  "error": {
W/ApiaryClient( 6604):   "errors": [
W/ApiaryClient( 6604):    {
W/ApiaryClient( 6604):     "domain": "global",
W/ApiaryClient( 6604):     "reason": "required",
W/ApiaryClient( 6604):     "message": "Login Required",
W/ApiaryClient( 6604):     "locationType": "header",
W/ApiaryClient( 6604):     "location": "Authorization"
W/ApiaryClient( 6604):    }
W/ApiaryClient( 6604):   ],
W/ApiaryClient( 6604):   "code": 401,
W/ApiaryClient( 6604):   "message": "Login Required"
W/ApiaryClient( 6604):  }
W/ApiaryClient( 6604): }
W/ApiaryClient( 6604): errCount = 1: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6604): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-1888646283833582182&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6604): Headers:
W/ApiaryClient( 6604): accept-encoding: [gzip]
W/ApiaryClient( 6604): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6604): gdata-version: 2
,I/ActivityManager( 1031): Start proc com.google.android.apps.plus for service com.google.android.apps.plus/.service.EsSyncAdapterService: pid=6833 uid=10097 gids={50097, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/NSApplication( 6775): Starting up...
I/ActivityManager( 1031): Killing 4898:com.android.vending/u0a44 (adj 15): empty #17
,W/libprocessgroup( 1031): failed to open /acct/uid_10044/pid_4898/cgroup.procs: No such file or directory
,W/ResourcesManager( 6833): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/GLSActivity( 2129): [ac] getting account id
,I/GLSUser ( 2129): [t] Fetched account id for thalitester@gmail.com : 105256135866144380227
,D/libc-netbsd(  323): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  323): res_queryN name = mtalk.google.com, class = 1, type = 1
I/CheckinService( 2345): Checking schedule, now: 1449832529139 next: 1449802491637
I/CheckinService( 2345): active receiver: enabled
,I/CheckinService( 2345): Preparing to send checkin request
I/EventLogService( 2345): Accumulating logs since 1449832289138
,I/iu.SyncManager( 2345): SYNC; picasa accounts
,D/libc-netbsd(  323): res_queryN name = mtalk.google.com succeed
D/NetworkLogImpl( 2345): Loaded NetworkSpeedPredictor
,I/iu.Environment( 2345): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
I/iu.UploadsManager( 2345): num queued entries: 0
I/iu.UploadsManager( 2345): num updated entries: 0
,I/iu.SyncManager( 2345): NEXT; no task
,D/ChimeraCfgMgr( 2345): Loading module com.google.android.gms.kids from APK com.google.android.gms
D/ChimeraCfgMgr( 2345): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/PostponalbeReceiver( 5170): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.intent.action.TIME_SET'.
I/ActivityManager( 1031): Start proc com.lge.clock for broadcast com.lge.clock/.alarmclock.ALBootInit: pid=6894 uid=10010 gids={50010, 9997, 3003, 1028, 4002} abi=armeabi-v7a
,I/CheckinRequestBuilder( 2345): Checkin reason type: 12 attempt count: 1
,I/GLSUser ( 2129): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: ac2dm
I/GLSUser ( 2129): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> ac2dm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2129): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2129): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
D/WifiService( 1031): New client listening to asynchronous messages
E/ActivityThread( 2345): Failed to find provider info for com.google.android.wearable.settings
V/GLSActivity( 2129): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1031): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1031): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1031): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1031): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1031): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1415): onNotificationPosted
W/Kids    ( 2345): [AccountUtils] Account not ready
W/Kids    ( 2345): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/Kids    ( 2345): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/Kids    ( 2345): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/Kids    ( 2345): 	at com.google.android.gms.auth.p.c(SourceFile:550)
W/Kids    ( 2345): 	at com.google.android.gms.auth.p.b(SourceFile:477)
W/Kids    ( 2345): 	at com.google.android.gms.kids.account.k.d(SourceFile:103)
W/Kids    ( 2345): 	at com.google.android.gms.kids.account.p.a(SourceFile:70)
W/Kids    ( 2345): 	at com.google.android.gms.kids.account.t.a(SourceFile:62)
W/Kids    ( 2345): 	at com.google.android.gms.chimera.f.run(SourceFile:179)
W/Kids    ( 2345): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Kids    ( 2345): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Kids    ( 2345): 	at java.lang.Thread.run(Thread.java:818)
D/SmartCoverUpdateMonitor( 1415): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1415): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1415): handleNotificationPosted(true)
D/QuickCircle( 1415): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1415): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1415): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1415): post do just update job
D/LgeQuickCoverNotificationData( 1415): showAll3
D/LgeQuickCoverNotificationData( 1415): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1415): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1415): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1415): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1415): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1415): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1415): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1415): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1415): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1415): isNotificationForCurrentUser : true
,E/LgeQuickCoverOverlayWindow( 1415): updateNotificationData: count=3
D/QuickStatusbarLayout( 1415): Notification difference=198
D/QuickStatusbarLayout( 1415): child = android.widget.LinearLayout{9d5fc15 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,D/ALBootInit( 6894): ====action==>android.intent.action.TIME_SET
,D/ALBootInit( 6894): Alarm ALBootInit: TIME_SET
D/Alarms  ( 6894): [setNextAlert] start
,D/Alarms  ( 6894): [setNextAlert] (1)
I/art     ( 2345): Explicit concurrent mark sweep GC freed 12907(1061KB) AllocSpace objects, 18(288KB) LOS objects, 49% free, 32MB/64MB, paused 1.331ms total 52.391ms
,D/GCM     ( 2129): Connected
,I/art     ( 1031): Explicit concurrent mark sweep GC freed 20144(871KB) AllocSpace objects, 4(448KB) LOS objects, 33% free, 44MB/66MB, paused 1.310ms total 73.686ms
D/Alarms  ( 6894):  minTime  = 0
,D/Alarms  ( 6894):  -- OK multi -- 0
I/VacuumService( 2129): Vacuum at: now=1449832529473 tag=VacuumService
E/jeny.kim( 6894): [setNextAlert] setNextAlert  temp_Alarmlink + 
E/jeny.kim( 6894): [setNextAlert]setNextAlert temp_AlarmLinkText + 
I/GoogleURLConnFactory( 2129): Using platform SSLCertificateSocketFactory
D/GCM     ( 2129): Message class com.google.f.a.a.p
,W/Uploader( 2129): No account for auth token provided
,I/CommonUtil( 6894): BUILD Country: EU
D/Alarms  ( 6894): broadcastToWidgetProvider : false
D/Alarms  ( 6894): Enter formatDayAndTime(final Context context, long timeInMiliSec)
V/GLSActivity( 2129): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/SettingsProvider( 1031): call_put(system:next_alarm_formatted=) for 0 calling package = com.lge.clock
I/DigitalAppWidgetProvider( 6894): onReceive: android.intent.action.TIME_SET
,V/DigitalAppWidgetProvider( 6894): cancelAlarmOnQuarterHour android.app.ReceiverRestrictedContext@369476c2
V/DigitalAppWidgetProvider( 6894): startAlarmOnQuarterHour android.app.ReceiverRestrictedContext@369476c2
D/QuickCoverProvider( 6894): onReceiver
I/indal   ( 1415): SmartCoverWidgetContext createApplicationContext
I/indal   ( 1415): SmartCoverWidgetContext createApplicationContext
,D/libc-netbsd(  323): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  323): res_queryN name = play.googleapis.com, class = 1, type = 1
D/WeatherAncestor( 6755): 2 : onReceive, action: android.intent.action.TIME_SET, Time(hour:min:sec) 12:15:29
D/Weather.Utils( 6755): 2 : the weather widgets(using time tick) are gone.
D/Weather.Utils( 6755): 2 : All the weather widget is gone.
D/UpdateThreadPoolManager( 6755): 2 : This is isUpdating : false
,I/GLSUser ( 2129): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2129): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2129): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2129): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
D/WeatherService( 6755): 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@1571dcd3
D/ForecastDataCache( 6755): 2 : lastUpdatedTime: 1430558561343
D/ForecastDataCache( 6755): 2 : currentPackageVersion: 4.40.4
D/ForecastDataCache( 6755): 2 : Cache is up-to-date, count: 0
V/GLSActivity( 2129): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/Weather_cast( 6755): 2 : set auto-update time : 12/11 15:15
D/WeatherAncestor( 6755): 2 : onReceive has processed, action: android.intent.action.TIME_SET, Time(hour:min:sec) 12:15:29
,I/GLSUser ( 2129): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: AndroidCheckInServer
I/GLSUser ( 2129): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> AndroidCheckInServer without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2129): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2129): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
I/ActivityManager( 1031): Start proc com.qualcomm.timeservice for broadcast com.qualcomm.timeservice/.TimeServiceBroadcastReceiver: pid=6925 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,I/ActivityManager( 1031): Killing 5956:com.lge.bnr/1000 (adj 15): empty #17
D/libc-netbsd(  323): res_queryN name = play.googleapis.com succeed
I/art     (  360): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 356us total 18.312ms
,I/art     (  360): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 339us total 17.649ms
,I/art     (  360): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 339us total 15.557ms
,W/libprocessgroup( 1031): failed to open /acct/uid_1000/pid_5956/cgroup.procs: No such file or directory
,V/GLSActivity( 2129): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1031): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1031): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1031): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1031): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1031): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1415): onNotificationPosted
W/GLSActivity( 2129): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2129): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2129): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2129): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2129): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2129): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2129): 	at android.os.Binder.execTransact(Binder.java:446)
D/SmartCoverUpdateMonitor( 1415): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1415): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1415): handleNotificationPosted(true)
D/QuickCircle( 1415): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1415): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1415): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1415): post do just update job
D/LgeQuickCoverNotificationData( 1415): showAll3
D/LgeQuickCoverNotificationData( 1415): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1415): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1415): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1415): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1415): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1415): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1415): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1415): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1415): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1415): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1415): updateNotificationData: count=3
,E/BooksAccountManager( 6604): Authentication error
E/BooksAccountManager( 6604): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6604): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6604): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6604): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6604): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6604): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6604): null auth token
V/NotificationService( 1031): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/TimeService( 6925): Receivedandroid.intent.action.TIME_SET intent. Current Time is 1449832529716
D/        ( 6925): TimeServiceNative: User Time to be set is 1449832529716
D/QC-time-services( 6925): Lib:time_genoff_operation: pargs->base = 2
D/QC-time-services( 6925): Lib:time_genoff_operation: pargs->operation = 0
D/QC-time-services( 6925): Lib:time_genoff_operation: pargs->ts_val = 1449832529716
D/QC-time-services(  382): Daemon: Connection accepted:time_genoff
D/QC-time-services(  382): Daemon:Received base = 2, unit = 1, operation = 0,value = 1449832529716
D/QC-time-services(  382): Daemon:genoff_opr: Base = 2, val = 1449832529716, operation = 0
,D/QC-time-services(  382): Daemon:rtc_get: Time read from RTC -- MM/DD/YY HH:MM:SS3/20/70 4:28:11
V/NotificationService( 1031): pkg=com.google.android.gms canInterrupt=false intercept=true
D/QC-time-services(  382): Daemon:Value read from RTC seconds = 9433691000
I/NotificationServiceEx( 1031): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/QC-time-services(  382): Daemon:new time 1449832529716 
D/QC-time-services(  382): Daemon: delta 1440398838716 genoff 1440398838716 
D/NotificationServiceEx( 1031): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/QC-time-services(  382): Daemon:genoff_persistent_update: Writing genoff = 1440398838716 to memory
D/QC-time-services(  382): Daemon:Opening File: /data/time/ats_2
D/QC-time-services(  382): Daemon:time_persistent_memory_opr:Genoff write operation 
D/NotificationServiceEx( 1031): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/QC-time-services( 6925): Lib:time_genoff_operation: Send to server  passed!!
D/QuickStatusbarLayout( 1415): Notification difference=198
D/QuickStatusbarLayout( 1415): child = android.widget.LinearLayout{9d5fc15 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
W/CheckinRequestBuilder( 2345): awaiting user notification for token
D/LgeQuickCoverNLService( 1415): onNotificationPosted
D/SmartCoverUpdateMonitor( 1415): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1415): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1415): handleNotificationPosted(true)
D/QuickCircle( 1415): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1415): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1415): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1415): post do just update job
D/LgeQuickCoverNotificationData( 1415): showAll3
D/LgeQuickCoverNotificationData( 1415): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1415): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1415): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
D/QC-time-services(  382): Updating the TOD offset
D/QC-time-services(  382): Daemon:genoff_persistent_update: Writing genoff = 1440398838716 to memory
D/QC-time-services(  382): Daemon:Opening File: /data/time/ats_1
E/LgeQuickCoverOverlayWindow( 1415): showNotificationWithSetupData: display=false
D/QC-time-services(  382): Daemon:time_persistent_memory_opr:Genoff write operation 
D/LgeQuickCoverOverlayWindow( 1415): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1415): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1415): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1415): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1415): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1415): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1415): updateNotificationData: count=3
E/QC-time-services(  382): Daemon:Update to modem bit set
D/QC-time-services(  382): Daemon:genoff_send_modem: Sending data to MODEM !
D/QC-time-services(  382): Daemon: Base = 2, Value being sent to MODEM = 1124434038716
E/QC-time-services( 6925): Receive Passed == base = 2, unit = 1, operation = 0, result = 0
,E/QC-time-services(  382): Daemon:tod_update_ind_cb: Got Update from modem msg_id 40
,E/QC-time-services(  382): Daemon: Time-services: Waiting to acceptconnection
D/QuickStatusbarLayout( 1415): Notification difference=198
D/QuickStatusbarLayout( 1415): child = android.widget.LinearLayout{9d5fc15 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,I/ActivityManager( 1031): Start proc com.android.calendar for broadcast com.android.calendar/.widget.CalendarAppWidgetProvider: pid=6943 uid=10013 gids={50013, 9997, 3003, 1028, 1015} abi=armeabi
,I/ActivityManager( 1031): Killing 6362:com.lge.lifetracker/u0a37 (adj 15): empty #17
D/sensors_hal_Time( 1031): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1031): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1031): tsOffsetIs: Apps: 295467293017; DSPS: 9822949; Offset : -4322611158
W/libprocessgroup( 1031): failed to open /acct/uid_10037/pid_6362/cgroup.procs: No such file or directory
W/ApiaryClient( 6604): Error response from books API: {
W/ApiaryClient( 6604):  "error": {
W/ApiaryClient( 6604):   "errors": [
W/ApiaryClient( 6604):    {
W/ApiaryClient( 6604):     "domain": "global",
W/ApiaryClient( 6604):     "reason": "required",
W/ApiaryClient( 6604):     "message": "Login Required",
W/ApiaryClient( 6604):     "locationType": "header",
W/ApiaryClient( 6604):     "location": "Authorization"
W/ApiaryClient( 6604):    }
W/ApiaryClient( 6604):   ],
W/ApiaryClient( 6604):   "code": 401,
W/ApiaryClient( 6604):   "message": "Login Required"
W/ApiaryClient( 6604):  }
W/ApiaryClient( 6604): }
W/ApiaryClient( 6604): errCount = 2: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6604): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-1888646283833582182&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6604): Headers:
W/ApiaryClient( 6604): accept-encoding: [gzip]
W/ApiaryClient( 6604): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6604): gdata-version: 2
,W/ResourcesManager( 6943): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/ActivityManager( 1031): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=6961 uid=10005 gids={50005, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
,D/CalendarApplication( 6943): CalendarApplication.onCreate()
,D/PreferenceKeysParser( 6943): [debug_displayParseInfos] preference keys.size() = 44
,D/PreferenceKeysParser( 6943): [debug_displayParseInfos] preference keys = {lg_preferences_tardis_1=com.android.calendar.adaptation.PreferenceKey$KeyData@348dded1, lg_preferences_hide_declined=com.android.calendar.adaptation.PreferenceKey$KeyData@f1bd36, lg_preferences_default_reminder=com.android.calendar.adaptation.PreferenceKey$KeyData@1c583437, lg_preferences_month_view_style=com.android.calendar.adaptation.PreferenceKey$KeyData@b012da4, lg_preferences_alerts_ringtone=com.android.calendar.adaptation.PreferenceKey$KeyData@3c40970d, lg_preferences_device_tz=com.android.calendar.adaptation.PreferenceKey$KeyData@369476c2, lg_preferences_debug_datesearch=com.android.calendar.adaptation.PreferenceKey$KeyData@1571dcd3, lg_preferences_debug_country=com.android.calendar.adaptation.PreferenceKey$KeyData@30f58010, lg_preferences_display_weather_information=com.android.calendar.adaptation.PreferenceKey$KeyData@1ec9709, lg_preferences_alerts_vibrateWhen=com.android.calendar.adaptation.PreferenceKey$KeyData@1b73d0e, lg_preferences_debug_rtl=com.android.calendar.adaptation.PreferenceKey$KeyData@1673732f, lg_preferences_alerts_type=com.android.calendar.adaptation.PreferenceKey$KeyData@19a8d3c, lg_preferrences_country_code=com.android.calendar.adaptation.PreferenceKey$KeyData@3e3e9ac5, lg_preferences_weather_info=com.android.calendar.adaptation.PreferenceKey$KeyData@d2e1c1a, lg_preference_holiday_calendar_ver=com.android.calendar.adaptation.PreferenceKey$KeyData@3f4e134b, lg_preferences_show_controls=com.android.calendar.adaptation.PreferenceKey$KeyData@35214128, lg_preferences_user_select_noti_sound=com.android.calendar.adaptation.PreferenceKey$KeyData@df31e41, lg_preference_default_myphonebook=com.android.calendar.adaptation.PreferenceKey$KeyData@2b01dfe6, lg_preferences_skip_setup=com.android.calendar.adaptation.PreferenceKey$KeyData@33e89927, lg_preferred_startView=com.android.calendar.adaptation.PreferenceKey$KeyData@13dd47d4, lg_preferences_debug_operator=com.android.calendar.adaptation.PreferenceKey$KeyData@3125d7d, lg_preferences_exclude_sticker_list=com.android.calendar.adaptation.PreferenceKey$KeyData@32fc1472, lg_preferences_writable_calendars_count=com.android.calendar.adaptation.PreferenceKey$KeyData@5bba0c3, lg_preferred_detailedView=com.android.calendar.adaptation.PreferenceKey$KeyData@35b10d40, lg_preferences_debug_floating=com.android.calendar.adaptation.PreferenceKey$KeyData@dec5479, lg_preferences_home_tz=com.android.calendar.adaptation.PreferenceKey$KeyData@3df305be, lg_preferences_home_tz_enabled=com.android.calendar.adaptation.PreferenceKey$KeyData@1b2d861f, lg_preference_received_provider_reminder_broadcast=com.android.calendar.adaptation.PreferenceKey$KeyData@c39bd6c, lg_preferences_default_cell_height=com.android.calendar.adaptation.PreferenceKey$KeyData@39d4bf35, lg_preferences_notification_type=com.android.calendar.adaptation.PreferenceKey$KeyData@9d5bfca, lg_preferences_show_week_num=com.android.calendar.adaptation.PreferenceKey$KeyData@30ae653b, lg_preferences_dont_show_again_no_online_account=com.android.calendar.adaptation.PreferenceKey$KeyData@23bb4458, lg_preferences_alerts_popup=com.android.calendar.adaptation.PreferenceKey$KeyData@399f19b1, lg_preferences_week_start_day=com.android.calendar.adaptation.PreferenceKey$KeyData@12780e96, lg_preferences_app_version=com.android.calendar.adaptation.PreferenceKey$KeyData@f941a17, lg_preferences_alerts=com.android.calendar.adaptation.PreferenceKey$KeyData@6cc4e04, lg_preferences_select_aux_calendar=com.android.calendar.adaptation.PreferenceKey$KeyData@3fda9fed, lg_preferences_widget_info_calendars=com.android.calendar.adaptation.PreferenceKey$KeyData@2b1e7e22, lg_preferences_alerts_default_ringtone=com.android.calendar.adaptation.PreferenceKey$KeyData@16b640b3, lg_preference_defaultCalendar=com.android.calendar.adaptation.PreferenceKey$KeyData@30c24670, lg_preferences_alerts_vibratetype=com.android.calendar.adaptation.PreferenceKey$KeyData@1ece4de9, lg_preferences_recent_timezones=com.android.calendar.adaptation.PreferenceKey$KeyData@24ca5a6e, lg_
D/GeneralP,referenceUtils( 6943): [migratePrefrenceKeys] Exit: Version(44001600) >= 42001300
D/Config  ( 6943): [init]
,I/Config  ( 6943): LGCalendar ver.4.40.16
I/Config  ( 6943): start check model
I/Config  ( 6943): start check native_ca
I/Config  ( 6943): Config Operator=OPEN, Country=EU
D/Config  ( 6943): [setDefaultValuesToPref]
D/Config  ( 6943): [parseProfiles]
,D/ProfilesParser( 6943): [debug_displayParseInfos] profile.country = null
D/ProfilesParser( 6943): [debug_displayParseInfos] profile.operator = null
D/Config  ( 6943): [updateProfiletoCountryInfo]
D/GeneralPreference( 6943): [checkAndMigrateOldPreference]
E/AgendaWidgetManager( 6943): [updateWidgets] 
,W/Uploader( 2129): No account for auth token provided
I/InitNotificationRingtoneService( 6943): Start InitializeAlertRingtoneService.onHandleIntent
I/AlertUtils( 6943): [setFormatNotificationSound] current noti URI = content://media/internal/audio/media/41
W/ResourcesManager( 6961): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6961): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
I/AlertUtils( 6943): [getCalendarNotiSoundURIFromCursor] getCount()= 21
,I/AlertUtils( 6943): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Arpeggio.ogg
I/AlertUtils( 6943): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Country_Blues.ogg
I/AlertUtils( 6943): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Crystal.ogg
I/AlertUtils( 6943): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Dewdrop.ogg
I/AlertUtils( 6943): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Ding_Dong.ogg
,I/AlertUtils( 6943): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Echo.ogg
I/AlertUtils( 6943): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Email.ogg
I/AlertUtils( 6943): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Game_Over.ogg
,I/AlertUtils( 6943): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Gayageum.ogg
I/AlertUtils( 6943): [getMediaFilepathFromContentUri] filepath = /system/media/audio/alarms/Afternoon_Walk.ogg
I/AlertUtils( 6943): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Harmonics.ogg
I/MultiDex( 6961): VM with version 2.1.0 has multidex support
I/MultiDex( 6961): install
I/MultiDex( 6961): VM has multidex support, MultiDex support library is disabled.
I/AlertUtils( 6943): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Idea.ogg
,I/AlertUtils( 6943): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/News.ogg
I/AlertUtils( 6943): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Pebble.ogg
I/AlertUtils( 6943): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Schedule.ogg
I/AlertUtils( 6943): [getCalendarNotiSoundURIFromCursor] filePath = /system/media/audio/notifications/Schedule.ogg, new URI = content://media/internal/audio/media/41
I/AlertUtils( 6943): set default noti to content://media/internal/audio/media/41
,I/InitNotificationRingtoneService( 6943): End InitializeAlertRingtoneService.onHandleIntent
V/JNIHelp ( 6961): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
D/MonthWidgetProvider( 6943): [onReceive]
D/CalendarWidgetProvider( 6943): [onReceive]
D/CalendarWidgetProvider( 6943): [CalendarWidgetProvider] got the intent: Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.android.calendar/.widget.MonthWidgetProvider }
W/HolidayIntentService( 6943): onHandleIntent
,D/HolidayDataLoader( 6943): readJsonAsset : holiday.json
D/CalendarTypeController( 6943): [onUpdateAndInitCalendarTime]
D/WeekWidgetProvider( 6943): [onReceive]
D/CalendarWidgetProvider( 6943): [onReceive]
D/CalendarWidgetProvider( 6943): [CalendarWidgetProvider] got the intent: Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.android.calendar/.widget.WeekWidgetProvider }
,D/CalendarTypeController( 6943): [onUpdateAndInitCalendarTime]
E/HolidayIntentService( 6943): onHandleIntent:holiday data empty
,I/ActivityManager( 1031): Killing 6411:com.lge.settings.easy/1000 (adj 15): empty #17
W/ActivityThread( 6961): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 6961): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@a383b1e: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6961): Installed default security provider GmsCore_OpenSSL
I/art     ( 2129): Explicit concurrent mark sweep GC freed 39242(2MB) AllocSpace objects, 17(1959KB) LOS objects, 50% free, 30MB/62MB, paused 743us total 45.978ms
,W/libprocessgroup( 1031): failed to open /acct/uid_1000/pid_6411/cgroup.procs: No such file or directory
,W/Uploader( 2129):  no longer exists, so no auth token.
I/ActivityManager( 1031): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.realtimechat.RequestWriter$NetworkStateReceiver: pid=6987 uid=10072 gids={50072, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,W/ResourcesManager( 6987): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,D/WVCdm   (  328): Instantiating CDM.
,I/WVCdm   (  328): CdmEngine::OpenSession
I/WVCdm   (  328): Level3 Library Sep 25 2014 17:10:03
W/WVCdm   (  328): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
,D/LgDataFeature( 6987): LgDataFeature() Constructor: none
D/LgDataFeature( 6987): LgDataFeature() Constructor Done, null
,D/DrmWidevineDash(  328): OEMCrypto_Initialize: starts! g_qsee_apps_version = 0x13
D/DrmWidevineDash(  328): Service_Initialize: starts!
,D/QSEECOMAPI: (  328): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  328): App is not loaded in QSEE
I/GoogleURLConnFactory( 6961): Using platform SSLCertificateSocketFactory
,D/QSEECOMAPI: (  328): Loaded image: APP id = 3
D/DrmWidevineDash(  328): Service_Initialize: ends! returns 0
D/DrmWidevineDash(  328): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb0968000
E/DrmWidevineDash(  328): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb0968000
D/libc-netbsd(  323): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  323): res_queryN name = www.googleapis.com, class = 1, type = 1
D/libc-netbsd(  323): res_queryN name = www.googleapis.com succeed
,D/DrmWidevineDash(  328): OEMCrypto_Initialize: ends! returns 0
D/DrmWidevineDash(  328): OEMCrypto_APIVersion: starts!
D/DrmWidevineDash(  328): hlos api version =  9
D/DrmWidevineDash(  328): tz api version =  8
D/DrmWidevineDash(  328): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  328): OEMCrypto_IsKeyboxValid: starts!
I/Babel   ( 6987): MmsConfig: mnc/mcc: 0/0
I/Babel   ( 6987): MmsConfig.loadMmsSettings
D/DrmWidevineDash(  328): OEMCrypto_IsKeyboxValid: ends! returns 0
D/WVCdm   (  328): OEMCrypto_Initialize Level 1 success. I will use level 1.
D/DrmWidevineDash(  328): OEMCrypto_OpenSession: starts! SID=0xb0cff940
D/DrmWidevineDash(  328): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  328): OEMCrypto_OpenSession: ends! returns 0
D/DrmWidevineDash(  328): OEMCrypto_GetRandom: starts! randomData=0xb1426620, dataLength=8
D/DrmWidevineDash(  328): OEMCrypto_GetRandom: ends! returns 0
D/DrmWidevineDash(  328): OEMCrypto_LoadDeviceRSAKey: starts!SID=1, wrapped_rsa_key=0xb14dbc00, wrapped_rsa_key_length=1280
,D/DrmWidevineDash(  328): OEMCrypto_LoadDeviceRSAKey: ends! returns 0
I/WVCdm   (  328): CdmEngine::QueryKeyControlInfo
W/WVCdm   (  328): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  328): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  328): CdmEngine::GenerateKeyRequest
D/DrmWidevineDash(  328): OEMCrypto_GetDeviceID: starts! deviceID=0xb543dd40, idLength=0xbe874ff0
I/Babel   ( 6987): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D855 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D855-M3-D1.xml
I/Babel   ( 6987): MmsConfig.loadFromDatabase
D/DrmWidevineDash(  328): OEMCrypto_GetDeviceID: ends! returns 0
D/DrmWidevineDash(  328): OEMCrypto_SupportsUsageTable: starts!
D/DrmWidevineDash(  328): OEMCrypto_SupportsUsageTable: is_supported = 1
D/DrmWidevineDash(  328): OEMCrypto_SupportsUsageTable: wv_app_version = 25
D/DrmWidevineDash(  328): OEMCrypto_SupportsUsageTable: ends! returns 0x0
D/DrmWidevineDash(  328): OEMCrypto_GetHDCPCapability: starts!
D/DrmWidevineDash(  328): OEMCrypto_GetHDCPCapability: ends! returns 0x0
D/DrmWidevineDash(  328): OEMCrypto_APIVersion: starts!
D/DrmWidevineDash(  328): hlos api version =  9
D/DrmWidevineDash(  328): tz api version =  8
D/DrmWidevineDash(  328): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  328): OEMCrypto_GenerateNonce: starts! SID=1
D/DrmWidevineDash(  328): OEMCrypto_GenerateNonce: ends! returns 0
D/WVCdm   (  328): PrepareKeyRequest: nonce=3608115488
D/DrmWidevineDash(  328): OEMCrypto_GenerateRSASignature starts! SID=1, message=0xb57aad00
D/DrmWidevineDash(  328): message_length=1597, signature=0xb148b680, signature_length=3196538836
,E/Babel   ( 6987): canonicalizeMccMnc: invalid mccmnc 
I/Babel   ( 6987): MmsConfig.loadFromResources
E/Babel   ( 6987): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel   ( 6987): MmsConfig.loadMmsSettings: mUserAgent=LG-D855 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D855-M3-D1.xml
W/AudioCapabilities( 6987): Unsupported mime audio/evrc
W/AudioCapabilities( 6987): Unsupported mime audio/qcelp
W/VideoCapabilities( 6987): Unrecognized profile 2130706433 for video/avc
W/Settings( 6987): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/AudioCapabilities( 6987): Unsupported mime audio/amr-wb-plus
W/AudioCapabilities( 6987): Unsupported mime audio/qcelp
W/AudioCapabilities( 6987): Unsupported mime audio/evrc
,W/VideoCapabilities( 6987): Unsupported mime video/x-ms-wmv
W/VideoCapabilities( 6987): Unsupported mime video/divx
W/VideoCapabilities( 6987): Unsupported mime video/divx311
W/VideoCapabilities( 6987): Unsupported mime video/divx4
,W/VideoCapabilities( 6987): Unsupported mime video/mp4v-esdp
I/DigitalAppWidgetProvider( 6894): onReceive: android.intent.action.ALARM_CHANGED
D/WeatherAncestor( 6755): 2 : onReceive, action: com.lge.sizechangable.weather.action.setweathercast, Time(hour:min:sec) 12:15:30
D/Weather.Utils( 6755): 2 : the weather widgets(using time tick) are gone.
D/DrmWidevineDash(  328): OEMCrypto_GenerateRSASignature returns 0
D/Weather.Utils( 6755): 2 : All the weather widget is gone.
D/UpdateThreadPoolManager( 6755): 2 : This is isUpdating : false
I/WVCdm   (  328): CdmEngine::CloseSession
D/DrmWidevineDash(  328): OEMCrypto_CloseSession: starts! SID=1
D/DrmWidevineDash(  328): OEMCrypto_CloseSession: ends! returns 0
I/WVCdm   (  328): L3 Terminate.
D/DrmWidevineDash(  328): OEMCrypto_Terminate: starts!
D/Weather_cast( 6755): 2 : Update is Canceled by com.lge.sizechangable.weather.action.alarm
D/WeatherAncestor( 6755): 2 : onReceive has processed, action: com.lge.sizechangable.weather.action.setweathercast, Time(hour:min:sec) 12:15:30
D/DrmWidevineDash(  328): Service_Uninitialize: starts!
D/QSEECOMAPI: (  328): QSEECom_dealloc_memory 
D/QSEECOMAPI: (  328): QSEECom_shutdown_app, app_id = 3
D/DrmWidevineDash(  328): Service_Uninitialize: ends! returns 0x0
D/DrmWidevineDash(  328): OEMCrypto_Terminate: ends! returns 0
,D/GCM     ( 2129): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
D/AuthorizationBluetoothService( 2129): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
V/GmsCoreStatsServiceLauncher( 2345): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=5.9, 0.0, 0.0  rx=4.8 bcn=0 [on:0 tx:0 rx:0 period:3000] from screen [on:0 period:-1866415463] gl rssi=-45 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=5.9, 0.0, 0.0  rx=4.8 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-1866415462] gl rssi=-45 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
I/VideoCapabilities( 6987): Unsupported profile 4 for video/mp4v-es
,W/ResourcesManager( 6987): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6987): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
W/AudioCapabilities( 6987): Unsupported mime audio/eac3
W/AudioCapabilities( 6987): Unsupported mime audio/ac3
W/AudioCapabilities( 6987): Unsupported mime audio/g726
W/AudioCapabilities( 6987): Unsupported mime audio/wma-voice
,W/AudioCapabilities( 6987): Unsupported mime audio/x-ms-wma
W/AudioCapabilities( 6987): Unsupported mime audio/adpcm
W/VideoCapabilities( 6987): Unsupported mime video/theora
W/VideoCapabilities( 6987): Unsupported mime video/mjpg
I/ActivityManager( 1031): Start proc com.google.android.gms.wearable for service com.google.android.gms/.wearable.service.WearableService: pid=7020 uid=10005 gids={50005, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
,D/LocationInitializer( 2345): Restart initialization of location
,W/ResourcesManager( 7020): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 7020): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 6987): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,I/MultiDex( 7020): VM with version 2.1.0 has multidex support
I/MultiDex( 7020): install
I/MultiDex( 7020): VM has multidex support, MultiDex support library is disabled.
V/JNIHelp ( 7020): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,W/System  ( 6987): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/system/framework/com.google.android.media.effects.jar", zip file "/system/app/Hangouts/Hangouts.apk"],nativeLibraryDirectories=[/system/app/Hangouts/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6987): Installed default security provider GmsCore_OpenSSL
,W/ActivityThread( 7020): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 7020): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@a383b1e: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 7020): Installed default security provider GmsCore_OpenSSL
,D/WearableService( 7020): callingUid 10005, callindPid: 7020
E/MDM     ( 1832): [86] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,D/GCM     ( 2129): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
D/AuthorizationBluetoothService( 2129): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
V/GmsCoreStatsServiceLauncher( 2345): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
E/MDM     ( 1832): [87] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,W/Uploader( 2129): No account for auth token provided
D/LocationInitializer( 2345): Restart initialization of location
V/GLSActivity( 2129): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2129): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.talk, service: oauth2:https://www.googleapis.com/auth/chat https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/hangouts https://www.googleapis.com/auth/identity.plus.page.impersonation https://www.googleapis.com/auth/chat.native
I/GLSUser ( 2129): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/chat https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/hangouts https://www.googleapis.com/auth/identity.plus.page.impersonation https://www.googleapis.com/auth/chat.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2129): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2129): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2129): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2129): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2129): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2129): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2129): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2129): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
E/Babel   ( 6987): UserRecoverableAuthException.
E/Babel   ( 6987): cfq: BadAuthentication
E/Babel   ( 6987): 	at cfn.a(Unknown Source)
E/Babel   ( 6987): 	at f.a(PG:191)
E/Babel   ( 6987): 	at ava.a(PG:88)
E/Babel   ( 6987): 	at ava.a(PG:128)
E/Babel   ( 6987): 	at bjs.a(PG:255)
E/Babel   ( 6987): 	at bep.a(PG:602)
E/Babel   ( 6987): 	at bep.a(PG:469)
E/Babel   ( 6987): 	at bpo.run(PG:1141)
E/Babel   ( 6987): Error getting auth token
E/Babel   ( 6987): bxl
E/Babel   ( 6987): 	at f.a(PG:201)
E/Babel   ( 6987): 	at ava.a(PG:88)
E/Babel   ( 6987): 	at ava.a(PG:128)
E/Babel   ( 6987): 	at bjs.a(PG:255)
E/Babel   ( 6987): 	at bep.a(PG:602)
E/Babel   ( 6987): 	at bep.a(PG:469)
E/Babel   ( 6987): 	at bpo.run(PG:1141)
I/Babel_RequestWriter( 6987): error sending REQ[fc:12; creat:1449796653865; type:bev-787623987]; took 201 ms (error code == 100)
,E/Babel   ( 6987): Account registration failedRedacted-21
E/Babel   ( 6987): bph: null -- null
E/Babel   ( 6987): 	at ava.a(PG:120)
E/Babel   ( 6987): 	at ava.a(PG:128)
E/Babel   ( 6987): 	at bjs.a(PG:255)
E/Babel   ( 6987): 	at bep.a(PG:602)
E/Babel   ( 6987): 	at bep.a(PG:469)
E/Babel   ( 6987): 	at bpo.run(PG:1141)
I/Babel   ( 6987): Account setup failed with error state:106 account:Redacted-21
I/Babel   ( 6987): Account sign in complete with state 106account: Redacted-21
V/NotificationService( 1031): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1031): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1031): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1031): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1031): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1415): onNotificationPosted
,W/GLSActivity( 2129): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2129): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2129): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2129): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2129): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2129): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2129): 	at android.os.Binder.execTransact(Binder.java:446)
I/art     ( 6987): Note: end time exceeds epoch: 
E/BooksAccountManager( 6604): Authentication error
E/BooksAccountManager( 6604): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6604): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6604): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6604): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6604): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6604): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6604): null auth token
D/SmartCoverUpdateMonitor( 1415): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1415): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1415): handleNotificationPosted(true)
D/QuickCircle( 1415): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1415): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1415): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1415): post do just update job
D/LgeQuickCoverNotificationData( 1415): showAll3
D/LgeQuickCoverNotificationData( 1415): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1415): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1415): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1415): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1415): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1415): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1415): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1415): isNotificationForCurrentUser : true
,D/LgeQuickCoverOverlayWindow( 1415): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1415): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1415): updateNotificationData: count=3
I/GLSUser ( 2129): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.talk, service: oauth2:https://www.googleapis.com/auth/chat https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/hangouts https://www.googleapis.com/auth/identity.plus.page.impersonation https://www.googleapis.com/auth/chat.native
I/GLSUser ( 2129): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/chat https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/hangouts https://www.googleapis.com/auth/identity.plus.page.impersonation https://www.googleapis.com/auth/chat.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2129): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2129): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2129): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/QuickStatusbarLayout( 1415): Notification difference=198
D/QuickStatusbarLayout( 1415): child = android.widget.LinearLayout{9d5fc15 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
W/ResourcesManager( 2129): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,V/NotificationService( 1031): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1031): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1031): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1031): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1031): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1415): onNotificationPosted
E/Babel   ( 6987): Unexpected exception while authenticating.
D/SmartCoverUpdateMonitor( 1415): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1415): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1415): handleNotificationPosted(true)
D/QuickCircle( 1415): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1415): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1415): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1415): post do just update job
D/LgeQuickCoverNotificationData( 1415): showAll3
D/LgeQuickCoverNotificationData( 1415): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1415): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1415): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1415): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1415): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1415): isNotificationForCurrentUser : true
E/Babel   ( 6987): cfr: User intervention required. Notification has been pushed.
E/Babel   ( 6987): 	at cfn.b(Unknown Source)
E/Babel   ( 6987): 	at cfn.a(Unknown Source)
E/Babel   ( 6987): 	at f.a(PG:188)
E/Babel   ( 6987): 	at ava.b(PG:143)
E/Babel   ( 6987): 	at bnr.run(PG:5415)
E/Babel   ( 6987): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/Babel   ( 6987): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/Babel   ( 6987): 	at java.lang.Thread.run(Thread.java:818)
D/LgeQuickCoverOverlayWindow( 1415): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1415): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1415): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1415): isNotificationForCurrentUser : true
,E/LgeQuickCoverOverlayWindow( 1415): updateNotificationData: count=3
D/QuickStatusbarLayout( 1415): Notification difference=198
D/QuickStatusbarLayout( 1415): child = android.widget.LinearLayout{9d5fc15 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,W/ApiaryClient( 6604): Error response from books API: {
W/ApiaryClient( 6604):  "error": {
W/ApiaryClient( 6604):   "errors": [
W/ApiaryClient( 6604):    {
W/ApiaryClient( 6604):     "domain": "global",
W/ApiaryClient( 6604):     "reason": "required",
W/ApiaryClient( 6604):     "message": "Login Required",
W/ApiaryClient( 6604):     "locationType": "header",
W/ApiaryClient( 6604):     "location": "Authorization"
W/ApiaryClient( 6604):    }
W/ApiaryClient( 6604):   ],
W/ApiaryClient( 6604):   "code": 401,
W/ApiaryClient( 6604):   "message": "Login Required"
W/ApiaryClient( 6604):  }
W/ApiaryClient( 6604): }
W/ApiaryClient( 6604): errCount = 3: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6604): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-1888646283833582182&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6604): Headers:
W/ApiaryClient( 6604): accept-encoding: [gzip]
W/ApiaryClient( 6604): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6604): gdata-version: 2
,W/Uploader( 2129): No account for auth token provided
,W/Uploader( 2129): No account for auth token provided
E/BooksSync( 6604): Soft error: 
E/BooksSync( 6604): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 6604): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-1888646283833582182&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 6604): Headers:
E/BooksSync( 6604): accept-encoding: [gzip]
E/BooksSync( 6604): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 6604): gdata-version: 2
E/BooksSync( 6604): 
E/BooksSync( 6604): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 6604): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 6604): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 6604): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 6604): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 6604): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 6604): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 6604): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 6604): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 6604): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 6604): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 6604): {
E/BooksSync( 6604):  "error": {
E/BooksSync( 6604):   "errors": [
E/BooksSync( 6604):    {
E/BooksSync( 6604):     "domain": "global",
E/BooksSync( 6604):     "reason": "required",
E/BooksSync( 6604):     "message": "Login Required",
E/BooksSync( 6604):     "locationType": "header",
E/BooksSync( 6604):     "location": "Authorization"
E/BooksSync( 6604):    }
E/BooksSync( 6604):   ],
E/BooksSync( 6604):   "code": 401,
E/BooksSync( 6604):   "message": "Login Required"
E/BooksSync( 6604):  }
E/BooksSync( 6604): }
E/BooksSync( 6604): 
E/BooksSync( 6604): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 6604): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 6604): 	... 8 more
E/BooksSync( 6604): Sync error
E/BooksSync( 6604): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 6604): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-1888646283833582182&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 6604): Headers:
E/BooksSync( 6604): accept-encoding: [gzip]
E/BooksSync( 6604): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 6604): gdata-version: 2
E/BooksSync( 6604): 
E/BooksSync( 6604): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 6604): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 6604): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 6604): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 6604): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 6,604): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 6604): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 6604): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 6604): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 6604): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 6604): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 6604): {
E/BooksSync( 6604):  "error": {
E/BooksSync( 6604):   "errors": [
E/BooksSync( 6604):    {
E/BooksSync( 6604):     "domain": "global",
E/BooksSync( 6604):     "reason": "required",
E/BooksSync( 6604):     "message": "Login Required",
E/BooksSync( 6604):     "locationType": "header",
E/BooksSync( 6604):     "location": "Authorization"
E/BooksSync( 6604):    }
E/BooksSync( 6604):   ],
E/BooksSync( 6604):   "code": 401,
E/BooksSync( 6604):   "message": "Login Required"
E/BooksSync( 6604):  }
E/BooksSync( 6604): }
E/BooksSync( 6604): 
E/BooksSync( 6604): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 6604): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 6604): 	... 8 more
I/BooksSync( 6604): Finished books sync
,I/ActivityManager( 1031): Killing 6328:com.lge.sync/1000 (adj 15): empty #17
,D/SyncManager( 1031): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 26451, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,W/libprocessgroup( 1031): failed to open /acct/uid_1000/pid_6328/cgroup.procs: No such file or directory
,I/GAV2    ( 6604): Thread[GAThread,5,main]: No campaign data found.
I/art     ( 1031): Explicit concurrent mark sweep GC freed 20209(1033KB) AllocSpace objects, 5(592KB) LOS objects, 33% free, 44MB/66MB, paused 3.085ms total 142.468ms
,V/GLSActivity( 2129): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2129): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.syncadapters.contacts, service: cp
I/GLSUser ( 2129): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> cp without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 2129): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2129): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2129): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1031): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1031): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1031): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1031): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1031): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1415): onNotificationPosted
D/SmartCoverUpdateMonitor( 1415): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1415): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1415): handleNotificationPosted(true)
D/QuickCircle( 1415): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1415): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1415): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1415): post do just update job
D/LgeQuickCoverNotificationData( 1415): showAll3
D/LgeQuickCoverNotificationData( 1415): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1415): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1415): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1415): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1415): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1415): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1415): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1415): isNotificationForCurrentUser : true
,D/LgeQuickCoverOverlayWindow( 1415): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1415): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1415): updateNotificationData: count=3
D/QuickStatusbarLayout( 1415): Notification difference=198
,D/QuickStatusbarLayout( 1415): child = android.widget.LinearLayout{9d5fc15 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
W/GLSActivity( 2129): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2129): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2129): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2129): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2129): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2129): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2129): 	at android.os.Binder.execTransact(Binder.java:446)
,D/ContactsSyncAdapter( 2129): innerSync failed
D/ContactsSyncAdapter( 2129): com.google.wireless.gdata2.client.AuthenticationException: unable to get auth token android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
D/ContactsSyncAdapter( 2129): 	at com.google.android.syncadapters.contacts.AuthInfo.getAuthToken(AuthInfo.java:45)
D/ContactsSyncAdapter( 2129): 	at com.google.android.syncadapters.contacts.ContactsSyncAdapter.innerPerformSync(ContactsSyncAdapter.java:263)
D/ContactsSyncAdapter( 2129): 	at com.google.android.syncadapters.contacts.ContactsSyncAdapter.onPerformLoggedSync(ContactsSyncAdapter.java:168)
D/ContactsSyncAdapter( 2129): 	at com.google.android.common.LoggingThreadedSyncAdapter.onPerformSync(LoggingThreadedSyncAdapter.java:33)
D/ContactsSyncAdapter( 2129): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
D/ContactsSyncAdapter( 2129): Caused by: android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
D/ContactsSyncAdapter( 2129): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
D/ContactsSyncAdapter( 2129): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
D/ContactsSyncAdapter( 2129): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
D/ContactsSyncAdapter( 2129): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
D/ContactsSyncAdapter( 2129): 	at android.os.Binder.execTransact(Binder.java:446)
D/SyncManager( 1031): failed sync operation thalitester@gmail.com u0 (com.google), com.android.contacts, LOCAL, currentRunTime 325217, reason: 10019, SyncResult: stats [ numAuthExceptions: 1]
,I/dex2oat ( 7072): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=39 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,I/dex2oat ( 7072): dex2oat took 53.257ms (threads: 4)
,I/Adreno-EGL( 6961): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 6961): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 6961): Build Date: 12/12/14 금
I/Adreno-EGL( 6961): Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
I/Adreno-EGL( 6961): Remote Branch: 
I/Adreno-EGL( 6961): Local Patches: 
I/Adreno-EGL( 6961): Reconstruct Branch: 
,I/GAV4    ( 6775): Thread[GAThread,5,main]: No campaign data found.
,I/WVCdm   (  328): CdmEngine::OpenSession
I/WVCdm   (  328): Level3 Library Sep 25 2014 17:10:03
W/WVCdm   (  328): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
,D/DrmWidevineDash(  328): OEMCrypto_Initialize: starts! g_qsee_apps_version = 0x13
D/DrmWidevineDash(  328): Service_Initialize: starts!
D/QSEECOMAPI: (  328): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  328): App is not loaded in QSEE
,D/QSEECOMAPI: (  328): Loaded image: APP id = 3
,D/DrmWidevineDash(  328): Service_Initialize: ends! returns 0
D/DrmWidevineDash(  328): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb0968000
E/DrmWidevineDash(  328): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb0968000
,D/DrmWidevineDash(  328): OEMCrypto_Initialize: ends! returns 0
D/DrmWidevineDash(  328): OEMCrypto_APIVersion: starts!
D/DrmWidevineDash(  328): hlos api version =  9
D/DrmWidevineDash(  328): tz api version =  8
D/DrmWidevineDash(  328): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  328): OEMCrypto_IsKeyboxValid: starts!
,D/DrmWidevineDash(  328): OEMCrypto_IsKeyboxValid: ends! returns 0
D/WVCdm   (  328): OEMCrypto_Initialize Level 1 success. I will use level 1.
D/DrmWidevineDash(  328): OEMCrypto_OpenSession: starts! SID=0xb0eff940
D/DrmWidevineDash(  328): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  328): OEMCrypto_OpenSession: ends! returns 0
D/DrmWidevineDash(  328): OEMCrypto_GetRandom: starts! randomData=0xb14262a0, dataLength=8
D/DrmWidevineDash(  328): OEMCrypto_GetRandom: ends! returns 0
D/DrmWidevineDash(  328): OEMCrypto_LoadDeviceRSAKey: starts!SID=1, wrapped_rsa_key=0xb14db000, wrapped_rsa_key_length=1280
D/DrmWidevineDash(  328): OEMCrypto_LoadDeviceRSAKey: ends! returns 0
I/WVCdm   (  328): CdmEngine::QueryKeyControlInfo
W/WVCdm   (  328): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  328): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  328): CdmEngine::GenerateKeyRequest
D/DrmWidevineDash(  328): OEMCrypto_GetDeviceID: starts! deviceID=0xb543dd80, idLength=0xb0dff710
D/DrmWidevineDash(  328): OEMCrypto_GetDeviceID: ends! returns 0
D/DrmWidevineDash(  328): OEMCrypto_SupportsUsageTable: starts!
,D/DrmWidevineDash(  328): OEMCrypto_SupportsUsageTable: is_supported = 1
D/DrmWidevineDash(  328): OEMCrypto_SupportsUsageTable: wv_app_version = 25
D/DrmWidevineDash(  328): OEMCrypto_SupportsUsageTable: ends! returns 0x0
D/DrmWidevineDash(  328): OEMCrypto_GetHDCPCapability: starts!
D/DrmWidevineDash(  328): OEMCrypto_GetHDCPCapability: ends! returns 0x0
D/DrmWidevineDash(  328): OEMCrypto_APIVersion: starts!
D/DrmWidevineDash(  328): hlos api version =  9
D/DrmWidevineDash(  328): tz api version =  8
D/DrmWidevineDash(  328): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  328): OEMCrypto_GenerateNonce: starts! SID=1
D/DrmWidevineDash(  328): OEMCrypto_GenerateNonce: ends! returns 0
D/WVCdm   (  328): PrepareKeyRequest: nonce=711532764
D/DrmWidevineDash(  328): OEMCrypto_GenerateRSASignature starts! SID=1, message=0xb57ab400
D/DrmWidevineDash(  328): message_length=1632, signature=0xb547f4c0, signature_length=2967467764
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=31.4, 0.0, 0.0  rx=23.9 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1866412454] gl rssi=-48 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=31.4, 0.0, 0.0  rx=23.9 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-1866412453] gl rssi=-48 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
D/DrmWidevineDash(  328): OEMCrypto_GenerateRSASignature returns 0
,I/WVCdm   (  328): CdmEngine::CloseSession
,D/DrmWidevineDash(  328): OEMCrypto_CloseSession: starts! SID=1
D/DrmWidevineDash(  328): OEMCrypto_CloseSession: ends! returns 0
I/WVCdm   (  328): L3 Terminate.
D/DrmWidevineDash(  328): OEMCrypto_Terminate: starts!
D/DrmWidevineDash(  328): Service_Uninitialize: starts!
D/QSEECOMAPI: (  328): QSEECom_dealloc_memory 
D/QSEECOMAPI: (  328): QSEECom_shutdown_app, app_id = 3
D/DrmWidevineDash(  328): Service_Uninitialize: ends! returns 0x0
D/DrmWidevineDash(  328): OEMCrypto_Terminate: ends! returns 0
I/Adreno-EGL( 6961): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 6961): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 6961): Build Date: 12/12/14 금
I/Adreno-EGL( 6961): Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
I/Adreno-EGL( 6961): Remote Branch: 
I/Adreno-EGL( 6961): Local Patches: 
I/Adreno-EGL( 6961): Reconstruct Branch: 
,I/Adreno-EGL( 6961): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 6961): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 6961): Build Date: 12/12/14 금
I/Adreno-EGL( 6961): Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
I/Adreno-EGL( 6961): Remote Branch: 
I/Adreno-EGL( 6961): Local Patches: 
I/Adreno-EGL( 6961): Reconstruct Branch: 
,D/LgDataFeature( 6961): LgDataFeature() Constructor: none
D/LgDataFeature( 6961): LgDataFeature() Constructor Done, null
,I/CheckinRequestBuilder( 2345): Classify the device as Phone.
I/ActivityManager( 1031): Killing 5883:com.uei.lg.quicksetsdk.maxq616/1000 (adj 15): empty #17
,I/QRemote ( 5995): [RemoteControlManager.java:195:onServiceDisconnected()] oooooo start
W/System.err( 5995): android.os.DeadObjectException
W/System.err( 5995): 	at android.os.BinderProxy.transactNative(Native Method)
W/System.err( 5995): 	at android.os.BinderProxy.transact(Binder.java:496)
,W/System.err( 5995): 	at com.uei.control.IControl.unregisterCallback(IControl.java:502)
,W/System.err( 5995): 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:199)
W/System.err( 5995): 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
W/System.err( 5995): 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
W/System.err( 5995): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 5995): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 5995): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 5995): 	at android.app.ActivityThread.main(ActivityThread.java:5274)
W/System.err( 5995): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 5995): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 5995): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
W/System.err( 5995): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
E/UEI.SmartControl( 5995): IControl.unregisterCallback error: android.os.DeadObjectException
W/System.err( 5995): android.os.DeadObjectException
W/System.err( 5995): 	at android.os.BinderProxy.transactNative(Native Method)
W/System.err( 5995): 	at android.os.BinderProxy.transact(Binder.java:496)
W/System.err( 5995): 	at com.uei.control.IControl.unregisterSetupReadyCallback(IControl.java:818)
W/System.err( 5995): 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:200)
W/System.err( 5995): 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
W/System.err( 5995): 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
W/System.err( 5995): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 5995): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 5995): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 5995): 	at android.app.ActivityThread.main(ActivityThread.java:5274)
W/System.err( 5995): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 5995): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 5995): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
W/System.err( 5995): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
E/UEI.SmartControl( 5995): IControl.unregisterSetupReadyCallback error: android.os.DeadObjectException
I/QRemote ( 5995): [RemoteControlManager.java:203:onServiceDisconnected()] oooooo Control unbind before rebinding.
W/libprocessgroup( 1031): failed to open /acct/uid_1000/pid_5883/cgroup.procs: No such file or directory
W/ActivityManager( 1031): Scheduling restart of crashed service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service in 1000ms
,D/QRemote ( 5995): [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]10
I/QRemote ( 5995): [RemoteControlManager.java:157:onBindIRService()] oooooo bind
I/ActivityManager( 1031): Start proc com.uei.lg.quicksetsdk.maxq616 for service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service: pid=7089 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,D/QRemote ( 5995): [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
D/libc-netbsd(  323): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  323): res_queryN name = android.clients.google.com, class = 1, type = 1
,D/UEI.SmartControl( 7089): Quickset Services start...
,I/UEI.SmartControl( 7089): Manufacture = LGE
D/UEI.SmartControl( 7089): Id = LGNevo
D/UEI.SmartControl( 7089): File observer start...
E/UEI.SmartControl( 7089): IR Port is disabled: false
D/UEI.SmartControl( 7089): Starting file observer...
D/UEI.SmartControl( 7089): Extracting JNI libs...
D/UEI.SmartControl( 7089): --- this system supports 32-bit or 64-bit only
,D/libc-netbsd(  323): res_queryN name = android.clients.google.com succeed
,D/UEI.SmartControl( 7089): --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
D/UEI.SmartControl( 7089): --- Checking lib: libqs_armeabi-v7a.zip
D/UEI.SmartControl( 7089): --- Extracting JNI libs: libqs_armeabi-v7a.zip
I/UEI.SmartControl( 7089): --- Selecting new region: 6
,I/UEI.SmartControl( 7089): Model = LG-D855
D/UEI.SmartControl( 7089): QS Service created
I/UEI.SmartControl( 7089): Service initServices...
,D/UEI.SmartControl( 7089): QS start get config
D/UEI.SmartControl( 7089): Loading JNI Libs...
,I/UEI.SmartControl( 7089): Supports setup maps: true
D/UEI.SmartControl( 7089): QS start statue = true Error code = 0
I/UEI.SmartControl( 7089): QS version = v2.7.10.1_RC1
I/UEI.SmartControl( 7089): QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
I/UEI.SmartControl( 7089): ### init IR Blaster...
,D/serial_port( 7089): Configuring serial port
E/UEI.SmartControl( 7089): UEIBLaster setting for 616
I/UEI.SmartControl( 7089): Setting serial record hearder size = 2
I/UEI.SmartControl( 7089): configuring settings for MAXQ616
I/UEI.SmartControl( 7089): Get version...
D/UEI.SmartControl( 7089): serial port data available: 21
,D/UEI.SmartControl( 7089): MAXQ616 A2-X4 software.
I/UEI.SmartControl( 7089): IR Blaster version: 256702256704300002
,I/UEI.SmartControl( 7089): QS saving settings...
D/UEI.SmartControl( 7089): IR Blaster version: 25672567
D/UEI.SmartControl( 7089): serial port data available: 4
,I/UEI.SmartControl( 7089): Device manager: loading config....
D/UEI.SmartControl( 7089): ----------- loading internal config...
W/ContextImpl( 7089): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
E/UEI.SmartControl( 7089): Services init done
D/UEI.SmartControl( 7089): QS Service init finished
,D/UEI.SmartControl( 7089): QS Service version name: 2.1.91
,D/UEI.SmartControl( 7089): QS Service version code: 201091
D/UEI.SmartControl( 7089): Service requested: Control
D/UEI.SmartControl( 7089): Request IControl service: devices are loaded...
,E/UEI.SmartControl( 7089): Loading SETTINGS...
I/QRemote ( 5995): [RemoteControlManager.java:183:onServiceConnected()] oooooo start
I/UEI.SmartControl( 7089): ------ IControl API: 11
I/UEI.SmartControl( 7089): Registering callback...
I/ActivityManager( 1031): Killing 6275:com.android.settings/1000 (adj 15): empty #17
I/UEI.SmartControl( 7089): ------ IControl API: 19
I/UEI.SmartControl( 7089): Registering Services Ready callback...
D/UEI.SmartControl( 7089): -- Open brand translation xml: brands_translations_ko
,I/UEI.SmartControl( 7089): Notify AllClients services are ready: 0
I/QRemote ( 5995): [RemoteControlManager.java:660:QSSetupIsReady()] oooooo 140517:sdkIsReady callback... get functions. Result:0
D/UEI.SmartControl( 7089): -----service ready thread exits
,D/QRemote ( 5995): [RemoteControlManager.java:388:handleMessage()] oooooo 140510:START_SESSION
D/QRemote ( 5995): [RemoteControlManager.java:394:handleMessage()] oooooo 140510:send retrieve msg
D/QRemote ( 5995): [RemoteControlManager.java:322:handleMessage()] oooooo 140510:handler call retrieveDevices
D/QRemote ( 5995): [RemoteControlManager.java:336:retrieveDevices()] oooooo retrieveDevices: start
I/UEI.SmartControl( 7089): ------ IControl API: 8
D/WifiService( 1031): Client connection lost with reason: 4
,D/QRemote ( 5995): [RemoteControlManager.java:340:retrieveDevices()] oooooo retrieveDevices: 0
D/QRemote ( 5995): [RemoteControlManager.java:345:retrieveDevices()] oooooo retrieveDevices complete:true
D/QRemote ( 5995): [RemoteControlManager.java:353:retrieveDevices()] oooooo retrieveDevices: notifyDataSetChanged()
D/QRemote ( 5995): [QRemoteApplication.java:145:onRemoteControlStateChanged()] oooooo onRemoteControlStateChanged called in QRemoteApp
D/QRemote ( 5995): [QRemoteApplication.java:158:onRemoteControlStateChanged()] oooooo Widget count is [1]. send broadcast
D/QRemote ( 5995): [QRemoteApplication.java:160:onRemoteControlStateChanged()] oooooo Widget[0]:3
W/libprocessgroup( 1031): failed to open /acct/uid_1000/pid_6275/cgroup.procs: No such file or directory
D/UEI.SmartControl( 7089): Internal service binding...
,D/QRemote ( 5995): [QRemoteApplication.java:188:onRemoteControlStateChanged()] oooooo 140526:onRemoteControlStateChanged&sdkIsReady. stop Service
,V/QRemote ( 5995): [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
D/QRemote ( 5995): [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
E/QRemote ( 5995): [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
D/QRemote ( 5995): [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
D/QRemote ( 5995): [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
D/QRemote ( 5995): [RemoteAppWidgetProvider.java:506:onUpdate()] oooooo 140510:RetrieveDevices complete. Start loading
D/QRemote ( 5995): [RemoteAppWidgetProvider.java:508:onUpdate()] oooooo 140510:appWidgetIds[0]:3 loading
D/QRemote ( 5995): [RemoteAppWidgetManager.java:41:startLoading()] oooooo 140518:widgetId[3] loading start at [1449832535023]
D/QRemote ( 5995): [RemoteAppWidgetManager.java:239:doInBackground()] oooooo 140407:doinBack arr:0
,V/QRemote ( 5995): [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.widget_ui_update
E/QRemote ( 5995): [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
D/QRemote ( 5995): [RemoteAppWidgetProvider.java:171:onReceive()] oooooo total:0
D/QRemote ( 5995): [RemoteAppWidgetProvider.java:172:onReceive()] oooooo selected:0
D/QRemote ( 5995): [RemoteAppWidgetProvider.java:173:onReceive()] oooooo arr:[]
D/QRemote ( 5995): [RemoteAppWidgetProvider.java:174:onReceive()] oooooo appWidgetId:3
D/QRemote ( 5995): [RemoteAppWidgetProvider.java:815:updateRemoteViews()] oooooo UpdateRemoteViews3:widgetId:3
D/QRemote ( 5995): [RemoteAppWidgetProvider.java:986:updateRemoteViews()] oooooo updateAppWidget5:widgetId:3]
I/CheckinTask( 2345): Sending checkin request (9797 bytes)
,I/ActivityManager( 1031): Killing 6586:com.lge.appbox.client/u0a11 (adj 15): empty #17
,W/libprocessgroup( 1031): failed to open /acct/uid_10011/pid_6586/cgroup.procs: No such file or directory
,I/ActivityManager( 1031): Killing 6302:com.lge.formmanager/u0a26 (adj 15): empty #17
W/libprocessgroup( 1031): failed to open /acct/uid_10026/pid_6302/cgroup.procs: No such file or directory
,I/CheckinResponseProcessor( 2345): From server: 10 gservices updates and 4 deletes
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=42.7, 0.0, 0.0  rx=38.4 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1866409433] gl rssi=-48 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=42.7, 0.0, 0.0  rx=38.4 bcn=0 [on:0 tx:0 rx:0 period:4] from screen [on:0 period:-1866409429] gl rssi=-48 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,I/CertBlacklister( 1031): Certificate blacklist changed, updating...
I/CertBlacklister( 1031): Certificate blacklist updated
,D/SettingsProvider( 1031): row count exceeds max cache entries for table system
D/SettingsProvider( 1031): row count exceeds max cache entries for table system
,I/GservicesProvider( 2129): main difference update completed
,I/ActivityManager( 1031): Start proc com.google.android.partnersetup for broadcast com.google.android.partnersetup/.GservicesChangedReceiver: pid=7143 uid=10008 gids={50008, 9997, 3003} abi=armeabi-v7a
,I/CheckinRequestBuilder( 2345): Checkin reason type: 12 attempt count: 1
,E/ActivityThread( 2345): Failed to find provider info for com.google.android.wearable.settings
,I/ContactAccountLoggerTas( 4258): canRun() : Opted Out
,I/ActivityManager( 1031): Start proc com.google.android.configupdater for broadcast com.google.android.configupdater/.CertPin.CertPinUpdateRequestReceiver: pid=7182 uid=10059 gids={50059, 9997, 3003} abi=armeabi-v7a
I/Search.GservicesUpdateTask( 4258): Updating Gservices keys
,D/LgDataFeature( 7143): LgDataFeature() Constructor: none
D/LgDataFeature( 7143): LgDataFeature() Constructor Done, null
,E/UpdateRequestReceiver( 7182): Received malformed URL while handling Gservices.CHANGED_ACTION
,E/UpdateRequestReceiver( 7182): Received malformed URL while handling Gservices.CHANGED_ACTION
E/UpdateRequestReceiver( 7182): Received malformed URL while handling Gservices.CHANGED_ACTION
,E/UpdateRequestReceiver( 7182): Received malformed URL while handling Gservices.CHANGED_ACTION
I/art     ( 2129): Explicit concurrent mark sweep GC freed 27173(1481KB) AllocSpace objects, 9(1296KB) LOS objects, 50% free, 30MB/62MB, paused 1.477ms total 57.061ms
,I/ContactAccountLoggerTas( 4258): canRun() : Opted Out
I/ContactAccountLoggerTas( 4258): canRun() : Opted Out
W/Search.LoginHelper( 4258): User recoverable exception for scope: oauth2:https://www.googleapis.com/auth/googlenow
,W/Search.LoginHelper( 4258): User recoverable exception for scope: oauth2:https://www.googleapis.com/auth/googlenow
I/ContactAccountLoggerTas( 4258): canRun() : Opted Out
I/ContactAccountLoggerTas( 4258): canRun() : Opted Out
I/GLSUser ( 2129): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: AndroidCheckInServer
I/GLSUser ( 2129): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> AndroidCheckInServer without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 2129): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2129): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2129): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1031): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1031): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1031): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1031): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1031): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1415): onNotificationPosted
W/CheckinRequestBuilder( 2345): awaiting user notification for token
D/SmartCoverUpdateMonitor( 1415): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1415): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1415): handleNotificationPosted(true)
D/QuickCircle( 1415): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1415): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1415): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1415): post do just update job
D/LgeQuickCoverNotificationData( 1415): showAll3
D/LgeQuickCoverNotificationData( 1415): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1415): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1415): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1415): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1415): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1415): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1415): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1415): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1415): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1415): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1415): updateNotificationData: count=3
I/ActivityManager( 1031): Killing 6729:com.lge.drmservice/u0a62 (adj 15): empty #17
,I/CheckinRequestBuilder( 2345): Classify the device as Phone.
D/QuickStatusbarLayout( 1415): Notification difference=198
D/QuickStatusbarLayout( 1415): child = android.widget.LinearLayout{9d5fc15 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,W/libprocessgroup( 1031): failed to open /acct/uid_10062/pid_6729/cgroup.procs: No such file or directory
,I/ActivityManager( 1031): Killing 6624:com.android.gallery3d/u0a27 (adj 15): empty #17
,W/libprocessgroup( 1031): failed to open /acct/uid_10027/pid_6624/cgroup.procs: No such file or directory
,I/CheckinTask( 2345): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,I/CheckinService( 2345): Checking schedule, now: 1449832537385 next: 1450418568371
I/CheckinService( 2345): active receiver: disabled
,I/SystemUpdateService( 2345): receiver: Intent { act=com.google.gservices.intent.action.GSERVICES_CHANGED flg=0x10 cmp=com.google.android.gms/.update.SystemUpdateService$Receiver }
,D/SystemUpdateService( 2345): onCreate
D/SystemUpdateService( 2345): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/CheckinService( 2345): Checking schedule, now: 1449832537423 next: 1450418568371
I/CheckinService( 2345): active receiver: disabled
I/SystemUpdateService( 2345): cancelUpdate (empty URL)
I/SystemUpdateService( 2345): active receiver: disabled
,D/SystemEventReceiver( 2345): Received GSERVICES_CHANGED broadcast
D/GCM     ( 2129): GcmService start Intent { act=com.google.gservices.intent.action.GSERVICES_CHANGED flg=0x10 cmp=com.google.android.gms/.gcm.GcmService } com.google.gservices.intent.action.GSERVICES_CHANGED
I/OcrUtils( 2345): Updating ocr activity enabled=false
I/GCoreUlr( 1832): Starting service, intent=Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) }, extras=Bundle[{receiverAction=com.google.gservices.intent.action.GSERVICES_CHANGED}]
,D/SystemUpdateService( 2345): onDestroy
,I/GCoreUlr( 1832): DispatchingService.onCreate()
I/GCoreUlr( 1832): WorldUpdater received intent Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) } with receiverAction com.google.gservices.intent.action.GSERVICES_CHANGED
,I/art     ( 1832): Explicit concurrent mark sweep GC freed 14976(803KB) AllocSpace objects, 4(64KB) LOS objects, 50% free, 30MB/62MB, paused 2.489ms total 66.600ms
,I/art     ( 2345): Explicit concurrent mark sweep GC freed 27179(2MB) AllocSpace objects, 11(176KB) LOS objects, 49% free, 32MB/64MB, paused 2.344ms total 68.168ms
E/DataBuffer( 1832): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@22cd69af)
,I/art     ( 2129): Explicit concurrent mark sweep GC freed 7081(329KB) AllocSpace objects, 3(432KB) LOS objects, 50% free, 30MB/62MB, paused 2.076ms total 55.054ms
,I/GCoreUlr( 1832): WorldUpdater:com.google.gservices.intent.action.GSERVICES_CHANGED: Ensuring that reporting is stopped because of reasons: {account#2#=[InactiveReason{mVersionCode=0, mIdentifier=12, mName='LocationDisabled'}, InactiveReason{mVersionCode=0, mIdentifier=10, mName='AuthError'}, InactiveReason{mVersionCode=0, mIdentifier=6, mName='ReportingNotEnabled'}, InactiveReason{mVersionCode=0, mIdentifier=14, mName='HistoryNotEnabled'}]}
,I/art     ( 1031): Explicit concurrent mark sweep GC freed 28550(1298KB) AllocSpace objects, 6(352KB) LOS objects, 33% free, 44MB/66MB, paused 3.705ms total 176.588ms
I/GCoreUlr( 1832): Unbound from all location providers
,I/GCoreUlr( 1832): DispatchingService.onDestroy()
,I/GCoreUlr( 1832): Unbound from all location providers
D/ChimeraCfgMgr( 2345): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/GCM     ( 2129): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
D/ChimeraCfgMgr( 2345): Loading module com.google.android.gms.kids from APK com.google.android.gms
,I/GLSUser ( 2129): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: ac2dm
I/GLSUser ( 2129): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> ac2dm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2129): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2129): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2129): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1031): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1031): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1031): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1031): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
,D/NotificationServiceEx( 1031): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
W/Kids    ( 2345): [AccountUtils] Account not ready
W/Kids    ( 2345): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/Kids    ( 2345): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/Kids    ( 2345): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/Kids    ( 2345): 	at com.google.android.gms.auth.p.c(SourceFile:550)
W/Kids    ( 2345): 	at com.google.android.gms.auth.p.b(SourceFile:477)
W/Kids    ( 2345): 	at com.google.android.gms.kids.account.k.d(SourceFile:103)
W/Kids    ( 2345): 	at com.google.android.gms.kids.account.p.a(SourceFile:70)
W/Kids    ( 2345): 	at com.google.android.gms.kids.account.t.a(SourceFile:62)
W/Kids    ( 2345): 	at com.google.android.gms.chimera.f.run(SourceFile:179)
W/Kids    ( 2345): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Kids    ( 2345): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Kids    ( 2345): 	at java.lang.Thread.run(Thread.java:818)
D/LgeQuickCoverNLService( 1415): onNotificationPosted
D/SmartCoverUpdateMonitor( 1415): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1415): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1415): handleNotificationPosted(true)
D/QuickCircle( 1415): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1415): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1415): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1415): post do just update job
D/LgeQuickCoverNotificationData( 1415): showAll3
D/LgeQuickCoverNotificationData( 1415): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1415): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1415): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1415): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1415): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1415): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1415): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1415): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1415): [native noti] inex =  2
,D/LgeQuickCoverNotificationData( 1415): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1415): updateNotificationData: count=3
D/QuickStatusbarLayout( 1415): Notification difference=198
,D/QuickStatusbarLayout( 1415): child = android.widget.LinearLayout{9d5fc15 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
I/ActivityManager( 1031): Killing 6775:com.google.android.apps.magazines/u0a93 (adj 15): empty #17
,W/libprocessgroup( 1031): failed to open /acct/uid_10093/pid_6775/cgroup.procs: No such file or directory
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-47 f=2412 sc=60 link=72 tx=32.4, 0.0, 0.0  rx=26.7 bcn=0 [on:0 tx:0 rx:0 period:3005] from screen [on:0 period:-1866406419] gl rssi=-47 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-47 f=2412 sc=60 link=72 tx=32.4, 0.0, 0.0  rx=26.7 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1866406416] gl rssi=-47 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,D/UEI.SmartControl( 7089): Internal timer expired: 1
,D/UEI.SmartControl( 7089): unbind internal service
D/serial_port( 7089): close(fd = 25)
,I/UEI.SmartControl( 7089): Serial port is closed.
I/GAV2    ( 6833): Thread[GAThread,5,main]: No campaign data found.
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-47 f=2412 sc=60 link=72 tx=16.2, 0.0, 0.0  rx=13.4 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1866403390] gl rssi=-47 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-47 f=2412 sc=60 link=72 tx=16.2, 0.0, 0.0  rx=13.4 bcn=0 [on:0 tx:0 rx:0 period:21] from screen [on:0 period:-1866403369] gl rssi=-47 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-47 f=2412 sc=60 link=72 tx=8.1, 0.0, 0.0  rx=6.7 bcn=0 [on:0 tx:0 rx:0 period:3005] from screen [on:0 period:-1866400350] gl rssi=-47 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-47 f=2412 sc=60 link=72 tx=8.1, 0.0, 0.0  rx=6.7 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1866400347] gl rssi=-47 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,I/[SystemUI]QPairHandler( 1473): onReceive = android.intent.action.PACKAGE_CHANGED
,D/SplitUIService( 1884): replaced split : contains_com.google.android.talk / true
,I/InputReader( 1031): Reconfiguring input devices.  changes=0x00000010
,D/SplitUIManager( 1884): split_name #11 / not available #0
,I/SplitUIService( 1884): split app #11
I/ActivityManager( 1031): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.manager.PreloadListManagerHelper: pid=7264 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,I/InputReader( 1031): Reconfiguring input devices.  changes=0x00000010
,I/[SystemUI]QSlideListController( 1473): onReceive = android.intent.action.PACKAGE_CHANGED
,I/[SystemUI]AppWidgetPanel(QRemoteWidgetPanel)( 1473): onReceive = android.intent.action.PACKAGE_CHANGED, packageName : com.google.android.talk
I/[SystemUI]QPairHandler( 1473): onReceive = android.intent.action.PACKAGE_CHANGED
I/[SystemUI]QSlideListController( 1473): onReceive = android.intent.action.PACKAGE_CHANGED
I/[SystemUI]AppWidgetPanel(QRemoteWidgetPanel)( 1473): onReceive = android.intent.action.PACKAGE_CHANGED, packageName : com.google.android.gms
,I/[LGHome]EVENT( 2086): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.talk flg=0x4000010 (has extras) }
I/[LGHome]EVENT( 2086): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
D/administrator( 1031): Handling package changes for user 0
W/ResourcesManager( 2086): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
I/[LGHome]Launcher( 2086): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,I/[LGHome]Launcher( 2086): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,I/AppUp4:AppBoxCP( 7264): onCreate
W/AppUp4:DB( 7264):  [AppBoxDatabaseHelper] construct
I/AppUp4:DB( 7264):  setFingerPrint start
I/AppUp4:DB( 7264):  newfinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys SDK version = 21
,I/AppUp4:DB( 7264):  beforefinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys
I/AppUp4:DB( 7264):  SDK version = 21
I/AppUp4:DB( 7264):  beforefinger == newfinger no write in DB
D/AppUp4:AppBoxApplication( 7264): AppBoxApplication onCreate()
I/AppUp4:CustModeStarterReceiver( 7264): onReceive
,I/NotificationService( 1031): action=android.intent.action.PACKAGE_CHANGED queryReplace=false
D/BackupManagerService( 1031): Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.talk flg=0x4000010 (has extras) }
,D/LgDataFeature( 7264): LgDataFeature() Constructor: none
D/LgDataFeature( 7264): LgDataFeature() Constructor Done, null
,W/ResourcesManager( 1031): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,D/administrator( 1031): Handling package changes for user 0
D/AppUp4:CustFacade( 7264): Context : android.app.ReceiverRestrictedContext@f1bd36
D/AppUp4:CustFacade( 7264): isCustomizationCompleted : false
D/AppUp4:CustFacade( 7264): isPhone : true
D/AppUp4:CustModeStarterReceiver( 7264): begin check event
I/AppUp4:CustModeStarterReceiver( 7264): Event For Nothing, skip.
I/NotificationService( 1031): action=android.intent.action.PACKAGE_CHANGED queryReplace=false
D/BackupManagerService( 1031): Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
I/BackupManagerService( 1031): Unbinding ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,I/ActivityManager( 1031): Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=7292 uid=10019 gids={50019, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
I/ActivityManager( 1031): Killing 6647:com.android.chrome/u0a57 (adj 15): empty #17
W/ResourcesManager( 1031): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourceType( 1031): Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
I/BackupManagerService( 1031): Binding to transport host ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,W/libprocessgroup( 1031): failed to open /acct/uid_10057/pid_6647/cgroup.procs: No such file or directory
I/[LGHome]EVENT( 2086): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
,V/BackupManagerService( 1031): Connected to transport ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
V/BackupManagerService( 1031): Registering transport com.google.android.gms/.backup.BackupTransportService::com.google.android.gms/.backup.BackupTransportService = com.android.internal.backup.IBackupTransport$Stub$Proxy@23ac686a
W/ResourceType( 1031): Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
I/[LGHome]EVENT( 2086): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
,V/GmsNetworkLocationProvi( 1832): DISABLE
I/GCoreNlp( 1832): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
W/ResourcesManager( 7292): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 7292): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 7292): Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
W/ResourcesManager( 7292): Asset path '/system/framework/lghiddenlibs.jar' does not exist or contains no resources.
,W/ResourcesManager( 7292): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
I/SystemConfig( 7292): BUILD Country: EU
I/SystemConfig( 7292): BUILD Operator: OPEN
,D/LocationProviderProxy( 1031): applying state to connected service
I/ActivityManager( 1031): Killing 6668:com.lge.email/u0a23 (adj 15): empty #17
,W/libprocessgroup( 1031): failed to open /acct/uid_10023/pid_6668/cgroup.procs: No such file or directory
,I/SystemConfig( 7292): pm.hasSystemFeature(com.lge.ims.rcs) = false
,I/SystemConfig( 7292): existFile = false
I/SystemConfig( 7292): canReadFile = false
I/SystemConfig( 7292): systemFeature RCS result false
D/SystemConfig( 7292): refreshRcsSupport() :false
I/ActivityManager( 1031): Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=7313 uid=10027 gids={50027, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
,W/PackageSettings( 1031): Skipping PackageSetting{225e55a5 com.example.hello/10318} due to missing metadata
,W/ResourcesManager( 7313): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7313): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,W/ResourcesManager( 7313): Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
W/ResourcesManager( 7313): Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
I/AppConfig( 7313): Total System Memory = 2995761152
,D/SystemHelper( 7313): region [EU], country [EU], operator [OPEN], sub-operator []
,I/ActivityManager( 1031): Killing 5170:com.wsandroid.suite.lge/1000 (adj 15): empty #17
,W/libprocessgroup( 1031): failed to open /acct/uid_1000/pid_5170/cgroup.procs: No such file or directory
,I/UpdateIcingCorporaServi( 4258): Updating corpora: APPS=com.google.android.talk, CONTACTS=MAYBE
V/SIM_STK ( 1031): Menu title from STK is T-Mobile
,W/ResourcesManager( 4258): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
I/ActivityManager( 1031): Start proc com.lge.lockscreensettings for broadcast com.lge.lockscreensettings/.PackageIntentReceiver: pid=7344 uid=10080 gids={50080, 9997, 1028, 1015} abi=armeabi-v7a
,I/UpdateIcingCorporaServi( 4258): UpdateCorporaTask done [took 79 ms] updated apps [took 79 ms] 
I/art     (  360): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 476us total 21.531ms
,I/art     (  360): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 435us total 20.210ms
I/art     (  360): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 442us total 20.146ms
,I/LockScreenSettings( 7344): Wallpaper base directory = /data/data/com.lge.lockscreensettings/files/
,D/LockScreenSettings( 7344): Quick window widget present in DB = com.lge.clock.quickcover.QuickCoverSettingActivity  true
D/LockScreenSettings( 7344): Quick window widget present in DB = com.lge.camera.app.QuickWindowCameraActivity  true
D/LockScreenSettings( 7344): Quick window widget present in DB = com.android.contacts.activities.QuickCircleActivity  true
D/LockScreenSettings( 7344): Quick window widget present in DB = com.android.mms.quickcover.QuickCoverActivity  true
D/LockScreenSettings( 7344): Quick window widget present in DB = com.lge.music.MusicQuickCircle  true
D/LockScreenSettings( 7344): Quick window widget present in DB = com.lge.lifetracker.QuickCover  true
,I/ActivityManager( 1031): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=7363 uid=10044 gids={50044, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager( 1031): Killing 6925:com.qualcomm.timeservice/1000 (adj 15): empty #17
W/libprocessgroup( 1031): failed to open /acct/uid_1000/pid_6925/cgroup.procs: No such file or directory
,I/art     ( 2129): Explicit concurrent mark sweep GC freed 6763(324KB) AllocSpace objects, 3(432KB) LOS objects, 50% free, 30MB/62MB, paused 4.243ms total 86.698ms
,D/Finsky  ( 7363): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,D/LgDataFeature( 7363): LgDataFeature() Constructor: none
D/LgDataFeature( 7363): LgDataFeature() Constructor Done, null
,D/Finsky  ( 7363): [1] DailyHygiene.goMakeHygieneIfDirty: Dirty, need more hygiene.
,I/ActivityManager( 1031): Start proc com.google.android.gms:car for service com.google.android.gms/.car.CarService: pid=7402 uid=10005 gids={50005, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
,W/Settings( 7363): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 7363): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/ResourcesManager( 7402): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 7402): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
V/DownloadManager( 3366): starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 3366): created cursor android.database.sqlite.SQLiteCursor@2c34dfa5 on behalf of 7363
D/Finsky  ( 7363): [1] 2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 7363): [1] 2.run: Finished loading 1 libraries.
D/Finsky  ( 7363): [1] GmsCoreHelper.cleanupNlp: result=false type=4
I/MultiDex( 7402): VM with version 2.1.0 has multidex support
,I/MultiDex( 7402): install
I/MultiDex( 7402): VM has multidex support, MultiDex support library is disabled.
D/PackageBroadcastService( 2345): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.talk
D/Finsky  ( 7363): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,I/AppUp4:CustModeStarterReceiver( 7264): onReceive
,I/PeopleContactsSync( 2345): CP2 sync disabled
D/AppUp4:CustFacade( 7264): Context : android.app.ReceiverRestrictedContext@f1bd36
D/AppUp4:CustFacade( 7264): isCustomizationCompleted : false
D/AppUp4:CustFacade( 7264): isPhone : true
D/AppUp4:CustModeStarterReceiver( 7264): begin check event
I/AppUp4:CustModeStarterReceiver( 7264): Event For Nothing, skip.
V/JNIHelp ( 7402): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,I/ActivityManager( 1031): Killing 6943:com.android.calendar/u0a13 (adj 15): empty #17
W/ActivityThread( 7402): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 7402): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@a383b1e: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,I/ProviderInstaller( 7402): Installed default security provider GmsCore_OpenSSL
W/libprocessgroup( 1031): failed to open /acct/uid_10013/pid_6943/cgroup.procs: No such file or directory
,I/UpdateIcingCorporaServi( 4258): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,D/LockScreenSettings( 7344): Quick window widget present in DB = com.lge.clock.quickcover.QuickCoverSettingActivity  true
D/LockScreenSettings( 7344): Quick window widget present in DB = com.lge.camera.app.QuickWindowCameraActivity  true
D/LockScreenSettings( 7344): Quick window widget present in DB = com.android.contacts.activities.QuickCircleActivity  true
D/LockScreenSettings( 7344): Quick window widget present in DB = com.android.mms.quickcover.QuickCoverActivity  true
,D/LockScreenSettings( 7344): Quick window widget present in DB = com.lge.music.MusicQuickCircle  true
D/LockScreenSettings( 7344): Quick window widget present in DB = com.lge.lifetracker.QuickCover  true
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-47 f=2412 sc=60 link=72 tx=4.0, 0.0, 0.0  rx=3.3 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1866397326] gl rssi=-47 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-47 f=2412 sc=60 link=72 tx=4.0, 0.0, 0.0  rx=3.3 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-1866397325] gl rssi=-47 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
D/PackageBroadcastService( 2345): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,D/GCM     ( 2129): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
I/PackageBroadcastService( 2345): Null package name or gms related package.  Ignoreing.
D/AuthorizationBluetoothService( 2129): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,V/GmsCoreStatsServiceLauncher( 2345): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
I/Icing   ( 2345): updateResources: need to parse f{com.google.android.gms}
,D/WearableService( 7020): callingUid 10005, callindPid: 7020
E/MDM     ( 1832): [97] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,D/LocationInitializer( 2345): Restart initialization of location
,V/Finsky  ( 7363): [1] GearheadStateMonitor.onReady: sIsProjecting:false
,V/SIM_STK ( 1031): Menu title from STK is T-Mobile
,I/UpdateIcingCorporaServi( 4258): UpdateCorporaTask done [took 355 ms] updated apps [took 355 ms] 
,D/Finsky  ( 7363): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
,V/AlarmManager( 1031): RTC_WAKEUP set : Alarm{23fa6893 type 0 when 1449832549230 com.android.vending} when 1449832549230
,I/art     ( 1031): Explicit concurrent mark sweep GC freed 42793(2MB) AllocSpace objects, 5(208KB) LOS objects, 33% free, 44MB/66MB, paused 2.628ms total 180.240ms
,V/GLSActivity( 2129): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/GLSUser ( 2129): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 2129): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 2129): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2129): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2129): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/Finsky  ( 7363): [1] 1.onErrorResponse: Unable to preload experiments: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,V/GLSActivity( 2129): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/GLSUser ( 2129): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 2129): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2129): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2129): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2129): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/GLSActivity( 2129): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2129): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 2129): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2129): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2129): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2129): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/Finsky  ( 7363): [1] LibraryUpdateListener.onErrorResponse: Library replication failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,V/SIM_STK ( 1031): Menu title from STK is T-Mobile
,D/sensors_hal_Time( 1031): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1031): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1031): tsOffsetIs: Apps: 315469458270; DSPS: 10478379; Offset : -4322583280
,V/GLSActivity( 2129): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2129): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 2129): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2129): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2129): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2129): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/Finsky  ( 7363): [1] 2.onErrorResponse: Update check failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,D/Finsky  ( 7363): [1] DailyHygiene.logDeviceFeaturesAndContinue: Logging device features
D/Finsky  ( 7363): [1] DailyHygiene.flushEventLogsAndContinue: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 7363): [1] DailyHygiene.reschedule: Scheduling new run in 9 minutes (failures=1)
D/DeviceConnectionService( 1832): client connected with version: 7571000
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-47 f=2412 sc=60 link=72 tx=2.0, 0.0, 0.0  rx=1.7 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1866394312] gl rssi=-47 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-47 f=2412 sc=60 link=72 tx=2.0, 0.0, 0.0  rx=1.7 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-1866394311] gl rssi=-47 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,I/ActivityManager( 1031): Killing 6894:com.lge.clock/u0a10 (adj 15): empty #17
,W/libprocessgroup( 1031): failed to open /acct/uid_10010/pid_6894/cgroup.procs: No such file or directory
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-47 f=2412 sc=60 link=72 tx=2.0, 0.0, 0.0  rx=1.8 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1866391292] gl rssi=-47 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-47 f=2412 sc=60 link=72 tx=2.0, 0.0, 0.0  rx=1.8 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1866391289] gl rssi=-47 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,V/AlarmManager( 1031): ELAPSED_WAKEUP set : Alarm{1bada692 type 2 when 322819 android} when 322819
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-47 f=2412 sc=60 link=72 tx=1.0, 0.0, 0.0  rx=0.9 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:-1866388267] gl rssi=-47 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-47 f=2412 sc=60 link=72 tx=1.0, 0.0, 0.0  rx=0.9 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1866388264] gl rssi=-47 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,I/[SystemUI]TimeTickManager( 1473): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1473): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1473): called onTimeUpdated()
I/[SystemUI]Clock( 1473): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1473): called onTimeUpdated()
I/[SystemUI]DateView( 1473): called onTimeUpdated()
I/[SystemUI]DateView( 1473): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1473): handleTimeUpdate
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.5 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1866385236] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.5 bcn=0 [on:0 tx:0 rx:0 period:13] from screen [on:0 period:-1866385223] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1031):  ConnectedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 1 0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 1 0
E/WifiStateMachine( 1031):  ConnectModeState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 1 0
E/WifiStateMachine( 1031):  DriverStartedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 1 0
E/WifiStateMachine( 1031):  SupplicantStartedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 1 0
,E/WifiStateMachine( 1031):  DefaultState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 1 0
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.3, 0.0, 0.0  rx=0.2 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1866382200] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.3, 0.0, 0.0  rx=0.2 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1866382197] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3000] from screen [on:0 period:-1866379175] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:13] from screen [on:0 period:-1866379162] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
D/sensors_hal_Time( 1031): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1031): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1031): tsOffsetIs: Apps: 335472112585; DSPS: 11133826; Offset : -4322584282
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1866376140] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1866376137] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1866373114] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:13] from screen [on:0 period:-1866373101] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
D/PowerManagerServiceEx( 1031): acquireWakeLockInternal: lock=538279423, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1031
,V/AlarmManager( 1031): RTC_WAKEUP set : Alarm{30ad3c60 type 0 when 1449832564599 com.android.vending} when 1449832564599
,D/[Concierge]Service( 2627): onStartCommand(). Type : 9
,D/PowerManagerServiceEx( 1031): releaseWakeLockInternal: lock=538279423 [*alarm*], flags=0x0
,V/SIM_STK ( 1031): Menu title from STK is T-Mobile
,V/GLSActivity( 2129): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2129): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 2129): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2129): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2129): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2129): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/Finsky  ( 7363): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 7363): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 7363): [1] 5.onFinished: Scheduling replication attempt 1.
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1866370080] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-1866370079] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=2.0, 0.0, 0.0  rx=1.5 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:-1866367059] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=2.0, 0.0, 0.0  rx=1.5 bcn=0 [on:0 tx:0 rx:0 period:13] from screen [on:0 period:-1866367046] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=1.0, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1866364023] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=1.0, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1866364020] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1866360995] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:14] from screen [on:0 period:-1866360981] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
I/ActivityManager( 1031): Killing 6755:com.lge.sizechangable.weather/u0a85 (adj 15): empty #17
,W/libprocessgroup( 1031): failed to open /acct/uid_10085/pid_6755/cgroup.procs: No such file or directory
,V/AlarmManager( 1031): ELAPSED_WAKEUP set : Alarm{2e8d842 type 2 when 352854 android} when 352854
,I/BooksSync( 6604): Starting books sync
,D/BooksSync( 6604): started syncMyEbooks
,V/GLSActivity( 2129): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2129): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.syncadapters.contacts, service: cp
,I/GLSUser ( 2129): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> cp without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2129): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2129): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2129): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1031): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
V/NotificationService( 1031): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1031): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1031): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1031): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,D/LgeQuickCoverNLService( 1415): onNotificationPosted
D/SmartCoverUpdateMonitor( 1415): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1415): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1415): handleNotificationPosted(true)
D/QuickCircle( 1415): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1415): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1415): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1415): post do just update job
D/LgeQuickCoverNotificationData( 1415): showAll3
D/LgeQuickCoverNotificationData( 1415): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1415): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1415): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1415): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1415): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1415): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1415): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1415): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1415): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1415): isNotificationForCurrentUser : true
W/GLSActivity( 2129): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2129): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2129): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2129): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2129): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2129): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2129): 	at android.os.Binder.execTransact(Binder.java:446)
D/ContactsSyncAdapter( 2129): innerSync failed
D/ContactsSyncAdapter( 2129): com.google.wireless.gdata2.client.AuthenticationException: unable to get auth token android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
D/ContactsSyncAdapter( 2129): 	at com.google.android.syncadapters.contacts.AuthInfo.getAuthToken(AuthInfo.java:45)
D/ContactsSyncAdapter( 2129): 	at com.google.android.syncadapters.contacts.ContactsSyncAdapter.innerPerformSync(ContactsSyncAdapter.java:263)
D/ContactsSyncAdapter( 2129): 	at com.google.android.syncadapters.contacts.ContactsSyncAdapter.onPerformLoggedSync(ContactsSyncAdapter.java:168)
D/ContactsSyncAdapter( 2129): 	at com.google.android.common.LoggingThreadedSyncAdapter.onPerformSync(LoggingThreadedSyncAdapter.java:33)
D/ContactsSyncAdapter( 2129): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
D/ContactsSyncAdapter( 2129): Caused by: android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
D/ContactsSyncAdapter( 2129): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
D/ContactsSyncAdapter( 2129): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
D/ContactsSyncAdapter( 2129): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
D/ContactsSyncAdapter( 2129): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
D/ContactsSyncAdapter( 2129): 	at android.os.Binder.execTransact(Binder.java:446)
E/LgeQuickCoverOverlayWindow( 1415): updateNotificationData: count=3
,D/QuickStatusbarLayout( 1415): Notification difference=198
D/QuickStatusbarLayout( 1415): child = android.widget.LinearLayout{9d5fc15 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,D/SyncManager( 1031): failed sync operation thalitester@gmail.com u0 (com.google), com.android.contacts, LOCAL, currentRunTime 325217, reason: 10019, SyncResult: stats [ numAuthExceptions: 1]
D/SyncManager( 1031): not retrying sync operation because the error is a hard error: thalitester@gmail.com u0 (com.google), com.android.contacts, LOCAL, currentRunTime 415744, reason: 10019
I/GLSUser ( 2129): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2129): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2129): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2129): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2129): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/NotificationService( 1031): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1031): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1031): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1031): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1031): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
W/GLSActivity( 2129): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2129): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2129): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2129): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2129): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2129): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2129): 	at android.os.Binder.execTransact(Binder.java:446)
D/LgeQuickCoverNLService( 1415): onNotificationPosted
,E/BooksAccountManager( 6604): Authentication error
E/BooksAccountManager( 6604): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6604): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6604): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6604): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6604): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6604): 	at android.os.Binder.execTransact(Binder.java:446)
,D/SmartCoverUpdateMonitor( 1415): received broadcast com.lge.intent.action.NLDataPosted
E/HttpHelper( 6604): null auth token
E/SmartCoverUpdateMonitor( 1415): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1415): handleNotificationPosted(true)
D/QuickCircle( 1415): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1415): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1415): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1415): post do just update job
D/LgeQuickCoverNotificationData( 1415): showAll3
D/LgeQuickCoverNotificationData( 1415): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1415): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1415): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1415): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1415): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1415): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1415): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1415): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1415): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1415): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1415): updateNotificationData: count=3
D/QuickStatusbarLayout( 1415): Notification difference=198
D/QuickStatusbarLayout( 1415): child = android.widget.LinearLayout{9d5fc15 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,W/ApiaryClient( 6604): Error response from books API: {
W/ApiaryClient( 6604):  "error": {
W/ApiaryClient( 6604):   "errors": [
W/ApiaryClient( 6604):    {
W/ApiaryClient( 6604):     "domain": "global",
W/ApiaryClient( 6604):     "reason": "required",
W/ApiaryClient( 6604):     "message": "Login Required",
W/ApiaryClient( 6604):     "locationType": "header",
W/ApiaryClient( 6604):     "location": "Authorization"
W/ApiaryClient( 6604):    }
W/ApiaryClient( 6604):   ],
W/ApiaryClient( 6604):   "code": 401,
W/ApiaryClient( 6604):   "message": "Login Required"
W/ApiaryClient( 6604):  }
W/ApiaryClient( 6604): }
W/ApiaryClient( 6604): errCount = 1: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6604): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-5567572849282948254&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6604): Headers:
W/ApiaryClient( 6604): accept-encoding: [gzip]
W/ApiaryClient( 6604): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6604): gdata-version: 2
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.3, 0.0, 0.0  rx=0.2 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1866357960] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.3, 0.0, 0.0  rx=0.2 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1866357957] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,I/art     ( 2129): Explicit concurrent mark sweep GC freed 19324(1121KB) AllocSpace objects, 6(864KB) LOS objects, 50% free, 30MB/62MB, paused 2.334ms total 69.251ms
,V/GLSActivity( 2129): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/GLSUser ( 2129): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2129): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2129): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2129): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2129): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1031): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1031): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1031): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1031): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1031): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1415): onNotificationPosted
D/SmartCoverUpdateMonitor( 1415): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1415): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1415): handleNotificationPosted(true)
D/QuickCircle( 1415): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1415): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1415): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1415): post do just update job
D/LgeQuickCoverNotificationData( 1415): showAll3
D/LgeQuickCoverNotificationData( 1415): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1415): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1415): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1415): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1415): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1415): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1415): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1415): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1415): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1415): isNotificationForCurrentUser : true
,E/LgeQuickCoverOverlayWindow( 1415): updateNotificationData: count=3
W/GLSActivity( 2129): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2129): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2129): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2129): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2129): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2129): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2129): 	at android.os.Binder.execTransact(Binder.java:446)
E/BooksAccountManager( 6604): Authentication error
E/BooksAccountManager( 6604): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6604): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6604): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6604): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6604): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6604): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6604): null auth token
D/QuickStatusbarLayout( 1415): Notification difference=198
D/QuickStatusbarLayout( 1415): child = android.widget.LinearLayout{9d5fc15 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,W/ApiaryClient( 6604): Error response from books API: {
W/ApiaryClient( 6604):  "error": {
W/ApiaryClient( 6604):   "errors": [
W/ApiaryClient( 6604):    {
W/ApiaryClient( 6604):     "domain": "global",
W/ApiaryClient( 6604):     "reason": "required",
W/ApiaryClient( 6604):     "message": "Login Required",
W/ApiaryClient( 6604):     "locationType": "header",
W/ApiaryClient( 6604):     "location": "Authorization"
W/ApiaryClient( 6604):    }
W/ApiaryClient( 6604):   ],
W/ApiaryClient( 6604):   "code": 401,
W/ApiaryClient( 6604):   "message": "Login Required"
W/ApiaryClient( 6604):  }
W/ApiaryClient( 6604): }
,W/ApiaryClient( 6604): errCount = 2: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6604): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-5567572849282948254&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6604): Headers:
W/ApiaryClient( 6604): accept-encoding: [gzip]
W/ApiaryClient( 6604): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6604): gdata-version: 2
D/sensors_hal_Time( 1031): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1031): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1031): tsOffsetIs: Apps: 355474044348; DSPS: 11789250; Offset : -4322605253
,V/GLSActivity( 2129): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2129): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2129): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2129): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2129): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2129): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1031): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1031): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1031): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1031): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1031): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1415): onNotificationPosted
,D/SmartCoverUpdateMonitor( 1415): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1415): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1415): handleNotificationPosted(true)
D/QuickCircle( 1415): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1415): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1415): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1415): post do just update job
D/LgeQuickCoverNotificationData( 1415): showAll3
D/LgeQuickCoverNotificationData( 1415): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1415): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1415): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1415): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1415): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1415): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1415): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1415): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1415): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1415): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1415): updateNotificationData: count=3
W/GLSActivity( 2129): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2129): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2129): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2129): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2129): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2129): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2129): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 6604): Authentication error
E/BooksAccountManager( 6604): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6604): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6604): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6604): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6604): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6604): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6604): null auth token
D/QuickStatusbarLayout( 1415): Notification difference=198
D/QuickStatusbarLayout( 1415): child = android.widget.LinearLayout{9d5fc15 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
W/ApiaryClient( 6604): Error response from books API: {
W/ApiaryClient( 6604):  "error": {
W/ApiaryClient( 6604):   "errors": [
W/ApiaryClient( 6604):    {
W/ApiaryClient( 6604):     "domain": "global",
W/ApiaryClient( 6604):     "reason": "required",
W/ApiaryClient( 6604):     "message": "Login Required",
W/ApiaryClient( 6604):     "locationType": "header",
W/ApiaryClient( 6604):     "location": "Authorization"
W/ApiaryClient( 6604):    }
W/ApiaryClient( 6604):   ],
W/ApiaryClient( 6604):   "code": 401,
W/ApiaryClient( 6604):   "message": "Login Required"
W/ApiaryClient( 6604):  }
W/ApiaryClient( 6604): }
,W/ApiaryClient( 6604): errCount = 3: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6604): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-5567572849282948254&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6604): Headers:
W/ApiaryClient( 6604): accept-encoding: [gzip]
W/ApiaryClient( 6604): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6604): gdata-version: 2
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=1.6, 0.0, 0.0  rx=1.1 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1866354937] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=1.6, 0.0, 0.0  rx=1.1 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1866354934] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
E/BooksSync( 6604): Soft error: 
E/BooksSync( 6604): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 6604): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-5567572849282948254&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 6604): Headers:
E/BooksSync( 6604): accept-encoding: [gzip]
E/BooksSync( 6604): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 6604): gdata-version: 2
E/BooksSync( 6604): 
E/BooksSync( 6604): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 6604): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 6604): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 6604): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 6604): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 6604): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 6604): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 6604): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 6604): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 6604): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 6604): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 6604): {
E/BooksSync( 6604):  "error": {
E/BooksSync( 6604):   "errors": [
E/BooksSync( 6604):    {
E/BooksSync( 6604):     "domain": "global",
E/BooksSync( 6604):     "reason": "required",
E/BooksSync( 6604):     "message": "Login Required",
E/BooksSync( 6604):     "locationType": "header",
E/BooksSync( 6604):     "location": "Authorization"
E/BooksSync( 6604):    }
E/BooksSync( 6604):   ],
E/BooksSync( 6604):   "code": 401,
E/BooksSync( 6604):   "message": "Login Required"
E/BooksSync( 6604):  }
E/BooksSync( 6604): }
E/BooksSync( 6604): 
E/BooksSync( 6604): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 6604): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 6604): 	... 8 more
,E/BooksSync( 6604): Sync error
E/BooksSync( 6604): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 6604): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-5567572849282948254&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 6604): Headers:
E/BooksSync( 6604): accept-encoding: [gzip]
E/BooksSync( 6604): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 6604): gdata-version: 2
E/BooksSync( 6604): 
E/BooksSync( 6604): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 6604): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 6604): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 6604): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 6604): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 6604): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 6604): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 6604): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 6604): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 6604): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 6604): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 6604): {
E/BooksSync( 6604):  "error": {
E/BooksSync( 6604):   "errors": [
E/BooksSync( 6604):    {
E/BooksSync( 6604):     "domain": "global",
E/BooksSync( 6604):     "reason": "required",
E/BooksSync( 6604):     "message": "Login Required",
E/BooksSync( 6604):     "locationType": "header",
E/BooksSync( 6604):     "location": "Authorization"
E/BooksSync( 6604):    }
E/BooksSync( 6604):   ],
E/BooksSync( 6604):   "code": 401,
E/BooksSync( 6604):   "message": "Login Required"
E/BooksSync( 6604):  }
E/BooksSync( 6604): }
E/BooksSync( 6604): 
E/BooksSync( 6604): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 6604): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 6604): 	... 8 more
I/BooksSync( 6604): Finished books sync
D/SyncManager( 1031): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 329883, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=4.3, 0.0, 0.0  rx=3.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1866351904] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=4.3, 0.0, 0.0  rx=3.0 bcn=0 [on:0 tx:0 rx:0 period:15] from screen [on:0 period:-1866351889] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
V/AlarmManager( 1031): RTC_WAKEUP set : Alarm{154d549e type 0 when 1449832595733 com.android.vending} when 1449832595733
,V/SIM_STK ( 1031): Menu title from STK is T-Mobile
,V/GLSActivity( 2129): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2129): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 2129): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2129): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2129): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2129): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/Finsky  ( 7363): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 7363): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 7363): [1] 5.onFinished: Scheduling replication attempt 2.
,I/art     ( 1031): Explicit concurrent mark sweep GC freed 37810(1661KB) AllocSpace objects, 6(608KB) LOS objects, 33% free, 44MB/66MB, paused 2.044ms total 77.843ms
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=2.2, 0.0, 0.0  rx=1.5 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1866348868] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=2.2, 0.0, 0.0  rx=1.5 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-1866348867] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=1.1, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:-1866345851] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=1.1, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1866345848] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=1.5, 0.0, 0.0  rx=1.4 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1866342827] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=1.5, 0.0, 0.0  rx=1.4 bcn=0 [on:0 tx:0 rx:0 period:13] from screen [on:0 period:-1866342814] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1866339793] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1866339790] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.3 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1866336754] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.3 bcn=0 [on:0 tx:0 rx:0 period:15] from screen [on:0 period:-1866336739] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
D/sensors_hal_Time( 1031): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1031): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1031): tsOffsetIs: Apps: 375476257622; DSPS: 12444682; Offset : -4322589427
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.2, 0.0, 0.0  rx=0.2 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1866333717] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.2, 0.0, 0.0  rx=0.2 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1866333714] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,I/[SystemUI]LGPowerUI( 1473): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1473): On Skip Timer : true
,D/WifiController( 1031): battery changed pluggedType: 2
,D/LEDHandler( 1964): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1964): Battery Level Remaining: 100%
D/LEDHandler( 1964): Battery Temp: 282, mChargingStatus=5, mChargingStop=false
D/KeyguardUpdateMonitor( 1473): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 282
I/[SystemUI]LGPowerUI( 1473): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings( 1031): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1031): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/HeadsetStateMachine( 6236): Disconnected process message: 10, size: 0
D/LGDMClient( 3985): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.intent.action.BATTERY_CHANGED
D/LGDMClient( 3985): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
I/[SystemUI]BatterySaverHandler( 1473): onReceive = android.intent.action.BATTERY_CHANGED
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1866330687] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1866330684] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,V/AlarmManager( 1031): RTC_WAKEUP set : Alarm{a136449 type 0 when 1449832616914 com.android.vending} when 1449832616914
,V/SIM_STK ( 1031): Menu title from STK is T-Mobile
,V/AlarmManager( 1031): ELAPSED_WAKEUP set : Alarm{c46214e type 2 when 382930 android} when 382930
,V/GLSActivity( 2129): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2129): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 2129): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2129): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2129): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2129): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/Finsky  ( 7363): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 7363): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 7363): [1] 5.onFinished: Scheduling replication attempt 3.
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1866327654] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:12] from screen [on:0 period:-1866327642] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
I/[SystemUI]TimeTickManager( 1473): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1473): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1473): called onTimeUpdated()
I/[SystemUI]Clock( 1473): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1473): called onTimeUpdated()
I/[SystemUI]DateView( 1473): called onTimeUpdated()
I/[SystemUI]DateView( 1473): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1473): handleTimeUpdate
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1866324621] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1866324618] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1866321592] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1866321589] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1866318562] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1866318559] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,D/sensors_hal_Time( 1031): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1031): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1031): tsOffsetIs: Apps: 395478183135; DSPS: 13100105; Offset : -4322586626
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=2.0, 0.0, 0.0  rx=1.5 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1866315535] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=2.0, 0.0, 0.0  rx=1.5 bcn=0 [on:0 tx:0 rx:0 period:11] from screen [on:0 period:-1866315524] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=1.0, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1866312506] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=1.0, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:12] from screen [on:0 period:-1866312494] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1866309473] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1866309470] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.3, 0.0, 0.0  rx=0.2 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1866306444] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.3, 0.0, 0.0  rx=0.2 bcn=0 [on:0 tx:0 rx:0 period:11] from screen [on:0 period:-1866306433] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1866303411] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1866303408] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,D/PowerManagerServiceEx( 1031): acquireWakeLockInternal: lock=538279423, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1031
,V/AlarmManager( 1031): RTC_WAKEUP set : Alarm{1500f1b9 type 0 when 1449832637404 com.android.vending} when 1449832637404
,D/[Concierge]Service( 2627): onStartCommand(). Type : 9
,D/PowerManagerServiceEx( 1031): releaseWakeLockInternal: lock=538279423 [*alarm*], flags=0x0
,V/SIM_STK ( 1031): Menu title from STK is T-Mobile
,V/GLSActivity( 2129): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2129): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 2129): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2129): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2129): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2129): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 7363): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 7363): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 7363): [1] 5.onFinished: Scheduling replication attempt 4.
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1866300382] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1866300379] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1866297352] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1866297349] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,D/sensors_hal_Time( 1031): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1031): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1031): tsOffsetIs: Apps: 415480996201; DSPS: 13755557; Offset : -4322580942
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1866294322] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-1866294312] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=1.0, 0.0, 0.0  rx=1.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1866291288] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=1.0, 0.0, 0.0  rx=1.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1866291285] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,V/AlarmManager( 1031): ELAPSED_WAKEUP set : Alarm{b4f1bf3 type 2 when 421240 android} when 421240
,I/BooksSync( 6604): Starting books sync
,D/BooksSync( 6604): started syncMyEbooks
,V/GLSActivity( 2129): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2129): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2129): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2129): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 2129): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2129): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1031): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1031): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1031): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1031): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1031): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1415): onNotificationPosted
D/SmartCoverUpdateMonitor( 1415): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1415): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1415): handleNotificationPosted(true)
D/QuickCircle( 1415): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1415): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1415): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1415): post do just update job
D/LgeQuickCoverNotificationData( 1415): showAll3
D/LgeQuickCoverNotificationData( 1415): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1415): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1415): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1415): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1415): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1415): isNotificationForCurrentUser : true
,D/LgeQuickCoverOverlayWindow( 1415): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1415): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1415): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1415): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1415): updateNotificationData: count=3
W/GLSActivity( 2129): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2129): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2129): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2129): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2129): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2129): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2129): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 6604): Authentication error
E/BooksAccountManager( 6604): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6604): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6604): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6604): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6604): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6604): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6604): null auth token
D/QuickStatusbarLayout( 1415): Notification difference=198
D/QuickStatusbarLayout( 1415): child = android.widget.LinearLayout{9d5fc15 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,W/ApiaryClient( 6604): Error response from books API: {
W/ApiaryClient( 6604):  "error": {
W/ApiaryClient( 6604):   "errors": [
W/ApiaryClient( 6604):    {
W/ApiaryClient( 6604):     "domain": "global",
W/ApiaryClient( 6604):     "reason": "required",
W/ApiaryClient( 6604):     "message": "Login Required",
W/ApiaryClient( 6604):     "locationType": "header",
W/ApiaryClient( 6604):     "location": "Authorization"
W/ApiaryClient( 6604):    }
W/ApiaryClient( 6604):   ],
W/ApiaryClient( 6604):   "code": 401,
W/ApiaryClient( 6604):   "message": "Login Required"
W/ApiaryClient( 6604):  }
W/ApiaryClient( 6604): }
,W/ApiaryClient( 6604): errCount = 1: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6604): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=4498739429599255840&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6604): Headers:
W/ApiaryClient( 6604): accept-encoding: [gzip]
W/ApiaryClient( 6604): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6604): gdata-version: 2
V/GLSActivity( 2129): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2129): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2129): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2129): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2129): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2129): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1031): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1031): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1031): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1031): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1031): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
W/GLSActivity( 2129): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2129): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2129): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2129): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2129): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2129): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2129): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 6604): Authentication error
E/BooksAccountManager( 6604): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6604): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6604): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6604): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6604): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6604): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6604): null auth token
W/ResourcesManager( 1415): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 1415): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,D/LgeQuickCoverNLService( 1415): onNotificationPosted
D/SmartCoverUpdateMonitor( 1415): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1415): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1415): handleNotificationPosted(true)
D/QuickCircle( 1415): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1415): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1415): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1415): post do just update job
D/LgeQuickCoverNotificationData( 1415): showAll3
D/LgeQuickCoverNotificationData( 1415): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1415): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1415): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1415): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1415): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1415): isNotificationForCurrentUser : true
W/ResourcesManager( 1415): Asset path '/system/framework/com.lge.systemui.jar' does not exist or contains no resources.
W/ResourcesManager( 1415): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,D/LgeQuickCoverOverlayWindow( 1415): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1415): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1415): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1415): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1415): updateNotificationData: count=3
,D/QuickStatusbarLayout( 1415): Notification difference=198
D/QuickStatusbarLayout( 1415): child = android.widget.LinearLayout{9d5fc15 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
W/ApiaryClient( 6604): Error response from books API: {
W/ApiaryClient( 6604):  "error": {
W/ApiaryClient( 6604):   "errors": [
W/ApiaryClient( 6604):    {
W/ApiaryClient( 6604):     "domain": "global",
W/ApiaryClient( 6604):     "reason": "required",
W/ApiaryClient( 6604):     "message": "Login Required",
W/ApiaryClient( 6604):     "locationType": "header",
W/ApiaryClient( 6604):     "location": "Authorization"
W/ApiaryClient( 6604):    }
W/ApiaryClient( 6604):   ],
W/ApiaryClient( 6604):   "code": 401,
W/ApiaryClient( 6604):   "message": "Login Required"
W/ApiaryClient( 6604):  }
W/ApiaryClient( 6604): }
,W/ApiaryClient( 6604): errCount = 2: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6604): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=4498739429599255840&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6604): Headers:
W/ApiaryClient( 6604): accept-encoding: [gzip]
W/ApiaryClient( 6604): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6604): gdata-version: 2
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.5 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1866288260] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.5 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1866288257] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,V/GLSActivity( 2129): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2129): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2129): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2129): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 2129): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2129): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1031): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1031): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1031): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1031): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1031): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1415): onNotificationPosted
,D/SmartCoverUpdateMonitor( 1415): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1415): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1415): handleNotificationPosted(true)
D/QuickCircle( 1415): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1415): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1415): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1415): post do just update job
D/LgeQuickCoverNotificationData( 1415): showAll3
D/LgeQuickCoverNotificationData( 1415): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1415): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1415): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1415): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1415): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1415): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1415): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1415): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1415): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1415): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1415): updateNotificationData: count=3
W/GLSActivity( 2129): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2129): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2129): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2129): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2129): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2129): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2129): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 6604): Authentication error
E/BooksAccountManager( 6604): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6604): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6604): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6604): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6604): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6604): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6604): null auth token
D/QuickStatusbarLayout( 1415): Notification difference=198
D/QuickStatusbarLayout( 1415): child = android.widget.LinearLayout{9d5fc15 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,W/ApiaryClient( 6604): Error response from books API: {
W/ApiaryClient( 6604):  "error": {
W/ApiaryClient( 6604):   "errors": [
W/ApiaryClient( 6604):    {
W/ApiaryClient( 6604):     "domain": "global",
W/ApiaryClient( 6604):     "reason": "required",
W/ApiaryClient( 6604):     "message": "Login Required",
W/ApiaryClient( 6604):     "locationType": "header",
W/ApiaryClient( 6604):     "location": "Authorization"
W/ApiaryClient( 6604):    }
W/ApiaryClient( 6604):   ],
W/ApiaryClient( 6604):   "code": 401,
W/ApiaryClient( 6604):   "message": "Login Required"
W/ApiaryClient( 6604):  }
W/ApiaryClient( 6604): }
,W/ApiaryClient( 6604): errCount = 3: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6604): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=4498739429599255840&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6604): Headers:
W/ApiaryClient( 6604): accept-encoding: [gzip]
W/ApiaryClient( 6604): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6604): gdata-version: 2
E/BooksSync( 6604): Soft error: 
E/BooksSync( 6604): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 6604): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=4498739429599255840&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 6604): Headers:
E/BooksSync( 6604): accept-encoding: [gzip]
E/BooksSync( 6604): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 6604): gdata-version: 2
E/BooksSync( 6604): 
E/BooksSync( 6604): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 6604): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 6604): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 6604): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 6604): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 6604): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 6604): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 6604): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 6604): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 6604): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 6604): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 6604): {
E/BooksSync( 6604):  "error": {
E/BooksSync( 6604):   "errors": [
E/BooksSync( 6604):    {
E/BooksSync( 6604):     "domain": "global",
E/BooksSync( 6604):     "reason": "required",
E/BooksSync( 6604):     "message": "Login Required",
E/BooksSync( 6604):     "locationType": "header",
E/BooksSync( 6604):     "location": "Authorization"
E/BooksSync( 6604):    }
E/BooksSync( 6604):   ],
E/BooksSync( 6604):   "code": 401,
E/BooksSync( 6604):   "message": "Login Required"
E/BooksSync( 6604):  }
E/BooksSync( 6604): }
E/BooksSync( 6604): 
E/BooksSync( 6604): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 6604): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 6604): 	... 8 more
,E/BooksSync( 6604): Sync error
E/BooksSync( 6604): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 6604): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=4498739429599255840&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 6604): Headers:
E/BooksSync( 6604): accept-encoding: [gzip]
E/BooksSync( 6604): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 6604): gdata-version: 2
E/BooksSync( 6604): 
E/BooksSync( 6604): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 6604): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 6604): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 6604): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 6604): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 6604): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 6604): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 6604): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 6604): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 6604): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 6604): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 6604): {
E/BooksSync( 6604):  "error": {
E/BooksSync( 6604):   "errors": [
E/BooksSync( 6604):    {
E/BooksSync( 6604):     "domain": "global",
E/BooksSync( 6604):     "reason": "required",
E/BooksSync( 6604):     "message": "Login Required",
E/BooksSync( 6604):     "locationType": "header",
E/BooksSync( 6604):     "location": "Authorization"
E/BooksSync( 6604):    }
E/BooksSync( 6604):   ],
E/BooksSync( 6604):   "code": 401,
E/BooksSync( 6604):   "message": "Login Required"
E/BooksSync( 6604):  }
E/BooksSync( 6604): }
E/BooksSync( 6604): 
E/BooksSync( 6604): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 6604): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 6604): 	... 8 more
I/BooksSync( 6604): Finished books sync
D/SyncManager( 1031): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 421240, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=3.8, 0.0, 0.0  rx=3.3 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1866285236] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=3.8, 0.0, 0.0  rx=3.3 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-1866285226] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=3.4, 0.0, 0.0  rx=2.6 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1866282204] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=3.4, 0.0, 0.0  rx=2.6 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-1866282194] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=1.7, 0.0, 0.0  rx=1.3 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1866279172] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=1.7, 0.0, 0.0  rx=1.3 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1866279169] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,D/sensors_hal_Time( 1031): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1031): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1031): tsOffsetIs: Apps: 435482974110; DSPS: 14410982; Offset : -4322586701
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1866276144] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:9] from screen [on:0 period:-1866276135] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.3 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1866273114] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.3 bcn=0 [on:0 tx:0 rx:0 period:11] from screen [on:0 period:-1866273103] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.2, 0.0, 0.0  rx=0.2 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1866270080] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.2, 0.0, 0.0  rx=0.2 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1866270077] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,V/AlarmManager( 1031): RTC_WAKEUP set : Alarm{13659b1a type 0 when 1449832665337 com.android.vending} when 1449832665337
,V/SIM_STK ( 1031): Menu title from STK is T-Mobile
,V/GLSActivity( 2129): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2129): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 2129): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2129): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2129): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2129): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/Finsky  ( 7363): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 7363): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 7363): [1] 5.onFinished: Scheduling replication attempt 5.
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=1.1, 0.0, 0.0  rx=0.6 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1866267059] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=1.1, 0.0, 0.0  rx=0.6 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1866267056] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,I/[SystemUI]TimeTickManager( 1473): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1473): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1473): called onTimeUpdated()
I/[SystemUI]Clock( 1473): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1473): called onTimeUpdated()
I/[SystemUI]DateView( 1473): called onTimeUpdated()
I/[SystemUI]DateView( 1473): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1473): handleTimeUpdate
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.6, 0.0, 0.0  rx=0.3 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1866264030] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.6, 0.0, 0.0  rx=0.3 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1866264027] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.3, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1866261000] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.3, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:2] from screen [on:0 period:-1866260998] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,D/PowerManagerServiceEx( 1031): acquireWakeLockInternal: lock=538279423, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1031
,V/AlarmManager( 1031): ELAPSED_WAKEUP set : Alarm{1a67246c type 2 when 451287 android} when 451287
D/[Concierge]Service( 2627): onStartCommand(). Type : 9
,D/PowerManagerServiceEx( 1031): releaseWakeLockInternal: lock=538279423 [*alarm*], flags=0x0
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1866257970] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1866257967] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,D/sensors_hal_Time( 1031): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1031): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1031): tsOffsetIs: Apps: 455485302331; DSPS: 15066419; Offset : -4322608491
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1866254945] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:11] from screen [on:0 period:-1866254934] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1866251913] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1866251910] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1866248884] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:9] from screen [on:0 period:-1866248875] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1866245852] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1866245849] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:-1866242820] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1866242817] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=1.0, 0.0, 0.0  rx=0.5 bcn=0 [on:0 tx:0 rx:0 period:3006] from screen [on:0 period:-1866239796] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,V/AlarmManager( 1031): RTC_WAKEUP set : Alarm{186afeca type 0 when 1449832698462 com.android.vending} when 1449832698462
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=1.0, 0.0, 0.0  rx=0.5 bcn=0 [on:0 tx:0 rx:0 period:24] from screen [on:0 period:-1866239772] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
V/SIM_STK ( 1031): Menu title from STK is T-Mobile
,V/GLSActivity( 2129): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2129): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 2129): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>],
I/GLSUser ( 2129): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2129): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2129): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/Finsky  ( 7363): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 7363): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 7363): [1] 5.onFinished: Giving up after 6 failures.
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.3 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1866236756] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.3 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-1866236746] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
D/sensors_hal_Time( 1031): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1031): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1031): tsOffsetIs: Apps: 475487331334; DSPS: 15721845; Offset : -4322593387
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.3, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1866233724] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.3, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:9] from screen [on:0 period:-1866233715] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1866230695] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-1866230685] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1866227664] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:12] from screen [on:0 period:-1866227652] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1866224630] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1866224627] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1866221600] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1866221597] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1866218570] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1866218567] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,D/sensors_hal_Time( 1031): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1031): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1031): tsOffsetIs: Apps: 495488939711; DSPS: 16377258; Offset : -4322602624
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=2.0, 0.0, 0.0  rx=1.5 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1866215549] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=2.0, 0.0, 0.0  rx=1.5 bcn=0 [on:0 tx:0 rx:0 period:2] from screen [on:0 period:-1866215547] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=1.0, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1866212520] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=1.0, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:11] from screen [on:0 period:-1866212509] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1866209491] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1866209488] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.3, 0.0, 0.0  rx=0.2 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1866206460] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.3, 0.0, 0.0  rx=0.2 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1866206457] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,I/[SystemUI]TimeTickManager( 1473): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1473): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1473): called onTimeUpdated()
I/[SystemUI]Clock( 1473): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1473): called onTimeUpdated()
I/[SystemUI]DateView( 1473): called onTimeUpdated()
I/[SystemUI]DateView( 1473): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1473): handleTimeUpdate
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1866203430] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1866203427] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1866200400] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1866200397] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1866197372] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1866197369] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,D/sensors_hal_Time( 1031): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1031): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1031): tsOffsetIs: Apps: 515491162829; DSPS: 17032691; Offset : -4322607289
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1866194347] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1866194344] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1866191315] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-1866191305] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=1.0, 0.0, 0.0  rx=1.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1866188285] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=1.0, 0.0, 0.0  rx=1.0 bcn=0 [on:0 tx:0 rx:0 period:9] from screen [on:0 period:-1866188276] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.5 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1866185255] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.5 bcn=0 [on:0 tx:0 rx:0 period:9] from screen [on:0 period:-1866185246] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.3, 0.0, 0.0  rx=0.3 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1866182224] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.3, 0.0, 0.0  rx=0.3 bcn=0 [on:0 tx:0 rx:0 period:11] from screen [on:0 period:-1866182213] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3000] from screen [on:0 period:-1866179193] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:4] from screen [on:0 period:-1866179189] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,D/sensors_hal_Time( 1031): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1031): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1031): tsOffsetIs: Apps: 535493343811; DSPS: 17688122; Offset : -4322592846
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=2.6, 0.0, 0.0  rx=2.6 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1866176163] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=2.6, 0.0, 0.0  rx=2.6 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1866176160] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=3.3, 0.0, 0.0  rx=3.8 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1866173144] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=3.3, 0.0, 0.0  rx=3.8 bcn=0 [on:0 tx:0 rx:0 period:9] from screen [on:0 period:-1866173135] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=1.6, 0.0, 0.0  rx=1.9 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:-1866170111] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=1.6, 0.0, 0.0  rx=1.9 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1866170108] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=3.3, 0.0, 0.0  rx=4.4 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1866167081] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=3.3, 0.0, 0.0  rx=4.4 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1866167078] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=4.2, 0.0, 0.0  rx=4.7 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1866164049] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=4.2, 0.0, 0.0  rx=4.7 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1866164046] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=2.1, 0.0, 0.0  rx=2.4 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1866161019] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=2.1, 0.0, 0.0  rx=2.4 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1866161016] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,D/PowerManagerServiceEx( 1031): acquireWakeLockInternal: lock=538279423, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1031
,V/AlarmManager( 1031): ELAPSED_WAKEUP set : Alarm{eb2809c type 2 when 553616 android} when 553616
D/[Concierge]Service( 2627): onStartCommand(). Type : 9
,D/PowerManagerServiceEx( 1031): releaseWakeLockInternal: lock=538279423 [*alarm*], flags=0x0
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=1.0, 0.0, 0.0  rx=1.2 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1866157990] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=1.0, 0.0, 0.0  rx=1.2 bcn=0 [on:0 tx:0 rx:0 period:2] from screen [on:0 period:-1866157988] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,I/BooksSync( 6604): Starting books sync
,D/BooksSync( 6604): started syncMyEbooks
,V/GLSActivity( 2129): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/GLSUser ( 2129): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2129): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2129): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2129): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2129): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1031): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1031): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1031): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1031): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1031): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1415): onNotificationPosted
,D/SmartCoverUpdateMonitor( 1415): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1415): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1415): handleNotificationPosted(true)
D/QuickCircle( 1415): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1415): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1415): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1415): post do just update job
D/LgeQuickCoverNotificationData( 1415): showAll3
D/LgeQuickCoverNotificationData( 1415): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1415): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1415): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1415): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1415): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1415): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1415): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1415): isNotificationForCurrentUser : true
W/GLSActivity( 2129): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2129): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2129): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2129): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2129): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2129): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2129): 	at android.os.Binder.execTransact(Binder.java:446)
D/LgeQuickCoverOverlayWindow( 1415): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1415): isNotificationForCurrentUser : true
E/BooksAccountManager( 6604): Authentication error
E/BooksAccountManager( 6604): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6604): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6604): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6604): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6604): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6604): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6604): null auth token
,E/LgeQuickCoverOverlayWindow( 1415): updateNotificationData: count=3
D/QuickStatusbarLayout( 1415): Notification difference=198
D/QuickStatusbarLayout( 1415): child = android.widget.LinearLayout{9d5fc15 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,W/ApiaryClient( 6604): Error response from books API: {
W/ApiaryClient( 6604):  "error": {
W/ApiaryClient( 6604):   "errors": [
W/ApiaryClient( 6604):    {
W/ApiaryClient( 6604):     "domain": "global",
W/ApiaryClient( 6604):     "reason": "required",
W/ApiaryClient( 6604):     "message": "Login Required",
W/ApiaryClient( 6604):     "locationType": "header",
W/ApiaryClient( 6604):     "location": "Authorization"
W/ApiaryClient( 6604):    }
W/ApiaryClient( 6604):   ],
W/ApiaryClient( 6604):   "code": 401,
W/ApiaryClient( 6604):   "message": "Login Required"
W/ApiaryClient( 6604):  }
W/ApiaryClient( 6604): }
,W/ApiaryClient( 6604): errCount = 1: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6604): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-7210265407269099089&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6604): Headers:
W/ApiaryClient( 6604): accept-encoding: [gzip]
W/ApiaryClient( 6604): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6604): gdata-version: 2
D/sensors_hal_Time( 1031): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1031): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1031): tsOffsetIs: Apps: 555495608334; DSPS: 18343556; Offset : -4322586990
,V/GLSActivity( 2129): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2129): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2129): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2129): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 2129): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2129): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     ( 1031): Explicit concurrent mark sweep GC freed 81798(3MB) AllocSpace objects, 5(592KB) LOS objects, 33% free, 44MB/66MB, paused 2.543ms total 155.982ms
,V/NotificationService( 1031): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1031): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1031): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1031): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1031): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1415): onNotificationPosted
,D/SmartCoverUpdateMonitor( 1415): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1415): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1415): handleNotificationPosted(true)
D/QuickCircle( 1415): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1415): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1415): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1415): post do just update job
D/LgeQuickCoverNotificationData( 1415): showAll3
D/LgeQuickCoverNotificationData( 1415): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1415): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1415): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1415): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1415): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1415): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1415): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1415): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1415): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1415): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1415): updateNotificationData: count=3
W/GLSActivity( 2129): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2129): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2129): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2129): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2129): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2129): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2129): 	at android.os.Binder.execTransact(Binder.java:446)
E/BooksAccountManager( 6604): Authentication error
E/BooksAccountManager( 6604): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6604): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6604): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6604): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6604): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6604): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6604): null auth token
,D/QuickStatusbarLayout( 1415): Notification difference=198
D/QuickStatusbarLayout( 1415): child = android.widget.LinearLayout{9d5fc15 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
W/ApiaryClient( 6604): Error response from books API: {
W/ApiaryClient( 6604):  "error": {
W/ApiaryClient( 6604):   "errors": [
W/ApiaryClient( 6604):    {
W/ApiaryClient( 6604):     "domain": "global",
W/ApiaryClient( 6604):     "reason": "required",
W/ApiaryClient( 6604):     "message": "Login Required",
W/ApiaryClient( 6604):     "locationType": "header",
W/ApiaryClient( 6604):     "location": "Authorization"
W/ApiaryClient( 6604):    }
W/ApiaryClient( 6604):   ],
W/ApiaryClient( 6604):   "code": 401,
W/ApiaryClient( 6604):   "message": "Login Required"
W/ApiaryClient( 6604):  }
W/ApiaryClient( 6604): }
,W/ApiaryClient( 6604): errCount = 2: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6604): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-7210265407269099089&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6604): Headers:
W/ApiaryClient( 6604): accept-encoding: [gzip]
W/ApiaryClient( 6604): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6604): gdata-version: 2
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.6 bcn=0 [on:0 tx:0 rx:0 period:3006] from screen [on:0 period:-1866154969] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.6 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1866154966] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,V/GLSActivity( 2129): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2129): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2129): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2129): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2129): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2129): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1031): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1031): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1031): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1031): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1031): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1415): onNotificationPosted
,D/SmartCoverUpdateMonitor( 1415): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1415): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1415): handleNotificationPosted(true)
D/QuickCircle( 1415): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1415): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1415): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1415): post do just update job
D/LgeQuickCoverNotificationData( 1415): showAll3
D/LgeQuickCoverNotificationData( 1415): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1415): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1415): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1415): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1415): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1415): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1415): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1415): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1415): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1415): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1415): updateNotificationData: count=3
W/GLSActivity( 2129): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2129): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2129): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2129): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2129): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2129): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2129): 	at android.os.Binder.execTransact(Binder.java:446)
,D/QuickStatusbarLayout( 1415): Notification difference=198
D/QuickStatusbarLayout( 1415): child = android.widget.LinearLayout{9d5fc15 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
E/BooksAccountManager( 6604): Authentication error
E/BooksAccountManager( 6604): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6604): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6604): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6604): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6604): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6604): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6604): null auth token
W/ApiaryClient( 6604): Error response from books API: {
W/ApiaryClient( 6604):  "error": {
W/ApiaryClient( 6604):   "errors": [
W/ApiaryClient( 6604):    {
W/ApiaryClient( 6604):     "domain": "global",
W/ApiaryClient( 6604):     "reason": "required",
W/ApiaryClient( 6604):     "message": "Login Required",
W/ApiaryClient( 6604):     "locationType": "header",
W/ApiaryClient( 6604):     "location": "Authorization"
W/ApiaryClient( 6604):    }
W/ApiaryClient( 6604):   ],
W/ApiaryClient( 6604):   "code": 401,
W/ApiaryClient( 6604):   "message": "Login Required"
W/ApiaryClient( 6604):  }
W/ApiaryClient( 6604): }
,W/ApiaryClient( 6604): errCount = 3: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6604): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-7210265407269099089&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6604): Headers:
W/ApiaryClient( 6604): accept-encoding: [gzip]
W/ApiaryClient( 6604): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6604): gdata-version: 2
E/BooksSync( 6604): Soft error: 
E/BooksSync( 6604): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 6604): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-7210265407269099089&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 6604): Headers:
E/BooksSync( 6604): accept-encoding: [gzip]
E/BooksSync( 6604): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 6604): gdata-version: 2
E/BooksSync( 6604): 
E/BooksSync( 6604): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 6604): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 6604): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 6604): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 6604): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 6604): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 6604): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 6604): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 6604): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 6604): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 6604): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 6604): {
E/BooksSync( 6604):  "error": {
E/BooksSync( 6604):   "errors": [
E/BooksSync( 6604):    {
E/BooksSync( 6604):     "domain": "global",
E/BooksSync( 6604):     "reason": "required",
E/BooksSync( 6604):     "message": "Login Required",
E/BooksSync( 6604):     "locationType": "header",
E/BooksSync( 6604):     "location": "Authorization"
E/BooksSync( 6604):    }
E/BooksSync( 6604):   ],
E/BooksSync( 6604):   "code": 401,
E/BooksSync( 6604):   "message": "Login Required"
E/BooksSync( 6604):  }
E/BooksSync( 6604): }
E/BooksSync( 6604): 
E/BooksSync( 6604): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 6604): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 6604): 	... 8 more
,E/BooksSync( 6604): Sync error
E/BooksSync( 6604): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 6604): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-7210265407269099089&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 6604): Headers:
E/BooksSync( 6604): accept-encoding: [gzip]
E/BooksSync( 6604): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 6604): gdata-version: 2
E/BooksSync( 6604): 
E/BooksSync( 6604): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 6604): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 6604): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 6604): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 6604): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 6604): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 6604): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 6604): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 6604): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 6604): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 6604): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 6604): {
E/BooksSync( 6604):  "error": {
E/BooksSync( 6604):   "errors": [
E/BooksSync( 6604):    {
E/BooksSync( 6604):     "domain": "global",
E/BooksSync( 6604):     "reason": "required",
E/BooksSync( 6604):     "message": "Login Required",
E/BooksSync( 6604):     "locationType": "header",
E/BooksSync( 6604):     "location": "Authorization"
E/BooksSync( 6604):    }
E/BooksSync( 6604):   ],
E/BooksSync( 6604):   "code": 401,
E/BooksSync( 6604):   "message": "Login Required"
E/BooksSync( 6604):  }
E/BooksSync( 6604): }
E/BooksSync( 6604): 
E/BooksSync( 6604): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 6604): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 6604): 	... 8 more
I/BooksSync( 6604): Finished books sync
D/SyncManager( 1031): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 553616, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=4.8, 0.0, 0.0  rx=4.3 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1866151940] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=4.8, 0.0, 0.0  rx=4.3 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1866151937] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=4.9, 0.0, 0.0  rx=4.1 bcn=0 [on:0 tx:0 rx:0 period:2999] from screen [on:0 period:-1866148911] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=4.9, 0.0, 0.0  rx=4.1 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1866148908] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,I/[SystemUI]TimeTickManager( 1473): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1473): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1473): called onTimeUpdated()
I/[SystemUI]Clock( 1473): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1473): called onTimeUpdated()
I/[SystemUI]DateView( 1473): called onTimeUpdated()
I/[SystemUI]DateView( 1473): called onTimeUpdated()
,D/KeyguardUpdateMonitor( 1473): handleTimeUpdate
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=2.4, 0.0, 0.0  rx=2.1 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1866145880] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=2.4, 0.0, 0.0  rx=2.1 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1866145877] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=1.2, 0.0, 0.0  rx=1.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1866142850] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=1.2, 0.0, 0.0  rx=1.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1866142847] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.6, 0.0, 0.0  rx=0.5 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1866139820] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.6, 0.0, 0.0  rx=0.5 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1866139817] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=1.3, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1866136790] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=1.3, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1866136787] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,D/sensors_hal_Time( 1031): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1031): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1031): tsOffsetIs: Apps: 575497815514; DSPS: 18998989; Offset : -4322607385
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1866133763] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:4] from screen [on:0 period:-1866133759] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.3, 0.0, 0.0  rx=0.2 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1866130732] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.3, 0.0, 0.0  rx=0.2 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1866130729] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,D/PowerManagerServiceEx( 1031): acquireWakeLockInternal: lock=538279423, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1031
,V/AlarmManager( 1031): ELAPSED_WAKEUP set : Alarm{164451a6 type 2 when 583843 android} when 583843
D/[Concierge]Service( 2627): onStartCommand(). Type : 9
,D/PowerManagerServiceEx( 1031): releaseWakeLockInternal: lock=538279423 [*alarm*], flags=0x0
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.2, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:2999] from screen [on:0 period:-1866127705] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.2, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-1866127704] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1866124686] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:9] from screen [on:0 period:-1866124677] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3000] from screen [on:0 period:-1866121656] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-1866121646] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3000] from screen [on:0 period:-1866118622] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1866118619] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,D/sensors_hal_Time( 1031): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1031): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1031): tsOffsetIs: Apps: 595499137694; DSPS: 19654392; Offset : -4322597512
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1866115601] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:4] from screen [on:0 period:-1866115597] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=1.0, 0.0, 0.0  rx=0.5 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1866112572] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=1.0, 0.0, 0.0  rx=0.5 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1866112569] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.3 bcn=0 [on:0 tx:0 rx:0 period:3000] from screen [on:0 period:-1866109544] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.3 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-1866109534] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.3, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1866106512] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.3, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1866106509] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1866103486] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-1866103476] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1866100455] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:11] from screen [on:0 period:-1866100444] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
V/GLSActivity( 2129): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2129): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 2129): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2129): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2129): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2129): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1031): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1031): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1031): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1031): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1031): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1415): onNotificationPosted
,D/SmartCoverUpdateMonitor( 1415): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1415): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1415): handleNotificationPosted(true)
D/QuickCircle( 1415): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1415): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1415): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1415): post do just update job
D/LgeQuickCoverNotificationData( 1415): showAll3
D/LgeQuickCoverNotificationData( 1415): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1415): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1415): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1415): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1415): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1415): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1415): [native noti] inex =  1,
D/LgeQuickCoverNotificationData( 1415): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1415): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1415): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1415): updateNotificationData: count=3
W/GLSActivity( 2129): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2129): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2129): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2129): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2129): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2129): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2129): 	at android.os.Binder.execTransact(Binder.java:446)
,E/PlayEventLogger( 7363): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 7363): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 7363): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/PlayEventLogger( 7363): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 7363): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/PlayEventLogger( 7363): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 7363): 	at android.os.Binder.execTransact(Binder.java:446)
D/QuickStatusbarLayout( 1415): Notification difference=198
D/QuickStatusbarLayout( 1415): child = android.widget.LinearLayout{9d5fc15 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
W/System  ( 7363): Ignoring header User-Agent because its value was null.
,D/libc-netbsd(  323): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  323): res_queryN name = play.googleapis.com, class = 1, type = 1
D/libc-netbsd(  323): res_queryN name = play.googleapis.com succeed
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:-1866097420] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:4] from screen [on:0 period:-1866097416] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
D/sensors_hal_Time( 1031): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1031): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1031): tsOffsetIs: Apps: 615501943416; DSPS: 20309844; Offset : -4322599459
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=2.0, 0.0, 0.0  rx=1.5 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1866094406] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=2.0, 0.0, 0.0  rx=1.5 bcn=0 [on:0 tx:0 rx:0 period:8] from screen [on:0 period:-1866094398] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=5.0, 0.0, 0.0  rx=5.3 bcn=0 [on:0 tx:0 rx:0 period:3000] from screen [on:0 period:-1866091377] gl rssi=-48 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=5.0, 0.0, 0.0  rx=5.3 bcn=0 [on:0 tx:0 rx:0 period:11] from screen [on:0 period:-1866091366] gl rssi=-48 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=3.5, 0.0, 0.0  rx=3.1 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1866088345] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=3.5, 0.0, 0.0  rx=3.1 bcn=0 [on:0 tx:0 rx:0 period:9] from screen [on:0 period:-1866088336] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
I/[SystemUI]TimeTickManager( 1473): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1473): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1473): called onTimeUpdated()
I/[SystemUI]Clock( 1473): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1473): called onTimeUpdated()
I/[SystemUI]DateView( 1473): called onTimeUpdated()
I/[SystemUI]DateView( 1473): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1473): handleTimeUpdate
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=1.8, 0.0, 0.0  rx=1.6 bcn=0 [on:0 tx:0 rx:0 period:2998] from screen [on:0 period:-1866085318] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=1.8, 0.0, 0.0  rx=1.6 bcn=0 [on:0 tx:0 rx:0 period:2] from screen [on:0 period:-1866085316] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.9, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1866082299] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.9, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1866082296] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3000] from screen [on:0 period:-1866079271] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1866079268] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.2, 0.0, 0.0  rx=0.2 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1866076241] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.2, 0.0, 0.0  rx=0.2 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1866076238] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,D/sensors_hal_Time( 1031): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1031): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1031): tsOffsetIs: Apps: 635503824294; DSPS: 20965265; Offset : -4322580075
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1866073213] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1866073210] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1866070185] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:9] from screen [on:0 period:-1866070176] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1866067155] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:11] from screen [on:0 period:-1866067144] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1866064121] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1866064118] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=1.0, 0.0, 0.0  rx=0.5 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1866061090] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=1.0, 0.0, 0.0  rx=0.5 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1866061087] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.3 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1866058061] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.3 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1866058058] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,D/sensors_hal_Time( 1031): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1031): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1031): tsOffsetIs: Apps: 655506005536; DSPS: 21620697; Offset : -4322596333
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.3, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1866055031] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.3, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1866055028] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3000] from screen [on:0 period:-1866052005] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-1866051995] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0,
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1866048974] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:12] from screen [on:0 period:-1866048962] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3009] from screen [on:0 period:-1866045935] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:6] from screen [on:0 period:-1866045929] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:-1866042912] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1866042909] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1866039881] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1866039878] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=1.0, 0.0, 0.0  rx=0.5 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1866036850] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=1.0, 0.0, 0.0  rx=0.5 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1866036847] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,D/sensors_hal_Time( 1031): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1031): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1031): tsOffsetIs: Apps: 675508037507; DSPS: 22276124; Offset : -4322608989
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.3 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1866033823] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.3 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1866033820] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.3, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1866030782] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.3, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1866030779] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3000] from screen [on:0 period:-1866027754] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-1866027744] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
I/[SystemUI]TimeTickManager( 1473): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1473): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1473): called onTimeUpdated()
I/[SystemUI]Clock( 1473): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1473): called onTimeUpdated()
I/[SystemUI]DateView( 1473): called onTimeUpdated()
I/[SystemUI]DateView( 1473): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1473): handleTimeUpdate
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1866024722] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1866024719] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1866021692] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1866021689] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1866018665] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:11] from screen [on:0 period:-1866018654] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
D/sensors_hal_Time( 1031): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1031): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1031): tsOffsetIs: Apps: 695510929688; DSPS: 22931578; Offset : -4322585278
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1866015633] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1866015630] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=1.0, 0.0, 0.0  rx=0.5 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1866012607] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=1.0, 0.0, 0.0  rx=0.5 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1866012604] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.3 bcn=0 [on:0 tx:0 rx:0 period:3000] from screen [on:0 period:-1866009579] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.3 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1866009576] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.3, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1866006550] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.3, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1866006547] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1866003522] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1866003519] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3000] from screen [on:0 period:-1866000494] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-1866000484] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3000] from screen [on:0 period:-1865997464] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:11] from screen [on:0 period:-1865997453] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
D/sensors_hal_Time( 1031): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1031): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1031): tsOffsetIs: Apps: 715513078013; DSPS: 23587009; Offset : -4322603753
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1865994433] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1865994430] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1865991405] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-1865991395] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1865988375] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-1865988365] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=1.0, 0.0, 0.0  rx=0.5 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1865985345] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=1.0, 0.0, 0.0  rx=0.5 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-1865985335] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.3 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:-1865982311] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.3 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1865982308] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.3, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1865979281] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.3, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1865979278] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1865976253] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1865976250] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,D/sensors_hal_Time( 1031): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1031): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1031): tsOffsetIs: Apps: 735514965868; DSPS: 24242431; Offset : -4322607935
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3000] from screen [on:0 period:-1865973225] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-1865973215] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3000] from screen [on:0 period:-1865970195] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-1865970185] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1865967162] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1865967159] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,I/[SystemUI]TimeTickManager( 1473): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1473): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1473): called onTimeUpdated()
I/[SystemUI]Clock( 1473): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1473): called onTimeUpdated()
I/[SystemUI]DateView( 1473): called onTimeUpdated()
I/[SystemUI]DateView( 1473): called onTimeUpdated()
,D/KeyguardUpdateMonitor( 1473): handleTimeUpdate
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1865964132] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1865964129] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=1.5, 0.0, 0.0  rx=0.5 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1865961110] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=1.5, 0.0, 0.0  rx=0.5 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1865961107] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=1.3, 0.0, 0.0  rx=1.3 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1865958082] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=1.3, 0.0, 0.0  rx=1.3 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1865958079] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,D/sensors_hal_Time( 1031): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1031): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1031): tsOffsetIs: Apps: 755516874560; DSPS: 24897853; Offset : -4322591437
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.6, 0.0, 0.0  rx=0.6 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1865955052] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.6, 0.0, 0.0  rx=0.6 bcn=0 [on:0 tx:0 rx:0 period:4] from screen [on:0 period:-1865955048] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.3, 0.0, 0.0  rx=0.3 bcn=0 [on:0 tx:0 rx:0 period:3005] from screen [on:0 period:-1865952030] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.3, 0.0, 0.0  rx=0.3 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1865952027] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.2, 0.0, 0.0  rx=0.2 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1865949001] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.2, 0.0, 0.0  rx=0.2 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1865948998] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1865945972] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1865945969] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1865942941] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1865942938] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1865939911] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1865939908] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1865936881] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1865936878] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,D/sensors_hal_Time( 1031): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1031): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1031): tsOffsetIs: Apps: 775519191688; DSPS: 25553289; Offset : -4322593671
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=1.0, 0.0, 0.0  rx=1.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1865933852] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=1.0, 0.0, 0.0  rx=1.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1865933849] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.5 bcn=0 [on:0 tx:0 rx:0 period:3000] from screen [on:0 period:-1865930824] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.5 bcn=0 [on:0 tx:0 rx:0 period:11] from screen [on:0 period:-1865930813] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.3, 0.0, 0.0  rx=0.3 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1865927791] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.3, 0.0, 0.0  rx=0.3 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1865927788] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1865924761] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1865924758] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1865921732] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:4] from screen [on:0 period:-1865921728] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1865918704] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:4] from screen [on:0 period:-1865918700] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,D/sensors_hal_Time( 1031): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1031): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1031): tsOffsetIs: Apps: 795521520691; DSPS: 26208725; Offset : -4322584056
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1865915674] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-1865915664] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1865912644] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:12] from screen [on:0 period:-1865912632] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=1.5, 0.0, 0.0  rx=1.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1865909620] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=1.5, 0.0, 0.0  rx=1.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1865909617] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.5 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1865906592] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.5 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1865906589] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,I/[SystemUI]TimeTickManager( 1473): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1473): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1473): called onTimeUpdated()
I/[SystemUI]Clock( 1473): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1473): called onTimeUpdated()
I/[SystemUI]DateView( 1473): called onTimeUpdated()
I/[SystemUI]DateView( 1473): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1473): handleTimeUpdate
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.3 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1865903563] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.3 bcn=0 [on:0 tx:0 rx:0 period:4] from screen [on:0 period:-1865903559] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.2, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1865900532] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.2, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1865900529] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1865897503] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1865897500] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,D/PowerManagerServiceEx( 1031): acquireWakeLockInternal: lock=538279423, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1031
,V/AlarmManager( 1031): ELAPSED_WAKEUP set : Alarm{1144e018 type 2 when 815401 android} when 815401
D/[Concierge]Service( 2627): onStartCommand(). Type : 9
,D/PowerManagerServiceEx( 1031): releaseWakeLockInternal: lock=538279423 [*alarm*], flags=0x0
,D/sensors_hal_Time( 1031): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1031): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1031): tsOffsetIs: Apps: 815523134902; DSPS: 26864138; Offset : -4322584803
,I/BooksSync( 6604): Starting books sync
,D/BooksSync( 6604): started syncMyEbooks
,V/GLSActivity( 2129): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2129): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2129): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2129): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2129): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2129): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1031): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1031): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1031): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1031): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1031): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1415): onNotificationPosted
D/SmartCoverUpdateMonitor( 1415): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1415): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1415): handleNotificationPosted(true)
D/QuickCircle( 1415): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1415): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1415): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1415): post do just update job
D/LgeQuickCoverNotificationData( 1415): showAll3
D/LgeQuickCoverNotificationData( 1415): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1415): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1415): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1415): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1415): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1415): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1415): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1415): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1415): [native noti] inex =  2
,D/LgeQuickCoverNotificationData( 1415): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1415): updateNotificationData: count=3
W/GLSActivity( 2129): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2129): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2129): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2129): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2129): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2129): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2129): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 6604): Authentication error
E/BooksAccountManager( 6604): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6604): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6604): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6604): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6604): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6604): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6604): null auth token
D/libc-netbsd(  323): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  323): res_queryN name = www.googleapis.com, class = 1, type = 1
,D/QuickStatusbarLayout( 1415): Notification difference=198
D/QuickStatusbarLayout( 1415): child = android.widget.LinearLayout{9d5fc15 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1865894474] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:12] from screen [on:0 period:-1865894462] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
D/libc-netbsd(  323): res_queryN name = www.googleapis.com succeed
,W/ApiaryClient( 6604): Error response from books API: {
W/ApiaryClient( 6604):  "error": {
W/ApiaryClient( 6604):   "errors": [
W/ApiaryClient( 6604):    {
W/ApiaryClient( 6604):     "domain": "global",
W/ApiaryClient( 6604):     "reason": "required",
W/ApiaryClient( 6604):     "message": "Login Required",
W/ApiaryClient( 6604):     "locationType": "header",
W/ApiaryClient( 6604):     "location": "Authorization"
W/ApiaryClient( 6604):    }
W/ApiaryClient( 6604):   ],
W/ApiaryClient( 6604):   "code": 401,
W/ApiaryClient( 6604):   "message": "Login Required"
W/ApiaryClient( 6604):  }
W/ApiaryClient( 6604): }
,W/ApiaryClient( 6604): errCount = 1: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6604): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=7290648614087186020&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6604): Headers:
W/ApiaryClient( 6604): accept-encoding: [gzip]
W/ApiaryClient( 6604): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6604): gdata-version: 2
V/GLSActivity( 2129): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     ( 2129): Explicit concurrent mark sweep GC freed 37385(2MB) AllocSpace objects, 22(3MB) LOS objects, 50% free, 30MB/62MB, paused 2.587ms total 77.637ms
,I/GLSUser ( 2129): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2129): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2129): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2129): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2129): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1031): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1031): pkg=com.google.android.gms canInterrupt=false intercept=true
,I/NotificationServiceEx( 1031): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1031): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1031): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1415): onNotificationPosted
D/SmartCoverUpdateMonitor( 1415): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1415): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1415): handleNotificationPosted(true)
D/QuickCircle( 1415): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1415): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1415): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1415): post do just update job
D/LgeQuickCoverNotificationData( 1415): showAll3
D/LgeQuickCoverNotificationData( 1415): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1415): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1415): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1415): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1415): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1415): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1415): [native noti] inex =  1
,D/LgeQuickCoverNotificationData( 1415): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1415): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1415): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1415): updateNotificationData: count=3
,W/GLSActivity( 2129): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2129): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2129): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2129): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2129): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2129): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2129): 	at android.os.Binder.execTransact(Binder.java:446)
D/QuickStatusbarLayout( 1415): Notification difference=198
D/QuickStatusbarLayout( 1415): child = android.widget.LinearLayout{9d5fc15 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,E/BooksAccountManager( 6604): Authentication error
E/BooksAccountManager( 6604): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6604): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6604): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6604): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6604): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6604): 	at android.os.Binder.execTransact(Binder.java:446)
,E/HttpHelper( 6604): null auth token
W/ApiaryClient( 6604): Error response from books API: {
W/ApiaryClient( 6604):  "error": {
W/ApiaryClient( 6604):   "errors": [
W/ApiaryClient( 6604):    {
W/ApiaryClient( 6604):     "domain": "global",
W/ApiaryClient( 6604):     "reason": "required",
W/ApiaryClient( 6604):     "message": "Login Required",
W/ApiaryClient( 6604):     "locationType": "header",
W/ApiaryClient( 6604):     "location": "Authorization"
W/ApiaryClient( 6604):    }
W/ApiaryClient( 6604):   ],
W/ApiaryClient( 6604):   "code": 401,
W/ApiaryClient( 6604):   "message": "Login Required"
W/ApiaryClient( 6604):  }
W/ApiaryClient( 6604): }
,W/ApiaryClient( 6604): errCount = 2: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6604): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=7290648614087186020&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6604): Headers:
W/ApiaryClient( 6604): accept-encoding: [gzip]
W/ApiaryClient( 6604): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6604): gdata-version: 2
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=1.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1865891441] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=1.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1865891438] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,V/GLSActivity( 2129): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2129): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2129): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2129): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2129): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2129): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1031): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1031): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1031): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1031): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1031): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1415): onNotificationPosted
,D/SmartCoverUpdateMonitor( 1415): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1415): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1415): handleNotificationPosted(true)
D/QuickCircle( 1415): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1415): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1415): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1415): post do just update job
D/LgeQuickCoverNotificationData( 1415): showAll3
D/LgeQuickCoverNotificationData( 1415): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1415): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1415): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1415): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1415): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1415): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1415): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1415): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1415): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1415): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1415): updateNotificationData: count=3
,W/GLSActivity( 2129): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2129): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2129): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2129): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2129): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2129): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2129): 	at android.os.Binder.execTransact(Binder.java:446)
E/BooksAccountManager( 6604): Authentication error
E/BooksAccountManager( 6604): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6604): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6604): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6604): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6604): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6604): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6604): null auth token
D/QuickStatusbarLayout( 1415): Notification difference=198
D/QuickStatusbarLayout( 1415): child = android.widget.LinearLayout{9d5fc15 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,W/ApiaryClient( 6604): Error response from books API: {
W/ApiaryClient( 6604):  "error": {
W/ApiaryClient( 6604):   "errors": [
W/ApiaryClient( 6604):    {
W/ApiaryClient( 6604):     "domain": "global",
W/ApiaryClient( 6604):     "reason": "required",
W/ApiaryClient( 6604):     "message": "Login Required",
W/ApiaryClient( 6604):     "locationType": "header",
W/ApiaryClient( 6604):     "location": "Authorization"
W/ApiaryClient( 6604):    }
W/ApiaryClient( 6604):   ],
W/ApiaryClient( 6604):   "code": 401,
W/ApiaryClient( 6604):   "message": "Login Required"
W/ApiaryClient( 6604):  }
W/ApiaryClient( 6604): }
W/ApiaryClient( 6604): errCount = 3: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6604): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=7290648614087186020&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6604): Headers:
W/ApiaryClient( 6604): accept-encoding: [gzip]
W/ApiaryClient( 6604): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6604): gdata-version: 2
,E/BooksSync( 6604): Soft error: 
E/BooksSync( 6604): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 6604): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=7290648614087186020&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 6604): Headers:
E/BooksSync( 6604): accept-encoding: [gzip]
E/BooksSync( 6604): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 6604): gdata-version: 2
E/BooksSync( 6604): 
E/BooksSync( 6604): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 6604): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 6604): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 6604): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 6604): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 6604): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 6604): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 6604): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 6604): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 6604): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 6604): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 6604): {
E/BooksSync( 6604):  "error": {
E/BooksSync( 6604):   "errors": [
E/BooksSync( 6604):    {
E/BooksSync( 6604):     "domain": "global",
E/BooksSync( 6604):     "reason": "required",
E/BooksSync( 6604):     "message": "Login Required",
E/BooksSync( 6604):     "locationType": "header",
E/BooksSync( 6604):     "location": "Authorization"
E/BooksSync( 6604):    }
E/BooksSync( 6604):   ],
E/BooksSync( 6604):   "code": 401,
E/BooksSync( 6604):   "message": "Login Required"
E/BooksSync( 6604):  }
E/BooksSync( 6604): }
E/BooksSync( 6604): 
E/BooksSync( 6604): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 6604): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 6604): 	... 8 more
,E/BooksSync( 6604): Sync error
E/BooksSync( 6604): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 6604): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=7290648614087186020&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 6604): Headers:
E/BooksSync( 6604): accept-encoding: [gzip]
E/BooksSync( 6604): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 6604): gdata-version: 2
E/BooksSync( 6604): 
E/BooksSync( 6604): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 6604): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 6604): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 6604): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 6604): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 6604): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 6604): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 6604): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 6604): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 6604): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 6604): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 6604): {
E/BooksSync( 6604):  "error": {
E/BooksSync( 6604):   "errors": [
E/BooksSync( 6604):    {
E/BooksSync( 6604):     "domain": "global",
E/BooksSync( 6604):     "reason": "required",
E/BooksSync( 6604):     "message": "Login Required",
E/BooksSync( 6604):     "locationType": "header",
E/BooksSync( 6604):     "location": "Authorization"
E/BooksSync( 6604):    }
E/BooksSync( 6604):   ],
E/BooksSync( 6604):   "code": 401,
E/BooksSync( 6604):   "message": "Login Required"
E/BooksSync( 6604):  }
E/BooksSync( 6604): }
E/BooksSync( 6604): 
E/BooksSync( 6604): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 6604): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 6604): 	... 8 more
I/BooksSync( 6604): Finished books sync
D/SyncManager( 1031): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 815401, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=8.0, 0.0, 0.0  rx=7.5 bcn=0 [on:0 tx:0 rx:0 period:2994] from screen [on:0 period:-1865888420] gl rssi=-48 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=8.0, 0.0, 0.0  rx=7.5 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1865888417] gl rssi=-48 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=6.5, 0.0, 0.0  rx=5.3 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1865885390] gl rssi=-48 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=6.5, 0.0, 0.0  rx=5.3 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1865885387] gl rssi=-48 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=3.3, 0.0, 0.0  rx=2.6 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1865882361] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=3.3, 0.0, 0.0  rx=2.6 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1865882358] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=1.6, 0.0, 0.0  rx=1.3 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1865879332] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=1.6, 0.0, 0.0  rx=1.3 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1865879329] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1865876303] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1865876300] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,D/sensors_hal_Time( 1031): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1031): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1031): tsOffsetIs: Apps: 835525023592; DSPS: 27519560; Offset : -4322590598
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.3 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1865873273] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.3 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1865873270] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.2, 0.0, 0.0  rx=0.2 bcn=0 [on:0 tx:0 rx:0 period:3000] from screen [on:0 period:-1865870246] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.2, 0.0, 0.0  rx=0.2 bcn=0 [on:0 tx:0 rx:0 period:9] from screen [on:0 period:-1865870237] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1865867215] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:9] from screen [on:0 period:-1865867206] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
V/AlarmManager( 1031): ELAPSED_WAKEUP set : Alarm{af85342 type 2 when 845604 android} when 845604
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1865864184] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-1865864174] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1865861153] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1865861150] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=1.0, 0.0, 0.0  rx=0.5 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1865858125] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=1.0, 0.0, 0.0  rx=0.5 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-1865858115] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
D/sensors_hal_Time( 1031): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1031): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1031): tsOffsetIs: Apps: 855527327647; DSPS: 28174996; Offset : -4322605802
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.3 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1865855095] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.3 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-1865855085] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.3, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1865852061] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.3, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1865852058] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=2.1, 0.0, 0.0  rx=2.6 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1865849039] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=2.1, 0.0, 0.0  rx=2.6 bcn=0 [on:0 tx:0 rx:0 period:4] from screen [on:0 period:-1865849035] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,D/Finsky  ( 7363): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
,V/AlarmManager( 1031): RTC_WAKEUP set : Alarm{298ff090 type 0 when 1449833094876 com.android.vending} when 1449833094876
,V/GLSActivity( 2129): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2129): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 2129): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2129): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2129): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2129): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/Finsky  ( 7363): [1] 1.onErrorResponse: Unable to preload experiments: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,V/GLSActivity( 2129): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/GLSUser ( 2129): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 2129): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2129): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2129): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2129): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/GLSActivity( 2129): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2129): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 2129): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2129): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2129): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2129): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/Finsky  ( 7363): [1] LibraryUpdateListener.onErrorResponse: Library replication failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,V/SIM_STK ( 1031): Menu title from STK is T-Mobile
,V/GLSActivity( 2129): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2129): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 2129): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2129): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2129): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2129): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/Finsky  ( 7363): [1] 2.onErrorResponse: Update check failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,D/Finsky  ( 7363): [1] DailyHygiene.logDeviceFeaturesAndContinue: Logging device features
D/Finsky  ( 7363): [1] DailyHygiene.flushEventLogsAndContinue: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 7363): [1] DailyHygiene.reschedule: Scheduling new run in 28 minutes (failures=2)
D/DeviceConnectionService( 1832): client connected with version: 7571000
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=1.1, 0.0, 0.0  rx=1.3 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1865846011] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=1.1, 0.0, 0.0  rx=1.3 bcn=0 [on:0 tx:0 rx:0 period:2] from screen [on:0 period:-1865846009] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,I/[SystemUI]TimeTickManager( 1473): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1473): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1473): called onTimeUpdated()
I/[SystemUI]Clock( 1473): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1473): called onTimeUpdated()
I/[SystemUI]DateView( 1473): called onTimeUpdated()
I/[SystemUI]DateView( 1473): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1473): handleTimeUpdate
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.6 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1865842989] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.6 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1865842986] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.3, 0.0, 0.0  rx=0.3 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1865839959] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.3, 0.0, 0.0  rx=0.3 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1865839956] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.2 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1865836930] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.2 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1865836927] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,D/sensors_hal_Time( 1031): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1031): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1031): tsOffsetIs: Apps: 875529514150; DSPS: 28830427; Offset : -4322586072
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=1.1, 0.0, 0.0  rx=0.6 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1865833901] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=1.1, 0.0, 0.0  rx=0.6 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1865833898] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.3 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1865830872] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.3 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1865830869] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.3, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1865827842] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.3, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1865827839] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1865824813] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1865824810] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1865821785] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:9] from screen [on:0 period:-1865821776] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
D/PowerManagerServiceEx( 1031): acquireWakeLockInternal: lock=538279423, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1031
,V/AlarmManager( 1031): RTC_WAKEUP set : Alarm{3f52f052 type 0 when 1449833114154 com.android.vending} when 1449833114154
,D/[Concierge]Service( 2627): onStartCommand(). Type : 9
,D/PowerManagerServiceEx( 1031): releaseWakeLockInternal: lock=538279423 [*alarm*], flags=0x0
,V/SIM_STK ( 1031): Menu title from STK is T-Mobile
,V/GLSActivity( 2129): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2129): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 2129): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2129): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2129): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2129): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/Finsky  ( 7363): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 7363): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 7363): [1] 5.onFinished: Scheduling replication attempt 1.
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3000] from screen [on:0 period:-1865818755] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:11] from screen [on:0 period:-1865818744] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
D/sensors_hal_Time( 1031): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1031): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1031): tsOffsetIs: Apps: 895531483569; DSPS: 29485852; Offset : -4322600088
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1865815724] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:9] from screen [on:0 period:-1865815715] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1865812694] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:11] from screen [on:0 period:-1865812683] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=1.0, 0.0, 0.0  rx=0.5 bcn=0 [on:0 tx:0 rx:0 period:3000] from screen [on:0 period:-1865809664] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=1.0, 0.0, 0.0  rx=0.5 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-1865809654] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.3 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1865806633] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.3 bcn=0 [on:0 tx:0 rx:0 period:4] from screen [on:0 period:-1865806629] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.3, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1865803610] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.3, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1865803607] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,V/AlarmManager( 1031): RTC_WAKEUP set : Alarm{3b9c974d type 0 when 1449833144740 com.android.vending} when 1449833144740
,V/SIM_STK ( 1031): Menu title from STK is T-Mobile
,V/GLSActivity( 2129): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     ( 1031): Explicit concurrent mark sweep GC freed 115361(5MB) AllocSpace objects, 8(896KB) LOS objects, 33% free, 44MB/67MB, paused 1.824ms total 105.733ms
,I/GLSUser ( 2129): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 2129): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2129): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2129): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2129): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3000] from screen [on:0 period:-1865800582] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-1865800581] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
D/Finsky  ( 7363): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 7363): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 7363): [1] 5.onFinished: Scheduling replication attempt 2.
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1865797570] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1865797567] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,D/sensors_hal_Time( 1031): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1031): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1031): tsOffsetIs: Apps: 915533404135; DSPS: 30141275; Offset : -4322602311
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1865794544] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-1865794534] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1865791514] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:4] from screen [on:0 period:-1865791510] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1865788485] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:9] from screen [on:0 period:-1865788476] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
I/[SystemUI]TimeTickManager( 1473): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1473): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1473): called onTimeUpdated()
I/[SystemUI]Clock( 1473): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1473): called onTimeUpdated()
I/[SystemUI]DateView( 1473): called onTimeUpdated()
I/[SystemUI]DateView( 1473): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1473): handleTimeUpdate
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1865785454] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-1865785444] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=1.0, 0.0, 0.0  rx=0.5 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1865782422] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=1.0, 0.0, 0.0  rx=0.5 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1865782419] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.3 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1865779393] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.3 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1865779390] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.3, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3000] from screen [on:0 period:-1865776365] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.3, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:11] from screen [on:0 period:-1865776354] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
D/sensors_hal_Time( 1031): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1031): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1031): tsOffsetIs: Apps: 935535019387; DSPS: 30796688; Offset : -4322604440
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1865773331] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1865773328] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,D/PowerManagerServiceEx( 1031): acquireWakeLockInternal: lock=538279423, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1031
,V/AlarmManager( 1031): RTC_WAKEUP set : Alarm{12acf114 type 0 when 1449833165471 com.android.vending} when 1449833165471
,D/[Concierge]Service( 2627): onStartCommand(). Type : 9
,D/PowerManagerServiceEx( 1031): releaseWakeLockInternal: lock=538279423 [*alarm*], flags=0x0
,V/SIM_STK ( 1031): Menu title from STK is T-Mobile
,V/GLSActivity( 2129): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2129): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 2129): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 2129): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2129): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2129): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/Finsky  ( 7363): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 7363): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 7363): [1] 5.onFinished: Scheduling replication attempt 3.
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1865770301] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1865770298] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1865767270] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:4] from screen [on:0 period:-1865767266] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1865764240] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1865764237] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1865761210] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1865761207] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=1.0, 0.0, 0.0  rx=0.5 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1865758180] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=1.0, 0.0, 0.0  rx=0.5 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1865758177] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,D/sensors_hal_Time( 1031): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1031): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1031): tsOffsetIs: Apps: 955537182505; DSPS: 31452119; Offset : -4322608199
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.3 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1865755151] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.3 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1865755148] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.3, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1865752111] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.3, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1865752108] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1865749082] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1865749079] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1865746052] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1865746049] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1865743022] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1865743019] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,V/AlarmManager( 1031): RTC_WAKEUP set : Alarm{192db057 type 0 when 1449833194447 com.android.vending} when 1449833194447
,V/SIM_STK ( 1031): Menu title from STK is T-Mobile
,V/GLSActivity( 2129): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2129): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 2129): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2129): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2129): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2129): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/Finsky  ( 7363): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 7363): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 7363): [1] 5.onFinished: Scheduling replication attempt 4.
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1865739994] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-1865739984] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1865736961] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1865736958] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,D/sensors_hal_Time( 1031): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1031): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1031): tsOffsetIs: Apps: 975539506351; DSPS: 32107555; Offset : -4322603742
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=1.0, 0.0, 0.0  rx=0.5 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1865733930] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=1.0, 0.0, 0.0  rx=0.5 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1865733927] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.3 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1865730901] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.3 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1865730898] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.3, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1865727871] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.3, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1865727868] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,I/[SystemUI]TimeTickManager( 1473): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1473): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1473): called onTimeUpdated()
I/[SystemUI]Clock( 1473): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1473): called onTimeUpdated()
I/[SystemUI]DateView( 1473): called onTimeUpdated()
I/[SystemUI]DateView( 1473): called onTimeUpdated()
,D/KeyguardUpdateMonitor( 1473): handleTimeUpdate
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1865724841] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1865724838] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1865721812] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1865721809] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1865718784] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-1865718774] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
D/sensors_hal_Time( 1031): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1031): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1031): tsOffsetIs: Apps: 995542030875; DSPS: 32762998; Offset : -4322611968
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1865715751] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1865715748] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1865712723] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1865712720] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=1.0, 0.0, 0.0  rx=0.5 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1865709701] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=1.0, 0.0, 0.0  rx=0.5 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1865709698] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,D/PowerManagerServiceEx( 1031): acquireWakeLockInternal: lock=538279423, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1031
,V/AlarmManager( 1031): RTC_WAKEUP set : Alarm{35a4a086 type 0 when 1449833225661 com.android.vending} when 1449833225661
,D/[Concierge]Service( 2627): onStartCommand(). Type : 9
,D/PowerManagerServiceEx( 1031): releaseWakeLockInternal: lock=538279423 [*alarm*], flags=0x0
,V/SIM_STK ( 1031): Menu title from STK is T-Mobile
,V/GLSActivity( 2129): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2129): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 2129): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2129): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2129): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2129): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/Finsky  ( 7363): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 7363): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 7363): [1] 5.onFinished: Scheduling replication attempt 5.
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.3 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1865706675] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.3 bcn=0 [on:0 tx:0 rx:0 period:11] from screen [on:0 period:-1865706664] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.3, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1865703644] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.3, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:9] from screen [on:0 period:-1865703635] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1865700613] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1865700610] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3000] from screen [on:0 period:-1865697585] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:9] from screen [on:0 period:-1865697576] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
D/sensors_hal_Time( 1031): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1031): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1031): tsOffsetIs: Apps: 1015544369566; DSPS: 33418434; Offset : -4322592848
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1865694554] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:9] from screen [on:0 period:-1865694545] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3000] from screen [on:0 period:-1865691525] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:11] from screen [on:0 period:-1865691514] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1865688493] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1865688490] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1865685464] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:4] from screen [on:0 period:-1865685460] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=1.0, 0.0, 0.0  rx=0.5 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1865682416] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=1.0, 0.0, 0.0  rx=0.5 bcn=0 [on:0 tx:0 rx:0 period:8] from screen [on:0 period:-1865682408] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.3 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1865679386] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.3 bcn=0 [on:0 tx:0 rx:0 period:9] from screen [on:0 period:-1865679377] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
V/AlarmManager( 1031): RTC_WAKEUP set : Alarm{2c4e00d1 type 0 when 1449833258373 com.android.vending} when 1449833258373
,V/SIM_STK ( 1031): Menu title from STK is T-Mobile
,V/GLSActivity( 2129): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2129): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 2129): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2129): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2129): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2129): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/Finsky  ( 7363): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 7363): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 7363): [1] 5.onFinished: Giving up after 6 failures.
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.3, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1865676354] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.3, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-1865676344] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
D/sensors_hal_Time( 1031): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1031): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1031): tsOffsetIs: Apps: 1035546541120; DSPS: 34073865; Offset : -4322587885
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1865673324] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-1865673314] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3000] from screen [on:0 period:-1865670293] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1865670290] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1865667263] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1865667260] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,I/[SystemUI]TimeTickManager( 1473): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1473): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1473): called onTimeUpdated()
I/[SystemUI]Clock( 1473): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1473): called onTimeUpdated()
I/[SystemUI]DateView( 1473): called onTimeUpdated()
I/[SystemUI]DateView( 1473): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1473): handleTimeUpdate
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1865664230] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1865664227] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1865661200] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1865661197] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=1.0, 0.0, 0.0  rx=0.5 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1865658171] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=1.0, 0.0, 0.0  rx=0.5 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1865658168] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,D/sensors_hal_Time( 1031): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1031): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1031): tsOffsetIs: Apps: 1055548547831; DSPS: 34729291; Offset : -4322595230
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.3 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1865655142] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.3 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1865655139] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.3, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1865652114] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.3, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-1865652104] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1865649084] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-1865649074] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1865646052] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1865646049] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=1.0, 0.0, 0.0  rx=1.5 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1865643022] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=1.0, 0.0, 0.0  rx=1.5 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1865643019] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1865639994] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:9] from screen [on:0 period:-1865639985] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-47 f=2412 sc=60 link=72 tx=0.3, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1865636963] gl rssi=-47 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-47 f=2412 sc=60 link=72 tx=0.3, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1865636960] gl rssi=-47 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,D/sensors_hal_Time( 1031): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1031): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1031): tsOffsetIs: Apps: 1075551327928; DSPS: 35384742; Offset : -4322592311
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-47 f=2412 sc=60 link=72 tx=1.1, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:2999] from screen [on:0 period:-1865633916] gl rssi=-47 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-47 f=2412 sc=60 link=72 tx=1.1, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:9] from screen [on:0 period:-1865633907] gl rssi=-47 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-47 f=2412 sc=60 link=72 tx=0.6, 0.0, 0.0  rx=0.3 bcn=0 [on:0 tx:0 rx:0 period:3000] from screen [on:0 period:-1865630885] gl rssi=-47 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-47 f=2412 sc=60 link=72 tx=0.6, 0.0, 0.0  rx=0.3 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-1865630875] gl rssi=-47 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-47 f=2412 sc=60 link=72 tx=0.3, 0.0, 0.0  rx=0.2 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1865627862] gl rssi=-47 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-47 f=2412 sc=60 link=72 tx=0.3, 0.0, 0.0  rx=0.2 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1865627859] gl rssi=-47 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-47 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1865624831] gl rssi=-47 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-47 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1865624828] gl rssi=-47 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-47 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1865621801] gl rssi=-47 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-47 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1865621798] gl rssi=-47 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-47 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1865618772] gl rssi=-47 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-47 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1865618769] gl rssi=-47 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,D/sensors_hal_Time( 1031): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1031): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1031): tsOffsetIs: Apps: 1095552951618; DSPS: 36040155; Offset : -4322586105
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-47 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1865615742] gl rssi=-47 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-47 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:2] from screen [on:0 period:-1865615740] gl rssi=-47 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-47 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1865612714] gl rssi=-47 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-47 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:9] from screen [on:0 period:-1865612705] gl rssi=-47 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-47 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1865609685] gl rssi=-47 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-47 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:11] from screen [on:0 period:-1865609674] gl rssi=-47 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-47 f=2412 sc=60 link=72 tx=1.0, 0.0, 0.0  rx=0.5 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1865606653] gl rssi=-47 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-47 f=2412 sc=60 link=72 tx=1.0, 0.0, 0.0  rx=0.5 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1865606650] gl rssi=-47 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,I/[SystemUI]TimeTickManager( 1473): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1473): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1473): called onTimeUpdated()
I/[SystemUI]Clock( 1473): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1473): called onTimeUpdated()
I/[SystemUI]DateView( 1473): called onTimeUpdated()
I/[SystemUI]DateView( 1473): called onTimeUpdated()
,D/KeyguardUpdateMonitor( 1473): handleTimeUpdate
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.3 bcn=0 [on:0 tx:0 rx:0 period:3000] from screen [on:0 period:-1865603625] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.3 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-1865603615] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.3, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1865600596] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.3, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:9] from screen [on:0 period:-1865600587] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1865597566] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:9] from screen [on:0 period:-1865597557] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
D/sensors_hal_Time( 1031): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1031): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1031): tsOffsetIs: Apps: 1115555298590; DSPS: 36695592; Offset : -4322589013
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1865594535] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:9] from screen [on:0 period:-1865594526] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1865591506] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:9] from screen [on:0 period:-1865591497] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1865588477] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1865588474] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1865585456] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-1865585446] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=1.0, 0.0, 0.0  rx=0.5 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1865582424] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=1.0, 0.0, 0.0  rx=0.5 bcn=0 [on:0 tx:0 rx:0 period:9] from screen [on:0 period:-1865582415] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.3 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1865579393] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.3 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1865579390] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.3, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1865576365] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.3, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:9] from screen [on:0 period:-1865576356] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
D/sensors_hal_Time( 1031): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1031): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1031): tsOffsetIs: Apps: 1135557630248; DSPS: 37351029; Offset : -4322607103
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1865573335] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-1865573325] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3000] from screen [on:0 period:-1865570305] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-1865570295] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1865567274] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:9] from screen [on:0 period:-1865567265] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1865564244] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:11] from screen [on:0 period:-1865564233] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3007] from screen [on:0 period:-1865561207] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1865561204] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=1.0, 0.0, 0.0  rx=0.5 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1865558176] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=1.0, 0.0, 0.0  rx=0.5 bcn=0 [on:0 tx:0 rx:0 period:9] from screen [on:0 period:-1865558167] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
D/sensors_hal_Time( 1031): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1031): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1031): tsOffsetIs: Apps: 1155559665813; DSPS: 38006455; Offset : -4322585881
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.3 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1865555147] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.3 bcn=0 [on:0 tx:0 rx:0 period:9] from screen [on:0 period:-1865555138] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.3, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1865552125] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.3, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-1865552115] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1865549095] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-1865549085] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1865546063] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1865546060] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,I/[SystemUI]TimeTickManager( 1473): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1473): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1473): called onTimeUpdated()
I/[SystemUI]Clock( 1473): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1473): called onTimeUpdated()
I/[SystemUI]DateView( 1473): called onTimeUpdated()
I/[SystemUI]DateView( 1473): called onTimeUpdated()
,D/KeyguardUpdateMonitor( 1473): handleTimeUpdate
D/PowerManagerServiceEx( 1031): acquireWakeLockInternal: lock=538279423, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1031
,I/ActivityManager( 1031): Start proc com.lge.clock for broadcast com.lge.clock/.widget.DigitalAppWidgetProvider: pid=7865 uid=10010 gids={50010, 9997, 3003, 1028, 4002} abi=armeabi-v7a
,D/[Concierge]Service( 2627): onStartCommand(). Type : 9
,I/DigitalAppWidgetProvider( 7865): onReceive: com.android.deskclock.ON_QUARTER_HOUR
,V/DigitalAppWidgetProvider( 7865): startAlarmOnQuarterHour android.app.ReceiverRestrictedContext@f1bd36
D/PowerManagerServiceEx( 1031): releaseWakeLockInternal: lock=538279423 [*alarm*], flags=0x0
I/ActivityManager( 1031): Killing 7089:com.uei.lg.quicksetsdk.maxq616/1000 (adj 15): empty #17
I/QRemote ( 5995): [RemoteControlManager.java:195:onServiceDisconnected()] oooooo start
W/System.err( 5995): android.os.DeadObjectException
W/System.err( 5995): 	at android.os.BinderProxy.transactNative(Native Method)
W/System.err( 5995): 	at android.os.BinderProxy.transact(Binder.java:496)
,W/System.err( 5995): 	at com.uei.control.IControl.unregisterCallback(IControl.java:502)
W/System.err( 5995): 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:199)
W/System.err( 5995): 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
W/System.err( 5995): 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
W/System.err( 5995): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 5995): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 5995): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 5995): 	at android.app.ActivityThread.main(ActivityThread.java:5274)
W/System.err( 5995): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 5995): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 5995): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
W/System.err( 5995): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
E/UEI.SmartControl( 5995): IControl.unregisterCallback error: android.os.DeadObjectException
W/System.err( 5995): android.os.DeadObjectException
W/System.err( 5995): 	at android.os.BinderProxy.transactNative(Native Method)
W/System.err( 5995): 	at android.os.BinderProxy.transact(Binder.java:496)
W/System.err( 5995): 	at com.uei.control.IControl.unregisterSetupReadyCallback(IControl.java:818)
W/System.err( 5995): 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:200)
W/System.err( 5995): 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
W/System.err( 5995): 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
W/System.err( 5995): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 5995): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 5995): 	at android.os.Looper.loop(Looper.java:135)
,W/System.err( 5995): 	at android.app.ActivityThread.main(ActivityThread.java:5274)
W/System.err( 5995): ,	at java.lang.reflect.Method.invoke(Native Method)
,W/System.err( 5995): ,	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 5995): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
W/System.err( 5995): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
E/UEI.SmartControl( 5995): IControl.unregisterSetupReadyCallback error: android.os.DeadObjectException
I/QRemote ( 5995): [RemoteControlManager.java:203:onServiceDisconnected()] oooooo Control unbind before rebinding.
W/libprocessgroup( 1031): failed to open /acct/uid_1000/pid_7089/cgroup.procs: No such file or directory
,W/ActivityManager( 1031): Scheduling restart of crashed service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service in 1000ms
,D/QRemote ( 5995): [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]10
I/QRemote ( 5995): [RemoteControlManager.java:157:onBindIRService()] oooooo bind
I/ActivityManager( 1031): Start proc com.uei.lg.quicksetsdk.maxq616 for service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service: pid=7902 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,D/QRemote ( 5995): [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
,D/UEI.SmartControl( 7902): Quickset Services start...
,I/UEI.SmartControl( 7902): Manufacture = LGE
,D/UEI.SmartControl( 7902): Id = LGNevo
D/UEI.SmartControl( 7902): File observer start...
E/UEI.SmartControl( 7902): IR Port is disabled: false
D/UEI.SmartControl( 7902): Starting file observer...
D/UEI.SmartControl( 7902): Extracting JNI libs...
D/UEI.SmartControl( 7902): --- this system supports 32-bit or 64-bit only
D/UEI.SmartControl( 7902): --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
D/UEI.SmartControl( 7902): --- Checking lib: libqs_armeabi-v7a.zip
D/UEI.SmartControl( 7902): --- Extracting JNI libs: libqs_armeabi-v7a.zip
,I/UEI.SmartControl( 7902): --- Selecting new region: 6
,I/UEI.SmartControl( 7902): Model = LG-D855
D/UEI.SmartControl( 7902): QS Service created
I/UEI.SmartControl( 7902): Service initServices...
D/UEI.SmartControl( 7902): QS start get config
,D/UEI.SmartControl( 7902): Loading JNI Libs...
,I/UEI.SmartControl( 7902): Supports setup maps: true
,D/UEI.SmartControl( 7902): QS start statue = true Error code = 0
I/UEI.SmartControl( 7902): QS version = v2.7.10.1_RC1
I/UEI.SmartControl( 7902): QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
I/UEI.SmartControl( 7902): ### init IR Blaster...
D/serial_port( 7902): Configuring serial port
E/UEI.SmartControl( 7902): UEIBLaster setting for 616
I/UEI.SmartControl( 7902): Setting serial record hearder size = 2
I/UEI.SmartControl( 7902): configuring settings for MAXQ616
I/UEI.SmartControl( 7902): Get version...
D/UEI.SmartControl( 7902): serial port data available: 21
,D/UEI.SmartControl( 7902): MAXQ616 A2-X4 software.
I/UEI.SmartControl( 7902): IR Blaster version: 256702256704300002
I/UEI.SmartControl( 7902): QS saving settings...
D/UEI.SmartControl( 7902): IR Blaster version: 25672567
,D/UEI.SmartControl( 7902): serial port data available: 4
,W/ContextImpl( 7902): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
,I/UEI.SmartControl( 7902): Device manager: loading config....
D/UEI.SmartControl( 7902): ----------- loading internal config...
E/UEI.SmartControl( 7902): Services init done
D/UEI.SmartControl( 7902): QS Service init finished
D/UEI.SmartControl( 7902): QS Service version name: 2.1.91
D/UEI.SmartControl( 7902): QS Service version code: 201091
D/UEI.SmartControl( 7902): Service requested: Control
E/UEI.SmartControl( 7902): Loading SETTINGS...
,D/UEI.SmartControl( 7902): Request IControl service: devices are loaded...
I/ActivityManager( 1031): Killing 5995:com.lge.qremote/u0a112 (adj 15): empty #17
D/UEI.SmartControl( 7902): -- Open brand translation xml: brands_translations_ko
,I/UEI.SmartControl( 7902): Notify AllClients services are ready: 0
D/UEI.SmartControl( 7902): -----service ready thread exits
,W/libprocessgroup( 1031): failed to open /acct/uid_10112/pid_5995/cgroup.procs: No such file or directory
,D/UEI.SmartControl( 7902): Internal service binding...
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1865543033] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:9] from screen [on:0 period:-1865543024] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1865540002] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-1865539992] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
D/serial_port( 7902): close(fd = 25)
,I/UEI.SmartControl( 7902): Serial port is closed.
D/UEI.SmartControl( 7902): Internal timer expired: 1
,D/UEI.SmartControl( 7902): unbind internal service
D/UEI.SmartControl( 7902): Service.onUnbind: IControl
,D/UEI.SmartControl( 7902): Service.onDestroy
D/UEI.SmartControl( 7902): Lock is in USE false
D/UEI.SmartControl( 7902): unbind internal service
W/System.err( 7902): java.lang.IllegalArgumentException: Service not registered: com.uei.control.g@1ec9709
W/System.err( 7902): 	at android.app.LoadedApk.forgetServiceDispatcher(LoadedApk.java:1119)
W/System.err( 7902): 	at android.app.ContextImpl.unbindService(ContextImpl.java:1873)
W/System.err( 7902): 	at android.content.ContextWrapper.unbindService(ContextWrapper.java:550)
W/System.err( 7902): 	at com.uei.control.Service.c(Unknown Source)
W/System.err( 7902): 	at com.uei.control.Service.onDestroy(Unknown Source)
W/System.err( 7902): 	at android.app.ActivityThread.handleStopService(ActivityThread.java:2901)
W/System.err( 7902): 	at android.app.ActivityThread.access$2200(ActivityThread.java:148)
W/System.err( 7902): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1386)
W/System.err( 7902): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 7902): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 7902): 	at android.app.ActivityThread.main(ActivityThread.java:5274)
W/System.err( 7902): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 7902): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 7902): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
W/System.err( 7902): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
E/UEI.SmartControl( 7902): java.lang.IllegalArgumentException: Service not registered: com.uei.control.g@1ec9709
I/UEI.SmartControl( 7902): Serial port is closed.
I/UEI.SmartControl( 7902): Serial port is closed.
D/UEI.SmartControl( 7902): Blaster closed
D/UEI.SmartControl( 7902): Shut down QS...
D/UEI.SmartControl( 7902): Stopping QS lib
D/UEI.SmartControl( 7902): QS lib stop result = true
D/UEI.SmartControl( 7902): Stopped QS lib
D/UEI.SmartControl( 7902): Stopped file observer...
D/UEI.SmartControl( 7902): QS shutdown complete
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1865536969] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1865536966] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,D/sensors_hal_Time( 1031): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1031): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1031): tsOffsetIs: Apps: 1175562499348; DSPS: 38661908; Offset : -4322590350
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1865533939] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1865533936] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=1.0, 0.0, 0.0  rx=0.5 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1865530910] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=1.0, 0.0, 0.0  rx=0.5 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1865530907] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.3 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1865527881] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.3 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1865527878] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.3, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1865524853] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.3, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1865524850] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,V/AlarmManager( 1031): ELAPSED_WAKEUP set : Alarm{5471f7d type 2 when 1188116 com.android.bluetooth} when 1188116
,W/bt-smp  ( 6236): Key(LSB ~ MSB) = 0a 3c a6 fe eb 17 6a 79 a6 1f 0a 0b f9 50 a0 5f 
W/bt-smp  ( 6236): Plain text(LSB ~ MSB) = 07 86 45 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 6236): Encrypted text(LSB ~ MSB) = 21 4b 0c 94 6d 1c 75 a2 9c 88 0d d6 94 30 20 15 
W/bt-btm  ( 6236): Stopping oneshot timer
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1865521824] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-1865521814] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1865518791] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1865518788] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,D/sensors_hal_Time( 1031): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1031): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1031): tsOffsetIs: Apps: 1195564691007; DSPS: 39317340; Offset : -4322595983
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1865515760] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1865515757] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1865512732] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1865512729] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1865509704] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-1865509694] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=1.0, 0.0, 0.0  rx=0.5 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1865506680] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=1.0, 0.0, 0.0  rx=0.5 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1865506677] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.3 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1865503650] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.3 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1865503647] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.3, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1865500616] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.3, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:9] from screen [on:0 period:-1865500607] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3000] from screen [on:0 period:-1865497588] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1865497585] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,D/sensors_hal_Time( 1031): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1031): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1031): tsOffsetIs: Apps: 1215566608499; DSPS: 39972763; Offset : -4322601072
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3000] from screen [on:0 period:-1865494558] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1865494555] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1865491528] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1865491525] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,I/UsageStatsService( 1031): User[0] Flushing usage stats to disk
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1865488498] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1865488495] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,I/[SystemUI]TimeTickManager( 1473): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1473): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1473): called onTimeUpdated()
I/[SystemUI]Clock( 1473): called onTimeUpdated()
I/LgeClockWidgetControlView( 1473): called onTimeUpdated()
I/[SystemUI]DateView( 1473): called onTimeUpdated()
I/[SystemUI]DateView( 1473): called onTimeUpdated()
,D/KeyguardUpdateMonitor( 1473): handleTimeUpdate
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3007] from screen [on:0 period:-1865485463] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:11] from screen [on:0 period:-1865485452] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=1.0, 0.0, 0.0  rx=0.5 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1865482436] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=1.0, 0.0, 0.0  rx=0.5 bcn=0 [on:0 tx:0 rx:0 period:9] from screen [on:0 period:-1865482427] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.3 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1865479405] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.3 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-1865479395] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.3, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1865476372] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.3, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1865476369] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,D/sensors_hal_Time( 1031): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1031): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1031): tsOffsetIs: Apps: 1235568569012; DSPS: 40628187; Offset : -4322593762
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1865473344] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:9] from screen [on:0 period:-1865473335] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1865470314] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-1865470304] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1865467281] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1865467278] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1865464255] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:9] from screen [on:0 period:-1865464246] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1865461223] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1865461220] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=1.0, 0.0, 0.0  rx=0.5 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1865458200] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=1.0, 0.0, 0.0  rx=0.5 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1865458197] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,D/sensors_hal_Time( 1031): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1031): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1031): tsOffsetIs: Apps: 1255570809526; DSPS: 41283620; Offset : -4322581006
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.3 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1865455172] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.3 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1865455169] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.3, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1865452145] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.3, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-1865452135] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1865449115] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-1865449105] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1865446083] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1865446080] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1865443054] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:11] from screen [on:0 period:-1865443043] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
I/[SystemUI]LGPowerUI( 1473): onReceive = com.lge.android.intent.action.BATTERYEX
,I/[SystemUI]LGPowerUI( 1473): On Skip Timer : true
D/WifiController( 1031): battery changed pluggedType: 2
,D/LEDHandler( 1964): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1964): Battery Level Remaining: 100%
D/LEDHandler( 1964): Battery Temp: 278, mChargingStatus=5, mChargingStop=false
D/KeyguardUpdateMonitor( 1473): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 278
I/[SystemUI]LGPowerUI( 1473): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings( 1031): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1031): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/HeadsetStateMachine( 6236): Disconnected process message: 10, size: 0
I/[SystemUI]BatterySaverHandler( 1473): onReceive = android.intent.action.BATTERY_CHANGED
D/LGDMClient( 3985): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.intent.action.BATTERY_CHANGED
D/LGDMClient( 3985): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1865440022] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1865440019] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1865436997] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1865436994] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,D/sensors_hal_Time( 1031): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1031): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1031): tsOffsetIs: Apps: 1275572973424; DSPS: 41939051; Offset : -4322583907
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1865433969] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1865433966] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=1.0, 0.0, 0.0  rx=0.5 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1865430940] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=1.0, 0.0, 0.0  rx=0.5 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1865430937] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.3 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1865427915] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.3 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-1865427905] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
I/[SystemUI]TimeTickManager( 1473): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1473): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1473): called onTimeUpdated()
I/[SystemUI]Clock( 1473): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1473): called onTimeUpdated()
I/[SystemUI]DateView( 1473): called onTimeUpdated()
I/[SystemUI]DateView( 1473): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1473): handleTimeUpdate
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.3, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1865424884] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.3, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-1865424874] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1865421862] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1865421859] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1865418833] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1865418830] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,D/sensors_hal_Time( 1031): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1031): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1031): tsOffsetIs: Apps: 1295575172427; DSPS: 42594483; Offset : -4322581911
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1865415804] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-1865415794] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1865412775] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-1865412765] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1865409744] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:12] from screen [on:0 period:-1865409732] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=1.0, 0.0, 0.0  rx=0.5 bcn=0 [on:0 tx:0 rx:0 period:2999] from screen [on:0 period:-1865406713] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=1.0, 0.0, 0.0  rx=0.5 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1865406710] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.3 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1865403682] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.3 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1865403679] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.3, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1865400653] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.3, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1865400650] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1865397624] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:4] from screen [on:0 period:-1865397620] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,D/sensors_hal_Time( 1031): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1031): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1031): tsOffsetIs: Apps: 1315577089034; DSPS: 43249906; Offset : -4322588118
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1865394595] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:9] from screen [on:0 period:-1865394586] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1865391566] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:9] from screen [on:0 period:-1865391557] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1865388537] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1865388534] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1865385507] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-1865385497] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=1.0, 0.0, 0.0  rx=0.5 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1865382476] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=1.0, 0.0, 0.0  rx=0.5 bcn=0 [on:0 tx:0 rx:0 period:9] from screen [on:0 period:-1865382467] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.3 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1865379445] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.3 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-1865379435] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
D/PowerManagerServiceEx( 1031): acquireWakeLockInternal: lock=538279423, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1031
,V/AlarmManager( 1031): ELAPSED_WAKEUP set : Alarm{28eae72 type 2 when 1334121 android} when 1334121
D/[Concierge]Service( 2627): onStartCommand(). Type : 9
,D/PowerManagerServiceEx( 1031): releaseWakeLockInternal: lock=538279423 [*alarm*], flags=0x0
,I/BooksSync( 6604): Starting books sync
,D/BooksSync( 6604): started syncMyEbooks
,V/GLSActivity( 2129): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2129): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2129): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 2129): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2129): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2129): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1031): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1031): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1031): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1031): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1031): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1415): onNotificationPosted
D/SmartCoverUpdateMonitor( 1415): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1415): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1415): handleNotificationPosted(true)
D/QuickCircle( 1415): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1415): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1415): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
,D/LgeQuickCoverNotificationData( 1415): post do just update job
W/GLSActivity( 2129): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2129): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2129): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2129): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2129): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2129): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2129): 	at android.os.Binder.execTransact(Binder.java:446)
D/LgeQuickCoverNotificationData( 1415): showAll3
D/LgeQuickCoverNotificationData( 1415): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1415): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1415): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1415): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1415): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1415): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1415): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1415): isNotificationForCurrentUser : true
,D/LgeQuickCoverOverlayWindow( 1415): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1415): isNotificationForCurrentUser : true
E/BooksAccountManager( 6604): Authentication error
E/BooksAccountManager( 6604): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6604): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6604): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6604): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6604): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6604): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6604): null auth token
E/LgeQuickCoverOverlayWindow( 1415): updateNotificationData: count=3
D/libc-netbsd(  323): default dns: query_ipv6=0, query_ipv4=1
,D/libc-netbsd(  323): res_queryN name = www.googleapis.com, class = 1, type = 1
D/QuickStatusbarLayout( 1415): Notification difference=198
D/QuickStatusbarLayout( 1415): child = android.widget.LinearLayout{9d5fc15 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,D/libc-netbsd(  323): res_queryN name = www.googleapis.com succeed
,W/ApiaryClient( 6604): Error response from books API: {
W/ApiaryClient( 6604):  "error": {
W/ApiaryClient( 6604):   "errors": [
W/ApiaryClient( 6604):    {
W/ApiaryClient( 6604):     "domain": "global",
W/ApiaryClient( 6604):     "reason": "required",
W/ApiaryClient( 6604):     "message": "Login Required",
W/ApiaryClient( 6604):     "locationType": "header",
W/ApiaryClient( 6604):     "location": "Authorization"
W/ApiaryClient( 6604):    }
W/ApiaryClient( 6604):   ],
W/ApiaryClient( 6604):   "code": 401,
W/ApiaryClient( 6604):   "message": "Login Required"
W/ApiaryClient( 6604):  }
W/ApiaryClient( 6604): }
,W/ApiaryClient( 6604): errCount = 1: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6604): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-4196568711975012170&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6604): Headers:
W/ApiaryClient( 6604): accept-encoding: [gzip]
W/ApiaryClient( 6604): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6604): gdata-version: 2
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.3, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1865376422] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.3, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:2] from screen [on:0 period:-1865376420] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,D/sensors_hal_Time( 1031): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1031): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1031): tsOffsetIs: Apps: 1335579210589; DSPS: 43905336; Offset : -4322602664
,V/GLSActivity( 2129): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2129): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2129): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2129): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 2129): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2129): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1031): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1031): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1031): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1031): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1031): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1415): onNotificationPosted
,D/SmartCoverUpdateMonitor( 1415): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1415): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1415): handleNotificationPosted(true)
D/QuickCircle( 1415): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1415): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1415): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1415): post do just update job
D/LgeQuickCoverNotificationData( 1415): showAll3
D/LgeQuickCoverNotificationData( 1415): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1415): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1415): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1415): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1415): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1415): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1415): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1415): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1415): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1415): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1415): updateNotificationData: count=3
W/GLSActivity( 2129): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2129): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2129): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2129): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2129): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2129): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2129): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 6604): Authentication error
E/BooksAccountManager( 6604): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6604): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6604): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6604): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6604): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6604): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6604): null auth token
D/QuickStatusbarLayout( 1415): Notification difference=198
D/QuickStatusbarLayout( 1415): child = android.widget.LinearLayout{9d5fc15 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,W/ApiaryClient( 6604): Error response from books API: {
W/ApiaryClient( 6604):  "error": {
W/ApiaryClient( 6604):   "errors": [
W/ApiaryClient( 6604):    {
W/ApiaryClient( 6604):     "domain": "global",
W/ApiaryClient( 6604):     "reason": "required",
W/ApiaryClient( 6604):     "message": "Login Required",
W/ApiaryClient( 6604):     "locationType": "header",
W/ApiaryClient( 6604):     "location": "Authorization"
W/ApiaryClient( 6604):    }
W/ApiaryClient( 6604):   ],
W/ApiaryClient( 6604):   "code": 401,
W/ApiaryClient( 6604):   "message": "Login Required"
W/ApiaryClient( 6604):  }
W/ApiaryClient( 6604): }
,W/ApiaryClient( 6604): errCount = 2: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6604): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-4196568711975012170&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6604): Headers:
W/ApiaryClient( 6604): accept-encoding: [gzip]
W/ApiaryClient( 6604): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6604): gdata-version: 2
V/GLSActivity( 2129): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2129): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2129): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2129): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 2129): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2129): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1031): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1031): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1031): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1031): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1031): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1415): onNotificationPosted
,D/SmartCoverUpdateMonitor( 1415): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1415): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1415): handleNotificationPosted(true)
D/QuickCircle( 1415): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1415): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1415): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1415): post do just update job
D/LgeQuickCoverNotificationData( 1415): showAll3
D/LgeQuickCoverNotificationData( 1415): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1415): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1415): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1415): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1415): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1415): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1415): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1415): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1415): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1415): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1415): updateNotificationData: count=3
,W/GLSActivity( 2129): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2129): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2129): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2129): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2129): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2129): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2129): 	at android.os.Binder.execTransact(Binder.java:446)
E/BooksAccountManager( 6604): Authentication error
E/BooksAccountManager( 6604): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6604): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6604): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6604): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6604): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6604): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6604): null auth token
D/QuickStatusbarLayout( 1415): Notification difference=198
D/QuickStatusbarLayout( 1415): child = android.widget.LinearLayout{9d5fc15 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,W/ApiaryClient( 6604): Error response from books API: {
W/ApiaryClient( 6604):  "error": {
W/ApiaryClient( 6604):   "errors": [
W/ApiaryClient( 6604):    {
W/ApiaryClient( 6604):     "domain": "global",
W/ApiaryClient( 6604):     "reason": "required",
W/ApiaryClient( 6604):     "message": "Login Required",
W/ApiaryClient( 6604):     "locationType": "header",
W/ApiaryClient( 6604):     "location": "Authorization"
W/ApiaryClient( 6604):    }
W/ApiaryClient( 6604):   ],
W/ApiaryClient( 6604):   "code": 401,
W/ApiaryClient( 6604):   "message": "Login Required"
W/ApiaryClient( 6604):  }
W/ApiaryClient( 6604): }
,W/ApiaryClient( 6604): errCount = 3: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6604): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-4196568711975012170&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6604): Headers:
W/ApiaryClient( 6604): accept-encoding: [gzip]
W/ApiaryClient( 6604): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6604): gdata-version: 2
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=6.1, 0.0, 0.0  rx=4.6 bcn=0 [on:0 tx:0 rx:0 period:3005] from screen [on:0 period:-1865373405] gl rssi=-48 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=6.1, 0.0, 0.0  rx=4.6 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-1865373395] gl rssi=-48 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
E/BooksSync( 6604): Soft error: 
E/BooksSync( 6604): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 6604): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-4196568711975012170&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 6604): Headers:
E/BooksSync( 6604): accept-encoding: [gzip]
E/BooksSync( 6604): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 6604): gdata-version: 2
E/BooksSync( 6604): 
E/BooksSync( 6604): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 6604): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 6604): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 6604): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 6604): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 6604): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 6604): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 6604): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 6604): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 6604): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 6604): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 6604): {
E/BooksSync( 6604):  "error": {
E/BooksSync( 6604):   "errors": [
E/BooksSync( 6604):    {
E/BooksSync( 6604):     "domain": "global",
E/BooksSync( 6604):     "reason": "required",
E/BooksSync( 6604):     "message": "Login Required",
E/BooksSync( 6604):     "locationType": "header",
E/BooksSync( 6604):     "location": "Authorization"
E/BooksSync( 6604):    }
E/BooksSync( 6604):   ],
E/BooksSync( 6604):   "code": 401,
E/BooksSync( 6604):   "message": "Login Required"
E/BooksSync( 6604):  }
E/BooksSync( 6604): }
E/BooksSync( 6604): 
E/BooksSync( 6604): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 6604): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 6604): 	... 8 more
,E/BooksSync( 6604): Sync error
E/BooksSync( 6604): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 6604): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-4196568711975012170&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 6604): Headers:
E/BooksSync( 6604): accept-encoding: [gzip]
E/BooksSync( 6604): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 6604): gdata-version: 2
E/BooksSync( 6604): 
E/BooksSync( 6604): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 6604): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 6604): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 6604): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 6604): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 6604): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 6604): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 6604): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 6604): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 6604): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 6604): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 6604): {
E/BooksSync( 6604):  "error": {
E/BooksSync( 6604):   "errors": [
E/BooksSync( 6604):    {
E/BooksSync( 6604):     "domain": "global",
E/BooksSync( 6604):     "reason": "required",
E/BooksSync( 6604):     "message": "Login Required",
E/BooksSync( 6604):     "locationType": "header",
E/BooksSync( 6604):     "location": "Authorization"
E/BooksSync( 6604):    }
E/BooksSync( 6604):   ],
E/BooksSync( 6604):   "code": 401,
E/BooksSync( 6604):   "message": "Login Required"
E/BooksSync( 6604):  }
E/BooksSync( 6604): }
E/BooksSync( 6604): 
E/BooksSync( 6604): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 6604): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 6604): 	... 8 more
I/BooksSync( 6604): Finished books sync
D/SyncManager( 1031): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 1334121, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=7.1, 0.0, 0.0  rx=4.3 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1865370382] gl rssi=-48 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=7.1, 0.0, 0.0  rx=4.3 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1865370379] gl rssi=-48 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=3.5, 0.0, 0.0  rx=2.1 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1865367352] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=3.5, 0.0, 0.0  rx=2.1 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1865367349] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,I/[SystemUI]TimeTickManager( 1473): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1473): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1473): called onTimeUpdated()
I/[SystemUI]Clock( 1473): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1473): called onTimeUpdated()
I/[SystemUI]DateView( 1473): called onTimeUpdated()
I/[SystemUI]DateView( 1473): called onTimeUpdated()
,D/KeyguardUpdateMonitor( 1473): handleTimeUpdate
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=2.3, 0.0, 0.0  rx=1.1 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1865364323] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=2.3, 0.0, 0.0  rx=1.1 bcn=0 [on:0 tx:0 rx:0 period:11] from screen [on:0 period:-1865364312] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=1.1, 0.0, 0.0  rx=0.5 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1865361291] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=1.1, 0.0, 0.0  rx=0.5 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1865361288] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=1.1, 0.0, 0.0  rx=0.3 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1865358260] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=1.1, 0.0, 0.0  rx=0.3 bcn=0 [on:0 tx:0 rx:0 period:4] from screen [on:0 period:-1865358256] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,D/sensors_hal_Time( 1031): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1031): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1031): tsOffsetIs: Apps: 1355581111050; DSPS: 44560758; Offset : -4322594346
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=1.5, 0.0, 0.0  rx=0.6 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1865355230] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=1.5, 0.0, 0.0  rx=0.6 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1865355227] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.3 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1865352201] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.3 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1865352198] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.2 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1865349172] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.2 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1865349169] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,D/PowerManagerServiceEx( 1031): acquireWakeLockInternal: lock=538279423, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1031
,V/AlarmManager( 1031): ELAPSED_WAKEUP set : Alarm{24132bcc type 2 when 1364580 android} when 1364580
D/[Concierge]Service( 2627): onStartCommand(). Type : 9
,D/PowerManagerServiceEx( 1031): releaseWakeLockInternal: lock=538279423 [*alarm*], flags=0x0
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.2, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1865346144] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.2, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:11] from screen [on:0 period:-1865346133] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1865343110] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1865343107] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1865340080] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1865340077] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.3, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1865337050] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.3, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1865337047] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,D/sensors_hal_Time( 1031): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1031): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1031): tsOffsetIs: Apps: 1375584106667; DSPS: 45216216; Offset : -4322589372
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1865334022] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1865334019] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=1.1, 0.0, 0.0  rx=0.5 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1865330993] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=1.1, 0.0, 0.0  rx=0.5 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1865330990] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.3 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1865327964] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.3 bcn=0 [on:0 tx:0 rx:0 period:9] from screen [on:0 period:-1865327955] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.3, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1865324934] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.3, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-1865324924] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1865321902] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:4] from screen [on:0 period:-1865321898] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1865318871] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1865318868] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,D/sensors_hal_Time( 1031): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1031): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1031): tsOffsetIs: Apps: 1395586342962; DSPS: 45871649; Offset : -4322581148
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1865315841] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1865315838] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1865312811] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1865312808] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3000] from screen [on:0 period:-1865309784] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:11] from screen [on:0 period:-1865309773] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=1.3, 0.0, 0.0  rx=0.5 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1865306752] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=1.3, 0.0, 0.0  rx=0.5 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1865306749] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,I/[SystemUI]TimeTickManager( 1473): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1473): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1473): called onTimeUpdated()
I/[SystemUI]Clock( 1473): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1473): called onTimeUpdated()
I/[SystemUI]DateView( 1473): called onTimeUpdated()
I/[SystemUI]DateView( 1473): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1473): handleTimeUpdate
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-47 f=2412 sc=60 link=72 tx=0.6, 0.0, 0.0  rx=0.3 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1865303722] gl rssi=-47 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-47 f=2412 sc=60 link=72 tx=0.6, 0.0, 0.0  rx=0.3 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1865303719] gl rssi=-47 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-47 f=2412 sc=60 link=72 tx=0.3, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1865300692] gl rssi=-47 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-47 f=2412 sc=60 link=72 tx=0.3, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1865300689] gl rssi=-47 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-47 f=2412 sc=60 link=72 tx=0.2, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3000] from screen [on:0 period:-1865297665] gl rssi=-47 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-47 f=2412 sc=60 link=72 tx=0.2, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-1865297655] gl rssi=-47 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
D/sensors_hal_Time( 1031): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1031): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1031): tsOffsetIs: Apps: 1415588041079; DSPS: 46527065; Offset : -4322591703
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-47 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1865294635] gl rssi=-47 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-47 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-1865294625] gl rssi=-47 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-47 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3000] from screen [on:0 period:-1865291605] gl rssi=-47 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-47 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:12] from screen [on:0 period:-1865291593] gl rssi=-47 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-47 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1865288572] gl rssi=-47 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-47 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1865288569] gl rssi=-47 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-47 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1865285542] gl rssi=-47 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-47 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1865285539] gl rssi=-47 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-47 f=2412 sc=60 link=72 tx=1.0, 0.0, 0.0  rx=0.5 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1865282521] gl rssi=-47 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-47 f=2412 sc=60 link=72 tx=1.0, 0.0, 0.0  rx=0.5 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1865282518] gl rssi=-47 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-47 f=2412 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.3 bcn=0 [on:0 tx:0 rx:0 period:3000] from screen [on:0 period:-1865279494] gl rssi=-47 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-47 f=2412 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.3 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-1865279484] gl rssi=-47 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-47 f=2412 sc=60 link=72 tx=0.3, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1865276461] gl rssi=-47 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-47 f=2412 sc=60 link=72 tx=0.3, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1865276458] gl rssi=-47 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,D/sensors_hal_Time( 1031): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1031): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1031): tsOffsetIs: Apps: 1435590356593; DSPS: 47182501; Offset : -4322595524
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-47 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1865273432] gl rssi=-47 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-47 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1865273429] gl rssi=-47 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-47 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3000] from screen [on:0 period:-1865270402] gl rssi=-47 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-47 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1865270399] gl rssi=-47 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-47 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1865267372] gl rssi=-47 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-47 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1865267369] gl rssi=-47 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-47 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1865264342] gl rssi=-47 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-47 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1865264339] gl rssi=-47 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-47 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1865261313] gl rssi=-47 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-47 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-1865261303] gl rssi=-47 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-47 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1865258280] gl rssi=-47 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-47 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1865258277] gl rssi=-47 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,D/sensors_hal_Time( 1031): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1031): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1031): tsOffsetIs: Apps: 1455592584710; DSPS: 47837934; Offset : -4322595451
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-47 f=2412 sc=60 link=72 tx=1.0, 0.0, 0.0  rx=0.5 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1865255249] gl rssi=-47 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-47 f=2412 sc=60 link=72 tx=1.0, 0.0, 0.0  rx=0.5 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1865255246] gl rssi=-47 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-47 f=2412 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.3 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1865252220] gl rssi=-47 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-47 f=2412 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.3 bcn=0 [on:0 tx:0 rx:0 period:9] from screen [on:0 period:-1865252211] gl rssi=-47 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-47 f=2412 sc=60 link=72 tx=0.3, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1865249191] gl rssi=-47 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-47 f=2412 sc=60 link=72 tx=0.3, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1865249188] gl rssi=-47 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-47 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1865246161] gl rssi=-47 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-47 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1865246158] gl rssi=-47 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,I/[SystemUI]TimeTickManager( 1473): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1473): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1473): called onTimeUpdated()
I/[SystemUI]Clock( 1473): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1473): called onTimeUpdated()
I/[SystemUI]DateView( 1473): called onTimeUpdated()
I/[SystemUI]DateView( 1473): called onTimeUpdated()
,D/KeyguardUpdateMonitor( 1473): handleTimeUpdate
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-47 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1865243131] gl rssi=-47 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-47 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1865243128] gl rssi=-47 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-47 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1865240103] gl rssi=-47 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-47 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1865240100] gl rssi=-47 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-47 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1865237075] gl rssi=-47 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-47 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:9] from screen [on:0 period:-1865237066] gl rssi=-47 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
D/sensors_hal_Time( 1031): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1031): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1031): tsOffsetIs: Apps: 1475595536629; DSPS: 48493391; Offset : -4322603762
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-47 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3000] from screen [on:0 period:-1865234045] gl rssi=-47 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-47 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-1865234035] gl rssi=-47 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-47 f=2412 sc=60 link=72 tx=1.0, 0.0, 0.0  rx=0.5 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1865231014] gl rssi=-47 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-47 f=2412 sc=60 link=72 tx=1.0, 0.0, 0.0  rx=0.5 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-1865231004] gl rssi=-47 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-47 f=2412 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.3 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1865227982] gl rssi=-47 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-47 f=2412 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.3 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1865227979] gl rssi=-47 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-47 f=2412 sc=60 link=72 tx=0.3, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3000] from screen [on:0 period:-1865224954] gl rssi=-47 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-47 f=2412 sc=60 link=72 tx=0.3, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:4] from screen [on:0 period:-1865224950] gl rssi=-47 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-47 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1865221924] gl rssi=-47 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-47 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-1865221914] gl rssi=-47 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-47 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1865218892] gl rssi=-47 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-47 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-1865218891] gl rssi=-47 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,D/sensors_hal_Time( 1031): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1031): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1031): tsOffsetIs: Apps: 1495597746413; DSPS: 49148823; Offset : -4322591271
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-47 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:-1865215871] gl rssi=-47 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-47 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1865215868] gl rssi=-47 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1865212844] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-1865212834] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-47 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1865209812] gl rssi=-47 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-47 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1865209809] gl rssi=-47 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-47 f=2412 sc=60 link=72 tx=1.0, 0.0, 0.0  rx=0.5 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1865206784] gl rssi=-47 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-47 f=2412 sc=60 link=72 tx=1.0, 0.0, 0.0  rx=0.5 bcn=0 [on:0 tx:0 rx:0 period:4] from screen [on:0 period:-1865206780] gl rssi=-47 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-47 f=2412 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.3 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1865203755] gl rssi=-47 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-47 f=2412 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.3 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-1865203745] gl rssi=-47 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-47 f=2412 sc=60 link=72 tx=0.3, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1865200725] gl rssi=-47 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-47 f=2412 sc=60 link=72 tx=0.3, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:11] from screen [on:0 period:-1865200714] gl rssi=-47 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-47 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:-1865197695] gl rssi=-47 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-47 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:11] from screen [on:0 period:-1865197684] gl rssi=-47 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
D/sensors_hal_Time( 1031): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1031): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1031): tsOffsetIs: Apps: 1515599652916; DSPS: 49804246; Offset : -4322607400
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-47 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1865194663] gl rssi=-47 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-47 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:9] from screen [on:0 period:-1865194654] gl rssi=-47 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-47 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3005] from screen [on:0 period:-1865191627] gl rssi=-47 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-47 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1865191624] gl rssi=-47 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-47 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1865188600] gl rssi=-47 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-47 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1865188597] gl rssi=-47 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,I/[SystemUI]TimeTickManager( 1473): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1473): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1473): called onTimeUpdated()
I/[SystemUI]Clock( 1473): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1473): called onTimeUpdated()
I/[SystemUI]DateView( 1473): called onTimeUpdated()
I/[SystemUI]DateView( 1473): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1473): handleTimeUpdate
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-47 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1865185570] gl rssi=-47 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-47 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1865185567] gl rssi=-47 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-47 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1865182541] gl rssi=-47 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-47 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1865182538] gl rssi=-47 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-47 f=2412 sc=60 link=72 tx=1.0, 0.0, 0.0  rx=0.5 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1865179513] gl rssi=-47 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-47 f=2412 sc=60 link=72 tx=1.0, 0.0, 0.0  rx=0.5 bcn=0 [on:0 tx:0 rx:0 period:4] from screen [on:0 period:-1865179509] gl rssi=-47 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-47 f=2412 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.3 bcn=0 [on:0 tx:0 rx:0 period:2999] from screen [on:0 period:-1865176493] gl rssi=-47 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-47 f=2412 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.3 bcn=0 [on:0 tx:0 rx:0 period:4] from screen [on:0 period:-1865176489] gl rssi=-47 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,D/sensors_hal_Time( 1031): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1031): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1031): tsOffsetIs: Apps: 1535601588221; DSPS: 50459669; Offset : -4322594677
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-47 f=2412 sc=60 link=72 tx=0.3, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1865173464] gl rssi=-47 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-47 f=2412 sc=60 link=72 tx=0.3, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-1865173454] gl rssi=-47 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-47 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1865170432] gl rssi=-47 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-47 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1865170429] gl rssi=-47 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1865167402] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1865167399] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1865164373] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1865164370] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1865161345] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:9] from screen [on:0 period:-1865161336] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1865158315] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:11] from screen [on:0 period:-1865158304] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
D/sensors_hal_Time( 1031): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1031): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1031): tsOffsetIs: Apps: 1555603814308; DSPS: 51115102; Offset : -4322596166
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=1.0, 0.0, 0.0  rx=0.5 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1865155283] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=1.0, 0.0, 0.0  rx=0.5 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1865155280] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.3 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1865152253] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.3 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1865152250] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.3, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1865149224] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.3, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-1865149214] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1865146192] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1865146189] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1865143162] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1865143159] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1865140132] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1865140129] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1865137101] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1865137098] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,D/sensors_hal_Time( 1031): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1031): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1031): tsOffsetIs: Apps: 1575606066018; DSPS: 51770536; Offset : -4322602756
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1865134071] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1865134068] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=1.0, 0.0, 0.0  rx=0.5 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1865131045] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=1.0, 0.0, 0.0  rx=0.5 bcn=0 [on:0 tx:0 rx:0 period:9] from screen [on:0 period:-1865131036] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=2.5, 0.0, 0.0  rx=2.8 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1865128015] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=2.5, 0.0, 0.0  rx=2.8 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-1865128005] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
I/[SystemUI]TimeTickManager( 1473): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1473): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1473): called onTimeUpdated()
I/[SystemUI]Clock( 1473): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1473): called onTimeUpdated()
I/[SystemUI]DateView( 1473): called onTimeUpdated()
I/[SystemUI]DateView( 1473): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1473): handleTimeUpdate
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=1.3, 0.0, 0.0  rx=1.4 bcn=0 [on:0 tx:0 rx:0 period:3000] from screen [on:0 period:-1865124985] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=1.3, 0.0, 0.0  rx=1.4 bcn=0 [on:0 tx:0 rx:0 period:9] from screen [on:0 period:-1865124976] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.6, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1865121954] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.6, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:11] from screen [on:0 period:-1865121943] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-47 f=2412 sc=60 link=72 tx=0.3, 0.0, 0.0  rx=0.3 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1865118922] gl rssi=-47 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-47 f=2412 sc=60 link=72 tx=0.3, 0.0, 0.0  rx=0.3 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1865118919] gl rssi=-47 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,D/sensors_hal_Time( 1031): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1031): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1031): tsOffsetIs: Apps: 1595608031062; DSPS: 52425960; Offset : -4322590915
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-47 f=2412 sc=60 link=72 tx=0.2, 0.0, 0.0  rx=0.2 bcn=0 [on:0 tx:0 rx:0 period:3000] from screen [on:0 period:-1865115894] gl rssi=-47 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-47 f=2412 sc=60 link=72 tx=0.2, 0.0, 0.0  rx=0.2 bcn=0 [on:0 tx:0 rx:0 period:9] from screen [on:0 period:-1865115885] gl rssi=-47 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-47 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3000] from screen [on:0 period:-1865112865] gl rssi=-47 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-47 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:11] from screen [on:0 period:-1865112854] gl rssi=-47 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-47 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1865109831] gl rssi=-47 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-47 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1865109828] gl rssi=-47 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-47 f=2412 sc=60 link=72 tx=1.0, 0.0, 0.0  rx=0.5 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1865106808] gl rssi=-47 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-47 f=2412 sc=60 link=72 tx=1.0, 0.0, 0.0  rx=0.5 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1865106805] gl rssi=-47 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-47 f=2412 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.3 bcn=0 [on:0 tx:0 rx:0 period:3000] from screen [on:0 period:-1865103780] gl rssi=-47 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-47 f=2412 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.3 bcn=0 [on:0 tx:0 rx:0 period:4] from screen [on:0 period:-1865103776] gl rssi=-47 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-47 f=2412 sc=60 link=72 tx=0.3, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1865100750] gl rssi=-47 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-47 f=2412 sc=60 link=72 tx=0.3, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1865100747] gl rssi=-47 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-47 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1865097721] gl rssi=-47 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-47 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1865097718] gl rssi=-47 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,D/sensors_hal_Time( 1031): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1031): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1031): tsOffsetIs: Apps: 1615610301681; DSPS: 53081395; Offset : -4322609037
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-47 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:-1865094690] gl rssi=-47 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-47 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:4] from screen [on:0 period:-1865094686] gl rssi=-47 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-47 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1865091660] gl rssi=-47 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-47 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:4] from screen [on:0 period:-1865091656] gl rssi=-47 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-47 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:2999] from screen [on:0 period:-1865088629] gl rssi=-47 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-47 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1865088626] gl rssi=-47 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-47 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1865085601] gl rssi=-47 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-47 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1865085598] gl rssi=-47 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-47 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3000] from screen [on:0 period:-1865082572] gl rssi=-47 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-47 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1865082569] gl rssi=-47 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-47 f=2412 sc=60 link=72 tx=1.0, 0.0, 0.0  rx=0.5 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1865079542] gl rssi=-47 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-47 f=2412 sc=60 link=72 tx=1.0, 0.0, 0.0  rx=0.5 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1865079539] gl rssi=-47 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-47 f=2412 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.3 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1865076521] gl rssi=-47 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-47 f=2412 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.3 bcn=0 [on:0 tx:0 rx:0 period:4] from screen [on:0 period:-1865076517] gl rssi=-47 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,D/sensors_hal_Time( 1031): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1031): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1031): tsOffsetIs: Apps: 1635612286464; DSPS: 53736820; Offset : -4322607714
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-47 f=2412 sc=60 link=72 tx=0.3, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1865073490] gl rssi=-47 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-47 f=2412 sc=60 link=72 tx=0.3, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1865073487] gl rssi=-47 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-47 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1865070461] gl rssi=-47 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-47 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1865070458] gl rssi=-47 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-47 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3000] from screen [on:0 period:-1865067432] gl rssi=-47 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-47 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1865067429] gl rssi=-47 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,I/[SystemUI]TimeTickManager( 1473): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1473): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1473): called onTimeUpdated()
I/[SystemUI]Clock( 1473): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1473): called onTimeUpdated()
I/[SystemUI]DateView( 1473): called onTimeUpdated()
I/[SystemUI]DateView( 1473): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1473): handleTimeUpdate
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-47 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1865064401] gl rssi=-47 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-47 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1865064398] gl rssi=-47 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-47 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1865061370] gl rssi=-47 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-47 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1865061367] gl rssi=-47 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-47 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1865058341] gl rssi=-47 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-47 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1865058338] gl rssi=-47 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,D/sensors_hal_Time( 1031): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1031): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1031): tsOffsetIs: Apps: 1655614181352; DSPS: 54392242; Offset : -4322605201
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-47 f=2412 sc=60 link=72 tx=1.0, 0.0, 0.0  rx=0.5 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1865055310] gl rssi=-47 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-47 f=2412 sc=60 link=72 tx=1.0, 0.0, 0.0  rx=0.5 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1865055307] gl rssi=-47 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-47 f=2412 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.3 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1865052282] gl rssi=-47 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-47 f=2412 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.3 bcn=0 [on:0 tx:0 rx:0 period:4] from screen [on:0 period:-1865052278] gl rssi=-47 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-47 f=2412 sc=60 link=72 tx=0.3, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1865049254] gl rssi=-47 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-47 f=2412 sc=60 link=72 tx=0.3, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:9] from screen [on:0 period:-1865049245] gl rssi=-47 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-47 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1865046222] gl rssi=-47 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-47 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1865046219] gl rssi=-47 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-47 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1865043191] gl rssi=-47 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-47 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1865043188] gl rssi=-47 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-47 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1865040163] gl rssi=-47 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-47 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1865040160] gl rssi=-47 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-47 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1865037134] gl rssi=-47 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-47 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-1865037124] gl rssi=-47 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
D/sensors_hal_Time( 1031): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1031): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1031): tsOffsetIs: Apps: 1675616284730; DSPS: 55047671; Offset : -4322607537
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-47 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1865034104] gl rssi=-47 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-47 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-1865034094] gl rssi=-47 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-47 f=2412 sc=60 link=72 tx=1.0, 0.0, 0.0  rx=0.5 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1865031072] gl rssi=-47 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-47 f=2412 sc=60 link=72 tx=1.0, 0.0, 0.0  rx=0.5 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1865031069] gl rssi=-47 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-47 f=2412 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.3 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1865028041] gl rssi=-47 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-47 f=2412 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.3 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1865028038] gl rssi=-47 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-47 f=2412 sc=60 link=72 tx=0.3, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1865025020] gl rssi=-47 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-47 f=2412 sc=60 link=72 tx=0.3, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1865025017] gl rssi=-47 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-47 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1865021990] gl rssi=-47 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-47 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1865021987] gl rssi=-47 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-47 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1865018961] gl rssi=-47 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-47 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1865018958] gl rssi=-47 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,D/sensors_hal_Time( 1031): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1031): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1031): tsOffsetIs: Apps: 1695618548160; DSPS: 55703105; Offset : -4322602511
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3008] from screen [on:0 period:-1865015926] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:8] from screen [on:0 period:-1865015918] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-47 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1865012900] gl rssi=-47 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-47 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:4] from screen [on:0 period:-1865012896] gl rssi=-47 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1865009869] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1865009866] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,D/PowerManagerServiceEx( 1031): acquireWakeLockInternal: lock=538279423, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1031
,V/AlarmManager( 1031): ELAPSED_WAKEUP set : Alarm{1f49fe15 type 2 when 1704642 android} when 1704642
D/[Concierge]Service( 2627): onStartCommand(). Type : 9
,D/PowerManagerServiceEx( 1031): releaseWakeLockInternal: lock=538279423 [*alarm*], flags=0x0
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-47 f=2412 sc=60 link=72 tx=1.0, 0.0, 0.0  rx=0.5 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1865006847] gl rssi=-47 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-47 f=2412 sc=60 link=72 tx=1.0, 0.0, 0.0  rx=0.5 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1865006844] gl rssi=-47 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
I/[SystemUI]TimeTickManager( 1473): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1473): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1473): called onTimeUpdated()
I/[SystemUI]Clock( 1473): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1473): called onTimeUpdated()
I/[SystemUI]DateView( 1473): called onTimeUpdated()
I/[SystemUI]DateView( 1473): called onTimeUpdated()
,D/KeyguardUpdateMonitor( 1473): handleTimeUpdate
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-47 f=2412 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.3 bcn=0 [on:0 tx:0 rx:0 period:3005] from screen [on:0 period:-1865003826] gl rssi=-47 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-47 f=2412 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.3 bcn=0 [on:0 tx:0 rx:0 period:9] from screen [on:0 period:-1865003817] gl rssi=-47 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-47 f=2412 sc=60 link=72 tx=0.3, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1865000795] gl rssi=-47 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-47 f=2412 sc=60 link=72 tx=0.3, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-1865000785] gl rssi=-47 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-47 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1864997764] gl rssi=-47 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-47 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:11] from screen [on:0 period:-1864997753] gl rssi=-47 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
D/sensors_hal_Time( 1031): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1031): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1031): tsOffsetIs: Apps: 1715621339038; DSPS: 56358556; Offset : -4322588577
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-47 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1864994733] gl rssi=-47 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-47 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:4] from screen [on:0 period:-1864994729] gl rssi=-47 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-47 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1864991704] gl rssi=-47 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-47 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:9] from screen [on:0 period:-1864991695] gl rssi=-47 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-47 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1864988674] gl rssi=-47 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-47 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:12] from screen [on:0 period:-1864988662] gl rssi=-47 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-47 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1864985641] gl rssi=-47 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-47 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1864985638] gl rssi=-47 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-47 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1864982610] gl rssi=-47 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-47 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1864982607] gl rssi=-47 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-47 f=2412 sc=60 link=72 tx=1.0, 0.0, 0.0  rx=0.5 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1864979584] gl rssi=-47 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-47 f=2412 sc=60 link=72 tx=1.0, 0.0, 0.0  rx=0.5 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-1864979574] gl rssi=-47 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-47 f=2412 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.3 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1864976552] gl rssi=-47 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-47 f=2412 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.3 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1864976549] gl rssi=-47 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,D/sensors_hal_Time( 1031): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1031): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1031): tsOffsetIs: Apps: 1735623619030; DSPS: 57013991; Offset : -4322597429
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-47 f=2412 sc=60 link=72 tx=0.3, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1864973523] gl rssi=-47 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-47 f=2412 sc=60 link=72 tx=0.3, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1864973520] gl rssi=-47 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-47 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1864970495] gl rssi=-47 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-47 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-1864970485] gl rssi=-47 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-47 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1864967464] gl rssi=-47 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-47 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:11] from screen [on:0 period:-1864967453] gl rssi=-47 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-47 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1864964432] gl rssi=-47 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-47 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1864964429] gl rssi=-47 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-47 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1864961402] gl rssi=-47 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0,
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-47 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1864961399] gl rssi=-47 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:-1864958375] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-1864958365] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
D/sensors_hal_Time( 1031): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1031): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1031): tsOffsetIs: Apps: 1755625441001; DSPS: 57669411; Offset : -4322606617
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=1.0, 0.0, 0.0  rx=0.5 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1864955345] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=1.0, 0.0, 0.0  rx=0.5 bcn=0 [on:0 tx:0 rx:0 period:9] from screen [on:0 period:-1864955336] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.3 bcn=0 [on:0 tx:0 rx:0 period:3000] from screen [on:0 period:-1864952316] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.3 bcn=0 [on:0 tx:0 rx:0 period:9] from screen [on:0 period:-1864952307] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.3, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1864949286] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.3, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-1864949276] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1864946255] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-1864946245] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
I/[SystemUI]TimeTickManager( 1473): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1473): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1473): called onTimeUpdated()
I/[SystemUI]Clock( 1473): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1473): called onTimeUpdated()
I/[SystemUI]DateView( 1473): called onTimeUpdated()
I/[SystemUI]DateView( 1473): called onTimeUpdated()
,D/KeyguardUpdateMonitor( 1473): handleTimeUpdate
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1864943225] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:9] from screen [on:0 period:-1864943216] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3000] from screen [on:0 period:-1864940196] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-1864940186] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1864937165] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-1864937155] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
D/sensors_hal_Time( 1031): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1031): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1031): tsOffsetIs: Apps: 1775627611307; DSPS: 58324842; Offset : -4322602981
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1864934135] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:11] from screen [on:0 period:-1864934124] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=1.0, 0.0, 0.0  rx=0.5 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1864931105] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=1.0, 0.0, 0.0  rx=0.5 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-1864931095] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.3 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1864928073] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.3 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1864928070] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.3, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1864925044] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.3, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-1864925034] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1864922012] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:4] from screen [on:0 period:-1864922008] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1864918981] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1864918978] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,D/sensors_hal_Time( 1031): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1031): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1031): tsOffsetIs: Apps: 1795629765621; DSPS: 58980272; Offset : -4322584715
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1864915951] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1864915948] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1864912923] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:4] from screen [on:0 period:-1864912919] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1864909892] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1864909889] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1864906862] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1864906859] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=1.0, 0.0, 0.0  rx=0.5 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:-1864903831] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=1.0, 0.0, 0.0  rx=0.5 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1864903828] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.3 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1864900800] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.3 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1864900797] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.3, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1864897770] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.3, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1864897767] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,D/sensors_hal_Time( 1031): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1031): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1031): tsOffsetIs: Apps: 1815634860406; DSPS: 59635799; Offset : -4322586600
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1864894740] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1864894737] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1864891711] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:4] from screen [on:0 period:-1864891707] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1864888681] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1864888678] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,I/[SystemUI]TimeTickManager( 1473): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1473): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1473): called onTimeUpdated()
I/[SystemUI]Clock( 1473): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1473): called onTimeUpdated()
I/[SystemUI]DateView( 1473): called onTimeUpdated()
I/[SystemUI]DateView( 1473): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1473): handleTimeUpdate
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1864885650] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:4] from screen [on:0 period:-1864885646] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1864882624] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-1864882614] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=1.0, 0.0, 0.0  rx=0.5 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1864879593] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=1.0, 0.0, 0.0  rx=0.5 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1864879590] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.3 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1864876563] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.3 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1864876560] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,D/sensors_hal_Time( 1031): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1031): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1031): tsOffsetIs: Apps: 1835635967430; DSPS: 60291196; Offset : -4322608596
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.3, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1864873533] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.3, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1864873530] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1864870503] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1864870500] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3000] from screen [on:0 period:-1864867472] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:4] from screen [on:0 period:-1864867468] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1864864444] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-1864864434] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1864861411] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1864861408] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1864858381] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1864858378] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,D/PowerManagerServiceEx( 1031): acquireWakeLockInternal: lock=538279423, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1031
,V/AlarmManager( 1031): ELAPSED_WAKEUP set : Alarm{1f57ef1b type 2 when 1195135 com.google.android.gms} when 1195135
,V/AlarmManager( 1031): ELAPSED_WAKEUP set : Alarm{2d2d38b8 type 2 when 1233843 com.google.android.gms} when 1233843
V/AlarmManager( 1031): RTC_WAKEUP set : Alarm{19d96691 type 0 when 1449834089188 com.google.android.gms} when 1449834089188
I/ProcessStatsService( 1031): Prepared write state in 17ms
,I/ProcessStatsService( 1031): Prepared write state in 21ms
,D/[Concierge]Service( 2627): onStartCommand(). Type : 9
,D/GCM     ( 2129): Message class com.google.f.a.a.i
,D/sensors_hal_Time( 1031): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1031): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1031): tsOffsetIs: Apps: 1855637570078; DSPS: 60946608; Offset : -4322590805
,D/LocationManagerService( 1031): getAllProviders()=[passive, gps, network]
,V/GLSActivity( 2129): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/PowerManagerServiceEx( 1031): releaseWakeLockInternal: lock=538279423 [*alarm*], flags=0x0
I/EventLogService( 2345): Aggregate from 1449832529187 (log), 1449832289138 (data)
,I/GLSUser ( 2129): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/ads_measurement
,I/GLSUser ( 2129): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/ads_measurement without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2129): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2129): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
I/ProcessStatsService( 1031): Pruning old procstats: /data/system/procstats/state-2015-12-10-15-10-00.bin
I/art     ( 2129): Explicit concurrent mark sweep GC freed 41393(2MB) AllocSpace objects, 11(1584KB) LOS objects, 50% free, 30MB/62MB, paused 966us total 40.992ms
,I/art     ( 1031): Explicit concurrent mark sweep GC freed 271510(12MB) AllocSpace objects, 12(692KB) LOS objects, 33% free, 45MB/68MB, paused 1.569ms total 98.485ms
,V/GLSActivity( 2129): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/GLSUser ( 2129): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2: email
I/GLSUser ( 2129): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2: email without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2129): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2129): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,E/Ads     ( 2345): [JAMS] Failed to get OAuth token: com.google.android.gms.auth.ad: BadAuthentication
V/GLSActivity( 2129): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=1.0, 0.0, 0.0  rx=0.5 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1864855352] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=1.0, 0.0, 0.0  rx=0.5 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1864855349] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=1.5, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1864852322] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=1.5, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1864852319] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1864849294] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-1864849284] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.2 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1864846263] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.2 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1864846260] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.2, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1864843233] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.2, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1864843230] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1864840203] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1864840200] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1864837174] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:9] from screen [on:0 period:-1864837165] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
D/sensors_hal_Time( 1031): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1031): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1031): tsOffsetIs: Apps: 1875639773039; DSPS: 61602040; Offset : -4322587037
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1864834144] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:11] from screen [on:0 period:-1864834133] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=1.0, 0.0, 0.0  rx=0.5 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1864831121] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=1.0, 0.0, 0.0  rx=0.5 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1864831118] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.3 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1864828090] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.3 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1864828087] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,D/PowerManagerServiceEx( 1031): acquireWakeLockInternal: lock=538279423, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1031
,I/[SystemUI]TimeTickManager( 1473): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1473): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1473): called onTimeUpdated()
I/[SystemUI]Clock( 1473): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1473): called onTimeUpdated()
I/[SystemUI]DateView( 1473): called onTimeUpdated()
I/[SystemUI]DateView( 1473): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1473): handleTimeUpdate
D/[Concierge]Service( 2627): onStartCommand(). Type : 9
,D/PowerManagerServiceEx( 1031): releaseWakeLockInternal: lock=538279423 [*alarm*], flags=0x0
,V/DownloadManager( 3366): starting query, database is not null; projection[0] is _id; projection[1] is _data AS local_filename; projection[2] is mediaprovider_uri; projection[3] is destination; projection[4] is title; projection[5] is description; projection[6] is uri; projection[7] is status; projection[8] is hint; projection[9] is mimetype AS media_type; projection[10] is total_bytes AS total_size; projection[11] is lastmod AS last_modified_timestamp; projection[12] is current_bytes AS bytes_so_far; projection[13] is allow_write; projection[14] is 'placeholder' AS local_uri; projection[15] is 'placeholder' AS reason; projection[16] is drm_status; selection is status='190' OR status='192' OR status='193' OR status='194' OR status='195' OR status='196' OR status='197' OR status='200' AND deleted != '1'; selectionArgs is null; sort is lastmod DESC.
,V/DownloadManager( 3366): created cursor android.database.sqlite.SQLiteCursor@d45af7a on behalf of 2345
V/DownloadManager( 3366): starting query, database is not null; projection[0] is _id; projection[1] is _data AS local_filename; projection[2] is mediaprovider_uri; projection[3] is destination; projection[4] is title; projection[5] is description; projection[6] is uri; projection[7] is status; projection[8] is hint; projection[9] is mimetype AS media_type; projection[10] is total_bytes AS total_size; projection[11] is lastmod AS last_modified_timestamp; projection[12] is current_bytes AS bytes_so_far; projection[13] is allow_write; projection[14] is 'placeholder' AS local_uri; projection[15] is 'placeholder' AS reason; projection[16] is drm_status; selection is (status>='400' AND status<'600') AND deleted != '1'; selectionArgs is null; sort is lastmod DESC.
,V/DownloadManager( 3366): created cursor android.database.sqlite.SQLiteCursor@147f132b on behalf of 2345
V/DownloadManager( 3366): starting query, database is not null; projection[0] is _id; projection[1] is _data AS local_filename; projection[2] is mediaprovider_uri; projection[3] is destination; projection[4] is title; projection[5] is description; projection[6] is uri; projection[7] is status; projection[8] is hint; projection[9] is mimetype AS media_type; projection[10] is total_bytes AS total_size; projection[11] is lastmod AS last_modified_timestamp; projection[12] is current_bytes AS bytes_so_far; projection[13] is allow_write; projection[14] is 'placeholder' AS local_uri; projection[15] is 'placeholder' AS reason; projection[16] is drm_status; selection is status='200' AND deleted != '1'; selectionArgs is null; sort is lastmod DESC.
,V/DownloadManager( 3366): created cursor android.database.sqlite.SQLiteCursor@30347388 on behalf of 2345
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.3, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1864825060] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.3, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1864825057] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1864822034] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-1864822024] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1864819004] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:12] from screen [on:0 period:-1864818992] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
D/sensors_hal_Time( 1031): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1031): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1031): tsOffsetIs: Apps: 1895642465428; DSPS: 62257489; Offset : -4322610764
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3000] from screen [on:0 period:-1864815972] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1864815969] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1864812944] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-1864812934] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1864809910] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1864809907] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-47 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1864806879] gl rssi=-47 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0,
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-47 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1864806876] gl rssi=-47 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-47 f=2412 sc=60 link=72 tx=1.0, 0.0, 0.0  rx=0.5 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1864803849] gl rssi=-47 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-47 f=2412 sc=60 link=72 tx=1.0, 0.0, 0.0  rx=0.5 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1864803846] gl rssi=-47 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-47 f=2412 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.3 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1864800820] gl rssi=-47 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-47 f=2412 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.3 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1864800817] gl rssi=-47 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-47 f=2412 sc=60 link=72 tx=0.3, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1864797791] gl rssi=-47 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-47 f=2412 sc=60 link=72 tx=0.3, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1864797788] gl rssi=-47 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,D/sensors_hal_Time( 1031): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1031): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1031): tsOffsetIs: Apps: 1915644597815; DSPS: 62912918; Offset : -4322584273
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-47 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:2999] from screen [on:0 period:-1864794764] gl rssi=-47 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-47 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:4] from screen [on:0 period:-1864794760] gl rssi=-47 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-47 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3000] from screen [on:0 period:-1864791736] gl rssi=-47 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-47 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:9] from screen [on:0 period:-1864791727] gl rssi=-47 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-47 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3000] from screen [on:0 period:-1864788707] gl rssi=-47 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-47 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:9] from screen [on:0 period:-1864788698] gl rssi=-47 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-47 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1864785676] gl rssi=-47 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-47 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-1864785666] gl rssi=-47 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-47 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1864782645] gl rssi=-47 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-47 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:12] from screen [on:0 period:-1864782633] gl rssi=-47 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-47 f=2412 sc=60 link=72 tx=1.0, 0.0, 0.0  rx=0.5 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1864779611] gl rssi=-47 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-47 f=2412 sc=60 link=72 tx=1.0, 0.0, 0.0  rx=0.5 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1864779608] gl rssi=-47 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-47 f=2412 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.3 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1864776581] gl rssi=-47 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-47 f=2412 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.3 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1864776578] gl rssi=-47 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,D/sensors_hal_Time( 1031): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1031): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1031): tsOffsetIs: Apps: 1935646540777; DSPS: 63568342; Offset : -4322594175
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-47 f=2412 sc=60 link=72 tx=0.3, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1864773552] gl rssi=-47 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-47 f=2412 sc=60 link=72 tx=0.3, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1864773549] gl rssi=-47 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-47 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1864770522] gl rssi=-47 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-47 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1864770519] gl rssi=-47 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3007] from screen [on:0 period:-1864767487] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:13] from screen [on:0 period:-1864767474] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
I/[SystemUI]TimeTickManager( 1473): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1473): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1473): called onTimeUpdated()
I/[SystemUI]Clock( 1473): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1473): called onTimeUpdated()
I/[SystemUI]DateView( 1473): called onTimeUpdated()
I/[SystemUI]DateView( 1473): called onTimeUpdated()
,D/KeyguardUpdateMonitor( 1473): handleTimeUpdate
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1864764457] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1864764454] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3005] from screen [on:0 period:-1864761422] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-1864761412] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1864758396] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:9] from screen [on:0 period:-1864758387] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
D/sensors_hal_Time( 1031): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1031): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1031): tsOffsetIs: Apps: 1955648608165; DSPS: 64223770; Offset : -4322602295
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=1.0, 0.0, 0.0  rx=0.5 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1864755365] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=1.0, 0.0, 0.0  rx=0.5 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-1864755355] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.3 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1864752331] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.3 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1864752328] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.3, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1864749300] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.3, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1864749297] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1864746272] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1864746269] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1864743244] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-1864743234] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1864740212] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1864740209] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3000] from screen [on:0 period:-1864737185] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-1864737184] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,D/sensors_hal_Time( 1031): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1031): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1031): tsOffsetIs: Apps: 1975650853626; DSPS: 64879203; Offset : -4322584384
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3005] from screen [on:0 period:-1864734164] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-1864734154] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=1.0, 0.0, 0.0  rx=0.5 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1864731141] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=1.0, 0.0, 0.0  rx=0.5 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1864731138] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.3 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1864728116] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.3 bcn=0 [on:0 tx:0 rx:0 period:8] from screen [on:0 period:-1864728108] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.3, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1864725086] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.3, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-1864725076] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1864722056] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-1864722046] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1864719024] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-1864719014] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
D/sensors_hal_Time( 1031): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1031): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1031): tsOffsetIs: Apps: 1995653041223; DSPS: 65534635; Offset : -4322594181
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1864715992] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1864715989] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1864712964] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:9] from screen [on:0 period:-1864712955] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1864709934] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:11] from screen [on:0 period:-1864709923] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1864706902] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1864706899] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,I/[SystemUI]TimeTickManager( 1473): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1473): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1473): called onTimeUpdated()
I/[SystemUI]Clock( 1473): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1473): called onTimeUpdated()
I/[SystemUI]DateView( 1473): called onTimeUpdated()
I/[SystemUI]DateView( 1473): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1473): handleTimeUpdate
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=1.0, 0.0, 0.0  rx=0.5 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1864703872] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=1.0, 0.0, 0.0  rx=0.5 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1864703869] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.3 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1864700844] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.3 bcn=0 [on:0 tx:0 rx:0 period:4] from screen [on:0 period:-1864700840] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.3, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1864697814] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.3, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:8] from screen [on:0 period:-1864697806] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
D/sensors_hal_Time( 1031): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1031): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1031): tsOffsetIs: Apps: 2015655324132; DSPS: 66190070; Offset : -4322600117
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1864694786] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:7] from screen [on:0 period:-1864694779] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1864691758] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1864691755] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-47 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1864688727] gl rssi=-47 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-47 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1864688724] gl rssi=-47 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-47 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1864685698] gl rssi=-47 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-47 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1864685695] gl rssi=-47 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-47 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1864682672] gl rssi=-47 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-47 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1864682669] gl rssi=-47 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=1.0, 0.0, 0.0  rx=0.5 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1864679643] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=1.0, 0.0, 0.0  rx=0.5 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1864679640] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.3 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1864676615] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.3 bcn=0 [on:0 tx:0 rx:0 period:9] from screen [on:0 period:-1864676606] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
D/sensors_hal_Time( 1031): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1031): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1031): tsOffsetIs: Apps: 2035657305218; DSPS: 66845495; Offset : -4322602335
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.3, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1864673584] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.3, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:9] from screen [on:0 period:-1864673575] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1864670554] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:11] from screen [on:0 period:-1864670543] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1864667522] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1864667519] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1864664492] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1864664489] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3000] from screen [on:0 period:-1864661464] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-1864661454] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1864658433] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1864658430] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,D/sensors_hal_Time( 1031): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1031): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1031): tsOffsetIs: Apps: 2055658868179; DSPS: 67500906; Offset : -4322596213
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=1.0, 0.0, 0.0  rx=0.5 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1864655404] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=1.0, 0.0, 0.0  rx=0.5 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-1864655394] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.3 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1864652371] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.3 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1864652368] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.3, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1864649342] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.3, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1864649339] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-47 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1864646312] gl rssi=-47 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-47 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1864646309] gl rssi=-47 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,I/[SystemUI]TimeTickManager( 1473): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1473): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1473): called onTimeUpdated()
I/[SystemUI]Clock( 1473): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1473): called onTimeUpdated()
I/[SystemUI]DateView( 1473): called onTimeUpdated()
I/[SystemUI]DateView( 1473): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1473): handleTimeUpdate
D/PowerManagerServiceEx( 1031): acquireWakeLockInternal: lock=538279423, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1031
,D/[Concierge]Service( 2627): onStartCommand(). Type : 9
,I/DigitalAppWidgetProvider( 7865): onReceive: com.android.deskclock.ON_QUARTER_HOUR
,V/DigitalAppWidgetProvider( 7865): startAlarmOnQuarterHour android.app.ReceiverRestrictedContext@f1bd36
D/PowerManagerServiceEx( 1031): releaseWakeLockInternal: lock=538279423 [*alarm*], flags=0x0
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-47 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1864643284] gl rssi=-47 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-47 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:12] from screen [on:0 period:-1864643272] gl rssi=-47 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-47 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1864640250] gl rssi=-47 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-47 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1864640247] gl rssi=-47 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-47 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1864637223] gl rssi=-47 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-47 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1864637220] gl rssi=-47 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,D/sensors_hal_Time( 1031): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1031): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1031): tsOffsetIs: Apps: 2075660801817; DSPS: 68156329; Offset : -4322584922
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-47 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1864634191] gl rssi=-47 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-47 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1864634188] gl rssi=-47 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-47 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1864631164] gl rssi=-47 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-47 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:11] from screen [on:0 period:-1864631153] gl rssi=-47 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-47 f=2412 sc=60 link=72 tx=1.0, 0.0, 0.0  rx=0.5 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1864628130] gl rssi=-47 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-47 f=2412 sc=60 link=72 tx=1.0, 0.0, 0.0  rx=0.5 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1864628127] gl rssi=-47 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.3 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1864625099] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.3 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1864625096] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,V/AlarmManager( 1031): ELAPSED_WAKEUP set : Alarm{9737318 type 2 when 2088135 com.android.bluetooth} when 2088135
,W/bt-smp  ( 6236): Key(LSB ~ MSB) = 0a 3c a6 fe eb 17 6a 79 a6 1f 0a 0b f9 50 a0 5f 
W/bt-smp  ( 6236): Plain text(LSB ~ MSB) = 25 1a 5f 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 6236): Encrypted text(LSB ~ MSB) = 0c 94 77 6c d9 66 2f 29 fa f0 d5 18 9a 7b 4e 11 
W/bt-btm  ( 6236): Stopping oneshot timer
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.3, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1864622070] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.3, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1864622067] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1864619040] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1864619037] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,D/sensors_hal_Time( 1031): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1031): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1031): tsOffsetIs: Apps: 2095662915716; DSPS: 68811759; Offset : -4322607385
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1864616011] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1864616008] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1864612982] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1864612979] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1864609954] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-1864609944] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1864606923] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1864606920] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=1.0, 0.0, 0.0  rx=0.5 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1864603892] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=1.0, 0.0, 0.0  rx=0.5 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1864603889] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.3 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1864600862] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.3 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1864600859] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.3, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3000] from screen [on:0 period:-1864597835] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.3, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:9] from screen [on:0 period:-1864597826] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
D/sensors_hal_Time( 1031): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1031): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1031): tsOffsetIs: Apps: 2115664832166; DSPS: 69467182; Offset : -4322613489
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1864594806] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,TIME-OUT KILL (timeout was 1800000ms),E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:9] from screen [on:0 period:-1864594797] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3000] from screen [on:0 period:-1864591778] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1864591775] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
D/AndroidRuntime( 8119): 
D/AndroidRuntime( 8119): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 8119): CheckJNI is OFF
D/AndroidRuntime( 8119): Calling main entry com.android.commands.pm.Pm
I/ActivityManager( 1031): Force stopping com.test.thalitest appid=10311 user=-1: uninstall pkg
I/ActivityManager( 1031): Killing 6159:com.test.thalitest/u0a311 (adj 0): stop com.test.thalitest
I/WindowState( 1031): WIN DEATH: Window{23bb6ffa u0 com.test.thalitest/com.test.thalitest.MainActivity}
D/WifiService( 1031): Client connection lost with reason: 4
D/InputDispatcher( 1031): Window went away: Window{23bb6ffa u0 com.test.thalitest/com.test.thalitest.MainActivity}
W/PackageSettings( 1031): Skipping PackageSetting{225e55a5 com.example.hello/10318} due to missing metadata
I/ActivityManager( 1031): Killing 7313:com.android.gallery3d/u0a27 (adj 15): empty for 1807s
I/ActivityManager( 1031): Killing 7292:com.android.contacts/u0a19 (adj 15): empty for 1807s
I/ActivityManager( 1031): Killing 7264:com.lge.appbox.client/u0a11 (adj 15): empty for 1807s
I/ActivityManager( 1031): Killing 6987:com.google.android.talk/u0a72 (adj 15): empty for 1807s
I/ActivityManager( 1031): Killing 6961:com.google.android.gms.unstable/u0a5 (adj 15): empty for 1816s
I/ActivityManager( 1031): Killing 7182:com.google.android.configupdater/u0a59 (adj 15): empty for 1818s
I/ActivityManager( 1031): Killing 7143:com.google.android.partnersetup/u0a8 (adj 15): empty for 1818s
I/ActivityManager( 1031):   Force finishing activity ActivityRecord{206a37a7 u0 com.test.thalitest/.MainActivity t4}
E/GBMv2   (  348): DFP En is all cleared set to be enabled
W/ActivityManager( 1031): Spurious death for ProcessRecord{fc98171 6159:com.test.thalitest/u0a311}, curProc for 6159: null
I/ActivityManager( 1031): Force stopping com.test.thalitest appid=10311 user=0: pkg removed
I/ActivityManager( 1031):   Force finishing activity ActivityRecord{206a37a7 u0 com.test.thalitest/.MainActivity t4 f}
W/ActivityManager( 1031): Duplicate finish request for ActivityRecord{206a37a7 u0 com.test.thalitest/.MainActivity t4 f}
I/art     ( 4258): Explicit concurrent mark sweep GC freed 31096(1841KB) AllocSpace objects, 5(89KB) LOS objects, 34% free, 29MB/45MB, paused 449us total 71.744ms
W/libprocessgroup( 1031): failed to open /acct/uid_10027/pid_7313/cgroup.procs: No such file or directory
W/libprocessgroup( 1031): failed to open /acct/uid_10019/pid_7292/cgroup.procs: No such file or directory
W/libprocessgroup( 1031): failed to open /acct/uid_10011/pid_7264/cgroup.procs: No such file or directory
W/libprocessgroup( 1031): failed to open /acct/uid_10072/pid_6987/cgroup.procs: No such file or directory
W/libprocessgroup( 1031): failed to open /acct/uid_10005/pid_6961/cgroup.procs: No such file or directory
W/libprocessgroup( 1031): failed to open /acct/uid_10059/pid_7182/cgroup.procs: No such file or directory
W/libprocessgroup( 1031): failed to open /acct/uid_10008/pid_7143/cgroup.procs: No such file or directory
I/[LGHome]EVENT( 2086): [Launcher.java:5338:onStart()]onStart
D/SplitWindowPolicy( 1964): updateActivityStateChanged: resumed=false, screenId=0, isScreenFull=false
D/SplitWindowPolicy( 1964): topRunningActivity=ActivityInfo{20067860 co.....Launcher}, taskId=3, activityType=1, bIsSplit=false
I/[LGHome]EVENT( 2086): [Launcher.java:903:onResume()]onResume
I/[LGHome]EVENT( 2086): [LauncherModel.java:1352:startLoader()]startLoader isLaunching=true
D/ActionManagerService( 1919): notifyUserLog: 1000003
D/LIA_Informant_ActionManagerMessageHandler( 2728): handleMessage: what(1000) actionID(0x1000003)
I/[LGHome]GBoardWebView( 2086): [GBoardWebView.java:306:loadCacheBitmapPostDelayed()]loadCacheBitmapPostDelayed() delay:1
I/[LGHome]LGActivityUtil( 2086): [LGActivityUtil.java:319:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
I/[LGHome]EVENT( 2086): [Launcher.java:1056:onResume()]onResume end
I/[LGHome]EVENT( 2086): [Launcher.java:1114:onPause()]onPause
D/SplitWindowPolicy( 1964): updateActivityStateChanged: resumed=true, screenId=0, isScreenFull=false
D/SplitWindowPolicy( 1964): topRunningActivity=ActivityInfo{15aeb119 co.....Launcher}, taskId=3, activityType=1, bIsSplit=false
D/ActionManagerService( 1919): notifyUserLog: 1000004
I/[LGHome]GBoardWebView( 2086): [GBoardWebView.java:247:writeCacheBitmapPostDelayed()]writeCacheBitmapPostDelayed() delay: we don't have a change point1
I/[LGHome]Launcher.Model( 2086): [LauncherModel.java:1469:loadAndBindWorkspace()]loadAndBindWorkspace=0ms
D/KeyguardModel( 1473): mPackageIntentReceiver, received action: android.intent.action.PACKAGE_REMOVED, sendingUserId:0
D/LIA_Informant_ActionManagerMessageHandler( 2728): handleMessage: what(1000) actionID(0x1000004)
I/InputReader( 1031): Reconfiguring input devices.  changes=0x00000010
W/GeofencerStateMachine( 1832): Ignoring removeGeofence because network location is disabled.
D/LIA_Service_RemotePackageHandler( 2042): onReceive action : android.intent.action.PACKAGE_REMOVED = package:com.test.thalitest
D/LIA_MrGDBLogger_PackageInfoDetector( 2728): [dreamwood]action: android.intent.action.PACKAGE_REMOVED, package: com.test.thalitest
E/LGBluetoothAvrcpQcomAdapter( 6236): [BTUI] [BTUI] onReceive()... android.intent.action.PACKAGE_REMOVED
D/LGBluetoothAvrcpQcomAdapter( 6236): [BTUI] [+] updateMediaPlayerInfo
I/ActivityManager( 1031): Start proc com.wsandroid.suite.lge for broadcast com.wsandroid.suite.lge/com.wavesecure.core.WSAndroidSystemIntentReceiver: pid=8174 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
V/BoardContentProvider( 2728): query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
W/System.err( 4216): android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
W/System.err( 4216): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
W/System.err( 4216): 	at com.lge.mlt.MptOnAppWatcher$1.onReceive(MptOnAppWatcher.java:44)
W/System.err( 4216): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:956)
W/System.err( 4216): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 4216): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 4216): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 4216): 	at android.app.ActivityThread.main(ActivityThread.java:5274)
W/System.err( 4216): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 4216): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 4216): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
W/System.err( 4216): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
I/[SystemUI]QSlideListController( 1473): onReceive = android.intent.action.PACKAGE_REMOVED
I/GBoardWebViewUtils( 2086): checkExpiredAndRemoveCard() card: GBoardCard = { id: mw_initial
I/GBoardWebViewUtils( 2086): , create_time: 1430558575574
I/GBoardWebViewUtils( 2086): , expire_time: 0
I/GBoardWebViewUtils( 2086): , raw_uri: file:///system/etc/mrg_default_forms/MyWellness/initial/initial.html?id=mw_initial
I/GBoardWebViewUtils( 2086): , category: com.lge.intent.category.gboard.MYWELLNESS
I/GBoardWebViewUtils( 2086): , display: false
I/GBoardWebViewUtils( 2086): , animation: false }
I/GBoardWebViewUtils( 2086): checkExpiredAndRemoveCard() card: GBoardCard = { id: dyk000
I/GBoardWebViewUtils( 2086): , create_time: 1430558575600
I/GBoardWebViewUtils( 2086): , expire_time: 0
I/GBoardWebViewUtils( 2086): , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
I/GBoardWebViewUtils( 2086): , category: com.lge.intent.category.gboard.DOYOUKNOW
I/GBoardWebViewUtils( 2086): , display: false
I/GBoardWebViewUtils( 2086): , animation: false }
I/GBoardWebViewUtils( 2086): checkExpiredAndRemoveCard() card: GBoardCard = { id: guide_1111111111116_1449757673225
I/GBoardWebViewUtils( 2086): , create_time: 1449757673771
I/GBoardWebViewUtils( 2086): , expire_time: 0
I/GBoardWebViewUtils( 2086): , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/2/userguide.html?id=guide_1111111111116_1449757673225&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
I/GBoardWebViewUtils( 2086): , category: com.lge.intent.category.gboard.DOYOUKNOW
I/GBoardWebViewUtils( 2086): , display: false
I/GBoardWebViewUtils( 2086): , animation: false }
D/KeyguardModel( 1473): package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
D/KeyguardModel( 1473): createShortcutInfo...
D/WallpaperManager( 2086): suggestDesiredDimensions(2880, 2560) by package(com.lge.launcher2)
D/KeyguardModel( 1473): package = com.android.mms, class = com.android.mms.ui.ConversationList
D/KeyguardModel( 1473): createShortcutInfo...
I/SystemUI[Framework]( 1031): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x8000, pkg=com.android.systemui
W/ResourcesManager( 1473): Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
W/ResourcesManager( 1473): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 1473): Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
W/ResourcesManager( 1473): Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
I/art     ( 1031): Explicit concurrent mark sweep GC freed 92220(4MB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 45MB/67MB, paused 7.150ms total 199.367ms
W/PhoneWindowManagerEx( 1031): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx( 1031): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx( 1031): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework]( 1031): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@116903d1,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework]( 1031): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
I/[SystemUI]AppWidgetPanel(QRemoteWidgetPanel)( 1473): onReceive = android.intent.action.PACKAGE_REMOVED, packageName : com.test.thalitest
D/KeyguardModel( 1473): mPackageIntentReceiver, received action: android.intent.action.PACKAGE_FULLY_REMOVED, sendingUserId:0
W/ResourceType( 1473): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1473): Failure retrieving resources for com.android.mms: Resource ID #0x0
I/art     ( 1031): WaitForGcToComplete blocked for 135.398ms for cause Explicit
D/KeyguardModel( 1473): package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
D/KeyguardModel( 1473): createShortcutInfo...
W/ResourcesManager( 1473): Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
W/ResourcesManager( 1473): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
I/[LGHome]GBoardWebView( 2086): [GBoardWebView.java:321:loadCacheBitmap()]loadCacheBitmap()
W/ResourceType( 1473): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1473): Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
V/SIM_STK ( 1031): Menu title from STK is T-Mobile
D/SplitUIManager( 1884): split_name #11 / not available #0
D/SplitUIService( 1884): removed split : 
D/KeyguardModel( 1473): package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
D/KeyguardModel( 1473): createShortcutInfo...
W/ResourcesManager( 1473): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 1473): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 1473): Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
W/ResourcesManager( 1473): Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
W/ResourceType( 1473): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1473): Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
D/KeyguardModel( 1473): package = com.lge.camera, class = com.lge.camera.CameraApp
D/KeyguardModel( 1473): createShortcutInfo...
D/KeyguardModel( 1473): handleShortcutListChanged...
D/KeyguardModel( 1473): package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
D/KeyguardModel( 1473): createShortcutInfo...
V/SIM_STK ( 1031): Menu title from STK is T-Mobile
V/SIM_STK ( 1031): Menu title from STK is T-Mobile
I/[LGHome]EVENT( 2086): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
I/[LGHome]EVENT( 2086): [Launcher.java:5349:onStop()]onStop
D/administrator( 1031): Handling package changes for user 0
D/KeyguardModel( 1473): package = com.android.mms, class = com.android.mms.ui.ConversationList
D/KeyguardModel( 1473): createShortcutInfo...
W/ResourceType( 1473): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1473): Failure retrieving resources for com.android.mms: Resource ID #0x0
D/KeyguardModel( 1473): package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
D/KeyguardModel( 1473): createShortcutInfo...
W/ResourceType( 1473): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1473): Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
D/KeyguardModel( 1473): package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
D/KeyguardModel( 1473): createShortcutInfo...
W/ResourceType( 1473): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1473): Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
D/KeyguardModel( 1473): package = com.lge.camera, class = com.lge.camera.CameraApp
D/KeyguardModel( 1473): createShortcutInfo...
W/ActivityManager( 1031): getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
D/LGBluetoothAvrcpQcomAdapter( 6236): [BTUI] installed app name: Music
D/LGBluetoothAvrcpQcomAdapter( 6236): [BTUI] installed app name: Google Play Music
D/LGBluetoothAvrcpQcomAdapter( 6236): [BTUI] === MediaPlayerInfo (playerId:0) ===
D/LGBluetoothAvrcpQcomAdapter( 6236): [BTUI]          displayName: Music
D/LGBluetoothAvrcpQcomAdapter( 6236): [BTUI]          packageName: com.lge.music
D/LGBluetoothAvrcpQcomAdapter( 6236): [BTUI]          playState: 2 (PAUSED)
D/LGBluetoothAvrcpQcomAdapter( 6236): [BTUI] === MediaPlayerInfo (playerId:1) ===
D/LGBluetoothAvrcpQcomAdapter( 6236): [BTUI]          displayName: Google Play Music
D/LGBluetoothAvrcpQcomAdapter( 6236): [BTUI]          packageName: com.google.android.music
D/LGBluetoothAvrcpQcomAdapter( 6236): [BTUI]          playState: 2 (PAUSED)
D/LGBluetoothAvrcpQcomAdapter( 6236): [BTUI] [-] updateMediaPlayerInfo
W/ResourcesManager( 8174): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
D/KeyguardModel( 1473): handleShortcutListChanged...
D/SplitUIManager( 1884): split_name #11 / not available #0
I/SplitUIService( 1884): split app #11
D/PluginManager( 8174): init()
V/SIM_STK ( 1031): Menu title from STK is T-Mobile
I/[LGHome]Launcher.Model( 2086): [LauncherModel.java:2230:run()] LauncherModel bind current page shortcut
I/[LGHome]Launcher( 2086): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/[LGHome]EVENT( 2086): [Workspace.java:918:addInScreen()]Add Shortcut [Email] in screen 1 [1, 4]
I/[LGHome]EVENT( 2086): [Workspace.java:918:addInScreen()]Add Shortcut [Play Store] in screen 1 [2, 4]
I/[LGHome]EVENT( 2086): [Workspace.java:918:addInScreen()]Add Shortcut [Camera] in screen 1 [3, 4]
I/[LGHome]EVENT( 2086): [Workspace.java:918:addInScreen()]Add Shortcut [Settings] in screen 1 [4, 4]
I/Timeline( 1031): Timeline: Activity_windows_visible id: ActivityRecord{39a5f548 u0 com.lge.launcher2/.Launcher t3} time:2122447
I/[LGHome]Launcher.Model( 2086): [LauncherModel.java:2244:run()] LauncherModel bind current page shortcut
I/[LGHome]Launcher( 2086): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/[LGHome]EVENT( 2086): [Workspace.java:918:addInScreen()]Add Folder [Google] in screen 1 [0, 4]
I/[LGHome]Launcher.Model( 2086): [LauncherModel.java:2256:run()] LauncherModel bind current page widget
I/[LGHome]Launcher( 2086): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 2086): [LGUnreadLgeEmailsBadge.java:107:countUnreadItems()]setTotalCount : 0
I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 2086): [LGUnreadLgeEmailsBadge.java:108:countUnreadItems()]countUnreadItems() ended..
I/NotificationService( 1031): action=android.intent.action.PACKAGE_REMOVED queryReplace=false
D/BackupManagerService( 1031): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/JobSchedulerService( 1031): Receieved: android.intent.action.PACKAGE_REMOVED
D/TaskPersister( 1031): removeObsoleteFile: deleting file=4_task.xml
D/PhoneStatusBar( 1473): setSystemUiVisibility vis=8000 mask=ffffffff oldVal=0 newVal=8000 diff=8000
I/[SystemUI]NavigationThemeResource( 1473): NavigationKey Color is changed(BLACK -> WHITE_WITH_SHADOW)
I/[SystemUI]NavigationThemeResource( 1473):  BarMode=4, Theme=WHITE, LightBackground=false (Transparent)
I/[SystemUI]NavigationThemeResource( 1473): , Keyguard show=false, IME shown=false, Panel expanded=false
I/[Concierge]WidgetView( 2086): ConciergeWidgetView is instantiated. sIsWidgetAttached : true
D/[Concierge]Service( 2627): onStartCommand(). Type : 8
D/[Concierge]Service( 2627): Update widget. Component : {com.lge.concierge/com.lge.concierge.ConciergeWidgetProvider}
D/[Concierge]Service( 2627): Update widget ID : 11
D/[Concierge]WidgetView( 2086): change position of spinner
I/[Concierge]WidgetView( 2086): initWebView(). Time : 1449834356826
D/[Concierge]Service( 2627): onStartCommand(). Type : 0
I/ThermalEngine(  342): Thermal-Server: Thermal received msg from  override
I/Thermal-Lib( 3099): Thermal-Lib-Client: Client request sent
I/[Concierge]WebView( 2086): Return exist ConciergeWebView. Reuse : 866058693
D/[Concierge]WidgetView( 2086): State Change : null -> AccInBeforeState
I/[LgeWidgetLib]LgeAppWidgetHostView( 2086): [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
I/[LgeWidgetLib]ExtViewHost( 2086): [LgeAppWidgetExtViewHost.java:136:setState()]New State = com.lge.lgewidgetlib.extview.NormalState@2f0f671
I/[LGHome]EVENT( 2086): [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.concierge.ConciergeWidgetProvider] in screen 1 [0, 0]
I/[LGHome]Launcher.Model( 2086): [LauncherModel.java:2256:run()] LauncherModel bind current page widget
I/[LGHome]Launcher( 2086): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/[LGHome]EVENT( 2086): [Workspace.java:918:addInScreen()]Add AppWidget [com.google.android.googlequicksearchbox.SearchWidgetProvider] in screen 1 [0, 2]
D/[Concierge]WidgetView( 2086): isWidgetUpdateSkippable ? true
D/[Concierge]WidgetBroadcastReceiver( 2086): New receiver registered. Self-unregister old one. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
W/[Concierge]WidgetView( 2086): Widget kill message received. Destory myself. My : 1449832262387, New one : 1449834356826
D/[Concierge]WidgetView( 2086): Unregister all receivers
W/[Concierge]WidgetBroadcastReceiver( 2086): Tried unregister broadcastReceiver which is not registered. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
I/[LGHome]Launcher( 2086): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/[LGHome]EVENT( 2086): [Workspace.java:918:addInScreen()]Add Shortcut [Gallery] in screen 2 [0, 4]
I/[LGHome]EVENT( 2086): [Workspace.java:918:addInScreen()]Add Shortcut [Calendar] in screen 2 [1, 4]
I/[LGHome]EVENT( 2086): [Workspace.java:918:addInScreen()]Add Shortcut [QuickMemo+] in screen 2 [2, 4]
I/[LGHome]EVENT( 2086): [Workspace.java:918:addInScreen()]Add Shortcut [Quick Remote] in screen 2 [3, 4]
I/[LGHome]EVENT( 2086): [Workspace.java:918:addInScreen()]Add Shortcut [FM Radio] in screen 2 [4, 4]
I/[LGHome]Launcher( 2086): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/[LGHome]Launcher( 2086): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/[LgeWidgetLib]LgeAppWidgetHostView( 2086): [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
E/[LgeWidgetLib]LgeAppWidgetHostView( 2086): [LgeAppWidgetHostView.java:124:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
I/[LGHome]EVENT( 2086): [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1] in screen 2 [0, 0]
I/[LGHome]Launcher( 2086): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/art     ( 1031): Explicit concurrent mark sweep GC freed 14186(773KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 44MB/67MB, paused 1.951ms total 306.429ms
W/ResourcesManager( 1031): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
I/Timeline( 2086): Timeline: Activity_idle id: android.os.BinderProxy@2788e894 time:2122597
W/ResourceType( 1031): Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
I/[LGHome]EVENT( 2086): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
D/AndroidRuntime( 8119): Shutting down VM
W/ExternalStrings( 8174): load override strings
W/ExternalStrings( 8174): java.lang.RuntimeException: Unexpected tag, got eat-comment
W/ExternalStrings( 8174): 	at com.mcafee.plugin.af.a(Unknown Source)
W/ExternalStrings( 8174): 	at com.mcafee.plugin.ac.b(Unknown Source)
W/ExternalStrings( 8174): 	at com.mcafee.plugin.ak.d(Unknown Source)
W/ExternalStrings( 8174): 	at com.mcafee.plugin.ak.a(Unknown Source)
W/ExternalStrings( 8174): 	at com.mcafee.app.s.getClassLoader(Unknown Source)
W/ExternalStrings( 8174): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5001)
W/ExternalStrings( 8174): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4609)
W/ExternalStrings( 8174): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4549)
W/ExternalStrings( 8174): 	at android.app.ActivityThread.access$1500(ActivityThread.java:148)
W/ExternalStrings( 8174): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1344)
W/ExternalStrings( 8174): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/ExternalStrings( 8174): 	at android.os.Looper.loop(Looper.java:135)
W/ExternalStrings( 8174): 	at android.app.ActivityThread.main(ActivityThread.java:5274)
W/ExternalStrings( 8174): 	at java.lang.reflect.Method.invoke(Native Method)
W/ExternalStrings( 8174): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/ExternalStrings( 8174): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
W/ExternalStrings( 8174): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
D/StatusProvider( 8174): onCreate
I/chromium( 2086): [INFO:CONSOLE(0)] "'window.webkitStorageInfo' is deprecated. Please use 'navigator.webkitTemporaryStorage' or 'navigator.webkitPersistentStorage' instead.", source:  (0)
V/Signer  ( 8174): override build config not found
D/Signer  ( 8174): value of property debug is false
D/LGMDMWrapper( 8174): Found class 'com.mcafee.lgmdm.LGMDMWrapper$DataWipe'.
D/LGMDMWrapper( 8174): Found class 'com.mcafee.lgmdm.LGMDMWrapper$DownloadMode'.
D/LGMDMWrapper( 8174): Found class 'com.mcafee.lgmdm.LGMDMWrapper$HardReset'.
D/LGMDMWrapper( 8174): Found class 'com.mcafee.lgmdm.LGMDMWrapper$HardwareKeyReset'.
D/LGMDMWrapper( 8174): Found class 'com.mcafee.lgmdm.LGMDMWrapper$RemoveDeviceAdmin'.
D/LGMDMWrapper( 8174): Found class 'com.mcafee.lgmdm.LGMDMWrapper$UnknownSourceInstallation'.
D/LGMDMWrapper( 8174): Found class 'com.mcafee.lgmdm.LGMDMWrapper$Usb'.
D/LGMDMWrapper( 8174): Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbDebugging'.
D/LGMDMWrapper( 8174): Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbHostStorage'.
D/LGMDMWrapper( 8174): Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbMediaTransfer'.
D/LGMDMWrapper( 8174): Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbPictureTransfer'.
D/LGMDMWrapper( 8174): Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbStorage'.
D/LGMDMWrapper( 8174): Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbTethering'.
V/LGMDMManager( 8174): Create singleton instance
I/GBoardtInterface( 2086): onReloaded()
I/GBoardWebViewClient( 2086): onPageFinished url:file:///android_asset/www/main.html
V/BoardContentProvider( 2728): query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
V/BoardContentProvider( 2728): query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
D/ActionManagerService( 1919): notifyUserLog: 1000001
D/LIA_Informant_ActionManagerMessageHandler( 2728): handleMessage: what(1000) actionID(0x1000001)
D/LIA_Informant_Tips_SmartTipsActionManager( 2728): onEvent() : ACTION_BOARD_ENABLED
D/ActionManagerService( 1919): notifyUserLog: 1000001
D/LIA_Informant_ActionManagerMessageHandler( 2728): handleMessage: what(1000) actionID(0x1000001)
D/LIA_Informant_Tips_SmartTipsActionManager( 2728): onEvent() : ACTION_BOARD_ENABLED
D/LIA_Informant_Tips_FormEventRepository( 2728): getSize() : size - 0
D/LIA_Informant_Tips_SmartTipsActionManager( 2728): onSettingEvent() : GBoard On - add scheduler - 0
V/BoardContentProvider( 2728): query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
D/GBoardUriUtils( 2086): fileExists: file:///system/etc/mrg_default_forms/MyWellness/initial/initial2.html?id=mw_initial return true
D/GBoardWebViewUtils( 2086): changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyWellness/initial/initial2.html?id=mw_initial
D/GBoardUriUtils( 2086): fileExists: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial2.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc] return true
D/GBoardWebViewUtils( 2086): changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial2.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
D/GBoardUriUtils( 2086): fileExists: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/2/userguide2.html?id=guide_1111111111116_1449757673225&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay return true
D/GBoardWebViewUtils( 2086): changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/2/userguide2.html?id=guide_1111111111116_1449757673225&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
D/LGMDMWrapper( 8174): LG MDM library v4.0.0 is available on this device.
D/PostponalbeReceiver( 8174): WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.intent.action.PACKAGE_REMOVED'.
W/ContextImpl( 8174): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
I/ActivityManager( 1031): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.manager.PreloadListManagerHelper: pid=8204 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
I/ActivityManager( 1031): Killing 6833:com.google.android.apps.plus/u0a97 (adj 15): empty for 1808s
W/ActivityThread( 8174): ClassLoader.getResources: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/libprocessgroup( 1031): failed to open /acct/uid_10097/pid_6833/cgroup.procs: No such file or directory
I/AppUp4:AppBoxCP( 8204): onCreate
W/AppUp4:DB( 8204):  [AppBoxDatabaseHelper] construct
W/FileUtils( 8204): Failed to chmod(/data/data/com.lge.appbox.client/databases/appbox.db): android.system.ErrnoException: chmod failed: EROFS (Read-only file system)
I/AppUp4:DB( 8204):  setFingerPrint start
I/AppUp4:DB( 8204):  newfinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys SDK version = 21
I/AppUp4:DB( 8204):  beforefinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys
E/SQLiteDatabase( 8174): Failed to open database '/data/data/com.wsandroid.suite.lge/databases/WSAndroid'.
E/SQLiteDatabase( 8174): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 8174): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 8174): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 8174): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 8174): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 8174): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 8174): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 8174): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:907)
E/SQLiteDatabase( 8174): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:892)
E/SQLiteDatabase( 8174): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:795)
E/SQLiteDatabase( 8174): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1213)
E/SQLiteDatabase( 8174): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 8174): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 8174): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 8174): 	at com.mcafee.wsstorage.b.a(Unknown Source)
E/SQLiteDatabase( 8174): 	at com.mcafee.wsstorage.a.m(Unknown Source)
E/SQLiteDatabase( 8174): 	at com.mcafee.wsstorage.a.a(Unknown Source)
E/SQLiteDatabase( 8174): 	at com.mcafee.wsstorage.a.b(Unknown Source)
E/SQLiteDatabase( 8174): 	at com.mcafee.wsstorage.ConfigManager.g(Unknown Source)
E/SQLiteDatabase( 8174): 	at com.mcafee.wsstorage.ConfigManager.c(Unknown Source)
E/SQLiteDatabase( 8174): 	at com.mcafee.wsstorage.ConfigManager.ab(Unknown Source)
E/SQLiteDatabase( 8174): 	at com.mcafee.fw.ws.WSLicenseService.a(Unknown Source)
E/SQLiteDatabase( 8174): 	at com.mcafee.g.b.a(Unknown Source)
E/SQLiteDatabase( 8174): 	at com.mcafee.applock.AppLockComponent.a_(Unknown Source)
E/SQLiteDatabase( 8174): 	at com.mcafee.applock.AppLockComponent.a(Unknown Source)
E/SQLiteDatabase( 8174): 	at com.mcafee.c.b.b(Unknown Source)
E/SQLiteDatabase( 8174): 	at com.mcafee.framework.b.a(Unknown Source)
E/SQLiteDatabase( 8174): 	at com.mcafee.app.t.run(Unknown Source)
E/SQLiteDatabase( 8174): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/SQLiteDatabase( 8174): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 8174): 	at com.mcafee.d.f.run(Unknown Source)
E/SQLiteDatabase( 8174): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 8174): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 8174): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteDatabase( 8174): 	at com.mcafee.d.c.run(Unknown Source)
I/AppUp4:DB( 8204):  SDK version = 21
I/AppUp4:DB( 8204):  beforefinger == newfinger no write in DB
D/AppUp4:AppBoxApplication( 8204): AppBoxApplication onCreate()
E/SQLiteLog( 8204): (3850) statement aborts at 24: [INSERT INTO exclude_apps(package) VALUES (?)] disk I/O error
E/SQLiteDatabase( 8204): Error inserting package=com.test.thalitest
E/SQLiteDatabase( 8204): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 8204): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 8204): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:787)
E/SQLiteDatabase( 8204): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:926)
E/SQLiteDatabase( 8204): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 8204): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1572)
E/SQLiteDatabase( 8204): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1442)
E/SQLiteDatabase( 8204): 	at com.lge.appbox.databases.AppBoxContentProvider.insert(AppBoxContentProvider.java:220)
E/SQLiteDatabase( 8204): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:238)
E/SQLiteDatabase( 8204): 	at android.content.ContentResolver.insert(ContentResolver.java:1223)
E/SQLiteDatabase( 8204): 	at com.lge.appbox.manager.PreloadListManagerHelper.addExcludeApp(PreloadListManagerHelper.java:134)
E/SQLiteDatabase( 8204): 	at com.lge.appbox.manager.PreloadListManagerHelper.addExcludeAppInternal(PreloadListManagerHelper.java:115)
E/SQLiteDatabase( 8204): 	at com.lge.appbox.manager.PreloadListManagerHelper.onRemoveAppEvent(PreloadListManagerHelper.java:100)
E/SQLiteDatabase( 8204): 	at com.lge.appbox.manager.PreloadListManagerHelper.updateExDb(PreloadListManagerHelper.java:65)
E/SQLiteDatabase( 8204): 	at com.lge.appbox.manager.PreloadListManagerHelper.onReceive(PreloadListManagerHelper.java:46)
E/SQLiteDatabase( 8204): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2586)
E/SQLiteDatabase( 8204): 	at android.app.ActivityThread.access$1700(ActivityThread.java:148)
E/SQLiteDatabase( 8204): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1360)
E/SQLiteDatabase( 8204): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 8204): 	at android.os.Looper.loop(Looper.java:135)
E/SQLiteDatabase( 8204): 	at android.app.ActivityThread.main(ActivityThread.java:5274)
E/SQLiteDatabase( 8204): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteDatabase( 8204): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteDatabase( 8204): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
E/SQLiteDatabase( 8204): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1864588748] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-48 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:0] from screen [on:0 period:-1864588748] gl rssi=-48 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
I/ActivityManager( 1031): Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=8227 uid=10019 gids={50019, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
E/SQLiteDatabase( 8174): Failed to open database '/data/data/com.wsandroid.suite.lge/databases/lockedapplications'.
E/SQLiteDatabase( 8174): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 8174): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 8174): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 8174): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 8174): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 8174): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 8174): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 8174): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:907)
E/SQLiteDatabase( 8174): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:892)
E/SQLiteDatabase( 8174): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:795)
E/SQLiteDatabase( 8174): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1213)
E/SQLiteDatabase( 8174): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 8174): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 8174): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteDatabase( 8174): 	at com.mcafee.applock.a.a(Unknown Source)
E/SQLiteDatabase( 8174): 	at com.mcafee.applock.d.d(Unknown Source)
E/SQLiteDatabase( 8174): 	at com.mcafee.applock.d.<init>(Unknown Source)
E/SQLiteDatabase( 8174): 	at com.mcafee.applock.d.a(Unknown Source)
E/SQLiteDatabase( 8174): 	at com.mcafee.modes.adapt.a.<init>(Unknown Source)
E/SQLiteDatabase( 8174): 	at com.mcafee.modes.adapt.a.a(Unknown Source)
E/SQLiteDatabase( 8174): 	at com.mcafee.modes.adapt.ModesLockHelper.a(Unknown Source)
E/SQLiteDatabase( 8174): 	at com.mcafee.applock.h.<init>(Unknown Source)
E/SQLiteDatabase( 8174): 	at com.mcafee.applock.f.<init>(Unknown Source)
E/SQLiteDatabase( 8174): 	at com.mcafee.applock.f.a(Unknown Source)
E/SQLiteDatabase( 8174): 	at com.mcafee.applock.AppLockComponent.d(Unknown Source)
E/SQLiteDatabase( 8174): 	at com.mcafee.applock.AppLockComponent.a_(Unknown Source)
E/SQLiteDatabase( 8174): 	at com.mcafee.applock.AppLockComponent.a(Unknown Source)
E/SQLiteDatabase( 8174): 	at com.mcafee.c.b.b(Unknown Source)
E/SQLiteDatabase( 8174): 	at com.mcafee.framework.b.a(Unknown Source)
E/SQLiteDatabase( 8174): 	at com.mcafee.app.t.run(Unknown Source)
E/SQLiteDatabase( 8174): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/SQLiteDatabase( 8174): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 8174): 	at com.mcafee.d.f.run(Unknown Source)
E/SQLiteDatabase( 8174): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 8174): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 8174): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteDatabase( 8174): 	at com.mcafee.d.c.run(Unknown Source)
I/ActivityManager( 1031): Killing 7402:com.google.android.gms:car/u0a5 (adj 15): empty for 1808s
E/SQLiteOpenHelper( 8174): Couldn't open lockedapplications for writing (will try read-only):
E/SQLiteOpenHelper( 8174): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 8174): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 8174): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteOpenHelper( 8174): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteOpenHelper( 8174): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 8174): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 8174): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 8174): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:907)
E/SQLiteOpenHelper( 8174): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:892)
E/SQLiteOpenHelper( 8174): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:795)
E/SQLiteOpenHelper( 8174): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1213)
E/SQLiteOpenHelper( 8174): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteOpenHelper( 8174): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteOpenHelper( 8174): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteOpenHelper( 8174): 	at com.mcafee.applock.a.a(Unknown Source)
E/SQLiteOpenHelper( 8174): 	at com.mcafee.applock.d.d(Unknown Source)
E/SQLiteOpenHelper( 8174): 	at com.mcafee.applock.d.<init>(Unknown Source)
E/SQLiteOpenHelper( 8174): 	at com.mcafee.applock.d.a(Unknown Source)
E/SQLiteOpenHelper( 8174): 	at com.mcafee.modes.adapt.a.<init>(Unknown Source)
E/SQLiteOpenHelper( 8174): 	at com.mcafee.modes.adapt.a.a(Unknown Source)
E/SQLiteOpenHelper( 8174): 	at com.mcafee.modes.adapt.ModesLockHelper.a(Unknown Source)
E/SQLiteOpenHelper( 8174): 	at com.mcafee.applock.h.<init>(Unknown Source)
E/SQLiteOpenHelper( 8174): 	at com.mcafee.applock.f.<init>(Unknown Source)
E/SQLiteOpenHelper( 8174): 	at com.mcafee.applock.f.a(Unknown Source)
E/SQLiteOpenHelper( 8174): 	at com.mcafee.applock.AppLockComponent.d(Unknown Source)
E/SQLiteOpenHelper( 8174): 	at com.mcafee.applock.AppLockComponent.a_(Unknown Source)
E/SQLiteOpenHelper( 8174): 	at com.mcafee.applock.AppLockComponent.a(Unknown Source)
E/SQLiteOpenHelper( 8174): 	at com.mcafee.c.b.b(Unknown Source)
E/SQLiteOpenHelper( 8174): 	at com.mcafee.framework.b.a(Unknown Source)
E/SQLiteOpenHelper( 8174): 	at com.mcafee.app.t.run(Unknown Source)
E/SQLiteOpenHelper( 8174): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/SQLiteOpenHelper( 8174): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteOpenHelper( 8174): 	at com.mcafee.d.f.run(Unknown Source)
E/SQLiteOpenHelper( 8174): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteOpenHelper( 8174): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteOpenHelper( 8174): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteOpenHelper( 8174): 	at com.mcafee.d.c.run(Unknown Source)
W/SQLiteOpenHelper( 8174): Opened lockedapplications in read-only mode

```
