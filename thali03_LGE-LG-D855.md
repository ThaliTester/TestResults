#### Test 525393149f38b37_thali03_LGE-LG-D855 Logs


```
--------- beginning of main
D/sensors_hal_Time( 1029): tsOffsetIs: Apps: 152773171732; DSPS: 5147484; Offset : -4327470050
,D/AndroidRuntime( 6087): 
D/AndroidRuntime( 6087): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 6087): CheckJNI is OFF
D/AndroidRuntime( 6087): Calling main entry com.android.commands.am.Am
--------- beginning of system
I/ActivityManager( 1029): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
V/SplitWindowPolicy( 1945): checkScreen => return. sourceIntent is null or not support SplitWindow component: ComponentInfo{co..../co.....MainActivity}
D/SplitInfo( 1029): new ActivitySplitInfo : ActivitySplitInfo [screenZone=0/ flag=0/ state=NATIVE]
V/ActivityStackEx( 1029): create ActivityStackEx
D/ActivityManager( 1029): setTaskToReturnTo : TaskRecord{3240d616 #2 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
D/ActivityManager( 1029): setTaskToReturnTo : TaskRecord{3240d616 #2 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
D/WindowStateEx( 1029): AppWindowTokenEx init.. 
E/GBMv2   (  342): DFP En is all cleared set to be enabled
D/QuickStatusbarLayout( 1393): Notification difference=198
D/QuickStatusbarLayout( 1393): child = android.widget.LinearLayout{156a1e25 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
D/LgeAbsQuickCoverView( 1393): mCoverXPos: 0 ,mCoverYPos: 0
D/LgeAbsQuickCoverView( 1393): mCoverWidth: 0 ,mCoverHeight: 0
I/ActivityManager( 1029): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6107 uid=10311 gids={50311, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
D/AndroidRuntime( 6087): Shutting down VM
V/ActivityManager( 1029): Display changed displayId=0
D/DSDPConnection( 1849): Display #0 changed.
D/SplitWindowPolicy( 1945): updateActivityStateChanged: resumed=true, screenId=1, isScreenFull=true
D/SplitWindowPolicy( 1945): topRunningActivity=ActivityInfo{2aa4430a co.....MainActivity}, taskId=2, activityType=0, bIsSplit=false
D/SplitWindowPolicy( 1945): updateActivityStateChanged: resumed=false, screenId=1, isScreenFull=true
D/SplitWindowPolicy( 1945): topRunningActivity=ActivityInfo{1819c77b co.....MainActivity}, taskId=2, activityType=0, bIsSplit=false
D/ContextHelper( 6107): convertTheme. context->name=com.test.thalitest themeResourceId=16973833
I/WebViewFactory( 6107): Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
I/LibraryLoader( 6107): Loading: webviewchromium
I/LibraryLoader( 6107): Time to load native libraries: 2 ms (timestamps 8823-8825)
I/LibraryLoader( 6107): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 6107): Binding Chromium to main looper Looper (main, tid 1) {339cb5c7}
,I/LibraryLoader( 6107): Expected native library version number "",actual native library version number ""
I/chromium( 6107): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 6107): Initializing chromium process, renderers=0
W/art     ( 6107): Attempt to remove local handle scope entry from IRT, ignoring
W/chromium( 6107): [WARNING:dns_config_service_posix.cc(293)] Failed to read DnsConfig.
V/AudioPolicyService(  314): registerClient() client 0xb14271e0, uid 10311
D/BluetoothManagerService( 1029): Message: 20
D/BluetoothManagerService( 1029): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@8d8d1f0:true
D/BluetoothAdapter( 6107): 403060724: getState() :  mService = null. Returning STATE_OFF
W/chromium( 6107): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
I/chromium( 6107): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=32 off=46780 len=2953
I/chromium( 6107): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:33 off:229536 len:643667
I/Adreno-EGL( 6107): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 6107): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 6107): Build Date: 12/12/14 금
I/Adreno-EGL( 6107): Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
I/Adreno-EGL( 6107): Remote Branch: 
I/Adreno-EGL( 6107): Local Patches: 
I/Adreno-EGL( 6107): Reconstruct Branch: 
W/chromium( 6107): [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
W/chromium( 6107): [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
W/art     ( 6107): Attempt to remove local handle scope entry from IRT, ignoring
W/AwContents( 6107): onDetachedFromWindow called when already detached. Ignoring
D/SystemWebViewEngine( 6107): CordovaWebView is running on device made by: LGE
W/art     ( 6107): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 6107): Attempt to remove local handle scope entry from IRT, ignoring
D/OpenGLRenderer( 6107): Render dirty regions requested: true
I/OpenGLRenderer( 6107): Initialized EGL, version 1.4
D/OpenGLRenderer( 6107): Enabling debug mode 0
D/Atlas   ( 6107): Validating map...
D/SplitWindow( 1029): check instance of lgWin Window{929faaa u0 com.test.thalitest/com.test.thalitest.MainActivity}
D/LgDataFeature( 6107): LgDataFeature() Constructor: none
D/LgDataFeature( 6107): LgDataFeature() Constructor Done, null
I/SystemUI[Framework]( 1029): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x0, pkg=com.android.systemui
W/PhoneWindowManagerEx( 1029): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx( 1029): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx( 1029): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework]( 1029): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@2130028b,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework]( 1029): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
D/PhoneStatusBar( 1451): setSystemUiVisibility vis=0 mask=ffffffff oldVal=8000 newVal=0 diff=8000
I/[SystemUI]NavigationThemeResource( 1451): NavigationKey Color is changed(WHITE_WITH_SHADOW -> BLACK)
I/[SystemUI]NavigationThemeResource( 1451):  BarMode=0, Theme=WHITE, LightBackground=false (Transparent)
I/[SystemUI]NavigationThemeResource( 1451): , Keyguard show=false, IME shown=false, Panel expanded=false
I/ActivityManager( 1029): Displayed com.test.thalitest/.MainActivity: +543ms (total +620ms)
I/Timeline( 1029): Timeline: Activity_windows_visible id: ActivityRecord{11da0b97 u0 com.test.thalitest/.MainActivity t2} time:159249
I/Timeline( 6107): Timeline: Activity_idle id: android.os.BinderProxy@da18624 time:159255
I/chromium( 6107): [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
I/chromium( 6107): 
D/JsMessageQueue( 6107): Set native->JS mode to OnlineEventsBridgeMode
I/chromium( 6107): [INFO:SkFontConfigInterface_android.cpp(247)] ---- failed to open </system/fonts/CutiveMono.ttf> as a font
I/chromium( 6107): 
D/jxcore_app_log( 6107): JniHelper::setJavaVM(0xb487c280), pthread_self() = -1435096320
D/JX-Cordova( 6107): jxcore cordova android initializing
E/GBMv2   (  342): DFP En is all cleared set to be enabled
E/GBMv2   (  342): Set value is all cleared set the max
I/GBMv2   (  342): DFP Enabled. Ignore VFP set
,W/jxcore-log( 6107): Initializing JXcore engine
W/jxcore-log( 6107): JXcore engine is ready
,W/jxcore-log( 6107): Starting JXcore engine
,W/.test.thalitest( 6107): type=1400 audit(0.0:146): avc: denied { ioctl } for path="socket:[10248]" dev="sockfs" ino=10248 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
,W/.test.thalitest( 6107): type=1400 audit(0.0:147): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3222 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
W/.test.thalitest( 6107): type=1400 audit(0.0:148): avc: denied { ioctl } for path="socket:[8566]" dev="sockfs" ino=8566 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
W/.test.thalitest( 6107): type=1400 audit(0.0:149): avc: denied { ioctl } for path="/cust" dev="mmcblk0p42" ino=2 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=dir
W/.test.thalitest( 6107): type=1400 audit(0.0:150): avc: denied { ioctl } for path="socket:[30145]" dev="sockfs" ino=30145 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
I/art     ( 6107): Background sticky concurrent mark sweep GC freed 123357(11MB) AllocSpace objects, 23(7MB) LOS objects, 28% free, 39MB/55MB, paused 970us total 112.033ms
,W/jxcore-log( 6107): Platform android
W/jxcore-log( 6107): 
W/jxcore-log( 6107): Process ARCH arm
W/jxcore-log( 6107): 
,I/jxcore-log( 6107): JXcore Cordova bridge is ready!
I/jxcore-log( 6107): 
W/jxcore-log( 6107): JXcore engine is started
,I/jxcore-log( 6107): Toggling radios to true
I/jxcore-log( 6107): 
,D/BluetoothManagerService( 1029): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,D/BluetoothManagerService( 1029): enable():  mBluetooth =null mBinding = false
,D/BluetoothManagerService( 1029): Message: 1
D/BluetoothManagerService( 1029): MESSAGE_ENABLE: mBluetooth = null
D/WifiService( 1029): New client listening to asynchronous messages
D/LocationManagerService( 1029): getAllProviders()=[passive, gps, network]
D/Ulp_jni ( 1029): JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
D/Ulp_jni ( 1029): JNI:system_update. Event-4
I/ActivityManager( 1029): Start proc com.android.bluetooth for service com.android.bluetooth/.btservice.AdapterService: pid=6189 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008, 4002, 1023} abi=armeabi-v7a
,D/WifiServiceImplEx( 1029): setWifiEnabled: true pid=6107, uid=10311, package= com.test.thalitest, App Lable : ThaliTest
D/WifiService( 1029): setWifiEnabled: true pid=6107, uid=10311
E/WifiService( 1029): Invoking mWifiStateMachine.setWifiEnabled
D/LocationManagerService( 1029): getAllProviders()=[passive, gps, network]
D/Ulp_jni ( 1029): JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 1,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
D/Ulp_jni ( 1029): JNI:system_update. Event-4
E/WifiStateMachine( 1029):  InitialState CMD_START_SUPPLICANT 0 0
I/LGFTMITEM( 1029): [GET_FTM][id=6], offset=12288
D/WifiServiceImplEx( 1029): disconnect pid=6107, uid=10311, packageName=com.test.thalitest
D/WifiServiceImplEx( 1029): reconnect pid=6107, uid=10311, packageName=com.test.thalitest
,I/jxcore-log( 6107): Radios toggled
I/jxcore-log( 6107): 
E/WifiUtil( 1029): wfc_util_ffile_check_copy(): pid[1029] pDestFName[/data/misc/wifi/WCNSS_qcom_cfg.ini] pSourceFName[/system/etc/wifi/WCNSS_qcom_cfg.ini]
E/WifiUtil( 1029): wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
E/WifiUtil( 1029): wfc_util_ffile_check_copy(): pid[1029] pDestFName[/data/misc/wifi/WCNSS_qcom_wlan_nv.bin] pSourceFName[/system/etc/wifi/WCNSS_qcom_wlan_nv.bin]
E/WifiUtil( 1029): wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
I/WifiUtil( 1029): Intf0MacAddress=C49A027B60AC
E/WifiHW  ( 1029): unknown target_country: EU , set to default
E/WifiHW  ( 1029): [wifi_ensure_config_files] default country1 = GB
E/WifiHW  ( 1029): [wifi_ensure_config_files] default country2 = GB
,I/WifiUtil( 1029): gEnableBmps=1
,W/ResourcesManager( 6189): Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
,W/ResourcesManager( 6189): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 6189): Asset path '/system/framework/com.qcom.bluetooth.jar' does not exist or contains no resources.
W/ResourcesManager( 6189): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
D/BluetoothAdapterApp( 6189): Loading JNI Library
,D/BluetoothAdapterApp( 6189): REFCOUNT: Constructed com.android.bluetooth.btservice.AdapterApp@3daba5eb Instance Count = 1
,D/SoftapController(  309): Softap fwReload - Ok
,D/libc-netbsd(  309): default dns: query_ipv6=0, query_ipv4=0
D/CommandListener(  309): Setting iface cfg
D/CommandListener(  309): Trying to bring down wlan0
D/CommandListener(  309): Clearing all IP addresses on wlan0
D/Tethering( 1029): sendTetherStateChangedBroadcast 1, 0, 0
D/Tethering( 1029): InitialState.processMessage what=4
,D/DSQN    ( 1029): DNSproblemNotiEnabled is disabled ignore DNS fail CB
I/ActivityManager( 1029): Start proc com.android.settings for broadcast com.android.settings/.deviceinfo.UsbSettingsReceiver: pid=6227 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,D/Tethering( 1029): sendTetherStateChangedBroadcast 0, 0, 0
E/WifiHW  ( 1029): Cannot open "/system/etc/wifi/autojoinconfig.txt": No such file or directory
,D/BluetoothAdapterApp( 6189): onCreate
E/WifiStateMachine( 1029): Couldn't get getWiFiOffloadingIface : 
E/WifiStateMachine( 1029): useWiFiOffloading() : false
E/WifiStateMachine( 1029): CONFIG_LGE_WLAN_PATH : true
I/WifiServerServiceExt( 1029): WIFI_STATE_CHANGED_ACTION [2]
V/WfdStateTracker( 1945): WfdStateTracker handleDirectStateChangedEvent: 1
D/StatusBar.NetworkController( 1451): refreshViews: Data not connected!! Set no data type icon / Roaming
D/WifiMonitor( 1029): startMonitoring(wlan0) with mConnected = false
D/WifiMonitor( 1029): connecting to supplicant
E/WifiHW  ( 1029): Unable to open connection to supplicant on "@android:wpa_wlan0": No such file or directory
W/wpa_supplicant( 6242): type=1400 audit(0.0:151): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6843 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,W/wpa_supplicant( 6242): type=1400 audit(0.0:152): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6843 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
D/ProfileConfigQcom( 6189): [BTUI] HeadsetService is supported
D/ProfileConfigQcom( 6189): Adding HeadsetService
D/ProfileConfigQcom( 6189): [BTUI] A2dpService is supported
D/ProfileConfigQcom( 6189): Adding A2dpService
D/ProfileConfigQcom( 6189): [BTUI] HidService is supported
D/ProfileConfigQcom( 6189): Adding HidService
D/ProfileConfigQcom( 6189): [BTUI] HealthService is supported
D/ProfileConfigQcom( 6189): Adding HealthService
D/LGBluetoothFeatureConfig( 6189): isSupportPan() :  mTargetOp=OPEN
D/ProfileConfigQcom( 6189): [BTUI] PanService is supported
D/ProfileConfigQcom( 6189): Adding PanService
D/ProfileConfigQcom( 6189): [BTUI] GattService is supported
D/ProfileConfigQcom( 6189): Adding GattService
D/ProfileConfigQcom( 6189): [BTUI] BluetoothMapService is supported
D/ProfileConfigQcom( 6189): Adding BluetoothMapService
D/ProfileConfigQcom( 6189): [BTUI] HeadsetClientService is NOT supported
I/wpa_supplicant( 6242): Successfully initialized wpa_supplicant
,D/BluetoothManagerService( 1029): Message: 20
D/BluetoothManagerService( 1029): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@1e771205:true
D/BluetoothAdapterState( 6189): make
I/LGFMServiceAdapter( 6189): [FM] LGFMServiceAdapter : create
I/bluedroid-qcom( 6189): init
,I/BluetoothAdapterState( 6189): Entering OffState
,I/bte_conf( 6189): bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
I/bte_conf( 6189): bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
E/bt_osi_config( 6189): config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
I/bte_conf( 6189): bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
D/BTIF_CORE( 6189): [BTUI] lge_load_bluetooth_address
I/bluedroid-qcom( 6189): get_profile_interface socket
I/bluedroid-qcom( 6189): get_profile_interface map_client
W/bdaddr_loader( 6249): type=1400 audit(0.0:153): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6843 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
W/bdaddr_loader( 6249): type=1400 audit(0.0:154): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6843 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
I/wpa_supplicant( 6242): rfkill: Cannot open RFKILL control device
I/wpa_supplicant( 6242): [LGE_PATCH] unset P2P_CAPABLE to ifname wlan0
I/GKI_LINUX( 6189): gki_task_entry task_id=1 [BTIF] starting
D/BluetoothAdapterProperties( 6189): Address is:58:3F:54:73:64:C0
D/BluetoothManagerService( 1029): Bluetooth Adapter name changed to G3-1
D/BluetoothManagerService( 1029): Stored Bluetooth name: G3-1
D/BluetoothAdapterProperties( 6189): Name is: G3-1
D/BluetoothManagerService( 1029): BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
D/BluetoothManagerService( 1029): Message: 40
D/lge_bdaddr_loader( 6249): [BTUI] bdaddr_loader ::: START
D/lge_bdaddr_loader( 6249): [BTUI] bluetooth_load_bdaddress
I/LGFTMITEM( 6249): [GET_FTM][id=8], offset=16384
D/BluetoothManagerService( 1029): MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
D/lge_bdaddr_loader( 6249): [BTUI] bdaddr to set in property : 58:3F:54:73:64:C0
,I/bluedroid-qcom( 6189): config_hci_snoop_log
D/BluetoothManagerService( 1029): Calling onBluetoothServiceUp callbacks
D/BluetoothManagerService( 1029): Broadcasting onBluetoothServiceUp() to 7 receivers.
E/lge_bdaddr_loader( 6249): [BTUI] bluetooth_load_bdaddress : OK => 58:3F:54:73:64:C0
D/lge_bdaddr_loader( 6249): [BTUI] bdaddr_loader ::: END
W/ResourcesManager( 6227): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6227): Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
W/ResourcesManager( 6227): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 6227): Asset path '/system/framework/com.lge.bluetooth.jar' does not exist or contains no resources.
V/LGMDMManagerInternal( 6189): Create singleton instance
W/ResourcesManager( 6227): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
W/ResourcesManager( 6227): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
D/BluetoothAdapterState( 6189): CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
D/BluetoothAdapterProperties( 6189): Setting state to 11
I/BluetoothAdapterState( 6189): Bluetooth adapter state changed: 10-> 11
,D/BluetoothManagerService( 1029): Message: 60
D/BluetoothManagerService( 1029): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
D/BluetoothManagerService( 1029): Bluetooth State Change Intent: 10 -> 11
D/LGBluetoothAPIService( 1945): [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
I/[SystemUI]BluetoothHandler( 1451): Receive : BluetoothAdapter.ACTION_STATE_CHANGED
I/LGBluetoothServiceJni( 6189): classInitNative: succeeds
D/BluetoothBondStateMachine( 6189): make
D/BluetoothAdapterService( 6189): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3c79d192
D/LGBluetoothServiceAdapter( 6189): [BTUI] check adapter is available - false.
D/BluetoothAdapterService( 6189): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3c79d192
D/LGBluetoothServiceAdapter( 6189): [BTUI] check adapter is available - true : set adapter available.
D/LGBluetoothSettingsDBObserver( 6189): [BTUI] register observer for LG device name DB
I/BluetoothBondStateMachine( 6189): StableState(): Entering Off State
,I/wpa_supplicant( 6242): rfkill: Cannot open RFKILL control device
E/BluetoothAdapterService( 6189): File transfer profiles supported!!
E/BluetoothAdapterService( 6189): File transfer profiles supported!!
,D/BluetoothHeadset( 1029): Proxy object connected
D/BluetoothHeadset( 1849): Proxy object connected
D/HeadsetService( 6189): Received start request. Starting profile...
I/LGBluetoothHeadsetServiceJni( 6189): classInitNative: succeeds
D/LGBluetoothHfpAdapter( 6189): Version 1.6
D/BluetoothHeadset( 1849): Proxy object connected
D/LGBluetoothFeatureConfig( 6189): isPrivacyLogsEnabled : true
D/BluetoothHeadset( 1849): Proxy object connected
I/BluetoothHeadsetServiceJni( 6189): classInitNative: succeeds
D/HeadsetStateMachine( 6189): make
E/BluetoothAdapterService( 6189): File transfer profiles supported!!
E/BluetoothAdapterService( 6189): File transfer profiles supported!!
D/UsbSettingsReceiver( 6227): [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
D/UsbSettingsReceiver( 6227): [AUTORUN] sys.usb.config = ptp_only,adb
D/UsbSettingsReceiver( 6227): [AUTORUN] sys.usb.state = ptp_only,adb
D/UsbSettingsReceiver( 6227): [AUTORUN] persist.sys.usb.config = ptp_only,adb
,D/UsbSettingsReceiver( 6227): [AUTORUN] onReceive() : app userid = 0, current userid = 0
,E/BluetoothAdapterService( 6189): File transfer profiles supported!!
D/LgDataFeature( 6189): LgDataFeature() Constructor: none
D/LgDataFeature( 6189): LgDataFeature() Constructor Done, null
E/BluetoothAdapterService( 6189): File transfer profiles supported!!
D/HeadsetStateMachine( 6189): max_hf_connections = 1
I/bluedroid-qcom( 6189): get_profile_interface handsfree
V/ToneGenerator( 6189): ToneGenerator constructor: streamType=8, volume=1.000000
V/AudioPolicyService(  314): registerClient() client 0xb1427f00, uid 1002
V/AudioPolicyManager(  314): getOutput() device 2, stream 8, samplingRate 0, format 0, channelMask 3, flags 0
V/AudioPolicyManagerEx(  314): AudioPolicyManagerEx: getOutputForDevice
V/AudioPolicyManagerEx(  314): getOutput() returns output 2
,V/AudioSystem( 6189): getOutputSamplingRate() no output descriptor for output 2 in gOutputs
E/BluetoothAdapterService( 6189): File transfer profiles supported!!
V/AudioFlinger(  314): registerClient() client 0xb1433358, pid 6189
V/AudioSystem(  314): ioConfigChanged() event 0, ioHandle 2
,V/AudioSystem(  314): ioConfigChanged() opening already existing output! 2
V/AudioSystem( 1451): ioConfigChanged() event 0, ioHandle 2
V/AudioSystem( 1451): ioConfigChanged() opening already existing output! 2
V/AudioSystem( 3178): ioConfigChanged() event 0, ioHandle 2
V/AudioSystem( 3178): ioConfigChanged() opening already existing output! 2
V/AudioSystem( 1849): ioConfigChanged() event 0, ioHandle 2
V/AudioSystem( 1029): ioConfigChanged() event 0, ioHandle 2
V/AudioSystem( 1849): ioConfigChanged() opening already existing output! 2
V/AudioSystem( 1029): ioConfigChanged() opening already existing output! 2
V/ToneGenerator( 6189): Create Track: 0xb4928080
V/AudioTrack( 6189): set(): streamType 8, sampleRate 0, format 0x1, channelMask 0x1, frameCount 0, flags #4, notificationFrames 0, sessionId 0, transferType 1
V/AudioTrack( 6189): set() streamType 8, sampleRate 0, format 1, frameCount 0, flags 0004
V/AudioPolicyManager(  314): getOutputForAttr() usage=3, content=4, tag= flags=00000000
V/AudioPolicyManager(  314): getOutputForAttr() device 2, samplingRate 0, format 0, channelMask 3, flags 0
V/AudioPolicyManagerEx(  314): AudioPolicyManagerEx: getOutputForDevice
V/AudioPolicyManagerEx(  314): getOutput() returns output 2
V/AudioSystem( 6189): ioConfigChanged() event 0, ioHandle 2
V/AudioSystem( 6189): ioConfigChanged() new output samplingRate 48000, format 0x5 channel mask 0x3 frameCount 960 latency 50
I/AudioFlinger(  314): isAudioPlaybackHookOn() false
V/AudioPolicyManager(  314): getOutputForAttr() usage=3, content=4, tag= flags=00000000
V/AudioPolicyManager(  314): getOutputForAttr() device 2, samplingRate 48000, format 1, channelMask 1, flags 4
V/AudioPolicyManagerEx(  314): AudioPolicyManagerEx: getOutputForDevice
V/AudioPolicyManagerEx(  314): getOutput() returns output 2
V/AudioSystem( 6189): getLatency() output 2, latency 50
V/AudioSystem( 6189): getFrameCount() output 2, frameCount 960
V/AudioTrack( 6189): createTrack_l() output 2 afLatency 50
V/AudioFlinger(  314): [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
V/AudioFlinger(  314): [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
V/AudioSystem(  314): ioConfigChanged() event 0, ioHandle 4
V/AudioSystem(  314): ioConfigChanged() opening already existing output! 4
V/AudioSystem( 1849): ioConfigChanged() event 0, ioHandle 4
V/AudioSystem( 1849): ioConfigChanged() opening already existing output! 4
V/AudioSystem( 1451): ioConfigChanged() event 0, ioHandle 4
V/AudioSystem( 1451): ioConfigChanged() opening already existing output! 4
V/AudioSystem( 3178): ioConfigChanged() event 0, ioHandle 4
V/AudioSystem( 3178): ioConfigChanged() opening already existing output! 4
V/AudioFlinger(  314): [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
V/AudioFlinger(  314): [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
V/AudioFlinger(  314): createTrack() lSessionId: 16
V/AudioSystem( 1029): ioConfigChanged() event 0, ioHandle 4
V/AudioSystem( 1029): ioConfigChanged() opening already existing output! 4
V/AudioSystem( 6189): ioConfigChanged() event 0, ioHandle 4
V/AudioSystem( 6189): ioConfigChanged() new output samplingRate 48000, format 0x1 channel mask 0x3 frameCount 960 latency 80
V/AudioTrack( 6189): AUDIO_OUTPUT_FLAG_FAST successful; frameCount 480
V/AudioFlinger(  314): acquiring 16 from 6189, for 6189
V/AudioFlinger(  314):  added new entry for 16
V/ToneGenerator( 6189): ToneGenerator INIT OK, time: 162357
D/BluetoothAdapterService( 6189): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3c79d192
D/BluetoothAdapterService( 6189): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3c79d192
D/UsbSettingsControl( 6227): [AUTORUN] getUsbConnected() : connected=true
D/UsbSettingsReceiver( 6227): [AUTORUN] onReceive() : availableList=[wlan0]
D/UsbSettingsReceiver( 6227): [AUTORUN] onReceive() : activeList=[]
D/UsbSettingsReceiver( 6227): [AUTORUN] onReceive() : errorList=[]
D/HeadsetStateMachine( 61,89): Enter Disconnected: -2, size: 0
D/UsbSettingsControl( 6227): [AUTORUN] isAutorunTimer() : mAutorunChanging=false
D/UsbSettingsReceiver( 6227): [AUTORUN] onReceive() : TetherState Changed=wlan0
D/HeadsetPhoneState( 6189): [BTUI] listenForPhoneState : start = false
D/LGBluetoothHfpManager( 6189): [BTUI] listenForMultiSimPhoneState : start = false
D/HeadsetStateMachine( 6189): [BTUI] change sampling rate to 8000 when device is disconnected
V/AudioFlinger(  314): setParameters(): io 0, keyvalue bt_samplerate=8000, calling pid 6189
D/audio_hw_primary(  314): adev_set_parameters: enter: bt_samplerate=8000
V/voice   (  314): voice_set_parameters: enter: bt_samplerate=8000
V/compress_voip(  314): voice_extn_compress_voip_set_parameters: enter: bt_samplerate=8000
V/compress_voip(  314): voice_extn_compress_voip_set_parameters: exit
V/voice   (  314): voice_set_parameters: exit with code(0)
V/msm8974_platform_lge(  314): LGE_platform_set_parameters: enter: bt_samplerate=8000
V/msm8974_platform(  314): platform_set_parameters: enter: bt_samplerate=8000
D/A2dpService( 6189): Received start request. Starting profile...
V/msm8974_platform(  314): platform_set_parameters: exit with code(0)
V/lge_audio_loopback(  314): lge_platform_set_loopback_parameters: enter: 
V/audio_hw_primary(  314): adev_set_parameters: exit with code(0)
E/audio_a2dp_hw(  314): adev_set_parameters: ERROR: set param called even when stream out is null
D/BluetoothA2dp( 1029): Proxy object connected
I/BluetoothAvrcpServiceJni( 6189): classInitNative: succeeds
V/ToneGenerator( 6189): ToneGenerator destructor
V/ToneGenerator( 6189): stopTone
V/ToneGenerator( 6189): Delete Track: 0xb4928080
V/AudioPolicyService(  314): AudioCommandThread() adding release output 2
V/AudioPolicyService(  314): inserting command: 6 at index 0, num commands 0
V/AudioFlinger(  314): PlaybackThread::Track destructor
V/AudioPolicyService(  314): AudioCommandThread() waking up
V/AudioFlinger(  314): removeClient_l() pid 6189, calling pid 314
V/AudioPolicyService(  314): AudioCommandThread() processing release output 2
V/AudioPolicyManager(  314): releaseOutput() 2
V/AudioPolicyService(  314): AudioCommandThread() going to sleep
V/Avrcp   ( 6189): make
V/AudioTrack( 6189): ~AudioTrack, releasing session id from 6189 on behalf of 6189
D/Avrcp   ( 6189): [BTUI] Use Native AVRCP : init jni
D/UsbSettingsControl( 6227): [AUTORUN] setTetherStatus() : status=false
I/bluedroid-qcom( 6189): get_profile_interface avrcp
V/AudioFlinger(  314): releasing 16 from 6189 for 6189
V/AudioFlinger(  314):  decremented refcount to 0
V/AudioFlinger(  314): purging stale effects
I/ActivityManager( 1029): Killing 5487:com.lge.appbox.client/u0a11 (adj 15): empty #17
W/Process ( 1029): Unable to open /proc/6253/status
V/LGMDMManager( 6189): Create singleton instance
I/BluetoothAdapterState( 6189): Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
I/wpa_supplicant( 6242): [LGE_WLAN_PATCH]P2P 5GHz support level:2(0:no 1:gconly 2:gconly_UNII1 3:full)
,I/wpa_supplicant( 6242): p2p0: CTRL-EVENT-AVOID-FREQ ranges=
,I/wpa_supplicant( 6242): wlan0: CTRL-EVENT-SCAN-STARTED 
W/libprocessgroup( 1029): failed to open /acct/uid_10011/pid_5487/cgroup.procs: No such file or directory
,D/UsbSettingsReceiver( 6227): [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
D/UsbSettingsReceiver( 6227): [AUTORUN] sys.usb.config = ptp_only,adb
D/UsbSettingsReceiver( 6227): [AUTORUN] sys.usb.state = ptp_only,adb
D/UsbSettingsReceiver( 6227): [AUTORUN] persist.sys.usb.config = ptp_only,adb
D/UsbSettingsReceiver( 6227): [AUTORUN] onReceive() : app userid = 0, current userid = 0
,D/UsbSettingsControl( 6227): [AUTORUN] getUsbConnected() : connected=true
D/UsbSettingsReceiver( 6227): [AUTORUN] onReceive() : availableList=[]
D/UsbSettingsReceiver( 6227): [AUTORUN] onReceive() : activeList=[]
D/UsbSettingsReceiver( 6227): [AUTORUN] onReceive() : errorList=[]
D/UsbSettingsControl( 6227): [AUTORUN] isAutorunTimer() : mAutorunChanging=false
D/UsbSettingsControl( 6227): [AUTORUN] setTetherStatus() : status=false
V/AudioManager( 6189): registerRemoteController: size of Media player list: 0
,E/AudioManager( 6189): No RCC entry present to update
E/RemoteController( 6189): Cannot set synchronization mode on an unregistered RemoteController
I/BluetoothAvrcpQcomServiceJni( 6189): classInitQcomNative: succeeds
,D/LGBluetoothAvrcpQcomAdapter( 6189): [BTUI] Use QCOM AVRCP 1.5 : init jni, browsing = false
I/BluetoothAvrcpQcomServiceJni( 6189): initQcomNative: succeeds
I/ActivityManager( 1029): Start proc com.lge.formmanager for broadcast com.lge.formmanager/.FormServiceReceiver: pid=6257 uid=10026 gids={50026, 9997, 3003, 1028} abi=armeabi-v7a
,D/LGBluetoothAvrcpQcomAdapter( 6189): [BTUI] [+] updateMediaPlayerInfo
,V/SIM_STK ( 1029): Menu title from STK is T-Mobile
V/SIM_STK ( 1029): Menu title from STK is T-Mobile
,I/art     ( 1029): Explicit concurrent mark sweep GC freed 26497(1365KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 44MB/66MB, paused 1.449ms total 109.218ms
,W/ActivityManager( 1029): getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
,D/LGBluetoothAvrcpQcomAdapter( 6189): [BTUI] installed app name: Music
D/LGBluetoothAvrcpQcomAdapter( 6189): [BTUI] installed app name: Google Play Music
D/LGBluetoothAvrcpQcomAdapter( 6189): [BTUI] === MediaPlayerInfo (playerId:0) ===
D/LGBluetoothAvrcpQcomAdapter( 6189): [BTUI]          displayName: Music
D/LGBluetoothAvrcpQcomAdapter( 6189): [BTUI]          packageName: com.lge.music
D/LGBluetoothAvrcpQcomAdapter( 6189): [BTUI]          playState: 2 (PAUSED)
D/LGBluetoothAvrcpQcomAdapter( 6189): [BTUI] === MediaPlayerInfo (playerId:1) ===
D/LGBluetoothAvrcpQcomAdapter( 6189): [BTUI]          displayName: Google Play Music
D/LGBluetoothAvrcpQcomAdapter( 6189): [BTUI]          packageName: com.google.android.music
D/LGBluetoothAvrcpQcomAdapter( 6189): [BTUI]          playState: 2 (PAUSED)
D/LGBluetoothAvrcpQcomAdapter( 6189): [BTUI] [-] updateMediaPlayerInfo
I/BluetoothA2dpServiceJni( 6189): classInitNative
I/BluetoothA2dpServiceJni( 6189): classInitNative: succeeds
D/A2dpStateMachine( 6189): make
I/bluedroid-qcom( 6189): get_profile_interface a2dp
I/GKI_LINUX( 6189): gki_task_entry task_id=2 [A2DP-MEDIA] starting
I/LGBluetoothA2dpServiceJni( 6189): classInitNative: succeeds
,I/LGBluetoothA2dpAdapter( 6189): [BTUI] getInstance : create [LGBluetoothA2dpAdapter]
D/BluetoothAdapterService( 6189): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3c79d192
D/A2dpStateMachine( 6189): Enter Disconnected: -2
I/BluetoothHidServiceJni( 6189): classInitNative: succeeds
D/HidService( 6189): Received start request. Starting profile...
I/bluedroid-qcom( 6189): get_profile_interface hidhost
D/BluetoothAdapterService( 6189): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3c79d192
I/BluetoothHealthServiceJni( 6189): classInitNative: succeeds
D/HealthService( 6189): Received start request. Starting profile...
I/bluedroid-qcom( 6189): get_profile_interface health
I/LGBluetoothHealthServiceJni( 6189): classInitNative: succeeds
D/BluetoothAdapterService( 6189): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3c79d192
I/BluetoothPanServiceJni( 6189): classInitNative(L105): succeeds
D/PanService( 6189): Received start request. Starting profile...
D/BluetoothPanServiceJni( 6189): initializeNative(L110): pan
I/bluedroid-qcom( 6189): get_profile_interface pan
I/ActivityManager( 1029): Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=6284 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
I/LGBluetoothPanAdapter( 6189): [BTUI] getInstance : create [LGBluetoothPanAdapter]
D/BluetoothAdapterService( 6189): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3c79d192
D/HeadsetStateMachine( 6189): Proxy object connected
D/LGBluetoothHfpAdapter( 6189): [BTUI] queryPhoneState
D/LGBluetoothHfpAdapter( 6189): Try to query the phonestate on bind
,D/BluetoothPhoneService.BluetoothLTECall( 1849):  call mBluetoothHeadset.phoneStateChanged()
I/BtGatt.JNI( 6189): classInitNative(L901): classInitNative: Success!
W/FormManager( 6257): Network not available. Please check & try again.
W/BluetoothHeadset( 1849): Proxy not attached to service
D/BluetoothHeadset( 1849): java.lang.Throwable
D/BluetoothHeadset( 1849): 	at android.bluetooth.BluetoothHeadset.phoneStateChanged(BluetoothHeadset.java:826)
D/BluetoothHeadset( 1849): 	at com.android.phone.BluetoothPhoneService$BluetoothLTECall.handleQueryPhoneState(BluetoothPhoneService.java:1527)
D/BluetoothHeadset( 1849): 	at com.android.phone.BluetoothPhoneService$BluetoothLTECall.access$700(BluetoothPhoneService.java:1360)
D/BluetoothHeadset( 1849): 	at com.android.phone.BluetoothPhoneService$1.handleMessage(BluetoothPhoneService.java:268)
D/BluetoothHeadset( 1849): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/BluetoothHeadset( 1849): 	at android.os.Looper.loop(Looper.java:135)
D/BluetoothHeadset( 1849): 	at android.app.ActivityThread.main(ActivityThread.java:5274)
D/BluetoothHeadset( 1849): 	at java.lang.reflect.Method.invoke(Native Method)
D/BluetoothHeadset( 1849): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/BluetoothHeadset( 1849): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
D/BluetoothHeadset( 1849): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
D/BtGatt.DebugUtils( 6189): handleDebugAction() action=null
D/BtGatt.GattService( 6189): Received start request. Starting profile...
D/BtGatt.GattService( 6189): start()
I/bluedroid-qcom( 6189): get_profile_interface gatt
D/BtGatt.AdvertiseManager( 6189): advertise manager created
D/BluetoothAdapterService( 6189): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3c79d192
D/BluetoothAdapterService( 6189): Profile still not running:com.android.bluetooth.gatt.GattService
D/HeadsetStateMachine( 6189): Disconnected process message: 10, size: 0
D/HeadsetPhoneState( 6189): sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
D/BluetoothAdapterService( 6189): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3c79d192
D/HeadsetStateMachine( 6189): Disconnected process message: 11, size: 0
I/LGBluetoothMapAdapter( 6189): [BTUI] getInstance : create [LGBluetoothMapAdapter]
V/BluetoothMapService( 6189): BluetoothMapBinder()
,D/BluetoothMapService( 6189): Received start request. Starting profile...
D/BluetoothMapService( 6189): start()
D/BluetoothMapEmailSettingsLoader( 6189): Found 0 applications
D/BluetoothMapEmailAppObserver( 6189): createReceiver()
D/BluetoothMapEmailAppObserver( 6189): initObservers()
D/BluetoothMapEmailAppObserver( 6189): getEnabledAccountItems()
V/FormManager( 6257): Network unavailable.
D/BluetoothAdapterService( 6189): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3c79d192
V/BluetoothPbapReceiver( 6189): PbapReceiver onReceive 
V/BluetoothPbapReceiver( 6189): ***********action = android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothPbapReceiver( 6189): ***********state = 11
,D/BluetoothAdapterService( 6189): Profile still not running:com.android.bluetooth.gatt.GattService
D/BluetoothAdapterService( 6189): Profile still not running:com.android.bluetooth.gatt.GattService
,D/BluetoothAdapterService( 6189): Profile still not running:com.android.bluetooth.gatt.GattService
V/PanService( 6189): [BTUI] SIM Extra State :ABSENT
D/BluetoothAdapterService( 6189): Profile still not running:com.android.bluetooth.gatt.GattService
D/BluetoothAdapterService( 6189): Profile still not running:com.android.bluetooth.map.BluetoothMapService
V/BluetoothMapService( 6189): Handler(): got msg=1
D/BluetoothAdapterState( 6189): CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
I/bluedroid-qcom( 6189): enable
I/bt_hci_bdroid( 6189): init
I/GKI_LINUX( 6189): gki_task_entry task_id=0 [BTU] starting
I/bt-btu  ( 6189): btu_task pending for preload complete event
,I/bt_vendor( 6189): bt-vendor : init
I/bt_vendor( 6189): bt-vendor : get_bt_soc_type
E/bt_vendor( 6189): get_bt_soc_type: Failed to get soc type
I/bt_vendor( 6189): init: Local BD Address : c0:64:73:54:3f:58
D/bt_userial_mct( 6189): userial_init
D/bt_hci_bdroid( 6189): set_power 1
I/bt_vendor( 6189): bt-vendor : BT_VND_OP_POWER_CTRL: On
I/bt_vendor( 6189): Starting hciattach daemon
I/bt_vendor( 6189): try to set true
W/sh      ( 6308): type=1400 audit(0.0:155): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6843 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
W/sh      ( 6308): type=1400 audit(0.0:156): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6843 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
I/ActivityManager( 1029): Start proc com.lge.lifetracker for broadcast com.lge.lifetracker/.receiver.HealthDeviceReceiver: pid=6309 uid=10037 gids={50037, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
,I/qcom-bluetooth( 6314): /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  
V/FormManager( 6257): Network unavailable.
,D/PCSuite ( 6284): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
I/ActivityManager( 1029): Killing 5509:com.android.contacts/u0a19 (adj 15): empty #17
,V/WiFiOffLoadBroadcast( 6227): WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
D/WifiService( 1029): New client listening to asynchronous messages
,I/qcom-bluetooth( 6334): /system/etc/init.qcom.bt.sh: Transport : smd 
I/qcom-bluetooth( 6336): /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
D/LgDataFeature( 6227): LgDataFeature() Constructor: none
D/LgDataFeature( 6227): LgDataFeature() Constructor Done, null
,D/WiFiOffLoadUpdatePriority( 6227): remove : truetruefalse
D/WiFiOffLoadUpdatePriority( 6227): remove2
V/WiFiOffLoadSharedPrefsUtils( 6227): save wifi state
V/WiFiOffLoadSharedPrefsUtils( 6227): save remove
D/WiFiOffLoadBroadcast( 6227): mLastConnectedNetwork from SharedPrefsUtils for wifioffloading : null
D/WiFiOffLoadBroadcast( 6227): S: false, R: true
I/qcom-bluetooth( 6338): /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
I/qcom-bluetooth( 6339): /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> 
,E/wpa_supplicant( 6242): USIM:  scard_init function
I/wpa_supplicant( 6242): Trying to associate with SSID 'NG700'
I/qcom-bluetooth( 6340): /system/etc/init.qcom.bt.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
I/qcom-bluetooth( 6341): /system/etc/init.qcom.bt.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> 
,I/ActivityManager( 1029): Killing 5831:com.lge.email/u0a23 (adj 15): empty #17
,I/libmdmdetect( 6343): ESOC framework not supported
E/Diag_Lib( 6343):  Diag_LSM_Init: Failed to open handle to diag driver, error = 13
D/bthci_qcomm_linux( 6343): [BTUI] bt_hci_qcomm_pfal_get_bdaddress: Get BDADDR from bluedroid prop (58:3F:54:73:64:C0)
D/bthci_qcomm_common( 6343): [BTUI] bt_hci_qcomm_init:
,D/bthci_qcomm_common( 6343): [BTUI]     BDADDR: 58:3F:54:73:64:C0
D/bthci_qcomm_common( 6343): [BTUI]     BR/EDR: Class 1
D/bthci_qcomm_common( 6343): [BTUI]     LE: Class 2
D/bthci_qcomm_common( 6343): [BTUI]     Ref Clock: 32M
D/btqsocnvmtags( 6343): [BTUI] init_riva_entries: set NORMAL power settings
,I/wpa_supplicant( 6242): wlan0: Associated with c0:ff:d4:d3:aa:48
,I/wpa_supplicant( 6242): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 6242): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
W/libprocessgroup( 1029): failed to open /acct/uid_10023/pid_5831/cgroup.procs: No such file or directory
W/libprocessgroup( 1029): failed to open /acct/uid_10019/pid_5509/cgroup.procs: No such file or directory
I/rmt_storage(  305): rmt_storage_connect_cb: clnt_h=0x5 conn_h=0xb6403090
I/rmt_storage(  305): rmt_storage_rw_iovec_cb: /boot/modem_fs2: clnt_h=0x2: req_h=0x9 msg_id=3: R/W request received
I/rmt_storage(  305): wakelock acquired: 1, error no: 42
I/rmt_storage(  305): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 Unblock worker thread (th_id: -1236806912)
,D/Tethering( 1029): sendTetherStateChangedBroadcast 1, 0, 0
,D/UsbSettingsReceiver( 6227): [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
D/UsbSettingsReceiver( 6227): [AUTORUN] sys.usb.config = ptp_only,adb
D/UsbSettingsReceiver( 6227): [AUTORUN] sys.usb.state = ptp_only,adb
D/UsbSettingsReceiver( 6227): [AUTORUN] persist.sys.usb.config = ptp_only,adb
D/UsbSettingsReceiver( 6227): [AUTORUN] onReceive() : app userid = 0, current userid = 0
D/UsbSettingsControl( 6227): [AUTORUN] getUsbConnected() : connected=true
D/UsbSettingsReceiver( 6227): [AUTORUN] onReceive() : availableList=[wlan0]
D/UsbSettingsReceiver( 6227): [AUTORUN] onReceive() : activeList=[]
D/UsbSettingsReceiver( 6227): [AUTORUN] onReceive() : errorList=[]
D/UsbSettingsControl( 6227): [AUTORUN] isAutorunTimer() : mAutorunChanging=false
D/UsbSettingsReceiver( 6227): [AUTORUN] onReceive() : TetherState Changed=wlan0
D/UsbSettingsControl( 6227): [AUTORUN] setTetherStatus() : status=false
E/ActivityThread( 6309): Failed to find provider info for com.lge.lgaccount.provider
,W/LG Account v2.2( 6309): No ProfileInfo entries
I/LG Account v2.2( 6309): isEnabled: false
I/Feature ( 6309): [Lifetracker]ver: 4.21.112(40211120)
I/Feature ( 6309): [Lifetracker]Country: EU
I/Feature ( 6309): [Lifetracker]Operator: OPEN
I/Feature ( 6309): [Lifetracker]Ranking support: false
I/Feature ( 6309): [Lifetracker]Comfort support: false
I/Feature ( 6309): [Lifetracker]Accessory: true
I/Feature ( 6309): [Lifetracker]Health device: true
I/Feature ( 6309): [Lifetracker]Extra Pedometer: false
I/Feature ( 6309): [Lifetracker]Blood glucose device: false
I/Feature ( 6309): [Lifetracker]Device Number: 3
D/BluetoothPermissionRequest( 6227): onReceive
D/LGBluetoothFeatureConfig( 6227):  get() - isFeatureLoaded : false
I/rmt_storage(  305): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0x9 msg_id=3: Bytes written = 1572864
I/rmt_storage(  305): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0x9 msg_id=3: Send response: res=0 err=0
I/rmt_storage(  305): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 About to block rmt_storage client thread (th_id: -1236806912) wakelock released: 1, error no: 0
I/rmt_storage(  305): 
,I/rmt_storage(  305): rmt_storage_disconnect_cb: clnt_h=0x0x5 conn_h=0x0xb6403090
E/Diag_Lib(  899): [IMS_FATAL]| 3347 | 909 |ims-rtp-daemon ims_rtp_qmi_handler_thread_func waiting on select thread>
D/BluetoothManagerService( 1029): Message: 20
D/BluetoothManagerService( 1029): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@3d6f65b:true
D/LGBluetoothResetSettingReceiver( 6227): return without doing reset settings.
,I/ActivityManager( 1029): Killing 5530:com.android.gallery3d/u0a27 (adj 15): empty #17
E/WifiStateMachine( 1029):  SupplicantStartingState CMD_SET_OPERATIONAL_MODE 1 0
E/WifiStateMachine( 1029):  SupplicantStartingState CMD_START_DRIVER 0 0
E/WifiStateMachine( 1029):  SupplicantStartingState CMD_SET_HIGH_PERF_MODE 0 0
E/WifiStateMachine( 1029):  DefaultState CMD_SET_HIGH_PERF_MODE 0 0
E/WifiStateMachine( 1029):  SupplicantStartingState CMD_DISCONNECT 0 0
E/WifiStateMachine( 1029):  DefaultState CMD_DISCONNECT 0 0
E/WifiStateMachine( 1029):  SupplicantStartingState CMD_RECONNECT 0 0
E/WifiStateMachine( 1029):  DefaultState CMD_RECONNECT 0 0
E/WifiStateMachine( 1029):  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1029):  DefaultState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1029):  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1029):  DefaultState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1029):  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1029):  DefaultState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1029):  SupplicantStartingState SUP_CONNECTION_EVENT 0 0
D/WifiNative-wlan0( 1029): doString: [DRIVER MACADDR]
D/WifiNative-wlan0( 1029):    returned Macaddr = c4:9a:02:7b:60:ac
D/WifiStateMachine( 1029): MAC Addr from driver = c4:9a:02:7b:60:ac
D/WifiOffDelayIfNotUsed( 1029): setPowerSaveActivated(false)
E/WifiStateMachine( 1029): Couldn't get getWiFiOffloadingIface : 
E/WifiStateMachine( 1029): useWiFiOffloading() : false
E/WifiStateMachine( 1029): CONFIG_LGE_WLAN_PATH : true
W/libprocessgroup( 1029): failed to open /acct/uid_10027/pid_5530/cgroup.procs: No such file or directory
D/LGBluetoothOppAdapter( 6189): [BTUI] getInstance : create [LGBluetoothOppAdapter]
,W/Settings( 1029): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1029): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/StatusBar.NetworkController( 1451): refreshViews: Data not connected!! Set no data type icon / Roaming
D/WifiNative-wlan0( 1029): doBoolean: SET update_config 1
D/WfdService( 1945): Waiting for WifiP2p enabling
,D/WifiNative-wlan0( 1029): SET update_config 1: returned true
D/WifiConfigStore( 1029): Loading config and enabling all networks 
D/WifiNative-wlan0( 1029): doString: [LIST_NETWORKS]
D/WifiNative-wlan0( 1029):    returned network id / ssid / bssid / flags 0	NG700	any	[CURRENT]
D/PCSuite ( 6284): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
E/WifiConfigStore( 1029): readNetworkVariablesFromSupplicantFile key=psk
I/WifiServerServiceExt( 1029): WIFI_STATE_CHANGED_ACTION [3]
I/WifiServerServiceExt( 1029): batteryPsActivateMsgHandler : state:0 event:3
,V/BluetoothFtpReceiver( 6189): BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
V/WiFiOffLoadBroadcast( 6227): WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
E/WifiConfigStore( 1029): readNetworkVariableFromSupplicantFile ssid=["NG700"] key=psk
V/BluetoothSapReceiver( 6189): [BTUI] checkServiceStart
E/WifiConfigStore( 1029): Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
V/BluetoothSapReceiver( 6189): [BTUI] region:EU country:EU
V/BluetoothSapReceiver( 6189): SapReceiver onReceive 
W/FormManager( 6257): Network not available. Please check & try again.
D/WifiStateMachine( 1029): enableVerboseLogging : level 2
V/BluetoothSapReceiver( 6189): action = android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothSapReceiver( 6189):  Bluetooth Adapter state = 11
V/FormManager( 6257): Network unavailable.
D/WifiNative-wlan0( 1029): doBoolean: SET device_name g3_global_com
D/WifiNative-wlan0( 1029): SET device_name g3_global_com: returned true
D/WifiNative-wlan0( 1029): doBoolean: SET manufacturer LGE
D/WifiNative-wlan0( 1029): SET manufacturer LGE: returned true
D/WifiNative-wlan0( 1029): doBoolean: SET model_name LG-D855
D/WifiNative-wlan0( 1029): SET model_name LG-D855: returned true
D/WifiNative-wlan0( 1029): doBoolean: SET model_number LG-D855
D/WiFiOffLoadUpdatePriority( 6227): remove : truetruetrue
D/WifiNative-wlan0( 1029): SET model_number LG-D855: returned true
D/WifiNative-wlan0( 1029): doBoolean: SET serial_number LGD8553bed2d08
D/WifiNative-wlan0( 1029): SET serial_number LGD8553bed2d08: returned true
,D/WifiNative-wlan0( 1029): doBoolean: SET config_methods physical_display virtual_push_button
D/WifiNative-wlan0( 1029): SET config_methods physical_display virtual_push_button: returned true
D/WifiNative-wlan0( 1029): doBoolean: SET device_type 10-0050F204-5
D/WifiNative-wlan0( 1029): SET device_type 10-0050F204-5: returned true
,I/ActivityManager( 1029): Start proc com.lge.settings.easy for broadcast com.lge.settings.easy/com.lge.settings.bluetooth.LGBluetoothProfileConnectionReceiver: pid=6354 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
D/WifiStateMachine( 1029): Setting OUI to DA-A1-19
D/WifiNative-wlan0( 1029): doBoolean: SCAN_INTERVAL 120
,D/WfdsService( 1945): Supplicant Connection state is changed : true
D/WfdsService( 1945): DefaultState - WIFI_SUPPLICANT_CONNECTED
D/WfdsService( 1945): Set the WFDS Monitor: true
D/WifiNative-wlan0( 1029): SCAN_INTERVAL 120: returned true
D/WifiNative-HAL( 1029): Setting external_sim to 1
D/WifiNative-wlan0( 1029): doBoolean: SET external_sim 1
V/FormManager( 6257): Network unavailable.
D/WfdsMonitor( 1945): WfdsMonitorThread create
D/WfdsMonitor( 1945): WFDS Monitor is created and started
D/WfdsService( 1945): WiFi: Supplicant connection re-established
D/WifiNative-wlan0( 1029): SET external_sim 1: returned true
I/WifiNative-HAL( 1029): startHal
E/wifi    ( 1029): getStaticLongField sWifiHalHandle 0x989338dc
E/WifiHAL ( 1029): Could not connect handle
D/wifi    ( 1029): halHandle = 0x0, mVM = 0xb487c280, mCls = 0x502132
I/WifiNative-HAL( 1029): Could not start hal
D/WifiStateMachine( 1029): Setting OUI to DA-A1-19
I/WifiNative-HAL( 1029): startHal
E/wifi    ( 1029): getStaticLongField sWifiHalHandle 0x9893385c
E/WifiHAL ( 1029): Could not connect handle
D/wifi    ( 1029): halHandle = 0x0, mVM = 0xb487c280, mCls = 0x302076
I/WifiNative-HAL( 1029): Could not start hal
D/WifiNative-wlan0( 1029): doBoolean: STA_AUTOCONNECT 1
W/Settings( 6020): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiNative-wlan0( 1029): STA_AUTOCONNECT 1: returned true
D/WifiNative-wlan0( 1029): doBoolean: DRIVER BTCOEXSCAN-STOP
I/wpa_supplicant( 6242): wpa_driver_nl80211_ext_driver_cmd BTCOEXSCAN-STOP
D/WifiNative-wlan0( 1029): DRIVER BTCOEXSCAN-STOP: returned true
D/WifiHS20( 1029): hidePasspointNotification off =false
D/WifiNative-wlan0( 1029): doBoolean: DRIVER RXFILTER-STOP
I/wpa_supplicant( 6242): wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
D/WifiNative-wlan0( 1029): DRIVER RXFILTER-STOP: returned true
D/WifiNative-wlan0( 1029): doBoolean: DRIVER RXFILTER-REMOVE 3
I/wpa_supplicant( 6242): wpa_driver_nl80211_ext_driver_cmd RXFILTER-REMOVE 3
D/WifiNative-wlan0( 1029): DRIVER RXFILTER-REMOVE 3: returned true
D/WifiNative-wlan0( 1029): doBoolean: DRIVER RXFILTER-START
I/wpa_supplicant( 6242): wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
,D/WifiNative-wlan0( 1029): DRIVER RXFILTER-START: returned true
D/WifiNative-wlan0( 1029): doBoolean: DRIVER RXFILTER-STOP
I/wpa_supplicant( 6242): wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
D/WifiNative-wlan0( 1029): DRIVER RXFILTER-STOP: returned true
D/WifiNative-wlan0( 1029): doBoolean: DRIVER RXFILTER-REMOVE 2
I/wpa_supplicant( 6242): android_multicast_filter_startstop : multicast filter set
D/WifiNative-wlan0( 1029): DRIVER RXFILTER-REMOVE 2: returned true
D/WifiNative-wlan0( 1029): doBoolean: DRIVER RXFILTER-START
I/wpa_supplicant( 6242): wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
D/WifiNative-wlan0( 1029): DRIVER RXFILTER-START: returned true
E/WifiNative: ( 1029): [163,366,508 us] RECONNECT  stack:logDbg - reconnect - enter - invokeEnterMethods - performTransitions
D/WifiNative-wlan0( 1029): doBoolean: RECONNECT
D/WifiNative-wlan0( 1029): RECONNECT: returned true
D/WifiNative-wlan0( 1029): doString: [STATUS]
D/WifiMonitor( 1029): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
D/WifiNative-wlan0( 1029):    returned bssid=c0:ff:d4:d3:aa:48 ssid=NG700 id=0 mode=station pairwise_cipher=CCMP group_cipher=CCMP key_mgmt=WPA2-PSK wpa_state=COMPLETED p2p_device_address=02:9a:02:7b:60:ac address=c4:9a:02:7b:60:ac uuid=530d3fd0-1ba3-5409-a336-ff4e42af59a2
E/WifiMonitor( 1029): WifiMonitor:wlan0 cnt=0 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/WifiNative-wlan0( 1029): doBoolean: DRIVER SETSUSPENDMODE 1
I/wpa_supplicant( 6242): wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 1
D/WifiNative-wlan0( 1029): DRIVER SETSUSPENDMODE 1: returned true
D/WifiNative-wlan0( 1029): doBoolean: SET ps 1
D/WifiNative-wlan0( 1029): SET ps 1: returned true
D/LGWifiP2pService( 1029): P2pDisabledState{ when=0 what=131203 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiStateMachine( 1029):  DisconnectedState CMD_SET_OPERATIONAL_MODE 1 0
E/WifiStateMachine( 1029):  DisconnectedState CMD_START_DRIVER 0 0
I/StatusBar.NetworkController( 1451): networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1451): mWifiConnected = false, mWifiLevel = 0
E/WifiStateMachine( 1029):  ConnectModeState CMD_START_DRIVER 0 0
E/WifiStateMachine( 1029):  DriverStartedState CMD_START_DRIVER 0 0
E/WifiStateMachine( 1029):  DisconnectedState what:132106 1 0
E/WifiStateMachine( 1029):  ConnectModeState what:132106 1 0
E/WifiStateMachine( 1029):  DriverStartedState what:132106 1 0
,I/WifiServerServiceExt( 1029): setWifiDualbandAPConnection band : 1
W/Settings( 1029): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1029): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1029): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
D/CommandListener(  309): Setting iface cfg
D/CommandListener(  309): Trying to bring up p2p0
D/WifiMonitor( 1029): startMonitoring(p2p0) with mConnected = true
D/LGWifiP2pService( 1029): P2pEnablingState
D/LGWifiP2pService( 1029): P2pEnablingState{ when=0 what=147457 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1029): P2p socket connection successful
D/LGWifiP2pService( 1029): P2pEnabledState
D/LGWifiP2pService( 1029): sending p2p connection changed broadcast
D/WifiNative-p2p0( 1029): doBoolean: SET persistent_reconnect 1
E/CtrlSupplicant( 1945): Access OK "@android:wpa_wlan0"
E/CtrlSupplicant( 1945): Succeed to open control connection
D/WifiNative-p2p0( 1029): SET persistent_reconnect 1: returned true
D/WifiScanningService( 1029): SCAN_AVAILABLE : 3
D/RttService( 1029): SCAN_AVAILABLE : 3
E/CtrlSupplicant( 1945): Succeed to open monitor connection
D/WifiScanningService( 1029): DefaultState got{ when=-1ms what=160006 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-p2p0( 1029): doBoolean: SET device_name G3-1
I/WifiNative-HAL( 1029): startHal
D/RttService( 1029): DefaultState got{ when=-1ms what=160512 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-p2p0( 1029): SET device_name G3-1: returned true
D/LGWifiP2pService( 1029): [LGE_P2P] initializeP2pSettings() check postfix
D/LGWifiP2pService( 1029): before postfix = G3-1
D/WifiServerServiceExt( 1029): postfix byte check : 4
D/LGWifiP2pService( 1029): after postfix = G3-1
E/wifi    ( 1029): getStaticLongField sWifiHalHandle 0x94d2499c
D/WifiNative-p2p0( 1029): doBoolean: SET p2p_ssid_postfix -G3-1
E/WifiHAL ( 1029): Could not connect handle
D/wifi    ( 1029): halHandle = 0x0, mVM = 0xb487c280, mCls = 0x202072
I/WifiNative-HAL( 1029): Could not start hal
E/WifiScanningService( 1029): could not start HAL
D/StatusBar.NetworkController( 1451): refreshViews: Data not connected!! Set no data type icon / Roaming
E/wpa_supplicant( 6242): nWIFIDualbandAPConnection: 1
D/WfdsMonitor( 1945): Supplicant connection established
E/WifiStateMachine( 1029):  DisconnectedState what:132096 -100 0
D/WifiNative-p2p0( 1029): SET p2p_ssid_postfix -G3-1: returned true
D/WifiNative-p2p0( 1029): doBoolean: SET device_type 10-0050F204-5
D/WifiNative-p2p0( 1029): SET device_type 10-0050F204-5: returned true
D/WifiNative-p2p0( 1029): doBoolean: SET config_methods virtual_push_button physical_display keypad
V/WfdStateTracker( 1945): WfdStateTracker handleDirectStateChangedEvent: 2
D/WfdsService( 1945): WifiP2pState is changed : true
D/WifiNative-p2p0( 1029): SET config_methods virtual_push_button physical_display keypad: returned true
D/WifiNative-p2p0( 1029): doBoolean: P2P_SET conc_pref p2p
E/WifiStateMachine( 1029):  ConnectModeState what:132096 -100 0
D/WifiNative-p2p0( 1029): P2P_SET conc_pref p2p: returned true
D/WifiNative-HAL( 1029): p2pGetDeviceAddress
E/WifiStateMachine( 1029):  DriverStartedState what:132096 -100 0
I/WifiServerServiceExt( 1029): set CMD_DISCONNECT_RSSI_LVL : -100
E/wpa_supplicant( 6242): disconnect_rssi_lvl: -100
D/WfdsService( 1945): Connected to the supplicant for wfds
D/WifiNative-HAL( 1029): p2pGetDeviceAddress returning 02:9a:02:7b:60:ac
D/WfdsJNI ( 1945): doCommand: WFDS_SET TRUE
I/wpa_supplicant( 6242): WFDS: wfds_supplicant_wfds_cmd: cmd = SET TRUE
D/WfdsJNI ( 1945): doCommand: WFDS_GET_MAC_ADDRESS
I/wpa_supplicant( 6242): WFDS: wfds_supplicant_wfds_cmd: cmd = GET_MAC_ADDRESS
D/WfdsJNI ( 1945): doCommand: IFNAME=wlan0 GET_CAPABILITY channels
D/WfdsService( 1945): selectPreferre,dScanChannel [36]
D/WfdsService( 1945): STATE : WfdsEnabledState - enter: this device mac 02:9a:02:7b:60:ac
D/WfdsService( 1945): DefaultState - WFDS_ENABLE(DISABLE)
D/WfdsService( 1945): WIFI_P2P_CONNECTION_CHANGED_ACTION
D/LGWifiP2pService( 1029): DeviceAddress: 02:9a:02:7b:60:ac
D/WifiNative-p2p0( 1029): doBoolean: P2P_FLUSH
D/WifiNative-p2p0( 1029): P2P_FLUSH: returned true
D/WfdsService( 1945): isConnected: false
D/WifiNative-p2p0( 1029): doBoolean: P2P_SERVICE_FLUSH
D/WifiNative-p2p0( 1029): P2P_SERVICE_FLUSH: returned true
D/WifiNative-p2p0( 1029): doString: [LIST_NETWORKS]
D/WifiNative-p2p0( 1029):    returned OK
D/WifiNative-p2p0( 1029): doBoolean: SAVE_CONFIG
D/WifiNative-p2p0( 1029): SAVE_CONFIG: returned false
D/LGWifiP2pService( 1029): sending p2p persistent groups changed broadcast
D/LGWifiP2pService( 1029): InactiveState
D/LGWifiP2pService( 1029): InactiveState{ when=-2ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1029): P2pEnabledState{ when=-2ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-p2p0( 1029): doBoolean: DRIVER COUNTRY CZ
I/WfdStateTracker( 1945): handleP2pThisDeviceChanged
D/WfdsService( 1945): WIFI_P2P_THIS_DEVICE_CHANGED_ATCION
D/WfdsService( 1945): Update P2p Interface State: 3
D/WifiService( 1029): New client listening to asynchronous messages
W/ResourcesManager( 6354): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,I/wpa_supplicant( 6242): wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
I/wpa_supplicant( 6242): p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
D/WifiNative-p2p0( 1029): DRIVER COUNTRY CZ: returned true
D/LGWifiP2pService( 1029): InactiveState{ when=-25ms what=139287 arg2=1 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1029): P2pEnabledState{ when=-25ms what=139287 arg2=1 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1029): DefaultState{ when=-25ms what=139287 arg2=1 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 6242): [LGE_PATCH] driver_cmd() country:CZ
D/LGWifiP2pService( 1029): InactiveState{ when=-25ms what=139283 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 6242): p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
D/LGWifiP2pService( 1029): P2pEnabledState{ when=-25ms what=139283 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1029): DefaultState{ when=-25ms what=139283 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1029): InactiveState{ when=-26ms what=139287 arg2=1 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1029): P2pEnabledState{ when=-26ms what=139287 arg2=1 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1029): DefaultState{ when=-26ms what=139287 arg2=1 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1029): InactiveState{ when=-1ms what=139285 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1029): P2pEnabledState{ when=-1ms what=139285 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 6242): p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
D/LGWifiP2pService( 1029): DefaultState{ when=-1ms what=139285 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiStateMachine( 1029):  DisconnectedState CMD_GET_CONFIGURED_NETWORKS uid=1000 1000 0 num=1
E/WifiServerServiceExt( 1029): No p2p device connected
E/WifiStateMachine( 1029):  ConnectModeState CMD_GET_CONFIGURED_NETWORKS uid=1000 1000 0 num=1
W/WfdsService( 1945): DefaultState - msg [9441285] is not handled
D/WfdsMonitor( 1945): Event [CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
E/WifiStateMachine( 1029):  DisconnectedState CMD_SET_COUNTRY_CODE 1 0 cz
D/WfdsMonitor( 1945): Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
D/WfdsMonitor( 1945): Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
D/WifiMonitor( 1029): Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
E/WifiMonitor( 1029): WifiMonitor:p2p0 cnt=1 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
E/WifiStateMachine( 1029):  ConnectModeState CMD_SET_COUNTRY_CODE 1 0 cz
E/WifiMonitor( 1029): handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
E/WifiMonitor( 1029): handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
D/WifiMonitor( 1029): Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
E/WifiMonitor( 1029): WifiMonitor:p2p0 cnt=2 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
E/WifiMonitor( 1029): handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
E/WifiMonitor( 1029): handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
D/WifiMonitor( 1029): Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
E/WifiMonitor( 1029): WifiMonitor:p2p0 cnt=3 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
E/WifiStateMachine( 1029):  DriverStartedState CMD_SET_COUNTRY_CODE 1 0 cz
E/WifiMonitor( 1029): handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
D/WifiNative-wlan0( 1029): doBoolean: DRIVER COUNTRY CZ
E/WifiMonitor( 1029): handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
I/wpa_supplicant( 6242): wpa_driver_nl80211_ex,t_driver_cmd COUNTRY CZ
I/wpa_supplicant( 6242): wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
I/wpa_supplicant( 6242): [LGE_PATCH] driver_cmd() country:CZ
I/wpa_supplicant( 6242): p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
D/WifiNative-wlan0( 1029): DRIVER COUNTRY CZ: returned true
D/LGWifiP2pService( 1029): InactiveState{ when=0 what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1029): P2pEnabledState{ when=0 what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 6242): p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
E/WifiStateMachine( 1029):  DisconnectedState CMD_SET_FREQUENCY_BAND 0 0
E/WifiStateMachine( 1029):  ConnectModeState CMD_SET_FREQUENCY_BAND 0 0
D/WfdsMonitor( 1945): Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
D/WfdsMonitor( 1945): Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
E/WifiStateMachine( 1029):  DriverStartedState CMD_SET_FREQUENCY_BAND 0 0
D/WifiMonitor( 1029): Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
E/WifiMonitor( 1029): WifiMonitor:wlan0 cnt=4 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
D/WifiNative-wlan0( 1029): doBoolean: DRIVER SETBAND 0
E/WifiMonitor( 1029): handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
E/WifiMonitor( 1029): handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
I/wpa_supplicant( 6242): wpa_driver_nl80211_ext_driver_cmd SETBAND 0 - interface name wlan0
D/WifiMonitor( 1029): Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
I/wpa_supplicant( 6242): wlan0: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
E/WifiMonitor( 1029): WifiMonitor:p2p0 cnt=5 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
E/WifiMonitor( 1029): handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
E/WifiMonitor( 1029): handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
D/WifiMonitor( 1029): Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
E/WifiMonitor( 1029): WifiMonitor:p2p0 cnt=6 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
E/WifiMonitor( 1029): handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
E/WifiMonitor( 1029): handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
D/WifiMonitor( 1029): Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN]
E/WifiMonitor( 1029): WifiMonitor:wlan0 cnt=7 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
E/WifiMonitor( 1029): handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
E/WifiMonitor( 1029): handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
D/WifiNative-wlan0( 1029): DRIVER SETBAND 0: returned true
D/WifiNative-wlan0( 1029): doBoolean: BSS_FLUSH 0
D/WifiNative-wlan0( 1029): BSS_FLUSH 0: returned true
D/WifiNative-wlan0( 1029): doBoolean: SCAN
I/wpa_supplicant( 6242): wlan0: CTRL-EVENT-SCAN-STARTED 
D/WifiMonitor( 1029): Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1029): WifiMonitor:wlan0 cnt=8 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1029): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1029): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
D/WifiNative-wlan0( 1029): SCAN: returned true
E/WifiStateMachine( 1029):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 0 0 rt=163428  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine( 1029):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 0 0 rt=163429  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
W/Settings( 1029): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1029): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1029): NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
E/WifiStateMachine( 1029):  DisconnectedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
I/StatusBar.NetworkController( 1451): networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1451): mWifiConnected = false, mWifiLevel = 0
E/WifiStateMachine( 1029):  ConnectModeState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
E/WifiStateMachine( 1029):  DriverStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
E/WifiStateMachine( 1029):  SupplicantStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
E/WifiStateMachine( 1029):  DefaultState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
D/StatusBar.NetworkController( 1451): refreshViews: Data not connected!! Set no data type icon / Roaming
E/WifiStateMachine( 1029):  DisconnectedState CMD_SAVE_CONFIG uid=1000 0 0
E/WifiStateMachine( 1029):  ConnectModeState CMD_SAVE_CONFIG uid=1000 0 0
D/WifiNative-wlan0( 1029): doBoolean: SAVE_CONFIG
D/WifiNative-wlan0( 1029): SAVE_CONFIG: returned true
D/AuthorizationBluetoothService( 2108): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
D/WiFiOffLoadUpdatePriority( 6227): remove1
V/WiFiOffLoadSharedPrefsUtils( 6227): save remove
D/WifiServerServiceExt( 1029): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1029): setSupplicantStateCOMPLETED
D/WiFiOffLoadBroadcast( 6227): mLastConnectedNetwork from SharedPrefsUtils for wifioffloading : null
D/WiFiOffLoadBroadcast( 6227): S: false, R: false
E/WifiStateMachine( 1029):  DisconnectedState CMD_GET_CONFIGURED_NETWORKS uid=1000 1000 0 num=1
,E/WifiStateMachine( 1029):  ConnectModeState CMD_GET_CONFIGURED_NETWORKS uid=1000 1000 0 num=1
D/WiFiOffLoadUpdatePriority( 6227): saved SSID: "NG700"
D/WiFiOffLoadUpdatePriority( 6227): connected SSID: null
D/WiFiOffLoadUpdatePriority( 6227): private wpa: "NG700" 300
D/WifiServiceImplEx( 1029): addOrUpdateNetwork pid=6227, uid=1000, packageName=android.uid.system:1000
E/addOrUpdateNetwork( 1029):  uid = 1000 SSID "NG700" nid=0
E/WifiStateMachine( 1029):  DisconnectedState CMD_ADD_OR_UPDATE_NETWORK uid=1000 0 0 "NG700"WPA_PSK prio=300 status=0
E/WifiStateMachine( 1029):  ConnectModeState CMD_ADD_OR_UPDATE_NETWORK uid=1000 0 0 "NG700"WPA_PSK prio=300 status=0
E/WifiConfigStore( 1029):  key="NG700"WPA_PSK netId=0 uid=0/1000
D/WifiServerServiceExt( 1029): addOrUpdateNetwork: mThisIsFirstEnableing = false
D/WifiNative-wlan0( 1029): doBoolean: SET_NETWORK 0 ssid 4e47373030
D/WifiNative-wlan0( 1029): SET_NETWORK 0 ssid 4e47373030: returned true
D/WifiNative-wlan0( 1029): doBoolean: SET_NETWORK 0 key_mgmt WPA-PSK
D/WifiNative-wlan0( 1029): SET_NETWORK 0 key_mgmt WPA-PSK: returned true
D/WifiNative-wlan0( 1029): doBoolean: SET_NETWORK 0 proto WPA RSN
D/WifiNative-wlan0( 1029): SET_NETWORK 0 proto WPA RSN: returned true
D/WifiNative-wlan0( 1029): doBoolean: SET_NETWORK 0 pairwise TKIP CCMP
D/WifiNative-wlan0( 1029): SET_NETWORK 0 pairwise TKIP CCMP: returned true
D/WifiNative-wlan0( 1029): doBoolean: SET_NETWORK 0 group WEP40 WEP104 TKIP CCMP
D/WifiNative-wlan0( 1029): SET_NETWORK 0 group WEP40 WEP104 TKIP CCMP: returned true
D/WifiNative-wlan0( 1029): doBoolean: SET_NETWORK 0 priority 300
D/WifiNative-wlan0( 1029): SET_NETWORK 0 priority 300: returned true
E/WifiConfigStore( 1029): will read network variables netId=0
E/WifiConfigStore( 1029): writeIpAndProxyConfigurationsOnChange: "NG700" -> "NG700" path: /data/misc/wifi/ipconfig.txt
E/WifiConfigStore( 1029):  writeKnownNetworkHistory() num networks:1 needWrite=false
D/WiFiOffLoadUpdatePriority( 6227):  ssid "NG700" prio 300
D/WiFiOffLoadUpdatePriority( 6227): configuration updated: 0
E/WifiStateMachine( 1029):  DisconnectedState CMD_SAVE_CONFIG uid=1000 0 0
E/WifiStateMachine( 1029):  ConnectModeState CMD_SAVE_CONFIG uid=1000 0 0
D/WifiNative-wlan0( 1029): doBoolean: SAVE_CONFIG
D/WifiNative-wlan0( 1029): SAVE_CONFIG: returned true
D/WiFiOffLoadUpdatePriority( 6227): configuration saved: true
I/ActivityManager( 1029): Killing 5153:com.wsandroid.suite.lge/1000 (adj 15): empty #17
,W/libprocessgroup( 1029): failed to open /acct/uid_1000/pid_5153/cgroup.procs: No such file or directory
,D/LGDMClient( 3924): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
D/LGDMClient( 3924): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
W/ContextImpl( 3924): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
W/ContextImpl( 3924): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,D/LGDMClient( 3924): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=3, isUserType=1
,D/LGDMClient( 3924): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
D/LGDMClient( 3924): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
,I/ActivityManager( 1029): Start proc com.wsandroid.suite.lge for broadcast com.wsandroid.suite.lge/com.wavesecure.core.WSAndroidSystemIntentReceiver: pid=6375 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,I/art     (  346): Explicit concurrent mark sweep GC freed 707(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 437us total 22.573ms
,I/art     (  346): Explicit concurrent mark sweep GC freed 7(240B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 1.280ms total 18.250ms
,I/art     (  346): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 285us total 15.740ms
,W/ResourcesManager( 6375): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
D/PluginManager( 6375): init()
,E/QC-QMI  ( 6343): qmi_client [6343] 13: failed to locate client data
,E/QC-QMI  (  464): qmuxd: RX on fd=32 returned error=0 errno[2:No such file or directory]
E/QC-QMI  (  464): QMUX qmux_client_id=13 not found in qmux client list, unable to remove
D/BluetoothManagerService( 1029): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/jxcore-log( 6107): Got Device Bluetooth address: 58:3F:54:73:64:C0
I/jxcore-log( 6107): 
I/jxcore-log( 6107): my name is : LGE-LG-D855_PT108
I/jxcore-log( 6107): 
I/qcom-bluetooth( 6393): /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 58:3f:54:73:64:c0 
,I/qcom-bluetooth( 6397): /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
I/jxcore-log( 6107): attempting to connect to test coordinator
I/jxcore-log( 6107): 
I/jxcore-log( 6107): check test folder
I/jxcore-log( 6107): 
I/jxcore-log( 6107): found test : ./testFindPeers.js
I/jxcore-log( 6107): 
,I/jxcore-log( 6107): found test : ./testReConnect.js
I/jxcore-log( 6107): 
,I/bt_vendor( 6189): bluetooth satus is on
D/bt_hci_bdroid( 6189): preload
D/bt_userial_mct( 6189): userial_open(port:0)
I/bt_vendor( 6189): bt-vendor : BT_VND_OP_USERIAL_OPEN
I/jxcore-log( 6107): found test : ./testSendData.js
I/jxcore-log( 6107): 
I/bt_vendor( 6189): Done intiailizing UART
,I/bt_vendor( 6189): Done intiailizing UART
I/bt_userial_mct( 6189): CMD=66, EVT=66, ACL_Out=67, ACL_In=67
I/bt_vendor( 6189): Bluetooth Firmware and transport layer are initialized
I/bt-btu  ( 6189): btu_task received preload complete event
D/bt_userial_mct( 6189): Entering userial_read_thread()
W/bt-l2cap( 6189): L2CAP - L2CA_Register() called for PSM: 0x0001
W/bt-l2cap( 6189): L2CAP - L2CA_Register() called for PSM: 0x001f
W/bt-l2cap( 6189): L2CAP - L2CA_Register() called for PSM: 0x0003
I/        ( 6189): BTE_InitTraceLevels -- TRC_HCI
I/        ( 6189): BTE_InitTraceLevels -- TRC_L2CAP
I/        ( 6189): BTE_InitTraceLevels -- TRC_RFCOMM
I/        ( 6189): BTE_InitTraceLevels -- TRC_AVDT
I/        ( 6189): BTE_InitTraceLevels -- TRC_AVRC
I/        ( 6189): BTE_InitTraceLevels -- TRC_A2D
I/        ( 6189): BTE_InitTraceLevels -- TRC_BNEP
I/        ( 6189): BTE_InitTraceLevels -- TRC_BTM
I/        ( 6189): BTE_InitTraceLevels -- TRC_HID_HOST
I/        ( 6189): BTE_InitTraceLevels -- TRC_GAP
I/        ( 6189): BTE_InitTraceLevels -- TRC_PAN
I/        ( 6189): BTE_InitTraceLevels -- TRC_SDP
I/        ( 6189): BTE_InitTraceLevels -- TRC_GATT
,I/        ( 6189): BTE_InitTraceLevels -- TRC_SMP
I/        ( 6189): BTE_InitTraceLevels -- TRC_BTAPP
I/        ( 6189): BTE_InitTraceLevels -- TRC_BTIF
W/bt-btm  ( 6189): btm_decode_ext_features_page Secure conn Controller support Enabled
E/bt-btm  ( 6189): BTM_SecRegister:p_cb_info->p_le_callback == 0xa01ce061 
E/bt-btm  ( 6189): BTM_SecRegister: btm_cb.api.p_le_callback = 0xa01ce061 
,E/bt-btif ( 6189): Calling BTA_HhEnable
W/bt-l2cap( 6189): L2CAP - L2CA_Register() called for PSM: 0x0019
W/bt-l2cap( 6189): L2CAP - L2CA_Register() called for PSM: 0x0017
W/bt-l2cap( 6189): L2CAP - L2CA_Register() called for PSM: 0x001b
E/bt-btif ( 6189): btif_storage_get_adapter_property service_mask:0x2140040
W/bt-l2cap( 6189): L2CAP - L2CA_Register() called for PSM: 0x0011
W/bt-l2cap( 6189): L2CAP - L2CA_Register() called for PSM: 0x0013
D/BluetoothAdapterProperties( 6189): Address is:58:3F:54:73:64:C0
D/BluetoothAdapterProperties( 6189): Name is: G3-1
D/BluetoothManagerService( 1029): Bluetooth Adapter name changed to G3-1
D/BluetoothManagerService( 1029): Stored Bluetooth name: G3-1
,D/BluetoothAdapterProperties( 6189): Scan Mode:20
I/jxcore-log( 6107): Test app app.js loaded
I/jxcore-log( 6107): 
D/BluetoothAdapterProperties( 6189): Discoverable Timeout:120
D/bt_hci_bdroid( 6189): postload
D/bt_hci_bdroid( 6189): Used up Tx Cmd credits
W/bt-l2cap( 6189): L2CAP - L2CA_Register() called for PSM: 0x000f
W/bt-smp  ( 6189): Key(LSB ~ MSB) = 0a 3c a6 fe eb 17 6a 79 a6 1f 0a 0b f9 50 a0 5f 
W/bt-smp  ( 6189): Plain text(LSB ~ MSB) = 0a ef 6f 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 6189): Encrypted text(LSB ~ MSB) = 48 4f 76 37 05 5a 9c 92 28 b7 e6 a8 93 be 7f dc 
W/bt-btm  ( 6189): Stopping oneshot timer
D/bt_hci_bdroid( 6189): Used up Tx Cmd credits
D/bt_hci_bdroid( 6189): Used up Tx Cmd credits
D/bt_hci_bdroid( 6189): Used up Tx Cmd credits
D/bt_hci_bdroid( 6189): Used up Tx Cmd credits
E/bt_mct  ( 6189): hci lib postload completed
,I/jxcore-log( 6107): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6107): 
D/bte_conf( 6189): Device ID record 1 : primary
D/bte_conf( 6189):   vendorId            = 00c4
D/bte_conf( 6189):   vendorIdSource      = 0001
D/bte_conf( 6189):   product             = 13a1
D/bte_conf( 6189):   version             = 1000
D/bte_conf( 6189):   clientExecutableURL = 
D/bte_conf( 6189):   serviceDescription  = 
D/bte_conf( 6189):   documentationURL    = 
D/bte_conf( 6189): bte_load_did_conf no section named DID2.
I/Choreographer( 6107): Skipped 150 frames!  The application may be doing too much work on its main thread.
D/BluetoothPanServiceJni( 6189): control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
D/BluetoothAdapterState( 6189): CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
D/BluetoothAdapterProperties( 6189): ScanMode =  20
D/BluetoothAdapterProperties( 6189): State =  11
D/BluetoothAdapterProperties( 6189): mDiscoverableTimeout = 120
V/LGBluetoothServiceAdapter( 6189): [BTUI] state:11, scanmode:20, timeout:120
D/BluetoothAdapterProperties( 6189): Setting state to 12
W/sh      ( 6401): type=1400 audit(0.0:157): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6843 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
W/sh      ( 6401): type=1400 audit(0.0:158): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6843 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
I/BluetoothAdapterState( 6189): Bluetooth adapter state changed: 11-> 12
D/BluetoothManagerService( 1029): Message: 60
D/BluetoothManagerService( 1029): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
I/BluetoothAdapterState( 6189): Entering On State
D/BluetoothManagerService( 1029): Broadcasting onBluetoothStateChange(true) to 5 receivers.
D/BluetoothHeadset( 1849): onBluetoothStateChange: up=true
D/btif_config_util( 6189): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
W/bt-smp  ( 6189): Key(LSB ~ MSB) = 0a 3c a6 fe eb 17 6a 79 a6 1f 0a 0b f9 50 a0 5f 
W/bt-smp  ( 6189): Plain text(LSB ~ MSB) = 7e 8e 66 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 6189): Encrypted text(LSB ~ MSB) = a1 ca 65 99 cf 14 11 b0 09 a2 eb 4e b4 06 89 ec 
W/bt-btm  ( 6189): Stopping oneshot timer
D/LGBluetoothServiceAdapter( 6189): [BTUI] OnState
D/LGBluetoothServiceAdapter( 6189): [BTUI]         global_name: G3-1
D/LGBluetoothServiceAdapter( 6189): [BTUI]         local_name: G3-1
D/BluetoothAdapterService( 6189): [BTUI] autoConnect() : not allowed
D/BluetoothHeadset( 1849): onBluetoothStateChange: up=true
,W/bt-smp  ( 6189): Key(LSB ~ MSB) = 0a 3c a6 fe eb 17 6a 79 a6 1f 0a 0b f9 50 a0 5f 
W/bt-smp  ( 6189): Plain text(LSB ~ MSB) = 6b 02 6e 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 6189): Encrypted text(LSB ~ MSB) = e9 7e 31 13 25 a0 62 f5 a0 2a 66 7d a3 af b8 1b 
W/bt-btm  ( 6189): Stopping oneshot timer
D/BluetoothHeadset( 1849): onBluetoothStateChange: up=true
D/BluetoothA2dp( 1029): onBluetoothStateChange: up=true
D/BluetoothHeadset( 1029): onBluetoothStateChange: up=true
I/chromium( 6107): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,D/BluetoothManagerService( 1029): BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
W/bt-smp  ( 6189): Key(LSB ~ MSB) = 0a 3c a6 fe eb 17 6a 79 a6 1f 0a 0b f9 50 a0 5f 
W/bt-smp  ( 6189): Plain text(LSB ~ MSB) = c0 cb 59 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 6189): Encrypted text(LSB ~ MSB) = 26 ce b5 66 fc ce 81 1f c9 98 33 76 f1 f5 ac aa 
W/bt-btm  ( 6189): Stopping oneshot timer
E/BluetoothManagerService( 1029): Fail to bind to: Intent { act=android.bluetooth.IQBluetooth }
D/BluetoothManagerService( 1029): Bluetooth State Change Intent: 11 -> 12
D/LGBluetoothAPIService( 1945): [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
I/[SystemUI]BluetoothHandler( 1451): Receive : BluetoothAdapter.ACTION_STATE_CHANGED
D/LGBluetoothAPIService( 1945): Message: 1
D/LGBluetoothAPIService( 1945): MESSAGE_BOOT_COMPLETED
,I/qcom-bt-wlan-coex( 6412): /system/etc/init.qcom.coex.sh: btwlancoex/abtfilt not available 
W/ExternalStrings( 6375): load override strings
W/ExternalStrings( 6375): java.lang.RuntimeException: Unexpected tag, got eat-comment
W/ExternalStrings( 6375): 	at com.mcafee.plugin.af.a(Unknown Source)
W/ExternalStrings( 6375): 	at com.mcafee.plugin.ac.b(Unknown Source)
W/ExternalStrings( 6375): 	at com.mcafee.plugin.ak.d(Unknown Source)
W/ExternalStrings( 6375): 	at com.mcafee.plugin.ak.a(Unknown Source)
W/ExternalStrings( 6375): 	at com.mcafee.app.s.getClassLoader(Unknown Source)
W/ExternalStrings( 6375): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5001)
W/ExternalStrings( 6375): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4609)
W/ExternalStrings( 6375): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4549)
W/ExternalStrings( 6375): 	at android.app.ActivityThread.access$1500(ActivityThread.java:148)
W/ExternalStrings( 6375): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1344)
W/ExternalStrings( 6375): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/ExternalStrings( 6375): 	at android.os.Looper.loop(Looper.java:135)
W/ExternalStrings( 6375): 	at android.app.ActivityThread.main(ActivityThread.java:5274)
W/ExternalStrings( 6375): 	at java.lang.reflect.Method.invoke(Native Method)
W/ExternalStrings( 6375): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/ExternalStrings( 6375): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
W/ExternalStrings( 6375): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
D/StatusProvider( 6375): onCreate
D/BluetoothManagerService( 1029): Message: 40
D/BluetoothManagerService( 1029): MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
I/BluetoothMapService( 6189): onReceive: android.bluetooth.adapter.action.STATE_CHANGED
D/BluetoothMapService( 6189): STATE_ON
W/bt-smp  ( 6189): Key(LSB ~ MSB) = 0a 3c a6 fe eb 17 6a 79 a6 1f 0a 0b f9 50 a0 5f 
W/bt-smp  ( 6189): Plain text(LSB ~ MSB) = d1 8d 6d 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 6189): Encrypted text(LSB ~ MSB) = d1 49 58 7d 05 2d 0f 47 39 de 4a 5a 5a f4 ae 21 
W/bt-btm  ( 6189): Stopping oneshot timer
I/LGBluetoothAPIService( 1945): [BTUI] LGBluetoothAPIService Binding Success
D/LGBluetoothDeviceModeControllManager( 6189): [BTUI] checkDeviceModeAndSet, sinkMode : false
I/chromium( 6107): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,W/ContextImpl( 6227): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
D/LGBluetoothAPIServer( 6189): [BTUI] onCreate()
D/LGBluetoothAPIServer( 6189): [BTUI] onBind()
V/BluetoothMapService( 6189): Handler(): got msg=1
D/LGBluetoothAPIService( 1945): [BTUI] LGBluetoothAPIServiceConnection: connected to LGBluetoothAPIAdapter
D/BluetoothMapMasInstance( 6189): Map Service startRfcommSocketListener
D/LGBluetoothAPIService( 1945): Message: 100
D/LGBluetoothAPIService( 1945): MESSAGE_BLUETOOTH_SERVICE_CONNECTED
D/BluetoothMapMasInstance( 6189): MAS initSocket()
D/BluetoothMapMasInstance( 6189):   masId = 00
D/BluetoothMapMasInstance( 6189):   msgTypes = 0e
D/BluetoothMapMasInstance( 6189):   masName = SMS/MMS
D/BluetoothMapMasInstance( 6189):   SDP string = 000eSMS/MMS
,D/BluetoothManagerService( 1029): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
W/BluetoothAdapter( 6189): getBluetoothService() called with no BluetoothManagerCallback
D/LGBluetoothServiceAdapter( 6189): [BTUI] createSocketChannel FD=73 mFd=0
V/BluetoothMapMasInstance( 6189): Succeed to create listening socket 
D/BluetoothMapMasInstance( 6189): Accepting socket connection...
D/BluetoothAdapterProperties( 6189): Discoverable Timeout:120
D/LGBluetoothDeviceModeControllManager( 6189): adapterPropertyChangedCallback on  LGAdapter : do nothing - 9
D/BluetoothAdapterProperties( 6189): Scan Mode:21
D/LGBluetoothDeviceModeControllManager( 6189): getDeviceMode  deviceMode 0
D/LocalBluetoothProfileManager( 6227): Adding local A2DP profile
D/BluetoothAdapterService( 6189): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3c79d192
V/BluetoothPbapService( 6189): Pbap Service onCreate
V/BluetoothPbapService( 6189): Starting PBAP service
,D/LGBluetoothPbapAdapter( 6189): [BTUI] getInstance : create
V/BluetoothPbapService( 6189): action: android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothPbapService( 6189): state: 12
V/BluetoothPbapReceiver( 6189): PbapReceiver onReceive 
V/BluetoothPbapReceiver( 6189): ***********action = android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothPbapReceiver( 6189): ***********state = 12
D/BluetoothManagerService( 1029): Message: 30
V/BluetoothPbapService( 6189): Handler(): got msg=1
V/BluetoothPbapService( 6189): Pbap Service startRfcommSocketListener
V/BluetoothPbapService( 6189): Pbap Service initSocket
D/BluetoothManagerService( 1029): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/LocalBluetoothProfileManager( 6227): Adding local HEADSET profile
W/BluetoothAdapter( 6189): getBluetoothService() called with no BluetoothManagerCallback
D/LGBluetoothServiceAdapter( 6189): [BTUI] createSocketChannel FD=75 mFd=73
V/BluetoothPbapService( 6189): Succeed to create listening socket 
V/BluetoothPbapService( 6189): Accepting socket connection...
D/BluetoothManagerService( 1029): Message: 30
,D/BluetoothManagerService( 1029): Message: 30
V/Signer  ( 6375): override build config not found
D/Signer  ( 6375): value of property debug is false
D/BluetoothManagerService( 1029): Message: 30
D/LocalBluetoothProfileManager( 6227): Adding local MAP profile
D/BluetoothMap( 6227): Create BluetoothMap proxy object
,D/BluetoothManagerService( 1029): Message: 30
D/BluetoothManagerService( 1029): Message: 30
D/LocalBluetoothProfileManager( 6227): LocalBluetoothProfileManager construction complete
V/BluetoothPbapService( 6189): Pbap Service onBind
D/LGBluetoothUserBindClient( 6227): [BTUI] initUserBindClient
W/ContextImpl( 6227): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.android.settings.bluetooth.LGBluetoothUserBindClient.initUserBindClient:90 com.android.settings.bluetooth.LGBluetoothUserBindClient.<init>:55 com.android.settings.bluetooth.LGBluetoothUserBindClient.getInstance:47 
,D/DockEventReceiver( 6227): finishStartingService: stopping service
,D/BluetoothA2dp( 6227): Proxy object connected
D/A2dpProfile( 6227): Bluetooth service connected
D/LGMDMWrapper( 6375): Found class 'com.mcafee.lgmdm.LGMDMWrapper$DataWipe'.
D/LGMDMWrapper( 6375): Found class 'com.mcafee.lgmdm.LGMDMWrapper$DownloadMode'.
D/LGMDMWrapper( 6375): Found class 'com.mcafee.lgmdm.LGMDMWrapper$HardReset'.
D/LGMDMWrapper( 6375): Found class 'com.mcafee.lgmdm.LGMDMWrapper$HardwareKeyReset'.
,D/LGMDMWrapper( 6375): Found class 'com.mcafee.lgmdm.LGMDMWrapper$RemoveDeviceAdmin'.
D/LGMDMWrapper( 6375): Found class 'com.mcafee.lgmdm.LGMDMWrapper$UnknownSourceInstallation'.
D/LGMDMWrapper( 6375): Found class 'com.mcafee.lgmdm.LGMDMWrapper$Usb'.
D/LGMDMWrapper( 6375): Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbDebugging'.
D/LGMDMWrapper( 6375): Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbHostStorage'.
D/LGMDMWrapper( 6375): Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbMediaTransfer'.
D/LGMDMWrapper( 6375): Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbPictureTransfer'.
D/LGMDMWrapper( 6375): Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbStorage'.
D/LGMDMWrapper( 6375): Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbTethering'.
V/LGMDMManager( 6375): Create singleton instance
,D/LGMDMWrapper( 6375): LG MDM library v4.0.0 is available on this device.
,D/BluetoothHeadset( 6227): Proxy object connected
,D/HeadsetProfile( 6227): Bluetooth service connected
D/BluetoothInputDevice( 6227): Proxy object connected
D/HidProfile( 6227): Bluetooth service connected
D/BluetoothPan( 6227): BluetoothPAN Proxy object connected
D/PanProfile( 6227): Bluetooth service connected
D/BluetoothMap( 6227): Proxy object connected
D/MapProfile( 6227): Bluetooth service connected
D/BluetoothMap( 6227): getConnectedDevices()
V/BluetoothMapService( 6189): getConnectedDevices()
D/BluetoothPbap( 6227): Proxy object connected
D/PbapServerProfile( 6227): Bluetooth service connected
D/LGBluetoothUserBindClient( 6227): [BTUI] onServiceConnected
D/BluetoothPermissionRequest( 6227): onReceive
,D/LGBluetoothFeatureConfig( 6227): isPrivacyLogsEnabled : true
D/LGBluetoothUtils( 6227): [BTUI] FileNotFound: readProperty
D/LGBluetoothResetSettingReceiver( 6227): return without doing reset settings.
V/BluetoothOppReceiver( 6189): Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_ON
I/LGBluetoothOppAdapter( 6189): [BTUI] startOppService()
V/BluetoothOppManager( 6189): restoreApplicationData! falsefalsenullnull
,D/PostponalbeReceiver( 6375): WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
W/ContextImpl( 6375): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
I/PCSuite ( 6284): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
,D/PCSuite ( 6284): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 6284): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 6227): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 6227): MCCMNC not supported: null
D/LGBluetoothFeatureConfig( 6189): isPrivacyLogsEnabled : true
V/BtOppService( 6189): onCreate
,V/BluetoothOppNotification( 6189): send message
V/BtOppService( 6189): Deleted complete outbound shares, number =  0
,V/BtOppService( 6189): Deleted complete inbound failed shares, number = 0
V/BluetoothOppProvider( 6189): starting query, database is not null; projection[0] is _id; selection is direction=1 AND status=200 AND visibility=1; selectionArgs is null; sort is _id.
I/ActivityManager( 1029): Start proc com.lge.qremote for broadcast com.lge.qremote/.settings.WiFiStateReceiver: pid=6429 uid=10112 gids={50112, 9997, 1028, 1015, 3003, 3002} abi=armeabi
V/BluetoothOppProvider( 6189): created cursor android.database.sqlite.SQLiteCursor@3a4caf8f on behalf of 
V/BtOppService( 6189): Starting RfcommListener
I/ActivityManager( 1029): Killing 5867:com.uei.lg.quicksetsdk.maxq616/1000 (adj 15): empty #17
D/BluetoothOppPreference( 6189): Dumping Names:  
D/BluetoothOppPreference( 6189): {}
D/BluetoothOppPreference( 6189): Dumping Channels:  
,D/BluetoothOppPreference( 6189): {}
V/BtOppService( 6189): onStartCommand
,V/BtOppService( 6189): pendingUpdate is true keepUpdateThread is false sListenStarted is true
V/BluetoothOppProvider( 6189): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
V/BluetoothOppProvider( 6189): created cursor android.database.sqlite.SQLiteCursor@156a1e25 on behalf of 
V/BluetoothOppNotification( 6189): update too frequent, put in queue
V/BtOppService( 6189): pendingUpdate is true keepUpdateThread is false sListenStarted is true
V/BluetoothOppProvider( 6189): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
V/BluetoothOppProvider( 6189): created cursor android.database.sqlite.SQLiteCursor@28fc4bfa on behalf of 
V/BluetoothOppNotification( 6189): update too frequent, put in queue
V/BtOppService( 6189): pendingUpdate is false keepUpdateThread is false sListenStarted is true
W/ActivityThread( 6375): ClassLoader.getResources: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/libprocessgroup( 1029): failed to open /acct/uid_1000/pid_5867/cgroup.procs: No such file or directory
,V/BluetoothFtpReceiver( 6189): BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothFtpReceiver( 6189): BluetoothFtpReceiver Start Service
V/BluetoothOppNotification( 6189): new notify threadi!
,V/BluetoothOppNotification( 6189): send delay message
V/BtOppService( 6189): ContentObserver received notification
V/BtOppService( 6189): ContentObserver received notification
V/BluetoothOppProvider( 6189): starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
V/BtOppService( 6189): start RfcommListener
V/BtOppService( 6189): pendingUpdate is true keepUpdateThread is false sListenStarted is true
V/BluetoothOppProvider( 6189): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
V/BluetoothOppProvider( 6189): created cursor android.database.sqlite.SQLiteCursor@feeb5ab on behalf of 
V/BluetoothOppNotification( 6189): mUpdateCompleteNotification = true
V/BtOppService( 6189): RfcommListener started
,V/BtOppRfcommListener( 6189): Starting RFCOMM listener....
V/BluetoothOppProvider( 6189): created cursor android.database.sqlite.SQLiteCursor@313fa408 on behalf of 
D/BluetoothManagerService( 1029): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
W/BluetoothAdapter( 6189): getBluetoothService() called with no BluetoothManagerCallback
D/LGBluetoothServiceAdapter( 6189): [BTUI] createSocketChannel FD=79 mFd=75
V/BluetoothOppProvider( 6189): starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
V/BtOppRfcommListener( 6189): Started RFCOMM listener....
I/BtOppRfcommListener( 6189): Accept thread started.
V/BtOppRfcommListener( 6189): Accepting connection...
V/BluetoothOppProvider( 6189): created cursor android.database.sqlite.SQLiteCursor@24377a1 on behalf of 
V/BtOppService( 6189): pendingUpdate is false keepUpdateThread is false sListenStarted is true
V/BluetoothOppNotification( 6189): outbound: succ-0  fail-0
V/BluetoothOppNotification( 6189): outbound notification was removed.
V/BluetoothOppProvider( 6189): starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
V/BluetoothOppProvider( 6189): created cursor android.database.sqlite.SQLiteCursor@2cb32dc6 on behalf of 
V/BluetoothOppNotification( 6189): inbound: succ-0  fail-0
,V/BluetoothOppNotification( 6189): inbound notification was removed.
V/BluetoothOppProvider( 6189): starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
V/BluetoothOppProvider( 6189): created cursor android.database.sqlite.SQLiteCursor@d610187 on behalf of 
D/BluetoothAdapterService( 6189): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3c79d192
V/BluetoothFtpService( 6189): Ftp Service onCreate
I/BluetoothFtpService( 6189): Ftp Service onCreate
V/BluetoothFtpService( 6189): Ftp Service onStartCommand
V/BluetoothFtpService( 6189): action: android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothFtpService( 6189): Starting Listening on sockets
V/BluetoothSapReceiver( 6189): [BTUI] checkServiceStart
V/BluetoothSapReceiver( 6189): [BTUI] region:EU country:EU
V/BluetoothSapReceiver( 6189): SapReceiver onReceive 
V/BluetoothSapReceiver( 6189): action = android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothSapReceiver( 6189):  Bluetooth Adapter state = 12
V/BluetoothSapReceiver( 6189): Calling SAP service start service with action = null
W/ResourcesManager( 6429): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
V/BluetoothFtpService( 6189): Handler(): got msg=1
V/BluetoothFtpService( 6189): Ftp Service startRfcommSocketListener
V/BluetoothFtpService( 6189): Ftp Service initSocket
,D/BluetoothManagerService( 1029): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
W/BluetoothAdapter( 6189): getBluetoothService() called with no BluetoothManagerCallback
D/LGBluetoothServiceAdapter( 6189): [BTUI] createSocketChannel FD=80 mFd=79
V/BluetoothFtpService( 6189): Succeed to create listening socket on channel 20
V/BluetoothFtpService:RfcommSocketAcceptThread( 6189): Run Accept thread
D/AuthorizationBluetoothService( 2108): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,D/BluetoothAdapterService( 6189): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3c79d192
V/BluetoothSapService( 6189): Sap Service onCreate
V/BluetoothSapService( 6189): action: android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothSapService( 6189): state: 12
V/BluetoothSapService( 6189): Starting SAP server process
V/BluetoothSapService( 6189): SAP Service startRfcommListenerThread
V/BluetoothSapService( 6189): Sap Service initRfcommSocket
D/BluetoothManagerService( 1029): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,W/BluetoothAdapter( 6189): getBluetoothService() called with no BluetoothManagerCallback
W/sapd    ( 6455): type=1400 audit(0.0:159): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6843 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
W/sapd    ( 6455): type=1400 audit(0.0:160): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6843 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
D/LGBluetoothServiceAdapter( 6189): [BTUI] createSocketChannel FD=82 mFd=80
V/BluetoothSapService( 6189): Succeed to create listening socket 
V/BluetoothSapService( 6189): Accepting socket connection...
D/QRemote ( 6429): [QRemoteApplication.java:230:onCreate()] oooooo QRemoteApp onCreate....
V/BT_SAP  ( 6455): Event pipe created
,V/BT_SAP  ( 6455): create_server_socket qcom.sap.server
V/BT_SAP  ( 6455): created socket fd 6
,D/QRemote ( 6429): [CarrierUtils.java:858:getHardwareSettings()] oooooo qremote android.os.Build.MODEL = LG-D855
,I/QRemote ( 6429): [CarrierUtils.java:859:getHardwareSettings()] oooooo getCountry :: EU
,I/QRemote ( 6429): [CarrierUtils.java:860:getHardwareSettings()] oooooo getCarrier :: OPEN
,I/QRemote ( 6429): [CarrierUtils.java:861:getHardwareSettings()] oooooo getArea :: COM
D/QRemote ( 6429): [CarrierUtils.java:862:getHardwareSettings()] oooooo Loading Config...
D/QRemote ( 6429): [CarrierUtils.java:876:getHardwareSettings()] oooooo qremote configuration file = R.xml.qremote_conf
D/QRemote ( 6429): [QRemoteApplication.java:701:updateWidget()] oooooo Widget count is [1]. send broadcast
D/QRemote ( 6429): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6429): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 6429): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,V/[BNRBootReceiver]( 5962): boot receiver action = android.net.wifi.p2p.CONNECTION_STATE_CHANGE
D/BNRAndroBeam( 5962): [BnR DirectBeam] Android Direct Beam(NFC) Connection changed
D/QRemote ( 6429): [QRemoteService.java:196:onCreate()] oooooo 140526:onCreate
D/QRemote ( 6429): [QRemoteService.java:217:onStartCommand()] oooooo 140526:onStartCommand:action:action.application.oncreate. startId:1, flags:0
V/[BNRBootReceiver]( 5962): Boot Receiver Return
,D/PostponalbeReceiver( 6375): WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
W/ContextImpl( 6375): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
V/WiFiOffLoadBroadcast( 6227): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6227): MCCMNC not supported: null
D/QRemote ( 6429): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6429): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 6429): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
D/PostponalbeReceiver( 6375): WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'null'.
,V/QRemote ( 6429): [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
,D/QRemote ( 6429): [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
D/QRemote ( 6429): [QRemoteApplication.java:86:getControlManager()] oooooo mControlManager is null. make new RemoteControlManager
D/LgDataFeature( 6429): LgDataFeature() Constructor: none
D/LgDataFeature( 6429): LgDataFeature() Constructor Done, null
,V/SoundPool( 6429): SoundPool constructor: maxChannels=2, attr.usage=13, attr.flags=0x0, attr.tags=
V/SoundPool( 6429): load: fd=30, offset=10857164, length=17813, priority=1
V/SoundPool( 6429): create sampleID=1, fd=31, offset=17813 length=10857164
V/SoundPool( 6429): doLoad: loading sample sampleID=1
I/QRemote ( 6429): [RemoteControlManager.java:157:onBindIRService()] oooooo bind
V/SoundPool( 6429): Start decode
V/MediaPlayer[Native]( 6429): decode(31, 10857164, 17813)
,V/MediaPlayerService(  314): decode(24, 10857164, 17813)
W/BrunchPlayerTypeImpl(  314): [SelectPlayer] LocalType
W/BrunchPlayerTypeImpl(  314): [getMediaType] EXTEND_MEDIA_MIMETYPE = application/ogg
W/BrunchPlayerTypeImpl(  314): [FindUsePlayer] type = [application/ogg]
W/BrunchPlayerTypeImpl(  314): [FindUsePlayer] componentName = [9101]
W/MediaPlayerFactory(  314): [getPlayerType:fd] nType = 3
V/MediaPlayerService(  314): player type = 3
V/AwesomePlayer(  314): AwesomePlayer create()
V/AwesomePlayer(  314): reset_l() 
V/AwesomePlayer(  314): cancelPlayerEvents
V/AwesomePlayer(  314): setAudioSink() 
V/AwesomePlayer(  314): reset_l() 
V/AudioCache(  314): notify(0xb1163840, 8, 0, 0)
V/AudioCache(  314): ignored
V/AwesomePlayer(  314): cancelPlayerEvents
D/Utils   (  314): printFileName fd(25) -> /data/preload/LGQRemote/LGQRemote.apk
V/AwesomePlayer(  314): setDataSource_l dataSource
V/LGParserOSAL(  314): SniffLGParser start
V/LGParserOSAL(  314): MainType:5, SubType=0
V/LGParserOSAL(  314): #### check Mime : application/ogg
V/LGParserOSAL(  314): Detector mimeType:application/ogg, Confidence=1.000000
E/MediaExtractor(  314): Use LGExtractor :application/ogg 
D/LgDataFeature( 6375): LgDataFeature() Constructor: none
D/LgDataFeature( 6375): LgDataFeature() Constructor Done, null
,I/ActivityManager( 1029): Start proc com.uei.lg.quicksetsdk.maxq616 for service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service: pid=6470 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,D/QRemote ( 6429): [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
V/LGParserOSAL(  314): supported mime: application/ogg
V/AwesomePlayer(  314): setDataSource_l() extractor countTracks=1
V/AwesomePlayer(  314): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer(  314): mBitrate = -1 bits/sec
V/AwesomePlayer(  314): AudioTrack Setting
V/AwesomePlayer(  314): AudioTrack Setting channelCount = 2
V/AwesomePlayer(  314): setAudioSource() 
V/MediaPlayerService(  314): prepare
V/AwesomePlayer(  314): prepareAsync_l() 
V/MediaPlayerService(  314): wait for prepare
E/QRemote ( 6429): [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
D/QRemote ( 6429): [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
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
V/OMXCodec(  314): [OMX.google.vorbis.decoder] allocated buffer 0xb14345b0 on input port
V/OMXCodec(  314): [OMX.google.vorbis.decoder] allocated buffer 0xb1434600 on input port
V/OMXCodec(  314): [OMX.google.vorbis.decoder] allocated buffer 0xb1434650 on input port
V/OMXCodec(  314): [OMX.google.vorbis.decoder] allocated buffer 0xb14346a0 on input port
V/OMXCodec(  314): allocateBuffersOnPort portIndex=1
V/OMXCodec(  314): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
V/OMXCodec(  314): [OMX.google.vorb,is.decoder] allocated buffer 0xb1434880 on output port
V/OMXCodec(  314): [OMX.google.vorbis.decoder] allocated buffer 0xb1434970 on output port
V/OMXCodec(  314): [OMX.google.vorbis.decoder] allocated buffer 0xb1434dd0 on output port
V/OMXCodec(  314): [OMX.google.vorbis.decoder] allocated buffer 0xb152e060 on output port
V/OMXCodec(  314): init() mAsyncCompletion wait!!! 
V/OMXCodec(  314): [OMX.google.vorbis.decoder] onStateChange 2
V/OMXCodec(  314): [OMX.google.vorbis.decoder] Now Idle.
V/OMXCodec(  314): [OMX.google.vorbis.decoder] setState mState=2 , newState=3
V/OMXCodec(  314): init() mAsyncCompletion wait!!! 
V/OMXCodec(  314): [OMX.google.vorbis.decoder] onStateChange 3
V/OMXCodec(  314): [OMX.google.vorbis.decoder] Now Executing.
V/OMXCodec(  314): [OMX.google.vorbis.decoder] setState mState=3 , newState=4
V/OMXCodec(  314): init() mAsyncCompletion wait free! 
V/AwesomePlayer(  314): finishAsyncPrepare_l() 
V/AudioCache(  314): notify(0xb1163840, 5, 0, 0)
V/AudioCache(  314): ignored
V/AudioCache(  314): notify(0xb1163840, 1, 0, 0)
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
V/OMXCodec(  314): [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2973976704
V/OMXCodec(  314): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
V/OMXCodec(  314): [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2973976944
V/OMXCodec(  314): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
V/OMXCodec(  314): [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2973978064
V/OMXCodec(  314): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
V/OMXCodec(  314): [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2974998624
V/OMXCodec(  314): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
V/OMXCodec(  314): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
V/OMXCodec(  314): [OMX.google.vorbis.decoder] initOutputFormat()
V/OMXCodec(  314): [OMX.google.vorbis.decoder] reconfig handling, formatHasNotablyChanged
V/OMXCodec(  314): [OMX.google.vorbis.decoder] enablePortAsync portIndex=1
V/OMXCodec(  314): [OMX.google.vorbis.decoder] sending OMX_CommandPortEnable(1)
V/OMXCodec(  314): allocateBuffersOnPort portIndex=1
V/OMXCodec(  314): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
V/OMXCodec(  314): [OMX.google.vorbis.decoder] allocated buffer 0xb1434dd0 on output port
V/OMXCodec(  314): [OMX.google.vorbis.decoder] allocated buffer 0xb1434970 on output port
V/OMXCodec(  314): [OMX.google.vorbis.decoder] allocated buffer 0xb1434880 on output port
V/OMXCodec(  314): [OMX.google.vorbis.decoder] allocated buffer 0xb152e1a0 on output port
V/OMXCodec(  314): [OMX.google.vorbis.decoder] PORT_ENABLED(1)
V/OMXCodec(  314): [OMX.google.vorbis.decoder] setState mState=7 , newState=4
,V/AudioCache(  314): open(48000, 2, 0x0, 1, 4)
V/AudioCache(  314): notify(0xb1163840, 6, 0, 0)
V/AudioCache(  314): ignored
V/AudioCache(  314): write(0xb57fb000, 4096)
V/AudioCache(  314): memcpy(0xac602000, 0xb57fb000, 4096)
V/AudioCache(  314): write(0xb57fb000, 4096)
V/AudioCache(  314): memcpy(0xac603000, 0xb57fb000, 4096)
V/AudioCache(  314): write(0xb57fb000, 4096)
V/AudioCache(  314): memcpy(0xac604000, 0xb57fb000, 4096)
V/MediaPlayerService(  314): wait for playback complete
V/AudioCache(  314): write(0xb57fb000, 4096)
V/AudioCache(  314): memcpy(0xac605000, 0xb57fb000, 4096)
V/AudioCache(  314): write(0xb57fb000, 4096)
V/AudioCache(  314): memcpy(0xac606000, 0xb57fb000, 4096)
V/AudioCache(  314): write(0xb57fb000, 4096)
V/AudioCache(  314): memcpy(0xac607000, 0xb57fb000, 4096)
V/AudioCache(  314): write(0xb57fb000, 4096)
V/AudioCache(  314): memcpy(0xac608000, 0xb57fb000, 4096)
V/AudioCache(  314): write(0xb57fb000, 4096)
V/AudioCache(  314): memcpy(0xac609000, 0xb57fb000, 4096)
V/AudioCache(  314): write(0xb57fb000, 4096)
V/AudioCache(  314): memcpy(0xac60a000, 0xb57fb000, 4096)
V/AudioCache(  314): write(0xb57fb000, 4096)
V/AudioCache(  314): memcpy(0xac60b000, 0xb57fb000, 4096)
V/AudioCache(  314): write(0xb57fb000, 4096)
V/AudioCache(  314): memcpy(0xac60c000, 0xb57fb000, 4096)
V/AudioCache(  314): write(0xb57fb000, 4096)
V/AudioCache(  314): memcpy(0xac60d000, 0xb57fb000, 4096)
V/AudioCache(  314): write(0xb57fb000, 4096)
V/AudioCache(  314): memcpy(0xac60e000, 0xb57fb000, 4096)
V/AudioCache(  314): write(0xb57fb000, 4096)
V/AudioCache(  314): memcpy(0xac60f000, 0xb57fb000, 4096)
V/AudioCache(  314): write(0xb57fb000, 4096)
V/AudioCache(  314): memcpy(0xac610000, 0xb57fb000, 4096)
V/AudioCache(  314): write(0xb57fb000, 4096)
V/AudioCache(  314): memcpy(0xac611000, 0xb57fb000, 4096)
V/AudioCache(  314): write(0xb57fb000, 4096)
V/AudioCache(  314): memcpy(0xac612000, 0xb57fb000, 4096)
V/AudioCache(  314): write(0xb57fb000, 4096)
V/AudioCache(  314): memcpy(0xac613000, 0xb57fb000, 4096)
V/AudioCache(  314): write(0xb57fb000, 4096)
V/AudioCache(  314): memcpy(0xac614000, 0xb57fb000, 4096)
V/AudioCache(  314): write(0xb57fb000, 4096)
V/AudioCache(  314): memcpy(0xac615000, 0xb57fb000, 4096)
V/AudioCache(  314): write(0xb57fb000, 4096)
V/AudioCache(  314): memcpy(0xac616000, 0xb57fb000, 4096)
V/AudioCache(  314): write(0xb57fb000, 4096)
V/AudioCache(  314): memcpy(0xac617000, 0xb57fb000, 4096)
V/AudioCache(  314): write(0xb57fb000, 4096)
V/AudioCache(  314): memcpy(0xac618000, 0xb57fb000, 4096)
V/AudioCache(  314): write(0xb57fb000, 4096)
V/AudioCache(  314): memcpy(0xac619000, 0xb57fb000, 4096)
V/AudioCache(  314): write(0xb57fb000, 4096)
V/AudioCache(  314): memcpy(0xac61a000, 0xb57fb000, 4096)
V/AudioCache(  314): write(0xb57fb000, 4096)
V/AudioCache(  314): memcpy(0xac61b000, 0xb57fb000, 4096)
V/AudioCache(  314): write(0xb57fb000, 4096)
V/AudioCache(  314): memcpy(0xac61c000, 0xb57fb000, 4096)
V/LGMDMManager( 6429): Create singleton instance
V/AudioCache(  314): write(0xb57fb000, 4096)
V/AudioCache(  314): memcpy(0xac61d000, 0xb57fb000, 4096)
V/AudioCache(  314): write(0xb57fb000, 4096)
V/AudioCache(  314): memcpy(0xac61e000, 0xb57fb000, 4096)
V/AudioCache(  314): write(0xb57fb000, 4096)
V/AudioCache(  314): memcpy(0xac61f000, 0xb57fb000, 4096)
V/AudioCache(  314): write(0xb57fb000, 4096)
V/AudioCache(  314): memcpy(0xac620000, 0xb57fb000, 4096)
V/AudioCache(  314): write(0xb57fb000, 4096)
V/AudioCache(  314): memcpy(0xac621000, 0xb57fb000, 4096)
V/AudioCache(  314): write(0xb57fb000, 4096)
V/AudioCache(  314): memcpy(0xac622000, 0xb57fb000, 4096)
V/AudioCache(  314): write(0xb57fb000, 4096)
V/AudioCache(  314): memcpy(0xac623000, 0xb57fb000, 4096)
V/AudioCache(  314): write(0xb57fb000, 4096)
V/AudioCache(  314): memcpy(0xac624000, 0xb57fb000, 4096)
V/AudioCache(  314): write(0xb57fb000, 4096)
V/AudioCache(  314): memcpy(0xac625000, 0xb57fb000, 4096)
V/AudioCache(  314): write(0xb57fb000, 4096)
V/AudioCache(  314): memcpy(0xac626,000, 0xb57fb000, 4096)
V/AudioCache(  314): write(0xb57fb000, 4096)
V/AudioCache(  314): memcpy(0xac627000, 0xb57fb000, 4096)
V/AudioCache(  314): write(0xb57fb000, 4096)
V/AudioCache(  314): memcpy(0xac628000, 0xb57fb000, 4096)
,V/AudioCache(  314): write(0xb57fb000, 4096)
V/AudioCache(  314): memcpy(0xac629000, 0xb57fb000, 4096)
V/AudioCache(  314): write(0xb57fb000, 4096)
V/AudioCache(  314): memcpy(0xac62a000, 0xb57fb000, 4096)
V/AudioCache(  314): write(0xb57fb000, 4096)
V/AudioCache(  314): memcpy(0xac62b000, 0xb57fb000, 4096)
V/AudioCache(  314): write(0xb57fb000, 4096)
V/AudioCache(  314): memcpy(0xac62c000, 0xb57fb000, 4096)
V/AudioCache(  314): write(0xb57fb000, 4096)
V/AudioCache(  314): memcpy(0xac62d000, 0xb57fb000, 4096)
V/AudioCache(  314): write(0xb57fb000, 4096)
V/AudioCache(  314): memcpy(0xac62e000, 0xb57fb000, 4096)
V/AudioCache(  314): write(0xb57fb000, 4096)
V/AudioCache(  314): memcpy(0xac62f000, 0xb57fb000, 4096)
V/AudioCache(  314): write(0xb57fb000, 4096)
V/AudioCache(  314): memcpy(0xac630000, 0xb57fb000, 4096)
V/AudioCache(  314): write(0xb57fb000, 4096)
V/AudioCache(  314): memcpy(0xac631000, 0xb57fb000, 4096)
V/AudioCache(  314): write(0xb57fb000, 4096)
V/AudioCache(  314): memcpy(0xac632000, 0xb57fb000, 4096)
V/AudioCache(  314): write(0xb57fb000, 4096)
V/AudioCache(  314): memcpy(0xac633000, 0xb57fb000, 4096)
V/OMXCodec(  314): [OMX.google.vorbis.decoder] No more output data.
V/OMXCodec(  314): [OMX.google.vorbis.decoder] There is no more output data available, not calling fillOutputBuffer
V/AwesomePlayer(  314): postAudioEOS() 
V/AudioCache(  314): write(0xb57fb000, 280)
V/AudioCache(  314): memcpy(0xac634000, 0xb57fb000, 280)
V/AwesomePlayer(  314): postStreamDoneEvent_l() -> status:-1011 
V/AwesomePlayer(  314): onStreamDone
V/AwesomePlayer(  314): MEDIA_PLAYBACK_COMPLETE
V/AudioCache(  314): notify(0xb1163840, 2, 0, 0)
V/AudioCache(  314): playback complete
V/AwesomePlayer(  314): pause_l() 
V/AudioCache(  314): notify(0xb1163840, 7, 0, 0)
V/AudioCache(  314): ignored
V/AwesomePlayer(  314): cancelPlayerEvents
V/AudioCache(  314): wait - success
V/MediaPlayerService(  314): return size 205080, sampleRate=48000, channelCount = 2, format = 1
D/AudioPlayer(  314): Pause Playback at 1068125
V/AwesomePlayer(  314): reset_l() 
V/AudioCache(  314): notify(0xb1163840, 8, 0, 0)
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
V/OMXCodec(  314): [OMX.google.vorbis.decoder] freeing buffer 0xb14346a0 on port 0
V/OMXCodec(  314): [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=3
V/OMXCodec(  314): [OMX.google.vorbis.decoder] freeing buffer 0xb1434650 on port 0
V/OMXCodec(  314): [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=2
V/OMXCodec(  314): [OMX.google.vorbis.decoder] freeing buffer 0xb1434600 on port 0
V/OMXCodec(  314): [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=1
V/OMXCodec(  314): [OMX.google.vorbis.decoder] freeing buffer 0xb14345b0 on port 0
V/OMXCodec(  314): [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=0
V/OMXCodec(  314): [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
V/OMXCodec(  314): [OMX.google.vorbis.decoder] freeing buffer 0xb152e1a0 on port 1
V/OMXCodec(  314): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=3
V/OMXCodec(  314): [OMX.google.vorbis.decoder] freeing buffer 0xb1434880 on port 1
V/OMXCodec(  314): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=2
V/OMXCodec(  314): [OMX.google.vorbis.decoder] freeing buffer 0xb1434970 on port 1
V/OMXCodec(  314): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=1
V/OMXCodec(  314): [OMX.google.vorbis.decoder] freeing buffer 0,xb1434dd0 on port 1
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
V/SoundPool( 6429): close(31)
V/SoundPool( 6429): pointer = 0x9ff36000, size = 205080, sampleRate = 48000, numChannels = 2
,D/UEI.SmartControl( 6470): Quickset Services start...
I/UEI.SmartControl( 6470): Manufacture = LGE
D/UEI.SmartControl( 6470): Id = LGNevo
,D/UEI.SmartControl( 6470): File observer start...
D/QRemote ( 6429): [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
D/QRemote ( 6429): [RemoteAppWidgetProvider.java:486:onUpdate()] oooooo 140510:RetrieveDevices is not complete. Just waiting
E/UEI.SmartControl( 6470): IR Port is disabled: false
D/UEI.SmartControl( 6470): Starting file observer...
D/UEI.SmartControl( 6470): Extracting JNI libs...
D/UEI.SmartControl( 6470): --- this system supports 32-bit or 64-bit only
D/QRemote ( 6429): [RemoteAppWidgetProvider.java:499:onUpdate()] oooooo 140514:alarm set after 5000ms:1223
D/PostponalbeReceiver( 6375): WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'null'.
W/ContextImpl( 6375): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.vsmandroid.gh.h:-1 com.mcafee.vsm.ext.common.a.d.a:-1 com.mcafee.vsm.ext.common.api.ExtUtils.stopApp:-1 
D/SiteAdvisor( 6375): com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.google.android.browser/com.android.browser.BrowserActivity not supported
,D/SiteAdvisor( 6375): com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.amazon.cloud9/com.amazon.cloud9.BrowserActivity not supported
D/SiteAdvisor( 6375): com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.sec.android.app.sbrowser/com.sec.android.app.sbrowser.SBrowserMainActivity not supported
D/SiteAdvisor( 6375): com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.sec.android.app.sbrowser/com.sec.android.app.sbrowser.SBrowserMainActivity not supported
D/SiteAdvisor( 6375): com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.htc.sense.browser/com.htc.sense.browser.BrowserActivity not supported
I/SiteAdvisor( 6375): com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Loading supported browsers: com.android.browser/com.android.browser.BrowserActivity; com.android.chrome/com.android.chrome.Main; 
D/SiteAdvisor( 6375): com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Here is the storedCurrentAppVersion: 3.1.2.1430
D/SiteAdvisor( 6375): com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Here about to commit perfs
,D/UEI.SmartControl( 6470): --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
,D/UEI.SmartControl( 6470): --- Checking lib: libqs_armeabi-v7a.zip
D/UEI.SmartControl( 6470): --- Extracting JNI libs: libqs_armeabi-v7a.zip
,I/UEI.SmartControl( 6470): --- Selecting new region: 6
I/UEI.SmartControl( 6470): Model = LG-D855
D/UEI.SmartControl( 6470): QS Service created
I/UEI.SmartControl( 6470): Service initServices...
,D/UEI.SmartControl( 6470): QS start get config
,D/UEI.SmartControl( 6470): Loading JNI Libs...
,I/UEI.SmartControl( 6470): Supports setup maps: true
,D/UEI.SmartControl( 6470): QS start statue = true Error code = 0
I/UEI.SmartControl( 6470): QS version = v2.7.10.1_RC1
I/UEI.SmartControl( 6470): QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
I/UEI.SmartControl( 6470): ### init IR Blaster...
D/serial_port( 6470): Configuring serial port
,E/UEI.SmartControl( 6470): UEIBLaster setting for 616
I/UEI.SmartControl( 6470): Setting serial record hearder size = 2
I/UEI.SmartControl( 6470): configuring settings for MAXQ616
I/UEI.SmartControl( 6470): Get version...
D/UEI.SmartControl( 6470): serial port data available: 21
,D/UEI.SmartControl( 6470): MAXQ616 A2-X4 software.
I/UEI.SmartControl( 6470): IR Blaster version: 256702256704300002
I/UEI.SmartControl( 6470): QS saving settings...
D/UEI.SmartControl( 6470): IR Blaster version: 25672567
,D/UEI.SmartControl( 6470): serial port data available: 4
,I/jxcore-log( 6107): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6107): 
,I/UEI.SmartControl( 6470): Device manager: loading config....
,D/UEI.SmartControl( 6470): ----------- loading internal config...
,W/ContextImpl( 6470): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
E/UEI.SmartControl( 6470): Services init done
D/UEI.SmartControl( 6470): QS Service init finished
D/UEI.SmartControl( 6470): QS Service version name: 2.1.91
D/UEI.SmartControl( 6470): QS Service version code: 201091
D/UEI.SmartControl( 6470): Service requested: Control
E/UEI.SmartControl( 6470): Loading SETTINGS...
D/UEI.SmartControl( 6470): Request IControl service: devices are loaded...
,I/QRemote ( 6429): [RemoteControlManager.java:183:onServiceConnected()] oooooo start
,D/UEI.SmartControl( 6470): Internal service binding...
I/UEI.SmartControl( 6470): ------ IControl API: 11
I/UEI.SmartControl( 6470): Registering callback...
I/UEI.SmartControl( 6470): ------ IControl API: 19
I/UEI.SmartControl( 6470): Registering Services Ready callback...
D/UEI.SmartControl( 6470): -- Open brand translation xml: brands_translations_ko
I/UEI.SmartControl( 6470): Notify AllClients services are ready: 0
D/UEI.SmartControl( 6470): -----service ready thread exits
I/QRemote ( 6429): [RemoteControlManager.java:660:QSSetupIsReady()] oooooo 140517:sdkIsReady callback... get functions. Result:0
D/QRemote ( 6429): [RemoteControlManager.java:388:handleMessage()] oooooo 140510:START_SESSION
D/QRemote ( 6429): [RemoteControlManager.java:394:handleMessage()] oooooo 140510:send retrieve msg
,D/QRemote ( 6429): [RemoteControlManager.java:322:handleMessage()] oooooo 140510:handler call retrieveDevices
D/QRemote ( 6429): [RemoteControlManager.java:336:retrieveDevices()] oooooo retrieveDevices: start
I/UEI.SmartControl( 6470): ------ IControl API: 8
D/QRemote ( 6429): [RemoteControlManager.java:340:retrieveDevices()] oooooo retrieveDevices: 0
D/QRemote ( 6429): [RemoteControlManager.java:345:retrieveDevices()] oooooo retrieveDevices complete:true
D/QRemote ( 6429): [RemoteControlManager.java:353:retrieveDevices()] oooooo retrieveDevices: notifyDataSetChanged()
D/QRemote ( 6429): [QRemoteApplication.java:145:onRemoteControlStateChanged()] oooooo onRemoteControlStateChanged called in QRemoteApp
D/QRemote ( 6429): [QRemoteApplication.java:158:onRemoteControlStateChanged()] oooooo Widget count is [1]. send broadcast
D/QRemote ( 6429): [QRemoteApplication.java:160:onRemoteControlStateChanged()] oooooo Widget[0]:3
D/QRemote ( 6429): [QRemoteApplication.java:188:onRemoteControlStateChanged()] oooooo 140526:onRemoteControlStateChanged&sdkIsReady. stop Service
,V/QRemote ( 6429): [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
D/QRemote ( 6429): [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
E/QRemote ( 6429): [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
D/QRemote ( 6429): [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
D/QRemote ( 6429): [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
D/QRemote ( 6429): [RemoteAppWidgetProvider.java:506:onUpdate()] oooooo 140510:RetrieveDevices complete. Start loading
D/QRemote ( 6429): [RemoteAppWidgetProvider.java:508:onUpdate()] oooooo 140510:appWidgetIds[0]:3 loading
D/QRemote ( 6429): [RemoteAppWidgetManager.java:41:startLoading()] oooooo 140518:widgetId[3] loading start at [1449156172306]
D/QRemote ( 6429): [QRemoteService.java:207:onDestroy()] oooooo 140526:onDestroy
,I/ActivityManager( 1029): Killing 5557:com.lge.lockscreensettings/u0a80 (adj 15): empty #17
D/QRemote ( 6429): [RemoteAppWidgetManager.java:239:doInBackground()] oooooo 140407:doinBack arr:0
,I/ActivityManager( 1029): Killing 5715:com.android.defcontainer/u0a4 (adj 15): empty #18
,W/libprocessgroup( 1029): failed to open /acct/uid_10080/pid_5557/cgroup.procs: No such file or directory
,W/libprocessgroup( 1029): failed to open /acct/uid_10004/pid_5715/cgroup.procs: No such file or directory
V/BluetoothOppNotification( 6189): new notify threadi!
V/QRemote ( 6429): [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.widget_ui_update
V/BluetoothOppNotification( 6189): send delay message
E/QRemote ( 6429): [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
D/QRemote ( 6429): [RemoteAppWidgetProvider.java:171:onReceive()] oooooo total:0
D/QRemote ( 6429): [RemoteAppWidgetProvider.java:172:onReceive()] oooooo selected:0
D/QRemote ( 6429): [RemoteAppWidgetProvider.java:173:onReceive()] oooooo arr:[]
D/QRemote ( 6429): [RemoteAppWidgetProvider.java:174:onReceive()] oooooo appWidgetId:3
D/QRemote ( 6429): [RemoteAppWidgetProvider.java:815:updateRemoteViews()] oooooo UpdateRemoteViews3:widgetId:3
,V/BluetoothOppProvider( 6189): starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
V/BluetoothOppProvider( 6189): created cursor android.database.sqlite.SQLiteCursor@291cec20 on behalf of 
V/BluetoothOppNotification( 6189): mUpdateCompleteNotification = true
V/BluetoothOppProvider( 6189): starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
V/BluetoothOppProvider( 6189): created cursor android.database.sqlite.SQLiteCursor@120279d9 on behalf of 
V/BluetoothOppNotification( 6189): outbound: succ-0  fail-0
D/QRemote ( 6429): [RemoteAppWidgetProvider.java:986:updateRemoteViews()] oooooo updateAppWidget5:widgetId:3]
,V/BluetoothOppNotification( 6189): outbound notification was removed.,
V/BluetoothOppProvider( 6189): starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
V/BluetoothOppProvider( 6189): created cursor android.database.sqlite.SQLiteCursor@3042f9e on behalf of 
V/BluetoothOppNotification( 6189): inbound: succ-0  fail-0
V/BluetoothOppNotification( 6189): inbound notification was removed.
V/BluetoothOppProvider( 6189): starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
V/BluetoothOppProvider( 6189): created cursor android.database.sqlite.SQLiteCursor@17e9a7f on behalf of 
D/WfdsMonitor( 1945): Event [CTRL-EVENT-SCAN-RESULTS ]
D/WfdsMonitor( 1945): Event [WPS-AP-AVAILABLE ]
,E/WifiMonitor( 1029): WifiMonitor:wlan0 cnt=9 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
E/WifiMonitor( 1029): handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
E/WifiMonitor( 1029): WifiMonitor:p2p0 cnt=10 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
E/WifiMonitor( 1029): handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
E/WifiStateMachine( 1029):  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=0 bcn=0
E/WifiStateMachine( 1029):  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=0 bcn=0
E/WifiStateMachine( 1029):  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=0 bcn=0
E/WifiStateMachine( 1029):  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=0 bcn=0
I/WifiNative-HAL( 1029): startHal
E/wifi    ( 1029): getStaticLongField sWifiHalHandle 0x989338cc
E/WifiHAL ( 1029): Could not connect handle
D/wifi    ( 1029): halHandle = 0x0, mVM = 0xb487c280, mCls = 0x601f9a
I/WifiNative-HAL( 1029): Could not start hal
,D/WifiMonitor( 1029): Event [IFNAME=p2p0 WPS-AP-AVAILABLE ]
E/WifiMonitor( 1029): WifiMonitor:p2p0 cnt=11 dispatchEvent: WPS-AP-AVAILABLE 
D/LGWifiP2pService( 1029): InactiveState{ when=-14ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1029): P2pEnabledState{ when=-14ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1029): DefaultState{ when=-14ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/WifiMonitor( 1029): couldn't identify event type - WPS-AP-AVAILABLE 
D/WifiNative-wlan0( 1029): doString: [BSS RANGE=0- MASK=0x21987]
V/WiFiOffLoadBroadcast( 6227): WiFiOffLoadBroadcast: android.net.wifi.SCAN_RESULTS
,D/WiFiOffLoadBroadcast( 6227): Not supported operator for automatic switch
,I/jxcore-log( 6107): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6107): 
,I/jxcore-log( 6107): BLE advertisement not supported: MultipleAdvertisement not supported
I/jxcore-log( 6107): 
,D/UEI.SmartControl( 6470): Internal timer expired: 1
D/UEI.SmartControl( 6470): unbind internal service
,I/jxcore-log( 6107): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6107): 
D/serial_port( 6470): close(fd = 25)
I/UEI.SmartControl( 6470): Serial port is closed.
,V/AlarmManager( 1029): RTC_WAKEUP set : Alarm{11832afc type 0 when 1449156170356 android} when 1449156170356
,E/WifiStateMachine( 1029):  DisconnectedState CMD_START_SCAN -2 -2 ic=1 proc(ms):4 rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 fiv=120000 [on:0 tx:0 rx:0 period:1752199970] from screen [on:0 period:1752199970]
E/WifiStateMachine( 1029):  ConnectModeState CMD_START_SCAN -2 -2 ic=1 proc(ms):28 rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 fiv=120000 [on:0 tx:0 rx:0 period:6] from screen [on:0 period:1752199976]
,V/AlarmManager( 1029): RTC_WAKEUP set : Alarm{15fc4fda type 0 when 1449156176085 com.android.vending} when 1449156176085,
E/WifiStateMachine( 1029):  DriverStartedState CMD_START_SCAN -2 -2 ic=1 proc(ms):35 rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 fiv=120000 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:1752199977]
D/WifiNative-wlan0( 1029): doBoolean: SCAN
I/wpa_supplicant( 6242): wlan0: CTRL-EVENT-SCAN-STARTED 
D/WifiMonitor( 1029): Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1029): WifiMonitor:wlan0 cnt=12 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1029): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1029): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
,D/WifiNative-wlan0( 1029): SCAN: returned true
I/WifiNative-HAL( 1029): startHal
E/wifi    ( 1029): getStaticLongField sWifiHalHandle 0x989337dc
E/WifiHAL ( 1029): Could not connect handle
D/wifi    ( 1029): halHandle = 0x0, mVM = 0xb487c280, mCls = 0x402156
I/WifiNative-HAL( 1029): Could not start hal
V/QRemote ( 6429): [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.wait_loading
D/QRemote ( 6429): [RemoteAppWidgetProvider.java:211:onReceive()] oooooo 140514:alarm msg received!:1223
V/SIM_STK ( 1029): Menu title from STK is T-Mobile
,V/GLSActivity( 2108): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     ( 2108): Explicit concurrent mark sweep GC freed 21762(1222KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 30MB/62MB, paused 2.196ms total 57.655ms
,I/GLSUser ( 2108): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 2108): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2108): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2108): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2108): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/Finsky  ( 4896): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 4896): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 4896): [1] 5.onFinished: Scheduling replication attempt 3.
,I/[SystemUI]TimeTickManager( 1451): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1451): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1451): called onTimeUpdated()
I/[SystemUI]Clock( 1451): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1451): called onTimeUpdated()
I/[SystemUI]DateView( 1451): called onTimeUpdated()
I/[SystemUI]DateView( 1451): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1451): handleTimeUpdate
D/sensors_hal_Time( 1029): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1029): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1029): tsOffsetIs: Apps: 174029003998; DSPS: 5844000; Offset : -4327619020
,D/WfdsMonitor( 1945): Event [CTRL-EVENT-SCAN-RESULTS ]
D/WfdsMonitor( 1945): Event [WPS-AP-AVAILABLE ]
,E/WifiMonitor( 1029): WifiMonitor:wlan0 cnt=13 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
E/WifiMonitor( 1029): handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
E/WifiMonitor( 1029): WifiMonitor:p2p0 cnt=14 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
E/WifiStateMachine( 1029):  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=4 known=0 got=4 bcn=0
E/WifiStateMachine( 1029):  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=4 known=0 got=4 bcn=0
E/WifiStateMachine( 1029):  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=4 known=0 got=4 bcn=0
E/WifiStateMachine( 1029):  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=4 known=0 got=4 bcn=0
D/WifiNative-wlan0( 1029): doString: [BSS RANGE=0- MASK=0x21987]
E/WifiMonitor( 1029): handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
,D/LGWifiP2pService( 1029): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1029): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1029): DefaultState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiMonitor( 1029): Event [IFNAME=p2p0 WPS-AP-AVAILABLE ]
E/WifiMonitor( 1029): WifiMonitor:p2p0 cnt=15 dispatchEvent: WPS-AP-AVAILABLE 
W/WifiMonitor( 1029): couldn't identify event type - WPS-AP-AVAILABLE 
V/WiFiOffLoadBroadcast( 6227): WiFiOffLoadBroadcast: android.net.wifi.SCAN_RESULTS
,D/WiFiOffLoadBroadcast( 6227): Not supported operator for automatic switch
I/jxcore-log( 6107): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6107): 
,I/jxcore-log( 6107): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6107): 
,I/jxcore-log( 6107): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6107): 
,I/jxcore-log( 6107): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6107): 
,D/sensors_hal_Time( 1029): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1029): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1029): tsOffsetIs: Apps: 194031143574; DSPS: 6499430; Offset : -4327615700
,I/jxcore-log( 6107): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6107): 
,D/PowerManagerServiceEx( 1029): acquireWakeLockInternal: lock=231167151, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1029
,V/AlarmManager( 1029): RTC_WAKEUP set : Alarm{351099f5 type 0 when 1449156199146 com.android.vending} when 1449156199146
,D/[Concierge]Service( 2611): onStartCommand(). Type : 9
,D/PowerManagerServiceEx( 1029): releaseWakeLockInternal: lock=231167151 [*alarm*], flags=0x0
,V/SIM_STK ( 1029): Menu title from STK is T-Mobile
,V/GLSActivity( 2108): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2108): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 2108): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2108): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2108): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2108): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/Finsky  ( 4896): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 4896): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 4896): [1] 5.onFinished: Scheduling replication attempt 4.
,I/jxcore-log( 6107): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6107): 
,I/jxcore-log( 6107): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6107): 
,I/jxcore-log( 6107): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6107): 
,D/sensors_hal_Time( 1029): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1029): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1029): tsOffsetIs: Apps: 214033049610; DSPS: 7154852; Offset : -4327601962
,I/jxcore-log( 6107): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6107): 
,V/AlarmManager( 1029): ELAPSED_WAKEUP set : Alarm{31d11cf type 2 when 179966 com.google.android.gms} when 179966
,V/AlarmManager( 1029): RTC_WAKEUP set : Alarm{3a7cea65 type 0 when 1449156224201 com.android.vending} when 1449156224201
,D/libc-netbsd(  309): default dns: query_ipv6=0, query_ipv4=0
,D/DSQN    ( 1029): DNSproblemNotiEnabled is disabled ignore DNS fail CB
,I/art     ( 1029): Explicit concurrent mark sweep GC freed 37801(1830KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 44MB/66MB, paused 2.397ms total 140.256ms
,V/SIM_STK ( 1029): Menu title from STK is T-Mobile
,V/GLSActivity( 2108): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2108): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 2108): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2108): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2108): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2108): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/Finsky  ( 4896): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 4896): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 4896): [1] 5.onFinished: Scheduling replication attempt 5.
,I/jxcore-log( 6107): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6107): 
,I/jxcore-log( 6107): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6107): 
,I/jxcore-log( 6107): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6107): 
,I/[SystemUI]TimeTickManager( 1451): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1451): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1451): called onTimeUpdated()
I/[SystemUI]Clock( 1451): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1451): called onTimeUpdated()
I/[SystemUI]DateView( 1451): called onTimeUpdated()
I/[SystemUI]DateView( 1451): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1451): handleTimeUpdate
D/sensors_hal_Time( 1029): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1029): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1029): tsOffsetIs: Apps: 234035315435; DSPS: 7810286; Offset : -4327594517
,I/jxcore-log( 6107): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6107): 
,I/jxcore-log( 6107): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6107): 
,D/PowerManagerServiceEx( 1029): acquireWakeLockInternal: lock=231167151, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1029
,V/AlarmManager( 1029): RTC_WAKEUP set : Alarm{193eb5db type 0 when 1449156245855 com.android.vending} when 1449156245855
,D/[Concierge]Service( 2611): onStartCommand(). Type : 9
,D/PowerManagerServiceEx( 1029): releaseWakeLockInternal: lock=231167151 [*alarm*], flags=0x0
,V/SIM_STK ( 1029): Menu title from STK is T-Mobile
,V/GLSActivity( 2108): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2108): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 2108): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2108): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2108): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2108): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/Finsky  ( 4896): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 4896): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 4896): [1] 5.onFinished: Giving up after 6 failures.
,I/jxcore-log( 6107): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6107): 
,I/jxcore-log( 6107): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6107): 
,D/sensors_hal_Time( 1029): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1029): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1029): tsOffsetIs: Apps: 254037218448; DSPS: 8465709; Offset : -4327613877
,I/jxcore-log( 6107): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6107): 
,I/jxcore-log( 6107): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6107): 
,I/jxcore-log( 6107): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6107): 
,I/jxcore-log( 6107): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6107): 
,D/sensors_hal_Time( 1029): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1029): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1029): tsOffsetIs: Apps: 274039310263; DSPS: 9121137; Offset : -4327597387
,V/AlarmManager( 1029): ELAPSED_WAKEUP set : Alarm{14937f45 type 2 when 240124 android} when 240124
,V/AlarmManager( 1029): ELAPSED_WAKEUP set : Alarm{27f2669a type 2 when 260244 com.google.android.gms} when 260244
,D/libc-netbsd(  309): default dns: query_ipv6=0, query_ipv4=0
D/DSQN    ( 1029): DNSproblemNotiEnabled is disabled ignore DNS fail CB
,I/jxcore-log( 6107): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6107): 
,I/jxcore-log( 6107): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6107): 
,I/jxcore-log( 6107): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6107): 
,I/jxcore-log( 6107): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6107): 
,I/[SystemUI]TimeTickManager( 1451): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1451): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1451): called onTimeUpdated()
I/[SystemUI]Clock( 1451): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1451): called onTimeUpdated()
I/[SystemUI]DateView( 1451): called onTimeUpdated()
I/[SystemUI]DateView( 1451): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1451): handleTimeUpdate
D/sensors_hal_Time( 1029): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1029): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1029): tsOffsetIs: Apps: 294042337286; DSPS: 9776597; Offset : -4327621992
,I/jxcore-log( 6107): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6107): 
,I/jxcore-log( 6107): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6107): 
,I/jxcore-log( 6107): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6107): 
,I/[SystemUI]LGPowerUI( 1451): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1451): On Skip Timer : true
,D/WifiController( 1029): battery changed pluggedType: 2
,D/LGDMClient( 3924): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1451): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 292
D/LEDHandler( 1945): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1945): Battery Level Remaining: 100%
D/LEDHandler( 1945): Battery Temp: 292, mChargingStatus=5, mChargingStop=false
I/[SystemUI]LGPowerUI( 1451): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]BatterySaverHandler( 1451): onReceive = android.intent.action.BATTERY_CHANGED
D/HeadsetStateMachine( 6189): Disconnected process message: 10, size: 0
,W/Settings( 1029): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1029): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/LGDMClient( 3924): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
I/jxcore-log( 6107): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6107): 
,D/sensors_hal_Time( 1029): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1029): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1029): tsOffsetIs: Apps: 314044402122; DSPS: 10432024; Offset : -4327601963
,I/jxcore-log( 6107): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6107): 
,I/jxcore-log( 6107): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6107): 
,I/jxcore-log( 6107): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6107): 
,I/jxcore-log( 6107): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6107): 
,D/sensors_hal_Time( 1029): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1029): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1029): tsOffsetIs: Apps: 334046322011; DSPS: 11087447; Offset : -4327604448
,I/jxcore-log( 6107): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6107): 
,I/jxcore-log( 6107): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6107): 
,D/PowerManagerServiceEx( 1029): acquireWakeLockInternal: lock=231167151, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1029
,D/[Concierge]Service( 2611): onStartCommand(). Type : 9
,D/PowerManagerServiceEx( 1029): releaseWakeLockInternal: lock=231167151 [*alarm*], flags=0x0
,I/jxcore-log( 6107): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6107): 
,I/jxcore-log( 6107): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6107): 
,V/GLSActivity( 2108): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2108): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 2108): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2108): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2108): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2108): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1029): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,D/ZenLog  ( 1029): intercepted: 0|com.google.android.gms|1|null|10005,none
V/NotificationService( 1029): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1029): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1029): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1029): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
W/GLSActivity( 2108): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2108): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2108): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2108): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2108): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2108): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2108): 	at android.os.Binder.execTransact(Binder.java:446)
,W/ResourcesManager( 1451): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 1451): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,W/ResourcesManager( 1393): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 1393): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
D/LgeQuickCoverNLService( 1393): onNotificationPosted
D/SmartCoverUpdateMonitor( 1393): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1393): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1393): handleNotificationPosted(true)
D/QuickCircle( 1393): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1393): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1393): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1393): post do add job
D/LgeQuickCoverNotificationData( 1393): add : 2
D/LgeQuickCoverNotificationData( 1393): do add job
D/LgeQuickCoverNotificationData( 1393): showAll3
D/LgeQuickCoverNotificationData( 1393): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1393): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
D/LgeQuickCoverNotificationData( 1393): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
E/LgeQuickCoverOverlayWindow( 1393): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1393): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1393): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1393): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1393): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1393): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1393): isNotificationForCurrentUser : true
,E/LgeQuickCoverOverlayWindow( 1393): updateNotificationData: count=3
E/PlayEventLogger( 4896): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 4896): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 4896): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/PlayEventLogger( 4896): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 4896): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/PlayEventLogger( 4896): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 4896): 	at android.os.Binder.execTransact(Binder.java:446)
I/[SystemUI]TimeTickManager( 1451): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1451): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1451): called onTimeUpdated()
I/[SystemUI]Clock( 1451): called onTimeUpdated()
,D/QuickStatusbarLayout( 1393): Notification difference=198
D/QuickStatusbarLayout( 1393): child = android.widget.LinearLayout{156a1e25 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
I/LgeClockWidgetControlView( 1451): called onTimeUpdated()
I/[SystemUI]DateView( 1451): called onTimeUpdated()
I/[SystemUI]DateView( 1451): called onTimeUpdated()
W/System  ( 4896): Ignoring header User-Agent because its value was null.
,D/libc-netbsd(  309): default dns: query_ipv6=0, query_ipv4=0
D/DSQN    ( 1029): DNSproblemNotiEnabled is disabled ignore DNS fail CB
D/KeyguardUpdateMonitor( 1451): handleTimeUpdate
D/sensors_hal_Time( 1029): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1029): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1029): tsOffsetIs: Apps: 354048499659; DSPS: 11742879; Offset : -4327624325
I/jxcore-log( 6107): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6107): 
,I/jxcore-log( 6107): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6107): 
,I/jxcore-log( 6107): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6107): 
,I/jxcore-log( 6107): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6107): 
,D/sensors_hal_Time( 1029): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1029): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1029): tsOffsetIs: Apps: 374052075434; DSPS: 12398356; Offset : -4327618977
,I/jxcore-log( 6107): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6107): 
,I/jxcore-log( 6107): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6107): 
,I/jxcore-log( 6107): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6107): 
,I/jxcore-log( 6107): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6107): 
,D/sensors_hal_Time( 1029): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1029): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1029): tsOffsetIs: Apps: 394054344072; DSPS: 13053790; Offset : -4327608536
,I/jxcore-log( 6107): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6107): 
,I/jxcore-log( 6107): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6107): 
,I/jxcore-log( 6107): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6107): 
,I/jxcore-log( 6107): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6107): 
,I/[SystemUI]TimeTickManager( 1451): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1451): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1451): called onTimeUpdated()
I/[SystemUI]Clock( 1451): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1451): called onTimeUpdated()
I/[SystemUI]DateView( 1451): called onTimeUpdated()
I/[SystemUI]DateView( 1451): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1451): handleTimeUpdate
D/sensors_hal_Time( 1029): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1029): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1029): tsOffsetIs: Apps: 414055977448; DSPS: 13709204; Offset : -4327623291
,I/jxcore-log( 6107): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6107): 
,I/jxcore-log( 6107): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6107): 
,I/jxcore-log( 6107): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6107): 
,I/jxcore-log( 6107): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6107): 
,D/sensors_hal_Time( 1029): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1029): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1029): tsOffsetIs: Apps: 434058147442; DSPS: 14364635; Offset : -4327620098
,I/jxcore-log( 6107): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6107): 
,I/jxcore-log( 6107): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6107): 
,I/jxcore-log( 6107): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6107): 
,I/jxcore-log( 6107): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6107): 
,D/sensors_hal_Time( 1029): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1029): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1029): tsOffsetIs: Apps: 454060472643; DSPS: 15020071; Offset : -4327614076
,I/jxcore-log( 6107): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6107): 
,I/jxcore-log( 6107): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6107): 
,I/jxcore-log( 6107): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6107): 
,I/jxcore-log( 6107): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6107): 
,I/[SystemUI]TimeTickManager( 1451): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1451): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1451): called onTimeUpdated()
I/[SystemUI]Clock( 1451): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1451): called onTimeUpdated()
I/[SystemUI]DateView( 1451): called onTimeUpdated()
I/[SystemUI]DateView( 1451): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1451): handleTimeUpdate
D/sensors_hal_Time( 1029): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1029): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1029): tsOffsetIs: Apps: 474062382219; DSPS: 15675493; Offset : -4327596538
,I/jxcore-log( 6107): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6107): 
,I/jxcore-log( 6107): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6107): 
,I/jxcore-log( 6107): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6107): 
,I/jxcore-log( 6107): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6107): 
,D/sensors_hal_Time( 1029): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1029): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1029): tsOffsetIs: Apps: 494063969138; DSPS: 16330906; Offset : -4327627650
,I/jxcore-log( 6107): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6107): 
,I/jxcore-log( 6107): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6107): 
,I/jxcore-log( 6107): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6107): 
,I/jxcore-log( 6107): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6107): 
,D/sensors_hal_Time( 1029): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1029): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1029): tsOffsetIs: Apps: 514066177828; DSPS: 16986338; Offset : -4327615730
,I/jxcore-log( 6107): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6107): 
,I/jxcore-log( 6107): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6107): 
,I/jxcore-log( 6107): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6107): 
,I/jxcore-log( 6107): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6107): 
,I/[SystemUI]TimeTickManager( 1451): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1451): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1451): called onTimeUpdated()
I/[SystemUI]Clock( 1451): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1451): called onTimeUpdated()
I/[SystemUI]DateView( 1451): called onTimeUpdated()
I/[SystemUI]DateView( 1451): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1451): handleTimeUpdate
D/sensors_hal_Time( 1029): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1029): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1029): tsOffsetIs: Apps: 534068080007; DSPS: 17641760; Offset : -4327605511
,I/jxcore-log( 6107): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6107): 
,I/jxcore-log( 6107): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6107): 
,I/jxcore-log( 6107): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6107): 
,I/jxcore-log( 6107): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6107): 
,D/sensors_hal_Time( 1029): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1029): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1029): tsOffsetIs: Apps: 554070373230; DSPS: 18297195; Offset : -4327601340
,I/jxcore-log( 6107): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6107): 
,I/jxcore-log( 6107): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6107): 
,I/jxcore-log( 6107): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6107): 
,I/jxcore-log( 6107): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6107): 
,D/sensors_hal_Time( 1029): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1029): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1029): tsOffsetIs: Apps: 574072313378; DSPS: 18952619; Offset : -4327614135
,I/jxcore-log( 6107): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6107): 
,I/jxcore-log( 6107): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6107): 
,I/jxcore-log( 6107): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6107): 
,I/jxcore-log( 6107): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6107): 
,I/[SystemUI]TimeTickManager( 1451): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1451): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1451): called onTimeUpdated()
I/[SystemUI]Clock( 1451): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1451): called onTimeUpdated()
I/[SystemUI]DateView( 1451): called onTimeUpdated()
I/[SystemUI]DateView( 1451): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1451): handleTimeUpdate
D/sensors_hal_Time( 1029): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1029): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1029): tsOffsetIs: Apps: 594074239985; DSPS: 19608042; Offset : -4327610266
,I/jxcore-log( 6107): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6107): 
,I/jxcore-log( 6107): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6107): 
,I/jxcore-log( 6107): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6107): 
,I/jxcore-log( 6107): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6107): 
,D/sensors_hal_Time( 1029): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1029): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1029): tsOffsetIs: Apps: 614076517894; DSPS: 20263476; Offset : -4327590554
,I/jxcore-log( 6107): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6107): 
,I/jxcore-log( 6107): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6107): 
,I/jxcore-log( 6107): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6107): 
,I/jxcore-log( 6107): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6107): 
,D/sensors_hal_Time( 1029): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1029): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1029): tsOffsetIs: Apps: 634078670385; DSPS: 20918907; Offset : -4327604760
,I/jxcore-log( 6107): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6107): 
,I/jxcore-log( 6107): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6107): 
,I/jxcore-log( 6107): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6107): 
,I/jxcore-log( 6107): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6107): 
,I/[SystemUI]TimeTickManager( 1451): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1451): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1451): called onTimeUpdated()
I/[SystemUI]Clock( 1451): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1451): called onTimeUpdated()
I/[SystemUI]DateView( 1451): called onTimeUpdated()
I/[SystemUI]DateView( 1451): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1451): handleTimeUpdate
V/GLSActivity( 2108): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2108): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 2108): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2108): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2108): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2108): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1029): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1029): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1029): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1029): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1029): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1393): onNotificationPosted
,D/SmartCoverUpdateMonitor( 1393): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1393): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1393): handleNotificationPosted(true)
D/QuickCircle( 1393): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1393): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1393): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1393): post do just update job
D/LgeQuickCoverNotificationData( 1393): showAll3
D/LgeQuickCoverNotificationData( 1393): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1393): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
D/LgeQuickCoverNotificationData( 1393): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
E/LgeQuickCoverOverlayWindow( 1393): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1393): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1393): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1393): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1393): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1393): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1393): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1393): updateNotificationData: count=3
W/GLSActivity( 2108): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2108): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2108): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2108): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2108): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2108): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2108): 	at android.os.Binder.execTransact(Binder.java:446)
,E/PlayEventLogger( 4896): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 4896): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 4896): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/PlayEventLogger( 4896): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 4896): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/PlayEventLogger( 4896): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 4896): 	at android.os.Binder.execTransact(Binder.java:446)
W/System  ( 4896): Ignoring header User-Agent because its value was null.
D/libc-netbsd(  309): default dns: query_ipv6=0, query_ipv4=0
D/DSQN    ( 1029): DNSproblemNotiEnabled is disabled ignore DNS fail CB
D/QuickStatusbarLayout( 1393): Notification difference=198
D/QuickStatusbarLayout( 1393): child = android.widget.LinearLayout{156a1e25 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,D/sensors_hal_Time( 1029): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1029): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1029): tsOffsetIs: Apps: 654080962567; DSPS: 21574342; Offset : -4327601473
,I/jxcore-log( 6107): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6107): 
,I/jxcore-log( 6107): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6107): 
,I/jxcore-log( 6107): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6107): 
,I/jxcore-log( 6107): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6107): 
,D/sensors_hal_Time( 1029): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1029): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1029): tsOffsetIs: Apps: 674082868964; DSPS: 22229765; Offset : -4327617605
,I/jxcore-log( 6107): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6107): 
,I/jxcore-log( 6107): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6107): 
,I/jxcore-log( 6107): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6107): 
,I/jxcore-log( 6107): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6107): 
,D/sensors_hal_Time( 1029): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1029): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1029): tsOffsetIs: Apps: 694085038019; DSPS: 22885196; Offset : -4327615297
,D/PowerManagerServiceEx( 1029): acquireWakeLockInternal: lock=231167151, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1029
,V/AlarmManager( 1029): ELAPSED_WAKEUP set : Alarm{124192dd type 2 when 541616 com.google.android.gms} when 541616
,D/[Concierge]Service( 2611): onStartCommand(). Type : 9
,D/libc-netbsd(  309): default dns: query_ipv6=0, query_ipv4=0
,D/DSQN    ( 1029): DNSproblemNotiEnabled is disabled ignore DNS fail CB
,D/PowerManagerServiceEx( 1029): releaseWakeLockInternal: lock=231167151 [*alarm*], flags=0x0
I/jxcore-log( 6107): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6107): 
,I/jxcore-log( 6107): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6107): 
,I/jxcore-log( 6107): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6107): 
,I/[SystemUI]TimeTickManager( 1451): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1451): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1451): called onTimeUpdated()
I/[SystemUI]Clock( 1451): called onTimeUpdated()
I/LgeClockWidgetControlView( 1451): called onTimeUpdated()
I/[SystemUI]DateView( 1451): called onTimeUpdated()
I/[SystemUI]DateView( 1451): called onTimeUpdated()
,D/KeyguardUpdateMonitor( 1451): handleTimeUpdate
I/jxcore-log( 6107): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6107): 
,D/sensors_hal_Time( 1029): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1029): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1029): tsOffsetIs: Apps: 714087072283; DSPS: 23540622; Offset : -4327595195
,I/jxcore-log( 6107): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6107): 
,I/jxcore-log( 6107): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6107): 
,I/jxcore-log( 6107): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6107): 
,I/[SystemUI]LGPowerUI( 1451): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1451): On Skip Timer : true
,D/LEDHandler( 1945): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1945): Battery Level Remaining: 100%
D/LEDHandler( 1945): Battery Temp: 285, mChargingStatus=5, mChargingStop=false
,D/KeyguardUpdateMonitor( 1451): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 285
I/[SystemUI]LGPowerUI( 1451): onReceive = android.intent.action.BATTERY_CHANGED
D/WifiController( 1029): battery changed pluggedType: 2
I/[SystemUI]BatterySaverHandler( 1451): onReceive = android.intent.action.BATTERY_CHANGED
D/HeadsetStateMachine( 6189): Disconnected process message: 10, size: 0
W/Settings( 1029): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1029): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/LGDMClient( 3924): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.intent.action.BATTERY_CHANGED
D/LGDMClient( 3924): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
I/jxcore-log( 6107): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6107): 
,D/sensors_hal_Time( 1029): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1029): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1029): tsOffsetIs: Apps: 734089034930; DSPS: 24196047; Offset : -4327616216
,I/jxcore-log( 6107): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6107): 
,I/jxcore-log( 6107): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6107): 
,I/jxcore-log( 6107): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6107): 
,I/jxcore-log( 6107): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6107): 
,D/sensors_hal_Time( 1029): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1029): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1029): tsOffsetIs: Apps: 754091480393; DSPS: 24851487; Offset : -4327612003
,I/jxcore-log( 6107): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6107): 
,I/jxcore-log( 6107): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6107): 
,I/jxcore-log( 6107): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6107): 
,I/[SystemUI]TimeTickManager( 1451): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1451): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1451): called onTimeUpdated()
I/[SystemUI]Clock( 1451): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1451): called onTimeUpdated()
I/[SystemUI]DateView( 1451): called onTimeUpdated()
I/[SystemUI]DateView( 1451): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1451): handleTimeUpdate
I/jxcore-log( 6107): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6107): 
,D/sensors_hal_Time( 1029): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1029): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1029): tsOffsetIs: Apps: 774093677677; DSPS: 25506919; Offset : -4327612063
,I/jxcore-log( 6107): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6107): 
,I/jxcore-log( 6107): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6107): 
,I/jxcore-log( 6107): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6107): 
,I/jxcore-log( 6107): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6107): 
,D/sensors_hal_Time( 1029): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1029): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1029): tsOffsetIs: Apps: 794095141678; DSPS: 26162327; Offset : -4327613245
,D/PowerManagerServiceEx( 1029): acquireWakeLockInternal: lock=231167151, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1029
,D/LIA_Informant_Tips_UserGuideCardScheduler( 2707): onReceive! : com.lge.ia.task.informant.dyk.userguide.UserGuideCardScheduler
I/LIA_Informant_Tips_LogTracer( 2707): [Log Tracer - Schedule Transition] UserGuide, ALARM_RECEIVE : 2015-12-03 16:33:25...... Request
D/LIA_Informant_Tips_CardFlowHandlerBase( 2707): onSchedule() - Intent { act=com.lge.ia.task.informant.dyk.userguide.UserGuideCardScheduler flg=0x14 (has extras) }
V/AlarmManager( 1029): RTC_WAKEUP set : Alarm{34990e52 type 0 when 1449156780339 com.lge.ia.task.informant} when 1449156780339
D/[Concierge]Service( 2611): onStartCommand(). Type : 9
,I/jxcore-log( 6107): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6107): 
I/LIA_Informant_BoardStateUtil( 2707): isEnabledGBoard() : count > 0 - true
D/LIA_Informant_BoardStateUtil( 2707): isEnabledMyGuideOfGboard : true
,D/LIA_Informant_Tips_CardFlowHandlerBase( 2707): onSchedule() : Board Status : Show Card - 7
I/LIA_Informant_Tips_CardFlowHandlerBase( 2707): onSchedule() : cardType - guide
,D/LIA_Informant_Tips_FeatureConditionChecker( 2707): check (maxCardNum : 1)
D/LIA_Informant_Tips_UserGuideDBManager( 2707): getCandidateFeatureList
D/LIA_Informant_Tips_UserGuideXMLParser( 2707): getXML() : Ok - system/etc/mrg_default_forms/MyGuide/MyGuideBoard/UserGuideCard/userguidecard.xml
,I/LIA_Informant_Tips_FeatureConditionChecker( 2707): Step A : featureList size - 11
D/LIA_Informant_Tips_UserGuideDBManager( 2707): getTotalUsed
I/LIA_Informant_Tips_FeatureConditionChecker( 2707): Step B : featureID - 7, featureName - ugc_qremote_on_alarm, appName - qremote, appUsed - 0, score - 3.999999900000005
,I/LIA_Informant_Tips_FeatureConditionChecker( 2707): Step B : featureID - 22, featureName - ugc_oho_dial_keypad, appName - one_hand_operation, appUsed - 0, score - 3.999999900000005
I/LIA_Informant_Tips_FeatureConditionChecker( 2707): Step B : featureID - 25, featureName - ugc_navigationbar, appName - navigationbar, appUsed - 0, score - 3.999999900000005
I/LIA_Informant_Tips_FeatureConditionChecker( 2707): Step B : featureID - 3, featureName - ugc_camera_dual, appName - camera, appUsed - 0, score - 4.999999900000005
I/LIA_Informant_Tips_FeatureConditionChecker( 2707): Step B : featureID - 9, featureName - ugc_qremote_always_home, appName - qremote, appUsed - 0, score - 4.999999900000005
I/LIA_Informant_Tips_FeatureConditionChecker( 2707): Step B : featureID - 12, featureName - ugc_battery_power_saver, appName - battery, appUsed - 0, score - 4.999999900000005
I/LIA_Informant_Tips_FeatureConditionChecker( 2707): Step B : featureID - 16, featureName - ugc_gesture_motion_call, appName - gesture, appUsed - 8, score - 4.000335462594356
I/LIA_Informant_Tips_FeatureConditionChecker( 2707): Step B : featureID - 23, featureName - ugc_oho_lockscreen, appName - one_hand_operation, appUsed - 0, score - 4.999999900000005
I/LIA_Informant_Tips_FeatureConditionChecker( 2707): Step B : featureID - 26, featureName - ugc_lg_backup, appName - lg_backup, appUsed - 0, score - 4.999999900000005
I/LIA_Informant_Tips_FeatureConditionChecker( 2707): Step B : featureID - 28, featureName - ugc_home_edit_page, appName - home, appUsed - 0, score - 4.999999900000005
I/LIA_Informant_Tips_FeatureConditionChecker( 2707): Step B : featureID - 31, featureName - ugc_home_folder, appName - home, appUsed - 0, score - 4.999999900000005
D/LIA_Informant_Tips_UserGuideDBManager( 2707): getAppListOfPrevCard
D/LIA_Informant_Tips_FeatureConditionChecker( 2707): Step C : prevAppList - camera
,D/LIA_Informant_Tips_FeatureConditionChecker( 2707): Step C : featureList size - 11
D/LIA_Informant_Tips_FeatureConditionChecker( 2707): Step C : prevAppList - camera
D/LIA_Informant_Tips_FeatureConditionChecker( 2707): Step C : all same app : false
D/LIA_Informant_Tips_FeatureConditionChecker( 2707): Step C : featureList isAllContains prevApp : false
I/LIA_Informant_Tips_FeatureConditionChecker( 2707): Step C : getFeatureOfMinScore feature - ugc_navigationbar, score - 3.999999900000005
I/LIA_Informant_Tips_FeatureConditionChecker( 2707): Step C : selectLowestScoreCardList - cardList size=1
D/LIA_Informant_Tips_CardFlowHandlerBase( 2707): getCardGeneratorList() : boardStatus - 7
D/LIA_Informant_Tips_UserGuideXMLParser( 2707): getXML() : Ok - system/etc/mrg_default_forms/MyGuide/MyGuideBoard/UserGuideCard/userguidecard.xml
D/LIA_Informant_Tips_UserGuideXMLParser( 2707): getParamList() : paramList-1
,I/LIA_Informant_Tips_CardFormUtil( 2707): getDYKCardPath() : cardType - guide, path - file:///system/etc/mrg_default_forms/MyGuide/MyGuideBoard/UserGuideCard/dyk_userguide_card.html
I/LIA_Informant_Tips_LogTracer( 2707): [Log Tracer - Card Generation] UserGuide, DYK, CARD_CMD_ADD, guide_1111111111116_ugc_navigationbar...... Request
D/LIA_Informant_Tips_DYKCardGenerator( 2707): sendCard : file:///system/etc/mrg_default_forms/MyGuide/MyGuideBoard/UserGuideCard/dyk_userguide_card.html?id=guide_1111111111116_ugc_navigationbar&title=[@string/display_home_touch_buttons]&desc=[@string/dyk_ugc_navigationbar_desc]&bgimg=res/drawable/navigation.jpg&iconimg=res/drawable/ic_null.png&goto_app=intent%3A%2F%2F%23Intent%3Bcomponent%3Dcom.android.settings%2F.Settings%2524ButtonCombinationDragActivity%3BS.cardid%3D%5B%40param%2Fid%5D%3Bend&url=intent%3A%2F%2F%23Intent%3Bcomponent%3Dcom.android.settings%2F.Settings%2524ButtonCombinationDragActivity%3BS.cardid%3D%5B%40param%2Fid%5D%3Bend
D/LIA_Informant_ActionManagerMessageHandler( 2707): setCard
D/ActionManagerService( 1909): executeCardCommand(0, com.lge.intent.category.doyouknow.GUIDE)
D/LIA_Informant_Tips_UserGuideDBManager( 2707): setUploadCardInfo
I/LIA_Informant_Tips_LogTracer( 2707): [Log Tracer - Card Generation] UserGuide, GBoard, CARD_CMD_ADD, guide_1111111111116_1449156806130...... Request
,I/LIA_Informant_Tips_CardFormUtil( 2707): getGBoardCardPath() : cardType - guide, path - file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/1/userguide.html
D/LIA_Informant_Tips_GBoardCardGenerator( 2707): sendCard : file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/1/userguide.html?id=guide_1111111111116_1449156806130&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
D/LIA_Informant_ActionManagerMessageHandler( 2707): setCard
,D/ActionManagerService( 1909): executeCardCommand(0, com.lge.intent.category.gboard.DOYOUKNOW)
D/LIA_Informant_Tips_UserGuideDBManager( 2707): setUploadCardInfo
I/LIA_Informant_Tips_LogTracer( 2707): [Log Tracer - Card Generation] UserGuide, Concierge, CARD_CMD_ADD, guide_1111111111116...... Request
,D/LIA_Informant_Tips_ConciergeCardGenerator( 2707): sendCard : my_guide?id=guide_1111111111116&summary=%5B%40string%2Fguide_summary%5D&source=%5B%40string%2Fguide_source%5D&key_data=id&category=com.lge.intent.category.doyouknow.*&expire_time=1449329606155
D/LIA_Informant_ActionManagerMessageHandler( 2707): setCard
D/ActionManagerService( 1909): executeCardCommand(0, com.lge.intent.category.CONCIERGE)
D/LIA_Informant_Tips_UserGuideDBManager( 2707): setUploadCardInfo
D/[Concierge]Service( 2611): Card command received
V/BoardContentProvider( 2707): query(): uri(content://com.lge.mrg.boardcontent/concierge) projection([id]) order(null)
I/LIA_Informant_Tips_UserGuideCardFlowHandler( 2707): updateStateCardGenerated() : UserGuide Working Duration Count is reset to 1
,D/LIA_Informant_Tips_UserGuideCardScheduler( 2707): cancel
,I/LIA_Informant_Tips_LogTracer( 2707): [Log Tracer - Schedule Transition] UserGuide, DATE_RESET : working count : 1...... Request
,D/PowerManagerServiceEx( 1029): releaseWakeLockInternal: lock=231167151 [*alarm*], flags=0x0
D/[Concierge]CardInfo( 2611): CardInfo loaded.  Path (/system/etc/mrg_default_forms/ConciergeBoard/card_forms/my_guide), Version (1.0.0)
D/[Concierge]CardNotifier( 2611): Send card notification. Card id : guide_1111111111116
I/ActivityManager( 1029): Start proc com.lge.doyouknow for broadcast com.lge.doyouknow/.DYKBoardReceiver: pid=6669 uid=10036 gids={50036, 9997, 3003, 1028} abi=armeabi
,D/LIA_MrGDBLogger_BoardDetector( 2707): [dreamwood]dreamwood check json : {"card_cmd":"add","card_name":"my_guide","day_of_week":5,"id":"[guide_1111111111116]"}
,I/DYKBoardReceiver( 6669): action = com.lge.mrg.service.action.CARD_COMMAND
,I/DYKBoardReceiver( 6669): Card info : card Command = 0 category = com.lge.intent.category.doyouknow.GUIDE uri =file:///system/etc/mrg_default_forms/MyGuide/MyGuideBoard/UserGuideCard/dyk_userguide_card.html?id=guide_1111111111116_ugc_navigationbar&title=[@string/display_home_touch_buttons]&desc=[@string/dyk_ugc_navigationbar_desc]&bgimg=res/drawable/navigation.jpg&iconimg=res/drawable/ic_null.png&goto_app=intent%3A%2F%2F%23Intent%3Bcomponent%3Dcom.android.settings%2F.Settings%2524ButtonCombinationDragActivity%3BS.cardid%3D%5B%40param%2Fid%5D%3Bend&url=intent%3A%2F%2F%23Intent%3Bcomponent%3Dcom.android.settings%2F.Settings%2524ButtonCombinationDragActivity%3BS.cardid%3D%5B%40param%2Fid%5D%3Bend
D/DYKBoardProvider( 6669): insert
V/BoardContentProvider( 2707): insert(): uri(content://com.lge.mrg.boardcontent/doyouknow)
I/BoardContentProvider( 2707): notify insert: uri = content://com.lge.mrg.boardcontent/doyouknow
,D/DYKBoard:MainActivity( 6669): loadingFullCard
V/NotificationService( 1029): enqueueNotificationInternal: pkg=com.lge.concierge id=915 notification=Notification(pri=0 contentView=null vibrate=[0,0,0,0] sound=content://media/internal/audio/media/39 defaults=0x0 flags=0x11 color=0x00000000 vis=PUBLIC)
,D/ZenLog  ( 1029): intercepted: 0|com.lge.concierge|915|null|10017,none
D/BoardContract.Concierge( 2611): insert
V/NotificationService( 1029): pkg=com.lge.concierge canInterrupt=false intercept=true
I/NotificationServiceEx( 1029): LED remove() : mLights=0|com.lge.concierge|915|null|10017
D/NotificationServiceEx( 1029): updateLightListLocked :r=0|com.lge.concierge|915|null|10017, action=2
D/NotificationServiceEx( 1029): notification=Notification(pri=0 contentView=null vibrate=[0,0,0,0] sound=content://media/internal/audio/media/39 defaults=0x0 flags=0x11 color=0x00000000 vis=PUBLIC)
D/lightsbindercall( 1029): calling ... updateLightList
V/BoardContentProvider( 2707): query(): uri(content://com.lge.mrg.boardcontent/concierge) projection([id]) order(null)
E/lightsbindercall( 1029): virtual void android::BpLEDManager::updateLightList(int32_t, int32_t, int, int32_t, int32_t, int32_t, const android::String16&) : Binder Transaction Start!!
D/LEDService( 1945): updateLightListInternal() : action=2 pkg=com.lge.concierge
E/lightsbindercall( 1029): virtual void android::BpLEDManager::updateLightList(int32_t, int32_t, int, int32_t, int32_t, int32_t, const android::String16&) : Binder Transaction End!! (error code 0)
V/BoardContentProvider( 2707): insert(): uri(content://com.lge.mrg.boardcontent/concierge)
D/LgeQuickCoverNLService( 1393): onNotificationPosted
,D/SmartCoverUpdateMonitor( 1393): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1393): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1393): handleNotificationPosted(true)
D/QuickCircle( 1393): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1393): post() sbn.getKey(): 0|com.lge.concierge|915|null|10017
D/LgeQuickCoverNotificationData( 1393): post() sbn.getGroupKey(): 0|com.lge.concierge|915|null|10017
D/LgeQuickCoverNotificationData( 1393): post do add job
D/LgeQuickCoverNotificationData( 1393): add : 3
D/LgeQuickCoverNotificationData( 1393): do add job
D/LgeQuickCoverNotificationData( 1393): showAll4
D/LgeQuickCoverNotificationData( 1393): showAll() ID : 915,0|com.lge.concierge|915|null|10017
D/LgeQuickCoverNotificationData( 1393): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1393): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
D/LgeQuickCoverNotificationData( 1393): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
E/LgeQuickCoverOverlayWindow( 1393): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1393): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1393): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1393): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1393): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1393): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1393): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1393): [native noti] inex =  3
D/LgeQuickCoverNotificationData( 1393): isNotificationForCurrentUser : true
I/BoardContentProvider( 2707): notify insert: uri = content://com.lge.mrg.boardcontent/concierge
,E/LgeQuickCoverOverlayWindow( 1393): updateNotificationData: count=4
D/QuickStatusbarLayout( 1393): Notification difference=198
D/[Concierge]AConciergeServiceListener( 2059): Msg received + type = 0
D/QuickStatusbarLayout( 1393): child = android.widget.LinearLayout{156a1e25 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
D/[Concierge][WearableNotifier]( 2611): sendWearableNotification, Name = my_guide, title = Smart Tips
D/[Concierge]CardInfo( 2059): CardInfo loaded.  Path (/system/etc/mrg_default_forms/ConciergeBoard/card_forms/my_guide), Version (1.0.0)
,I/PeerNotificationManager( 2611): startService :: notifyToSideOnly
I/PeerNotificationManager( 2611): SideServiceConnection
W/ActivityManager( 1029): Unable to start service Intent { act=com.lge.wmanClients.notification.SideNotificationService pkg=com.lge.wman } U=0: not found
D/[Concierge][WearableNotifier]( 2611): sendWearableNotification, sent id = 1195088426
,W/[Concierge]StringReplacer( 2059): Token not found. Keep token string : param/id
W/[Concierge]StringReplacer( 2059): Token not found. Keep token string : param/id
W/[Concierge]StringReplacer( 2059): Token not found. Keep token string : encode.json:card/action_delete
D/[Concierge]WebView( 2059): Add card 
,D/[Concierge]WebView_Console( 2059): Theme name is empty or null. For : DIV. Apply default theme
,D/[Concierge]WebView_Console( 2059): converting : /system/etc/mrg_default_forms/ConciergeBoard/card_forms/my_guide/res/drawable-xxhdpi/style.css
,I/WebViewFactory( 6669): Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
D/[Concierge]WebView_Console( 2059): converting : /system/etc/mrg_default_forms/ConciergeBoard/card_forms/my_guide/res/drawable-xxxhdpi/style.css
,I/LibraryLoader( 6669): Loading: webviewchromium
,I/LibraryLoader( 6669): Time to load native libraries: 7 ms (timestamps 9805-9812)
I/LibraryLoader( 6669): Expected native library version number "",actual native library version number ""
D/[Concierge]WebView( 2059): Is VZW : false
,V/WebViewChromiumFactoryProvider( 6669): Binding Chromium to main looper Looper (main, tid 1) {339cb5c7}
,I/LibraryLoader( 6669): Expected native library version number "",actual native library version number ""
I/chromium( 6669): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
D/[Concierge]WebView( 2059): Is VZW : false
D/[Concierge]WebView( 2059): isEulaAccepted : true
,I/BrowserStartupController( 6669): Initializing chromium process, renderers=0
W/art     ( 6669): Attempt to remove local handle scope entry from IRT, ignoring
W/chromium( 6669): [WARNING:dns_config_service_posix.cc(293)] Failed to read DnsConfig.
,W/chromium( 6669): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
,I/chromium( 6669): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=33 off=46780 len=2953
I/chromium( 6669): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:34 off:229536 len:643667
V/AudioPolicyService(  314): registerClient() client 0xb1427c40, uid 10036
,W/AudioManagerAndroid( 6669): Requires BLUETOOTH permission
D/[Concierge]WebView_Console( 2059): url("concierge_popup_icon_17.png") -> url(/system/etc/mrg_default_forms/ConciergeBoard/card_forms/my_guide/res/drawable-xxhdpi/concierge_popup_icon_17.png)
,D/[Concierge]WebView_Console( 2059): url("concierge_popup_icon_17.png") -> url(/system/etc/mrg_default_forms/ConciergeBoard/card_forms/my_guide/res/drawable-xxxhdpi/concierge_popup_icon_17.png)
I/Adreno-EGL( 6669): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 6669): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 6669): Build Date: 12/12/14 금
I/Adreno-EGL( 6669): Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
I/Adreno-EGL( 6669): Remote Branch: 
I/Adreno-EGL( 6669): Local Patches: 
I/Adreno-EGL( 6669): Reconstruct Branch: 
W/chromium( 6669): [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
,W/chromium( 6669): [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
W/art     ( 6669): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 6669): onDetachedFromWindow called when already detached. Ignoring
W/art     ( 6669): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 6669): Attempt to remove local handle scope entry from IRT, ignoring
D/DYKBoard:MainActivity( 6669): mDYKEventWebView load contents
,I/ActivityManager( 1029): Killing 5886:com.google.android.apps.docs/u0a61 (adj 15): empty #17
D/LgDataFeature( 6669): LgDataFeature() Constructor: none
D/LgDataFeature( 6669): LgDataFeature() Constructor Done, null
,W/libprocessgroup( 1029): failed to open /acct/uid_10061/pid_5886/cgroup.procs: No such file or directory
,D/GBoardUriUtils( 2059): fileExists: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/1/userguide2.html?id=guide_1111111111116_1449156806130&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay return true
D/GBoardWebViewUtils( 2059): changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/1/userguide2.html?id=guide_1111111111116_1449156806130&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
,V/BoardContentProvider( 2707): query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
D/GBoardCardProvider( 2059): deleteById id:guide_1111111111116_1448553258556
V/BoardContentProvider( 2707): delete(): uri(content://com.lge.mrg.boardcontent/gboard)
,I/BoardContentProvider( 2707): notify delete: uri = content://com.lge.mrg.boardcontent/gboard
W/System.err( 2059): java.lang.NumberFormatException: Invalid int: "null"
W/System.err( 2059): 	at java.lang.Integer.invalidInt(Integer.java:138)
W/System.err( 2059): 	at java.lang.Integer.parseInt(Integer.java:358)
W/System.err( 2059): 	at java.lang.Integer.parseInt(Integer.java:334)
W/System.err( 2059): 	at com.lge.launcher2.gboard.database.GBoardCardProvider.getExpireTime(GBoardCardProvider.java:47)
W/System.err( 2059): 	at com.lge.launcher2.gboard.database.GBoardCardProvider.insertCard(GBoardCardProvider.java:34)
W/System.err( 2059): 	at com.lge.launcher2.gboard.GBoardWebViewUtils.addCard(GBoardWebViewUtils.java:44)
W/System.err( 2059): 	at com.lge.launcher2.gboard.GBoardReceiver.onReceive(GBoardReceiver.java:36)
W/System.err( 2059): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2586)
W/System.err( 2059): 	at android.app.ActivityThread.access$1700(ActivityThread.java:148)
W/System.err( 2059): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1360)
W/System.err( 2059): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 2059): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 2059): 	at android.app.ActivityThread.main(ActivityThread.java:5274)
W/System.err( 2059): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 2059): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 2059): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
W/System.err( 2059): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
D/GBoardCardProvider( 2059): insert
V/BoardContentProvider( 2707): insert(): uri(content://com.lge.mrg.boardcontent/gboard)
,I/BoardContentProvider( 2707): notify insert: uri = content://com.lge.mrg.boardcontent/gboard
I/chromium( 6669): [INFO:CONSOLE(1)] "Uncaught ReferenceError: collapseCard is not defined", source:  (1)
,I/GBoardtInterface( 2059): exportHTML()
,I/chromium( 6669): [INFO:SkFontConfigInterface_android.cpp(247)] ---- failed to open </system/fonts/CutiveMono.ttf> as a font
I/chromium( 6669): 
,I/chromium( 6669): [INFO:CONSOLE(738)] "on load event", source: file:///android_asset/www/js/controlCards.js (738)
,E/DYKBoard( 6669): onPageFinished url:file:///android_asset/www/dykContainer.html?deviceHeight=531
,V/BoardContentProvider( 2707): query(): uri(content://com.lge.mrg.boardcontent/doyouknow) projection(null) order(null)
V/BoardContentProvider( 2707): query(): uri(content://com.lge.mrg.boardcontent/doyouknow) projection(null) order(null)
V/BoardContentProvider( 2707): query(): uri(content://com.lge.mrg.boardcontent/doyouknow) projection(null) order(create_time asc)
,D/DYKBoard:MainActivity( 6669): mDYKEventWebView load contents
,I/chromium( 6669): [INFO:CONSOLE(61)] "addAllCard-----------------------", source: file:///android_asset/www/js/controlCards.js (61)
I/chromium( 6669): [INFO:CONSOLE(50)] "[object Object]", source: file:///android_asset/www/libs/form_converter.js (50)
,I/chromium( 6669): [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
I/chromium( 6669): 
,I/chromium( 6669): [INFO:CONSOLE(50)] "[object Object]", source: file:///android_asset/www/libs/form_converter.js (50)
,I/chromium( 6669): [INFO:CONSOLE(57)] "file:///system/etc/mrg_default_forms/MyGuide/MyGuideBoard/Initial/textlink/res/values/strings.xml", source: file:///android_asset/www/libs/string_replacer.js (57)
,I/chromium( 6669): [INFO:CONSOLE(57)] "file:///system/etc/mrg_default_forms/MyGuide/MyGuideBoard/Initial/oiscamera/res/values/strings.xml", source: file:///android_asset/www/libs/string_replacer.js (57)
I/chromium( 6669): [INFO:CONSOLE(57)] "file:///system/etc/mrg_default_forms/MyGuide/MyGuideBoard/Initial/guestmode/res/values/strings.xml", source: file:///android_asset/www/libs/string_replacer.js (57)
,I/chromium( 6669): [INFO:CONSOLE(57)] "file:///data/user/0/com.lge.formmanager/files/MyGuide_MyGuideBoard_PromotionCard_DualWindow/res/values/strings.xml", source: file:///android_asset/www/libs/string_replacer.js (57)
I/chromium( 6669): [INFO:CONSOLE(57)] "file:///data/user/0/com.lge.formmanager/files/MyGuide_MyGuideBoard_PromotionCard_SmartKeyboard/res/values/strings.xml", source: file:///android_asset/www/libs/string_replacer.js (57)
,I/chromium( 6669): [INFO:CONSOLE(57)] "file:///data/user/0/com.lge.formmanager/files/MyGuide_MyGuideBoard_PromotionCard_QuadHD/res/values/strings.xml", source: file:///android_asset/www/libs/string_replacer.js (57)
I/chromium( 6669): [INFO:CONSOLE(57)] "file:///data/user/0/com.lge.formmanager/files/MyGuide_MyGuideBoard_PromotionCard_SmartBulletin/res/values/strings.xml", source: file:///android_asset/www/libs/string_replacer.js (57)
,I/chromium( 6669): [INFO:CONSOLE(57)] "file:///data/user/0/com.lge.formmanager/files/MyGuide_MyGuideBoard_PromotionCard_QuickCircle/res/values/strings.xml", source: file:///android_asset/www/libs/string_replacer.js (57)
,I/chromium( 6669): [INFO:CONSOLE(57)] "file:///data/user/0/com.lge.formmanager/files/MyGuide_MyGuideBoard_PromotionCard_QuickCircleCase/res/values/strings.xml", source: file:///android_asset/www/libs/string_replacer.js (57)
,I/chromium( 6669): [INFO:CONSOLE(57)] "file:///system/etc/mrg_default_forms/MyGuide/MyGuideBoard/UserGuideCard/res/values/strings.xml", source: file:///android_asset/www/libs/string_replacer.js (57)
I/chromium( 6669): [INFO:CONSOLE(57)] "file:///system/etc/mrg_default_forms/MyGuide/MyGuideBoard/UserGuideCard/res/values/strings.xml", source: file:///android_asset/www/libs/string_replacer.js (57)
,I/chromium( 6669): [INFO:CONSOLE(57)] "file:///system/etc/mrg_default_forms/MyGuide/MyGuideBoard/UserGuideCard/res/values/strings.xml", source: file:///android_asset/www/libs/string_replacer.js (57)
I/chromium( 6669): [INFO:CONSOLE(57)] "file:///system/etc/mrg_default_forms/MyGuide/MyGuideBoard/UserGuideCard/res/values/strings.xml", source: file:///android_asset/www/libs/string_replacer.js (57)
,I/chromium( 6669): [INFO:CONSOLE(57)] "file:///system/etc/mrg_default_forms/MyGuide/MyGuideBoard/UserGuideCard/res/values/strings.xml", source: file:///android_asset/www/libs/string_replacer.js (57)
,I/chromium( 6669): [INFO:CONSOLE(57)] "file:///system/etc/mrg_default_forms/MyGuide/MyGuideBoard/UserGuideCard/res/values/strings.xml", source: file:///android_asset/www/libs/string_replacer.js (57)
I/chromium( 6669): [INFO:CONSOLE(57)] "file:///system/etc/mrg_default_forms/MyGuide/MyGuideBoard/UserGuideCard/res/values/strings.xml", source: file:///android_asset/www/libs/string_replacer.js (57)
,I/chromium( 6669): [INFO:CONSOLE(57)] "file:///system/etc/mrg_default_forms/MyGuide/MyGuideBoard/UserGuideCard/res/values/strings.xml", source: file:///android_asset/www/libs/string_replacer.js (57)
I/chromium( 6669): [INFO:CONSOLE(57)] "file:///system/etc/mrg_default_forms/MyGuide/MyGuideBoard/UserGuideCard/res/values/strings.xml", source: file:///android_asset/www/libs/string_replacer.js (57)
,I/chromium( 6669): [INFO:CONSOLE(57)] "file:///system/etc/mrg_default_forms/MyGuide/MyGuideBoard/UserGuideCard/res/values/strings.xml", source: file:///android_asset/www/libs/string_replacer.js (57)
I/chromium( 6669): [INFO:CONSOLE(57)] "file:///system/etc/mrg_default_forms/MyGuide/MyGuideBoard/UserGuideCard/res/values/strings.xml", source: file:///android_asset/www/libs/string_replacer.js (57)
,I/chromium( 6669): [INFO:CONSOLE(57)] "file:///system/etc/mrg_default_forms/MyGuide/MyGuideBoard/UserGuideCard/res/values/strings.xml", source: file:///android_asset/www/libs/string_replacer.js (57)
I/chromium( 6669): [INFO:CONSOLE(57)] "file:///system/etc/mrg_default_forms/MyGuide/MyGuideBoard/UserGuideCard/res/values/strings.xml", source: file:///android_asset/www/libs/string_replacer.js (57)
,I/chromium( 6669): [INFO:CONSOLE(57)] "file:///system/etc/mrg_default_forms/MyGuide/MyGuideBoard/UserGuideCard/res/values/strings.xml", source: file:///android_asset/www/libs/string_replacer.js (57)
I/chromium( 6669): [INFO:CONSOLE(57)] "file:///system/etc/mrg_default_forms/MyGuide/MyGuideBoard/UserGuideCard/res/values/strings.xml", source: file:///android_asset/www/libs/string_replacer.js (57)
,I/chromium( 6669): [INFO:CONSOLE(57)] "file:///system/etc/mrg_default_forms/MyGuide/MyGuideBoard/UserGuideCard/res/values/strings.xml", source: file:///android_asset/www/libs/string_replacer.js (57)
I/chromium( 6669): [INFO:CONSOLE(57)] "file:///system/etc/mrg_default_forms/MyGuide/MyGuideBoard/UserGuideCard/res/values/strings.xml", source: file:///android_asset/www/libs/string_replacer.js (57)
I/chromium( 6669): [INFO:CONSOLE(57)] "file:///system/etc/mrg_default_forms/MyGuide/MyGuideBoard/Initial/textlink/res/values-en/strings.xml", source: file:///android_asset/www/libs/string_replacer.js (57)
,I/chromium( 6669): [INFO:CONSOLE(57)] "file:///system/etc/mrg_default_forms/MyGuide/MyGuideBoard/Initial/oiscamera/res/values-en/strings.xml", source: file:///android_asset/www/libs/string_replacer.js (57)
I/chromium( 6669): [INFO:CONSOLE(57)] "file:///system/etc/mrg_default_forms/MyGuide/MyGuideBoard/Initial/guestmode/res/values-en/strings.xml", source: file:///android_asset/www/libs/string_replacer.js (57)
,I/chromium( 6669): [INFO:CONSOLE(57)] "file:///data/user/0/com.lge.formmanager/files/MyGuide_MyGuideBoard_PromotionCard_DualWindow/res/values-en/strings.xml", source: file:///android_asset/www/libs/string_replacer.js (57)
I/chromium( 6669): [INFO:CONSOLE(57)] "file:///data/user/0/com.lge.formmanager/files/MyGuide_MyGuideBoard_PromotionCard_SmartKeyboard/res/values-en/strings.xml", source: file:///android_asset/www/libs/string_replacer.js (57)
,I/chromium( 6669): [INFO:CONSOLE(57)] "file:///data/user/0/com.lge.formmanager/files/MyGuide_MyGuideBoard_PromotionCard_QuadHD/res/values-en/strings.xml", source: file:///android_asset/www/libs/string_replacer.js (57)
,I/chromium( 6669): [INFO:CONSOLE(57)] "file:///data/user/0/com.lge.formmanager/files/MyGuide_MyGuideBoard_PromotionCard_SmartBulletin/res/values-en/strings.xml", source: file:///android_asset/www/libs/string_replacer.js (57)
,I/chromium( 6669): [INFO:CONSOLE(57)] "file:///data/user/0/com.lge.formmanager/files/MyGuide_MyGuideBoard_PromotionCard_QuickCircle/res/values-en/strings.xml", source: file:///android_asset/www/libs/string_replacer.js (57)
I/chromium( 6669): [INFO:CONSOLE(57)] "file:///system/etc/mrg_default_forms/MyGuide/MyGuideBoard/UserGuideCard/res/values-en/strings.xml", source: file:///android_asset/www/libs/string_replacer.js (57)
,I/chromium( 6669): [INFO:CONSOLE(57)] "file:///system/etc/mrg_default_forms/MyGuide/MyGuideBoard/UserGuideCard/res/values-en/strings.xml", source: file:///android_asset/www/libs/string_replacer.js (57)
,I/chromium( 6669): [INFO:CONSOLE(57)] "file:///system/etc/mrg_default_forms/MyGuide/MyGuideBoard/UserGuideCard/res/values-en/strings.xml", source: file:///android_asset/www/libs/string_replacer.js (57)
,I/chromium( 6669): [INFO:CONSOLE(57)] "file:///system/etc/mrg_default_forms/MyGuide/MyGuideBoard/UserGuideCard/res/values-en/strings.xml", source: file:///android_asset/www/libs/string_replacer.js (57)
,I/chromium( 6669): [INFO:CONSOLE(57)] "file:///system/etc/mrg_default_forms/MyGuide/MyGuideBoard/UserGuideCard/res/values-en/strings.xml", source: file:///android_asset/www/libs/string_replacer.js (57)
,I/chromium( 6669): [INFO:CONSOLE(57)] "file:///data/user/0/com.lge.formmanager/files/MyGuide_MyGuideBoard_PromotionCard_QuickCircleCase/res/values-en/strings.xml", source: file:///android_asset/www/libs/string_replacer.js (57)
I/chromium( 6669): [INFO:CONSOLE(57)] "file:///system/etc/mrg_default_forms/MyGuide/MyGuideBoard/UserGuideCard/res/values-en/strings.xml", source: file:///android_asset/www/libs/string_replacer.js (57)
,I/chromium( 6669): [INFO:CONSOLE(57)] "file:///system/etc/mrg_default_forms/MyGuide/MyGuideBoard/UserGuideCard/res/values-en/strings.xml", source: file:///android_asset/www/libs/string_replacer.js (57)
,I/chromium( 6669): [INFO:CONSOLE(57)] "file:///system/etc/mrg_default_forms/MyGuide/MyGuideBoard/UserGuideCard/res/values-en/strings.xml", source: file:///android_asset/www/libs/string_replacer.js (57)
,I/chromium( 6669): [INFO:CONSOLE(57)] "file:///system/etc/mrg_default_forms/MyGuide/MyGuideBoard/UserGuideCard/res/values-en/strings.xml", source: file:///android_asset/www/libs/string_replacer.js (57)
,I/chromium( 6669): [INFO:CONSOLE(57)] "file:///system/etc/mrg_default_forms/MyGuide/MyGuideBoard/UserGuideCard/res/values-en/strings.xml", source: file:///android_asset/www/libs/string_replacer.js (57)
,I/chromium( 6669): [INFO:CONSOLE(57)] "file:///system/etc/mrg_default_forms/MyGuide/MyGuideBoard/UserGuideCard/res/values-en/strings.xml", source: file:///android_asset/www/libs/string_replacer.js (57)
,I/chromium( 6669): [INFO:CONSOLE(57)] "file:///system/etc/mrg_default_forms/MyGuide/MyGuideBoard/UserGuideCard/res/values-en/strings.xml", source: file:///android_asset/www/libs/string_replacer.js (57)
,I/chromium( 6669): [INFO:CONSOLE(57)] "file:///system/etc/mrg_default_forms/MyGuide/MyGuideBoard/UserGuideCard/res/values-en/strings.xml", source: file:///android_asset/www/libs/string_replacer.js (57)
,I/chromium( 6669): [INFO:CONSOLE(57)] "file:///system/etc/mrg_default_forms/MyGuide/MyGuideBoard/UserGuideCard/res/values-en/strings.xml", source: file:///android_asset/www/libs/string_replacer.js (57)
,I/chromium( 6669): [INFO:CONSOLE(57)] "file:///system/etc/mrg_default_forms/MyGuide/MyGuideBoard/UserGuideCard/res/values-en/strings.xml", source: file:///android_asset/www/libs/string_replacer.js (57)
,I/chromium( 6669): [INFO:CONSOLE(57)] "file:///system/etc/mrg_default_forms/MyGuide/MyGuideBoard/UserGuideCard/res/values-en/strings.xml", source: file:///android_asset/www/libs/string_replacer.js (57)
,I/chromium( 6669): [INFO:CONSOLE(57)] "file:///system/etc/mrg_default_forms/MyGuide/MyGuideBoard/UserGuideCard/res/values-en/strings.xml", source: file:///android_asset/www/libs/string_replacer.js (57)
,I/chromium( 6669): [INFO:CONSOLE(64)] "failed to load : file:///system/etc/mrg_default_forms/MyGuide/MyGuideBoard/Initial/textlink/res/values-en/strings.xml", source: file:///android_asset/www/libs/string_replacer.js (64)
I/chromium( 6669): [INFO:CONSOLE(57)] "file:///system/etc/mrg_default_forms/MyGuide/MyGuideBoard/Initial/textlink/res/values-en-rUS/strings.xml", source: file:///android_asset/www/libs/string_replacer.js (57)
I/chromium( 6669): [INFO:CONSOLE(64)] "failed to load : file:///system/etc/mrg_default_forms/MyGuide/MyGuideBoard/Initial/oiscamera/res/values-en/strings.xml", source: file:///android_asset/www/libs/string_replacer.js (64)
,I/chromium( 6669): [INFO:CONSOLE(57)] "file:///system/etc/mrg_default_forms/MyGuide/MyGuideBoard/Initial/oiscamera/res/values-en-rUS/strings.xml", source: file:///android_asset/www/libs/string_replacer.js (57)
I/chromium( 6669): [INFO:CONSOLE(64)] "failed to load : file:///system/etc/mrg_default_forms/MyGuide/MyGuideBoard/Initial/guestmode/res/values-en/strings.xml", source: file:///android_asset/www/libs/string_replacer.js (64)
I/chromium( 6669): [INFO:CONSOLE(57)] "file:///system/etc/mrg_default_forms/MyGuide/MyGuideBoard/Initial/guestmode/res/values-en-rUS/strings.xml", source: file:///android_asset/www/libs/string_replacer.js (57)
I/chromium( 6669): [INFO:CONSOLE(64)] "failed to load : file:///data/user/0/com.lge.formmanager/files/MyGuide_MyGuideBoard_PromotionCard_DualWindow/res/values-en/strings.xml", source: file:///android_asset/www/libs/string_replacer.js (64)
,I/chromium( 6669): [INFO:CONSOLE(57)] "file:///data/user/0/com.lge.formmanager/files/MyGuide_MyGuideBoard_PromotionCard_DualWindow/res/values-en-rUS/strings.xml", source: file:///android_asset/www/libs/string_replacer.js (57)
I/chromium( 6669): [INFO:CONSOLE(64)] "failed to load : file:///data/user/0/com.lge.formmanager/files/MyGuide_MyGuideBoard_PromotionCard_SmartKeyboard/res/values-en/strings.xml", source: file:///android_asset/www/libs/string_replacer.js (64)
I/chromium( 6669): [INFO:CONSOLE(57)] "file:///data/user/0/com.lge.formmanager/files/MyGuide_MyGuideBoard_PromotionCard_SmartKeyboard/res/values-en-rUS/strings.xml", source: file:///android_asset/www/libs/string_replacer.js (57)
I/chromium( 6669): [INFO:CONSOLE(64)] "failed to load : file:///data/user/0/com.lge.formmanager/files/MyGuide_MyGuideBoard_PromotionCard_QuadHD/res/values-en/strings.xml", source: file:///android_asset/www/libs/string_replacer.js (64)
,I/chromium( 6669): [INFO:CONSOLE(57)] "file:///data/user/0/com.lge.formmanager/files/MyGuide_MyGuideBoard_PromotionCard_QuadHD/res/values-en-rUS/strings.xml", source: file:///android_asset/www/libs/string_replacer.js (57)
I/chromium( 6669): [INFO:CONSOLE(64)] "failed to load : file:///data/user/0/com.lge.formmanager/files/MyGuide_MyGuideBoard_PromotionCard_SmartBulletin/res/values-en/strings.xml", source: file:///android_asset/www/libs/string_replacer.js (64)
I/chromium( 6669): [INFO:CONSOLE(57)] "file:///data/user/0/com.lge.formmanager/files/MyGuide_MyGuideBoard_PromotionCard_SmartBulletin/res/values-en-rUS/strings.xml", source: file:///android_asset/www/libs/string_replacer.js (57)
I/chromium( 6669): [INFO:CONSOLE(64)] "failed to load : file:///data/user/0/com.lge.formmanager/files/MyGuide_MyGuideBoard_PromotionCard_QuickCircle/res/values-en/strings.xml", source: file:///android_asset/www/libs/string_replacer.js (64)
,I/chromium( 6669): [INFO:CONSOLE(57)] "file:///data/user/0/com.lge.formmanager/files/MyGuide_MyGuideBoard_PromotionCard_QuickCircle/res/values-en-rUS/strings.xml", source: file:///android_asset/www/libs/string_replacer.js (57)
I/chromium( 6669): [INFO:CONSOLE(64)] "failed to load : file:///system/etc/mrg_default_forms/MyGuide/MyGuideBoard/UserGuideCard/res/values-en/strings.xml", source: file:///android_asset/www/libs/string_replacer.js (64)
I/chromium( 6669): [INFO:CONSOLE(57)] "file:///system/etc/mrg_default_forms/MyGuide/MyGuideBoard/UserGuideCard/res/values-en-rUS/strings.xml", source: file:///android_asset/www/libs/string_replacer.js (57)
I/chromium( 6669): [INFO:CONSOLE(64)] "failed to load : file:///system/etc/mrg_default_forms/MyGuide/MyGuideBoard/UserGuideCard/res/values-en/strings.xml", source: file:///android_asset/www/libs/string_replacer.js (64)
,I/chromium( 6669): [INFO:CONSOLE(57)] "file:///system/etc/mrg_default_forms/MyGuide/MyGuideBoard/UserGuideCard/res/values-en-rUS/strings.xml", source: file:///android_asset/www/libs/string_replacer.js (57)
I/chromium( 6669): [INFO:CONSOLE(64)] "failed to load : file:///system/etc/mrg_default_forms/MyGuide/MyGuideBoard/UserGuideCard/res/values-en/strings.xml", source: file:///android_asset/www/libs/string_replacer.js (64)
I/chromium( 6669): [INFO:CONSOLE(57)] "file:///system/etc/mrg_default_forms/MyGuide/MyGuideBoard/UserGuideCard/res/values-en-rUS/strings.xml", source: file:///android_asset/www/libs/string_replacer.js (57)
I/chromium( 6669): [INFO:CONSOLE(64)] "failed to load : file:///system/etc/mrg_default_forms/MyGuide/MyGuideBoard/UserGuideCard/res/values-en/strings.xml", source: file:///android_asset/www/libs/string_replacer.js (64)
I/chromium( 6669): [INFO:CONSOLE(57)] "file:///system/etc/mrg_default_forms/MyGuide/MyGuideBoard/UserGuideCard/res/values-en-rUS/strings.xml", source: file:///android_asset/www/libs/string_replacer.js (57)
,I/chromium( 6669): [INFO:CONSOLE(64)] "failed to load : file:///system/etc/mrg_default_forms/MyGuide/MyGuideBoard/UserGuideCard/res/values-en/strings.xml", source: file:///android_asset/www/libs/string_replacer.js (64)
I/chromium( 6669): [INFO:CONSOLE(57)] "file:///system/etc/mrg_default_forms/MyGuide/MyGuideBoard/UserGuideCard/res/values-en-rUS/strings.xml", source: file:///android_asset/www/libs/string_replacer.js (57)
I/chromium( 6669): [INFO:CONSOLE(64)] "failed to load : file:///data/user/0/com.lge.formmanager/files/MyGuide_MyGuideBoard_PromotionCard_QuickCircleCase/res/values-en/strings.xml", source: file:///android_asset/www/libs/string_replacer.js (64)
I/chromium( 6669): [INFO:CONSOLE(57)] "file:///data/user/0/com.lge.formmanager/files/MyGuide_MyGuideBoard_PromotionCard_QuickCircleCase/res/values-en-rUS/strings.xml", source: file:///android_asset/www/libs/string_replacer.js (57)
I/chromium( 6669): [INFO:CONSOLE(64)] "failed to load : file:///system/etc/mrg_default_forms/MyGuide/MyGuideBoard/UserGuideCard/res/values-en/strings.xml", source: file:///android_asset/www/libs/string_replacer.js (64)
I/chromium( 6669): [INFO:CONSOLE(57)] "file:///system/etc/mrg_default_forms/MyGuide/MyGuideBoard/UserGuideCard/res/values-en-rUS/strings.xml", source: file:///android_asset/www/libs/string_replacer.js (57)
I/chromium( 6669): [INFO:CONSOLE(64)] "failed to load : file:///system/etc/mrg_default_forms/MyGuide/MyGuideBoard/UserGuideCard/res/values-en/strings.xml", source: file:///android_asset/www/libs/string_replacer.js (64)
I/chromium( 6669): [INFO:CONSOLE(57)] "file:///system/etc/mrg_default_forms/MyGuide/MyGuideBoard/UserGuideCard/res/values-en-rUS/strings.xml", source: file:///android_asset/www/libs/string_replacer.js (57)
,I/chromium( 6669): [INFO:CONSOLE(64)] "failed to load : file:///system/etc/mrg_default_forms/MyGuide/MyGuideBoard/UserGuideCard/res/values-en/strings.xml", source: file:///android_asset/www/libs/string_replacer.js (64)
,I/chromium( 6669): [INFO:CONSOLE(57)] "file:///system/etc/mrg_default_forms/MyGuide/MyGuideBoard/UserGuideCard/res/values-en-rUS/strings.xml", source: file:///android_asset/www/libs/string_replacer.js (57)
I/chromium( 6669): [INFO:CONSOLE(64)] "failed to load : file:///system/etc/mrg_default_forms/MyGuide/MyGuideBoard/UserGuideCard/res/values-en/strings.xml", source: file:///android_asset/www/libs/string_replacer.js (64)
,I/chromium( 6669): [INFO:CONSOLE(57)] "file:///system/etc/mrg_default_forms/MyGuide/MyGuideBoard/UserGuideCard/res/values-en-rUS/strings.xml", source: file:///android_asset/www/libs/string_replacer.js (57)
I/chromium( 6669): [INFO:CONSOLE(64)] "failed to load : file:///system/etc/mrg_default_forms/MyGuide/MyGuideBoard/UserGuideCard/res/values-en/strings.xml", source: file:///android_asset/www/libs/string_replacer.js (64)
I/chromium( 6669): [INFO:CONSOLE(57)] "file:///system/etc/mrg_default_forms/MyGuide/MyGuideBoard/UserGuideCard/res/values-en-rUS/strings.xml", source: file:///android_asset/www/libs/string_replacer.js (57)
I/chromium( 6669): [INFO:CONSOLE(64)] "failed to load : file:///system/etc/mrg_default_forms/MyGuide/MyGuideBoard/UserGuideCard/res/values-en/strings.xml", source: file:///android_asset/www/libs/string_replacer.js (64)
,I/chromium( 6669): [INFO:CONSOLE(57)] "file:///system/etc/mrg_default_forms/MyGuide/MyGuideBoard/UserGuideCard/res/values-en-rUS/strings.xml", source: file:///android_asset/www/libs/string_replacer.js (57)
I/chromium( 6669): [INFO:CONSOLE(64)] "failed to load : file:///system/etc/mrg_default_forms/MyGuide/MyGuideBoard/UserGuideCard/res/values-en/strings.xml", source: file:///android_asset/www/libs/string_replacer.js (64)
I/chromium( 6669): [INFO:CONSOLE(57)] "file:///system/etc/mrg_default_forms/MyGuide/MyGuideBoard/UserGuideCard/res/values-en-rUS/strings.xml", source: file:///android_asset/www/libs/string_replacer.js (57)
I/chromium( 6669): [INFO:CONSOLE(64)] "failed to load : file:///system/etc/mrg_default_forms/MyGuide/MyGuideBoard/UserGuideCard/res/values-en/strings.xml", source: file:///android_asset/www/libs/string_replacer.js (64)
I/chromium( 6669): [INFO:CONSOLE(57)] "file:///system/etc/mrg_default_forms/MyGuide/MyGuideBoard/UserGuideCard/res/values-en-rUS/strings.xml", source: file:///android_asset/www/libs/string_replacer.js (57)
,I/chromium( 6669): [INFO:CONSOLE(64)] "failed to load : file:///system/etc/mrg_default_forms/MyGuide/MyGuideBoard/UserGuideCard/res/values-en/strings.xml", source: file:///android_asset/www/libs/string_replacer.js (64)
I/chromium( 6669): [INFO:CONSOLE(57)] "file:///system/etc/mrg_default_forms/MyGuide/MyGuideBoard/UserGuideCard/res/values-en-rUS/strings.xml", source: file:///android_asset/www/libs/string_replacer.js (57)
I/chromium( 6669): [INFO:CONSOLE(64)] "failed to load : file:///system/etc/mrg_default_forms/MyGuide/MyGuideBoard/UserGuideCard/res/values-en/strings.xml", source: file:///android_asset/www/libs/string_replacer.js (64)
I/chromium( 6669): [INFO:CONSOLE(57)] "file:///system/etc/mrg_default_forms/MyGuide/MyGuideBoard/UserGuideCard/res/values-en-rUS/strings.xml", source: file:///android_asset/www/libs/string_replacer.js (57)
I/chromium( 6669): [INFO:CONSOLE(64)] "failed to load : file:///system/etc/mrg_default_forms/MyGuide/MyGuideBoard/UserGuideCard/res/values-en/strings.xml", source: file:///android_asset/www/libs/string_replacer.js (64)
,I/chromium( 6669): [INFO:CONSOLE(57)] "file:///system/etc/mrg_default_forms/MyGuide/MyGuideBoard/UserGuideCard/res/values-en-rUS/strings.xml", source: file:///android_asset/www/libs/string_replacer.js (57)
,I/chromium( 6669): [INFO:CONSOLE(64)] "failed to load : file:///system/etc/mrg_default_forms/MyGuide/MyGuideBoard/UserGuideCard/res/values-en/strings.xml", source: file:///android_asset/www/libs/string_replacer.js (64)
I/chromium( 6669): [INFO:CONSOLE(57)] "file:///system/etc/mrg_default_forms/MyGuide/MyGuideBoard/UserGuideCard/res/values-en-rUS/strings.xml", source: file:///android_asset/www/libs/string_replacer.js (57)
I/chromium( 6669): [INFO:CONSOLE(177)] "url('res/drawable/dyk_textlink_bg.jpg') -> url(file:///system/etc/mrg_default_forms/MyGuide/MyGuideBoard/Initial/textlink/res/drawable/dyk_textlink_bg.jpg)", source: file:///android_asset/www/libs/form_converter.js (177)
,I/chromium( 6669): [INFO:CONSOLE(177)] "url('res/drawable/dyk_oiscamera_bg.jpg') -> url(file:///system/etc/mrg_default_forms/MyGuide/MyGuideBoard/Initial/oiscamera/res/drawable/dyk_oiscamera_bg.jpg)", source: file:///android_asset/www/libs/form_converter.js (177)
,I/chromium( 6669): [INFO:CONSOLE(177)] "url('res/drawable/ic_setting.png') -> url(file:///system/etc/mrg_default_forms/MyGuide/MyGuideBoard/Initial/oiscamera/res/drawable/ic_setting.png)", source: file:///android_asset/www/libs/form_converter.js (177)
I/chromium( 6669): [INFO:CONSOLE(177)] "url('res/drawable/dyk_guestmode_bg.jpg') -> url(file:///system/etc/mrg_default_forms/MyGuide/MyGuideBoard/Initial/guestmode/res/drawable/dyk_guestmode_bg.jpg)", source: file:///android_asset/www/libs/form_converter.js (177)
,I/chromium( 6669): [INFO:CONSOLE(177)] "url('res/drawable/ic_launcher_camera.png') -> url(file:///system/etc/mrg_default_forms/MyGuide/MyGuideBoard/Initial/guestmode/res/drawable/ic_launcher_camera.png)", source: file:///android_asset/www/libs/form_converter.js (177)
I/chromium( 6669): [INFO:CONSOLE(177)] "url('res/drawable/dyk_dualwindow_bg.jpg') -> url(file:///data/user/0/com.lge.formmanager/files/MyGuide_MyGuideBoard_PromotionCard_DualWindow/res/drawable/dyk_dualwindow_bg.jpg)", source: file:///android_asset/www/libs/form_converter.js (177)
,I/chromium( 6669): [INFO:CONSOLE(177)] "url('res/drawable/dyk_smartkeyboard_bg.jpg') -> url(file:///data/user/0/com.lge.formmanager/files/MyGuide_MyGuideBoard_PromotionCard_SmartKeyboard/res/drawable/dyk_smartkeyboard_bg.jpg)", source: file:///android_asset/www/libs/form_converter.js (177)
,I/chromium( 6669): [INFO:CONSOLE(177)] "url('res/drawable/dyk_quadhd_bg.jpg') -> url(file:///data/user/0/com.lge.formmanager/files/MyGuide_MyGuideBoard_PromotionCard_QuadHD/res/drawable/dyk_quadhd_bg.jpg)", source: file:///android_asset/www/libs/form_converter.js (177)
,I/chromium( 6669): [INFO:CONSOLE(177)] "url('res/drawable/dyk_smartbulletin_bg.jpg') -> url(file:///data/user/0/com.lge.formmanager/files/MyGuide_MyGuideBoard_PromotionCard_SmartBulletin/res/drawable/dyk_smartbulletin_bg.jpg)", source: file:///android_asset/www/libs/form_converter.js (177)
,I/chromium( 6669): [INFO:CONSOLE(177)] "url('res/drawable/dyk_quickcircle_bg.jpg') -> url(file:///data/user/0/com.lge.formmanager/files/MyGuide_MyGuideBoard_PromotionCard_QuickCircle/res/drawable/dyk_quickcircle_bg.jpg)", source: file:///android_asset/www/libs/form_converter.js (177)
,I/chromium( 6669): [INFO:CONSOLE(177)] "url(res/drawable/keyboard_move_cursor.jpg) -> url(file:///system/etc/mrg_default_forms/MyGuide/MyGuideBoard/UserGuideCard/res/drawable/keyboard_move_cursor.jpg)", source: file:///android_asset/www/libs/form_converter.js (177)
I/chromium( 6669): [INFO:CONSOLE(177)] "url(res/drawable/ic_null.png) -> url(file:///system/etc/mrg_default_forms/MyGuide/MyGuideBoard/UserGuideCard/res/drawable/ic_null.png)", source: file:///android_asset/www/libs/form_converter.js (177)
,I/chromium( 6669): [INFO:CONSOLE(177)] "url(res/drawable/keyboard_suggestion.jpg) -> url(file:///system/etc/mrg_default_forms/MyGuide/MyGuideBoard/UserGuideCard/res/drawable/keyboard_suggestion.jpg)", source: file:///android_asset/www/libs/form_converter.js (177)
I/chromium( 6669): [INFO:CONSOLE(177)] "url(res/drawable/ic_null.png) -> url(file:///system/etc/mrg_default_forms/MyGuide/MyGuideBoard/UserGuideCard/res/drawable/ic_null.png)", source: file:///android_asset/www/libs/form_converter.js (177)
,I/chromium( 6669): [INFO:CONSOLE(177)] "url(res/drawable/dual_window.jpg) -> url(file:///system/etc/mrg_default_forms/MyGuide/MyGuideBoard/UserGuideCard/res/drawable/dual_window.jpg)", source: file:///android_asset/www/libs/form_converter.js (177)
,I/chromium( 6669): [INFO:CONSOLE(177)] "url(res/drawable/ic_null.png) -> url(file:///system/etc/mrg_default_forms/MyGuide/MyGuideBoard/UserGuideCard/res/drawable/ic_null.png)", source: file:///android_asset/www/libs/form_converter.js (177)
,I/chromium( 6669): [INFO:CONSOLE(177)] "url(res/drawable/camera_voice_shutter.jpg) -> url(file:///system/etc/mrg_default_forms/MyGuide/MyGuideBoard/UserGuideCard/res/drawable/camera_voice_shutter.jpg)", source: file:///android_asset/www/libs/form_converter.js (177)
I/chromium( 6669): [INFO:CONSOLE(177)] "url(res/drawable/ic_null.png) -> url(file:///system/etc/mrg_default_forms/MyGuide/MyGuideBoard/UserGuideCard/res/drawable/ic_null.png)", source: file:///android_asset/www/libs/form_converter.js (177)
I/chromium( 6669): [INFO:CONSOLE(177)] "url(res/drawable/camera_switch.jpg) -> url(file:///system/etc/mrg_default_forms/MyGuide/MyGuideBoard/UserGuideCard/res/drawable/camera_switch.jpg)", source: file:///android_asset/www/libs/form_converter.js (177)
I/chromium( 6669): [INFO:CONSOLE(177)] "url(res/drawable/ic_launcher_camera.png) -> url(file:///system/etc/mrg_default_forms/MyGuide/MyGuideBoard/UserGuideCard/res/drawable/ic_launcher_camera.png)", source: file:///android_asset/www/libs/form_converter.js (177)
,I/chromium( 6669): [INFO:CONSOLE(177)] "url('res/drawable/dyk_quickcirclecase_bg.jpg') -> url(file:///data/user/0/com.lge.formmanager/files/MyGuide_MyGuideBoard_PromotionCard_QuickCircleCase/res/drawable/dyk_quickcirclecase_bg.jpg)", source: file:///android_asset/www/libs/form_converter.js (177)
I/chromium( 6669): [INFO:CONSOLE(177)] "url(res/drawable/gesture_call.jpg) -> url(file:///system/etc/mrg_default_forms/MyGuide/MyGuideBoard/UserGuideCard/res/drawable/gesture_call.jpg)", source: file:///android_asset/www/libs/form_converter.js (177)
,I/chromium( 6669): [INFO:CONSOLE(177)] "url(res/drawable/setting.png) -> url(file:///system/etc/mrg_default_forms/MyGuide/MyGuideBoard/UserGuideCard/res/drawable/setting.png)", source: file:///android_asset/www/libs/form_converter.js (177)
I/chromium( 6669): [INFO:CONSOLE(177)] "url(res/drawable/camera_gestureshot.jpg) -> url(file:///system/etc/mrg_default_forms/MyGuide/MyGuideBoard/UserGuideCard/res/drawable/camera_gestureshot.jpg)", source: file:///android_asset/www/libs/form_converter.js (177)
I/chromium( 6669): [INFO:CONSOLE(177)] "url(res/drawable/ic_launcher_camera.png) -> url(file:///system/etc/mrg_default_forms/MyGuide/MyGuideBoard/UserGuideCard/res/drawable/ic_launcher_camera.png)", source: file:///android_asset/www/libs/form_converter.js (177)
,I/chromium( 6669): [INFO:CONSOLE(177)] "url(res/drawable/home_cleanview.jpg) -> url(file:///system/etc/mrg_default_forms/MyGuide/MyGuideBoard/UserGuideCard/res/drawable/home_cleanview.jpg)", source: file:///android_asset/www/libs/form_converter.js (177)
I/chromium( 6669): [INFO:CONSOLE(177)] "url(res/drawable/ic_null.png) -> url(file:///system/etc/mrg_default_forms/MyGuide/MyGuideBoard/UserGuideCard/res/drawable/ic_null.png)", source: file:///android_asset/www/libs/form_converter.js (177)
,I/chromium( 6669): [INFO:CONSOLE(177)] "url(res/drawable/keyboard_split.jpg) -> url(file:///system/etc/mrg_default_forms/MyGuide/MyGuideBoard/UserGuideCard/res/drawable/keyboard_split.jpg)", source: file:///android_asset/www/libs/form_converter.js (177)
I/chromium( 6669): [INFO:CONSOLE(177)] "url(res/drawable/setting.png) -> url(file:///system/etc/mrg_default_forms/MyGuide/MyGuideBoard/UserGuideCard/res/drawable/setting.png)", source: file:///android_asset/www/libs/form_converter.js (177)
I/chromium( 6669): [INFO:CONSOLE(177)] "url(res/drawable/internet.jpg) -> url(file:///system/etc/mrg_default_forms/MyGuide/MyGuideBoard/UserGuideCard/res/drawable/internet.jpg)", source: file:///android_asset/www/libs/form_converter.js (177)
,I/chromium( 6669): [INFO:CONSOLE(177)] "url(res/drawable/ic_internet.png) -> url(file:///system/etc/mrg_default_forms/MyGuide/MyGuideBoard/UserGuideCard/res/drawable/ic_internet.png)", source: file:///android_asset/www/libs/form_converter.js (177)
I/chromium( 6669): [INFO:CONSOLE(177)] "url(res/drawable/keyboard_path_input.jpg) -> url(file:///system/etc/mrg_default_forms/MyGuide/MyGuideBoard/UserGuideCard/res/drawable/keyboard_path_input.jpg)", source: file:///android_asset/www/libs/form_converter.js (177)
I/chromium( 6669): [INFO:CONSOLE(177)] "url(res/drawable/setting.png) -> url(file:///system/etc/mrg_default_forms/MyGuide/MyGuideBoard/UserGuideCard/res/drawable/setting.png)", source: file:///android_asset/www/libs/form_converter.js (177)
I/chromium( 6669): [INFO:CONSOLE(177)] "url(res/drawable/camera_magic_focus.jpg) -> url(file:///system/etc/mrg_default_forms/MyGuide/MyGuideBoard/UserGuideCard/res/drawable/camera_magic_focus.jpg)", source: file:///android_asset/www/libs/form_converter.js (177)
,I/chromium( 6669): [INFO:CONSOLE(177)] "url(res/drawable/ic_launcher_camera.png) -> url(file:///system/etc/mrg_default_forms/MyGuide/MyGuideBoard/UserGuideCard/res/drawable/ic_launcher_camera.png)", source: file:///android_asset/www/libs/form_converter.js (177)
I/chromium( 6669): [INFO:CONSOLE(177)] "url(res/drawable/keyboard_onehand.jpg) -> url(file:///system/etc/mrg_default_forms/MyGuide/MyGuideBoard/UserGuideCard/res/drawable/keyboard_onehand.jpg)", source: file:///android_asset/www/libs/form_converter.js (177)
I/chromium( 6669): [INFO:CONSOLE(177)] "url(res/drawable/setting.png) -> url(file:///system/etc/mrg_default_forms/MyGuide/MyGuideBoard/UserGuideCard/res/drawable/setting.png)", source: file:///android_asset/www/libs/form_converter.js (177)
I/chromium( 6669): [INFO:CONSOLE(177)] "url(res/drawable/gesture_call.jpg) -> url(file:///system/etc/mrg_default_forms/MyGuide/MyGuideBoard/UserGuideCard/res/drawable/gesture_call.jpg)", source: file:///android_asset/www/libs/form_converter.js (177)
,I/chromium( 6669): [INFO:CONSOLE(177)] "url(res/drawable/setting.png) -> url(file:///system/etc/mrg_default_forms/MyGuide/MyGuideBoard/UserGuideCard/res/drawable/setting.png)", source: file:///android_asset/www/libs/form_converter.js (177)
I/chromium( 6669): [INFO:CONSOLE(177)] "url(res/drawable/home_iconchange.jpg) -> url(file:///system/etc/mrg_default_forms/MyGuide/MyGuideBoard/UserGuideCard/res/drawable/home_iconchange.jpg)", source: file:///android_asset/www/libs/form_converter.js (177)
I/chromium( 6669): [INFO:CONSOLE(177)] "url(res/drawable/ic_null.png) -> url(file:///system/etc/mrg_default_forms/MyGuide/MyGuideBoard/UserGuideCard/res/drawable/ic_null.png)", source: file:///android_asset/www/libs/form_converter.js (177)
I/chromium( 6669): [INFO:CONSOLE(177)] "url(res/drawable/camera_panorama.jpg) -> url(file:///system/etc/mrg_default_forms/MyGuide/MyGuideBoard/UserGuideCard/res/drawable/camera_panorama.jpg)", source: file:///android_asset/www/libs/form_converter.js (177)
I/chromium( 6669): [INFO:CONSOLE(177)] "url(res/drawable/ic_launcher_camera.png) -> url(file:///system/etc/mrg_default_forms/MyGuide/MyGuideBoard/UserGuideCard/res/drawable/ic_launcher_camera.png)", source: file:///android_asset/www/libs/form_converter.js (177)
,I/chromium( 6669): [INFO:CONSOLE(177)] "url(res/drawable/navigation.jpg) -> url(file:///system/etc/mrg_default_forms/MyGuide/MyGuideBoard/UserGuideCard/res/drawable/navigation.jpg)", source: file:///android_asset/www/libs/form_converter.js (177)
I/chromium( 6669): [INFO:CONSOLE(177)] "url(res/drawable/ic_null.png) -> url(file:///system/etc/mrg_default_forms/MyGuide/MyGuideBoard/UserGuideCard/res/drawable/ic_null.png)", source: file:///android_asset/www/libs/form_converter.js (177)
I/chromium( 6669): [INFO:CONSOLE(95)] "attachInitialCard-----------------------", source: file:///android_asset/www/js/controlCards.js (95)
I/chromium( 6669): [INFO:CONSOLE(176)] "attach remaining card -------------", source: file:///android_asset/www/js/controlCards.js (176)
,I/chromium( 6669): [INFO:CONSOLE(180)] "calculate rotation degree-------------------", source: file:///android_asset/www/js/animation.js (180)
,I/chromium( 6669): [INFO:CONSOLE(111)] "accordion collapse effect ----------------------------- ", source: file:///android_asset/www/js/animation.js (111)
,I/chromium( 6669): [INFO:CONSOLE(602)] "exportDYKHTML----------------", source: file:///android_asset/www/js/controlCards.js (602)
D/DYKBoard( 6669): exportDYKHTML(), GBoard refresh = 1
,D/DYKBoard( 6669): Out File Path =/data/data/com.lge.doyouknow/files/www/dykContainer.html
W/ScreenOrientationListener( 6669): Removing an inexistent observer!
I/jxcore-log( 6107): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6107): 
,I/jxcore-log( 6107): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6107): 
,D/sensors_hal_Time( 1029): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1029): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1029): tsOffsetIs: Apps: 814097135317; DSPS: 26817752; Offset : -4327602987
,I/jxcore-log( 6107): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6107): 
,I/jxcore-log( 6107): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6107): 
,I/jxcore-log( 6107): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6107): 
,I/jxcore-log( 6107): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6107): 
,I/[SystemUI]TimeTickManager( 1451): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1451): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1451): called onTimeUpdated()
I/[SystemUI]Clock( 1451): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1451): called onTimeUpdated()
I/[SystemUI]DateView( 1451): called onTimeUpdated()
I/[SystemUI]DateView( 1451): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1451): handleTimeUpdate
D/sensors_hal_Time( 1029): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1029): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1029): tsOffsetIs: Apps: 834099162132; DSPS: 27473179; Offset : -4327621006
,I/jxcore-log( 6107): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6107): 
,I/jxcore-log( 6107): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6107): 
,I/jxcore-log( 6107): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6107): 
,I/jxcore-log( 6107): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6107): 
,D/sensors_hal_Time( 1029): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1029): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1029): tsOffsetIs: Apps: 854102052020; DSPS: 28128633; Offset : -4327599562
,I/jxcore-log( 6107): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6107): 
,I/jxcore-log( 6107): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6107): 
,I/jxcore-log( 6107): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6107): 
,I/jxcore-log( 6107): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6107): 
,D/sensors_hal_Time( 1029): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1029): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1029): tsOffsetIs: Apps: 874104268731; DSPS: 28784066; Offset : -4327610661
,I/jxcore-log( 6107): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6107): 
,I/jxcore-log( 6107): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6107): 
,I/jxcore-log( 6107): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6107): 
,I/jxcore-log( 6107): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6107): 
,I/[SystemUI]TimeTickManager( 1451): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1451): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1451): called onTimeUpdated()
I/[SystemUI]Clock( 1451): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1451): called onTimeUpdated()
I/[SystemUI]DateView( 1451): called onTimeUpdated()
I/[SystemUI]DateView( 1451): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1451): handleTimeUpdate
D/sensors_hal_Time( 1029): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1029): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1029): tsOffsetIs: Apps: 894106194454; DSPS: 29439489; Offset : -4327607493
,I/jxcore-log( 6107): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6107): 
,I/jxcore-log( 6107): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6107): 
,I/jxcore-log( 6107): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6107): 
,I/jxcore-log( 6107): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6107): 
,D/sensors_hal_Time( 1029): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1029): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1029): tsOffsetIs: Apps: 914108083873; DSPS: 30094911; Offset : -4327610216
,I/jxcore-log( 6107): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6107): 
,I/jxcore-log( 6107): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6107): 
,I/jxcore-log( 6107): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6107): 
,I/jxcore-log( 6107): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6107): 
,D/sensors_hal_Time( 1029): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1029): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1029): tsOffsetIs: Apps: 934110887043; DSPS: 30750363; Offset : -4327614871
,I/jxcore-log( 6107): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6107): 
,I/jxcore-log( 6107): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6107): 
,I/jxcore-log( 6107): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6107): 
,I/jxcore-log( 6107): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6107): 
,I/[SystemUI]TimeTickManager( 1451): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1451): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1451): called onTimeUpdated()
I/[SystemUI]Clock( 1451): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1451): called onTimeUpdated()
I/[SystemUI]DateView( 1451): called onTimeUpdated()
I/[SystemUI]DateView( 1451): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1451): handleTimeUpdate
,V/GLSActivity( 2108): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2108): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 2108): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2108): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 2108): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2108): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1029): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1029): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1029): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1029): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1029): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1393): onNotificationPosted
,D/SmartCoverUpdateMonitor( 1393): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1393): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1393): handleNotificationPosted(true)
D/QuickCircle( 1393): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1393): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1393): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1393): post do just update job
D/LgeQuickCoverNotificationData( 1393): showAll4
D/LgeQuickCoverNotificationData( 1393): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1393): showAll() ID : 915,0|com.lge.concierge|915|null|10017
D/LgeQuickCoverNotificationData( 1393): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
D/LgeQuickCoverNotificationData( 1393): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
E/LgeQuickCoverOverlayWindow( 1393): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1393): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1393): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1393): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1393): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1393): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1393): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1393): [native noti] inex =  3
D/LgeQuickCoverNotificationData( 1393): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1393): updateNotificationData: count=4
,D/QuickStatusbarLayout( 1393): Notification difference=198
D/QuickStatusbarLayout( 1393): child = android.widget.LinearLayout{156a1e25 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
W/GLSActivity( 2108): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2108): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2108): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2108): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2108): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2108): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2108): 	at android.os.Binder.execTransact(Binder.java:446)
,E/PlayEventLogger( 4896): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 4896): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 4896): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/PlayEventLogger( 4896): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 4896): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/PlayEventLogger( 4896): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 4896): 	at android.os.Binder.execTransact(Binder.java:446)
W/System  ( 4896): Ignoring header User-Agent because its value was null.
,D/libc-netbsd(  309): default dns: query_ipv6=0, query_ipv4=0
D/DSQN    ( 1029): DNSproblemNotiEnabled is disabled ignore DNS fail CB
I/art     ( 1029): Explicit concurrent mark sweep GC freed 21433(960KB) AllocSpace objects, 2(288KB) LOS objects, 33% free, 44MB/66MB, paused 2.081ms total 129.244ms
,D/sensors_hal_Time( 1029): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1029): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1029): tsOffsetIs: Apps: 954112781515; DSPS: 31405785; Offset : -4327612333
,I/jxcore-log( 6107): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6107): 
,I/jxcore-log( 6107): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6107): 
,I/jxcore-log( 6107): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6107): 
,I/jxcore-log( 6107): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6107): 
,D/sensors_hal_Time( 1029): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1029): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1029): tsOffsetIs: Apps: 974114675413; DSPS: 32061207; Offset : -4327610447
,I/jxcore-log( 6107): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6107): 
,I/jxcore-log( 6107): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6107): 
,I/jxcore-log( 6107): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6107): 
,I/jxcore-log( 6107): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6107): 
,D/sensors_hal_Time( 1029): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1029): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1029): tsOffsetIs: Apps: 994116887436; DSPS: 32716639; Offset : -4327595872
,I/jxcore-log( 6107): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6107): 
,I/jxcore-log( 6107): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6107): 
,I/jxcore-log( 6107): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6107): 
,I/jxcore-log( 6107): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6107): 
,I/[SystemUI]TimeTickManager( 1451): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1451): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1451): called onTimeUpdated()
I/[SystemUI]Clock( 1451): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1451): called onTimeUpdated()
I/[SystemUI]DateView( 1451): called onTimeUpdated()
I/[SystemUI]DateView( 1451): called onTimeUpdated()
,D/KeyguardUpdateMonitor( 1451): handleTimeUpdate
D/sensors_hal_Time( 1029): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1029): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1029): tsOffsetIs: Apps: 1014118814356; DSPS: 33372063; Offset : -4327622102
,I/jxcore-log( 6107): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6107): ,
,I/jxcore-log( 6107): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6107): 
,I/jxcore-log( 6107): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6107): 
,I/jxcore-log( 6107): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6107): 
,D/sensors_hal_Time( 1029): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1029): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1029): tsOffsetIs: Apps: 1034121086068; DSPS: 34027497; Offset : -4327608613
,I/jxcore-log( 6107): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6107): 
,I/jxcore-log( 6107): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6107): 
,I/jxcore-log( 6107): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6107): 
,I/jxcore-log( 6107): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6107): 
,D/sensors_hal_Time( 1029): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1029): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1029): tsOffsetIs: Apps: 1054123351788; DSPS: 34682931; Offset : -4327601090
,I/jxcore-log( 6107): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6107): 
,I/jxcore-log( 6107): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6107): 
,D/PowerManagerServiceEx( 1029): acquireWakeLockInternal: lock=231167151, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1029
,V/AlarmManager( 1029): ELAPSED_WAKEUP set : Alarm{2c9fb798 type 2 when 1064110 com.android.bluetooth} when 1064110
,W/bt-smp  ( 6189): Key(LSB ~ MSB) = 0a 3c a6 fe eb 17 6a 79 a6 1f 0a 0b f9 50 a0 5f 
W/bt-smp  ( 6189): Plain text(LSB ~ MSB) = a7 f2 7e 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 6189): Encrypted text(LSB ~ MSB) = 38 5c cc 25 89 1c 1e 4b bb b1 b3 52 a1 18 9f 27 
W/bt-btm  ( 6189): Stopping oneshot timer
D/[Concierge]Service( 2611): onStartCommand(). Type : 9
,D/PowerManagerServiceEx( 1029): releaseWakeLockInternal: lock=231167151 [*alarm*], flags=0x0
,I/jxcore-log( 6107): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6107): 
,I/jxcore-log( 6107): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6107): 
,I/[SystemUI]TimeTickManager( 1451): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1451): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1451): called onTimeUpdated()
I/[SystemUI]Clock( 1451): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1451): called onTimeUpdated()
I/[SystemUI]DateView( 1451): called onTimeUpdated()
I/[SystemUI]DateView( 1451): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1451): handleTimeUpdate
,D/sensors_hal_Time( 1029): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1029): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1029): tsOffsetIs: Apps: 1074132029698; DSPS: 35338576; Offset : -4327620976
,I/jxcore-log( 6107): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6107): 
,I/jxcore-log( 6107): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6107): 
,I/jxcore-log( 6107): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6107): 
,I/jxcore-log( 6107): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6107): 
,D/sensors_hal_Time( 1029): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1029): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1029): tsOffsetIs: Apps: 1094133948023; DSPS: 35993998; Offset : -4327594559
,I/jxcore-log( 6107): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6107): 
,I/jxcore-log( 6107): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6107): 
,I/jxcore-log( 6107): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6107): 
,I/jxcore-log( 6107): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6107): 
,D/sensors_hal_Time( 1029): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1029): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1029): tsOffsetIs: Apps: 1114135761193; DSPS: 36649418; Offset : -4327612391
,I/jxcore-log( 6107): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6107): 
,I/jxcore-log( 6107): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6107): 
,I/jxcore-log( 6107): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6107): 
,I/jxcore-log( 6107): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6107): 
,I/[SystemUI]TimeTickManager( 1451): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1451): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1451): called onTimeUpdated()
I/[SystemUI]Clock( 1451): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1451): called onTimeUpdated()
I/[SystemUI]DateView( 1451): called onTimeUpdated()
I/[SystemUI]DateView( 1451): called onTimeUpdated()
,D/KeyguardUpdateMonitor( 1451): handleTimeUpdate
,D/sensors_hal_Time( 1029): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1029): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1029): tsOffsetIs: Apps: 1134137882279; DSPS: 37304847; Offset : -4327597018
,I/jxcore-log( 6107): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6107): 
,I/jxcore-log( 6107): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6107): 
,I/jxcore-log( 6107): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6107): 
,I/jxcore-log( 6107): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6107): 
,D/sensors_hal_Time( 1029): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1029): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1029): tsOffsetIs: Apps: 1154140113626; DSPS: 37960280; Offset : -4327593428
,I/jxcore-log( 6107): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6107): 
,I/jxcore-log( 6107): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6107): 
,I/jxcore-log( 6107): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6107): 
,I/jxcore-log( 6107): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6107): 
,D/sensors_hal_Time( 1029): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1029): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1029): tsOffsetIs: Apps: 1174142373566; DSPS: 38615715; Offset : -4327622307
,I/jxcore-log( 6107): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6107): 
,I/jxcore-log( 6107): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6107): 
,I/jxcore-log( 6107): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6107): 
,I/jxcore-log( 6107): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6107): 
,I/[SystemUI]TimeTickManager( 1451): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1451): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1451): called onTimeUpdated()
I/[SystemUI]Clock( 1451): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1451): called onTimeUpdated()
I/[SystemUI]DateView( 1451): called onTimeUpdated()
I/[SystemUI]DateView( 1451): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1451): handleTimeUpdate
D/sensors_hal_Time( 1029): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1029): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1029): tsOffsetIs: Apps: 1194144625277; DSPS: 39271148; Offset : -4327598588
,I/jxcore-log( 6107): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6107): 
,I/jxcore-log( 6107): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6107): 
,I/jxcore-log( 6107): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6107): 
,I/jxcore-log( 6107): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6107): 
,D/sensors_hal_Time( 1029): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1029): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1029): tsOffsetIs: Apps: 1214146874435; DSPS: 39926582; Offset : -4327607314
,I/jxcore-log( 6107): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6107): 
,I/UsageStatsService( 1029): User[0] Flushing usage stats to disk
,I/jxcore-log( 6107): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6107): 
,I/jxcore-log( 6107): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6107): 
,I/jxcore-log( 6107): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6107): 
,D/sensors_hal_Time( 1029): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1029): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1029): tsOffsetIs: Apps: 1234149033490; DSPS: 40582013; Offset : -4327615059
,I/jxcore-log( 6107): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6107): 
,I/jxcore-log( 6107): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6107): 
,I/jxcore-log( 6107): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6107): 
,I/jxcore-log( 6107): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6107): 
,I/[SystemUI]TimeTickManager( 1451): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1451): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1451): called onTimeUpdated()
I/[SystemUI]Clock( 1451): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1451): called onTimeUpdated()
I/[SystemUI]DateView( 1451): called onTimeUpdated()
I/[SystemUI]DateView( 1451): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1451): handleTimeUpdate
V/GLSActivity( 2108): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2108): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 2108): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2108): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 2108): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2108): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1029): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1029): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1029): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1029): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1029): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1393): onNotificationPosted
D/SmartCoverUpdateMonitor( 1393): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1393): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1393): handleNotificationPosted(true)
D/QuickCircle( 1393): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1393): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1393): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1393): post do just update job
D/LgeQuickCoverNotificationData( 1393): showAll4
D/LgeQuickCoverNotificationData( 1393): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1393): showAll() ID : 915,0|com.lge.concierge|915|null|10017
D/LgeQuickCoverNotificationData( 1393): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
D/LgeQuickCoverNotificationData( 1393): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
E/LgeQuickCoverOverlayWindow( 1393): showNotificationWithSetupData: display=false
,D/LgeQuickCoverOverlayWindow( 1393): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1393): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1393): [native noti] inex =  1
,D/LgeQuickCoverNotificationData( 1393): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1393): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1393): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1393): [native noti] inex =  3
D/LgeQuickCoverNotificationData( 1393): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1393): updateNotificationData: count=4
D/QuickStatusbarLayout( 1393): Notification difference=198
D/QuickStatusbarLayout( 1393): child = android.widget.LinearLayout{156a1e25 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
W/GLSActivity( 2108): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2108): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2108): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2108): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2108): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2108): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2108): 	at android.os.Binder.execTransact(Binder.java:446)
,E/PlayEventLogger( 4896): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 4896): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 4896): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/PlayEventLogger( 4896): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 4896): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/PlayEventLogger( 4896): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 4896): 	at android.os.Binder.execTransact(Binder.java:446)
W/System  ( 4896): Ignoring header User-Agent because its value was null.
D/libc-netbsd(  309): default dns: query_ipv6=0, query_ipv4=0
D/DSQN    ( 1029): DNSproblemNotiEnabled is disabled ignore DNS fail CB
D/sensors_hal_Time( 1029): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1029): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1029): tsOffsetIs: Apps: 1254150687858; DSPS: 41237427; Offset : -4327608718
,I/jxcore-log( 6107): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6107): 
,I/jxcore-log( 6107): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6107): 
,I/jxcore-log( 6107): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6107): 
,I/jxcore-log( 6107): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6107): 
,D/sensors_hal_Time( 1029): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1029): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1029): tsOffsetIs: Apps: 1274152714204; DSPS: 41892853; Offset : -4327596532
,I/jxcore-log( 6107): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6107): 
,I/jxcore-log( 6107): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6107): 
,I/jxcore-log( 6107): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6107): 
,I/jxcore-log( 6107): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6107): 
,D/sensors_hal_Time( 1029): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1029): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1029): tsOffsetIs: Apps: 1294154648676; DSPS: 42548277; Offset : -4327615107
,I/jxcore-log( 6107): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6107): 
,I/jxcore-log( 6107): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6107): 
,I/jxcore-log( 6107): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6107): 
,I/jxcore-log( 6107): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6107): 
,I/[SystemUI]TimeTickManager( 1451): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1451): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1451): called onTimeUpdated()
I/[SystemUI]Clock( 1451): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1451): called onTimeUpdated()
I/[SystemUI]DateView( 1451): called onTimeUpdated()
I/[SystemUI]DateView( 1451): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1451): handleTimeUpdate
D/sensors_hal_Time( 1029): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1029): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1029): tsOffsetIs: Apps: 1314156812054; DSPS: 43203708; Offset : -4327618633
,I/jxcore-log( 6107): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6107): 
,I/[SystemUI]LGPowerUI( 1451): onReceive = com.lge.android.intent.action.BATTERYEX
,I/[SystemUI]LGPowerUI( 1451): On Skip Timer : true
D/LEDHandler( 1945): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1945): Battery Level Remaining: 100%
D/LEDHandler( 1945): Battery Temp: 281, mChargingStatus=5, mChargingStop=false
,D/KeyguardUpdateMonitor( 1451): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 281
I/[SystemUI]LGPowerUI( 1451): onReceive = android.intent.action.BATTERY_CHANGED
D/WifiController( 1029): battery changed pluggedType: 2
I/[SystemUI]BatterySaverHandler( 1451): onReceive = android.intent.action.BATTERY_CHANGED
D/HeadsetStateMachine( 6189): Disconnected process message: 10, size: 0
,W/Settings( 1029): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1029): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/LGDMClient( 3924): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.intent.action.BATTERY_CHANGED
D/LGDMClient( 3924): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
I/jxcore-log( 6107): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6107): 
,I/jxcore-log( 6107): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6107): 
,I/jxcore-log( 6107): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6107): 
,D/sensors_hal_Time( 1029): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1029): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1029): tsOffsetIs: Apps: 1334158677514; DSPS: 43859129; Offset : -4327614667
I/jxcore-log( 6107): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6107): 
,I/jxcore-log( 6107): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6107): 
,I/jxcore-log( 6107): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6107): 
,I/jxcore-log( 6107): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6107): 
,D/sensors_hal_Time( 1029): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1029): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1029): tsOffsetIs: Apps: 1354160686987; DSPS: 44514555; Offset : -4327619355
,I/jxcore-log( 6107): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6107): 
,D/PowerManagerServiceEx( 1029): acquireWakeLockInternal: lock=231167151, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1029
,V/AlarmManager( 1029): ELAPSED_WAKEUP set : Alarm{18fe70ba type 2 when 1231551 com.google.android.gms} when 1231551
,D/[Concierge]Service( 2611): onStartCommand(). Type : 9
,D/libc-netbsd(  309): default dns: query_ipv6=0, query_ipv4=0
,D/DSQN    ( 1029): DNSproblemNotiEnabled is disabled ignore DNS fail CB
,D/PowerManagerServiceEx( 1029): releaseWakeLockInternal: lock=231167151 [*alarm*], flags=0x0
I/jxcore-log( 6107): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6107): 
,I/jxcore-log( 6107): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6107): 
,I/jxcore-log( 6107): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6107): 
,I/[SystemUI]TimeTickManager( 1451): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1451): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1451): called onTimeUpdated()
I/[SystemUI]Clock( 1451): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1451): called onTimeUpdated()
I/[SystemUI]DateView( 1451): called onTimeUpdated()
I/[SystemUI]DateView( 1451): called onTimeUpdated()
,D/KeyguardUpdateMonitor( 1451): handleTimeUpdate
D/sensors_hal_Time( 1029): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1029): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1029): tsOffsetIs: Apps: 1374162809323; DSPS: 45169984; Offset : -4327602940
,I/jxcore-log( 6107): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6107): 
,I/jxcore-log( 6107): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6107): 
,I/jxcore-log( 6107): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6107): 
,I/jxcore-log( 6107): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6107): 
,D/sensors_hal_Time( 1029): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1029): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1029): tsOffsetIs: Apps: 1394164977388; DSPS: 45825415; Offset : -4327601571
,I/jxcore-log( 6107): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6107): 
,I/jxcore-log( 6107): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6107): 
,I/jxcore-log( 6107): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6107): 
,I/jxcore-log( 6107): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6107): 
,D/sensors_hal_Time( 1029): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1029): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1029): tsOffsetIs: Apps: 1414167148057; DSPS: 46480846; Offset : -4327597624
,I/jxcore-log( 6107): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6107): 
,I/jxcore-log( 6107): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6107): 
,I/jxcore-log( 6107): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6107): 
,I/jxcore-log( 6107): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6107): 
,I/[SystemUI]TimeTickManager( 1451): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1451): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1451): called onTimeUpdated()
I/[SystemUI]Clock( 1451): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1451): called onTimeUpdated()
I/[SystemUI]DateView( 1451): called onTimeUpdated()
I/[SystemUI]DateView( 1451): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1451): handleTimeUpdate
D/sensors_hal_Time( 1029): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1029): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1029): tsOffsetIs: Apps: 1434169493154; DSPS: 47136283; Offset : -4327602407
,I/jxcore-log( 6107): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6107): 
,I/jxcore-log( 6107): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6107): 
,I/jxcore-log( 6107): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6107): 
,I/jxcore-log( 6107): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6107): 
,D/sensors_hal_Time( 1029): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1029): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1029): tsOffsetIs: Apps: 1454172412991; DSPS: 47791739; Offset : -4327612310
,I/jxcore-log( 6107): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6107): 
,I/jxcore-log( 6107): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6107): 
,I/jxcore-log( 6107): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6107): 
,I/jxcore-log( 6107): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6107): 
,D/sensors_hal_Time( 1029): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1029): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1029): tsOffsetIs: Apps: 1474174576055; DSPS: 48447170; Offset : -4327615811
,I/jxcore-log( 6107): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6107): 
,I/jxcore-log( 6107): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6107): 
,I/jxcore-log( 6107): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6107): 
,I/jxcore-log( 6107): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6107): 
,I/[SystemUI]TimeTickManager( 1451): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1451): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1451): called onTimeUpdated()
I/[SystemUI]Clock( 1451): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1451): called onTimeUpdated()
I/[SystemUI]DateView( 1451): called onTimeUpdated()
I/[SystemUI]DateView( 1451): called onTimeUpdated()
,D/KeyguardUpdateMonitor( 1451): handleTimeUpdate
D/sensors_hal_Time( 1029): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1029): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1029): tsOffsetIs: Apps: 1494176185526; DSPS: 49102582; Offset : -4327593462
,I/jxcore-log( 6107): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6107): 
,I/jxcore-log( 6107): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6107): 
,I/jxcore-log( 6107): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6107): 
,I/jxcore-log( 6107): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6107): 
,D/sensors_hal_Time( 1029): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1029): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1029): tsOffsetIs: Apps: 1514178322915; DSPS: 49758013; Offset : -4327622638
,I/jxcore-log( 6107): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6107): 
,I/jxcore-log( 6107): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6107): 
,I/jxcore-log( 6107): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6107): 
,I/jxcore-log( 6107): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6107): 
,D/sensors_hal_Time( 1029): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1029): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1029): tsOffsetIs: Apps: 1534180614002; DSPS: 50413448; Offset : -4327620239
,I/jxcore-log( 6107): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6107): 
,I/jxcore-log( 6107): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6107): 
,I/jxcore-log( 6107): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6107): 
,I/jxcore-log( 6107): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6107): 
,I/[SystemUI]TimeTickManager( 1451): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1451): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1451): called onTimeUpdated()
I/[SystemUI]Clock( 1451): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1451): called onTimeUpdated()
I/[SystemUI]DateView( 1451): called onTimeUpdated()
I/[SystemUI]DateView( 1451): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1451): handleTimeUpdate
V/GLSActivity( 2108): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2108): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 2108): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2108): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2108): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2108): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1029): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1029): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1029): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1029): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1029): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1393): onNotificationPosted
,D/sensors_hal_Time( 1029): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1029): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1029): tsOffsetIs: Apps: 1554187303316; DSPS: 51069027; Offset : -4327612843
D/SmartCoverUpdateMonitor( 1393): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1393): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1393): handleNotificationPosted(true)
D/QuickCircle( 1393): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1393): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1393): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1393): post do just update job
D/LgeQuickCoverNotificationData( 1393): showAll4
D/LgeQuickCoverNotificationData( 1393): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1393): showAll() ID : 915,0|com.lge.concierge|915|null|10017
D/LgeQuickCoverNotificationData( 1393): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
D/LgeQuickCoverNotificationData( 1393): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
E/LgeQuickCoverOverlayWindow( 1393): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1393): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1393): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1393): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1393): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1393): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1393): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1393): [native noti] inex =  3
D/LgeQuickCoverNotificationData( 1393): isNotificationForCurrentUser : true
,E/LgeQuickCoverOverlayWindow( 1393): updateNotificationData: count=4
,W/GLSActivity( 2108): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2108): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2108): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2108): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2108): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2108): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2108): 	at android.os.Binder.execTransact(Binder.java:446)
,D/QuickStatusbarLayout( 1393): Notification difference=198
D/QuickStatusbarLayout( 1393): child = android.widget.LinearLayout{156a1e25 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
E/PlayEventLogger( 4896): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 4896): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 4896): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/PlayEventLogger( 4896): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 4896): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/PlayEventLogger( 4896): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 4896): 	at android.os.Binder.execTransact(Binder.java:446)
W/System  ( 4896): Ignoring header User-Agent because its value was null.
D/libc-netbsd(  309): default dns: query_ipv6=0, query_ipv4=0
D/DSQN    ( 1029): DNSproblemNotiEnabled is disabled ignore DNS fail CB
I/jxcore-log( 6107): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6107): 
,I/jxcore-log( 6107): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6107): 
,I/jxcore-log( 6107): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6107): 
,I/jxcore-log( 6107): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6107): 
,D/sensors_hal_Time( 1029): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1029): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1029): tsOffsetIs: Apps: 1574189232580; DSPS: 51724450; Offset : -4327607697
,I/jxcore-log( 6107): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6107): 
,I/jxcore-log( 6107): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6107): 
,I/jxcore-log( 6107): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6107): 
,I/jxcore-log( 6107): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6107): 
,D/sensors_hal_Time( 1029): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1029): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1029): tsOffsetIs: Apps: 1594191975593; DSPS: 52379900; Offset : -4327611318
,I/jxcore-log( 6107): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6107): 
,I/jxcore-log( 6107): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6107): 
,I/jxcore-log( 6107): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6107): 
,I/jxcore-log( 6107): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6107): 
,I/[SystemUI]TimeTickManager( 1451): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1451): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1451): called onTimeUpdated()
I/[SystemUI]Clock( 1451): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1451): called onTimeUpdated()
I/[SystemUI]DateView( 1451): called onTimeUpdated()
I/[SystemUI]DateView( 1451): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1451): handleTimeUpdate
,D/sensors_hal_Time( 1029): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1029): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1029): tsOffsetIs: Apps: 1614193926627; DSPS: 53035324; Offset : -4327613539
,I/jxcore-log( 6107): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6107): 
,I/jxcore-log( 6107): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6107): 
,I/jxcore-log( 6107): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6107): 
,I/jxcore-log( 6107): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6107): 
,D/sensors_hal_Time( 1029): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1029): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1029): tsOffsetIs: Apps: 1634195842557; DSPS: 53690747; Offset : -4327620113
,I/jxcore-log( 6107): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6107): 
,I/jxcore-log( 6107): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6107): 
,I/jxcore-log( 6107): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6107): 
,I/jxcore-log( 6107): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6107): 
,D/sensors_hal_Time( 1029): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1029): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1029): tsOffsetIs: Apps: 1654197759163; DSPS: 54346169; Offset : -4327595492
,I/jxcore-log( 6107): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6107): 
,I/jxcore-log( 6107): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6107): 
,I/jxcore-log( 6107): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6107): 
,I/[SystemUI]TimeTickManager( 1451): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1451): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1451): called onTimeUpdated()
I/[SystemUI]Clock( 1451): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1451): called onTimeUpdated()
I/[SystemUI]DateView( 1451): called onTimeUpdated()
I/[SystemUI]DateView( 1451): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1451): handleTimeUpdate
I/jxcore-log( 6107): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6107): 
,D/sensors_hal_Time( 1029): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1029): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1029): tsOffsetIs: Apps: 1674199416552; DSPS: 55001584; Offset : -4327616492
,I/jxcore-log( 6107): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6107): 
,I/jxcore-log( 6107): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6107): 
,I/jxcore-log( 6107): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6107): 
,I/jxcore-log( 6107): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6107): 
,D/sensors_hal_Time( 1029): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1029): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1029): tsOffsetIs: Apps: 1694201632534; DSPS: 55657016; Offset : -4327598036
,I/jxcore-log( 6107): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6107): 
,I/jxcore-log( 6107): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6107): 
,I/jxcore-log( 6107): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6107): 
,I/jxcore-log( 6107): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6107): 
,D/sensors_hal_Time( 1029): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1029): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1029): tsOffsetIs: Apps: 1714203356589; DSPS: 56312433; Offset : -4327613353
,I/jxcore-log( 6107): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6107): 
,I/jxcore-log( 6107): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6107): 
,I/jxcore-log( 6107): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6107): 
,I/[SystemUI]TimeTickManager( 1451): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1451): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1451): called onTimeUpdated()
I/[SystemUI]Clock( 1451): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1451): called onTimeUpdated()
I/[SystemUI]DateView( 1451): called onTimeUpdated()
I/[SystemUI]DateView( 1451): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1451): handleTimeUpdate
I/jxcore-log( 6107): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6107): 
,D/sensors_hal_Time( 1029): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1029): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1029): tsOffsetIs: Apps: 1734205561685; DSPS: 56967865; Offset : -4327605496
,I/jxcore-log( 6107): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6107): 
,I/jxcore-log( 6107): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6107): 
,I/jxcore-log( 6107): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6107): 
,I/jxcore-log( 6107): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6107): 
,D/sensors_hal_Time( 1029): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1029): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1029): tsOffsetIs: Apps: 1754207740896; DSPS: 57623296; Offset : -4327593060
,I/jxcore-log( 6107): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6107): 
,I/jxcore-log( 6107): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6107): 
,I/jxcore-log( 6107): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6107): 
,I/jxcore-log( 6107): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6107): 
,D/sensors_hal_Time( 1029): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1029): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1029): tsOffsetIs: Apps: 1774209880108; DSPS: 58278727; Offset : -4327620439
,I/jxcore-log( 6107): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6107): 
,I/jxcore-log( 6107): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6107): 
,I/jxcore-log( 6107): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6107): 
,I/[SystemUI]TimeTickManager( 1451): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1451): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1451): called onTimeUpdated()
I/[SystemUI]Clock( 1451): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1451): called onTimeUpdated()
I/[SystemUI]DateView( 1451): called onTimeUpdated()
I/[SystemUI]DateView( 1451): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1451): handleTimeUpdate
I/jxcore-log( 6107): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6107): 
,D/sensors_hal_Time( 1029): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1029): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1029): tsOffsetIs: Apps: 1794211930777; DSPS: 58934154; Offset : -4327614474
,I/jxcore-log( 6107): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6107): 
,I/jxcore-log( 6107): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6107): 
,I/jxcore-log( 6107): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6107): 
,I/jxcore-log( 6107): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6107): 
,D/sensors_hal_Time( 1029): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1029): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1029): tsOffsetIs: Apps: 1814213904259; DSPS: 59589578; Offset : -4327594247
,I/jxcore-log( 6107): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6107): 
,I/jxcore-log( 6107): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6107): 
,I/jxcore-log( 6107): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6107): 
,D/sensors_hal_Time( 1029): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1029): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1029): tsOffsetIs: Apps: 1834221326959; DSPS: 60245182; Offset : -4327617914
,I/jxcore-log( 6107): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6107): 
,I/jxcore-log( 6107): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6107): 
,I/jxcore-log( 6107): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6107): 
,I/jxcore-log( 6107): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6107): 
,I/[SystemUI]TimeTickManager( 1451): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1451): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1451): called onTimeUpdated()
I/[SystemUI]Clock( 1451): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1451): called onTimeUpdated()
I/[SystemUI]DateView( 1451): called onTimeUpdated()
I/[SystemUI]DateView( 1451): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1451): handleTimeUpdate
,D/sensors_hal_Time( 1029): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1029): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1029): tsOffsetIs: Apps: 1854223302629; DSPS: 60900606; Offset : -4327595343
,V/GLSActivity( 2108): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/jxcore-log( 6107): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6107): 
I/ProcessStatsService( 1029): Prepared write state in 9ms
,I/GLSUser ( 2108): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 2108): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2108): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2108): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2108): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1029): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1029): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1029): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1029): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1029): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1393): onNotificationPosted
,D/SmartCoverUpdateMonitor( 1393): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1393): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1393): handleNotificationPosted(true)
D/QuickCircle( 1393): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1393): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1393): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1393): post do just update job
D/LgeQuickCoverNotificationData( 1393): showAll4
D/LgeQuickCoverNotificationData( 1393): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1393): showAll() ID : 915,0|com.lge.concierge|915|null|10017
D/LgeQuickCoverNotificationData( 1393): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
D/LgeQuickCoverNotificationData( 1393): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
E/LgeQuickCoverOverlayWindow( 1393): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1393): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1393): isNotificationForCurrentUser : true
,D/LgeQuickCoverOverlayWindow( 1393): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1393): isNotificationForCurrentUser : true
W/GLSActivity( 2108): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2108): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2108): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2108): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2108): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2108): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2108): 	at android.os.Binder.execTransact(Binder.java:446)
D/LgeQuickCoverOverlayWindow( 1393): [native noti] inex =  2
,D/LgeQuickCoverNotificationData( 1393): isNotificationForCurrentUser : true
E/PlayEventLogger( 4896): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 4896): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 4896): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/PlayEventLogger( 4896): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 4896): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/PlayEventLogger( 4896): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 4896): 	at android.os.Binder.execTransact(Binder.java:446)
D/LgeQuickCoverOverlayWindow( 1393): [native noti] inex =  3
D/LgeQuickCoverNotificationData( 1393): isNotificationForCurrentUser : true
W/System  ( 4896): Ignoring header User-Agent because its value was null.
E/LgeQuickCoverOverlayWindow( 1393): updateNotificationData: count=4
D/QuickStatusbarLayout( 1393): Notification difference=198
D/QuickStatusbarLayout( 1393): child = android.widget.LinearLayout{156a1e25 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
D/libc-netbsd(  309): default dns: query_ipv6=0, query_ipv4=0
D/DSQN    ( 1029): DNSproblemNotiEnabled is disabled ignore DNS fail CB
I/ProcessStatsService( 1029): Pruning old procstats: /data/system/procstats/state-2015-12-02-16-01-02.bin
,I/jxcore-log( 6107): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6107): 
,I/jxcore-log( 6107): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6107): 
,I/jxcore-log( 6107): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6107): 
,D/sensors_hal_Time( 1029): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1029): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1029): tsOffsetIs: Apps: 1874225547986; DSPS: 61556040; Offset : -4327608391
,I/jxcore-log( 6107): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6107): 
,I/jxcore-log( 6107): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6107): 
,I/jxcore-log( 6107): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6107): 
,I/jxcore-log( 6107): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6107): 
,D/sensors_hal_Time( 1029): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1029): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1029): tsOffsetIs: Apps: 1894227714280; DSPS: 62211471; Offset : -4327608924
,I/jxcore-log( 6107): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6107): 
,I/jxcore-log( 6107): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6107): 
,I/jxcore-log( 6107): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6107): 
,I/jxcore-log( 6107): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6107): 
,I/[SystemUI]TimeTickManager( 1451): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1451): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1451): called onTimeUpdated()
I/[SystemUI]Clock( 1451): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1451): called onTimeUpdated()
I/[SystemUI]DateView( 1451): called onTimeUpdated()
I/[SystemUI]DateView( 1451): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1451): handleTimeUpdate
,D/sensors_hal_Time( 1029): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1029): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1029): tsOffsetIs: Apps: 1914229874637; DSPS: 62866902; Offset : -4327615185
,I/jxcore-log( 6107): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6107): 
,I/jxcore-log( 6107): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6107): 
,I/jxcore-log( 6107): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6107): 
,I/jxcore-log( 6107): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6107): 
,D/sensors_hal_Time( 1029): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1029): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1029): tsOffsetIs: Apps: 1934232549474; DSPS: 63522349; Offset : -4327595273
,I/jxcore-log( 6107): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6107): 
,I/jxcore-log( 6107): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6107): 
,I/jxcore-log( 6107): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6107): 
,I/jxcore-log( 6107): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6107): 
,D/sensors_hal_Time( 1029): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1029): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1029): tsOffsetIs: Apps: 1954234737956; DSPS: 64177781; Offset : -4327604083
,I/jxcore-log( 6107): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6107): 
,I/jxcore-log( 6107): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6107): 
,D/PowerManagerServiceEx( 1029): acquireWakeLockInternal: lock=231167151, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1029
,I/ActivityManager( 1029): Killing 2319:com.google.android.gms/u0a5 (adj 15): empty for 1837s
,V/AlarmManager( 1029): ELAPSED_WAKEUP set : Alarm{212a750e type 2 when 1964144 com.android.bluetooth} when 1964144
W/bt-smp  ( 6189): Key(LSB ~ MSB) = 0a 3c a6 fe eb 17 6a 79 a6 1f 0a 0b f9 50 a0 5f 
W/bt-smp  ( 6189): Plain text(LSB ~ MSB) = fe 07 43 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 6189): Encrypted text(LSB ~ MSB) = 6a 97 d8 0a 2b 74 3f 0f 37 0b ea b7 52 46 a4 f1 
W/bt-btm  ( 6189): Stopping oneshot timer
I/ActivityManager( 1029): Killing 5982:com.google.android.gms.wearable/u0a5 (adj 15): empty for 1837s
,I/ActivityManager( 1029): Killing 5944:com.lge.eula/1000 (adj 15): empty for 1843s
,I/ActivityManager( 1029): Killing 5587:com.google.android.apps.plus/u0a97 (adj 15): empty for 1844s
,W/libprocessgroup( 1029): failed to open /acct/uid_10005/pid_2319/cgroup.procs: No such file or directory
,W/libprocessgroup( 1029): failed to open /acct/uid_10097/pid_5587/cgroup.procs: No such file or directory
W/libprocessgroup( 1029): failed to open /acct/uid_10005/pid_5982/cgroup.procs: No such file or directory
W/libprocessgroup( 1029): failed to open /acct/uid_1000/pid_5944/cgroup.procs: No such file or directory
D/[Concierge]Service( 2611): onStartCommand(). Type : 9
,D/PowerManagerServiceEx( 1029): releaseWakeLockInternal: lock=231167151 [*alarm*], flags=0x0
,I/jxcore-log( 6107): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6107): 
,I/jxcore-log( 6107): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6107): 
,I/[SystemUI]TimeTickManager( 1451): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1451): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1451): called onTimeUpdated()
I/[SystemUI]Clock( 1451): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1451): called onTimeUpdated()
I/[SystemUI]DateView( 1451): called onTimeUpdated()
I/[SystemUI]DateView( 1451): called onTimeUpdated()
,D/KeyguardUpdateMonitor( 1451): handleTimeUpdate
D/sensors_hal_Time( 1029): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1029): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1029): tsOffsetIs: Apps: 1974236501750; DSPS: 64833199; Offset : -4327610361
,I/jxcore-log( 6107): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6107): 
,I/jxcore-log( 6107): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6107): 
,TIME-OUT KILL (timeout was 1800000ms),I/jxcore-log( 6107): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6107): 
D/AndroidRuntime( 7025): 
D/AndroidRuntime( 7025): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 7025): CheckJNI is OFF
D/AndroidRuntime( 7025): Calling main entry com.android.commands.pm.Pm
I/ActivityManager( 1029): Force stopping com.test.thalitest appid=10311 user=-1: uninstall pkg
I/ActivityManager( 1029): Killing 6107:com.test.thalitest/u0a311 (adj 0): stop com.test.thalitest
W/PackageSettings( 1029): Skipping PackageSetting{16a953b5 com.example.hello/10318} due to missing metadata
I/WindowState( 1029): WIN DEATH: Window{929faaa u0 com.test.thalitest/com.test.thalitest.MainActivity}
D/WifiService( 1029): Client connection lost with reason: 4
D/InputDispatcher( 1029): Window went away: Window{929faaa u0 com.test.thalitest/com.test.thalitest.MainActivity}
I/ActivityManager( 1029): Killing 6284:com.lge.sync/1000 (adj 15): empty for 1820s
I/ActivityManager( 1029): Killing 5962:com.lge.bnr/1000 (adj 15): empty for 1820s
I/ActivityManager( 1029): Killing 6354:com.lge.settings.easy/1000 (adj 15): empty for 1820s
I/ActivityManager( 1029):   Force finishing activity ActivityRecord{11da0b97 u0 com.test.thalitest/.MainActivity t2}
W/ActivityManager( 1029): Spurious death for ProcessRecord{25924b2f 6107:com.test.thalitest/u0a311}, curProc for 6107: null
W/libprocessgroup( 1029): failed to open /acct/uid_1000/pid_6284/cgroup.procs: No such file or directory
W/libprocessgroup( 1029): failed to open /acct/uid_1000/pid_5962/cgroup.procs: No such file or directory
W/libprocessgroup( 1029): failed to open /acct/uid_1000/pid_6354/cgroup.procs: No such file or directory
E/GBMv2   (  342): DFP En is all cleared set to be enabled
I/ActivityManager( 1029): Force stopping com.test.thalitest appid=10311 user=0: pkg removed
I/ActivityManager( 1029):   Force finishing activity ActivityRecord{11da0b97 u0 com.test.thalitest/.MainActivity t2 f}
W/ActivityManager( 1029): Duplicate finish request for ActivityRecord{11da0b97 u0 com.test.thalitest/.MainActivity t2 f}
D/SplitWindowPolicy( 1945): updateActivityStateChanged: resumed=false, screenId=0, isScreenFull=false
D/SplitWindowPolicy( 1945): topRunningActivity=ActivityInfo{4b0f02d co.....Launcher}, taskId=1, activityType=1, bIsSplit=false
D/SplitWindowPolicy( 1945): updateActivityStateChanged: resumed=true, screenId=0, isScreenFull=false
D/SplitWindowPolicy( 1945): topRunningActivity=ActivityInfo{18522962 co.....Launcher}, taskId=1, activityType=1, bIsSplit=false
D/SplitWindowManager( 1029): removeStackAndNeedHomeResume ActivityStack{278c853c stackId=1, 0 tasks}
I/[LGHome]EVENT( 2059): [Launcher.java:5338:onStart()]onStart
I/[LGHome]EVENT( 2059): [Launcher.java:903:onResume()]onResume
I/[LGHome]EVENT( 2059): [LauncherModel.java:1352:startLoader()]startLoader isLaunching=true
I/[LGHome]Launcher.Model( 2059): [LauncherModel.java:1469:loadAndBindWorkspace()]loadAndBindWorkspace=1ms
D/ActionManagerService( 1909): notifyUserLog: 1000003
D/LIA_Informant_ActionManagerMessageHandler( 2707): handleMessage: what(1000) actionID(0x1000003)
I/[LGHome]GBoardWebView( 2059): [GBoardWebView.java:306:loadCacheBitmapPostDelayed()]loadCacheBitmapPostDelayed() delay:1
I/[LGHome]LGActivityUtil( 2059): [LGActivityUtil.java:319:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
D/KeyguardModel( 1451): mPackageIntentReceiver, received action: android.intent.action.PACKAGE_REMOVED, sendingUserId:0
D/LIA_MrGDBLogger_PackageInfoDetector( 2707): [dreamwood]action: android.intent.action.PACKAGE_REMOVED, package: com.test.thalitest
D/LIA_Service_RemotePackageHandler( 2008): onReceive action : android.intent.action.PACKAGE_REMOVED = package:com.test.thalitest
E/LGBluetoothAvrcpQcomAdapter( 6189): [BTUI] [BTUI] onReceive()... android.intent.action.PACKAGE_REMOVED
D/LGBluetoothAvrcpQcomAdapter( 6189): [BTUI] [+] updateMediaPlayerInfo
W/GeofencerStateMachine( 1814): Ignoring removeGeofence because network location is disabled.
I/InputReader( 1029): Reconfiguring input devices.  changes=0x00000010
I/art     ( 4264): Explicit concurrent mark sweep GC freed 16828(940KB) AllocSpace objects, 0(0B) LOS objects, 35% free, 29MB/45MB, paused 497us total 45.162ms
W/System.err( 4214): android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
W/System.err( 4214): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
W/System.err( 4214): 	at com.lge.mlt.MptOnAppWatcher$1.onReceive(MptOnAppWatcher.java:44)
W/System.err( 4214): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:956)
W/System.err( 4214): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 4214): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 4214): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 4214): 	at android.app.ActivityThread.main(ActivityThread.java:5274)
W/System.err( 4214): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 4214): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 4214): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
W/System.err( 4214): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
V/SIM_STK ( 1029): Menu title from STK is T-Mobile
D/PostponalbeReceiver( 6375): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.intent.action.PACKAGE_REMOVED'.
I/ActivityManager( 1029): Start proc com.lge.lockscreensettings for content provider com.lge.lockscreensettings/.LockSettingsProvider: pid=7057 uid=10080 gids={50080, 9997, 1028, 1015} abi=armeabi-v7a
I/[LGHome]EVENT( 2059): [Launcher.java:1056:onResume()]onResume end
I/[LGHome]EVENT( 2059): [Launcher.java:1114:onPause()]onPause
I/[SystemUI]QSlideListController( 1451): onReceive = android.intent.action.PACKAGE_REMOVED
I/[LGHome]GBoardWebView( 2059): [GBoardWebView.java:247:writeCacheBitmapPostDelayed()]writeCacheBitmapPostDelayed() delay: we don't have a change point1
D/ActionManagerService( 1909): notifyUserLog: 1000004
V/BoardContentProvider( 2707): query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
D/LIA_Informant_ActionManagerMessageHandler( 2707): handleMessage: what(1000) actionID(0x1000004)
I/GBoardWebViewUtils( 2059): checkExpiredAndRemoveCard() card: GBoardCard = { id: mw_initial
I/GBoardWebViewUtils( 2059): , create_time: 1430558575574
I/GBoardWebViewUtils( 2059): , expire_time: 0
I/GBoardWebViewUtils( 2059): , raw_uri: file:///system/etc/mrg_default_forms/MyWellness/initial/initial.html?id=mw_initial
I/GBoardWebViewUtils( 2059): , category: com.lge.intent.category.gboard.MYWELLNESS
I/GBoardWebViewUtils( 2059): , display: false
I/GBoardWebViewUtils( 2059): , animation: false }
I/GBoardWebViewUtils( 2059): checkExpiredAndRemoveCard() card: GBoardCard = { id: dyk000
I/GBoardWebViewUtils( 2059): , create_time: 1430558575600
I/GBoardWebViewUtils( 2059): , expire_time: 0
I/GBoardWebViewUtils( 2059): , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
I/GBoardWebViewUtils( 2059): , category: com.lge.intent.category.gboard.DOYOUKNOW
I/GBoardWebViewUtils( 2059): , display: false
I/GBoardWebViewUtils( 2059): , animation: false }
I/GBoardWebViewUtils( 2059): checkExpiredAndRemoveCard() card: GBoardCard = { id: guide_1111111111116_1449156806130
I/GBoardWebViewUtils( 2059): , create_time: 1449156807049
I/GBoardWebViewUtils( 2059): , expire_time: 0
I/GBoardWebViewUtils( 2059): , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/1/userguide.html?id=guide_1111111111116_1449156806130&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
I/GBoardWebViewUtils( 2059): , category: com.lge.intent.category.gboard.DOYOUKNOW
I/GBoardWebViewUtils( 2059): , display: false
I/GBoardWebViewUtils( 2059): , animation: false }
I/SystemUI[Framework]( 1029): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x8000, pkg=com.android.systemui
W/PhoneWindowManagerEx( 1029): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx( 1029): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx( 1029): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework]( 1029): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@2130028b,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework]( 1029): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
D/WallpaperManager( 2059): suggestDesiredDimensions(2880, 2560) by package(com.lge.launcher2)
I/[SystemUI]AppWidgetPanel(QRemoteWidgetPanel)( 1451): onReceive = android.intent.action.PACKAGE_REMOVED, packageName : com.test.thalitest
D/KeyguardModel( 1451): mPackageIntentReceiver, received action: android.intent.action.PACKAGE_FULLY_REMOVED, sendingUserId:0
I/[LGHome]GBoardWebView( 2059): [GBoardWebView.java:321:loadCacheBitmap()]loadCacheBitmap()
D/SplitUIManager( 1866): split_name #11 / not available #0
D/SplitUIService( 1866): removed split : 
V/SIM_STK ( 1029): Menu title from STK is T-Mobile
V/SIM_STK ( 1029): Menu title from STK is T-Mobile
I/art     ( 1029): Explicit concurrent mark sweep GC freed 24630(1550KB) AllocSpace objects, 12(875KB) LOS objects, 33% free, 44MB/67MB, paused 2.120ms total 231.851ms
I/[LGHome]EVENT( 2059): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
I/art     ( 1029): WaitForGcToComplete blocked for 92.750ms for cause Explicit
I/LockScreenSettings( 7057): Wallpaper base directory = /data/user/0/com.lge.lockscreensettings/files/
D/administrator( 1029): Handling package changes for user 0
W/ActivityManager( 1029): getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
D/LGBluetoothAvrcpQcomAdapter( 6189): [BTUI] installed app name: Music
D/LGBluetoothAvrcpQcomAdapter( 6189): [BTUI] installed app name: Google Play Music
D/LGBluetoothAvrcpQcomAdapter( 6189): [BTUI] === MediaPlayerInfo (playerId:0) ===
D/LGBluetoothAvrcpQcomAdapter( 6189): [BTUI]          displayName: Music
D/LGBluetoothAvrcpQcomAdapter( 6189): [BTUI]          packageName: com.lge.music
D/LGBluetoothAvrcpQcomAdapter( 6189): [BTUI]          playState: 2 (PAUSED)
D/LGBluetoothAvrcpQcomAdapter( 6189): [BTUI] === MediaPlayerInfo (playerId:1) ===
D/LGBluetoothAvrcpQcomAdapter( 6189): [BTUI]          displayName: Google Play Music
D/LGBluetoothAvrcpQcomAdapter( 6189): [BTUI]          packageName: com.google.android.music
D/LGBluetoothAvrcpQcomAdapter( 6189): [BTUI]          playState: 2 (PAUSED)
D/LGBluetoothAvrcpQcomAdapter( 6189): [BTUI] [-] updateMediaPlayerInfo
I/[LGHome]EVENT( 2059): [Launcher.java:5349:onStop()]onStop
D/SplitUIManager( 1866): split_name #11 / not available #0
I/SplitUIService( 1866): split app #11
V/SIM_STK ( 1029): Menu title from STK is T-Mobile
I/ActivityManager( 1029): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.manager.PreloadListManagerHelper: pid=7080 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
D/KeyguardModel( 1451): package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
D/KeyguardModel( 1451): createShortcutInfo...
D/KeyguardModel( 1451): package = com.android.mms, class = com.android.mms.ui.ConversationList
D/KeyguardModel( 1451): createShortcutInfo...
W/ResourcesManager( 1451): Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
W/ResourcesManager( 1451): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 1451): Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
W/ResourcesManager( 1451): Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
W/ResourceType( 1451): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1451): Failure retrieving resources for com.android.mms: Resource ID #0x0
D/KeyguardModel( 1451): package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
D/KeyguardModel( 1451): createShortcutInfo...
W/ResourcesManager( 1451): Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
W/ResourcesManager( 1451): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourceType( 1451): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1451): Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
D/KeyguardModel( 1451): package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
D/KeyguardModel( 1451): createShortcutInfo...
I/NotificationService( 1029): action=android.intent.action.PACKAGE_REMOVED queryReplace=false
D/BackupManagerService( 1029): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/JobSchedulerService( 1029): Receieved: android.intent.action.PACKAGE_REMOVED
W/ResourcesManager( 1451): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 1451): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 1451): Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
W/ResourcesManager( 1451): Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
D/TaskPersister( 1029): removeObsoleteFile: deleting file=2_task.xml
W/ResourceType( 1451): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1451): Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
D/PhoneStatusBar( 1451): setSystemUiVisibility vis=8000 mask=ffffffff oldVal=0 newVal=8000 diff=8000
I/[SystemUI]NavigationThemeResource( 1451): NavigationKey Color is changed(BLACK -> WHITE_WITH_SHADOW)
I/[SystemUI]NavigationThemeResource( 1451):  BarMode=4, Theme=WHITE, LightBackground=false (Transparent)
I/[SystemUI]NavigationThemeResource( 1451): , Keyguard show=false, IME shown=false, Panel expanded=false
D/KeyguardModel( 1451): package = com.lge.camera, class = com.lge.camera.CameraApp
D/KeyguardModel( 1451): createShortcutInfo...
D/KeyguardModel( 1451): package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
D/KeyguardModel( 1451): createShortcutInfo...
D/KeyguardModel( 1451): package = com.android.mms, class = com.android.mms.ui.ConversationList
D/KeyguardModel( 1451): createShortcutInfo...
W/ResourceType( 1451): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1451): Failure retrieving resources for com.android.mms: Resource ID #0x0
D/KeyguardModel( 1451): package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
D/KeyguardModel( 1451): createShortcutInfo...
W/ResourceType( 1451): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1451): Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
D/KeyguardModel( 1451): package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
D/KeyguardModel( 1451): createShortcutInfo...
W/ResourceType( 1451): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1451): Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
D/KeyguardModel( 1451): package = com.lge.camera, class = com.lge.camera.CameraApp
D/KeyguardModel( 1451): createShortcutInfo...
D/KeyguardModel( 1451): handleShortcutListChanged...
I/ActivityManager( 1029): Killing 6309:com.lge.lifetracker/u0a37 (adj 15): empty for 1821s
I/[LGHome]Launcher.Model( 2059): [LauncherModel.java:2230:run()] LauncherModel bind current page shortcut
I/[LGHome]Launcher( 2059): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/[LGHome]EVENT( 2059): [Workspace.java:918:addInScreen()]Add Shortcut [Email] in screen 1 [1, 4]
I/[LGHome]EVENT( 2059): [Workspace.java:918:addInScreen()]Add Shortcut [Play Store] in screen 1 [2, 4]
I/[LGHome]EVENT( 2059): [Workspace.java:918:addInScreen()]Add Shortcut [Camera] in screen 1 [3, 4]
I/AppUp4:AppBoxCP( 7080): onCreate
I/[LGHome]EVENT( 2059): [Workspace.java:918:addInScreen()]Add Shortcut [Settings] in screen 1 [4, 4]
W/AppUp4:DB( 7080):  [AppBoxDatabaseHelper] construct
I/AppUp4:DB( 7080):  setFingerPrint start
I/AppUp4:DB( 7080):  newfinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys SDK version = 21
I/AppUp4:DB( 7080):  beforefinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys
I/AppUp4:DB( 7080):  SDK version = 21
I/AppUp4:DB( 7080):  beforefinger == newfinger no write in DB
I/[LGHome]Launcher.Model( 2059): [LauncherModel.java:2244:run()] LauncherModel bind current page shortcut
I/[LGHome]Launcher( 2059): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 2059): [LGUnreadLgeEmailsBadge.java:107:countUnreadItems()]setTotalCount : 0
I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 2059): [LGUnreadLgeEmailsBadge.java:108:countUnreadItems()]countUnreadItems() ended..
I/[LGHome]EVENT( 2059): [Workspace.java:918:addInScreen()]Add Folder [Google] in screen 1 [0, 4]
I/[LGHome]Launcher.Model( 2059): [LauncherModel.java:2256:run()] LauncherModel bind current page widget
I/[LGHome]Launcher( 2059): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/art     ( 1029): Explicit concurrent mark sweep GC freed 9166(528KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 44MB/67MB, paused 1.832ms total 199.390ms
D/KeyguardModel( 1451): handleShortcutListChanged...
W/libprocessgroup( 1029): failed to open /acct/uid_10037/pid_6309/cgroup.procs: No such file or directory
I/[Concierge]WidgetView( 2059): ConciergeWidgetView is instantiated. sIsWidgetAttached : true
I/Timeline( 1029): Timeline: Activity_windows_visible id: ActivityRecord{2bdd6698 u0 com.lge.launcher2/.Launcher t1} time:1986117
D/[Concierge]Service( 2611): onStartCommand(). Type : 8
D/AppUp4:AppBoxApplication( 7080): AppBoxApplication onCreate()
D/[Concierge]Service( 2611): Update widget. Component : {com.lge.concierge/com.lge.concierge.ConciergeWidgetProvider}
D/[Concierge]Service( 2611): Update widget ID : 11
D/[Concierge]WidgetView( 2059): change position of spinner
D/[Concierge]Service( 2611): onStartCommand(). Type : 0
I/[Concierge]WidgetView( 2059): initWebView(). Time : 1449157992904
D/AppUp4:PreloadHelper( 7080): added Exclude : com.test.thalitest
W/ResourcesManager( 1029): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourceType( 1029): Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
I/ActivityManager( 1029): Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=7099 uid=10019 gids={50019, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
I/ActivityManager( 1029): Killing 6470:com.uei.lg.quicksetsdk.maxq616/1000 (adj 15): empty for 1814s
I/QRemote ( 6429): [RemoteControlManager.java:195:onServiceDisconnected()] oooooo start
W/System.err( 6429): android.os.DeadObjectException
W/System.err( 6429): 	at android.os.BinderProxy.transactNative(Native Method)
W/System.err( 6429): 	at android.os.BinderProxy.transact(Binder.java:496)
W/System.err( 6429): 	at com.uei.control.IControl.unregisterCallback(IControl.java:502)
W/System.err( 6429): 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:199)
W/System.err( 6429): 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
W/System.err( 6429): 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
W/System.err( 6429): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 6429): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 6429): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 6429): 	at android.app.ActivityThread.main(ActivityThread.java:5274)
W/System.err( 6429): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 6429): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 6429): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
W/System.err( 6429): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
E/UEI.SmartControl( 6429): IControl.unregisterCallback error: android.os.DeadObjectException
W/System.err( 6429): android.os.DeadObjectException
W/System.err( 6429): 	at android.os.BinderProxy.transactNative(Native Method)
W/System.err( 6429): 	at android.os.BinderProxy.transact(Binder.java:496)
W/System.err( 6429): 	at com.uei.control.IControl.unregisterSetupReadyCallback(IControl.java:818)
W/System.err( 6429): 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:200)
W/System.err( 6429): 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
W/System.err( 6429): 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
W/System.err( 6429): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 6429): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 6429): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 6429): 	at android.app.ActivityThread.main(ActivityThread.java:5274)
W/System.err( 6429): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 6429): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 6429): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
W/System.err( 6429): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
E/UEI.SmartControl( 6429): IControl.unregisterSetupReadyCallback error: android.os.DeadObjectException
I/QRemote ( 6429): [RemoteControlManager.java:203:onServiceDisconnected()] oooooo Control unbind before rebinding.
D/AndroidRuntime( 7025): Shutting down VM
E/libprocessgroup( 1029): failed to kill 1 processes for processgroup 6470
I/[Concierge]WebView( 2059): Return exist ConciergeWebView. Reuse : 496897463
D/[Concierge]WidgetView( 2059): State Change : null -> AccInBeforeState
I/[LgeWidgetLib]LgeAppWidgetHostView( 2059): [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
I/[LgeWidgetLib]ExtViewHost( 2059): [LgeAppWidgetExtViewHost.java:136:setState()]New State = com.lge.lgewidgetlib.extview.NormalState@35679968
I/[LGHome]EVENT( 2059): [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.concierge.ConciergeWidgetProvider] in screen 1 [0, 0]
I/[LGHome]Launcher.Model( 2059): [LauncherModel.java:2256:run()] LauncherModel bind current page widget
I/[LGHome]Launcher( 2059): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/[LGHome]EVENT( 2059): [Workspace.java:918:addInScreen()]Add AppWidget [com.google.android.googlequicksearchbox.SearchWidgetProvider] in screen 1 [0, 2]
D/[Concierge]WidgetView( 2059): isWidgetUpdateSkippable ? true
D/[Concierge]WidgetBroadcastReceiver( 2059): New receiver registered. Self-unregister old one. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
W/ActivityManager( 1029): Scheduling restart of crashed service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service in 1000ms
D/QRemote ( 6429): [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]10
I/QRemote ( 6429): [RemoteControlManager.java:157:onBindIRService()] oooooo bind
W/ResourcesManager( 7099): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7099): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 7099): Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
W/ResourcesManager( 7099): Asset path '/system/framework/lghiddenlibs.jar' does not exist or contains no resources.
W/ResourcesManager( 7099): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
I/ActivityManager( 1029): Start proc com.uei.lg.quicksetsdk.maxq616 for service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service: pid=7121 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
D/QRemote ( 6429): [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
W/[Concierge]WidgetView( 2059): Widget kill message received. Destory myself. My : 1449156035234, New one : 1449157992904
D/[Concierge]WidgetView( 2059): Unregister all receivers
W/[Concierge]WidgetBroadcastReceiver( 2059): Tried unregister broadcastReceiver which is not registered. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
I/[LGHome]Launcher( 2059): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/[LGHome]EVENT( 2059): [Workspace.java:918:addInScreen()]Add Shortcut [Gallery] in screen 2 [0, 4]
I/[LGHome]EVENT( 2059): [Workspace.java:918:addInScreen()]Add Shortcut [Calendar] in screen 2 [1, 4]
I/[LGHome]EVENT( 2059): [Workspace.java:918:addInScreen()]Add Shortcut [QuickMemo+] in screen 2 [2, 4]
I/[LGHome]EVENT( 2059): [Workspace.java:918:addInScreen()]Add Shortcut [Quick Remote] in screen 2 [3, 4]
I/[LGHome]EVENT( 2059): [Workspace.java:918:addInScreen()]Add Shortcut [FM Radio] in screen 2 [4, 4]
I/[LGHome]EVENT( 2059): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
I/[LGHome]Launcher( 2059): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/[LGHome]Launcher( 2059): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/[LgeWidgetLib]LgeAppWidgetHostView( 2059): [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
E/[LgeWidgetLib]LgeAppWidgetHostView( 2059): [LgeAppWidgetHostView.java:124:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
I/[LGHome]EVENT( 2059): [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1] in screen 2 [0, 0]
I/[LGHome]Launcher( 2059): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/SystemConfig( 7099): BUILD Country: EU
I/SystemConfig( 7099): BUILD Operator: OPEN
E/UEI.SmartControl( 7121): Failed while opening the log file.
E/UEI.SmartControl( 7121): java.io.FileNotFoundException: /data/data/com.uei.lg.quicksetsdk.maxq616/app_log/app.log: open failed: EROFS (Read-only file system)
E/UEI.SmartControl( 7121): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/UEI.SmartControl( 7121): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/UEI.SmartControl( 7121): 	at java.io.FileWriter.<init>(FileWriter.java:58)
E/UEI.SmartControl( 7121): 	at com.uei.e.c.a(Unknown Source)
E/UEI.SmartControl( 7121): 	at com.uei.e.c.a(Unknown Source)
E/UEI.SmartControl( 7121): 	at com.uei.e.c.<init>(Unknown Source)
E/UEI.SmartControl( 7121): 	at com.uei.e.c.a(Unknown Source)
E/UEI.SmartControl( 7121): 	at com.uei.control.core.QSApp.onCreate(Unknown Source)
E/UEI.SmartControl( 7121): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1011)
E/UEI.SmartControl( 7121): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4568)
E/UEI.SmartControl( 7121): 	at android.app.ActivityThread.access$1500(ActivityThread.java:148)
E/UEI.SmartControl( 7121): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1344)
E/UEI.SmartControl( 7121): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/UEI.SmartControl( 7121): 	at android.os.Looper.loop(Looper.java:135)
E/UEI.SmartControl( 7121): 	at android.app.ActivityThread.main(ActivityThread.java:5274)
E/UEI.SmartControl( 7121): 	at java.lang.reflect.Method.invoke(Native Method)
E/UEI.SmartControl( 7121): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/UEI.SmartControl( 7121): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
E/UEI.SmartControl( 7121): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
E/UEI.SmartControl( 7121): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/UEI.SmartControl( 7121): 	at libcore.io.Posix.open(Native Method)
E/UEI.SmartControl( 7121): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/UEI.SmartControl( 7121): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/UEI.SmartControl( 7121): 	... 18 more
D/UEI.SmartControl( 7121): Quickset Services start...
I/UEI.SmartControl( 7121): Manufacture = LGE
D/UEI.SmartControl( 7121): Id = LGNevo
D/UEI.SmartControl( 7121): File observer start...
E/UEI.SmartControl( 7121): IR Port is disabled: false
E/SharedPreferencesImpl( 2059): Couldn't rename file /data/user/0/com.lge.launcher2/shared_prefs/broadcast.numberbadge.counter.xml to backup file /data/user/0/com.lge.launcher2/shared_prefs/broadcast.numberbadge.counter.xml.bak
D/UEI.SmartControl( 7121): Starting file observer...
D/UEI.SmartControl( 7121): Extracting JNI libs...
D/UEI.SmartControl( 7121): --- this system supports 32-bit or 64-bit only
I/Timeline( 2059): Timeline: Activity_idle id: android.os.BinderProxy@3edbf6e4 time:1986608
I/ActivityManager( 1029): Killing 6429:com.lge.qremote/u0a112 (adj 15): empty for 1814s
D/UEI.SmartControl( 7121): --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
D/UEI.SmartControl( 7121): --- Checking lib: libqs_armeabi-v7a.zip
D/UEI.SmartControl( 7121): --- Extracting JNI libs: libqs_armeabi-v7a.zip
E/UEI.SmartControl( 7121): unzip: java.io.FileNotFoundException: /data/data/com.uei.lg.quicksetsdk.maxq616/files/libqs_jni.so: open failed: EROFS (Read-only file system)
I/UEI.SmartControl( 7121): --- Selecting new region: 6

```
