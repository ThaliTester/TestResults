#### Test 57924002d5e0b14_thali03_LGE-LG-D855 Logs


```
--------- beginning of system
V/AlarmManager( 1030): RTC_WAKEUP set : Alarm{2a864a94 type 0 when 1454440716121 com.android.vending} when 1454440716121
,W/ContextImpl( 4189): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 com.lge.mlt.MptOnLogDumper.run:279 <bottom of call stack> <bottom of call stack> 
--------- beginning of main
V/SIM_STK ( 1030): Menu title from STK is T-Mobile
D/AndroidRuntime( 5956): 
D/AndroidRuntime( 5956): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 5956): CheckJNI is OFF
V/GLSActivity( 2126): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/GLSUser ( 2126): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 2126): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2126): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2126): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2126): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/Finsky  ( 4843): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/AndroidRuntime( 5956): Calling main entry com.android.commands.am.Am
D/Finsky  ( 4843): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 4843): [1] 5.onFinished: Scheduling replication attempt 1.
I/ActivityManager( 1030): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
V/SplitWindowPolicy( 1964): checkScreen => return. sourceIntent is null or not support SplitWindow component: ComponentInfo{co..../co.....MainActivity}
D/SplitInfo( 1030): new ActivitySplitInfo : ActivitySplitInfo [screenZone=0/ flag=0/ state=NATIVE]
D/ActivityManager( 1030): setTaskToReturnTo : TaskRecord{3223d356 #4 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
D/ActivityManager( 1030): setTaskToReturnTo : TaskRecord{3223d356 #4 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
D/WindowStateEx( 1030): AppWindowTokenEx init.. 
E/GBMv2   (  332): DFP En is all cleared set to be enabled
I/ActivityManager( 1030): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=5996 uid=10311 gids={50311, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
D/AndroidRuntime( 5956): Shutting down VM
V/ActivityManager( 1030): Display changed displayId=0
D/DSDPConnection( 1866): Display #0 changed.
D/SplitWindowPolicy( 1964): updateActivityStateChanged: resumed=true, screenId=1, isScreenFull=true
D/SplitWindowPolicy( 1964): topRunningActivity=ActivityInfo{f0d1408 co.....MainActivity}, taskId=4, activityType=0, bIsSplit=false
D/SplitWindowPolicy( 1964): updateActivityStateChanged: resumed=false, screenId=1, isScreenFull=true
D/SplitWindowPolicy( 1964): topRunningActivity=ActivityInfo{2adc27a1 co.....MainActivity}, taskId=4, activityType=0, bIsSplit=false
D/ContextHelper( 5996): convertTheme. context->name=com.test.thalitest themeResourceId=16973833
I/WebViewFactory( 5996): Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,I/LibraryLoader( 5996): Loading: webviewchromium
I/LibraryLoader( 5996): Time to load native libraries: 4 ms (timestamps 2121-2125)
I/LibraryLoader( 5996): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 5996): Binding Chromium to main looper Looper (main, tid 1) {229833cd}
I/LibraryLoader( 5996): Expected native library version number "",actual native library version number ""
I/chromium( 5996): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 5996): Initializing chromium process, renderers=0
W/art     ( 5996): Attempt to remove local handle scope entry from IRT, ignoring
W/chromium( 5996): [WARNING:dns_config_service_posix.cc(293)] Failed to read DnsConfig.
,V/AudioPolicyService(  313): registerClient() client 0xb14274c0, uid 10311
,D/BluetoothManagerService( 1030): Message: 20
D/BluetoothManagerService( 1030): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@33b1e530:true
D/BluetoothAdapter( 5996): 941929602: getState() :  mService = null. Returning STATE_OFF
W/chromium( 5996): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
I/chromium( 5996): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=32 off=46780 len=2953
I/chromium( 5996): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:33 off:229536 len:643667
I/Adreno-EGL( 5996): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 5996): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 5996): Build Date: 12/12/14 금
I/Adreno-EGL( 5996): Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
I/Adreno-EGL( 5996): Remote Branch: 
I/Adreno-EGL( 5996): Local Patches: 
I/Adreno-EGL( 5996): Reconstruct Branch: 
,W/chromium( 5996): [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
,W/chromium( 5996): [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
W/art     ( 5996): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 5996): onDetachedFromWindow called when already detached. Ignoring
D/SystemWebViewEngine( 5996): CordovaWebView is running on device made by: LGE
,W/art     ( 5996): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 5996): Attempt to remove local handle scope entry from IRT, ignoring
,D/OpenGLRenderer( 5996): Render dirty regions requested: true
,I/OpenGLRenderer( 5996): Initialized EGL, version 1.4
D/OpenGLRenderer( 5996): Enabling debug mode 0
D/Atlas   ( 5996): Validating map...
,D/SplitWindow( 1030): check instance of lgWin Window{3d0943ea u0 com.test.thalitest/com.test.thalitest.MainActivity}
W/ActivityManager( 1030): Activity pause timeout for ActivityRecord{e295fd7 u0 com.test.thalitest/.MainActivity t4}
,D/LgDataFeature( 5996): LgDataFeature() Constructor: none
D/LgDataFeature( 5996): LgDataFeature() Constructor Done, null
,I/SystemUI[Framework]( 1030): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x0, pkg=com.android.systemui
,D/PhoneStatusBar( 1472): setSystemUiVisibility vis=0 mask=ffffffff oldVal=8000 newVal=0 diff=8000
I/[SystemUI]NavigationThemeResource( 1472): NavigationKey Color is changed(WHITE_WITH_SHADOW -> BLACK)
I/[SystemUI]NavigationThemeResource( 1472):  BarMode=0, Theme=WHITE, LightBackground=false (Transparent)
I/[SystemUI]NavigationThemeResource( 1472): , Keyguard show=false, IME shown=false, Panel expanded=false
W/PhoneWindowManagerEx( 1030): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx( 1030): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx( 1030): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework]( 1030): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@36685e45,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework]( 1030): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
I/Timeline( 5996): Timeline: Activity_idle id: android.os.BinderProxy@12f74232 time:112574
,I/ActivityManager( 1030): Displayed com.test.thalitest/.MainActivity: +630ms (total +735ms)
I/Timeline( 1030): Timeline: Activity_windows_visible id: ActivityRecord{e295fd7 u0 com.test.thalitest/.MainActivity t4} time:112578
I/chromium( 5996): [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
I/chromium( 5996): 
,D/JsMessageQueue( 5996): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log( 5996): JniHelper::setJavaVM(0xb487c280), pthread_self() = -1435196160
,I/chromium( 5996): [INFO:SkFontConfigInterface_android.cpp(247)] ---- failed to open </system/fonts/CutiveMono.ttf> as a font
I/chromium( 5996): 
,I/chromium( 5996): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/CloudHub( 2210): [CLIENT][CloudHubClientFactory$1|onTick] Until finished: 19979
,E/GBMv2   (  332): DFP En is all cleared set to be enabled
E/GBMv2   (  332): Set value is all cleared set the max
I/GBMv2   (  332): DFP Enabled. Ignore VFP set
,W/jxcore-log( 5996): Initializing JXcore engine
W/jxcore-log( 5996): JXcore engine is ready
,W/Thread-689( 6050): type=1400 audit(0.0:148): avc: denied { ioctl } for path="socket:[8578]" dev="sockfs" ino=8578 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
,W/Thread-689( 6050): type=1400 audit(0.0:149): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3222 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
W/Thread-689( 6050): type=1400 audit(0.0:150): avc: denied { ioctl } for path="socket:[7687]" dev="sockfs" ino=7687 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
W/Thread-689( 6050): type=1400 audit(0.0:151): avc: denied { ioctl } for path="/cust" dev="mmcblk0p42" ino=2 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=dir
W/Thread-689( 6050): type=1400 audit(0.0:152): avc: denied { ioctl } for path="socket:[31007]" dev="sockfs" ino=31007 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
W/jxcore-log( 5996): Starting JXcore engine
,W/jxcore-log( 5996): Platform android
W/jxcore-log( 5996): 
W/jxcore-log( 5996): Process ARCH arm
W/jxcore-log( 5996): 
,I/jxcore-log( 5996): JXcore Cordova bridge is ready!
I/jxcore-log( 5996): 
W/jxcore-log( 5996): JXcore engine is started
,I/jxcore-log( 5996): Toggling radios to true
I/jxcore-log( 5996): 
D/BluetoothManagerService( 1030): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1030): enable():  mBluetooth =null mBinding = false
,D/BluetoothManagerService( 1030): Message: 1
D/BluetoothManagerService( 1030): MESSAGE_ENABLE: mBluetooth = null
D/LocationManagerService( 1030): getAllProviders()=[passive, gps, network]
D/Ulp_jni ( 1030): JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
D/Ulp_jni ( 1030): JNI:system_update. Event-4
D/WifiService( 1030): New client listening to asynchronous messages
I/ActivityManager( 1030): Start proc com.android.bluetooth for service com.android.bluetooth/.btservice.AdapterService: pid=6053 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008, 4002, 1023} abi=armeabi-v7a
D/WifiServiceImplEx( 1030): setWifiEnabled: true pid=5996, uid=10311, package= com.test.thalitest, App Lable : ThaliTest
D/WifiService( 1030): setWifiEnabled: true pid=5996, uid=10311
E/WifiService( 1030): Invoking mWifiStateMachine.setWifiEnabled
,D/LocationManagerService( 1030): getAllProviders()=[passive, gps, network]
D/Ulp_jni ( 1030): JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 1,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
D/Ulp_jni ( 1030): JNI:system_update. Event-4
E/WifiStateMachine( 1030):  InitialState CMD_START_SUPPLICANT 0 0
I/LGFTMITEM( 1030): [GET_FTM][id=6], offset=12288
D/WifiServiceImplEx( 1030): disconnect pid=5996, uid=10311, packageName=com.test.thalitest
D/WifiServiceImplEx( 1030): reconnect pid=5996, uid=10311, packageName=com.test.thalitest
E/WifiUtil( 1030): wfc_util_ffile_check_copy(): pid[1030] pDestFName[/data/misc/wifi/WCNSS_qcom_cfg.ini] pSourceFName[/system/etc/wifi/WCNSS_qcom_cfg.ini]
E/WifiUtil( 1030): wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
E/WifiUtil( 1030): wfc_util_ffile_check_copy(): pid[1030] pDestFName[/data/misc/wifi/WCNSS_qcom_wlan_nv.bin] pSourceFName[/system/etc/wifi/WCNSS_qcom_wlan_nv.bin]
E/WifiUtil( 1030): wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
I/WifiUtil( 1030): Intf0MacAddress=C49A027B60AC
E/WifiHW  ( 1030): unknown target_country: EU , set to default
E/WifiHW  ( 1030): [wifi_ensure_config_files] default country1 = GB
E/WifiHW  ( 1030): [wifi_ensure_config_files] default country2 = GB
I/WifiUtil( 1030): gEnableBmps=1
I/jxcore-log( 5996): Radios toggled
I/jxcore-log( 5996): 
I/jxcore-log( 5996): My device name is: LGE-LG-D855
I/jxcore-log( 5996): 
,W/ResourcesManager( 6053): Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
W/ResourcesManager( 6053): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 6053): Asset path '/system/framework/com.qcom.bluetooth.jar' does not exist or contains no resources.
,W/ResourcesManager( 6053): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
D/BluetoothAdapterApp( 6053): Loading JNI Library
,D/SoftapController(  308): Softap fwReload - Ok
,D/CommandListener(  308): Setting iface cfg
D/CommandListener(  308): Trying to bring down wlan0
D/Tethering( 1030): sendTetherStateChangedBroadcast 1, 0, 0
D/CommandListener(  308): Clearing all IP addresses on wlan0
D/Tethering( 1030): InitialState.processMessage what=4
,D/libc-netbsd(  308): default dns: query_ipv6=0, query_ipv4=0
D/DSQN    ( 1030): DNSproblemNotiEnabled is disabled ignore DNS fail CB
,I/ActivityManager( 1030): Start proc com.android.settings for broadcast com.android.settings/.deviceinfo.UsbSettingsReceiver: pid=6091 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
D/Tethering( 1030): sendTetherStateChangedBroadcast 0, 0, 0
D/BluetoothAdapterApp( 6053): REFCOUNT: Constructed com.android.bluetooth.btservice.AdapterApp@28212f91 Instance Count = 1
E/WifiHW  ( 1030): Cannot open "/system/etc/wifi/autojoinconfig.txt": No such file or directory
,E/WifiStateMachine( 1030): Couldn't get getWiFiOffloadingIface : 
E/WifiStateMachine( 1030): useWiFiOffloading() : false
E/WifiStateMachine( 1030): CONFIG_LGE_WLAN_PATH : true
D/WifiMonitor( 1030): startMonitoring(wlan0) with mConnected = false
D/WifiMonitor( 1030): connecting to supplicant
I/WifiServerServiceExt( 1030): WIFI_STATE_CHANGED_ACTION [2]
V/WfdStateTracker( 1964): WfdStateTracker handleDirectStateChangedEvent: 1
D/StatusBar.NetworkController( 1472): refreshViews: Data not connected!! Set no data type icon / Roaming
W/wpa_supplicant( 6108): type=1400 audit(0.0:153): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6838 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
D/BluetoothAdapterApp( 6053): onCreate
W/wpa_supplicant( 6108): type=1400 audit(0.0:154): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6838 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,I/wpa_supplicant( 6108): Successfully initialized wpa_supplicant
,I/wpa_supplicant( 6108): rfkill: Cannot open RFKILL control device
I/wpa_supplicant( 6108): [LGE_PATCH] unset P2P_CAPABLE to ifname wlan0
D/ProfileConfigQcom( 6053): [BTUI] HeadsetService is supported
D/ProfileConfigQcom( 6053): Adding HeadsetService
D/ProfileConfigQcom( 6053): [BTUI] A2dpService is supported
D/ProfileConfigQcom( 6053): Adding A2dpService
D/ProfileConfigQcom( 6053): [BTUI] HidService is supported
D/ProfileConfigQcom( 6053): Adding HidService
D/ProfileConfigQcom( 6053): [BTUI] HealthService is supported
D/ProfileConfigQcom( 6053): Adding HealthService
D/LGBluetoothFeatureConfig( 6053): isSupportPan() :  mTargetOp=OPEN
D/ProfileConfigQcom( 6053): [BTUI] PanService is supported
D/ProfileConfigQcom( 6053): Adding PanService
D/ProfileConfigQcom( 6053): [BTUI] GattService is supported
D/ProfileConfigQcom( 6053): Adding GattService
D/ProfileConfigQcom( 6053): [BTUI] BluetoothMapService is supported
D/ProfileConfigQcom( 6053): Adding BluetoothMapService
D/ProfileConfigQcom( 6053): [BTUI] HeadsetClientService is NOT supported
W/ResourcesManager( 6091): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6091): Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
W/ResourcesManager( 6091): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 6091): Asset path '/system/framework/com.lge.bluetooth.jar' does not exist or contains no resources.
,W/ResourcesManager( 6091): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
W/ResourcesManager( 6091): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
D/BluetoothManagerService( 1030): Message: 20
D/BluetoothManagerService( 1030): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@35e2c845:true
,D/BluetoothAdapterState( 6053): make
I/LGFMServiceAdapter( 6053): [FM] LGFMServiceAdapter : create
I/bluedroid-qcom( 6053): init
I/BluetoothAdapterState( 6053): Entering OffState
I/bte_conf( 6053): bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
I/bte_conf( 6053): bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
E/bt_osi_config( 6053): config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
I/bte_conf( 6053): bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
D/BTIF_CORE( 6053): [BTUI] lge_load_bluetooth_address
I/bluedroid-qcom( 6053): get_profile_interface socket
I/bluedroid-qcom( 6053): get_profile_interface map_client
I/GKI_LINUX( 6053): gki_task_entry task_id=1 [BTIF] starting
D/BluetoothManagerService( 1030): BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
D/BluetoothManagerService( 1030): Message: 40
W/bdaddr_loader( 6114): type=1400 audit(0.0:155): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6838 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
W/bdaddr_loader( 6114): type=1400 audit(0.0:156): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6838 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
D/BluetoothManagerService( 1030): MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
,W/bdaddr_loader( 6114): type=1400 audit(0.0:156): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6838 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
D/BluetoothAdapterProperties( 6053): Address is:58:3F:54:73:64:C0
D/BluetoothManagerService( 1030): Bluetooth Adapter name changed to G3-1
D/BluetoothManagerService( 1030): Stored Bluetooth name: G3-1
D/BluetoothAdapterProperties( 6053): Name is: G3-1
I/bluedroid-qcom( 6053): config_hci_snoop_log
D/lge_bdaddr_loader( 6114): [BTUI] bdaddr_loader ::: START
D/lge_bdaddr_loader( 6114): [BTUI] bluetooth_load_bdaddress
I/LGFTMITEM( 6114): [GET_FTM][id=8], offset=16384
D/BluetoothManagerService( 1030): Calling onBluetoothServiceUp callbacks
D/lge_bdaddr_loader( 6114): [BTUI] bdaddr to set in property : 58:3F:54:73:64:C0
D/BluetoothManagerService( 1030): Broadcasting onBluetoothServiceUp() to 7 receivers.
V/LGMDMManagerInternal( 6053): Create singleton instance
E/lge_bdaddr_loader( 6114): [BTUI] bluetooth_load_bdaddress : OK => 58:3F:54:73:64:C0
D/lge_bdaddr_loader( 6114): [BTUI] bdaddr_loader ::: END
I/wpa_supplicant( 6108): rfkill: Cannot open RFKILL control device
,D/BluetoothAdapterState( 6053): CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
D/BluetoothAdapterProperties( 6053): Setting state to 11
I/BluetoothAdapterState( 6053): Bluetooth adapter state changed: 10-> 11
I/LGBluetoothServiceJni( 6053): classInitNative: succeeds
,D/BluetoothManagerService( 1030): Message: 60
D/BluetoothManagerService( 1030): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
,D/BluetoothManagerService( 1030): Bluetooth State Change Intent: 10 -> 11
D/BluetoothBondStateMachine( 6053): make
D/LGBluetoothAPIService( 1964): [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
I/[SystemUI]BluetoothHandler( 1472): Receive : BluetoothAdapter.ACTION_STATE_CHANGED
D/BluetoothAdapterService( 6053): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2dc453d0
D/LGBluetoothServiceAdapter( 6053): [BTUI] check adapter is available - false.
I/BluetoothBondStateMachine( 6053): StableState(): Entering Off State,
D/BluetoothAdapterService( 6053): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2dc453d0
D/LGBluetoothServiceAdapter( 6053): [BTUI] check adapter is available - true : set adapter available.
D/LGBluetoothSettingsDBObserver( 6053): [BTUI] register observer for LG device name DB
E/BluetoothAdapterService( 6053): File transfer profiles supported!!
,E/BluetoothAdapterService( 6053): File transfer profiles supported!!
D/BluetoothHeadset( 1866): Proxy object connected
D/BluetoothHeadset( 1866): Proxy object connected
D/BluetoothHeadset( 1866): Proxy object connected
D/HeadsetService( 6053): Received start request. Starting profile...
I/LGBluetoothHeadsetServiceJni( 6053): classInitNative: succeeds
D/LGBluetoothHfpAdapter( 6053): Version 1.6
D/LGBluetoothFeatureConfig( 6053): isPrivacyLogsEnabled : true
I/BluetoothHeadsetServiceJni( 6053): classInitNative: succeeds
D/BluetoothHeadset( 1030): Proxy object connected
D/HeadsetStateMachine( 6053): make
E/BluetoothAdapterService( 6053): File transfer profiles supported!!
,E/BluetoothAdapterService( 6053): File transfer profiles supported!!
E/BluetoothAdapterService( 6053): File transfer profiles supported!!
E/BluetoothAdapterService( 6053): File transfer profiles supported!!
,E/BluetoothAdapterService( 6053): File transfer profiles supported!!
D/UsbSettingsReceiver( 6091): [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
D/UsbSettingsReceiver( 6091): [AUTORUN] sys.usb.config = ptp_only,adb
D/UsbSettingsReceiver( 6091): [AUTORUN] sys.usb.state = ptp_only,adb
D/UsbSettingsReceiver( 6091): [AUTORUN] persist.sys.usb.config = ptp_only,adb
D/UsbSettingsReceiver( 6091): [AUTORUN] onReceive() : app userid = 0, current userid = 0
,I/wpa_supplicant( 6108): [LGE_WLAN_PATCH]P2P 5GHz support level:2(0:no 1:gconly 2:gconly_UNII1 3:full)
D/UsbSettingsControl( 6091): [AUTORUN] getUsbConnected() : connected=true
D/UsbSettingsReceiver( 6091): [AUTORUN] onReceive() : availableList=[wlan0]
D/UsbSettingsReceiver( 6091): [AUTORUN] onReceive() : activeList=[]
D/UsbSettingsReceiver( 6091): [AUTORUN] onReceive() : errorList=[]
D/UsbSettingsControl( 6091): [AUTORUN] isAutorunTimer() : mAutorunChanging=false
D/LgDataFeature( 6053): LgDataFeature() Constructor: none
D/UsbSettingsReceiver( 6091): [AUTORUN] onReceive() : TetherState Changed=wlan0
D/LgDataFeature( 6053): LgDataFeature() Constructor Done, null
D/UsbSettingsControl( 6091): [AUTORUN] setTetherStatus() : status=false
I/wpa_supplicant( 6108): p2p0: CTRL-EVENT-AVOID-FREQ ranges=
I/ActivityManager( 1030): Killing 5654:com.android.defcontainer/u0a4 (adj 15): empty #17
I/wpa_supplicant( 6108): wlan0: CTRL-EVENT-SCAN-STARTED 
V/LGMDMManager( 6053): Create singleton instance
E/WifiStateMachine( 1030):  SupplicantStartingState CMD_SET_OPERATIONAL_MODE 1 0
I/BluetoothAdapterState( 6053): Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
E/WifiStateMachine( 1030):  SupplicantStartingState CMD_START_DRIVER 0 0
E/WifiStateMachine( 1030):  SupplicantStartingState CMD_SET_HIGH_PERF_MODE 0 0
E/WifiStateMachine( 1030):  DefaultState CMD_SET_HIGH_PERF_MODE 0 0
E/WifiStateMachine( 1030):  SupplicantStartingState CMD_DISCONNECT 0 0
,E/WifiStateMachine( 1030):  DefaultState CMD_DISCONNECT 0 0
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
E/WifiStateMachine( 1030): Couldn't get getWiFiOffloadingIface : 
E/WifiStateMachine( 1030): useWiFiOffloading() : false
E/WifiStateMachine( 1030): CONFIG_LGE_WLAN_PATH : true
W/Settings( 1030): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/HeadsetStateMachine( 6053): max_hf_connections = 1
W/Settings( 1030): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/bluedroid-qcom( 6053): get_profile_interface handsfree
W/libprocessgroup( 1030): failed to open /acct/uid_10004/pid_5654/cgroup.procs: No such file or directory
,V/ToneGenerator( 6053): ToneGenerator constructor: streamType=8, volume=1.000000
V/AudioPolicyService(  313): registerClient() client 0xb1427960, uid 1002
V/AudioPolicyManager(  313): getOutput() device 2, stream 8, samplingRate 0, format 0, channelMask 3, flags 0
V/AudioPolicyManagerEx(  313): AudioPolicyManagerEx: getOutputForDevice
V/AudioPolicyManagerEx(  313): getOutput() returns output 2
V/AudioSystem( 6053): getOutputSamplingRate() no output descriptor for output 2 in gOutputs
D/WifiNative-wlan0( 1030): doBoolean: SET update_config 1
D/WifiNative-wlan0( 1030): SET update_config 1: returned true
I/WifiServerServiceExt( 1030): WIFI_STATE_CHANGED_ACTION [3]
D/WifiConfigStore( 1030): Loading config and enabling all networks 
D/WifiNative-wlan0( 1030): doString: [LIST_NETWORKS]
D/StatusBar.NetworkController( 1472): refreshViews: Data not connected!! Set no data type icon / Roaming
I/WifiServerServiceExt( 1030): batteryPsActivateMsgHandler : state:0 event:3
V/AudioFlinger(  313): registerClient() client 0xb55816b8, pid 6053
V/AudioSystem(  313): ioConfigChanged() event 0, ioHandle 2
V/AudioSystem(  313): ioConfigChanged() opening already existing output! 2
V/AudioSystem( 1472): ioConfigChanged() event 0, ioHandle 2
V/AudioSystem( 1472): ioConfigChanged() opening already existing output! 2
V/AudioSystem( 2210): ioConfigChanged() event 0, ioHandle 2
,V/AudioSystem( 2210): ioConfigChanged() opening already existing output! 2
V/AudioSystem( 3300): ioConfigChanged() event 0, ioHandle 2
V/AudioSystem( 3300): ioConfigChanged() opening already existing output! 2
V/AudioSystem( 6053): ioConfigChanged() event 0, ioHandle 2
V/AudioSystem(  313): ioConfigChanged() event 0, ioHandle 4
V/AudioSystem(  313): ioConfigChanged() opening already existing output! 4
V/AudioSystem( 2210): ioConfigChanged() event 0, ioHandle 4
,V/AudioSystem( 2210): ioConfigChanged() opening already existing output! 4
V/ToneGenerator( 6053): Create Track: 0xb4928080
V/AudioTrack( 6053): set(): streamType 8, sampleRate 0, format 0x1, channelMask 0x1, frameCount 0, flags #4, notificationFrames 0, sessionId 0, transferType 1
,V/AudioTrack( 6053): set() streamType 8, sampleRate 0, format 1, frameCount 0, flags 0004
V/AudioPolicyManager(  313): getOutputForAttr() usage=3, content=4, tag= flags=00000000
V/AudioPolicyManager(  313): getOutputForAttr() device 2, samplingRate 0, format 0, channelMask 3, flags 0
V/AudioPolicyManagerEx(  313): AudioPolicyManagerEx: getOutputForDevice
V/AudioPolicyManagerEx(  313): getOutput() returns output 2
V/AudioSystem( 6053): getOutputSamplingRate() no output descriptor for output 2 in gOutputs
V/AudioSystem( 6053): ioConfigChanged() new output samplingRate 48000, format 0x5 channel mask 0x3 frameCount 960 latency 50
D/WfdService( 1964): Waiting for WifiP2p enabling
D/WifiNative-wlan0( 1030):    returned network id / ssid / bssid / flags 0	NG700	any	
V/AudioSystem( 1030): ioConfigChanged() event 0, ioHandle 2
V/AudioSystem( 1030): ioConfigChanged() opening already existing output! 2
V/AudioSystem( 6053): ioConfigChanged() event 0, ioHandle 4
V/AudioSystem( 6053): ioConfigChanged() new output samplingRate 48000, format 0x1 channel mask 0x3 frameCount 960 latency 80
V/AudioSystem( 1030): ioConfigChanged() event 0, ioHandle 4
V/AudioSystem( 1030): ioConfigChanged() opening already existing output! 4
I/AudioFlinger(  313): isAudioPlaybackHookOn() false
V/AudioPolicyManager(  313): getOutputForAttr() usage=3, content=4, tag= flags=00000000
V/AudioPolicyManager(  313): getOutputForAttr() device 2, samplingRate 48000, format 1, channelMask 1, flags 4
V/AudioPolicyManagerEx(  313): AudioPolicyManagerEx: getOutputForDevice
V/AudioPolicyManagerEx(  313): getOutput() returns output 2
V/AudioSystem( 6053): getLatency() output 2, latency 50
V/AudioSystem( 6053): getFrameCount() output 2, frameCount 960
V/AudioTrack( 6053): createTrack_l() output 2 afLatency 50
V/AudioFlinger(  313): [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
V/AudioFlinger(  313): [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
V/AudioFlinger(  313): [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
V/AudioFlinger(  313): [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
V/AudioFlinger(  313): createTrack() lSessionId: 16
V/AudioSystem( 1472): ioConfigChanged() event 0, ioHandle 4
V/AudioSystem( 1472): ioConfigChanged() opening already existing output! 4
V/AudioSystem( 3300): ioConfigChanged() event 0, ioHandle 4
V/AudioSystem( 3300): ioConfigChanged() opening already existing output! 4
V/AudioSystem( 1866): ioConfigChanged() event 0, ioHandle 2
V/AudioSystem( 1866): ioConfigChanged() opening already existing output! 2
V/AudioSystem( 1866): ioConfigChanged() event 0, ioHandle 4
V/AudioSystem( 1866): ioConfigChanged() opening already existing output! 4
V/AudioTrack( 6053): AUDIO_OUTPUT_FLAG_FAST successful; frameCount 480
V/AudioFlinger(  313): acquiring 16 from 6053, for 6053
V/AudioFlinger(  313):  added new entry for 16
V/ToneGenerator( 6053): ToneGenerator INIT OK, time: 115757
D/BluetoothAdapterService( 6053): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2dc453d0
D/BluetoothAdapterService( 6053): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2dc453d0
D/HeadsetStateMachine( 6053): Enter Disconnected: -2, size: 0
D/UsbSettingsReceiver( 6091): [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
D/UsbSettingsReceiver( 6091): [AUTORUN] sys.usb.config = ptp_only,adb
D/UsbSettingsReceiver( 6091): [AUTORUN] sys.usb.state = ptp_only,adb
D/UsbSettingsReceiver( 6091): [AUTORUN] persist.sys.usb.config = ptp_only,adb
D/UsbSettingsReceiver( 6091): [AUTORUN] onReceive() : app userid = 0, current userid = 0
D/HeadsetPhoneState( 6053): [BTUI] listenForPhoneState : start = false
D/UsbSettingsControl( 6091): [AUTORUN] getUsbConnected() : connected=true
D/LGBluetoothHfpManager( 6053): [BTUI] listenForMultiSimPhoneState : start = false
D/UsbSettingsReceiver( 6091): [AUTORUN] onReceive() : availableList=[]
D/UsbSettingsReceiver( 6091): [AUTORUN] onReceive() : activeLis,t=[]
D/UsbSettingsReceiver( 6091): [AUTORUN] onReceive() : errorList=[]
D/HeadsetStateMachine( 6053): [BTUI] change sampling rate to 8000 when device is disconnected
D/UsbSettingsControl( 6091): [AUTORUN] isAutorunTimer() : mAutorunChanging=false
D/UsbSettingsControl( 6091): [AUTORUN] setTetherStatus() : status=false
V/AudioFlinger(  313): setParameters(): io 0, keyvalue bt_samplerate=8000, calling pid 6053
D/audio_hw_primary(  313): adev_set_parameters: enter: bt_samplerate=8000
V/voice   (  313): voice_set_parameters: enter: bt_samplerate=8000
V/compress_voip(  313): voice_extn_compress_voip_set_parameters: enter: bt_samplerate=8000
V/compress_voip(  313): voice_extn_compress_voip_set_parameters: exit
V/voice   (  313): voice_set_parameters: exit with code(0)
V/msm8974_platform_lge(  313): LGE_platform_set_parameters: enter: bt_samplerate=8000
V/msm8974_platform(  313): platform_set_parameters: enter: bt_samplerate=8000
V/msm8974_platform(  313): platform_set_parameters: exit with code(0)
V/lge_audio_loopback(  313): lge_platform_set_loopback_parameters: enter: 
V/audio_hw_primary(  313): adev_set_parameters: exit with code(0)
E/audio_a2dp_hw(  313): adev_set_parameters: ERROR: set param called even when stream out is null
V/ToneGenerator( 6053): ToneGenerator destructor
V/ToneGenerator( 6053): stopTone
V/ToneGenerator( 6053): Delete Track: 0xb4928080
V/AudioTrack( 6053): ~AudioTrack, releasing session id from 6053 on behalf of 6053
V/AudioFlinger(  313): releasing 16 from 6053 for 6053
V/AudioFlinger(  313):  decremented refcount to 0
V/AudioFlinger(  313): purging stale effects
V/AudioPolicyService(  313): AudioCommandThread() adding release output 2
V/AudioPolicyService(  313): inserting command: 6 at index 0, num commands 0
V/AudioPolicyService(  313): AudioCommandThread() waking up
V/AudioPolicyService(  313): AudioCommandThread() processing release output 2
V/AudioPolicyManager(  313): releaseOutput() 2
V/AudioPolicyService(  313): AudioCommandThread() going to sleep
V/AudioFlinger(  313): PlaybackThread::Track destructor
V/AudioFlinger(  313): removeClient_l() pid 6053, calling pid 313
E/WifiConfigStore( 1030): readNetworkVariablesFromSupplicantFile key=psk
E/WifiConfigStore( 1030): readNetworkVariableFromSupplicantFile ssid=["NG700"] key=psk
E/WifiConfigStore( 1030): Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
I/ActivityManager( 1030): Start proc com.lge.formmanager for broadcast com.lge.formmanager/.FormServiceReceiver: pid=6121 uid=10026 gids={50026, 9997, 3003, 1028} abi=armeabi-v7a
,D/BluetoothA2dp( 1030): Proxy object connected
D/A2dpService( 6053): Received start request. Starting profile...
D/WifiStateMachine( 1030): enableVerboseLogging : level 2
D/WifiNative-wlan0( 1030): doBoolean: SET device_name g3_global_com
I/BluetoothAvrcpServiceJni( 6053): classInitNative: succeeds
D/WifiNative-wlan0( 1030): SET device_name g3_global_com: returned true
D/WifiNative-wlan0( 1030): doBoolean: SET manufacturer LGE
V/Avrcp   ( 6053): make
D/WifiNative-wlan0( 1030): SET manufacturer LGE: returned true
D/WifiNative-wlan0( 1030): doBoolean: SET model_name LG-D855
D/Avrcp   ( 6053): [BTUI] Use Native AVRCP : init jni
I/bluedroid-qcom( 6053): get_profile_interface avrcp
D/WifiNative-wlan0( 1030): SET model_name LG-D855: returned true
D/WifiNative-wlan0( 1030): doBoolean: SET model_number LG-D855
D/WifiNative-wlan0( 1030): SET model_number LG-D855: returned true
D/WifiNative-wlan0( 1030): doBoolean: SET serial_number LGD8553bed2d08
D/WifiNative-wlan0( 1030): SET serial_number LGD8553bed2d08: returned true
D/WifiNative-wlan0( 1030): doBoolean: SET config_methods physical_display virtual_push_button
D/WifiNative-wlan0( 1030): SET config_methods physical_display virtual_push_button: returned true
D/WifiNative-wlan0( 1030): doBoolean: SET device_type 10-0050F204-5
D/WifiNative-wlan0( 1030): SET device_type 10-0050F204-5: returned true
D/WifiStateMachine( 1030): Setting OUI to DA-A1-19
D/WifiNative-wlan0( 1030): doBoolean: SCAN_INTERVAL 120
D/WfdsService( 1964): Supplicant Connection state is changed : true
D/WfdsService( 1964): DefaultState - WIFI_SUPPLICANT_CONNECTED
D/WfdsService( 1964): Set the WFDS Monitor: true
D/WifiNative-wlan0( 1030): SCAN_INTERVAL 120: returned true
D/WifiNative-HAL( 1030): Setting external_sim to 1
D/WfdsMonitor( 1964): WfdsMonitorThread create
D/WfdsMonitor( 1964): WFDS Monitor is created and started
D/WfdsService( 1964): WiFi: Supplicant connection re-established
D/WifiNative-wlan0( 1030): doBoolean: SET external_sim 1
D/WifiNative-wlan0( 1030): SET external_sim 1: returned true
I/WifiNative-HAL( 1030): startHal
E/wifi    ( 1030): getStaticLongField sWifiHalHandle 0x9884f8dc
E/WifiHAL ( 1030): Could not connect handle
D/wifi    ( 1030): halHandle = 0x0, mVM = 0xb487c280, mCls = 0x10225e
I/WifiNative-HAL( 1030): Could not start hal
D/WifiStateMachine( 1030): Setting OUI to DA-A1-19
I/WifiNative-HAL( 1030): startHal
E/wifi    ( 1030): getStaticLongField sWifiHalHandle 0x9884f85c
E/WifiHAL ( 1030): Could not connect handle
D/wifi    ( 1030): halHandle = 0x0, mVM = 0xb487c280, mCls = 0x102262
I/WifiNative-HAL( 1030): Could not start hal
D/WifiNative-wlan0( 1030): doBoolean: STA_AUTOCONNECT 1
D/WifiNative-wlan0( 1030): STA_AUTOCONNECT 1: returned true
D/WifiNative-wlan0( 1030): doBoolean: DRIVER BTCOEXSCAN-STOP
I/wpa_supplicant( 6108): wpa_driver_nl80211_ext_driver_cmd BTCOEXSCAN-STOP
V/AudioManager( 6053): registerRemoteController: size of Media player list: 0
D/WifiNative-wlan0( 1030): DRIVER BTCOEXSCAN-STOP: returned true
D/WifiHS20( 1030): hidePasspointNotification off =false
W/Settings( 1030): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1030): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1030): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
I/StatusBar.NetworkController( 1472): networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1472): mWifiConnected = false, mWifiLevel = 0
D/WifiNative-wlan0( 1030): doBoolean: DRIVER RXFILTER-STOP
E/AudioManager( 6053): No RCC entry present to update
I/wpa_supplicant( 6108): wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
E/RemoteController( 6053): Cannot set synchronization mode on an unregistered ,RemoteController
D/WifiNative-wlan0( 1030): DRIVER RXFILTER-STOP: returned true
D/WifiNative-wlan0( 1030): doBoolean: DRIVER RXFILTER-REMOVE 3
I/wpa_supplicant( 6108): wpa_driver_nl80211_ext_driver_cmd RXFILTER-REMOVE 3
D/WifiNative-wlan0( 1030): DRIVER RXFILTER-REMOVE 3: returned true
D/WifiNative-wlan0( 1030): doBoolean: DRIVER RXFILTER-START
I/wpa_supplicant( 6108): wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
D/WifiNative-wlan0( 1030): DRIVER RXFILTER-START: returned true
D/WifiNative-wlan0( 1030): doBoolean: DRIVER RXFILTER-STOP
I/wpa_supplicant( 6108): wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
D/WifiNative-wlan0( 1030): DRIVER RXFILTER-STOP: returned true
D/WifiNative-wlan0( 1030): doBoolean: DRIVER RXFILTER-REMOVE 2
I/wpa_supplicant( 6108): android_multicast_filter_startstop : multicast filter set
D/WifiNative-wlan0( 1030): DRIVER RXFILTER-REMOVE 2: returned true
D/WifiNative-wlan0( 1030): doBoolean: DRIVER RXFILTER-START
I/wpa_supplicant( 6108): wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
D/WifiNative-wlan0( 1030): DRIVER RXFILTER-START: returned true
D/StatusBar.NetworkController( 1472): refreshViews: Data not connected!! Set no data type icon / Roaming
I/BluetoothAvrcpQcomServiceJni( 6053): classInitQcomNative: succeeds
D/LGBluetoothAvrcpQcomAdapter( 6053): [BTUI] Use QCOM AVRCP 1.5 : init jni, browsing = false
I/BluetoothAvrcpQcomServiceJni( 6053): initQcomNative: succeeds
E/WifiNative: ( 1030): [115,803,699 us] RECONNECT  stack:logDbg - reconnect - enter - invokeEnterMethods - performTransitions
E/CtrlSupplicant( 1964): Access OK "@android:wpa_wlan0"
E/CtrlSupplicant( 1964): Succeed to open control connection
E/CtrlSupplicant( 1964): Succeed to open monitor connection
D/LGBluetoothAvrcpQcomAdapter( 6053): [BTUI] [+] updateMediaPlayerInfo
D/WifiService( 1030): New client listening to asynchronous messages
D/WifiNative-wlan0( 1030): doBoolean: RECONNECT
D/WifiNative-wlan0( 1030): RECONNECT: returned true
D/WifiNative-wlan0( 1030): doString: [STATUS]
D/WfdsMonitor( 1964): Supplicant connection established
D/WfdsService( 1964): Connected to the supplicant for wfds
D/WifiMonitor( 1030): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
E/WifiMonitor( 1030): WifiMonitor:wlan0 cnt=1 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
D/WifiNative-wlan0( 1030):    returned wpa_state=SCANNING p2p_device_address=02:9a:02:7b:60:ac address=c4:9a:02:7b:60:ac uuid=530d3fd0-1ba3-5409-a336-ff4e42af59a2
D/WifiNative-wlan0( 1030): doBoolean: DRIVER SETSUSPENDMODE 1
I/wpa_supplicant( 6108): wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 1
D/WifiNative-wlan0( 1030): DRIVER SETSUSPENDMODE 1: returned true
D/WifiNative-wlan0( 1030): doBoolean: SET ps 1
D/WifiNative-wlan0( 1030): SET ps 1: returned true
D/LGWifiP2pService( 1030): P2pDisabledState{ when=0 what=131203 target=com.android.internal.util.StateMachine$SmHandler }
,D/CommandListener(  308): Setting iface cfg
D/CommandListener(  308): Trying to bring up p2p0
D/WifiMonitor( 1030): startMonitoring(p2p0) with mConnected = true
D/LGWifiP2pService( 1030): P2pEnablingState
D/LGWifiP2pService( 1030): P2pEnablingState{ when=0 what=147457 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1030): P2p socket connection successful
D/LGWifiP2pService( 1030): P2pEnabledState
E/WifiStateMachine( 1030):  DisconnectedState CMD_SET_OPERATIONAL_MODE 1 0
E/WifiStateMachine( 1030):  DisconnectedState CMD_START_DRIVER 0 0
E/WifiStateMachine( 1030):  ConnectModeState CMD_START_DRIVER 0 0
E/WifiStateMachine( 1030):  DriverStartedState CMD_START_DRIVER 0 0
E/WifiStateMachine( 1030):  DisconnectedState what:132106 1 0
E/WifiStateMachine( 1030):  ConnectModeState what:132106 1 0
E/WifiStateMachine( 1030):  DriverStartedState what:132106 1 0
I/WifiServerServiceExt( 1030): setWifiDualbandAPConnection band : 1
E/wpa_supplicant( 6108): nWIFIDualbandAPConnection: 1
D/WifiScanningService( 1030): SCAN_AVAILABLE : 3
D/RttService( 1030): SCAN_AVAILABLE : 3
,D/WifiScanningService( 1030): DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
I/WifiNative-HAL( 1030): startHal
E/wifi    ( 1030): getStaticLongField sWifiHalHandle 0x94de499c
E/WifiHAL ( 1030): Could not connect handle
D/wifi    ( 1030): halHandle = 0x0, mVM = 0xb487c280, mCls = 0x102286
I/WifiNative-HAL( 1030): Could not start hal
E/WifiScanningService( 1030): could not start HAL
D/LGWifiP2pService( 1030): sending p2p connection changed broadcast
D/RttService( 1030): DefaultState got{ when=-1ms what=160512 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiStateMachine( 1030):  DisconnectedState what:132096 -100 0
D/WifiNative-p2p0( 1030): doBoolean: SET persistent_reconnect 1
E/WifiStateMachine( 1030):  ConnectModeState what:132096 -100 0
E/WifiStateMachine( 1030):  DriverStartedState what:132096 -100 0
I/WifiServerServiceExt( 1030): set CMD_DISCONNECT_RSSI_LVL : -100
V/WfdStateTracker( 1964): WfdStateTracker handleDirectStateChangedEvent: 2
D/WfdsService( 1964): WifiP2pState is changed : true
E/wpa_supplicant( 6108): disconnect_rssi_lvl: -100
D/WfdsService( 1964): Receive the WFDS_ENABLE Method
D/WfdsService( 1964): Set the WFDS Monitor: true
D/WfdsService( 1964): Connected to the supplicant for wfds
D/WfdsJNI ( 1964): doCommand: WFDS_SET TRUE
I/wpa_supplicant( 6108): WFDS: wfds_supplicant_wfds_cmd: cmd = SET TRUE
D/WfdsJNI ( 1964): doCommand: WFDS_GET_MAC_ADDRESS
I/wpa_supplicant( 6108): WFDS: wfds_supplicant_wfds_cmd: cmd = GET_MAC_ADDRESS
E/WifiStateMachine( 1030):  DisconnectedState CMD_SET_COUNTRY_CODE 1 0 cz
D/WfdsJNI ( 1964): doCommand: IFNAME=wlan0 GET_CAPABILITY channels
D/WfdsService( 1964): selectPreferredScanChannel [36]
D/WfdsService( 1964): STATE : WfdsEnabledState - enter: this device mac 02:9a:02:7b:60:ac
E/WifiStateMachine( 1030):  ConnectModeState CMD_SET_COUNTRY_CODE 1 0 cz
D/WifiNative-p2p0( 1030): SET persistent_reconnect 1: returned true
D/WifiNative-p2p0( 1030): doBoolean: SET device_name G3-1
D/WfdsService( 1964): WIFI_P2P_CONNECTION_CHANGED_ACTION
E/WifiStateMachine( 1030):  DriverStartedState CMD_SET_COUNTRY_CODE 1 0 cz
D/WifiNative-p2p0( 1030): SET device_name G3-1: returned true
D/WifiNative-wlan0( 1030): doBoolean: DRIVER COUNTRY CZ
D/LGWifiP2pService( 1030): [LGE_P2P] initializeP2pSettings() check postfix
D/LGWifiP2pService( 1030): before postfix = G3-1
I/wpa_supplicant( 6108): wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
D/WifiServerServiceExt( 1030): postfix byte check : 4
I/wpa_supplicant( 6108): wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
I/wpa_supplicant( 6108): [LGE_PATCH] driver_cmd() country:CZ
I/wpa_supplicant( 6108): p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
I/wpa_supplicant( 6108): p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
D/WifiNative-wlan0( 1030): DRIVER COUNTRY CZ: returned true
D/WfdsMonitor( 1964): Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
D/WfdsMonitor( 1964): Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
D/WifiMonitor( 1030): Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
E/WifiMonitor( 1030): WifiMonitor:wlan0 cnt=2 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
D/WfdsService( 1964): isConnected: false
D/LGWifiP2pService( 1030): after postfix = G3-1
E/WifiMonitor( 1030): handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
E/WifiMonitor( 1030): handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
D/WifiMonitor( 1030): Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
E/WifiMonitor( 1030): WifiMonitor:p2p0 cnt=3 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
E/WifiMonitor( 1030): handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
E/WifiMonitor( 1030): handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
D/WifiMonitor( 1030): Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
E/WifiMonitor( 1030): W,ifiMonitor:p2p0 cnt=4 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
E/WifiMonitor( 1030): handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
E/WifiMonitor( 1030): handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
D/WifiNative-p2p0( 1030): doBoolean: SET p2p_ssid_postfix -G3-1
E/WifiStateMachine( 1030):  DisconnectedState CMD_SET_FREQUENCY_BAND 0 0
D/WifiNative-p2p0( 1030): SET p2p_ssid_postfix -G3-1: returned true
D/WifiNative-p2p0( 1030): doBoolean: SET device_type 10-0050F204-5
D/WifiNative-p2p0( 1030): SET device_type 10-0050F204-5: returned true
D/WifiNative-p2p0( 1030): doBoolean: SET config_methods virtual_push_button physical_display keypad
E/WifiStateMachine( 1030):  ConnectModeState CMD_SET_FREQUENCY_BAND 0 0
D/WifiNative-p2p0( 1030): SET config_methods virtual_push_button physical_display keypad: returned true
D/WifiNative-p2p0( 1030): doBoolean: P2P_SET conc_pref p2p
E/WifiStateMachine( 1030):  DriverStartedState CMD_SET_FREQUENCY_BAND 0 0
D/WifiNative-p2p0( 1030): P2P_SET conc_pref p2p: returned true
D/WifiNative-wlan0( 1030): doBoolean: DRIVER SETBAND 0
I/wpa_supplicant( 6108): wpa_driver_nl80211_ext_driver_cmd SETBAND 0 - interface name wlan0
I/wpa_supplicant( 6108): wlan0: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
D/WifiMonitor( 1030): Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN]
E/WifiMonitor( 1030): WifiMonitor:wlan0 cnt=5 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
E/WifiMonitor( 1030): handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
D/WifiNative-wlan0( 1030): DRIVER SETBAND 0: returned true
E/WifiMonitor( 1030): handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
D/WifiNative-HAL( 1030): p2pGetDeviceAddress
D/WifiNative-wlan0( 1030): doBoolean: BSS_FLUSH 0
D/WifiNative-HAL( 1030): p2pGetDeviceAddress returning 02:9a:02:7b:60:ac
D/LGWifiP2pService( 1030): DeviceAddress: 02:9a:02:7b:60:ac
D/WifiNative-p2p0( 1030): doBoolean: P2P_FLUSH
D/WifiNative-p2p0( 1030): P2P_FLUSH: returned true
D/WifiNative-p2p0( 1030): doBoolean: P2P_SERVICE_FLUSH
I/WfdStateTracker( 1964): handleP2pThisDeviceChanged
D/WfdsService( 1964): WIFI_P2P_THIS_DEVICE_CHANGED_ATCION
D/WfdsService( 1964): Update P2p Interface State: 3
D/WifiNative-p2p0( 1030): P2P_SERVICE_FLUSH: returned true
D/WifiNative-p2p0( 1030): doString: [LIST_NETWORKS]
D/WifiNative-p2p0( 1030):    returned network id / ssid / bssid / flags
D/WifiNative-p2p0( 1030): doBoolean: SAVE_CONFIG
D/WifiNative-wlan0( 1030): BSS_FLUSH 0: returned true
D/WifiNative-wlan0( 1030): doBoolean: SCAN
D/WifiNative-wlan0( 1030): SCAN: returned false
E/WifiStateMachine( 1030):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 1 0 rt=115880  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
E/WifiStateMachine( 1030):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 1 0 rt=115882  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
I/StatusBar.NetworkController( 1472): networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1472): mWifiConnected = false, mWifiLevel = 0
E/WifiStateMachine( 1030):  DisconnectedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
W/Settings( 1030): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/StatusBar.NetworkController( 1472): refreshViews: Data not connected!! Set no data type icon / Roaming
W/Settings( 1030): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1030): NETWORK_STATE_CHANGED_ACTION [SCANNING]
E/WifiStateMachine( 1030):  ConnectModeState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
,D/WifiNative-p2p0( 1030): SAVE_CONFIG: returned true
D/LGWifiP2pService( 1030): sending p2p persistent groups changed broadcast
D/LGWifiP2pService( 1030): InactiveState
D/LGWifiP2pService( 1030): InactiveState{ when=-18ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1030): P2pEnabledState{ when=-18ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-p2p0( 1030): doBoolean: DRIVER COUNTRY CZ
I/wpa_supplicant( 6108): wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
I/wpa_supplicant( 6108): p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
E/WifiStateMachine( 1030):  DriverStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
D/WfdsMonitor( 1964): Event [CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
D/WifiMonitor( 1030): Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
E/WifiMonitor( 1030): WifiMonitor:p2p0 cnt=6 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
E/WifiMonitor( 1030): handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
E/WifiMonitor( 1030): handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
E/WifiStateMachine( 1030):  SupplicantStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
E/WifiStateMachine( 1030):  DefaultState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
I/wpa_supplicant( 6108): [LGE_PATCH] driver_cmd() country:CZ
I/wpa_supplicant( 6108): p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
D/WfdsMonitor( 1964): Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
D/WifiMonitor( 1030): Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
E/WifiMonitor( 1030): WifiMonitor:p2p0 cnt=7 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
E/WifiMonitor( 1030): handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
E/WifiMonitor( 1030): handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
I/wpa_supplicant( 6108): p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
D/WifiServerServiceExt( 1030): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1030): setSupplicantStateSCANNING
D/WfdsMonitor( 1964): Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
D/WifiMonitor( 1030): Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
E/WifiMonitor( 1030): WifiMonitor:p2p0 cnt=8 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
E/WifiMonitor( 1030): handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
E/WifiMonitor( 1030): handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
D/WifiNative-p2p0( 1030): DRIVER COUNTRY CZ: returned true
D/LGWifiP2pService( 1030): InactiveState{ when=-15ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1030): P2pEnabledState{ when=-15ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1030): InactiveState{ when=-4ms what=139287 arg2=1 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1030): P2pEnabledState{ when=-4ms what=139287 arg2=1 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1030): DefaultState{ when=-4ms what=139287 arg2=1 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1030): InactiveState{ when=0 what=139285 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1030): P2pEnabledState{ when=0 what=139285 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1030): DefaultState{ when=0 what=139285 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1030): InactiveState{ when=-1ms what=139287 arg2=1 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1030): P2pEnabledState{ when=-1ms what=139287 arg2=1 target=com.android.internal.util.StateMachine$SmHandler }
D/LGW,ifiP2pService( 1030): DefaultState{ when=-1ms what=139287 arg2=1 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1030): InactiveState{ when=-1ms what=139283 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1030): P2pEnabledState{ when=-1ms what=139283 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1030): DefaultState{ when=-1ms what=139283 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
W/WfdsService( 1964): DefaultState - msg [9441285] is not handled
E/WifiServerServiceExt( 1030): No p2p device connected
V/SIM_STK ( 1030): Menu title from STK is T-Mobile
V/SIM_STK ( 1030): Menu title from STK is T-Mobile
,I/ActivityManager( 1030): Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=6146 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,W/FormManager( 6121): Network not available. Please check & try again.
V/FormManager( 6121): Network unavailable.
V/FormManager( 6121): Network unavailable.
,W/ActivityManager( 1030): getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
D/LGBluetoothAvrcpQcomAdapter( 6053): [BTUI] installed app name: Music
D/LGBluetoothAvrcpQcomAdapter( 6053): [BTUI] installed app name: Google Play Music
D/LGBluetoothAvrcpQcomAdapter( 6053): [BTUI] === MediaPlayerInfo (playerId:0) ===
D/LGBluetoothAvrcpQcomAdapter( 6053): [BTUI]          displayName: Music
D/LGBluetoothAvrcpQcomAdapter( 6053): [BTUI]          packageName: com.lge.music
D/LGBluetoothAvrcpQcomAdapter( 6053): [BTUI]          playState: 2 (PAUSED)
D/LGBluetoothAvrcpQcomAdapter( 6053): [BTUI] === MediaPlayerInfo (playerId:1) ===
D/LGBluetoothAvrcpQcomAdapter( 6053): [BTUI]          displayName: Google Play Music
D/LGBluetoothAvrcpQcomAdapter( 6053): [BTUI]          packageName: com.google.android.music
D/LGBluetoothAvrcpQcomAdapter( 6053): [BTUI]          playState: 2 (PAUSED)
D/LGBluetoothAvrcpQcomAdapter( 6053): [BTUI] [-] updateMediaPlayerInfo
I/BluetoothA2dpServiceJni( 6053): classInitNative
I/BluetoothA2dpServiceJni( 6053): classInitNative: succeeds
D/A2dpStateMachine( 6053): make
I/bluedroid-qcom( 6053): get_profile_interface a2dp
I/GKI_LINUX( 6053): gki_task_entry task_id=2 [A2DP-MEDIA] starting
I/LGBluetoothA2dpServiceJni( 6053): classInitNative: succeeds
I/LGBluetoothA2dpAdapter( 6053): [BTUI] getInstance : create [LGBluetoothA2dpAdapter]
,D/BluetoothAdapterService( 6053): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2dc453d0
I/BluetoothHidServiceJni( 6053): classInitNative: succeeds
I/ActivityManager( 1030): Killing 5761:com.google.android.partnersetup/u0a8 (adj 15): empty #17
D/A2dpStateMachine( 6053): Enter Disconnected: -2
D/HidService( 6053): Received start request. Starting profile...
I/bluedroid-qcom( 6053): get_profile_interface hidhost
D/BluetoothAdapterService( 6053): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2dc453d0
I/BluetoothHealthServiceJni( 6053): classInitNative: succeeds
D/HealthService( 6053): Received start request. Starting profile...
I/bluedroid-qcom( 6053): get_profile_interface health
I/LGBluetoothHealthServiceJni( 6053): classInitNative: succeeds
D/BluetoothAdapterService( 6053): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2dc453d0
I/BluetoothPanServiceJni( 6053): classInitNative(L105): succeeds
D/PanService( 6053): Received start request. Starting profile...
D/BluetoothPanServiceJni( 6053): initializeNative(L110): pan
I/bluedroid-qcom( 6053): get_profile_interface pan
,D/PCSuite ( 6146): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,I/art     ( 1030): Explicit concurrent mark sweep GC freed 37930(1959KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 43MB/65MB, paused 1.989ms total 72.542ms
,I/LGBluetoothPanAdapter( 6053): [BTUI] getInstance : create [LGBluetoothPanAdapter]
D/BluetoothAdapterService( 6053): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2dc453d0
,I/BtGatt.JNI( 6053): classInitNative(L901): classInitNative: Success!
W/libprocessgroup( 1030): failed to open /acct/uid_10008/pid_5761/cgroup.procs: No such file or directory
D/BtGatt.DebugUtils( 6053): handleDebugAction() action=null
D/BtGatt.GattService( 6053): Received start request. Starting profile...
D/BtGatt.GattService( 6053): start()
I/bluedroid-qcom( 6053): get_profile_interface gatt
D/BtGatt.AdvertiseManager( 6053): advertise manager created
V/WiFiOffLoadBroadcast( 6091): WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
E/WifiMonitor( 1030): WifiMonitor:wlan0 cnt=9 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
E/WifiMonitor( 1030): handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
D/WifiMonitor( 1030): Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
E/WifiMonitor( 1030): WifiMonitor:wlan0 cnt=10 dispatchEvent: WPS-AP-AVAILABLE 
W/WifiMonitor( 1030): couldn't identify event type - WPS-AP-AVAILABLE 
I/wpa_supplicant( 6108): [LGE_PATCH]scan interval[0] = 2 sec.
,D/WfdsMonitor( 1964): Event [CTRL-EVENT-SCAN-RESULTS ]
E/WifiStateMachine( 1030):  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=0 bcn=0
D/WfdsMonitor( 1964): Event [WPS-AP-AVAILABLE ]
E/WifiMonitor( 1030): WifiMonitor:p2p0 cnt=11 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
E/WifiStateMachine( 1030):  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=0 bcn=0
E/WifiMonitor( 1030): handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
D/WifiMonitor( 1030): Event [IFNAME=p2p0 WPS-AP-AVAILABLE ]
E/WifiMonitor( 1030): WifiMonitor:p2p0 cnt=12 dispatchEvent: WPS-AP-AVAILABLE 
W/WifiMonitor( 1030): couldn't identify event type - WPS-AP-AVAILABLE 
D/BluetoothAdapterService( 6053): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2dc453d0
D/LGWifiP2pService( 1030): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiStateMachine( 1030):  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=0 bcn=0
D/LGWifiP2pService( 1030): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1030): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiStateMachine( 1030):  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=0 bcn=0
I/WifiNative-HAL( 1030): startHal
E/wifi    ( 1030): getStaticLongField sWifiHalHandle 0x9884f8cc
E/WifiHAL ( 1030): Could not connect handle
D/wifi    ( 1030): halHandle = 0x0, mVM = 0xb487c280, mCls = 0x402116
I/WifiNative-HAL( 1030): Could not start hal
D/WifiNative-wlan0( 1030): doString: [BSS RANGE=0- MASK=0x21987]
D/BluetoothAdapterService( 6053): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2dc453d0
I/LGBluetoothMapAdapter( 6053): [BTUI] getInstance : create [LGBluetoothMapAdapter]
V/BluetoothMapService( 6053): BluetoothMapBinder()
D/BluetoothMapService( 6053): Received start request. Starting profile...
D/BluetoothMapService( 6053): start()
D/BluetoothMapEmailSettingsLoader( 6053): Found 0 applications
D/BluetoothMapEmailAppObserver( 6053): createReceiver()
D/BluetoothMapEmailAppObserver( 6053): initObservers()
D/BluetoothMapEmailAppObserver( 6053): getEnabledAccountItems()
D/BluetoothAdapterService( 6053): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2dc453d0
D/HeadsetStateMachine( 6053): Proxy object connected
D/LGBluetoothHfpAdapter( 6053): [BTUI] queryPhoneState
D/LGBluetoothHfpAdapter( 6053): Try to query the phonestate on bind
D/BluetoothPhoneService.BluetoothLTECall( 1866):  call mBluetoothHeadset.phoneStateChanged()
D/WifiService( 1030): New client listening to asynchronous messages
,V/BluetoothPbapReceiver( 6053): PbapReceiver onReceive 
V/BluetoothPbapReceiver( 6053): ***********action = android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothPbapReceiver( 6053): ***********state = 11
W/BluetoothHeadset( 1866): Proxy not attached to service
D/BluetoothHeadset( 1866): java.lang.Throwable
D/BluetoothHeadset( 1866): 	at android.bluetooth.BluetoothHeadset.phoneStateChanged(BluetoothHeadset.java:826)
D/BluetoothHeadset( 1866): 	at com.android.phone.BluetoothPhoneService$BluetoothLTECall.handleQueryPhoneState(BluetoothPhoneService.java:1527)
D/BluetoothHeadset( 1866): 	at com.android.phone.BluetoothPhoneService$BluetoothLTECall.access$700(BluetoothPhoneService.java:1360)
D/BluetoothHeadset( 1866): 	at com.android.phone.BluetoothPhoneService$1.handleMessage(BluetoothPhoneService.java:268)
D/BluetoothHeadset( 1866): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/BluetoothHeadset( 1866): 	at android.os.Looper.loop(Looper.java:135)
D/BluetoothHeadset( 1866): 	at android.app.ActivityThread.main(ActivityThread.java:5274)
D/BluetoothHeadset( 1866): 	at java.lang.reflect.Method.invoke(Native Method)
D/BluetoothHeadset( 1866): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/BluetoothHeadset( 1866): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
D/BluetoothHeadset( 1866): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
D/BluetoothAdapterService( 6053): Profile still not running:com.android.bluetooth.gatt.GattService
D/BluetoothAdapterService( 6053): Profile still not running:com.android.bluetooth.gatt.GattService
D/HeadsetStateMachine( 6053): Disconnected process message: 10, size: 0
D/HeadsetPhoneState( 6053): sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
D/HeadsetStateMachine( 6053): Disconnected process message: 11, size: 0
,D/BluetoothAdapterService( 6053): Profile still not running:com.android.bluetooth.gatt.GattService
D/BluetoothAdapterService( 6053): Profile still not running:com.android.bluetooth.gatt.GattService
V/PanService( 6053): [BTUI] SIM Extra State :ABSENT
D/BluetoothAdapterService( 6053): Profile still not running:com.android.bluetooth.gatt.GattService
D/BluetoothAdapterService( 6053): Profile still not running:com.android.bluetooth.map.BluetoothMapService
V/BluetoothMapService( 6053): Handler(): got msg=1
D/BluetoothAdapterState( 6053): CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
,I/bluedroid-qcom( 6053): enable
I/GKI_LINUX( 6053): gki_task_entry task_id=0 [BTU] starting
I/bt-btu  ( 6053): btu_task pending for preload complete event
I/bt_hci_bdroid( 6053): init
I/bt_vendor( 6053): bt-vendor : init
I/bt_vendor( 6053): bt-vendor : get_bt_soc_type
E/bt_vendor( 6053): get_bt_soc_type: Failed to get soc type
I/bt_vendor( 6053): init: Local BD Address : c0:64:73:54:3f:58
D/bt_userial_mct( 6053): userial_init
D/LgDataFeature( 6091): LgDataFeature() Constructor: none
D/LgDataFeature( 6091): LgDataFeature() Constructor Done, null
D/bt_hci_bdroid( 6053): set_power 1
I/bt_vendor( 6053): bt-vendor : BT_VND_OP_POWER_CTRL: On
,I/bt_vendor( 6053): Starting hciattach daemon
I/bt_vendor( 6053): try to set true
W/sh      ( 6180): type=1400 audit(0.0:157): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6838 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
W/sh      ( 6180): type=1400 audit(0.0:158): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6838 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,I/ActivityManager( 1030): Start proc com.lge.lifetracker for broadcast com.lge.lifetracker/.receiver.HealthDeviceReceiver: pid=6181 uid=10037 gids={50037, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
D/WiFiOffLoadUpdatePriority( 6091): remove : truetruetrue
I/qcom-bluetooth( 6192): /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  
,E/WifiStateMachine( 1030):  DisconnectedState CMD_GET_CONFIGURED_NETWORKS uid=1000 1000 0 num=1
E/WifiStateMachine( 1030):  ConnectModeState CMD_GET_CONFIGURED_NETWORKS uid=1000 1000 0 num=1
E/WifiStateMachine( 1030):  DisconnectedState CMD_SAVE_CONFIG uid=1000 0 0
,E/WifiStateMachine( 1030):  ConnectModeState CMD_SAVE_CONFIG uid=1000 0 0
D/WifiNative-wlan0( 1030): doBoolean: SAVE_CONFIG
D/WifiNative-wlan0( 1030): SAVE_CONFIG: returned true
D/WiFiOffLoadUpdatePriority( 6091): remove1
V/WiFiOffLoadSharedPrefsUtils( 6091): save remove
D/WiFiOffLoadBroadcast( 6091): mLastConnectedNetwork from SharedPrefsUtils for wifioffloading : null
,D/WiFiOffLoadBroadcast( 6091): S: false, R: false
E/WifiStateMachine( 1030):  DisconnectedState CMD_GET_CONFIGURED_NETWORKS uid=1000 1000 0 num=1
E/WifiStateMachine( 1030):  ConnectModeState CMD_GET_CONFIGURED_NETWORKS uid=1000 1000 0 num=1
D/WiFiOffLoadUpdatePriority( 6091): saved SSID: "NG700"
D/WiFiOffLoadUpdatePriority( 6091): connected SSID: null
D/WiFiOffLoadUpdatePriority( 6091): private wpa: "NG700" 300
D/WifiServiceImplEx( 1030): addOrUpdateNetwork pid=6091, uid=1000, packageName=android.uid.system:1000
E/addOrUpdateNetwork( 1030):  uid = 1000 SSID "NG700" nid=0
E/WifiStateMachine( 1030):  DisconnectedState CMD_ADD_OR_UPDATE_NETWORK uid=1000 0 0 "NG700"WPA_PSK prio=300 status=2
E/WifiStateMachine( 1030):  ConnectModeState CMD_ADD_OR_UPDATE_NETWORK uid=1000 0 0 "NG700"WPA_PSK prio=300 status=2
E/WifiConfigStore( 1030):  key="NG700"WPA_PSK netId=0 uid=0/1000
D/WifiServerServiceExt( 1030): addOrUpdateNetwork: mThisIsFirstEnableing = false
D/WifiNative-wlan0( 1030): doBoolean: SET_NETWORK 0 ssid 4e47373030
I/qcom-bluetooth( 6205): /system/etc/init.qcom.bt.sh: Transport : smd 
,I/qcom-bluetooth( 6206): /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
D/WifiNative-wlan0( 1030): SET_NETWORK 0 ssid 4e47373030: returned true
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
I/qcom-bluetooth( 6208): /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,E/WifiConfigStore( 1030): writeIpAndProxyConfigurationsOnChange: "NG700" -> "NG700" path: /data/misc/wifi/ipconfig.txt
E/WifiConfigStore( 1030):  writeKnownNetworkHistory() num networks:1 needWrite=false
E/ActivityThread( 6181): Failed to find provider info for com.lge.lgaccount.provider
W/LG Account v2.2( 6181): No ProfileInfo entries
I/LG Account v2.2( 6181): isEnabled: false
I/Feature ( 6181): [Lifetracker]ver: 4.21.112(40211120)
I/Feature ( 6181): [Lifetracker]Country: EU
I/Feature ( 6181): [Lifetracker]Operator: OPEN
I/Feature ( 6181): [Lifetracker]Ranking support: false
I/Feature ( 6181): [Lifetracker]Comfort support: false
D/WiFiOffLoadUpdatePriority( 6091):  ssid "NG700" prio 300
I/Feature ( 6181): [Lifetracker]Accessory: true
D/WiFiOffLoadUpdatePriority( 6091): configuration updated: 0
I/Feature ( 6181): [Lifetracker]Health device: true
I/Feature ( 6181): [Lifetracker]Extra Pedometer: false
I/Feature ( 6181): [Lifetracker]Blood glucose device: false
I/Feature ( 6181): [Lifetracker]Device Number: 3
E/WifiStateMachine( 1030):  DisconnectedState CMD_SAVE_CONFIG uid=1000 0 0
E/WifiStateMachine( 1030):  ConnectModeState CMD_SAVE_CONFIG uid=1000 0 0
D/WifiNative-wlan0( 1030): doBoolean: SAVE_CONFIG
I/ActivityManager( 1030): Killing 5454:com.lge.appbox.client/u0a11 (adj 15): empty #17
D/WifiNative-wlan0( 1030): SAVE_CONFIG: returned true
D/WiFiOffLoadUpdatePriority( 6091): configuration saved: true
I/qcom-bluetooth( 6211): /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> 
,I/qcom-bluetooth( 6212): /system/etc/init.qcom.bt.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
I/qcom-bluetooth( 6213): /system/etc/init.qcom.bt.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> 
I/libmdmdetect( 6215): ESOC framework not supported
,E/Diag_Lib( 6215):  Diag_LSM_Init: Failed to open handle to diag driver, error = 13
,D/bthci_qcomm_linux( 6215): [BTUI] bt_hci_qcomm_pfal_get_bdaddress: Get BDADDR from bluedroid prop (58:3F:54:73:64:C0)
D/bthci_qcomm_common( 6215): [BTUI] bt_hci_qcomm_init:
D/bthci_qcomm_common( 6215): [BTUI]     BDADDR: 58:3F:54:73:64:C0
D/bthci_qcomm_common( 6215): [BTUI]     BR/EDR: Class 1
D/bthci_qcomm_common( 6215): [BTUI]     LE: Class 2
D/bthci_qcomm_common( 6215): [BTUI]     Ref Clock: 32M
D/btqsocnvmtags( 6215): [BTUI] init_riva_entries: set NORMAL power settings
W/libprocessgroup( 1030): failed to open /acct/uid_10011/pid_5454/cgroup.procs: No such file or directory
,D/BluetoothPermissionRequest( 6091): onReceive
,D/LGBluetoothFeatureConfig( 6091):  get() - isFeatureLoaded : false
,D/BluetoothManagerService( 1030): Message: 20
D/BluetoothManagerService( 1030): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@2d04e69b:true
,I/ActivityManager( 1030): Killing 5473:com.android.contacts/u0a19 (adj 15): empty #17
,D/LGBluetoothResetSettingReceiver( 6091): return without doing reset settings.
I/rmt_storage(  304): rmt_storage_connect_cb: clnt_h=0x5 conn_h=0xb6403090
I/rmt_storage(  304): rmt_storage_rw_iovec_cb: /boot/modem_fs2: clnt_h=0x2: req_h=0x9 msg_id=3: R/W request received
I/rmt_storage(  304): wakelock acquired: 1, error no: 42
I/rmt_storage(  304): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 Unblock worker thread (th_id: -1236806912)
,I/rmt_storage(  304): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0x9 msg_id=3: Bytes written = 1572864
,I/rmt_storage(  304): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0x9 msg_id=3: Send response: res=0 err=0
I/rmt_storage(  304): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 About to block rmt_storage client thread (th_id: -1236806912) wakelock released: 1, error no: 0
I/rmt_storage(  304): 
,I/rmt_storage(  304): rmt_storage_disconnect_cb: clnt_h=0x0x5 conn_h=0x0xb6403090
E/Diag_Lib(  898): [IMS_FATAL]| 3347 | 906 |ims-rtp-daemon ims_rtp_qmi_handler_thread_func waiting on select thread>
D/LGBluetoothOppAdapter( 6053): [BTUI] getInstance : create [LGBluetoothOppAdapter]
W/libprocessgroup( 1030): failed to open /acct/uid_10019/pid_5473/cgroup.procs: No such file or directory
V/BluetoothFtpReceiver( 6053): BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
,V/BluetoothSapReceiver( 6053): [BTUI] checkServiceStart
V/BluetoothSapReceiver( 6053): [BTUI] region:EU country:EU
V/BluetoothSapReceiver( 6053): SapReceiver onReceive 
V/BluetoothSapReceiver( 6053): action = android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothSapReceiver( 6053):  Bluetooth Adapter state = 11
,I/ActivityManager( 1030): Start proc com.lge.settings.easy for broadcast com.lge.settings.easy/com.lge.settings.bluetooth.LGBluetoothProfileConnectionReceiver: pid=6222 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,D/PCSuite ( 6146): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 6091): WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
W/FormManager( 6121): Network not available. Please check & try again.
,V/FormManager( 6121): Network unavailable.
V/FormManager( 6121): Network unavailable.
D/WiFiOffLoadBroadcast( 6091): MCCMNC not supported: null
D/LGDMClient( 3984): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
D/LGDMClient( 3984): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
W/ContextImpl( 3984): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
W/ContextImpl( 3984): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,D/LGDMClient( 3984): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=3, isUserType=1
,D/PostponalbeReceiver( 5135): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
D/LGDMClient( 3984): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
D/LGDMClient( 3984): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
I/PCSuite ( 6146): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
,D/PCSuite ( 6146): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 6146): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 6091): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6091): MCCMNC not supported: null
W/ResourcesManager( 6222): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
I/ActivityManager( 1030): Start proc com.lge.qremote for broadcast com.lge.qremote/.settings.WiFiStateReceiver: pid=6242 uid=10112 gids={50112, 9997, 1028, 1015, 3003, 3002} abi=armeabi
,I/ActivityManager( 1030): Killing 5782:com.lge.email/u0a23 (adj 15): empty #17
W/libprocessgroup( 1030): failed to open /acct/uid_10023/pid_5782/cgroup.procs: No such file or directory
,D/AuthorizationBluetoothService( 2126): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,W/ResourcesManager( 6242): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,D/QRemote ( 6242): [QRemoteApplication.java:230:onCreate()] oooooo QRemoteApp onCreate....
,D/QRemote ( 6242): [CarrierUtils.java:858:getHardwareSettings()] oooooo qremote android.os.Build.MODEL = LG-D855
I/QRemote ( 6242): [CarrierUtils.java:859:getHardwareSettings()] oooooo getCountry :: EU
,I/QRemote ( 6242): [CarrierUtils.java:860:getHardwareSettings()] oooooo getCarrier :: OPEN
I/QRemote ( 6242): [CarrierUtils.java:861:getHardwareSettings()] oooooo getArea :: COM,
D/QRemote ( 6242): [CarrierUtils.java:862:getHardwareSettings()] oooooo Loading Config...
D/QRemote ( 6242): [CarrierUtils.java:876:getHardwareSettings()] oooooo qremote configuration file = R.xml.qremote_conf
D/QRemote ( 6242): [QRemoteApplication.java:701:updateWidget()] oooooo Widget count is [1]. send broadcast
D/QRemote ( 6242): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6242): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 6242): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,V/[BNRBootReceiver]( 5917): boot receiver action = android.net.wifi.p2p.CONNECTION_STATE_CHANGE
D/BNRAndroBeam( 5917): [BnR DirectBeam] Android Direct Beam(NFC) Connection changed
D/QRemote ( 6242): [QRemoteService.java:196:onCreate()] oooooo 140526:onCreate
D/QRemote ( 6242): [QRemoteService.java:217:onStartCommand()] oooooo 140526:onStartCommand:action:action.application.oncreate. startId:1, flags:0
V/[BNRBootReceiver]( 5917): Boot Receiver Return
D/PostponalbeReceiver( 5135): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
V/WiFiOffLoadBroadcast( 6091): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6091): MCCMNC not supported: null
D/QRemote ( 6242): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6242): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 6242): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
V/WiFiOffLoadBroadcast( 6091): WiFiOffLoadBroadcast: android.net.wifi.SCAN_RESULTS
D/WiFiOffLoadBroadcast( 6091): Not supported operator for automatic switch
V/QRemote ( 6242): [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
D/QRemote ( 6242): [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
D/QRemote ( 6242): [QRemoteApplication.java:86:getControlManager()] oooooo mControlManager is null. make new RemoteControlManager
D/LgDataFeature( 6242): LgDataFeature() Constructor: none
D/LgDataFeature( 6242): LgDataFeature() Constructor Done, null
V/SoundPool( 6242): SoundPool constructor: maxChannels=2, attr.usage=13, attr.flags=0x0, attr.tags=
,V/SoundPool( 6242): load: fd=30, offset=10857164, length=17813, priority=1
V/SoundPool( 6242): create sampleID=1, fd=31, offset=17813 length=10857164
V/SoundPool( 6242): doLoad: loading sample sampleID=1
I/QRemote ( 6242): [RemoteControlManager.java:157:onBindIRService()] oooooo bind
V/SoundPool( 6242): Start decode
V/MediaPlayer[Native]( 6242): decode(31, 10857164, 17813)
V/MediaPlayerService(  313): decode(24, 10857164, 17813)
W/BrunchPlayerTypeImpl(  313): [SelectPlayer] LocalType
W/BrunchPlayerTypeImpl(  313): [getMediaType] EXTEND_MEDIA_MIMETYPE = application/ogg
W/BrunchPlayerTypeImpl(  313): [FindUsePlayer] type = [application/ogg]
W/BrunchPlayerTypeImpl(  313): [FindUsePlayer] componentName = [9101]
W/MediaPlayerFactory(  313): [getPlayerType:fd] nType = 3
V/MediaPlayerService(  313): player type = 3
V/AwesomePlayer(  313): AwesomePlayer create()
D/QRemote ( 6242): [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
D/UEI.SmartControl( 5809): QS Service created
V/AwesomePlayer(  313): reset_l() 
V/AwesomePlayer(  313): cancelPlayerEvents
V/AwesomePlayer(  313): setAudioSink() 
V/AwesomePlayer(  313): reset_l() 
V/AudioCache(  313): notify(0xb1432300, 8, 0, 0)
V/AudioCache(  313): ignored
V/AwesomePlayer(  313): cancelPlayerEvents
D/Utils   (  313): printFileName fd(25) -> /data/preload/LGQRemote/LGQRemote.apk
V/AwesomePlayer(  313): setDataSource_l dataSource
V/LGParserOSAL(  313): SniffLGParser start
V/LGParserOSAL(  313): MainType:5, SubType=0
V/LGParserOSAL(  313): #### check Mime : application/ogg
V/LGParserOSAL(  313): Detector mimeType:application/ogg, Confidence=1.000000
E/MediaExtractor(  313): Use LGExtractor :application/ogg 
E/QRemote ( 6242): [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
,D/QRemote ( 6242): [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
V/LGParserOSAL(  313): supported mime: application/ogg
V/AwesomePlayer(  313): setDataSource_l() extractor countTracks=1
V/AwesomePlayer(  313): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer(  313): mBitrate = -1 bits/sec
V/AwesomePlayer(  313): AudioTrack Setting
V/AwesomePlayer(  313): AudioTrack Setting channelCount = 2
V/AwesomePlayer(  313): setAudioSource() 
V/MediaPlayerService(  313): prepare
V/AwesomePlayer(  313): prepareAsync_l() 
V/MediaPlayerService(  313): wait for prepare
I/UEI.SmartControl( 5809): Service initServices...
D/UEI.SmartControl( 5809): QS start get config
V/AwesomePlayer(  313): onPrepareAsyncEvent() 
V/AwesomePlayer(  313): initAudioDecoder() 
W/Utils   (  313): bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
V/AudioSystem(  313): isOffloadSupported()
V/AudioPolicyManager(  313): isOffloadSupported: SR=48000, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
D/AudioPolicyManager(  313): isOffloadSupported: stream_type != MUSIC, returning false
I/AudioFlinger(  313): isAudioPlaybackHookOn() false
V/AwesomePlayer(  313): getUseOffload() = 0 
V/OMXCodec(  313): OMXCodec::Create
V/OMXCodec(  313): findMatchingCodecs()
V/OMXCodec(  313): matching 'OMX.google.vorbis.decoder' quirks 0x00000000
V/OMXCodec(  313): matchingCodecs.size()=1
V/OMXCodec(  313): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
D/OMXCodec(  313): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
V/LGCodecAdapter(  313): LG Codec Adapter start
V/OMXCodec(  313): OMXCodec Createtor
V/OMXCodec(  313): setComponentRole
V/OMXCodec(  313): configureCodec protected=0
V/LGCodecAdapter(  313): called getLGCodecSpecificData
V/LGCodecOSAL(  313): Called LGgetCodecSpecificDataMETA
V/LGCodecOSAL(  313): Called LGconfigureCodecMETA
V/LGCodecOSAL(  313): Called LGconfigureCodecMSG
V/LGCodecOSAL(  313): Not support LGCodec
V/OMXCodec(  313): [OMX.google.vorbis.decoder] initOutputFormat()
V/OMXCodec(  313): Codec outputs a different number of channels than the input stream contains (contains 2 channels, codec outputs 1 channels).
V/OMXCodec(  313): Codec outputs at different sampling rate than what the input stream contains (contains data at 48000 Hz, codec outputs 44100 Hz)
I/AwesomePlayer(  313): Could not offload audio decode, try pcm offload
W/Utils   (  313): bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
V/AudioSystem(  313): isOffloadSupported()
V/AudioPolicyManager(  313): isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
D/AudioPolicyManager(  313): isOffloadSupported: stream_type != MUSIC, returning false
V/OMXCodec(  313): [OMX.google.vorbis.decoder] start mState=1
V/OMXCodec(  313): init()
V/OMXCodec(  313): [OMX.google.vorbis.decoder] setState mState=1 , newState=2
V/OMXCodec(  313): allocateBuffers
V/OMXCodec(  313): allocateBuffersOnPort portIndex=0
V/OMXCodec(  313): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
V/OMXCodec(  313): [OMX.google.vorbis.decoder] allocated buffer 0xb1434330 on input port
V/OMXCodec(  313): [OMX.google.vorbis.decoder] allocated buffer 0xb14345b0 on input port
V/OMXCodec(  313): [OMX.google.vorbis.decoder] allocated buffer 0xb1434600 on input port
V/OMXCodec(  313): [OMX.google.vorbis.decoder] allocated buffer 0xb1434650 on input port
V/OMXCodec(  313): allocateBuffersOnPort portIndex=1
V/OMXCodec(  313): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
V/OMXCodec(  313): [OMX.google.vorbis.decoder] allocated buffer 0xb14346a0 on output port
V/OMXCodec(  313): [OMX.google.vorbis.d,ecoder] allocated buffer 0xb1434740 on output port
V/OMXCodec(  313): [OMX.google.vorbis.decoder] allocated buffer 0xb1434830 on output port
V/OMXCodec(  313): [OMX.google.vorbis.decoder] allocated buffer 0xb1434bf0 on output port
V/OMXCodec(  313): init() mAsyncCompletion wait!!! 
V/OMXCodec(  313): [OMX.google.vorbis.decoder] onStateChange 2
V/OMXCodec(  313): [OMX.google.vorbis.decoder] Now Idle.
V/OMXCodec(  313): [OMX.google.vorbis.decoder] setState mState=2 , newState=3
V/OMXCodec(  313): [OMX.google.vorbis.decoder] onStateChange 3
V/OMXCodec(  313): [OMX.google.vorbis.decoder] Now Executing.
V/OMXCodec(  313): [OMX.google.vorbis.decoder] setState mState=3 , newState=4
V/LGMDMManager( 6242): Create singleton instance
V/OMXCodec(  313): init() mAsyncCompletion wait free! 
V/AwesomePlayer(  313): finishAsyncPrepare_l() 
V/AudioCache(  313): notify(0xb1432300, 5, 0, 0)
V/AudioCache(  313): ignored
V/AudioCache(  313): notify(0xb1432300, 1, 0, 0)
V/AudioCache(  313): prepared
V/AudioCache(  313): wait - success
V/MediaPlayerService(  313): start
V/AwesomePlayer(  313): play_l() 
V/AwesomePlayer(  313): play_l m_isDivXDRM=0, bpurchasefile:0
V/AwesomePlayer(  313): createAudioPlayer_l
V/AwesomePlayer(  313): seekAudioIfNecessary_l() 
V/AwesomePlayer(  313): startAudioPlayer_l() 
D/AudioPlayer(  313): start of Playback, useOffload 0
V/OMXCodec(  313): [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
V/OMXCodec(  313): [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
V/OMXCodec(  313): [OMX.google.vorbis.decoder] OMX_EventPortSettingsChanged(port=1, data2=0x00000000)
V/OMXCodec(  313): [OMX.google.vorbis.decoder] PORT_SETTINGS_CHANGED(1)
V/OMXCodec(  313): [OMX.google.vorbis.decoder] setState mState=4 , newState=7
V/OMXCodec(  313): [OMX.google.vorbis.decoder] disablePortAsync portIndex=1
V/OMXCodec(  313): [OMX.google.vorbis.decoder] sending OMX_CommandPortDisable(1)
V/OMXCodec(  313): [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
V/OMXCodec(  313): [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2973976224
V/OMXCodec(  313): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
V/OMXCodec(  313): [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2973976384
V/OMXCodec(  313): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
V/OMXCodec(  313): [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2973976624
V/OMXCodec(  313): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
V/OMXCodec(  313): [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2973977584
V/OMXCodec(  313): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
V/OMXCodec(  313): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
V/OMXCodec(  313): [OMX.google.vorbis.decoder] initOutputFormat()
V/OMXCodec(  313): [OMX.google.vorbis.decoder] reconfig handling, formatHasNotablyChanged
V/OMXCodec(  313): [OMX.google.vorbis.decoder] enablePortAsync portIndex=1
V/OMXCodec(  313): [OMX.google.vorbis.decoder] sending OMX_CommandPortEnable(1)
V/OMXCodec(  313): allocateBuffersOnPort portIndex=1
V/OMXCodec(  313): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
V/OMXCodec(  313): [OMX.google.vorbis.decoder] allocated buffer 0xb1434830 on output port
V/OMXCodec(  313): [OMX.google.vorbis.decoder] allocated buffer 0xb1434740 on output port
V/OMXCodec(  313): [OMX.google.vorbis.decoder] allocated buffer 0xb14346a0 on output port
V/OMXCodec(  313): [OMX.google.vorbis.decoder] allocated buffer 0xb15290b0 on output port
V/OMXCodec(  313): [OMX.google.vorbis.decoder] PORT_ENABLED(1)
V/OMXCodec(  313): [OMX.google.vorbis.decoder] setState mState=7 , newState=4
V/AudioCache(  313): open(48000, 2, 0x0, 1, 4)
V/AudioCache(  313): notify(0xb1432300, 6, 0, 0)
V/AudioCache(  313): ignored
V/MediaPlayerService(  313): wait for playback complete
V/AudioCache(  313): write(0xb1245000, 4096)
V/AudioCache(  313): memcpy(0xac602000, 0xb1245000, 4096)
V/AudioCache(  313): write(0xb1245000, 4096)
V/AudioCache(  313): memcpy(0xac603000, 0xb1245000, 4096)
V/AudioCache(  313): write(0xb1245000, 4096)
V/AudioCache(  313): memcpy(0xac604000, 0xb1245000, 4096)
V/AudioCache(  313): write(0xb1245000, 4096)
V/AudioCache(  313): memcpy(0xac605000, 0xb1245000, 4096)
V/AudioCache(  313): write(0xb1245000, 4096)
V/AudioCache(  313): memcpy(0xac606000, 0xb1245000, 4096)
V/AudioCache(  313): write(0xb1245000, 4096)
V/AudioCache(  313): memcpy(0xac607000, 0xb1245000, 4096)
V/AudioCache(  313): write(0xb1245000, 4096)
V/AudioCache(  313): memcpy(0xac608000, 0xb1245000, 4096)
V/AudioCache(  313): write(0xb1245000, 4096)
V/AudioCache(  313): memcpy(0xac609000, 0xb1245000, 4096)
V/AudioCache(  313): write(0xb1245000, 4096)
V/AudioCache(  313): memcpy(0xac60a000, 0xb1245000, 4096)
V/AudioCache(  313): write(0xb1245000, 4096)
V/AudioCache(  313): memcpy(0xac60b000, 0xb1245000, 4096)
V/AudioCache(  313): write(0xb1245000, 4096)
V/AudioCache(  313): memcpy(0xac60c000, 0xb1245000, 4096)
V/AudioCache(  313): write(0xb1245000, 4096)
V/AudioCache(  313): memcpy(0xac60d000, 0xb1245000, 4096)
V/AudioCache(  313): write(0xb1245000, 4096)
V/AudioCache(  313): memcpy(0xac60e000, 0xb1245000, 4096)
V/AudioCache(  313): write(0xb1245000, 4096)
V/AudioCache(  313): memcpy(0xac60f000, 0xb1245000, 4096)
V/AudioCache(  313): write(0xb1245000, 4096)
V/AudioCache(  313): memcpy(0xac610000, 0xb1245000, 4096)
V/AudioCache(  313): write(0xb1245000, 4096)
V/AudioCache(  313): memcpy(0xac611000, 0xb1245000, 4096)
V/AudioCache(  313): write(0xb1245000, 4096)
V/AudioCache(  313): memcpy(0xac612000, 0xb1245000, 4096)
V/AudioCache(  313): write(0xb1245000, 4096)
V/AudioCache(  313): memcpy(0xac613000, 0xb1245000, 4096)
V/AudioCache(  313): write(0xb1245000, 4096)
V/AudioCache(  313): memcpy(0xac614000, 0xb1245000, 4096)
V/AudioCache(  313): write(0xb1245000, 4096)
V/AudioCache(  313): memcpy(0xac615000, 0xb1245000, 4096)
V/AudioCache(  313): write(0xb1245000, 4096)
V/AudioCache(  313): memcpy(0xac616000, 0xb1245000, 4096)
V/AudioCache(  313): write(0xb1245000, 4096)
V/AudioCache(  313): memcpy(0xac617000, 0xb1245000, 4096)
V/AudioCache(  313): write(0xb1245000, 4096)
V/AudioCache(  313): memcpy(0xac618000, 0xb1245000, 4096)
V/AudioCache(  313): write(0xb1245000, 4096)
V/AudioCache(  313): memcpy(0xac619000, 0xb1245000, 4096)
V/AudioCache(  313): write(0xb1245000, 4096)
V/AudioCache(  313): memcpy(0xac61a000, 0xb1245000, 4096)
V/AudioCache(  313): write(0xb1245000, 4096)
V/AudioCache(  313): memcpy(0xac61b000, 0xb1245000, 4096)
V/AudioCache(  313): write(0xb1245000, 4096)
V/AudioCache(  313): memcpy(0xac61c000, 0xb1245000, 4096)
V/AudioCache(  313): write(0xb1245000, 4096)
V/AudioCache(  313): memcpy(0xac61d000, 0xb1245000, 4096)
V/AudioCache(  313): write(0xb1245000, 4096)
V/AudioCache(  313): memcpy(0xac61e000, 0xb1245000, 4096)
V/AudioCache(  313): write(0xb1245000, 4096)
V/AudioCache(  313): memcpy(0xac61f000, 0xb1245000, 4096)
V/AudioCache(  313): write(0xb1245000, 4096)
V/AudioCache(  313): memcpy(0xac620000, 0xb1245000, 4096)
,V/AudioCache(  313): write(0xb1245000, 4096)
V/AudioCache(  313): memcpy(0xac621000, 0xb1245000, 4096)
V/AudioCache(  313): write(0xb1245000, 4096)
V/AudioCache(  313): memcpy(0xac622000, 0xb1245000, 4096)
V/AudioCache(  313): write(0xb1245000, 4096)
V/AudioCache(  313): memcpy(0xac623000, 0xb1245000, 4096)
V/AudioCache(  313): write(0xb1245000, 4096)
V/AudioCache(  313): memcpy(0xac624000, 0xb1245000, 4096)
V/AudioCache(  313): write(0xb1245000, 4096)
V/AudioCache(  313): memcpy(0xac625000, 0xb1245000, 4096)
V/AudioCache(  313): write(0xb1245000, 4096)
V/AudioCache(  313): memcpy(0xac626000, 0xb1245000, 4096)
V/AudioCache(  313): write(0xb1245000, 4096)
V/AudioCache(  313): memcpy(0xac627000, 0xb1245000, 4096)
V/AudioCache(  313): write(0xb1245000, 4096)
V/AudioCache(  313): memcpy(0xac628000, 0xb1245000, 4096)
V/AudioCache(  313): write(0xb1245000, 4096)
V/AudioCache(  313): memcpy(0xac629000, 0xb1245000, 4096)
V/AudioCache(  313): write(0xb1245000, 4096)
V/AudioCache(  313): memcpy(0xac62a000, 0xb1245000, 4096)
V/AudioCache(  313): write(0xb1245000, 4096)
V/AudioCache(  313): memcpy(0xac62b000, 0xb1245000, 4096)
V/AudioCache(  313): write(0xb1245000, 4096)
V/AudioCache(  313): memcpy(0xac62c000, 0xb1245000, 4096)
V/AudioCache(  313): write(0xb1245000, 4096)
V/AudioCache(  313): memcpy(0xac62d000, 0xb1245000, 4096)
V/AudioCache(  313): write(0xb1245000, 4096)
V/AudioCache(  313): memcpy(0xac62e000, 0xb1245000, 4096)
V/AudioCache(  313): write(0xb1245000, 4096)
V/AudioCache(  313): memcpy(0xac62f000, 0xb1245000, 4096)
V/AudioCache(  313): write(0xb1245000, 4096)
V/AudioCache(  313): memcpy(0xac630000, 0xb1245000, 4096)
V/AudioCache(  313): write(0xb1245000, 4096)
V/AudioCache(  313): memcpy(0xac631000, 0xb1245000, 4096)
V/AudioCache(  313): write(0xb1245000, 4096)
V/AudioCache(  313): memcpy(0xac632000, 0xb1245000, 4096)
V/AudioCache(  313): write(0xb1245000, 4096)
V/AudioCache(  313): memcpy(0xac633000, 0xb1245000, 4096)
V/OMXCodec(  313): [OMX.google.vorbis.decoder] No more output data.
V/OMXCodec(  313): [OMX.google.vorbis.decoder] There is no more output data available, not calling fillOutputBuffer
V/AwesomePlayer(  313): postAudioEOS() 
V/AudioCache(  313): write(0xb1245000, 280)
V/AudioCache(  313): memcpy(0xac634000, 0xb1245000, 280)
V/AwesomePlayer(  313): postStreamDoneEvent_l() -> status:-1011 
V/AwesomePlayer(  313): onStreamDone
V/AwesomePlayer(  313): MEDIA_PLAYBACK_COMPLETE
V/AudioCache(  313): notify(0xb1432300, 2, 0, 0)
V/AudioCache(  313): playback complete
V/AwesomePlayer(  313): pause_l() 
V/AudioCache(  313): notify(0xb1432300, 7, 0, 0)
V/AudioCache(  313): ignored
V/AwesomePlayer(  313): cancelPlayerEvents
D/AudioPlayer(  313): Pause Playback at 1068125
V/AudioCache(  313): wait - success
V/MediaPlayerService(  313): return size 205080, sampleRate=48000, channelCount = 2, format = 1
V/AwesomePlayer(  313): reset_l() 
V/AudioCache(  313): notify(0xb1432300, 8, 0, 0)
V/AudioCache(  313): ignored
V/AwesomePlayer(  313): cancelPlayerEvents
D/AudioPlayer(  313): reset: mPlaying=0 mReachedEOS=1 useOffload=0
V/OMXCodec(  313): [OMX.google.vorbis.decoder] stop mState=4
V/OMXCodec(  313): [OMX.google.vorbis.decoder] stopOmxComponent_l mState=4
V/OMXCodec(  313): [OMX.google.vorbis.decoder] setState mState=4 , newState=5
V/OMXCodec(  313): [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
V/OMXCodec(  313): [OMX.google.vorbis.decoder] onStateChange 2
V/OMXCodec(  313): [OMX.google.vorbis.decoder] Now Idle.
V/OMXCodec(  313): [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=0
V/OMXCodec(  313): [OMX.google.vorbis.decoder] freeing buffer 0xb1434650 on port 0
V/OMXCodec(  313): [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=3
V/OMXCodec(  313): [OMX.google.vorbis.decoder] freeing buffer 0xb1434600 on port 0
V/OMXCodec(  313): [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=2
V/OMXCodec(  313): [OMX.google.vorbis.decoder] freeing buffer 0xb14345b0 on port 0
V/OMXCodec(  313): [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=1
V/OMXCodec(  313): [OMX.google.vorbis.decoder] freeing buffer 0xb1434330 on port 0
V/OMXCodec(  313): [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=0
V/OMXCodec(  313): [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
V/OMXCodec(  313): [OMX.google.vorbis.decoder] freeing buffer 0xb15290b0 on port 1
V/OMXCodec(  313): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=3
V/OMXCodec(  313): [OMX.google.vorbis.decoder] freeing buffer 0xb14346a0 on port 1
V/OMXCodec(  313): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=2
V/OMXCodec(  313): [OMX.google.vorbis.decoder] freeing buffer 0xb1434740 on port 1
V/OMXCodec(  313): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=1
V/OMXCodec(  313): [OMX.google.vorbis.decoder] freeing buffer 0xb1434830 on port 1
V/OMXCodec(  313): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
V/OMXCodec(  313): [OMX.google.vorbis.decoder] setState mState=5 , newState=6
V/OMXCodec(  313): [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
V/OMXCodec(  313): [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
V/OMXCodec(  313): [OMX.google.vorbis.decoder] onStateChange 1
V/OMXCodec(  313): [OMX.google.vorbis.decoder] Now Loaded.
V/OMXCodec(  313): [OMX.google.vorbis.decoder] setState mState=6 , newState=1
V/OMXCodec(  313): [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
V/OMXCodec(  313): [OMX.google.vorbis.decoder] stopped in state 1
V/OMXCodec(  313): [OMX.google.vorbis.decoder] ~OMXCodec mstate =1
V/OMXCodec(  313): [OMX.google.vorbis.decoder] setState mState=1 , newState=0
D/AudioPlayer(  313): AudioPlayer releasing audio source
D/AudioPlayer(  313): AudioPlayer done releasing audio source
V/AwesomePlayer(  313): reset_l() 
V/AwesomePlayer(  313): cancelPlayerEvents
V/AwesomePlayer(  313): ~AwesomePlayer call
V/AwesomePlayer(  313): reset_l() 
V/AwesomePlayer(  313): cancelPlayerEvents
V/SoundPool( 6242): close(31)
V/SoundPool( 6242): pointer = 0x9ffc5000, size = 205080, sampleRate = 48000, numChannels = 2
D/QRemote ( 6242): [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
,D/QRemote ( 6242): [RemoteAppWidgetProvider.java:486:onUpdate()] oooooo 140510:RetrieveDevices is not complete. Just waiting
D/QRemote ( 6242): [RemoteAppWidgetProvider.java:499:onUpdate()] oooooo 140514:alarm set after 5000ms:9193
D/sensors_hal_Time( 1030): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1030): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1030): tsOffsetIs: Apps: 117288992560; DSPS: 3984848; Offset : -4334097697
,E/QC-QMI  ( 6215): qmi_client [6215] 13: failed to locate client data
,E/QC-QMI  (  460): qmuxd: RX on fd=32 returned error=0 errno[2:No such file or directory]
E/QC-QMI  (  460): QMUX qmux_client_id=13 not found in qmux client list, unable to remove
,I/UEI.SmartControl( 5809): Supports setup maps: true
,D/UEI.SmartControl( 5809): QS start statue = true Error code = 0
,I/UEI.SmartControl( 5809): QS version = v2.7.10.1_RC1
,I/UEI.SmartControl( 5809): QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
I/UEI.SmartControl( 5809): ### init IR Blaster...
D/serial_port( 5809): Configuring serial port
,E/UEI.SmartControl( 5809): UEIBLaster setting for 616
I/UEI.SmartControl( 5809): Setting serial record hearder size = 2
I/UEI.SmartControl( 5809): configuring settings for MAXQ616
I/UEI.SmartControl( 5809): Get version...
I/qcom-bluetooth( 6287): /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 58:3f:54:73:64:c0 
I/qcom-bluetooth( 6289): /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,D/UEI.SmartControl( 5809): serial port data available: 21
I/bt_vendor( 6053): bluetooth satus is on
,D/bt_hci_bdroid( 6053): preload
D/bt_userial_mct( 6053): userial_open(port:0)
I/bt_vendor( 6053): bt-vendor : BT_VND_OP_USERIAL_OPEN
I/bt_vendor( 6053): Done intiailizing UART
I/bt_vendor( 6053): Done intiailizing UART
I/bt_userial_mct( 6053): CMD=66, EVT=66, ACL_Out=67, ACL_In=67
I/bt_vendor( 6053): Bluetooth Firmware and transport layer are initialized
D/bt_userial_mct( 6053): Entering userial_read_thread()
I/bt-btu  ( 6053): btu_task received preload complete event
W/bt-l2cap( 6053): L2CAP - L2CA_Register() called for PSM: 0x0001
W/bt-l2cap( 6053): L2CAP - L2CA_Register() called for PSM: 0x001f
W/bt-l2cap( 6053): L2CAP - L2CA_Register() called for PSM: 0x0003
D/UEI.SmartControl( 5809): MAXQ616 A2-X4 software.
I/UEI.SmartControl( 5809): IR Blaster version: 256702256704300002
I/UEI.SmartControl( 5809): QS saving settings...
D/UEI.SmartControl( 5809): IR Blaster version: 25672567
I/        ( 6053): BTE_InitTraceLevels -- TRC_HCI
I/        ( 6053): BTE_InitTraceLevels -- TRC_L2CAP
I/        ( 6053): BTE_InitTraceLevels -- TRC_RFCOMM
I/        ( 6053): BTE_InitTraceLevels -- TRC_AVDT
I/        ( 6053): BTE_InitTraceLevels -- TRC_AVRC
I/        ( 6053): BTE_InitTraceLevels -- TRC_A2D
I/        ( 6053): BTE_InitTraceLevels -- TRC_BNEP
I/        ( 6053): BTE_InitTraceLevels -- TRC_BTM
I/        ( 6053): BTE_InitTraceLevels -- TRC_HID_HOST
I/        ( 6053): BTE_InitTraceLevels -- TRC_GAP
I/        ( 6053): BTE_InitTraceLevels -- TRC_PAN
I/        ( 6053): BTE_InitTraceLevels -- TRC_SDP
I/        ( 6053): BTE_InitTraceLevels -- TRC_GATT
I/        ( 6053): BTE_InitTraceLevels -- TRC_SMP
I/        ( 6053): BTE_InitTraceLevels -- TRC_BTAPP
I/        ( 6053): BTE_InitTraceLevels -- TRC_BTIF
D/UEI.SmartControl( 5809): serial port data available: 4
,W/bt-btm  ( 6053): btm_decode_ext_features_page Secure conn Controller support Enabled
E/bt-btm  ( 6053): BTM_SecRegister:p_cb_info->p_le_callback == 0xa01d3061 
E/bt-btm  ( 6053): BTM_SecRegister: btm_cb.api.p_le_callback = 0xa01d3061 
,W/ContextImpl( 5809): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
E/UEI.SmartControl( 5809): Services init done
D/UEI.SmartControl( 5809): QS Service init finished
D/UEI.SmartControl( 5809): QS Service version name: 2.1.91
D/UEI.SmartControl( 5809): QS Service version code: 201091
D/UEI.SmartControl( 5809): Service requested: Control
D/UEI.SmartControl( 5809): Internal service binding...
I/UEI.SmartControl( 5809): Device manager: loading config....
,D/UEI.SmartControl( 5809): ----------- loading internal config...
I/QRemote ( 6242): [RemoteControlManager.java:183:onServiceConnected()] oooooo start
I/UEI.SmartControl( 5809): ------ IControl API: 11
D/UEI.SmartControl( 5809): File observer start...
E/UEI.SmartControl( 5809): IR Port is disabled: false
D/UEI.SmartControl( 5809): Starting file observer...
I/UEI.SmartControl( 5809): Registering callback...
,I/UEI.SmartControl( 5809): ------ IControl API: 19
I/UEI.SmartControl( 5809): Registering Services Ready callback...
E/UEI.SmartControl( 5809): Loading SETTINGS...
E/bt-btif ( 6053): Calling BTA_HhEnable
E/bt-btif ( 6053): btif_storage_get_adapter_property service_mask:0x2140040
D/BluetoothAdapterProperties( 6053): Address is:58:3F:54:73:64:C0
W/bt-l2cap( 6053): L2CAP - L2CA_Register() called for PSM: 0x0019
W/bt-l2cap( 6053): L2CAP - L2CA_Register() called for PSM: 0x0017
W/bt-l2cap( 6053): L2CAP - L2CA_Register() called for PSM: 0x001b
W/bt-l2cap( 6053): L2CAP - L2CA_Register() called for PSM: 0x0011
W/bt-l2cap( 6053): L2CAP - L2CA_Register() called for PSM: 0x0013
D/BluetoothAdapterProperties( 6053): Name is: G3-1
D/BluetoothManagerService( 1030): Bluetooth Adapter name changed to G3-1
D/BluetoothManagerService( 1030): Stored Bluetooth name: G3-1
D/BluetoothAdapterProperties( 6053): Scan Mode:20
D/BluetoothAdapterProperties( 6053): Discoverable Timeout:120
D/bt_hci_bdroid( 6053): postload
,D/bt_hci_bdroid( 6053): Used up Tx Cmd credits
W/bt-l2cap( 6053): L2CAP - L2CA_Register() called for PSM: 0x000f
D/UEI.SmartControl( 5809): -- Open brand translation xml: brands_translations_ko
W/bt-smp  ( 6053): Key(LSB ~ MSB) = 0a 3c a6 fe eb 17 6a 79 a6 1f 0a 0b f9 50 a0 5f 
W/bt-smp  ( 6053): Plain text(LSB ~ MSB) = 3a 36 47 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 6053): Encrypted text(LSB ~ MSB) = b3 20 76 75 88 c1 d1 36 36 a8 14 88 b2 40 7b 17 
W/bt-btm  ( 6053): Stopping oneshot timer
D/bt_hci_bdroid( 6053): Used up Tx Cmd credits
D/bt_hci_bdroid( 6053): Used up Tx Cmd credits
D/bt_hci_bdroid( 6053): Used up Tx Cmd credits
D/bt_hci_bdroid( 6053): Used up Tx Cmd credits
D/bte_conf( 6053): Device ID record 1 : primary
D/bte_conf( 6053):   vendorId            = 00c4
E/bt_mct  ( 6053): hci lib postload completed
D/bte_conf( 6053):   vendorIdSource      = 0001
D/bte_conf( 6053):   product             = 13a1
D/bte_conf( 6053):   version             = 1000
D/bte_conf( 6053):   clientExecutableURL = 
D/bte_conf( 6053):   serviceDescription  = 
D/bte_conf( 6053):   documentationURL    = 
D/bte_conf( 6053): bte_load_did_conf no section named DID2.
D/BluetoothPanServiceJni( 6053): control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
D/BluetoothAdapterState( 6053): CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
D/BluetoothAdapterProperties( 6053): ScanMode =  20
D/BluetoothAdapterProperties( 6053): State =  11
D/BluetoothAdapterProperties( 6053): mDiscoverableTimeout = 120
V/LGBluetoothServiceAdapter( 6053): [BTUI] state:11, scanmode:20, timeout:120
D/BluetoothAdapterProperties( 6053): Setting state to 12
I/BluetoothAdapterState( 6053): Bluetooth adapter state changed: 11-> 12
D/btif_config_util( 6053): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,D/BluetoothManagerService( 1030): Message: 60
D/BluetoothManagerService( 1030): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
D/BluetoothManagerService( 1030): Broadcasting onBluetoothStateChange(true) to 5 receivers.
W/sh      ( 6301): type=1400 audit(0.0:159): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6838 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,W/sh      ( 6301): type=1400 audit(0.0:160): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6838 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
D/BluetoothHeadset( 1866): onBluetoothStateChange: up=true
I/BluetoothAdapterState( 6053): Entering On State
D/BluetoothHeadset( 1866): onBluetoothStateChange: up=true
D/BluetoothHeadset( 1866): onBluetoothStateChange: up=true
D/BluetoothHeadset( 1030): onBluetoothStateChange: up=true
D/BluetoothA2dp( 1030): onBluetoothStateChange: up=true
D/LGBluetoothServiceAdapter( 6053): [BTUI] OnState
D/LGBluetoothServiceAdapter( 6053): [BTUI]         global_name: G3-1
D/LGBluetoothServiceAdapter( 6053): [BTUI]         local_name: G3-1
E/BluetoothManagerService( 1030): Fail to bind to: Intent { act=android.bluetooth.IQBluetooth }
D/BluetoothManagerService( 1030): Bluetooth State Change Intent: 11 -> 12
D/BluetoothAdapterService( 6053): [BTUI] autoConnect() : not allowed
D/BluetoothManagerService( 1030): BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
I/UEI.SmartControl( 5809): Notify AllClients services are ready: 0
I/QRemote ( 6242): [RemoteControlManager.java:660:QSSetupIsReady()] oooooo 140517:sdkIsReady callback... get functions. Result:0
D/UEI.SmartControl( 5809): -----service ready thread exits
W/bt-smp  ( 6053): Key(LSB ~ MSB) = 0a 3c a6 fe eb 17 6a 79 a6 1f 0a 0b f9 50 a0 5f 
W/bt-smp  ( 6053): Plain text(LSB ~ MSB) = 38 d0 7d 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 6053): Encrypted text(LSB ~ MSB) = bb 10 26 6b b2 58 b2 3f db 06 77 a2 42 0b bb 67 
W/bt-btm  ( 6053): Stopping oneshot timer
,D/LGBluetoothAPIService( 1964): [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
D/LGBluetoothAPIService( 1964): Message: 1
D/LGBluetoothAPIService( 1964): MESSAGE_BOOT_COMPLETED
I/[SystemUI]BluetoothHandler( 1472): Receive : BluetoothAdapter.ACTION_STATE_CHANGED
D/QRemote ( 6242): [RemoteControlManager.java:388:handleMessage()] oooooo 140510:START_SESSION
D/QRemote ( 6242): [RemoteControlManager.java:394:handleMessage()] oooooo 140510:send retrieve msg
D/QRemote ( 6242): [RemoteControlManager.java:322:handleMessage()] oooooo 140510:handler call retrieveDevices
D/QRemote ( 6242): [RemoteControlManager.java:336:retrieveDevices()] oooooo retrieveDevices: start
D/BluetoothManagerService( 1030): Message: 40
D/BluetoothManagerService( 1030): MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
W/bt-smp  ( 6053): Key(LSB ~ MSB) = 0a 3c a6 fe eb 17 6a 79 a6 1f 0a 0b f9 50 a0 5f 
W/bt-smp  ( 6053): Plain text(LSB ~ MSB) = d6 c7 79 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 6053): Encrypted text(LSB ~ MSB) = dc 3d 3f ac 9a 40 33 6b 77 b2 e6 48 12 70 9b 07 
W/bt-btm  ( 6053): Stopping oneshot timer
,W/bt-smp  ( 6053): Key(LSB ~ MSB) = 0a 3c a6 fe eb 17 6a 79 a6 1f 0a 0b f9 50 a0 5f 
I/UEI.SmartControl( 5809): ------ IControl API: 8
W/bt-smp  ( 6053): Plain text(LSB ~ MSB) = d0 d0 4b 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 6053): Encrypted text(LSB ~ MSB) = 02 ba 99 56 9d c7 f0 0f cd 19 41 3b 62 90 28 56 
W/bt-btm  ( 6053): Stopping oneshot timer
D/QRemote ( 6242): [RemoteControlManager.java:340:retrieveDevices()] oooooo retrieveDevices: 0
,D/QRemote ( 6242): [RemoteControlManager.java:345:retrieveDevices()] oooooo retrieveDevices complete:true
D/QRemote ( 6242): [RemoteControlManager.java:353:retrieveDevices()] oooooo retrieveDevices: notifyDataSetChanged()
I/BluetoothMapService( 6053): onReceive: android.bluetooth.adapter.action.STATE_CHANGED
D/BluetoothMapService( 6053): STATE_ON
I/LGBluetoothAPIService( 1964): [BTUI] LGBluetoothAPIService Binding Success
D/LGBluetoothDeviceModeControllManager( 6053): [BTUI] checkDeviceModeAndSet, sinkMode : false
,I/qcom-bt-wlan-coex( 6315): /system/etc/init.qcom.coex.sh: btwlancoex/abtfilt not available 
W/bt-smp  ( 6053): Key(LSB ~ MSB) = 0a 3c a6 fe eb 17 6a 79 a6 1f 0a 0b f9 50 a0 5f 
W/bt-smp  ( 6053): Plain text(LSB ~ MSB) = de da 71 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 6053): Encrypted text(LSB ~ MSB) = 60 5e dc b4 7a ed 71 63 dd a0 ec cd d6 45 a0 52 
W/bt-btm  ( 6053): Stopping oneshot timer
D/QRemote ( 6242): [QRemoteApplication.java:145:onRemoteControlStateChanged()] oooooo onRemoteControlStateChanged called in QRemoteApp
,D/BluetoothAdapterService( 6053): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2dc453d0
V/BluetoothPbapService( 6053): Pbap Service onCreate
V/BluetoothPbapService( 6053): Starting PBAP service
D/QRemote ( 6242): [QRemoteApplication.java:158:onRemoteControlStateChanged()] oooooo Widget count is [1]. send broadcast
D/LGBluetoothPbapAdapter( 6053): [BTUI] getInstance : create
V/BluetoothPbapService( 6053): action: android.bluetooth.adapter.action.STATE_CHANGED
,V/BluetoothPbapService( 6053): state: 12
V/BluetoothMapService( 6053): Handler(): got msg=1
D/BluetoothMapMasInstance( 6053): Map Service startRfcommSocketListener
D/BluetoothMapMasInstance( 6053): MAS initSocket()
D/BluetoothMapMasInstance( 6053):   masId = 00
D/BluetoothMapMasInstance( 6053):   msgTypes = 0e
D/BluetoothMapMasInstance( 6053):   masName = SMS/MMS
D/BluetoothMapMasInstance( 6053):   SDP string = 000eSMS/MMS
D/QRemote ( 6242): [QRemoteApplication.java:160:onRemoteControlStateChanged()] oooooo Widget[0]:3
D/QRemote ( 6242): [QRemoteApplication.java:188:onRemoteControlStateChanged()] oooooo 140526:onRemoteControlStateChanged&sdkIsReady. stop Service
W/ContextImpl( 6091): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
D/BluetoothManagerService( 1030): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
W/BluetoothAdapter( 6053): getBluetoothService() called with no BluetoothManagerCallback
D/LGBluetoothServiceAdapter( 6053): [BTUI] createSocketChannel FD=73 mFd=0
V/BluetoothMapMasInstance( 6053): Succeed to create listening socket 
D/BluetoothMapMasInstance( 6053): Accepting socket connection...
V/QRemote ( 6242): [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
,D/QRemote ( 6242): [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
E/QRemote ( 6242): [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
D/QRemote ( 6242): [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
D/QRemote ( 6242): [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
D/QRemote ( 6242): [RemoteAppWidgetProvider.java:506:onUpdate()] oooooo 140510:RetrieveDevices complete. Start loading
D/QRemote ( 6242): [RemoteAppWidgetProvider.java:508:onUpdate()] oooooo 140510:appWidgetIds[0]:3 loading
D/QRemote ( 6242): [RemoteAppWidgetManager.java:41:startLoading()] oooooo 140518:widgetId[3] loading start at [1454440725849]
D/QRemote ( 6242): [QRemoteService.java:207:onDestroy()] oooooo 140526:onDestroy
,D/QRemote ( 6242): [RemoteAppWidgetManager.java:239:doInBackground()] oooooo 140407:doinBack arr:0
,V/QRemote ( 6242): [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.widget_ui_update
E/QRemote ( 6242): [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
D/QRemote ( 6242): [RemoteAppWidgetProvider.java:171:onReceive()] oooooo total:0
D/QRemote ( 6242): [RemoteAppWidgetProvider.java:172:onReceive()] oooooo selected:0
D/QRemote ( 6242): [RemoteAppWidgetProvider.java:173:onReceive()] oooooo arr:[]
D/QRemote ( 6242): [RemoteAppWidgetProvider.java:174:onReceive()] oooooo appWidgetId:3
D/QRemote ( 6242): [RemoteAppWidgetProvider.java:815:updateRemoteViews()] oooooo UpdateRemoteViews3:widgetId:3
D/QRemote ( 6242): [RemoteAppWidgetProvider.java:986:updateRemoteViews()] oooooo updateAppWidget5:widgetId:3]
,D/LGBluetoothAPIServer( 6053): [BTUI] onCreate()
,D/LGBluetoothAPIServer( 6053): [BTUI] onBind()
D/LGBluetoothAPIService( 1964): [BTUI] LGBluetoothAPIServiceConnection: connected to LGBluetoothAPIAdapter
D/LGBluetoothAPIService( 1964): Message: 100
V/BluetoothPbapService( 6053): Handler(): got msg=1
D/LGBluetoothAPIService( 1964): MESSAGE_BLUETOOTH_SERVICE_CONNECTED
,V/BluetoothPbapService( 6053): Pbap Service startRfcommSocketListener
,V/BluetoothPbapReceiver( 6053): PbapReceiver onReceive 
V/BluetoothPbapReceiver( 6053): ***********action = android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothPbapReceiver( 6053): ***********state = 12
V/BluetoothPbapService( 6053): Pbap Service initSocket
D/BluetoothManagerService( 1030): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
W/BluetoothAdapter( 6053): getBluetoothService() called with no BluetoothManagerCallback
D/LGBluetoothServiceAdapter( 6053): [BTUI] createSocketChannel FD=75 mFd=73
V/BluetoothPbapService( 6053): Succeed to create listening socket 
V/BluetoothPbapService( 6053): Accepting socket connection...
D/LocalBluetoothProfileManager( 6091): Adding local A2DP profile
D/BluetoothManagerService( 1030): Message: 30
,D/LocalBluetoothProfileManager( 6091): Adding local HEADSET profile
D/BluetoothManagerService( 1030): Message: 30
D/BluetoothManagerService( 1030): Message: 30
D/BluetoothManagerService( 1030): Message: 30
,D/BluetoothAdapterProperties( 6053): Discoverable Timeout:120
D/LGBluetoothDeviceModeControllManager( 6053): adapterPropertyChangedCallback on  LGAdapter : do nothing - 9
D/BluetoothAdapterProperties( 6053): Scan Mode:21
D/LGBluetoothDeviceModeControllManager( 6053): getDeviceMode  deviceMode 0
D/LocalBluetoothProfileManager( 6091): Adding local MAP profile
D/BluetoothMap( 6091): Create BluetoothMap proxy object
D/BluetoothManagerService( 1030): Message: 30
D/BluetoothManagerService( 1030): Message: 30
D/LocalBluetoothProfileManager( 6091): LocalBluetoothProfileManager construction complete
V/BluetoothPbapService( 6053): Pbap Service onBind
D/LGBluetoothUserBindClient( 6091): [BTUI] initUserBindClient
,W/ContextImpl( 6091): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.android.settings.bluetooth.LGBluetoothUserBindClient.initUserBindClient:90 com.android.settings.bluetooth.LGBluetoothUserBindClient.<init>:55 com.android.settings.bluetooth.LGBluetoothUserBindClient.getInstance:47 
D/DockEventReceiver( 6091): finishStartingService: stopping service
D/BluetoothA2dp( 6091): Proxy object connected
D/A2dpProfile( 6091): Bluetooth service connected
,D/BluetoothHeadset( 6091): Proxy object connected
D/HeadsetProfile( 6091): Bluetooth service connected
D/BluetoothInputDevice( 6091): Proxy object connected
D/HidProfile( 6091): Bluetooth service connected
D/BluetoothPan( 6091): BluetoothPAN Proxy object connected
D/PanProfile( 6091): Bluetooth service connected
D/BluetoothMap( 6091): Proxy object connected
D/MapProfile( 6091): Bluetooth service connected
,D/BluetoothMap( 6091): getConnectedDevices()
V/BluetoothMapService( 6053): getConnectedDevices()
D/BluetoothPbap( 6091): Proxy object connected
D/PbapServerProfile( 6091): Bluetooth service connected
D/LGBluetoothUserBindClient( 6091): [BTUI] onServiceConnected
D/BluetoothPermissionRequest( 6091): onReceive
D/LGBluetoothFeatureConfig( 6091): isPrivacyLogsEnabled : true
D/LGBluetoothUtils( 6091): [BTUI] FileNotFound: readProperty
D/LGBluetoothResetSettingReceiver( 6091): return without doing reset settings.
I/ActivityManager( 1030): Killing 5494:com.android.gallery3d/u0a27 (adj 15): empty #17
W/libprocessgroup( 1030): failed to open /acct/uid_10027/pid_5494/cgroup.procs: No such file or directory
,V/BluetoothOppReceiver( 6053): Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_ON
I/LGBluetoothOppAdapter( 6053): [BTUI] startOppService()
V/BluetoothOppManager( 6053): restoreApplicationData! falsefalsenullnull
,D/LGBluetoothFeatureConfig( 6053): isPrivacyLogsEnabled : true
,V/BtOppService( 6053): onCreate
V/BluetoothOppNotification( 6053): send message
V/BtOppService( 6053): Starting RfcommListener
D/BluetoothOppPreference( 6053): Dumping Names:  
,D/BluetoothOppPreference( 6053): {}
D/BluetoothOppPreference( 6053): Dumping Channels:  
D/BluetoothOppPreference( 6053): {}
V/BtOppService( 6053): onStartCommand
V/BluetoothFtpReceiver( 6053): BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothFtpReceiver( 6053): BluetoothFtpReceiver Start Service
V/BtOppService( 6053): pendingUpdate is true keepUpdateThread is false sListenStarted is true
V/BtOppService( 6053): Deleted complete outbound shares, number =  0
V/BluetoothOppNotification( 6053): new notify threadi!
V/BluetoothOppNotification( 6053): send delay message
V/BtOppService( 6053): start RfcommListener
V/BluetoothOppProvider( 6053): starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
V/BtOppService( 6053): Deleted complete inbound failed shares, number = 0
V/BluetoothOppProvider( 6053): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
V/BluetoothOppProvider( 6053): starting query, database is not null; projection[0] is _id; selection is direction=1 AND status=200 AND visibility=1; selectionArgs is null; sort is _id.
V/BtOppService( 6053): RfcommListener started
,V/BtOppRfcommListener( 6053): Starting RFCOMM listener....
D/BluetoothManagerService( 1030): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
W/BluetoothAdapter( 6053): getBluetoothService() called with no BluetoothManagerCallback
V/BluetoothOppProvider( 6053): created cursor android.database.sqlite.SQLiteCursor@29f0ea on behalf of 
D/LGBluetoothServiceAdapter( 6053): [BTUI] createSocketChannel FD=79 mFd=75
V/BtOppRfcommListener( 6053): Started RFCOMM listener....
I/BtOppRfcommListener( 6053): Accept thread started.
V/BtOppRfcommListener( 6053): Accepting connection...
V/BluetoothOppProvider( 6053): created cursor android.database.sqlite.SQLiteCursor@183f0fdb on behalf of 
V/BluetoothOppNotification( 6053): mUpdateCompleteNotification = true
,V/BluetoothOppProvider( 6053): starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
D/BluetoothAdapterService( 6053): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2dc453d0
V/BluetoothOppProvider( 6053): created cursor android.database.sqlite.SQLiteCursor@2810aa78 on behalf of 
V/BluetoothFtpService( 6053): Ftp Service onCreate
I/BluetoothFtpService( 6053): Ftp Service onCreate
V/BluetoothFtpService( 6053): Ftp Service onStartCommand
V/BluetoothFtpService( 6053): action: android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothFtpService( 6053): Starting Listening on sockets
V/BtOppService( 6053): ContentObserver received notification
V/BluetoothSapReceiver( 6053): [BTUI] checkServiceStart
V/BluetoothSapReceiver( 6053): [BTUI] region:EU country:EU
V/BluetoothSapReceiver( 6053): SapReceiver onReceive 
V/BluetoothSapReceiver( 6053): action = android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothSapReceiver( 6053):  Bluetooth Adapter state = 12
V/BluetoothSapReceiver( 6053): Calling SAP service start service with action = null
V/BtOppService( 6053): pendingUpdate is true keepUpdateThread is false sListenStarted is true
V/BluetoothOppProvider( 6053): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
V/BluetoothOppProvider( 6053): created cursor android.database.sqlite.SQLiteCursor@192e31b6 on behalf of 
V/BluetoothOppNotification( 6053): outbound: succ-0  fail-0
V/BluetoothOppProvider( 6053): created cursor android.database.sqlite.SQLiteCursor@3494ceb7 on behalf of 
V/BluetoothOppNotification( 6053): update too frequent, put in queue
V/BtOppService( 6053): ContentObserver received notification
V/BluetoothFtpService( 6053): Handler(): got msg=1
V/BluetoothFtpService( 6053): Ftp Service startRfcommSocketListener
V/BluetoothFtpService( 6053): Ftp Service initSocket
D/BluetoothManagerService( 1030): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
V/BluetoothOppNotification( 6053): outbound notification was removed.
W/BluetoothAdapter( 6053): getBluetoothService() called with no BluetoothManagerCallback
V/BtOppService( 6053): pendingUpdate is true keepUpdateThread is false sListenStarted is true
V/BluetoothOppProvider( 6053): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
D/LGBluetoothServiceAdapter( 6053): [BTUI] createSocketChannel FD=80 mFd=79
V/BluetoothFtpService( 6053): Succeed to create listening socket on channel 20
V/BluetoothOppProvider( 6053): created cursor android.database.sqlite.SQLiteCursor@12e1f624 on behalf of 
V/BluetoothOppNotification( 6053): update too frequent, put in queue
V/BluetoothFtpService:RfcommSocketAcceptThread( 6053): Run Accept thread
,D/BluetoothAdapterService( 6053): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2dc453d0
D/AuthorizationBluetoothService( 2126): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
V/BluetoothSapService( 6053): Sap Service onCreate
V/BluetoothOppProvider( 6053): starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
V/BluetoothOppProvider( 6053): created cursor android.database.sqlite.SQLiteCursor@211d9f53 on behalf of 
V/BluetoothSapService( 6053): action: android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothSapService( 6053): state: 12
V/BtOppService( 6053): pendingUpdate is false keepUpdateThread is false sListenStarted is true
V/BluetoothSapService( 6053): Starting SAP server process
V/BluetoothOppNotification( 6053): inbound: succ-0  fail-0
V/BluetoothOppNotification( 6053): inbound notification was removed.
V/BluetoothOppProvider( 6053): starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
V/BluetoothSapService( 6053): SAP Service startRfcommListenerThread
V/BluetoothOppProvider( 6053): created cursor android.database.sqlite.SQLiteCursor@33605d89 on behalf of 
V/BluetoothSapService( 6053): Sap Service initRfcommSocket
D/BluetoothManagerService( 1030): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,W/BluetoothAdapter( 6053): getBluetoothService() called with no BluetoothManagerCallback
D/LGBluetoothServiceAdapter( 6053): [BTUI] createSocketChannel FD=82 mFd=80
V/BluetoothSapService( 6053): Succeed to create listening socket 
V/BluetoothSapService( 6053): Accepting socket connection...
W/sapd    ( 6333): type=1400 audit(0.0:161): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6838 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
W/sapd    ( 6333): type=1400 audit(0.0:162): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6838 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
V/BT_SAP  ( 6333): Event pipe created
V/BT_SAP  ( 6333): create_server_socket qcom.sap.server
V/BT_SAP  ( 6333): created socket fd 6
,I/wpa_supplicant( 6108): wlan0: CTRL-EVENT-SCAN-STARTED 
,D/WifiMonitor( 1030): Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1030): WifiMonitor:wlan0 cnt=13 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1030): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1030): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
V/BluetoothOppNotification( 6053): new notify threadi!
V/BluetoothOppNotification( 6053): send delay message
,V/BluetoothOppProvider( 6053): starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
V/BluetoothOppProvider( 6053): created cursor android.database.sqlite.SQLiteCursor@1d7dc18e on behalf of 
V/BluetoothOppNotification( 6053): mUpdateCompleteNotification = true
V/BluetoothOppProvider( 6053): starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
V/BluetoothOppProvider( 6053): created cursor android.database.sqlite.SQLiteCursor@2158ddaf on behalf of 
V/BluetoothOppNotification( 6053): outbound: succ-0  fail-0
V/BluetoothOppNotification( 6053): outbound notification was removed.
V/BluetoothOppProvider( 6053): starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
V/BluetoothOppProvider( 6053): created cursor android.database.sqlite.SQLiteCursor@2abbe5bc on behalf of 
V/BluetoothOppNotification( 6053): inbound: succ-0  fail-0
V/BluetoothOppNotification( 6053): inbound notification was removed.
V/BluetoothOppProvider( 6053): starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
V/BluetoothOppProvider( 6053): created cursor android.database.sqlite.SQLiteCursor@1d684945 on behalf of 
,I/jxcore-log( 5996): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMultiplex.js
I/jxcore-log( 5996): 
,E/wpa_supplicant( 6108): USIM:  scard_init function
I/wpa_supplicant( 6108): Trying to associate with SSID 'NG700'
,E/WifiMonitor( 1030): WifiMonitor:wlan0 cnt=14 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
E/WifiMonitor( 1030): handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
D/WifiMonitor( 1030): Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
E/WifiMonitor( 1030): WifiMonitor:wlan0 cnt=15 dispatchEvent: WPS-AP-AVAILABLE 
W/WifiMonitor( 1030): couldn't identify event type - WPS-AP-AVAILABLE 
D/WifiMonitor( 1030): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
E/WifiMonitor( 1030): WifiMonitor:wlan0 cnt=16 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
E/WifiStateMachine( 1030):  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=3 known=0 got=3 bcn=0
E/WifiStateMachine( 1030):  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=3 known=0 got=3 bcn=0
E/WifiStateMachine( 1030):  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=3 known=0 got=3 bcn=0
E/WifiStateMachine( 1030):  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=3 known=0 got=3 bcn=0
I/WifiNative-HAL( 1030): startHal
E/wifi    ( 1030): getStaticLongField sWifiHalHandle 0x9884f8cc
E/WifiHAL ( 1030): Could not connect handle
D/wifi    ( 1030): halHandle = 0x0, mVM = 0xb487c280, mCls = 0x401782
I/WifiNative-HAL( 1030): Could not start hal
D/WifiNative-wlan0( 1030): doString: [BSS RANGE=0- MASK=0x21987]
,E/WifiStateMachine( 1030):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 16 0 rt=120204  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
,I/StatusBar.NetworkController( 1472): networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1472): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1472): refreshViews: Data not connected!! Set no data type icon / Roaming
W/Settings( 1030): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1030): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1030): NETWORK_STATE_CHANGED_ACTION [SCANNING]
,W/Settings( 1030): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1030): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1030): NETWORK_STATE_CHANGED_ACTION [CONNECTING]
E/WifiStateMachine( 1030):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 16 0 rt=120228  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
D/WifiServerServiceExt( 1030): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1030): setSupplicantStateASSOCIATING
I/StatusBar.NetworkController( 1472): networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1472): mWifiConnected = false, mWifiLevel = 0
,D/StatusBar.NetworkController( 1472): refreshViews: Data not connected!! Set no data type icon / Roaming
D/PostponalbeReceiver( 5135): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
V/WiFiOffLoadBroadcast( 6091): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6091): MCCMNC not supported: null
D/QRemote ( 6242): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6242): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 6242): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
D/PostponalbeReceiver( 5135): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,V/WiFiOffLoadBroadcast( 6091): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 6091): MCCMNC not supported: null
D/QRemote ( 6242): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6242): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 6242): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,I/wpa_supplicant( 6108): wlan0: Associated with c0:ff:d4:d3:aa:48
,D/WifiMonitor( 1030): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
E/WifiMonitor( 1030): WifiMonitor:wlan0 cnt=17 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
D/WifiMonitor( 1030): Event [IFNAME=wlan0 Associated with c0:ff:d4:d3:aa:48]
E/WifiStateMachine( 1030):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 17 0 rt=120298  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
E/WifiStateMachine( 1030):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 17 0 rt=120298  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
E/WifiMonitor( 1030): WifiMonitor:wlan0 cnt=18 dispatchEvent: Associated with c0:ff:d4:d3:aa:48
D/WifiMonitor( 1030): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1030): WifiMonitor:wlan0 cnt=19 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
E/WifiStateMachine( 1030):  DisconnectedState CMD_ASSOCIATED_BSSID 18 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=120300
E/WifiStateMachine( 1030):  ConnectModeState CMD_ASSOCIATED_BSSID 18 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=120300
E/WifiStateMachine( 1030):  DriverStartedState CMD_ASSOCIATED_BSSID 18 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=120301
E/WifiStateMachine( 1030):  SupplicantStartedState CMD_ASSOCIATED_BSSID 18 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=120301
E/WifiStateMachine( 1030):  DefaultState CMD_ASSOCIATED_BSSID 18 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=120301
E/WifiStateMachine( 1030):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 19 0 rt=120302  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: FOUR_WAY_HANDSHAKE
I/wpa_supplicant( 6108): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 6108): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
D/WifiMonitor( 1030): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1030): WifiMonitor:wlan0 cnt=20 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/WifiMonitor( 1030): Event [IFNAME=wlan0 WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]]
E/WifiMonitor( 1030): WifiMonitor:wlan0 cnt=21 dispatchEvent: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
W/WifiMonitor( 1030): couldn't identify event type - WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
D/WifiMonitor( 1030): Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]]
E/WifiMonitor( 1030): WifiMonitor:wlan0 cnt=22 dispatchEvent: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
E/WifiStateMachine( 1030):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 19 0 rt=120304  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: FOUR_WAY_HANDSHAKE
E/WifiMonitor( 1030): handleEvent 1  Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
D/WifiMonitor( 1030): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1030): WifiMonitor:wlan0 cnt=23 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/WifiServerServiceExt( 1030): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1030): setSupplicantStateASSOCIATED
E/WifiStateMachine( 1030):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 20 0 rt=120305  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: GROUP_HANDSHAKE
E/WifiStateMachine( 1030):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 20 0 rt=120306  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: GROUP_HANDSHAKE
,I/StatusBar.NetworkController( 1472): networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1472): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1472): refreshViews: Data not connected!! Set no data type icon / Roaming
W/Settings( 1030): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1030): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1030): NETWORK_STATE_CHANGED_ACTION [CONNECTING]
I/StatusBar.NetworkController( 1472): networkInfo=[type: WIFI[], state: CONNECTING/AUTHENTICATING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1472): mWifiConnected = false, mWifiLevel = 0
,W/Settings( 1030): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1030): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1030): NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
D/Tethering( 1030): sendTetherStateChangedBroadcast 1, 0, 0
E/WifiStateMachine( 1030):  DisconnectedState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=120322
E/WifiStateMachine( 1030):  ConnectModeState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=120322
D/PostponalbeReceiver( 5135): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
D/WifiServerServiceExt( 1030): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1030): setSupplicantStateFOUR_WAY_HANDSHAKE
D/StatusBar.NetworkController( 1472): refreshViews: Data not connected!! Set no data type icon / Roaming
D/WifiNative-wlan0( 1030): doString: [STATUS]
D/libc-netbsd(  308): default dns: query_ipv6=0, query_ipv4=0
D/WifiMonitor( 1030): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1030): WifiMonitor:wlan0 cnt=24 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/WifiNative-wlan0( 1030):    returned bssid=c0:ff:d4:d3:aa:48 ssid=NG700 id=0 mode=station pairwise_cipher=CCMP group_cipher=CCMP key_mgmt=WPA2-PSK wpa_state=COMPLETED p2p_device_address=02:9a:02:7b:60:ac address=c4:9a:02:7b:60:ac uuid=530d3fd0-1ba3-5409-a336-ff4e42af59a2
D/DSQN    ( 1030): DNSproblemNotiEnabled is disabled ignore DNS fail CB
I/WifiServiceExtension( 1030): setVHTCapabilityType  : false
V/WiFiOffLoadBroadcast( 6091): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,I/WifiServerServiceExt( 1030): wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
I/WifiServerServiceExt( 1030): setKeepAlivePacketInterval msec : 60
,W/Settings( 1030): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1030): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1030): NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
W/Settings( 1030): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1030): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1030): NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
I/StatusBar.NetworkController( 1472): networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1472): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1472): refreshViews: Data not connected!! Set no data type icon / Roaming
I/StatusBar.NetworkController( 1472): networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1472): mWifiConnected = false, mWifiLevel = 0
D/WiFiOffLoadBroadcast( 6091): MCCMNC not supported: null
D/StatusBar.NetworkController( 1472): refreshViews: Data not connected!! Set no data type icon / Roaming
D/ConnectivityService( 1030): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
D/ConnectivityService( 1030): Got NetworkAgent Messenger
D/ConnectivityService( 1030): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
D/ConnectivityService( 1030): NetworkAgent connected
E/WifiConfigStore( 1030): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/WifiNative-wlan0( 1030): doBoolean: SET_NETWORK 0 bssid any
D/QRemote ( 6242): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6242): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 6242): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,D/WifiNative-wlan0( 1030): SET_NETWORK 0 bssid any: returned true
D/WifiNative-wlan0( 1030): doBoolean: SAVE_CONFIG
D/PostponalbeReceiver( 5135): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
D/WifiNative-wlan0( 1030): SAVE_CONFIG: returned true
E/WifiConfigStore( 1030): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/WifiNative-wlan0( 1030): doBoolean: SET_NETWORK 0 bssid any
D/WifiNative-wlan0( 1030): SET_NETWORK 0 bssid any: returned true
D/WifiNative-wlan0( 1030): doBoolean: SAVE_CONFIG
D/WifiNative-wlan0( 1030): SAVE_CONFIG: returned true
V/WiFiOffLoadBroadcast( 6091): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/CommandListener(  308): Setting iface cfg
,E/WifiStateMachine( 1030): Start Dhcp Watchdog 1
D/DhcpStateMachine( 1030): StoppedState
D/DhcpStateMachine( 1030): StoppedState{ when=-1ms what=196609 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine( 1030): WaitBeforeStartState
E/WifiStateMachine( 1030):  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 23 0 rt=120376  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine( 1030):  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 23 0 rt=120376  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
D/WiFiOffLoadBroadcast( 6091): MCCMNC not supported: null
E/WifiStateMachine( 1030):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 23 0 rt=120377  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
D/WifiServerServiceExt( 1030): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1030): setSupplicantStateGROUP_HANDSHAKE
E/WifiStateMachine( 1030):  ObtainingIpState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1030):  L2ConnectedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1030):  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1030):  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1030):  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1030):  DefaultState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1030):  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 24 0 rt=120382  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
,D/QRemote ( 6242): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
E/WifiStateMachine( 1030):  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 24 0 rt=120382  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
D/QRemote ( 6242): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 6242): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
E/WifiStateMachine( 1030):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 24 0 rt=120383  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
,E/WifiStateMachine( 1030):  ObtainingIpState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:-1553184868] from screen [on:0 period:-1553184868]
E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-1553184867]
D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
D/UsbSettingsReceiver( 6091): [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
D/UsbSettingsReceiver( 6091): [AUTORUN] sys.usb.config = ptp_only,adb
D/UsbSettingsReceiver( 6091): [AUTORUN] sys.usb.state = ptp_only,adb
D/UsbSettingsReceiver( 6091): [AUTORUN] persist.sys.usb.config = ptp_only,adb
D/UsbSettingsReceiver( 6091): [AUTORUN] onReceive() : app userid = 0, current userid = 0
D/UsbSettingsControl( 6091): [AUTORUN] getUsbConnected() : connected=true
D/UsbSettingsReceiver( 6091): [AUTORUN] onReceive() : availableList=[wlan0]
D/UsbSettingsReceiver( 6091): [AUTORUN] onReceive() : activeList=[]
D/UsbSettingsReceiver( 6091): [AUTORUN] onReceive() : errorList=[]
D/UsbSettingsControl( 6091): [AUTORUN] isAutorunTimer() : mAutorunChanging=false
D/UsbSettingsReceiver( 6091): [AUTORUN] onReceive() : TetherState Changed=wlan0
D/UsbSettingsControl( 6091): [AUTORUN] setTetherStatus() : status=false
D/PostponalbeReceiver( 5135): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
D/StatusBar.NetworkController( 1472): refreshViews: Data not connected!! Set no data type icon / Roaming
D/ConnectivityService( 1030): updateNetworkScore for NetworkAgentInfo [WIFI () - 100] to 60
,E/WifiStateMachine( 1030):  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1030):  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
V/WiFiOffLoadBroadcast( 6091): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
E/WifiStateMachine( 1030):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1030):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1030):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1030):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
D/ConnectivityService( 1030): Update of LinkProperties for NetworkAgentInfo [WIFI () - 100]; created=false
E/WifiStateMachine( 1030):  ObtainingIpState CMD_PRE_DHCP_ACTION 0 0 txpkts=1,0,0
E/WifiStateMachine( 1030):  L2ConnectedState CMD_PRE_DHCP_ACTION 0 0 txpkts=1,0,0
D/WifiNative-wlan0( 1030): doBoolean: DRIVER SETSUSPENDMODE 0
D/WiFiOffLoadBroadcast( 6091): MCCMNC not supported: null
D/QRemote ( 6242): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6242): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 6242): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,D/PostponalbeReceiver( 5135): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
V/WiFiOffLoadBroadcast( 6091): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6091): MCCMNC not supported: null
I/wpa_supplicant( 6108): wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 0
D/QRemote ( 6242): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/WifiNative-wlan0( 1030): DRIVER SETSUSPENDMODE 0: returned true
,D/WifiNative-wlan0( 1030): doBoolean: SET ps 0
D/QRemote ( 6242): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
D/WifiNative-wlan0( 1030): SET ps 0: returned true
D/WifiNative-wlan0( 1030): doBoolean: DRIVER BTCOEXMODE 1
I/QRemote ( 6242): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
I/wpa_supplicant( 6108): wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 1
D/WifiNative-wlan0( 1030): DRIVER BTCOEXMODE 1: returned true
E/WifiStateMachine( 1030): CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
D/LGWifiP2pService( 1030): InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@bd55e7d target=com.android.internal.util.StateMachine$SmHandler }
V/DhcpStateMachine( 1030): Current State is mWaitBeforeStartState.
D/LGWifiP2pService( 1030): P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@bd55e7d target=com.android.internal.util.StateMachine$SmHandler }
V/LgDhcpStateMachineHelper( 1030): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
D/DhcpStateMachine( 1030): WaitBeforeStartState{ when=-1ms what=196615 target=com.android.internal.util.StateMachine$SmHandler }
V/LgDhcpStateMachineHelper( 1030): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700" is not exist.
D/DhcpStateMachine( 1030): DHCP Start wake lock is acquired.
D/WifiServerServiceExt( 1030): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1030): setSupplicantStateCOMPLETED
,D/DhcpStateMachine( 1030): DHCPV4 request on wlan0
,V/LgDhcpStateMachineHelper( 1030): [bssid] hash key :c0:ff:d4:d3:aa:48
D/LgDhcpStateMachineHelper( 1030): dhcp.ap.macaddress = c0:ff:d4:d3:aa:48
W/dhcpcd  ( 6357): type=1400 audit(0.0:163): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6838 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,W/dhcpcd  ( 6357): type=1400 audit(0.0:164): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6838 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
I/dhcpcd  ( 6357): version 5.5.6 starting
E/dhcpcd  ( 6357): get_duid: m
D/dhcpcd  ( 6357): wlan0: using ClientID 01:c4:9a:02:7b:60:ac
D/dhcpcd  ( 6357): wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason PREINIT
,D/dhcpcd  ( 6357): getUsingAPMacAddress: c0:ff:d4:d3:aa:48 , return 1
D/dhcpcd  ( 6357): [read_lease] unlink /data/misc/dhcp/dhcpcd-wlan0.lease, link /data/misc/dhcp/dhcpcd-wlan0-c0:ff:d4:d3:aa:48.lease2
D/dhcpcd  ( 6357): wlan0: reading lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
,I/dhcpcd  ( 6357): wlan0: rebinding lease of 192.168.1.141
D/dhcpcd  ( 6357): wlan0: sending REQUEST (xid 0xfdae0dfe), next in 3.84 seconds
I/jxcore-log( 5996): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
I/jxcore-log( 5996): 
,I/jxcore-log( 5996): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
I/jxcore-log( 5996): 
,I/jxcore-log( 5996): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js
I/jxcore-log( 5996): 
I/jxcore-log( 5996): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
I/jxcore-log( 5996): 
I/dhcpcd  ( 6357): wlan0: acknowledged 192.168.1.141 from 192.168.1.1
,I/dhcpcd  ( 6357): wlan0: leased 192.168.1.141 for 86400 seconds
D/dhcpcd  ( 6357): wlan0: adding IP address 192.168.1.141/24
,D/dhcpcd  ( 6357): wlan0: adding route to 192.168.1.0/24
D/dhcpcd  ( 6357): wlan0: adding default route via 192.168.1.1
D/dhcpcd  ( 6357): wlan0: writing lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
D/dhcpcd  ( 6357): getUsingAPMacAddress: c0:ff:d4:d3:aa:48 , return 1
D/dhcpcd  ( 6357): write_lease_ext: /data/misc/dhcp/dhcpcd-wlan0-c0:ff:d4:d3:aa:48.lease2
D/dhcpcd  ( 6357): wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason REBOOT
E/WifiStateMachine( 1030):  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1030):  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1030):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1030):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1030):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1030):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
D/ConnectivityService( 1030): Update of LinkProperties for NetworkAgentInfo [WIFI () - 100]; created=false
E/WifiStateMachine( 1030):  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0 v4
E/WifiStateMachine( 1030):  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4
E/WifiStateMachine( 1030):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0 v4
E/WifiStateMachine( 1030):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4
E/WifiStateMachine( 1030):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4
E/WifiStateMachine( 1030):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0 v4
D/ConnectivityService( 1030): Update of LinkProperties for NetworkAgentInfo [WIFI () - 100]; created=false
,D/DhcpStateMachine( 1030): DHCPV4 succeeded on wlan0
,D/LgDhcpStateMachineHelper( 1030): CheckDhcpDirectory [Lease File Count] : 3
V/LgDhcpStateMachineHelper( 1030): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
D/LgDhcpStateMachineHelper( 1030): checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.141
V/LgDhcpStateMachineHelper( 1030): Add DhcpResults: IP address 192.168.1.141/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 86400 seconds
V/DhcpStateMachine( 1030): Current State is mWaitBeforeStartState.
V/LgDhcpStateMachineHelper( 1030): bShouldSendDhcpAction Result: true
E/WifiStateMachine( 1030):  ObtainingIpState CMD_POST_DHCP_ACTION 1 0 OK  v4
E/WifiStateMachine( 1030):  L2ConnectedState CMD_POST_DHCP_ACTION 1 0 OK  v4
D/LGWifiP2pService( 1030): InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1030): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0( 1030): doBoolean: DRIVER BTCOEXMODE 2
I/wpa_supplicant( 6108): wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
D/DhcpStateMachine( 1030): DHCP Start/Renew wake lock is released.
D/WifiNative-wlan0( 1030): DRIVER BTCOEXMODE 2: returned true
,D/WifiNative-wlan0( 1030): doBoolean: DRIVER SETSUSPENDMODE 1
I/wpa_supplicant( 6108): wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 1
D/WifiNative-wlan0( 1030): DRIVER SETSUSPENDMODE 1: returned true
D/WifiNative-wlan0( 1030): doBoolean: SET ps 1
,D/DhcpStateMachine( 1030): RunningState
D/WifiNative-wlan0( 1030): SET ps 1: returned true
E/WifiStateMachine( 1030):  ObtainingIpState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
E/WifiStateMachine( 1030):  L2ConnectedState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
E/WifiStateMachine( 1030): WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
D/ConnectivityService( 1030): Update of LinkProperties for NetworkAgentInfo [WIFI () - 100]; created=false
D/ConnectivityService( 1030): ignoring duplicate network state non-change
,W/Settings( 1030): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1030): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1030): NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
I/StatusBar.NetworkController( 1472): networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/StatusBar.NetworkController( 1472): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1472): refreshViews: Data not connected!! Set no data type icon / Roaming
E/WifiStateMachine( 1030): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
D/ConnectivityService( 1030): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
D/ConnectivityService( 1030): Adding iface wlan0 to network 100
I/StatusBar.NetworkController( 1472): networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1472): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1472): refreshViews: Data not connected!! Set no data type icon / Roaming
,E/ConnectivityService( 1030): Unexpected mtu value: 0, wlan0
D/ConnectivityService( 1030): Adding Route [fe80::/64 -> :: wlan0] to network 100
,D/ConnectivityService( 1030): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 100
D/ConnectivityService( 1030): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 100
D/ConnectivityService( 1030): addLocalRoutetoDefaultNetwork
D/ConnectivityService( 1030): defaultNAI is null or Wi-Fi no need to add Loacal route to default network. WiFi netid = 100
D/ConnectivityService( 1030): Setting Dns servers for network 100 to [/192.168.1.1]
W/Settings( 1030): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1030): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1030): NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
,D/WifiHS20( 1030): [PASSPOINT] passpointNotification: hs20AP list is checked
I/StatusBar.NetworkController( 1472): networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1472): mWifiConnected = true, mWifiLevel = 2
D/StatusBar.NetworkController( 1472): refreshViews: Data not connected!! Set no data type icon / Roaming
W/Settings( 1030): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1030): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1030): NETWORK_STATE_CHANGED_ACTION [CONNECTED]
V/WfdStateTracker( 1964): handleWifiStateChangedEvent: 1
D/WifiHS20( 1030): [PASSPOINT] passpointNotification: hs20AP list is checked
,W/Settings( 1030): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1030): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1030): NETWORK_STATE_CHANGED_ACTION [CONNECTED]
D/Nat464Xlat( 1030): requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
D/ConnectivityService( 1030): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService( 1030): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService( 1030): rematching NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService( 1030):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService( 1030):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1030):     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
D/ConnectivityService( 1030):   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1030):     satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:true
D/ConnectivityService( 1030): currentScore = 0, newScore = 20
D/ConnectivityService( 1030):    accepting network in place of null
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1030): DefaultState{ when=-2ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1030): Connected
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1030): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
I/StatusBar.NetworkController( 1472): networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1472): mWifiConnected = true, mWifiLevel = 2
D/StatusBar.NetworkController( 1472): refreshViews: Data not connected!! Set no data type icon / Roaming
D/ConnectivityService( 1030): sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1030): Checking http://clients3.google.com/generate_204 on "NG700"
D/WIFI    ( 1030): new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    ( 1030):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/TelephonyNetworkFactory-1( 1866): new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/TelephonyNetworkFactory-1( 1866):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
D/ConnectivityService( 1030): Setting tx/rx TCP buffers to 524288,1048576,2097152,262144,524288,1048576
D/libc-netbsd(  308): res_queryN name = clients3.google.com, class = 1, type = 28
E/ConnectivityService( 1030): [lg_data] Adding agent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.141/24,fe80::c69a:2ff:fe7b:60ac/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
D/CSLegacyTypeTracker( 1030): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
,D/ConnectivityService( 1030): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService( 1030): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/CSLegacyTypeTracker( 1030): [e] list.add(nai) empty : false size: 1
D/ConnectivityService( 1030): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.141/24,fe80::c69a:2ff:fe7b:60ac/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
D/ConnectivityService( 1030): validation of new default Network = false
D/ConnectivityService( 1030): Default network via Wi-Fi connected. start DSQN
D/DSQN    ( 1030): enableDataServiceNotify 
D/DSQN    ( 1030): start dsqn bin
D/libc-netbsd(  308): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  308): res_queryN name = 2.android.pool.ntp.org, class = 1, type = 1
D/PostponalbeReceiver( 5135): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
D/LocSvc_java( 1030): Sending msg: 4 arg1:1 arg2:1
D/LocSvc_java( 1030): getAGpsConnectionInfo connType - 4
D/LocSvc_java( 1030): updateNetworkState connTyp: 4 available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java( 1030): ignore wifi update if we are not in OPENING or CLOSING
D/LocSvc_java( 1030): Sending msg: 5 arg1:0 arg2:1
D/libc-netbsd(  308): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  308): res_queryN name = europe.pool.ntp.org, class = 1, type = 1
,D/ConnectivityService( 1030): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService( 1030):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1030):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1030): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityManager.CallbackHandler( 1472): CM callback handler got msg 524290
D/libc-netbsd(  308): res_queryN name = clients3.google.com, class = 1, type = 1
,D/TelephonyIcons( 1472): null signal icon name: drawable/stat_sys_signal_null
D/StatusBar.NetworkController( 1472): refreshViews: Data not connected!! Set no data type icon / Roaming
V/WiFiOffLoadBroadcast( 6091): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/StatusBar.NetworkController( 1472): refreshViews: Data not connected!! Set no data type icon / Roaming
D/libc-netbsd(  308): res_queryN name = 2.android.pool.ntp.org succeed
W/dsqn    ( 6407): type=1400 audit(0.0:165): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6838 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
D/WiFiOffLoadBroadcast( 6091): MCCMNC not supported: null
,W/dsqn    ( 6407): type=1400 audit(0.0:166): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6838 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,D/libc-netbsd(  308): res_queryN name = europe.pool.ntp.org succeed
D/QRemote ( 6242): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6242): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 6242): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
D/libc-netbsd(  308): res_queryN name = clients3.google.com succeed
D/PostponalbeReceiver( 5135): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,V/NetworkPolicy( 1030): [LG_RESTRICTED] checkMobilePolicy_type()
E/DSQN    ( 6407): DSQN ssw
V/WiFiOffLoadBroadcast( 6091): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/LGDataListener(  308): argv[0]=dsqncommand
D/LGDataListener(  308): argv[1]=wlan0
D/LGDataListener(  308): argv[2]=1
D/LGDataListener(  308): notifyDSQN DSQN STARTMONITOR wlan0 1
D/WiFiOffLoadBroadcast( 6091): MCCMNC not supported: null
D/DSQN    ( 1030): DSQM DsqnNotification wlan0  1
D/DSQN    ( 1030): start to monitor internet connection
D/QRemote ( 6242): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6242): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 6242): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,D/PostponalbeReceiver( 5135): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
I/PCSuite ( 6146): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
D/PCSuite ( 6146): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 6091): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6091): MCCMNC not supported: null
D/QRemote ( 6242): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6242): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
D/QRemote ( 6242): [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1030): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Tue, 02 Feb 2016 19:18:50 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1454440730583], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1454440730552]}
I/QRemote ( 6242): [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1030): Don't send network conditions - lacking user consent.
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1030): Validated
I/QRemote ( 6242): [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
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
D/ConnectivityManager.CallbackHandler( 1472): CM callback handler got msg 524290
D/WIFI    ( 1030): new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    ( 1030):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService( 1030): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
D/TelephonyNetworkFactory-1( 1866): new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/TelephonyNetworkFactory-1( 1866):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
D/PostponalbeReceiver( 5135): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,I/PCSuite ( 6146): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
D/PCSuite ( 6146): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 6091): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6091): MCCMNC not supported: null
,D/TelephonyIcons( 1472): null signal icon name: drawable/stat_sys_signal_null
D/StatusBar.NetworkController( 1472): refreshViews: Data not connected!! Set no data type icon / Roaming
D/StatusBar.NetworkController( 1472): refreshViews: Data not connected!! Set no data type icon / Roaming
D/QRemote ( 6242): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6242): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
D/QRemote ( 6242): [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
I/QRemote ( 6242): [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
I/QRemote ( 6242): [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
D/LocSvc_java( 1030): NTP server : europe.pool.ntp.org
D/LocSvc_java( 1030): NTP server returned: 1454440731074 (Tue Feb 02 20:18:51 GMT+01:00 2016) reference: 122558 certainty: 60 system time offset: 424
D/LocSvc_java( 1030): Sending msg: 10 arg1:0 arg2:1
,D/UEI.SmartControl( 5809): Internal timer expired: 2
D/UEI.SmartControl( 5809): unbind internal service
,D/serial_port( 5809): close(fd = 24)
I/UEI.SmartControl( 5809): Serial port is closed.
,E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1553181856] gl rssi=-64 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1553181853] gl rssi=-64 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
,D/StatusBar.NetworkController( 1472): refreshViews: Data not connected!! Set no data type icon / Roaming
,V/WifiInternetCheck( 1030): Single check msg out of sync, ignoring.
,D/ConnectivityService( 1030): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/GpsLocationProvider( 1030): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
D/Tethering( 1030): MasterInitialState.processMessage what=3
D/AlarmManagerService( 1030): Setting time of day to sec=1454440733
W/AlarmManagerService( 1030): Unable to set rtc to 1454440733: Invalid argument
,D/KeyguardUpdateMonitor( 1472): handleTimeUpdate
,I/SecureClockService( 1964): Intent.ACTION_TIME_CHANGED 
I/[SystemUI]Clock( 1472): onReceive = android.intent.action.TIME_SET
I/LgeClockWidgetControlView( 1472): time changed, timezoneChanged : false
D/LIA_Informant_Tips_DateChangeManager( 2704): onReceive() : ACTION_TIME_CHANGED
I/LIA_Informant_Tips_LogTracer( 2704): [Log Tracer - Schedule Transition] Time Change Event Received : 2016-02-02 20:18:53...... Request
I/LIA_Informant_Tips_LogTracer( 2704): [Log Tracer - Schedule Transition] UserGuide, DATE_UPDATE : working count : 6, total count : 163, new day : false...... Request
D/LIA_Informant_Tips_DateChangeManager( 2704): DateInfo : SmartTips Total Working Day Count = 163
D/LIA_Informant_Tips_DateChangeManager( 2704): DateInfo : UserGuide Working Duration Count = 6
D/LIA_Informant_Tips_DateChangeManager( 2704): DateInfo : Last Date Check Time = 2016-02-02 20:18:53
W/ActivityManager( 1030): getTasks: caller 10029 is using old GET_TASKS but privileged; allowing
D/PostponalbeReceiver( 5135): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
,W/ContextImpl( 5135): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
I/[LGHome]LGDateChangeReceiver( 2082): [LGDateChangeReceiver.java:78:updateCalendarShortcut()]date=2 currentDate=-1 dayofweek=3 currentDayOfWeek=-1
I/[LGHome]LGCalendarIcon( 2082): [LGCalendarIcon.java:214:makeCalendarBitmap()]Locale = en_US dayofweek= Tue date= 2
,I/[LGHome]LGCalendarIcon( 2082): [LGCalendarIcon.java:214:makeCalendarBitmap()]Locale = en_US dayofweek= Tue date= 2
I/[LGHome]Launcher( 2082): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/NetworkMonitor( 5182): type=WIFI subType= reason=null isConnected=true
,D/[Concierge]Service( 2607): onStartCommand(). Type : 9
I/ActivityManager( 1030): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=6435 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,I/ActivityManager( 1030): Start proc com.google.android.apps.books for service com.google.android.apps.books/.service.SyncService: pid=6455 uid=10054 gids={50054, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/art     (  337): Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 378us total 17.309ms
,I/art     (  337): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 295us total 14.148ms
,I/AppUp4:AppBoxCP( 6435): onCreate
W/AppUp4:DB( 6435):  [AppBoxDatabaseHelper] construct
I/art     (  337): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 253us total 12.884ms
,I/AppUp4:DB( 6435):  setFingerPrint start
,I/AppUp4:DB( 6435):  newfinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys SDK version = 21
I/AppUp4:DB( 6435):  beforefinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys
,I/AppUp4:DB( 6435):  SDK version = 21
I/AppUp4:DB( 6435):  beforefinger == newfinger no write in DB
I/ActivityManager( 1030): Start proc com.android.gallery3d for service com.android.gallery3d/com.lge.gallery.picasa.PicasaService: pid=6472 uid=10027 gids={50027, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
,D/AppUp4:AppBoxApplication( 6435): AppBoxApplication onCreate()
I/NetworkStateForAutoUpdateMonitor( 6435): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 6435): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 6435): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 6435): [onReceive] request level :IDLE....
I/AppUp4:CustModeStarterReceiver( 6435): onReceive
,W/ResourcesManager( 6472): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6472): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 6472): Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
W/ResourcesManager( 6472): Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
D/LgDataFeature( 6435): LgDataFeature() Constructor: none
D/LgDataFeature( 6435): LgDataFeature() Constructor Done, null
,D/AppUp4:CustFacade( 6435): Context : android.app.ReceiverRestrictedContext@352ca793
D/AppUp4:CustFacade( 6435): isCustomizationCompleted : false
D/AppUp4:CustFacade( 6435): isPhone : true
D/AppUp4:CustModeStarterReceiver( 6435): begin check event
I/AppUp4:CustModeStarterReceiver( 6435): Event For GoodConnectivity
D/AppUp4:CustModeStarterReceiver( 6435): runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
D/AppUp4:CustModeStarterReceiver( 6435): call method handleAsyncCustNotification.
D/AppUp4:CustModeStarterReceiver( 6435): handleAsync isTriedOnce : false
E/AppUp4:CustModeStarterReceiver( 6435): handleAsyncCustNotification do not startCustService
,I/ActivityManager( 1030): Start proc com.android.chrome for service com.android.chrome/com.google.android.apps.chrome.sync.ChromeBrowserSyncAdapterService: pid=6491 uid=10057 gids={50057, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager( 1030): Killing 5517:com.lge.lockscreensettings/u0a80 (adj 15): empty #17
D/LGDMClient( 3984): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 3984): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
W/ContextImpl( 3984): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,W/libprocessgroup( 1030): failed to open /acct/uid_10080/pid_5517/cgroup.procs: No such file or directory
W/ContextImpl( 3984): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,I/AppConfig( 6472): Total System Memory = 2995761152
D/SystemHelper( 6472): region [EU], country [EU], operator [OPEN], sub-operator []
V/DownloadManager( 3355): Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
I/ReaderUtils( 6455): PortraitW 1440 LandscapeW 2392 SmallestSize 1340 LargestSize 2392 textZoom 4.4999995 isTablet false Memory 256
V/DownloadManager( 3355): DownloadService onCreate
,D/LGDMClient( 3984): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=3, isUserType=1
I/DownloadManager( 3355): in removeSpuriousFiles
V/DownloadManager( 3355): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
I/LGDMClient( 3984): [DmServiceProcessor.java] [processNetworkChanged()] : [91] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
V/DownloadManager( 3355): created cursor android.database.sqlite.SQLiteCursor@7e656a9 on behalf of 3355
I/jxcore-log( 5996): Test app app.js loaded
I/jxcore-log( 5996): 
I/DownloadManager( 3355): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGMyGuide_4.40.09_COM_COM_20150430011620058_RELG-D855.apk
I/DownloadManager( 3355): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGBackup_4.50.37_COM_COM_20150608234245157.apk
I/DownloadManager( 3355): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/CalendarProvider_4.2.8_COM_COM_20150304234552863_RELG-D855.apk
I/DownloadManager( 3355): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calendar_4.40.16_COM_COM_20150304234554754_RELG-D855.apk
I/DownloadManager( 3355): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.10_COM_COM_20150521235426173_RELG-D855.apk
I/DownloadManager( 3355): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQVoiceplusN_2.3.3_COM_COM_20150604065210803.apk
I/DownloadManager( 3355): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.11_COM_COM_v2_20150911144028620_RELG-D855_21.apk
I/DownloadManager( 3355): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQMemoplus(LG-D855_user)_20150902050954661.apk
I/DownloadManager( 3355): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/RemoteCall_4.1.10_COM_COM_20150817053748728.apk
I/DownloadManager( 3355): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/rspermlge(6713)_20150901080430397.apk
I/DownloadManager( 3355): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGBackup_4.51.57_COM_COM_8275_2_20151201044833536_RELG-D855_21.apk
I/chromium( 5996): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5996): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5996): 	Automate Bluetooth MAC address resolution: true, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5996): 	Provide Bluetooth MAC address timeout in milliseconds: 40000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5996): 	Bluetooth MAC address: 58:3F:54:73:64:C0, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5996): 	Discovery mode: WIFI, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5996): 	Peer expiration time in milliseconds: 60000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5996): 	Advertise mode: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5996): 	Advertise TX power level: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5996): 	Scan mode: 1
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5996): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1b82a4ce added. We now have 1 listener(s)
I/ActivityManager( 1030): Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=6518 uid=10023 gids={50023, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
D/LGDMClient( 3984): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 3984): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
I/DownloadManager( 3355): in trimDatabase
I/jxcore-log( 5996): BLE advertisement is not supported: Bluetooth LE advertising is not supported
I/jxcore-log( 5996): 
W/ContextImpl( 3984): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:141 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:180 android.app.IntentService$ServiceHandler.handleMessage:65 
,E/LGDMClient( 3984): [DmNotiService.java] [onCreate()] : [148] : DmNotiService.onCreate()
D/LGDMClient( 3984): [DmNotiService.java] [onStartCommand()] : [182] : in the new onStartCommand()
D/LGDMClient( 3984): [DmNotiService.java] [handleStart()] : [203] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
V/DownloadManager( 3355): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
,V/DownloadManager( 3355): DownloadService onStartCommand
V/DownloadManager( 3355): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3355): created cursor android.database.sqlite.SQLiteCursor@3508895c on behalf of 3355
V/DownloadManager( 3355): created cursor android.database.sqlite.SQLiteCursor@7a4b465 on behalf of 3355
V/DownloadManager( 3355): processing inserted download 1
,V/DownloadManager( 3355): processing inserted download 4
V/DownloadManager( 3355): processing inserted download 7
V/DownloadManager( 3355): processing inserted download 8
V/DownloadManager( 3355): processing inserted download 9
V/DownloadManager( 3355): processing inserted download 10
V/DownloadManager( 3355): processing inserted download 16
V/DownloadManager( 3355): processing inserted download 17
V/DownloadManager( 3355): processing inserted download 18
V/DownloadManager( 3355): processing inserted download 21
V/DownloadManager( 3355): processing inserted download 22
V/DownloadManager( 3355): DownloadService onDestroy
W/GAV2    ( 6455): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,I/BooksApp( 6455): Created application version: 3.2.35 (30235)
W/ResourcesManager( 6518): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6518): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 6518): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
W/ResourcesManager( 6518): Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
,I/art     ( 2126): Explicit concurrent mark sweep GC freed 16611(934KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 30MB/62MB, paused 791us total 24.747ms
,W/DriveInitializer( 2352): Background init thread started
,D/GpsLocationProvider( 1030): updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/VoldCmdListener(  280): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  280): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.gms/files/
W/Vold    (  280): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 2352): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.gms/files
E/GpsLocationProvider( 1030): No APN found to select.
,I/LGEmail ( 6518): [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
D/DelayedSyncController( 6491): Delaying sync.
I/BooksSync( 6455): Starting books sync
D/LGEmail ( 6518): user build Type == true (at Util.java isUserModeBuildType 3507)[v:6.41.18]
,I/ActivityManager( 1030): Killing 5828:com.google.android.apps.docs/u0a61 (adj 15): empty #17
W/DriveInitializer( 2352): Awaiting to be initialized
,W/ResourceType( 6518): No package identifier when getting value for resource number 0x00000000
,I/art     ( 1030): Explicit concurrent mark sweep GC freed 70243(3MB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 44MB/66MB, paused 1.224ms total 79.580ms
,W/libprocessgroup( 1030): failed to open /acct/uid_10061/pid_5828/cgroup.procs: No such file or directory
,D/LgDataFeature( 6518): LgDataFeature() Constructor: none
D/LgDataFeature( 6518): LgDataFeature() Constructor Done, null
,E/Auth.Api.Credentials( 2352): [CredentialSyncAdapter] Unknown sync event.
I/ActivityManager( 1030): Killing 5536:com.google.android.apps.plus/u0a97 (adj 15): empty #17
W/libprocessgroup( 1030): failed to open /acct/uid_10097/pid_5536/cgroup.procs: No such file or directory
,W/DriveInitializer( 2352): Background init thread ended
,D/eas_req ( 6518): ---addEventToQueue() easCode=2, requestId=0 (at EasSupport.java addEventToQueue 69)
,I/LgeMiscReceiver( 3300): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 3300): action = android.net.conn.CONNECTIVITY_CHANGE
,I/LgeMiscReceiver( 3300): networkInfo.isConnected() = true
E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-58 f=2412 sc=60 link=72 tx=6.2, 0.0, 0.0  rx=5.5 bcn=0 [on:0 tx:0 rx:0 period:3412] from screen [on:0 period:-1553178426] gl rssi=-58 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
D/PhoneState( 3300): setPdpRejectCasuse : false
E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-58 f=2412 sc=60 link=72 tx=6.2, 0.0, 0.0  rx=5.5 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-1553178425] gl rssi=-58 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
I/HubEmail( 6518): JNI_OnLoad()
I/HubEmail( 6518): -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 6518): registerNatives()
I/HubEmail( 6518): -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 6518): registerNativeMethods()
I/HubEmail( 6518): -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
W/art     ( 6518): JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
I/ActivityManager( 1030): Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=6575 uid=10062 gids={50062, 9997, 4002, 3003, 1028} abi=armeabi-v7a
,D/BooksSync( 6455): started syncMyEbooks
D/StatusBar.NetworkController( 1472): refreshViews: Data not connected!! Set no data type icon / Roaming
W/Settings( 6518): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 6518): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/libc-netbsd(  308): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  308): res_queryN name = static-avc.lglime.com, class = 1, type = 1
,D/DrmBroadcastReceiver( 6575): Receive CONNECTIVITY_ACTION
,D/DrmBroadcastReceiver( 6575): 1  network is available. Sync DRM Time with NTP
,V/DrmService( 6575): Service onCreate
D/DrmService( 6575): Received new request = 2
I/DrmSntpClient( 6575): Start Sync process
D/DrmSntpClient( 6575): Server : 0
D/libc-netbsd(  308): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  308): res_queryN name = pool.ntp.org, class = 1, type = 1
,D/libc-netbsd(  308): res_queryN name = static-avc.lglime.com succeed
,I/ActivityManager( 1030): Start proc com.lge.sizechangable.weather for broadcast com.lge.sizechangable.weather/.layout.WeatherWidget: pid=6599 uid=10085 gids={50085, 9997, 3003, 1028, 1015} abi=armeabi-v7a
D/libc-netbsd(  308): res_queryN name = pool.ntp.org succeed
V/GLSActivity( 2126): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/libc-netbsd(  308): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  308): res_queryN name = www.google.com, class = 1, type = 1
,I/GLSUser ( 2126): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2126): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2126): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2126): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2126): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/LGDrmClient( 6575): _DRM_ServiceGet() : Bind lgdrm service
,V/ILGDrmService(  318): eDRM_SetDRMTime +++
I/LGDRM   (  318): [DRM] SET TIME : YR=2016, MON=2, DAY=2
I/LGDRM   (  318): [DRM] SET TIME : HR=19, MIN=18, SEC=55
V/FormManager( 6121): There are no updated forms. The schedule will be deleted.
V/ILGDrmService(  318): eDRM_SetDRMTime ---
I/DrmSntpClient( 6575): Synched
D/DrmService( 6575): Completed !! request = 2
D/DrmService( 6575): Request count = 0
,V/DrmService( 6575): Service onDestroy
I/ActivityManager( 1030): Killing 5893:com.lge.eula/1000 (adj 15): empty #17
V/FormManager( 6121): Alarm would be updated, because LastCheckTime has been updated.
D/libc-netbsd(  308): res_queryN name = www.google.com succeed
D/libc-netbsd(  308): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  308): res_queryN name = clients3.google.com, class = 1, type = 1
D/libc-netbsd(  308): res_queryN name = clients3.google.com succeed
,I/art     ( 6599): Almond Protected OAT
W/libprocessgroup( 1030): failed to open /acct/uid_1000/pid_5893/cgroup.procs: No such file or directory
,V/WifiInternetCheck( 1030): isHttpConnectionAvailable - We got a valid response : 204
I/ActivityManager( 1030): Killing 5331:com.google.android.gms.wearable/u0a5 (adj 15): empty #17
V/NotificationService( 1030): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,D/ZenLog  ( 1030): intercepted: 0|com.google.android.gms|1|null|10005,none
V/NotificationService( 1030): pkg=com.google.android.gms canInterrupt=false intercept=true
W/GLSActivity( 2126): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2126): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2126): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2126): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2126): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2126): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2126): 	at android.os.Binder.execTransact(Binder.java:446)
I/NotificationServiceEx( 1030): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1030): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1030): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,W/libprocessgroup( 1030): failed to open /acct/uid_10005/pid_5331/cgroup.procs: No such file or directory
D/WeatherApplication( 6599): removeAccount
,D/WeatherApplication( 6599): Account.length = 0
E/WeatherApplication( 6599): OPERATOR:OPEN
E/BooksAccountManager( 6455): Authentication error
E/BooksAccountManager( 6455): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6455): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6455): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6455): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6455): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6455): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6455): null auth token
W/ResourcesManager( 1411): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 1411): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,D/LgeQuickCoverNLService( 1411): onNotificationPosted
D/SmartCoverUpdateMonitor( 1411): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1411): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1411): handleNotificationPosted(true)
D/QuickCircle( 1411): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1411): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1411): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1411): post do add job
D/LgeQuickCoverNotificationData( 1411): add : 2
D/LgeQuickCoverNotificationData( 1411): do add job
D/LgeQuickCoverNotificationData( 1411): showAll3
D/LgeQuickCoverNotificationData( 1411): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1411): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1411): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1411): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1411): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1411): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1411): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1411): isNotificationForCurrentUser : true
W/ResourcesManager( 1472): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 1472): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
I/GLSUser ( 2126): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.syncadapters.contacts, service: cp
I/GLSUser ( 2126): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> cp without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2126): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2126): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
D/LgeQuickCoverOverlayWindow( 1411): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1411): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1411): updateNotificationData: count=3
D/WeatherAncestor( 6599): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 20:18:55
V/GLSActivity( 2126): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/libc-netbsd(  308): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  308): res_queryN name = www.googleapis.com, class = 1, type = 1
D/Weather.Utils( 6599): 2 : the weather widgets(using time tick) are gone.
D/Weather.Utils( 6599): 2 : All the weather widget is gone.
,D/UpdateThreadPoolManager( 6599): 2 : This is isUpdating : false
D/WeatherAncestor( 6599): connectivity changed - connection : true
D/WeatherService( 6599): 2 : isServiceAlived():false forecastCache:null
D/QuickStatusbarLayout( 1411): Notification difference=198
D/QuickStatusbarLayout( 1411): child = android.widget.LinearLayout{183f0fdb V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
D/ForecastDataCache( 6599): 2 : lastUpdatedTime: 1430558561343
D/ForecastDataCache( 6599): 2 : currentPackageVersion: 4.40.4
D/ForecastDataCache( 6599): 2 : Cache is not up-to-date, count: 0
,V/NotificationService( 1030): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/libc-netbsd(  308): res_queryN name = www.googleapis.com succeed
V/NotificationService( 1030): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1030): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1030): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1030): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,W/GLSActivity( 2126): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2126): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2126): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2126): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2126): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2126): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2126): 	at android.os.Binder.execTransact(Binder.java:446)
D/LgeQuickCoverNLService( 1411): onNotificationPosted
D/ContactsSyncAdapter( 2126): innerSync failed
D/ContactsSyncAdapter( 2126): com.google.wireless.gdata2.client.AuthenticationException: unable to get auth token android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
D/ContactsSyncAdapter( 2126): 	at com.google.android.syncadapters.contacts.AuthInfo.getAuthToken(AuthInfo.java:45)
D/ContactsSyncAdapter( 2126): 	at com.google.android.syncadapters.contacts.ContactsSyncAdapter.innerPerformSync(ContactsSyncAdapter.java:263)
D/ContactsSyncAdapter( 2126): 	at com.google.android.syncadapters.contacts.ContactsSyncAdapter.onPerformLoggedSync(ContactsSyncAdapter.java:168)
D/ContactsSyncAdapter( 2126): 	at com.google.android.common.LoggingThreadedSyncAdapter.onPerformSync(LoggingThreadedSyncAdapter.java:33)
D/ContactsSyncAdapter( 2126): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
D/ContactsSyncAdapter( 2126): Caused by: android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
D/ContactsSyncAdapter( 2126): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
D/ContactsSyncAdapter( 2126): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
D/ContactsSyncAdapter( 2126): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
D/ContactsSyncAdapter( 2126): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
D/ContactsSyncAdapter( 2126): 	at android.os.Binder.execTransact(Binder.java:446)
D/SmartCoverUpdateMonitor( 1411): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1411): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1411): handleNotificationPosted(true)
D/QuickCircle( 1411): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1411): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1411): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1411): post do just update job
D/LgeQuickCoverNotificationData( 1411): showAll3
D/LgeQuickCoverNotificationData( 1411): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1411): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1411): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1411): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1411): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1411): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1411): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1411): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1411): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1411): isNotificationForCurrentUser : true
,E/LgeQuickCoverOverlayWindow( 1411): updateNotificationData: count=3
D/SyncManager( 1030): failed sync operation thalitester@gmail.com u0 (com.google), com.android.contacts, LOCAL, currentRunTime 26549, reason: 10019, SyncResult: stats [ numAuthExceptions: 1]
D/Weather_cast( 6599): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherAncestor( 6599): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 20:18:55
D/SyncManager( 1030): not retrying sync operation because the error is a hard error: thalitester@gmail.com u0 (com.google), com.android.contacts, LOCAL, currentRunTime 159649, reason: 10019
,D/QuickStatusbarLayout( 1411): Notification difference=198
D/QuickStatusbarLayout( 1411): child = android.widget.LinearLayout{183f0fdb V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,I/ActivityManager( 1030): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=6622 uid=10093 gids={50093, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager( 1030): Killing 2210:com.lge.music/u0a34 (adj 15): empty #17
V/AudioFlinger(  313): 2210 died, releasing its sessions
V/AudioFlinger(  313):  pid 1866 @ 0
V/AudioFlinger(  313):  pid 3300 @ 1
V/AudioFlinger(  313):  pid 3300 @ 2
,W/libprocessgroup( 1030): failed to open /acct/uid_10034/pid_2210/cgroup.procs: No such file or directory
,E/VoldCmdListener(  280): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  280): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  280): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6622): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
E/VoldCmdListener(  280): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  280): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  280): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6622): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
E/VoldCmdListener(  280): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  280): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  280): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6622): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
E/VoldCmdListener(  280): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  280): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  280): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6622): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
,D/DelayedSyncController( 6491): Delaying sync.
,W/ApiaryClient( 6455): Error response from books API: {
W/ApiaryClient( 6455):  "error": {
W/ApiaryClient( 6455):   "errors": [
W/ApiaryClient( 6455):    {
W/ApiaryClient( 6455):     "domain": "global",
W/ApiaryClient( 6455):     "reason": "required",
W/ApiaryClient( 6455):     "message": "Login Required",
W/ApiaryClient( 6455):     "locationType": "header",
W/ApiaryClient( 6455):     "location": "Authorization"
W/ApiaryClient( 6455):    }
W/ApiaryClient( 6455):   ],
W/ApiaryClient( 6455):   "code": 401,
W/ApiaryClient( 6455):   "message": "Login Required"
W/ApiaryClient( 6455):  }
W/ApiaryClient( 6455): }
,W/ApiaryClient( 6455): errCount = 1: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6455): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-8024716860683195160&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6455): Headers:
W/ApiaryClient( 6455): accept-encoding: [gzip]
W/ApiaryClient( 6455): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6455): gdata-version: 2
,I/ActivityManager( 1030): Start proc com.google.android.apps.plus for service com.google.android.apps.plus/.service.EsSyncAdapterService: pid=6663 uid=10097 gids={50097, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,W/ResourcesManager( 6663): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/WebViewFactory( 6622): Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,I/LibraryLoader( 6622): Loading: webviewchromium
I/LibraryLoader( 6622): Time to load native libraries: 6 ms (timestamps 7140-7146)
I/LibraryLoader( 6622): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 6622): Binding Chromium to main looper Looper (main, tid 1) {34d0e58a}
,I/LibraryLoader( 6622): Expected native library version number "",actual native library version number ""
I/chromium( 6622): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 6622): Initializing chromium process, renderers=0
W/art     ( 6622): Attempt to remove local handle scope entry from IRT, ignoring
,W/chromium( 6622): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
I/chromium( 6622): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=38 off=46780 len=2953
I/chromium( 6622): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:39 off:229536 len:643667
,V/AudioPolicyService(  313): registerClient() client 0xb1427740, uid 10093
,W/AudioManagerAndroid( 6622): Requires BLUETOOTH permission
I/Adreno-EGL( 6622): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 6622): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 6622): Build Date: 12/12/14 금
I/Adreno-EGL( 6622): Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
I/Adreno-EGL( 6622): Remote Branch: 
I/Adreno-EGL( 6622): Local Patches: 
I/Adreno-EGL( 6622): Reconstruct Branch: 
,I/NSApplication( 6622): Starting up...
,I/ActivityManager( 1030): Killing 4843:com.android.vending/u0a44 (adj 15): empty #17
,W/libprocessgroup( 1030): failed to open /acct/uid_10044/pid_4843/cgroup.procs: No such file or directory
,I/GLSActivity( 2126): [ac] getting account id
,I/GLSUser ( 2126): [t] Fetched account id for thalitester@gmail.com : 105256135866144380227
,D/libc-netbsd(  308): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  308): res_queryN name = mtalk.google.com, class = 1, type = 1
,I/iu.SyncManager( 2352): SYNC; picasa accounts
,D/libc-netbsd(  308): res_queryN name = mtalk.google.com succeed
D/NetworkLogImpl( 2352): Loaded NetworkSpeedPredictor
,I/iu.Environment( 2352): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/iu.UploadsManager( 2352): num queued entries: 0
,I/iu.UploadsManager( 2352): num updated entries: 0
I/iu.SyncManager( 2352): NEXT; no task
,I/art     ( 1030): Explicit concurrent mark sweep GC freed 29111(1303KB) AllocSpace objects, 4(192KB) LOS objects, 33% free, 44MB/66MB, paused 1.315ms total 107.040ms
,D/ChimeraCfgMgr( 2352): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/ChimeraCfgMgr( 2352): Loading module com.google.android.gms.kids from APK com.google.android.gms
D/PostponalbeReceiver( 5135): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.intent.action.TIME_SET'.
,I/ActivityManager( 1030): Start proc com.lge.clock for broadcast com.lge.clock/.alarmclock.ALBootInit: pid=6723 uid=10010 gids={50010, 9997, 3003, 1028, 4002} abi=armeabi-v7a
,I/GLSUser ( 2126): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: ac2dm
,I/GLSUser ( 2126): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> ac2dm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2126): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2126): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2126): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/NotificationService( 1030): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
V/NotificationService( 1030): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1030): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1030): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1030): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,D/LgeQuickCoverNLService( 1411): onNotificationPosted
,D/SmartCoverUpdateMonitor( 1411): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1411): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1411): handleNotificationPosted(true)
D/QuickCircle( 1411): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1411): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1411): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1411): post do just update job
D/LgeQuickCoverNotificationData( 1411): showAll3
D/LgeQuickCoverNotificationData( 1411): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1411): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1411): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1411): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1411): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1411): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1411): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1411): isNotificationForCurrentUser : true
W/Kids    ( 2352): [AccountUtils] Account not ready
W/Kids    ( 2352): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/Kids    ( 2352): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/Kids    ( 2352): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/Kids    ( 2352): 	at com.google.android.gms.auth.p.c(SourceFile:550)
W/Kids    ( 2352): 	at com.google.android.gms.auth.p.b(SourceFile:477)
W/Kids    ( 2352): 	at com.google.android.gms.kids.account.k.d(SourceFile:103)
W/Kids    ( 2352): 	at com.google.android.gms.kids.account.p.a(SourceFile:70)
W/Kids    ( 2352): 	at com.google.android.gms.kids.account.t.a(SourceFile:62)
W/Kids    ( 2352): 	at com.google.android.gms.chimera.f.run(SourceFile:179)
W/Kids    ( 2352): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Kids    ( 2352): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Kids    ( 2352): 	at java.lang.Thread.run(Thread.java:818)
D/LgeQuickCoverOverlayWindow( 1411): [native noti] inex =  2
,D/LgeQuickCoverNotificationData( 1411): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1411): updateNotificationData: count=3
D/QuickStatusbarLayout( 1411): Notification difference=198
D/QuickStatusbarLayout( 1411): child = android.widget.LinearLayout{183f0fdb V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,D/GCM     ( 2126): Connected
,D/GCM     ( 2126): Message class com.google.f.a.a.p
D/ALBootInit( 6723): ====action==>android.intent.action.TIME_SET
D/ALBootInit( 6723): Alarm ALBootInit: TIME_SET
,D/Alarms  ( 6723): [setNextAlert] start
D/Alarms  ( 6723): [setNextAlert] (1)
,D/Alarms  ( 6723):  minTime  = 0
,D/Alarms  ( 6723):  -- OK multi -- 0
E/jeny.kim( 6723): [setNextAlert] setNextAlert  temp_Alarmlink + 
E/jeny.kim( 6723): [setNextAlert]setNextAlert temp_AlarmLinkText + 
I/CommonUtil( 6723): BUILD Country: EU
D/Alarms  ( 6723): broadcastToWidgetProvider : false
,D/Alarms  ( 6723): Enter formatDayAndTime(final Context context, long timeInMiliSec)
V/SettingsProvider( 1030): call_put(system:next_alarm_formatted=) for 0 calling package = com.lge.clock
,I/DigitalAppWidgetProvider( 6723): onReceive: android.intent.action.TIME_SET
V/DigitalAppWidgetProvider( 6723): cancelAlarmOnQuarterHour android.app.ReceiverRestrictedContext@2dc453d0
V/DigitalAppWidgetProvider( 6723): startAlarmOnQuarterHour android.app.ReceiverRestrictedContext@2dc453d0
,D/QuickCoverProvider( 6723): onReceiver
I/indal   ( 1411): SmartCoverWidgetContext createApplicationContext
,I/indal   ( 1411): SmartCoverWidgetContext createApplicationContext
D/WeatherAncestor( 6599): 2 : onReceive, action: android.intent.action.TIME_SET, Time(hour:min:sec) 20:18:56
,D/Weather.Utils( 6599): 2 : the weather widgets(using time tick) are gone.
D/Weather.Utils( 6599): 2 : All the weather widget is gone.
D/UpdateThreadPoolManager( 6599): 2 : This is isUpdating : false
V/GLSActivity( 2126): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/WeatherService( 6599): 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@31013fc9
,D/ForecastDataCache( 6599): 2 : lastUpdatedTime: 1430558561343
D/ForecastDataCache( 6599): 2 : currentPackageVersion: 4.40.4
D/ForecastDataCache( 6599): 2 : Cache is up-to-date, count: 0
D/Weather_cast( 6599): 2 : set auto-update time : 2/2 23:18
,D/WeatherAncestor( 6599): 2 : onReceive has processed, action: android.intent.action.TIME_SET, Time(hour:min:sec) 20:18:56
,I/GLSUser ( 2126): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 2126): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2126): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2126): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/ActivityManager( 1030): Start proc com.qualcomm.timeservice for broadcast com.qualcomm.timeservice/.TimeServiceBroadcastReceiver: pid=6749 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
I/ActivityManager( 1030): Killing 5917:com.lge.bnr/1000 (adj 15): empty #17
,W/libprocessgroup( 1030): failed to open /acct/uid_1000/pid_5917/cgroup.procs: No such file or directory
,V/GLSActivity( 2126): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1030): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1030): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1030): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1030): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1030): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
W/GLSActivity( 2126): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2126): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2126): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2126): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2126): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2126): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2126): 	at android.os.Binder.execTransact(Binder.java:446)
,D/TimeService( 6749): Receivedandroid.intent.action.TIME_SET intent. Current Time is 1454440736740
,D/LgeQuickCoverNLService( 1411): onNotificationPosted
D/        ( 6749): TimeServiceNative: User Time to be set is 1454440736740
D/QC-time-services( 6749): Lib:time_genoff_operation: pargs->base = 2
D/QC-time-services( 6749): Lib:time_genoff_operation: pargs->operation = 0
D/QC-time-services( 6749): Lib:time_genoff_operation: pargs->ts_val = 1454440736740
D/QC-time-services( 6749): Lib:time_genoff_operation: Send to server  passed!!
D/QC-time-services(  367): Daemon: Connection accepted:time_genoff
D/QC-time-services(  367): Daemon:Received base = 2, unit = 1, operation = 0,value = 1454440736740
D/QC-time-services(  367): Daemon:genoff_opr: Base = 2, val = 1454440736740, operation = 0
D/QC-time-services(  367): Daemon:rtc_get: Time read from RTC -- MM/DD/YY HH:MM:SS5/12/70 12:31:3
D/QC-time-services(  367): Daemon:Value read from RTC seconds = 14041863000
D/QC-time-services(  367): Daemon:new time 1454440736740 
D/QC-time-services(  367): Daemon: delta 1440398873740 genoff 1440398873740 
D/QC-time-services(  367): Daemon:genoff_persistent_update: Writing genoff = 1440398873740 to memory
D/QC-time-services(  367): Daemon:Opening File: /data/time/ats_2
D/QC-time-services(  367): Daemon:time_persistent_memory_opr:Genoff write operation 
D/SmartCoverUpdateMonitor( 1411): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1411): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1411): handleNotificationPosted(true)
D/QuickCircle( 1411): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1411): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1411): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1411): post do just update job
D/LgeQuickCoverNotificationData( 1411): showAll3
D/LgeQuickCoverNotificationData( 1411): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1411): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1411): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1411): showNotificationWithSetupData: display=false
E/BooksAccountManager( 6455): Authentication error
E/BooksAccountManager( 6455): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6455): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6455): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6455): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6455): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6455): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6455): null auth token
D/LgeQuickCoverOverlayWindow( 1411): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1411): isNotificationForCurrentUser : true
,D/LgeQuickCoverOverlayWindow( 1411): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1411): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1411): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1411): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1411): updateNotificationData: count=3
D/QC-time-services(  367): Updating the TOD offset
D/QC-time-services(  367): Daemon:genoff_persistent_update: Writing genoff = 1440398873740 to memory
D/QC-time-services(  367): Daemon:Opening File: /data/time/ats_1
D/QC-time-services(  367): Daemon:time_persistent_memory_opr:Genoff write operation 
E/QC-time-services(  367): Daemon:Update to modem bit set
,D/QC-time-services(  367): Daemon:genoff_send_modem: Sending data to MODEM !
D/QC-time-services(  367): Daemon: Base = 2, Value being sent to MODEM = 1124434073740
E/QC-time-services( 6749): Receive Passed == base = 2, unit = 1, operation = 0, result = 0
E/QC-time-services(  367): Daemon:tod_update_ind_cb: Got Update from modem msg_id 40
E/QC-time-services(  367): Daemon: Time-services: Waiting to acceptconnection
D/QuickStatusbarLayout( 1411): Notification difference=198
D/QuickStatusbarLayout( 1411): child = android.widget.LinearLayout{183f0fdb V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
I/ActivityManager( 1030): Start proc com.android.calendar for broadcast com.android.calendar/.widget.CalendarAppWidgetProvider: pid=6767 uid=10013 gids={50013, 9997, 3003, 1028, 1015} abi=armeabi
,I/ActivityManager( 1030): Killing 6181:com.lge.lifetracker/u0a37 (adj 15): empty #17
W/ApiaryClient( 6455): Error response from books API: {
W/ApiaryClient( 6455):  "error": {
W/ApiaryClient( 6455):   "errors": [
W/ApiaryClient( 6455):    {
W/ApiaryClient( 6455):     "domain": "global",
W/ApiaryClient( 6455):     "reason": "required",
W/ApiaryClient( 6455):     "message": "Login Required",
W/ApiaryClient( 6455):     "locationType": "header",
W/ApiaryClient( 6455):     "location": "Authorization"
W/ApiaryClient( 6455):    }
W/ApiaryClient( 6455):   ],
W/ApiaryClient( 6455):   "code": 401,
W/ApiaryClient( 6455):   "message": "Login Required"
W/ApiaryClient( 6455):  }
W/ApiaryClient( 6455): }
,W/ApiaryClient( 6455): errCount = 2: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6455): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-8024716860683195160&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6455): Headers:
W/ApiaryClient( 6455): accept-encoding: [gzip]
W/ApiaryClient( 6455): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6455): gdata-version: 2
W/libprocessgroup( 1030): failed to open /acct/uid_10037/pid_6181/cgroup.procs: No such file or directory
,W/ResourcesManager( 6767): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,D/CalendarApplication( 6767): CalendarApplication.onCreate()
,D/PreferenceKeysParser( 6767): [debug_displayParseInfos] preference keys.size() = 44
D/PreferenceKeysParser( 6767): [debug_displayParseInfos] preference keys = {lg_preferences_tardis_1=com.android.calendar.adaptation.PreferenceKey$KeyData@3bd7d2f7, lg_preferences_hide_declined=com.android.calendar.adaptation.PreferenceKey$KeyData@1f364564, lg_preferences_default_reminder=com.android.calendar.adaptation.PreferenceKey$KeyData@229833cd, lg_preferences_month_view_style=com.android.calendar.adaptation.PreferenceKey$KeyData@3824b482, lg_preferences_alerts_ringtone=com.android.calendar.adaptation.PreferenceKey$KeyData@352ca793, lg_preferences_device_tz=com.android.calendar.adaptation.PreferenceKey$KeyData@2dc453d0, lg_preferences_debug_datesearch=com.android.calendar.adaptation.PreferenceKey$KeyData@31013fc9, lg_preferences_debug_country=com.android.calendar.adaptation.PreferenceKey$KeyData@1d6d96ce, lg_preferences_display_weather_information=com.android.calendar.adaptation.PreferenceKey$KeyData@1cf029ef, lg_preferences_alerts_vibrateWhen=com.android.calendar.adaptation.PreferenceKey$KeyData@1ce2dcfc, lg_preferences_debug_rtl=com.android.calendar.adaptation.PreferenceKey$KeyData@12d50f85, lg_preferences_alerts_type=com.android.calendar.adaptation.PreferenceKey$KeyData@355051da, lg_preferrences_country_code=com.android.calendar.adaptation.PreferenceKey$KeyData@14bf760b, lg_preferences_weather_info=com.android.calendar.adaptation.PreferenceKey$KeyData@2fecce8, lg_preference_holiday_calendar_ver=com.android.calendar.adaptation.PreferenceKey$KeyData@c5c1f01, lg_preferences_show_controls=com.android.calendar.adaptation.PreferenceKey$KeyData@1071b1a6, lg_preferences_user_select_noti_sound=com.android.calendar.adaptation.PreferenceKey$KeyData@30ed67e7, lg_preference_default_myphonebook=com.android.calendar.adaptation.PreferenceKey$KeyData@2e67cf94, lg_preferences_skip_setup=com.android.calendar.adaptation.PreferenceKey$KeyData@3eaaa3d, lg_preferred_startView=com.android.calendar.adaptation.PreferenceKey$KeyData@12f74232, lg_preferences_debug_operator=com.android.calendar.adaptation.PreferenceKey$KeyData@e1e9b83, lg_preferences_exclude_sticker_list=com.android.calendar.adaptation.PreferenceKey$KeyData@20bc5100, lg_preferences_writable_calendars_count=com.android.calendar.adaptation.PreferenceKey$KeyData@36dcad39, lg_preferred_detailedView=com.android.calendar.adaptation.PreferenceKey$KeyData@bd34f7e, lg_preferences_debug_floating=com.android.calendar.adaptation.PreferenceKey$KeyData@24a56cdf, lg_preferences_home_tz=com.android.calendar.adaptation.PreferenceKey$KeyData@15157d2c, lg_preferences_home_tz_enabled=com.android.calendar.adaptation.PreferenceKey$KeyData@251e3f5, lg_preference_received_provider_reminder_broadcast=com.android.calendar.adaptation.PreferenceKey$KeyData@34d0e58a, lg_preferences_default_cell_height=com.android.calendar.adaptation.PreferenceKey$KeyData@359df7fb, lg_preferences_notification_type=com.android.calendar.adaptation.PreferenceKey$KeyData@3cf34018, lg_preferences_show_week_num=com.android.calendar.adaptation.PreferenceKey$KeyData@3ba9ca71, lg_preferences_dont_show_again_no_online_account=com.android.calendar.adaptation.PreferenceKey$KeyData@275fd056, lg_preferences_alerts_popup=com.android.calendar.adaptation.PreferenceKey$KeyData@2dca18d7, lg_preferences_week_start_day=com.android.calendar.adaptation.PreferenceKey$KeyData@1fe845c4, lg_preferences_app_version=com.android.calendar.adaptation.PreferenceKey$KeyData@14bf9cad, lg_preferences_alerts=com.android.calendar.adaptation.PreferenceKey$KeyData@12209be2, lg_preferences_select_aux_calendar=com.android.calendar.adaptation.PreferenceKey$KeyData@1a2d6b73, lg_preferences_widget_info_calendars=com.android.calendar.adaptation.PreferenceKey$KeyData@a05fa30, lg_preferences_alerts_default_ringtone=com.android.calendar.adaptation.PreferenceKey$KeyData@7e656a9, lg_preference_defaultCalendar=com.android.calendar.adaptation.PreferenceKey$KeyData@3b30942e, lg_preferences_alerts_vibratetype=com.android.calendar.adaptation.PreferenceKey$KeyData@a694bcf, lg_preferences_recent_timezones=com.android.calendar.adaptation.PreferenceKey$KeyData@3508895
,D/GeneralPreferenceUtils( 6767): [migratePrefrenceKeys] Exit: Version(44001600) >= 42001300
D/Config  ( 6767): [init]
,I/Config  ( 6767): LGCalendar ver.4.40.16
I/Config  ( 6767): start check model
I/Config  ( 6767): start check native_ca
I/Config  ( 6767): Config Operator=OPEN, Country=EU
D/Config  ( 6767): [setDefaultValuesToPref]
D/Config  ( 6767): [parseProfiles]
D/ProfilesParser( 6767): [debug_displayParseInfos] profile.country = null
D/ProfilesParser( 6767): [debug_displayParseInfos] profile.operator = null
D/Config  ( 6767): [updateProfiletoCountryInfo]
D/GeneralPreference( 6767): [checkAndMigrateOldPreference]
E/AgendaWidgetManager( 6767): [updateWidgets] 
I/InitNotificationRingtoneService( 6767): Start InitializeAlertRingtoneService.onHandleIntent
I/AlertUtils( 6767): [setFormatNotificationSound] current noti URI = content://media/internal/audio/media/41
D/MonthWidgetProvider( 6767): [onReceive]
D/CalendarWidgetProvider( 6767): [onReceive]
D/CalendarWidgetProvider( 6767): [CalendarWidgetProvider] got the intent: Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.android.calendar/.widget.MonthWidgetProvider }
W/HolidayIntentService( 6767): onHandleIntent
D/CalendarTypeController( 6767): [onUpdateAndInitCalendarTime]
D/HolidayDataLoader( 6767): readJsonAsset : holiday.json
D/WeekWidgetProvider( 6767): [onReceive]
D/CalendarWidgetProvider( 6767): [onReceive]
D/CalendarWidgetProvider( 6767): [CalendarWidgetProvider] got the intent: Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.android.calendar/.widget.WeekWidgetProvider }
D/CalendarTypeController( 6767): [onUpdateAndInitCalendarTime]
I/AlertUtils( 6767): [getCalendarNotiSoundURIFromCursor] getCount()= 21
I/AlertUtils( 6767): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Arpeggio.ogg
I/AlertUtils( 6767): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Country_Blues.ogg
I/AlertUtils( 6767): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Crystal.ogg
I/AlertUtils( 6767): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Dewdrop.ogg
I/AlertUtils( 6767): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Ding_Dong.ogg
I/AlertUtils( 6767): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Echo.ogg
I/AlertUtils( 6767): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Email.ogg
I/AlertUtils( 6767): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Game_Over.ogg
I/AlertUtils( 6767): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Gayageum.ogg
I/AlertUtils( 6767): [getMediaFilepathFromContentUri] filepath = /system/media/audio/alarms/Afternoon_Walk.ogg
I/AlertUtils( 6767): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Harmonics.ogg
I/AlertUtils( 6767): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Idea.ogg
I/AlertUtils( 6767): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/News.ogg
I/AlertUtils( 6767): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Pebble.ogg
I/AlertUtils( 6767): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Schedule.ogg
I/AlertUtils( 6767): [getCalendarNotiSoundURIFromCursor] filePath = /system/media/audio/notifications/Schedule.ogg, new URI = content://media/internal/audio/media/41
I/AlertUtils( 6767): set default noti to content://media/internal/audio/media/41
I/InitNotificationRingtoneService( 6767): End InitializeAlertRingtoneService.onHandleIntent
V/QRemote ( 6242): [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.wait_loading
D/QRemote ( 6242): [RemoteAppWidgetProvider.java:211:onReceive()] oooooo 140514:alarm msg received!:9193
E/HolidayIntentService( 6767): onHandleIntent:holiday data empty
I/ActivityManager( 1030): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.realtimechat.RequestWriter$NetworkStateReceiver: pid=6803 uid=10072 gids={50072, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
I/ActivityManager( 1030): Killing 6222:com.lge.settings.easy/1000 (adj 15): empty #17
I/art     (  337): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 394us total 19.105ms
I/art     (  337): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 287us total 16.064ms
I/art     (  337): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 287us total 14.765ms
W/libprocessgroup( 1030): failed to open /acct/uid_1000/pid_6222/cgroup.procs: No such file or directory
W/ResourcesManager( 6803): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
D/LgDataFeature( 6803): LgDataFeature() Constructor: none
D/LgDataFeature( 6803): LgDataFeature() Constructor Done, null
I/Babel   ( 6803): MmsConfig: mnc/mcc: 0/0
I/Babel   ( 6803): MmsConfig.loadMmsSettings
I/Babel   ( 6803): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D855 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D855-M3-D1.xml
I/Babel   ( 6803): MmsConfig.loadFromDatabase
E/Babel   ( 6803): canonicalizeMccMnc: invalid mccmnc 
I/Babel   ( 6803): MmsConfig.loadFromResources
E/Babel   ( 6803): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel   ( 6803): MmsConfig.loadMmsSettings: mUserAgent=LG-D855 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D855-M3-D1.xml
W/Settings( 6803): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/AudioCapabilities( 6803): Unsupported mime audio/evrc
W/AudioCapabilities( 6803): Unsupported mime audio/qcelp
W/VideoCapabilities( 6803): Unrecognized profile 2130706433 for video/avc
W/AudioCapabilities( 6803): Unsupported mime audio/amr-wb-plus
W/AudioCapabilities( 6803): Unsupported mime audio/qcelp
W/AudioCapabilities( 6803): Unsupported mime audio/evrc
W/VideoCapabilities( 6803): Unsupported mime video/x-ms-wmv
W/VideoCapabilities( 6803): Unsupported mime video/divx
W/VideoCapabilities( 6803): Unsupported mime video/divx311
W/VideoCapabilities( 6803): Unsupported mime video/divx4
I/DigitalAppWidgetProvider( 6723): onReceive: android.intent.action.ALARM_CHANGED
D/WeatherAncestor( 6599): 2 : onReceive, action: com.lge.sizechangable.weather.action.setweathercast, Time(hour:min:sec) 20:18:57
D/Weather.Utils( 6599): 2 : the weather widgets(using time tick) are gone.
D/Weather.Utils( 6599): 2 : All the weather widget is gone.
D/UpdateThreadPoolManager( 6599): 2 : This is isUpdating : false
D/Weather_cast( 6599): 2 : Update is Canceled by com.lge.sizechangable.weather.action.alarm
D/WeatherAncestor( 6599): 2 : onReceive has processed, action: com.lge.sizechangable.weather.action.setweathercast, Time(hour:min:sec) 20:18:57
W/VideoCapabilities( 6803): Unsupported mime video/mp4v-esdp
I/VideoCapabilities( 6803): Unsupported profile 4 for video/mp4v-es
V/GLSActivity( 2126): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/ResourcesManager( 6803): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6803): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
W/AudioCapabilities( 6803): Unsupported mime audio/eac3
W/AudioCapabilities( 6803): Unsupported mime audio/ac3
W/AudioCapabilities( 6803): Unsupported mime audio/g726
W/AudioCapabilities( 6803): Unsupported mime audio/wma-voice
W/AudioCapabilities( 6803): Unsupported mime audio/x-ms-wma
W/AudioCapabilities( 6803): Unsupported mime audio/adpcm
W/VideoCapabilities( 6803): Unsupported mime video/theora
W/VideoCapabilities( 6803): Unsupported mime video/mjpg
I/GLSUser ( 2126): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2126): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2126): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2126): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2126): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/JNIHelp ( 6803): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-54 f=2412 sc=60 link=72 tx=5.1, 0.0, 0.0  rx=3.8 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1553175397] gl rssi=-54 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-54 f=2412 sc=60 link=72 tx=5.1, 0.0, 0.0  rx=3.8 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1553175394] gl rssi=-54 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
I/art     ( 2126): Explicit concurrent mark sweep GC freed 19700(1132KB) AllocSpace objects, 13(1616KB) LOS objects, 51% free, 30MB/62MB, paused 811us total 54.871ms
D/StatusBar.NetworkController( 1472): refreshViews: Data not connected!! Set no data type icon / Roaming
,W/System  ( 6803): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/system/framework/com.google.android.media.effects.jar", zip file "/system/app/Hangouts/Hangouts.apk"],nativeLibraryDirectories=[/system/app/Hangouts/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6803): Installed default security provider GmsCore_OpenSSL
V/NotificationService( 1030): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1030): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1030): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1030): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1030): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
W/GLSActivity( 2126): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2126): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2126): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2126): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2126): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2126): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2126): 	at android.os.Binder.execTransact(Binder.java:446)
E/BooksAccountManager( 6455): Authentication error
E/BooksAccountManager( 6455): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6455): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6455): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6455): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6455): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6455): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6455): null auth token
D/LgeQuickCoverNLService( 1411): onNotificationPosted
D/SmartCoverUpdateMonitor( 1411): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1411): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1411): handleNotificationPosted(true)
D/QuickCircle( 1411): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1411): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1411): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1411): post do just update job
D/LgeQuickCoverNotificationData( 1411): showAll3
D/LgeQuickCoverNotificationData( 1411): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1411): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1411): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1411): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1411): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1411): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1411): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1411): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1411): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1411): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1411): updateNotificationData: count=3
,D/QuickStatusbarLayout( 1411): Notification difference=198
,D/QuickStatusbarLayout( 1411): child = android.widget.LinearLayout{183f0fdb V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
I/GLSUser ( 2126): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.talk, service: oauth2:https://www.googleapis.com/auth/chat https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/hangouts https://www.googleapis.com/auth/identity.plus.page.impersonation https://www.googleapis.com/auth/chat.native
I/GLSUser ( 2126): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/chat https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/hangouts https://www.googleapis.com/auth/identity.plus.page.impersonation https://www.googleapis.com/auth/chat.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2126): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2126): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2126): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/ApiaryClient( 6455): Error response from books API: {
W/ApiaryClient( 6455):  "error": {
W/ApiaryClient( 6455):   "errors": [
W/ApiaryClient( 6455):    {
W/ApiaryClient( 6455):     "domain": "global",
W/ApiaryClient( 6455):     "reason": "required",
W/ApiaryClient( 6455):     "message": "Login Required",
W/ApiaryClient( 6455):     "locationType": "header",
W/ApiaryClient( 6455):     "location": "Authorization"
W/ApiaryClient( 6455):    }
W/ApiaryClient( 6455):   ],
W/ApiaryClient( 6455):   "code": 401,
W/ApiaryClient( 6455):   "message": "Login Required"
W/ApiaryClient( 6455):  }
W/ApiaryClient( 6455): }
W/ApiaryClient( 6455): errCount = 3: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6455): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-8024716860683195160&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6455): Headers:
W/ApiaryClient( 6455): accept-encoding: [gzip]
W/ApiaryClient( 6455): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6455): gdata-version: 2
E/Babel   ( 6803): UserRecoverableAuthException.
E/Babel   ( 6803): cfq: BadAuthentication
E/Babel   ( 6803): 	at cfn.a(Unknown Source)
E/Babel   ( 6803): 	at f.a(PG:191)
E/Babel   ( 6803): 	at ava.a(PG:88)
E/Babel   ( 6803): 	at ava.a(PG:128)
E/Babel   ( 6803): 	at bjs.a(PG:255)
E/Babel   ( 6803): 	at bep.a(PG:602)
E/Babel   ( 6803): 	at bep.a(PG:469)
E/Babel   ( 6803): 	at bpo.run(PG:1141)
E/Babel   ( 6803): Error getting auth token
E/Babel   ( 6803): bxl
E/Babel   ( 6803): 	at f.a(PG:201)
E/Babel   ( 6803): 	at ava.a(PG:88)
E/Babel   ( 6803): 	at ava.a(PG:128)
E/Babel   ( 6803): 	at bjs.a(PG:255)
E/Babel   ( 6803): 	at bep.a(PG:602)
E/Babel   ( 6803): 	at bep.a(PG:469)
E/Babel   ( 6803): 	at bpo.run(PG:1141)
I/Babel_RequestWriter( 6803): error sending REQ[fc:8; creat:1454435294626; type:bev-561779241]; took 89 ms (error code == 100)
,E/Babel   ( 6803): Account registration failedRedacted-21
E/Babel   ( 6803): bph: null -- null
E/Babel   ( 6803): 	at ava.a(PG:120)
E/Babel   ( 6803): 	at ava.a(PG:128)
E/Babel   ( 6803): 	at bjs.a(PG:255)
E/Babel   ( 6803): 	at bep.a(PG:602)
E/Babel   ( 6803): 	at bep.a(PG:469)
E/Babel   ( 6803): 	at bpo.run(PG:1141)
I/Babel   ( 6803): Account setup failed with error state:106 account:Redacted-21
I/Babel   ( 6803): Account sign in complete with state 106account: Redacted-21
I/art     ( 6803): Note: end time exceeds epoch: 
,I/GLSUser ( 2126): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.talk, service: oauth2:https://www.googleapis.com/auth/chat https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/hangouts https://www.googleapis.com/auth/identity.plus.page.impersonation https://www.googleapis.com/auth/chat.native
,I/GLSUser ( 2126): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/chat https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/hangouts https://www.googleapis.com/auth/identity.plus.page.impersonation https://www.googleapis.com/auth/chat.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2126): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2126): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2126): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/ResourcesManager( 2126): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,V/NotificationService( 1030): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
V/NotificationService( 1030): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1030): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1030): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1030): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,E/Babel   ( 6803): Unexpected exception while authenticating.
E/Babel   ( 6803): cfr: User intervention required. Notification has been pushed.
E/Babel   ( 6803): 	at cfn.b(Unknown Source)
E/Babel   ( 6803): 	at cfn.a(Unknown Source)
E/Babel   ( 6803): 	at f.a(PG:188)
E/Babel   ( 6803): 	at ava.b(PG:143)
E/Babel   ( 6803): 	at bnr.run(PG:5415)
E/Babel   ( 6803): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/Babel   ( 6803): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/Babel   ( 6803): 	at java.lang.Thread.run(Thread.java:818)
D/LgeQuickCoverNLService( 1411): onNotificationPosted
D/SmartCoverUpdateMonitor( 1411): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1411): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1411): handleNotificationPosted(true)
D/QuickCircle( 1411): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1411): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1411): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1411): post do just update job
D/LgeQuickCoverNotificationData( 1411): showAll3
D/LgeQuickCoverNotificationData( 1411): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1411): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1411): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1411): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1411): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1411): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1411): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1411): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1411): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1411): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1411): updateNotificationData: count=3
D/QuickStatusbarLayout( 1411): Notification difference=198
D/QuickStatusbarLayout( 1411): child = android.widget.LinearLayout{183f0fdb V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,E/BooksSync( 6455): Soft error: 
E/BooksSync( 6455): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 6455): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-8024716860683195160&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 6455): Headers:
E/BooksSync( 6455): accept-encoding: [gzip]
E/BooksSync( 6455): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 6455): gdata-version: 2
E/BooksSync( 6455): 
E/BooksSync( 6455): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 6455): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 6455): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 6455): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 6455): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 6455): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 6455): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 6455): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 6455): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 6455): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 6455): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 6455): {
E/BooksSync( 6455):  "error": {
E/BooksSync( 6455):   "errors": [
E/BooksSync( 6455):    {
E/BooksSync( 6455):     "domain": "global",
E/BooksSync( 6455):     "reason": "required",
E/BooksSync( 6455):     "message": "Login Required",
E/BooksSync( 6455):     "locationType": "header",
E/BooksSync( 6455):     "location": "Authorization"
E/BooksSync( 6455):    }
E/BooksSync( 6455):   ],
E/BooksSync( 6455):   "code": 401,
E/BooksSync( 6455):   "message": "Login Required"
E/BooksSync( 6455):  }
E/BooksSync( 6455): }
E/BooksSync( 6455): 
E/BooksSync( 6455): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 6455): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 6455): 	... 8 more
,E/BooksSync( 6455): Sync error
E/BooksSync( 6455): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 6455): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-8024716860683195160&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 6455): Headers:
E/BooksSync( 6455): accept-encoding: [gzip]
E/BooksSync( 6455): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 6455): gdata-version: 2
E/BooksSync( 6455): 
E/BooksSync( 6455): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 6455): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 6455): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 6455): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 6455): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 6455): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 6455): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 6455): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 6455): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 6455): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 6455): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 6455): {
E/BooksSync( 6455):  "error": {
E/BooksSync( 6455):   "errors": [
E/BooksSync( 6455):    {
E/BooksSync( 6455):     "domain": "global",
E/BooksSync( 6455):     "reason": "required",
E/BooksSync( 6455):     "message": "Login Required",
E/BooksSync( 6455):     "locationType": "header",
E/BooksSync( 6455):     "location": "Authorization"
E/BooksSync( 6455):    }
E/BooksSync( 6455):   ],
E/BooksSync( 6455):   "code": 401,
E/BooksSync( 6455):   "message": "Login Required"
E/BooksSync( 6455):  }
E/BooksSync( 6455): }
E/BooksSync( 6455): 
E/BooksSync( 6455): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 6455): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 6455): 	... 8 more
I/BooksSync( 6455): Finished books sync
I/ActivityManager( 1030): Killing 6146:com.lge.sync/1000 (adj 15): empty #17
,D/SyncManager( 1030): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 26519, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,W/libprocessgroup( 1030): failed to open /acct/uid_1000/pid_6146/cgroup.procs: No such file or directory
,V/GLSActivity( 2126): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2126): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.syncadapters.contacts, service: cp
I/GLSUser ( 2126): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> cp without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2126): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2126): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2126): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1030): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1030): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1030): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1030): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1030): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1411): onNotificationPosted
D/SmartCoverUpdateMonitor( 1411): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1411): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1411): handleNotificationPosted(true)
D/QuickCircle( 1411): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1411): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1411): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1411): post do just update job
D/LgeQuickCoverNotificationData( 1411): showAll3
D/LgeQuickCoverNotificationData( 1411): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1411): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1411): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1411): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1411): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1411): isNotificationForCurrentUser : true
,D/LgeQuickCoverOverlayWindow( 1411): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1411): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1411): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1411): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1411): updateNotificationData: count=3
W/GLSActivity( 2126): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2126): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2126): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2126): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2126): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2126): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2126): 	at android.os.Binder.execTransact(Binder.java:446)
,D/QuickStatusbarLayout( 1411): Notification difference=198
D/QuickStatusbarLayout( 1411): child = android.widget.LinearLayout{183f0fdb V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,D/ContactsSyncAdapter( 2126): innerSync failed
D/ContactsSyncAdapter( 2126): com.google.wireless.gdata2.client.AuthenticationException: unable to get auth token android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
D/ContactsSyncAdapter( 2126): 	at com.google.android.syncadapters.contacts.AuthInfo.getAuthToken(AuthInfo.java:45)
D/ContactsSyncAdapter( 2126): 	at com.google.android.syncadapters.contacts.ContactsSyncAdapter.innerPerformSync(ContactsSyncAdapter.java:263)
D/ContactsSyncAdapter( 2126): 	at com.google.android.syncadapters.contacts.ContactsSyncAdapter.onPerformLoggedSync(ContactsSyncAdapter.java:168)
D/ContactsSyncAdapter( 2126): 	at com.google.android.common.LoggingThreadedSyncAdapter.onPerformSync(LoggingThreadedSyncAdapter.java:33)
D/ContactsSyncAdapter( 2126): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
D/ContactsSyncAdapter( 2126): Caused by: android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
D/ContactsSyncAdapter( 2126): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
D/ContactsSyncAdapter( 2126): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
D/ContactsSyncAdapter( 2126): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
D/ContactsSyncAdapter( 2126): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
D/ContactsSyncAdapter( 2126): 	at android.os.Binder.execTransact(Binder.java:446)
,D/SyncManager( 1030): failed sync operation thalitester@gmail.com u0 (com.google), com.android.contacts, LOCAL, currentRunTime 159649, reason: 10019, SyncResult: stats [ numAuthExceptions: 1]
,I/art     ( 1030): Explicit concurrent mark sweep GC freed 21811(1039KB) AllocSpace objects, 7(752KB) LOS objects, 33% free, 44MB/66MB, paused 2.336ms total 139.101ms
,I/GAV2    ( 6455): Thread[GAThread,5,main]: No campaign data found.
,I/ActivityManager( 1030): Start proc com.android.vending for service com.android.vending/com.google.android.finsky.services.ContentSyncService: pid=6880 uid=10044 gids={50044, 9997, 3003, 1028, 1015} abi=armeabi-v7a
V/AlarmManager( 1030): RTC_WAKEUP set : Alarm{3c8ae2c5 type 0 when 1454440739881 com.android.vending} when 1454440739881
,D/Finsky  ( 6880): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,D/LgDataFeature( 6880): LgDataFeature() Constructor: none
,D/LgDataFeature( 6880): LgDataFeature() Constructor Done, null
,D/Finsky  ( 6880): [1] DailyHygiene.goMakeHygieneIfDirty: Dirty, need more hygiene.
,I/GAV4    ( 6622): Thread[GAThread,5,main]: No campaign data found.
,I/[SystemUI]TimeTickManager( 1472): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1472): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1472): called onTimeUpdated()
I/[SystemUI]Clock( 1472): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1472): called onTimeUpdated()
I/[SystemUI]DateView( 1472): called onTimeUpdated()
I/[SystemUI]DateView( 1472): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1472): handleTimeUpdate
I/ActivityManager( 1030): Start proc com.google.android.gms:car for service com.google.android.gms/.car.CarService: pid=6923 uid=10005 gids={50005, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
,W/Settings( 6880): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 6880): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,V/DownloadManager( 3355): starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 3355): created cursor android.database.sqlite.SQLiteCursor@3cd8d5eb on behalf of 6880
W/ResourcesManager( 6923): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 6923): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
D/Finsky  ( 6880): [1] 2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 6880): [1] 2.run: Finished loading 1 libraries.
D/Finsky  ( 6880): [1] GmsCoreHelper.cleanupNlp: result=false type=4
D/Finsky  ( 6880): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,I/MultiDex( 6923): VM with version 2.1.0 has multidex support
I/MultiDex( 6923): install
I/MultiDex( 6923): VM has multidex support, MultiDex support library is disabled.
,V/JNIHelp ( 6923): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,V/SIM_STK ( 1030): Menu title from STK is T-Mobile
,W/ActivityThread( 6923): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 6923): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@13af018c: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6923): Installed default security provider GmsCore_OpenSSL
D/GCM     ( 2126): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,D/AuthorizationBluetoothService( 2126): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
V/GmsCoreStatsServiceLauncher( 2352): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
I/ActivityManager( 1030): Start proc com.google.android.gms.wearable for service com.google.android.gms/.wearable.service.WearableService: pid=6954 uid=10005 gids={50005, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
,D/LocationInitializer( 2352): Restart initialization of location
,I/ActivityManager( 1030): Killing 6091:com.android.settings/1000 (adj 15): empty #17
,W/ResourcesManager( 6954): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6954): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
D/WifiService( 1030): Client connection lost with reason: 4
,I/MultiDex( 6954): VM with version 2.1.0 has multidex support
I/MultiDex( 6954): install
I/MultiDex( 6954): VM has multidex support, MultiDex support library is disabled.
,E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=20.1, 0.0, 0.0  rx=17.4 bcn=0 [on:0 tx:0 rx:0 period:3005] from screen [on:0 period:-1553172376] gl rssi=-63 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=20.1, 0.0, 0.0  rx=17.4 bcn=0 [on:0 tx:0 rx:0 period:0] from screen [on:0 period:-1553172376] gl rssi=-63 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
W/libprocessgroup( 1030): failed to open /acct/uid_1000/pid_6091/cgroup.procs: No such file or directory
,V/JNIHelp ( 6954): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,W/ActivityThread( 6954): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 6954): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@13af018c: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6954): Installed default security provider GmsCore_OpenSSL
,D/WearableService( 6954): callingUid 10005, callindPid: 6954
V/GLSActivity( 2126): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/GCM     ( 2126): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,D/AuthorizationBluetoothService( 2126): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
V/GmsCoreStatsServiceLauncher( 2352): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,E/MDM     ( 1831): [86] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,E/MDM     ( 1831): [86] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
I/GLSUser ( 2126): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 2126): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2126): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2126): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2126): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     ( 2352): Explicit concurrent mark sweep GC freed 17140(1236KB) AllocSpace objects, 18(288KB) LOS objects, 49% free, 32MB/64MB, paused 1.380ms total 45.950ms
D/LocationInitializer( 2352): Restart initialization of location
D/Finsky  ( 6880): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,V/Finsky  ( 6880): [1] GearheadStateMonitor.onReady: sIsProjecting:false
,D/Finsky  ( 6880): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 6880): [1] 5.onFinished: Scheduling replication attempt 2.
I/ActivityManager( 1030): Killing 6121:com.lge.formmanager/u0a26 (adj 15): empty #17
,I/ActivityManager( 1030): Killing 6435:com.lge.appbox.client/u0a11 (adj 15): empty #18
,W/libprocessgroup( 1030): failed to open /acct/uid_10026/pid_6121/cgroup.procs: No such file or directory
,W/libprocessgroup( 1030): failed to open /acct/uid_10011/pid_6435/cgroup.procs: No such file or directory
D/PowerManagerServiceEx( 1030): acquireWakeLockInternal: lock=770300739, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1030
,V/AlarmManager( 1030): RTC_WAKEUP set : Alarm{317744a3 type 0 when 1454440741403 com.android.vending} when 1454440741403
D/Finsky  ( 6880): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
D/[Concierge]Service( 2607): onStartCommand(). Type : 9
,V/GLSActivity( 2126): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/PowerManagerServiceEx( 1030): releaseWakeLockInternal: lock=770300739 [*alarm*], flags=0x0
,I/GLSUser ( 2126): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 2126): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 2126): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2126): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2126): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/Finsky  ( 6880): [1] 1.onErrorResponse: Unable to preload experiments: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,V/GLSActivity( 2126): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2126): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 2126): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2126): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2126): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2126): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/GLSActivity( 2126): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2126): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 2126): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 2126): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2126): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2126): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/Finsky  ( 6880): [1] LibraryUpdateListener.onErrorResponse: Library replication failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,V/SIM_STK ( 1030): Menu title from STK is T-Mobile
,V/GLSActivity( 2126): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2126): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 2126): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 2126): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 2126): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2126): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/Finsky  ( 6880): [1] 2.onErrorResponse: Update check failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,D/Finsky  ( 6880): [1] DailyHygiene.logDeviceFeaturesAndContinue: Logging device features
,D/Finsky  ( 6880): [1] DailyHygiene.flushEventLogsAndContinue: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 6880): [1] DailyHygiene.reschedule: Scheduling new run in 32 minutes (failures=2)
,D/DeviceConnectionService( 1831): client connected with version: 7571000
,I/ActivityManager( 1030): Killing 6575:com.lge.drmservice/u0a62 (adj 15): empty #17
,W/libprocessgroup( 1030): failed to open /acct/uid_10062/pid_6575/cgroup.procs: No such file or directory
,E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=12.5, 0.0, 0.0  rx=10.7 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:-1553169358] gl rssi=-63 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=12.5, 0.0, 0.0  rx=10.7 bcn=0 [on:0 tx:0 rx:0 period:9] from screen [on:0 period:-1553169349] gl rssi=-63 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
D/sensors_hal_Time( 1030): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1030): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1030): tsOffsetIs: Apps: 137290592607; DSPS: 4640260; Offset : -4334089772
,I/ActivityManager( 1030): Killing 6622:com.google.android.apps.magazines/u0a93 (adj 15): empty #17
,W/libprocessgroup( 1030): failed to open /acct/uid_10093/pid_6622/cgroup.procs: No such file or directory
,E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=7.3, 0.0, 0.0  rx=5.8 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1553166326] gl rssi=-63 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=7.3, 0.0, 0.0  rx=5.8 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1553166323] gl rssi=-63 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=4.1, 0.0, 0.0  rx=3.4 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1553163299] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=4.1, 0.0, 0.0  rx=3.4 bcn=0 [on:0 tx:0 rx:0 period:9] from screen [on:0 period:-1553163290] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=2.1, 0.0, 0.0  rx=1.7 bcn=0 [on:0 tx:0 rx:0 period:3000] from screen [on:0 period:-1553160271] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=2.1, 0.0, 0.0  rx=1.7 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1553160268] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
,I/[SystemUI]QPairHandler( 1472): onReceive = android.intent.action.PACKAGE_CHANGED
,I/[LGHome]EVENT( 2082): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.talk flg=0x4000010 (has extras) }
,D/administrator( 1030): Handling package changes for user 0
D/SplitUIService( 1883): replaced split : contains_com.google.android.talk / true
,I/InputReader( 1030): Reconfiguring input devices.  changes=0x00000010
,I/ActivityManager( 1030): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.manager.PreloadListManagerHelper: pid=6998 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,I/[SystemUI]QSlideListController( 1472): onReceive = android.intent.action.PACKAGE_CHANGED
I/[SystemUI]AppWidgetPanel(QRemoteWidgetPanel)( 1472): onReceive = android.intent.action.PACKAGE_CHANGED, packageName : com.google.android.talk
D/SplitUIManager( 1883): split_name #11 / not available #0
I/SplitUIService( 1883): split app #11
,W/ResourcesManager( 2082): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
I/[LGHome]Launcher( 2082): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,I/AppUp4:AppBoxCP( 6998): onCreate
W/AppUp4:DB( 6998):  [AppBoxDatabaseHelper] construct
,I/AppUp4:DB( 6998):  setFingerPrint start
I/AppUp4:DB( 6998):  newfinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys SDK version = 21
I/AppUp4:DB( 6998):  beforefinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys
I/AppUp4:DB( 6998):  SDK version = 21
I/AppUp4:DB( 6998):  beforefinger == newfinger no write in DB
,D/AppUp4:AppBoxApplication( 6998): AppBoxApplication onCreate()
I/AppUp4:CustModeStarterReceiver( 6998): onReceive
,I/NotificationService( 1030): action=android.intent.action.PACKAGE_CHANGED queryReplace=false
D/BackupManagerService( 1030): Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.talk flg=0x4000010 (has extras) }
,W/ResourcesManager( 1030): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
D/LgDataFeature( 6998): LgDataFeature() Constructor: none
D/LgDataFeature( 6998): LgDataFeature() Constructor Done, null
,D/AppUp4:CustFacade( 6998): Context : android.app.ReceiverRestrictedContext@1f364564
D/AppUp4:CustFacade( 6998): isCustomizationCompleted : false
D/AppUp4:CustFacade( 6998): isPhone : true
D/AppUp4:CustModeStarterReceiver( 6998): begin check event
I/AppUp4:CustModeStarterReceiver( 6998): Event For Nothing, skip.
W/ResourcesManager( 1030): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/ActivityManager( 1030): Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=7033 uid=10019 gids={50019, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
,I/ActivityManager( 1030): Killing 6472:com.android.gallery3d/u0a27 (adj 15): empty #17
W/ResourceType( 1030): Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
W/libprocessgroup( 1030): failed to open /acct/uid_10027/pid_6472/cgroup.procs: No such file or directory
,I/[LGHome]EVENT( 2082): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
,W/ResourcesManager( 7033): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 7033): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 7033): Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
W/ResourcesManager( 7033): Asset path '/system/framework/lghiddenlibs.jar' does not exist or contains no resources.
W/ResourcesManager( 7033): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
,I/SystemConfig( 7033): BUILD Country: EU
,I/SystemConfig( 7033): BUILD Operator: OPEN
,I/ActivityManager( 1030): Killing 6491:com.android.chrome/u0a57 (adj 15): empty #17
,W/libprocessgroup( 1030): failed to open /acct/uid_10057/pid_6491/cgroup.procs: No such file or directory
,I/ActivityManager( 1030): Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=7054 uid=10027 gids={50027, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
,I/SystemConfig( 7033): pm.hasSystemFeature(com.lge.ims.rcs) = false
I/SystemConfig( 7033): existFile = false
I/SystemConfig( 7033): canReadFile = false
I/SystemConfig( 7033): systemFeature RCS result false
D/SystemConfig( 7033): refreshRcsSupport() :false
,W/ResourcesManager( 7054): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7054): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 7054): Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
W/ResourcesManager( 7054): Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
,I/AppConfig( 7054): Total System Memory = 2995761152
,D/SystemHelper( 7054): region [EU], country [EU], operator [OPEN], sub-operator []
I/ActivityManager( 1030): Killing 6663:com.google.android.apps.plus/u0a97 (adj 15): empty #17
,W/libprocessgroup( 1030): failed to open /acct/uid_10097/pid_6663/cgroup.procs: No such file or directory
,I/UpdateIcingCorporaServi( 4236): Updating corpora: APPS=com.google.android.talk, CONTACTS=MAYBE
,V/SIM_STK ( 1030): Menu title from STK is T-Mobile
,I/ActivityManager( 1030): Start proc com.lge.lockscreensettings for broadcast com.lge.lockscreensettings/.PackageIntentReceiver: pid=7075 uid=10080 gids={50080, 9997, 1028, 1015} abi=armeabi-v7a
,W/ResourcesManager( 4236): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/UpdateIcingCorporaServi( 4236): UpdateCorporaTask done [took 90 ms] updated apps [took 90 ms] 
,I/LockScreenSettings( 7075): Wallpaper base directory = /data/data/com.lge.lockscreensettings/files/
,D/LockScreenSettings( 7075): Quick window widget present in DB = com.lge.clock.quickcover.QuickCoverSettingActivity  true
D/LockScreenSettings( 7075): Quick window widget present in DB = com.lge.camera.app.QuickWindowCameraActivity  true
D/LockScreenSettings( 7075): Quick window widget present in DB = com.android.contacts.activities.QuickCircleActivity  true
D/LockScreenSettings( 7075): Quick window widget present in DB = com.android.mms.quickcover.QuickCoverActivity  true
D/LockScreenSettings( 7075): Quick window widget present in DB = com.lge.music.MusicQuickCircle  true
,D/LockScreenSettings( 7075): Quick window widget present in DB = com.lge.lifetracker.QuickCover  true
I/ActivityManager( 1030): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=7093 uid=10097 gids={50097, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager( 1030): Killing 6518:com.lge.email/u0a23 (adj 15): empty #17
,W/libprocessgroup( 1030): failed to open /acct/uid_10023/pid_6518/cgroup.procs: No such file or directory
,W/ResourcesManager( 7093): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,D/PackageBroadcastService( 2352): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.talk
,I/PeopleContactsSync( 2352): CP2 sync disabled
,I/art     ( 1030): Explicit concurrent mark sweep GC freed 35379(1643KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 44MB/66MB, paused 3.698ms total 173.203ms
,I/GLSActivity( 2126): [ac] getting account id
,I/art     ( 2126): Explicit concurrent mark sweep GC freed 23051(1372KB) AllocSpace objects, 9(1296KB) LOS objects, 51% free, 30MB/62MB, paused 1.268ms total 41.700ms
,I/GLSUser ( 2126): [t] Fetched account id for thalitester@gmail.com : 105256135866144380227
,E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=1.5, 0.0, 0.0  rx=1.4 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1553157241] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=1.5, 0.0, 0.0  rx=1.4 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1553157238] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=1.3, 0.0, 0.0  rx=1.2 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1553154208] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=1.3, 0.0, 0.0  rx=1.2 bcn=0 [on:0 tx:0 rx:0 period:12] from screen [on:0 period:-1553154196] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
I/ActivityManager( 1030): Killing 5135:com.wsandroid.suite.lge/1000 (adj 15): empty #17
,W/libprocessgroup( 1030): failed to open /acct/uid_1000/pid_5135/cgroup.procs: No such file or directory
,E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=0.6, 0.0, 0.0  rx=0.6 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1553151178] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=0.6, 0.0, 0.0  rx=0.6 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-1553151168] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
V/AlarmManager( 1030): RTC_WAKEUP set : Alarm{230c9795 type 0 when 1454440761740 com.android.vending} when 1454440761740
,V/SIM_STK ( 1030): Menu title from STK is T-Mobile
,V/GLSActivity( 2126): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2126): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 2126): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2126): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2126): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2126): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/Finsky  ( 6880): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 6880): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 6880): [1] 5.onFinished: Scheduling replication attempt 3.
,V/AlarmManager( 1030): ELAPSED_WAKEUP set : Alarm{2ce5966f type 2 when 155826 android} when 155826
,E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1553148146] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1553148143] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
,D/sensors_hal_Time( 1030): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1030): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1030): tsOffsetIs: Apps: 157292506715; DSPS: 5295683; Offset : -4334098245
,E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:-1553145114] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1553145111] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1030):  ConnectedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 1 0
,E/WifiStateMachine( 1030):  L2ConnectedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 1 0
E/WifiStateMachine( 1030):  ConnectModeState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 1 0
E/WifiStateMachine( 1030):  DriverStartedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 1 0
E/WifiStateMachine( 1030):  SupplicantStartedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 1 0
,E/WifiStateMachine( 1030):  DefaultState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 1 0
,E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1553142088] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:12] from screen [on:0 period:-1553142076] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=0.9, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1553139055] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=0.9, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1553139052] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:-1553136024] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1553136021] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1553132995] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1553132992] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
,I/wpa_supplicant( 6108): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=0
,D/WifiMonitor( 1030): Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=0]
E/WifiMonitor( 1030): WifiMonitor:wlan0 cnt=25 dispatchEvent: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=0
E/WifiMonitor( 1030): handleEvent 2  CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=0
D/WifiMonitor( 1030): handleNetworkStateChange: Could not parse disconnect string
E/WifiMonitor( 1030): WifiMonitor notify network disconnect: null reason=0
D/WifiMonitor( 1030): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1030): WifiMonitor:wlan0 cnt=26 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
,D/Tethering( 1030): InitialState.processMessage what=4
D/Tethering( 1030): sendTetherStateChangedBroadcast 0, 0, 0
E/WifiStateMachine( 1030):  ConnectedState NETWORK_DISCONNECTION_EVENT nid=0 reason=0 lastbssid=c0:ff:d4:d3:aa:48 freq=2412 rssi=-63 rt=171959
E/WifiStateMachine( 1030):  L2ConnectedState NETWORK_DISCONNECTION_EVENT nid=0 reason=0 lastbssid=c0:ff:d4:d3:aa:48 freq=2412 rssi=-63 rt=171960
E/WifiStateMachine( 1030):  ConnectModeState NETWORK_DISCONNECTION_EVENT nid=0 reason=0 lastbssid=c0:ff:d4:d3:aa:48 freq=2412 rssi=-63 rt=171960
E/WifiConfigStore( 1030): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/WifiNative-wlan0( 1030): doBoolean: SET_NETWORK 0 bssid any
,D/WifiNative-wlan0( 1030): SET_NETWORK 0 bssid any: returned true
D/WifiNative-wlan0( 1030): doBoolean: SAVE_CONFIG
D/WifiNative-wlan0( 1030): SAVE_CONFIG: returned true
D/WifiNative-wlan0( 1030): doBoolean: DRIVER BTCOEXMODE 2
I/wpa_supplicant( 6108): wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
,D/LGWifiP2pService( 1030): InactiveState{ when=-3ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1030): P2pEnabledState{ when=-3ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0( 1030): DRIVER BTCOEXMODE 2: returned true
D/WifiNative-wlan0( 1030): doBoolean: SET ps 1
D/WifiNative-wlan0( 1030): SET ps 1: returned true
D/CommandListener(  308): Clearing all IP addresses on wlan0
,D/DhcpStateMachine( 1030): RunningState{ when=-10ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
V/NativeCrypto( 2126): Read error: ssl=0xaa6d0600: I/O error during system call, Connection timed out
D/WifiMonitor( 1030): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
E/WifiMonitor( 1030): WifiMonitor:wlan0 cnt=27 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
,I/ActivityManager( 1030): Start proc com.android.settings for broadcast com.android.settings/.deviceinfo.UsbSettingsReceiver: pid=7148 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,I/wpa_supplicant( 6108): wlan0: CTRL-EVENT-SCAN-STARTED 
,D/WifiMonitor( 1030): Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1030): WifiMonitor:wlan0 cnt=28 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1030): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1030): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
V/NativeCrypto( 2126): SSL shutdown failed: ssl=0xaa6d0600: I/O error during system call, Broken pipe
,D/ConnectivityService( 1030): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
D/ConnectivityService( 1030): NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 2
D/WifiHS20( 1030): hidePasspointNotification off =false
,V/WfdStateTracker( 1964): handleWifiStateChangedEvent: 0
W/Settings( 1030): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1030): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1030): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
I/StatusBar.NetworkController( 1472): networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1472): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1472): refreshViews: Data not connected!! Set no data type icon / Roaming
D/WifiHS20( 1030): hidePasspointNotification off =false
,W/Settings( 1030): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1030): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1030): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
E/WifiStateMachine( 1030): WifiStateMachine: Leaving Connected state
E/WifiStateMachine( 1030):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 26 0 rt=172127  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: DISCONNECTED
D/ConnectivityService( 1030): reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10005
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1030): ValidatedState{ when=-1ms what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1030): DefaultState{ when=-1ms what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1030): Forcing reevaluation
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1030): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1030): Checking http://clients3.google.com/generate_204 on <unknown ssid>
I/StatusBar.NetworkController( 1472): networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1472): mWifiConnected = false, mWifiLevel = 0
,E/WifiStateMachine( 1030):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 26 0 rt=172127  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: DISCONNECTED
E/WifiStateMachine( 1030):  DisconnectedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1030):  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1030):  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1030):  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1030):  DefaultState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1030):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 27 0 rt=172136  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
D/StatusBar.NetworkController( 1472): refreshViews: Data not connected!! Set no data type icon / Roaming
D/WifiHS20( 1030): hidePasspointNotification off =false
W/Settings( 1030): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1030): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1030): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
,I/StatusBar.NetworkController( 1472): networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1472): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1472): refreshViews: Data not connected!! Set no data type icon / Roaming
I/StatusBar.NetworkController( 1472): networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1472): mWifiConnected = false, mWifiLevel = 0
W/Settings( 1030): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1030): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1030): NETWORK_STATE_CHANGED_ACTION [SCANNING]
D/StatusBar.NetworkController( 1472): refreshViews: Data not connected!! Set no data type icon / Roaming
E/WifiStateMachine( 1030):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 27 0 rt=172151  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
E/WifiStateMachine( 1030):  DisconnectedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1030):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1030):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1030):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1030):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
,E/WifiStateMachine( 1030):  DisconnectedState CMD_UPDATE_LINKPROPERTIES 0 0
D/ConnectivityService( 1030): Default network via Wi-Fi disconnect. stop DSQN
D/DSQN    ( 1030): disableDataServiceNotify
D/DSQN    ( 1030): stop dsqn bin
E/WifiStateMachine( 1030):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
D/libc-netbsd(  308): default dns: query_ipv6=0, query_ipv4=0
D/DSQN    ( 1030): DNSproblemNotiEnabled is disabled ignore DNS fail CB
E/WifiStateMachine( 1030):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1030): Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
E/WifiStateMachine( 1030):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1030):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
D/WifiNetworkAgent( 1030): NetworkAgent: NetworkAgent channel lost
D/ConnectivityService( 1030): notifyType LOST for NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService( 1030):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1030):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1030): sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
D/Nat464Xlat( 1030): requiresClat: netType=1, connected=false, hasIPv4Address=true, hasInternetCapability=true
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1030): EvaluatingState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityManager.CallbackHandler( 1472): CM callback handler got msg 524292
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1030): DefaultState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/CSLegacyTypeTracker( 1030): [lge_data] remove agent NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.141/24,fe80::c69a:2ff:fe7b:60ac/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} } list []  wasFirstNetwork :true
D/CSLegacyTypeTracker( 1030): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
D/ConnectivityService( 1030): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1030): Disconnected - quitting
D/WifiServerServiceExt( 1030): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1030): setSupplicantStateDISCONNECTED
D/ConnectivityService( 1030): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService( 1030): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
V/NetworkPolicy( 1030): [LG_RESTRICTED] !!!isConnected  type  :1
D/LocSvc_java( 1030): Sending msg: 4 arg1:0 arg2:1
,D/LocSvc_java( 1030): getAGpsConnectionInfo connType - 4
,D/LocSvc_java( 1030): updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java( 1030): ignore wifi update if we are not in OPENING or CLOSING
D/ConnectivityService( 1030): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService( 1030): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1030): sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/NetworkManagementService( 1030): Removing idletimer
W/Settings( 1030): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/ConnectivityService( 1030): requestNetworkTransitionWakelock: wakelock - ignore in airplane mode
E/ConnectivityService( 1030): EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
D/WIFI    ( 1030): new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    ( 1030):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/TelephonyNetworkFactory-1( 1866): new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/TelephonyNetworkFactory-1( 1866):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
V/NetworkPolicy( 1030): [LG_RESTRICTED] !!!isConnected  type  :1
D/LocSvc_java( 1030): Sending msg: 4 arg1:0 arg2:1
D/WifiServerServiceExt( 1030): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1030): setSupplicantStateSCANNING
D/LocSvc_java( 1030): getAGpsConnectionInfo connType - 4
D/LocSvc_java( 1030): updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java( 1030): ignore wifi update if we are not in OPENING or CLOSING
,D/TelephonyIcons( 1472): null signal icon name: drawable/stat_sys_signal_null
D/StatusBar.NetworkController( 1472): refreshViews: Data not connected!! Set no data type icon / Roaming
D/StatusBar.NetworkController( 1472): refreshViews: Data not connected!! Set no data type icon / Roaming
,D/TelephonyIcons( 1472): null signal icon name: drawable/stat_sys_signal_null
D/StatusBar.NetworkController( 1472): refreshViews: Data not connected!! Set no data type icon / Roaming
D/StatusBar.NetworkController( 1472): refreshViews: Data not connected!! Set no data type icon / Roaming
W/ResourcesManager( 7148): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7148): Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
,W/ResourcesManager( 7148): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 7148): Asset path '/system/framework/com.lge.bluetooth.jar' does not exist or contains no resources.
W/ResourcesManager( 7148): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
W/ResourcesManager( 7148): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
D/UsbSettingsReceiver( 7148): [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
D/UsbSettingsReceiver( 7148): [AUTORUN] sys.usb.config = ptp_only,adb
D/UsbSettingsReceiver( 7148): [AUTORUN] sys.usb.state = ptp_only,adb
D/UsbSettingsReceiver( 7148): [AUTORUN] persist.sys.usb.config = ptp_only,adb
D/UsbSettingsReceiver( 7148): [AUTORUN] onReceive() : app userid = 0, current userid = 0
,D/DhcpStateMachine( 1030): StoppedState
D/UsbSettingsControl( 7148): [AUTORUN] getUsbConnected() : connected=true
D/UsbSettingsReceiver( 7148): [AUTORUN] onReceive() : availableList=[]
D/UsbSettingsReceiver( 7148): [AUTORUN] onReceive() : activeList=[]
D/UsbSettingsReceiver( 7148): [AUTORUN] onReceive() : errorList=[]
D/UsbSettingsControl( 7148): [AUTORUN] isAutorunTimer() : mAutorunChanging=false
D/UsbSettingsControl( 7148): [AUTORUN] setTetherStatus() : status=false
,I/ActivityManager( 1030): Start proc com.wsandroid.suite.lge for broadcast com.wsandroid.suite.lge/com.wavesecure.core.WSAndroidSystemIntentReceiver: pid=7189 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
I/ActivityManager( 1030): Killing 6749:com.qualcomm.timeservice/1000 (adj 15): empty #17
,W/libprocessgroup( 1030): failed to open /acct/uid_1000/pid_6749/cgroup.procs: No such file or directory
,W/ResourcesManager( 7189): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,D/PluginManager( 7189): init()
,W/ExternalStrings( 7189): load override strings
W/ExternalStrings( 7189): java.lang.RuntimeException: Unexpected tag, got eat-comment
W/ExternalStrings( 7189): 	at com.mcafee.plugin.af.a(Unknown Source)
W/ExternalStrings( 7189): 	at com.mcafee.plugin.ac.b(Unknown Source)
W/ExternalStrings( 7189): 	at com.mcafee.plugin.ak.d(Unknown Source)
W/ExternalStrings( 7189): 	at com.mcafee.plugin.ak.a(Unknown Source)
W/ExternalStrings( 7189): 	at com.mcafee.app.s.getClassLoader(Unknown Source)
W/ExternalStrings( 7189): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5001)
W/ExternalStrings( 7189): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4609)
W/ExternalStrings( 7189): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4549)
W/ExternalStrings( 7189): 	at android.app.ActivityThread.access$1500(ActivityThread.java:148)
W/ExternalStrings( 7189): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1344)
W/ExternalStrings( 7189): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/ExternalStrings( 7189): 	at android.os.Looper.loop(Looper.java:135)
W/ExternalStrings( 7189): 	at android.app.ActivityThread.main(ActivityThread.java:5274)
W/ExternalStrings( 7189): 	at java.lang.reflect.Method.invoke(Native Method)
W/ExternalStrings( 7189): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/ExternalStrings( 7189): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
W/ExternalStrings( 7189): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
,D/StatusProvider( 7189): onCreate
V/Signer  ( 7189): override build config not found
D/Signer  ( 7189): value of property debug is false
,D/LGMDMWrapper( 7189): Found class 'com.mcafee.lgmdm.LGMDMWrapper$DataWipe'.
D/LGMDMWrapper( 7189): Found class 'com.mcafee.lgmdm.LGMDMWrapper$DownloadMode'.
D/LGMDMWrapper( 7189): Found class 'com.mcafee.lgmdm.LGMDMWrapper$HardReset'.
D/LGMDMWrapper( 7189): Found class 'com.mcafee.lgmdm.LGMDMWrapper$HardwareKeyReset'.
D/LGMDMWrapper( 7189): Found class 'com.mcafee.lgmdm.LGMDMWrapper$RemoveDeviceAdmin'.
D/LGMDMWrapper( 7189): Found class 'com.mcafee.lgmdm.LGMDMWrapper$UnknownSourceInstallation'.
D/LGMDMWrapper( 7189): Found class 'com.mcafee.lgmdm.LGMDMWrapper$Usb'.
D/LGMDMWrapper( 7189): Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbDebugging'.
D/LGMDMWrapper( 7189): Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbHostStorage'.
D/LGMDMWrapper( 7189): Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbMediaTransfer'.
D/LGMDMWrapper( 7189): Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbPictureTransfer'.
,D/LGMDMWrapper( 7189): Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbStorage'.
D/LGMDMWrapper( 7189): Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbTethering'.
V/LGMDMManager( 7189): Create singleton instance
D/LGMDMWrapper( 7189): LG MDM library v4.0.0 is available on this device.
,D/PostponalbeReceiver( 7189): WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,W/ContextImpl( 7189): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
I/ActivityManager( 1030): Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=7217 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,I/ActivityManager( 1030): Killing 6767:com.android.calendar/u0a13 (adj 15): empty #17
I/art     (  337): Explicit concurrent mark sweep GC freed 708(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 194us total 12.028ms
,I/art     (  337): Explicit concurrent mark sweep GC freed 6(208B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 188us total 8.931ms
I/art     (  337): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 204us total 9.073ms
,W/libprocessgroup( 1030): failed to open /acct/uid_10013/pid_6767/cgroup.procs: No such file or directory
,W/ActivityThread( 7189): ClassLoader.getResources: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,I/PCSuite ( 7217): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
,D/PCSuite ( 7217): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 7217): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 7148): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/LgDataFeature( 7148): LgDataFeature() Constructor: none
D/LgDataFeature( 7148): LgDataFeature() Constructor Done, null
,D/WiFiOffLoadBroadcast( 7148): MCCMNC not supported: null
,D/QRemote ( 6242): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,D/QRemote ( 6242): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 6242): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
D/PostponalbeReceiver( 7189): WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
W/ContextImpl( 7189): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
,I/PCSuite ( 7217): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 7217): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 7217): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 7148): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 7148): MCCMNC not supported: null
D/QRemote ( 6242): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6242): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 6242): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,D/PostponalbeReceiver( 7189): WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,W/ContextImpl( 7189): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
I/PCSuite ( 7217): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 7217): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 7217): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 7148): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 7148): MCCMNC not supported: null
D/QRemote ( 6242): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,D/QRemote ( 6242): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 6242): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
D/PostponalbeReceiver( 7189): WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
W/ContextImpl( 7189): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
V/WiFiOffLoadBroadcast( 7148): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 7148): MCCMNC not supported: null
D/QRemote ( 6242): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6242): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 6242): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,D/LgDataFeature( 7189): LgDataFeature() Constructor: none
D/LgDataFeature( 7189): LgDataFeature() Constructor Done, null
D/PostponalbeReceiver( 7189): WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'null'.
,D/PostponalbeReceiver( 7189): WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'null'.
D/PostponalbeReceiver( 7189): WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'null'.
D/PostponalbeReceiver( 7189): WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'null'.
I/ActivityManager( 1030): Killing 6803:com.google.android.talk/u0a72 (adj 15): empty #17
,W/libprocessgroup( 1030): failed to open /acct/uid_10072/pid_6803/cgroup.procs: No such file or directory
,W/ContextImpl( 7189): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.vsmandroid.gh.h:-1 com.mcafee.vsm.ext.common.a.d.a:-1 com.mcafee.vsm.ext.common.api.ExtUtils.stopApp:-1 
,D/SiteAdvisor( 7189): com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.google.android.browser/com.android.browser.BrowserActivity not supported
,D/SiteAdvisor( 7189): com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.amazon.cloud9/com.amazon.cloud9.BrowserActivity not supported
D/SiteAdvisor( 7189): com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.sec.android.app.sbrowser/com.sec.android.app.sbrowser.SBrowserMainActivity not supported
,D/SiteAdvisor( 7189): com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.sec.android.app.sbrowser/com.sec.android.app.sbrowser.SBrowserMainActivity not supported
D/SiteAdvisor( 7189): com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.htc.sense.browser/com.htc.sense.browser.BrowserActivity not supported
I/SiteAdvisor( 7189): com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Loading supported browsers: com.android.browser/com.android.browser.BrowserActivity; com.android.chrome/com.android.chrome.Main; 
D/SiteAdvisor( 7189): com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Here is the storedCurrentAppVersion: 3.1.2.1430
,D/SiteAdvisor( 7189): com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Here about to commit perfs
,I/wpa_supplicant( 6108): [LGE_PATCH]scan interval[0] = 2 sec.
,D/WfdsMonitor( 1964): Event [CTRL-EVENT-SCAN-RESULTS ]
D/WfdsMonitor( 1964): Event [WPS-AP-AVAILABLE ]
E/WifiMonitor( 1030): WifiMonitor:wlan0 cnt=29 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
E/WifiMonitor( 1030): handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
D/WifiMonitor( 1030): Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
E/WifiMonitor( 1030): WifiMonitor:wlan0 cnt=30 dispatchEvent: WPS-AP-AVAILABLE 
W/WifiMonitor( 1030): couldn't identify event type - WPS-AP-AVAILABLE 
E/WifiMonitor( 1030): WifiMonitor:p2p0 cnt=31 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
E/WifiMonitor( 1030): handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
D/LGWifiP2pService( 1030): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1030): P2pEnabledState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1030): DefaultState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiMonitor( 1030): Event [IFNAME=p2p0 WPS-AP-AVAILABLE ]
E/WifiMonitor( 1030): WifiMonitor:p2p0 cnt=32 dispatchEvent: WPS-AP-AVAILABLE 
W/WifiMonitor( 1030): couldn't identify event type - WPS-AP-AVAILABLE 
E/WifiStateMachine( 1030):  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=4 known=0 got=4 bcn=0
E/WifiStateMachine( 1030):  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=4 known=0 got=4 bcn=0
E/WifiStateMachine( 1030):  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=4 known=0 got=4 bcn=0
E/WifiStateMachine( 1030):  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=4 known=0 got=4 bcn=0
D/WifiNative-wlan0( 1030): doString: [BSS RANGE=0- MASK=0x21987]
,E/WifiStateMachine( 1030):  DisconnectedState CMD_START_SCAN -2 -2 ic=1 proc(ms):3 rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 fiv=20000 [on:0 tx:0 rx:0 period:2617] from screen [on:0 period:-1553130351]
,E/WifiStateMachine( 1030):  ConnectModeState CMD_START_SCAN -2 -2 ic=1 proc(ms):6 rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 fiv=20000 [on:0 tx:0 rx:0 period:2] from screen [on:0 period:-1553130349]
,V/AlarmManager( 1030): RTC_WAKEUP set : Alarm{21ebfb80 type 0 when 1454440780819 android} when 1454440780819
V/AlarmManager( 1030): RTC_WAKEUP set : Alarm{19f13dfe type 0 when 1454440782984 com.android.vending} when 1454440782984
,E/WifiStateMachine( 1030):  DriverStartedState CMD_START_SCAN -2 -2 ic=1 proc(ms):9 rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 fiv=20000 [on:0 tx:0 rx:0 period:27] from screen [on:0 period:-1553130322]
,D/WifiNative-wlan0( 1030): doBoolean: SCAN
I/wpa_supplicant( 6108): wlan0: CTRL-EVENT-SCAN-STARTED 
D/WifiMonitor( 1030): Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1030): WifiMonitor:wlan0 cnt=33 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1030): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1030): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
D/WifiNative-wlan0( 1030): SCAN: returned true
V/SIM_STK ( 1030): Menu title from STK is T-Mobile
,V/GLSActivity( 2126): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2126): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 2126): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2126): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2126): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2126): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/Finsky  ( 6880): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 6880): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 6880): [1] 5.onFinished: Scheduling replication attempt 4.
,E/WifiStateMachine( 1030):  DisconnectedState CMD_RSSI_POLL 1 0 0x 00:00:00:00:00:00 rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:352] from screen [on:0 period:-1553129966] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1030):  ConnectModeState CMD_RSSI_POLL 1 0 0x 00:00:00:00:00:00 rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1553129963] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1030):  DriverStartedState CMD_RSSI_POLL 1 0 0x 00:00:00:00:00:00 rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:2] from screen [on:0 period:-1553129961] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1030):  SupplicantStartedState CMD_RSSI_POLL 1 0 0x 00:00:00:00:00:00 rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:2] from screen [on:0 period:-1553129959] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1030):  DefaultState CMD_RSSI_POLL 1 0 0x 00:00:00:00:00:00 rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:13] from screen [on:0 period:-1553129946] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/ConnectivityService( 1030): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering( 1030): MasterInitialState.processMessage what=3
D/GpsLocationProvider( 1030): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,D/ConnectivityService( 1030): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
D/Tethering( 1030): MasterInitialState.processMessage what=3
,D/PostponalbeReceiver( 7189): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
I/NetworkMonitor( 5182): type=WIFI subType= reason=null isConnected=false
,I/NetworkMonitor( 5182): type=WIFI subType= reason=null isConnected=false
,W/ContextImpl( 7189): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
,I/NetworkStateForAutoUpdateMonitor( 6998): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 6998): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
,I/NetworkStateForAutoUpdateMonitor( 6998): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 6998): [onReceive] request level :IDLE....
I/AppUp4:CustModeStarterReceiver( 6998): onReceive
,D/AppUp4:CustFacade( 6998): Context : android.app.ReceiverRestrictedContext@1f364564
D/AppUp4:CustFacade( 6998): isCustomizationCompleted : false
D/AppUp4:CustFacade( 6998): isPhone : true
D/AppUp4:CustModeStarterReceiver( 6998): begin check event
I/AppUp4:CustModeStarterReceiver( 6998): Event For GoodConnectivity
D/AppUp4:CustModeStarterReceiver( 6998): runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
D/AppUp4:CustModeStarterReceiver( 6998): call method handleAsyncCustNotification.
D/AppUp4:CustModeStarterReceiver( 6998): handleAsync isTriedOnce : false
E/AppUp4:CustModeStarterReceiver( 6998): handleAsyncCustNotification do not startCustService
,D/LGDMClient( 3984): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 3984): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
W/ContextImpl( 3984): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
W/ContextImpl( 3984): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,D/LGDMClient( 3984): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=3, isUserType=1
,D/LGDMClient( 3984): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 3984): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
I/ActivityManager( 1030): Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=7290 uid=10023 gids={50023, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,D/GpsLocationProvider( 1030): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,D/GpsLocationProvider( 1030): updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/GpsLocationProvider( 1030): updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
W/ResourcesManager( 7290): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7290): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,W/ResourcesManager( 7290): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
,W/ResourcesManager( 7290): Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
I/LGEmail ( 7290): [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,D/LGEmail ( 7290): user build Type == true (at Util.java isUserModeBuildType 3507)[v:6.41.18]
,W/ResourceType( 7290): No package identifier when getting value for resource number 0x00000000
,D/LgDataFeature( 7290): LgDataFeature() Constructor: none
D/LgDataFeature( 7290): LgDataFeature() Constructor Done, null
,D/eas_req ( 7290): ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
,I/ActivityManager( 1030): Start proc com.lge.formmanager for broadcast com.lge.formmanager/.FormServiceReceiver: pid=7318 uid=10026 gids={50026, 9997, 3003, 1028} abi=armeabi-v7a
,I/HubEmail( 7290): JNI_OnLoad()
I/HubEmail( 7290): -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 7290): registerNatives()
I/HubEmail( 7290): -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 7290): registerNativeMethods()
I/HubEmail( 7290): -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
W/art     ( 7290): JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
,I/ActivityManager( 1030): Killing 6723:com.lge.clock/u0a10 (adj 15): empty #17
W/libprocessgroup( 1030): failed to open /acct/uid_10010/pid_6723/cgroup.procs: No such file or directory
,W/Settings( 7290): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/LgeMiscReceiver( 3300): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 3300): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 3300): networkInfo.isConnected() = false
,I/ActivityManager( 1030): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=7354 uid=10057 gids={50057, 9997, 3003, 1028, 1015} abi=armeabi-v7a
W/FormManager( 7318): Network not available. Please check & try again.
V/FormManager( 7318): Network unavailable.
,V/FormManager( 7318): Network unavailable.
I/ActivityManager( 1030): Killing 6599:com.lge.sizechangable.weather/u0a85 (adj 15): empty #17
,W/libprocessgroup( 1030): failed to open /acct/uid_10085/pid_6599/cgroup.procs: No such file or directory
I/ActivityManager( 1030): Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=7373 uid=10062 gids={50062, 9997, 4002, 3003, 1028} abi=armeabi-v7a
,I/ActivityManager( 1030): Killing 6455:com.google.android.apps.books/u0a54 (adj 15): empty #17
W/libprocessgroup( 1030): failed to open /acct/uid_10054/pid_6455/cgroup.procs: No such file or directory
,V/AlarmManager( 1030): ELAPSED_WAKEUP set : Alarm{3165876a type 2 when 176469 com.google.android.gms} when 176469
,I/ActivityManager( 1030): Start proc com.lge.sizechangable.weather for broadcast com.lge.sizechangable.weather/.layout.WeatherWidget: pid=7393 uid=10085 gids={50085, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager( 1030): Killing 6923:com.google.android.gms:car/u0a5 (adj 15): empty #17
W/libprocessgroup( 1030): failed to open /acct/uid_10005/pid_6923/cgroup.procs: No such file or directory
,I/art     ( 7393): Almond Protected OAT
,D/WeatherApplication( 7393): removeAccount
,D/WeatherApplication( 7393): Account.length = 0
E/WeatherApplication( 7393): OPERATOR:OPEN
D/WeatherAncestor( 7393): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 20:19:45
D/Weather.Utils( 7393): 2 : the weather widgets(using time tick) are gone.
D/Weather.Utils( 7393): 2 : All the weather widget is gone.
D/UpdateThreadPoolManager( 7393): 2 : This is isUpdating : false
,D/WeatherAncestor( 7393): connectivity changed - connection : true
D/WeatherService( 7393): 2 : isServiceAlived():false forecastCache:null
E/WifiMonitor( 1030): WifiMonitor:wlan0 cnt=34 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
E/WifiMonitor( 1030): handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
D/WifiMonitor( 1030): Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
E/WifiMonitor( 1030): WifiMonitor:wlan0 cnt=35 dispatchEvent: WPS-AP-AVAILABLE 
W/WifiMonitor( 1030): couldn't identify event type - WPS-AP-AVAILABLE 
I/wpa_supplicant( 6108): Trying to associate with SSID 'NG700'
E/WifiStateMachine( 1030):  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=4 known=0 got=4 bcn=0
E/WifiStateMachine( 1030):  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=4 known=0 got=4 bcn=0
D/ForecastDataCache( 7393): 2 : lastUpdatedTime: 1430558561343
D/ForecastDataCache( 7393): 2 : currentPackageVersion: 4.40.4
D/ForecastDataCache( 7393): 2 : Cache is not up-to-date, count: 0
E/WifiStateMachine( 1030):  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=4 known=0 got=4 bcn=0
D/WifiMonitor( 1030): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
E/WifiMonitor( 1030): WifiMonitor:wlan0 cnt=36 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
E/WifiStateMachine( 1030):  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=4 known=0 got=4 bcn=0
D/WifiNative-wlan0( 1030): doString: [BSS RANGE=0- MASK=0x21987]
,E/WifiStateMachine( 1030):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 36 0 rt=176734  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
,E/WifiStateMachine( 1030):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 36 0 rt=176735  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
I/StatusBar.NetworkController( 1472): networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1472): mWifiConnected = false, mWifiLevel = 0
W/Settings( 1030): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1030): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1030): NETWORK_STATE_CHANGED_ACTION [SCANNING]
W/Settings( 1030): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1030): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1030): NETWORK_STATE_CHANGED_ACTION [CONNECTING]
D/StatusBar.NetworkController( 1472): refreshViews: Data not connected!! Set no data type icon / Roaming
D/WifiServerServiceExt( 1030): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1030): setSupplicantStateASSOCIATING
I/StatusBar.NetworkController( 1472): networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1472): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1472): refreshViews: Data not connected!! Set no data type icon / Roaming
D/Weather_cast( 7393): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherAncestor( 7393): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 20:19:45
,I/ActivityManager( 1030): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7411 uid=10093 gids={50093, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager( 1030): Killing 7033:com.android.contacts/u0a19 (adj 15): empty #17
W/libprocessgroup( 1030): failed to open /acct/uid_10019/pid_7033/cgroup.procs: No such file or directory
,E/VoldCmdListener(  280): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
,E/Vold    (  280): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  280): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7411): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
E/VoldCmdListener(  280): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  280): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  280): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7411): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
E/VoldCmdListener(  280): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
,E/Vold    (  280): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  280): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7411): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
E/VoldCmdListener(  280): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  280): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  280): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7411): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
D/sensors_hal_Time( 1030): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1030): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1030): tsOffsetIs: Apps: 177293625977; DSPS: 5951080; Offset : -4334106806
,I/WebViewFactory( 7411): Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,I/LibraryLoader( 7411): Loading: webviewchromium
,I/LibraryLoader( 7411): Time to load native libraries: 12 ms (timestamps 7374-7386)
,I/LibraryLoader( 7411): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 7411): Binding Chromium to main looper Looper (main, tid 1) {15157d2c}
,I/LibraryLoader( 7411): Expected native library version number "",actual native library version number ""
I/chromium( 7411): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 7411): Initializing chromium process, renderers=0
,W/art     ( 7411): Attempt to remove local handle scope entry from IRT, ignoring
W/chromium( 7411): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
,I/chromium( 7411): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=38 off=46780 len=2953
I/chromium( 7411): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:39 off:229536 len:643667
V/AudioPolicyService(  313): registerClient() client 0xb14275e0, uid 10093
,W/AudioManagerAndroid( 7411): Requires BLUETOOTH permission
I/Adreno-EGL( 7411): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 7411): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 7411): Build Date: 12/12/14 금
I/Adreno-EGL( 7411): Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
I/Adreno-EGL( 7411): Remote Branch: 
I/Adreno-EGL( 7411): Local Patches: 
I/Adreno-EGL( 7411): Reconstruct Branch: 
,I/NSApplication( 7411): Starting up...
,I/ActivityManager( 1030): Killing 7054:com.android.gallery3d/u0a27 (adj 15): empty #17
,W/libprocessgroup( 1030): failed to open /acct/uid_10027/pid_7054/cgroup.procs: No such file or directory
,I/iu.Environment( 2352): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,I/iu.UploadsManager( 2352): num queued entries: 0
I/iu.UploadsManager( 2352): num updated entries: 0
I/iu.SyncManager( 2352): NEXT; no task
,D/ChimeraCfgMgr( 2352): Loading module com.google.android.gms.kids from APK com.google.android.gms
D/PostponalbeReceiver( 7189): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
,W/ContextImpl( 7189): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
,I/NetworkStateForAutoUpdateMonitor( 6998): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 6998): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 6998): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 6998): [onReceive] request level :IDLE....
,I/AppUp4:CustModeStarterReceiver( 6998): onReceive
,D/AppUp4:CustFacade( 6998): Context : android.app.ReceiverRestrictedContext@1f364564
D/AppUp4:CustFacade( 6998): isCustomizationCompleted : false
D/AppUp4:CustFacade( 6998): isPhone : true
D/AppUp4:CustModeStarterReceiver( 6998): begin check event
I/AppUp4:CustModeStarterReceiver( 6998): Event For GoodConnectivity, noConnectivity : false, but skip! 
D/LGDMClient( 3984): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 3984): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,W/ContextImpl( 3984): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,W/ContextImpl( 3984): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
D/LGDMClient( 3984): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=3, isUserType=1
,D/eas_req ( 7290): ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
D/LGDMClient( 3984): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 3984): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
W/Settings( 7290): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/FormManager( 7318): Network not available. Please check & try again.
I/LgeMiscReceiver( 3300): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
,I/LgeMiscReceiver( 3300): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 3300): networkInfo.isConnected() = false
D/WeatherAncestor( 7393): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 20:19:46
,V/FormManager( 7318): Network unavailable.
D/Weather.Utils( 7393): 2 : the weather widgets(using time tick) are gone.
,D/Weather.Utils( 7393): 2 : All the weather widget is gone.
D/UpdateThreadPoolManager( 7393): 2 : This is isUpdating : false
D/WeatherAncestor( 7393): connectivity changed - connection : true
D/WeatherService( 7393): 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@31013fc9
D/ForecastDataCache( 7393): 2 : lastUpdatedTime: 1430558561343
D/ForecastDataCache( 7393): 2 : currentPackageVersion: 4.40.4
D/ForecastDataCache( 7393): 2 : Cache is up-to-date, count: 0
D/Weather_cast( 7393): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherAncestor( 7393): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 20:19:46
V/FormManager( 7318): Network unavailable.
D/ChimeraCfgMgr( 2352): Loading module com.google.android.gms.kids from APK com.google.android.gms
,I/art     ( 1030): Explicit concurrent mark sweep GC freed 68492(3MB) AllocSpace objects, 0(0B) LOS objects, 33% free, 44MB/66MB, paused 2.180ms total 159.458ms
,D/libc-netbsd(  308): default dns: query_ipv6=0, query_ipv4=0
D/DSQN    ( 1030): DNSproblemNotiEnabled is disabled ignore DNS fail CB
V/WiFiOffLoadBroadcast( 7148): WiFiOffLoadBroadcast: android.net.wifi.SCAN_RESULTS
,D/WiFiOffLoadBroadcast( 7148): Not supported operator for automatic switch
D/PostponalbeReceiver( 7189): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
V/WiFiOffLoadBroadcast( 7148): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 7148): MCCMNC not supported: null
,D/QRemote ( 6242): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,D/QRemote ( 6242): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 6242): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
D/PostponalbeReceiver( 7189): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
V/WiFiOffLoadBroadcast( 7148): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 7148): MCCMNC not supported: null
D/QRemote ( 6242): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6242): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 6242): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,V/AlarmManager( 1030): ELAPSED_WAKEUP set : Alarm{14df1117 type 2 when 178264 com.google.android.gms} when 178264
,I/wpa_supplicant( 6108): wlan0: Associated with c0:ff:d4:d3:aa:48
,D/WifiMonitor( 1030): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
E/WifiMonitor( 1030): WifiMonitor:wlan0 cnt=37 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
D/WifiMonitor( 1030): Event [IFNAME=wlan0 Associated with c0:ff:d4:d3:aa:48]
E/WifiMonitor( 1030): WifiMonitor:wlan0 cnt=38 dispatchEvent: Associated with c0:ff:d4:d3:aa:48
D/WifiMonitor( 1030): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1030): WifiMonitor:wlan0 cnt=39 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
E/WifiStateMachine( 1030):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 37 0 rt=178332  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
I/wpa_supplicant( 6108): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 6108): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
E/WifiStateMachine( 1030):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 37 0 rt=178335  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
D/WifiMonitor( 1030): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1030): WifiMonitor:wlan0 cnt=40 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/WifiMonitor( 1030): Event [IFNAME=wlan0 WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]]
E/WifiMonitor( 1030): WifiMonitor:wlan0 cnt=41 dispatchEvent: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
W/WifiMonitor( 1030): couldn't identify event type - WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
D/WifiMonitor( 1030): Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]]
E/WifiMonitor( 1030): WifiMonitor:wlan0 cnt=42 dispatchEvent: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
E/WifiMonitor( 1030): handleEvent 1  Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
D/WifiMonitor( 1030): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1030): WifiMonitor:wlan0 cnt=43 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
E/WifiStateMachine( 1030):  DisconnectedState CMD_ASSOCIATED_BSSID 38 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=178339
E/WifiStateMachine( 1030):  ConnectModeState CMD_ASSOCIATED_BSSID 38 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=178339
E/WifiStateMachine( 1030):  DriverStartedState CMD_ASSOCIATED_BSSID 38 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=178340
,E/WifiStateMachine( 1030):  SupplicantStartedState CMD_ASSOCIATED_BSSID 38 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=178343
E/WifiStateMachine( 1030):  DefaultState CMD_ASSOCIATED_BSSID 38 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=178344
E/WifiStateMachine( 1030):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 39 0 rt=178344  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: FOUR_WAY_HANDSHAKE
D/UsbSettingsReceiver( 7148): [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
D/Tethering( 1030): sendTetherStateChangedBroadcast 1, 0, 0
D/UsbSettingsReceiver( 7148): [AUTORUN] sys.usb.config = ptp_only,adb
,D/UsbSettingsReceiver( 7148): [AUTORUN] sys.usb.state = ptp_only,adb
D/UsbSettingsReceiver( 7148): [AUTORUN] persist.sys.usb.config = ptp_only,adb
I/StatusBar.NetworkController( 1472): networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1472): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1472): refreshViews: Data not connected!! Set no data type icon / Roaming
W/Settings( 1030): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings( 1030): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1030): NETWORK_STATE_CHANGED_ACTION [CONNECTING]
D/UsbSettingsReceiver( 7148): [AUTORUN] onReceive() : app userid = 0, current userid = 0
E/WifiStateMachine( 1030):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 39 0 rt=178355  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: FOUR_WAY_HANDSHAKE
I/StatusBar.NetworkController( 1472): networkInfo=[type: WIFI[], state: CONNECTING/AUTHENTICATING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1472): mWifiConnected = false, mWifiLevel = 0
W/Settings( 1030): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1030): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1030): NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
D/StatusBar.NetworkController( 1472): refreshViews: Data not connected!! Set no data type icon / Roaming
E/WifiStateMachine( 1030):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 40 0 rt=178360  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: GROUP_HANDSHAKE
D/UsbSettingsControl( 7148): [AUTORUN] getUsbConnected() : connected=true
D/UsbSettingsReceiver( 7148): [AUTORUN] onReceive() : availableList=[wlan0]
D/UsbSettingsReceiver( 7148): [AUTORUN] onReceive() : activeList=[]
D/UsbSettingsReceiver( 7148): [AUTORUN] onReceive() : errorList=[]
D/UsbSettingsControl( 7148): [AUTORUN] isAutorunTimer() : mAutorunChanging=false
D/UsbSettingsReceiver( 7148): [AUTORUN] onReceive() : TetherState Changed=wlan0
E/WifiStateMachine( 1030):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 40 0 rt=178361  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: GROUP_HANDSHAKE
D/UsbSettingsControl( 7148): [AUTORUN] setTetherStatus() : status=false
D/WifiServerServiceExt( 1030): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1030): setSupplicantStateASSOCIATED
D/PostponalbeReceiver( 7189): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,E/WifiStateMachine( 1030):  DisconnectedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1030):  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1030):  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1030):  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1030):  DefaultState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1030):  DisconnectedState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=178367
E/WifiStateMachine( 1030):  ConnectModeState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=178367
D/WifiNative-wlan0( 1030): doString: [STATUS]
D/WifiMonitor( 1030): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1030): WifiMonitor:wlan0 cnt=44 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/WifiNative-wlan0( 1030):    returned bssid=c0:ff:d4:d3:aa:48 ssid=NG700 id=0 mode=station pairwise_cipher=CCMP group_cipher=CCMP key_mgmt=WPA2-PSK wpa_state=COMPLETED p2p_device_address=02:9a:02:7b:60:ac address=c4:9a:02:7b:60:ac uuid=530d3fd0-1ba3-5409-a336-ff4e42af59a2
I/WifiServiceExtension( 1030): setVHTCapabilityType  : false
V/WiFiOffLoadBroadcast( 7148): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 7148): MCCMNC not supported: null
,D/QRemote ( 6242): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6242): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 6242): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
D/PostponalbeReceiver( 7189): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,V/WiFiOffLoadBroadcast( 7148): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
I/WifiServerServiceExt( 1030): wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
I/WifiServerServiceExt( 1030): setKeepAlivePacketInterval msec : 60
,D/WiFiOffLoadBroadcast( 7148): MCCMNC not supported: null
I/StatusBar.NetworkController( 1472): networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1472): mWifiConnected = false, mWifiLevel = 0
W/Settings( 1030): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1030): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1030): NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
D/StatusBar.NetworkController( 1472): refreshViews: Data not connected!! Set no data type icon / Roaming
W/Settings( 1030): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1030): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1030): NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
I/StatusBar.NetworkController( 1472): networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1472): mWifiConnected = false, mWifiLevel = 0
,D/StatusBar.NetworkController( 1472): refreshViews: Data not connected!! Set no data type icon / Roaming
D/QRemote ( 6242): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6242): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
D/ConnectivityService( 1030): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
E/WifiConfigStore( 1030): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
I/QRemote ( 6242): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
D/WifiNative-wlan0( 1030): doBoolean: SET_NETWORK 0 bssid any
D/ConnectivityService( 1030): Got NetworkAgent Messenger
D/ConnectivityService( 1030): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
D/ConnectivityService( 1030): NetworkAgent connected
,D/WifiNative-wlan0( 1030): SET_NETWORK 0 bssid any: returned true
D/WifiNative-wlan0( 1030): doBoolean: SAVE_CONFIG
D/PostponalbeReceiver( 7189): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
D/WifiNative-wlan0( 1030): SAVE_CONFIG: returned true
E/WifiConfigStore( 1030): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/WifiNative-wlan0( 1030): doBoolean: SET_NETWORK 0 bssid any
D/WifiNative-wlan0( 1030): SET_NETWORK 0 bssid any: returned true
D/WifiNative-wlan0( 1030): doBoolean: SAVE_CONFIG
V/WiFiOffLoadBroadcast( 7148): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WifiNative-wlan0( 1030): SAVE_CONFIG: returned true
D/CommandListener(  308): Setting iface cfg
,E/WifiStateMachine( 1030): Start Dhcp Watchdog 2
,E/WifiStateMachine( 1030):  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 43 0 rt=178431  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine( 1030):  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 43 0 rt=178431  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine( 1030):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 43 0 rt=178432  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
D/WifiServerServiceExt( 1030): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1030): setSupplicantStateFOUR_WAY_HANDSHAKE
D/DhcpStateMachine( 1030): StoppedState{ when=-3ms what=196609 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine( 1030): WaitBeforeStartState
D/WifiServerServiceExt( 1030): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1030): setSupplicantStateGROUP_HANDSHAKE
E/WifiStateMachine( 1030):  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 44 0 rt=178434  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine( 1030):  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 44 0 rt=178434  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
D/WiFiOffLoadBroadcast( 7148): MCCMNC not supported: null
E/WifiStateMachine( 1030):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 44 0 rt=178435  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine( 1030):  ObtainingIpState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3537] from screen [on:0 period:-1553126406] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-1553126405] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
D/ConnectivityService( 1030): updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
E/WifiStateMachine( 1030):  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1030):  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
D/QRemote ( 6242): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
E/WifiStateMachine( 1030):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
D/QRemote ( 6242): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
E/WifiStateMachine( 1030):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
I/QRemote ( 6242): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
E/WifiStateMachine( 1030):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1030):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
D/ConnectivityService( 1030): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
,E/WifiStateMachine( 1030):  ObtainingIpState CMD_PRE_DHCP_ACTION 0 0 txpkts=66,0,0
D/WifiServerServiceExt( 1030): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1030): setSupplicantStateCOMPLETED
E/WifiStateMachine( 1030):  L2ConnectedState CMD_PRE_DHCP_ACTION 0 0 txpkts=66,0,0
D/WifiNative-wlan0( 1030): doBoolean: DRIVER SETSUSPENDMODE 0
D/PostponalbeReceiver( 7189): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
V/WiFiOffLoadBroadcast( 7148): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 7148): MCCMNC not supported: null
D/QRemote ( 6242): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6242): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 6242): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
I/wpa_supplicant( 6108): wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 0
D/WifiNative-wlan0( 1030): DRIVER SETSUSPENDMODE 0: returned true
D/WifiNative-wlan0( 1030): doBoolean: SET ps 0
D/WifiNative-wlan0( 1030): SET ps 0: returned true
D/WifiNative-wlan0( 1030): doBoolean: DRIVER BTCOEXMODE 1
I/wpa_supplicant( 6108): wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 1
D/WifiNative-wlan0( 1030): DRIVER BTCOEXMODE 1: returned true
E/WifiStateMachine( 1030): CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
V/DhcpStateMachine( 1030): Current State is mWaitBeforeStartState.
D/LGWifiP2pService( 1030): InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@bd55e7d target=com.android.internal.util.StateMachine$SmHandler }
V/LgDhcpStateMachineHelper( 1030): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
D/LGWifiP2pService( 1030): P2pEnabledState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@bd55e7d target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine( 1030): WaitBeforeStartState{ when=0 what=196615 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine( 1030): DHCP Start wake lock is acquired.
D/CommandListener(  308): Setting iface cfg
D/CommandListener(  308): Trying to bring up wlan0
,V/LgDhcpStateMachineHelper( 1030): setInterfaceUpWithDhcpInfo: IP configuration succeeded: IP address 192.168.1.141/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 86400 seconds
D/WifiServerServiceExt( 1030): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1030): setSupplicantStateCOMPLETED
E/WifiStateMachine( 1030):  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1030):  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1030):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1030):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1030):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
,E/WifiStateMachine( 1030):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
D/ConnectivityService( 1030): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
E/WifiStateMachine( 1030):  ObtainingIpState CMD_POST_DHCP_ACTION 1 0 OK  v4
E/WifiStateMachine( 1030):  L2ConnectedState CMD_POST_DHCP_ACTION 1 0 OK  v4
D/WifiNative-wlan0( 1030): doBoolean: DRIVER BTCOEXMODE 2
D/LGWifiP2pService( 1030): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1030): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 6108): wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
D/WifiNative-wlan0( 1030): DRIVER BTCOEXMODE 2: returned true
D/WifiNative-wlan0( 1030): doBoolean: DRIVER SETSUSPENDMODE 1
I/wpa_supplicant( 6108): wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 1
D/WifiNative-wlan0( 1030): DRIVER SETSUSPENDMODE 1: returned true
D/WifiNative-wlan0( 1030): doBoolean: SET ps 1
D/WifiNative-wlan0( 1030): SET ps 1: returned true
,D/ConnectivityService( 1030): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
E/WifiStateMachine( 1030):  ObtainingIpState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
E/WifiStateMachine( 1030):  L2ConnectedState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
E/WifiStateMachine( 1030): WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
D/ConnectivityService( 1030): ignoring duplicate network state non-change
,I/StatusBar.NetworkController( 1472): networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1472): mWifiConnected = false, mWifiLevel = 0
W/Settings( 1030): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1030): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1030): NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
D/StatusBar.NetworkController( 1472): refreshViews: Data not connected!! Set no data type icon / Roaming
D/ConnectivityService( 1030): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
D/ConnectivityService( 1030): Adding iface wlan0 to network 101
I/StatusBar.NetworkController( 1472): networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1472): mWifiConnected = false, mWifiLevel = 0
,D/StatusBar.NetworkController( 1472): refreshViews: Data not connected!! Set no data type icon / Roaming
D/PostponalbeReceiver( 7189): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
W/Settings( 1030): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1030): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1030): NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
D/WifiHS20( 1030): [PASSPOINT] passpointNotification: hs20AP list is checked
E/WifiStateMachine( 1030): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
I/StatusBar.NetworkController( 1472): networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1472): mWifiConnected = true, mWifiLevel = 2
V/WfdStateTracker( 1964): handleWifiStateChangedEvent: 1
D/StatusBar.NetworkController( 1472): refreshViews: Data not connected!! Set no data type icon / Roaming
,W/Settings( 1030): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1030): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1030): NETWORK_STATE_CHANGED_ACTION [CONNECTED]
D/WifiHS20( 1030): [PASSPOINT] passpointNotification: hs20AP list is checked
W/Settings( 1030): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1030): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1030): NETWORK_STATE_CHANGED_ACTION [CONNECTED]
,V/WiFiOffLoadBroadcast( 7148): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,I/StatusBar.NetworkController( 1472): networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
E/ConnectivityService( 1030): Unexpected mtu value: 0, wlan0
D/ConnectivityService( 1030): Adding Route [fe80::/64 -> :: wlan0] to network 101
I/StatusBar.NetworkController( 1472): mWifiConnected = true, mWifiLevel = 2
D/ConnectivityService( 1030): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
D/StatusBar.NetworkController( 1472): refreshViews: Data not connected!! Set no data type icon / Roaming
E/Netd    (  308): netlink response contains error (File exists)
D/ConnectivityService( 1030): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
D/ConnectivityService( 1030): addLocalRoutetoDefaultNetwork
D/ConnectivityService( 1030): defaultNAI is null or Wi-Fi no need to add Loacal route to default network. WiFi netid = 101
D/ConnectivityService( 1030): Setting Dns servers for network 101 to [/192.168.1.1]
D/WiFiOffLoadBroadcast( 7148): MCCMNC not supported: null
D/Nat464Xlat( 1030): requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
D/ConnectivityService( 1030): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1030): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1030): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1030):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService( 1030):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1030):     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
D/ConnectivityService( 1030):   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/ConnectivityService( 1030):     satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:true
D/ConnectivityService( 1030): currentScore = 0, newScore = 20
D/ConnectivityService( 1030):    accepting network in place of null
D/ConnectivityService( 1030): sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1030): DefaultState{ when=-1ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1030): Connected
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1030): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1030): Checking http://clients3.google.com/generate_204 on "NG700"
D/WIFI    ( 1030): new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    ( 1030):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/TelephonyNetworkFactory-1( 1866): new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/TelephonyNetworkFactory-1( 1866):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
E/ConnectivityService( 1030): [lg_data] Adding agent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.141/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
D/CSLegacyTypeTracker( 1030): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
D/ConnectivityService( 1030): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService( 1030): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/CSLegacyTypeTracker( 1030): [e] list.add(nai) empty : false size: 1
D/libc-netbsd(  308): res_queryN name = clients3.google.com, class = 1, type = 28
D/ConnectivityService( 1030): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.141/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
D/LocSvc_java( 1030): Sending msg: 4 arg1:1 arg2:1
D/LocSvc_java( 1030): getAGpsConnectionInfo connType - 4
D/LocSvc_java( 1030): updateNetworkState connTyp: 4 available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java( 1030,): ignore wifi update if we are not in OPENING or CLOSING
D/ConnectivityService( 1030): validation of new default Network = false
D/ConnectivityService( 1030): Default network via Wi-Fi connected. start DSQN
D/DSQN    ( 1030): enableDataServiceNotify 
D/DSQN    ( 1030): start dsqn bin
,D/ConnectivityService( 1030): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1030):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
W/dsqn    ( 7508): type=1400 audit(0.0:167): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6838 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
W/dsqn    ( 7508): type=1400 audit(0.0:168): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6838 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
D/ConnectivityService( 1030):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1030): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityManager.CallbackHandler( 1472): CM callback handler got msg 524290
D/QRemote ( 6242): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6242): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 6242): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
D/PostponalbeReceiver( 7189): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,E/DSQN    ( 7508): DSQN ssw
V/WiFiOffLoadBroadcast( 7148): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,V/NetworkPolicy( 1030): [LG_RESTRICTED] checkMobilePolicy_type()
D/WiFiOffLoadBroadcast( 7148): MCCMNC not supported: null
,D/QRemote ( 6242): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/TelephonyIcons( 1472): null signal icon name: drawable/stat_sys_signal_null
D/QRemote ( 6242): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 6242): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
D/StatusBar.NetworkController( 1472): refreshViews: Data not connected!! Set no data type icon / Roaming
D/StatusBar.NetworkController( 1472): refreshViews: Data not connected!! Set no data type icon / Roaming
D/PostponalbeReceiver( 7189): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
D/libc-netbsd(  308): res_queryN name = clients3.google.com, class = 1, type = 1
I/PCSuite ( 7217): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
D/PCSuite ( 7217): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
,V/WiFiOffLoadBroadcast( 7148): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 7148): MCCMNC not supported: null
D/QRemote ( 6242): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,D/QRemote ( 6242): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
D/QRemote ( 6242): [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
I/QRemote ( 6242): [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
I/QRemote ( 6242): [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
D/PostponalbeReceiver( 7189): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
D/libc-netbsd(  308): res_queryN name = clients3.google.com succeed
,I/PCSuite ( 7217): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
D/PCSuite ( 7217): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 7148): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 7148): MCCMNC not supported: null
D/LGDataListener(  308): argv[0]=dsqncommand
D/LGDataListener(  308): argv[1]=wlan0
D/LGDataListener(  308): argv[2]=1
D/LGDataListener(  308): notifyDSQN DSQN STARTMONITOR wlan0 1
D/DSQN    ( 1030): DSQM DsqnNotification wlan0  1
D/DSQN    ( 1030): start to monitor internet connection
D/DhcpStateMachine( 1030): DHCPV4 request on wlan0
V/LgDhcpStateMachineHelper( 1030): [bssid] hash key :c0:ff:d4:d3:aa:48
D/LgDhcpStateMachineHelper( 1030): dhcp.ap.macaddress = c0:ff:d4:d3:aa:48
,D/QRemote ( 6242): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6242): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
W/dhcpcd  ( 7514): type=1400 audit(0.0:169): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6838 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
W/dhcpcd  ( 7514): type=1400 audit(0.0:170): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6838 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
D/QRemote ( 6242): [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
I/QRemote ( 6242): [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
I/QRemote ( 6242): [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
I/dhcpcd  ( 7514): version 5.5.6 starting
,D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1030): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Tue, 02 Feb 2016 19:19:47 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1454440787191], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1454440787169]}
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1030): Don't send network conditions - lacking user consent.
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
D/ConnectivityService( 1030): sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityManager.CallbackHandler( 1472): CM callback handler got msg 524290
E/dhcpcd  ( 7514): get_duid: m
D/dhcpcd  ( 7514): wlan0: using ClientID 01:c4:9a:02:7b:60:ac
D/ConnectivityService( 1030): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
D/dhcpcd  ( 7514): wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason PREINIT
D/WIFI    ( 1030): new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    ( 1030):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/TelephonyNetworkFactory-1( 1866): new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/TelephonyNetworkFactory-1( 1866):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
,D/TelephonyIcons( 1472): null signal icon name: drawable/stat_sys_signal_null
,D/StatusBar.NetworkController( 1472): refreshViews: Data not connected!! Set no data type icon / Roaming
D/StatusBar.NetworkController( 1472): refreshViews: Data not connected!! Set no data type icon / Roaming
D/dhcpcd  ( 7514): getUsingAPMacAddress: c0:ff:d4:d3:aa:48 , return 1
D/dhcpcd  ( 7514): [read_lease] unlink /data/misc/dhcp/dhcpcd-wlan0.lease, link /data/misc/dhcp/dhcpcd-wlan0-c0:ff:d4:d3:aa:48.lease2
D/dhcpcd  ( 7514): wlan0: reading lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
I/dhcpcd  ( 7514): wlan0: rebinding lease of 192.168.1.141
D/dhcpcd  ( 7514): wlan0: sending REQUEST (xid 0x92922b0d), next in 3.38 seconds
,E/WifiStateMachine( 1030):  ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
,E/WifiStateMachine( 1030):  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
,I/dhcpcd  ( 7514): wlan0: acknowledged 192.168.1.141 from 192.168.1.1
,E/WifiStateMachine( 1030):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
E/WifiStateMachine( 1030):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
,E/WifiStateMachine( 1030):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
E/WifiStateMachine( 1030):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
D/ConnectivityService( 1030): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=true
D/ConnectivityService( 1030): identical MTU - not setting
,D/Nat464Xlat( 1030): requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
D/ConnectivityService( 1030): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1030):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1030):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1030): sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityManager.CallbackHandler( 1472): CM callback handler got msg 524295
I/dhcpcd  ( 7514): wlan0: leased 192.168.1.141 for 86400 seconds
D/dhcpcd  ( 7514): wlan0: adding IP address 192.168.1.141/24
D/dhcpcd  ( 7514): wlan0: adding route to 192.168.1.0/24
D/dhcpcd  ( 7514): wlan0: adding default route via 192.168.1.1
D/dhcpcd  ( 7514): wlan0: writing lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
D/dhcpcd  ( 7514): getUsingAPMacAddress: c0:ff:d4:d3:aa:48 , return 1
D/dhcpcd  ( 7514): write_lease_ext: /data/misc/dhcp/dhcpcd-wlan0-c0:ff:d4:d3:aa:48.lease2
D/dhcpcd  ( 7514): wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason REBOOT
D/DhcpStateMachine( 1030): DHCPV4 succeeded on wlan0
D/LgDhcpStateMachineHelper( 1030): CheckDhcpDirectory [Lease File Count] : 3
V/LgDhcpStateMachineHelper( 1030): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
D/LgDhcpStateMachineHelper( 1030): checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.141
V/LgDhcpStateMachineHelper( 1030): Don't need to update mDhcpResultsCacheList
V/DhcpStateMachine( 1030): Current State is mWaitBeforeStartState.
V/LgDhcpStateMachineHelper( 1030): bShouldSendDhcpAction Result: false
D/DhcpStateMachine( 1030): DHCP Start/Renew wake lock is released.
D/DhcpStateMachine( 1030): RunningState
,E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=33.0, 0.0, 0.0  rx=28.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1553123399] gl rssi=-63 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=33.0, 0.0, 0.0  rx=28.0 bcn=0 [on:0 tx:0 rx:0 period:11] from screen [on:0 period:-1553123388] gl rssi=-63 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
D/StatusBar.NetworkController( 1472): refreshViews: Data not connected!! Set no data type icon / Roaming
,V/WifiInternetCheck( 1030): Single check msg out of sync, ignoring.
,D/ConnectivityService( 1030): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering( 1030): MasterInitialState.processMessage what=3
D/PostponalbeReceiver( 7189): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
,I/NetworkMonitor( 5182): type=WIFI subType= reason=null isConnected=true
W/ContextImpl( 7189): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
,I/NetworkStateForAutoUpdateMonitor( 6998): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 6998): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 6998): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 6998): [onReceive] request level :IDLE....
I/AppUp4:CustModeStarterReceiver( 6998): onReceive
,D/AppUp4:CustFacade( 6998): Context : android.app.ReceiverRestrictedContext@1f364564
D/AppUp4:CustFacade( 6998): isCustomizationCompleted : false
D/AppUp4:CustFacade( 6998): isPhone : true
D/AppUp4:CustModeStarterReceiver( 6998): begin check event
I/AppUp4:CustModeStarterReceiver( 6998): Event For GoodConnectivity, noConnectivity : false, but skip! 
,D/LGDMClient( 3984): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 3984): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,W/ContextImpl( 3984): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
W/ContextImpl( 3984): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,V/DownloadManager( 3355): Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
D/eas_req ( 7290): ---addEventToQueue() easCode=2, requestId=0 (at EasSupport.java addEventToQueue 69)
,V/DownloadManager( 3355): DownloadService onCreate
I/DownloadManager( 3355): in removeSpuriousFiles
,V/DownloadManager( 3355): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
,D/LGDMClient( 3984): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=3, isUserType=1
,V/DownloadManager( 3355): created cursor android.database.sqlite.SQLiteCursor@1842df48 on behalf of 3355
I/DownloadManager( 3355): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGMyGuide_4.40.09_COM_COM_20150430011620058_RELG-D855.apk
I/DownloadManager( 3355): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGBackup_4.50.37_COM_COM_20150608234245157.apk
I/DownloadManager( 3355): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/CalendarProvider_4.2.8_COM_COM_20150304234552863_RELG-D855.apk
I/DownloadManager( 3355): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calendar_4.40.16_COM_COM_20150304234554754_RELG-D855.apk
I/DownloadManager( 3355): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.10_COM_COM_20150521235426173_RELG-D855.apk
I/DownloadManager( 3355): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQVoiceplusN_2.3.3_COM_COM_20150604065210803.apk
I/DownloadManager( 3355): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.11_COM_COM_v2_20150911144028620_RELG-D855_21.apk
I/DownloadManager( 3355): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQMemoplus(LG-D855_user)_20150902050954661.apk
I/DownloadManager( 3355): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/RemoteCall_4.1.10_COM_COM_20150817053748728.apk
I/DownloadManager( 3355): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/rspermlge(6713)_20150901080430397.apk
I/DownloadManager( 3355): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGBackup_4.51.57_COM_COM_8275_2_20151201044833536_RELG-D855_21.apk
,D/LGDMClient( 3984): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 3984): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
I/LGDMClient( 3984): [DmServiceProcessor.java] [processNetworkChanged()] : [91] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
W/Settings( 7290): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 7290): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/LgeMiscReceiver( 3300): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 3300): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 3300): networkInfo.isConnected() = true
D/PhoneState( 3300): setPdpRejectCasuse : false
I/DownloadManager( 3355): in trimDatabase
V/DownloadManager( 3355): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
,W/ContextImpl( 3984): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:141 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:180 android.app.IntentService$ServiceHandler.handleMessage:65 
V/DownloadManager( 3355): created cursor android.database.sqlite.SQLiteCursor@2e3131e1 on behalf of 3355
E/LGDMClient( 3984): [DmNotiService.java] [onCreate()] : [148] : DmNotiService.onCreate()
D/LGDMClient( 3984): [DmNotiService.java] [onStartCommand()] : [182] : in the new onStartCommand()
D/LGDMClient( 3984): [DmNotiService.java] [handleStart()] : [203] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
D/WeatherAncestor( 7393): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 20:19:50
,D/Weather.Utils( 7393): 2 : the weather widgets(using time tick) are gone.
D/Weather.Utils( 7393): 2 : All the weather widget is gone.
D/UpdateThreadPoolManager( 7393): 2 : This is isUpdating : false
D/WeatherAncestor( 7393): connectivity changed - connection : true
D/WeatherService( 7393): 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@31013fc9
D/ForecastDataCache( 7393): 2 : lastUpdatedTime: 1430558561343
D/ForecastDataCache( 7393): 2 : currentPackageVersion: 4.40.4
D/ForecastDataCache( 7393): 2 : Cache is up-to-date, count: 0
D/Weather_cast( 7393): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherAncestor( 7393): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 20:19:50
V/GLSActivity( 2126): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/DownloadManager( 3355): DownloadService onStartCommand
V/DownloadManager( 3355): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
D/libc-netbsd(  308): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  308): res_queryN name = static-avc.lglime.com, class = 1, type = 1
,V/DownloadManager( 3355): created cursor android.database.sqlite.SQLiteCursor@b4aa7f4 on behalf of 3355
V/DownloadManager( 3355): processing inserted download 1
V/DownloadManager( 3355): processing inserted download 4
V/DownloadManager( 3355): processing inserted download 7
V/DownloadManager( 3355): processing inserted download 8
V/DownloadManager( 3355): processing inserted download 9
V/DownloadManager( 3355): processing inserted download 10
V/DownloadManager( 3355): processing inserted download 16
V/DownloadManager( 3355): processing inserted download 17
V/DownloadManager( 3355): processing inserted download 18
V/DownloadManager( 3355): processing inserted download 21
V/DownloadManager( 3355): processing inserted download 22
,V/DownloadManager( 3355): DownloadService onDestroy
,D/libc-netbsd(  308): res_queryN name = static-avc.lglime.com succeed
,I/ActivityManager( 1030): Start proc com.google.android.apps.books for service com.google.android.apps.books/.service.SyncService: pid=7597 uid=10054 gids={50054, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/GpsLocationProvider( 1030): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,I/iu.Environment( 2352): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
I/iu.UploadsManager( 2352): num queued entries: 0
I/iu.UploadsManager( 2352): num updated entries: 0
I/iu.SyncManager( 2352): NEXT; no task
V/FormManager( 7318): There are no updated forms. The schedule will be deleted.
,V/FormManager( 7318): Alarm would be updated, because LastCheckTime has been updated.
D/ChimeraCfgMgr( 2352): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/ChimeraCfgMgr( 2352): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/GpsLocationProvider( 1030): updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/libc-netbsd(  308): default dns: query_ipv6=0, query_ipv4=1
,D/libc-netbsd(  308): res_queryN name = mtalk.google.com, class = 1, type = 1
,I/VacuumService( 2126): Vacuum at: now=1454440790523 tag=VacuumService
I/ReaderUtils( 7597): PortraitW 1440 LandscapeW 2392 SmallestSize 1340 LargestSize 2392 textZoom 4.4999995 isTablet false Memory 256
,D/libc-netbsd(  308): res_queryN name = mtalk.google.com succeed
,I/GLSUser ( 2126): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: ac2dm
I/GLSUser ( 2126): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> ac2dm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2126): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2126): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2126): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/GAV4    ( 7411): Thread[GAThread,5,main]: No campaign data found.
,W/GAV2    ( 7597): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,I/BooksApp( 7597): Created application version: 3.2.35 (30235)
,V/GLSActivity( 2126): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/GoogleURLConnFactory( 2126): Using platform SSLCertificateSocketFactory
,V/NotificationService( 1030): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
V/NotificationService( 1030): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1030): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1030): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1030): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1411): onNotificationPosted
W/Kids    ( 2352): [AccountUtils] Account not ready
W/Kids    ( 2352): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/Kids    ( 2352): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/Kids    ( 2352): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/Kids    ( 2352): 	at com.google.android.gms.auth.p.c(SourceFile:550)
W/Kids    ( 2352): 	at com.google.android.gms.auth.p.b(SourceFile:477)
W/Kids    ( 2352): 	at com.google.android.gms.kids.account.k.d(SourceFile:103)
W/Kids    ( 2352): 	at com.google.android.gms.kids.account.p.a(SourceFile:70)
W/Kids    ( 2352): 	at com.google.android.gms.kids.account.t.a(SourceFile:62)
W/Kids    ( 2352): 	at com.google.android.gms.chimera.f.run(SourceFile:179)
W/Kids    ( 2352): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Kids    ( 2352): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Kids    ( 2352): 	at java.lang.Thread.run(Thread.java:818)
D/SmartCoverUpdateMonitor( 1411): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1411): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1411): handleNotificationPosted(true)
D/QuickCircle( 1411): onNotificationPosted() : isPosted true
,D/LgeQuickCoverNotificationData( 1411): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1411): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1411): post do just update job
D/LgeQuickCoverNotificationData( 1411): showAll3
D/LgeQuickCoverNotificationData( 1411): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1411): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1411): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1411): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1411): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1411): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1411): [native noti] inex =  1
,D/LgeQuickCoverNotificationData( 1411): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1411): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1411): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1411): updateNotificationData: count=3
I/GLSUser ( 2126): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.syncadapters.contacts, service: cp
I/GLSUser ( 2126): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> cp without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2126): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2126): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2126): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/Uploader( 2126): No account for auth token provided
I/BooksSync( 7597): Starting books sync
,D/QuickStatusbarLayout( 1411): Notification difference=198
D/QuickStatusbarLayout( 1411): child = android.widget.LinearLayout{183f0fdb V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
D/libc-netbsd(  308): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  308): res_queryN name = play.googleapis.com, class = 1, type = 1
V/NotificationService( 1030): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1030): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1030): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1030): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1030): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
W/GLSActivity( 2126): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2126): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2126): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2126): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2126): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2126): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2126): 	at android.os.Binder.execTransact(Binder.java:446)
D/LgeQuickCoverNLService( 1411): onNotificationPosted
D/SmartCoverUpdateMonitor( 1411): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1411): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1411): handleNotificationPosted(true)
D/QuickCircle( 1411): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1411): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1411): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1411): post do just update job
D/LgeQuickCoverNotificationData( 1411): showAll3
D/LgeQuickCoverNotificationData( 1411): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1411): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1411): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1411): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1411): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1411): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1411): [native noti] inex =  1
D/ContactsSyncAdapter( 2126): innerSync failed
D/ContactsSyncAdapter( 2126): com.google.wireless.gdata2.client.AuthenticationException: unable to get auth token android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
D/ContactsSyncAdapter( 2126): 	at com.google.android.syncadapters.contacts.AuthInfo.getAuthToken(AuthInfo.java:45)
D/ContactsSyncAdapter( 2126): 	at com.google.android.syncadapters.contacts.ContactsSyncAdapter.innerPerformSync(ContactsSyncAdapter.java:263)
D/ContactsSyncAdapter( 2126): 	at com.google.android.syncadapters.contacts.ContactsSyncAdapter.onPerformLoggedSync(ContactsSyncAdapter.java:168)
D/ContactsSyncAdapter( 2126): 	at com.google.android.common.LoggingThreadedSyncAdapter.onPerformSync(LoggingThreadedSyncAdapter.java:33)
D/ContactsSyncAdapter( 2126): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
D/ContactsSyncAdapter( 2126): Caused by: android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
D/ContactsSyncAdapter( 2126): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
D/ContactsSyncAdapter( 2126): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
D/ContactsSyncAdapter( 2126): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
D/ContactsSyncAdapter( 2126): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
D/ContactsSyncAdapter( 2126): 	at android.os.Binder.execTransact(Binder.java:446)
D/LgeQuickCoverNotificationData( 1411): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindo,w( 1411): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1411): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1411): updateNotificationData: count=3
,D/SyncManager( 1030): failed sync operation thalitester@gmail.com u0 (com.google), com.android.contacts, LOCAL, currentRunTime 159649, reason: 10019, SyncResult: stats [ numAuthExceptions: 1]
D/SyncManager( 1030): not retrying sync operation because the error is a hard error: thalitester@gmail.com u0 (com.google), com.android.contacts, LOCAL, currentRunTime 214502, reason: 10019
D/QuickStatusbarLayout( 1411): Notification difference=198
D/QuickStatusbarLayout( 1411): child = android.widget.LinearLayout{183f0fdb V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,D/libc-netbsd(  308): res_queryN name = play.googleapis.com succeed
D/GCM     ( 2126): Connected
,D/GCM     ( 2126): Message class com.google.f.a.a.p
,D/BooksSync( 7597): started syncMyEbooks
,V/GLSActivity( 2126): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2126): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2126): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 2126): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2126): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2126): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/Uploader( 2126): No account for auth token provided
,V/NotificationService( 1030): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1030): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1030): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1030): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1030): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
W/GLSActivity( 2126): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2126): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2126): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2126): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2126): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2126): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2126): 	at android.os.Binder.execTransact(Binder.java:446)
D/LgeQuickCoverNLService( 1411): onNotificationPosted
D/SmartCoverUpdateMonitor( 1411): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1411): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1411): handleNotificationPosted(true)
D/QuickCircle( 1411): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1411): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1411): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1411): post do just update job
D/LgeQuickCoverNotificationData( 1411): showAll3
D/LgeQuickCoverNotificationData( 1411): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1411): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1411): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1411): showNotificationWithSetupData: display=false
,D/LgeQuickCoverOverlayWindow( 1411): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1411): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1411): [native noti] inex =  1
E/BooksAccountManager( 7597): Authentication error
E/BooksAccountManager( 7597): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7597): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 7597): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 7597): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 7597): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 7597): 	at android.os.Binder.execTransact(Binder.java:446)
D/LgeQuickCoverNotificationData( 1411): isNotificationForCurrentUser : true
E/HttpHelper( 7597): null auth token
D/LgeQuickCoverOverlayWindow( 1411): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1411): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1411): updateNotificationData: count=3
D/libc-netbsd(  308): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  308): res_queryN name = www.googleapis.com, class = 1, type = 1
,D/QuickStatusbarLayout( 1411): Notification difference=198
D/QuickStatusbarLayout( 1411): child = android.widget.LinearLayout{183f0fdb V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,W/Uploader( 2126): No account for auth token provided
D/libc-netbsd(  308): res_queryN name = www.googleapis.com succeed
,W/Uploader( 2126):  no longer exists, so no auth token.
D/libc-netbsd(  308): default dns: query_ipv6=0, query_ipv4=1
,D/libc-netbsd(  308): res_queryN name = www.google.com, class = 1, type = 1
,D/libc-netbsd(  308): res_queryN name = www.google.com succeed
,D/libc-netbsd(  308): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  308): res_queryN name = clients3.google.com, class = 1, type = 1
D/libc-netbsd(  308): res_queryN name = clients3.google.com succeed
,W/Uploader( 2126): No account for auth token provided
V/WifiInternetCheck( 1030): isHttpConnectionAvailable - We got a valid response : 204
,W/Uploader( 2126): No account for auth token provided
,W/Uploader( 2126): No account for auth token provided
W/ApiaryClient( 7597): Error response from books API: {
W/ApiaryClient( 7597):  "error": {
W/ApiaryClient( 7597):   "errors": [
W/ApiaryClient( 7597):    {
W/ApiaryClient( 7597):     "domain": "global",
W/ApiaryClient( 7597):     "reason": "required",
W/ApiaryClient( 7597):     "message": "Login Required",
W/ApiaryClient( 7597):     "locationType": "header",
W/ApiaryClient( 7597):     "location": "Authorization"
W/ApiaryClient( 7597):    }
W/ApiaryClient( 7597):   ],
W/ApiaryClient( 7597):   "code": 401,
W/ApiaryClient( 7597):   "message": "Login Required"
W/ApiaryClient( 7597):  }
W/ApiaryClient( 7597): }
W/ApiaryClient( 7597): errCount = 1: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7597): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=6066853396518710436&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7597): Headers:
W/ApiaryClient( 7597): accept-encoding: [gzip]
W/ApiaryClient( 7597): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 7597): gdata-version: 2
,V/GLSActivity( 2126): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2126): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2126): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2126): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2126): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2126): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1030): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1030): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1030): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1030): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1030): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1411): onNotificationPosted
,D/SmartCoverUpdateMonitor( 1411): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1411): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1411): handleNotificationPosted(true)
D/QuickCircle( 1411): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1411): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1411): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1411): post do just update job
D/LgeQuickCoverNotificationData( 1411): showAll3
D/LgeQuickCoverNotificationData( 1411): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1411): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1411): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1411): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1411): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1411): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1411): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1411): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1411): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1411): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1411): updateNotificationData: count=3
W/GLSActivity( 2126): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2126): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2126): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2126): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2126): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2126): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2126): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 7597): Authentication error
E/BooksAccountManager( 7597): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7597): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 7597): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 7597): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 7597): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 7597): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 7597): null auth token
D/QuickStatusbarLayout( 1411): Notification difference=198
D/QuickStatusbarLayout( 1411): child = android.widget.LinearLayout{183f0fdb V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
W/ApiaryClient( 7597): Error response from books API: {
W/ApiaryClient( 7597):  "error": {
W/ApiaryClient( 7597):   "errors": [
W/ApiaryClient( 7597):    {
W/ApiaryClient( 7597):     "domain": "global",
W/ApiaryClient( 7597):     "reason": "required",
W/ApiaryClient( 7597):     "message": "Login Required",
W/ApiaryClient( 7597):     "locationType": "header",
W/ApiaryClient( 7597):     "location": "Authorization"
W/ApiaryClient( 7597):    }
W/ApiaryClient( 7597):   ],
W/ApiaryClient( 7597):   "code": 401,
W/ApiaryClient( 7597):   "message": "Login Required"
W/ApiaryClient( 7597):  }
W/ApiaryClient( 7597): }
,W/ApiaryClient( 7597): errCount = 2: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7597): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=6066853396518710436&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7597): Headers:
W/ApiaryClient( 7597): accept-encoding: [gzip]
W/ApiaryClient( 7597): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 7597): gdata-version: 2
,E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-59 f=2412 sc=60 link=72 tx=21.5, 0.0, 0.0  rx=17.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1553120359] gl rssi=-59 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-59 f=2412 sc=60 link=72 tx=21.5, 0.0, 0.0  rx=17.0 bcn=0 [on:0 tx:0 rx:0 period:12] from screen [on:0 period:-1553120347] gl rssi=-59 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
D/StatusBar.NetworkController( 1472): refreshViews: Data not connected!! Set no data type icon / Roaming
,V/GLSActivity( 2126): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2126): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2126): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2126): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2126): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2126): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     ( 1030): Explicit concurrent mark sweep GC freed 62729(2MB) AllocSpace objects, 6(608KB) LOS objects, 33% free, 44MB/66MB, paused 2.491ms total 156.827ms
,V/NotificationService( 1030): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1030): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1030): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1030): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1030): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1411): onNotificationPosted
D/SmartCoverUpdateMonitor( 1411): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1411): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1411): handleNotificationPosted(true)
D/QuickCircle( 1411): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1411): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1411): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1411): post do just update job
D/LgeQuickCoverNotificationData( 1411): showAll3
D/LgeQuickCoverNotificationData( 1411): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1411): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1411): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1411): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1411): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1411): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1411): [native noti] inex =  1
,D/LgeQuickCoverNotificationData( 1411): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1411): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1411): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1411): updateNotificationData: count=3
W/GLSActivity( 2126): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2126): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2126): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2126): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2126): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2126): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2126): 	at android.os.Binder.execTransact(Binder.java:446)
E/BooksAccountManager( 7597): Authentication error
E/BooksAccountManager( 7597): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7597): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 7597): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 7597): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 7597): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 7597): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 7597): null auth token
,D/QuickStatusbarLayout( 1411): Notification difference=198
D/QuickStatusbarLayout( 1411): child = android.widget.LinearLayout{183f0fdb V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,W/ApiaryClient( 7597): Error response from books API: {
W/ApiaryClient( 7597):  "error": {
W/ApiaryClient( 7597):   "errors": [
W/ApiaryClient( 7597):    {
W/ApiaryClient( 7597):     "domain": "global",
W/ApiaryClient( 7597):     "reason": "required",
W/ApiaryClient( 7597):     "message": "Login Required",
W/ApiaryClient( 7597):     "locationType": "header",
W/ApiaryClient( 7597):     "location": "Authorization"
W/ApiaryClient( 7597):    }
W/ApiaryClient( 7597):   ],
W/ApiaryClient( 7597):   "code": 401,
W/ApiaryClient( 7597):   "message": "Login Required"
W/ApiaryClient( 7597):  }
W/ApiaryClient( 7597): }
W/ApiaryClient( 7597): errCount = 3: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7597): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=6066853396518710436&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7597): Headers:
W/ApiaryClient( 7597): accept-encoding: [gzip]
W/ApiaryClient( 7597): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 7597): gdata-version: 2
,V/AlarmManager( 1030): ELAPSED_WAKEUP set : Alarm{2a5dc1b5 type 2 when 185850 android} when 185850
,E/BooksSync( 7597): Soft error: 
E/BooksSync( 7597): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 7597): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=6066853396518710436&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 7597): Headers:
E/BooksSync( 7597): accept-encoding: [gzip]
E/BooksSync( 7597): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 7597): gdata-version: 2
E/BooksSync( 7597): 
E/BooksSync( 7597): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 7597): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 7597): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 7597): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 7597): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 7597): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 7597): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 7597): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 7597): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 7597): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 7597): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 7597): {
E/BooksSync( 7597):  "error": {
E/BooksSync( 7597):   "errors": [
E/BooksSync( 7597):    {
E/BooksSync( 7597):     "domain": "global",
E/BooksSync( 7597):     "reason": "required",
E/BooksSync( 7597):     "message": "Login Required",
E/BooksSync( 7597):     "locationType": "header",
E/BooksSync( 7597):     "location": "Authorization"
E/BooksSync( 7597):    }
E/BooksSync( 7597):   ],
E/BooksSync( 7597):   "code": 401,
E/BooksSync( 7597):   "message": "Login Required"
E/BooksSync( 7597):  }
E/BooksSync( 7597): }
E/BooksSync( 7597): 
E/BooksSync( 7597): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 7597): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 7597): 	... 8 more
,E/BooksSync( 7597): Sync error
E/BooksSync( 7597): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 7597): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=6066853396518710436&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 7597): Headers:
E/BooksSync( 7597): accept-encoding: [gzip]
E/BooksSync( 7597): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 7597): gdata-version: 2
E/BooksSync( 7597): 
E/BooksSync( 7597): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 7597): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 7597): 	,at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 7597): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 7597): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 7597): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 7597): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 7597): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 7597): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 7597): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 7597): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 7597): {
E/BooksSync( 7597):  "error": {
E/BooksSync( 7597):   "errors": [
E/BooksSync( 7597):    {
E/BooksSync( 7597):     "domain": "global",
E/BooksSync( 7597):     "reason": "required",
E/BooksSync( 7597):     "message": "Login Required",
E/BooksSync( 7597):     "locationType": "header",
E/BooksSync( 7597):     "location": "Authorization"
E/BooksSync( 7597):    }
E/BooksSync( 7597):   ],
E/BooksSync( 7597):   "code": 401,
E/BooksSync( 7597):   "message": "Login Required"
E/BooksSync( 7597):  }
E/BooksSync( 7597): }
E/BooksSync( 7597): 
E/BooksSync( 7597): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 7597): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 7597): 	... 8 more
I/BooksSync( 7597): Finished books sync
I/ActivityManager( 1030): Killing 7075:com.lge.lockscreensettings/u0a80 (adj 15): empty #17
,D/SyncManager( 1030): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 161082, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,W/libprocessgroup( 1030): failed to open /acct/uid_10080/pid_7075/cgroup.procs: No such file or directory
,I/GAV2    ( 7597): Thread[GAThread,5,main]: No campaign data found.
,E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-53 f=2412 sc=60 link=72 tx=39.8, 0.0, 0.0  rx=30.5 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:-1553117320] gl rssi=-53 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-53 f=2412 sc=60 link=72 tx=39.8, 0.0, 0.0  rx=30.5 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1553117317] gl rssi=-53 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
D/StatusBar.NetworkController( 1472): refreshViews: Data not connected!! Set no data type icon / Roaming
,E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=21.4, 0.0, 0.0  rx=16.8 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1553114289] gl rssi=-63 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=21.4, 0.0, 0.0  rx=16.8 bcn=0 [on:0 tx:0 rx:0 period:11] from screen [on:0 period:-1553114278] gl rssi=-63 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
I/[SystemUI]TimeTickManager( 1472): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1472): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1472): called onTimeUpdated()
I/[SystemUI]Clock( 1472): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1472): called onTimeUpdated()
,I/[SystemUI]DateView( 1472): called onTimeUpdated()
I/[SystemUI]DateView( 1472): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1472): handleTimeUpdate
,E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=11.7, 0.0, 0.0  rx=8.4 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1553111255] gl rssi=-63 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=11.7, 0.0, 0.0  rx=8.4 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1553111252] gl rssi=-63 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=6.3, 0.0, 0.0  rx=4.7 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1553108226] gl rssi=-63 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=6.3, 0.0, 0.0  rx=4.7 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1553108223] gl rssi=-63 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
,D/sensors_hal_Time( 1030): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1030): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1030): tsOffsetIs: Apps: 197294982740; DSPS: 6606484; Offset : -4334094352
,E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=3.2, 0.0, 0.0  rx=2.3 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1553105200] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=3.2, 0.0, 0.0  rx=2.3 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-1553105190] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
D/PowerManagerServiceEx( 1030): acquireWakeLockInternal: lock=770300739, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1030
,V/AlarmManager( 1030): RTC_WAKEUP set : Alarm{39f5c431 type 0 when 1454440803265 com.android.vending} when 1454440803265
,D/[Concierge]Service( 2607): onStartCommand(). Type : 9
,D/PowerManagerServiceEx( 1030): releaseWakeLockInternal: lock=770300739 [*alarm*], flags=0x0
,V/SIM_STK ( 1030): Menu title from STK is T-Mobile
,V/GLSActivity( 2126): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2126): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 2126): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2126): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2126): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2126): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/Finsky  ( 6880): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 6880): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 6880): [1] 5.onFinished: Scheduling replication attempt 5.
,E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=2.1, 0.0, 0.0  rx=1.7 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1553102169] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=2.1, 0.0, 0.0  rx=1.7 bcn=0 [on:0 tx:0 rx:0 period:12] from screen [on:0 period:-1553102157] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=1.5, 0.0, 0.0  rx=1.3 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1553099143] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=1.5, 0.0, 0.0  rx=1.3 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1553099140] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1553096118] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-1553096108] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=0.9, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1553093089] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=0.9, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:11] from screen [on:0 period:-1553093078] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1553090056] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1553090053] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
,V/AlarmManager( 1030): ELAPSED_WAKEUP set : Alarm{540b9ab type 2 when 215877 android} when 215877
,D/sensors_hal_Time( 1030): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1030): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1030): tsOffsetIs: Apps: 217296829920; DSPS: 7261905; Offset : -4334108510
,E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1553087030] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-1553087020] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1030):  ConnectedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
E/WifiStateMachine( 1030):  L2ConnectedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
,E/WifiStateMachine( 1030):  ConnectModeState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
,E/WifiStateMachine( 1030):  DriverStartedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
E/WifiStateMachine( 1030):  SupplicantStartedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
E/WifiStateMachine( 1030):  DefaultState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=0.9, 0.0, 0.0  rx=0.9 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1553084008] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=0.9, 0.0, 0.0  rx=0.9 bcn=0 [on:0 tx:0 rx:0 period:13] from screen [on:0 period:-1553083995] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1553080974] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1553080971] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:-1553077943] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1553077940] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
,V/AlarmManager( 1030): ELAPSED_WAKEUP set : Alarm{3a635808 type 2 when 212278 android} when 212278
,V/AlarmManager( 1030): RTC_WAKEUP set : Alarm{ea001c6 type 0 when 1454440829176 com.android.vending} when 1454440829176
,V/SIM_STK ( 1030): Menu title from STK is T-Mobile
,V/GLSActivity( 2126): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2126): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 2126): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 2126): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 2126): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2126): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/Finsky  ( 6880): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 6880): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 6880): [1] 5.onFinished: Giving up after 6 failures.
,E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3005] from screen [on:0 period:-1553074915] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1553074912] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1553071885] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1553071882] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1553068861] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1553068858] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
,D/sensors_hal_Time( 1030): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1030): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1030): tsOffsetIs: Apps: 237298858975; DSPS: 7917331; Offset : -4334093824
,E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1553065834] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1553065831] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1553062808] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-1553062798] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1553059776] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1553059773] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
,V/AlarmManager( 1030): ELAPSED_WAKEUP set : Alarm{6a0d338 type 2 when 245900 android} when 245900
,I/BooksSync( 7597): Starting books sync
,D/BooksSync( 7597): started syncMyEbooks
,V/GLSActivity( 2126): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     ( 2126): Explicit concurrent mark sweep GC freed 48143(2MB) AllocSpace objects, 15(1927KB) LOS objects, 51% free, 30MB/62MB, paused 1.559ms total 45.625ms
,I/GLSUser ( 2126): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2126): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2126): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2126): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2126): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1030): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1030): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1030): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1030): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1030): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1411): onNotificationPosted
D/SmartCoverUpdateMonitor( 1411): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1411): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1411): handleNotificationPosted(true)
D/QuickCircle( 1411): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1411): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1411): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1411): post do just update job
D/LgeQuickCoverNotificationData( 1411): showAll3
D/LgeQuickCoverNotificationData( 1411): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1411): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1411): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1411): showNotificationWithSetupData: display=false
,D/LgeQuickCoverOverlayWindow( 1411): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1411): isNotificationForCurrentUser : true
W/GLSActivity( 2126): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2126): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2126): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2126): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2126): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2126): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2126): 	at android.os.Binder.execTransact(Binder.java:446)
D/LgeQuickCoverOverlayWindow( 1411): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1411): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1411): [native noti] inex =  2
,D/LgeQuickCoverNotificationData( 1411): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1411): updateNotificationData: count=3
E/BooksAccountManager( 7597): Authentication error
E/BooksAccountManager( 7597): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7597): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 7597): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 7597): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 7597): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 7597): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 7597): null auth token
D/QuickStatusbarLayout( 1411): Notification difference=198
D/QuickStatusbarLayout( 1411): child = android.widget.LinearLayout{183f0fdb V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,W/ApiaryClient( 7597): Error response from books API: {
W/ApiaryClient( 7597):  "error": {
W/ApiaryClient( 7597):   "errors": [
W/ApiaryClient( 7597):    {
W/ApiaryClient( 7597):     "domain": "global",
W/ApiaryClient( 7597):     "reason": "required",
W/ApiaryClient( 7597):     "message": "Login Required",
W/ApiaryClient( 7597):     "locationType": "header",
W/ApiaryClient( 7597):     "location": "Authorization"
W/ApiaryClient( 7597):    }
W/ApiaryClient( 7597):   ],
W/ApiaryClient( 7597):   "code": 401,
W/ApiaryClient( 7597):   "message": "Login Required"
W/ApiaryClient( 7597):  }
W/ApiaryClient( 7597): }
,W/ApiaryClient( 7597): errCount = 1: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7597): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=303886063549208150&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7597): Headers:
W/ApiaryClient( 7597): accept-encoding: [gzip]
W/ApiaryClient( 7597): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 7597): gdata-version: 2
,V/GLSActivity( 2126): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2126): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2126): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2126): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2126): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2126): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1030): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1030): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1030): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1030): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1030): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1411): onNotificationPosted
,D/SmartCoverUpdateMonitor( 1411): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1411): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1411): handleNotificationPosted(true)
D/QuickCircle( 1411): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1411): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1411): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1411): post do just update job
D/LgeQuickCoverNotificationData( 1411): showAll3
D/LgeQuickCoverNotificationData( 1411): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1411): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1411): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1411): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1411): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1411): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1411): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1411): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1411): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1411): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1411): updateNotificationData: count=3
W/GLSActivity( 2126): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2126): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2126): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2126): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2126): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2126): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2126): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 7597): Authentication error
E/BooksAccountManager( 7597): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7597): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 7597): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 7597): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 7597): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 7597): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 7597): null auth token
D/QuickStatusbarLayout( 1411): Notification difference=198
D/QuickStatusbarLayout( 1411): child = android.widget.LinearLayout{183f0fdb V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
W/ApiaryClient( 7597): Error response from books API: {
W/ApiaryClient( 7597):  "error": {
W/ApiaryClient( 7597):   "errors": [
W/ApiaryClient( 7597):    {
W/ApiaryClient( 7597):     "domain": "global",
W/ApiaryClient( 7597):     "reason": "required",
W/ApiaryClient( 7597):     "message": "Login Required",
W/ApiaryClient( 7597):     "locationType": "header",
W/ApiaryClient( 7597):     "location": "Authorization"
W/ApiaryClient( 7597):    }
W/ApiaryClient( 7597):   ],
W/ApiaryClient( 7597):   "code": 401,
W/ApiaryClient( 7597):   "message": "Login Required"
W/ApiaryClient( 7597):  }
W/ApiaryClient( 7597): }
,W/ApiaryClient( 7597): errCount = 2: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7597): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=303886063549208150&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7597): Headers:
W/ApiaryClient( 7597): accept-encoding: [gzip]
W/ApiaryClient( 7597): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 7597): gdata-version: 2
,E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1553056748] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:12] from screen [on:0 period:-1553056736] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
I/[SystemUI]LGPowerUI( 1472): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1472): On Skip Timer : true
,D/WifiController( 1030): battery changed pluggedType: 2
,D/LEDHandler( 1964): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1964): Battery Level Remaining: 100%
D/LEDHandler( 1964): Battery Temp: 285, mChargingStatus=5, mChargingStop=false
D/KeyguardUpdateMonitor( 1472): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 285
I/[SystemUI]LGPowerUI( 1472): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings( 1030): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1030): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/HeadsetStateMachine( 6053): Disconnected process message: 10, size: 0
I/[SystemUI]BatterySaverHandler( 1472): onReceive = android.intent.action.BATTERY_CHANGED
D/LGDMClient( 3984): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.intent.action.BATTERY_CHANGED
D/LGDMClient( 3984): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,V/GLSActivity( 2126): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/GLSUser ( 2126): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2126): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2126): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2126): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2126): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1030): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1030): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1030): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1030): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1030): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1411): onNotificationPosted
D/SmartCoverUpdateMonitor( 1411): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1411): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1411): handleNotificationPosted(true)
D/QuickCircle( 1411): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1411): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1411): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1411): post do just update job
D/LgeQuickCoverNotificationData( 1411): showAll3
D/LgeQuickCoverNotificationData( 1411): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1411): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1411): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1411): showNotificationWithSetupData: display=false
,D/LgeQuickCoverOverlayWindow( 1411): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1411): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1411): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1411): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1411): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1411): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1411): updateNotificationData: count=3
W/GLSActivity( 2126): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2126): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2126): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2126): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2126): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2126): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2126): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 7597): Authentication error
E/BooksAccountManager( 7597): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7597): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 7597): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 7597): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 7597): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 7597): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 7597): null auth token
D/QuickStatusbarLayout( 1411): Notification difference=198
D/QuickStatusbarLayout( 1411): child = android.widget.LinearLayout{183f0fdb V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,W/ApiaryClient( 7597): Error response from books API: {
W/ApiaryClient( 7597):  "error": {
W/ApiaryClient( 7597):   "errors": [
W/ApiaryClient( 7597):    {
W/ApiaryClient( 7597):     "domain": "global",
W/ApiaryClient( 7597):     "reason": "required",
W/ApiaryClient( 7597):     "message": "Login Required",
W/ApiaryClient( 7597):     "locationType": "header",
W/ApiaryClient( 7597):     "location": "Authorization"
W/ApiaryClient( 7597):    }
W/ApiaryClient( 7597):   ],
W/ApiaryClient( 7597):   "code": 401,
W/ApiaryClient( 7597):   "message": "Login Required"
W/ApiaryClient( 7597):  }
W/ApiaryClient( 7597): }
W/ApiaryClient( 7597): errCount = 3: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7597): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=303886063549208150&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7597): Headers:
W/ApiaryClient( 7597): accept-encoding: [gzip]
W/ApiaryClient( 7597): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 7597): gdata-version: 2
,E/BooksSync( 7597): Soft error: 
E/BooksSync( 7597): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 7597): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=303886063549208150&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 7597): Headers:
E/BooksSync( 7597): accept-encoding: [gzip]
E/BooksSync( 7597): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 7597): gdata-version: 2
E/BooksSync( 7597): 
E/BooksSync( 7597): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 7597): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 7597): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 7597): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 7597): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 7597): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 7597): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 7597): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 7597): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 7597): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 7597): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 7597): {
E/BooksSync( 7597):  "error": {
E/BooksSync( 7597):   "errors": [
E/BooksSync( 7597):    {
E/BooksSync( 7597):     "domain": "global",
E/BooksSync( 7597):     "reason": "required",
E/BooksSync( 7597):     "message": "Login Required",
E/BooksSync( 7597):     "locationType": "header",
E/BooksSync( 7597):     "location": "Authorization"
E/BooksSync( 7597):    }
E/BooksSync( 7597):   ],
E/BooksSync( 7597):   "code": 401,
E/BooksSync( 7597):   "message": "Login Required"
E/BooksSync( 7597):  }
E/BooksSync( 7597): }
E/BooksSync( 7597): 
E/BooksSync( 7597): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 7597): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 7597): 	... 8 more
,E/BooksSync( 7597): Sync error
E/BooksSync( 7597): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 7597): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=303886063549208150&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 7597): Headers:
E/BooksSync( 7597): accept-encoding: [gzip]
E/BooksSync( 7597): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 7597): gdata-version: 2
E/BooksSync( 7597): 
E/BooksSync( 7597): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 7597): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 7597): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 7597): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 7597): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 7597): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 7597): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 7597): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 7597): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 7597): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 7597): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 7597): {
E/BooksSync( 7597):  "error": {
E/BooksSync( 7597):   "errors": [
E/BooksSync( 7597):    {
E/BooksSync( 7597):     "domain": "global",
E/BooksSync( 7597):     "reason": "required",
E/BooksSync( 7597):     "message": "Login Required",
E/BooksSync( 7597):     "locationType": "header",
E/BooksSync( 7597):     "location": "Authorization"
E/BooksSync( 7597):    }
E/BooksSync( 7597):   ],
E/BooksSync( 7597):   "code": 401,
E/BooksSync( 7597):   "message": "Login Required"
E/BooksSync( 7597):  }
E/BooksSync( 7597): }
E/BooksSync( 7597): 
E/BooksSync( 7597): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 7597): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 7597): 	... 8 more
I/BooksSync( 7597): Finished books sync
D/SyncManager( 1030): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 217368, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=2.8, 0.0, 0.0  rx=2.8 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1553053713] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=2.8, 0.0, 0.0  rx=2.8 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1553053710] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
,I/[SystemUI]TimeTickManager( 1472): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1472): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1472): called onTimeUpdated()
,I/[SystemUI]Clock( 1472): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1472): called onTimeUpdated()
,I/[SystemUI]DateView( 1472): called onTimeUpdated()
I/[SystemUI]DateView( 1472): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1472): handleTimeUpdate
E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=2.4, 0.0, 0.0  rx=2.4 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1553050688] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=2.4, 0.0, 0.0  rx=2.4 bcn=0 [on:0 tx:0 rx:0 period:12] from screen [on:0 period:-1553050676] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=1.7, 0.0, 0.0  rx=1.7 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1553047655] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=1.7, 0.0, 0.0  rx=1.7 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1553047652] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
,D/sensors_hal_Time( 1030): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1030): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1030): tsOffsetIs: Apps: 257301015737; DSPS: 8572762; Offset : -4334103732
,E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=0.9, 0.0, 0.0  rx=0.9 bcn=0 [on:0 tx:0 rx:0 period:3000] from screen [on:0 period:-1553044629] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=0.9, 0.0, 0.0  rx=0.9 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-1553044619] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=3.9, 0.0, 0.0  rx=3.4 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1553041598] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=3.9, 0.0, 0.0  rx=3.4 bcn=0 [on:0 tx:0 rx:0 period:11] from screen [on:0 period:-1553041587] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=2.0, 0.0, 0.0  rx=1.7 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1553038562] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=2.0, 0.0, 0.0  rx=1.7 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1553038559] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=1.0, 0.0, 0.0  rx=0.9 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1553035541] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=1.0, 0.0, 0.0  rx=0.9 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1553035538] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1553032511] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:4] from screen [on:0 period:-1553032507] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=0.2, 0.0, 0.0  rx=0.2 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1553029479] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=0.2, 0.0, 0.0  rx=0.2 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-1553029469] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
D/PowerManagerServiceEx( 1030): acquireWakeLockInternal: lock=770300739, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1030
,V/AlarmManager( 1030): ELAPSED_WAKEUP set : Alarm{cff3d62 type 2 when 275948 android} when 275948
D/[Concierge]Service( 2607): onStartCommand(). Type : 9
,D/PowerManagerServiceEx( 1030): releaseWakeLockInternal: lock=770300739 [*alarm*], flags=0x0
,D/sensors_hal_Time( 1030): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1030): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1030): tsOffsetIs: Apps: 277303050887; DSPS: 9228189; Offset : -4334113234
,E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1553026447] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:4] from screen [on:0 period:-1553026443] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1553023417] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:4] from screen [on:0 period:-1553023413] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1553020388] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-1553020378] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=1.0, 0.0, 0.0  rx=1.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1553017357] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=1.0, 0.0, 0.0  rx=1.0 bcn=0 [on:0 tx:0 rx:0 period:12] from screen [on:0 period:-1553017345] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.5 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1553014324] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.5 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1553014321] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=0.3, 0.0, 0.0  rx=0.3 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1553011301] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=0.3, 0.0, 0.0  rx=0.3 bcn=0 [on:0 tx:0 rx:0 period:4] from screen [on:0 period:-1553011297] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3000] from screen [on:0 period:-1553008272] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1553008269] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
,D/sensors_hal_Time( 1030): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1030): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1030): tsOffsetIs: Apps: 297305183119; DSPS: 9883619; Offset : -4334117258
,E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1553005244] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1553005241] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1553002219] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-1553002209] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1552999189] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:13] from screen [on:0 period:-1552999176] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=1.0, 0.0, 0.0  rx=1.5 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1552996155] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=1.0, 0.0, 0.0  rx=1.5 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1552996152] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
,V/AlarmManager( 1030): ELAPSED_WAKEUP set : Alarm{292d2ef3 type 2 when 311226 android} when 311226
,I/BooksSync( 7597): Starting books sync
,D/BooksSync( 7597): started syncMyEbooks
,V/GLSActivity( 2126): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2126): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2126): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2126): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2126): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2126): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1030): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1030): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1030): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1030): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1030): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1411): onNotificationPosted
,D/SmartCoverUpdateMonitor( 1411): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1411): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1411): handleNotificationPosted(true)
D/QuickCircle( 1411): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1411): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1411): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1411): post do just update job
D/LgeQuickCoverNotificationData( 1411): showAll3
D/LgeQuickCoverNotificationData( 1411): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1411): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1411): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1411): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1411): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1411): isNotificationForCurrentUser : true
W/GLSActivity( 2126): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2126): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2126): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2126): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2126): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2126): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2126): 	at android.os.Binder.execTransact(Binder.java:446)
E/BooksAccountManager( 7597): Authentication error
E/BooksAccountManager( 7597): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7597): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 7597): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 7597): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 7597): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 7597): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 7597): null auth token
D/LgeQuickCoverOverlayWindow( 1411): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1411): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1411): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1411): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1411): updateNotificationData: count=3
,D/QuickStatusbarLayout( 1411): Notification difference=198
,D/QuickStatusbarLayout( 1411): child = android.widget.LinearLayout{183f0fdb V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
W/ApiaryClient( 7597): Error response from books API: {
W/ApiaryClient( 7597):  "error": {
W/ApiaryClient( 7597):   "errors": [
W/ApiaryClient( 7597):    {
W/ApiaryClient( 7597):     "domain": "global",
W/ApiaryClient( 7597):     "reason": "required",
W/ApiaryClient( 7597):     "message": "Login Required",
W/ApiaryClient( 7597):     "locationType": "header",
W/ApiaryClient( 7597):     "location": "Authorization"
W/ApiaryClient( 7597):    }
W/ApiaryClient( 7597):   ],
W/ApiaryClient( 7597):   "code": 401,
W/ApiaryClient( 7597):   "message": "Login Required"
W/ApiaryClient( 7597):  }
W/ApiaryClient( 7597): }
,W/ApiaryClient( 7597): errCount = 1: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7597): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=6163758574892024486&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7597): Headers:
W/ApiaryClient( 7597): accept-encoding: [gzip]
W/ApiaryClient( 7597): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 7597): gdata-version: 2
,I/[SystemUI]TimeTickManager( 1472): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1472): called onTimeUpdated()
,I/[SystemUI]KeyguardIndicationController( 1472): called onTimeUpdated()
I/[SystemUI]Clock( 1472): called onTimeUpdated()
I/LgeClockWidgetControlView( 1472): called onTimeUpdated()
,I/[SystemUI]DateView( 1472): called onTimeUpdated()
,I/[SystemUI]DateView( 1472): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1472): handleTimeUpdate
E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=1.5, 0.0, 0.0  rx=1.3 bcn=0 [on:0 tx:0 rx:0 period:3006] from screen [on:0 period:-1552993125] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=1.5, 0.0, 0.0  rx=1.3 bcn=0 [on:0 tx:0 rx:0 period:6] from screen [on:0 period:-1552993119] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
,V/GLSActivity( 2126): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2126): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2126): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2126): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2126): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2126): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1030): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1030): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1030): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1030): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1030): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
W/GLSActivity( 2126): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2126): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2126): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2126): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2126): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2126): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2126): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 7597): Authentication error
E/BooksAccountManager( 7597): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7597): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 7597): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 7597): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 7597): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 7597): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 7597): null auth token
W/ResourcesManager( 1411): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 1411): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,D/LgeQuickCoverNLService( 1411): onNotificationPosted
D/SmartCoverUpdateMonitor( 1411): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1411): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1411): handleNotificationPosted(true)
D/QuickCircle( 1411): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1411): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1411): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1411): post do just update job
D/LgeQuickCoverNotificationData( 1411): showAll3
D/LgeQuickCoverNotificationData( 1411): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1411): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1411): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1411): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1411): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1411): isNotificationForCurrentUser : true
W/ResourcesManager( 1411): Asset path '/system/framework/com.lge.systemui.jar' does not exist or contains no resources.
W/ResourcesManager( 1411): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,D/LgeQuickCoverOverlayWindow( 1411): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1411): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1411): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1411): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1411): updateNotificationData: count=3
D/QuickStatusbarLayout( 1411): Notification difference=198
D/QuickStatusbarLayout( 1411): child = android.widget.LinearLayout{183f0fdb V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,W/ApiaryClient( 7597): Error response from books API: {
W/ApiaryClient( 7597):  "error": {
W/ApiaryClient( 7597):   "errors": [
W/ApiaryClient( 7597):    {
W/ApiaryClient( 7597):     "domain": "global",
W/ApiaryClient( 7597):     "reason": "required",
W/ApiaryClient( 7597):     "message": "Login Required",
W/ApiaryClient( 7597):     "locationType": "header",
W/ApiaryClient( 7597):     "location": "Authorization"
W/ApiaryClient( 7597):    }
W/ApiaryClient( 7597):   ],
W/ApiaryClient( 7597):   "code": 401,
W/ApiaryClient( 7597):   "message": "Login Required"
W/ApiaryClient( 7597):  }
W/ApiaryClient( 7597): }
,W/ApiaryClient( 7597): errCount = 2: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7597): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=6163758574892024486&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7597): Headers:
W/ApiaryClient( 7597): accept-encoding: [gzip]
W/ApiaryClient( 7597): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 7597): gdata-version: 2
V/GLSActivity( 2126): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2126): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 2126): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2126): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2126): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2126): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1030): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1030): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1030): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1030): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1030): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1411): onNotificationPosted
,D/SmartCoverUpdateMonitor( 1411): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1411): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1411): handleNotificationPosted(true)
D/QuickCircle( 1411): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1411): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1411): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1411): post do just update job
D/LgeQuickCoverNotificationData( 1411): showAll3
D/LgeQuickCoverNotificationData( 1411): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1411): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1411): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1411): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1411): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1411): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1411): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1411): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1411): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1411): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1411): updateNotificationData: count=3
W/GLSActivity( 2126): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2126): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2126): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2126): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2126): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2126): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2126): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 7597): Authentication error
E/BooksAccountManager( 7597): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7597): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 7597): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 7597): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 7597): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 7597): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 7597): null auth token
D/QuickStatusbarLayout( 1411): Notification difference=198
D/QuickStatusbarLayout( 1411): child = android.widget.LinearLayout{183f0fdb V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
W/ApiaryClient( 7597): Error response from books API: {
W/ApiaryClient( 7597):  "error": {
W/ApiaryClient( 7597):   "errors": [
W/ApiaryClient( 7597):    {
W/ApiaryClient( 7597):     "domain": "global",
W/ApiaryClient( 7597):     "reason": "required",
W/ApiaryClient( 7597):     "message": "Login Required",
W/ApiaryClient( 7597):     "locationType": "header",
W/ApiaryClient( 7597):     "location": "Authorization"
W/ApiaryClient( 7597):    }
W/ApiaryClient( 7597):   ],
W/ApiaryClient( 7597):   "code": 401,
W/ApiaryClient( 7597):   "message": "Login Required"
W/ApiaryClient( 7597):  }
W/ApiaryClient( 7597): }
,W/ApiaryClient( 7597): errCount = 3: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7597): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=6163758574892024486&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7597): Headers:
W/ApiaryClient( 7597): accept-encoding: [gzip]
W/ApiaryClient( 7597): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 7597): gdata-version: 2
,E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=1.8, 0.0, 0.0  rx=1.6 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:-1552990109] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=1.8, 0.0, 0.0  rx=1.6 bcn=0 [on:0 tx:0 rx:0 period:11] from screen [on:0 period:-1552990098] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
,E/BooksSync( 7597): Soft error: 
E/BooksSync( 7597): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 7597): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=6163758574892024486&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 7597): Headers:
E/BooksSync( 7597): accept-encoding: [gzip]
E/BooksSync( 7597): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 7597): gdata-version: 2
E/BooksSync( 7597): 
E/BooksSync( 7597): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 7597): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 7597): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 7597): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 7597): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 7597): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 7597): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 7597): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 7597): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 7597): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 7597): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 7597): {
E/BooksSync( 7597):  "error": {
E/BooksSync( 7597):   "errors": [
E/BooksSync( 7597):    {
E/BooksSync( 7597):     "domain": "global",
E/BooksSync( 7597):     "reason": "required",
E/BooksSync( 7597):     "message": "Login Required",
E/BooksSync( 7597):     "locationType": "header",
E/BooksSync( 7597):     "location": "Authorization"
E/BooksSync( 7597):    }
E/BooksSync( 7597):   ],
E/BooksSync( 7597):   "code": 401,
E/BooksSync( 7597):   "message": "Login Required"
E/BooksSync( 7597):  }
E/BooksSync( 7597): }
E/BooksSync( 7597): 
E/BooksSync( 7597): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 7597): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 7597): 	... 8 more
,E/BooksSync( 7597): Sync error
E/BooksSync( 7597): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 7597): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=6163758574892024486&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 7597): Headers:
E/BooksSync( 7597): accept-encoding: [gzip]
E/BooksSync( 7597): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 7597): gdata-version: 2
E/BooksSync( 7597): 
E/BooksSync( 7597): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 7597): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 7597): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 7597): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 7597): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 7597): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 7597): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 7597): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 7597): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 7597): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 7597): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 7597): {
E/BooksSync( 7597):  "error": {
E/BooksSync( 7597):   "errors": [
E/BooksSync( 7597):    {
E/BooksSync( 7597):     "domain": "global",
E/BooksSync( 7597):     "reason": "required",
E/BooksSync( 7597):     "message": "Login Required",
E/BooksSync( 7597):     "locationType": "header",
E/BooksSync( 7597):     "location": "Authorization"
E/BooksSync( 7597):    }
E/BooksSync( 7597):   ],
E/BooksSync( 7597):   "code": 401,
E/BooksSync( 7597):   "message": "Login Required"
E/BooksSync( 7597):  }
E/BooksSync( 7597): }
E/BooksSync( 7597): 
E/BooksSync( 7597): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 7597): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 7597): 	... 8 more
I/BooksSync( 7597): Finished books sync
D/SyncManager( 1030): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 311226, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/sensors_hal_Time( 1030): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1030): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1030): tsOffsetIs: Apps: 317307012278; DSPS: 10539038; Offset : -4334088506
,E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=2.9, 0.0, 0.0  rx=2.8 bcn=0 [on:0 tx:0 rx:0 period:3000] from screen [on:0 period:-1552987078] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=2.9, 0.0, 0.0  rx=2.8 bcn=0 [on:0 tx:0 rx:0 period:9] from screen [on:0 period:-1552987069] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=1.4, 0.0, 0.0  rx=1.4 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1552984048] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=1.4, 0.0, 0.0  rx=1.4 bcn=0 [on:0 tx:0 rx:0 period:13] from screen [on:0 period:-1552984035] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1552981013] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1552981010] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:-1552977986] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1552977983] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=0.2, 0.0, 0.0  rx=0.2 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1552974956] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=0.2, 0.0, 0.0  rx=0.2 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1552974953] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1552971926] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1552971923] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1552968899] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-1552968889] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
,D/sensors_hal_Time( 1030): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1030): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1030): tsOffsetIs: Apps: 337308865968; DSPS: 11194459; Offset : -4334096570
,E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=1.0, 0.0, 0.0  rx=0.5 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1552965869] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=1.0, 0.0, 0.0  rx=0.5 bcn=0 [on:0 tx:0 rx:0 period:9] from screen [on:0 period:-1552965860] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
D/PowerManagerServiceEx( 1030): acquireWakeLockInternal: lock=770300739, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1030
,V/AlarmManager( 1030): ELAPSED_WAKEUP set : Alarm{20b79441 type 2 when 341258 android} when 341258
D/[Concierge]Service( 2607): onStartCommand(). Type : 9
,D/PowerManagerServiceEx( 1030): releaseWakeLockInternal: lock=770300739 [*alarm*], flags=0x0
,E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.3 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1552962839] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.3 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-1552962829] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=0.3, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1552959809] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=0.3, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:14] from screen [on:0 period:-1552959795] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1552956783] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1552956780] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
,I/ActivityManager( 1030): Killing 6954:com.google.android.gms.wearable/u0a5 (adj 15): empty #17
,W/libprocessgroup( 1030): failed to open /acct/uid_10005/pid_6954/cgroup.procs: No such file or directory
,E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1552953754] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1552953751] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:-1552950729] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:9] from screen [on:0 period:-1552950720] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1552947699] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:12] from screen [on:0 period:-1552947687] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
,D/sensors_hal_Time( 1030): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1030): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1030): tsOffsetIs: Apps: 357310734763; DSPS: 11849880; Offset : -4334089217
,E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1552944667] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:9] from screen [on:0 period:-1552944658] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=1.0, 0.0, 0.0  rx=0.5 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1552941638] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=1.0, 0.0, 0.0  rx=0.5 bcn=0 [on:0 tx:0 rx:0 period:12] from screen [on:0 period:-1552941626] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.3 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1552938604] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.3 bcn=0 [on:0 tx:0 rx:0 period:4] from screen [on:0 period:-1552938600] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=2.8, 0.0, 0.0  rx=2.6 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1552935580] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=2.8, 0.0, 0.0  rx=2.6 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1552935577] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
D/PowerManagerServiceEx( 1030): acquireWakeLockInternal: lock=770300739, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1030
,D/[Concierge]Service( 2607): onStartCommand(). Type : 9
,I/[SystemUI]TimeTickManager( 1472): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1472): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1472): called onTimeUpdated()
I/[SystemUI]Clock( 1472): called onTimeUpdated()
I/LgeClockWidgetControlView( 1472): called onTimeUpdated()
I/[SystemUI]DateView( 1472): called onTimeUpdated()
I/[SystemUI]DateView( 1472): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1472): handleTimeUpdate
D/PowerManagerServiceEx( 1030): releaseWakeLockInternal: lock=770300739 [*alarm*], flags=0x0
,E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=2.4, 0.0, 0.0  rx=2.3 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1552932550] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=2.4, 0.0, 0.0  rx=2.3 bcn=0 [on:0 tx:0 rx:0 period:2] from screen [on:0 period:-1552932548] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=1.2, 0.0, 0.0  rx=1.2 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:-1552929525] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=1.2, 0.0, 0.0  rx=1.2 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1552929522] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
,D/sensors_hal_Time( 1030): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1030): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1030): tsOffsetIs: Apps: 377312838349; DSPS: 12505309; Offset : -4334091396
,E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=0.6, 0.0, 0.0  rx=0.6 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1552926496] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=0.6, 0.0, 0.0  rx=0.6 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1552926493] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=3.3, 0.0, 0.0  rx=3.3 bcn=0 [on:0 tx:0 rx:0 period:3000] from screen [on:0 period:-1552923469] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=3.3, 0.0, 0.0  rx=3.3 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-1552923459] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=1.6, 0.0, 0.0  rx=1.6 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1552920439] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=1.6, 0.0, 0.0  rx=1.6 bcn=0 [on:0 tx:0 rx:0 period:13] from screen [on:0 period:-1552920426] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=1.8, 0.0, 0.0  rx=1.3 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1552917404] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=1.8, 0.0, 0.0  rx=1.3 bcn=0 [on:0 tx:0 rx:0 period:4] from screen [on:0 period:-1552917400] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=0.9, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3005] from screen [on:0 period:-1552914375] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=0.9, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:11] from screen [on:0 period:-1552914364] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.3 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1552911343] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.3 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1552911340] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=0.2, 0.0, 0.0  rx=0.2 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1552908314] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=0.2, 0.0, 0.0  rx=0.2 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1552908311] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
,D/sensors_hal_Time( 1030): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1030): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1030): tsOffsetIs: Apps: 397314881154; DSPS: 13160736; Offset : -4334093139
,E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1552905284] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1552905281] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1552902255] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1552902252] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1552899225] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1552899222] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:-1552896194] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1552896191] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=1.0, 0.0, 0.0  rx=0.5 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:-1552893171] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=1.0, 0.0, 0.0  rx=0.5 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1552893168] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.3 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1552890143] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.3 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1552890140] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
,D/sensors_hal_Time( 1030): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1030): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1030): tsOffsetIs: Apps: 417316818125; DSPS: 13816160; Offset : -4334109475
,E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=0.3, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1552887115] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=0.3, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1552887112] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1552884085] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1552884082] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1552881055] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1552881052] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=4.5, 0.0, 0.0  rx=6.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1552878032] gl rssi=-63 ag=0 hr ticks 0,0,0 ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=4.5, 0.0, 0.0  rx=6.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1552878029] gl rssi=-63 ag=0 hr ticks 0,0,0 ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=2.3, 0.0, 0.0  rx=3.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1552875004] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=2.3, 0.0, 0.0  rx=3.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1552875001] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
,I/[SystemUI]TimeTickManager( 1472): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1472): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1472): called onTimeUpdated()
,I/[SystemUI]Clock( 1472): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1472): called onTimeUpdated()
,I/[SystemUI]DateView( 1472): called onTimeUpdated()
,I/[SystemUI]DateView( 1472): called onTimeUpdated()
,D/KeyguardUpdateMonitor( 1472): handleTimeUpdate
,V/GLSActivity( 2126): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     ( 1030): Explicit concurrent mark sweep GC freed 93090(4MB) AllocSpace objects, 10(1056KB) LOS objects, 33% free, 44MB/66MB, paused 2.294ms total 185.981ms
,I/GLSUser ( 2126): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 2126): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2126): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2126): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2126): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1030): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
V/NotificationService( 1030): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1030): LED remove() : mLights=0|com.google.android.gms|1|null|10005
,D/NotificationServiceEx( 1030): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1030): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
W/GLSActivity( 2126): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2126): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2126): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2126): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2126): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2126): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2126): 	at android.os.Binder.execTransact(Binder.java:446)
E/PlayEventLogger( 6880): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 6880): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 6880): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/PlayEventLogger( 6880): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 6880): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/PlayEventLogger( 6880): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 6880): 	at android.os.Binder.execTransact(Binder.java:446)
D/LgeQuickCoverNLService( 1411): onNotificationPosted
D/SmartCoverUpdateMonitor( 1411): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1411): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1411): handleNotificationPosted(true)
D/QuickCircle( 1411): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1411): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1411): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1411): post do just update job
D/LgeQuickCoverNotificationData( 1411): showAll3
D/LgeQuickCoverNotificationData( 1411): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1411): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1411): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1411): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1411): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1411): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1411): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1411): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1411): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1411): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1411): updateNotificationData: count=3
,D/QuickStatusbarLayout( 1411): Notification difference=198
D/QuickStatusbarLayout( 1411): child = android.widget.LinearLayout{183f0fdb V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
W/System  ( 6880): Ignoring header User-Agent because its value was null.
,D/libc-netbsd(  308): default dns: query_ipv6=0, query_ipv4=1
,D/libc-netbsd(  308): res_queryN name = play.googleapis.com, class = 1, type = 1
D/libc-netbsd(  308): res_queryN name = play.googleapis.com succeed
,E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=1.1, 0.0, 0.0  rx=1.5 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1552871975] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=1.1, 0.0, 0.0  rx=1.5 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1552871972] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=6.1, 0.0, 0.0  rx=5.3 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1552868952] gl rssi=-63 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=6.1, 0.0, 0.0  rx=5.3 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1552868949] gl rssi=-63 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
,D/sensors_hal_Time( 1030): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1030): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1030): tsOffsetIs: Apps: 437318402753; DSPS: 14471572; Offset : -4334111840
D/PowerManagerServiceEx( 1030): acquireWakeLockInternal: lock=770300739, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1030
,V/AlarmManager( 1030): ELAPSED_WAKEUP set : Alarm{2e71eb3b type 2 when 437907 android} when 437907
D/[Concierge]Service( 2607): onStartCommand(). Type : 9
,D/PowerManagerServiceEx( 1030): releaseWakeLockInternal: lock=770300739 [*alarm*], flags=0x0
,I/BooksSync( 7597): Starting books sync
,D/BooksSync( 7597): started syncMyEbooks
,V/GLSActivity( 2126): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2126): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 2126): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2126): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2126): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2126): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1030): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1030): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1030): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1030): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1030): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1411): onNotificationPosted
,W/GLSActivity( 2126): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2126): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2126): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2126): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2126): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2126): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2126): 	at android.os.Binder.execTransact(Binder.java:446)
D/SmartCoverUpdateMonitor( 1411): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1411): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1411): handleNotificationPosted(true)
D/QuickCircle( 1411): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1411): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
,D/LgeQuickCoverNotificationData( 1411): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1411): post do just update job
D/LgeQuickCoverNotificationData( 1411): showAll3
D/LgeQuickCoverNotificationData( 1411): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1411): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1411): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1411): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1411): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1411): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1411): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1411): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1411): [native noti] inex =  2
E/BooksAccountManager( 7597): Authentication error
E/BooksAccountManager( 7597): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7597): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 7597): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 7597): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 7597): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 7597): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 7597): null auth token
D/LgeQuickCoverNotificationData( 1411): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1411): updateNotificationData: count=3
D/QuickStatusbarLayout( 1411): Notification difference=198
D/QuickStatusbarLayout( 1411): child = android.widget.LinearLayout{183f0fdb V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,W/ApiaryClient( 7597): Error response from books API: {
W/ApiaryClient( 7597):  "error": {
W/ApiaryClient( 7597):   "errors": [
W/ApiaryClient( 7597):    {
W/ApiaryClient( 7597):     "domain": "global",
W/ApiaryClient( 7597):     "reason": "required",
W/ApiaryClient( 7597):     "message": "Login Required",
W/ApiaryClient( 7597):     "locationType": "header",
W/ApiaryClient( 7597):     "location": "Authorization"
W/ApiaryClient( 7597):    }
W/ApiaryClient( 7597):   ],
W/ApiaryClient( 7597):   "code": 401,
W/ApiaryClient( 7597):   "message": "Login Required"
W/ApiaryClient( 7597):  }
W/ApiaryClient( 7597): }
,W/ApiaryClient( 7597): errCount = 1: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized,
W/ApiaryClient( 7597): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=8493256757977319015&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app,
W/ApiaryClient( 7597): Headers:
W/ApiaryClient( 7597): accept-encoding: [gzip]
W/ApiaryClient( 7597): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 7597): gdata-version: 2
,E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=4.0, 0.0, 0.0  rx=3.1 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1552865928] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=4.0, 0.0, 0.0  rx=3.1 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-1552865918] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
V/GLSActivity( 2126): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2126): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2126): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2126): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2126): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2126): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1030): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1030): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1030): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1030): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1030): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1411): onNotificationPosted
,D/SmartCoverUpdateMonitor( 1411): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1411): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1411): handleNotificationPosted(true)
D/QuickCircle( 1411): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1411): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1411): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1411): post do just update job
D/LgeQuickCoverNotificationData( 1411): showAll3
D/LgeQuickCoverNotificationData( 1411): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1411): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1411): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1411): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1411): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1411): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1411): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1411): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1411): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1411): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1411): updateNotificationData: count=3
W/GLSActivity( 2126): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2126): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2126): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2126): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2126): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2126): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2126): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 7597): Authentication error
E/BooksAccountManager( 7597): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7597): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 7597): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 7597): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 7597): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 7597): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 7597): null auth token
D/QuickStatusbarLayout( 1411): Notification difference=198
D/QuickStatusbarLayout( 1411): child = android.widget.LinearLayout{183f0fdb V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,W/ApiaryClient( 7597): Error response from books API: {
W/ApiaryClient( 7597):  "error": {
W/ApiaryClient( 7597):   "errors": [
W/ApiaryClient( 7597):    {
W/ApiaryClient( 7597):     "domain": "global",
W/ApiaryClient( 7597):     "reason": "required",
W/ApiaryClient( 7597):     "message": "Login Required",
W/ApiaryClient( 7597):     "locationType": "header",
W/ApiaryClient( 7597):     "location": "Authorization"
W/ApiaryClient( 7597):    }
W/ApiaryClient( 7597):   ],
W/ApiaryClient( 7597):   "code": 401,
W/ApiaryClient( 7597):   "message": "Login Required"
W/ApiaryClient( 7597):  }
W/ApiaryClient( 7597): }
,W/ApiaryClient( 7597): errCount = 2: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7597): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=8493256757977319015&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7597): Headers:
W/ApiaryClient( 7597): accept-encoding: [gzip]
W/ApiaryClient( 7597): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 7597): gdata-version: 2
,V/GLSActivity( 2126): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2126): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2126): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2126): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2126): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2126): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1030): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1030): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1030): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1030): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1030): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1411): onNotificationPosted
D/SmartCoverUpdateMonitor( 1411): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1411): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1411): handleNotificationPosted(true)
D/QuickCircle( 1411): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1411): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1411): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1411): post do just update job
D/LgeQuickCoverNotificationData( 1411): showAll3
D/LgeQuickCoverNotificationData( 1411): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1411): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1411): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1411): showNotificationWithSetupData: display=false
,D/LgeQuickCoverOverlayWindow( 1411): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1411): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1411): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1411): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1411): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1411): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1411): updateNotificationData: count=3
W/GLSActivity( 2126): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2126): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2126): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2126): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2126): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2126): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2126): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 7597): Authentication error
E/BooksAccountManager( 7597): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7597): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 7597): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 7597): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 7597): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 7597): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 7597): null auth token
D/QuickStatusbarLayout( 1411): Notification difference=198
D/QuickStatusbarLayout( 1411): child = android.widget.LinearLayout{183f0fdb V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
W/ApiaryClient( 7597): Error response from books API: {
W/ApiaryClient( 7597):  "error": {
W/ApiaryClient( 7597):   "errors": [
W/ApiaryClient( 7597):    {
W/ApiaryClient( 7597):     "domain": "global",
W/ApiaryClient( 7597):     "reason": "required",
W/ApiaryClient( 7597):     "message": "Login Required",
W/ApiaryClient( 7597):     "locationType": "header",
W/ApiaryClient( 7597):     "location": "Authorization"
W/ApiaryClient( 7597):    }
W/ApiaryClient( 7597):   ],
W/ApiaryClient( 7597):   "code": 401,
W/ApiaryClient( 7597):   "message": "Login Required"
W/ApiaryClient( 7597):  }
W/ApiaryClient( 7597): }
,W/ApiaryClient( 7597): errCount = 3: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7597): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=8493256757977319015&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7597): Headers:
W/ApiaryClient( 7597): accept-encoding: [gzip]
W/ApiaryClient( 7597): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 7597): gdata-version: 2
,E/BooksSync( 7597): Soft error: 
E/BooksSync( 7597): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 7597): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=8493256757977319015&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 7597): Headers:
E/BooksSync( 7597): accept-encoding: [gzip]
E/BooksSync( 7597): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 7597): gdata-version: 2
E/BooksSync( 7597): 
E/BooksSync( 7597): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 7597): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 7597): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 7597): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 7597): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 7597): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 7597): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 7597): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 7597): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 7597): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 7597): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 7597): {
E/BooksSync( 7597):  "error": {
E/BooksSync( 7597):   "errors": [
E/BooksSync( 7597):    {
E/BooksSync( 7597):     "domain": "global",
E/BooksSync( 7597):     "reason": "required",
E/BooksSync( 7597):     "message": "Login Required",
E/BooksSync( 7597):     "locationType": "header",
E/BooksSync( 7597):     "location": "Authorization"
E/BooksSync( 7597):    }
E/BooksSync( 7597):   ],
E/BooksSync( 7597):   "code": 401,
E/BooksSync( 7597):   "message": "Login Required"
E/BooksSync( 7597):  }
E/BooksSync( 7597): }
E/BooksSync( 7597): 
E/BooksSync( 7597): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 7597): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 7597): 	... 8 more
,E/BooksSync( 7597): Sync error
E/BooksSync( 7597): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 7597): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=8493256757977319015&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 7597): Headers:
E/BooksSync( 7597): accept-encoding: [gzip]
E/BooksSync( 7597): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 7597): gdata-version: 2
E/BooksSync( 7597): 
E/BooksSync( 7597): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 7597): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 7597): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 7597): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 7597): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 7597): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 7597): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 7597): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 7597): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 7597): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 7597): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 7597): {
E/BooksSync( 7597):  "error": {
E/BooksSync( 7597):   "errors": [
E/BooksSync( 7597):    {
E/BooksSync( 7597):     "domain": "global",
E/BooksSync( 7597):     "reason": "required",
E/BooksSync( 7597):     "message": "Login Required",
E/BooksSync( 7597):     "locationType": "header",
E/BooksSync( 7597):     "location": "Authorization"
E/BooksSync( 7597):    }
E/BooksSync( 7597):   ],
E/BooksSync( 7597):   "code": 401,
E/BooksSync( 7597):   "message": "Login Required"
E/BooksSync( 7597):  }
E/BooksSync( 7597): }
E/BooksSync( 7597): 
E/BooksSync( 7597): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 7597): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 7597): 	... 8 more
I/BooksSync( 7597): Finished books sync
D/SyncManager( 1030): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 437907, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=3.0, 0.0, 0.0  rx=2.6 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:-1552862895] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=3.0, 0.0, 0.0  rx=2.6 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-1552862885] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=3.5, 0.0, 0.0  rx=3.3 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1552859870] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=3.5, 0.0, 0.0  rx=3.3 bcn=0 [on:0 tx:0 rx:0 period:11] from screen [on:0 period:-1552859859] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=1.8, 0.0, 0.0  rx=1.6 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1552856837] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=1.8, 0.0, 0.0  rx=1.6 bcn=0 [on:0 tx:0 rx:0 period:22] from screen [on:0 period:-1552856815] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=0.9, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1552853794] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=0.9, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1552853791] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3000] from screen [on:0 period:-1552850766] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1552850763] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=0.2, 0.0, 0.0  rx=0.2 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1552847738] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=0.2, 0.0, 0.0  rx=0.2 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-1552847728] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
,D/sensors_hal_Time( 1030): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1030): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1030): tsOffsetIs: Apps: 457321747798; DSPS: 15127041; Offset : -4334093002
,E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1552844706] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1552844703] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=1.1, 0.0, 0.0  rx=0.6 bcn=0 [on:0 tx:0 rx:0 period:3000] from screen [on:0 period:-1552841680] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=1.1, 0.0, 0.0  rx=0.6 bcn=0 [on:0 tx:0 rx:0 period:9] from screen [on:0 period:-1552841671] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.3 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1552838650] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.3 bcn=0 [on:0 tx:0 rx:0 period:12] from screen [on:0 period:-1552838638] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
,V/AlarmManager( 1030): ELAPSED_WAKEUP set : Alarm{2184eecd type 2 when 467991 android} when 467991
,E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=0.3, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1552835617] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=0.3, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:4] from screen [on:0 period:-1552835613] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1552832586] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1552832583] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1552829554] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1552829551] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
,D/sensors_hal_Time( 1030): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1030): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1030): tsOffsetIs: Apps: 477323629405; DSPS: 15782463; Offset : -4334103589
,E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1552826525] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1552826522] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1552823499] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:9] from screen [on:0 period:-1552823490] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1552820469] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:12] from screen [on:0 period:-1552820457] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=1.0, 0.0, 0.0  rx=0.5 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1552817435] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=1.0, 0.0, 0.0  rx=0.5 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1552817432] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.3 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1552814405] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.3 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1552814402] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
,I/[SystemUI]TimeTickManager( 1472): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1472): called onTimeUpdated()
,I/[SystemUI]KeyguardIndicationController( 1472): called onTimeUpdated()
,I/[SystemUI]Clock( 1472): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1472): called onTimeUpdated()
,I/[SystemUI]DateView( 1472): called onTimeUpdated()
,I/[SystemUI]DateView( 1472): called onTimeUpdated()
,D/KeyguardUpdateMonitor( 1472): handleTimeUpdate
,E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=0.3, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1552811375] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=0.3, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1552811372] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1552808344] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1552808341] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
,D/sensors_hal_Time( 1030): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1030): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1030): tsOffsetIs: Apps: 497325469866; DSPS: 16437883; Offset : -4334094131
,E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3005] from screen [on:0 period:-1552805316] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1552805313] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1552802288] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:11] from screen [on:0 period:-1552802277] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1552799255] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1552799252] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3000] from screen [on:0 period:-1552796228] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-1552796218] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=1.0, 0.0, 0.0  rx=0.5 bcn=0 [on:0 tx:0 rx:0 period:3000] from screen [on:0 period:-1552793206] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=1.0, 0.0, 0.0  rx=0.5 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-1552793205] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.3 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1552790186] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.3 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1552790183] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
,D/sensors_hal_Time( 1030): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1030): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1030): tsOffsetIs: Apps: 517327581681; DSPS: 17093312; Offset : -4334088055
,E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=0.3, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1552787156] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=0.3, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1552787153] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
,I/wpa_supplicant( 6108): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=0
,D/WifiMonitor( 1030): Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=0]
E/WifiMonitor( 1030): WifiMonitor:wlan0 cnt=45 dispatchEvent: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=0
E/WifiMonitor( 1030): handleEvent 2  CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=0
D/WifiMonitor( 1030): handleNetworkStateChange: Could not parse disconnect string
E/WifiMonitor( 1030): WifiMonitor notify network disconnect: null reason=0
E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3007] from screen [on:0 period:-1552784121] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-1552784120] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
D/Tethering( 1030): InitialState.processMessage what=4
D/WifiMonitor( 1030): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1030): WifiMonitor:wlan0 cnt=46 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/Tethering( 1030): sendTetherStateChangedBroadcast 0, 0, 0
,D/ConnectivityService( 1030): updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 50
D/ConnectivityService( 1030): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1030):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService( 1030):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1030):     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
D/ConnectivityService( 1030): Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
D/ConnectivityService( 1030): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1030):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1030):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1030): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
,D/ConnectivityManager.CallbackHandler( 1472): CM callback handler got msg 524290
D/ConnectivityService( 1030): sending new Min Network Score(50): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/TelephonyNetworkFactory-1( 1866): new score 50 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/TelephonyNetworkFactory-1( 1866):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
E/WifiStateMachine( 1030):  ConnectedState NETWORK_DISCONNECTION_EVENT nid=0 reason=0 lastbssid=c0:ff:d4:d3:aa:48 freq=2412 rssi=-127 rt=520751
E/WifiStateMachine( 1030):  L2ConnectedState NETWORK_DISCONNECTION_EVENT nid=0 reason=0 lastbssid=c0:ff:d4:d3:aa:48 freq=2412 rssi=-127 rt=520751
E/WifiStateMachine( 1030):  ConnectModeState NETWORK_DISCONNECTION_EVENT nid=0 reason=0 lastbssid=c0:ff:d4:d3:aa:48 freq=2412 rssi=-127 rt=520751
E/WifiConfigStore( 1030): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/WifiNative-wlan0( 1030): doBoolean: SET_NETWORK 0 bssid any
D/WifiNative-wlan0( 1030): SET_NETWORK 0 bssid any: returned true
D/WifiNative-wlan0( 1030): doBoolean: SAVE_CONFIG
D/UsbSettingsReceiver( 7148): [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
D/UsbSettingsReceiver( 7148): [AUTORUN] sys.usb.config = ptp_only,adb
D/UsbSettingsReceiver( 7148): [AUTORUN] sys.usb.state = ptp_only,adb
D/UsbSettingsReceiver( 7148): [AUTORUN] persist.sys.usb.config = ptp_only,adb
,D/UsbSettingsReceiver( 7148): [AUTORUN] onReceive() : app userid = 0, current userid = 0
D/WifiNative-wlan0( 1030): SAVE_CONFIG: returned true
D/WifiNative-wlan0( 1030): doBoolean: DRIVER BTCOEXMODE 2
I/wpa_supplicant( 6108): wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
D/LGWifiP2pService( 1030): InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1030): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0( 1030): DRIVER BTCOEXMODE 2: returned true
D/WifiNative-wlan0( 1030): doBoolean: SET ps 1
D/WifiNative-wlan0( 1030): SET ps 1: returned true
D/CommandListener(  308): Clearing all IP addresses on wlan0
D/DhcpStateMachine( 1030): RunningState{ when=-8ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
,V/NativeCrypto( 2126): Read error: ssl=0xaa6d0600: I/O error during system call, Connection timed out
,D/WifiMonitor( 1030): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
E/WifiMonitor( 1030): WifiMonitor:wlan0 cnt=47 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
V/NativeCrypto( 2126): SSL shutdown failed: ssl=0xaa6d0600: I/O error during system call, Broken pipe
I/wpa_supplicant( 6108): wlan0: CTRL-EVENT-SCAN-STARTED 
,D/WifiMonitor( 1030): Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1030): WifiMonitor:wlan0 cnt=48 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1030): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1030): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
D/ConnectivityService( 1030): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
D/ConnectivityService( 1030): NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 2
D/WifiHS20( 1030): hidePasspointNotification off =false
,I/StatusBar.NetworkController( 1472): networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1472): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1472): refreshViews: Data not connected!! Set no data type icon / Roaming
V/WfdStateTracker( 1964): handleWifiStateChangedEvent: 0
W/Settings( 1030): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1030): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1030): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
E/WifiStateMachine( 1030): WifiStateMachine: Leaving Connected state
I/jxcore-log( 5996): Toggling radios to false
I/jxcore-log( 5996): 
D/WifiHS20( 1030): hidePasspointNotification off =false
W/Settings( 1030): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1030): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1030): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
,E/WifiStateMachine( 1030):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 46 0 rt=520889  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: DISCONNECTED
E/WifiStateMachine( 1030):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 46 0 rt=520890  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: DISCONNECTED
E/WifiStateMachine( 1030):  DisconnectedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1030):  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1030):  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1030):  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1030):  DefaultState CMD_TETHER_STATE_CHANGE 0 0
D/WIFI    ( 1030): new score 50 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    ( 1030):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
E/WifiStateMachine( 1030):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 47 0 rt=520893  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
E/WifiStateMachine( 1030):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 47 0 rt=520896  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
D/WifiNetworkAgent( 1030): NetworkAgent: NetworkAgent channel lost
E/WifiStateMachine( 1030):  DisconnectedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1030):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1030):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1030):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1030):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1030):  DisconnectedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1030):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1030):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1030):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1030):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
,D/UsbSettingsControl( 7148): [AUTORUN] getUsbConnected() : connected=true
D/UsbSettingsReceiver( 7148): [AUTORUN] onReceive() : availableList=[]
D/UsbSettingsReceiver( 7148): [AUTORUN] onReceive() : activeList=[]
D/UsbSettingsReceiver( 7148): [AUTORUN] onReceive() : errorList=[]
D/UsbSettingsControl( 7148): [AUTORUN] isAutorunTimer() : mAutorunChanging=false
D/UsbSettingsControl( 7148): [AUTORUN] setTetherStatus() : status=false
D/BluetoothManagerService( 1030): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1030): disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@5ea5382 mBinding = false
D/ConnectivityService( 1030): Default network via Wi-Fi disconnect. stop DSQN
D/DSQN    ( 1030): disableDataServiceNotify
D/DSQN    ( 1030): stop dsqn bin
D/WifiHS20( 1030): hidePasspointNotification off =false
D/ConnectivityService( 1030): reportBadNetwork(NetworkAgentInfo [WIFI () - 101]) by 10005
W/Settings( 1030): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1030): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1030): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1030): ValidatedState{ when=0 what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
W/Settings( 1030): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1030): DefaultState{ when=-1ms what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
W/Settings( 1030): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1030): Forcing reevaluation
D/WifiOffDelayIfNotUsed( 1030): NETWORK_STATE_CHANGED_ACTION [SCANNING]
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1030): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiServerServiceExt( 1030): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1030): setSupplicantStateSCANNING
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1030): Checking http://clients3.google.com/generate_204 on <unknown ssid>
I/StatusBar.NetworkController( 1472): networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1472): mWifiConnected = false, mWifiLevel = 0
D/ConnectivityService( 1030): notifyType LOST for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1030):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1030):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/libc-netbsd(  308): default dns: query_ipv6=0, query_ipv4=0
D/ConnectivityService( 1030): sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
D/DSQN    ( 1030): DNSproblemNotiEnabled is disabled ignore DNS fail CB
,D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1030): Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
D/LocationManagerService( 1030): getAllProviders()=[passive, gps, network]
D/Ulp_jni ( 1030): JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 1,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
D/Ulp_jni ( 1030): JNI:system_update. Event-4
D/BluetoothManagerService( 1030): Message: 2
D/BluetoothManagerService( 1030): Sending off request.
D/LGBluetoothServiceAdapter( 6053): [BTUI] Precleanup
D/Nat464Xlat( 1030): requiresClat: netType=1, connected=false, hasIPv4Address=true, hasInternetCapability=true
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1030): EvaluatingState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1030): DefaultState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1030): Disconnected - quitting
D/ConnectivityManager.CallbackHandler( 1472): CM callback handler got msg 524292
D/StatusBar.NetworkController( 1472): refreshViews: Data not connected!! Set no data type icon / Roaming
D/WifiServiceImplEx( 1030): setWifiEnabled: false pid=5996, uid=10311, package= com.test.thalitest, App Lable : ThaliTest
D/WifiService( 1030): setWifiEnabled: false pid=5996, uid=10311
E/WifiService( 1030): Invoking mWifiStateMachine.setWifiEnabled
D/BluetoothAdapterState( 6053): CURRENT_STATE=ON, MESSAGE = USER_TURN_OFF
D/BluetoothAdapterProperties( 6053): Setting state to 13
I/BluetoothAdapterState( 6053): Bluetooth adapter state changed: 12-> 13
D/BluetoothAdapterProperties( 6053): onBluetoothDisable()
I/BluetoothAdapterState( 6053): Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
I/StatusBar.NetworkController( 1472): networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1472): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1472): refreshViews: Data not connected!! Set no data type icon / Roaming
D/BluetoothManagerService( 1030): Message: 60
D/BluetoothManagerService( 1030): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 12, newState=13
D/BluetoothManagerService( 1030): Bluetooth State Change Intent: 12 -> 13
D/PostponalbeReceiver( 7189): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
D/CSLegacyTypeTracker( 1030): [lge_data] remove agent NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.141/24,fe80::c69a:2ff:fe7b:60ac/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{50} validated{true} created{true} explicitlySelected{false} } list []  wasFirstNetwork :true
D/CSLegacyTypeTracker( 1030): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
D/ConnectivityService( 1030): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
I/StatusBar.NetworkController( 1472): networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar,.NetworkController( 1472): mWifiConnected = false, mWifiLevel = 0
,D/ConnectivityService( 1030): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService( 1030): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/StatusBar.NetworkController( 1472): refreshViews: Data not connected!! Set no data type icon / Roaming
D/BluetoothAdapterProperties( 6053): Scan Mode:20
D/BluetoothAdapterState( 6053): CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
D/btif_config_util( 6053): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
V/BluetoothSapService( 6053): Accept thread exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
V/BluetoothFtpService:RfcommSocketAcceptThread( 6053): Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
E/BtOppRfcommListener( 6053): Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
V/BluetoothPbapService( 6053): Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
W/bt-l2cap( 6053): L2CAP - L2CA_Deregister() called for PSM: 0x000f
W/bt-btif ( 6053): bta_dm_disable BTA_DISABLE_DELAY set to 1000 ms
W/bt-l2cap( 6053): L2CAP - L2CA_Deregister() called for PSM: 0x0019
W/bt-l2cap( 6053): L2CAP - L2CA_Deregister() called for PSM: 0x0017
W/bt-l2cap( 6053): L2CAP - L2CA_Deregister() called for PSM: 0x001b
W/bt-l2cap( 6053): L2CAP - L2CA_Deregister() called for PSM: 0x0019
W/bt-l2cap( 6053): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 6053): L2CAP - L2CA_Deregister() called for PSM: 0x0017
W/bt-l2cap( 6053): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-l2cap( 6053): L2CAP - L2CA_Deregister() called for PSM: 0x001b
W/bt-l2cap( 6053): L2CAP - PSM: 0x001b not found for deregistration
W/bt-l2cap( 6053): L2CAP - L2CA_Deregister() called for PSM: 0x0011
W/bt-l2cap( 6053): L2CAP - L2CA_Deregister() called for PSM: 0x0013
E/bt-btif ( 6053): bta_gattc_deregister Deregister Failedm unknown client cif
V/BluetoothMapMasInstance( 6053): Accept exception: (expected at shutdown)
V/BluetoothMapMasInstance( 6053): java.io.IOException: read failed, socket might closed or timeout, read ret: -1
V/BluetoothMapMasInstance( 6053): 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:586)
V/BluetoothMapMasInstance( 6053): 	at android.bluetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:563)
V/BluetoothMapMasInstance( 6053): 	at android.bluetooth.BluetoothSocket.accept(BluetoothSocket.java:418)
V/BluetoothMapMasInstance( 6053): 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:130)
V/BluetoothMapMasInstance( 6053): 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:116)
V/BluetoothMapMasInstance( 6053): 	at com.android.bluetooth.map.BluetoothMapMasInstance$SocketAcceptThread.run(BluetoothMapMasInstance.java:133)
D/LGBluetoothAPIService( 1964): [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
I/[SystemUI]BluetoothHandler( 1472): Receive : BluetoothAdapter.ACTION_STATE_CHANGED
D/ConnectivityService( 1030): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService( 1030): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1030): sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/NetworkManagementService( 1030): Removing idletimer
W/Settings( 1030): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/ConnectivityService( 1030): requestNetworkTransitionWakelock: wakelock - ignore in airplane mode
E/ConnectivityService( 1030): EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
D/WIFI    ( 1030): n,ew score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    ( 1030):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/TelephonyNetworkFactory-1( 1866): new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/TelephonyNetworkFactory-1( 1866):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
I/BluetoothMapService( 6053): onReceive: android.bluetooth.adapter.action.STATE_CHANGED
D/BluetoothMapService( 6053): STATE_TURNING_OFF
V/BtOppService( 6053): Receiver DISABLED_ACTION 
V/BluetoothMapService( 6053): Handler(): got msg=4
D/BluetoothMapService( 6053): MAP Service closeService in
D/BluetoothMapMasInstance( 6053): MAP Service shutdown
D/LGBluetoothMapAdapter( 6053): [BTUI] LGBluetoothMapAdapter cleanup
V/BluetoothMapService( 6053): MAP Service closeService out
I/BtOppRfcommListener( 6053): stopping Accept Thread
V/BtOppRfcommListener( 6053): close mBtServerSocket
I/BtOppRfcommListener( 6053): BluetoothSocket listen thread finished
V/BtOppRfcommListener( 6053): waiting for thread to terminate
V/BtOppRfcommListener( 6053): done waiting for thread to terminate
D/LocationManagerService( 1030): getAllProviders()=[passive, gps, network]
D/Ulp_jni ( 1030): JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
D/Ulp_jni ( 1030): JNI:system_update. Event-4
I/jxcore-log( 5996): Radios toggled
I/jxcore-log( 5996): 
E/WifiStateMachine( 1030):  DisconnectedState CMD_STOP_SUPPLICANT 0 0
E/WifiStateMachine( 1030):  ConnectModeState CMD_STOP_SUPPLICANT 0 0
E/WifiStateMachine( 1030):  DriverStartedState CMD_STOP_SUPPLICANT 0 0
E/WifiStateMachine( 1030):  SupplicantStartedState CMD_STOP_SUPPLICANT 0 0
,D/LocSvc_java( 1030): Sending msg: 4 arg1:0 arg2:1
D/LocSvc_java( 1030): Sending msg: 4 arg1:0 arg2:1
D/LocSvc_java( 1030): getAGpsConnectionInfo connType - 4
D/LocSvc_java( 1030): updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java( 1030): ignore wifi update if we are not in OPENING or CLOSING
D/LocSvc_java( 1030): getAGpsConnectionInfo connType - 4
D/LocSvc_java( 1030): updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java( 1030): ignore wifi update if we are not in OPENING or CLOSING
V/NetworkPolicy( 1030): [LG_RESTRICTED] !!!isConnected  type  :1
V/NetworkPolicy( 1030): [LG_RESTRICTED] !!!isConnected  type  :1
V/BtOppService( 6053): onDestroy
D/LGBluetoothOppAdapter( 6053): [BTUI] LGBluetoothOppAdapter cleanup
I/PCSuite ( 7217): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 7217): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 7217): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
W/ContextImpl( 7148): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
D/LGWifiP2pService( 1030): InactiveState{ when=0 what=131204 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1030): P2pEnabledState{ when=0 what=131204 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiMonitor( 1030): stopMonitoring(p2p0) = com.android.server.wifi.p2p.LGWifiP2pServiceImpl$P2pStateMachine@23cb2406
D/WifiScanningService( 1030): SCAN_AVAILABLE : 1
D/LGWifiP2pService( 1030): P2pDisablingState
D/RttService( 1030): SCAN_AVAILABLE : 1
D/LGWifiP2pService( 1030): P2pDisablingState{ when=-1ms what=147458 target=com.android.internal.util.StateMachine$SmHandler }
D/RttService( 1030): EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiScanningService( 1030): DefaultState got{ when=0 what=160007 target=com.android.internal.util.StateMachine$SmHandler }
,D/LGWifiP2pService( 1030): p2p socket connection lost
D/LGWifiP2pService( 1030): P2pDisabledState
E/WifiStateMachine( 1030):  WaitForP2pDisableState CMD_DISABLE_P2P_RSP uid=1000 0 0
D/WifiNative-wlan0( 1030): doBoolean: DRIVER BTCOEXMODE 2
I/wpa_supplicant( 6108): wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
V/WfdStateTracker( 1964): WfdStateTracker handleDirectStateChangedEvent: 0
D/WfdsService( 1964): WifiP2pState is changed : false
D/WifiNative-wlan0( 1030): DRIVER BTCOEXMODE 2: returned true
D/WifiNative-wlan0( 1030): doBoolean: SET ps 1
D/WfdsService( 1964): WfdsEnabledState: Receive the WFDS_DISABLE message
D/WfdsService( 1964): Set the WFDS Monitor: false
D/WfdsMonitor( 1964): WFDS Monitor is stopped
D/WfdsService( 1964): STATE : WfdsDisabledState - enter
W/WfdsSession:Controller( 1964): DefaultState - msg [9441355] is not handled
D/CtrlSupplicant( 1964): Received on exit socket, terminate
E/CtrlSupplicant( 1964): wfds_wait_for_event: buf = CTRL-EVENT-TERMINATING  - connection closed
D/WfdsMonitor( 1964): Event [CTRL-EVENT-TERMINATING  - connection closed]
D/WfdsMonitor( 1964): WfdsMonitorThread is received the interrupt - closing
W/WfdsService( 1964): DefaultState - msg [9445378] is not handled
D/LGWifiP2pService( 1030): P2pDisabledState{ when=-2ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1030): DefaultState{ when=-2ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0( 1030): SET ps 1: returned true
D/CommandListener(  308): Clearing all IP addresses on wlan0
V/BluetoothPbapReceiver( 6053): PbapReceiver onReceive 
V/BluetoothPbapReceiver( 6053): ***********action = android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothPbapReceiver( 6053): ***********state = 13
V/BluetoothPbapReceiver( 6053): ***********Calling start service!!!! with action = null
V/BluetoothPbapService( 6053): action: android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothPbapService( 6053): state: 13
V/WiFiOffLoadBroadcast( 7148): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
V/BluetoothPbapService( 6053): Pbap Service closeService in
,D/WiFiOffLoadBroadcast( 7148): MCCMNC not supported: null
D/BluetoothManagerService( 1030): Message: 20
D/BluetoothManagerService( 1030): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@b6e25ce:true
I/ActivityManager( 1030): Start proc com.lge.lifetracker for broadcast com.lge.lifetracker/.receiver.HealthDeviceReceiver: pid=7881 uid=10037 gids={50037, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
,V/BluetoothPbapService( 6053): successfully stopped pbap service
V/BluetoothPbapService( 6053): Pbap Service closeService out
V/BluetoothPbapService( 6053): Pbap Service onDestroy
V/BluetoothPbapService( 6053): Pbap Service closeService in
V/BluetoothPbapService( 6053): Pbap Service closeService out
,D/LGBluetoothPbapAdapter( 6053): [BTUI] cleanup
D/WifiHS20( 1030): hidePasspointNotification off =false
W/Settings( 1030): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1030): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1030): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
D/WifiNative-p2p0( 1030): doBoolean: TERMINATE
D/WifiNative-p2p0( 1030): TERMINATE: returned true
E/WifiStateMachine( 1030): Couldn't get getWiFiOffloadingIface : 
E/WifiStateMachine( 1030): useWiFiOffloading() : false
E/WifiStateMachine( 1030): CONFIG_LGE_WLAN_PATH : true
D/WifiHS20( 1030): hidePasspointNotification off =false
W/Settings( 1030): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1030): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1030): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
V/WfdStateTracker( 1964): WfdStateTracker handleDirectStateChangedEvent: 6
I/WifiServerServiceExt( 1030): WIFI_STATE_CHANGED_ACTION [0]
,D/BluetoothManagerService( 1030): Message: 30
D/BluetoothManagerService( 1030): Message: 30
,D/LocalBluetoothProfileManager( 7148): Adding local MAP profile
D/BluetoothMap( 7148): Create BluetoothMap proxy object
D/BluetoothManagerService( 1030): Message: 30
D/BluetoothManagerService( 1030): Message: 30
D/TelephonyIcons( 1472): null signal icon name: drawable/stat_sys_signal_null
D/StatusBar.NetworkController( 1472): refreshViews: Data not connected!! Set no data type icon / Roaming
D/StatusBar.NetworkController( 1472): refreshViews: Data not connected!! Set no data type icon / Roaming
D/LocalBluetoothProfileManager( 7148): LocalBluetoothProfileManager construction complete
D/LGBluetoothFeatureConfig( 7148):  get() - isFeatureLoaded : false
,D/LGBluetoothUserBindClient( 7148): [BTUI] initUserBindClient
D/TelephonyIcons( 1472): null signal icon name: drawable/stat_sys_signal_null
D/StatusBar.NetworkController( 1472): refreshViews: Data not connected!! Set no data type icon / Roaming
D/StatusBar.NetworkController( 1472): refreshViews: Data not connected!! Set no data type icon / Roaming
I/StatusBar.NetworkController( 1472): networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1472): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1472): refreshViews: Data not connected!! Set no data type icon / Roaming
,I/StatusBar.NetworkController( 1472): networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1472): mWifiConnected = false, mWifiLevel = 0
W/ContextImpl( 7148): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.android.settings.bluetooth.LGBluetoothUserBindClient.initUserBindClient:90 com.android.settings.bluetooth.LGBluetoothUserBindClient.<init>:55 com.android.settings.bluetooth.LGBluetoothUserBindClient.getInstance:47 
D/StatusBar.NetworkController( 1472): refreshViews: Data not connected!! Set no data type icon / Roaming
D/StatusBar.NetworkController( 1472): refreshViews: Data not connected!! Set no data type icon / Roaming
D/DockEventReceiver( 7148): finishStartingService: stopping service
D/BluetoothInputDevice( 7148): Proxy object connected
D/DhcpStateMachine( 1030): StoppedState
D/DhcpStateMachine( 1030): StoppedState{ when=-95ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
D/HidProfile( 7148): Bluetooth service connected
D/BluetoothPan( 7148): BluetoothPAN Proxy object connected
D/PanProfile( 7148): Bluetooth service connected
D/QRemote ( 6242): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/BluetoothMap( 7148): Proxy object connected
E/WifiStateMachine( 1030):  SupplicantStoppingState CMD_ON_QUIT 0 0
D/MapProfile( 7148): Bluetooth service connected
E/WifiStateMachine( 1030):  DefaultState CMD_ON_QUIT 0 0
D/BluetoothMap( 7148): getConnectedDevices()
,D/BluetoothMap( 7148): Bluetooth is Not enabled
D/QRemote ( 6242): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
D/LGBluetoothUserBindClient( 7148): [BTUI] onServiceConnected
I/QRemote ( 6242): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
D/PostponalbeReceiver( 7189): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
I/PCSuite ( 7217): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 7217): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 7217): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 7148): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,E/ActivityThread( 7881): Failed to find provider info for com.lge.lgaccount.provider
W/LG Account v2.2( 7881): No ProfileInfo entries
I/LG Account v2.2( 7881): isEnabled: false
I/Feature ( 7881): [Lifetracker]ver: 4.21.112(40211120)
I/Feature ( 7881): [Lifetracker]Country: EU
I/Feature ( 7881): [Lifetracker]Operator: OPEN
I/Feature ( 7881): [Lifetracker]Ranking support: false
I/Feature ( 7881): [Lifetracker]Comfort support: false
,I/Feature ( 7881): [Lifetracker]Accessory: true
I/Feature ( 7881): [Lifetracker]Health device: true
I/Feature ( 7881): [Lifetracker]Extra Pedometer: false
I/Feature ( 7881): [Lifetracker]Blood glucose device: false
I/Feature ( 7881): [Lifetracker]Device Number: 3
D/WiFiOffLoadBroadcast( 7148): MCCMNC not supported: null
D/LGBluetoothAuthorization( 7148): [BTUI] cancel All Notification
D/BluetoothPermissionRequest( 7148): onReceive
D/LGBluetoothAuthorization( 7148): [BTUI] cancel All Notification
,I/ActivityManager( 1030): Killing 6998:com.lge.appbox.client/u0a11 (adj 15): empty #17
D/LGBluetoothResetSettingReceiver( 7148): return without doing reset settings.
V/BluetoothOppReceiver( 6053): Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_TURNING_OFF
D/BluetoothOppNotification( 6053): [BTUI] cancel opp incoming file confirm notification
W/libprocessgroup( 1030): failed to open /acct/uid_10011/pid_6998/cgroup.procs: No such file or directory
D/BluetoothOppNotification( 6053): [BTUI] cancel opp active transfer file notification
,D/QRemote ( 6242): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,V/BluetoothFtpReceiver( 6053): BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothFtpReceiver( 6053): BluetoothFtpReceiver Start Service
D/QRemote ( 6242): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
V/BluetoothFtpService( 6053): Ftp Service onStartCommand
V/BluetoothFtpService( 6053): action: android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothFtpService( 6053): Ftp Service closeService
E/BluetoothFtpService:RfcommSocketAcceptThread( 6053): Shutdown
V/BluetoothFtpService( 6053): successfully stopped ftp service
I/QRemote ( 6242): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
V/BluetoothSapReceiver( 6053): [BTUI] checkServiceStart
V/BluetoothSapReceiver( 6053): [BTUI] region:EU country:EU
V/BluetoothSapReceiver( 6053): SapReceiver onReceive 
V/BluetoothSapReceiver( 6053): action = android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothSapReceiver( 6053):  Bluetooth Adapter state = 13
V/BluetoothSapReceiver( 6053): Calling SAP service start service with action = null
D/PostponalbeReceiver( 7189): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
V/BluetoothFtpService( 6053): Ftp Service onDestroy
V/BluetoothFtpService( 6053): Ftp Service closeService
,V/BluetoothSapService( 6053): action: android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothSapService( 6053): state: 13
V/BluetoothSapService( 6053): Stopping SAP server process
,V/BluetoothSapService( 6053): Sap Service closeSapService in
V/BluetoothSapService( 6053): Close listen Socket : 
V/BluetoothSapService( 6053): Close rfcomm Socket : 
V/BluetoothSapService( 6053): Close sapd  Socket : 
I/PCSuite ( 7217): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 7217): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 7217): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
V/BluetoothSapService( 6053): Sap Service closeSapService out
V/BluetoothSapService( 6053): Sap Service onDestroy
V/BluetoothSapService( 6053): Sap Service closeSapService in
,V/BluetoothSapService( 6053): Close listen Socket : 
V/BluetoothSapService( 6053): Close rfcomm Socket : 
V/BluetoothSapService( 6053): Close sapd  Socket : 
I/ActivityManager( 1030): Start proc com.lge.settings.easy for broadcast com.lge.settings.easy/com.lge.settings.bluetooth.LGBluetoothProfileConnectionReceiver: pid=7907 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,V/BluetoothSapService( 6053): Sap Service closeSapService out
V/WiFiOffLoadBroadcast( 7148): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 7148): MCCMNC not supported: null
D/QRemote ( 6242): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,D/QRemote ( 6242): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 6242): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
D/PostponalbeReceiver( 7189): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
V/WiFiOffLoadBroadcast( 7148): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 7148): MCCMNC not supported: null
D/QRemote ( 6242): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,D/QRemote ( 6242): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 6242): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
D/PostponalbeReceiver( 7189): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,I/PCSuite ( 7217): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 7217): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 7217): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 7148): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,W/ResourcesManager( 7907): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
D/WiFiOffLoadBroadcast( 7148): MCCMNC not supported: null
,D/QRemote ( 6242): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6242): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 6242): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,D/PostponalbeReceiver( 7189): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
I/PCSuite ( 7217): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 7217): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 7217): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 7148): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/AuthorizationBluetoothService( 2126): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
D/WiFiOffLoadBroadcast( 7148): MCCMNC not supported: null
D/QRemote ( 6242): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6242): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 6242): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,D/PCSuite ( 7217): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,V/WiFiOffLoadBroadcast( 7148): WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
W/FormManager( 7318): Network not available. Please check & try again.
,V/FormManager( 7318): Network unavailable.
D/WiFiOffLoadBroadcast( 7148): MCCMNC not supported: null
V/FormManager( 7318): Network unavailable.
,I/ActivityManager( 1030): Killing 7290:com.lge.email/u0a23 (adj 15): empty #17
,W/libprocessgroup( 1030): failed to open /acct/uid_10023/pid_7290/cgroup.procs: No such file or directory
,D/bt_hci_bdroid( 6053): cleanup
,I/bt_lpm  ( 6053): LPM is already off!!!
I/bt_userial_mct( 6053): exiting userial_read_thread
D/bt_userial_mct( 6053): Leaving userial_evt_read_thread()
W/bt-btif ( 6053): ag scb idx 1 not allocated
E/bt-btif ( 6053): BTA AG is already disabled, ignoring ...
W/bt-l2cap( 6053): L2CAP - L2CA_Deregister() called for PSM: 0x0019
W/bt-l2cap( 6053): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 6053): L2CAP - L2CA_Deregister() called for PSM: 0x0017
W/bt-l2cap( 6053): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-l2cap( 6053): L2CAP - L2CA_Deregister() called for PSM: 0x001b
W/bt-l2cap( 6053): L2CAP - PSM: 0x001b not found for deregistration
W/bt-l2cap( 6053): L2CAP - L2CA_Deregister() called for PSM: 0x0019
W/bt-l2cap( 6053): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 6053): L2CAP - L2CA_Deregister() called for PSM: 0x0017
W/bt-l2cap( 6053): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-l2cap( 6053): L2CAP - L2CA_Deregister() called for PSM: 0x001b
W/bt-l2cap( 6053): L2CAP - PSM: 0x001b not found for deregistration
W/bt-l2cap( 6053): L2CAP - L2CA_Deregister() called for PSM: 0x0019
W/bt-l2cap( 6053): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 6053): L2CAP - L2CA_Deregister() called for PSM: 0x0017
W/bt-l2cap( 6053): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-l2cap( 6053): L2CAP - L2CA_Deregister() called for PSM: 0x001b
W/bt-l2cap( 6053): L2CAP - PSM: 0x001b not found for deregistration
E/bt-btif ( 6053): bta_gattc_deregister Deregister Failedm unknown client cif
D/bt_userial_mct( 6053): userial_close_reader Joined userial reader thread: 0
I/bt_vendor( 6053): hw_epilog_process
D/bt_hci_bdroid( 6053): cleanup Finalizing cleanup
D/bt_userial_mct( 6053): userial_close
E/bt_userial_mct( 6053): pthread_join() FAILED result:3
I/bt_vendor( 6053): bt-vendor : BT_VND_OP_USERIAL_CLOSE btSocType: 0
D/bt_hci_bdroid( 6053): set_power 0
I/bt_vendor( 6053): bt-vendor : BT_VND_OP_POWER_CTRL: Off
I/bt_vendor( 6053): bluetooth satus is on
I/bt_vendor( 6053): bt-vendor : resetting BT status
I/bt_vendor( 6053): Starting hciattach daemon
I/bt_vendor( 6053): try to set false
,I/bt_vendor( 6053): Starting hciattach daemon
I/bt_vendor( 6053): try to set false
I/bt_vendor( 6053): cleanup
I/GKI_LINUX( 6053): gki_task task_id=0 [BTU] terminating
I/GKI_LINUX( 6053): GKI_exit_task 0 done
I/GKI_LINUX( 6053): GKI_shutdown(): task [BTU] terminated
D/BluetoothAdapterState( 6053): CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
D/HeadsetService( 6053): Received stop request...Stopping profile...
,I/LGBluetoothHfpAdapter( 6053): [BTUI] LGBluetoothHfpAdapter cleanup
W/LGBluetoothHeadsetServiceJni( 6053): Cleaning up Bluetooth Handsfree callback object
D/BluetoothAdapterService( 6053): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2dc453d0
D/HeadsetStateMachine( 6053): Exit Disconnected: -1
D/BluetoothHeadset( 1030): Proxy object disconnected
D/AudioService( 1030): onServiceDisconnected: Bluetooth profile: 1
D/BluetoothHeadset( 1866): Proxy object disconnected
D/BluetoothHeadset( 1866): Proxy object disconnected
D/BluetoothHeadset( 1866): Proxy object disconnected
D/BluetoothAdapterState( 6053): Stopping profile services that were post enabled
,D/A2dpService( 6053): Received stop request...Stopping profile...
D/A2dpStateMachine( 6053): Exit Disconnected: -1
D/LGBluetoothAvrcpQcomAdapter( 6053): [BTUI] cleanup
D/LGBluetoothA2dpAdapter( 6053): [BTUI] LGBluetoothA2dpAdapter cleanup
W/LGBluetoothA2dpServiceJni( 6053): Cleaning up Bluetooth Handsfree callback object
D/BluetoothAdapterService( 6053): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2dc453d0
D/HidService( 6053): Received stop request...Stopping profile...
D/BluetoothAdapterService( 6053): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2dc453d0
D/BluetoothA2dp( 1030): Proxy object disconnected
D/AudioService( 1030): onServiceDisconnected: Bluetooth profile: 2
D/HealthService( 6053): Received stop request...Stopping profile...
,D/BluetoothAdapterService( 6053): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2dc453d0
D/HeadsetStateMachine( 6053): Unbinding service...
D/HeadsetPhoneState( 6053): [BTUI] listenForPhoneState : start = false
D/LGBluetoothHfpManager( 6053): [BTUI] listenForMultiSimPhoneState : start = false
D/HeadsetPhoneState( 6053): [BTUI] listenForPhoneState : start = false
D/LGBluetoothHfpManager( 6053): [BTUI] listenForMultiSimPhoneState : start = false
W/BluetoothHeadsetServiceJni( 6053): Cleaning up Bluetooth Handsfree Interface...
W/BluetoothHeadsetServiceJni( 6053): Cleaning up Bluetooth Handsfree callback object
I/LGBluetoothHfpAdapter( 6053): [BTUI] LGBluetoothHfpAdapter cleanup
D/PanService( 6053): Received stop request...Stopping profile...
D/BluetoothAdapterService( 6053): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2dc453d0
D/BtGatt.DebugUtils( 6053): handleDebugAction() action=null
D/BtGatt.GattService( 6053): Received stop request...Stopping profile...
D/BtGatt.GattService( 6053): stop()
D/BtGatt.AdvertiseManager( 6053): advertise clients cleared
,D/BluetoothAdapterService( 6053): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2dc453d0
D/BluetoothMapService( 6053): Received stop request...Stopping profile...
D/BluetoothMapService( 6053): stop()
D/BluetoothMapEmailAppObserver( 6053): deinitObservers()
D/BluetoothMapEmailAppObserver( 6053): removeReceiver()
D/BluetoothAdapterService( 6053): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2dc453d0
I/BluetoothA2dpServiceJni( 6053): cleanupNative
I/GKI_LINUX( 6053): gki_task task_id=2 [A2DP-MEDIA] terminating
I/GKI_LINUX( 6053): GKI_exit_task 2 done
I/GKI_LINUX( 6053): GKI_shutdown(): task [A2DP-MEDIA] terminated
W/BluetoothHidServiceJni( 6053): Cleaning up Bluetooth HID Interface...
W/BluetoothHidServiceJni( 6053): Cleaning up Bluetooth GID callback object
W/BluetoothHealthServiceJni( 6053): Cleaning up Bluetooth Health Interface...
W/BluetoothHealthServiceJni( 6053): Cleaning up Bluetooth Health object
W/LGBluetoothHealthServiceJni( 6053): Cleaning up Bluetooth Health object
W/BluetoothPanServiceJni( 6053): Cleaning up Bluetooth PAN Interface...
W/BluetoothPanServiceJni( 6053): Cleaning up Bluetooth PAN callback object
V/BluetoothMapService( 6053): Handler(): got msg=4
D/BluetoothMapService( 6053): MAP Service closeService in
D/LGBluetoothMapAdapter( 6053): [BTUI] LGBluetoothMapAdapter cleanup
V/BluetoothMapService( 6053): MAP Service closeService out
,D/BluetoothAdapterState( 6053): CURRENT_STATE=PENDING, MESSAGE = STOPPED, isTurningOn=false, isTurningOff=true
D/BluetoothAdapterProperties( 6053): Setting state to 10
I/BluetoothAdapterState( 6053): Bluetooth adapter state changed: 13-> 10
D/BluetoothMapService( 6053): cleanup()
D/BluetoothMapService( 6053): MAP Service closeService in
D/LGBluetoothMapAdapter( 6053): [BTUI] LGBluetoothMapAdapter cleanup
V/BluetoothMapService( 6053): MAP Service closeService out
D/BluetoothManagerService( 1030): Message: 60
D/BluetoothManagerService( 1030): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 13, newState=10
D/BluetoothManagerService( 1030): Broadcasting onBluetoothStateChange(false) to 9 receivers.
I/BluetoothAdapterState( 6053): Entering OffState
D/BluetoothHeadset( 1866): onBluetoothStateChange: up=false
D/BluetoothHeadset( 1866): onBluetoothStateChange: up=false
D/BluetoothHeadset( 1866): onBluetoothStateChange: up=false
D/BluetoothPbap( 7148): onBluetoothStateChange: up=false
D/BluetoothInputDevice( 7148): onBluetoothStateChange: up=false
,D/BluetoothHeadset( 1030): onBluetoothStateChange: up=false
D/BluetoothPan( 7148): onBluetoothStateChange on: false
D/BluetoothMap( 7148): onBluetoothStateChange: up=false
D/BluetoothA2dp( 1030): onBluetoothStateChange: up=false
D/BluetoothManagerService( 1030): Calling onBluetoothServiceDown callbacks
D/BluetoothManagerService( 1030): Broadcasting onBluetoothServiceDown() to 8 receivers.
D/BluetoothManagerService( 1030): Calling onQBluetoothServiceDown callbacks
D/BluetoothManagerService( 1030): Broadcasting onQBluetoothServiceDown() to 0 receivers.
D/BluetoothManagerService( 1030): unbindAndFinish(): android.bluetooth.IBluetooth$Stub$Proxy@5ea5382 mBinding = false
D/BluetoothManagerService( 1030): Sending unbind request.
I/GKI_LINUX( 6053): gki_task task_id=1 [BTIF] terminating
,I/GKI_LINUX( 6053): GKI_exit_task 1 done
I/GKI_LINUX( 6053): GKI_shutdown(): task [BTIF] terminated
I/BluetoothServiceJni( 6053): cleanupNative: return from cleanup
I/art     ( 6053): --- WEIRD: removing null entry 246
W/art     ( 6053): JNI WARNING: DeleteGlobalRef(0x2003da) failed to find entry
W/LGBluetoothServiceJni( 6053): Cleaning up Bluetooth Service callback object
D/LGBluetoothSettingsDBObserver( 6053): [BTUI] unregister observer for LG device name DB
D/BluetoothManagerService( 1030): Bluetooth State Change Intent: 13 -> 10
I/art     ( 6053): System.exit called, status: 0
I/AndroidRuntime( 6053): VM exiting with result code 0, cleanup skipped.
V/AudioFlinger(  313): 6053 died, releasing its sessions
V/AudioFlinger(  313):  pid 1866 @ 0
V/AudioFlinger(  313):  pid 3300 @ 1
V/AudioFlinger(  313):  pid 3300 @ 2
,D/LGBluetoothAPIService( 1964): [BTUI] LGBluetoothAPIServiceConnection: disconnected from LGBluetoothAPIAdapter
D/LGBluetoothAPIService( 1964): Message: 101
E/LGBluetoothAPIService( 1964): MESSAGE_BLUETOOTH_SERVICE_DISCONNECTED
D/LGBluetoothAPIService( 1964): Calling onBluetoothServiceDown callbacks
D/LGBluetoothAPIService( 1964): Broadcasting onBluetoothServiceDown() to 0 receivers.
D/LGBluetoothUserBindClient( 7148): [BTUI] onServiceDisconnected
,I/ActivityManager( 1030): Process com.android.bluetooth (pid 6053) has died
W/ActivityManager( 1030): Scheduling restart of crashed service com.android.bluetooth/com.lge.bluetooth.app.LGBluetoothAPIServer in 1000ms
W/ActivityManager( 1030): Scheduling restart of crashed service com.android.bluetooth/com.lge.bluetooth.app.LGBluetoothUserBindServer in 11000ms
D/LGBluetoothAPIService( 1964): [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
,I/[SystemUI]BluetoothHandler( 1472): Receive : BluetoothAdapter.ACTION_STATE_CHANGED
D/LGBluetoothAPIService( 1964): Message: 2
D/LGBluetoothAPIService( 1964): unbindAndFinish(): null mBinding = false
D/BluetoothAdapter( 1472): 227846661: getState() :  mService = null. Returning STATE_OFF
D/BluetoothAdapter( 1472): 227846661: getState() :  mService = null. Returning STATE_OFF
D/LGBluetoothFeatureConfig( 7148): isPrivacyLogsEnabled : true
E/LGBluetoothEventManager( 7148): [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_OFF
D/LGBluetoothEventManager( 7148): [BTUI] clear device connection state
,W/ContextImpl( 7148): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
,I/ActivityManager( 1030): Start proc com.android.bluetooth for broadcast com.android.bluetooth/.pbap.BluetoothPbapReceiver: pid=7954 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008, 4002, 1023} abi=armeabi-v7a
,D/DockEventReceiver( 7148): finishStartingService: stopping service
,W/ResourcesManager( 7954): Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
,W/ResourcesManager( 7954): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 7954): Asset path '/system/framework/com.qcom.bluetooth.jar' does not exist or contains no resources.
W/ResourcesManager( 7954): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,D/BluetoothAdapterApp( 7954): Loading JNI Library
,D/BluetoothAdapterApp( 7954): REFCOUNT: Constructed com.android.bluetooth.btservice.AdapterApp@28212f91 Instance Count = 1
,D/BluetoothAdapterApp( 7954): onCreate
D/ProfileConfigQcom( 7954): [BTUI] HeadsetService is supported
D/ProfileConfigQcom( 7954): Adding HeadsetService
D/ProfileConfigQcom( 7954): [BTUI] A2dpService is supported
,D/ProfileConfigQcom( 7954): Adding A2dpService
,D/ProfileConfigQcom( 7954): [BTUI] HidService is supported
D/ProfileConfigQcom( 7954): Adding HidService
D/ProfileConfigQcom( 7954): [BTUI] HealthService is supported
D/ProfileConfigQcom( 7954): Adding HealthService
D/LGBluetoothFeatureConfig( 7954): isSupportPan() :  mTargetOp=OPEN
D/ProfileConfigQcom( 7954): [BTUI] PanService is supported
D/ProfileConfigQcom( 7954): Adding PanService
D/ProfileConfigQcom( 7954): [BTUI] GattService is supported
D/ProfileConfigQcom( 7954): Adding GattService
D/ProfileConfigQcom( 7954): [BTUI] BluetoothMapService is supported
D/ProfileConfigQcom( 7954): Adding BluetoothMapService
D/ProfileConfigQcom( 7954): [BTUI] HeadsetClientService is NOT supported
V/BluetoothPbapReceiver( 7954): PbapReceiver onReceive 
V/BluetoothPbapReceiver( 7954): ***********action = android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothPbapReceiver( 7954): ***********state = 10
V/LGMDMManagerInternal( 7954): Create singleton instance
D/LGBluetoothAPIServer( 7954): [BTUI] onCreate()
D/LGBluetoothAPIServer( 7954): [BTUI] onBind()
,D/LGBluetoothAPIService( 1964): [BTUI] LGBluetoothAPIServiceConnection: connected to LGBluetoothAPIAdapter
D/LGBluetoothAPIService( 1964): Message: 100
D/LGBluetoothAPIService( 1964): MESSAGE_BLUETOOTH_SERVICE_CONNECTED
D/BluetoothPermissionRequest( 7148): onReceive
D/LGBluetoothUtils( 7148): [BTUI] FileNotFound: readProperty
D/BluetoothDiscoverableTimeoutReceiver( 7148): cancelDiscoverableAlarm(): Enter
,D/LGBluetoothUserBindClient( 7148): [BTUI] onServiceConnected
,D/LGBluetoothResetSettingReceiver( 7148): return without doing reset settings.
D/LGBluetoothOppAdapter( 7954): [BTUI] getInstance : create [LGBluetoothOppAdapter]
,V/BluetoothFtpReceiver( 7954): BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothSapReceiver( 7954): [BTUI] checkServiceStart
V/BluetoothSapReceiver( 7954): [BTUI] region:EU country:EU
V/BluetoothSapReceiver( 7954): SapReceiver onReceive 
V/BluetoothSapReceiver( 7954): action = android.bluetooth.adapter.action.STATE_CHANGED
,V/BluetoothSapReceiver( 7954):  Bluetooth Adapter state = 10
D/LGBluetoothProfileConnectionReceiver_EasySetting( 7907): [BTUI] STATE_OFF : reset connected device information EasySettings
D/AuthorizationBluetoothService( 2126): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,I/wpa_supplicant( 6108): p2p0: CTRL-EVENT-TERMINATING 
,I/wpa_supplicant( 6108): monitor socket send errors count : 1
,I/wpa_supplicant( 6108): CTRL_IFACE: Detach monitor /data/misc/wifi/sockets/wpa_ctrl_1964-2\x00 that cannot receive messages
,W/wpa_supplicant( 6108): USIM:  scard_deinit function
D/WifiMonitor( 1030): Event [IFNAME=p2p0 CTRL-EVENT-TERMINATING ]
D/WifiMonitor( 1030): Dropping event because (p2p0) is stopped
D/WifiMonitor( 1030): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=0 BSSID=00:00:00:00:00:00 SSID=]
E/WifiMonitor( 1030): WifiMonitor:wlan0 cnt=49 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=0 BSSID=00:00:00:00:00:00 SSID=
E/WifiStateMachine( 1030):  SupplicantStoppingState SUPPLICANT_STATE_CHANGE_EVENT 49 0 rt=522911  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: DISCONNECTED
E/WifiStateMachine( 1030):  DefaultState SUPPLICANT_STATE_CHANGE_EVENT 49 0 rt=522912  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: DISCONNECTED
I/wpa_supplicant( 6108): wlan0: CTRL-EVENT-TERMINATING 
,D/WifiMonitor( 1030): Event [IFNAME=wlan0 CTRL-EVENT-TERMINATING ]
,E/WifiMonitor( 1030): WifiMonitor:wlan0 cnt=50 dispatchEvent: CTRL-EVENT-TERMINATING 
D/WifiMonitor( 1030): Disconnecting from the supplicant, no more events
,E/WifiStateMachine( 1030):  SupplicantStoppingState SUP_DISCONNECTION_EVENT 50 0
D/WfdsService( 1964): Supplicant Connection state is changed : false
,D/WfdsService( 1964): DefaultState - WIFI_SUPPLICANT_DISCONNECTED
,D/WfdsService( 1964): Set the WFDS Monitor: false
D/WfdsMonitor( 1964): WFDS Monitor is stopped
,D/WifiOffDelayIfNotUsed( 1030): stopMonitoring
E/WifiStateMachine( 1030): Couldn't get getWiFiOffloadingIface : 
E/WifiStateMachine( 1030): useWiFiOffloading() : false
E/WifiStateMachine( 1030): CONFIG_LGE_WLAN_PATH : true
,D/StatusBar.NetworkController( 1472): refreshViews: Data not connected!! Set no data type icon / Roaming
V/WfdStateTracker( 1964): WfdStateTracker handleDirectStateChangedEvent: 0
,W/Settings( 1831): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/WifiServerServiceExt( 1030): WIFI_STATE_CHANGED_ACTION [1]
I/WifiServerServiceExt( 1030): batteryPsActivateMsgHandler : state:0 event:1
I/WifiServerServiceExt( 1030): batteryPsActivateMsgHandler : this is not treated
D/LGDMClient( 3984): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
D/LGDMClient( 3984): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
W/ContextImpl( 3984): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,W/ContextImpl( 3984): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
I/PCSuite ( 7217): [StartReceiver]WIFI_STATE_CHANGED_ACTION : WIFI_STATE_DISABLED
D/PCSuite ( 7217): [StartReceiver][getUpdateNecessity]update = false
,D/PCSuite ( 7217): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 7148): WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,D/WiFiOffLoadBroadcast( 7148): MCCMNC not supported: null
D/LGDMClient( 3984): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=3, isUserType=1
,D/LGDMClient( 3984): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
D/LGDMClient( 3984): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
,V/FormManager( 7318): Network unavailable.
V/FormManager( 7318): Network unavailable.
W/FormManager( 7318): Network not available. Please check & try again.
,E/WifiStateMachine( 1030):  InitialState CMD_RSSI_POLL 2 0 <unknown ssid> rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1552781089] bl(1) rssi=-127 ag=0 br lr ls-=0 [56,56,52,50,50] brc=1 lrc=0
,E/WifiStateMachine( 1030):  DefaultState CMD_RSSI_POLL 2 0 <unknown ssid> rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:9] from screen [on:0 period:-1552781080] bl(1) rssi=-127 ag=0 br lr ls-=0 [56,56,52,50,50] brc=1 lrc=0
,D/ConnectivityService( 1030): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering( 1030): MasterInitialState.processMessage what=3
D/GpsLocationProvider( 1030): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,D/ConnectivityService( 1030): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
D/Tethering( 1030): MasterInitialState.processMessage what=3
,D/PostponalbeReceiver( 7189): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
I/NetworkMonitor( 5182): type=WIFI subType= reason=null isConnected=false
,I/NetworkMonitor( 5182): type=WIFI subType= reason=null isConnected=false
W/ContextImpl( 7189): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
,D/GpsLocationProvider( 1030): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,I/ActivityManager( 1030): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=7991 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,D/GpsLocationProvider( 1030): updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/GpsLocationProvider( 1030): updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/art     (  337): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 466us total 48.610ms
,I/art     (  337): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 448us total 20.103ms
I/art     (  337): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 401us total 19.289ms
,I/AppUp4:AppBoxCP( 7991): onCreate
W/AppUp4:DB( 7991):  [AppBoxDatabaseHelper] construct
I/AppUp4:DB( 7991):  setFingerPrint start
I/AppUp4:DB( 7991):  newfinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys SDK version = 21
,I/AppUp4:DB( 7991):  beforefinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys
I/AppUp4:DB( 7991):  SDK version = 21
I/AppUp4:DB( 7991):  beforefinger == newfinger no write in DB
D/AppUp4:AppBoxApplication( 7991): AppBoxApplication onCreate()
I/NetworkStateForAutoUpdateMonitor( 7991): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 7991): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 7991): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 7991): [onReceive] request level :IDLE....
,I/AppUp4:CustModeStarterReceiver( 7991): onReceive
D/LgDataFeature( 7991): LgDataFeature() Constructor: none
D/LgDataFeature( 7991): LgDataFeature() Constructor Done, null
,D/AppUp4:CustFacade( 7991): Context : android.app.ReceiverRestrictedContext@352ca793
,D/AppUp4:CustFacade( 7991): isCustomizationCompleted : false
D/AppUp4:CustFacade( 7991): isPhone : true
D/AppUp4:CustModeStarterReceiver( 7991): begin check event
I/AppUp4:CustModeStarterReceiver( 7991): Event For GoodConnectivity
D/AppUp4:CustModeStarterReceiver( 7991): runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
D/AppUp4:CustModeStarterReceiver( 7991): call method handleAsyncCustNotification.
D/AppUp4:CustModeStarterReceiver( 7991): handleAsync isTriedOnce : false
E/AppUp4:CustModeStarterReceiver( 7991): handleAsyncCustNotification do not startCustService
I/ActivityManager( 1030): Killing 7354:com.android.chrome/u0a57 (adj 15): empty #17
W/libprocessgroup( 1030): failed to open /acct/uid_10057/pid_7354/cgroup.procs: No such file or directory
,D/LGDMClient( 3984): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 3984): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
W/ContextImpl( 3984): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
W/ContextImpl( 3984): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
D/LGDMClient( 3984): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=3, isUserType=1
,D/LGDMClient( 3984): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 3984): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
I/ActivityManager( 1030): Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=8030 uid=10023 gids={50023, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,W/ResourcesManager( 8030): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 8030): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 8030): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
W/ResourcesManager( 8030): Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
I/LGEmail ( 8030): [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,D/LGEmail ( 8030): user build Type == true (at Util.java isUserModeBuildType 3507)[v:6.41.18]
,W/ResourceType( 8030): No package identifier when getting value for resource number 0x00000000
,D/LgDataFeature( 8030): LgDataFeature() Constructor: none
,D/LgDataFeature( 8030): LgDataFeature() Constructor Done, null
,D/eas_req ( 8030): ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
,I/LgeMiscReceiver( 3300): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 3300): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 3300): networkInfo.isConnected() = false
,I/HubEmail( 8030): JNI_OnLoad()
I/HubEmail( 8030): -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 8030): registerNatives()
I/HubEmail( 8030): -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 8030): registerNativeMethods()
I/HubEmail( 8030): -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
W/art     ( 8030): JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
I/ActivityManager( 1030): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=8062 uid=10057 gids={50057, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/FormManager( 7318): Network not available. Please check & try again.
,V/FormManager( 7318): Network unavailable.
W/Settings( 8030): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
V/FormManager( 7318): Network unavailable.
,I/ActivityManager( 1030): Killing 7373:com.lge.drmservice/u0a62 (adj 15): empty #17
,W/libprocessgroup( 1030): failed to open /acct/uid_10062/pid_7373/cgroup.procs: No such file or directory
I/ActivityManager( 1030): Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=8080 uid=10062 gids={50062, 9997, 4002, 3003, 1028} abi=armeabi-v7a
,I/ActivityManager( 1030): Killing 7393:com.lge.sizechangable.weather/u0a85 (adj 15): empty #17
W/libprocessgroup( 1030): failed to open /acct/uid_10085/pid_7393/cgroup.procs: No such file or directory
,I/ActivityManager( 1030): Start proc com.lge.sizechangable.weather for broadcast com.lge.sizechangable.weather/.layout.WeatherWidget: pid=8097 uid=10085 gids={50085, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager( 1030): Killing 7411:com.google.android.apps.magazines/u0a93 (adj 15): empty #17
,W/libprocessgroup( 1030): failed to open /acct/uid_10093/pid_7411/cgroup.procs: No such file or directory
,I/art     ( 8097): Almond Protected OAT
,D/WeatherApplication( 8097): removeAccount
,D/WeatherApplication( 8097): Account.length = 0
E/WeatherApplication( 8097): OPERATOR:OPEN
,D/WeatherAncestor( 8097): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 20:25:34
D/Weather.Utils( 8097): 2 : the weather widgets(using time tick) are gone.
D/Weather.Utils( 8097): 2 : All the weather widget is gone.
D/UpdateThreadPoolManager( 8097): 2 : This is isUpdating : false
,D/WeatherAncestor( 8097): connectivity changed - connection : true
D/WeatherService( 8097): 2 : isServiceAlived():false forecastCache:null
D/ForecastDataCache( 8097): 2 : lastUpdatedTime: 1430558561343
D/ForecastDataCache( 8097): 2 : currentPackageVersion: 4.40.4
D/ForecastDataCache( 8097): 2 : Cache is not up-to-date, count: 0
,D/Weather_cast( 8097): 2 : isUpdateNeedForAlarm : no city return false
,D/WeatherAncestor( 8097): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 20:25:34
,I/ActivityManager( 1030): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=8115 uid=10093 gids={50093, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager( 1030): Killing 7093:com.google.android.apps.plus/u0a97 (adj 15): empty #17
,W/libprocessgroup( 1030): failed to open /acct/uid_10097/pid_7093/cgroup.procs: No such file or directory
,E/VoldCmdListener(  280): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
,E/Vold    (  280): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  280): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 8115): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
E/VoldCmdListener(  280): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  280): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  280): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 8115): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
E/VoldCmdListener(  280): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  280): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  280): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 8115): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
E/VoldCmdListener(  280): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  280): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  280): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 8115): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
D/LGWifiP2pService( 1030): P2pDisabledState{ when=-5ms what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1030): DefaultState{ when=-5ms what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
,E/WifiStateMachine( 1030):  InitialState CMD_STOP_SUPPLICANT_FAILED 1 0
,E/WifiStateMachine( 1030):  DefaultState CMD_STOP_SUPPLICANT_FAILED 1 0
,I/WebViewFactory( 8115): Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,I/LibraryLoader( 8115): Loading: webviewchromium
,I/LibraryLoader( 8115): Time to load native libraries: 6 ms (timestamps 6174-6180)
I/LibraryLoader( 8115): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 8115): Binding Chromium to main looper Looper (main, tid 1) {15157d2c}
,I/LibraryLoader( 8115): Expected native library version number "",actual native library version number ""
,I/chromium( 8115): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 8115): Initializing chromium process, renderers=0
,W/art     ( 8115): Attempt to remove local handle scope entry from IRT, ignoring
W/chromium( 8115): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
,I/chromium( 8115): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=38 off=46780 len=2953
,I/chromium( 8115): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:39 off:229536 len:643667
V/AudioPolicyService(  313): registerClient() client 0xb14272a0, uid 10093
W/AudioManagerAndroid( 8115): Requires BLUETOOTH permission
I/Adreno-EGL( 8115): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 8115): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 8115): Build Date: 12/12/14 금
I/Adreno-EGL( 8115): Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
I/Adreno-EGL( 8115): Remote Branch: 
I/Adreno-EGL( 8115): Local Patches: 
I/Adreno-EGL( 8115): Reconstruct Branch: 
,I/art     ( 1030): Explicit concurrent mark sweep GC freed 89947(4MB) AllocSpace objects, 5(592KB) LOS objects, 33% free, 44MB/66MB, paused 2.163ms total 149.339ms
,I/NSApplication( 8115): Starting up...
,I/ActivityManager( 1030): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=8170 uid=10097 gids={50097, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
I/ActivityManager( 1030): Killing 6880:com.android.vending/u0a44 (adj 15): empty #17
W/libprocessgroup( 1030): failed to open /acct/uid_10044/pid_6880/cgroup.procs: No such file or directory
,W/ResourcesManager( 8170): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/iu.Environment( 2352): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,I/iu.UploadsManager( 2352): num queued entries: 0
I/iu.UploadsManager( 2352): num updated entries: 0
I/iu.SyncManager( 2352): NEXT; no task
,D/ChimeraCfgMgr( 2352): Loading module com.google.android.gms.kids from APK com.google.android.gms
D/PostponalbeReceiver( 7189): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
,I/NetworkStateForAutoUpdateMonitor( 7991): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 7991): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 7991): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 7991): [onReceive] request level :IDLE....
W/ContextImpl( 7189): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
I/AppUp4:CustModeStarterReceiver( 7991): onReceive
,D/AppUp4:CustFacade( 7991): Context : android.app.ReceiverRestrictedContext@352ca793
D/AppUp4:CustFacade( 7991): isCustomizationCompleted : false
D/AppUp4:CustFacade( 7991): isPhone : true
D/AppUp4:CustModeStarterReceiver( 7991): begin check event
I/AppUp4:CustModeStarterReceiver( 7991): Event For GoodConnectivity, noConnectivity : false, but skip! 
D/LGDMClient( 3984): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMClient( 3984): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
W/ContextImpl( 3984): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
I/GLSActivity( 2126): [ac] getting account id
W/ContextImpl( 3984): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
I/GLSUser ( 2126): [t] Fetched account id for thalitester@gmail.com : 105256135866144380227
,D/eas_req ( 8030): ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
D/LGDMClient( 3984): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=3, isUserType=1
D/LGDMClient( 3984): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 3984): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
,I/LgeMiscReceiver( 3300): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
,I/LgeMiscReceiver( 3300): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 3300): networkInfo.isConnected() = false
W/FormManager( 7318): Network not available. Please check & try again.
,W/Settings( 8030): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
V/FormManager( 7318): Network unavailable.
D/WeatherAncestor( 8097): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 20:25:35
D/Weather.Utils( 8097): 2 : the weather widgets(using time tick) are gone.
D/Weather.Utils( 8097): 2 : All the weather widget is gone.
D/UpdateThreadPoolManager( 8097): 2 : This is isUpdating : false
D/WeatherAncestor( 8097): connectivity changed - connection : true
D/WeatherService( 8097): 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@31013fc9
D/ForecastDataCache( 8097): 2 : lastUpdatedTime: 1430558561343
D/ForecastDataCache( 8097): 2 : currentPackageVersion: 4.40.4
,D/ForecastDataCache( 8097): 2 : Cache is up-to-date, count: 0
,D/Weather_cast( 8097): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherAncestor( 8097): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 20:25:35
V/FormManager( 7318): Network unavailable.
D/ChimeraCfgMgr( 2352): Loading module com.google.android.gms.kids from APK com.google.android.gms
,I/art     ( 3355): Explicit concurrent mark sweep GC freed 6121(410KB) AllocSpace objects, 0(0B) LOS objects, 36% free, 27MB/43MB, paused 589us total 33.067ms
,D/PowerManagerServiceEx( 1030): acquireWakeLockInternal: lock=770300739, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1030
,V/AlarmManager( 1030): ELAPSED_WAKEUP set : Alarm{1ffe19a2 type 2 when 528719 com.google.android.gms} when 528719
,D/[Concierge]Service( 2607): onStartCommand(). Type : 9
,D/libc-netbsd(  308): default dns: query_ipv6=0, query_ipv4=0
,D/DSQN    ( 1030): DNSproblemNotiEnabled is disabled ignore DNS fail CB
D/PowerManagerServiceEx( 1030): releaseWakeLockInternal: lock=770300739 [*alarm*], flags=0x0
,I/GAV4    ( 8115): Thread[GAThread,5,main]: No campaign data found.
,I/ActivityManager( 1030): Killing 7597:com.google.android.apps.books/u0a54 (adj 15): empty #17
,W/libprocessgroup( 1030): failed to open /acct/uid_10054/pid_7597/cgroup.procs: No such file or directory
,D/sensors_hal_Time( 1030): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1030): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1030): tsOffsetIs: Apps: 537329939121; DSPS: 17748750; Offset : -4334110882
,I/[SystemUI]TimeTickManager( 1472): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1472): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1472): called onTimeUpdated()
,I/[SystemUI]Clock( 1472): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1472): called onTimeUpdated()
I/[SystemUI]DateView( 1472): called onTimeUpdated()
I/[SystemUI]DateView( 1472): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1472): handleTimeUpdate
,D/sensors_hal_Time( 1030): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1030): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1030): tsOffsetIs: Apps: 557331785208; DSPS: 18404170; Offset : -4334095953
,D/sensors_hal_Time( 1030): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1030): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1030): tsOffsetIs: Apps: 577333871397; DSPS: 19059598; Offset : -4334085116
,D/sensors_hal_Time( 1030): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1030): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1030): tsOffsetIs: Apps: 597335643786; DSPS: 19715017; Offset : -4334113187
,I/[SystemUI]TimeTickManager( 1472): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1472): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1472): called onTimeUpdated()
,I/[SystemUI]Clock( 1472): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1472): called onTimeUpdated()
,I/[SystemUI]DateView( 1472): called onTimeUpdated()
,I/[SystemUI]DateView( 1472): called onTimeUpdated()
,D/KeyguardUpdateMonitor( 1472): handleTimeUpdate
D/sensors_hal_Time( 1030): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1030): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1030): tsOffsetIs: Apps: 617337718205; DSPS: 20370445; Offset : -4334113963
,D/sensors_hal_Time( 1030): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1030): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1030): tsOffsetIs: Apps: 637339785645; DSPS: 21025872; Offset : -4334091175
,D/PowerManagerServiceEx( 1030): acquireWakeLockInternal: lock=770300739, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1030
,D/[Concierge]Service( 2607): onStartCommand(). Type : 9
,D/PowerManagerServiceEx( 1030): releaseWakeLockInternal: lock=770300739 [*alarm*], flags=0x0
,D/sensors_hal_Time( 1030): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1030): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1030): tsOffsetIs: Apps: 657341759545; DSPS: 21681297; Offset : -4334100865
,I/[SystemUI]TimeTickManager( 1472): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1472): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1472): called onTimeUpdated()
I/[SystemUI]Clock( 1472): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1472): called onTimeUpdated()
,I/[SystemUI]DateView( 1472): called onTimeUpdated()
,I/[SystemUI]DateView( 1472): called onTimeUpdated()
,D/KeyguardUpdateMonitor( 1472): handleTimeUpdate
D/sensors_hal_Time( 1030): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1030): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1030): tsOffsetIs: Apps: 677343833911; DSPS: 22336725; Offset : -4334101564,
,D/PowerManagerServiceEx( 1030): acquireWakeLockInternal: lock=770300739, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1030
,V/AlarmManager( 1030): ELAPSED_WAKEUP set : Alarm{24993f69 type 2 when 687508 android} when 687508
D/[Concierge]Service( 2607): onStartCommand(). Type : 9
,D/PowerManagerServiceEx( 1030): releaseWakeLockInternal: lock=770300739 [*alarm*], flags=0x0
,D/sensors_hal_Time( 1030): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1030): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1030): tsOffsetIs: Apps: 697345837290; DSPS: 22992151; Offset : -4334112320
,D/sensors_hal_Time( 1030): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1030): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1030): tsOffsetIs: Apps: 717347913948; DSPS: 23647579; Offset : -4334110909
,I/[SystemUI]TimeTickManager( 1472): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1472): called onTimeUpdated()
,I/[SystemUI]KeyguardIndicationController( 1472): called onTimeUpdated()
,I/[SystemUI]Clock( 1472): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1472): called onTimeUpdated()
,I/[SystemUI]DateView( 1472): called onTimeUpdated()
,I/[SystemUI]DateView( 1472): called onTimeUpdated()
,D/KeyguardUpdateMonitor( 1472): handleTimeUpdate
,D/sensors_hal_Time( 1030): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1030): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0,
D/sensors_hal_Time( 1030): tsOffsetIs: Apps: 737349995659; DSPS: 24303007; Offset : -4334104392,
,D/sensors_hal_Time( 1030): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1030): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1030): tsOffsetIs: Apps: 757352001017; DSPS: 24958433; Offset : -4334113221
,D/sensors_hal_Time( 1030): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1030): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0,
,D/sensors_hal_Time( 1030): tsOffsetIs: Apps: 777353871478; DSPS: 25613854; Offset : -4334104332
,I/[SystemUI]TimeTickManager( 1472): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1472): called onTimeUpdated()
,I/[SystemUI]KeyguardIndicationController( 1472): called onTimeUpdated()
,I/[SystemUI]Clock( 1472): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1472): called onTimeUpdated()
,I/[SystemUI]DateView( 1472): called onTimeUpdated()
,I/[SystemUI]DateView( 1472): called onTimeUpdated()
,D/KeyguardUpdateMonitor( 1472): handleTimeUpdate
,D/PowerManagerServiceEx( 1030): acquireWakeLockInternal: lock=770300739, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1030
,I/ActivityManager( 1030): Start proc com.lge.clock for broadcast com.lge.clock/.widget.DigitalAppWidgetProvider: pid=8260 uid=10010 gids={50010, 9997, 3003, 1028, 4002} abi=armeabi-v7a
,D/[Concierge]Service( 2607): onStartCommand(). Type : 9
,I/DigitalAppWidgetProvider( 8260): onReceive: com.android.deskclock.ON_QUARTER_HOUR
,V/DigitalAppWidgetProvider( 8260): startAlarmOnQuarterHour android.app.ReceiverRestrictedContext@1f364564
I/ActivityManager( 1030): Killing 5809:com.uei.lg.quicksetsdk.maxq616/1000 (adj 15): empty #17
D/PowerManagerServiceEx( 1030): releaseWakeLockInternal: lock=770300739 [*alarm*], flags=0x0
,I/QRemote ( 6242): [RemoteControlManager.java:195:onServiceDisconnected()] oooooo start
,W/System.err( 6242): android.os.DeadObjectException
W/System.err( 6242): 	at android.os.BinderProxy.transactNative(Native Method)
,W/System.err( 6242): 	at android.os.BinderProxy.transact(Binder.java:496)
W/System.err( 6242): 	at com.uei.control.IControl.unregisterCallback(IControl.java:502)
,W/System.err( 6242): 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:199)
W/System.err( 6242): 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
W/System.err( 6242): 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
W/System.err( 6242): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 6242): 	at android.os.Handler.dispatchMessage(Handler.java:95)
,W/System.err( 6242): 	at android.os.Looper.loop(Looper.java:135)
,W/System.err( 6242): 	at android.app.ActivityThread.main(ActivityThread.java:5274)
W/System.err( 6242): 	at java.lang.reflect.Method.invoke(Native Method)
,W/System.err( 6242): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 6242): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
,W/System.err( 6242): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
E/UEI.SmartControl( 6242): IControl.unregisterCallback error: android.os.DeadObjectException
W/System.err( 6242): android.os.DeadObjectException
,W/System.err( 6242): 	at android.os.BinderProxy.transactNative(Native Method)
W/System.err( 6242): 	at android.os.BinderProxy.transact(Binder.java:496)
W/System.err( 6242): 	at com.uei.control.IControl.unregisterSetupReadyCallback(IControl.java:818)
,W/System.err( 6242): 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:200)
,W/System.err( 6242): 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
W/System.err( 6242): 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
W/System.err( 6242): 	at android.os.Handler.handleCallback(Handler.java:739)
,W/System.err( 6242): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 6242): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 6242): 	at android.app.ActivityThread.main(ActivityThread.java:5274)
W/System.err( 6242): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 6242): 	at java.lang.reflect.Method.invoke(Method.java:372)
,W/System.err( 6242): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
W/System.err( 6242): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
E/UEI.SmartControl( 6242): IControl.unregisterSetupReadyCallback error: android.os.DeadObjectException
I/QRemote ( 6242): [RemoteControlManager.java:203:onServiceDisconnected()] oooooo Control unbind before rebinding.
W/libprocessgroup( 1030): failed to open /acct/uid_1000/pid_5809/cgroup.procs: No such file or directory
W/ActivityManager( 1030): Scheduling restart of crashed service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service in 1000ms
,D/QRemote ( 6242): [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]10
,I/QRemote ( 6242): [RemoteControlManager.java:157:onBindIRService()] oooooo bind
I/ActivityManager( 1030): Start proc com.uei.lg.quicksetsdk.maxq616 for service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service: pid=8294 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,D/QRemote ( 6242): [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
,D/UEI.SmartControl( 8294): Quickset Services start...
,I/UEI.SmartControl( 8294): Manufacture = LGE
,D/UEI.SmartControl( 8294): Id = LGNevo
,D/UEI.SmartControl( 8294): File observer start...
E/UEI.SmartControl( 8294): IR Port is disabled: false
D/UEI.SmartControl( 8294): Starting file observer...
D/UEI.SmartControl( 8294): Extracting JNI libs...
D/UEI.SmartControl( 8294): --- this system supports 32-bit or 64-bit only
D/UEI.SmartControl( 8294): --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
D/UEI.SmartControl( 8294): --- Checking lib: libqs_armeabi-v7a.zip
D/UEI.SmartControl( 8294): --- Extracting JNI libs: libqs_armeabi-v7a.zip
,I/UEI.SmartControl( 8294): --- Selecting new region: 6
,I/UEI.SmartControl( 8294): Model = LG-D855
,D/UEI.SmartControl( 8294): QS Service created
I/UEI.SmartControl( 8294): Service initServices...
,D/UEI.SmartControl( 8294): QS start get config
D/UEI.SmartControl( 8294): Loading JNI Libs...
,I/UEI.SmartControl( 8294): Supports setup maps: true
,D/UEI.SmartControl( 8294): QS start statue = true Error code = 0
I/UEI.SmartControl( 8294): QS version = v2.7.10.1_RC1
I/UEI.SmartControl( 8294): QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
I/UEI.SmartControl( 8294): ### init IR Blaster...
D/serial_port( 8294): Configuring serial port
,E/UEI.SmartControl( 8294): UEIBLaster setting for 616
I/UEI.SmartControl( 8294): Setting serial record hearder size = 2
I/UEI.SmartControl( 8294): configuring settings for MAXQ616
I/UEI.SmartControl( 8294): Get version...
D/UEI.SmartControl( 8294): serial port data available: 21
,D/UEI.SmartControl( 8294): MAXQ616 A2-X4 software.
I/UEI.SmartControl( 8294): IR Blaster version: 256702256704300002
I/UEI.SmartControl( 8294): QS saving settings...
,D/UEI.SmartControl( 8294): IR Blaster version: 25672567
D/UEI.SmartControl( 8294): serial port data available: 4
,W/ContextImpl( 8294): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
,I/UEI.SmartControl( 8294): Device manager: loading config....
D/UEI.SmartControl( 8294): ----------- loading internal config...
E/UEI.SmartControl( 8294): Services init done
D/UEI.SmartControl( 8294): QS Service init finished
D/UEI.SmartControl( 8294): QS Service version name: 2.1.91
D/UEI.SmartControl( 8294): QS Service version code: 201091
,D/UEI.SmartControl( 8294): Service requested: Control
E/UEI.SmartControl( 8294): Loading SETTINGS...
,D/UEI.SmartControl( 8294): Request IControl service: devices are loaded...
I/ActivityManager( 1030): Killing 6242:com.lge.qremote/u0a112 (adj 15): empty #17
D/UEI.SmartControl( 8294): -- Open brand translation xml: brands_translations_ko
,I/UEI.SmartControl( 8294): Notify AllClients services are ready: 0
D/UEI.SmartControl( 8294): -----service ready thread exits
,W/libprocessgroup( 1030): failed to open /acct/uid_10112/pid_6242/cgroup.procs: No such file or directory
,D/UEI.SmartControl( 8294): Internal service binding...
,D/sensors_hal_Time( 1030): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1030): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1030): tsOffsetIs: Apps: 797355706261; DSPS: 26269274; Offset : -4334100578
,D/UEI.SmartControl( 8294): Internal timer expired: 1
,D/UEI.SmartControl( 8294): unbind internal service
,D/UEI.SmartControl( 8294): Service.onUnbind: IControl
,D/UEI.SmartControl( 8294): Service.onDestroy
D/UEI.SmartControl( 8294): Lock is in USE false
D/UEI.SmartControl( 8294): unbind internal service
W/System.err( 8294): java.lang.IllegalArgumentException: Service not registered: com.uei.control.g@1cf029ef
W/System.err( 8294): 	at android.app.LoadedApk.forgetServiceDispatcher(LoadedApk.java:1119)
W/System.err( 8294): 	at android.app.ContextImpl.unbindService(ContextImpl.java:1873)
W/System.err( 8294): 	at android.content.ContextWrapper.unbindService(ContextWrapper.java:550)
W/System.err( 8294): 	at com.uei.control.Service.c(Unknown Source)
W/System.err( 8294): 	at com.uei.control.Service.onDestroy(Unknown Source)
W/System.err( 8294): 	at android.app.ActivityThread.handleStopService(ActivityThread.java:2901)
D/serial_port( 8294): close(fd = 25)
,W/System.err( 8294): 	at android.app.ActivityThread.access$2200(ActivityThread.java:148)
,W/System.err( 8294): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1386)
,W/System.err( 8294): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,W/System.err( 8294): 	at android.os.Looper.loop(Looper.java:135)
,W/System.err( 8294): 	at android.app.ActivityThread.main(ActivityThread.java:5274)
,W/System.err( 8294): 	at java.lang.reflect.Method.invoke(Native Method)
,W/System.err( 8294): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 8294): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
W/System.err( 8294): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
E/UEI.SmartControl( 8294): java.lang.IllegalArgumentException: Service not registered: com.uei.control.g@1cf029ef
I/UEI.SmartControl( 8294): Serial port is closed.
I/UEI.SmartControl( 8294): Serial port is closed.
I/UEI.SmartControl( 8294): Serial port is closed.,
D/UEI.SmartControl( 8294): Blaster closed
D/UEI.SmartControl( 8294): Shut down QS...,
D/UEI.SmartControl( 8294): Stopping QS lib
D/UEI.SmartControl( 8294): QS lib stop result = true
D/UEI.SmartControl( 8294): Stopped QS lib
D/UEI.SmartControl( 8294): Stopped file observer...
D/UEI.SmartControl( 8294): QS shutdown complete
D/sensors_hal_Time( 1030): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1030): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1030): tsOffsetIs: Apps: 817357769171; DSPS: 26924702; Offset : -4334112811
,D/sensors_hal_Time( 1030): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1030): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1030): tsOffsetIs: Apps: 837359877860; DSPS: 27580131; Offset : -4334109862
,I/[SystemUI]TimeTickManager( 1472): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1472): called onTimeUpdated()
,I/[SystemUI]KeyguardIndicationController( 1472): called onTimeUpdated()
,I/[SystemUI]Clock( 1472): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1472): called onTimeUpdated()
,I/[SystemUI]DateView( 1472): called onTimeUpdated()
,I/[SystemUI]DateView( 1472): called onTimeUpdated()
,D/KeyguardUpdateMonitor( 1472): handleTimeUpdate
,D/sensors_hal_Time( 1030): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1030): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1030): tsOffsetIs: Apps: 857362007229; DSPS: 28235560; Offset : -4334086205,
,D/sensors_hal_Time( 1030): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1030): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1030): tsOffsetIs: Apps: 877364100346; DSPS: 28890989; Offset : -4334098749
,D/sensors_hal_Time( 1030): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1030): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1030): tsOffsetIs: Apps: 897365839661; DSPS: 29546406; Offset : -4334099065
,I/[SystemUI]TimeTickManager( 1472): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1472): called onTimeUpdated()
,I/[SystemUI]KeyguardIndicationController( 1472): called onTimeUpdated()
,I/[SystemUI]Clock( 1472): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1472): called onTimeUpdated()
,I/[SystemUI]DateView( 1472): called onTimeUpdated()
I/[SystemUI]DateView( 1472): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1472): handleTimeUpdate
,D/sensors_hal_Time( 1030): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1030): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1030): tsOffsetIs: Apps: 917367745643; DSPS: 30201829; Offset : -4334115665
,D/sensors_hal_Time( 1030): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1030): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1030): tsOffsetIs: Apps: 937369871052; DSPS: 30857258; Offset : -4334095970
,D/sensors_hal_Time( 1030): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1030): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1030): tsOffsetIs: Apps: 957373009482; DSPS: 31512721; Offset : -4334100823
,I/[SystemUI]LGPowerUI( 1472): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1472): On Skip Timer : true
,D/WifiController( 1030): battery changed pluggedType: 2
,D/LEDHandler( 1964): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1964): Battery Level Remaining: 100%
D/LEDHandler( 1964): Battery Temp: 278, mChargingStatus=5, mChargingStop=false
D/KeyguardUpdateMonitor( 1472): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 278
I/[SystemUI]LGPowerUI( 1472): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]BatterySaverHandler( 1472): onReceive = android.intent.action.BATTERY_CHANGED
D/LGDMClient( 3984): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.intent.action.BATTERY_CHANGED
,D/LGDMClient( 3984): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,I/[SystemUI]TimeTickManager( 1472): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1472): called onTimeUpdated()
,I/[SystemUI]KeyguardIndicationController( 1472): called onTimeUpdated()
,I/[SystemUI]Clock( 1472): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1472): called onTimeUpdated()
,I/[SystemUI]DateView( 1472): called onTimeUpdated()
,I/[SystemUI]DateView( 1472): called onTimeUpdated()
,D/KeyguardUpdateMonitor( 1472): handleTimeUpdate
,D/sensors_hal_Time( 1030): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1030): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1030): tsOffsetIs: Apps: 977382410204; DSPS: 32168389; Offset : -4334099489
,D/sensors_hal_Time( 1030): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1030): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1030): tsOffsetIs: Apps: 997384474571; DSPS: 32823817; Offset : -4334110292
,D/sensors_hal_Time( 1030): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1030): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1030): tsOffsetIs: Apps: 1017386542584; DSPS: 33479244; Offset : -4334087165
,I/[SystemUI]TimeTickManager( 1472): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1472): called onTimeUpdated()
,I/[SystemUI]KeyguardIndicationController( 1472): called onTimeUpdated()
,I/[SystemUI]Clock( 1472): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1472): called onTimeUpdated()
,I/[SystemUI]DateView( 1472): called onTimeUpdated()
,I/[SystemUI]DateView( 1472): called onTimeUpdated()
,D/KeyguardUpdateMonitor( 1472): handleTimeUpdate
,D/sensors_hal_Time( 1030): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1030): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0,
D/sensors_hal_Time( 1030): tsOffsetIs: Apps: 1037388408045; DSPS: 34134666; Offset : -4334113637
,D/sensors_hal_Time( 1030): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1030): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1030): tsOffsetIs: Apps: 1057390193767; DSPS: 34790084; Offset : -4334097988
,D/sensors_hal_Time( 1030): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1030): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1030): tsOffsetIs: Apps: 1077392401364; DSPS: 35445516; Offset : -4334087681
,I/[SystemUI]TimeTickManager( 1472): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1472): called onTimeUpdated()
,I/[SystemUI]KeyguardIndicationController( 1472): called onTimeUpdated()
,I/[SystemUI]Clock( 1472): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1472): called onTimeUpdated()
,I/[SystemUI]DateView( 1472): called onTimeUpdated()
,I/[SystemUI]DateView( 1472): called onTimeUpdated()
,D/KeyguardUpdateMonitor( 1472): handleTimeUpdate
,D/sensors_hal_Time( 1030): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1030): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1030): tsOffsetIs: Apps: 1097394293126; DSPS: 36100938; Offset : -4334088035,
,I/[SystemUI]LGPowerUI( 1472): onReceive = com.lge.android.intent.action.BATTERYEX
,I/[SystemUI]LGPowerUI( 1472): On Skip Timer : true
,D/LEDHandler( 1964): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1964): Battery Level Remaining: 100%
D/LEDHandler( 1964): Battery Temp: 276, mChargingStatus=5, mChargingStop=false
,D/KeyguardUpdateMonitor( 1472): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 276
I/[SystemUI]LGPowerUI( 1472): onReceive = android.intent.action.BATTERY_CHANGED
D/WifiController( 1030): battery changed pluggedType: 2
I/[SystemUI]BatterySaverHandler( 1472): onReceive = android.intent.action.BATTERY_CHANGED
D/LGDMClient( 3984): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.intent.action.BATTERY_CHANGED
D/LGDMClient( 3984): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,D/sensors_hal_Time( 1030): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1030): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1030): tsOffsetIs: Apps: 1117396457702; DSPS: 36756369; Offset : -4334090181
,D/sensors_hal_Time( 1030): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1030): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1030): tsOffsetIs: Apps: 1137398278580; DSPS: 37411789; Offset : -4334100307
,I/[SystemUI]TimeTickManager( 1472): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1472): called onTimeUpdated()
,I/[SystemUI]KeyguardIndicationController( 1472): called onTimeUpdated()
,I/[SystemUI]Clock( 1472): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1472): called onTimeUpdated()
,I/[SystemUI]DateView( 1472): called onTimeUpdated()
,I/[SystemUI]DateView( 1472): called onTimeUpdated()
,D/KeyguardUpdateMonitor( 1472): handleTimeUpdate
,D/sensors_hal_Time( 1030): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1030): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1030): tsOffsetIs: Apps: 1157401289718; DSPS: 38067248; Offset : -4334110382
,D/sensors_hal_Time( 1030): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1030): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1030): tsOffsetIs: Apps: 1177403282731; DSPS: 38722673; Offset : -4334101195
,D/sensors_hal_Time( 1030): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1030): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1030): tsOffsetIs: Apps: 1197405052724; DSPS: 39378091; Offset : -4334101220
,I/[SystemUI]TimeTickManager( 1472): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1472): called onTimeUpdated()
,I/[SystemUI]KeyguardIndicationController( 1472): called onTimeUpdated()
,I/[SystemUI]Clock( 1472): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1472): called onTimeUpdated()
,I/[SystemUI]DateView( 1472): called onTimeUpdated()
,I/[SystemUI]DateView( 1472): called onTimeUpdated()
,D/KeyguardUpdateMonitor( 1472): handleTimeUpdate
,D/sensors_hal_Time( 1030): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1030): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0,
,D/sensors_hal_Time( 1030): tsOffsetIs: Apps: 1217406911361; DSPS: 40033512; Offset : -4334103948
,I/UsageStatsService( 1030): User[0] Flushing usage stats to disk
,D/sensors_hal_Time( 1030): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1030): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0,
,D/sensors_hal_Time( 1030): tsOffsetIs: Apps: 1237409001198; DSPS: 40688940; Offset : -4334089489
,D/sensors_hal_Time( 1030): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1030): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1030): tsOffsetIs: Apps: 1257410920045; DSPS: 41344363; Offset : -4334093222
,I/[SystemUI]TimeTickManager( 1472): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1472): called onTimeUpdated()
,I/[SystemUI]KeyguardIndicationController( 1472): called onTimeUpdated()
,I/[SystemUI]Clock( 1472): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1472): called onTimeUpdated()
,I/[SystemUI]DateView( 1472): called onTimeUpdated()
I/[SystemUI]DateView( 1472): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1472): handleTimeUpdate
,D/sensors_hal_Time( 1030): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1030): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1030): tsOffsetIs: Apps: 1277413036391; DSPS: 41999792; Offset : -4334082537
,D/sensors_hal_Time( 1030): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1030): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1030): tsOffsetIs: Apps: 1297415099561; DSPS: 42655220; Offset : -4334094589
,D/sensors_hal_Time( 1030): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1030): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1030): tsOffsetIs: Apps: 1317416869553; DSPS: 43310638; Offset : -4334094513
,I/[SystemUI]TimeTickManager( 1472): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1472): called onTimeUpdated()
,I/[SystemUI]KeyguardIndicationController( 1472): called onTimeUpdated()
,I/[SystemUI]Clock( 1472): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1472): called onTimeUpdated()
I/[SystemUI]DateView( 1472): called onTimeUpdated()
I/[SystemUI]DateView( 1472): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1472): handleTimeUpdate
,D/sensors_hal_Time( 1030): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1030): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1030): tsOffsetIs: Apps: 1337418971732; DSPS: 43966067; Offset : -4334098151
,TIME-OUT KILL (timeout was 1200000ms)
```
