#### Test 56818254e6f5c3b_thali03_LGE-LG-D855 Logs


```
--------- beginning of main
V/SIM_STK ( 1028): Menu title from STK is T-Mobile
,I/art     ( 1028): Explicit concurrent mark sweep GC freed 37066(1608KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 43MB/65MB, paused 3.793ms total 129.642ms
V/GLSActivity( 2109): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/GLSUser ( 2109): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 2109): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2109): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2109): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2109): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/Finsky  ( 4865): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 4865): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 4865): [1] 5.onFinished: Giving up after 6 failures.
D/AndroidRuntime( 6125): 
D/AndroidRuntime( 6125): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 6125): CheckJNI is OFF
D/AndroidRuntime( 6125): Calling main entry com.android.commands.am.Am
--------- beginning of system
I/ActivityManager( 1028): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
V/SplitWindowPolicy( 1944): checkScreen => return. sourceIntent is null or not support SplitWindow component: ComponentInfo{co..../co.....MainActivity}
D/SplitInfo( 1028): new ActivitySplitInfo : ActivitySplitInfo [screenZone=0/ flag=0/ state=NATIVE]
D/ActivityManager( 1028): setTaskToReturnTo : TaskRecord{29d18a7f #4 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
D/ActivityManager( 1028): setTaskToReturnTo : TaskRecord{29d18a7f #4 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
D/WindowStateEx( 1028): AppWindowTokenEx init.. 
E/GBMv2   (  345): DFP En is all cleared set to be enabled
I/ActivityManager( 1028): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6150 uid=10311 gids={50311, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
D/AndroidRuntime( 6125): Shutting down VM
V/ActivityManager( 1028): Display changed displayId=0
D/DSDPConnection( 1850): Display #0 changed.
D/SplitWindowPolicy( 1944): updateActivityStateChanged: resumed=true, screenId=1, isScreenFull=true
D/SplitWindowPolicy( 1944): topRunningActivity=ActivityInfo{2c50eab co.....MainActivity}, taskId=4, activityType=0, bIsSplit=false
D/SplitWindowPolicy( 1944): updateActivityStateChanged: resumed=false, screenId=1, isScreenFull=true
D/SplitWindowPolicy( 1944): topRunningActivity=ActivityInfo{3ba18908 co.....MainActivity}, taskId=4, activityType=0, bIsSplit=false
D/ContextHelper( 6150): convertTheme. context->name=com.test.thalitest themeResourceId=16973833
,I/WebViewFactory( 6150): Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,I/LibraryLoader( 6150): Loading: webviewchromium
I/LibraryLoader( 6150): Time to load native libraries: 5 ms (timestamps 9926-9931)
,I/LibraryLoader( 6150): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 6150): Binding Chromium to main looper Looper (main, tid 1) {3dbe4a64}
,I/LibraryLoader( 6150): Expected native library version number "",actual native library version number ""
I/chromium( 6150): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 6150): Initializing chromium process, renderers=0
,W/art     ( 6150): Attempt to remove local handle scope entry from IRT, ignoring
W/chromium( 6150): [WARNING:dns_config_service_posix.cc(293)] Failed to read DnsConfig.
W/chromium( 6150): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
,I/chromium( 6150): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=32 off=46780 len=2953
I/chromium( 6150): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:33 off:229536 len:643667
V/AudioPolicyService(  324): registerClient() client 0xb54f4fc0, uid 10311
D/BluetoothManagerService( 1028): Message: 20
D/BluetoothManagerService( 1028): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@1723fb11:true
,D/BluetoothAdapter( 6150): 839406797: getState() :  mService = null. Returning STATE_OFF
I/Adreno-EGL( 6150): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 6150): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 6150): Build Date: 12/12/14 금
I/Adreno-EGL( 6150): Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
I/Adreno-EGL( 6150): Remote Branch: 
I/Adreno-EGL( 6150): Local Patches: 
I/Adreno-EGL( 6150): Reconstruct Branch: 
W/chromium( 6150): [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
,W/chromium( 6150): [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
W/art     ( 6150): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 6150): onDetachedFromWindow called when already detached. Ignoring
D/SystemWebViewEngine( 6150): CordovaWebView is running on device made by: LGE
,W/art     ( 6150): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 6150): Attempt to remove local handle scope entry from IRT, ignoring
,D/OpenGLRenderer( 6150): Render dirty regions requested: true
I/OpenGLRenderer( 6150): Initialized EGL, version 1.4
D/OpenGLRenderer( 6150): Enabling debug mode 0
,D/Atlas   ( 6150): Validating map...
D/SplitWindow( 1028): check instance of lgWin Window{13b9eb03 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,I/SystemUI[Framework]( 1028): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x0, pkg=com.android.systemui
,W/PhoneWindowManagerEx( 1028): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx( 1028): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx( 1028): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework]( 1028): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@2eb1cc2b,  pkg=WindowManager.LayoutParams
D/PhoneStatusBar( 1446): setSystemUiVisibility vis=0 mask=ffffffff oldVal=8000 newVal=0 diff=8000
I/[SystemUI]NavigationThemeResource( 1446): NavigationKey Color is changed(WHITE_WITH_SHADOW -> BLACK)
I/[SystemUI]NavigationThemeResource( 1446):  BarMode=0, Theme=WHITE, LightBackground=false (Transparent)
I/[SystemUI]NavigationThemeResource( 1446): , Keyguard show=false, IME shown=false, Panel expanded=false
I/SystemUI[Framework]( 1028): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
D/LgDataFeature( 6150): LgDataFeature() Constructor: none
D/LgDataFeature( 6150): LgDataFeature() Constructor Done, null
,I/ActivityManager( 1028): Displayed com.test.thalitest/.MainActivity: +592ms (total +682ms)
,I/Timeline( 1028): Timeline: Activity_windows_visible id: ActivityRecord{3a4da4c u0 com.test.thalitest/.MainActivity t4} time:250333
I/Timeline( 6150): Timeline: Activity_idle id: android.os.BinderProxy@14250b3d time:250336
D/JsMessageQueue( 6150): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log( 6150): JniHelper::setJavaVM(0xb487c280), pthread_self() = -1435098880
,I/chromium( 6150): [INFO:SkFontConfigInterface_android.cpp(247)] ---- failed to open </system/fonts/CutiveMono.ttf> as a font
I/chromium( 6150): 
,I/chromium( 6150): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/chromium( 6150): [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
I/chromium( 6150): 
,E/GBMv2   (  345): DFP En is all cleared set to be enabled
E/GBMv2   (  345): Set value is all cleared set the max
I/GBMv2   (  345): DFP Enabled. Ignore VFP set
,W/jxcore-log( 6150): Initializing JXcore engine
W/jxcore-log( 6150): JXcore engine is ready
W/Thread-684( 6216): type=1400 audit(0.0:146): avc: denied { ioctl } for path="socket:[8312]" dev="sockfs" ino=8312 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
W/Thread-684( 6216): type=1400 audit(0.0:147): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3222 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
W/Thread-684( 6216): type=1400 audit(0.0:148): avc: denied { ioctl } for path="socket:[8443]" dev="sockfs" ino=8443 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
W/Thread-684( 6216): type=1400 audit(0.0:149): avc: denied { ioctl } for path="/cust" dev="mmcblk0p42" ino=2 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=dir
W/Thread-684( 6216): type=1400 audit(0.0:150): avc: denied { ioctl } for path="socket:[30020]" dev="sockfs" ino=30020 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
W/jxcore-log( 6150): Starting JXcore engine
W/jxcore-log( 6150): Platform android
W/jxcore-log( 6150): 
W/jxcore-log( 6150): Process ARCH arm
W/jxcore-log( 6150): 
I/jxcore-log( 6150): JXcore Cordova bridge is ready!
I/jxcore-log( 6150): 
W/jxcore-log( 6150): JXcore engine is started
I/jxcore-log( 6150): Toggling radios to true
I/jxcore-log( 6150): 
D/BluetoothManagerService( 1028): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1028): enable():  mBluetooth =null mBinding = false
D/LocationManagerService( 1028): getAllProviders()=[passive, gps, network]
D/Ulp_jni ( 1028): JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
D/Ulp_jni ( 1028): JNI:system_update. Event-4
D/BluetoothManagerService( 1028): Message: 1
D/BluetoothManagerService( 1028): MESSAGE_ENABLE: mBluetooth = null
D/WifiService( 1028): New client listening to asynchronous messages
I/ActivityManager( 1028): Start proc com.android.bluetooth for service com.android.bluetooth/.btservice.AdapterService: pid=6231 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008, 4002, 1023} abi=armeabi-v7a
D/WifiServiceImplEx( 1028): setWifiEnabled: true pid=6150, uid=10311, package= com.test.thalitest, App Lable : ThaliTest
D/WifiService( 1028): setWifiEnabled: true pid=6150, uid=10311
E/WifiService( 1028): Invoking mWifiStateMachine.setWifiEnabled
D/LocationManagerService( 1028): getAllProviders()=[passive, gps, network]
D/Ulp_jni ( 1028): JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 1,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
D/Ulp_jni ( 1028): JNI:system_update. Event-4
E/WifiStateMachine( 1028):  InitialState CMD_START_SUPPLICANT 0 0
I/LGFTMITEM( 1028): [GET_FTM][id=6], offset=12288
D/WifiServiceImplEx( 1028): disconnect pid=6150, uid=10311, packageName=com.test.thalitest
D/WifiServiceImplEx( 1028): reconnect pid=6150, uid=10311, packageName=com.test.thalitest
I/jxcore-log( 6150): Radios toggled
I/jxcore-log( 6150): 
I/jxcore-log( 6150): My device name is: LGE-LG-D855
I/jxcore-log( 6150): 
E/WifiUtil( 1028): wfc_util_ffile_check_copy(): pid[1028] pDestFName[/data/misc/wifi/WCNSS_qcom_cfg.ini] pSourceFName[/system/etc/wifi/WCNSS_qcom_cfg.ini]
E/WifiUtil( 1028): wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
E/WifiUtil( 1028): wfc_util_ffile_check_copy(): pid[1028] pDestFName[/data/misc/wifi/WCNSS_qcom_wlan_nv.bin] pSourceFName[/system/etc/wifi/WCNSS_qcom_wlan_nv.bin]
E/WifiUtil( 1028): wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
I/WifiUtil( 1028): Intf0MacAddress=C49A027B60AC
E/WifiHW  ( 1028): unknown target_country: EU , set to default
E/WifiHW  ( 1028): [wifi_ensure_config_files] default country1 = GB
E/WifiHW  ( 1028): [wifi_ensure_config_files] default country2 = GB
I/WifiUtil( 1028): gEnableBmps=1
W/ResourcesManager( 6231): Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
W/ResourcesManager( 6231): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 6231): Asset path '/system/framework/com.qcom.bluetooth.jar' does not exist or contains no resources.
W/ResourcesManager( 6231): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
D/BluetoothAdapterApp( 6231): Loading JNI Library
D/BluetoothAdapterApp( 6231): REFCOUNT: Constructed com.android.bluetooth.btservice.AdapterApp@3a43ab8 Instance Count = 1
,D/SoftapController(  319): Softap fwReload - Ok
D/Tethering( 1028): sendTetherStateChangedBroadcast 1, 0, 0
D/libc-netbsd(  319): default dns: query_ipv6=0, query_ipv4=0
D/CommandListener(  319): Setting iface cfg
D/CommandListener(  319): Trying to bring down wlan0
D/Tethering( 1028): InitialState.processMessage what=4
,D/DSQN    ( 1028): DNSproblemNotiEnabled is disabled ignore DNS fail CB
D/CommandListener(  319): Clearing all IP addresses on wlan0
I/ActivityManager( 1028): Start proc com.android.settings for broadcast com.android.settings/.deviceinfo.UsbSettingsReceiver: pid=6269 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
D/Tethering( 1028): sendTetherStateChangedBroadcast 0, 0, 0
D/BluetoothAdapterApp( 6231): onCreate
,D/ProfileConfigQcom( 6231): [BTUI] HeadsetService is supported
D/ProfileConfigQcom( 6231): Adding HeadsetService
D/ProfileConfigQcom( 6231): [BTUI] A2dpService is supported
D/ProfileConfigQcom( 6231): Adding A2dpService
D/ProfileConfigQcom( 6231): [BTUI] HidService is supported
D/ProfileConfigQcom( 6231): Adding HidService
D/ProfileConfigQcom( 6231): [BTUI] HealthService is supported
D/ProfileConfigQcom( 6231): Adding HealthService
D/LGBluetoothFeatureConfig( 6231): isSupportPan() :  mTargetOp=OPEN
D/ProfileConfigQcom( 6231): [BTUI] PanService is supported
D/ProfileConfigQcom( 6231): Adding PanService
D/ProfileConfigQcom( 6231): [BTUI] GattService is supported
D/ProfileConfigQcom( 6231): Adding GattService
D/ProfileConfigQcom( 6231): [BTUI] BluetoothMapService is supported
D/ProfileConfigQcom( 6231): Adding BluetoothMapService
D/ProfileConfigQcom( 6231): [BTUI] HeadsetClientService is NOT supported
D/BluetoothManagerService( 1028): Message: 20
D/BluetoothManagerService( 1028): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@c93d962:true
,D/BluetoothAdapterState( 6231): make
I/LGFMServiceAdapter( 6231): [FM] LGFMServiceAdapter : create
W/ResourcesManager( 6269): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6269): Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
I/BluetoothAdapterState( 6231): Entering OffState
W/ResourcesManager( 6269): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
I/bluedroid-qcom( 6231): init
W/ResourcesManager( 6269): Asset path '/system/framework/com.lge.bluetooth.jar' does not exist or contains no resources.
W/ResourcesManager( 6269): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
W/ResourcesManager( 6269): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
I/bte_conf( 6231): bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
I/bte_conf( 6231): bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
E/bt_osi_config( 6231): config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
I/bte_conf( 6231): bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
D/BTIF_CORE( 6231): [BTUI] lge_load_bluetooth_address
I/bluedroid-qcom( 6231): get_profile_interface socket
I/bluedroid-qcom( 6231): get_profile_interface map_client
I/GKI_LINUX( 6231): gki_task_entry task_id=1 [BTIF] starting
D/BluetoothAdapterProperties( 6231): Address is:58:3F:54:73:64:C0
,D/BluetoothManagerService( 1028): Bluetooth Adapter name changed to G3-1
D/BluetoothManagerService( 1028): Stored Bluetooth name: G3-1
D/BluetoothManagerService( 1028): BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
D/BluetoothAdapterProperties( 6231): Name is: G3-1
W/bdaddr_loader( 6291): type=1400 audit(0.0:151): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
D/BluetoothManagerService( 1028): Message: 40
D/BluetoothManagerService( 1028): MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
W/bdaddr_loader( 6291): type=1400 audit(0.0:152): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
D/lge_bdaddr_loader( 6291): [BTUI] bdaddr_loader ::: START
D/lge_bdaddr_loader( 6291): [BTUI] bluetooth_load_bdaddress
I/LGFTMITEM( 6291): [GET_FTM][id=8], offset=16384
D/lge_bdaddr_loader( 6291): [BTUI] bdaddr to set in property : 58:3F:54:73:64:C0
I/bluedroid-qcom( 6231): config_hci_snoop_log
D/BluetoothManagerService( 1028): Calling onBluetoothServiceUp callbacks
D/BluetoothManagerService( 1028): Broadcasting onBluetoothServiceUp() to 7 receivers.
E/lge_bdaddr_loader( 6291): [BTUI] bluetooth_load_bdaddress : OK => 58:3F:54:73:64:C0
D/lge_bdaddr_loader( 6291): [BTUI] bdaddr_loader ::: END
V/LGMDMManagerInternal( 6231): Create singleton instance
E/WifiHW  ( 1028): Cannot open "/system/etc/wifi/autojoinconfig.txt": No such file or directory
E/WifiStateMachine( 1028): Couldn't get getWiFiOffloadingIface : 
E/WifiStateMachine( 1028): useWiFiOffloading() : false
E/WifiStateMachine( 1028): CONFIG_LGE_WLAN_PATH : true
D/WifiMonitor( 1028): startMonitoring(wlan0) with mConnected = false
D/WifiMonitor( 1028): connecting to supplicant
,V/WfdStateTracker( 1944): WfdStateTracker handleDirectStateChangedEvent: 1
W/wpa_supplicant( 6292): type=1400 audit(0.0:153): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
W/wpa_supplicant( 6292): type=1400 audit(0.0:154): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
D/StatusBar.NetworkController( 1446): refreshViews: Data not connected!! Set no data type icon / Roaming
I/WifiServerServiceExt( 1028): WIFI_STATE_CHANGED_ACTION [2]
I/wpa_supplicant( 6292): Successfully initialized wpa_supplicant
,I/wpa_supplicant( 6292): rfkill: Cannot open RFKILL control device
I/wpa_supplicant( 6292): [LGE_PATCH] unset P2P_CAPABLE to ifname wlan0
D/BluetoothAdapterState( 6231): CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
D/BluetoothAdapterProperties( 6231): Setting state to 11
I/BluetoothAdapterState( 6231): Bluetooth adapter state changed: 10-> 11
I/LGBluetoothServiceJni( 6231): classInitNative: succeeds
D/BluetoothManagerService( 1028): Message: 60
,D/BluetoothManagerService( 1028): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
D/BluetoothManagerService( 1028): Bluetooth State Change Intent: 10 -> 11
D/LGBluetoothAPIService( 1944): [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
D/BluetoothBondStateMachine( 6231): make
I/[SystemUI]BluetoothHandler( 1446): Receive : BluetoothAdapter.ACTION_STATE_CHANGED
D/BluetoothAdapterService( 6231): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@20043093
I/BluetoothBondStateMachine( 6231): StableState(): Entering Off State
D/LGBluetoothServiceAdapter( 6231): [BTUI] check adapter is available - false.
D/BluetoothAdapterService( 6231): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@20043093
D/LGBluetoothServiceAdapter( 6231): [BTUI] check adapter is available - true : set adapter available.
D/LGBluetoothSettingsDBObserver( 6231): [BTUI] register observer for LG device name DB
E/BluetoothAdapterService( 6231): File transfer profiles supported!!
E/BluetoothAdapterService( 6231): File transfer profiles supported!!
,D/HeadsetService( 6231): Received start request. Starting profile...
D/BluetoothHeadset( 1850): Proxy object connected
I/LGBluetoothHeadsetServiceJni( 6231): classInitNative: succeeds
D/LGBluetoothHfpAdapter( 6231): Version 1.6
D/BluetoothHeadset( 1850): Proxy object connected
D/BluetoothHeadset( 1850): Proxy object connected
D/BluetoothHeadset( 1028): Proxy object connected
D/LGBluetoothFeatureConfig( 6231): isPrivacyLogsEnabled : true
I/BluetoothHeadsetServiceJni( 6231): classInitNative: succeeds
D/HeadsetStateMachine( 6231): make
E/BluetoothAdapterService( 6231): File transfer profiles supported!!
E/BluetoothAdapterService( 6231): File transfer profiles supported!!
E/BluetoothAdapterService( 6231): File transfer profiles supported!!
E/BluetoothAdapterService( 6231): File transfer profiles supported!!
E/BluetoothAdapterService( 6231): File transfer profiles supported!!
,V/LGMDMManager( 6231): Create singleton instance
I/BluetoothAdapterState( 6231): Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
D/LgDataFeature( 6231): LgDataFeature() Constructor: none
D/LgDataFeature( 6231): LgDataFeature() Constructor Done, null
D/HeadsetStateMachine( 6231): max_hf_connections = 1
I/bluedroid-qcom( 6231): get_profile_interface handsfree
V/ToneGenerator( 6231): ToneGenerator constructor: streamType=8, volume=1.000000
V/AudioPolicyService(  324): registerClient() client 0xb558a200, uid 1002
V/AudioPolicyManager(  324): getOutput() device 2, stream 8, samplingRate 0, format 0, channelMask 3, flags 0
V/AudioPolicyManagerEx(  324): AudioPolicyManagerEx: getOutputForDevice
,V/AudioPolicyManagerEx(  324): getOutput() returns output 2
V/AudioSystem( 6231): getOutputSamplingRate() no output descriptor for output 2 in gOutputs
V/AudioFlinger(  324): registerClient() client 0xb55814f0, pid 6231
V/AudioSystem(  324): ioConfigChanged() event 0, ioHandle 2
V/AudioSystem(  324): ioConfigChanged() opening already existing output! 2
V/AudioSystem( 1446): ioConfigChanged() event 0, ioHandle 2
V/AudioSystem( 1446): ioConfigChanged() opening already existing output! 2
V/AudioSystem( 1028): ioConfigChanged() event 0, ioHandle 2
V/AudioSystem( 1028): ioConfigChanged() opening already existing output! 2
V/AudioSystem( 1850): ioConfigChanged() event 0, ioHandle 2
V/AudioSystem( 1850): ioConfigChanged() opening already existing output! 2
V/AudioSystem(  324): ioConfigChanged() event 0, ioHandle 4
V/AudioSystem(  324): ioConfigChanged() opening already existing output! 4
V/AudioSystem( 2188): ioConfigChanged() event 0, ioHandle 2
V/AudioSystem( 2188): ioConfigChanged() opening already existing output! 2
V/AudioSystem( 1850): ioConfigChanged() event 0, ioHandle 4
V/AudioSystem( 1850): ioConfigChanged() opening already existing output! 4
V/AudioSystem( 2188): ioConfigChanged() event 0, ioHandle 4
V/AudioSystem( 2188): ioConfigChanged() opening already existing output! 4
V/AudioSystem( 1028): ioConfigChanged() event 0, ioHandle 4
V/AudioSystem( 1028): ioConfigChanged() opening already existing output! 4
V/AudioSystem( 3211): ioConfigChanged() event 0, ioHandle 2
V/AudioSystem( 3211): ioConfigChanged() opening already existing output! 2
V/AudioSystem( 3211): ioConfigChanged() event 0, ioHandle 4
V/AudioSystem( 3211): ioConfigChanged() opening already existing output! 4
V/AudioSystem( 1446): ioConfigChanged() event 0, ioHandle 4
V/AudioSystem( 1446): ioConfigChanged() opening already existing output! 4
V/AudioSystem( 6231): ioConfigChanged() event 0, ioHandle 2
V/AudioSystem( 6231): ioConfigChanged() new output samplingRate 48000, format 0x5 channel mask 0x3 frameCount 960 latency 50
V/AudioSystem( 6231): ioConfigChanged() event 0, ioHandle 4
V/AudioSystem( 6231): ioConfigChanged() new output samplingRate 48000, format 0x1 channel mask 0x3 frameCount 960 latency 80
V/ToneGenerator( 6231): Create Track: 0xb4928a80
V/AudioTrack( 6231): set(): streamType 8, sampleRate 0, format 0x1, channelMask 0x1, frameCount 0, flags #4, notificationFrames 0, sessionId 0, transferType 1
V/AudioTrack( 6231): set() streamType 8, sampleRate 0, format 1, frameCount 0, flags 0004
V/AudioPolicyManager(  324): getOutputForAttr() usage=3, content=4, tag= flags=00000000
V/AudioPolicyManager(  324): getOutputForAttr() device 2, samplingRate 0, format 0, channelMask 3, flags 0
V/AudioPolicyManagerEx(  324): AudioPolicyManagerEx: getOutputForDevice
V/AudioPolicyManagerEx(  324): getOutput() returns output 2
I/AudioFlinger(  324): isAudioPlaybackHookOn() false
V/AudioPolicyManager(  324): getOutputForAttr() usage=3, content=4, tag= flags=00000000
,V/AudioPolicyManager(  324): getOutputForAttr() device 2, samplingRate 48000, format 1, channelMask 1, flags 4
V/AudioPolicyManagerEx(  324): AudioPolicyManagerEx: getOutputForDevice
V/AudioPolicyManagerEx(  324): getOutput() returns output 2
V/AudioSystem( 6231): getLatency() output 2, latency 50
V/AudioSystem( 6231): getFrameCount() output 2, frameCount 960
V/AudioTrack( 6231): createTrack_l() output 2 afLatency 50
V/AudioFlinger(  324): [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
V/AudioFlinger(  324): [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
V/AudioFlinger(  324): [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
V/AudioFlinger(  324): [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
V/AudioFlinger(  324): createTrack() lSessionId: 16
V/AudioTrack( 6231): AUDIO_OUTPUT_FLAG_FAST successful; frameCount 480
V/AudioFlinger(  324): acquiring 16 from 6231, for 6231
V/AudioFlinger(  324):  added new entry for 16
V/ToneGenerator( 6231): ToneGenerator INIT OK, time: 253292
D/BluetoothAdapterService( 6231): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@20043093
D/HeadsetStateMachine( 6231): Enter Disconnected: -2, size: 0
D/HeadsetPhoneState( 6231): [BTUI] listenForPhoneState : start = false
D/LGBluetoothHfpManager( 6231): [BTUI] listenForMultiSimPhoneState : start = false
D/BluetoothAdapterService( 6231): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@20043093
D/HeadsetStateMachine( 6231): [BTUI] change sampling rate to 8000 when device is disconnected
D/BluetoothA2dp( 1028): Proxy object connected
V/AudioFlinger(  324): setParameters(): io 0, keyvalue bt_samplerate=8000, calling pid 6231
D/A2dpService( 6231): Received start request. Starting profile...
D/audio_hw_primary(  324): adev_set_parameters: enter: bt_samplerate=8000
V/voice   (  324): voice_set_parameters: enter: bt_samplerate=8000
V/compress_voip(  324): voice_extn_compress_voip_set_parameters: enter: bt_samplerate=8000
V/compress_voip(  324): voice_extn_compress_voip_set_parameters: exit
V/voice   (  324): voice_set_parameters: exit with code(0)
V/msm8974_platform_lge(  324): LGE_platform_set_parameters: enter: bt_samplerate=8000
V/msm8974_platform(  324): platform_set_parameters: enter: bt_samplerate=8000
V/msm8974_platform(  324): platform_set_parameters: exit with code(0)
V/lge_audio_loopback(  324): lge_platform_set_loopback_parameters: enter: 
V/audio_hw_primary(  324): adev_set_parameters: exit with code(0)
E/audio_a2dp_hw(  324): adev_set_parameters: ERROR: set param called even when stream out is null
V/ToneGenerator( 6231): ToneGenerator destructor
V/ToneGenerator( 6231): stopTone
V/ToneGenerator( 6231): Delete Track: 0xb4928a80
I/BluetoothAvrcpServiceJni( 6231): classInitNative: succeeds
V/AudioTrack( 6231): ~AudioTrack, releasing session id from 6231 on behalf of 6231
V/AudioFlinger(  324): releasing 16 from 6231 for 6231
V/AudioFlinger(  324):  decremented refcount to 0
V/AudioFlinger(  324): purging stale effects
V/AudioPolicyService(  324): AudioCommandThread() adding release output 2
V/AudioPolicyService(  324): inserting command: 6 at index 0, num commands 0
V/AudioFlinger(  324): PlaybackThread::Track destructor
V/AudioPolicyService(  324): AudioCommandThread() waking up
V/AudioFlinger(  324): removeClient_l() pid 6231, calling pid 324
V/AudioPolicyService(  324): AudioCommandThread() processing release output 2
V/AudioPolicyManager(  324): releaseOutput() 2
V/AudioPolicyService(  324): AudioCommandThread() going to sleep
V/Avrcp   ( 6231): make
D/Avrcp   ( 6231): [BTUI] Use Native AVRCP : init jni
I/bluedroid-qcom( 6231): get_profile_interface avrcp
W/Process ( 1028): Unable to open /proc/6295/status
,V/AudioManager( 6231): registerRemoteController: size of Media player list: 0
D/UsbSettingsReceiver( 6269): [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
D/UsbSettingsReceiver( 6269): [AUTORUN] sys.usb.config = ptp_only,adb
D/UsbSettingsReceiver( 6269): [AUTORUN] sys.usb.state = ptp_only,adb
D/UsbSettingsReceiver( 6269): [AUTORUN] persist.sys.usb.config = ptp_only,adb
D/UsbSettingsReceiver( 6269): [AUTORUN] onReceive() : app userid = 0, current userid = 0
E/AudioManager( 6231): No RCC entry present to update
E/RemoteController( 6231): Cannot set synchronization mode on an unregistered RemoteController
I/BluetoothAvrcpQcomServiceJni( 6231): classInitQcomNative: succeeds
D/LGBluetoothAvrcpQcomAdapter( 6231): [BTUI] Use QCOM AVRCP 1.5 : init jni, browsing = false
I/BluetoothAvrcpQcomServiceJni( 6231): initQcomNative: succeeds
D/LGBluetoothAvrcpQcomAdapter( 6231): [BTUI] [+] updateMediaPlayerInfo
D/UsbSettingsControl( 6269): [AUTORUN] getUsbConnected() : connected=true
D/UsbSettingsReceiver( 6269): [AUTORUN] onReceive() : availableList=[wlan0]
D/UsbSettingsReceiver( 6269): [AUTORUN] onReceive() : activeList=[]
D/UsbSettingsReceiver( 6269): [AUTORUN] onReceive() : errorList=[]
D/UsbSettingsControl( 6269): [AUTORUN] isAutorunTimer() : mAutorunChanging=false
D/UsbSettingsReceiver( 6269): [AUTORUN] onReceive() : TetherState Changed=wlan0
D/UsbSettingsControl( 6269): [AUTORUN] setTetherStatus() : status=false
I/wpa_supplicant( 6292): rfkill: Cannot open RFKILL control device
,I/ActivityManager( 1028): Killing 5474:com.lge.appbox.client/u0a11 (adj 15): empty #17
V/SIM_STK ( 1028): Menu title from STK is T-Mobile
V/SIM_STK ( 1028): Menu title from STK is T-Mobile
,I/wpa_supplicant( 6292): [LGE_WLAN_PATCH]P2P 5GHz support level:2(0:no 1:gconly 2:gconly_UNII1 3:full)
I/wpa_supplicant( 6292): p2p0: CTRL-EVENT-AVOID-FREQ ranges=
I/wpa_supplicant( 6292): wlan0: CTRL-EVENT-SCAN-STARTED 
E/WifiStateMachine( 1028):  SupplicantStartingState CMD_SET_OPERATIONAL_MODE 1 0
E/WifiStateMachine( 1028):  SupplicantStartingState CMD_START_DRIVER 0 0
E/WifiStateMachine( 1028):  SupplicantStartingState CMD_SET_HIGH_PERF_MODE 0 0
D/WifiMonitor( 1028): Event [IFNAME=p2p0 CTRL-EVENT-AVOID-FREQ ranges=]
E/WifiStateMachine( 1028):  DefaultState CMD_SET_HIGH_PERF_MODE 0 0
D/WifiMonitor( 1028): Dropping event because (p2p0) is stopped
D/WifiMonitor( 1028): Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
E/WifiStateMachine( 1028):  SupplicantStartingState CMD_DISCONNECT 0 0
E/WifiStateMachine( 1028):  DefaultState CMD_DISCONNECT 0 0
E/WifiMonitor( 1028): WifiMonitor:wlan0 cnt=0 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiStateMachine( 1028):  SupplicantStartingState CMD_RECONNECT 0 0
E/WifiMonitor( 1028): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiStateMachine( 1028):  DefaultState CMD_RECONNECT 0 0
E/WifiMonitor( 1028): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
E/WifiStateMachine( 1028):  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1028):  DefaultState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1028):  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1028):  DefaultState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1028):  SupplicantStartingState SUP_CONNECTION_EVENT 0 0
D/WifiNative-wlan0( 1028): doString: [DRIVER MACADDR]
,D/WifiNative-wlan0( 1028):    returned Macaddr = c4:9a:02:7b:60:ac
D/WifiStateMachine( 1028): MAC Addr from driver = c4:9a:02:7b:60:ac
D/WifiOffDelayIfNotUsed( 1028): setPowerSaveActivated(false)
D/UsbSettingsReceiver( 6269): [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
D/UsbSettingsReceiver( 6269): [AUTORUN] sys.usb.config = ptp_only,adb
D/UsbSettingsReceiver( 6269): [AUTORUN] sys.usb.state = ptp_only,adb
D/UsbSettingsReceiver( 6269): [AUTORUN] persist.sys.usb.config = ptp_only,adb
W/libprocessgroup( 1028): failed to open /acct/uid_10011/pid_5474/cgroup.procs: No such file or directory
E/WifiStateMachine( 1028): Couldn't get getWiFiOffloadingIface : 
E/WifiStateMachine( 1028): useWiFiOffloading() : false
E/WifiStateMachine( 1028): CONFIG_LGE_WLAN_PATH : true
D/UsbSettingsReceiver( 6269): [AUTORUN] onReceive() : app userid = 0, current userid = 0
D/WifiNative-wlan0( 1028): doBoolean: SET update_config 1
W/Settings( 1028): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1028): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/StatusBar.NetworkController( 1446): refreshViews: Data not connected!! Set no data type icon / Roaming
D/WfdService( 1944): Waiting for WifiP2p enabling
,D/WifiNative-wlan0( 1028): SET update_config 1: returned true
D/WifiConfigStore( 1028): Loading config and enabling all networks 
,D/WifiNative-wlan0( 1028): doString: [LIST_NETWORKS]
I/WifiServerServiceExt( 1028): WIFI_STATE_CHANGED_ACTION [3]
D/WifiNative-wlan0( 1028):    returned network id / ssid / bssid / flags 0	NG700	any	
I/WifiServerServiceExt( 1028): batteryPsActivateMsgHandler : state:0 event:3
D/UsbSettingsControl( 6269): [AUTORUN] getUsbConnected() : connected=true
E/WifiConfigStore( 1028): readNetworkVariablesFromSupplicantFile key=psk
D/UsbSettingsReceiver( 6269): [AUTORUN] onReceive() : availableList=[]
D/UsbSettingsReceiver( 6269): [AUTORUN] onReceive() : activeList=[]
D/UsbSettingsReceiver( 6269): [AUTORUN] onReceive() : errorList=[]
D/UsbSettingsControl( 6269): [AUTORUN] isAutorunTimer() : mAutorunChanging=false
D/UsbSettingsControl( 6269): [AUTORUN] setTetherStatus() : status=false
,E/WifiConfigStore( 1028): readNetworkVariableFromSupplicantFile ssid=["NG700"] key=psk
E/WifiConfigStore( 1028): Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
,I/ActivityManager( 1028): Start proc com.lge.formmanager for broadcast com.lge.formmanager/.FormServiceReceiver: pid=6300 uid=10026 gids={50026, 9997, 3003, 1028} abi=armeabi-v7a
D/WifiStateMachine( 1028): enableVerboseLogging : level 2
D/WifiNative-wlan0( 1028): doBoolean: SET device_name g3_global_com
D/WifiNative-wlan0( 1028): SET device_name g3_global_com: returned true
D/WifiNative-wlan0( 1028): doBoolean: SET manufacturer LGE
D/WifiNative-wlan0( 1028): SET manufacturer LGE: returned true
D/WifiNative-wlan0( 1028): doBoolean: SET model_name LG-D855
D/WifiNative-wlan0( 1028): SET model_name LG-D855: returned true
D/WifiNative-wlan0( 1028): doBoolean: SET model_number LG-D855
D/WifiNative-wlan0( 1028): SET model_number LG-D855: returned true
D/WifiNative-wlan0( 1028): doBoolean: SET serial_number LGD8553bed2d08
D/WifiNative-wlan0( 1028): SET serial_number LGD8553bed2d08: returned true
D/WifiNative-wlan0( 1028): doBoolean: SET config_methods physical_display virtual_push_button
D/WifiNative-wlan0( 1028): SET config_methods physical_display virtual_push_button: returned true
D/WifiNative-wlan0( 1028): doBoolean: SET device_type 10-0050F204-5
D/WifiNative-wlan0( 1028): SET device_type 10-0050F204-5: returned true
D/WfdsService( 1944): Supplicant Connection state is changed : true
,D/WfdsService( 1944): DefaultState - WIFI_SUPPLICANT_CONNECTED
W/Settings( 6022): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WfdsService( 1944): Set the WFDS Monitor: true
D/WifiStateMachine( 1028): Setting OUI to DA-A1-19
D/WifiNative-wlan0( 1028): doBoolean: SCAN_INTERVAL 120
D/WifiNative-wlan0( 1028): SCAN_INTERVAL 120: returned true
D/WifiNative-HAL( 1028): Setting external_sim to 1
D/WifiNative-wlan0( 1028): doBoolean: SET external_sim 1
D/WifiNative-wlan0( 1028): SET external_sim 1: returned true
I/WifiNative-HAL( 1028): startHal
E/wifi    ( 1028): getStaticLongField sWifiHalHandle 0x989908dc
E/WifiHAL ( 1028): Could not connect handle
D/wifi    ( 1028): halHandle = 0x0, mVM = 0xb487c280, mCls = 0x60205a
I/WifiNative-HAL( 1028): Could not start hal
D/WifiStateMachine( 1028): Setting OUI to DA-A1-19
I/WifiNative-HAL( 1028): startHal
E/wifi    ( 1028): getStaticLongField sWifiHalHandle 0x9899085c
E/WifiHAL ( 1028): Could not connect handle
D/wifi    ( 1028): halHandle = 0x0, mVM = 0xb487c280, mCls = 0x601fe2
I/WifiNative-HAL( 1028): Could not start hal
D/WifiNative-wlan0( 1028): doBoolean: STA_AUTOCONNECT 1
D/WifiNative-wlan0( 1028): STA_AUTOCONNECT 1: returned true
D/WfdsMonitor( 1944): WfdsMonitorThread create
D/WifiNative-wlan0( 1028): doBoolean: DRIVER BTCOEXSCAN-STOP
I/wpa_supplicant( 6292): wpa_driver_nl80211_ext_driver_cmd BTCOEXSCAN-STOP
D/WfdsMonitor( 1944): WFDS Monitor is created and started
D/WfdsService( 1944): WiFi: Supplicant connection re-established
D/WifiNative-wlan0( 1028): DRIVER BTCOEXSCAN-STOP: returned true
D/WifiHS20( 1028): hidePasspointNotification off =false
D/WifiNative-wlan0( 1028): doBoolean: DRIVER RXFILTER-STOP
I/wpa_supplicant( 6292): wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
,W/Settings( 1028): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1028): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiNative-wlan0( 1028): DRIVER RXFILTER-STOP: returned true
D/WifiOffDelayIfNotUsed( 1028): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
D/WifiNative-wlan0( 1028): doBoolean: DRIVER RXFILTER-REMOVE 3
I/wpa_supplicant( 6292): wpa_driver_nl80211_ext_driver_cmd RXFILTER-REMOVE 3
D/WifiNative-wlan0( 1028): DRIVER RXFILTER-REMOVE 3: returned true
D/WifiNative-wlan0( 1028): doBoolean: DRIVER RXFILTER-START
I/wpa_supplicant( 6292): wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
D/WifiNative-wlan0( 1028): DRIVER RXFILTER-START: returned true
D/WifiNative-wlan0( 1028): doBoolean: DRIVER RXFILTER-STOP
,I/wpa_supplicant( 6292): wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
D/WifiNative-wlan0( 1028): DRIVER RXFILTER-STOP: returned true
D/WifiNative-wlan0( 1028): doBoolean: DRIVER RXFILTER-REMOVE 2
I/wpa_supplicant( 6292): android_multicast_filter_startstop : multicast filter set
D/WifiNative-wlan0( 1028): DRIVER RXFILTER-REMOVE 2: returned true
D/WifiNative-wlan0( 1028): doBoolean: DRIVER RXFILTER-START
I/wpa_supplicant( 6292): wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
D/WifiNative-wlan0( 1028): DRIVER RXFILTER-START: returned true
E/WifiNative: ( 1028): [253,456,908 us] RECONNECT  stack:logDbg - reconnect - enter - invokeEnterMethods - performTransitions
D/WifiNative-wlan0( 1028): doBoolean: RECONNECT
I/StatusBar.NetworkController( 1446): networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1446): mWifiConnected = false, mWifiLevel = 0
D/WifiNative-wlan0( 1028): RECONNECT: returned true
E/CtrlSupplicant( 1944): Access OK "@android:wpa_wlan0"
D/WifiNative-wlan0( 1028): doString: [STATUS]
D/WifiNative-wlan0( 1028):    returned wpa_state=SCANNING p2p_device_address=02:9a:02:7b:60:ac address=c4:9a:02:7b:60:ac uuid=530d3fd0-1ba3-5409-a336-ff4e42af59a2
D/WifiNative-wlan0( 1028): doBoolean: DRIVER SETSUSPENDMODE 1
I/wpa_supplicant( 6292): wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 1
D/WifiMonitor( 1028): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
D/WifiNative-wlan0( 1028): DRIVER SETSUSPENDMODE 1: returned true
E/WifiMonitor( 1028): WifiMonitor:wlan0 cnt=1 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
D/WifiNative-wlan0( 1028): doBoolean: SET ps 1
D/WifiNative-wlan0( 1028): SET ps 1: returned true
D/LGWifiP2pService( 1028): P2pDisabledState{ when=0 what=131203 target=com.android.internal.util.StateMachine$SmHandler }
D/CommandListener(  319): Setting iface cfg
D/CommandListener(  319): Trying to bring up p2p0
D/WifiMonitor( 1028): startMonitoring(p2p0) with mConnected = true
D/LGWifiP2pService( 1028): P2pEnablingState
D/LGWifiP2pService( 1028): P2pEnablingState{ when=-1ms what=147457 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1028): P2p socket connection successful
D/LGWifiP2pService( 1028): P2pEnabledState
D/WifiScanningService( 1028): SCAN_AVAILABLE : 3
D/RttService( 1028): SCAN_AVAILABLE : 3
D/WifiScanningService( 1028): DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
I/WifiNative-HAL( 1028): startHal
E/wifi    ( 1028): getStaticLongField sWifiHalHandle 0x97b6e99c
E/WifiHAL ( 1028): Could not connect handle
D/wifi    ( 1028): halHandle = 0x0, mVM = 0xb487c280, mCls = 0x701ba2
I/WifiNative-HAL( 1028): Could not start hal
E/WifiScanningService( 1028): could not start HAL
D/LGWifiP2pService( 1028): sending p2p connection changed broadcast
D/WifiNative-p2p0( 1028): doBoolean: SET persistent_reconnect 1
D/RttService( 1028): DefaultState got{ when=-2ms what=160512 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-p2p0( 1028): SET persistent_reconnect 1: returned true
D/WifiNative-p2p0( 1028): doBoolean: SET device_name G3-1
,E/CtrlSupplicant( 1944): Succeed to open control connection
E/CtrlSupplicant( 1944): Succeed to open monitor connection
E/WifiStateMachine( 1028):  DisconnectedState CMD_SET_OPERATIONAL_MODE 1 0
D/WifiNative-p2p0( 1028): SET device_name G3-1: returned true
E/WifiStateMachine( 1028):  DisconnectedState CMD_START_DRIVER 0 0
D/LGWifiP2pService( 1028): [LGE_P2P] initializeP2pSettings() check postfix
D/WfdsMonitor( 1944): Supplicant connection established
D/LGWifiP2pService( 1028): before postfix = G3-1
D/WfdsService( 1944): Connected to the supplicant for wfds
D/WifiServerServiceExt( 1028): postfix byte check : 4
D/LGWifiP2pService( 1028): after postfix = G3-1
D/WifiNative-p2p0( 1028): doBoolean: SET p2p_ssid_postfix -G3-1
D/WifiNative-p2p0( 1028): SET p2p_ssid_postfix -G3-1: returned true
D/WifiNative-p2p0( 1028): doBoolean: SET device_type 10-0050F204-5
D/WifiNative-p2p0( 1028): SET device_type 10-0050F204-5: returned true
D/WifiNative-p2p0( 1028): doBoolean: SET config_methods virtual_push_button physical_display keypad
D/WifiNative-p2p0( 1028): SET config_methods virtual_push_button physical_display keypad: returned true
D/WifiNative-p2p0( 1028): doBoolean: P2P_SET conc_pref p2p
D/WifiNative-p2p0( 1028): P2P_SET conc_pref p2p: returned true
D/WifiNative-HAL( 1028): p2pGetDeviceAddress
D/WifiNative-HAL( 1028): p2pGetDeviceAddress returning 02:9a:02:7b:60:ac
E/WifiStateMachine( 1028):  ConnectModeState CMD_START_DRIVER 0 0
E/WifiStateMachine( 1028):  DriverStartedState CMD_START_DRIVER 0 0
E/WifiStateMachine( 1028):  DisconnectedState what:132106 1 0
E/WifiStateMachine( 1028):  ConnectModeState what:132106 1 0
E/WifiStateMachine( 1028):  DriverStartedState what:132106 1 0
I/WifiServerServiceExt( 1028): setWifiDualbandAPConnection band : 1
E/wpa_supplicant( 6292): nWIFIDualbandAPConnection: 1
E/WifiStateMachine( 1028):  DisconnectedState what:132096 -100 0
E/WifiStateMachine( 1028):  ConnectModeState what:132096 -100 0
E/WifiStateMachine( 1028):  DriverStartedState what:132096 -100 0
I/WifiServerServiceExt( 1028): set CMD_DISCONNECT_RSSI_LVL : -100
E/wpa_supplicant( 6292): disconnect_rssi_lvl: -100
E/WifiStateMachine( 1028):  DisconnectedState CMD_SET_COUNTRY_CODE 1 0 cz
E/WifiStateMachine( 1028):  ConnectModeState CMD_SET_COUNTRY_CODE 1 0 cz
E/WifiStateMachine( 1028):  DriverStartedState CMD_SET_COUNTRY_CODE 1 0 cz
D/WifiNative-wlan0( 1028): doBoolean: DRIVER COUNTRY CZ
I/wpa_supplicant( 6292): wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
I/wpa_supplicant( 6292): wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
D/WifiMonitor( 1028): Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
E/WifiMonitor( 1028): WifiMonitor:wlan0 cnt=2 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
E/WifiMonitor( 1028): handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
E/WifiMonitor( 1028): handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
I/wpa_supplicant( 6292): [LGE_PATCH] driver_cmd() country:CZ
I/wpa_supplicant( 6292): p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
D/WifiMonitor( 1028): Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
E/WifiMonitor( 1028): WifiMonitor:p2p0 cnt=3 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
E/WifiMonitor( 1028): handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
E/WifiMonitor( 1028): handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
D/WifiNative-wlan0( 1028): DRIVER COUNTRY CZ: returned true
D/WfdsMonitor( 1944): Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
I/wpa_supplicant( 6292): p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
D/WfdsMonitor( 1944): Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
,D/WifiMonitor( 1028): Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
E/WifiMonitor( 1028): WifiMonitor:p2p0 cnt=4 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
E/WifiMonitor( 1028): handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
E/WifiMonitor( 1028): handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
E/WifiStateMachine( 1028):  DisconnectedState CMD_SET_FREQUENCY_BAND 0 0
E/WifiStateMachine( 1028):  ConnectModeState CMD_SET_FREQUENCY_BAND 0 0
E/WifiStateMachine( 1028):  DriverStartedState CMD_SET_FREQUENCY_BAND 0 0
D/WifiNative-wlan0( 1028): doBoolean: DRIVER SETBAND 0
I/wpa_supplicant( 6292): wpa_driver_nl80211_ext_driver_cmd SETBAND 0 - interface name wlan0
I/wpa_supplicant( 6292): wlan0: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
D/WifiMonitor( 1028): Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN]
E/WifiMonitor( 1028): WifiMonitor:wlan0 cnt=5 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
E/WifiMonitor( 1028): handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
E/WifiMonitor( 1028): handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
D/WifiNative-wlan0( 1028): DRIVER SETBAND 0: returned true
D/WifiNative-wlan0( 1028): doBoolean: BSS_FLUSH 0
D/WifiNative-wlan0( 1028): BSS_FLUSH 0: returned true
D/WifiNative-wlan0( 1028): doBoolean: SCAN
D/WifiNative-wlan0( 1028): SCAN: returned false
V/WfdStateTracker( 1944): WfdStateTracker handleDirectStateChangedEvent: 2
D/WfdsService( 1944): WifiP2pState is changed : true
D/WfdsService( 1944): Receive the WFDS_ENABLE Method
D/WfdsService( 1944): Set the WFDS Monitor: true
D/WfdsService( 1944): Connected to the supplicant for wfds
D/WfdsJNI ( 1944): doCommand: WFDS_SET TRUE
I/wpa_supplicant( 6292): WFDS: wfds_supplicant_wfds_cmd: cmd = SET TRUE
D/WfdsJNI ( 1944): doCommand: WFDS_GET_MAC_ADDRESS
I/wpa_supplicant( 6292): WFDS: wfds_supplicant_wfds_cmd: cmd = GET_MAC_ADDRESS
D/WfdsJNI ( 1944): doCommand: IFNAME=wlan0 GET_CAPABILITY channels
D/WfdsService( 1944): selectPreferredScanChannel [36]
D/WfdsService( 1944): STATE : WfdsEnabledState - enter: this device mac 02:9a:02:7b:60:ac
E/WifiStateMachine( 1028):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 1 0 rt=253482  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
D/WfdsService( 1944): WIFI_P2P_CONNECTION_CHANGED_ACTION
D/LGWifiP2pService( 1028): DeviceAddress: 02:9a:02:7b:60:ac
D/WifiNative-p2p0( 1028): doBoolean: P2P_FLUSH
D/WifiNative-p2p0( 1028): P2P_FLUSH: returned true
D/WifiNative-p2p0( 1028): doBoolean: P2P_SERVICE_FLUSH
D/WifiNative-p2p0( 1028): P2P_SERVICE_FLUSH: returned true
D/WifiNative-p2p0( 1028): doString: [LIST_NETWORKS]
D/WfdsService( 1944): isConnected: false
D/WifiNative-p2p0( 1028):    returned network id / ssid / bssid / flags
D/WifiNative-p2p0( 1028): doBoolean: SAVE_CONFIG
D/StatusBar.NetworkController( 1446): refreshViews: Data not connected!! Set no data type icon / Roaming
W/ActivityManager( 1028): getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
E/WifiStateMachine( 1028):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 1 0 rt=253489  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
E/WifiStateMachine( 1028):  DisconnectedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
I/WfdStateTracker( 1944): handleP2pThisDeviceChanged
E/WifiStateMachine( 1028):  ConnectModeState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
E/WifiStateMachine( 1028):  DriverStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
E/WifiStateMachine( 1028):  SupplicantStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
I/StatusBar.NetworkController( 1446): networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1446): mWifiConnected = false, mWifiLevel = 0
D/WifiNative-p2p0( 1028): SAVE_CONFIG: returned true
D/LGWifiP2pService( 1028): sending p2p persistent groups changed broadcast
D/LGWifiP2pService( 1028): InactiveState
D/LGWifiP2pService( 1028): InactiveState{ when=-18ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1028): P2pEnabledState{ when=-18ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-p2p0( 1028): doBoolean: DRIVER COUNTRY CZ
E/WifiStateMachine( 1028):  DefaultState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
I/wpa_supplicant( 6292): wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
I/wpa_supplicant( 6292): p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
W/Settings( 1028): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1028): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1028): NETWORK_STATE_CHANGED_ACTION [SCANNING]
I/wpa_supplicant( 6292): [LGE_PATCH] driver_cmd() country:CZ
D/StatusBar.NetworkController( 1446): refreshViews: Data not connected!! Set no data type icon / Roaming
I/wpa_supplicant( 6292): p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
D/WfdsService( 1944): WIFI_P2P_THIS_DEVICE_CHANGED_ATCION
D/WfdsService( 1944): Update P2p Interface State: 3
D/WifiMonitor( 1028): Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
E/WifiMonitor( 1028): WifiMonitor:p2p0 cnt=6 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
E/WifiMonitor( 1028): handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
E/WifiMonitor( 1028): handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
D/WifiMonitor( 1028): Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
I/wpa_supplicant( 6292): p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
E/WifiMonitor( 1028): WifiMonitor:p2p0 cnt=7 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
E/WifiMonitor( 1028): handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
E/WifiMonitor( 1028): handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
D/WifiMonitor( 1028): Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
E/WifiMonitor( 1028): WifiMonitor:p2p0 cnt=8 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
E/WifiMonitor( 1028): handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
E/WifiMonitor( 1028): handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
D/WfdsMonitor( 1944): Event [CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
D/WfdsMonitor( 1944): Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
D/WfdsMonitor( 1944): Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
D/WifiNative-p2p0( 1028): DRIVER COUNTRY CZ: returned true
D/LGWifiP2pService( 1028): InactiveState{ when=-12ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1028): P2pEnabledState{ when=-12ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1028): InactiveState{ when=-1ms what=139287 arg2=1 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1028): P2pEnabledState{ when=-1ms what=139287 arg2=1 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1028): DefaultState{ when=-1ms what=139287 arg2=1 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1028): InactiveState{ when=0 what=139285 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1028): P2pEnabledState{ when=0 what=139285 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1028): DefaultState{ when=0 what=139285 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1028): InactiveState{ when=0 what=139287 arg2=1 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1028): P2pEnabledState{ when=0 what=139287 arg2=1 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1028): DefaultState{ when=-1ms what=139287 arg2=1 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1028): InactiveState{ when=-1ms what=139283 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1028): P2pEnabledState{ when=-1ms what=139283 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1028): DefaultState{ when=-1ms what=139283 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiServerServiceExt( 1028): No p2p device connected
,D/WifiServerServiceExt( 1028): SUPPLICANT_STATE_CHANGED_ACTION
W/WfdsService( 1944): DefaultState - msg [9441285] is not handled
D/WifiServerServiceExt( 1028): setSupplicantStateSCANNING
D/LGBluetoothAvrcpQcomAdapter( 6231): [BTUI] installed app name: Music
D/LGBluetoothAvrcpQcomAdapter( 6231): [BTUI] installed app name: Google Play Music
D/LGBluetoothAvrcpQcomAdapter( 6231): [BTUI] === MediaPlayerInfo (playerId:0) ===
D/LGBluetoothAvrcpQcomAdapter( 6231): [BTUI]          displayName: Music
D/LGBluetoothAvrcpQcomAdapter( 6231): [BTUI]          packageName: com.lge.music
D/LGBluetoothAvrcpQcomAdapter( 6231): [BTUI]          playState: 2 (PAUSED)
D/LGBluetoothAvrcpQcomAdapter( 6231): [BTUI] === MediaPlayerInfo (playerId:1) ===
D/LGBluetoothAvrcpQcomAdapter( 6231): [BTUI]          displayName: Google Play Music
D/LGBluetoothAvrcpQcomAdapter( 6231): [BTUI]          packageName: com.google.android.music
D/LGBluetoothAvrcpQcomAdapter( 6231): [BTUI]          playState: 2 (PAUSED)
D/LGBluetoothAvrcpQcomAdapter( 6231): [BTUI] [-] updateMediaPlayerInfo
I/BluetoothA2dpServiceJni( 6231): classInitNative
I/BluetoothA2dpServiceJni( 6231): classInitNative: succeeds
D/A2dpStateMachine( 6231): make
I/bluedroid-qcom( 6231): get_profile_interface a2dp
I/GKI_LINUX( 6231): gki_task_entry task_id=2 [A2DP-MEDIA] starting
I/LGBluetoothA2dpServiceJni( 6231): classInitNative: succeeds
I/LGBluetoothA2dpAdapter( 6231): [BTUI] getInstance : create [LGBluetoothA2dpAdapter]
D/BluetoothAdapterService( 6231): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@20043093
I/BluetoothHidServiceJni( 6231): classInitNative: succeeds
D/WifiService( 1028): New client listening to asynchronous messages
D/HidService( 6231): Received start request. Starting profile...
I/bluedroid-qcom( 6231): get_profile_interface hidhost
D/BluetoothAdapterService( 6231): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@20043093
I/BluetoothHealthServiceJni( 6231): classInitNative: succeeds
D/HealthService( 6231): Received start request. Starting profile...
D/A2dpStateMachine( 6231): Enter Disconnected: -2
I/bluedroid-qcom( 6231): get_profile_interface health
I/LGBluetoothHealthServiceJni( 6231): classInitNative: succeeds
D/BluetoothAdapterService( 6231): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@20043093
I/BluetoothPanServiceJni( 6231): classInitNative(L105): succeeds
D/PanService( 6231): Received start request. Starting profile...
D/BluetoothPanServiceJni( 6231): initializeNative(L110): pan
I/bluedroid-qcom( 6231): get_profile_interface pan
I/LGBluetoothPanAdapter( 6231): [BTUI] getInstance : create [LGBluetoothPanAdapter]
D/BluetoothAdapterService( 6231): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@20043093
I/BtGatt.JNI( 6231): classInitNative(L901): classInitNative: Success!
D/BtGatt.DebugUtils( 6231): handleDebugAction() action=null
D/BtGatt.GattService( 6231): Received start request. Starting profile...
D/BtGatt.GattService( 6231): start()
I/bluedroid-qcom( 6231): get_profile_interface gatt
D/BtGatt.AdvertiseManager( 6231): advertise manager created
D/BluetoothAdapterService( 6231): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@20043093
D/BluetoothAdapterService( 6231): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@20043093
I/LGBluetoothMapAdapter( 6231): [BTUI] getInstance : create [LGBluetoothMapAdapter]
V/BluetoothMapService( 6231): BluetoothMapBinder()
D/BluetoothMapService( 6231): Received start request. Starting profile...
D/BluetoothMapService( 6231): start()
,I/ActivityManager( 1028): Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=6332 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
D/BluetoothMapEmailSettingsLoader( 6231): Found 0 applications
D/BluetoothMapEmailAppObserver( 6231): createReceiver()
D/BluetoothMapEmailAppObserver( 6231): initObservers()
D/BluetoothMapEmailAppObserver( 6231): getEnabledAccountItems()
D/BluetoothAdapterService( 6231): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@20043093
D/HeadsetStateMachine( 6231): Proxy object connected
D/LGBluetoothHfpAdapter( 6231): [BTUI] queryPhoneState
,D/LGBluetoothHfpAdapter( 6231): Try to query the phonestate on bind
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
D/BluetoothAdapterService( 6231): Profile still not running:com.android.bluetooth.gatt.GattService
V/BluetoothPbapReceiver( 6231): PbapReceiver onReceive 
D/HeadsetStateMachine( 6231): Disconnected process message: 10, size: 0
V/BluetoothPbapReceiver( 6231): ***********action = android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothPbapReceiver( 6231): ***********state = 11
,W/FormManager( 6300): Network not available. Please check & try again.
D/HeadsetPhoneState( 6231): sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
D/HeadsetStateMachine( 6231): Disconnected process message: 11, size: 0
D/BluetoothAdapterService( 6231): Profile still not running:com.android.bluetooth.gatt.GattService
D/BluetoothAdapterService( 6231): Profile still not running:com.android.bluetooth.gatt.GattService
D/BluetoothAdapterService( 6231): Profile still not running:com.android.bluetooth.gatt.GattService
V/PanService( 6231): [BTUI] SIM Extra State :ABSENT
,D/BluetoothAdapterService( 6231): Profile still not running:com.android.bluetooth.gatt.GattService
D/BluetoothAdapterService( 6231): Profile still not running:com.android.bluetooth.map.BluetoothMapService
V/BluetoothMapService( 6231): Handler(): got msg=1
,D/BluetoothAdapterState( 6231): CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
I/bluedroid-qcom( 6231): enable
I/bt_hci_bdroid( 6231): init
I/GKI_LINUX( 6231): gki_task_entry task_id=0 [BTU] starting
I/bt-btu  ( 6231): btu_task pending for preload complete event
I/bt_vendor( 6231): bt-vendor : init
I/bt_vendor( 6231): bt-vendor : get_bt_soc_type
E/bt_vendor( 6231): get_bt_soc_type: Failed to get soc type
I/bt_vendor( 6231): init: Local BD Address : c0:64:73:54:3f:58
D/bt_userial_mct( 6231): userial_init
,D/bt_hci_bdroid( 6231): set_power 1
I/bt_vendor( 6231): bt-vendor : BT_VND_OP_POWER_CTRL: On
I/bt_vendor( 6231): Starting hciattach daemon
I/bt_vendor( 6231): try to set true
W/sh      ( 6357): type=1400 audit(0.0:155): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
I/ActivityManager( 1028): Start proc com.lge.lifetracker for broadcast com.lge.lifetracker/.receiver.HealthDeviceReceiver: pid=6352 uid=10037 gids={50037, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
W/sh      ( 6357): type=1400 audit(0.0:156): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
I/qcom-bluetooth( 6367): /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  
,V/FormManager( 6300): Network unavailable.
V/FormManager( 6300): Network unavailable.
,I/ActivityManager( 1028): Killing 5500:com.android.contacts/u0a19 (adj 15): empty #17
D/PCSuite ( 6332): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,I/qcom-bluetooth( 6377): /system/etc/init.qcom.bt.sh: Transport : smd 
I/qcom-bluetooth( 6380): /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
I/qcom-bluetooth( 6382): /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,I/qcom-bluetooth( 6385): /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> 
I/qcom-bluetooth( 6386): /system/etc/init.qcom.bt.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,I/qcom-bluetooth( 6387): /system/etc/init.qcom.bt.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> 
,I/libmdmdetect( 6389): ESOC framework not supported
,E/Diag_Lib( 6389):  Diag_LSM_Init: Failed to open handle to diag driver, error = 13
D/bthci_qcomm_linux( 6389): [BTUI] bt_hci_qcomm_pfal_get_bdaddress: Get BDADDR from bluedroid prop (58:3F:54:73:64:C0)
D/bthci_qcomm_common( 6389): [BTUI] bt_hci_qcomm_init:
,D/bthci_qcomm_common( 6389): [BTUI]     BDADDR: 58:3F:54:73:64:C0
,D/bthci_qcomm_common( 6389): [BTUI]     BR/EDR: Class 1
D/bthci_qcomm_common( 6389): [BTUI]     LE: Class 2
D/bthci_qcomm_common( 6389): [BTUI]     Ref Clock: 32M
D/btqsocnvmtags( 6389): [BTUI] init_riva_entries: set NORMAL power settings
W/libprocessgroup( 1028): failed to open /acct/uid_10019/pid_5500/cgroup.procs: No such file or directory
,E/ActivityThread( 6352): Failed to find provider info for com.lge.lgaccount.provider
W/LG Account v2.2( 6352): No ProfileInfo entries
I/LG Account v2.2( 6352): isEnabled: false
I/Feature ( 6352): [Lifetracker]ver: 4.21.112(40211120)
,I/Feature ( 6352): [Lifetracker]Country: EU
I/Feature ( 6352): [Lifetracker]Operator: OPEN
I/Feature ( 6352): [Lifetracker]Ranking support: false
I/Feature ( 6352): [Lifetracker]Comfort support: false
I/Feature ( 6352): [Lifetracker]Accessory: true
,I/Feature ( 6352): [Lifetracker]Health device: true
I/Feature ( 6352): [Lifetracker]Extra Pedometer: false
I/Feature ( 6352): [Lifetracker]Blood glucose device: false
I/Feature ( 6352): [Lifetracker]Device Number: 3
,I/ActivityManager( 1028): Killing 5838:com.lge.email/u0a23 (adj 15): empty #17
V/WiFiOffLoadBroadcast( 6269): WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
D/WifiService( 1028): New client listening to asynchronous messages
,E/WifiMonitor( 1028): WifiMonitor:wlan0 cnt=9 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
E/WifiMonitor( 1028): handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
D/WifiMonitor( 1028): Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
E/WifiMonitor( 1028): WifiMonitor:wlan0 cnt=10 dispatchEvent: WPS-AP-AVAILABLE 
E/wpa_supplicant( 6292): USIM:  scard_init function
W/WifiMonitor( 1028): couldn't identify event type - WPS-AP-AVAILABLE 
,I/wpa_supplicant( 6292): Trying to associate with SSID 'NG700'
E/WifiStateMachine( 1028):  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=0 bcn=0
E/WifiStateMachine( 1028):  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=0 bcn=0
E/WifiStateMachine( 1028):  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=0 bcn=0
E/WifiStateMachine( 1028):  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=0 bcn=0
I/WifiNative-HAL( 1028): startHal
E/wifi    ( 1028): getStaticLongField sWifiHalHandle 0x989908cc
E/WifiHAL ( 1028): Could not connect handle
D/wifi    ( 1028): halHandle = 0x0, mVM = 0xb487c280, mCls = 0x4020f6
I/WifiNative-HAL( 1028): Could not start hal
D/WifiNative-wlan0( 1028): doString: [BSS RANGE=0- MASK=0x21987]
D/WifiMonitor( 1028): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
E/WifiMonitor( 1028): WifiMonitor:wlan0 cnt=11 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
I/rmt_storage(  316): rmt_storage_connect_cb: clnt_h=0x5 conn_h=0xb6403090
I/rmt_storage(  316): rmt_storage_rw_iovec_cb: /boot/modem_fs1: clnt_h=0x1: req_h=0x9 msg_id=3: R/W request received
I/rmt_storage(  316): wakelock acquired: 1, error no: 42
I/rmt_storage(  316): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 Unblock worker thread (th_id: -1236807552)
D/LgDataFeature( 6269): LgDataFeature() Constructor: none
D/LgDataFeature( 6269): LgDataFeature() Constructor Done, null
,D/WiFiOffLoadUpdatePriority( 6269): remove : truetruetrue
W/libprocessgroup( 1028): failed to open /acct/uid_10023/pid_5838/cgroup.procs: No such file or directory
,E/WifiStateMachine( 1028):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 11 0 rt=253909  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
E/WifiStateMachine( 1028):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 11 0 rt=253910  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
E/WifiStateMachine( 1028):  DisconnectedState CMD_GET_CONFIGURED_NETWORKS uid=1000 1000 0 num=1
E/WifiStateMachine( 1028):  ConnectModeState CMD_GET_CONFIGURED_NETWORKS uid=1000 1000 0 num=1
E/WifiStateMachine( 1028):  DisconnectedState CMD_SAVE_CONFIG uid=1000 0 0
E/WifiStateMachine( 1028):  ConnectModeState CMD_SAVE_CONFIG uid=1000 0 0
D/WifiNative-wlan0( 1028): doBoolean: SAVE_CONFIG
I/rmt_storage(  316): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0x9 msg_id=3: Bytes written = 1572864
I/rmt_storage(  316): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0x9 msg_id=3: Send response: res=0 err=0
,I/rmt_storage(  316): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 About to block rmt_storage client thread (th_id: -1236807552) wakelock released: 1, error no: 22
I/rmt_storage(  316): 
E/Diag_Lib(  900): [IMS_FATAL]| 3347 | 913 |ims-rtp-daemon ims_rtp_qmi_handler_thread_func waiting on select thread>
I/rmt_storage(  316): rmt_storage_disconnect_cb: clnt_h=0x0x5 conn_h=0x0xb6403090
D/WifiNative-wlan0( 1028): SAVE_CONFIG: returned true
D/WiFiOffLoadUpdatePriority( 6269): remove1
V/WiFiOffLoadSharedPrefsUtils( 6269): save remove
I/StatusBar.NetworkController( 1446): networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1446): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1446): refreshViews: Data not connected!! Set no data type icon / Roaming
,W/Settings( 1028): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1028): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1028): NETWORK_STATE_CHANGED_ACTION [SCANNING]
I/StatusBar.NetworkController( 1446): networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1446): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1446): refreshViews: Data not connected!! Set no data type icon / Roaming
W/Settings( 1028): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1028): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1028): NETWORK_STATE_CHANGED_ACTION [CONNECTING]
D/WifiServerServiceExt( 1028): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1028): setSupplicantStateASSOCIATING
D/WiFiOffLoadBroadcast( 6269): mLastConnectedNetwork from SharedPrefsUtils for wifioffloading : null
D/WiFiOffLoadBroadcast( 6269): S: false, R: false
,E/WifiStateMachine( 1028):  DisconnectedState CMD_GET_CONFIGURED_NETWORKS uid=1000 1000 0 num=1
E/WifiStateMachine( 1028):  ConnectModeState CMD_GET_CONFIGURED_NETWORKS uid=1000 1000 0 num=1
D/WiFiOffLoadUpdatePriority( 6269): saved SSID: "NG700"
D/WiFiOffLoadUpdatePriority( 6269): connected SSID: null
D/WiFiOffLoadUpdatePriority( 6269): private wpa: "NG700" 300
D/WifiServiceImplEx( 1028): addOrUpdateNetwork pid=6269, uid=1000, packageName=android.uid.system:1000
E/addOrUpdateNetwork( 1028):  uid = 1000 SSID "NG700" nid=0
E/WifiStateMachine( 1028):  DisconnectedState CMD_ADD_OR_UPDATE_NETWORK uid=1000 0 0 "NG700"WPA_PSK prio=300 status=2
E/WifiStateMachine( 1028):  ConnectModeState CMD_ADD_OR_UPDATE_NETWORK uid=1000 0 0 "NG700"WPA_PSK prio=300 status=2
E/WifiConfigStore( 1028):  key="NG700"WPA_PSK netId=0 uid=0/1000
D/WifiServerServiceExt( 1028): addOrUpdateNetwork: mThisIsFirstEnableing = false
D/WifiNative-wlan0( 1028): doBoolean: SET_NETWORK 0 ssid 4e47373030
D/WifiNative-wlan0( 1028): SET_NETWORK 0 ssid 4e47373030: returned true
D/WifiNative-wlan0( 1028): doBoolean: SET_NETWORK 0 key_mgmt WPA-PSK
D/WifiNative-wlan0( 1028): SET_NETWORK 0 key_mgmt WPA-PSK: returned true
D/WifiNative-wlan0( 1028): doBoolean: SET_NETWORK 0 proto WPA RSN
D/WifiNative-wlan0( 1028): SET_NETWORK 0 proto WPA RSN: returned true
D/WifiNative-wlan0( 1028): doBoolean: SET_NETWORK 0 pairwise TKIP CCMP
D/WifiNative-wlan0( 1028): SET_NETWORK 0 pairwise TKIP CCMP: returned true
D/WifiNative-wlan0( 1028): doBoolean: SET_NETWORK 0 group WEP40 WEP104 TKIP CCMP
D/WifiNative-wlan0( 1028): SET_NETWORK 0 group WEP40 WEP104 TKIP CCMP: returned true
D/WifiNative-wlan0( 1028): doBoolean: SET_NETWORK 0 priority 300
,D/WifiNative-wlan0( 1028): SET_NETWORK 0 priority 300: returned true
E/WifiConfigStore( 1028): will read network variables netId=0
E/WifiConfigStore( 1028): writeIpAndProxyConfigurationsOnChange: "NG700" -> "NG700" path: /data/misc/wifi/ipconfig.txt
E/WifiConfigStore( 1028):  writeKnownNetworkHistory() num networks:1 needWrite=false
D/WiFiOffLoadUpdatePriority( 6269):  ssid "NG700" prio 300
D/WiFiOffLoadUpdatePriority( 6269): configuration updated: 0
E/WifiStateMachine( 1028):  DisconnectedState CMD_SAVE_CONFIG uid=1000 0 0
E/WifiStateMachine( 1028):  ConnectModeState CMD_SAVE_CONFIG uid=1000 0 0
D/WifiNative-wlan0( 1028): doBoolean: SAVE_CONFIG
,D/WifiNative-wlan0( 1028): SAVE_CONFIG: returned true
D/WiFiOffLoadUpdatePriority( 6269): configuration saved: true
D/BluetoothPermissionRequest( 6269): onReceive
,D/LGBluetoothFeatureConfig( 6269):  get() - isFeatureLoaded : false
D/BluetoothManagerService( 1028): Message: 20
D/BluetoothManagerService( 1028): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@3ba5740:true
I/ActivityManager( 1028): Killing 5523:com.android.gallery3d/u0a27 (adj 15): empty #17
,D/LGBluetoothResetSettingReceiver( 6269): return without doing reset settings.
D/LGBluetoothOppAdapter( 6231): [BTUI] getInstance : create [LGBluetoothOppAdapter]
,W/libprocessgroup( 1028): failed to open /acct/uid_10027/pid_5523/cgroup.procs: No such file or directory
V/BluetoothFtpReceiver( 6231): BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
,V/BluetoothSapReceiver( 6231): [BTUI] checkServiceStart
V/BluetoothSapReceiver( 6231): [BTUI] region:EU country:EU
V/BluetoothSapReceiver( 6231): SapReceiver onReceive 
V/BluetoothSapReceiver( 6231): action = android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothSapReceiver( 6231):  Bluetooth Adapter state = 11
I/wpa_supplicant( 6292): wlan0: Associated with c0:ff:d4:d3:aa:48
D/WifiMonitor( 1028): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
E/WifiMonitor( 1028): WifiMonitor:wlan0 cnt=12 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
D/WifiMonitor( 1028): Event [IFNAME=wlan0 Associated with c0:ff:d4:d3:aa:48]
E/WifiMonitor( 1028): WifiMonitor:wlan0 cnt=13 dispatchEvent: Associated with c0:ff:d4:d3:aa:48
D/WifiMonitor( 1028): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1028): WifiMonitor:wlan0 cnt=14 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
E/WifiStateMachine( 1028):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 12 0 rt=254265  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
E/WifiStateMachine( 1028):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 12 0 rt=254265  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
E/WifiStateMachine( 1028):  DisconnectedState CMD_ASSOCIATED_BSSID 13 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=254266
E/WifiStateMachine( 1028):  ConnectModeState CMD_ASSOCIATED_BSSID 13 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=254267
,I/wpa_supplicant( 6292): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
E/WifiStateMachine( 1028):  DriverStartedState CMD_ASSOCIATED_BSSID 13 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=254268
I/wpa_supplicant( 6292): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
D/WifiMonitor( 1028): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1028): WifiMonitor:wlan0 cnt=15 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/WifiMonitor( 1028): Event [IFNAME=wlan0 WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]]
E/WifiMonitor( 1028): WifiMonitor:wlan0 cnt=16 dispatchEvent: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
W/WifiMonitor( 1028): couldn't identify event type - WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
D/WifiMonitor( 1028): Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]]
E/WifiMonitor( 1028): WifiMonitor:wlan0 cnt=17 dispatchEvent: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
E/WifiMonitor( 1028): handleEvent 1  Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
D/WifiMonitor( 1028): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1028): WifiMonitor:wlan0 cnt=18 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
E/WifiStateMachine( 1028):  SupplicantStartedState CMD_ASSOCIATED_BSSID 13 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=254270
E/WifiStateMachine( 1028):  DefaultState CMD_ASSOCIATED_BSSID 13 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=254270
E/WifiStateMachine( 1028):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 14 0 rt=254271  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: FOUR_WAY_HANDSHAKE
I/ActivityManager( 1028): Start proc com.lge.settings.easy for broadcast com.lge.settings.easy/com.lge.settings.bluetooth.LGBluetoothProfileConnectionReceiver: pid=6399 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
D/Tethering( 1028): sendTetherStateChangedBroadcast 1, 0, 0
,E/WifiStateMachine( 1028):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 14 0 rt=254301  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: FOUR_WAY_HANDSHAKE
E/WifiStateMachine( 1028):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 15 0 rt=254302  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: GROUP_HANDSHAKE
E/WifiStateMachine( 1028):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 15 0 rt=254303  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: GROUP_HANDSHAKE
E/WifiStateMachine( 1028):  DisconnectedState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=254303
E/WifiStateMachine( 1028):  ConnectModeState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=254304
I/StatusBar.NetworkController( 1446): networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1446): mWifiConnected = false, mWifiLevel = 0
W/Settings( 1028): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1028): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1028): NETWORK_STATE_CHANGED_ACTION [CONNECTING]
D/StatusBar.NetworkController( 1446): refreshViews: Data not connected!! Set no data type icon / Roaming
I/StatusBar.NetworkController( 1446): networkInfo=[type: WIFI[], state: CONNECTING/AUTHENTICATING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1446): mWifiConnected = false, mWifiLevel = 0
W/Settings( 1028): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1028): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1028): NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
D/WifiServerServiceExt( 1028): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1028): setSupplicantStateASSOCIATED
D/StatusBar.NetworkController( 1446): refreshViews: Data not connected!! Set no data type icon / Roaming
,D/WifiNative-wlan0( 1028): doString: [STATUS]
D/WifiMonitor( 1028): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1028): WifiMonitor:wlan0 cnt=19 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/WifiNative-wlan0( 1028):    returned bssid=c0:ff:d4:d3:aa:48 ssid=NG700 id=0 mode=station pairwise_cipher=CCMP group_cipher=CCMP key_mgmt=WPA2-PSK wpa_state=COMPLETED p2p_device_address=02:9a:02:7b:60:ac address=c4:9a:02:7b:60:ac uuid=530d3fd0-1ba3-5409-a336-ff4e42af59a2
D/PCSuite ( 6332): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
I/WifiServiceExtension( 1028): setVHTCapabilityType  : false
,V/WiFiOffLoadBroadcast( 6269): WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
I/WifiServerServiceExt( 1028): wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
I/WifiServerServiceExt( 1028): setKeepAlivePacketInterval msec : 60
I/StatusBar.NetworkController( 1446): networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1446): mWifiConnected = false, mWifiLevel = 0
,W/Settings( 1028): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1028): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1028): NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
W/Settings( 1028): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1028): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1028): NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
D/StatusBar.NetworkController( 1446): refreshViews: Data not connected!! Set no data type icon / Roaming
,D/ConnectivityService( 1028): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
D/ConnectivityService( 1028): Got NetworkAgent Messenger
D/ConnectivityService( 1028): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
D/ConnectivityService( 1028): NetworkAgent connected
E/WifiConfigStore( 1028): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/WifiNative-wlan0( 1028): doBoolean: SET_NETWORK 0 bssid any
D/WifiNative-wlan0( 1028): SET_NETWORK 0 bssid any: returned true
D/WifiNative-wlan0( 1028): doBoolean: SAVE_CONFIG
I/StatusBar.NetworkController( 1446): networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1446): mWifiConnected = false, mWifiLevel = 0
D/WifiNative-wlan0( 1028): SAVE_CONFIG: returned true
,D/StatusBar.NetworkController( 1446): refreshViews: Data not connected!! Set no data type icon / Roaming
E/WifiConfigStore( 1028): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,D/WifiNative-wlan0( 1028): doBoolean: SET_NETWORK 0 bssid any
D/WifiNative-wlan0( 1028): SET_NETWORK 0 bssid any: returned true
D/WifiNative-wlan0( 1028): doBoolean: SAVE_CONFIG
D/WifiNative-wlan0( 1028): SAVE_CONFIG: returned true
D/CommandListener(  319): Setting iface cfg
W/FormManager( 6300): Network not available. Please check & try again.
E/WifiStateMachine( 1028): Start Dhcp Watchdog 1
E/WifiStateMachine( 1028):  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 18 0 rt=254373  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine( 1028):  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 18 0 rt=254374  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine( 1028):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 18 0 rt=254374  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
D/WifiServerServiceExt( 1028): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1028): setSupplicantStateFOUR_WAY_HANDSHAKE
D/DhcpStateMachine( 1028): StoppedState
D/DhcpStateMachine( 1028): StoppedState{ when=-2ms what=196609 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine( 1028): WaitBeforeStartState
E/WifiStateMachine( 1028):  ObtainingIpState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1028):  L2ConnectedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1028):  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1028):  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1028):  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1028):  DefaultState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1028):  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 19 0 rt=254378  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine( 1028):  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 19 0 rt=254378  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine( 1028):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 19 0 rt=254378  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine( 1028):  ObtainingIpState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:-1908051885] from screen [on:0 period:-1908051885]
E/WifiStateMachine( 1028):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-1908051884]
I/WifiNative-HAL( 1028): startHal
E/wifi    ( 1028): getStaticLongField sWifiHalHandle 0x989908bc
E/WifiHAL ( 1028): Could not connect handle
D/wifi    ( 1028): halHandle = 0x0, mVM = 0xb487c280, mCls = 0x70180e
I/WifiNative-HAL( 1028): Could not start hal
D/WifiNative-wlan0( 1028): doString: [SIGNAL_POLL]
D/WifiServerServiceExt( 1028): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1028): setSupplicantStateGROUP_HANDSHAKE
E/WifiStateMachine( 1028):  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
W/ResourcesManager( 6399): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
D/ConnectivityService( 1028): updateNetworkScore for NetworkAgentInfo [WIFI () - 100] to 60
E/WifiStateMachine( 1028):  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1028):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1028):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1028):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1028):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
D/StatusBar.NetworkController( 1446): refreshViews: Data not connected!! Set no data type icon / Roaming
D/ConnectivityService( 1028): Update of LinkProperties for NetworkAgentInfo [WIFI () - 100]; created=false
D/WifiServerServiceExt( 1028): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1028): setSupplicantStateCOMPLETED
,E/WifiStateMachine( 1028):  ObtainingIpState CMD_PRE_DHCP_ACTION 0 0 txpkts=0,0,0
E/WifiStateMachine( 1028):  L2ConnectedState CMD_PRE_DHCP_ACTION 0 0 txpkts=0,0,0
D/WifiNative-wlan0( 1028): doBoolean: DRIVER SETSUSPENDMODE 0
D/WiFiOffLoadBroadcast( 6269): MCCMNC not supported: null
V/FormManager( 6300): Network unavailable.
V/FormManager( 6300): Network unavailable.
,D/LGDMClient( 3979): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
,D/LGDMClient( 3979): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
W/ContextImpl( 3979): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
I/ActivityManager( 1028): Killing 5164:com.wsandroid.suite.lge/1000 (adj 15): empty #17
I/wpa_supplicant( 6292): wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 0
D/WifiNative-wlan0( 1028): DRIVER SETSUSPENDMODE 0: returned true
D/WifiNative-wlan0( 1028): doBoolean: SET ps 0
D/WifiNative-wlan0( 1028): SET ps 0: returned true
D/WifiNative-wlan0( 1028): doBoolean: DRIVER BTCOEXMODE 1
I/wpa_supplicant( 6292): wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 1
D/WifiNative-wlan0( 1028): DRIVER BTCOEXMODE 1: returned true
E/WifiStateMachine( 1028): CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
V/DhcpStateMachine( 1028): Current State is mWaitBeforeStartState.
D/LGWifiP2pService( 1028): InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@269d6dd2 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1028): P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@269d6dd2 target=com.android.internal.util.StateMachine$SmHandler }
V/LgDhcpStateMachineHelper( 1028): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
V/LgDhcpStateMachineHelper( 1028): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700" is not exist.
D/DhcpStateMachine( 1028): WaitBeforeStartState{ when=0 what=196615 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine( 1028): DHCP Start wake lock is acquired.
D/AuthorizationBluetoothService( 2109): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,D/WifiServerServiceExt( 1028): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1028): setSupplicantStateCOMPLETED
W/libprocessgroup( 1028): failed to open /acct/uid_1000/pid_5164/cgroup.procs: No such file or directory
W/ContextImpl( 3979): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,D/LGDMClient( 3979): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=3, isUserType=1
,D/LGDMClient( 3979): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
,D/LGDMClient( 3979): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
D/DhcpStateMachine( 1028): DHCPV4 request on wlan0
V/LgDhcpStateMachineHelper( 1028): [bssid] hash key :c0:ff:d4:d3:aa:48
D/LgDhcpStateMachineHelper( 1028): dhcp.ap.macaddress = c0:ff:d4:d3:aa:48
,I/ActivityManager( 1028): Start proc com.wsandroid.suite.lge for broadcast com.wsandroid.suite.lge/com.wavesecure.core.WSAndroidSystemIntentReceiver: pid=6429 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,W/dhcpcd  ( 6428): type=1400 audit(0.0:157): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
W/dhcpcd  ( 6428): type=1400 audit(0.0:158): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,I/dhcpcd  ( 6428): version 5.5.6 starting
E/dhcpcd  ( 6428): get_duid: m
D/dhcpcd  ( 6428): wlan0: using ClientID 01:c4:9a:02:7b:60:ac
D/dhcpcd  ( 6428): wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason PREINIT
,W/ResourcesManager( 6429): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,D/PluginManager( 6429): init()
,D/dhcpcd  ( 6428): getUsingAPMacAddress: c0:ff:d4:d3:aa:48 , return 1
D/dhcpcd  ( 6428): [read_lease] unlink /data/misc/dhcp/dhcpcd-wlan0.lease, link /data/misc/dhcp/dhcpcd-wlan0-c0:ff:d4:d3:aa:48.lease2
D/dhcpcd  ( 6428): wlan0: reading lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
I/dhcpcd  ( 6428): wlan0: rebinding lease of 192.168.1.141
,D/dhcpcd  ( 6428): wlan0: sending REQUEST (xid 0x29ba25f7), next in 3.94 seconds
E/QC-QMI  ( 6389): qmi_client [6389] 13: failed to locate client data
,E/QC-QMI  (  479): qmuxd: RX on fd=32 returned error=0 errno[2:No such file or directory]
E/QC-QMI  (  479): QMUX qmux_client_id=13 not found in qmux client list, unable to remove
I/qcom-bluetooth( 6452): /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 58:3f:54:73:64:c0 
,I/qcom-bluetooth( 6453): /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,I/bt_vendor( 6231): bluetooth satus is on
D/bt_hci_bdroid( 6231): preload
D/bt_userial_mct( 6231): userial_open(port:0)
I/bt_vendor( 6231): bt-vendor : BT_VND_OP_USERIAL_OPEN
I/bt_vendor( 6231): Done intiailizing UART
,I/bt_vendor( 6231): Done intiailizing UART
I/bt_userial_mct( 6231): CMD=66, EVT=66, ACL_Out=67, ACL_In=67
I/bt_vendor( 6231): Bluetooth Firmware and transport layer are initialized
I/bt-btu  ( 6231): btu_task received preload complete event
D/bt_userial_mct( 6231): Entering userial_read_thread()
W/bt-l2cap( 6231): L2CAP - L2CA_Register() called for PSM: 0x0001
W/bt-l2cap( 6231): L2CAP - L2CA_Register() called for PSM: 0x001f
W/bt-l2cap( 6231): L2CAP - L2CA_Register() called for PSM: 0x0003
I/        ( 6231): BTE_InitTraceLevels -- TRC_HCI
I/        ( 6231): BTE_InitTraceLevels -- TRC_L2CAP
I/        ( 6231): BTE_InitTraceLevels -- TRC_RFCOMM
I/        ( 6231): BTE_InitTraceLevels -- TRC_AVDT
I/        ( 6231): BTE_InitTraceLevels -- TRC_AVRC
I/        ( 6231): BTE_InitTraceLevels -- TRC_A2D
I/        ( 6231): BTE_InitTraceLevels -- TRC_BNEP
I/        ( 6231): BTE_InitTraceLevels -- TRC_BTM
I/        ( 6231): BTE_InitTraceLevels -- TRC_HID_HOST
I/        ( 6231): BTE_InitTraceLevels -- TRC_GAP
I/        ( 6231): BTE_InitTraceLevels -- TRC_PAN
I/        ( 6231): BTE_InitTraceLevels -- TRC_SDP
I/        ( 6231): BTE_InitTraceLevels -- TRC_GATT
I/        ( 6231): BTE_InitTraceLevels -- TRC_SMP
I/        ( 6231): BTE_InitTraceLevels -- TRC_BTAPP
I/        ( 6231): BTE_InitTraceLevels -- TRC_BTIF
W/bt-btm  ( 6231): btm_decode_ext_features_page Secure conn Controller support Enabled
E/bt-btm  ( 6231): BTM_SecRegister:p_cb_info->p_le_callback == 0xa0209061 
E/bt-btm  ( 6231): BTM_SecRegister: btm_cb.api.p_le_callback = 0xa0209061 
,E/bt-btif ( 6231): Calling BTA_HhEnable
W/bt-l2cap( 6231): btif_storage_get_adapter_property service_mask
E/bt-btif ( 6231): btif_storage_get_adapter_property service_mask:0x2140040
W/bt-l2cap( 6231): L2CAP - L2CA_Register() called for PSM: 0x0017
W/bt-l2cap( 6231): L2CAP - L2CA_Register() called for PSM: 0x001b
D/BluetoothAdapterProperties( 6231): Address is:58:3F:54:73:64:C0
W/bt-l2cap( 6231): L2CAP - L2CA_Register() called for PSM: 0x0011
W/bt-l2cap( 6231): L2CAP - L2CA_Register() called for PSM: 0x0013
D/BluetoothAdapterProperties( 6231): Name is: G3-1
D/BluetoothManagerService( 1028): Bluetooth Adapter name changed to G3-1
D/BluetoothManagerService( 1028): Stored Bluetooth name: G3-1
D/BluetoothAdapterProperties( 6231): Scan Mode:20
D/BluetoothAdapterProperties( 6231): Discoverable Timeout:120
D/bt_hci_bdroid( 6231): postload
D/bt_hci_bdroid( 6231): Used up Tx Cmd credits
W/bt-l2cap( 6231): L2CAP - L2CA_Register() called for PSM: 0x000f
W/bt-smp  ( 6231): Key(LSB ~ MSB) = 0a 3c a6 fe eb 17 6a 79 a6 1f 0a 0b f9 50 a0 5f 
,W/bt-smp  ( 6231): Plain text(LSB ~ MSB) = 67 11 51 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 6231): Encrypted text(LSB ~ MSB) = 9b 7d 3c bb 25 92 40 06 98 7f 39 66 73 d6 90 e0 
D/bt_hci_bdroid( 6231): Used up Tx Cmd credits
D/bt_hci_bdroid( 6231): Used up Tx Cmd credits
D/bt_hci_bdroid( 6231): Used up Tx Cmd credits
W/bt-btm  ( 6231): Stopping oneshot timer
D/bt_hci_bdroid( 6231): Used up Tx Cmd credits
E/bt_mct  ( 6231): hci lib postload completed
D/bte_conf( 6231): Device ID record 1 : primary
D/bte_conf( 6231):   vendorId            = 00c4
,D/bte_conf( 6231):   vendorIdSource      = 0001
D/bte_conf( 6231):   product             = 13a1
,D/bte_conf( 6231):   version             = 1000
D/bte_conf( 6231):   clientExecutableURL = 
D/bte_conf( 6231):   serviceDescription  = 
D/bte_conf( 6231):   documentationURL    = 
D/bte_conf( 6231): bte_load_did_conf no section named DID2.
,D/BluetoothAdapterState( 6231): CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
D/BluetoothAdapterProperties( 6231): ScanMode =  20
D/BluetoothAdapterProperties( 6231): State =  11
W/sh      ( 6457): type=1400 audit(0.0:159): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
W/sh      ( 6457): type=1400 audit(0.0:160): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
D/BluetoothAdapterProperties( 6231): mDiscoverableTimeout = 120
V/LGBluetoothServiceAdapter( 6231): [BTUI] state:11, scanmode:20, timeout:120
D/BluetoothAdapterProperties( 6231): Setting state to 12
I/BluetoothAdapterState( 6231): Bluetooth adapter state changed: 11-> 12
D/BluetoothPanServiceJni( 6231): control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
I/BluetoothAdapterState( 6231): Entering On State
D/btif_config_util( 6231): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
D/BluetoothManagerService( 1028): Message: 60
D/BluetoothManagerService( 1028): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
D/BluetoothManagerService( 1028): Broadcasting onBluetoothStateChange(true) to 5 receivers.
,D/BluetoothHeadset( 1850): onBluetoothStateChange: up=true
D/LGBluetoothServiceAdapter( 6231): [BTUI] OnState
D/LGBluetoothServiceAdapter( 6231): [BTUI]         global_name: G3-1
D/LGBluetoothServiceAdapter( 6231): [BTUI]         local_name: G3-1
D/BluetoothAdapterService( 6231): [BTUI] autoConnect() : not allowed
D/BluetoothHeadset( 1028): onBluetoothStateChange: up=true
D/BluetoothHeadset( 1850): onBluetoothStateChange: up=true
D/BluetoothA2dp( 1028): onBluetoothStateChange: up=true
D/BluetoothHeadset( 1850): onBluetoothStateChange: up=true
,E/BluetoothManagerService( 1028): Fail to bind to: Intent { act=android.bluetooth.IQBluetooth }
D/BluetoothManagerService( 1028): Bluetooth State Change Intent: 11 -> 12
I/[SystemUI]BluetoothHandler( 1446): Receive : BluetoothAdapter.ACTION_STATE_CHANGED
D/LGBluetoothAPIService( 1944): [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
D/LGBluetoothAPIService( 1944): Message: 1
D/LGBluetoothAPIService( 1944): MESSAGE_BOOT_COMPLETED
,D/BluetoothManagerService( 1028): BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
I/LGBluetoothAPIService( 1944): [BTUI] LGBluetoothAPIService Binding Success
D/BluetoothManagerService( 1028): Message: 40
D/BluetoothManagerService( 1028): MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
I/BluetoothMapService( 6231): onReceive: android.bluetooth.adapter.action.STATE_CHANGED
D/BluetoothMapService( 6231): STATE_ON
D/LGBluetoothAPIServer( 6231): [BTUI] onCreate()
D/LGBluetoothAPIServer( 6231): [BTUI] onBind()
V/BluetoothMapService( 6231): Handler(): got msg=1
D/LGBluetoothAPIService( 1944): [BTUI] LGBluetoothAPIServiceConnection: connected to LGBluetoothAPIAdapter
D/LGBluetoothAPIService( 1944): Message: 100
D/LGBluetoothAPIService( 1944): MESSAGE_BLUETOOTH_SERVICE_CONNECTED
D/BluetoothMapMasInstance( 6231): Map Service startRfcommSocketListener
,D/BluetoothMapMasInstance( 6231): MAS initSocket()
D/BluetoothMapMasInstance( 6231):   masId = 00
D/BluetoothMapMasInstance( 6231):   msgTypes = 0e
D/BluetoothMapMasInstance( 6231):   masName = SMS/MMS
D/BluetoothMapMasInstance( 6231):   SDP string = 000eSMS/MMS
W/bt-smp  ( 6231): Key(LSB ~ MSB) = 0a 3c a6 fe eb 17 6a 79 a6 1f 0a 0b f9 50 a0 5f 
W/bt-smp  ( 6231): Plain text(LSB ~ MSB) = 42 ad 61 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 6231): Encrypted text(LSB ~ MSB) = 44 48 96 22 d9 b8 20 d8 ec eb 63 2e 18 fe 48 d5 
W/bt-btm  ( 6231): Stopping oneshot timer
D/BluetoothManagerService( 1028): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
W/BluetoothAdapter( 6231): getBluetoothService() called with no BluetoothManagerCallback
W/bt-smp  ( 6231): Key(LSB ~ MSB) = 0a 3c a6 fe eb 17 6a 79 a6 1f 0a 0b f9 50 a0 5f 
W/bt-smp  ( 6231): Plain text(LSB ~ MSB) = 9a f5 4d 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 6231): Encrypted text(LSB ~ MSB) = 43 50 92 bb 28 90 81 f4 fe e7 ce 1e 12 90 d2 e1 
W/bt-btm  ( 6231): Stopping oneshot timer
D/LGBluetoothServiceAdapter( 6231): [BTUI] createSocketChannel FD=73 mFd=0
V/BluetoothMapMasInstance( 6231): Succeed to create listening socket 
D/BluetoothMapMasInstance( 6231): Accepting socket connection...
,W/ContextImpl( 6269): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
W/bt-smp  ( 6231): Key(LSB ~ MSB) = 0a 3c a6 fe eb 17 6a 79 a6 1f 0a 0b f9 50 a0 5f 
W/bt-smp  ( 6231): Plain text(LSB ~ MSB) = a7 6c 4f 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 6231): Encrypted text(LSB ~ MSB) = d4 e2 f0 ee 37 ba f1 1a 3d 52 1d 0d 5b 4b e5 6d 
W/bt-btm  ( 6231): Stopping oneshot timer
I/qcom-bt-wlan-coex( 6465): /system/etc/init.qcom.coex.sh: btwlancoex/abtfilt not available 
D/LGBluetoothDeviceModeControllManager( 6231): [BTUI] checkDeviceModeAndSet, sinkMode : false
D/BluetoothAdapterService( 6231): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@20043093
V/BluetoothPbapService( 6231): Pbap Service onCreate
V/BluetoothPbapService( 6231): Starting PBAP service
D/LGBluetoothPbapAdapter( 6231): [BTUI] getInstance : create
V/BluetoothPbapService( 6231): action: android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothPbapService( 6231): state: 12
V/BluetoothPbapReceiver( 6231): PbapReceiver onReceive 
V/BluetoothPbapReceiver( 6231): ***********action = android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothPbapReceiver( 6231): ***********state = 12
W/bt-smp  ( 6231): Key(LSB ~ MSB) = 0a 3c a6 fe eb 17 6a 79 a6 1f 0a 0b f9 50 a0 5f 
W/bt-smp  ( 6231): Plain text(LSB ~ MSB) = e9 91 48 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 6231): Encrypted text(LSB ~ MSB) = 00 07 cb a1 1d ae 34 a2 e0 c2 e4 6f a9 aa 54 7f 
W/bt-btm  ( 6231): Stopping oneshot timer
V/BluetoothPbapService( 6231): Handler(): got msg=1
V/BluetoothPbapService( 6231): Pbap Service startRfcommSocketListener
,V/BluetoothPbapService( 6231): Pbap Service initSocket
D/BluetoothManagerService( 1028): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
W/BluetoothAdapter( 6231): getBluetoothService() called with no BluetoothManagerCallback
D/LGBluetoothServiceAdapter( 6231): [BTUI] createSocketChannel FD=75 mFd=73
V/BluetoothPbapService( 6231): Succeed to create listening socket 
V/BluetoothPbapService( 6231): Accepting socket connection...
,D/LocalBluetoothProfileManager( 6269): Adding local A2DP profile
D/BluetoothManagerService( 1028): Message: 30
D/LocalBluetoothProfileManager( 6269): Adding local HEADSET profile
,W/ExternalStrings( 6429): load override strings
W/ExternalStrings( 6429): java.lang.RuntimeException: Unexpected tag, got eat-comment
W/ExternalStrings( 6429): 	at com.mcafee.plugin.af.a(Unknown Source)
W/ExternalStrings( 6429): 	at com.mcafee.plugin.ac.b(Unknown Source)
W/ExternalStrings( 6429): 	at com.mcafee.plugin.ak.d(Unknown Source)
W/ExternalStrings( 6429): 	at com.mcafee.plugin.ak.a(Unknown Source)
W/ExternalStrings( 6429): 	at com.mcafee.app.s.getClassLoader(Unknown Source)
W/ExternalStrings( 6429): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5001)
W/ExternalStrings( 6429): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4609)
W/ExternalStrings( 6429): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4549)
W/ExternalStrings( 6429): 	at android.app.ActivityThread.access$1500(ActivityThread.java:148)
W/ExternalStrings( 6429): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1344)
W/ExternalStrings( 6429): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/ExternalStrings( 6429): 	at android.os.Looper.loop(Looper.java:135)
W/ExternalStrings( 6429): 	at android.app.ActivityThread.main(ActivityThread.java:5274)
W/ExternalStrings( 6429): 	at java.lang.reflect.Method.invoke(Native Method)
W/ExternalStrings( 6429): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/ExternalStrings( 6429): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
W/ExternalStrings( 6429): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
D/BluetoothManagerService( 1028): Message: 30
D/StatusProvider( 6429): onCreate
D/BluetoothManagerService( 1028): Message: 30
D/BluetoothManagerService( 1028): Message: 30
D/LocalBluetoothProfileManager( 6269): Adding local MAP profile
,D/BluetoothMap( 6269): Create BluetoothMap proxy object
D/BluetoothManagerService( 1028): Message: 30
D/BluetoothManagerService( 1028): Message: 30
D/LocalBluetoothProfileManager( 6269): LocalBluetoothProfileManager construction complete
V/BluetoothPbapService( 6231): Pbap Service onBind
D/BluetoothAdapterProperties( 6231): Discoverable Timeout:120
D/LGBluetoothDeviceModeControllManager( 6231): adapterPropertyChangedCallback on  LGAdapter : do nothing - 9
D/BluetoothAdapterProperties( 6231): Scan Mode:21
D/LGBluetoothDeviceModeControllManager( 6231): getDeviceMode  deviceMode 0
D/LGBluetoothUserBindClient( 6269): [BTUI] initUserBindClient
,W/ContextImpl( 6269): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.android.settings.bluetooth.LGBluetoothUserBindClient.initUserBindClient:90 com.android.settings.bluetooth.LGBluetoothUserBindClient.<init>:55 com.android.settings.bluetooth.LGBluetoothUserBindClient.getInstance:47 
D/DockEventReceiver( 6269): finishStartingService: stopping service
D/BluetoothA2dp( 6269): Proxy object connected
D/A2dpProfile( 6269): Bluetooth service connected
,V/Signer  ( 6429): override build config not found
D/Signer  ( 6429): value of property debug is false
,D/LGMDMWrapper( 6429): Found class 'com.mcafee.lgmdm.LGMDMWrapper$DataWipe'.
,D/LGMDMWrapper( 6429): Found class 'com.mcafee.lgmdm.LGMDMWrapper$DownloadMode'.
D/LGMDMWrapper( 6429): Found class 'com.mcafee.lgmdm.LGMDMWrapper$HardReset'.
D/LGMDMWrapper( 6429): Found class 'com.mcafee.lgmdm.LGMDMWrapper$HardwareKeyReset'.
D/LGMDMWrapper( 6429): Found class 'com.mcafee.lgmdm.LGMDMWrapper$RemoveDeviceAdmin'.
D/LGMDMWrapper( 6429): Found class 'com.mcafee.lgmdm.LGMDMWrapper$UnknownSourceInstallation'.
D/LGMDMWrapper( 6429): Found class 'com.mcafee.lgmdm.LGMDMWrapper$Usb'.
D/LGMDMWrapper( 6429): Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbDebugging'.
D/LGMDMWrapper( 6429): Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbHostStorage'.
D/LGMDMWrapper( 6429): Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbMediaTransfer'.
D/LGMDMWrapper( 6429): Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbPictureTransfer'.
D/LGMDMWrapper( 6429): Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbStorage'.
D/LGMDMWrapper( 6429): Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbTethering'.
V/LGMDMManager( 6429): Create singleton instance
D/BluetoothHeadset( 6269): Proxy object connected
,D/HeadsetProfile( 6269): Bluetooth service connected
D/BluetoothInputDevice( 6269): Proxy object connected
D/HidProfile( 6269): Bluetooth service connected
D/BluetoothPan( 6269): BluetoothPAN Proxy object connected
D/PanProfile( 6269): Bluetooth service connected
D/BluetoothMap( 6269): Proxy object connected
D/MapProfile( 6269): Bluetooth service connected
D/BluetoothMap( 6269): getConnectedDevices()
V/BluetoothMapService( 6231): getConnectedDevices()
D/BluetoothPbap( 6269): Proxy object connected
D/PbapServerProfile( 6269): Bluetooth service connected
D/LGBluetoothUserBindClient( 6269): [BTUI] onServiceConnected
D/BluetoothPermissionRequest( 6269): onReceive
D/LGBluetoothFeatureConfig( 6269): isPrivacyLogsEnabled : true
D/LGBluetoothUtils( 6269): [BTUI] FileNotFound: readProperty
D/LGBluetoothResetSettingReceiver( 6269): return without doing reset settings.
V/BluetoothOppReceiver( 6231): Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_ON
,I/LGBluetoothOppAdapter( 6231): [BTUI] startOppService()
V/BluetoothOppManager( 6231): restoreApplicationData! falsefalsenullnull
D/LGBluetoothFeatureConfig( 6231): isPrivacyLogsEnabled : true
,V/BtOppService( 6231): onCreate
V/BluetoothOppNotification( 6231): send message
V/BtOppService( 6231): Starting RfcommListener
D/BluetoothOppPreference( 6231): Dumping Names:  
D/BluetoothOppPreference( 6231): {}
D/BluetoothOppPreference( 6231): Dumping Channels:  
D/BluetoothOppPreference( 6231): {}
V/BtOppService( 6231): onStartCommand
V/BluetoothFtpReceiver( 6231): BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothFtpReceiver( 6231): BluetoothFtpReceiver Start Service
V/BtOppService( 6231): pendingUpdate is true keepUpdateThread is false sListenStarted is true
V/BluetoothOppNotification( 6231): new notify threadi!
V/BluetoothOppNotification( 6231): send delay message
V/BtOppService( 6231): start RfcommListener
D/LGMDMWrapper( 6429): LG MDM library v4.0.0 is available on this device.
V/BtOppService( 6231): RfcommListener started
,V/BtOppRfcommListener( 6231): Starting RFCOMM listener....
D/BluetoothManagerService( 1028): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
V/BluetoothOppProvider( 6231): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
V/BluetoothOppProvider( 6231): starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
V/BtOppService( 6231): Deleted complete outbound shares, number =  0
D/BluetoothAdapterService( 6231): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@20043093
W/BluetoothAdapter( 6231): getBluetoothService() called with no BluetoothManagerCallback
V/BluetoothFtpService( 6231): Ftp Service onCreate
I/BluetoothFtpService( 6231): Ftp Service onCreate
V/BluetoothFtpService( 6231): Ftp Service onStartCommand
V/BluetoothFtpService( 6231): action: android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothFtpService( 6231): Starting Listening on sockets
V/BluetoothSapReceiver( 6231): [BTUI] checkServiceStart
V/BluetoothSapReceiver( 6231): [BTUI] region:EU country:EU
V/BluetoothSapReceiver( 6231): SapReceiver onReceive 
V/BluetoothSapReceiver( 6231): action = android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothSapReceiver( 6231):  Bluetooth Adapter state = 12
V/BluetoothSapReceiver( 6231): Calling SAP service start service with action = null
V/BtOppService( 6231): Deleted complete inbound failed shares, number = 0
D/LGBluetoothServiceAdapter( 6231): [BTUI] createSocketChannel FD=78 mFd=75
V/BluetoothOppProvider( 6231): starting query, database is not null; projection[0] is _id; selection is direction=1 AND status=200 AND visibility=1; selectionArgs is null; sort is _id.
V/BtOppRfcommListener( 6231): Started RFCOMM listener....
I/BtOppRfcommListener( 6231): Accept thread started.
V/BtOppRfcommListener( 6231): Accepting connection...
V/BtOppService( 6231): ContentObserver received notification
V/BluetoothFtpService( 6231): Handler(): got msg=1
,V/BluetoothFtpService( 6231): Ftp Service startRfcommSocketListener
V/BluetoothFtpService( 6231): Ftp Service initSocket
V/BluetoothOppProvider( 6231): created cursor android.database.sqlite.SQLiteCursor@184a5dea on behalf of 
V/BluetoothOppProvider( 6231): created cursor android.database.sqlite.SQLiteCursor@d4378db on behalf of 
V/BtOppService( 6231): pendingUpdate is true keepUpdateThread is false sListenStarted is true
V/BluetoothOppProvider( 6231): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
V/BluetoothOppProvider( 6231): created cursor android.database.sqlite.SQLiteCursor@8ef5f78 on behalf of 
V/BluetoothOppProvider( 6231): created cursor android.database.sqlite.SQLiteCursor@bd26651 on behalf of 
D/AuthorizationBluetoothService( 2109): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
D/BluetoothManagerService( 1028): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
W/BluetoothAdapter( 6231): getBluetoothService() called with no BluetoothManagerCallback
D/LGBluetoothServiceAdapter( 6231): [BTUI] createSocketChannel FD=82 mFd=78
V/BluetoothFtpService( 6231): Succeed to create listening socket on channel 20
V/BluetoothOppNotification( 6231): mUpdateCompleteNotification = true
V/BtOppService( 6231): ContentObserver received notification
V/BluetoothOppNotification( 6231): update too frequent, put in queue
V/BluetoothFtpService:RfcommSocketAcceptThread( 6231): Run Accept thread
V/BtOppService( 6231): pendingUpdate is true keepUpdateThread is false sListenStarted is true
V/BluetoothOppProvider( 6231): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
V/BluetoothOppProvider( 6231): starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
V/BluetoothOppProvider( 6231): created cursor android.database.sqlite.SQLiteCursor@17686eb6 on behalf of 
D/BluetoothAdapterService( 6231): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@20043093
V/BluetoothSapService( 6231): Sap Service onCreate
,V/BluetoothOppNotification( 6231): update too frequent, put in queue
V/BluetoothSapService( 6231): action: android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothSapService( 6231): state: 12
V/BluetoothSapService( 6231): Starting SAP server process
V/BtOppService( 6231): pendingUpdate is false keepUpdateThread is false sListenStarted is true
V/BluetoothOppProvider( 6231): created cursor android.database.sqlite.SQLiteCursor@3f84c042 on behalf of 
V/BluetoothSapService( 6231): SAP Service startRfcommListenerThread
V/BluetoothOppNotification( 6231): outbound: succ-0  fail-0
V/BluetoothOppNotification( 6231): outbound notification was removed.
V/BluetoothSapService( 6231): Sap Service initRfcommSocket
V/BluetoothOppProvider( 6231): starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
D/BluetoothManagerService( 1028): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
V/BluetoothOppProvider( 6231): created cursor android.database.sqlite.SQLiteCursor@33262853 on behalf of 
W/BluetoothAdapter( 6231): getBluetoothService() called with no BluetoothManagerCallback
V/BluetoothOppNotification( 6231): inbound: succ-0  fail-0
D/LGBluetoothServiceAdapter( 6231): [BTUI] createSocketChannel FD=83 mFd=82
V/BluetoothSapService( 6231): Succeed to create listening socket 
V/BluetoothSapService( 6231): Accepting socket connection...
V/BluetoothOppNotification( 6231): inbound notification was removed.
V/BluetoothOppProvider( 6231): starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
V/BluetoothOppProvider( 6231): created cursor android.database.sqlite.SQLiteCursor@2abaa590 on behalf of 
W/sapd    ( 6483): type=1400 audit(0.0:161): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
W/sapd    ( 6483): type=1400 audit(0.0:162): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
D/PostponalbeReceiver( 6429): WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
V/BT_SAP  ( 6483): Event pipe created
V/BT_SAP  ( 6483): create_server_socket qcom.sap.server
V/BT_SAP  ( 6483): created socket fd 6
,I/PCSuite ( 6332): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 6332): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 6332): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 6269): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
W/ContextImpl( 6429): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
D/WiFiOffLoadBroadcast( 6269): MCCMNC not supported: null
I/ActivityManager( 1028): Start proc com.lge.qremote for broadcast com.lge.qremote/.settings.WiFiStateReceiver: pid=6490 uid=10112 gids={50112, 9997, 1028, 1015, 3003, 3002} abi=armeabi
I/ActivityManager( 1028): Killing 2188:com.lge.music/u0a34 (adj 15): empty #17
,V/AudioFlinger(  324): 2188 died, releasing its sessions
V/AudioFlinger(  324):  pid 1850 @ 0
V/AudioFlinger(  324):  pid 3211 @ 1
V/AudioFlinger(  324):  pid 3211 @ 2
,W/ActivityThread( 6429): ClassLoader.getResources: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/libprocessgroup( 1028): failed to open /acct/uid_10034/pid_2188/cgroup.procs: No such file or directory
,W/ResourcesManager( 6490): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
D/QRemote ( 6490): [QRemoteApplication.java:230:onCreate()] oooooo QRemoteApp onCreate....
,D/QRemote ( 6490): [CarrierUtils.java:858:getHardwareSettings()] oooooo qremote android.os.Build.MODEL = LG-D855
I/QRemote ( 6490): [CarrierUtils.java:859:getHardwareSettings()] oooooo getCountry :: EU
I/QRemote ( 6490): [CarrierUtils.java:860:getHardwareSettings()] oooooo getCarrier :: OPEN
I/QRemote ( 6490): [CarrierUtils.java:861:getHardwareSettings()] oooooo getArea :: COM
D/QRemote ( 6490): [CarrierUtils.java:862:getHardwareSettings()] oooooo Loading Config...
D/QRemote ( 6490): [CarrierUtils.java:876:getHardwareSettings()] oooooo qremote configuration file = R.xml.qremote_conf
,D/QRemote ( 6490): [QRemoteApplication.java:701:updateWidget()] oooooo Widget count is [1]. send broadcast
D/QRemote ( 6490): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6490): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 6490): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,V/[BNRBootReceiver]( 5947): boot receiver action = android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,D/BNRAndroBeam( 5947): [BnR DirectBeam] Android Direct Beam(NFC) Connection changed
D/QRemote ( 6490): [QRemoteService.java:196:onCreate()] oooooo 140526:onCreate
V/[BNRBootReceiver]( 5947): Boot Receiver Return
D/QRemote ( 6490): [QRemoteService.java:217:onStartCommand()] oooooo 140526:onStartCommand:action:action.application.oncreate. startId:1, flags:0
D/PostponalbeReceiver( 6429): WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
W/ContextImpl( 6429): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
V/WiFiOffLoadBroadcast( 6269): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6269): MCCMNC not supported: null
I/art     ( 1028): Explicit concurrent mark sweep GC freed 55134(2MB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 44MB/66MB, paused 2.263ms total 102.658ms
,D/QRemote ( 6490): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6490): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 6490): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,V/WiFiOffLoadBroadcast( 6269): WiFiOffLoadBroadcast: android.net.wifi.SCAN_RESULTS
D/WiFiOffLoadBroadcast( 6269): Not supported operator for automatic switch
W/ContextImpl( 6429): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
D/PostponalbeReceiver( 6429): WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
V/WiFiOffLoadBroadcast( 6269): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6269): MCCMNC not supported: null
D/QRemote ( 6490): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6490): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 6490): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
D/PostponalbeReceiver( 6429): WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
W/ContextImpl( 6429): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
V/WiFiOffLoadBroadcast( 6269): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6269): MCCMNC not supported: null
D/QRemote ( 6490): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6490): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 6490): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,D/UsbSettingsReceiver( 6269): [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
D/UsbSettingsReceiver( 6269): [AUTORUN] sys.usb.config = ptp_only,adb
D/UsbSettingsReceiver( 6269): [AUTORUN] sys.usb.state = ptp_only,adb
D/UsbSettingsReceiver( 6269): [AUTORUN] persist.sys.usb.config = ptp_only,adb
D/UsbSettingsReceiver( 6269): [AUTORUN] onReceive() : app userid = 0, current userid = 0
,D/UsbSettingsControl( 6269): [AUTORUN] getUsbConnected() : connected=true
D/UsbSettingsReceiver( 6269): [AUTORUN] onReceive() : availableList=[wlan0]
D/UsbSettingsReceiver( 6269): [AUTORUN] onReceive() : activeList=[]
D/UsbSettingsReceiver( 6269): [AUTORUN] onReceive() : errorList=[]
D/UsbSettingsControl( 6269): [AUTORUN] isAutorunTimer() : mAutorunChanging=false
D/UsbSettingsReceiver( 6269): [AUTORUN] onReceive() : TetherState Changed=wlan0
D/UsbSettingsControl( 6269): [AUTORUN] setTetherStatus() : status=false
D/PostponalbeReceiver( 6429): WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
W/ContextImpl( 6429): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
V/WiFiOffLoadBroadcast( 6269): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6269): MCCMNC not supported: null
E/WifiStateMachine( 1028):  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
D/QRemote ( 6490): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
E/WifiStateMachine( 1028):  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
D/QRemote ( 6490): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
E/WifiStateMachine( 1028):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
I/QRemote ( 6490): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
E/WifiStateMachine( 1028):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1028):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1028):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
D/PostponalbeReceiver( 6429): WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
W/ContextImpl( 6429): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
D/ConnectivityService( 1028): Update of LinkProperties for NetworkAgentInfo [WIFI () - 100]; created=false
V/WiFiOffLoadBroadcast( 6269): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 6269): MCCMNC not supported: null
D/QRemote ( 6490): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6490): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 6490): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,D/PostponalbeReceiver( 6429): WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
W/ContextImpl( 6429): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
V/WiFiOffLoadBroadcast( 6269): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 6269): MCCMNC not supported: null
D/QRemote ( 6490): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,D/QRemote ( 6490): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 6490): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
D/PostponalbeReceiver( 6429): WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
W/ContextImpl( 6429): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
V/WiFiOffLoadBroadcast( 6269): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/LgDataFeature( 6429): LgDataFeature() Constructor: none
D/LgDataFeature( 6429): LgDataFeature() Constructor Done, null
D/WiFiOffLoadBroadcast( 6269): MCCMNC not supported: null
,D/QRemote ( 6490): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6490): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 6490): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
D/PostponalbeReceiver( 6429): WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'null'.
,V/QRemote ( 6490): [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
D/QRemote ( 6490): [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
D/QRemote ( 6490): [QRemoteApplication.java:86:getControlManager()] oooooo mControlManager is null. make new RemoteControlManager
D/LgDataFeature( 6490): LgDataFeature() Constructor: none
D/LgDataFeature( 6490): LgDataFeature() Constructor Done, null
,V/SoundPool( 6490): SoundPool constructor: maxChannels=2, attr.usage=13, attr.flags=0x0, attr.tags=
V/SoundPool( 6490): load: fd=30, offset=10857164, length=17813, priority=1
V/SoundPool( 6490): create sampleID=1, fd=31, offset=17813 length=10857164
V/SoundPool( 6490): doLoad: loading sample sampleID=1
I/QRemote ( 6490): [RemoteControlManager.java:157:onBindIRService()] oooooo bind
D/QRemote ( 6490): [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
V/SoundPool( 6490): Start decode
,V/MediaPlayer[Native]( 6490): decode(31, 10857164, 17813)
D/UEI.SmartControl( 5889): QS Service created
V/MediaPlayerService(  324): decode(24, 10857164, 17813)
W/BrunchPlayerTypeImpl(  324): [SelectPlayer] LocalType
W/BrunchPlayerTypeImpl(  324): [getMediaType] EXTEND_MEDIA_MIMETYPE = application/ogg
W/BrunchPlayerTypeImpl(  324): [FindUsePlayer] type = [application/ogg]
W/BrunchPlayerTypeImpl(  324): [FindUsePlayer] componentName = [9101]
W/MediaPlayerFactory(  324): [getPlayerType:fd] nType = 3
V/MediaPlayerService(  324): player type = 3
V/AwesomePlayer(  324): AwesomePlayer create()
V/AwesomePlayer(  324): reset_l() 
V/AwesomePlayer(  324): cancelPlayerEvents
V/AwesomePlayer(  324): setAudioSink() 
V/AwesomePlayer(  324): reset_l() 
V/AudioCache(  324): notify(0xb143abc0, 8, 0, 0)
V/AudioCache(  324): ignored
V/AwesomePlayer(  324): cancelPlayerEvents
D/Utils   (  324): printFileName fd(25) -> /data/preload/LGQRemote/LGQRemote.apk
V/AwesomePlayer(  324): setDataSource_l dataSource
V/LGParserOSAL(  324): SniffLGParser start
V/LGParserOSAL(  324): MainType:5, SubType=0
V/LGParserOSAL(  324): #### check Mime : application/ogg
V/LGParserOSAL(  324): Detector mimeType:application/ogg, Confidence=1.000000
E/MediaExtractor(  324): Use LGExtractor :application/ogg 
E/QRemote ( 6490): [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
D/QRemote ( 6490): [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
W/ContextImpl( 6429): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.vsmandroid.gh.h:-1 com.mcafee.vsm.ext.common.a.d.a:-1 com.mcafee.vsm.ext.common.api.ExtUtils.stopApp:-1 
V/LGMDMManager( 6490): Create singleton instance
,I/UEI.SmartControl( 5889): Service initServices...
D/UEI.SmartControl( 5889): QS start get config
V/LGParserOSAL(  324): supported mime: application/ogg
V/AwesomePlayer(  324): setDataSource_l() extractor countTracks=1
V/AwesomePlayer(  324): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer(  324): mBitrate = -1 bits/sec
V/AwesomePlayer(  324): AudioTrack Setting
V/AwesomePlayer(  324): AudioTrack Setting channelCount = 2
V/AwesomePlayer(  324): setAudioSource() 
V/MediaPlayerService(  324): prepare
V/AwesomePlayer(  324): prepareAsync_l() 
V/MediaPlayerService(  324): wait for prepare
V/AwesomePlayer(  324): onPrepareAsyncEvent() 
V/AwesomePlayer(  324): initAudioDecoder() 
W/Utils   (  324): bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
V/AudioSystem(  324): isOffloadSupported()
V/AudioPolicyManager(  324): isOffloadSupported: SR=48000, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
D/AudioPolicyManager(  324): isOffloadSupported: stream_type != MUSIC, returning false
I/AudioFlinger(  324): isAudioPlaybackHookOn() false
V/AwesomePlayer(  324): getUseOffload() = 0 
V/OMXCodec(  324): OMXCodec::Create
V/OMXCodec(  324): findMatchingCodecs()
V/OMXCodec(  324): matching 'OMX.google.vorbis.decoder' quirks 0x00000000
V/OMXCodec(  324): matchingCodecs.size()=1
V/OMXCodec(  324): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
D/OMXCodec(  324): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
V/LGCodecAdapter(  324): LG Codec Adapter start
V/OMXCodec(  324): OMXCodec Createtor
V/OMXCodec(  324): setComponentRole
V/OMXCodec(  324): configureCodec protected=0
V/LGCodecAdapter(  324): called getLGCodecSpecificData
V/LGCodecOSAL(  324): Called LGgetCodecSpecificDataMETA
D/SiteAdvisor( 6429): com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.google.android.browser/com.android.browser.BrowserActivity not supported
V/LGCodecOSAL(  324): Called LGconfigureCodecMETA
V/LGCodecOSAL(  324): Called LGconfigureCodecMSG
V/LGCodecOSAL(  324): Not support LGCodec
V/OMXCodec(  324): [OMX.google.vorbis.decoder] initOutputFormat()
V/OMXCodec(  324): Codec outputs a different number of channels than the input stream contains (contains 2 channels, codec outputs 1 channels).
V/OMXCodec(  324): Codec outputs at different sampling rate than what the input stream contains (contains data at 48000 Hz, codec outputs 44100 Hz)
I/AwesomePlayer(  324): Could not offload audio decode, try pcm offload
W/Utils   (  324): bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
V/AudioSystem(  324): isOffloadSupported()
V/AudioPolicyManager(  324): isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
D/AudioPolicyManager(  324): isOffloadSupported: stream_type != MUSIC, returning false
V/OMXCodec(  324): [OMX.google.vorbis.decoder] start mState=1
V/OMXCodec(  324): init()
V/OMXCodec(  324): [OMX.google.vorbis.decoder] setState mState=1 , newState=2
V/OMXCodec(  324): allocateBuffers
V/OMXCodec(  324): allocateBuffersOnPort portIndex=0
V/OMXCodec(  324): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
V/OMXCodec(  324): [OMX.google.vorbis.decoder] allocated buffer 0xb54f7e20 on input port
V/OMXCodec(  324): [OMX.google.vorbis.decoder] allocated buffer 0xb54f7ec0 on input port
V/OMXCodec(  324): [OMX.google.vorbis.decoder] allocated buffer 0xb54f7f10 on input port
V/OMXCodec(  324): [OMX.google.vorbis.decoder] allocated buffer 0xb54f7f60 on input port
V/OMXCodec(  324): allocateBuffersOnPort portIndex=1
V/OMXCodec(  324): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
V/OMXCodec(  324): [OMX.google.,vorbis.decoder] allocated buffer 0xb54f7fb0 on output port
V/OMXCodec(  324): [OMX.google.vorbis.decoder] allocated buffer 0xb57bf150 on output port
V/OMXCodec(  324): [OMX.google.vorbis.decoder] allocated buffer 0xb57bf1f0 on output port
V/OMXCodec(  324): [OMX.google.vorbis.decoder] allocated buffer 0xb57bf380 on output port
V/OMXCodec(  324): init() mAsyncCompletion wait!!! 
V/OMXCodec(  324): [OMX.google.vorbis.decoder] onStateChange 2
V/OMXCodec(  324): [OMX.google.vorbis.decoder] Now Idle.
V/OMXCodec(  324): [OMX.google.vorbis.decoder] setState mState=2 , newState=3
V/OMXCodec(  324): [OMX.google.vorbis.decoder] onStateChange 3
V/OMXCodec(  324): [OMX.google.vorbis.decoder] Now Executing.
V/OMXCodec(  324): [OMX.google.vorbis.decoder] setState mState=3 , newState=4
V/OMXCodec(  324): init() mAsyncCompletion wait free! 
V/AwesomePlayer(  324): finishAsyncPrepare_l() 
V/AudioCache(  324): notify(0xb143abc0, 5, 0, 0)
V/AudioCache(  324): ignored
V/AudioCache(  324): notify(0xb143abc0, 1, 0, 0)
V/AudioCache(  324): prepared
V/AudioCache(  324): wait - success
V/MediaPlayerService(  324): start
V/AwesomePlayer(  324): play_l() 
V/AwesomePlayer(  324): play_l m_isDivXDRM=0, bpurchasefile:0
V/AwesomePlayer(  324): createAudioPlayer_l
V/AwesomePlayer(  324): seekAudioIfNecessary_l() 
V/AwesomePlayer(  324): startAudioPlayer_l() 
D/AudioPlayer(  324): start of Playback, useOffload 0
V/OMXCodec(  324): [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
V/OMXCodec(  324): [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
V/OMXCodec(  324): [OMX.google.vorbis.decoder] OMX_EventPortSettingsChanged(port=1, data2=0x00000000)
V/OMXCodec(  324): [OMX.google.vorbis.decoder] PORT_SETTINGS_CHANGED(1)
V/OMXCodec(  324): [OMX.google.vorbis.decoder] setState mState=4 , newState=7
V/OMXCodec(  324): [OMX.google.vorbis.decoder] disablePortAsync portIndex=1
V/OMXCodec(  324): [OMX.google.vorbis.decoder] sending OMX_CommandPortDisable(1)
V/OMXCodec(  324): [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
V/OMXCodec(  324): [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041886128
V/OMXCodec(  324): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
V/OMXCodec(  324): [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3044798800
V/OMXCodec(  324): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
V/OMXCodec(  324): [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3044798960
V/OMXCodec(  324): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
V/OMXCodec(  324): [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3044799360
V/OMXCodec(  324): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
V/OMXCodec(  324): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
V/OMXCodec(  324): [OMX.google.vorbis.decoder] initOutputFormat()
V/OMXCodec(  324): [OMX.google.vorbis.decoder] reconfig handling, formatHasNotablyChanged
V/OMXCodec(  324): [OMX.google.vorbis.decoder] enablePortAsync portIndex=1
V/OMXCodec(  324): [OMX.google.vorbis.decoder] sending OMX_CommandPortEnable(1)
V/OMXCodec(  324): allocateBuffersOnPort portIndex=1
V/OMXCodec(  324): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
V/OMXCodec(  324): [OMX.google.vorbis.decoder] allocated buffer 0xb57bf1f0 on output port
V/OMXCodec(  324): [OMX.google.vorbis.decoder] allocated buffer 0xb57bf150 on output port
V/OMXCodec(  324): [OMX.google.vorbis.decoder] allocated buffer 0xb54f7fb0 on output port
V/OMXCodec(  324): [OMX.google.vorbis.decoder] allocated buffer 0xb1439100 on output port
V/OMXCodec(  324): [OMX.google.vorbis.decoder] PORT_ENABLED(1)
V/OMXCodec(  324): [OMX.google.vorbis.decoder] setState mState=7 , newState=4
V/AudioCache(  324): open(48000, 2, 0x0, 1, 4)
V/AudioCache(  324): notify(0xb143abc0, 6, 0, 0)
V/AudioCache(  324): ignored
V/MediaPlayerService(  324): wait for playback complete
D/SiteAdvisor( 6429): com.mcafee.android.b.a.a(Unknown Source): 'Backg,roundWoker-TemporaryThread-1': Browser component :com.amazon.cloud9/com.amazon.cloud9.BrowserActivity not supported
D/SiteAdvisor( 6429): com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.sec.android.app.sbrowser/com.sec.android.app.sbrowser.SBrowserMainActivity not supported
D/SiteAdvisor( 6429): com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.sec.android.app.sbrowser/com.sec.android.app.sbrowser.SBrowserMainActivity not supported
D/SiteAdvisor( 6429): com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.htc.sense.browser/com.htc.sense.browser.BrowserActivity not supported
I/SiteAdvisor( 6429): com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Loading supported browsers: com.android.browser/com.android.browser.BrowserActivity; com.android.chrome/com.android.chrome.Main; 
V/AudioCache(  324): write(0xb17c3000, 4096)
V/AudioCache(  324): memcpy(0xac602000, 0xb17c3000, 4096)
V/AudioCache(  324): write(0xb17c3000, 4096)
V/AudioCache(  324): memcpy(0xac603000, 0xb17c3000, 4096)
V/AudioCache(  324): write(0xb17c3000, 4096)
V/AudioCache(  324): memcpy(0xac604000, 0xb17c3000, 4096)
D/SiteAdvisor( 6429): com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Here is the storedCurrentAppVersion: 3.1.2.1430
V/AudioCache(  324): write(0xb17c3000, 4096)
V/AudioCache(  324): memcpy(0xac605000, 0xb17c3000, 4096)
D/SiteAdvisor( 6429): com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Here about to commit perfs
V/AudioCache(  324): write(0xb17c3000, 4096)
V/AudioCache(  324): memcpy(0xac606000, 0xb17c3000, 4096)
V/AudioCache(  324): write(0xb17c3000, 4096)
V/AudioCache(  324): memcpy(0xac607000, 0xb17c3000, 4096)
V/AudioCache(  324): write(0xb17c3000, 4096)
V/AudioCache(  324): memcpy(0xac608000, 0xb17c3000, 4096)
V/AudioCache(  324): write(0xb17c3000, 4096)
V/AudioCache(  324): memcpy(0xac609000, 0xb17c3000, 4096)
V/AudioCache(  324): write(0xb17c3000, 4096)
V/AudioCache(  324): memcpy(0xac60a000, 0xb17c3000, 4096)
V/AudioCache(  324): write(0xb17c3000, 4096)
V/AudioCache(  324): memcpy(0xac60b000, 0xb17c3000, 4096)
V/AudioCache(  324): write(0xb17c3000, 4096)
V/AudioCache(  324): memcpy(0xac60c000, 0xb17c3000, 4096)
V/AudioCache(  324): write(0xb17c3000, 4096)
V/AudioCache(  324): memcpy(0xac60d000, 0xb17c3000, 4096)
V/AudioCache(  324): write(0xb17c3000, 4096)
V/AudioCache(  324): memcpy(0xac60e000, 0xb17c3000, 4096)
V/AudioCache(  324): write(0xb17c3000, 4096)
V/AudioCache(  324): memcpy(0xac60f000, 0xb17c3000, 4096)
V/AudioCache(  324): write(0xb17c3000, 4096)
V/AudioCache(  324): memcpy(0xac610000, 0xb17c3000, 4096)
V/AudioCache(  324): write(0xb17c3000, 4096)
V/AudioCache(  324): memcpy(0xac611000, 0xb17c3000, 4096)
V/AudioCache(  324): write(0xb17c3000, 4096)
V/AudioCache(  324): memcpy(0xac612000, 0xb17c3000, 4096)
V/AudioCache(  324): write(0xb17c3000, 4096)
V/AudioCache(  324): memcpy(0xac613000, 0xb17c3000, 4096)
V/AudioCache(  324): write(0xb17c3000, 4096)
V/AudioCache(  324): memcpy(0xac614000, 0xb17c3000, 4096)
V/AudioCache(  324): write(0xb17c3000, 4096)
V/AudioCache(  324): memcpy(0xac615000, 0xb17c3000, 4096)
V/AudioCache(  324): write(0xb17c3000, 4096)
V/AudioCache(  324): memcpy(0xac616000, 0xb17c3000, 4096)
V/AudioCache(  324): write(0xb17c3000, 4096)
V/AudioCache(  324): memcpy(0xac617000, 0xb17c3000, 4096)
V/AudioCache(  324): write(0xb17c3000, 4096)
V/AudioCache(  324): memcpy(0xac618000, 0xb17c3000, 4096)
V/AudioCache(  324): write(0xb17c3000, 4096)
V/AudioCache(  324): memcpy(0xac619000, 0xb17c3000, 4096)
V/AudioCache(  324): write(0xb17c3000, 4096)
V/AudioCache(  324): memcpy(0xac61a000, 0xb17c3000, 4096)
V/AudioCache(  324): write(0xb17c3000, 4096)
V/AudioCache(  324): memcpy(0xac61b000, 0xb17c3000, 4096)
V/AudioCache(  324): write(0xb17c3000, 4096)
V/AudioCache(  324): memcpy(0xac61c000, 0xb17c3000, 4096)
V/AudioCache(  324): write(0xb17c3000, 4096)
V/AudioCache(  324): memcpy(0xac61d000, 0xb17c3000, 4096)
V/AudioCache(  324): write(0xb17c3000, 4096)
V/AudioCache(  324): memcpy(0xac61e000, 0xb17c3000, 4096)
V/AudioCache(  324): write(0xb17c3000, 4096)
V/AudioCache(  324): memcpy(0xac61f000, 0xb17c3000, 4096)
V/AudioCache(  324): write(0xb17c3000, 4096)
V/AudioCache(  324): memcpy(0xac620000, 0xb17c3000, 4096)
V/AudioCache(  324): write(0xb17c3000, 4096)
V/AudioCache(  324): memcpy(0xac621000, 0xb17c3000, 4096)
V/AudioCache(  324): write(0xb17c3000, 4096)
V/AudioCache(  324): memcpy(0xac622000, 0xb17c3000, 4096)
V/AudioCache(  324): write(0xb17c3000, 4096)
V/AudioCache(  324): memcpy(0xac623000, 0xb17c3000, 4096)
V/AudioCache(  324): write(0xb17c3000, 4096)
V/AudioCache(  324): memcpy(0xac624000, 0xb17c3000, 4096)
V/AudioCache(  324): write(0xb17c3000, 4096)
V/AudioCache(  324): memcpy(0xac625000, 0xb17c3000, 4096)
V/AudioCache(  324): write(0xb17c3000, 4096)
V/AudioCache(  324): memcpy(0xac626000, 0xb17c3000, 4096)
V/AudioCache(  324): write(0xb17c3000, 4096)
V/AudioCache(  324): memcpy(0xac627000, 0xb17c3000, 4096)
V/AudioCache(  324): write(0xb17c3000, 4096)
V/AudioCache(  324): memcpy(0xac628000, 0xb17c3000, 4096)
V/AudioCache(  324): write(0xb17c3000, 4096)
V/AudioCache(  324): memcpy(0xac629000, 0xb17c3000, 4096)
V/AudioCache(  324): write(0xb17c3000, 4096)
V/AudioCache(  324): memcpy(0xac62a000, 0xb17c3000, 4096)
,V/AudioCache(  324): write(0xb17c3000, 4096)
V/AudioCache(  324): memcpy(0xac62b000, 0xb17c3000, 4096)
V/AudioCache(  324): write(0xb17c3000, 4096)
V/AudioCache(  324): memcpy(0xac62c000, 0xb17c3000, 4096)
V/AudioCache(  324): write(0xb17c3000, 4096)
V/AudioCache(  324): memcpy(0xac62d000, 0xb17c3000, 4096)
V/AudioCache(  324): write(0xb17c3000, 4096)
V/AudioCache(  324): memcpy(0xac62e000, 0xb17c3000, 4096)
V/AudioCache(  324): write(0xb17c3000, 4096)
V/AudioCache(  324): memcpy(0xac62f000, 0xb17c3000, 4096)
V/AudioCache(  324): write(0xb17c3000, 4096)
V/AudioCache(  324): memcpy(0xac630000, 0xb17c3000, 4096)
V/AudioCache(  324): write(0xb17c3000, 4096)
V/AudioCache(  324): memcpy(0xac631000, 0xb17c3000, 4096)
V/AudioCache(  324): write(0xb17c3000, 4096)
V/AudioCache(  324): memcpy(0xac632000, 0xb17c3000, 4096)
V/AudioCache(  324): write(0xb17c3000, 4096)
V/AudioCache(  324): memcpy(0xac633000, 0xb17c3000, 4096)
V/OMXCodec(  324): [OMX.google.vorbis.decoder] No more output data.
V/OMXCodec(  324): [OMX.google.vorbis.decoder] There is no more output data available, not calling fillOutputBuffer
V/AwesomePlayer(  324): postAudioEOS() 
V/AudioCache(  324): write(0xb17c3000, 280)
V/AudioCache(  324): memcpy(0xac634000, 0xb17c3000, 280)
V/AwesomePlayer(  324): postStreamDoneEvent_l() -> status:-1011 
V/AwesomePlayer(  324): onStreamDone
V/AwesomePlayer(  324): MEDIA_PLAYBACK_COMPLETE
V/AudioCache(  324): notify(0xb143abc0, 2, 0, 0)
V/AudioCache(  324): playback complete
V/AwesomePlayer(  324): pause_l() 
V/AudioCache(  324): wait - success
V/AudioCache(  324): notify(0xb143abc0, 7, 0, 0)
V/MediaPlayerService(  324): return size 205080, sampleRate=48000, channelCount = 2, format = 1
V/AudioCache(  324): ignored
V/AwesomePlayer(  324): cancelPlayerEvents
D/AudioPlayer(  324): Pause Playback at 1068125
V/AwesomePlayer(  324): reset_l() 
V/AudioCache(  324): notify(0xb143abc0, 8, 0, 0)
V/AudioCache(  324): ignored
V/AwesomePlayer(  324): cancelPlayerEvents
D/AudioPlayer(  324): reset: mPlaying=0 mReachedEOS=1 useOffload=0
V/OMXCodec(  324): [OMX.google.vorbis.decoder] stop mState=4
V/OMXCodec(  324): [OMX.google.vorbis.decoder] stopOmxComponent_l mState=4
V/OMXCodec(  324): [OMX.google.vorbis.decoder] setState mState=4 , newState=5
V/OMXCodec(  324): [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
V/OMXCodec(  324): [OMX.google.vorbis.decoder] onStateChange 2
V/OMXCodec(  324): [OMX.google.vorbis.decoder] Now Idle.
V/OMXCodec(  324): [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=0
V/OMXCodec(  324): [OMX.google.vorbis.decoder] freeing buffer 0xb54f7f60 on port 0
V/OMXCodec(  324): [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=3
V/OMXCodec(  324): [OMX.google.vorbis.decoder] freeing buffer 0xb54f7f10 on port 0
V/OMXCodec(  324): [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=2
V/OMXCodec(  324): [OMX.google.vorbis.decoder] freeing buffer 0xb54f7ec0 on port 0
V/OMXCodec(  324): [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=1
V/OMXCodec(  324): [OMX.google.vorbis.decoder] freeing buffer 0xb54f7e20 on port 0
V/OMXCodec(  324): [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=0
V/OMXCodec(  324): [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
V/OMXCodec(  324): [OMX.google.vorbis.decoder] freeing buffer 0xb1439100 on port 1
V/OMXCodec(  324): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=3
V/OMXCodec(  324): [OMX.google.vorbis.decoder] freeing buffer 0xb54f7fb0 on port 1
V/OMXCodec(  324): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=2
V/OMXCodec(  324): [OMX.google.vorbis.decoder] freeing buffer 0xb57bf150 on port 1
V/OMXCodec(  324): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=1
V/OMXCodec(  324): [OMX.google.vorbis.decoder] freeing buffer 0xb57bf1f0 on port 1
V/OMXCodec(  324): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
V/OMXCodec(  324): [OMX.google.vorbis.decoder] setState mState=5 , newState=6
V/OMXCodec(  324): [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
V/OMXCodec(  324): [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
V/OMXCodec(  324): [OMX.google.vorbis.decoder] onStateChange 1
V/OMXCodec(  324): [OMX.google.vorbis.decoder] Now Loaded.
V/OMXCodec(  324): [OMX.google.vorbis.decoder] setState mState=6 , newState=1
V/OMXCodec(  324): [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
V/OMXCodec(  324): [OMX.google.vorbis.decoder] stopped in state 1
V/OMXCodec(  324): [OMX.google.vorbis.decoder] ~OMXCodec mstate =1
V/OMXCodec(  324): [OMX.google.vorbis.decoder] setState mState=1 , newState=0
D/AudioPlayer(  324): AudioPlayer releasing audio source
D/AudioPlayer(  324): AudioPlayer done releasing audio source
V/AwesomePlayer(  324): reset_l() 
V/AwesomePlayer(  324): cancelPlayerEvents
V/AwesomePlayer(  324): ~AwesomePlayer call
V/AwesomePlayer(  324): reset_l() 
V/AwesomePlayer(  324): cancelPlayerEvents
V/SoundPool( 6490): close(31)
V/SoundPool( 6490): pointer = 0x9fffb000, size = 205080, sampleRate = 48000, numChannels = 2
D/QRemote ( 6490): [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
D/QRemote ( 6490): [RemoteAppWidgetProvider.java:486:onUpdate()] oooooo 140510:RetrieveDevices is not complete. Just waiting
D/QRemote ( 6490): [RemoteAppWidgetProvider.java:499:onUpdate()] oooooo 140514:alarm set after 5000ms:6327
,D/PostponalbeReceiver( 6429): WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'null'.
D/PostponalbeReceiver( 6429): WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'null'.
D/PostponalbeReceiver( 6429): WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'null'.
D/PostponalbeReceiver( 6429): WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'null'.
D/PostponalbeReceiver( 6429): WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'null'.
D/PostponalbeReceiver( 6429): WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'null'.
D/PostponalbeReceiver( 6429): WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'null'.
I/UEI.SmartControl( 5889): Supports setup maps: true
,D/UEI.SmartControl( 5889): QS start statue = true Error code = 0
I/UEI.SmartControl( 5889): QS version = v2.7.10.1_RC1
I/UEI.SmartControl( 5889): QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
I/UEI.SmartControl( 5889): ### init IR Blaster...
D/serial_port( 5889): Configuring serial port
E/UEI.SmartControl( 5889): UEIBLaster setting for 616
I/UEI.SmartControl( 5889): Setting serial record hearder size = 2
I/UEI.SmartControl( 5889): configuring settings for MAXQ616
I/UEI.SmartControl( 5889): Get version...
D/UEI.SmartControl( 5889): serial port data available: 21
,D/UEI.SmartControl( 5889): MAXQ616 A2-X4 software.
I/UEI.SmartControl( 5889): IR Blaster version: 256702256704300002
I/UEI.SmartControl( 5889): QS saving settings...
,D/UEI.SmartControl( 5889): IR Blaster version: 25672567
D/UEI.SmartControl( 5889): serial port data available: 4
,W/ContextImpl( 5889): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
V/BluetoothOppNotification( 6231): new notify threadi!
V/BluetoothOppNotification( 6231): send delay message
,V/BluetoothOppProvider( 6231): starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
I/UEI.SmartControl( 5889): Device manager: loading config....
E/UEI.SmartControl( 5889): Services init done
D/UEI.SmartControl( 5889): QS Service init finished
D/UEI.SmartControl( 5889): QS Service version name: 2.1.91
D/UEI.SmartControl( 5889): QS Service version code: 201091
D/UEI.SmartControl( 5889): Service requested: Control
D/UEI.SmartControl( 5889): ----------- loading internal config...
E/UEI.SmartControl( 5889): Loading SETTINGS...
D/UEI.SmartControl( 5889): Request IControl service: devices are loaded...
,I/QRemote ( 6490): [RemoteControlManager.java:183:onServiceConnected()] oooooo start
I/UEI.SmartControl( 5889): ------ IControl API: 11
D/UEI.SmartControl( 5889): File observer start...
E/UEI.SmartControl( 5889): IR Port is disabled: false
D/UEI.SmartControl( 5889): Starting file observer...
I/UEI.SmartControl( 5889): Registering callback...
D/UEI.SmartControl( 5889): Internal service binding...
I/UEI.SmartControl( 5889): ------ IControl API: 19
I/UEI.SmartControl( 5889): Registering Services Ready callback...
D/UEI.SmartControl( 5889): -- Open brand translation xml: brands_translations_ko
V/BluetoothOppProvider( 6231): created cursor android.database.sqlite.SQLiteCursor@2d4a8e89 on behalf of 
V/BluetoothOppNotification( 6231): mUpdateCompleteNotification = true
V/BluetoothOppProvider( 6231): starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
V/BluetoothOppProvider( 6231): created cursor android.database.sqlite.SQLiteCursor@7229e8e on behalf of 
V/BluetoothOppNotification( 6231): outbound: succ-0  fail-0
V/BluetoothOppNotification( 6231): outbound notification was removed.
V/BluetoothOppProvider( 6231): starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
V/BluetoothOppProvider( 6231): created cursor android.database.sqlite.SQLiteCursor@5e0f6af on behalf of 
V/BluetoothOppNotification( 6231): inbound: succ-0  fail-0
V/BluetoothOppNotification( 6231): inbound notification was removed.
V/BluetoothOppProvider( 6231): starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
V/BluetoothOppProvider( 6231): created cursor android.database.sqlite.SQLiteCursor@64c8abc on behalf of 
,I/UEI.SmartControl( 5889): Notify AllClients services are ready: 0
I/QRemote ( 6490): [RemoteControlManager.java:660:QSSetupIsReady()] oooooo 140517:sdkIsReady callback... get functions. Result:0
D/QRemote ( 6490): [RemoteControlManager.java:388:handleMessage()] oooooo 140510:START_SESSION
D/QRemote ( 6490): [RemoteControlManager.java:394:handleMessage()] oooooo 140510:send retrieve msg
D/QRemote ( 6490): [RemoteControlManager.java:322:handleMessage()] oooooo 140510:handler call retrieveDevices
D/UEI.SmartControl( 5889): -----service ready thread exits
D/QRemote ( 6490): [RemoteControlManager.java:336:retrieveDevices()] oooooo retrieveDevices: start
I/UEI.SmartControl( 5889): ------ IControl API: 8
D/QRemote ( 6490): [RemoteControlManager.java:340:retrieveDevices()] oooooo retrieveDevices: 0
D/QRemote ( 6490): [RemoteControlManager.java:345:retrieveDevices()] oooooo retrieveDevices complete:true
,D/QRemote ( 6490): [RemoteControlManager.java:353:retrieveDevices()] oooooo retrieveDevices: notifyDataSetChanged()
D/QRemote ( 6490): [QRemoteApplication.java:145:onRemoteControlStateChanged()] oooooo onRemoteControlStateChanged called in QRemoteApp
D/QRemote ( 6490): [QRemoteApplication.java:158:onRemoteControlStateChanged()] oooooo Widget count is [1]. send broadcast
D/QRemote ( 6490): [QRemoteApplication.java:160:onRemoteControlStateChanged()] oooooo Widget[0]:3
D/QRemote ( 6490): [QRemoteApplication.java:188:onRemoteControlStateChanged()] oooooo 140526:onRemoteControlStateChanged&sdkIsReady. stop Service
V/QRemote ( 6490): [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
D/QRemote ( 6490): [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
E/QRemote ( 6490): [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
,D/QRemote ( 6490): [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
D/QRemote ( 6490): [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
D/QRemote ( 6490): [RemoteAppWidgetProvider.java:506:onUpdate()] oooooo 140510:RetrieveDevices complete. Start loading
D/QRemote ( 6490): [RemoteAppWidgetProvider.java:508:onUpdate()] oooooo 140510:appWidgetIds[0]:3 loading
D/QRemote ( 6490): [RemoteAppWidgetManager.java:41:startLoading()] oooooo 140518:widgetId[3] loading start at [1454085863378]
D/QRemote ( 6490): [QRemoteService.java:207:onDestroy()] oooooo 140526:onDestroy
I/ActivityManager( 1028): Killing 5728:com.android.defcontainer/u0a4 (adj 15): empty #17
,D/QRemote ( 6490): [RemoteAppWidgetManager.java:239:doInBackground()] oooooo 140407:doinBack arr:0
,W/libprocessgroup( 1028): failed to open /acct/uid_10004/pid_5728/cgroup.procs: No such file or directory
,V/QRemote ( 6490): [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.widget_ui_update
,E/QRemote ( 6490): [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
,D/QRemote ( 6490): [RemoteAppWidgetProvider.java:171:onReceive()] oooooo total:0
D/QRemote ( 6490): [RemoteAppWidgetProvider.java:172:onReceive()] oooooo selected:0
D/QRemote ( 6490): [RemoteAppWidgetProvider.java:173:onReceive()] oooooo arr:[]
D/QRemote ( 6490): [RemoteAppWidgetProvider.java:174:onReceive()] oooooo appWidgetId:3
D/QRemote ( 6490): [RemoteAppWidgetProvider.java:815:updateRemoteViews()] oooooo UpdateRemoteViews3:widgetId:3
D/QRemote ( 6490): [RemoteAppWidgetProvider.java:986:updateRemoteViews()] oooooo updateAppWidget5:widgetId:3]
,I/dhcpcd  ( 6428): wlan0: acknowledged 192.168.1.141 from 192.168.1.1
,I/dhcpcd  ( 6428): wlan0: leased 192.168.1.141 for 86400 seconds
D/dhcpcd  ( 6428): wlan0: adding IP address 192.168.1.141/24
D/dhcpcd  ( 6428): wlan0: adding route to 192.168.1.0/24
,D/dhcpcd  ( 6428): wlan0: adding default route via 192.168.1.1
D/dhcpcd  ( 6428): wlan0: writing lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
E/WifiStateMachine( 1028):  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1028):  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1028):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
D/dhcpcd  ( 6428): getUsingAPMacAddress: c0:ff:d4:d3:aa:48 , return 1
E/WifiStateMachine( 1028):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
D/dhcpcd  ( 6428): write_lease_ext: /data/misc/dhcp/dhcpcd-wlan0-c0:ff:d4:d3:aa:48.lease2
,D/dhcpcd  ( 6428): wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason REBOOT
E/WifiStateMachine( 1028):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1028):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
D/ConnectivityService( 1028): Update of LinkProperties for NetworkAgentInfo [WIFI () - 100]; created=false
D/DhcpStateMachine( 1028): DHCPV4 succeeded on wlan0
,D/LgDhcpStateMachineHelper( 1028): CheckDhcpDirectory [Lease File Count] : 3
V/LgDhcpStateMachineHelper( 1028): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
D/LgDhcpStateMachineHelper( 1028): checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.141
V/LgDhcpStateMachineHelper( 1028): Add DhcpResults: IP address 192.168.1.141/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 86400 seconds
V/DhcpStateMachine( 1028): Current State is mWaitBeforeStartState.
V/LgDhcpStateMachineHelper( 1028): bShouldSendDhcpAction Result: true
E/WifiStateMachine( 1028):  ObtainingIpState CMD_POST_DHCP_ACTION 1 0 OK  v4
E/WifiStateMachine( 1028):  L2ConnectedState CMD_POST_DHCP_ACTION 1 0 OK  v4
D/WifiNative-wlan0( 1028): doBoolean: DRIVER BTCOEXMODE 2
D/LGWifiP2pService( 1028): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1028): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 6292): wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
D/DhcpStateMachine( 1028): DHCP Start/Renew wake lock is released.
D/DhcpStateMachine( 1028): RunningState
D/WifiNative-wlan0( 1028): DRIVER BTCOEXMODE 2: returned true
D/WifiNative-wlan0( 1028): doBoolean: DRIVER SETSUSPENDMODE 1
I/wpa_supplicant( 6292): wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 1
D/WifiNative-wlan0( 1028): DRIVER SETSUSPENDMODE 1: returned true
D/WifiNative-wlan0( 1028): doBoolean: SET ps 1
,D/WifiNative-wlan0( 1028): SET ps 1: returned true
E/WifiStateMachine( 1028):  ObtainingIpState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
E/WifiStateMachine( 1028):  L2ConnectedState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
E/WifiStateMachine( 1028): WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
D/ConnectivityService( 1028): Update of LinkProperties for NetworkAgentInfo [WIFI () - 100]; created=false
D/ConnectivityService( 1028): ignoring duplicate network state non-change
,D/ConnectivityService( 1028): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
D/ConnectivityService( 1028): Adding iface wlan0 to network 100
I/StatusBar.NetworkController( 1446): networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1446): mWifiConnected = false, mWifiLevel = 0
,W/Settings( 1028): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1028): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1028): NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
D/StatusBar.NetworkController( 1446): refreshViews: Data not connected!! Set no data type icon / Roaming
I/StatusBar.NetworkController( 1446): networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1446): mWifiConnected = false, mWifiLevel = 0
,W/Settings( 1028): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1028): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1028): NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
E/WifiStateMachine( 1028): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
D/WifiHS20( 1028): [PASSPOINT] passpointNotification: hs20AP list is checked
D/StatusBar.NetworkController( 1446): refreshViews: Data not connected!! Set no data type icon / Roaming
I/StatusBar.NetworkController( 1446): networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,W/Settings( 1028): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1028): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1028): NETWORK_STATE_CHANGED_ACTION [CONNECTED]
,E/ConnectivityService( 1028): Unexpected mtu value: 0, wlan0
D/ConnectivityService( 1028): Adding Route [fe80::/64 -> :: wlan0] to network 100
D/WifiHS20( 1028): [PASSPOINT] passpointNotification: hs20AP list is checked
D/ConnectivityService( 1028): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 100
V/WfdStateTracker( 1944): handleWifiStateChangedEvent: 1
D/ConnectivityService( 1028): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 100
D/ConnectivityService( 1028): addLocalRoutetoDefaultNetwork
D/ConnectivityService( 1028): defaultNAI is null or Wi-Fi no need to add Loacal route to default network. WiFi netid = 100
D/ConnectivityService( 1028): Setting Dns servers for network 100 to [/192.168.1.1]
W/Settings( 1028): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1028): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1028): NETWORK_STATE_CHANGED_ACTION [CONNECTED]
D/Nat464Xlat( 1028): requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
D/ConnectivityService( 1028): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService( 1028): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 100]
I/StatusBar.NetworkController( 1446): mWifiConnected = true, mWifiLevel = 2
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1028): DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1028): Connected
D/StatusBar.NetworkController( 1446): refreshViews: Data not connected!! Set no data type icon / Roaming
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1028): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1028): Checking http://clients3.google.com/generate_204 on "NG700"
D/ConnectivityService( 1028): rematching NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService( 1028):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService( 1028):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1028):     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
D/ConnectivityService( 1028):   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1028):     satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:true
D/ConnectivityService( 1028): currentScore = 0, newScore = 20
D/ConnectivityService( 1028):    accepting network in place of null
D/ConnectivityService( 1028): sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/WIFI    ( 1028): new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    ( 1028):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/TelephonyNetworkFactory-1( 1850): new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/TelephonyNetworkFactory-1( 1850):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
I/StatusBar.NetworkController( 1446): networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1446): mWifiConnected = true, mWifiLevel = 2
D/StatusBar.NetworkController( 1446): refreshViews: Data not connected!! Set no data type icon / Roaming
D/PostponalbeReceiver( 6429): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,D/ConnectivityService( 1028): Setting tx/rx TCP buffers to 524288,1048576,2097152,262144,524288,1048576
D/libc-netbsd(  319): res_queryN name = clients3.google.com, class = 1, type = 28
E/ConnectivityService( 1028): [lg_data] Adding agent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::c69a:2ff:fe7b:60ac/64,192.168.1.141/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
D/CSLegacyTypeTracker( 1028): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
D/ConnectivityService( 1028): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/LocSvc_java( 1028): Sending msg: 4 arg1:1 arg2:1
D/LocSvc_java( 1028): getAGpsConnectionInfo connType - 4
D/LocSvc_java( 1028): updateNetworkState connTyp: 4 available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java( 1028): ignore wifi update if we are not in OPENING or CLOSING
D/LocSvc_java( 1028): Sending msg: 5 arg1:0 arg2:1
D/libc-netbsd(  319): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  319): res_queryN name = 2.android.pool.ntp.org, class = 1, type = 1
,D/libc-netbsd(  319): res_queryN name = 2.android.pool.ntp.org., class = 1, type = 1
D/DSQN    ( 1028): DNSproblemNotiEnabled is disabled ignore DNS fail CB
D/ConnectivityService( 1028): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/CSLegacyTypeTracker( 1028): [e] list.add(nai) empty : false size: 1
D/ConnectivityService( 1028): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::c69a:2ff:fe7b:60ac/64,192.168.1.141/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
D/ConnectivityService( 1028): validation of new default Network = false
D/ConnectivityService( 1028): Default network via Wi-Fi connected. start DSQN
D/DSQN    ( 1028): enableDataServiceNotify 
D/DSQN    ( 1028): start dsqn bin
,D/libc-netbsd(  319): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  319): res_queryN name = europe.pool.ntp.org, class = 1, type = 1
V/NetworkPolicy( 1028): [LG_RESTRICTED] checkMobilePolicy_type()
D/ConnectivityService( 1028): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService( 1028):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1028):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1028): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityManager.CallbackHandler( 1446): CM callback handler got msg 524290
W/dsqn    ( 6598): type=1400 audit(0.0:163): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
W/dsqn    ( 6598): type=1400 audit(0.0:164): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,D/TelephonyIcons( 1446): null signal icon name: drawable/stat_sys_signal_null
D/StatusBar.NetworkController( 1446): refreshViews: Data not connected!! Set no data type icon / Roaming
D/StatusBar.NetworkController( 1446): refreshViews: Data not connected!! Set no data type icon / Roaming
D/libc-netbsd(  319): res_queryN name = clients3.google.com, class = 1, type = 1
E/DSQN    ( 6598): DSQN ssw
,V/WiFiOffLoadBroadcast( 6269): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/libc-netbsd(  319): res_queryN name = clients3.google.com succeed
,D/WiFiOffLoadBroadcast( 6269): MCCMNC not supported: null
D/QRemote ( 6490): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6490): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 6490): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,D/PostponalbeReceiver( 6429): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
D/LGDataListener(  319): argv[0]=dsqncommand
D/LGDataListener(  319): argv[1]=wlan0
,D/LGDataListener(  319): argv[2]=1
D/LGDataListener(  319): notifyDSQN DSQN STARTMONITOR wlan0 1
D/DSQN    ( 1028): DSQM DsqnNotification wlan0  1
,D/DSQN    ( 1028): start to monitor internet connection
V/WiFiOffLoadBroadcast( 6269): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 6269): MCCMNC not supported: null
D/QRemote ( 6490): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6490): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 6490): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
D/PostponalbeReceiver( 6429): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
I/PCSuite ( 6332): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1028): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Fri, 29 Jan 2016 16:44:24 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1454085864343], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1454085864322]}
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1028): Don't send network conditions - lacking user consent.
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1028): Validated
D/ConnectivityService( 1028): Validated NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService( 1028): rematching NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService( 1028):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService( 1028):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1028):     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
D/ConnectivityService( 1028): Network NetworkAgentInfo [WIFI () - 100] was already satisfying request 1. No change.
D/ConnectivityService( 1028): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService( 1028):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1028):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1028): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1028): sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1028): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
D/WIFI    ( 1028): new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    ( 1028):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/TelephonyNetworkFactory-1( 1850): new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityManager.CallbackHandler( 1446): CM callback handler got msg 524290
D/TelephonyNetworkFactory-1( 1850):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
D/PCSuite ( 6332): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
,V/WiFiOffLoadBroadcast( 6269): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 6269): MCCMNC not supported: null
D/QRemote ( 6490): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6490): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,D/QRemote ( 6490): [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
D/TelephonyIcons( 1446): null signal icon name: drawable/stat_sys_signal_null
I/QRemote ( 6490): [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
I/QRemote ( 6490): [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
D/StatusBar.NetworkController( 1446): refreshViews: Data not connected!! Set no data type icon / Roaming
D/StatusBar.NetworkController( 1446): refreshViews: Data not connected!! Set no data type icon / Roaming
D/PostponalbeReceiver( 6429): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,I/PCSuite ( 6332): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
,D/PCSuite ( 6332): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 6269): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 6269): MCCMNC not supported: null
,D/QRemote ( 6490): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6490): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
D/libc-netbsd(  319): res_queryN name = europe.pool.ntp.org succeed
D/QRemote ( 6490): [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
I/QRemote ( 6490): [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
I/QRemote ( 6490): [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
E/WifiStateMachine( 1028):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1908048880] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1028):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-1908048879] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1028): doString: [SIGNAL_POLL]
D/StatusBar.NetworkController( 1446): refreshViews: Data not connected!! Set no data type icon / Roaming
I/jxcore-log( 6150): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMultiplex.js
I/jxcore-log( 6150): 
,I/jxcore-log( 6150): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
I/jxcore-log( 6150): 
,I/jxcore-log( 6150): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
I/jxcore-log( 6150): 
I/jxcore-log( 6150): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliCryptoManager.js
I/jxcore-log( 6150): 
,I/jxcore-log( 6150): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliEmitter.js
I/jxcore-log( 6150): 
,I/jxcore-log( 6150): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNativeLayer.js
I/jxcore-log( 6150): 
,I/jxcore-log( 6150): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationManager.js
I/jxcore-log( 6150): 
I/jxcore-log( 6150): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
I/jxcore-log( 6150): 
V/WifiInternetCheck( 1028): Single check msg out of sync, ignoring.
,D/ConnectivityService( 1028): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering( 1028): MasterInitialState.processMessage what=3
D/GpsLocationProvider( 1028): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
D/libc-netbsd(  319): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  319): res_queryN name = 2.android.pool.ntp.org, class = 1, type = 1
D/PostponalbeReceiver( 6429): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
,W/ContextImpl( 6429): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
,I/NetworkMonitor( 5212): type=WIFI subType= reason=null isConnected=true
,D/libc-netbsd(  319): res_queryN name = 2.android.pool.ntp.org succeed
V/GLSActivity( 2109): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/AlarmManagerService( 1028): Setting time of day to sec=1454085867
W/AlarmManagerService( 1028): Unable to set rtc to 1454085867: Invalid argument
I/ActivityManager( 1028): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=6647 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,I/SecureClockService( 1944): Intent.ACTION_TIME_CHANGED 
,D/LIA_Informant_Tips_DateChangeManager( 2700): onReceive() : ACTION_TIME_CHANGED
I/LIA_Informant_Tips_LogTracer( 2700): [Log Tracer - Schedule Transition] Time Change Event Received : 2016-01-29 17:44:27...... Request
I/LIA_Informant_Tips_LogTracer( 2700): [Log Tracer - Schedule Transition] UserGuide, DATE_UPDATE : working count : 2, total count : 159, new day : false...... Request
D/LIA_Informant_Tips_DateChangeManager( 2700): DateInfo : SmartTips Total Working Day Count = 159
D/LIA_Informant_Tips_DateChangeManager( 2700): DateInfo : UserGuide Working Duration Count = 2
D/LIA_Informant_Tips_DateChangeManager( 2700): DateInfo : Last Date Check Time = 2016-01-29 17:44:27
I/[SystemUI]Clock( 1446): onReceive = android.intent.action.TIME_SET
I/LgeClockWidgetControlView( 1446): time changed, timezoneChanged : false
W/ActivityManager( 1028): getTasks: caller 10029 is using old GET_TASKS but privileged; allowing
I/[LGHome]LGDateChangeReceiver( 2065): [LGDateChangeReceiver.java:78:updateCalendarShortcut()]date=29 currentDate=-1 dayofweek=6 currentDayOfWeek=-1
D/KeyguardUpdateMonitor( 1446): handleTimeUpdate
,I/[LGHome]LGCalendarIcon( 2065): [LGCalendarIcon.java:214:makeCalendarBitmap()]Locale = en_US dayofweek= Fri date= 29
I/[LGHome]LGCalendarIcon( 2065): [LGCalendarIcon.java:214:makeCalendarBitmap()]Locale = en_US dayofweek= Fri date= 29
I/[LGHome]Launcher( 2065): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
E/WifiStateMachine( 1028):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-50 f=2412 sc=60 link=72 tx=6.0, 0.0, 0.0  rx=4.0 bcn=0 [on:0 tx:0 rx:0 period:2853] from screen [on:0 period:-1908046023] gl rssi=-50 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
E/WifiStateMachine( 1028):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-50 f=2412 sc=60 link=72 tx=6.0, 0.0, 0.0  rx=4.0 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-1908046022] gl rssi=-50 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
D/WifiNative-wlan0( 1028): doString: [SIGNAL_POLL]
,I/AppUp4:AppBoxCP( 6647): onCreate
W/AppUp4:DB( 6647):  [AppBoxDatabaseHelper] construct
I/AppUp4:DB( 6647):  setFingerPrint start
I/AppUp4:DB( 6647):  newfinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys SDK version = 21
I/AppUp4:DB( 6647):  beforefinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys
I/AppUp4:DB( 6647):  SDK version = 21
I/AppUp4:DB( 6647):  beforefinger == newfinger no write in DB
,I/ActivityManager( 1028): Start proc com.google.android.apps.books for service com.google.android.apps.books/.service.SyncService: pid=6666 uid=10054 gids={50054, 9997, 3003, 1028, 1015} abi=armeabi-v7a
D/AppUp4:AppBoxApplication( 6647): AppBoxApplication onCreate()
I/NetworkStateForAutoUpdateMonitor( 6647): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 6647): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 6647): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 6647): [onReceive] request level :IDLE....
,I/AppUp4:CustModeStarterReceiver( 6647): onReceive
D/[Concierge]Service( 2589): onStartCommand(). Type : 9
I/art     (  349): Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 348us total 15.685ms
I/art     (  349): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 272us total 12.998ms
,I/GoogleURLConnFactory( 2109): Using platform SSLCertificateSocketFactory
I/VacuumService( 2109): Vacuum at: now=1454085867388 tag=VacuumService
I/art     (  349): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 255us total 12.111ms
,D/LgDataFeature( 6647): LgDataFeature() Constructor: none
W/Uploader( 2109): No account for auth token provided
D/LgDataFeature( 6647): LgDataFeature() Constructor Done, null
,D/AppUp4:CustFacade( 6647): Context : android.app.ReceiverRestrictedContext@3af0c182
D/AppUp4:CustFacade( 6647): isCustomizationCompleted : false
D/AppUp4:CustFacade( 6647): isPhone : true
I/ActivityManager( 1028): Start proc com.android.gallery3d for service com.android.gallery3d/com.lge.gallery.picasa.PicasaService: pid=6687 uid=10027 gids={50027, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
D/AppUp4:CustModeStarterReceiver( 6647): begin check event
I/AppUp4:CustModeStarterReceiver( 6647): Event For GoodConnectivity
D/AppUp4:CustModeStarterReceiver( 6647): runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
D/AppUp4:CustModeStarterReceiver( 6647): call method handleAsyncCustNotification.
D/AppUp4:CustModeStarterReceiver( 6647): handleAsync isTriedOnce : false
E/AppUp4:CustModeStarterReceiver( 6647): handleAsyncCustNotification do not startCustService
,I/ActivityManager( 1028): Killing 5549:com.lge.lockscreensettings/u0a80 (adj 15): empty #17
,D/LGDMClient( 3979): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 3979): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
W/ContextImpl( 3979): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,W/libprocessgroup( 1028): failed to open /acct/uid_10080/pid_5549/cgroup.procs: No such file or directory
,I/ReaderUtils( 6666): PortraitW 1440 LandscapeW 2392 SmallestSize 1340 LargestSize 2392 textZoom 4.4999995 isTablet false Memory 256
,W/ContextImpl( 3979): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,D/libc-netbsd(  319): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  319): res_queryN name = play.googleapis.com, class = 1, type = 1
,V/DownloadManager( 3288): Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 3979): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=3, isUserType=1
I/LGDMClient( 3979): [DmServiceProcessor.java] [processNetworkChanged()] : [91] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
,W/ResourcesManager( 6687): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6687): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 6687): Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
W/ResourcesManager( 6687): Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
D/LGDMClient( 3979): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 3979): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
,I/ActivityManager( 1028): Start proc com.android.chrome for service com.android.chrome/com.google.android.apps.chrome.sync.ChromeBrowserSyncAdapterService: pid=6712 uid=10057 gids={50057, 9997, 3003, 1028, 1015} abi=armeabi-v7a
D/libc-netbsd(  319): res_queryN name = play.googleapis.com succeed
D/GpsLocationProvider( 1028): updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
V/DownloadManager( 3288): DownloadService onCreate
W/ContextImpl( 3979): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:141 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:180 android.app.IntentService$ServiceHandler.handleMessage:65 
I/DownloadManager( 3288): in removeSpuriousFiles
V/DownloadManager( 3288): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 3288): created cursor android.database.sqlite.SQLiteCursor@33d7cf30 on behalf of 3288
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
I/DownloadManager( 3288): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGBackup_4.51.57_COM_COM_8275_2_20151201044833536_RELG-D855_21.apk
I/DownloadManager( 3288): in trimDatabase
V/DownloadManager( 3288): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
V/DownloadManager( 3288): created cursor android.database.sqlite.SQLiteCursor@32407a9 on behalf of 3288
I/ActivityManager( 1028): Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=6734 uid=10023 gids={50023, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,V/DownloadManager( 3288): DownloadService onStartCommand
E/LGDMClient( 3979): [DmNotiService.java] [onCreate()] : [148] : DmNotiService.onCreate()
D/LGDMClient( 3979): [DmNotiService.java] [onStartCommand()] : [182] : in the new onStartCommand()
,V/DownloadManager( 3288): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
I/AppConfig( 6687): Total System Memory = 2995761152
D/LGDMClient( 3979): [DmNotiService.java] [handleStart()] : [203] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
V/DownloadManager( 3288): created cursor android.database.sqlite.SQLiteCursor@12a2ae5c on behalf of 3288
V/DownloadManager( 3288): processing inserted download 1
V/DownloadManager( 3288): processing inserted download 4
V/DownloadManager( 3288): processing inserted download 7
V/DownloadManager( 3288): processing inserted download 8
V/DownloadManager( 3288): processing inserted download 9
V/DownloadManager( 3288): processing inserted download 10
V/DownloadManager( 3288): processing inserted download 16
V/DownloadManager( 3288): processing inserted download 17
V/DownloadManager( 3288): processing inserted download 18
V/DownloadManager( 3288): processing inserted download 21
V/DownloadManager( 3288): processing inserted download 22
D/SystemHelper( 6687): region [EU], country [EU], operator [OPEN], sub-operator []
,E/GpsLocationProvider( 1028): No APN found to select.
,V/DownloadManager( 3288): DownloadService onDestroy
,W/GAV2    ( 6666): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,W/ResourcesManager( 6734): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6734): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 6734): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
W/ResourcesManager( 6734): Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
I/BooksApp( 6666): Created application version: 3.2.35 (30235)
,W/DriveInitializer( 2328): Background init thread started
,E/VoldCmdListener(  278): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  278): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.gms/files/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 2328): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.gms/files
W/Uploader( 2109): No account for auth token provided
,I/LGEmail ( 6734): [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,D/LGEmail ( 6734): user build Type == true (at Util.java isUserModeBuildType 3507)[v:6.41.18]
,W/DriveInitializer( 2328): Background init thread ended
I/Thermal-Lib( 3101): Thermal-Lib-Client: Client request sent
I/ThermalEngine(  339): Thermal-Server: Thermal received msg from  override
,W/Uploader( 2109): No account for auth token provided
W/ResourceType( 6734): No package identifier when getting value for resource number 0x00000000
I/BooksSync( 6666): Starting books sync
,D/DelayedSyncController( 6712): Delaying sync.
D/LgDataFeature( 6734): LgDataFeature() Constructor: none
D/LgDataFeature( 6734): LgDataFeature() Constructor Done, null
,I/ActivityManager( 1028): Killing 5870:com.google.android.apps.docs/u0a61 (adj 15): empty #17
W/libprocessgroup( 1028): failed to open /acct/uid_10061/pid_5870/cgroup.procs: No such file or directory
,W/Uploader( 2109):  no longer exists, so no auth token.
I/ActivityManager( 1028): Killing 5583:com.google.android.apps.plus/u0a97 (adj 15): empty #17
,W/libprocessgroup( 1028): failed to open /acct/uid_10097/pid_5583/cgroup.procs: No such file or directory
,E/Auth.Api.Credentials( 2328): [CredentialSyncAdapter] Unknown sync event.
,D/eas_req ( 6734): ---addEventToQueue() easCode=2, requestId=0 (at EasSupport.java addEventToQueue 69)
,I/HubEmail( 6734): JNI_OnLoad()
I/HubEmail( 6734): -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 6734): registerNatives()
I/HubEmail( 6734): -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 6734): registerNativeMethods()
I/HubEmail( 6734): -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
W/art     ( 6734): JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
,W/Settings( 6734): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/libc-netbsd(  319): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  319): res_queryN name = www.google.com, class = 1, type = 1
W/Settings( 6734): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/LgeMiscReceiver( 3211): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 3211): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 3211): networkInfo.isConnected() = true
D/PhoneState( 3211): setPdpRejectCasuse : false
,D/libc-netbsd(  319): default dns: query_ipv6=0, query_ipv4=1
,D/libc-netbsd(  319): res_queryN name = static-avc.lglime.com, class = 1, type = 1
D/libc-netbsd(  319): res_queryN name = www.google.com succeed
D/libc-netbsd(  319): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  319): res_queryN name = clients3.google.com, class = 1, type = 1
D/libc-netbsd(  319): res_queryN name = clients3.google.com succeed
,D/UEI.SmartControl( 5889): Internal timer expired: 4
D/UEI.SmartControl( 5889): unbind internal service
,I/ActivityManager( 1028): Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=6794 uid=10062 gids={50062, 9997, 4002, 3003, 1028} abi=armeabi-v7a
V/WifiInternetCheck( 1028): isHttpConnectionAvailable - We got a valid response : 204
,I/art     ( 1028): Explicit concurrent mark sweep GC freed 49994(2MB) AllocSpace objects, 4(64KB) LOS objects, 33% free, 44MB/66MB, paused 1.885ms total 100.966ms
,D/libc-netbsd(  319): res_queryN name = static-avc.lglime.com succeed
D/DrmBroadcastReceiver( 6794): Receive CONNECTIVITY_ACTION
D/DrmBroadcastReceiver( 6794): 1  network is available. Sync DRM Time with NTP
,V/DrmService( 6794): Service onCreate
D/DrmService( 6794): Received new request = 2
I/DrmSntpClient( 6794): Start Sync process
D/DrmSntpClient( 6794): Server : 0
,D/libc-netbsd(  319): default dns: query_ipv6=0, query_ipv4=1
,D/libc-netbsd(  319): res_queryN name = pool.ntp.org, class = 1, type = 1
I/ActivityManager( 1028): Start proc com.lge.sizechangable.weather for broadcast com.lge.sizechangable.weather/.layout.WeatherWidget: pid=6814 uid=10085 gids={50085, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/BooksSync( 6666): started syncMyEbooks
,I/art     ( 6814): Almond Protected OAT
,D/serial_port( 5889): close(fd = 24)
I/UEI.SmartControl( 5889): Serial port is closed.
D/WeatherApplication( 6814): removeAccount
D/WeatherApplication( 6814): Account.length = 0
E/WeatherApplication( 6814): OPERATOR:OPEN
,V/GLSActivity( 2109): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/WeatherAncestor( 6814): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 17:44:28
D/Weather.Utils( 6814): 2 : the weather widgets(using time tick) are gone.
D/Weather.Utils( 6814): 2 : All the weather widget is gone.
D/UpdateThreadPoolManager( 6814): 2 : This is isUpdating : false
D/WeatherAncestor( 6814): connectivity changed - connection : true
D/WeatherService( 6814): 2 : isServiceAlived():false forecastCache:null
D/ForecastDataCache( 6814): 2 : lastUpdatedTime: 1430558561343
D/ForecastDataCache( 6814): 2 : currentPackageVersion: 4.40.4
,D/ForecastDataCache( 6814): 2 : Cache is not up-to-date, count: 0
,D/Weather_cast( 6814): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherAncestor( 6814): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 17:44:28
I/art     ( 2109): Explicit concurrent mark sweep GC freed 24526(1310KB) AllocSpace objects, 1(39KB) LOS objects, 51% free, 30MB/62MB, paused 1.095ms total 29.502ms
I/ActivityManager( 1028): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=6837 uid=10093 gids={50093, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager( 1028): Killing 5916:com.lge.eula/1000 (adj 15): empty #17
,V/FormManager( 6300): There are no updated forms. The schedule will be deleted.
,V/FormManager( 6300): Alarm would be updated, because LastCheckTime has been updated.
D/libc-netbsd(  319): res_queryN name = pool.ntp.org succeed
I/LGDrmClient( 6794): _DRM_ServiceGet() : Bind lgdrm service
,V/ILGDrmService(  332): eDRM_SetDRMTime +++
I/LGDRM   (  332): [DRM] SET TIME : YR=2016, MON=1, DAY=29
I/LGDRM   (  332): [DRM] SET TIME : HR=16, MIN=44, SEC=27
V/ILGDrmService(  332): eDRM_SetDRMTime ---
I/DrmSntpClient( 6794): Synched
D/DrmService( 6794): Completed !! request = 2
D/DrmService( 6794): Request count = 0
W/libprocessgroup( 1028): failed to open /acct/uid_1000/pid_5916/cgroup.procs: No such file or directory
,V/DrmService( 6794): Service onDestroy
I/ActivityManager( 1028): Killing 5361:com.google.android.gms.wearable/u0a5 (adj 15): empty #17
W/libprocessgroup( 1028): failed to open /acct/uid_10005/pid_5361/cgroup.procs: No such file or directory
,I/ActivityManager( 1028): Killing 6022:com.google.android.talk/u0a72 (adj 15): empty #17
I/GLSUser ( 2109): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2109): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2109): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2109): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,E/VoldCmdListener(  278): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  278): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6837): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
E/VoldCmdListener(  278): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  278): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6837): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
E/VoldCmdListener(  278): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  278): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6837): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
E/VoldCmdListener(  278): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  278): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6837): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
,W/libprocessgroup( 1028): failed to open /acct/uid_10072/pid_6022/cgroup.procs: No such file or directory
,V/GLSActivity( 2109): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1028): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,D/ZenLog  ( 1028): intercepted: 0|com.google.android.gms|1|null|10005,none
V/NotificationService( 1028): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1028): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1028): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1028): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
W/GLSActivity( 2109): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2109): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2109): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2109): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2109): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2109): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2109): 	at android.os.Binder.execTransact(Binder.java:446)
,W/ResourcesManager( 1446): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 1446): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
E/BooksAccountManager( 6666): Authentication error
E/BooksAccountManager( 6666): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6666): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6666): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6666): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6666): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6666): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6666): null auth token
W/ResourcesManager( 1396): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 1396): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
D/LgeQuickCoverNLService( 1396): onNotificationPosted
D/SmartCoverUpdateMonitor( 1396): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1396): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1396): handleNotificationPosted(true)
D/QuickCircle( 1396): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1396): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1396): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1396): post do add job
D/LgeQuickCoverNotificationData( 1396): add : 2
D/LgeQuickCoverNotificationData( 1396): do add job
D/LgeQuickCoverNotificationData( 1396): showAll3
D/LgeQuickCoverNotificationData( 1396): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1396): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1396): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1396): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1396): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1396): isNotificationForCurrentUser : true
D/libc-netbsd(  319): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  319): res_queryN name = www.googleapis.com, class = 1, type = 1
,D/LgeQuickCoverOverlayWindow( 1396): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1396): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1396): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1396): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1396): updateNotificationData: count=3
,D/QuickStatusbarLayout( 1396): Notification difference=198
D/QuickStatusbarLayout( 1396): child = android.widget.LinearLayout{184a5dea V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,V/GLSActivity( 2109): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/libc-netbsd(  319): res_queryN name = www.googleapis.com succeed
,I/GLSUser ( 2109): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.syncadapters.contacts, service: cp
I/GLSUser ( 2109): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> cp without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2109): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2109): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2109): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1028): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
V/NotificationService( 1028): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1028): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1028): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1028): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,D/LgeQuickCoverNLService( 1396): onNotificationPosted
W/GLSActivity( 2109): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2109): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2109): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2109): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2109): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2109): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2109): 	at android.os.Binder.execTransact(Binder.java:446)
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
D/ContactsSyncAdapter( 2109): innerSync failed
D/ContactsSyncAdapter( 2109): com.google.wireless.gdata2.client.AuthenticationException: unable to get auth token android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
D/ContactsSyncAdapter( 2109): 	at com.google.android.syncadapters.contacts.AuthInfo.getAuthToken(AuthInfo.java:45)
D/ContactsSyncAdapter( 2109): 	at com.google.android.syncadapters.contacts.ContactsSyncAdapter.innerPerformSync(ContactsSyncAdapter.java:263)
D/ContactsSyncAdapter( 2109): 	at com.google.android.syncadapters.contacts.ContactsSyncAdapter.onPerformLoggedSync(ContactsSyncAdapter.java:168)
D/ContactsSyncAdapter( 2109): 	at com.google.android.common.LoggingThreadedSyncAdapter.onPerformSync(LoggingThreadedSyncAdapter.java:33)
D/ContactsSyncAdapter( 2109): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
D/ContactsSyncAdapter( 2109): Caused by: android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
D/ContactsSyncAdapter( 2109): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
D/ContactsSyncAdapter( 2109): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
D/ContactsSyncAdapter( 2109): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
D/ContactsSyncAdapter( 2109): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
D/ContactsSyncAdapter( 2109): 	at android.os.Binder.execTransact(Binder.java:446)
,D/SyncManager( 1028): failed sync operation thalitester@gmail.com u0 (com.google), com.android.contacts, LOCAL, currentRunTime 26681, reason: 10019, SyncResult: stats [ numAuthExceptions: 1]
D/SyncManager( 1028): not retrying sync operation because the error is a hard error: thalitester@gmail.com u0 (com.google), com.android.contacts, LOCAL, currentRunTime 293270, reason: 10019
D/QuickStatusbarLayout( 1396): Notification difference=198
D/QuickStatusbarLayout( 1396): child = android.widget.LinearLayout{184a5dea V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,I/WebViewFactory( 6837): Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,I/ActivityManager( 1028): Start proc com.google.android.apps.plus for service com.google.android.apps.plus/.service.EsSyncAdapterService: pid=6884 uid=10097 gids={50097, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/LibraryLoader( 6837): Loading: webviewchromium
I/LibraryLoader( 6837): Time to load native libraries: 5 ms (timestamps 2359-2364)
I/LibraryLoader( 6837): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 6837): Binding Chromium to main looper Looper (main, tid 1) {315764f5}
I/LibraryLoader( 6837): Expected native library version number "",actual native library version number ""
I/chromium( 6837): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 6837): Initializing chromium process, renderers=0
W/art     ( 6837): Attempt to remove local handle scope entry from IRT, ignoring
,W/chromium( 6837): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
I/chromium( 6837): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=38 off=46780 len=2953
,I/chromium( 6837): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:39 off:229536 len:643667
V/AudioPolicyService(  324): registerClient() client 0xb14ce0a0, uid 10093
W/AudioManagerAndroid( 6837): Requires BLUETOOTH permission
W/ResourcesManager( 6884): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
I/Adreno-EGL( 6837): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 6837): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 6837): Build Date: 12/12/14 금
I/Adreno-EGL( 6837): Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
I/Adreno-EGL( 6837): Remote Branch: 
I/Adreno-EGL( 6837): Local Patches: 
I/Adreno-EGL( 6837): Reconstruct Branch: 
,W/ApiaryClient( 6666): Error response from books API: {
W/ApiaryClient( 6666):  "error": {
W/ApiaryClient( 6666):   "errors": [
W/ApiaryClient( 6666):    {
W/ApiaryClient( 6666):     "domain": "global",
W/ApiaryClient( 6666):     "reason": "required",
W/ApiaryClient( 6666):     "message": "Login Required",
W/ApiaryClient( 6666):     "locationType": "header",
W/ApiaryClient( 6666):     "location": "Authorization"
W/ApiaryClient( 6666):    }
W/ApiaryClient( 6666):   ],
W/ApiaryClient( 6666):   "code": 401,
W/ApiaryClient( 6666):   "message": "Login Required"
W/ApiaryClient( 6666):  }
W/ApiaryClient( 6666): }
W/ApiaryClient( 6666): errCount = 1: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6666): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=6417322921033128067&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6666): Headers:
W/ApiaryClient( 6666): accept-encoding: [gzip]
W/ApiaryClient( 6666): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6666): gdata-version: 2
,I/NSApplication( 6837): Starting up...
,I/ActivityManager( 1028): Killing 4865:com.android.vending/u0a44 (adj 15): empty #17
,W/libprocessgroup( 1028): failed to open /acct/uid_10044/pid_4865/cgroup.procs: No such file or directory
,D/libc-netbsd(  319): default dns: query_ipv6=0, query_ipv4=1
,D/libc-netbsd(  319): res_queryN name = mtalk.google.com, class = 1, type = 1
I/iu.SyncManager( 2328): SYNC; picasa accounts
,I/GLSActivity( 2109): [ac] getting account id
I/GLSUser ( 2109): [t] Fetched account id for thalitester@gmail.com : 105256135866144380227
,D/NetworkLogImpl( 2328): Loaded NetworkSpeedPredictor
I/iu.Environment( 2328): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
D/libc-netbsd(  319): res_queryN name = mtalk.google.com succeed
I/iu.UploadsManager( 2328): num queued entries: 0
I/iu.UploadsManager( 2328): num updated entries: 0
I/iu.SyncManager( 2328): NEXT; no task
D/ChimeraCfgMgr( 2328): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/ChimeraCfgMgr( 2328): Loading module com.google.android.gms.kids from APK com.google.android.gms
D/PostponalbeReceiver( 6429): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.intent.action.TIME_SET'.
,I/ActivityManager( 1028): Start proc com.lge.clock for broadcast com.lge.clock/.alarmclock.ALBootInit: pid=6947 uid=10010 gids={50010, 9997, 3003, 1028, 4002} abi=armeabi-v7a
,I/GLSUser ( 2109): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: ac2dm
I/GLSUser ( 2109): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> ac2dm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2109): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2109): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2109): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1028): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1028): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1028): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1028): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1028): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
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
W/Kids    ( 2328): [AccountUtils] Account not ready
W/Kids    ( 2328): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/Kids    ( 2328): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/Kids    ( 2328): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/Kids    ( 2328): 	at com.google.android.gms.auth.p.c(SourceFile:550)
W/Kids    ( 2328): 	at com.google.android.gms.auth.p.b(SourceFile:477)
W/Kids    ( 2328): 	at com.google.android.gms.kids.account.k.d(SourceFile:103)
W/Kids    ( 2328): 	at com.google.android.gms.kids.account.p.a(SourceFile:70)
W/Kids    ( 2328): 	at com.google.android.gms.kids.account.t.a(SourceFile:62)
W/Kids    ( 2328): 	at com.google.android.gms.chimera.f.run(SourceFile:179)
W/Kids    ( 2328): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Kids    ( 2328): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Kids    ( 2328): 	at java.lang.Thread.run(Thread.java:818)
,D/ALBootInit( 6947): ====action==>android.intent.action.TIME_SET
,D/QuickStatusbarLayout( 1396): Notification difference=198
D/QuickStatusbarLayout( 1396): child = android.widget.LinearLayout{184a5dea V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
D/ALBootInit( 6947): Alarm ALBootInit: TIME_SET
D/Alarms  ( 6947): [setNextAlert] start
D/Alarms  ( 6947): [setNextAlert] (1)
,D/Alarms  ( 6947):  minTime  = 0
D/Alarms  ( 6947):  -- OK multi -- 0
E/jeny.kim( 6947): [setNextAlert] setNextAlert  temp_Alarmlink + 
E/jeny.kim( 6947): [setNextAlert]setNextAlert temp_AlarmLinkText + 
I/CommonUtil( 6947): BUILD Country: EU
D/Alarms  ( 6947): broadcastToWidgetProvider : false
D/Alarms  ( 6947): Enter formatDayAndTime(final Context context, long timeInMiliSec)
V/SettingsProvider( 1028): call_put(system:next_alarm_formatted=) for 0 calling package = com.lge.clock
,I/DigitalAppWidgetProvider( 6947): onReceive: android.intent.action.TIME_SET
V/DigitalAppWidgetProvider( 6947): cancelAlarmOnQuarterHour android.app.ReceiverRestrictedContext@20043093
V/DigitalAppWidgetProvider( 6947): startAlarmOnQuarterHour android.app.ReceiverRestrictedContext@20043093
D/QuickCoverProvider( 6947): onReceiver
D/WeatherAncestor( 6814): 2 : onReceive, action: android.intent.action.TIME_SET, Time(hour:min:sec) 17:44:30
D/Weather.Utils( 6814): 2 : the weather widgets(using time tick) are gone.
D/Weather.Utils( 6814): 2 : All the weather widget is gone.
D/UpdateThreadPoolManager( 6814): 2 : This is isUpdating : false
D/WeatherService( 6814): 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@d47a8d0
D/ForecastDataCache( 6814): 2 : lastUpdatedTime: 1430558561343
D/ForecastDataCache( 6814): 2 : currentPackageVersion: 4.40.4
D/ForecastDataCache( 6814): 2 : Cache is up-to-date, count: 0
D/Weather_cast( 6814): 2 : set auto-update time : 1/29 20:44
D/WeatherAncestor( 6814): 2 : onReceive has processed, action: android.intent.action.TIME_SET, Time(hour:min:sec) 17:44:30
,I/art     ( 1028): Explicit concurrent mark sweep GC freed 23971(1063KB) AllocSpace objects, 3(304KB) LOS objects, 33% free, 44MB/66MB, paused 1.180ms total 80.181ms
,I/indal   ( 1396): SmartCoverWidgetContext createApplicationContext
I/indal   ( 1396): SmartCoverWidgetContext createApplicationContext
I/ActivityManager( 1028): Start proc com.qualcomm.timeservice for broadcast com.qualcomm.timeservice/.TimeServiceBroadcastReceiver: pid=6973 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
I/ActivityManager( 1028): Killing 6399:com.lge.settings.easy/1000 (adj 15): empty #17
D/GCM     ( 2109): Connected
,W/libprocessgroup( 1028): failed to open /acct/uid_1000/pid_6399/cgroup.procs: No such file or directory
,D/GCM     ( 2109): Message class com.google.f.a.a.p
,D/DelayedSyncController( 6712): Delaying sync.
,D/TimeService( 6973): Receivedandroid.intent.action.TIME_SET intent. Current Time is 1454085870249
D/        ( 6973): TimeServiceNative: User Time to be set is 1454085870249
D/QC-time-services( 6973): Lib:time_genoff_operation: pargs->base = 2
D/QC-time-services( 6973): Lib:time_genoff_operation: pargs->operation = 0
D/QC-time-services( 6973): Lib:time_genoff_operation: pargs->ts_val = 1454085870249
D/QC-time-services(  381): Daemon: Connection accepted:time_genoff
,D/QC-time-services(  381): Daemon:Received base = 2, unit = 1, operation = 0,value = 1454085870249
,D/QC-time-services(  381): Daemon:genoff_opr: Base = 2, val = 1454085870249, operation = 0
D/QC-time-services(  381): Daemon:rtc_get: Time read from RTC -- MM/DD/YY HH:MM:SS5/8/70 9:56:40
D/QC-time-services(  381): Daemon:Value read from RTC seconds = 13687000000
D/QC-time-services(  381): Daemon:new time 1454085870249 
D/QC-time-services(  381): Daemon: delta 1440398870249 genoff 1440398870249 
D/QC-time-services(  381): Daemon:genoff_persistent_update: Writing genoff = 1440398870249 to memory
D/QC-time-services(  381): Daemon:Opening File: /data/time/ats_2
D/QC-time-services(  381): Daemon:time_persistent_memory_opr:Genoff write operation 
D/QC-time-services( 6973): Lib:time_genoff_operation: Send to server  passed!!
D/QC-time-services(  381): Updating the TOD offset
D/QC-time-services(  381): Daemon:genoff_persistent_update: Writing genoff = 1440398870249 to memory
D/QC-time-services(  381): Daemon:Opening File: /data/time/ats_1
D/QC-time-services(  381): Daemon:time_persistent_memory_opr:Genoff write operation 
E/QC-time-services(  381): Daemon:Update to modem bit set
D/QC-time-services(  381): Daemon:genoff_send_modem: Sending data to MODEM !
D/QC-time-services(  381): Daemon: Base = 2, Value being sent to MODEM = 1124434070249
E/QC-time-services( 6973): Receive Passed == base = 2, unit = 1, operation = 0, result = 0
,E/QC-time-services(  381): Daemon:tod_update_ind_cb: Got Update from modem msg_id 40
E/QC-time-services(  381): Daemon: Time-services: Waiting to acceptconnection
I/ActivityManager( 1028): Start proc com.android.calendar for broadcast com.android.calendar/.widget.CalendarAppWidgetProvider: pid=6993 uid=10013 gids={50013, 9997, 3003, 1028, 1015} abi=armeabi
I/ActivityManager( 1028): Killing 5947:com.lge.bnr/1000 (adj 15): empty #17
,E/WifiStateMachine( 1028):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-52 f=2412 sc=60 link=72 tx=4.5, 0.0, 0.0  rx=3.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1908043017] gl rssi=-52 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1028):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-52 f=2412 sc=60 link=72 tx=4.5, 0.0, 0.0  rx=3.0 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-1908043016] gl rssi=-52 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1028): doString: [SIGNAL_POLL]
W/libprocessgroup( 1028): failed to open /acct/uid_1000/pid_5947/cgroup.procs: No such file or directory
,D/StatusBar.NetworkController( 1446): refreshViews: Data not connected!! Set no data type icon / Roaming
V/GLSActivity( 2109): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ResourcesManager( 6993): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/GLSUser ( 2109): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2109): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2109): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2109): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2109): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1028): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1028): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1028): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1028): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1028): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
W/GLSActivity( 2109): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2109): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2109): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2109): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2109): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2109): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2109): 	at android.os.Binder.execTransact(Binder.java:446)
E/BooksAccountManager( 6666): Authentication error
E/BooksAccountManager( 6666): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6666): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6666): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6666): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6666): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6666): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6666): null auth token
,D/LgeQuickCoverNLService( 1396): onNotificationPosted
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
D/CalendarApplication( 6993): CalendarApplication.onCreate()
,I/GLSUser ( 2109): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.syncadapters.contacts, service: cp
I/GLSUser ( 2109): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> cp without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2109): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2109): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2109): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/QuickStatusbarLayout( 1396): Notification difference=198
,D/QuickStatusbarLayout( 1396): child = android.widget.LinearLayout{184a5dea V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
D/PreferenceKeysParser( 6993): [debug_displayParseInfos] preference keys.size() = 44
D/PreferenceKeysParser( 6993): [debug_displayParseInfos] preference keys = {lg_preferences_tardis_1=com.android.calendar.adaptation.PreferenceKey$KeyData@35fadbf6, lg_preferences_hide_declined=com.android.calendar.adaptation.PreferenceKey$KeyData@118cbf7, lg_preferences_default_reminder=com.android.calendar.adaptation.PreferenceKey$KeyData@3dbe4a64, lg_preferences_month_view_style=com.android.calendar.adaptation.PreferenceKey$KeyData@320854cd, lg_preferences_alerts_ringtone=com.android.calendar.adaptation.PreferenceKey$KeyData@3af0c182, lg_preferences_device_tz=com.android.calendar.adaptation.PreferenceKey$KeyData@20043093, lg_preferences_debug_datesearch=com.android.calendar.adaptation.PreferenceKey$KeyData@d47a8d0, lg_preferences_debug_country=com.android.calendar.adaptation.PreferenceKey$KeyData@1dd270c9, lg_preferences_display_weather_information=com.android.calendar.adaptation.PreferenceKey$KeyData@156d73ce, lg_preferences_alerts_vibrateWhen=com.android.calendar.adaptation.PreferenceKey$KeyData@183742ef, lg_preferences_debug_rtl=com.android.calendar.adaptation.PreferenceKey$KeyData@19c681fc, lg_preferences_alerts_type=com.android.calendar.adaptation.PreferenceKey$KeyData@3a085085, lg_preferrences_country_code=com.android.calendar.adaptation.PreferenceKey$KeyData@9f0feda, lg_preferences_weather_info=com.android.calendar.adaptation.PreferenceKey$KeyData@1fdf1f0b, lg_preference_holiday_calendar_ver=com.android.calendar.adaptation.PreferenceKey$KeyData@1af7c1e8, lg_preferences_show_controls=com.android.calendar.adaptation.PreferenceKey$KeyData@1a027001, lg_preferences_user_select_noti_sound=com.android.calendar.adaptation.PreferenceKey$KeyData@32f02ea6, lg_preference_default_myphonebook=com.android.calendar.adaptation.PreferenceKey$KeyData@18dea0e7, lg_preferences_skip_setup=com.android.calendar.adaptation.PreferenceKey$KeyData@57b1494, lg_preferred_startView=com.android.calendar.adaptation.PreferenceKey$KeyData@14250b3d, lg_preferences_debug_operator=com.android.calendar.adaptation.PreferenceKey$KeyData@b608f32, lg_preferences_exclude_sticker_list=com.android.calendar.adaptation.PreferenceKey$KeyData@366a6483, lg_preferences_writable_calendars_count=com.android.calendar.adaptation.PreferenceKey$KeyData@163ee600, lg_preferred_detailedView=com.android.calendar.adaptation.PreferenceKey$KeyData@6dc1e39, lg_preferences_debug_floating=com.android.calendar.adaptation.PreferenceKey$KeyData@16046c7e, lg_preferences_home_tz=com.android.calendar.adaptation.PreferenceKey$KeyData@2064c5df, lg_preferences_home_tz_enabled=com.android.calendar.adaptation.PreferenceKey$KeyData@28ac622c, lg_preference_received_provider_reminder_broadcast=com.android.calendar.adaptation.PreferenceKey$KeyData@315764f5, lg_preferences_default_cell_height=com.android.calendar.adaptation.PreferenceKey$KeyData@2d76d28a, lg_preferences_notification_type=com.android.calendar.adaptation.PreferenceKey$KeyData@3079e0fb, lg_preferences_show_week_num=com.android.calendar.adaptation.PreferenceKey$KeyData@3937518, lg_preferences_dont_show_again_no_online_account=com.android.calendar.adaptation.PreferenceKey$KeyData@1c065b71, lg_preferences_alerts_popup=com.android.calendar.adaptation.PreferenceKey$KeyData@8f78d56, lg_preferences_week_start_day=com.android.calendar.adaptation.PreferenceKey$KeyData@24fb91d7, lg_preferences_app_version=com.android.calendar.adaptation.PreferenceKey$KeyData@8d6cac4, lg_preferences_alerts=com.android.calendar.adaptation.PreferenceKey$KeyData@cd43dad, lg_preferences_select_aux_calendar=com.android.calendar.adaptation.PreferenceKey$KeyData@1f728e2, lg_preferences_widget_info_calendars=com.android.calendar.adaptation.PreferenceKey$KeyData@257d7473, lg_preferences_alerts_default_ringtone=com.android.calendar.adaptation.PreferenceKey$KeyData@33d7cf30, lg_preference_defaultCalendar=com.android.calendar.adaptation.PreferenceKey$KeyData@32407a9, lg_preferences_alerts_vibratetype=com.android.calendar.adaptation.PreferenceKey$KeyData@2662f12e, lg_preferences_recent_timezones=com.android.calendar.adaptation.PreferenceKey$KeyData@3530e4cf, 
D/GeneralPreferenceUtils( 6993): [migratePrefrenceKeys] Exit: Version(44001600) >= 42001300
D/Config  ( 6993): [init]
,I/Config  ( 6993): LGCalendar ver.4.40.16
I/Config  ( 6993): start check model
I/Config  ( 6993): start check native_ca
V/NotificationService( 1028): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
I/Config  ( 6993): Config Operator=OPEN, Country=EU
D/Config  ( 6993): [setDefaultValuesToPref]
D/Config  ( 6993): [parseProfiles]
V/NotificationService( 1028): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1028): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1028): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1028): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/ProfilesParser( 6993): [debug_displayParseInfos] profile.country = null
D/ProfilesParser( 6993): [debug_displayParseInfos] profile.operator = null
D/LgeQuickCoverNLService( 1396): onNotificationPosted
D/Config  ( 6993): [updateProfiletoCountryInfo]
W/GLSActivity( 2109): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2109): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2109): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2109): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2109): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2109): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2109): 	at android.os.Binder.execTransact(Binder.java:446)
D/ContactsSyncAdapter( 2109): innerSync failed
D/ContactsSyncAdapter( 2109): com.google.wireless.gdata2.client.AuthenticationException: unable to get auth token android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
D/ContactsSyncAdapter( 2109): 	at com.google.android.syncadapters.contacts.AuthInfo.getAuthToken(AuthInfo.java:45)
D/ContactsSyncAdapter( 2109): 	at com.google.android.syncadapters.contacts.ContactsSyncAdapter.innerPerformSync(ContactsSyncAdapter.java:263)
D/ContactsSyncAdapter( 2109): 	at com.google.android.syncadapters.contacts.ContactsSyncAdapter.onPerformLoggedSync(ContactsSyncAdapter.java:168)
D/ContactsSyncAdapter( 2109): 	at com.google.android.common.LoggingThreadedSyncAdapter.onPerformSync(LoggingThreadedSyncAdapter.java:33)
D/ContactsSyncAdapter( 2109): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
D/ContactsSyncAdapter( 2109): Caused by: android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
D/ContactsSyncAdapter( 2109): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
D/ContactsSyncAdapter( 2109): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
D/ContactsSyncAdapter( 2109): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
D/ContactsSyncAdapter( 2109): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
D/ContactsSyncAdapter( 2109): 	at android.os.Binder.execTransact(Binder.java:446)
D/GeneralPreference( 6993): [checkAndMigrateOldPreference]
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
,D/LgeQuickCoverNotificationData( 1396): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1396): updateNotificationData: count=3
E/AgendaWidgetManager( 6993): [updateWidgets] 
D/SyncManager( 1028): failed sync operation thalitester@gmail.com u0 (com.google), com.android.contacts, LOCAL, currentRunTime 293270, reason: 10019, SyncResult: stats [ numAuthExceptions: 1]
I/InitNotificationRingtoneService( 6993): Start InitializeAlertRingtoneService.onHandleIntent
I/AlertUtils( 6993): [setFormatNotificationSound] current noti URI = content://media/internal/audio/media/41
D/QuickStatusbarLayout( 1396): Notification difference=198
D/QuickStatusbarLayout( 1396): child = android.widget.LinearLayout{184a5dea V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,I/AlertUtils( 6993): [getCalendarNotiSoundURIFromCursor] getCount()= 21
,W/ApiaryClient( 6666): Error response from books API: {
W/ApiaryClient( 6666):  "error": {
W/ApiaryClient( 6666):   "errors": [
W/ApiaryClient( 6666):    {
W/ApiaryClient( 6666):     "domain": "global",
W/ApiaryClient( 6666):     "reason": "required",
W/ApiaryClient( 6666):     "message": "Login Required",
W/ApiaryClient( 6666):     "locationType": "header",
W/ApiaryClient( 6666):     "location": "Authorization"
W/ApiaryClient( 6666):    }
W/ApiaryClient( 6666):   ],
W/ApiaryClient( 6666):   "code": 401,
W/ApiaryClient( 6666):   "message": "Login Required"
W/ApiaryClient( 6666):  }
W/ApiaryClient( 6666): }
I/AlertUtils( 6993): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Arpeggio.ogg
W/ApiaryClient( 6666): errCount = 2: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6666): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=6417322921033128067&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6666): Headers:
W/ApiaryClient( 6666): accept-encoding: [gzip]
W/ApiaryClient( 6666): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6666): gdata-version: 2
I/AlertUtils( 6993): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Country_Blues.ogg
I/AlertUtils( 6993): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Crystal.ogg
I/AlertUtils( 6993): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Dewdrop.ogg
I/AlertUtils( 6993): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Ding_Dong.ogg
,I/AlertUtils( 6993): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Echo.ogg
I/AlertUtils( 6993): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Email.ogg
I/AlertUtils( 6993): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Game_Over.ogg
I/AlertUtils( 6993): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Gayageum.ogg
,I/AlertUtils( 6993): [getMediaFilepathFromContentUri] filepath = /system/media/audio/alarms/Afternoon_Walk.ogg
I/AlertUtils( 6993): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Harmonics.ogg
I/AlertUtils( 6993): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Idea.ogg
I/AlertUtils( 6993): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/News.ogg
,I/AlertUtils( 6993): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Pebble.ogg
I/AlertUtils( 6993): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Schedule.ogg
I/AlertUtils( 6993): [getCalendarNotiSoundURIFromCursor] filePath = /system/media/audio/notifications/Schedule.ogg, new URI = content://media/internal/audio/media/41
I/AlertUtils( 6993): set default noti to content://media/internal/audio/media/41
I/InitNotificationRingtoneService( 6993): End InitializeAlertRingtoneService.onHandleIntent
,W/HolidayIntentService( 6993): onHandleIntent
D/MonthWidgetProvider( 6993): [onReceive]
,D/CalendarWidgetProvider( 6993): [onReceive]
D/CalendarWidgetProvider( 6993): [CalendarWidgetProvider] got the intent: Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.android.calendar/.widget.MonthWidgetProvider }
D/HolidayDataLoader( 6993): readJsonAsset : holiday.json
D/CalendarTypeController( 6993): [onUpdateAndInitCalendarTime]
D/WeekWidgetProvider( 6993): [onReceive]
D/CalendarWidgetProvider( 6993): [onReceive]
D/CalendarWidgetProvider( 6993): [CalendarWidgetProvider] got the intent: Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.android.calendar/.widget.WeekWidgetProvider }
D/CalendarTypeController( 6993): [onUpdateAndInitCalendarTime]
I/DigitalAppWidgetProvider( 6947): onReceive: android.intent.action.ALARM_CHANGED
,D/WeatherAncestor( 6814): 2 : onReceive, action: com.lge.sizechangable.weather.action.setweathercast, Time(hour:min:sec) 17:44:30
,D/Weather.Utils( 6814): 2 : the weather widgets(using time tick) are gone.
D/Weather.Utils( 6814): 2 : All the weather widget is gone.
D/UpdateThreadPoolManager( 6814): 2 : This is isUpdating : false
D/Weather_cast( 6814): 2 : Update is Canceled by com.lge.sizechangable.weather.action.alarm
D/WeatherAncestor( 6814): 2 : onReceive has processed, action: com.lge.sizechangable.weather.action.setweathercast, Time(hour:min:sec) 17:44:30
E/HolidayIntentService( 6993): onHandleIntent:holiday data empty
,I/ActivityManager( 1028): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.realtimechat.RequestWriter$NetworkStateReceiver: pid=7019 uid=10072 gids={50072, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
I/ActivityManager( 1028): Killing 6352:com.lge.lifetracker/u0a37 (adj 15): empty #17
,I/art     (  349): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 460us total 23.340ms
,I/art     (  349): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 394us total 19.116ms
,I/art     (  349): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 363us total 18.350ms
,W/libprocessgroup( 1028): failed to open /acct/uid_10037/pid_6352/cgroup.procs: No such file or directory
,W/ResourcesManager( 7019): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,D/LgDataFeature( 7019): LgDataFeature() Constructor: none
D/LgDataFeature( 7019): LgDataFeature() Constructor Done, null
,I/Babel   ( 7019): MmsConfig: mnc/mcc: 0/0
I/Babel   ( 7019): MmsConfig.loadMmsSettings
I/Babel   ( 7019): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D855 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D855-M3-D1.xml
I/Babel   ( 7019): MmsConfig.loadFromDatabase
,E/Babel   ( 7019): canonicalizeMccMnc: invalid mccmnc 
,I/Babel   ( 7019): MmsConfig.loadFromResources
E/Babel   ( 7019): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel   ( 7019): MmsConfig.loadMmsSettings: mUserAgent=LG-D855 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D855-M3-D1.xml
W/Settings( 7019): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/AudioCapabilities( 7019): Unsupported mime audio/evrc
,W/AudioCapabilities( 7019): Unsupported mime audio/qcelp
W/VideoCapabilities( 7019): Unrecognized profile 2130706433 for video/avc
W/AudioCapabilities( 7019): Unsupported mime audio/amr-wb-plus
,W/AudioCapabilities( 7019): Unsupported mime audio/qcelp
W/AudioCapabilities( 7019): Unsupported mime audio/evrc
W/VideoCapabilities( 7019): Unsupported mime video/x-ms-wmv
,W/VideoCapabilities( 7019): Unsupported mime video/divx
W/VideoCapabilities( 7019): Unsupported mime video/divx311
W/VideoCapabilities( 7019): Unsupported mime video/divx4
W/VideoCapabilities( 7019): Unsupported mime video/mp4v-esdp
I/VideoCapabilities( 7019): Unsupported profile 4 for video/mp4v-es
,W/ResourcesManager( 7019): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 7019): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
W/AudioCapabilities( 7019): Unsupported mime audio/eac3
W/AudioCapabilities( 7019): Unsupported mime audio/ac3
W/AudioCapabilities( 7019): Unsupported mime audio/g726
W/AudioCapabilities( 7019): Unsupported mime audio/wma-voice
W/AudioCapabilities( 7019): Unsupported mime audio/x-ms-wma
W/AudioCapabilities( 7019): Unsupported mime audio/adpcm
W/VideoCapabilities( 7019): Unsupported mime video/theora
,W/VideoCapabilities( 7019): Unsupported mime video/mjpg
V/JNIHelp ( 7019): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,W/System  ( 7019): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/system/framework/com.google.android.media.effects.jar", zip file "/system/app/Hangouts/Hangouts.apk"],nativeLibraryDirectories=[/system/app/Hangouts/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 7019): Installed default security provider GmsCore_OpenSSL
,I/GLSUser ( 2109): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.talk, service: oauth2:https://www.googleapis.com/auth/chat https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/hangouts https://www.googleapis.com/auth/identity.plus.page.impersonation https://www.googleapis.com/auth/chat.native
I/GLSUser ( 2109): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/chat https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/hangouts https://www.googleapis.com/auth/identity.plus.page.impersonation https://www.googleapis.com/auth/chat.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2109): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2109): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2109): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
E/Babel   ( 7019): UserRecoverableAuthException.
E/Babel   ( 7019): cfq: BadAuthentication
E/Babel   ( 7019): 	at cfn.a(Unknown Source)
E/Babel   ( 7019): 	at f.a(PG:191)
E/Babel   ( 7019): 	at ava.a(PG:88)
E/Babel   ( 7019): 	at ava.a(PG:128)
E/Babel   ( 7019): 	at bjs.a(PG:255)
E/Babel   ( 7019): 	at bep.a(PG:602)
E/Babel   ( 7019): 	at bep.a(PG:469)
E/Babel   ( 7019): 	at bpo.run(PG:1141)
E/Babel   ( 7019): Error getting auth token
E/Babel   ( 7019): bxl
E/Babel   ( 7019): 	at f.a(PG:201)
E/Babel   ( 7019): 	at ava.a(PG:88)
E/Babel   ( 7019): 	at ava.a(PG:128)
E/Babel   ( 7019): 	at bjs.a(PG:255)
E/Babel   ( 7019): 	at bep.a(PG:602)
E/Babel   ( 7019): 	at bep.a(PG:469)
E/Babel   ( 7019): 	at bpo.run(PG:1141)
I/Babel_RequestWriter( 7019): error sending REQ[fc:8; creat:1454083938630; type:bev-71518384]; took 97 ms (error code == 100)
,E/Babel   ( 7019): Account registration failedRedacted-21
E/Babel   ( 7019): bph: null -- null
E/Babel   ( 7019): 	at ava.a(PG:120)
E/Babel   ( 7019): 	at ava.a(PG:128)
E/Babel   ( 7019): 	at bjs.a(PG:255)
E/Babel   ( 7019): 	at bep.a(PG:602)
E/Babel   ( 7019): 	at bep.a(PG:469)
E/Babel   ( 7019): 	at bpo.run(PG:1141)
I/Babel   ( 7019): Account setup failed with error state:106 account:Redacted-21
I/Babel   ( 7019): Account sign in complete with state 106account: Redacted-21
I/art     ( 7019): Note: end time exceeds epoch: 
,I/GLSUser ( 2109): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.talk, service: oauth2:https://www.googleapis.com/auth/chat https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/hangouts https://www.googleapis.com/auth/identity.plus.page.impersonation https://www.googleapis.com/auth/chat.native
,I/GLSUser ( 2109): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/chat https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/hangouts https://www.googleapis.com/auth/identity.plus.page.impersonation https://www.googleapis.com/auth/chat.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2109): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2109): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2109): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/jxcore-log( 6150): Test app app.js loaded
I/jxcore-log( 6150): 
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6150): setDiscoveryMode: Mode set to BLE
I/jxcore-log( 6150): BLE advertisement is supported
I/jxcore-log( 6150): 
W/ResourcesManager( 2109): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/chromium( 6150): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
V/NotificationService( 1028): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
V/NotificationService( 1028): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1028): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1028): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1028): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,D/LgeQuickCoverNLService( 1396): onNotificationPosted
,E/Babel   ( 7019): Unexpected exception while authenticating.
E/Babel   ( 7019): cfr: User intervention required. Notification has been pushed.
E/Babel   ( 7019): 	at cfn.b(Unknown Source)
E/Babel   ( 7019): 	at cfn.a(Unknown Source)
E/Babel   ( 7019): 	at f.a(PG:188)
E/Babel   ( 7019): 	at ava.b(PG:143)
E/Babel   ( 7019): 	at bnr.run(PG:5415)
E/Babel   ( 7019): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/Babel   ( 7019): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/Babel   ( 7019): 	at java.lang.Thread.run(Thread.java:818)
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
D/QuickStatusbarLayout( 1396): child = android.widget.LinearLayout{184a5dea V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,V/GLSActivity( 2109): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/jxcore-log( 6150): --= Surplus to requirements =--
I/jxcore-log( 6150): 
I/jxcore-log( 6150): ****TEST TOOK:  ms ****
I/jxcore-log( 6150): 
,I/jxcore-log( 6150): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 6150): 
I/GLSUser ( 2109): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2109): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2109): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2109): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2109): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/NotificationService( 1028): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1028): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1028): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1028): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
,D/NotificationServiceEx( 1028): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
W/GLSActivity( 2109): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2109): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2109): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2109): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2109): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2109): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2109): 	at android.os.Binder.execTransact(Binder.java:446)
D/LgeQuickCoverNLService( 1396): onNotificationPosted
E/BooksAccountManager( 6666): Authentication error
E/BooksAccountManager( 6666): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6666): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6666): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6666): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6666): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6666): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6666): null auth token
D/SmartCoverUpdateMonitor( 1396): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1396): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1396): handleNotificationPosted(true)
D/QuickCircle( 1396): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1396): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1396): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1396): post do just update job
D/LgeQuickCoverNotificationData( 1396): showAll3
,D/LgeQuickCoverNotificationData( 1396): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
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
D/QuickStatusbarLayout( 1396): child = android.widget.LinearLayout{184a5dea V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,W/ApiaryClient( 6666): Error response from books API: {
W/ApiaryClient( 6666):  "error": {
W/ApiaryClient( 6666):   "errors": [
W/ApiaryClient( 6666):    {
W/ApiaryClient( 6666):     "domain": "global",
W/ApiaryClient( 6666):     "reason": "required",
W/ApiaryClient( 6666):     "message": "Login Required",
W/ApiaryClient( 6666):     "locationType": "header",
W/ApiaryClient( 6666):     "location": "Authorization"
W/ApiaryClient( 6666):    }
W/ApiaryClient( 6666):   ],
W/ApiaryClient( 6666):   "code": 401,
W/ApiaryClient( 6666):   "message": "Login Required"
W/ApiaryClient( 6666):  }
W/ApiaryClient( 6666): }
,W/ApiaryClient( 6666): errCount = 3: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6666): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=6417322921033128067&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6666): Headers:
W/ApiaryClient( 6666): accept-encoding: [gzip]
W/ApiaryClient( 6666): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6666): gdata-version: 2
W/ProcessCpuTracker( 1028): Skipping unknown process pid 6935
,W/ProcessCpuTracker( 1028): Skipping unknown process pid 6936
W/ProcessCpuTracker( 1028): Skipping unknown process pid 7012
W/ProcessCpuTracker( 1028): Skipping unknown process pid 7014
W/ProcessCpuTracker( 1028): Skipping unknown process pid 7063
D/AndroidRuntime( 7061): 
D/AndroidRuntime( 7061): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime( 7061): CheckJNI is OFF
D/sensors_hal_Time( 1028): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1028): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1028): tsOffsetIs: Apps: 265202365945; DSPS: 8830955; Offset : -4312375500
,D/AndroidRuntime( 7061): Calling main entry com.android.commands.pm.Pm
,I/ActivityManager( 1028): Force stopping com.test.thalitest appid=10311 user=-1: uninstall pkg
I/ActivityManager( 1028): Killing 6150:com.test.thalitest/u0a311 (adj 0): stop com.test.thalitest
I/WindowState( 1028): WIN DEATH: Window{13b9eb03 u0 com.test.thalitest/com.test.thalitest.MainActivity}
D/WifiService( 1028): Client connection lost with reason: 4
,D/InputDispatcher( 1028): Window went away: Window{13b9eb03 u0 com.test.thalitest/com.test.thalitest.MainActivity}
I/ActivityManager( 1028):   Force finishing activity ActivityRecord{3a4da4c u0 com.test.thalitest/.MainActivity t4}
,W/PackageSettings( 1028): Skipping PackageSetting{183464eb com.example.hello/10319} due to missing metadata
,E/GBMv2   (  345): DFP En is all cleared set to be enabled
,W/ActivityManager( 1028): Spurious death for ProcessRecord{2138a4bf 6150:com.test.thalitest/u0a311}, curProc for 6150: null
I/ActivityManager( 1028): Force stopping com.test.thalitest appid=10311 user=0: pkg removed
I/ActivityManager( 1028):   Force finishing activity ActivityRecord{3a4da4c u0 com.test.thalitest/.MainActivity t4 f}
W/ActivityManager( 1028): Duplicate finish request for ActivityRecord{3a4da4c u0 com.test.thalitest/.MainActivity t4 f}
,D/SplitWindowPolicy( 1944): updateActivityStateChanged: resumed=false, screenId=0, isScreenFull=false
D/SplitWindowPolicy( 1944): topRunningActivity=ActivityInfo{2af1d52 co.....Launcher}, taskId=3, activityType=1, bIsSplit=false
D/SplitWindowPolicy( 1944): updateActivityStateChanged: resumed=true, screenId=0, isScreenFull=false
D/SplitWindowPolicy( 1944): topRunningActivity=ActivityInfo{3eeaa823 co.....Launcher}, taskId=3, activityType=1, bIsSplit=false
I/[LGHome]EVENT( 2065): [Launcher.java:5338:onStart()]onStart
I/[LGHome]EVENT( 2065): [Launcher.java:903:onResume()]onResume
,D/KeyguardModel( 1446): mPackageIntentReceiver, received action: android.intent.action.PACKAGE_REMOVED, sendingUserId:0
,I/InputReader( 1028): Reconfiguring input devices.  changes=0x00000010
D/LIA_Service_RemotePackageHandler( 2010): onReceive action : android.intent.action.PACKAGE_REMOVED = package:com.test.thalitest
E/LGBluetoothAvrcpQcomAdapter( 6231): [BTUI] [BTUI] onReceive()... android.intent.action.PACKAGE_REMOVED
D/LGBluetoothAvrcpQcomAdapter( 6231): [BTUI] [+] updateMediaPlayerInfo
D/LIA_MrGDBLogger_PackageInfoDetector( 2700): [dreamwood]action: android.intent.action.PACKAGE_REMOVED, package: com.test.thalitest
,D/PostponalbeReceiver( 6429): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.intent.action.PACKAGE_REMOVED'.
I/[LGHome]EVENT( 2065): [LauncherModel.java:1352:startLoader()]startLoader isLaunching=true
,I/[LGHome]Launcher.Model( 2065): [LauncherModel.java:1469:loadAndBindWorkspace()]loadAndBindWorkspace=0ms
W/GeofencerStateMachine( 1815): Ignoring removeGeofence because network location is disabled.
V/SIM_STK ( 1028): Menu title from STK is T-Mobile
,W/System.err( 4184): android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
W/System.err( 4184): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
W/System.err( 4184): 	at com.lge.mlt.MptOnAppWatcher$1.onReceive(MptOnAppWatcher.java:44)
W/System.err( 4184): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:956)
W/System.err( 4184): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 4184): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 4184): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 4184): 	at android.app.ActivityThread.main(ActivityThread.java:5274)
,W/System.err( 4184): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 4184): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 4184): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
W/System.err( 4184): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
,D/administrator( 1028): Handling package changes for user 0
V/SIM_STK ( 1028): Menu title from STK is T-Mobile
V/SIM_STK ( 1028): Menu title from STK is T-Mobile
,I/ActivityManager( 1028): Start proc com.lge.lockscreensettings for content provider com.lge.lockscreensettings/.LockSettingsProvider: pid=7093 uid=10080 gids={50080, 9997, 1028, 1015} abi=armeabi-v7a
D/ActionManagerService( 1901): notifyUserLog: 1000003
,D/LIA_Informant_ActionManagerMessageHandler( 2700): handleMessage: what(1000) actionID(0x1000003)
I/[LGHome]GBoardWebView( 2065): [GBoardWebView.java:306:loadCacheBitmapPostDelayed()]loadCacheBitmapPostDelayed() delay:1
D/AppUp4:PreloadHelper( 6647): added Exclude : com.test.thalitest
I/[LGHome]LGActivityUtil( 2065): [LGActivityUtil.java:319:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
I/[LGHome]EVENT( 2065): [Launcher.java:1056:onResume()]onResume end
I/[SystemUI]QSlideListController( 1446): onReceive = android.intent.action.PACKAGE_REMOVED
I/art     ( 4230): Explicit concurrent mark sweep GC freed 15090(880KB) AllocSpace objects, 0(0B) LOS objects, 35% free, 29MB/45MB, paused 546us total 163.663ms
,V/SIM_STK ( 1028): Menu title from STK is T-Mobile
,I/ActivityManager( 1028): Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=7111 uid=10019 gids={50019, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
W/ActivityManager( 1028): getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
D/LGBluetoothAvrcpQcomAdapter( 6231): [BTUI] installed app name: Music
D/LGBluetoothAvrcpQcomAdapter( 6231): [BTUI] installed app name: Google Play Music
D/LGBluetoothAvrcpQcomAdapter( 6231): [BTUI] === MediaPlayerInfo (playerId:0) ===
D/LGBluetoothAvrcpQcomAdapter( 6231): [BTUI]          displayName: Music
D/LGBluetoothAvrcpQcomAdapter( 6231): [BTUI]          packageName: com.lge.music
D/LGBluetoothAvrcpQcomAdapter( 6231): [BTUI]          playState: 2 (PAUSED)
D/LGBluetoothAvrcpQcomAdapter( 6231): [BTUI] === MediaPlayerInfo (playerId:1) ===
D/LGBluetoothAvrcpQcomAdapter( 6231): [BTUI]          displayName: Google Play Music
D/LGBluetoothAvrcpQcomAdapter( 6231): [BTUI]          packageName: com.google.android.music
D/LGBluetoothAvrcpQcomAdapter( 6231): [BTUI]          playState: 2 (PAUSED)
D/LGBluetoothAvrcpQcomAdapter( 6231): [BTUI] [-] updateMediaPlayerInfo
I/[LGHome]EVENT( 2065): [Launcher.java:1114:onPause()]onPause
I/[LGHome]GBoardWebView( 2065): [GBoardWebView.java:247:writeCacheBitmapPostDelayed()]writeCacheBitmapPostDelayed() delay: we don't have a change point1
D/ActionManagerService( 1901): notifyUserLog: 1000004
D/LIA_Informant_ActionManagerMessageHandler( 2700): handleMessage: what(1000) actionID(0x1000004)
V/BoardContentProvider( 2700): query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
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
I/GBoardWebViewUtils( 2065): checkExpiredAndRemoveCard() card: GBoardCard = { id: guide_1111111111116_1453982949437
I/GBoardWebViewUtils( 2065): , create_time: 1453982950152
I/GBoardWebViewUtils( 2065): , expire_time: 0
I/GBoardWebViewUtils( 2065): , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/4/userguide.html?id=guide_1111111111116_1453982949437&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
I/GBoardWebViewUtils( 2065): , category: com.lge.intent.category.gboard.DOYOUKNOW
I/GBoardWebViewUtils( 2065): , display: false
I/GBoardWebViewUtils( 2065): , animation: false }
,I/[SystemUI]AppWidgetPanel(QRemoteWidgetPanel)( 1446): onReceive = android.intent.action.PACKAGE_REMOVED, packageName : com.test.thalitest
D/KeyguardModel( 1446): mPackageIntentReceiver, received action: android.intent.action.PACKAGE_FULLY_REMOVED, sendingUserId:0
D/WallpaperManager( 2065): suggestDesiredDimensions(2880, 2560) by package(com.lge.launcher2)
,I/SystemUI[Framework]( 1028): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x8000, pkg=com.android.systemui
W/PhoneWindowManagerEx( 1028): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx( 1028): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx( 1028): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework]( 1028): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@2eb1cc2b,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework]( 1028): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
,I/[LGHome]EVENT( 2065): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
I/[LGHome]GBoardWebView( 2065): [GBoardWebView.java:321:loadCacheBitmap()]loadCacheBitmap()
,I/LockScreenSettings( 7093): Wallpaper base directory = /data/user/0/com.lge.lockscreensettings/files/
D/SplitUIManager( 1867): split_name #11 / not available #0
,D/SplitUIService( 1867): removed split : 
D/KeyguardModel( 1446): package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
D/KeyguardModel( 1446): createShortcutInfo...
I/NotificationService( 1028): action=android.intent.action.PACKAGE_REMOVED queryReplace=false
D/BackupManagerService( 1028): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/JobSchedulerService( 1028): Receieved: android.intent.action.PACKAGE_REMOVED
,D/KeyguardModel( 1446): package = com.android.mms, class = com.android.mms.ui.ConversationList
D/KeyguardModel( 1446): createShortcutInfo...
D/PhoneStatusBar( 1446): setSystemUiVisibility vis=8000 mask=ffffffff oldVal=0 newVal=8000 diff=8000
D/TaskPersister( 1028): removeObsoleteFile: deleting file=4_task.xml
I/[SystemUI]NavigationThemeResource( 1446): NavigationKey Color is changed(BLACK -> WHITE_WITH_SHADOW)
I/[SystemUI]NavigationThemeResource( 1446):  BarMode=4, Theme=WHITE, LightBackground=false (Transparent)
I/[SystemUI]NavigationThemeResource( 1446): , Keyguard show=false, IME shown=false, Panel expanded=false
W/ResourcesManager( 1446): Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
W/ResourcesManager( 1446): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 1446): Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
,W/ResourcesManager( 1446): Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
W/ResourceType( 1446): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1446): Failure retrieving resources for com.android.mms: Resource ID #0x0
D/KeyguardModel( 1446): package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
D/KeyguardModel( 1446): createShortcutInfo...
W/ResourcesManager( 1446): Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
W/ResourcesManager( 1446): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourceType( 1446): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1446): Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
,D/KeyguardModel( 1446): package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
D/KeyguardModel( 1446): createShortcutInfo...
D/SplitUIManager( 1867): split_name #11 / not available #0
I/SplitUIService( 1867): split app #11
W/ResourcesManager( 1446): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 1446): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 1446): Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
W/ResourcesManager( 1446): Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
,W/ResourceType( 1446): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1446): Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
D/KeyguardModel( 1446): package = com.lge.camera, class = com.lge.camera.CameraApp
D/KeyguardModel( 1446): createShortcutInfo...
D/KeyguardModel( 1446): handleShortcutListChanged...
D/KeyguardModel( 1446): package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
D/KeyguardModel( 1446): createShortcutInfo...
,I/[LGHome]EVENT( 2065): [Launcher.java:5349:onStop()]onStop
D/KeyguardModel( 1446): package = com.android.mms, class = com.android.mms.ui.ConversationList
D/KeyguardModel( 1446): createShortcutInfo...
W/ResourceType( 1446): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1446): Failure retrieving resources for com.android.mms: Resource ID #0x0
D/KeyguardModel( 1446): package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
D/KeyguardModel( 1446): createShortcutInfo...
W/ResourceType( 1446): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1446): Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
W/ResourcesManager( 7111): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7111): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 7111): Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
W/ResourcesManager( 7111): Asset path '/system/framework/lghiddenlibs.jar' does not exist or contains no resources.
W/ResourcesManager( 7111): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
,D/KeyguardModel( 1446): package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
D/KeyguardModel( 1446): createShortcutInfo...
W/ResourceType( 1446): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1446): Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
D/KeyguardModel( 1446): package = com.lge.camera, class = com.lge.camera.CameraApp
D/KeyguardModel( 1446): createShortcutInfo...
I/ActivityManager( 1028): Killing 6332:com.lge.sync/1000 (adj 15): empty #17
,I/[LGHome]Launcher.Model( 2065): [LauncherModel.java:2230:run()] LauncherModel bind current page shortcut
I/[LGHome]Launcher( 2065): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,I/[LGHome]EVENT( 2065): [Workspace.java:918:addInScreen()]Add Shortcut [Email] in screen 1 [1, 4]
I/[LGHome]EVENT( 2065): [Workspace.java:918:addInScreen()]Add Shortcut [Play Store] in screen 1 [2, 4]
I/[LGHome]EVENT( 2065): [Workspace.java:918:addInScreen()]Add Shortcut [Camera] in screen 1 [3, 4]
I/[LGHome]EVENT( 2065): [Workspace.java:918:addInScreen()]Add Shortcut [Settings] in screen 1 [4, 4]
I/[LGHome]Launcher.Model( 2065): [LauncherModel.java:2244:run()] LauncherModel bind current page shortcut
I/[LGHome]Launcher( 2065): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 2065): [LGUnreadLgeEmailsBadge.java:107:countUnreadItems()]setTotalCount : 0
I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 2065): [LGUnreadLgeEmailsBadge.java:108:countUnreadItems()]countUnreadItems() ended..
W/libprocessgroup( 1028): failed to open /acct/uid_1000/pid_6332/cgroup.procs: No such file or directory
D/KeyguardModel( 1446): handleShortcutListChanged...
I/art     ( 1028): Explicit concurrent mark sweep GC freed 35126(2MB) AllocSpace objects, 7(624KB) LOS objects, 33% free, 44MB/66MB, paused 2.823ms total 204.793ms
I/Timeline( 1028): Timeline: Activity_windows_visible id: ActivityRecord{15a16fc6 u0 com.lge.launcher2/.Launcher t3} time:265874
,I/[LGHome]EVENT( 2065): [Workspace.java:918:addInScreen()]Add Folder [Google] in screen 1 [0, 4]
I/[LGHome]Launcher.Model( 2065): [LauncherModel.java:2256:run()] LauncherModel bind current page widget
I/[LGHome]Launcher( 2065): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/[Concierge]WidgetView( 2065): ConciergeWidgetView is instantiated. sIsWidgetAttached : true
D/[Concierge]Service( 2589): onStartCommand(). Type : 8
D/[Concierge]Service( 2589): Update widget. Component : {com.lge.concierge/com.lge.concierge.ConciergeWidgetProvider}
D/[Concierge]Service( 2589): Update widget ID : 11
D/[Concierge]WidgetView( 2065): change position of spinner
,E/BooksSync( 6666): Soft error: 
E/BooksSync( 6666): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 6666): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=6417322921033128067&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 6666): Headers:
E/BooksSync( 6666): accept-encoding: [gzip]
E/BooksSync( 6666): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 6666): gdata-version: 2
E/BooksSync( 6666): 
E/BooksSync( 6666): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 6666): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 6666): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 6666): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 6666): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 6666): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 6666): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 6666): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 6666): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 6666): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 6666): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 6666): {
E/BooksSync( 6666):  "error": {
E/BooksSync( 6666):   "errors": [
E/BooksSync( 6666):    {
E/BooksSync( 6666):     "domain": "global",
E/BooksSync( 6666):     "reason": "required",
E/BooksSync( 6666):     "message": "Login Required",
E/BooksSync( 6666):     "locationType": "header",
E/BooksSync( 6666):     "location": "Authorization"
E/BooksSync( 6666):    }
E/BooksSync( 6666):   ],
E/BooksSync( 6666):   "code": 401,
E/BooksSync( 6666):   "message": "Login Required"
E/BooksSync( 6666):  }
E/BooksSync( 6666): }
E/BooksSync( 6666): 
E/BooksSync( 6666): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 6666): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 6666): 	... 8 more
E/BooksSync( 6666): Sync error
E/BooksSync( 6666): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 6666): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=6417322921033128067&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 6666): Headers:
E/BooksSync( 6666): accept-encoding: [gzip]
E/BooksSync( 6666): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 6666): gdata-version: 2
E/BooksSync( 6666): 
E/BooksSync( 6666): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 6666): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 6666): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 6666): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 6666): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 6666): 	at com.google.android.apps.books.data.NetworkTaskQ,ueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 6666): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 6666): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 6666): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 6666): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 6666): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 6666): {
E/BooksSync( 6666):  "error": {
E/BooksSync( 6666):   "errors": [
E/BooksSync( 6666):    {
E/BooksSync( 6666):     "domain": "global",
E/BooksSync( 6666):     "reason": "required",
E/BooksSync( 6666):     "message": "Login Required",
E/BooksSync( 6666):     "locationType": "header",
E/BooksSync( 6666):     "location": "Authorization"
E/BooksSync( 6666):    }
E/BooksSync( 6666):   ],
E/BooksSync( 6666):   "code": 401,
E/BooksSync( 6666):   "message": "Login Required"
E/BooksSync( 6666):  }
E/BooksSync( 6666): }
E/BooksSync( 6666): 
E/BooksSync( 6666): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 6666): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 6666): 	... 8 more
I/BooksSync( 6666): Finished books sync
I/SystemConfig( 7111): BUILD Country: EU
I/SystemConfig( 7111): BUILD Operator: OPEN
I/[Concierge]WidgetView( 2065): initWebView(). Time : 1454085872815
D/[Concierge]Service( 2589): onStartCommand(). Type : 0
,I/GAV2    ( 6666): Thread[GAThread,5,main]: No campaign data found.
D/AndroidRuntime( 7061): Shutting down VM
,I/[Concierge]WebView( 2065): Return exist ConciergeWebView. Reuse : 714706276
D/[Concierge]WidgetView( 2065): State Change : null -> AccInBeforeState
I/[LgeWidgetLib]LgeAppWidgetHostView( 2065): [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
I/[LgeWidgetLib]ExtViewHost( 2065): [LgeAppWidgetExtViewHost.java:136:setState()]New State = com.lge.lgewidgetlib.extview.NormalState@3507dec
I/[LGHome]EVENT( 2065): [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.concierge.ConciergeWidgetProvider] in screen 1 [0, 0]
I/[LGHome]Launcher.Model( 2065): [LauncherModel.java:2256:run()] LauncherModel bind current page widget
I/[LGHome]Launcher( 2065): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/[LGHome]EVENT( 2065): [Workspace.java:918:addInScreen()]Add AppWidget [com.google.android.googlequicksearchbox.SearchWidgetProvider] in screen 1 [0, 2]
D/[Concierge]WidgetView( 2065): isWidgetUpdateSkippable ? true
D/[Concierge]WidgetBroadcastReceiver( 2065): New receiver registered. Self-unregister old one. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
W/[Concierge]WidgetView( 2065): Widget kill message received. Destory myself. My : 1454085635108, New one : 1454085872815
D/[Concierge]WidgetView( 2065): Unregister all receivers
,W/[Concierge]WidgetBroadcastReceiver( 2065): Tried unregister broadcastReceiver which is not registered. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
I/[LGHome]Launcher( 2065): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/[LGHome]EVENT( 2065): [Workspace.java:918:addInScreen()]Add Shortcut [Gallery] in screen 2 [0, 4]
I/[LGHome]EVENT( 2065): [Workspace.java:918:addInScreen()]Add Shortcut [Calendar] in screen 2 [1, 4]
I/[LGHome]EVENT( 2065): [Workspace.java:918:addInScreen()]Add Shortcut [QuickMemo+] in screen 2 [2, 4]
I/[LGHome]EVENT( 2065): [Workspace.java:918:addInScreen()]Add Shortcut [Quick Remote] in screen 2 [3, 4]
I/[LGHome]EVENT( 2065): [Workspace.java:918:addInScreen()]Add Shortcut [FM Radio] in screen 2 [4, 4]
I/[LGHome]Launcher( 2065): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/[LGHome]Launcher( 2065): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/ActivityManager( 1028): Killing 5889:com.uei.lg.quicksetsdk.maxq616/1000 (adj 15): empty #17
,I/QRemote ( 6490): [RemoteControlManager.java:195:onServiceDisconnected()] oooooo start
W/System.err( 6490): android.os.DeadObjectException
W/System.err( 6490): 	at android.os.BinderProxy.transactNative(Native Method)
W/System.err( 6490): 	at android.os.BinderProxy.transact(Binder.java:496)
W/System.err( 6490): 	at com.uei.control.IControl.unregisterCallback(IControl.java:502)
W/System.err( 6490): 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:199)
W/System.err( 6490): 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
W/System.err( 6490): 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
W/System.err( 6490): 	at android.os.Handler.handleCallback(Handler.java:739)
,W/System.err( 6490): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 6490): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 6490): 	at android.app.ActivityThread.main(ActivityThread.java:5274)
W/System.err( 6490): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 6490): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 6490): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
W/System.err( 6490): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
E/UEI.SmartControl( 6490): IControl.unregisterCallback error: android.os.DeadObjectException
W/System.err( 6490): android.os.DeadObjectException
W/System.err( 6490): 	at android.os.BinderProxy.transactNative(Native Method)
W/System.err( 6490): 	at android.os.BinderProxy.transact(Binder.java:496)
W/System.err( 6490): 	at com.uei.control.IControl.unregisterSetupReadyCallback(IControl.java:818)
W/System.err( 6490): 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:200)
W/System.err( 6490): 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
W/System.err( 6490): 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
W/System.err( 6490): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 6490): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 6490): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 6490): 	at android.app.ActivityThread.main(ActivityThread.java:5274)
W/System.err( 6490): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 6490): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 6490): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
W/System.err( 6490): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
E/UEI.SmartControl( 6490): IControl.unregisterSetupReadyCallback error: android.os.DeadObjectException
I/QRemote ( 6490): [RemoteControlManager.java:203:onServiceDisconnected()] oooooo Control unbind before rebinding.
W/ResourcesManager( 1028): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourceType( 1028): Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
I/[LgeWidgetLib]LgeAppWidgetHostView( 2065): [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
,E/[LgeWidgetLib]LgeAppWidgetHostView( 2065): [LgeAppWidgetHostView.java:124:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
I/[LGHome]EVENT( 2065): [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1] in screen 2 [0, 0]
I/[LGHome]Launcher( 2065): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/Timeline( 2065): Timeline: Activity_idle id: android.os.BinderProxy@3c130ca7 time:266032
,I/chromium( 2065): [INFO:CONSOLE(0)] "'window.webkitStorageInfo' is deprecated. Please use 'navigator.webkitTemporaryStorage' or 'navigator.webkitPersistentStorage' instead.", source:  (0)
,W/libprocessgroup( 1028): failed to open /acct/uid_1000/pid_5889/cgroup.procs: No such file or directory
,W/ActivityManager( 1028): Scheduling restart of crashed service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service in 1000ms
D/QRemote ( 6490): [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]10
I/QRemote ( 6490): [RemoteControlManager.java:157:onBindIRService()] oooooo bind
I/SystemConfig( 7111): pm.hasSystemFeature(com.lge.ims.rcs) = false
I/SystemConfig( 7111): existFile = false
I/SystemConfig( 7111): canReadFile = false
I/SystemConfig( 7111): systemFeature RCS result false
D/SystemConfig( 7111): refreshRcsSupport() :false
,I/GBoardtInterface( 2065): onReloaded()
,I/GBoardWebViewClient( 2065): onPageFinished url:file:///android_asset/www/main.html
I/ActivityManager( 1028): Start proc com.uei.lg.quicksetsdk.maxq616 for service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service: pid=7140 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,D/QRemote ( 6490): [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
V/BoardContentProvider( 2700): query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
I/ActivityManager( 1028): Killing 6269:com.android.settings/1000 (adj 15): empty #17
D/SyncManager( 1028): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 26643, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/VoicemailCleanupService( 2169): Cleaning up data for package: com.test.thalitest
,D/WifiService( 1028): Client connection lost with reason: 4
,W/libprocessgroup( 1028): failed to open /acct/uid_1000/pid_6269/cgroup.procs: No such file or directory
,I/PackageChangeReceiver( 6734): intent action : android.intent.action.PACKAGE_REMOVED (at PackageChangeReceiver.java onReceive 20)
,E/SharedPreferencesImpl( 6687): Couldn't rename file /data/data/com.android.gallery3d/shared_prefs/com.android.gallery3d_preferences.xml to backup file /data/data/com.android.gallery3d/shared_prefs/com.android.gallery3d_preferences.xml.bak
D/LIA_Service_NativeEventReceiver( 2010): onReceive action : android.intent.action.PACKAGE_REMOVED = package:com.test.thalitest
I/LIA_Service_PlatformUtil( 2010): startLIAService() : Trying to start LIA service ...
D/LIA_Service_LIAService( 2010): onStartCommand() : LIAService started! - id :4, intent : Intent { act=com.lge.ia pkg=com.lge.ia (has extras) }
V/BoardContentProvider( 2700): query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
,D/PostponalbeReceiver( 6429): OasPackageInstalledReceiver is processing the broadcast action 'android.intent.action.PACKAGE_REMOVED'.
E/UEI.SmartControl( 7140): Failed while opening the log file.
E/UEI.SmartControl( 7140): java.io.FileNotFoundException: /data/data/com.uei.lg.quicksetsdk.maxq616/app_log/app.log: open failed: EROFS (Read-only file system)
E/UEI.SmartControl( 7140): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/UEI.SmartControl( 7140): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/UEI.SmartControl( 7140): 	at java.io.FileWriter.<init>(FileWriter.java:58)
E/UEI.SmartControl( 7140): 	at com.uei.e.c.a(Unknown Source)
E/UEI.SmartControl( 7140): 	at com.uei.e.c.a(Unknown Source)
E/UEI.SmartControl( 7140): 	at com.uei.e.c.<init>(Unknown Source)
E/UEI.SmartControl( 7140): 	at com.uei.e.c.a(Unknown Source)
E/UEI.SmartControl( 7140): 	at com.uei.control.core.QSApp.onCreate(Unknown Source)
E/UEI.SmartControl( 7140): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1011)
E/UEI.SmartControl( 7140): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4568)
E/UEI.SmartControl( 7140): 	at android.app.ActivityThread.access$1500(ActivityThread.java:148)
E/UEI.SmartControl( 7140): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1344)
E/UEI.SmartControl( 7140): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/UEI.SmartControl( 7140): 	at android.os.Looper.loop(Looper.java:135)
E/UEI.SmartControl( 7140): 	at android.app.ActivityThread.main(ActivityThread.java:5274)
E/UEI.SmartControl( 7140): 	at java.lang.reflect.Method.invoke(Native Method)
E/UEI.SmartControl( 7140): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/UEI.SmartControl( 7140): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
E/UEI.SmartControl( 7140): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
E/UEI.SmartControl( 7140): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/UEI.SmartControl( 7140): 	at libcore.io.Posix.open(Native Method)
E/UEI.SmartControl( 7140): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/UEI.SmartControl( 7140): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/UEI.SmartControl( 7140): 	... 18 more
,D/UEI.SmartControl( 7140): Quickset Services start...
I/UEI.SmartControl( 7140): Manufacture = LGE
D/UEI.SmartControl( 7140): Id = LGNevo
D/UEI.SmartControl( 7140): File observer start...
E/UEI.SmartControl( 7140): IR Port is disabled: false
D/UEI.SmartControl( 7140): Starting file observer...
D/UEI.SmartControl( 7140): Extracting JNI libs...
D/UEI.SmartControl( 7140): --- this system supports 32-bit or 64-bit only
I/ActivityManager( 1028): Start proc com.lge.lifetracker for broadcast com.lge.lifetracker/.core.receiver.CoreEventReceiver: pid=7161 uid=10037 gids={50037, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
,D/ActionManagerService( 1901): notifyUserLog: 1000001
D/LIA_Informant_ActionManagerMessageHandler( 2700): handleMessage: what(1000) actionID(0x1000001)
D/LIA_Informant_Tips_SmartTipsActionManager( 2700): onEvent() : ACTION_BOARD_ENABLED
D/ActionManagerService( 1901): notifyUserLog: 1000001
D/LIA_Informant_ActionManagerMessageHandler( 2700): handleMessage: what(1000) actionID(0x1000001)
D/LIA_Informant_Tips_SmartTipsActionManager( 2700): onEvent() : ACTION_BOARD_ENABLED
D/LIA_Informant_Tips_FormEventRepository( 2700): getSize() : size - 0
D/LIA_Informant_Tips_SmartTipsActionManager( 2700): onSettingEvent() : GBoard On - add scheduler - 0
V/BoardContentProvider( 2700): query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
D/GBoardUriUtils( 2065): fileExists: file:///system/etc/mrg_default_forms/MyWellness/initial/initial2.html?id=mw_initial return true
D/GBoardWebViewUtils( 2065): changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyWellness/initial/initial2.html?id=mw_initial
D/GBoardUriUtils( 2065): fileExists: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial2.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc] return true
D/GBoardWebViewUtils( 2065): changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial2.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
,D/GBoardUriUtils( 2065): fileExists: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/4/userguide2.html?id=guide_1111111111116_1453982949437&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay return true
D/GBoardWebViewUtils( 2065): changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/4/userguide2.html?id=guide_1111111111116_1453982949437&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
I/[LGHome]EVENT( 2065): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
,D/UEI.SmartControl( 7140): --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
D/UEI.SmartControl( 7140): --- Checking lib: libqs_armeabi-v7a.zip
D/UEI.SmartControl( 7140): --- Extracting JNI libs: libqs_armeabi-v7a.zip
E/UEI.SmartControl( 7140): unzip: java.io.FileNotFoundException: /data/data/com.uei.lg.quicksetsdk.maxq616/files/libqs_jni.so: open failed: EROFS (Read-only file system)
I/UEI.SmartControl( 7140): --- Selecting new region: 6

```
