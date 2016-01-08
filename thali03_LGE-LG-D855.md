#### Test 5497026140aeaf4_thali03_LGE-LG-D855 Logs


```
--------- beginning of main
D/sensors_hal_Time( 1030): tsOffsetIs: Apps: 257438909104; DSPS: 8576475; Offset : -4304391274
,D/AndroidRuntime( 6175): 
D/AndroidRuntime( 6175): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 6175): CheckJNI is OFF
D/AndroidRuntime( 6175): Calling main entry com.android.commands.am.Am
--------- beginning of system
I/ActivityManager( 1030): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
V/SplitWindowPolicy( 1953): checkScreen => return. sourceIntent is null or not support SplitWindow component: ComponentInfo{co..../co.....MainActivity}
D/SplitInfo( 1030): new ActivitySplitInfo : ActivitySplitInfo [screenZone=0/ flag=0/ state=NATIVE]
D/ActivityManager( 1030): setTaskToReturnTo : TaskRecord{2555579d #4 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
D/ActivityManager( 1030): setTaskToReturnTo : TaskRecord{2555579d #4 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
D/WindowStateEx( 1030): AppWindowTokenEx init.. 
E/GBMv2   (  334): DFP En is all cleared set to be enabled
I/ActivityManager( 1030): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6195 uid=10311 gids={50311, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
D/AndroidRuntime( 6175): Shutting down VM
V/AlarmManager( 1030): RTC_WAKEUP set : Alarm{2c619f5e type 0 when 1452278490931 com.android.vending} when 1452278490931
V/ActivityManager( 1030): Display changed displayId=0
D/DSDPConnection( 1852): Display #0 changed.
V/SIM_STK ( 1030): Menu title from STK is T-Mobile
D/SplitWindowPolicy( 1953): updateActivityStateChanged: resumed=true, screenId=1, isScreenFull=true
D/SplitWindowPolicy( 1953): topRunningActivity=ActivityInfo{1fb6a50c co.....MainActivity}, taskId=4, activityType=0, bIsSplit=false
D/SplitWindowPolicy( 1953): updateActivityStateChanged: resumed=false, screenId=1, isScreenFull=true
D/SplitWindowPolicy( 1953): topRunningActivity=ActivityInfo{1a561e55 co.....MainActivity}, taskId=4, activityType=0, bIsSplit=false
D/ContextHelper( 6195): convertTheme. context->name=com.test.thalitest themeResourceId=16973833
,I/WebViewFactory( 6195): Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,I/LibraryLoader( 6195): Loading: webviewchromium
I/LibraryLoader( 6195): Time to load native libraries: 3 ms (timestamps 1598-1601)
I/LibraryLoader( 6195): Expected native library version number "",actual native library version number ""
V/GLSActivity( 2121): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/WebViewChromiumFactoryProvider( 6195): Binding Chromium to main looper Looper (main, tid 1) {366e1ec1}
I/LibraryLoader( 6195): Expected native library version number "",actual native library version number ""
,I/chromium( 6195): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 6195): Initializing chromium process, renderers=0
W/art     ( 6195): Attempt to remove local handle scope entry from IRT, ignoring
,W/chromium( 6195): [WARNING:dns_config_service_posix.cc(293)] Failed to read DnsConfig.
V/AudioPolicyService(  311): registerClient() client 0xb57dac60, uid 10311
,D/BluetoothManagerService( 1030): Message: 20
D/BluetoothManagerService( 1030): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@2bb6f9d1:true
W/chromium( 6195): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
I/chromium( 6195): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=32 off=46780 len=2953
I/chromium( 6195): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:33 off:229536 len:643667
D/BluetoothAdapter( 6195): 76027494: getState() :  mService = null. Returning STATE_OFF
I/Adreno-EGL( 6195): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 6195): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 6195): Build Date: 12/12/14 금
I/Adreno-EGL( 6195): Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
I/Adreno-EGL( 6195): Remote Branch: 
I/Adreno-EGL( 6195): Local Patches: 
I/Adreno-EGL( 6195): Reconstruct Branch: 
,I/art     ( 1030): Explicit concurrent mark sweep GC freed 26886(1218KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 43MB/65MB, paused 1.651ms total 83.412ms
,I/GLSUser ( 2121): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 2121): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2121): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2121): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2121): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/Finsky  ( 4918): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 4918): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 4918): [1] 5.onFinished: Giving up after 6 failures.
W/chromium( 6195): [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
,W/chromium( 6195): [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
W/art     ( 6195): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 6195): onDetachedFromWindow called when already detached. Ignoring
D/SystemWebViewEngine( 6195): CordovaWebView is running on device made by: LGE
,W/art     ( 6195): Attempt to remove local handle scope entry from IRT, ignoring
,W/art     ( 6195): Attempt to remove local handle scope entry from IRT, ignoring
,D/OpenGLRenderer( 6195): Render dirty regions requested: true
I/OpenGLRenderer( 6195): Initialized EGL, version 1.4
,D/OpenGLRenderer( 6195): Enabling debug mode 0
D/Atlas   ( 6195): Validating map...
,D/SplitWindow( 1030): check instance of lgWin Window{351b6b58 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,D/LgDataFeature( 6195): LgDataFeature() Constructor: none
D/LgDataFeature( 6195): LgDataFeature() Constructor Done, null
,I/SystemUI[Framework]( 1030): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x0, pkg=com.android.systemui
W/PhoneWindowManagerEx( 1030): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx( 1030): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx( 1030): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework]( 1030): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@16fc3356,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework]( 1030): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
D/PhoneStatusBar( 1457): setSystemUiVisibility vis=0 mask=ffffffff oldVal=8000 newVal=0 diff=8000
,I/[SystemUI]NavigationThemeResource( 1457): NavigationKey Color is changed(WHITE_WITH_SHADOW -> BLACK)
I/[SystemUI]NavigationThemeResource( 1457):  BarMode=0, Theme=WHITE, LightBackground=false (Transparent)
I/[SystemUI]NavigationThemeResource( 1457): , Keyguard show=false, IME shown=false, Panel expanded=false
I/ActivityManager( 1030): Displayed com.test.thalitest/.MainActivity: +617ms (total +723ms)
,I/Timeline( 1030): Timeline: Activity_windows_visible id: ActivityRecord{6765412 u0 com.test.thalitest/.MainActivity t4} time:272047
I/Timeline( 6195): Timeline: Activity_idle id: android.os.BinderProxy@2738e516 time:272048
D/JsMessageQueue( 6195): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log( 6195): JniHelper::setJavaVM(0xb487c280), pthread_self() = -1434888448
D/JX-Cordova( 6195): jxcore cordova android initializing
,E/GBMv2   (  334): DFP En is all cleared set to be enabled
E/GBMv2   (  334): Set value is all cleared set the max
I/GBMv2   (  334): DFP Enabled. Ignore VFP set
,W/jxcore-log( 6195): Initializing JXcore engine
,W/jxcore-log( 6195): JXcore engine is ready
W/jxcore-log( 6195): Starting JXcore engine
W/.test.thalitest( 6195): type=1400 audit(0.0:146): avc: denied { ioctl } for path="socket:[10561]" dev="sockfs" ino=10561 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
W/.test.thalitest( 6195): type=1400 audit(0.0:147): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3222 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
W/.test.thalitest( 6195): type=1400 audit(0.0:148): avc: denied { ioctl } for path="socket:[7460]" dev="sockfs" ino=7460 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
W/.test.thalitest( 6195): type=1400 audit(0.0:149): avc: denied { ioctl } for path="/cust" dev="mmcblk0p42" ino=2 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=dir
W/.test.thalitest( 6195): type=1400 audit(0.0:150): avc: denied { ioctl } for path="socket:[28479]" dev="sockfs" ino=28479 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
,I/art     ( 6195): Background sticky concurrent mark sweep GC freed 124626(12MB) AllocSpace objects, 23(7MB) LOS objects, 28% free, 39MB/55MB, paused 1.628ms total 120.483ms
,W/jxcore-log( 6195): Platform android
W/jxcore-log( 6195): 
W/jxcore-log( 6195): Process ARCH arm
W/jxcore-log( 6195): 
I/jxcore-log( 6195): JXcore Cordova bridge is ready!
I/jxcore-log( 6195): 
W/jxcore-log( 6195): JXcore engine is started
,I/jxcore-log( 6195): Toggling radios to true
I/jxcore-log( 6195): 
,D/BluetoothManagerService( 1030): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1030): enable():  mBluetooth =null mBinding = false
,D/BluetoothManagerService( 1030): Message: 1
D/BluetoothManagerService( 1030): MESSAGE_ENABLE: mBluetooth = null
D/LocationManagerService( 1030): getAllProviders()=[passive, gps, network]
,D/Ulp_jni ( 1030): JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
D/Ulp_jni ( 1030): JNI:system_update. Event-4
D/WifiService( 1030): New client listening to asynchronous messages
,I/ActivityManager( 1030): Start proc com.android.bluetooth for service com.android.bluetooth/.btservice.AdapterService: pid=6276 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008, 4002, 1023} abi=armeabi-v7a
,D/WifiServiceImplEx( 1030): setWifiEnabled: true pid=6195, uid=10311, package= com.test.thalitest, App Lable : ThaliTest
D/WifiService( 1030): setWifiEnabled: true pid=6195, uid=10311
E/WifiService( 1030): Invoking mWifiStateMachine.setWifiEnabled
D/LocationManagerService( 1030): getAllProviders()=[passive, gps, network]
E/WifiStateMachine( 1030):  InitialState CMD_START_SUPPLICANT 0 0
D/Ulp_jni ( 1030): JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 1,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
I/LGFTMITEM( 1030): [GET_FTM][id=6], offset=12288
D/Ulp_jni ( 1030): JNI:system_update. Event-4
,D/WifiServiceImplEx( 1030): disconnect pid=6195, uid=10311, packageName=com.test.thalitest
E/WifiUtil( 1030): wfc_util_ffile_check_copy(): pid[1030] pDestFName[/data/misc/wifi/WCNSS_qcom_cfg.ini] pSourceFName[/system/etc/wifi/WCNSS_qcom_cfg.ini]
E/WifiUtil( 1030): wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
E/WifiUtil( 1030): wfc_util_ffile_check_copy(): pid[1030] pDestFName[/data/misc/wifi/WCNSS_qcom_wlan_nv.bin] pSourceFName[/system/etc/wifi/WCNSS_qcom_wlan_nv.bin]
E/WifiUtil( 1030): wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
I/WifiUtil( 1030): Intf0MacAddress=C49A027B60AC
E/WifiHW  ( 1030): unknown target_country: EU , set to default
E/WifiHW  ( 1030): [wifi_ensure_config_files] default country1 = GB
E/WifiHW  ( 1030): [wifi_ensure_config_files] default country2 = GB
I/WifiUtil( 1030): gEnableBmps=1
D/WifiServiceImplEx( 1030): reconnect pid=6195, uid=10311, packageName=com.test.thalitest
I/jxcore-log( 6195): Radios toggled
I/jxcore-log( 6195): 
,W/ResourcesManager( 6276): Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
W/ResourcesManager( 6276): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 6276): Asset path '/system/framework/com.qcom.bluetooth.jar' does not exist or contains no resources.
W/ResourcesManager( 6276): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,D/BluetoothAdapterApp( 6276): Loading JNI Library
,D/Tethering( 1030): sendTetherStateChangedBroadcast 1, 0, 0
,D/Tethering( 1030): InitialState.processMessage what=4
D/SoftapController(  307): Softap fwReload - Ok
D/libc-netbsd(  307): default dns: query_ipv6=0, query_ipv4=0
D/CommandListener(  307): Setting iface cfg
D/CommandListener(  307): Trying to bring down wlan0
D/DSQN    ( 1030): DNSproblemNotiEnabled is disabled ignore DNS fail CB
D/CommandListener(  307): Clearing all IP addresses on wlan0
,D/BluetoothAdapterApp( 6276): REFCOUNT: Constructed com.android.bluetooth.btservice.AdapterApp@2c329345 Instance Count = 1
,E/WifiHW  ( 1030): Cannot open "/system/etc/wifi/autojoinconfig.txt": No such file or directory
I/ActivityManager( 1030): Start proc com.android.settings for broadcast com.android.settings/.deviceinfo.UsbSettingsReceiver: pid=6308 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
D/Tethering( 1030): sendTetherStateChangedBroadcast 0, 0, 0
E/WifiStateMachine( 1030): Couldn't get getWiFiOffloadingIface : 
E/WifiStateMachine( 1030): useWiFiOffloading() : false
E/WifiStateMachine( 1030): CONFIG_LGE_WLAN_PATH : true
D/WifiMonitor( 1030): startMonitoring(wlan0) with mConnected = false
D/WifiMonitor( 1030): connecting to supplicant
,W/wpa_supplicant( 6321): type=1400 audit(0.0:151): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6815 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
W/wpa_supplicant( 6321): type=1400 audit(0.0:152): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6815 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
D/BluetoothAdapterApp( 6276): onCreate
V/WfdStateTracker( 1953): WfdStateTracker handleDirectStateChangedEvent: 1
D/StatusBar.NetworkController( 1457): refreshViews: Data not connected!! Set no data type icon / Roaming
I/WifiServerServiceExt( 1030): WIFI_STATE_CHANGED_ACTION [2]
I/wpa_supplicant( 6321): Successfully initialized wpa_supplicant
,D/ProfileConfigQcom( 6276): [BTUI] HeadsetService is supported
D/ProfileConfigQcom( 6276): Adding HeadsetService
D/ProfileConfigQcom( 6276): [BTUI] A2dpService is supported
D/ProfileConfigQcom( 6276): Adding A2dpService
I/wpa_supplicant( 6321): rfkill: Cannot open RFKILL control device
D/ProfileConfigQcom( 6276): [BTUI] HidService is supported
D/ProfileConfigQcom( 6276): Adding HidService
I/wpa_supplicant( 6321): [LGE_PATCH] unset P2P_CAPABLE to ifname wlan0
D/ProfileConfigQcom( 6276): [BTUI] HealthService is supported
D/ProfileConfigQcom( 6276): Adding HealthService
D/LGBluetoothFeatureConfig( 6276): isSupportPan() :  mTargetOp=OPEN
D/ProfileConfigQcom( 6276): [BTUI] PanService is supported
D/ProfileConfigQcom( 6276): Adding PanService
D/ProfileConfigQcom( 6276): [BTUI] GattService is supported
D/ProfileConfigQcom( 6276): Adding GattService
D/ProfileConfigQcom( 6276): [BTUI] BluetoothMapService is supported
D/ProfileConfigQcom( 6276): Adding BluetoothMapService
D/ProfileConfigQcom( 6276): [BTUI] HeadsetClientService is NOT supported
,D/BluetoothManagerService( 1030): Message: 20
D/BluetoothManagerService( 1030): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@179a362b:true
,D/BluetoothAdapterState( 6276): make
W/ResourcesManager( 6308): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6308): Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
W/ResourcesManager( 6308): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 6308): Asset path '/system/framework/com.lge.bluetooth.jar' does not exist or contains no resources.
W/ResourcesManager( 6308): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
W/ResourcesManager( 6308): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
I/LGFMServiceAdapter( 6276): [FM] LGFMServiceAdapter : create
I/bluedroid-qcom( 6276): init
I/BluetoothAdapterState( 6276): Entering OffState
I/bte_conf( 6276): bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,I/bte_conf( 6276): bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
E/bt_osi_config( 6276): config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
I/bte_conf( 6276): bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
D/BTIF_CORE( 6276): [BTUI] lge_load_bluetooth_address
I/bluedroid-qcom( 6276): get_profile_interface socket
I/bluedroid-qcom( 6276): get_profile_interface map_client
W/bdaddr_loader( 6337): type=1400 audit(0.0:153): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6815 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
W/bdaddr_loader( 6337): type=1400 audit(0.0:154): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6815 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
I/GKI_LINUX( 6276): gki_task_entry task_id=1 [BTIF] starting
D/BluetoothAdapterProperties( 6276): Address is:58:3F:54:73:64:C0
D/lge_bdaddr_loader( 6337): [BTUI] bdaddr_loader ::: START
,D/lge_bdaddr_loader( 6337): [BTUI] bluetooth_load_bdaddress
I/LGFTMITEM( 6337): [GET_FTM][id=8], offset=16384
D/lge_bdaddr_loader( 6337): [BTUI] bdaddr to set in property : 58:3F:54:73:64:C0
D/BluetoothManagerService( 1030): Bluetooth Adapter name changed to G3-1
D/BluetoothAdapterProperties( 6276): Name is: G3-1
D/BluetoothManagerService( 1030): Stored Bluetooth name: G3-1
D/BluetoothManagerService( 1030): BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
,E/lge_bdaddr_loader( 6337): [BTUI] bluetooth_load_bdaddress : OK => 58:3F:54:73:64:C0
,D/lge_bdaddr_loader( 6337): [BTUI] bdaddr_loader ::: END
D/BluetoothManagerService( 1030): Message: 40
D/BluetoothManagerService( 1030): MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
I/bluedroid-qcom( 6276): config_hci_snoop_log
D/BluetoothManagerService( 1030): Calling onBluetoothServiceUp callbacks
D/BluetoothManagerService( 1030): Broadcasting onBluetoothServiceUp() to 7 receivers.
V/LGMDMManagerInternal( 6276): Create singleton instance
,I/wpa_supplicant( 6321): rfkill: Cannot open RFKILL control device
,D/UsbSettingsReceiver( 6308): [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
D/UsbSettingsReceiver( 6308): [AUTORUN] sys.usb.config = ptp_only,adb
D/UsbSettingsReceiver( 6308): [AUTORUN] sys.usb.state = ptp_only,adb
D/UsbSettingsReceiver( 6308): [AUTORUN] persist.sys.usb.config = ptp_only,adb
D/UsbSettingsReceiver( 6308): [AUTORUN] onReceive() : app userid = 0, current userid = 0
,D/BluetoothAdapterState( 6276): CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
D/BluetoothAdapterProperties( 6276): Setting state to 11
I/BluetoothAdapterState( 6276): Bluetooth adapter state changed: 10-> 11
D/BluetoothManagerService( 1030): Message: 60
D/BluetoothManagerService( 1030): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
I/LGBluetoothServiceJni( 6276): classInitNative: succeeds
D/BluetoothManagerService( 1030): Bluetooth State Change Intent: 10 -> 11
D/LGBluetoothAPIService( 1953): [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
I/[SystemUI]BluetoothHandler( 1457): Receive : BluetoothAdapter.ACTION_STATE_CHANGED
D/UsbSettingsControl( 6308): [AUTORUN] getUsbConnected() : connected=true
,D/UsbSettingsReceiver( 6308): [AUTORUN] onReceive() : availableList=[wlan0]
D/UsbSettingsReceiver( 6308): [AUTORUN] onReceive() : activeList=[]
D/UsbSettingsReceiver( 6308): [AUTORUN] onReceive() : errorList=[]
D/UsbSettingsControl( 6308): [AUTORUN] isAutorunTimer() : mAutorunChanging=false
D/UsbSettingsReceiver( 6308): [AUTORUN] onReceive() : TetherState Changed=wlan0
D/UsbSettingsControl( 6308): [AUTORUN] setTetherStatus() : status=false
I/ActivityManager( 1030): Killing 5846:com.google.android.partnersetup/u0a8 (adj 15): empty #17
I/wpa_supplicant( 6321): [LGE_WLAN_PATCH]P2P 5GHz support level:2(0:no 1:gconly 2:gconly_UNII1 3:full)
,I/wpa_supplicant( 6321): p2p0: CTRL-EVENT-AVOID-FREQ ranges=
I/wpa_supplicant( 6321): wlan0: CTRL-EVENT-SCAN-STARTED 
,E/WifiStateMachine( 1030):  SupplicantStartingState CMD_SET_OPERATIONAL_MODE 1 0
E/WifiStateMachine( 1030):  SupplicantStartingState CMD_START_DRIVER 0 0
E/WifiStateMachine( 1030):  SupplicantStartingState CMD_SET_HIGH_PERF_MODE 0 0
D/WifiMonitor( 1030): Event [IFNAME=p2p0 CTRL-EVENT-AVOID-FREQ ranges=]
E/WifiStateMachine( 1030):  DefaultState CMD_SET_HIGH_PERF_MODE 0 0
D/WifiMonitor( 1030): Dropping event because (p2p0) is stopped
D/WifiMonitor( 1030): Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
E/WifiStateMachine( 1030):  SupplicantStartingState CMD_DISCONNECT 0 0
E/WifiStateMachine( 1030):  DefaultState CMD_DISCONNECT 0 0
E/WifiMonitor( 1030): WifiMonitor:wlan0 cnt=0 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1030): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1030): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
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
W/libprocessgroup( 1030): failed to open /acct/uid_10008/pid_5846/cgroup.procs: No such file or directory
,V/BluetoothPbapReceiver( 6276): PbapReceiver onReceive 
,D/BluetoothBondStateMachine( 6276): make
V/BluetoothPbapReceiver( 6276): ***********action = android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothPbapReceiver( 6276): ***********state = 11
W/Settings( 1030): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
E/WifiStateMachine( 1030): Couldn't get getWiFiOffloadingIface : 
E/WifiStateMachine( 1030): useWiFiOffloading() : false
E/WifiStateMachine( 1030): CONFIG_LGE_WLAN_PATH : true
W/Settings( 1030): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/StatusBar.NetworkController( 1457): refreshViews: Data not connected!! Set no data type icon / Roaming
D/WfdService( 1953): Waiting for WifiP2p enabling
D/WifiNative-wlan0( 1030): doBoolean: SET update_config 1
D/WifiNative-wlan0( 1030): SET update_config 1: returned true
D/WifiConfigStore( 1030): Loading config and enabling all networks 
D/WifiNative-wlan0( 1030): doString: [LIST_NETWORKS]
,D/BluetoothAdapterService( 6276): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@5b2a254
D/LGBluetoothServiceAdapter( 6276): [BTUI] check adapter is available - false.
D/BluetoothAdapterService( 6276): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@5b2a254
D/LGBluetoothServiceAdapter( 6276): [BTUI] check adapter is available - true : set adapter available.
I/WifiServerServiceExt( 1030): WIFI_STATE_CHANGED_ACTION [3]
D/LGBluetoothSettingsDBObserver( 6276): [BTUI] register observer for LG device name DB
I/WifiServerServiceExt( 1030): batteryPsActivateMsgHandler : state:0 event:3
I/BluetoothBondStateMachine( 6276): StableState(): Entering Off State
,D/UsbSettingsReceiver( 6308): [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
D/UsbSettingsReceiver( 6308): [AUTORUN] sys.usb.config = ptp_only,adb
D/UsbSettingsReceiver( 6308): [AUTORUN] sys.usb.state = ptp_only,adb
D/UsbSettingsReceiver( 6308): [AUTORUN] persist.sys.usb.config = ptp_only,adb
D/WifiNative-wlan0( 1030):    returned network id / ssid / bssid / flags 0	NG700	any	
E/BluetoothAdapterService( 6276): File transfer profiles supported!!
E/WifiConfigStore( 1030): readNetworkVariablesFromSupplicantFile key=psk
,E/WifiConfigStore( 1030): readNetworkVariableFromSupplicantFile ssid=["NG700"] key=psk
E/WifiConfigStore( 1030): Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
I/ActivityManager( 1030): Start proc com.lge.lifetracker for broadcast com.lge.lifetracker/.receiver.HealthDeviceReceiver: pid=6341 uid=10037 gids={50037, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
,D/UsbSettingsReceiver( 6308): [AUTORUN] onReceive() : app userid = 0, current userid = 0
E/BluetoothAdapterService( 6276): File transfer profiles supported!!
D/WifiStateMachine( 1030): enableVerboseLogging : level 2
D/BluetoothHeadset( 1030): Proxy object connected
D/BluetoothHeadset( 1852): Proxy object connected
D/BluetoothHeadset( 1852): Proxy object connected
D/BluetoothHeadset( 1852): Proxy object connected
D/HeadsetService( 6276): Received start request. Starting profile...
E/BluetoothAdapterService( 6276): File transfer profiles supported!!
I/LGBluetoothHeadsetServiceJni( 6276): classInitNative: succeeds
D/LGBluetoothHfpAdapter( 6276): Version 1.6
D/UsbSettingsControl( 6308): [AUTORUN] getUsbConnected() : connected=true
D/UsbSettingsReceiver( 6308): [AUTORUN] onReceive() : availableList=[]
D/UsbSettingsReceiver( 6308): [AUTORUN] onReceive() : activeList=[]
D/UsbSettingsReceiver( 6308): [AUTORUN] onReceive() : errorList=[]
D/UsbSettingsControl( 6308): [AUTORUN] isAutorunTimer() : mAutorunChanging=false
D/UsbSettingsControl( 6308): [AUTORUN] setTetherStatus() : status=false
,D/LGBluetoothFeatureConfig( 6276): isPrivacyLogsEnabled : true
I/BluetoothHeadsetServiceJni( 6276): classInitNative: succeeds
E/BluetoothAdapterService( 6276): File transfer profiles supported!!
D/HeadsetStateMachine( 6276): make
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
D/WifiNative-wlan0( 1030): SET config_methods physical_display virtual_push_button: returned true
D/WifiNative-wlan0( 1030): doBoolean: SET device_type 10-0050F204-5
D/WifiNative-wlan0( 1030): SET device_type 10-0050F204-5: returned true
,D/LgDataFeature( 6276): LgDataFeature() Constructor: none
D/LgDataFeature( 6276): LgDataFeature() Constructor Done, null
,I/ActivityManager( 1030): Start proc com.lge.formmanager for broadcast com.lge.formmanager/.FormServiceReceiver: pid=6359 uid=10026 gids={50026, 9997, 3003, 1028} abi=armeabi-v7a
,D/WifiStateMachine( 1030): Setting OUI to DA-A1-19
D/WifiNative-wlan0( 1030): doBoolean: SCAN_INTERVAL 120
D/WifiNative-wlan0( 1030): SCAN_INTERVAL 120: returned true
D/WifiNative-HAL( 1030): Setting external_sim to 1
D/WifiNative-wlan0( 1030): doBoolean: SET external_sim 1
D/WifiNative-wlan0( 1030): SET external_sim 1: returned true
,I/WifiNative-HAL( 1030): startHal
E/wifi    ( 1030): getStaticLongField sWifiHalHandle 0x9895c8dc
E/WifiHAL ( 1030): Could not connect handle
D/wifi    ( 1030): halHandle = 0x0, mVM = 0xb487c280, mCls = 0x601e92
I/WifiNative-HAL( 1030): Could not start hal
D/WifiStateMachine( 1030): Setting OUI to DA-A1-19
I/WifiNative-HAL( 1030): startHal
E/wifi    ( 1030): getStaticLongField sWifiHalHandle 0x9895c85c
E/WifiHAL ( 1030): Could not connect handle
D/wifi    ( 1030): halHandle = 0x0, mVM = 0xb487c280, mCls = 0x601e8a
I/WifiNative-HAL( 1030): Could not start hal
D/WifiNative-wlan0( 1030): doBoolean: STA_AUTOCONNECT 1
D/WifiNative-wlan0( 1030): STA_AUTOCONNECT 1: returned true
D/WifiNative-wlan0( 1030): doBoolean: DRIVER BTCOEXSCAN-STOP
I/wpa_supplicant( 6321): wpa_driver_nl80211_ext_driver_cmd BTCOEXSCAN-STOP
D/WifiNative-wlan0( 1030): DRIVER BTCOEXSCAN-STOP: returned true
E/BluetoothAdapterService( 6276): File transfer profiles supported!!
D/HeadsetStateMachine( 6276): max_hf_connections = 1
I/bluedroid-qcom( 6276): get_profile_interface handsfree
V/ToneGenerator( 6276): ToneGenerator constructor: streamType=8, volume=1.000000
D/WfdsService( 1953): Supplicant Connection state is changed : true
D/WfdsService( 1953): DefaultState - WIFI_SUPPLICANT_CONNECTED
D/WfdsService( 1953): Set the WFDS Monitor: true
V/AudioPolicyService(  311): registerClient() client 0xb558afc0, uid 1002
V/AudioPolicyManager(  311): getOutput() device 2, stream 8, samplingRate 0, format 0, channelMask 3, flags 0
V/AudioPolicyManagerEx(  311): AudioPolicyManagerEx: getOutputForDevice
V/AudioPolicyManagerEx(  311): getOutput() returns output 2
V/AudioSystem( 6276): getOutputSamplingRate() no output descriptor for output 2 in gOutputs
D/WifiNative-wlan0( 1030): doBoolean: DRIVER RXFILTER-STOP
I/wpa_supplicant( 6321): wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
V/AudioFlinger(  311): registerClient() client 0xb1433058, pid 6276
D/WfdsMonitor( 1953): WfdsMonitorThread create
D/WfdsMonitor( 1953): WFDS Monitor is created and started
D/WfdsService( 1953): WiFi: Supplicant connection re-established
V/AudioSystem(  311): ioConfigChanged() event 0, ioHandle 2
V/AudioSystem(  311): ioConfigChanged() opening already existing output! 2
V/AudioSystem( 1030): ioConfigChanged() event 0, ioHandle 2
V/AudioSystem( 1030): ioConfigChanged() opening already existing output! 2
V/AudioSystem(  311): ioConfigChanged() event 0, ioHandle 4
V/AudioSystem(  311): ioConfigChanged() opening already existing output! 4
V/AudioSystem( 1457): ioConfigChanged() event 0, ioHandle 2
V/AudioSystem( 1457): ioConfigChanged() opening already existing output! 2
V/AudioSystem( 3292): ioConfigChanged() event 0, ioHandle 2
V/AudioSystem( 3292): ioConfigChanged() opening already existing output! 2
V/AudioSystem( 3292): ioConfigChanged() event 0, ioHandle 4
V/AudioSystem( 3292): ioConfigChanged() opening already existing output! 4
V/AudioSystem( 1852): ioConfigChanged() event 0, ioHandle 2
V/AudioSystem( 1852): ioConfigChanged() opening already existing output! 2
V/AudioSystem( 1030): ioConfigChanged() event 0, ioHandle 4
V/AudioSystem( 1852): ioConfigChanged() event 0, ioHandle 4
V/AudioSystem( 1030): ioConfigChanged() opening already existing output! 4
V/AudioSystem( 1852): ioConfigChanged() opening already existing output! 4
V/AudioSystem( 1457): ioConfigChanged() event 0, ioHandle 4
V/AudioSystem( 1457): ioConfigChanged() opening already existing output! 4
V/AudioSystem( 6276): ioConfigChanged() event 0, ioHandle 2
W/Settings( 6088): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiNative-wlan0( 1030): DRIVER RXFILTER-STOP: returned true
D/WifiNative-wlan0( 1030): doBoolean: DRIVER RXFILTER-REMOVE 3
I/wpa_supplicant( 6321): wpa_driver_nl80211_ext_driver_cmd RXFILTER-REMOVE 3
D/WifiNative-wlan0( 1030): DRIVER RXFILTER-REMOVE 3: returned true
D/WifiNative-wlan0( 1030): doBoolean: DRIVER RXFILTER-START
I/wpa_supplicant( 6321): wpa_driver_nl8,0211_ext_driver_cmd RXFILTER-START
D/WifiNative-wlan0( 1030): DRIVER RXFILTER-START: returned true
D/WifiNative-wlan0( 1030): doBoolean: DRIVER RXFILTER-STOP
I/wpa_supplicant( 6321): wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
D/WifiNative-wlan0( 1030): DRIVER RXFILTER-STOP: returned true
D/WifiNative-wlan0( 1030): doBoolean: DRIVER RXFILTER-REMOVE 2
I/wpa_supplicant( 6321): android_multicast_filter_startstop : multicast filter set
D/WifiNative-wlan0( 1030): DRIVER RXFILTER-REMOVE 2: returned true
D/WifiNative-wlan0( 1030): doBoolean: DRIVER RXFILTER-START
I/wpa_supplicant( 6321): wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
,D/WifiNative-wlan0( 1030): DRIVER RXFILTER-START: returned true
E/WifiNative: ( 1030): [275,235,192 us] RECONNECT  stack:logDbg - reconnect - enter - invokeEnterMethods - performTransitions
D/WifiNative-wlan0( 1030): doBoolean: RECONNECT
V/ToneGenerator( 6276): Create Track: 0xb4928a80
V/AudioTrack( 6276): set(): streamType 8, sampleRate 0, format 0x1, channelMask 0x1, frameCount 0, flags #4, notificationFrames 0, sessionId 0, transferType 1
V/AudioTrack( 6276): set() streamType 8, sampleRate 0, format 1, frameCount 0, flags 0004
V/AudioPolicyManager(  311): getOutputForAttr() usage=3, content=4, tag= flags=00000000
V/AudioPolicyManager(  311): getOutputForAttr() device 2, samplingRate 0, format 0, channelMask 3, flags 0
V/AudioPolicyManagerEx(  311): AudioPolicyManagerEx: getOutputForDevice
V/AudioPolicyManagerEx(  311): getOutput() returns output 2
V/AudioSystem( 6276): getOutputSamplingRate() no output descriptor for output 2 in gOutputs
D/WifiNative-wlan0( 1030): RECONNECT: returned true
D/WifiNative-wlan0( 1030): doString: [STATUS]
D/WifiNative-wlan0( 1030):    returned wpa_state=SCANNING p2p_device_address=02:9a:02:7b:60:ac address=c4:9a:02:7b:60:ac uuid=530d3fd0-1ba3-5409-a336-ff4e42af59a2
D/WifiNative-wlan0( 1030): doBoolean: DRIVER SETSUSPENDMODE 1
I/wpa_supplicant( 6321): wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 1
D/WifiNative-wlan0( 1030): DRIVER SETSUSPENDMODE 1: returned true
D/WifiNative-wlan0( 1030): doBoolean: SET ps 1
D/WifiNative-wlan0( 1030): SET ps 1: returned true
D/LGWifiP2pService( 1030): P2pDisabledState{ when=0 what=131203 target=com.android.internal.util.StateMachine$SmHandler }
E/CtrlSupplicant( 1953): Access OK "@android:wpa_wlan0"
E/CtrlSupplicant( 1953): Succeed to open control connection
E/CtrlSupplicant( 1953): Succeed to open monitor connection
D/WifiMonitor( 1030): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
E/WifiMonitor( 1030): WifiMonitor:wlan0 cnt=1 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
D/CommandListener(  307): Setting iface cfg
D/CommandListener(  307): Trying to bring up p2p0
D/WfdsMonitor( 1953): Supplicant connection established
D/WfdsService( 1953): Connected to the supplicant for wfds
D/WifiMonitor( 1030): startMonitoring(p2p0) with mConnected = true
V/AudioSystem( 6276): ioConfigChanged() new output samplingRate 48000, format 0x5 channel mask 0x3 frameCount 960 latency 50
D/LGWifiP2pService( 1030): P2pEnablingState
D/LGWifiP2pService( 1030): P2pEnablingState{ when=0 what=147457 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1030): P2p socket connection successful
D/LGWifiP2pService( 1030): P2pEnabledState
,I/AudioFlinger(  311): isAudioPlaybackHookOn() false
V/AudioSystem( 6276): ioConfigChanged() event 0, ioHandle 4
V/AudioSystem( 6276): ioConfigChanged() new output samplingRate 48000, format 0x1 channel mask 0x3 frameCount 960 latency 80
V/AudioPolicyManager(  311): getOutputForAttr() usage=3, content=4, tag= flags=00000000
V/AudioPolicyManager(  311): getOutputForAttr() device 2, samplingRate 48000, format 1, channelMask 1, flags 4
V/AudioPolicyManagerEx(  311): AudioPolicyManagerEx: getOutputForDevice
V/AudioPolicyManagerEx(  311): getOutput() returns output 2
V/AudioSystem( 6276): getLatency() output 2, latency 50
V/AudioSystem( 6276): getFrameCount() output 2, frameCount 960
V/AudioTrack( 6276): createTrack_l() output 2 afLatency 50
D/LGWifiP2pService( 1030): sending p2p connection changed broadcast
V/AudioFlinger(  311): [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
V/AudioFlinger(  311): [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
V/AudioFlinger(  311): [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
V/AudioFlinger(  311): [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
V/AudioFlinger(  311): createTrack() lSessionId: 16
D/WifiHS20( 1030): hidePasspointNotification off =false
E/BluetoothAdapterService( 6276): File transfer profiles supported!!
W/Settings( 1030): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1030): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1030): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
I/StatusBar.NetworkController( 1457): networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1457): mWifiConnected = false, mWifiLevel = 0
E/WifiStateMachine( 1030):  DisconnectedState CMD_SET_OPERATIONAL_MODE 1 0
D/WifiNative-p2p0( 1030): doBoolean: SET persistent_reconnect 1
D/StatusBar.NetworkController( 1457): refreshViews: Data not connected!! Set no data type icon / Roaming
V/WfdStateTracker( 1953): WfdStateTracker handleDirectStateChangedEvent: 2
D/WfdsService( 1953): WifiP2pState is changed : true
D/WfdsService( 1953): Receive the WFDS_ENABLE Method
D/WfdsService( 1953): Set the WFDS Monitor: true
D/WifiScanningService( 1030): SCAN_AVAILABLE : 3
D/WfdsService( 1953): Connected to the supplicant for wfds
D/RttService( 1030): SCAN_AVAILABLE : 3
D/WfdsJNI ( 1953): doCommand: WFDS_SET TRUE
I/wpa_supplicant( 6321): WFDS: wfds_supplicant_wfds_cmd: cmd = SET TRUE
D/RttService( 1030): DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiScanningService( 1030): DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
I/WifiNative-HAL( 1030): startHal
D/WfdsJNI ( 1953): doCommand: WFDS_GET_MAC_ADDRESS
I/wpa_supplicant( 6321): WFDS: wfds_supplicant_wfds_cmd: cmd = GET_MAC_ADDRESS
D/WfdsJNI ( 1953): doCommand: IFNAME=wlan0 GET_CAPABILITY channels
D/WfdsService( 1953): selectPreferredScanChannel [36]
D/WfdsService( 1953): STATE : WfdsEnabledState - enter: this device mac 02:9a:02:7b:60:ac
,E/WifiStateMachine( 1030):  DisconnectedState CMD_START_DRIVER 0 0
D/WifiNative-p2p0( 1030): SET persistent_reconnect 1: returned true
E/wifi    ( 1030): getStaticLongField sWifiHalHandle 0x94f6b99c
E/WifiHAL ( 1030): Could not connect handle
D/wifi    ( 1030): halHandle = 0x0, mVM = 0xb487c280, mCls = 0x801d16
I/WifiNative-HAL( 1030): Could not start hal
E/WifiScanningService( 1030): could not start HAL
D/WifiNative-p2p0( 1030): doBoolean: SET device_name G3-1
D/WifiNative-p2p0( 1030): SET device_name G3-1: returned true
D/LGWifiP2pService( 1030): [LGE_P2P] initializeP2pSettings() check postfix
D/LGWifiP2pService( 1030): before postfix = G3-1
D/WifiServerServiceExt( 1030): postfix byte check : 4
D/LGWifiP2pService( 1030): after postfix = G3-1
D/WifiNative-p2p0( 1030): doBoolean: SET p2p_ssid_postfix -G3-1
D/WifiNative-p2p0( 1030): SET p2p_ssid_postfix -G3-1: returned true
D/WifiNative-p2p0( 1030): doBoolean: SET device_type 10-0050F204-5
,D/WifiNative-p2p0( 1030): SET device_type 10-0050F204-5: returned true
D/WifiNative-p2p0( 1030): doBoolean: SET config_methods virtual_push_button physical_display keypad
D/WifiNative-p2p0( 1030): SET config_methods virtual_push_button physical_display keypad: returned true
D/WifiNative-p2p0( 1030): doBoolean: P2P_SET conc_pref p2p
D/WifiNative-p2p0( 1030): P2P_SET conc_pref p2p: returned true
D/WifiNative-HAL( 1030): p2pGetDeviceAddress
D/WfdsService( 1953): WIFI_P2P_CONNECTION_CHANGED_ACTION
E/WifiStateMachine( 1030):  ConnectModeState CMD_START_DRIVER 0 0
D/WfdsService( 1953): isConnected: false
D/WifiNative-HAL( 1030): p2pGetDeviceAddress returning 02:9a:02:7b:60:ac
E/WifiStateMachine( 1030):  DriverStartedState CMD_START_DRIVER 0 0
E/WifiStateMachine( 1030):  DisconnectedState what:132106 1 0
E/WifiStateMachine( 1030):  ConnectModeState what:132106 1 0
E/WifiStateMachine( 1030):  DriverStartedState what:132106 1 0
I/WifiServerServiceExt( 1030): setWifiDualbandAPConnection band : 1
E/wpa_supplicant( 6321): nWIFIDualbandAPConnection: 1
D/LGWifiP2pService( 1030): DeviceAddress: 02:9a:02:7b:60:ac
D/WifiNative-p2p0( 1030): doBoolean: P2P_FLUSH
D/WifiNative-p2p0( 1030): P2P_FLUSH: returned true
D/WifiNative-p2p0( 1030): doBoolean: P2P_SERVICE_FLUSH
I/WfdStateTracker( 1953): handleP2pThisDeviceChanged
D/WfdsService( 1953): WIFI_P2P_THIS_DEVICE_CHANGED_ATCION
D/WifiNative-p2p0( 1030): P2P_SERVICE_FLUSH: returned true
D/WifiNative-p2p0( 1030): doString: [LIST_NETWORKS]
D/WifiNative-p2p0( 1030):    returned OK
D/WifiNative-p2p0( 1030): doBoolean: SAVE_CONFIG
D/WifiNative-p2p0( 1030): SAVE_CONFIG: returned false
V/AudioTrack( 6276): AUDIO_OUTPUT_FLAG_FAST successful; frameCount 480
D/LGWifiP2pService( 1030): sending p2p persistent groups changed broadcast
D/LGWifiP2pService( 1030): InactiveState
V/AudioFlinger(  311): acquiring 16 from 6276, for 6276
V/AudioFlinger(  311):  added new entry for 16
D/LGWifiP2pService( 1030): InactiveState{ when=-1ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1030): P2pEnabledState{ when=-1ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
V/ToneGenerator( 6276): ToneGenerator INIT OK, time: 275271
D/BluetoothAdapterService( 6276): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@5b2a254
D/WifiNative-p2p0( 1030): doBoolean: DRIVER COUNTRY CZ
D/HeadsetStateMachine( 6276): Enter Disconnected: -2, size: 0
D/HeadsetPhoneState( 6276): [BTUI] listenForPhoneState : start = false
D/LGBluetoothHfpManager( 6276): [BTUI] listenForMultiSimPhoneState : start = false
D/HeadsetStateMachine( 6276): [BTUI] change sampling rate to 8000 when device is disconnected
D/WfdsService( 1953): Update P2p Interface State: 3
E/BluetoothAdapterService( 6276): File transfer profiles supported!!
,V/AudioFlinger(  311): setParameters(): io 0, keyvalue bt_samplerate=8000, calling pid 6276
D/BluetoothAdapterService( 6276): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@5b2a254
D/audio_hw_primary(  311): adev_set_parameters: enter: bt_samplerate=8000
V/voice   (  311): voice_set_parameters: enter: bt_samplerate=8000
V/compress_voip(  311): voice_extn_compress_voip_set_parameters: enter: bt_samplerate=8000
V/compress_voip(  311): voice_extn_compress_voip_set_parameters: exit
V/voice   (  311): voice_set_parameters: exit with code(0)
V/msm8974_platform_lge(  311): LGE_platform_set_parameters: enter: bt_samplerate=8000
V/msm8974_platform(  311): platform_set_parameters: enter: bt_samplerate=8000
V/msm8974_platform(  311): platform_set_parameters: exit with code(0)
V/lge_audio_loopback(  311): lge_platform_set_loopback_parameters: enter: 
V/audio_hw_primary(  311): adev_set_parameters: exit with code(0)
E/audio_a2dp_hw(  311): adev_set_parameters: ERROR: set param called even when stream out is null
V/ToneGenerator( 6276): ToneGenerator destructor
V/ToneGenerator( 6276): stopTone
V/ToneGenerator( 6276): Delete Track: 0xb4928a80
V/AudioTrack( 6276): ~AudioTrack, releasing session id from 6276 on behalf of 6276
V/AudioFlinger(  311): releasing 16 from 6276 for 6276
V/AudioFlinger(  311):  decremented refcount to 0
V/AudioFlinger(  311): purging stale effects
V/AudioPolicyService(  311): AudioCommandThread() adding release output 2
V/AudioPolicyService(  311): inserting command: 6 at index 0, num commands 0
V/AudioPolicyService(  311): AudioCommandThread() waking up
V/AudioPolicyService(  311): AudioCommandThread() processing release output 2
V/AudioPolicyManager(  311): releaseOutput() 2
V/AudioPolicyService(  311): AudioCommandThread() going to sleep
V/AudioFlinger(  311): PlaybackThread::Track destructor
V/AudioFlinger(  311): removeClient_l() pid 6276, calling pid 311
I/wpa_supplicant( 6321): wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
I/wpa_supplicant( 6321): p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
D/BluetoothA2dp( 1030): Proxy object connected
I/wpa_supplicant( 6321): [LGE_PATCH] driver_cmd() country:CZ
I/wpa_supplicant( 6321): p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
D/A2dpService( 6276): Received start request. Starting profile...
I/wpa_supplicant( 6321): p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
I/BluetoothAvrcpServiceJni( 6276): classInitNative: succeeds
D/WifiNative-p2p0( 1030): DRIVER COUNTRY CZ: returned true
V/Avrcp   ( 6276): make
E/WifiStateMachine( 1030):  DisconnectedState what:132096 -100 0
D/Avrcp   ( 6276): [BTUI] Use Native AVRCP : init jni
I/bluedroid-qcom( 6276): get_profile_interface avrcp
E/WifiStateMachine( 1030):  ConnectModeState what:132096 -100 0
E/WifiStateMachine( 1030):  DriverStartedState what:132096 -100 0
I/WifiServerServiceExt( 1030): set CMD_DISCONNECT_RSSI_LVL : -100
E/wpa_supplicant( 6321): disconnect_rssi_lvl: -100
D/WfdsMonitor( 1953): Event [CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
D/WfdsMonitor( 1953): Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
D/WfdsMonitor( 1953): Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
D/WifiMonitor( 1030): Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
E/WifiMonitor( 1030): WifiMonitor:p2p0 cnt=2 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
E/WifiMonitor( 1030): handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
E/WifiMonitor( 1030): handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
D/WifiMonitor( 1030): Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
E/WifiMonitor( 1030): WifiMonitor:p2p0 cnt=3 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
E/WifiMonitor( 1030): handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
E/WifiMonitor( 1030): handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
D/WifiMoni,tor( 1030): Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
E/WifiMonitor( 1030): WifiMonitor:p2p0 cnt=4 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
E/WifiMonitor( 1030): handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
E/WifiMonitor( 1030): handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
D/LGWifiP2pService( 1030): InactiveState{ when=-11ms what=139287 arg2=1 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1030): P2pEnabledState{ when=-13ms what=139287 arg2=1 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1030): DefaultState{ when=-13ms what=139287 arg2=1 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1030): InactiveState{ when=-13ms what=139285 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1030): P2pEnabledState{ when=-14ms what=139285 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1030): DefaultState{ when=-14ms what=139285 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1030): InactiveState{ when=-14ms what=139287 arg2=1 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1030): P2pEnabledState{ when=-14ms what=139287 arg2=1 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1030): DefaultState{ when=-14ms what=139287 arg2=1 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1030): InactiveState{ when=-14ms what=139283 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1030): P2pEnabledState{ when=-14ms what=139283 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1030): DefaultState{ when=-14ms what=139283 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiServerServiceExt( 1030): No p2p device connected
W/WfdsService( 1953): DefaultState - msg [9441285] is not handled
E/WifiStateMachine( 1030):  DisconnectedState CMD_SET_COUNTRY_CODE 1 0 cz
E/WifiStateMachine( 1030):  ConnectModeState CMD_SET_COUNTRY_CODE 1 0 cz
E/WifiStateMachine( 1030):  DriverStartedState CMD_SET_COUNTRY_CODE 1 0 cz
D/WifiNative-wlan0( 1030): doBoolean: DRIVER COUNTRY CZ
I/wpa_supplicant( 6321): wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
I/wpa_supplicant( 6321): wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
I/wpa_supplicant( 6321): [LGE_PATCH] driver_cmd() country:CZ
I/wpa_supplicant( 6321): p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
I/wpa_supplicant( 6321): p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
D/WfdsMonitor( 1953): Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
D/WfdsMonitor( 1953): Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
D/WifiMonitor( 1030): Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
E/WifiMonitor( 1030): WifiMonitor:wlan0 cnt=5 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
E/WifiMonitor( 1030): handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
E/WifiMonitor( 1030): handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
D/WifiMonitor( 1030): Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
E/WifiMonitor( 1030): WifiMonitor:p2p0 cnt=6 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
E/WifiMonitor( 1030): handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
E/WifiMonitor( 1030): handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
D/WifiMonitor( 1030): Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
E/WifiMonitor( 1030): WifiMonitor:p2p0 cnt=7 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
E/WifiMonitor( 1030): handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
E/WifiMonitor( 1030): handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
D/WifiNative-wlan0( 1030): DRIVER COUNTRY CZ: returned true
E/WifiStateMachine( 1030):  DisconnectedState CMD_SET_FREQUENCY_BAND 0 0
E/WifiStateMachine( 1030):  ConnectModeState CMD_SET_FREQUENCY_BAND 0 0
E/WifiStateMachine( 1030):  DriverStartedState CMD_SET_FREQUENCY_BAND 0 0
D/WifiNative-wlan0( 1030): doBoolean: DRIVER SETBAND 0
I/wpa_supplicant( 6321): wpa_driver_nl80211_ext_driver_cmd SETBAND 0 - interface name wlan0
I/wpa_supplicant( 6321): wlan0: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
D/WifiMonitor( 1030): Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN]
E/WifiMonitor( 1030): WifiMonitor:wlan0 cnt=8 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
E/WifiMonitor( 1030): handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
E/WifiMonitor( 1030): handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
D/LGWifiP2pService( 1030): InactiveState{ when=-2ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1030): P2pEnabledState{ when=-2ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0( 1030): DRIVER SETBAND 0: returned true
D/WifiNative-wlan0( 1030): doBoolean: BSS_FLUSH 0
D/WifiNative-wlan0( 1030): BSS_FLUSH 0: returned true
D/WifiNative-wlan0( 1030): doBoolean: SCAN
D/WifiNative-wlan0( 1030): SCAN: returned false
E/WifiStateMachine( 1030):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 1 0 rt=275282  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
W/Settings( 1030): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1030): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1030): NETWORK_STATE_CHANGED_ACTION [SCANNING]
I/StatusBar.NetworkController( 1457): networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1457): mWifiConnected = false, mWifiLevel = 0
E/WifiStateMachine( 1030):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 1 0 rt=275285  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
E/WifiStateMachine( 1030):  DisconnectedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
E/WifiStateMachine( 1030):  ConnectModeState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
E/WifiStateMachine( 1030):  DriverStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
E/WifiStateMachine( 1030):  SupplicantStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
E/WifiStateMachine( 1030):  DefaultState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
D/WifiService( 1030): New client listening to asynchronous messages
D/WifiServerServiceExt( 1030): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1030): setSupplicantStateSCANNING
V/AudioManager( 6276): registerRemoteController: size of Media player list: 0
D/StatusBar.NetworkController( 1457): refreshViews: Data not connected!! Set no data type icon / Roaming
E/AudioManager( 6276): No RCC entry present to update
E/RemoteController( 6276): Cannot set synchronization mode on an unregistered RemoteController
,I/BluetoothAvrcpQcomServiceJni( 6276): classInitQcomNative: succeeds
D/LGBluetoothAvrcpQcomAdapter( 6276): [BTUI] Use QCOM AVRCP 1.5 : init jni, browsing = false
I/BluetoothAvrcpQcomServiceJni( 6276): initQcomNative: succeeds
V/LGMDMManager( 6276): Create singleton instance
I/BluetoothAdapterState( 6276): Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
D/LGBluetoothAvrcpQcomAdapter( 6276): [BTUI] [+] updateMediaPlayerInfo
E/ActivityThread( 6341): Failed to find provider info for com.lge.lgaccount.provider
W/LG Account v2.2( 6341): No ProfileInfo entries
I/LG Account v2.2( 6341): isEnabled: false
I/Feature ( 6341): [Lifetracker]ver: 4.21.112(40211120)
I/Feature ( 6341): [Lifetracker]Country: EU
I/Feature ( 6341): [Lifetracker]Operator: OPEN
I/Feature ( 6341): [Lifetracker]Ranking support: false
I/Feature ( 6341): [Lifetracker]Comfort support: false
I/Feature ( 6341): [Lifetracker]Accessory: true
I/Feature ( 6341): [Lifetracker]Health device: true
I/Feature ( 6341): [Lifetracker]Extra Pedometer: false
I/Feature ( 6341): [Lifetracker]Blood glucose device: false
I/Feature ( 6341): [Lifetracker]Device Number: 3
,V/SIM_STK ( 1030): Menu title from STK is T-Mobile
V/SIM_STK ( 1030): Menu title from STK is T-Mobile
I/ActivityManager( 1030): Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=6388 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,D/BluetoothPermissionRequest( 6308): onReceive
D/LGBluetoothFeatureConfig( 6308):  get() - isFeatureLoaded : false
W/FormManager( 6359): Network not available. Please check & try again.
V/FormManager( 6359): Network unavailable.
V/FormManager( 6359): Network unavailable.
,D/BluetoothManagerService( 1030): Message: 20
D/BluetoothManagerService( 1030): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@12bc21a6:true
D/LGBluetoothResetSettingReceiver( 6308): return without doing reset settings.
I/ActivityManager( 1030): Killing 5509:com.lge.appbox.client/u0a11 (adj 15): empty #17
W/libprocessgroup( 1030): failed to open /acct/uid_10011/pid_5509/cgroup.procs: No such file or directory
,E/WifiMonitor( 1030): WifiMonitor:wlan0 cnt=9 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
E/WifiMonitor( 1030): handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
D/WifiMonitor( 1030): Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
E/wpa_supplicant( 6321): USIM:  scard_init function
E/WifiMonitor( 1030): WifiMonitor:wlan0 cnt=10 dispatchEvent: WPS-AP-AVAILABLE 
W/WifiMonitor( 1030): couldn't identify event type - WPS-AP-AVAILABLE 
I/wpa_supplicant( 6321): Trying to associate with SSID 'NG700'
,D/WifiMonitor( 1030): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
E/WifiMonitor( 1030): WifiMonitor:wlan0 cnt=11 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
E/WifiStateMachine( 1030):  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=0 bcn=0
E/WifiStateMachine( 1030):  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=0 bcn=0
E/WifiStateMachine( 1030):  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=0 bcn=0
E/WifiStateMachine( 1030):  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=0 bcn=0
I/WifiNative-HAL( 1030): startHal
E/wifi    ( 1030): getStaticLongField sWifiHalHandle 0x9895c8cc
E/WifiHAL ( 1030): Could not connect handle
D/wifi    ( 1030): halHandle = 0x0, mVM = 0xb487c280, mCls = 0xa01892
I/WifiNative-HAL( 1030): Could not start hal
D/WifiNative-wlan0( 1030): doString: [BSS RANGE=0- MASK=0x21987]
W/ActivityManager( 1030): getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
I/ActivityManager( 1030): Killing 5530:com.android.contacts/u0a19 (adj 15): empty #17
D/LGBluetoothAvrcpQcomAdapter( 6276): [BTUI] installed app name: Music
,D/LGBluetoothAvrcpQcomAdapter( 6276): [BTUI] installed app name: Google Play Music
D/LGBluetoothAvrcpQcomAdapter( 6276): [BTUI] === MediaPlayerInfo (playerId:0) ===
D/LGBluetoothAvrcpQcomAdapter( 6276): [BTUI]          displayName: Music
D/LGBluetoothAvrcpQcomAdapter( 6276): [BTUI]          packageName: com.lge.music
D/LGBluetoothAvrcpQcomAdapter( 6276): [BTUI]          playState: 2 (PAUSED)
D/LGBluetoothAvrcpQcomAdapter( 6276): [BTUI] === MediaPlayerInfo (playerId:1) ===
D/LGBluetoothAvrcpQcomAdapter( 6276): [BTUI]          displayName: Google Play Music
D/LGBluetoothAvrcpQcomAdapter( 6276): [BTUI]          packageName: com.google.android.music
D/LGBluetoothAvrcpQcomAdapter( 6276): [BTUI]          playState: 2 (PAUSED)
D/LGBluetoothAvrcpQcomAdapter( 6276): [BTUI] [-] updateMediaPlayerInfo
I/BluetoothA2dpServiceJni( 6276): classInitNative
I/BluetoothA2dpServiceJni( 6276): classInitNative: succeeds
D/A2dpStateMachine( 6276): make
I/bluedroid-qcom( 6276): get_profile_interface a2dp
I/GKI_LINUX( 6276): gki_task_entry task_id=2 [A2DP-MEDIA] starting
I/LGBluetoothA2dpServiceJni( 6276): classInitNative: succeeds
I/LGBluetoothA2dpAdapter( 6276): [BTUI] getInstance : create [LGBluetoothA2dpAdapter]
D/BluetoothAdapterService( 6276): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@5b2a254
I/BluetoothHidServiceJni( 6276): classInitNative: succeeds
D/A2dpStateMachine( 6276): Enter Disconnected: -2
D/HidService( 6276): Received start request. Starting profile...
I/bluedroid-qcom( 6276): get_profile_interface hidhost
D/BluetoothAdapterService( 6276): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@5b2a254
,I/BluetoothHealthServiceJni( 6276): classInitNative: succeeds
,D/HealthService( 6276): Received start request. Starting profile...
I/bluedroid-qcom( 6276): get_profile_interface health
I/LGBluetoothHealthServiceJni( 6276): classInitNative: succeeds
D/BluetoothAdapterService( 6276): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@5b2a254
D/HeadsetStateMachine( 6276): Proxy object connected
D/LGBluetoothHfpAdapter( 6276): [BTUI] queryPhoneState
D/LGBluetoothHfpAdapter( 6276): Try to query the phonestate on bind
D/BluetoothPhoneService.BluetoothLTECall( 1852):  call mBluetoothHeadset.phoneStateChanged()
W/BluetoothHeadset( 1852): Proxy not attached to service
D/BluetoothHeadset( 1852): java.lang.Throwable
D/BluetoothHeadset( 1852): 	at android.bluetooth.BluetoothHeadset.phoneStateChanged(BluetoothHeadset.java:826)
D/BluetoothHeadset( 1852): 	at com.android.phone.BluetoothPhoneService$BluetoothLTECall.handleQueryPhoneState(BluetoothPhoneService.java:1527)
D/BluetoothHeadset( 1852): 	at com.android.phone.BluetoothPhoneService$BluetoothLTECall.access$700(BluetoothPhoneService.java:1360)
D/BluetoothHeadset( 1852): 	at com.android.phone.BluetoothPhoneService$1.handleMessage(BluetoothPhoneService.java:268)
D/BluetoothHeadset( 1852): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/BluetoothHeadset( 1852): 	at android.os.Looper.loop(Looper.java:135)
D/BluetoothHeadset( 1852): 	at android.app.ActivityThread.main(ActivityThread.java:5274)
D/BluetoothHeadset( 1852): 	at java.lang.reflect.Method.invoke(Native Method)
D/BluetoothHeadset( 1852): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/BluetoothHeadset( 1852): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
D/BluetoothHeadset( 1852): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
I/BluetoothPanServiceJni( 6276): classInitNative(L105): succeeds
D/PanService( 6276): Received start request. Starting profile...
D/BluetoothPanServiceJni( 6276): initializeNative(L110): pan
I/bluedroid-qcom( 6276): get_profile_interface pan
D/PCSuite ( 6388): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,I/wpa_supplicant( 6321): wlan0: Associated with c0:ff:d4:d3:aa:48
D/WifiMonitor( 1030): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
E/WifiMonitor( 1030): WifiMonitor:wlan0 cnt=12 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
,D/WifiMonitor( 1030): Event [IFNAME=wlan0 Associated with c0:ff:d4:d3:aa:48]
E/WifiMonitor( 1030): WifiMonitor:wlan0 cnt=13 dispatchEvent: Associated with c0:ff:d4:d3:aa:48
D/WifiMonitor( 1030): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1030): WifiMonitor:wlan0 cnt=14 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
,W/libprocessgroup( 1030): failed to open /acct/uid_10019/pid_5530/cgroup.procs: No such file or directory
,E/WifiStateMachine( 1030):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 11 0 rt=275664  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
D/WifiMonitor( 1030): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
I/wpa_supplicant( 6321): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
E/WifiMonitor( 1030): WifiMonitor:wlan0 cnt=15 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
I/wpa_supplicant( 6321): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
,D/WifiMonitor( 1030): Event [IFNAME=wlan0 WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]]
E/WifiMonitor( 1030): WifiMonitor:wlan0 cnt=16 dispatchEvent: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
W/WifiMonitor( 1030): couldn't identify event type - WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
D/WifiMonitor( 1030): Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]]
E/WifiMonitor( 1030): WifiMonitor:wlan0 cnt=17 dispatchEvent: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
E/WifiMonitor( 1030): handleEvent 1  Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
D/Tethering( 1030): sendTetherStateChangedBroadcast 1, 0, 0
I/LGBluetoothPanAdapter( 6276): [BTUI] getInstance : create [LGBluetoothPanAdapter]
D/BluetoothAdapterService( 6276): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@5b2a254
D/WifiMonitor( 1030): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1030): WifiMonitor:wlan0 cnt=18 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
I/BtGatt.JNI( 6276): classInitNative(L901): classInitNative: Success!
I/StatusBar.NetworkController( 1457): networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1457): mWifiConnected = false, mWifiLevel = 0
,E/WifiStateMachine( 1030):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 11 0 rt=275686  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
E/WifiStateMachine( 1030):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 12 0 rt=275688  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
E/WifiStateMachine( 1030):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 12 0 rt=275689  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
D/StatusBar.NetworkController( 1457): refreshViews: Data not connected!! Set no data type icon / Roaming
D/BtGatt.DebugUtils( 6276): handleDebugAction() action=null
E/WifiStateMachine( 1030):  DisconnectedState CMD_ASSOCIATED_BSSID 13 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=275691
D/BtGatt.GattService( 6276): Received start request. Starting profile...
D/BtGatt.GattService( 6276): start()
I/bluedroid-qcom( 6276): get_profile_interface gatt
E/WifiStateMachine( 1030):  ConnectModeState CMD_ASSOCIATED_BSSID 13 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=275691
E/WifiStateMachine( 1030):  DriverStartedState CMD_ASSOCIATED_BSSID 13 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=275691
E/WifiStateMachine( 1030):  SupplicantStartedState CMD_ASSOCIATED_BSSID 13 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=275692
D/BtGatt.AdvertiseManager( 6276): advertise manager created
E/WifiStateMachine( 1030):  DefaultState CMD_ASSOCIATED_BSSID 13 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=275692
E/WifiStateMachine( 1030):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 14 0 rt=275694  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: FOUR_WAY_HANDSHAKE
W/Settings( 1030): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1030): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1030): NETWORK_STATE_CHANGED_ACTION [SCANNING]
I/StatusBar.NetworkController( 1457): networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1457): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1457): refreshViews: Data not connected!! Set no data type icon / Roaming
,W/Settings( 1030): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1030): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1030): NETWORK_STATE_CHANGED_ACTION [CONNECTING]
W/Settings( 1030): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1030): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1030): NETWORK_STATE_CHANGED_ACTION [CONNECTING]
I/StatusBar.NetworkController( 1457): networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1457): mWifiConnected = false, mWifiLevel = 0
,E/WifiStateMachine( 1030):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 14 0 rt=275716  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: FOUR_WAY_HANDSHAKE
D/StatusBar.NetworkController( 1457): refreshViews: Data not connected!! Set no data type icon / Roaming
E/WifiStateMachine( 1030):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 15 0 rt=275716  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: GROUP_HANDSHAKE
E/WifiStateMachine( 1030):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 15 0 rt=275717  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: GROUP_HANDSHAKE
E/WifiStateMachine( 1030):  DisconnectedState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=275718
E/WifiStateMachine( 1030):  ConnectModeState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=275718
D/WifiNative-wlan0( 1030): doString: [STATUS]
D/WifiMonitor( 1030): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1030): WifiMonitor:wlan0 cnt=19 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/BluetoothAdapterService( 6276): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@5b2a254
I/StatusBar.NetworkController( 1457): networkInfo=[type: WIFI[], state: CONNECTING/AUTHENTICATING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1457): mWifiConnected = false, mWifiLevel = 0
W/Settings( 1030): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1030): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1030): NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
D/HeadsetStateMachine( 6276): Disconnected process message: 10, size: 0
D/StatusBar.NetworkController( 1457): refreshViews: Data not connected!! Set no data type icon / Roaming
D/HeadsetPhoneState( 6276): sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
D/WifiNative-wlan0( 1030):    returned bssid=c0:ff:d4:d3:aa:48 ssid=NG700 id=0 mode=station pairwise_cipher=CCMP group_cipher=CCMP key_mgmt=WPA2-PSK wpa_state=COMPLETED p2p_device_address=02:9a:02:7b:60:ac address=c4:9a:02:7b:60:ac uuid=530d3fd0-1ba3-5409-a336-ff4e42af59a2
D/HeadsetStateMachine( 6276): Disconnected process message: 11, size: 0
I/WifiServiceExtension( 1030): setVHTCapabilityType  : false
D/BluetoothAdapterService( 6276): Profile still not running:com.android.bluetooth.gatt.GattService
,D/BluetoothAdapterService( 6276): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@5b2a254
I/LGBluetoothMapAdapter( 6276): [BTUI] getInstance : create [LGBluetoothMapAdapter]
V/BluetoothMapService( 6276): BluetoothMapBinder()
D/BluetoothMapService( 6276): Received start request. Starting profile...
D/BluetoothMapService( 6276): start()
V/WiFiOffLoadBroadcast( 6308): WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
D/BluetoothMapEmailSettingsLoader( 6276): Found 0 applications
D/BluetoothMapEmailAppObserver( 6276): createReceiver()
D/BluetoothMapEmailAppObserver( 6276): initObservers()
D/BluetoothMapEmailAppObserver( 6276): getEnabledAccountItems()
D/WifiService( 1030): New client listening to asynchronous messages
I/WifiServerServiceExt( 1030): wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
I/WifiServerServiceExt( 1030): setKeepAlivePacketInterval msec : 60
,D/BluetoothAdapterService( 6276): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@5b2a254
D/LGBluetoothOppAdapter( 6276): [BTUI] getInstance : create [LGBluetoothOppAdapter]
W/Settings( 1030): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1030): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1030): NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
I/StatusBar.NetworkController( 1457): networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1457): mWifiConnected = false, mWifiLevel = 0
D/BluetoothAdapterService( 6276): Profile still not running:com.android.bluetooth.gatt.GattService
W/Settings( 1030): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1030): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1030): NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
D/StatusBar.NetworkController( 1457): refreshViews: Data not connected!! Set no data type icon / Roaming
D/BluetoothAdapterService( 6276): Profile still not running:com.android.bluetooth.gatt.GattService
I/StatusBar.NetworkController( 1457): networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1457): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1457): refreshViews: Data not connected!! Set no data type icon / Roaming
,D/BluetoothAdapterService( 6276): Profile still not running:com.android.bluetooth.gatt.GattService
D/BluetoothAdapterService( 6276): Profile still not running:com.android.bluetooth.gatt.GattService
V/PanService( 6276): [BTUI] SIM Extra State :ABSENT
D/BluetoothAdapterService( 6276): Profile still not running:com.android.bluetooth.map.BluetoothMapService
V/BluetoothMapService( 6276): Handler(): got msg=1
D/BluetoothAdapterState( 6276): CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
I/bluedroid-qcom( 6276): enable
I/GKI_LINUX( 6276): gki_task_entry task_id=0 [BTU] starting
I/bt-btu  ( 6276): btu_task pending for preload complete event
I/bt_hci_bdroid( 6276): init
D/ConnectivityService( 1030): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
,D/ConnectivityService( 1030): Got NetworkAgent Messenger
D/ConnectivityService( 1030): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
D/ConnectivityService( 1030): NetworkAgent connected
E/WifiConfigStore( 1030): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/WifiNative-wlan0( 1030): doBoolean: SET_NETWORK 0 bssid any
D/WifiNative-wlan0( 1030): SET_NETWORK 0 bssid any: returned true
D/WifiNative-wlan0( 1030): doBoolean: SAVE_CONFIG
V/BluetoothFtpReceiver( 6276): BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothSapReceiver( 6276): [BTUI] checkServiceStart
V/BluetoothSapReceiver( 6276): [BTUI] region:EU country:EU
V/BluetoothSapReceiver( 6276): SapReceiver onReceive 
V/BluetoothSapReceiver( 6276): action = android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothSapReceiver( 6276):  Bluetooth Adapter state = 11
I/bt_vendor( 6276): bt-vendor : init
I/bt_vendor( 6276): bt-vendor : get_bt_soc_type
E/bt_vendor( 6276): get_bt_soc_type: Failed to get soc type
I/bt_vendor( 6276): init: Local BD Address : c0:64:73:54:3f:58
D/bt_userial_mct( 6276): userial_init
D/bt_hci_bdroid( 6276): set_power 1
I/bt_vendor( 6276): bt-vendor : BT_VND_OP_POWER_CTRL: On
I/bt_vendor( 6276): Starting hciattach daemon
I/bt_vendor( 6276): try to set true
W/sh      ( 6424): type=1400 audit(0.0:155): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6815 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
W/sh      ( 6424): type=1400 audit(0.0:156): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6815 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
D/LgDataFeature( 6308): LgDataFeature() Constructor: none
,D/WifiNative-wlan0( 1030): SAVE_CONFIG: returned true
E/WifiConfigStore( 1030): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/WifiNative-wlan0( 1030): doBoolean: SET_NETWORK 0 bssid any
D/LgDataFeature( 6308): LgDataFeature() Constructor Done, null
D/WifiNative-wlan0( 1030): SET_NETWORK 0 bssid any: returned true
D/WifiNative-wlan0( 1030): doBoolean: SAVE_CONFIG
I/qcom-bluetooth( 6425): /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  
D/WiFiOffLoadUpdatePriority( 6308): remove : truetruetrue
D/WifiNative-wlan0( 1030): SAVE_CONFIG: returned true
D/CommandListener(  307): Setting iface cfg
I/ActivityManager( 1030): Start proc com.lge.settings.easy for broadcast com.lge.settings.easy/com.lge.settings.bluetooth.LGBluetoothProfileConnectionReceiver: pid=6433 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,E/WifiStateMachine( 1030): Start Dhcp Watchdog 1
E/WifiStateMachine( 1030):  ObtainingIpState CMD_TETHER_STATE_CHANGE 0 0
D/DhcpStateMachine( 1030): StoppedState
E/WifiStateMachine( 1030):  L2ConnectedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1030):  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
D/DhcpStateMachine( 1030): StoppedState{ when=-1ms what=196609 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiStateMachine( 1030):  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
D/DhcpStateMachine( 1030): WaitBeforeStartState
E/WifiStateMachine( 1030):  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1030):  DefaultState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1030):  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 18 0 rt=275825  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine( 1030):  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 18 0 rt=275825  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine( 1030):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 18 0 rt=275826  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
D/WifiServerServiceExt( 1030): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1030): setSupplicantStateASSOCIATING
D/WifiServerServiceExt( 1030): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1030): setSupplicantStateASSOCIATED
D/WifiServerServiceExt( 1030): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1030): setSupplicantStateFOUR_WAY_HANDSHAKE
D/WifiServerServiceExt( 1030): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1030): setSupplicantStateGROUP_HANDSHAKE
E/WifiStateMachine( 1030):  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 19 0 rt=275830  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine( 1030):  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 19 0 rt=275830  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine( 1030):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 19 0 rt=275831  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
I/qcom-bluetooth( 6442): /system/etc/init.qcom.bt.sh: Transport : smd 
E/WifiStateMachine( 1030):  ObtainingIpState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:579558230] from screen [on:0 period:579558230]
E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:579558231]
I/WifiNative-HAL( 1030): startHal
E/wifi    ( 1030): getStaticLongField sWifiHalHandle 0x9895c8bc
E/WifiHAL ( 1030): Could not connect handle
D/wifi    ( 1030): halHandle = 0x0, mVM = 0xb487c280, mCls = 0x9016e6
I/WifiNative-HAL( 1030): Could not start hal
D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
,I/qcom-bluetooth( 6450): /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
D/StatusBar.NetworkController( 1457): refreshViews: Data not connected!! Set no data type icon / Roaming
D/ConnectivityService( 1030): updateNetworkScore for NetworkAgentInfo [WIFI () - 100] to 60
E/WifiStateMachine( 1030):  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1030):  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1030):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1030):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1030):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1030):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
D/ConnectivityService( 1030): Update of LinkProperties for NetworkAgentInfo [WIFI () - 100]; created=false
E/WifiStateMachine( 1030):  ObtainingIpState CMD_GET_CONFIGURED_NETWORKS uid=1000 1000 0 num=1
,E/WifiStateMachine( 1030):  L2ConnectedState CMD_GET_CONFIGURED_NETWORKS uid=1000 1000 0 num=1
E/WifiStateMachine( 1030):  ConnectModeState CMD_GET_CONFIGURED_NETWORKS uid=1000 1000 0 num=1
,E/WifiStateMachine( 1030):  ObtainingIpState CMD_PRE_DHCP_ACTION 0 0 txpkts=1,0,0
E/WifiStateMachine( 1030):  L2ConnectedState CMD_PRE_DHCP_ACTION 0 0 txpkts=1,0,0
D/WifiNative-wlan0( 1030): doBoolean: DRIVER SETSUSPENDMODE 0
I/qcom-bluetooth( 6453): /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
W/ResourcesManager( 6433): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,I/qcom-bluetooth( 6454): /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> 
I/wpa_supplicant( 6321): wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 0
D/WifiNative-wlan0( 1030): DRIVER SETSUSPENDMODE 0: returned true
D/WifiNative-wlan0( 1030): doBoolean: SET ps 0
D/WifiNative-wlan0( 1030): SET ps 0: returned true
D/WifiNative-wlan0( 1030): doBoolean: DRIVER BTCOEXMODE 1
I/wpa_supplicant( 6321): wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 1
D/WifiNative-wlan0( 1030): DRIVER BTCOEXMODE 1: returned true
E/WifiStateMachine( 1030): CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
D/LGWifiP2pService( 1030): InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@345cf18c target=com.android.internal.util.StateMachine$SmHandler }
V/DhcpStateMachine( 1030): Current State is mWaitBeforeStartState.
D/LGWifiP2pService( 1030): P2pEnabledState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@345cf18c target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine( 1030): WaitBeforeStartState{ when=0 what=196615 target=com.android.internal.util.StateMachine$SmHandler }
V/LgDhcpStateMachineHelper( 1030): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
V/LgDhcpStateMachineHelper( 1030): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700" is not exist.
D/DhcpStateMachine( 1030): DHCP Start wake lock is acquired.
D/WifiServerServiceExt( 1030): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1030): setSupplicantStateCOMPLETED
I/qcom-bluetooth( 6455): /system/etc/init.qcom.bt.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,D/WifiServerServiceExt( 1030): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1030): setSupplicantStateCOMPLETED
E/WifiStateMachine( 1030):  ObtainingIpState CMD_SAVE_CONFIG uid=1000 0 0
I/ActivityManager( 1030): Killing 5872:com.lge.email/u0a23 (adj 15): empty #17
E/WifiStateMachine( 1030):  L2ConnectedState CMD_SAVE_CONFIG uid=1000 0 0
E/WifiStateMachine( 1030):  ConnectModeState CMD_SAVE_CONFIG uid=1000 0 0
D/WifiNative-wlan0( 1030): doBoolean: SAVE_CONFIG
I/qcom-bluetooth( 6456): /system/etc/init.qcom.bt.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> 
D/WifiNative-wlan0( 1030): SAVE_CONFIG: returned true
,D/WiFiOffLoadUpdatePriority( 6308): remove1
V/WiFiOffLoadSharedPrefsUtils( 6308): save remove
I/libmdmdetect( 6458): ESOC framework not supported
E/Diag_Lib( 6458):  Diag_LSM_Init: Failed to open handle to diag driver, error = 13
D/WiFiOffLoadBroadcast( 6308): mLastConnectedNetwork from SharedPrefsUtils for wifioffloading : null
D/WiFiOffLoadBroadcast( 6308): S: false, R: false
E/WifiStateMachine( 1030):  ObtainingIpState CMD_GET_CONFIGURED_NETWORKS uid=1000 1000 0 num=1
E/WifiStateMachine( 1030):  L2ConnectedState CMD_GET_CONFIGURED_NETWORKS uid=1000 1000 0 num=1
E/WifiStateMachine( 1030):  ConnectModeState CMD_GET_CONFIGURED_NETWORKS uid=1000 1000 0 num=1
D/WiFiOffLoadUpdatePriority( 6308): saved SSID: "NG700"
D/WiFiOffLoadUpdatePriority( 6308): connected SSID: null
D/WiFiOffLoadUpdatePriority( 6308): private wpa: "NG700" 300
,D/bthci_qcomm_linux( 6458): [BTUI] bt_hci_qcomm_pfal_get_bdaddress: Get BDADDR from bluedroid prop (58:3F:54:73:64:C0)
D/bthci_qcomm_common( 6458): [BTUI] bt_hci_qcomm_init:
D/bthci_qcomm_common( 6458): [BTUI]     BDADDR: 58:3F:54:73:64:C0
D/bthci_qcomm_common( 6458): [BTUI]     BR/EDR: Class 1
D/bthci_qcomm_common( 6458): [BTUI]     LE: Class 2
D/bthci_qcomm_common( 6458): [BTUI]     Ref Clock: 32M
D/btqsocnvmtags( 6458): [BTUI] init_riva_entries: set NORMAL power settings
D/WifiServiceImplEx( 1030): addOrUpdateNetwork pid=6308, uid=1000, packageName=android.uid.system:1000
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
W/libprocessgroup( 1030): failed to open /acct/uid_10023/pid_5872/cgroup.procs: No such file or directory
,D/AuthorizationBluetoothService( 2121): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
D/WiFiOffLoadUpdatePriority( 6308):  ssid "NG700" prio 300
D/WiFiOffLoadUpdatePriority( 6308): configuration updated: 0
E/WifiStateMachine( 1030):  ObtainingIpState CMD_SAVE_CONFIG uid=1000 0 0
,E/WifiStateMachine( 1030):  L2ConnectedState CMD_SAVE_CONFIG uid=1000 0 0
E/WifiStateMachine( 1030):  ConnectModeState CMD_SAVE_CONFIG uid=1000 0 0
D/WifiNative-wlan0( 1030): doBoolean: SAVE_CONFIG
D/WifiNative-wlan0( 1030): SAVE_CONFIG: returned true
,D/WiFiOffLoadUpdatePriority( 6308): configuration saved: true
D/PCSuite ( 6388): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,V/WiFiOffLoadBroadcast( 6308): WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
D/WiFiOffLoadBroadcast( 6308): MCCMNC not supported: null
D/LGDMClient( 3984): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
D/LGDMClient( 3984): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
W/ContextImpl( 3984): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,W/ContextImpl( 3984): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
W/FormManager( 6359): Network not available. Please check & try again.
V/FormManager( 6359): Network unavailable.
V/FormManager( 6359): Network unavailable.
D/PostponalbeReceiver( 5178): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
I/rmt_storage(  302): rmt_storage_connect_cb: clnt_h=0x5 conn_h=0xb6403090
I/rmt_storage(  302): rmt_storage_rw_iovec_cb: /boot/modem_fs2: clnt_h=0x2: req_h=0x9 msg_id=3: R/W request received
I/rmt_storage(  302): wakelock acquired: 1, error no: 42
I/rmt_storage(  302): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 Unblock worker thread (th_id: -1236806912)
D/LGDMClient( 3984): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
D/LGDMClient( 3984): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
I/PCSuite ( 6388): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
,D/LGDMClient( 3984): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=3, isUserType=1
D/PCSuite ( 6388): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 6388): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 6308): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6308): MCCMNC not supported: null
,I/ActivityManager( 1030): Start proc com.lge.qremote for broadcast com.lge.qremote/.settings.WiFiStateReceiver: pid=6467 uid=10112 gids={50112, 9997, 1028, 1015, 3003, 3002} abi=armeabi
I/ActivityManager( 1030): Killing 5556:com.android.gallery3d/u0a27 (adj 15): empty #17
D/DhcpStateMachine( 1030): DHCPV4 request on wlan0
V/LgDhcpStateMachineHelper( 1030): [bssid] hash key :c0:ff:d4:d3:aa:48
D/LgDhcpStateMachineHelper( 1030): dhcp.ap.macaddress = c0:ff:d4:d3:aa:48
I/art     (  338): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 290us total 15.587ms
,I/art     (  338): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 269us total 12.511ms
I/art     (  338): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 262us total 11.470ms
,W/dhcpcd  ( 6477): type=1400 audit(0.0:157): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6815 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
W/dhcpcd  ( 6477): type=1400 audit(0.0:158): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6815 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
I/rmt_storage(  302): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0x9 msg_id=3: Bytes written = 1572864
I/rmt_storage(  302): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0x9 msg_id=3: Send response: res=0 err=0
I/rmt_storage(  302): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 About to block rmt_storage client thread (th_id: -1236806912) wakelock released: 1, error no: 0
I/rmt_storage(  302): 
I/rmt_storage(  302): rmt_storage_disconnect_cb: clnt_h=0x0x5 conn_h=0x0xb6403090
,E/Diag_Lib(  902): [IMS_FATAL]| 3347 | 910 |ims-rtp-daemon ims_rtp_qmi_handler_thread_func waiting on select thread>
I/dhcpcd  ( 6477): version 5.5.6 starting
E/dhcpcd  ( 6477): get_duid: m
D/dhcpcd  ( 6477): wlan0: using ClientID 01:c4:9a:02:7b:60:ac
D/dhcpcd  ( 6477): wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason PREINIT
W/libprocessgroup( 1030): failed to open /acct/uid_10027/pid_5556/cgroup.procs: No such file or directory
,W/ResourcesManager( 6467): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,D/QRemote ( 6467): [QRemoteApplication.java:230:onCreate()] oooooo QRemoteApp onCreate....
,D/QRemote ( 6467): [CarrierUtils.java:858:getHardwareSettings()] oooooo qremote android.os.Build.MODEL = LG-D855
,I/QRemote ( 6467): [CarrierUtils.java:859:getHardwareSettings()] oooooo getCountry :: EU
I/QRemote ( 6467): [CarrierUtils.java:860:getHardwareSettings()] oooooo getCarrier :: OPEN
I/QRemote ( 6467): [CarrierUtils.java:861:getHardwareSettings()] oooooo getArea :: COM
D/QRemote ( 6467): [CarrierUtils.java:862:getHardwareSettings()] oooooo Loading Config...
D/QRemote ( 6467): [CarrierUtils.java:876:getHardwareSettings()] oooooo qremote configuration file = R.xml.qremote_conf
D/QRemote ( 6467): [QRemoteApplication.java:701:updateWidget()] oooooo Widget count is [1]. send broadcast
D/dhcpcd  ( 6477): getUsingAPMacAddress: c0:ff:d4:d3:aa:48 , return 1
D/dhcpcd  ( 6477): [read_lease] unlink /data/misc/dhcp/dhcpcd-wlan0.lease, link /data/misc/dhcp/dhcpcd-wlan0-c0:ff:d4:d3:aa:48.lease2
D/dhcpcd  ( 6477): wlan0: reading lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
D/QRemote ( 6467): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,I/dhcpcd  ( 6477): wlan0: rebinding lease of 192.168.1.141
D/QRemote ( 6467): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
D/dhcpcd  ( 6477): wlan0: sending REQUEST (xid 0x3539545b), next in 3.32 seconds
I/QRemote ( 6467): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,D/QRemote ( 6467): [QRemoteService.java:196:onCreate()] oooooo 140526:onCreate
V/[BNRBootReceiver]( 5992): boot receiver action = android.net.wifi.p2p.CONNECTION_STATE_CHANGE
D/BNRAndroBeam( 5992): [BnR DirectBeam] Android Direct Beam(NFC) Connection changed
D/QRemote ( 6467): [QRemoteService.java:217:onStartCommand()] oooooo 140526:onStartCommand:action:action.application.oncreate. startId:1, flags:0
V/[BNRBootReceiver]( 5992): Boot Receiver Return
D/PostponalbeReceiver( 5178): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,V/WiFiOffLoadBroadcast( 6308): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6308): MCCMNC not supported: null
D/QRemote ( 6467): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6467): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 6467): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,V/WiFiOffLoadBroadcast( 6308): WiFiOffLoadBroadcast: android.net.wifi.SCAN_RESULTS
D/WiFiOffLoadBroadcast( 6308): Not supported operator for automatic switch
D/UsbSettingsReceiver( 6308): [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
D/UsbSettingsReceiver( 6308): [AUTORUN] sys.usb.config = ptp_only,adb
D/UsbSettingsReceiver( 6308): [AUTORUN] sys.usb.state = ptp_only,adb
D/UsbSettingsReceiver( 6308): [AUTORUN] persist.sys.usb.config = ptp_only,adb
D/UsbSettingsReceiver( 6308): [AUTORUN] onReceive() : app userid = 0, current userid = 0
D/UsbSettingsControl( 6308): [AUTORUN] getUsbConnected() : connected=true
D/UsbSettingsReceiver( 6308): [AUTORUN] onReceive() : availableList=[wlan0]
D/UsbSettingsReceiver( 6308): [AUTORUN] onReceive() : activeList=[]
D/UsbSettingsReceiver( 6308): [AUTORUN] onReceive() : errorList=[]
D/UsbSettingsControl( 6308): [AUTORUN] isAutorunTimer() : mAutorunChanging=false
D/UsbSettingsReceiver( 6308): [AUTORUN] onReceive() : TetherState Changed=wlan0
,D/UsbSettingsControl( 6308): [AUTORUN] setTetherStatus() : status=false
D/PostponalbeReceiver( 5178): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,V/WiFiOffLoadBroadcast( 6308): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 6308): MCCMNC not supported: null
D/QRemote ( 6467): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6467): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 6467): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,D/PostponalbeReceiver( 5178): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
V/WiFiOffLoadBroadcast( 6308): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6308): MCCMNC not supported: null
D/QRemote ( 6467): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6467): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 6467): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
D/PostponalbeReceiver( 5178): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
V/WiFiOffLoadBroadcast( 6308): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6308): MCCMNC not supported: null
D/QRemote ( 6467): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6467): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 6467): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,D/PostponalbeReceiver( 5178): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
V/WiFiOffLoadBroadcast( 6308): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6308): MCCMNC not supported: null
D/QRemote ( 6467): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6467): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 6467): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
D/PostponalbeReceiver( 5178): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,V/WiFiOffLoadBroadcast( 6308): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 6308): MCCMNC not supported: null
D/QRemote ( 6467): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,D/QRemote ( 6467): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 6467): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
D/PostponalbeReceiver( 5178): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
V/WiFiOffLoadBroadcast( 6308): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6308): MCCMNC not supported: null
D/QRemote ( 6467): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6467): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 6467): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
V/QRemote ( 6467): [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
,D/QRemote ( 6467): [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
D/QRemote ( 6467): [QRemoteApplication.java:86:getControlManager()] oooooo mControlManager is null. make new RemoteControlManager
D/LgDataFeature( 6467): LgDataFeature() Constructor: none
D/LgDataFeature( 6467): LgDataFeature() Constructor Done, null
,V/SoundPool( 6467): SoundPool constructor: maxChannels=2, attr.usage=13, attr.flags=0x0, attr.tags=
V/SoundPool( 6467): load: fd=30, offset=10857164, length=17813, priority=1
V/SoundPool( 6467): create sampleID=1, fd=31, offset=17813 length=10857164
V/SoundPool( 6467): doLoad: loading sample sampleID=1
I/QRemote ( 6467): [RemoteControlManager.java:157:onBindIRService()] oooooo bind
V/SoundPool( 6467): Start decode
V/MediaPlayer[Native]( 6467): decode(31, 10857164, 17813)
V/MediaPlayerService(  311): decode(24, 10857164, 17813)
W/BrunchPlayerTypeImpl(  311): [SelectPlayer] LocalType
W/BrunchPlayerTypeImpl(  311): [getMediaType] EXTEND_MEDIA_MIMETYPE = application/ogg
W/BrunchPlayerTypeImpl(  311): [FindUsePlayer] type = [application/ogg]
W/BrunchPlayerTypeImpl(  311): [FindUsePlayer] componentName = [9101]
W/MediaPlayerFactory(  311): [getPlayerType:fd] nType = 3
V/MediaPlayerService(  311): player type = 3
V/AwesomePlayer(  311): AwesomePlayer create()
V/AwesomePlayer(  311): reset_l() 
V/AwesomePlayer(  311): cancelPlayerEvents
V/AwesomePlayer(  311): setAudioSink() 
V/AwesomePlayer(  311): reset_l() 
V/AudioCache(  311): notify(0xb040d200, 8, 0, 0)
V/AudioCache(  311): ignored
V/AwesomePlayer(  311): cancelPlayerEvents
D/Utils   (  311): printFileName fd(25) -> /data/preload/LGQRemote/LGQRemote.apk
V/AwesomePlayer(  311): setDataSource_l dataSource
V/LGParserOSAL(  311): SniffLGParser start
V/LGParserOSAL(  311): MainType:5, SubType=0
V/LGParserOSAL(  311): #### check Mime : application/ogg
V/LGParserOSAL(  311): Detector mimeType:application/ogg, Confidence=1.000000
E/MediaExtractor(  311): Use LGExtractor :application/ogg 
D/QRemote ( 6467): [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
D/UEI.SmartControl( 5900): QS Service created
E/QRemote ( 6467): [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
D/QRemote ( 6467): [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
I/UEI.SmartControl( 5900): Service initServices...
V/LGMDMManager( 6467): Create singleton instance
D/UEI.SmartControl( 5900): QS start get config
,V/LGParserOSAL(  311): supported mime: application/ogg
V/AwesomePlayer(  311): setDataSource_l() extractor countTracks=1
V/AwesomePlayer(  311): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer(  311): mBitrate = -1 bits/sec
V/AwesomePlayer(  311): AudioTrack Setting
V/AwesomePlayer(  311): AudioTrack Setting channelCount = 2
V/AwesomePlayer(  311): setAudioSource() 
V/MediaPlayerService(  311): prepare
V/AwesomePlayer(  311): prepareAsync_l() 
V/MediaPlayerService(  311): wait for prepare
V/AwesomePlayer(  311): onPrepareAsyncEvent() 
,V/AwesomePlayer(  311): initAudioDecoder() 
W/Utils   (  311): bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
V/AudioSystem(  311): isOffloadSupported()
V/AudioPolicyManager(  311): isOffloadSupported: SR=48000, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
D/AudioPolicyManager(  311): isOffloadSupported: stream_type != MUSIC, returning false
I/AudioFlinger(  311): isAudioPlaybackHookOn() false
V/AwesomePlayer(  311): getUseOffload() = 0 
V/OMXCodec(  311): OMXCodec::Create
V/OMXCodec(  311): findMatchingCodecs()
V/OMXCodec(  311): matching 'OMX.google.vorbis.decoder' quirks 0x00000000
V/OMXCodec(  311): matchingCodecs.size()=1
V/OMXCodec(  311): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
D/OMXCodec(  311): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
V/LGCodecAdapter(  311): LG Codec Adapter start
V/OMXCodec(  311): OMXCodec Createtor
V/OMXCodec(  311): setComponentRole
V/OMXCodec(  311): configureCodec protected=0
V/LGCodecAdapter(  311): called getLGCodecSpecificData
V/LGCodecOSAL(  311): Called LGgetCodecSpecificDataMETA
V/LGCodecOSAL(  311): Called LGconfigureCodecMETA
V/LGCodecOSAL(  311): Called LGconfigureCodecMSG
V/LGCodecOSAL(  311): Not support LGCodec
V/OMXCodec(  311): [OMX.google.vorbis.decoder] initOutputFormat()
V/OMXCodec(  311): Codec outputs a different number of channels than the input stream contains (contains 2 channels, codec outputs 1 channels).
V/OMXCodec(  311): Codec outputs at different sampling rate than what the input stream contains (contains data at 48000 Hz, codec outputs 44100 Hz)
I/AwesomePlayer(  311): Could not offload audio decode, try pcm offload
W/Utils   (  311): bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
V/AudioSystem(  311): isOffloadSupported()
V/AudioPolicyManager(  311): isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
D/AudioPolicyManager(  311): isOffloadSupported: stream_type != MUSIC, returning false
V/OMXCodec(  311): [OMX.google.vorbis.decoder] start mState=1
V/OMXCodec(  311): init()
V/OMXCodec(  311): [OMX.google.vorbis.decoder] setState mState=1 , newState=2
V/OMXCodec(  311): allocateBuffers
V/OMXCodec(  311): allocateBuffersOnPort portIndex=0
V/OMXCodec(  311): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
V/OMXCodec(  311): [OMX.google.vorbis.decoder] allocated buffer 0xb100d1a0 on input port
V/OMXCodec(  311): [OMX.google.vorbis.decoder] allocated buffer 0xb100d1f0 on input port
V/OMXCodec(  311): [OMX.google.vorbis.decoder] allocated buffer 0xb100d240 on input port
V/OMXCodec(  311): [OMX.google.vorbis.decoder] allocated buffer 0xb100d290 on input port
V/OMXCodec(  311): allocateBuffersOnPort portIndex=1
V/OMXCodec(  311): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
V/OMXCodec(  311): [OMX.google.vorbis.decoder] allocated buffer 0xb100d2e0 on output port
V/OMXCodec(  311): [OMX.google.vorbis.decoder] allocated buffer 0xb100d470 on output port
V/OMXCodec(  311): [OMX.google.vorbis.decoder] allocated buffer 0xb100d4c0 on output port
V/OMXCodec(  311): [OMX.google.vorbis.decoder] allocated buffer 0xb100d560 on output port
V/OMXCodec(  311): init() mAsyncCompletion wait!!! 
V/OMXCodec(  311): [OMX.google.vorbis.decoder] onStateChange 2
V/OMXCodec(  311): [OMX.google.vorbis.decoder] Now Idle.
V/OMXCodec(  311): [OMX.google.vorbis.decoder] setState mState=2 , newState=3
V/OMXCodec(  311): init() mAsyncCompletion wait!!! 
V/OMXCodec(  311): [OMX.google.vorbis.decoder] onStateChange 3
V/OMXCodec(  311): [OMX.google.vorbis.decoder] Now Executing.
V/OMXCodec(  311): [OMX.google.vorbis.decoder] setState mState=3 , newState=4
V/OMXCodec(  311): init() ,mAsyncCompletion wait free! 
V/AwesomePlayer(  311): finishAsyncPrepare_l() 
V/AudioCache(  311): notify(0xb040d200, 5, 0, 0)
V/AudioCache(  311): ignored
V/AudioCache(  311): notify(0xb040d200, 1, 0, 0)
V/AudioCache(  311): prepared
V/AudioCache(  311): wait - success
V/MediaPlayerService(  311): start
V/AwesomePlayer(  311): play_l() 
V/AwesomePlayer(  311): play_l m_isDivXDRM=0, bpurchasefile:0
V/AwesomePlayer(  311): createAudioPlayer_l
V/AwesomePlayer(  311): seekAudioIfNecessary_l() 
V/AwesomePlayer(  311): startAudioPlayer_l() 
D/AudioPlayer(  311): start of Playback, useOffload 0
V/OMXCodec(  311): [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
V/OMXCodec(  311): [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
V/OMXCodec(  311): [OMX.google.vorbis.decoder] OMX_EventPortSettingsChanged(port=1, data2=0x00000000)
V/OMXCodec(  311): [OMX.google.vorbis.decoder] PORT_SETTINGS_CHANGED(1)
V/OMXCodec(  311): [OMX.google.vorbis.decoder] setState mState=4 , newState=7
V/OMXCodec(  311): [OMX.google.vorbis.decoder] disablePortAsync portIndex=1
V/OMXCodec(  311): [OMX.google.vorbis.decoder] sending OMX_CommandPortDisable(1)
V/OMXCodec(  311): [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
V/OMXCodec(  311): [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2969621216
V/OMXCodec(  311): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
V/OMXCodec(  311): [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2969621616
V/OMXCodec(  311): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
V/OMXCodec(  311): [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2969621696
V/OMXCodec(  311): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
V/OMXCodec(  311): [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2969621856
V/OMXCodec(  311): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
V/OMXCodec(  311): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
V/OMXCodec(  311): [OMX.google.vorbis.decoder] initOutputFormat()
V/OMXCodec(  311): [OMX.google.vorbis.decoder] reconfig handling, formatHasNotablyChanged
V/OMXCodec(  311): [OMX.google.vorbis.decoder] enablePortAsync portIndex=1
V/OMXCodec(  311): [OMX.google.vorbis.decoder] sending OMX_CommandPortEnable(1)
V/OMXCodec(  311): allocateBuffersOnPort portIndex=1
V/OMXCodec(  311): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
V/OMXCodec(  311): [OMX.google.vorbis.decoder] allocated buffer 0xb100d4c0 on output port
V/OMXCodec(  311): [OMX.google.vorbis.decoder] allocated buffer 0xb100d470 on output port
V/OMXCodec(  311): [OMX.google.vorbis.decoder] allocated buffer 0xb100d2e0 on output port
V/OMXCodec(  311): [OMX.google.vorbis.decoder] allocated buffer 0xb100d920 on output port
V/OMXCodec(  311): [OMX.google.vorbis.decoder] PORT_ENABLED(1)
V/OMXCodec(  311): [OMX.google.vorbis.decoder] setState mState=7 , newState=4
,V/AudioCache(  311): open(48000, 2, 0x0, 1, 4)
V/AudioCache(  311): notify(0xb040d200, 6, 0, 0)
V/AudioCache(  311): ignored
V/MediaPlayerService(  311): wait for playback complete
V/AudioCache(  311): write(0xb1521000, 4096)
,V/AudioCache(  311): memcpy(0xac300000, 0xb1521000, 4096)
V/AudioCache(  311): write(0xb1521000, 4096)
V/AudioCache(  311): memcpy(0xac301000, 0xb1521000, 4096)
V/AudioCache(  311): write(0xb1521000, 4096)
V/AudioCache(  311): memcpy(0xac302000, 0xb1521000, 4096)
V/AudioCache(  311): write(0xb1521000, 4096)
V/AudioCache(  311): memcpy(0xac303000, 0xb1521000, 4096)
V/AudioCache(  311): write(0xb1521000, 4096)
V/AudioCache(  311): memcpy(0xac304000, 0xb1521000, 4096)
V/AudioCache(  311): write(0xb1521000, 4096)
V/AudioCache(  311): memcpy(0xac305000, 0xb1521000, 4096)
V/AudioCache(  311): write(0xb1521000, 4096)
V/AudioCache(  311): memcpy(0xac306000, 0xb1521000, 4096)
V/AudioCache(  311): write(0xb1521000, 4096)
V/AudioCache(  311): memcpy(0xac307000, 0xb1521000, 4096)
V/AudioCache(  311): write(0xb1521000, 4096)
V/AudioCache(  311): memcpy(0xac308000, 0xb1521000, 4096)
V/AudioCache(  311): write(0xb1521000, 4096)
V/AudioCache(  311): memcpy(0xac309000, 0xb1521000, 4096)
V/AudioCache(  311): write(0xb1521000, 4096)
V/AudioCache(  311): memcpy(0xac30a000, 0xb1521000, 4096)
V/AudioCache(  311): write(0xb1521000, 4096)
V/AudioCache(  311): memcpy(0xac30b000, 0xb1521000, 4096)
V/AudioCache(  311): write(0xb1521000, 4096)
V/AudioCache(  311): memcpy(0xac30c000, 0xb1521000, 4096)
V/AudioCache(  311): write(0xb1521000, 4096)
V/AudioCache(  311): memcpy(0xac30d000, 0xb1521000, 4096)
V/AudioCache(  311): write(0xb1521000, 4096)
V/AudioCache(  311): memcpy(0xac30e000, 0xb1521000, 4096)
V/AudioCache(  311): write(0xb1521000, 4096)
V/AudioCache(  311): memcpy(0xac30f000, 0xb1521000, 4096)
V/AudioCache(  311): write(0xb1521000, 4096)
V/AudioCache(  311): memcpy(0xac310000, 0xb1521000, 4096)
V/AudioCache(  311): write(0xb1521000, 4096)
V/AudioCache(  311): memcpy(0xac311000, 0xb1521000, 4096)
V/AudioCache(  311): write(0xb1521000, 4096)
V/AudioCache(  311): memcpy(0xac312000, 0xb1521000, 4096)
,V/AudioCache(  311): write(0xb1521000, 4096)
V/AudioCache(  311): memcpy(0xac313000, 0xb1521000, 4096)
V/AudioCache(  311): write(0xb1521000, 4096)
V/AudioCache(  311): memcpy(0xac314000, 0xb1521000, 4096)
V/AudioCache(  311): write(0xb1521000, 4096)
V/AudioCache(  311): memcpy(0xac315000, 0xb1521000, 4096)
V/AudioCache(  311): write(0xb1521000, 4096)
V/AudioCache(  311): memcpy(0xac316000, 0xb1521000, 4096)
V/AudioCache(  311): write(0xb1521000, 4096)
V/AudioCache(  311): memcpy(0xac317000, 0xb1521000, 4096)
V/AudioCache(  311): write(0xb1521000, 4096)
V/AudioCache(  311): memcpy(0xac318000, 0xb1521000, 4096)
V/AudioCache(  311): write(0xb1521000, 4096)
V/AudioCache(  311): memcpy(0xac319000, 0xb1521000, 4096)
V/AudioCache(  311): write(0xb1521000, 4096)
V/AudioCache(  311): memcpy(0xac31a000, 0xb1521000, 4096)
V/AudioCache(  311): write(0xb1521000, 4096)
V/AudioCache(  311): memcpy(0xac31b000, 0xb1521000, 4096)
V/AudioCache(  311): write(0xb1521000, 4096)
V/AudioCache(  311): memcpy(0xac31c000, 0xb1521000, 4096)
V/AudioCache(  311): write(0xb1521000, 4096)
V/AudioCache(  311): memcpy(0xac31d000, 0xb1521000, 4096)
V/AudioCache(  311): write(0xb1521000, 4096)
V/AudioCache(  311): memcpy(0xac31e000, 0xb1521000, 4096)
V/AudioCache(  311): write(0xb1521000, 4096)
V/AudioCache(  311): memcpy(0xac31f000, 0xb1521000, 4096)
V/AudioCache(  311): write(0xb1521000, 4096)
V/AudioCache(  311): memcpy(0xac320000, 0xb1521000, 4096)
V/AudioCache(  311): write(0xb1521000, 4096)
V/AudioCache(  311): memcpy(0xac321000, 0xb1521000, 4096)
V/AudioCache(  311): write(0xb1521000, 4096)
V/AudioCache(  311): memcpy(0xac322000, 0xb1521000, 4096)
V/AudioCache(  311): write(0xb1521000, 4096)
V/AudioCache(  311): memcpy(0xac323000, 0xb1521000, 4096)
V/AudioCache(  311): write(0xb1521000, 4096)
V/AudioCache(  311): memcpy(0xac324000, 0xb1521000, 4096)
V/AudioCache(  311): write(0xb1521000, 4096)
V/AudioCache(  311): memcpy(0xac325000, 0xb1521000, 4096)
V/AudioCache(  311): write(0xb1521000, 4096)
V/AudioCache(  311): memcpy(0xac326000, 0xb1521000, 4096)
V/AudioCache(  311): write(0xb1521000, 4096)
V/AudioCache(  311): memcpy(0xac327000, 0xb1521000, 4096)
V/AudioCache(  311): write(0xb1521000, 4096)
V/AudioCache(  311): memcpy(0xac328000, 0xb1521000, 4096)
V/AudioCache(  311): write(0xb1521000, 4096)
V/AudioCache(  311): memcpy(0xac329000, 0xb1521000, 4096)
V/AudioCache(  311): write(0xb1521000, 4096)
V/AudioCache(  311): memcpy(0xac32a000, 0xb1521000, 4096)
V/AudioCache(  311): write(0xb1521000, 4096)
V/AudioCache(  311): memcpy(0xac32b000, 0xb1521000, 4096)
V/AudioCache(  311): write(0xb1521000, 4096)
V/AudioCache(  311): memcpy(0xac32c000, 0xb1521000, 4096)
V/AudioCache(  311): write(0xb1521000, 4096)
V/AudioCache(  311): memcpy(0xac32d000, 0xb1521000, 4096)
V/AudioCache(  311): write(0xb1521000, 4096)
V/AudioCache(  311): memcpy(0xac32e000, 0xb1521000, 4096)
V/AudioCache(  311): write(0xb1521000, 4096)
V/AudioCache(  311): memcpy(0xac32f000, 0xb1521000, 4096)
V/AudioCache(  311): write(0xb1521000, 4096)
V/AudioCache(  311): memcpy(0xac330000, 0xb1521000, 4096)
V/OMXCodec(  311): [OMX.google.vorbis.decoder] No more output data.
V/AudioCache(  311): write(0xb1521000, 4096)
V/AudioCache(  311): memcpy(0xac331000, 0xb1521000, 4096)
V/OMXCodec(  311): [OMX.google.vorbis.decoder] There is no more output data available, not calling fillOutputBuffer
V/OMXCodec(  311): [OMX.google.vorbis.decoder] There is no more output data available, not calling fillOutputBuffer
V/AwesomePlayer(  311): postAudioEOS() 
V/AudioCache(  311): write(0xb1521000, 280)
V/AudioCache(  311): memcpy(0xac332000, 0xb1521000, 280)
,V/AwesomePlayer(  311): postStreamDoneEvent_l() -> status:-1011 
V/AwesomePlayer(  311): onStreamDone
V/AwesomePlayer(  311): MEDIA_PLAYBACK_COMPLETE
V/AudioCache(  311): notify(0xb040d200, 2, 0, 0)
V/AudioCache(  311): playback complete
V/AwesomePlayer(  311): pause_l() 
V/AudioCache(  311): notify(0xb040d200, 7, 0, 0)
V/AudioCache(  311): ignored
V/AwesomePlayer(  311): cancelPlayerEvents
V/AudioCache(  311): wait - success
V/MediaPlayerService(  311): return size 205080, sampleRate=48000, channelCount = 2, format = 1
D/AudioPlayer(  311): Pause Playback at 1068125
V/AwesomePlayer(  311): reset_l() 
V/AudioCache(  311): notify(0xb040d200, 8, 0, 0)
V/AudioCache(  311): ignored
V/AwesomePlayer(  311): cancelPlayerEvents
D/AudioPlayer(  311): reset: mPlaying=0 mReachedEOS=1 useOffload=0
V/OMXCodec(  311): [OMX.google.vorbis.decoder] stop mState=4
V/OMXCodec(  311): [OMX.google.vorbis.decoder] stopOmxComponent_l mState=4
V/OMXCodec(  311): [OMX.google.vorbis.decoder] setState mState=4 , newState=5
V/OMXCodec(  311): [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
V/OMXCodec(  311): [OMX.google.vorbis.decoder] onStateChange 2
V/OMXCodec(  311): [OMX.google.vorbis.decoder] Now Idle.
V/OMXCodec(  311): [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=0
V/OMXCodec(  311): [OMX.google.vorbis.decoder] freeing buffer 0xb100d290 on port 0
V/OMXCodec(  311): [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=3
V/OMXCodec(  311): [OMX.google.vorbis.decoder] freeing buffer 0xb100d240 on port 0
V/OMXCodec(  311): [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=2
V/OMXCodec(  311): [OMX.google.vorbis.decoder] freeing buffer 0xb100d1f0 on port 0
V/OMXCodec(  311): [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=1
V/OMXCodec(  311): [OMX.google.vorbis.decoder] freeing buffer 0xb100d1a0 on port 0
V/OMXCodec(  311): [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=0
V/OMXCodec(  311): [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
V/OMXCodec(  311): [OMX.google.vorbis.decoder] freeing buffer 0xb100d920 on port 1
V/OMXCodec(  311): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=3
V/OMXCodec(  311): [OMX.google.vorbis.decoder] freeing buffer 0xb100d2e0 on port 1
,V/OMXCodec(  311): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=2
V/OMXCodec(  311): [OMX.google.vorbis.decoder] freeing buffer 0xb100d470 on port 1
V/OMXCodec(  311): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=1
V/OMXCodec(  311): [OMX.google.vorbis.decoder] freeing buffer 0xb100d4c0 on port 1
V/OMXCodec(  311): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
V/OMXCodec(  311): [OMX.google.vorbis.decoder] setState mState=5 , newState=6
V/OMXCodec(  311): [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
V/OMXCodec(  311): [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
V/OMXCodec(  311): [OMX.google.vorbis.decoder] onStateChange 1
V/OMXCodec(  311): [OMX.google.vorbis.decoder] Now Loaded.
V/OMXCodec(  311): [OMX.google.vorbis.decoder] setState mState=6 , newState=1
V/OMXCodec(  311): [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
V/OMXCodec(  311): [OMX.google.vorbis.decoder] stopped in state 1
V/OMXCodec(  311): [OMX.google.vorbis.decoder] ~OMXCodec mstate =1
V/OMXCodec(  311): [OMX.google.vorbis.decoder] setState mState=1 , newState=0
D/AudioPlayer(  311): AudioPlayer releasing audio source
D/AudioPlayer(  311): AudioPlayer done releasing audio source
V/AwesomePlayer(  311): reset_l() 
V/AwesomePlayer(  311): cancelPlayerEvents
V/AwesomePlayer(  311): ~AwesomePlayer call
V/AwesomePlayer(  311): reset_l() 
V/AwesomePlayer(  311): cancelPlayerEvents
V/SoundPool( 6467): close(31)
V/SoundPool( 6467): pointer = 0x9ffcc000, size = 205080, sampleRate = 48000, numChannels = 2
D/QRemote ( 6467): [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
D/QRemote ( 6467): [RemoteAppWidgetProvider.java:486:onUpdate()] oooooo 140510:RetrieveDevices is not complete. Just waiting
,D/QRemote ( 6467): [RemoteAppWidgetProvider.java:499:onUpdate()] oooooo 140514:alarm set after 5000ms:5716
I/UEI.SmartControl( 5900): Supports setup maps: true
D/UEI.SmartControl( 5900): QS start statue = true Error code = 0
I/UEI.SmartControl( 5900): QS version = v2.7.10.1_RC1
I/UEI.SmartControl( 5900): QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
I/UEI.SmartControl( 5900): ### init IR Blaster...
D/serial_port( 5900): Configuring serial port
E/UEI.SmartControl( 5900): UEIBLaster setting for 616
I/UEI.SmartControl( 5900): Setting serial record hearder size = 2
I/UEI.SmartControl( 5900): configuring settings for MAXQ616
I/UEI.SmartControl( 5900): Get version...
D/UEI.SmartControl( 5900): serial port data available: 21
D/UEI.SmartControl( 5900): MAXQ616 A2-X4 software.
I/UEI.SmartControl( 5900): IR Blaster version: 256702256704300002
I/UEI.SmartControl( 5900): QS saving settings...
D/UEI.SmartControl( 5900): IR Blaster version: 25672567
D/UEI.SmartControl( 5900): serial port data available: 4
I/UEI.SmartControl( 5900): Device manager: loading config....
D/UEI.SmartControl( 5900): ----------- loading internal config...
W/ContextImpl( 5900): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
E/UEI.SmartControl( 5900): Services init done
D/UEI.SmartControl( 5900): QS Service init finished
D/UEI.SmartControl( 5900): QS Service version name: 2.1.91
D/UEI.SmartControl( 5900): QS Service version code: 201091
D/UEI.SmartControl( 5900): Service requested: Control
E/UEI.SmartControl( 5900): Loading SETTINGS...
D/UEI.SmartControl( 5900): Request IControl service: devices are loaded...
I/QRemote ( 6467): [RemoteControlManager.java:183:onServiceConnected()] oooooo start
I/UEI.SmartControl( 5900): ------ IControl API: 11
D/UEI.SmartControl( 5900): File observer start...
D/UEI.SmartControl( 5900): Internal service binding...
E/UEI.SmartControl( 5900): IR Port is disabled: false
D/UEI.SmartControl( 5900): Starting file observer...
I/UEI.SmartControl( 5900): Registering callback...
I/UEI.SmartControl( 5900): ------ IControl API: 19
I/UEI.SmartControl( 5900): Registering Services Ready callback...
E/QC-QMI  ( 6458): qmi_client [6458] 13: failed to locate client data
E/QC-QMI  (  449): qmuxd: RX on fd=32 returned error=0 errno[2:No such file or directory]
E/QC-QMI  (  449): QMUX qmux_client_id=13 not found in qmux client list, unable to remove
D/UEI.SmartControl( 5900): -- Open brand translation xml: brands_translations_ko
I/UEI.SmartControl( 5900): Notify AllClients services are ready: 0
I/QRemote ( 6467): [RemoteControlManager.java:660:QSSetupIsReady()] oooooo 140517:sdkIsReady callback... get functions. Result:0
D/QRemote ( 6467): [RemoteControlManager.java:388:handleMessage()] oooooo 140510:START_SESSION
D/QRemote ( 6467): [RemoteControlManager.java:394:handleMessage()] oooooo 140510:send retrieve msg
D/QRemote ( 6467): [RemoteControlManager.java:322:handleMessage()] oooooo 140510:handler call retrieveDevices
D/QRemote ( 6467): [RemoteControlManager.java:336:retrieveDevices()] oooooo retrieveDevices: start
I/UEI.SmartControl( 5900): ------ IControl API: 8
D/UEI.SmartControl( 5900): -----service ready thread exits
D/QRemote ( 6467): [RemoteControlManager.java:340:retrieveDevices()] oooooo retrieveDevices: 0
D/QRemote ( 6467): [RemoteControlManager.java:345:retrieveDevices()] oooooo retrieveDevices complete:true
D/QRemote ( 6467): [RemoteControlManager.java:353:retrieveDevices()] oooooo retrieveDevices: notifyDataSetChanged()
D/QRemote ( 6467): [QRemoteApplication.java:145:onRemoteControlStateChanged()] oooooo onRemoteControlStateChanged called in QRemoteApp
D/QRemote ( 6467): [QRemoteApplication.java:158:onRemoteControlStateChanged()] oooooo Widget count is [1]. send broadcast
D/QRemote ( 6467): [QRemoteApplication.java:160:onRemoteControlStateChanged()] oooooo Widget[0]:3
D/QRemote ( 6467): [QRemoteApplication.java:188:onRemoteControlStateChanged()] oooooo 140526:onRemoteControlStateChanged&sdkIsReady. stop Service
V/QRemote ( 6467): [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
D/QRemote ( 6467): [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
E/QRemote ( 6467): [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
D/QRemote ( 6467): [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
D/QRemote ( 6467): [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
D/QRemote ( 6467): [RemoteAppWidgetProvider.java:506:onUpdate()] oooooo 140510:RetrieveDevices complete. Start loading
D/QRemote ( 6467): [RemoteAppWidgetProvider.java:508:onUpdate()] oooooo 140510:appWidgetIds[0]:3 loading
D/QRemote ( 6467): [RemoteAppWidgetManager.java:41:startLoading()] oooooo 140518:widgetId[3] loading start at [1452278505403]
D/QRemote ( 6467): [QRemoteService.java:207:onDestroy()] oooooo 140526:onDestroy
I/ActivityManager( 1030): Killing 5767:com.android.defcontainer/u0a4 (adj 15): empty #17
D/QRemote ( 6467): [RemoteAppWidgetManager.java:239:doInBackground()] oooooo 140407:doinBack arr:0
I/qcom-bluetooth( 6511): /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 58:3f:54:73:64:c0 
I/qcom-bluetooth( 6512): /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
I/bt_vendor( 6276): bluetooth satus is on
D/bt_hci_bdroid( 6276): preload
D/bt_userial_mct( 6276): userial_open(port:0)
I/bt_vendor( 6276): bt-vendor : BT_VND_OP_USERIAL_OPEN
I/bt_vendor( 6276): Done intiailizing UART
I/bt_vendor( 6276): Done intiailizing UART
I/bt_userial_mct( 6276): CMD=66, EVT=66, ACL_Out=67, ACL_In=67
I/bt_vendor( 6276): Bluetooth Firmware and transport layer are initialized
D/bt_userial_mct( 6276): Entering userial_read_thread()
I/bt-btu  ( 6276): btu_task received preload complete event
W/bt-l2cap( 6276): L2CAP - L2CA_Register() called for PSM: 0x0001
W/bt-l2cap( 6276): L2CAP - L2CA_Register() called for PSM: 0x001f
W/bt-l2cap( 6276): L2CAP - L2CA_Register() called for PSM: 0x0003
I/        ( 6276): BTE_InitTraceLevels -- TRC_HCI
I/        ( 6276): BTE_InitTraceLevels -- TRC_L2CAP
I/        ( 6276): BTE_InitTraceLevels -- TRC_RFCOMM
I/        ( 6276): BTE_InitTraceLevels -- TRC_AVDT
I/        ( 6276): BTE_InitTraceLevels -- TRC_AVRC
I/        ( 6276): BTE_InitTraceLevels -- TRC_A2D
I/        ( 6276): BTE_InitTraceLevels -- TRC_BNEP
I/        ( 6276): BTE_InitTraceLevels -- TRC_BTM
I/        ( 6276): BTE_InitTraceLevels -- TRC_HID_HOST
I/        ( 6276): BTE_InitTraceLevels -- TRC_GAP
I/        ( 6276): BTE_InitTraceLevels -- TRC_PAN
I/        ( 6276): BTE_InitTraceLevels -- TRC_SDP
I/        ( 6276): BTE_InitTraceLevels -- TRC_GATT
I/        ( 6276): BTE_InitTraceLevels -- TRC_SMP
I/        ( 6276): BTE_InitTraceLevels -- TRC_BTAPP
I/        ( 6276): BTE_InitTraceLevels -- TRC_BTIF
W/libprocessgroup( 1030): failed to open /acct/uid_10004/pid_5767/cgroup.procs: No such file or directory
V/QRemote ( 6467): [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.widget_ui_update
E/QRemote ( 6467): [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
D/QRemote ( 6467): [RemoteAppWidgetProvider.java:171:onReceive()] oooooo total:0
D/QRemote ( 6467): [RemoteAppWidgetProvider.java:172:onReceive()] oooooo selected:0
D/QRemote ( 6467): [RemoteAppWidgetProvider.java:173:onReceive()] oooooo arr:[]
D/QRemote ( 6467): [RemoteAppWidgetProvider.java:174:onReceive()] oooooo appWidgetId:3
D/QRemote ( 6467): [RemoteAppWidgetProvider.java:815:updateRemoteViews()] oooooo UpdateRemoteViews3:widgetId:3
W/bt-btm  ( 6276): btm_decode_ext_features_page Secure conn Controller support Enabled
E/bt-btm  ( 6276): BTM_SecRegister:p_cb_info->p_le_callback == 0xa01da061 
E/bt-btm  ( 6276): BTM_SecRegister: btm_cb.api.p_le_callback = 0xa01da061 
E/bt-btif ( 6276): Calling BTA_HhEnable
W/bt-l2cap( 6276): L2CAP - L2CA_Register() called for PSM: 0x0019
W/bt-l2cap( 6276): L2CAP - L2CA_Register() called for PSM: 0x0017
W/bt-l2cap( 6276): btif_storage_get_adapter_property service_mask
E/bt-btif ( 6276): btif_storage_get_adapter_property service_mask:0x2140040
W/bt-l2cap( 6276): L2CAP - L2CA_Register() called for PSM: 0x0011
D/BluetoothAdapterProperties( 6276): Address is:58:3F:54:73:64:C0
W/bt-l2cap( 6276): L2CAP - L2CA_Register() called for PSM: 0x0013
D/QRemote ( 6467): [RemoteAppWidgetProvider.java:986:updateRemoteViews()] oooooo updateAppWidget5:widgetId:3]
D/BluetoothManagerService( 1030): Bluetooth Adapter name changed to G3-1
D/BluetoothManagerService( 1030): Stored Bluetooth name: G3-1
D/BluetoothAdapterProperties( 6276): Name is: G3-1
D/BluetoothAdapterProperties( 6276): Scan Mode:20
D/BluetoothAdapterProperties( 6276): Discoverable Timeout:120
D/bt_hci_bdroid( 6276): postload
W/bt-l2cap( 6276): L2CAP - L2CA_Register() called for PSM: 0x000f
D/bt_hci_bdroid( 6276): Used up Tx Cmd credits
D/bt_hci_bdroid( 6276): Used up Tx Cmd credits
D/bt_hci_bdroid( 6276): Used up Tx Cmd credits
D/bte_conf( 6276): Device ID record 1 : primary
D/bte_conf( 6276):   vendorId            = 00c4
D/bte_conf( 6276):   vendorIdSource      = 0001
D/bte_conf( 6276):   product             = 13a1
D/bte_conf( 6276):   version             = 1000
D/bte_conf( 6276):   clientExecutableURL = 
D/bte_conf( 6276):   serviceDescription  = 
D/bte_conf( 6276):   documentationURL    = 
D/bte_conf( 6276): bte_load_did_conf no section named DID2.
E/bt_mct  ( 6276): hci lib postload completed
D/BluetoothAdapterState( 6276): CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
W/sh      ( 6516): type=1400 audit(0.0:159): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6815 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
W/sh      ( 6516): type=1400 audit(0.0:160): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6815 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
D/BluetoothAdapterProperties( 6276): ScanMode =  20
D/BluetoothAdapterProperties( 6276): State =  11
W/bt-smp  ( 6276): Key(LSB ~ MSB) = 0a 3c a6 fe eb 17 6a 79 a6 1f 0a 0b f9 50 a0 5f 
W/bt-smp  ( 6276): Plain text(LSB ~ MSB) = f8 1b 77 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 6276): Encrypted text(LSB ~ MSB) = 5d 60 c8 a4 e3 b0 0e 0b 96 50 29 b7 17 f7 1f 50 
D/BluetoothAdapterProperties( 6276): mDiscoverableTimeout = 120
W/bt-btm  ( 6276): Stopping oneshot timer
V/LGBluetoothServiceAdapter( 6276): [BTUI] state:11, scanmode:20, timeout:120
D/BluetoothAdapterProperties( 6276): Setting state to 12
I/BluetoothAdapterState( 6276): Bluetooth adapter state changed: 11-> 12
D/BluetoothManagerService( 1030): Message: 60
D/BluetoothManagerService( 1030): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
D/BluetoothManagerService( 1030): Broadcasting onBluetoothStateChange(true) to 5 receivers.
I/BluetoothAdapterState( 6276): Entering On State
D/BluetoothPanServiceJni( 6276): control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
D/btif_config_util( 6276): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
D/BluetoothHeadset( 1852): onBluetoothStateChange: up=true
D/LGBluetoothServiceAdapter( 6276): [BTUI] OnState
D/LGBluetoothServiceAdapter( 6276): [BTUI]         global_name: G3-1
D/LGBluetoothServiceAdapter( 6276): [BTUI]         local_name: G3-1
D/BluetoothAdapterService( 6276): [BTUI] autoConnect() : not allowed
D/BluetoothHeadset( 1852): onBluetoothStateChange: up=true
D/BluetoothA2dp( 1030): onBluetoothStateChange: up=true
D/BluetoothHeadset( 1030): onBluetoothStateChange: up=true
W/bt-smp  ( 6276): Key(LSB ~ MSB) = 0a 3c a6 fe eb 17 6a 79 a6 1f 0a 0b f9 50 a0 5f 
W/bt-smp  ( 6276): Plain text(LSB ~ MSB) = 9c d7 5d 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 6276): Encrypted text(LSB ~ MSB) = 60 64 d5 83 20 62 74 db 25 38 0d 6a 85 8c 32 43 
W/bt-btm  ( 6276): Stopping oneshot timer
D/BluetoothHeadset( 1852): onBluetoothStateChange: up=true
E/BluetoothManagerService( 1030): Fail to bind to: Intent { act=android.bluetooth.IQBluetooth }
D/BluetoothManagerService( 1030): Bluetooth State Change Intent: 11 -> 12
D/LGBluetoothAPIService( 1953): [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
I/[SystemUI]BluetoothHandler( 1457): Receive : BluetoothAdapter.ACTION_STATE_CHANGED
D/LGBluetoothAPIService( 1953): Message: 1
D/LGBluetoothAPIService( 1953): MESSAGE_BOOT_COMPLETED
W/bt-smp  ( 6276): Key(LSB ~ MSB) = 0a 3c a6 fe eb 17 6a 79 a6 1f 0a 0b f9 50 a0 5f 
W/bt-smp  ( 6276): Plain text(LSB ~ MSB) = af aa 65 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 6276): Encrypted text(LSB ~ MSB) = 9a 81 ea eb 81 7a 7f 82 b8 5f 5d 87 7e ee 7a 3b 
W/bt-btm  ( 6276): Stopping oneshot timer
D/BluetoothManagerService( 1030): BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
D/BluetoothManagerService( 1030): Message: 40
D/BluetoothManagerService( 1030): MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
I/LGBluetoothAPIService( 1953): [BTUI] LGBluetoothAPIService Binding Success
I/BluetoothMapService( 6276): onReceive: android.bluetooth.adapter.action.STATE_CHANGED
D/BluetoothMapService( 6276): STATE_ON
W/bt-smp  ( 6276): Key(LSB ~ MSB) = 0a 3c a6 fe eb 17 6a 79 a6 1f 0a 0b f9 50 a0 5f 
W/bt-smp  ( 6276): Plain text(LSB ~ MSB) = 26 8c 50 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 6276): Encrypted text(LSB ~ MSB) = b6 ed e5 b6 31 fd a9 0b 81 21 b4 7a 20 f5 29 e1 
W/bt-btm  ( 6276): Stopping oneshot timer
D/LGBluetoothAPIServer( 6276): [BTUI] onCreate()
V/BluetoothMapService( 6276): Handler(): got msg=1
D/BluetoothMapMasInstance( 6276): Map Service startRfcommSocketListener
D/LGBluetoothAPIServer( 6276): [BTUI] onBind()
D/LGBluetoothDeviceModeControllManager( 6276): [BTUI] checkDeviceModeAndSet, sinkMode : false
D/BluetoothMapMasInstance( 6276): MAS initSocket()
D/BluetoothMapMasInstance( 6276):   masId = 00
D/BluetoothMapMasInstance( 6276):   msgTypes = 0e
D/BluetoothMapMasInstance( 6276):   masName = SMS/MMS
D/BluetoothMapMasInstance( 6276):   SDP string = 000eSMS/MMS
D/BluetoothAdapterService( 6276): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@5b2a254
V/BluetoothPbapService( 6276): Pbap Service onCreate
V/BluetoothPbapService( 6276): Starting PBAP service
W/bt-smp  ( 6276): Key(LSB ~ MSB) = 0a 3c a6 fe eb 17 6a 79 a6 1f 0a 0b f9 50 a0 5f 
W/bt-smp  ( 6276): Plain text(LSB ~ MSB) = 19 9b 4c 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 6276): Encrypted text(LSB ~ MSB) = 5e 74 f5 2f 13 2e c6 bd c2 50 b4 dc 84 31 f0 46 
W/bt-btm  ( 6276): Stopping oneshot timer
D/LGBluetoothAPIService( 1953): [BTUI] LGBluetoothAPIServiceConnection: connected to LGBluetoothAPIAdapter
D/LGBluetoothAPIService( 1953): Message: 100
D/LGBluetoothAPIService( 1953): MESSAGE_BLUETOOTH_SERVICE_CONNECTED
D/BluetoothManagerService( 1030): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/LGBluetoothPbapAdapter( 6276): [BTUI] getInstance : create
V/BluetoothPbapService( 6276): action: android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothPbapService( 6276): state: 12
V/BluetoothPbapService( 6276): Handler(): got msg=1
V/BluetoothPbapService( 6276): Pbap Service startRfcommSocketListener
W/BluetoothAdapter( 6276): getBluetoothService() called with no BluetoothManagerCallback
D/LGBluetoothServiceAdapter( 6276): [BTUI] createSocketChannel FD=73 mFd=0
V/BluetoothMapMasInstance( 6276): Succeed to create listening socket 
D/BluetoothMapMasInstance( 6276): Accepting socket connection...
V/BluetoothPbapService( 6276): Pbap Service initSocket
D/BluetoothManagerService( 1030): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
W/BluetoothAdapter( 6276): getBluetoothService() called with no BluetoothManagerCallback
D/LGBluetoothServiceAdapter( 6276): [BTUI] createSocketChannel FD=75 mFd=73
V/BluetoothPbapService( 6276): Succeed to create listening socket 
V/BluetoothPbapService( 6276): Accepting socket connection...
I/qcom-bt-wlan-coex( 6528): /system/etc/init.qcom.coex.sh: btwlancoex/abtfilt not available 
W/ContextImpl( 6308): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
V/BluetoothPbapReceiver( 6276): PbapReceiver onReceive 
V/BluetoothPbapReceiver( 6276): ***********action = android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothPbapReceiver( 6276): ***********state = 12
D/LocalBluetoothProfileManager( 6308): Adding local A2DP profile
D/BluetoothManagerService( 1030): Message: 30
D/LocalBluetoothProfileManager( 6308): Adding local HEADSET profile
D/BluetoothManagerService( 1030): Message: 30
D/BluetoothManagerService( 1030): Message: 30
D/BluetoothManagerService( 1030): Message: 30
D/LocalBluetoothProfileManager( 6308): Adding local MAP profile
D/BluetoothMap( 6308): Create BluetoothMap proxy object
D/BluetoothManagerService( 1030): Message: 30
D/BluetoothManagerService( 1030): Message: 30
D/LocalBluetoothProfileManager( 6308): LocalBluetoothProfileManager construction complete
V/BluetoothPbapService( 6276): Pbap Service onBind
D/LGBluetoothUserBindClient( 6308): [BTUI] initUserBindClient
W/ContextImpl( 6308): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.android.settings.bluetooth.LGBluetoothUserBindClient.initUserBindClient:90 com.android.settings.bluetooth.LGBluetoothUserBindClient.<init>:55 com.android.settings.bluetooth.LGBluetoothUserBindClient.getInstance:47 
D/DockEventReceiver( 6308): finishStartingService: stopping service
D/BluetoothA2dp( 6308): Proxy object connected
D/A2dpProfile( 6308): Bluetooth service connected
D/BluetoothHeadset( 6308): Proxy object connected
D/HeadsetProfile( 6308): Bluetooth service connected
D/BluetoothInputDevice( 6308): Proxy object connected
D/HidProfile( 6308): Bluetooth service connected
D/BluetoothPan( 6308): BluetoothPAN Proxy object connected
D/PanProfile( 6308): Bluetooth service connected
D/BluetoothMap( 6308): Proxy object connected
D/MapProfile( 6308): Bluetooth service connected
D/BluetoothMap( 6308): getConnectedDevices()
V/BluetoothMapService( 6276): getConnectedDevices()
D/BluetoothPbap( 6308): Proxy object connected
D/PbapServerProfile( 6308): Bluetooth service connected
D/LGBluetoothUserBindClient( 6308): [BTUI] onServiceConnected
D/BluetoothPermissionRequest( 6308): onReceive
D/LGBluetoothFeatureConfig( 6308): isPrivacyLogsEnabled : true
D/LGBluetoothUtils( 6308): [BTUI] FileNotFound: readProperty
D/BluetoothAdapterProperties( 6276): Discoverable Timeout:120
D/LGBluetoothDeviceModeControllManager( 6276): adapterPropertyChangedCallback on  LGAdapter : do nothing - 9
D/BluetoothAdapterProperties( 6276): Scan Mode:21
D/LGBluetoothDeviceModeControllManager( 6276): getDeviceMode  deviceMode 0
D/LGBluetoothResetSettingReceiver( 6308): return without doing reset settings.
V/BluetoothOppReceiver( 6276): Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_ON
I/LGBluetoothOppAdapter( 6276): [BTUI] startOppService()
V/BluetoothOppManager( 6276): restoreApplicationData! falsefalsenullnull
E/WifiStateMachine( 1030):  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1030):  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1030):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1030):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1030):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1030):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
D/ConnectivityService( 1030): Update of LinkProperties for NetworkAgentInfo [WIFI () - 100]; created=false
D/LGBluetoothFeatureConfig( 6276): isPrivacyLogsEnabled : true
V/BtOppService( 6276): onCreate
V/BluetoothOppNotification( 6276): send message
V/BtOppService( 6276): Starting RfcommListener
D/BluetoothOppPreference( 6276): Dumping Names:  
D/BluetoothOppPreference( 6276): {}
D/BluetoothOppPreference( 6276): Dumping Channels:  
D/BluetoothOppPreference( 6276): {}
V/BtOppService( 6276): onStartCommand
V/BtOppService( 6276): pendingUpdate is true keepUpdateThread is false sListenStarted is true
V/BluetoothFtpReceiver( 6276): BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothFtpReceiver( 6276): BluetoothFtpReceiver Start Service
V/BluetoothOppNotification( 6276): new notify threadi!
V/BluetoothOppNotification( 6276): send delay message
V/BtOppService( 6276): start RfcommListener
V/BtOppService( 6276): RfcommListener started
V/BtOppRfcommListener( 6276): Starting RFCOMM listener....
D/BluetoothManagerService( 1030): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
W/BluetoothAdapter( 6276): getBluetoothService() called with no BluetoothManagerCallback
D/LGBluetoothServiceAdapter( 6276): [BTUI] createSocketChannel FD=79 mFd=75
V/BtOppRfcommListener( 6276): Started RFCOMM listener....
I/BtOppRfcommListener( 6276): Accept thread started.
V/BtOppRfcommListener( 6276): Accepting connection...
V/BluetoothOppProvider( 6276): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
V/BtOppService( 6276): Deleted complete outbound shares, number =  0
V/BtOppService( 6276): Deleted complete inbound failed shares, number = 0
V/BluetoothOppProvider( 6276): starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
V/BluetoothOppProvider( 6276): starting query, database is not null; projection[0] is _id; selection is direction=1 AND status=200 AND visibility=1; selectionArgs is null; sort is _id.
V/BluetoothOppProvider( 6276): created cursor android.database.sqlite.SQLiteCursor@37c20e4e on behalf of 
I/dhcpcd  ( 6477): wlan0: acknowledged 192.168.1.141 from 192.168.1.1
V/BluetoothOppProvider( 6276): created cursor android.database.sqlite.SQLiteCursor@3c500b6f on behalf of 
V/BluetoothOppNotification( 6276): mUpdateCompleteNotification = true
V/BluetoothOppProvider( 6276): created cursor android.database.sqlite.SQLiteCursor@186ae07c on behalf of 
V/BluetoothOppProvider( 6276): starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
V/BtOppService( 6276): pendingUpdate is false keepUpdateThread is false sListenStarted is true
V/BluetoothOppProvider( 6276): created cursor android.database.sqlite.SQLiteCursor@11cf8d05 on behalf of 
V/BluetoothOppNotification( 6276): outbound: succ-0  fail-0
V/BluetoothOppNotification( 6276): outbound notification was removed.
D/BluetoothAdapterService( 6276): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@5b2a254
V/BluetoothFtpService( 6276): Ftp Service onCreate
I/BluetoothFtpService( 6276): Ftp Service onCreate
V/BluetoothFtpService( 6276): Ftp Service onStartCommand
V/BluetoothFtpService( 6276): action: android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothFtpService( 6276): Starting Listening on sockets
V/BluetoothSapReceiver( 6276): [BTUI] checkServiceStart
V/BluetoothSapReceiver( 6276): [BTUI] region:EU country:EU
V/BluetoothSapReceiver( 6276): SapReceiver onReceive 
V/BluetoothSapReceiver( 6276): action = android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothSapReceiver( 6276):  Bluetooth Adapter state = 12
V/BluetoothSapReceiver( 6276): Calling SAP service start service with action = null
V/BtOppService( 6276): ContentObserver received notification
V/BtOppService( 6276): ContentObserver received notification
V/BluetoothFtpService( 6276): Handler(): got msg=1
V/BluetoothFtpService( 6276): Ftp Service startRfcommSocketListener
V/BtOppService( 6276): pendingUpdate is true keepUpdateThread is false sListenStarted is true
V/BluetoothFtpService( 6276): Ftp Service initSocket
V/BluetoothOppProvider( 6276): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
V/BluetoothOppProvider( 6276): created cursor android.database.sqlite.SQLiteCursor@3fbef8b on behalf of 
V/BluetoothOppNotification( 6276): update too frequent, put in queue
V/BtOppService( 6276): pendingUpdate is false keepUpdateThread is false sListenStarted is true
V/BluetoothOppProvider( 6276): starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
V/BluetoothOppProvider( 6276): created cursor android.database.sqlite.SQLiteCursor@5c38868 on behalf of 
D/AuthorizationBluetoothService( 2121): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
V/BluetoothOppNotification( 6276): inbound: succ-0  fail-0
D/BluetoothManagerService( 1030): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
W/BluetoothAdapter( 6276): getBluetoothService() called with no BluetoothManagerCallback
V/BluetoothOppNotification( 6276): inbound notification was removed.
V/BluetoothOppProvider( 6276): starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
D/LGBluetoothServiceAdapter( 6276): [BTUI] createSocketChannel FD=80 mFd=79
V/BluetoothOppProvider( 6276): created cursor android.database.sqlite.SQLiteCursor@3040f481 on behalf of 
V/BluetoothFtpService( 6276): Succeed to create listening socket on channel 20
V/BluetoothFtpService:RfcommSocketAcceptThread( 6276): Run Accept thread
I/dhcpcd  ( 6477): wlan0: leased 192.168.1.141 for 86400 seconds
D/dhcpcd  ( 6477): wlan0: adding IP address 192.168.1.141/24
D/dhcpcd  ( 6477): wlan0: adding route to 192.168.1.0/24
D/dhcpcd  ( 6477): wlan0: adding default route via 192.168.1.1
D/dhcpcd  ( 6477): wlan0: writing lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
D/dhcpcd  ( 6477): getUsingAPMacAddress: c0:ff:d4:d3:aa:48 , return 1
D/dhcpcd  ( 6477): write_lease_ext: /data/misc/dhcp/dhcpcd-wlan0-c0:ff:d4:d3:aa:48.lease2
D/dhcpcd  ( 6477): wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason REBOOT
E/WifiStateMachine( 1030):  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
D/BluetoothAdapterService( 6276): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@5b2a254
V/BluetoothSapService( 6276): Sap Service onCreate
E/WifiStateMachine( 1030):  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1030):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1030):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
V/BluetoothSapService( 6276): action: android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothSapService( 6276): state: 12
V/BluetoothSapService( 6276): Starting SAP server process
E/WifiStateMachine( 1030):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1030):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
D/ConnectivityService( 1030): Update of LinkProperties for NetworkAgentInfo [WIFI () - 100]; created=false
V/BluetoothSapService( 6276): SAP Service startRfcommListenerThread
V/BluetoothSapService( 6276): Sap Service initRfcommSocket
D/BluetoothManagerService( 1030): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
W/BluetoothAdapter( 6276): getBluetoothService() called with no BluetoothManagerCallback
W/sapd    ( 6547): type=1400 audit(0.0:161): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6815 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
W/sapd    ( 6547): type=1400 audit(0.0:162): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6815 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
D/LGBluetoothServiceAdapter( 6276): [BTUI] createSocketChannel FD=82 mFd=80
V/BluetoothSapService( 6276): Succeed to create listening socket 
V/BluetoothSapService( 6276): Accepting socket connection...
D/sensors_hal_Time( 1030): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1030): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1030): tsOffsetIs: Apps: 277439991043; DSPS: 9231871; Offset : -4304407056
V/BT_SAP  ( 6547): Event pipe created
V/BT_SAP  ( 6547): create_server_socket qcom.sap.server
V/BT_SAP  ( 6547): created socket fd 6
D/DhcpStateMachine( 1030): DHCPV4 succeeded on wlan0
D/LgDhcpStateMachineHelper( 1030): CheckDhcpDirectory [Lease File Count] : 3
V/LgDhcpStateMachineHelper( 1030): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
D/LgDhcpStateMachineHelper( 1030): checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.141
V/LgDhcpStateMachineHelper( 1030): Add DhcpResults: IP address 192.168.1.141/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 86400 seconds
V/DhcpStateMachine( 1030): Current State is mWaitBeforeStartState.
V/LgDhcpStateMachineHelper( 1030): bShouldSendDhcpAction Result: true
D/DhcpStateMachine( 1030): DHCP Start/Renew wake lock is released.
D/DhcpStateMachine( 1030): RunningState
E/WifiStateMachine( 1030):  ObtainingIpState CMD_POST_DHCP_ACTION 1 0 OK  v4
E/WifiStateMachine( 1030):  L2ConnectedState CMD_POST_DHCP_ACTION 1 0 OK  v4
D/WifiNative-wlan0( 1030): doBoolean: DRIVER BTCOEXMODE 2
D/LGWifiP2pService( 1030): InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 6321): wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
D/LGWifiP2pService( 1030): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0( 1030): DRIVER BTCOEXMODE 2: returned true
D/WifiNative-wlan0( 1030): doBoolean: DRIVER SETSUSPENDMODE 1
I/wpa_supplicant( 6321): wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 1
D/WifiNative-wlan0( 1030): DRIVER SETSUSPENDMODE 1: returned true
D/WifiNative-wlan0( 1030): doBoolean: SET ps 1
D/WifiNative-wlan0( 1030): SET ps 1: returned true
D/ConnectivityService( 1030): Update of LinkProperties for NetworkAgentInfo [WIFI () - 100]; created=false
E/WifiStateMachine( 1030):  ObtainingIpState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
E/WifiStateMachine( 1030):  L2ConnectedState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
E/WifiStateMachine( 1030): WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
D/ConnectivityService( 1030): ignoring duplicate network state non-change
D/ConnectivityService( 1030): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
I/StatusBar.NetworkController( 1457): networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1457): mWifiConnected = false, mWifiLevel = 0
W/Settings( 1030): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1030): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1030): NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
D/ConnectivityService( 1030): Adding iface wlan0 to network 100
D/PostponalbeReceiver( 5178): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
W/Settings( 1030): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1030): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1030): NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
D/WifiHS20( 1030): [PASSPOINT] passpointNotification: hs20AP list is checked
W/Settings( 1030): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1030): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1030): NETWORK_STATE_CHANGED_ACTION [CONNECTED]
V/WfdStateTracker( 1953): handleWifiStateChangedEvent: 1
D/StatusBar.NetworkController( 1457): refreshViews: Data not connected!! Set no data type icon / Roaming
E/ConnectivityService( 1030): Unexpected mtu value: 0, wlan0
D/ConnectivityService( 1030): Adding Route [fe80::/64 -> :: wlan0] to network 100
D/ConnectivityService( 1030): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 100
D/ConnectivityService( 1030): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 100
D/ConnectivityService( 1030): addLocalRoutetoDefaultNetwork
D/ConnectivityService( 1030): defaultNAI is null or Wi-Fi no need to add Loacal route to default network. WiFi netid = 100
D/ConnectivityService( 1030): Setting Dns servers for network 100 to [/192.168.1.1]
I/StatusBar.NetworkController( 1457): networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1457): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1457): refreshViews: Data not connected!! Set no data type icon / Roaming
D/WifiHS20( 1030): [PASSPOINT] passpointNotification: hs20AP list is checked
W/Settings( 1030): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1030): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1030): NETWORK_STATE_CHANGED_ACTION [CONNECTED]
D/Nat464Xlat( 1030): requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
D/ConnectivityService( 1030): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService( 1030): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 100]
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1030): DefaultState{ when=-1ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1030): Connected
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1030): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1030): Checking http://clients3.google.com/generate_204 on "NG700"
D/ConnectivityService( 1030): rematching NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService( 1030):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService( 1030):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1030):     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
D/ConnectivityService( 1030):   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1030):     satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:true
D/ConnectivityService( 1030): currentScore = 0, newScore = 20
D/ConnectivityService( 1030):    accepting network in place of null
D/ConnectivityService( 1030): sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/libc-netbsd(  307): res_queryN name = clients3.google.com, class = 1, type = 28
E/WifiStateMachine( 1030): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
D/ConnectivityService( 1030): Setting tx/rx TCP buffers to 524288,1048576,2097152,262144,524288,1048576
D/TelephonyNetworkFactory-1( 1852): new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/TelephonyNetworkFactory-1( 1852):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
I/StatusBar.NetworkController( 1457): networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
V/WiFiOffLoadBroadcast( 6308): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WIFI    ( 1030): new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    ( 1030):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/WiFiOffLoadBroadcast( 6308): MCCMNC not supported: null
I/StatusBar.NetworkController( 1457): mWifiConnected = true, mWifiLevel = 3
D/StatusBar.NetworkController( 1457): refreshViews: Data not connected!! Set no data type icon / Roaming
E/ConnectivityService( 1030): [lg_data] Adding agent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::c69a:2ff:fe7b:60ac/64,192.168.1.141/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
D/CSLegacyTypeTracker( 1030): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
D/ConnectivityService( 1030): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/LocSvc_java( 1030): Sending msg: 4 arg1:1 arg2:1
D/QRemote ( 6467): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6467): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
D/LocSvc_java( 1030): getAGpsConnectionInfo connType - 4
D/LocSvc_java( 1030): updateNetworkState connTyp: 4 available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java( 1030): ignore wifi update if we are not in OPENING or CLOSING
D/LocSvc_java( 1030): Sending msg: 5 arg1:0 arg2:1
D/libc-netbsd(  307): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  307): res_queryN name = 2.android.pool.ntp.org, class = 1, type = 1
D/libc-netbsd(  307): res_queryN name = 2.android.pool.ntp.org., class = 1, type = 1
D/DSQN    ( 1030): DNSproblemNotiEnabled is disabled ignore DNS fail CB
D/libc-netbsd(  307): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  307): res_queryN name = europe.pool.ntp.org, class = 1, type = 1
D/libc-netbsd(  307): res_queryN name = europe.pool.ntp.org., class = 1, type = 1
D/DSQN    ( 1030): DNSproblemNotiEnabled is disabled ignore DNS fail CB
D/LocSvc_java( 1030): requestTime failed
D/LocSvc_java( 1030): Sending msg: 10 arg1:0 arg2:1
I/QRemote ( 6467): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
D/ConnectivityService( 1030): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/CSLegacyTypeTracker( 1030): [e] list.add(nai) empty : false size: 1
D/ConnectivityService( 1030): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::c69a:2ff:fe7b:60ac/64,192.168.1.141/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
D/PostponalbeReceiver( 5178): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
D/ConnectivityService( 1030): validation of new default Network = false
D/ConnectivityService( 1030): Default network via Wi-Fi connected. start DSQN
D/DSQN    ( 1030): enableDataServiceNotify 
D/DSQN    ( 1030): start dsqn bin
I/StatusBar.NetworkController( 1457): networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1457): mWifiConnected = true, mWifiLevel = 3
D/StatusBar.NetworkController( 1457): refreshViews: Data not connected!! Set no data type icon / Roaming
D/libc-netbsd(  307): res_queryN name = clients3.google.com, class = 1, type = 1
V/WiFiOffLoadBroadcast( 6308): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
V/NetworkPolicy( 1030): [LG_RESTRICTED] checkMobilePolicy_type()
D/WiFiOffLoadBroadcast( 6308): MCCMNC not supported: null
D/ConnectivityService( 1030): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService( 1030):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1030):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1030): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityManager.CallbackHandler( 1457): CM callback handler got msg 524290
W/dsqn    ( 6585): type=1400 audit(0.0:163): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6815 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
W/dsqn    ( 6585): type=1400 audit(0.0:164): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6815 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
D/QRemote ( 6467): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6467): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 6467): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
D/PostponalbeReceiver( 5178): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
I/PCSuite ( 6388): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
D/TelephonyIcons( 1457): null signal icon name: drawable/stat_sys_signal_null
E/DSQN    ( 6585): DSQN ssw
D/StatusBar.NetworkController( 1457): refreshViews: Data not connected!! Set no data type icon / Roaming
D/StatusBar.NetworkController( 1457): refreshViews: Data not connected!! Set no data type icon / Roaming
D/PCSuite ( 6388): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 6308): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/libc-netbsd(  307): res_queryN name = clients3.google.com succeed
D/WiFiOffLoadBroadcast( 6308): MCCMNC not supported: null
D/QRemote ( 6467): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6467): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
D/QRemote ( 6467): [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
I/QRemote ( 6467): [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
I/QRemote ( 6467): [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
D/PostponalbeReceiver( 5178): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
D/LGDataListener(  307): argv[0]=dsqncommand
D/LGDataListener(  307): argv[1]=wlan0
D/LGDataListener(  307): argv[2]=1
D/LGDataListener(  307): notifyDSQN DSQN STARTMONITOR wlan0 1
D/DSQN    ( 1030): DSQM DsqnNotification wlan0  1
D/DSQN    ( 1030): start to monitor internet connection
I/PCSuite ( 6388): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
D/PCSuite ( 6388): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 6308): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6308): MCCMNC not supported: null
D/QRemote ( 6467): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6467): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
D/QRemote ( 6467): [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
I/QRemote ( 6467): [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
I/QRemote ( 6467): [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1030): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Fri, 08 Jan 2016 18:41:46 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1452278506374], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1452278506359]}
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
D/ConnectivityManager.CallbackHandler( 1457): CM callback handler got msg 524290
D/ConnectivityService( 1030): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
D/WIFI    ( 1030): new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/TelephonyNetworkFactory-1( 1852): new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    ( 1030):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,D/TelephonyNetworkFactory-1( 1852):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
,D/TelephonyIcons( 1457): null signal icon name: drawable/stat_sys_signal_null
D/StatusBar.NetworkController( 1457): refreshViews: Data not connected!! Set no data type icon / Roaming
D/StatusBar.NetworkController( 1457): refreshViews: Data not connected!! Set no data type icon / Roaming
V/BluetoothOppNotification( 6276): new notify threadi!
V/BluetoothOppNotification( 6276): send delay message
V/BluetoothOppProvider( 6276): starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
,V/BluetoothOppProvider( 6276): created cursor android.database.sqlite.SQLiteCursor@2d0757bd on behalf of 
V/BluetoothOppNotification( 6276): mUpdateCompleteNotification = true
V/BluetoothOppProvider( 6276): starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
V/BluetoothOppProvider( 6276): created cursor android.database.sqlite.SQLiteCursor@20a21b2 on behalf of 
V/BluetoothOppNotification( 6276): outbound: succ-0  fail-0
,V/BluetoothOppNotification( 6276): outbound notification was removed.
V/BluetoothOppProvider( 6276): starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
V/BluetoothOppProvider( 6276): created cursor android.database.sqlite.SQLiteCursor@3640c503 on behalf of 
V/BluetoothOppNotification( 6276): inbound: succ-0  fail-0
,V/BluetoothOppNotification( 6276): inbound notification was removed.
V/BluetoothOppProvider( 6276): starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
V/BluetoothOppProvider( 6276): created cursor android.database.sqlite.SQLiteCursor@38ecfc80 on behalf of 
E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-51 f=2412 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:579561244] gl rssi=-51 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-51 f=2412 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:8] from screen [on:0 period:579561252] gl rssi=-51 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
D/StatusBar.NetworkController( 1457): refreshViews: Data not connected!! Set no data type icon / Roaming
,V/WifiInternetCheck( 1030): Single check msg out of sync, ignoring.
,D/ConnectivityService( 1030): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering( 1030): MasterInitialState.processMessage what=3
D/libc-netbsd(  307): default dns: query_ipv6=0, query_ipv4=1
,D/libc-netbsd(  307): res_queryN name = 2.android.pool.ntp.org, class = 1, type = 1
D/libc-netbsd(  307): res_queryN name = 2.android.pool.ntp.org succeed
,D/PostponalbeReceiver( 5178): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
,D/GpsLocationProvider( 1030): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
I/NetworkMonitor( 5241): type=WIFI subType= reason=null isConnected=true
D/AlarmManagerService( 1030): Setting time of day to sec=1452278509
W/AlarmManagerService( 1030): Unable to set rtc to 1452278509: Invalid argument
,W/ContextImpl( 5178): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
I/ActivityManager( 1030): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=6612 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,I/SecureClockService( 1953): Intent.ACTION_TIME_CHANGED 
W/ActivityManager( 1030): getTasks: caller 10029 is using old GET_TASKS but privileged; allowing
I/[LGHome]LGDateChangeReceiver( 2068): [LGDateChangeReceiver.java:78:updateCalendarShortcut()]date=8 currentDate=-1 dayofweek=6 currentDayOfWeek=-1
D/LIA_Informant_Tips_DateChangeManager( 2679): onReceive() : ACTION_TIME_CHANGED
I/[LGHome]LGCalendarIcon( 2068): [LGCalendarIcon.java:214:makeCalendarBitmap()]Locale = en_US dayofweek= Fri date= 8
I/LIA_Informant_Tips_LogTracer( 2679): [Log Tracer - Schedule Transition] Time Change Event Received : 2016-01-08 19:41:49...... Request
I/LIA_Informant_Tips_LogTracer( 2679): [Log Tracer - Schedule Transition] UserGuide, DATE_UPDATE : working count : 2, total count : 138, new day : false...... Request
D/LIA_Informant_Tips_DateChangeManager( 2679): DateInfo : SmartTips Total Working Day Count = 138
D/LIA_Informant_Tips_DateChangeManager( 2679): DateInfo : UserGuide Working Duration Count = 2
D/LIA_Informant_Tips_DateChangeManager( 2679): DateInfo : Last Date Check Time = 2016-01-08 19:41:49
,I/[LGHome]LGCalendarIcon( 2068): [LGCalendarIcon.java:214:makeCalendarBitmap()]Locale = en_US dayofweek= Fri date= 8
I/[SystemUI]Clock( 1457): onReceive = android.intent.action.TIME_SET
I/[LGHome]Launcher( 2068): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/LgeClockWidgetControlView( 1457): time changed, timezoneChanged : false
V/GLSActivity( 2121): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/KeyguardUpdateMonitor( 1457): handleTimeUpdate
,I/ActivityManager( 1030): Start proc com.google.android.apps.books for service com.google.android.apps.books/.service.SyncService: pid=6634 uid=10054 gids={50054, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager( 1030): Start proc com.android.gallery3d for service com.android.gallery3d/com.lge.gallery.picasa.PicasaService: pid=6651 uid=10027 gids={50027, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
,I/art     ( 1030): Explicit concurrent mark sweep GC freed 77118(3MB) AllocSpace objects, 4(64KB) LOS objects, 33% free, 44MB/66MB, paused 3.402ms total 119.233ms
,I/ActivityManager( 1030): Start proc com.android.chrome for service com.android.chrome/com.google.android.apps.chrome.sync.ChromeBrowserSyncAdapterService: pid=6669 uid=10057 gids={50057, 9997, 3003, 1028, 1015} abi=armeabi-v7a
D/GpsLocationProvider( 1030): updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/[Concierge]Service( 2590): onStartCommand(). Type : 9
,W/ResourcesManager( 6651): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6651): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 6651): Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
W/ResourcesManager( 6651): Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
E/GpsLocationProvider( 1030): No APN found to select.
,I/AppConfig( 6651): Total System Memory = 2995761152
,D/SystemHelper( 6651): region [EU], country [EU], operator [OPEN], sub-operator []
I/AppUp4:AppBoxCP( 6612): onCreate
W/AppUp4:DB( 6612):  [AppBoxDatabaseHelper] construct
I/AppUp4:DB( 6612):  setFingerPrint start
I/AppUp4:DB( 6612):  newfinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys SDK version = 21
,I/ActivityManager( 1030): Killing 5919:com.google.android.apps.docs/u0a61 (adj 15): empty #17
I/ThermalEngine(  326): Thermal-Server: Thermal received msg from  override
I/Thermal-Lib( 3061): Thermal-Lib-Client: Client request sent
I/AppUp4:DB( 6612):  beforefinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys
I/AppUp4:DB( 6612):  SDK version = 21
I/AppUp4:DB( 6612):  beforefinger == newfinger no write in DB
,W/libprocessgroup( 1030): failed to open /acct/uid_10061/pid_5919/cgroup.procs: No such file or directory
D/AppUp4:AppBoxApplication( 6612): AppBoxApplication onCreate()
,I/NetworkStateForAutoUpdateMonitor( 6612): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 6612): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/ReaderUtils( 6634): PortraitW 1440 LandscapeW 2392 SmallestSize 1340 LargestSize 2392 textZoom 4.4999995 isTablet false Memory 256
I/NetworkStateForAutoUpdateMonitor( 6612): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 6612): [onReceive] request level :IDLE....
I/AppUp4:CustModeStarterReceiver( 6612): onReceive
,D/LgDataFeature( 6612): LgDataFeature() Constructor: none
D/LgDataFeature( 6612): LgDataFeature() Constructor Done, null
,D/AppUp4:CustFacade( 6612): Context : android.app.ReceiverRestrictedContext@1da8cda7
D/AppUp4:CustFacade( 6612): isCustomizationCompleted : false
D/AppUp4:CustFacade( 6612): isPhone : true
D/AppUp4:CustModeStarterReceiver( 6612): begin check event
I/AppUp4:CustModeStarterReceiver( 6612): Event For GoodConnectivity
D/AppUp4:CustModeStarterReceiver( 6612): runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
I/VacuumService( 2121): Vacuum at: now=1452278509709 tag=VacuumService
D/AppUp4:CustModeStarterReceiver( 6612): call method handleAsyncCustNotification.
D/AppUp4:CustModeStarterReceiver( 6612): handleAsync isTriedOnce : false
E/AppUp4:CustModeStarterReceiver( 6612): handleAsyncCustNotification do not startCustService
I/ActivityManager( 1030): Killing 5584:com.lge.lockscreensettings/u0a80 (adj 15): empty #17
W/GAV2    ( 6634): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
E/Auth.Api.Credentials( 2338): [CredentialSyncAdapter] Unknown sync event.
,D/DelayedSyncController( 6669): Delaying sync.
D/LGDMClient( 3984): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 3984): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
W/ContextImpl( 3984): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,W/ContextImpl( 3984): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,W/libprocessgroup( 1030): failed to open /acct/uid_10080/pid_5584/cgroup.procs: No such file or directory
D/LGDMClient( 3984): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=3, isUserType=1
I/LGDMClient( 3984): [DmServiceProcessor.java] [processNetworkChanged()] : [91] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
,V/DownloadManager( 3347): Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 3984): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 3984): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
I/BooksApp( 6634): Created application version: 3.2.35 (30235)
V/DownloadManager( 3347): DownloadService onCreate
I/DownloadManager( 3347): in removeSpuriousFiles
V/DownloadManager( 3347): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3347): created cursor android.database.sqlite.SQLiteCursor@1a2b1252 on behalf of 3347
I/DownloadManager( 3347): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGMyGuide_4.40.09_COM_COM_20150430011620058_RELG-D855.apk
I/DownloadManager( 3347): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGBackup_4.50.37_COM_COM_20150608234245157.apk
I/DownloadManager( 3347): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/CalendarProvider_4.2.8_COM_COM_20150304234552863_RELG-D855.apk
I/DownloadManager( 3347): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calendar_4.40.16_COM_COM_20150304234554754_RELG-D855.apk
I/DownloadManager( 3347): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.10_COM_COM_20150521235426173_RELG-D855.apk
I/DownloadManager( 3347): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQVoiceplusN_2.3.3_COM_COM_20150604065210803.apk
I/DownloadManager( 3347): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.11_COM_COM_v2_20150911144028620_RELG-D855_21.apk
I/DownloadManager( 3347): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQMemoplus(LG-D855_user)_20150902050954661.apk
I/DownloadManager( 3347): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/RemoteCall_4.1.10_COM_COM_20150817053748728.apk
I/DownloadManager( 3347): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/rspermlge(6713)_20150901080430397.apk
I/DownloadManager( 3347): in trimDatabase
V/DownloadManager( 3347): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
V/DownloadManager( 3347): created cursor android.database.sqlite.SQLiteCursor@157f923 on behalf of 3347
,I/ActivityManager( 1030): Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=6710 uid=10023 gids={50023, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
V/DownloadManager( 3347): DownloadService onStartCommand
,V/DownloadManager( 3347): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
W/DriveInitializer( 2338): Background init thread started
V/DownloadManager( 3347): created cursor android.database.sqlite.SQLiteCursor@3af653d9 on behalf of 3347
V/DownloadManager( 3347): processing inserted download 1
V/DownloadManager( 3347): processing inserted download 4
V/DownloadManager( 3347): processing inserted download 7
V/DownloadManager( 3347): processing inserted download 8
V/DownloadManager( 3347): processing inserted download 9
V/DownloadManager( 3347): processing inserted download 10
V/DownloadManager( 3347): processing inserted download 16
V/DownloadManager( 3347): processing inserted download 17
V/DownloadManager( 3347): processing inserted download 18
V/DownloadManager( 3347): processing inserted download 21
,W/ContextImpl( 3984): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:141 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:180 android.app.IntentService$ServiceHandler.handleMessage:65 
V/DownloadManager( 3347): DownloadService onDestroy
E/LGDMClient( 3984): [DmNotiService.java] [onCreate()] : [148] : DmNotiService.onCreate()
D/LGDMClient( 3984): [DmNotiService.java] [onStartCommand()] : [182] : in the new onStartCommand()
D/LGDMClient( 3984): [DmNotiService.java] [handleStart()] : [203] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
,E/VoldCmdListener(  278): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  278): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.gms/files/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 2338): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.gms/files
W/ResourcesManager( 6710): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 6710): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 6710): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
W/ResourcesManager( 6710): Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
I/ActivityManager( 1030): Killing 5614:com.google.android.apps.plus/u0a97 (adj 15): empty #17
,E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-50 f=2412 sc=60 link=72 tx=4.2, 0.0, 0.0  rx=3.0 bcn=0 [on:0 tx:0 rx:0 period:2826] from screen [on:0 period:579564090] gl rssi=-50 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-50 f=2412 sc=60 link=72 tx=4.2, 0.0, 0.0  rx=3.0 bcn=0 [on:0 tx:0 rx:0 period:0] from screen [on:0 period:579564090] gl rssi=-50 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
W/libprocessgroup( 1030): failed to open /acct/uid_10097/pid_5614/cgroup.procs: No such file or directory
,I/LGEmail ( 6710): [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
W/DriveInitializer( 2338): Background init thread ended
I/GoogleURLConnFactory( 2121): Using platform SSLCertificateSocketFactory
,W/Uploader( 2121): No account for auth token provided
D/LGEmail ( 6710): user build Type == true (at Util.java isUserModeBuildType 3507)[v:6.41.18]
D/libc-netbsd(  307): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  307): res_queryN name = play.googleapis.com, class = 1, type = 1
I/BooksSync( 6634): Starting books sync
,W/ResourceType( 6710): No package identifier when getting value for resource number 0x00000000
,D/libc-netbsd(  307): res_queryN name = play.googleapis.com succeed
I/jxcore-log( 6195): Test app app.js loaded
I/jxcore-log( 6195): 
I/chromium( 6195): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,I/chromium( 6195): [INFO:SkFontConfigInterface_android.cpp(247)] ---- failed to open </system/fonts/CutiveMono.ttf> as a font
I/chromium( 6195): 
D/LgDataFeature( 6710): LgDataFeature() Constructor: none
D/LgDataFeature( 6710): LgDataFeature() Constructor Done, null
I/art     ( 2121): Explicit concurrent mark sweep GC freed 20024(1111KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 30MB/62MB, paused 1.091ms total 35.989ms
,D/serial_port( 5900): close(fd = 24)
D/libc-netbsd(  307): default dns: query_ipv6=0, query_ipv4=1
,D/libc-netbsd(  307): res_queryN name = www.google.com, class = 1, type = 1
I/UEI.SmartControl( 5900): Serial port is closed.
,D/libc-netbsd(  307): res_queryN name = www.google.com succeed
,D/libc-netbsd(  307): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  307): res_queryN name = clients3.google.com, class = 1, type = 1
D/libc-netbsd(  307): res_queryN name = clients3.google.com succeed
,I/chromium( 6195): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
I/jxcore-log( 6195): --= Surplus to requirements =--
I/jxcore-log( 6195): 
I/jxcore-log( 6195): ****TEST TOOK:  ms ****
I/jxcore-log( 6195): 
I/jxcore-log( 6195): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 6195): 
D/eas_req ( 6710): ---addEventToQueue() easCode=2, requestId=0 (at EasSupport.java addEventToQueue 69)
,D/BooksSync( 6634): started syncMyEbooks
D/UEI.SmartControl( 5900): Internal timer expired: 4
D/UEI.SmartControl( 5900): unbind internal service
V/WifiInternetCheck( 1030): isHttpConnectionAvailable - We got a valid response : 204
I/HubEmail( 6710): JNI_OnLoad()
I/HubEmail( 6710): -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 6710): registerNatives()
I/HubEmail( 6710): -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 6710): registerNativeMethods()
I/HubEmail( 6710): -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/LgeMiscReceiver( 3292): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 3292): action = android.net.conn.CONNECTIVITY_CHANGE
,I/LgeMiscReceiver( 3292): networkInfo.isConnected() = true
W/art     ( 6710): JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
D/PhoneState( 3292): setPdpRejectCasuse : false
W/Settings( 6710): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/ActivityManager( 1030): Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=6774 uid=10062 gids={50062, 9997, 4002, 3003, 1028} abi=armeabi-v7a
,D/libc-netbsd(  307): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  307): res_queryN name = static-avc.lglime.com, class = 1, type = 1
W/Settings( 6710): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Uploader( 2121): No account for auth token provided
,I/chromium( 6195): [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
I/chromium( 6195): 
,V/GLSActivity( 2121): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/DrmBroadcastReceiver( 6774): Receive CONNECTIVITY_ACTION
,D/DrmBroadcastReceiver( 6774): 1  network is available. Sync DRM Time with NTP
V/DrmService( 6774): Service onCreate
D/DrmService( 6774): Received new request = 2
I/DrmSntpClient( 6774): Start Sync process
D/DrmSntpClient( 6774): Server : 0
I/GLSUser ( 2121): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2121): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2121): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2121): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,D/libc-netbsd(  307): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  307): res_queryN name = pool.ntp.org, class = 1, type = 1
D/libc-netbsd(  307): res_queryN name = static-avc.lglime.com succeed
I/ActivityManager( 1030): Start proc com.lge.sizechangable.weather for broadcast com.lge.sizechangable.weather/.layout.WeatherWidget: pid=6799 uid=10085 gids={50085, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,V/GLSActivity( 2121): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/Uploader( 2121): No account for auth token provided
D/libc-netbsd(  307): res_queryN name = pool.ntp.org succeed
,V/FormManager( 6359): There are no updated forms. The schedule will be deleted.
,V/FormManager( 6359): Alarm would be updated, because LastCheckTime has been updated.
V/NotificationService( 1030): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/ZenLog  ( 1030): intercepted: 0|com.google.android.gms|1|null|10005,none
V/NotificationService( 1030): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1030): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1030): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1030): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
I/LGDrmClient( 6774): _DRM_ServiceGet() : Bind lgdrm service
V/ILGDrmService(  319): eDRM_SetDRMTime +++
I/LGDRM   (  319): [DRM] SET TIME : YR=2016, MON=1, DAY=8
I/LGDRM   (  319): [DRM] SET TIME : HR=18, MIN=41, SEC=49
W/GLSActivity( 2121): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2121): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2121): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2121): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2121): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2121): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2121): 	at android.os.Binder.execTransact(Binder.java:446)
,W/ResourcesManager( 1399): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 1399): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
E/BooksAccountManager( 6634): Authentication error
E/BooksAccountManager( 6634): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6634): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6634): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6634): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6634): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6634): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6634): null auth token
D/LgeQuickCoverNLService( 1399): onNotificationPosted
V/ILGDrmService(  319): eDRM_SetDRMTime ---
I/DrmSntpClient( 6774): Synched
D/SmartCoverUpdateMonitor( 1399): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1399): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1399): handleNotificationPosted(true)
D/QuickCircle( 1399): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1399): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1399): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1399): post do add job
D/LgeQuickCoverNotificationData( 1399): add : 2
D/LgeQuickCoverNotificationData( 1399): do add job
D/LgeQuickCoverNotificationData( 1399): showAll3
D/LgeQuickCoverNotificationData( 1399): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/DrmService( 6774): Completed !! request = 2
D/LgeQuickCoverNotificationData( 1399): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
D/LgeQuickCoverNotificationData( 1399): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
E/LgeQuickCoverOverlayWindow( 1399): showNotificationWithSetupData: display=false
D/DrmService( 6774): Request count = 0
D/LgeQuickCoverOverlayWindow( 1399): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1399): isNotificationForCurrentUser : true
V/DrmService( 6774): Service onDestroy
I/ActivityManager( 1030): Killing 5973:com.lge.eula/1000 (adj 15): empty #17
D/LgeQuickCoverOverlayWindow( 1399): [native noti] inex =  1
D/AndroidRuntime( 6793): 
D/AndroidRuntime( 6793): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
W/ResourcesManager( 1457): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
D/AndroidRuntime( 6793): CheckJNI is OFF
W/ResourcesManager( 1457): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
I/art     ( 6799): Almond Protected OAT
,D/libc-netbsd(  307): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  307): res_queryN name = www.googleapis.com, class = 1, type = 1
D/libc-netbsd(  307): res_queryN name = www.googleapis.com succeed
,D/LgeQuickCoverNotificationData( 1399): isNotificationForCurrentUser : true
,W/libprocessgroup( 1030): failed to open /acct/uid_1000/pid_5973/cgroup.procs: No such file or directory
,V/GLSActivity( 2121): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/ActivityManager( 1030): Killing 6011:com.google.android.gms.wearable/u0a5 (adj 15): empty #17
D/WeatherApplication( 6799): removeAccount
,D/AndroidRuntime( 6793): Calling main entry com.android.commands.pm.Pm
,W/Uploader( 2121): No account for auth token provided
D/WeatherApplication( 6799): Account.length = 0
E/WeatherApplication( 6799): OPERATOR:OPEN
D/WeatherAncestor( 6799): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 19:41:50
W/PackageSettings( 1030): Skipping PackageSetting{253b8a7f com.example.hello/10319} due to missing metadata
,D/Weather.Utils( 6799): 2 : the weather widgets(using time tick) are gone.
D/Weather.Utils( 6799): 2 : All the weather widget is gone.
D/UpdateThreadPoolManager( 6799): 2 : This is isUpdating : false
D/WeatherAncestor( 6799): connectivity changed - connection : true
D/WeatherService( 6799): 2 : isServiceAlived():false forecastCache:null
,D/ForecastDataCache( 6799): 2 : lastUpdatedTime: 1430558561343
D/ForecastDataCache( 6799): 2 : currentPackageVersion: 4.40.4
D/ForecastDataCache( 6799): 2 : Cache is not up-to-date, count: 0
I/art     ( 1030): Explicit concurrent mark sweep GC freed 31307(1704KB) AllocSpace objects, 4(64KB) LOS objects, 33% free, 44MB/66MB, paused 1.506ms total 75.200ms
,I/ActivityManager( 1030): Force stopping com.test.thalitest appid=10311 user=-1: uninstall pkg
D/LgeQuickCoverOverlayWindow( 1399): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1399): isNotificationForCurrentUser : true
I/ActivityManager( 1030): Killing 6195:com.test.thalitest/u0a311 (adj 0): stop com.test.thalitest
E/LgeQuickCoverOverlayWindow( 1399): updateNotificationData: count=3
D/QuickStatusbarLayout( 1399): Notification difference=198
D/QuickStatusbarLayout( 1399): child = android.widget.LinearLayout{3c500b6f V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
D/Weather_cast( 6799): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherAncestor( 6799): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 19:41:50
I/WindowState( 1030): WIN DEATH: Window{351b6b58 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,D/WifiService( 1030): Client connection lost with reason: 4
D/InputDispatcher( 1030): Window went away: Window{351b6b58 u0 com.test.thalitest/com.test.thalitest.MainActivity}
W/ApiaryClient( 6634): Error response from books API: {
W/ApiaryClient( 6634):  "error": {
W/ApiaryClient( 6634):   "errors": [
W/ApiaryClient( 6634):    {
W/ApiaryClient( 6634):     "domain": "global",
W/ApiaryClient( 6634):     "reason": "required",
W/ApiaryClient( 6634):     "message": "Login Required",
W/ApiaryClient( 6634):     "locationType": "header",
W/ApiaryClient( 6634):     "location": "Authorization"
W/ApiaryClient( 6634):    }
W/ApiaryClient( 6634):   ],
W/ApiaryClient( 6634):   "code": 401,
W/ApiaryClient( 6634):   "message": "Login Required"
W/ApiaryClient( 6634):  }
W/ApiaryClient( 6634): }
,W/ApiaryClient( 6634): errCount = 1: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6634): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-6371522681661194489&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6634): Headers:
W/ApiaryClient( 6634): accept-encoding: [gzip]
W/ApiaryClient( 6634): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6634): gdata-version: 2
I/ActivityManager( 1030):   Force finishing activity ActivityRecord{6765412 u0 com.test.thalitest/.MainActivity t4}
,E/GBMv2   (  334): DFP En is all cleared set to be enabled
I/ActivityManager( 1030): Force stopping com.test.thalitest appid=10311 user=0: pkg removed
I/ActivityManager( 1030):   Force finishing activity ActivityRecord{6765412 u0 com.test.thalitest/.MainActivity t4 f}
W/ActivityManager( 1030): Duplicate finish request for ActivityRecord{6765412 u0 com.test.thalitest/.MainActivity t4 f}
,W/libprocessgroup( 1030): failed to open /acct/uid_10005/pid_6011/cgroup.procs: No such file or directory
,D/LIA_Service_RemotePackageHandler( 2030): onReceive action : android.intent.action.PACKAGE_REMOVED = package:com.test.thalitest
D/LIA_MrGDBLogger_PackageInfoDetector( 2679): [dreamwood]action: android.intent.action.PACKAGE_REMOVED, package: com.test.thalitest
,E/LGBluetoothAvrcpQcomAdapter( 6276): [BTUI] [BTUI] onReceive()... android.intent.action.PACKAGE_REMOVED
D/LGBluetoothAvrcpQcomAdapter( 6276): [BTUI] [+] updateMediaPlayerInfo
W/System.err( 4210): android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
W/System.err( 4210): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
W/System.err( 4210): 	at com.lge.mlt.MptOnAppWatcher$1.onReceive(MptOnAppWatcher.java:44)
W/System.err( 4210): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:956)
W/System.err( 4210): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 4210): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 4210): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 4210): 	at android.app.ActivityThread.main(ActivityThread.java:5274)
W/System.err( 4210): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 4210): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 4210): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
W/System.err( 4210): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
I/art     ( 4248): Explicit concurrent mark sweep GC freed 15196(885KB) AllocSpace objects, 0(0B) LOS objects, 34% free, 29MB/45MB, paused 565us total 34.397ms
,I/InputReader( 1030): Reconfiguring input devices.  changes=0x00000010
W/GeofencerStateMachine( 1817): Ignoring removeGeofence because network location is disabled.
V/SIM_STK ( 1030): Menu title from STK is T-Mobile
,D/SplitUIManager( 1869): split_name #11 / not available #0
D/SplitUIService( 1869): removed split : 
I/ActivityManager( 1030): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=6839 uid=10093 gids={50093, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager( 1030): Killing 6088:com.google.android.talk/u0a72 (adj 15): empty #17
D/SplitUIManager( 1869): split_name #11 / not available #0
I/SplitUIService( 1869): split app #11
V/SIM_STK ( 1030): Menu title from STK is T-Mobile
V/SIM_STK ( 1030): Menu title from STK is T-Mobile
,D/administrator( 1030): Handling package changes for user 0
,V/SIM_STK ( 1030): Menu title from STK is T-Mobile
I/art     ( 1030): Explicit concurrent mark sweep GC freed 6407(408KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 44MB/66MB, paused 2.469ms total 156.797ms
,W/ActivityManager( 1030): Spurious death for ProcessRecord{2cc66c9 6195:com.test.thalitest/u0a311}, curProc for 6195: null
I/[LGHome]EVENT( 2068): [Launcher.java:5338:onStart()]onStart
I/[LGHome]EVENT( 2068): [Launcher.java:903:onResume()]onResume
I/[LGHome]EVENT( 2068): [LauncherModel.java:1352:startLoader()]startLoader isLaunching=true
I/[LGHome]Launcher.Model( 2068): [LauncherModel.java:1469:loadAndBindWorkspace()]loadAndBindWorkspace=0ms
,W/libprocessgroup( 1030): failed to open /acct/uid_10072/pid_6088/cgroup.procs: No such file or directory
W/ActivityManager( 1030): getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
D/LGBluetoothAvrcpQcomAdapter( 6276): [BTUI] installed app name: Music
D/LGBluetoothAvrcpQcomAdapter( 6276): [BTUI] installed app name: Google Play Music
D/LGBluetoothAvrcpQcomAdapter( 6276): [BTUI] === MediaPlayerInfo (playerId:0) ===
D/LGBluetoothAvrcpQcomAdapter( 6276): [BTUI]          displayName: Music
D/LGBluetoothAvrcpQcomAdapter( 6276): [BTUI]          packageName: com.lge.music
D/LGBluetoothAvrcpQcomAdapter( 6276): [BTUI]          playState: 2 (PAUSED)
D/LGBluetoothAvrcpQcomAdapter( 6276): [BTUI] === MediaPlayerInfo (playerId:1) ===
D/LGBluetoothAvrcpQcomAdapter( 6276): [BTUI]          displayName: Google Play Music
D/LGBluetoothAvrcpQcomAdapter( 6276): [BTUI]          packageName: com.google.android.music
D/LGBluetoothAvrcpQcomAdapter( 6276): [BTUI]          playState: 2 (PAUSED)
D/LGBluetoothAvrcpQcomAdapter( 6276): [BTUI] [-] updateMediaPlayerInfo
W/Uploader( 2121):  no longer exists, so no auth token.
D/SplitWindowPolicy( 1953): updateActivityStateChanged: resumed=false, screenId=0, isScreenFull=false
I/[LGHome]GBoardWebView( 2068): [GBoardWebView.java:306:loadCacheBitmapPostDelayed()]loadCacheBitmapPostDelayed() delay:1
D/SplitWindowPolicy( 1953): topRunningActivity=ActivityInfo{43d8037 co.....Launcher}, taskId=3, activityType=1, bIsSplit=false
D/ActionManagerService( 1905): notifyUserLog: 1000003
I/[LGHome]LGActivityUtil( 2068): [LGActivityUtil.java:319:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
D/SplitWindowPolicy( 1953): updateActivityStateChanged: resumed=true, screenId=0, isScreenFull=false
D/SplitWindowPolicy( 1953): topRunningActivity=ActivityInfo{2cca89a4 co.....Launcher}, taskId=3, activityType=1, bIsSplit=false
I/[LGHome]EVENT( 2068): [Launcher.java:1056:onResume()]onResume end
D/LIA_Informant_ActionManagerMessageHandler( 2679): handleMessage: what(1000) actionID(0x1000003)
,I/[LGHome]EVENT( 2068): [Launcher.java:1114:onPause()]onPause
D/ActionManagerService( 1905): notifyUserLog: 1000004
I/[LGHome]GBoardWebView( 2068): [GBoardWebView.java:247:writeCacheBitmapPostDelayed()]writeCacheBitmapPostDelayed() delay: we don't have a change point1
V/BoardContentProvider( 2679): query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
D/LIA_Informant_ActionManagerMessageHandler( 2679): handleMessage: what(1000) actionID(0x1000004)
I/GBoardWebViewUtils( 2068): checkExpiredAndRemoveCard() card: GBoardCard = { id: mw_initial
I/GBoardWebViewUtils( 2068): , create_time: 1430558575574
I/GBoardWebViewUtils( 2068): , expire_time: 0
I/GBoardWebViewUtils( 2068): , raw_uri: file:///system/etc/mrg_default_forms/MyWellness/initial/initial.html?id=mw_initial
I/GBoardWebViewUtils( 2068): , category: com.lge.intent.category.gboard.MYWELLNESS
I/GBoardWebViewUtils( 2068): , display: false
I/GBoardWebViewUtils( 2068): , animation: false }
I/GBoardWebViewUtils( 2068): checkExpiredAndRemoveCard() card: GBoardCard = { id: dyk000
I/GBoardWebViewUtils( 2068): , create_time: 1430558575600
I/GBoardWebViewUtils( 2068): , expire_time: 0
I/GBoardWebViewUtils( 2068): , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
I/GBoardWebViewUtils( 2068): , category: com.lge.intent.category.gboard.DOYOUKNOW
I/GBoardWebViewUtils( 2068): , display: false
I/GBoardWebViewUtils( 2068): , animation: false }
I/GBoardWebViewUtils( 2068): checkExpiredAndRemoveCard() card: GBoardCard = { id: guide_1111111111116_1452175674810
I/GBoardWebViewUtils( 2068): , create_time: 1452175675684
I/GBoardWebViewUtils( 2068): , expire_time: 0
I/GBoardWebViewUtils( 2068): , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/1/userguide.html?id=guide_1111111111116_1452175674810&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
I/GBoardWebViewUtils( 2068): , category: com.lge.intent.category.gboard.DOYOUKNOW
I/GBoardWebViewUtils( 2068): , display: false
I/GBoardWebViewUtils( 2068): , animation: false }
D/KeyguardModel( 1457): mPackageIntentReceiver, received action: android.intent.action.PACKAGE_REMOVED, sendingUserId:0
I/[LGHome]EVENT( 2068): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
I/[SystemUI]QSlideListController( 1457): onReceive = android.intent.action.PACKAGE_REMOVED
D/WallpaperManager( 2068): suggestDesiredDimensions(2880, 2560) by package(com.lge.launcher2)
I/GLSUser ( 2121): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.syncadapters.contacts, service: cp
I/GLSUser ( 2121): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> cp without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2121): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2121): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2121): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/SystemUI[Framework]( 1030): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x8000, pkg=com.android.systemui
W/PhoneWindowManagerEx( 1030): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx( 1030): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx( 1030): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework]( 1030): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@16fc3356,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework]( 1030): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
I/[SystemUI]AppWidgetPanel(QRemoteWidgetPanel)( 1457): onReceive = android.intent.action.PACKAGE_REMOVED, packageName : com.test.thalitest
D/KeyguardModel( 1457): mPackageIntentReceiver, received action: android.intent.action.PACKAGE_FULLY_REMOVED, sendingUserId:0
,I/[LGHome]GBoardWebView( 2068): [GBoardWebView.java:321:loadCacheBitmap()]loadCacheBitmap()
I/ActivityManager( 1030): Start proc com.lge.lockscreensettings for content provider com.lge.lockscreensettings/.LockSettingsProvider: pid=6860 uid=10080 gids={50080, 9997, 1028, 1015} abi=armeabi-v7a
,I/NotificationService( 1030): action=android.intent.action.PACKAGE_REMOVED queryReplace=false
D/BackupManagerService( 1030): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/JobSchedulerService( 1030): Receieved: android.intent.action.PACKAGE_REMOVED
V/NotificationService( 1030): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/TaskPersister( 1030): removeObsoleteFile: deleting file=4_task.xml
V/NotificationService( 1030): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1030): LED remove() : mLights=0|com.google.android.gms|1|null|10005
,D/NotificationServiceEx( 1030): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1030): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/PhoneStatusBar( 1457): setSystemUiVisibility vis=8000 mask=ffffffff oldVal=0 newVal=8000 diff=8000
,I/[SystemUI]NavigationThemeResource( 1457): NavigationKey Color is changed(BLACK -> WHITE_WITH_SHADOW)
I/[SystemUI]NavigationThemeResource( 1457):  BarMode=4, Theme=WHITE, LightBackground=false (Transparent)
I/[SystemUI]NavigationThemeResource( 1457): , Keyguard show=false, IME shown=false, Panel expanded=false
D/LgeQuickCoverNLService( 1399): onNotificationPosted
D/SmartCoverUpdateMonitor( 1399): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1399): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1399): handleNotificationPosted(true)
D/QuickCircle( 1399): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1399): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1399): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1399): post do just update job
D/LgeQuickCoverNotificationData( 1399): showAll3
D/LgeQuickCoverNotificationData( 1399): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1399): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
D/LgeQuickCoverNotificationData( 1399): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
E/LgeQuickCoverOverlayWindow( 1399): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1399): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1399): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1399): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1399): isNotificationForCurrentUser : true
W/GLSActivity( 2121): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2121): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2121): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2121): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2121): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2121): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2121): 	at android.os.Binder.execTransact(Binder.java:446)
D/LgeQuickCoverOverlayWindow( 1399): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1399): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1399): updateNotificationData: count=3
D/ContactsSyncAdapter( 2121): innerSync failed
D/ContactsSyncAdapter( 2121): com.google.wireless.gdata2.client.AuthenticationException: unable to get auth token android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
D/ContactsSyncAdapter( 2121): 	at com.google.android.syncadapters.contacts.AuthInfo.getAuthToken(AuthInfo.java:45)
D/ContactsSyncAdapter( 2121): 	at com.google.android.syncadapters.contacts.ContactsSyncAdapter.innerPerformSync(ContactsSyncAdapter.java:263)
D/ContactsSyncAdapter( 2121): 	at com.google.android.syncadapters.contacts.ContactsSyncAdapter.onPerformLoggedSync(ContactsSyncAdapter.java:168)
D/ContactsSyncAdapter( 2121): 	at com.google.android.common.LoggingThreadedSyncAdapter.onPerformSync(LoggingThreadedSyncAdapter.java:33)
D/ContactsSyncAdapter( 2121): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
D/ContactsSyncAdapter( 2121): Caused by: android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
D/ContactsSyncAdapter( 2121): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
D/ContactsSyncAdapter( 2121): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
D/ContactsSyncAdapter( 2121): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
D/ContactsSyncAdapter( 2121): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
D/ContactsSyncAdapter( 2121): 	at and,roid.os.Binder.execTransact(Binder.java:446)
,D/QuickStatusbarLayout( 1399): Notification difference=198
,D/QuickStatusbarLayout( 1399): child = android.widget.LinearLayout{3c500b6f V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
D/AndroidRuntime( 6793): Shutting down VM
,I/[LGHome]EVENT( 2068): [Launcher.java:5349:onStop()]onStop
I/LockScreenSettings( 6860): Wallpaper base directory = /data/user/0/com.lge.lockscreensettings/files/
,D/KeyguardModel( 1457): package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
D/KeyguardModel( 1457): createShortcutInfo...
,D/KeyguardModel( 1457): package = com.android.mms, class = com.android.mms.ui.ConversationList
D/KeyguardModel( 1457): createShortcutInfo...
W/ResourcesManager( 1457): Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
W/ResourcesManager( 1457): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 1457): Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
W/ResourcesManager( 1457): Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
W/ResourceType( 1457): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1457): Failure retrieving resources for com.android.mms: Resource ID #0x0
,D/KeyguardModel( 1457): package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
,D/KeyguardModel( 1457): createShortcutInfo...
W/ResourcesManager( 1457): Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
W/ResourcesManager( 1457): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourceType( 1457): No package identifier when getting value for resource number 0x00000000
I/[LGHome]Launcher.Model( 2068): [LauncherModel.java:2230:run()] LauncherModel bind current page shortcut
W/PackageManager( 1457): Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
I/[LGHome]Launcher( 2068): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
D/KeyguardModel( 1457): package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
D/KeyguardModel( 1457): createShortcutInfo...
I/[LGHome]EVENT( 2068): [Workspace.java:918:addInScreen()]Add Shortcut [Email] in screen 1 [1, 4]
I/[LGHome]EVENT( 2068): [Workspace.java:918:addInScreen()]Add Shortcut [Play Store] in screen 1 [2, 4]
I/[LGHome]EVENT( 2068): [Workspace.java:918:addInScreen()]Add Shortcut [Camera] in screen 1 [3, 4]
I/[LGHome]EVENT( 2068): [Workspace.java:918:addInScreen()]Add Shortcut [Settings] in screen 1 [4, 4]
,W/ResourcesManager( 1457): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 1457): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 1457): Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
W/ResourcesManager( 1457): Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
W/ResourceType( 1457): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1457): Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
D/KeyguardModel( 1457): package = com.lge.camera, class = com.lge.camera.CameraApp
D/KeyguardModel( 1457): createShortcutInfo...
,I/ActivityManager( 1030): Killing 4918:com.android.vending/u0a44 (adj 15): empty #17
E/VoldCmdListener(  278): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  278): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6839): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
E/VoldCmdListener(  278): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  278): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6839): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
I/[LGHome]Launcher.Model( 2068): [LauncherModel.java:2244:run()] LauncherModel bind current page shortcut
I/[LGHome]Launcher( 2068): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 2068): [LGUnreadLgeEmailsBadge.java:107:countUnreadItems()]setTotalCount : 0
,I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 2068): [LGUnreadLgeEmailsBadge.java:108:countUnreadItems()]countUnreadItems() ended..
E/VoldCmdListener(  278): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  278): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6839): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
W/ResourcesManager( 1030): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
I/[LGHome]EVENT( 2068): [Workspace.java:918:addInScreen()]Add Folder [Google] in screen 1 [0, 4]
I/[LGHome]Launcher.Model( 2068): [LauncherModel.java:2256:run()] LauncherModel bind current page widget
I/[LGHome]Launcher( 2068): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
W/ResourceType( 1030): Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
E/VoldCmdListener(  278): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  278): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6839): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
I/[Concierge]WidgetView( 2068): ConciergeWidgetView is instantiated. sIsWidgetAttached : true
,D/KeyguardModel( 1457): handleShortcutListChanged...
I/Timeline( 1030): Timeline: Activity_windows_visible id: ActivityRecord{14f5456a u0 com.lge.launcher2/.Launcher t3} time:283022
W/libprocessgroup( 1030): failed to open /acct/uid_10044/pid_4918/cgroup.procs: No such file or directory
D/[Concierge]Service( 2590): onStartCommand(). Type : 8
,D/[Concierge]Service( 2590): Update widget. Component : {com.lge.concierge/com.lge.concierge.ConciergeWidgetProvider}
D/[Concierge]Service( 2590): Update widget ID : 11
D/KeyguardModel( 1457): package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
D/KeyguardModel( 1457): createShortcutInfo...
D/[Concierge]WidgetView( 2068): change position of spinner
D/KeyguardModel( 1457): package = com.android.mms, class = com.android.mms.ui.ConversationList
D/KeyguardModel( 1457): createShortcutInfo...
W/ResourceType( 1457): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1457): Failure retrieving resources for com.android.mms: Resource ID #0x0
D/SyncManager( 1030): failed sync operation thalitester@gmail.com u0 (com.google), com.android.contacts, LOCAL, currentRunTime 26365, reason: 10019, SyncResult: stats [ numAuthExceptions: 1]
D/KeyguardModel( 1457): package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
D/KeyguardModel( 1457): createShortcutInfo...
W/ResourceType( 1457): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1457): Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
D/KeyguardModel( 1457): package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
D/KeyguardModel( 1457): createShortcutInfo...
D/SyncManager( 1030): not retrying sync operation because the error is a hard error: thalitester@gmail.com u0 (com.google), com.android.contacts, LOCAL, currentRunTime 315777, reason: 10019
W/ResourceType( 1457): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1457): Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
D/KeyguardModel( 1457): package = com.lge.camera, class = com.lge.camera.CameraApp
D/KeyguardModel( 1457): createShortcutInfo...
I/[Concierge]WidgetView( 2068): initWebView(). Time : 1452278511298
D/[Concierge]Service( 2590): onStartCommand(). Type : 0
D/KeyguardModel( 1457): handleShortcutListChanged...
,I/[Concierge]WebView( 2068): Return exist ConciergeWebView. Reuse : 747973885
,D/[Concierge]WidgetView( 2068): State Change : null -> AccInBeforeState
I/[LgeWidgetLib]LgeAppWidgetHostView( 2068): [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
I/[LgeWidgetLib]ExtViewHost( 2068): [LgeAppWidgetExtViewHost.java:136:setState()]New State = com.lge.lgewidgetlib.extview.NormalState@ee71e61
I/[LGHome]EVENT( 2068): [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.concierge.ConciergeWidgetProvider] in screen 1 [0, 0]
I/[LGHome]Launcher.Model( 2068): [LauncherModel.java:2256:run()] LauncherModel bind current page widget
I/[LGHome]Launcher( 2068): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/[LGHome]EVENT( 2068): [Workspace.java:918:addInScreen()]Add AppWidget [com.google.android.googlequicksearchbox.SearchWidgetProvider] in screen 1 [0, 2]
I/[LGHome]EVENT( 2068): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
D/[Concierge]WidgetView( 2068): isWidgetUpdateSkippable ? true
D/[Concierge]WidgetBroadcastReceiver( 2068): New receiver registered. Self-unregister old one. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
,W/[Concierge]WidgetView( 2068): Widget kill message received. Destory myself. My : 1452278256220, New one : 1452278511298
D/[Concierge]WidgetView( 2068): Unregister all receivers
W/[Concierge]WidgetBroadcastReceiver( 2068): Tried unregister broadcastReceiver which is not registered. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
,I/[LGHome]Launcher( 2068): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/[LGHome]EVENT( 2068): [Workspace.java:918:addInScreen()]Add Shortcut [Gallery] in screen 2 [0, 4]
I/[LGHome]EVENT( 2068): [Workspace.java:918:addInScreen()]Add Shortcut [Calendar] in screen 2 [1, 4]
I/[LGHome]EVENT( 2068): [Workspace.java:918:addInScreen()]Add Shortcut [QuickMemo+] in screen 2 [2, 4]
I/[LGHome]EVENT( 2068): [Workspace.java:918:addInScreen()]Add Shortcut [Quick Remote] in screen 2 [3, 4]
I/[LGHome]EVENT( 2068): [Workspace.java:918:addInScreen()]Add Shortcut [FM Radio] in screen 2 [4, 4]
I/[LGHome]Launcher( 2068): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/[LGHome]Launcher( 2068): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,D/DelayedSyncController( 6669): Delaying sync.
,I/[LgeWidgetLib]LgeAppWidgetHostView( 2068): [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
,E/[LgeWidgetLib]LgeAppWidgetHostView( 2068): [LgeAppWidgetHostView.java:124:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
I/[LGHome]EVENT( 2068): [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1] in screen 2 [0, 0]
I/[LGHome]Launcher( 2068): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/Timeline( 2068): Timeline: Activity_idle id: android.os.BinderProxy@3a6497d6 time:283165
,I/WebViewFactory( 6839): Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
I/LibraryLoader( 6839): Loading: webviewchromium
I/LibraryLoader( 6839): Time to load native libraries: 3 ms (timestamps 3177-3180)
,I/LibraryLoader( 6839): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 6839): Binding Chromium to main looper Looper (main, tid 1) {38ff80ee}
I/LibraryLoader( 6839): Expected native library version number "",actual native library version number ""
I/chromium( 6839): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 6839): Initializing chromium process, renderers=0
,W/art     ( 6839): Attempt to remove local handle scope entry from IRT, ignoring
V/AudioPolicyService(  311): registerClient() client 0xb558a460, uid 10093
W/chromium( 6839): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
I/chromium( 6839): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=38 off=46780 len=2953
I/chromium( 6839): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:39 off:229536 len:643667
W/AudioManagerAndroid( 6839): Requires BLUETOOTH permission
I/Adreno-EGL( 6839): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 6839): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 6839): Build Date: 12/12/14 금
I/Adreno-EGL( 6839): Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
I/Adreno-EGL( 6839): Remote Branch: 
I/Adreno-EGL( 6839): Local Patches: 
I/Adreno-EGL( 6839): Reconstruct Branch: 
,I/NSApplication( 6839): Starting up...
,I/chromium( 2068): [INFO:CONSOLE(0)] "'window.webkitStorageInfo' is deprecated. Please use 'navigator.webkitTemporaryStorage' or 'navigator.webkitPersistentStorage' instead.", source:  (0)
,I/ActivityManager( 1030): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=6920 uid=10097 gids={50097, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
I/ActivityManager( 1030): Killing 5992:com.lge.bnr/1000 (adj 15): empty #17
I/GBoardtInterface( 2068): onReloaded()
,I/GBoardWebViewClient( 2068): onPageFinished url:file:///android_asset/www/main.html
W/libprocessgroup( 1030): failed to open /acct/uid_1000/pid_5992/cgroup.procs: No such file or directory
,V/BoardContentProvider( 2679): query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
V/BoardContentProvider( 2679): query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
D/ActionManagerService( 1905): notifyUserLog: 1000001
,D/LIA_Informant_ActionManagerMessageHandler( 2679): handleMessage: what(1000) actionID(0x1000001)
D/LIA_Informant_Tips_SmartTipsActionManager( 2679): onEvent() : ACTION_BOARD_ENABLED
D/ActionManagerService( 1905): notifyUserLog: 1000001
D/LIA_Informant_ActionManagerMessageHandler( 2679): handleMessage: what(1000) actionID(0x1000001)
D/LIA_Informant_Tips_SmartTipsActionManager( 2679): onEvent() : ACTION_BOARD_ENABLED
D/LIA_Informant_Tips_FormEventRepository( 2679): getSize() : size - 0
D/LIA_Informant_Tips_SmartTipsActionManager( 2679): onSettingEvent() : GBoard On - add scheduler - 0
V/BoardContentProvider( 2679): query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
D/GBoardUriUtils( 2068): fileExists: file:///system/etc/mrg_default_forms/MyWellness/initial/initial2.html?id=mw_initial return true
D/GBoardWebViewUtils( 2068): changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyWellness/initial/initial2.html?id=mw_initial
D/GBoardUriUtils( 2068): fileExists: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial2.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc] return true
D/GBoardWebViewUtils( 2068): changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial2.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
D/GBoardUriUtils( 2068): fileExists: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/1/userguide2.html?id=guide_1111111111116_1452175674810&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay return true
D/GBoardWebViewUtils( 2068): changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/1/userguide2.html?id=guide_1111111111116_1452175674810&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
W/ResourcesManager( 6920): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.

```
