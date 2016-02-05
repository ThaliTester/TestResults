#### Test 58497659c9ea290_thali03_LGE-LG-D855 Logs


```
--------- beginning of system
V/AlarmManager( 1032): RTC_WAKEUP set : Alarm{1e3daad3 type 0 when 1454714890159 com.android.vending} when 1454714890159
,W/ContextImpl( 4160): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 com.lge.mlt.MptOnLogDumper.run:279 <bottom of call stack> <bottom of call stack> 
--------- beginning of main
V/SIM_STK ( 1032): Menu title from STK is T-Mobile
V/GLSActivity( 2166): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/AndroidRuntime( 6008): 
D/AndroidRuntime( 6008): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 6008): CheckJNI is OFF
I/GLSUser ( 2166): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 2166): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2166): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2166): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2166): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/Finsky  ( 4826): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 4826): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 4826): [1] 5.onFinished: Scheduling replication attempt 1.
D/AndroidRuntime( 6008): Calling main entry com.android.commands.am.Am
I/ActivityManager( 1032): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
V/SplitWindowPolicy( 1942): checkScreen => return. sourceIntent is null or not support SplitWindow component: ComponentInfo{co..../co.....MainActivity}
D/SplitInfo( 1032): new ActivitySplitInfo : ActivitySplitInfo [screenZone=0/ flag=0/ state=NATIVE]
D/ActivityManager( 1032): setTaskToReturnTo : TaskRecord{1edd7b7d #4 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
D/ActivityManager( 1032): setTaskToReturnTo : TaskRecord{1edd7b7d #4 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
D/WindowStateEx( 1032): AppWindowTokenEx init.. 
E/GBMv2   (  332): DFP En is all cleared set to be enabled
I/ActivityManager( 1032): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6048 uid=10311 gids={50311, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
D/AndroidRuntime( 6008): Shutting down VM
V/ActivityManager( 1032): Display changed displayId=0
D/DSDPConnection( 1852): Display #0 changed.
D/SplitWindowPolicy( 1942): updateActivityStateChanged: resumed=true, screenId=1, isScreenFull=true
D/SplitWindowPolicy( 1942): topRunningActivity=ActivityInfo{322d237e co.....MainActivity}, taskId=4, activityType=0, bIsSplit=false
D/SplitWindowPolicy( 1942): updateActivityStateChanged: resumed=false, screenId=1, isScreenFull=true
D/SplitWindowPolicy( 1942): topRunningActivity=ActivityInfo{f7cb0df co.....MainActivity}, taskId=4, activityType=0, bIsSplit=false
D/ContextHelper( 6048): convertTheme. context->name=com.test.thalitest themeResourceId=16973833
I/WebViewFactory( 6048): Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
I/LibraryLoader( 6048): Loading: webviewchromium
I/LibraryLoader( 6048): Time to load native libraries: 4 ms (timestamps 9341-9345)
,I/LibraryLoader( 6048): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 6048): Binding Chromium to main looper Looper (main, tid 1) {9fc7a6b}
,I/LibraryLoader( 6048): Expected native library version number "",actual native library version number ""
I/chromium( 6048): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 6048): Initializing chromium process, renderers=0
,W/art     ( 6048): Attempt to remove local handle scope entry from IRT, ignoring
W/chromium( 6048): [WARNING:dns_config_service_posix.cc(293)] Failed to read DnsConfig.
W/chromium( 6048): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
,I/chromium( 6048): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=32 off=46780 len=2953
I/chromium( 6048): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:33 off:229536 len:643667
V/AudioPolicyService(  315): registerClient() client 0xb119dfa0, uid 10311
D/BluetoothManagerService( 1032): Message: 20
,D/BluetoothManagerService( 1032): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@32efb41f:true
I/Adreno-EGL( 6048): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 6048): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 6048): Build Date: 12/12/14 금
I/Adreno-EGL( 6048): Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
I/Adreno-EGL( 6048): Remote Branch: 
I/Adreno-EGL( 6048): Local Patches: 
I/Adreno-EGL( 6048): Reconstruct Branch: 
D/BluetoothAdapter( 6048): 126806472: getState() :  mService = null. Returning STATE_OFF
,W/chromium( 6048): [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
,W/chromium( 6048): [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
W/art     ( 6048): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 6048): onDetachedFromWindow called when already detached. Ignoring
D/SystemWebViewEngine( 6048): CordovaWebView is running on device made by: LGE
,W/art     ( 6048): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 6048): Attempt to remove local handle scope entry from IRT, ignoring
,D/OpenGLRenderer( 6048): Render dirty regions requested: true
I/OpenGLRenderer( 6048): Initialized EGL, version 1.4
,D/OpenGLRenderer( 6048): Enabling debug mode 0
D/Atlas   ( 6048): Validating map...
,D/SplitWindow( 1032): check instance of lgWin Window{1ee50f21 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,D/LgDataFeature( 6048): LgDataFeature() Constructor: none
D/LgDataFeature( 6048): LgDataFeature() Constructor Done, null
I/SystemUI[Framework]( 1032): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x0, pkg=com.android.systemui
,D/PhoneStatusBar( 1452): setSystemUiVisibility vis=0 mask=ffffffff oldVal=8000 newVal=0 diff=8000
W/PhoneWindowManagerEx( 1032): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx( 1032): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx( 1032): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework]( 1032): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@cba0975,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework]( 1032): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
I/[SystemUI]NavigationThemeResource( 1452): NavigationKey Color is changed(WHITE_WITH_SHADOW -> BLACK)
I/[SystemUI]NavigationThemeResource( 1452):  BarMode=0, Theme=WHITE, LightBackground=false (Transparent)
I/[SystemUI]NavigationThemeResource( 1452): , Keyguard show=false, IME shown=false, Panel expanded=false
I/Timeline( 6048): Timeline: Activity_idle id: android.os.BinderProxy@9b454f8 time:109755
,I/ActivityManager( 1032): Displayed com.test.thalitest/.MainActivity: +593ms (total +693ms)
I/Timeline( 1032): Timeline: Activity_windows_visible id: ActivityRecord{1f9bda72 u0 com.test.thalitest/.MainActivity t4} time:109782
I/chromium( 6048): [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
I/chromium( 6048): 
,D/JsMessageQueue( 6048): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log( 6048): JniHelper::setJavaVM(0xb487c280), pthread_self() = -1435011328
,I/chromium( 6048): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/chromium( 6048): [INFO:SkFontConfigInterface_android.cpp(247)] ---- failed to open </system/fonts/CutiveMono.ttf> as a font
I/chromium( 6048): 
,E/GBMv2   (  332): DFP En is all cleared set to be enabled
E/GBMv2   (  332): Set value is all cleared set the max
I/GBMv2   (  332): DFP Enabled. Ignore VFP set
,W/jxcore-log( 6048): Initializing JXcore engine
,W/jxcore-log( 6048): JXcore engine is ready
W/Thread-683( 6102): type=1400 audit(0.0:146): avc: denied { ioctl } for path="socket:[10404]" dev="sockfs" ino=10404 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
W/Thread-683( 6102): type=1400 audit(0.0:147): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3222 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
W/Thread-683( 6102): type=1400 audit(0.0:148): avc: denied { ioctl } for path="socket:[7460]" dev="sockfs" ino=7460 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
,W/Thread-683( 6102): type=1400 audit(0.0:149): avc: denied { ioctl } for path="/cust" dev="mmcblk0p42" ino=2 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=dir
W/Thread-683( 6102): type=1400 audit(0.0:150): avc: denied { ioctl } for path="socket:[28580]" dev="sockfs" ino=28580 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
W/jxcore-log( 6048): Starting JXcore engine
,W/jxcore-log( 6048): Platform android
W/jxcore-log( 6048): 
W/jxcore-log( 6048): Process ARCH arm
W/jxcore-log( 6048): 
,I/jxcore-log( 6048): JXcore Cordova bridge is ready!
I/jxcore-log( 6048): 
,W/jxcore-log( 6048): JXcore engine is started
,I/jxcore-log( 6048): Toggling radios to true
I/jxcore-log( 6048): 
,D/BluetoothManagerService( 1032): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1032): enable():  mBluetooth =null mBinding = false
,D/LocationManagerService( 1032): getAllProviders()=[passive, gps, network]
D/Ulp_jni ( 1032): JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
D/Ulp_jni ( 1032): JNI:system_update. Event-4
D/BluetoothManagerService( 1032): Message: 1
D/BluetoothManagerService( 1032): MESSAGE_ENABLE: mBluetooth = null
D/WifiService( 1032): New client listening to asynchronous messages
I/ActivityManager( 1032): Start proc com.android.bluetooth for service com.android.bluetooth/.btservice.AdapterService: pid=6105 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008, 4002, 1023} abi=armeabi-v7a
D/WifiServiceImplEx( 1032): setWifiEnabled: true pid=6048, uid=10311, package= com.test.thalitest, App Lable : ThaliTest
D/WifiService( 1032): setWifiEnabled: true pid=6048, uid=10311
E/WifiService( 1032): Invoking mWifiStateMachine.setWifiEnabled
,D/LocationManagerService( 1032): getAllProviders()=[passive, gps, network]
D/Ulp_jni ( 1032): JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 1,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
D/Ulp_jni ( 1032): JNI:system_update. Event-4
E/WifiStateMachine( 1032):  InitialState CMD_START_SUPPLICANT 0 0
I/LGFTMITEM( 1032): [GET_FTM][id=6], offset=12288
D/WifiServiceImplEx( 1032): disconnect pid=6048, uid=10311, packageName=com.test.thalitest
D/WifiServiceImplEx( 1032): reconnect pid=6048, uid=10311, packageName=com.test.thalitest
I/jxcore-log( 6048): Radios toggled
I/jxcore-log( 6048): 
I/jxcore-log( 6048): My device name is: LGE-LG-D855
I/jxcore-log( 6048): 
E/WifiUtil( 1032): wfc_util_ffile_check_copy(): pid[1032] pDestFName[/data/misc/wifi/WCNSS_qcom_cfg.ini] pSourceFName[/system/etc/wifi/WCNSS_qcom_cfg.ini]
E/WifiUtil( 1032): wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
E/WifiUtil( 1032): wfc_util_ffile_check_copy(): pid[1032] pDestFName[/data/misc/wifi/WCNSS_qcom_wlan_nv.bin] pSourceFName[/system/etc/wifi/WCNSS_qcom_wlan_nv.bin]
E/WifiUtil( 1032): wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
I/WifiUtil( 1032): Intf0MacAddress=C49A027B60AC
E/WifiHW  ( 1032): unknown target_country: EU , set to default
E/WifiHW  ( 1032): [wifi_ensure_config_files] default country1 = GB
E/WifiHW  ( 1032): [wifi_ensure_config_files] default country2 = GB
I/WifiUtil( 1032): gEnableBmps=1
,W/ResourcesManager( 6105): Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
W/ResourcesManager( 6105): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 6105): Asset path '/system/framework/com.qcom.bluetooth.jar' does not exist or contains no resources.
W/ResourcesManager( 6105): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,D/BluetoothAdapterApp( 6105): Loading JNI Library
,D/SoftapController(  311): Softap fwReload - Ok
,D/CommandListener(  311): Setting iface cfg
D/CommandListener(  311): Trying to bring down wlan0
D/CommandListener(  311): Clearing all IP addresses on wlan0
E/WifiHW  ( 1032): Cannot open "/system/etc/wifi/autojoinconfig.txt": No such file or directory
,E/WifiStateMachine( 1032): Couldn't get getWiFiOffloadingIface : 
E/WifiStateMachine( 1032): useWiFiOffloading() : false
E/WifiStateMachine( 1032): CONFIG_LGE_WLAN_PATH : true
V/WfdStateTracker( 1942): WfdStateTracker handleDirectStateChangedEvent: 1
D/StatusBar.NetworkController( 1452): refreshViews: Data not connected!! Set no data type icon / Roaming
W/wpa_supplicant( 6130): type=1400 audit(0.0:151): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
W/wpa_supplicant( 6130): type=1400 audit(0.0:152): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,D/WifiMonitor( 1032): startMonitoring(wlan0) with mConnected = false
D/WifiMonitor( 1032): connecting to supplicant
D/BluetoothAdapterApp( 6105): REFCOUNT: Constructed com.android.bluetooth.btservice.AdapterApp@f03a84f Instance Count = 1
I/ActivityManager( 1032): Start proc com.lge.formmanager for broadcast com.lge.formmanager/.FormServiceReceiver: pid=6131 uid=10026 gids={50026, 9997, 3003, 1028} abi=armeabi-v7a
,I/WifiServerServiceExt( 1032): WIFI_STATE_CHANGED_ACTION [2]
D/Tethering( 1032): sendTetherStateChangedBroadcast 1, 0, 0
D/BluetoothAdapterApp( 6105): onCreate
D/libc-netbsd(  311): default dns: query_ipv6=0, query_ipv4=0
,I/wpa_supplicant( 6130): Successfully initialized wpa_supplicant
D/DSQN    ( 1032): DNSproblemNotiEnabled is disabled ignore DNS fail CB
D/Tethering( 1032): InitialState.processMessage what=4
D/Tethering( 1032): sendTetherStateChangedBroadcast 0, 0, 0
,D/ProfileConfigQcom( 6105): [BTUI] HeadsetService is supported
D/ProfileConfigQcom( 6105): Adding HeadsetService
D/ProfileConfigQcom( 6105): [BTUI] A2dpService is supported
D/ProfileConfigQcom( 6105): Adding A2dpService
D/ProfileConfigQcom( 6105): [BTUI] HidService is supported
D/ProfileConfigQcom( 6105): Adding HidService
D/ProfileConfigQcom( 6105): [BTUI] HealthService is supported
D/ProfileConfigQcom( 6105): Adding HealthService
D/LGBluetoothFeatureConfig( 6105): isSupportPan() :  mTargetOp=OPEN
,D/ProfileConfigQcom( 6105): [BTUI] PanService is supported
D/ProfileConfigQcom( 6105): Adding PanService
D/ProfileConfigQcom( 6105): [BTUI] GattService is supported
D/ProfileConfigQcom( 6105): Adding GattService
D/ProfileConfigQcom( 6105): [BTUI] BluetoothMapService is supported
D/ProfileConfigQcom( 6105): Adding BluetoothMapService
D/ProfileConfigQcom( 6105): [BTUI] HeadsetClientService is NOT supported
I/wpa_supplicant( 6130): rfkill: Cannot open RFKILL control device
,I/wpa_supplicant( 6130): [LGE_PATCH] unset P2P_CAPABLE to ifname wlan0
D/BluetoothManagerService( 1032): Message: 20
D/BluetoothManagerService( 1032): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@3c97c4b8:true
D/BluetoothAdapterState( 6105): make
,I/LGFMServiceAdapter( 6105): [FM] LGFMServiceAdapter : create
I/BluetoothAdapterState( 6105): Entering OffState
I/bluedroid-qcom( 6105): init
I/bte_conf( 6105): bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,I/bte_conf( 6105): bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
E/bt_osi_config( 6105): config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
I/bte_conf( 6105): bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
D/BTIF_CORE( 6105): [BTUI] lge_load_bluetooth_address
I/bluedroid-qcom( 6105): get_profile_interface socket
I/bluedroid-qcom( 6105): get_profile_interface map_client
I/GKI_LINUX( 6105): gki_task_entry task_id=1 [BTIF] starting
W/bdaddr_loader( 6166): type=1400 audit(0.0:153): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
W/bdaddr_loader( 6166): type=1400 audit(0.0:154): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
D/BluetoothAdapterProperties( 6105): Address is:58:3F:54:73:64:C0
D/lge_bdaddr_loader( 6166): [BTUI] bdaddr_loader ::: START
D/lge_bdaddr_loader( 6166): [BTUI] bluetooth_load_bdaddress
I/LGFTMITEM( 6166): [GET_FTM][id=8], offset=16384
D/lge_bdaddr_loader( 6166): [BTUI] bdaddr to set in property : 58:3F:54:73:64:C0
E/lge_bdaddr_loader( 6166): [BTUI] bluetooth_load_bdaddress : OK => 58:3F:54:73:64:C0
,D/lge_bdaddr_loader( 6166): [BTUI] bdaddr_loader ::: END
I/ActivityManager( 1032): Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=6171 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,D/BluetoothManagerService( 1032): Bluetooth Adapter name changed to G3-1
D/BluetoothManagerService( 1032): Stored Bluetooth name: G3-1
D/BluetoothAdapterProperties( 6105): Name is: G3-1
D/BluetoothManagerService( 1032): BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
D/BluetoothManagerService( 1032): Message: 40
D/BluetoothManagerService( 1032): MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
I/bluedroid-qcom( 6105): config_hci_snoop_log
D/BluetoothManagerService( 1032): Calling onBluetoothServiceUp callbacks
D/BluetoothManagerService( 1032): Broadcasting onBluetoothServiceUp() to 7 receivers.
V/LGMDMManagerInternal( 6105): Create singleton instance
,V/FormManager( 6131): Network unavailable.
V/FormManager( 6131): Network unavailable.
W/FormManager( 6131): Network not available. Please check & try again.
,I/wpa_supplicant( 6130): rfkill: Cannot open RFKILL control device
I/ActivityManager( 1032): Killing 5770:com.google.android.partnersetup/u0a8 (adj 15): empty #17
D/BluetoothAdapterState( 6105): CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
D/BluetoothAdapterProperties( 6105): Setting state to 11
I/BluetoothAdapterState( 6105): Bluetooth adapter state changed: 10-> 11
,D/BluetoothManagerService( 1032): Message: 60
D/BluetoothManagerService( 1032): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
D/BluetoothManagerService( 1032): Bluetooth State Change Intent: 10 -> 11
I/LGBluetoothServiceJni( 6105): classInitNative: succeeds
D/PCSuite ( 6171): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
W/libprocessgroup( 1032): failed to open /acct/uid_10008/pid_5770/cgroup.procs: No such file or directory
,I/wpa_supplicant( 6130): [LGE_WLAN_PATCH]P2P 5GHz support level:2(0:no 1:gconly 2:gconly_UNII1 3:full)
D/BluetoothBondStateMachine( 6105): make
D/LGBluetoothAPIService( 1942): [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
I/[SystemUI]BluetoothHandler( 1452): Receive : BluetoothAdapter.ACTION_STATE_CHANGED
I/wpa_supplicant( 6130): p2p0: CTRL-EVENT-AVOID-FREQ ranges=
I/wpa_supplicant( 6130): wlan0: CTRL-EVENT-SCAN-STARTED 
D/BluetoothAdapterService( 6105): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@26ac4986
D/LGBluetoothServiceAdapter( 6105): [BTUI] check adapter is available - false.
,D/BluetoothAdapterService( 6105): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@26ac4986
D/LGBluetoothServiceAdapter( 6105): [BTUI] check adapter is available - true : set adapter available.
E/WifiStateMachine( 1032):  SupplicantStartingState CMD_SET_OPERATIONAL_MODE 1 0
D/LGBluetoothSettingsDBObserver( 6105): [BTUI] register observer for LG device name DB
E/WifiStateMachine( 1032):  SupplicantStartingState CMD_START_DRIVER 0 0
E/WifiStateMachine( 1032):  SupplicantStartingState CMD_SET_HIGH_PERF_MODE 0 0
E/WifiStateMachine( 1032):  DefaultState CMD_SET_HIGH_PERF_MODE 0 0
D/WifiMonitor( 1032): Event [IFNAME=p2p0 CTRL-EVENT-AVOID-FREQ ranges=]
D/WifiMonitor( 1032): Dropping event because (p2p0) is stopped
D/WifiMonitor( 1032): Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1032): WifiMonitor:wlan0 cnt=0 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiStateMachine( 1032):  SupplicantStartingState CMD_DISCONNECT 0 0
E/WifiMonitor( 1032): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1032): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
E/WifiStateMachine( 1032):  DefaultState CMD_DISCONNECT 0 0
E/WifiStateMachine( 1032):  SupplicantStartingState CMD_RECONNECT 0 0
E/WifiStateMachine( 1032):  DefaultState CMD_RECONNECT 0 0
I/BluetoothBondStateMachine( 6105): StableState(): Entering Off State
E/WifiStateMachine( 1032):  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1032):  DefaultState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1032):  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1032):  DefaultState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1032):  SupplicantStartingState SUP_CONNECTION_EVENT 0 0
D/WifiNative-wlan0( 1032): doString: [DRIVER MACADDR]
D/WifiNative-wlan0( 1032):    returned Macaddr = c4:9a:02:7b:60:ac
D/WifiStateMachine( 1032): MAC Addr from driver = c4:9a:02:7b:60:ac
D/WifiOffDelayIfNotUsed( 1032): setPowerSaveActivated(false)
I/CloudHub( 2141): [CLIENT][CloudHubClientFactory$1|onTick] Until finished: 19979
,E/BluetoothAdapterService( 6105): File transfer profiles supported!!
I/ActivityManager( 1032): Start proc com.android.settings for broadcast com.android.settings/.bluetooth.DockEventReceiver: pid=6193 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
I/ActivityManager( 1032): Killing 5412:com.lge.appbox.client/u0a11 (adj 15): empty #17
,E/WifiStateMachine( 1032): Couldn't get getWiFiOffloadingIface : 
E/WifiStateMachine( 1032): useWiFiOffloading() : false
E/WifiStateMachine( 1032): CONFIG_LGE_WLAN_PATH : true
W/Settings( 1032): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings( 1032): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
E/BluetoothAdapterService( 6105): File transfer profiles supported!!
D/WifiNative-wlan0( 1032): doBoolean: SET update_config 1
W/libprocessgroup( 1032): failed to open /acct/uid_10011/pid_5412/cgroup.procs: No such file or directory
D/WifiNative-wlan0( 1032): SET update_config 1: returned true
D/WifiConfigStore( 1032): Loading config and enabling all networks 
D/WifiNative-wlan0( 1032): doString: [LIST_NETWORKS]
D/WifiNative-wlan0( 1032):    returned network id / ssid / bssid / flags 0	NG700	any	
D/BluetoothHeadset( 1032): Proxy object connected
D/HeadsetService( 6105): Received start request. Starting profile...
,I/LGBluetoothHeadsetServiceJni( 6105): classInitNative: succeeds
D/LGBluetoothHfpAdapter( 6105): Version 1.6
D/BluetoothHeadset( 1852): Proxy object connected
D/BluetoothHeadset( 1852): Proxy object connected
D/BluetoothHeadset( 1852): Proxy object connected
D/LGBluetoothFeatureConfig( 6105): isPrivacyLogsEnabled : true
I/BluetoothHeadsetServiceJni( 6105): classInitNative: succeeds
D/HeadsetStateMachine( 6105): make
E/BluetoothAdapterService( 6105): File transfer profiles supported!!
E/BluetoothAdapterService( 6105): File transfer profiles supported!!
E/BluetoothAdapterService( 6105): File transfer profiles supported!!
E/BluetoothAdapterService( 6105): File transfer profiles supported!!
W/ResourcesManager( 6193): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6193): Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
W/ResourcesManager( 6193): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 6193): Asset path '/system/framework/com.lge.bluetooth.jar' does not exist or contains no resources.
E/BluetoothAdapterService( 6105): File transfer profiles supported!!
W/ResourcesManager( 6193): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
W/ResourcesManager( 6193): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,E/WifiConfigStore( 1032): readNetworkVariablesFromSupplicantFile key=psk
D/LgDataFeature( 6105): LgDataFeature() Constructor: none
D/LgDataFeature( 6105): LgDataFeature() Constructor Done, null
E/WifiConfigStore( 1032): readNetworkVariableFromSupplicantFile ssid=["NG700"] key=psk
,E/WifiConfigStore( 1032): Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
D/WifiStateMachine( 1032): enableVerboseLogging : level 2
,D/WifiNative-wlan0( 1032): doBoolean: SET device_name g3_global_com
V/LGMDMManager( 6105): Create singleton instance
I/BluetoothAdapterState( 6105): Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
D/WifiNative-wlan0( 1032): SET device_name g3_global_com: returned true
D/WifiNative-wlan0( 1032): doBoolean: SET manufacturer LGE
D/WifiNative-wlan0( 1032): SET manufacturer LGE: returned true
D/WifiNative-wlan0( 1032): doBoolean: SET model_name LG-D855
D/WifiNative-wlan0( 1032): SET model_name LG-D855: returned true
D/WifiNative-wlan0( 1032): doBoolean: SET model_number LG-D855
D/WifiNative-wlan0( 1032): SET model_number LG-D855: returned true
D/WifiNative-wlan0( 1032): doBoolean: SET serial_number LGD8553bed2d08
D/WifiNative-wlan0( 1032): SET serial_number LGD8553bed2d08: returned true
D/WifiNative-wlan0( 1032): doBoolean: SET config_methods physical_display virtual_push_button
D/WifiNative-wlan0( 1032): SET config_methods physical_display virtual_push_button: returned true
D/WifiNative-wlan0( 1032): doBoolean: SET device_type 10-0050F204-5
D/WifiNative-wlan0( 1032): SET device_type 10-0050F204-5: returned true
D/WifiStateMachine( 1032): Setting OUI to DA-A1-19
D/WifiNative-wlan0( 1032): doBoolean: SCAN_INTERVAL 120
D/WifiNative-wlan0( 1032): SCAN_INTERVAL 120: returned true
D/WifiNative-HAL( 1032): Setting external_sim to 1
D/WifiNative-wlan0( 1032): doBoolean: SET external_sim 1
D/WifiNative-wlan0( 1032): SET external_sim 1: returned true
I/WifiNative-HAL( 1032): startHal
E/wifi    ( 1032): getStaticLongField sWifiHalHandle 0x989628dc
E/WifiHAL ( 1032): Could not connect handle
D/wifi    ( 1032): halHandle = 0x0, mVM = 0xb487c280, mCls = 0x102292
I/WifiNative-HAL( 1032): Could not start hal
D/WifiStateMachine( 1032): Setting OUI to DA-A1-19
I/WifiNative-HAL( 1032): startHal
E/wifi    ( 1032): getStaticLongField sWifiHalHandle 0x9896285c
E/WifiHAL ( 1032): Could not connect handle
D/wifi    ( 1032): halHandle = 0x0, mVM = 0xb487c280, mCls = 0x102296
I/WifiNative-HAL( 1032): Could not start hal
D/WifiNative-wlan0( 1032): doBoolean: STA_AUTOCONNECT 1
D/WifiNative-wlan0( 1032): STA_AUTOCONNECT 1: returned true
D/WifiNative-wlan0( 1032): doBoolean: DRIVER BTCOEXSCAN-STOP
I/wpa_supplicant( 6130): wpa_driver_nl80211_ext_driver_cmd BTCOEXSCAN-STOP
D/WifiNative-wlan0( 1032): DRIVER BTCOEXSCAN-STOP: returned true
D/WifiNative-wlan0( 1032): doBoolean: DRIVER RXFILTER-STOP
I/wpa_supplicant( 6130): wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
D/WifiNative-wlan0( 1032): DRIVER RXFILTER-STOP: returned true
D/WifiNative-wlan0( 1032): doBoolean: DRIVER RXFILTER-REMOVE 3
I/wpa_supplicant( 6130): wpa_driver_nl80211_ext_driver_cmd RXFILTER-REMOVE 3
D/WifiNative-wlan0( 1032): DRIVER RXFILTER-REMOVE 3: returned true
D/WifiNative-wlan0( 1032): doBoolean: DRIVER RXFILTER-START
I/wpa_supplicant( 6130): wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
D/WifiNative-wlan0( 1032): DRIVER RXFILTER-START: returned true
D/WifiNative-wlan0( 1032): doBoolean: DRIVER RXFILTER-STOP
I/wpa_supplicant( 6130): wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
D/WifiNative-wlan0( 1032): DRIVER RXFILTER-STOP: returned true
D/WifiNative-wlan0( 1032): doBoolean: DRIVER RXFILTER-REMOVE 2
I/wpa_supplicant( 6130): android_multicast_filter_startstop : multicast filter set
D/WifiNative-wlan0( 1032): DRIVER RXFILTER-REMOVE 2: returned true
D/WifiNative-wlan0( 1032): doBoolean: DRIVER RXFILTER-START
I/wpa_supplicant( 6130): wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
D/WifiNative-wlan0( 1032): DRIVER RXFILTER-START: returned true
E/WifiNative: ( 1032): [113,518,928 us] RECONNECT  stack:logDbg - reconnect - enter - invokeEnterMethods - performTransitions
D/WifiNative-wlan0( 1032): doBoolean: RECONNECT
D/WifiNative-wlan0( 1032): RECONNECT: returned true
D/WifiNative-wlan0( 1032): doString: [STATUS]
D/WifiMonitor( 1032): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
E/WifiMonitor( 1032): WifiMonitor:wlan0 cnt=1 dispatchEvent: CTRL-EVENT-ST,ATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
D/WifiNative-wlan0( 1032):    returned wpa_state=SCANNING p2p_device_address=02:9a:02:7b:60:ac address=c4:9a:02:7b:60:ac uuid=530d3fd0-1ba3-5409-a336-ff4e42af59a2
D/WifiNative-wlan0( 1032): doBoolean: DRIVER SETSUSPENDMODE 1
I/wpa_supplicant( 6130): wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 1
D/WifiNative-wlan0( 1032): DRIVER SETSUSPENDMODE 1: returned true
D/WifiNative-wlan0( 1032): doBoolean: SET ps 1
D/WifiNative-wlan0( 1032): SET ps 1: returned true
D/LGWifiP2pService( 1032): P2pDisabledState{ when=0 what=131203 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiStateMachine( 1032):  DisconnectedState CMD_SET_OPERATIONAL_MODE 1 0
E/WifiStateMachine( 1032):  DisconnectedState CMD_START_DRIVER 0 0
E/WifiStateMachine( 1032):  ConnectModeState CMD_START_DRIVER 0 0
D/CommandListener(  311): Setting iface cfg
D/CommandListener(  311): Trying to bring up p2p0
D/WifiMonitor( 1032): startMonitoring(p2p0) with mConnected = true
E/WifiStateMachine( 1032):  DriverStartedState CMD_START_DRIVER 0 0
D/LGWifiP2pService( 1032): P2pEnablingState
D/LGWifiP2pService( 1032): P2pEnablingState{ when=0 what=147457 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1032): P2p socket connection successful
D/LGWifiP2pService( 1032): P2pEnabledState
D/WfdService( 1942): Waiting for WifiP2p enabling
E/WifiStateMachine( 1032):  DisconnectedState CMD_SET_COUNTRY_CODE 1 0 cz
E/WifiStateMachine( 1032):  ConnectModeState CMD_SET_COUNTRY_CODE 1 0 cz
D/StatusBar.NetworkController( 1452): refreshViews: Data not connected!! Set no data type icon / Roaming
E/WifiStateMachine( 1032):  DriverStartedState CMD_SET_COUNTRY_CODE 1 0 cz
D/WifiNative-wlan0( 1032): doBoolean: DRIVER COUNTRY CZ
I/wpa_supplicant( 6130): wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
,I/wpa_supplicant( 6130): wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
I/wpa_supplicant( 6130): [LGE_PATCH] driver_cmd() country:CZ
I/wpa_supplicant( 6130): p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
I/wpa_supplicant( 6130): p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
D/WifiMonitor( 1032): Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
E/WifiMonitor( 1032): WifiMonitor:wlan0 cnt=2 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
E/WifiMonitor( 1032): handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
E/WifiMonitor( 1032): handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
D/WifiMonitor( 1032): Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
E/WifiMonitor( 1032): WifiMonitor:p2p0 cnt=3 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
E/WifiMonitor( 1032): handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
E/WifiMonitor( 1032): handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
D/WifiMonitor( 1032): Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
E/WifiMonitor( 1032): WifiMonitor:p2p0 cnt=4 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
E/WifiMonitor( 1032): handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
,E/WifiMonitor( 1032): handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
D/WifiNative-wlan0( 1032): DRIVER COUNTRY CZ: returned true
E/WifiStateMachine( 1032):  DisconnectedState CMD_SET_FREQUENCY_BAND 0 0
E/WifiStateMachine( 1032):  ConnectModeState CMD_SET_FREQUENCY_BAND 0 0
E/WifiStateMachine( 1032):  DriverStartedState CMD_SET_FREQUENCY_BAND 0 0
D/WifiNative-wlan0( 1032): doBoolean: DRIVER SETBAND 0
I/wpa_supplicant( 6130): wpa_driver_nl80211_ext_driver_cmd SETBAND 0 - interface name wlan0
I/wpa_supplicant( 6130): wlan0: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
D/WifiMonitor( 1032): Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN]
E/WifiMonitor( 1032): WifiMonitor:wlan0 cnt=5 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
E/WifiMonitor( 1032): handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
E/WifiMonitor( 1032): handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
D/WifiNative-wlan0( 1032): DRIVER SETBAND 0: returned true
D/WifiNative-wlan0( 1032): doBoolean: BSS_FLUSH 0
D/WifiNative-wlan0( 1032): BSS_FLUSH 0: returned true
D/WifiNative-wlan0( 1032): doBoolean: SCAN
D/WifiNative-wlan0( 1032): SCAN: returned false
E/WifiStateMachine( 1032):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 1 0 rt=113529  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
D/WfdsService( 1942): Supplicant Connection state is changed : true
D/WfdsService( 1942): DefaultState - WIFI_SUPPLICANT_CONNECTED
D/WfdsService( 1942): Set the WFDS Monitor: true
I/WifiServerServiceExt( 1032): WIFI_STATE_CHANGED_ACTION [3]
D/LGWifiP2pService( 1032): sending p2p connection changed broadcast
I/WifiServerServiceExt( 1032): batteryPsActivateMsgHandler : state:0 event:3
D/WfdsMonitor( 1942): WfdsMonitorThread create
D/WifiNative-p2p0( 1032): doBoolean: SET persistent_reconnect 1
D/WfdsMonitor( 1942): WFDS Monitor is created and started
D/WfdsService( 1942): WiFi: Supplicant connection re-established
V/WfdStateTracker( 1942): WfdStateTracker handleDirectStateChangedEvent: 2
I/StatusBar.NetworkController( 1452): networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/WfdsService( 1942): WifiP2pState is changed : true
I/StatusBar.NetworkController( 1452): mWifiConnected = false, mWifiLevel = 0
D/WfdsService( 1942): Receive the WFDS_ENABLE Method
D/WfdsService( 1942): Set the WFDS Monitor: true
D/WfdsService( 1942): Connected to the supplicant for wfds
D/WfdsJNI ( 1942): doCommand: WFDS_SET TRUE
E/CtrlSupplicant( 1942): Not connected to wap_supplicant - "WFDS_SET TRUE" command dropped.
D/WfdsJNI ( 1942): wfds_send_command: [WFDS_SET TRUE] failed
D/WfdsJNI ( 1942): doCommand: WFDS_GET_MAC_ADDRESS
E/CtrlSupplicant( 1942): Not connected to wap_supplicant - "WFDS_GET_MAC_ADDRESS" command dropped.
D/WfdsJNI ( 1942): wfds_send_command: [WFDS_GET_MAC_ADDRESS] failed
D/WfdsJNI ( 1942): doCommand: IFNAME=wlan0 GET_CAPABILITY channels
E/CtrlSupplicant( 1942): Not connected to wap_supplicant - "IFNAME=wlan0 GET_CAPABILITY channels" command dropped.
D/WfdsJNI ( 1942): wfds_send_command: [IFNAME=wlan0 GET_CAPABILITY channels] failed
D/WfdsService( 1942): selectPreferredScanChannel [0]
D/WfdsService( 1942): STATE : WfdsEnabledState - enter: this device mac null
D/WifiHS20( 1032): hidePasspointNotification off =false
D/WifiNative-p2p0( 1032): SET persistent_reconnect 1: returned true
D/WifiNative-p2p0( 1032): doBoolean: SET device_name G3-1
,D/StatusBar.NetworkController( 1452): refreshViews: Data not connected!! Set no data type icon / Roaming
D/WifiNative-p2p0( 1032): SET device_name G3-1: returned true
D/LGWifiP2pService( 1032): [LGE_P2P] initializeP2pSettings() check postfix
D/LGWifiP2pService( 1032): before postfix = G3-1
D/WifiServerServiceExt( 1032): postfix byte check : 4
D/LGWifiP2pService( 1032): after postfix = G3-1
D/WifiNative-p2p0( 1032): doBoolean: SET p2p_ssid_postfix -G3-1
E/WifiStateMachine( 1032):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 1 0 rt=113542  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
D/WfdsService( 1942): WIFI_P2P_CONNECTION_CHANGED_ACTION
E/WifiStateMachine( 1032):  DisconnectedState what:132106 1 0
D/WfdsService( 1942): isConnected: false
E/WifiStateMachine( 1032):  ConnectModeState what:132106 1 0
E/WifiStateMachine( 1032):  DriverStartedState what:132106 1 0
I/WifiServerServiceExt( 1032): setWifiDualbandAPConnection band : 1
W/Settings( 1032): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
E/wpa_supplicant( 6130): nWIFIDualbandAPConnection: 1
W/Settings( 1032): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
E/WifiStateMachine( 1032):  DisconnectedState what:132096 -100 0
E/CtrlSupplicant( 1942): Access OK "@android:wpa_wlan0"
D/WifiOffDelayIfNotUsed( 1032): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
D/WifiScanningService( 1032): SCAN_AVAILABLE : 3
E/WifiStateMachine( 1032):  ConnectModeState what:132096 -100 0
D/WifiScanningService( 1032): DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
I/WifiNative-HAL( 1032): startHal
E/WifiStateMachine( 1032):  DriverStartedState what:132096 -100 0
I/WifiServerServiceExt( 1032): set CMD_DISCONNECT_RSSI_LVL : -100
D/RttService( 1032): SCAN_AVAILABLE : 3
E/wpa_supplicant( 6130): disconnect_rssi_lvl: -100
E/CtrlSupplicant( 1942): Succeed to open control connection
E/CtrlSupplicant( 1942): Succeed to open monitor connection
D/WfdsMonitor( 1942): Supplicant connection established
E/WifiStateMachine( 1032):  DisconnectedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
D/WfdsService( 1942): Received the Event that WfdsMonitor is connected to supplicant
D/RttService( 1032): DefaultState got{ when=-1ms what=160512 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiStateMachine( 1032):  ConnectModeState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
E/WifiStateMachine( 1032):  DriverStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
E/WifiStateMachine( 1032):  SupplicantStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
D/WifiNative-p2p0( 1032): SET p2p_ssid_postfix -G3-1: returned true
E/wifi    ( 1032): getStaticLongField sWifiHalHandle 0x94e6c99c
E/WifiHAL ( 1032): Could not connect handle
D/wifi    ( 1032): halHandle = 0x0, mVM = 0xb487c280, mCls = 0x10229a
I/WifiNative-HAL( 1032): Could not start hal
E/WifiScanningService( 1032): could not start HAL
D/WifiNative-p2p0( 1032): doBoolean: SET device_type 10-0050F204-5
E/WifiStateMachine( 1032):  DefaultState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
D/WifiNative-p2p0( 1032): SET device_type 10-0050F204-5: returned true
D/WifiNative-p2p0( 1032): doBoolean: SET config_methods virtual_push_button physical_display keypad
D/WifiNative-p2p0( 1032): SET config_methods virtual_push_button physical_display keypad: returned true
D/WifiNative-p2p0( 1032): doBoolean: P2P_SET conc_pref p2p
D/WifiNative-p2p0( 1032): P2P_SET conc_pref p2p: returned true
D/WifiNative-HAL( 1032): p2pGetDeviceAddress
I/StatusBar.NetworkController( 1452): networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1452): mWifiConnected = false, mWifiL,evel = 0
D/WifiNative-HAL( 1032): p2pGetDeviceAddress returning 02:9a:02:7b:60:ac
W/Settings( 1032): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/LGWifiP2pService( 1032): DeviceAddress: 02:9a:02:7b:60:ac
W/Settings( 1032): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1032): NETWORK_STATE_CHANGED_ACTION [SCANNING]
D/WifiNative-p2p0( 1032): doBoolean: P2P_FLUSH
D/WifiServerServiceExt( 1032): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1032): setSupplicantStateSCANNING
D/WifiNative-p2p0( 1032): P2P_FLUSH: returned true
D/WifiNative-p2p0( 1032): doBoolean: P2P_SERVICE_FLUSH
I/WfdStateTracker( 1942): handleP2pThisDeviceChanged
D/WfdsService( 1942): WIFI_P2P_THIS_DEVICE_CHANGED_ATCION
D/WfdsService( 1942): Update P2p Interface State: 3
D/StatusBar.NetworkController( 1452): refreshViews: Data not connected!! Set no data type icon / Roaming
D/WifiNative-p2p0( 1032): P2P_SERVICE_FLUSH: returned true
D/WifiNative-p2p0( 1032): doString: [LIST_NETWORKS]
D/WifiNative-p2p0( 1032):    returned network id / ssid / bssid / flags
D/WifiNative-p2p0( 1032): doBoolean: SAVE_CONFIG
D/WifiNative-p2p0( 1032): SAVE_CONFIG: returned true
D/LGWifiP2pService( 1032): sending p2p persistent groups changed broadcast
D/LGWifiP2pService( 1032): InactiveState
D/LGWifiP2pService( 1032): InactiveState{ when=-53ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1032): P2pEnabledState{ when=-54ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-p2p0( 1032): doBoolean: DRIVER COUNTRY CZ
,I/wpa_supplicant( 6130): wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
I/wpa_supplicant( 6130): p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
D/WfdsMonitor( 1942): Event [CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
D/WifiMonitor( 1032): Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
E/WifiMonitor( 1032): WifiMonitor:p2p0 cnt=6 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
E/WifiMonitor( 1032): handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
E/WifiMonitor( 1032): handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
I/wpa_supplicant( 6130): [LGE_PATCH] driver_cmd() country:CZ
I/wpa_supplicant( 6130): p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
D/WifiNative-p2p0( 1032): DRIVER COUNTRY CZ: returned true
D/LGWifiP2pService( 1032): InactiveState{ when=-29ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1032): P2pEnabledState{ when=-29ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1032): InactiveState{ when=0 what=139287 arg2=1 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1032): P2pEnabledState{ when=0 what=139287 arg2=1 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1032): DefaultState{ when=0 what=139287 arg2=1 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1032): InactiveState{ when=0 what=139283 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1032): P2pEnabledState{ when=0 what=139283 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1032): DefaultState{ when=-1ms what=139283 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiServerServiceExt( 1032): No p2p device connected
I/wpa_supplicant( 6130): p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
I/art     ( 1032): Explicit concurrent mark sweep GC freed 36210(1794KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 43MB/65MB, paused 1.498ms total 92.999ms
D/WfdsMonitor( 1942): Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
D/WfdsMonitor( 1942): Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
D/WifiMonitor( 1032): Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
E/WifiMonitor( 1032): WifiMonitor:p2p0 cnt=7 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
E/WifiMonitor( 1032): handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
D/HeadsetStateMachine( 6105): max_hf_connections = 1
I/bluedroid-qcom( 6105): get_profile_interface handsfree
D/LGWifiP2pService( 1032): InactiveState{ when=0 what=139287 arg2=1 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1032): P2pEnabledState{ when=0 what=139287 arg2=1 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1032): DefaultState{ when=0 what=139287 arg2=1 target=com.android.internal.util.StateMachine$SmHandler }
V/ToneGenerator( 6105): ToneGenerator constructor: streamType=8, volume=1.000000
D/WifiService( 1032): New client listening to asynchronous messages
D/LGWifiP2pService( 1032): InactiveState{ when=0 what=139285 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
V/AudioPolicyService(  315): registerClient() client 0xb119dd60, uid 1002
V/AudioPolicyManager(  315): getOutput() device 2, stream 8, samplingRate 0, format 0, channelMask 3, flags 0
E/WifiMonitor( 1032): handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
V/AudioPolicyManagerEx(  315): AudioPolicyManagerEx: getOutputForDevice
V/AudioPolicyManagerEx(  315): getOutput() returns output 2
D/WifiMonitor( 1032): Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
E/WifiMonitor( 1032): WifiMonitor:p2p0 cnt=8 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
D/LGWifiP2pService( 1032): P2pEnabledState{ when=-1ms w,hat=139285 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiMonitor( 1032): handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
E/WifiMonitor( 1032): handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
D/LGWifiP2pService( 1032): DefaultState{ when=-1ms what=139285 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
V/AudioSystem( 6105): getOutputSamplingRate() no output descriptor for output 2 in gOutputs
V/AudioFlinger(  315): registerClient() client 0xb1433388, pid 6105
W/WfdsService( 1942): DefaultState - msg [9441285] is not handled
V/ToneGenerator( 6105): Create Track: 0xb4928080
V/AudioTrack( 6105): set(): streamType 8, sampleRate 0, format 0x1, channelMask 0x1, frameCount 0, flags #4, notificationFrames 0, sessionId 0, transferType 1
V/AudioTrack( 6105): set() streamType 8, sampleRate 0, format 1, frameCount 0, flags 0004
V/AudioPolicyManager(  315): getOutputForAttr() usage=3, content=4, tag= flags=00000000
V/AudioPolicyManager(  315): getOutputForAttr() device 2, samplingRate 0, format 0, channelMask 3, flags 0
V/AudioPolicyManagerEx(  315): AudioPolicyManagerEx: getOutputForDevice
V/AudioPolicyManagerEx(  315): getOutput() returns output 2
V/AudioSystem( 6105): getOutputSamplingRate() no output descriptor for output 2 in gOutputs
V/AudioSystem(  315): ioConfigChanged() event 0, ioHandle 2
V/AudioSystem(  315): ioConfigChanged() opening already existing output! 2
V/AudioSystem( 2141): ioConfigChanged() event 0, ioHandle 2
V/AudioSystem( 2141): ioConfigChanged() opening already existing output! 2
V/AudioSystem( 3242): ioConfigChanged() event 0, ioHandle 2
V/AudioSystem( 3242): ioConfigChanged() opening already existing output! 2
V/AudioSystem( 6105): ioConfigChanged() event 0, ioHandle 2
V/AudioSystem( 6105): ioConfigChanged() new output samplingRate 48000, format 0x5 channel mask 0x3 frameCount 960 latency 50
V/AudioSystem(  315): ioConfigChanged() event 0, ioHandle 4
V/AudioSystem(  315): ioConfigChanged() opening already existing output! 4
V/AudioSystem( 2141): ioConfigChanged() event 0, ioHandle 4
V/AudioSystem( 2141): ioConfigChanged() opening already existing output! 4
V/AudioSystem( 3242): ioConfigChanged() event 0, ioHandle 4
V/AudioSystem( 3242): ioConfigChanged() opening already existing output! 4
V/AudioSystem( 6105): ioConfigChanged() event 0, ioHandle 4
V/AudioSystem( 6105): ioConfigChanged() new output samplingRate 48000, format 0x1 channel mask 0x3 frameCount 960 latency 80
I/AudioFlinger(  315): isAudioPlaybackHookOn() false
V/AudioPolicyManager(  315): getOutputForAttr() usage=3, content=4, tag= flags=00000000
V/AudioPolicyManager(  315): getOutputForAttr() device 2, samplingRate 48000, format 1, channelMask 1, flags 4
V/AudioPolicyManagerEx(  315): AudioPolicyManagerEx: getOutputForDevice
V/AudioPolicyManagerEx(  315): getOutput() returns output 2
V/AudioSystem( 6105): getLatency() output 2, latency 50
V/AudioSystem( 6105): getFrameCount() output 2, frameCount 960
V/AudioTrack( 6105): createTrack_l() output 2 afLatency 50
V/AudioFlinger(  315): [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
V/AudioFlinger(  315): [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
V/AudioFlinger(  315): [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
V/AudioFlinger(  315): [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
V/AudioFlinger(  315): createTrack() lSessionId: 16
V/AudioSystem( 1852): ioConfigChanged() event 0, ioHandle 2
V/AudioSystem( 1852): ioConfigChanged() opening already existing output! 2
V/AudioSystem( 1852): ioConfigChanged() event 0, ioHandle 4
V/AudioSystem( 1852): ioConfigChanged() opening already existing output! 4
V/AudioSystem( 1452): ioConfigChanged() event 0, ioHandle 2
V/AudioSystem( 1452): ioConfigChanged() opening already existing output! 2
V/AudioSystem( 1452): ioConfigChanged() event 0, ioHandle 4
V/AudioSystem( 1452): ioConfigChanged() opening already existing output! 4
V/AudioSystem( 1032): ioConfigChanged() event 0, ioHandle 2
V/AudioSystem( 1032): ioConfigChanged() opening already existing output! 2
V/AudioSystem( 1032): ioConfigChanged() event 0, ioHandle 4
V/AudioSystem( 1032): ioConfigChanged() opening already existing output! 4
V/AudioTrack( 6105): AUDIO_OUTPUT_FLAG_FAST successful; frameCount 480
V/AudioFlinger(  315): acquiring 16 from 6105, for 6105
V/AudioFlinger(  315):  added new entry for 16
V/ToneGenerator( 6105): ToneGenerator INIT OK, time: 113606
D/BluetoothAdapterService( 6105): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@26ac4986
D/HeadsetStateMachine( 6105): Enter Disconnected: -2, size: 0
D/BluetoothAdapterService( 6105): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@26ac4986
D/BluetoothA2dp( 1032): Proxy object connected
D/A2dpService( 6105): Received start request. Starting profile...
D/HeadsetPhoneState( 6105): [BTUI] listenForPhoneState : start = false
I/BluetoothAvrcpServiceJni( 6105): classInitNative: succeeds
D/LGBluetoothHfpManager( 6105): [BTUI] listenForMultiSimPhoneState : start = false
D/HeadsetStateMachine( 6105): [BTUI] change sampling rate to 8000 when device is disconnected
V/Avrcp   ( 6105): make
D/Avrcp   ( 6105): [BTUI] Use Native AVRCP : init jni
I/bluedroid-qcom( 6105): get_profile_interface avrcp
V/AudioFlinger(  315): setParameters(): io 0, keyvalue bt_samplerate=8000, calling pid 6105
D/audio_hw_primary(  315): adev_set_parameters: enter: bt_samplerate=8000
V/voice   (  315): voice_set_parameters: enter: bt_samplerate=8000
V/compress_voip(  315): voice_extn_compress_voip_set_parameters: enter: bt_samplerate=8000
V/compress_voip(  315): voice_extn_compress_voip_set_parameters: exit
V/voice   (  315): voice_set_parameters: exit with code(0)
V/msm8974_platform_lge(  315): LGE_platform_set_parameters: enter: bt_samplerate=8000
V/msm8974_platform(  315): platform_set_parameters: enter: bt_samplerate=8000
V/msm8974_platform(  315): platform_set_parameters: exit with code(0)
V/lge_audio_loopback(  315): lge_platform_set_loopback_parameters: enter: 
V/audio_hw_primary(  315): adev_set_parameters: exit with code(0)
E/audio_a2dp_hw(  315): adev_set_parameters: ERROR: set param called even when stream out is null
V/ToneGenerator( 6105): ToneGenerator destructor
V/ToneGenerator( 6105): stopTone
V/ToneGenerator( 6105): Delete Track: 0xb4928080
V/AudioTrack( 6105): ~AudioTrack, releasing session id from 6105 on behalf of 6105
V/AudioPolicyService(  315): AudioCommandThread() adding release output 2
V/AudioPolicyService(  315): inserting command: 6 at index 0, num commands 0
V/AudioFlinger(  315): releasing 16 from 6105 for 6105
V/AudioFlinger(  315):  decremented refcount to 0
V/AudioFlinger(  315): PlaybackThread::Track destructor
V/AudioFlinger(  315): purging stale effects
V/AudioPolicyService(  315): AudioCommandThread() waking up
V/AudioFlinger(  315): removeClient_l() pid 6105, calling pid 315
V/AudioPolicyService(  315): AudioCommandThread() processing release output 2
V/AudioPolicyManager(  315): releaseOutput() 2
V/AudioPolicyService(  315): AudioCommandThread() going to sleep
V/AudioManager( 6105): registerRemoteController: size of Media player list: 0
E/AudioManager( 6105): No RCC entry present to update
E/RemoteController( 6105): Cannot set synchronization mode on an unregistered RemoteController
I/BluetoothAvrcpQcomServiceJni( 6105): classInitQcomNative: succeeds
D/LGBluetoothAvrcpQcomAdapter( 6105): [BTUI] Use QCOM AVRCP 1.5 : init jni, browsing = false
I/BluetoothAvrcpQcomServiceJni( 6105): initQcomNative: succeeds
,D/LGBluetoothAvrcpQcomAdapter( 6105): [BTUI] [+] updateMediaPlayerInfo
I/ActivityManager( 1032): Killing 5433:com.android.contacts/u0a19 (adj 15): empty #17
V/WiFiOffLoadBroadcast( 6193): WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
D/WifiService( 1032): New client listening to asynchronous messages
,V/SIM_STK ( 1032): Menu title from STK is T-Mobile
V/SIM_STK ( 1032): Menu title from STK is T-Mobile
,D/LgDataFeature( 6193): LgDataFeature() Constructor: none
D/LgDataFeature( 6193): LgDataFeature() Constructor Done, null
D/WiFiOffLoadUpdatePriority( 6193): remove : truetruetrue
E/WifiStateMachine( 1032):  DisconnectedState CMD_GET_CONFIGURED_NETWORKS uid=1000 1000 0 num=1
E/WifiStateMachine( 1032):  ConnectModeState CMD_GET_CONFIGURED_NETWORKS uid=1000 1000 0 num=1
,E/WifiStateMachine( 1032):  DisconnectedState CMD_SAVE_CONFIG uid=1000 0 0
E/WifiStateMachine( 1032):  ConnectModeState CMD_SAVE_CONFIG uid=1000 0 0
D/WifiNative-wlan0( 1032): doBoolean: SAVE_CONFIG
D/WifiNative-wlan0( 1032): SAVE_CONFIG: returned true
D/WiFiOffLoadUpdatePriority( 6193): remove1
V/WiFiOffLoadSharedPrefsUtils( 6193): save remove
D/WiFiOffLoadBroadcast( 6193): mLastConnectedNetwork from SharedPrefsUtils for wifioffloading : null
D/WiFiOffLoadBroadcast( 6193): S: false, R: false
,E/WifiStateMachine( 1032):  DisconnectedState CMD_GET_CONFIGURED_NETWORKS uid=1000 1000 0 num=1
E/WifiStateMachine( 1032):  ConnectModeState CMD_GET_CONFIGURED_NETWORKS uid=1000 1000 0 num=1
D/WiFiOffLoadUpdatePriority( 6193): saved SSID: "NG700"
D/WiFiOffLoadUpdatePriority( 6193): connected SSID: null
D/WiFiOffLoadUpdatePriority( 6193): private wpa: "NG700" 300
D/WifiServiceImplEx( 1032): addOrUpdateNetwork pid=6193, uid=1000, packageName=android.uid.system:1000
E/addOrUpdateNetwork( 1032):  uid = 1000 SSID "NG700" nid=0
E/WifiStateMachine( 1032):  DisconnectedState CMD_ADD_OR_UPDATE_NETWORK uid=1000 0 0 "NG700"WPA_PSK prio=300 status=2
E/WifiStateMachine( 1032):  ConnectModeState CMD_ADD_OR_UPDATE_NETWORK uid=1000 0 0 "NG700"WPA_PSK prio=300 status=2
E/WifiConfigStore( 1032):  key="NG700"WPA_PSK netId=0 uid=0/1000
D/WifiServerServiceExt( 1032): addOrUpdateNetwork: mThisIsFirstEnableing = false
D/WifiNative-wlan0( 1032): doBoolean: SET_NETWORK 0 ssid 4e47373030
D/WifiNative-wlan0( 1032): SET_NETWORK 0 ssid 4e47373030: returned true
D/WifiNative-wlan0( 1032): doBoolean: SET_NETWORK 0 key_mgmt WPA-PSK
,E/WifiMonitor( 1032): WifiMonitor:wlan0 cnt=9 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
I/wpa_supplicant( 6130): [LGE_PATCH]scan interval[0] = 2 sec.
E/WifiMonitor( 1032): handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
,D/WifiMonitor( 1032): Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
E/WifiMonitor( 1032): WifiMonitor:wlan0 cnt=10 dispatchEvent: WPS-AP-AVAILABLE 
W/WifiMonitor( 1032): couldn't identify event type - WPS-AP-AVAILABLE 
E/WifiMonitor( 1032): WifiMonitor:p2p0 cnt=11 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
E/WifiMonitor( 1032): handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
D/WifiNative-wlan0( 1032): SET_NETWORK 0 key_mgmt WPA-PSK: returned true
D/WfdsMonitor( 1942): Event [CTRL-EVENT-SCAN-RESULTS ]
D/WifiMonitor( 1032): Event [IFNAME=p2p0 WPS-AP-AVAILABLE ]
E/WifiMonitor( 1032): WifiMonitor:p2p0 cnt=12 dispatchEvent: WPS-AP-AVAILABLE 
W/WifiMonitor( 1032): couldn't identify event type - WPS-AP-AVAILABLE 
D/WifiNative-wlan0( 1032): doBoolean: SET_NETWORK 0 proto WPA RSN
D/WfdsMonitor( 1942): Event [WPS-AP-AVAILABLE ]
D/LGWifiP2pService( 1032): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1032): P2pEnabledState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1032): DefaultState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
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
W/libprocessgroup( 1032): failed to open /acct/uid_10019/pid_5433/cgroup.procs: No such file or directory
,W/ActivityManager( 1032): getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
D/WiFiOffLoadUpdatePriority( 6193):  ssid "NG700" prio 300
D/WiFiOffLoadUpdatePriority( 6193): configuration updated: 0
,E/WifiStateMachine( 1032):  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=0 bcn=0
E/WifiStateMachine( 1032):  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=0 bcn=0
E/WifiStateMachine( 1032):  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=0 bcn=0
E/WifiStateMachine( 1032):  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=0 bcn=0
I/WifiNative-HAL( 1032): startHal
E/wifi    ( 1032): getStaticLongField sWifiHalHandle 0x989628cc
E/WifiHAL ( 1032): Could not connect handle
D/wifi    ( 1032): halHandle = 0x0, mVM = 0xb487c280, mCls = 0x602106
I/WifiNative-HAL( 1032): Could not start hal
D/WifiNative-wlan0( 1032): doString: [BSS RANGE=0- MASK=0x21987]
D/LGBluetoothAvrcpQcomAdapter( 6105): [BTUI] installed app name: Music
E/WifiStateMachine( 1032):  DisconnectedState CMD_SAVE_CONFIG uid=1000 0 0
D/LGBluetoothAvrcpQcomAdapter( 6105): [BTUI] installed app name: Google Play Music
D/LGBluetoothAvrcpQcomAdapter( 6105): [BTUI] === MediaPlayerInfo (playerId:0) ===
D/LGBluetoothAvrcpQcomAdapter( 6105): [BTUI]          displayName: Music
D/LGBluetoothAvrcpQcomAdapter( 6105): [BTUI]          packageName: com.lge.music
D/LGBluetoothAvrcpQcomAdapter( 6105): [BTUI]          playState: 2 (PAUSED)
D/LGBluetoothAvrcpQcomAdapter( 6105): [BTUI] === MediaPlayerInfo (playerId:1) ===
D/LGBluetoothAvrcpQcomAdapter( 6105): [BTUI]          displayName: Google Play Music
D/LGBluetoothAvrcpQcomAdapter( 6105): [BTUI]          packageName: com.google.android.music
D/LGBluetoothAvrcpQcomAdapter( 6105): [BTUI]          playState: 2 (PAUSED)
D/LGBluetoothAvrcpQcomAdapter( 6105): [BTUI] [-] updateMediaPlayerInfo
I/BluetoothA2dpServiceJni( 6105): classInitNative
I/BluetoothA2dpServiceJni( 6105): classInitNative: succeeds
D/A2dpStateMachine( 6105): make
E/WifiStateMachine( 1032):  ConnectModeState CMD_SAVE_CONFIG uid=1000 0 0
D/WifiNative-wlan0( 1032): doBoolean: SAVE_CONFIG
I/bluedroid-qcom( 6105): get_profile_interface a2dp
I/GKI_LINUX( 6105): gki_task_entry task_id=2 [A2DP-MEDIA] starting
,I/LGBluetoothA2dpServiceJni( 6105): classInitNative: succeeds
I/LGBluetoothA2dpAdapter( 6105): [BTUI] getInstance : create [LGBluetoothA2dpAdapter]
D/BluetoothAdapterService( 6105): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@26ac4986
D/A2dpStateMachine( 6105): Enter Disconnected: -2
I/BluetoothHidServiceJni( 6105): classInitNative: succeeds
D/WifiNative-wlan0( 1032): SAVE_CONFIG: returned true
D/WiFiOffLoadUpdatePriority( 6193): configuration saved: true
D/HidService( 6105): Received start request. Starting profile...
I/bluedroid-qcom( 6105): get_profile_interface hidhost
D/BluetoothAdapterService( 6105): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@26ac4986
I/BluetoothHealthServiceJni( 6105): classInitNative: succeeds
D/HealthService( 6105): Received start request. Starting profile...
I/bluedroid-qcom( 6105): get_profile_interface health
I/LGBluetoothHealthServiceJni( 6105): classInitNative: succeeds
D/BluetoothAdapterService( 6105): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@26ac4986
,I/BluetoothPanServiceJni( 6105): classInitNative(L105): succeeds
D/PanService( 6105): Received start request. Starting profile...
D/BluetoothPanServiceJni( 6105): initializeNative(L110): pan
I/bluedroid-qcom( 6105): get_profile_interface pan
I/LGBluetoothPanAdapter( 6105): [BTUI] getInstance : create [LGBluetoothPanAdapter]
D/BluetoothAdapterService( 6105): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@26ac4986
D/UsbSettingsReceiver( 6193): [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
I/BtGatt.JNI( 6105): classInitNative(L901): classInitNative: Success!
D/UsbSettingsReceiver( 6193): [AUTORUN] sys.usb.config = ptp_only,adb
D/UsbSettingsReceiver( 6193): [AUTORUN] sys.usb.state = ptp_only,adb
D/UsbSettingsReceiver( 6193): [AUTORUN] persist.sys.usb.config = ptp_only,adb
D/UsbSettingsReceiver( 6193): [AUTORUN] onReceive() : app userid = 0, current userid = 0
D/BtGatt.DebugUtils( 6105): handleDebugAction() action=null
D/BtGatt.GattService( 6105): Received start request. Starting profile...
D/BtGatt.GattService( 6105): start()
I/bluedroid-qcom( 6105): get_profile_interface gatt
D/BtGatt.AdvertiseManager( 6105): advertise manager created
D/BluetoothAdapterService( 6105): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@26ac4986
,D/BluetoothAdapterService( 6105): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@26ac4986
I/LGBluetoothMapAdapter( 6105): [BTUI] getInstance : create [LGBluetoothMapAdapter]
V/BluetoothMapService( 6105): BluetoothMapBinder()
D/BluetoothMapService( 6105): Received start request. Starting profile...
D/BluetoothMapService( 6105): start()
D/UsbSettingsControl( 6193): [AUTORUN] getUsbConnected() : connected=true
D/UsbSettingsReceiver( 6193): [AUTORUN] onReceive() : availableList=[]
D/UsbSettingsReceiver( 6193): [AUTORUN] onReceive() : activeList=[]
D/UsbSettingsReceiver( 6193): [AUTORUN] onReceive() : errorList=[]
,D/BluetoothMapEmailSettingsLoader( 6105): Found 0 applications
D/UsbSettingsControl( 6193): [AUTORUN] isAutorunTimer() : mAutorunChanging=false
D/BluetoothMapEmailAppObserver( 6105): createReceiver()
D/UsbSettingsControl( 6193): [AUTORUN] setTetherStatus() : status=false
D/BluetoothMapEmailAppObserver( 6105): initObservers()
D/BluetoothMapEmailAppObserver( 6105): getEnabledAccountItems()
D/PCSuite ( 6171): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
D/BluetoothAdapterService( 6105): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@26ac4986
V/WiFiOffLoadBroadcast( 6193): WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
D/HeadsetStateMachine( 6105): Proxy object connected
D/LGBluetoothHfpAdapter( 6105): [BTUI] queryPhoneState
D/LGBluetoothHfpAdapter( 6105): Try to query the phonestate on bind
D/BluetoothPhoneService.BluetoothLTECall( 1852):  call mBluetoothHeadset.phoneStateChanged()
,W/BluetoothHeadset( 1852): Proxy not attached to service
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
W/FormManager( 6131): Network not available. Please check & try again.
D/BluetoothAdapterService( 6105): Profile still not running:com.android.bluetooth.gatt.GattService
D/HeadsetStateMachine( 6105): Disconnected process message: 10, size: 0
D/HeadsetPhoneState( 6105): sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
D/HeadsetStateMachine( 6105): Disconnected process message: 11, size: 0
V/BluetoothPbapReceiver( 6105): PbapReceiver onReceive 
,D/WiFiOffLoadBroadcast( 6193): MCCMNC not supported: null
V/BluetoothPbapReceiver( 6105): ***********action = android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothPbapReceiver( 6105): ***********state = 11
D/BluetoothAdapterService( 6105): Profile still not running:com.android.bluetooth.gatt.GattService
D/BluetoothAdapterService( 6105): Profile still not running:com.android.bluetooth.gatt.GattService
D/BluetoothAdapterService( 6105): Profile still not running:com.android.bluetooth.gatt.GattService
V/PanService( 6105): [BTUI] SIM Extra State :ABSENT
D/BluetoothAdapterService( 6105): Profile still not running:com.android.bluetooth.gatt.GattService
D/BluetoothAdapterService( 6105): Profile still not running:com.android.bluetooth.map.BluetoothMapService
V/BluetoothMapService( 6105): Handler(): got msg=1
D/BluetoothAdapterState( 6105): CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
I/bluedroid-qcom( 6105): enable
I/GKI_LINUX( 6105): gki_task_entry task_id=0 [BTU] starting
I/bt-btu  ( 6105): btu_task pending for preload complete event
I/bt_hci_bdroid( 6105): init
,I/bt_vendor( 6105): bt-vendor : init
I/bt_vendor( 6105): bt-vendor : get_bt_soc_type
E/bt_vendor( 6105): get_bt_soc_type: Failed to get soc type
I/bt_vendor( 6105): init: Local BD Address : c0:64:73:54:3f:58
D/bt_userial_mct( 6105): userial_init
D/bt_hci_bdroid( 6105): set_power 1
I/bt_vendor( 6105): bt-vendor : BT_VND_OP_POWER_CTRL: On
I/bt_vendor( 6105): Starting hciattach daemon
I/bt_vendor( 6105): try to set true
W/sh      ( 6234): type=1400 audit(0.0:155): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
W/sh      ( 6234): type=1400 audit(0.0:156): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
I/ActivityManager( 1032): Start proc com.lge.lifetracker for broadcast com.lge.lifetracker/.receiver.HealthDeviceReceiver: pid=6235 uid=10037 gids={50037, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
V/FormManager( 6131): Network unavailable.
,D/LGDMClient( 3951): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
D/LGDMClient( 3951): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
W/ContextImpl( 3951): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
I/qcom-bluetooth( 6244): /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  
W/ContextImpl( 3951): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
V/FormManager( 6131): Network unavailable.
D/PostponalbeReceiver( 5124): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
D/LGDMClient( 3951): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=3, isUserType=1
D/LGDMClient( 3951): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
,I/PCSuite ( 6171): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 6171): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 6171): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 6193): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6193): MCCMNC not supported: null
D/LGDMClient( 3951): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
D/QRemote ( 5964): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,D/QRemote ( 5964): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/qcom-bluetooth( 6261): /system/etc/init.qcom.bt.sh: Transport : smd 
I/qcom-bluetooth( 6264): /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,I/QRemote ( 5964): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
V/[BNRBootReceiver]( 5938): boot receiver action = android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,D/BNRAndroBeam( 5938): [BnR DirectBeam] Android Direct Beam(NFC) Connection changed
V/[BNRBootReceiver]( 5938): Boot Receiver Return
I/qcom-bluetooth( 6266): /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
D/PostponalbeReceiver( 5124): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
V/WiFiOffLoadBroadcast( 6193): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,I/qcom-bluetooth( 6269): /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> 
E/ActivityThread( 6235): Failed to find provider info for com.lge.lgaccount.provider
W/LG Account v2.2( 6235): No ProfileInfo entries
I/LG Account v2.2( 6235): isEnabled: false
I/Feature ( 6235): [Lifetracker]ver: 4.21.112(40211120)
I/Feature ( 6235): [Lifetracker]Country: EU
I/Feature ( 6235): [Lifetracker]Operator: OPEN
I/Feature ( 6235): [Lifetracker]Ranking support: false
I/Feature ( 6235): [Lifetracker]Comfort support: false
I/Feature ( 6235): [Lifetracker]Accessory: true
I/Feature ( 6235): [Lifetracker]Health device: true
I/Feature ( 6235): [Lifetracker]Extra Pedometer: false
I/Feature ( 6235): [Lifetracker]Blood glucose device: false
I/Feature ( 6235): [Lifetracker]Device Number: 3
D/WiFiOffLoadBroadcast( 6193): MCCMNC not supported: null
I/qcom-bluetooth( 6271): /system/etc/init.qcom.bt.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
D/BluetoothPermissionRequest( 6193): onReceive
I/qcom-bluetooth( 6272): /system/etc/init.qcom.bt.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> 
D/LGBluetoothFeatureConfig( 6193):  get() - isFeatureLoaded : false
,D/BluetoothManagerService( 1032): Message: 20
D/BluetoothManagerService( 1032): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@2b1a4e1d:true
I/ActivityManager( 1032): Killing 5792:com.lge.email/u0a23 (adj 15): empty #17
D/LGBluetoothResetSettingReceiver( 6193): return without doing reset settings.
,I/libmdmdetect( 6274): ESOC framework not supported
E/Diag_Lib( 6274):  Diag_LSM_Init: Failed to open handle to diag driver, error = 13
D/bthci_qcomm_linux( 6274): [BTUI] bt_hci_qcomm_pfal_get_bdaddress: Get BDADDR from bluedroid prop (58:3F:54:73:64:C0)
D/bthci_qcomm_common( 6274): [BTUI] bt_hci_qcomm_init:
D/bthci_qcomm_common( 6274): [BTUI]     BDADDR: 58:3F:54:73:64:C0
D/bthci_qcomm_common( 6274): [BTUI]     BR/EDR: Class 1
,D/bthci_qcomm_common( 6274): [BTUI]     LE: Class 2
D/bthci_qcomm_common( 6274): [BTUI]     Ref Clock: 32M
D/btqsocnvmtags( 6274): [BTUI] init_riva_entries: set NORMAL power settings
D/LGBluetoothOppAdapter( 6105): [BTUI] getInstance : create [LGBluetoothOppAdapter]
,W/libprocessgroup( 1032): failed to open /acct/uid_10023/pid_5792/cgroup.procs: No such file or directory
D/QRemote ( 5964): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,D/QRemote ( 5964): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 5964): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
V/BluetoothFtpReceiver( 6105): BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
V/WiFiOffLoadBroadcast( 6193): WiFiOffLoadBroadcast: android.net.wifi.SCAN_RESULTS
V/BluetoothSapReceiver( 6105): [BTUI] checkServiceStart
V/BluetoothSapReceiver( 6105): [BTUI] region:EU country:EU
V/BluetoothSapReceiver( 6105): SapReceiver onReceive 
V/BluetoothSapReceiver( 6105): action = android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothSapReceiver( 6105):  Bluetooth Adapter state = 11
,D/WiFiOffLoadBroadcast( 6193): Not supported operator for automatic switch
I/rmt_storage(  308): rmt_storage_connect_cb: clnt_h=0x5 conn_h=0xb6403090
,I/rmt_storage(  308): rmt_storage_rw_iovec_cb: /boot/modem_fs1: clnt_h=0x1: req_h=0x9 msg_id=3: R/W request received
I/rmt_storage(  308): wakelock acquired: 1, error no: 42
I/rmt_storage(  308): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 Unblock worker thread (th_id: -1236807552)
I/ActivityManager( 1032): Start proc com.lge.settings.easy for broadcast com.lge.settings.easy/com.lge.settings.bluetooth.LGBluetoothProfileConnectionReceiver: pid=6278 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,I/rmt_storage(  308): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0x9 msg_id=3: Bytes written = 1572864
I/rmt_storage(  308): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0x9 msg_id=3: Send response: res=0 err=0
I/rmt_storage(  308): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 About to block rmt_storage client thread (th_id: -1236807552) wakelock released: 1, error no: 22
I/rmt_storage(  308): 
I/rmt_storage(  308): rmt_storage_disconnect_cb: clnt_h=0x0x5 conn_h=0x0xb6403090
E/Diag_Lib(  868): [IMS_FATAL]| 3347 | 894 |ims-rtp-daemon ims_rtp_qmi_handler_thread_func waiting on select thread>
W/ResourcesManager( 6278): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,I/ActivityManager( 1032): Killing 5452:com.android.gallery3d/u0a27 (adj 15): empty #17
,W/libprocessgroup( 1032): failed to open /acct/uid_10027/pid_5452/cgroup.procs: No such file or directory
D/AuthorizationBluetoothService( 2166): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,E/QC-QMI  ( 6274): qmi_client [6274] 13: failed to locate client data
,E/QC-QMI  (  444): qmuxd: RX on fd=32 returned error=0 errno[2:No such file or directory]
E/QC-QMI  (  444): QMUX qmux_client_id=13 not found in qmux client list, unable to remove
I/qcom-bluetooth( 6304): /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 58:3f:54:73:64:c0 
,I/qcom-bluetooth( 6305): /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,I/bt_vendor( 6105): bluetooth satus is on
D/bt_hci_bdroid( 6105): preload
,D/bt_userial_mct( 6105): userial_open(port:0)
I/bt_vendor( 6105): bt-vendor : BT_VND_OP_USERIAL_OPEN
I/bt_vendor( 6105): Done intiailizing UART
,I/bt_vendor( 6105): Done intiailizing UART
I/bt_userial_mct( 6105): CMD=66, EVT=66, ACL_Out=67, ACL_In=67
I/bt_vendor( 6105): Bluetooth Firmware and transport layer are initialized
D/bt_userial_mct( 6105): Entering userial_read_thread()
I/bt-btu  ( 6105): btu_task received preload complete event
W/bt-l2cap( 6105): L2CAP - L2CA_Register() called for PSM: 0x0001
W/bt-l2cap( 6105): L2CAP - L2CA_Register() called for PSM: 0x001f
W/bt-l2cap( 6105): L2CAP - L2CA_Register() called for PSM: 0x0003
I/        ( 6105): BTE_InitTraceLevels -- TRC_HCI
I/        ( 6105): BTE_InitTraceLevels -- TRC_L2CAP
,I/        ( 6105): BTE_InitTraceLevels -- TRC_RFCOMM
I/        ( 6105): BTE_InitTraceLevels -- TRC_AVDT
I/        ( 6105): BTE_InitTraceLevels -- TRC_AVRC
I/        ( 6105): BTE_InitTraceLevels -- TRC_A2D
I/        ( 6105): BTE_InitTraceLevels -- TRC_BNEP
I/        ( 6105): BTE_InitTraceLevels -- TRC_BTM
I/        ( 6105): BTE_InitTraceLevels -- TRC_HID_HOST
I/        ( 6105): BTE_InitTraceLevels -- TRC_GAP
I/        ( 6105): BTE_InitTraceLevels -- TRC_PAN
I/        ( 6105): BTE_InitTraceLevels -- TRC_SDP
I/        ( 6105): BTE_InitTraceLevels -- TRC_GATT
I/        ( 6105): BTE_InitTraceLevels -- TRC_SMP
I/        ( 6105): BTE_InitTraceLevels -- TRC_BTAPP
I/        ( 6105): BTE_InitTraceLevels -- TRC_BTIF
W/bt-btm  ( 6105): btm_decode_ext_features_page Secure conn Controller support Enabled
E/bt-btm  ( 6105): BTM_SecRegister:p_cb_info->p_le_callback == 0xa01e5061 
E/bt-btm  ( 6105): BTM_SecRegister: btm_cb.api.p_le_callback = 0xa01e5061 
,E/bt-btif ( 6105): Calling BTA_HhEnable
E/bt-btif ( 6105): btif_storage_get_adapter_property service_mask:0x2140040
D/BluetoothAdapterProperties( 6105): Address is:58:3F:54:73:64:C0
,D/BluetoothAdapterProperties( 6105): Name is: G3-1
D/BluetoothAdapterProperties( 6105): Scan Mode:20
D/BluetoothAdapterProperties( 6105): Discoverable Timeout:120
D/bt_hci_bdroid( 6105): postload
W/bt-l2cap( 6105): L2CAP - L2CA_Register() called for PSM: 0x0019
W/bt-l2cap( 6105): L2CAP - L2CA_Register() called for PSM: 0x0017
W/bt-l2cap( 6105): L2CAP - L2CA_Register() called for PSM: 0x001b
W/bt-l2cap( 6105): L2CAP - L2CA_Register() called for PSM: 0x0011
W/bt-l2cap( 6105): L2CAP - L2CA_Register() called for PSM: 0x0013
D/BluetoothManagerService( 1032): Bluetooth Adapter name changed to G3-1
D/bt_hci_bdroid( 6105): Used up Tx Cmd credits
W/bt-l2cap( 6105): L2CAP - L2CA_Register() called for PSM: 0x000f
D/BluetoothManagerService( 1032): Stored Bluetooth name: G3-1
D/bt_hci_bdroid( 6105): Used up Tx Cmd credits
D/bt_hci_bdroid( 6105): Used up Tx Cmd credits
D/bte_conf( 6105): Device ID record 1 : primary
D/bte_conf( 6105):   vendorId            = 00c4
D/bte_conf( 6105):   vendorIdSource      = 0001
D/bte_conf( 6105):   product             = 13a1
D/bte_conf( 6105):   version             = 1000
D/bte_conf( 6105):   clientExecutableURL = 
D/bte_conf( 6105):   serviceDescription  = 
D/bte_conf( 6105):   documentationURL    = 
D/bte_conf( 6105): bte_load_did_conf no section named DID2.
D/bt_hci_bdroid( 6105): Used up Tx Cmd credits
D/BluetoothAdapterState( 6105): CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
D/BluetoothAdapterProperties( 6105): ScanMode =  20
D/BluetoothAdapterProperties( 6105): State =  11
D/BluetoothAdapterProperties( 6105): mDiscoverableTimeout = 120
V/LGBluetoothServiceAdapter( 6105): [BTUI] state:11, scanmode:20, timeout:120
D/BluetoothAdapterProperties( 6105): Setting state to 12
I/BluetoothAdapterState( 6105): Bluetooth adapter state changed: 11-> 12
D/BluetoothPanServiceJni( 6105): control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
D/btif_config_util( 6105): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
W/sh      ( 6318): type=1400 audit(0.0:157): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
W/sh      ( 6318): type=1400 audit(0.0:158): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,D/BluetoothManagerService( 1032): Message: 60
D/BluetoothManagerService( 1032): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
E/bt_mct  ( 6105): hci lib postload completed
D/BluetoothManagerService( 1032): Broadcasting onBluetoothStateChange(true) to 5 receivers.
D/BluetoothHeadset( 1032): onBluetoothStateChange: up=true
D/BluetoothHeadset( 1852): onBluetoothStateChange: up=true
D/BluetoothHeadset( 1852): onBluetoothStateChange: up=true
I/BluetoothAdapterState( 6105): Entering On State
D/BluetoothHeadset( 1852): onBluetoothStateChange: up=true
D/BluetoothA2dp( 1032): onBluetoothStateChange: up=true
E/BluetoothManagerService( 1032): Fail to bind to: Intent { act=android.bluetooth.IQBluetooth }
D/BluetoothManagerService( 1032): Bluetooth State Change Intent: 11 -> 12
D/LGBluetoothServiceAdapter( 6105): [BTUI] OnState
D/LGBluetoothServiceAdapter( 6105): [BTUI]         global_name: G3-1
I/[SystemUI]BluetoothHandler( 1452): Receive : BluetoothAdapter.ACTION_STATE_CHANGED
D/LGBluetoothServiceAdapter( 6105): [BTUI]         local_name: G3-1
D/LGBluetoothAPIService( 1942): [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
,D/LGBluetoothAPIService( 1942): Message: 1
D/LGBluetoothAPIService( 1942): MESSAGE_BOOT_COMPLETED
W/bt-smp  ( 6105): Key(LSB ~ MSB) = 0a 3c a6 fe eb 17 6a 79 a6 1f 0a 0b f9 50 a0 5f 
W/bt-smp  ( 6105): Plain text(LSB ~ MSB) = ee 68 7a 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 6105): Encrypted text(LSB ~ MSB) = 9b f7 03 58 61 76 3c 06 80 58 66 ac 18 bb 7b 90 
W/bt-btm  ( 6105): Stopping oneshot timer
D/BluetoothAdapterProperties( 6105): Discoverable Timeout:120
D/LGBluetoothDeviceModeControllManager( 6105): adapterPropertyChangedCallback on  LGAdapter : do nothing - 9
D/BluetoothManagerService( 1032): BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
D/BluetoothAdapterService( 6105): [BTUI] autoConnect() : not allowed
D/BluetoothManagerService( 1032): Message: 40
D/BluetoothManagerService( 1032): MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
I/LGBluetoothAPIService( 1942): [BTUI] LGBluetoothAPIService Binding Success
I/BluetoothMapService( 6105): onReceive: android.bluetooth.adapter.action.STATE_CHANGED
,D/BluetoothMapService( 6105): STATE_ON
V/BluetoothMapService( 6105): Handler(): got msg=1
D/BluetoothMapMasInstance( 6105): Map Service startRfcommSocketListener
W/ContextImpl( 6193): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
W/bt-smp  ( 6105): Key(LSB ~ MSB) = 0a 3c a6 fe eb 17 6a 79 a6 1f 0a 0b f9 50 a0 5f 
W/bt-smp  ( 6105): Plain text(LSB ~ MSB) = c2 6d 43 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 6105): Encrypted text(LSB ~ MSB) = 97 9d 46 eb b5 c6 9b c8 d4 a9 06 41 5c ed d3 f5 
W/bt-btm  ( 6105): Stopping oneshot timer
D/LGBluetoothAPIServer( 6105): [BTUI] onCreate()
D/LGBluetoothAPIServer( 6105): [BTUI] onBind()
D/LGBluetoothAPIService( 1942): [BTUI] LGBluetoothAPIServiceConnection: connected to LGBluetoothAPIAdapter
D/LGBluetoothAPIService( 1942): Message: 100
D/LGBluetoothAPIService( 1942): MESSAGE_BLUETOOTH_SERVICE_CONNECTED
,W/bt-smp  ( 6105): Key(LSB ~ MSB) = 0a 3c a6 fe eb 17 6a 79 a6 1f 0a 0b f9 50 a0 5f 
W/bt-smp  ( 6105): Plain text(LSB ~ MSB) = 8e 35 42 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 6105): Encrypted text(LSB ~ MSB) = fc 9e 50 31 4e c3 ef 83 75 9d 04 cb 3e 93 bf c8 
W/bt-btm  ( 6105): Stopping oneshot timer
I/qcom-bt-wlan-coex( 6328): /system/etc/init.qcom.coex.sh: btwlancoex/abtfilt not available 
D/BluetoothMapMasInstance( 6105): MAS initSocket()
D/BluetoothMapMasInstance( 6105):   masId = 00
D/BluetoothMapMasInstance( 6105):   msgTypes = 0e
D/BluetoothMapMasInstance( 6105):   masName = SMS/MMS
D/BluetoothMapMasInstance( 6105):   SDP string = 000eSMS/MMS
D/LocalBluetoothProfileManager( 6193): Adding local A2DP profile
D/BluetoothManagerService( 1032): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
W/BluetoothAdapter( 6105): getBluetoothService() called with no BluetoothManagerCallback
,W/bt-smp  ( 6105): Key(LSB ~ MSB) = 0a 3c a6 fe eb 17 6a 79 a6 1f 0a 0b f9 50 a0 5f 
W/bt-smp  ( 6105): Plain text(LSB ~ MSB) = 5a 8e 54 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 6105): Encrypted text(LSB ~ MSB) = f7 4d 59 cb 9e e7 cf 96 39 ae a4 89 42 c2 2c ed 
W/bt-btm  ( 6105): Stopping oneshot timer
D/BluetoothManagerService( 1032): Message: 30
D/BluetoothAdapterProperties( 6105): Scan Mode:21
D/LGBluetoothDeviceModeControllManager( 6105): getDeviceMode  deviceMode 0
D/LGBluetoothDeviceModeControllManager( 6105): [BTUI] checkDeviceModeAndSet, sinkMode : false
D/LGBluetoothServiceAdapter( 6105): [BTUI] createSocketChannel FD=73 mFd=0
V/BluetoothMapMasInstance( 6105): Succeed to create listening socket 
D/BluetoothMapMasInstance( 6105): Accepting socket connection...
D/LocalBluetoothProfileManager( 6193): Adding local HEADSET profile
D/BluetoothAdapterService( 6105): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@26ac4986
V/BluetoothPbapService( 6105): Pbap Service onCreate
V/BluetoothPbapService( 6105): Starting PBAP service
D/LGBluetoothPbapAdapter( 6105): [BTUI] getInstance : create
D/BluetoothManagerService( 1032): Message: 30
V/BluetoothPbapService( 6105): action: android.bluetooth.adapter.action.STATE_CHANGED
W/bt-smp  ( 6105): Key(LSB ~ MSB) = 0a 3c a6 fe eb 17 6a 79 a6 1f 0a 0b f9 50 a0 5f 
W/bt-smp  ( 6105): Plain text(LSB ~ MSB) = b2 6a 6e 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 6105): Encrypted text(LSB ~ MSB) = 8b 6e 97 81 43 cc 9e ae 8b 6c bf 4e c8 d9 7d 67 
W/bt-btm  ( 6105): Stopping oneshot timer
V/BluetoothPbapService( 6105): state: 12
V/BluetoothPbapReceiver( 6105): PbapReceiver onReceive 
V/BluetoothPbapReceiver( 6105): ***********action = android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothPbapReceiver( 6105): ***********state = 12
V/BluetoothPbapService( 6105): Handler(): got msg=1
V/BluetoothPbapService( 6105): Pbap Service startRfcommSocketListener
,V/BluetoothPbapService( 6105): Pbap Service initSocket
D/BluetoothManagerService( 1032): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
W/BluetoothAdapter( 6105): getBluetoothService() called with no BluetoothManagerCallback
D/LGBluetoothServiceAdapter( 6105): [BTUI] createSocketChannel FD=75 mFd=73
V/BluetoothPbapService( 6105): Succeed to create listening socket 
V/BluetoothPbapService( 6105): Accepting socket connection...
D/BluetoothManagerService( 1032): Message: 30
D/BluetoothManagerService( 1032): Message: 30
D/LocalBluetoothProfileManager( 6193): Adding local MAP profile
,D/BluetoothMap( 6193): Create BluetoothMap proxy object
D/BluetoothManagerService( 1032): Message: 30
D/BluetoothManagerService( 1032): Message: 30
V/BluetoothPbapService( 6105): Pbap Service onBind
D/LocalBluetoothProfileManager( 6193): LocalBluetoothProfileManager construction complete
D/LGBluetoothUserBindClient( 6193): [BTUI] initUserBindClient
W/ContextImpl( 6193): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.android.settings.bluetooth.LGBluetoothUserBindClient.initUserBindClient:90 com.android.settings.bluetooth.LGBluetoothUserBindClient.<init>:55 com.android.settings.bluetooth.LGBluetoothUserBindClient.getInstance:47 
,D/DockEventReceiver( 6193): finishStartingService: stopping service
D/BluetoothA2dp( 6193): Proxy object connected
D/A2dpProfile( 6193): Bluetooth service connected
D/BluetoothHeadset( 6193): Proxy object connected
D/HeadsetProfile( 6193): Bluetooth service connected
,D/BluetoothInputDevice( 6193): Proxy object connected
D/HidProfile( 6193): Bluetooth service connected
D/BluetoothPan( 6193): BluetoothPAN Proxy object connected
D/PanProfile( 6193): Bluetooth service connected
D/BluetoothMap( 6193): Proxy object connected
D/MapProfile( 6193): Bluetooth service connected
D/BluetoothMap( 6193): getConnectedDevices()
V/BluetoothMapService( 6105): getConnectedDevices()
D/BluetoothPbap( 6193): Proxy object connected
,D/PbapServerProfile( 6193): Bluetooth service connected
D/LGBluetoothUserBindClient( 6193): [BTUI] onServiceConnected
D/BluetoothPermissionRequest( 6193): onReceive
D/LGBluetoothFeatureConfig( 6193): isPrivacyLogsEnabled : true
D/LGBluetoothUtils( 6193): [BTUI] FileNotFound: readProperty
D/LGBluetoothResetSettingReceiver( 6193): return without doing reset settings.
V/BluetoothOppReceiver( 6105): Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_ON
,I/LGBluetoothOppAdapter( 6105): [BTUI] startOppService()
V/BluetoothOppManager( 6105): restoreApplicationData! falsefalsenullnull
D/LGBluetoothFeatureConfig( 6105): isPrivacyLogsEnabled : true
V/BtOppService( 6105): onCreate
,V/BluetoothOppNotification( 6105): send message
V/BtOppService( 6105): Starting RfcommListener
D/BluetoothOppPreference( 6105): Dumping Names:  
D/BluetoothOppPreference( 6105): {}
D/BluetoothOppPreference( 6105): Dumping Channels:  
D/BluetoothOppPreference( 6105): {}
V/BtOppService( 6105): onStartCommand
V/BtOppService( 6105): pendingUpdate is true keepUpdateThread is false sListenStarted is true
,V/BluetoothFtpReceiver( 6105): BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothFtpReceiver( 6105): BluetoothFtpReceiver Start Service
V/BluetoothOppNotification( 6105): new notify threadi!
V/BluetoothOppNotification( 6105): send delay message
V/BtOppService( 6105): start RfcommListener
V/BtOppService( 6105): RfcommListener started
V/BtOppRfcommListener( 6105): Starting RFCOMM listener....
V/BtOppService( 6105): Deleted complete outbound shares, number =  0
V/BluetoothOppProvider( 6105): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
D/BluetoothManagerService( 1032): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
V/BluetoothOppProvider( 6105): starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
,V/BluetoothOppProvider( 6105): created cursor android.database.sqlite.SQLiteCursor@2c71170 on behalf of 
V/BluetoothOppProvider( 6105): created cursor android.database.sqlite.SQLiteCursor@2b2bce9 on behalf of 
W/BluetoothAdapter( 6105): getBluetoothService() called with no BluetoothManagerCallback
V/BtOppService( 6105): Deleted complete inbound failed shares, number = 0
D/LGBluetoothServiceAdapter( 6105): [BTUI] createSocketChannel FD=80 mFd=75
V/BtOppRfcommListener( 6105): Started RFCOMM listener....
I/BtOppRfcommListener( 6105): Accept thread started.
V/BtOppRfcommListener( 6105): Accepting connection...
D/BluetoothAdapterService( 6105): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@26ac4986
V/BluetoothFtpService( 6105): Ftp Service onCreate
I/BluetoothFtpService( 6105): Ftp Service onCreate
V/BluetoothFtpService( 6105): Ftp Service onStartCommand
V/BluetoothOppNotification( 6105): mUpdateCompleteNotification = true
V/BluetoothFtpService( 6105): action: android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothFtpService( 6105): Starting Listening on sockets
V/BluetoothSapReceiver( 6105): [BTUI] checkServiceStart
V/BluetoothSapReceiver( 6105): [BTUI] region:EU country:EU
V/BluetoothSapReceiver( 6105): SapReceiver onReceive 
V/BluetoothSapReceiver( 6105): action = android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothSapReceiver( 6105):  Bluetooth Adapter state = 12
V/BluetoothSapReceiver( 6105): Calling SAP service start service with action = null
V/BluetoothOppProvider( 6105): starting query, database is not null; projection[0] is _id; selection is direction=1 AND status=200 AND visibility=1; selectionArgs is null; sort is _id.
V/BluetoothOppProvider( 6105): created cursor android.database.sqlite.SQLiteCursor@1241bc0f on behalf of 
V/BtOppService( 6105): ContentObserver received notification
V/BtOppService( 6105): ContentObserver received notification
V/BluetoothFtpService( 6105): Handler(): got msg=1
V/BluetoothFtpService( 6105): Ftp Service startRfcommSocketListener
V/BluetoothFtpService( 6105): Ftp Service initSocket
V/BtOppService( 6105): pendingUpdate is true keepUpdateThread is false sListenStarted is true
V/BluetoothOppProvider( 6105): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
V/BluetoothOppProvider( 6105): created cursor android.database.sqlite.SQLiteCursor@fe3d49c on behalf of 
D/BluetoothManagerService( 1032): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
V/BluetoothOppNotification( 6105): update too frequent, put in queue
W/BluetoothAdapter( 6105): getBluetoothService() called with no BluetoothManagerCallback
,V/BtOppService( 6105): pendingUpdate is false keepUpdateThread is false sListenStarted is true
V/BluetoothFtpService( 6105): Succeed to create listening socket on channel 20
V/BluetoothOppProvider( 6105): starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
V/BluetoothFtpService:RfcommSocketAcceptThread( 6105): Run Accept thread
V/BluetoothOppProvider( 6105): created cursor android.database.sqlite.SQLiteCursor@3b713ea5 on behalf of 
V/BluetoothOppNotification( 6105): outbound: succ-0  fail-0
V/BluetoothOppNotification( 6105): outbound notification was removed.
V/BluetoothOppProvider( 6105): starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
D/AuthorizationBluetoothService( 2166): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
V/BluetoothOppProvider( 6105): created cursor android.database.sqlite.SQLiteCursor@28ec227a on behalf of 
V/BluetoothOppNotification( 6105): inbound: succ-0  fail-0
V/BluetoothOppNotification( 6105): inbound notification was removed.
V/BluetoothOppProvider( 6105): starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
V/BluetoothOppProvider( 6105): created cursor android.database.sqlite.SQLiteCursor@3680a2b on behalf of 
D/BluetoothAdapterService( 6105): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@26ac4986
V/BluetoothSapService( 6105): Sap Service onCreate
,V/BluetoothSapService( 6105): action: android.bluetooth.adapter.action.STATE_CHANGED
,V/BluetoothSapService( 6105): state: 12
V/BluetoothSapService( 6105): Starting SAP server process
V/BluetoothSapService( 6105): SAP Service startRfcommListenerThread
V/BluetoothSapService( 6105): Sap Service initRfcommSocket
D/BluetoothManagerService( 1032): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
W/BluetoothAdapter( 6105): getBluetoothService() called with no BluetoothManagerCallback
D/LGBluetoothServiceAdapter( 6105): [BTUI] createSocketChannel FD=82 mFd=80
V/BluetoothSapService( 6105): Succeed to create listening socket 
V/BluetoothSapService( 6105): Accepting socket connection...
W/sapd    ( 6350): type=1400 audit(0.0:159): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
W/sapd    ( 6350): type=1400 audit(0.0:160): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
V/BT_SAP  ( 6350): Event pipe created
V/BT_SAP  ( 6350): create_server_socket qcom.sap.server
V/BT_SAP  ( 6350): created socket fd 6
,I/wpa_supplicant( 6130): wlan0: CTRL-EVENT-SCAN-STARTED 
D/WifiMonitor( 1032): Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1032): WifiMonitor:wlan0 cnt=13 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1032): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1032): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
,V/BluetoothOppNotification( 6105): new notify threadi!
,V/BluetoothOppNotification( 6105): send delay message
V/BluetoothOppProvider( 6105): starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
V/BluetoothOppProvider( 6105): created cursor android.database.sqlite.SQLiteCursor@245b1e07 on behalf of 
V/BluetoothOppNotification( 6105): mUpdateCompleteNotification = true
V/BluetoothOppProvider( 6105): starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
V/BluetoothOppProvider( 6105): created cursor android.database.sqlite.SQLiteCursor@3e5c1b34 on behalf of 
V/BluetoothOppNotification( 6105): outbound: succ-0  fail-0
V/BluetoothOppNotification( 6105): outbound notification was removed.
V/BluetoothOppProvider( 6105): starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
V/BluetoothOppProvider( 6105): created cursor android.database.sqlite.SQLiteCursor@1bb99d5d on behalf of 
V/BluetoothOppNotification( 6105): inbound: succ-0  fail-0
V/BluetoothOppNotification( 6105): inbound notification was removed.
V/BluetoothOppProvider( 6105): starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
V/BluetoothOppProvider( 6105): created cursor android.database.sqlite.SQLiteCursor@2ee886d2 on behalf of 
E/wpa_supplicant( 6130): USIM:  scard_init function
I/wpa_supplicant( 6130): Trying to associate with SSID 'NG700'
,E/WifiMonitor( 1032): WifiMonitor:wlan0 cnt=14 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
E/WifiMonitor( 1032): handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
D/WifiMonitor( 1032): Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
E/WifiMonitor( 1032): WifiMonitor:wlan0 cnt=15 dispatchEvent: WPS-AP-AVAILABLE 
W/WifiMonitor( 1032): couldn't identify event type - WPS-AP-AVAILABLE 
D/WifiMonitor( 1032): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
E/WifiMonitor( 1032): WifiMonitor:wlan0 cnt=16 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
E/WifiStateMachine( 1032):  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=1 known=0 got=1 bcn=0
E/WifiStateMachine( 1032):  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=1 known=0 got=1 bcn=0
E/WifiStateMachine( 1032):  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=1 known=0 got=1 bcn=0
D/sensors_hal_Time( 1032): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1032): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1032): tsOffsetIs: Apps: 117830250063; DSPS: 4001651; Offset : -4305009223
E/WifiStateMachine( 1032):  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=1 known=0 got=1 bcn=0
I/WifiNative-HAL( 1032): startHal
E/wifi    ( 1032): getStaticLongField sWifiHalHandle 0x989628cc
E/WifiHAL ( 1032): Could not connect handle
D/wifi    ( 1032): halHandle = 0x0, mVM = 0xb487c280, mCls = 0x8021b6
I/WifiNative-HAL( 1032): Could not start hal
D/WifiNative-wlan0( 1032): doString: [BSS RANGE=0- MASK=0x21987]
E/WifiStateMachine( 1032):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 16 0 rt=117833  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
,W/Settings( 1032): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1032): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1032): NETWORK_STATE_CHANGED_ACTION [SCANNING]
,I/StatusBar.NetworkController( 1452): networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1452): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1452): refreshViews: Data not connected!! Set no data type icon / Roaming
,I/StatusBar.NetworkController( 1452): networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1452): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1452): refreshViews: Data not connected!! Set no data type icon / Roaming
W/Settings( 1032): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1032): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1032): NETWORK_STATE_CHANGED_ACTION [CONNECTING]
E/WifiStateMachine( 1032):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 16 0 rt=117868  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
D/WifiServerServiceExt( 1032): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1032): setSupplicantStateASSOCIATING
D/PostponalbeReceiver( 5124): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,V/WiFiOffLoadBroadcast( 6193): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6193): MCCMNC not supported: null
D/QRemote ( 5964): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,D/QRemote ( 5964): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 5964): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
D/PostponalbeReceiver( 5124): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
V/WiFiOffLoadBroadcast( 6193): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6193): MCCMNC not supported: null
D/QRemote ( 5964): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 5964): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 5964): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,I/jxcore-log( 6048): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMultiplex.js
I/jxcore-log( 6048): 
,I/wpa_supplicant( 6130): wlan0: CTRL-EVENT-ASSOC-REJECT bssid=c0:ff:d4:d3:aa:48 status_code=1
,D/WifiMonitor( 1032): Event [IFNAME=wlan0 CTRL-EVENT-ASSOC-REJECT bssid=c0:ff:d4:d3:aa:48 status_code=1]
E/WifiMonitor( 1032): WifiMonitor:wlan0 cnt=17 dispatchEvent: CTRL-EVENT-ASSOC-REJECT bssid=c0:ff:d4:d3:aa:48 status_code=1
D/WifiMonitor( 1032): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=00:00:00:00:00:00 SSID=NG700]
E/WifiMonitor( 1032): WifiMonitor:wlan0 cnt=18 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=00:00:00:00:00:00 SSID=NG700
E/WifiStateMachine( 1032):  DisconnectedState ASSOCIATION_REJECTION_EVENT 17 1 c0:ff:d4:d3:aa:48 blacklist=false rt=119841
E/WifiStateMachine( 1032):  ConnectModeState ASSOCIATION_REJECTION_EVENT 17 1 c0:ff:d4:d3:aa:48 blacklist=false rt=119842
E/WifiStateMachine( 1032):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 18 0 rt=119842  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: DISCONNECTED
D/WifiHS20( 1032): hidePasspointNotification off =false
,I/StatusBar.NetworkController( 1452): networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1452): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1452): refreshViews: Data not connected!! Set no data type icon / Roaming
W/Settings( 1032): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1032): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1032): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
E/WifiStateMachine( 1032):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 18 0 rt=119860  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: DISCONNECTED
,D/WifiServerServiceExt( 1032): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1032): setSupplicantStateDISCONNECTED
,D/PostponalbeReceiver( 5124): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,I/wpa_supplicant( 6130): wlan0: CTRL-EVENT-SCAN-STARTED 
,D/WifiMonitor( 1032): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
E/WifiMonitor( 1032): WifiMonitor:wlan0 cnt=19 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
D/WifiMonitor( 1032): Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1032): WifiMonitor:wlan0 cnt=20 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1032): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1032): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
E/WifiStateMachine( 1032):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 19 0 rt=119941  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
D/WifiHS20( 1032): hidePasspointNotification off =false
E/WifiStateMachine( 1032):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 19 0 rt=119966  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
,W/Settings( 1032): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1032): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1032): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
I/StatusBar.NetworkController( 1452): networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1452): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1452): refreshViews: Data not connected!! Set no data type icon / Roaming
,W/Settings( 1032): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1032): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1032): NETWORK_STATE_CHANGED_ACTION [SCANNING]
D/WifiServerServiceExt( 1032): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1032): setSupplicantStateSCANNING
I/StatusBar.NetworkController( 1452): networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1452): mWifiConnected = false, mWifiLevel = 0
I/PCSuite ( 6171): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 6171): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 6171): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,D/StatusBar.NetworkController( 1452): refreshViews: Data not connected!! Set no data type icon / Roaming
V/WiFiOffLoadBroadcast( 6193): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6193): MCCMNC not supported: null
D/QRemote ( 5964): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,D/QRemote ( 5964): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 5964): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
D/PostponalbeReceiver( 5124): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
I/PCSuite ( 6171): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 6171): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 6171): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,V/WiFiOffLoadBroadcast( 6193): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 6193): MCCMNC not supported: null
,D/QRemote ( 5964): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 5964): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 5964): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
D/PostponalbeReceiver( 5124): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,V/WiFiOffLoadBroadcast( 6193): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 6193): MCCMNC not supported: null
D/QRemote ( 5964): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,D/QRemote ( 5964): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 5964): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
I/jxcore-log( 6048): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
I/jxcore-log( 6048): 
,I/jxcore-log( 6048): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
I/jxcore-log( 6048): 
,I/jxcore-log( 6048): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliCryptoManager.js
I/jxcore-log( 6048): 
,I/jxcore-log( 6048): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliEmitter.js
I/jxcore-log( 6048): 
,I/jxcore-log( 6048): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNativeLayer.js
I/jxcore-log( 6048): 
,I/jxcore-log( 6048): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js
I/jxcore-log( 6048): 
I/jxcore-log( 6048): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationManager.js
I/jxcore-log( 6048): 
,I/jxcore-log( 6048): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
I/jxcore-log( 6048): 
,I/wpa_supplicant( 6130): Trying to associate with SSID 'NG700'
,E/WifiMonitor( 1032): WifiMonitor:wlan0 cnt=21 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
E/WifiMonitor( 1032): handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
D/WifiMonitor( 1032): Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
E/WifiMonitor( 1032): WifiMonitor:wlan0 cnt=22 dispatchEvent: WPS-AP-AVAILABLE 
W/WifiMonitor( 1032): couldn't identify event type - WPS-AP-AVAILABLE 
D/WifiMonitor( 1032): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
E/WifiMonitor( 1032): WifiMonitor:wlan0 cnt=23 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
E/WifiStateMachine( 1032):  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=4 known=0 got=4 bcn=0
E/WifiStateMachine( 1032):  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=4 known=0 got=4 bcn=0
E/WifiStateMachine( 1032):  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=4 known=0 got=4 bcn=0
E/WifiStateMachine( 1032):  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=4 known=0 got=4 bcn=0
D/WifiNative-wlan0( 1032): doString: [BSS RANGE=0- MASK=0x21987]
E/WifiStateMachine( 1032):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 23 0 rt=122050  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
W/Settings( 1032): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1032): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1032): NETWORK_STATE_CHANGED_ACTION [SCANNING]
,I/StatusBar.NetworkController( 1452): networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1452): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1452): refreshViews: Data not connected!! Set no data type icon / Roaming
E/WifiStateMachine( 1032):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 23 0 rt=122074  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
,D/PostponalbeReceiver( 5124): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,W/Settings( 1032): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1032): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1032): NETWORK_STATE_CHANGED_ACTION [CONNECTING]
,I/StatusBar.NetworkController( 1452): networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1452): mWifiConnected = false, mWifiLevel = 0
D/WifiServerServiceExt( 1032): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1032): setSupplicantStateASSOCIATING
D/StatusBar.NetworkController( 1452): refreshViews: Data not connected!! Set no data type icon / Roaming
,I/wpa_supplicant( 6130): wlan0: Associated with c0:ff:d4:d3:aa:48
D/WifiMonitor( 1032): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
E/WifiMonitor( 1032): WifiMonitor:wlan0 cnt=24 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
D/WifiMonitor( 1032): Event [IFNAME=wlan0 Associated with c0:ff:d4:d3:aa:48]
E/WifiMonitor( 1032): WifiMonitor:wlan0 cnt=25 dispatchEvent: Associated with c0:ff:d4:d3:aa:48
D/WifiMonitor( 1032): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1032): WifiMonitor:wlan0 cnt=26 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
E/WifiStateMachine( 1032):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 24 0 rt=122162  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
E/WifiStateMachine( 1032):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 24 0 rt=122164  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
D/Tethering( 1032): sendTetherStateChangedBroadcast 1, 0, 0
E/WifiStateMachine( 1032):  DisconnectedState CMD_ASSOCIATED_BSSID 25 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=122177
E/WifiStateMachine( 1032):  ConnectModeState CMD_ASSOCIATED_BSSID 25 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=122178
E/WifiStateMachine( 1032):  DriverStartedState CMD_ASSOCIATED_BSSID 25 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=122178
E/WifiStateMachine( 1032):  SupplicantStartedState CMD_ASSOCIATED_BSSID 25 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=122178
D/libc-netbsd(  311): default dns: query_ipv6=0, query_ipv4=0
E/WifiStateMachine( 1032):  DefaultState CMD_ASSOCIATED_BSSID 25 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=122179
E/WifiStateMachine( 1032):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 26 0 rt=122179  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: FOUR_WAY_HANDSHAKE
,W/Settings( 1032): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1032): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1032): NETWORK_STATE_CHANGED_ACTION [CONNECTING]
I/wpa_supplicant( 6130): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 6130): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
I/StatusBar.NetworkController( 1452): networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1452): mWifiConnected = false, mWifiLevel = 0
D/WifiMonitor( 1032): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1032): WifiMonitor:wlan0 cnt=27 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/WifiMonitor( 1032): Event [IFNAME=wlan0 WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]]
E/WifiMonitor( 1032): WifiMonitor:wlan0 cnt=28 dispatchEvent: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
W/WifiMonitor( 1032): couldn't identify event type - WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
D/WifiMonitor( 1032): Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]]
E/WifiMonitor( 1032): WifiMonitor:wlan0 cnt=29 dispatchEvent: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
E/WifiMonitor( 1032): handleEvent 1  Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
D/WifiMonitor( 1032): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1032): WifiMonitor:wlan0 cnt=30 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/DSQN    ( 1032): DNSproblemNotiEnabled is disabled ignore DNS fail CB
D/StatusBar.NetworkController( 1452): refreshViews: Data not connected!! Set no data type icon / Roaming
W/Settings( 1032): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1032): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1032): NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
E/WifiStateMachine( 1032):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 26 0 rt=122187  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: FOUR_WAY_HANDSHAKE
D/WifiServerServiceExt( 1032): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1032): setSupplicantStateASSOCIATED
I/StatusBar.NetworkController( 1452): networkInfo=[type: WIFI[], state: CONNECTING/AUTHENTICATING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1452): mWifiConnected = false, mWifiLevel = 0
E/WifiStateMachine( 1032):  DisconnectedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1032):  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1032):  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1032):  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
D/StatusBar.NetworkController( 1452): refreshViews: Data not connected!! Set no data type icon / Roaming
E/WifiStateMachine( 1032):  DefaultState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1032):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 27 0 rt=122189  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: GROUP_HANDSHAKE
E/WifiStateMachine( 1032):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 27 0 rt=122189  SSID: NG700 BSS,ID: c0:ff:d4:d3:aa:48 nid: 0 state: GROUP_HANDSHAKE
E/WifiStateMachine( 1032):  DisconnectedState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=122190
E/WifiStateMachine( 1032):  ConnectModeState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=122190
D/WifiNative-wlan0( 1032): doString: [STATUS]
D/WifiMonitor( 1032): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1032): WifiMonitor:wlan0 cnt=31 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/WifiNative-wlan0( 1032):    returned bssid=c0:ff:d4:d3:aa:48 ssid=NG700 id=0 mode=station pairwise_cipher=CCMP group_cipher=CCMP key_mgmt=WPA2-PSK wpa_state=COMPLETED p2p_device_address=02:9a:02:7b:60:ac address=c4:9a:02:7b:60:ac uuid=530d3fd0-1ba3-5409-a336-ff4e42af59a2
I/WifiServiceExtension( 1032): setVHTCapabilityType  : false
V/WiFiOffLoadBroadcast( 6193): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6193): MCCMNC not supported: null
I/WifiServerServiceExt( 1032): wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
I/WifiServerServiceExt( 1032): setKeepAlivePacketInterval msec : 60
,W/Settings( 1032): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1032): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1032): NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
W/Settings( 1032): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1032): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1032): NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
I/StatusBar.NetworkController( 1452): networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1452): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1452): refreshViews: Data not connected!! Set no data type icon / Roaming
,I/StatusBar.NetworkController( 1452): networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/StatusBar.NetworkController( 1452): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1452): refreshViews: Data not connected!! Set no data type icon / Roaming
D/QRemote ( 5964): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 5964): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 5964): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
D/ConnectivityService( 1032): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
D/ConnectivityService( 1032): Got NetworkAgent Messenger
D/ConnectivityService( 1032): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,D/ConnectivityService( 1032): NetworkAgent connected
E/WifiConfigStore( 1032): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/WifiNative-wlan0( 1032): doBoolean: SET_NETWORK 0 bssid any
D/WifiNative-wlan0( 1032): SET_NETWORK 0 bssid any: returned true
,D/WifiNative-wlan0( 1032): doBoolean: SAVE_CONFIG
D/PostponalbeReceiver( 5124): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
V/WiFiOffLoadBroadcast( 6193): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6193): MCCMNC not supported: null
D/QRemote ( 5964): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 5964): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 5964): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,D/UsbSettingsReceiver( 6193): [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
D/UsbSettingsReceiver( 6193): [AUTORUN] sys.usb.config = ptp_only,adb
D/UsbSettingsReceiver( 6193): [AUTORUN] sys.usb.state = ptp_only,adb
D/UsbSettingsReceiver( 6193): [AUTORUN] persist.sys.usb.config = ptp_only,adb
D/UsbSettingsReceiver( 6193): [AUTORUN] onReceive() : app userid = 0, current userid = 0
D/UsbSettingsControl( 6193): [AUTORUN] getUsbConnected() : connected=true
D/UsbSettingsReceiver( 6193): [AUTORUN] onReceive() : availableList=[wlan0]
D/UsbSettingsReceiver( 6193): [AUTORUN] onReceive() : activeList=[]
D/UsbSettingsReceiver( 6193): [AUTORUN] onReceive() : errorList=[]
D/UsbSettingsControl( 6193): [AUTORUN] isAutorunTimer() : mAutorunChanging=false
D/UsbSettingsReceiver( 6193): [AUTORUN] onReceive() : TetherState Changed=wlan0
D/UsbSettingsControl( 6193): [AUTORUN] setTetherStatus() : status=false
D/PostponalbeReceiver( 5124): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
V/WiFiOffLoadBroadcast( 6193): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WifiNative-wlan0( 1032): SAVE_CONFIG: returned true
E/WifiConfigStore( 1032): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/WifiNative-wlan0( 1032): doBoolean: SET_NETWORK 0 bssid any
D/WifiNative-wlan0( 1032): SET_NETWORK 0 bssid any: returned true
D/WifiNative-wlan0( 1032): doBoolean: SAVE_CONFIG
D/WiFiOffLoadBroadcast( 6193): MCCMNC not supported: null
D/QRemote ( 5964): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 5964): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 5964): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,D/PostponalbeReceiver( 5124): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
D/WifiNative-wlan0( 1032): SAVE_CONFIG: returned true
D/CommandListener(  311): Setting iface cfg
E/WifiStateMachine( 1032): Start Dhcp Watchdog 1
E/WifiStateMachine( 1032):  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 30 0 rt=122288  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine( 1032):  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 30 0 rt=122288  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine( 1032):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 30 0 rt=122288  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
D/DhcpStateMachine( 1032): StoppedState
D/WifiServerServiceExt( 1032): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1032): setSupplicantStateFOUR_WAY_HANDSHAKE
D/DhcpStateMachine( 1032): StoppedState{ when=-2ms what=196609 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine( 1032): WaitBeforeStartState
D/WifiServerServiceExt( 1032): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1032): setSupplicantStateGROUP_HANDSHAKE
E/WifiStateMachine( 1032):  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 31 0 rt=122290  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine( 1032):  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 31 0 rt=122290  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
,E/WifiStateMachine( 1032):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 31 0 rt=122291  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine( 1032):  ObtainingIpState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:-1279009179] from screen [on:0 period:-1279009179]
E/WifiStateMachine( 1032):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-1279009178]
D/WifiNative-wlan0( 1032): doString: [SIGNAL_POLL]
V/WiFiOffLoadBroadcast( 6193): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/StatusBar.NetworkController( 1452): refreshViews: Data not connected!! Set no data type icon / Roaming
D/WiFiOffLoadBroadcast( 6193): MCCMNC not supported: null
D/ConnectivityService( 1032): updateNetworkScore for NetworkAgentInfo [WIFI () - 100] to 60
E/WifiStateMachine( 1032):  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1032):  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1032):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1032):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1032):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
,E/WifiStateMachine( 1032):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
D/ConnectivityService( 1032): Update of LinkProperties for NetworkAgentInfo [WIFI () - 100]; created=false
D/WifiServerServiceExt( 1032): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1032): setSupplicantStateCOMPLETED
E/WifiStateMachine( 1032):  ObtainingIpState CMD_PRE_DHCP_ACTION 0 0 txpkts=1,0,0
D/QRemote ( 5964): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
E/WifiStateMachine( 1032):  L2ConnectedState CMD_PRE_DHCP_ACTION 0 0 txpkts=1,0,0
D/WifiNative-wlan0( 1032): doBoolean: DRIVER SETSUSPENDMODE 0
D/QRemote ( 5964): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 5964): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
D/PostponalbeReceiver( 5124): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
V/WiFiOffLoadBroadcast( 6193): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6193): MCCMNC not supported: null
,D/QRemote ( 5964): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 5964): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 5964): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
D/PostponalbeReceiver( 5124): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,I/wpa_supplicant( 6130): wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 0
D/WifiNative-wlan0( 1032): DRIVER SETSUSPENDMODE 0: returned true
D/WifiNative-wlan0( 1032): doBoolean: SET ps 0
D/WifiNative-wlan0( 1032): SET ps 0: returned true
D/WifiNative-wlan0( 1032): doBoolean: DRIVER BTCOEXMODE 1
I/wpa_supplicant( 6130): wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 1
D/WifiNative-wlan0( 1032): DRIVER BTCOEXMODE 1: returned true
E/WifiStateMachine( 1032): CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
D/LGWifiP2pService( 1032): InactiveState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@4dafeaa target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1032): P2pEnabledState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@4dafeaa target=com.android.internal.util.StateMachine$SmHandler }
V/DhcpStateMachine( 1032): Current State is mWaitBeforeStartState.
D/DhcpStateMachine( 1032): WaitBeforeStartState{ when=0 what=196615 target=com.android.internal.util.StateMachine$SmHandler }
V/LgDhcpStateMachineHelper( 1032): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
V/LgDhcpStateMachineHelper( 1032): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700" is not exist.
D/DhcpStateMachine( 1032): DHCP Start wake lock is acquired.
V/WiFiOffLoadBroadcast( 6193): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WifiServerServiceExt( 1032): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1032): setSupplicantStateCOMPLETED
,D/WiFiOffLoadBroadcast( 6193): MCCMNC not supported: null
,D/QRemote ( 5964): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 5964): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 5964): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
D/DhcpStateMachine( 1032): DHCPV4 request on wlan0
,V/LgDhcpStateMachineHelper( 1032): [bssid] hash key :c0:ff:d4:d3:aa:48
D/LgDhcpStateMachineHelper( 1032): dhcp.ap.macaddress = c0:ff:d4:d3:aa:48
W/dhcpcd  ( 6445): type=1400 audit(0.0:161): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,W/dhcpcd  ( 6445): type=1400 audit(0.0:162): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,I/dhcpcd  ( 6445): version 5.5.6 starting
E/dhcpcd  ( 6445): get_duid: m
D/dhcpcd  ( 6445): wlan0: using ClientID 01:c4:9a:02:7b:60:ac
D/dhcpcd  ( 6445): wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason PREINIT
,D/dhcpcd  ( 6445): getUsingAPMacAddress: c0:ff:d4:d3:aa:48 , return 1
D/dhcpcd  ( 6445): [read_lease] unlink /data/misc/dhcp/dhcpcd-wlan0.lease, link /data/misc/dhcp/dhcpcd-wlan0-c0:ff:d4:d3:aa:48.lease2
D/dhcpcd  ( 6445): wlan0: reading lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
,I/dhcpcd  ( 6445): wlan0: rebinding lease of 192.168.1.141
D/dhcpcd  ( 6445): wlan0: sending REQUEST (xid 0x43bf7682), next in 3.13 seconds
E/WifiStateMachine( 1032):  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1032):  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1032):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1032):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1032):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1032):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
,D/ConnectivityService( 1032): Update of LinkProperties for NetworkAgentInfo [WIFI () - 100]; created=false
I/dhcpcd  ( 6445): wlan0: acknowledged 192.168.1.141 from 192.168.1.1
,I/dhcpcd  ( 6445): wlan0: leased 192.168.1.141 for 86400 seconds
D/dhcpcd  ( 6445): wlan0: adding IP address 192.168.1.141/24
D/dhcpcd  ( 6445): wlan0: adding route to 192.168.1.0/24
D/dhcpcd  ( 6445): wlan0: adding default route via 192.168.1.1
D/dhcpcd  ( 6445): wlan0: writing lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
D/dhcpcd  ( 6445): getUsingAPMacAddress: c0:ff:d4:d3:aa:48 , return 1
D/dhcpcd  ( 6445): write_lease_ext: /data/misc/dhcp/dhcpcd-wlan0-c0:ff:d4:d3:aa:48.lease2
D/dhcpcd  ( 6445): wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason REBOOT
,E/WifiStateMachine( 1032):  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1032):  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1032):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1032):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1032):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1032):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
D/ConnectivityService( 1032): Update of LinkProperties for NetworkAgentInfo [WIFI () - 100]; created=false
,D/DhcpStateMachine( 1032): DHCPV4 succeeded on wlan0
,D/LgDhcpStateMachineHelper( 1032): CheckDhcpDirectory [Lease File Count] : 3
V/LgDhcpStateMachineHelper( 1032): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
D/LgDhcpStateMachineHelper( 1032): checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.141
V/LgDhcpStateMachineHelper( 1032): Add DhcpResults: IP address 192.168.1.141/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 86400 seconds
V/DhcpStateMachine( 1032): Current State is mWaitBeforeStartState.
V/LgDhcpStateMachineHelper( 1032): bShouldSendDhcpAction Result: true
E/WifiStateMachine( 1032):  ObtainingIpState CMD_POST_DHCP_ACTION 1 0 OK  v4
E/WifiStateMachine( 1032):  L2ConnectedState CMD_POST_DHCP_ACTION 1 0 OK  v4
D/WifiNative-wlan0( 1032): doBoolean: DRIVER BTCOEXMODE 2
D/DhcpStateMachine( 1032): DHCP Start/Renew wake lock is released.
I/wpa_supplicant( 6130): wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
D/LGWifiP2pService( 1032): InactiveState{ when=-2ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1032): P2pEnabledState{ when=-2ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0( 1032): DRIVER BTCOEXMODE 2: returned true
D/WifiNative-wlan0( 1032): doBoolean: DRIVER SETSUSPENDMODE 1
I/wpa_supplicant( 6130): wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 1
D/WifiNative-wlan0( 1032): DRIVER SETSUSPENDMODE 1: returned true
D/WifiNative-wlan0( 1032): doBoolean: SET ps 1
D/DhcpStateMachine( 1032): RunningState
D/WifiNative-wlan0( 1032): SET ps 1: returned true
D/ConnectivityService( 1032): Update of LinkProperties for NetworkAgentInfo [WIFI () - 100]; created=false
E/WifiStateMachine( 1032):  ObtainingIpState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
E/WifiStateMachine( 1032):  L2ConnectedState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
E/WifiStateMachine( 1032): WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
D/ConnectivityService( 1032): ignoring duplicate network state non-change
,W/Settings( 1032): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1032): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1032): NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
,D/ConnectivityService( 1032): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
I/StatusBar.NetworkController( 1452): networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1452): mWifiConnected = false, mWifiLevel = 0
D/ConnectivityService( 1032): Adding iface wlan0 to network 100
E/WifiStateMachine( 1032): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,D/StatusBar.NetworkController( 1452): refreshViews: Data not connected!! Set no data type icon / Roaming
I/StatusBar.NetworkController( 1452): networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1452): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1452): refreshViews: Data not connected!! Set no data type icon / Roaming
,E/ConnectivityService( 1032): Unexpected mtu value: 0, wlan0
D/ConnectivityService( 1032): Adding Route [fe80::/64 -> :: wlan0] to network 100
D/ConnectivityService( 1032): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 100
V/WfdStateTracker( 1942): handleWifiStateChangedEvent: 1
D/ConnectivityService( 1032): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 100
D/ConnectivityService( 1032): addLocalRoutetoDefaultNetwork
I/StatusBar.NetworkController( 1452): networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService( 1032): defaultNAI is null or Wi-Fi no need to add Loacal route to default network. WiFi netid = 100
D/ConnectivityService( 1032): Setting Dns servers for network 100 to [/192.168.1.1]
W/Settings( 1032): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1032): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1032): NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
D/WifiHS20( 1032): [PASSPOINT] passpointNotification: hs20AP list is checked
,I/StatusBar.NetworkController( 1452): mWifiConnected = true, mWifiLevel = 2
D/StatusBar.NetworkController( 1452): refreshViews: Data not connected!! Set no data type icon / Roaming
W/Settings( 1032): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1032): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1032): NETWORK_STATE_CHANGED_ACTION [CONNECTED]
D/WifiHS20( 1032): [PASSPOINT] passpointNotification: hs20AP list is checked
D/PostponalbeReceiver( 5124): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
W/Settings( 1032): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1032): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1032): NETWORK_STATE_CHANGED_ACTION [CONNECTED]
D/Nat464Xlat( 1032): requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
D/ConnectivityService( 1032): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService( 1032): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService( 1032): rematching NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService( 1032):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService( 1032):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1032):     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
,D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1032): DefaultState{ when=-2ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1032): Connected
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1032): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1032): Checking http://clients3.google.com/generate_204 on "NG700"
D/ConnectivityService( 1032):   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1032):     satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:true
D/ConnectivityService( 1032): currentScore = 0, newScore = 20
D/ConnectivityService( 1032):    accepting network in place of null
D/ConnectivityService( 1032): sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    ( 1032): new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    ( 1032):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
I/StatusBar.NetworkController( 1452): networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1452): mWifiConnected = true, mWifiLevel = 2
D/StatusBar.NetworkController( 1452): refreshViews: Data not connected!! Set no data type icon / Roaming
D/ConnectivityService( 1032): Setting tx/rx TCP buffers to 524288,1048576,2097152,262144,524288,1048576
D/TelephonyNetworkFactory-1( 1852): new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/TelephonyNetworkFactory-1( 1852):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
E/ConnectivityService( 1032): [lg_data] Adding agent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::c69a:2ff:fe7b:60ac/64,192.168.1.141/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
D/CSLegacyTypeTracker( 1032): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
D/ConnectivityService( 1032): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/libc-netbsd(  311): res_queryN name = clients3.google.com, class = 1, type = 28
,D/libc-netbsd(  311): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  311): res_queryN name = 2.android.pool.ntp.org, class = 1, type = 1
D/libc-netbsd(  311): res_queryN name = 2.android.pool.ntp.org., class = 1, type = 1
D/LocSvc_java( 1032): Sending msg: 4 arg1:1 arg2:1
D/LocSvc_java( 1032): getAGpsConnectionInfo connType - 4
D/DSQN    ( 1032): DNSproblemNotiEnabled is disabled ignore DNS fail CB
D/LocSvc_java( 1032): updateNetworkState connTyp: 4 available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java( 1032): ignore wifi update if we are not in OPENING or CLOSING
D/LocSvc_java( 1032): Sending msg: 5 arg1:0 arg2:1
D/ConnectivityService( 1032): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/CSLegacyTypeTracker( 1032): [e] list.add(nai) empty : false size: 1
D/ConnectivityService( 1032): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::c69a:2ff:fe7b:60ac/64,192.168.1.141/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
,D/ConnectivityService( 1032): validation of new default Network = false
D/ConnectivityService( 1032): Default network via Wi-Fi connected. start DSQN
D/DSQN    ( 1032): enableDataServiceNotify 
D/DSQN    ( 1032): start dsqn bin
D/libc-netbsd(  311): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  311): res_queryN name = europe.pool.ntp.org, class = 1, type = 1
D/libc-netbsd(  311): res_queryN name = europe.pool.ntp.org., class = 1, type = 1
D/DSQN    ( 1032): DNSproblemNotiEnabled is disabled ignore DNS fail CB
D/LocSvc_java( 1032): requestTime failed
D/LocSvc_java( 1032): Sending msg: 10 arg1:0 arg2:1
V/NetworkPolicy( 1032): [LG_RESTRICTED] checkMobilePolicy_type()
D/ConnectivityService( 1032): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService( 1032):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1032):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1032): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityManager.CallbackHandler( 1452): CM callback handler got msg 524290
W/dsqn    ( 6505): type=1400 audit(0.0:163): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
W/dsqn    ( 6505): type=1400 audit(0.0:164): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,V/WiFiOffLoadBroadcast( 6193): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/TelephonyIcons( 1452): null signal icon name: drawable/stat_sys_signal_null
D/StatusBar.NetworkController( 1452): refreshViews: Data not connected!! Set no data type icon / Roaming
D/StatusBar.NetworkController( 1452): refreshViews: Data not connected!! Set no data type icon / Roaming
D/libc-netbsd(  311): res_queryN name = clients3.google.com, class = 1, type = 1
E/DSQN    ( 6505): DSQN ssw
,D/WiFiOffLoadBroadcast( 6193): MCCMNC not supported: null
D/QRemote ( 5964): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 5964): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 5964): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
D/PostponalbeReceiver( 5124): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,V/WiFiOffLoadBroadcast( 6193): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 6193): MCCMNC not supported: null
D/libc-netbsd(  311): res_queryN name = clients3.google.com succeed
,D/QRemote ( 5964): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 5964): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 5964): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
D/PostponalbeReceiver( 5124): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
I/PCSuite ( 6171): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
,D/PCSuite ( 6171): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
D/LGDataListener(  311): argv[0]=dsqncommand
D/LGDataListener(  311): argv[1]=wlan0
D/LGDataListener(  311): argv[2]=1
D/LGDataListener(  311): notifyDSQN DSQN STARTMONITOR wlan0 1
D/DSQN    ( 1032): DSQM DsqnNotification wlan0  1
D/DSQN    ( 1032): start to monitor internet connection
V/WiFiOffLoadBroadcast( 6193): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 6193): MCCMNC not supported: null
D/QRemote ( 5964): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 5964): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
D/QRemote ( 5964): [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
I/QRemote ( 5964): [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
I/QRemote ( 5964): [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
,D/PostponalbeReceiver( 5124): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
I/PCSuite ( 6171): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
D/PCSuite ( 6171): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 6193): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6193): MCCMNC not supported: null
D/QRemote ( 5964): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 5964): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
D/QRemote ( 5964): [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
I/QRemote ( 5964): [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
I/QRemote ( 5964): [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1032): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Fri, 05 Feb 2016 23:28:26 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1454714906851], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1454714906821]}
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1032): Don't send network conditions - lacking user consent.
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1032): Validated
D/ConnectivityService( 1032): Validated NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService( 1032): rematching NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService( 1032):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService( 1032):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1032):     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
D/ConnectivityService( 1032): Network NetworkAgentInfo [WIFI () - 100] was already satisfying request 1. No change.
D/ConnectivityService( 1032): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService( 1032):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1032):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1032): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1032): sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityManager.CallbackHandler( 1452): CM callback handler got msg 524290
D/ConnectivityService( 1032): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
D/WIFI    ( 1032): new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    ( 1032):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/TelephonyNetworkFactory-1( 1852): new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/TelephonyNetworkFactory-1( 1852):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
,D/TelephonyIcons( 1452): null signal icon name: drawable/stat_sys_signal_null
D/StatusBar.NetworkController( 1452): refreshViews: Data not connected!! Set no data type icon / Roaming
D/StatusBar.NetworkController( 1452): refreshViews: Data not connected!! Set no data type icon / Roaming
W/ProcessCpuTracker( 1032): Skipping unknown process pid 6500
W/ProcessCpuTracker( 1032): Skipping unknown process pid 6503
,E/WifiStateMachine( 1032):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-61 f=2412 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1279006172] gl rssi=-61 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1032):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-61 f=2412 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:0] from screen [on:0 period:-1279006172] gl rssi=-61 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1032): doString: [SIGNAL_POLL]
D/StatusBar.NetworkController( 1452): refreshViews: Data not connected!! Set no data type icon / Roaming
V/WifiInternetCheck( 1032): Single check msg out of sync, ignoring.
,D/ConnectivityService( 1032): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering( 1032): MasterInitialState.processMessage what=3,
D/libc-netbsd(  311): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  311): res_queryN name = 2.android.pool.ntp.org, class = 1, type = 1
,D/GpsLocationProvider( 1032): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
D/PostponalbeReceiver( 5124): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
W/ContextImpl( 5124): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
,I/NetworkMonitor( 5172): type=WIFI subType= reason=null isConnected=true
,D/libc-netbsd(  311): res_queryN name = 2.android.pool.ntp.org succeed
I/ActivityManager( 1032): Start proc com.google.android.apps.books for service com.google.android.apps.books/.service.SyncService: pid=6521 uid=10054 gids={50054, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/AlarmManagerService( 1032): Setting time of day to sec=1454714909
W/AlarmManagerService( 1032): Unable to set rtc to 1454714909: Invalid argument
,I/ActivityManager( 1032): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=6550 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
I/ActivityManager( 1032): Start proc com.android.gallery3d for service com.android.gallery3d/com.lge.gallery.picasa.PicasaService: pid=6569 uid=10027 gids={50027, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
,I/SecureClockService( 1942): Intent.ACTION_TIME_CHANGED 
D/KeyguardUpdateMonitor( 1452): handleTimeUpdate
I/[SystemUI]Clock( 1452): onReceive = android.intent.action.TIME_SET
W/ActivityManager( 1032): getTasks: caller 10029 is using old GET_TASKS but privileged; allowing
,D/LIA_Informant_Tips_DateChangeManager( 2702): onReceive() : ACTION_TIME_CHANGED
I/LgeClockWidgetControlView( 1452): time changed, timezoneChanged : false
I/LIA_Informant_Tips_LogTracer( 2702): [Log Tracer - Schedule Transition] Time Change Event Received : 2016-02-06 00:28:29...... Request
I/LIA_Informant_Tips_LogTracer( 2702): [Log Tracer - Schedule Transition] UserGuide, DATE_UPDATE : working count : 3, total count : 167, new day : false...... Request
D/LIA_Informant_Tips_DateChangeManager( 2702): DateInfo : SmartTips Total Working Day Count = 167
D/LIA_Informant_Tips_DateChangeManager( 2702): DateInfo : UserGuide Working Duration Count = 3
D/LIA_Informant_Tips_DateChangeManager( 2702): DateInfo : Last Date Check Time = 2016-02-06 00:28:29
I/[LGHome]LGDateChangeReceiver( 2069): [LGDateChangeReceiver.java:78:updateCalendarShortcut()]date=6 currentDate=-1 dayofweek=7 currentDayOfWeek=-1
I/[LGHome]LGCalendarIcon( 2069): [LGCalendarIcon.java:214:makeCalendarBitmap()]Locale = en_US dayofweek= Sat date= 6
I/[LGHome]LGCalendarIcon( 2069): [LGCalendarIcon.java:214:makeCalendarBitmap()]Locale = en_US dayofweek= Sat date= 6
I/[LGHome]Launcher( 2069): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,D/[Concierge]Service( 2593): onStartCommand(). Type : 9
W/ResourcesManager( 6569): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6569): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,W/ResourcesManager( 6569): Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
W/ResourcesManager( 6569): Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
I/AppUp4:AppBoxCP( 6550): onCreate
W/AppUp4:DB( 6550):  [AppBoxDatabaseHelper] construct
,I/AppUp4:DB( 6550):  setFingerPrint start
I/AppUp4:DB( 6550):  newfinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys SDK version = 21
I/AppUp4:DB( 6550):  beforefinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys
I/AppUp4:DB( 6550):  SDK version = 21
I/AppUp4:DB( 6550):  beforefinger == newfinger no write in DB
D/AppUp4:AppBoxApplication( 6550): AppBoxApplication onCreate()
I/NetworkStateForAutoUpdateMonitor( 6550): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 6550): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
,I/NetworkStateForAutoUpdateMonitor( 6550): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 6550): [onReceive] request level :IDLE....
I/AppUp4:CustModeStarterReceiver( 6550): onReceive
D/LgDataFeature( 6550): LgDataFeature() Constructor: none
D/LgDataFeature( 6550): LgDataFeature() Constructor Done, null
,D/AppUp4:CustFacade( 6550): Context : android.app.ReceiverRestrictedContext@1bc4aa61
D/AppUp4:CustFacade( 6550): isCustomizationCompleted : false
D/AppUp4:CustFacade( 6550): isPhone : true
D/AppUp4:CustModeStarterReceiver( 6550): begin check event
I/AppUp4:CustModeStarterReceiver( 6550): Event For GoodConnectivity
D/AppUp4:CustModeStarterReceiver( 6550): runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
I/AppConfig( 6569): Total System Memory = 2995761152
,D/SystemHelper( 6569): region [EU], country [EU], operator [OPEN], sub-operator []
D/AppUp4:CustModeStarterReceiver( 6550): call method handleAsyncCustNotification.
D/AppUp4:CustModeStarterReceiver( 6550): handleAsync isTriedOnce : false
E/AppUp4:CustModeStarterReceiver( 6550): handleAsyncCustNotification do not startCustService
,I/ActivityManager( 1032): Killing 5855:com.google.android.apps.docs/u0a61 (adj 15): empty #17
I/jxcore-log( 6048): Test app app.js loaded
I/jxcore-log( 6048): 
,I/chromium( 6048): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6048): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6048): 	Automate Bluetooth MAC address resolution: true, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6048): 	Provide Bluetooth MAC address timeout in milliseconds: 40000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6048): 	Bluetooth MAC address: 58:3F:54:73:64:C0, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6048): 	Discovery mode: WIFI, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6048): 	Peer expiration time in milliseconds: 60000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6048): 	Advertise mode: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6048): 	Advertise TX power level: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6048): 	Scan mode: 1
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6048): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3191d985 added. We now have 1 listener(s)
I/jxcore-log( 6048): BLE advertisement is not supported: Bluetooth LE advertising is not supported
I/jxcore-log( 6048): 
I/jxcore-log( 6048): TAP version 13
I/jxcore-log( 6048): 
,I/jxcore-log( 6048): # setup
I/jxcore-log( 6048): 
I/jxcore-log( 6048): # #generatePreambleAndBeacons empty keys to notify
I/jxcore-log( 6048): 
D/LGDMClient( 3951): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 3951): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
W/ContextImpl( 3951): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,W/libprocessgroup( 1032): failed to open /acct/uid_10061/pid_5855/cgroup.procs: No such file or directory
I/jxcore-log( 6048): ok 1 should be equal
I/jxcore-log( 6048): 
I/jxcore-log( 6048): ok 2 should be equal
I/jxcore-log( 6048): 
W/ContextImpl( 3951): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
I/ReaderUtils( 6521): PortraitW 1440 LandscapeW 2392 SmallestSize 1340 LargestSize 2392 textZoom 4.4999995 isTablet false Memory 256
I/jxcore-log( 6048): ok 3 should be equal
I/jxcore-log( 6048): 
I/jxcore-log( 6048): ok 4 should be equal
I/jxcore-log( 6048): 
I/jxcore-log( 6048): # teardown
I/jxcore-log( 6048): 
I/jxcore-log( 6048): # setup
I/jxcore-log( 6048): 
I/jxcore-log( 6048): # #generatePreambleAndBeacons multiple keys to notify
I/jxcore-log( 6048): 
,E/WifiStateMachine( 1032):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-58 f=2412 sc=60 link=72 tx=4.2, 0.0, 0.0  rx=3.5 bcn=0 [on:0 tx:0 rx:0 period:2969] from screen [on:0 period:-1279003194] gl rssi=-58 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1032):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-58 f=2412 sc=60 link=72 tx=4.2, 0.0, 0.0  rx=3.5 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-1279003193] gl rssi=-58 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1032): doString: [SIGNAL_POLL]
I/ActivityManager( 1032): Start proc com.android.chrome for service com.android.chrome/com.google.android.apps.chrome.sync.ChromeBrowserSyncAdapterService: pid=6594 uid=10057 gids={50057, 9997, 3003, 1028, 1015} abi=armeabi-v7a
D/GpsLocationProvider( 1032): updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/art     (  358): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 448us total 22.182ms
,I/art     (  358): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 406us total 18.530ms
,V/DownloadManager( 3285): Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
,V/DownloadManager( 3285): DownloadService onCreate
I/DownloadManager( 3285): in removeSpuriousFiles
D/LGDMClient( 3951): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=3, isUserType=1
I/LGDMClient( 3951): [DmServiceProcessor.java] [processNetworkChanged()] : [91] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
V/DownloadManager( 3285): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
I/art     (  358): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 358us total 16.968ms
,V/DownloadManager( 3285): created cursor android.database.sqlite.SQLiteCursor@100ea2d4 on behalf of 3285
I/jxcore-log( 6048): ok 5 should be equal
I/jxcore-log( 6048): 
I/jxcore-log( 6048): ok 6 should be equal
I/jxcore-log( 6048): 
I/DownloadManager( 3285): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGMyGuide_4.40.09_COM_COM_20150430011620058_RELG-D855.apk
I/DownloadManager( 3285): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGBackup_4.50.37_COM_COM_20150608234245157.apk
I/DownloadManager( 3285): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/CalendarProvider_4.2.8_COM_COM_20150304234552863_RELG-D855.apk
I/DownloadManager( 3285): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calendar_4.40.16_COM_COM_20150304234554754_RELG-D855.apk
I/DownloadManager( 3285): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.10_COM_COM_20150521235426173_RELG-D855.apk
I/DownloadManager( 3285): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQVoiceplusN_2.3.3_COM_COM_20150604065210803.apk
I/DownloadManager( 3285): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.11_COM_COM_v2_20150911144028620_RELG-D855_21.apk
I/DownloadManager( 3285): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQMemoplus(LG-D855_user)_20150902050954661.apk
I/DownloadManager( 3285): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/RemoteCall_4.1.10_COM_COM_20150817053748728.apk
I/DownloadManager( 3285): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/rspermlge(6713)_20150901080430397.apk
I/DownloadManager( 3285): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGBackup_4.51.57_COM_COM_8275_2_20151201044833536_RELG-D855_21.apk
I/DownloadManager( 3285): in trimDatabase
V/DownloadManager( 3285): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
I/jxcore-log( 6048): ok 7 should be equal
I/jxcore-log( 6048): 
V/DownloadManager( 3285): created cursor android.database.sqlite.SQLiteCursor@29f86772 on behalf of 3285
I/jxcore-log( 6048): ok 8 should be equal
I/jxcore-log( 6048): 
I/jxcore-log( 6048): # teardown
I/jxcore-log( 6048): 
,I/jxcore-log( 6048): # setup
I/jxcore-log( 6048): 
I/jxcore-log( 6048): # #parseBeacons invalid ECDH public key in beaconStreamWithPreAmble
I/jxcore-log( 6048): 
D/LGDMClient( 3951): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 3951): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
I/jxcore-log( 6048): ok 9 should throw
I/jxcore-log( 6048): 
I/ActivityManager( 1032): Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=6620 uid=10023 gids={50023, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
I/jxcore-log( 6048): # teardown
I/jxcore-log( 6048): 
I/jxcore-log( 6048): # setup
I/jxcore-log( 6048): 
I/jxcore-log( 6048): # #parseBeacons invalid expiration in beaconStreamWithPreAmble
I/jxcore-log( 6048): 
W/ContextImpl( 3951): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:141 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:180 android.app.IntentService$ServiceHandler.handleMessage:65 
V/DownloadManager( 3285): DownloadService onStartCommand
V/DownloadManager( 3285): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
,E/LGDMClient( 3951): [DmNotiService.java] [onCreate()] : [148] : DmNotiService.onCreate()
D/LGDMClient( 3951): [DmNotiService.java] [onStartCommand()] : [182] : in the new onStartCommand()
D/LGDMClient( 3951): [DmNotiService.java] [handleStart()] : [203] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
E/GpsLocationProvider( 1032): No APN found to select.
I/jxcore-log( 6048): ok 10 should throw
I/jxcore-log( 6048): 
I/jxcore-log( 6048): # teardown
I/jxcore-log( 6048): 
V/DownloadManager( 3285): created cursor android.database.sqlite.SQLiteCursor@131d1840 on behalf of 3285
I/jxcore-log( 6048): # setup
I/jxcore-log( 6048): 
I/jxcore-log( 6048): # #parseBeacons no beacons returns null
I/jxcore-log( 6048): 
V/DownloadManager( 3285): processing inserted download 1
V/DownloadManager( 3285): processing inserted download 4
,W/GAV2    ( 6521): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
I/jxcore-log( 6048): ok 11 should be equal
I/jxcore-log( 6048): 
,I/jxcore-log( 6048): # teardown
I/jxcore-log( 6048): 
I/jxcore-log( 6048): # setup
I/jxcore-log( 6048): 
I/jxcore-log( 6048): # #parseBeacons invalid size for encryptedBeaconKeyId in  beaconStreamWithPreAmble
I/jxcore-log( 6048): 
V/DownloadManager( 3285): processing inserted download 7
V/DownloadManager( 3285): processing inserted download 8
V/DownloadManager( 3285): processing inserted download 9
V/DownloadManager( 3285): processing inserted download 10
V/DownloadManager( 3285): processing inserted download 16
V/DownloadManager( 3285): processing inserted download 17
V/DownloadManager( 3285): processing inserted download 18
V/DownloadManager( 3285): processing inserted download 21
I/jxcore-log( 6048): ok 12 should throw
I/jxcore-log( 6048): 
I/jxcore-log( 6048): # teardown
I/jxcore-log( 6048): 
V/DownloadManager( 3285): processing inserted download 22
I/jxcore-log( 6048): # setup
I/jxcore-log( 6048): 
I/jxcore-log( 6048): # #parseBeacons addressBookCallback fails decrypt
I/jxcore-log( 6048): 
,I/BooksApp( 6521): Created application version: 3.2.35 (30235)
V/DownloadManager( 3285): DownloadService onDestroy
I/ActivityManager( 1032): Killing 5479:com.lge.lockscreensettings/u0a80 (adj 15): empty #17
,W/ResourcesManager( 6620): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6620): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 6620): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
W/ResourcesManager( 6620): Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
I/art     ( 2166): Explicit concurrent mark sweep GC freed 17131(967KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 30MB/62MB, paused 1.299ms total 43.621ms
,W/libprocessgroup( 1032): failed to open /acct/uid_10080/pid_5479/cgroup.procs: No such file or directory
,I/LGEmail ( 6620): [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
I/jxcore-log( 6048): ok 13 should be equal
I/jxcore-log( 6048): 
I/jxcore-log( 6048): # teardown
I/jxcore-log( 6048): 
I/jxcore-log( 6048): # setup
I/jxcore-log( 6048): 
I/jxcore-log( 6048): # #parseBeacons addressBookCallback returns null for all
I/jxcore-log( 6048): 
,W/DriveInitializer( 2361): Background init thread started
D/DelayedSyncController( 6594): Delaying sync.
,D/LGEmail ( 6620): user build Type == true (at Util.java isUserModeBuildType 3507)[v:6.41.18]
E/VoldCmdListener(  279): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  279): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.gms/files/
W/Vold    (  279): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 2361): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.gms/files
I/ActivityManager( 1032): Killing 5509:com.google.android.apps.plus/u0a97 (adj 15): empty #17
W/DriveInitializer( 2361): Awaiting to be initialized
,W/ResourceType( 6620): No package identifier when getting value for resource number 0x00000000
,I/jxcore-log( 6048): ok 14 (unnamed assert)
I/jxcore-log( 6048): 
,I/jxcore-log( 6048): ok 15 should be equal
I/jxcore-log( 6048): 
I/jxcore-log( 6048): # teardown
I/jxcore-log( 6048): 
,I/jxcore-log( 6048): # setup
I/jxcore-log( 6048): 
I/jxcore-log( 6048): # #parseBeacons addressBookCallback returns public key
I/jxcore-log( 6048): 
I/jxcore-log( 6048): ok 16 (unnamed assert)
I/jxcore-log( 6048): 
,I/jxcore-log( 6048): ok 17 (unnamed assert)
I/jxcore-log( 6048): 
I/jxcore-log( 6048): # teardown
I/jxcore-log( 6048): 
I/jxcore-log( 6048): # setup
I/jxcore-log( 6048): 
I/jxcore-log( 6048): # #parseBeacons with beacons both for and not for the user
I/jxcore-log( 6048): 
I/art     ( 1032): Explicit concurrent mark sweep GC freed 77083(3MB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 44MB/66MB, paused 2.524ms total 172.608ms
,W/libprocessgroup( 1032): failed to open /acct/uid_10097/pid_5509/cgroup.procs: No such file or directory
V/AlarmManager( 1032): RTC_WAKEUP set : Alarm{239219ba type 0 when 1454714910698 com.android.vending} when 1454714910698
,D/libc-netbsd(  311): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  311): res_queryN name = www.google.com, class = 1, type = 1
,I/jxcore-log( 6048): ok 18 (unnamed assert)
I/jxcore-log( 6048): 
I/jxcore-log( 6048): # teardown
I/jxcore-log( 6048): 
D/libc-netbsd(  311): res_queryN name = www.google.com succeed
,D/libc-netbsd(  311): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  311): res_queryN name = clients3.google.com, class = 1, type = 1
D/libc-netbsd(  311): res_queryN name = clients3.google.com succeed
D/LgDataFeature( 6620): LgDataFeature() Constructor: none
D/LgDataFeature( 6620): LgDataFeature() Constructor Done, null
E/Auth.Api.Credentials( 2361): [CredentialSyncAdapter] Unknown sync event.
,I/BooksSync( 6521): Starting books sync
V/SIM_STK ( 1032): Menu title from STK is T-Mobile
W/DriveInitializer( 2361): Background init thread ended
,V/WifiInternetCheck( 1032): isHttpConnectionAvailable - We got a valid response : 204
,D/eas_req ( 6620): ---addEventToQueue() easCode=2, requestId=0 (at EasSupport.java addEventToQueue 69)
,I/LgeMiscReceiver( 3242): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 3242): action = android.net.conn.CONNECTIVITY_CHANGE
,I/LgeMiscReceiver( 3242): networkInfo.isConnected() = true
D/PhoneState( 3242): setPdpRejectCasuse : false
I/HubEmail( 6620): JNI_OnLoad()
I/HubEmail( 6620): -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 6620): registerNatives()
I/HubEmail( 6620): -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 6620): registerNativeMethods()
I/HubEmail( 6620): -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
W/art     ( 6620): JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
D/libc-netbsd(  311): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  311): res_queryN name = static-avc.lglime.com, class = 1, type = 1
,I/ActivityManager( 1032): Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=6683 uid=10062 gids={50062, 9997, 4002, 3003, 1028} abi=armeabi-v7a
W/Settings( 6620): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 6620): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,V/GLSActivity( 2166): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/DrmBroadcastReceiver( 6683): Receive CONNECTIVITY_ACTION
D/BooksSync( 6521): started syncMyEbooks
D/DrmBroadcastReceiver( 6683): 1  network is available. Sync DRM Time with NTP
,V/DrmService( 6683): Service onCreate
D/DrmService( 6683): Received new request = 2
I/GLSUser ( 2166): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 2166): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2166): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2166): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
I/DrmSntpClient( 6683): Start Sync process
D/DrmSntpClient( 6683): Server : 0
D/libc-netbsd(  311): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  311): res_queryN name = pool.ntp.org, class = 1, type = 1
,I/ActivityManager( 1032): Start proc com.lge.sizechangable.weather for broadcast com.lge.sizechangable.weather/.layout.WeatherWidget: pid=6708 uid=10085 gids={50085, 9997, 3003, 1028, 1015} abi=armeabi-v7a
V/GLSActivity( 2166): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/Finsky  ( 4826): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 4826): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 4826): [1] 5.onFinished: Scheduling replication attempt 2.
,V/GLSActivity( 2166): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     ( 6708): Almond Protected OAT
D/libc-netbsd(  311): res_queryN name = pool.ntp.org succeed
I/GLSUser ( 2166): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 2166): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2166): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2166): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2166): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/LGDrmClient( 6683): _DRM_ServiceGet() : Bind lgdrm service
V/ILGDrmService(  320): eDRM_SetDRMTime +++
I/LGDRM   (  320): [DRM] SET TIME : YR=2016, MON=2, DAY=5
I/LGDRM   (  320): [DRM] SET TIME : HR=23, MIN=28, SEC=31
,D/DelayedSyncController( 6594): Delaying sync.
V/ILGDrmService(  320): eDRM_SetDRMTime ---
I/DrmSntpClient( 6683): Synched
D/DrmService( 6683): Completed !! request = 2
D/DrmService( 6683): Request count = 0
V/DrmService( 6683): Service onDestroy
I/ActivityManager( 1032): Killing 5913:com.lge.eula/1000 (adj 15): empty #17
,W/libprocessgroup( 1032): failed to open /acct/uid_1000/pid_5913/cgroup.procs: No such file or directory
,D/WeatherApplication( 6708): removeAccount
D/WeatherApplication( 6708): Account.length = 0
E/WeatherApplication( 6708): OPERATOR:OPEN
D/WeatherAncestor( 6708): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 0:28:31
D/Weather.Utils( 6708): 2 : the weather widgets(using time tick) are gone.
D/Weather.Utils( 6708): 2 : All the weather widget is gone.
D/UpdateThreadPoolManager( 6708): 2 : This is isUpdating : false
D/WeatherAncestor( 6708): connectivity changed - connection : true
D/WeatherService( 6708): 2 : isServiceAlived():false forecastCache:null
,V/NotificationService( 1032): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/ForecastDataCache( 6708): 2 : lastUpdatedTime: 1430558561343
D/ForecastDataCache( 6708): 2 : currentPackageVersion: 4.40.4
D/ForecastDataCache( 6708): 2 : Cache is not up-to-date, count: 0
D/ZenLog  ( 1032): intercepted: 0|com.google.android.gms|1|null|10005,none
V/NotificationService( 1032): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1032): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1032): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1032): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
W/GLSActivity( 2166): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2166): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2166): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2166): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2166): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2166): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2166): 	at android.os.Binder.execTransact(Binder.java:446)
W/ResourcesManager( 1397): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
E/BooksAccountManager( 6521): Authentication error
E/BooksAccountManager( 6521): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6521): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6521): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6521): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6521): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6521): 	at android.os.Binder.execTransact(Binder.java:446)
W/ResourcesManager( 1397): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
E/HttpHelper( 6521): null auth token
W/ResourcesManager( 1452): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 1452): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
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
D/LgeQuickCoverOverlayWindow( 1397): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1397): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1397): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1397): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1397): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1397): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1397): updateNotificationData: count=3
D/Weather_cast( 6708): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherAncestor( 6708): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 0:28:31
D/libc-netbsd(  311): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  311): res_queryN name = www.googleapis.com, class = 1, type = 1
D/QuickStatusbarLayout( 1397): Notification difference=198
D/QuickStatusbarLayout( 1397): child = android.widget.LinearLayout{2b2bce9 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,D/libc-netbsd(  311): res_queryN name = www.googleapis.com succeed
,I/ActivityManager( 1032): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=6732 uid=10093 gids={50093, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager( 1032): Killing 5327:com.google.android.gms.wearable/u0a5 (adj 15): empty #17
,W/libprocessgroup( 1032): failed to open /acct/uid_10005/pid_5327/cgroup.procs: No such file or directory
,D/libc-netbsd(  311): res_queryN name = static-avc.lglime.com succeed
V/FormManager( 6131): There are no updated forms. The schedule will be deleted.
,I/ActivityManager( 1032): Start proc com.google.android.apps.plus for service com.google.android.apps.plus/.service.EsSyncAdapterService: pid=6749 uid=10097 gids={50097, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
V/FormManager( 6131): Alarm would be updated, because LastCheckTime has been updated.
I/ActivityManager( 1032): Killing 2141:com.lge.music/u0a34 (adj 15): empty #17
,V/AudioFlinger(  315): 2141 died, releasing its sessions
V/AudioFlinger(  315):  pid 1852 @ 0
V/AudioFlinger(  315):  pid 3242 @ 1
V/AudioFlinger(  315):  pid 3242 @ 2
,E/VoldCmdListener(  279): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  279): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  279): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6732): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
E/VoldCmdListener(  279): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  279): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  279): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6732): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
E/VoldCmdListener(  279): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  279): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  279): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6732): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
E/VoldCmdListener(  279): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  279): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  279): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6732): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
W/libprocessgroup( 1032): failed to open /acct/uid_10034/pid_2141/cgroup.procs: No such file or directory
,W/ResourcesManager( 6749): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ApiaryClient( 6521): Error response from books API: {
W/ApiaryClient( 6521):  "error": {
W/ApiaryClient( 6521):   "errors": [
W/ApiaryClient( 6521):    {
W/ApiaryClient( 6521):     "domain": "global",
W/ApiaryClient( 6521):     "reason": "required",
W/ApiaryClient( 6521):     "message": "Login Required",
W/ApiaryClient( 6521):     "locationType": "header",
W/ApiaryClient( 6521):     "location": "Authorization"
W/ApiaryClient( 6521):    }
W/ApiaryClient( 6521):   ],
W/ApiaryClient( 6521):   "code": 401,
W/ApiaryClient( 6521):   "message": "Login Required"
W/ApiaryClient( 6521):  }
W/ApiaryClient( 6521): }
,W/ApiaryClient( 6521): errCount = 1: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6521): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=127592504003830964&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6521): Headers:
W/ApiaryClient( 6521): accept-encoding: [gzip]
W/ApiaryClient( 6521): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6521): gdata-version: 2
I/GLSActivity( 2166): [ac] getting account id
,I/WebViewFactory( 6732): Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
I/GLSUser ( 2166): [t] Fetched account id for thalitester@gmail.com : 105256135866144380227
I/LibraryLoader( 6732): Loading: webviewchromium
,I/LibraryLoader( 6732): Time to load native libraries: 5 ms (timestamps 9949-9954)
I/LibraryLoader( 6732): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 6732): Binding Chromium to main looper Looper (main, tid 1) {578cb10}
I/LibraryLoader( 6732): Expected native library version number "",actual native library version number ""
I/chromium( 6732): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 6732): Initializing chromium process, renderers=0
,W/art     ( 6732): Attempt to remove local handle scope entry from IRT, ignoring
W/chromium( 6732): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
I/chromium( 6732): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=39 off=46780 len=2953
I/chromium( 6732): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:40 off:229536 len:643667
,V/AudioPolicyService(  315): registerClient() client 0xb119dd80, uid 10093
W/AudioManagerAndroid( 6732): Requires BLUETOOTH permission
D/ChimeraCfgMgr( 2361): Loading module com.google.android.gms.games from APK com.google.android.gms
,I/Adreno-EGL( 6732): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 6732): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 6732): Build Date: 12/12/14 금
I/Adreno-EGL( 6732): Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
I/Adreno-EGL( 6732): Remote Branch: 
I/Adreno-EGL( 6732): Local Patches: 
I/Adreno-EGL( 6732): Reconstruct Branch: 
,I/NSApplication( 6732): Starting up...
,I/ActivityManager( 1032): Killing 5938:com.lge.bnr/1000 (adj 15): empty #17
,I/art     ( 1032): Explicit concurrent mark sweep GC freed 27941(1226KB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 44MB/66MB, paused 1.571ms total 112.307ms
,W/libprocessgroup( 1032): failed to open /acct/uid_1000/pid_5938/cgroup.procs: No such file or directory
,D/libc-netbsd(  311): default dns: query_ipv6=0, query_ipv4=1
,D/libc-netbsd(  311): res_queryN name = mtalk.google.com, class = 1, type = 1
V/GLSActivity( 2166): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/iu.SyncManager( 2361): SYNC; picasa accounts
,D/libc-netbsd(  311): res_queryN name = mtalk.google.com succeed
I/GLSUser ( 2166): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.syncadapters.contacts, service: cp
I/GLSUser ( 2166): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> cp without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2166): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2166): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2166): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/NetworkLogImpl( 2361): Loaded NetworkSpeedPredictor
I/iu.Environment( 2361): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
I/iu.UploadsManager( 2361): num queued entries: 0
,I/iu.UploadsManager( 2361): num updated entries: 0
I/iu.SyncManager( 2361): NEXT; no task
D/ChimeraCfgMgr( 2361): Loading module com.google.android.gms.kids from APK com.google.android.gms
D/ChimeraCfgMgr( 2361): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/PostponalbeReceiver( 5124): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.intent.action.TIME_SET'.
,V/NotificationService( 1032): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
V/NotificationService( 1032): pkg=com.google.android.gms canInterrupt=false intercept=true
W/GLSActivity( 2166): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2166): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2166): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2166): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2166): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2166): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2166): 	at android.os.Binder.execTransact(Binder.java:446)
I/ActivityManager( 1032): Start proc com.lge.clock for broadcast com.lge.clock/.alarmclock.ALBootInit: pid=6829 uid=10010 gids={50010, 9997, 3003, 1028, 4002} abi=armeabi-v7a
,I/NotificationServiceEx( 1032): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1032): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1032): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/ContactsSyncAdapter( 2166): innerSync failed
D/ContactsSyncAdapter( 2166): com.google.wireless.gdata2.client.AuthenticationException: unable to get auth token android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
D/ContactsSyncAdapter( 2166): 	at com.google.android.syncadapters.contacts.AuthInfo.getAuthToken(AuthInfo.java:45)
D/ContactsSyncAdapter( 2166): 	at com.google.android.syncadapters.contacts.ContactsSyncAdapter.innerPerformSync(ContactsSyncAdapter.java:263)
D/ContactsSyncAdapter( 2166): 	at com.google.android.syncadapters.contacts.ContactsSyncAdapter.onPerformLoggedSync(ContactsSyncAdapter.java:168)
D/ContactsSyncAdapter( 2166): 	at com.google.android.common.LoggingThreadedSyncAdapter.onPerformSync(LoggingThreadedSyncAdapter.java:33)
D/ContactsSyncAdapter( 2166): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
D/ContactsSyncAdapter( 2166): Caused by: android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
D/ContactsSyncAdapter( 2166): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
D/ContactsSyncAdapter( 2166): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
D/ContactsSyncAdapter( 2166): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
D/ContactsSyncAdapter( 2166): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
D/ContactsSyncAdapter( 2166): 	at android.os.Binder.execTransact(Binder.java:446)
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
,D/LgeQuickCoverOverlayWindow( 1397): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1397): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1397): updateNotificationData: count=3
D/SyncManager( 1032): failed sync operation thalitester@gmail.com u0 (com.google), com.android.contacts, LOCAL, currentRunTime 87054, reason: 10019, SyncResult: stats [ numAuthExceptions: 1]
,D/QuickStatusbarLayout( 1397): Notification difference=198
D/QuickStatusbarLayout( 1397): child = android.widget.LinearLayout{2b2bce9 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,I/GLSUser ( 2166): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: ac2dm
I/GLSUser ( 2166): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> ac2dm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2166): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2166): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2166): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/NotificationService( 1032): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,D/ALBootInit( 6829): ====action==>android.intent.action.TIME_SET
V/NotificationService( 1032): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1032): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1032): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1032): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/ALBootInit( 6829): Alarm ALBootInit: TIME_SET
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
D/Alarms  ( 6829): [setNextAlert] start
,D/LgeQuickCoverOverlayWindow( 1397): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1397): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1397): updateNotificationData: count=3
W/Kids    ( 2361): [AccountUtils] Account not ready
W/Kids    ( 2361): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/Kids    ( 2361): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/Kids    ( 2361): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/Kids    ( 2361): 	at com.google.android.gms.auth.p.c(SourceFile:550)
W/Kids    ( 2361): 	at com.google.android.gms.auth.p.b(SourceFile:477)
W/Kids    ( 2361): 	at com.google.android.gms.kids.account.k.d(SourceFile:103)
W/Kids    ( 2361): 	at com.google.android.gms.kids.account.p.a(SourceFile:70)
W/Kids    ( 2361): 	at com.google.android.gms.kids.account.t.a(SourceFile:62)
W/Kids    ( 2361): 	at com.google.android.gms.chimera.f.run(SourceFile:179)
W/Kids    ( 2361): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Kids    ( 2361): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Kids    ( 2361): 	at java.lang.Thread.run(Thread.java:818)
D/Alarms  ( 6829): [setNextAlert] (1)
,D/Alarms  ( 6829):  minTime  = 0
D/Alarms  ( 6829):  -- OK multi -- 0
D/QuickStatusbarLayout( 1397): Notification difference=198
E/jeny.kim( 6829): [setNextAlert] setNextAlert  temp_Alarmlink + 
D/QuickStatusbarLayout( 1397): child = android.widget.LinearLayout{2b2bce9 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
E/jeny.kim( 6829): [setNextAlert]setNextAlert temp_AlarmLinkText + 
I/CommonUtil( 6829): BUILD Country: EU
D/Alarms  ( 6829): broadcastToWidgetProvider : false
,D/Alarms  ( 6829): Enter formatDayAndTime(final Context context, long timeInMiliSec)
V/SettingsProvider( 1032): call_put(system:next_alarm_formatted=) for 0 calling package = com.lge.clock
,I/DigitalAppWidgetProvider( 6829): onReceive: android.intent.action.TIME_SET
D/GCM     ( 2166): Connected
V/DigitalAppWidgetProvider( 6829): cancelAlarmOnQuarterHour android.app.ReceiverRestrictedContext@26ac4986
,V/DigitalAppWidgetProvider( 6829): startAlarmOnQuarterHour android.app.ReceiverRestrictedContext@26ac4986
,D/QuickCoverProvider( 6829): onReceiver
,I/indal   ( 1397): SmartCoverWidgetContext createApplicationContext
,I/indal   ( 1397): SmartCoverWidgetContext createApplicationContext
D/WeatherAncestor( 6708): 2 : onReceive, action: android.intent.action.TIME_SET, Time(hour:min:sec) 0:28:32
,D/Weather.Utils( 6708): 2 : the weather widgets(using time tick) are gone.
D/Weather.Utils( 6708): 2 : All the weather widget is gone.
D/UpdateThreadPoolManager( 6708): 2 : This is isUpdating : false
D/GCM     ( 2166): Message class com.google.f.a.a.p
D/WeatherService( 6708): 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@19665247
,D/ForecastDataCache( 6708): 2 : lastUpdatedTime: 1430558561343
D/ForecastDataCache( 6708): 2 : currentPackageVersion: 4.40.4
D/ForecastDataCache( 6708): 2 : Cache is up-to-date, count: 0
,D/Weather_cast( 6708): 2 : set auto-update time : 2/6 3:28
D/WeatherAncestor( 6708): 2 : onReceive has processed, action: android.intent.action.TIME_SET, Time(hour:min:sec) 0:28:32
,I/ActivityManager( 1032): Start proc com.qualcomm.timeservice for broadcast com.qualcomm.timeservice/.TimeServiceBroadcastReceiver: pid=6853 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi
I/ActivityManager( 1032): Killing 6235:com.lge.lifetracker/u0a37 (adj 15): empty #17
,W/libprocessgroup( 1032): failed to open /acct/uid_10037/pid_6235/cgroup.procs: No such file or directory
,V/GLSActivity( 2166): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/TimeService( 6853): Receivedandroid.intent.action.TIME_SET intent. Current Time is 1454714912703
D/        ( 6853): TimeServiceNative: User Time to be set is 1454714912703
D/QC-time-services( 6853): Lib:time_genoff_operation: pargs->base = 2
D/QC-time-services( 6853): Lib:time_genoff_operation: pargs->operation = 0
D/QC-time-services( 6853): Lib:time_genoff_operation: pargs->ts_val = 1454714912703
D/QC-time-services(  371): Daemon: Connection accepted:time_genoff
D/QC-time-services( 6853): Lib:time_genoff_operation: Send to server  passed!!
D/QC-time-services(  371): Daemon:Received base = 2, unit = 1, operation = 0,value = 1454714912703
D/QC-time-services(  371): Daemon:genoff_opr: Base = 2, val = 1454714912703, operation = 0
D/QC-time-services(  371): Daemon:rtc_get: Time read from RTC -- MM/DD/YY HH:MM:SS5/15/70 16:40:37
D/QC-time-services(  371): Daemon:Value read from RTC seconds = 14316037000
,D/QC-time-services(  371): Daemon:new time 1454714912703 
D/QC-time-services(  371): Daemon: delta 1440398875703 genoff 1440398875703 
D/QC-time-services(  371): Daemon:genoff_persistent_update: Writing genoff = 1440398875703 to memory
D/QC-time-services(  371): Daemon:Opening File: /data/time/ats_2
D/QC-time-services(  371): Daemon:time_persistent_memory_opr:Genoff write operation 
D/QC-time-services(  371): Updating the TOD offset
D/QC-time-services(  371): Daemon:genoff_persistent_update: Writing genoff = 1440398875703 to memory
D/QC-time-services(  371): Daemon:Opening File: /data/time/ats_1
D/QC-time-services(  371): Daemon:time_persistent_memory_opr:Genoff write operation 
I/GLSUser ( 2166): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2166): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2166): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2166): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,E/QC-time-services(  371): Daemon:Update to modem bit set
D/QC-time-services(  371): Daemon:genoff_send_modem: Sending data to MODEM !
D/QC-time-services(  371): Daemon: Base = 2, Value being sent to MODEM = 1124434075703
E/QC-time-services( 6853): Receive Passed == base = 2, unit = 1, operation = 0, result = 0
V/GLSActivity( 2166): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
E/QC-time-services(  371): Daemon:tod_update_ind_cb: Got Update from modem msg_id 40
E/QC-time-services(  371): Daemon: Time-services: Waiting to acceptconnection
I/ActivityManager( 1032): Start proc com.android.calendar for broadcast com.android.calendar/.widget.CalendarAppWidgetProvider: pid=6874 uid=10013 gids={50013, 9997, 3003, 1028, 1015} abi=armeabi
,I/ActivityManager( 1032): Killing 6278:com.lge.settings.easy/1000 (adj 15): empty #17
W/libprocessgroup( 1032): failed to open /acct/uid_1000/pid_6278/cgroup.procs: No such file or directory
,V/NotificationService( 1032): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1032): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1032): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1032): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1032): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
W/GLSActivity( 2166): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2166): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2166): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2166): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2166): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2166): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2166): 	at android.os.Binder.execTransact(Binder.java:446)
D/LgeQuickCoverNLService( 1397): onNotificationPosted
D/SmartCoverUpdateMonitor( 1397): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1397): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1397): handleNotificationPosted(true)
E/BooksAccountManager( 6521): Authentication error
E/BooksAccountManager( 6521): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6521): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6521): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6521): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6521): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6521): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6521): null auth token
,D/QuickCircle( 1397): onNotificationPosted() : isPosted true
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
W/ResourcesManager( 6874): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,D/QuickStatusbarLayout( 1397): Notification difference=198
D/QuickStatusbarLayout( 1397): child = android.widget.LinearLayout{2b2bce9 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
D/CalendarApplication( 6874): CalendarApplication.onCreate()
,D/PreferenceKeysParser( 6874): [debug_displayParseInfos] preference keys.size() = 44
D/PreferenceKeysParser( 6874): [debug_displayParseInfos] preference keys = {lg_preferences_tardis_1=com.android.calendar.adaptation.PreferenceKey$KeyData@f99a4e5, lg_preferences_hide_declined=com.android.calendar.adaptation.PreferenceKey$KeyData@22c72bba, lg_preferences_default_reminder=com.android.calendar.adaptation.PreferenceKey$KeyData@9fc7a6b, lg_preferences_month_view_style=com.android.calendar.adaptation.PreferenceKey$KeyData@78ee9c8, lg_preferences_alerts_ringtone=com.android.calendar.adaptation.PreferenceKey$KeyData@1bc4aa61, lg_preferences_device_tz=com.android.calendar.adaptation.PreferenceKey$KeyData@26ac4986, lg_preferences_debug_datesearch=com.android.calendar.adaptation.PreferenceKey$KeyData@19665247, lg_preferences_debug_country=com.android.calendar.adaptation.PreferenceKey$KeyData@278cda74, lg_preferences_display_weather_information=com.android.calendar.adaptation.PreferenceKey$KeyData@2b408b9d, lg_preferences_alerts_vibrateWhen=com.android.calendar.adaptation.PreferenceKey$KeyData@2d737812, lg_preferences_debug_rtl=com.android.calendar.adaptation.PreferenceKey$KeyData@38abcbe3, lg_preferences_alerts_type=com.android.calendar.adaptation.PreferenceKey$KeyData@dd729e0, lg_preferrences_country_code=com.android.calendar.adaptation.PreferenceKey$KeyData@369f4499, lg_preferences_weather_info=com.android.calendar.adaptation.PreferenceKey$KeyData@300d035e, lg_preference_holiday_calendar_ver=com.android.calendar.adaptation.PreferenceKey$KeyData@2545433f, lg_preferences_show_controls=com.android.calendar.adaptation.PreferenceKey$KeyData@3ab5040c, lg_preferences_user_select_noti_sound=com.android.calendar.adaptation.PreferenceKey$KeyData@13969155, lg_preference_default_myphonebook=com.android.calendar.adaptation.PreferenceKey$KeyData@3421f76a, lg_preferences_skip_setup=com.android.calendar.adaptation.PreferenceKey$KeyData@11d4d45b, lg_preferred_startView=com.android.calendar.adaptation.PreferenceKey$KeyData@9b454f8, lg_preferences_debug_operator=com.android.calendar.adaptation.PreferenceKey$KeyData@37bedd1, lg_preferences_exclude_sticker_list=com.android.calendar.adaptation.PreferenceKey$KeyData@3ee02036, lg_preferences_writable_calendars_count=com.android.calendar.adaptation.PreferenceKey$KeyData@2f025b37, lg_preferred_detailedView=com.android.calendar.adaptation.PreferenceKey$KeyData@3f55c8a4, lg_preferences_debug_floating=com.android.calendar.adaptation.PreferenceKey$KeyData@2d80960d, lg_preferences_home_tz=com.android.calendar.adaptation.PreferenceKey$KeyData@288609c2, lg_preferences_home_tz_enabled=com.android.calendar.adaptation.PreferenceKey$KeyData@261773d3, lg_preference_received_provider_reminder_broadcast=com.android.calendar.adaptation.PreferenceKey$KeyData@578cb10, lg_preferences_default_cell_height=com.android.calendar.adaptation.PreferenceKey$KeyData@ad8609, lg_preferences_notification_type=com.android.calendar.adaptation.PreferenceKey$KeyData@1caf000e, lg_preferences_show_week_num=com.android.calendar.adaptation.PreferenceKey$KeyData@215b7a2f, lg_preferences_dont_show_again_no_online_account=com.android.calendar.adaptation.PreferenceKey$KeyData@287883c, lg_preferences_alerts_popup=com.android.calendar.adaptation.PreferenceKey$KeyData@399f79c5, lg_preferences_week_start_day=com.android.calendar.adaptation.PreferenceKey$KeyData@135f0f1a, lg_preferences_app_version=com.android.calendar.adaptation.PreferenceKey$KeyData@3e2f8a4b, lg_preferences_alerts=com.android.calendar.adaptation.PreferenceKey$KeyData@3762ec28, lg_preferences_select_aux_calendar=com.android.calendar.adaptation.PreferenceKey$KeyData@802ed41, lg_preferences_widget_info_calendars=com.android.calendar.adaptation.PreferenceKey$KeyData@ecf02e6, lg_preferences_alerts_default_ringtone=com.android.calendar.adaptation.PreferenceKey$KeyData@4ea8027, lg_preference_defaultCalendar=com.android.calendar.adaptation.PreferenceKey$KeyData@100ea2d4, lg_preferences_alerts_vibratetype=com.android.calendar.adaptation.PreferenceKey$KeyData@fd01c7d, lg_preferences_recent_ti,mezones=com.android.calendar.adaptation.PreferenceKey$KeyData@29f86772, lg
,D/GeneralPreferenceUtils( 6874): [migratePrefrenceKeys] Exit: Version(44001600) >= 42001300
D/Config  ( 6874): [init]
,I/Config  ( 6874): LGCalendar ver.4.40.16
I/Config  ( 6874): start check model
I/Config  ( 6874): start check native_ca
I/Config  ( 6874): Config Operator=OPEN, Country=EU
D/Config  ( 6874): [setDefaultValuesToPref]
D/Config  ( 6874): [parseProfiles]
W/ApiaryClient( 6521): Error response from books API: {
W/ApiaryClient( 6521):  "error": {
W/ApiaryClient( 6521):   "errors": [
W/ApiaryClient( 6521):    {
W/ApiaryClient( 6521):     "domain": "global",
W/ApiaryClient( 6521):     "reason": "required",
W/ApiaryClient( 6521):     "message": "Login Required",
W/ApiaryClient( 6521):     "locationType": "header",
W/ApiaryClient( 6521):     "location": "Authorization"
W/ApiaryClient( 6521):    }
W/ApiaryClient( 6521):   ],
W/ApiaryClient( 6521):   "code": 401,
W/ApiaryClient( 6521):   "message": "Login Required"
W/ApiaryClient( 6521):  }
W/ApiaryClient( 6521): }
W/ApiaryClient( 6521): errCount = 2: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6521): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=127592504003830964&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6521): Headers:
W/ApiaryClient( 6521): accept-encoding: [gzip]
W/ApiaryClient( 6521): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6521): gdata-version: 2
D/ProfilesParser( 6874): [debug_displayParseInfos] profile.country = null
D/ProfilesParser( 6874): [debug_displayParseInfos] profile.operator = null
D/Config  ( 6874): [updateProfiletoCountryInfo]
D/GeneralPreference( 6874): [checkAndMigrateOldPreference]
E/AgendaWidgetManager( 6874): [updateWidgets] 
,I/InitNotificationRingtoneService( 6874): Start InitializeAlertRingtoneService.onHandleIntent
I/AlertUtils( 6874): [setFormatNotificationSound] current noti URI = content://media/internal/audio/media/41
I/AlertUtils( 6874): [getCalendarNotiSoundURIFromCursor] getCount()= 21
,I/AlertUtils( 6874): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Arpeggio.ogg
I/AlertUtils( 6874): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Country_Blues.ogg
,I/AlertUtils( 6874): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Crystal.ogg
I/AlertUtils( 6874): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Dewdrop.ogg
I/AlertUtils( 6874): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Ding_Dong.ogg
,I/AlertUtils( 6874): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Echo.ogg
I/AlertUtils( 6874): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Email.ogg
I/AlertUtils( 6874): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Game_Over.ogg
,I/AlertUtils( 6874): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Gayageum.ogg
I/AlertUtils( 6874): [getMediaFilepathFromContentUri] filepath = /system/media/audio/alarms/Afternoon_Walk.ogg
,I/AlertUtils( 6874): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Harmonics.ogg
I/AlertUtils( 6874): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Idea.ogg
,I/AlertUtils( 6874): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/News.ogg
I/AlertUtils( 6874): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Pebble.ogg
I/AlertUtils( 6874): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Schedule.ogg
I/AlertUtils( 6874): [getCalendarNotiSoundURIFromCursor] filePath = /system/media/audio/notifications/Schedule.ogg, new URI = content://media/internal/audio/media/41
,I/AlertUtils( 6874): set default noti to content://media/internal/audio/media/41
,I/InitNotificationRingtoneService( 6874): End InitializeAlertRingtoneService.onHandleIntent
E/WifiStateMachine( 1032):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-61 f=2412 sc=60 link=72 tx=4.6, 0.0, 0.0  rx=3.2 bcn=0 [on:0 tx:0 rx:0 period:3006] from screen [on:0 period:-1279000184] gl rssi=-61 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1032):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-61 f=2412 sc=60 link=72 tx=4.6, 0.0, 0.0  rx=3.2 bcn=0 [on:0 tx:0 rx:0 period:2] from screen [on:0 period:-1279000182] gl rssi=-61 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1032): doString: [SIGNAL_POLL]
,W/HolidayIntentService( 6874): onHandleIntent
D/MonthWidgetProvider( 6874): [onReceive]
D/CalendarWidgetProvider( 6874): [onReceive]
D/CalendarWidgetProvider( 6874): [CalendarWidgetProvider] got the intent: Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.android.calendar/.widget.MonthWidgetProvider }
D/HolidayDataLoader( 6874): readJsonAsset : holiday.json
D/CalendarTypeController( 6874): [onUpdateAndInitCalendarTime]
,D/WeekWidgetProvider( 6874): [onReceive]
D/CalendarWidgetProvider( 6874): [onReceive]
D/CalendarWidgetProvider( 6874): [CalendarWidgetProvider] got the intent: Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.android.calendar/.widget.WeekWidgetProvider }
D/CalendarTypeController( 6874): [onUpdateAndInitCalendarTime]
I/DigitalAppWidgetProvider( 6829): onReceive: android.intent.action.ALARM_CHANGED
,E/HolidayIntentService( 6874): onHandleIntent:holiday data empty
D/WeatherAncestor( 6708): 2 : onReceive, action: com.lge.sizechangable.weather.action.setweathercast, Time(hour:min:sec) 0:28:33
D/Weather.Utils( 6708): 2 : the weather widgets(using time tick) are gone.
D/Weather.Utils( 6708): 2 : All the weather widget is gone.
D/UpdateThreadPoolManager( 6708): 2 : This is isUpdating : false
,D/Weather_cast( 6708): 2 : Update is Canceled by com.lge.sizechangable.weather.action.alarm
D/WeatherAncestor( 6708): 2 : onReceive has processed, action: com.lge.sizechangable.weather.action.setweathercast, Time(hour:min:sec) 0:28:33
I/ActivityManager( 1032): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.realtimechat.RequestWriter$NetworkStateReceiver: pid=6898 uid=10072 gids={50072, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,I/ActivityManager( 1032): Killing 6171:com.lge.sync/1000 (adj 15): empty #17
W/libprocessgroup( 1032): failed to open /acct/uid_1000/pid_6171/cgroup.procs: No such file or directory
,W/ResourcesManager( 6898): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,D/LgDataFeature( 6898): LgDataFeature() Constructor: none
D/LgDataFeature( 6898): LgDataFeature() Constructor Done, null
,I/Babel   ( 6898): MmsConfig: mnc/mcc: 0/0
I/Babel   ( 6898): MmsConfig.loadMmsSettings
I/Babel   ( 6898): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D855 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D855-M3-D1.xml
I/Babel   ( 6898): MmsConfig.loadFromDatabase
,E/Babel   ( 6898): canonicalizeMccMnc: invalid mccmnc 
,I/Babel   ( 6898): MmsConfig.loadFromResources
E/Babel   ( 6898): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel   ( 6898): MmsConfig.loadMmsSettings: mUserAgent=LG-D855 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D855-M3-D1.xml
W/Settings( 6898): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/AudioCapabilities( 6898): Unsupported mime audio/evrc
,W/AudioCapabilities( 6898): Unsupported mime audio/qcelp
W/VideoCapabilities( 6898): Unrecognized profile 2130706433 for video/avc
W/AudioCapabilities( 6898): Unsupported mime audio/amr-wb-plus
,W/AudioCapabilities( 6898): Unsupported mime audio/qcelp
W/AudioCapabilities( 6898): Unsupported mime audio/evrc
I/GCM     ( 2361): Message from null null
E/GCM     ( 2361): Dropping message from null
W/VideoCapabilities( 6898): Unsupported mime video/x-ms-wmv
,W/VideoCapabilities( 6898): Unsupported mime video/divx
W/ResourcesManager( 6898): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 6898): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
W/VideoCapabilities( 6898): Unsupported mime video/divx311
W/VideoCapabilities( 6898): Unsupported mime video/divx4
W/VideoCapabilities( 6898): Unsupported mime video/mp4v-esdp
,V/GLSActivity( 2166): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/VideoCapabilities( 6898): Unsupported profile 4 for video/mp4v-es
,W/AudioCapabilities( 6898): Unsupported mime audio/eac3
W/AudioCapabilities( 6898): Unsupported mime audio/ac3
W/AudioCapabilities( 6898): Unsupported mime audio/g726
W/AudioCapabilities( 6898): Unsupported mime audio/wma-voice
W/AudioCapabilities( 6898): Unsupported mime audio/x-ms-wma
,W/AudioCapabilities( 6898): Unsupported mime audio/adpcm
W/VideoCapabilities( 6898): Unsupported mime video/theora
W/VideoCapabilities( 6898): Unsupported mime video/mjpg
I/art     ( 2166): Explicit concurrent mark sweep GC freed 20978(1209KB) AllocSpace objects, 13(1616KB) LOS objects, 51% free, 30MB/62MB, paused 1.773ms total 68.081ms
V/JNIHelp ( 6898): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,I/GLSUser ( 2166): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2166): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 2166): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2166): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2166): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1032): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1032): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1032): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1032): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1032): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
W/GLSActivity( 2166): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2166): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2166): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2166): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2166): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2166): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2166): 	at android.os.Binder.execTransact(Binder.java:446)
E/BooksAccountManager( 6521): Authentication error
E/BooksAccountManager( 6521): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6521): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6521): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6521): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6521): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6521): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6521): null auth token
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
D/QuickStatusbarLayout( 1397): child = android.widget.LinearLayout{2b2bce9 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,W/System  ( 6898): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/system/framework/com.google.android.media.effects.jar", zip file "/system/app/Hangouts/Hangouts.apk"],nativeLibraryDirectories=[/system/app/Hangouts/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,I/ProviderInstaller( 6898): Installed default security provider GmsCore_OpenSSL
W/ApiaryClient( 6521): Error response from books API: {
W/ApiaryClient( 6521):  "error": {
W/ApiaryClient( 6521):   "errors": [
W/ApiaryClient( 6521):    {
W/ApiaryClient( 6521):     "domain": "global",
W/ApiaryClient( 6521):     "reason": "required",
W/ApiaryClient( 6521):     "message": "Login Required",
W/ApiaryClient( 6521):     "locationType": "header",
W/ApiaryClient( 6521):     "location": "Authorization"
W/ApiaryClient( 6521):    }
W/ApiaryClient( 6521):   ],
W/ApiaryClient( 6521):   "code": 401,
W/ApiaryClient( 6521):   "message": "Login Required"
W/ApiaryClient( 6521):  }
W/ApiaryClient( 6521): }
W/ApiaryClient( 6521): errCount = 3: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6521): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=127592504003830964&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6521): Headers:
W/ApiaryClient( 6521): accept-encoding: [gzip]
W/ApiaryClient( 6521): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6521): gdata-version: 2
,I/GLSUser ( 2166): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.talk, service: oauth2:https://www.googleapis.com/auth/chat https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/hangouts https://www.googleapis.com/auth/identity.plus.page.impersonation https://www.googleapis.com/auth/chat.native
I/GLSUser ( 2166): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/chat https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/hangouts https://www.googleapis.com/auth/identity.plus.page.impersonation https://www.googleapis.com/auth/chat.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2166): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2166): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2166): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
E/Babel   ( 6898): UserRecoverableAuthException.
E/Babel   ( 6898): cfq: BadAuthentication
E/Babel   ( 6898): 	at cfn.a(Unknown Source)
E/Babel   ( 6898): 	at f.a(PG:191)
E/Babel   ( 6898): 	at ava.a(PG:88)
E/Babel   ( 6898): 	at ava.a(PG:128)
E/Babel   ( 6898): 	at bjs.a(PG:255)
E/Babel   ( 6898): 	at bep.a(PG:602)
E/Babel   ( 6898): 	at bep.a(PG:469)
E/Babel   ( 6898): 	at bpo.run(PG:1141)
E/Babel   ( 6898): Error getting auth token
E/Babel   ( 6898): bxl
E/Babel   ( 6898): 	at f.a(PG:201)
E/Babel   ( 6898): 	at ava.a(PG:88)
E/Babel   ( 6898): 	at ava.a(PG:128)
E/Babel   ( 6898): 	at bjs.a(PG:255)
E/Babel   ( 6898): 	at bep.a(PG:602)
E/Babel   ( 6898): 	at bep.a(PG:469)
E/Babel   ( 6898): 	at bpo.run(PG:1141)
I/Babel_RequestWriter( 6898): error sending REQ[fc:8; creat:1454702476661; type:bev-468162471]; took 114 ms (error code == 100)
,E/Babel   ( 6898): Account registration failedRedacted-21
E/Babel   ( 6898): bph: null -- null
E/Babel   ( 6898): 	at ava.a(PG:120)
E/Babel   ( 6898): 	at ava.a(PG:128)
E/Babel   ( 6898): 	at bjs.a(PG:255)
E/Babel   ( 6898): 	at bep.a(PG:602)
E/Babel   ( 6898): 	at bep.a(PG:469)
E/Babel   ( 6898): 	at bpo.run(PG:1141)
I/Babel   ( 6898): Account setup failed with error state:106 account:Redacted-21
I/Babel   ( 6898): Account sign in complete with state 106account: Redacted-21
I/art     ( 6898): Note: end time exceeds epoch: 
,I/GLSUser ( 2166): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.talk, service: oauth2:https://www.googleapis.com/auth/chat https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/hangouts https://www.googleapis.com/auth/identity.plus.page.impersonation https://www.googleapis.com/auth/chat.native
,I/GLSUser ( 2166): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/chat https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/hangouts https://www.googleapis.com/auth/identity.plus.page.impersonation https://www.googleapis.com/auth/chat.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2166): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2166): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2166): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/art     ( 1032): Explicit concurrent mark sweep GC freed 17877(818KB) AllocSpace objects, 5(592KB) LOS objects, 33% free, 44MB/66MB, paused 1.452ms total 71.345ms
,W/ResourcesManager( 2166): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
V/NotificationService( 1032): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1032): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1032): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1032): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1032): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
E/Babel   ( 6898): Unexpected exception while authenticating.
E/Babel   ( 6898): cfr: User intervention required. Notification has been pushed.
E/Babel   ( 6898): 	at cfn.b(Unknown Source)
E/Babel   ( 6898): 	at cfn.a(Unknown Source)
E/Babel   ( 6898): 	at f.a(PG:188)
E/Babel   ( 6898): 	at ava.b(PG:143)
E/Babel   ( 6898): 	at bnr.run(PG:5415)
E/Babel   ( 6898): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/Babel   ( 6898): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/Babel   ( 6898): 	at java.lang.Thread.run(Thread.java:818)
D/LgeQuickCoverNLService( 1397): onNotificationPosted
D/SmartCoverUpdateMonitor( 1397): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1397): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1397): handleNotificationPosted(true)
D/QuickCircle( 1397): onNotificationPosted() : isPosted true
,D/LgeQuickCoverNotificationData( 1397): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
,D/LgeQuickCoverNotificationData( 1397): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
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
D/QuickStatusbarLayout( 1397): Notification difference=198
D/QuickStatusbarLayout( 1397): child = android.widget.LinearLayout{2b2bce9 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,W/ProcessCpuTracker( 1032): Skipping unknown process pid 6943,
,E/BooksSync( 6521): Soft error: 
E/BooksSync( 6521): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 6521): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=127592504003830964&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 6521): Headers:
E/BooksSync( 6521): accept-encoding: [gzip]
E/BooksSync( 6521): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 6521): gdata-version: 2
E/BooksSync( 6521): 
E/BooksSync( 6521): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 6521): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 6521): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 6521): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 6521): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 6521): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 6521): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 6521): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 6521): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 6521): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 6521): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 6521): {
E/BooksSync( 6521):  "error": {
E/BooksSync( 6521):   "errors": [
E/BooksSync( 6521):    {
E/BooksSync( 6521):     "domain": "global",
E/BooksSync( 6521):     "reason": "required",
E/BooksSync( 6521):     "message": "Login Required",
E/BooksSync( 6521):     "locationType": "header",
E/BooksSync( 6521):     "location": "Authorization"
E/BooksSync( 6521):    }
E/BooksSync( 6521):   ],
E/BooksSync( 6521):   "code": 401,
E/BooksSync( 6521):   "message": "Login Required"
E/BooksSync( 6521):  }
E/BooksSync( 6521): }
E/BooksSync( 6521): 
E/BooksSync( 6521): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 6521): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 6521): 	... 8 more
,E/BooksSync( 6521): Sync error
E/BooksSync( 6521): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 6521): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=127592504003830964&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 6521): Headers:
E/BooksSync( 6521): accept-encoding: [gzip]
E/BooksSync( 6521): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 6521): gdata-version: 2
E/BooksSync( 6521): 
E/BooksSync( 6521): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 6521): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 6521): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 6521): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 6521): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 6521): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 6521): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 6521): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 6521): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 6521): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 6521): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 6521): {
E/BooksSync( 6521):  "error": {
E/BooksSync( 6521):   "errors": [
E/BooksSync( 6521):    {
E/BooksSync( 6521):     "domain": "global",
E/BooksSync( 6521):     "reason": "required",
E/BooksSync( 6521):     "message": "Login Required",
E/BooksSync( 6521):     "locationType": "header",
E/BooksSync( 6521):     "location": "Authorization"
E/BooksSync( 6521):    }
E/BooksSync( 6521):   ],
E/BooksSync( 6521):   "code": 401,
E/BooksSync( 6521):   "message": "Login Required"
E/BooksSync( 6521):  }
E/BooksSync( 6521): }
E/BooksSync( 6521): 
E/BooksSync( 6521): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 6521): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 6521): 	... 8 more
I/BooksSync( 6521): Finished books sync
I/ActivityManager( 1032): Killing 5825:com.uei.lg.quicksetsdk.maxq616/1000 (adj 15): empty #17
,D/SyncManager( 1032): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 26409, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,I/QRemote ( 5964): [RemoteControlManager.java:195:onServiceDisconnected()] oooooo start
W/System.err( 5964): android.os.DeadObjectException
W/System.err( 5964): 	at android.os.BinderProxy.transactNative(Native Method)
W/System.err( 5964): 	at android.os.BinderProxy.transact(Binder.java:496)
W/System.err( 5964): 	at com.uei.control.IControl.unregisterCallback(IControl.java:502)
W/System.err( 5964): 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:199)
W/System.err( 5964): 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
W/System.err( 5964): 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
W/System.err( 5964): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 5964): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 5964): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 5964): 	at android.app.ActivityThread.main(ActivityThread.java:5274)
W/System.err( 5964): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 5964): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 5964): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
W/System.err( 5964): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
E/UEI.SmartControl( 5964): IControl.unregisterCallback error: android.os.DeadObjectException
W/System.err( 5964): android.os.DeadObjectException
,W/System.err( 5964): 	at android.os.BinderProxy.transactNative(Native Method)
W/System.err( 5964): 	at android.os.BinderProxy.transact(Binder.java:496)
W/System.err( 5964): 	at com.uei.control.IControl.unregisterSetupReadyCallback(IControl.java:818)
W/System.err( 5964): 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:200)
W/System.err( 5964): 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
W/System.err( 5964): 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
W/System.err( 5964): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 5964): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 5964): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 5964): 	at android.app.ActivityThread.main(ActivityThread.java:5274)
W/System.err( 5964): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 5964): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 5964): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
W/System.err( 5964): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
E/UEI.SmartControl( 5964): IControl.unregisterSetupReadyCallback error: android.os.DeadObjectException
I/QRemote ( 5964): [RemoteControlManager.java:203:onServiceDisconnected()] oooooo Control unbind before rebinding.
W/libprocessgroup( 1032): failed to open /acct/uid_1000/pid_5825/cgroup.procs: No such file or directory
W/ActivityManager( 1032): Scheduling restart of crashed service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service in 1000ms
,D/QRemote ( 5964): [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]10
I/QRemote ( 5964): [RemoteControlManager.java:157:onBindIRService()] oooooo bind
,I/ActivityManager( 1032): Start proc com.uei.lg.quicksetsdk.maxq616 for service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service: pid=6961 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
D/QRemote ( 5964): [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
I/GAV2    ( 6521): Thread[GAThread,5,main]: No campaign data found.
,D/UEI.SmartControl( 6961): Quickset Services start...
,I/UEI.SmartControl( 6961): Manufacture = LGE
,D/UEI.SmartControl( 6961): Id = LGNevo
D/UEI.SmartControl( 6961): File observer start...
E/UEI.SmartControl( 6961): IR Port is disabled: false
D/UEI.SmartControl( 6961): Starting file observer...
D/UEI.SmartControl( 6961): Extracting JNI libs...
D/UEI.SmartControl( 6961): --- this system supports 32-bit or 64-bit only
D/UEI.SmartControl( 6961): --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
D/UEI.SmartControl( 6961): --- Checking lib: libqs_armeabi-v7a.zip
D/UEI.SmartControl( 6961): --- Extracting JNI libs: libqs_armeabi-v7a.zip
,I/UEI.SmartControl( 6961): --- Selecting new region: 6
,I/UEI.SmartControl( 6961): Model = LG-D855
D/UEI.SmartControl( 6961): QS Service created
I/UEI.SmartControl( 6961): Service initServices...
,D/UEI.SmartControl( 6961): QS start get config
D/UEI.SmartControl( 6961): Loading JNI Libs...
,I/UEI.SmartControl( 6961): Supports setup maps: true
,D/UEI.SmartControl( 6961): QS start statue = true Error code = 0
I/UEI.SmartControl( 6961): QS version = v2.7.10.1_RC1
I/UEI.SmartControl( 6961): QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
I/UEI.SmartControl( 6961): ### init IR Blaster...
D/serial_port( 6961): Configuring serial port
E/UEI.SmartControl( 6961): UEIBLaster setting for 616
I/UEI.SmartControl( 6961): Setting serial record hearder size = 2
I/UEI.SmartControl( 6961): configuring settings for MAXQ616
,I/UEI.SmartControl( 6961): Get version...
D/UEI.SmartControl( 6961): serial port data available: 21
,D/UEI.SmartControl( 6961): MAXQ616 A2-X4 software.
I/UEI.SmartControl( 6961): IR Blaster version: 256702256704300002
I/UEI.SmartControl( 6961): QS saving settings...
D/UEI.SmartControl( 6961): IR Blaster version: 25672567
,D/UEI.SmartControl( 6961): serial port data available: 4
,E/WifiStateMachine( 1032):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-62 f=2412 sc=60 link=72 tx=20.3, 0.0, 0.0  rx=17.6 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1278997171] gl rssi=-62 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
E/WifiStateMachine( 1032):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-62 f=2412 sc=60 link=72 tx=20.3, 0.0, 0.0  rx=17.6 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-1278997170] gl rssi=-62 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
D/WifiNative-wlan0( 1032): doString: [SIGNAL_POLL]
,W/ContextImpl( 6961): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
I/UEI.SmartControl( 6961): Device manager: loading config....
E/UEI.SmartControl( 6961): Services init done
D/UEI.SmartControl( 6961): QS Service init finished
D/UEI.SmartControl( 6961): QS Service version name: 2.1.91
D/UEI.SmartControl( 6961): QS Service version code: 201091
,D/UEI.SmartControl( 6961): ----------- loading internal config...
D/UEI.SmartControl( 6961): Service requested: Control
D/UEI.SmartControl( 6961): Request IControl service: devices are loaded...
E/UEI.SmartControl( 6961): Loading SETTINGS...
I/QRemote ( 5964): [RemoteControlManager.java:183:onServiceConnected()] oooooo start
I/ActivityManager( 1032): Killing 6193:com.android.settings/1000 (adj 15): empty #17
,I/UEI.SmartControl( 6961): ------ IControl API: 11
I/UEI.SmartControl( 6961): Registering callback...
I/UEI.SmartControl( 6961): ------ IControl API: 19
I/UEI.SmartControl( 6961): Registering Services Ready callback...
D/UEI.SmartControl( 6961): -- Open brand translation xml: brands_translations_ko
I/UEI.SmartControl( 6961): Notify AllClients services are ready: 0
D/UEI.SmartControl( 6961): -----service ready thread exits
I/QRemote ( 5964): [RemoteControlManager.java:660:QSSetupIsReady()] oooooo 140517:sdkIsReady callback... get functions. Result:0
D/QRemote ( 5964): [RemoteControlManager.java:388:handleMessage()] oooooo 140510:START_SESSION
,D/QRemote ( 5964): [RemoteControlManager.java:394:handleMessage()] oooooo 140510:send retrieve msg
D/QRemote ( 5964): [RemoteControlManager.java:322:handleMessage()] oooooo 140510:handler call retrieveDevices
D/QRemote ( 5964): [RemoteControlManager.java:336:retrieveDevices()] oooooo retrieveDevices: start
I/UEI.SmartControl( 6961): ------ IControl API: 8
D/QRemote ( 5964): [RemoteControlManager.java:340:retrieveDevices()] oooooo retrieveDevices: 0
D/QRemote ( 5964): [RemoteControlManager.java:345:retrieveDevices()] oooooo retrieveDevices complete:true
D/QRemote ( 5964): [RemoteControlManager.java:353:retrieveDevices()] oooooo retrieveDevices: notifyDataSetChanged()
D/QRemote ( 5964): [QRemoteApplication.java:145:onRemoteControlStateChanged()] oooooo onRemoteControlStateChanged called in QRemoteApp
D/QRemote ( 5964): [QRemoteApplication.java:158:onRemoteControlStateChanged()] oooooo Widget count is [1]. send broadcast
D/QRemote ( 5964): [QRemoteApplication.java:160:onRemoteControlStateChanged()] oooooo Widget[0]:3
D/WifiService( 1032): Client connection lost with reason: 4
,W/libprocessgroup( 1032): failed to open /acct/uid_1000/pid_6193/cgroup.procs: No such file or directory
,D/UEI.SmartControl( 6961): Internal service binding...
D/QRemote ( 5964): [QRemoteApplication.java:188:onRemoteControlStateChanged()] oooooo 140526:onRemoteControlStateChanged&sdkIsReady. stop Service
V/QRemote ( 5964): [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
D/QRemote ( 5964): [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
,E/QRemote ( 5964): [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
D/QRemote ( 5964): [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
D/QRemote ( 5964): [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
D/QRemote ( 5964): [RemoteAppWidgetProvider.java:506:onUpdate()] oooooo 140510:RetrieveDevices complete. Start loading
D/QRemote ( 5964): [RemoteAppWidgetProvider.java:508:onUpdate()] oooooo 140510:appWidgetIds[0]:3 loading
D/QRemote ( 5964): [RemoteAppWidgetManager.java:41:startLoading()] oooooo 140518:widgetId[3] loading start at [1454714916287]
D/QRemote ( 5964): [RemoteAppWidgetManager.java:239:doInBackground()] oooooo 140407:doinBack arr:0
,V/QRemote ( 5964): [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.widget_ui_update
E/QRemote ( 5964): [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
D/QRemote ( 5964): [RemoteAppWidgetProvider.java:171:onReceive()] oooooo total:0
D/QRemote ( 5964): [RemoteAppWidgetProvider.java:172:onReceive()] oooooo selected:0
D/QRemote ( 5964): [RemoteAppWidgetProvider.java:173:onReceive()] oooooo arr:[]
D/QRemote ( 5964): [RemoteAppWidgetProvider.java:174:onReceive()] oooooo appWidgetId:3
D/QRemote ( 5964): [RemoteAppWidgetProvider.java:815:updateRemoteViews()] oooooo UpdateRemoteViews3:widgetId:3
D/QRemote ( 5964): [RemoteAppWidgetProvider.java:986:updateRemoteViews()] oooooo updateAppWidget5:widgetId:3]
I/GAV4    ( 6732): Thread[GAThread,5,main]: No campaign data found.
,I/ActivityManager( 1032): Killing 6550:com.lge.appbox.client/u0a11 (adj 15): empty #17
,W/libprocessgroup( 1032): failed to open /acct/uid_10011/pid_6550/cgroup.procs: No such file or directory
,E/WifiStateMachine( 1032):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-62 f=2412 sc=60 link=72 tx=12.2, 0.0, 0.0  rx=10.3 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1278994155] gl rssi=-62 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,E/WifiStateMachine( 1032):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-62 f=2412 sc=60 link=72 tx=12.2, 0.0, 0.0  rx=10.3 bcn=0 [on:0 tx:0 rx:0 period:4] from screen [on:0 period:-1278994151] gl rssi=-62 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,D/WifiNative-wlan0( 1032): doString: [SIGNAL_POLL]
,I/ActivityManager( 1032): Killing 4826:com.android.vending/u0a44 (adj 15): empty #17
,W/libprocessgroup( 1032): failed to open /acct/uid_10044/pid_4826/cgroup.procs: No such file or directory
,D/sensors_hal_Time( 1032): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1032): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1032): tsOffsetIs: Apps: 137832221619; DSPS: 4657075; Offset : -4305003109
,D/UEI.SmartControl( 6961): Internal timer expired: 1
,D/UEI.SmartControl( 6961): unbind internal service
,D/serial_port( 6961): close(fd = 25)
,I/UEI.SmartControl( 6961): Serial port is closed.
,E/WifiStateMachine( 1032):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-61 f=2412 sc=60 link=72 tx=6.6, 0.0, 0.0  rx=5.7 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1278991128] gl rssi=-61 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,E/WifiStateMachine( 1032):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-61 f=2412 sc=60 link=72 tx=6.6, 0.0, 0.0  rx=5.7 bcn=0 [on:0 tx:0 rx:0 period:4] from screen [on:0 period:-1278991124] gl rssi=-61 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,D/WifiNative-wlan0( 1032): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1032):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-61 f=2412 sc=60 link=72 tx=3.3, 0.0, 0.0  rx=2.8 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:-1278988102] gl rssi=-61 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1032):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-61 f=2412 sc=60 link=72 tx=3.3, 0.0, 0.0  rx=2.8 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-1278988092] gl rssi=-61 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1032): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1032):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-61 f=2412 sc=60 link=72 tx=2.1, 0.0, 0.0  rx=1.9 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1278985070] gl rssi=-61 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1032):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-61 f=2412 sc=60 link=72 tx=2.1, 0.0, 0.0  rx=1.9 bcn=0 [on:0 tx:0 rx:0 period:12] from screen [on:0 period:-1278985058] gl rssi=-61 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1032): doString: [SIGNAL_POLL]
I/[SystemUI]QPairHandler( 1452): onReceive = android.intent.action.PACKAGE_CHANGED
,D/SplitUIService( 1869): replaced split : contains_com.google.android.talk / true
,I/InputReader( 1032): Reconfiguring input devices.  changes=0x00000010
,D/SplitUIManager( 1869): split_name #11 / not available #0
I/SplitUIService( 1869): split app #11
,I/ActivityManager( 1032): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.manager.PreloadListManagerHelper: pid=7002 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,I/[SystemUI]QSlideListController( 1452): onReceive = android.intent.action.PACKAGE_CHANGED
I/[SystemUI]AppWidgetPanel(QRemoteWidgetPanel)( 1452): onReceive = android.intent.action.PACKAGE_CHANGED, packageName : com.google.android.talk
I/[LGHome]EVENT( 2069): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.talk flg=0x4000010 (has extras) }
,I/art     (  358): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 468us total 48.876ms
D/administrator( 1032): Handling package changes for user 0
,I/art     (  358): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 434us total 21.192ms
W/ResourcesManager( 2069): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
I/[LGHome]Launcher( 2069): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,I/art     (  358): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 405us total 19.898ms
I/AppUp4:AppBoxCP( 7002): onCreate
,W/AppUp4:DB( 7002):  [AppBoxDatabaseHelper] construct
I/AppUp4:DB( 7002):  setFingerPrint start
I/AppUp4:DB( 7002):  newfinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys SDK version = 21
I/AppUp4:DB( 7002):  beforefinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys
I/AppUp4:DB( 7002):  SDK version = 21
I/AppUp4:DB( 7002):  beforefinger == newfinger no write in DB
D/AppUp4:AppBoxApplication( 7002): AppBoxApplication onCreate()
,I/AppUp4:CustModeStarterReceiver( 7002): onReceive
D/LgDataFeature( 7002): LgDataFeature() Constructor: none
D/LgDataFeature( 7002): LgDataFeature() Constructor Done, null
I/NotificationService( 1032): action=android.intent.action.PACKAGE_CHANGED queryReplace=false
D/BackupManagerService( 1032): Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.talk flg=0x4000010 (has extras) }
,D/AppUp4:CustFacade( 7002): Context : android.app.ReceiverRestrictedContext@22c72bba
D/AppUp4:CustFacade( 7002): isCustomizationCompleted : false
D/AppUp4:CustFacade( 7002): isPhone : true
D/AppUp4:CustModeStarterReceiver( 7002): begin check event
I/AppUp4:CustModeStarterReceiver( 7002): Event For Nothing, skip.
W/ResourcesManager( 1032): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
I/ActivityManager( 1032): Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=7038 uid=10019 gids={50019, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
,I/ActivityManager( 1032): Killing 6131:com.lge.formmanager/u0a26 (adj 15): empty #17
W/ResourcesManager( 1032): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourceType( 1032): Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
,W/libprocessgroup( 1032): failed to open /acct/uid_10026/pid_6131/cgroup.procs: No such file or directory
I/[LGHome]EVENT( 2069): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
,W/ResourcesManager( 7038): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7038): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 7038): Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
,W/ResourcesManager( 7038): Asset path '/system/framework/lghiddenlibs.jar' does not exist or contains no resources.
W/ResourcesManager( 7038): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
I/SystemConfig( 7038): BUILD Country: EU
I/SystemConfig( 7038): BUILD Operator: OPEN
,I/ActivityManager( 1032): Killing 6683:com.lge.drmservice/u0a62 (adj 15): empty #17
,W/libprocessgroup( 1032): failed to open /acct/uid_10062/pid_6683/cgroup.procs: No such file or directory
,I/SystemConfig( 7038): pm.hasSystemFeature(com.lge.ims.rcs) = false
I/SystemConfig( 7038): existFile = false
I/SystemConfig( 7038): canReadFile = false
I/SystemConfig( 7038): systemFeature RCS result false
D/SystemConfig( 7038): refreshRcsSupport() :false
I/UpdateIcingCorporaServi( 4205): Updating corpora: APPS=com.google.android.talk, CONTACTS=MAYBE
,I/ActivityManager( 1032): Start proc com.lge.lockscreensettings for broadcast com.lge.lockscreensettings/.PackageIntentReceiver: pid=7063 uid=10080 gids={50080, 9997, 1028, 1015} abi=armeabi-v7a
V/SIM_STK ( 1032): Menu title from STK is T-Mobile
W/ResourcesManager( 4205): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/UpdateIcingCorporaServi( 4205): UpdateCorporaTask done [took 75 ms] updated apps [took 75 ms] 
I/LockScreenSettings( 7063): Wallpaper base directory = /data/data/com.lge.lockscreensettings/files/
,D/LockScreenSettings( 7063): Quick window widget present in DB = com.lge.clock.quickcover.QuickCoverSettingActivity  true
,D/LockScreenSettings( 7063): Quick window widget present in DB = com.lge.camera.app.QuickWindowCameraActivity  true
D/LockScreenSettings( 7063): Quick window widget present in DB = com.android.contacts.activities.QuickCircleActivity  true
D/LockScreenSettings( 7063): Quick window widget present in DB = com.android.mms.quickcover.QuickCoverActivity  true
D/LockScreenSettings( 7063): Quick window widget present in DB = com.lge.music.MusicQuickCircle  true
D/LockScreenSettings( 7063): Quick window widget present in DB = com.lge.lifetracker.QuickCover  true
,I/ActivityManager( 1032): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=7081 uid=10044 gids={50044, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager( 1032): Killing 6594:com.android.chrome/u0a57 (adj 15): empty #17
W/libprocessgroup( 1032): failed to open /acct/uid_10057/pid_6594/cgroup.procs: No such file or directory
,D/Finsky  ( 7081): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,D/LgDataFeature( 7081): LgDataFeature() Constructor: none
D/LgDataFeature( 7081): LgDataFeature() Constructor Done, null
,D/Finsky  ( 7081): [1] DailyHygiene.goMakeHygieneIfDirty: Dirty, need more hygiene.
,I/ActivityManager( 1032): Start proc com.google.android.gms:car for service com.google.android.gms/.car.CarService: pid=7117 uid=10005 gids={50005, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
,W/Settings( 7081): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 7081): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
W/ResourcesManager( 7117): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 7117): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/DownloadManager( 3285): starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3285): created cursor android.database.sqlite.SQLiteCursor@3e188be on behalf of 7081
D/Finsky  ( 7081): [1] 2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 7081): [1] 2.run: Finished loading 1 libraries.
,D/Finsky  ( 7081): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,I/MultiDex( 7117): VM with version 2.1.0 has multidex support
I/MultiDex( 7117): install
I/MultiDex( 7117): VM has multidex support, MultiDex support library is disabled.
D/PackageBroadcastService( 2361): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.talk
,D/Finsky  ( 7081): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
V/JNIHelp ( 7117): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,I/ActivityManager( 1032): Start proc com.google.android.gms.wearable for service com.google.android.gms/.wearable.service.WearableControlService: pid=7147 uid=10005 gids={50005, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
,I/ActivityManager( 1032): Killing 6732:com.google.android.apps.magazines/u0a93 (adj 15): empty #17
W/ActivityThread( 7117): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 7117): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@1f559122: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 7117): Installed default security provider GmsCore_OpenSSL
,I/PeopleContactsSync( 2361): CP2 sync disabled
W/libprocessgroup( 1032): failed to open /acct/uid_10093/pid_6732/cgroup.procs: No such file or directory
,D/GCM     ( 2166): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
D/AuthorizationBluetoothService( 2166): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
V/GmsCoreStatsServiceLauncher( 2361): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,W/ResourcesManager( 7147): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 7147): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,D/LocationInitializer( 2361): Restart initialization of location
,I/MultiDex( 7147): VM with version 2.1.0 has multidex support
I/MultiDex( 7147): install
I/MultiDex( 7147): VM has multidex support, MultiDex support library is disabled.
,E/WifiStateMachine( 1032):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-61 f=2412 sc=60 link=72 tx=1.6, 0.0, 0.0  rx=1.5 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1278982038] gl rssi=-61 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1032):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-61 f=2412 sc=60 link=72 tx=1.6, 0.0, 0.0  rx=1.5 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-1278982037] gl rssi=-61 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1032): doString: [SIGNAL_POLL]
,V/JNIHelp ( 7147): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
I/art     ( 2361): Explicit concurrent mark sweep GC freed 17369(1271KB) AllocSpace objects, 20(320KB) LOS objects, 49% free, 32MB/64MB, paused 1.100ms total 59.881ms
,W/ActivityThread( 7147): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 7147): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@1f559122: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 7147): Installed default security provider GmsCore_OpenSSL
,W/NativeLibraryUtils( 7147): Install did not work
W/NativeLibraryUtils( 7147): java.io.IOException: fcntl failed: EAGAIN (Try again)
W/NativeLibraryUtils( 7147): 	at java.nio.FileChannelImpl.basicLock(FileChannelImpl.java:123)
W/NativeLibraryUtils( 7147): 	at java.nio.FileChannelImpl.tryLock(FileChannelImpl.java:181)
W/NativeLibraryUtils( 7147): 	at java.nio.channels.FileChannel.tryLock(FileChannel.java:584)
W/NativeLibraryUtils( 7147): 	at com.google.android.gms.common.util.ax.a(SourceFile:314)
W/NativeLibraryUtils( 7147): 	at com.google.android.gms.common.app.a.run(SourceFile:136)
W/NativeLibraryUtils( 7147): Caused by: android.system.ErrnoException: fcntl failed: EAGAIN (Try again)
W/NativeLibraryUtils( 7147): 	at libcore.io.Posix.fcntlFlock(Native Method)
W/NativeLibraryUtils( 7147): 	at libcore.io.ForwardingOs.fcntlFlock(ForwardingOs.java:70)
W/NativeLibraryUtils( 7147): 	at java.nio.FileChannelImpl.basicLock(FileChannelImpl.java:121)
W/NativeLibraryUtils( 7147): 	... 4 more
,I/ActivityManager( 1032): Killing 6620:com.lge.email/u0a23 (adj 15): empty #17
D/WearableService( 7147): callingUid 10005, callindPid: 7147
,W/libprocessgroup( 1032): failed to open /acct/uid_10023/pid_6620/cgroup.procs: No such file or directory
,D/GCM     ( 2166): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
D/AuthorizationBluetoothService( 2166): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
V/GmsCoreStatsServiceLauncher( 2361): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,V/Finsky  ( 7081): [1] GearheadStateMonitor.onReady: sIsProjecting:false
E/MDM     ( 1814): [85] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,E/MDM     ( 1814): [86] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
D/LocationInitializer( 2361): Restart initialization of location
,V/AlarmManager( 1032): RTC_WAKEUP set : Alarm{d02b59c type 0 when 1454714931197 com.android.vending} when 1454714931197
,V/SIM_STK ( 1032): Menu title from STK is T-Mobile
,V/AlarmManager( 1032): RTC_WAKEUP set : Alarm{2ff06b7a type 0 when 1454714931787 com.android.vending} when 1454714931787
,D/Finsky  ( 7081): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
V/GLSActivity( 2166): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2166): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 2166): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2166): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2166): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2166): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/Finsky  ( 7081): [1] 1.onErrorResponse: Unable to preload experiments: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,V/GLSActivity( 2166): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/GLSUser ( 2166): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 2166): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2166): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2166): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2166): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 2166): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2166): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 2166): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2166): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2166): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2166): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/Finsky  ( 7081): [1] LibraryUpdateListener.onErrorResponse: Library replication failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,I/GLSUser ( 2166): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 2166): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2166): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2166): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2166): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/Finsky  ( 7081): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 7081): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 7081): [1] 5.onFinished: Scheduling replication attempt 3.
,V/SIM_STK ( 1032): Menu title from STK is T-Mobile
,V/GLSActivity( 2166): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2166): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 2166): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 2166): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2166): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2166): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/Finsky  ( 7081): [1] 2.onErrorResponse: Update check failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,D/Finsky  ( 7081): [1] DailyHygiene.logDeviceFeaturesAndContinue: Logging device features
D/Finsky  ( 7081): [1] DailyHygiene.flushEventLogsAndContinue: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 7081): [1] DailyHygiene.reschedule: Giving up. (failures=6)
D/DeviceConnectionService( 1814): client connected with version: 7571000
,E/WifiStateMachine( 1032):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-61 f=2412 sc=60 link=72 tx=1.8, 0.0, 0.0  rx=1.2 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1278979021] gl rssi=-61 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1032):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-61 f=2412 sc=60 link=72 tx=1.8, 0.0, 0.0  rx=1.2 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-1278979011] gl rssi=-61 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1032): doString: [SIGNAL_POLL]
I/ActivityManager( 1032): Killing 5124:com.wsandroid.suite.lge/1000 (adj 15): empty #17
,W/libprocessgroup( 1032): failed to open /acct/uid_1000/pid_5124/cgroup.procs: No such file or directory
,E/WifiStateMachine( 1032):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-61 f=2412 sc=60 link=72 tx=1.4, 0.0, 0.0  rx=1.1 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1278975990] gl rssi=-61 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1032):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-61 f=2412 sc=60 link=72 tx=1.4, 0.0, 0.0  rx=1.1 bcn=0 [on:0 tx:0 rx:0 period:9] from screen [on:0 period:-1278975981] gl rssi=-61 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1032): doString: [SIGNAL_POLL]
,D/sensors_hal_Time( 1032): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1032): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1032): tsOffsetIs: Apps: 157833270153; DSPS: 5312469; Offset : -4304992434
,I/[SystemUI]TimeTickManager( 1452): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1452): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1452): called onTimeUpdated()
I/[SystemUI]Clock( 1452): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1452): called onTimeUpdated()
,I/[SystemUI]DateView( 1452): called onTimeUpdated()
,I/[SystemUI]DateView( 1452): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1452): handleTimeUpdate
,D/PowerManagerServiceEx( 1032): acquireWakeLockInternal: lock=937964813, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1032
,V/AlarmManager( 1032): ELAPSED_WAKEUP set : Alarm{332b58e2 type 2 when 158338 android} when 158338
D/[Concierge]Service( 2593): onStartCommand(). Type : 9
,D/PowerManagerServiceEx( 1032): releaseWakeLockInternal: lock=937964813 [*alarm*], flags=0x0
,E/WifiStateMachine( 1032):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-62 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.6 bcn=0 [on:0 tx:0 rx:0 period:3005] from screen [on:0 period:-1278972956] gl rssi=-62 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1032):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-62 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.6 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1278972953] gl rssi=-62 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1032): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1032):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-62 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1278969927] gl rssi=-62 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1032):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-62 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1278969924] gl rssi=-62 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1032): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1032):  ConnectedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 1 0
,E/WifiStateMachine( 1032):  L2ConnectedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 1 0
E/WifiStateMachine( 1032):  ConnectModeState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 1 0
E/WifiStateMachine( 1032):  DriverStartedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 1 0
E/WifiStateMachine( 1032):  SupplicantStartedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 1 0
,E/WifiStateMachine( 1032):  DefaultState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 1 0
,E/WifiStateMachine( 1032):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-62 f=2412 sc=60 link=72 tx=0.9, 0.0, 0.0  rx=0.9 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1278966897] gl rssi=-62 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1032):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-62 f=2412 sc=60 link=72 tx=0.9, 0.0, 0.0  rx=0.9 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1278966894] gl rssi=-62 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1032): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1032):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-62 f=2412 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1278963869] gl rssi=-62 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1032):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-62 f=2412 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1278963866] gl rssi=-62 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1032): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1032):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-62 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1278960840] gl rssi=-62 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1032):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-62 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-1278960830] gl rssi=-62 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1032): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1032):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-62 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1278957802] gl rssi=-62 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1032):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-62 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:12] from screen [on:0 period:-1278957790] gl rssi=-62 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1032): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1032):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-62 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1278954769] gl rssi=-62 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1032):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-62 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:4] from screen [on:0 period:-1278954765] gl rssi=-62 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1032): doString: [SIGNAL_POLL]
,D/sensors_hal_Time( 1032): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1032): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1032): tsOffsetIs: Apps: 177835146812; DSPS: 5967891; Offset : -4305007630
,E/WifiStateMachine( 1032):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-62 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1278951741] gl rssi=-62 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1032):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-62 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-1278951731] gl rssi=-62 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1032): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1032):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-62 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1278948711] gl rssi=-62 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1032):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-62 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:12] from screen [on:0 period:-1278948699] gl rssi=-62 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1032): doString: [SIGNAL_POLL]
,V/AlarmManager( 1032): RTC_WAKEUP set : Alarm{271f7f30 type 0 when 1454714952279 com.android.vending} when 1454714952279
,V/AlarmManager( 1032): ELAPSED_WAKEUP set : Alarm{1049f7a9 type 2 when 178610 com.google.android.gms} when 178610
,V/SIM_STK ( 1032): Menu title from STK is T-Mobile
,I/art     ( 1032): Explicit concurrent mark sweep GC freed 48007(2MB) AllocSpace objects, 3(176KB) LOS objects, 33% free, 44MB/66MB, paused 2.310ms total 175.609ms
V/GLSActivity( 2166): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GoogleURLConnFactory( 2166): Using platform SSLCertificateSocketFactory
,I/VacuumService( 2166): Vacuum at: now=1454714967286 tag=VacuumService
,V/GLSActivity( 2166): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GoogleURLConnFactory( 2166): Using platform SSLCertificateSocketFactory
,W/Uploader( 2166): No account for auth token provided
E/WifiStateMachine( 1032):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-62 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1278945678] gl rssi=-62 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1032):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-62 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-1278945677] gl rssi=-62 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1032): doString: [SIGNAL_POLL]
,I/art     ( 2166): Explicit concurrent mark sweep GC freed 31437(1864KB) AllocSpace objects, 8(896KB) LOS objects, 51% free, 30MB/62MB, paused 2.033ms total 90.016ms
,D/libc-netbsd(  311): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  311): res_queryN name = play.googleapis.com, class = 1, type = 1
I/GLSUser ( 2166): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 2166): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2166): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 2166): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
D/libc-netbsd(  311): res_queryN name = play.googleapis.com succeed
V/GLSActivity( 2166): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/Finsky  ( 7081): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 7081): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 7081): [1] 5.onFinished: Scheduling replication attempt 4.
,W/Uploader( 2166): No account for auth token provided
,W/Uploader( 2166): No account for auth token provided
,W/Uploader( 2166):  no longer exists, so no auth token.
,W/Uploader( 2166): No account for auth token provided
,W/Uploader( 2166): No account for auth token provided
,V/AlarmManager( 1032): ELAPSED_WAKEUP set : Alarm{24287e89 type 2 when 188428 android} when 188428
,I/BooksSync( 6521): Starting books sync
,D/BooksSync( 6521): started syncMyEbooks
,V/GLSActivity( 2166): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2166): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2166): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2166): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2166): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2166): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1032): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1032): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1032): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1032): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1032): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
W/GLSActivity( 2166): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2166): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2166): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2166): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2166): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2166): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2166): 	at android.os.Binder.execTransact(Binder.java:446)
D/LgeQuickCoverNLService( 1397): onNotificationPosted
E/BooksAccountManager( 6521): Authentication error
E/BooksAccountManager( 6521): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6521): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6521): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6521): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6521): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6521): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6521): null auth token
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
,D/LgeQuickCoverNotificationData( 1397): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1397): updateNotificationData: count=3
I/GLSUser ( 2166): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.syncadapters.contacts, service: cp
I/GLSUser ( 2166): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> cp without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2166): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 2166): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
D/QuickStatusbarLayout( 1397): Notification difference=198
D/QuickStatusbarLayout( 1397): child = android.widget.LinearLayout{2b2bce9 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
V/GLSActivity( 2166): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1032): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1032): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1032): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1032): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1032): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
W/GLSActivity( 2166): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2166): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2166): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2166): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2166): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2166): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2166): 	at android.os.Binder.execTransact(Binder.java:446)
D/ContactsSyncAdapter( 2166): innerSync failed
D/ContactsSyncAdapter( 2166): com.google.wireless.gdata2.client.AuthenticationException: unable to get auth token android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
D/ContactsSyncAdapter( 2166): 	at com.google.android.syncadapters.contacts.AuthInfo.getAuthToken(AuthInfo.java:45)
D/ContactsSyncAdapter( 2166): 	at com.google.android.syncadapters.contacts.ContactsSyncAdapter.innerPerformSync(ContactsSyncAdapter.java:263)
D/ContactsSyncAdapter( 2166): 	at com.google.android.syncadapters.contacts.ContactsSyncAdapter.onPerformLoggedSync(ContactsSyncAdapter.java:168)
D/ContactsSyncAdapter( 2166): 	at com.google.android.common.LoggingThreadedSyncAdapter.onPerformSync(LoggingThreadedSyncAdapter.java:33)
D/ContactsSyncAdapter( 2166): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
D/ContactsSyncAdapter( 2166): Caused by: android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
D/ContactsSyncAdapter( 2166): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
D/ContactsSyncAdapter( 2166): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
D/ContactsSyncAdapter( 2166): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
D/ContactsSyncAdapter( 2166): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
D/ContactsSyncAdapter( 2166): 	at android.os.Binder.execTransact(Binder.java:446)
,W/ApiaryClient( 6521): Error response from books API: {
W/ApiaryClient( 6521):  "error": {
W/ApiaryClient( 6521):   "errors": [
W/ApiaryClient( 6521):    {
W/ApiaryClient( 6521):     "domain": "global",
W/ApiaryClient( 6521):     "reason": "required",
W/ApiaryClient( 6521):     "message": "Login Required",
W/ApiaryClient( 6521):     "locationType": "header",
W/ApiaryClient( 6521):     "location": "Authorization"
W/ApiaryClient( 6521):    }
W/ApiaryClient( 6521):   ],
W/ApiaryClient( 6521):   "code": 401,
W/ApiaryClient( 6521):   "message": "Login Required"
W/ApiaryClient( 6521):  }
W/ApiaryClient( 6521): }
,D/LgeQuickCoverNLService( 1397): onNotificationPosted
W/ApiaryClient( 6521): errCount = 1: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6521): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-5578191707498781264&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6521): Headers:
W/ApiaryClient( 6521): accept-encoding: [gzip]
W/ApiaryClient( 6521): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6521): gdata-version: 2
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
D/SyncManager( 1032): failed sync operation thalitester@gmail.com u0 (com.google), com.android.contacts, LOCAL, currentRunTime 161922, reason: 10019, SyncResult: stats [ numAuthExceptions: 1]
D/LgeQuickCoverOverlayWindow( 1397): [native noti] inex =  1
D/SyncManager( 1032): not retrying sync operation because the error is a hard error: thalitester@gmail.com u0 (com.google), com.android.contacts, LOCAL, currentRunTime 251858, reason: 10019
D/LgeQuickCoverNotificationData( 1397): isNotificationForCurrentUser : true
,D/LgeQuickCoverOverlayWindow( 1397): [native noti] inex =  2
,D/LgeQuickCoverNotificationData( 1397): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1397): updateNotificationData: count=3
D/QuickStatusbarLayout( 1397): Notification difference=198
D/QuickStatusbarLayout( 1397): child = android.widget.LinearLayout{2b2bce9 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,E/WifiStateMachine( 1032):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-62 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3005] from screen [on:0 period:-1278942660] gl rssi=-62 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1032):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-62 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:4] from screen [on:0 period:-1278942656] gl rssi=-62 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1032): doString: [SIGNAL_POLL]
V/GLSActivity( 2166): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2166): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2166): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2166): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2166): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2166): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1032): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1032): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1032): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1032): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1032): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
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
W/GLSActivity( 2166): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2166): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2166): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2166): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2166): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2166): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2166): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 6521): Authentication error
E/BooksAccountManager( 6521): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6521): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6521): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6521): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6521): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6521): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6521): null auth token
D/QuickStatusbarLayout( 1397): Notification difference=198
D/QuickStatusbarLayout( 1397): child = android.widget.LinearLayout{2b2bce9 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,W/ApiaryClient( 6521): Error response from books API: {
W/ApiaryClient( 6521):  "error": {
W/ApiaryClient( 6521):   "errors": [
W/ApiaryClient( 6521):    {
W/ApiaryClient( 6521):     "domain": "global",
W/ApiaryClient( 6521):     "reason": "required",
W/ApiaryClient( 6521):     "message": "Login Required",
W/ApiaryClient( 6521):     "locationType": "header",
W/ApiaryClient( 6521):     "location": "Authorization"
W/ApiaryClient( 6521):    }
W/ApiaryClient( 6521):   ],
W/ApiaryClient( 6521):   "code": 401,
W/ApiaryClient( 6521):   "message": "Login Required"
W/ApiaryClient( 6521):  }
W/ApiaryClient( 6521): }
,W/ApiaryClient( 6521): errCount = 2: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6521): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-5578191707498781264&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6521): Headers:
W/ApiaryClient( 6521): accept-encoding: [gzip]
W/ApiaryClient( 6521): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6521): gdata-version: 2
,V/GLSActivity( 2166): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2166): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2166): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2166): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2166): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2166): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1032): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1032): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1032): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1032): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1032): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
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
W/GLSActivity( 2166): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2166): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2166): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2166): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2166): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2166): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2166): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 6521): Authentication error
E/BooksAccountManager( 6521): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6521): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6521): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6521): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6521): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6521): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6521): null auth token
D/QuickStatusbarLayout( 1397): Notification difference=198
D/QuickStatusbarLayout( 1397): child = android.widget.LinearLayout{2b2bce9 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,W/ApiaryClient( 6521): Error response from books API: {
W/ApiaryClient( 6521):  "error": {
W/ApiaryClient( 6521):   "errors": [
W/ApiaryClient( 6521):    {
W/ApiaryClient( 6521):     "domain": "global",
W/ApiaryClient( 6521):     "reason": "required",
W/ApiaryClient( 6521):     "message": "Login Required",
W/ApiaryClient( 6521):     "locationType": "header",
W/ApiaryClient( 6521):     "location": "Authorization"
W/ApiaryClient( 6521):    }
W/ApiaryClient( 6521):   ],
W/ApiaryClient( 6521):   "code": 401,
W/ApiaryClient( 6521):   "message": "Login Required"
W/ApiaryClient( 6521):  }
W/ApiaryClient( 6521): }
,W/ApiaryClient( 6521): errCount = 3: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6521): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-5578191707498781264&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6521): Headers:
W/ApiaryClient( 6521): accept-encoding: [gzip]
W/ApiaryClient( 6521): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6521): gdata-version: 2
,E/WifiStateMachine( 1032):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-62 f=2412 sc=60 link=72 tx=12.2, 0.0, 0.0  rx=8.2 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1278939644] gl rssi=-62 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
E/WifiStateMachine( 1032):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-62 f=2412 sc=60 link=72 tx=12.2, 0.0, 0.0  rx=8.2 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1278939641] gl rssi=-62 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
D/WifiNative-wlan0( 1032): doString: [SIGNAL_POLL]
,E/BooksSync( 6521): Soft error: 
E/BooksSync( 6521): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 6521): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-5578191707498781264&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 6521): Headers:
E/BooksSync( 6521): accept-encoding: [gzip]
E/BooksSync( 6521): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 6521): gdata-version: 2
E/BooksSync( 6521): 
E/BooksSync( 6521): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 6521): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 6521): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 6521): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 6521): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 6521): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 6521): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 6521): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 6521): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 6521): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 6521): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 6521): {
E/BooksSync( 6521):  "error": {
E/BooksSync( 6521):   "errors": [
E/BooksSync( 6521):    {
E/BooksSync( 6521):     "domain": "global",
E/BooksSync( 6521):     "reason": "required",
E/BooksSync( 6521):     "message": "Login Required",
E/BooksSync( 6521):     "locationType": "header",
E/BooksSync( 6521):     "location": "Authorization"
E/BooksSync( 6521):    }
E/BooksSync( 6521):   ],
E/BooksSync( 6521):   "code": 401,
E/BooksSync( 6521):   "message": "Login Required"
E/BooksSync( 6521):  }
E/BooksSync( 6521): }
E/BooksSync( 6521): 
E/BooksSync( 6521): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 6521): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 6521): 	... 8 more
,E/BooksSync( 6521): Sync error
E/BooksSync( 6521): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 6521): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-5578191707498781264&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 6521): Headers:
E/BooksSync( 6521): accept-encoding: [gzip]
E/BooksSync( 6521): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 6521): gdata-version: 2
E/BooksSync( 6521): 
E/BooksSync( 6521): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 6521): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 6521): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 6521): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 6521): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 6521): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 6521): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 6521): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 6521): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 6521): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 6521): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 6521): {
E/BooksSync( 6521):  "error": {
E/BooksSync( 6521):   "errors": [
E/BooksSync( 6521):    {
E/BooksSync( 6521):     "domain": "global",
E/BooksSync( 6521):     "reason": "required",
E/BooksSync( 6521):     "message": "Login Required",
E/BooksSync( 6521):     "locationType": "header",
E/BooksSync( 6521):     "location": "Authorization"
E/BooksSync( 6521):    }
E/BooksSync( 6521):   ],
E/BooksSync( 6521):   "code": 401,
E/BooksSync( 6521):   "message": "Login Required"
E/BooksSync( 6521):  }
E/BooksSync( 6521): }
E/BooksSync( 6521): 
E/BooksSync( 6521): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 6521): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 6521): 	... 8 more
I/BooksSync( 6521): Finished books sync
D/SyncManager( 1032): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 164044, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,E/WifiStateMachine( 1032):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-62 f=2412 sc=60 link=72 tx=9.6, 0.0, 0.0  rx=7.1 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1278936615] gl rssi=-62 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,E/WifiStateMachine( 1032):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-62 f=2412 sc=60 link=72 tx=9.6, 0.0, 0.0  rx=7.1 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1278936612] gl rssi=-62 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
D/WifiNative-wlan0( 1032): doString: [SIGNAL_POLL]
,D/sensors_hal_Time( 1032): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1032): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1032): tsOffsetIs: Apps: 197837055448; DSPS: 6623313; Offset : -4304990980
,E/WifiStateMachine( 1032):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-62 f=2412 sc=60 link=72 tx=4.8, 0.0, 0.0  rx=3.5 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1278933589] gl rssi=-62 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1032):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-62 f=2412 sc=60 link=72 tx=4.8, 0.0, 0.0  rx=3.5 bcn=0 [on:0 tx:0 rx:0 period:4] from screen [on:0 period:-1278933585] gl rssi=-62 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1032): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1032):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-62 f=2412 sc=60 link=72 tx=2.9, 0.0, 0.0  rx=2.3 bcn=0 [on:0 tx:0 rx:0 period:3000] from screen [on:0 period:-1278930561] gl rssi=-62 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1032):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-62 f=2412 sc=60 link=72 tx=2.9, 0.0, 0.0  rx=2.3 bcn=0 [on:0 tx:0 rx:0 period:24] from screen [on:0 period:-1278930537] gl rssi=-62 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1032): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1032):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-62 f=2412 sc=60 link=72 tx=1.9, 0.0, 0.0  rx=1.6 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1278927518] gl rssi=-62 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1032):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-62 f=2412 sc=60 link=72 tx=1.9, 0.0, 0.0  rx=1.6 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1278927515] gl rssi=-62 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1032): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1032):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-62 f=2412 sc=60 link=72 tx=1.0, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:-1278924488] gl rssi=-62 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1032):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-62 f=2412 sc=60 link=72 tx=1.0, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1278924485] gl rssi=-62 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1032): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1032):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-62 f=2412 sc=60 link=72 tx=1.0, 0.0, 0.0  rx=0.9 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1278921459] gl rssi=-62 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1032):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-62 f=2412 sc=60 link=72 tx=1.0, 0.0, 0.0  rx=0.9 bcn=0 [on:0 tx:0 rx:0 period:12] from screen [on:0 period:-1278921447] gl rssi=-62 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1032): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1032):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-62 f=2412 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.5 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:-1278918426] gl rssi=-62 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1032):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-62 f=2412 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.5 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1278918423] gl rssi=-62 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1032): doString: [SIGNAL_POLL]
,V/AlarmManager( 1032): RTC_WAKEUP set : Alarm{ea0ec9e type 0 when 1454714987766 com.android.vending} when 1454714987766
,V/AlarmManager( 1032): ELAPSED_WAKEUP set : Alarm{22d1137f type 2 when 211907 android} when 211907
,V/SIM_STK ( 1032): Menu title from STK is T-Mobile
,V/GLSActivity( 2166): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2166): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 2166): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2166): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2166): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2166): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/Finsky  ( 7081): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 7081): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 7081): [1] 5.onFinished: Scheduling replication attempt 5.
E/WifiStateMachine( 1032):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-62 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3000] from screen [on:0 period:-1278915401] gl rssi=-62 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1032):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-62 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-1278915400] gl rssi=-62 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1032): doString: [SIGNAL_POLL]
,D/sensors_hal_Time( 1032): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1032): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1032): tsOffsetIs: Apps: 217838928619; DSPS: 7278735; Offset : -4305010185
,I/[SystemUI]TimeTickManager( 1452): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1452): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1452): called onTimeUpdated()
,I/[SystemUI]Clock( 1452): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1452): called onTimeUpdated()
,I/[SystemUI]DateView( 1452): called onTimeUpdated()
,I/[SystemUI]DateView( 1452): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1452): handleTimeUpdate
,D/PowerManagerServiceEx( 1032): acquireWakeLockInternal: lock=937964813, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1032
,V/AlarmManager( 1032): ELAPSED_WAKEUP set : Alarm{3f445c49 type 2 when 218500 android} when 218500
D/[Concierge]Service( 2593): onStartCommand(). Type : 9
,D/PowerManagerServiceEx( 1032): releaseWakeLockInternal: lock=937964813 [*alarm*], flags=0x0
,E/WifiStateMachine( 1032):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-62 f=2412 sc=60 link=72 tx=0.9, 0.0, 0.0  rx=0.9 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1278912389] gl rssi=-62 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1032):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-62 f=2412 sc=60 link=72 tx=0.9, 0.0, 0.0  rx=0.9 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1278912386] gl rssi=-62 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1032): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1032):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-62 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1278909365] gl rssi=-62 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1032):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-62 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1278909362] gl rssi=-62 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1032): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1032):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-62 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1278906338] gl rssi=-62 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1032):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-62 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1278906335] gl rssi=-62 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1032): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1032):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-62 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1278903309] gl rssi=-62 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1032):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-62 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1278903306] gl rssi=-62 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1032): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1032):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-62 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3000] from screen [on:0 period:-1278900282] gl rssi=-62 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1032):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-62 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-1278900281] gl rssi=-62 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1032): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1032):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-62 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:-1278897270] gl rssi=-62 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1032):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-62 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:9] from screen [on:0 period:-1278897261] gl rssi=-62 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1032): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1032):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-62 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1278894239] gl rssi=-62 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1032):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-62 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:4] from screen [on:0 period:-1278894235] gl rssi=-62 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1032): doString: [SIGNAL_POLL]
,D/sensors_hal_Time( 1032): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1032): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1032): tsOffsetIs: Apps: 237841416112; DSPS: 7934176; Offset : -4304994512
,E/WifiStateMachine( 1032):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-62 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1278891212] gl rssi=-62 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1032):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-62 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:2] from screen [on:0 period:-1278891210] gl rssi=-62 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1032): doString: [SIGNAL_POLL]
,V/AlarmManager( 1032): RTC_WAKEUP set : Alarm{1e9bda6f type 0 when 1454715017279 com.android.vending} when 1454715017279
,I/DigitalAppWidgetProvider( 6829): onReceive: com.android.deskclock.ON_QUARTER_HOUR
,V/DigitalAppWidgetProvider( 6829): startAlarmOnQuarterHour android.app.ReceiverRestrictedContext@26ac4986
,V/SIM_STK ( 1032): Menu title from STK is T-Mobile
,V/GLSActivity( 2166): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2166): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 2166): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2166): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2166): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2166): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/Finsky  ( 7081): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 7081): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 7081): [1] 5.onFinished: Giving up after 6 failures.
,E/WifiStateMachine( 1032):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-62 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3005] from screen [on:0 period:-1278888185] gl rssi=-62 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1032):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-62 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1278888182] gl rssi=-62 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1032): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1032):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-62 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:2999] from screen [on:0 period:-1278885165] gl rssi=-62 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1032):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-62 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-1278885164] gl rssi=-62 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1032): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1032):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-62 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1278882153] gl rssi=-62 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1032):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-62 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1278882150] gl rssi=-62 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1032): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1032):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-62 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1278879123] gl rssi=-62 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1032):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-62 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1278879120] gl rssi=-62 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1032): doString: [SIGNAL_POLL]
,V/AlarmManager( 1032): ELAPSED_WAKEUP set : Alarm{145fe9b9 type 2 when 253532 android} when 253532
,I/BooksSync( 6521): Starting books sync
,D/BooksSync( 6521): started syncMyEbooks
,V/GLSActivity( 2166): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     ( 1032): Explicit concurrent mark sweep GC freed 50072(2MB) AllocSpace objects, 6(608KB) LOS objects, 33% free, 44MB/66MB, paused 3.413ms total 165.985ms
,I/GLSUser ( 2166): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2166): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2166): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2166): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2166): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1032): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1032): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1032): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1032): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1032): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,D/LgeQuickCoverNLService( 1397): onNotificationPosted
W/GLSActivity( 2166): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2166): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2166): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2166): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2166): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2166): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2166): 	at android.os.Binder.execTransact(Binder.java:446)
D/SmartCoverUpdateMonitor( 1397): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1397): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1397): handleNotificationPosted(true)
,D/QuickCircle( 1397): onNotificationPosted() : isPosted true
,D/LgeQuickCoverNotificationData( 1397): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
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
E/BooksAccountManager( 6521): Authentication error
E/BooksAccountManager( 6521): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6521): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6521): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6521): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6521): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6521): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6521): null auth token
D/LgeQuickCoverOverlayWindow( 1397): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1397): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1397): updateNotificationData: count=3
,D/QuickStatusbarLayout( 1397): Notification difference=198
D/QuickStatusbarLayout( 1397): child = android.widget.LinearLayout{2b2bce9 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,W/ApiaryClient( 6521): Error response from books API: {
W/ApiaryClient( 6521):  "error": {
W/ApiaryClient( 6521):   "errors": [
W/ApiaryClient( 6521):    {
W/ApiaryClient( 6521):     "domain": "global",
W/ApiaryClient( 6521):     "reason": "required",
W/ApiaryClient( 6521):     "message": "Login Required",
W/ApiaryClient( 6521):     "locationType": "header",
W/ApiaryClient( 6521):     "location": "Authorization"
W/ApiaryClient( 6521):    }
W/ApiaryClient( 6521):   ],
W/ApiaryClient( 6521):   "code": 401,
W/ApiaryClient( 6521):   "message": "Login Required"
W/ApiaryClient( 6521):  }
W/ApiaryClient( 6521): }
,W/ApiaryClient( 6521): errCount = 1: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6521): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-8648918616328657663&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6521): Headers:
W/ApiaryClient( 6521): accept-encoding: [gzip]
W/ApiaryClient( 6521): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6521): gdata-version: 2
V/GLSActivity( 2166): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2166): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 2166): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2166): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2166): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2166): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1032): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1032): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1032): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1032): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1032): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
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
D/QuickStatusbarLayout( 1397): Notification difference=198
D/QuickStatusbarLayout( 1397): child = android.widget.LinearLayout{2b2bce9 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,W/GLSActivity( 2166): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2166): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2166): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2166): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2166): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2166): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2166): 	at android.os.Binder.execTransact(Binder.java:446)
E/BooksAccountManager( 6521): Authentication error
E/BooksAccountManager( 6521): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6521): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6521): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6521): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6521): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6521): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6521): null auth token
,W/ApiaryClient( 6521): Error response from books API: {
W/ApiaryClient( 6521):  "error": {
W/ApiaryClient( 6521):   "errors": [
W/ApiaryClient( 6521):    {
W/ApiaryClient( 6521):     "domain": "global",
W/ApiaryClient( 6521):     "reason": "required",
W/ApiaryClient( 6521):     "message": "Login Required",
W/ApiaryClient( 6521):     "locationType": "header",
W/ApiaryClient( 6521):     "location": "Authorization"
W/ApiaryClient( 6521):    }
W/ApiaryClient( 6521):   ],
W/ApiaryClient( 6521):   "code": 401,
W/ApiaryClient( 6521):   "message": "Login Required"
W/ApiaryClient( 6521):  }
W/ApiaryClient( 6521): }
,W/ApiaryClient( 6521): errCount = 2: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6521): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-8648918616328657663&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6521): Headers:
W/ApiaryClient( 6521): accept-encoding: [gzip]
W/ApiaryClient( 6521): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6521): gdata-version: 2
,E/WifiStateMachine( 1032):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-62 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1278876091] gl rssi=-62 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1032):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-62 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:9] from screen [on:0 period:-1278876082] gl rssi=-62 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1032): doString: [SIGNAL_POLL]
,V/GLSActivity( 2166): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2166): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2166): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 2166): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2166): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2166): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1032): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1032): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1032): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1032): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1032): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
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
W/GLSActivity( 2166): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2166): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2166): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2166): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2166): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2166): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2166): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 6521): Authentication error
E/BooksAccountManager( 6521): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6521): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6521): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6521): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6521): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6521): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6521): null auth token
D/QuickStatusbarLayout( 1397): Notification difference=198
D/QuickStatusbarLayout( 1397): child = android.widget.LinearLayout{2b2bce9 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,W/ApiaryClient( 6521): Error response from books API: {
W/ApiaryClient( 6521):  "error": {
W/ApiaryClient( 6521):   "errors": [
W/ApiaryClient( 6521):    {
W/ApiaryClient( 6521):     "domain": "global",
W/ApiaryClient( 6521):     "reason": "required",
W/ApiaryClient( 6521):     "message": "Login Required",
W/ApiaryClient( 6521):     "locationType": "header",
W/ApiaryClient( 6521):     "location": "Authorization"
W/ApiaryClient( 6521):    }
W/ApiaryClient( 6521):   ],
W/ApiaryClient( 6521):   "code": 401,
W/ApiaryClient( 6521):   "message": "Login Required"
W/ApiaryClient( 6521):  }
W/ApiaryClient( 6521): }
,W/ApiaryClient( 6521): errCount = 3: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6521): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-8648918616328657663&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6521): Headers:
W/ApiaryClient( 6521): accept-encoding: [gzip]
W/ApiaryClient( 6521): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6521): gdata-version: 2
,E/BooksSync( 6521): Soft error: 
E/BooksSync( 6521): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 6521): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-8648918616328657663&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 6521): Headers:
E/BooksSync( 6521): accept-encoding: [gzip]
E/BooksSync( 6521): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 6521): gdata-version: 2
E/BooksSync( 6521): 
E/BooksSync( 6521): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 6521): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 6521): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 6521): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 6521): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 6521): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 6521): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 6521): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 6521): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 6521): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 6521): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 6521): {
E/BooksSync( 6521):  "error": {
E/BooksSync( 6521):   "errors": [
E/BooksSync( 6521):    {
E/BooksSync( 6521):     "domain": "global",
E/BooksSync( 6521):     "reason": "required",
E/BooksSync( 6521):     "message": "Login Required",
E/BooksSync( 6521):     "locationType": "header",
E/BooksSync( 6521):     "location": "Authorization"
E/BooksSync( 6521):    }
E/BooksSync( 6521):   ],
E/BooksSync( 6521):   "code": 401,
E/BooksSync( 6521):   "message": "Login Required"
E/BooksSync( 6521):  }
E/BooksSync( 6521): }
E/BooksSync( 6521): 
E/BooksSync( 6521): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 6521): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 6521): 	... 8 more
,E/BooksSync( 6521): Sync error
E/BooksSync( 6521): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 6521): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-8648918616328657663&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 6521): Headers:
E/BooksSync( 6521): accept-encoding: [gzip]
E/BooksSync( 6521): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 6521): gdata-version: 2
E/BooksSync( 6521): 
E/BooksSync( 6521): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 6521): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 6521): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 6521): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 6521): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 6521): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 6521): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 6521): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 6521): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 6521): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 6521): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 6521): {
E/BooksSync( 6521):  "error": {
E/BooksSync( 6521):   "errors": [
E/BooksSync( 6521):    {
E/BooksSync( 6521):     "domain": "global",
E/BooksSync( 6521):     "reason": "required",
E/BooksSync( 6521):     "message": "Login Required",
E/BooksSync( 6521):     "locationType": "header",
E/BooksSync( 6521):     "location": "Authorization"
E/BooksSync( 6521):    }
E/BooksSync( 6521):   ],
E/BooksSync( 6521):   "code": 401,
E/BooksSync( 6521):   "message": "Login Required"
E/BooksSync( 6521):  }
E/BooksSync( 6521): }
E/BooksSync( 6521): 
E/BooksSync( 6521): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 6521): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 6521): 	... 8 more
I/BooksSync( 6521): Finished books sync
D/SyncManager( 1032): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 253532, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/sensors_hal_Time( 1032): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1032): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1032): tsOffsetIs: Apps: 257845828813; DSPS: 8589681; Offset : -4305006730
,E/WifiStateMachine( 1032):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-62 f=2412 sc=60 link=72 tx=3.4, 0.0, 0.0  rx=2.4 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:-1278873067] gl rssi=-62 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1032):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-62 f=2412 sc=60 link=72 tx=3.4, 0.0, 0.0  rx=2.4 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1278873064] gl rssi=-62 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1032): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1032):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-62 f=2412 sc=60 link=72 tx=3.7, 0.0, 0.0  rx=2.7 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1278870038] gl rssi=-62 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1032):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-62 f=2412 sc=60 link=72 tx=3.7, 0.0, 0.0  rx=2.7 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1278870035] gl rssi=-62 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1032): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1032):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-62 f=2412 sc=60 link=72 tx=2.3, 0.0, 0.0  rx=1.8 bcn=0 [on:0 tx:0 rx:0 period:3000] from screen [on:0 period:-1278867018] gl rssi=-62 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1032):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-62 f=2412 sc=60 link=72 tx=2.3, 0.0, 0.0  rx=1.8 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1278867015] gl rssi=-62 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1032): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1032):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-62 f=2412 sc=60 link=72 tx=1.2, 0.0, 0.0  rx=0.9 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1278863988] gl rssi=-62 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1032):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-62 f=2412 sc=60 link=72 tx=1.2, 0.0, 0.0  rx=0.9 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1278863985] gl rssi=-62 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1032): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1032):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-62 f=2412 sc=60 link=72 tx=1.1, 0.0, 0.0  rx=1.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1278860962] gl rssi=-62 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1032):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-62 f=2412 sc=60 link=72 tx=1.1, 0.0, 0.0  rx=1.0 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-1278860952] gl rssi=-62 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1032): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1032):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-62 f=2412 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.5 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1278857930] gl rssi=-62 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1032):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-62 f=2412 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.5 bcn=0 [on:0 tx:0 rx:0 period:12] from screen [on:0 period:-1278857918] gl rssi=-62 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1032): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1032):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-62 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3000] from screen [on:0 period:-1278854898] gl rssi=-62 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1032):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-62 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-1278854897] gl rssi=-62 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1032): doString: [SIGNAL_POLL]
,D/sensors_hal_Time( 1032): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1032): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1032): tsOffsetIs: Apps: 277847900836; DSPS: 9245109; Offset : -4305010162
,I/[SystemUI]TimeTickManager( 1452): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1452): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1452): called onTimeUpdated()
I/[SystemUI]Clock( 1452): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1452): called onTimeUpdated()
,I/[SystemUI]DateView( 1452): called onTimeUpdated()
,I/[SystemUI]DateView( 1452): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1452): handleTimeUpdate
,E/WifiStateMachine( 1032):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-62 f=2412 sc=60 link=72 tx=0.9, 0.0, 0.0  rx=0.9 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1278851886] gl rssi=-62 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1032):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-62 f=2412 sc=60 link=72 tx=0.9, 0.0, 0.0  rx=0.9 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1278851883] gl rssi=-62 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1032): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1032):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-62 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1278848860] gl rssi=-62 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1032):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-62 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:5] from screen [on:0 period:-1278848855] gl rssi=-62 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1032): doString: [SIGNAL_POLL]
,D/PowerManagerServiceEx( 1032): acquireWakeLockInternal: lock=937964813, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1032
,V/AlarmManager( 1032): ELAPSED_WAKEUP set : Alarm{dc16f37 type 2 when 283580 android} when 283580
D/[Concierge]Service( 2593): onStartCommand(). Type : 9
,D/PowerManagerServiceEx( 1032): releaseWakeLockInternal: lock=937964813 [*alarm*], flags=0x0
,E/WifiStateMachine( 1032):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-62 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1278845831] gl rssi=-62 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1032):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-62 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-1278845821] gl rssi=-62 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1032): doString: [SIGNAL_POLL]
I/jxcore-log( 6048): --= Surplus to requirements =--
I/jxcore-log( 6048): 
I/jxcore-log( 6048): ****TEST TOOK:  ms ****
I/jxcore-log( 6048): 
I/jxcore-log( 6048): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 6048): 
,D/AndroidRuntime( 7369): 
D/AndroidRuntime( 7369): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime( 7369): CheckJNI is OFF
D/AndroidRuntime( 7369): Calling main entry com.android.commands.pm.Pm
,I/ActivityManager( 1032): Force stopping com.test.thalitest appid=10311 user=-1: uninstall pkg
I/ActivityManager( 1032): Killing 6048:com.test.thalitest/u0a311 (adj 0): stop com.test.thalitest
,I/WindowState( 1032): WIN DEATH: Window{1ee50f21 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,D/WifiService( 1032): Client connection lost with reason: 4
D/InputDispatcher( 1032): Window went away: Window{1ee50f21 u0 com.test.thalitest/com.test.thalitest.MainActivity}
I/ActivityManager( 1032):   Force finishing activity ActivityRecord{1f9bda72 u0 com.test.thalitest/.MainActivity t4}
,W/PackageSettings( 1032): Skipping PackageSetting{1ae966be com.example.hello/10319} due to missing metadata
,E/GBMv2   (  332): DFP En is all cleared set to be enabled
W/ActivityManager( 1032): Spurious death for ProcessRecord{6c94ca4 6048:com.test.thalitest/u0a311}, curProc for 6048: null
,D/SplitWindowPolicy( 1942): updateActivityStateChanged: resumed=false, screenId=0, isScreenFull=false
D/SplitWindowPolicy( 1942): topRunningActivity=ActivityInfo{1ca02456 co.....Launcher}, taskId=3, activityType=1, bIsSplit=false
I/ActivityManager( 1032): Force stopping com.test.thalitest appid=10311 user=0: pkg removed
I/ActivityManager( 1032):   Force finishing activity ActivityRecord{1f9bda72 u0 com.test.thalitest/.MainActivity t4 f}
D/SplitWindowPolicy( 1942): updateActivityStateChanged: resumed=true, screenId=0, isScreenFull=false
W/ActivityManager( 1032): Duplicate finish request for ActivityRecord{1f9bda72 u0 com.test.thalitest/.MainActivity t4 f}
D/SplitWindowPolicy( 1942): topRunningActivity=ActivityInfo{2bc5dcd7 co.....Launcher}, taskId=3, activityType=1, bIsSplit=false
,I/[LGHome]EVENT( 2069): [Launcher.java:5338:onStart()]onStart
I/[LGHome]EVENT( 2069): [Launcher.java:903:onResume()]onResume
D/KeyguardModel( 1452): mPackageIntentReceiver, received action: android.intent.action.PACKAGE_REMOVED, sendingUserId:0
D/LIA_Service_RemotePackageHandler( 2015): onReceive action : android.intent.action.PACKAGE_REMOVED = package:com.test.thalitest
D/LIA_MrGDBLogger_PackageInfoDetector( 2702): [dreamwood]action: android.intent.action.PACKAGE_REMOVED, package: com.test.thalitest
W/GeofencerStateMachine( 1814): Ignoring removeGeofence because network location is disabled.
,I/InputReader( 1032): Reconfiguring input devices.  changes=0x00000010
W/System.err( 4160): android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
,W/System.err( 4160): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
W/System.err( 4160): 	at com.lge.mlt.MptOnAppWatcher$1.onReceive(MptOnAppWatcher.java:44)
W/System.err( 4160): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:956)
W/System.err( 4160): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 4160): 	at android.os.Handler.dispatchMessage(Handler.java:95)
E/LGBluetoothAvrcpQcomAdapter( 6105): [BTUI] [BTUI] onReceive()... android.intent.action.PACKAGE_REMOVED
D/LGBluetoothAvrcpQcomAdapter( 6105): [BTUI] [+] updateMediaPlayerInfo
W/System.err( 4160): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 4160): 	at android.app.ActivityThread.main(ActivityThread.java:5274)
W/System.err( 4160): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 4160): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 4160): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
W/System.err( 4160): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
I/art     ( 4205): Explicit concurrent mark sweep GC freed 21932(1270KB) AllocSpace objects, 0(0B) LOS objects, 34% free, 29MB/45MB, paused 474us total 54.072ms
V/SIM_STK ( 1032): Menu title from STK is T-Mobile
,I/ActivityManager( 1032): Start proc com.wsandroid.suite.lge for broadcast com.wsandroid.suite.lge/com.wavesecure.core.WSAndroidSystemIntentReceiver: pid=7399 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,I/[LGHome]EVENT( 2069): [LauncherModel.java:1352:startLoader()]startLoader isLaunching=true
I/[LGHome]Launcher.Model( 2069): [LauncherModel.java:1469:loadAndBindWorkspace()]loadAndBindWorkspace=0ms
I/art     ( 1032): Explicit concurrent mark sweep GC freed 23438(1410KB) AllocSpace objects, 6(480KB) LOS objects, 33% free, 44MB/66MB, paused 2.248ms total 123.266ms
,I/[LGHome]GBoardWebView( 2069): [GBoardWebView.java:306:loadCacheBitmapPostDelayed()]loadCacheBitmapPostDelayed() delay:1
D/ActionManagerService( 1904): notifyUserLog: 1000003
D/LIA_Informant_ActionManagerMessageHandler( 2702): handleMessage: what(1000) actionID(0x1000003)
D/KeyguardModel( 1452): package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
D/KeyguardModel( 1452): createShortcutInfo...
I/[LGHome]LGActivityUtil( 2069): [LGActivityUtil.java:319:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
I/[SystemUI]QSlideListController( 1452): onReceive = android.intent.action.PACKAGE_REMOVED
I/[LGHome]EVENT( 2069): [Launcher.java:1056:onResume()]onResume end
D/KeyguardModel( 1452): package = com.android.mms, class = com.android.mms.ui.ConversationList
D/KeyguardModel( 1452): createShortcutInfo...
I/[LGHome]EVENT( 2069): [Launcher.java:1114:onPause()]onPause
,D/ActionManagerService( 1904): notifyUserLog: 1000004
I/[LGHome]GBoardWebView( 2069): [GBoardWebView.java:247:writeCacheBitmapPostDelayed()]writeCacheBitmapPostDelayed() delay: we don't have a change point1
D/LIA_Informant_ActionManagerMessageHandler( 2702): handleMessage: what(1000) actionID(0x1000004)
V/BoardContentProvider( 2702): query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
V/SIM_STK ( 1032): Menu title from STK is T-Mobile
V/SIM_STK ( 1032): Menu title from STK is T-Mobile
W/ResourcesManager( 1452): Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
I/GBoardWebViewUtils( 2069): checkExpiredAndRemoveCard() card: GBoardCard = { id: mw_initial
I/GBoardWebViewUtils( 2069): , create_time: 1430558575574
I/GBoardWebViewUtils( 2069): , expire_time: 0
I/GBoardWebViewUtils( 2069): , raw_uri: file:///system/etc/mrg_default_forms/MyWellness/initial/initial.html?id=mw_initial
I/GBoardWebViewUtils( 2069): , category: com.lge.intent.category.gboard.MYWELLNESS
I/GBoardWebViewUtils( 2069): , display: false
I/GBoardWebViewUtils( 2069): , animation: false }
I/GBoardWebViewUtils( 2069): checkExpiredAndRemoveCard() card: GBoardCard = { id: dyk000
I/GBoardWebViewUtils( 2069): , create_time: 1430558575600
I/GBoardWebViewUtils( 2069): , expire_time: 0
I/GBoardWebViewUtils( 2069): , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
I/GBoardWebViewUtils( 2069): , category: com.lge.intent.category.gboard.DOYOUKNOW
I/GBoardWebViewUtils( 2069): , display: false
I/GBoardWebViewUtils( 2069): , animation: false }
I/GBoardWebViewUtils( 2069): checkExpiredAndRemoveCard() card: GBoardCard = { id: guide_1111111111116_1454599632914
I/GBoardWebViewUtils( 2069): , create_time: 1454599633839
I/GBoardWebViewUtils( 2069): , expire_time: 0
I/GBoardWebViewUtils( 2069): , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/0/userguide.html?id=guide_1111111111116_1454599632914&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
I/GBoardWebViewUtils( 2069): , category: com.lge.intent.category.gboard.DOYOUKNOW
I/GBoardWebViewUtils( 2069): , display: false
I/GBoardWebViewUtils( 2069): , animation: false }
W/ResourcesManager( 1452): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 1452): Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
W/ResourcesManager( 1452): Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
W/ResourceType( 1452): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1452): Failure retrieving resources for com.android.mms: Resource ID #0x0
I/[SystemUI]AppWidgetPanel(QRemoteWidgetPanel)( 1452): onReceive = android.intent.action.PACKAGE_REMOVED, packageName : com.test.thalitest
D/KeyguardModel( 1452): package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
D/KeyguardModel( 1452): createShortcutInfo...
D/WallpaperManager( 2069): suggestDesiredDimensions(2880, 2560) by package(com.lge.launcher2)
D/KeyguardModel( 1452): mPackageIntentReceiver, received action: android.intent.action.PACKAGE_FULLY_REMOVED, sendingUserId:0
I/SystemUI[Framework]( 1032): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x8000, pkg=com.android.systemui
W/PhoneWindowManagerEx( 1032): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx( 1032): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx( 1032): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework]( 1032): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@cba0975,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework]( 1032): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
W/ResourcesManager( 1452): Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
W/ResourcesManager( 1452): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourceType( 1452): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1452): Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
,D/KeyguardModel( 1452): package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
D/KeyguardModel( 1452): createShortcutInfo...
D/administrator( 1032): Handling package changes for user 0
I/[LGHome]EVENT( 2069): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
I/[LGHome]GBoardWebView( 2069): [GBoardWebView.java:321:loadCacheBitmap()]loadCacheBitmap()
W/ResourcesManager( 1452): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 1452): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 1452): Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
W/ResourcesManager( 1452): Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
D/SplitUIManager( 1869): split_name #11 / not available #0
D/SplitUIService( 1869): removed split : 
W/ResourceType( 1452): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1452): Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
,D/KeyguardModel( 1452): package = com.lge.camera, class = com.lge.camera.CameraApp
D/KeyguardModel( 1452): createShortcutInfo...
W/ActivityManager( 1032): getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
D/LGBluetoothAvrcpQcomAdapter( 6105): [BTUI] installed app name: Music
D/LGBluetoothAvrcpQcomAdapter( 6105): [BTUI] installed app name: Google Play Music
D/LGBluetoothAvrcpQcomAdapter( 6105): [BTUI] === MediaPlayerInfo (playerId:0) ===
D/LGBluetoothAvrcpQcomAdapter( 6105): [BTUI]          displayName: Music
D/LGBluetoothAvrcpQcomAdapter( 6105): [BTUI]          packageName: com.lge.music
D/LGBluetoothAvrcpQcomAdapter( 6105): [BTUI]          playState: 2 (PAUSED)
D/LGBluetoothAvrcpQcomAdapter( 6105): [BTUI] === MediaPlayerInfo (playerId:1) ===
D/LGBluetoothAvrcpQcomAdapter( 6105): [BTUI]          displayName: Google Play Music
D/LGBluetoothAvrcpQcomAdapter( 6105): [BTUI]          packageName: com.google.android.music
D/LGBluetoothAvrcpQcomAdapter( 6105): [BTUI]          playState: 2 (PAUSED)
D/LGBluetoothAvrcpQcomAdapter( 6105): [BTUI] [-] updateMediaPlayerInfo
D/KeyguardModel( 1452): handleShortcutListChanged...
D/KeyguardModel( 1452): package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
D/KeyguardModel( 1452): createShortcutInfo...
D/KeyguardModel( 1452): package = com.android.mms, class = com.android.mms.ui.ConversationList
D/KeyguardModel( 1452): createShortcutInfo...
D/SplitUIManager( 1869): split_name #11 / not available #0
I/SplitUIService( 1869): split app #11
W/ResourceType( 1452): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1452): Failure retrieving resources for com.android.mms: Resource ID #0x0
,D/KeyguardModel( 1452): package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
D/KeyguardModel( 1452): createShortcutInfo...
W/ResourceType( 1452): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1452): Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
W/ResourcesManager( 7399): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
D/KeyguardModel( 1452): package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
D/KeyguardModel( 1452): createShortcutInfo...
W/ResourceType( 1452): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1452): Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
D/KeyguardModel( 1452): package = com.lge.camera, class = com.lge.camera.CameraApp
D/KeyguardModel( 1452): createShortcutInfo...
V/SIM_STK ( 1032): Menu title from STK is T-Mobile
,D/KeyguardModel( 1452): handleShortcutListChanged...
I/[LGHome]EVENT( 2069): [Launcher.java:5349:onStop()]onStop
I/NotificationService( 1032): action=android.intent.action.PACKAGE_REMOVED queryReplace=false
D/BackupManagerService( 1032): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/JobSchedulerService( 1032): Receieved: android.intent.action.PACKAGE_REMOVED
D/PluginManager( 7399): init()
D/TaskPersister( 1032): removeObsoleteFile: deleting file=4_task.xml
,D/PhoneStatusBar( 1452): setSystemUiVisibility vis=8000 mask=ffffffff oldVal=0 newVal=8000 diff=8000
I/[SystemUI]NavigationThemeResource( 1452): NavigationKey Color is changed(BLACK -> WHITE_WITH_SHADOW)
I/[SystemUI]NavigationThemeResource( 1452):  BarMode=4, Theme=WHITE, LightBackground=false (Transparent)
I/[SystemUI]NavigationThemeResource( 1452): , Keyguard show=false, IME shown=false, Panel expanded=false
I/[LGHome]Launcher.Model( 2069): [LauncherModel.java:2230:run()] LauncherModel bind current page shortcut
,I/[LGHome]Launcher( 2069): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/[LGHome]EVENT( 2069): [Workspace.java:918:addInScreen()]Add Shortcut [Email] in screen 1 [1, 4]
I/[LGHome]EVENT( 2069): [Workspace.java:918:addInScreen()]Add Shortcut [Play Store] in screen 1 [2, 4]
I/[LGHome]EVENT( 2069): [Workspace.java:918:addInScreen()]Add Shortcut [Camera] in screen 1 [3, 4]
I/[LGHome]EVENT( 2069): [Workspace.java:918:addInScreen()]Add Shortcut [Settings] in screen 1 [4, 4]
,I/Timeline( 1032): Timeline: Activity_windows_visible id: ActivityRecord{3d8d6083 u0 com.lge.launcher2/.Launcher t3} time:288051
I/[LGHome]Launcher.Model( 2069): [LauncherModel.java:2244:run()] LauncherModel bind current page shortcut
I/[LGHome]Launcher( 2069): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 2069): [LGUnreadLgeEmailsBadge.java:107:countUnreadItems()]setTotalCount : 0
I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 2069): [LGUnreadLgeEmailsBadge.java:108:countUnreadItems()]countUnreadItems() ended..
W/ResourcesManager( 1032): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourceType( 1032): Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
,I/[LGHome]EVENT( 2069): [Workspace.java:918:addInScreen()]Add Folder [Google] in screen 1 [0, 4]
I/[LGHome]EVENT( 2069): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
I/[LGHome]Launcher.Model( 2069): [LauncherModel.java:2256:run()] LauncherModel bind current page widget
I/[LGHome]Launcher( 2069): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/[Concierge]WidgetView( 2069): ConciergeWidgetView is instantiated. sIsWidgetAttached : true
D/[Concierge]Service( 2593): onStartCommand(). Type : 8
D/[Concierge]Service( 2593): Update widget. Component : {com.lge.concierge/com.lge.concierge.ConciergeWidgetProvider}
,D/[Concierge]Service( 2593): Update widget ID : 11
D/[Concierge]WidgetView( 2069): change position of spinner
D/[Concierge]Service( 2593): onStartCommand(). Type : 0
I/[Concierge]WidgetView( 2069): initWebView(). Time : 1454715069923
I/[Concierge]WebView( 2069): Return exist ConciergeWebView. Reuse : 529954639
D/[Concierge]WidgetView( 2069): State Change : null -> AccInBeforeState
I/[LgeWidgetLib]LgeAppWidgetHostView( 2069): [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
I/[LgeWidgetLib]ExtViewHost( 2069): [LgeAppWidgetExtViewHost.java:136:setState()]New State = com.lge.lgewidgetlib.extview.NormalState@cb005f7
I/[LGHome]EVENT( 2069): [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.concierge.ConciergeWidgetProvider] in screen 1 [0, 0]
,I/[LGHome]Launcher.Model( 2069): [LauncherModel.java:2256:run()] LauncherModel bind current page widget
I/[LGHome]Launcher( 2069): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/[LGHome]EVENT( 2069): [Workspace.java:918:addInScreen()]Add AppWidget [com.google.android.googlequicksearchbox.SearchWidgetProvider] in screen 1 [0, 2]
D/[Concierge]WidgetView( 2069): isWidgetUpdateSkippable ? true
D/[Concierge]WidgetBroadcastReceiver( 2069): New receiver registered. Self-unregister old one. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
I/art     ( 1032): Explicit concurrent mark sweep GC freed 11542(613KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 44MB/66MB, paused 2.740ms total 288.389ms
,W/[Concierge]WidgetView( 2069): Widget kill message received. Destory myself. My : 1454714809892, New one : 1454715069923
D/[Concierge]WidgetView( 2069): Unregister all receivers
W/[Concierge]WidgetBroadcastReceiver( 2069): Tried unregister broadcastReceiver which is not registered. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
I/[LGHome]Launcher( 2069): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/[LGHome]EVENT( 2069): [Workspace.java:918:addInScreen()]Add Shortcut [Gallery] in screen 2 [0, 4]
I/[LGHome]EVENT( 2069): [Workspace.java:918:addInScreen()]Add Shortcut [Calendar] in screen 2 [1, 4]
I/[LGHome]EVENT( 2069): [Workspace.java:918:addInScreen()]Add Shortcut [QuickMemo+] in screen 2 [2, 4]
I/[LGHome]EVENT( 2069): [Workspace.java:918:addInScreen()]Add Shortcut [Quick Remote] in screen 2 [3, 4]
I/[LGHome]EVENT( 2069): [Workspace.java:918:addInScreen()]Add Shortcut [FM Radio] in screen 2 [4, 4]
I/[LGHome]Launcher( 2069): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/[LGHome]Launcher( 2069): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/[LgeWidgetLib]LgeAppWidgetHostView( 2069): [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
,E/[LgeWidgetLib]LgeAppWidgetHostView( 2069): [LgeAppWidgetHostView.java:124:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
I/[LGHome]EVENT( 2069): [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1] in screen 2 [0, 0]
I/[LGHome]Launcher( 2069): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,I/Timeline( 2069): Timeline: Activity_idle id: android.os.BinderProxy@17d21e2a time:288210
,D/AndroidRuntime( 7369): Shutting down VM
,W/ExternalStrings( 7399): load override strings
W/ExternalStrings( 7399): java.lang.RuntimeException: Unexpected tag, got eat-comment
W/ExternalStrings( 7399): 	at com.mcafee.plugin.af.a(Unknown Source)
W/ExternalStrings( 7399): 	at com.mcafee.plugin.ac.b(Unknown Source)
W/ExternalStrings( 7399): 	at com.mcafee.plugin.ak.d(Unknown Source)
W/ExternalStrings( 7399): 	at com.mcafee.plugin.ak.a(Unknown Source)
W/ExternalStrings( 7399): 	at com.mcafee.app.s.getClassLoader(Unknown Source)
W/ExternalStrings( 7399): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5001)
W/ExternalStrings( 7399): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4609)
W/ExternalStrings( 7399): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4549)
W/ExternalStrings( 7399): 	at android.app.ActivityThread.access$1500(ActivityThread.java:148)
W/ExternalStrings( 7399): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1344)
W/ExternalStrings( 7399): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/ExternalStrings( 7399): 	at android.os.Looper.loop(Looper.java:135)
W/ExternalStrings( 7399): 	at android.app.ActivityThread.main(ActivityThread.java:5274)
W/ExternalStrings( 7399): 	at java.lang.reflect.Method.invoke(Native Method)
W/ExternalStrings( 7399): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/ExternalStrings( 7399): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
W/ExternalStrings( 7399): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
D/StatusProvider( 7399): onCreate
,V/Signer  ( 7399): override build config not found
D/Signer  ( 7399): value of property debug is false
,D/LGMDMWrapper( 7399): Found class 'com.mcafee.lgmdm.LGMDMWrapper$DataWipe'.
D/LGMDMWrapper( 7399): Found class 'com.mcafee.lgmdm.LGMDMWrapper$DownloadMode'.
,D/LGMDMWrapper( 7399): Found class 'com.mcafee.lgmdm.LGMDMWrapper$HardReset'.
D/LGMDMWrapper( 7399): Found class 'com.mcafee.lgmdm.LGMDMWrapper$HardwareKeyReset'.
D/LGMDMWrapper( 7399): Found class 'com.mcafee.lgmdm.LGMDMWrapper$RemoveDeviceAdmin'.
,D/LGMDMWrapper( 7399): Found class 'com.mcafee.lgmdm.LGMDMWrapper$UnknownSourceInstallation'.
D/LGMDMWrapper( 7399): Found class 'com.mcafee.lgmdm.LGMDMWrapper$Usb'.
D/LGMDMWrapper( 7399): Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbDebugging'.
D/LGMDMWrapper( 7399): Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbHostStorage'.
D/LGMDMWrapper( 7399): Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbMediaTransfer'.
D/LGMDMWrapper( 7399): Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbPictureTransfer'.
D/LGMDMWrapper( 7399): Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbStorage'.
D/LGMDMWrapper( 7399): Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbTethering'.
I/chromium( 2069): [INFO:CONSOLE(0)] "'window.webkitStorageInfo' is deprecated. Please use 'navigator.webkitTemporaryStorage' or 'navigator.webkitPersistentStorage' instead.", source:  (0)
V/LGMDMManager( 7399): Create singleton instance
I/GBoardtInterface( 2069): onReloaded()
I/GBoardWebViewClient( 2069): onPageFinished url:file:///android_asset/www/main.html
V/BoardContentProvider( 2702): query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
,V/BoardContentProvider( 2702): query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
,D/ActionManagerService( 1904): notifyUserLog: 1000001
D/LIA_Informant_ActionManagerMessageHandler( 2702): handleMessage: what(1000) actionID(0x1000001)
D/LIA_Informant_Tips_SmartTipsActionManager( 2702): onEvent() : ACTION_BOARD_ENABLED
,D/LGMDMWrapper( 7399): LG MDM library v4.0.0 is available on this device.
,D/ActionManagerService( 1904): notifyUserLog: 1000001
D/LIA_Informant_ActionManagerMessageHandler( 2702): handleMessage: what(1000) actionID(0x1000001)
D/LIA_Informant_Tips_SmartTipsActionManager( 2702): onEvent() : ACTION_BOARD_ENABLED
D/LIA_Informant_Tips_FormEventRepository( 2702): getSize() : size - 0
D/LIA_Informant_Tips_SmartTipsActionManager( 2702): onSettingEvent() : GBoard On - add scheduler - 0
V/BoardContentProvider( 2702): query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
D/GBoardUriUtils( 2069): fileExists: file:///system/etc/mrg_default_forms/MyWellness/initial/initial2.html?id=mw_initial return true
D/GBoardWebViewUtils( 2069): changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyWellness/initial/initial2.html?id=mw_initial
,D/GBoardUriUtils( 2069): fileExists: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial2.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc] return true
D/GBoardWebViewUtils( 2069): changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial2.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
D/GBoardUriUtils( 2069): fileExists: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/0/userguide2.html?id=guide_1111111111116_1454599632914&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay return true
D/GBoardWebViewUtils( 2069): changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/0/userguide2.html?id=guide_1111111111116_1454599632914&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
D/PostponalbeReceiver( 7399): WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.intent.action.PACKAGE_REMOVED'.
,W/ContextImpl( 7399): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
,D/AppUp4:PreloadHelper( 7002): added Exclude : com.test.thalitest
,I/ActivityManager( 1032): Killing 6853:com.qualcomm.timeservice/1000 (adj 15): empty #17
W/ActivityThread( 7399): ClassLoader.getResources: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/libprocessgroup( 1032): failed to open /acct/uid_1000/pid_6853/cgroup.procs: No such file or directory
,D/ContactsProvider2ForLG( 2272): performBackgroundTask SQLiteDiskIOException during query
D/ContactsProvider2ForLG( 2272): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 778)
D/ContactsProvider2ForLG( 2272): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
D/ContactsProvider2ForLG( 2272): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:560)
D/ContactsProvider2ForLG( 2272): 	at android.database.sqlite.SQLiteSession.endTransactionUnchecked(SQLiteSession.java:437)
D/ContactsProvider2ForLG( 2272): 	at android.database.sqlite.SQLiteSession.endTransaction(SQLiteSession.java:401)
D/ContactsProvider2ForLG( 2272): 	at android.database.sqlite.SQLiteDatabase.endTransaction(SQLiteDatabase.java:525)
D/ContactsProvider2ForLG( 2272): 	at com.android.providers.contacts.ContactDirectoryManager.updateDirectoriesForPackage(ContactDirectoryManager.java:414)
D/ContactsProvider2ForLG( 2272): 	at com.android.providers.contacts.ContactDirectoryManager.onPackageChanged(ContactDirectoryManager.java:363)
D/ContactsProvider2ForLG( 2272): 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:974)
D/ContactsProvider2ForLG( 2272): 	at com.android.providers.contacts.ContactsProvider2ForLG.performBackgroundTask(ContactsProvider2ForLG.java:375)
D/ContactsProvider2ForLG( 2272): 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:748)
D/ContactsProvider2ForLG( 2272): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/ContactsProvider2ForLG( 2272): 	at android.os.Looper.loop(Looper.java:135)
D/ContactsProvider2ForLG( 2272): 	at android.os.HandlerThread.run(HandlerThread.java:61)
D/VoicemailCleanupService( 2272): Cleaning up data for package: com.test.thalitest
,E/SQLiteDatabase( 7399): Failed to open database '/data/data/com.wsandroid.suite.lge/databases/WSAndroid'.
E/SQLiteDatabase( 7399): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 7399): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 7399): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 7399): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 7399): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 7399): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 7399): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 7399): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:907)
E/SQLiteDatabase( 7399): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:892)
E/SQLiteDatabase( 7399): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:795)
E/SQLiteDatabase( 7399): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1213)
E/SQLiteDatabase( 7399): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 7399): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 7399): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 7399): 	at com.mcafee.wsstorage.b.a(Unknown Source)
E/SQLiteDatabase( 7399): 	at com.mcafee.wsstorage.a.m(Unknown Source)
E/SQLiteDatabase( 7399): 	at com.mcafee.wsstorage.a.a(Unknown Source)
E/SQLiteDatabase( 7399): 	at com.mcafee.wsstorage.a.b(Unknown Source)
E/SQLiteDatabase( 7399): 	at com.mcafee.wsstorage.ConfigManager.g(Unknown Source)
E/SQLiteDatabase( 7399): 	at com.mcafee.wsstorage.ConfigManager.c(Unknown Source)
E/SQLiteDatabase( 7399): 	at com.mcafee.wsstorage.ConfigManager.ab(Unknown Source)
E/SQLiteDatabase( 7399): 	at com.mcafee.fw.ws.WSLicenseService.a(Unknown Source)
E/SQLiteDatabase( 7399): 	at com.mcafee.g.b.a(Unknown Source)
E/SQLiteDatabase( 7399): 	at com.mcafee.applock.AppLockComponent.a_(Unknown Source)
E/SQLiteDatabase( 7399): 	at com.mcafee.applock.AppLockComponent.a(Unknown Source)
E/SQLiteDatabase( 7399): 	at com.mcafee.c.b.b(Unknown Source)
E/SQLiteDatabase( 7399): 	at com.mcafee.framework.b.a(Unknown Source)
E/SQLiteDatabase( 7399): 	at com.mcafee.app.t.run(Unknown Source)
E/SQLiteDatabase( 7399): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/SQLiteDatabase( 7399): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 7399): 	at com.mcafee.d.f.run(Unknown Source)
E/SQLiteDatabase( 7399): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 7399): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 7399): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteDatabase( 7399): 	at com.mcafee.d.c.run(Unknown Source)
E/SQLiteLog( 2272): (3850) statement aborts at 37: [DELETE FROM calls WHERE (((source_package = 'com.test.thalitest'))) AND ((type = 4))] disk I/O error
--------- beginning of crash
E/AndroidRuntime( 2272): FATAL EXCEPTION: IntentService[VoicemailCleanupService]
E/AndroidRuntime( 2272): Process: android.process.acore, PID: 2272
E/AndroidRuntime( 2272): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 2272): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/AndroidRuntime( 2272): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:739)
E/AndroidRuntime( 2272): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:892),
E/AndroidRuntime( 2272): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/AndroidRuntime( 2272): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1600)
E/AndroidRuntime( 2272): 	at com.android.providers.contacts.util.DbModifierWithNotification.delete(DbModifierWithNotification.java:161)
E/AndroidRuntime( 2272): 	at com.android.providers.contacts.voicemail.VoicemailContentTable.delete(VoicemailContentTable.java:229)
E/AndroidRuntime( 2272): 	at com.android.providers.contacts.voicemail.VoicemailContentProvider.delete(VoicemailContentProvider.java:135)
E/AndroidRuntime( 2272): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:312)
E/AndroidRuntime( 2272): 	at android.content.ContentResolver.delete(ContentResolver.java:1315)
E/AndroidRuntime( 2272): 	at com.android.providers.contacts.voicemail.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
E/AndroidRuntime( 2272): 	at com.android.providers.contacts.voicemail.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
E/AndroidRuntime( 2272): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 2272): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 2272): 	at android.os.Looper.loop(Looper.java:135)
E/AndroidRuntime( 2272): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ActivityManager( 1032): Start proc com.lge.email for broadcast com.lge.email/.receiver.PackageChangeReceiver: pid=7434 uid=10023 gids={50023, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,I/Process ( 2272): Sending signal. PID: 2272 SIG: 9
E/DropBoxManagerService( 1032): Can't write: system_app_crash
E/DropBoxManagerService( 1032): java.io.FileNotFoundException: /data/system/dropbox/drop110.tmp: open failed: EROFS (Read-only file system)
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
,E/SQLiteDatabase( 7399): Failed to open database '/data/data/com.wsandroid.suite.lge/databases/lockedapplications'.
E/SQLiteDatabase( 7399): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 7399): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 7399): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 7399): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 7399): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 7399): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 7399): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 7399): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:907)
E/SQLiteDatabase( 7399): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:892)
E/SQLiteDatabase( 7399): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:795)
E/SQLiteDatabase( 7399): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1213)
E/SQLiteDatabase( 7399): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 7399): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 7399): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteDatabase( 7399): 	at com.mcafee.applock.a.a(Unknown Source)
E/SQLiteDatabase( 7399): 	at com.mcafee.applock.d.d(Unknown Source)
E/SQLiteDatabase( 7399): 	at com.mcafee.applock.d.<init>(Unknown Source)
E/SQLiteDatabase( 7399): 	at com.mcafee.applock.d.a(Unknown Source)
E/SQLiteDatabase( 7399): 	at com.mcafee.modes.adapt.a.<init>(Unknown Source)
E/SQLiteDatabase( 7399): 	at com.mcafee.modes.adapt.a.a(Unknown Source)
E/SQLiteDatabase( 7399): 	at com.mcafee.modes.adapt.ModesLockHelper.a(Unknown Source)
E/SQLiteDatabase( 7399): 	at com.mcafee.applock.h.<init>(Unknown Source)
E/SQLiteDatabase( 7399): 	at com.mcafee.applock.f.<init>(Unknown Source)
E/SQLiteDatabase( 7399): 	at com.mcafee.applock.f.a(Unknown Source)
E/SQLiteDatabase( 7399): 	at com.mcafee.applock.AppLockComponent.d(Unknown Source)
E/SQLiteDatabase( 7399): 	at com.mcafee.applock.AppLockComponent.a_(Unknown Source)
E/SQLiteDatabase( 7399): 	at com.mcafee.applock.AppLockComponent.a(Unknown Source)
E/SQLiteDatabase( 7399): 	at com.mcafee.c.b.b(Unknown Source)
E/SQLiteDatabase( 7399): 	at com.mcafee.framework.b.a(Unknown Source)
E/SQLiteDatabase( 7399): 	at com.mcafee.app.t.run(Unknown Source)
E/SQLiteDatabase( 7399): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/SQLiteDatabase( 7399): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 7399): 	at com.mcafee.d.f.run(Unknown Source)
E/SQLiteDatabase( 7399): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 7399): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 7399): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteDatabase( 7399): 	at com.mcafee.d.c.run(Unknown Source)
E/SQLiteOpenHelper( 7399): Couldn't open lockedapplications for writing (will try read-only):
E/SQLiteOpenHelper( 7399): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 7399): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 7399): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteOpenHelper( 7399): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteOpenHelper( 7399): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQ,LiteConnectionPool.java:463)
E/SQLiteOpenHelper( 7399): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 7399): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 7399): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:907)
E/SQLiteOpenHelper( 7399): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:892)
E/SQLiteOpenHelper( 7399): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:795)
E/SQLiteOpenHelper( 7399): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1213)
E/SQLiteOpenHelper( 7399): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteOpenHelper( 7399): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteOpenHelper( 7399): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteOpenHelper( 7399): 	at com.mcafee.applock.a.a(Unknown Source)
E/SQLiteOpenHelper( 7399): 	at com.mcafee.applock.d.d(Unknown Source)
E/SQLiteOpenHelper( 7399): 	at com.mcafee.applock.d.<init>(Unknown Source)
E/SQLiteOpenHelper( 7399): 	at com.mcafee.applock.d.a(Unknown Source)
E/SQLiteOpenHelper( 7399): 	at com.mcafee.modes.adapt.a.<init>(Unknown Source)
E/SQLiteOpenHelper( 7399): 	at com.mcafee.modes.adapt.a.a(Unknown Source)
E/SQLiteOpenHelper( 7399): 	at com.mcafee.modes.adapt.ModesLockHelper.a(Unknown Source)
E/SQLiteOpenHelper( 7399): 	at com.mcafee.applock.h.<init>(Unknown Source)
E/SQLiteOpenHelper( 7399): 	at com.mcafee.applock.f.<init>(Unknown Source)
E/SQLiteOpenHelper( 7399): 	at com.mcafee.applock.f.a(Unknown Source)
E/SQLiteOpenHelper( 7399): 	at com.mcafee.applock.AppLockComponent.d(Unknown Source)
E/SQLiteOpenHelper( 7399): 	at com.mcafee.applock.AppLockComponent.a_(Unknown Source)
E/SQLiteOpenHelper( 7399): 	at com.mcafee.applock.AppLockComponent.a(Unknown Source)
E/SQLiteOpenHelper( 7399): 	at com.mcafee.c.b.b(Unknown Source)
E/SQLiteOpenHelper( 7399): 	at com.mcafee.framework.b.a(Unknown Source)
E/SQLiteOpenHelper( 7399): 	at com.mcafee.app.t.run(Unknown Source)
E/SQLiteOpenHelper( 7399): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/SQLiteOpenHelper( 7399): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteOpenHelper( 7399): 	at com.mcafee.d.f.run(Unknown Source)
E/SQLiteOpenHelper( 7399): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteOpenHelper( 7399): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteOpenHelper( 7399): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteOpenHelper( 7399): 	at com.mcafee.d.c.run(Unknown Source)
W/SQLiteOpenHelper( 7399): Opened lockedapplications in read-only mode
I/ActivityManager( 1032): Process android.process.acore (pid 2272) has died
W/ActivityManager( 1032): Scheduling restart of crashed service com.android.providers.contacts/.voicemail.VoicemailCleanupService in 1000ms
W/ActivityManager( 1032): Scheduling restart of crashed service com.android.providers.contacts/com.lge.providers.contacts.AliveAcoreService in 1000ms
E/WifiStateMachine( 1032):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-62 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1278842800] gl rssi=-62 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1032):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-62 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-1278842799] gl rssi=-62 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1032): doString: [SIGNAL_POLL]
E/SQLiteDatabase( 7399): Failed to open database '/data/data/com.wsandroid.suite.lge/databases/WSAndroid'.
E/SQLiteDatabase( 7399): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 7399): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 7399): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 7399): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 7399): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 7399): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 7399): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 7399): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:907)
E/SQLiteDatabase( 7399): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:892)
E/SQLiteDatabase( 7399): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:795)
E/SQLiteDatabase( 7399): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1213)
E/SQLiteDatabase( 7399): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 7399): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 7399): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 7399): 	at com.mcafee.wsstorage.b.a(Unknown Source)
E/SQLiteDatabase( 7399): 	at com.mcafee.wsstorage.a.m(Unknown Source)
E/SQLiteDatabase( 7399): 	at com.mcafee.wsstorage.a.a(Unknown Source)
E/SQLiteDatabase( 7399): 	at com.mcafee.wsstorage.a.b(Unknown Source)
E/SQLiteDatabase( 7399): 	at com.mcafee.wsstorage.ConfigManager.g(Unknown Source)
E/SQLiteDatabase( 7399): 	at com.mcafee.wsstorage.ConfigManager.b(Unknown Source)
E/SQLiteDatabase( 7399): 	at com.mcafee.notificationtray.e.<init>(Unknown Source)
E/SQLiteDatabase( 7399): 	at com.mcafee.notificationtray.e.a(Unknown Source)
E/SQLiteDatabase( 7399): 	at com.mcafee.notificationtray.NotificationComponent.a(Unknown Source)
E/SQLiteDatabase( 7399): 	at com.mcafee.c.b.b(Unknown Source)
E/SQLiteDatabase( 7399): 	at com.mcafee.framework.b.a(Unknown Source)
E/SQLiteDatabase( 7399): 	at com.mcafee.app.t.run(Unknown Source)
E/SQLiteDatabase( 7399): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/SQLiteDatabase( 7399): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 7399): 	at com.mcafee.d.f.run(Unknown Source)
E/SQLiteDatabase( 7399): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 7399): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 7399): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteDatabase( 7399): 	at com.mcafee.d.c.run(Unknown Source)
W/ResourcesManager( 7434): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
E/SQLiteDatabase( 7399): Failed to open database '/data/data/com.wsandroid.suite.lge/databases/WSAndroid'.
E/SQLiteDatabase( 7399): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 7399): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 7399): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 7399): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 7399): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 7399): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 7399): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 7399): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:907)
E/SQLiteDatabase( 7399): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:892)
E/SQLiteDatabase( 7399): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:795)
E/SQLiteDatabase( 7399): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1213)
E/SQLiteDatabase( 7399): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 7399): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 7399): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 7399): 	at com.mcafee.wsstorage.b.a(Unknown Source)
E/SQLiteDatabase( 7399): 	at com.mcafee.wsstorage.a.m(Unknown Source)
E/SQLiteDatabase( 7399): 	at com.mcafee.wsstorage.a.a(Unknown Source)
E/SQLiteDatabase( 7399): 	at com.mcafee.wsstorage.a.b(Unknown Source)
E/SQLiteDatabase( 7399): 	at com.mcafee.wsstorage.ConfigManager.a(Unknown Source)
E/SQLiteDatabase( 7399): 	at com.wavesecure.utils.CommonPhoneUtils.o(Unknown Source)
E/SQLiteDatabase( 7399): 	at com.wavesecure.utils.y.v(Unknown Source)
E/SQLiteDatabase( 7399): 	at com.wavesecure.core.WSComponent.a(Unknown Source)
E/SQLiteDatabase( 7399): 	at com.mcafee.c.b.b(Unknown Source)
E/SQLiteDatabase( 7399): 	at com.mcafee.framework.b.a(Unknown Source)
E/SQLiteDatabase( 7399): 	at com.mcafee.app.t.run(Unknown Source)
E/SQLiteDatabase( 7399): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/SQLiteDatabase( 7399): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 7399): 	at com.mcafee.d.f.run(Unknown Source)
E/SQLiteDatabase( 7399): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 7399): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 7399): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteDatabase( 7399): 	at com.mcafee.d.c.run(Unknown Source)
W/ResourcesManager( 7434): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 7434): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
W/ResourcesManager( 7434): Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
E/SQLiteDatabase( 7399): Failed to open database '/data/data/com.wsandroid.suite.lge/databases/WSAndroid'.
E/SQLiteDatabase( 7399): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 7399): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 7399): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 7399): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 7399): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 7399): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 7399): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 7399): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:907)
E/SQLiteDatabase( 7399): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:892)
E/SQLiteDatabase( 7399): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:795)
E/SQLiteDatabase( 7399): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1213)
E/SQLiteDatabase( 7399): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 7399): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 7399): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 7399): 	at com.mcafee.wsstorage.b.a(Unknown Source)
E/SQLiteDatabase( 7399): 	at com.mcafee.wsstorage.a.m(Unknown Source)
E/SQLiteDatabase( 7399): 	at com.mcafee.wsstorage.a.a(Unknown Source)
E/SQLiteDatabase( 7399): 	at com.mcafee.wsstorage.a.b(Unknown Source)
E/SQLiteDatabase( 7399): 	at com.mcafee.wsstorage.ConfigManager.g(Unknown Source)
E/SQLiteDatabase( 7399): 	at com.mcafee.wsstorage.ConfigManager.d(Unknown Source)
E/SQLiteDatabase( 7399): 	at com.wavesecure.utils.CommonPhoneUtils.o(Unknown Source)
E/SQLiteDatabase( 7399): 	at com.wavesecure.utils.y.v(Unknown Source)
E/SQLiteDatabase( 7399): 	at com.wavesecure.core.WSComponent.a(Unknown Source)
E/SQLiteDatabase( 7399): 	at com.mcafee.c.b.b(Unknown Source)
E/SQLiteDatabase( 7399): 	at com.mcafee.framework.b.a(Unknown Source)
E/SQLiteDatabase( 7399): 	at com.mcafee.app.t.run(Unknown Source)
E/SQLiteDatabase( 7399): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/SQLiteDatabase( 7399): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 7399): 	at com.mcafee.d.f.run(Unknown Source)
E/SQLiteDatabase( 7399): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 7399): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 7399): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteDatabase( 7399): 	at com.mcafee.d.c.run(Unknown Source)
E/SQLiteDatabase( 7399): Failed to open database '/data/data/com.wsandroid.suite.lge/databases/WSAndroid'.
E/SQLiteDatabase( 7399): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 7399): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 7399): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 7399): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 7399): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 7399): 	at android,.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 7399): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 7399): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:907)
E/SQLiteDatabase( 7399): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:892)
E/SQLiteDatabase( 7399): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:795)
E/SQLiteDatabase( 7399): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1213)
E/SQLiteDatabase( 7399): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 7399): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 7399): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 7399): 	at com.mcafee.wsstorage.b.a(Unknown Source)
E/SQLiteDatabase( 7399): 	at com.mcafee.wsstorage.a.m(Unknown Source)
E/SQLiteDatabase( 7399): 	at com.mcafee.wsstorage.a.a(Unknown Source)
E/SQLiteDatabase( 7399): 	at com.mcafee.wsstorage.a.b(Unknown Source)
E/SQLiteDatabase( 7399): 	at com.mcafee.wsstorage.ConfigManager.g(Unknown Source)
E/SQLiteDatabase( 7399): 	at com.mcafee.wsstorage.ConfigManager.c(Unknown Source)
E/SQLiteDatabase( 7399): 	at com.mcafee.wsstorage.ConfigManager.m(Unknown Source)
E/SQLiteDatabase( 7399): 	at com.wavesecure.core.WSComponent.a(Unknown Source)
E/SQLiteDatabase( 7399): 	at com.mcafee.c.b.b(Unknown Source)
E/SQLiteDatabase( 7399): 	at com.mcafee.framework.b.a(Unknown Source)
E/SQLiteDatabase( 7399): 	at com.mcafee.app.t.run(Unknown Source)
E/SQLiteDatabase( 7399): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/SQLiteDatabase( 7399): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 7399): 	at com.mcafee.d.f.run(Unknown Source)
E/SQLiteDatabase( 7399): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 7399): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 7399): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteDatabase( 7399): 	at com.mcafee.d.c.run(Unknown Source)
I/GBoardtInterface( 2069): exportHTML()
E/SQLiteDatabase( 7399): Failed to open database '/data/data/com.wsandroid.suite.lge/databases/WSAndroid'.
E/SQLiteDatabase( 7399): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 7399): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 7399): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 7399): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 7399): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 7399): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 7399): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 7399): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:907)
E/SQLiteDatabase( 7399): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:892)
E/SQLiteDatabase( 7399): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:795)
E/SQLiteDatabase( 7399): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1213)
E/SQLiteDatabase( 7399): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 7399): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 7399): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 7399): 	at com.mcafee.wsstorage.b.a(Unknown Source)
E/SQLiteDatabase( 7399): 	at com.mcafee.wsstorage.a.m(Unknown Source)
E/SQLiteDatabase( 7399): 	at com.mcafee.wsstorage.a.a(Unknown Source)
E/SQLiteDatabase( 7399): 	at com.mcafee.wsstorage.a.b(Unknown Source)
E/SQLiteDatabase( 7399): 	at com.mcafee.wsstorage.ConfigManager.g(Unknown Source)
E/SQLiteDatabase( 7399): 	at com.mcafee.wsstorage.ConfigManager.c(Unknown Source)
E/SQLiteDatabase( 7399): 	at com.wavesecure.c2dm.a.d(Unknown Source)
E/SQLiteDatabase( 7399): 	at com.wavesecure.c2dm.a.c(Unknown Source)
E/SQLiteDatabase( 7399): 	at com.wavesecure.notification.g.a(Unknown Source)
E/SQLiteDatabase( 7399): 	at com.wavesecure.core.WSComponent.a(Unknown Source)
E/SQLiteDatabase( 7399): 	at com.mcafee.c.b.b(Unknown Source)
E/SQLiteDatabase( 7399): 	at com.mcafee.framework.b.a(Unknown Source)
E/SQLiteDatabase( 7399): 	at com.mcafee.app.t.run(Unknown Source)
E/SQLiteDatabase( 7399): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/SQLiteDatabase( 7399): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 7399): 	at com.mcafee.d.f.run(Unknown Source)
E/SQLiteDatabase( 7399): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 7399): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 7399): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteDatabase( 7399): 	at com.mcafee.d.c.run(Unknown Source)
I/GBoardtInterface( 2069): exportHTML()
D/LgDataFeature( 7399): LgDataFeature() Constructor: none
D/LgDataFeature( 7399): LgDataFeature() Constructor Done, null

```
