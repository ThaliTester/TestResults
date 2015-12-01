#### Test 52320939cae1769_thali03_LGE-LG-D855 Logs


```
--------- beginning of main
D/sensors_hal_Time( 1030): tsOffsetIs: Apps: 288764858991; DSPS: 9602841; Offset : -4304193763
,D/AndroidRuntime( 6101): 
D/AndroidRuntime( 6101): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 6101): CheckJNI is OFF
D/AndroidRuntime( 6101): Calling main entry com.android.commands.am.Am
--------- beginning of system
I/ActivityManager( 1030): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
V/SplitWindowPolicy( 1950): checkScreen => return. sourceIntent is null or not support SplitWindow component: ComponentInfo{co..../co.....MainActivity}
D/SplitInfo( 1030): new ActivitySplitInfo : ActivitySplitInfo [screenZone=0/ flag=0/ state=NATIVE]
V/ActivityStackEx( 1030): create ActivityStackEx
D/ActivityManager( 1030): setTaskToReturnTo : TaskRecord{2185b541 #2 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
D/ActivityManager( 1030): setTaskToReturnTo : TaskRecord{2185b541 #2 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
D/WindowStateEx( 1030): AppWindowTokenEx init.. 
E/GBMv2   (  334): DFP En is all cleared set to be enabled
D/QuickStatusbarLayout( 1396): Notification difference=198
D/QuickStatusbarLayout( 1396): child = android.widget.LinearLayout{2154d13 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
D/LgeAbsQuickCoverView( 1396): mCoverXPos: 0 ,mCoverYPos: 0
D/LgeAbsQuickCoverView( 1396): mCoverWidth: 0 ,mCoverHeight: 0
I/ActivityManager( 1030): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6121 uid=10311 gids={50311, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
D/AndroidRuntime( 6101): Shutting down VM
V/ActivityManager( 1030): Display changed displayId=0
D/DSDPConnection( 1855): Display #0 changed.
D/SplitWindowPolicy( 1950): updateActivityStateChanged: resumed=true, screenId=1, isScreenFull=true
D/SplitWindowPolicy( 1950): topRunningActivity=ActivityInfo{256e66e0 co.....MainActivity}, taskId=2, activityType=0, bIsSplit=false
D/SplitWindowPolicy( 1950): updateActivityStateChanged: resumed=false, screenId=1, isScreenFull=true
D/SplitWindowPolicy( 1950): topRunningActivity=ActivityInfo{49a3d99 co.....MainActivity}, taskId=2, activityType=0, bIsSplit=false
D/ContextHelper( 6121): convertTheme. context->name=com.test.thalitest themeResourceId=16973833
,I/WebViewFactory( 6121): Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,I/LibraryLoader( 6121): Loading: webviewchromium
,I/LibraryLoader( 6121): Time to load native libraries: 6 ms (timestamps 4641-4647)
I/LibraryLoader( 6121): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 6121): Binding Chromium to main looper Looper (main, tid 1) {2e638f45}
I/LibraryLoader( 6121): Expected native library version number "",actual native library version number ""
I/chromium( 6121): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 6121): Initializing chromium process, renderers=0
,W/art     ( 6121): Attempt to remove local handle scope entry from IRT, ignoring
W/chromium( 6121): [WARNING:dns_config_service_posix.cc(293)] Failed to read DnsConfig.
,V/AudioPolicyService(  316): registerClient() client 0xb1470160, uid 10311
,D/BluetoothManagerService( 1030): Message: 20
,D/BluetoothManagerService( 1030): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@24a17fc3:true
D/BluetoothAdapter( 6121): 711538330: getState() :  mService = null. Returning STATE_OFF
,W/chromium( 6121): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
I/chromium( 6121): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=32 off=46780 len=2953
I/chromium( 6121): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:33 off:229536 len:643667
I/Adreno-EGL( 6121): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 6121): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 6121): Build Date: 12/12/14 금
I/Adreno-EGL( 6121): Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
I/Adreno-EGL( 6121): Remote Branch: 
I/Adreno-EGL( 6121): Local Patches: 
I/Adreno-EGL( 6121): Reconstruct Branch: 
,W/chromium( 6121): [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
,W/chromium( 6121): [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
W/art     ( 6121): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 6121): onDetachedFromWindow called when already detached. Ignoring
D/SystemWebViewEngine( 6121): CordovaWebView is running on device made by: LGE
,W/art     ( 6121): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 6121): Attempt to remove local handle scope entry from IRT, ignoring
,D/OpenGLRenderer( 6121): Render dirty regions requested: true
I/OpenGLRenderer( 6121): Initialized EGL, version 1.4
D/OpenGLRenderer( 6121): Enabling debug mode 0
,D/Atlas   ( 6121): Validating map...
D/SplitWindow( 1030): check instance of lgWin Window{319b86a5 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,W/ActivityManager( 1030): Activity pause timeout for ActivityRecord{346e2ae6 u0 com.test.thalitest/.MainActivity t2}
,I/SystemUI[Framework]( 1030): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x0, pkg=com.android.systemui
,W/PhoneWindowManagerEx( 1030): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx( 1030): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx( 1030): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework]( 1030): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@17096aa,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework]( 1030): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
D/PhoneStatusBar( 1446): setSystemUiVisibility vis=0 mask=ffffffff oldVal=8000 newVal=0 diff=8000
I/[SystemUI]NavigationThemeResource( 1446): NavigationKey Color is changed(WHITE_WITH_SHADOW -> BLACK)
I/[SystemUI]NavigationThemeResource( 1446):  BarMode=0, Theme=WHITE, LightBackground=false (Transparent)
I/[SystemUI]NavigationThemeResource( 1446): , Keyguard show=false, IME shown=false, Panel expanded=false
D/LgDataFeature( 6121): LgDataFeature() Constructor: none
D/LgDataFeature( 6121): LgDataFeature() Constructor Done, null
,I/Timeline( 6121): Timeline: Activity_idle id: android.os.BinderProxy@3b4c7a4a time:295088
,I/ActivityManager( 1030): Displayed com.test.thalitest/.MainActivity: +633ms (total +772ms)
I/Timeline( 1030): Timeline: Activity_windows_visible id: ActivityRecord{346e2ae6 u0 com.test.thalitest/.MainActivity t2} time:295092
I/chromium( 6121): [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
I/chromium( 6121): 
D/JsMessageQueue( 6121): Set native->JS mode to OnlineEventsBridgeMode
D/jxcore_app_log( 6121): JniHelper::setJavaVM(0xb487c280), pthread_self() = -1435090176
D/JX-Cordova( 6121): jxcore cordova android initializing
E/GBMv2   (  334): DFP En is all cleared set to be enabled
E/GBMv2   (  334): Set value is all cleared set the max
,I/GBMv2   (  334): DFP Enabled. Ignore VFP set
W/jxcore-log( 6121): Initializing JXcore engine
W/jxcore-log( 6121): JXcore engine is ready
,W/jxcore-log( 6121): Starting JXcore engine
,W/.test.thalitest( 6121): type=1400 audit(0.0:146): avc: denied { ioctl } for path="socket:[7961]" dev="sockfs" ino=7961 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
W/.test.thalitest( 6121): type=1400 audit(0.0:147): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3222 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
,W/.test.thalitest( 6121): type=1400 audit(0.0:148): avc: denied { ioctl } for path="socket:[9565]" dev="sockfs" ino=9565 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
W/.test.thalitest( 6121): type=1400 audit(0.0:149): avc: denied { ioctl } for path="/cust" dev="mmcblk0p42" ino=2 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=dir
W/.test.thalitest( 6121): type=1400 audit(0.0:150): avc: denied { ioctl } for path="socket:[30761]" dev="sockfs" ino=30761 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
W/jxcore-log( 6121): Platform android
W/jxcore-log( 6121): 
W/jxcore-log( 6121): Process ARCH arm
W/jxcore-log( 6121): 
,I/jxcore-log( 6121): JXcore Cordova bridge is ready!
I/jxcore-log( 6121): 
W/jxcore-log( 6121): JXcore engine is started
,I/jxcore-log( 6121): Toggling radios to true
I/jxcore-log( 6121): 
,D/BluetoothManagerService( 1030): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1030): enable():  mBluetooth =null mBinding = false
D/BluetoothManagerService( 1030): Message: 1
D/BluetoothManagerService( 1030): MESSAGE_ENABLE: mBluetooth = null
,D/LocationManagerService( 1030): getAllProviders()=[passive, gps, network]
D/Ulp_jni ( 1030): JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
D/Ulp_jni ( 1030): JNI:system_update. Event-4
D/WifiService( 1030): New client listening to asynchronous messages
I/ActivityManager( 1030): Start proc com.android.bluetooth for service com.android.bluetooth/.btservice.AdapterService: pid=6184 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008, 4002, 1023} abi=armeabi-v7a
D/WifiServiceImplEx( 1030): setWifiEnabled: true pid=6121, uid=10311, package= com.test.thalitest, App Lable : ThaliTest
D/WifiService( 1030): setWifiEnabled: true pid=6121, uid=10311
E/WifiService( 1030): Invoking mWifiStateMachine.setWifiEnabled
,D/LocationManagerService( 1030): getAllProviders()=[passive, gps, network]
D/Ulp_jni ( 1030): JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 1,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
D/Ulp_jni ( 1030): JNI:system_update. Event-4
,E/WifiStateMachine( 1030):  InitialState CMD_START_SUPPLICANT 0 0
I/LGFTMITEM( 1030): [GET_FTM][id=6], offset=12288
D/WifiServiceImplEx( 1030): disconnect pid=6121, uid=10311, packageName=com.test.thalitest
D/WifiServiceImplEx( 1030): reconnect pid=6121, uid=10311, packageName=com.test.thalitest
E/WifiUtil( 1030): wfc_util_ffile_check_copy(): pid[1030] pDestFName[/data/misc/wifi/WCNSS_qcom_cfg.ini] pSourceFName[/system/etc/wifi/WCNSS_qcom_cfg.ini]
E/WifiUtil( 1030): wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
E/WifiUtil( 1030): wfc_util_ffile_check_copy(): pid[1030] pDestFName[/data/misc/wifi/WCNSS_qcom_wlan_nv.bin] pSourceFName[/system/etc/wifi/WCNSS_qcom_wlan_nv.bin]
E/WifiUtil( 1030): wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
I/WifiUtil( 1030): Intf0MacAddress=C49A027B60AC
E/WifiHW  ( 1030): unknown target_country: EU , set to default
E/WifiHW  ( 1030): [wifi_ensure_config_files] default country1 = GB
E/WifiHW  ( 1030): [wifi_ensure_config_files] default country2 = GB
I/jxcore-log( 6121): Radios toggled
I/jxcore-log( 6121): 
I/WifiUtil( 1030): gEnableBmps=1
,W/ResourcesManager( 6184): Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
W/ResourcesManager( 6184): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 6184): Asset path '/system/framework/com.qcom.bluetooth.jar' does not exist or contains no resources.
W/ResourcesManager( 6184): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,D/BluetoothAdapterApp( 6184): Loading JNI Library
,D/SoftapController(  311): Softap fwReload - Ok
,D/CommandListener(  311): Setting iface cfg
D/CommandListener(  311): Trying to bring down wlan0
D/CommandListener(  311): Clearing all IP addresses on wlan0
E/WifiHW  ( 1030): Cannot open "/system/etc/wifi/autojoinconfig.txt": No such file or directory
,D/libc-netbsd(  311): default dns: query_ipv6=0, query_ipv4=0
,D/Tethering( 1030): sendTetherStateChangedBroadcast 1, 0, 0
D/Tethering( 1030): InitialState.processMessage what=4
,D/DSQN    ( 1030): DNSproblemNotiEnabled is disabled ignore DNS fail CB
E/WifiStateMachine( 1030): Couldn't get getWiFiOffloadingIface : 
E/WifiStateMachine( 1030): useWiFiOffloading() : false
E/WifiStateMachine( 1030): CONFIG_LGE_WLAN_PATH : true
,I/ActivityManager( 1030): Start proc com.android.settings for broadcast com.android.settings/.deviceinfo.UsbSettingsReceiver: pid=6210 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
W/wpa_supplicant( 6226): type=1400 audit(0.0:151): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
W/wpa_supplicant( 6226): type=1400 audit(0.0:152): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
D/BluetoothAdapterApp( 6184): REFCOUNT: Constructed com.android.bluetooth.btservice.AdapterApp@5134389 Instance Count = 1
D/Tethering( 1030): sendTetherStateChangedBroadcast 0, 0, 0
D/BluetoothAdapterApp( 6184): onCreate
D/WifiMonitor( 1030): startMonitoring(wlan0) with mConnected = false
D/WifiMonitor( 1030): connecting to supplicant
,V/WfdStateTracker( 1950): WfdStateTracker handleDirectStateChangedEvent: 1
D/StatusBar.NetworkController( 1446): refreshViews: Data not connected!! Set no data type icon / Roaming
I/WifiServerServiceExt( 1030): WIFI_STATE_CHANGED_ACTION [2]
I/wpa_supplicant( 6226): Successfully initialized wpa_supplicant
,I/wpa_supplicant( 6226): rfkill: Cannot open RFKILL control device
I/wpa_supplicant( 6226): [LGE_PATCH] unset P2P_CAPABLE to ifname wlan0
D/ProfileConfigQcom( 6184): [BTUI] HeadsetService is supported
D/ProfileConfigQcom( 6184): Adding HeadsetService
D/ProfileConfigQcom( 6184): [BTUI] A2dpService is supported
D/ProfileConfigQcom( 6184): Adding A2dpService
D/ProfileConfigQcom( 6184): [BTUI] HidService is supported
D/ProfileConfigQcom( 6184): Adding HidService
D/ProfileConfigQcom( 6184): [BTUI] HealthService is supported
D/ProfileConfigQcom( 6184): Adding HealthService
D/LGBluetoothFeatureConfig( 6184): isSupportPan() :  mTargetOp=OPEN
D/ProfileConfigQcom( 6184): [BTUI] PanService is supported
D/ProfileConfigQcom( 6184): Adding PanService
D/ProfileConfigQcom( 6184): [BTUI] GattService is supported
D/ProfileConfigQcom( 6184): Adding GattService
D/ProfileConfigQcom( 6184): [BTUI] BluetoothMapService is supported
D/ProfileConfigQcom( 6184): Adding BluetoothMapService
D/ProfileConfigQcom( 6184): [BTUI] HeadsetClientService is NOT supported
W/ResourcesManager( 6210): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6210): Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
W/ResourcesManager( 6210): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 6210): Asset path '/system/framework/com.lge.bluetooth.jar' does not exist or contains no resources.
W/ResourcesManager( 6210): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
W/ResourcesManager( 6210): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,D/BluetoothManagerService( 1030): Message: 20
D/BluetoothManagerService( 1030): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@23c404cc:true
D/BluetoothAdapterState( 6184): make
I/LGFMServiceAdapter( 6184): [FM] LGFMServiceAdapter : create
I/bluedroid-qcom( 6184): init
I/BluetoothAdapterState( 6184): Entering OffState
,I/bte_conf( 6184): bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
I/bte_conf( 6184): bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
E/bt_osi_config( 6184): config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
I/bte_conf( 6184): bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
D/BTIF_CORE( 6184): [BTUI] lge_load_bluetooth_address
I/bluedroid-qcom( 6184): get_profile_interface socket
I/bluedroid-qcom( 6184): get_profile_interface map_client
W/bdaddr_loader( 6244): type=1400 audit(0.0:153): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
I/GKI_LINUX( 6184): gki_task_entry task_id=1 [BTIF] starting
W/bdaddr_loader( 6244): type=1400 audit(0.0:154): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
D/BluetoothAdapterProperties( 6184): Address is:58:3F:54:73:64:C0
D/BluetoothManagerService( 1030): BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
D/BluetoothManagerService( 1030): Message: 40
D/BluetoothManagerService( 1030): MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
D/BluetoothAdapterProperties( 6184): Name is: G3-1
,D/BluetoothManagerService( 1030): Bluetooth Adapter name changed to G3-1
I/bluedroid-qcom( 6184): config_hci_snoop_log
D/BluetoothManagerService( 1030): Stored Bluetooth name: G3-1
D/BluetoothManagerService( 1030): Calling onBluetoothServiceUp callbacks
D/BluetoothManagerService( 1030): Broadcasting onBluetoothServiceUp() to 7 receivers.
D/lge_bdaddr_loader( 6244): [BTUI] bdaddr_loader ::: START
D/lge_bdaddr_loader( 6244): [BTUI] bluetooth_load_bdaddress
I/LGFTMITEM( 6244): [GET_FTM][id=8], offset=16384
D/lge_bdaddr_loader( 6244): [BTUI] bdaddr to set in property : 58:3F:54:73:64:C0
E/lge_bdaddr_loader( 6244): [BTUI] bluetooth_load_bdaddress : OK => 58:3F:54:73:64:C0
D/lge_bdaddr_loader( 6244): [BTUI] bdaddr_loader ::: END
V/LGMDMManagerInternal( 6184): Create singleton instance
I/wpa_supplicant( 6226): rfkill: Cannot open RFKILL control device
,D/BluetoothAdapterState( 6184): CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
D/BluetoothAdapterProperties( 6184): Setting state to 11
I/BluetoothAdapterState( 6184): Bluetooth adapter state changed: 10-> 11
,I/LGBluetoothServiceJni( 6184): classInitNative: succeeds
D/BluetoothManagerService( 1030): Message: 60
D/BluetoothManagerService( 1030): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
D/BluetoothManagerService( 1030): Bluetooth State Change Intent: 10 -> 11
D/BluetoothBondStateMachine( 6184): make
D/LGBluetoothAPIService( 1950): [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
I/BluetoothBondStateMachine( 6184): StableState(): Entering Off State
D/BluetoothAdapterService( 6184): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@5501fa8
I/[SystemUI]BluetoothHandler( 1446): Receive : BluetoothAdapter.ACTION_STATE_CHANGED
D/LGBluetoothServiceAdapter( 6184): [BTUI] check adapter is available - false.
D/BluetoothAdapterService( 6184): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@5501fa8
D/LGBluetoothServiceAdapter( 6184): [BTUI] check adapter is available - true : set adapter available.
D/LGBluetoothSettingsDBObserver( 6184): [BTUI] register observer for LG device name DB
E/BluetoothAdapterService( 6184): File transfer profiles supported!!
,D/BluetoothHeadset( 1030): Proxy object connected
D/BluetoothHeadset( 1855): Proxy object connected
D/HeadsetService( 6184): Received start request. Starting profile...
I/LGBluetoothHeadsetServiceJni( 6184): classInitNative: succeeds
D/LGBluetoothHfpAdapter( 6184): Version 1.6
E/BluetoothAdapterService( 6184): File transfer profiles supported!!
D/BluetoothHeadset( 1855): Proxy object connected
D/LGBluetoothFeatureConfig( 6184): isPrivacyLogsEnabled : true
I/BluetoothHeadsetServiceJni( 6184): classInitNative: succeeds
E/BluetoothAdapterService( 6184): File transfer profiles supported!!
D/HeadsetStateMachine( 6184): make
D/BluetoothHeadset( 1855): Proxy object connected
E/BluetoothAdapterService( 6184): File transfer profiles supported!!
,E/BluetoothAdapterService( 6184): File transfer profiles supported!!
E/BluetoothAdapterService( 6184): File transfer profiles supported!!
E/BluetoothAdapterService( 6184): File transfer profiles supported!!
D/UsbSettingsReceiver( 6210): [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
D/UsbSettingsReceiver( 6210): [AUTORUN] sys.usb.config = ptp_only,adb
D/UsbSettingsReceiver( 6210): [AUTORUN] sys.usb.state = ptp_only,adb
D/UsbSettingsReceiver( 6210): [AUTORUN] persist.sys.usb.config = ptp_only,adb
,D/UsbSettingsReceiver( 6210): [AUTORUN] onReceive() : app userid = 0, current userid = 0
V/LGMDMManager( 6184): Create singleton instance
I/BluetoothAdapterState( 6184): Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
I/wpa_supplicant( 6226): [LGE_WLAN_PATCH]P2P 5GHz support level:2(0:no 1:gconly 2:gconly_UNII1 3:full)
D/UsbSettingsControl( 6210): [AUTORUN] getUsbConnected() : connected=true
D/UsbSettingsReceiver( 6210): [AUTORUN] onReceive() : availableList=[wlan0]
D/UsbSettingsReceiver( 6210): [AUTORUN] onReceive() : activeList=[]
D/UsbSettingsReceiver( 6210): [AUTORUN] onReceive() : errorList=[]
D/UsbSettingsControl( 6210): [AUTORUN] isAutorunTimer() : mAutorunChanging=false
D/UsbSettingsReceiver( 6210): [AUTORUN] onReceive() : TetherState Changed=wlan0
D/UsbSettingsControl( 6210): [AUTORUN] setTetherStatus() : status=false
I/wpa_supplicant( 6226): p2p0: CTRL-EVENT-AVOID-FREQ ranges=
I/wpa_supplicant( 6226): wlan0: CTRL-EVENT-SCAN-STARTED 
I/ActivityManager( 1030): Killing 5788:com.google.android.partnersetup/u0a8 (adj 15): empty #17
E/WifiStateMachine( 1030):  SupplicantStartingState CMD_SET_OPERATIONAL_MODE 1 0
E/WifiStateMachine( 1030):  SupplicantStartingState CMD_START_DRIVER 0 0
E/WifiStateMachine( 1030):  SupplicantStartingState CMD_SET_HIGH_PERF_MODE 0 0
E/WifiStateMachine( 1030):  DefaultState CMD_SET_HIGH_PERF_MODE 0 0
E/WifiStateMachine( 1030):  SupplicantStartingState CMD_DISCONNECT 0 0
D/LgDataFeature( 6184): LgDataFeature() Constructor: none
E/WifiStateMachine( 1030):  DefaultState CMD_DISCONNECT 0 0
D/LgDataFeature( 6184): LgDataFeature() Constructor Done, null
E/WifiStateMachine( 1030):  SupplicantStartingState CMD_RECONNECT 0 0
E/WifiStateMachine( 1030):  DefaultState CMD_RECONNECT 0 0
E/WifiStateMachine( 1030):  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1030):  DefaultState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1030):  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1030):  DefaultState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1030):  SupplicantStartingState SUP_CONNECTION_EVENT 0 0
D/WifiNative-wlan0( 1030): doString: [DRIVER MACADDR]
D/WifiNative-wlan0( 1030):    returned Macaddr = c4:9a:02:7b:60:ac
D/WifiStateMachine( 1030): MAC Addr from driver = c4:9a:02:7b:60:ac
D/WifiOffDelayIfNotUsed( 1030): setPowerSaveActivated(false)
D/WifiMonitor( 1030): Event [IFNAME=p2p0 CTRL-EVENT-AVOID-FREQ ranges=]
D/WifiMonitor( 1030): Dropping event because (p2p0) is stopped
D/WifiMonitor( 1030): Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1030): WifiMonitor:wlan0 cnt=0 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1030): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1030): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
,E/WifiStateMachine( 1030): Couldn't get getWiFiOffloadingIface : 
E/WifiStateMachine( 1030): useWiFiOffloading() : false
E/WifiStateMachine( 1030): CONFIG_LGE_WLAN_PATH : true
,W/libprocessgroup( 1030): failed to open /acct/uid_10008/pid_5788/cgroup.procs: No such file or directory
D/HeadsetStateMachine( 6184): max_hf_connections = 1
I/bluedroid-qcom( 6184): get_profile_interface handsfree
V/ToneGenerator( 6184): ToneGenerator constructor: streamType=8, volume=1.000000
V/AudioPolicyService(  316): registerClient() client 0xb1427da0, uid 1002
W/Settings( 1030): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1030): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
V/AudioPolicyManager(  316): getOutput() device 2, stream 8, samplingRate 0, format 0, channelMask 3, flags 0
V/AudioPolicyManagerEx(  316): AudioPolicyManagerEx: getOutputForDevice
V/AudioPolicyManagerEx(  316): getOutput() returns output 2
V/AudioSystem( 6184): getOutputSamplingRate() no output descriptor for output 2 in gOutputs
,V/AudioFlinger(  316): registerClient() client 0xb1251ad8, pid 6184
V/AudioSystem(  316): ioConfigChanged() event 0, ioHandle 2
V/AudioSystem(  316): ioConfigChanged() opening already existing output! 2
V/AudioSystem( 1030): ioConfigChanged() event 0, ioHandle 2
V/AudioSystem( 1030): ioConfigChanged() opening already existing output! 2
V/AudioSystem( 1446): ioConfigChanged() event 0, ioHandle 2
V/AudioSystem( 1446): ioConfigChanged() opening already existing output! 2
V/AudioSystem( 1855): ioConfigChanged() event 0, ioHandle 2
V/AudioSystem( 1855): ioConfigChanged() opening already existing output! 2
V/AudioSystem( 3261): ioConfigChanged() event 0, ioHandle 2
V/AudioSystem( 3261): ioConfigChanged() opening already existing output! 2
V/AudioSystem( 6184): ioConfigChanged() event 0, ioHandle 2
V/AudioSystem(  316): ioConfigChanged() event 0, ioHandle 4
V/AudioSystem(  316): ioConfigChanged() opening already existing output! 4
V/AudioSystem( 1446): ioConfigChanged() event 0, ioHandle 4
V/AudioSystem( 1446): ioConfigChanged() opening already existing output! 4
V/AudioSystem( 1030): ioConfigChanged() event 0, ioHandle 4
V/AudioSystem( 1030): ioConfigChanged() opening already existing output! 4
V/AudioSystem( 1855): ioConfigChanged() event 0, ioHandle 4
V/AudioSystem( 1855): ioConfigChanged() opening already existing output! 4
V/AudioSystem( 3261): ioConfigChanged() event 0, ioHandle 4
V/AudioSystem( 3261): ioConfigChanged() opening already existing output! 4
V/AudioSystem( 6184): ioConfigChanged() new output samplingRate 48000, format 0x5 channel mask 0x3 frameCount 960 latency 50
V/AudioSystem( 6184): ioConfigChanged() event 0, ioHandle 4
V/AudioSystem( 6184): ioConfigChanged() new output samplingRate 48000, format 0x1 channel mask 0x3 frameCount 960 latency 80
V/ToneGenerator( 6184): Create Track: 0xb4928a80
V/AudioTrack( 6184): set(): streamType 8, sampleRate 0, format 0x1, channelMask 0x1, frameCount 0, flags #4, notificationFrames 0, sessionId 0, transferType 1
V/AudioTrack( 6184): set() streamType 8, sampleRate 0, format 1, frameCount 0, flags 0004
V/AudioPolicyManager(  316): getOutputForAttr() usage=3, content=4, tag= flags=00000000
V/AudioPolicyManager(  316): getOutputForAttr() device 2, samplingRate 0, format 0, channelMask 3, flags 0
V/AudioPolicyManagerEx(  316): AudioPolicyManagerEx: getOutputForDevice
V/AudioPolicyManagerEx(  316): getOutput() returns output 2
D/WifiNative-wlan0( 1030): doBoolean: SET update_config 1
I/AudioFlinger(  316): isAudioPlaybackHookOn() false
D/UsbSettingsReceiver( 6210): [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
D/UsbSettingsReceiver( 6210): [AUTORUN] sys.usb.config = ptp_only,adb
V/AudioPolicyManager(  316): getOutputForAttr() usage=3, content=4, tag= flags=00000000
D/StatusBar.NetworkController( 1446): refreshViews: Data not connected!! Set no data type icon / Roaming
V/AudioPolicyManager(  316): getOutputForAttr() device 2, samplingRate 48000, format 1, channelMask 1, flags 4
V/AudioPolicyManagerEx(  316): AudioPolicyManagerEx: getOutputForDevice
V/AudioPolicyManagerEx(  316): getOutput() returns output 2
D/UsbSettingsReceiver( 6210): [AUTORUN] sys.usb.state = ptp_only,adb
V/AudioSystem( 6184): getLatency() output 2, latency 50
V/AudioSystem( 6184): getFrameCount() output 2, frameCount 960
D/UsbSettingsReceiver( 6210): [AUTORUN] persist.sys.usb.config = ptp_only,adb
D/WfdService( 1950): Waiting for WifiP2p enabling
V/AudioTrack( 6184): createTrack_l() output 2 afLatency 50
V/AudioFlinger(  316): [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
V/AudioFlinger(  316): [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
V/AudioFlinger(  316): [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
V/AudioFlinger(  316): [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
V/AudioFlinger(  316): createTrack() lSessionId: 16
,I/WifiServerServiceExt( 1030): WIFI_STATE_CHANGED_ACTION [3]
I/WifiServerServiceExt( 1030): batteryPsActivateMsgHandler : state:0 event:3
D/UsbSettingsReceiver( 6210): [AUTORUN] onReceive() : app userid = 0, current userid = 0
V/AudioTrack( 6184): AUDIO_OUTPUT_FLAG_FAST successful; frameCount 480
V/AudioFlinger(  316): acquiring 16 from 6184, for 6184
V/AudioFlinger(  316):  added new entry for 16
V/ToneGenerator( 6184): ToneGenerator INIT OK, time: 298096
D/BluetoothAdapterService( 6184): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@5501fa8
D/HeadsetStateMachine( 6184): Enter Disconnected: -2, size: 0
D/HeadsetPhoneState( 6184): [BTUI] listenForPhoneState : start = false
D/LGBluetoothHfpManager( 6184): [BTUI] listenForMultiSimPhoneState : start = false
D/HeadsetStateMachine( 6184): [BTUI] change sampling rate to 8000 when device is disconnected
V/AudioFlinger(  316): setParameters(): io 0, keyvalue bt_samplerate=8000, calling pid 6184
D/audio_hw_primary(  316): adev_set_parameters: enter: bt_samplerate=8000
V/voice   (  316): voice_set_parameters: enter: bt_samplerate=8000
V/compress_voip(  316): voice_extn_compress_voip_set_parameters: enter: bt_samplerate=8000
V/compress_voip(  316): voice_extn_compress_voip_set_parameters: exit
V/voice   (  316): voice_set_parameters: exit with code(0)
V/msm8974_platform_lge(  316): LGE_platform_set_parameters: enter: bt_samplerate=8000
V/msm8974_platform(  316): platform_set_parameters: enter: bt_samplerate=8000
V/msm8974_platform(  316): platform_set_parameters: exit with code(0)
V/lge_audio_loopback(  316): lge_platform_set_loopback_parameters: enter: 
V/audio_hw_primary(  316): adev_set_parameters: exit with code(0)
E/audio_a2dp_hw(  316): adev_set_parameters: ERROR: set param called even when stream out is null
D/BluetoothAdapterService( 6184): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@5501fa8
V/ToneGenerator( 6184): ToneGenerator destructor
V/ToneGenerator( 6184): stopTone
V/ToneGenerator( 6184): Delete Track: 0xb4928a80
D/WifiNative-wlan0( 1030): SET update_config 1: returned true
D/WifiConfigStore( 1030): Loading config and enabling all networks 
D/WifiNative-wlan0( 1030): doString: [LIST_NETWORKS]
D/WifiNative-wlan0( 1030):    returned network id / ssid / bssid / flags 0	NG700	any	
V/AudioTrack( 6184): ~AudioTrack, releasing session id from 6184 on behalf of 6184
V/AudioFlinger(  316): releasing 16 from 6184 for 6184
V/AudioFlinger(  316):  decremented refcount to 0
V/AudioFlinger(  316): purging stale effects
V/AudioPolicyService(  316): AudioCommandThread() adding release output 2
V/AudioPolicyService(  316): inserting command: 6 at index 0, num commands 0
,V/AudioPolicyService(  316): AudioCommandThread() waking up
V/AudioPolicyService(  316): AudioCommandThread() processing release output 2
V/AudioPolicyManager(  316): releaseOutput() 2
V/AudioPolicyService(  316): AudioCommandThread() going to sleep
V/AudioFlinger(  316): PlaybackThread::Track destructor
V/AudioFlinger(  316): removeClient_l() pid 6184, calling pid 316
D/UsbSettingsControl( 6210): [AUTORUN] getUsbConnected() : connected=true
D/UsbSettingsReceiver( 6210): [AUTORUN] onReceive() : availableList=[]
D/UsbSettingsReceiver( 6210): [AUTORUN] onReceive() : activeList=[]
D/UsbSettingsReceiver( 6210): [AUTORUN] onReceive() : errorList=[]
D/UsbSettingsControl( 6210): [AUTORUN] isAutorunTimer() : mAutorunChanging=false
D/UsbSettingsControl( 6210): [AUTORUN] setTetherStatus() : status=false
D/BluetoothA2dp( 1030): Proxy object connected
D/A2dpService( 6184): Received start request. Starting profile...
I/BluetoothAvrcpServiceJni( 6184): classInitNative: succeeds
E/WifiConfigStore( 1030): readNetworkVariablesFromSupplicantFile key=psk
V/Avrcp   ( 6184): make
D/Avrcp   ( 6184): [BTUI] Use Native AVRCP : init jni
I/bluedroid-qcom( 6184): get_profile_interface avrcp
E/WifiConfigStore( 1030): readNetworkVariableFromSupplicantFile ssid=["NG700"] key=psk
,E/WifiConfigStore( 1030): Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
I/ActivityManager( 1030): Start proc com.lge.formmanager for broadcast com.lge.formmanager/.FormServiceReceiver: pid=6252 uid=10026 gids={50026, 9997, 3003, 1028} abi=armeabi-v7a
,D/WifiStateMachine( 1030): enableVerboseLogging : level 2
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
V/AudioManager( 6184): registerRemoteController: size of Media player list: 0
D/WifiNative-wlan0( 1030): SET config_methods physical_display virtual_push_button: returned true
D/WifiNative-wlan0( 1030): doBoolean: SET device_type 10-0050F204-5
D/WifiNative-wlan0( 1030): SET device_type 10-0050F204-5: returned true
E/AudioManager( 6184): No RCC entry present to update
E/RemoteController( 6184): Cannot set synchronization mode on an unregistered RemoteController
W/Settings( 6001): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WfdsService( 1950): Supplicant Connection state is changed : true
D/WfdsService( 1950): DefaultState - WIFI_SUPPLICANT_CONNECTED
D/WfdsService( 1950): Set the WFDS Monitor: true
D/WifiStateMachine( 1030): Setting OUI to DA-A1-19
D/WifiNative-wlan0( 1030): doBoolean: SCAN_INTERVAL 120
D/WifiNative-wlan0( 1030): SCAN_INTERVAL 120: returned true
D/WifiNative-HAL( 1030): Setting external_sim to 1
D/WifiNative-wlan0( 1030): doBoolean: SET external_sim 1
D/WifiNative-wlan0( 1030): SET external_sim 1: returned true
I/WifiNative-HAL( 1030): startHal
I/BluetoothAvrcpQcomServiceJni( 6184): classInitQcomNative: succeeds
E/wifi    ( 1030): getStaticLongField sWifiHalHandle 0x9892c8dc
E/WifiHAL ( 1030): Could not connect handle
D/wifi    ( 1030): halHandle = 0x0, mVM = 0xb487c280, mCls = 0x401c36
I/WifiNative-HAL( 1030): Could not start hal
D/WifiStateMachine( 1030): Setting OUI to DA-A1-19
I/WifiNative-HAL( 1030): startHal
E/wifi    ( 1030): getStaticLongField sWifiHalHandle 0x9892c85c
E/WifiHAL ( 1030): Could not connect handle
D/wifi    ( 1030): halHandle = 0x0, mVM = 0xb487c280, mCls = 0xb01c0e
I/WifiNative-HAL( 1030): Could not start hal
D/WifiNative-wlan0( 1030): doBoolean: STA_AUTOCONNECT 1
D/LGBluetoothAvrcpQcomAdapter( 6184): [BTUI] Use QCOM AVRCP 1.5 : init jni, browsing = false
I/BluetoothAvrcpQcomServiceJni( 6184): initQcomNative: succeeds
D/WifiNative-wlan0( 1030): STA_AUTOCONNECT 1: returned true
D/WifiNative-wlan0( 1030): doBoolean: DRIVER BTCOEXSCAN-STOP
I/wpa_supplicant( 6226): wpa_driver_nl80211_ext_driver_cmd BTCOEXSCAN-STOP
D/WifiNative-wlan0( 1030): DRIVER BTCOEXSCAN-STOP: returned true
,D/WfdsMonitor( 1950): WfdsMonitorThread create
D/WfdsMonitor( 1950): WFDS Monitor is created and started
D/WfdsService( 1950): WiFi: Supplicant connection re-established
E/CtrlSupplicant( 1950): Access OK "@android:wpa_wlan0"
D/LGBluetoothAvrcpQcomAdapter( 6184): [BTUI] [+] updateMediaPlayerInfo
I/StatusBar.NetworkController( 1446): networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1446): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1446): refreshViews: Data not connected!! Set no data type icon / Roaming
D/WifiHS20( 1030): hidePasspointNotification off =false
D/WifiNative-wlan0( 1030): doBoolean: DRIVER RXFILTER-STOP
I/wpa_supplicant( 6226): wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
W/Settings( 1030): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1030): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1030): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
E/CtrlSupplicant( 1950): Succeed to open control connection
E/CtrlSupplicant( 1950): Succeed to open monitor connection
D/WifiNative-wlan0( 1030): DRIVER RXFILTER-STOP: returned true
D/WifiNative-wlan0( 1030): doBoolean: DRIVER RXFILTER-REMOVE 3
I/wpa_supplicant( 6226): wpa_driver_nl80211_ext_driver_cmd RXFILTER-REMOVE 3
D/WfdsMonitor( 1950): Supplicant connection established
D/WfdsService( 1950): Connected to the supplicant for wfds
,D/WifiNative-wlan0( 1030): DRIVER RXFILTER-REMOVE 3: returned true
D/WifiNative-wlan0( 1030): doBoolean: DRIVER RXFILTER-START
I/wpa_supplicant( 6226): wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
D/WifiNative-wlan0( 1030): DRIVER RXFILTER-START: returned true
D/WifiNative-wlan0( 1030): doBoolean: DRIVER RXFILTER-STOP
I/wpa_supplicant( 6226): wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
D/WifiNative-wlan0( 1030): DRIVER RXFILTER-STOP: returned true
D/WifiNative-wlan0( 1030): doBoolean: DRIVER RXFILTER-REMOVE 2
I/wpa_supplicant( 6226): android_multicast_filter_startstop : multicast filter set
D/WifiNative-wlan0( 1030): DRIVER RXFILTER-REMOVE 2: returned true
D/WifiNative-wlan0( 1030): doBoolean: DRIVER RXFILTER-START
I/wpa_supplicant( 6226): wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
D/WifiNative-wlan0( 1030): DRIVER RXFILTER-START: returned true
E/WifiNative: ( 1030): [298,176,237 us] RECONNECT  stack:logDbg - reconnect - enter - invokeEnterMethods - performTransitions
D/WifiNative-wlan0( 1030): doBoolean: RECONNECT
D/WifiNative-wlan0( 1030): RECONNECT: returned true
D/WifiNative-wlan0( 1030): doString: [STATUS]
D/WifiMonitor( 1030): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
E/WifiMonitor( 1030): WifiMonitor:wlan0 cnt=1 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
D/WifiNative-wlan0( 1030):    returned wpa_state=SCANNING p2p_device_address=02:9a:02:7b:60:ac address=c4:9a:02:7b:60:ac uuid=530d3fd0-1ba3-5409-a336-ff4e42af59a2
D/WifiNative-wlan0( 1030): doBoolean: DRIVER SETSUSPENDMODE 1
I/wpa_supplicant( 6226): wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 1
D/WifiNative-wlan0( 1030): DRIVER SETSUSPENDMODE 1: returned true
D/WifiNative-wlan0( 1030): doBoolean: SET ps 1
D/WifiNative-wlan0( 1030): SET ps 1: returned true
D/LGWifiP2pService( 1030): P2pDisabledState{ when=0 what=131203 target=com.android.internal.util.StateMachine$SmHandler }
D/CommandListener(  311): Setting iface cfg
D/CommandListener(  311): Trying to bring up p2p0
D/WifiMonitor( 1030): startMonitoring(p2p0) with mConnected = true
D/LGWifiP2pService( 1030): P2pEnablingState
D/LGWifiP2pService( 1030): P2pEnablingState{ when=0 what=147457 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1030): P2p socket connection successful
D/LGWifiP2pService( 1030): P2pEnabledState
,D/WifiService( 1030): New client listening to asynchronous messages
D/LGWifiP2pService( 1030): sending p2p connection changed broadcast
E/WifiStateMachine( 1030):  DisconnectedState CMD_SET_OPERATIONAL_MODE 1 0
E/WifiStateMachine( 1030):  DisconnectedState CMD_START_DRIVER 0 0
E/WifiStateMachine( 1030):  ConnectModeState CMD_START_DRIVER 0 0
E/WifiStateMachine( 1030):  DriverStartedState CMD_START_DRIVER 0 0
,E/WifiStateMachine( 1030):  DisconnectedState what:132106 1 0
E/WifiStateMachine( 1030):  ConnectModeState what:132106 1 0
D/WifiScanningService( 1030): SCAN_AVAILABLE : 3
E/WifiStateMachine( 1030):  DriverStartedState what:132106 1 0
D/RttService( 1030): SCAN_AVAILABLE : 3
I/WifiServerServiceExt( 1030): setWifiDualbandAPConnection band : 1
D/WifiScanningService( 1030): DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
I/WifiNative-HAL( 1030): startHal
E/wifi    ( 1030): getStaticLongField sWifiHalHandle 0x94e3799c
E/wpa_supplicant( 6226): nWIFIDualbandAPConnection: 1
E/WifiHAL ( 1030): Could not connect handle
D/wifi    ( 1030): halHandle = 0x0, mVM = 0xb487c280, mCls = 0x401ae6
I/WifiNative-HAL( 1030): Could not start hal
E/WifiScanningService( 1030): could not start HAL
D/RttService( 1030): DefaultState got{ when=-1ms what=160512 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiStateMachine( 1030):  DisconnectedState what:132096 -100 0
E/WifiStateMachine( 1030):  ConnectModeState what:132096 -100 0
E/WifiStateMachine( 1030):  DriverStartedState what:132096 -100 0
I/WifiServerServiceExt( 1030): set CMD_DISCONNECT_RSSI_LVL : -100
E/wpa_supplicant( 6226): disconnect_rssi_lvl: -100
V/WfdStateTracker( 1950): WfdStateTracker handleDirectStateChangedEvent: 2
E/WifiStateMachine( 1030):  DisconnectedState CMD_SET_COUNTRY_CODE 1 0 cz
E/WifiStateMachine( 1030):  ConnectModeState CMD_SET_COUNTRY_CODE 1 0 cz
D/WfdsService( 1950): WifiP2pState is changed : true
E/WifiStateMachine( 1030):  DriverStartedState CMD_SET_COUNTRY_CODE 1 0 cz
D/WfdsService( 1950): Receive the WFDS_ENABLE Method
D/WfdsService( 1950): Set the WFDS Monitor: true
D/WfdsService( 1950): Connected to the supplicant for wfds
D/WifiNative-wlan0( 1030): doBoolean: DRIVER COUNTRY CZ
D/WfdsJNI ( 1950): doCommand: WFDS_SET TRUE
I/wpa_supplicant( 6226): wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
I/wpa_supplicant( 6226): wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
I/wpa_supplicant( 6226): [LGE_PATCH] driver_cmd() country:CZ
I/wpa_supplicant( 6226): WFDS: wfds_supplicant_wfds_cmd: cmd = SET TRUE
I/wpa_supplicant( 6226): p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
D/WfdsJNI ( 1950): doCommand: WFDS_GET_MAC_ADDRESS
I/wpa_supplicant( 6226): WFDS: wfds_supplicant_wfds_cmd: cmd = GET_MAC_ADDRESS
I/wpa_supplicant( 6226): p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
D/WfdsMonitor( 1950): Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
D/WfdsMonitor( 1950): Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
D/WfdsJNI ( 1950): doCommand: IFNAME=wlan0 GET_CAPABILITY channels
D/WifiMonitor( 1030): Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
E/WifiMonitor( 1030): WifiMonitor:wlan0 cnt=2 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
E/WifiMonitor( 1030): handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
D/WfdsService( 1950): selectPreferredScanChannel [36]
E/WifiMonitor( 1030): handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
D/WfdsService( 1950): STATE : WfdsEnabledState - enter: this device mac 02:9a:02:7b:60:ac
D/WifiMonitor( 1030): Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
E/WifiMonitor( 1030): WifiMonitor:p2p0 cnt=3 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
E/WifiMonitor( 1030): handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
E/WifiMonitor( 1030): handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
D/WifiMonitor( 1030): Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
E/WifiMonitor( 1030): WifiMonitor:p2p0 cnt=4 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
E/WifiMonitor( 1030): handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
E/WifiMonitor( 1030): handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
D/WifiNative-p2p0( 1030): doBoolean: SET pe,rsistent_reconnect 1
D/WifiNative-wlan0( 1030): DRIVER COUNTRY CZ: returned true
E/WifiStateMachine( 1030):  DisconnectedState CMD_SET_FREQUENCY_BAND 0 0
E/WifiStateMachine( 1030):  ConnectModeState CMD_SET_FREQUENCY_BAND 0 0
E/WifiStateMachine( 1030):  DriverStartedState CMD_SET_FREQUENCY_BAND 0 0
D/WifiNative-wlan0( 1030): doBoolean: DRIVER SETBAND 0
I/wpa_supplicant( 6226): wpa_driver_nl80211_ext_driver_cmd SETBAND 0 - interface name wlan0
I/wpa_supplicant( 6226): wlan0: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
D/WifiMonitor( 1030): Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN]
E/WifiMonitor( 1030): WifiMonitor:wlan0 cnt=5 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
E/WifiMonitor( 1030): handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
E/WifiMonitor( 1030): handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
D/WifiNative-wlan0( 1030): DRIVER SETBAND 0: returned true
D/WifiNative-wlan0( 1030): doBoolean: BSS_FLUSH 0
D/WifiNative-wlan0( 1030): BSS_FLUSH 0: returned true
D/WifiNative-wlan0( 1030): doBoolean: SCAN
D/WifiNative-wlan0( 1030): SCAN: returned false
E/WifiStateMachine( 1030):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 1 0 rt=298233  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
D/WifiNative-p2p0( 1030): SET persistent_reconnect 1: returned true
D/WfdsService( 1950): WIFI_P2P_CONNECTION_CHANGED_ACTION
D/WifiNative-p2p0( 1030): doBoolean: SET device_name G3-1
D/WifiNative-p2p0( 1030): SET device_name G3-1: returned true
D/LGWifiP2pService( 1030): [LGE_P2P] initializeP2pSettings() check postfix
D/LGWifiP2pService( 1030): before postfix = G3-1
D/WifiServerServiceExt( 1030): postfix byte check : 4
D/LGWifiP2pService( 1030): after postfix = G3-1
D/WifiNative-p2p0( 1030): doBoolean: SET p2p_ssid_postfix -G3-1
D/WfdsService( 1950): isConnected: false
D/WifiNative-p2p0( 1030): SET p2p_ssid_postfix -G3-1: returned true
D/WifiNative-p2p0( 1030): doBoolean: SET device_type 10-0050F204-5
D/WifiNative-p2p0( 1030): SET device_type 10-0050F204-5: returned true
D/WifiNative-p2p0( 1030): doBoolean: SET config_methods virtual_push_button physical_display keypad
D/WifiNative-p2p0( 1030): SET config_methods virtual_push_button physical_display keypad: returned true
D/WifiNative-p2p0( 1030): doBoolean: P2P_SET conc_pref p2p
D/WifiNative-p2p0( 1030): P2P_SET conc_pref p2p: returned true
D/WifiNative-HAL( 1030): p2pGetDeviceAddress
D/WifiNative-HAL( 1030): p2pGetDeviceAddress returning 02:9a:02:7b:60:ac
I/StatusBar.NetworkController( 1446): networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1446): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1446): refreshViews: Data not connected!! Set no data type icon / Roaming
W/Settings( 1030): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1030): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1030): NETWORK_STATE_CHANGED_ACTION [SCANNING]
D/LGWifiP2pService( 1030): DeviceAddress: 02:9a:02:7b:60:ac
D/WifiNative-p2p0( 1030): doBoolean: P2P_FLUSH
D/WifiNative-p2p0( 1030): P2P_FLUSH: returned true
D/WifiNative-p2p0( 1030): doBoolean: P2P_SERVICE_FLUSH
D/WifiNative-p2p0( 1030): P2P_SERVICE_FLUSH: returned true
I/WfdStateTracker( 1950): handleP2pThisDeviceChanged
D/WifiNative-p2p0( 1030): doString: [LIST_NETWORKS]
D/WfdsService( 1950): WIFI_P2P_THIS_DEVICE_CHANGED_ATCION
D/WfdsService( 1950): Update P2p Interface State: 3
D/WifiNative-p2p0( 1030):    returned network id / ssid / bssid / flags
D/WifiNative-p2p0( 1030): doBoolean: SAVE_CONFIG
E/WifiStateMachine( 1030):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 1 0 rt=298246  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
E/WifiStateMachine( 1030):  DisconnectedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
E/WifiStateMachine( 1030):  ConnectModeState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
E/WifiStateMachine( 1030):  DriverStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
E/WifiStateMachine( 1030):  SupplicantStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
E/WifiStateMachine( 1030):  DefaultState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
D/WifiServerServiceExt( 1030): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1030): setSupplicantStateSCANNING
D/WifiNative-p2p0( 1030): SAVE_CONFIG: returned true
D/LGWifiP2pService( 1030): sending p2p persistent groups changed broadcast
D/LGWifiP2pService( 1030): InactiveState
D/LGWifiP2pService( 1030): InactiveState{ when=-25ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1030): P2pEnabledState{ when=-25ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-p2p0( 1030): doBoolean: DRIVER COUNTRY CZ
I/wpa_supplicant( 6226): wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
I/wpa_supplicant( 6226): p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
I/wpa_supplicant( 6226): [LGE_PATCH] driver_cmd() country:CZ
I/wpa_supplicant( 6226): p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
I/wpa_supplicant( 6226): p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
D/WfdsMonitor( 1950): Event [CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
D/WfdsMonitor( 1950): Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
D/WfdsMonitor( 1950): Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
D/WifiMonitor( 1030): Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
E/WifiMonitor( 1030): WifiMonitor:p2p0 cnt=6 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
E/WifiMonitor( 1030): handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
E/WifiMonitor( 1030): handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
D/WifiNative-p2p0( 1030): DRIVER COUNTRY CZ: returned true
D/LGWifiP2pService( 1030): InactiveState{ when=-13ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1030): P2pEnabledState{ when=-13ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1030): InactiveState{ when=0 what=139287 arg2=1 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1030): P2pEnabledState{ when=0 what=139287 arg2=1 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1030): DefaultState{ when=-1ms what=139287 arg2=1 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1030): InactiveState{ when=-1ms what=139285 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiMonitor( 1030): Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
E/WifiMonitor( 1030): WifiMonitor:p2p0 cnt=7 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
E/WifiMonitor( 1030): handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
E/WifiMonitor( 1030): handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
D/WifiMonitor( 1030): Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
E/WifiMonitor( 1030): WifiMonitor:p2p0 cnt=8 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
E/WifiMonitor( 1030): handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
E/WifiMonitor( 1030): handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
D/LGWifiP2pService( 1030): P2pEnabledState{ when=-1ms what=139285 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1030): DefaultState{ when=-1ms what=139285 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1030): InactiveState{ when=-1ms what=139287 arg2=1 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1030): P2pEnabledState{ when=-1ms what=139287 arg2=1 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1030): DefaultState{ when=-2ms what=139287 arg2=1 target=com.android.internal.util.StateMachine$SmHandler }
,D/LGWifiP2pService( 1030): InactiveState{ when=-2ms what=139283 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1030): P2pEnabledState{ when=-2ms what=139283 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1030): DefaultState{ when=-2ms what=139283 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiServerServiceExt( 1030): No p2p device connected
W/WfdsService( 1950): DefaultState - msg [9441285] is not handled
V/SIM_STK ( 1030): Menu title from STK is T-Mobile
V/SIM_STK ( 1030): Menu title from STK is T-Mobile
I/ActivityManager( 1030): Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=6277 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,W/FormManager( 6252): Network not available. Please check & try again.
V/FormManager( 6252): Network unavailable.
,V/FormManager( 6252): Network unavailable.
W/ActivityManager( 1030): getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
D/LGBluetoothAvrcpQcomAdapter( 6184): [BTUI] installed app name: Music
D/LGBluetoothAvrcpQcomAdapter( 6184): [BTUI] installed app name: Google Play Music
D/LGBluetoothAvrcpQcomAdapter( 6184): [BTUI] === MediaPlayerInfo (playerId:0) ===
D/LGBluetoothAvrcpQcomAdapter( 6184): [BTUI]          displayName: Music
D/LGBluetoothAvrcpQcomAdapter( 6184): [BTUI]          packageName: com.lge.music
,D/LGBluetoothAvrcpQcomAdapter( 6184): [BTUI]          playState: 2 (PAUSED)
D/LGBluetoothAvrcpQcomAdapter( 6184): [BTUI] === MediaPlayerInfo (playerId:1) ===
D/LGBluetoothAvrcpQcomAdapter( 6184): [BTUI]          displayName: Google Play Music
D/LGBluetoothAvrcpQcomAdapter( 6184): [BTUI]          packageName: com.google.android.music
D/LGBluetoothAvrcpQcomAdapter( 6184): [BTUI]          playState: 2 (PAUSED)
D/LGBluetoothAvrcpQcomAdapter( 6184): [BTUI] [-] updateMediaPlayerInfo
I/BluetoothA2dpServiceJni( 6184): classInitNative
I/BluetoothA2dpServiceJni( 6184): classInitNative: succeeds
D/A2dpStateMachine( 6184): make
I/bluedroid-qcom( 6184): get_profile_interface a2dp
I/GKI_LINUX( 6184): gki_task_entry task_id=2 [A2DP-MEDIA] starting
I/LGBluetoothA2dpServiceJni( 6184): classInitNative: succeeds
I/LGBluetoothA2dpAdapter( 6184): [BTUI] getInstance : create [LGBluetoothA2dpAdapter]
D/BluetoothAdapterService( 6184): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@5501fa8
I/BluetoothHidServiceJni( 6184): classInitNative: succeeds
D/A2dpStateMachine( 6184): Enter Disconnected: -2
D/HidService( 6184): Received start request. Starting profile...
I/bluedroid-qcom( 6184): get_profile_interface hidhost
D/BluetoothAdapterService( 6184): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@5501fa8
I/BluetoothHealthServiceJni( 6184): classInitNative: succeeds
D/HealthService( 6184): Received start request. Starting profile...
I/bluedroid-qcom( 6184): get_profile_interface health
I/LGBluetoothHealthServiceJni( 6184): classInitNative: succeeds
D/BluetoothAdapterService( 6184): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@5501fa8
I/BluetoothPanServiceJni( 6184): classInitNative(L105): succeeds
D/PanService( 6184): Received start request. Starting profile...
,D/BluetoothPanServiceJni( 6184): initializeNative(L110): pan
I/bluedroid-qcom( 6184): get_profile_interface pan
I/LGBluetoothPanAdapter( 6184): [BTUI] getInstance : create [LGBluetoothPanAdapter]
D/BluetoothAdapterService( 6184): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@5501fa8
I/BtGatt.JNI( 6184): classInitNative(L901): classInitNative: Success!
I/ActivityManager( 1030): Killing 5451:com.lge.appbox.client/u0a11 (adj 15): empty #17
D/BtGatt.DebugUtils( 6184): handleDebugAction() action=null
D/BtGatt.GattService( 6184): Received start request. Starting profile...
D/BtGatt.GattService( 6184): start()
I/bluedroid-qcom( 6184): get_profile_interface gatt
D/BtGatt.AdvertiseManager( 6184): advertise manager created
D/PCSuite ( 6277): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,E/WifiMonitor( 1030): WifiMonitor:wlan0 cnt=9 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
E/WifiMonitor( 1030): handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
D/WifiMonitor( 1030): Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
E/WifiMonitor( 1030): WifiMonitor:wlan0 cnt=10 dispatchEvent: WPS-AP-AVAILABLE 
W/WifiMonitor( 1030): couldn't identify event type - WPS-AP-AVAILABLE 
E/wpa_supplicant( 6226): USIM:  scard_init function
,E/WifiStateMachine( 1030):  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=0 bcn=0
E/WifiStateMachine( 1030):  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=0 bcn=0
E/WifiStateMachine( 1030):  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=0 bcn=0
I/wpa_supplicant( 6226): Trying to associate with SSID 'NG700'
E/WifiStateMachine( 1030):  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=0 bcn=0
I/WifiNative-HAL( 1030): startHal
E/wifi    ( 1030): getStaticLongField sWifiHalHandle 0x9892c8cc
E/WifiHAL ( 1030): Could not connect handle
D/wifi    ( 1030): halHandle = 0x0, mVM = 0xb487c280, mCls = 0x70207a
I/WifiNative-HAL( 1030): Could not start hal
D/WifiNative-wlan0( 1030): doString: [BSS RANGE=0- MASK=0x21987]
D/WifiMonitor( 1030): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
E/WifiMonitor( 1030): WifiMonitor:wlan0 cnt=11 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
W/libprocessgroup( 1030): failed to open /acct/uid_10011/pid_5451/cgroup.procs: No such file or directory
,D/BluetoothAdapterService( 6184): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@5501fa8
,E/WifiStateMachine( 1030):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 11 0 rt=298503  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
D/BluetoothAdapterService( 6184): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@5501fa8
I/LGBluetoothMapAdapter( 6184): [BTUI] getInstance : create [LGBluetoothMapAdapter]
V/BluetoothMapService( 6184): BluetoothMapBinder()
D/BluetoothMapService( 6184): Received start request. Starting profile...
D/BluetoothMapService( 6184): start()
I/StatusBar.NetworkController( 1446): networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1446): mWifiConnected = false, mWifiLevel = 0
W/Settings( 1030): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1030): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1030): NETWORK_STATE_CHANGED_ACTION [SCANNING]
D/StatusBar.NetworkController( 1446): refreshViews: Data not connected!! Set no data type icon / Roaming
,I/wpa_supplicant( 6226): wlan0: Associated with c0:ff:d4:d3:aa:48
E/WifiStateMachine( 1030):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 11 0 rt=298519  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
D/WifiMonitor( 1030): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
E/WifiMonitor( 1030): WifiMonitor:wlan0 cnt=12 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
D/WifiMonitor( 1030): Event [IFNAME=wlan0 Associated with c0:ff:d4:d3:aa:48]
E/WifiMonitor( 1030): WifiMonitor:wlan0 cnt=13 dispatchEvent: Associated with c0:ff:d4:d3:aa:48
D/WifiMonitor( 1030): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1030): WifiMonitor:wlan0 cnt=14 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/Tethering( 1030): sendTetherStateChangedBroadcast 1, 0, 0
E/WifiStateMachine( 1030):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 12 0 rt=298522  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
E/WifiStateMachine( 1030):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 12 0 rt=298522  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
D/BluetoothMapEmailSettingsLoader( 6184): Found 0 applications
D/BluetoothMapEmailAppObserver( 6184): createReceiver()
I/wpa_supplicant( 6226): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
D/WifiMonitor( 1030): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1030): WifiMonitor:wlan0 cnt=15 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
I/wpa_supplicant( 6226): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
D/WifiMonitor( 1030): Event [IFNAME=wlan0 WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]]
E/WifiMonitor( 1030): WifiMonitor:wlan0 cnt=16 dispatchEvent: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
W/WifiMonitor( 1030): couldn't identify event type - WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
D/WifiMonitor( 1030): Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]]
E/WifiMonitor( 1030): WifiMonitor:wlan0 cnt=17 dispatchEvent: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
E/WifiMonitor( 1030): handleEvent 1  Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
D/WifiMonitor( 1030): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1030): WifiMonitor:wlan0 cnt=18 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
E/WifiStateMachine( 1030):  DisconnectedState CMD_ASSOCIATED_BSSID 13 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=298526
,V/WiFiOffLoadBroadcast( 6210): WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
E/WifiStateMachine( 1030):  ConnectModeState CMD_ASSOCIATED_BSSID 13 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=298528
E/WifiStateMachine( 1030):  DriverStartedState CMD_ASSOCIATED_BSSID 13 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=298528
E/WifiStateMachine( 1030):  SupplicantStartedState CMD_ASSOCIATED_BSSID 13 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=298529
I/StatusBar.NetworkController( 1446): networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
E/WifiStateMachine( 1030):  DefaultState CMD_ASSOCIATED_BSSID 13 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=298529
I/StatusBar.NetworkController( 1446): mWifiConnected = false, mWifiLevel = 0
E/WifiStateMachine( 1030):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 14 0 rt=298529  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: FOUR_WAY_HANDSHAKE
D/StatusBar.NetworkController( 1446): refreshViews: Data not connected!! Set no data type icon / Roaming
W/Settings( 1030): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1030): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1030): NETWORK_STATE_CHANGED_ACTION [CONNECTING]
D/WifiService( 1030): New client listening to asynchronous messages
D/WifiServerServiceExt( 1030): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1030): setSupplicantStateASSOCIATING
E/WifiStateMachine( 1030):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 14 0 rt=298540  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: FOUR_WAY_HANDSHAKE
E/WifiStateMachine( 1030):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 15 0 rt=298541  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: GROUP_HANDSHAKE
E/WifiStateMachine( 1030):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 15 0 rt=298541  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: GROUP_HANDSHAKE
,E/WifiStateMachine( 1030):  DisconnectedState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=298542
E/WifiStateMachine( 1030):  ConnectModeState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=298543
D/WifiNative-wlan0( 1030): doString: [STATUS]
D/WifiMonitor( 1030): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1030): WifiMonitor:wlan0 cnt=19 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/BluetoothMapEmailAppObserver( 6184): initObservers()
D/BluetoothMapEmailAppObserver( 6184): getEnabledAccountItems()
D/WifiNative-wlan0( 1030):    returned bssid=c0:ff:d4:d3:aa:48 ssid=NG700 id=0 mode=station pairwise_cipher=CCMP group_cipher=CCMP key_mgmt=WPA2-PSK wpa_state=COMPLETED p2p_device_address=02:9a:02:7b:60:ac address=c4:9a:02:7b:60:ac uuid=530d3fd0-1ba3-5409-a336-ff4e42af59a2
W/Settings( 1030): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1030): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1030): NETWORK_STATE_CHANGED_ACTION [CONNECTING]
I/WifiServiceExtension( 1030): setVHTCapabilityType  : false
D/BluetoothAdapterService( 6184): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@5501fa8
D/LgDataFeature( 6210): LgDataFeature() Constructor: none
D/LgDataFeature( 6210): LgDataFeature() Constructor Done, null
W/Settings( 1030): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1030): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1030): NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
V/BluetoothPbapReceiver( 6184): PbapReceiver onReceive 
D/WifiServerServiceExt( 1030): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1030): setSupplicantStateASSOCIATED
V/BluetoothPbapReceiver( 6184): ***********action = android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothPbapReceiver( 6184): ***********state = 11
,I/StatusBar.NetworkController( 1446): networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1446): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1446): refreshViews: Data not connected!! Set no data type icon / Roaming
D/HeadsetStateMachine( 6184): Proxy object connected
D/LGBluetoothHfpAdapter( 6184): [BTUI] queryPhoneState
D/LGBluetoothHfpAdapter( 6184): Try to query the phonestate on bind
I/StatusBar.NetworkController( 1446): networkInfo=[type: WIFI[], state: CONNECTING/AUTHENTICATING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1446): mWifiConnected = false, mWifiLevel = 0
D/BluetoothPhoneService.BluetoothLTECall( 1855):  call mBluetoothHeadset.phoneStateChanged()
D/StatusBar.NetworkController( 1446): refreshViews: Data not connected!! Set no data type icon / Roaming
W/BluetoothHeadset( 1855): Proxy not attached to service
D/BluetoothHeadset( 1855): java.lang.Throwable
D/BluetoothHeadset( 1855): 	at android.bluetooth.BluetoothHeadset.phoneStateChanged(BluetoothHeadset.java:826)
D/BluetoothHeadset( 1855): 	at com.android.phone.BluetoothPhoneService$BluetoothLTECall.handleQueryPhoneState(BluetoothPhoneService.java:1527)
D/BluetoothHeadset( 1855): 	at com.android.phone.BluetoothPhoneService$BluetoothLTECall.access$700(BluetoothPhoneService.java:1360)
D/BluetoothHeadset( 1855): 	at com.android.phone.BluetoothPhoneService$1.handleMessage(BluetoothPhoneService.java:268)
D/BluetoothHeadset( 1855): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/BluetoothHeadset( 1855): 	at android.os.Looper.loop(Looper.java:135)
D/BluetoothHeadset( 1855): 	at android.app.ActivityThread.main(ActivityThread.java:5274)
D/BluetoothHeadset( 1855): 	at java.lang.reflect.Method.invoke(Native Method)
D/BluetoothHeadset( 1855): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/BluetoothHeadset( 1855): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
D/BluetoothHeadset( 1855): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
D/BluetoothAdapterService( 6184): Profile still not running:com.android.bluetooth.gatt.GattService
D/HeadsetStateMachine( 6184): Disconnected process message: 10, size: 0
D/HeadsetPhoneState( 6184): sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
D/HeadsetStateMachine( 6184): Disconnected process message: 11, size: 0
,D/BluetoothAdapterService( 6184): Profile still not running:com.android.bluetooth.gatt.GattService
D/WiFiOffLoadUpdatePriority( 6210): remove : truetruetrue
D/BluetoothAdapterService( 6184): Profile still not running:com.android.bluetooth.gatt.GattService
D/BluetoothAdapterService( 6184): Profile still not running:com.android.bluetooth.gatt.GattService
D/BluetoothAdapterService( 6184): Profile still not running:com.android.bluetooth.gatt.GattService
V/PanService( 6184): [BTUI] SIM Extra State :ABSENT
D/BluetoothAdapterService( 6184): Profile still not running:com.android.bluetooth.map.BluetoothMapService
V/BluetoothMapService( 6184): Handler(): got msg=1
,D/BluetoothAdapterState( 6184): CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
I/bluedroid-qcom( 6184): enable
I/GKI_LINUX( 6184): gki_task_entry task_id=0 [BTU] starting
I/bt_hci_bdroid( 6184): init
I/bt-btu  ( 6184): btu_task pending for preload complete event
I/bt_vendor( 6184): bt-vendor : init
I/bt_vendor( 6184): bt-vendor : get_bt_soc_type
E/bt_vendor( 6184): get_bt_soc_type: Failed to get soc type
I/bt_vendor( 6184): init: Local BD Address : c0:64:73:54:3f:58
D/bt_userial_mct( 6184): userial_init
D/bt_hci_bdroid( 6184): set_power 1
I/bt_vendor( 6184): bt-vendor : BT_VND_OP_POWER_CTRL: On
I/bt_vendor( 6184): Starting hciattach daemon
I/bt_vendor( 6184): try to set true
W/sh      ( 6311): type=1400 audit(0.0:155): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
W/sh      ( 6311): type=1400 audit(0.0:156): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,I/ActivityManager( 1030): Start proc com.lge.lifetracker for broadcast com.lge.lifetracker/.receiver.HealthDeviceReceiver: pid=6312 uid=10037 gids={50037, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
I/WifiServerServiceExt( 1030): wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
I/WifiServerServiceExt( 1030): setKeepAlivePacketInterval msec : 60
I/qcom-bluetooth( 6313): /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  
I/StatusBar.NetworkController( 1446): networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1446): mWifiConnected = false, mWifiLevel = 0
W/Settings( 1030): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1030): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1030): NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
D/StatusBar.NetworkController( 1446): refreshViews: Data not connected!! Set no data type icon / Roaming
W/Settings( 1030): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1030): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1030): NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
,I/StatusBar.NetworkController( 1446): networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1446): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1446): refreshViews: Data not connected!! Set no data type icon / Roaming
V/AlarmManager( 1030): ELAPSED_WAKEUP set : Alarm{37ce1de1 type 2 when 237907 android} when 237907
D/ConnectivityService( 1030): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
D/ConnectivityService( 1030): Got NetworkAgent Messenger
E/WifiConfigStore( 1030): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/WifiNative-wlan0( 1030): doBoolean: SET_NETWORK 0 bssid any
D/WifiNative-wlan0( 1030): SET_NETWORK 0 bssid any: returned true
D/WifiNative-wlan0( 1030): doBoolean: SAVE_CONFIG
D/ConnectivityService( 1030): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
D/ConnectivityService( 1030): NetworkAgent connected
,D/WifiNative-wlan0( 1030): SAVE_CONFIG: returned true
E/WifiConfigStore( 1030): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/WifiNative-wlan0( 1030): doBoolean: SET_NETWORK 0 bssid any
D/WifiNative-wlan0( 1030): SET_NETWORK 0 bssid any: returned true
D/WifiNative-wlan0( 1030): doBoolean: SAVE_CONFIG
D/WifiNative-wlan0( 1030): SAVE_CONFIG: returned true
,D/CommandListener(  311): Setting iface cfg
E/WifiStateMachine( 1030): Start Dhcp Watchdog 1
E/WifiStateMachine( 1030):  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 18 0 rt=298645  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine( 1030):  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 18 0 rt=298646  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
D/DhcpStateMachine( 1030): StoppedState
D/DhcpStateMachine( 1030): StoppedState{ when=-2ms what=196609 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine( 1030): WaitBeforeStartState
,E/WifiStateMachine( 1030):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 18 0 rt=298647  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
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
E/WifiStateMachine( 1030):  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 19 0 rt=298652  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine( 1030):  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 19 0 rt=298652  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine( 1030):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 19 0 rt=298652  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine( 1030):  ObtainingIpState CMD_GET_CONFIGURED_NETWORKS uid=1000 1000 0 num=1
E/WifiStateMachine( 1030):  L2ConnectedState CMD_GET_CONFIGURED_NETWORKS uid=1000 1000 0 num=1
E/WifiStateMachine( 1030):  ConnectModeState CMD_GET_CONFIGURED_NETWORKS uid=1000 1000 0 num=1
I/qcom-bluetooth( 6337): /system/etc/init.qcom.bt.sh: Transport : smd 
,I/qcom-bluetooth( 6338): /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
E/WifiStateMachine( 1030):  ObtainingIpState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:1603597397] from screen [on:0 period:1603597397]
E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:1603597398]
I/WifiNative-HAL( 1030): startHal
E/wifi    ( 1030): getStaticLongField sWifiHalHandle 0x9892c8bc
E/WifiHAL ( 1030): Could not connect handle
D/wifi    ( 1030): halHandle = 0x0, mVM = 0xb487c280, mCls = 0x9014b2
I/WifiNative-HAL( 1030): Could not start hal
D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
D/StatusBar.NetworkController( 1446): refreshViews: Data not connected!! Set no data type icon / Roaming
E/WifiStateMachine( 1030):  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1030):  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
,E/WifiStateMachine( 1030):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
D/ConnectivityService( 1030): updateNetworkScore for NetworkAgentInfo [WIFI () - 100] to 60
E/WifiStateMachine( 1030):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1030):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1030):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
D/ConnectivityService( 1030): Update of LinkProperties for NetworkAgentInfo [WIFI () - 100]; created=false
E/WifiStateMachine( 1030):  ObtainingIpState CMD_PRE_DHCP_ACTION 0 0 txpkts=1,0,0
E/WifiStateMachine( 1030):  L2ConnectedState CMD_PRE_DHCP_ACTION 0 0 txpkts=1,0,0
D/WifiNative-wlan0( 1030): doBoolean: DRIVER SETSUSPENDMODE 0
I/qcom-bluetooth( 6340): /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
I/qcom-bluetooth( 6341): /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> 
,I/qcom-bluetooth( 6342): /system/etc/init.qcom.bt.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
I/qcom-bluetooth( 6343): /system/etc/init.qcom.bt.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> 
,I/wpa_supplicant( 6226): wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 0
D/WifiNative-wlan0( 1030): DRIVER SETSUSPENDMODE 0: returned true
D/WifiNative-wlan0( 1030): doBoolean: SET ps 0
D/WifiNative-wlan0( 1030): SET ps 0: returned true
D/WifiNative-wlan0( 1030): doBoolean: DRIVER BTCOEXMODE 1
I/wpa_supplicant( 6226): wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 1
D/WifiNative-wlan0( 1030): DRIVER BTCOEXMODE 1: returned true
E/WifiStateMachine( 1030): CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
V/DhcpStateMachine( 1030): Current State is mWaitBeforeStartState.
D/LGWifiP2pService( 1030): InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@264dec90 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1030): P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@264dec90 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine( 1030): WaitBeforeStartState{ when=0 what=196615 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine( 1030): DHCP Start wake lock is acquired.
V/LgDhcpStateMachineHelper( 1030): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
V/LgDhcpStateMachineHelper( 1030): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700" is not exist.
D/WifiServerServiceExt( 1030): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1030): setSupplicantStateCOMPLETED
E/WifiStateMachine( 1030):  ObtainingIpState CMD_SAVE_CONFIG uid=1000 0 0
E/WifiStateMachine( 1030):  L2ConnectedState CMD_SAVE_CONFIG uid=1000 0 0
E/WifiStateMachine( 1030):  ConnectModeState CMD_SAVE_CONFIG uid=1000 0 0
D/WifiNative-wlan0( 1030): doBoolean: SAVE_CONFIG
D/WifiServerServiceExt( 1030): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1030): setSupplicantStateCOMPLETED
E/ActivityThread( 6312): Failed to find provider info for com.lge.lgaccount.provider
,W/LG Account v2.2( 6312): No ProfileInfo entries
I/LG Account v2.2( 6312): isEnabled: false
I/Feature ( 6312): [Lifetracker]ver: 4.21.112(40211120)
I/Feature ( 6312): [Lifetracker]Country: EU
I/Feature ( 6312): [Lifetracker]Operator: OPEN
I/Feature ( 6312): [Lifetracker]Ranking support: false
I/Feature ( 6312): [Lifetracker]Comfort support: false
I/Feature ( 6312): [Lifetracker]Accessory: true
I/Feature ( 6312): [Lifetracker]Health device: true
I/Feature ( 6312): [Lifetracker]Extra Pedometer: false
I/Feature ( 6312): [Lifetracker]Blood glucose device: false
I/Feature ( 6312): [Lifetracker]Device Number: 3
I/libmdmdetect( 6345): ESOC framework not supported
E/Diag_Lib( 6345):  Diag_LSM_Init: Failed to open handle to diag driver, error = 13
I/ActivityManager( 1030): Killing 5473:com.android.contacts/u0a19 (adj 15): empty #17
D/WifiNative-wlan0( 1030): SAVE_CONFIG: returned true
D/WiFiOffLoadUpdatePriority( 6210): remove1
V/WiFiOffLoadSharedPrefsUtils( 6210): save remove
D/WiFiOffLoadBroadcast( 6210): mLastConnectedNetwork from SharedPrefsUtils for wifioffloading : null
D/WiFiOffLoadBroadcast( 6210): S: false, R: false
D/bthci_qcomm_linux( 6345): [BTUI] bt_hci_qcomm_pfal_get_bdaddress: Get BDADDR from bluedroid prop (58:3F:54:73:64:C0)
D/bthci_qcomm_common( 6345): [BTUI] bt_hci_qcomm_init:
D/bthci_qcomm_common( 6345): [BTUI]     BDADDR: 58:3F:54:73:64:C0
D/bthci_qcomm_common( 6345): [BTUI]     BR/EDR: Class 1
D/bthci_qcomm_common( 6345): [BTUI]     LE: Class 2
D/bthci_qcomm_common( 6345): [BTUI]     Ref Clock: 32M
D/btqsocnvmtags( 6345): [BTUI] init_riva_entries: set NORMAL power settings
E/WifiStateMachine( 1030):  ObtainingIpState CMD_GET_CONFIGURED_NETWORKS uid=1000 1000 0 num=1
E/WifiStateMachine( 1030):  L2ConnectedState CMD_GET_CONFIGURED_NETWORKS uid=1000 1000 0 num=1
E/WifiStateMachine( 1030):  ConnectModeState CMD_GET_CONFIGURED_NETWORKS uid=1000 1000 0 num=1
D/WiFiOffLoadUpdatePriority( 6210): saved SSID: "NG700"
,D/WiFiOffLoadUpdatePriority( 6210): connected SSID: null
D/WiFiOffLoadUpdatePriority( 6210): private wpa: "NG700" 300
D/WifiServiceImplEx( 1030): addOrUpdateNetwork pid=6210, uid=1000, packageName=android.uid.system:1000
E/addOrUpdateNetwork( 1030):  uid = 1000 SSID "NG700" nid=0
E/WifiStateMachine( 1030):  ObtainingIpState CMD_ADD_OR_UPDATE_NETWORK uid=1000 0 0 "NG700"WPA_PSK prio=300 status=2 any is current
E/WifiStateMachine( 1030):  L2ConnectedState CMD_ADD_OR_UPDATE_NETWORK uid=1000 0 0 "NG700"WPA_PSK prio=300 status=2 any is current
E/WifiStateMachine( 1030):  ConnectModeState CMD_ADD_OR_UPDATE_NETWORK uid=1000 0 0 "NG700"WPA_PSK prio=300 status=2 any is current
E/WifiConfigStore( 1030):  key="NG700"WPA_PSK netId=0 uid=0/1000
D/WifiServerServiceExt( 1030): addOrUpdateNetwork: mThisIsFirstEnableing = false
D/WifiNative-wlan0( 1030): doBoolean: SET_NETWORK 0 ssid 4e47373030
D/WifiNative-wlan0( 1030): SET_NETWORK 0 ssid 4e47373030: returned true
,E/WifiConfigStore( 1030): Setting BSSID for "NG700"WPA_PSK to any
D/WifiNative-wlan0( 1030): doBoolean: SET_NETWORK 0 bssid any
D/WifiNative-wlan0( 1030): SET_NETWORK 0 bssid any: returned true
D/WifiNative-wlan0( 1030): doBoolean: SET_NETWORK 0 key_mgmt WPA-PSK
D/WifiNative-wlan0( 1030): SET_NETWORK 0 key_mgmt WPA-PSK: returned true
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
I/rmt_storage(  308): rmt_storage_connect_cb: clnt_h=0x5 conn_h=0xb6403090
,I/rmt_storage(  308): rmt_storage_rw_iovec_cb: /boot/modem_fs1: clnt_h=0x1: req_h=0x9 msg_id=3: R/W request received
I/rmt_storage(  308): wakelock acquired: 1, error no: 42
I/rmt_storage(  308): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 Unblock worker thread (th_id: -1236807552)
,W/libprocessgroup( 1030): failed to open /acct/uid_10019/pid_5473/cgroup.procs: No such file or directory
,D/WiFiOffLoadUpdatePriority( 6210):  ssid "NG700" prio 300
D/WiFiOffLoadUpdatePriority( 6210): configuration updated: 0
E/WifiStateMachine( 1030):  ObtainingIpState CMD_SAVE_CONFIG uid=1000 0 0
E/WifiStateMachine( 1030):  L2ConnectedState CMD_SAVE_CONFIG uid=1000 0 0
E/WifiStateMachine( 1030):  ConnectModeState CMD_SAVE_CONFIG uid=1000 0 0
D/WifiNative-wlan0( 1030): doBoolean: SAVE_CONFIG
D/DhcpStateMachine( 1030): DHCPV4 request on wlan0
,V/LgDhcpStateMachineHelper( 1030): [bssid] hash key :c0:ff:d4:d3:aa:48
D/LgDhcpStateMachineHelper( 1030): dhcp.ap.macaddress = c0:ff:d4:d3:aa:48
W/dhcpcd  ( 6350): type=1400 audit(0.0:157): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,W/dhcpcd  ( 6350): type=1400 audit(0.0:158): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
I/rmt_storage(  308): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0x9 msg_id=3: Bytes written = 1572864
I/rmt_storage(  308): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0x9 msg_id=3: Send response: res=0 err=0
I/rmt_storage(  308): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 About to block rmt_storage client thread (th_id: -1236807552) wakelock released: 1, error no: 22
I/rmt_storage(  308): 
,I/rmt_storage(  308): rmt_storage_disconnect_cb: clnt_h=0x0x5 conn_h=0x0xb6403090
E/Diag_Lib(  883): [IMS_FATAL]| 3347 | 912 |ims-rtp-daemon ims_rtp_qmi_handler_thread_func waiting on select thread>
D/WifiNative-wlan0( 1030): SAVE_CONFIG: returned true
,I/dhcpcd  ( 6350): version 5.5.6 starting
D/WiFiOffLoadUpdatePriority( 6210): configuration saved: true
E/dhcpcd  ( 6350): get_duid: m
D/dhcpcd  ( 6350): wlan0: using ClientID 01:c4:9a:02:7b:60:ac
D/dhcpcd  ( 6350): wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason PREINIT
D/BluetoothPermissionRequest( 6210): onReceive
D/LGBluetoothFeatureConfig( 6210):  get() - isFeatureLoaded : false
,D/BluetoothManagerService( 1030): Message: 20
D/BluetoothManagerService( 1030): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@354d41bc:true
,I/ActivityManager( 1030): Killing 5810:com.lge.email/u0a23 (adj 15): empty #17
D/LGBluetoothResetSettingReceiver( 6210): return without doing reset settings.
D/dhcpcd  ( 6350): getUsingAPMacAddress: c0:ff:d4:d3:aa:48 , return 1
D/dhcpcd  ( 6350): [read_lease] unlink /data/misc/dhcp/dhcpcd-wlan0.lease, link /data/misc/dhcp/dhcpcd-wlan0-c0:ff:d4:d3:aa:48.lease2
D/dhcpcd  ( 6350): wlan0: reading lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
,I/dhcpcd  ( 6350): wlan0: rebinding lease of 192.168.1.122
D/dhcpcd  ( 6350): wlan0: sending REQUEST (xid 0x5d1cd33b), next in 4.56 seconds
D/LGBluetoothOppAdapter( 6184): [BTUI] getInstance : create [LGBluetoothOppAdapter]
W/libprocessgroup( 1030): failed to open /acct/uid_10023/pid_5810/cgroup.procs: No such file or directory
,D/PCSuite ( 6277): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,V/BluetoothFtpReceiver( 6184): BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
V/WiFiOffLoadBroadcast( 6210): WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
V/BluetoothSapReceiver( 6184): [BTUI] checkServiceStart
V/BluetoothSapReceiver( 6184): [BTUI] region:EU country:EU
V/BluetoothSapReceiver( 6184): SapReceiver onReceive 
V/BluetoothSapReceiver( 6184): action = android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothSapReceiver( 6184):  Bluetooth Adapter state = 11
D/WiFiOffLoadBroadcast( 6210): MCCMNC not supported: null
I/ActivityManager( 1030): Start proc com.lge.settings.easy for broadcast com.lge.settings.easy/com.lge.settings.bluetooth.LGBluetoothProfileConnectionReceiver: pid=6365 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,D/LGDMClient( 3941): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
D/LGDMClient( 3941): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
W/ContextImpl( 3941): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
W/ContextImpl( 3941): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
D/PostponalbeReceiver( 5128): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,D/LGDMClient( 3941): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=3, isUserType=1
I/PCSuite ( 6277): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/LGDMClient( 3941): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
D/LGDMClient( 3941): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
,W/FormManager( 6252): Network not available. Please check & try again.
V/FormManager( 6252): Network unavailable.
D/PCSuite ( 6277): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 6277): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 6210): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,V/FormManager( 6252): Network unavailable.
D/WiFiOffLoadBroadcast( 6210): MCCMNC not supported: null
W/ResourcesManager( 6365): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,I/ActivityManager( 1030): Start proc com.lge.qremote for broadcast com.lge.qremote/.settings.WiFiStateReceiver: pid=6386 uid=10112 gids={50112, 9997, 1028, 1015, 3003, 3002} abi=armeabi
,D/AuthorizationBluetoothService( 2125): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
I/ActivityManager( 1030): Killing 5498:com.android.gallery3d/u0a27 (adj 15): empty #17
,W/libprocessgroup( 1030): failed to open /acct/uid_10027/pid_5498/cgroup.procs: No such file or directory
,W/ResourcesManager( 6386): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,D/QRemote ( 6386): [QRemoteApplication.java:230:onCreate()] oooooo QRemoteApp onCreate....
,D/[Concierge]Service( 2596): onStartCommand(). Type : 9
,D/QRemote ( 6386): [CarrierUtils.java:858:getHardwareSettings()] oooooo qremote android.os.Build.MODEL = LG-D855
I/QRemote ( 6386): [CarrierUtils.java:859:getHardwareSettings()] oooooo getCountry :: EU
I/QRemote ( 6386): [CarrierUtils.java:860:getHardwareSettings()] oooooo getCarrier :: OPEN
I/QRemote ( 6386): [CarrierUtils.java:861:getHardwareSettings()] oooooo getArea :: COM
D/QRemote ( 6386): [CarrierUtils.java:862:getHardwareSettings()] oooooo Loading Config...
D/QRemote ( 6386): [CarrierUtils.java:876:getHardwareSettings()] oooooo qremote configuration file = R.xml.qremote_conf
,D/QRemote ( 6386): [QRemoteApplication.java:701:updateWidget()] oooooo Widget count is [1]. send broadcast
D/QRemote ( 6386): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6386): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 6386): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,V/[BNRBootReceiver]( 5925): boot receiver action = android.net.wifi.p2p.CONNECTION_STATE_CHANGE
D/BNRAndroBeam( 5925): [BnR DirectBeam] Android Direct Beam(NFC) Connection changed
D/QRemote ( 6386): [QRemoteService.java:196:onCreate()] oooooo 140526:onCreate
V/[BNRBootReceiver]( 5925): Boot Receiver Return
D/QRemote ( 6386): [QRemoteService.java:217:onStartCommand()] oooooo 140526:onStartCommand:action:action.application.oncreate. startId:1, flags:0
D/PostponalbeReceiver( 5128): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
V/WiFiOffLoadBroadcast( 6210): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6210): MCCMNC not supported: null
D/QRemote ( 6386): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6386): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 6386): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,V/WiFiOffLoadBroadcast( 6210): WiFiOffLoadBroadcast: android.net.wifi.SCAN_RESULTS
D/WiFiOffLoadBroadcast( 6210): Not supported operator for automatic switch
D/PostponalbeReceiver( 5128): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
D/BluetoothManagerService( 1030): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/jxcore-log( 6121): Got Device Bluetooth address: 58:3F:54:73:64:C0
I/jxcore-log( 6121): 
I/jxcore-log( 6121): my name is : LGE-LG-D855_PT3295
I/jxcore-log( 6121): 
,V/WiFiOffLoadBroadcast( 6210): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6210): MCCMNC not supported: null
D/QRemote ( 6386): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6386): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 6386): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
D/PostponalbeReceiver( 5128): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,V/WiFiOffLoadBroadcast( 6210): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6210): MCCMNC not supported: null
I/jxcore-log( 6121): attempting to connect to test coordinator
I/jxcore-log( 6121): 
I/jxcore-log( 6121): check test folder
I/jxcore-log( 6121): 
I/jxcore-log( 6121): found test : ./testFindPeers.js
I/jxcore-log( 6121): 
D/QRemote ( 6386): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6386): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 6386): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,D/UsbSettingsReceiver( 6210): [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
D/UsbSettingsReceiver( 6210): [AUTORUN] sys.usb.config = ptp_only,adb
D/UsbSettingsReceiver( 6210): [AUTORUN] sys.usb.state = ptp_only,adb
D/UsbSettingsReceiver( 6210): [AUTORUN] persist.sys.usb.config = ptp_only,adb
D/UsbSettingsReceiver( 6210): [AUTORUN] onReceive() : app userid = 0, current userid = 0
D/UsbSettingsControl( 6210): [AUTORUN] getUsbConnected() : connected=true
D/UsbSettingsReceiver( 6210): [AUTORUN] onReceive() : availableList=[wlan0]
D/UsbSettingsReceiver( 6210): [AUTORUN] onReceive() : activeList=[]
D/UsbSettingsReceiver( 6210): [AUTORUN] onReceive() : errorList=[]
D/UsbSettingsControl( 6210): [AUTORUN] isAutorunTimer() : mAutorunChanging=false
D/UsbSettingsReceiver( 6210): [AUTORUN] onReceive() : TetherState Changed=wlan0
D/UsbSettingsControl( 6210): [AUTORUN] setTetherStatus() : status=false
D/PostponalbeReceiver( 5128): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
I/jxcore-log( 6121): found test : ./testReConnect.js
I/jxcore-log( 6121): 
I/jxcore-log( 6121): found test : ./testSendData.js
I/jxcore-log( 6121): 
V/WiFiOffLoadBroadcast( 6210): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6210): MCCMNC not supported: null
D/QRemote ( 6386): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6386): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 6386): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,D/PostponalbeReceiver( 5128): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
V/WiFiOffLoadBroadcast( 6210): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,I/jxcore-log( 6121): Test app app.js loaded
I/jxcore-log( 6121): 
D/WiFiOffLoadBroadcast( 6210): MCCMNC not supported: null
D/QRemote ( 6386): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6386): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 6386): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,D/PostponalbeReceiver( 5128): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
E/QC-QMI  ( 6345): qmi_client [6345] 13: failed to locate client data
E/QC-QMI  (  453): qmuxd: RX on fd=32 returned error=0 errno[2:No such file or directory]
E/QC-QMI  (  453): QMUX qmux_client_id=13 not found in qmux client list, unable to remove
V/WiFiOffLoadBroadcast( 6210): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,I/jxcore-log( 6121): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6121): 
D/WiFiOffLoadBroadcast( 6210): MCCMNC not supported: null
D/QRemote ( 6386): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,D/QRemote ( 6386): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 6386): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
D/PostponalbeReceiver( 5128): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
V/WiFiOffLoadBroadcast( 6210): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
I/chromium( 6121): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,D/WiFiOffLoadBroadcast( 6210): MCCMNC not supported: null
I/chromium( 6121): [INFO:SkFontConfigInterface_android.cpp(247)] ---- failed to open </system/fonts/CutiveMono.ttf> as a font
I/chromium( 6121): 
,D/QRemote ( 6386): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6386): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 6386): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
V/QRemote ( 6386): [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
D/QRemote ( 6386): [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
D/QRemote ( 6386): [QRemoteApplication.java:86:getControlManager()] oooooo mControlManager is null. make new RemoteControlManager
,I/qcom-bluetooth( 6413): /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 58:3f:54:73:64:c0 
,I/qcom-bluetooth( 6414): /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
D/LgDataFeature( 6386): LgDataFeature() Constructor: none
D/LgDataFeature( 6386): LgDataFeature() Constructor Done, null
,I/chromium( 6121): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
V/SoundPool( 6386): SoundPool constructor: maxChannels=2, attr.usage=13, attr.flags=0x0, attr.tags=
V/SoundPool( 6386): load: fd=30, offset=10857164, length=17813, priority=1
V/SoundPool( 6386): create sampleID=1, fd=31, offset=17813 length=10857164
V/SoundPool( 6386): doLoad: loading sample sampleID=1
V/SoundPool( 6386): Start decode
,V/MediaPlayer[Native]( 6386): decode(31, 10857164, 17813)
V/MediaPlayerService(  316): decode(24, 10857164, 17813)
W/BrunchPlayerTypeImpl(  316): [SelectPlayer] LocalType
W/BrunchPlayerTypeImpl(  316): [getMediaType] EXTEND_MEDIA_MIMETYPE = application/ogg
W/BrunchPlayerTypeImpl(  316): [FindUsePlayer] type = [application/ogg]
I/QRemote ( 6386): [RemoteControlManager.java:157:onBindIRService()] oooooo bind
W/BrunchPlayerTypeImpl(  316): [FindUsePlayer] componentName = [9101]
W/MediaPlayerFactory(  316): [getPlayerType:fd] nType = 3
V/MediaPlayerService(  316): player type = 3
V/AwesomePlayer(  316): AwesomePlayer create()
V/AwesomePlayer(  316): reset_l() 
V/AwesomePlayer(  316): cancelPlayerEvents
V/AwesomePlayer(  316): setAudioSink() 
V/AwesomePlayer(  316): reset_l() 
V/AudioCache(  316): notify(0xb1163b00, 8, 0, 0)
V/AudioCache(  316): ignored
V/AwesomePlayer(  316): cancelPlayerEvents
D/Utils   (  316): printFileName fd(25) -> /data/preload/LGQRemote/LGQRemote.apk
V/AwesomePlayer(  316): setDataSource_l dataSource
V/LGParserOSAL(  316): SniffLGParser start
V/LGParserOSAL(  316): MainType:5, SubType=0
V/LGParserOSAL(  316): #### check Mime : application/ogg
V/LGParserOSAL(  316): Detector mimeType:application/ogg, Confidence=1.000000
E/MediaExtractor(  316): Use LGExtractor :application/ogg 
D/QRemote ( 6386): [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
E/QRemote ( 6386): [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
D/UEI.SmartControl( 5839): QS Service created
D/QRemote ( 6386): [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
V/LGMDMManager( 6386): Create singleton instance
,I/UEI.SmartControl( 5839): Service initServices...
D/UEI.SmartControl( 5839): QS start get config
I/bt_vendor( 6184): bluetooth satus is on
D/bt_hci_bdroid( 6184): preload
,D/bt_userial_mct( 6184): userial_open(port:0)
I/bt_vendor( 6184): bt-vendor : BT_VND_OP_USERIAL_OPEN
I/bt_vendor( 6184): Done intiailizing UART
I/bt_vendor( 6184): Done intiailizing UART
I/bt_userial_mct( 6184): CMD=66, EVT=66, ACL_Out=67, ACL_In=67
I/bt_vendor( 6184): Bluetooth Firmware and transport layer are initialized
D/bt_userial_mct( 6184): Entering userial_read_thread()
I/bt-btu  ( 6184): btu_task received preload complete event
W/bt-l2cap( 6184): L2CAP - L2CA_Register() called for PSM: 0x0001
W/bt-l2cap( 6184): L2CAP - L2CA_Register() called for PSM: 0x001f
W/bt-l2cap( 6184): L2CAP - L2CA_Register() called for PSM: 0x0003
I/        ( 6184): BTE_InitTraceLevels -- TRC_HCI
I/        ( 6184): BTE_InitTraceLevels -- TRC_L2CAP
I/        ( 6184): BTE_InitTraceLevels -- TRC_RFCOMM
I/        ( 6184): BTE_InitTraceLevels -- TRC_AVDT
I/        ( 6184): BTE_InitTraceLevels -- TRC_AVRC
I/        ( 6184): BTE_InitTraceLevels -- TRC_A2D
I/        ( 6184): BTE_InitTraceLevels -- TRC_BNEP
I/        ( 6184): BTE_InitTraceLevels -- TRC_BTM
I/        ( 6184): BTE_InitTraceLevels -- TRC_HID_HOST
I/        ( 6184): BTE_InitTraceLevels -- TRC_GAP
I/        ( 6184): BTE_InitTraceLevels -- TRC_PAN
I/        ( 6184): BTE_InitTraceLevels -- TRC_SDP
I/        ( 6184): BTE_InitTraceLevels -- TRC_GATT
I/        ( 6184): BTE_InitTraceLevels -- TRC_SMP
I/        ( 6184): BTE_InitTraceLevels -- TRC_BTAPP
I/        ( 6184): BTE_InitTraceLevels -- TRC_BTIF
V/LGParserOSAL(  316): supported mime: application/ogg
V/AwesomePlayer(  316): setDataSource_l() extractor countTracks=1
V/AwesomePlayer(  316): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer(  316): mBitrate = -1 bits/sec
V/AwesomePlayer(  316): AudioTrack Setting
V/AwesomePlayer(  316): AudioTrack Setting channelCount = 2
V/AwesomePlayer(  316): setAudioSource() 
V/MediaPlayerService(  316): prepare
V/AwesomePlayer(  316): prepareAsync_l() 
V/MediaPlayerService(  316): wait for prepare
V/AwesomePlayer(  316): onPrepareAsyncEvent() 
V/AwesomePlayer(  316): initAudioDecoder() 
W/Utils   (  316): bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
V/AudioSystem(  316): isOffloadSupported()
V/AudioPolicyManager(  316): isOffloadSupported: SR=48000, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
D/AudioPolicyManager(  316): isOffloadSupported: stream_type != MUSIC, returning false
I/AudioFlinger(  316): isAudioPlaybackHookOn() false
V/AwesomePlayer(  316): getUseOffload() = 0 
V/OMXCodec(  316): OMXCodec::Create
V/OMXCodec(  316): findMatchingCodecs()
V/OMXCodec(  316): matching 'OMX.google.vorbis.decoder' quirks 0x00000000
V/OMXCodec(  316): matchingCodecs.size()=1
V/OMXCodec(  316): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
,D/OMXCodec(  316): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
V/LGCodecAdapter(  316): LG Codec Adapter start
V/OMXCodec(  316): OMXCodec Createtor
V/OMXCodec(  316): setComponentRole
V/OMXCodec(  316): configureCodec protected=0
V/LGCodecAdapter(  316): called getLGCodecSpecificData
V/LGCodecOSAL(  316): Called LGgetCodecSpecificDataMETA
V/LGCodecOSAL(  316): Called LGconfigureCodecMETA
V/LGCodecOSAL(  316): Called LGconfigureCodecMSG
V/LGCodecOSAL(  316): Not support LGCodec
V/OMXCodec(  316): [OMX.google.vorbis.decoder] initOutputFormat()
V/OMXCodec(  316): Codec outputs a different number of channels than the input stream contains (contains 2 channels, codec outputs 1 channels).
V/OMXCodec(  316): Codec outputs at different sampling rate than what the input stream contains (contains data at 48000 Hz, codec outputs 44100 Hz)
I/AwesomePlayer(  316): Could not offload audio decode, try pcm offload
W/Utils   (  316): bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
V/AudioSystem(  316): isOffloadSupported()
V/AudioPolicyManager(  316): isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
D/AudioPolicyManager(  316): isOffloadSupported: stream_type != MUSIC, returning false
V/OMXCodec(  316): [OMX.google.vorbis.decoder] start mState=1
V/OMXCodec(  316): init()
V/OMXCodec(  316): [OMX.google.vorbis.decoder] setState mState=1 , newState=2
V/OMXCodec(  316): allocateBuffers
V/OMXCodec(  316): allocateBuffersOnPort portIndex=0
V/OMXCodec(  316): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
V/OMXCodec(  316): [OMX.google.vorbis.decoder] allocated buffer 0xb1434290 on input port
V/OMXCodec(  316): [OMX.google.vorbis.decoder] allocated buffer 0xb1434420 on input port
V/OMXCodec(  316): [OMX.google.vorbis.decoder] allocated buffer 0xb14344c0 on input port
V/OMXCodec(  316): [OMX.google.vorbis.decoder] allocated buffer 0xb1434510 on input port
V/OMXCodec(  316): allocateBuffersOnPort portIndex=1
V/OMXCodec(  316): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
V/OMXCodec(  316): [OMX.google.vorbis.decoder] allocated buffer 0xb1434560 on output port
V/OMXCodec(  316): [OMX.google.vorbis.decoder] allocated buffer 0xb1434600 on output port
V/OMXCodec(  316): [OMX.google.vorbis.decoder] allocated buffer 0xb1434650 on output port
V/OMXCodec(  316): [OMX.google.vorbis.decoder] allocated buffer 0xb14349c0 on output port
V/OMXCodec(  316): init() mAsyncCompletion wait!!! 
V/OMXCodec(  316): [OMX.google.vorbis.decoder] onStateChange 2
V/OMXCodec(  316): [OMX.google.vorbis.decoder] Now Idle.
V/OMXCodec(  316): [OMX.google.vorbis.decoder] setState mState=2 , newState=3
V/OMXCodec(  316): init() mAsyncCompletion wait!!! 
V/OMXCodec(  316): [OMX.google.vorbis.decoder] onStateChange 3
V/OMXCodec(  316): [OMX.google.vorbis.decoder] Now Executing.
V/OMXCodec(  316): [OMX.google.vorbis.decoder] setState mState=3 , newState=4
V/OMXCodec(  316): init() mAsyncCompletion wait free! 
V/AwesomePlayer(  316): finishAsyncPrepare_l() 
V/AudioCache(  316): notify(0xb1163b00, 5, 0, 0)
V/AudioCache(  316): ignored
V/AudioCache(  316): notify(0xb1163b00, 1, 0, 0)
V/AudioCache(  316): prepared
V/AudioCache(  316): wait - success
V/MediaPlayerService(  316): start
V/AwesomePlayer(  316): play_l() 
V/AwesomePlayer(  316): play_l m_isDivXDRM=0, bpurchasefile:0
V/AwesomePlayer(  316): createAudioPlayer_l
V/AwesomePlayer(  316): seekAudioIfNecessary_l() 
V/AwesomePlayer(  316): startAudioPlayer_l() 
D/AudioPlayer(  316): start of Playback, useOffload 0
V/OMXCodec(  316): [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
V/OMXCodec(  316): [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
V/OMXCodec(  316): [OMX.google.vorbis.decoder] OMX_EventPortSettingsChanged(port=1, data2=0x00000000)
V/OM,XCodec(  316): [OMX.google.vorbis.decoder] PORT_SETTINGS_CHANGED(1)
V/OMXCodec(  316): [OMX.google.vorbis.decoder] setState mState=4 , newState=7
V/OMXCodec(  316): [OMX.google.vorbis.decoder] disablePortAsync portIndex=1
V/OMXCodec(  316): [OMX.google.vorbis.decoder] sending OMX_CommandPortDisable(1)
V/OMXCodec(  316): [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
V/OMXCodec(  316): [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2973975904
V/OMXCodec(  316): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
V/OMXCodec(  316): [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2973976064
V/OMXCodec(  316): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
V/OMXCodec(  316): [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2973976144
V/OMXCodec(  316): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
V/OMXCodec(  316): [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2973977024
V/OMXCodec(  316): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
V/OMXCodec(  316): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
V/OMXCodec(  316): [OMX.google.vorbis.decoder] initOutputFormat()
V/OMXCodec(  316): [OMX.google.vorbis.decoder] reconfig handling, formatHasNotablyChanged
V/OMXCodec(  316): [OMX.google.vorbis.decoder] enablePortAsync portIndex=1
V/OMXCodec(  316): [OMX.google.vorbis.decoder] sending OMX_CommandPortEnable(1)
V/OMXCodec(  316): allocateBuffersOnPort portIndex=1
V/OMXCodec(  316): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
V/OMXCodec(  316): [OMX.google.vorbis.decoder] allocated buffer 0xb1434650 on output port
V/OMXCodec(  316): [OMX.google.vorbis.decoder] allocated buffer 0xb1434600 on output port
V/OMXCodec(  316): [OMX.google.vorbis.decoder] allocated buffer 0xb1434560 on output port
V/OMXCodec(  316): [OMX.google.vorbis.decoder] allocated buffer 0xb119a150 on output port
V/OMXCodec(  316): [OMX.google.vorbis.decoder] PORT_ENABLED(1)
V/OMXCodec(  316): [OMX.google.vorbis.decoder] setState mState=7 , newState=4
W/bt-btm  ( 6184): btm_decode_ext_features_page Secure conn Controller support Enabled
E/bt-btm  ( 6184): BTM_SecRegister:p_cb_info->p_le_callback == 0xa01ec061 
E/bt-btm  ( 6184): BTM_SecRegister: btm_cb.api.p_le_callback = 0xa01ec061 
,V/AudioCache(  316): open(48000, 2, 0x0, 1, 4)
V/AudioCache(  316): notify(0xb1163b00, 6, 0, 0)
,V/AudioCache(  316): ignored
V/AudioCache(  316): write(0xb124c000, 4096)
V/AudioCache(  316): memcpy(0xac406000, 0xb124c000, 4096)
V/MediaPlayerService(  316): wait for playback complete
D/QRemote ( 6386): [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
D/QRemote ( 6386): [RemoteAppWidgetProvider.java:486:onUpdate()] oooooo 140510:RetrieveDevices is not complete. Just waiting
D/QRemote ( 6386): [RemoteAppWidgetProvider.java:499:onUpdate()] oooooo 140514:alarm set after 5000ms:3479
E/bt-btif ( 6184): Calling BTA_HhEnable
E/bt-btif ( 6184): btif_storage_get_adapter_property service_mask:0x2140040
V/AudioCache(  316): write(0xb124c000, 4096)
V/AudioCache(  316): memcpy(0xac407000, 0xb124c000, 4096)
V/AudioCache(  316): write(0xb124c000, 4096)
V/AudioCache(  316): memcpy(0xac408000, 0xb124c000, 4096)
D/BluetoothAdapterProperties( 6184): Address is:58:3F:54:73:64:C0
V/AudioCache(  316): write(0xb124c000, 4096)
V/AudioCache(  316): memcpy(0xac409000, 0xb124c000, 4096)
W/bt-l2cap( 6184): L2CAP - L2CA_Register() called for PSM: 0x0019
,V/AudioCache(  316): write(0xb124c000, 4096)
V/AudioCache(  316): memcpy(0xac40a000, 0xb124c000, 4096)
,V/AudioCache(  316): write(0xb124c000, 4096)
V/AudioCache(  316): memcpy(0xac40b000, 0xb124c000, 4096)
V/AudioCache(  316): write(0xb124c000, 4096)
V/AudioCache(  316): memcpy(0xac40c000, 0xb124c000, 4096)
W/bt-l2cap( 6184): L2CAP - L2CA_Register() called for PSM: 0x0017
W/bt-l2cap( 6184): L2CAP - L2CA_Register() called for PSM: 0x001b
D/BluetoothManagerService( 1030): Bluetooth Adapter name changed to G3-1
W/bt-l2cap( 6184): L2CAP - L2CA_Register() called for PSM: 0x0011
W/bt-l2cap( 6184): L2CAP - L2CA_Register() called for PSM: 0x0013
D/BluetoothManagerService( 1030): Stored Bluetooth name: G3-1
D/BluetoothAdapterProperties( 6184): Name is: G3-1
D/BluetoothAdapterProperties( 6184): Scan Mode:20
V/AudioCache(  316): write(0xb124c000, 4096)
D/BluetoothAdapterProperties( 6184): Discoverable Timeout:120
V/AudioCache(  316): memcpy(0xac40d000, 0xb124c000, 4096)
D/bt_hci_bdroid( 6184): postload
D/bt_hci_bdroid( 6184): Used up Tx Cmd credits
V/AudioCache(  316): write(0xb124c000, 4096)
V/AudioCache(  316): memcpy(0xac40e000, 0xb124c000, 4096)
V/AudioCache(  316): write(0xb124c000, 4096)
V/AudioCache(  316): memcpy(0xac40f000, 0xb124c000, 4096)
W/bt-l2cap( 6184): L2CAP - L2CA_Register() called for PSM: 0x000f
V/AudioCache(  316): write(0xb124c000, 4096)
V/AudioCache(  316): memcpy(0xac410000, 0xb124c000, 4096)
D/bt_hci_bdroid( 6184): Used up Tx Cmd credits
D/bt_hci_bdroid( 6184): Used up Tx Cmd credits
D/bt_hci_bdroid( 6184): Used up Tx Cmd credits
E/bt_mct  ( 6184): hci lib postload completed
V/AudioCache(  316): write(0xb124c000, 4096)
V/AudioCache(  316): memcpy(0xac411000, 0xb124c000, 4096)
V/AudioCache(  316): write(0xb124c000, 4096)
V/AudioCache(  316): memcpy(0xac412000, 0xb124c000, 4096)
V/AudioCache(  316): write(0xb124c000, 4096)
V/AudioCache(  316): memcpy(0xac413000, 0xb124c000, 4096)
V/AudioCache(  316): write(0xb124c000, 4096)
V/AudioCache(  316): memcpy(0xac414000, 0xb124c000, 4096)
D/bte_conf( 6184): Device ID record 1 : primary
D/bte_conf( 6184):   vendorId            = 00c4
D/bte_conf( 6184):   vendorIdSource      = 0001
D/bte_conf( 6184):   product             = 13a1
D/bte_conf( 6184):   version             = 1000
D/bte_conf( 6184):   clientExecutableURL = 
D/bte_conf( 6184):   serviceDescription  = 
D/bte_conf( 6184):   documentationURL    = 
D/bte_conf( 6184): bte_load_did_conf no section named DID2.
V/AudioCache(  316): write(0xb124c000, 4096)
V/AudioCache(  316): memcpy(0xac415000, 0xb124c000, 4096)
V/AudioCache(  316): write(0xb124c000, 4096)
V/AudioCache(  316): memcpy(0xac416000, 0xb124c000, 4096)
W/sh      ( 6426): type=1400 audit(0.0:159): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
W/sh      ( 6426): type=1400 audit(0.0:160): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
W/bt-smp  ( 6184): Key(LSB ~ MSB) = 0a 3c a6 fe eb 17 6a 79 a6 1f 0a 0b f9 50 a0 5f 
W/bt-smp  ( 6184): Plain text(LSB ~ MSB) = e8 fd 75 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 6184): Encrypted text(LSB ~ MSB) = 05 e6 81 25 87 01 fe 1d 22 54 8e 3a 92 7c a8 88 
W/bt-btm  ( 6184): Stopping oneshot timer
D/BluetoothAdapterState( 6184): CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
D/BluetoothAdapterProperties( 6184): ScanMode =  20
D/BluetoothAdapterProperties( 6184): State =  11
D/BluetoothAdapterProperties( 6184): mDiscoverableTimeout = 120
V/LGBluetoothServiceAdapter( 6184): [BTUI] state:11, scanmode:20, timeout:120
D/BluetoothAdapterProperties( 6184): Setting state to 12
I/BluetoothAdapterState( 6184): Bluetooth adapter state changed: 11-> 12
D/BluetoothManagerService( 1030): Message: 60
D/BluetoothManagerService( 1030): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
D/BluetoothManagerService( 1030): Broadcasting onBluetoothStateChange(true) to 5 receivers.
D/BluetoothHeadset( ,1855): onBluetoothStateChange: up=true
D/BluetoothHeadset( 1855): onBluetoothStateChange: up=true
I/BluetoothAdapterState( 6184): Entering On State
D/BluetoothHeadset( 1030): onBluetoothStateChange: up=true
D/BluetoothHeadset( 1855): onBluetoothStateChange: up=true
D/BluetoothA2dp( 1030): onBluetoothStateChange: up=true
E/BluetoothManagerService( 1030): Fail to bind to: Intent { act=android.bluetooth.IQBluetooth }
D/BluetoothManagerService( 1030): Bluetooth State Change Intent: 11 -> 12
D/BluetoothManagerService( 1030): BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
D/BluetoothManagerService( 1030): Message: 40
D/BluetoothManagerService( 1030): MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
D/BluetoothPanServiceJni( 6184): control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
D/btif_config_util( 6184): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
D/LGBluetoothServiceAdapter( 6184): [BTUI] OnState
D/LGBluetoothServiceAdapter( 6184): [BTUI]         global_name: G3-1
D/LGBluetoothServiceAdapter( 6184): [BTUI]         local_name: G3-1
D/LGBluetoothAPIService( 1950): [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
D/LGBluetoothAPIService( 1950): Message: 1
D/LGBluetoothAPIService( 1950): MESSAGE_BOOT_COMPLETED
D/BluetoothAdapterService( 6184): [BTUI] autoConnect() : not allowed
,I/[SystemUI]BluetoothHandler( 1446): Receive : BluetoothAdapter.ACTION_STATE_CHANGED
V/AudioCache(  316): write(0xb124c000, 4096)
V/AudioCache(  316): memcpy(0xac417000, 0xb124c000, 4096)
V/AudioCache(  316): write(0xb124c000, 4096)
V/AudioCache(  316): memcpy(0xac418000, 0xb124c000, 4096)
W/bt-smp  ( 6184): Key(LSB ~ MSB) = 0a 3c a6 fe eb 17 6a 79 a6 1f 0a 0b f9 50 a0 5f 
W/bt-smp  ( 6184): Plain text(LSB ~ MSB) = ac 74 5c 00 00 00 00 00 00 00 00 00 00 00 00 00 
V/AudioCache(  316): write(0xb124c000, 4096)
V/AudioCache(  316): memcpy(0xac419000, 0xb124c000, 4096)
W/bt-smp  ( 6184): Encrypted text(LSB ~ MSB) = c8 4f 4d c3 80 46 a0 36 9c de 43 fe 84 3c da 32 
W/bt-btm  ( 6184): Stopping oneshot timer
V/AudioCache(  316): write(0xb124c000, 4096)
V/AudioCache(  316): memcpy(0xac41a000, 0xb124c000, 4096)
V/AudioCache(  316): write(0xb124c000, 4096)
V/AudioCache(  316): memcpy(0xac41b000, 0xb124c000, 4096)
V/AudioCache(  316): write(0xb124c000, 4096)
V/AudioCache(  316): memcpy(0xac41c000, 0xb124c000, 4096)
V/AudioCache(  316): write(0xb124c000, 4096)
V/AudioCache(  316): memcpy(0xac41d000, 0xb124c000, 4096)
V/AudioCache(  316): write(0xb124c000, 4096)
V/AudioCache(  316): memcpy(0xac41e000, 0xb124c000, 4096)
V/AudioCache(  316): write(0xb124c000, 4096)
V/AudioCache(  316): memcpy(0xac41f000, 0xb124c000, 4096)
V/AudioCache(  316): write(0xb124c000, 4096)
V/AudioCache(  316): memcpy(0xac420000, 0xb124c000, 4096)
V/AudioCache(  316): write(0xb124c000, 4096)
V/AudioCache(  316): memcpy(0xac421000, 0xb124c000, 4096)
I/LGBluetoothAPIService( 1950): [BTUI] LGBluetoothAPIService Binding Success
V/AudioCache(  316): write(0xb124c000, 4096)
V/AudioCache(  316): memcpy(0xac422000, 0xb124c000, 4096)
V/AudioCache(  316): write(0xb124c000, 4096)
V/AudioCache(  316): memcpy(0xac423000, 0xb124c000, 4096)
V/AudioCache(  316): write(0xb124c000, 4096)
I/BluetoothMapService( 6184): onReceive: android.bluetooth.adapter.action.STATE_CHANGED
D/BluetoothMapService( 6184): STATE_ON
V/AudioCache(  316): memcpy(0xac424000, 0xb124c000, 4096)
W/bt-smp  ( 6184): Key(LSB ~ MSB) = 0a 3c a6 fe eb 17 6a 79 a6 1f 0a 0b f9 50 a0 5f 
W/bt-smp  ( 6184): Plain text(LSB ~ MSB) = 3a fb 4f 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 6184): Encrypted text(LSB ~ MSB) = bb 63 b9 94 f0 5a 8b 1e a8 24 6c 0e 43 5b 27 0c 
W/bt-btm  ( 6184): Stopping oneshot timer
V/AudioCache(  316): write(0xb124c000, 4096)
V/AudioCache(  316): memcpy(0xac425000, 0xb124c000, 4096)
V/AudioCache(  316): write(0xb124c000, 4096)
V/AudioCache(  316): memcpy(0xac426000, 0xb124c000, 4096)
,V/AudioCache(  316): write(0xb124c000, 4096)
V/AudioCache(  316): memcpy(0xac427000, 0xb124c000, 4096)
V/AudioCache(  316): write(0xb124c000, 4096)
V/AudioCache(  316): memcpy(0xac428000, 0xb124c000, 4096)
V/AudioCache(  316): write(0xb124c000, 4096)
V/AudioCache(  316): memcpy(0xac429000, 0xb124c000, 4096)
V/AudioCache(  316): write(0xb124c000, 4096)
V/AudioCache(  316): memcpy(0xac42a000, 0xb124c000, 4096)
V/AudioCache(  316): write(0xb124c000, 4096)
,V/AudioCache(  316): memcpy(0xac42b000, 0xb124c000, 4096)
W/ContextImpl( 6210): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
V/AudioCache(  316): write(0xb124c000, 4096)
V/AudioCache(  316): memcpy(0xac42c000, 0xb124c000, 4096)
,V/AudioCache(  316): write(0xb124c000, 4096)
V/AudioCache(  316): memcpy(0xac42d000, 0xb124c000, 4096)
D/LGBluetoothAPIServer( 6184): [BTUI] onCreate()
D/LGBluetoothAPIServer( 6184): [BTUI] onBind()
V/AudioCache(  316): write(0xb124c000, 4096)
V/AudioCache(  316): memcpy(0xac42e000, 0xb124c000, 4096)
V/AudioCache(  316): write(0xb124c000, 4096)
V/AudioCache(  316): memcpy(0xac42f000, 0xb124c000, 4096)
V/BluetoothMapService( 6184): Handler(): got msg=1
D/BluetoothMapMasInstance( 6184): Map Service startRfcommSocketListener
,V/AudioCache(  316): write(0xb124c000, 4096)
V/AudioCache(  316): memcpy(0xac430000, 0xb124c000, 4096)
V/AudioCache(  316): write(0xb124c000, 4096)
V/AudioCache(  316): memcpy(0xac431000, 0xb124c000, 4096)
D/BluetoothMapMasInstance( 6184): MAS initSocket()
W/bt-smp  ( 6184): Key(LSB ~ MSB) = 0a 3c a6 fe eb 17 6a 79 a6 1f 0a 0b f9 50 a0 5f 
D/BluetoothMapMasInstance( 6184):   masId = 00
D/BluetoothMapMasInstance( 6184):   msgTypes = 0e
D/BluetoothMapMasInstance( 6184):   masName = SMS/MMS
D/BluetoothMapMasInstance( 6184):   SDP string = 000eSMS/MMS
W/bt-smp  ( 6184): Plain text(LSB ~ MSB) = 2b b0 46 00 00 00 00 00 00 00 00 00 00 00 00 00 
V/AudioCache(  316): write(0xb124c000, 4096)
W/bt-smp  ( 6184): Encrypted text(LSB ~ MSB) = a0 31 92 f3 f9 74 5f ae 25 7d 4f 28 ee 62 1e 0f 
V/AudioCache(  316): memcpy(0xac432000, 0xb124c000, 4096)
W/bt-btm  ( 6184): Stopping oneshot timer
V/AudioCache(  316): write(0xb124c000, 4096)
V/AudioCache(  316): memcpy(0xac433000, 0xb124c000, 4096)
D/BluetoothManagerService( 1030): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
V/AudioCache(  316): write(0xb124c000, 4096)
V/AudioCache(  316): memcpy(0xac434000, 0xb124c000, 4096)
W/BluetoothAdapter( 6184): getBluetoothService() called with no BluetoothManagerCallback
V/AudioCache(  316): write(0xb124c000, 4096)
V/AudioCache(  316): memcpy(0xac435000, 0xb124c000, 4096)
V/AudioCache(  316): write(0xb124c000, 4096)
V/AudioCache(  316): memcpy(0xac436000, 0xb124c000, 4096)
D/LGBluetoothServiceAdapter( 6184): [BTUI] createSocketChannel FD=73 mFd=0
V/BluetoothMapMasInstance( 6184): Succeed to create listening socket 
D/BluetoothMapMasInstance( 6184): Accepting socket connection...
V/AudioCache(  316): write(0xb124c000, 4096)
V/AudioCache(  316): memcpy(0xac437000, 0xb124c000, 4096)
V/OMXCodec(  316): [OMX.google.vorbis.decoder] No more output data.
V/OMXCodec(  316): [OMX.google.vorbis.decoder] There is no more output data available, not calling fillOutputBuffer
V/AwesomePlayer(  316): postAudioEOS() 
V/AudioCache(  316): write(0xb124c000, 280)
V/AudioCache(  316): memcpy(0xac438000, 0xb124c000, 280)
D/LGBluetoothAPIService( 1950): [BTUI] LGBluetoothAPIServiceConnection: connected to LGBluetoothAPIAdapter
D/LGBluetoothAPIService( 1950): Message: 100
D/LGBluetoothAPIService( 1950): MESSAGE_BLUETOOTH_SERVICE_CONNECTED
V/AwesomePlayer(  316): postStreamDoneEvent_l() -> status:-1011 
V/AwesomePlayer(  316): onStreamDone
V/AwesomePlayer(  316): MEDIA_PLAYBACK_COMPLETE
V/AudioCache(  316): notify(0xb1163b00, 2, 0, 0)
V/AudioCache(  316): playback complete
V/AwesomePlayer(  316): pause_l() 
V/AudioCache(  316): notify(0xb1163b00, 7, 0, 0)
V/AudioCache(  316): ignored
V/AwesomePlayer(  316): cancelPlayerEvents
V/AudioCache(  316): wait - success
V/MediaPlayerService(  316): return size 205080, sampleRate=48000, channelCount = 2, format = 1
D/BluetoothAdapterService( 6184): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@5501fa8
V/BluetoothPbapService( 6184): Pbap Service onCreate
V/BluetoothPbapService( 6184): Starting PBAP service
W/bt-smp  ( 6184): Key(LSB ~ MSB) = 0a 3c a6 fe eb 17 6a 79 a6 1f 0a 0b f9 50 a0 5f 
W/bt-smp  ( 6184): Plain text(LSB ~ MSB) = bf d1 5c 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 6184): Encrypted text(LSB ~ MSB) = 7a 69 15 38 db 56 56 98 3b 9f e9 c8 66 5b 01 44 
W/bt-btm  ( 6184): Stopping oneshot timer
D/LGBluetoothPbapAdapter( 6184): [BTUI] getInstance : create
,V/BluetoothPbapService( 6184): action: android.bluetooth.adapter.action.STATE_CHANGED
D/AudioPlayer(  316): Pause Playback at 1068125
V/BluetoothPbapService( 6184): state: 12
V/BluetoothPbapService( 6184): Handler(): got msg=1
V/AwesomePlayer(  316): reset_l() 
V/AudioCache(  316): notify(0xb1163b00, 8, 0, 0)
V/AudioCache(  316): ignored
V/AwesomePlayer(  316): cancelPlayerEvents
D/AudioPlayer(  316): reset: mPlaying=0 mReachedEOS=1 useOffload=0
V/OMXCodec(  316): [OMX.google.vorbis.decoder] stop mState=4
V/OMXCodec(  316): [OMX.google.vorbis.decoder] stopOmxComponent_l mState=4
V/OMXCodec(  316): [OMX.google.vorbis.decoder] setState mState=4 , newState=5
V/OMXCodec(  316): [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
V/BluetoothPbapService( 6184): Pbap Service startRfcommSocketListener
V/OMXCodec(  316): [OMX.google.vorbis.decoder] onStateChange 2
V/OMXCodec(  316): [OMX.google.vorbis.decoder] Now Idle.
V/OMXCodec(  316): [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=0
V/OMXCodec(  316): [OMX.google.vorbis.decoder] freeing buffer 0xb1434510 on port 0
V/OMXCodec(  316): [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=3
V/OMXCodec(  316): [OMX.google.vorbis.decoder] freeing buffer 0xb14344c0 on port 0
V/OMXCodec(  316): [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=2
V/OMXCodec(  316): [OMX.google.vorbis.decoder] freeing buffer 0xb1434420 on port 0
V/OMXCodec(  316): [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=1
V/OMXCodec(  316): [OMX.google.vorbis.decoder] freeing buffer 0xb1434290 on port 0
V/OMXCodec(  316): [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=0
V/OMXCodec(  316): [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
V/OMXCodec(  316): [OMX.google.vorbis.decoder] freeing buffer 0xb119a150 on port 1
V/OMXCodec(  316): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=3
V/OMXCodec(  316): [OMX.google.vorbis.decoder] freeing buffer 0xb1434560 on port 1
V/OMXCodec(  316): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=2
V/OMXCodec(  316): [OMX.google.vorbis.decoder] freeing buffer 0xb1434600 on port 1
V/OMXCodec(  316): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=1
V/OMXCodec(  316): [OMX.google.vorbis.decoder] freeing buffer 0xb1434650 on port 1
V/OMXCodec(  316): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
V/OMXCodec(  316): [OMX.google.vorbis.decoder] setState mState=5 , newState=6
V/OMXCodec(  316): [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
V/OMXCodec(  316): [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
V/OMXCodec(  316): [OMX.google.vorbis.decoder] onStateChange 1
V/OMXCodec(  316): [OMX.google.vorbis.decoder] Now Loaded.
V/OMXCodec(  316): [OMX.google.vorbis.decoder] setState mState=6 , newState=1
V/OMXCodec(  316): [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
V/OMXCodec(  316): [OMX.google.vorbis.decoder] stopped in state 1
V/OMXCodec(  316): [OMX.google.vorbis.decoder] ~OMXCodec mstate =1
V/OMXCodec(  316): [OMX.google.vorbis.decoder] setState mState=1 , newState=0
D/AudioPlayer(  316): AudioPlayer releasing audio source
D/AudioPlayer(  316): AudioPlayer done releasing audio source
V/BluetoothPbapService( 6184): Pbap Service initSocket
D/BluetoothManagerService( 1030): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
V/AwesomePlayer(  316): reset_l() 
V/AwesomePlayer(  316): cancelPlayerEvents
V/AwesomePlayer(  316): ~AwesomePlayer call
V/AwesomePlayer(  316): reset_l() 
V/AwesomePlayer(  316): cancelPlayerEvents
V/SoundPool( 6386): close(31)
V/SoundPool( 6386): pointer = 0x9ffde000, size = 205080, sampleRate = 48000, numChannels = 2
W/BluetoothAdapter( 6184): getBluetoothService() called with no BluetoothManagerCallback
D/LGBluetoothServiceAdapter( 6184): [BTUI] createSocketChannel FD=75 mFd=73
V/BluetoothPbapService( 6184): Succeed to create listening socket 
V/BluetoothPbapService( 6184): Accepting socket connection...
V/BluetoothPbapReceiver( 6,184): PbapReceiver onReceive 
V/BluetoothPbapReceiver( 6184): ***********action = android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothPbapReceiver( 6184): ***********state = 12
D/LGBluetoothDeviceModeControllManager( 6184): [BTUI] checkDeviceModeAndSet, sinkMode : false
,I/qcom-bt-wlan-coex( 6434): /system/etc/init.qcom.coex.sh: btwlancoex/abtfilt not available 
D/LocalBluetoothProfileManager( 6210): Adding local A2DP profile
D/BluetoothManagerService( 1030): Message: 30
D/LocalBluetoothProfileManager( 6210): Adding local HEADSET profile
,D/BluetoothManagerService( 1030): Message: 30
D/BluetoothManagerService( 1030): Message: 30
D/BluetoothManagerService( 1030): Message: 30
,D/LocalBluetoothProfileManager( 6210): Adding local MAP profile
D/BluetoothMap( 6210): Create BluetoothMap proxy object
D/BluetoothManagerService( 1030): Message: 30
D/BluetoothManagerService( 1030): Message: 30
V/BluetoothPbapService( 6184): Pbap Service onBind
D/LocalBluetoothProfileManager( 6210): LocalBluetoothProfileManager construction complete
D/LGBluetoothUserBindClient( 6210): [BTUI] initUserBindClient
W/ContextImpl( 6210): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.android.settings.bluetooth.LGBluetoothUserBindClient.initUserBindClient:90 com.android.settings.bluetooth.LGBluetoothUserBindClient.<init>:55 com.android.settings.bluetooth.LGBluetoothUserBindClient.getInstance:47 
,D/DockEventReceiver( 6210): finishStartingService: stopping service
D/BluetoothA2dp( 6210): Proxy object connected
D/A2dpProfile( 6210): Bluetooth service connected
D/BluetoothHeadset( 6210): Proxy object connected
D/HeadsetProfile( 6210): Bluetooth service connected
,D/BluetoothInputDevice( 6210): Proxy object connected
D/HidProfile( 6210): Bluetooth service connected
D/BluetoothPan( 6210): BluetoothPAN Proxy object connected
D/PanProfile( 6210): Bluetooth service connected
D/BluetoothMap( 6210): Proxy object connected
D/MapProfile( 6210): Bluetooth service connected
D/BluetoothMap( 6210): getConnectedDevices()
V/BluetoothMapService( 6184): getConnectedDevices()
D/BluetoothAdapterProperties( 6184): Discoverable Timeout:120
D/LGBluetoothDeviceModeControllManager( 6184): adapterPropertyChangedCallback on  LGAdapter : do nothing - 9
D/BluetoothPbap( 6210): Proxy object connected
D/BluetoothAdapterProperties( 6184): Scan Mode:21
D/LGBluetoothDeviceModeControllManager( 6184): getDeviceMode  deviceMode 0
D/PbapServerProfile( 6210): Bluetooth service connected
D/LGBluetoothUserBindClient( 6210): [BTUI] onServiceConnected
D/BluetoothPermissionRequest( 6210): onReceive
D/LGBluetoothFeatureConfig( 6210): isPrivacyLogsEnabled : true
D/LGBluetoothUtils( 6210): [BTUI] FileNotFound: readProperty
D/LGBluetoothResetSettingReceiver( 6210): return without doing reset settings.
V/BluetoothOppReceiver( 6184): Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_ON
,I/LGBluetoothOppAdapter( 6184): [BTUI] startOppService()
V/BluetoothOppManager( 6184): restoreApplicationData! falsefalsenullnull
,D/LGBluetoothFeatureConfig( 6184): isPrivacyLogsEnabled : true
V/BtOppService( 6184): onCreate
,V/BluetoothOppNotification( 6184): send message
V/BtOppService( 6184): Starting RfcommListener
D/BluetoothOppPreference( 6184): Dumping Names:  
D/BluetoothOppPreference( 6184): {}
D/BluetoothOppPreference( 6184): Dumping Channels:  
D/BluetoothOppPreference( 6184): {}
V/BtOppService( 6184): onStartCommand
V/BtOppService( 6184): pendingUpdate is true keepUpdateThread is false sListenStarted is true
V/BluetoothFtpReceiver( 6184): BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothFtpReceiver( 6184): BluetoothFtpReceiver Start Service
V/BluetoothOppNotification( 6184): new notify threadi!
V/BluetoothOppNotification( 6184): send delay message
V/BtOppService( 6184): start RfcommListener
,V/BtOppService( 6184): RfcommListener started
V/BtOppRfcommListener( 6184): Starting RFCOMM listener....
D/BluetoothManagerService( 1030): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
W/BluetoothAdapter( 6184): getBluetoothService() called with no BluetoothManagerCallback
D/LGBluetoothServiceAdapter( 6184): [BTUI] createSocketChannel FD=79 mFd=75
,V/BtOppRfcommListener( 6184): Started RFCOMM listener....
I/BtOppRfcommListener( 6184): Accept thread started.
V/BtOppRfcommListener( 6184): Accepting connection...
,V/BluetoothOppProvider( 6184): starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
V/BtOppService( 6184): Deleted complete outbound shares, number =  0
V/BluetoothOppProvider( 6184): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
V/BluetoothOppProvider( 6184): created cursor android.database.sqlite.SQLiteCursor@395a8002 on behalf of 
V/BluetoothOppProvider( 6184): created cursor android.database.sqlite.SQLiteCursor@2154d13 on behalf of 
D/BluetoothAdapterService( 6184): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@5501fa8
V/BluetoothFtpService( 6184): Ftp Service onCreate
I/BluetoothFtpService( 6184): Ftp Service onCreate
V/BluetoothFtpService( 6184): Ftp Service onStartCommand
V/BluetoothFtpService( 6184): action: android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothFtpService( 6184): Starting Listening on sockets
V/BluetoothSapReceiver( 6184): [BTUI] checkServiceStart
V/BluetoothSapReceiver( 6184): [BTUI] region:EU country:EU
V/BluetoothSapReceiver( 6184): SapReceiver onReceive 
V/BtOppService( 6184): Deleted complete inbound failed shares, number = 0
V/BluetoothOppProvider( 6184): starting query, database is not null; projection[0] is _id; selection is direction=1 AND status=200 AND visibility=1; selectionArgs is null; sort is _id.
V/BluetoothSapReceiver( 6184): action = android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothSapReceiver( 6184):  Bluetooth Adapter state = 12
V/BluetoothSapReceiver( 6184): Calling SAP service start service with action = null
I/dhcpcd  ( 6350): wlan0: acknowledged 192.168.1.122 from 192.168.1.1
V/BluetoothOppProvider( 6184): created cursor android.database.sqlite.SQLiteCursor@2afc2149 on behalf of 
V/BtOppService( 6184): ContentObserver received notification
V/BtOppService( 6184): ContentObserver received notification
V/BluetoothFtpService( 6184): Handler(): got msg=1
V/BluetoothOppNotification( 6184): mUpdateCompleteNotification = true
V/BluetoothFtpService( 6184): Ftp Service startRfcommSocketListener
V/BluetoothFtpService( 6184): Ftp Service initSocket
V/BtOppService( 6184): pendingUpdate is true keepUpdateThread is false sListenStarted is true
V/BluetoothOppProvider( 6184): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
D/AuthorizationBluetoothService( 2125): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
D/BluetoothManagerService( 1030): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
V/BluetoothOppProvider( 6184): created cursor android.database.sqlite.SQLiteCursor@26f49a4e on behalf of 
W/BluetoothAdapter( 6184): getBluetoothService() called with no BluetoothManagerCallback
,D/LGBluetoothServiceAdapter( 6184): [BTUI] createSocketChannel FD=81 mFd=79
V/BluetoothFtpService( 6184): Succeed to create listening socket on channel 20
V/BluetoothFtpService:RfcommSocketAcceptThread( 6184): Run Accept thread
V/BluetoothOppProvider( 6184): starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
V/BluetoothOppNotification( 6184): update too frequent, put in queue
V/BluetoothOppProvider( 6184): created cursor android.database.sqlite.SQLiteCursor@37da76f on behalf of 
V/BtOppService( 6184): pendingUpdate is false keepUpdateThread is false sListenStarted is true
V/BluetoothOppNotification( 6184): outbound: succ-0  fail-0
V/BluetoothOppNotification( 6184): outbound notification was removed.
V/BluetoothOppProvider( 6184): starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
V/BluetoothOppProvider( 6184): created cursor android.database.sqlite.SQLiteCursor@345e4c7c on behalf of 
D/BluetoothAdapterService( 6184): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@5501fa8
V/BluetoothSapService( 6184): Sap Service onCreate
V/BluetoothSapService( 6184): action: android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothSapService( 6184): state: 12
V/BluetoothSapService( 6184): Starting SAP server process
,V/BluetoothOppNotification( 6184): inbound: succ-0  fail-0
V/BluetoothSapService( 6184): SAP Service startRfcommListenerThread
V/BluetoothOppNotification( 6184): inbound notification was removed.
V/BluetoothOppProvider( 6184): starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
V/BluetoothSapService( 6184): Sap Service initRfcommSocket
D/BluetoothManagerService( 1030): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
V/BluetoothOppProvider( 6184): created cursor android.database.sqlite.SQLiteCursor@2b81b468 on behalf of 
W/BluetoothAdapter( 6184): getBluetoothService() called with no BluetoothManagerCallback
D/LGBluetoothServiceAdapter( 6184): [BTUI] createSocketChannel FD=83 mFd=81
V/BluetoothSapService( 6184): Succeed to create listening socket 
W/sapd    ( 6448): type=1400 audit(0.0:161): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
V/BluetoothSapService( 6184): Accepting socket connection...
W/sapd    ( 6448): type=1400 audit(0.0:162): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
I/dhcpcd  ( 6350): wlan0: leased 192.168.1.122 for 86400 seconds
D/dhcpcd  ( 6350): wlan0: adding IP address 192.168.1.122/24
,D/dhcpcd  ( 6350): wlan0: adding route to 192.168.1.0/24
,D/dhcpcd  ( 6350): wlan0: adding default route via 192.168.1.1
D/dhcpcd  ( 6350): wlan0: writing lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
D/dhcpcd  ( 6350): getUsingAPMacAddress: c0:ff:d4:d3:aa:48 , return 1
D/dhcpcd  ( 6350): write_lease_ext: /data/misc/dhcp/dhcpcd-wlan0-c0:ff:d4:d3:aa:48.lease2
D/dhcpcd  ( 6350): wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason REBOOT
V/BT_SAP  ( 6448): Event pipe created
V/BT_SAP  ( 6448): create_server_socket qcom.sap.server
V/BT_SAP  ( 6448): created socket fd 6
E/WifiStateMachine( 1030):  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1030):  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1030):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1030):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1030):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1030):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
D/ConnectivityService( 1030): Update of LinkProperties for NetworkAgentInfo [WIFI () - 100]; created=false
I/UEI.SmartControl( 5839): Supports setup maps: true
,D/UEI.SmartControl( 5839): QS start statue = true Error code = 0
,I/UEI.SmartControl( 5839): QS version = v2.7.10.1_RC1
I/UEI.SmartControl( 5839): QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
I/UEI.SmartControl( 5839): ### init IR Blaster...
D/serial_port( 5839): Configuring serial port
E/UEI.SmartControl( 5839): UEIBLaster setting for 616
I/UEI.SmartControl( 5839): Setting serial record hearder size = 2
I/UEI.SmartControl( 5839): configuring settings for MAXQ616
I/UEI.SmartControl( 5839): Get version...
E/WifiStateMachine( 1030):  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0 v4
E/WifiStateMachine( 1030):  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4
E/WifiStateMachine( 1030):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0 v4
E/WifiStateMachine( 1030):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4
E/WifiStateMachine( 1030):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4
E/WifiStateMachine( 1030):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0 v4
D/ConnectivityService( 1030): Update of LinkProperties for NetworkAgentInfo [WIFI () - 100]; created=false
,D/UEI.SmartControl( 5839): serial port data available: 21
D/UEI.SmartControl( 5839): MAXQ616 A2-X4 software.
I/UEI.SmartControl( 5839): IR Blaster version: 256702256704300002
I/UEI.SmartControl( 5839): QS saving settings...
D/UEI.SmartControl( 5839): IR Blaster version: 25672567
,D/UEI.SmartControl( 5839): serial port data available: 4
,I/UEI.SmartControl( 5839): Device manager: loading config....
D/UEI.SmartControl( 5839): ----------- loading internal config...
,W/ContextImpl( 5839): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
E/UEI.SmartControl( 5839): Services init done
D/UEI.SmartControl( 5839): QS Service init finished
D/UEI.SmartControl( 5839): QS Service version name: 2.1.91
D/UEI.SmartControl( 5839): QS Service version code: 201091
D/UEI.SmartControl( 5839): Service requested: Control
E/UEI.SmartControl( 5839): Loading SETTINGS...
D/UEI.SmartControl( 5839): Request IControl service: devices are loaded...
I/QRemote ( 6386): [RemoteControlManager.java:183:onServiceConnected()] oooooo start
D/UEI.SmartControl( 5839): Internal service binding...
I/UEI.SmartControl( 5839): ------ IControl API: 11
D/UEI.SmartControl( 5839): File observer start...
,E/UEI.SmartControl( 5839): IR Port is disabled: false
,D/UEI.SmartControl( 5839): Starting file observer...
I/UEI.SmartControl( 5839): Registering callback...
D/UEI.SmartControl( 5839): -- Open brand translation xml: brands_translations_ko
I/UEI.SmartControl( 5839): ------ IControl API: 19
,I/UEI.SmartControl( 5839): Registering Services Ready callback...
I/UEI.SmartControl( 5839): Notify AllClients services are ready: 0
D/UEI.SmartControl( 5839): -----service ready thread exits
I/QRemote ( 6386): [RemoteControlManager.java:660:QSSetupIsReady()] oooooo 140517:sdkIsReady callback... get functions. Result:0
D/QRemote ( 6386): [RemoteControlManager.java:388:handleMessage()] oooooo 140510:START_SESSION
D/QRemote ( 6386): [RemoteControlManager.java:394:handleMessage()] oooooo 140510:send retrieve msg
D/QRemote ( 6386): [RemoteControlManager.java:322:handleMessage()] oooooo 140510:handler call retrieveDevices
D/QRemote ( 6386): [RemoteControlManager.java:336:retrieveDevices()] oooooo retrieveDevices: start
I/UEI.SmartControl( 5839): ------ IControl API: 8
,D/QRemote ( 6386): [RemoteControlManager.java:340:retrieveDevices()] oooooo retrieveDevices: 0
D/QRemote ( 6386): [RemoteControlManager.java:345:retrieveDevices()] oooooo retrieveDevices complete:true
D/QRemote ( 6386): [RemoteControlManager.java:353:retrieveDevices()] oooooo retrieveDevices: notifyDataSetChanged()
D/QRemote ( 6386): [QRemoteApplication.java:145:onRemoteControlStateChanged()] oooooo onRemoteControlStateChanged called in QRemoteApp
D/QRemote ( 6386): [QRemoteApplication.java:158:onRemoteControlStateChanged()] oooooo Widget count is [1]. send broadcast
D/QRemote ( 6386): [QRemoteApplication.java:160:onRemoteControlStateChanged()] oooooo Widget[0]:3
D/QRemote ( 6386): [QRemoteApplication.java:188:onRemoteControlStateChanged()] oooooo 140526:onRemoteControlStateChanged&sdkIsReady. stop Service
V/QRemote ( 6386): [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
,D/QRemote ( 6386): [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
E/QRemote ( 6386): [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
D/QRemote ( 6386): [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
D/QRemote ( 6386): [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
D/QRemote ( 6386): [RemoteAppWidgetProvider.java:506:onUpdate()] oooooo 140510:RetrieveDevices complete. Start loading
D/QRemote ( 6386): [RemoteAppWidgetProvider.java:508:onUpdate()] oooooo 140510:appWidgetIds[0]:3 loading
D/QRemote ( 6386): [RemoteAppWidgetManager.java:41:startLoading()] oooooo 140518:widgetId[3] loading start at [1449007577941]
D/QRemote ( 6386): [QRemoteService.java:207:onDestroy()] oooooo 140526:onDestroy
,I/ActivityManager( 1030): Killing 5718:com.android.defcontainer/u0a4 (adj 15): empty #17
D/QRemote ( 6386): [RemoteAppWidgetManager.java:239:doInBackground()] oooooo 140407:doinBack arr:0
,W/libprocessgroup( 1030): failed to open /acct/uid_10004/pid_5718/cgroup.procs: No such file or directory
,V/QRemote ( 6386): [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.widget_ui_update
E/QRemote ( 6386): [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
D/QRemote ( 6386): [RemoteAppWidgetProvider.java:171:onReceive()] oooooo total:0
D/QRemote ( 6386): [RemoteAppWidgetProvider.java:172:onReceive()] oooooo selected:0
D/QRemote ( 6386): [RemoteAppWidgetProvider.java:173:onReceive()] oooooo arr:[]
D/QRemote ( 6386): [RemoteAppWidgetProvider.java:174:onReceive()] oooooo appWidgetId:3
D/QRemote ( 6386): [RemoteAppWidgetProvider.java:815:updateRemoteViews()] oooooo UpdateRemoteViews3:widgetId:3
D/DhcpStateMachine( 1030): DHCPV4 succeeded on wlan0
D/LgDhcpStateMachineHelper( 1030): CheckDhcpDirectory [Lease File Count] : 3
,V/LgDhcpStateMachineHelper( 1030): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
D/LgDhcpStateMachineHelper( 1030): checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.122
V/LgDhcpStateMachineHelper( 1030): Add DhcpResults: IP address 192.168.1.122/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 86400 seconds
V/DhcpStateMachine( 1030): Current State is mWaitBeforeStartState.
V/LgDhcpStateMachineHelper( 1030): bShouldSendDhcpAction Result: true
D/DhcpStateMachine( 1030): DHCP Start/Renew wake lock is released.
D/DhcpStateMachine( 1030): RunningState
E/WifiStateMachine( 1030):  ObtainingIpState CMD_POST_DHCP_ACTION 1 0 OK  v4
E/WifiStateMachine( 1030):  L2ConnectedState CMD_POST_DHCP_ACTION 1 0 OK  v4
D/WifiNative-wlan0( 1030): doBoolean: DRIVER BTCOEXMODE 2
I/wpa_supplicant( 6226): wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
D/LGWifiP2pService( 1030): InactiveState{ when=-2ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1030): P2pEnabledState{ when=-2ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0( 1030): DRIVER BTCOEXMODE 2: returned true
D/WifiNative-wlan0( 1030): doBoolean: DRIVER SETSUSPENDMODE 1
I/wpa_supplicant( 6226): wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 1
D/WifiNative-wlan0( 1030): DRIVER SETSUSPENDMODE 1: returned true
D/WifiNative-wlan0( 1030): doBoolean: SET ps 1
D/QRemote ( 6386): [RemoteAppWidgetProvider.java:986:updateRemoteViews()] oooooo updateAppWidget5:widgetId:3]
D/WifiNative-wlan0( 1030): SET ps 1: returned true
,D/ConnectivityService( 1030): Update of LinkProperties for NetworkAgentInfo [WIFI () - 100]; created=false
E/WifiStateMachine( 1030):  ObtainingIpState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
E/WifiStateMachine( 1030):  L2ConnectedState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
E/WifiStateMachine( 1030): WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
D/ConnectivityService( 1030): ignoring duplicate network state non-change
W/Settings( 1030): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1030): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1030): NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
,D/ConnectivityService( 1030): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
D/ConnectivityService( 1030): Adding iface wlan0 to network 100
W/Settings( 1030): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1030): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1030): NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
I/StatusBar.NetworkController( 1446): networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1446): mWifiConnected = false, mWifiLevel = 0
,D/StatusBar.NetworkController( 1446): refreshViews: Data not connected!! Set no data type icon / Roaming
E/WifiStateMachine( 1030): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
D/WifiHS20( 1030): [PASSPOINT] passpointNotification: hs20AP list is checked
I/StatusBar.NetworkController( 1446): networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1446): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1446): refreshViews: Data not connected!! Set no data type icon / Roaming
D/PostponalbeReceiver( 5128): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
I/StatusBar.NetworkController( 1446): networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/StatusBar.NetworkController( 1446): mWifiConnected = true, mWifiLevel = 3
V/WfdStateTracker( 1950): handleWifiStateChangedEvent: 1
W/Settings( 1030): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1030): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1030): NETWORK_STATE_CHANGED_ACTION [CONNECTED]
,D/StatusBar.NetworkController( 1446): refreshViews: Data not connected!! Set no data type icon / Roaming
E/ConnectivityService( 1030): Unexpected mtu value: 0, wlan0
D/ConnectivityService( 1030): Adding Route [fe80::/64 -> :: wlan0] to network 100
D/WifiHS20( 1030): [PASSPOINT] passpointNotification: hs20AP list is checked
,D/ConnectivityService( 1030): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 100
D/ConnectivityService( 1030): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 100
D/ConnectivityService( 1030): addLocalRoutetoDefaultNetwork
D/ConnectivityService( 1030): defaultNAI is null or Wi-Fi no need to add Loacal route to default network. WiFi netid = 100
D/ConnectivityService( 1030): Setting Dns servers for network 100 to [/192.168.1.1]
W/Settings( 1030): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1030): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1030): NETWORK_STATE_CHANGED_ACTION [CONNECTED]
D/Nat464Xlat( 1030): requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
D/ConnectivityService( 1030): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService( 1030): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService( 1030): rematching NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService( 1030):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1030): DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1030): Connected
D/ConnectivityService( 1030):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
,D/ConnectivityService( 1030):     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1030): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService( 1030):   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1030):     satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:true
D/ConnectivityService( 1030): currentScore = 0, newScore = 20
D/ConnectivityService( 1030):    accepting network in place of null
D/ConnectivityService( 1030): sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1030): Checking http://clients3.google.com/generate_204 on "NG700"
D/ConnectivityService( 1030): Setting tx/rx TCP buffers to 524288,1048576,2097152,262144,524288,1048576
D/WIFI    ( 1030): new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    ( 1030):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/TelephonyNetworkFactory-1( 1855): new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/TelephonyNetworkFactory-1( 1855):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
I/StatusBar.NetworkController( 1446): networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1446): mWifiConnected = true, mWifiLevel = 3
D/StatusBar.NetworkController( 1446): refreshViews: Data not connected!! Set no data type icon / Roaming
D/libc-netbsd(  311): res_queryN name = clients3.google.com, class = 1, type = 28
E/ConnectivityService( 1030): [lg_data] Adding agent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.122/24,fe80::c69a:2ff:fe7b:60ac/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
,D/CSLegacyTypeTracker( 1030): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
D/ConnectivityService( 1030): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService( 1030): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/CSLegacyTypeTracker( 1030): [e] list.add(nai) empty : false size: 1
D/ConnectivityService( 1030): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.122/24,fe80::c69a:2ff:fe7b:60ac/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
D/LocSvc_java( 1030): Sending msg: 4 arg1:1 arg2:1
D/libc-netbsd(  311): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  311): res_queryN name = 2.android.pool.ntp.org, class = 1, type = 1
D/LocSvc_java( 1030): getAGpsConnectionInfo connType - 4
D/libc-netbsd(  311): res_queryN name = 2.android.pool.ntp.org., class = 1, type = 1
D/LocSvc_java( 1030): updateNetworkState connTyp: 4 available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java( 1030): ignore wifi update if we are not in OPENING or CLOSING
D/LocSvc_java( 1030): Sending msg: 5 arg1:0 arg2:1
D/DSQN    ( 1030): DNSproblemNotiEnabled is disabled ignore DNS fail CB
D/ConnectivityService( 1030): validation of new default Network = false
D/ConnectivityService( 1030): Default network via Wi-Fi connected. start DSQN
D/DSQN    ( 1030): enableDataServiceNotify 
D/DSQN    ( 1030): start dsqn bin
D/libc-netbsd(  311): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  311): res_queryN name = europe.pool.ntp.org, class = 1, type = 1
,D/ConnectivityService( 1030): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService( 1030):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1030):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1030): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityManager.CallbackHandler( 1446): CM callback handler got msg 524290
,V/WiFiOffLoadBroadcast( 6210): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
W/dsqn    ( 6492): type=1400 audit(0.0:163): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
W/dsqn    ( 6492): type=1400 audit(0.0:164): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
V/NetworkPolicy( 1030): [LG_RESTRICTED] checkMobilePolicy_type()
D/WiFiOffLoadBroadcast( 6210): MCCMNC not supported: null
,D/libc-netbsd(  311): res_queryN name = clients3.google.com, class = 1, type = 1
E/DSQN    ( 6492): DSQN ssw
,D/QRemote ( 6386): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6386): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
D/TelephonyIcons( 1446): null signal icon name: drawable/stat_sys_signal_null
D/StatusBar.NetworkController( 1446): refreshViews: Data not connected!! Set no data type icon / Roaming
D/StatusBar.NetworkController( 1446): refreshViews: Data not connected!! Set no data type icon / Roaming
I/QRemote ( 6386): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
D/PostponalbeReceiver( 5128): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,V/WiFiOffLoadBroadcast( 6210): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/libc-netbsd(  311): res_queryN name = clients3.google.com succeed
,D/WiFiOffLoadBroadcast( 6210): MCCMNC not supported: null
D/QRemote ( 6386): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6386): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 6386): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,D/LGDataListener(  311): argv[0]=dsqncommand
D/PostponalbeReceiver( 5128): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,D/LGDataListener(  311): argv[1]=wlan0
D/LGDataListener(  311): argv[2]=1
D/LGDataListener(  311): notifyDSQN DSQN STARTMONITOR wlan0 1
D/DSQN    ( 1030): DSQM DsqnNotification wlan0  1
D/DSQN    ( 1030): start to monitor internet connection
I/PCSuite ( 6277): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
D/PCSuite ( 6277): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
,V/WiFiOffLoadBroadcast( 6210): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1030): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Tue, 01 Dec 2015 22:06:18 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1449007578218], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1449007578200]}
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
D/ConnectivityManager.CallbackHandler( 1446): CM callback handler got msg 524290
D/TelephonyNetworkFactory-1( 1855): new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/TelephonyNetworkFactory-1( 1855):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
D/WIFI    ( 1030): new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    ( 1030):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService( 1030): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
D/WiFiOffLoadBroadcast( 6210): MCCMNC not supported: null
,D/QRemote ( 6386): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,D/QRemote ( 6386): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,D/QRemote ( 6386): [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
I/QRemote ( 6386): [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
I/QRemote ( 6386): [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
D/PostponalbeReceiver( 5128): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
I/PCSuite ( 6277): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
D/PCSuite ( 6277): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
,V/WiFiOffLoadBroadcast( 6210): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6210): MCCMNC not supported: null
D/QRemote ( 6386): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6386): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,D/QRemote ( 6386): [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
I/QRemote ( 6386): [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
I/QRemote ( 6386): [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
D/TelephonyIcons( 1446): null signal icon name: drawable/stat_sys_signal_null
D/StatusBar.NetworkController( 1446): refreshViews: Data not connected!! Set no data type icon / Roaming
D/StatusBar.NetworkController( 1446): refreshViews: Data not connected!! Set no data type icon / Roaming
D/libc-netbsd(  311): res_queryN name = europe.pool.ntp.org succeed
,D/LocSvc_java( 1030): NTP server : europe.pool.ntp.org
D/LocSvc_java( 1030): NTP server returned: 1449007578502 (Tue Dec 01 23:06:18 GMT+01:00 2015) reference: 300894 certainty: 31 system time offset: 118
,D/LocSvc_java( 1030): Sending msg: 10 arg1:0 arg2:1
,D/LocSvc_java( 1030): reportXtraServer 
D/LocSvc_java( 1030):  server1=http://xtra2.gpsOneXTRA.net/xtra2.bin
D/LocSvc_java( 1030):  server2=http://xtra3.gpsOneXTRA.net/xtra2.bin
D/LocSvc_java( 1030):  server3=
D/LocSvc_java( 1030): xtraDownloadRequest
D/LocSvc_java( 1030): Sending msg: 6 arg1:0 arg2:1
,D/libc-netbsd(  311): default dns: query_ipv6=0, query_ipv4=1
,D/libc-netbsd(  311): res_queryN name = xtra2.gpsOneXTRA.net, class = 1, type = 1
D/libc-netbsd(  311): res_queryN name = xtra2.gpsOneXTRA.net succeed
,I/jxcore-log( 6121): DBG, CoordinatorConnector connect called
I/jxcore-log( 6121): 
,I/jxcore-log( 6121): Coordinator is now connected to the server!
I/jxcore-log( 6121): 
I/chromium( 6121): [INFO:CONSOLE(63)] "logCallback connected to server", source: file:///android_asset/www/js/thali_main.js (63)
,V/BluetoothOppNotification( 6184): new notify threadi!
V/BluetoothOppNotification( 6184): send delay message
,V/BluetoothOppProvider( 6184): starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
V/BluetoothOppProvider( 6184): created cursor android.database.sqlite.SQLiteCursor@3ba1b081 on behalf of 
V/BluetoothOppNotification( 6184): mUpdateCompleteNotification = true
V/BluetoothOppProvider( 6184): starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
V/BluetoothOppProvider( 6184): created cursor android.database.sqlite.SQLiteCursor@2c65a526 on behalf of 
V/BluetoothOppNotification( 6184): outbound: succ-0  fail-0
V/BluetoothOppNotification( 6184): outbound notification was removed.
V/BluetoothOppProvider( 6184): starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
V/BluetoothOppProvider( 6184): created cursor android.database.sqlite.SQLiteCursor@fd1567 on behalf of 
,V/BluetoothOppNotification( 6184): inbound: succ-0  fail-0
V/BluetoothOppNotification( 6184): inbound notification was removed.
V/BluetoothOppProvider( 6184): starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
D/LocSvc_java( 1030): calling native_inject_xtra_data
D/LocSvc_java( 1030): Sending msg: 11 arg1:0 arg2:1
I/art     ( 1030): Explicit concurrent mark sweep GC freed 74037(3MB) AllocSpace objects, 4(105KB) LOS objects, 33% free, 44MB/66MB, paused 2.767ms total 168.837ms
V/BluetoothOppProvider( 6184): created cursor android.database.sqlite.SQLiteCursor@3cf1af14 on behalf of 
,E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-53 f=2462 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:1603600405] gl rssi=-53 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-53 f=2462 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:1603600406] gl rssi=-53 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
,D/StatusBar.NetworkController( 1446): refreshViews: Data not connected!! Set no data type icon / Roaming
V/WifiInternetCheck( 1030): Single check msg out of sync, ignoring.
,D/ConnectivityService( 1030): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering( 1030): MasterInitialState.processMessage what=3
,D/libc-netbsd(  311): default dns: query_ipv6=0, query_ipv4=1
,D/libc-netbsd(  311): res_queryN name = 2.android.pool.ntp.org, class = 1, type = 1
D/GpsLocationProvider( 1030): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,D/PostponalbeReceiver( 5128): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
,W/ContextImpl( 5128): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
I/NetworkMonitor( 5187): type=WIFI subType= reason=null isConnected=true
,D/libc-netbsd(  311): res_queryN name = 2.android.pool.ntp.org succeed
D/AlarmManagerService( 1030): Setting time of day to sec=1449007581
,W/AlarmManagerService( 1030): Unable to set rtc to 1449007581: Invalid argument
I/ActivityManager( 1030): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=6541 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,I/SecureClockService( 1950): Intent.ACTION_TIME_CHANGED 
D/LIA_Informant_Tips_DateChangeManager( 2686): onReceive() : ACTION_TIME_CHANGED
I/LIA_Informant_Tips_LogTracer( 2686): [Log Tracer - Schedule Transition] Time Change Event Received : 2015-12-01 23:06:21...... Request
I/LIA_Informant_Tips_LogTracer( 2686): [Log Tracer - Schedule Transition] UserGuide, DATE_UPDATE : working count : 6, total count : 100, new day : false...... Request
D/LIA_Informant_Tips_DateChangeManager( 2686): DateInfo : SmartTips Total Working Day Count = 100
D/LIA_Informant_Tips_DateChangeManager( 2686): DateInfo : UserGuide Working Duration Count = 6
D/LIA_Informant_Tips_DateChangeManager( 2686): DateInfo : Last Date Check Time = 2015-12-01 23:06:21
,W/ActivityManager( 1030): getTasks: caller 10029 is using old GET_TASKS but privileged; allowing
D/KeyguardUpdateMonitor( 1446): handleTimeUpdate
I/[SystemUI]Clock( 1446): onReceive = android.intent.action.TIME_SET
I/LgeClockWidgetControlView( 1446): time changed, timezoneChanged : false
I/[LGHome]LGDateChangeReceiver( 2070): [LGDateChangeReceiver.java:78:updateCalendarShortcut()]date=1 currentDate=-1 dayofweek=3 currentDayOfWeek=-1
I/[LGHome]LGCalendarIcon( 2070): [LGCalendarIcon.java:214:makeCalendarBitmap()]Locale = en_US dayofweek= Tue date= 1
,I/[LGHome]LGCalendarIcon( 2070): [LGCalendarIcon.java:214:makeCalendarBitmap()]Locale = en_US dayofweek= Tue date= 1
I/[LGHome]Launcher( 2070): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,D/[Concierge]Service( 2596): onStartCommand(). Type : 9
I/AppUp4:AppBoxCP( 6541): onCreate
W/AppUp4:DB( 6541):  [AppBoxDatabaseHelper] construct
,I/AppUp4:DB( 6541):  setFingerPrint start
I/AppUp4:DB( 6541):  newfinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys SDK version = 21
I/AppUp4:DB( 6541):  beforefinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys
I/AppUp4:DB( 6541):  SDK version = 21
I/AppUp4:DB( 6541):  beforefinger == newfinger no write in DB
,I/ActivityManager( 1030): Start proc com.google.android.apps.books for service com.google.android.apps.books/.service.SyncService: pid=6562 uid=10054 gids={50054, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/AppUp4:AppBoxApplication( 6541): AppBoxApplication onCreate()
,I/NetworkStateForAutoUpdateMonitor( 6541): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 6541): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 6541): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 6541): [onReceive] request level :IDLE....
I/art     (  338): Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 287us total 13.689ms
I/GoogleURLConnFactory( 2125): Using platform SSLCertificateSocketFactory
I/AppUp4:CustModeStarterReceiver( 6541): onReceive
,I/art     (  338): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 248us total 12.615ms
I/art     (  338): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 250us total 11.612ms
,D/LgDataFeature( 6541): LgDataFeature() Constructor: none
,D/LgDataFeature( 6541): LgDataFeature() Constructor Done, null
D/AppUp4:CustFacade( 6541): Context : android.app.ReceiverRestrictedContext@328b5bcb
D/AppUp4:CustFacade( 6541): isCustomizationCompleted : false
D/AppUp4:CustFacade( 6541): isPhone : true
D/AppUp4:CustModeStarterReceiver( 6541): begin check event
I/AppUp4:CustModeStarterReceiver( 6541): Event For GoodConnectivity
D/AppUp4:CustModeStarterReceiver( 6541): runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
,I/ActivityManager( 1030): Start proc com.android.gallery3d for service com.android.gallery3d/com.lge.gallery.picasa.PicasaService: pid=6581 uid=10027 gids={50027, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
D/AppUp4:CustModeStarterReceiver( 6541): call method handleAsyncCustNotification.
D/AppUp4:CustModeStarterReceiver( 6541): handleAsync isTriedOnce : false
E/AppUp4:CustModeStarterReceiver( 6541): handleAsyncCustNotification do not startCustService
I/ActivityManager( 1030): Killing 5524:com.lge.lockscreensettings/u0a80 (adj 15): empty #17
,V/GLSActivity( 2125): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/AlarmManager( 1030): ELAPSED_WAKEUP set : Alarm{387d5562 type 2 when 304032 com.google.android.gms} when 304032
D/LGDMClient( 3941): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 3941): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,W/ContextImpl( 3941): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
W/libprocessgroup( 1030): failed to open /acct/uid_10080/pid_5524/cgroup.procs: No such file or directory
,W/ContextImpl( 3941): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,D/LGDMClient( 3941): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=3, isUserType=1
I/LGDMClient( 3941): [DmServiceProcessor.java] [processNetworkChanged()] : [91] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
,D/LGDMClient( 3941): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 3941): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
V/DownloadManager( 3291): Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
W/ResourcesManager( 6581): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 6581): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 6581): Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
V/DownloadManager( 3291): DownloadService onCreate
W/ResourcesManager( 6581): Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
I/DownloadManager( 3291): in removeSpuriousFiles
V/DownloadManager( 3291): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 3291): created cursor android.database.sqlite.SQLiteCursor@2110cda1 on behalf of 3291
I/DownloadManager( 3291): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGMyGuide_4.40.09_COM_COM_20150430011620058_RELG-D855.apk
I/DownloadManager( 3291): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGBackup_4.50.37_COM_COM_20150608234245157.apk
I/DownloadManager( 3291): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/CalendarProvider_4.2.8_COM_COM_20150304234552863_RELG-D855.apk
I/DownloadManager( 3291): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calendar_4.40.16_COM_COM_20150304234554754_RELG-D855.apk
I/DownloadManager( 3291): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.10_COM_COM_20150521235426173_RELG-D855.apk
I/DownloadManager( 3291): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQVoiceplusN_2.3.3_COM_COM_20150604065210803.apk
I/DownloadManager( 3291): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.11_COM_COM_v2_20150911144028620_RELG-D855_21.apk
I/DownloadManager( 3291): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQMemoplus(LG-D855_user)_20150902050954661.apk
I/DownloadManager( 3291): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/RemoteCall_4.1.10_COM_COM_20150817053748728.apk
I/DownloadManager( 3291): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/rspermlge(6713)_20150901080430397.apk
I/DownloadManager( 3291): in trimDatabase
V/DownloadManager( 3291): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
V/DownloadManager( 3291): created cursor android.database.sqlite.SQLiteCursor@1e54cbc6 on behalf of 3291
,I/ActivityManager( 1030): Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=6606 uid=10023 gids={50023, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
W/ContextImpl( 3941): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:141 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:180 android.app.IntentService$ServiceHandler.handleMessage:65 
E/LGDMClient( 3941): [DmNotiService.java] [onCreate()] : [148] : DmNotiService.onCreate()
,D/LGDMClient( 3941): [DmNotiService.java] [onStartCommand()] : [182] : in the new onStartCommand()
D/LGDMClient( 3941): [DmNotiService.java] [handleStart()] : [203] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
I/ActivityManager( 1030): Start proc com.android.chrome for service com.android.chrome/com.google.android.apps.chrome.sync.ChromeBrowserSyncAdapterService: pid=6625 uid=10057 gids={50057, 9997, 3003, 1028, 1015} abi=armeabi-v7a
V/DownloadManager( 3291): DownloadService onStartCommand
D/GpsLocationProvider( 1030): updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
V/DownloadManager( 3291): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3291): created cursor android.database.sqlite.SQLiteCursor@1e4ba2dd on behalf of 3291
,V/DownloadManager( 3291): processing inserted download 1
V/DownloadManager( 3291): processing inserted download 4
V/DownloadManager( 3291): processing inserted download 7
V/DownloadManager( 3291): processing inserted download 8
V/DownloadManager( 3291): processing inserted download 9
V/DownloadManager( 3291): processing inserted download 10
V/DownloadManager( 3291): processing inserted download 16
V/DownloadManager( 3291): processing inserted download 17
I/AppConfig( 6581): Total System Memory = 2995761152
V/DownloadManager( 3291): processing inserted download 18
V/DownloadManager( 3291): processing inserted download 21
D/SystemHelper( 6581): region [EU], country [EU], operator [OPEN], sub-operator []
,V/DownloadManager( 3291): DownloadService onDestroy
E/GpsLocationProvider( 1030): No APN found to select.
,W/ResourcesManager( 6606): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6606): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 6606): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
W/ResourcesManager( 6606): Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
,I/ActivityManager( 1030): Killing 5858:com.google.android.apps.docs/u0a61 (adj 15): empty #17
W/libprocessgroup( 1030): failed to open /acct/uid_10061/pid_5858/cgroup.procs: No such file or directory
,I/ReaderUtils( 6562): PortraitW 1440 LandscapeW 2392 SmallestSize 1340 LargestSize 2392 textZoom 4.4999995 isTablet false Memory 256
I/LGEmail ( 6606): [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
D/LGEmail ( 6606): user build Type == true (at Util.java isUserModeBuildType 3507)[v:6.41.18]
,W/DriveInitializer( 2327): Background init thread started
,W/ResourceType( 6606): No package identifier when getting value for resource number 0x00000000
W/GAV2    ( 6562): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
E/Auth.Api.Credentials( 2327): [CredentialSyncAdapter] Unknown sync event.
,I/BooksApp( 6562): Created application version: 3.2.35 (30235)
E/VoldCmdListener(  278): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  278): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.gms/files/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 2327): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.gms/files
W/DriveInitializer( 2327): Awaiting to be initialized
D/LgDataFeature( 6606): LgDataFeature() Constructor: none
D/LgDataFeature( 6606): LgDataFeature() Constructor Done, null
,W/DriveInitializer( 2327): Background init thread ended
,I/ThermalEngine(  328): Thermal-Server: Thermal received msg from  override
,I/Thermal-Lib( 3103): Thermal-Lib-Client: Client request sent
,D/DelayedSyncController( 6625): Delaying sync.
,I/BooksSync( 6562): Starting books sync
,D/eas_req ( 6606): ---addEventToQueue() easCode=2, requestId=0 (at EasSupport.java addEventToQueue 69)
I/ActivityManager( 1030): Killing 5558:com.google.android.apps.plus/u0a97 (adj 15): empty #17
I/art     ( 2125): Explicit concurrent mark sweep GC freed 22225(1277KB) AllocSpace objects, 2(32KB) LOS objects, 51% free, 30MB/62MB, paused 960us total 24.218ms
,I/jxcore-log( 6121): BLE advertisement not supported: MultipleAdvertisement not supported
I/jxcore-log( 6121): 
E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-50 f=2462 sc=60 link=72 tx=32.8, 0.0, 0.0  rx=30.0 bcn=0 [on:0 tx:0 rx:0 period:3106] from screen [on:0 period:1603603523] gl rssi=-50 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-50 f=2462 sc=60 link=72 tx=32.8, 0.0, 0.0  rx=30.0 bcn=0 [on:0 tx:0 rx:0 period:0] from screen [on:0 period:1603603523] gl rssi=-50 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
W/libprocessgroup( 1030): failed to open /acct/uid_10097/pid_5558/cgroup.procs: No such file or directory
,I/VacuumService( 2125): Vacuum at: now=1449007582301 tag=VacuumService
I/GoogleURLConnFactory( 2125): Using platform SSLCertificateSocketFactory
,I/LgeMiscReceiver( 3261): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 3261): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 3261): networkInfo.isConnected() = true
D/PhoneState( 3261): setPdpRejectCasuse : false
I/HubEmail( 6606): JNI_OnLoad()
I/HubEmail( 6606): -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 6606): registerNatives()
I/HubEmail( 6606): -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
,I/HubEmail( 6606): registerNativeMethods()
I/HubEmail( 6606): -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
W/art     ( 6606): JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
,W/Uploader( 2125): No account for auth token provided
,D/libc-netbsd(  311): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  311): res_queryN name = static-avc.lglime.com, class = 1, type = 1
,I/ActivityManager( 1030): Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=6689 uid=10062 gids={50062, 9997, 4002, 3003, 1028} abi=armeabi-v7a
W/Settings( 6606): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 6606): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/DrmBroadcastReceiver( 6689): Receive CONNECTIVITY_ACTION
,D/DrmBroadcastReceiver( 6689): 1  network is available. Sync DRM Time with NTP
D/libc-netbsd(  311): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  311): res_queryN name = www.google.com, class = 1, type = 1
V/DrmService( 6689): Service onCreate
D/DrmService( 6689): Received new request = 2
I/DrmSntpClient( 6689): Start Sync process
D/DrmSntpClient( 6689): Server : 0
D/libc-netbsd(  311): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  311): res_queryN name = pool.ntp.org, class = 1, type = 1
,D/BooksSync( 6562): started syncMyEbooks
,D/libc-netbsd(  311): res_queryN name = static-avc.lglime.com succeed
I/ActivityManager( 1030): Start proc com.lge.sizechangable.weather for broadcast com.lge.sizechangable.weather/.layout.WeatherWidget: pid=6711 uid=10085 gids={50085, 9997, 3003, 1028, 1015} abi=armeabi-v7a
D/libc-netbsd(  311): res_queryN name = www.google.com succeed
D/libc-netbsd(  311): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  311): res_queryN name = clients3.google.com, class = 1, type = 1
D/libc-netbsd(  311): res_queryN name = clients3.google.com succeed
D/libc-netbsd(  311): res_queryN name = pool.ntp.org succeed
,D/libc-netbsd(  311): default dns: query_ipv6=0, query_ipv4=1
I/LGDrmClient( 6689): _DRM_ServiceGet() : Bind lgdrm service
D/libc-netbsd(  311): res_queryN name = play.googleapis.com, class = 1, type = 1
V/ILGDrmService(  324): eDRM_SetDRMTime +++
I/LGDRM   (  324): [DRM] SET TIME : YR=2015, MON=12, DAY=1
I/LGDRM   (  324): [DRM] SET TIME : HR=22, MIN=6, SEC=22
V/ILGDrmService(  324): eDRM_SetDRMTime ---
I/DrmSntpClient( 6689): Synched
D/DrmService( 6689): Completed !! request = 2
D/DrmService( 6689): Request count = 0
V/DrmService( 6689): Service onDestroy
I/ActivityManager( 1030): Killing 5908:com.lge.eula/1000 (adj 15): empty #17
I/art     ( 6711): Almond Protected OAT
V/WifiInternetCheck( 1030): isHttpConnectionAvailable - We got a valid response : 204
,V/FormManager( 6252): There are no updated forms. The schedule will be deleted.
V/FormManager( 6252): Alarm would be updated, because LastCheckTime has been updated.
D/libc-netbsd(  311): res_queryN name = play.googleapis.com succeed
,W/libprocessgroup( 1030): failed to open /acct/uid_1000/pid_5908/cgroup.procs: No such file or directory
,D/WeatherApplication( 6711): removeAccount
D/WeatherApplication( 6711): Account.length = 0
E/WeatherApplication( 6711): OPERATOR:OPEN
D/WeatherAncestor( 6711): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 23:6:22
D/Weather.Utils( 6711): 2 : the weather widgets(using time tick) are gone.
D/Weather.Utils( 6711): 2 : All the weather widget is gone.
D/UpdateThreadPoolManager( 6711): 2 : This is isUpdating : false
,D/WeatherAncestor( 6711): connectivity changed - connection : true
D/WeatherService( 6711): 2 : isServiceAlived():false forecastCache:null
I/ActivityManager( 1030): Killing 5944:com.google.android.gms.wearable/u0a5 (adj 15): empty #17
D/ForecastDataCache( 6711): 2 : lastUpdatedTime: 1430558561343
D/ForecastDataCache( 6711): 2 : currentPackageVersion: 4.40.4
D/ForecastDataCache( 6711): 2 : Cache is not up-to-date, count: 0
D/Weather_cast( 6711): 2 : isUpdateNeedForAlarm : no city return false
,D/WeatherAncestor( 6711): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 23:6:22
I/art     ( 1030): Explicit concurrent mark sweep GC freed 30343(1376KB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 44MB/67MB, paused 1.266ms total 72.733ms
I/ActivityManager( 1030): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=6735 uid=10093 gids={50093, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager( 1030): Killing 6001:com.google.android.talk/u0a72 (adj 15): empty #17
,W/libprocessgroup( 1030): failed to open /acct/uid_10005/pid_5944/cgroup.procs: No such file or directory
,V/GLSActivity( 2125): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/libprocessgroup( 1030): failed to open /acct/uid_10072/pid_6001/cgroup.procs: No such file or directory
,I/GLSUser ( 2125): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2125): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2125): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2125): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2125): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1030): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1030): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1030): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1030): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1030): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
W/GLSActivity( 2125): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2125): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2125): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2125): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2125): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2125): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2125): 	at android.os.Binder.execTransact(Binder.java:446)
E/BooksAccountManager( 6562): Authentication error
E/BooksAccountManager( 6562): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6562): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6562): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6562): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6562): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6562): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6562): null auth token
D/LgeQuickCoverNLService( 1396): onNotificationPosted
D/SmartCoverUpdateMonitor( 1396): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1396): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1396): handleNotificationPosted(true)
D/QuickCircle( 1396): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1396): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1396): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1396): post do just update job
D/LgeQuickCoverNotificationData( 1396): showAll3
D/LgeQuickCoverNotificationData( 1396): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1396): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
D/LgeQuickCoverNotificationData( 1396): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
E/LgeQuickCoverOverlayWindow( 1396): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1396): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1396): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1396): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1396): isNotificationForCurrentUser : true
,D/LgeQuickCoverOverlayWindow( 1396): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1396): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1396): updateNotificationData: count=3
D/libc-netbsd(  311): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  311): res_queryN name = www.googleapis.com, class = 1, type = 1
,E/VoldCmdListener(  278): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  278): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6735): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
E/VoldCmdListener(  278): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  278): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6735): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
D/QuickStatusbarLayout( 1396): Notification difference=198
D/QuickStatusbarLayout( 1396): child = android.widget.LinearLayout{2154d13 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
E/VoldCmdListener(  278): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  278): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6735): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
E/VoldCmdListener(  278): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  278): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6735): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
,D/libc-netbsd(  311): res_queryN name = www.googleapis.com succeed
,W/Uploader( 2125): No account for auth token provided
V/GLSActivity( 2125): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2125): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.syncadapters.contacts, service: cp
,I/GLSUser ( 2125): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> cp without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2125): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2125): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2125): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1030): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1030): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1030): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1030): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1030): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1396): onNotificationPosted
W/GLSActivity( 2125): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2125): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2125): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2125): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2125): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2125): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2125): 	at android.os.Binder.execTransact(Binder.java:446)
D/SmartCoverUpdateMonitor( 1396): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1396): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1396): handleNotificationPosted(true)
D/QuickCircle( 1396): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1396): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1396): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1396): post do just update job
D/LgeQuickCoverNotificationData( 1396): showAll3
D/LgeQuickCoverNotificationData( 1396): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1396): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
D/LgeQuickCoverNotificationData( 1396): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
E/LgeQuickCoverOverlayWindow( 1396): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1396): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1396): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1396): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1396): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1396): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1396): isNotificationForCurrentUser : true
D/ContactsSyncAdapter( 2125): innerSync failed
D/ContactsSyncAdapter( 2125): com.google.wireless.gdata2.client.AuthenticationException: unable to get auth token android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
D/ContactsSyncAdapter( 2125): 	at com.google.android.syncadapters.contacts.AuthInfo.getAuthToken(AuthInfo.java:45)
D/ContactsSyncAdapter( 2125): 	at com.google.android.syncadapters.contacts.ContactsSyncAdapter.innerPerformSync(ContactsSyncAdapter.java:263)
D/ContactsSyncAdapter( 2125): 	at com.google.android.syncadapters.contacts.ContactsSyncAdapter.onPerformLoggedSync(ContactsSyncAdapter.java:168)
D/ContactsSyncAdapter( 2125): 	at com.google.android.common.LoggingThreadedSyncAdapter.onPerformSync(LoggingThreadedSyncAdapter.java:33)
D/ContactsSyncAdapter( 2125): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
D/ContactsSyncAdapter( 2125): Caused by: android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
D/ContactsSyncAdapter( 2125): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
D/ContactsSyncAdapter( 2125): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
D/ContactsSyncAdapter( 2125): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
D/ContactsSyncAdapter( 2125): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAcco,untManagerResponse.java:69)
D/ContactsSyncAdapter( 2125): 	at android.os.Binder.execTransact(Binder.java:446)
E/LgeQuickCoverOverlayWindow( 1396): updateNotificationData: count=3
W/Uploader( 2125):  no longer exists, so no auth token.
,D/QuickStatusbarLayout( 1396): Notification difference=198
D/QuickStatusbarLayout( 1396): child = android.widget.LinearLayout{2154d13 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
D/SyncManager( 1030): failed sync operation thalitester@gmail.com u0 (com.google), com.android.contacts, LOCAL, currentRunTime 26840, reason: 10019, SyncResult: stats [ numAuthExceptions: 1]
D/SyncManager( 1030): not retrying sync operation because the error is a hard error: thalitester@gmail.com u0 (com.google), com.android.contacts, LOCAL, currentRunTime 335672, reason: 10019
,I/WebViewFactory( 6735): Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,W/Uploader( 2125): No account for auth token provided
I/LibraryLoader( 6735): Loading: webviewchromium
D/DelayedSyncController( 6625): Delaying sync.
I/LibraryLoader( 6735): Time to load native libraries: 3 ms (timestamps 5271-5274)
I/LibraryLoader( 6735): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 6735): Binding Chromium to main looper Looper (main, tid 1) {386208a2}
I/LibraryLoader( 6735): Expected native library version number "",actual native library version number ""
I/chromium( 6735): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 6735): Initializing chromium process, renderers=0
,W/art     ( 6735): Attempt to remove local handle scope entry from IRT, ignoring
V/AudioPolicyService(  316): registerClient() client 0xb14272c0, uid 10093
W/chromium( 6735): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
W/AudioManagerAndroid( 6735): Requires BLUETOOTH permission
I/chromium( 6735): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=38 off=46780 len=2953
I/chromium( 6735): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:39 off:229536 len:643667
W/ApiaryClient( 6562): Error response from books API: {
W/ApiaryClient( 6562):  "error": {
W/ApiaryClient( 6562):   "errors": [
W/ApiaryClient( 6562):    {
W/ApiaryClient( 6562):     "domain": "global",
W/ApiaryClient( 6562):     "reason": "required",
W/ApiaryClient( 6562):     "message": "Login Required",
W/ApiaryClient( 6562):     "locationType": "header",
W/ApiaryClient( 6562):     "location": "Authorization"
W/ApiaryClient( 6562):    }
W/ApiaryClient( 6562):   ],
W/ApiaryClient( 6562):   "code": 401,
W/ApiaryClient( 6562):   "message": "Login Required"
W/ApiaryClient( 6562):  }
W/ApiaryClient( 6562): }
W/ApiaryClient( 6562): errCount = 1: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6562): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=1766505430382513662&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6562): Headers:
W/ApiaryClient( 6562): accept-encoding: [gzip]
W/ApiaryClient( 6562): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6562): gdata-version: 2
,I/Adreno-EGL( 6735): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 6735): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 6735): Build Date: 12/12/14 금
I/Adreno-EGL( 6735): Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
I/Adreno-EGL( 6735): Remote Branch: 
I/Adreno-EGL( 6735): Local Patches: 
I/Adreno-EGL( 6735): Reconstruct Branch: 
,W/Uploader( 2125): No account for auth token provided
I/ActivityManager( 1030): Start proc com.google.android.apps.plus for service com.google.android.apps.plus/.service.EsSyncAdapterService: pid=6794 uid=10097 gids={50097, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/NSApplication( 6735): Starting up...
,W/Uploader( 2125): No account for auth token provided
I/ActivityManager( 1030): Killing 4847:com.android.vending/u0a44 (adj 15): empty #17
,W/ResourcesManager( 6794): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
D/UEI.SmartControl( 5839): Internal timer expired: 2
D/UEI.SmartControl( 5839): unbind internal service
,W/libprocessgroup( 1030): failed to open /acct/uid_10044/pid_4847/cgroup.procs: No such file or directory
,D/serial_port( 5839): close(fd = 24)
I/UEI.SmartControl( 5839): Serial port is closed.
,D/libc-netbsd(  311): default dns: query_ipv6=0, query_ipv4=1
,D/libc-netbsd(  311): res_queryN name = mtalk.google.com, class = 1, type = 1
,I/iu.SyncManager( 2327): SYNC; picasa accounts
,I/GLSActivity( 2125): [ac] getting account id
,I/GLSUser ( 2125): [t] Fetched account id for thalitester@gmail.com : 105256135866144380227
D/NetworkLogImpl( 2327): Loaded NetworkSpeedPredictor
,I/iu.Environment( 2327): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
D/libc-netbsd(  311): res_queryN name = mtalk.google.com succeed
I/iu.UploadsManager( 2327): num queued entries: 0
I/iu.UploadsManager( 2327): num updated entries: 0
,I/iu.SyncManager( 2327): NEXT; no task
D/ChimeraCfgMgr( 2327): Loading module com.google.android.gms.kids from APK com.google.android.gms
D/ChimeraCfgMgr( 2327): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/PostponalbeReceiver( 5128): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.intent.action.TIME_SET'.
I/ActivityManager( 1030): Start proc com.lge.clock for broadcast com.lge.clock/.alarmclock.ALBootInit: pid=6838 uid=10010 gids={50010, 9997, 3003, 1028, 4002} abi=armeabi-v7a
,I/GLSUser ( 2125): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: ac2dm
,I/GLSUser ( 2125): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> ac2dm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2125): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2125): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2125): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/NotificationService( 1030): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
V/NotificationService( 1030): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1030): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1030): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1030): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1396): onNotificationPosted
D/SmartCoverUpdateMonitor( 1396): received broadcast com.lge.intent.action.NLDataPosted
,E/SmartCoverUpdateMonitor( 1396): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1396): handleNotificationPosted(true)
D/QuickCircle( 1396): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1396): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1396): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1396): post do just update job
D/LgeQuickCoverNotificationData( 1396): showAll3
D/LgeQuickCoverNotificationData( 1396): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1396): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
D/LgeQuickCoverNotificationData( 1396): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
E/LgeQuickCoverOverlayWindow( 1396): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1396): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1396): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1396): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1396): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1396): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1396): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1396): updateNotificationData: count=3
D/ALBootInit( 6838): ====action==>android.intent.action.TIME_SET
D/ALBootInit( 6838): Alarm ALBootInit: TIME_SET
,D/Alarms  ( 6838): [setNextAlert] start
D/QuickStatusbarLayout( 1396): Notification difference=198
D/QuickStatusbarLayout( 1396): child = android.widget.LinearLayout{2154d13 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
D/Alarms  ( 6838): [setNextAlert] (1)
,D/Alarms  ( 6838):  minTime  = 0
D/Alarms  ( 6838):  -- OK multi -- 0
E/jeny.kim( 6838): [setNextAlert] setNextAlert  temp_Alarmlink + 
E/jeny.kim( 6838): [setNextAlert]setNextAlert temp_AlarmLinkText + 
,I/CommonUtil( 6838): BUILD Country: EU
D/Alarms  ( 6838): broadcastToWidgetProvider : false
D/Alarms  ( 6838): Enter formatDayAndTime(final Context context, long timeInMiliSec)
W/Kids    ( 2327): [AccountUtils] Account not ready
W/Kids    ( 2327): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/Kids    ( 2327): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/Kids    ( 2327): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/Kids    ( 2327): 	at com.google.android.gms.auth.p.c(SourceFile:550)
W/Kids    ( 2327): 	at com.google.android.gms.auth.p.b(SourceFile:477)
W/Kids    ( 2327): 	at com.google.android.gms.kids.account.k.d(SourceFile:103)
W/Kids    ( 2327): 	at com.google.android.gms.kids.account.p.a(SourceFile:70)
W/Kids    ( 2327): 	at com.google.android.gms.kids.account.t.a(SourceFile:62)
W/Kids    ( 2327): 	at com.google.android.gms.chimera.f.run(SourceFile:179)
W/Kids    ( 2327): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Kids    ( 2327): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Kids    ( 2327): 	at java.lang.Thread.run(Thread.java:818)
V/SettingsProvider( 1030): call_put(system:next_alarm_formatted=) for 0 calling package = com.lge.clock
I/DigitalAppWidgetProvider( 6838): onReceive: android.intent.action.TIME_SET
,V/DigitalAppWidgetProvider( 6838): cancelAlarmOnQuarterHour android.app.ReceiverRestrictedContext@5501fa8
V/DigitalAppWidgetProvider( 6838): startAlarmOnQuarterHour android.app.ReceiverRestrictedContext@5501fa8
D/QuickCoverProvider( 6838): onReceiver
V/GLSActivity( 2125): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/indal   ( 1396): SmartCoverWidgetContext createApplicationContext
I/indal   ( 1396): SmartCoverWidgetContext createApplicationContext
D/WeatherAncestor( 6711): 2 : onReceive, action: android.intent.action.TIME_SET, Time(hour:min:sec) 23:6:23
,D/Weather.Utils( 6711): 2 : the weather widgets(using time tick) are gone.
D/Weather.Utils( 6711): 2 : All the weather widget is gone.
D/UpdateThreadPoolManager( 6711): 2 : This is isUpdating : false
D/WeatherService( 6711): 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@10b2dac1
D/ForecastDataCache( 6711): 2 : lastUpdatedTime: 1430558561343
D/ForecastDataCache( 6711): 2 : currentPackageVersion: 4.40.4
D/ForecastDataCache( 6711): 2 : Cache is up-to-date, count: 0
D/Weather_cast( 6711): 2 : set auto-update time : 12/2 2:6
D/WeatherAncestor( 6711): 2 : onReceive has processed, action: android.intent.action.TIME_SET, Time(hour:min:sec) 23:6:23
,I/GLSUser ( 2125): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.syncadapters.contacts, service: cp
I/GLSUser ( 2125): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> cp without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2125): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2125): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
D/GCM     ( 2125): Connected
,I/art     ( 1030): Explicit concurrent mark sweep GC freed 23233(1018KB) AllocSpace objects, 4(448KB) LOS objects, 33% free, 44MB/67MB, paused 1.542ms total 86.175ms
I/ActivityManager( 1030): Start proc com.qualcomm.timeservice for broadcast com.qualcomm.timeservice/.TimeServiceBroadcastReceiver: pid=6870 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
I/ActivityManager( 1030): Killing 5925:com.lge.bnr/1000 (adj 15): empty #17
,W/libprocessgroup( 1030): failed to open /acct/uid_1000/pid_5925/cgroup.procs: No such file or directory
,V/GLSActivity( 2125): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GCM     ( 2125): Ack for not saved message 71
D/GCM     ( 2125): Message class com.google.f.a.a.p
V/NotificationService( 1030): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1030): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1030): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1030): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1030): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
W/GLSActivity( 2125): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2125): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2125): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2125): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2125): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2125): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2125): 	at android.os.Binder.execTransact(Binder.java:446)
D/LgeQuickCoverNLService( 1396): onNotificationPosted
D/ContactsSyncAdapter( 2125): innerSync failed
D/ContactsSyncAdapter( 2125): com.google.wireless.gdata2.client.AuthenticationException: unable to get auth token android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
D/ContactsSyncAdapter( 2125): 	at com.google.android.syncadapters.contacts.AuthInfo.getAuthToken(AuthInfo.java:45)
D/ContactsSyncAdapter( 2125): 	at com.google.android.syncadapters.contacts.ContactsSyncAdapter.innerPerformSync(ContactsSyncAdapter.java:263)
D/ContactsSyncAdapter( 2125): 	at com.google.android.syncadapters.contacts.ContactsSyncAdapter.onPerformLoggedSync(ContactsSyncAdapter.java:168)
D/ContactsSyncAdapter( 2125): 	at com.google.android.common.LoggingThreadedSyncAdapter.onPerformSync(LoggingThreadedSyncAdapter.java:33)
D/ContactsSyncAdapter( 2125): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
D/ContactsSyncAdapter( 2125): Caused by: android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
D/ContactsSyncAdapter( 2125): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
D/ContactsSyncAdapter( 2125): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
D/ContactsSyncAdapter( 2125): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
D/ContactsSyncAdapter( 2125): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
D/ContactsSyncAdapter( 2125): 	at android.os.Binder.execTransact(Binder.java:446)
D/SmartCoverUpdateMonitor( 1396): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1396): MSG_NOTIFICATION_POSTED
,D/SmartCoverUpdateMonitor( 1396): handleNotificationPosted(true)
D/QuickCircle( 1396): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1396): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1396): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1396): post do just update job
,D/LgeQuickCoverNotificationData( 1396): showAll3
D/LgeQuickCoverNotificationData( 1396): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1396): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
D/LgeQuickCoverNotificationData( 1396): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
E/LgeQuickCoverOverlayWindow( 1396): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1396): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1396): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1396): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1396): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1396): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1396): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1396): updateNotificationData: count=3
D/TimeService( 6870): Receivedandroid.intent.action.TIME_SET intent. Current Time is 1449007583564
D/        ( 6870): TimeServiceNative: User Time to be set is 1449007583564
D/QC-time-services( 6870): Lib:time_genoff_operation: pargs->base = 2
D/QC-time-services( 6870): Lib:time_genoff_operation: pargs->operation = 0
D/QC-time-services( 6870): Lib:time_genoff_operation: pargs->ts_val = 1449007583564
D/QC-time-services( 6870): Lib:time_genoff_operation: Send to server  passed!!
D/QC-time-services(  361): Daemon: Connection accepted:time_genoff
D/QC-time-services(  361): Daemon:Received base = 2, unit = 1, operation = 0,value = 1449007583564
D/QC-time-services(  361): Daemon:genoff_opr: Base = 2, val = 1449007583564, operation = 0
D/QC-time-services(  361): Daemon:rtc_get: Time read from RTC -- MM/DD/YY HH:MM:SS3/10/70 15:19:11
D/QC-time-services(  361): Daemon:Value read from RTC seconds = 8608751000
D/QC-time-services(  361): Daemon:new time 1449007583564 
D/QC-time-services(  361): Daemon: delta 1440398832564 genoff 1440398832564 
D/QC-time-services(  361): Daemon:genoff_persistent_update: Writing genoff = 1440398832564 to memory
D/QC-time-services(  361): Daemon:Opening File: /data/time/ats_2
D/QC-time-services(  361): Daemon:time_persistent_memory_opr:Genoff write operation 
D/SyncManager( 1030): failed sync operation thalitester@gmail.com u0 (com.google), com.android.contacts, LOCAL, currentRunTime 335672, reason: 10019, SyncResult: stats [ numAuthExceptions: 1]
,D/QuickStatusbarLayout( 1396): Notification difference=198
D/QuickStatusbarLayout( 1396): child = android.widget.LinearLayout{2154d13 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
D/QC-time-services(  361): Updating the TOD offset
D/QC-time-services(  361): Daemon:genoff_persistent_update: Writing genoff = 1440398832564 to memory
D/QC-time-services(  361): Daemon:Opening File: /data/time/ats_1
D/QC-time-services(  361): Daemon:time_persistent_memory_opr:Genoff write operation 
E/QC-time-services(  361): Daemon:Update to modem bit set
D/QC-time-services(  361): Daemon:genoff_send_modem: Sending data to MODEM !
,D/QC-time-services(  361): Daemon: Base = 2, Value being sent to MODEM = 1124434032564
,E/QC-time-services( 6870): Receive Passed == base = 2, unit = 1, operation = 0, result = 0
E/QC-time-services(  361): Daemon:tod_update_ind_cb: Got Update from modem msg_id 40
E/QC-time-services(  361): Daemon: Time-services: Waiting to acceptconnection
I/ActivityManager( 1030): Start proc com.android.calendar for broadcast com.android.calendar/.widget.CalendarAppWidgetProvider: pid=6890 uid=10013 gids={50013, 9997, 3003, 1028, 1015} abi=armeabi
,I/ActivityManager( 1030): Killing 6312:com.lge.lifetracker/u0a37 (adj 15): empty #17
W/libprocessgroup( 1030): failed to open /acct/uid_10037/pid_6312/cgroup.procs: No such file or directory
,W/ResourcesManager( 6890): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,D/CalendarApplication( 6890): CalendarApplication.onCreate()
,D/PreferenceKeysParser( 6890): [debug_displayParseInfos] preference keys.size() = 44
,D/PreferenceKeysParser( 6890): [debug_displayParseInfos] preference keys = {lg_preferences_tardis_1=com.android.calendar.adaptation.PreferenceKey$KeyData@e1533af, lg_preferences_hide_declined=com.android.calendar.adaptation.PreferenceKey$KeyData@1d2083bc, lg_preferences_default_reminder=com.android.calendar.adaptation.PreferenceKey$KeyData@2e638f45, lg_preferences_month_view_style=com.android.calendar.adaptation.PreferenceKey$KeyData@2a69369a, lg_preferences_alerts_ringtone=com.android.calendar.adaptation.PreferenceKey$KeyData@328b5bcb, lg_preferences_device_tz=com.android.calendar.adaptation.PreferenceKey$KeyData@5501fa8, lg_preferences_debug_datesearch=com.android.calendar.adaptation.PreferenceKey$KeyData@10b2dac1, lg_preferences_debug_country=com.android.calendar.adaptation.PreferenceKey$KeyData@d142266, lg_preferences_display_weather_information=com.android.calendar.adaptation.PreferenceKey$KeyData@34f1e9a7, lg_preferences_alerts_vibrateWhen=com.android.calendar.adaptation.PreferenceKey$KeyData@1e5b8e54, lg_preferences_debug_rtl=com.android.calendar.adaptation.PreferenceKey$KeyData@3b5161fd, lg_preferences_alerts_type=com.android.calendar.adaptation.PreferenceKey$KeyData@142ffef2, lg_preferrences_country_code=com.android.calendar.adaptation.PreferenceKey$KeyData@19497943, lg_preferences_weather_info=com.android.calendar.adaptation.PreferenceKey$KeyData@340d3bc0, lg_preference_holiday_calendar_ver=com.android.calendar.adaptation.PreferenceKey$KeyData@285720f9, lg_preferences_show_controls=com.android.calendar.adaptation.PreferenceKey$KeyData@32bb183e, lg_preferences_user_select_noti_sound=com.android.calendar.adaptation.PreferenceKey$KeyData@1900669f, lg_preference_default_myphonebook=com.android.calendar.adaptation.PreferenceKey$KeyData@26a53ec, lg_preferences_skip_setup=com.android.calendar.adaptation.PreferenceKey$KeyData@15fd3b5, lg_preferred_startView=com.android.calendar.adaptation.PreferenceKey$KeyData@3b4c7a4a, lg_preferences_debug_operator=com.android.calendar.adaptation.PreferenceKey$KeyData@2c0ecdbb, lg_preferences_exclude_sticker_list=com.android.calendar.adaptation.PreferenceKey$KeyData@1e9ec2d8, lg_preferences_writable_calendars_count=com.android.calendar.adaptation.PreferenceKey$KeyData@3406f631, lg_preferred_detailedView=com.android.calendar.adaptation.PreferenceKey$KeyData@20dff116, lg_preferences_debug_floating=com.android.calendar.adaptation.PreferenceKey$KeyData@7d28a97, lg_preferences_home_tz=com.android.calendar.adaptation.PreferenceKey$KeyData@2a93484, lg_preferences_home_tz_enabled=com.android.calendar.adaptation.PreferenceKey$KeyData@1223c46d, lg_preference_received_provider_reminder_broadcast=com.android.calendar.adaptation.PreferenceKey$KeyData@386208a2, lg_preferences_default_cell_height=com.android.calendar.adaptation.PreferenceKey$KeyData@2fab3933, lg_preferences_notification_type=com.android.calendar.adaptation.PreferenceKey$KeyData@27c714f0, lg_preferences_show_week_num=com.android.calendar.adaptation.PreferenceKey$KeyData@39c53a69, lg_preferences_dont_show_again_no_online_account=com.android.calendar.adaptation.PreferenceKey$KeyData@6fc0cee, lg_preferences_alerts_popup=com.android.calendar.adaptation.PreferenceKey$KeyData@3356358f, lg_preferences_week_start_day=com.android.calendar.adaptation.PreferenceKey$KeyData@1ba0901c, lg_preferences_app_version=com.android.calendar.adaptation.PreferenceKey$KeyData@ee1425, lg_preferences_alerts=com.android.calendar.adaptation.PreferenceKey$KeyData@292009fa, lg_preferences_select_aux_calendar=com.android.calendar.adaptation.PreferenceKey$KeyData@370a9bab, lg_preferences_widget_info_calendars=com.android.calendar.adaptation.PreferenceKey$KeyData@3c349208, lg_preferences_alerts_default_ringtone=com.android.calendar.adaptation.PreferenceKey$KeyData@2110cda1, lg_preference_defaultCalendar=com.android.calendar.adaptation.PreferenceKey$KeyData@1e54cbc6, lg_preferences_alerts_vibratetype=com.android.calendar.adaptation.PreferenceKey$KeyData@21554787, lg_preferences_recent_timezones=com.android.calendar.adaptation.PreferenceKey$KeyData@684c6b4,
D/GeneralP,referenceUtils( 6890): [migratePrefrenceKeys] Exit: Version(44001600) >= 42001300
,D/Config  ( 6890): [init]
I/Config  ( 6890): LGCalendar ver.4.40.16
I/Config  ( 6890): start check model
I/Config  ( 6890): start check native_ca
I/Config  ( 6890): Config Operator=OPEN, Country=EU
D/Config  ( 6890): [setDefaultValuesToPref]
,D/Config  ( 6890): [parseProfiles]
D/ProfilesParser( 6890): [debug_displayParseInfos] profile.country = null
D/ProfilesParser( 6890): [debug_displayParseInfos] profile.operator = null
D/Config  ( 6890): [updateProfiletoCountryInfo]
D/GeneralPreference( 6890): [checkAndMigrateOldPreference]
E/AgendaWidgetManager( 6890): [updateWidgets] 
,V/GLSActivity( 2125): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2125): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2125): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2125): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2125): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2125): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1030): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1030): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1030): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1030): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1030): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1396): onNotificationPosted
,D/SmartCoverUpdateMonitor( 1396): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1396): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1396): handleNotificationPosted(true)
D/QuickCircle( 1396): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1396): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1396): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1396): post do just update job
D/LgeQuickCoverNotificationData( 1396): showAll3
D/LgeQuickCoverNotificationData( 1396): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1396): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
D/LgeQuickCoverNotificationData( 1396): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
E/LgeQuickCoverOverlayWindow( 1396): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1396): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1396): isNotificationForCurrentUser : true,
D/LgeQuickCoverOverlayWindow( 1396): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1396): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1396): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1396): isNotificationForCurrentUser : true
W/GLSActivity( 2125): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2125): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2125): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2125): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2125): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2125): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2125): 	at android.os.Binder.execTransact(Binder.java:446)
E/LgeQuickCoverOverlayWindow( 1396): updateNotificationData: count=3
E/BooksAccountManager( 6562): Authentication error
E/BooksAccountManager( 6562): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6562): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6562): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6562): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6562): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6562): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6562): null auth token
D/QuickStatusbarLayout( 1396): Notification difference=198
D/QuickStatusbarLayout( 1396): child = android.widget.LinearLayout{2154d13 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,I/InitNotificationRingtoneService( 6890): Start InitializeAlertRingtoneService.onHandleIntent
I/AlertUtils( 6890): [setFormatNotificationSound] current noti URI = content://media/internal/audio/media/41
D/MonthWidgetProvider( 6890): [onReceive]
D/CalendarWidgetProvider( 6890): [onReceive]
,D/CalendarWidgetProvider( 6890): [CalendarWidgetProvider] got the intent: Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.android.calendar/.widget.MonthWidgetProvider }
W/HolidayIntentService( 6890): onHandleIntent
D/HolidayDataLoader( 6890): readJsonAsset : holiday.json
D/CalendarTypeController( 6890): [onUpdateAndInitCalendarTime]
D/WeekWidgetProvider( 6890): [onReceive]
D/CalendarWidgetProvider( 6890): [onReceive]
D/CalendarWidgetProvider( 6890): [CalendarWidgetProvider] got the intent: Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.android.calendar/.widget.WeekWidgetProvider }
,I/AlertUtils( 6890): [getCalendarNotiSoundURIFromCursor] getCount()= 21
,D/CalendarTypeController( 6890): [onUpdateAndInitCalendarTime]
I/AlertUtils( 6890): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Arpeggio.ogg
I/AlertUtils( 6890): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Country_Blues.ogg
I/AlertUtils( 6890): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Crystal.ogg
,I/AlertUtils( 6890): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Dewdrop.ogg
I/AlertUtils( 6890): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Ding_Dong.ogg
W/ApiaryClient( 6562): Error response from books API: {
W/ApiaryClient( 6562):  "error": {
W/ApiaryClient( 6562):   "errors": [
W/ApiaryClient( 6562):    {
W/ApiaryClient( 6562):     "domain": "global",
W/ApiaryClient( 6562):     "reason": "required",
W/ApiaryClient( 6562):     "message": "Login Required",
W/ApiaryClient( 6562):     "locationType": "header",
W/ApiaryClient( 6562):     "location": "Authorization"
W/ApiaryClient( 6562):    }
W/ApiaryClient( 6562):   ],
W/ApiaryClient( 6562):   "code": 401,
W/ApiaryClient( 6562):   "message": "Login Required"
W/ApiaryClient( 6562):  }
W/ApiaryClient( 6562): }
W/ApiaryClient( 6562): errCount = 2: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6562): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=1766505430382513662&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6562): Headers:
W/ApiaryClient( 6562): accept-encoding: [gzip]
W/ApiaryClient( 6562): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6562): gdata-version: 2
,I/AlertUtils( 6890): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Echo.ogg
,I/AlertUtils( 6890): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Email.ogg
I/AlertUtils( 6890): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Game_Over.ogg
I/AlertUtils( 6890): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Gayageum.ogg
,I/AlertUtils( 6890): [getMediaFilepathFromContentUri] filepath = /system/media/audio/alarms/Afternoon_Walk.ogg
I/DigitalAppWidgetProvider( 6838): onReceive: android.intent.action.ALARM_CHANGED
I/AlertUtils( 6890): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Harmonics.ogg
,D/WeatherAncestor( 6711): 2 : onReceive, action: com.lge.sizechangable.weather.action.setweathercast, Time(hour:min:sec) 23:6:24
I/AlertUtils( 6890): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Idea.ogg
D/Weather.Utils( 6711): 2 : the weather widgets(using time tick) are gone.
D/Weather.Utils( 6711): 2 : All the weather widget is gone.
D/UpdateThreadPoolManager( 6711): 2 : This is isUpdating : false
I/AlertUtils( 6890): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/News.ogg
D/Weather_cast( 6711): 2 : Update is Canceled by com.lge.sizechangable.weather.action.alarm
D/WeatherAncestor( 6711): 2 : onReceive has processed, action: com.lge.sizechangable.weather.action.setweathercast, Time(hour:min:sec) 23:6:24
,I/AlertUtils( 6890): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Pebble.ogg
I/AlertUtils( 6890): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Schedule.ogg
I/AlertUtils( 6890): [getCalendarNotiSoundURIFromCursor] filePath = /system/media/audio/notifications/Schedule.ogg, new URI = content://media/internal/audio/media/41
E/HolidayIntentService( 6890): onHandleIntent:holiday data empty
I/ActivityManager( 1030): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.realtimechat.RequestWriter$NetworkStateReceiver: pid=6930 uid=10072 gids={50072, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,I/AlertUtils( 6890): set default noti to content://media/internal/audio/media/41
I/art     (  338): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 299us total 14.133ms
,I/InitNotificationRingtoneService( 6890): End InitializeAlertRingtoneService.onHandleIntent
I/ActivityManager( 1030): Killing 6365:com.lge.settings.easy/1000 (adj 15): empty #17
I/art     (  338): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 266us total 13.717ms
,I/art     (  338): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 258us total 11.914ms
W/libprocessgroup( 1030): failed to open /acct/uid_1000/pid_6365/cgroup.procs: No such file or directory
,W/ResourcesManager( 6930): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,D/LgDataFeature( 6930): LgDataFeature() Constructor: none
D/LgDataFeature( 6930): LgDataFeature() Constructor Done, null
,I/Babel   ( 6930): MmsConfig: mnc/mcc: 0/0
I/Babel   ( 6930): MmsConfig.loadMmsSettings
I/Babel   ( 6930): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D855 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D855-M3-D1.xml
I/Babel   ( 6930): MmsConfig.loadFromDatabase
,E/Babel   ( 6930): canonicalizeMccMnc: invalid mccmnc 
I/Babel   ( 6930): MmsConfig.loadFromResources
E/Babel   ( 6930): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel   ( 6930): MmsConfig.loadMmsSettings: mUserAgent=LG-D855 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D855-M3-D1.xml
,W/Settings( 6930): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/AudioCapabilities( 6930): Unsupported mime audio/evrc
W/AudioCapabilities( 6930): Unsupported mime audio/qcelp
W/VideoCapabilities( 6930): Unrecognized profile 2130706433 for video/avc
W/AudioCapabilities( 6930): Unsupported mime audio/amr-wb-plus
W/AudioCapabilities( 6930): Unsupported mime audio/qcelp
,W/AudioCapabilities( 6930): Unsupported mime audio/evrc
W/VideoCapabilities( 6930): Unsupported mime video/x-ms-wmv
,W/VideoCapabilities( 6930): Unsupported mime video/divx
W/VideoCapabilities( 6930): Unsupported mime video/divx311
W/VideoCapabilities( 6930): Unsupported mime video/divx4
W/VideoCapabilities( 6930): Unsupported mime video/mp4v-esdp
I/VideoCapabilities( 6930): Unsupported profile 4 for video/mp4v-es
,W/AudioCapabilities( 6930): Unsupported mime audio/eac3
W/AudioCapabilities( 6930): Unsupported mime audio/ac3
W/ResourcesManager( 6930): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6930): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
W/AudioCapabilities( 6930): Unsupported mime audio/g726
W/AudioCapabilities( 6930): Unsupported mime audio/wma-voice
W/AudioCapabilities( 6930): Unsupported mime audio/x-ms-wma
W/AudioCapabilities( 6930): Unsupported mime audio/adpcm
W/VideoCapabilities( 6930): Unsupported mime video/theora
,W/VideoCapabilities( 6930): Unsupported mime video/mjpg
V/JNIHelp ( 6930): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,W/System  ( 6930): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/system/framework/com.google.android.media.effects.jar", zip file "/system/app/Hangouts/Hangouts.apk"],nativeLibraryDirectories=[/system/app/Hangouts/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6930): Installed default security provider GmsCore_OpenSSL
,V/GLSActivity( 2125): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2125): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2125): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2125): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 2125): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2125): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/GLSUser ( 2125): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.talk, service: oauth2:https://www.googleapis.com/auth/chat https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/hangouts https://www.googleapis.com/auth/identity.plus.page.impersonation https://www.googleapis.com/auth/chat.native
I/GLSUser ( 2125): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/chat https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/hangouts https://www.googleapis.com/auth/identity.plus.page.impersonation https://www.googleapis.com/auth/chat.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2125): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2125): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2125): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1030): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
V/NotificationService( 1030): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1030): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1030): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1030): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,W/GLSActivity( 2125): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2125): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2125): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2125): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2125): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2125): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2125): 	at android.os.Binder.execTransact(Binder.java:446)
D/LgeQuickCoverNLService( 1396): onNotificationPosted
E/BooksAccountManager( 6562): Authentication error
E/BooksAccountManager( 6562): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6562): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6562): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6562): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6562): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6562): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6562): null auth token
D/SmartCoverUpdateMonitor( 1396): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1396): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1396): handleNotificationPosted(true)
D/QuickCircle( 1396): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1396): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1396): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1396): post do just update job
D/LgeQuickCoverNotificationData( 1396): showAll3
D/LgeQuickCoverNotificationData( 1396): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1396): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
D/LgeQuickCoverNotificationData( 1396): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
E/LgeQuickCoverOverlayWindow( 1396): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1396): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1396): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1396): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1396): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1396): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1396): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1396): updateNotificationData: count=3
,E/Babel   ( 6930): UserRecoverableAuthException.
E/Babel   ( 6930): cfq: BadAuthentication
E/Babel   ( 6930): 	at cfn.a(Unknown Source)
E/Babel   ( 6930): 	at f.a(PG:191)
E/Babel   ( 6930): 	at ava.a(PG:88)
E/Babel   ( 6930): 	at ava.a(PG:128)
E/Babel   ( 6930): 	at bjs.a(PG:255)
E/Babel   ( 6930): 	at bep.a(PG:602)
E/Babel   ( 6930): 	at bep.a(PG:469)
E/Babel   ( 6930): 	at bpo.run(PG:1141)
E/Babel   ( 6930): Error getting auth token
E/Babel   ( 6930): bxl
E/Babel   ( 6930): 	at f.a(PG:201)
E/Babel   ( 6930): 	at ava.a(PG:88)
E/Babel   ( 6930): 	at ava.a(PG:128)
E/Babel   ( 6930): 	at bjs.a(PG:255)
E/Babel   ( 6930): 	at bep.a(PG:602)
E/Babel   ( 6930): 	at bep.a(PG:469)
E/Babel   ( 6930): 	at bpo.run(PG:1141)
I/Babel_RequestWriter( 6930): error sending REQ[fc:12; creat:1448988542951; type:bev-1052113185]; took 124 ms (error code == 100)
E/Babel   ( 6930): Account registration failedRedacted-21
E/Babel   ( 6930): bph: null -- null
E/Babel   ( 6930): 	at ava.a(PG:120)
E/Babel   ( 6930): 	at ava.a(PG:128)
E/Babel   ( 6930): 	at bjs.a(PG:255)
E/Babel   ( 6930): 	at bep.a(PG:602)
E/Babel   ( 6930): 	at bep.a(PG:469)
E/Babel   ( 6930): 	at bpo.run(PG:1141)
I/Babel   ( 6930): Account setup failed with error state:106 account:Redacted-21
I/Babel   ( 6930): Account sign in complete with state 106account: Redacted-21
D/QuickStatusbarLayout( 1396): Notification difference=198
D/QuickStatusbarLayout( 1396): child = android.widget.LinearLayout{2154d13 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
I/art     ( 6930): Note: end time exceeds epoch: 
,I/GLSUser ( 2125): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.talk, service: oauth2:https://www.googleapis.com/auth/chat https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/hangouts https://www.googleapis.com/auth/identity.plus.page.impersonation https://www.googleapis.com/auth/chat.native
I/GLSUser ( 2125): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/chat https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/hangouts https://www.googleapis.com/auth/identity.plus.page.impersonation https://www.googleapis.com/auth/chat.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2125): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2125): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2125): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/ResourcesManager( 2125): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,W/ApiaryClient( 6562): Error response from books API: {
W/ApiaryClient( 6562):  "error": {
W/ApiaryClient( 6562):   "errors": [
W/ApiaryClient( 6562):    {
W/ApiaryClient( 6562):     "domain": "global",
W/ApiaryClient( 6562):     "reason": "required",
W/ApiaryClient( 6562):     "message": "Login Required",
W/ApiaryClient( 6562):     "locationType": "header",
W/ApiaryClient( 6562):     "location": "Authorization"
W/ApiaryClient( 6562):    }
W/ApiaryClient( 6562):   ],
W/ApiaryClient( 6562):   "code": 401,
W/ApiaryClient( 6562):   "message": "Login Required"
W/ApiaryClient( 6562):  }
W/ApiaryClient( 6562): }
W/ApiaryClient( 6562): errCount = 3: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6562): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=1766505430382513662&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6562): Headers:
W/ApiaryClient( 6562): accept-encoding: [gzip]
W/ApiaryClient( 6562): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6562): gdata-version: 2
V/NotificationService( 1030): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1030): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1030): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1030): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1030): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1396): onNotificationPosted
D/SmartCoverUpdateMonitor( 1396): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1396): MSG_NOTIFICATION_POSTED
E/Babel   ( 6930): Unexpected exception while authenticating.
D/SmartCoverUpdateMonitor( 1396): handleNotificationPosted(true)
D/QuickCircle( 1396): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1396): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1396): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1396): post do just update job
D/LgeQuickCoverNotificationData( 1396): showAll3
E/Babel   ( 6930): cfr: User intervention required. Notification has been pushed.
E/Babel   ( 6930): 	at cfn.b(Unknown Source)
E/Babel   ( 6930): 	at cfn.a(Unknown Source)
E/Babel   ( 6930): 	at f.a(PG:188)
E/Babel   ( 6930): 	at ava.b(PG:143)
E/Babel   ( 6930): 	at bnr.run(PG:5415)
E/Babel   ( 6930): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/Babel   ( 6930): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/Babel   ( 6930): 	at java.lang.Thread.run(Thread.java:818)
D/LgeQuickCoverNotificationData( 1396): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1396): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
D/LgeQuickCoverNotificationData( 1396): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
E/LgeQuickCoverOverlayWindow( 1396): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1396): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1396): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1396): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1396): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1396): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1396): isNotificationForCurrentUser : true
,E/LgeQuickCoverOverlayWindow( 1396): updateNotificationData: count=3
D/QuickStatusbarLayout( 1396): Notification difference=198
D/QuickStatusbarLayout( 1396): child = android.widget.LinearLayout{2154d13 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-49 f=2462 sc=60 link=72 tx=18.4, 0.0, 0.0  rx=16.5 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:1603606527] gl rssi=-49 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-49 f=2462 sc=60 link=72 tx=18.4, 0.0, 0.0  rx=16.5 bcn=0 [on:0 tx:0 rx:0 period:0] from screen [on:0 period:1603606527] gl rssi=-49 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
,I/ThermalEngine(  328): Thermal-Server: Thermal received msg from  override
I/Thermal-Lib( 3103): Thermal-Lib-Client: Client request sent
E/BooksSync( 6562): Soft error: 
E/BooksSync( 6562): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 6562): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=1766505430382513662&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 6562): Headers:
E/BooksSync( 6562): accept-encoding: [gzip]
E/BooksSync( 6562): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 6562): gdata-version: 2
E/BooksSync( 6562): 
E/BooksSync( 6562): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 6562): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 6562): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 6562): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 6562): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 6562): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 6562): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 6562): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 6562): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 6562): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 6562): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 6562): {
E/BooksSync( 6562):  "error": {
E/BooksSync( 6562):   "errors": [
E/BooksSync( 6562):    {
E/BooksSync( 6562):     "domain": "global",
E/BooksSync( 6562):     "reason": "required",
E/BooksSync( 6562):     "message": "Login Required",
E/BooksSync( 6562):     "locationType": "header",
E/BooksSync( 6562):     "location": "Authorization"
E/BooksSync( 6562):    }
E/BooksSync( 6562):   ],
E/BooksSync( 6562):   "code": 401,
E/BooksSync( 6562):   "message": "Login Required"
E/BooksSync( 6562):  }
E/BooksSync( 6562): }
E/BooksSync( 6562): 
E/BooksSync( 6562): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 6562): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 6562): 	... 8 more
E/BooksSync( 6562): Sync error
E/BooksSync( 6562): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 6562): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=1766505430382513662&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 6562): Headers:
E/BooksSync( 6562): accept-encoding: [gzip]
E/BooksSync( 6562): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 6562): gdata-version: 2
E/BooksSync( 6562): 
E/BooksSync( 6562): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 6562): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 6562): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 6562): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 6562): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 6562): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 6562): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 6562): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 6562): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 6562): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 6562): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 6562): {
E/BooksSync( 6562):  "error": {
E/BooksSync( 6562):   "errors": [
E/BooksSync( 6562):    {
E/BooksSync( 6562):     "domain": "global",
E/BooksSync( 6562):     "reason": "required",
E/BooksSync( 6562):     "message": "Login Required",
E/BooksSync( 6562):     "locationType": "header",
E/BooksSync( 6562):     "location": "Authorization"
E/BooksSync( 6562):    }
E/BooksSync( 6562):   ],
E/BooksSync( 6562):   "code": 401,
E/BooksSync( 6562):   "message": "Login Required"
E/BooksSync( 6562):  }
E/BooksSync( 6562): }
E/BooksSync( 6562): 
E/BooksSync( 6562): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 6562): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 6562): 	... 8 more
I/BooksSync( 6562): Finished books sync
I/ActivityManager( 1030): Killing 6277:com.lge.sync/1000 (adj 15): empty #17
D/SyncManager( 1030): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 26829, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
D/sensors_hal_Time( 1030): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1030): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1030): tsOffsetIs: Apps: 308765886708; DSPS: 10258237; Offset : -4304289965
W/libprocessgroup( 1030): failed to open /acct/uid_1000/pid_6277/cgroup.procs: No such file or directory
,I/GAV2    ( 6562): Thread[GAThread,5,main]: No campaign data found.
,I/GAV4    ( 6735): Thread[GAThread,5,main]: No campaign data found.
,I/ActivityManager( 1030): Killing 5839:com.uei.lg.quicksetsdk.maxq616/1000 (adj 15): empty #17
,I/QRemote ( 6386): [RemoteControlManager.java:195:onServiceDisconnected()] oooooo start
W/System.err( 6386): android.os.DeadObjectException
,W/System.err( 6386): 	at android.os.BinderProxy.transactNative(Native Method)
W/System.err( 6386): 	at android.os.BinderProxy.transact(Binder.java:496)
W/System.err( 6386): 	at com.uei.control.IControl.unregisterCallback(IControl.java:502)
W/System.err( 6386): 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:199)
W/System.err( 6386): 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
W/System.err( 6386): 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
W/System.err( 6386): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 6386): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 6386): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 6386): 	at android.app.ActivityThread.main(ActivityThread.java:5274)
W/System.err( 6386): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 6386): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 6386): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
W/System.err( 6386): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
E/UEI.SmartControl( 6386): IControl.unregisterCallback error: android.os.DeadObjectException
W/System.err( 6386): android.os.DeadObjectException
W/System.err( 6386): 	at android.os.BinderProxy.transactNative(Native Method)
W/System.err( 6386): 	at android.os.BinderProxy.transact(Binder.java:496)
W/System.err( 6386): 	at com.uei.control.IControl.unregisterSetupReadyCallback(IControl.java:818)
W/System.err( 6386): 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:200)
W/System.err( 6386): 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
W/System.err( 6386): 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
W/System.err( 6386): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 6386): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 6386): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 6386): 	at android.app.ActivityThread.main(ActivityThread.java:5274)
W/System.err( 6386): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 6386): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 6386): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
W/System.err( 6386): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
E/UEI.SmartControl( 6386): IControl.unregisterSetupReadyCallback error: android.os.DeadObjectException
I/QRemote ( 6386): [RemoteControlManager.java:203:onServiceDisconnected()] oooooo Control unbind before rebinding.
W/libprocessgroup( 1030): failed to open /acct/uid_1000/pid_5839/cgroup.procs: No such file or directory
W/ActivityManager( 1030): Scheduling restart of crashed service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service in 1000ms
,D/QRemote ( 6386): [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]10
I/QRemote ( 6386): [RemoteControlManager.java:157:onBindIRService()] oooooo bind
,E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-53 f=2462 sc=60 link=72 tx=37.2, 0.0, 0.0  rx=31.2 bcn=0 [on:0 tx:0 rx:0 period:3007] from screen [on:0 period:1603609539] gl rssi=-53 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-53 f=2462 sc=60 link=72 tx=37.2, 0.0, 0.0  rx=31.2 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:1603609540] gl rssi=-53 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
,I/ActivityManager( 1030): Start proc com.uei.lg.quicksetsdk.maxq616 for service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service: pid=6990 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,D/QRemote ( 6386): [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
D/UEI.SmartControl( 6990): Quickset Services start...
,I/UEI.SmartControl( 6990): Manufacture = LGE
,D/UEI.SmartControl( 6990): Id = LGNevo
,D/UEI.SmartControl( 6990): File observer start...
E/UEI.SmartControl( 6990): IR Port is disabled: false
D/UEI.SmartControl( 6990): Starting file observer...
D/UEI.SmartControl( 6990): Extracting JNI libs...
D/UEI.SmartControl( 6990): --- this system supports 32-bit or 64-bit only
D/UEI.SmartControl( 6990): --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
D/UEI.SmartControl( 6990): --- Checking lib: libqs_armeabi-v7a.zip
D/UEI.SmartControl( 6990): --- Extracting JNI libs: libqs_armeabi-v7a.zip
,I/UEI.SmartControl( 6990): --- Selecting new region: 6
,I/UEI.SmartControl( 6990): Model = LG-D855
D/UEI.SmartControl( 6990): QS Service created
I/UEI.SmartControl( 6990): Service initServices...
D/UEI.SmartControl( 6990): QS start get config
,D/UEI.SmartControl( 6990): Loading JNI Libs...
,I/UEI.SmartControl( 6990): Supports setup maps: true
,D/UEI.SmartControl( 6990): QS start statue = true Error code = 0
I/UEI.SmartControl( 6990): QS version = v2.7.10.1_RC1
I/UEI.SmartControl( 6990): QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
I/UEI.SmartControl( 6990): ### init IR Blaster...
D/serial_port( 6990): Configuring serial port
E/UEI.SmartControl( 6990): UEIBLaster setting for 616
I/UEI.SmartControl( 6990): Setting serial record hearder size = 2
I/UEI.SmartControl( 6990): configuring settings for MAXQ616
I/UEI.SmartControl( 6990): Get version...
,D/UEI.SmartControl( 6990): serial port data available: 21
,D/UEI.SmartControl( 6990): MAXQ616 A2-X4 software.
,I/UEI.SmartControl( 6990): IR Blaster version: 256702256704300002
I/UEI.SmartControl( 6990): QS saving settings...
D/UEI.SmartControl( 6990): IR Blaster version: 25672567
,D/UEI.SmartControl( 6990): serial port data available: 4
,I/UEI.SmartControl( 6990): Device manager: loading config....
,D/UEI.SmartControl( 6990): ----------- loading internal config...
,W/ContextImpl( 6990): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
E/UEI.SmartControl( 6990): Services init done
D/UEI.SmartControl( 6990): QS Service init finished
D/UEI.SmartControl( 6990): QS Service version name: 2.1.91
D/UEI.SmartControl( 6990): QS Service version code: 201091
,D/UEI.SmartControl( 6990): Service requested: Control
D/UEI.SmartControl( 6990): Request IControl service: devices are loaded...
I/ActivityManager( 1030): Killing 6210:com.android.settings/1000 (adj 15): empty #17
,I/QRemote ( 6386): [RemoteControlManager.java:183:onServiceConnected()] oooooo start
I/UEI.SmartControl( 6990): ------ IControl API: 11
I/UEI.SmartControl( 6990): Registering callback...
I/UEI.SmartControl( 6990): ------ IControl API: 19
I/UEI.SmartControl( 6990): Registering Services Ready callback...
E/UEI.SmartControl( 6990): Loading SETTINGS...
,D/UEI.SmartControl( 6990): -- Open brand translation xml: brands_translations_ko
,D/WifiService( 1030): Client connection lost with reason: 4
,I/UEI.SmartControl( 6990): Notify AllClients services are ready: 0
I/QRemote ( 6386): [RemoteControlManager.java:660:QSSetupIsReady()] oooooo 140517:sdkIsReady callback... get functions. Result:0
D/QRemote ( 6386): [RemoteControlManager.java:388:handleMessage()] oooooo 140510:START_SESSION
D/QRemote ( 6386): [RemoteControlManager.java:394:handleMessage()] oooooo 140510:send retrieve msg
D/QRemote ( 6386): [RemoteControlManager.java:322:handleMessage()] oooooo 140510:handler call retrieveDevices
D/QRemote ( 6386): [RemoteControlManager.java:336:retrieveDevices()] oooooo retrieveDevices: start
I/UEI.SmartControl( 6990): ------ IControl API: 8
D/UEI.SmartControl( 6990): -----service ready thread exits
D/QRemote ( 6386): [RemoteControlManager.java:340:retrieveDevices()] oooooo retrieveDevices: 0
D/QRemote ( 6386): [RemoteControlManager.java:345:retrieveDevices()] oooooo retrieveDevices complete:true
D/QRemote ( 6386): [RemoteControlManager.java:353:retrieveDevices()] oooooo retrieveDevices: notifyDataSetChanged()
D/QRemote ( 6386): [QRemoteApplication.java:145:onRemoteControlStateChanged()] oooooo onRemoteControlStateChanged called in QRemoteApp
D/QRemote ( 6386): [QRemoteApplication.java:158:onRemoteControlStateChanged()] oooooo Widget count is [1]. send broadcast
D/QRemote ( 6386): [QRemoteApplication.java:160:onRemoteControlStateChanged()] oooooo Widget[0]:3
W/libprocessgroup( 1030): failed to open /acct/uid_1000/pid_6210/cgroup.procs: No such file or directory
,D/UEI.SmartControl( 6990): Internal service binding...
D/QRemote ( 6386): [QRemoteApplication.java:188:onRemoteControlStateChanged()] oooooo 140526:onRemoteControlStateChanged&sdkIsReady. stop Service
,V/QRemote ( 6386): [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
D/QRemote ( 6386): [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
E/QRemote ( 6386): [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
D/QRemote ( 6386): [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
D/QRemote ( 6386): [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
D/QRemote ( 6386): [RemoteAppWidgetProvider.java:506:onUpdate()] oooooo 140510:RetrieveDevices complete. Start loading
D/QRemote ( 6386): [RemoteAppWidgetProvider.java:508:onUpdate()] oooooo 140510:appWidgetIds[0]:3 loading
D/QRemote ( 6386): [RemoteAppWidgetManager.java:41:startLoading()] oooooo 140518:widgetId[3] loading start at [1449007589215]
D/QRemote ( 6386): [RemoteAppWidgetManager.java:239:doInBackground()] oooooo 140407:doinBack arr:0
,V/QRemote ( 6386): [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.widget_ui_update
E/QRemote ( 6386): [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
D/QRemote ( 6386): [RemoteAppWidgetProvider.java:171:onReceive()] oooooo total:0
D/QRemote ( 6386): [RemoteAppWidgetProvider.java:172:onReceive()] oooooo selected:0
D/QRemote ( 6386): [RemoteAppWidgetProvider.java:173:onReceive()] oooooo arr:[]
D/QRemote ( 6386): [RemoteAppWidgetProvider.java:174:onReceive()] oooooo appWidgetId:3
D/QRemote ( 6386): [RemoteAppWidgetProvider.java:815:updateRemoteViews()] oooooo UpdateRemoteViews3:widgetId:3
D/QRemote ( 6386): [RemoteAppWidgetProvider.java:986:updateRemoteViews()] oooooo updateAppWidget5:widgetId:3]
,I/ActivityManager( 1030): Killing 6541:com.lge.appbox.client/u0a11 (adj 15): empty #17
W/libprocessgroup( 1030): failed to open /acct/uid_10011/pid_6541/cgroup.procs: No such file or directory
,E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-54 f=2462 sc=60 link=72 tx=19.1, 0.0, 0.0  rx=15.6 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:1603612559] gl rssi=-54 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-54 f=2462 sc=60 link=72 tx=19.1, 0.0, 0.0  rx=15.6 bcn=0 [on:0 tx:0 rx:0 period:4] from screen [on:0 period:1603612563] gl rssi=-54 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
,D/UEI.SmartControl( 6990): Internal timer expired: 1
,D/UEI.SmartControl( 6990): unbind internal service
D/serial_port( 6990): close(fd = 25)
,I/UEI.SmartControl( 6990): Serial port is closed.
E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-55 f=2462 sc=60 link=72 tx=9.5, 0.0, 0.0  rx=7.8 bcn=0 [on:0 tx:0 rx:0 period:3005] from screen [on:0 period:1603615597] gl rssi=-55 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-55 f=2462 sc=60 link=72 tx=9.5, 0.0, 0.0  rx=7.8 bcn=0 [on:0 tx:0 rx:0 period:12] from screen [on:0 period:1603615609] gl rssi=-55 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-55 f=2462 sc=60 link=72 tx=4.8, 0.0, 0.0  rx=3.9 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:1603618632] gl rssi=-55 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-55 f=2462 sc=60 link=72 tx=4.8, 0.0, 0.0  rx=3.9 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:1603618635] gl rssi=-55 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
,D/StatusBar.NetworkController( 1446): refreshViews: Data not connected!! Set no data type icon / Roaming
,I/[SystemUI]QPairHandler( 1446): onReceive = android.intent.action.PACKAGE_CHANGED
,D/SplitUIService( 1872): replaced split : contains_com.google.android.talk / true
,I/InputReader( 1030): Reconfiguring input devices.  changes=0x00000010
,E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-56 f=2462 sc=60 link=72 tx=2.4, 0.0, 0.0  rx=2.0 bcn=0 [on:0 tx:0 rx:0 period:3000] from screen [on:0 period:1603621680] gl rssi=-56 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-56 f=2462 sc=60 link=72 tx=2.4, 0.0, 0.0  rx=2.0 bcn=0 [on:0 tx:0 rx:0 period:9] from screen [on:0 period:1603621689] gl rssi=-56 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
I/ActivityManager( 1030): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.manager.PreloadListManagerHelper: pid=7040 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
I/[SystemUI]QSlideListController( 1446): onReceive = android.intent.action.PACKAGE_CHANGED
,I/[SystemUI]AppWidgetPanel(QRemoteWidgetPanel)( 1446): onReceive = android.intent.action.PACKAGE_CHANGED, packageName : com.google.android.talk
D/SplitUIManager( 1872): split_name #11 / not available #0
I/SplitUIService( 1872): split app #11
I/[LGHome]EVENT( 2070): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.talk flg=0x4000010 (has extras) }
,D/administrator( 1030): Handling package changes for user 0
W/ResourcesManager( 2070): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/[LGHome]Launcher( 2070): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/AppUp4:AppBoxCP( 7040): onCreate
,W/AppUp4:DB( 7040):  [AppBoxDatabaseHelper] construct
I/AppUp4:DB( 7040):  setFingerPrint start
I/AppUp4:DB( 7040):  newfinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys SDK version = 21
,I/NotificationService( 1030): action=android.intent.action.PACKAGE_CHANGED queryReplace=false
D/BackupManagerService( 1030): Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.talk flg=0x4000010 (has extras) }
W/ResourcesManager( 1030): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
I/AppUp4:DB( 7040):  beforefinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys
I/AppUp4:DB( 7040):  SDK version = 21
I/AppUp4:DB( 7040):  beforefinger == newfinger no write in DB
D/AppUp4:AppBoxApplication( 7040): AppBoxApplication onCreate()
I/AppUp4:CustModeStarterReceiver( 7040): onReceive
,D/LgDataFeature( 7040): LgDataFeature() Constructor: none
D/LgDataFeature( 7040): LgDataFeature() Constructor Done, null
,D/AppUp4:CustFacade( 7040): Context : android.app.ReceiverRestrictedContext@1d2083bc
D/AppUp4:CustFacade( 7040): isCustomizationCompleted : false
,D/AppUp4:CustFacade( 7040): isPhone : true
D/AppUp4:CustModeStarterReceiver( 7040): begin check event
I/AppUp4:CustModeStarterReceiver( 7040): Event For Nothing, skip.
W/ResourcesManager( 1030): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourceType( 1030): Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
,I/ActivityManager( 1030): Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=7077 uid=10019 gids={50019, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
I/ActivityManager( 1030): Killing 6252:com.lge.formmanager/u0a26 (adj 15): empty #17
W/libprocessgroup( 1030): failed to open /acct/uid_10026/pid_6252/cgroup.procs: No such file or directory
,I/[LGHome]EVENT( 2070): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
W/ResourcesManager( 7077): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7077): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,W/ResourcesManager( 7077): Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
W/ResourcesManager( 7077): Asset path '/system/framework/lghiddenlibs.jar' does not exist or contains no resources.
W/ResourcesManager( 7077): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
I/SystemConfig( 7077): BUILD Country: EU
,I/SystemConfig( 7077): BUILD Operator: OPEN
I/ActivityManager( 1030): Killing 6689:com.lge.drmservice/u0a62 (adj 15): empty #17
,W/libprocessgroup( 1030): failed to open /acct/uid_10062/pid_6689/cgroup.procs: No such file or directory
,I/SystemConfig( 7077): pm.hasSystemFeature(com.lge.ims.rcs) = false
I/SystemConfig( 7077): existFile = false
I/SystemConfig( 7077): canReadFile = false
I/SystemConfig( 7077): systemFeature RCS result false
D/SystemConfig( 7077): refreshRcsSupport() :false
I/UpdateIcingCorporaServi( 4198): Updating corpora: APPS=com.google.android.talk, CONTACTS=MAYBE
,I/ActivityManager( 1030): Start proc com.lge.lockscreensettings for broadcast com.lge.lockscreensettings/.PackageIntentReceiver: pid=7101 uid=10080 gids={50080, 9997, 1028, 1015} abi=armeabi-v7a
,V/SIM_STK ( 1030): Menu title from STK is T-Mobile
,W/ResourcesManager( 4198): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/UpdateIcingCorporaServi( 4198): UpdateCorporaTask done [took 109 ms] updated apps [took 109 ms] 
I/LockScreenSettings( 7101): Wallpaper base directory = /data/data/com.lge.lockscreensettings/files/
,D/LockScreenSettings( 7101): Quick window widget present in DB = com.lge.clock.quickcover.QuickCoverSettingActivity  true
,D/LockScreenSettings( 7101): Quick window widget present in DB = com.lge.camera.app.QuickWindowCameraActivity  true
D/LockScreenSettings( 7101): Quick window widget present in DB = com.android.contacts.activities.QuickCircleActivity  true
D/LockScreenSettings( 7101): Quick window widget present in DB = com.android.mms.quickcover.QuickCoverActivity  true
D/LockScreenSettings( 7101): Quick window widget present in DB = com.lge.music.MusicQuickCircle  true
D/LockScreenSettings( 7101): Quick window widget present in DB = com.lge.lifetracker.QuickCover  true
I/ActivityManager( 1030): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=7119 uid=10044 gids={50044, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager( 1030): Killing 6735:com.google.android.apps.magazines/u0a93 (adj 15): empty #17
,W/libprocessgroup( 1030): failed to open /acct/uid_10093/pid_6735/cgroup.procs: No such file or directory
,D/Finsky  ( 7119): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,D/LgDataFeature( 7119): LgDataFeature() Constructor: none
D/LgDataFeature( 7119): LgDataFeature() Constructor Done, null
,I/art     ( 1030): Explicit concurrent mark sweep GC freed 33732(1742KB) AllocSpace objects, 7(624KB) LOS objects, 33% free, 44MB/66MB, paused 2.090ms total 135.381ms
,D/Finsky  ( 7119): [1] DailyHygiene.goMakeHygieneIfDirty: Dirty, need more hygiene.
,I/ActivityManager( 1030): Start proc com.google.android.gms:car for service com.google.android.gms/.car.CarService: pid=7158 uid=10005 gids={50005, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
,W/Settings( 7119): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 7119): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,V/DownloadManager( 3291): starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 3291): created cursor android.database.sqlite.SQLiteCursor@ab4d523 on behalf of 7119
W/ResourcesManager( 7158): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 7158): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,D/Finsky  ( 7119): [1] 2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 7119): [1] 2.run: Finished loading 1 libraries.
,D/Finsky  ( 7119): [1] GmsCoreHelper.cleanupNlp: result=false type=4
D/PackageBroadcastService( 2327): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.talk
,I/MultiDex( 7158): VM with version 2.1.0 has multidex support
I/MultiDex( 7158): install
I/MultiDex( 7158): VM has multidex support, MultiDex support library is disabled.
D/Finsky  ( 7119): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
I/ActivityManager( 1030): Start proc com.google.android.gms.wearable for service com.google.android.gms/.wearable.service.WearableControlService: pid=7192 uid=10005 gids={50005, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
,I/ActivityManager( 1030): Killing 6625:com.android.chrome/u0a57 (adj 15): empty #17
I/PeopleContactsSync( 2327): CP2 sync disabled
I/art     ( 2125): Explicit concurrent mark sweep GC freed 44583(2MB) AllocSpace objects, 22(2MB) LOS objects, 50% free, 30MB/62MB, paused 858us total 53.878ms
,W/libprocessgroup( 1030): failed to open /acct/uid_10057/pid_6625/cgroup.procs: No such file or directory
,V/JNIHelp ( 7158): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,W/ResourcesManager( 7192): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 7192): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,W/ActivityThread( 7158): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 7158): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@f4144e4: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 7158): Installed default security provider GmsCore_OpenSSL
I/MultiDex( 7192): VM with version 2.1.0 has multidex support
I/MultiDex( 7192): install
I/MultiDex( 7192): VM has multidex support, MultiDex support library is disabled.
,D/GCM     ( 2125): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
D/AuthorizationBluetoothService( 2125): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,V/GmsCoreStatsServiceLauncher( 2327): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
V/JNIHelp ( 7192): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
D/LocationInitializer( 2327): Restart initialization of location
,W/ActivityThread( 7192): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 7192): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@f4144e4: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 7192): Installed default security provider GmsCore_OpenSSL
,W/NativeLibraryUtils( 7192): Install did not work
W/NativeLibraryUtils( 7192): java.io.IOException: fcntl failed: EAGAIN (Try again)
W/NativeLibraryUtils( 7192): 	at java.nio.FileChannelImpl.basicLock(FileChannelImpl.java:123)
W/NativeLibraryUtils( 7192): 	at java.nio.FileChannelImpl.tryLock(FileChannelImpl.java:181)
W/NativeLibraryUtils( 7192): 	at java.nio.channels.FileChannel.tryLock(FileChannel.java:584)
W/NativeLibraryUtils( 7192): 	at com.google.android.gms.common.util.ax.a(SourceFile:314)
W/NativeLibraryUtils( 7192): 	at com.google.android.gms.common.app.a.run(SourceFile:136)
W/NativeLibraryUtils( 7192): Caused by: android.system.ErrnoException: fcntl failed: EAGAIN (Try again)
W/NativeLibraryUtils( 7192): 	at libcore.io.Posix.fcntlFlock(Native Method)
W/NativeLibraryUtils( 7192): 	at libcore.io.ForwardingOs.fcntlFlock(ForwardingOs.java:70)
W/NativeLibraryUtils( 7192): 	at java.nio.FileChannelImpl.basicLock(FileChannelImpl.java:121)
W/NativeLibraryUtils( 7192): 	... 4 more
D/WearableService( 7192): callingUid 10005, callindPid: 7192
,E/MDM     ( 1819): [86] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
I/ActivityManager( 1030): Killing 6606:com.lge.email/u0a23 (adj 15): empty #17
,W/libprocessgroup( 1030): failed to open /acct/uid_10023/pid_6606/cgroup.procs: No such file or directory
,D/GCM     ( 2125): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,D/AuthorizationBluetoothService( 2125): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,V/GmsCoreStatsServiceLauncher( 2327): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,E/MDM     ( 1819): [87] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,D/LocationInitializer( 2327): Restart initialization of location
,V/Finsky  ( 7119): [1] GearheadStateMonitor.onReady: sIsProjecting:false
V/AlarmManager( 1030): RTC_WAKEUP set : Alarm{1aededcd type 0 when 1449007602959 com.android.vending} when 1449007602959
,D/Finsky  ( 7119): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
V/QRemote ( 6386): [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.wait_loading
D/QRemote ( 6386): [RemoteAppWidgetProvider.java:211:onReceive()] oooooo 140514:alarm msg received!:3479
V/GLSActivity( 2125): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2125): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 2125): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2125): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2125): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2125): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/Finsky  ( 7119): [1] 1.onErrorResponse: Unable to preload experiments: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,V/GLSActivity( 2125): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/GLSUser ( 2125): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 2125): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2125): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2125): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2125): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/GLSActivity( 2125): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2125): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 2125): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2125): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2125): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2125): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/Finsky  ( 7119): [1] LibraryUpdateListener.onErrorResponse: Library replication failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,V/SIM_STK ( 1030): Menu title from STK is T-Mobile
,E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2462 sc=60 link=72 tx=1.2, 0.0, 0.0  rx=1.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:1603624711] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2462 sc=60 link=72 tx=1.2, 0.0, 0.0  rx=1.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:1603624714] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
,V/GLSActivity( 2125): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2125): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 2125): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 2125): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2125): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2125): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/Finsky  ( 7119): [1] 2.onErrorResponse: Update check failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,D/Finsky  ( 7119): [1] DailyHygiene.logDeviceFeaturesAndContinue: Logging device features
,D/Finsky  ( 7119): [1] DailyHygiene.flushEventLogsAndContinue: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 7119): [1] DailyHygiene.reschedule: Giving up. (failures=6)
D/DeviceConnectionService( 1819): client connected with version: 7571000
,D/sensors_hal_Time( 1030): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1030): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1030): tsOffsetIs: Apps: 328768183784; DSPS: 10913672; Offset : -4304282958
,E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2462 sc=60 link=72 tx=1.6, 0.0, 0.0  rx=1.0 bcn=0 [on:0 tx:0 rx:0 period:3000] from screen [on:0 period:1603627730] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2462 sc=60 link=72 tx=1.6, 0.0, 0.0  rx=1.0 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:1603627731] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
,I/ActivityManager( 1030): Killing 5128:com.wsandroid.suite.lge/1000 (adj 15): empty #17
,W/libprocessgroup( 1030): failed to open /acct/uid_1000/pid_5128/cgroup.procs: No such file or directory
,E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2462 sc=60 link=72 tx=1.8, 0.0, 0.0  rx=1.5 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:1603630750] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2462 sc=60 link=72 tx=1.8, 0.0, 0.0  rx=1.5 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:1603630753] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
,V/AlarmManager( 1030): ELAPSED_WAKEUP set : Alarm{1e665160 type 2 when 334304 android} when 334304
,E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2462 sc=60 link=72 tx=0.9, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:1603633782] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2462 sc=60 link=72 tx=0.9, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:1603633785] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2462 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:1603636815] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2462 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:13] from screen [on:0 period:1603636828] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1030):  ConnectedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 1 0
E/WifiStateMachine( 1030):  L2ConnectedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 1 0
E/WifiStateMachine( 1030):  ConnectModeState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 1 0
E/WifiStateMachine( 1030):  DriverStartedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 1 0
E/WifiStateMachine( 1030):  SupplicantStartedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 1 0
E/WifiStateMachine( 1030):  DefaultState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 1 0
,E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2462 sc=60 link=72 tx=0.2, 0.0, 0.0  rx=0.2 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:1603639846] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2462 sc=60 link=72 tx=0.2, 0.0, 0.0  rx=0.2 bcn=0 [on:0 tx:0 rx:0 period:13] from screen [on:0 period:1603639859] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
I/[SystemUI]TimeTickManager( 1446): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1446): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1446): called onTimeUpdated()
I/[SystemUI]Clock( 1446): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1446): called onTimeUpdated()
I/[SystemUI]DateView( 1446): called onTimeUpdated()
I/[SystemUI]DateView( 1446): called onTimeUpdated()
,D/KeyguardUpdateMonitor( 1446): handleTimeUpdate
E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2462 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:1603642881] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2462 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:15] from screen [on:0 period:1603642896] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2462 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3005] from screen [on:0 period:1603645915] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2462 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:1603645925] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
D/sensors_hal_Time( 1030): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1030): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1030): tsOffsetIs: Apps: 348770440443; DSPS: 11569106; Offset : -4304284600
,I/ActivityManager( 1030): Killing 6870:com.qualcomm.timeservice/1000 (adj 15): empty #17
,W/libprocessgroup( 1030): failed to open /acct/uid_1000/pid_6870/cgroup.procs: No such file or directory
,E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2462 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:1603648939] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2462 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:4] from screen [on:0 period:1603648943] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
D/PowerManagerServiceEx( 1030): acquireWakeLockInternal: lock=174419834, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1030
,V/AlarmManager( 1030): RTC_WAKEUP set : Alarm{178736de type 0 when 1449007618270 com.android.vending} when 1449007618270
,D/[Concierge]Service( 2596): onStartCommand(). Type : 9
,D/PowerManagerServiceEx( 1030): releaseWakeLockInternal: lock=174419834 [*alarm*], flags=0x0
,V/SIM_STK ( 1030): Menu title from STK is T-Mobile
,V/GLSActivity( 2125): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2125): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 2125): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2125): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2125): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2125): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/Finsky  ( 7119): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 7119): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 7119): [1] 5.onFinished: Scheduling replication attempt 1.
,E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2462 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:1603651960] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2462 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:1603651963] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2462 sc=60 link=72 tx=1.0, 0.0, 0.0  rx=0.5 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:1603654992] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2462 sc=60 link=72 tx=1.0, 0.0, 0.0  rx=0.5 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:1603654995] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-56 f=2462 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.3 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:1603658020] gl rssi=-56 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-56 f=2462 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.3 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:1603658023] gl rssi=-56 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-56 f=2462 sc=60 link=72 tx=0.3, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:1603661053] gl rssi=-56 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-56 f=2462 sc=60 link=72 tx=0.3, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:12] from screen [on:0 period:1603661065] gl rssi=-56 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
V/AlarmManager( 1030): ELAPSED_WAKEUP set : Alarm{11e0d290 type 2 when 364338 android} when 364338
,I/BooksSync( 6562): Starting books sync
,D/BooksSync( 6562): started syncMyEbooks
,V/GLSActivity( 2125): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2125): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.syncadapters.contacts, service: cp
I/GLSUser ( 2125): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> cp without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2125): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2125): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2125): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/art     ( 1030): Explicit concurrent mark sweep GC freed 35503(1548KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 44MB/66MB, paused 4.024ms total 148.463ms
,V/NotificationService( 1030): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1030): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1030): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1030): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1030): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
W/GLSActivity( 2125): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2125): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2125): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2125): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2125): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2125): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2125): 	at android.os.Binder.execTransact(Binder.java:446)
D/ContactsSyncAdapter( 2125): innerSync failed
D/ContactsSyncAdapter( 2125): com.google.wireless.gdata2.client.AuthenticationException: unable to get auth token android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
D/ContactsSyncAdapter( 2125): 	at com.google.android.syncadapters.contacts.AuthInfo.getAuthToken(AuthInfo.java:45)
D/ContactsSyncAdapter( 2125): 	at com.google.android.syncadapters.contacts.ContactsSyncAdapter.innerPerformSync(ContactsSyncAdapter.java:263)
D/ContactsSyncAdapter( 2125): 	at com.google.android.syncadapters.contacts.ContactsSyncAdapter.onPerformLoggedSync(ContactsSyncAdapter.java:168)
D/ContactsSyncAdapter( 2125): 	at com.google.android.common.LoggingThreadedSyncAdapter.onPerformSync(LoggingThreadedSyncAdapter.java:33)
D/ContactsSyncAdapter( 2125): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
D/ContactsSyncAdapter( 2125): Caused by: android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
D/ContactsSyncAdapter( 2125): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
D/ContactsSyncAdapter( 2125): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
D/ContactsSyncAdapter( 2125): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
D/ContactsSyncAdapter( 2125): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
D/ContactsSyncAdapter( 2125): 	at android.os.Binder.execTransact(Binder.java:446)
D/LgeQuickCoverNLService( 1396): onNotificationPosted
D/SmartCoverUpdateMonitor( 1396): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1396): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1396): handleNotificationPosted(true)
D/QuickCircle( 1396): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1396): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1396): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1396): post do just update job
D/LgeQuickCoverNotificationData( 1396): showAll3
D/LgeQuickCoverNotificationData( 1396): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1396): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
D/LgeQuickCoverNotificationData( 1396): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
E/LgeQuickCoverOverlayWindow( 1396): showNotificationWithSetupData: display=false
,D/LgeQuickCoverOverlayWindow( 1396): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1396): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1396): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1396): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1396): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1396): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1396): updateNotificationData: count=3
,D/QuickStatusbarLayout( 1396): Notification difference=198
D/QuickStatusbarLayout( 1396): child = android.widget.LinearLayout{2154d13 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
D/SyncManager( 1030): failed sync operation thalitester@gmail.com u0 (com.google), com.android.contacts, LOCAL, currentRunTime 335672, reason: 10019, SyncResult: stats [ numAuthExceptions: 1]
,D/SyncManager( 1030): not retrying sync operation because the error is a hard error: thalitester@gmail.com u0 (com.google), com.android.contacts, LOCAL, currentRunTime 425812, reason: 10019
,I/GLSUser ( 2125): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2125): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2125): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2125): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2125): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/NotificationService( 1030): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1030): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1030): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1030): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1030): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1396): onNotificationPosted
D/SmartCoverUpdateMonitor( 1396): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1396): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1396): handleNotificationPosted(true)
D/QuickCircle( 1396): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1396): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1396): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1396): post do just update job
D/LgeQuickCoverNotificationData( 1396): showAll3
D/LgeQuickCoverNotificationData( 1396): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1396): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
D/LgeQuickCoverNotificationData( 1396): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
E/LgeQuickCoverOverlayWindow( 1396): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1396): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1396): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1396): [native noti] inex =  1
,D/LgeQuickCoverNotificationData( 1396): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1396): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1396): isNotificationForCurrentUser : true
W/GLSActivity( 2125): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2125): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2125): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2125): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2125): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2125): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2125): 	at android.os.Binder.execTransact(Binder.java:446)
E/LgeQuickCoverOverlayWindow( 1396): updateNotificationData: count=3
E/BooksAccountManager( 6562): Authentication error
E/BooksAccountManager( 6562): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6562): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6562): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6562): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6562): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6562): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6562): null auth token
D/QuickStatusbarLayout( 1396): Notification difference=198
D/QuickStatusbarLayout( 1396): child = android.widget.LinearLayout{2154d13 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
W/ApiaryClient( 6562): Error response from books API: {
W/ApiaryClient( 6562):  "error": {
W/ApiaryClient( 6562):   "errors": [
W/ApiaryClient( 6562):    {
W/ApiaryClient( 6562):     "domain": "global",
W/ApiaryClient( 6562):     "reason": "required",
W/ApiaryClient( 6562):     "message": "Login Required",
W/ApiaryClient( 6562):     "locationType": "header",
W/ApiaryClient( 6562):     "location": "Authorization"
W/ApiaryClient( 6562):    }
W/ApiaryClient( 6562):   ],
W/ApiaryClient( 6562):   "code": 401,
W/ApiaryClient( 6562):   "message": "Login Required"
W/ApiaryClient( 6562):  }
W/ApiaryClient( 6562): }
W/ApiaryClient( 6562): errCount = 1: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6562): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-7991167556589724623&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6562): Headers:
W/ApiaryClient( 6562): accept-encoding: [gzip]
W/ApiaryClient( 6562): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6562): gdata-version: 2
,E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-56 f=2462 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3005] from screen [on:0 period:1603664088] gl rssi=-56 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-56 f=2462 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:4] from screen [on:0 period:1603664092] gl rssi=-56 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
V/GLSActivity( 2125): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2125): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2125): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2125): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 2125): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2125): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1030): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1030): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1030): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1030): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1030): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1396): onNotificationPosted
,D/SmartCoverUpdateMonitor( 1396): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1396): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1396): handleNotificationPosted(true)
D/QuickCircle( 1396): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1396): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1396): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1396): post do just update job
D/LgeQuickCoverNotificationData( 1396): showAll3
D/LgeQuickCoverNotificationData( 1396): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1396): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
D/LgeQuickCoverNotificationData( 1396): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
E/LgeQuickCoverOverlayWindow( 1396): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1396): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1396): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1396): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1396): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1396): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1396): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1396): updateNotificationData: count=3
W/GLSActivity( 2125): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2125): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2125): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2125): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2125): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2125): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2125): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 6562): Authentication error
E/BooksAccountManager( 6562): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6562): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6562): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6562): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6562): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6562): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6562): null auth token
D/QuickStatusbarLayout( 1396): Notification difference=198
D/QuickStatusbarLayout( 1396): child = android.widget.LinearLayout{2154d13 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
W/ApiaryClient( 6562): Error response from books API: {
W/ApiaryClient( 6562):  "error": {
W/ApiaryClient( 6562):   "errors": [
W/ApiaryClient( 6562):    {
W/ApiaryClient( 6562):     "domain": "global",
W/ApiaryClient( 6562):     "reason": "required",
W/ApiaryClient( 6562):     "message": "Login Required",
W/ApiaryClient( 6562):     "locationType": "header",
W/ApiaryClient( 6562):     "location": "Authorization"
W/ApiaryClient( 6562):    }
W/ApiaryClient( 6562):   ],
W/ApiaryClient( 6562):   "code": 401,
W/ApiaryClient( 6562):   "message": "Login Required"
W/ApiaryClient( 6562):  }
W/ApiaryClient( 6562): }
,W/ApiaryClient( 6562): errCount = 2: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6562): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-7991167556589724623&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6562): Headers:
W/ApiaryClient( 6562): accept-encoding: [gzip]
W/ApiaryClient( 6562): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6562): gdata-version: 2
V/GLSActivity( 2125): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2125): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2125): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2125): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2125): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2125): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     ( 2125): Explicit concurrent mark sweep GC freed 27565(1558KB) AllocSpace objects, 8(1152KB) LOS objects, 50% free, 30MB/62MB, paused 2.328ms total 63.752ms
,V/NotificationService( 1030): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1030): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1030): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1030): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1030): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1396): onNotificationPosted
,D/SmartCoverUpdateMonitor( 1396): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1396): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1396): handleNotificationPosted(true)
D/QuickCircle( 1396): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1396): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1396): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1396): post do just update job
D/LgeQuickCoverNotificationData( 1396): showAll3
D/LgeQuickCoverNotificationData( 1396): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1396): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
D/LgeQuickCoverNotificationData( 1396): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
E/LgeQuickCoverOverlayWindow( 1396): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1396): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1396): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1396): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1396): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1396): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1396): isNotificationForCurrentUser : true
,E/LgeQuickCoverOverlayWindow( 1396): updateNotificationData: count=3
W/GLSActivity( 2125): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2125): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2125): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2125): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2125): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2125): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2125): 	at android.os.Binder.execTransact(Binder.java:446)
E/BooksAccountManager( 6562): Authentication error
E/BooksAccountManager( 6562): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6562): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6562): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6562): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6562): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6562): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6562): null auth token
D/QuickStatusbarLayout( 1396): Notification difference=198
D/QuickStatusbarLayout( 1396): child = android.widget.LinearLayout{2154d13 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,W/ApiaryClient( 6562): Error response from books API: {
W/ApiaryClient( 6562):  "error": {
W/ApiaryClient( 6562):   "errors": [
W/ApiaryClient( 6562):    {
W/ApiaryClient( 6562):     "domain": "global",
W/ApiaryClient( 6562):     "reason": "required",
W/ApiaryClient( 6562):     "message": "Login Required",
W/ApiaryClient( 6562):     "locationType": "header",
W/ApiaryClient( 6562):     "location": "Authorization"
W/ApiaryClient( 6562):    }
W/ApiaryClient( 6562):   ],
W/ApiaryClient( 6562):   "code": 401,
W/ApiaryClient( 6562):   "message": "Login Required"
W/ApiaryClient( 6562):  }
W/ApiaryClient( 6562): }
,W/ApiaryClient( 6562): errCount = 3: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6562): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-7991167556589724623&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6562): Headers:
W/ApiaryClient( 6562): accept-encoding: [gzip]
W/ApiaryClient( 6562): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6562): gdata-version: 2
E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-56 f=2462 sc=60 link=72 tx=1.1, 0.0, 0.0  rx=1.5 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:1603667105] gl rssi=-56 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-56 f=2462 sc=60 link=72 tx=1.1, 0.0, 0.0  rx=1.5 bcn=0 [on:0 tx:0 rx:0 period:14] from screen [on:0 period:1603667119] gl rssi=-56 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
E/BooksSync( 6562): Soft error: 
E/BooksSync( 6562): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 6562): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-7991167556589724623&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 6562): Headers:
E/BooksSync( 6562): accept-encoding: [gzip]
E/BooksSync( 6562): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 6562): gdata-version: 2
E/BooksSync( 6562): 
E/BooksSync( 6562): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 6562): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 6562): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 6562): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 6562): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 6562): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 6562): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 6562): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 6562): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 6562): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 6562): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 6562): {
E/BooksSync( 6562):  "error": {
E/BooksSync( 6562):   "errors": [
E/BooksSync( 6562):    {
E/BooksSync( 6562):     "domain": "global",
E/BooksSync( 6562):     "reason": "required",
E/BooksSync( 6562):     "message": "Login Required",
E/BooksSync( 6562):     "locationType": "header",
E/BooksSync( 6562):     "location": "Authorization"
E/BooksSync( 6562):    }
E/BooksSync( 6562):   ],
E/BooksSync( 6562):   "code": 401,
E/BooksSync( 6562):   "message": "Login Required"
E/BooksSync( 6562):  }
E/BooksSync( 6562): }
E/BooksSync( 6562): 
E/BooksSync( 6562): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 6562): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 6562): 	... 8 more
,E/BooksSync( 6562): Sync error
E/BooksSync( 6562): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 6562): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-7991167556589724623&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 6562): Headers:
E/BooksSync( 6562): accept-encoding: [gzip]
E/BooksSync( 6562): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 6562): gdata-version: 2
E/BooksSync( 6562): 
E/BooksSync( 6562): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 6562): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 6562): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 6562): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 6562): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 6562): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 6562): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 6562): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 6562): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 6562): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 6562): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 6562): {
E/BooksSync( 6562):  "error": {
E/BooksSync( 6562):   "errors": [
E/BooksSync( 6562):    {
E/BooksSync( 6562):     "domain": "global",
E/BooksSync( 6562):     "reason": "required",
E/BooksSync( 6562):     "message": "Login Required",
E/BooksSync( 6562):     "locationType": "header",
E/BooksSync( 6562):     "location": "Authorization"
E/BooksSync( 6562):    }
E/BooksSync( 6562):   ],
E/BooksSync( 6562):   "code": 401,
E/BooksSync( 6562):   "message": "Login Required"
E/BooksSync( 6562):  }
E/BooksSync( 6562): }
E/BooksSync( 6562): 
E/BooksSync( 6562): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 6562): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 6562): 	... 8 more
I/BooksSync( 6562): Finished books sync
D/SyncManager( 1030): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 341133, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/sensors_hal_Time( 1030): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1030): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1030): tsOffsetIs: Apps: 368772571842; DSPS: 12224536; Offset : -4304289144
,E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-56 f=2462 sc=60 link=72 tx=3.5, 0.0, 0.0  rx=3.8 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:1603670140] gl rssi=-56 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-56 f=2462 sc=60 link=72 tx=3.5, 0.0, 0.0  rx=3.8 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:1603670143] gl rssi=-56 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
,D/StatusBar.NetworkController( 1446): refreshViews: Data not connected!! Set no data type icon / Roaming
,E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-55 f=2462 sc=60 link=72 tx=1.8, 0.0, 0.0  rx=1.9 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:1603673188] gl rssi=-55 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-55 f=2462 sc=60 link=72 tx=1.8, 0.0, 0.0  rx=1.9 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:1603673191] gl rssi=-55 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-55 f=2462 sc=60 link=72 tx=0.9, 0.0, 0.0  rx=0.9 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:1603676215] gl rssi=-55 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-55 f=2462 sc=60 link=72 tx=0.9, 0.0, 0.0  rx=0.9 bcn=0 [on:0 tx:0 rx:0 period:14] from screen [on:0 period:1603676229] gl rssi=-55 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-55 f=2462 sc=60 link=72 tx=1.4, 0.0, 0.0  rx=1.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:1603679251] gl rssi=-55 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-55 f=2462 sc=60 link=72 tx=1.4, 0.0, 0.0  rx=1.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:1603679254] gl rssi=-55 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
,V/AlarmManager( 1030): RTC_WAKEUP set : Alarm{1343d138 type 0 when 1449007648325 com.android.vending} when 1449007648325
,V/SIM_STK ( 1030): Menu title from STK is T-Mobile
,V/GLSActivity( 2125): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2125): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 2125): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2125): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2125): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2125): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/Finsky  ( 7119): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 7119): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 7119): [1] 5.onFinished: Scheduling replication attempt 2.
,E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-55 f=2462 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.5 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:1603682280] gl rssi=-55 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-55 f=2462 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.5 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:1603682283] gl rssi=-55 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-55 f=2462 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.2 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:1603685320] gl rssi=-55 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-55 f=2462 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.2 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:1603685323] gl rssi=-55 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
,D/sensors_hal_Time( 1030): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1030): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1030): tsOffsetIs: Apps: 388774427668; DSPS: 12879957; Offset : -4304295099
,E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-55 f=2462 sc=60 link=72 tx=0.2, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:1603688348] gl rssi=-55 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-55 f=2462 sc=60 link=72 tx=0.2, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:1603688351] gl rssi=-55 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-55 f=2462 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:1603691377] gl rssi=-55 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-55 f=2462 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:1603691380] gl rssi=-55 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
,V/AlarmManager( 1030): ELAPSED_WAKEUP set : Alarm{9f9b15a type 2 when 394415 android} when 394415
,E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-55 f=2462 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:1603694410] gl rssi=-55 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-55 f=2462 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:1603694413] gl rssi=-55 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-55 f=2462 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:1603697440] gl rssi=-55 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-55 f=2462 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:1603697443] gl rssi=-55 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-55 f=2462 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:1603700465] gl rssi=-55 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-55 f=2462 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:11] from screen [on:0 period:1603700476] gl rssi=-55 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
I/[SystemUI]TimeTickManager( 1446): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1446): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1446): called onTimeUpdated()
I/[SystemUI]Clock( 1446): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1446): called onTimeUpdated()
I/[SystemUI]DateView( 1446): called onTimeUpdated()
I/[SystemUI]DateView( 1446): called onTimeUpdated()
,D/KeyguardUpdateMonitor( 1446): handleTimeUpdate
E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-55 f=2462 sc=60 link=72 tx=1.0, 0.0, 0.0  rx=0.5 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:1603703497] gl rssi=-55 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-55 f=2462 sc=60 link=72 tx=1.0, 0.0, 0.0  rx=0.5 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:1603703500] gl rssi=-55 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-55 f=2462 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.3 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:1603706527] gl rssi=-55 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-55 f=2462 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.3 bcn=0 [on:0 tx:0 rx:0 period:4] from screen [on:0 period:1603706531] gl rssi=-55 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
,D/sensors_hal_Time( 1030): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1030): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1030): tsOffsetIs: Apps: 408776279535; DSPS: 13535377; Offset : -4304274365
,E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-55 f=2462 sc=60 link=72 tx=0.3, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:1603709557] gl rssi=-55 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-55 f=2462 sc=60 link=72 tx=0.3, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:1603709560] gl rssi=-55 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
,D/PowerManagerServiceEx( 1030): acquireWakeLockInternal: lock=174419834, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1030
,V/AlarmManager( 1030): RTC_WAKEUP set : Alarm{ee9f868 type 0 when 1449007680026 com.android.vending} when 1449007680026
,D/[Concierge]Service( 2596): onStartCommand(). Type : 9
,D/PowerManagerServiceEx( 1030): releaseWakeLockInternal: lock=174419834 [*alarm*], flags=0x0
,V/SIM_STK ( 1030): Menu title from STK is T-Mobile
,V/GLSActivity( 2125): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2125): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 2125): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2125): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2125): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2125): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/Finsky  ( 7119): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 7119): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 7119): [1] 5.onFinished: Scheduling replication attempt 3.
,E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-55 f=2462 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3005] from screen [on:0 period:1603712591] gl rssi=-55 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-55 f=2462 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:1603712594] gl rssi=-55 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-55 f=2462 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:1603715619] gl rssi=-55 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-55 f=2462 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:11] from screen [on:0 period:1603715630] gl rssi=-55 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-55 f=2462 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:1603718649] gl rssi=-55 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-55 f=2462 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:1603718652] gl rssi=-55 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-55 f=2462 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:1603721677] gl rssi=-55 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-55 f=2462 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:1603721680] gl rssi=-55 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
,I/wpa_supplicant( 6226): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=0
,D/WifiMonitor( 1030): Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=0]
E/WifiMonitor( 1030): WifiMonitor:wlan0 cnt=20 dispatchEvent: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=0
E/WifiMonitor( 1030): handleEvent 2  CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=0
D/WifiMonitor( 1030): handleNetworkStateChange: Could not parse disconnect string
E/WifiMonitor( 1030): WifiMonitor notify network disconnect: null reason=0
D/WifiMonitor( 1030): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1030): WifiMonitor:wlan0 cnt=21 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
E/WifiStateMachine( 1030):  ConnectedState NETWORK_DISCONNECTION_EVENT nid=0 reason=0 lastbssid=c0:ff:d4:d3:aa:48 freq=2462 rssi=-55 rt=425222
E/WifiStateMachine( 1030):  L2ConnectedState NETWORK_DISCONNECTION_EVENT nid=0 reason=0 lastbssid=c0:ff:d4:d3:aa:48 freq=2462 rssi=-55 rt=425223
E/WifiStateMachine( 1030):  ConnectModeState NETWORK_DISCONNECTION_EVENT nid=0 reason=0 lastbssid=c0:ff:d4:d3:aa:48 freq=2462 rssi=-55 rt=425223
E/WifiConfigStore( 1030): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/WifiNative-wlan0( 1030): doBoolean: SET_NETWORK 0 bssid any
,D/Tethering( 1030): InitialState.processMessage what=4
D/Tethering( 1030): sendTetherStateChangedBroadcast 0, 0, 0
,D/WifiNative-wlan0( 1030): SET_NETWORK 0 bssid any: returned true
D/WifiNative-wlan0( 1030): doBoolean: SAVE_CONFIG
D/WifiNative-wlan0( 1030): SAVE_CONFIG: returned true
D/WifiNative-wlan0( 1030): doBoolean: DRIVER BTCOEXMODE 2
I/wpa_supplicant( 6226): wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
,D/LGWifiP2pService( 1030): InactiveState{ when=-2ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1030): P2pEnabledState{ when=-2ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
I/jxcore-log( 6121): DBG, CoordinatorConnector start_tests called
I/jxcore-log( 6121): 
D/WifiNative-wlan0( 1030): DRIVER BTCOEXMODE 2: returned true
D/WifiNative-wlan0( 1030): doBoolean: SET ps 1
D/WifiNative-wlan0( 1030): SET ps 1: returned true
D/CommandListener(  311): Clearing all IP addresses on wlan0
D/DhcpStateMachine( 1030): RunningState{ when=-12ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiMonitor( 1030): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
E/WifiMonitor( 1030): WifiMonitor:wlan0 cnt=22 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
,I/jxcore-log( 6121): DBG, CoordinatorConnector disconnect called
I/jxcore-log( 6121): 
I/jxcore-log( 6121): The Coordinator has disconnected!
I/jxcore-log( 6121): 
,I/wpa_supplicant( 6226): wlan0: CTRL-EVENT-SCAN-STARTED 
,V/NativeCrypto( 2125): Read error: ssl=0xaf45c600: I/O error during system call, Connection timed out
,I/ActivityManager( 1030): Start proc com.android.settings for broadcast com.android.settings/.deviceinfo.UsbSettingsReceiver: pid=7322 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
D/WifiMonitor( 1030): Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1030): WifiMonitor:wlan0 cnt=23 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1030): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
,E/WifiMonitor( 1030): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
V/NativeCrypto( 2125): SSL shutdown failed: ssl=0xaf45c600: I/O error during system call, Broken pipe
,D/ConnectivityService( 1030): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
D/ConnectivityService( 1030): ignoring duplicate network state non-change
D/ConnectivityService( 1030): NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 2
D/WifiHS20( 1030): hidePasspointNotification off =false
W/Settings( 1030): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1030): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1030): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
V/WfdStateTracker( 1950): handleWifiStateChangedEvent: 0
I/StatusBar.NetworkController( 1446): networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1446): mWifiConnected = false, mWifiLevel = 0
D/ConnectivityService( 1030): reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10005
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1030): ValidatedState{ when=0 what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1030): DefaultState{ when=0 what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
,D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1030): Forcing reevaluation
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1030): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1030): Checking http://clients3.google.com/generate_204 on <unknown ssid>
D/StatusBar.NetworkController( 1446): refreshViews: Data not connected!! Set no data type icon / Roaming
D/WifiHS20( 1030): hidePasspointNotification off =false
W/Settings( 1030): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1030): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1030): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
E/WifiStateMachine( 1030): WifiStateMachine: Leaving Connected state
E/WifiStateMachine( 1030):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 21 0 rt=425427  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: DISCONNECTED
E/WifiStateMachine( 1030):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 21 0 rt=425427  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: DISCONNECTED
E/WifiStateMachine( 1030):  DisconnectedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1030):  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1030):  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1030):  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1030):  DefaultState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1030):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 22 0 rt=425430  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
D/WifiHS20( 1030): hidePasspointNotification off =false
W/Settings( 1030): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1030): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1030): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
,W/Settings( 1030): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1030): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1030): NETWORK_STATE_CHANGED_ACTION [SCANNING]
E/WifiStateMachine( 1030):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 22 0 rt=425439  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
E/WifiStateMachine( 1030):  DisconnectedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1030):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
I/StatusBar.NetworkController( 1446): networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1446): mWifiConnected = false, mWifiLevel = 0
E/WifiStateMachine( 1030):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1030):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
D/StatusBar.NetworkController( 1446): refreshViews: Data not connected!! Set no data type icon / Roaming
E/WifiStateMachine( 1030):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1030):  DisconnectedState CMD_UPDATE_LINKPROPERTIES 0 0
I/StatusBar.NetworkController( 1446): networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1446): mWifiConnected = false, mWifiLevel = 0
E/WifiStateMachine( 1030):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
D/StatusBar.NetworkController( 1446): refreshViews: Data not connected!! Set no data type icon / Roaming
E/WifiStateMachine( 1030):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1030):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1030):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
D/WifiNetworkAgent( 1030): NetworkAgent: NetworkAgent channel lost
I/StatusBar.NetworkController( 1446): networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1446): mWifiConnected = false, mWifiLevel = 0
D/WifiServerServiceExt( 1030): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1030): setSupplicantStateDISCONNECTED
D/StatusBar.NetworkController( 1446): refreshViews: Data not connected!! Set no data type icon / Roaming
D/WifiServerServiceExt( 1030): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1030): setSupplicantStateSCANNING
,D/ConnectivityService( 1030): Default network via Wi-Fi disconnect. stop DSQN
D/DSQN    ( 1030): disableDataServiceNotify
D/DSQN    ( 1030): stop dsqn bin
D/libc-netbsd(  311): default dns: query_ipv6=0, query_ipv4=0
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1030): Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
D/DSQN    ( 1030): DNSproblemNotiEnabled is disabled ignore DNS fail CB
,D/ConnectivityService( 1030): notifyType LOST for NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService( 1030):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1030):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1030): sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
D/Nat464Xlat( 1030): requiresClat: netType=1, connected=false, hasIPv4Address=true, hasInternetCapability=true
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1030): EvaluatingState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityManager.CallbackHandler( 1446): CM callback handler got msg 524292
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1030): DefaultState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1030): Disconnected - quitting
D/CSLegacyTypeTracker( 1030): [lge_data] remove agent NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.122/24,fe80::c69a:2ff:fe7b:60ac/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} } list []  wasFirstNetwork :true
D/CSLegacyTypeTracker( 1030): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
D/ConnectivityService( 1030): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService( 1030): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService( 1030): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/LocSvc_java( 1030): Sending msg: 4 arg1:0 arg2:1
V/NetworkPolicy( 1030): [LG_RESTRICTED] !!!isConnected  type  :1
D/ConnectivityService( 1030): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/LocSvc_java( 1030): getAGpsConnectionInfo connType - 4
D/ConnectivityService( 1030): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1030): sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/NetworkManagementService( 1030): Removing idletimer
D/WIFI    ( 1030): new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    ( 1030):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
W/Settings( 1030): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/ConnectivityService( 1030): requestNetworkTransitionWakelock: wakelock - ignore in airplane mode
D/LocSvc_java( 1030): updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java( 1030): ignore wifi update if we are not in OPENING or CLOSING
D/TelephonyNetworkFactory-1( 1855): new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/T,elephonyNetworkFactory-1( 1855):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
V/NetworkPolicy( 1030): [LG_RESTRICTED] !!!isConnected  type  :1
D/LocSvc_java( 1030): Sending msg: 4 arg1:0 arg2:1
D/LocSvc_java( 1030): getAGpsConnectionInfo connType - 4
D/LocSvc_java( 1030): updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java( 1030): ignore wifi update if we are not in OPENING or CLOSING
,D/TelephonyIcons( 1446): null signal icon name: drawable/stat_sys_signal_null
,D/StatusBar.NetworkController( 1446): refreshViews: Data not connected!! Set no data type icon / Roaming
D/StatusBar.NetworkController( 1446): refreshViews: Data not connected!! Set no data type icon / Roaming
W/ResourcesManager( 7322): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7322): Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
W/ResourcesManager( 7322): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 7322): Asset path '/system/framework/com.lge.bluetooth.jar' does not exist or contains no resources.
W/ResourcesManager( 7322): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
W/ResourcesManager( 7322): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,D/TelephonyIcons( 1446): null signal icon name: drawable/stat_sys_signal_null
D/StatusBar.NetworkController( 1446): refreshViews: Data not connected!! Set no data type icon / Roaming
D/StatusBar.NetworkController( 1446): refreshViews: Data not connected!! Set no data type icon / Roaming
D/UsbSettingsReceiver( 7322): [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
D/UsbSettingsReceiver( 7322): [AUTORUN] sys.usb.config = ptp_only,adb
D/UsbSettingsReceiver( 7322): [AUTORUN] sys.usb.state = ptp_only,adb
D/UsbSettingsReceiver( 7322): [AUTORUN] persist.sys.usb.config = ptp_only,adb
D/UsbSettingsReceiver( 7322): [AUTORUN] onReceive() : app userid = 0, current userid = 0
,D/DhcpStateMachine( 1030): StoppedState
D/UsbSettingsControl( 7322): [AUTORUN] getUsbConnected() : connected=true
,D/UsbSettingsReceiver( 7322): [AUTORUN] onReceive() : availableList=[]
,D/UsbSettingsReceiver( 7322): [AUTORUN] onReceive() : activeList=[]
D/UsbSettingsReceiver( 7322): [AUTORUN] onReceive() : errorList=[]
D/UsbSettingsControl( 7322): [AUTORUN] isAutorunTimer() : mAutorunChanging=false
D/UsbSettingsControl( 7322): [AUTORUN] setTetherStatus() : status=false
I/ActivityManager( 1030): Start proc com.wsandroid.suite.lge for broadcast com.wsandroid.suite.lge/com.wavesecure.core.WSAndroidSystemIntentReceiver: pid=7364 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
I/ActivityManager( 1030): Killing 6890:com.android.calendar/u0a13 (adj 15): empty #17
,W/libprocessgroup( 1030): failed to open /acct/uid_10013/pid_6890/cgroup.procs: No such file or directory
,W/ResourcesManager( 7364): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,D/PluginManager( 7364): init()
,E/WifiStateMachine( 1030):  DisconnectedState CMD_RSSI_POLL 1 0 0x 00:00:00:00:00:00 rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:2999] from screen [on:0 period:1603724705] gl rssi=-55 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1030):  ConnectModeState CMD_RSSI_POLL 1 0 0x 00:00:00:00:00:00 rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:1603724706] gl rssi=-55 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1030):  DriverStartedState CMD_RSSI_POLL 1 0 0x 00:00:00:00:00:00 rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:1603724707] gl rssi=-55 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1030):  SupplicantStartedState CMD_RSSI_POLL 1 0 0x 00:00:00:00:00:00 rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:1603724708] gl rssi=-55 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1030):  DefaultState CMD_RSSI_POLL 1 0 0x 00:00:00:00:00:00 rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:0] from screen [on:0 period:1603724708] gl rssi=-55 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
W/ExternalStrings( 7364): load override strings
W/ExternalStrings( 7364): java.lang.RuntimeException: Unexpected tag, got eat-comment
W/ExternalStrings( 7364): 	at com.mcafee.plugin.af.a(Unknown Source)
W/ExternalStrings( 7364): 	at com.mcafee.plugin.ac.b(Unknown Source)
W/ExternalStrings( 7364): 	at com.mcafee.plugin.ak.d(Unknown Source)
W/ExternalStrings( 7364): 	at com.mcafee.plugin.ak.a(Unknown Source)
W/ExternalStrings( 7364): 	at com.mcafee.app.s.getClassLoader(Unknown Source)
W/ExternalStrings( 7364): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5001)
W/ExternalStrings( 7364): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4609)
W/ExternalStrings( 7364): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4549)
W/ExternalStrings( 7364): 	at android.app.ActivityThread.access$1500(ActivityThread.java:148)
W/ExternalStrings( 7364): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1344)
W/ExternalStrings( 7364): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/ExternalStrings( 7364): 	at android.os.Looper.loop(Looper.java:135)
W/ExternalStrings( 7364): 	at android.app.ActivityThread.main(ActivityThread.java:5274)
W/ExternalStrings( 7364): 	at java.lang.reflect.Method.invoke(Native Method)
W/ExternalStrings( 7364): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/ExternalStrings( 7364): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
W/ExternalStrings( 7364): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
,D/StatusProvider( 7364): onCreate
V/Signer  ( 7364): override build config not found
D/Signer  ( 7364): value of property debug is false
,D/LGMDMWrapper( 7364): Found class 'com.mcafee.lgmdm.LGMDMWrapper$DataWipe'.
D/LGMDMWrapper( 7364): Found class 'com.mcafee.lgmdm.LGMDMWrapper$DownloadMode'.
D/LGMDMWrapper( 7364): Found class 'com.mcafee.lgmdm.LGMDMWrapper$HardReset'.
D/LGMDMWrapper( 7364): Found class 'com.mcafee.lgmdm.LGMDMWrapper$HardwareKeyReset'.
D/LGMDMWrapper( 7364): Found class 'com.mcafee.lgmdm.LGMDMWrapper$RemoveDeviceAdmin'.
D/LGMDMWrapper( 7364): Found class 'com.mcafee.lgmdm.LGMDMWrapper$UnknownSourceInstallation'.
D/LGMDMWrapper( 7364): Found class 'com.mcafee.lgmdm.LGMDMWrapper$Usb'.
,D/LGMDMWrapper( 7364): Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbDebugging'.
D/LGMDMWrapper( 7364): Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbHostStorage'.
D/LGMDMWrapper( 7364): Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbMediaTransfer'.
D/LGMDMWrapper( 7364): Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbPictureTransfer'.
D/LGMDMWrapper( 7364): Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbStorage'.
D/LGMDMWrapper( 7364): Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbTethering'.
V/LGMDMManager( 7364): Create singleton instance
D/LGMDMWrapper( 7364): LG MDM library v4.0.0 is available on this device.
,D/PostponalbeReceiver( 7364): WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,W/ContextImpl( 7364): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
I/ActivityManager( 1030): Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=7399 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,I/ActivityManager( 1030): Killing 6838:com.lge.clock/u0a10 (adj 15): empty #17
I/jxcore-log( 6121): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6121): 
I/jxcore-log( 6121): Error type "connect_error" when connecting to the test server
I/jxcore-log( 6121): 
,W/libprocessgroup( 1030): failed to open /acct/uid_10010/pid_6838/cgroup.procs: No such file or directory
D/WifiServiceImplEx( 1030): setWifiEnabled: false pid=6121, uid=10311, package= com.test.thalitest, App Lable : ThaliTest
D/WifiService( 1030): setWifiEnabled: false pid=6121, uid=10311
E/WifiService( 1030): Invoking mWifiStateMachine.setWifiEnabled
,E/WifiStateMachine( 1030):  DisconnectedState CMD_STOP_SUPPLICANT 0 0
E/WifiStateMachine( 1030):  ConnectModeState CMD_STOP_SUPPLICANT 0 0
E/WifiStateMachine( 1030):  DriverStartedState CMD_STOP_SUPPLICANT 0 0
E/WifiStateMachine( 1030):  SupplicantStartedState CMD_STOP_SUPPLICANT 0 0
D/LocationManagerService( 1030): getAllProviders()=[passive, gps, network]
D/Ulp_jni ( 1030): JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
D/Ulp_jni ( 1030): JNI:system_update. Event-4
D/WifiServiceImplEx( 1030): setWifiEnabled: true pid=6121, uid=10311, package= com.test.thalitest, App Lable : ThaliTest
D/WifiService( 1030): setWifiEnabled: true pid=6121, uid=10311
E/WifiService( 1030): Invoking mWifiStateMachine.setWifiEnabled
D/WifiScanningService( 1030): SCAN_AVAILABLE : 1
D/RttService( 1030): SCAN_AVAILABLE : 1
D/LGWifiP2pService( 1030): InactiveState{ when=0 what=131204 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiScanningService( 1030): DefaultState got{ when=0 what=160007 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1030): P2pEnabledState{ when=0 what=131204 target=com.android.internal.util.StateMachine$SmHandler }
D/RttService( 1030): EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiMonitor( 1030): stopMonitoring(p2p0) = com.android.server.wifi.p2p.LGWifiP2pServiceImpl$P2pStateMachine@1f2d5cd9
D/LGWifiP2pService( 1030): P2pDisablingState
,V/WfdStateTracker( 1950): WfdStateTracker handleDirectStateChangedEvent: 0
D/WfdsService( 1950): WifiP2pState is changed : false
D/WfdsService( 1950): WfdsEnabledState: Receive the WFDS_DISABLE message
D/WfdsService( 1950): Set the WFDS Monitor: false
D/WfdsMonitor( 1950): WFDS Monitor is stopped
D/WfdsService( 1950): STATE : WfdsDisabledState - enter
D/CtrlSupplicant( 1950): Received on exit socket, terminate
E/CtrlSupplicant( 1950): wfds_wait_for_event: buf = CTRL-EVENT-TERMINATING  - connection closed
D/WfdsMonitor( 1950): Event [CTRL-EVENT-TERMINATING  - connection closed]
D/WfdsMonitor( 1950): WfdsMonitorThread is received the interrupt - closing
W/WfdsSession:Controller( 1950): DefaultState - msg [9441355] is not handled
W/WfdsService( 1950): DefaultState - msg [9445378] is not handled
D/LGWifiP2pService( 1030): P2pDisablingState{ when=-1ms what=147458 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1030): p2p socket connection lost
D/LocationManagerService( 1030): getAllProviders()=[passive, gps, network]
D/WifiController( 1030): WifiController msg { when=-2ms what=155656 target=com.android.internal.util.StateMachine$SmHandler } deferred for 484ms
D/Ulp_jni ( 1030): JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 1,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
D/Ulp_jni ( 1030): JNI:system_update. Event-4
D/LGWifiP2pService( 1030): P2pDisabledState
E/WifiStateMachine( 1030):  WaitForP2pDisableState CMD_DISABLE_P2P_RSP uid=1000 0 0
D/WifiNative-wlan0( 1030): doBoolean: DRIVER BTCOEXMODE 2
I/wpa_supplicant( 6226): wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
D/WifiServiceImplEx( 1030): disconnect pid=6121, uid=10311, packageName=com.test.thalitest
D/LGWifiP2pService( 1030): P2pDisabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1030): DefaultState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiServiceImplEx( 1030): reconnect pid=6121, uid=10311, packageName=com.test.thalitest
I/jxcore-log( 6121): Wifi toggled for connection repairment
I/jxcore-log( 6121): 
D/WifiNative-wlan0( 1030): DRIVER BTCOEXMODE 2: returned true
D/WifiNative-wlan0( 1030): doBoolean: SET ps 1
I/chromium( 6121): [INFO:CONSOLE(63)] "logCallback Error type "connect_error" when connecting to the test server", source: file:///android_asset/www/js/thali_main.js (63)
D/WifiNative-wlan0( 1030): SET ps 1: returned true
D/CommandListener(  311): Clearing all IP addresses on wlan0
D/DhcpStateMachine( 1030): StoppedState{ when=-1ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiHS20( 1030): hidePasspointNotification off =false
I/StatusBar.NetworkController( 1446): networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1446): mWifiConnected = false, mWifiLevel = 0
,D/StatusBar.NetworkController( 1446): refreshViews: Data not connected!! Set no data type icon / Roaming
W/Settings( 1030): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1030): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1030): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
D/WifiNative-p2p0( 1030): doBoolean: TERMINATE
D/WifiHS20( 1030): hidePasspointNotification off =false
D/WifiNative-p2p0( 1030): TERMINATE: returned true
E/WifiStateMachine( 1030): Couldn't get getWiFiOffloadingIface : 
E/WifiStateMachine( 1030): useWiFiOffloading() : false
E/WifiStateMachine( 1030): CONFIG_LGE_WLAN_PATH : true
I/StatusBar.NetworkController( 1446): networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1446): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1446): refreshViews: Data not connected!! Set no data type icon / Roaming
W/Settings( 1030): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1030): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1030): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
E/WifiStateMachine( 1030):  SupplicantStoppingState CMD_DISCONNECT 0 0
,E/WifiStateMachine( 1030):  DefaultState CMD_DISCONNECT 0 0
E/WifiStateMachine( 1030):  SupplicantStoppingState CMD_RECONNECT 0 0
E/WifiStateMachine( 1030):  DefaultState CMD_RECONNECT 0 0
E/WifiStateMachine( 1030):  SupplicantStoppingState CMD_ON_QUIT 0 0
E/WifiStateMachine( 1030):  DefaultState CMD_ON_QUIT 0 0
D/StatusBar.NetworkController( 1446): refreshViews: Data not connected!! Set no data type icon / Roaming
V/WfdStateTracker( 1950): WfdStateTracker handleDirectStateChangedEvent: 6
I/WifiServerServiceExt( 1030): WIFI_STATE_CHANGED_ACTION [0]
I/PCSuite ( 7399): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
,D/PCSuite ( 7399): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 7399): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 7322): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,W/ActivityThread( 7364): ClassLoader.getResources: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,D/LgDataFeature( 7322): LgDataFeature() Constructor: none
,D/LgDataFeature( 7322): LgDataFeature() Constructor Done, null
,D/WiFiOffLoadBroadcast( 7322): MCCMNC not supported: null
,D/QRemote ( 6386): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,D/QRemote ( 6386): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 6386): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
D/PostponalbeReceiver( 7364): WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
W/ContextImpl( 7364): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
I/PCSuite ( 7399): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 7399): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 7399): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 7322): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 7322): MCCMNC not supported: null
D/QRemote ( 6386): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6386): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 6386): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,D/PostponalbeReceiver( 7364): WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
W/ContextImpl( 7364): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
I/PCSuite ( 7399): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 7399): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 7399): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 7322): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 7322): MCCMNC not supported: null
D/QRemote ( 6386): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6386): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 6386): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
D/PostponalbeReceiver( 7364): WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
W/ContextImpl( 7364): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
,V/WiFiOffLoadBroadcast( 7322): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 7322): MCCMNC not supported: null
D/QRemote ( 6386): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6386): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 6386): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
D/PostponalbeReceiver( 7364): WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'null'.
D/PostponalbeReceiver( 7364): WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
W/ContextImpl( 7364): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
I/PCSuite ( 7399): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
,D/PCSuite ( 7399): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 7399): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 7322): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 7322): MCCMNC not supported: null
,D/QRemote ( 6386): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,D/QRemote ( 6386): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 6386): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
D/PostponalbeReceiver( 7364): WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
W/ContextImpl( 7364): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
I/PCSuite ( 7399): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 7399): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 7399): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 7322): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 7322): MCCMNC not supported: null
,D/QRemote ( 6386): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6386): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 6386): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
I/ActivityManager( 1030): Start proc com.lge.formmanager for broadcast com.lge.formmanager/.FormServiceReceiver: pid=7444 uid=10026 gids={50026, 9997, 3003, 1028} abi=armeabi-v7a
,I/ActivityManager( 1030): Killing 6711:com.lge.sizechangable.weather/u0a85 (adj 15): empty #17
I/art     (  338): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 435us total 20.933ms
,D/LgDataFeature( 7364): LgDataFeature() Constructor: none
D/LgDataFeature( 7364): LgDataFeature() Constructor Done, null
I/art     (  338): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 362us total 18.023ms
,I/art     (  338): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 285us total 15.386ms
,W/libprocessgroup( 1030): failed to open /acct/uid_10085/pid_6711/cgroup.procs: No such file or directory
,W/ContextImpl( 7364): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.vsmandroid.gh.h:-1 com.mcafee.vsm.ext.common.a.d.a:-1 com.mcafee.vsm.ext.common.api.ExtUtils.stopApp:-1 
,D/SiteAdvisor( 7364): com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.google.android.browser/com.android.browser.BrowserActivity not supported
,D/WifiController( 1030): DEFERRED_TOGGLE handled
E/WifiStateMachine( 1030):  SupplicantStoppingState CMD_START_SUPPLICANT 0 0
E/WifiStateMachine( 1030):  SupplicantStoppingState CMD_SET_OPERATIONAL_MODE 1 0
E/WifiStateMachine( 1030):  SupplicantStoppingState CMD_START_DRIVER 0 0
E/WifiStateMachine( 1030):  SupplicantStoppingState CMD_SET_HIGH_PERF_MODE 0 0
E/WifiStateMachine( 1030):  DefaultState CMD_SET_HIGH_PERF_MODE 0 0
D/SiteAdvisor( 7364): com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.amazon.cloud9/com.amazon.cloud9.BrowserActivity not supported
D/SiteAdvisor( 7364): com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.sec.android.app.sbrowser/com.sec.android.app.sbrowser.SBrowserMainActivity not supported
D/SiteAdvisor( 7364): com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.sec.android.app.sbrowser/com.sec.android.app.sbrowser.SBrowserMainActivity not supported
D/SiteAdvisor( 7364): com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.htc.sense.browser/com.htc.sense.browser.BrowserActivity not supported
I/SiteAdvisor( 7364): com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Loading supported browsers: com.android.browser/com.android.browser.BrowserActivity; com.android.chrome/com.android.chrome.Main; 
D/SiteAdvisor( 7364): com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Here is the storedCurrentAppVersion: 3.1.2.1430
,D/PCSuite ( 7399): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
D/SiteAdvisor( 7364): com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Here about to commit perfs
V/WiFiOffLoadBroadcast( 7322): WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,D/WiFiOffLoadBroadcast( 7322): MCCMNC not supported: null
D/PostponalbeReceiver( 7364): WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'null'.
,D/PostponalbeReceiver( 7364): WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'null'.
D/PostponalbeReceiver( 7364): WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'null'.
D/PostponalbeReceiver( 7364): WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'null'.
D/PostponalbeReceiver( 7364): WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'null'.
W/FormManager( 7444): Network not available. Please check & try again.
,V/FormManager( 7444): Network unavailable.
,V/FormManager( 7444): Network unavailable.
,I/ActivityManager( 1030): Killing 6930:com.google.android.talk/u0a72 (adj 15): empty #17
W/libprocessgroup( 1030): failed to open /acct/uid_10072/pid_6930/cgroup.procs: No such file or directory
,I/wpa_supplicant( 6226): p2p0: CTRL-EVENT-TERMINATING 
,I/wpa_supplicant( 6226): monitor socket send errors count : 1,
I/wpa_supplicant( 6226): CTRL_IFACE: Detach monitor /data/misc/wifi/sockets/wpa_ctrl_1950-2\x00 that cannot receive messages
D/WifiMonitor( 1030): Event [IFNAME=p2p0 CTRL-EVENT-TERMINATING ]
W/wpa_supplicant( 6226): USIM:  scard_deinit function
D/WifiMonitor( 1030): Dropping event because (p2p0) is stopped
D/WifiMonitor( 1030): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=0 BSSID=00:00:00:00:00:00 SSID=]
E/WifiMonitor( 1030): WifiMonitor:wlan0 cnt=24 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=0 BSSID=00:00:00:00:00:00 SSID=
E/WifiStateMachine( 1030):  SupplicantStoppingState SUPPLICANT_STATE_CHANGE_EVENT 24 0 rt=427429  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: DISCONNECTED
E/WifiStateMachine( 1030):  DefaultState SUPPLICANT_STATE_CHANGE_EVENT 24 0 rt=427431  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: DISCONNECTED
I/wpa_supplicant( 6226): wlan0: CTRL-EVENT-TERMINATING 
D/WifiMonitor( 1030): Event [IFNAME=wlan0 CTRL-EVENT-TERMINATING ]
E/WifiMonitor( 1030): WifiMonitor:wlan0 cnt=25 dispatchEvent: CTRL-EVENT-TERMINATING 
D/WifiMonitor( 1030): Disconnecting from the supplicant, no more events
E/WifiStateMachine( 1030):  SupplicantStoppingState SUP_DISCONNECTION_EVENT 25 0
,D/WfdsService( 1950): Supplicant Connection state is changed : false
,D/WfdsService( 1950): DefaultState - WIFI_SUPPLICANT_DISCONNECTED
D/WfdsService( 1950): Set the WFDS Monitor: false
D/WfdsMonitor( 1950): WFDS Monitor is stopped
D/WifiOffDelayIfNotUsed( 1030): stopMonitoring
E/WifiStateMachine( 1030): Couldn't get getWiFiOffloadingIface : 
E/WifiStateMachine( 1030): useWiFiOffloading() : false
E/WifiStateMachine( 1030): CONFIG_LGE_WLAN_PATH : true
I/WifiServerServiceExt( 1030): WIFI_STATE_CHANGED_ACTION [1]
,I/WifiServerServiceExt( 1030): batteryPsActivateMsgHandler : state:0 event:1
V/WfdStateTracker( 1950): WfdStateTracker handleDirectStateChangedEvent: 0
I/WifiServerServiceExt( 1030): batteryPsActivateMsgHandler : this is not treated
D/StatusBar.NetworkController( 1446): refreshViews: Data not connected!! Set no data type icon / Roaming
W/Settings( 1819): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/LGDMClient( 3941): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
D/LGDMClient( 3941): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,W/ContextImpl( 3941): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
W/ContextImpl( 3941): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
I/PCSuite ( 7399): [StartReceiver]WIFI_STATE_CHANGED_ACTION : WIFI_STATE_DISABLED
D/PCSuite ( 7399): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 7399): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,V/WiFiOffLoadBroadcast( 7322): WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,D/WiFiOffLoadBroadcast( 7322): MCCMNC not supported: null
D/LGDMClient( 3941): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=3, isUserType=1
,W/FormManager( 7444): Network not available. Please check & try again.
V/FormManager( 7444): Network unavailable.
,V/FormManager( 7444): Network unavailable.
D/LGDMClient( 3941): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
D/LGDMClient( 3941): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
,E/WifiStateMachine( 1030):  InitialState CMD_START_SUPPLICANT 0 0
I/LGFTMITEM( 1030): [GET_FTM][id=6], offset=12288
,E/WifiUtil( 1030): wfc_util_ffile_check_copy(): pid[1030] pDestFName[/data/misc/wifi/WCNSS_qcom_cfg.ini] pSourceFName[/system/etc/wifi/WCNSS_qcom_cfg.ini]
E/WifiUtil( 1030): wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
E/WifiUtil( 1030): wfc_util_ffile_check_copy(): pid[1030] pDestFName[/data/misc/wifi/WCNSS_qcom_wlan_nv.bin] pSourceFName[/system/etc/wifi/WCNSS_qcom_wlan_nv.bin]
E/WifiUtil( 1030): wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
I/WifiUtil( 1030): Intf0MacAddress=C49A027B60AC
E/WifiHW  ( 1030): unknown target_country: EU , set to default
E/WifiHW  ( 1030): [wifi_ensure_config_files] default country1 = GB
E/WifiHW  ( 1030): [wifi_ensure_config_files] default country2 = GB
I/WifiUtil( 1030): gEnableBmps=1
D/SoftapController(  311): Softap fwReload - Ok
,D/ConnectivityService( 1030): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
E/NetdConnector( 1030): NDC Command {53 softap fwreload wlan0 STA} took too long (578ms)
D/ConnectivityService( 1030): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/CommandListener(  311): Setting iface cfg
D/CommandListener(  311): Trying to bring down wlan0
,D/CommandListener(  311): Clearing all IP addresses on wlan0
D/Tethering( 1030): sendTetherStateChangedBroadcast 0, 0, 0
D/Tethering( 1030): InitialState.processMessage what=4
D/Tethering( 1030): sendTetherStateChangedBroadcast 0, 0, 0
D/Tethering( 1030): MasterInitialState.processMessage what=3
,D/GpsLocationProvider( 1030): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
E/WifiHW  ( 1030): Cannot open "/system/etc/wifi/autojoinconfig.txt": No such file or directory
W/wpa_supplicant( 7492): type=1400 audit(0.0:165): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
E/WifiStateMachine( 1030): Couldn't get getWiFiOffloadingIface : 
E/WifiStateMachine( 1030): useWiFiOffloading() : false
E/WifiStateMachine( 1030): CONFIG_LGE_WLAN_PATH : true
W/wpa_supplicant( 7492): type=1400 audit(0.0:166): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,D/PostponalbeReceiver( 7364): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
,D/WifiMonitor( 1030): startMonitoring(wlan0) with mConnected = false
D/WifiMonitor( 1030): connecting to supplicant
I/wpa_supplicant( 7492): Successfully initialized wpa_supplicant
D/Tethering( 1030): MasterInitialState.processMessage what=3
,I/WifiServerServiceExt( 1030): WIFI_STATE_CHANGED_ACTION [2]
W/ContextImpl( 7364): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
D/StatusBar.NetworkController( 1446): refreshViews: Data not connected!! Set no data type icon / Roaming
,I/wpa_supplicant( 7492): rfkill: Cannot open RFKILL control device
I/wpa_supplicant( 7492): [LGE_PATCH] unset P2P_CAPABLE to ifname wlan0
V/WfdStateTracker( 1950): WfdStateTracker handleDirectStateChangedEvent: 1
I/NetworkMonitor( 5187): type=WIFI subType= reason=null isConnected=false
D/GpsLocationProvider( 1030): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
D/GpsLocationProvider( 1030): updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/GpsLocationProvider( 1030): updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/NetworkMonitor( 5187): type=WIFI subType= reason=null isConnected=false
I/NetworkStateForAutoUpdateMonitor( 7040): [onReceive] BroadcastReceiver onReceive
,I/NetworkStateForAutoUpdateMonitor( 7040): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 7040): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 7040): [onReceive] request level :IDLE....
I/AppUp4:CustModeStarterReceiver( 7040): onReceive
D/AppUp4:CustFacade( 7040): Context : android.app.ReceiverRestrictedContext@1d2083bc
D/AppUp4:CustFacade( 7040): isCustomizationCompleted : false
D/AppUp4:CustFacade( 7040): isPhone : true
D/AppUp4:CustModeStarterReceiver( 7040): begin check event
I/AppUp4:CustModeStarterReceiver( 7040): Event For GoodConnectivity
D/AppUp4:CustModeStarterReceiver( 7040): runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
D/AppUp4:CustModeStarterReceiver( 7040): call method handleAsyncCustNotification.
D/AppUp4:CustModeStarterReceiver( 7040): handleAsync isTriedOnce : false
E/AppUp4:CustModeStarterReceiver( 7040): handleAsyncCustNotification do not startCustService
D/LGDMClient( 3941): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 3941): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
W/ContextImpl( 3941): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,W/ContextImpl( 3941): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
D/LGDMClient( 3941): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=3, isUserType=1
D/LGDMClient( 3941): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 3941): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
I/wpa_supplicant( 7492): rfkill: Cannot open RFKILL control device
I/ActivityManager( 1030): Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=7513 uid=10023 gids={50023, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,I/wpa_supplicant( 7492): [LGE_WLAN_PATCH]P2P 5GHz support level:2(0:no 1:gconly 2:gconly_UNII1 3:full)
,E/WifiStateMachine( 1030):  SupplicantStartingState CMD_SET_OPERATIONAL_MODE 1 0
E/WifiStateMachine( 1030):  SupplicantStartingState CMD_START_DRIVER 0 0
E/WifiStateMachine( 1030):  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1030):  DefaultState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1030):  SupplicantStartingState SUP_CONNECTION_EVENT 0 0
D/WifiNative-wlan0( 1030): doString: [DRIVER MACADDR]
D/WifiNative-wlan0( 1030):    returned Macaddr = c4:9a:02:7b:60:ac
D/WifiStateMachine( 1030): MAC Addr from driver = c4:9a:02:7b:60:ac
D/WifiOffDelayIfNotUsed( 1030): setPowerSaveActivated(false)
E/WifiStateMachine( 1030): Couldn't get getWiFiOffloadingIface : 
E/WifiStateMachine( 1030): useWiFiOffloading() : false
E/WifiStateMachine( 1030): CONFIG_LGE_WLAN_PATH : true
D/WifiNative-wlan0( 1030): doBoolean: SET update_config 1
D/WifiNative-wlan0( 1030): SET update_config 1: returned true
D/WifiConfigStore( 1030): Loading config and enabling all networks 
D/WifiNative-wlan0( 1030): doString: [LIST_NETWORKS]
W/Settings( 1030): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1030): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1030): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings( 1030): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1030): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
D/WifiNative-wlan0( 1030):    returned network id / ssid / bssid / flags 0	NG700	any	
D/StatusBar.NetworkController( 1446): refreshViews: Data not connected!! Set no data type icon / Roaming
D/WfdService( 1950): Waiting for WifiP2p enabling
I/WifiServerServiceExt( 1030): WIFI_STATE_CHANGED_ACTION [3]
I/WifiServerServiceExt( 1030): batteryPsActivateMsgHandler : state:0 event:3
I/wpa_supplicant( 7492): wlan0: CTRL-EVENT-SCAN-STARTED 
D/WifiMonitor( 1030): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
E/WifiMonitor( 1030): WifiMonitor:wlan0 cnt=25 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
D/WifiMonitor( 1030): Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1030): WifiMonitor:wlan0 cnt=26 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1030): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1030): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
D/sensors_hal_Time( 1030): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1030): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1030): tsOffsetIs: Apps: 428777675829; DSPS: 14190783; Offset : -4304280863
E/WifiConfigStore( 1030): readNetworkVariablesFromSupplicantFile key=psk
,E/WifiConfigStore( 1030): readNetworkVariableFromSupplicantFile ssid=["NG700"] key=psk
E/WifiConfigStore( 1030): Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
D/WifiStateMachine( 1030): enableVerboseLogging : level 2
D/WifiNative-wlan0( 1030): doBoolean: SET device_name g3_global_com
D/WifiNative-wlan0( 1030): SET device_name g3_global_com: returned true
D/WifiNative-wlan0( 1030): doBoolean: SET manufacturer LGE
D/WifiNative-wlan0( 1030): SET manufacturer LGE: returned true
D/WifiNative-wlan0( 1030): doBoolean: SET model_name LG-D855
D/WifiNative-wlan0( 1030): SET model_name LG-D855: returned true
W/ResourcesManager( 7513): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
D/WifiNative-wlan0( 1030): doBoolean: SET model_number LG-D855
D/WifiNative-wlan0( 1030): SET model_number LG-D855: returned true
D/WifiNative-wlan0( 1030): doBoolean: SET serial_number LGD8553bed2d08
W/ResourcesManager( 7513): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,D/WifiNative-wlan0( 1030): SET serial_number LGD8553bed2d08: returned true
D/WifiNative-wlan0( 1030): doBoolean: SET config_methods physical_display virtual_push_button
D/WifiNative-wlan0( 1030): SET config_methods physical_display virtual_push_button: returned true
D/WifiNative-wlan0( 1030): doBoolean: SET device_type 10-0050F204-5
D/WifiNative-wlan0( 1030): SET device_type 10-0050F204-5: returned true
W/ResourcesManager( 7513): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
W/ResourcesManager( 7513): Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
,D/WfdsService( 1950): Supplicant Connection state is changed : true
D/WfdsService( 1950): DefaultState - WIFI_SUPPLICANT_CONNECTED
D/WfdsService( 1950): Set the WFDS Monitor: true
D/WfdsMonitor( 1950): WfdsMonitorThread create
D/WfdsMonitor( 1950): WFDS Monitor is created and started
D/WfdsService( 1950): WiFi: Supplicant connection re-established
D/WifiStateMachine( 1030): Setting OUI to DA-A1-19
D/WifiNative-wlan0( 1030): doBoolean: SCAN_INTERVAL 120
D/WifiNative-wlan0( 1030): SCAN_INTERVAL 120: returned true
D/WifiNative-HAL( 1030): Setting external_sim to 1
D/WifiNative-wlan0( 1030): doBoolean: SET external_sim 1
D/WifiNative-wlan0( 1030): SET external_sim 1: returned true
I/WifiNative-HAL( 1030): startHal
E/wifi    ( 1030): getStaticLongField sWifiHalHandle 0x9892c8dc
E/WifiHAL ( 1030): Could not connect handle
D/wifi    ( 1030): halHandle = 0x0, mVM = 0xb487c280, mCls = 0x601da6
I/WifiNative-HAL( 1030): Could not start hal
D/WifiStateMachine( 1030): Setting OUI to DA-A1-19
I/WifiNative-HAL( 1030): startHal
E/wifi    ( 1030): getStaticLongField sWifiHalHandle 0x9892c85c
E/WifiHAL ( 1030): Could not connect handle
D/wifi    ( 1030): halHandle = 0x0, mVM = 0xb487c280, mCls = 0x801d8a
I/WifiNative-HAL( 1030): Could not start hal
D/WifiNative-wlan0( 1030): doBoolean: STA_AUTOCONNECT 1
D/WifiNative-wlan0( 1030): STA_AUTOCONNECT 1: returned true
E/CtrlSupplicant( 1950): Access OK "@android:wpa_wlan0"
D/WifiNative-wlan0( 1030): doBoolean: DRIVER BTCOEXSCAN-STOP
I/wpa_supplicant( 7492): wpa_driver_nl80211_ext_driver_cmd BTCOEXSCAN-STOP
D/WifiNative-wlan0( 1030): DRIVER BTCOEXSCAN-STOP: returned true
E/CtrlSupplicant( 1950): Succeed to open control connection
D/WifiNative-wlan0( 1030): doBoolean: DRIVER RXFILTER-STOP
E/CtrlSupplicant( 1950): Succeed to open monitor connection
I/wpa_supplicant( 7492): wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
D/WifiNative-wlan0( 1030): DRIVER RXFILTER-STOP: returned true
D/WifiNative-wlan0( 1030): doBoolean: DRIVER RXFILTER-REMOVE 3
D/WfdsMonitor( 1950): Supplicant connection established
I/wpa_supplicant( 7492): wpa_driver_nl80211_ext_driver_cmd RXFILTER-REMOVE 3
D/WfdsService( 1950): Connected to the supplicant for wfds
D/WifiNative-wlan0( 1030): DRIVER RXFILTER-REMOVE 3: returned true
D/WifiNative-wlan0( 1030): doBoolean: DRIVER RXFILTER-START
I/wpa_supplicant( 7492): wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
D/WifiNative-wlan0( 1030): DRIVER RXFILTER-START: returned true
D/WifiNative-wlan0( 1030): doBoolean: DRIVER RXFILTER-STOP
I/wpa_supplicant( 7492): wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
D/WifiNative-wlan0( 1030): DRIVER RXFILTER-STOP: returned true
D/WifiNative-wlan0( 1030): doBoolean: DRIVER RXFILTER-REMOVE 2
I/wpa_supplicant( 7492): android_multicast_filter_startstop : multicast filter set
D/WifiNative-wlan0( 1030): DRIVER RXFILTER-REMOVE 2: returned true
D/WifiNative-wlan0( 1030): doBoolean: DRIVER RXFILTER-START
I/wpa_supplicant( 7492): wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
D/WifiNative-wlan0( 1030): DRIVER RXFILTER-START: returned true
E/WifiNative: ( 1030): [428,784,019 us] RECONNECT  stack:logDbg - reconnect - enter - invokeEnterMethods - performTransitions
D/WifiNative-wlan0( 1030): doBoolean: RECONNECT
D/WifiNative-wlan0( 1030): RECONNECT: returned true
D/WifiNative-wlan0( 1030): doString: [STATUS]
D/WifiMonitor( 1030): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
E/WifiMonitor( 1030): WifiMonitor:wlan0 cnt=27 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
D/WifiNative-wlan0( 1030):    returned wpa_state=SCANNING p2p_device_address=02:9a:02:7b:60:ac address=c4:9a:02:7b:60:ac uuid=530d3fd0-1ba3-5409-a336-ff4e42af59a2
D/WifiNative-wlan0( 1030): doBoolean: SET ps 1
D/WifiNative-wlan0( 1030): SET ps 1: returned true
D/LGWifiP2pService( 1030): P2pDisabledState{ when=-1ms what=131203 target=com.android.internal.util.StateMachine$SmHandler }
D/CommandListener(  311): Setting iface cfg
D/CommandListener(  311): ,Trying to bring up p2p0
D/WifiMonitor( 1030): startMonitoring(p2p0) with mConnected = true
D/LGWifiP2pService( 1030): P2pEnablingState
D/LGWifiP2pService( 1030): P2pEnablingState{ when=0 what=147457 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1030): P2p socket connection successful
D/LGWifiP2pService( 1030): P2pEnabledState
V/WfdStateTracker( 1950): WfdStateTracker handleDirectStateChangedEvent: 2
D/WfdsService( 1950): WifiP2pState is changed : true
D/WfdsService( 1950): Receive the WFDS_ENABLE Method
D/WfdsService( 1950): Set the WFDS Monitor: true
D/WfdsService( 1950): Connected to the supplicant for wfds
D/WfdsJNI ( 1950): doCommand: WFDS_SET TRUE
I/wpa_supplicant( 7492): WFDS: wfds_supplicant_wfds_cmd: cmd = SET TRUE
D/WfdsService( 1950): selectPreferredScanChannel [36]
D/WfdsService( 1950): STATE : WfdsEnabledState - enter: this device mac 02:9a:02:7b:60:ac
D/LGWifiP2pService( 1030): sending p2p connection changed broadcast
D/WifiNative-p2p0( 1030): doBoolean: SET persistent_reconnect 1
D/WfdsService( 1950): WIFI_P2P_CONNECTION_CHANGED_ACTION
D/WfdsService( 1950): isConnected: false
D/WifiNative-p2p0( 1030): SET persistent_reconnect 1: returned true
D/WifiNative-p2p0( 1030): doBoolean: SET device_name G3-1
D/WifiNative-p2p0( 1030): SET device_name G3-1: returned true
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
D/WifiNative-p2p0( 1030): P2P_SET conc_pref p2p: returned true
D/WifiNative-HAL( 1030): p2pGetDeviceAddress
D/WifiNative-HAL( 1030): p2pGetDeviceAddress returning 02:9a:02:7b:60:ac
I/WfdStateTracker( 1950): handleP2pThisDeviceChanged
D/WfdsService( 1950): WIFI_P2P_THIS_DEVICE_CHANGED_ATCION
D/LGWifiP2pService( 1030): DeviceAddress: 02:9a:02:7b:60:ac
D/WfdsService( 1950): Update P2p Interface State: 3
D/WifiScanningService( 1030): SCAN_AVAILABLE : 3
D/WifiScanningService( 1030): DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
I/WifiNative-HAL( 1030): startHal
E/wifi    ( 1030): getStaticLongField sWifiHalHandle 0x94e3799c
E/WifiHAL ( 1030): Could not connect handle
D/wifi    ( 1030): halHandle = 0x0, mVM = 0xb487c280, mCls = 0x801d5a
I/WifiNative-HAL( 1030): Could not start hal
E/WifiScanningService( 1030): could not start HAL
D/RttService( 1030): SCAN_AVAILABLE : 3
D/RttService( 1030): DefaultState got{ when=-1ms what=160512 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiStateMachine( 1030):  DisconnectedState CMD_SET_OPERATIONAL_MODE 1 0
D/WifiNative-p2p0( 1030): doBoolean: P2P_FLUSH
D/WifiNative-p2p0( 1030): P2P_FLUSH: returned true
D/WifiNative-p2p0( 1030): doBoolean: P2P_SERVICE_FLUSH
E/WifiStateMachine( 1030):  DisconnectedState CMD_START_DRIVER 0 0
D/WifiNative-p2p0( 1030): P2P_SERVICE_FLUSH: returned true
D/WifiNative-p2p0( 1030): doString: [LIST_NETWORKS]
D/WifiNative-p2p0( 1030):    returned network id / ssid / bssid / flags
E/WifiStateMachine( 1030):  ConnectModeState CMD_START_DRIVER 0 0
D/WifiNative-p2p0( 1030): doBoolean: SAVE_CONFIG
E/WifiStateMachine( 1030):  DriverStartedState CMD_START_DRIVER 0 0
E/WifiStateMachine( 1030):  DisconnectedState what:132106 1 0
E/WifiStateMachine( 1030):  ConnectModeState what:132106 1 0
E/WifiStateMachine( 1030):  DriverStartedState what:132106 1 0
I/WifiServerServiceExt( 1030): setWifiDualbandAPConnection band : 1
E/wpa_supplicant( 7492): nWIFIDualbandAPConnection: 1
,D/WifiNative-p2p0( 1030): SAVE_CONFIG: returned true
D/LGWifiP2pService( 1030): sending p2p persistent groups changed broadcast
D/LGWifiP2pService( 1030): InactiveState
D/LGWifiP2pService( 1030): InactiveState{ when=-19ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1030): P2pEnabledState{ when=-19ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-p2p0( 1030): doBoolean: DRIVER COUNTRY CZ
E/WifiStateMachine( 1030):  DisconnectedState what:132096 -100 0
I/wpa_supplicant( 7492): wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
E/WifiStateMachine( 1030):  ConnectModeState what:132096 -100 0
I/wpa_supplicant( 7492): p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
E/WifiStateMachine( 1030):  DriverStartedState what:132096 -100 0
I/WifiServerServiceExt( 1030): set CMD_DISCONNECT_RSSI_LVL : -100
I/wpa_supplicant( 7492): [LGE_PATCH] driver_cmd() country:CZ
E/wpa_supplicant( 7492): disconnect_rssi_lvl: -100
I/wpa_supplicant( 7492): p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
D/WfdsMonitor( 1950): Event [CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
D/WfdsMonitor( 1950): Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
I/wpa_supplicant( 7492): p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
D/WfdsMonitor( 1950): Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
D/WifiMonitor( 1030): Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
E/WifiMonitor( 1030): WifiMonitor:p2p0 cnt=28 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
E/WifiMonitor( 1030): handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
E/WifiMonitor( 1030): handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
D/WifiMonitor( 1030): Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
E/WifiMonitor( 1030): WifiMonitor:p2p0 cnt=29 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
E/WifiMonitor( 1030): handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
E/WifiMonitor( 1030): handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
D/WifiMonitor( 1030): Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
E/WifiMonitor( 1030): WifiMonitor:p2p0 cnt=30 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
E/WifiMonitor( 1030): handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
E/WifiMonitor( 1030): handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
D/WifiNative-p2p0( 1030): DRIVER COUNTRY CZ: returned true
D/LGWifiP2pService( 1030): InactiveState{ when=-3ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1030): P2pEnabledState{ when=-3ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiStateMachine( 1030):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 25 0 rt=428821  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
D/LGWifiP2pService( 1030): DefaultState{ when=-3ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1030): InactiveState{ when=-4ms what=139285 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1030): P2pEnabledState{ when=-4ms what=139285 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1030): DefaultState{ when=-4ms what=139285 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1030): InactiveState{ when=-4ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1030): P2pEnabledState{ when=-4ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
W/WfdsService( 1950): DefaultState - msg [9441285] is not handled
D/LGWifiP2pService( 1030): DefaultState{ when=-5ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1030): InactiveState{ when=-5ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1030): P2pEnabledState{ when=-5ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
W/Settings( 1030): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/StatusBar.NetworkController( 1446): networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
W/Settings( 1030): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/StatusBar.NetworkController( 1446): mWifiConnected = false, mWifiLevel = 0
D/WifiOffDelayIfNotUsed( 1030): NETWORK_STATE_CHANGED_ACTION [SCANNING]
D/LGWifiP2pService( 1030): DefaultState{ when=-5ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
D/StatusBar.NetworkController( 1446): refreshViews: Data not connected!! Set no data type icon / Roaming
E/WifiStateMachine( 1030):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 25 0 rt=428825  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
E/WifiServerServiceExt( 1030): No p2p device connected
E/WifiStateMachine( 1030):  DisconnectedState CMD_SET_COUNTRY_CODE 2 0 cz
E/WifiStateMachine( 1030):  ConnectModeState CMD_SET_COUNTRY_CODE 2 0 cz
I/LGEmail ( 7513): [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
E/WifiStateMachine( 1030):  DriverStartedState CMD_SET_COUNTRY_CODE 2 0 cz
D/WifiNative-wlan0( 1030): doBoolean: DRIVER COUNTRY CZ
I/wpa_supplicant( 7492): wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
I/wpa_supplicant( 7492): wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
I/wpa_supplicant( 7492): [LGE_PATCH] driver_cmd() country:CZ
I/wpa_supplicant( 7492): p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
I/wpa_supplicant( 7492): p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
D/WifiMonitor( 1030): Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
E/WifiMonitor( 1030): WifiMonitor:wlan0 cnt=31 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
E/WifiMonitor( 1030): handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
E/WifiMonitor( 1030): handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
D/WifiMonitor( 1030): Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
E/WifiMonitor( 1030): WifiMonitor:p2p0 cnt=32 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
E/WifiMonitor( 1030): handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
E/WifiMonitor( 1030): handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
D/WifiMonitor( 1030): Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
E/WifiMonitor( 1030): WifiMonitor:p2p0 cnt=33 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
E/WifiMonitor( 1030): handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
E/WifiMonitor( 1030): handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
D/WfdsMonitor( 1950): Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
D/WfdsMonitor( 1950): Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
D/WifiNative-wlan0( 1030): DRIVER COUNTRY CZ: returned true
D/LGWifiP2pService( 1030): InactiveState{ when=0 what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1030): P2pEnabledState{ when=0 what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
E/WifiStateMachine( 1030):  DisconnectedState CMD_SET_FREQUENCY_BAND 0 0
E/WifiStateMachine( 1030):  ConnectModeState CMD_SET_FREQUENCY_BAND 0 0
E/WifiStateMachine( 1030):  DriverStartedState CMD_SET_FREQUENCY_BAND 0 0
D/WifiNative-wlan0( 1030): doBoolean: DRIVER SETBAND 0
I/wpa_supplicant( 7492): wpa_driver_nl80211_ext_driver_cmd SETBAND 0 - interface name wlan0
I/wpa_supplicant( 7492): wlan0: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
D/WifiMonitor( 1030): Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN]
E/WifiMonitor( 1030): WifiMonitor:wlan0 cnt=34 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
E/WifiMonitor( 1030): handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
E/WifiMonitor( 1030): handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
D/WifiNative-wlan0( 1030): DRIVER SETBAND 0: returned true
D/WifiNative-wlan0( 1030): doBoolean: BSS_FLUSH 0
D/WifiNative-wlan0( 1030): BSS_FLUSH 0: returned true
D/WifiNative-wlan0( 1030): doBoolean: SCAN
D/WifiNative-wlan0( 1030): SCAN: returned false
E/WifiStateMachine( 1030):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 27 0 rt=428837  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
I/StatusBar.NetworkController( 1446): networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1446): mWifiConnected = false, mWifiLevel = 0
D/LGEmail ( 7513): user build Type == true (at Util.java isUserModeBuildType 3507)[v:6.41.18]
W/Settings( 1030): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1030): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1030): NETWORK_STATE_CHANGED_ACTION [SCANNING]
I/jxcore-log( 6121): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6121): 
I/jxcore-log( 6121): Error type "connect_error" when connecting to the test server
I/jxcore-log( 6121): 
D/StatusBar.NetworkController( 1446): refreshViews: Data not connected!! Set no data type icon / Roaming
E/WifiStateMachine( 1030):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 27 0 rt=428842  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
E/WifiStateMachine( 1030):  DisconnectedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
E/WifiStateMachine( 1030):  ConnectModeState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
E/WifiStateMachine( 1030):  DriverStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
E/WifiStateMachine( 1030):  SupplicantStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
E/WifiStateMachine( 1030):  DefaultState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
D/WifiServerServiceExt( 1030): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1030): setSupplicantStateSCANNING
I/chromium( 6121): [INFO:CONSOLE(63)] "logCallback Error type "connect_error" when connecting to the test server", source: file:///android_asset/www/js/thali_main.js (63)
D/WifiServerServiceExt( 1030): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1030): setSupplicantStateSCANNING
W/ResourceType( 7513): No package identifier when getting value for resource number 0x00000000
,D/LgDataFeature( 7513): LgDataFeature() Constructor: none
D/LgDataFeature( 7513): LgDataFeature() Constructor Done, null
,D/eas_req ( 7513): ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
,I/HubEmail( 7513): JNI_OnLoad()
I/HubEmail( 7513): -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 7513): registerNatives()
I/HubEmail( 7513): -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 7513): registerNativeMethods()
I/HubEmail( 7513): -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
W/art     ( 7513): JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
,W/Settings( 7513): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/FormManager( 7444): Network not available. Please check & try again.
V/FormManager( 7444): Network unavailable.
V/FormManager( 7444): Network unavailable.
,I/ActivityManager( 1030): Killing 7077:com.android.contacts/u0a19 (adj 15): empty #17
,I/LgeMiscReceiver( 3261): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 3261): action = android.net.conn.CONNECTIVITY_CHANGE
,I/LgeMiscReceiver( 3261): networkInfo.isConnected() = false
W/libprocessgroup( 1030): failed to open /acct/uid_10019/pid_7077/cgroup.procs: No such file or directory
I/wpa_supplicant( 7492): [LGE_PATCH]scan interval[0] = 2 sec.
,E/WifiMonitor( 1030): WifiMonitor:wlan0 cnt=35 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
E/WifiMonitor( 1030): handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
D/WfdsMonitor( 1950): Event [CTRL-EVENT-SCAN-RESULTS ]
D/WifiMonitor( 1030): Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
E/WifiMonitor( 1030): WifiMonitor:wlan0 cnt=36 dispatchEvent: WPS-AP-AVAILABLE 
D/WfdsMonitor( 1950): Event [WPS-AP-AVAILABLE ]
W/WifiMonitor( 1030): couldn't identify event type - WPS-AP-AVAILABLE 
E/WifiMonitor( 1030): WifiMonitor:p2p0 cnt=37 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
E/WifiMonitor( 1030): handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
D/WifiMonitor( 1030): Event [IFNAME=p2p0 WPS-AP-AVAILABLE ]
E/WifiMonitor( 1030): WifiMonitor:p2p0 cnt=38 dispatchEvent: WPS-AP-AVAILABLE 
W/WifiMonitor( 1030): couldn't identify event type - WPS-AP-AVAILABLE 
I/ActivityManager( 1030): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=7543 uid=10057 gids={50057, 9997, 3003, 1028, 1015} abi=armeabi-v7a
D/LGWifiP2pService( 1030): InactiveState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1030): P2pEnabledState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1030): DefaultState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiStateMachine( 1030):  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=4 bcn=0
E/WifiStateMachine( 1030):  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=4 bcn=0
E/WifiStateMachine( 1030):  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=4 bcn=0
E/WifiStateMachine( 1030):  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=4 bcn=0
D/WifiNative-wlan0( 1030): doString: [BSS RANGE=0- MASK=0x21987]
,I/ActivityManager( 1030): Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=7564 uid=10062 gids={50062, 9997, 4002, 3003, 1028} abi=armeabi-v7a
I/ActivityManager( 1030): Killing 6581:com.android.gallery3d/u0a27 (adj 15): empty #17
,W/libprocessgroup( 1030): failed to open /acct/uid_10027/pid_6581/cgroup.procs: No such file or directory
,I/ActivityManager( 1030): Start proc com.lge.sizechangable.weather for broadcast com.lge.sizechangable.weather/.layout.WeatherWidget: pid=7581 uid=10085 gids={50085, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager( 1030): Killing 7101:com.lge.lockscreensettings/u0a80 (adj 15): empty #17
,W/libprocessgroup( 1030): failed to open /acct/uid_10080/pid_7101/cgroup.procs: No such file or directory
,I/art     ( 7581): Almond Protected OAT
,D/WeatherApplication( 7581): removeAccount
D/WeatherApplication( 7581): Account.length = 0
E/WeatherApplication( 7581): OPERATOR:OPEN
,D/WeatherAncestor( 7581): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 23:8:27
,D/Weather.Utils( 7581): 2 : the weather widgets(using time tick) are gone.
D/Weather.Utils( 7581): 2 : All the weather widget is gone.
D/UpdateThreadPoolManager( 7581): 2 : This is isUpdating : false
,D/WeatherAncestor( 7581): connectivity changed - connection : true
D/WeatherService( 7581): 2 : isServiceAlived():false forecastCache:null
D/ForecastDataCache( 7581): 2 : lastUpdatedTime: 1430558561343
D/ForecastDataCache( 7581): 2 : currentPackageVersion: 4.40.4
D/ForecastDataCache( 7581): 2 : Cache is not up-to-date, count: 0
,D/Weather_cast( 7581): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherAncestor( 7581): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 23:8:27
,I/ActivityManager( 1030): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7602 uid=10093 gids={50093, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager( 1030): Killing 6794:com.google.android.apps.plus/u0a97 (adj 15): empty #17
,W/libprocessgroup( 1030): failed to open /acct/uid_10097/pid_6794/cgroup.procs: No such file or directory
,E/VoldCmdListener(  278): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  278): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7602): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
E/VoldCmdListener(  278): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  278): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7602): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
E/VoldCmdListener(  278): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  278): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7602): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
,E/VoldCmdListener(  278): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  278): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7602): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
,I/art     ( 1030): Explicit concurrent mark sweep GC freed 99202(4MB) AllocSpace objects, 6(608KB) LOS objects, 33% free, 44MB/67MB, paused 2.433ms total 170.255ms
,I/WebViewFactory( 7602): Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,I/LibraryLoader( 7602): Loading: webviewchromium
I/LibraryLoader( 7602): Time to load native libraries: 3 ms (timestamps 543-546)
I/LibraryLoader( 7602): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 7602): Binding Chromium to main looper Looper (main, tid 1) {2a93484}
,I/LibraryLoader( 7602): Expected native library version number "",actual native library version number ""
I/chromium( 7602): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 7602): Initializing chromium process, renderers=0
W/art     ( 7602): Attempt to remove local handle scope entry from IRT, ignoring
,W/chromium( 7602): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
I/chromium( 7602): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=38 off=46780 len=2953
I/chromium( 7602): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:39 off:229536 len:643667
V/AudioPolicyService(  316): registerClient() client 0xb1427e00, uid 10093
,W/AudioManagerAndroid( 7602): Requires BLUETOOTH permission
I/Adreno-EGL( 7602): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 7602): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 7602): Build Date: 12/12/14 금
I/Adreno-EGL( 7602): Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
I/Adreno-EGL( 7602): Remote Branch: 
I/Adreno-EGL( 7602): Local Patches: 
I/Adreno-EGL( 7602): Reconstruct Branch: 
,I/NSApplication( 7602): Starting up...
,I/ActivityManager( 1030): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=7657 uid=10097 gids={50097, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager( 1030): Killing 7158:com.google.android.gms:car/u0a5 (adj 15): empty #17
W/libprocessgroup( 1030): failed to open /acct/uid_10005/pid_7158/cgroup.procs: No such file or directory
,W/ResourcesManager( 7657): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/iu.Environment( 2327): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,I/iu.UploadsManager( 2327): num queued entries: 0
I/iu.UploadsManager( 2327): num updated entries: 0
I/iu.SyncManager( 2327): NEXT; no task
D/ChimeraCfgMgr( 2327): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/PostponalbeReceiver( 7364): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
W/ContextImpl( 7364): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
,I/NetworkStateForAutoUpdateMonitor( 7040): [onReceive] BroadcastReceiver onReceive
,I/NetworkStateForAutoUpdateMonitor( 7040): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 7040): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 7040): [onReceive] request level :IDLE....
I/AppUp4:CustModeStarterReceiver( 7040): onReceive
,I/GLSActivity( 2125): [ac] getting account id
D/AppUp4:CustFacade( 7040): Context : android.app.ReceiverRestrictedContext@1d2083bc
D/AppUp4:CustFacade( 7040): isCustomizationCompleted : false
D/AppUp4:CustFacade( 7040): isPhone : true
D/AppUp4:CustModeStarterReceiver( 7040): begin check event
I/AppUp4:CustModeStarterReceiver( 7040): Event For GoodConnectivity, noConnectivity : false, but skip! 
I/wpa_supplicant( 7492): wlan0: CTRL-EVENT-SCAN-STARTED 
,D/WifiMonitor( 1030): Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1030): WifiMonitor:wlan0 cnt=39 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1030): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1030): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
D/LGDMClient( 3941): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMClient( 3941): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
I/GLSUser ( 2125): [t] Fetched account id for thalitester@gmail.com : 105256135866144380227
W/ContextImpl( 3941): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
W/ContextImpl( 3941): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
D/eas_req ( 7513): ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
,D/LGDMClient( 3941): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=3, isUserType=1
D/LGDMClient( 3941): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 3941): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
I/LgeMiscReceiver( 3261): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
,I/LgeMiscReceiver( 3261): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 3261): networkInfo.isConnected() = false
W/Settings( 7513): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/FormManager( 7444): Network not available. Please check & try again.
D/WeatherAncestor( 7581): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 23:8:28
,D/Weather.Utils( 7581): 2 : the weather widgets(using time tick) are gone.
D/Weather.Utils( 7581): 2 : All the weather widget is gone.
D/UpdateThreadPoolManager( 7581): 2 : This is isUpdating : false
D/WeatherAncestor( 7581): connectivity changed - connection : true
D/WeatherService( 7581): 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@10b2dac1
D/ForecastDataCache( 7581): 2 : lastUpdatedTime: 1430558561343
D/ForecastDataCache( 7581): 2 : currentPackageVersion: 4.40.4
V/FormManager( 7444): Network unavailable.
D/ForecastDataCache( 7581): 2 : Cache is up-to-date, count: 0
D/Weather_cast( 7581): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherAncestor( 7581): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 23:8:28
V/FormManager( 7444): Network unavailable.
,I/jxcore-log( 6121): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6121): 
I/jxcore-log( 6121): Error type "connect_error" when connecting to the test server
I/jxcore-log( 6121): 
I/chromium( 6121): [INFO:CONSOLE(63)] "logCallback Error type "connect_error" when connecting to the test server", source: file:///android_asset/www/js/thali_main.js (63)
D/ChimeraCfgMgr( 2327): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/UsbSettingsReceiver( 7322): [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
D/UsbSettingsReceiver( 7322): [AUTORUN] sys.usb.config = ptp_only,adb
D/UsbSettingsReceiver( 7322): [AUTORUN] sys.usb.state = ptp_only,adb
D/UsbSettingsReceiver( 7322): [AUTORUN] persist.sys.usb.config = ptp_only,adb
D/UsbSettingsReceiver( 7322): [AUTORUN] onReceive() : app userid = 0, current userid = 0
D/UsbSettingsControl( 7322): [AUTORUN] getUsbConnected() : connected=true
D/UsbSettingsReceiver( 7322): [AUTORUN] onReceive() : availableList=[]
D/UsbSettingsReceiver( 7322): [AUTORUN] onReceive() : activeList=[]
D/UsbSettingsReceiver( 7322): [AUTORUN] onReceive() : errorList=[]
D/UsbSettingsControl( 7322): [AUTORUN] isAutorunTimer() : mAutorunChanging=false
D/UsbSettingsControl( 7322): [AUTORUN] setTetherStatus() : status=false
D/PCSuite ( 7399): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,V/WiFiOffLoadBroadcast( 7322): WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
W/FormManager( 7444): Network not available. Please check & try again.
,V/FormManager( 7444): Network unavailable.
,D/WiFiOffLoadBroadcast( 7322): MCCMNC not supported: null
V/FormManager( 7444): Network unavailable.
D/PCSuite ( 7399): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,V/WiFiOffLoadBroadcast( 7322): WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
D/WiFiOffLoadBroadcast( 7322): MCCMNC not supported: null
D/LGDMClient( 3941): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
D/LGDMClient( 3941): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
W/FormManager( 7444): Network not available. Please check & try again.
W/ContextImpl( 3941): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,W/ContextImpl( 3941): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
V/FormManager( 7444): Network unavailable.
D/LGDMClient( 3941): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=3, isUserType=1
,D/LGDMClient( 3941): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
D/LGDMClient( 3941): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
,I/ActivityManager( 1030): Start proc com.lge.bnr for broadcast com.lge.bnr/.service.BNRBootReceiver: pid=7722 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi
,V/FormManager( 7444): Network unavailable.
,V/[BNRBootReceiver]( 7722): boot receiver action = android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,D/BNRAndroBeam( 7722): [BnR DirectBeam] Android Direct Beam(NFC) Connection changed
,V/[BNRBootReceiver]( 7722): Boot Receiver Return
,D/PostponalbeReceiver( 7364): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
V/WiFiOffLoadBroadcast( 7322): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 7322): MCCMNC not supported: null
D/QRemote ( 6386): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6386): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 6386): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
D/PostponalbeReceiver( 7364): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,V/WiFiOffLoadBroadcast( 7322): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 7322): MCCMNC not supported: null
D/LGWifiP2pService( 1030): InactiveState{ when=-1ms what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1030): P2pEnabledState{ when=-1ms what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1030): DefaultState{ when=-1ms what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
,D/QRemote ( 6386): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6386): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 6386): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
V/WiFiOffLoadBroadcast( 7322): WiFiOffLoadBroadcast: android.net.wifi.SCAN_RESULTS
,D/WiFiOffLoadBroadcast( 7322): Not supported operator for automatic switch
I/ActivityManager( 1030): Killing 7192:com.google.android.gms.wearable/u0a5 (adj 15): empty #17
E/WifiStateMachine( 1030):  DisconnectedState CMD_STOP_SUPPLICANT_FAILED 1 0
E/WifiStateMachine( 1030):  ConnectModeState CMD_STOP_SUPPLICANT_FAILED 1 0
E/WifiStateMachine( 1030):  DriverStartedState CMD_STOP_SUPPLICANT_FAILED 1 0
E/WifiStateMachine( 1030):  SupplicantStartedState CMD_STOP_SUPPLICANT_FAILED 1 0
E/WifiStateMachine( 1030):  DefaultState CMD_STOP_SUPPLICANT_FAILED 1 0
,W/libprocessgroup( 1030): failed to open /acct/uid_10005/pid_7192/cgroup.procs: No such file or directory
,I/wpa_supplicant( 7492): [LGE_PATCH]scan interval[1] = 3 sec.
,E/WifiMonitor( 1030): WifiMonitor:wlan0 cnt=40 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
E/WifiMonitor( 1030): handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
D/WifiMonitor( 1030): Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
E/WifiMonitor( 1030): WifiMonitor:wlan0 cnt=41 dispatchEvent: WPS-AP-AVAILABLE 
W/WifiMonitor( 1030): couldn't identify event type - WPS-AP-AVAILABLE 
E/WifiMonitor( 1030): WifiMonitor:p2p0 cnt=42 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
E/WifiMonitor( 1030): handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
D/LGWifiP2pService( 1030): InactiveState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1030): P2pEnabledState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1030): DefaultState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiMonitor( 1030): Event [IFNAME=p2p0 WPS-AP-AVAILABLE ]
E/WifiMonitor( 1030): WifiMonitor:p2p0 cnt=43 dispatchEvent: WPS-AP-AVAILABLE 
W/WifiMonitor( 1030): couldn't identify event type - WPS-AP-AVAILABLE 
E/WifiStateMachine( 1030):  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=1 known=0 got=1 bcn=0
E/WifiStateMachine( 1030):  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=1 known=0 got=1 bcn=0
E/WifiStateMachine( 1030):  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=1 known=0 got=1 bcn=0
E/WifiStateMachine( 1030):  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=1 known=0 got=1 bcn=0
D/WifiNative-wlan0( 1030): doString: [BSS RANGE=0- MASK=0x21987]
,D/WfdsMonitor( 1950): Event [CTRL-EVENT-SCAN-RESULTS ]
,D/WfdsMonitor( 1950): Event [WPS-AP-AVAILABLE ]
E/WifiStateMachine( 1030):  DisconnectedState CMD_START_SCAN -2 -2 ic=1 proc(ms):4 rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 fiv=20000 [on:0 tx:0 rx:0 period:7464] from screen [on:0 period:1603732173]
E/WifiStateMachine( 1030):  ConnectModeState CMD_START_SCAN -2 -2 ic=1 proc(ms):7 rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 fiv=20000 [on:0 tx:0 rx:0 period:2] from screen [on:0 period:1603732175]
,V/AlarmManager( 1030): RTC_WAKEUP set : Alarm{34f77bff type 0 when 1449007706589 android} when 1449007706589
V/AlarmManager( 1030): ELAPSED_WAKEUP set : Alarm{1b61adcc type 2 when 433322 com.google.android.gms} when 433322
E/WifiStateMachine( 1030):  DriverStartedState CMD_START_SCAN -2 -2 ic=1 proc(ms):30 rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 fiv=20000 [on:0 tx:0 rx:0 period:23] from screen [on:0 period:1603732198]
D/WifiNative-wlan0( 1030): doBoolean: SCAN
I/wpa_supplicant( 7492): wlan0: CTRL-EVENT-SCAN-STARTED 
,D/WifiMonitor( 1030): Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1030): WifiMonitor:wlan0 cnt=44 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1030): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1030): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
D/libc-netbsd(  311): default dns: query_ipv6=0, query_ipv4=0
D/DSQN    ( 1030): DNSproblemNotiEnabled is disabled ignore DNS fail CB
D/WifiNative-wlan0( 1030): SCAN: returned true
,V/AlarmManager( 1030): ELAPSED_WAKEUP set : Alarm{23535815 type 2 when 433462 android} when 433462
,V/AlarmManager( 1030): RTC_WAKEUP set : Alarm{1b51d91b type 0 when 1449007711173 com.android.vending} when 1449007711173
,V/SIM_STK ( 1030): Menu title from STK is T-Mobile
,V/GLSActivity( 2125): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2125): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 2125): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2125): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2125): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2125): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/Finsky  ( 7119): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 7119): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 7119): [1] 5.onFinished: Scheduling replication attempt 4.
,I/GAV4    ( 7602): Thread[GAThread,5,main]: No campaign data found.
,E/wpa_supplicant( 7492): USIM:  scard_init function
I/wpa_supplicant( 7492): Trying to associate with SSID 'NG700'
,E/WifiMonitor( 1030): WifiMonitor:wlan0 cnt=45 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
E/WifiMonitor( 1030): handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
D/WifiMonitor( 1030): Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
E/WifiMonitor( 1030): WifiMonitor:wlan0 cnt=46 dispatchEvent: WPS-AP-AVAILABLE 
W/WifiMonitor( 1030): couldn't identify event type - WPS-AP-AVAILABLE 
D/WifiMonitor( 1030): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
E/WifiMonitor( 1030): WifiMonitor:wlan0 cnt=47 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
E/WifiStateMachine( 1030):  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=1 known=0 got=1 bcn=0
E/WifiStateMachine( 1030):  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=1 known=0 got=1 bcn=0
E/WifiStateMachine( 1030):  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=1 known=0 got=1 bcn=0
E/WifiStateMachine( 1030):  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=1 known=0 got=1 bcn=0
D/WifiNative-wlan0( 1030): doString: [BSS RANGE=0- MASK=0x21987]
E/WifiStateMachine( 1030):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 47 0 rt=435452  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
,W/Settings( 1030): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1030): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1030): NETWORK_STATE_CHANGED_ACTION [CONNECTING]
I/StatusBar.NetworkController( 1446): networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1446): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1446): refreshViews: Data not connected!! Set no data type icon / Roaming
E/WifiStateMachine( 1030):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 47 0 rt=435467  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
,D/WifiServerServiceExt( 1030): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1030): setSupplicantStateASSOCIATING
V/WiFiOffLoadBroadcast( 7322): WiFiOffLoadBroadcast: android.net.wifi.SCAN_RESULTS
D/WiFiOffLoadBroadcast( 7322): Not supported operator for automatic switch
D/PostponalbeReceiver( 7364): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,V/WiFiOffLoadBroadcast( 7322): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 7322): MCCMNC not supported: null
D/QRemote ( 6386): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,D/QRemote ( 6386): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 6386): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
I/ActivityManager( 1030): Killing 6562:com.google.android.apps.books/u0a54 (adj 15): empty #17
,W/libprocessgroup( 1030): failed to open /acct/uid_10054/pid_6562/cgroup.procs: No such file or directory
,I/jxcore-log( 6121): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6121): 
I/jxcore-log( 6121): Error type "connect_error" when connecting to the test server
I/jxcore-log( 6121): 
,I/chromium( 6121): [INFO:CONSOLE(63)] "logCallback Error type "connect_error" when connecting to the test server", source: file:///android_asset/www/js/thali_main.js (63)
I/wpa_supplicant( 7492): wlan0: CTRL-EVENT-ASSOC-REJECT bssid=c0:ff:d4:d3:aa:48 status_code=1
,D/WifiMonitor( 1030): Event [IFNAME=wlan0 CTRL-EVENT-ASSOC-REJECT bssid=c0:ff:d4:d3:aa:48 status_code=1]
E/WifiMonitor( 1030): WifiMonitor:wlan0 cnt=48 dispatchEvent: CTRL-EVENT-ASSOC-REJECT bssid=c0:ff:d4:d3:aa:48 status_code=1
D/WifiMonitor( 1030): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=00:00:00:00:00:00 SSID=NG700]
E/WifiMonitor( 1030): WifiMonitor:wlan0 cnt=49 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=00:00:00:00:00:00 SSID=NG700
E/WifiStateMachine( 1030):  DisconnectedState ASSOCIATION_REJECTION_EVENT 48 1 c0:ff:d4:d3:aa:48 blacklist=false rt=437477
E/WifiStateMachine( 1030):  ConnectModeState ASSOCIATION_REJECTION_EVENT 48 1 c0:ff:d4:d3:aa:48 blacklist=false rt=437477
E/WifiStateMachine( 1030):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 49 0 rt=437478  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: DISCONNECTED
,D/WifiHS20( 1030): hidePasspointNotification off =false
W/Settings( 1030): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1030): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1030): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
I/StatusBar.NetworkController( 1446): networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1446): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1446): refreshViews: Data not connected!! Set no data type icon / Roaming
,E/WifiStateMachine( 1030):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 49 0 rt=437496  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: DISCONNECTED
D/WifiServerServiceExt( 1030): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1030): setSupplicantStateDISCONNECTED
D/PostponalbeReceiver( 7364): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
I/PCSuite ( 7399): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 7399): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 7399): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,V/WiFiOffLoadBroadcast( 7322): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 7322): MCCMNC not supported: null
D/QRemote ( 6386): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6386): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 6386): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
I/wpa_supplicant( 7492): wlan0: CTRL-EVENT-SCAN-STARTED 
,D/WifiMonitor( 1030): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
E/WifiMonitor( 1030): WifiMonitor:wlan0 cnt=50 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
D/WifiMonitor( 1030): Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1030): WifiMonitor:wlan0 cnt=51 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1030): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1030): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
E/WifiStateMachine( 1030):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 50 0 rt=437563  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
D/WifiHS20( 1030): hidePasspointNotification off =false
W/Settings( 1030): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1030): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1030): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
I/StatusBar.NetworkController( 1446): networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1446): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1446): refreshViews: Data not connected!! Set no data type icon / Roaming
,E/WifiStateMachine( 1030):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 50 0 rt=437579  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
I/StatusBar.NetworkController( 1446): networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1446): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1446): refreshViews: Data not connected!! Set no data type icon / Roaming
,W/Settings( 1030): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1030): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1030): NETWORK_STATE_CHANGED_ACTION [SCANNING]
D/WifiServerServiceExt( 1030): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1030): setSupplicantStateSCANNING
D/PostponalbeReceiver( 7364): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
I/PCSuite ( 7399): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 7399): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 7399): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,V/WiFiOffLoadBroadcast( 7322): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 7322): MCCMNC not supported: null
D/QRemote ( 6386): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6386): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 6386): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
D/PostponalbeReceiver( 7364): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
V/WiFiOffLoadBroadcast( 7322): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 7322): MCCMNC not supported: null
D/QRemote ( 6386): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6386): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 6386): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
I/wpa_supplicant( 7492): Trying to associate with SSID 'NG700'
,E/WifiMonitor( 1030): WifiMonitor:wlan0 cnt=52 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
E/WifiMonitor( 1030): handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
D/WifiMonitor( 1030): Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
E/WifiMonitor( 1030): WifiMonitor:wlan0 cnt=53 dispatchEvent: WPS-AP-AVAILABLE 
W/WifiMonitor( 1030): couldn't identify event type - WPS-AP-AVAILABLE 
D/WifiMonitor( 1030): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
E/WifiMonitor( 1030): WifiMonitor:wlan0 cnt=54 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
E/WifiStateMachine( 1030):  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=2 known=0 got=2 dur:2070 bcn=0
E/WifiStateMachine( 1030):  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=2 known=0 got=2 dur:2070 bcn=0
E/WifiStateMachine( 1030):  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=2 known=0 got=2 dur:2070 bcn=0
E/WifiStateMachine( 1030):  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=2 known=0 got=2 dur:2070 bcn=0
D/WifiNative-wlan0( 1030): doString: [BSS RANGE=0- MASK=0x21987]
E/WifiStateMachine( 1030):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 54 0 rt=439641  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
,I/StatusBar.NetworkController( 1446): networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1446): mWifiConnected = false, mWifiLevel = 0
W/Settings( 1030): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1030): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1030): NETWORK_STATE_CHANGED_ACTION [SCANNING]
D/StatusBar.NetworkController( 1446): refreshViews: Data not connected!! Set no data type icon / Roaming
,W/Settings( 1030): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1030): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1030): NETWORK_STATE_CHANGED_ACTION [CONNECTING]
E/WifiStateMachine( 1030):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 54 0 rt=439669  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
,D/WifiServerServiceExt( 1030): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1030): setSupplicantStateASSOCIATING
I/StatusBar.NetworkController( 1446): networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1446): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1446): refreshViews: Data not connected!! Set no data type icon / Roaming
D/PostponalbeReceiver( 7364): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
V/WiFiOffLoadBroadcast( 7322): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 7322): MCCMNC not supported: null
D/QRemote ( 6386): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,D/QRemote ( 6386): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 6386): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
D/PostponalbeReceiver( 7364): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
V/WiFiOffLoadBroadcast( 7322): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 7322): MCCMNC not supported: null
D/QRemote ( 6386): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6386): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 6386): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,I/wpa_supplicant( 7492): wlan0: Associated with c0:ff:d4:d3:aa:48
,D/WifiMonitor( 1030): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
E/WifiMonitor( 1030): WifiMonitor:wlan0 cnt=55 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
D/WifiMonitor( 1030): Event [IFNAME=wlan0 Associated with c0:ff:d4:d3:aa:48]
E/WifiMonitor( 1030): WifiMonitor:wlan0 cnt=56 dispatchEvent: Associated with c0:ff:d4:d3:aa:48
D/WifiMonitor( 1030): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1030): WifiMonitor:wlan0 cnt=57 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
I/wpa_supplicant( 7492): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 7492): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
E/WifiStateMachine( 1030):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 55 0 rt=439778  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
E/WifiStateMachine( 1030):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 55 0 rt=439779  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
D/WifiMonitor( 1030): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1030): WifiMonitor:wlan0 cnt=58 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/WifiMonitor( 1030): Event [IFNAME=wlan0 WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]]
E/WifiMonitor( 1030): WifiMonitor:wlan0 cnt=59 dispatchEvent: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
W/WifiMonitor( 1030): couldn't identify event type - WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
,D/WifiMonitor( 1030): Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]]
E/WifiMonitor( 1030): WifiMonitor:wlan0 cnt=60 dispatchEvent: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
E/WifiMonitor( 1030): handleEvent 1  Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
D/WifiMonitor( 1030): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1030): WifiMonitor:wlan0 cnt=61 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
E/WifiStateMachine( 1030):  DisconnectedState CMD_ASSOCIATED_BSSID 56 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=439787
E/WifiStateMachine( 1030):  ConnectModeState CMD_ASSOCIATED_BSSID 56 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=439788
D/Tethering( 1030): sendTetherStateChangedBroadcast 1, 0, 0
E/WifiStateMachine( 1030):  DriverStartedState CMD_ASSOCIATED_BSSID 56 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=439797
E/WifiStateMachine( 1030):  SupplicantStartedState CMD_ASSOCIATED_BSSID 56 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=439797
,E/WifiStateMachine( 1030):  DefaultState CMD_ASSOCIATED_BSSID 56 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=439801
E/WifiStateMachine( 1030):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 57 0 rt=439801  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: FOUR_WAY_HANDSHAKE
W/Settings( 1030): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1030): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1030): NETWORK_STATE_CHANGED_ACTION [CONNECTING]
I/StatusBar.NetworkController( 1446): networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1446): mWifiConnected = false, mWifiLevel = 0
,D/StatusBar.NetworkController( 1446): refreshViews: Data not connected!! Set no data type icon / Roaming
I/StatusBar.NetworkController( 1446): networkInfo=[type: WIFI[], state: CONNECTING/AUTHENTICATING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1446): mWifiConnected = false, mWifiLevel = 0
W/Settings( 1030): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1030): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1030): NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
D/StatusBar.NetworkController( 1446): refreshViews: Data not connected!! Set no data type icon / Roaming
E/WifiStateMachine( 1030):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 57 0 rt=439822  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: FOUR_WAY_HANDSHAKE
,D/WifiServerServiceExt( 1030): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1030): setSupplicantStateASSOCIATED
E/WifiStateMachine( 1030):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 58 0 rt=439827  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: GROUP_HANDSHAKE
E/WifiStateMachine( 1030):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 58 0 rt=439827  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: GROUP_HANDSHAKE
E/WifiStateMachine( 1030):  DisconnectedState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=439828
E/WifiStateMachine( 1030):  ConnectModeState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=439829
D/WifiNative-wlan0( 1030): doString: [STATUS]
D/WifiMonitor( 1030): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1030): WifiMonitor:wlan0 cnt=62 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/WifiNative-wlan0( 1030):    returned bssid=c0:ff:d4:d3:aa:48 ssid=NG700 id=0 mode=station pairwise_cipher=CCMP group_cipher=CCMP key_mgmt=WPA2-PSK wpa_state=COMPLETED p2p_device_address=02:9a:02:7b:60:ac address=c4:9a:02:7b:60:ac uuid=530d3fd0-1ba3-5409-a336-ff4e42af59a2
I/WifiServiceExtension( 1030): setVHTCapabilityType  : false
D/UsbSettingsReceiver( 7322): [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
D/UsbSettingsReceiver( 7322): [AUTORUN] sys.usb.config = ptp_only,adb
D/UsbSettingsReceiver( 7322): [AUTORUN] sys.usb.state = ptp_only,adb
,D/UsbSettingsReceiver( 7322): [AUTORUN] persist.sys.usb.config = ptp_only,adb
,D/UsbSettingsReceiver( 7322): [AUTORUN] onReceive() : app userid = 0, current userid = 0
D/UsbSettingsControl( 7322): [AUTORUN] getUsbConnected() : connected=true
D/UsbSettingsReceiver( 7322): [AUTORUN] onReceive() : availableList=[wlan0]
D/UsbSettingsReceiver( 7322): [AUTORUN] onReceive() : activeList=[]
D/UsbSettingsReceiver( 7322): [AUTORUN] onReceive() : errorList=[]
D/UsbSettingsControl( 7322): [AUTORUN] isAutorunTimer() : mAutorunChanging=false
D/UsbSettingsReceiver( 7322): [AUTORUN] onReceive() : TetherState Changed=wlan0
D/UsbSettingsControl( 7322): [AUTORUN] setTetherStatus() : status=false
I/WifiServerServiceExt( 1030): wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
I/WifiServerServiceExt( 1030): setKeepAlivePacketInterval msec : 60
W/Settings( 1030): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1030): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1030): NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
,I/StatusBar.NetworkController( 1446): networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1446): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1446): refreshViews: Data not connected!! Set no data type icon / Roaming
W/Settings( 1030): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1030): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1030): NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
I/StatusBar.NetworkController( 1446): networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1446): mWifiConnected = false, mWifiLevel = 0
,D/StatusBar.NetworkController( 1446): refreshViews: Data not connected!! Set no data type icon / Roaming
D/PostponalbeReceiver( 7364): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,D/ConnectivityService( 1030): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
E/WifiConfigStore( 1030): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/WifiNative-wlan0( 1030): doBoolean: SET_NETWORK 0 bssid any
D/WifiNative-wlan0( 1030): SET_NETWORK 0 bssid any: returned true
D/WifiNative-wlan0( 1030): doBoolean: SAVE_CONFIG
V/WiFiOffLoadBroadcast( 7322): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/ConnectivityService( 1030): Got NetworkAgent Messenger
D/ConnectivityService( 1030): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
D/ConnectivityService( 1030): NetworkAgent connected
D/WiFiOffLoadBroadcast( 7322): MCCMNC not supported: null
,D/WifiNative-wlan0( 1030): SAVE_CONFIG: returned true
E/WifiConfigStore( 1030): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/WifiNative-wlan0( 1030): doBoolean: SET_NETWORK 0 bssid any
D/QRemote ( 6386): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6386): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
D/WifiNative-wlan0( 1030): SET_NETWORK 0 bssid any: returned true
D/WifiNative-wlan0( 1030): doBoolean: SAVE_CONFIG
I/QRemote ( 6386): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
D/PostponalbeReceiver( 7364): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
D/WifiNative-wlan0( 1030): SAVE_CONFIG: returned true
,D/CommandListener(  311): Setting iface cfg
V/WiFiOffLoadBroadcast( 7322): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/DhcpStateMachine( 1030): StoppedState
E/WifiStateMachine( 1030): Start Dhcp Watchdog 2
D/DhcpStateMachine( 1030): StoppedState{ when=0 what=196609 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine( 1030): WaitBeforeStartState
E/WifiStateMachine( 1030):  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 61 0 rt=439924  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
D/WiFiOffLoadBroadcast( 7322): MCCMNC not supported: null
E/WifiStateMachine( 1030):  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 61 0 rt=439925  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine( 1030):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 61 0 rt=439926  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine( 1030):  ObtainingIpState CMD_TETHER_STATE_CHANGE 0 0
,E/WifiStateMachine( 1030):  L2ConnectedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1030):  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
D/QRemote ( 6386): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6386): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 6386): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
E/WifiStateMachine( 1030):  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1030):  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
D/PostponalbeReceiver( 7364): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
E/WifiStateMachine( 1030):  DefaultState CMD_TETHER_STATE_CHANGE 0 0
D/WifiServerServiceExt( 1030): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1030): setSupplicantStateGROUP_HANDSHAKE
E/WifiStateMachine( 1030):  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 62 0 rt=439939  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine( 1030):  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 62 0 rt=439939  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine( 1030):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 62 0 rt=439940  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
,E/WifiStateMachine( 1030):  ObtainingIpState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:6571] from screen [on:0 period:1603738781] gl rssi=-55 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
V/WiFiOffLoadBroadcast( 7322): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:1603738782] gl rssi=-55 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
D/StatusBar.NetworkController( 1446): refreshViews: Data not connected!! Set no data type icon / Roaming
D/ConnectivityService( 1030): updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
D/WiFiOffLoadBroadcast( 7322): MCCMNC not supported: null
E/WifiStateMachine( 1030):  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1030):  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1030):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1030):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1030):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1030):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
D/ConnectivityService( 1030): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
E/WifiStateMachine( 1030):  ObtainingIpState CMD_PRE_DHCP_ACTION 0 0 txpkts=148,0,0
E/WifiStateMachine( 1030):  L2ConnectedState CMD_PRE_DHCP_ACTION 0 0 txpkts=148,0,0
D/WifiNative-wlan0( 1030): doBoolean: DRIVER SETSUSPENDMODE 0
I/wpa_supplicant( 7492): wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 0
D/WifiNative-wlan0( 1030): DRIVER SETSUSPENDMODE 0: returned true
D/WifiNative-wlan0( 1030): doBoolean: SET ps 0
D/WifiNative-wlan0( 1030): SET ps 0: returned true
D/WifiNative-wlan0( 1030): doBoolean: DRIVER BTCOEXMODE 1
I/wpa_supplicant( 7492): wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 1
,D/WifiNative-wlan0( 1030): DRIVER BTCOEXMODE 1: returned true
E/WifiStateMachine( 1030): CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
V/DhcpStateMachine( 1030): Current State is mWaitBeforeStartState.
D/QRemote ( 6386): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
V/LgDhcpStateMachineHelper( 1030): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
D/QRemote ( 6386): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
D/LGWifiP2pService( 1030): InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@7f704cf target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1030): P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@7f704cf target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine( 1030): WaitBeforeStartState{ when=0 what=196615 target=com.android.internal.util.StateMachine$SmHandler }
I/QRemote ( 6386): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
D/DhcpStateMachine( 1030): DHCP Start wake lock is acquired.
D/CommandListener(  311): Setting iface cfg
D/CommandListener(  311): Trying to bring up wlan0
V/LgDhcpStateMachineHelper( 1030): setInterfaceUpWithDhcpInfo: IP configuration succeeded: IP address 192.168.1.122/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 86400 seconds
D/PostponalbeReceiver( 7364): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
D/WifiServerServiceExt( 1030): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1030): setSupplicantStateCOMPLETED
V/WiFiOffLoadBroadcast( 7322): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,E/WifiStateMachine( 1030):  ObtainingIpState CMD_POST_DHCP_ACTION 1 0 OK 
D/WifiServerServiceExt( 1030): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1030): setSupplicantStateCOMPLETED
E/WifiStateMachine( 1030):  L2ConnectedState CMD_POST_DHCP_ACTION 1 0 OK 
D/WifiNative-wlan0( 1030): doBoolean: DRIVER BTCOEXMODE 2
D/LGWifiP2pService( 1030): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1030): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 7492): wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
D/WifiNative-wlan0( 1030): DRIVER BTCOEXMODE 2: returned true
D/WifiNative-wlan0( 1030): doBoolean: DRIVER SETSUSPENDMODE 1
,I/wpa_supplicant( 7492): wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 1
D/WifiNative-wlan0( 1030): DRIVER SETSUSPENDMODE 1: returned true
D/WifiNative-wlan0( 1030): doBoolean: SET ps 1
D/WifiNative-wlan0( 1030): SET ps 1: returned true
D/ConnectivityService( 1030): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
E/WifiStateMachine( 1030):  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
E/WifiStateMachine( 1030):  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
E/WifiStateMachine( 1030):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
E/WifiStateMachine( 1030):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
E/WifiStateMachine( 1030):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
E/WifiStateMachine( 1030):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
D/ConnectivityService( 1030): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
E/WifiStateMachine( 1030):  ObtainingIpState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
E/WifiStateMachine( 1030):  L2ConnectedState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
E/WifiStateMachine( 1030): WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
D/WiFiOffLoadBroadcast( 7322): MCCMNC not supported: null
D/ConnectivityService( 1030): ignoring duplicate network state non-change
D/ConnectivityService( 1030): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,D/ConnectivityService( 1030): Adding iface wlan0 to network 101
I/StatusBar.NetworkController( 1446): networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1446): mWifiConnected = false, mWifiLevel = 0
W/Settings( 1030): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1030): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1030): NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
D/StatusBar.NetworkController( 1446): refreshViews: Data not connected!! Set no data type icon / Roaming
I/StatusBar.NetworkController( 1446): networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1446): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1446): refreshViews: Data not connected!! Set no data type icon / Roaming
W/Settings( 1030): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1030): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1030): NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
D/QRemote ( 6386): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6386): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 6386): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,E/WifiStateMachine( 1030): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
D/WifiHS20( 1030): [PASSPOINT] passpointNotification: hs20AP list is checked
V/WfdStateTracker( 1950): handleWifiStateChangedEvent: 1
,I/StatusBar.NetworkController( 1446): networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/StatusBar.NetworkController( 1446): mWifiConnected = true, mWifiLevel = 2
W/Settings( 1030): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/StatusBar.NetworkController( 1446): refreshViews: Data not connected!! Set no data type icon / Roaming
W/Settings( 1030): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1030): NETWORK_STATE_CHANGED_ACTION [CONNECTED]
D/WifiHS20( 1030): [PASSPOINT] passpointNotification: hs20AP list is checked
W/Settings( 1030): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1030): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1030): NETWORK_STATE_CHANGED_ACTION [CONNECTED]
E/ConnectivityService( 1030): Unexpected mtu value: 0, wlan0
D/ConnectivityService( 1030): Adding Route [fe80::/64 -> :: wlan0] to network 101
,D/ConnectivityService( 1030): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,E/Netd    (  311): netlink response contains error (File exists)
D/PostponalbeReceiver( 7364): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
D/ConnectivityService( 1030): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
D/ConnectivityService( 1030): addLocalRoutetoDefaultNetwork
D/ConnectivityService( 1030): defaultNAI is null or Wi-Fi no need to add Loacal route to default network. WiFi netid = 101
D/ConnectivityService( 1030): Setting Dns servers for network 101 to [/192.168.1.1]
D/Nat464Xlat( 1030): requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
D/ConnectivityService( 1030): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1030): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1030): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1030):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1030): DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1030): Connected
D/ConnectivityService( 1030):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1030):     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1030): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService( 1030):   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1030): Checking http://clients3.google.com/generate_204 on "NG700"
D/ConnectivityService( 1030):     satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:true
D/ConnectivityService( 1030): currentScore = 0, newScore = 20
D/ConnectivityService( 1030):    accepting network in place of null
D/ConnectivityService( 1030): sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    ( 1030): new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    ( 1030):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
I/StatusBar.NetworkController( 1446): networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1446): mWifiConnected = true, mWifiLevel = 2
D/StatusBar.NetworkController( 1446): refreshViews: Data not connected!! Set no data type icon / Roaming
E/ConnectivityService( 1030): [lg_data] Adding agent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.122/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
D/CSLegacyTypeTracker( 1030): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
D/ConnectivityService( 1030): ,sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService( 1030): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/CSLegacyTypeTracker( 1030): [e] list.add(nai) empty : false size: 1
D/TelephonyNetworkFactory-1( 1855): new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/libc-netbsd(  311): res_queryN name = clients3.google.com, class = 1, type = 28
D/TelephonyNetworkFactory-1( 1855):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
D/ConnectivityService( 1030): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.122/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
D/ConnectivityService( 1030): validation of new default Network = false
D/ConnectivityService( 1030): Default network via Wi-Fi connected. start DSQN
D/DSQN    ( 1030): enableDataServiceNotify 
D/DSQN    ( 1030): start dsqn bin
D/LocSvc_java( 1030): Sending msg: 4 arg1:1 arg2:1
,D/LocSvc_java( 1030): getAGpsConnectionInfo connType - 4
D/LocSvc_java( 1030): updateNetworkState connTyp: 4 available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java( 1030): ignore wifi update if we are not in OPENING or CLOSING
D/ConnectivityService( 1030): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1030):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1030):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
V/WiFiOffLoadBroadcast( 7322): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/ConnectivityService( 1030): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityManager.CallbackHandler( 1446): CM callback handler got msg 524290
W/dsqn    ( 7816): type=1400 audit(0.0:167): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
W/dsqn    ( 7816): type=1400 audit(0.0:168): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
D/WiFiOffLoadBroadcast( 7322): MCCMNC not supported: null
,E/DSQN    ( 7816): DSQN ssw
D/QRemote ( 6386): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6386): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 6386): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
D/PostponalbeReceiver( 7364): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
V/NetworkPolicy( 1030): [LG_RESTRICTED] checkMobilePolicy_type()
,D/TelephonyIcons( 1446): null signal icon name: drawable/stat_sys_signal_null
D/StatusBar.NetworkController( 1446): refreshViews: Data not connected!! Set no data type icon / Roaming
D/StatusBar.NetworkController( 1446): refreshViews: Data not connected!! Set no data type icon / Roaming
V/WiFiOffLoadBroadcast( 7322): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 7322): MCCMNC not supported: null
D/QRemote ( 6386): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6386): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 6386): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,D/PostponalbeReceiver( 7364): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
I/PCSuite ( 7399): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
D/PCSuite ( 7399): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 7322): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 7322): MCCMNC not supported: null
,D/QRemote ( 6386): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6386): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
D/QRemote ( 6386): [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
I/QRemote ( 6386): [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
I/QRemote ( 6386): [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
,D/libc-netbsd(  311): res_queryN name = clients3.google.com, class = 1, type = 1
,D/PostponalbeReceiver( 7364): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
I/PCSuite ( 7399): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
D/PCSuite ( 7399): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 7322): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 7322): MCCMNC not supported: null
D/QRemote ( 6386): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,D/QRemote ( 6386): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,D/QRemote ( 6386): [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
I/QRemote ( 6386): [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
I/QRemote ( 6386): [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
D/libc-netbsd(  311): res_queryN name = clients3.google.com succeed
D/DhcpStateMachine( 1030): DHCPV4 request on wlan0
V/LgDhcpStateMachineHelper( 1030): [bssid] hash key :c0:ff:d4:d3:aa:48
D/LgDhcpStateMachineHelper( 1030): dhcp.ap.macaddress = c0:ff:d4:d3:aa:48
,W/dhcpcd  ( 7820): type=1400 audit(0.0:169): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,W/dhcpcd  ( 7820): type=1400 audit(0.0:170): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
D/LGDataListener(  311): argv[0]=dsqncommand
D/LGDataListener(  311): argv[1]=wlan0
D/LGDataListener(  311): argv[2]=1
D/LGDataListener(  311): notifyDSQN DSQN STARTMONITOR wlan0 1
D/DSQN    ( 1030): DSQM DsqnNotification wlan0  1
D/DSQN    ( 1030): start to monitor internet connection
I/dhcpcd  ( 7820): version 5.5.6 starting
,E/dhcpcd  ( 7820): get_duid: m
D/dhcpcd  ( 7820): wlan0: using ClientID 01:c4:9a:02:7b:60:ac
D/dhcpcd  ( 7820): wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason PREINIT
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1030): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Tue, 01 Dec 2015 22:08:37 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1449007717829], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1449007717759]}
,D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1030): Don't send network conditions - lacking user consent.
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1030): Validated
D/ConnectivityService( 1030): Validated NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1030): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1030):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService( 1030):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1030):     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
D/ConnectivityService( 1030): Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
D/ConnectivityService( 1030): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1030):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1030):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1030): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityManager.CallbackHandler( 1446): CM callback handler got msg 524290
D/ConnectivityService( 1030): sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    ( 1030): new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/TelephonyNetworkFactory-1( 1855): new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    ( 1030):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/TelephonyNetworkFactory-1( 1855):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
D/ConnectivityService( 1030): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,D/TelephonyIcons( 1446): null signal icon name: drawable/stat_sys_signal_null
,D/StatusBar.NetworkController( 1446): refreshViews: Data not connected!! Set no data type icon / Roaming
D/StatusBar.NetworkController( 1446): refreshViews: Data not connected!! Set no data type icon / Roaming
D/dhcpcd  ( 7820): getUsingAPMacAddress: c0:ff:d4:d3:aa:48 , return 1
,D/dhcpcd  ( 7820): [read_lease] unlink /data/misc/dhcp/dhcpcd-wlan0.lease, link /data/misc/dhcp/dhcpcd-wlan0-c0:ff:d4:d3:aa:48.lease2
D/dhcpcd  ( 7820): wlan0: reading lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
I/dhcpcd  ( 7820): wlan0: rebinding lease of 192.168.1.122
D/dhcpcd  ( 7820): wlan0: sending REQUEST (xid 0xb10a2eb8), next in 3.37 seconds
E/WifiStateMachine( 1030):  ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
E/WifiStateMachine( 1030):  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
E/WifiStateMachine( 1030):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
,E/WifiStateMachine( 1030):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
E/WifiStateMachine( 1030):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
,E/WifiStateMachine( 1030):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
D/ConnectivityService( 1030): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=true
D/ConnectivityService( 1030): identical MTU - not setting
D/Nat464Xlat( 1030): requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
D/ConnectivityService( 1030): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1030):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1030):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1030): sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityManager.CallbackHandler( 1446): CM callback handler got msg 524295
I/dhcpcd  ( 7820): wlan0: acknowledged 192.168.1.122 from 192.168.1.1
,I/dhcpcd  ( 7820): wlan0: leased 192.168.1.122 for 86400 seconds
D/dhcpcd  ( 7820): wlan0: adding IP address 192.168.1.122/24
D/dhcpcd  ( 7820): wlan0: adding route to 192.168.1.0/24
D/dhcpcd  ( 7820): wlan0: adding default route via 192.168.1.1
D/dhcpcd  ( 7820): wlan0: writing lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
D/dhcpcd  ( 7820): getUsingAPMacAddress: c0:ff:d4:d3:aa:48 , return 1
D/dhcpcd  ( 7820): write_lease_ext: /data/misc/dhcp/dhcpcd-wlan0-c0:ff:d4:d3:aa:48.lease2
D/dhcpcd  ( 7820): wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason REBOOT
I/jxcore-log( 6121): DBG, CoordinatorConnector connect called
I/jxcore-log( 6121): 
I/jxcore-log( 6121): Coordinator is now connected to the server!
I/jxcore-log( 6121): 
,I/chromium( 6121): [INFO:CONSOLE(63)] "logCallback connected to server", source: file:///android_asset/www/js/thali_main.js (63)
,D/DhcpStateMachine( 1030): DHCPV4 succeeded on wlan0
,D/LgDhcpStateMachineHelper( 1030): CheckDhcpDirectory [Lease File Count] : 3
,V/LgDhcpStateMachineHelper( 1030): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
D/LgDhcpStateMachineHelper( 1030): checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.122
V/LgDhcpStateMachineHelper( 1030): Don't need to update mDhcpResultsCacheList
V/DhcpStateMachine( 1030): Current State is mWaitBeforeStartState.
V/LgDhcpStateMachineHelper( 1030): bShouldSendDhcpAction Result: false
D/DhcpStateMachine( 1030): DHCP Start/Renew wake lock is released.
D/DhcpStateMachine( 1030): RunningState
,E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-66 f=2462 sc=60 link=57 tx=74.0, 0.0, 0.0  rx=63.0 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:1603741791] gl rssi=-66 ag=0 ticks 0,0,1 ls-=0 [56,56,60,60,60] brc=0 lrc=0
E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-66 f=2462 sc=60 link=57 tx=74.0, 0.0, 0.0  rx=63.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:1603741794] gl rssi=-66 ag=0 ticks 0,0,1 ls-=0 [56,56,60,60,60] brc=0 lrc=0
D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
,D/StatusBar.NetworkController( 1446): refreshViews: Data not connected!! Set no data type icon / Roaming
,V/WifiInternetCheck( 1030): Single check msg out of sync, ignoring.
,D/ConnectivityService( 1030): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering( 1030): MasterInitialState.processMessage what=3
D/PostponalbeReceiver( 7364): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
,I/NetworkMonitor( 5187): type=WIFI subType= reason=null isConnected=true
,W/ContextImpl( 7364): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
I/NetworkStateForAutoUpdateMonitor( 7040): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 7040): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 7040): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 7040): [onReceive] request level :IDLE....
,I/AppUp4:CustModeStarterReceiver( 7040): onReceive
,D/AppUp4:CustFacade( 7040): Context : android.app.ReceiverRestrictedContext@1d2083bc
D/AppUp4:CustFacade( 7040): isCustomizationCompleted : false
D/AppUp4:CustFacade( 7040): isPhone : true
D/AppUp4:CustModeStarterReceiver( 7040): begin check event
I/AppUp4:CustModeStarterReceiver( 7040): Event For GoodConnectivity, noConnectivity : false, but skip! 
D/LGDMClient( 3941): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMClient( 3941): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
W/ContextImpl( 3941): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
W/ContextImpl( 3941): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
V/DownloadManager( 3291): Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
,D/eas_req ( 7513): ---addEventToQueue() easCode=2, requestId=0 (at EasSupport.java addEventToQueue 69)
,V/DownloadManager( 3291): DownloadService onCreate
I/LgeMiscReceiver( 3261): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
,I/LgeMiscReceiver( 3261): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 3261): networkInfo.isConnected() = true
D/PhoneState( 3261): setPdpRejectCasuse : false
,I/DownloadManager( 3291): in removeSpuriousFiles
V/DownloadManager( 3291): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
D/LGDMClient( 3941): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=3, isUserType=1
I/LGDMClient( 3941): [DmServiceProcessor.java] [processNetworkChanged()] : [91] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
V/DownloadManager( 3291): DownloadService onStartCommand
,V/DownloadManager( 3291): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3291): created cursor android.database.sqlite.SQLiteCursor@177b8d9e on behalf of 3291
V/DownloadManager( 3291): created cursor android.database.sqlite.SQLiteCursor@af5a07f on behalf of 3291
W/Settings( 7513): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WeatherAncestor( 7581): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 23:8:40
W/Settings( 7513): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/Weather.Utils( 7581): 2 : the weather widgets(using time tick) are gone.
D/Weather.Utils( 7581): 2 : All the weather widget is gone.
D/UpdateThreadPoolManager( 7581): 2 : This is isUpdating : false
D/WeatherAncestor( 7581): connectivity changed - connection : true
D/WeatherService( 7581): 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@10b2dac1
,D/ForecastDataCache( 7581): 2 : lastUpdatedTime: 1430558561343
D/ForecastDataCache( 7581): 2 : currentPackageVersion: 4.40.4
D/ForecastDataCache( 7581): 2 : Cache is up-to-date, count: 0
D/Weather_cast( 7581): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherAncestor( 7581): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 23:8:40
D/LGDMClient( 3941): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 3941): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
V/DownloadManager( 3291): processing inserted download 1
I/DownloadManager( 3291): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGMyGuide_4.40.09_COM_COM_20150430011620058_RELG-D855.apk
I/DownloadManager( 3291): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGBackup_4.50.37_COM_COM_20150608234245157.apk
I/DownloadManager( 3291): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/CalendarProvider_4.2.8_COM_COM_20150304234552863_RELG-D855.apk
I/DownloadManager( 3291): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calendar_4.40.16_COM_COM_20150304234554754_RELG-D855.apk
I/DownloadManager( 3291): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.10_COM_COM_20150521235426173_RELG-D855.apk
I/DownloadManager( 3291): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQVoiceplusN_2.3.3_COM_COM_20150604065210803.apk
I/DownloadManager( 3291): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.11_COM_COM_v2_20150911144028620_RELG-D855_21.apk
V/DownloadManager( 3291): processing inserted download 4
I/DownloadManager( 3291): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQMemoplus(LG-D855_user)_20150902050954661.apk
I/DownloadManager( 3291): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/RemoteCall_4.1.10_COM_COM_20150817053748728.apk
I/DownloadManager( 3291): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/rspermlge(6713)_20150901080430397.apk
V/DownloadManager( 3291): processing inserted download 7
W/ContextImpl( 3941): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:141 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:180 android.app.IntentService$ServiceHandler.handleMessage:65 
V/DownloadManager( 3291): processing inserted download 8
I/DownloadManager( 3291): in trimDatabase
V/DownloadManager( 3291): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
V/DownloadManager( 3291): processing inserted download 9
V/DownloadManager( 3291): created cursor android.database.sqlite.SQLiteCursor@22b6384c on behalf of 3291
,V/DownloadManager( 3291): processing inserted download 10
D/libc-netbsd(  311): default dns: query_ipv6=0, query_ipv4=1
,D/libc-netbsd(  311): res_queryN name = static-avc.lglime.com, class = 1, type = 1
V/DownloadManager( 3291): processing inserted download 16
V/DownloadManager( 3291): processing inserted download 17
V/DownloadManager( 3291): processing inserted download 18
V/DownloadManager( 3291): processing inserted download 21
I/ActivityManager( 1030): Start proc com.google.android.apps.books for service com.google.android.apps.books/.service.SyncService: pid=7886 uid=10054 gids={50054, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/GpsLocationProvider( 1030): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
E/LGDMClient( 3941): [DmNotiService.java] [onCreate()] : [148] : DmNotiService.onCreate()
D/LGDMClient( 3941): [DmNotiService.java] [onStartCommand()] : [182] : in the new onStartCommand()
D/LGDMClient( 3941): [DmNotiService.java] [handleStart()] : [203] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
D/GpsLocationProvider( 1030): updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
V/DownloadManager( 3291): DownloadService onDestroy
,D/libc-netbsd(  311): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  311): res_queryN name = mtalk.google.com, class = 1, type = 1
I/iu.Environment( 2327): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,D/libc-netbsd(  311): res_queryN name = static-avc.lglime.com succeed
I/iu.UploadsManager( 2327): num queued entries: 0
I/iu.UploadsManager( 2327): num updated entries: 0
I/iu.SyncManager( 2327): NEXT; no task
D/ChimeraCfgMgr( 2327): Loading module com.google.android.gms.kids from APK com.google.android.gms
D/ChimeraCfgMgr( 2327): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/libc-netbsd(  311): res_queryN name = mtalk.google.com succeed
I/GLSUser ( 2125): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: ac2dm
,I/GLSUser ( 2125): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> ac2dm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 2125): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2125): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2125): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/FormManager( 7444): There are no updated forms. The schedule will be deleted.
,V/FormManager( 7444): Alarm would be updated, because LastCheckTime has been updated.
V/NotificationService( 1030): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1030): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1030): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1030): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1030): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1396): onNotificationPosted
D/SmartCoverUpdateMonitor( 1396): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1396): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1396): handleNotificationPosted(true)
D/QuickCircle( 1396): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1396): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1396): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1396): post do just update job
D/LgeQuickCoverNotificationData( 1396): showAll3
D/LgeQuickCoverNotificationData( 1396): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1396): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
D/LgeQuickCoverNotificationData( 1396): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
E/LgeQuickCoverOverlayWindow( 1396): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1396): [native noti] inex =  0
I/ReaderUtils( 7886): PortraitW 1440 LandscapeW 2392 SmallestSize 1340 LargestSize 2392 textZoom 4.4999995 isTablet false Memory 256
D/LgeQuickCoverNotificationData( 1396): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1396): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1396): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1396): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1396): isNotificationForCurrentUser : true
W/Kids    ( 2327): [AccountUtils] Account not ready
W/Kids    ( 2327): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/Kids    ( 2327): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/Kids    ( 2327): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/Kids    ( 2327): 	at com.google.android.gms.auth.p.c(SourceFile:550)
W/Kids    ( 2327): 	at com.google.android.gms.auth.p.b(SourceFile:477)
W/Kids    ( 2327): 	at com.google.android.gms.kids.account.k.d(SourceFile:103)
W/Kids    ( 2327): 	at com.google.android.gms.kids.account.p.a(SourceFile:70)
W/Kids    ( 2327): 	at com.google.android.gms.kids.account.t.a(SourceFile:62)
W/Kids    ( 2327): 	at com.google.android.gms.chimera.f.run(SourceFile:179)
W/Kids    ( 2327): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Kids    ( 2327): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Kids    ( 2327): 	at java.lang.Thread.run(Thread.java:818)
E/LgeQuickCoverOverlayWindow( 1396): updateNotificationData: count=3
,D/QuickStatusbarLayout( 1396): Notification difference=198
,D/QuickStatusbarLayout( 1396): child = android.widget.LinearLayout{2154d13 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,W/GAV2    ( 7886): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,I/BooksApp( 7886): Created application version: 3.2.35 (30235)
,I/BooksSync( 7886): Starting books sync
,D/GCM     ( 2125): Connected
,I/GCM     ( 2125): Ack for not saved message 71
,D/GCM     ( 2125): Message class com.google.f.a.a.p
D/BooksSync( 7886): started syncMyEbooks
,V/GLSActivity( 2125): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     ( 1030): Explicit concurrent mark sweep GC freed 69775(3MB) AllocSpace objects, 2(160KB) LOS objects, 33% free, 44MB/67MB, paused 4.096ms total 182.614ms
,I/GLSUser ( 2125): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2125): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 2125): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2125): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2125): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1030): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1030): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1030): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1030): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1030): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
W/GLSActivity( 2125): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2125): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2125): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2125): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2125): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2125): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2125): 	at android.os.Binder.execTransact(Binder.java:446)
E/BooksAccountManager( 7886): Authentication error
E/BooksAccountManager( 7886): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7886): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 7886): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 7886): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 7886): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 7886): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 7886): null auth token
,D/LgeQuickCoverNLService( 1396): onNotificationPosted
D/SmartCoverUpdateMonitor( 1396): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1396): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1396): handleNotificationPosted(true)
D/QuickCircle( 1396): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1396): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1396): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1396): post do just update job
D/LgeQuickCoverNotificationData( 1396): showAll3
D/LgeQuickCoverNotificationData( 1396): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1396): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
D/LgeQuickCoverNotificationData( 1396): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
E/LgeQuickCoverOverlayWindow( 1396): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1396): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1396): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1396): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1396): isNotificationForCurrentUser : true
D/libc-netbsd(  311): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  311): res_queryN name = www.googleapis.com, class = 1, type = 1
D/LgeQuickCoverOverlayWindow( 1396): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1396): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1396): updateNotificationData: count=3
,D/QuickStatusbarLayout( 1396): Notification difference=198
D/QuickStatusbarLayout( 1396): child = android.widget.LinearLayout{2154d13 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,D/libc-netbsd(  311): res_queryN name = www.googleapis.com succeed
,D/libc-netbsd(  311): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  311): res_queryN name = www.google.com, class = 1, type = 1
,D/libc-netbsd(  311): res_queryN name = www.google.com succeed
,D/libc-netbsd(  311): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  311): res_queryN name = clients3.google.com, class = 1, type = 1
D/libc-netbsd(  311): res_queryN name = clients3.google.com succeed
V/WifiInternetCheck( 1030): isHttpConnectionAvailable - We got a valid response : 204
,W/ApiaryClient( 7886): Error response from books API: {
W/ApiaryClient( 7886):  "error": {
W/ApiaryClient( 7886):   "errors": [
W/ApiaryClient( 7886):    {
W/ApiaryClient( 7886):     "domain": "global",
W/ApiaryClient( 7886):     "reason": "required",
W/ApiaryClient( 7886):     "message": "Login Required",
W/ApiaryClient( 7886):     "locationType": "header",
W/ApiaryClient( 7886):     "location": "Authorization"
W/ApiaryClient( 7886):    }
W/ApiaryClient( 7886):   ],
W/ApiaryClient( 7886):   "code": 401,
W/ApiaryClient( 7886):   "message": "Login Required"
W/ApiaryClient( 7886):  }
W/ApiaryClient( 7886): }
,W/ApiaryClient( 7886): errCount = 1: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7886): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=575681240679184946&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7886): Headers:
W/ApiaryClient( 7886): accept-encoding: [gzip]
W/ApiaryClient( 7886): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 7886): gdata-version: 2
,W/bt-l2cap( 6184): l2c_link_hci_conn_req:current link_role= 1
,W/bt-btm  ( 6184): btm_acl_created hci_handle=1 link_role=1  transport=1
,W/bt-btm  ( 6184): btm_acl_created hci_handle=1 link_role=1  transport=1
W/bt-btm  ( 6184): btm_read_remote_version_complete: BDA: 80-01-84-8a-b3-68
W/bt-btm  ( 6184): btm_read_remote_version_complete lmp_version 7 manufacturer 29 lmp_subversion 2003
,W/bt-btm  ( 6184): btm_process_remote_ext_features_page 0: BDA: 80-01-84-8a-b3-68
W/bt-btm  ( 6184): ext_features_complt page_num:1 f[0]:x03, sm4:11, pend:0
W/bt-btm  ( 6184): btm_process_remote_ext_features_page 1: BDA: 80-01-84-8a-b3-68
W/bt-btif ( 6184): info:x10
,D/        ( 6184): remote version info [80:01:84:8a:b3:68]: 7, 1d, 7d3
W/bt-l2cap( 6184): L2CA_SetDesireRole() new:x0, disallow_switch:0
E/BluetoothRemoteDevices( 6184): aclStateChangeCallback: Device is NULL
D/LGBluetoothServiceUtil( 6184): [BTUI] sendBroadcastAclConnection: Connected, but device is null, sendBroadcast
D/BluetoothManagerService( 1030): Message: 20
D/BluetoothManagerService( 1030): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@1eb227a2:true
,D/LGBluetoothFeatureConfig( 7322): isPrivacyLogsEnabled : true
D/LGBluetoothUtils( 7322): [BTUI] FileNotFound: readProperty
D/LGBluetoothUtils( 7322): [BTUI] FileNotFound: storeHashmapFromFile
D/LGBluetoothPowerSaveListener( 7322): [BTUI] ACL connected => AclLinkCount = 1
,W/bt-l2cap( 6184): L2CAP - st: CLOSED evt: 10
W/bt-l2cap( 6184): L2CAP - st: TERM_W4_SEC_COMP evt: 7
W/bt-l2cap( 6184): L2CA_ErtmConnectRsp()  CID: 0x0040  Result: 0  Status: 0  BDA: 8001848ab368  p_ertm_info:0x00000000
W/bt-l2cap( 6184): L2CAP - st: W4_L2CA_CON_RSP evt: 22
,W/bt-l2cap( 6184): L2CAP - st: CONFIG evt: 24
V/GLSActivity( 2125): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/bt-l2cap( 6184): L2CAP - st: CONFIG evt: 14
W/bt-l2cap( 6184): L2CAP - st: CONFIG evt: 25
W/bt-l2cap( 6184): L2CAP-Upper layer Config_Rsp,Local CID: 0x0040,Remote CID: 0x0045,PSM: 1,our MTU present:1,our MTU:672
,W/bt-l2cap( 6184): L2CAP - st: CONFIG evt: 15
W/bt-l2cap( 6184): L2CAP-peer_Config_Rsp,Local CID: 0x0040,Remote CID: 0x0045,PSM: 1,peer MTU present: 0,peer MTU: 256
I/GLSUser ( 2125): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2125): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2125): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2125): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
W/bt-l2cap( 6184): L2CA_DisconnectRsp()  CID: 0x0040
W/bt-l2cap( 6184): L2CAP - st: W4_L2CA_DISC_RSP evt: 28
V/GLSActivity( 2125): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/NotificationService( 1030): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1030): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1030): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1030): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1030): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1396): onNotificationPosted
,D/SmartCoverUpdateMonitor( 1396): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1396): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1396): handleNotificationPosted(true)
D/QuickCircle( 1396): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1396): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1396): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1396): post do just update job
D/LgeQuickCoverNotificationData( 1396): showAll3
D/LgeQuickCoverNotificationData( 1396): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1396): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
D/LgeQuickCoverNotificationData( 1396): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
E/LgeQuickCoverOverlayWindow( 1396): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1396): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1396): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1396): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1396): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1396): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1396): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1396): updateNotificationData: count=3
,W/GLSActivity( 2125): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2125): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2125): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2125): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2125): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2125): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2125): 	at android.os.Binder.execTransact(Binder.java:446)
E/BooksAccountManager( 7886): Authentication error
E/BooksAccountManager( 7886): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7886): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 7886): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 7886): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 7886): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 7886): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 7886): null auth token
,D/QuickStatusbarLayout( 1396): Notification difference=198
D/QuickStatusbarLayout( 1396): child = android.widget.LinearLayout{2154d13 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-49 f=2462 sc=60 link=72 tx=45.0, 0.0, 0.0  rx=37.5 bcn=0 [on:0 tx:0 rx:0 period:3000] from screen [on:0 period:1603744834] gl rssi=-49 ag=0 hr ticks 0,0,1 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-49 f=2462 sc=60 link=72 tx=45.0, 0.0, 0.0  rx=37.5 bcn=0 [on:0 tx:0 rx:0 period:14] from screen [on:0 period:1603744848] gl rssi=-49 ag=0 hr ticks 0,0,1 ls-=0 [56,56,60,60,65] brc=0 lrc=0
D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
W/ApiaryClient( 7886): Error response from books API: {
W/ApiaryClient( 7886):  "error": {
W/ApiaryClient( 7886):   "errors": [
W/ApiaryClient( 7886):    {
W/ApiaryClient( 7886):     "domain": "global",
W/ApiaryClient( 7886):     "reason": "required",
W/ApiaryClient( 7886):     "message": "Login Required",
W/ApiaryClient( 7886):     "locationType": "header",
W/ApiaryClient( 7886):     "location": "Authorization"
W/ApiaryClient( 7886):    }
W/ApiaryClient( 7886):   ],
W/ApiaryClient( 7886):   "code": 401,
W/ApiaryClient( 7886):   "message": "Login Required"
W/ApiaryClient( 7886):  }
W/ApiaryClient( 7886): }
,W/ApiaryClient( 7886): errCount = 2: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7886): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=575681240679184946&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7886): Headers:
W/ApiaryClient( 7886): accept-encoding: [gzip]
W/ApiaryClient( 7886): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 7886): gdata-version: 2
V/GLSActivity( 2125): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2125): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2125): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2125): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 2125): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2125): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1030): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1030): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1030): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1030): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1030): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1396): onNotificationPosted
,D/SmartCoverUpdateMonitor( 1396): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1396): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1396): handleNotificationPosted(true)
D/QuickCircle( 1396): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1396): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1396): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1396): post do just update job
D/LgeQuickCoverNotificationData( 1396): showAll3
D/LgeQuickCoverNotificationData( 1396): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1396): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
D/LgeQuickCoverNotificationData( 1396): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
E/LgeQuickCoverOverlayWindow( 1396): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1396): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1396): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1396): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1396): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1396): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1396): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1396): updateNotificationData: count=3
,W/GLSActivity( 2125): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2125): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2125): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2125): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2125): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2125): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2125): 	at android.os.Binder.execTransact(Binder.java:446)
E/BooksAccountManager( 7886): Authentication error
E/BooksAccountManager( 7886): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7886): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 7886): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 7886): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 7886): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 7886): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 7886): null auth token
,D/QuickStatusbarLayout( 1396): Notification difference=198
D/QuickStatusbarLayout( 1396): child = android.widget.LinearLayout{2154d13 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
W/ApiaryClient( 7886): Error response from books API: {
W/ApiaryClient( 7886):  "error": {
W/ApiaryClient( 7886):   "errors": [
W/ApiaryClient( 7886):    {
W/ApiaryClient( 7886):     "domain": "global",
W/ApiaryClient( 7886):     "reason": "required",
W/ApiaryClient( 7886):     "message": "Login Required",
W/ApiaryClient( 7886):     "locationType": "header",
W/ApiaryClient( 7886):     "location": "Authorization"
W/ApiaryClient( 7886):    }
W/ApiaryClient( 7886):   ],
W/ApiaryClient( 7886):   "code": 401,
W/ApiaryClient( 7886):   "message": "Login Required"
W/ApiaryClient( 7886):  }
W/ApiaryClient( 7886): }
,W/ApiaryClient( 7886): errCount = 3: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7886): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=575681240679184946&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7886): Headers:
W/ApiaryClient( 7886): accept-encoding: [gzip]
W/ApiaryClient( 7886): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 7886): gdata-version: 2
I/GAV2    ( 7886): Thread[GAThread,5,main]: No campaign data found.
,E/BooksSync( 7886): Soft error: 
E/BooksSync( 7886): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 7886): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=575681240679184946&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 7886): Headers:
E/BooksSync( 7886): accept-encoding: [gzip]
E/BooksSync( 7886): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 7886): gdata-version: 2
E/BooksSync( 7886): 
E/BooksSync( 7886): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 7886): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 7886): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 7886): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 7886): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 7886): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 7886): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 7886): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 7886): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 7886): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 7886): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 7886): {
E/BooksSync( 7886):  "error": {
E/BooksSync( 7886):   "errors": [
E/BooksSync( 7886):    {
E/BooksSync( 7886):     "domain": "global",
E/BooksSync( 7886):     "reason": "required",
E/BooksSync( 7886):     "message": "Login Required",
E/BooksSync( 7886):     "locationType": "header",
E/BooksSync( 7886):     "location": "Authorization"
E/BooksSync( 7886):    }
E/BooksSync( 7886):   ],
E/BooksSync( 7886):   "code": 401,
E/BooksSync( 7886):   "message": "Login Required"
E/BooksSync( 7886):  }
E/BooksSync( 7886): }
E/BooksSync( 7886): 
E/BooksSync( 7886): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 7886): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 7886): 	... 8 more
E/BooksSync( 7886): Sync error
E/BooksSync( 7886): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 7886): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=575681240679184946&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 7886): Headers:
E/BooksSync( 7886): accept-encoding: [gzip]
E/BooksSync( 7886): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 7886): gdata-version: 2
E/BooksSync( 7886): 
E/BooksSync( 7886): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 7886): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 7886): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 7886): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 7886): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 7886): 	at com.google.android.apps.books.data.NetworkTaskQue,ue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 7886): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 7886): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 7886): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 7886): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 7886): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 7886): {
E/BooksSync( 7886):  "error": {
E/BooksSync( 7886):   "errors": [
E/BooksSync( 7886):    {
E/BooksSync( 7886):     "domain": "global",
E/BooksSync( 7886):     "reason": "required",
E/BooksSync( 7886):     "message": "Login Required",
E/BooksSync( 7886):     "locationType": "header",
E/BooksSync( 7886):     "location": "Authorization"
E/BooksSync( 7886):    }
E/BooksSync( 7886):   ],
E/BooksSync( 7886):   "code": 401,
E/BooksSync( 7886):   "message": "Login Required"
E/BooksSync( 7886):  }
E/BooksSync( 7886): }
E/BooksSync( 7886): 
E/BooksSync( 7886): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 7886): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 7886): 	... 8 more
I/BooksSync( 7886): Finished books sync
I/ActivityManager( 1030): Killing 7722:com.lge.bnr/1000 (adj 15): empty #17
,D/SyncManager( 1030): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 433462, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,W/libprocessgroup( 1030): failed to open /acct/uid_1000/pid_7722/cgroup.procs: No such file or directory
,D/sensors_hal_Time( 1030): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1030): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1030): tsOffsetIs: Apps: 448783295353; DSPS: 14846327; Offset : -4304277512
,E/bt-btm  ( 6184): btm_sec_disconnected - Clearing Pending flag
W/bt-l2cap( 6184): L2CA_SetDesireRole() new:x0, disallow_switch:0
,D/WifiServerServiceExt( 1030): Connected BT device : -1
I/BluetoothMapService( 6184): onReceive: android.bluetooth.device.action.ACL_DISCONNECTED
V/BluetoothPbapReceiver( 6184): PbapReceiver onReceive 
V/BluetoothPbapReceiver( 6184): ***********action = android.bluetooth.device.action.ACL_DISCONNECTED
V/BluetoothPbapReceiver( 6184): ***********Calling start service!!!! with action = null
,V/BluetoothPbapService( 6184): action: android.bluetooth.device.action.ACL_DISCONNECTED
V/BluetoothPbapService( 6184): state: -2147483648
D/BluetoothManagerService( 1030): Message: 20
D/BluetoothManagerService( 1030): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@2fa1a4aa:true
,D/LGBluetoothPowerSaveListener( 7322): [BTUI] ACL disconnected => AclLinkCount = 0
D/BluetoothManagerService( 1030): Message: 20
D/BluetoothManagerService( 1030): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@21cae438:true
,I/BTConnectionReceiver( 4198): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=80:01:84:8A:B3:68, alias=null, name=HTC Desire 820, majorDeviceClass=0, deviceClass=0]
,I/BluetoothClassifier( 4198): Bluetooth Device Name: HTC Desire 820
,E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-50 f=2462 sc=60 link=72 tx=40.5, 0.0, 0.0  rx=33.2 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:1603747862] gl rssi=-50 ag=0 hr ticks 0,0,1 ls-=0 [56,56,60,60,65] brc=0 lrc=0
E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-50 f=2462 sc=60 link=72 tx=40.5, 0.0, 0.0  rx=33.2 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:1603747865] gl rssi=-50 ag=0 hr ticks 0,0,1 ls-=0 [56,56,60,60,65] brc=0 lrc=0
D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
,D/btif_config_util( 6184): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-50 f=2462 sc=60 link=72 tx=23.8, 0.0, 0.0  rx=19.1 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:1603750893] gl rssi=-50 ag=0 hr ticks 0,0,1 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-50 f=2462 sc=60 link=72 tx=23.8, 0.0, 0.0  rx=19.1 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:1603750903] gl rssi=-50 ag=0 hr ticks 0,0,1 ls-=0 [56,56,60,60,65] brc=0 lrc=0
D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-50 f=2462 sc=60 link=72 tx=12.4, 0.0, 0.0  rx=9.6 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:1603753924] gl rssi=-50 ag=0 hr ticks 0,0,1 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-50 f=2462 sc=60 link=72 tx=12.4, 0.0, 0.0  rx=9.6 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:1603753934] gl rssi=-50 ag=0 hr ticks 0,0,1 ls-=0 [56,56,60,60,65] brc=0 lrc=0
D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
W/bt-l2cap( 6184): l2c_link_hci_conn_req:current link_role= 0
,W/bt-btm  ( 6184): btm_acl_role_changed: BDA: 80-01-84-8a-b3-68
,W/bt-btm  ( 6184): btm_acl_role_changed: New role: 0
,W/bt-btm  ( 6184): btm_acl_created hci_handle=2 link_role=1  transport=1
W/bt-btm  ( 6184): btm_acl_created hci_handle=2 link_role=0  transport=1
W/bt-btif ( 6184): info:x10
W/bt-l2cap( 6184): L2CA_SetDesireRole() new:x0, disallow_switch:0
,D/        ( 6184): remote version info [80:01:84:8a:b3:68]: 7, 1d, 7d3
,W/bt-btm  ( 6184): btm_read_remote_version_complete: BDA: 80-01-84-8a-b3-68
W/bt-btm  ( 6184): btm_read_remote_version_complete lmp_version 7 manufacturer 29 lmp_subversion 2003
,D/WifiServerServiceExt( 1030): Connected BT device : 0
W/bt-btm  ( 6184): btm_process_remote_ext_features_page 0: BDA: 80-01-84-8a-b3-68
,W/bt-btm  ( 6184): ext_features_complt page_num:1 f[0]:x03, sm4:11, pend:0
W/bt-btm  ( 6184): btm_process_remote_ext_features_page 1: BDA: 80-01-84-8a-b3-68
W/bt-l2cap( 6184): L2CAP - st: CLOSED evt: 10
W/bt-l2cap( 6184): L2CAP - st: TERM_W4_SEC_COMP evt: 7
W/bt-l2cap( 6184): L2CA_ErtmConnectRsp()  CID: 0x0041  Result: 0  Status: 0  BDA: 8001848ab368  p_ertm_info:0x00000000
W/bt-l2cap( 6184): L2CAP - st: W4_L2CA_CON_RSP evt: 22
W/bt-l2cap( 6184): L2CAP - st: CONFIG evt: 24
D/LGBluetoothPowerSaveListener( 7322): [BTUI] ACL connected => AclLinkCount = 1
W/bt-l2cap( 6184): L2CAP - st: CONFIG evt: 14
W/bt-l2cap( 6184): L2CAP - st: CONFIG evt: 25
W/bt-l2cap( 6184): L2CAP-Upper layer Config_Rsp,Local CID: 0x0041,Remote CID: 0x004c,PSM: 1,our MTU present:1,our MTU:672
W/bt-l2cap( 6184): L2CAP - st: CONFIG evt: 15
W/bt-l2cap( 6184): L2CAP-peer_Config_Rsp,Local CID: 0x0041,Remote CID: 0x004c,PSM: 1,peer MTU present: 0,peer MTU: 256
,W/bt-l2cap( 6184): L2CA_DisconnectRsp()  CID: 0x0041
W/bt-l2cap( 6184): L2CAP - st: W4_L2CA_DISC_RSP evt: 28
I/BTConnectionReceiver( 4198): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=80:01:84:8A:B3:68, alias=null, name=HTC Desire 820, majorDeviceClass=0, deviceClass=0]
I/BluetoothClassifier( 4198): Bluetooth Device Name: HTC Desire 820
,E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-50 f=2462 sc=60 link=72 tx=6.2, 0.0, 0.0  rx=4.8 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:1603756955] gl rssi=-50 ag=0 hr ticks 0,0,1 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-50 f=2462 sc=60 link=72 tx=6.2, 0.0, 0.0  rx=4.8 bcn=0 [on:0 tx:0 rx:0 period:11] from screen [on:0 period:1603756966] gl rssi=-50 ag=0 hr ticks 0,0,1 ls-=0 [56,56,60,60,65] brc=0 lrc=0
D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
W/bt-l2cap( 6184): l2c_link_hci_conn_req:current link_role= 0
,W/bt-btm  ( 6184): btm_acl_role_changed: BDA: e0-db-10-14-e2-c0
W/bt-btm  ( 6184): btm_acl_role_changed: New role: 0
,W/bt-btm  ( 6184): btm_acl_created hci_handle=3 link_role=1  transport=1
W/bt-btm  ( 6184): btm_acl_created hci_handle=3 link_role=0  transport=1
,W/bt-btm  ( 6184): btm_read_remote_version_complete: BDA: e0-db-10-14-e2-c0
W/bt-btm  ( 6184): btm_read_remote_version_complete lmp_version 7 manufacturer 15 lmp_subversion 8709
,E/bt-btm  ( 6184): btm_sec_disconnected - Clearing Pending flag
W/bt-l2cap( 6184): L2CA_SetDesireRole() new:x0, disallow_switch:0
,D/WifiServerServiceExt( 1030): Connected BT device : -1
,I/BluetoothMapService( 6184): onReceive: android.bluetooth.device.action.ACL_DISCONNECTED
,V/BluetoothPbapReceiver( 6184): PbapReceiver onReceive 
V/BluetoothPbapReceiver( 6184): ***********action = android.bluetooth.device.action.ACL_DISCONNECTED
V/BluetoothPbapReceiver( 6184): ***********Calling start service!!!! with action = null
,V/BluetoothPbapService( 6184): action: android.bluetooth.device.action.ACL_DISCONNECTED
V/BluetoothPbapService( 6184): state: -2147483648
D/LGBluetoothPowerSaveListener( 7322): [BTUI] ACL disconnected => AclLinkCount = 0
,I/BTConnectionReceiver( 4198): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=80:01:84:8A:B3:68, alias=null, name=HTC Desire 820, majorDeviceClass=0, deviceClass=0]
,I/BluetoothClassifier( 4198): Bluetooth Device Name: HTC Desire 820
W/bt-btm  ( 6184): btm_process_remote_ext_features_page 0: BDA: e0-db-10-14-e2-c0
W/bt-btm  ( 6184): ext_features_complt page_num:1 f[0]:x07, sm4:11, pend:0
W/bt-btm  ( 6184): btm_process_remote_ext_features_page 1: BDA: e0-db-10-14-e2-c0
W/bt-btif ( 6184): info:x10
W/bt-l2cap( 6184): L2CA_SetDesireRole() new:x0, disallow_switch:0
D/        ( 6184): remote version info [e0:db:10:14:e2:c0]: 7, f, 2205
E/BluetoothRemoteDevices( 6184): aclStateChangeCallback: Device is NULL
D/LGBluetoothServiceUtil( 6184): [BTUI] sendBroadcastAclConnection: Connected, but device is null, sendBroadcast
D/LGBluetoothPowerSaveListener( 7322): [BTUI] ACL connected => AclLinkCount = 1
,E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-52 f=2462 sc=60 link=72 tx=3.1, 0.0, 0.0  rx=2.4 bcn=0 [on:0 tx:0 rx:0 period:2999] from screen [on:0 period:1603759976] gl rssi=-52 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-52 f=2462 sc=60 link=72 tx=3.1, 0.0, 0.0  rx=2.4 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:1603759977] gl rssi=-52 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
,W/bt-btm  ( 6184): btm_acl_role_changed: BDA: e0-db-10-14-e2-c0
W/bt-btm  ( 6184): btm_acl_role_changed: New role: 1
E/bt-btm  ( 6184): tBTM_SEC_DEV:0xa039b218 rs_disc_pending=0
W/bt-btif ( 6184): bta_dm_check_av:0
W/bt-btif ( 6184): btif_dm_cback : unhandled event (14)
W/bt-l2cap( 6184): L2CAP - st: CLOSED evt: 10
W/bt-l2cap( 6184): L2CAP - st: TERM_W4_SEC_COMP evt: 7
W/bt-l2cap( 6184): L2CA_ErtmConnectRsp()  CID: 0x0042  Result: 0  Status: 0  BDA: e0db1014e2c0  p_ertm_info:0x00000000
W/bt-l2cap( 6184): L2CAP - st: W4_L2CA_CON_RSP evt: 22
W/bt-l2cap( 6184): L2CAP - st: CONFIG evt: 24
,W/bt-l2cap( 6184): L2CAP - st: CONFIG evt: 14
W/bt-l2cap( 6184): L2CAP - st: CONFIG evt: 25
W/bt-l2cap( 6184): L2CAP-Upper layer Config_Rsp,Local CID: 0x0042,Remote CID: 0x0045,PSM: 1,our MTU present:1,our MTU:672
,W/bt-l2cap( 6184): L2CAP - st: CONFIG evt: 15
W/bt-l2cap( 6184): L2CAP-peer_Config_Rsp,Local CID: 0x0042,Remote CID: 0x0045,PSM: 1,peer MTU present: 0,peer MTU: 672
W/bt-l2cap( 6184): L2CA_DisconnectRsp()  CID: 0x0042
W/bt-l2cap( 6184): L2CAP - st: W4_L2CA_DISC_RSP evt: 28
,V/AlarmManager( 1030): RTC_WAKEUP set : Alarm{18cd6176 type 0 when 1449007731487 com.android.vending} when 1449007731487
,V/SIM_STK ( 1030): Menu title from STK is T-Mobile
,V/GLSActivity( 2125): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2125): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 2125): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2125): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 2125): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2125): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/Finsky  ( 7119): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 7119): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 7119): [1] 5.onFinished: Scheduling replication attempt 5.
I/[SystemUI]TimeTickManager( 1446): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1446): called onTimeUpdated()
,I/[SystemUI]KeyguardIndicationController( 1446): called onTimeUpdated()
,I/[SystemUI]Clock( 1446): called onTimeUpdated()
I/LgeClockWidgetControlView( 1446): called onTimeUpdated()
I/[SystemUI]DateView( 1446): called onTimeUpdated()
I/[SystemUI]DateView( 1446): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1446): handleTimeUpdate
E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-52 f=2462 sc=60 link=72 tx=1.5, 0.0, 0.0  rx=1.2 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:1603762988] gl rssi=-52 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-52 f=2462 sc=60 link=72 tx=1.5, 0.0, 0.0  rx=1.2 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:1603762991] gl rssi=-52 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
,E/bt-btm  ( 6184): btm_sec_disconnected - Clearing Pending flag
W/bt-l2cap( 6184): L2CA_SetDesireRole() new:x0, disallow_switch:0
,D/WifiServerServiceExt( 1030): Connected BT device : -2
,I/BluetoothMapService( 6184): onReceive: android.bluetooth.device.action.ACL_DISCONNECTED
,V/BluetoothPbapReceiver( 6184): PbapReceiver onReceive 
V/BluetoothPbapReceiver( 6184): ***********action = android.bluetooth.device.action.ACL_DISCONNECTED
,V/BluetoothPbapReceiver( 6184): ***********Calling start service!!!! with action = null
V/BluetoothPbapService( 6184): action: android.bluetooth.device.action.ACL_DISCONNECTED
V/BluetoothPbapService( 6184): state: -2147483648
D/LGBluetoothPowerSaveListener( 7322): [BTUI] ACL disconnected => AclLinkCount = 0
,I/BTConnectionReceiver( 4198): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=E0:DB:10:14:E2:C0, alias=null, name=Note4-1, majorDeviceClass=0, deviceClass=0]
,I/BluetoothClassifier( 4198): Bluetooth Device Name: Note4-1
D/btif_config_util( 6184): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-55 f=2462 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.6 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:1603766011] gl rssi=-55 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-55 f=2462 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.6 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:1603766014] gl rssi=-55 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
,D/sensors_hal_Time( 1030): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1030): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1030): tsOffsetIs: Apps: 468782583887; DSPS: 15501664; Offset : -4304287229
,E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-55 f=2462 sc=60 link=72 tx=1.4, 0.0, 0.0  rx=1.3 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:1603769041] gl rssi=-55 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-55 f=2462 sc=60 link=72 tx=1.4, 0.0, 0.0  rx=1.3 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:1603769044] gl rssi=-55 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-55 f=2462 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.6 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:1603772068] gl rssi=-55 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-55 f=2462 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.6 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:1603772071] gl rssi=-55 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
,D/PowerManagerServiceEx( 1030): acquireWakeLockInternal: lock=174419834, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1030
,W/bt-l2cap( 6184): l2c_link_hci_conn_req:current link_role= 0
V/AlarmManager( 1030): ELAPSED_WAKEUP set : Alarm{32dbcb68 type 2 when 473248 android} when 473248
,D/[Concierge]Service( 2596): onStartCommand(). Type : 9
,D/PowerManagerServiceEx( 1030): releaseWakeLockInternal: lock=174419834 [*alarm*], flags=0x0
,W/bt-btm  ( 6184): btm_acl_role_changed: BDA: e0-db-10-14-e2-c0
,W/bt-btm  ( 6184): btm_acl_role_changed: New role: 0
,W/bt-btm  ( 6184): btm_acl_created hci_handle=4 link_role=1  transport=1
W/bt-btm  ( 6184): btm_acl_created hci_handle=4 link_role=0  transport=1
W/bt-btif ( 6184): info:x10
W/bt-l2cap( 6184): L2CA_SetDesireRole() new:x0, disallow_switch:0
,D/        ( 6184): remote version info [e0:db:10:14:e2:c0]: 7, 1d, 7d3
W/bt-btm  ( 6184): btm_read_remote_version_complete: BDA: e0-db-10-14-e2-c0
W/bt-btm  ( 6184): btm_read_remote_version_complete lmp_version 7 manufacturer 15 lmp_subversion 8709
D/WifiServerServiceExt( 1030): Connected BT device : -1
,D/LGBluetoothPowerSaveListener( 7322): [BTUI] ACL connected => AclLinkCount = 1
,I/BTConnectionReceiver( 4198): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=E0:DB:10:14:E2:C0, alias=null, name=Note4-1, majorDeviceClass=0, deviceClass=0]
,I/BluetoothClassifier( 4198): Bluetooth Device Name: Note4-1
W/bt-btm  ( 6184): btm_process_remote_ext_features_page 0: BDA: e0-db-10-14-e2-c0
W/bt-btm  ( 6184): ext_features_complt page_num:1 f[0]:x07, sm4:11, pend:0
W/bt-btm  ( 6184): btm_process_remote_ext_features_page 1: BDA: e0-db-10-14-e2-c0
,W/bt-l2cap( 6184): L2CAP - st: CLOSED evt: 10
,W/bt-l2cap( 6184): L2CAP - st: TERM_W4_SEC_COMP evt: 7
W/bt-l2cap( 6184): L2CA_ErtmConnectRsp()  CID: 0x0043  Result: 0  Status: 0  BDA: e0db1014e2c0  p_ertm_info:0x00000000
,W/bt-l2cap( 6184): L2CAP - st: W4_L2CA_CON_RSP evt: 22
W/bt-l2cap( 6184): L2CAP - st: CONFIG evt: 24
,W/bt-l2cap( 6184): L2CAP - st: CONFIG evt: 14
W/bt-l2cap( 6184): L2CAP - st: CONFIG evt: 25
W/bt-l2cap( 6184): L2CAP-Upper layer Config_Rsp,Local CID: 0x0043,Remote CID: 0x0046,PSM: 1,our MTU present:1,our MTU:672
,W/bt-l2cap( 6184): L2CAP - st: CONFIG evt: 15
W/bt-l2cap( 6184): L2CAP-peer_Config_Rsp,Local CID: 0x0043,Remote CID: 0x0046,PSM: 1,peer MTU present: 0,peer MTU: 672
W/bt-l2cap( 6184): L2CA_DisconnectRsp()  CID: 0x0043
W/bt-l2cap( 6184): L2CAP - st: W4_L2CA_DISC_RSP evt: 28
,E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-55 f=2462 sc=60 link=72 tx=0.3, 0.0, 0.0  rx=0.3 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:1603775134] gl rssi=-55 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-55 f=2462 sc=60 link=72 tx=0.3, 0.0, 0.0  rx=0.3 bcn=0 [on:0 tx:0 rx:0 period:9] from screen [on:0 period:1603775143] gl rssi=-55 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
E/bt-btm  ( 6184): btm_sec_disconnected - Clearing Pending flag
W/bt-l2cap( 6184): L2CA_SetDesireRole() new:x0, disallow_switch:0
,D/WifiServerServiceExt( 1030): Connected BT device : -2
I/BluetoothMapService( 6184): onReceive: android.bluetooth.device.action.ACL_DISCONNECTED
,V/BluetoothPbapReceiver( 6184): PbapReceiver onReceive 
V/BluetoothPbapReceiver( 6184): ***********action = android.bluetooth.device.action.ACL_DISCONNECTED
V/BluetoothPbapReceiver( 6184): ***********Calling start service!!!! with action = null
V/BluetoothPbapService( 6184): action: android.bluetooth.device.action.ACL_DISCONNECTED
V/BluetoothPbapService( 6184): state: -2147483648
D/LGBluetoothPowerSaveListener( 7322): [BTUI] ACL disconnected => AclLinkCount = 0
,I/BTConnectionReceiver( 4198): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=E0:DB:10:14:E2:C0, alias=null, name=Note4-1, majorDeviceClass=0, deviceClass=0]
,I/BluetoothClassifier( 4198): Bluetooth Device Name: Note4-1
,E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-55 f=2462 sc=60 link=72 tx=0.2, 0.0, 0.0  rx=0.2 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:1603778162] gl rssi=-55 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-55 f=2462 sc=60 link=72 tx=0.2, 0.0, 0.0  rx=0.2 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:1603778165] gl rssi=-55 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
,D/btif_config_util( 6184): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/WifiStateMachine( 1030):  ConnectedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
E/WifiStateMachine( 1030):  L2ConnectedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
,E/WifiStateMachine( 1030):  ConnectModeState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
E/WifiStateMachine( 1030):  DriverStartedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
E/WifiStateMachine( 1030):  SupplicantStartedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
E/WifiStateMachine( 1030):  DefaultState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-55 f=2462 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:1603781192] gl rssi=-55 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-55 f=2462 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:1603781195] gl rssi=-55 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
,W/bt-l2cap( 6184): l2c_link_hci_conn_req:current link_role= 0
,W/bt-btm  ( 6184): btm_acl_role_changed: BDA: e0-db-10-14-e2-c0
W/bt-btm  ( 6184): btm_acl_role_changed: New role: 0
,W/bt-btm  ( 6184): btm_acl_created hci_handle=5 link_role=1  transport=1
W/bt-btm  ( 6184): btm_acl_created hci_handle=5 link_role=0  transport=1
W/bt-btif ( 6184): info:x10
W/bt-l2cap( 6184): L2CA_SetDesireRole() new:x0, disallow_switch:0
D/        ( 6184): remote version info [e0:db:10:14:e2:c0]: 7, f, 2205
,W/bt-btm  ( 6184): btm_read_remote_version_complete: BDA: e0-db-10-14-e2-c0
W/bt-btm  ( 6184): btm_read_remote_version_complete lmp_version 7 manufacturer 15 lmp_subversion 8709
D/WifiServerServiceExt( 1030): Connected BT device : -1
,W/bt-btm  ( 6184): btm_process_remote_ext_features_page 0: BDA: e0-db-10-14-e2-c0
W/bt-btm  ( 6184): ext_features_complt page_num:1 f[0]:x07, sm4:11, pend:0
W/bt-btm  ( 6184): btm_process_remote_ext_features_page 1: BDA: e0-db-10-14-e2-c0
,D/LGBluetoothPowerSaveListener( 7322): [BTUI] ACL connected => AclLinkCount = 1
,I/BTConnectionReceiver( 4198): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=E0:DB:10:14:E2:C0, alias=null, name=Note4-1, majorDeviceClass=0, deviceClass=0]
,I/BluetoothClassifier( 4198): Bluetooth Device Name: Note4-1
W/bt-l2cap( 6184): L2CAP - st: CLOSED evt: 10
W/bt-l2cap( 6184): L2CAP - st: TERM_W4_SEC_COMP evt: 7
W/bt-l2cap( 6184): L2CA_ErtmConnectRsp()  CID: 0x0044  Result: 0  Status: 0  BDA: e0db1014e2c0  p_ertm_info:0x00000000
W/bt-l2cap( 6184): L2CAP - st: W4_L2CA_CON_RSP evt: 22
W/bt-l2cap( 6184): L2CAP - st: CONFIG evt: 24
,W/bt-l2cap( 6184): L2CAP - st: CONFIG evt: 14
W/bt-l2cap( 6184): L2CAP - st: CONFIG evt: 25
W/bt-l2cap( 6184): L2CAP-Upper layer Config_Rsp,Local CID: 0x0044,Remote CID: 0x0047,PSM: 1,our MTU present:1,our MTU:672
W/bt-l2cap( 6184): L2CAP - st: CONFIG evt: 15
W/bt-l2cap( 6184): L2CAP-peer_Config_Rsp,Local CID: 0x0044,Remote CID: 0x0047,PSM: 1,peer MTU present: 0,peer MTU: 672
,W/bt-l2cap( 6184): L2CA_DisconnectRsp()  CID: 0x0044
W/bt-l2cap( 6184): L2CAP - st: W4_L2CA_DISC_RSP evt: 28
,E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-55 f=2462 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:2999] from screen [on:0 period:1603784220] gl rssi=-55 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-55 f=2462 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:1603784221] gl rssi=-55 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
,V/AlarmManager( 1030): RTC_WAKEUP set : Alarm{302f1426 type 0 when 1449007759516 com.android.vending} when 1449007759516
,V/SIM_STK ( 1030): Menu title from STK is T-Mobile
,V/GLSActivity( 2125): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2125): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 2125): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2125): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2125): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2125): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/Finsky  ( 7119): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 7119): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 7119): [1] 5.onFinished: Giving up after 6 failures.
,E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-55 f=2462 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:1603787238] gl rssi=-55 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-55 f=2462 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:1603787241] gl rssi=-55 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
,D/sensors_hal_Time( 1030): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1030): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1030): tsOffsetIs: Apps: 488784697942; DSPS: 16157093; Offset : -4304278705
,E/bt-btm  ( 6184): btm_sec_disconnected - Clearing Pending flag
W/bt-l2cap( 6184): L2CA_SetDesireRole() new:x0, disallow_switch:0
D/WifiServerServiceExt( 1030): Connected BT device : -2
I/BluetoothMapService( 6184): onReceive: android.bluetooth.device.action.ACL_DISCONNECTED
,V/BluetoothPbapReceiver( 6184): PbapReceiver onReceive 
V/BluetoothPbapReceiver( 6184): ***********action = android.bluetooth.device.action.ACL_DISCONNECTED
V/BluetoothPbapReceiver( 6184): ***********Calling start service!!!! with action = null
,V/BluetoothPbapService( 6184): action: android.bluetooth.device.action.ACL_DISCONNECTED
V/BluetoothPbapService( 6184): state: -2147483648
D/LGBluetoothPowerSaveListener( 7322): [BTUI] ACL disconnected => AclLinkCount = 0
,I/BTConnectionReceiver( 4198): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=E0:DB:10:14:E2:C0, alias=null, name=Note4-1, majorDeviceClass=0, deviceClass=0]
,I/BluetoothClassifier( 4198): Bluetooth Device Name: Note4-1
D/btif_config_util( 6184): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-55 f=2462 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:1603790262] gl rssi=-55 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-55 f=2462 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:1603790265] gl rssi=-55 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-55 f=2462 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:1603793288] gl rssi=-55 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-55 f=2462 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:1603793291] gl rssi=-55 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-55 f=2462 sc=60 link=72 tx=1.0, 0.0, 0.0  rx=0.5 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:1603796315] gl rssi=-55 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-55 f=2462 sc=60 link=72 tx=1.0, 0.0, 0.0  rx=0.5 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:1603796325] gl rssi=-55 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
W/bt-l2cap( 6184): l2c_link_hci_conn_req:current link_role= 0
,W/bt-btm  ( 6184): btm_acl_role_changed: BDA: e0-db-10-14-e2-c0
W/bt-btm  ( 6184): btm_acl_role_changed: New role: 0
,W/bt-btm  ( 6184): btm_acl_created hci_handle=6 link_role=1  transport=1
W/bt-btm  ( 6184): btm_acl_created hci_handle=6 link_role=0  transport=1
W/bt-btif ( 6184): info:x10
W/bt-l2cap( 6184): L2CA_SetDesireRole() new:x0, disallow_switch:0
,D/        ( 6184): remote version info [e0:db:10:14:e2:c0]: 7, f, 2205
,W/bt-btm  ( 6184): btm_read_remote_version_complete: BDA: e0-db-10-14-e2-c0
W/bt-btm  ( 6184): btm_read_remote_version_complete lmp_version 7 manufacturer 15 lmp_subversion 8709
,D/WifiServerServiceExt( 1030): Connected BT device : -1
,W/bt-btm  ( 6184): btm_process_remote_ext_features_page 0: BDA: e0-db-10-14-e2-c0
W/bt-btm  ( 6184): ext_features_complt page_num:1 f[0]:x07, sm4:11, pend:0
W/bt-btm  ( 6184): btm_process_remote_ext_features_page 1: BDA: e0-db-10-14-e2-c0
,D/LGBluetoothPowerSaveListener( 7322): [BTUI] ACL connected => AclLinkCount = 1
,I/BTConnectionReceiver( 4198): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=E0:DB:10:14:E2:C0, alias=null, name=Note4-1, majorDeviceClass=0, deviceClass=0]
,I/BluetoothClassifier( 4198): Bluetooth Device Name: Note4-1
W/bt-l2cap( 6184): L2CAP - st: CLOSED evt: 10
W/bt-l2cap( 6184): L2CAP - st: TERM_W4_SEC_COMP evt: 7
W/bt-l2cap( 6184): L2CA_ErtmConnectRsp()  CID: 0x0045  Result: 0  Status: 0  BDA: e0db1014e2c0  p_ertm_info:0x00000000
W/bt-l2cap( 6184): L2CAP - st: W4_L2CA_CON_RSP evt: 22
W/bt-l2cap( 6184): L2CAP - st: CONFIG evt: 24
,W/bt-l2cap( 6184): L2CAP - st: CONFIG evt: 14
,W/bt-l2cap( 6184): L2CAP - st: CONFIG evt: 25
W/bt-l2cap( 6184): L2CAP-Upper layer Config_Rsp,Local CID: 0x0045,Remote CID: 0x0048,PSM: 1,our MTU present:1,our MTU:672
W/bt-l2cap( 6184): L2CAP - st: CONFIG evt: 15
W/bt-l2cap( 6184): L2CAP-peer_Config_Rsp,Local CID: 0x0045,Remote CID: 0x0048,PSM: 1,peer MTU present: 0,peer MTU: 672
W/bt-l2cap( 6184): L2CA_DisconnectRsp()  CID: 0x0045
W/bt-l2cap( 6184): L2CAP - st: W4_L2CA_DISC_RSP evt: 28
,E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-55 f=2462 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.3 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:1603799347] gl rssi=-55 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-55 f=2462 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.3 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:1603799350] gl rssi=-55 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
,E/bt-btm  ( 6184): btm_sec_disconnected - Clearing Pending flag
W/bt-l2cap( 6184): L2CA_SetDesireRole() new:x0, disallow_switch:0
,D/WifiServerServiceExt( 1030): Connected BT device : -2
I/BluetoothMapService( 6184): onReceive: android.bluetooth.device.action.ACL_DISCONNECTED
,V/BluetoothPbapReceiver( 6184): PbapReceiver onReceive 
V/BluetoothPbapReceiver( 6184): ***********action = android.bluetooth.device.action.ACL_DISCONNECTED
V/BluetoothPbapReceiver( 6184): ***********Calling start service!!!! with action = null
V/BluetoothPbapService( 6184): action: android.bluetooth.device.action.ACL_DISCONNECTED
V/BluetoothPbapService( 6184): state: -2147483648
D/LGBluetoothPowerSaveListener( 7322): [BTUI] ACL disconnected => AclLinkCount = 0
,I/BTConnectionReceiver( 4198): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=E0:DB:10:14:E2:C0, alias=null, name=Note4-1, majorDeviceClass=0, deviceClass=0]
,I/BluetoothClassifier( 4198): Bluetooth Device Name: Note4-1
V/AlarmManager( 1030): ELAPSED_WAKEUP set : Alarm{2f4cde98 type 2 when 503423 android} when 503423
,I/BooksSync( 7886): Starting books sync
,D/BooksSync( 7886): started syncMyEbooks
,V/GLSActivity( 2125): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-55 f=2462 sc=60 link=72 tx=0.3, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:2999] from screen [on:0 period:1603802367] gl rssi=-55 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-55 f=2462 sc=60 link=72 tx=0.3, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:1603802370] gl rssi=-55 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
I/GLSUser ( 2125): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2125): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 2125): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2125): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2125): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1030): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1030): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1030): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1030): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1030): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
W/GLSActivity( 2125): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2125): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2125): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2125): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2125): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2125): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2125): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 7886): Authentication error
E/BooksAccountManager( 7886): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7886): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 7886): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 7886): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 7886): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 7886): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 7886): null auth token
W/ResourcesManager( 1396): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 1396): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
D/LgeQuickCoverNLService( 1396): onNotificationPosted
,D/SmartCoverUpdateMonitor( 1396): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1396): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1396): handleNotificationPosted(true)
D/QuickCircle( 1396): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1396): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1396): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1396): post do just update job
D/LgeQuickCoverNotificationData( 1396): showAll3
D/LgeQuickCoverNotificationData( 1396): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1396): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
D/LgeQuickCoverNotificationData( 1396): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
E/LgeQuickCoverOverlayWindow( 1396): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1396): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1396): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1396): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1396): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1396): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1396): isNotificationForCurrentUser : true
W/ResourcesManager( 1396): Asset path '/system/framework/com.lge.systemui.jar' does not exist or contains no resources.
,W/ResourcesManager( 1396): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
E/LgeQuickCoverOverlayWindow( 1396): updateNotificationData: count=3
D/QuickStatusbarLayout( 1396): Notification difference=198
D/QuickStatusbarLayout( 1396): child = android.widget.LinearLayout{2154d13 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
W/ApiaryClient( 7886): Error response from books API: {
W/ApiaryClient( 7886):  "error": {
W/ApiaryClient( 7886):   "errors": [
W/ApiaryClient( 7886):    {
W/ApiaryClient( 7886):     "domain": "global",
W/ApiaryClient( 7886):     "reason": "required",
W/ApiaryClient( 7886):     "message": "Login Required",
W/ApiaryClient( 7886):     "locationType": "header",
W/ApiaryClient( 7886):     "location": "Authorization"
W/ApiaryClient( 7886):    }
W/ApiaryClient( 7886):   ],
W/ApiaryClient( 7886):   "code": 401,
W/ApiaryClient( 7886):   "message": "Login Required"
W/ApiaryClient( 7886):  }
W/ApiaryClient( 7886): }
W/ApiaryClient( 7886): errCount = 1: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7886): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=2533423556118443181&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7886): Headers:
W/ApiaryClient( 7886): accept-encoding: [gzip]
W/ApiaryClient( 7886): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 7886): gdata-version: 2
,D/btif_config_util( 6184): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,V/GLSActivity( 2125): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2125): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2125): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2125): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 2125): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2125): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     ( 2125): Explicit concurrent mark sweep GC freed 30425(1766KB) AllocSpace objects, 14(2016KB) LOS objects, 50% free, 30MB/62MB, paused 2.462ms total 60.520ms
,V/NotificationService( 1030): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1030): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1030): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1030): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1030): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1396): onNotificationPosted
,D/SmartCoverUpdateMonitor( 1396): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1396): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1396): handleNotificationPosted(true)
D/QuickCircle( 1396): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1396): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1396): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1396): post do just update job
D/LgeQuickCoverNotificationData( 1396): showAll3
D/LgeQuickCoverNotificationData( 1396): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1396): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
D/LgeQuickCoverNotificationData( 1396): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
E/LgeQuickCoverOverlayWindow( 1396): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1396): [native noti] inex =  0
,D/LgeQuickCoverNotificationData( 1396): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1396): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1396): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1396): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1396): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1396): updateNotificationData: count=3
W/GLSActivity( 2125): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2125): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2125): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2125): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2125): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2125): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2125): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 7886): Authentication error
E/BooksAccountManager( 7886): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7886): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 7886): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 7886): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 7886): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 7886): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 7886): null auth token
D/QuickStatusbarLayout( 1396): Notification difference=198
D/QuickStatusbarLayout( 1396): child = android.widget.LinearLayout{2154d13 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
W/ApiaryClient( 7886): Error response from books API: {
W/ApiaryClient( 7886):  "error": {
W/ApiaryClient( 7886):   "errors": [
W/ApiaryClient( 7886):    {
W/ApiaryClient( 7886):     "domain": "global",
W/ApiaryClient( 7886):     "reason": "required",
W/ApiaryClient( 7886):     "message": "Login Required",
W/ApiaryClient( 7886):     "locationType": "header",
W/ApiaryClient( 7886):     "location": "Authorization"
W/ApiaryClient( 7886):    }
W/ApiaryClient( 7886):   ],
W/ApiaryClient( 7886):   "code": 401,
W/ApiaryClient( 7886):   "message": "Login Required"
W/ApiaryClient( 7886):  }
W/ApiaryClient( 7886): }
,W/ApiaryClient( 7886): errCount = 2: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7886): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=2533423556118443181&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7886): Headers:
W/ApiaryClient( 7886): accept-encoding: [gzip]
W/ApiaryClient( 7886): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 7886): gdata-version: 2
V/GLSActivity( 2125): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2125): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2125): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2125): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2125): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2125): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1030): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1030): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1030): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1030): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1030): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1396): onNotificationPosted
,D/SmartCoverUpdateMonitor( 1396): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1396): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1396): handleNotificationPosted(true)
D/QuickCircle( 1396): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1396): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1396): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1396): post do just update job
D/LgeQuickCoverNotificationData( 1396): showAll3
D/LgeQuickCoverNotificationData( 1396): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1396): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
D/LgeQuickCoverNotificationData( 1396): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
E/LgeQuickCoverOverlayWindow( 1396): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1396): [native noti] inex =  0
,D/LgeQuickCoverNotificationData( 1396): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1396): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1396): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1396): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1396): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1396): updateNotificationData: count=3
W/GLSActivity( 2125): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2125): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2125): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2125): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2125): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2125): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2125): 	at android.os.Binder.execTransact(Binder.java:446)
E/BooksAccountManager( 7886): Authentication error
E/BooksAccountManager( 7886): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7886): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 7886): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 7886): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 7886): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 7886): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 7886): null auth token
,D/QuickStatusbarLayout( 1396): Notification difference=198
D/QuickStatusbarLayout( 1396): child = android.widget.LinearLayout{2154d13 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
W/ApiaryClient( 7886): Error response from books API: {
W/ApiaryClient( 7886):  "error": {
W/ApiaryClient( 7886):   "errors": [
W/ApiaryClient( 7886):    {
W/ApiaryClient( 7886):     "domain": "global",
W/ApiaryClient( 7886):     "reason": "required",
W/ApiaryClient( 7886):     "message": "Login Required",
W/ApiaryClient( 7886):     "locationType": "header",
W/ApiaryClient( 7886):     "location": "Authorization"
W/ApiaryClient( 7886):    }
W/ApiaryClient( 7886):   ],
W/ApiaryClient( 7886):   "code": 401,
W/ApiaryClient( 7886):   "message": "Login Required"
W/ApiaryClient( 7886):  }
W/ApiaryClient( 7886): }
,W/ApiaryClient( 7886): errCount = 3: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7886): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=2533423556118443181&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7886): Headers:
W/ApiaryClient( 7886): accept-encoding: [gzip]
W/ApiaryClient( 7886): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 7886): gdata-version: 2
E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-55 f=2462 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3005] from screen [on:0 period:1603805390] gl rssi=-55 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-55 f=2462 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:1603805393] gl rssi=-55 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
,E/BooksSync( 7886): Soft error: 
E/BooksSync( 7886): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 7886): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=2533423556118443181&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 7886): Headers:
E/BooksSync( 7886): accept-encoding: [gzip]
E/BooksSync( 7886): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 7886): gdata-version: 2
E/BooksSync( 7886): 
E/BooksSync( 7886): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 7886): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 7886): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 7886): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 7886): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 7886): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 7886): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 7886): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 7886): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 7886): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 7886): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 7886): {
E/BooksSync( 7886):  "error": {
E/BooksSync( 7886):   "errors": [
E/BooksSync( 7886):    {
E/BooksSync( 7886):     "domain": "global",
E/BooksSync( 7886):     "reason": "required",
E/BooksSync( 7886):     "message": "Login Required",
E/BooksSync( 7886):     "locationType": "header",
E/BooksSync( 7886):     "location": "Authorization"
E/BooksSync( 7886):    }
E/BooksSync( 7886):   ],
E/BooksSync( 7886):   "code": 401,
E/BooksSync( 7886):   "message": "Login Required"
E/BooksSync( 7886):  }
E/BooksSync( 7886): }
E/BooksSync( 7886): 
E/BooksSync( 7886): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 7886): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 7886): 	... 8 more
,E/BooksSync( 7886): Sync error
E/BooksSync( 7886): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 7886): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=2533423556118443181&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 7886): Headers:
E/BooksSync( 7886): accept-encoding: [gzip]
E/BooksSync( 7886): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 7886): gdata-version: 2
E/BooksSync( 7886): 
E/BooksSync( 7886): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 7886): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 7886): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 7886): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 7886): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 7886): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 7886): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 7886): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 7886): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 7886): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 7886): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 7886): {
E/BooksSync( 7886):  "error": {
E/BooksSync( 7886):   "errors": [
E/BooksSync( 7886):    {
E/BooksSync( 7886):     "domain": "global",
E/BooksSync( 7886):     "reason": "required",
E/BooksSync( 7886):     "message": "Login Required",
E/BooksSync( 7886):     "locationType": "header",
E/BooksSync( 7886):     "location": "Authorization"
E/BooksSync( 7886):    }
E/BooksSync( 7886):   ],
E/BooksSync( 7886):   "code": 401,
E/BooksSync( 7886):   "message": "Login Required"
E/BooksSync( 7886):  }
E/BooksSync( 7886): }
E/BooksSync( 7886): 
E/BooksSync( 7886): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 7886): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 7886): 	... 8 more
I/BooksSync( 7886): Finished books sync
D/SyncManager( 1030): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 481230, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/sensors_hal_Time( 1030): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1030): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1030): tsOffsetIs: Apps: 508786795382; DSPS: 16812522; Offset : -4304287030
,W/bt-l2cap( 6184): l2c_link_hci_conn_req:current link_role= 0
,W/bt-btm  ( 6184): btm_acl_role_changed: BDA: e0-db-10-14-e2-c0
W/bt-btm  ( 6184): btm_acl_role_changed: New role: 0
,W/bt-btm  ( 6184): btm_acl_created hci_handle=7 link_role=1  transport=1
W/bt-btm  ( 6184): btm_acl_created hci_handle=7 link_role=0  transport=1
W/bt-btif ( 6184): info:x10
W/bt-l2cap( 6184): L2CA_SetDesireRole() new:x0, disallow_switch:0
,D/        ( 6184): remote version info [e0:db:10:14:e2:c0]: 7, f, 2205
D/WifiServerServiceExt( 1030): Connected BT device : -1
,D/LGBluetoothPowerSaveListener( 7322): [BTUI] ACL connected => AclLinkCount = 1
,I/BTConnectionReceiver( 4198): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=E0:DB:10:14:E2:C0, alias=null, name=Note4-1, majorDeviceClass=0, deviceClass=0]
,I/BluetoothClassifier( 4198): Bluetooth Device Name: Note4-1
W/bt-btm  ( 6184): btm_read_remote_version_complete: BDA: e0-db-10-14-e2-c0
,W/bt-btm  ( 6184): btm_read_remote_version_complete lmp_version 7 manufacturer 15 lmp_subversion 8709
E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-55 f=2462 sc=60 link=72 tx=4.6, 0.0, 0.0  rx=3.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:1603808436] gl rssi=-55 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-55 f=2462 sc=60 link=72 tx=4.6, 0.0, 0.0  rx=3.0 bcn=0 [on:0 tx:0 rx:0 period:13] from screen [on:0 period:1603808449] gl rssi=-55 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
W/bt-btm  ( 6184): btm_process_remote_ext_features_page 0: BDA: e0-db-10-14-e2-c0
W/bt-btm  ( 6184): ext_features_complt page_num:1 f[0]:x07, sm4:11, pend:0
W/bt-btm  ( 6184): btm_process_remote_ext_features_page 1: BDA: e0-db-10-14-e2-c0
,W/bt-l2cap( 6184): L2CAP - st: CLOSED evt: 10
W/bt-l2cap( 6184): L2CAP - st: TERM_W4_SEC_COMP evt: 7
W/bt-l2cap( 6184): L2CA_ErtmConnectRsp()  CID: 0x0046  Result: 0  Status: 0  BDA: e0db1014e2c0  p_ertm_info:0x00000000
W/bt-l2cap( 6184): L2CAP - st: W4_L2CA_CON_RSP evt: 22
W/bt-l2cap( 6184): L2CAP - st: CONFIG evt: 24
,W/bt-l2cap( 6184): L2CAP - st: CONFIG evt: 14
W/bt-l2cap( 6184): L2CAP - st: CONFIG evt: 25
W/bt-l2cap( 6184): L2CAP-Upper layer Config_Rsp,Local CID: 0x0046,Remote CID: 0x0049,PSM: 1,our MTU present:1,our MTU:672
,W/bt-l2cap( 6184): L2CAP - st: CONFIG evt: 15
,W/bt-l2cap( 6184): L2CAP-peer_Config_Rsp,Local CID: 0x0046,Remote CID: 0x0049,PSM: 1,peer MTU present: 0,peer MTU: 672
W/bt-l2cap( 6184): L2CA_DisconnectRsp()  CID: 0x0046
W/bt-l2cap( 6184): L2CAP - st: W4_L2CA_DISC_RSP evt: 28
,W/bt-btm  ( 6184): btm_acl_role_changed: BDA: e0-db-10-14-e2-c0
W/bt-btm  ( 6184): btm_acl_role_changed: New role: 1
E/bt-btm  ( 6184): tBTM_SEC_DEV:0xa039b218 rs_disc_pending=0
W/bt-btif ( 6184): bta_dm_check_av:0
,W/bt-btif ( 6184): btif_dm_cback : unhandled event (14)
E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-55 f=2462 sc=60 link=72 tx=2.3, 0.0, 0.0  rx=1.5 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:1603811466] gl rssi=-55 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-55 f=2462 sc=60 link=72 tx=2.3, 0.0, 0.0  rx=1.5 bcn=0 [on:0 tx:0 rx:0 period:11] from screen [on:0 period:1603811477] gl rssi=-55 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
E/bt-btm  ( 6184): btm_sec_disconnected - Clearing Pending flag
W/bt-l2cap( 6184): L2CA_SetDesireRole() new:x0, disallow_switch:0
,D/WifiServerServiceExt( 1030): Connected BT device : -2
,I/BluetoothMapService( 6184): onReceive: android.bluetooth.device.action.ACL_DISCONNECTED
,V/BluetoothPbapReceiver( 6184): PbapReceiver onReceive 
V/BluetoothPbapReceiver( 6184): ***********action = android.bluetooth.device.action.ACL_DISCONNECTED
V/BluetoothPbapReceiver( 6184): ***********Calling start service!!!! with action = null
,V/BluetoothPbapService( 6184): action: android.bluetooth.device.action.ACL_DISCONNECTED
V/BluetoothPbapService( 6184): state: -2147483648
D/LGBluetoothPowerSaveListener( 7322): [BTUI] ACL disconnected => AclLinkCount = 0
,I/BTConnectionReceiver( 4198): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=E0:DB:10:14:E2:C0, alias=null, name=Note4-1, majorDeviceClass=0, deviceClass=0]
,I/BluetoothClassifier( 4198): Bluetooth Device Name: Note4-1
D/btif_config_util( 6184): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-55 f=2462 sc=60 link=72 tx=1.1, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:1603814490] gl rssi=-55 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-55 f=2462 sc=60 link=72 tx=1.1, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:1603814493] gl rssi=-55 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-55 f=2462 sc=60 link=72 tx=0.6, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:1603817519] gl rssi=-55 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-55 f=2462 sc=60 link=72 tx=0.6, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:1603817522] gl rssi=-55 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-55 f=2462 sc=60 link=72 tx=1.3, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:1603820547] gl rssi=-55 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-55 f=2462 sc=60 link=72 tx=1.3, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:1603820550] gl rssi=-55 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
,I/[SystemUI]TimeTickManager( 1446): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1446): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1446): called onTimeUpdated()
I/[SystemUI]Clock( 1446): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1446): called onTimeUpdated()
I/[SystemUI]DateView( 1446): called onTimeUpdated()
I/[SystemUI]DateView( 1446): called onTimeUpdated()
,D/KeyguardUpdateMonitor( 1446): handleTimeUpdate
E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-55 f=2462 sc=60 link=72 tx=0.6, 0.0, 0.0  rx=0.3 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:1603823574] gl rssi=-55 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-55 f=2462 sc=60 link=72 tx=0.6, 0.0, 0.0  rx=0.3 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:1603823584] gl rssi=-55 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-55 f=2462 sc=60 link=72 tx=0.3, 0.0, 0.0  rx=0.2 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:1603826604] gl rssi=-55 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-55 f=2462 sc=60 link=72 tx=0.3, 0.0, 0.0  rx=0.2 bcn=0 [on:0 tx:0 rx:0 period:11] from screen [on:0 period:1603826615] gl rssi=-55 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
D/sensors_hal_Time( 1030): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1030): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1030): tsOffsetIs: Apps: 528788712978; DSPS: 17467945; Offset : -4304292197
,E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-55 f=2462 sc=60 link=72 tx=0.2, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:1603829636] gl rssi=-55 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-55 f=2462 sc=60 link=72 tx=0.2, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:11] from screen [on:0 period:1603829647] gl rssi=-55 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
D/PowerManagerServiceEx( 1030): acquireWakeLockInternal: lock=174419834, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1030
,V/AlarmManager( 1030): ELAPSED_WAKEUP set : Alarm{4139dc2 type 2 when 533466 android} when 533466
D/[Concierge]Service( 2596): onStartCommand(). Type : 9
,D/PowerManagerServiceEx( 1030): releaseWakeLockInternal: lock=174419834 [*alarm*], flags=0x0
,E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-55 f=2462 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:1603832664] gl rssi=-55 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-55 f=2462 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:11] from screen [on:0 period:1603832675] gl rssi=-55 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-55 f=2462 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:1603835695] gl rssi=-55 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-55 f=2462 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:11] from screen [on:0 period:1603835706] gl rssi=-55 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-55 f=2462 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:1603838728] gl rssi=-55 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-55 f=2462 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:1603838731] gl rssi=-55 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-55 f=2462 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:1603841759] gl rssi=-55 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-55 f=2462 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:1603841762] gl rssi=-55 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-55 f=2462 sc=60 link=72 tx=3.0, 0.0, 0.0  rx=2.5 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:1603844785] gl rssi=-55 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-55 f=2462 sc=60 link=72 tx=3.0, 0.0, 0.0  rx=2.5 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:1603844795] gl rssi=-55 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
D/sensors_hal_Time( 1030): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1030): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1030): tsOffsetIs: Apps: 548791201878; DSPS: 18123386; Offset : -4304275143
,E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-55 f=2462 sc=60 link=72 tx=3.5, 0.0, 0.0  rx=3.3 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:1603847809] gl rssi=-55 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-55 f=2462 sc=60 link=72 tx=3.5, 0.0, 0.0  rx=3.3 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:1603847812] gl rssi=-55 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-55 f=2462 sc=60 link=72 tx=1.8, 0.0, 0.0  rx=1.6 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:1603850838] gl rssi=-55 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-55 f=2462 sc=60 link=72 tx=1.8, 0.0, 0.0  rx=1.6 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:1603850841] gl rssi=-55 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-55 f=2462 sc=60 link=72 tx=0.9, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:1603853868] gl rssi=-55 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-55 f=2462 sc=60 link=72 tx=0.9, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:1603853871] gl rssi=-55 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
,W/bt-l2cap( 6184): l2c_link_hci_conn_req:current link_role= 1
,W/bt-btm  ( 6184): btm_acl_created hci_handle=8 link_role=1  transport=1
W/bt-btm  ( 6184): btm_acl_created hci_handle=8 link_role=1  transport=1
,W/bt-btm  ( 6184): btm_read_remote_version_complete: BDA: 08-ec-a9-50-75-41
W/bt-btm  ( 6184): btm_read_remote_version_complete lmp_version 7 manufacturer 29 lmp_subversion 2003
,W/bt-l2cap( 6184): L2CAP - st: CLOSED evt: 10
W/bt-l2cap( 6184): L2CAP - st: TERM_W4_SEC_COMP evt: 7
W/bt-l2cap( 6184): L2CA_ErtmConnectRsp()  CID: 0x0047  Result: 0  Status: 0  BDA: 08eca9507541  p_ertm_info:0x00000000
W/bt-l2cap( 6184): L2CAP - st: W4_L2CA_CON_RSP evt: 22
W/bt-l2cap( 6184): L2CAP - st: CONFIG evt: 24
,W/bt-btm  ( 6184): btm_process_remote_ext_features_page 0: BDA: 08-ec-a9-50-75-41
W/bt-btm  ( 6184): ext_features_complt page_num:1 f[0]:x07, sm4:11, pend:0
W/bt-btm  ( 6184): btm_process_remote_ext_features_page 1: BDA: 08-ec-a9-50-75-41
W/bt-btif ( 6184): info:x10
W/bt-l2cap( 6184): L2CA_SetDesireRole() new:x0, disallow_switch:0
D/        ( 6184): remote version info [08:ec:a9:50:75:41]: 7, 1d, 7d3
E/BluetoothRemoteDevices( 6184): aclStateChangeCallback: Device is NULL
D/LGBluetoothServiceUtil( 6184): [BTUI] sendBroadcastAclConnection: Connected, but device is null, sendBroadcast
W/bt-l2cap( 6184): L2CAP - st: CONFIG evt: 14
W/bt-l2cap( 6184): L2CAP - st: CONFIG evt: 25
W/bt-l2cap( 6184): L2CAP-Upper layer Config_Rsp,Local CID: 0x0047,Remote CID: 0x0045,PSM: 1,our MTU present:1,our MTU:672
W/bt-l2cap( 6184): L2CAP - st: CONFIG evt: 15
W/bt-l2cap( 6184): L2CAP-peer_Config_Rsp,Local CID: 0x0047,Remote CID: 0x0045,PSM: 1,peer MTU present: 0,peer MTU: 672
,W/bt-l2cap( 6184): L2CA_DisconnectRsp()  CID: 0x0047
W/bt-l2cap( 6184): L2CAP - st: W4_L2CA_DISC_RSP evt: 28
,D/LGBluetoothPowerSaveListener( 7322): [BTUI] ACL connected => AclLinkCount = 1
E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-55 f=2462 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:1603856898] gl rssi=-55 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-55 f=2462 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:1603856899] gl rssi=-55 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-55 f=2462 sc=60 link=72 tx=0.2, 0.0, 0.0  rx=0.2 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:1603859918] gl rssi=-55 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-55 f=2462 sc=60 link=72 tx=0.2, 0.0, 0.0  rx=0.2 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:1603859921] gl rssi=-55 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
,E/bt-btm  ( 6184): btm_sec_disconnected - Clearing Pending flag
W/bt-l2cap( 6184): L2CA_SetDesireRole() new:x0, disallow_switch:0
,D/WifiServerServiceExt( 1030): Connected BT device : -3
I/BluetoothMapService( 6184): onReceive: android.bluetooth.device.action.ACL_DISCONNECTED
,V/BluetoothPbapReceiver( 6184): PbapReceiver onReceive 
V/BluetoothPbapReceiver( 6184): ***********action = android.bluetooth.device.action.ACL_DISCONNECTED
V/BluetoothPbapReceiver( 6184): ***********Calling start service!!!! with action = null
V/BluetoothPbapService( 6184): action: android.bluetooth.device.action.ACL_DISCONNECTED
V/BluetoothPbapService( 6184): state: -2147483648
D/LGBluetoothPowerSaveListener( 7322): [BTUI] ACL disconnected => AclLinkCount = 0
,I/BTConnectionReceiver( 4198): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=08:EC:A9:50:75:41, alias=null, name=A3-1, majorDeviceClass=0, deviceClass=0]
,I/BluetoothClassifier( 4198): Bluetooth Device Name: A3-1
D/btif_config_util( 6184): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-55 f=2462 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3000] from screen [on:0 period:1603862938] gl rssi=-55 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-55 f=2462 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:1603862939] gl rssi=-55 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-55 f=2462 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:1603865957] gl rssi=-55 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-55 f=2462 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:4] from screen [on:0 period:1603865961] gl rssi=-55 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
,W/bt-l2cap( 6184): l2c_link_hci_conn_req:current link_role= 0
,W/bt-btm  ( 6184): btm_acl_role_changed: BDA: 08-ec-a9-50-75-41
W/bt-btm  ( 6184): btm_acl_role_changed: New role: 0
,W/bt-btm  ( 6184): btm_acl_created hci_handle=9 link_role=1  transport=1
W/bt-btm  ( 6184): btm_acl_created hci_handle=9 link_role=0  transport=1
W/bt-btif ( 6184): info:x10
W/bt-l2cap( 6184): L2CA_SetDesireRole() new:x0, disallow_switch:0
,D/        ( 6184): remote version info [08:ec:a9:50:75:41]: 7, 1d, 7d3
D/WifiServerServiceExt( 1030): Connected BT device : -2
,W/bt-btm  ( 6184): btm_read_remote_version_complete: BDA: 08-ec-a9-50-75-41
W/bt-btm  ( 6184): btm_read_remote_version_complete lmp_version 7 manufacturer 29 lmp_subversion 2003
W/bt-btm  ( 6184): btm_process_remote_ext_features_page 0: BDA: 08-ec-a9-50-75-41
W/bt-btm  ( 6184): ext_features_complt page_num:1 f[0]:x07, sm4:11, pend:0
W/bt-btm  ( 6184): btm_process_remote_ext_features_page 1: BDA: 08-ec-a9-50-75-41
,D/LGBluetoothPowerSaveListener( 7322): [BTUI] ACL connected => AclLinkCount = 1
,I/BTConnectionReceiver( 4198): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=08:EC:A9:50:75:41, alias=null, name=A3-1, majorDeviceClass=0, deviceClass=0]
,I/BluetoothClassifier( 4198): Bluetooth Device Name: A3-1
,W/bt-l2cap( 6184): L2CAP - st: CLOSED evt: 10
W/bt-l2cap( 6184): L2CAP - st: TERM_W4_SEC_COMP evt: 7
W/bt-l2cap( 6184): L2CA_ErtmConnectRsp()  CID: 0x0048  Result: 0  Status: 0  BDA: 08eca9507541  p_ertm_info:0x00000000
W/bt-l2cap( 6184): L2CAP - st: W4_L2CA_CON_RSP evt: 22
W/bt-l2cap( 6184): L2CAP - st: CONFIG evt: 24
,W/bt-l2cap( 6184): L2CAP - st: CONFIG evt: 14
W/bt-l2cap( 6184): L2CAP - st: CONFIG evt: 25
W/bt-l2cap( 6184): L2CAP-Upper layer Config_Rsp,Local CID: 0x0048,Remote CID: 0x0046,PSM: 1,our MTU present:1,our MTU:672
W/bt-l2cap( 6184): L2CAP - st: CONFIG evt: 15
W/bt-l2cap( 6184): L2CAP-peer_Config_Rsp,Local CID: 0x0048,Remote CID: 0x0046,PSM: 1,peer MTU present: 0,peer MTU: 672
,W/bt-l2cap( 6184): L2CA_DisconnectRsp()  CID: 0x0048
W/bt-l2cap( 6184): L2CAP - st: W4_L2CA_DISC_RSP evt: 28
D/sensors_hal_Time( 1030): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1030): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1030): tsOffsetIs: Apps: 568793377078; DSPS: 18778817; Offset : -4304266691
,E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-55 f=2462 sc=60 link=72 tx=3.0, 0.0, 0.0  rx=3.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:1603868987] gl rssi=-55 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-55 f=2462 sc=60 link=72 tx=3.0, 0.0, 0.0  rx=3.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:1603868990] gl rssi=-55 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
,E/bt-btm  ( 6184): btm_sec_disconnected - Clearing Pending flag
W/bt-l2cap( 6184): L2CA_SetDesireRole() new:x0, disallow_switch:0
,D/WifiServerServiceExt( 1030): Connected BT device : -3
I/BluetoothMapService( 6184): onReceive: android.bluetooth.device.action.ACL_DISCONNECTED
,V/BluetoothPbapReceiver( 6184): PbapReceiver onReceive 
V/BluetoothPbapReceiver( 6184): ***********action = android.bluetooth.device.action.ACL_DISCONNECTED
V/BluetoothPbapReceiver( 6184): ***********Calling start service!!!! with action = null
V/BluetoothPbapService( 6184): action: android.bluetooth.device.action.ACL_DISCONNECTED
V/BluetoothPbapService( 6184): state: -2147483648
D/LGBluetoothPowerSaveListener( 7322): [BTUI] ACL disconnected => AclLinkCount = 0
,I/BTConnectionReceiver( 4198): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=08:EC:A9:50:75:41, alias=null, name=A3-1, majorDeviceClass=0, deviceClass=0]
,I/BluetoothClassifier( 4198): Bluetooth Device Name: A3-1
V/AlarmManager( 1030): ELAPSED_WAKEUP set : Alarm{3c7777d3 type 2 when 572641 android} when 572641
,I/BooksSync( 7886): Starting books sync
,I/art     ( 1030): Explicit concurrent mark sweep GC freed 65509(2MB) AllocSpace objects, 8(896KB) LOS objects, 33% free, 44MB/67MB, paused 3.056ms total 161.655ms
,D/BooksSync( 7886): started syncMyEbooks
V/GLSActivity( 2125): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2125): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2125): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2125): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2125): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2125): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1030): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1030): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1030): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1030): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1030): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1396): onNotificationPosted
W/GLSActivity( 2125): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2125): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2125): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2125): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2125): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2125): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2125): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 7886): Authentication error
E/BooksAccountManager( 7886): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7886): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 7886): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 7886): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 7886): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 7886): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 7886): null auth token
,D/SmartCoverUpdateMonitor( 1396): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1396): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1396): handleNotificationPosted(true)
D/QuickCircle( 1396): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1396): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1396): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1396): post do just update job
D/LgeQuickCoverNotificationData( 1396): showAll3
D/LgeQuickCoverNotificationData( 1396): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1396): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
D/LgeQuickCoverNotificationData( 1396): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
E/LgeQuickCoverOverlayWindow( 1396): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1396): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1396): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1396): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1396): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1396): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1396): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1396): updateNotificationData: count=3
D/QuickStatusbarLayout( 1396): Notification difference=198
D/QuickStatusbarLayout( 1396): child = android.widget.LinearLayout{2154d13 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,W/ApiaryClient( 7886): Error response from books API: {
W/ApiaryClient( 7886):  "error": {
W/ApiaryClient( 7886):   "errors": [
W/ApiaryClient( 7886):    {
W/ApiaryClient( 7886):     "domain": "global",
W/ApiaryClient( 7886):     "reason": "required",
W/ApiaryClient( 7886):     "message": "Login Required",
W/ApiaryClient( 7886):     "locationType": "header",
W/ApiaryClient( 7886):     "location": "Authorization"
W/ApiaryClient( 7886):    }
W/ApiaryClient( 7886):   ],
W/ApiaryClient( 7886):   "code": 401,
W/ApiaryClient( 7886):   "message": "Login Required"
W/ApiaryClient( 7886):  }
W/ApiaryClient( 7886): }
,W/ApiaryClient( 7886): errCount = 1: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7886): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-4883896957524325323&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7886): Headers:
W/ApiaryClient( 7886): accept-encoding: [gzip]
W/ApiaryClient( 7886): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 7886): gdata-version: 2
,E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-55 f=2462 sc=60 link=72 tx=1.5, 0.0, 0.0  rx=1.5 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:1603872010] gl rssi=-55 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-55 f=2462 sc=60 link=72 tx=1.5, 0.0, 0.0  rx=1.5 bcn=0 [on:0 tx:0 rx:0 period:4] from screen [on:0 period:1603872014] gl rssi=-55 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
V/GLSActivity( 2125): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2125): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2125): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2125): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2125): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2125): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1030): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1030): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1030): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1030): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1030): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,D/LgeQuickCoverNLService( 1396): onNotificationPosted
,D/SmartCoverUpdateMonitor( 1396): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1396): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1396): handleNotificationPosted(true)
D/QuickCircle( 1396): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1396): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1396): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1396): post do just update job
D/LgeQuickCoverNotificationData( 1396): showAll3
D/LgeQuickCoverNotificationData( 1396): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1396): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
D/LgeQuickCoverNotificationData( 1396): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
E/LgeQuickCoverOverlayWindow( 1396): showNotificationWithSetupData: display=false
,D/LgeQuickCoverOverlayWindow( 1396): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1396): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1396): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1396): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1396): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1396): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1396): updateNotificationData: count=3
W/GLSActivity( 2125): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2125): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2125): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2125): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2125): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2125): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2125): 	at android.os.Binder.execTransact(Binder.java:446)
E/BooksAccountManager( 7886): Authentication error
E/BooksAccountManager( 7886): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7886): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 7886): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 7886): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 7886): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 7886): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 7886): null auth token
,D/QuickStatusbarLayout( 1396): Notification difference=198
D/QuickStatusbarLayout( 1396): child = android.widget.LinearLayout{2154d13 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
D/btif_config_util( 6184): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,W/ApiaryClient( 7886): Error response from books API: {
W/ApiaryClient( 7886):  "error": {
W/ApiaryClient( 7886):   "errors": [
W/ApiaryClient( 7886):    {
W/ApiaryClient( 7886):     "domain": "global",
W/ApiaryClient( 7886):     "reason": "required",
W/ApiaryClient( 7886):     "message": "Login Required",
W/ApiaryClient( 7886):     "locationType": "header",
W/ApiaryClient( 7886):     "location": "Authorization"
W/ApiaryClient( 7886):    }
W/ApiaryClient( 7886):   ],
W/ApiaryClient( 7886):   "code": 401,
W/ApiaryClient( 7886):   "message": "Login Required"
W/ApiaryClient( 7886):  }
W/ApiaryClient( 7886): }
,W/ApiaryClient( 7886): errCount = 2: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7886): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-4883896957524325323&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7886): Headers:
W/ApiaryClient( 7886): accept-encoding: [gzip]
W/ApiaryClient( 7886): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 7886): gdata-version: 2
V/GLSActivity( 2125): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2125): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2125): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2125): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 2125): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2125): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1030): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1030): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1030): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1030): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1030): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,D/LgeQuickCoverNLService( 1396): onNotificationPosted
,D/SmartCoverUpdateMonitor( 1396): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1396): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1396): handleNotificationPosted(true)
D/QuickCircle( 1396): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1396): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1396): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1396): post do just update job
D/LgeQuickCoverNotificationData( 1396): showAll3
D/LgeQuickCoverNotificationData( 1396): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1396): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
D/LgeQuickCoverNotificationData( 1396): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
E/LgeQuickCoverOverlayWindow( 1396): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1396): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1396): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1396): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1396): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1396): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1396): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1396): updateNotificationData: count=3
W/GLSActivity( 2125): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2125): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2125): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2125): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2125): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2125): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2125): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 7886): Authentication error
E/BooksAccountManager( 7886): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7886): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 7886): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 7886): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 7886): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 7886): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 7886): null auth token
D/QuickStatusbarLayout( 1396): Notification difference=198
D/QuickStatusbarLayout( 1396): child = android.widget.LinearLayout{2154d13 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
W/ApiaryClient( 7886): Error response from books API: {
W/ApiaryClient( 7886):  "error": {
W/ApiaryClient( 7886):   "errors": [
W/ApiaryClient( 7886):    {
W/ApiaryClient( 7886):     "domain": "global",
W/ApiaryClient( 7886):     "reason": "required",
W/ApiaryClient( 7886):     "message": "Login Required",
W/ApiaryClient( 7886):     "locationType": "header",
W/ApiaryClient( 7886):     "location": "Authorization"
W/ApiaryClient( 7886):    }
W/ApiaryClient( 7886):   ],
W/ApiaryClient( 7886):   "code": 401,
W/ApiaryClient( 7886):   "message": "Login Required"
W/ApiaryClient( 7886):  }
W/ApiaryClient( 7886): }
,W/ApiaryClient( 7886): errCount = 3: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7886): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-4883896957524325323&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7886): Headers:
W/ApiaryClient( 7886): accept-encoding: [gzip]
W/ApiaryClient( 7886): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 7886): gdata-version: 2
E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-55 f=2462 sc=60 link=72 tx=2.3, 0.0, 0.0  rx=1.8 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:1603875025] gl rssi=-55 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-55 f=2462 sc=60 link=72 tx=2.3, 0.0, 0.0  rx=1.8 bcn=0 [on:0 tx:0 rx:0 period:11] from screen [on:0 period:1603875036] gl rssi=-55 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
E/BooksSync( 7886): Soft error: 
E/BooksSync( 7886): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 7886): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-4883896957524325323&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 7886): Headers:
E/BooksSync( 7886): accept-encoding: [gzip]
E/BooksSync( 7886): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 7886): gdata-version: 2
E/BooksSync( 7886): 
E/BooksSync( 7886): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 7886): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 7886): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 7886): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 7886): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 7886): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 7886): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 7886): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 7886): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 7886): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 7886): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 7886): {
E/BooksSync( 7886):  "error": {
E/BooksSync( 7886):   "errors": [
E/BooksSync( 7886):    {
E/BooksSync( 7886):     "domain": "global",
E/BooksSync( 7886):     "reason": "required",
E/BooksSync( 7886):     "message": "Login Required",
E/BooksSync( 7886):     "locationType": "header",
E/BooksSync( 7886):     "location": "Authorization"
E/BooksSync( 7886):    }
E/BooksSync( 7886):   ],
E/BooksSync( 7886):   "code": 401,
E/BooksSync( 7886):   "message": "Login Required"
E/BooksSync( 7886):  }
E/BooksSync( 7886): }
E/BooksSync( 7886): 
E/BooksSync( 7886): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 7886): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 7886): 	... 8 more
,E/BooksSync( 7886): Sync error
E/BooksSync( 7886): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 7886): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-4883896957524325323&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 7886): Headers:
E/BooksSync( 7886): accept-encoding: [gzip]
E/BooksSync( 7886): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 7886): gdata-version: 2
E/BooksSync( 7886): 
E/BooksSync( 7886): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 7886): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 7886): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 7886): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 7886): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 7886): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 7886): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 7886): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 7886): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 7886): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 7886): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 7886): {
E/BooksSync( 7886):  "error": {
E/BooksSync( 7886):   "errors": [
E/BooksSync( 7886):    {
E/BooksSync( 7886):     "domain": "global",
E/BooksSync( 7886):     "reason": "required",
E/BooksSync( 7886):     "message": "Login Required",
E/BooksSync( 7886):     "locationType": "header",
E/BooksSync( 7886):     "location": "Authorization"
E/BooksSync( 7886):    }
E/BooksSync( 7886):   ],
E/BooksSync( 7886):   "code": 401,
E/BooksSync( 7886):   "message": "Login Required"
E/BooksSync( 7886):  }
E/BooksSync( 7886): }
E/BooksSync( 7886): 
E/BooksSync( 7886): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 7886): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 7886): 	... 8 more
I/BooksSync( 7886): Finished books sync
D/SyncManager( 1030): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 572641, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-55 f=2462 sc=60 link=72 tx=4.1, 0.0, 0.0  rx=2.9 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:1603878053] gl rssi=-55 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-55 f=2462 sc=60 link=72 tx=4.1, 0.0, 0.0  rx=2.9 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:1603878063] gl rssi=-55 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
W/bt-l2cap( 6184): l2c_link_hci_conn_req:current link_role= 0
,W/bt-btm  ( 6184): btm_acl_role_changed: BDA: 08-ec-a9-50-75-41
W/bt-btm  ( 6184): btm_acl_role_changed: New role: 0
,W/bt-btm  ( 6184): btm_acl_created hci_handle=10 link_role=1  transport=1
,W/bt-btm  ( 6184): btm_acl_created hci_handle=10 link_role=0  transport=1
W/bt-btif ( 6184): info:x10
W/bt-l2cap( 6184): L2CA_SetDesireRole() new:x0, disallow_switch:0
,D/        ( 6184): remote version info [08:ec:a9:50:75:41]: 7, 1d, 7d3
D/WifiServerServiceExt( 1030): Connected BT device : -2
,W/bt-btm  ( 6184): btm_read_remote_version_complete: BDA: 08-ec-a9-50-75-41
W/bt-btm  ( 6184): btm_read_remote_version_complete lmp_version 7 manufacturer 29 lmp_subversion 2003
W/bt-btm  ( 6184): btm_process_remote_ext_features_page 0: BDA: 08-ec-a9-50-75-41
W/bt-btm  ( 6184): ext_features_complt page_num:1 f[0]:x07, sm4:11, pend:0
W/bt-btm  ( 6184): btm_process_remote_ext_features_page 1: BDA: 08-ec-a9-50-75-41
,D/LGBluetoothPowerSaveListener( 7322): [BTUI] ACL connected => AclLinkCount = 1
I/BTConnectionReceiver( 4198): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=08:EC:A9:50:75:41, alias=null, name=A3-1, majorDeviceClass=0, deviceClass=0]
,I/BluetoothClassifier( 4198): Bluetooth Device Name: A3-1
W/bt-l2cap( 6184): L2CAP - st: CLOSED evt: 10
W/bt-l2cap( 6184): L2CAP - st: TERM_W4_SEC_COMP evt: 7
W/bt-l2cap( 6184): L2CA_ErtmConnectRsp()  CID: 0x0049  Result: 0  Status: 0  BDA: 08eca9507541  p_ertm_info:0x00000000
W/bt-l2cap( 6184): L2CAP - st: W4_L2CA_CON_RSP evt: 22
W/bt-l2cap( 6184): L2CAP - st: CONFIG evt: 24
,W/bt-l2cap( 6184): L2CAP - st: CONFIG evt: 14
W/bt-l2cap( 6184): L2CAP - st: CONFIG evt: 25
W/bt-l2cap( 6184): L2CAP-Upper layer Config_Rsp,Local CID: 0x0049,Remote CID: 0x0047,PSM: 1,our MTU present:1,our MTU:672
W/bt-l2cap( 6184): L2CAP - st: CONFIG evt: 15
W/bt-l2cap( 6184): L2CAP-peer_Config_Rsp,Local CID: 0x0049,Remote CID: 0x0047,PSM: 1,peer MTU present: 0,peer MTU: 672
W/bt-l2cap( 6184): L2CA_DisconnectRsp()  CID: 0x0049
W/bt-l2cap( 6184): L2CAP - st: W4_L2CA_DISC_RSP evt: 28
,E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-55 f=2462 sc=60 link=72 tx=2.1, 0.0, 0.0  rx=1.4 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:1603881083] gl rssi=-55 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-55 f=2462 sc=60 link=72 tx=2.1, 0.0, 0.0  rx=1.4 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:1603881093] gl rssi=-55 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
I/[SystemUI]TimeTickManager( 1446): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1446): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1446): called onTimeUpdated()
I/[SystemUI]Clock( 1446): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1446): called onTimeUpdated()
I/[SystemUI]DateView( 1446): called onTimeUpdated()
I/[SystemUI]DateView( 1446): called onTimeUpdated()
,D/KeyguardUpdateMonitor( 1446): handleTimeUpdate
E/bt-btm  ( 6184): btm_sec_disconnected - Clearing Pending flag
W/bt-l2cap( 6184): L2CA_SetDesireRole() new:x0, disallow_switch:0
,D/WifiServerServiceExt( 1030): Connected BT device : -3
I/BluetoothMapService( 6184): onReceive: android.bluetooth.device.action.ACL_DISCONNECTED
,V/BluetoothPbapReceiver( 6184): PbapReceiver onReceive 
V/BluetoothPbapReceiver( 6184): ***********action = android.bluetooth.device.action.ACL_DISCONNECTED
V/BluetoothPbapReceiver( 6184): ***********Calling start service!!!! with action = null
V/BluetoothPbapService( 6184): action: android.bluetooth.device.action.ACL_DISCONNECTED
V/BluetoothPbapService( 6184): state: -2147483648
,D/LGBluetoothPowerSaveListener( 7322): [BTUI] ACL disconnected => AclLinkCount = 0
,I/BTConnectionReceiver( 4198): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=08:EC:A9:50:75:41, alias=null, name=A3-1, majorDeviceClass=0, deviceClass=0]
,I/BluetoothClassifier( 4198): Bluetooth Device Name: A3-1
,E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-54 f=2462 sc=60 link=72 tx=1.0, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:1603884109] gl rssi=-54 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-54 f=2462 sc=60 link=72 tx=1.0, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:1603884112] gl rssi=-54 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
,D/btif_config_util( 6184): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-54 f=2462 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:1603887138] gl rssi=-54 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-54 f=2462 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:1603887141] gl rssi=-54 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
,D/sensors_hal_Time( 1030): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1030): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1030): tsOffsetIs: Apps: 588795482226; DSPS: 19434246; Offset : -4304267309
,E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-54 f=2462 sc=60 link=72 tx=0.3, 0.0, 0.0  rx=0.2 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:1603890169] gl rssi=-54 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-54 f=2462 sc=60 link=72 tx=0.3, 0.0, 0.0  rx=0.2 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:1603890172] gl rssi=-54 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
,W/bt-l2cap( 6184): l2c_link_hci_conn_req:current link_role= 0
,W/bt-btm  ( 6184): btm_acl_role_changed: BDA: 08-ec-a9-50-75-41
,W/bt-btm  ( 6184): btm_acl_role_changed: New role: 0
,W/bt-btm  ( 6184): btm_acl_created hci_handle=11 link_role=1  transport=1
W/bt-btm  ( 6184): btm_acl_created hci_handle=11 link_role=0  transport=1
W/bt-btif ( 6184): info:x10
W/bt-l2cap( 6184): L2CA_SetDesireRole() new:x0, disallow_switch:0
D/        ( 6184): remote version info [08:ec:a9:50:75:41]: 7, 1d, 7d3
D/WifiServerServiceExt( 1030): Connected BT device : -2
D/LGBluetoothPowerSaveListener( 7322): [BTUI] ACL connected => AclLinkCount = 1
,I/BTConnectionReceiver( 4198): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=08:EC:A9:50:75:41, alias=null, name=A3-1, majorDeviceClass=0, deviceClass=0]
,I/BluetoothClassifier( 4198): Bluetooth Device Name: A3-1
W/bt-btm  ( 6184): btm_read_remote_version_complete: BDA: 08-ec-a9-50-75-41
W/bt-btm  ( 6184): btm_read_remote_version_complete lmp_version 7 manufacturer 29 lmp_subversion 2003
,W/bt-btm  ( 6184): btm_process_remote_ext_features_page 0: BDA: 08-ec-a9-50-75-41
W/bt-btm  ( 6184): ext_features_complt page_num:1 f[0]:x07, sm4:11, pend:0
W/bt-btm  ( 6184): btm_process_remote_ext_features_page 1: BDA: 08-ec-a9-50-75-41
,W/bt-l2cap( 6184): L2CAP - st: CLOSED evt: 10
W/bt-l2cap( 6184): L2CAP - st: TERM_W4_SEC_COMP evt: 7
W/bt-l2cap( 6184): L2CA_ErtmConnectRsp()  CID: 0x004a  Result: 0  Status: 0  BDA: 08eca9507541  p_ertm_info:0x00000000
W/bt-l2cap( 6184): L2CAP - st: W4_L2CA_CON_RSP evt: 22
W/bt-l2cap( 6184): L2CAP - st: CONFIG evt: 24
,W/bt-l2cap( 6184): L2CAP - st: CONFIG evt: 14
W/bt-l2cap( 6184): L2CAP - st: CONFIG evt: 25
W/bt-l2cap( 6184): L2CAP-Upper layer Config_Rsp,Local CID: 0x004a,Remote CID: 0x0048,PSM: 1,our MTU present:1,our MTU:672
W/bt-l2cap( 6184): L2CAP - st: CONFIG evt: 15
W/bt-l2cap( 6184): L2CAP-peer_Config_Rsp,Local CID: 0x004a,Remote CID: 0x0048,PSM: 1,peer MTU present: 0,peer MTU: 672
W/bt-l2cap( 6184): L2CA_DisconnectRsp()  CID: 0x004a
W/bt-l2cap( 6184): L2CAP - st: W4_L2CA_DISC_RSP evt: 28
,W/bt-btm  ( 6184): btm_acl_role_changed: BDA: 08-ec-a9-50-75-41
,W/bt-btm  ( 6184): btm_acl_role_changed: New role: 1
E/bt-btm  ( 6184): tBTM_SEC_DEV:0xa039b3e0 rs_disc_pending=0
W/bt-btif ( 6184): bta_dm_check_av:0
,W/bt-btif ( 6184): btif_dm_cback : unhandled event (14)
E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-54 f=2462 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:1603893195] gl rssi=-54 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-54 f=2462 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:12] from screen [on:0 period:1603893207] gl rssi=-54 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
E/bt-btm  ( 6184): btm_sec_disconnected - Clearing Pending flag
W/bt-l2cap( 6184): L2CA_SetDesireRole() new:x0, disallow_switch:0
,D/WifiServerServiceExt( 1030): Connected BT device : -3
I/BluetoothMapService( 6184): onReceive: android.bluetooth.device.action.ACL_DISCONNECTED
,V/BluetoothPbapReceiver( 6184): PbapReceiver onReceive 
V/BluetoothPbapReceiver( 6184): ***********action = android.bluetooth.device.action.ACL_DISCONNECTED
V/BluetoothPbapReceiver( 6184): ***********Calling start service!!!! with action = null
V/BluetoothPbapService( 6184): action: android.bluetooth.device.action.ACL_DISCONNECTED
V/BluetoothPbapService( 6184): state: -2147483648
D/LGBluetoothPowerSaveListener( 7322): [BTUI] ACL disconnected => AclLinkCount = 0
,I/BTConnectionReceiver( 4198): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=08:EC:A9:50:75:41, alias=null, name=A3-1, majorDeviceClass=0, deviceClass=0]
,I/BluetoothClassifier( 4198): Bluetooth Device Name: A3-1
,E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-54 f=2462 sc=60 link=72 tx=1.1, 0.0, 0.0  rx=0.5 bcn=0 [on:0 tx:0 rx:0 period:3007] from screen [on:0 period:1603896232] gl rssi=-54 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-54 f=2462 sc=60 link=72 tx=1.1, 0.0, 0.0  rx=0.5 bcn=0 [on:0 tx:0 rx:0 period:8] from screen [on:0 period:1603896240] gl rssi=-54 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
D/btif_config_util( 6184): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-54 f=2462 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.3 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:1603899256] gl rssi=-54 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-54 f=2462 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.3 bcn=0 [on:0 tx:0 rx:0 period:11] from screen [on:0 period:1603899267] gl rssi=-54 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
D/PowerManagerServiceEx( 1030): acquireWakeLockInternal: lock=174419834, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1030
,V/AlarmManager( 1030): ELAPSED_WAKEUP set : Alarm{25f322a5 type 2 when 602691 android} when 602691
D/[Concierge]Service( 2596): onStartCommand(). Type : 9
,D/PowerManagerServiceEx( 1030): releaseWakeLockInternal: lock=174419834 [*alarm*], flags=0x0
,E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-54 f=2462 sc=60 link=72 tx=0.3, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:1603902289] gl rssi=-54 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-54 f=2462 sc=60 link=72 tx=0.3, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:1603902292] gl rssi=-54 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-54 f=2462 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:1603905319] gl rssi=-54 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-54 f=2462 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:1603905322] gl rssi=-54 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
,W/bt-l2cap( 6184): l2c_link_hci_conn_req:current link_role= 0
,W/bt-btm  ( 6184): btm_acl_role_changed: BDA: 80-01-84-8a-b3-68
W/bt-btm  ( 6184): btm_acl_role_changed: New role: 0
,W/bt-btm  ( 6184): btm_acl_created hci_handle=12 link_role=1  transport=1
,W/bt-btm  ( 6184): btm_acl_created hci_handle=12 link_role=0  transport=1
W/bt-btif ( 6184): info:x10
W/bt-l2cap( 6184): L2CA_SetDesireRole() new:x0, disallow_switch:0
D/        ( 6184): remote version info [80:01:84:8a:b3:68]: 7, 1d, 7d3
D/WifiServerServiceExt( 1030): Connected BT device : -2
,W/bt-btm  ( 6184): btm_read_remote_version_complete: BDA: 80-01-84-8a-b3-68
W/bt-btm  ( 6184): btm_read_remote_version_complete lmp_version 7 manufacturer 29 lmp_subversion 2003
W/bt-btm  ( 6184): btm_process_remote_ext_features_page 0: BDA: 80-01-84-8a-b3-68
W/bt-btm  ( 6184): ext_features_complt page_num:1 f[0]:x03, sm4:11, pend:0
W/bt-btm  ( 6184): btm_process_remote_ext_features_page 1: BDA: 80-01-84-8a-b3-68
,D/LGBluetoothPowerSaveListener( 7322): [BTUI] ACL connected => AclLinkCount = 1
,I/BTConnectionReceiver( 4198): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=80:01:84:8A:B3:68, alias=null, name=HTC Desire 820, majorDeviceClass=0, deviceClass=0]
,I/BluetoothClassifier( 4198): Bluetooth Device Name: HTC Desire 820
,W/bt-btm  ( 6184): btm_acl_role_changed: BDA: 80-01-84-8a-b3-68
W/bt-btm  ( 6184): btm_acl_role_changed: New role: 1
E/bt-btm  ( 6184): tBTM_SEC_DEV:0xa039b050 rs_disc_pending=0
W/bt-btif ( 6184): bta_dm_check_av:0
,W/bt-btif ( 6184): btif_dm_cback : unhandled event (14)
W/bt-l2cap( 6184): L2CAP - st: CLOSED evt: 10
W/bt-l2cap( 6184): L2CAP - st: TERM_W4_SEC_COMP evt: 7
W/bt-l2cap( 6184): L2CA_ErtmConnectRsp()  CID: 0x004b  Result: 0  Status: 0  BDA: 8001848ab368  p_ertm_info:0x00000000
W/bt-l2cap( 6184): L2CAP - st: W4_L2CA_CON_RSP evt: 22
W/bt-l2cap( 6184): L2CAP - st: CONFIG evt: 24
,W/bt-l2cap( 6184): L2CAP - st: CONFIG evt: 14
W/bt-l2cap( 6184): L2CAP - st: CONFIG evt: 25
W/bt-l2cap( 6184): L2CAP-Upper layer Config_Rsp,Local CID: 0x004b,Remote CID: 0x0046,PSM: 1,our MTU present:1,our MTU:672
W/bt-l2cap( 6184): L2CAP - st: CONFIG evt: 15
W/bt-l2cap( 6184): L2CAP-peer_Config_Rsp,Local CID: 0x004b,Remote CID: 0x0046,PSM: 1,peer MTU present: 0,peer MTU: 256
,W/bt-l2cap( 6184): L2CA_DisconnectRsp()  CID: 0x004b
W/bt-l2cap( 6184): L2CAP - st: W4_L2CA_DISC_RSP evt: 28
,D/sensors_hal_Time( 1030): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1030): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1030): tsOffsetIs: Apps: 608797472323; DSPS: 20089672; Offset : -4304291371
,E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-54 f=2462 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:1603908347] gl rssi=-54 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-54 f=2462 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:1603908350] gl rssi=-54 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
,E/bt-btm  ( 6184): btm_sec_disconnected - Clearing Pending flag
W/bt-l2cap( 6184): L2CA_SetDesireRole() new:x0, disallow_switch:0
,D/WifiServerServiceExt( 1030): Connected BT device : -3
I/BluetoothMapService( 6184): onReceive: android.bluetooth.device.action.ACL_DISCONNECTED
,V/BluetoothPbapReceiver( 6184): PbapReceiver onReceive 
V/BluetoothPbapReceiver( 6184): ***********action = android.bluetooth.device.action.ACL_DISCONNECTED
V/BluetoothPbapReceiver( 6184): ***********Calling start service!!!! with action = null
V/BluetoothPbapService( 6184): action: android.bluetooth.device.action.ACL_DISCONNECTED
V/BluetoothPbapService( 6184): state: -2147483648
,D/LGBluetoothPowerSaveListener( 7322): [BTUI] ACL disconnected => AclLinkCount = 0
,I/BTConnectionReceiver( 4198): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=80:01:84:8A:B3:68, alias=null, name=HTC Desire 820, majorDeviceClass=0, deviceClass=0]
,I/BluetoothClassifier( 4198): Bluetooth Device Name: HTC Desire 820
E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-54 f=2462 sc=60 link=72 tx=1.5, 0.0, 0.0  rx=1.5 bcn=0 [on:0 tx:0 rx:0 period:3000] from screen [on:0 period:1603911368] gl rssi=-54 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-54 f=2462 sc=60 link=72 tx=1.5, 0.0, 0.0  rx=1.5 bcn=0 [on:0 tx:0 rx:0 period:2] from screen [on:0 period:1603911370] gl rssi=-54 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
,D/btif_config_util( 6184): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-54 f=2462 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:1603914390] gl rssi=-54 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-54 f=2462 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:1603914393] gl rssi=-54 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-54 f=2462 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:1603917420] gl rssi=-54 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-54 f=2462 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:1603917423] gl rssi=-54 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-54 f=2462 sc=60 link=72 tx=1.2, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:1603920445] gl rssi=-54 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-54 f=2462 sc=60 link=72 tx=1.2, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:11] from screen [on:0 period:1603920456] gl rssi=-54 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
V/GLSActivity( 2125): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2125): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 2125): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2125): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2125): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2125): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1030): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1030): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1030): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1030): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1030): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1396): onNotificationPosted
,D/SmartCoverUpdateMonitor( 1396): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1396): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1396): handleNotificationPosted(true)
D/QuickCircle( 1396): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1396): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1396): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1396): post do just update job
D/LgeQuickCoverNotificationData( 1396): showAll3
D/LgeQuickCoverNotificationData( 1396): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1396): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
D/LgeQuickCoverNotificationData( 1396): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
E/LgeQuickCoverOverlayWindow( 1396): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1396): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1396): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1396): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1396): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1396): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1396): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1396): updateNotificationData: count=3
D/QuickStatusbarLayout( 1396): Notification difference=198
D/QuickStatusbarLayout( 1396): child = android.widget.LinearLayout{2154d13 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,W/GLSActivity( 2125): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2125): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2125): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2125): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2125): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2125): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2125): 	at android.os.Binder.execTransact(Binder.java:446)
E/PlayEventLogger( 7119): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 7119): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 7119): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/PlayEventLogger( 7119): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 7119): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/PlayEventLogger( 7119): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 7119): 	at android.os.Binder.execTransact(Binder.java:446)
,E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-54 f=2462 sc=60 link=72 tx=0.6, 0.0, 0.0  rx=0.3 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:1603923477] gl rssi=-54 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-54 f=2462 sc=60 link=72 tx=0.6, 0.0, 0.0  rx=0.3 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:1603923480] gl rssi=-54 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
W/System  ( 7119): Ignoring header User-Agent because its value was null.
,D/libc-netbsd(  311): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  311): res_queryN name = play.googleapis.com, class = 1, type = 1
D/libc-netbsd(  311): res_queryN name = play.googleapis.com succeed
,E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-55 f=2462 sc=60 link=72 tx=0.3, 0.0, 0.0  rx=0.2 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:1603926497] gl rssi=-55 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-55 f=2462 sc=60 link=72 tx=0.3, 0.0, 0.0  rx=0.2 bcn=0 [on:0 tx:0 rx:0 period:4] from screen [on:0 period:1603926501] gl rssi=-55 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
,D/sensors_hal_Time( 1030): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1030): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1030): tsOffsetIs: Apps: 628799551586; DSPS: 20745100; Offset : -4304287303
,E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-55 f=2462 sc=60 link=72 tx=5.6, 0.0, 0.0  rx=5.1 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:1603929529] gl rssi=-55 ag=0 hr ticks 0,0,1 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-55 f=2462 sc=60 link=72 tx=5.6, 0.0, 0.0  rx=5.1 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:1603929532] gl rssi=-55 ag=0 hr ticks 0,0,1 ls-=0 [56,56,60,60,65] brc=0 lrc=0
D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-55 f=2462 sc=60 link=72 tx=2.8, 0.0, 0.0  rx=2.5 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:1603932560] gl rssi=-55 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-55 f=2462 sc=60 link=72 tx=2.8, 0.0, 0.0  rx=2.5 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:1603932563] gl rssi=-55 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-55 f=2462 sc=60 link=72 tx=1.4, 0.0, 0.0  rx=1.3 bcn=0 [on:0 tx:0 rx:0 period:3000] from screen [on:0 period:1603935588] gl rssi=-55 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-55 f=2462 sc=60 link=72 tx=1.4, 0.0, 0.0  rx=1.3 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:1603935591] gl rssi=-55 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-55 f=2462 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.6 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:1603938618] gl rssi=-55 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-55 f=2462 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.6 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:1603938621] gl rssi=-55 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
,I/[SystemUI]TimeTickManager( 1446): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1446): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1446): called onTimeUpdated()
I/[SystemUI]Clock( 1446): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1446): called onTimeUpdated()
I/[SystemUI]DateView( 1446): called onTimeUpdated()
I/[SystemUI]DateView( 1446): called onTimeUpdated()
,D/KeyguardUpdateMonitor( 1446): handleTimeUpdate
E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-55 f=2462 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.3 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:1603941647] gl rssi=-55 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-55 f=2462 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.3 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:1603941650] gl rssi=-55 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
,D/PowerManagerServiceEx( 1030): acquireWakeLockInternal: lock=174419834, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1030
,D/[Concierge]Service( 2596): onStartCommand(). Type : 9
,D/PowerManagerServiceEx( 1030): releaseWakeLockInternal: lock=174419834 [*alarm*], flags=0x0
,E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-55 f=2462 sc=60 link=72 tx=1.2, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:1603944677] gl rssi=-55 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-55 f=2462 sc=60 link=72 tx=1.2, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:1603944680] gl rssi=-55 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
,D/sensors_hal_Time( 1030): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1030): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1030): tsOffsetIs: Apps: 648801849078; DSPS: 21400535; Offset : -4304278734
,E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-55 f=2462 sc=60 link=72 tx=0.6, 0.0, 0.0  rx=0.3 bcn=0 [on:0 tx:0 rx:0 period:3005] from screen [on:0 period:1603947711] gl rssi=-55 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-55 f=2462 sc=60 link=72 tx=0.6, 0.0, 0.0  rx=0.3 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:1603947714] gl rssi=-55 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-55 f=2462 sc=60 link=72 tx=0.3, 0.0, 0.0  rx=0.2 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:1603950741] gl rssi=-55 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-55 f=2462 sc=60 link=72 tx=0.3, 0.0, 0.0  rx=0.2 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:1603950744] gl rssi=-55 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
,W/bt-l2cap( 6184): l2c_link_hci_conn_req:current link_role= 1
,W/bt-btm  ( 6184): btm_acl_created hci_handle=13 link_role=1  transport=1
,W/bt-btm  ( 6184): btm_acl_created hci_handle=13 link_role=1  transport=1
,W/bt-btm  ( 6184): btm_read_remote_version_complete: BDA: 44-80-eb-7b-5a-05
W/bt-btm  ( 6184): btm_read_remote_version_complete lmp_version 6 manufacturer 29 lmp_subversion 2003
,W/bt-btm  ( 6184): btm_process_remote_ext_features_page 0: BDA: 44-80-eb-7b-5a-05
,W/bt-btm  ( 6184): ext_features_complt page_num:1 f[0]:x07, sm4:11, pend:0
W/bt-btm  ( 6184): btm_process_remote_ext_features_page 1: BDA: 44-80-eb-7b-5a-05
W/bt-btif ( 6184): info:x10
W/bt-l2cap( 6184): L2CA_SetDesireRole() new:x0, disallow_switch:0
,D/        ( 6184): remote version info [44:80:eb:7b:5a:05]: 6, 1d, 7d3
E/BluetoothRemoteDevices( 6184): aclStateChangeCallback: Device is NULL
D/LGBluetoothServiceUtil( 6184): [BTUI] sendBroadcastAclConnection: Connected, but device is null, sendBroadcast
D/LGBluetoothPowerSaveListener( 7322): [BTUI] ACL connected => AclLinkCount = 1
,W/bt-l2cap( 6184): L2CAP - st: CLOSED evt: 10
W/bt-l2cap( 6184): L2CAP - st: TERM_W4_SEC_COMP evt: 7
W/bt-l2cap( 6184): L2CA_ErtmConnectRsp()  CID: 0x004c  Result: 0  Status: 0  BDA: 4480eb7b5a05  p_ertm_info:0x00000000
W/bt-l2cap( 6184): L2CAP - st: W4_L2CA_CON_RSP evt: 22
W/bt-l2cap( 6184): L2CAP - st: CONFIG evt: 24
,W/bt-l2cap( 6184): L2CAP - st: CONFIG evt: 14
W/bt-l2cap( 6184): L2CAP - st: CONFIG evt: 25
W/bt-l2cap( 6184): L2CAP-Upper layer Config_Rsp,Local CID: 0x004c,Remote CID: 0x0041,PSM: 1,our MTU present:1,our MTU:672
W/bt-l2cap( 6184): L2CAP - st: CONFIG evt: 15
W/bt-l2cap( 6184): L2CAP-peer_Config_Rsp,Local CID: 0x004c,Remote CID: 0x0041,PSM: 1,peer MTU present: 0,peer MTU: 672
W/bt-l2cap( 6184): L2CA_DisconnectRsp()  CID: 0x004c
W/bt-l2cap( 6184): L2CAP - st: W4_L2CA_DISC_RSP evt: 28
,E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-55 f=2462 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:1603953771] gl rssi=-55 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-55 f=2462 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:1603953774] gl rssi=-55 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
,E/bt-btm  ( 6184): btm_sec_disconnected - Clearing Pending flag
W/bt-l2cap( 6184): L2CA_SetDesireRole() new:x0, disallow_switch:0
,D/WifiServerServiceExt( 1030): Connected BT device : -4
I/BluetoothMapService( 6184): onReceive: android.bluetooth.device.action.ACL_DISCONNECTED
,V/BluetoothPbapReceiver( 6184): PbapReceiver onReceive 
V/BluetoothPbapReceiver( 6184): ***********action = android.bluetooth.device.action.ACL_DISCONNECTED
V/BluetoothPbapReceiver( 6184): ***********Calling start service!!!! with action = null
V/BluetoothPbapService( 6184): action: android.bluetooth.device.action.ACL_DISCONNECTED
V/BluetoothPbapService( 6184): state: -2147483648
D/LGBluetoothPowerSaveListener( 7322): [BTUI] ACL disconnected => AclLinkCount = 0
,I/BTConnectionReceiver( 4198): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=44:80:EB:7B:5A:05, alias=null, name=XT1072, majorDeviceClass=0, deviceClass=0]
,I/BluetoothClassifier( 4198): Bluetooth Device Name: XT1072
E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-55 f=2462 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:1603956795] gl rssi=-55 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-55 f=2462 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:11] from screen [on:0 period:1603956806] gl rssi=-55 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
D/btif_config_util( 6184): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-55 f=2462 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:1603959830] gl rssi=-55 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-55 f=2462 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:1603959833] gl rssi=-55 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-55 f=2462 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:1603962859] gl rssi=-55 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-55 f=2462 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:1603962862] gl rssi=-55 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-55 f=2462 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:1603965889] gl rssi=-55 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-55 f=2462 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:1603965892] gl rssi=-55 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
,D/sensors_hal_Time( 1030): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1030): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1030): tsOffsetIs: Apps: 668803981207; DSPS: 22055965; Offset : -4304282627
,I/[SystemUI]LGPowerUI( 1446): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1446): On Skip Timer : true
,D/LGDMClient( 3941): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.intent.action.BATTERY_CHANGED
D/LGDMClient( 3941): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,D/HeadsetStateMachine( 6184): Disconnected process message: 10, size: 0
D/LEDHandler( 1950): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1950): Battery Level Remaining: 100%
D/LEDHandler( 1950): Battery Temp: 285, mChargingStatus=5, mChargingStop=false
D/KeyguardUpdateMonitor( 1446): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 285
I/[SystemUI]LGPowerUI( 1446): onReceive = android.intent.action.BATTERY_CHANGED
D/WifiController( 1030): battery changed pluggedType: 2
I/[SystemUI]BatterySaverHandler( 1446): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings( 1030): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1030): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-55 f=2462 sc=60 link=72 tx=1.0, 0.0, 0.0  rx=0.5 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:1603968912] gl rssi=-55 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-55 f=2462 sc=60 link=72 tx=1.0, 0.0, 0.0  rx=0.5 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:1603968915] gl rssi=-55 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-55 f=2462 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.3 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:1603971936] gl rssi=-55 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-55 f=2462 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.3 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:1603971939] gl rssi=-55 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-55 f=2462 sc=60 link=72 tx=0.3, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:1603974965] gl rssi=-55 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-55 f=2462 sc=60 link=72 tx=0.3, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:12] from screen [on:0 period:1603974977] gl rssi=-55 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-55 f=2462 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:1603977990] gl rssi=-55 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-55 f=2462 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:1603977993] gl rssi=-55 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-55 f=2462 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:1603981019] gl rssi=-55 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-55 f=2462 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:1603981022] gl rssi=-55 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-55 f=2462 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:1603984048] gl rssi=-55 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-55 f=2462 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:1603984051] gl rssi=-55 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-55 f=2462 sc=60 link=72 tx=3.0, 0.0, 0.0  rx=4.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:1603987078] gl rssi=-55 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-55 f=2462 sc=60 link=72 tx=3.0, 0.0, 0.0  rx=4.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:1603987081] gl rssi=-55 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
,D/sensors_hal_Time( 1030): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1030): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1030): tsOffsetIs: Apps: 688806132032; DSPS: 22711395; Offset : -4304268241
,E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-55 f=2462 sc=60 link=72 tx=1.5, 0.0, 0.0  rx=2.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:1603990104] gl rssi=-55 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-55 f=2462 sc=60 link=72 tx=1.5, 0.0, 0.0  rx=2.0 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:1603990114] gl rssi=-55 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
D/StatusBar.NetworkController( 1446): refreshViews: Data not connected!! Set no data type icon / Roaming
,E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-56 f=2462 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=1.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:1603993151] gl rssi=-56 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-56 f=2462 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=1.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:1603993154] gl rssi=-56 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-56 f=2462 sc=60 link=72 tx=1.4, 0.0, 0.0  rx=1.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:1603996174] gl rssi=-56 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-56 f=2462 sc=60 link=72 tx=1.4, 0.0, 0.0  rx=1.0 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:1603996184] gl rssi=-56 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-56 f=2462 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.5 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:1603999205] gl rssi=-56 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-56 f=2462 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.5 bcn=0 [on:0 tx:0 rx:0 period:12] from screen [on:0 period:1603999217] gl rssi=-56 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
I/[SystemUI]TimeTickManager( 1446): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1446): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1446): called onTimeUpdated()
I/[SystemUI]Clock( 1446): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1446): called onTimeUpdated()
I/[SystemUI]DateView( 1446): called onTimeUpdated()
I/[SystemUI]DateView( 1446): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1446): handleTimeUpdate
,E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-56 f=2462 sc=60 link=72 tx=0.3, 0.0, 0.0  rx=0.3 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:1604002238] gl rssi=-56 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-56 f=2462 sc=60 link=72 tx=0.3, 0.0, 0.0  rx=0.3 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:1604002241] gl rssi=-56 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-56 f=2462 sc=60 link=72 tx=0.2, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:1604005270] gl rssi=-56 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-56 f=2462 sc=60 link=72 tx=0.2, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:1604005273] gl rssi=-56 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
,D/PowerManagerServiceEx( 1030): acquireWakeLockInternal: lock=174419834, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1030
,V/AlarmManager( 1030): ELAPSED_WAKEUP set : Alarm{d3b581b type 2 when 707355 android} when 707355
D/[Concierge]Service( 2596): onStartCommand(). Type : 9
,D/PowerManagerServiceEx( 1030): releaseWakeLockInternal: lock=174419834 [*alarm*], flags=0x0
,I/BooksSync( 7886): Starting books sync
,D/BooksSync( 7886): started syncMyEbooks
,V/GLSActivity( 2125): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/GLSUser ( 2125): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2125): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2125): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2125): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2125): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1030): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1030): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1030): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1030): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1030): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1396): onNotificationPosted
,D/SmartCoverUpdateMonitor( 1396): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1396): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1396): handleNotificationPosted(true)
D/QuickCircle( 1396): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1396): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1396): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1396): post do just update job
D/LgeQuickCoverNotificationData( 1396): showAll3
D/LgeQuickCoverNotificationData( 1396): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1396): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
D/LgeQuickCoverNotificationData( 1396): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
E/LgeQuickCoverOverlayWindow( 1396): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1396): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1396): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1396): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1396): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1396): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1396): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1396): updateNotificationData: count=3
W/GLSActivity( 2125): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2125): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2125): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2125): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2125): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2125): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2125): 	at android.os.Binder.execTransact(Binder.java:446)
E/BooksAccountManager( 7886): Authentication error
E/BooksAccountManager( 7886): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7886): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 7886): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 7886): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 7886): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 7886): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 7886): null auth token
D/QuickStatusbarLayout( 1396): Notification difference=198
D/QuickStatusbarLayout( 1396): child = android.widget.LinearLayout{2154d13 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,W/ApiaryClient( 7886): Error response from books API: {
W/ApiaryClient( 7886):  "error": {
W/ApiaryClient( 7886):   "errors": [
W/ApiaryClient( 7886):    {
W/ApiaryClient( 7886):     "domain": "global",
W/ApiaryClient( 7886):     "reason": "required",
W/ApiaryClient( 7886):     "message": "Login Required",
W/ApiaryClient( 7886):     "locationType": "header",
W/ApiaryClient( 7886):     "location": "Authorization"
W/ApiaryClient( 7886):    }
W/ApiaryClient( 7886):   ],
W/ApiaryClient( 7886):   "code": 401,
W/ApiaryClient( 7886):   "message": "Login Required"
W/ApiaryClient( 7886):  }
W/ApiaryClient( 7886): }
,W/ApiaryClient( 7886): errCount = 1: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7886): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=5779976773728055546&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7886): Headers:
W/ApiaryClient( 7886): accept-encoding: [gzip]
W/ApiaryClient( 7886): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 7886): gdata-version: 2
V/GLSActivity( 2125): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2125): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 2125): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2125): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2125): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2125): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/sensors_hal_Time( 1030): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1030): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1030): tsOffsetIs: Apps: 708810670254; DSPS: 23366904; Offset : -4304275837
,V/NotificationService( 1030): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1030): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1030): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1030): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1030): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1396): onNotificationPosted
D/SmartCoverUpdateMonitor( 1396): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1396): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1396): handleNotificationPosted(true)
D/QuickCircle( 1396): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1396): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1396): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1396): post do just update job
D/LgeQuickCoverNotificationData( 1396): showAll3
D/LgeQuickCoverNotificationData( 1396): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1396): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
D/LgeQuickCoverNotificationData( 1396): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
E/LgeQuickCoverOverlayWindow( 1396): showNotificationWithSetupData: display=false
,D/LgeQuickCoverOverlayWindow( 1396): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1396): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1396): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1396): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1396): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1396): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1396): updateNotificationData: count=3
W/GLSActivity( 2125): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2125): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2125): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2125): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2125): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2125): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2125): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 7886): Authentication error
E/BooksAccountManager( 7886): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7886): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 7886): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 7886): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 7886): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 7886): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 7886): null auth token
D/QuickStatusbarLayout( 1396): Notification difference=198
D/QuickStatusbarLayout( 1396): child = android.widget.LinearLayout{2154d13 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,W/ApiaryClient( 7886): Error response from books API: {
W/ApiaryClient( 7886):  "error": {
W/ApiaryClient( 7886):   "errors": [
W/ApiaryClient( 7886):    {
W/ApiaryClient( 7886):     "domain": "global",
W/ApiaryClient( 7886):     "reason": "required",
W/ApiaryClient( 7886):     "message": "Login Required",
W/ApiaryClient( 7886):     "locationType": "header",
W/ApiaryClient( 7886):     "location": "Authorization"
W/ApiaryClient( 7886):    }
W/ApiaryClient( 7886):   ],
W/ApiaryClient( 7886):   "code": 401,
W/ApiaryClient( 7886):   "message": "Login Required"
W/ApiaryClient( 7886):  }
W/ApiaryClient( 7886): }
,W/ApiaryClient( 7886): errCount = 2: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7886): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=5779976773728055546&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7886): Headers:
W/ApiaryClient( 7886): accept-encoding: [gzip]
W/ApiaryClient( 7886): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 7886): gdata-version: 2
,E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-56 f=2462 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:1604008298] gl rssi=-56 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-56 f=2462 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:1604008301] gl rssi=-56 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
,V/GLSActivity( 2125): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2125): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2125): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2125): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 2125): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2125): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1030): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1030): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1030): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1030): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1030): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1396): onNotificationPosted
,D/SmartCoverUpdateMonitor( 1396): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1396): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1396): handleNotificationPosted(true)
D/QuickCircle( 1396): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1396): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1396): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1396): post do just update job
D/LgeQuickCoverNotificationData( 1396): showAll3
D/LgeQuickCoverNotificationData( 1396): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1396): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
D/LgeQuickCoverNotificationData( 1396): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
E/LgeQuickCoverOverlayWindow( 1396): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1396): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1396): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1396): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1396): isNotificationForCurrentUser : true
,D/LgeQuickCoverOverlayWindow( 1396): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1396): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1396): updateNotificationData: count=3
W/GLSActivity( 2125): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2125): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2125): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2125): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2125): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2125): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2125): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 7886): Authentication error
E/BooksAccountManager( 7886): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7886): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 7886): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 7886): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 7886): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 7886): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 7886): null auth token
D/QuickStatusbarLayout( 1396): Notification difference=198
D/QuickStatusbarLayout( 1396): child = android.widget.LinearLayout{2154d13 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,W/ApiaryClient( 7886): Error response from books API: {
W/ApiaryClient( 7886):  "error": {
W/ApiaryClient( 7886):   "errors": [
W/ApiaryClient( 7886):    {
W/ApiaryClient( 7886):     "domain": "global",
W/ApiaryClient( 7886):     "reason": "required",
W/ApiaryClient( 7886):     "message": "Login Required",
W/ApiaryClient( 7886):     "locationType": "header",
W/ApiaryClient( 7886):     "location": "Authorization"
W/ApiaryClient( 7886):    }
W/ApiaryClient( 7886):   ],
W/ApiaryClient( 7886):   "code": 401,
W/ApiaryClient( 7886):   "message": "Login Required"
W/ApiaryClient( 7886):  }
W/ApiaryClient( 7886): }
,W/ApiaryClient( 7886): errCount = 3: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7886): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=5779976773728055546&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7886): Headers:
W/ApiaryClient( 7886): accept-encoding: [gzip]
W/ApiaryClient( 7886): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 7886): gdata-version: 2
,E/BooksSync( 7886): Soft error: 
E/BooksSync( 7886): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 7886): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=5779976773728055546&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 7886): Headers:
E/BooksSync( 7886): accept-encoding: [gzip]
E/BooksSync( 7886): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 7886): gdata-version: 2
E/BooksSync( 7886): 
E/BooksSync( 7886): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 7886): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 7886): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 7886): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 7886): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 7886): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 7886): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 7886): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 7886): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 7886): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 7886): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 7886): {
E/BooksSync( 7886):  "error": {
E/BooksSync( 7886):   "errors": [
E/BooksSync( 7886):    {
E/BooksSync( 7886):     "domain": "global",
E/BooksSync( 7886):     "reason": "required",
E/BooksSync( 7886):     "message": "Login Required",
E/BooksSync( 7886):     "locationType": "header",
E/BooksSync( 7886):     "location": "Authorization"
E/BooksSync( 7886):    }
E/BooksSync( 7886):   ],
E/BooksSync( 7886):   "code": 401,
E/BooksSync( 7886):   "message": "Login Required"
E/BooksSync( 7886):  }
E/BooksSync( 7886): }
E/BooksSync( 7886): 
E/BooksSync( 7886): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 7886): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 7886): 	... 8 more
,E/BooksSync( 7886): Sync error
E/BooksSync( 7886): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 7886): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=5779976773728055546&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 7886): Headers:
E/BooksSync( 7886): accept-encoding: [gzip]
E/BooksSync( 7886): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 7886): gdata-version: 2
E/BooksSync( 7886): 
E/BooksSync( 7886): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 7886): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 7886): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 7886): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 7886): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 7886): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 7886): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 7886): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 7886): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 7886): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 7886): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 7886): {
E/BooksSync( 7886):  "error": {
E/BooksSync( 7886):   "errors": [
E/BooksSync( 7886):    {
E/BooksSync( 7886):     "domain": "global",
E/BooksSync( 7886):     "reason": "required",
E/BooksSync( 7886):     "message": "Login Required",
E/BooksSync( 7886):     "locationType": "header",
E/BooksSync( 7886):     "location": "Authorization"
E/BooksSync( 7886):    }
E/BooksSync( 7886):   ],
E/BooksSync( 7886):   "code": 401,
E/BooksSync( 7886):   "message": "Login Required"
E/BooksSync( 7886):  }
E/BooksSync( 7886): }
E/BooksSync( 7886): 
E/BooksSync( 7886): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 7886): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 7886): 	... 8 more
I/BooksSync( 7886): Finished books sync
D/SyncManager( 1030): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 707355, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-56 f=2462 sc=60 link=72 tx=3.0, 0.0, 0.0  rx=2.0 bcn=0 [on:0 tx:0 rx:0 period:3000] from screen [on:0 period:1604011323] gl rssi=-56 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-56 f=2462 sc=60 link=72 tx=3.0, 0.0, 0.0  rx=2.0 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:1604011324] gl rssi=-56 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-56 f=2462 sc=60 link=72 tx=3.0, 0.0, 0.0  rx=2.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:1604014346] gl rssi=-56 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-56 f=2462 sc=60 link=72 tx=3.0, 0.0, 0.0  rx=2.0 bcn=0 [on:0 tx:0 rx:0 period:11] from screen [on:0 period:1604014357] gl rssi=-56 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-56 f=2462 sc=60 link=72 tx=1.5, 0.0, 0.0  rx=1.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:1604017379] gl rssi=-56 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-56 f=2462 sc=60 link=72 tx=1.5, 0.0, 0.0  rx=1.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:1604017382] gl rssi=-56 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-56 f=2462 sc=60 link=72 tx=1.8, 0.0, 0.0  rx=1.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:1604020411] gl rssi=-56 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-56 f=2462 sc=60 link=72 tx=1.8, 0.0, 0.0  rx=1.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:1604020414] gl rssi=-56 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-56 f=2462 sc=60 link=72 tx=0.9, 0.0, 0.0  rx=0.5 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:1604023440] gl rssi=-56 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-56 f=2462 sc=60 link=72 tx=0.9, 0.0, 0.0  rx=0.5 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:1604023443] gl rssi=-56 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
,D/StatusBar.NetworkController( 1446): refreshViews: Data not connected!! Set no data type icon / Roaming
,E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-55 f=2462 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.3 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:1604026483] gl rssi=-55 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-55 f=2462 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.3 bcn=0 [on:0 tx:0 rx:0 period:9] from screen [on:0 period:1604026492] gl rssi=-55 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
D/sensors_hal_Time( 1030): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1030): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1030): tsOffsetIs: Apps: 728812891705; DSPS: 24022337; Offset : -4304283418
,E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-55 f=2462 sc=60 link=72 tx=0.2, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:1604029514] gl rssi=-55 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-55 f=2462 sc=60 link=72 tx=0.2, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:1604029524] gl rssi=-55 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-55 f=2462 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:1604032545] gl rssi=-55 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-55 f=2462 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:13] from screen [on:0 period:1604032558] gl rssi=-55 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-55 f=2462 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:1604035578] gl rssi=-55 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-55 f=2462 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:1604035581] gl rssi=-55 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
,V/AlarmManager( 1030): ELAPSED_WAKEUP set : Alarm{382864ad type 2 when 737552 android} when 737552,
,E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-55 f=2462 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:1604038608] gl rssi=-55 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-55 f=2462 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:1604038611] gl rssi=-55 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-55 f=2462 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:1604041638] gl rssi=-55 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-55 f=2462 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:1604041641] gl rssi=-55 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-55 f=2462 sc=60 link=72 tx=1.0, 0.0, 0.0  rx=0.5 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:1604044664] gl rssi=-55 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-55 f=2462 sc=60 link=72 tx=1.0, 0.0, 0.0  rx=0.5 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:1604044674] gl rssi=-55 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
D/sensors_hal_Time( 1030): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1030): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1030): tsOffsetIs: Apps: 748814753572; DSPS: 24677758; Offset : -4304283071
,E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-55 f=2462 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.3 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:1604047693] gl rssi=-55 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-55 f=2462 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.3 bcn=0 [on:0 tx:0 rx:0 period:9] from screen [on:0 period:1604047702] gl rssi=-55 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-55 f=2462 sc=60 link=72 tx=0.3, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:1604050725] gl rssi=-55 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-55 f=2462 sc=60 link=72 tx=0.3, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:1604050735] gl rssi=-55 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-55 f=2462 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:1604053757] gl rssi=-55 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-55 f=2462 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:1604053760] gl rssi=-55 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-55 f=2462 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:1604056786] gl rssi=-55 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-55 f=2462 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:4] from screen [on:0 period:1604056790] gl rssi=-55 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-55 f=2462 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:1604059815] gl rssi=-55 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-55 f=2462 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:1604059825] gl rssi=-55 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
I/[SystemUI]TimeTickManager( 1446): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1446): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1446): called onTimeUpdated()
I/[SystemUI]Clock( 1446): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1446): called onTimeUpdated()
I/[SystemUI]DateView( 1446): called onTimeUpdated()
I/[SystemUI]DateView( 1446): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1446): handleTimeUpdate
,E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-55 f=2462 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:1604062847] gl rssi=-55 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-55 f=2462 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:1604062850] gl rssi=-55 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-55 f=2462 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:1604065878] gl rssi=-55 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-55 f=2462 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:1604065881] gl rssi=-55 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
,D/sensors_hal_Time( 1030): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1030): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1030): tsOffsetIs: Apps: 768816851845; DSPS: 25333187; Offset : -4304290590
,E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-55 f=2462 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:1604068907] gl rssi=-55 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-55 f=2462 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:1604068917] gl rssi=-55 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-55 f=2462 sc=60 link=72 tx=1.0, 0.0, 0.0  rx=0.5 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:1604071938] gl rssi=-55 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-55 f=2462 sc=60 link=72 tx=1.0, 0.0, 0.0  rx=0.5 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:1604071941] gl rssi=-55 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-55 f=2462 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.3 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:1604074963] gl rssi=-55 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-55 f=2462 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.3 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:1604074966] gl rssi=-55 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-55 f=2462 sc=60 link=72 tx=0.3, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:1604077995] gl rssi=-55 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-55 f=2462 sc=60 link=72 tx=0.3, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:11] from screen [on:0 period:1604078006] gl rssi=-55 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-55 f=2462 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3000] from screen [on:0 period:1604081025] gl rssi=-55 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-55 f=2462 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:11] from screen [on:0 period:1604081036] gl rssi=-55 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-55 f=2462 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:1604084059] gl rssi=-55 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-55 f=2462 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:1604084062] gl rssi=-55 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-55 f=2462 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:1604087089] gl rssi=-55 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-55 f=2462 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:1604087092] gl rssi=-55 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
,D/sensors_hal_Time( 1030): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1030): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1030): tsOffsetIs: Apps: 788819004077; DSPS: 25988617; Offset : -4304274536
,E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-55 f=2462 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:1604090117] gl rssi=-55 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-55 f=2462 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:1604090120] gl rssi=-55 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-55 f=2462 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:1604093147] gl rssi=-55 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-55 f=2462 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:1604093150] gl rssi=-55 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-55 f=2462 sc=60 link=72 tx=1.0, 0.0, 0.0  rx=0.5 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:1604096176] gl rssi=-55 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-55 f=2462 sc=60 link=72 tx=1.0, 0.0, 0.0  rx=0.5 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:1604096186] gl rssi=-55 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-55 f=2462 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.3 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:1604099206] gl rssi=-55 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-55 f=2462 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.3 bcn=0 [on:0 tx:0 rx:0 period:4] from screen [on:0 period:1604099210] gl rssi=-55 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-55 f=2462 sc=60 link=72 tx=0.3, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:1604102237] gl rssi=-55 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-55 f=2462 sc=60 link=72 tx=0.3, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:1604102240] gl rssi=-55 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-55 f=2462 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:1604105267] gl rssi=-55 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-55 f=2462 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:1604105270] gl rssi=-55 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
,D/sensors_hal_Time( 1030): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1030): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1030): tsOffsetIs: Apps: 808821271570; DSPS: 26644051; Offset : -4304265317
,E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-55 f=2462 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:1604108296] gl rssi=-55 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-55 f=2462 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:4] from screen [on:0 period:1604108300] gl rssi=-55 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-55 f=2462 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:1604111325] gl rssi=-55 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-55 f=2462 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:1604111335] gl rssi=-55 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-55 f=2462 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:1604114357] gl rssi=-55 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-55 f=2462 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:1604114360] gl rssi=-55 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-55 f=2462 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:1604117386] gl rssi=-55 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-55 f=2462 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:11] from screen [on:0 period:1604117397] gl rssi=-55 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-55 f=2462 sc=60 link=72 tx=1.0, 0.0, 0.0  rx=0.5 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:1604120418] gl rssi=-55 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-55 f=2462 sc=60 link=72 tx=1.0, 0.0, 0.0  rx=0.5 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:1604120421] gl rssi=-55 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
,I/[SystemUI]TimeTickManager( 1446): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1446): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1446): called onTimeUpdated()
I/[SystemUI]Clock( 1446): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1446): called onTimeUpdated()
,I/[SystemUI]DateView( 1446): called onTimeUpdated()
I/[SystemUI]DateView( 1446): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1446): handleTimeUpdate
,D/PowerManagerServiceEx( 1030): acquireWakeLockInternal: lock=174419834, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1030
,I/ActivityManager( 1030): Start proc com.lge.clock for broadcast com.lge.clock/.widget.DigitalAppWidgetProvider: pid=8098 uid=10010 gids={50010, 9997, 3003, 1028, 4002} abi=armeabi-v7a
,D/[Concierge]Service( 2596): onStartCommand(). Type : 9
,I/DigitalAppWidgetProvider( 8098): onReceive: com.android.deskclock.ON_QUARTER_HOUR
,V/DigitalAppWidgetProvider( 8098): startAlarmOnQuarterHour android.app.ReceiverRestrictedContext@1d2083bc
D/PowerManagerServiceEx( 1030): releaseWakeLockInternal: lock=174419834 [*alarm*], flags=0x0
I/ActivityManager( 1030): Killing 7399:com.lge.sync/1000 (adj 15): empty #17
W/libprocessgroup( 1030): failed to open /acct/uid_1000/pid_7399/cgroup.procs: No such file or directory
,E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-55 f=2462 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.3 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:1604123449] gl rssi=-55 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-55 f=2462 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.3 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:1604123452] gl rssi=-55 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-55 f=2462 sc=60 link=72 tx=0.3, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:1604126475] gl rssi=-55 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-55 f=2462 sc=60 link=72 tx=0.3, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:1604126485] gl rssi=-55 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
D/sensors_hal_Time( 1030): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1030): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1030): tsOffsetIs: Apps: 828824874427; DSPS: 27299530; Offset : -4304291995
,E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-55 f=2462 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:1604129507] gl rssi=-55 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-55 f=2462 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:1604129510] gl rssi=-55 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-55 f=2462 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:1604132532] gl rssi=-55 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-55 f=2462 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:1604132535] gl rssi=-55 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-55 f=2462 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:1604135562] gl rssi=-55 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-55 f=2462 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:1604135565] gl rssi=-55 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-55 f=2462 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:1604138590] gl rssi=-55 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-55 f=2462 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:1604138593] gl rssi=-55 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-55 f=2462 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:1604141620] gl rssi=-55 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-55 f=2462 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:1604141623] gl rssi=-55 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-55 f=2462 sc=60 link=72 tx=1.0, 0.0, 0.0  rx=0.5 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:1604144649] gl rssi=-55 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-55 f=2462 sc=60 link=72 tx=1.0, 0.0, 0.0  rx=0.5 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:1604144652] gl rssi=-55 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
,D/sensors_hal_Time( 1030): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1030): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1030): tsOffsetIs: Apps: 848826806346; DSPS: 27954953; Offset : -4304284455
,E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-55 f=2462 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.3 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:1604147678] gl rssi=-55 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-55 f=2462 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.3 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:1604147681] gl rssi=-55 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-55 f=2462 sc=60 link=72 tx=0.3, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:1604150707] gl rssi=-55 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-55 f=2462 sc=60 link=72 tx=0.3, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:1604150710] gl rssi=-55 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-55 f=2462 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:1604153737] gl rssi=-55 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-55 f=2462 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:1604153740] gl rssi=-55 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-55 f=2462 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:1604156766] gl rssi=-55 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-55 f=2462 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:1604156776] gl rssi=-55 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-55 f=2462 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:1604159797] gl rssi=-55 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-55 f=2462 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:1604159800] gl rssi=-55 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-55 f=2462 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:1604162828] gl rssi=-55 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-55 f=2462 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:1604162831] gl rssi=-55 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-55 f=2462 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:1604165858] gl rssi=-55 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-55 f=2462 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:1604165861] gl rssi=-55 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
,D/sensors_hal_Time( 1030): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1030): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1030): tsOffsetIs: Apps: 868828988578; DSPS: 28610384; Offset : -4304269128
,E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-55 f=2462 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:1604168887] gl rssi=-55 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-55 f=2462 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:13] from screen [on:0 period:1604168900] gl rssi=-55 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-55 f=2462 sc=60 link=72 tx=3.0, 0.0, 0.0  rx=3.0 bcn=0 [on:0 tx:0 rx:0 period:3005] from screen [on:0 period:1604171920] gl rssi=-55 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-55 f=2462 sc=60 link=72 tx=3.0, 0.0, 0.0  rx=3.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:1604171923] gl rssi=-55 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-55 f=2462 sc=60 link=72 tx=1.5, 0.0, 0.0  rx=1.5 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:1604174949] gl rssi=-55 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-55 f=2462 sc=60 link=72 tx=1.5, 0.0, 0.0  rx=1.5 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:1604174952] gl rssi=-55 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-55 f=2462 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:1604177977] gl rssi=-55 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-55 f=2462 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:1604177980] gl rssi=-55 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-55 f=2462 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:1604181007] gl rssi=-55 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-55 f=2462 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:1604181010] gl rssi=-55 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
,I/[SystemUI]TimeTickManager( 1446): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1446): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1446): called onTimeUpdated()
I/[SystemUI]Clock( 1446): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1446): called onTimeUpdated()
I/[SystemUI]DateView( 1446): called onTimeUpdated()
I/[SystemUI]DateView( 1446): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1446): handleTimeUpdate
E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-55 f=2462 sc=60 link=72 tx=0.2, 0.0, 0.0  rx=0.2 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:1604184037] gl rssi=-55 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-55 f=2462 sc=60 link=72 tx=0.2, 0.0, 0.0  rx=0.2 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:1604184040] gl rssi=-55 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-55 f=2462 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:1604187068] gl rssi=-55 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-55 f=2462 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:1604187071] gl rssi=-55 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
,D/sensors_hal_Time( 1030): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1030): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1030): tsOffsetIs: Apps: 888830916592; DSPS: 29265807; Offset : -4304263616
,E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-55 f=2462 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:1604190098] gl rssi=-55 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-55 f=2462 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:1604190101] gl rssi=-55 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-55 f=2462 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:1604193128] gl rssi=-55 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-55 f=2462 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:1604193131] gl rssi=-55 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-55 f=2462 sc=60 link=72 tx=1.0, 0.0, 0.0  rx=0.5 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:1604196157] gl rssi=-55 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-55 f=2462 sc=60 link=72 tx=1.0, 0.0, 0.0  rx=0.5 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:1604196160] gl rssi=-55 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-55 f=2462 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.3 bcn=0 [on:0 tx:0 rx:0 period:3000] from screen [on:0 period:1604199185] gl rssi=-55 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-55 f=2462 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.3 bcn=0 [on:0 tx:0 rx:0 period:11] from screen [on:0 period:1604199196] gl rssi=-55 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-55 f=2462 sc=60 link=72 tx=0.3, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:1604202218] gl rssi=-55 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-55 f=2462 sc=60 link=72 tx=0.3, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:1604202221] gl rssi=-55 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-55 f=2462 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:2999] from screen [on:0 period:1604205246] gl rssi=-55 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-55 f=2462 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:1604205249] gl rssi=-55 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
,D/sensors_hal_Time( 1030): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1030): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1030): tsOffsetIs: Apps: 908833029396; DSPS: 29921237; Offset : -4304287356
,E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-55 f=2462 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:1604208277] gl rssi=-55 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-55 f=2462 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:1604208280] gl rssi=-55 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-55 f=2462 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:1604211305] gl rssi=-55 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-55 f=2462 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:11] from screen [on:0 period:1604211316] gl rssi=-55 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-55 f=2462 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:1604214337] gl rssi=-55 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-55 f=2462 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:1604214340] gl rssi=-55 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-55 f=2462 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:1604217368] gl rssi=-55 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-55 f=2462 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:1604217371] gl rssi=-55 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
,TIME-OUT KILL (timeout was 600000ms)
```
