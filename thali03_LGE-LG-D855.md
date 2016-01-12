#### Test 55613145ac448d4_thali03_LGE-LG-D855 Logs


```
--------- beginning of main
D/Finsky  ( 4957): [1] 5.onFinished: Giving up after 6 failures.
,D/AndroidRuntime( 6175): 
D/AndroidRuntime( 6175): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 6175): CheckJNI is OFF
D/AndroidRuntime( 6175): Calling main entry com.android.commands.am.Am
--------- beginning of system
I/ActivityManager( 1032): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
V/SplitWindowPolicy( 1953): checkScreen => return. sourceIntent is null or not support SplitWindow component: ComponentInfo{co..../co.....MainActivity}
D/SplitInfo( 1032): new ActivitySplitInfo : ActivitySplitInfo [screenZone=0/ flag=0/ state=NATIVE]
D/ActivityManager( 1032): setTaskToReturnTo : TaskRecord{110ea68e #4 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
D/ActivityManager( 1032): setTaskToReturnTo : TaskRecord{110ea68e #4 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
D/WindowStateEx( 1032): AppWindowTokenEx init.. 
E/GBMv2   (  337): DFP En is all cleared set to be enabled
I/ActivityManager( 1032): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6195 uid=10311 gids={50311, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
D/AndroidRuntime( 6175): Shutting down VM
V/ActivityManager( 1032): Display changed displayId=0
D/DSDPConnection( 1862): Display #0 changed.
D/SplitWindowPolicy( 1953): updateActivityStateChanged: resumed=true, screenId=1, isScreenFull=true
D/SplitWindowPolicy( 1953): topRunningActivity=ActivityInfo{334ce194 co.....MainActivity}, taskId=4, activityType=0, bIsSplit=false
D/SplitWindowPolicy( 1953): updateActivityStateChanged: resumed=false, screenId=1, isScreenFull=true
D/SplitWindowPolicy( 1953): topRunningActivity=ActivityInfo{10ef543d co.....MainActivity}, taskId=4, activityType=0, bIsSplit=false
D/ContextHelper( 6195): convertTheme. context->name=com.test.thalitest themeResourceId=16973833
,I/WebViewFactory( 6195): Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,I/LibraryLoader( 6195): Loading: webviewchromium
I/LibraryLoader( 6195): Time to load native libraries: 4 ms (timestamps 515-519)
,I/LibraryLoader( 6195): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 6195): Binding Chromium to main looper Looper (main, tid 1) {4776529}
,I/LibraryLoader( 6195): Expected native library version number "",actual native library version number ""
I/chromium( 6195): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 6195): Initializing chromium process, renderers=0
,W/art     ( 6195): Attempt to remove local handle scope entry from IRT, ignoring
W/chromium( 6195): [WARNING:dns_config_service_posix.cc(293)] Failed to read DnsConfig.
V/AudioPolicyService(  320): registerClient() client 0xb57bc6c0, uid 10311
,W/chromium( 6195): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
I/chromium( 6195): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=32 off=46780 len=2953
I/chromium( 6195): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:33 off:229536 len:643667
I/Adreno-EGL( 6195): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 6195): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 6195): Build Date: 12/12/14 금
I/Adreno-EGL( 6195): Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
I/Adreno-EGL( 6195): Remote Branch: 
I/Adreno-EGL( 6195): Local Patches: 
I/Adreno-EGL( 6195): Reconstruct Branch: 
,D/BluetoothManagerService( 1032): Message: 20
D/BluetoothManagerService( 1032): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@15ea8:true
D/BluetoothAdapter( 6195): 777961646: getState() :  mService = null. Returning STATE_OFF
W/chromium( 6195): [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
W/chromium( 6195): [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
,W/art     ( 6195): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 6195): onDetachedFromWindow called when already detached. Ignoring
D/SystemWebViewEngine( 6195): CordovaWebView is running on device made by: LGE
,W/art     ( 6195): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 6195): Attempt to remove local handle scope entry from IRT, ignoring
D/OpenGLRenderer( 6195): Render dirty regions requested: true
I/OpenGLRenderer( 6195): Initialized EGL, version 1.4
D/OpenGLRenderer( 6195): Enabling debug mode 0
D/Atlas   ( 6195): Validating map...
D/SplitWindow( 1032): check instance of lgWin Window{11110fa2 u0 com.test.thalitest/com.test.thalitest.MainActivity}
I/SystemUI[Framework]( 1032): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x0, pkg=com.android.systemui
W/PhoneWindowManagerEx( 1032): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx( 1032): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx( 1032): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework]( 1032): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@3f2abfa1,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework]( 1032): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
D/PhoneStatusBar( 1461): setSystemUiVisibility vis=0 mask=ffffffff oldVal=8000 newVal=0 diff=8000
I/[SystemUI]NavigationThemeResource( 1461): NavigationKey Color is changed(WHITE_WITH_SHADOW -> BLACK)
I/[SystemUI]NavigationThemeResource( 1461):  BarMode=0, Theme=WHITE, LightBackground=false (Transparent)
I/[SystemUI]NavigationThemeResource( 1461): , Keyguard show=false, IME shown=false, Panel expanded=false
D/LgDataFeature( 6195): LgDataFeature() Constructor: none
D/LgDataFeature( 6195): LgDataFeature() Constructor Done, null
I/Timeline( 6195): Timeline: Activity_idle id: android.os.BinderProxy@29d2b15e time:280926
I/ActivityManager( 1032): Displayed com.test.thalitest/.MainActivity: +593ms (total +719ms)
I/Timeline( 1032): Timeline: Activity_windows_visible id: ActivityRecord{19d05eaf u0 com.test.thalitest/.MainActivity t4} time:280932
I/chromium( 6195): [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
I/chromium( 6195): 
D/JsMessageQueue( 6195): Set native->JS mode to OnlineEventsBridgeMode
D/jxcore_app_log( 6195): JniHelper::setJavaVM(0xb487c280), pthread_self() = -1434869504
D/JX-Cordova( 6195): jxcore cordova android initializing
E/GBMv2   (  337): DFP En is all cleared set to be enabled
E/GBMv2   (  337): Set value is all cleared set the max
I/GBMv2   (  337): DFP Enabled. Ignore VFP set
,W/jxcore-log( 6195): Initializing JXcore engine
W/jxcore-log( 6195): JXcore engine is ready
,W/jxcore-log( 6195): Starting JXcore engine
,W/.test.thalitest( 6195): type=1400 audit(0.0:148): avc: denied { ioctl } for path="socket:[8347]" dev="sockfs" ino=8347 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
,W/.test.thalitest( 6195): type=1400 audit(0.0:149): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3222 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
W/.test.thalitest( 6195): type=1400 audit(0.0:150): avc: denied { ioctl } for path="socket:[10522]" dev="sockfs" ino=10522 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
W/.test.thalitest( 6195): type=1400 audit(0.0:151): avc: denied { ioctl } for path="/cust" dev="mmcblk0p42" ino=2 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=dir
W/.test.thalitest( 6195): type=1400 audit(0.0:152): avc: denied { ioctl } for path="socket:[31001]" dev="sockfs" ino=31001 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
I/art     ( 6195): Background sticky concurrent mark sweep GC freed 124996(12MB) AllocSpace objects, 23(7MB) LOS objects, 28% free, 39MB/55MB, paused 1.045ms total 114.236ms
,W/jxcore-log( 6195): Platform android
W/jxcore-log( 6195): 
W/jxcore-log( 6195): Process ARCH arm
W/jxcore-log( 6195): 
,I/jxcore-log( 6195): JXcore Cordova bridge is ready!
I/jxcore-log( 6195): 
W/jxcore-log( 6195): JXcore engine is started
,I/jxcore-log( 6195): Toggling radios to true
I/jxcore-log( 6195): 
,D/BluetoothManagerService( 1032): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1032): enable():  mBluetooth =null mBinding = false
D/BluetoothManagerService( 1032): Message: 1
,D/BluetoothManagerService( 1032): MESSAGE_ENABLE: mBluetooth = null
D/LocationManagerService( 1032): getAllProviders()=[passive, gps, network]
D/Ulp_jni ( 1032): JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
D/Ulp_jni ( 1032): JNI:system_update. Event-4
D/WifiService( 1032): New client listening to asynchronous messages
,I/ActivityManager( 1032): Start proc com.android.bluetooth for service com.android.bluetooth/.btservice.AdapterService: pid=6275 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008, 4002, 1023} abi=armeabi-v7a
,D/WifiServiceImplEx( 1032): setWifiEnabled: true pid=6195, uid=10311, package= com.test.thalitest, App Lable : ThaliTest
D/WifiService( 1032): setWifiEnabled: true pid=6195, uid=10311
E/WifiService( 1032): Invoking mWifiStateMachine.setWifiEnabled
,E/WifiStateMachine( 1032):  InitialState CMD_START_SUPPLICANT 0 0
I/LGFTMITEM( 1032): [GET_FTM][id=6], offset=12288
D/LocationManagerService( 1032): getAllProviders()=[passive, gps, network]
D/Ulp_jni ( 1032): JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 1,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
D/Ulp_jni ( 1032): JNI:system_update. Event-4
D/WifiServiceImplEx( 1032): disconnect pid=6195, uid=10311, packageName=com.test.thalitest
E/WifiUtil( 1032): wfc_util_ffile_check_copy(): pid[1032] pDestFName[/data/misc/wifi/WCNSS_qcom_cfg.ini] pSourceFName[/system/etc/wifi/WCNSS_qcom_cfg.ini]
E/WifiUtil( 1032): wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
E/WifiUtil( 1032): wfc_util_ffile_check_copy(): pid[1032] pDestFName[/data/misc/wifi/WCNSS_qcom_wlan_nv.bin] pSourceFName[/system/etc/wifi/WCNSS_qcom_wlan_nv.bin]
D/WifiServiceImplEx( 1032): reconnect pid=6195, uid=10311, packageName=com.test.thalitest
E/WifiUtil( 1032): wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
I/WifiUtil( 1032): Intf0MacAddress=C49A027B60AC
E/WifiHW  ( 1032): unknown target_country: EU , set to default
E/WifiHW  ( 1032): [wifi_ensure_config_files] default country1 = GB
E/WifiHW  ( 1032): [wifi_ensure_config_files] default country2 = GB
I/WifiUtil( 1032): gEnableBmps=1
I/jxcore-log( 6195): Radios toggled
I/jxcore-log( 6195): 
I/jxcore-log( 6195): My device name is: LGE-LG-D855
I/jxcore-log( 6195): 
,W/ResourcesManager( 6275): Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
,W/ResourcesManager( 6275): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 6275): Asset path '/system/framework/com.qcom.bluetooth.jar' does not exist or contains no resources.
W/ResourcesManager( 6275): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
D/BluetoothAdapterApp( 6275): Loading JNI Library
,D/SoftapController(  316): Softap fwReload - Ok
,D/Tethering( 1032): sendTetherStateChangedBroadcast 1, 0, 0
D/libc-netbsd(  316): default dns: query_ipv6=0, query_ipv4=0
D/Tethering( 1032): InitialState.processMessage what=4
D/DSQN    ( 1032): DNSproblemNotiEnabled is disabled ignore DNS fail CB
,D/CommandListener(  316): Setting iface cfg
D/CommandListener(  316): Trying to bring down wlan0
D/CommandListener(  316): Clearing all IP addresses on wlan0
I/ActivityManager( 1032): Start proc com.android.settings for broadcast com.android.settings/.deviceinfo.UsbSettingsReceiver: pid=6307 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,D/Tethering( 1032): sendTetherStateChangedBroadcast 0, 0, 0
D/BluetoothAdapterApp( 6275): REFCOUNT: Constructed com.android.bluetooth.btservice.AdapterApp@29e4c32d Instance Count = 1
,E/WifiHW  ( 1032): Cannot open "/system/etc/wifi/autojoinconfig.txt": No such file or directory
E/WifiStateMachine( 1032): Couldn't get getWiFiOffloadingIface : 
E/WifiStateMachine( 1032): useWiFiOffloading() : false
E/WifiStateMachine( 1032): CONFIG_LGE_WLAN_PATH : true
D/WifiMonitor( 1032): startMonitoring(wlan0) with mConnected = false
D/WifiMonitor( 1032): connecting to supplicant
E/WifiHW  ( 1032): Unable to open connection to supplicant on "@android:wpa_wlan0": No such file or directory
I/WifiServerServiceExt( 1032): WIFI_STATE_CHANGED_ACTION [2]
V/WfdStateTracker( 1953): WfdStateTracker handleDirectStateChangedEvent: 1
D/StatusBar.NetworkController( 1461): refreshViews: Data not connected!! Set no data type icon / Roaming
,W/wpa_supplicant( 6323): type=1400 audit(0.0:153): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6848 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
W/wpa_supplicant( 6323): type=1400 audit(0.0:154): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6848 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
D/BluetoothAdapterApp( 6275): onCreate
,I/wpa_supplicant( 6323): Successfully initialized wpa_supplicant
,D/ProfileConfigQcom( 6275): [BTUI] HeadsetService is supported
D/ProfileConfigQcom( 6275): Adding HeadsetService
D/ProfileConfigQcom( 6275): [BTUI] A2dpService is supported
D/ProfileConfigQcom( 6275): Adding A2dpService
D/ProfileConfigQcom( 6275): [BTUI] HidService is supported
D/ProfileConfigQcom( 6275): Adding HidService
D/ProfileConfigQcom( 6275): [BTUI] HealthService is supported
D/ProfileConfigQcom( 6275): Adding HealthService
D/LGBluetoothFeatureConfig( 6275): isSupportPan() :  mTargetOp=OPEN
D/ProfileConfigQcom( 6275): [BTUI] PanService is supported
D/ProfileConfigQcom( 6275): Adding PanService
D/ProfileConfigQcom( 6275): [BTUI] GattService is supported
D/ProfileConfigQcom( 6275): Adding GattService
D/ProfileConfigQcom( 6275): [BTUI] BluetoothMapService is supported
D/ProfileConfigQcom( 6275): Adding BluetoothMapService
D/ProfileConfigQcom( 6275): [BTUI] HeadsetClientService is NOT supported
,W/ResourcesManager( 6307): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6307): Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
W/ResourcesManager( 6307): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 6307): Asset path '/system/framework/com.lge.bluetooth.jar' does not exist or contains no resources.
W/ResourcesManager( 6307): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
W/ResourcesManager( 6307): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
I/wpa_supplicant( 6323): rfkill: Cannot open RFKILL control device
I/wpa_supplicant( 6323): [LGE_PATCH] unset P2P_CAPABLE to ifname wlan0
D/BluetoothManagerService( 1032): Message: 20
D/BluetoothManagerService( 1032): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@277d25dd:true
,D/BluetoothAdapterState( 6275): make
I/LGFMServiceAdapter( 6275): [FM] LGFMServiceAdapter : create
I/bluedroid-qcom( 6275): init
I/BluetoothAdapterState( 6275): Entering OffState
I/bte_conf( 6275): bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
I/bte_conf( 6275): bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
E/bt_osi_config( 6275): config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
I/bte_conf( 6275): bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
D/BTIF_CORE( 6275): [BTUI] lge_load_bluetooth_address
I/bluedroid-qcom( 6275): get_profile_interface socket
I/bluedroid-qcom( 6275): get_profile_interface map_client
I/GKI_LINUX( 6275): gki_task_entry task_id=1 [BTIF] starting
D/BluetoothAdapterProperties( 6275): Address is:58:3F:54:73:64:C0
,W/bdaddr_loader( 6336): type=1400 audit(0.0:155): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6848 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
W/bdaddr_loader( 6336): type=1400 audit(0.0:156): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6848 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
D/BluetoothManagerService( 1032): Bluetooth Adapter name changed to G3-1
D/BluetoothManagerService( 1032): Stored Bluetooth name: G3-1
D/BluetoothAdapterProperties( 6275): Name is: G3-1
D/lge_bdaddr_loader( 6336): [BTUI] bdaddr_loader ::: START
D/lge_bdaddr_loader( 6336): [BTUI] bluetooth_load_bdaddress
I/LGFTMITEM( 6336): [GET_FTM][id=8], offset=16384
D/BluetoothManagerService( 1032): BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
D/BluetoothManagerService( 1032): Message: 40
D/BluetoothManagerService( 1032): MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
D/lge_bdaddr_loader( 6336): [BTUI] bdaddr to set in property : 58:3F:54:73:64:C0
I/bluedroid-qcom( 6275): config_hci_snoop_log
D/BluetoothManagerService( 1032): Calling onBluetoothServiceUp callbacks
D/BluetoothManagerService( 1032): Broadcasting onBluetoothServiceUp() to 7 receivers.
V/LGMDMManagerInternal( 6275): Create singleton instance
E/lge_bdaddr_loader( 6336): [BTUI] bluetooth_load_bdaddress : OK => 58:3F:54:73:64:C0
D/lge_bdaddr_loader( 6336): [BTUI] bdaddr_loader ::: END
,D/BluetoothAdapterState( 6275): CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
D/BluetoothAdapterProperties( 6275): Setting state to 11
I/BluetoothAdapterState( 6275): Bluetooth adapter state changed: 10-> 11
,I/LGBluetoothServiceJni( 6275): classInitNative: succeeds
D/BluetoothManagerService( 1032): Message: 60
D/BluetoothManagerService( 1032): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
D/BluetoothManagerService( 1032): Bluetooth State Change Intent: 10 -> 11
I/[SystemUI]BluetoothHandler( 1461): Receive : BluetoothAdapter.ACTION_STATE_CHANGED
D/LGBluetoothAPIService( 1953): [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
D/BluetoothBondStateMachine( 6275): make
D/BluetoothAdapterService( 6275): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@22bdc9dc
D/LGBluetoothServiceAdapter( 6275): [BTUI] check adapter is available - false.
D/BluetoothAdapterService( 6275): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@22bdc9dc
D/LGBluetoothServiceAdapter( 6275): [BTUI] check adapter is available - true : set adapter available.
D/LGBluetoothSettingsDBObserver( 6275): [BTUI] register observer for LG device name DB
I/BluetoothBondStateMachine( 6275): StableState(): Entering Off State
E/BluetoothAdapterService( 6275): File transfer profiles supported!!
,D/BluetoothHeadset( 1032): Proxy object connected
D/HeadsetService( 6275): Received start request. Starting profile...
I/LGBluetoothHeadsetServiceJni( 6275): classInitNative: succeeds
D/LGBluetoothHfpAdapter( 6275): Version 1.6
D/LGBluetoothFeatureConfig( 6275): isPrivacyLogsEnabled : true
D/BluetoothHeadset( 1862): Proxy object connected
I/BluetoothHeadsetServiceJni( 6275): classInitNative: succeeds
I/wpa_supplicant( 6323): rfkill: Cannot open RFKILL control device
E/BluetoothAdapterService( 6275): File transfer profiles supported!!
D/HeadsetStateMachine( 6275): make
D/BluetoothHeadset( 1862): Proxy object connected
D/BluetoothHeadset( 1862): Proxy object connected
E/BluetoothAdapterService( 6275): File transfer profiles supported!!
,D/UsbSettingsReceiver( 6307): [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
E/BluetoothAdapterService( 6275): File transfer profiles supported!!
D/UsbSettingsReceiver( 6307): [AUTORUN] sys.usb.config = ptp_only,adb
D/UsbSettingsReceiver( 6307): [AUTORUN] sys.usb.state = ptp_only,adb
D/UsbSettingsReceiver( 6307): [AUTORUN] persist.sys.usb.config = ptp_only,adb
,D/LgDataFeature( 6275): LgDataFeature() Constructor: none
D/LgDataFeature( 6275): LgDataFeature() Constructor Done, null
D/UsbSettingsReceiver( 6307): [AUTORUN] onReceive() : app userid = 0, current userid = 0
D/HeadsetStateMachine( 6275): max_hf_connections = 1
I/bluedroid-qcom( 6275): get_profile_interface handsfree
E/BluetoothAdapterService( 6275): File transfer profiles supported!!
V/ToneGenerator( 6275): ToneGenerator constructor: streamType=8, volume=1.000000
V/AudioPolicyService(  320): registerClient() client 0xb57bc4a0, uid 1002
V/AudioPolicyManager(  320): getOutput() device 2, stream 8, samplingRate 0, format 0, channelMask 3, flags 0
V/AudioPolicyManagerEx(  320): AudioPolicyManagerEx: getOutputForDevice
V/AudioPolicyManagerEx(  320): getOutput() returns output 2
V/AudioSystem( 6275): getOutputSamplingRate() no output descriptor for output 2 in gOutputs
V/AudioFlinger(  320): registerClient() client 0xb5581568, pid 6275
V/AudioSystem(  320): ioConfigChanged() event 0, ioHandle 4
V/AudioSystem(  320): ioConfigChanged() opening already existing output! 4
V/AudioSystem( 1461): ioConfigChanged() event 0, ioHandle 4
V/AudioSystem( 1461): ioConfigChanged() opening already existing output! 4
V/AudioSystem( 1862): ioConfigChanged() event 0, ioHandle 4
V/AudioSystem( 1862): ioConfigChanged() opening already existing output! 4
V/AudioSystem( 3284): ioConfigChanged() event 0, ioHandle 4
V/AudioSystem( 3284): ioConfigChanged() opening already existing output! 4
V/AudioSystem(  320): ioConfigChanged() event 0, ioHandle 2
V/AudioSystem(  320): ioConfigChanged() opening already existing output! 2
V/AudioSystem( 1862): ioConfigChanged() event 0, ioHandle 2
V/AudioSystem( 1862): ioConfigChanged() opening already existing output! 2
V/AudioSystem( 1461): ioConfigChanged() event 0, ioHandle 2
V/AudioSystem( 1461): ioConfigChanged() opening already existing output! 2
V/AudioSystem( 3284): ioConfigChanged() event 0, ioHandle 2
V/AudioSystem( 3284): ioConfigChanged() opening already existing output! 2
V/ToneGenerator( 6275): Create Track: 0xb4928080
V/AudioTrack( 6275): set(): streamType 8, sampleRate 0, format 0x1, channelMask 0x1, frameCount 0, flags #4, notificationFrames 0, sessionId 0, transferType 1
V/AudioTrack( 6275): set() streamType 8, sampleRate 0, format 1, frameCount 0, flags 0004
V/AudioPolicyManager(  320): getOutputForAttr() usage=3, content=4, tag= flags=00000000
V/AudioPolicyManager(  320): getOutputForAttr() device 2, samplingRate 0, format 0, channelMask 3, flags 0
V/AudioPolicyManagerEx(  320): AudioPolicyManagerEx: getOutputForDevice
V/AudioPolicyManagerEx(  320): getOutput() returns output 2
V/AudioSystem( 6275): getOutputSamplingRate() no output descriptor for output 2 in gOutputs
V/AudioSystem( 6275): ioConfigChanged() event 0, ioHandle 4
V/AudioSystem( 6275): ioConfigChanged() new output samplingRate 48000, format 0x1 channel mask 0x3 frameCount 960 latency 80
V/AudioSystem( 6275): ioConfigChanged() event 0, ioHandle 2
V/AudioSystem( 6275): ioConfigChanged() new output samplingRate 48000, format 0x5 channel mask 0x3 frameCount 960 latency 50
I/AudioFlinger(  320): isAudioPlaybackHookOn() false
V/AudioSystem( 1032): ioConfigChanged() event 0, ioHandle 4
V/AudioSystem( 1032): ioConfigChanged() opening already existing output! 4
V/AudioSystem( 1032): ioConfigChanged() event 0, ioHandle 2
V/AudioSystem( 1032): ioConfigChanged() opening already existing output! 2
V/AudioPolicyManager(  320): getOutputForAttr() usage=3, content=4, tag= flags=00000000
V/AudioPolicyManager(  320): getOutputForAttr() device 2, samplingRate 48000, format 1, channelMask 1, flags 4
V/AudioPolicyManagerEx(  320): AudioPolicyManagerEx: getOutputForDevice
V/AudioPolicyManagerEx(  320): getOutput() returns output 2
V/AudioSystem( 6275): getLatency() output 2, latency 50
V/AudioSystem( 6275): getFrameCount() output 2, frameCount 960
V/AudioTrack( 6275): createTrack_l() output 2 afLatency 50
V/AudioFlinger(  320): [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
V/AudioFl,inger(  320): [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
V/AudioFlinger(  320): [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
V/AudioFlinger(  320): [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
V/AudioFlinger(  320): createTrack() lSessionId: 16
V/AudioTrack( 6275): AUDIO_OUTPUT_FLAG_FAST successful; frameCount 480
V/AudioFlinger(  320): acquiring 16 from 6275, for 6275
V/AudioFlinger(  320):  added new entry for 16
V/ToneGenerator( 6275): ToneGenerator INIT OK, time: 284062
D/BluetoothAdapterService( 6275): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@22bdc9dc
D/HeadsetStateMachine( 6275): Enter Disconnected: -2, size: 0
D/HeadsetPhoneState( 6275): [BTUI] listenForPhoneState : start = false
D/LGBluetoothHfpManager( 6275): [BTUI] listenForMultiSimPhoneState : start = false
D/HeadsetStateMachine( 6275): [BTUI] change sampling rate to 8000 when device is disconnected
V/AudioFlinger(  320): setParameters(): io 0, keyvalue bt_samplerate=8000, calling pid 6275
D/audio_hw_primary(  320): adev_set_parameters: enter: bt_samplerate=8000
V/voice   (  320): voice_set_parameters: enter: bt_samplerate=8000
V/compress_voip(  320): voice_extn_compress_voip_set_parameters: enter: bt_samplerate=8000
D/BluetoothAdapterService( 6275): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@22bdc9dc
V/compress_voip(  320): voice_extn_compress_voip_set_parameters: exit
V/voice   (  320): voice_set_parameters: exit with code(0)
V/msm8974_platform_lge(  320): LGE_platform_set_parameters: enter: bt_samplerate=8000
V/msm8974_platform(  320): platform_set_parameters: enter: bt_samplerate=8000
V/msm8974_platform(  320): platform_set_parameters: exit with code(0)
V/lge_audio_loopback(  320): lge_platform_set_loopback_parameters: enter: 
V/audio_hw_primary(  320): adev_set_parameters: exit with code(0)
E/audio_a2dp_hw(  320): adev_set_parameters: ERROR: set param called even when stream out is null
,V/ToneGenerator( 6275): ToneGenerator destructor
V/ToneGenerator( 6275): stopTone
V/ToneGenerator( 6275): Delete Track: 0xb4928080
V/AudioTrack( 6275): ~AudioTrack, releasing session id from 6275 on behalf of 6275
V/AudioFlinger(  320): releasing 16 from 6275 for 6275
V/AudioFlinger(  320):  decremented refcount to 0
V/AudioFlinger(  320): purging stale effects
V/AudioPolicyService(  320): AudioCommandThread() adding release output 2
V/AudioPolicyService(  320): inserting command: 6 at index 0, num commands 0
V/AudioFlinger(  320): PlaybackThread::Track destructor
V/AudioPolicyService(  320): AudioCommandThread() waking up
V/AudioFlinger(  320): removeClient_l() pid 6275, calling pid 320
V/AudioPolicyService(  320): AudioCommandThread() processing release output 2
V/AudioPolicyManager(  320): releaseOutput() 2
V/AudioPolicyService(  320): AudioCommandThread() going to sleep
D/BluetoothA2dp( 1032): Proxy object connected
E/BluetoothAdapterService( 6275): File transfer profiles supported!!
D/A2dpService( 6275): Received start request. Starting profile...
I/BluetoothAvrcpServiceJni( 6275): classInitNative: succeeds
V/Avrcp   ( 6275): make
D/Avrcp   ( 6275): [BTUI] Use Native AVRCP : init jni
I/bluedroid-qcom( 6275): get_profile_interface avrcp
E/BluetoothAdapterService( 6275): File transfer profiles supported!!
W/Process ( 1032): Unable to open /proc/6339/status
D/UsbSettingsControl( 6307): [AUTORUN] getUsbConnected() : connected=true
D/UsbSettingsReceiver( 6307): [AUTORUN] onReceive() : availableList=[wlan0]
D/UsbSettingsReceiver( 6307): [AUTORUN] onReceive() : activeList=[]
D/UsbSettingsReceiver( 6307): [AUTORUN] onReceive() : errorList=[]
D/UsbSettingsControl( 6307): [AUTORUN] isAutorunTimer() : mAutorunChanging=false
D/UsbSettingsReceiver( 6307): [AUTORUN] onReceive() : TetherState Changed=wlan0
D/UsbSettingsControl( 6307): [AUTORUN] setTetherStatus() : status=false
V/AudioManager( 6275): registerRemoteController: size of Media player list: 0
,E/AudioManager( 6275): No RCC entry present to update
E/RemoteController( 6275): Cannot set synchronization mode on an unregistered RemoteController
I/ActivityManager( 1032): Killing 5840:com.google.android.partnersetup/u0a8 (adj 15): empty #17
I/BluetoothAvrcpQcomServiceJni( 6275): classInitQcomNative: succeeds
D/LGBluetoothAvrcpQcomAdapter( 6275): [BTUI] Use QCOM AVRCP 1.5 : init jni, browsing = false
I/BluetoothAvrcpQcomServiceJni( 6275): initQcomNative: succeeds
V/LGMDMManager( 6275): Create singleton instance
,I/BluetoothAdapterState( 6275): Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
I/wpa_supplicant( 6323): [LGE_WLAN_PATCH]P2P 5GHz support level:2(0:no 1:gconly 2:gconly_UNII1 3:full)
,I/wpa_supplicant( 6323): p2p0: CTRL-EVENT-AVOID-FREQ ranges=
I/wpa_supplicant( 6323): wlan0: CTRL-EVENT-SCAN-STARTED 
W/libprocessgroup( 1032): failed to open /acct/uid_10008/pid_5840/cgroup.procs: No such file or directory
,D/LGBluetoothAvrcpQcomAdapter( 6275): [BTUI] [+] updateMediaPlayerInfo
D/UsbSettingsReceiver( 6307): [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
D/UsbSettingsReceiver( 6307): [AUTORUN] sys.usb.config = ptp_only,adb
D/UsbSettingsReceiver( 6307): [AUTORUN] sys.usb.state = ptp_only,adb
D/UsbSettingsReceiver( 6307): [AUTORUN] persist.sys.usb.config = ptp_only,adb
,D/UsbSettingsReceiver( 6307): [AUTORUN] onReceive() : app userid = 0, current userid = 0
,D/UsbSettingsControl( 6307): [AUTORUN] getUsbConnected() : connected=true
D/UsbSettingsReceiver( 6307): [AUTORUN] onReceive() : availableList=[]
D/UsbSettingsReceiver( 6307): [AUTORUN] onReceive() : activeList=[]
D/UsbSettingsReceiver( 6307): [AUTORUN] onReceive() : errorList=[]
D/UsbSettingsControl( 6307): [AUTORUN] isAutorunTimer() : mAutorunChanging=false
D/UsbSettingsControl( 6307): [AUTORUN] setTetherStatus() : status=false
V/SIM_STK ( 1032): Menu title from STK is T-Mobile
V/SIM_STK ( 1032): Menu title from STK is T-Mobile
I/ActivityManager( 1032): Start proc com.lge.formmanager for broadcast com.lge.formmanager/.FormServiceReceiver: pid=6346 uid=10026 gids={50026, 9997, 3003, 1028} abi=armeabi-v7a
,W/ActivityManager( 1032): getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
,D/LGBluetoothAvrcpQcomAdapter( 6275): [BTUI] installed app name: Music
D/LGBluetoothAvrcpQcomAdapter( 6275): [BTUI] installed app name: Google Play Music
,D/LGBluetoothAvrcpQcomAdapter( 6275): [BTUI] === MediaPlayerInfo (playerId:0) ===
D/LGBluetoothAvrcpQcomAdapter( 6275): [BTUI]          displayName: Music
D/LGBluetoothAvrcpQcomAdapter( 6275): [BTUI]          packageName: com.lge.music
D/LGBluetoothAvrcpQcomAdapter( 6275): [BTUI]          playState: 2 (PAUSED)
D/LGBluetoothAvrcpQcomAdapter( 6275): [BTUI] === MediaPlayerInfo (playerId:1) ===
D/LGBluetoothAvrcpQcomAdapter( 6275): [BTUI]          displayName: Google Play Music
D/LGBluetoothAvrcpQcomAdapter( 6275): [BTUI]          packageName: com.google.android.music
D/LGBluetoothAvrcpQcomAdapter( 6275): [BTUI]          playState: 2 (PAUSED)
D/LGBluetoothAvrcpQcomAdapter( 6275): [BTUI] [-] updateMediaPlayerInfo
I/BluetoothA2dpServiceJni( 6275): classInitNative
I/BluetoothA2dpServiceJni( 6275): classInitNative: succeeds
D/A2dpStateMachine( 6275): make
I/bluedroid-qcom( 6275): get_profile_interface a2dp
I/GKI_LINUX( 6275): gki_task_entry task_id=2 [A2DP-MEDIA] starting
I/LGBluetoothA2dpServiceJni( 6275): classInitNative: succeeds
I/LGBluetoothA2dpAdapter( 6275): [BTUI] getInstance : create [LGBluetoothA2dpAdapter]
D/BluetoothAdapterService( 6275): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@22bdc9dc
I/BluetoothHidServiceJni( 6275): classInitNative: succeeds
,D/HidService( 6275): Received start request. Starting profile...
I/bluedroid-qcom( 6275): get_profile_interface hidhost
D/BluetoothAdapterService( 6275): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@22bdc9dc
I/BluetoothHealthServiceJni( 6275): classInitNative: succeeds
D/HealthService( 6275): Received start request. Starting profile...
D/A2dpStateMachine( 6275): Enter Disconnected: -2
I/bluedroid-qcom( 6275): get_profile_interface health
I/LGBluetoothHealthServiceJni( 6275): classInitNative: succeeds
D/BluetoothAdapterService( 6275): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@22bdc9dc
D/HeadsetStateMachine( 6275): Proxy object connected
D/LGBluetoothHfpAdapter( 6275): [BTUI] queryPhoneState
D/LGBluetoothHfpAdapter( 6275): Try to query the phonestate on bind
D/BluetoothPhoneService.BluetoothLTECall( 1862):  call mBluetoothHeadset.phoneStateChanged()
I/BluetoothPanServiceJni( 6275): classInitNative(L105): succeeds
D/PanService( 6275): Received start request. Starting profile...
D/BluetoothPanServiceJni( 6275): initializeNative(L110): pan
I/bluedroid-qcom( 6275): get_profile_interface pan
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
,I/ActivityManager( 1032): Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=6373 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
I/LGBluetoothPanAdapter( 6275): [BTUI] getInstance : create [LGBluetoothPanAdapter]
D/BluetoothAdapterService( 6275): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@22bdc9dc
,D/BluetoothAdapterService( 6275): Profile still not running:com.android.bluetooth.gatt.GattService
I/BtGatt.JNI( 6275): classInitNative(L901): classInitNative: Success!
D/HeadsetStateMachine( 6275): Disconnected process message: 10, size: 0
D/HeadsetPhoneState( 6275): sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
D/HeadsetStateMachine( 6275): Disconnected process message: 11, size: 0
D/BtGatt.DebugUtils( 6275): handleDebugAction() action=null
,D/BtGatt.GattService( 6275): Received start request. Starting profile...
D/BtGatt.GattService( 6275): start()
I/bluedroid-qcom( 6275): get_profile_interface gatt
D/BtGatt.AdvertiseManager( 6275): advertise manager created
D/BluetoothAdapterService( 6275): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@22bdc9dc
V/FormManager( 6346): Network unavailable.
,V/FormManager( 6346): Network unavailable.
D/BluetoothAdapterService( 6275): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@22bdc9dc
I/LGBluetoothMapAdapter( 6275): [BTUI] getInstance : create [LGBluetoothMapAdapter]
W/FormManager( 6346): Network not available. Please check & try again.
V/BluetoothMapService( 6275): BluetoothMapBinder()
D/BluetoothMapService( 6275): Received start request. Starting profile...
D/BluetoothMapService( 6275): start()
D/BluetoothMapEmailSettingsLoader( 6275): Found 0 applications
D/BluetoothMapEmailAppObserver( 6275): createReceiver()
D/BluetoothMapEmailAppObserver( 6275): initObservers()
D/BluetoothMapEmailAppObserver( 6275): getEnabledAccountItems()
,D/BluetoothAdapterService( 6275): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@22bdc9dc
V/BluetoothPbapReceiver( 6275): PbapReceiver onReceive 
V/BluetoothPbapReceiver( 6275): ***********action = android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothPbapReceiver( 6275): ***********state = 11
D/BluetoothAdapterService( 6275): Profile still not running:com.android.bluetooth.gatt.GattService
,D/BluetoothAdapterService( 6275): Profile still not running:com.android.bluetooth.gatt.GattService
D/BluetoothAdapterService( 6275): Profile still not running:com.android.bluetooth.gatt.GattService
D/BluetoothAdapterService( 6275): Profile still not running:com.android.bluetooth.gatt.GattService
V/PanService( 6275): [BTUI] SIM Extra State :ABSENT
D/BluetoothAdapterService( 6275): Profile still not running:com.android.bluetooth.map.BluetoothMapService
V/BluetoothMapService( 6275): Handler(): got msg=1
,D/BluetoothAdapterState( 6275): CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
I/bluedroid-qcom( 6275): enable
I/GKI_LINUX( 6275): gki_task_entry task_id=0 [BTU] starting
I/bt-btu  ( 6275): btu_task pending for preload complete event
I/bt_hci_bdroid( 6275): init
I/bt_vendor( 6275): bt-vendor : init
,I/bt_vendor( 6275): bt-vendor : get_bt_soc_type
E/bt_vendor( 6275): get_bt_soc_type: Failed to get soc type
I/bt_vendor( 6275): init: Local BD Address : c0:64:73:54:3f:58
D/bt_userial_mct( 6275): userial_init
,I/ActivityManager( 1032): Start proc com.lge.lifetracker for broadcast com.lge.lifetracker/.receiver.HealthDeviceReceiver: pid=6395 uid=10037 gids={50037, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
D/bt_hci_bdroid( 6275): set_power 1
I/bt_vendor( 6275): bt-vendor : BT_VND_OP_POWER_CTRL: On
I/bt_vendor( 6275): Starting hciattach daemon
I/bt_vendor( 6275): try to set true
I/ActivityManager( 1032): Killing 5544:com.lge.appbox.client/u0a11 (adj 15): empty #17
W/sh      ( 6406): type=1400 audit(0.0:157): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6848 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
W/sh      ( 6406): type=1400 audit(0.0:158): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6848 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
D/PCSuite ( 6373): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
I/qcom-bluetooth( 6414): /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  
,I/qcom-bluetooth( 6422): /system/etc/init.qcom.bt.sh: Transport : smd 
,I/qcom-bluetooth( 6423): /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
I/qcom-bluetooth( 6425): /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,I/qcom-bluetooth( 6426): /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> 
,I/qcom-bluetooth( 6427): /system/etc/init.qcom.bt.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,W/libprocessgroup( 1032): failed to open /acct/uid_10011/pid_5544/cgroup.procs: No such file or directory
I/qcom-bluetooth( 6428): /system/etc/init.qcom.bt.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> 
E/wpa_supplicant( 6323): USIM:  scard_init function
,I/wpa_supplicant( 6323): Trying to associate with SSID 'NG700'
V/WiFiOffLoadBroadcast( 6307): WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,I/libmdmdetect( 6430): ESOC framework not supported
E/Diag_Lib( 6430):  Diag_LSM_Init: Failed to open handle to diag driver, error = 13
D/WifiService( 1032): New client listening to asynchronous messages
D/bthci_qcomm_linux( 6430): [BTUI] bt_hci_qcomm_pfal_get_bdaddress: Get BDADDR from bluedroid prop (58:3F:54:73:64:C0)
,D/bthci_qcomm_common( 6430): [BTUI] bt_hci_qcomm_init:
D/bthci_qcomm_common( 6430): [BTUI]     BDADDR: 58:3F:54:73:64:C0
D/bthci_qcomm_common( 6430): [BTUI]     BR/EDR: Class 1
D/bthci_qcomm_common( 6430): [BTUI]     LE: Class 2
D/bthci_qcomm_common( 6430): [BTUI]     Ref Clock: 32M
D/btqsocnvmtags( 6430): [BTUI] init_riva_entries: set NORMAL power settings
E/ActivityThread( 6395): Failed to find provider info for com.lge.lgaccount.provider
W/LG Account v2.2( 6395): No ProfileInfo entries
I/LG Account v2.2( 6395): isEnabled: false
I/Feature ( 6395): [Lifetracker]ver: 4.21.112(40211120)
I/Feature ( 6395): [Lifetracker]Country: EU
I/Feature ( 6395): [Lifetracker]Operator: OPEN
I/Feature ( 6395): [Lifetracker]Ranking support: false
I/Feature ( 6395): [Lifetracker]Comfort support: false
I/Feature ( 6395): [Lifetracker]Accessory: true
I/Feature ( 6395): [Lifetracker]Health device: true
I/Feature ( 6395): [Lifetracker]Extra Pedometer: false
I/Feature ( 6395): [Lifetracker]Blood glucose device: false
I/Feature ( 6395): [Lifetracker]Device Number: 3
I/ActivityManager( 1032): Killing 5571:com.android.contacts/u0a19 (adj 15): empty #17
D/LgDataFeature( 6307): LgDataFeature() Constructor: none
D/LgDataFeature( 6307): LgDataFeature() Constructor Done, null
,D/WiFiOffLoadUpdatePriority( 6307): remove : truetruefalse
D/WiFiOffLoadUpdatePriority( 6307): remove2
V/WiFiOffLoadSharedPrefsUtils( 6307): save wifi state
V/WiFiOffLoadSharedPrefsUtils( 6307): save remove
D/WiFiOffLoadBroadcast( 6307): mLastConnectedNetwork from SharedPrefsUtils for wifioffloading : null
D/WiFiOffLoadBroadcast( 6307): S: false, R: true
,I/wpa_supplicant( 6323): wlan0: Associated with c0:ff:d4:d3:aa:48
,I/rmt_storage(  314): rmt_storage_connect_cb: clnt_h=0x5 conn_h=0xb6403090
I/rmt_storage(  314): rmt_storage_rw_iovec_cb: /boot/modem_fs2: clnt_h=0x2: req_h=0x9 msg_id=3: R/W request received
I/rmt_storage(  314): wakelock acquired: 1, error no: 42
I/rmt_storage(  314): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 Unblock worker thread (th_id: -1236806912)
W/libprocessgroup( 1032): failed to open /acct/uid_10019/pid_5571/cgroup.procs: No such file or directory
I/wpa_supplicant( 6323): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 6323): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
D/Tethering( 1032): sendTetherStateChangedBroadcast 1, 0, 0
,D/BluetoothPermissionRequest( 6307): onReceive
,D/LGBluetoothFeatureConfig( 6307):  get() - isFeatureLoaded : false
D/BluetoothManagerService( 1032): Message: 20
,D/BluetoothManagerService( 1032): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@2bf1cbf3:true
I/ActivityManager( 1032): Killing 5860:com.lge.email/u0a23 (adj 15): empty #17
D/LGBluetoothResetSettingReceiver( 6307): return without doing reset settings.
E/WifiStateMachine( 1032):  SupplicantStartingState CMD_SET_OPERATIONAL_MODE 1 0
E/WifiStateMachine( 1032):  SupplicantStartingState CMD_START_DRIVER 0 0
,E/WifiStateMachine( 1032):  SupplicantStartingState CMD_SET_HIGH_PERF_MODE 0 0
E/WifiStateMachine( 1032):  DefaultState CMD_SET_HIGH_PERF_MODE 0 0
E/WifiStateMachine( 1032):  SupplicantStartingState CMD_DISCONNECT 0 0
E/WifiStateMachine( 1032):  DefaultState CMD_DISCONNECT 0 0
E/WifiStateMachine( 1032):  SupplicantStartingState CMD_RECONNECT 0 0
E/WifiStateMachine( 1032):  DefaultState CMD_RECONNECT 0 0
E/WifiStateMachine( 1032):  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1032):  DefaultState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1032):  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1032):  DefaultState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1032):  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1032):  DefaultState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1032):  SupplicantStartingState SUP_CONNECTION_EVENT 0 0
D/WifiNative-wlan0( 1032): doString: [DRIVER MACADDR]
D/WifiNative-wlan0( 1032):    returned Macaddr = c4:9a:02:7b:60:ac
D/WifiStateMachine( 1032): MAC Addr from driver = c4:9a:02:7b:60:ac
D/WifiOffDelayIfNotUsed( 1032): setPowerSaveActivated(false)
I/rmt_storage(  314): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0x9 msg_id=3: Bytes written = 1572864
I/rmt_storage(  314): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0x9 msg_id=3: Send response: res=0 err=0
I/rmt_storage(  314): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 About to block rmt_storage client thread (th_id: -1236806912) wakelock released: 1, error no: 0
I/rmt_storage(  314): 
,I/rmt_storage(  314): rmt_storage_disconnect_cb: clnt_h=0x0x5 conn_h=0x0xb6403090
E/Diag_Lib(  885): [IMS_FATAL]| 3347 | 913 |ims-rtp-daemon ims_rtp_qmi_handler_thread_func waiting on select thread>
D/UsbSettingsReceiver( 6307): [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
D/UsbSettingsReceiver( 6307): [AUTORUN] sys.usb.config = ptp_only,adb
D/UsbSettingsReceiver( 6307): [AUTORUN] sys.usb.state = ptp_only,adb
D/UsbSettingsReceiver( 6307): [AUTORUN] persist.sys.usb.config = ptp_only,adb
W/libprocessgroup( 1032): failed to open /acct/uid_10023/pid_5860/cgroup.procs: No such file or directory
D/LGBluetoothOppAdapter( 6275): [BTUI] getInstance : create [LGBluetoothOppAdapter]
,E/WifiStateMachine( 1032): Couldn't get getWiFiOffloadingIface : 
E/WifiStateMachine( 1032): useWiFiOffloading() : false
E/WifiStateMachine( 1032): CONFIG_LGE_WLAN_PATH : true
D/WifiNative-wlan0( 1032): doBoolean: SET update_config 1
D/WifiNative-wlan0( 1032): SET update_config 1: returned true
D/WifiConfigStore( 1032): Loading config and enabling all networks 
D/WifiNative-wlan0( 1032): doString: [LIST_NETWORKS]
D/WifiNative-wlan0( 1032):    returned network id / ssid / bssid / flags 0	NG700	any	[CURRENT]
E/WifiConfigStore( 1032): readNetworkVariablesFromSupplicantFile key=psk
E/WifiConfigStore( 1032): readNetworkVariableFromSupplicantFile ssid=["NG700"] key=psk
E/WifiConfigStore( 1032): Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
W/Settings( 1032): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1032): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/StatusBar.NetworkController( 1461): refreshViews: Data not connected!! Set no data type icon / Roaming
D/WfdService( 1953): Waiting for WifiP2p enabling
I/WifiServerServiceExt( 1032): WIFI_STATE_CHANGED_ACTION [3]
D/WifiStateMachine( 1032): enableVerboseLogging : level 2
D/UsbSettingsReceiver( 6307): [AUTORUN] onReceive() : app userid = 0, current userid = 0
D/WifiNative-wlan0( 1032): doBoolean: SET device_name g3_global_com
D/WifiNative-wlan0( 1032): SET device_name g3_global_com: returned true
D/WifiNative-wlan0( 1032): doBoolean: SET manufacturer LGE
D/WifiNative-wlan0( 1032): SET manufacturer LGE: returned true
D/WifiNative-wlan0( 1032): doBoolean: SET model_name LG-D855
I/WifiServerServiceExt( 1032): batteryPsActivateMsgHandler : state:0 event:3
D/WifiNative-wlan0( 1032): SET model_name LG-D855: returned true
D/WifiNative-wlan0( 1032): doBoolean: SET model_number LG-D855
D/WifiNative-wlan0( 1032): SET model_number LG-D855: returned true
D/WifiNative-wlan0( 1032): doBoolean: SET serial_number LGD8553bed2d08
D/WifiNative-wlan0( 1032): SET serial_number LGD8553bed2d08: returned true
D/WifiNative-wlan0( 1032): doBoolean: SET config_methods physical_display virtual_push_button
D/WifiNative-wlan0( 1032): SET config_methods physical_display virtual_push_button: returned true
D/WifiNative-wlan0( 1032): doBoolean: SET device_type 10-0050F204-5
D/WifiNative-wlan0( 1032): SET device_type 10-0050F204-5: returned true
D/WfdsService( 1953): Supplicant Connection state is changed : true
D/WifiStateMachine( 1032): Setting OUI to DA-A1-19
D/WifiNative-wlan0( 1032): doBoolean: SCAN_INTERVAL 120
D/WfdsService( 1953): DefaultState - WIFI_SUPPLICANT_CONNECTED
D/WifiNative-wlan0( 1032): SCAN_INTERVAL 120: returned true
D/WifiNative-HAL( 1032): Setting external_sim to 1
D/WfdsService( 1953): Set the WFDS Monitor: true
D/WifiNative-wlan0( 1032): doBoolean: SET external_sim 1
,D/WifiNative-wlan0( 1032): SET external_sim 1: returned true
I/WifiNative-HAL( 1032): startHal
E/wifi    ( 1032): getStaticLongField sWifiHalHandle 0x989368dc
E/WifiHAL ( 1032): Could not connect handle
D/wifi    ( 1032): halHandle = 0x0, mVM = 0xb487c280, mCls = 0x701faa
I/WifiNative-HAL( 1032): Could not start hal
D/WifiStateMachine( 1032): Setting OUI to DA-A1-19
I/WifiNative-HAL( 1032): startHal
E/wifi    ( 1032): getStaticLongField sWifiHalHandle 0x9893685c
E/WifiHAL ( 1032): Could not connect handle
D/wifi    ( 1032): halHandle = 0x0, mVM = 0xb487c280, mCls = 0x501f62
I/WifiNative-HAL( 1032): Could not start hal
D/WifiNative-wlan0( 1032): doBoolean: STA_AUTOCONNECT 1
D/WifiNative-wlan0( 1032): STA_AUTOCONNECT 1: returned true
D/WifiNative-wlan0( 1032): doBoolean: DRIVER BTCOEXSCAN-STOP
D/WfdsMonitor( 1953): WfdsMonitorThread create
I/wpa_supplicant( 6323): wpa_driver_nl80211_ext_driver_cmd BTCOEXSCAN-STOP
D/WfdsMonitor( 1953): WFDS Monitor is created and started
D/WfdsService( 1953): WiFi: Supplicant connection re-established
D/WifiNative-wlan0( 1032): DRIVER BTCOEXSCAN-STOP: returned true
E/CtrlSupplicant( 1953): Access OK "@android:wpa_wlan0"
E/CtrlSupplicant( 1953): Succeed to open control connection
E/CtrlSupplicant( 1953): Succeed to open monitor connection
D/WifiNative-wlan0( 1032): doBoolean: DRIVER RXFILTER-STOP
I/wpa_supplicant( 6323): wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
D/UsbSettingsControl( 6307): [AUTORUN] getUsbConnected() : connected=true
D/UsbSettingsReceiver( 6307): [AUTORUN] onReceive() : availableList=[wlan0]
D/UsbSettingsReceiver( 6307): [AUTORUN] onReceive() : activeList=[]
D/UsbSettingsReceiver( 6307): [AUTORUN] onReceive() : errorList=[]
D/UsbSettingsControl( 6307): [AUTORUN] isAutorunTimer() : mAutorunChanging=false
D/UsbSettingsReceiver( 6307): [AUTORUN] onReceive() : TetherState Changed=wlan0
D/UsbSettingsControl( 6307): [AUTORUN] setTetherStatus() : status=false
D/WifiHS20( 1032): hidePasspointNotification off =false
I/StatusBar.NetworkController( 1461): networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1461): mWifiConnected = false, mWifiLevel = 0
W/Settings( 1032): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1032): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1032): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
D/WfdsMonitor( 1953): Supplicant connection established
D/StatusBar.NetworkController( 1461): refreshViews: Data not connected!! Set no data type icon / Roaming
D/WifiNative-wlan0( 1032): DRIVER RXFILTER-STOP: returned true
,D/WifiNative-wlan0( 1032): doBoolean: DRIVER RXFILTER-REMOVE 3
I/wpa_supplicant( 6323): wpa_driver_nl80211_ext_driver_cmd RXFILTER-REMOVE 3
D/WifiNative-wlan0( 1032): DRIVER RXFILTER-REMOVE 3: returned true
D/WifiNative-wlan0( 1032): doBoolean: DRIVER RXFILTER-START
I/wpa_supplicant( 6323): wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
D/WifiNative-wlan0( 1032): DRIVER RXFILTER-START: returned true
D/WifiNative-wlan0( 1032): doBoolean: DRIVER RXFILTER-STOP
I/wpa_supplicant( 6323): wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
W/Settings( 6030): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiNative-wlan0( 1032): DRIVER RXFILTER-STOP: returned true
D/WifiNative-wlan0( 1032): doBoolean: DRIVER RXFILTER-REMOVE 2
I/wpa_supplicant( 6323): android_multicast_filter_startstop : multicast filter set
D/WfdsService( 1953): Connected to the supplicant for wfds
D/WifiNative-wlan0( 1032): DRIVER RXFILTER-REMOVE 2: returned true
D/WifiNative-wlan0( 1032): doBoolean: DRIVER RXFILTER-START
I/wpa_supplicant( 6323): wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
D/WifiNative-wlan0( 1032): DRIVER RXFILTER-START: returned true
E/WifiNative: ( 1032): [284,959,105 us] RECONNECT  stack:logDbg - reconnect - enter - invokeEnterMethods - performTransitions
D/WifiNative-wlan0( 1032): doBoolean: RECONNECT
D/WifiNative-wlan0( 1032): RECONNECT: returned true
D/WifiNative-wlan0( 1032): doString: [STATUS]
D/WifiMonitor( 1032): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
D/WifiNative-wlan0( 1032):    returned bssid=c0:ff:d4:d3:aa:48 ssid=NG700 id=0 mode=station pairwise_cipher=CCMP group_cipher=CCMP key_mgmt=WPA2-PSK wpa_state=COMPLETED p2p_device_address=02:9a:02:7b:60:ac address=c4:9a:02:7b:60:ac uuid=530d3fd0-1ba3-5409-a336-ff4e42af59a2
E/WifiMonitor( 1032): WifiMonitor:wlan0 cnt=0 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/WifiNative-wlan0( 1032): doBoolean: DRIVER SETSUSPENDMODE 1
I/wpa_supplicant( 6323): wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 1
D/WifiNative-wlan0( 1032): DRIVER SETSUSPENDMODE 1: returned true
D/WifiNative-wlan0( 1032): doBoolean: SET ps 1
D/WifiNative-wlan0( 1032): SET ps 1: returned true
D/LGWifiP2pService( 1032): P2pDisabledState{ when=0 what=131203 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiScanningService( 1032): SCAN_AVAILABLE : 3
D/RttService( 1032): SCAN_AVAILABLE : 3
D/WifiScanningService( 1032): DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
,I/WifiNative-HAL( 1032): startHal
E/wifi    ( 1032): getStaticLongField sWifiHalHandle 0x97b1699c
D/RttService( 1032): DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiHAL ( 1032): Could not connect handle
,D/wifi    ( 1032): halHandle = 0x0, mVM = 0xb487c280, mCls = 0x700f7a
I/WifiNative-HAL( 1032): Could not start hal
E/WifiScanningService( 1032): could not start HAL
E/WifiStateMachine( 1032):  DisconnectedState CMD_SET_OPERATIONAL_MODE 1 0
E/WifiStateMachine( 1032):  DisconnectedState CMD_START_DRIVER 0 0
E/WifiStateMachine( 1032):  ConnectModeState CMD_START_DRIVER 0 0
E/WifiStateMachine( 1032):  DriverStartedState CMD_START_DRIVER 0 0
E/WifiStateMachine( 1032):  DisconnectedState what:132106 1 0
V/FormManager( 6346): Network unavailable.
E/WifiStateMachine( 1032):  ConnectModeState what:132106 1 0
E/WifiStateMachine( 1032):  DriverStartedState what:132106 1 0
I/WifiServerServiceExt( 1032): setWifiDualbandAPConnection band : 1
E/wpa_supplicant( 6323): nWIFIDualbandAPConnection: 1
W/FormManager( 6346): Network not available. Please check & try again.
D/CommandListener(  316): Setting iface cfg
D/CommandListener(  316): Trying to bring up p2p0
D/WifiMonitor( 1032): startMonitoring(p2p0) with mConnected = true
D/LGWifiP2pService( 1032): P2pEnablingState
D/LGWifiP2pService( 1032): P2pEnablingState{ when=0 what=147457 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1032): P2p socket connection successful
D/PCSuite ( 6373): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
D/LGWifiP2pService( 1032): P2pEnabledState
V/FormManager( 6346): Network unavailable.
D/LGWifiP2pService( 1032): sending p2p connection changed broadcast
V/WfdStateTracker( 1953): WfdStateTracker handleDirectStateChangedEvent: 2
D/WfdsService( 1953): WifiP2pState is changed : true
D/WfdsService( 1953): Receive the WFDS_ENABLE Method
D/WfdsService( 1953): Set the WFDS Monitor: true
D/WfdsService( 1953): Connected to the supplicant for wfds
D/WfdsJNI ( 1953): doCommand: WFDS_SET TRUE
I/wpa_supplicant( 6323): WFDS: wfds_supplicant_wfds_cmd: cmd = SET TRUE
D/WfdsJNI ( 1953): doCommand: WFDS_GET_MAC_ADDRESS
I/wpa_supplicant( 6323): WFDS: wfds_supplicant_wfds_cmd: cmd = GET_MAC_ADDRESS
E/WifiStateMachine( 1032):  DisconnectedState what:132096 -100 0
D/WfdsJNI ( 1953): doCommand: IFNAME=wlan0 GET_CAPABILITY channels
E/WifiStateMachine( 1032):  ConnectModeState what:132096 -100 0
D/WfdsService( 1953): selectPreferredScanChannel [36]
D/WfdsService( 1953): STATE : WfdsEnabledState - enter: this device mac 02:9a:02:7b:60:ac
E/WifiStateMachine( 1032):  DriverStartedState what:132096 -100 0
I/WifiServerServiceExt( 1032): set CMD_DISCONNECT_RSSI_LVL : -100
E/wpa_supplicant( 6323): disconnect_rssi_lvl: -100
E/WifiStateMachine( 1032):  DisconnectedState CMD_SET_COUNTRY_CODE 1 0 cz
E/WifiStateMachine( 1032):  ConnectModeState CMD_SET_COUNTRY_CODE 1 0 cz
E/WifiStateMachine( 1032):  DriverStartedState CMD_SET_COUNTRY_CODE 1 0 cz
D/WifiNative-wlan0( 1032): doBoolean: DRIVER COUNTRY CZ
I/wpa_supplicant( 6323): wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
I/wpa_supplicant( 6323): wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
D/WifiMonitor( 1032): Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
E/WifiMonitor( 1032): WifiMonitor:wlan0 cnt=1 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
I/wpa_supplicant( 6323): [LGE_PATCH] driver_cmd() country:CZ
I/wpa_supplicant( 6323): p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
E/WifiMonitor( 1032): handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
E/WifiMonitor( 1032): handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
D/WifiMonitor( 1032): Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
E/WifiMonitor( 1032): WifiMonitor:p2p0 cnt=2 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
E/WifiMonitor( 1032): handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
E/WifiMonitor( 1032): handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
I/wpa_supplicant( 6323): p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
D/WifiMon,itor( 1032): Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
E/WifiMonitor( 1032): WifiMonitor:p2p0 cnt=3 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
E/WifiMonitor( 1032): handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
E/WifiMonitor( 1032): handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
D/WfdsMonitor( 1953): Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
D/WfdsMonitor( 1953): Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
D/WifiNative-wlan0( 1032): DRIVER COUNTRY CZ: returned true
E/WifiStateMachine( 1032):  DisconnectedState CMD_SET_FREQUENCY_BAND 0 0
E/WifiStateMachine( 1032):  ConnectModeState CMD_SET_FREQUENCY_BAND 0 0
E/WifiStateMachine( 1032):  DriverStartedState CMD_SET_FREQUENCY_BAND 0 0
D/WifiNative-wlan0( 1032): doBoolean: DRIVER SETBAND 0
I/wpa_supplicant( 6323): wpa_driver_nl80211_ext_driver_cmd SETBAND 0 - interface name wlan0
I/wpa_supplicant( 6323): wlan0: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
D/WifiNative-p2p0( 1032): doBoolean: SET persistent_reconnect 1
D/WifiMonitor( 1032): Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN]
E/WifiMonitor( 1032): WifiMonitor:wlan0 cnt=4 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
E/WifiMonitor( 1032): handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
E/WifiMonitor( 1032): handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
D/WifiNative-wlan0( 1032): DRIVER SETBAND 0: returned true
D/WifiNative-wlan0( 1032): doBoolean: BSS_FLUSH 0
D/WifiNative-wlan0( 1032): BSS_FLUSH 0: returned true
D/WifiNative-wlan0( 1032): doBoolean: SCAN
D/WifiService( 1032): New client listening to asynchronous messages
V/BluetoothFtpReceiver( 6275): BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
I/wpa_supplicant( 6323): wlan0: CTRL-EVENT-SCAN-STARTED 
D/WifiMonitor( 1032): Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1032): WifiMonitor:wlan0 cnt=5 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1032): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1032): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
D/WifiNative-wlan0( 1032): SCAN: returned true
E/WifiStateMachine( 1032):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 0 0 rt=284992  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
V/WiFiOffLoadBroadcast( 6307): WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
V/BluetoothSapReceiver( 6275): [BTUI] checkServiceStart
V/BluetoothSapReceiver( 6275): [BTUI] region:EU country:EU
V/BluetoothSapReceiver( 6275): SapReceiver onReceive 
D/WfdsService( 1953): WIFI_P2P_CONNECTION_CHANGED_ACTION
D/WifiNative-p2p0( 1032): SET persistent_reconnect 1: returned true
D/WifiNative-p2p0( 1032): doBoolean: SET device_name G3-1
D/WfdsService( 1953): isConnected: false
V/BluetoothSapReceiver( 6275): action = android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothSapReceiver( 6275):  Bluetooth Adapter state = 11
D/WifiNative-p2p0( 1032): SET device_name G3-1: returned true
D/LGWifiP2pService( 1032): [LGE_P2P] initializeP2pSettings() check postfix
D/LGWifiP2pService( 1032): before postfix = G3-1
D/WifiServerServiceExt( 1032): postfix byte check : 4
D/LGWifiP2pService( 1032): after postfix = G3-1
D/WifiNative-p2p0( 1032): doBoolean: SET p2p_ssid_postfix -G3-1
D/WifiNative-p2p0( 1032): SET p2p_ssid_postfix -G3-1: returned true
E/WifiStateMachine( 1032):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 0 0 rt=284995  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
D/WifiNative-p2p0( 1032): doBoolean: SET device_type 10-0050F204-5
D/WifiNative-p2p0( 1032): SET device_type 10-0050F204-5: returned true
D/WifiNative-p2p0( 1032): doBoolean: SET config_methods virtual_push_button physical_display keypad
E/WifiStateMachine( 1032):  DisconnectedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
,D/WifiNative-p2p0( 1032): SET config_methods virtual_push_button physical_display keypad: returned true
D/WifiNative-p2p0( 1032): doBoolean: P2P_SET conc_pref p2p
,E/WifiStateMachine( 1032):  ConnectModeState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
E/WifiStateMachine( 1032):  DriverStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
E/WifiStateMachine( 1032):  SupplicantStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
D/WifiNative-p2p0( 1032): P2P_SET conc_pref p2p: returned true
D/WifiNative-HAL( 1032): p2pGetDeviceAddress
E/WifiStateMachine( 1032):  DefaultState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
D/WifiNative-HAL( 1032): p2pGetDeviceAddress returning 02:9a:02:7b:60:ac
D/WiFiOffLoadUpdatePriority( 6307): remove : truetruetrue
I/ActivityManager( 1032): Start proc com.lge.settings.easy for broadcast com.lge.settings.easy/com.lge.settings.bluetooth.LGBluetoothProfileConnectionReceiver: pid=6445 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
E/WifiStateMachine( 1032):  DisconnectedState CMD_GET_CONFIGURED_NETWORKS uid=1000 1000 0 num=1
E/WifiStateMachine( 1032):  ConnectModeState CMD_GET_CONFIGURED_NETWORKS uid=1000 1000 0 num=1
I/StatusBar.NetworkController( 1461): networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1461): mWifiConnected = false, mWifiLevel = 0
,D/StatusBar.NetworkController( 1461): refreshViews: Data not connected!! Set no data type icon / Roaming
D/LGWifiP2pService( 1032): DeviceAddress: 02:9a:02:7b:60:ac
D/WifiNative-p2p0( 1032): doBoolean: P2P_FLUSH
W/Settings( 1032): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1032): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1032): NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
D/WifiServerServiceExt( 1032): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1032): setSupplicantStateCOMPLETED
D/WifiNative-p2p0( 1032): P2P_FLUSH: returned true
D/WifiNative-p2p0( 1032): doBoolean: P2P_SERVICE_FLUSH
D/WifiNative-p2p0( 1032): P2P_SERVICE_FLUSH: returned true
D/WifiNative-p2p0( 1032): doString: [LIST_NETWORKS]
D/WifiNative-p2p0( 1032):    returned network id / ssid / bssid / flags
D/WifiNative-p2p0( 1032): doBoolean: SAVE_CONFIG
E/WifiStateMachine( 1032):  DisconnectedState CMD_SAVE_CONFIG uid=1000 0 0
E/WifiStateMachine( 1032):  ConnectModeState CMD_SAVE_CONFIG uid=1000 0 0
D/WifiNative-wlan0( 1032): doBoolean: SAVE_CONFIG
I/WfdStateTracker( 1953): handleP2pThisDeviceChanged
D/WfdsService( 1953): WIFI_P2P_THIS_DEVICE_CHANGED_ATCION
D/WfdsService( 1953): Update P2p Interface State: 3
D/WifiNative-p2p0( 1032): SAVE_CONFIG: returned true
,D/LGWifiP2pService( 1032): sending p2p persistent groups changed broadcast
D/LGWifiP2pService( 1032): InactiveState
D/LGWifiP2pService( 1032): InactiveState{ when=-62ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1032): P2pEnabledState{ when=-62ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-p2p0( 1032): doBoolean: DRIVER COUNTRY CZ
D/WifiNative-wlan0( 1032): SAVE_CONFIG: returned true
I/wpa_supplicant( 6323): wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
I/wpa_supplicant( 6323): p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
I/wpa_supplicant( 6323): [LGE_PATCH] driver_cmd() country:CZ
I/wpa_supplicant( 6323): p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
D/WiFiOffLoadUpdatePriority( 6307): remove1
V/WiFiOffLoadSharedPrefsUtils( 6307): save remove
I/wpa_supplicant( 6323): p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
D/WfdsMonitor( 1953): Event [CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
D/WfdsMonitor( 1953): Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
D/WfdsMonitor( 1953): Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
D/WifiMonitor( 1032): Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
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
D/WifiNative-p2p0( 1032): DRIVER COUNTRY CZ: returned true
D/LGWifiP2pService( 1032): InactiveState{ when=-16ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1032): P2pEnabledState{ when=-17ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1032): InactiveState{ when=-1ms what=139287 arg2=1 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1032): P2pEnabledState{ when=-1ms what=139287 arg2=1 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1032): DefaultState{ when=-1ms what=139287 arg2=1 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1032): InactiveState{ when=-1ms what=139285 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1032): P2pEnabledState{ when=-1ms what=139285 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1032): DefaultState{ when=-1ms what=139285 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1032): InactiveState{ when=0 what=139287 arg2=1 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1032): P2pEnabledState{ when=0 what=139287 arg2=1 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1032): DefaultState{ when=0 what=139287 arg2=1 target=com.android.internal.util.StateMachine$SmHandler }
W/WfdsService( 1953): DefaultState - msg [9441285] is not handled
D/LGWifiP2pService( 1032): InactiveState{ when=-1ms what=139283 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1032): P2pEnabledState{ when=-1ms what=139283 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1032): DefaultState{ when=-1ms what=139283 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiServerServiceExt( 1032): No p2p device connected
D/WiFiOffLoadBroadcast( 6307): mLastConnectedNetwork from SharedPrefsUtils for wifioffloading : null
D/WiFiOffLoadBroadcast( 6307): S: false, R: false
E/WifiStateMachine( 1032):  DisconnectedState CMD_GET_CONFIGURED_NETWORKS uid=1000 1000 0 num=1
E/WifiStateMachine( 1032):  ConnectModeState CMD_GET_CONFIGURED_NETWORKS uid=1000 1000 0 num=1
D/WiFiOffLoadUpdatePriority( 6307): saved SSID: "NG700"
D/WiFiOffLoadUpdatePriority( 6307): connected SSID: null
D/WiFiOffLoadUpdatePriority( 6307): private wpa: "NG700" 300
D/WifiServiceImplEx( 1032): addOrUpdateNetwork pid=6307, uid=1000, packageName=android.uid.system:1000
,E/addOrUpdateNetwork( 1032):  uid = 1000 SSID "NG700" nid=0
E/WifiStateMachine( 1032):  DisconnectedState CMD_ADD_OR_UPDATE_NETWORK uid=1000 0 0 "NG700"WPA_PSK prio=300 status=0
E/WifiStateMachine( 1032):  ConnectModeState CMD_ADD_OR_UPDATE_NETWORK uid=1000 0 0 "NG700"WPA_PSK prio=300 status=0
E/WifiConfigStore( 1032):  key="NG700"WPA_PSK netId=0 uid=0/1000
D/WifiServerServiceExt( 1032): addOrUpdateNetwork: mThisIsFirstEnableing = false
D/WifiNative-wlan0( 1032): doBoolean: SET_NETWORK 0 ssid 4e47373030
W/ResourcesManager( 6445): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
D/WifiNative-wlan0( 1032): SET_NETWORK 0 ssid 4e47373030: returned true
D/WifiNative-wlan0( 1032): doBoolean: SET_NETWORK 0 key_mgmt WPA-PSK
D/WifiNative-wlan0( 1032): SET_NETWORK 0 key_mgmt WPA-PSK: returned true
D/WifiNative-wlan0( 1032): doBoolean: SET_NETWORK 0 proto WPA RSN
D/AuthorizationBluetoothService( 2119): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
D/WifiNative-wlan0( 1032): SET_NETWORK 0 proto WPA RSN: returned true
D/WifiNative-wlan0( 1032): doBoolean: SET_NETWORK 0 pairwise TKIP CCMP
D/WifiNative-wlan0( 1032): SET_NETWORK 0 pairwise TKIP CCMP: returned true
D/WifiNative-wlan0( 1032): doBoolean: SET_NETWORK 0 group WEP40 WEP104 TKIP CCMP
D/WifiNative-wlan0( 1032): SET_NETWORK 0 group WEP40 WEP104 TKIP CCMP: returned true
D/WifiNative-wlan0( 1032): doBoolean: SET_NETWORK 0 priority 300
D/WifiNative-wlan0( 1032): SET_NETWORK 0 priority 300: returned true
E/WifiConfigStore( 1032): will read network variables netId=0
E/WifiConfigStore( 1032): writeIpAndProxyConfigurationsOnChange: "NG700" -> "NG700" path: /data/misc/wifi/ipconfig.txt
E/WifiConfigStore( 1032):  writeKnownNetworkHistory() num networks:1 needWrite=false
D/WiFiOffLoadUpdatePriority( 6307):  ssid "NG700" prio 300
D/WiFiOffLoadUpdatePriority( 6307): configuration updated: 0
E/WifiStateMachine( 1032):  DisconnectedState CMD_SAVE_CONFIG uid=1000 0 0
E/WifiStateMachine( 1032):  ConnectModeState CMD_SAVE_CONFIG uid=1000 0 0
D/WifiNative-wlan0( 1032): doBoolean: SAVE_CONFIG
,D/WifiNative-wlan0( 1032): SAVE_CONFIG: returned true
D/WiFiOffLoadUpdatePriority( 6307): configuration saved: true
I/ActivityManager( 1032): Killing 5593:com.android.gallery3d/u0a27 (adj 15): empty #17
D/LGDMClient( 3990): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
D/LGDMClient( 3990): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,W/libprocessgroup( 1032): failed to open /acct/uid_10027/pid_5593/cgroup.procs: No such file or directory
W/ContextImpl( 3990): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
W/ContextImpl( 3990): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
D/LGDMClient( 3990): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=3, isUserType=1
D/PostponalbeReceiver( 5227): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
D/LGDMClient( 3990): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
D/LGDMClient( 3990): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
,I/PCSuite ( 6373): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
,D/PCSuite ( 6373): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 6373): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 6307): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6307): MCCMNC not supported: null
I/ActivityManager( 1032): Start proc com.lge.qremote for broadcast com.lge.qremote/.settings.WiFiStateReceiver: pid=6466 uid=10112 gids={50112, 9997, 1028, 1015, 3003, 3002} abi=armeabi
,I/art     (  377): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 423us total 19.601ms
,I/art     (  377): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 353us total 17.584ms
W/ResourcesManager( 6466): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
I/art     (  377): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 289us total 15.211ms
,D/QRemote ( 6466): [QRemoteApplication.java:230:onCreate()] oooooo QRemoteApp onCreate....
,D/QRemote ( 6466): [CarrierUtils.java:858:getHardwareSettings()] oooooo qremote android.os.Build.MODEL = LG-D855
,I/QRemote ( 6466): [CarrierUtils.java:859:getHardwareSettings()] oooooo getCountry :: EU
I/QRemote ( 6466): [CarrierUtils.java:860:getHardwareSettings()] oooooo getCarrier :: OPEN
I/QRemote ( 6466): [CarrierUtils.java:861:getHardwareSettings()] oooooo getArea :: COM
D/QRemote ( 6466): [CarrierUtils.java:862:getHardwareSettings()] oooooo Loading Config...
D/QRemote ( 6466): [CarrierUtils.java:876:getHardwareSettings()] oooooo qremote configuration file = R.xml.qremote_conf
D/QRemote ( 6466): [QRemoteApplication.java:701:updateWidget()] oooooo Widget count is [1]. send broadcast
D/QRemote ( 6466): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,D/QRemote ( 6466): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 6466): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,D/QRemote ( 6466): [QRemoteService.java:196:onCreate()] oooooo 140526:onCreate
,V/[BNRBootReceiver]( 5969): boot receiver action = android.net.wifi.p2p.CONNECTION_STATE_CHANGE
D/BNRAndroBeam( 5969): [BnR DirectBeam] Android Direct Beam(NFC) Connection changed
D/QRemote ( 6466): [QRemoteService.java:217:onStartCommand()] oooooo 140526:onStartCommand:action:action.application.oncreate. startId:1, flags:0
V/[BNRBootReceiver]( 5969): Boot Receiver Return
D/PostponalbeReceiver( 5227): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
V/WiFiOffLoadBroadcast( 6307): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6307): MCCMNC not supported: null
D/QRemote ( 6466): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,D/QRemote ( 6466): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 6466): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
V/QRemote ( 6466): [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
D/QRemote ( 6466): [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
D/QRemote ( 6466): [QRemoteApplication.java:86:getControlManager()] oooooo mControlManager is null. make new RemoteControlManager
,D/LgDataFeature( 6466): LgDataFeature() Constructor: none
D/LgDataFeature( 6466): LgDataFeature() Constructor Done, null
,V/SoundPool( 6466): SoundPool constructor: maxChannels=2, attr.usage=13, attr.flags=0x0, attr.tags=
V/SoundPool( 6466): load: fd=30, offset=10857164, length=17813, priority=1
V/SoundPool( 6466): create sampleID=1, fd=31, offset=17813 length=10857164
V/SoundPool( 6466): doLoad: loading sample sampleID=1
I/QRemote ( 6466): [RemoteControlManager.java:157:onBindIRService()] oooooo bind
V/SoundPool( 6466): Start decode
V/MediaPlayer[Native]( 6466): decode(31, 10857164, 17813)
,V/MediaPlayerService(  320): decode(24, 10857164, 17813)
W/BrunchPlayerTypeImpl(  320): [SelectPlayer] LocalType
W/BrunchPlayerTypeImpl(  320): [getMediaType] EXTEND_MEDIA_MIMETYPE = application/ogg
W/BrunchPlayerTypeImpl(  320): [FindUsePlayer] type = [application/ogg]
W/BrunchPlayerTypeImpl(  320): [FindUsePlayer] componentName = [9101]
W/MediaPlayerFactory(  320): [getPlayerType:fd] nType = 3
V/MediaPlayerService(  320): player type = 3
V/AwesomePlayer(  320): AwesomePlayer create()
,V/AwesomePlayer(  320): reset_l() 
V/AwesomePlayer(  320): cancelPlayerEvents
,V/AwesomePlayer(  320): setAudioSink() 
V/AwesomePlayer(  320): reset_l() 
V/AudioCache(  320): notify(0xb5474d80, 8, 0, 0)
V/AudioCache(  320): ignored
D/QRemote ( 6466): [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
V/AwesomePlayer(  320): cancelPlayerEvents
D/Utils   (  320): printFileName fd(25) -> /data/preload/LGQRemote/LGQRemote.apk
V/AwesomePlayer(  320): setDataSource_l dataSource
D/UEI.SmartControl( 5887): QS Service created
V/LGParserOSAL(  320): SniffLGParser start
V/LGParserOSAL(  320): MainType:5, SubType=0
V/LGParserOSAL(  320): #### check Mime : application/ogg
V/LGParserOSAL(  320): Detector mimeType:application/ogg, Confidence=1.000000
E/MediaExtractor(  320): Use LGExtractor :application/ogg 
E/QRemote ( 6466): [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
D/QRemote ( 6466): [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
,V/LGParserOSAL(  320): supported mime: application/ogg
V/AwesomePlayer(  320): setDataSource_l() extractor countTracks=1
V/LGMDMManager( 6466): Create singleton instance
V/AwesomePlayer(  320): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer(  320): mBitrate = -1 bits/sec
V/AwesomePlayer(  320): AudioTrack Setting
V/AwesomePlayer(  320): AudioTrack Setting channelCount = 2
V/AwesomePlayer(  320): setAudioSource() 
V/MediaPlayerService(  320): prepare
V/AwesomePlayer(  320): prepareAsync_l() 
V/MediaPlayerService(  320): wait for prepare
,V/AwesomePlayer(  320): onPrepareAsyncEvent() 
V/AwesomePlayer(  320): initAudioDecoder() 
W/Utils   (  320): bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
V/AudioSystem(  320): isOffloadSupported()
I/UEI.SmartControl( 5887): Service initServices...
V/AudioPolicyManager(  320): isOffloadSupported: SR=48000, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
D/UEI.SmartControl( 5887): QS start get config
D/AudioPolicyManager(  320): isOffloadSupported: stream_type != MUSIC, returning false
I/AudioFlinger(  320): isAudioPlaybackHookOn() false
V/AwesomePlayer(  320): getUseOffload() = 0 
V/OMXCodec(  320): OMXCodec::Create
V/OMXCodec(  320): findMatchingCodecs()
V/OMXCodec(  320): matching 'OMX.google.vorbis.decoder' quirks 0x00000000
V/OMXCodec(  320): matchingCodecs.size()=1
V/OMXCodec(  320): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
D/OMXCodec(  320): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
V/LGCodecAdapter(  320): LG Codec Adapter start
V/OMXCodec(  320): OMXCodec Createtor
V/OMXCodec(  320): setComponentRole
V/OMXCodec(  320): configureCodec protected=0
V/LGCodecAdapter(  320): called getLGCodecSpecificData
V/LGCodecOSAL(  320): Called LGgetCodecSpecificDataMETA
V/LGCodecOSAL(  320): Called LGconfigureCodecMETA
V/LGCodecOSAL(  320): Called LGconfigureCodecMSG
V/LGCodecOSAL(  320): Not support LGCodec
V/OMXCodec(  320): [OMX.google.vorbis.decoder] initOutputFormat()
V/OMXCodec(  320): Codec outputs a different number of channels than the input stream contains (contains 2 channels, codec outputs 1 channels).
V/OMXCodec(  320): Codec outputs at different sampling rate than what the input stream contains (contains data at 48000 Hz, codec outputs 44100 Hz)
I/AwesomePlayer(  320): Could not offload audio decode, try pcm offload
W/Utils   (  320): bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
V/AudioSystem(  320): isOffloadSupported()
V/AudioPolicyManager(  320): isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
D/AudioPolicyManager(  320): isOffloadSupported: stream_type != MUSIC, returning false
V/OMXCodec(  320): [OMX.google.vorbis.decoder] start mState=1
V/OMXCodec(  320): init()
V/OMXCodec(  320): [OMX.google.vorbis.decoder] setState mState=1 , newState=2
V/OMXCodec(  320): allocateBuffers
V/OMXCodec(  320): allocateBuffersOnPort portIndex=0
V/OMXCodec(  320): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
V/OMXCodec(  320): [OMX.google.vorbis.decoder] allocated buffer 0xb57c40b0 on input port
V/OMXCodec(  320): [OMX.google.vorbis.decoder] allocated buffer 0xb57c41a0 on input port
V/OMXCodec(  320): [OMX.google.vorbis.decoder] allocated buffer 0xb57c4240 on input port
V/OMXCodec(  320): [OMX.google.vorbis.decoder] allocated buffer 0xb57c4290 on input port
V/OMXCodec(  320): allocateBuffersOnPort portIndex=1
V/OMXCodec(  320): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
V/OMXCodec(  320): [OMX.google.vorbis.decoder] allocated buffer 0xb57c4330 on output port
V/OMXCodec(  320): [OMX.google.vorbis.decoder] allocated buffer 0xb57c44c0 on output port
V/OMXCodec(  320): [OMX.google.vorbis.decoder] allocated buffer 0xb57c4510 on output port
V/OMXCodec(  320): [OMX.google.vorbis.decoder] allocated buffer 0xb57c4560 on output port
V/OMXCodec(  320): init() mAsyncCompletion wait!!! 
V/OMXCodec(  320): [OMX.google.vorbis.decoder] onStateChange 2
V/OMXCodec(  320): [OMX.google.vorbis.decoder] Now Idle.
V/OMXCodec(  320): [OMX.google.vorbis.decoder] setState mState=2 , newState=3
V/OMXCodec(  320): init() mAsyncCompletion wait!!! 
V/OMXCodec(  320): [OMX.google.vorbis.decoder] onStateChange 3
V/OMXCodec(  320): [,OMX.google.vorbis.decoder] Now Executing.
V/OMXCodec(  320): [OMX.google.vorbis.decoder] setState mState=3 , newState=4
V/OMXCodec(  320): init() mAsyncCompletion wait free! 
V/AwesomePlayer(  320): finishAsyncPrepare_l() 
V/AudioCache(  320): notify(0xb5474d80, 5, 0, 0)
V/AudioCache(  320): ignored
V/AudioCache(  320): notify(0xb5474d80, 1, 0, 0)
V/AudioCache(  320): prepared
V/AudioCache(  320): wait - success
V/MediaPlayerService(  320): start
V/AwesomePlayer(  320): play_l() 
V/AwesomePlayer(  320): play_l m_isDivXDRM=0, bpurchasefile:0
V/AwesomePlayer(  320): createAudioPlayer_l
V/AwesomePlayer(  320): seekAudioIfNecessary_l() 
V/AwesomePlayer(  320): startAudioPlayer_l() 
D/AudioPlayer(  320): start of Playback, useOffload 0
V/OMXCodec(  320): [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
V/OMXCodec(  320): [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
V/OMXCodec(  320): [OMX.google.vorbis.decoder] OMX_EventPortSettingsChanged(port=1, data2=0x00000000)
V/OMXCodec(  320): [OMX.google.vorbis.decoder] PORT_SETTINGS_CHANGED(1)
V/OMXCodec(  320): [OMX.google.vorbis.decoder] setState mState=4 , newState=7
V/OMXCodec(  320): [OMX.google.vorbis.decoder] disablePortAsync portIndex=1
V/OMXCodec(  320): [OMX.google.vorbis.decoder] sending OMX_CommandPortDisable(1)
V/OMXCodec(  320): [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
V/OMXCodec(  320): [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3044819760
V/OMXCodec(  320): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
V/OMXCodec(  320): [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3044820160
V/OMXCodec(  320): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
V/OMXCodec(  320): [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3044820240
V/OMXCodec(  320): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
V/OMXCodec(  320): [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3044820320
V/OMXCodec(  320): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
V/OMXCodec(  320): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
V/OMXCodec(  320): [OMX.google.vorbis.decoder] initOutputFormat()
V/OMXCodec(  320): [OMX.google.vorbis.decoder] reconfig handling, formatHasNotablyChanged
V/OMXCodec(  320): [OMX.google.vorbis.decoder] enablePortAsync portIndex=1
,V/OMXCodec(  320): [OMX.google.vorbis.decoder] sending OMX_CommandPortEnable(1)
V/OMXCodec(  320): allocateBuffersOnPort portIndex=1
V/OMXCodec(  320): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
V/OMXCodec(  320): [OMX.google.vorbis.decoder] allocated buffer 0xb57c4510 on output port
V/OMXCodec(  320): [OMX.google.vorbis.decoder] allocated buffer 0xb57c44c0 on output port
V/OMXCodec(  320): [OMX.google.vorbis.decoder] allocated buffer 0xb57c4330 on output port
V/OMXCodec(  320): [OMX.google.vorbis.decoder] allocated buffer 0xb57c47e0 on output port
V/OMXCodec(  320): [OMX.google.vorbis.decoder] PORT_ENABLED(1)
V/OMXCodec(  320): [OMX.google.vorbis.decoder] setState mState=7 , newState=4
V/AudioCache(  320): open(48000, 2, 0x0, 1, 4)
V/AudioCache(  320): notify(0xb5474d80, 6, 0, 0)
V/AudioCache(  320): ignored
V/MediaPlayerService(  320): wait for playback complete
V/AudioCache(  320): write(0xb14ba000, 4096)
V/AudioCache(  320): memcpy(0xab406000, 0xb14ba000, 4096)
V/AudioCache(  320): write(0xb14ba000, 4096)
V/AudioCache(  320): memcpy(0xab407000, 0xb14ba000, 4096)
V/AudioCache(  320): write(0xb14ba000, 4096)
V/AudioCache(  320): memcpy(0xab408000, 0xb14ba000, 4096)
V/AudioCache(  320): write(0xb14ba000, 4096)
V/AudioCache(  320): memcpy(0xab409000, 0xb14ba000, 4096)
V/AudioCache(  320): write(0xb14ba000, 4096)
V/AudioCache(  320): memcpy(0xab40a000, 0xb14ba000, 4096)
V/AudioCache(  320): write(0xb14ba000, 4096)
V/AudioCache(  320): memcpy(0xab40b000, 0xb14ba000, 4096)
V/AudioCache(  320): write(0xb14ba000, 4096)
V/AudioCache(  320): memcpy(0xab40c000, 0xb14ba000, 4096)
V/AudioCache(  320): write(0xb14ba000, 4096)
V/AudioCache(  320): memcpy(0xab40d000, 0xb14ba000, 4096)
V/AudioCache(  320): write(0xb14ba000, 4096)
V/AudioCache(  320): memcpy(0xab40e000, 0xb14ba000, 4096)
V/AudioCache(  320): write(0xb14ba000, 4096)
V/AudioCache(  320): memcpy(0xab40f000, 0xb14ba000, 4096)
V/AudioCache(  320): write(0xb14ba000, 4096)
V/AudioCache(  320): memcpy(0xab410000, 0xb14ba000, 4096)
V/AudioCache(  320): write(0xb14ba000, 4096)
V/AudioCache(  320): memcpy(0xab411000, 0xb14ba000, 4096)
V/AudioCache(  320): write(0xb14ba000, 4096)
V/AudioCache(  320): memcpy(0xab412000, 0xb14ba000, 4096)
V/AudioCache(  320): write(0xb14ba000, 4096)
V/AudioCache(  320): memcpy(0xab413000, 0xb14ba000, 4096)
V/AudioCache(  320): write(0xb14ba000, 4096)
V/AudioCache(  320): memcpy(0xab414000, 0xb14ba000, 4096)
V/AudioCache(  320): write(0xb14ba000, 4096)
V/AudioCache(  320): memcpy(0xab415000, 0xb14ba000, 4096)
V/AudioCache(  320): write(0xb14ba000, 4096)
V/AudioCache(  320): memcpy(0xab416000, 0xb14ba000, 4096)
V/AudioCache(  320): write(0xb14ba000, 4096)
V/AudioCache(  320): memcpy(0xab417000, 0xb14ba000, 4096)
V/AudioCache(  320): write(0xb14ba000, 4096)
V/AudioCache(  320): memcpy(0xab418000, 0xb14ba000, 4096)
V/AudioCache(  320): write(0xb14ba000, 4096)
V/AudioCache(  320): memcpy(0xab419000, 0xb14ba000, 4096)
V/AudioCache(  320): write(0xb14ba000, 4096)
V/AudioCache(  320): memcpy(0xab41a000, 0xb14ba000, 4096)
V/AudioCache(  320): write(0xb14ba000, 4096)
V/AudioCache(  320): memcpy(0xab41b000, 0xb14ba000, 4096)
,V/AudioCache(  320): write(0xb14ba000, 4096)
V/AudioCache(  320): memcpy(0xab41c000, 0xb14ba000, 4096)
V/AudioCache(  320): write(0xb14ba000, 4096)
V/AudioCache(  320): memcpy(0xab41d000, 0xb14ba000, 4096)
V/AudioCache(  320): write(0xb14ba000, 4096)
V/AudioCache(  320): memcpy(0xab41e000, 0xb14ba000, 4096)
V/AudioCache(  320): write(0xb14ba000, 4096)
V/AudioCache(  320): memcpy(0xab41f000, 0xb14ba000, 4096)
V/AudioCache(  320): write(0xb14ba000, 4096)
V/AudioCache(  320): memcpy(0xab420000, 0xb14ba000, 4096)
V/AudioCache(  320): write(0xb14ba000, 4096)
V/AudioCache(  320): memcpy(0xab421000, 0xb14ba000, 4096)
V/AudioCache(  320): write(0xb14ba000, 4096)
V/AudioCache(  320): memcpy(0xab422000, 0xb14ba000, 4096)
V/AudioCache(  320): write(0xb14ba000, 4096)
V/AudioCache(  320): memcpy(0xab423000, 0xb14ba000, 4096)
V/AudioCache(  320): write(0xb14ba000, 4096)
V/AudioCache(  320): memcpy(0xab424000, 0xb14ba000, 4096)
V/AudioCache(  320): write(0xb14ba000, 4096)
V/AudioCache(  320): memcpy(0xab425000, 0xb14ba000, 4096)
V/AudioCache(  320): write(0xb14ba000, 4096)
V/AudioCache(  320): memcpy(0xab426000, 0xb14ba000, 4096)
V/AudioCache(  320): write(0xb14ba000, 4096)
V/AudioCache(  320): memcpy(0xab427000, 0xb14ba000, 4096)
V/AudioCache(  320): write(0xb14ba000, 4096)
V/AudioCache(  320): memcpy(0xab428000, 0xb14ba000, 4096)
V/AudioCache(  320): write(0xb14ba000, 4096)
V/AudioCache(  320): memcpy(0xab429000, 0xb14ba000, 4096)
V/AudioCache(  320): write(0xb14ba000, 4096)
V/AudioCache(  320): memcpy(0xab42a000, 0xb14ba000, 4096)
,V/AudioCache(  320): write(0xb14ba000, 4096)
V/AudioCache(  320): memcpy(0xab42b000, 0xb14ba000, 4096)
V/AudioCache(  320): write(0xb14ba000, 4096)
V/AudioCache(  320): memcpy(0xab42c000, 0xb14ba000, 4096)
V/AudioCache(  320): write(0xb14ba000, 4096)
V/AudioCache(  320): memcpy(0xab42d000, 0xb14ba000, 4096)
V/AudioCache(  320): write(0xb14ba000, 4096)
V/AudioCache(  320): memcpy(0xab42e000, 0xb14ba000, 4096)
V/AudioCache(  320): write(0xb14ba000, 4096)
V/AudioCache(  320): memcpy(0xab42f000, 0xb14ba000, 4096)
V/AudioCache(  320): write(0xb14ba000, 4096)
V/AudioCache(  320): memcpy(0xab430000, 0xb14ba000, 4096)
V/AudioCache(  320): write(0xb14ba000, 4096)
V/AudioCache(  320): memcpy(0xab431000, 0xb14ba000, 4096)
V/AudioCache(  320): write(0xb14ba000, 4096)
V/AudioCache(  320): memcpy(0xab432000, 0xb14ba000, 4096)
V/AudioCache(  320): write(0xb14ba000, 4096)
V/AudioCache(  320): memcpy(0xab433000, 0xb14ba000, 4096)
V/AudioCache(  320): write(0xb14ba000, 4096)
V/AudioCache(  320): memcpy(0xab434000, 0xb14ba000, 4096)
V/AudioCache(  320): write(0xb14ba000, 4096)
V/AudioCache(  320): memcpy(0xab435000, 0xb14ba000, 4096)
V/AudioCache(  320): write(0xb14ba000, 4096)
V/AudioCache(  320): memcpy(0xab436000, 0xb14ba000, 4096)
V/AudioCache(  320): write(0xb14ba000, 4096)
V/AudioCache(  320): memcpy(0xab437000, 0xb14ba000, 4096)
,V/OMXCodec(  320): [OMX.google.vorbis.decoder] No more output data.
V/OMXCodec(  320): [OMX.google.vorbis.decoder] There is no more output data available, not calling fillOutputBuffer
V/AwesomePlayer(  320): postAudioEOS() 
V/AudioCache(  320): write(0xb14ba000, 280)
V/AudioCache(  320): memcpy(0xab438000, 0xb14ba000, 280)
V/AwesomePlayer(  320): postStreamDoneEvent_l() -> status:-1011 
V/AwesomePlayer(  320): onStreamDone
V/AwesomePlayer(  320): MEDIA_PLAYBACK_COMPLETE
V/AudioCache(  320): notify(0xb5474d80, 2, 0, 0)
V/AudioCache(  320): playback complete
V/AwesomePlayer(  320): pause_l() 
V/AudioCache(  320): notify(0xb5474d80, 7, 0, 0)
V/AudioCache(  320): ignored
V/AwesomePlayer(  320): cancelPlayerEvents
D/AudioPlayer(  320): Pause Playback at 1068125
V/AudioCache(  320): wait - success
V/MediaPlayerService(  320): return size 205080, sampleRate=48000, channelCount = 2, format = 1
V/AwesomePlayer(  320): reset_l() 
V/AudioCache(  320): notify(0xb5474d80, 8, 0, 0)
V/AudioCache(  320): ignored
V/AwesomePlayer(  320): cancelPlayerEvents
D/AudioPlayer(  320): reset: mPlaying=0 mReachedEOS=1 useOffload=0
V/OMXCodec(  320): [OMX.google.vorbis.decoder] stop mState=4
V/OMXCodec(  320): [OMX.google.vorbis.decoder] stopOmxComponent_l mState=4
V/OMXCodec(  320): [OMX.google.vorbis.decoder] setState mState=4 , newState=5
V/OMXCodec(  320): [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
V/OMXCodec(  320): [OMX.google.vorbis.decoder] onStateChange 2
V/OMXCodec(  320): [OMX.google.vorbis.decoder] Now Idle.
V/OMXCodec(  320): [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=0
V/OMXCodec(  320): [OMX.google.vorbis.decoder] freeing buffer 0xb57c4290 on port 0
V/OMXCodec(  320): [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=3
V/OMXCodec(  320): [OMX.google.vorbis.decoder] freeing buffer 0xb57c4240 on port 0
V/OMXCodec(  320): [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=2
V/OMXCodec(  320): [OMX.google.vorbis.decoder] freeing buffer 0xb57c41a0 on port 0
V/OMXCodec(  320): [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=1
V/OMXCodec(  320): [OMX.google.vorbis.decoder] freeing buffer 0xb57c40b0 on port 0
V/OMXCodec(  320): [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=0
V/OMXCodec(  320): [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
V/OMXCodec(  320): [OMX.google.vorbis.decoder] freeing buffer 0xb57c47e0 on port 1
,V/OMXCodec(  320): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=3
V/OMXCodec(  320): [OMX.google.vorbis.decoder] freeing buffer 0xb57c4330 on port 1
V/OMXCodec(  320): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=2
V/OMXCodec(  320): [OMX.google.vorbis.decoder] freeing buffer 0xb57c44c0 on port 1
V/OMXCodec(  320): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=1
V/OMXCodec(  320): [OMX.google.vorbis.decoder] freeing buffer 0xb57c4510 on port 1
V/OMXCodec(  320): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
V/OMXCodec(  320): [OMX.google.vorbis.decoder] setState mState=5 , newState=6
V/OMXCodec(  320): [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
V/OMXCodec(  320): [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
V/OMXCodec(  320): [OMX.google.vorbis.decoder] onStateChange 1
V/OMXCodec(  320): [OMX.google.vorbis.decoder] Now Loaded.
V/OMXCodec(  320): [OMX.google.vorbis.decoder] setState mState=6 , newState=1
V/OMXCodec(  320): [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
V/OMXCodec(  320): [OMX.google.vorbis.decoder] stopped in state 1
V/OMXCodec(  320): [OMX.google.vorbis.decoder] ~OMXCodec mstate =1
V/OMXCodec(  320): [OMX.google.vorbis.decoder] setState mState=1 , newState=0
D/AudioPlayer(  320): AudioPlayer releasing audio source
D/AudioPlayer(  320): AudioPlayer done releasing audio source
V/AwesomePlayer(  320): reset_l() 
V/AwesomePlayer(  320): cancelPlayerEvents
V/AwesomePlayer(  320): ~AwesomePlayer call
V/AwesomePlayer(  320): reset_l() 
V/AwesomePlayer(  320): cancelPlayerEvents
V/SoundPool( 6466): close(31)
V/SoundPool( 6466): pointer = 0x9ff3c000, size = 205080, sampleRate = 48000, numChannels = 2
D/QRemote ( 6466): [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
D/QRemote ( 6466): [RemoteAppWidgetProvider.java:486:onUpdate()] oooooo 140510:RetrieveDevices is not complete. Just waiting
,D/QRemote ( 6466): [RemoteAppWidgetProvider.java:499:onUpdate()] oooooo 140514:alarm set after 5000ms:1058
E/QC-QMI  ( 6430): qmi_client [6430] 13: failed to locate client data
E/QC-QMI  (  464): qmuxd: RX on fd=32 returned error=0 errno[2:No such file or directory]
E/QC-QMI  (  464): QMUX qmux_client_id=13 not found in qmux client list, unable to remove
,I/qcom-bluetooth( 6494): /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 58:3f:54:73:64:c0 
,I/qcom-bluetooth( 6495): /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
I/bt_vendor( 6275): bluetooth satus is on
,D/bt_hci_bdroid( 6275): preload
D/bt_userial_mct( 6275): userial_open(port:0)
I/bt_vendor( 6275): bt-vendor : BT_VND_OP_USERIAL_OPEN
I/bt_vendor( 6275): Done intiailizing UART
I/bt_vendor( 6275): Done intiailizing UART
I/bt_userial_mct( 6275): CMD=66, EVT=66, ACL_Out=67, ACL_In=67
I/bt_vendor( 6275): Bluetooth Firmware and transport layer are initialized
I/bt-btu  ( 6275): btu_task received preload complete event
W/bt-l2cap( 6275): L2CAP - L2CA_Register() called for PSM: 0x0001
W/bt-l2cap( 6275): L2CAP - L2CA_Register() called for PSM: 0x001f
D/bt_userial_mct( 6275): Entering userial_read_thread()
W/bt-l2cap( 6275): L2CAP - L2CA_Register() called for PSM: 0x0003
I/        ( 6275): BTE_InitTraceLevels -- TRC_HCI
I/        ( 6275): BTE_InitTraceLevels -- TRC_L2CAP
I/        ( 6275): BTE_InitTraceLevels -- TRC_RFCOMM
I/        ( 6275): BTE_InitTraceLevels -- TRC_AVDT
I/        ( 6275): BTE_InitTraceLevels -- TRC_AVRC
I/        ( 6275): BTE_InitTraceLevels -- TRC_A2D
I/        ( 6275): BTE_InitTraceLevels -- TRC_BNEP
I/        ( 6275): BTE_InitTraceLevels -- TRC_BTM
I/        ( 6275): BTE_InitTraceLevels -- TRC_HID_HOST
I/        ( 6275): BTE_InitTraceLevels -- TRC_GAP
I/        ( 6275): BTE_InitTraceLevels -- TRC_PAN
I/        ( 6275): BTE_InitTraceLevels -- TRC_SDP
I/        ( 6275): BTE_InitTraceLevels -- TRC_GATT
I/        ( 6275): BTE_InitTraceLevels -- TRC_SMP
I/        ( 6275): BTE_InitTraceLevels -- TRC_BTAPP
I/        ( 6275): BTE_InitTraceLevels -- TRC_BTIF
W/bt-btm  ( 6275): btm_decode_ext_features_page Secure conn Controller support Enabled
E/bt-btm  ( 6275): BTM_SecRegister:p_cb_info->p_le_callback == 0xa01d4061 
E/bt-btm  ( 6275): BTM_SecRegister: btm_cb.api.p_le_callback = 0xa01d4061 
,E/bt-btif ( 6275): Calling BTA_HhEnable
E/bt-btif ( 6275): btif_storage_get_adapter_property service_mask:0x2140040
,D/BluetoothAdapterProperties( 6275): Address is:58:3F:54:73:64:C0
D/BluetoothAdapterProperties( 6275): Name is: G3-1
D/BluetoothManagerService( 1032): Bluetooth Adapter name changed to G3-1
W/bt-l2cap( 6275): L2CAP - L2CA_Register() called for PSM: 0x0019
W/bt-l2cap( 6275): L2CAP - L2CA_Register() called for PSM: 0x0017
W/bt-l2cap( 6275): L2CAP - L2CA_Register() called for PSM: 0x001b
W/bt-l2cap( 6275): L2CAP - L2CA_Register() called for PSM: 0x0011
W/bt-l2cap( 6275): L2CAP - L2CA_Register() called for PSM: 0x0013
D/BluetoothManagerService( 1032): Stored Bluetooth name: G3-1
D/BluetoothAdapterProperties( 6275): Scan Mode:20
D/BluetoothAdapterProperties( 6275): Discoverable Timeout:120
D/bt_hci_bdroid( 6275): postload
D/bt_hci_bdroid( 6275): Used up Tx Cmd credits
W/bt-l2cap( 6275): L2CAP - L2CA_Register() called for PSM: 0x000f
D/bt_hci_bdroid( 6275): Used up Tx Cmd credits
D/bt_hci_bdroid( 6275): Used up Tx Cmd credits
E/bt_mct  ( 6275): hci lib postload completed
D/bte_conf( 6275): Device ID record 1 : primary
D/bte_conf( 6275):   vendorId            = 00c4
D/bte_conf( 6275):   vendorIdSource      = 0001
D/bte_conf( 6275):   product             = 13a1
D/bte_conf( 6275):   version             = 1000
D/bte_conf( 6275):   clientExecutableURL = 
D/bte_conf( 6275):   serviceDescription  = 
D/bte_conf( 6275):   documentationURL    = 
D/bte_conf( 6275): bte_load_did_conf no section named DID2.
W/bt-smp  ( 6275): Key(LSB ~ MSB) = 0a 3c a6 fe eb 17 6a 79 a6 1f 0a 0b f9 50 a0 5f 
W/bt-smp  ( 6275): Plain text(LSB ~ MSB) = d3 2e 76 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 6275): Encrypted text(LSB ~ MSB) = f7 a1 bd 26 34 f2 40 4a af f8 9b 2a a7 5e c0 ac 
W/bt-btm  ( 6275): Stopping oneshot timer
W/sh      ( 6499): type=1400 audit(0.0:159): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6848 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
W/sh      ( 6499): type=1400 audit(0.0:160): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6848 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
D/BluetoothAdapterState( 6275): CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
D/BluetoothAdapterProperties( 6275): ScanMode =  20
D/BluetoothAdapterProperties( 6275): State =  11
D/BluetoothAdapterProperties( 6275): mDiscoverableTimeout = 120
V/LGBluetoothServiceAdapter( 6275): [BTUI] state:11, scanmode:20, timeout:120
D/BluetoothAdapterProperties( 6275): Setting state to 12
I/BluetoothAdapterState( 6275): Bluetooth adapter state changed: 11-> 12
D/BluetoothManagerService( 1032): Message: 60
D/BluetoothManagerService( 1032): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
D/BluetoothManagerService( 1032): Broadcasting onBluetoothStateChange(true) to 5 receivers.
I/BluetoothAdapterState( 6275): Entering On State
D/BluetoothHeadset( 1862): onBluetoothStateChange: up=true
D/BluetoothA2dp( 1032): onBluetoothStateChange: up=true
D/BluetoothHeadset( 1032): onBluetoothStateChange: up=true
D/BluetoothPanServiceJni( 6275): control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
D/btif_config_util( 6275): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
D/BluetoothHeadset( 1862): onBluetoothStateChange: up=true
D/LGBluetoothServiceAdapter( 6275): [BTUI] OnState
D/LGBluetoothServiceAdapter( 6275): [BTUI]         global_name: G3-1
D/LGBluetoothServiceAdapter( 6275): [BTUI]         local_name: G3-1
D/BluetoothHeadset( 1862): onBluetoothStateChange: up=true
D/BluetoothAdapterService( 6275): [BTUI] autoConnect() : not allowed
,D/BluetoothManagerService( 1032): BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
E/BluetoothManagerService( 1032): Fail to bind to: Intent { act=android.bluetooth.IQBluetooth }
D/BluetoothManagerService( 1032): Bluetooth State Change Intent: 11 -> 12
D/LGBluetoothAPIService( 1953): [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
D/LGBluetoothAPIService( 1953): Message: 1
D/LGBluetoothAPIService( 1953): MESSAGE_BOOT_COMPLETED
I/[SystemUI]BluetoothHandler( 1461): Receive : BluetoothAdapter.ACTION_STATE_CHANGED
D/BluetoothManagerService( 1032): Message: 40
D/BluetoothManagerService( 1032): MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
I/LGBluetoothAPIService( 1953): [BTUI] LGBluetoothAPIService Binding Success
W/bt-smp  ( 6275): Key(LSB ~ MSB) = 0a 3c a6 fe eb 17 6a 79 a6 1f 0a 0b f9 50 a0 5f 
W/bt-smp  ( 6275): Plain text(LSB ~ MSB) = f0 cb 76 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 6275): Encrypted text(LSB ~ MSB) = 5d c7 e2 e8 33 d3 c4 38 a8 3c 04 de 53 7e 0c ba 
W/bt-btm  ( 6275): Stopping oneshot timer
,I/BluetoothMapService( 6275): onReceive: android.bluetooth.adapter.action.STATE_CHANGED
D/BluetoothMapService( 6275): STATE_ON
W/bt-smp  ( 6275): Key(LSB ~ MSB) = 0a 3c a6 fe eb 17 6a 79 a6 1f 0a 0b f9 50 a0 5f 
W/bt-smp  ( 6275): Plain text(LSB ~ MSB) = 9f 0e 46 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 6275): Encrypted text(LSB ~ MSB) = 85 6a b1 5a ac 00 cb cd 52 25 4e de 09 d9 5f ac 
W/bt-btm  ( 6275): Stopping oneshot timer
,W/ContextImpl( 6307): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
D/LGBluetoothAPIServer( 6275): [BTUI] onCreate()
D/LGBluetoothAPIServer( 6275): [BTUI] onBind()
D/LGBluetoothAPIService( 1953): [BTUI] LGBluetoothAPIServiceConnection: connected to LGBluetoothAPIAdapter
D/LGBluetoothAPIService( 1953): Message: 100
D/LGBluetoothAPIService( 1953): MESSAGE_BLUETOOTH_SERVICE_CONNECTED
I/qcom-bt-wlan-coex( 6505): /system/etc/init.qcom.coex.sh: btwlancoex/abtfilt not available 
W/bt-smp  ( 6275): Key(LSB ~ MSB) = 0a 3c a6 fe eb 17 6a 79 a6 1f 0a 0b f9 50 a0 5f 
W/bt-smp  ( 6275): Plain text(LSB ~ MSB) = 40 b7 52 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 6275): Encrypted text(LSB ~ MSB) = 7e 07 46 45 24 e3 50 0c 34 d7 72 a2 0d 81 89 f9 
W/bt-btm  ( 6275): Stopping oneshot timer
,D/BluetoothAdapterService( 6275): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@22bdc9dc
V/BluetoothPbapService( 6275): Pbap Service onCreate
V/BluetoothPbapService( 6275): Starting PBAP service
D/LGBluetoothPbapAdapter( 6275): [BTUI] getInstance : create
V/BluetoothMapService( 6275): Handler(): got msg=1
D/BluetoothMapMasInstance( 6275): Map Service startRfcommSocketListener
D/LGBluetoothDeviceModeControllManager( 6275): [BTUI] checkDeviceModeAndSet, sinkMode : false
W/bt-smp  ( 6275): Key(LSB ~ MSB) = 0a 3c a6 fe eb 17 6a 79 a6 1f 0a 0b f9 50 a0 5f 
W/bt-smp  ( 6275): Plain text(LSB ~ MSB) = 71 47 43 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 6275): Encrypted text(LSB ~ MSB) = 0e 23 be 0a 2f f8 a1 2c 89 9d 1e dc 74 a6 ab 4e 
W/bt-btm  ( 6275): Stopping oneshot timer
V/BluetoothPbapService( 6275): action: android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothPbapService( 6275): state: 12
V/BluetoothPbapReceiver( 6275): PbapReceiver onReceive 
V/BluetoothPbapReceiver( 6275): ***********action = android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothPbapReceiver( 6275): ***********state = 12
V/BluetoothPbapService( 6275): Handler(): got msg=1
V/BluetoothPbapService( 6275): Pbap Service startRfcommSocketListener
D/BluetoothMapMasInstance( 6275): MAS initSocket()
D/BluetoothMapMasInstance( 6275):   masId = 00
D/BluetoothMapMasInstance( 6275):   msgTypes = 0e
D/BluetoothMapMasInstance( 6275):   masName = SMS/MMS
D/BluetoothMapMasInstance( 6275):   SDP string = 000eSMS/MMS
V/BluetoothPbapService( 6275): Pbap Service initSocket
D/BluetoothManagerService( 1032): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1032): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
W/BluetoothAdapter( 6275): getBluetoothService() called with no BluetoothManagerCallback
W/BluetoothAdapter( 6275): getBluetoothService() called with no BluetoothManagerCallback
,D/LocalBluetoothProfileManager( 6307): Adding local A2DP profile
D/LGBluetoothServiceAdapter( 6275): [BTUI] createSocketChannel FD=73 mFd=0
V/BluetoothMapMasInstance( 6275): Succeed to create listening socket 
D/BluetoothMapMasInstance( 6275): Accepting socket connection...
D/LGBluetoothServiceAdapter( 6275): [BTUI] createSocketChannel FD=75 mFd=73
V/BluetoothPbapService( 6275): Succeed to create listening socket 
V/BluetoothPbapService( 6275): Accepting socket connection...
D/BluetoothManagerService( 1032): Message: 30
D/LocalBluetoothProfileManager( 6307): Adding local HEADSET profile
D/BluetoothManagerService( 1032): Message: 30
,D/BluetoothManagerService( 1032): Message: 30
D/BluetoothManagerService( 1032): Message: 30
D/LocalBluetoothProfileManager( 6307): Adding local MAP profile
,D/BluetoothMap( 6307): Create BluetoothMap proxy object
D/BluetoothManagerService( 1032): Message: 30
D/BluetoothManagerService( 1032): Message: 30
D/LocalBluetoothProfileManager( 6307): LocalBluetoothProfileManager construction complete
V/BluetoothPbapService( 6275): Pbap Service onBind
D/LGBluetoothUserBindClient( 6307): [BTUI] initUserBindClient
W/ContextImpl( 6307): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.android.settings.bluetooth.LGBluetoothUserBindClient.initUserBindClient:90 com.android.settings.bluetooth.LGBluetoothUserBindClient.<init>:55 com.android.settings.bluetooth.LGBluetoothUserBindClient.getInstance:47 
,D/DockEventReceiver( 6307): finishStartingService: stopping service
D/BluetoothA2dp( 6307): Proxy object connected
D/A2dpProfile( 6307): Bluetooth service connected
D/BluetoothHeadset( 6307): Proxy object connected
D/HeadsetProfile( 6307): Bluetooth service connected
,D/BluetoothInputDevice( 6307): Proxy object connected
D/HidProfile( 6307): Bluetooth service connected
D/BluetoothPan( 6307): BluetoothPAN Proxy object connected
D/PanProfile( 6307): Bluetooth service connected
D/BluetoothMap( 6307): Proxy object connected
D/MapProfile( 6307): Bluetooth service connected
D/BluetoothMap( 6307): getConnectedDevices()
V/BluetoothMapService( 6275): getConnectedDevices()
D/BluetoothPbap( 6307): Proxy object connected
D/PbapServerProfile( 6307): Bluetooth service connected
D/LGBluetoothUserBindClient( 6307): [BTUI] onServiceConnected
D/BluetoothPermissionRequest( 6307): onReceive
D/LGBluetoothFeatureConfig( 6307): isPrivacyLogsEnabled : true
D/LGBluetoothUtils( 6307): [BTUI] FileNotFound: readProperty
D/LGBluetoothResetSettingReceiver( 6307): return without doing reset settings.
,V/BluetoothOppReceiver( 6275): Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_ON
I/LGBluetoothOppAdapter( 6275): [BTUI] startOppService()
D/BluetoothAdapterProperties( 6275): Discoverable Timeout:120
D/LGBluetoothDeviceModeControllManager( 6275): adapterPropertyChangedCallback on  LGAdapter : do nothing - 9
D/BluetoothAdapterProperties( 6275): Scan Mode:21
D/LGBluetoothDeviceModeControllManager( 6275): getDeviceMode  deviceMode 0
I/UEI.SmartControl( 5887): Supports setup maps: true
D/UEI.SmartControl( 5887): QS start statue = true Error code = 0
I/UEI.SmartControl( 5887): QS version = v2.7.10.1_RC1
I/UEI.SmartControl( 5887): QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
I/UEI.SmartControl( 5887): ### init IR Blaster...
,V/BluetoothOppManager( 6275): restoreApplicationData! falsefalsenullnull
D/serial_port( 5887): Configuring serial port
E/UEI.SmartControl( 5887): UEIBLaster setting for 616
I/UEI.SmartControl( 5887): Setting serial record hearder size = 2
I/UEI.SmartControl( 5887): configuring settings for MAXQ616
I/UEI.SmartControl( 5887): Get version...
D/LGBluetoothFeatureConfig( 6275): isPrivacyLogsEnabled : true
V/BtOppService( 6275): onCreate
,V/BluetoothOppNotification( 6275): send message
V/BtOppService( 6275): Starting RfcommListener
D/UEI.SmartControl( 5887): serial port data available: 21
D/BluetoothOppPreference( 6275): Dumping Names:  
D/BluetoothOppPreference( 6275): {}
D/BluetoothOppPreference( 6275): Dumping Channels:  
D/BluetoothOppPreference( 6275): {}
V/BtOppService( 6275): onStartCommand
V/BtOppService( 6275): pendingUpdate is true keepUpdateThread is false sListenStarted is true
V/BluetoothFtpReceiver( 6275): BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothFtpReceiver( 6275): BluetoothFtpReceiver Start Service
,V/BluetoothOppNotification( 6275): new notify threadi!
V/BluetoothOppNotification( 6275): send delay message
V/BtOppService( 6275): start RfcommListener
V/BtOppService( 6275): RfcommListener started
V/BtOppRfcommListener( 6275): Starting RFCOMM listener....
D/BluetoothManagerService( 1032): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
W/BluetoothAdapter( 6275): getBluetoothService() called with no BluetoothManagerCallback
D/LGBluetoothServiceAdapter( 6275): [BTUI] createSocketChannel FD=78 mFd=75
V/BtOppRfcommListener( 6275): Started RFCOMM listener....
I/BtOppRfcommListener( 6275): Accept thread started.
V/BtOppRfcommListener( 6275): Accepting connection...
V/BtOppService( 6275): Deleted complete outbound shares, number =  0
V/BluetoothOppProvider( 6275): starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
,V/BluetoothOppProvider( 6275): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
V/BtOppService( 6275): Deleted complete inbound failed shares, number = 0
V/BluetoothOppProvider( 6275): starting query, database is not null; projection[0] is _id; selection is direction=1 AND status=200 AND visibility=1; selectionArgs is null; sort is _id.
D/BluetoothAdapterService( 6275): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@22bdc9dc
V/BluetoothFtpService( 6275): Ftp Service onCreate
I/BluetoothFtpService( 6275): Ftp Service onCreate
V/BluetoothFtpService( 6275): Ftp Service onStartCommand
V/BluetoothFtpService( 6275): action: android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothFtpService( 6275): Starting Listening on sockets
V/BluetoothOppProvider( 6275): created cursor android.database.sqlite.SQLiteCursor@333c9717 on behalf of 
V/BluetoothSapReceiver( 6275): [BTUI] checkServiceStart
V/BluetoothSapReceiver( 6275): [BTUI] region:EU country:EU
V/BluetoothSapReceiver( 6275): SapReceiver onReceive 
V/BluetoothSapReceiver( 6275): action = android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothSapReceiver( 6275):  Bluetooth Adapter state = 12
V/BluetoothSapReceiver( 6275): Calling SAP service start service with action = null
V/BtOppService( 6275): ContentObserver received notification
V/BtOppService( 6275): ContentObserver received notification
V/BluetoothFtpService( 6275): Handler(): got msg=1
V/BluetoothFtpService( 6275): Ftp Service startRfcommSocketListener
V/BluetoothFtpService( 6275): Ftp Service initSocket
V/BluetoothOppProvider( 6275): created cursor android.database.sqlite.SQLiteCursor@399f8704 on behalf of 
V/BluetoothOppProvider( 6275): created cursor android.database.sqlite.SQLiteCursor@1527e4ed on behalf of 
V/BluetoothOppNotification( 6275): mUpdateCompleteNotification = true
V/BtOppService( 6275): pendingUpdate is true keepUpdateThread is false sListenStarted is true
V/BluetoothOppProvider( 6275): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
D/UEI.SmartControl( 5887): MAXQ616 A2-X4 software.
I/UEI.SmartControl( 5887): IR Blaster version: 256702256704300002
I/UEI.SmartControl( 5887): QS saving settings...
D/BluetoothManagerService( 1032): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
W/BluetoothAdapter( 6275): getBluetoothService() called with no BluetoothManagerCallback
D/UEI.SmartControl( 5887): IR Blaster version: 25672567
V/BluetoothOppProvider( 6275): created cursor android.database.sqlite.SQLiteCursor@260adf22 on behalf of 
V/BluetoothOppProvider( 6275): starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
V/BluetoothOppNotification( 6275): update too frequent, put in queue
V/BluetoothOppProvider( 6275): created cursor android.database.sqlite.SQLiteCursor@38e98db3 on behalf of 
V/BtOppService( 6275): pendingUpdate is false keepUpdateThread is false sListenStarted is true
V/BluetoothOppNotification( 6275): outbound: succ-0  fail-0
,D/AuthorizationBluetoothService( 2119): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
V/BluetoothOppNotification( 6275): outbound notification was removed.
D/LGBluetoothServiceAdapter( 6275): [BTUI] createSocketChannel FD=80 mFd=78
V/BluetoothOppProvider( 6275): starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
V/BluetoothFtpService( 6275): Succeed to create listening socket on channel 20
V/BluetoothFtpService:RfcommSocketAcceptThread( 6275): Run Accept thread
D/BluetoothAdapterService( 6275): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@22bdc9dc
V/BluetoothSapService( 6275): Sap Service onCreate
D/UEI.SmartControl( 5887): serial port data available: 4
,W/ContextImpl( 5887): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
,I/UEI.SmartControl( 5887): Device manager: loading config....
,D/UEI.SmartControl( 5887): ----------- loading internal config...
E/UEI.SmartControl( 5887): Loading SETTINGS...
D/UEI.SmartControl( 5887): -- Open brand translation xml: brands_translations_ko
I/UEI.SmartControl( 5887): Notify AllClients services are ready: 0
D/UEI.SmartControl( 5887): -----service ready thread exits
,I/art     ( 1032): Explicit concurrent mark sweep GC freed 37742(1936KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 44MB/66MB, paused 1.956ms total 117.294ms
,V/BluetoothOppProvider( 6275): created cursor android.database.sqlite.SQLiteCursor@189bcb6e on behalf of 
V/BluetoothSapService( 6275): action: android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothSapService( 6275): state: 12
V/BluetoothSapService( 6275): Starting SAP server process
V/BluetoothSapService( 6275): SAP Service startRfcommListenerThread
E/UEI.SmartControl( 5887): Services init done
D/UEI.SmartControl( 5887): QS Service init finished
V/BluetoothOppNotification( 6275): inbound: succ-0  fail-0
V/BluetoothSapService( 6275): Sap Service initRfcommSocket
D/BluetoothManagerService( 1032): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
V/BluetoothOppNotification( 6275): inbound notification was removed.
V/BluetoothOppProvider( 6275): starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
W/sapd    ( 6527): type=1400 audit(0.0:161): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6848 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
V/BluetoothOppProvider( 6275): created cursor android.database.sqlite.SQLiteCursor@3bbeb29c on behalf of 
W/BluetoothAdapter( 6275): getBluetoothService() called with no BluetoothManagerCallback
W/sapd    ( 6527): type=1400 audit(0.0:162): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6848 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
D/LGBluetoothServiceAdapter( 6275): [BTUI] createSocketChannel FD=83 mFd=80
V/BluetoothSapService( 6275): Succeed to create listening socket 
V/BluetoothSapService( 6275): Accepting socket connection...
D/UEI.SmartControl( 5887): QS Service version name: 2.1.91
D/UEI.SmartControl( 5887): QS Service version code: 201091
D/UEI.SmartControl( 5887): Service requested: Control
I/QRemote ( 6466): [RemoteControlManager.java:183:onServiceConnected()] oooooo start
,D/UEI.SmartControl( 5887): Internal service binding...
I/UEI.SmartControl( 5887): ------ IControl API: 11
D/UEI.SmartControl( 5887): File observer start...
E/UEI.SmartControl( 5887): IR Port is disabled: false
D/UEI.SmartControl( 5887): Starting file observer...
I/UEI.SmartControl( 5887): Registering callback...
I/UEI.SmartControl( 5887): ------ IControl API: 19
I/UEI.SmartControl( 5887): Registering Services Ready callback...
I/UEI.SmartControl( 5887): Notify client services are ready...
I/QRemote ( 6466): [RemoteControlManager.java:660:QSSetupIsReady()] oooooo 140517:sdkIsReady callback... get functions. Result:0
D/QRemote ( 6466): [RemoteControlManager.java:388:handleMessage()] oooooo 140510:START_SESSION
D/QRemote ( 6466): [RemoteControlManager.java:394:handleMessage()] oooooo 140510:send retrieve msg
D/QRemote ( 6466): [RemoteControlManager.java:322:handleMessage()] oooooo 140510:handler call retrieveDevices
D/QRemote ( 6466): [RemoteControlManager.java:336:retrieveDevices()] oooooo retrieveDevices: start
I/UEI.SmartControl( 5887): ------ IControl API: 8
D/QRemote ( 6466): [RemoteControlManager.java:340:retrieveDevices()] oooooo retrieveDevices: 0
D/QRemote ( 6466): [RemoteControlManager.java:345:retrieveDevices()] oooooo retrieveDevices complete:true
D/QRemote ( 6466): [RemoteControlManager.java:353:retrieveDevices()] oooooo retrieveDevices: notifyDataSetChanged()
D/QRemote ( 6466): [QRemoteApplication.java:145:onRemoteControlStateChanged()] oooooo onRemoteControlStateChanged called in QRemoteApp
,D/QRemote ( 6466): [QRemoteApplication.java:158:onRemoteControlStateChanged()] oooooo Widget count is [1]. send broadcast
D/QRemote ( 6466): [QRemoteApplication.java:160:onRemoteControlStateChanged()] oooooo Widget[0]:3
D/QRemote ( 6466): [QRemoteApplication.java:188:onRemoteControlStateChanged()] oooooo 140526:onRemoteControlStateChanged&sdkIsReady. stop Service
V/QRemote ( 6466): [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
D/QRemote ( 6466): [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
E/QRemote ( 6466): [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
D/QRemote ( 6466): [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
D/QRemote ( 6466): [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
D/QRemote ( 6466): [RemoteAppWidgetProvider.java:506:onUpdate()] oooooo 140510:RetrieveDevices complete. Start loading
D/QRemote ( 6466): [RemoteAppWidgetProvider.java:508:onUpdate()] oooooo 140510:appWidgetIds[0]:3 loading
D/QRemote ( 6466): [RemoteAppWidgetManager.java:41:startLoading()] oooooo 140518:widgetId[3] loading start at [1452596698016]
D/QRemote ( 6466): [QRemoteService.java:207:onDestroy()] oooooo 140526:onDestroy
,V/BT_SAP  ( 6527): Event pipe created
V/BT_SAP  ( 6527): create_server_socket qcom.sap.server
V/BT_SAP  ( 6527): created socket fd 6
I/ActivityManager( 1032): Killing 5756:com.android.defcontainer/u0a4 (adj 15): empty #17
D/QRemote ( 6466): [RemoteAppWidgetManager.java:239:doInBackground()] oooooo 140407:doinBack arr:0
,W/libprocessgroup( 1032): failed to open /acct/uid_10004/pid_5756/cgroup.procs: No such file or directory
,V/QRemote ( 6466): [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.widget_ui_update
E/QRemote ( 6466): [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
D/QRemote ( 6466): [RemoteAppWidgetProvider.java:171:onReceive()] oooooo total:0
D/QRemote ( 6466): [RemoteAppWidgetProvider.java:172:onReceive()] oooooo selected:0
D/QRemote ( 6466): [RemoteAppWidgetProvider.java:173:onReceive()] oooooo arr:[]
D/QRemote ( 6466): [RemoteAppWidgetProvider.java:174:onReceive()] oooooo appWidgetId:3
D/QRemote ( 6466): [RemoteAppWidgetProvider.java:815:updateRemoteViews()] oooooo UpdateRemoteViews3:widgetId:3
,D/QRemote ( 6466): [RemoteAppWidgetProvider.java:986:updateRemoteViews()] oooooo updateAppWidget5:widgetId:3]
,V/BluetoothOppNotification( 6275): new notify threadi!
V/BluetoothOppNotification( 6275): send delay message
,V/BluetoothOppProvider( 6275): starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
V/BluetoothOppProvider( 6275): created cursor android.database.sqlite.SQLiteCursor@b45c4a5 on behalf of 
V/BluetoothOppNotification( 6275): mUpdateCompleteNotification = true
V/BluetoothOppProvider( 6275): starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
V/BluetoothOppProvider( 6275): created cursor android.database.sqlite.SQLiteCursor@b3d307a on behalf of 
V/BluetoothOppNotification( 6275): outbound: succ-0  fail-0
,V/BluetoothOppNotification( 6275): outbound notification was removed.
V/BluetoothOppProvider( 6275): starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
V/BluetoothOppProvider( 6275): created cursor android.database.sqlite.SQLiteCursor@262f002b on behalf of 
V/BluetoothOppNotification( 6275): inbound: succ-0  fail-0
,V/BluetoothOppNotification( 6275): inbound notification was removed.
V/BluetoothOppProvider( 6275): starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
V/BluetoothOppProvider( 6275): created cursor android.database.sqlite.SQLiteCursor@20525c88 on behalf of 
I/[SystemUI]TimeTickManager( 1461): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1461): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1461): called onTimeUpdated()
I/[SystemUI]Clock( 1461): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1461): called onTimeUpdated()
I/[SystemUI]DateView( 1461): called onTimeUpdated()
I/[SystemUI]DateView( 1461): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1461): handleTimeUpdate
D/WfdsMonitor( 1953): Event [CTRL-EVENT-SCAN-RESULTS ]
D/WfdsMonitor( 1953): Event [WPS-AP-AVAILABLE ]
,E/WifiMonitor( 1032): WifiMonitor:wlan0 cnt=9 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
E/WifiMonitor( 1032): handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
E/WifiMonitor( 1032): WifiMonitor:p2p0 cnt=10 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
E/WifiMonitor( 1032): handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
D/LGWifiP2pService( 1032): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1032): P2pEnabledState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1032): DefaultState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiMonitor( 1032): Event [IFNAME=p2p0 WPS-AP-AVAILABLE ]
E/WifiMonitor( 1032): WifiMonitor:p2p0 cnt=11 dispatchEvent: WPS-AP-AVAILABLE 
W/WifiMonitor( 1032): couldn't identify event type - WPS-AP-AVAILABLE 
E/WifiStateMachine( 1032):  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=0 bcn=0
E/WifiStateMachine( 1032):  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=0 bcn=0
E/WifiStateMachine( 1032):  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=0 bcn=0
E/WifiStateMachine( 1032):  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=0 bcn=0
I/WifiNative-HAL( 1032): startHal
E/wifi    ( 1032): getStaticLongField sWifiHalHandle 0x989368cc
E/WifiHAL ( 1032): Could not connect handle
D/wifi    ( 1032): halHandle = 0x0, mVM = 0xb487c280, mCls = 0x502126
I/WifiNative-HAL( 1032): Could not start hal
D/WifiNative-wlan0( 1032): doString: [BSS RANGE=0- MASK=0x21987]
,V/WiFiOffLoadBroadcast( 6307): WiFiOffLoadBroadcast: android.net.wifi.SCAN_RESULTS
,D/WiFiOffLoadBroadcast( 6307): Not supported operator for automatic switch
I/jxcore-log( 6195): Test app app.js loaded
I/jxcore-log( 6195): 
,I/chromium( 6195): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,I/chromium( 6195): [INFO:SkFontConfigInterface_android.cpp(247)] ---- failed to open </system/fonts/CutiveMono.ttf> as a font
I/chromium( 6195): 
,I/chromium( 6195): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,D/PowerManagerServiceEx( 1032): acquireWakeLockInternal: lock=636702108, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1032
,V/QRemote ( 6466): [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.wait_loading
,D/QRemote ( 6466): [RemoteAppWidgetProvider.java:211:onReceive()] oooooo 140514:alarm msg received!:1058
,D/[Concierge]Service( 2602): onStartCommand(). Type : 9
D/PowerManagerServiceEx( 1032): releaseWakeLockInternal: lock=636702108 [*alarm*], flags=0x0
,D/UEI.SmartControl( 5887): Internal timer expired: 2
D/UEI.SmartControl( 5887): unbind internal service
,D/serial_port( 5887): close(fd = 24)
,I/UEI.SmartControl( 5887): Serial port is closed.
D/sensors_hal_Time( 1032): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1032): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1032): tsOffsetIs: Apps: 296425333848; DSPS: 9853927; Offset : -4307967064
,D/sensors_hal_Time( 1032): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1032): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1032): tsOffsetIs: Apps: 316427614726; DSPS: 10509361; Offset : -4307944514
,D/sensors_hal_Time( 1032): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1032): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1032): tsOffsetIs: Apps: 336429752374; DSPS: 11164791; Offset : -4307943095
,I/[SystemUI]TimeTickManager( 1461): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1461): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1461): called onTimeUpdated()
I/[SystemUI]Clock( 1461): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1461): called onTimeUpdated()
I/[SystemUI]DateView( 1461): called onTimeUpdated()
I/[SystemUI]DateView( 1461): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1461): handleTimeUpdate
V/GLSActivity( 2119): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2119): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 2119): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2119): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2119): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2119): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1032): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1032): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1032): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1032): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1032): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1412): onNotificationPosted
,D/SmartCoverUpdateMonitor( 1412): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1412): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1412): handleNotificationPosted(true)
D/QuickCircle( 1412): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1412): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1412): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1412): post do just update job
D/LgeQuickCoverNotificationData( 1412): showAll3
D/LgeQuickCoverNotificationData( 1412): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1412): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
D/LgeQuickCoverNotificationData( 1412): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
E/LgeQuickCoverOverlayWindow( 1412): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1412): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1412): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1412): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1412): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1412): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1412): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1412): updateNotificationData: count=3
,D/QuickStatusbarLayout( 1412): Notification difference=198
D/QuickStatusbarLayout( 1412): child = android.widget.LinearLayout{333c9717 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
W/GLSActivity( 2119): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2119): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2119): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2119): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2119): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2119): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2119): 	at android.os.Binder.execTransact(Binder.java:446)
,E/PlayEventLogger( 4957): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 4957): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 4957): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/PlayEventLogger( 4957): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 4957): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/PlayEventLogger( 4957): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 4957): 	at android.os.Binder.execTransact(Binder.java:446)
W/System  ( 4957): Ignoring header User-Agent because its value was null.
,D/libc-netbsd(  316): default dns: query_ipv6=0, query_ipv4=0
,D/DSQN    ( 1032): DNSproblemNotiEnabled is disabled ignore DNS fail CB
D/sensors_hal_Time( 1032): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1032): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1032): tsOffsetIs: Apps: 356431418618; DSPS: 11820206; Offset : -4307955214
,D/sensors_hal_Time( 1032): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1032): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1032): tsOffsetIs: Apps: 376433301162; DSPS: 12475628; Offset : -4307964812
,D/sensors_hal_Time( 1032): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1032): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1032): tsOffsetIs: Apps: 396435492143; DSPS: 13131059; Offset : -4307940631
,E/WifiStateMachine( 1032):  DisconnectedState CMD_START_SCAN -2 -2 ic=1 proc(ms):4 rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 fiv=120000 [on:0 tx:0 rx:0 period:897870261] from screen [on:0 period:897870261]
E/WifiStateMachine( 1032):  ConnectModeState CMD_START_SCAN -2 -2 ic=1 proc(ms):10 rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 fiv=120000 [on:0 tx:0 rx:0 period:2] from screen [on:0 period:897870263]
,V/AlarmManager( 1032): RTC_WAKEUP set : Alarm{1e2d7a1e type 0 when 1452596696915 android} when 1452596696915
E/WifiStateMachine( 1032):  DriverStartedState CMD_START_SCAN -2 -2 ic=1 proc(ms):12 rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 fiv=120000 [on:0 tx:0 rx:0 period:18] from screen [on:0 period:897870281]
D/WifiNative-wlan0( 1032): doBoolean: SCAN
,I/wpa_supplicant( 6323): wlan0: CTRL-EVENT-SCAN-STARTED 
D/WifiMonitor( 1032): Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1032): WifiMonitor:wlan0 cnt=12 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1032): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1032): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
D/WifiNative-wlan0( 1032): SCAN: returned true
I/WifiNative-HAL( 1032): startHal
E/wifi    ( 1032): getStaticLongField sWifiHalHandle 0x989367dc
E/WifiHAL ( 1032): Could not connect handle
D/wifi    ( 1032): halHandle = 0x0, mVM = 0xb487c280, mCls = 0x5020f2
I/WifiNative-HAL( 1032): Could not start hal
D/[Concierge]Service( 2602): onStartCommand(). Type : 9
,D/WfdsMonitor( 1953): Event [CTRL-EVENT-SCAN-RESULTS ]
D/WfdsMonitor( 1953): Event [WPS-AP-AVAILABLE ]
,E/WifiMonitor( 1032): WifiMonitor:wlan0 cnt=13 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
E/WifiMonitor( 1032): handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
E/WifiMonitor( 1032): WifiMonitor:p2p0 cnt=14 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
E/WifiMonitor( 1032): handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
E/WifiStateMachine( 1032):  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=6 known=0 got=6 bcn=0
E/WifiStateMachine( 1032):  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=6 known=0 got=6 bcn=0
E/WifiStateMachine( 1032):  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=6 known=0 got=6 bcn=0
E/WifiStateMachine( 1032):  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=6 known=0 got=6 bcn=0
D/WifiNative-wlan0( 1032): doString: [BSS RANGE=0- MASK=0x21987]
D/LGWifiP2pService( 1032): InactiveState{ when=-5ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1032): P2pEnabledState{ when=-5ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1032): DefaultState{ when=-5ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiMonitor( 1032): Event [IFNAME=p2p0 WPS-AP-AVAILABLE ]
E/WifiMonitor( 1032): WifiMonitor:p2p0 cnt=15 dispatchEvent: WPS-AP-AVAILABLE 
W/WifiMonitor( 1032): couldn't identify event type - WPS-AP-AVAILABLE 
V/WiFiOffLoadBroadcast( 6307): WiFiOffLoadBroadcast: android.net.wifi.SCAN_RESULTS
,D/WiFiOffLoadBroadcast( 6307): Not supported operator for automatic switch
I/[SystemUI]TimeTickManager( 1461): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1461): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1461): called onTimeUpdated()
I/[SystemUI]Clock( 1461): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1461): called onTimeUpdated()
I/[SystemUI]DateView( 1461): called onTimeUpdated()
I/[SystemUI]DateView( 1461): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1461): handleTimeUpdate
D/sensors_hal_Time( 1032): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1032): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1032): tsOffsetIs: Apps: 416437615156; DSPS: 13786489; Offset : -4307953849
,D/sensors_hal_Time( 1032): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1032): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1032): tsOffsetIs: Apps: 436439791451; DSPS: 14441920; Offset : -4307944380
,D/sensors_hal_Time( 1032): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1032): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1032): tsOffsetIs: Apps: 456441765819; DSPS: 15097345; Offset : -4307953576
,I/[SystemUI]TimeTickManager( 1461): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1461): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1461): called onTimeUpdated()
I/[SystemUI]Clock( 1461): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1461): called onTimeUpdated()
I/[SystemUI]DateView( 1461): called onTimeUpdated()
I/[SystemUI]DateView( 1461): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1461): handleTimeUpdate
D/sensors_hal_Time( 1032): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1032): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1032): tsOffsetIs: Apps: 476443921384; DSPS: 15752776; Offset : -4307964734
,D/sensors_hal_Time( 1032): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1032): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1032): tsOffsetIs: Apps: 496445474136; DSPS: 16408187; Offset : -4307968352
,D/sensors_hal_Time( 1032): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1032): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1032): tsOffsetIs: Apps: 516447669337; DSPS: 17063618; Offset : -4307939925
,I/[SystemUI]TimeTickManager( 1461): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1461): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1461): called onTimeUpdated()
I/[SystemUI]Clock( 1461): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1461): called onTimeUpdated()
I/[SystemUI]DateView( 1461): called onTimeUpdated()
I/[SystemUI]DateView( 1461): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1461): handleTimeUpdate
D/sensors_hal_Time( 1032): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1032): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1032): tsOffsetIs: Apps: 536449842142; DSPS: 17719050; Offset : -4307964385
,D/sensors_hal_Time( 1032): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1032): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1032): tsOffsetIs: Apps: 556452655572; DSPS: 18374502; Offset : -4307958494
,D/sensors_hal_Time( 1032): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1032): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1032): tsOffsetIs: Apps: 576454819523; DSPS: 19029933; Offset : -4307961449
,I/[SystemUI]TimeTickManager( 1461): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1461): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1461): called onTimeUpdated()
I/[SystemUI]Clock( 1461): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1461): called onTimeUpdated()
I/[SystemUI]DateView( 1461): called onTimeUpdated()
I/[SystemUI]DateView( 1461): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1461): handleTimeUpdate
D/sensors_hal_Time( 1032): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1032): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1032): tsOffsetIs: Apps: 596456860556; DSPS: 19685360; Offset : -4307965014
,D/sensors_hal_Time( 1032): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1032): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1032): tsOffsetIs: Apps: 616458772788; DSPS: 20340782; Offset : -4307944925
,D/sensors_hal_Time( 1032): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1032): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1032): tsOffsetIs: Apps: 636460985281; DSPS: 20996215; Offset : -4307960163
,I/[SystemUI]TimeTickManager( 1461): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1461): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1461): called onTimeUpdated()
I/[SystemUI]Clock( 1461): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1461): called onTimeUpdated()
I/[SystemUI]DateView( 1461): called onTimeUpdated()
I/[SystemUI]DateView( 1461): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1461): handleTimeUpdate
I/ActivityManager( 1032): Killing 5617:com.lge.lockscreensettings/u0a80 (adj 15): empty #17
,W/libprocessgroup( 1032): failed to open /acct/uid_10080/pid_5617/cgroup.procs: No such file or directory
,V/GLSActivity( 2119): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2119): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 2119): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2119): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2119): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2119): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1032): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1032): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1032): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1032): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1032): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1412): onNotificationPosted
D/SmartCoverUpdateMonitor( 1412): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1412): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1412): handleNotificationPosted(true)
D/QuickCircle( 1412): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1412): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1412): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1412): post do just update job
D/LgeQuickCoverNotificationData( 1412): showAll3
D/LgeQuickCoverNotificationData( 1412): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1412): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
D/LgeQuickCoverNotificationData( 1412): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
E/LgeQuickCoverOverlayWindow( 1412): showNotificationWithSetupData: display=false
,D/LgeQuickCoverOverlayWindow( 1412): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1412): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1412): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1412): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1412): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1412): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1412): updateNotificationData: count=3
W/GLSActivity( 2119): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2119): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2119): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2119): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2119): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2119): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2119): 	at android.os.Binder.execTransact(Binder.java:446)
,E/PlayEventLogger( 4957): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 4957): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 4957): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/PlayEventLogger( 4957): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 4957): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/PlayEventLogger( 4957): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 4957): 	at android.os.Binder.execTransact(Binder.java:446)
W/System  ( 4957): Ignoring header User-Agent because its value was null.
D/libc-netbsd(  316): default dns: query_ipv6=0, query_ipv4=0
D/DSQN    ( 1032): DNSproblemNotiEnabled is disabled ignore DNS fail CB
D/QuickStatusbarLayout( 1412): Notification difference=198
D/QuickStatusbarLayout( 1412): child = android.widget.LinearLayout{333c9717 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,D/PowerManagerServiceEx( 1032): acquireWakeLockInternal: lock=636702108, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1032
,V/AlarmManager( 1032): ELAPSED_WAKEUP set : Alarm{35e6e3d0 type 2 when 497750 com.google.android.gms} when 497750
,D/[Concierge]Service( 2602): onStartCommand(). Type : 9
,D/libc-netbsd(  316): default dns: query_ipv6=0, query_ipv4=0
,D/DSQN    ( 1032): DNSproblemNotiEnabled is disabled ignore DNS fail CB
D/PowerManagerServiceEx( 1032): releaseWakeLockInternal: lock=636702108 [*alarm*], flags=0x0
,D/sensors_hal_Time( 1032): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1032): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1032): tsOffsetIs: Apps: 656463101159; DSPS: 21651644; Offset : -4307950075
,D/sensors_hal_Time( 1032): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1032): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1032): tsOffsetIs: Apps: 676465384537; DSPS: 22307079; Offset : -4307955386
,D/sensors_hal_Time( 1032): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1032): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1032): tsOffsetIs: Apps: 696467548487; DSPS: 22962510; Offset : -4307958340
,I/[SystemUI]TimeTickManager( 1461): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1461): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1461): called onTimeUpdated()
I/[SystemUI]Clock( 1461): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1461): called onTimeUpdated()
I/[SystemUI]DateView( 1461): called onTimeUpdated()
I/[SystemUI]DateView( 1461): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1461): handleTimeUpdate
,D/sensors_hal_Time( 1032): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1032): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1032): tsOffsetIs: Apps: 716469457021; DSPS: 23617932; Offset : -4307941922
,D/sensors_hal_Time( 1032): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1032): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1032): tsOffsetIs: Apps: 736472023993; DSPS: 24273376; Offset : -4307938427
,D/sensors_hal_Time( 1032): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1032): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1032): tsOffsetIs: Apps: 756473918569; DSPS: 24928799; Offset : -4307966353
,I/[SystemUI]TimeTickManager( 1461): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1461): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1461): called onTimeUpdated()
I/[SystemUI]Clock( 1461): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1461): called onTimeUpdated()
I/[SystemUI]DateView( 1461): called onTimeUpdated()
I/[SystemUI]DateView( 1461): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1461): handleTimeUpdate
D/sensors_hal_Time( 1032): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1032): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1032): tsOffsetIs: Apps: 776475870644; DSPS: 25584223; Offset : -4307967403
,D/sensors_hal_Time( 1032): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1032): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1032): tsOffsetIs: Apps: 796477810897; DSPS: 26239646; Offset : -4307949758
,D/sensors_hal_Time( 1032): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1032): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1032): tsOffsetIs: Apps: 816479663962; DSPS: 26895067; Offset : -4307958266
,I/[SystemUI]TimeTickManager( 1461): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1461): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1461): called onTimeUpdated()
I/[SystemUI]Clock( 1461): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1461): called onTimeUpdated()
I/[SystemUI]DateView( 1461): called onTimeUpdated()
I/[SystemUI]DateView( 1461): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1461): handleTimeUpdate
D/sensors_hal_Time( 1032): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1032): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1032): tsOffsetIs: Apps: 836481923278; DSPS: 27550501; Offset : -4307957225
,D/sensors_hal_Time( 1032): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1032): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1032): tsOffsetIs: Apps: 856484048531; DSPS: 28205931; Offset : -4307968254
,D/sensors_hal_Time( 1032): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1032): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1032): tsOffsetIs: Apps: 876486364981; DSPS: 28861366; Offset : -4307940596
,I/[SystemUI]TimeTickManager( 1461): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1461): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1461): called onTimeUpdated()
I/[SystemUI]Clock( 1461): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1461): called onTimeUpdated()
I/[SystemUI]DateView( 1461): called onTimeUpdated()
I/[SystemUI]DateView( 1461): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1461): handleTimeUpdate
D/sensors_hal_Time( 1032): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1032): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1032): tsOffsetIs: Apps: 896488281067; DSPS: 29516789; Offset : -4307947222
,D/sensors_hal_Time( 1032): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1032): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1032): tsOffsetIs: Apps: 916490560904; DSPS: 30172224; Offset : -4307956126
,D/sensors_hal_Time( 1032): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1032): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1032): tsOffsetIs: Apps: 936492667250; DSPS: 30827653; Offset : -4307955492
,I/[SystemUI]TimeTickManager( 1461): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1461): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1461): called onTimeUpdated()
I/[SystemUI]Clock( 1461): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1461): called onTimeUpdated()
I/[SystemUI]DateView( 1461): called onTimeUpdated()
I/[SystemUI]DateView( 1461): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1461): handleTimeUpdate
V/GLSActivity( 2119): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2119): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 2119): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2119): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2119): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2119): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1032): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1032): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1032): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1032): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1032): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1412): onNotificationPosted
,D/SmartCoverUpdateMonitor( 1412): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1412): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1412): handleNotificationPosted(true)
D/QuickCircle( 1412): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1412): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1412): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1412): post do just update job
D/LgeQuickCoverNotificationData( 1412): showAll3
D/LgeQuickCoverNotificationData( 1412): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1412): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
D/LgeQuickCoverNotificationData( 1412): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
E/LgeQuickCoverOverlayWindow( 1412): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1412): [native noti] inex =  0
,D/LgeQuickCoverNotificationData( 1412): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1412): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1412): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1412): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1412): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1412): updateNotificationData: count=3
W/GLSActivity( 2119): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2119): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2119): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2119): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2119): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2119): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2119): 	at android.os.Binder.execTransact(Binder.java:446)
E/PlayEventLogger( 4957): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 4957): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 4957): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/PlayEventLogger( 4957): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 4957): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/PlayEventLogger( 4957): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 4957): 	at android.os.Binder.execTransact(Binder.java:446)
W/System  ( 4957): Ignoring header User-Agent because its value was null.
,D/QuickStatusbarLayout( 1412): Notification difference=198
D/QuickStatusbarLayout( 1412): child = android.widget.LinearLayout{333c9717 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
D/libc-netbsd(  316): default dns: query_ipv6=0, query_ipv4=0
D/DSQN    ( 1032): DNSproblemNotiEnabled is disabled ignore DNS fail CB
D/sensors_hal_Time( 1032): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1032): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1032): tsOffsetIs: Apps: 956494591461; DSPS: 31483076; Offset : -4307953888
,D/sensors_hal_Time( 1032): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1032): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1032): tsOffsetIs: Apps: 976497183380; DSPS: 32138521; Offset : -4307955937
,D/sensors_hal_Time( 1032): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1032): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1032): tsOffsetIs: Apps: 996499080508; DSPS: 32793943; Offset : -4307950874
,I/[SystemUI]TimeTickManager( 1461): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1461): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1461): called onTimeUpdated()
I/[SystemUI]Clock( 1461): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1461): called onTimeUpdated()
I/[SystemUI]DateView( 1461): called onTimeUpdated()
I/[SystemUI]DateView( 1461): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1461): handleTimeUpdate
D/sensors_hal_Time( 1032): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1032): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1032): tsOffsetIs: Apps: 1016501962949; DSPS: 33449398; Offset : -4307967602
,D/sensors_hal_Time( 1032): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1032): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1032): tsOffsetIs: Apps: 1036511050024; DSPS: 34105055; Offset : -4307944117
,D/sensors_hal_Time( 1032): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1032): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1032): tsOffsetIs: Apps: 1056513090329; DSPS: 34760482; Offset : -4307948646
,I/[SystemUI]TimeTickManager( 1461): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1461): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1461): called onTimeUpdated()
I/[SystemUI]Clock( 1461): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1461): called onTimeUpdated()
I/[SystemUI]DateView( 1461): called onTimeUpdated()
I/[SystemUI]DateView( 1461): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1461): handleTimeUpdate
D/sensors_hal_Time( 1032): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1032): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1032): tsOffsetIs: Apps: 1076520461936; DSPS: 35416084; Offset : -4307962215
,D/sensors_hal_Time( 1032): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1032): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1032): tsOffsetIs: Apps: 1096522643178; DSPS: 36071515; Offset : -4307947903
,D/sensors_hal_Time( 1032): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1032): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1032): tsOffsetIs: Apps: 1116524356869; DSPS: 36726931; Offset : -4307943014
,I/[SystemUI]TimeTickManager( 1461): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1461): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1461): called onTimeUpdated()
I/[SystemUI]Clock( 1461): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1461): called onTimeUpdated()
I/[SystemUI]DateView( 1461): called onTimeUpdated()
I/[SystemUI]DateView( 1461): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1461): handleTimeUpdate
D/sensors_hal_Time( 1032): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1032): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1032): tsOffsetIs: Apps: 1136526259048; DSPS: 37382354; Offset : -4307963521
,D/PowerManagerServiceEx( 1032): acquireWakeLockInternal: lock=636702108, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1032
,V/AlarmManager( 1032): ELAPSED_WAKEUP set : Alarm{1d375232 type 2 when 1147074 com.google.android.gms} when 1147074
D/[Concierge]Service( 2602): onStartCommand(). Type : 9
,D/libc-netbsd(  316): default dns: query_ipv6=0, query_ipv4=0
,D/DSQN    ( 1032): DNSproblemNotiEnabled is disabled ignore DNS fail CB
D/PowerManagerServiceEx( 1032): releaseWakeLockInternal: lock=636702108 [*alarm*], flags=0x0
,D/sensors_hal_Time( 1032): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1032): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1032): tsOffsetIs: Apps: 1156528201124; DSPS: 38037777; Offset : -4307944000
,D/sensors_hal_Time( 1032): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1032): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1032): tsOffsetIs: Apps: 1176530911221; DSPS: 38693226; Offset : -4307950098
,V/AlarmManager( 1032): ELAPSED_WAKEUP set : Alarm{10456b83 type 2 when 1185828 com.android.bluetooth} when 1185828
,W/bt-smp  ( 6275): Key(LSB ~ MSB) = 0a 3c a6 fe eb 17 6a 79 a6 1f 0a 0b f9 50 a0 5f 
W/bt-smp  ( 6275): Plain text(LSB ~ MSB) = b0 28 4e 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 6275): Encrypted text(LSB ~ MSB) = 73 f4 87 15 c8 ad 5a 74 87 5a 86 b4 89 71 e3 ff 
W/bt-btm  ( 6275): Stopping oneshot timer
I/[SystemUI]TimeTickManager( 1461): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1461): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1461): called onTimeUpdated()
I/[SystemUI]Clock( 1461): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1461): called onTimeUpdated()
I/[SystemUI]DateView( 1461): called onTimeUpdated()
I/[SystemUI]DateView( 1461): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1461): handleTimeUpdate
D/sensors_hal_Time( 1032): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1032): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1032): tsOffsetIs: Apps: 1196532983609; DSPS: 39348654; Offset : -4307952827
,D/sensors_hal_Time( 1032): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1032): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1032): tsOffsetIs: Apps: 1216535167195; DSPS: 40004086; Offset : -4307966430
,I/UsageStatsService( 1032): User[0] Flushing usage stats to disk
,D/sensors_hal_Time( 1032): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1032): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1032): tsOffsetIs: Apps: 1236537266458; DSPS: 40659514; Offset : -4307942518
,I/[SystemUI]TimeTickManager( 1461): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1461): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1461): called onTimeUpdated()
I/[SystemUI]Clock( 1461): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1461): called onTimeUpdated()
I/[SystemUI]DateView( 1461): called onTimeUpdated()
I/[SystemUI]DateView( 1461): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1461): handleTimeUpdate
V/GLSActivity( 2119): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2119): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 2119): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2119): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2119): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2119): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1032): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1032): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1032): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1032): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1032): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1412): onNotificationPosted
,D/SmartCoverUpdateMonitor( 1412): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1412): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1412): handleNotificationPosted(true)
D/QuickCircle( 1412): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1412): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1412): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1412): post do just update job
D/LgeQuickCoverNotificationData( 1412): showAll3
D/LgeQuickCoverNotificationData( 1412): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1412): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
D/LgeQuickCoverNotificationData( 1412): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
E/LgeQuickCoverOverlayWindow( 1412): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1412): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1412): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1412): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1412): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1412): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1412): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1412): updateNotificationData: count=3
W/GLSActivity( 2119): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2119): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2119): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2119): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2119): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2119): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2119): 	at android.os.Binder.execTransact(Binder.java:446)
,E/PlayEventLogger( 4957): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 4957): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 4957): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/PlayEventLogger( 4957): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 4957): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/PlayEventLogger( 4957): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 4957): 	at android.os.Binder.execTransact(Binder.java:446)
W/System  ( 4957): Ignoring header User-Agent because its value was null.
D/QuickStatusbarLayout( 1412): Notification difference=198
D/QuickStatusbarLayout( 1412): child = android.widget.LinearLayout{333c9717 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
D/libc-netbsd(  316): default dns: query_ipv6=0, query_ipv4=0
,D/DSQN    ( 1032): DNSproblemNotiEnabled is disabled ignore DNS fail CB
D/sensors_hal_Time( 1032): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1032): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1032): tsOffsetIs: Apps: 1256539223273; DSPS: 41314938; Offset : -4307938828
,D/sensors_hal_Time( 1032): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1032): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1032): tsOffsetIs: Apps: 1276541771704; DSPS: 41970382; Offset : -4307953874
,D/sensors_hal_Time( 1032): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1032): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1032): tsOffsetIs: Apps: 1296543876331; DSPS: 42625811; Offset : -4307954855
,I/[SystemUI]TimeTickManager( 1461): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1461): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1461): called onTimeUpdated()
I/[SystemUI]Clock( 1461): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1461): called onTimeUpdated()
I/[SystemUI]DateView( 1461): called onTimeUpdated()
I/[SystemUI]DateView( 1461): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1461): handleTimeUpdate
D/sensors_hal_Time( 1032): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1032): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1032): tsOffsetIs: Apps: 1316545471323; DSPS: 43281223; Offset : -4307946777
,D/sensors_hal_Time( 1032): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1032): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1032): tsOffsetIs: Apps: 1336547480743; DSPS: 43936649; Offset : -4307951570
,D/sensors_hal_Time( 1032): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1032): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1032): tsOffsetIs: Apps: 1356549593079; DSPS: 44592078; Offset : -4307944920
,I/[SystemUI]TimeTickManager( 1461): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1461): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1461): called onTimeUpdated()
I/[SystemUI]Clock( 1461): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1461): called onTimeUpdated()
I/[SystemUI]DateView( 1461): called onTimeUpdated()
I/[SystemUI]DateView( 1461): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1461): handleTimeUpdate
D/sensors_hal_Time( 1032): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1032): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1032): tsOffsetIs: Apps: 1376551862916; DSPS: 45247513; Offset : -4307963901
,D/sensors_hal_Time( 1032): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1032): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1032): tsOffsetIs: Apps: 1396553663689; DSPS: 45902932; Offset : -4307963639
,D/sensors_hal_Time( 1032): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1032): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1032): tsOffsetIs: Apps: 1416555546546; DSPS: 46558353; Offset : -4307942459
,I/[SystemUI]TimeTickManager( 1461): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1461): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1461): called onTimeUpdated()
I/[SystemUI]Clock( 1461): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1461): called onTimeUpdated()
I/[SystemUI]DateView( 1461): called onTimeUpdated()
I/[SystemUI]DateView( 1461): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1461): handleTimeUpdate
D/sensors_hal_Time( 1032): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1032): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1032): tsOffsetIs: Apps: 1436561456383; DSPS: 47213907; Offset : -4307953031
,D/sensors_hal_Time( 1032): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1032): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1032): tsOffsetIs: Apps: 1456563088406; DSPS: 47869320; Offset : -4307938388
,D/sensors_hal_Time( 1032): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1032): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1032): tsOffsetIs: Apps: 1476565257096; DSPS: 48524752; Offset : -4307966912
,I/[SystemUI]TimeTickManager( 1461): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1461): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1461): called onTimeUpdated()
I/[SystemUI]Clock( 1461): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1461): called onTimeUpdated()
I/[SystemUI]DateView( 1461): called onTimeUpdated()
I/[SystemUI]DateView( 1461): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1461): handleTimeUpdate
D/sensors_hal_Time( 1032): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1032): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1032): tsOffsetIs: Apps: 1496567154067; DSPS: 49180174; Offset : -4307962136
,D/sensors_hal_Time( 1032): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1032): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1032): tsOffsetIs: Apps: 1516568984789; DSPS: 49835594; Offset : -4307962312
,D/sensors_hal_Time( 1032): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1032): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1032): tsOffsetIs: Apps: 1536571276031; DSPS: 50491029; Offset : -4307959836
,I/[SystemUI]TimeTickManager( 1461): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1461): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1461): called onTimeUpdated()
I/[SystemUI]Clock( 1461): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1461): called onTimeUpdated()
I/[SystemUI]DateView( 1461): called onTimeUpdated()
I/[SystemUI]DateView( 1461): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1461): handleTimeUpdate
V/GLSActivity( 2119): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2119): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 2119): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2119): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2119): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2119): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1032): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1032): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1032): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1032): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1032): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1412): onNotificationPosted
,D/SmartCoverUpdateMonitor( 1412): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1412): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1412): handleNotificationPosted(true)
D/QuickCircle( 1412): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1412): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1412): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1412): post do just update job
D/LgeQuickCoverNotificationData( 1412): showAll3
D/LgeQuickCoverNotificationData( 1412): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1412): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
D/LgeQuickCoverNotificationData( 1412): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
E/LgeQuickCoverOverlayWindow( 1412): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1412): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1412): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1412): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1412): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1412): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1412): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1412): updateNotificationData: count=3
W/GLSActivity( 2119): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2119): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2119): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2119): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2119): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2119): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2119): 	at android.os.Binder.execTransact(Binder.java:446)
,E/PlayEventLogger( 4957): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 4957): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 4957): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/PlayEventLogger( 4957): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 4957): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/PlayEventLogger( 4957): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 4957): 	at android.os.Binder.execTransact(Binder.java:446)
W/System  ( 4957): Ignoring header User-Agent because its value was null.
D/libc-netbsd(  316): default dns: query_ipv6=0, query_ipv4=0
D/DSQN    ( 1032): DNSproblemNotiEnabled is disabled ignore DNS fail CB
D/QuickStatusbarLayout( 1412): Notification difference=198
D/QuickStatusbarLayout( 1412): child = android.widget.LinearLayout{333c9717 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,D/sensors_hal_Time( 1032): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1032): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1032): tsOffsetIs: Apps: 1556573143264; DSPS: 51146450; Offset : -4307954253
,D/sensors_hal_Time( 1032): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1032): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1032): tsOffsetIs: Apps: 1576574831901; DSPS: 51801865; Offset : -4307944109
,D/sensors_hal_Time( 1032): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1032): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1032): tsOffsetIs: Apps: 1596576671946; DSPS: 52457286; Offset : -4307965662
,I/[SystemUI]TimeTickManager( 1461): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1461): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1461): called onTimeUpdated()
I/[SystemUI]Clock( 1461): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1461): called onTimeUpdated()
I/[SystemUI]DateView( 1461): called onTimeUpdated()
I/[SystemUI]DateView( 1461): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1461): handleTimeUpdate
D/sensors_hal_Time( 1032): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1032): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1032): tsOffsetIs: Apps: 1616578749855; DSPS: 53112714; Offset : -4307962845
,D/sensors_hal_Time( 1032): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1032): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1032): tsOffsetIs: Apps: 1636581025629; DSPS: 53768148; Offset : -4307945475
,D/sensors_hal_Time( 1032): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1032): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1032): tsOffsetIs: Apps: 1656583157496; DSPS: 54423578; Offset : -4307949840
,I/[SystemUI]TimeTickManager( 1461): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1461): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1461): called onTimeUpdated()
,I/[SystemUI]Clock( 1461): called onTimeUpdated()
I/LgeClockWidgetControlView( 1461): called onTimeUpdated()
I/[SystemUI]DateView( 1461): called onTimeUpdated()
I/[SystemUI]DateView( 1461): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1461): handleTimeUpdate
D/sensors_hal_Time( 1032): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1032): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1032): tsOffsetIs: Apps: 1676585477228; DSPS: 55079014; Offset : -4307949495
,D/sensors_hal_Time( 1032): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1032): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1032): tsOffsetIs: Apps: 1696587673834; DSPS: 55734446; Offset : -4307950102
,D/sensors_hal_Time( 1032): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1032): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1032): tsOffsetIs: Apps: 1716589584087; DSPS: 56389869; Offset : -4307962431
,I/[SystemUI]TimeTickManager( 1461): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1461): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1461): called onTimeUpdated()
I/[SystemUI]Clock( 1461): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1461): called onTimeUpdated()
I/[SystemUI]DateView( 1461): called onTimeUpdated()
I/[SystemUI]DateView( 1461): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1461): handleTimeUpdate
D/sensors_hal_Time( 1032): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1032): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1032): tsOffsetIs: Apps: 1736592109549; DSPS: 57045311; Offset : -4307939462
,D/sensors_hal_Time( 1032): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1032): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1032): tsOffsetIs: Apps: 1756594037875; DSPS: 57700735; Offset : -4307964079
,D/sensors_hal_Time( 1032): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1032): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1032): tsOffsetIs: Apps: 1776595938492; DSPS: 58356157; Offset : -4307955683
,I/[SystemUI]TimeTickManager( 1461): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1461): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1461): called onTimeUpdated()
I/[SystemUI]Clock( 1461): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1461): called onTimeUpdated()
I/[SystemUI]DateView( 1461): called onTimeUpdated()
I/[SystemUI]DateView( 1461): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1461): handleTimeUpdate
D/sensors_hal_Time( 1032): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1032): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1032): tsOffsetIs: Apps: 1796598115307; DSPS: 59011588; Offset : -4307945615
,D/sensors_hal_Time( 1032): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1032): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1032): tsOffsetIs: Apps: 1816600893165; DSPS: 59667039; Offset : -4307944908
,D/sensors_hal_Time( 1032): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1032): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1032): tsOffsetIs: Apps: 1836603104511; DSPS: 60322472; Offset : -4307961399
,I/[SystemUI]TimeTickManager( 1461): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1461): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1461): called onTimeUpdated()
I/[SystemUI]Clock( 1461): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1461): called onTimeUpdated()
I/[SystemUI]DateView( 1461): called onTimeUpdated()
I/[SystemUI]DateView( 1461): called onTimeUpdated()
,D/KeyguardUpdateMonitor( 1461): handleTimeUpdate
V/GLSActivity( 2119): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ProcessStatsService( 1032): Prepared write state in 9ms
,I/GLSUser ( 2119): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 2119): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2119): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2119): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2119): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1032): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1032): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1032): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1032): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1032): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1412): onNotificationPosted
D/SmartCoverUpdateMonitor( 1412): received broadcast com.lge.intent.action.NLDataPosted
W/GLSActivity( 2119): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2119): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2119): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2119): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2119): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2119): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2119): 	at android.os.Binder.execTransact(Binder.java:446)
E/SmartCoverUpdateMonitor( 1412): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1412): handleNotificationPosted(true)
D/QuickCircle( 1412): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1412): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1412): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1412): post do just update job
,D/LgeQuickCoverNotificationData( 1412): showAll3
D/LgeQuickCoverNotificationData( 1412): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1412): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
D/LgeQuickCoverNotificationData( 1412): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
E/LgeQuickCoverOverlayWindow( 1412): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1412): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1412): isNotificationForCurrentUser : true
E/PlayEventLogger( 4957): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 4957): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 4957): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/PlayEventLogger( 4957): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 4957): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/PlayEventLogger( 4957): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 4957): 	at android.os.Binder.execTransact(Binder.java:446)
W/System  ( 4957): Ignoring header User-Agent because its value was null.
D/LgeQuickCoverOverlayWindow( 1412): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1412): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1412): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1412): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1412): updateNotificationData: count=3
D/libc-netbsd(  316): default dns: query_ipv6=0, query_ipv4=0
,D/DSQN    ( 1032): DNSproblemNotiEnabled is disabled ignore DNS fail CB
D/QuickStatusbarLayout( 1412): Notification difference=198
D/QuickStatusbarLayout( 1412): child = android.widget.LinearLayout{333c9717 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,D/sensors_hal_Time( 1032): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1032): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1032): tsOffsetIs: Apps: 1856605229503; DSPS: 60977901; Offset : -4307941963
,D/sensors_hal_Time( 1032): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1032): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1032): tsOffsetIs: Apps: 1876607098870; DSPS: 61633323; Offset : -4307964763
,D/sensors_hal_Time( 1032): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1032): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1032): tsOffsetIs: Apps: 1896609129227; DSPS: 62288749; Offset : -4307948646
,I/[SystemUI]TimeTickManager( 1461): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1461): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1461): called onTimeUpdated()
I/[SystemUI]Clock( 1461): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1461): called onTimeUpdated()
I/[SystemUI]DateView( 1461): called onTimeUpdated()
I/[SystemUI]DateView( 1461): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1461): handleTimeUpdate
,D/sensors_hal_Time( 1032): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1032): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1032): tsOffsetIs: Apps: 1916611684637; DSPS: 62944193; Offset : -4307956790
,D/sensors_hal_Time( 1032): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1032): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1032): tsOffsetIs: Apps: 1936613822389; DSPS: 63599623; Offset : -4307955086
,D/sensors_hal_Time( 1032): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1032): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1032): tsOffsetIs: Apps: 1956615938215; DSPS: 64255052; Offset : -4307944842
,I/[SystemUI]TimeTickManager( 1461): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1461): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1461): called onTimeUpdated()
I/[SystemUI]Clock( 1461): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1461): called onTimeUpdated()
I/[SystemUI]DateView( 1461): called onTimeUpdated()
I/[SystemUI]DateView( 1461): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1461): handleTimeUpdate
,D/sensors_hal_Time( 1032): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1032): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1032): tsOffsetIs: Apps: 1976618134613; DSPS: 64910484; Offset : -4307945893
,D/sensors_hal_Time( 1032): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1032): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1032): tsOffsetIs: Apps: 1996620801065; DSPS: 65565932; Offset : -4307965039
,D/sensors_hal_Time( 1032): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1032): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1032): tsOffsetIs: Apps: 2016622926213; DSPS: 66221361; Offset : -4307945526
,I/[SystemUI]TimeTickManager( 1461): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1461): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1461): called onTimeUpdated()
I/[SystemUI]Clock( 1461): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1461): called onTimeUpdated()
I/[SystemUI]DateView( 1461): called onTimeUpdated()
I/[SystemUI]DateView( 1461): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1461): handleTimeUpdate
,D/sensors_hal_Time( 1032): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1032): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1032): tsOffsetIs: Apps: 2036625019955; DSPS: 66876790; Offset : -4307957575
,D/sensors_hal_Time( 1032): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1032): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1032): tsOffsetIs: Apps: 2056626943958; DSPS: 67532213; Offset : -4307956101
,D/sensors_hal_Time( 1032): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1032): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1032): tsOffsetIs: Apps: 2076628864418; DSPS: 68187636; Offset : -4307958197
,D/PowerManagerServiceEx( 1032): acquireWakeLockInternal: lock=636702108, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1032
,I/ActivityManager( 1032): Killing 6346:com.lge.formmanager/u0a26 (adj 15): empty for 1800s
,V/AlarmManager( 1032): ELAPSED_WAKEUP set : Alarm{9c13a78 type 2 when 2085848 com.android.bluetooth} when 2085848
W/bt-smp  ( 6275): Key(LSB ~ MSB) = 0a 3c a6 fe eb 17 6a 79 a6 1f 0a 0b f9 50 a0 5f 
W/bt-smp  ( 6275): Plain text(LSB ~ MSB) = dc 2e 59 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 6275): Encrypted text(LSB ~ MSB) = d1 9c 0c 85 51 09 2e 34 2d 56 0f 66 15 0d d4 db 
W/bt-btm  ( 6275): Stopping oneshot timer
I/ActivityManager( 1032): Killing 4957:com.android.vending/u0a44 (adj 15): empty for 1808s
,I/ActivityManager( 1032): Killing 2361:com.google.android.gms/u0a5 (adj 15): empty for 1937s
,I/ActivityManager( 1032): Killing 5991:com.google.android.gms.wearable/u0a5 (adj 15): empty for 1962s
,I/ActivityManager( 1032): Killing 5943:com.lge.eula/1000 (adj 15): empty for 1968s
,I/ActivityManager( 1032): Killing 5635:com.google.android.apps.plus/u0a97 (adj 15): empty for 1968s
,I/ActivityManager( 1032): Killing 5906:com.google.android.apps.docs/u0a61 (adj 15): empty for 1968s
,W/libprocessgroup( 1032): failed to open /acct/uid_10026/pid_6346/cgroup.procs: No such file or directory
,W/libprocessgroup( 1032): failed to open /acct/uid_10005/pid_2361/cgroup.procs: No such file or directory
W/libprocessgroup( 1032): failed to open /acct/uid_10005/pid_5991/cgroup.procs: No such file or directory
W/libprocessgroup( 1032): failed to open /acct/uid_1000/pid_5943/cgroup.procs: No such file or directory
,W/libprocessgroup( 1032): failed to open /acct/uid_10097/pid_5635/cgroup.procs: No such file or directory
W/libprocessgroup( 1032): failed to open /acct/uid_10061/pid_5906/cgroup.procs: No such file or directory
W/libprocessgroup( 1032): failed to open /acct/uid_10044/pid_4957/cgroup.procs: No such file or directory
D/[Concierge]Service( 2602): onStartCommand(). Type : 9
,D/PowerManagerServiceEx( 1032): releaseWakeLockInternal: lock=636702108 [*alarm*], flags=0x0
,I/[SystemUI]TimeTickManager( 1461): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1461): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1461): called onTimeUpdated()
I/[SystemUI]Clock( 1461): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1461): called onTimeUpdated()
I/[SystemUI]DateView( 1461): called onTimeUpdated()
I/[SystemUI]DateView( 1461): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1461): handleTimeUpdate
,D/sensors_hal_Time( 1032): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1032): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1032): tsOffsetIs: Apps: 2096630399516; DSPS: 68843046; Offset : -4307949030
,TIME-OUT KILL (timeout was 1800000ms),D/AndroidRuntime( 6885): 
D/AndroidRuntime( 6885): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 6885): CheckJNI is OFF
D/AndroidRuntime( 6885): Calling main entry com.android.commands.pm.Pm
I/ActivityManager( 1032): Force stopping com.test.thalitest appid=10311 user=-1: uninstall pkg
I/ActivityManager( 1032): Killing 6195:com.test.thalitest/u0a311 (adj 0): stop com.test.thalitest
I/WindowState( 1032): WIN DEATH: Window{11110fa2 u0 com.test.thalitest/com.test.thalitest.MainActivity}
D/WifiService( 1032): Client connection lost with reason: 4
D/InputDispatcher( 1032): Window went away: Window{11110fa2 u0 com.test.thalitest/com.test.thalitest.MainActivity}
I/ActivityManager( 1032):   Force finishing activity ActivityRecord{19d05eaf u0 com.test.thalitest/.MainActivity t4}
W/PackageSettings( 1032): Skipping PackageSetting{35629c27 com.example.hello/10319} due to missing metadata
E/GBMv2   (  337): DFP En is all cleared set to be enabled
W/ActivityManager( 1032): Spurious death for ProcessRecord{37e6a551 6195:com.test.thalitest/u0a311}, curProc for 6195: null
I/ActivityManager( 1032): Force stopping com.test.thalitest appid=10311 user=0: pkg removed
I/ActivityManager( 1032):   Force finishing activity ActivityRecord{19d05eaf u0 com.test.thalitest/.MainActivity t4 f}
W/ActivityManager( 1032): Duplicate finish request for ActivityRecord{19d05eaf u0 com.test.thalitest/.MainActivity t4 f}
I/art     ( 4286): Explicit concurrent mark sweep GC freed 17532(1063KB) AllocSpace objects, 0(0B) LOS objects, 34% free, 29MB/45MB, paused 558us total 50.864ms
I/[LGHome]EVENT( 2065): [Launcher.java:5338:onStart()]onStart
D/SplitWindowPolicy( 1953): updateActivityStateChanged: resumed=false, screenId=0, isScreenFull=false
D/SplitWindowPolicy( 1953): topRunningActivity=ActivityInfo{3bf4c6df co.....Launcher}, taskId=3, activityType=1, bIsSplit=false
I/[LGHome]EVENT( 2065): [Launcher.java:903:onResume()]onResume
D/SplitWindowPolicy( 1953): updateActivityStateChanged: resumed=true, screenId=0, isScreenFull=false
D/SplitWindowPolicy( 1953): topRunningActivity=ActivityInfo{b4acf2c co.....Launcher}, taskId=3, activityType=1, bIsSplit=false
I/[LGHome]EVENT( 2065): [LauncherModel.java:1352:startLoader()]startLoader isLaunching=true
I/[LGHome]Launcher.Model( 2065): [LauncherModel.java:1469:loadAndBindWorkspace()]loadAndBindWorkspace=0ms
D/KeyguardModel( 1461): mPackageIntentReceiver, received action: android.intent.action.PACKAGE_REMOVED, sendingUserId:0
I/InputReader( 1032): Reconfiguring input devices.  changes=0x00000010
W/GeofencerStateMachine( 1803): Ignoring removeGeofence because network location is disabled.
D/LIA_Service_RemotePackageHandler( 2007): onReceive action : android.intent.action.PACKAGE_REMOVED = package:com.test.thalitest
D/LIA_MrGDBLogger_PackageInfoDetector( 2695): [dreamwood]action: android.intent.action.PACKAGE_REMOVED, package: com.test.thalitest
E/LGBluetoothAvrcpQcomAdapter( 6275): [BTUI] [BTUI] onReceive()... android.intent.action.PACKAGE_REMOVED
D/LGBluetoothAvrcpQcomAdapter( 6275): [BTUI] [+] updateMediaPlayerInfo
D/PostponalbeReceiver( 5227): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.intent.action.PACKAGE_REMOVED'.
V/SIM_STK ( 1032): Menu title from STK is T-Mobile
W/System.err( 4227): android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
W/System.err( 4227): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
W/System.err( 4227): 	at com.lge.mlt.MptOnAppWatcher$1.onReceive(MptOnAppWatcher.java:44)
W/System.err( 4227): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:956)
W/System.err( 4227): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 4227): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 4227): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 4227): 	at android.app.ActivityThread.main(ActivityThread.java:5274)
W/System.err( 4227): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 4227): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 4227): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
W/System.err( 4227): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
I/art     ( 1032): Explicit concurrent mark sweep GC freed 37887(2MB) AllocSpace objects, 15(1111KB) LOS objects, 33% free, 44MB/66MB, paused 1.806ms total 164.986ms
I/art     ( 1032): WaitForGcToComplete blocked for 126.362ms for cause Explicit
I/ActivityManager( 1032): Start proc com.lge.lockscreensettings for content provider com.lge.lockscreensettings/.LockSettingsProvider: pid=6916 uid=10080 gids={50080, 9997, 1028, 1015} abi=armeabi-v7a
I/[LGHome]GBoardWebView( 2065): [GBoardWebView.java:306:loadCacheBitmapPostDelayed()]loadCacheBitmapPostDelayed() delay:1
D/ActionManagerService( 1917): notifyUserLog: 1000003
D/LIA_Informant_ActionManagerMessageHandler( 2695): handleMessage: what(1000) actionID(0x1000003)
I/[SystemUI]QSlideListController( 1461): onReceive = android.intent.action.PACKAGE_REMOVED
I/ActivityManager( 1032): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.manager.PreloadListManagerHelper: pid=6932 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
I/[LGHome]LGActivityUtil( 2065): [LGActivityUtil.java:319:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
I/[LGHome]EVENT( 2065): [Launcher.java:1056:onResume()]onResume end
I/[LGHome]EVENT( 2065): [Launcher.java:1114:onPause()]onPause
D/ActionManagerService( 1917): notifyUserLog: 1000004
I/[LGHome]GBoardWebView( 2065): [GBoardWebView.java:247:writeCacheBitmapPostDelayed()]writeCacheBitmapPostDelayed() delay: we don't have a change point1
D/LIA_Informant_ActionManagerMessageHandler( 2695): handleMessage: what(1000) actionID(0x1000004)
I/[SystemUI]AppWidgetPanel(QRemoteWidgetPanel)( 1461): onReceive = android.intent.action.PACKAGE_REMOVED, packageName : com.test.thalitest
D/KeyguardModel( 1461): mPackageIntentReceiver, received action: android.intent.action.PACKAGE_FULLY_REMOVED, sendingUserId:0
D/SplitUIManager( 1881): split_name #11 / not available #0
D/SplitUIService( 1881): removed split : 
V/BoardContentProvider( 2695): query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
I/GBoardWebViewUtils( 2065): checkExpiredAndRemoveCard() card: GBoardCard = { id: mw_initial
I/GBoardWebViewUtils( 2065): , create_time: 1430558575574
I/GBoardWebViewUtils( 2065): , expire_time: 0
I/GBoardWebViewUtils( 2065): , raw_uri: file:///system/etc/mrg_default_forms/MyWellness/initial/initial.html?id=mw_initial
I/GBoardWebViewUtils( 2065): , category: com.lge.intent.category.gboard.MYWELLNESS
I/GBoardWebViewUtils( 2065): , display: false
I/GBoardWebViewUtils( 2065): , animation: false }
I/GBoardWebViewUtils( 2065): checkExpiredAndRemoveCard() card: GBoardCard = { id: dyk000
I/GBoardWebViewUtils( 2065): , create_time: 1430558575600
I/GBoardWebViewUtils( 2065): , expire_time: 0
I/GBoardWebViewUtils( 2065): , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
I/GBoardWebViewUtils( 2065): , category: com.lge.intent.category.gboard.DOYOUKNOW
I/GBoardWebViewUtils( 2065): , display: false
I/GBoardWebViewUtils( 2065): , animation: false }
I/GBoardWebViewUtils( 2065): checkExpiredAndRemoveCard() card: GBoardCard = { id: guide_1111111111116_1452175674810
I/GBoardWebViewUtils( 2065): , create_time: 1452175675684
I/GBoardWebViewUtils( 2065): , expire_time: 0
I/GBoardWebViewUtils( 2065): , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/1/userguide.html?id=guide_1111111111116_1452175674810&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
I/GBoardWebViewUtils( 2065): , category: com.lge.intent.category.gboard.DOYOUKNOW
I/GBoardWebViewUtils( 2065): , display: false
I/GBoardWebViewUtils( 2065): , animation: false }
I/SystemUI[Framework]( 1032): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x8000, pkg=com.android.systemui
W/PhoneWindowManagerEx( 1032): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx( 1032): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx( 1032): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework]( 1032): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@3f2abfa1,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework]( 1032): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
V/SIM_STK ( 1032): Menu title from STK is T-Mobile
V/SIM_STK ( 1032): Menu title from STK is T-Mobile
D/WallpaperManager( 2065): suggestDesiredDimensions(2880, 2560) by package(com.lge.launcher2)
I/[LGHome]EVENT( 2065): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/administrator( 1032): Handling package changes for user 0
I/[LGHome]GBoardWebView( 2065): [GBoardWebView.java:321:loadCacheBitmap()]loadCacheBitmap()
I/LockScreenSettings( 6916): Wallpaper base directory = /data/user/0/com.lge.lockscreensettings/files/
D/SplitUIManager( 1881): split_name #11 / not available #0
I/SplitUIService( 1881): split app #11
D/KeyguardModel( 1461): package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
D/KeyguardModel( 1461): createShortcutInfo...
D/KeyguardModel( 1461): package = com.android.mms, class = com.android.mms.ui.ConversationList
D/KeyguardModel( 1461): createShortcutInfo...
V/SIM_STK ( 1032): Menu title from STK is T-Mobile
W/ResourcesManager( 1461): Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
W/ResourcesManager( 1461): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 1461): Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
W/ResourcesManager( 1461): Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
W/ResourceType( 1461): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1461): Failure retrieving resources for com.android.mms: Resource ID #0x0
D/KeyguardModel( 1461): package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
D/KeyguardModel( 1461): createShortcutInfo...
W/ActivityManager( 1032): getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
D/LGBluetoothAvrcpQcomAdapter( 6275): [BTUI] installed app name: Music
D/LGBluetoothAvrcpQcomAdapter( 6275): [BTUI] installed app name: Google Play Music
D/LGBluetoothAvrcpQcomAdapter( 6275): [BTUI] === MediaPlayerInfo (playerId:0) ===
D/LGBluetoothAvrcpQcomAdapter( 6275): [BTUI]          displayName: Music
D/LGBluetoothAvrcpQcomAdapter( 6275): [BTUI]          packageName: com.lge.music
D/LGBluetoothAvrcpQcomAdapter( 6275): [BTUI]          playState: 2 (PAUSED)
D/LGBluetoothAvrcpQcomAdapter( 6275): [BTUI] === MediaPlayerInfo (playerId:1) ===
D/LGBluetoothAvrcpQcomAdapter( 6275): [BTUI]          displayName: Google Play Music
D/LGBluetoothAvrcpQcomAdapter( 6275): [BTUI]          packageName: com.google.android.music
D/LGBluetoothAvrcpQcomAdapter( 6275): [BTUI]          playState: 2 (PAUSED)
D/LGBluetoothAvrcpQcomAdapter( 6275): [BTUI] [-] updateMediaPlayerInfo
W/ResourcesManager( 1461): Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
W/ResourcesManager( 1461): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourceType( 1461): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1461): Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
D/KeyguardModel( 1461): package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
D/KeyguardModel( 1461): createShortcutInfo...
W/ResourcesManager( 1461): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 1461): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 1461): Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
W/ResourcesManager( 1461): Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
W/ResourceType( 1461): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1461): Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
D/KeyguardModel( 1461): package = com.lge.camera, class = com.lge.camera.CameraApp
D/KeyguardModel( 1461): createShortcutInfo...
D/KeyguardModel( 1461): handleShortcutListChanged...
D/KeyguardModel( 1461): package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
D/KeyguardModel( 1461): createShortcutInfo...
D/KeyguardModel( 1461): package = com.android.mms, class = com.android.mms.ui.ConversationList
D/KeyguardModel( 1461): createShortcutInfo...
W/ResourceType( 1461): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1461): Failure retrieving resources for com.android.mms: Resource ID #0x0
D/KeyguardModel( 1461): package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
D/KeyguardModel( 1461): createShortcutInfo...
I/[LGHome]EVENT( 2065): [Launcher.java:5349:onStop()]onStop
W/ResourceType( 1461): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1461): Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
D/KeyguardModel( 1461): package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
D/KeyguardModel( 1461): createShortcutInfo...
W/ResourceType( 1461): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1461): Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
I/AppUp4:AppBoxCP( 6932): onCreate
W/AppUp4:DB( 6932):  [AppBoxDatabaseHelper] construct
D/KeyguardModel( 1461): package = com.lge.camera, class = com.lge.camera.CameraApp
D/KeyguardModel( 1461): createShortcutInfo...
I/ActivityManager( 1032): Killing 5969:com.lge.bnr/1000 (adj 15): empty for 1815s
I/AppUp4:DB( 6932):  setFingerPrint start
I/AppUp4:DB( 6932):  newfinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys SDK version = 21
I/AppUp4:DB( 6932):  beforefinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys
I/AppUp4:DB( 6932):  SDK version = 21
I/AppUp4:DB( 6932):  beforefinger == newfinger no write in DB
I/NotificationService( 1032): action=android.intent.action.PACKAGE_REMOVED queryReplace=false
D/BackupManagerService( 1032): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/JobSchedulerService( 1032): Receieved: android.intent.action.PACKAGE_REMOVED
I/ThermalEngine(  331): Thermal-Server: Thermal received msg from  override
I/Thermal-Lib( 3089): Thermal-Lib-Client: Client request sent
I/art     ( 1032): Explicit concurrent mark sweep GC freed 13744(830KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 44MB/66MB, paused 2.357ms total 247.074ms
I/[LGHome]Launcher.Model( 2065): [LauncherModel.java:2230:run()] LauncherModel bind current page shortcut
I/[LGHome]Launcher( 2065): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/[LGHome]EVENT( 2065): [Workspace.java:918:addInScreen()]Add Shortcut [Email] in screen 1 [1, 4]
I/[LGHome]EVENT( 2065): [Workspace.java:918:addInScreen()]Add Shortcut [Play Store] in screen 1 [2, 4]
I/[LGHome]EVENT( 2065): [Workspace.java:918:addInScreen()]Add Shortcut [Camera] in screen 1 [3, 4]
I/[LGHome]EVENT( 2065): [Workspace.java:918:addInScreen()]Add Shortcut [Settings] in screen 1 [4, 4]
D/KeyguardModel( 1461): handleShortcutListChanged...
W/libprocessgroup( 1032): failed to open /acct/uid_1000/pid_5969/cgroup.procs: No such file or directory
D/PhoneStatusBar( 1461): setSystemUiVisibility vis=8000 mask=ffffffff oldVal=0 newVal=8000 diff=8000
I/[SystemUI]NavigationThemeResource( 1461): NavigationKey Color is changed(BLACK -> WHITE_WITH_SHADOW)
I/[SystemUI]NavigationThemeResource( 1461):  BarMode=4, Theme=WHITE, LightBackground=false (Transparent)
I/[SystemUI]NavigationThemeResource( 1461): , Keyguard show=false, IME shown=false, Panel expanded=false
D/AppUp4:AppBoxApplication( 6932): AppBoxApplication onCreate()
D/TaskPersister( 1032): removeObsoleteFile: deleting file=4_task.xml
I/[LGHome]Launcher.Model( 2065): [LauncherModel.java:2244:run()] LauncherModel bind current page shortcut
I/[LGHome]Launcher( 2065): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/Timeline( 1032): Timeline: Activity_windows_visible id: ActivityRecord{37daed3d u0 com.lge.launcher2/.Launcher t3} time:2100913
I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 2065): [LGUnreadLgeEmailsBadge.java:107:countUnreadItems()]setTotalCount : 0
I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 2065): [LGUnreadLgeEmailsBadge.java:108:countUnreadItems()]countUnreadItems() ended..
D/AppUp4:PreloadHelper( 6932): added Exclude : com.test.thalitest
I/[LGHome]EVENT( 2065): [Workspace.java:918:addInScreen()]Add Folder [Google] in screen 1 [0, 4]
I/[LGHome]Launcher.Model( 2065): [LauncherModel.java:2256:run()] LauncherModel bind current page widget
I/[LGHome]Launcher( 2065): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/[Concierge]WidgetView( 2065): ConciergeWidgetView is instantiated. sIsWidgetAttached : true
W/ResourcesManager( 1032): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourceType( 1032): Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
D/AndroidRuntime( 6885): Shutting down VM
I/ActivityManager( 1032): Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=6959 uid=10019 gids={50019, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
I/ActivityManager( 1032): Killing 6373:com.lge.sync/1000 (adj 15): empty for 1815s
W/libprocessgroup( 1032): failed to open /acct/uid_1000/pid_6373/cgroup.procs: No such file or directory
D/[Concierge]Service( 2602): onStartCommand(). Type : 8
D/[Concierge]Service( 2602): Update widget. Component : {com.lge.concierge/com.lge.concierge.ConciergeWidgetProvider}
D/[Concierge]Service( 2602): Update widget ID : 11
D/[Concierge]WidgetView( 2065): change position of spinner
I/[Concierge]WidgetView( 2065): initWebView(). Time : 1452598512726
D/[Concierge]Service( 2602): onStartCommand(). Type : 0
W/ResourcesManager( 6959): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6959): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 6959): Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
W/ResourcesManager( 6959): Asset path '/system/framework/lghiddenlibs.jar' does not exist or contains no resources.
W/ResourcesManager( 6959): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
I/[Concierge]WebView( 2065): Return exist ConciergeWebView. Reuse : 755831269
D/[Concierge]WidgetView( 2065): State Change : null -> AccInBeforeState
I/[LgeWidgetLib]LgeAppWidgetHostView( 2065): [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
I/[LgeWidgetLib]ExtViewHost( 2065): [LgeAppWidgetExtViewHost.java:136:setState()]New State = com.lge.lgewidgetlib.extview.NormalState@2cf878d0
I/[LGHome]EVENT( 2065): [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.concierge.ConciergeWidgetProvider] in screen 1 [0, 0]
I/[LGHome]Launcher.Model( 2065): [LauncherModel.java:2256:run()] LauncherModel bind current page widget
I/[LGHome]Launcher( 2065): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/[LGHome]EVENT( 2065): [Workspace.java:918:addInScreen()]Add AppWidget [com.google.android.googlequicksearchbox.SearchWidgetProvider] in screen 1 [0, 2]
D/[Concierge]WidgetView( 2065): isWidgetUpdateSkippable ? true
I/[LGHome]EVENT( 2065): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
D/[Concierge]WidgetBroadcastReceiver( 2065): New receiver registered. Self-unregister old one. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
W/[Concierge]WidgetView( 2065): Widget kill message received. Destory myself. My : 1452596439671, New one : 1452598512726
D/[Concierge]WidgetView( 2065): Unregister all receivers
W/[Concierge]WidgetBroadcastReceiver( 2065): Tried unregister broadcastReceiver which is not registered. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
I/[LGHome]Launcher( 2065): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/[LGHome]EVENT( 2065): [Workspace.java:918:addInScreen()]Add Shortcut [Gallery] in screen 2 [0, 4]
I/[LGHome]EVENT( 2065): [Workspace.java:918:addInScreen()]Add Shortcut [Calendar] in screen 2 [1, 4]
I/[LGHome]EVENT( 2065): [Workspace.java:918:addInScreen()]Add Shortcut [QuickMemo+] in screen 2 [2, 4]
I/[LGHome]EVENT( 2065): [Workspace.java:918:addInScreen()]Add Shortcut [Quick Remote] in screen 2 [3, 4]
I/[LGHome]EVENT( 2065): [Workspace.java:918:addInScreen()]Add Shortcut [FM Radio] in screen 2 [4, 4]
I/[LGHome]Launcher( 2065): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/[LGHome]Launcher( 2065): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/SystemConfig( 6959): BUILD Country: EU
I/SystemConfig( 6959): BUILD Operator: OPEN
I/[LgeWidgetLib]LgeAppWidgetHostView( 2065): [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
E/[LgeWidgetLib]LgeAppWidgetHostView( 2065): [LgeAppWidgetHostView.java:124:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
I/[LGHome]EVENT( 2065): [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1] in screen 2 [0, 0]
I/[LGHome]Launcher( 2065): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/ActivityManager( 1032): Killing 6395:com.lge.lifetracker/u0a37 (adj 15): empty for 1815s
I/Timeline( 2065): Timeline: Activity_idle id: android.os.BinderProxy@1c7ec1e time:2101104
W/libprocessgroup( 1032): failed to open /acct/uid_10037/pid_6395/cgroup.procs: No such file or directory
I/SystemConfig( 6959): pm.hasSystemFeature(com.lge.ims.rcs) = false
I/SystemConfig( 6959): existFile = false
I/SystemConfig( 6959): canReadFile = false
I/SystemConfig( 6959): systemFeature RCS result false
D/SystemConfig( 6959): refreshRcsSupport() :false
D/VoicemailCleanupService( 2191): Cleaning up data for package: com.test.thalitest
I/chromium( 2065): [INFO:CONSOLE(0)] "'window.webkitStorageInfo' is deprecated. Please use 'navigator.webkitTemporaryStorage' or 'navigator.webkitPersistentStorage' instead.", source:  (0)
E/SQLiteLog( 2191): (3850) statement aborts at 37: [DELETE FROM calls WHERE (((source_package = 'com.test.thalitest'))) AND ((type = 4))] disk I/O error
--------- beginning of crash
E/AndroidRuntime( 2191): FATAL EXCEPTION: IntentService[VoicemailCleanupService]
E/AndroidRuntime( 2191): Process: android.process.acore, PID: 2191
E/AndroidRuntime( 2191): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 2191): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/AndroidRuntime( 2191): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:739)
E/AndroidRuntime( 2191): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:892)
E/AndroidRuntime( 2191): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/AndroidRuntime( 2191): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1600)
E/AndroidRuntime( 2191): 	at com.android.providers.contacts.util.DbModifierWithNotification.delete(DbModifierWithNotification.java:161)
E/AndroidRuntime( 2191): 	at com.android.providers.contacts.voicemail.VoicemailContentTable.delete(VoicemailContentTable.java:229)
E/AndroidRuntime( 2191): 	at com.android.providers.contacts.voicemail.VoicemailContentProvider.delete(VoicemailContentProvider.java:135)
E/AndroidRuntime( 2191): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:312)
E/AndroidRuntime( 2191): 	at android.content.ContentResolver.delete(ContentResolver.java:1315)
E/AndroidRuntime( 2191): 	at com.android.providers.contacts.voicemail.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
E/AndroidRuntime( 2191): 	at com.android.providers.contacts.voicemail.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
E/AndroidRuntime( 2191): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 2191): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 2191): 	at android.os.Looper.loop(Looper.java:135)
E/AndroidRuntime( 2191): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ActivityManager( 1032): Start proc com.lge.email for broadcast com.lge.email/.receiver.PackageChangeReceiver: pid=6984 uid=10023 gids={50023, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
I/Process ( 2191): Sending signal. PID: 2191 SIG: 9
E/DropBoxManagerService( 1032): Can't write: system_app_crash
E/DropBoxManagerService( 1032): java.io.FileNotFoundException: /data/system/dropbox/drop107.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 1032): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/DropBoxManagerService( 1032): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/DropBoxManagerService( 1032): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/DropBoxManagerService( 1032): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
E/DropBoxManagerService( 1032): 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
E/DropBoxManagerService( 1032): 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12437)
E/DropBoxManagerService( 1032): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 1032): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 1032): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/DropBoxManagerService( 1032): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/DropBoxManagerService( 1032): 	... 5 more
I/GBoardtInterface( 2065): onReloaded()
I/GBoardWebViewClient( 2065): onPageFinished url:file:///android_asset/www/main.html
W/ResourcesManager( 6984): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6984): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 6984): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
W/ResourcesManager( 6984): Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
I/ActivityManager( 1032): Process android.process.acore (pid 2191) has died
W/ActivityManager( 1032): Scheduling restart of crashed service com.android.providers.contacts/com.lge.providers.contacts.AliveAcoreService in 1000ms
W/ActivityManager( 1032): Scheduling restart of crashed service com.android.providers.contacts/.voicemail.VoicemailCleanupService in 11000ms
V/BoardContentProvider( 2695): query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
V/BoardContentProvider( 2695): query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
D/ActionManagerService( 1917): notifyUserLog: 1000001
D/LIA_Informant_ActionManagerMessageHandler( 2695): handleMessage: what(1000) actionID(0x1000001)
D/LIA_Informant_Tips_SmartTipsActionManager( 2695): onEvent() : ACTION_BOARD_ENABLED
D/ActionManagerService( 1917): notifyUserLog: 1000001
D/LIA_Informant_ActionManagerMessageHandler( 2695): handleMessage: what(1000) actionID(0x1000001)
D/LIA_Informant_Tips_SmartTipsActionManager( 2695): onEvent() : ACTION_BOARD_ENABLED
D/LIA_Informant_Tips_FormEventRepository( 2695): getSize() : size - 0
D/LIA_Informant_Tips_SmartTipsActionManager( 2695): onSettingEvent() : GBoard On - add scheduler - 0
V/BoardContentProvider( 2695): query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
D/GBoardUriUtils( 2065): fileExists: file:///system/etc/mrg_default_forms/MyWellness/initial/initial2.html?id=mw_initial return true
D/GBoardWebViewUtils( 2065): changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyWellness/initial/initial2.html?id=mw_initial
D/GBoardUriUtils( 2065): fileExists: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial2.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc] return true
D/GBoardWebViewUtils( 2065): changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial2.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
D/GBoardUriUtils( 2065): fileExists: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/1/userguide2.html?id=guide_1111111111116_1452175674810&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay return true
D/GBoardWebViewUtils( 2065): changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/1/userguide2.html?id=guide_1111111111116_1452175674810&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
E/SQLiteDatabase( 6984): Failed to open database '/data/data/com.lge.email/databases/Downloads.db'.
E/SQLiteDatabase( 6984): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 6984): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 6984): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 6984): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 6984): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 6984): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 6984): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 6984): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:907)
E/SQLiteDatabase( 6984): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:892)
E/SQLiteDatabase( 6984): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:795)
E/SQLiteDatabase( 6984): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1213)
E/SQLiteDatabase( 6984): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 6984): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 6984): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 6984): 	at com.lge.email.ui.largefile.DownloadProvider.onCreate(DownloadProvider.java:51)
E/SQLiteDatabase( 6984): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1714)
E/SQLiteDatabase( 6984): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1683)
E/SQLiteDatabase( 6984): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5014)
E/SQLiteDatabase( 6984): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4609)
E/SQLiteDatabase( 6984): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4549)
E/SQLiteDatabase( 6984): 	at android.app.ActivityThread.access$1500(ActivityThread.java:148)
E/SQLiteDatabase( 6984): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1344)
E/SQLiteDatabase( 6984): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 6984): 	at android.os.Looper.loop(Looper.java:135)
E/SQLiteDatabase( 6984): 	at android.app.ActivityThread.main(ActivityThread.java:5274)
E/SQLiteDatabase( 6984): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteDatabase( 6984): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteDatabase( 6984): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
E/SQLiteDatabase( 6984): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
W/System.err( 6984): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
W/System.err( 6984): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
W/System.err( 6984): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
W/System.err( 6984): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
W/System.err( 6984): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
W/System.err( 6984): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
W/System.err( 6984): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
W/System.err( 6984): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:907)
W/System.err( 6984): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:892)
W/System.err( 6984): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:795)
W/System.err( 6984): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1213)
W/System.err( 6984): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
W/System.err( 6984): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
W/System.err( 6984): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
W/System.err( 6984): 	at com.lge.email.ui.largefile.DownloadProvider.onCreate(DownloadProvider.java:51)
W/System.err( 6984): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1714)
W/System.err( 6984): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1683)
W/System.err( 6984): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5014)
W/System.err( 6984): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4609)
W/System.err( 6984): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4549)
W/System.err( 6984): 	at android.app.ActivityThread.access$1500(ActivityThread.java:148)
W/System.err( 6984): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1344)
W/System.err( 6984): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 6984): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 6984): 	at android.app.ActivityThread.main(ActivityThread.java:5274)
W/System.err( 6984): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 6984): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 6984): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
W/System.err( 6984): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
E/SQLiteDatabase( 6984): Failed to open database '/data/data/com.lge.email/databases/sqt.db'.
E/SQLiteDatabase( 6984): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 6984): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 6984): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 6984): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 6984): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 6984): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 6984): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 6984): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:907)
E/SQLiteDatabase( 6984): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:892)
E/SQLiteDatabase( 6984): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:795)
E/SQLiteDatabase( 6984): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1213)
E/SQLiteDatabase( 6984): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 6984): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 6984): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 6984): 	at com.lge.email.providers.sqt.SqtProvider.onCreate(SqtProvider.java:155)
E/SQLiteDatabase( 6984): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1714)
E/SQLiteDatabase( 6984): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1683)
E/SQLiteDatabase( 6984): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5014)
E/SQLiteDatabase( 6984): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4609)
E/SQLiteDatabase( 6984): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4549)
E/SQLiteDatabase( 6984): 	at android.app.ActivityThread.access$1500(ActivityThread.java:148)
E/SQLiteDatabase( 6984): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1344)
E/SQLiteDatabase( 6984): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 6984): 	at android.os.Looper.loop(Looper.java:135)
E/SQLiteDatabase( 6984): 	at android.app.ActivityThread.main(ActivityThread.java:5274)
E/SQLiteDatabase( 6984): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteDatabase( 6984): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteDatabase( 6984): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
E/SQLiteDatabase( 6984): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
D/AndroidRuntime( 6984): Shutting down VM
E/AndroidRuntime( 6984): FATAL EXCEPTION: main
E/AndroidRuntime( 6984): Process: com.lge.email, PID: 6984
E/AndroidRuntime( 6984): java.lang.RuntimeException: Unable to get provider com.lge.email.providers.sqt.SqtProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 6984): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5017)
E/AndroidRuntime( 6984): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4609)
E/AndroidRuntime( 6984): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4549)
E/AndroidRuntime( 6984): 	at android.app.ActivityThread.access$1500(ActivityThread.java:148)
E/AndroidRuntime( 6984): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1344)
E/AndroidRuntime( 6984): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 6984): 	at android.os.Looper.loop(Looper.java:135)
E/AndroidRuntime( 6984): 	at android.app.ActivityThread.main(ActivityThread.java:5274)
E/AndroidRuntime( 6984): 	at java.lang.reflect.Method.invoke(Native Method)
E/AndroidRuntime( 6984): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/AndroidRuntime( 6984): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
E/AndroidRuntime( 6984): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
E/AndroidRuntime( 6984): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 6984): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 6984): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/AndroidRuntime( 6984): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/AndroidRuntime( 6984): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 6984): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 6984): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 6984): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:907)
E/AndroidRuntime( 6984): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:892)
E/AndroidRuntime( 6984): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:795)
E/AndroidRuntime( 6984): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1213)
E/AndroidRuntime( 6984): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/AndroidRuntime( 6984): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/AndroidRuntime( 6984): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/AndroidRuntime( 6984): 	at com.lge.email.providers.sqt.SqtProvider.onCreate(SqtProvider.java:155)
E/AndroidRuntime( 6984): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1714)
E/AndroidRuntime( 6984): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1683)
E/AndroidRuntime( 6984): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5014)
E/AndroidRuntime( 6984): 	... 11 more
I/Process ( 6984): Sending signal. PID: 6984 SIG: 9
E/DropBoxManagerService( 1032): Can't write: system_app_crash
E/DropBoxManagerService( 1032): java.io.FileNotFoundException: /data/system/dropbox/drop108.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 1032): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/DropBoxManagerService( 1032): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/DropBoxManagerService( 1032): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/DropBoxManagerService( 1032): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
E/DropBoxManagerService( 1032): 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
E/DropBoxManagerService( 1032): 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12437)
E/DropBoxManagerService( 1032): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 1032): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 1032): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/DropBoxManagerService( 1032): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/DropBoxManagerService( 1032): 	... 5 more
I/qdhwcomposer(  280): handle_blank_event: dpy:0 panel power state: 0

```
