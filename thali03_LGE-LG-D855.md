#### Test 58135655a1ee273_thali03_LGE-LG-D855 Logs


```
--------- beginning of system
V/AlarmManager( 1029): RTC_WAKEUP set : Alarm{14c435ec type 0 when 1454597256731 com.android.vending} when 1454597256731
,W/ContextImpl( 4241): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 com.lge.mlt.MptOnLogDumper.run:279 <bottom of call stack> <bottom of call stack> 
--------- beginning of main
V/SIM_STK ( 1029): Menu title from STK is T-Mobile
D/AndroidRuntime( 6071): 
D/AndroidRuntime( 6071): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 6071): CheckJNI is OFF
V/GLSActivity( 2157): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/GLSUser ( 2157): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 2157): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2157): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2157): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2157): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/Finsky  ( 4926): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 4926): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 4926): [1] 5.onFinished: Scheduling replication attempt 1.
D/AndroidRuntime( 6071): Calling main entry com.android.commands.am.Am
I/ActivityManager( 1029): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
V/SplitWindowPolicy( 1958): checkScreen => return. sourceIntent is null or not support SplitWindow component: ComponentInfo{co..../co.....MainActivity}
D/SplitInfo( 1029): new ActivitySplitInfo : ActivitySplitInfo [screenZone=0/ flag=0/ state=NATIVE]
D/ActivityManager( 1029): setTaskToReturnTo : TaskRecord{127f1eee #4 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
D/ActivityManager( 1029): setTaskToReturnTo : TaskRecord{127f1eee #4 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
D/WindowStateEx( 1029): AppWindowTokenEx init.. 
E/GBMv2   (  347): DFP En is all cleared set to be enabled
I/ActivityManager( 1029): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6110 uid=10311 gids={50311, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
D/AndroidRuntime( 6071): Shutting down VM
V/ActivityManager( 1029): Display changed displayId=0
D/DSDPConnection( 1861): Display #0 changed.
D/SplitWindowPolicy( 1958): updateActivityStateChanged: resumed=true, screenId=1, isScreenFull=true
D/SplitWindowPolicy( 1958): topRunningActivity=ActivityInfo{353aee74 co.....MainActivity}, taskId=4, activityType=0, bIsSplit=false
D/SplitWindowPolicy( 1958): updateActivityStateChanged: resumed=false, screenId=1, isScreenFull=true
D/SplitWindowPolicy( 1958): topRunningActivity=ActivityInfo{770f9d co.....MainActivity}, taskId=4, activityType=0, bIsSplit=false
D/ContextHelper( 6110): convertTheme. context->name=com.test.thalitest themeResourceId=16973833
I/WebViewFactory( 6110): Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
I/LibraryLoader( 6110): Loading: webviewchromium
I/LibraryLoader( 6110): Time to load native libraries: 3 ms (timestamps 2298-2301)
,I/LibraryLoader( 6110): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 6110): Binding Chromium to main looper Looper (main, tid 1) {1b35ce89}
,I/LibraryLoader( 6110): Expected native library version number "",actual native library version number ""
I/chromium( 6110): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 6110): Initializing chromium process, renderers=0
,W/art     ( 6110): Attempt to remove local handle scope entry from IRT, ignoring
W/chromium( 6110): [WARNING:dns_config_service_posix.cc(293)] Failed to read DnsConfig.
V/AudioPolicyService(  325): registerClient() client 0xb100fb60, uid 10311
,D/BluetoothManagerService( 1029): Message: 20
D/BluetoothManagerService( 1029): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@31cf1408:true
D/BluetoothAdapter( 6110): 30203534: getState() :  mService = null. Returning STATE_OFF
W/chromium( 6110): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
I/chromium( 6110): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=32 off=46780 len=2953
I/chromium( 6110): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:33 off:229536 len:643667
I/Adreno-EGL( 6110): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 6110): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 6110): Build Date: 12/12/14 금
I/Adreno-EGL( 6110): Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
I/Adreno-EGL( 6110): Remote Branch: 
I/Adreno-EGL( 6110): Local Patches: 
I/Adreno-EGL( 6110): Reconstruct Branch: 
,W/chromium( 6110): [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
,W/chromium( 6110): [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
W/art     ( 6110): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 6110): onDetachedFromWindow called when already detached. Ignoring
D/SystemWebViewEngine( 6110): CordovaWebView is running on device made by: LGE
,W/art     ( 6110): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 6110): Attempt to remove local handle scope entry from IRT, ignoring
,D/OpenGLRenderer( 6110): Render dirty regions requested: true
,I/OpenGLRenderer( 6110): Initialized EGL, version 1.4
D/OpenGLRenderer( 6110): Enabling debug mode 0
,D/Atlas   ( 6110): Validating map...
D/SplitWindow( 1029): check instance of lgWin Window{2517202 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,D/LgDataFeature( 6110): LgDataFeature() Constructor: none
D/LgDataFeature( 6110): LgDataFeature() Constructor Done, null
,I/SystemUI[Framework]( 1029): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x0, pkg=com.android.systemui
D/PhoneStatusBar( 1464): setSystemUiVisibility vis=0 mask=ffffffff oldVal=8000 newVal=0 diff=8000
I/[SystemUI]NavigationThemeResource( 1464): NavigationKey Color is changed(WHITE_WITH_SHADOW -> BLACK)
I/[SystemUI]NavigationThemeResource( 1464):  BarMode=0, Theme=WHITE, LightBackground=false (Transparent)
I/[SystemUI]NavigationThemeResource( 1464): , Keyguard show=false, IME shown=false, Panel expanded=false
W/PhoneWindowManagerEx( 1029): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx( 1029): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx( 1029): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework]( 1029): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@982b9e2,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework]( 1029): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
,I/Timeline( 6110): Timeline: Activity_idle id: android.os.BinderProxy@2d74073e time:112712
I/ActivityManager( 1029): Displayed com.test.thalitest/.MainActivity: +558ms (total +667ms)
I/Timeline( 1029): Timeline: Activity_windows_visible id: ActivityRecord{35a0df8f u0 com.test.thalitest/.MainActivity t4} time:112714
,I/chromium( 6110): [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
I/chromium( 6110): 
,D/JsMessageQueue( 6110): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log( 6110): JniHelper::setJavaVM(0xb487c280), pthread_self() = -1435202816
,I/chromium( 6110): [INFO:SkFontConfigInterface_android.cpp(247)] ---- failed to open </system/fonts/CutiveMono.ttf> as a font
I/chromium( 6110): 
,I/chromium( 6110): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,E/GBMv2   (  347): DFP En is all cleared set to be enabled
E/GBMv2   (  347): Set value is all cleared set the max
I/GBMv2   (  347): DFP Enabled. Ignore VFP set
W/jxcore-log( 6110): Initializing JXcore engine
W/jxcore-log( 6110): JXcore engine is ready
W/Thread-694( 6164): type=1400 audit(0.0:148): avc: denied { ioctl } for path="socket:[10248]" dev="sockfs" ino=10248 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
W/Thread-694( 6164): type=1400 audit(0.0:149): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3222 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
W/Thread-694( 6164): type=1400 audit(0.0:150): avc: denied { ioctl } for path="socket:[10036]" dev="sockfs" ino=10036 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
W/Thread-694( 6164): type=1400 audit(0.0:151): avc: denied { ioctl } for path="/cust" dev="mmcblk0p42" ino=2 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=dir
W/Thread-694( 6164): type=1400 audit(0.0:152): avc: denied { ioctl } for path="socket:[30090]" dev="sockfs" ino=30090 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
W/jxcore-log( 6110): Starting JXcore engine
W/jxcore-log( 6110): Platform android
W/jxcore-log( 6110): 
W/jxcore-log( 6110): Process ARCH arm
W/jxcore-log( 6110): 
,I/jxcore-log( 6110): JXcore Cordova bridge is ready!
I/jxcore-log( 6110): 
W/jxcore-log( 6110): JXcore engine is started
,I/CloudHub( 2205): [CLIENT][CloudHubClientFactory$1|onTick] Until finished: 19979
,I/jxcore-log( 6110): Toggling radios to true
I/jxcore-log( 6110): 
,D/BluetoothManagerService( 1029): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1029): enable():  mBluetooth =null mBinding = false
,D/LocationManagerService( 1029): getAllProviders()=[passive, gps, network]
D/Ulp_jni ( 1029): JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
D/Ulp_jni ( 1029): JNI:system_update. Event-4
D/BluetoothManagerService( 1029): Message: 1
D/BluetoothManagerService( 1029): MESSAGE_ENABLE: mBluetooth = null
D/WifiService( 1029): New client listening to asynchronous messages
I/ActivityManager( 1029): Start proc com.android.bluetooth for service com.android.bluetooth/.btservice.AdapterService: pid=6167 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008, 4002, 1023} abi=armeabi-v7a
D/WifiServiceImplEx( 1029): setWifiEnabled: true pid=6110, uid=10311, package= com.test.thalitest, App Lable : ThaliTest
,D/WifiService( 1029): setWifiEnabled: true pid=6110, uid=10311
E/WifiService( 1029): Invoking mWifiStateMachine.setWifiEnabled
D/LocationManagerService( 1029): getAllProviders()=[passive, gps, network]
D/Ulp_jni ( 1029): JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 1,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
D/Ulp_jni ( 1029): JNI:system_update. Event-4
E/WifiStateMachine( 1029):  InitialState CMD_START_SUPPLICANT 0 0
I/LGFTMITEM( 1029): [GET_FTM][id=6], offset=12288
D/WifiServiceImplEx( 1029): disconnect pid=6110, uid=10311, packageName=com.test.thalitest
D/WifiServiceImplEx( 1029): reconnect pid=6110, uid=10311, packageName=com.test.thalitest
I/jxcore-log( 6110): Radios toggled
I/jxcore-log( 6110): 
I/jxcore-log( 6110): My device name is: LGE-LG-D855
I/jxcore-log( 6110): 
E/WifiUtil( 1029): wfc_util_ffile_check_copy(): pid[1029] pDestFName[/data/misc/wifi/WCNSS_qcom_cfg.ini] pSourceFName[/system/etc/wifi/WCNSS_qcom_cfg.ini]
E/WifiUtil( 1029): wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
E/WifiUtil( 1029): wfc_util_ffile_check_copy(): pid[1029] pDestFName[/data/misc/wifi/WCNSS_qcom_wlan_nv.bin] pSourceFName[/system/etc/wifi/WCNSS_qcom_wlan_nv.bin]
E/WifiUtil( 1029): wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
I/WifiUtil( 1029): Intf0MacAddress=C49A027B60AC
E/WifiHW  ( 1029): unknown target_country: EU , set to default
E/WifiHW  ( 1029): [wifi_ensure_config_files] default country1 = GB
E/WifiHW  ( 1029): [wifi_ensure_config_files] default country2 = GB
I/WifiUtil( 1029): gEnableBmps=1
,W/ResourcesManager( 6167): Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
W/ResourcesManager( 6167): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 6167): Asset path '/system/framework/com.qcom.bluetooth.jar' does not exist or contains no resources.
W/ResourcesManager( 6167): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,D/BluetoothAdapterApp( 6167): Loading JNI Library
,D/SoftapController(  320): Softap fwReload - Ok
,D/Tethering( 1029): sendTetherStateChangedBroadcast 1, 0, 0
D/BluetoothAdapterApp( 6167): REFCOUNT: Constructed com.android.bluetooth.btservice.AdapterApp@1dbd568d Instance Count = 1
D/libc-netbsd(  320): default dns: query_ipv6=0, query_ipv4=0
D/CommandListener(  320): Setting iface cfg
D/CommandListener(  320): Trying to bring down wlan0
,D/DSQN    ( 1029): DNSproblemNotiEnabled is disabled ignore DNS fail CB
D/Tethering( 1029): InitialState.processMessage what=4
D/CommandListener(  320): Clearing all IP addresses on wlan0
I/ActivityManager( 1029): Start proc com.android.settings for broadcast com.android.settings/.deviceinfo.UsbSettingsReceiver: pid=6193 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,D/Tethering( 1029): sendTetherStateChangedBroadcast 0, 0, 0
E/WifiHW  ( 1029): Cannot open "/system/etc/wifi/autojoinconfig.txt": No such file or directory
D/BluetoothAdapterApp( 6167): onCreate
,E/WifiStateMachine( 1029): Couldn't get getWiFiOffloadingIface : 
E/WifiStateMachine( 1029): useWiFiOffloading() : false
E/WifiStateMachine( 1029): CONFIG_LGE_WLAN_PATH : true
D/WifiMonitor( 1029): startMonitoring(wlan0) with mConnected = false
D/WifiMonitor( 1029): connecting to supplicant
D/StatusBar.NetworkController( 1464): refreshViews: Data not connected!! Set no data type icon / Roaming
V/WfdStateTracker( 1958): WfdStateTracker handleDirectStateChangedEvent: 1
W/wpa_supplicant( 6202): type=1400 audit(0.0:153): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
W/wpa_supplicant( 6202): type=1400 audit(0.0:154): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
I/WifiServerServiceExt( 1029): WIFI_STATE_CHANGED_ACTION [2]
I/wpa_supplicant( 6202): Successfully initialized wpa_supplicant
,I/wpa_supplicant( 6202): rfkill: Cannot open RFKILL control device
I/wpa_supplicant( 6202): [LGE_PATCH] unset P2P_CAPABLE to ifname wlan0
D/ProfileConfigQcom( 6167): [BTUI] HeadsetService is supported
D/ProfileConfigQcom( 6167): Adding HeadsetService
D/ProfileConfigQcom( 6167): [BTUI] A2dpService is supported
D/ProfileConfigQcom( 6167): Adding A2dpService
D/ProfileConfigQcom( 6167): [BTUI] HidService is supported
D/ProfileConfigQcom( 6167): Adding HidService
D/ProfileConfigQcom( 6167): [BTUI] HealthService is supported
D/ProfileConfigQcom( 6167): Adding HealthService
D/LGBluetoothFeatureConfig( 6167): isSupportPan() :  mTargetOp=OPEN
D/ProfileConfigQcom( 6167): [BTUI] PanService is supported
D/ProfileConfigQcom( 6167): Adding PanService
D/ProfileConfigQcom( 6167): [BTUI] GattService is supported
D/ProfileConfigQcom( 6167): Adding GattService
D/ProfileConfigQcom( 6167): [BTUI] BluetoothMapService is supported
D/ProfileConfigQcom( 6167): Adding BluetoothMapService
D/ProfileConfigQcom( 6167): [BTUI] HeadsetClientService is NOT supported
,W/ResourcesManager( 6193): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6193): Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
W/ResourcesManager( 6193): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 6193): Asset path '/system/framework/com.lge.bluetooth.jar' does not exist or contains no resources.
W/ResourcesManager( 6193): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
W/ResourcesManager( 6193): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
D/BluetoothManagerService( 1029): Message: 20
D/BluetoothManagerService( 1029): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@1dcdbd:true
,D/BluetoothAdapterState( 6167): make
I/LGFMServiceAdapter( 6167): [FM] LGFMServiceAdapter : create
I/BluetoothAdapterState( 6167): Entering OffState
I/bluedroid-qcom( 6167): init
I/bte_conf( 6167): bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
I/bte_conf( 6167): bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
E/bt_osi_config( 6167): config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
I/bte_conf( 6167): bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
D/BTIF_CORE( 6167): [BTUI] lge_load_bluetooth_address
I/bluedroid-qcom( 6167): get_profile_interface socket
I/bluedroid-qcom( 6167): get_profile_interface map_client
,W/bdaddr_loader( 6226): type=1400 audit(0.0:155): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
W/bdaddr_loader( 6226): type=1400 audit(0.0:156): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
I/GKI_LINUX( 6167): gki_task_entry task_id=1 [BTIF] starting
D/BluetoothManagerService( 1029): BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
D/BluetoothManagerService( 1029): Message: 40
D/BluetoothManagerService( 1029): MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
I/bluedroid-qcom( 6167): config_hci_snoop_log
D/BluetoothManagerService( 1029): Calling onBluetoothServiceUp callbacks
D/BluetoothManagerService( 1029): Broadcasting onBluetoothServiceUp() to 7 receivers.
D/lge_bdaddr_loader( 6226): [BTUI] bdaddr_loader ::: START
D/lge_bdaddr_loader( 6226): [BTUI] bluetooth_load_bdaddress
I/LGFTMITEM( 6226): [GET_FTM][id=8], offset=16384
D/lge_bdaddr_loader( 6226): [BTUI] bdaddr to set in property : 58:3F:54:73:64:C0
V/LGMDMManagerInternal( 6167): Create singleton instance
E/lge_bdaddr_loader( 6226): [BTUI] bluetooth_load_bdaddress : OK => 58:3F:54:73:64:C0
D/lge_bdaddr_loader( 6226): [BTUI] bdaddr_loader ::: END
,D/BluetoothAdapterProperties( 6167): Address is:58:3F:54:73:64:C0
D/BluetoothManagerService( 1029): Bluetooth Adapter name changed to G3-1
D/BluetoothManagerService( 1029): Stored Bluetooth name: G3-1
D/BluetoothAdapterProperties( 6167): Name is: G3-1
,I/wpa_supplicant( 6202): rfkill: Cannot open RFKILL control device
D/BluetoothAdapterState( 6167): CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
D/BluetoothAdapterProperties( 6167): Setting state to 11
I/BluetoothAdapterState( 6167): Bluetooth adapter state changed: 10-> 11
I/LGBluetoothServiceJni( 6167): classInitNative: succeeds
,D/BluetoothManagerService( 1029): Message: 60
D/BluetoothManagerService( 1029): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
D/BluetoothManagerService( 1029): Bluetooth State Change Intent: 10 -> 11
D/BluetoothBondStateMachine( 6167): make
I/[SystemUI]BluetoothHandler( 1464): Receive : BluetoothAdapter.ACTION_STATE_CHANGED
D/LGBluetoothAPIService( 1958): [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
D/BluetoothAdapterService( 6167): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a0cabc
D/LGBluetoothServiceAdapter( 6167): [BTUI] check adapter is available - false.
D/BluetoothAdapterService( 6167): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a0cabc
D/LGBluetoothServiceAdapter( 6167): [BTUI] check adapter is available - true : set adapter available.
D/LGBluetoothSettingsDBObserver( 6167): [BTUI] register observer for LG device name DB
I/BluetoothBondStateMachine( 6167): StableState(): Entering Off State
D/UsbSettingsReceiver( 6193): [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
D/UsbSettingsReceiver( 6193): [AUTORUN] sys.usb.config = ptp_only,adb
D/UsbSettingsReceiver( 6193): [AUTORUN] sys.usb.state = ptp_only,adb
D/UsbSettingsReceiver( 6193): [AUTORUN] persist.sys.usb.config = ptp_only,adb
D/UsbSettingsReceiver( 6193): [AUTORUN] onReceive() : app userid = 0, current userid = 0
,E/BluetoothAdapterService( 6167): File transfer profiles supported!!
D/UsbSettingsControl( 6193): [AUTORUN] getUsbConnected() : connected=true
D/UsbSettingsReceiver( 6193): [AUTORUN] onReceive() : availableList=[wlan0]
D/UsbSettingsReceiver( 6193): [AUTORUN] onReceive() : activeList=[]
D/UsbSettingsReceiver( 6193): [AUTORUN] onReceive() : errorList=[]
D/BluetoothHeadset( 1861): Proxy object connected
D/UsbSettingsControl( 6193): [AUTORUN] isAutorunTimer() : mAutorunChanging=false
D/UsbSettingsReceiver( 6193): [AUTORUN] onReceive() : TetherState Changed=wlan0
D/UsbSettingsControl( 6193): [AUTORUN] setTetherStatus() : status=false
D/BluetoothHeadset( 1861): Proxy object connected
D/BluetoothHeadset( 1861): Proxy object connected
D/BluetoothHeadset( 1029): Proxy object connected
,I/ActivityManager( 1029): Killing 5752:com.android.defcontainer/u0a4 (adj 15): empty #17
D/HeadsetService( 6167): Received start request. Starting profile...
I/LGBluetoothHeadsetServiceJni( 6167): classInitNative: succeeds
D/LGBluetoothHfpAdapter( 6167): Version 1.6
D/LGBluetoothFeatureConfig( 6167): isPrivacyLogsEnabled : true
E/BluetoothAdapterService( 6167): File transfer profiles supported!!
,I/wpa_supplicant( 6202): [LGE_WLAN_PATCH]P2P 5GHz support level:2(0:no 1:gconly 2:gconly_UNII1 3:full)
I/wpa_supplicant( 6202): p2p0: CTRL-EVENT-AVOID-FREQ ranges=
I/wpa_supplicant( 6202): wlan0: CTRL-EVENT-SCAN-STARTED 
I/BluetoothHeadsetServiceJni( 6167): classInitNative: succeeds
D/HeadsetStateMachine( 6167): make
E/WifiStateMachine( 1029):  SupplicantStartingState CMD_SET_OPERATIONAL_MODE 1 0
E/WifiStateMachine( 1029):  SupplicantStartingState CMD_START_DRIVER 0 0
E/WifiStateMachine( 1029):  SupplicantStartingState CMD_SET_HIGH_PERF_MODE 0 0
E/WifiStateMachine( 1029):  DefaultState CMD_SET_HIGH_PERF_MODE 0 0
E/WifiStateMachine( 1029):  SupplicantStartingState CMD_DISCONNECT 0 0
D/WifiMonitor( 1029): Event [IFNAME=p2p0 CTRL-EVENT-AVOID-FREQ ranges=]
D/WifiMonitor( 1029): Dropping event because (p2p0) is stopped
D/WifiMonitor( 1029): Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1029): WifiMonitor:wlan0 cnt=0 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1029): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1029): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
E/WifiStateMachine( 1029):  DefaultState CMD_DISCONNECT 0 0
,E/WifiStateMachine( 1029):  SupplicantStartingState CMD_RECONNECT 0 0
E/WifiStateMachine( 1029):  DefaultState CMD_RECONNECT 0 0
E/WifiStateMachine( 1029):  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1029):  DefaultState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1029):  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1029):  DefaultState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1029):  SupplicantStartingState SUP_CONNECTION_EVENT 0 0
D/WifiNative-wlan0( 1029): doString: [DRIVER MACADDR]
D/WifiNative-wlan0( 1029):    returned Macaddr = c4:9a:02:7b:60:ac
D/WifiStateMachine( 1029): MAC Addr from driver = c4:9a:02:7b:60:ac
D/WifiOffDelayIfNotUsed( 1029): setPowerSaveActivated(false)
D/LgDataFeature( 6167): LgDataFeature() Constructor: none
D/LgDataFeature( 6167): LgDataFeature() Constructor Done, null
W/libprocessgroup( 1029): failed to open /acct/uid_10004/pid_5752/cgroup.procs: No such file or directory
,E/BluetoothAdapterService( 6167): File transfer profiles supported!!
E/WifiStateMachine( 1029): Couldn't get getWiFiOffloadingIface : 
E/WifiStateMachine( 1029): useWiFiOffloading() : false
E/WifiStateMachine( 1029): CONFIG_LGE_WLAN_PATH : true
D/HeadsetStateMachine( 6167): max_hf_connections = 1
D/WifiNative-wlan0( 1029): doBoolean: SET update_config 1
I/bluedroid-qcom( 6167): get_profile_interface handsfree
D/WifiNative-wlan0( 1029): SET update_config 1: returned true
D/WifiConfigStore( 1029): Loading config and enabling all networks 
D/WifiNative-wlan0( 1029): doString: [LIST_NETWORKS]
D/WifiNative-wlan0( 1029):    returned network id / ssid / bssid / flags 0	NG700	any	
W/Settings( 1029): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1029): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WfdService( 1958): Waiting for WifiP2p enabling
D/StatusBar.NetworkController( 1464): refreshViews: Data not connected!! Set no data type icon / Roaming
,E/WifiConfigStore( 1029): readNetworkVariablesFromSupplicantFile key=psk
V/ToneGenerator( 6167): ToneGenerator constructor: streamType=8, volume=1.000000
E/WifiConfigStore( 1029): readNetworkVariableFromSupplicantFile ssid=["NG700"] key=psk
E/WifiConfigStore( 1029): Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
I/WifiServerServiceExt( 1029): WIFI_STATE_CHANGED_ACTION [3]
V/AudioPolicyService(  325): registerClient() client 0xb54f4ee0, uid 1002
V/AudioPolicyManager(  325): getOutput() device 2, stream 8, samplingRate 0, format 0, channelMask 3, flags 0
V/AudioPolicyManagerEx(  325): AudioPolicyManagerEx: getOutputForDevice
D/UsbSettingsReceiver( 6193): [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
V/AudioPolicyManagerEx(  325): getOutput() returns output 2
D/UsbSettingsReceiver( 6193): [AUTORUN] sys.usb.config = ptp_only,adb
D/UsbSettingsReceiver( 6193): [AUTORUN] sys.usb.state = ptp_only,adb
D/UsbSettingsReceiver( 6193): [AUTORUN] persist.sys.usb.config = ptp_only,adb
V/AudioSystem( 6167): getOutputSamplingRate() no output descriptor for output 2 in gOutputs
V/AudioFlinger(  325): registerClient() client 0xb14333a0, pid 6167
D/WifiStateMachine( 1029): enableVerboseLogging : level 2
D/WifiNative-wlan0( 1029): doBoolean: SET device_name g3_global_com
V/ToneGenerator( 6167): Create Track: 0xb4928080
V/AudioTrack( 6167): set(): streamType 8, sampleRate 0, format 0x1, channelMask 0x1, frameCount 0, flags #4, notificationFrames 0, sessionId 0, transferType 1
V/AudioTrack( 6167): set() streamType 8, sampleRate 0, format 1, frameCount 0, flags 0004
D/WifiNative-wlan0( 1029): SET device_name g3_global_com: returned true
D/WifiNative-wlan0( 1029): doBoolean: SET manufacturer LGE
D/WifiNative-wlan0( 1029): SET manufacturer LGE: returned true
D/WifiNative-wlan0( 1029): doBoolean: SET model_name LG-D855
I/WifiServerServiceExt( 1029): batteryPsActivateMsgHandler : state:0 event:3
D/WifiNative-wlan0( 1029): SET model_name LG-D855: returned true
D/WifiNative-wlan0( 1029): doBoolean: SET model_number LG-D855
V/AudioPolicyManager(  325): getOutputForAttr() usage=3, content=4, tag= flags=00000000
V/AudioPolicyManager(  325): getOutputForAttr() device 2, samplingRate 0, format 0, channelMask 3, flags 0
V/AudioPolicyManagerEx(  325): AudioPolicyManagerEx: getOutputForDevice
V/AudioPolicyManagerEx(  325): getOutput() returns output 2
V/AudioSystem( 6167): getOutputSamplingRate() no output descriptor for output 2 in gOutputs
D/WifiNative-wlan0( 1029): SET model_number LG-D855: returned true
D/WifiNative-wlan0( 1029): doBoolean: SET serial_number LGD8553bed2d08
D/WifiNative-wlan0( 1029): SET serial_number LGD8553bed2d08: returned true
D/WifiNative-wlan0( 1029): doBoolean: SET config_methods physical_display virtual_push_button
D/WifiNative-wlan0( 1029): SET config_methods physical_display virtual_push_button: returned true
D/WifiNative-wlan0( 1029): doBoolean: SET device_type 10-0050F204-5
D/WifiNative-wlan0( 1029): SET device_type 10-0050F204-5: returned true
D/WifiStateMachine( 1029): Setting OUI to DA-A1-19
D/WifiNative-wlan0( 1029): doBoolean: SCAN_INTERVAL 120
D/WifiNative-wlan0( 1029): SCAN_INTERVAL 120: returned true
D/WifiNative-HAL( 1029): Setting external_sim to 1
D/WifiNative-wlan0( 1029): doBoolean: SET external_sim 1
,D/WifiNative-wlan0( 1029): SET external_sim 1: returned true
I/WifiNative-HAL( 1029): startHal
E/wifi    ( 1029): getStaticLongField sWifiHalHandle 0x988c38dc
E/WifiHAL ( 1029): Could not connect handle
D/WfdsService( 1958): Supplicant Connection state is changed : true
D/wifi    ( 1029): halHandle = 0x0, mVM = 0xb487c280, mCls = 0x102222
I/WifiNative-HAL( 1029): Could not start hal
D/WifiStateMachine( 1029): Setting OUI to DA-A1-19
I/WifiNative-HAL( 1029): startHal
,E/wifi    ( 1029): getStaticLongField sWifiHalHandle 0x988c385c
E/WifiHAL ( 1029): Could not connect handle
D/wifi    ( 1029): halHandle = 0x0, mVM = 0xb487c280, mCls = 0x102226
I/WifiNative-HAL( 1029): Could not start hal
D/WfdsService( 1958): DefaultState - WIFI_SUPPLICANT_CONNECTED
D/WifiNative-wlan0( 1029): doBoolean: STA_AUTOCONNECT 1
D/WfdsService( 1958): Set the WFDS Monitor: true
D/WifiNative-wlan0( 1029): STA_AUTOCONNECT 1: returned true
D/WifiNative-wlan0( 1029): doBoolean: DRIVER BTCOEXSCAN-STOP
I/wpa_supplicant( 6202): wpa_driver_nl80211_ext_driver_cmd BTCOEXSCAN-STOP
D/WifiNative-wlan0( 1029): DRIVER BTCOEXSCAN-STOP: returned true
D/WfdsMonitor( 1958): WfdsMonitorThread create
D/WfdsMonitor( 1958): WFDS Monitor is created and started
D/WfdsService( 1958): WiFi: Supplicant connection re-established
V/AudioSystem(  325): ioConfigChanged() event 0, ioHandle 4
V/AudioSystem(  325): ioConfigChanged() opening already existing output! 4
V/AudioSystem( 2205): ioConfigChanged() event 0, ioHandle 4
V/AudioSystem( 2205): ioConfigChanged() opening already existing output! 4
V/AudioSystem( 3280): ioConfigChanged() event 0, ioHandle 4
V/AudioSystem( 3280): ioConfigChanged() opening already existing output! 4
V/AudioSystem( 6167): ioConfigChanged() event 0, ioHandle 4
V/AudioSystem( 6167): ioConfigChanged() new output samplingRate 48000, format 0x1 channel mask 0x3 frameCount 960 latency 80
,D/WifiNative-wlan0( 1029): doBoolean: DRIVER RXFILTER-STOP
I/wpa_supplicant( 6202): wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
V/AudioSystem( 1464): ioConfigChanged() event 0, ioHandle 4
V/AudioSystem( 1464): ioConfigChanged() opening already existing output! 4
D/WifiNative-wlan0( 1029): DRIVER RXFILTER-STOP: returned true
D/WifiHS20( 1029): hidePasspointNotification off =false
V/AudioSystem(  325): ioConfigChanged() event 0, ioHandle 2
V/AudioSystem(  325): ioConfigChanged() opening already existing output! 2
V/AudioSystem( 6167): ioConfigChanged() event 0, ioHandle 2
V/AudioSystem( 6167): ioConfigChanged() new output samplingRate 48000, format 0x5 channel mask 0x3 frameCount 960 latency 50
V/AudioSystem( 1029): ioConfigChanged() event 0, ioHandle 4
,V/AudioSystem( 1029): ioConfigChanged() opening already existing output! 4
V/AudioSystem( 1029): ioConfigChanged() event 0, ioHandle 2
V/AudioSystem( 1029): ioConfigChanged() opening already existing output! 2
V/AudioSystem( 3280): ioConfigChanged() event 0, ioHandle 2
V/AudioSystem( 3280): ioConfigChanged() opening already existing output! 2
V/AudioSystem( 1464): ioConfigChanged() event 0, ioHandle 2
,V/AudioSystem( 1464): ioConfigChanged() opening already existing output! 2
V/AudioSystem( 2205): ioConfigChanged() event 0, ioHandle 2
V/AudioSystem( 2205): ioConfigChanged() opening already existing output! 2
I/AudioFlinger(  325): isAudioPlaybackHookOn() false
V/AudioPolicyManager(  325): getOutputForAttr() usage=3, content=4, tag= flags=00000000
V/AudioPolicyManager(  325): getOutputForAttr() device 2, samplingRate 48000, format 1, channelMask 1, flags 4
,V/AudioPolicyManagerEx(  325): AudioPolicyManagerEx: getOutputForDevice
V/AudioPolicyManagerEx(  325): getOutput() returns output 2
V/AudioSystem( 6167): getLatency() output 2, latency 50
V/AudioSystem( 6167): getFrameCount() output 2, frameCount 960
V/AudioTrack( 6167): createTrack_l() output 2 afLatency 50
V/AudioFlinger(  325): [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
,V/AudioFlinger(  325): [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
V/AudioFlinger(  325): [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
V/AudioFlinger(  325): [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
V/AudioFlinger(  325): createTrack() lSessionId: 16
V/AudioTrack( 6167): AUDIO_OUTPUT_FLAG_FAST successful; frameCount 480
,V/AudioFlinger(  325): acquiring 16 from 6167, for 6167
V/AudioFlinger(  325):  added new entry for 16
I/StatusBar.NetworkController( 1464): networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
W/Settings( 1029): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1029): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/StatusBar.NetworkController( 1464): mWifiConnected = false, mWifiLevel = 0
,D/WifiOffDelayIfNotUsed( 1029): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
D/WifiNative-wlan0( 1029): doBoolean: DRIVER RXFILTER-REMOVE 3
I/wpa_supplicant( 6202): wpa_driver_nl80211_ext_driver_cmd RXFILTER-REMOVE 3
D/WifiNative-wlan0( 1029): DRIVER RXFILTER-REMOVE 3: returned true
D/WifiNative-wlan0( 1029): doBoolean: DRIVER RXFILTER-START
I/wpa_supplicant( 6202): wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
,E/CtrlSupplicant( 1958): Access OK "@android:wpa_wlan0"
E/CtrlSupplicant( 1958): Succeed to open control connection
E/CtrlSupplicant( 1958): Succeed to open monitor connection
D/WfdsMonitor( 1958): Supplicant connection established
D/WfdsService( 1958): Connected to the supplicant for wfds
V/ToneGenerator( 6167): ToneGenerator INIT OK, time: 116179
D/BluetoothAdapterService( 6167): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a0cabc
D/WifiNative-wlan0( 1029): DRIVER RXFILTER-START: returned true
D/WifiNative-wlan0( 1029): doBoolean: DRIVER RXFILTER-STOP
V/AudioSystem( 1861): ioConfigChanged() event 0, ioHandle 4
V/AudioSystem( 1861): ioConfigChanged() opening already existing output! 4
I/wpa_supplicant( 6202): wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
V/AudioSystem( 1861): ioConfigChanged() event 0, ioHandle 2
V/AudioSystem( 1861): ioConfigChanged() opening already existing output! 2
D/WifiNative-wlan0( 1029): DRIVER RXFILTER-STOP: returned true
D/HeadsetStateMachine( 6167): Enter Disconnected: -2, size: 0
D/WifiNative-wlan0( 1029): doBoolean: DRIVER RXFILTER-REMOVE 2
D/HeadsetPhoneState( 6167): [BTUI] listenForPhoneState : start = false
D/LGBluetoothHfpManager( 6167): [BTUI] listenForMultiSimPhoneState : start = false
I/wpa_supplicant( 6202): android_multicast_filter_startstop : multicast filter set
D/HeadsetStateMachine( 6167): [BTUI] change sampling rate to 8000 when device is disconnected
D/WifiNative-wlan0( 1029): DRIVER RXFILTER-REMOVE 2: returned true
D/WifiNative-wlan0( 1029): doBoolean: DRIVER RXFILTER-START
I/wpa_supplicant( 6202): wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
V/AudioFlinger(  325): setParameters(): io 0, keyvalue bt_samplerate=8000, calling pid 6167
D/WifiNative-wlan0( 1029): DRIVER RXFILTER-START: returned true
E/BluetoothAdapterService( 6167): File transfer profiles supported!!
E/WifiNative: ( 1029): [116,166,254 us] RECONNECT  stack:logDbg - reconnect - enter - invokeEnterMethods - performTransitions
D/audio_hw_primary(  325): adev_set_parameters: enter: bt_samplerate=8000
V/voice   (  325): voice_set_parameters: enter: bt_samplerate=8000
V/compress_voip(  325): voice_extn_compress_voip_set_parameters: enter: bt_samplerate=8000
V/compress_voip(  325): voice_extn_compress_voip_set_parameters: exit
V/voice   (  325): voice_set_parameters: exit with code(0)
V/msm8974_platform_lge(  325): LGE_platform_set_parameters: enter: bt_samplerate=8000
V/msm8974_platform(  325): platform_set_parameters: enter: bt_samplerate=8000
V/msm8974_platform(  325): platform_set_parameters: exit with code(0)
V/lge_audio_loopback(  325): lge_platform_set_loopback_parameters: enter: 
V/audio_hw_primary(  325): adev_set_parameters: exit with code(0)
E/audio_a2dp_hw(  325): adev_set_parameters: ERROR: set param called even when stream out is null
D/WifiNative-wlan0( 1029): doBoolean: RECONNECT
D/BluetoothAdapterService( 6167): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a0cabc
V/BluetoothPbapReceiver( 6167): PbapReceiver onReceive 
V/BluetoothPbapReceiver( 6167): ***********action = android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothPbapReceiver( 6167): ***********state = 11
D/WifiNative-wlan0( 1029): RECONNECT: returned true
D/WifiNative-wlan0( 1029): doString: [STATUS]
D/WifiMonitor( 1029): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
E/WifiMonitor( 1029): WifiMonitor:wlan0 cnt=1 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
D/WifiNative-wlan0( 1029):    returned wpa_state=SCANNING p2p_device_address=02:9a:02:7b:60:ac address=c4:9a:02:7b:60:ac uuid=530d3fd0-1ba3-5409-a336-ff4e42af59a2
D/WifiNative-wlan0( 1029): doBoolean: DRIVER SETSUSPENDMODE 1
I/wpa_supplicant( 6202): wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 1
D/WifiNative-wlan0( 1029): DRIVER SETSUSPENDMODE 1: returned true
V/ToneGenerator( 6167): ToneGenerator destructor
V/ToneGenerator( 6167): stopTone
V/ToneGenerator( 6167): Delete Track,: 0xb4928080
V/AudioTrack( 6167): ~AudioTrack, releasing session id from 6167 on behalf of 6167
V/AudioPolicyService(  325): AudioCommandThread() adding release output 2
V/AudioPolicyService(  325): inserting command: 6 at index 0, num commands 0
V/AudioFlinger(  325): PlaybackThread::Track destructor
V/AudioPolicyService(  325): AudioCommandThread() waking up
V/AudioFlinger(  325): removeClient_l() pid 6167, calling pid 325
V/AudioFlinger(  325): releasing 16 from 6167 for 6167
V/AudioFlinger(  325):  decremented refcount to 0
V/AudioPolicyService(  325): AudioCommandThread() processing release output 2
V/AudioFlinger(  325): purging stale effects
V/AudioPolicyManager(  325): releaseOutput() 2
V/AudioPolicyService(  325): AudioCommandThread() going to sleep
D/WifiNative-wlan0( 1029): doBoolean: SET ps 1
D/StatusBar.NetworkController( 1464): refreshViews: Data not connected!! Set no data type icon / Roaming
D/WifiNative-wlan0( 1029): SET ps 1: returned true
D/LGWifiP2pService( 1029): P2pDisabledState{ when=-1ms what=131203 target=com.android.internal.util.StateMachine$SmHandler }
D/UsbSettingsReceiver( 6193): [AUTORUN] onReceive() : app userid = 0, current userid = 0
,D/WifiService( 1029): New client listening to asynchronous messages
D/CommandListener(  320): Setting iface cfg
D/CommandListener(  320): Trying to bring up p2p0
D/WifiMonitor( 1029): startMonitoring(p2p0) with mConnected = true
D/LGWifiP2pService( 1029): P2pEnablingState
D/LGWifiP2pService( 1029): P2pEnablingState{ when=0 what=147457 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1029): P2p socket connection successful
D/LGWifiP2pService( 1029): P2pEnabledState
I/ActivityManager( 1029): Start proc com.lge.lifetracker for broadcast com.lge.lifetracker/.receiver.HealthDeviceReceiver: pid=6237 uid=10037 gids={50037, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
,E/WifiStateMachine( 1029):  DisconnectedState CMD_SET_OPERATIONAL_MODE 1 0
,E/WifiStateMachine( 1029):  DisconnectedState CMD_START_DRIVER 0 0
,E/BluetoothAdapterService( 6167): File transfer profiles supported!!
D/BluetoothA2dp( 1029): Proxy object connected
E/WifiStateMachine( 1029):  ConnectModeState CMD_START_DRIVER 0 0
D/A2dpService( 6167): Received start request. Starting profile...
I/BluetoothAvrcpServiceJni( 6167): classInitNative: succeeds
E/WifiStateMachine( 1029):  DriverStartedState CMD_START_DRIVER 0 0
D/LGWifiP2pService( 1029): sending p2p connection changed broadcast
V/Avrcp   ( 6167): make
V/WfdStateTracker( 1958): WfdStateTracker handleDirectStateChangedEvent: 2
D/Avrcp   ( 6167): [BTUI] Use Native AVRCP : init jni
D/WfdsService( 1958): WifiP2pState is changed : true
I/bluedroid-qcom( 6167): get_profile_interface avrcp
D/WfdsService( 1958): Receive the WFDS_ENABLE Method
D/WfdsService( 1958): Set the WFDS Monitor: true
D/WfdsService( 1958): Connected to the supplicant for wfds
D/WfdsJNI ( 1958): doCommand: WFDS_SET TRUE
I/wpa_supplicant( 6202): WFDS: wfds_supplicant_wfds_cmd: cmd = SET TRUE
D/WifiNative-p2p0( 1029): doBoolean: SET persistent_reconnect 1
D/WfdsJNI ( 1958): doCommand: WFDS_GET_MAC_ADDRESS
I/wpa_supplicant( 6202): WFDS: wfds_supplicant_wfds_cmd: cmd = GET_MAC_ADDRESS
D/WfdsJNI ( 1958): doCommand: IFNAME=wlan0 GET_CAPABILITY channels
D/UsbSettingsControl( 6193): [AUTORUN] getUsbConnected() : connected=true
D/UsbSettingsReceiver( 6193): [AUTORUN] onReceive() : availableList=[]
D/WfdsService( 1958): selectPreferredScanChannel [36]
D/UsbSettingsReceiver( 6193): [AUTORUN] onReceive() : activeList=[]
D/WfdsService( 1958): STATE : WfdsEnabledState - enter: this device mac 02:9a:02:7b:60:ac
D/UsbSettingsReceiver( 6193): [AUTORUN] onReceive() : errorList=[]
,D/UsbSettingsControl( 6193): [AUTORUN] isAutorunTimer() : mAutorunChanging=false
D/UsbSettingsControl( 6193): [AUTORUN] setTetherStatus() : status=false
D/WifiNative-p2p0( 1029): SET persistent_reconnect 1: returned true
D/WifiScanningService( 1029): SCAN_AVAILABLE : 3
,D/WifiNative-p2p0( 1029): doBoolean: SET device_name G3-1
D/WifiScanningService( 1029): DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
D/RttService( 1029): SCAN_AVAILABLE : 3
I/WifiNative-HAL( 1029): startHal
D/RttService( 1029): DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-p2p0( 1029): SET device_name G3-1: returned true
D/LGWifiP2pService( 1029): [LGE_P2P] initializeP2pSettings() check postfix
,D/LGWifiP2pService( 1029): before postfix = G3-1
D/WifiServerServiceExt( 1029): postfix byte check : 4
D/LGWifiP2pService( 1029): after postfix = G3-1
D/WifiNative-p2p0( 1029): doBoolean: SET p2p_ssid_postfix -G3-1
D/WfdsService( 1958): WIFI_P2P_CONNECTION_CHANGED_ACTION
D/WfdsService( 1958): isConnected: false
D/WifiNative-p2p0( 1029): SET p2p_ssid_postfix -G3-1: returned true
E/wifi    ( 1029): getStaticLongField sWifiHalHandle 0x94e6c99c
,D/WifiNative-p2p0( 1029): doBoolean: SET device_type 10-0050F204-5
E/WifiHAL ( 1029): Could not connect handle
D/wifi    ( 1029): halHandle = 0x0, mVM = 0xb487c280, mCls = 0x102252
I/WifiNative-HAL( 1029): Could not start hal
E/WifiScanningService( 1029): could not start HAL
D/WifiNative-p2p0( 1029): SET device_type 10-0050F204-5: returned true
D/WifiNative-p2p0( 1029): doBoolean: SET config_methods virtual_push_button physical_display keypad
,E/WifiStateMachine( 1029):  DisconnectedState what:132106 1 0
D/WifiNative-p2p0( 1029): SET config_methods virtual_push_button physical_display keypad: returned true
D/WifiNative-p2p0( 1029): doBoolean: P2P_SET conc_pref p2p
D/WifiNative-p2p0( 1029): P2P_SET conc_pref p2p: returned true
D/WifiNative-HAL( 1029): p2pGetDeviceAddress
E/WifiStateMachine( 1029):  ConnectModeState what:132106 1 0
D/WifiNative-HAL( 1029): p2pGetDeviceAddress returning 02:9a:02:7b:60:ac
,E/WifiStateMachine( 1029):  DriverStartedState what:132106 1 0
I/WifiServerServiceExt( 1029): setWifiDualbandAPConnection band : 1
E/wpa_supplicant( 6202): nWIFIDualbandAPConnection: 1
E/WifiStateMachine( 1029):  DisconnectedState what:132096 -100 0
V/AudioManager( 6167): registerRemoteController: size of Media player list: 0
E/WifiStateMachine( 1029):  ConnectModeState what:132096 -100 0
E/WifiStateMachine( 1029):  DriverStartedState what:132096 -100 0
I/WifiServerServiceExt( 1029): set CMD_DISCONNECT_RSSI_LVL : -100
E/wpa_supplicant( 6202): disconnect_rssi_lvl: -100
E/WifiStateMachine( 1029):  DisconnectedState CMD_SET_COUNTRY_CODE 1 0 cz
E/AudioManager( 6167): No RCC entry present to update
E/RemoteController( 6167): Cannot set synchronization mode on an unregistered RemoteController
E/WifiStateMachine( 1029):  ConnectModeState CMD_SET_COUNTRY_CODE 1 0 cz
E/WifiStateMachine( 1029):  DriverStartedState CMD_SET_COUNTRY_CODE 1 0 cz
D/WifiNative-wlan0( 1029): doBoolean: DRIVER COUNTRY CZ
I/BluetoothAvrcpQcomServiceJni( 6167): classInitQcomNative: succeeds
I/wpa_supplicant( 6202): wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
D/LGBluetoothAvrcpQcomAdapter( 6167): [BTUI] Use QCOM AVRCP 1.5 : init jni, browsing = false
I/BluetoothAvrcpQcomServiceJni( 6167): initQcomNative: succeeds
I/wpa_supplicant( 6202): wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
I/wpa_supplicant( 6202): [LGE_PATCH] driver_cmd() country:CZ
I/wpa_supplicant( 6202): p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
I/wpa_supplicant( 6202): p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
D/WfdsMonitor( 1958): Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
,D/WfdsMonitor( 1958): Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
D/WifiMonitor( 1029): Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
E/WifiMonitor( 1029): WifiMonitor:wlan0 cnt=2 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
E/WifiMonitor( 1029): handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
E/WifiMonitor( 1029): handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
D/WifiMonitor( 1029): Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
E/WifiMonitor( 1029): WifiMonitor:p2p0 cnt=3 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
E/WifiMonitor( 1029): handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
E/WifiMonitor( 1029): handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
D/WifiMonitor( 1029): Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
E/WifiMonitor( 1029): WifiMonitor:p2p0 cnt=4 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
E/WifiMonitor( 1029): handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
E/WifiMonitor( 1029): handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
D/WifiNative-wlan0( 1029): DRIVER COUNTRY CZ: returned true
E/WifiStateMachine( 1029):  DisconnectedState CMD_SET_FREQUENCY_BAND 0 0
E/WifiStateMachine( 1029):  ConnectModeState CMD_SET_FREQUENCY_BAND 0 0
E/WifiStateMachine( 1029):  DriverStartedState CMD_SET_FREQUENCY_BAND 0 0
D/WifiNative-wlan0( 1029): doBoolean: DRIVER SETBAND 0
I/wpa_supplicant( 6202): wpa_driver_nl80211_ext_driver_cmd SETBAND 0 - interface name wlan0
I/wpa_supplicant( 6202): wlan0: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
D/WifiMonitor( 1029): Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN]
E/WifiMonitor( 1029): WifiMonitor:wlan0 cnt=5 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
E/WifiMonitor( 1029): handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
E/WifiMonitor( 1029): handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
D/WifiNative-wlan0( 1029): DRIVER SETBAND 0: returned true
D/WifiNative-wlan0( 1029): doBoolean: BSS_FLUSH 0
D/WifiNative-wlan0( 1029): BSS_FLUSH 0: returned true
D/WifiNative-wlan0( 1029): doBoolean: SCAN
D/WifiNative-wlan0( 1029): SCAN: returned false
E/WifiStateMachine( 1029):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 1 0 rt=116247  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
I/ActivityManager( 1029): Start proc com.lge.formmanager for broadcast com.lge.formmanager/.FormServiceReceiver: pid=6256 uid=10026 gids={50026, 9997, 3003, 1028} abi=armeabi-v7a
D/LGWifiP2pService( 1029): DeviceAddress: 02:9a:02:7b:60:ac
D/WifiNative-p2p0( 1029): doBoolean: P2P_FLUSH
E/WifiStateMachine( 1029):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 1 0 rt=116259  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
,E/WifiStateMachine( 1029):  DisconnectedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
E/WifiStateMachine( 1029):  ConnectModeState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
E/WifiStateMachine( 1029):  DriverStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
D/WifiNative-p2p0( 1029): P2P_FLUSH: returned true
D/WifiNative-p2p0( 1029): doBoolean: P2P_SERVICE_FLUSH
D/WifiNative-p2p0( 1029): P2P_SERVICE_FLUSH: returned true
E/WifiStateMachine( 1029):  SupplicantStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
D/WifiNative-p2p0( 1029): doString: [LIST_NETWORKS]
D/WifiNative-p2p0( 1029):    returned network id / ssid / bssid / flags
D/WifiNative-p2p0( 1029): doBoolean: SAVE_CONFIG
E/WifiStateMachine( 1029):  DefaultState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
D/LGBluetoothAvrcpQcomAdapter( 6167): [BTUI] [+] updateMediaPlayerInfo
I/WfdStateTracker( 1958): handleP2pThisDeviceChanged
D/WfdsService( 1958): WIFI_P2P_THIS_DEVICE_CHANGED_ATCION
D/WfdsService( 1958): Update P2p Interface State: 3
I/StatusBar.NetworkController( 1464): networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1464): mWifiConnected = false, mWifiLevel = 0
,W/Settings( 1029): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1029): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1029): NETWORK_STATE_CHANGED_ACTION [SCANNING]
E/BluetoothAdapterService( 6167): File transfer profiles supported!!
D/WifiNative-p2p0( 1029): SAVE_CONFIG: returned true
D/LGWifiP2pService( 1029): sending p2p persistent groups changed broadcast
D/LGWifiP2pService( 1029): InactiveState
D/LGWifiP2pService( 1029): InactiveState{ when=-75ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1029): P2pEnabledState{ when=-75ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-p2p0( 1029): doBoolean: DRIVER COUNTRY CZ
,D/WifiServerServiceExt( 1029): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1029): setSupplicantStateSCANNING
D/StatusBar.NetworkController( 1464): refreshViews: Data not connected!! Set no data type icon / Roaming
I/wpa_supplicant( 6202): wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
I/wpa_supplicant( 6202): p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
I/wpa_supplicant( 6202): [LGE_PATCH] driver_cmd() country:CZ
I/wpa_supplicant( 6202): p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
I/wpa_supplicant( 6202): p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
D/WifiNative-p2p0( 1029): DRIVER COUNTRY CZ: returned true
D/LGWifiP2pService( 1029): InactiveState{ when=-63ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1029): P2pEnabledState{ when=-63ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1029): InactiveState{ when=-6ms what=139287 arg2=1 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1029): P2pEnabledState{ when=-6ms what=139287 arg2=1 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1029): DefaultState{ when=-6ms what=139287 arg2=1 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiMonitor( 1029): Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
D/WfdsMonitor( 1958): Event [CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
D/WfdsMonitor( 1958): Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
D/WfdsMonitor( 1958): Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
E/WifiMonitor( 1029): WifiMonitor:p2p0 cnt=6 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
E/WifiMonitor( 1029): handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
E/WifiMonitor( 1029): handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
D/WifiMonitor( 1029): Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
E/WifiMonitor( 1029): WifiMonitor:p2p0 cnt=7 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
E/WifiMonitor( 1029): handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
E/WifiMonitor( 1029): handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
D/WifiMonitor( 1029): Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
E/WifiMonitor( 1029): WifiMonitor:p2p0 cnt=8 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
E/WifiMonitor( 1029): handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
E/WifiMonitor( 1029): handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
D/LGWifiP2pService( 1029): InactiveState{ when=-7ms what=139285 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1029): P2pEnabledState{ when=-7ms what=139285 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1029): DefaultState{ when=-8ms what=139285 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1029): InactiveState{ when=-2ms what=139287 arg2=1 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1029): P2pEnabledState{ when=-2ms what=139287 arg2=1 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1029): DefaultState{ when=-2ms what=139287 arg2=1 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1029): InactiveState{ when=-2ms what=139283 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1029): P2pEnabledState{ when=-2ms what=139283 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1029): DefaultState{ when=-2ms what=139283 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
W/WfdsService( 1958): DefaultState - msg [9441285] is not handled
E/WifiServerServiceExt( 1029): No p2p device connected
E/BluetoothAdapterService( 6167): Fil,e transfer profiles supported!!
V/LGMDMManager( 6167): Create singleton instance
E/ActivityThread( 6237): Failed to find provider info for com.lge.lgaccount.provider
W/LG Account v2.2( 6237): No ProfileInfo entries
I/LG Account v2.2( 6237): isEnabled: false
I/Feature ( 6237): [Lifetracker]ver: 4.21.112(40211120)
I/Feature ( 6237): [Lifetracker]Country: EU
I/Feature ( 6237): [Lifetracker]Operator: OPEN
I/Feature ( 6237): [Lifetracker]Ranking support: false
I/Feature ( 6237): [Lifetracker]Comfort support: false
I/Feature ( 6237): [Lifetracker]Accessory: true
I/Feature ( 6237): [Lifetracker]Health device: true
I/Feature ( 6237): [Lifetracker]Extra Pedometer: false
I/Feature ( 6237): [Lifetracker]Blood glucose device: false
I/Feature ( 6237): [Lifetracker]Device Number: 3
,I/BluetoothAdapterState( 6167): Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
V/SIM_STK ( 1029): Menu title from STK is T-Mobile
V/SIM_STK ( 1029): Menu title from STK is T-Mobile
D/BluetoothPermissionRequest( 6193): onReceive
D/LGBluetoothFeatureConfig( 6193):  get() - isFeatureLoaded : false
,I/ActivityManager( 1029): Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=6280 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
W/FormManager( 6256): Network not available. Please check & try again.
,V/FormManager( 6256): Network unavailable.
V/FormManager( 6256): Network unavailable.
W/ActivityManager( 1029): getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
I/ActivityManager( 1029): Killing 5887:com.google.android.partnersetup/u0a8 (adj 15): empty #17
,D/LGBluetoothAvrcpQcomAdapter( 6167): [BTUI] installed app name: Music
D/LGBluetoothAvrcpQcomAdapter( 6167): [BTUI] installed app name: Google Play Music
D/LGBluetoothAvrcpQcomAdapter( 6167): [BTUI] === MediaPlayerInfo (playerId:0) ===
D/LGBluetoothAvrcpQcomAdapter( 6167): [BTUI]          displayName: Music
D/LGBluetoothAvrcpQcomAdapter( 6167): [BTUI]          packageName: com.lge.music
D/LGBluetoothAvrcpQcomAdapter( 6167): [BTUI]          playState: 2 (PAUSED)
D/LGBluetoothAvrcpQcomAdapter( 6167): [BTUI] === MediaPlayerInfo (playerId:1) ===
D/LGBluetoothAvrcpQcomAdapter( 6167): [BTUI]          displayName: Google Play Music
D/LGBluetoothAvrcpQcomAdapter( 6167): [BTUI]          packageName: com.google.android.music
D/LGBluetoothAvrcpQcomAdapter( 6167): [BTUI]          playState: 2 (PAUSED)
D/LGBluetoothAvrcpQcomAdapter( 6167): [BTUI] [-] updateMediaPlayerInfo
I/BluetoothA2dpServiceJni( 6167): classInitNative
I/BluetoothA2dpServiceJni( 6167): classInitNative: succeeds
D/A2dpStateMachine( 6167): make
I/bluedroid-qcom( 6167): get_profile_interface a2dp
I/GKI_LINUX( 6167): gki_task_entry task_id=2 [A2DP-MEDIA] starting
I/LGBluetoothA2dpServiceJni( 6167): classInitNative: succeeds
I/LGBluetoothA2dpAdapter( 6167): [BTUI] getInstance : create [LGBluetoothA2dpAdapter]
D/BluetoothAdapterService( 6167): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a0cabc
D/A2dpStateMachine( 6167): Enter Disconnected: -2
D/HeadsetStateMachine( 6167): Proxy object connected
D/LGBluetoothHfpAdapter( 6167): [BTUI] queryPhoneState
D/LGBluetoothHfpAdapter( 6167): Try to query the phonestate on bind
D/BluetoothPhoneService.BluetoothLTECall( 1861):  call mBluetoothHeadset.phoneStateChanged()
I/BluetoothHidServiceJni( 6167): classInitNative: succeeds
W/BluetoothHeadset( 1861): Proxy not attached to service
D/BluetoothHeadset( 1861): java.lang.Throwable
D/BluetoothHeadset( 1861): 	at android.bluetooth.BluetoothHeadset.phoneStateChanged(BluetoothHeadset.java:826)
D/BluetoothHeadset( 1861): 	at com.android.phone.BluetoothPhoneService$BluetoothLTECall.handleQueryPhoneState(BluetoothPhoneService.java:1527)
D/BluetoothHeadset( 1861): 	at com.android.phone.BluetoothPhoneService$BluetoothLTECall.access$700(BluetoothPhoneService.java:1360)
D/BluetoothHeadset( 1861): 	at com.android.phone.BluetoothPhoneService$1.handleMessage(BluetoothPhoneService.java:268)
D/BluetoothHeadset( 1861): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/BluetoothHeadset( 1861): 	at android.os.Looper.loop(Looper.java:135)
D/BluetoothHeadset( 1861): 	at android.app.ActivityThread.main(ActivityThread.java:5274)
D/BluetoothHeadset( 1861): 	at java.lang.reflect.Method.invoke(Native Method)
D/BluetoothHeadset( 1861): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/BluetoothHeadset( 1861): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
D/BluetoothHeadset( 1861): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
D/HidService( 6167): Received start request. Starting profile...
I/bluedroid-qcom( 6167): get_profile_interface hidhost
D/BluetoothAdapterService( 6167): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a0cabc
D/BluetoothAdapterService( 6167): Profile still not running:com.android.bluetooth.gatt.GattService
I/BluetoothHealthServiceJni( 6167): classInitNative: succeeds
D/HealthService( 6167): Received start request. Starting profile...
,D/HeadsetStateMachine( 6167): Disconnected process message: 10, size: 0
D/HeadsetPhoneState( 6167): sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
D/HeadsetStateMachine( 6167): Disconnected process message: 11, size: 0
I/bluedroid-qcom( 6167): get_profile_interface health
I/LGBluetoothHealthServiceJni( 6167): classInitNative: succeeds
D/BluetoothAdapterService( 6167): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a0cabc
I/BluetoothPanServiceJni( 6167): classInitNative(L105): succeeds
D/PanService( 6167): Received start request. Starting profile...
D/BluetoothPanServiceJni( 6167): initializeNative(L110): pan
I/bluedroid-qcom( 6167): get_profile_interface pan
E/wpa_supplicant( 6202): USIM:  scard_init function
E/WifiMonitor( 1029): WifiMonitor:wlan0 cnt=9 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
E/WifiMonitor( 1029): handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
D/WifiMonitor( 1029): Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
E/WifiMonitor( 1029): WifiMonitor:wlan0 cnt=10 dispatchEvent: WPS-AP-AVAILABLE 
I/wpa_supplicant( 6202): Trying to associate with SSID 'NG700'
W/WifiMonitor( 1029): couldn't identify event type - WPS-AP-AVAILABLE 
D/WifiMonitor( 1029): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
E/WifiMonitor( 1029): WifiMonitor:wlan0 cnt=11 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
,E/WifiStateMachine( 1029):  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=0 bcn=0
E/WifiStateMachine( 1029):  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=0 bcn=0
,E/WifiStateMachine( 1029):  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=0 bcn=0
E/WifiStateMachine( 1029):  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=0 bcn=0
I/WifiNative-HAL( 1029): startHal
E/wifi    ( 1029): getStaticLongField sWifiHalHandle 0x988c38cc
E/WifiHAL ( 1029): Could not connect handle
D/wifi    ( 1029): halHandle = 0x0, mVM = 0xb487c280, mCls = 0x1022a2
I/WifiNative-HAL( 1029): Could not start hal
D/WifiNative-wlan0( 1029): doString: [BSS RANGE=0- MASK=0x21987]
I/art     ( 1029): Explicit concurrent mark sweep GC freed 40037(2MB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 43MB/65MB, paused 2.305ms total 148.970ms
D/BluetoothManagerService( 1029): Message: 20
D/BluetoothManagerService( 1029): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@172928e0:true
,W/libprocessgroup( 1029): failed to open /acct/uid_10008/pid_5887/cgroup.procs: No such file or directory
E/WifiStateMachine( 1029):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 11 0 rt=116584  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
I/LGBluetoothPanAdapter( 6167): [BTUI] getInstance : create [LGBluetoothPanAdapter]
D/BluetoothAdapterService( 6167): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a0cabc
,I/BtGatt.JNI( 6167): classInitNative(L901): classInitNative: Success!
E/WifiStateMachine( 1029):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 11 0 rt=116599  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
D/BtGatt.DebugUtils( 6167): handleDebugAction() action=null
D/BtGatt.GattService( 6167): Received start request. Starting profile...
D/BtGatt.GattService( 6167): start()
I/bluedroid-qcom( 6167): get_profile_interface gatt
D/BtGatt.AdvertiseManager( 6167): advertise manager created
D/BluetoothAdapterService( 6167): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a0cabc
D/BluetoothAdapterService( 6167): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a0cabc
I/LGBluetoothMapAdapter( 6167): [BTUI] getInstance : create [LGBluetoothMapAdapter]
V/BluetoothMapService( 6167): BluetoothMapBinder()
D/BluetoothMapService( 6167): Received start request. Starting profile...
D/BluetoothMapService( 6167): start()
,D/LGBluetoothResetSettingReceiver( 6193): return without doing reset settings.
,D/BluetoothMapEmailSettingsLoader( 6167): Found 0 applications
D/BluetoothMapEmailAppObserver( 6167): createReceiver()
I/ActivityManager( 1029): Killing 5542:com.lge.appbox.client/u0a11 (adj 15): empty #17
D/PCSuite ( 6280): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,I/StatusBar.NetworkController( 1464): networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1464): mWifiConnected = false, mWifiLevel = 0
,D/StatusBar.NetworkController( 1464): refreshViews: Data not connected!! Set no data type icon / Roaming
W/Settings( 1029): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1029): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1029): NETWORK_STATE_CHANGED_ACTION [SCANNING]
I/StatusBar.NetworkController( 1464): networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1464): mWifiConnected = false, mWifiLevel = 0
,D/StatusBar.NetworkController( 1464): refreshViews: Data not connected!! Set no data type icon / Roaming
W/Settings( 1029): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/BluetoothMapEmailAppObserver( 6167): initObservers()
D/BluetoothMapEmailAppObserver( 6167): getEnabledAccountItems()
W/Settings( 1029): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1029): NETWORK_STATE_CHANGED_ACTION [CONNECTING]
D/WifiServerServiceExt( 1029): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1029): setSupplicantStateASSOCIATING
W/libprocessgroup( 1029): failed to open /acct/uid_10011/pid_5542/cgroup.procs: No such file or directory
,D/BluetoothAdapterService( 6167): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a0cabc
D/BluetoothAdapterService( 6167): Profile still not running:com.android.bluetooth.gatt.GattService
,D/BluetoothAdapterService( 6167): Profile still not running:com.android.bluetooth.gatt.GattService
D/BluetoothAdapterService( 6167): Profile still not running:com.android.bluetooth.gatt.GattService
V/WiFiOffLoadBroadcast( 6193): WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
D/BluetoothAdapterService( 6167): Profile still not running:com.android.bluetooth.gatt.GattService
D/BluetoothAdapterService( 6167): Profile still not running:com.android.bluetooth.map.BluetoothMapService
D/LGBluetoothOppAdapter( 6167): [BTUI] getInstance : create [LGBluetoothOppAdapter]
V/PanService( 6167): [BTUI] SIM Extra State :ABSENT
V/BluetoothMapService( 6167): Handler(): got msg=1
,D/BluetoothAdapterState( 6167): CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
I/bluedroid-qcom( 6167): enable
I/GKI_LINUX( 6167): gki_task_entry task_id=0 [BTU] starting
I/bt-btu  ( 6167): btu_task pending for preload complete event
I/bt_hci_bdroid( 6167): init
D/WifiService( 1029): New client listening to asynchronous messages
V/BluetoothFtpReceiver( 6167): BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothSapReceiver( 6167): [BTUI] checkServiceStart
V/BluetoothSapReceiver( 6167): [BTUI] region:EU country:EU
V/BluetoothSapReceiver( 6167): SapReceiver onReceive 
V/BluetoothSapReceiver( 6167): action = android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothSapReceiver( 6167):  Bluetooth Adapter state = 11
I/bt_vendor( 6167): bt-vendor : init
I/bt_vendor( 6167): bt-vendor : get_bt_soc_type
E/bt_vendor( 6167): get_bt_soc_type: Failed to get soc type
I/bt_vendor( 6167): init: Local BD Address : c0:64:73:54:3f:58
D/bt_userial_mct( 6167): userial_init
D/bt_hci_bdroid( 6167): set_power 1
I/bt_vendor( 6167): bt-vendor : BT_VND_OP_POWER_CTRL: On
I/bt_vendor( 6167): Starting hciattach daemon
I/bt_vendor( 6167): try to set true
,W/sh      ( 6314): type=1400 audit(0.0:157): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
W/sh      ( 6314): type=1400 audit(0.0:158): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,D/LgDataFeature( 6193): LgDataFeature() Constructor: none
D/LgDataFeature( 6193): LgDataFeature() Constructor Done, null
D/WiFiOffLoadUpdatePriority( 6193): remove : truetruetrue
E/WifiStateMachine( 1029):  DisconnectedState CMD_GET_CONFIGURED_NETWORKS uid=1000 1000 0 num=1
E/WifiStateMachine( 1029):  ConnectModeState CMD_GET_CONFIGURED_NETWORKS uid=1000 1000 0 num=1
I/qcom-bluetooth( 6316): /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  
E/WifiStateMachine( 1029):  DisconnectedState CMD_SAVE_CONFIG uid=1000 0 0
E/WifiStateMachine( 1029):  ConnectModeState CMD_SAVE_CONFIG uid=1000 0 0
D/WifiNative-wlan0( 1029): doBoolean: SAVE_CONFIG
D/WifiNative-wlan0( 1029): SAVE_CONFIG: returned true
D/WiFiOffLoadUpdatePriority( 6193): remove1
V/WiFiOffLoadSharedPrefsUtils( 6193): save remove
I/ActivityManager( 1029): Start proc com.lge.settings.easy for broadcast com.lge.settings.easy/com.lge.settings.bluetooth.LGBluetoothProfileConnectionReceiver: pid=6319 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,D/WiFiOffLoadBroadcast( 6193): mLastConnectedNetwork from SharedPrefsUtils for wifioffloading : null
D/WiFiOffLoadBroadcast( 6193): S: false, R: false
,E/WifiStateMachine( 1029):  DisconnectedState CMD_GET_CONFIGURED_NETWORKS uid=1000 1000 0 num=1
E/WifiStateMachine( 1029):  ConnectModeState CMD_GET_CONFIGURED_NETWORKS uid=1000 1000 0 num=1
D/WiFiOffLoadUpdatePriority( 6193): saved SSID: "NG700"
D/WiFiOffLoadUpdatePriority( 6193): connected SSID: null
D/WiFiOffLoadUpdatePriority( 6193): private wpa: "NG700" 300
D/WifiServiceImplEx( 1029): addOrUpdateNetwork pid=6193, uid=1000, packageName=android.uid.system:1000
E/addOrUpdateNetwork( 1029):  uid = 1000 SSID "NG700" nid=0
E/WifiStateMachine( 1029):  DisconnectedState CMD_ADD_OR_UPDATE_NETWORK uid=1000 0 0 "NG700"WPA_PSK prio=300 status=2
E/WifiStateMachine( 1029):  ConnectModeState CMD_ADD_OR_UPDATE_NETWORK uid=1000 0 0 "NG700"WPA_PSK prio=300 status=2
E/WifiConfigStore( 1029):  key="NG700"WPA_PSK netId=0 uid=0/1000
D/WifiServerServiceExt( 1029): addOrUpdateNetwork: mThisIsFirstEnableing = false
D/WifiNative-wlan0( 1029): doBoolean: SET_NETWORK 0 ssid 4e47373030
I/qcom-bluetooth( 6340): /system/etc/init.qcom.bt.sh: Transport : smd 
,I/qcom-bluetooth( 6341): /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
W/ResourcesManager( 6319): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,D/WifiNative-wlan0( 1029): SET_NETWORK 0 ssid 4e47373030: returned true
,D/WifiNative-wlan0( 1029): doBoolean: SET_NETWORK 0 key_mgmt WPA-PSK
D/WifiNative-wlan0( 1029): SET_NETWORK 0 key_mgmt WPA-PSK: returned true
D/WifiNative-wlan0( 1029): doBoolean: SET_NETWORK 0 proto WPA RSN
D/WifiNative-wlan0( 1029): SET_NETWORK 0 proto WPA RSN: returned true
D/WifiNative-wlan0( 1029): doBoolean: SET_NETWORK 0 pairwise TKIP CCMP
D/WifiNative-wlan0( 1029): SET_NETWORK 0 pairwise TKIP CCMP: returned true
D/WifiNative-wlan0( 1029): doBoolean: SET_NETWORK 0 group WEP40 WEP104 TKIP CCMP
D/WifiNative-wlan0( 1029): SET_NETWORK 0 group WEP40 WEP104 TKIP CCMP: returned true
D/WifiNative-wlan0( 1029): doBoolean: SET_NETWORK 0 priority 300
I/qcom-bluetooth( 6343): /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
D/WifiNative-wlan0( 1029): SET_NETWORK 0 priority 300: returned true
E/WifiConfigStore( 1029): will read network variables netId=0
E/WifiConfigStore( 1029): writeIpAndProxyConfigurationsOnChange: "NG700" -> "NG700" path: /data/misc/wifi/ipconfig.txt
E/WifiConfigStore( 1029):  writeKnownNetworkHistory() num networks:1 needWrite=false
I/ActivityManager( 1029): Killing 5569:com.android.contacts/u0a19 (adj 15): empty #17
,I/qcom-bluetooth( 6344): /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> 
I/qcom-bluetooth( 6345): /system/etc/init.qcom.bt.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
I/qcom-bluetooth( 6346): /system/etc/init.qcom.bt.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> 
,I/libmdmdetect( 6348): ESOC framework not supported
E/Diag_Lib( 6348):  Diag_LSM_Init: Failed to open handle to diag driver, error = 13
,D/bthci_qcomm_linux( 6348): [BTUI] bt_hci_qcomm_pfal_get_bdaddress: Get BDADDR from bluedroid prop (58:3F:54:73:64:C0)
D/bthci_qcomm_common( 6348): [BTUI] bt_hci_qcomm_init:
D/bthci_qcomm_common( 6348): [BTUI]     BDADDR: 58:3F:54:73:64:C0
D/bthci_qcomm_common( 6348): [BTUI]     BR/EDR: Class 1
D/bthci_qcomm_common( 6348): [BTUI]     LE: Class 2
D/bthci_qcomm_common( 6348): [BTUI]     Ref Clock: 32M
D/btqsocnvmtags( 6348): [BTUI] init_riva_entries: set NORMAL power settings
D/AuthorizationBluetoothService( 2157): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
W/libprocessgroup( 1029): failed to open /acct/uid_10019/pid_5569/cgroup.procs: No such file or directory
,D/WiFiOffLoadUpdatePriority( 6193):  ssid "NG700" prio 300
,D/WiFiOffLoadUpdatePriority( 6193): configuration updated: 0
E/WifiStateMachine( 1029):  DisconnectedState CMD_SAVE_CONFIG uid=1000 0 0
E/WifiStateMachine( 1029):  ConnectModeState CMD_SAVE_CONFIG uid=1000 0 0
D/WifiNative-wlan0( 1029): doBoolean: SAVE_CONFIG
D/WifiNative-wlan0( 1029): SAVE_CONFIG: returned true
D/WiFiOffLoadUpdatePriority( 6193): configuration saved: true
,I/ActivityManager( 1029): Killing 5908:com.lge.email/u0a23 (adj 15): empty #17
I/rmt_storage(  313): rmt_storage_connect_cb: clnt_h=0x5 conn_h=0xb6403090
I/rmt_storage(  313): rmt_storage_rw_iovec_cb: /boot/modem_fs1: clnt_h=0x1: req_h=0x9 msg_id=3: R/W request received
I/rmt_storage(  313): wakelock acquired: 1, error no: 42
I/rmt_storage(  313): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 Unblock worker thread (th_id: -1236807552)
,W/libprocessgroup( 1029): failed to open /acct/uid_10023/pid_5908/cgroup.procs: No such file or directory
,D/PCSuite ( 6280): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 6193): WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,D/WiFiOffLoadBroadcast( 6193): MCCMNC not supported: null
W/FormManager( 6256): Network not available. Please check & try again.
,V/FormManager( 6256): Network unavailable.
D/LGDMClient( 4005): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
D/LGDMClient( 4005): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
I/rmt_storage(  313): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0x9 msg_id=3: Bytes written = 1572864
I/rmt_storage(  313): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0x9 msg_id=3: Send response: res=0 err=0
I/rmt_storage(  313): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 About to block rmt_storage client thread (th_id: -1236807552) wakelock released: 1, error no: 22
I/rmt_storage(  313): 
V/FormManager( 6256): Network unavailable.
W/ContextImpl( 4005): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
I/rmt_storage(  313): rmt_storage_disconnect_cb: clnt_h=0x0x5 conn_h=0x0xb6403090
E/Diag_Lib(  896): [IMS_FATAL]| 3347 | 912 |ims-rtp-daemon ims_rtp_qmi_handler_thread_func waiting on select thread>
W/ContextImpl( 4005): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
D/PostponalbeReceiver( 5221): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,D/LGDMClient( 4005): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=3, isUserType=1
I/PCSuite ( 6280): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 6280): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 6280): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 6193): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/LGDMClient( 4005): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
D/LGDMClient( 4005): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
D/WiFiOffLoadBroadcast( 6193): MCCMNC not supported: null
I/ActivityManager( 1029): Start proc com.lge.qremote for broadcast com.lge.qremote/.settings.WiFiStateReceiver: pid=6359 uid=10112 gids={50112, 9997, 1028, 1015, 3003, 3002} abi=armeabi
,W/ResourcesManager( 6359): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,D/QRemote ( 6359): [QRemoteApplication.java:230:onCreate()] oooooo QRemoteApp onCreate....
,D/QRemote ( 6359): [CarrierUtils.java:858:getHardwareSettings()] oooooo qremote android.os.Build.MODEL = LG-D855
I/QRemote ( 6359): [CarrierUtils.java:859:getHardwareSettings()] oooooo getCountry :: EU
I/QRemote ( 6359): [CarrierUtils.java:860:getHardwareSettings()] oooooo getCarrier :: OPEN
I/QRemote ( 6359): [CarrierUtils.java:861:getHardwareSettings()] oooooo getArea :: COM
,D/QRemote ( 6359): [CarrierUtils.java:862:getHardwareSettings()] oooooo Loading Config...
D/QRemote ( 6359): [CarrierUtils.java:876:getHardwareSettings()] oooooo qremote configuration file = R.xml.qremote_conf
D/QRemote ( 6359): [QRemoteApplication.java:701:updateWidget()] oooooo Widget count is [1]. send broadcast
D/QRemote ( 6359): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6359): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 6359): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,D/QRemote ( 6359): [QRemoteService.java:196:onCreate()] oooooo 140526:onCreate
V/[BNRBootReceiver]( 6011): boot receiver action = android.net.wifi.p2p.CONNECTION_STATE_CHANGE
D/BNRAndroBeam( 6011): [BnR DirectBeam] Android Direct Beam(NFC) Connection changed
D/QRemote ( 6359): [QRemoteService.java:217:onStartCommand()] oooooo 140526:onStartCommand:action:action.application.oncreate. startId:1, flags:0
V/[BNRBootReceiver]( 6011): Boot Receiver Return
,D/PostponalbeReceiver( 5221): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
V/WiFiOffLoadBroadcast( 6193): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6193): MCCMNC not supported: null
D/QRemote ( 6359): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6359): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 6359): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
V/WiFiOffLoadBroadcast( 6193): WiFiOffLoadBroadcast: android.net.wifi.SCAN_RESULTS
,D/WiFiOffLoadBroadcast( 6193): Not supported operator for automatic switch
D/PostponalbeReceiver( 5221): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
V/WiFiOffLoadBroadcast( 6193): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6193): MCCMNC not supported: null
D/QRemote ( 6359): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6359): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 6359): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
D/PostponalbeReceiver( 5221): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
V/WiFiOffLoadBroadcast( 6193): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6193): MCCMNC not supported: null
D/QRemote ( 6359): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6359): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 6359): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
V/QRemote ( 6359): [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
,D/QRemote ( 6359): [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
D/QRemote ( 6359): [QRemoteApplication.java:86:getControlManager()] oooooo mControlManager is null. make new RemoteControlManager
D/sensors_hal_Time( 1029): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1029): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1029): tsOffsetIs: Apps: 117433773343; DSPS: 3988882; Offset : -4312458158
D/LgDataFeature( 6359): LgDataFeature() Constructor: none
D/LgDataFeature( 6359): LgDataFeature() Constructor Done, null
,V/SoundPool( 6359): SoundPool constructor: maxChannels=2, attr.usage=13, attr.flags=0x0, attr.tags=
V/SoundPool( 6359): load: fd=30, offset=10857164, length=17813, priority=1
V/SoundPool( 6359): create sampleID=1, fd=31, offset=17813 length=10857164
V/SoundPool( 6359): doLoad: loading sample sampleID=1
I/QRemote ( 6359): [RemoteControlManager.java:157:onBindIRService()] oooooo bind
D/QRemote ( 6359): [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
D/UEI.SmartControl( 5934): QS Service created
E/QRemote ( 6359): [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
D/QRemote ( 6359): [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
V/SoundPool( 6359): Start decode
V/MediaPlayer[Native]( 6359): decode(31, 10857164, 17813)
V/MediaPlayerService(  325): decode(24, 10857164, 17813)
W/BrunchPlayerTypeImpl(  325): [SelectPlayer] LocalType
W/BrunchPlayerTypeImpl(  325): [getMediaType] EXTEND_MEDIA_MIMETYPE = application/ogg
W/BrunchPlayerTypeImpl(  325): [FindUsePlayer] type = [application/ogg]
W/BrunchPlayerTypeImpl(  325): [FindUsePlayer] componentName = [9101]
W/MediaPlayerFactory(  325): [getPlayerType:fd] nType = 3
V/MediaPlayerService(  325): player type = 3
V/AwesomePlayer(  325): AwesomePlayer create()
V/AwesomePlayer(  325): reset_l() 
V/AwesomePlayer(  325): cancelPlayerEvents
V/AwesomePlayer(  325): setAudioSink() 
V/AwesomePlayer(  325): reset_l() 
V/AudioCache(  325): notify(0xb54745c0, 8, 0, 0)
V/AudioCache(  325): ignored
V/AwesomePlayer(  325): cancelPlayerEvents
D/Utils   (  325): printFileName fd(25) -> /data/preload/LGQRemote/LGQRemote.apk
V/AwesomePlayer(  325): setDataSource_l dataSource
V/LGParserOSAL(  325): SniffLGParser start
V/LGParserOSAL(  325): MainType:5, SubType=0
V/LGParserOSAL(  325): #### check Mime : application/ogg
V/LGParserOSAL(  325): Detector mimeType:application/ogg, Confidence=1.000000
E/MediaExtractor(  325): Use LGExtractor :application/ogg 
,V/LGMDMManager( 6359): Create singleton instance
I/UEI.SmartControl( 5934): Service initServices...
D/UEI.SmartControl( 5934): QS start get config
,D/QRemote ( 6359): [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
D/QRemote ( 6359): [RemoteAppWidgetProvider.java:486:onUpdate()] oooooo 140510:RetrieveDevices is not complete. Just waiting
,D/QRemote ( 6359): [RemoteAppWidgetProvider.java:499:onUpdate()] oooooo 140514:alarm set after 5000ms:7812
V/LGParserOSAL(  325): supported mime: application/ogg
V/AwesomePlayer(  325): setDataSource_l() extractor countTracks=1
V/AwesomePlayer(  325): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer(  325): mBitrate = -1 bits/sec
V/AwesomePlayer(  325): AudioTrack Setting
V/AwesomePlayer(  325): AudioTrack Setting channelCount = 2
V/AwesomePlayer(  325): setAudioSource() 
V/MediaPlayerService(  325): prepare
V/AwesomePlayer(  325): prepareAsync_l() 
V/MediaPlayerService(  325): wait for prepare
V/AwesomePlayer(  325): onPrepareAsyncEvent() 
V/AwesomePlayer(  325): initAudioDecoder() 
W/Utils   (  325): bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
V/AudioSystem(  325): isOffloadSupported()
V/AudioPolicyManager(  325): isOffloadSupported: SR=48000, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
D/AudioPolicyManager(  325): isOffloadSupported: stream_type != MUSIC, returning false
I/AudioFlinger(  325): isAudioPlaybackHookOn() false
V/AwesomePlayer(  325): getUseOffload() = 0 
V/OMXCodec(  325): OMXCodec::Create
V/OMXCodec(  325): findMatchingCodecs()
V/OMXCodec(  325): matching 'OMX.google.vorbis.decoder' quirks 0x00000000
V/OMXCodec(  325): matchingCodecs.size()=1
V/OMXCodec(  325): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
D/OMXCodec(  325): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
V/LGCodecAdapter(  325): LG Codec Adapter start
V/OMXCodec(  325): OMXCodec Createtor
V/OMXCodec(  325): setComponentRole
V/OMXCodec(  325): configureCodec protected=0
V/LGCodecAdapter(  325): called getLGCodecSpecificData
V/LGCodecOSAL(  325): Called LGgetCodecSpecificDataMETA
V/LGCodecOSAL(  325): Called LGconfigureCodecMETA
V/LGCodecOSAL(  325): Called LGconfigureCodecMSG
V/LGCodecOSAL(  325): Not support LGCodec
V/OMXCodec(  325): [OMX.google.vorbis.decoder] initOutputFormat()
V/OMXCodec(  325): Codec outputs a different number of channels than the input stream contains (contains 2 channels, codec outputs 1 channels).
V/OMXCodec(  325): Codec outputs at different sampling rate than what the input stream contains (contains data at 48000 Hz, codec outputs 44100 Hz)
I/AwesomePlayer(  325): Could not offload audio decode, try pcm offload
W/Utils   (  325): bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
V/AudioSystem(  325): isOffloadSupported()
V/AudioPolicyManager(  325): isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
D/AudioPolicyManager(  325): isOffloadSupported: stream_type != MUSIC, returning false
V/OMXCodec(  325): [OMX.google.vorbis.decoder] start mState=1
V/OMXCodec(  325): init()
V/OMXCodec(  325): [OMX.google.vorbis.decoder] setState mState=1 , newState=2
V/OMXCodec(  325): allocateBuffers
V/OMXCodec(  325): allocateBuffersOnPort portIndex=0
V/OMXCodec(  325): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
V/OMXCodec(  325): [OMX.google.vorbis.decoder] allocated buffer 0xb54f7e70 on input port
V/OMXCodec(  325): [OMX.google.vorbis.decoder] allocated buffer 0xb54f7ec0 on input port
V/OMXCodec(  325): [OMX.google.vorbis.decoder] allocated buffer 0xb54f7f10 on input port
V/OMXCodec(  325): [OMX.google.vorbis.decoder] allocated buffer 0xb54f7f60 on input port
V/OMXCodec(  325): allocateBuffersOnPort portIndex=1
,V/OMXCodec(  325): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
V/OMXCodec(  325): [OMX.google.vorbis.decoder] allocated buffer 0xb57bf100 on output port
V/OMXCodec(  325): [OMX.google.vorbis.decoder] allocated buffer 0xb57bf2e0 on output port
V/OMXCodec(  325): [OMX.google.vorbis.decoder] allocated buffer 0xb57bf4c0 on output port
V/OMXCodec(  325): [OMX.google.vorbis.decoder] allocated buffer 0xb57bf510 on output port
V/OMXCodec(  325): init() mAsyncCompletion wait!!! 
V/OMXCodec(  325): [OMX.google.vorbis.decoder] onStateChange 2
V/OMXCodec(  325): [OMX.google.vorbis.decoder] Now Idle.
V/OMXCodec(  325): [OMX.google.vorbis.decoder] setState mState=2 , newState=3
V/OMXCodec(  325): [OMX.google.vorbis.decoder] onStateChange 3
V/OMXCodec(  325): [OMX.google.vorbis.decoder] Now Executing.
V/OMXCodec(  325): [OMX.google.vorbis.decoder] setState mState=3 , newState=4
V/OMXCodec(  325): init() mAsyncCompletion wait free! 
V/AwesomePlayer(  325): finishAsyncPrepare_l() 
V/AudioCache(  325): notify(0xb54745c0, 5, 0, 0)
V/AudioCache(  325): ignored
V/AudioCache(  325): notify(0xb54745c0, 1, 0, 0)
V/AudioCache(  325): prepared
V/AudioCache(  325): wait - success
V/MediaPlayerService(  325): start
V/AwesomePlayer(  325): play_l() 
V/AwesomePlayer(  325): play_l m_isDivXDRM=0, bpurchasefile:0
V/AwesomePlayer(  325): createAudioPlayer_l
V/AwesomePlayer(  325): seekAudioIfNecessary_l() 
V/AwesomePlayer(  325): startAudioPlayer_l() 
D/AudioPlayer(  325): start of Playback, useOffload 0
V/OMXCodec(  325): [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
V/OMXCodec(  325): [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
V/OMXCodec(  325): [OMX.google.vorbis.decoder] OMX_EventPortSettingsChanged(port=1, data2=0x00000000)
V/OMXCodec(  325): [OMX.google.vorbis.decoder] PORT_SETTINGS_CHANGED(1)
V/OMXCodec(  325): [OMX.google.vorbis.decoder] setState mState=4 , newState=7
V/OMXCodec(  325): [OMX.google.vorbis.decoder] disablePortAsync portIndex=1
V/OMXCodec(  325): [OMX.google.vorbis.decoder] sending OMX_CommandPortDisable(1)
V/OMXCodec(  325): [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
V/OMXCodec(  325): [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3044798720
V/OMXCodec(  325): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
V/OMXCodec(  325): [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3044799200
V/OMXCodec(  325): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
V/OMXCodec(  325): [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3044799680
V/OMXCodec(  325): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
V/OMXCodec(  325): [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3044799760
V/OMXCodec(  325): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
V/OMXCodec(  325): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
V/OMXCodec(  325): [OMX.google.vorbis.decoder] initOutputFormat()
V/OMXCodec(  325): [OMX.google.vorbis.decoder] reconfig handling, formatHasNotablyChanged
V/OMXCodec(  325): [OMX.google.vorbis.decoder] enablePortAsync portIndex=1
V/OMXCodec(  325): [OMX.google.vorbis.decoder] sending OMX_CommandPortEnable(1)
V/OMXCodec(  325): allocateBuffersOnPort portIndex=1
V/OMXCodec(  325): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
V/OMXCodec(  325): [OMX.google.vorbis.decoder] allocated buffer 0xb57bf4c0 on output port
V/OMXCodec(  325): [OMX.google.vorbis.decoder] allocated buffer 0xb57bf2e0 on output port
V/OMXCodec(  325): [OMX.google.vorbis.decoder] allocated buffer 0xb57bf100 on output port
V/OMXCodec(  325): [OMX.google.vorbis.decoder] allocated buffer 0xb14fc0b0 on output port
V/OMXCodec(  325): [OMX.google.vorbis.decoder] PORT_ENABLED(1)
V/OMXCodec(  325): [OMX.google.vorbis.decoder] setState mState=7 , newState=4
V/AudioCache(  325): open(48000, 2, 0x0, 1, 4)
V/AudioCache(  325): notify(0xb54745c0, 6, 0, 0)
V/AudioCache(  325): ignored,
V/MediaPlayerService(  325): wait for playback complete
V/AudioCache(  325): write(0xb1742000, 4096)
V/AudioCache(  325): memcpy(0xab602000, 0xb1742000, 4096)
V/AudioCache(  325): write(0xb1742000, 4096)
V/AudioCache(  325): memcpy(0xab603000, 0xb1742000, 4096)
V/AudioCache(  325): write(0xb1742000, 4096)
V/AudioCache(  325): memcpy(0xab604000, 0xb1742000, 4096)
V/AudioCache(  325): write(0xb1742000, 4096)
V/AudioCache(  325): memcpy(0xab605000, 0xb1742000, 4096)
V/AudioCache(  325): write(0xb1742000, 4096)
V/AudioCache(  325): memcpy(0xab606000, 0xb1742000, 4096)
V/AudioCache(  325): write(0xb1742000, 4096)
V/AudioCache(  325): memcpy(0xab607000, 0xb1742000, 4096)
V/AudioCache(  325): write(0xb1742000, 4096)
V/AudioCache(  325): memcpy(0xab608000, 0xb1742000, 4096)
V/AudioCache(  325): write(0xb1742000, 4096)
V/AudioCache(  325): memcpy(0xab609000, 0xb1742000, 4096)
V/AudioCache(  325): write(0xb1742000, 4096)
V/AudioCache(  325): memcpy(0xab60a000, 0xb1742000, 4096)
V/AudioCache(  325): write(0xb1742000, 4096)
V/AudioCache(  325): memcpy(0xab60b000, 0xb1742000, 4096)
V/AudioCache(  325): write(0xb1742000, 4096)
V/AudioCache(  325): memcpy(0xab60c000, 0xb1742000, 4096)
V/AudioCache(  325): write(0xb1742000, 4096)
V/AudioCache(  325): memcpy(0xab60d000, 0xb1742000, 4096)
V/AudioCache(  325): write(0xb1742000, 4096)
V/AudioCache(  325): memcpy(0xab60e000, 0xb1742000, 4096)
V/AudioCache(  325): write(0xb1742000, 4096)
V/AudioCache(  325): memcpy(0xab60f000, 0xb1742000, 4096)
V/AudioCache(  325): write(0xb1742000, 4096)
V/AudioCache(  325): memcpy(0xab610000, 0xb1742000, 4096)
V/AudioCache(  325): write(0xb1742000, 4096)
V/AudioCache(  325): memcpy(0xab611000, 0xb1742000, 4096)
V/AudioCache(  325): write(0xb1742000, 4096)
V/AudioCache(  325): memcpy(0xab612000, 0xb1742000, 4096)
V/AudioCache(  325): write(0xb1742000, 4096)
V/AudioCache(  325): memcpy(0xab613000, 0xb1742000, 4096)
V/AudioCache(  325): write(0xb1742000, 4096)
V/AudioCache(  325): memcpy(0xab614000, 0xb1742000, 4096)
V/AudioCache(  325): write(0xb1742000, 4096)
V/AudioCache(  325): memcpy(0xab615000, 0xb1742000, 4096)
V/AudioCache(  325): write(0xb1742000, 4096)
V/AudioCache(  325): memcpy(0xab616000, 0xb1742000, 4096)
V/AudioCache(  325): write(0xb1742000, 4096)
V/AudioCache(  325): memcpy(0xab617000, 0xb1742000, 4096)
V/AudioCache(  325): write(0xb1742000, 4096)
V/AudioCache(  325): memcpy(0xab618000, 0xb1742000, 4096)
V/AudioCache(  325): write(0xb1742000, 4096)
V/AudioCache(  325): memcpy(0xab619000, 0xb1742000, 4096)
V/AudioCache(  325): write(0xb1742000, 4096)
V/AudioCache(  325): memcpy(0xab61a000, 0xb1742000, 4096)
V/AudioCache(  325): write(0xb1742000, 4096)
V/AudioCache(  325): memcpy(0xab61b000, 0xb1742000, 4096)
V/AudioCache(  325): write(0xb1742000, 4096)
V/AudioCache(  325): memcpy(0xab61c000, 0xb1742000, 4096)
V/AudioCache(  325): write(0xb1742000, 4096)
V/AudioCache(  325): memcpy(0xab61d000, 0xb1742000, 4096)
V/AudioCache(  325): write(0xb1742000, 4096)
V/AudioCache(  325): memcpy(0xab61e000, 0xb1742000, 4096)
V/AudioCache(  325): write(0xb1742000, 4096)
V/AudioCache(  325): memcpy(0xab61f000, 0xb1742000, 4096)
V/AudioCache(  325): write(0xb1742000, 4096)
V/AudioCache(  325): memcpy(0xab620000, 0xb1742000, 4096)
,V/AudioCache(  325): write(0xb1742000, 4096)
V/AudioCache(  325): memcpy(0xab621000, 0xb1742000, 4096)
V/AudioCache(  325): write(0xb1742000, 4096)
V/AudioCache(  325): memcpy(0xab622000, 0xb1742000, 4096)
V/AudioCache(  325): write(0xb1742000, 4096)
V/AudioCache(  325): memcpy(0xab623000, 0xb1742000, 4096)
V/AudioCache(  325): write(0xb1742000, 4096)
V/AudioCache(  325): memcpy(0xab624000, 0xb1742000, 4096)
,V/AudioCache(  325): write(0xb1742000, 4096)
V/AudioCache(  325): memcpy(0xab625000, 0xb1742000, 4096)
V/AudioCache(  325): write(0xb1742000, 4096)
V/AudioCache(  325): memcpy(0xab626000, 0xb1742000, 4096)
V/AudioCache(  325): write(0xb1742000, 4096)
V/AudioCache(  325): memcpy(0xab627000, 0xb1742000, 4096)
V/AudioCache(  325): write(0xb1742000, 4096)
V/AudioCache(  325): memcpy(0xab628000, 0xb1742000, 4096)
V/AudioCache(  325): write(0xb1742000, 4096)
V/AudioCache(  325): memcpy(0xab629000, 0xb1742000, 4096)
V/AudioCache(  325): write(0xb1742000, 4096)
V/AudioCache(  325): memcpy(0xab62a000, 0xb1742000, 4096)
V/AudioCache(  325): write(0xb1742000, 4096)
V/AudioCache(  325): memcpy(0xab62b000, 0xb1742000, 4096)
V/AudioCache(  325): write(0xb1742000, 4096)
V/AudioCache(  325): memcpy(0xab62c000, 0xb1742000, 4096)
V/AudioCache(  325): write(0xb1742000, 4096)
V/AudioCache(  325): memcpy(0xab62d000, 0xb1742000, 4096)
V/AudioCache(  325): write(0xb1742000, 4096)
V/AudioCache(  325): memcpy(0xab62e000, 0xb1742000, 4096)
V/AudioCache(  325): write(0xb1742000, 4096)
V/AudioCache(  325): memcpy(0xab62f000, 0xb1742000, 4096)
V/AudioCache(  325): write(0xb1742000, 4096)
V/AudioCache(  325): memcpy(0xab630000, 0xb1742000, 4096)
V/AudioCache(  325): write(0xb1742000, 4096)
V/AudioCache(  325): memcpy(0xab631000, 0xb1742000, 4096)
V/AudioCache(  325): write(0xb1742000, 4096)
V/AudioCache(  325): memcpy(0xab632000, 0xb1742000, 4096)
V/AudioCache(  325): write(0xb1742000, 4096)
V/AudioCache(  325): memcpy(0xab633000, 0xb1742000, 4096)
V/OMXCodec(  325): [OMX.google.vorbis.decoder] No more output data.
V/OMXCodec(  325): [OMX.google.vorbis.decoder] There is no more output data available, not calling fillOutputBuffer
V/AwesomePlayer(  325): postAudioEOS() 
V/AudioCache(  325): write(0xb1742000, 280)
V/AudioCache(  325): memcpy(0xab634000, 0xb1742000, 280)
V/AwesomePlayer(  325): postStreamDoneEvent_l() -> status:-1011 
V/AwesomePlayer(  325): onStreamDone
V/AwesomePlayer(  325): MEDIA_PLAYBACK_COMPLETE
V/AudioCache(  325): notify(0xb54745c0, 2, 0, 0)
V/AudioCache(  325): playback complete
V/AwesomePlayer(  325): pause_l() 
V/AudioCache(  325): notify(0xb54745c0, 7, 0, 0)
V/AudioCache(  325): ignored
V/AwesomePlayer(  325): cancelPlayerEvents
D/AudioPlayer(  325): Pause Playback at 1068125
V/AudioCache(  325): wait - success
V/MediaPlayerService(  325): return size 205080, sampleRate=48000, channelCount = 2, format = 1
V/AwesomePlayer(  325): reset_l() 
V/AudioCache(  325): notify(0xb54745c0, 8, 0, 0)
V/AudioCache(  325): ignored
V/AwesomePlayer(  325): cancelPlayerEvents
D/AudioPlayer(  325): reset: mPlaying=0 mReachedEOS=1 useOffload=0
V/OMXCodec(  325): [OMX.google.vorbis.decoder] stop mState=4
V/OMXCodec(  325): [OMX.google.vorbis.decoder] stopOmxComponent_l mState=4
V/OMXCodec(  325): [OMX.google.vorbis.decoder] setState mState=4 , newState=5
V/OMXCodec(  325): [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
V/OMXCodec(  325): [OMX.google.vorbis.decoder] onStateChange 2
V/OMXCodec(  325): [OMX.google.vorbis.decoder] Now Idle.
V/OMXCodec(  325): [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=0
V/OMXCodec(  325): [OMX.google.vorbis.decoder] freeing buffer 0xb54f7f60 on port 0
V/OMXCodec(  325): [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=3
V/OMXCodec(  325): [OMX.google.vorbis.decoder] freeing buffer 0xb54f7f10 on port 0
V/OMXCodec(  325): [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=2
V/OMXCodec(  325): [OMX.google.vorbis.decoder] freeing buffer 0xb54f7ec0 on port 0
V/OMXCodec(  325): [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=1
V/OMXCodec(  325): [OMX.google.vorbis.decoder] freeing buffer 0xb54f7e70 on port 0
V/OMXCodec(  325): [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=0
V/OMXCodec(  325): [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
V/OMXCodec(  325): [OMX.google.vorbis.decoder] freeing buffer 0xb14fc0b0 on port 1
V/OMXCodec(  325): [OMX.google.vorbis.decoder] freeBuffer, portIndex=1,bufIndex=3
V/OMXCodec(  325): [OMX.google.vorbis.decoder] freeing buffer 0xb57bf100 on port 1
V/OMXCodec(  325): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=2
V/OMXCodec(  325): [OMX.google.vorbis.decoder] freeing buffer 0xb57bf2e0 on port 1
V/OMXCodec(  325): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=1
V/OMXCodec(  325): [OMX.google.vorbis.decoder] freeing buffer 0xb57bf4c0 on port 1
V/OMXCodec(  325): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
V/OMXCodec(  325): [OMX.google.vorbis.decoder] setState mState=5 , newState=6
V/OMXCodec(  325): [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
V/OMXCodec(  325): [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
V/OMXCodec(  325): [OMX.google.vorbis.decoder] onStateChange 1
V/OMXCodec(  325): [OMX.google.vorbis.decoder] Now Loaded.
V/OMXCodec(  325): [OMX.google.vorbis.decoder] setState mState=6 , newState=1
V/OMXCodec(  325): [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
V/OMXCodec(  325): [OMX.google.vorbis.decoder] stopped in state 1
V/OMXCodec(  325): [OMX.google.vorbis.decoder] ~OMXCodec mstate =1
V/OMXCodec(  325): [OMX.google.vorbis.decoder] setState mState=1 , newState=0
D/AudioPlayer(  325): AudioPlayer releasing audio source
D/AudioPlayer(  325): AudioPlayer done releasing audio source
V/AwesomePlayer(  325): reset_l() 
V/AwesomePlayer(  325): cancelPlayerEvents
V/AwesomePlayer(  325): ~AwesomePlayer call
V/AwesomePlayer(  325): reset_l() 
V/AwesomePlayer(  325): cancelPlayerEvents
V/SoundPool( 6359): close(31)
V/SoundPool( 6359): pointer = 0x9fe34000, size = 205080, sampleRate = 48000, numChannels = 2
,I/UEI.SmartControl( 5934): Supports setup maps: true
,D/UEI.SmartControl( 5934): QS start statue = true Error code = 0
I/UEI.SmartControl( 5934): QS version = v2.7.10.1_RC1
I/UEI.SmartControl( 5934): QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
I/UEI.SmartControl( 5934): ### init IR Blaster...
D/serial_port( 5934): Configuring serial port
E/UEI.SmartControl( 5934): UEIBLaster setting for 616
I/UEI.SmartControl( 5934): Setting serial record hearder size = 2
I/UEI.SmartControl( 5934): configuring settings for MAXQ616
I/UEI.SmartControl( 5934): Get version...
D/UEI.SmartControl( 5934): serial port data available: 21
,D/UEI.SmartControl( 5934): MAXQ616 A2-X4 software.
I/UEI.SmartControl( 5934): IR Blaster version: 256702256704300002
I/UEI.SmartControl( 5934): QS saving settings...
,D/UEI.SmartControl( 5934): IR Blaster version: 25672567
D/UEI.SmartControl( 5934): serial port data available: 4
,W/ContextImpl( 5934): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
,E/UEI.SmartControl( 5934): Services init done
D/UEI.SmartControl( 5934): QS Service init finished
D/UEI.SmartControl( 5934): QS Service version name: 2.1.91
D/UEI.SmartControl( 5934): QS Service version code: 201091
I/UEI.SmartControl( 5934): Device manager: loading config....
D/UEI.SmartControl( 5934): ----------- loading internal config...
,D/UEI.SmartControl( 5934): Service requested: Control
E/UEI.SmartControl( 5934): Loading SETTINGS...
,D/UEI.SmartControl( 5934): Request IControl service: devices are loaded...
D/UEI.SmartControl( 5934): Internal service binding...
I/QRemote ( 6359): [RemoteControlManager.java:183:onServiceConnected()] oooooo start
,I/UEI.SmartControl( 5934): ------ IControl API: 11
,D/UEI.SmartControl( 5934): File observer start...
E/UEI.SmartControl( 5934): IR Port is disabled: false
D/UEI.SmartControl( 5934): Starting file observer...
I/UEI.SmartControl( 5934): Registering callback...
I/UEI.SmartControl( 5934): ------ IControl API: 19
I/UEI.SmartControl( 5934): Registering Services Ready callback...
,E/QC-QMI  ( 6348): qmi_client [6348] 13: failed to locate client data
E/QC-QMI  (  477): qmuxd: RX on fd=32 returned error=0 errno[2:No such file or directory]
E/QC-QMI  (  477): QMUX qmux_client_id=13 not found in qmux client list, unable to remove
D/UEI.SmartControl( 5934): -- Open brand translation xml: brands_translations_ko
,I/UEI.SmartControl( 5934): Notify AllClients services are ready: 0
,D/UEI.SmartControl( 5934): -----service ready thread exits
I/QRemote ( 6359): [RemoteControlManager.java:660:QSSetupIsReady()] oooooo 140517:sdkIsReady callback... get functions. Result:0
D/QRemote ( 6359): [RemoteControlManager.java:388:handleMessage()] oooooo 140510:START_SESSION
D/QRemote ( 6359): [RemoteControlManager.java:394:handleMessage()] oooooo 140510:send retrieve msg
D/QRemote ( 6359): [RemoteControlManager.java:322:handleMessage()] oooooo 140510:handler call retrieveDevices
D/QRemote ( 6359): [RemoteControlManager.java:336:retrieveDevices()] oooooo retrieveDevices: start
I/UEI.SmartControl( 5934): ------ IControl API: 8
D/QRemote ( 6359): [RemoteControlManager.java:340:retrieveDevices()] oooooo retrieveDevices: 0
D/QRemote ( 6359): [RemoteControlManager.java:345:retrieveDevices()] oooooo retrieveDevices complete:true
D/QRemote ( 6359): [RemoteControlManager.java:353:retrieveDevices()] oooooo retrieveDevices: notifyDataSetChanged()
D/QRemote ( 6359): [QRemoteApplication.java:145:onRemoteControlStateChanged()] oooooo onRemoteControlStateChanged called in QRemoteApp
,D/QRemote ( 6359): [QRemoteApplication.java:158:onRemoteControlStateChanged()] oooooo Widget count is [1]. send broadcast
D/QRemote ( 6359): [QRemoteApplication.java:160:onRemoteControlStateChanged()] oooooo Widget[0]:3
D/QRemote ( 6359): [QRemoteApplication.java:188:onRemoteControlStateChanged()] oooooo 140526:onRemoteControlStateChanged&sdkIsReady. stop Service
V/QRemote ( 6359): [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
D/QRemote ( 6359): [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
,E/QRemote ( 6359): [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
D/QRemote ( 6359): [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
D/QRemote ( 6359): [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
D/QRemote ( 6359): [RemoteAppWidgetProvider.java:506:onUpdate()] oooooo 140510:RetrieveDevices complete. Start loading
D/QRemote ( 6359): [RemoteAppWidgetProvider.java:508:onUpdate()] oooooo 140510:appWidgetIds[0]:3 loading
D/QRemote ( 6359): [RemoteAppWidgetManager.java:41:startLoading()] oooooo 140518:widgetId[3] loading start at [1454597266180]
D/QRemote ( 6359): [QRemoteService.java:207:onDestroy()] oooooo 140526:onDestroy
I/ActivityManager( 1029): Killing 5591:com.android.gallery3d/u0a27 (adj 15): empty #17
,I/qcom-bluetooth( 6412): /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 58:3f:54:73:64:c0 
,I/qcom-bluetooth( 6413): /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
I/bt_vendor( 6167): bluetooth satus is on
D/bt_hci_bdroid( 6167): preload
D/bt_userial_mct( 6167): userial_open(port:0)
I/bt_vendor( 6167): bt-vendor : BT_VND_OP_USERIAL_OPEN
,I/bt_vendor( 6167): Done intiailizing UART
I/bt_vendor( 6167): Done intiailizing UART
I/bt_userial_mct( 6167): CMD=66, EVT=66, ACL_Out=67, ACL_In=67
I/bt_vendor( 6167): Bluetooth Firmware and transport layer are initialized
D/bt_userial_mct( 6167): Entering userial_read_thread()
I/bt-btu  ( 6167): btu_task received preload complete event
W/bt-l2cap( 6167): L2CAP - L2CA_Register() called for PSM: 0x0001
W/bt-l2cap( 6167): L2CAP - L2CA_Register() called for PSM: 0x001f
W/bt-l2cap( 6167): L2CAP - L2CA_Register() called for PSM: 0x0003
D/QRemote ( 6359): [RemoteAppWidgetManager.java:239:doInBackground()] oooooo 140407:doinBack arr:0
I/        ( 6167): BTE_InitTraceLevels -- TRC_HCI
I/        ( 6167): BTE_InitTraceLevels -- TRC_L2CAP
I/        ( 6167): BTE_InitTraceLevels -- TRC_RFCOMM
I/        ( 6167): BTE_InitTraceLevels -- TRC_AVDT
I/        ( 6167): BTE_InitTraceLevels -- TRC_AVRC
I/        ( 6167): BTE_InitTraceLevels -- TRC_A2D
I/        ( 6167): BTE_InitTraceLevels -- TRC_BNEP
I/        ( 6167): BTE_InitTraceLevels -- TRC_BTM
I/        ( 6167): BTE_InitTraceLevels -- TRC_HID_HOST
I/        ( 6167): BTE_InitTraceLevels -- TRC_GAP
I/        ( 6167): BTE_InitTraceLevels -- TRC_PAN
I/        ( 6167): BTE_InitTraceLevels -- TRC_SDP
I/        ( 6167): BTE_InitTraceLevels -- TRC_GATT
I/        ( 6167): BTE_InitTraceLevels -- TRC_SMP
I/        ( 6167): BTE_InitTraceLevels -- TRC_BTAPP
I/        ( 6167): BTE_InitTraceLevels -- TRC_BTIF
W/bt-btm  ( 6167): btm_decode_ext_features_page Secure conn Controller support Enabled
E/bt-btm  ( 6167): BTM_SecRegister:p_cb_info->p_le_callback == 0xa0140061 
E/bt-btm  ( 6167): BTM_SecRegister: btm_cb.api.p_le_callback = 0xa0140061 
,E/bt-btif ( 6167): Calling BTA_HhEnable
E/bt-btif ( 6167): btif_storage_get_adapter_property service_mask:0x2140040
D/BluetoothAdapterProperties( 6167): Address is:58:3F:54:73:64:C0
W/bt-l2cap( 6167): L2CAP - L2CA_Register() called for PSM: 0x0019
W/bt-l2cap( 6167): L2CAP - L2CA_Register() called for PSM: 0x0017
W/bt-l2cap( 6167): L2CAP - L2CA_Register() called for PSM: 0x001b
W/bt-l2cap( 6167): L2CAP - L2CA_Register() called for PSM: 0x0011
W/bt-l2cap( 6167): L2CAP - L2CA_Register() called for PSM: 0x0013
W/bt-smp  ( 6167): Key(LSB ~ MSB) = 0a 3c a6 fe eb 17 6a 79 a6 1f 0a 0b f9 50 a0 5f 
W/bt-smp  ( 6167): Plain text(LSB ~ MSB) = 37 64 69 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 6167): Encrypted text(LSB ~ MSB) = 86 86 5f eb 62 5e a8 7d d2 f6 54 45 c1 a5 93 f7 
W/bt-btm  ( 6167): Stopping oneshot timer
,W/libprocessgroup( 1029): failed to open /acct/uid_10027/pid_5591/cgroup.procs: No such file or directory
D/BluetoothAdapterProperties( 6167): Name is: G3-1
D/BluetoothManagerService( 1029): Bluetooth Adapter name changed to G3-1
D/BluetoothManagerService( 1029): Stored Bluetooth name: G3-1
,D/BluetoothAdapterProperties( 6167): Scan Mode:20
D/BluetoothAdapterProperties( 6167): Discoverable Timeout:120
D/bt_hci_bdroid( 6167): postload
E/bt_mct  ( 6167): hci lib postload completed
W/bt-l2cap( 6167): L2CAP - L2CA_Register() called for PSM: 0x000f
V/QRemote ( 6359): [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.widget_ui_update
E/QRemote ( 6359): [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
D/QRemote ( 6359): [RemoteAppWidgetProvider.java:171:onReceive()] oooooo total:0
D/QRemote ( 6359): [RemoteAppWidgetProvider.java:172:onReceive()] oooooo selected:0
D/QRemote ( 6359): [RemoteAppWidgetProvider.java:173:onReceive()] oooooo arr:[]
D/QRemote ( 6359): [RemoteAppWidgetProvider.java:174:onReceive()] oooooo appWidgetId:3
D/QRemote ( 6359): [RemoteAppWidgetProvider.java:815:updateRemoteViews()] oooooo UpdateRemoteViews3:widgetId:3
,D/bte_conf( 6167): Device ID record 1 : primary
D/bte_conf( 6167):   vendorId            = 00c4
D/bte_conf( 6167):   vendorIdSource      = 0001
D/bte_conf( 6167):   product             = 13a1
D/bte_conf( 6167):   version             = 1000
D/bte_conf( 6167):   clientExecutableURL = 
D/bte_conf( 6167):   serviceDescription  = 
D/bte_conf( 6167):   documentationURL    = 
D/bte_conf( 6167): bte_load_did_conf no section named DID2.
D/QRemote ( 6359): [RemoteAppWidgetProvider.java:986:updateRemoteViews()] oooooo updateAppWidget5:widgetId:3]
W/sh      ( 6417): type=1400 audit(0.0:159): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
W/sh      ( 6417): type=1400 audit(0.0:160): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
D/BluetoothAdapterState( 6167): CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
D/BluetoothAdapterProperties( 6167): ScanMode =  20
D/BluetoothAdapterProperties( 6167): State =  11
D/BluetoothAdapterProperties( 6167): mDiscoverableTimeout = 120
V/LGBluetoothServiceAdapter( 6167): [BTUI] state:11, scanmode:20, timeout:120
,D/BluetoothAdapterProperties( 6167): Setting state to 12
I/BluetoothAdapterState( 6167): Bluetooth adapter state changed: 11-> 12
D/BluetoothManagerService( 1029): Message: 60
D/BluetoothManagerService( 1029): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
D/BluetoothPanServiceJni( 6167): control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
D/BluetoothManagerService( 1029): Broadcasting onBluetoothStateChange(true) to 5 receivers.
D/btif_config_util( 6167): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
I/BluetoothAdapterState( 6167): Entering On State
D/BluetoothHeadset( 1861): onBluetoothStateChange: up=true
D/BluetoothHeadset( 1029): onBluetoothStateChange: up=true
D/BluetoothHeadset( 1861): onBluetoothStateChange: up=true
D/BluetoothHeadset( 1861): onBluetoothStateChange: up=true
D/BluetoothA2dp( 1029): onBluetoothStateChange: up=true
D/LGBluetoothServiceAdapter( 6167): [BTUI] OnState
E/BluetoothManagerService( 1029): Fail to bind to: Intent { act=android.bluetooth.IQBluetooth }
D/BluetoothManagerService( 1029): Bluetooth State Change Intent: 11 -> 12
D/LGBluetoothServiceAdapter( 6167): [BTUI]         global_name: G3-1
D/LGBluetoothServiceAdapter( 6167): [BTUI]         local_name: G3-1
D/BluetoothAdapterService( 6167): [BTUI] autoConnect() : not allowed
D/LGBluetoothAPIService( 1958): [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
D/LGBluetoothAPIService( 1958): Message: 1
D/LGBluetoothAPIService( 1958): MESSAGE_BOOT_COMPLETED
I/[SystemUI]BluetoothHandler( 1464): Receive : BluetoothAdapter.ACTION_STATE_CHANGED
D/BluetoothManagerService( 1029): BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
D/BluetoothManagerService( 1029): Message: 40
D/BluetoothManagerService( 1029): MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
,I/LGBluetoothAPIService( 1958): [BTUI] LGBluetoothAPIService Binding Success
I/BluetoothMapService( 6167): onReceive: android.bluetooth.adapter.action.STATE_CHANGED
D/BluetoothMapService( 6167): STATE_ON
D/LGBluetoothAPIServer( 6167): [BTUI] onCreate()
,D/LGBluetoothAPIServer( 6167): [BTUI] onBind()
D/LGBluetoothDeviceModeControllManager( 6167): [BTUI] checkDeviceModeAndSet, sinkMode : false
W/ContextImpl( 6193): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
D/LGBluetoothAPIService( 1958): [BTUI] LGBluetoothAPIServiceConnection: connected to LGBluetoothAPIAdapter
,D/LGBluetoothAPIService( 1958): Message: 100
D/LGBluetoothAPIService( 1958): MESSAGE_BLUETOOTH_SERVICE_CONNECTED
I/qcom-bt-wlan-coex( 6423): /system/etc/init.qcom.coex.sh: btwlancoex/abtfilt not available 
D/BluetoothAdapterService( 6167): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a0cabc
V/BluetoothPbapService( 6167): Pbap Service onCreate
V/BluetoothPbapService( 6167): Starting PBAP service
D/LGBluetoothPbapAdapter( 6167): [BTUI] getInstance : create
V/BluetoothPbapService( 6167): action: android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothPbapService( 6167): state: 12
V/BluetoothMapService( 6167): Handler(): got msg=1
D/BluetoothMapMasInstance( 6167): Map Service startRfcommSocketListener
V/BluetoothPbapReceiver( 6167): PbapReceiver onReceive 
V/BluetoothPbapReceiver( 6167): ***********action = android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothPbapReceiver( 6167): ***********state = 12
D/BluetoothMapMasInstance( 6167): MAS initSocket()
D/BluetoothMapMasInstance( 6167):   masId = 00
D/BluetoothMapMasInstance( 6167):   msgTypes = 0e
D/BluetoothMapMasInstance( 6167):   masName = SMS/MMS
D/BluetoothMapMasInstance( 6167):   SDP string = 000eSMS/MMS
D/BluetoothManagerService( 1029): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
V/BluetoothPbapService( 6167): Handler(): got msg=1
V/BluetoothPbapService( 6167): Pbap Service startRfcommSocketListener
V/BluetoothPbapService( 6167): Pbap Service initSocket
D/BluetoothManagerService( 1029): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,W/BluetoothAdapter( 6167): getBluetoothService() called with no BluetoothManagerCallback
W/BluetoothAdapter( 6167): getBluetoothService() called with no BluetoothManagerCallback
D/LGBluetoothServiceAdapter( 6167): [BTUI] createSocketChannel FD=73 mFd=0
D/LGBluetoothServiceAdapter( 6167): [BTUI] createSocketChannel FD=75 mFd=73
V/BluetoothMapMasInstance( 6167): Succeed to create listening socket 
V/BluetoothPbapService( 6167): Succeed to create listening socket 
D/BluetoothMapMasInstance( 6167): Accepting socket connection...
V/BluetoothPbapService( 6167): Accepting socket connection...
D/LocalBluetoothProfileManager( 6193): Adding local A2DP profile
D/BluetoothManagerService( 1029): Message: 30
,D/LocalBluetoothProfileManager( 6193): Adding local HEADSET profile
D/BluetoothManagerService( 1029): Message: 30
D/BluetoothManagerService( 1029): Message: 30
D/BluetoothManagerService( 1029): Message: 30
D/LocalBluetoothProfileManager( 6193): Adding local MAP profile
D/BluetoothMap( 6193): Create BluetoothMap proxy object
D/BluetoothManagerService( 1029): Message: 30
,D/BluetoothManagerService( 1029): Message: 30
D/LocalBluetoothProfileManager( 6193): LocalBluetoothProfileManager construction complete
V/BluetoothPbapService( 6167): Pbap Service onBind
D/LGBluetoothUserBindClient( 6193): [BTUI] initUserBindClient
W/ContextImpl( 6193): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.android.settings.bluetooth.LGBluetoothUserBindClient.initUserBindClient:90 com.android.settings.bluetooth.LGBluetoothUserBindClient.<init>:55 com.android.settings.bluetooth.LGBluetoothUserBindClient.getInstance:47 
D/DockEventReceiver( 6193): finishStartingService: stopping service
,D/BluetoothA2dp( 6193): Proxy object connected
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
V/BluetoothMapService( 6167): getConnectedDevices()
D/BluetoothPbap( 6193): Proxy object connected
D/PbapServerProfile( 6193): Bluetooth service connected
D/LGBluetoothUserBindClient( 6193): [BTUI] onServiceConnected
D/BluetoothPermissionRequest( 6193): onReceive
D/LGBluetoothFeatureConfig( 6193): isPrivacyLogsEnabled : true
D/LGBluetoothUtils( 6193): [BTUI] FileNotFound: readProperty
D/LGBluetoothResetSettingReceiver( 6193): return without doing reset settings.
,V/BluetoothOppReceiver( 6167): Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_ON
I/LGBluetoothOppAdapter( 6167): [BTUI] startOppService()
V/BluetoothOppManager( 6167): restoreApplicationData! falsefalsenullnull
,D/LGBluetoothFeatureConfig( 6167): isPrivacyLogsEnabled : true
V/BtOppService( 6167): onCreate
,D/BluetoothAdapterProperties( 6167): Discoverable Timeout:120
D/LGBluetoothDeviceModeControllManager( 6167): adapterPropertyChangedCallback on  LGAdapter : do nothing - 9
D/BluetoothAdapterProperties( 6167): Scan Mode:21
D/LGBluetoothDeviceModeControllManager( 6167): getDeviceMode  deviceMode 0
V/BluetoothOppNotification( 6167): send message
V/BtOppService( 6167): Starting RfcommListener
D/BluetoothOppPreference( 6167): Dumping Names:  
D/BluetoothOppPreference( 6167): {}
D/BluetoothOppPreference( 6167): Dumping Channels:  
D/BluetoothOppPreference( 6167): {}
V/BtOppService( 6167): onStartCommand
V/BtOppService( 6167): pendingUpdate is true keepUpdateThread is false sListenStarted is true
V/BluetoothFtpReceiver( 6167): BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothFtpReceiver( 6167): BluetoothFtpReceiver Start Service
,V/BluetoothOppNotification( 6167): new notify threadi!
V/BluetoothOppNotification( 6167): send delay message
V/BtOppService( 6167): start RfcommListener
V/BtOppService( 6167): RfcommListener started
V/BtOppRfcommListener( 6167): Starting RFCOMM listener....
D/BluetoothManagerService( 1029): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
W/BluetoothAdapter( 6167): getBluetoothService() called with no BluetoothManagerCallback
D/LGBluetoothServiceAdapter( 6167): [BTUI] createSocketChannel FD=78 mFd=75
V/BtOppRfcommListener( 6167): Started RFCOMM listener....
I/BtOppRfcommListener( 6167): Accept thread started.
V/BtOppRfcommListener( 6167): Accepting connection...
V/BtOppService( 6167): Deleted complete outbound shares, number =  0
V/BluetoothOppProvider( 6167): starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
V/BtOppService( 6167): Deleted complete inbound failed shares, number = 0
V/BluetoothOppProvider( 6167): created cursor android.database.sqlite.SQLiteCursor@6e90176 on behalf of 
V/BluetoothOppProvider( 6167): starting query, database is not null; projection[0] is _id; selection is direction=1 AND status=200 AND visibility=1; selectionArgs is null; sort is _id.
V/BluetoothOppNotification( 6167): mUpdateCompleteNotification = true
V/BluetoothOppProvider( 6167): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
V/BluetoothOppProvider( 6167): created cursor android.database.sqlite.SQLiteCursor@6ebc377 on behalf of 
V/BluetoothOppProvider( 6167): starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
,D/BluetoothAdapterService( 6167): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a0cabc
V/BluetoothFtpService( 6167): Ftp Service onCreate
I/BluetoothFtpService( 6167): Ftp Service onCreate
V/BluetoothFtpService( 6167): Ftp Service onStartCommand
V/BluetoothFtpService( 6167): action: android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothFtpService( 6167): Starting Listening on sockets
V/BluetoothSapReceiver( 6167): [BTUI] checkServiceStart
V/BluetoothSapReceiver( 6167): [BTUI] region:EU country:EU
V/BluetoothSapReceiver( 6167): SapReceiver onReceive 
V/BluetoothSapReceiver( 6167): action = android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothSapReceiver( 6167):  Bluetooth Adapter state = 12
V/BluetoothSapReceiver( 6167): Calling SAP service start service with action = null
V/BtOppService( 6167): ContentObserver received notification
V/BtOppService( 6167): ContentObserver received notification
V/BluetoothFtpService( 6167): Handler(): got msg=1
D/AuthorizationBluetoothService( 2157): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
V/BluetoothOppProvider( 6167): created cursor android.database.sqlite.SQLiteCursor@1d72d84d on behalf of 
V/BluetoothOppProvider( 6167): created cursor android.database.sqlite.SQLiteCursor@205bbf02 on behalf of 
V/BluetoothFtpService( 6167): Ftp Service startRfcommSocketListener
V/BluetoothFtpService( 6167): Ftp Service initSocket,
V/BtOppService( 6167): pendingUpdate is true keepUpdateThread is false sListenStarted is true
V/BluetoothOppProvider( 6167): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
D/BluetoothManagerService( 1029): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
V/BluetoothOppNotification( 6167): outbound: succ-0  fail-0
W/BluetoothAdapter( 6167): getBluetoothService() called with no BluetoothManagerCallback
D/LGBluetoothServiceAdapter( 6167): [BTUI] createSocketChannel FD=80 mFd=78
V/BluetoothFtpService( 6167): Succeed to create listening socket on channel 20
V/BluetoothOppProvider( 6167): created cursor android.database.sqlite.SQLiteCursor@38cf2013 on behalf of 
V/BluetoothOppNotification( 6167): outbound notification was removed.
V/BluetoothOppProvider( 6167): starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
V/BluetoothOppNotification( 6167): update too frequent, put in queue
V/BluetoothOppProvider( 6167): created cursor android.database.sqlite.SQLiteCursor@2da8a250 on behalf of 
V/BluetoothOppNotification( 6167): inbound: succ-0  fail-0
,V/BluetoothOppNotification( 6167): inbound notification was removed.
V/BluetoothOppProvider( 6167): starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
V/BtOppService( 6167): pendingUpdate is false keepUpdateThread is false sListenStarted is true
V/BluetoothOppProvider( 6167): created cursor android.database.sqlite.SQLiteCursor@2c21ac49 on behalf of 
,V/BluetoothFtpService:RfcommSocketAcceptThread( 6167): Run Accept thread
D/BluetoothAdapterService( 6167): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a0cabc
V/BluetoothSapService( 6167): Sap Service onCreate
,V/BluetoothSapService( 6167): action: android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothSapService( 6167): state: 12
V/BluetoothSapService( 6167): Starting SAP server process
V/BluetoothSapService( 6167): SAP Service startRfcommListenerThread
V/BluetoothSapService( 6167): Sap Service initRfcommSocket
D/BluetoothManagerService( 1029): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
W/BluetoothAdapter( 6167): getBluetoothService() called with no BluetoothManagerCallback
D/LGBluetoothServiceAdapter( 6167): [BTUI] createSocketChannel FD=82 mFd=80
V/BluetoothSapService( 6167): Succeed to create listening socket 
V/BluetoothSapService( 6167): Accepting socket connection...
W/sapd    ( 6444): type=1400 audit(0.0:161): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
W/sapd    ( 6444): type=1400 audit(0.0:162): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
V/BT_SAP  ( 6444): Event pipe created
V/BT_SAP  ( 6444): create_server_socket qcom.sap.server
V/BT_SAP  ( 6444): created socket fd 6
,I/wpa_supplicant( 6202): wlan0: CTRL-EVENT-ASSOC-REJECT bssid=c0:ff:d4:d3:aa:48 status_code=1
,D/WifiMonitor( 1029): Event [IFNAME=wlan0 CTRL-EVENT-ASSOC-REJECT bssid=c0:ff:d4:d3:aa:48 status_code=1]
E/WifiMonitor( 1029): WifiMonitor:wlan0 cnt=12 dispatchEvent: CTRL-EVENT-ASSOC-REJECT bssid=c0:ff:d4:d3:aa:48 status_code=1
D/WifiMonitor( 1029): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=00:00:00:00:00:00 SSID=NG700]
E/WifiMonitor( 1029): WifiMonitor:wlan0 cnt=13 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=00:00:00:00:00:00 SSID=NG700
E/WifiStateMachine( 1029):  DisconnectedState ASSOCIATION_REJECTION_EVENT 12 1 c0:ff:d4:d3:aa:48 blacklist=false rt=119288
E/WifiStateMachine( 1029):  ConnectModeState ASSOCIATION_REJECTION_EVENT 12 1 c0:ff:d4:d3:aa:48 blacklist=false rt=119288
E/WifiStateMachine( 1029):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 13 0 rt=119289  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: DISCONNECTED
D/WifiHS20( 1029): hidePasspointNotification off =false
W/Settings( 1029): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1029): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1029): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
I/StatusBar.NetworkController( 1464): networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1464): mWifiConnected = false, mWifiLevel = 0
,D/StatusBar.NetworkController( 1464): refreshViews: Data not connected!! Set no data type icon / Roaming
E/WifiStateMachine( 1029):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 13 0 rt=119304  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: DISCONNECTED
D/WifiServerServiceExt( 1029): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1029): setSupplicantStateDISCONNECTED
,D/PostponalbeReceiver( 5221): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,I/wpa_supplicant( 6202): wlan0: CTRL-EVENT-SCAN-STARTED 
,D/WifiMonitor( 1029): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
E/WifiMonitor( 1029): WifiMonitor:wlan0 cnt=14 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
,D/WifiMonitor( 1029): Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1029): WifiMonitor:wlan0 cnt=15 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1029): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1029): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
E/WifiStateMachine( 1029):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 14 0 rt=119389  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
D/WifiHS20( 1029): hidePasspointNotification off =false
W/Settings( 1029): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1029): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1029): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
E/WifiStateMachine( 1029):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 14 0 rt=119397  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
,W/Settings( 1029): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1029): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1029): NETWORK_STATE_CHANGED_ACTION [SCANNING]
V/BluetoothOppNotification( 6167): new notify threadi!
V/BluetoothOppNotification( 6167): send delay message
I/StatusBar.NetworkController( 1464): networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1464): mWifiConnected = false, mWifiLevel = 0
D/WifiServerServiceExt( 1029): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1029): setSupplicantStateSCANNING
D/StatusBar.NetworkController( 1464): refreshViews: Data not connected!! Set no data type icon / Roaming
V/BluetoothOppProvider( 6167): starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
V/BluetoothOppProvider( 6167): created cursor android.database.sqlite.SQLiteCursor@20cfc405 on behalf of 
V/BluetoothOppNotification( 6167): mUpdateCompleteNotification = true
I/PCSuite ( 6280): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 6280): [StartReceiver][getUpdateNecessity]update = false
I/StatusBar.NetworkController( 1464): networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/PCSuite ( 6280): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
I/StatusBar.NetworkController( 1464): mWifiConnected = false, mWifiLevel = 0
V/BluetoothOppProvider( 6167): starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
D/StatusBar.NetworkController( 1464): refreshViews: Data not connected!! Set no data type icon / Roaming
V/BluetoothOppProvider( 6167): created cursor android.database.sqlite.SQLiteCursor@270e2c5a on behalf of 
V/BluetoothOppNotification( 6167): outbound: succ-0  fail-0
,V/BluetoothOppNotification( 6167): outbound notification was removed.
V/BluetoothOppProvider( 6167): starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
V/WiFiOffLoadBroadcast( 6193): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
V/BluetoothOppProvider( 6167): created cursor android.database.sqlite.SQLiteCursor@1a287e8b on behalf of 
D/WiFiOffLoadBroadcast( 6193): MCCMNC not supported: null
V/BluetoothOppNotification( 6167): inbound: succ-0  fail-0
V/BluetoothOppNotification( 6167): inbound notification was removed.
V/BluetoothOppProvider( 6167): starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
,V/BluetoothOppProvider( 6167): created cursor android.database.sqlite.SQLiteCursor@244e6b68 on behalf of 
D/QRemote ( 6359): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6359): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 6359): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
D/PostponalbeReceiver( 5221): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,I/PCSuite ( 6280): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 6280): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 6280): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,V/WiFiOffLoadBroadcast( 6193): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 6193): MCCMNC not supported: null
D/QRemote ( 6359): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6359): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 6359): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
D/PostponalbeReceiver( 5221): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
V/WiFiOffLoadBroadcast( 6193): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6193): MCCMNC not supported: null
D/QRemote ( 6359): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,D/QRemote ( 6359): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 6359): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
I/wpa_supplicant( 6202): Trying to associate with SSID 'NG700'
E/WifiMonitor( 1029): WifiMonitor:wlan0 cnt=16 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
E/WifiMonitor( 1029): handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
D/WifiMonitor( 1029): Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
E/WifiMonitor( 1029): WifiMonitor:wlan0 cnt=17 dispatchEvent: WPS-AP-AVAILABLE 
W/WifiMonitor( 1029): couldn't identify event type - WPS-AP-AVAILABLE 
D/WifiMonitor( 1029): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
E/WifiMonitor( 1029): WifiMonitor:wlan0 cnt=18 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
,E/WifiStateMachine( 1029):  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=4 known=0 got=4 bcn=0
E/WifiStateMachine( 1029):  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=4 known=0 got=4 bcn=0
E/WifiStateMachine( 1029):  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=4 known=0 got=4 bcn=0
E/WifiStateMachine( 1029):  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=4 known=0 got=4 bcn=0
I/WifiNative-HAL( 1029): startHal
E/wifi    ( 1029): getStaticLongField sWifiHalHandle 0x988c38cc
E/WifiHAL ( 1029): Could not connect handle
D/wifi    ( 1029): halHandle = 0x0, mVM = 0xb487c280, mCls = 0x20229a
I/WifiNative-HAL( 1029): Could not start hal
D/WifiNative-wlan0( 1029): doString: [BSS RANGE=0- MASK=0x21987]
E/WifiStateMachine( 1029):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 18 0 rt=121531  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
I/StatusBar.NetworkController( 1464): networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1464): mWifiConnected = false, mWifiLevel = 0
,D/StatusBar.NetworkController( 1464): refreshViews: Data not connected!! Set no data type icon / Roaming
W/Settings( 1029): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1029): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1029): NETWORK_STATE_CHANGED_ACTION [SCANNING]
E/WifiStateMachine( 1029):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 18 0 rt=121547  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
W/Settings( 1029): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1029): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1029): NETWORK_STATE_CHANGED_ACTION [CONNECTING]
D/WifiServerServiceExt( 1029): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1029): setSupplicantStateASSOCIATING
D/PostponalbeReceiver( 5221): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
V/WiFiOffLoadBroadcast( 6193): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,I/StatusBar.NetworkController( 1464): networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1464): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1464): refreshViews: Data not connected!! Set no data type icon / Roaming
D/WiFiOffLoadBroadcast( 6193): MCCMNC not supported: null
,D/QRemote ( 6359): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6359): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 6359): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
D/PostponalbeReceiver( 5221): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
V/WiFiOffLoadBroadcast( 6193): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6193): MCCMNC not supported: null
,D/QRemote ( 6359): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6359): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 6359): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
I/jxcore-log( 6110): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMultiplex.js
I/jxcore-log( 6110): 
,I/wpa_supplicant( 6202): wlan0: Associated with c0:ff:d4:d3:aa:48
,D/WifiMonitor( 1029): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
E/WifiMonitor( 1029): WifiMonitor:wlan0 cnt=19 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
D/WifiMonitor( 1029): Event [IFNAME=wlan0 Associated with c0:ff:d4:d3:aa:48]
E/WifiMonitor( 1029): WifiMonitor:wlan0 cnt=20 dispatchEvent: Associated with c0:ff:d4:d3:aa:48
D/WifiMonitor( 1029): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1029): WifiMonitor:wlan0 cnt=21 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
I/wpa_supplicant( 6202): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 6202): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
E/WifiStateMachine( 1029):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 19 0 rt=122866  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
,D/WifiMonitor( 1029): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1029): WifiMonitor:wlan0 cnt=22 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/WifiMonitor( 1029): Event [IFNAME=wlan0 WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]]
E/WifiMonitor( 1029): WifiMonitor:wlan0 cnt=23 dispatchEvent: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
W/WifiMonitor( 1029): couldn't identify event type - WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
D/WifiMonitor( 1029): Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]]
E/WifiMonitor( 1029): WifiMonitor:wlan0 cnt=24 dispatchEvent: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
E/WifiMonitor( 1029): handleEvent 1  Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
E/WifiStateMachine( 1029):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 19 0 rt=122873  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
E/WifiStateMachine( 1029):  DisconnectedState CMD_ASSOCIATED_BSSID 20 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=122876
E/WifiStateMachine( 1029):  ConnectModeState CMD_ASSOCIATED_BSSID 20 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=122877
E/WifiStateMachine( 1029):  DriverStartedState CMD_ASSOCIATED_BSSID 20 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=122877
D/WifiMonitor( 1029): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1029): WifiMonitor:wlan0 cnt=25 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
,D/Tethering( 1029): sendTetherStateChangedBroadcast 1, 0, 0
E/WifiStateMachine( 1029):  SupplicantStartedState CMD_ASSOCIATED_BSSID 20 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=122888
E/WifiStateMachine( 1029):  DefaultState CMD_ASSOCIATED_BSSID 20 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=122888
E/WifiStateMachine( 1029):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 21 0 rt=122889  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: FOUR_WAY_HANDSHAKE
D/libc-netbsd(  320): default dns: query_ipv6=0, query_ipv4=0
,D/DSQN    ( 1029): DNSproblemNotiEnabled is disabled ignore DNS fail CB
,I/StatusBar.NetworkController( 1464): networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1464): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1464): refreshViews: Data not connected!! Set no data type icon / Roaming
W/Settings( 1029): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1029): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1029): NETWORK_STATE_CHANGED_ACTION [CONNECTING]
,W/Settings( 1029): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1029): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1029): NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
I/StatusBar.NetworkController( 1464): networkInfo=[type: WIFI[], state: CONNECTING/AUTHENTICATING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1464): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1464): refreshViews: Data not connected!! Set no data type icon / Roaming
E/WifiStateMachine( 1029):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 21 0 rt=122930  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: FOUR_WAY_HANDSHAKE
E/WifiStateMachine( 1029):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 22 0 rt=122931  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: GROUP_HANDSHAKE
E/WifiStateMachine( 1029):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 22 0 rt=122932  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: GROUP_HANDSHAKE
D/UsbSettingsReceiver( 6193): [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
D/UsbSettingsReceiver( 6193): [AUTORUN] sys.usb.config = ptp_only,adb
D/UsbSettingsReceiver( 6193): [AUTORUN] sys.usb.state = ptp_only,adb
D/UsbSettingsReceiver( 6193): [AUTORUN] persist.sys.usb.config = ptp_only,adb
E/WifiStateMachine( 1029):  DisconnectedState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=122934
,D/WifiServerServiceExt( 1029): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1029): setSupplicantStateASSOCIATED
D/UEI.SmartControl( 5934): Internal timer expired: 2
D/UEI.SmartControl( 5934): unbind internal service
E/WifiStateMachine( 1029):  ConnectModeState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=122934
,D/WifiNative-wlan0( 1029): doString: [STATUS]
D/WifiNative-wlan0( 1029):    returned bssid=c0:ff:d4:d3:aa:48 ssid=NG700 id=0 mode=station pairwise_cipher=CCMP group_cipher=CCMP key_mgmt=WPA2-PSK wpa_state=COMPLETED p2p_device_address=02:9a:02:7b:60:ac address=c4:9a:02:7b:60:ac uuid=530d3fd0-1ba3-5409-a336-ff4e42af59a2
D/WifiMonitor( 1029): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1029): WifiMonitor:wlan0 cnt=26 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
I/WifiServiceExtension( 1029): setVHTCapabilityType  : false
D/UsbSettingsReceiver( 6193): [AUTORUN] onReceive() : app userid = 0, current userid = 0
D/UsbSettingsControl( 6193): [AUTORUN] getUsbConnected() : connected=true
D/UsbSettingsReceiver( 6193): [AUTORUN] onReceive() : availableList=[wlan0]
D/UsbSettingsReceiver( 6193): [AUTORUN] onReceive() : activeList=[]
D/UsbSettingsReceiver( 6193): [AUTORUN] onReceive() : errorList=[]
D/UsbSettingsControl( 6193): [AUTORUN] isAutorunTimer() : mAutorunChanging=false
D/UsbSettingsReceiver( 6193): [AUTORUN] onReceive() : TetherState Changed=wlan0
D/UsbSettingsControl( 6193): [AUTORUN] setTetherStatus() : status=false
,I/WifiServerServiceExt( 1029): wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
I/WifiServerServiceExt( 1029): setKeepAlivePacketInterval msec : 60
D/PostponalbeReceiver( 5221): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
W/Settings( 1029): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1029): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1029): NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
I/StatusBar.NetworkController( 1464): networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1464): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1464): refreshViews: Data not connected!! Set no data type icon / Roaming
W/Settings( 1029): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1029): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1029): NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
I/StatusBar.NetworkController( 1464): networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1464): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1464): refreshViews: Data not connected!! Set no data type icon / Roaming
,V/WiFiOffLoadBroadcast( 6193): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
V/AlarmManager( 1029): ELAPSED_WAKEUP set : Alarm{3ed0693 type 2 when 121649 com.google.android.gms} when 121649
D/WiFiOffLoadBroadcast( 6193): MCCMNC not supported: null
D/ConnectivityService( 1029): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
D/ConnectivityService( 1029): Got NetworkAgent Messenger
E/WifiConfigStore( 1029): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/WifiNative-wlan0( 1029): doBoolean: SET_NETWORK 0 bssid any
,D/WifiNative-wlan0( 1029): SET_NETWORK 0 bssid any: returned true
D/WifiNative-wlan0( 1029): doBoolean: SAVE_CONFIG
D/ConnectivityService( 1029): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
D/ConnectivityService( 1029): NetworkAgent connected
D/QRemote ( 6359): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6359): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 6359): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
D/PostponalbeReceiver( 5221): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
D/WifiNative-wlan0( 1029): SAVE_CONFIG: returned true
E/WifiConfigStore( 1029): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/WifiNative-wlan0( 1029): doBoolean: SET_NETWORK 0 bssid any
D/WifiNative-wlan0( 1029): SET_NETWORK 0 bssid any: returned true
D/WifiNative-wlan0( 1029): doBoolean: SAVE_CONFIG
D/WifiNative-wlan0( 1029): SAVE_CONFIG: returned true
D/CommandListener(  320): Setting iface cfg
,V/WiFiOffLoadBroadcast( 6193): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/DhcpStateMachine( 1029): StoppedState
E/WifiStateMachine( 1029): Start Dhcp Watchdog 1
D/DhcpStateMachine( 1029): StoppedState{ when=0 what=196609 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine( 1029): WaitBeforeStartState
E/WifiStateMachine( 1029):  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 25 0 rt=123027  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine( 1029):  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 25 0 rt=123029  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine( 1029):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 25 0 rt=123029  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
D/WiFiOffLoadBroadcast( 6193): MCCMNC not supported: null
E/WifiStateMachine( 1029):  ObtainingIpState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1029):  L2ConnectedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1029):  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1029):  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1029):  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1029):  DefaultState CMD_TETHER_STATE_CHANGE 0 0
D/WifiServerServiceExt( 1029): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1029): setSupplicantStateFOUR_WAY_HANDSHAKE
D/WifiServerServiceExt( 1029): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1029): setSupplicantStateGROUP_HANDSHAKE
,D/QRemote ( 6359): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6359): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
E/WifiStateMachine( 1029):  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 26 0 rt=123036  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
I/QRemote ( 6359): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
E/WifiStateMachine( 1029):  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 26 0 rt=123036  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine( 1029):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 26 0 rt=123037  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
D/PostponalbeReceiver( 5221): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
E/WifiStateMachine( 1029):  ObtainingIpState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:-1396642175] from screen [on:0 period:-1396642175]
E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-1396642174]
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
D/StatusBar.NetworkController( 1464): refreshViews: Data not connected!! Set no data type icon / Roaming
,V/WiFiOffLoadBroadcast( 6193): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/ConnectivityService( 1029): updateNetworkScore for NetworkAgentInfo [WIFI () - 100] to 60
E/WifiStateMachine( 1029):  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1029):  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1029):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1029):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
D/WiFiOffLoadBroadcast( 6193): MCCMNC not supported: null
E/WifiStateMachine( 1029):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1029):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
D/ConnectivityService( 1029): Update of LinkProperties for NetworkAgentInfo [WIFI () - 100]; created=false
E/WifiStateMachine( 1029):  ObtainingIpState CMD_PRE_DHCP_ACTION 0 0 txpkts=1,0,0
E/WifiStateMachine( 1029):  L2ConnectedState CMD_PRE_DHCP_ACTION 0 0 txpkts=1,0,0
D/WifiNative-wlan0( 1029): doBoolean: DRIVER SETSUSPENDMODE 0
D/QRemote ( 6359): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6359): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 6359): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
D/PostponalbeReceiver( 5221): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,V/WiFiOffLoadBroadcast( 6193): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6193): MCCMNC not supported: null
D/QRemote ( 6359): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6359): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 6359): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
I/wpa_supplicant( 6202): wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 0
D/WifiNative-wlan0( 1029): DRIVER SETSUSPENDMODE 0: returned true
D/WifiNative-wlan0( 1029): doBoolean: SET ps 0
D/WifiNative-wlan0( 1029): SET ps 0: returned true
D/WifiNative-wlan0( 1029): doBoolean: DRIVER BTCOEXMODE 1
I/wpa_supplicant( 6202): wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 1
D/WifiNative-wlan0( 1029): DRIVER BTCOEXMODE 1: returned true
E/WifiStateMachine( 1029): CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
D/LGWifiP2pService( 1029): InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@334c808a target=com.android.internal.util.StateMachine$SmHandler }
V/DhcpStateMachine( 1029): Current State is mWaitBeforeStartState.
D/LGWifiP2pService( 1029): P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@334c808a target=com.android.internal.util.StateMachine$SmHandler }
V/LgDhcpStateMachineHelper( 1029): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
D/DhcpStateMachine( 1029): WaitBeforeStartState{ when=0 what=196615 target=com.android.internal.util.StateMachine$SmHandler }
V/LgDhcpStateMachineHelper( 1029): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700" is not exist.
D/DhcpStateMachine( 1029): DHCP Start wake lock is acquired.
D/WifiServerServiceExt( 1029): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1029): setSupplicantStateCOMPLETED
D/WifiServerServiceExt( 1029): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1029): setSupplicantStateCOMPLETED
D/libc-netbsd(  320): default dns: query_ipv6=0, query_ipv4=0
,D/DSQN    ( 1029): DNSproblemNotiEnabled is disabled ignore DNS fail CB
V/QRemote ( 6359): [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.wait_loading
D/QRemote ( 6359): [RemoteAppWidgetProvider.java:211:onReceive()] oooooo 140514:alarm msg received!:7812
I/ActivityManager( 1029): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.realtimechat.RequestWriter$NetworkStateReceiver: pid=6536 uid=10072 gids={50072, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,I/art     (  352): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 452us total 20.252ms
,I/art     (  352): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 398us total 17.884ms
,I/jxcore-log( 6110): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
I/jxcore-log( 6110): 
I/art     (  352): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 360us total 16.163ms
,W/ResourcesManager( 6536): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
D/LgDataFeature( 6536): LgDataFeature() Constructor: none
,D/LgDataFeature( 6536): LgDataFeature() Constructor Done, null
,D/DhcpStateMachine( 1029): DHCPV4 request on wlan0
V/LgDhcpStateMachineHelper( 1029): [bssid] hash key :c0:ff:d4:d3:aa:48
D/LgDhcpStateMachineHelper( 1029): dhcp.ap.macaddress = c0:ff:d4:d3:aa:48
I/jxcore-log( 6110): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
I/jxcore-log( 6110): 
,W/dhcpcd  ( 6553): type=1400 audit(0.0:163): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
W/dhcpcd  ( 6553): type=1400 audit(0.0:164): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
I/jxcore-log( 6110): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliCryptoManager.js
I/jxcore-log( 6110): 
I/dhcpcd  ( 6553): version 5.5.6 starting
E/dhcpcd  ( 6553): get_duid: m
D/dhcpcd  ( 6553): wlan0: using ClientID 01:c4:9a:02:7b:60:ac
D/dhcpcd  ( 6553): wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason PREINIT
,I/jxcore-log( 6110): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliEmitter.js
I/jxcore-log( 6110): 
I/Babel   ( 6536): MmsConfig: mnc/mcc: 0/0
I/Babel   ( 6536): MmsConfig.loadMmsSettings
I/Babel   ( 6536): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D855 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D855-M3-D1.xml
D/dhcpcd  ( 6553): getUsingAPMacAddress: c0:ff:d4:d3:aa:48 , return 1
,I/Babel   ( 6536): MmsConfig.loadFromDatabase
D/dhcpcd  ( 6553): [read_lease] unlink /data/misc/dhcp/dhcpcd-wlan0.lease, link /data/misc/dhcp/dhcpcd-wlan0-c0:ff:d4:d3:aa:48.lease2
D/dhcpcd  ( 6553): wlan0: reading lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
,I/jxcore-log( 6110): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNativeLayer.js
I/jxcore-log( 6110): 
I/dhcpcd  ( 6553): wlan0: rebinding lease of 192.168.1.141
D/dhcpcd  ( 6553): wlan0: sending REQUEST (xid 0x62449341), next in 4.45 seconds
E/Babel   ( 6536): canonicalizeMccMnc: invalid mccmnc 
I/Babel   ( 6536): MmsConfig.loadFromResources
,I/jxcore-log( 6110): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationManager.js
I/jxcore-log( 6110): 
E/Babel   ( 6536): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel   ( 6536): MmsConfig.loadMmsSettings: mUserAgent=LG-D855 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D855-M3-D1.xml
I/jxcore-log( 6110): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
I/jxcore-log( 6110): 
W/AudioCapabilities( 6536): Unsupported mime audio/evrc
W/AudioCapabilities( 6536): Unsupported mime audio/qcelp
W/VideoCapabilities( 6536): Unrecognized profile 2130706433 for video/avc
,W/Settings( 6536): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/serial_port( 5934): close(fd = 24)
W/AudioCapabilities( 6536): Unsupported mime audio/amr-wb-plus
,I/UEI.SmartControl( 5934): Serial port is closed.
W/AudioCapabilities( 6536): Unsupported mime audio/qcelp
,W/AudioCapabilities( 6536): Unsupported mime audio/evrc
I/ActivityManager( 1029): Killing 5953:com.google.android.apps.docs/u0a61 (adj 15): empty #17
,W/VideoCapabilities( 6536): Unsupported mime video/x-ms-wmv
W/VideoCapabilities( 6536): Unsupported mime video/divx
W/VideoCapabilities( 6536): Unsupported mime video/divx311
W/VideoCapabilities( 6536): Unsupported mime video/divx4
W/VideoCapabilities( 6536): Unsupported mime video/mp4v-esdp
,I/VideoCapabilities( 6536): Unsupported profile 4 for video/mp4v-es
,W/AudioCapabilities( 6536): Unsupported mime audio/eac3
W/AudioCapabilities( 6536): Unsupported mime audio/ac3
W/AudioCapabilities( 6536): Unsupported mime audio/g726
W/AudioCapabilities( 6536): Unsupported mime audio/wma-voice
W/AudioCapabilities( 6536): Unsupported mime audio/x-ms-wma
W/AudioCapabilities( 6536): Unsupported mime audio/adpcm
W/VideoCapabilities( 6536): Unsupported mime video/theora
,W/VideoCapabilities( 6536): Unsupported mime video/mjpg
W/libprocessgroup( 1029): failed to open /acct/uid_10061/pid_5953/cgroup.procs: No such file or directory
,I/dhcpcd  ( 6553): wlan0: acknowledged 192.168.1.141 from 192.168.1.1
,I/dhcpcd  ( 6553): wlan0: leased 192.168.1.141 for 86400 seconds
D/dhcpcd  ( 6553): wlan0: adding IP address 192.168.1.141/24
D/dhcpcd  ( 6553): wlan0: adding route to 192.168.1.0/24
D/dhcpcd  ( 6553): wlan0: adding default route via 192.168.1.1
,D/dhcpcd  ( 6553): wlan0: writing lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
D/dhcpcd  ( 6553): getUsingAPMacAddress: c0:ff:d4:d3:aa:48 , return 1
D/dhcpcd  ( 6553): write_lease_ext: /data/misc/dhcp/dhcpcd-wlan0-c0:ff:d4:d3:aa:48.lease2
D/dhcpcd  ( 6553): wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason REBOOT
,E/WifiStateMachine( 1029):  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1029):  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1029):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
,E/WifiStateMachine( 1029):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1029):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1029):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
D/ConnectivityService( 1029): Update of LinkProperties for NetworkAgentInfo [WIFI () - 100]; created=false
E/WifiStateMachine( 1029):  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0 v4
E/WifiStateMachine( 1029):  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4
E/WifiStateMachine( 1029):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0 v4
E/WifiStateMachine( 1029):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4
E/WifiStateMachine( 1029):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4
E/WifiStateMachine( 1029):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0 v4
,D/ConnectivityService( 1029): Update of LinkProperties for NetworkAgentInfo [WIFI () - 100]; created=false
D/DhcpStateMachine( 1029): DHCPV4 succeeded on wlan0
,D/LgDhcpStateMachineHelper( 1029): CheckDhcpDirectory [Lease File Count] : 3
V/LgDhcpStateMachineHelper( 1029): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
D/LgDhcpStateMachineHelper( 1029): checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.141
V/LgDhcpStateMachineHelper( 1029): Add DhcpResults: IP address 192.168.1.141/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 86400 seconds
V/DhcpStateMachine( 1029): Current State is mWaitBeforeStartState.
V/LgDhcpStateMachineHelper( 1029): bShouldSendDhcpAction Result: true
D/DhcpStateMachine( 1029): DHCP Start/Renew wake lock is released.
D/DhcpStateMachine( 1029): RunningState
E/WifiStateMachine( 1029):  ObtainingIpState CMD_POST_DHCP_ACTION 1 0 OK  v4
,E/WifiStateMachine( 1029):  L2ConnectedState CMD_POST_DHCP_ACTION 1 0 OK  v4
D/WifiNative-wlan0( 1029): doBoolean: DRIVER BTCOEXMODE 2
I/wpa_supplicant( 6202): wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
D/LGWifiP2pService( 1029): InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1029): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0( 1029): DRIVER BTCOEXMODE 2: returned true
D/WifiNative-wlan0( 1029): doBoolean: DRIVER SETSUSPENDMODE 1
I/wpa_supplicant( 6202): wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 1
D/WifiNative-wlan0( 1029): DRIVER SETSUSPENDMODE 1: returned true
D/WifiNative-wlan0( 1029): doBoolean: SET ps 1
D/WifiNative-wlan0( 1029): SET ps 1: returned true
E/WifiStateMachine( 1029):  ObtainingIpState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
E/WifiStateMachine( 1029):  L2ConnectedState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
E/WifiStateMachine( 1029): WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
D/ConnectivityService( 1029): Update of LinkProperties for NetworkAgentInfo [WIFI () - 100]; created=false
D/ConnectivityService( 1029): ignoring duplicate network state non-change
,W/Settings( 1029): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1029): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1029): NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
,D/ConnectivityService( 1029): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
D/ConnectivityService( 1029): Adding iface wlan0 to network 100
I/StatusBar.NetworkController( 1464): networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1464): mWifiConnected = false, mWifiLevel = 0
,D/StatusBar.NetworkController( 1464): refreshViews: Data not connected!! Set no data type icon / Roaming
D/PostponalbeReceiver( 5221): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,E/WifiStateMachine( 1029): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,W/Settings( 1029): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
E/ConnectivityService( 1029): Unexpected mtu value: 0, wlan0
W/Settings( 1029): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1029): NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
D/ConnectivityService( 1029): Adding Route [fe80::/64 -> :: wlan0] to network 100
D/ConnectivityService( 1029): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 100
D/WifiHS20( 1029): [PASSPOINT] passpointNotification: hs20AP list is checked
D/ConnectivityService( 1029): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 100
D/ConnectivityService( 1029): addLocalRoutetoDefaultNetwork
D/ConnectivityService( 1029): defaultNAI is null or Wi-Fi no need to add Loacal route to default network. WiFi netid = 100
D/ConnectivityService( 1029): Setting Dns servers for network 100 to [/192.168.1.1]
W/Settings( 1029): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1029): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1029): NETWORK_STATE_CHANGED_ACTION [CONNECTED]
D/WifiHS20( 1029): [PASSPOINT] passpointNotification: hs20AP list is checked
,I/StatusBar.NetworkController( 1464): networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1464): mWifiConnected = false, mWifiLevel = 0
V/WfdStateTracker( 1958): handleWifiStateChangedEvent: 1
D/StatusBar.NetworkController( 1464): refreshViews: Data not connected!! Set no data type icon / Roaming
I/StatusBar.NetworkController( 1464): networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,W/Settings( 1029): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings( 1029): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1029): NETWORK_STATE_CHANGED_ACTION [CONNECTED]
D/Nat464Xlat( 1029): requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
D/ConnectivityService( 1029): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService( 1029): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService( 1029): rematching NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService( 1029):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService( 1029):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1029):     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
D/ConnectivityService( 1029):   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1029):     satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:true
D/ConnectivityService( 1029): currentScore = 0, newScore = 20
D/ConnectivityService( 1029):    accepting network in place of null
D/ConnectivityService( 1029): sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
I/StatusBar.NetworkController( 1464): mWifiConnected = true, mWifiLevel = 2
D/ConnectivityService( 1029): Setting tx/rx TCP buffers to 524288,1048576,2097152,262144,524288,1048576
D/StatusBar.NetworkController( 1464): refreshViews: Data not connected!! Set no data type icon / Roaming
D/WIFI    ( 1029): new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    ( 1029):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1029): DefaultState{ when=-6ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1029): Connected
D/TelephonyNetworkFactory-1( 1861): new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1029): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/TelephonyNetworkFactory-1( 1861):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
,D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1029): Checking http://clients3.google.com/generate_204 on "NG700"
I/StatusBar.NetworkController( 1464): networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1464): mWifiConnected = true, mWifiLevel = 2
D/StatusBar.NetworkController( 1464): refreshViews: Data not connected!! Set no data type icon / Roaming
D/libc-netbsd(  320): res_queryN name = clients3.google.com, class = 1, type = 28
,E/ConnectivityService( 1029): [lg_data] Adding agent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.141/24,fe80::c69a:2ff:fe7b:60ac/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
D/CSLegacyTypeTracker( 1029): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
D/ConnectivityService( 1029): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService( 1029): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/CSLegacyTypeTracker( 1029): [e] list.add(nai) empty : false size: 1
D/ConnectivityService( 1029): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.141/24,fe80::c69a:2ff:fe7b:60ac/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
D/LocSvc_java( 1029): Sending msg: 4 arg1:1 arg2:1
D/ConnectivityService( 1029): validation of new default Network = false
D/ConnectivityService( 1029): Default network via Wi-Fi connected. start DSQN
D/LocSvc_java( 1029): getAGpsConnectionInfo connType - 4
D/DSQN    ( 1029): enableDataServiceNotify 
D/DSQN    ( 1029): start dsqn bin
D/LocSvc_java( 1029): updateNetworkState connTyp: 4 available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java( 1029): ignore wifi update if we are not in OPENING or CLOSING
D/LocSvc_java( 1029): Sending msg: 5 arg1:0 arg2:1
D/libc-netbsd(  320): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  320): res_queryN name = 2.android.pool.ntp.org, class = 1, type = 1
,D/libc-netbsd(  320): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  320): res_queryN name = europe.pool.ntp.org, class = 1, type = 1
D/ConnectivityService( 1029): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 100]
,D/ConnectivityService( 1029):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1029):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1029): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityManager.CallbackHandler( 1464): CM callback handler got msg 524290
W/dsqn    ( 6617): type=1400 audit(0.0:165): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,W/dsqn    ( 6617): type=1400 audit(0.0:166): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
V/WiFiOffLoadBroadcast( 6193): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6193): MCCMNC not supported: null
D/libc-netbsd(  320): res_queryN name = clients3.google.com, class = 1, type = 1
E/DSQN    ( 6617): DSQN ssw
D/TelephonyIcons( 1464): null signal icon name: drawable/stat_sys_signal_null
D/StatusBar.NetworkController( 1464): refreshViews: Data not connected!! Set no data type icon / Roaming
D/StatusBar.NetworkController( 1464): refreshViews: Data not connected!! Set no data type icon / Roaming
,D/libc-netbsd(  320): res_queryN name = 2.android.pool.ntp.org succeed
D/QRemote ( 6359): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6359): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 6359): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
D/PostponalbeReceiver( 5221): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,V/WiFiOffLoadBroadcast( 6193): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 6193): MCCMNC not supported: null
D/libc-netbsd(  320): res_queryN name = clients3.google.com succeed
,D/QRemote ( 6359): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6359): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 6359): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
D/PostponalbeReceiver( 5221): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
I/PCSuite ( 6280): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
,D/PCSuite ( 6280): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
D/libc-netbsd(  320): res_queryN name = europe.pool.ntp.org succeed
V/WiFiOffLoadBroadcast( 6193): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/LGDataListener(  320): argv[0]=dsqncommand
D/LGDataListener(  320): argv[1]=wlan0
D/LGDataListener(  320): argv[2]=1
D/LGDataListener(  320): notifyDSQN DSQN STARTMONITOR wlan0 1
D/DSQN    ( 1029): DSQM DsqnNotification wlan0  1
,D/DSQN    ( 1029): start to monitor internet connection
D/WiFiOffLoadBroadcast( 6193): MCCMNC not supported: null
,D/QRemote ( 6359): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6359): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
D/QRemote ( 6359): [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
I/QRemote ( 6359): [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
I/QRemote ( 6359): [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1029): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Thu, 04 Feb 2016 14:47:53 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1454597273299], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1454597273280]}
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1029): Don't send network conditions - lacking user consent.
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1029): Validated
V/NetworkPolicy( 1029): [LG_RESTRICTED] checkMobilePolicy_type()
D/ConnectivityService( 1029): Validated NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService( 1029): rematching NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService( 1029):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService( 1029):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1029):     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
D/ConnectivityService( 1029): Network NetworkAgentInfo [WIFI () - 100] was already satisfying request 1. No change.
D/ConnectivityService( 1029): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService( 1029):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1029):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1029): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1029): sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1029): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
D/WIFI    ( 1029): new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    ( 1029):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityManager.CallbackHandler( 1464): CM callback handler got msg 524290
D/TelephonyNetworkFactory-1( 1861): new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/TelephonyNetworkFactory-1( 1861):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
D/PostponalbeReceiver( 5221): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,I/PCSuite ( 6280): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
D/PCSuite ( 6280): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 6193): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6193): MCCMNC not supported: null
D/LocSvc_java( 1029): NTP server : europe.pool.ntp.org
D/LocSvc_java( 1029): NTP server returned: 1454597273378 (Thu Feb 04 15:47:53 GMT+01:00 2016) reference: 125197 certainty: 24 system time offset: 51
D/LocSvc_java( 1029): Sending msg: 10 arg1:0 arg2:1
,D/LocSvc_java( 1029): reportXtraServer 
D/LocSvc_java( 1029):  server1=http://xtra3.gpsOneXTRA.net/xtra2.bin
D/LocSvc_java( 1029):  server2=http://xtra2.gpsOneXTRA.net/xtra2.bin
D/LocSvc_java( 1029):  server3=
,D/LocSvc_java( 1029): xtraDownloadRequest
D/LocSvc_java( 1029): Sending msg: 6 arg1:0 arg2:1
D/TelephonyIcons( 1464): null signal icon name: drawable/stat_sys_signal_null
D/QRemote ( 6359): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6359): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
D/QRemote ( 6359): [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
D/StatusBar.NetworkController( 1464): refreshViews: Data not connected!! Set no data type icon / Roaming
I/QRemote ( 6359): [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
D/StatusBar.NetworkController( 1464): refreshViews: Data not connected!! Set no data type icon / Roaming
I/QRemote ( 6359): [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
,D/libc-netbsd(  320): default dns: query_ipv6=0, query_ipv4=1
,D/libc-netbsd(  320): res_queryN name = xtra2.gpsOneXTRA.net, class = 1, type = 1
D/libc-netbsd(  320): res_queryN name = xtra2.gpsOneXTRA.net succeed
,D/LocSvc_java( 1029): calling native_inject_xtra_data
,D/LocSvc_java( 1029): Sending msg: 11 arg1:0 arg2:1
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-65 f=2412 sc=60 link=65 tx=0.5, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:-1396639166] gl rssi=-65 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-65 f=2412 sc=60 link=65 tx=0.5, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:8] from screen [on:0 period:-1396639158] gl rssi=-65 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
D/StatusBar.NetworkController( 1464): refreshViews: Data not connected!! Set no data type icon / Roaming
V/WifiInternetCheck( 1029): Single check msg out of sync, ignoring.
,D/ConnectivityService( 1029): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering( 1029): MasterInitialState.processMessage what=3
D/AlarmManagerService( 1029): Setting time of day to sec=1454597276
,W/AlarmManagerService( 1029): Unable to set rtc to 1454597276: Invalid argument
D/GpsLocationProvider( 1029): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,I/SecureClockService( 1958): Intent.ACTION_TIME_CHANGED 
I/[SystemUI]Clock( 1464): onReceive = android.intent.action.TIME_SET
D/LIA_Informant_Tips_DateChangeManager( 3581): onReceive() : ACTION_TIME_CHANGED
I/LIA_Informant_Tips_LogTracer( 3581): [Log Tracer - Schedule Transition] Time Change Event Received : 2016-02-04 15:47:56...... Request
I/LIA_Informant_Tips_LogTracer( 3581): [Log Tracer - Schedule Transition] UserGuide, DATE_UPDATE : working count : 8, total count : 165, new day : false...... Request
D/LIA_Informant_Tips_DateChangeManager( 3581): DateInfo : SmartTips Total Working Day Count = 165
D/LIA_Informant_Tips_DateChangeManager( 3581): DateInfo : UserGuide Working Duration Count = 8
D/LIA_Informant_Tips_DateChangeManager( 3581): DateInfo : Last Date Check Time = 2016-02-04 15:47:56
I/LgeClockWidgetControlView( 1464): time changed, timezoneChanged : false
,I/NetworkMonitor( 5289): type=WIFI subType= reason=null isConnected=true
D/KeyguardUpdateMonitor( 1464): handleTimeUpdate
,W/ActivityManager( 1029): getTasks: caller 10029 is using old GET_TASKS but privileged; allowing
I/[LGHome]LGDateChangeReceiver( 2078): [LGDateChangeReceiver.java:78:updateCalendarShortcut()]date=4 currentDate=-1 dayofweek=5 currentDayOfWeek=-1
I/[LGHome]LGCalendarIcon( 2078): [LGCalendarIcon.java:214:makeCalendarBitmap()]Locale = en_US dayofweek= Thu date= 4
,D/PostponalbeReceiver( 5221): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
W/ContextImpl( 5221): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
I/[LGHome]LGCalendarIcon( 2078): [LGCalendarIcon.java:214:makeCalendarBitmap()]Locale = en_US dayofweek= Thu date= 4
I/[LGHome]Launcher( 2078): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,D/[Concierge]Service( 2605): onStartCommand(). Type : 9
,I/GoogleURLConnFactory( 2157): Using platform SSLCertificateSocketFactory
I/ActivityManager( 1029): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=6648 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,I/ActivityManager( 1029): Start proc com.google.android.apps.books for service com.google.android.apps.books/.service.SyncService: pid=6668 uid=10054 gids={50054, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/AppUp4:AppBoxCP( 6648): onCreate
,W/AppUp4:DB( 6648):  [AppBoxDatabaseHelper] construct
,I/AppUp4:DB( 6648):  setFingerPrint start
I/AppUp4:DB( 6648):  newfinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys SDK version = 21
I/AppUp4:DB( 6648):  beforefinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys
I/AppUp4:DB( 6648):  SDK version = 21
I/AppUp4:DB( 6648):  beforefinger == newfinger no write in DB
,I/ActivityManager( 1029): Start proc com.android.gallery3d for service com.android.gallery3d/com.lge.gallery.picasa.PicasaService: pid=6686 uid=10027 gids={50027, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
D/AppUp4:AppBoxApplication( 6648): AppBoxApplication onCreate()
I/NetworkStateForAutoUpdateMonitor( 6648): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 6648): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 6648): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 6648): [onReceive] request level :IDLE....
,I/AppUp4:CustModeStarterReceiver( 6648): onReceive
,D/LgDataFeature( 6648): LgDataFeature() Constructor: none
,D/LgDataFeature( 6648): LgDataFeature() Constructor Done, null
W/ResourcesManager( 6686): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6686): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 6686): Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
W/ResourcesManager( 6686): Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
,D/AppUp4:CustFacade( 6648): Context : android.app.ReceiverRestrictedContext@1fde36af
D/AppUp4:CustFacade( 6648): isCustomizationCompleted : false
,D/AppUp4:CustFacade( 6648): isPhone : true
D/AppUp4:CustModeStarterReceiver( 6648): begin check event
I/AppUp4:CustModeStarterReceiver( 6648): Event For GoodConnectivity
D/AppUp4:CustModeStarterReceiver( 6648): runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
D/AppUp4:CustModeStarterReceiver( 6648): call method handleAsyncCustNotification.
D/AppUp4:CustModeStarterReceiver( 6648): handleAsync isTriedOnce : false
E/AppUp4:CustModeStarterReceiver( 6648): handleAsyncCustNotification do not startCustService
I/ActivityManager( 1029): Killing 5614:com.lge.lockscreensettings/u0a80 (adj 15): empty #17
,D/LGDMClient( 4005): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMClient( 4005): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
I/AppConfig( 6686): Total System Memory = 2995761152
W/libprocessgroup( 1029): failed to open /acct/uid_10080/pid_5614/cgroup.procs: No such file or directory
D/SystemHelper( 6686): region [EU], country [EU], operator [OPEN], sub-operator []
W/ContextImpl( 4005): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,I/ReaderUtils( 6668): PortraitW 1440 LandscapeW 2392 SmallestSize 1340 LargestSize 2392 textZoom 4.4999995 isTablet false Memory 256
,W/ContextImpl( 4005): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
I/ActivityManager( 1029): Start proc com.android.chrome for service com.android.chrome/com.google.android.apps.chrome.sync.ChromeBrowserSyncAdapterService: pid=6709 uid=10057 gids={50057, 9997, 3003, 1028, 1015} abi=armeabi-v7a
D/GpsLocationProvider( 1029): updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/DownloadManager( 3306): Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
,V/DownloadManager( 3306): DownloadService onCreate
I/DownloadManager( 3306): in removeSpuriousFiles
V/DownloadManager( 3306): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3306): created cursor android.database.sqlite.SQLiteCursor@b6ea8fa on behalf of 3306
I/DownloadManager( 3306): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGMyGuide_4.40.09_COM_COM_20150430011620058_RELG-D855.apk
I/DownloadManager( 3306): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGBackup_4.50.37_COM_COM_20150608234245157.apk
I/DownloadManager( 3306): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/CalendarProvider_4.2.8_COM_COM_20150304234552863_RELG-D855.apk
I/DownloadManager( 3306): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calendar_4.40.16_COM_COM_20150304234554754_RELG-D855.apk
I/DownloadManager( 3306): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.10_COM_COM_20150521235426173_RELG-D855.apk
I/DownloadManager( 3306): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQVoiceplusN_2.3.3_COM_COM_20150604065210803.apk
I/DownloadManager( 3306): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.11_COM_COM_v2_20150911144028620_RELG-D855_21.apk
I/DownloadManager( 3306): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQMemoplus(LG-D855_user)_20150902050954661.apk
I/DownloadManager( 3306): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/RemoteCall_4.1.10_COM_COM_20150817053748728.apk
I/DownloadManager( 3306): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/rspermlge(6713)_20150901080430397.apk
I/DownloadManager( 3306): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGBackup_4.51.57_COM_COM_8275_2_20151201044833536_RELG-D855_21.apk
I/DownloadManager( 3306): in trimDatabase
V/DownloadManager( 3306): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
V/DownloadManager( 3306): created cursor android.database.sqlite.SQLiteCursor@f64eab on behalf of 3306
,D/LGDMClient( 4005): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=3, isUserType=1
,I/ActivityManager( 1029): Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=6733 uid=10023 gids={50023, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
I/LGDMClient( 4005): [DmServiceProcessor.java] [processNetworkChanged()] : [91] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
D/LGDMClient( 4005): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 4005): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
E/GpsLocationProvider( 1029): No APN found to select.
,V/DownloadManager( 3306): DownloadService onStartCommand
V/DownloadManager( 3306): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3306): created cursor android.database.sqlite.SQLiteCursor@206e5ac6 on behalf of 3306
V/DownloadManager( 3306): processing inserted download 1
V/DownloadManager( 3306): processing inserted download 4
V/DownloadManager( 3306): processing inserted download 7
V/DownloadManager( 3306): processing inserted download 8
V/DownloadManager( 3306): processing inserted download 9
V/DownloadManager( 3306): processing inserted download 10
V/DownloadManager( 3306): processing inserted download 16
,V/DownloadManager( 3306): processing inserted download 17
V/DownloadManager( 3306): processing inserted download 18
V/DownloadManager( 3306): processing inserted download 21
V/DownloadManager( 3306): processing inserted download 22
W/GAV2    ( 6668): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
W/ContextImpl( 4005): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:141 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:180 android.app.IntentService$ServiceHandler.handleMessage:65 
,I/art     ( 2157): Explicit concurrent mark sweep GC freed 22989(1331KB) AllocSpace objects, 2(32KB) LOS objects, 51% free, 30MB/62MB, paused 676us total 24.113ms
,I/art     ( 1029): Explicit concurrent mark sweep GC freed 72914(3MB) AllocSpace objects, 5(120KB) LOS objects, 33% free, 43MB/65MB, paused 1.324ms total 90.191ms
,E/LGDMClient( 4005): [DmNotiService.java] [onCreate()] : [148] : DmNotiService.onCreate()
D/LGDMClient( 4005): [DmNotiService.java] [onStartCommand()] : [182] : in the new onStartCommand()
D/LGDMClient( 4005): [DmNotiService.java] [handleStart()] : [203] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
V/DownloadManager( 3306): DownloadService onDestroy
,I/BooksApp( 6668): Created application version: 3.2.35 (30235)
I/VacuumService( 2157): Vacuum at: now=1454597276988 tag=VacuumService
,W/ResourcesManager( 6733): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 6733): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,W/ResourcesManager( 6733): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
W/ResourcesManager( 6733): Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
I/BooksSync( 6668): Starting books sync
W/DriveInitializer( 2334): Background init thread started
,E/VoldCmdListener(  278): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  278): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.gms/files/
,W/Vold    (  278): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 2334): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.gms/files
I/ActivityManager( 1029): Killing 5638:com.google.android.apps.plus/u0a97 (adj 15): empty #17
I/jxcore-log( 6110): Test app app.js loaded
I/jxcore-log( 6110): 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6110): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6110): 	Automate Bluetooth MAC address resolution: true, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6110): 	Provide Bluetooth MAC address timeout in milliseconds: 40000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6110): 	Bluetooth MAC address: 58:3F:54:73:64:C0, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6110): 	Discovery mode: WIFI, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6110): 	Peer expiration time in milliseconds: 60000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6110): 	Advertise mode: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6110): 	Advertise TX power level: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6110): 	Scan mode: 1
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6110): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@255fc390 added. We now have 1 listener(s)
I/chromium( 6110): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,I/jxcore-log( 6110): BLE advertisement is not supported: Bluetooth LE advertising is not supported
I/jxcore-log( 6110): 
W/libprocessgroup( 1029): failed to open /acct/uid_10097/pid_5638/cgroup.procs: No such file or directory
,I/LGEmail ( 6733): [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
V/GLSActivity( 2157): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/LGEmail ( 6733): user build Type == true (at Util.java isUserModeBuildType 3507)[v:6.41.18]
,W/DriveInitializer( 2334): Awaiting to be initialized
,E/Auth.Api.Credentials( 2334): [CredentialSyncAdapter] Unknown sync event.
D/DelayedSyncController( 6709): Delaying sync.
W/DriveInitializer( 2334): Background init thread ended
,I/ActivityManager( 1029): Killing 5989:com.lge.eula/1000 (adj 15): empty #17
,W/ResourceType( 6733): No package identifier when getting value for resource number 0x00000000
,D/BooksSync( 6668): started syncMyEbooks
,W/libprocessgroup( 1029): failed to open /acct/uid_1000/pid_5989/cgroup.procs: No such file or directory
I/GoogleURLConnFactory( 2157): Using platform SSLCertificateSocketFactory
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-54 f=2412 sc=60 link=72 tx=29.8, 0.0, 0.0  rx=27.5 bcn=0 [on:0 tx:0 rx:0 period:3064] from screen [on:0 period:-1396636082] gl rssi=-54 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-54 f=2412 sc=60 link=72 tx=29.8, 0.0, 0.0  rx=27.5 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-1396636081] gl rssi=-54 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,W/Uploader( 2157): No account for auth token provided
D/libc-netbsd(  320): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  320): res_queryN name = play.googleapis.com, class = 1, type = 1
D/LgDataFeature( 6733): LgDataFeature() Constructor: none
,D/LgDataFeature( 6733): LgDataFeature() Constructor Done, null
D/libc-netbsd(  320): res_queryN name = play.googleapis.com succeed
,V/GLSActivity( 2157): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2157): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2157): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 2157): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2157): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2157): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/eas_req ( 6733): ---addEventToQueue() easCode=2, requestId=0 (at EasSupport.java addEventToQueue 69)
,V/NotificationService( 1029): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/libc-netbsd(  320): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  320): res_queryN name = www.google.com, class = 1, type = 1
D/ZenLog  ( 1029): intercepted: 0|com.google.android.gms|1|null|10005,none
V/NotificationService( 1029): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1029): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1029): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1029): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
W/ResourcesManager( 1464): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 1464): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,W/GLSActivity( 2157): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2157): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2157): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2157): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2157): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2157): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2157): 	at android.os.Binder.execTransact(Binder.java:446)
I/LgeMiscReceiver( 3280): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/HubEmail( 6733): JNI_OnLoad()
I/HubEmail( 6733): -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 6733): registerNatives()
I/HubEmail( 6733): -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 6733): registerNativeMethods()
I/HubEmail( 6733): -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
W/art     ( 6733): JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
W/ResourcesManager( 1410): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 1410): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
I/LgeMiscReceiver( 3280): action = android.net.conn.CONNECTIVITY_CHANGE
E/BooksAccountManager( 6668): Authentication error
E/BooksAccountManager( 6668): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6668): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6668): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6668): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6668): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6668): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6668): null auth token
I/LgeMiscReceiver( 3280): networkInfo.isConnected() = true
D/PhoneState( 3280): setPdpRejectCasuse : false
D/LgeQuickCoverNLService( 1410): onNotificationPosted
,W/Settings( 6733): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/libc-netbsd(  320): res_queryN name = www.google.com succeed
D/libc-netbsd(  320): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  320): res_queryN name = clients3.google.com, class = 1, type = 1
D/libc-netbsd(  320): res_queryN name = clients3.google.com succeed
D/libc-netbsd(  320): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  320): res_queryN name = www.googleapis.com, class = 1, type = 1
I/ActivityManager( 1029): Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=6803 uid=10062 gids={50062, 9997, 4002, 3003, 1028} abi=armeabi-v7a
D/libc-netbsd(  320): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  320): res_queryN name = static-avc.lglime.com, class = 1, type = 1
,D/SmartCoverUpdateMonitor( 1410): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1410): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1410): handleNotificationPosted(true)
D/QuickCircle( 1410): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1410): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1410): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1410): post do add job
D/LgeQuickCoverNotificationData( 1410): add : 2
D/LgeQuickCoverNotificationData( 1410): do add job
D/LgeQuickCoverNotificationData( 1410): showAll3
D/LgeQuickCoverNotificationData( 1410): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1410): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1410): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1410): showNotificationWithSetupData: display=false
,D/LgeQuickCoverOverlayWindow( 1410): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1410): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1410): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1410): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1410): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1410): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1410): updateNotificationData: count=3
W/Settings( 6733): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/libc-netbsd(  320): res_queryN name = www.googleapis.com succeed
V/WifiInternetCheck( 1029): isHttpConnectionAvailable - We got a valid response : 204
,D/QuickStatusbarLayout( 1410): Notification difference=198
D/QuickStatusbarLayout( 1410): child = android.widget.LinearLayout{6ebc377 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,D/DrmBroadcastReceiver( 6803): Receive CONNECTIVITY_ACTION
,D/DrmBroadcastReceiver( 6803): 1  network is available. Sync DRM Time with NTP
,V/DrmService( 6803): Service onCreate
D/DrmService( 6803): Received new request = 2
,I/DrmSntpClient( 6803): Start Sync process
D/DrmSntpClient( 6803): Server : 0
,D/libc-netbsd(  320): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  320): res_queryN name = pool.ntp.org, class = 1, type = 1
,I/ActivityManager( 1029): Start proc com.lge.sizechangable.weather for broadcast com.lge.sizechangable.weather/.layout.WeatherWidget: pid=6824 uid=10085 gids={50085, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager( 1029): Start proc com.google.android.apps.plus for service com.google.android.apps.plus/.service.EsSyncAdapterService: pid=6841 uid=10097 gids={50097, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,D/libc-netbsd(  320): res_queryN name = pool.ntp.org succeed
I/LGDrmClient( 6803): _DRM_ServiceGet() : Bind lgdrm service
,V/ILGDrmService(  330): eDRM_SetDRMTime +++
I/LGDRM   (  330): [DRM] SET TIME : YR=2016, MON=2, DAY=4
I/LGDRM   (  330): [DRM] SET TIME : HR=14, MIN=47, SEC=56
V/ILGDrmService(  330): eDRM_SetDRMTime ---
I/DrmSntpClient( 6803): Synched
D/DrmService( 6803): Completed !! request = 2
D/DrmService( 6803): Request count = 0
I/art     ( 6824): Almond Protected OAT
V/DrmService( 6803): Service onDestroy
I/ActivityManager( 1029): Killing 5436:com.google.android.gms.wearable/u0a5 (adj 15): empty #17
,W/ResourcesManager( 6841): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/Uploader( 2157): No account for auth token provided
W/ApiaryClient( 6668): Error response from books API: {
W/ApiaryClient( 6668):  "error": {
W/ApiaryClient( 6668):   "errors": [
W/ApiaryClient( 6668):    {
W/ApiaryClient( 6668):     "domain": "global",
W/ApiaryClient( 6668):     "reason": "required",
W/ApiaryClient( 6668):     "message": "Login Required",
W/ApiaryClient( 6668):     "locationType": "header",
W/ApiaryClient( 6668):     "location": "Authorization"
W/ApiaryClient( 6668):    }
W/ApiaryClient( 6668):   ],
W/ApiaryClient( 6668):   "code": 401,
W/ApiaryClient( 6668):   "message": "Login Required"
W/ApiaryClient( 6668):  }
W/ApiaryClient( 6668): }
,W/ApiaryClient( 6668): errCount = 1: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6668): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-7057674547180076272&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6668): Headers:
W/ApiaryClient( 6668): accept-encoding: [gzip]
W/ApiaryClient( 6668): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6668): gdata-version: 2
W/libprocessgroup( 1029): failed to open /acct/uid_10005/pid_5436/cgroup.procs: No such file or directory
D/WeatherApplication( 6824): removeAccount
,D/WeatherApplication( 6824): Account.length = 0
E/WeatherApplication( 6824): OPERATOR:OPEN
D/WeatherAncestor( 6824): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 15:47:57
D/Weather.Utils( 6824): 2 : the weather widgets(using time tick) are gone.
D/Weather.Utils( 6824): 2 : All the weather widget is gone.
D/UpdateThreadPoolManager( 6824): 2 : This is isUpdating : false
,D/WeatherAncestor( 6824): connectivity changed - connection : true
W/Uploader( 2157): No account for auth token provided
D/WeatherService( 6824): 2 : isServiceAlived():false forecastCache:null
D/ForecastDataCache( 6824): 2 : lastUpdatedTime: 1430558561343
,D/ForecastDataCache( 6824): 2 : currentPackageVersion: 4.40.4
D/ForecastDataCache( 6824): 2 : Cache is not up-to-date, count: 0
D/Weather_cast( 6824): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherAncestor( 6824): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 15:47:57
,I/ActivityManager( 1029): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=6862 uid=10093 gids={50093, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager( 1029): Killing 2205:com.lge.music/u0a34 (adj 15): empty #17
,D/libc-netbsd(  320): res_queryN name = static-avc.lglime.com succeed
,V/AudioFlinger(  325): 2205 died, releasing its sessions
V/AudioFlinger(  325):  pid 1861 @ 0
,V/AudioFlinger(  325):  pid 3280 @ 1
V/AudioFlinger(  325):  pid 3280 @ 2
W/libprocessgroup( 1029): failed to open /acct/uid_10034/pid_2205/cgroup.procs: No such file or directory
,W/Uploader( 2157):  no longer exists, so no auth token.
,V/FormManager( 6256): There are no updated forms. The schedule will be deleted.
,V/FormManager( 6256): Alarm would be updated, because LastCheckTime has been updated.
I/ActivityManager( 1029): Killing 4926:com.android.vending/u0a44 (adj 15): empty #17
,W/libprocessgroup( 1029): failed to open /acct/uid_10044/pid_4926/cgroup.procs: No such file or directory
,W/Uploader( 2157): No account for auth token provided
,E/VoldCmdListener(  278): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  278): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6862): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
,E/VoldCmdListener(  278): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  278): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6862): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
E/VoldCmdListener(  278): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  278): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6862): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
E/VoldCmdListener(  278): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  278): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6862): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
,W/Uploader( 2157): No account for auth token provided
,I/GLSActivity( 2157): [ac] getting account id
,I/GLSUser ( 2157): [t] Fetched account id for thalitester@gmail.com : 105256135866144380227
I/art     ( 1029): Explicit concurrent mark sweep GC freed 28699(1304KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 44MB/66MB, paused 1.838ms total 108.902ms
,I/WebViewFactory( 6862): Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,I/LibraryLoader( 6862): Loading: webviewchromium
I/LibraryLoader( 6862): Time to load native libraries: 3 ms (timestamps 64-67)
I/LibraryLoader( 6862): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 6862): Binding Chromium to main looper Looper (main, tid 1) {1de7c016}
I/LibraryLoader( 6862): Expected native library version number "",actual native library version number ""
,I/chromium( 6862): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 6862): Initializing chromium process, renderers=0
W/art     ( 6862): Attempt to remove local handle scope entry from IRT, ignoring
D/DelayedSyncController( 6709): Delaying sync.
,W/chromium( 6862): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
I/chromium( 6862): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=38 off=46780 len=2953
I/chromium( 6862): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:39 off:229536 len:643667
,V/AudioPolicyService(  325): registerClient() client 0xb100fe60, uid 10093
W/AudioManagerAndroid( 6862): Requires BLUETOOTH permission
I/Adreno-EGL( 6862): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 6862): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 6862): Build Date: 12/12/14 금
I/Adreno-EGL( 6862): Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
I/Adreno-EGL( 6862): Remote Branch: 
I/Adreno-EGL( 6862): Local Patches: 
I/Adreno-EGL( 6862): Reconstruct Branch: 
V/GLSActivity( 2157): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2157): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.syncadapters.contacts, service: cp
,I/GLSUser ( 2157): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> cp without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2157): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2157): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2157): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/NSApplication( 6862): Starting up...
,V/NotificationService( 1029): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1029): pkg=com.google.android.gms canInterrupt=false intercept=true
I/ActivityManager( 1029): Killing 6011:com.lge.bnr/1000 (adj 15): empty #17
W/GLSActivity( 2157): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2157): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2157): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2157): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2157): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2157): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2157): 	at android.os.Binder.execTransact(Binder.java:446)
I/NotificationServiceEx( 1029): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1029): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1029): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,W/libprocessgroup( 1029): failed to open /acct/uid_1000/pid_6011/cgroup.procs: No such file or directory
D/ContactsSyncAdapter( 2157): innerSync failed
D/ContactsSyncAdapter( 2157): com.google.wireless.gdata2.client.AuthenticationException: unable to get auth token android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
D/ContactsSyncAdapter( 2157): 	at com.google.android.syncadapters.contacts.AuthInfo.getAuthToken(AuthInfo.java:45)
D/ContactsSyncAdapter( 2157): 	at com.google.android.syncadapters.contacts.ContactsSyncAdapter.innerPerformSync(ContactsSyncAdapter.java:263)
D/ContactsSyncAdapter( 2157): 	at com.google.android.syncadapters.contacts.ContactsSyncAdapter.onPerformLoggedSync(ContactsSyncAdapter.java:168)
D/ContactsSyncAdapter( 2157): 	at com.google.android.common.LoggingThreadedSyncAdapter.onPerformSync(LoggingThreadedSyncAdapter.java:33)
D/ContactsSyncAdapter( 2157): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
D/ContactsSyncAdapter( 2157): Caused by: android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
D/ContactsSyncAdapter( 2157): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
D/ContactsSyncAdapter( 2157): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
D/ContactsSyncAdapter( 2157): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
D/ContactsSyncAdapter( 2157): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
D/ContactsSyncAdapter( 2157): 	at android.os.Binder.execTransact(Binder.java:446)
D/LgeQuickCoverNLService( 1410): onNotificationPosted
,D/SmartCoverUpdateMonitor( 1410): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1410): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1410): handleNotificationPosted(true)
D/QuickCircle( 1410): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1410): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1410): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1410): post do just update job
D/LgeQuickCoverNotificationData( 1410): showAll3
D/LgeQuickCoverNotificationData( 1410): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1410): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1410): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1410): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1410): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1410): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1410): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1410): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1410): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1410): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1410): updateNotificationData: count=3
D/SyncManager( 1029): failed sync operation thalitester@gmail.com u0 (com.google), com.android.contacts, LOCAL, currentRunTime 26700, reason: 10019, SyncResult: stats [ numAuthExceptions: 1]
,D/SyncManager( 1029): not retrying sync operation because the error is a hard error: thalitester@gmail.com u0 (com.google), com.android.contacts, LOCAL, currentRunTime 163312, reason: 10019
D/QuickStatusbarLayout( 1410): Notification difference=198
D/QuickStatusbarLayout( 1410): child = android.widget.LinearLayout{6ebc377 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
D/libc-netbsd(  320): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  320): res_queryN name = mtalk.google.com, class = 1, type = 1
,I/iu.SyncManager( 2334): SYNC; picasa accounts
,D/NetworkLogImpl( 2334): Loaded NetworkSpeedPredictor
I/iu.Environment( 2334): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,D/libc-netbsd(  320): res_queryN name = mtalk.google.com succeed
I/iu.UploadsManager( 2334): num queued entries: 0
I/iu.UploadsManager( 2334): num updated entries: 0
I/iu.SyncManager( 2334): NEXT; no task
,I/art     ( 2157): Explicit concurrent mark sweep GC freed 27515(1507KB) AllocSpace objects, 7(903KB) LOS objects, 51% free, 30MB/62MB, paused 1.850ms total 74.473ms
,D/ChimeraCfgMgr( 2334): Loading module com.google.android.gms.kids from APK com.google.android.gms
D/ChimeraCfgMgr( 2334): Loading module com.google.android.gms.kids from APK com.google.android.gms
,V/GLSActivity( 2157): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/PostponalbeReceiver( 5221): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.intent.action.TIME_SET'.
I/ActivityManager( 1029): Start proc com.lge.clock for broadcast com.lge.clock/.alarmclock.ALBootInit: pid=6951 uid=10010 gids={50010, 9997, 3003, 1028, 4002} abi=armeabi-v7a
,I/GLSUser ( 2157): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2157): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2157): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2157): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2157): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2157): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: ac2dm
I/GLSUser ( 2157): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> ac2dm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2157): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2157): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2157): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/NotificationService( 1029): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
V/NotificationService( 1029): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1029): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1029): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1029): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1029): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
V/NotificationService( 1029): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1029): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1029): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1029): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
W/Kids    ( 2334): [AccountUtils] Account not ready
W/Kids    ( 2334): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/Kids    ( 2334): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/Kids    ( 2334): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/Kids    ( 2334): 	at com.google.android.gms.auth.p.c(SourceFile:550)
W/Kids    ( 2334): 	at com.google.android.gms.auth.p.b(SourceFile:477)
W/Kids    ( 2334): 	at com.google.android.gms.kids.account.k.d(SourceFile:103)
W/Kids    ( 2334): 	at com.google.android.gms.kids.account.p.a(SourceFile:70)
W/Kids    ( 2334): 	at com.google.android.gms.kids.account.t.a(SourceFile:62)
W/Kids    ( 2334): 	at com.google.android.gms.chimera.f.run(SourceFile:179)
W/Kids    ( 2334): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Kids    ( 2334): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Kids    ( 2334): 	at java.lang.Thread.run(Thread.java:818)
,W/GLSActivity( 2157): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2157): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2157): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2157): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2157): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2157): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2157): 	at android.os.Binder.execTransact(Binder.java:446)
D/LgeQuickCoverNLService( 1410): onNotificationPosted
,D/SmartCoverUpdateMonitor( 1410): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1410): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1410): handleNotificationPosted(true)
D/QuickCircle( 1410): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1410): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1410): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1410): post do just update job
D/LgeQuickCoverNotificationData( 1410): showAll3
D/LgeQuickCoverNotificationData( 1410): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1410): showAll() ID : 1,0|com.google.android.gms|1|null|10005
,D/LgeQuickCoverNotificationData( 1410): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1410): showNotificationWithSetupData: display=false
E/BooksAccountManager( 6668): Authentication error
E/BooksAccountManager( 6668): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6668): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6668): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6668): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6668): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6668): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6668): null auth token
D/LgeQuickCoverOverlayWindow( 1410): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1410): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1410): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1410): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1410): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1410): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1410): updateNotificationData: count=3
D/LgeQuickCoverNLService( 1410): onNotificationPosted
D/GCM     ( 2157): Connected
,D/QuickStatusbarLayout( 1410): Notification difference=198
,D/QuickStatusbarLayout( 1410): child = android.widget.LinearLayout{6ebc377 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
D/SmartCoverUpdateMonitor( 1410): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1410): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1410): handleNotificationPosted(true)
D/QuickCircle( 1410): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1410): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1410): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1410): post do just update job
D/LgeQuickCoverNotificationData( 1410): showAll3
D/LgeQuickCoverNotificationData( 1410): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1410): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1410): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1410): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1410): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1410): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1410): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1410): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1410): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1410): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1410): updateNotificationData: count=3
D/ALBootInit( 6951): ====action==>android.intent.action.TIME_SET
,D/ALBootInit( 6951): Alarm ALBootInit: TIME_SET
D/Alarms  ( 6951): [setNextAlert] start
D/QuickStatusbarLayout( 1410): Notification difference=198
D/QuickStatusbarLayout( 1410): child = android.widget.LinearLayout{6ebc377 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,D/GCM     ( 2157): Message class com.google.f.a.a.p
D/Alarms  ( 6951): [setNextAlert] (1)
D/Alarms  ( 6951):  minTime  = 0
D/Alarms  ( 6951):  -- OK multi -- 0
,E/jeny.kim( 6951): [setNextAlert] setNextAlert  temp_Alarmlink + 
E/jeny.kim( 6951): [setNextAlert]setNextAlert temp_AlarmLinkText + 
W/ApiaryClient( 6668): Error response from books API: {
W/ApiaryClient( 6668):  "error": {
W/ApiaryClient( 6668):   "errors": [
W/ApiaryClient( 6668):    {
W/ApiaryClient( 6668):     "domain": "global",
W/ApiaryClient( 6668):     "reason": "required",
W/ApiaryClient( 6668):     "message": "Login Required",
W/ApiaryClient( 6668):     "locationType": "header",
W/ApiaryClient( 6668):     "location": "Authorization"
W/ApiaryClient( 6668):    }
W/ApiaryClient( 6668):   ],
W/ApiaryClient( 6668):   "code": 401,
W/ApiaryClient( 6668):   "message": "Login Required"
W/ApiaryClient( 6668):  }
W/ApiaryClient( 6668): }
W/ApiaryClient( 6668): errCount = 2: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6668): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-7057674547180076272&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6668): Headers:
W/ApiaryClient( 6668): accept-encoding: [gzip]
W/ApiaryClient( 6668): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6668): gdata-version: 2
I/CommonUtil( 6951): BUILD Country: EU
,D/Alarms  ( 6951): broadcastToWidgetProvider : false
D/Alarms  ( 6951): Enter formatDayAndTime(final Context context, long timeInMiliSec)
V/SettingsProvider( 1029): call_put(system:next_alarm_formatted=) for 0 calling package = com.lge.clock
,I/DigitalAppWidgetProvider( 6951): onReceive: android.intent.action.TIME_SET
,V/DigitalAppWidgetProvider( 6951): cancelAlarmOnQuarterHour android.app.ReceiverRestrictedContext@a0cabc
V/DigitalAppWidgetProvider( 6951): startAlarmOnQuarterHour android.app.ReceiverRestrictedContext@a0cabc
D/QuickCoverProvider( 6951): onReceiver
,I/indal   ( 1410): SmartCoverWidgetContext createApplicationContext
I/indal   ( 1410): SmartCoverWidgetContext createApplicationContext
,D/WeatherAncestor( 6824): 2 : onReceive, action: android.intent.action.TIME_SET, Time(hour:min:sec) 15:47:59
,D/Weather.Utils( 6824): 2 : the weather widgets(using time tick) are gone.
D/Weather.Utils( 6824): 2 : All the weather widget is gone.
D/UpdateThreadPoolManager( 6824): 2 : This is isUpdating : false
D/WeatherService( 6824): 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@ba3ca45
,D/ForecastDataCache( 6824): 2 : lastUpdatedTime: 1430558561343
,D/ForecastDataCache( 6824): 2 : currentPackageVersion: 4.40.4
D/ForecastDataCache( 6824): 2 : Cache is up-to-date, count: 0
D/Weather_cast( 6824): 2 : set auto-update time : 2/4 18:47
D/WeatherAncestor( 6824): 2 : onReceive has processed, action: android.intent.action.TIME_SET, Time(hour:min:sec) 15:47:59
,I/ActivityManager( 1029): Start proc com.qualcomm.timeservice for broadcast com.qualcomm.timeservice/.TimeServiceBroadcastReceiver: pid=6975 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
I/ActivityManager( 1029): Killing 6237:com.lge.lifetracker/u0a37 (adj 15): empty #17
,I/art     (  352): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 433us total 21.746ms
,I/art     (  352): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 366us total 18.221ms
,I/art     (  352): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 290us total 15.739ms
,W/libprocessgroup( 1029): failed to open /acct/uid_10037/pid_6237/cgroup.procs: No such file or directory
,D/TimeService( 6975): Receivedandroid.intent.action.TIME_SET intent. Current Time is 1454597279252
D/        ( 6975): TimeServiceNative: User Time to be set is 1454597279253
D/QC-time-services( 6975): Lib:time_genoff_operation: pargs->base = 2
D/QC-time-services( 6975): Lib:time_genoff_operation: pargs->operation = 0
D/QC-time-services( 6975): Lib:time_genoff_operation: pargs->ts_val = 1454597279253
D/QC-time-services( 6975): Lib:time_genoff_operation: Send to server  passed!!
D/QC-time-services(  406): Daemon: Connection accepted:time_genoff
D/QC-time-services(  406): Daemon:Received base = 2, unit = 1, operation = 0,value = 1454597279253
D/QC-time-services(  406): Daemon:genoff_opr: Base = 2, val = 1454597279253, operation = 0
D/QC-time-services(  406): Daemon:rtc_get: Time read from RTC -- MM/DD/YY HH:MM:SS5/14/70 8:0:5
D/QC-time-services(  406): Daemon:Value read from RTC seconds = 14198405000
D/QC-time-services(  406): Daemon:new time 1454597279253 
D/QC-time-services(  406): Daemon: delta 1440398874253 genoff 1440398874253 
D/QC-time-services(  406): Daemon:genoff_persistent_update: Writing genoff = 1440398874253 to memory
D/QC-time-services(  406): Daemon:Opening File: /data/time/ats_2
D/QC-time-services(  406): Daemon:time_persistent_memory_opr:Genoff write operation 
,D/QC-time-services(  406): Updating the TOD offset
,D/QC-time-services(  406): Daemon:genoff_persistent_update: Writing genoff = 1440398874253 to memory
D/QC-time-services(  406): Daemon:Opening File: /data/time/ats_1
,D/QC-time-services(  406): Daemon:time_persistent_memory_opr:Genoff write operation 
E/QC-time-services(  406): Daemon:Update to modem bit set
D/QC-time-services(  406): Daemon:genoff_send_modem: Sending data to MODEM !
D/QC-time-services(  406): Daemon: Base = 2, Value being sent to MODEM = 1124434074253
E/QC-time-services( 6975): Receive Passed == base = 2, unit = 1, operation = 0, result = 0
,E/QC-time-services(  406): Daemon:tod_update_ind_cb: Got Update from modem msg_id 40
,E/QC-time-services(  406): Daemon: Time-services: Waiting to acceptconnection
I/ActivityManager( 1029): Start proc com.android.calendar for broadcast com.android.calendar/.widget.CalendarAppWidgetProvider: pid=6993 uid=10013 gids={50013, 9997, 3003, 1028, 1015} abi=armeabi
I/ActivityManager( 1029): Killing 6319:com.lge.settings.easy/1000 (adj 15): empty #17
,W/libprocessgroup( 1029): failed to open /acct/uid_1000/pid_6319/cgroup.procs: No such file or directory
,W/ResourcesManager( 6993): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,D/CalendarApplication( 6993): CalendarApplication.onCreate()
,D/PreferenceKeysParser( 6993): [debug_displayParseInfos] preference keys.size() = 44
,D/PreferenceKeysParser( 6993): [debug_displayParseInfos] preference keys = {lg_preferences_tardis_1=com.android.calendar.adaptation.PreferenceKey$KeyData@bcf6853, lg_preferences_hide_declined=com.android.calendar.adaptation.PreferenceKey$KeyData@3c4ae590, lg_preferences_default_reminder=com.android.calendar.adaptation.PreferenceKey$KeyData@1b35ce89, lg_preferences_month_view_style=com.android.calendar.adaptation.PreferenceKey$KeyData@1ccde8e, lg_preferences_alerts_ringtone=com.android.calendar.adaptation.PreferenceKey$KeyData@1fde36af, lg_preferences_device_tz=com.android.calendar.adaptation.PreferenceKey$KeyData@a0cabc, lg_preferences_debug_datesearch=com.android.calendar.adaptation.PreferenceKey$KeyData@ba3ca45, lg_preferences_debug_country=com.android.calendar.adaptation.PreferenceKey$KeyData@12bc559a, lg_preferences_display_weather_information=com.android.calendar.adaptation.PreferenceKey$KeyData@2b618ecb, lg_preferences_alerts_vibrateWhen=com.android.calendar.adaptation.PreferenceKey$KeyData@2e0dd6a8, lg_preferences_debug_rtl=com.android.calendar.adaptation.PreferenceKey$KeyData@13bc5c1, lg_preferences_alerts_type=com.android.calendar.adaptation.PreferenceKey$KeyData@30fa3166, lg_preferrences_country_code=com.android.calendar.adaptation.PreferenceKey$KeyData@30784ca7, lg_preferences_weather_info=com.android.calendar.adaptation.PreferenceKey$KeyData@3abdb554, lg_preference_holiday_calendar_ver=com.android.calendar.adaptation.PreferenceKey$KeyData@22fdfcfd, lg_preferences_show_controls=com.android.calendar.adaptation.PreferenceKey$KeyData@31e7fdf2, lg_preferences_user_select_noti_sound=com.android.calendar.adaptation.PreferenceKey$KeyData@a530c43, lg_preference_default_myphonebook=com.android.calendar.adaptation.PreferenceKey$KeyData@31ead2c0, lg_preferences_skip_setup=com.android.calendar.adaptation.PreferenceKey$KeyData@db26bf9, lg_preferred_startView=com.android.calendar.adaptation.PreferenceKey$KeyData@2d74073e, lg_preferences_debug_operator=com.android.calendar.adaptation.PreferenceKey$KeyData@c90299f, lg_preferences_exclude_sticker_list=com.android.calendar.adaptation.PreferenceKey$KeyData@160a5aec, lg_preferences_writable_calendars_count=com.android.calendar.adaptation.PreferenceKey$KeyData@8a4ceb5, lg_preferred_detailedView=com.android.calendar.adaptation.PreferenceKey$KeyData@3a25594a, lg_preferences_debug_floating=com.android.calendar.adaptation.PreferenceKey$KeyData@3c57c0bb, lg_preferences_home_tz=com.android.calendar.adaptation.PreferenceKey$KeyData@39b839d8, lg_preferences_home_tz_enabled=com.android.calendar.adaptation.PreferenceKey$KeyData@a20a131, lg_preference_received_provider_reminder_broadcast=com.android.calendar.adaptation.PreferenceKey$KeyData@1de7c016, lg_preferences_default_cell_height=com.android.calendar.adaptation.PreferenceKey$KeyData@3f37ad97, lg_preferences_notification_type=com.android.calendar.adaptation.PreferenceKey$KeyData@3b631b84, lg_preferences_show_week_num=com.android.calendar.adaptation.PreferenceKey$KeyData@7ad1f6d, lg_preferences_dont_show_again_no_online_account=com.android.calendar.adaptation.PreferenceKey$KeyData@3f97c7a2, lg_preferences_alerts_popup=com.android.calendar.adaptation.PreferenceKey$KeyData@1bbf8c33, lg_preferences_week_start_day=com.android.calendar.adaptation.PreferenceKey$KeyData@fb86bf0, lg_preferences_app_version=com.android.calendar.adaptation.PreferenceKey$KeyData@e094569, lg_preferences_alerts=com.android.calendar.adaptation.PreferenceKey$KeyData@254ebbee, lg_preferences_select_aux_calendar=com.android.calendar.adaptation.PreferenceKey$KeyData@27dcb88f, lg_preferences_widget_info_calendars=com.android.calendar.adaptation.PreferenceKey$KeyData@6d0571c, lg_preferences_alerts_default_ringtone=com.android.calendar.adaptation.PreferenceKey$KeyData@1ce7cf25, lg_preference_defaultCalendar=com.android.calendar.adaptation.PreferenceKey$KeyData@b6ea8fa, lg_preferences_alerts_vibratetype=com.android.calendar.adaptation.PreferenceKey$KeyData@f64eab, lg_preferences_recent_timezones=com.android.calendar.adaptation.PreferenceKey$KeyData@3819c908, lg_pre
D/GeneralP,referenceUtils( 6993): [migratePrefrenceKeys] Exit: Version(44001600) >= 42001300
D/Config  ( 6993): [init]
I/Config  ( 6993): LGCalendar ver.4.40.16
I/Config  ( 6993): start check model
I/Config  ( 6993): start check native_ca
I/Config  ( 6993): Config Operator=OPEN, Country=EU
D/Config  ( 6993): [setDefaultValuesToPref]
D/Config  ( 6993): [parseProfiles]
D/ProfilesParser( 6993): [debug_displayParseInfos] profile.country = null
D/ProfilesParser( 6993): [debug_displayParseInfos] profile.operator = null
D/Config  ( 6993): [updateProfiletoCountryInfo]
D/GeneralPreference( 6993): [checkAndMigrateOldPreference]
E/AgendaWidgetManager( 6993): [updateWidgets] 
,I/InitNotificationRingtoneService( 6993): Start InitializeAlertRingtoneService.onHandleIntent
,I/AlertUtils( 6993): [setFormatNotificationSound] current noti URI = content://media/internal/audio/media/41
I/AlertUtils( 6993): [getCalendarNotiSoundURIFromCursor] getCount()= 21
,I/AlertUtils( 6993): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Arpeggio.ogg
I/AlertUtils( 6993): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Country_Blues.ogg
,I/AlertUtils( 6993): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Crystal.ogg
I/AlertUtils( 6993): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Dewdrop.ogg
,I/AlertUtils( 6993): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Ding_Dong.ogg
I/AlertUtils( 6993): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Echo.ogg
,I/AlertUtils( 6993): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Email.ogg
I/AlertUtils( 6993): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Game_Over.ogg
I/AlertUtils( 6993): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Gayageum.ogg
,I/AlertUtils( 6993): [getMediaFilepathFromContentUri] filepath = /system/media/audio/alarms/Afternoon_Walk.ogg
I/AlertUtils( 6993): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Harmonics.ogg
I/AlertUtils( 6993): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Idea.ogg
,I/AlertUtils( 6993): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/News.ogg
I/AlertUtils( 6993): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Pebble.ogg
I/AlertUtils( 6993): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Schedule.ogg
I/AlertUtils( 6993): [getCalendarNotiSoundURIFromCursor] filePath = /system/media/audio/notifications/Schedule.ogg, new URI = content://media/internal/audio/media/41
,I/AlertUtils( 6993): set default noti to content://media/internal/audio/media/41
I/InitNotificationRingtoneService( 6993): End InitializeAlertRingtoneService.onHandleIntent
D/MonthWidgetProvider( 6993): [onReceive]
D/CalendarWidgetProvider( 6993): [onReceive]
D/CalendarWidgetProvider( 6993): [CalendarWidgetProvider] got the intent: Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.android.calendar/.widget.MonthWidgetProvider }
,W/HolidayIntentService( 6993): onHandleIntent
D/HolidayDataLoader( 6993): readJsonAsset : holiday.json
D/CalendarTypeController( 6993): [onUpdateAndInitCalendarTime]
D/WeekWidgetProvider( 6993): [onReceive]
D/CalendarWidgetProvider( 6993): [onReceive]
,D/CalendarWidgetProvider( 6993): [CalendarWidgetProvider] got the intent: Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.android.calendar/.widget.WeekWidgetProvider }
D/CalendarTypeController( 6993): [onUpdateAndInitCalendarTime]
E/HolidayIntentService( 6993): onHandleIntent:holiday data empty
,I/ActivityManager( 1029): Killing 6536:com.google.android.talk/u0a72 (adj 15): empty #17
W/libprocessgroup( 1029): failed to open /acct/uid_10072/pid_6536/cgroup.procs: No such file or directory
,I/ActivityManager( 1029): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.realtimechat.RequestWriter$NetworkStateReceiver: pid=7020 uid=10072 gids={50072, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,V/GLSActivity( 2157): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2157): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2157): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2157): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2157): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
D/PowerManagerServiceEx( 1029): acquireWakeLockInternal: lock=811726971, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1029
,I/ActivityManager( 1029): Start proc com.android.vending for service com.android.vending/com.google.android.finsky.services.ContentSyncService: pid=7037 uid=10044 gids={50044, 9997, 3003, 1028, 1015} abi=armeabi-v7a
V/AlarmManager( 1029): RTC_WAKEUP set : Alarm{15abf40b type 0 when 1454597280050 com.android.vending} when 1454597280050
,I/[SystemUI]TimeTickManager( 1464): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1464): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1464): called onTimeUpdated()
I/[SystemUI]Clock( 1464): called onTimeUpdated()
I/LgeClockWidgetControlView( 1464): called onTimeUpdated()
I/[SystemUI]DateView( 1464): called onTimeUpdated()
I/[SystemUI]DateView( 1464): called onTimeUpdated()
,D/KeyguardUpdateMonitor( 1464): handleTimeUpdate
I/art     ( 1029): Explicit concurrent mark sweep GC freed 26377(1166KB) AllocSpace objects, 4(448KB) LOS objects, 33% free, 43MB/65MB, paused 3.328ms total 172.408ms
,V/GLSActivity( 2157): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/[Concierge]Service( 2605): onStartCommand(). Type : 9
,W/ResourcesManager( 7020): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,V/NotificationService( 1029): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
V/NotificationService( 1029): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1029): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1029): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1029): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,W/GLSActivity( 2157): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2157): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2157): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2157): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2157): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2157): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2157): 	at android.os.Binder.execTransact(Binder.java:446)
,D/PowerManagerServiceEx( 1029): releaseWakeLockInternal: lock=811726971 [*alarm*], flags=0x0
D/LgeQuickCoverNLService( 1410): onNotificationPosted
E/BooksAccountManager( 6668): Authentication error
E/BooksAccountManager( 6668): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6668): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6668): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6668): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6668): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6668): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6668): null auth token
E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-54 f=2412 sc=60 link=72 tx=16.4, 0.0, 0.0  rx=14.8 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:-1396633070] gl rssi=-54 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-54 f=2412 sc=60 link=72 tx=16.4, 0.0, 0.0  rx=14.8 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-1396633069] gl rssi=-54 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
D/SmartCoverUpdateMonitor( 1410): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1410): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1410): handleNotificationPosted(true)
D/QuickCircle( 1410): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1410): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1410): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1410): post do just update job
D/LgeQuickCoverNotificationData( 1410): showAll3
D/LgeQuickCoverNotificationData( 1410): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1410): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1410): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1410): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1410): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1410): isNotificationForCurrentUser : true
,D/LgeQuickCoverOverlayWindow( 1410): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1410): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1410): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1410): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1410): updateNotificationData: count=3
D/QuickStatusbarLayout( 1410): Notification difference=198
,D/QuickStatusbarLayout( 1410): child = android.widget.LinearLayout{6ebc377 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
D/StatusBar.NetworkController( 1464): refreshViews: Data not connected!! Set no data type icon / Roaming
W/ApiaryClient( 6668): Error response from books API: {
W/ApiaryClient( 6668):  "error": {
W/ApiaryClient( 6668):   "errors": [
W/ApiaryClient( 6668):    {
W/ApiaryClient( 6668):     "domain": "global",
W/ApiaryClient( 6668):     "reason": "required",
W/ApiaryClient( 6668):     "message": "Login Required",
W/ApiaryClient( 6668):     "locationType": "header",
W/ApiaryClient( 6668):     "location": "Authorization"
W/ApiaryClient( 6668):    }
W/ApiaryClient( 6668):   ],
W/ApiaryClient( 6668):   "code": 401,
W/ApiaryClient( 6668):   "message": "Login Required"
W/ApiaryClient( 6668):  }
W/ApiaryClient( 6668): }
,W/ApiaryClient( 6668): errCount = 3: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6668): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-7057674547180076272&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6668): Headers:
W/ApiaryClient( 6668): accept-encoding: [gzip]
W/ApiaryClient( 6668): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6668): gdata-version: 2
D/LgDataFeature( 7020): LgDataFeature() Constructor: none
D/LgDataFeature( 7020): LgDataFeature() Constructor Done, null
,D/Finsky  ( 7037): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
D/LgDataFeature( 7037): LgDataFeature() Constructor: none
D/LgDataFeature( 7037): LgDataFeature() Constructor Done, null
,I/Babel   ( 7020): MmsConfig: mnc/mcc: 0/0
I/Babel   ( 7020): MmsConfig.loadMmsSettings
,I/Babel   ( 7020): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D855 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D855-M3-D1.xml
I/Babel   ( 7020): MmsConfig.loadFromDatabase
,E/Babel   ( 7020): canonicalizeMccMnc: invalid mccmnc 
I/Babel   ( 7020): MmsConfig.loadFromResources
E/Babel   ( 7020): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel   ( 7020): MmsConfig.loadMmsSettings: mUserAgent=LG-D855 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D855-M3-D1.xml
,W/AudioCapabilities( 7020): Unsupported mime audio/evrc
W/Settings( 7020): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/AudioCapabilities( 7020): Unsupported mime audio/qcelp
W/VideoCapabilities( 7020): Unrecognized profile 2130706433 for video/avc
,D/Finsky  ( 7037): [1] DailyHygiene.goMakeHygieneIfDirty: Dirty, need more hygiene.
,W/AudioCapabilities( 7020): Unsupported mime audio/amr-wb-plus
,W/AudioCapabilities( 7020): Unsupported mime audio/qcelp
,W/AudioCapabilities( 7020): Unsupported mime audio/evrc
I/DigitalAppWidgetProvider( 6951): onReceive: android.intent.action.ALARM_CHANGED
D/WeatherAncestor( 6824): 2 : onReceive, action: com.lge.sizechangable.weather.action.setweathercast, Time(hour:min:sec) 15:48:0
D/Weather.Utils( 6824): 2 : the weather widgets(using time tick) are gone.
D/Weather.Utils( 6824): 2 : All the weather widget is gone.
D/UpdateThreadPoolManager( 6824): 2 : This is isUpdating : false
,W/VideoCapabilities( 7020): Unsupported mime video/x-ms-wmv
W/VideoCapabilities( 7020): Unsupported mime video/divx
W/VideoCapabilities( 7020): Unsupported mime video/divx311
W/VideoCapabilities( 7020): Unsupported mime video/divx4
,W/VideoCapabilities( 7020): Unsupported mime video/mp4v-esdp
W/ResourcesManager( 7020): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 7020): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
I/VideoCapabilities( 7020): Unsupported profile 4 for video/mp4v-es
,I/ActivityManager( 1029): Start proc com.google.android.gms:car for service com.google.android.gms/.car.CarService: pid=7091 uid=10005 gids={50005, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
,D/Weather_cast( 6824): 2 : Update is Canceled by com.lge.sizechangable.weather.action.alarm
D/WeatherAncestor( 6824): 2 : onReceive has processed, action: com.lge.sizechangable.weather.action.setweathercast, Time(hour:min:sec) 15:48:0
W/AudioCapabilities( 7020): Unsupported mime audio/eac3
W/AudioCapabilities( 7020): Unsupported mime audio/ac3
W/AudioCapabilities( 7020): Unsupported mime audio/g726
W/AudioCapabilities( 7020): Unsupported mime audio/wma-voice
,W/Settings( 7037): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
W/AudioCapabilities( 7020): Unsupported mime audio/x-ms-wma
W/Settings( 7037): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
W/AudioCapabilities( 7020): Unsupported mime audio/adpcm
W/VideoCapabilities( 7020): Unsupported mime video/theora
W/VideoCapabilities( 7020): Unsupported mime video/mjpg
,V/DownloadManager( 3306): starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; selection is null; selectionArgs is null; sort is null.
W/ResourcesManager( 7091): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 7091): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
V/DownloadManager( 3306): created cursor android.database.sqlite.SQLiteCursor@1066db4 on behalf of 7037
,D/Finsky  ( 7037): [1] 2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 7037): [1] 2.run: Finished loading 1 libraries.
,D/Finsky  ( 7037): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,I/MultiDex( 7091): VM with version 2.1.0 has multidex support
I/MultiDex( 7091): install
I/MultiDex( 7091): VM has multidex support, MultiDex support library is disabled.
V/JNIHelp ( 7020): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,D/Finsky  ( 7037): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
V/JNIHelp ( 7091): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
W/ActivityThread( 7091): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 7091): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@b558438: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 7091): Installed default security provider GmsCore_OpenSSL
D/GCM     ( 2157): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,D/AuthorizationBluetoothService( 2157): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
V/GmsCoreStatsServiceLauncher( 2334): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
V/SIM_STK ( 1029): Menu title from STK is T-Mobile
,W/System  ( 7020): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/system/framework/com.google.android.media.effects.jar", zip file "/system/app/Hangouts/Hangouts.apk"],nativeLibraryDirectories=[/system/app/Hangouts/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,I/ProviderInstaller( 7020): Installed default security provider GmsCore_OpenSSL
I/ActivityManager( 1029): Start proc com.google.android.gms.wearable for service com.google.android.gms/.wearable.service.WearableService: pid=7118 uid=10005 gids={50005, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
,D/LocationInitializer( 2334): Restart initialization of location
,W/ResourcesManager( 7118): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 7118): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
I/MultiDex( 7118): VM with version 2.1.0 has multidex support
I/MultiDex( 7118): install
,I/MultiDex( 7118): VM has multidex support, MultiDex support library is disabled.
I/art     ( 2334): Explicit concurrent mark sweep GC freed 17907(1296KB) AllocSpace objects, 19(304KB) LOS objects, 49% free, 32MB/64MB, paused 801us total 36.747ms
V/JNIHelp ( 7118): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,W/ActivityThread( 7118): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 7118): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@b558438: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 7118): Installed default security provider GmsCore_OpenSSL
,D/WearableService( 7118): callingUid 10005, callindPid: 7118
V/Finsky  ( 7037): [1] GearheadStateMonitor.onReady: sIsProjecting:false
,E/MDM     ( 1826): [86] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,D/AuthorizationBluetoothService( 2157): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
D/GCM     ( 2157): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
V/GmsCoreStatsServiceLauncher( 2334): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,I/GLSUser ( 2157): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.talk, service: oauth2:https://www.googleapis.com/auth/chat https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/hangouts https://www.googleapis.com/auth/identity.plus.page.impersonation https://www.googleapis.com/auth/chat.native
I/GLSUser ( 2157): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/chat https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/hangouts https://www.googleapis.com/auth/identity.plus.page.impersonation https://www.googleapis.com/auth/chat.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 2157): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2157): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2157): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
E/MDM     ( 1826): [87] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
D/LocationInitializer( 2334): Restart initialization of location
,E/Babel   ( 7020): UserRecoverableAuthException.
E/Babel   ( 7020): cfq: BadAuthentication
E/Babel   ( 7020): 	at cfn.a(Unknown Source)
E/Babel   ( 7020): 	at f.a(PG:191)
E/Babel   ( 7020): 	at ava.a(PG:88)
E/Babel   ( 7020): 	at ava.a(PG:128)
E/Babel   ( 7020): 	at bjs.a(PG:255)
E/Babel   ( 7020): 	at bep.a(PG:602)
E/Babel   ( 7020): 	at bep.a(PG:469)
E/Babel   ( 7020): 	at bpo.run(PG:1141)
E/Babel   ( 7020): Error getting auth token
E/Babel   ( 7020): bxl
E/Babel   ( 7020): 	at f.a(PG:201)
E/Babel   ( 7020): 	at ava.a(PG:88)
E/Babel   ( 7020): 	at ava.a(PG:128)
E/Babel   ( 7020): 	at bjs.a(PG:255)
E/Babel   ( 7020): 	at bep.a(PG:602)
E/Babel   ( 7020): 	at bep.a(PG:469)
E/Babel   ( 7020): 	at bpo.run(PG:1141)
I/Babel_RequestWriter( 7020): error sending REQ[fc:8; creat:1454594343454; type:bev-921425530]; took 191 ms (error code == 100)
E/Babel   ( 7020): Account registration failedRedacted-21
E/Babel   ( 7020): bph: null -- null
E/Babel   ( 7020): 	at ava.a(PG:120)
E/Babel   ( 7020): 	at ava.a(PG:128)
E/Babel   ( 7020): 	at bjs.a(PG:255)
E/Babel   ( 7020): 	at bep.a(PG:602)
E/Babel   ( 7020): 	at bep.a(PG:469)
E/Babel   ( 7020): 	at bpo.run(PG:1141)
I/Babel   ( 7020): Account setup failed with error state:106 account:Redacted-21
I/Babel   ( 7020): Account sign in complete with state 106account: Redacted-21
,I/art     ( 7020): Note: end time exceeds epoch: 
,V/GLSActivity( 2157): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2157): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.talk, service: oauth2:https://www.googleapis.com/auth/chat https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/hangouts https://www.googleapis.com/auth/identity.plus.page.impersonation https://www.googleapis.com/auth/chat.native
,I/GLSUser ( 2157): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/chat https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/hangouts https://www.googleapis.com/auth/identity.plus.page.impersonation https://www.googleapis.com/auth/chat.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2157): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2157): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2157): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/GLSUser ( 2157): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 2157): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2157): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2157): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2157): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ResourcesManager( 2157): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,D/Finsky  ( 7037): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 7037): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 7037): [1] 5.onFinished: Scheduling replication attempt 2.
I/ActivityManager( 1029): Killing 5934:com.uei.lg.quicksetsdk.maxq616/1000 (adj 15): empty #17
,V/NotificationService( 1029): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
V/NotificationService( 1029): pkg=com.google.android.gms canInterrupt=false intercept=true
E/BooksSync( 6668): Soft error: 
E/BooksSync( 6668): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 6668): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-7057674547180076272&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 6668): Headers:
E/BooksSync( 6668): accept-encoding: [gzip]
E/BooksSync( 6668): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 6668): gdata-version: 2
E/BooksSync( 6668): 
E/BooksSync( 6668): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 6668): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 6668): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 6668): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 6668): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 6668): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 6668): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 6668): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 6668): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 6668): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 6668): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 6668): {
E/BooksSync( 6668):  "error": {
E/BooksSync( 6668):   "errors": [
E/BooksSync( 6668):    {
E/BooksSync( 6668):     "domain": "global",
E/BooksSync( 6668):     "reason": "required",
E/BooksSync( 6668):     "message": "Login Required",
E/BooksSync( 6668):     "locationType": "header",
E/BooksSync( 6668):     "location": "Authorization"
E/BooksSync( 6668):    }
E/BooksSync( 6668):   ],
E/BooksSync( 6668):   "code": 401,
E/BooksSync( 6668):   "message": "Login Required"
E/BooksSync( 6668):  }
E/BooksSync( 6668): }
E/BooksSync( 6668): 
E/BooksSync( 6668): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 6668): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 6668): 	... 8 more
E/BooksSync( 6668): Sync error
E/BooksSync( 6668): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 6668): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-7057674547180076272&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 6668): Headers:
E/BooksSync( 6668): accept-encoding: [gzip]
E/BooksSync( 6668): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 6668): gdata-version: 2
E/BooksSync( 6668): 
E/BooksSync( 6668): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 6668): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 6668): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/Bo,oksSync( 6668): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 6668): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 6668): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 6668): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 6668): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 6668): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 6668): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 6668): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 6668): {
E/BooksSync( 6668):  "error": {
E/BooksSync( 6668):   "errors": [
E/BooksSync( 6668):    {
E/BooksSync( 6668):     "domain": "global",
E/BooksSync( 6668):     "reason": "required",
E/BooksSync( 6668):     "message": "Login Required",
E/BooksSync( 6668):     "locationType": "header",
E/BooksSync( 6668):     "location": "Authorization"
E/BooksSync( 6668):    }
E/BooksSync( 6668):   ],
E/BooksSync( 6668):   "code": 401,
E/BooksSync( 6668):   "message": "Login Required"
E/BooksSync( 6668):  }
E/BooksSync( 6668): }
E/BooksSync( 6668): 
E/BooksSync( 6668): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 6668): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 6668): 	... 8 more
I/BooksSync( 6668): Finished books sync
I/QRemote ( 6359): [RemoteControlManager.java:195:onServiceDisconnected()] oooooo start
W/System.err( 6359): android.os.DeadObjectException
,W/System.err( 6359): 	at android.os.BinderProxy.transactNative(Native Method)
,W/System.err( 6359): 	at android.os.BinderProxy.transact(Binder.java:496)
W/System.err( 6359): 	at com.uei.control.IControl.unregisterCallback(IControl.java:502)
W/System.err( 6359): 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:199)
W/System.err( 6359): 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
W/System.err( 6359): 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
W/System.err( 6359): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 6359): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 6359): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 6359): 	at android.app.ActivityThread.main(ActivityThread.java:5274)
W/System.err( 6359): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 6359): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 6359): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
W/System.err( 6359): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
E/UEI.SmartControl( 6359): IControl.unregisterCallback error: android.os.DeadObjectException
W/System.err( 6359): android.os.DeadObjectException
W/System.err( 6359): 	at android.os.BinderProxy.transactNative(Native Method)
W/System.err( 6359): 	at android.os.BinderProxy.transact(Binder.java:496)
W/System.err( 6359): 	at com.uei.control.IControl.unregisterSetupReadyCallback(IControl.java:818)
W/System.err( 6359): 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:200)
,W/System.err( 6359): 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
W/System.err( 6359): 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
W/System.err( 6359): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 6359): 	at android.os.Handler.dispatchMessage(Handler.java:95)
,W/System.err( 6359): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 6359): 	at android.app.ActivityThread.main(ActivityThread.java:5274)
W/System.err( 6359): 	at java.lang.reflect.Method.invoke(Native Method)
,W/System.err( 6359): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 6359): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
W/System.err( 6359): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
E/UEI.SmartControl( 6359): IControl.unregisterSetupReadyCallback error: android.os.DeadObjectException
,I/QRemote ( 6359): [RemoteControlManager.java:203:onServiceDisconnected()] oooooo Control unbind before rebinding.
I/ActivityManager( 1029): Killing 6280:com.lge.sync/1000 (adj 15): empty #18
,I/NotificationServiceEx( 1029): LED remove() : mLights=0|com.google.android.gms|1|null|10005
,D/NotificationServiceEx( 1029): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1029): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
E/Babel   ( 7020): Unexpected exception while authenticating.
E/Babel   ( 7020): cfr: User intervention required. Notification has been pushed.
E/Babel   ( 7020): 	at cfn.b(Unknown Source)
E/Babel   ( 7020): 	at cfn.a(Unknown Source)
E/Babel   ( 7020): 	at f.a(PG:188)
E/Babel   ( 7020): 	at ava.b(PG:143)
E/Babel   ( 7020): 	at bnr.run(PG:5415)
E/Babel   ( 7020): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/Babel   ( 7020): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/Babel   ( 7020): 	at java.lang.Thread.run(Thread.java:818)
,W/libprocessgroup( 1029): failed to open /acct/uid_1000/pid_5934/cgroup.procs: No such file or directory
W/ActivityManager( 1029): Scheduling restart of crashed service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service in 1000ms
D/LgeQuickCoverNLService( 1410): onNotificationPosted
D/SyncManager( 1029): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 26666, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
W/libprocessgroup( 1029): failed to open /acct/uid_1000/pid_6280/cgroup.procs: No such file or directory
D/QRemote ( 6359): [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]10
I/QRemote ( 6359): [RemoteControlManager.java:157:onBindIRService()] oooooo bind
,I/ActivityManager( 1029): Killing 6193:com.android.settings/1000 (adj 15): empty #17
,D/WifiService( 1029): Client connection lost with reason: 4
,I/ActivityManager( 1029): Start proc com.uei.lg.quicksetsdk.maxq616 for service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service: pid=7150 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,D/QRemote ( 6359): [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
D/SmartCoverUpdateMonitor( 1410): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1410): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1410): handleNotificationPosted(true)
D/QuickCircle( 1410): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1410): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1410): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1410): post do just update job
D/LgeQuickCoverNotificationData( 1410): showAll3
D/LgeQuickCoverNotificationData( 1410): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1410): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1410): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1410): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1410): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1410): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1410): [native noti] inex =  1
W/libprocessgroup( 1029): failed to open /acct/uid_1000/pid_6193/cgroup.procs: No such file or directory
V/AlarmManager( 1029): RTC_WAKEUP set : Alarm{2a013654 type 0 when 1454597281600 com.android.vending} when 1454597281600
D/Finsky  ( 7037): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
D/LgeQuickCoverNotificationData( 1410): isNotificationForCurrentUser : true
,D/LgeQuickCoverOverlayWindow( 1410): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1410): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1410): updateNotificationData: count=3
D/QuickStatusbarLayout( 1410): Notification difference=198
D/QuickStatusbarLayout( 1410): child = android.widget.LinearLayout{6ebc377 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
V/GLSActivity( 2157): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2157): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 2157): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2157): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2157): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2157): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/Finsky  ( 7037): [1] 1.onErrorResponse: Unable to preload experiments: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,V/GLSActivity( 2157): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/UEI.SmartControl( 7150): Quickset Services start...
,I/UEI.SmartControl( 7150): Manufacture = LGE
D/UEI.SmartControl( 7150): Id = LGNevo
D/UEI.SmartControl( 7150): File observer start...
E/UEI.SmartControl( 7150): IR Port is disabled: false
D/UEI.SmartControl( 7150): Starting file observer...
D/UEI.SmartControl( 7150): Extracting JNI libs...
D/UEI.SmartControl( 7150): --- this system supports 32-bit or 64-bit only
I/GLSUser ( 2157): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 2157): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2157): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2157): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2157): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/GLSUser ( 2157): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.syncadapters.contacts, service: cp
,I/GLSUser ( 2157): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> cp without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2157): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2157): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2157): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/GAV2    ( 6668): Thread[GAThread,5,main]: No campaign data found.
V/NotificationService( 1029): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1029): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1029): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1029): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1029): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
W/GLSActivity( 2157): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2157): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2157): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2157): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2157): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2157): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2157): 	at android.os.Binder.execTransact(Binder.java:446)
D/ContactsSyncAdapter( 2157): innerSync failed
D/ContactsSyncAdapter( 2157): com.google.wireless.gdata2.client.AuthenticationException: unable to get auth token android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
D/ContactsSyncAdapter( 2157): 	at com.google.android.syncadapters.contacts.AuthInfo.getAuthToken(AuthInfo.java:45)
D/ContactsSyncAdapter( 2157): 	at com.google.android.syncadapters.contacts.ContactsSyncAdapter.innerPerformSync(ContactsSyncAdapter.java:263)
D/ContactsSyncAdapter( 2157): 	at com.google.android.syncadapters.contacts.ContactsSyncAdapter.onPerformLoggedSync(ContactsSyncAdapter.java:168)
D/ContactsSyncAdapter( 2157): 	at com.google.android.common.LoggingThreadedSyncAdapter.onPerformSync(LoggingThreadedSyncAdapter.java:33)
D/ContactsSyncAdapter( 2157): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
D/ContactsSyncAdapter( 2157): Caused by: android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
D/ContactsSyncAdapter( 2157): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
D/ContactsSyncAdapter( 2157): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
D/ContactsSyncAdapter( 2157): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
D/ContactsSyncAdapter( 2157): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
D/ContactsSyncAdapter( 2157): 	at android.os.Binder.execTransact(Binder.java:446)
,D/LgeQuickCoverNLService( 1410): onNotificationPosted
D/SmartCoverUpdateMonitor( 1410): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1410): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1410): handleNotificationPosted(true)
D/QuickCircle( 1410): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1410): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1410): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1410): post do just update job
D/LgeQuickCoverNotificationData( 1410): showAll3
D/LgeQuickCoverNotificationData( 1410): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1410): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1410): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1410): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1410): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1410): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1410): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1410): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1410): [native noti] inex =  2
D/UEI.SmartControl( 7150): --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
D/UEI.SmartControl( 7150): --- Checking lib: libqs_armeabi-v7a.zip
D/UEI.SmartControl( 7150): --- Extracting JNI libs: libqs_armeabi-v7a.zip
,D/LgeQuickCoverNotificationData( 1410): isNotificationForCurrentUser : true
D/SyncManager( 1029): failed sync operation thalitester@gmail.com u0 (com.google), com.android.contacts, LOCAL, currentRunTime 163312, reason: 10019, SyncResult: stats [ numAuthExceptions: 1]
E/LgeQuickCoverOverlayWindow( 1410): updateNotificationData: count=3
D/QuickStatusbarLayout( 1410): Notification difference=198
D/QuickStatusbarLayout( 1410): child = android.widget.LinearLayout{6ebc377 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,I/UEI.SmartControl( 7150): --- Selecting new region: 6
,I/UEI.SmartControl( 7150): Model = LG-D855
D/UEI.SmartControl( 7150): QS Service created
I/art     ( 2157): Explicit concurrent mark sweep GC freed 29458(1708KB) AllocSpace objects, 16(2MB) LOS objects, 50% free, 30MB/62MB, paused 1.975ms total 66.786ms
,I/UEI.SmartControl( 7150): Service initServices...
D/UEI.SmartControl( 7150): QS start get config
I/GLSUser ( 2157): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 2157): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2157): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2157): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2157): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/Finsky  ( 7037): [1] LibraryUpdateListener.onErrorResponse: Library replication failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,D/UEI.SmartControl( 7150): Loading JNI Libs...
V/SIM_STK ( 1029): Menu title from STK is T-Mobile
,I/UEI.SmartControl( 7150): Supports setup maps: true
,D/UEI.SmartControl( 7150): QS start statue = true Error code = 0
,I/UEI.SmartControl( 7150): QS version = v2.7.10.1_RC1
I/UEI.SmartControl( 7150): QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
,I/UEI.SmartControl( 7150): ### init IR Blaster...
D/serial_port( 7150): Configuring serial port
E/UEI.SmartControl( 7150): UEIBLaster setting for 616
I/UEI.SmartControl( 7150): Setting serial record hearder size = 2
I/UEI.SmartControl( 7150): configuring settings for MAXQ616
I/UEI.SmartControl( 7150): Get version...
,D/UEI.SmartControl( 7150): serial port data available: 21
,D/UEI.SmartControl( 7150): MAXQ616 A2-X4 software.
I/UEI.SmartControl( 7150): IR Blaster version: 256702256704300002
I/UEI.SmartControl( 7150): QS saving settings...
D/UEI.SmartControl( 7150): IR Blaster version: 25672567
,D/UEI.SmartControl( 7150): serial port data available: 4
,V/GLSActivity( 2157): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/UEI.SmartControl( 7150): Device manager: loading config....
I/GLSUser ( 2157): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 2157): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2157): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2157): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
D/UEI.SmartControl( 7150): ----------- loading internal config...
V/GLSActivity( 2157): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/ContextImpl( 7150): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
E/UEI.SmartControl( 7150): Loading SETTINGS...
,D/UEI.SmartControl( 7150): -- Open brand translation xml: brands_translations_ko
,I/UEI.SmartControl( 7150): Notify AllClients services are ready: 0
D/UEI.SmartControl( 7150): -----service ready thread exits
,I/art     ( 1029): Explicit concurrent mark sweep GC freed 28899(1259KB) AllocSpace objects, 6(480KB) LOS objects, 33% free, 44MB/66MB, paused 1.590ms total 75.545ms
,E/UEI.SmartControl( 7150): Services init done
,D/UEI.SmartControl( 7150): QS Service init finished
D/UEI.SmartControl( 7150): QS Service version name: 2.1.91
D/UEI.SmartControl( 7150): QS Service version code: 201091
D/UEI.SmartControl( 7150): Service requested: Control
D/UEI.SmartControl( 7150): Internal service binding...
I/QRemote ( 6359): [RemoteControlManager.java:183:onServiceConnected()] oooooo start
,I/UEI.SmartControl( 7150): ------ IControl API: 11
W/Finsky  ( 7037): [1] 2.onErrorResponse: Update check failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
I/UEI.SmartControl( 7150): Registering callback...
D/Finsky  ( 7037): [1] DailyHygiene.logDeviceFeaturesAndContinue: Logging device features
I/UEI.SmartControl( 7150): ------ IControl API: 19
I/UEI.SmartControl( 7150): Registering Services Ready callback...
I/UEI.SmartControl( 7150): Notify client services are ready...
I/QRemote ( 6359): [RemoteControlManager.java:660:QSSetupIsReady()] oooooo 140517:sdkIsReady callback... get functions. Result:0
D/QRemote ( 6359): [RemoteControlManager.java:388:handleMessage()] oooooo 140510:START_SESSION
D/QRemote ( 6359): [RemoteControlManager.java:394:handleMessage()] oooooo 140510:send retrieve msg
D/QRemote ( 6359): [RemoteControlManager.java:322:handleMessage()] oooooo 140510:handler call retrieveDevices
D/QRemote ( 6359): [RemoteControlManager.java:336:retrieveDevices()] oooooo retrieveDevices: start
I/UEI.SmartControl( 7150): ------ IControl API: 8
D/QRemote ( 6359): [RemoteControlManager.java:340:retrieveDevices()] oooooo retrieveDevices: 0
D/QRemote ( 6359): [RemoteControlManager.java:345:retrieveDevices()] oooooo retrieveDevices complete:true
D/QRemote ( 6359): [RemoteControlManager.java:353:retrieveDevices()] oooooo retrieveDevices: notifyDataSetChanged()
D/QRemote ( 6359): [QRemoteApplication.java:145:onRemoteControlStateChanged()] oooooo onRemoteControlStateChanged called in QRemoteApp
D/QRemote ( 6359): [QRemoteApplication.java:158:onRemoteControlStateChanged()] oooooo Widget count is [1]. send broadcast
D/QRemote ( 6359): [QRemoteApplication.java:160:onRemoteControlStateChanged()] oooooo Widget[0]:3
D/Finsky  ( 7037): [1] DailyHygiene.flushEventLogsAndContinue: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/QRemote ( 6359): [QRemoteApplication.java:188:onRemoteControlStateChanged()] oooooo 140526:onRemoteControlStateChanged&sdkIsReady. stop Service
V/QRemote ( 6359): [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
D/QRemote ( 6359): [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
,E/QRemote ( 6359): [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
D/QRemote ( 6359): [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
D/QRemote ( 6359): [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
D/QRemote ( 6359): [RemoteAppWidgetProvider.java:506:onUpdate()] oooooo 140510:RetrieveDevices complete. Start loading
D/QRemote ( 6359): [RemoteAppWidgetProvider.java:508:onUpdate()] oooooo 140510:appWidgetIds[0]:3 loading
D/QRemote ( 6359): [RemoteAppWidgetManager.java:41:startLoading()] oooooo 140518:widgetId[3] loading start at [1454597282549]
D/Finsky  ( 7037): [1] DailyHygiene.reschedule: Scheduling new run in 866 minutes (failures=5)
D/QRemote ( 6359): [RemoteAppWidgetManager.java:239:doInBackground()] oooooo 140407:doinBack arr:0
V/QRemote ( 6359): [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.widget_ui_update
,E/QRemote ( 6359): [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
D/QRemote ( 6359): [RemoteAppWidgetProvider.java:171:onReceive()] oooooo total:0
D/QRemote ( 6359): [RemoteAppWidgetProvider.java:172:onReceive()] oooooo selected:0
D/QRemote ( 6359): [RemoteAppWidgetProvider.java:173:onReceive()] oooooo arr:[]
D/QRemote ( 6359): [RemoteAppWidgetProvider.java:174:onReceive()] oooooo appWidgetId:3
D/QRemote ( 6359): [RemoteAppWidgetProvider.java:815:updateRemoteViews()] oooooo UpdateRemoteViews3:widgetId:3
,D/QRemote ( 6359): [RemoteAppWidgetProvider.java:986:updateRemoteViews()] oooooo updateAppWidget5:widgetId:3]
I/ActivityManager( 1029): Killing 6648:com.lge.appbox.client/u0a11 (adj 15): empty #17
D/DeviceConnectionService( 1826): client connected with version: 7571000
,W/libprocessgroup( 1029): failed to open /acct/uid_10011/pid_6648/cgroup.procs: No such file or directory
,I/ActivityManager( 1029): Killing 6256:com.lge.formmanager/u0a26 (adj 15): empty #17
,W/libprocessgroup( 1029): failed to open /acct/uid_10026/pid_6256/cgroup.procs: No such file or directory
,I/GAV4    ( 6862): Thread[GAThread,5,main]: No campaign data found.
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-65 f=2412 sc=60 link=65 tx=36.2, 0.0, 0.0  rx=30.4 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1396630061] gl rssi=-65 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-65 f=2412 sc=60 link=65 tx=36.2, 0.0, 0.0  rx=30.4 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-1396630060] gl rssi=-65 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,D/sensors_hal_Time( 1029): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1029): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1029): tsOffsetIs: Apps: 137435788024; DSPS: 4644308; Offset : -4312469877
,I/ActivityManager( 1029): Killing 6803:com.lge.drmservice/u0a62 (adj 15): empty #17
,W/libprocessgroup( 1029): failed to open /acct/uid_10062/pid_6803/cgroup.procs: No such file or directory
,I/ActivityManager( 1029): Killing 6862:com.google.android.apps.magazines/u0a93 (adj 15): empty #17
,W/libprocessgroup( 1029): failed to open /acct/uid_10093/pid_6862/cgroup.procs: No such file or directory
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-65 f=2412 sc=60 link=65 tx=20.6, 0.0, 0.0  rx=16.7 bcn=0 [on:0 tx:0 rx:0 period:3017] from screen [on:0 period:-1396627036] gl rssi=-65 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-65 f=2412 sc=60 link=65 tx=20.6, 0.0, 0.0  rx=16.7 bcn=0 [on:0 tx:0 rx:0 period:4] from screen [on:0 period:-1396627032] gl rssi=-65 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
W/ProcessCpuTracker( 1029): Skipping unknown process pid 7203
,W/ProcessCpuTracker( 1029): Skipping unknown process pid 7204
,W/ProcessCpuTracker( 1029): Skipping unknown process pid 7206
D/serial_port( 7150): close(fd = 25)
,D/UEI.SmartControl( 7150): Internal timer expired: 1
,D/UEI.SmartControl( 7150): unbind internal service
I/UEI.SmartControl( 7150): Serial port is closed.
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-65 f=2412 sc=60 link=65 tx=10.8, 0.0, 0.0  rx=8.8 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:-1396624014] gl rssi=-65 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-65 f=2412 sc=60 link=65 tx=10.8, 0.0, 0.0  rx=8.8 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1396624011] gl rssi=-65 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-65 f=2412 sc=60 link=65 tx=5.9, 0.0, 0.0  rx=4.9 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1396620984] gl rssi=-65 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-65 f=2412 sc=60 link=65 tx=5.9, 0.0, 0.0  rx=4.9 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1396620981] gl rssi=-65 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-65 f=2412 sc=60 link=65 tx=2.9, 0.0, 0.0  rx=2.5 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1396617954] gl rssi=-65 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-65 f=2412 sc=60 link=65 tx=2.9, 0.0, 0.0  rx=2.5 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1396617951] gl rssi=-65 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,I/[SystemUI]QPairHandler( 1464): onReceive = android.intent.action.PACKAGE_CHANGED
,D/SplitUIService( 1878): replaced split : contains_com.google.android.talk / true
,I/InputReader( 1029): Reconfiguring input devices.  changes=0x00000010
,I/ActivityManager( 1029): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.manager.PreloadListManagerHelper: pid=7210 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,I/[SystemUI]QSlideListController( 1464): onReceive = android.intent.action.PACKAGE_CHANGED
I/[SystemUI]AppWidgetPanel(QRemoteWidgetPanel)( 1464): onReceive = android.intent.action.PACKAGE_CHANGED, packageName : com.google.android.talk
I/[LGHome]EVENT( 2078): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.talk flg=0x4000010 (has extras) }
,W/ResourcesManager( 2078): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,D/SplitUIManager( 1878): split_name #11 / not available #0
I/SplitUIService( 1878): split app #11
D/administrator( 1029): Handling package changes for user 0
,I/[LGHome]Launcher( 2078): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/AppUp4:AppBoxCP( 7210): onCreate
W/AppUp4:DB( 7210):  [AppBoxDatabaseHelper] construct
,I/AppUp4:DB( 7210):  setFingerPrint start
I/AppUp4:DB( 7210):  newfinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys SDK version = 21
I/AppUp4:DB( 7210):  beforefinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys
I/AppUp4:DB( 7210):  SDK version = 21
I/AppUp4:DB( 7210):  beforefinger == newfinger no write in DB
,D/AppUp4:AppBoxApplication( 7210): AppBoxApplication onCreate()
,I/AppUp4:CustModeStarterReceiver( 7210): onReceive
D/LgDataFeature( 7210): LgDataFeature() Constructor: none
D/LgDataFeature( 7210): LgDataFeature() Constructor Done, null
,D/AppUp4:CustFacade( 7210): Context : android.app.ReceiverRestrictedContext@3c4ae590
D/AppUp4:CustFacade( 7210): isCustomizationCompleted : false
,D/AppUp4:CustFacade( 7210): isPhone : true
D/AppUp4:CustModeStarterReceiver( 7210): begin check event
I/AppUp4:CustModeStarterReceiver( 7210): Event For Nothing, skip.
I/NotificationService( 1029): action=android.intent.action.PACKAGE_CHANGED queryReplace=false
D/BackupManagerService( 1029): Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.talk flg=0x4000010 (has extras) }
,W/ResourcesManager( 1029): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
I/ActivityManager( 1029): Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=7246 uid=10019 gids={50019, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
,I/ActivityManager( 1029): Killing 6709:com.android.chrome/u0a57 (adj 15): empty #17
W/ResourcesManager( 1029): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourceType( 1029): Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
,W/libprocessgroup( 1029): failed to open /acct/uid_10057/pid_6709/cgroup.procs: No such file or directory
,I/[LGHome]EVENT( 2078): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
W/ResourcesManager( 7246): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7246): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 7246): Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
,W/ResourcesManager( 7246): Asset path '/system/framework/lghiddenlibs.jar' does not exist or contains no resources.
W/ResourcesManager( 7246): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
I/SystemConfig( 7246): BUILD Country: EU
I/SystemConfig( 7246): BUILD Operator: OPEN
,I/ActivityManager( 1029): Killing 6686:com.android.gallery3d/u0a27 (adj 15): empty #17
,W/libprocessgroup( 1029): failed to open /acct/uid_10027/pid_6686/cgroup.procs: No such file or directory
,I/SystemConfig( 7246): pm.hasSystemFeature(com.lge.ims.rcs) = false
I/SystemConfig( 7246): existFile = false
,I/SystemConfig( 7246): canReadFile = false
I/SystemConfig( 7246): systemFeature RCS result false
D/SystemConfig( 7246): refreshRcsSupport() :false
,I/ActivityManager( 1029): Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=7269 uid=10027 gids={50027, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
,W/ResourcesManager( 7269): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7269): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 7269): Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
,W/ResourcesManager( 7269): Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
I/AppConfig( 7269): Total System Memory = 2995761152
,D/SystemHelper( 7269): region [EU], country [EU], operator [OPEN], sub-operator []
,I/ActivityManager( 1029): Killing 6841:com.google.android.apps.plus/u0a97 (adj 15): empty #17
,W/libprocessgroup( 1029): failed to open /acct/uid_10097/pid_6841/cgroup.procs: No such file or directory
,I/UpdateIcingCorporaServi( 4282): Updating corpora: APPS=com.google.android.talk, CONTACTS=MAYBE
V/SIM_STK ( 1029): Menu title from STK is T-Mobile
,W/ResourcesManager( 4282): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/UpdateIcingCorporaServi( 4282): UpdateCorporaTask done [took 57 ms] updated apps [took 57 ms] 
I/ActivityManager( 1029): Start proc com.lge.lockscreensettings for broadcast com.lge.lockscreensettings/.PackageIntentReceiver: pid=7289 uid=10080 gids={50080, 9997, 1028, 1015} abi=armeabi-v7a
,I/LockScreenSettings( 7289): Wallpaper base directory = /data/data/com.lge.lockscreensettings/files/
,D/LockScreenSettings( 7289): Quick window widget present in DB = com.lge.clock.quickcover.QuickCoverSettingActivity  true
D/LockScreenSettings( 7289): Quick window widget present in DB = com.lge.camera.app.QuickWindowCameraActivity  true
D/LockScreenSettings( 7289): Quick window widget present in DB = com.android.contacts.activities.QuickCircleActivity  true
D/LockScreenSettings( 7289): Quick window widget present in DB = com.android.mms.quickcover.QuickCoverActivity  true
D/LockScreenSettings( 7289): Quick window widget present in DB = com.lge.music.MusicQuickCircle  true
D/LockScreenSettings( 7289): Quick window widget present in DB = com.lge.lifetracker.QuickCover  true
,I/ActivityManager( 1029): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=7306 uid=10097 gids={50097, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
I/ActivityManager( 1029): Killing 6733:com.lge.email/u0a23 (adj 15): empty #17
,I/art     (  352): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 299us total 19.894ms
,I/art     (  352): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 353us total 17.511ms
,I/art     (  352): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 381us total 16.627ms
,W/libprocessgroup( 1029): failed to open /acct/uid_10023/pid_6733/cgroup.procs: No such file or directory
W/ResourcesManager( 7306): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,D/PackageBroadcastService( 2334): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.talk
,I/PeopleContactsSync( 2334): CP2 sync disabled
,I/GLSActivity( 2157): [ac] getting account id
,I/GLSUser ( 2157): [t] Fetched account id for thalitester@gmail.com : 105256135866144380227
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-65 f=2412 sc=60 link=65 tx=2.0, 0.0, 0.0  rx=1.7 bcn=0 [on:0 tx:0 rx:0 period:3005] from screen [on:0 period:-1396614924] gl rssi=-65 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-65 f=2412 sc=60 link=65 tx=2.0, 0.0, 0.0  rx=1.7 bcn=0 [on:0 tx:0 rx:0 period:2] from screen [on:0 period:-1396614922] gl rssi=-65 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-65 f=2412 sc=60 link=65 tx=1.5, 0.0, 0.0  rx=1.4 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1396611900] gl rssi=-65 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-65 f=2412 sc=60 link=65 tx=1.5, 0.0, 0.0  rx=1.4 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-1396611899] gl rssi=-65 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,I/ActivityManager( 1029): Killing 5221:com.wsandroid.suite.lge/1000 (adj 15): empty #17
,W/libprocessgroup( 1029): failed to open /acct/uid_1000/pid_5221/cgroup.procs: No such file or directory
,V/AlarmManager( 1029): RTC_WAKEUP set : Alarm{34601f7a type 0 when 1454597302078 com.android.vending} when 1454597302078
,V/SIM_STK ( 1029): Menu title from STK is T-Mobile
,V/GLSActivity( 2157): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2157): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 2157): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2157): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2157): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2157): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/Finsky  ( 7037): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 7037): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 7037): [1] 5.onFinished: Scheduling replication attempt 3.
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-65 f=2412 sc=60 link=65 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1396608878] gl rssi=-65 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-65 f=2412 sc=60 link=65 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-1396608868] gl rssi=-65 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
D/sensors_hal_Time( 1029): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1029): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1029): tsOffsetIs: Apps: 157437881506; DSPS: 5299737; Offset : -4312482056
,V/AlarmManager( 1029): ELAPSED_WAKEUP set : Alarm{162d51cc type 2 when 158593 android} when 158593
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-65 f=2412 sc=60 link=65 tx=0.9, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1396605849] gl rssi=-65 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-65 f=2412 sc=60 link=65 tx=0.9, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:11] from screen [on:0 period:-1396605838] gl rssi=-65 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-65 f=2412 sc=60 link=65 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1396602816] gl rssi=-65 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-65 f=2412 sc=60 link=65 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1396602813] gl rssi=-65 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1029):  ConnectedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 1 0
,E/WifiStateMachine( 1029):  L2ConnectedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 1 0
E/WifiStateMachine( 1029):  ConnectModeState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 1 0
E/WifiStateMachine( 1029):  DriverStartedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 1 0
E/WifiStateMachine( 1029):  SupplicantStartedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 1 0
,E/WifiStateMachine( 1029):  DefaultState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 1 0
E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-65 f=2412 sc=60 link=65 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:2999] from screen [on:0 period:-1396599792] gl rssi=-65 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-65 f=2412 sc=60 link=65 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-1396599791] gl rssi=-65 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-65 f=2412 sc=60 link=65 tx=0.9, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:-1396596780] gl rssi=-65 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-65 f=2412 sc=60 link=65 tx=0.9, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-1396596770] gl rssi=-65 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-65 f=2412 sc=60 link=65 tx=0.4, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1396593750] gl rssi=-65 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-65 f=2412 sc=60 link=65 tx=0.4, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:11] from screen [on:0 period:-1396593739] gl rssi=-65 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-65 f=2412 sc=60 link=65 tx=0.7, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1396590718] gl rssi=-65 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-65 f=2412 sc=60 link=65 tx=0.7, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:4] from screen [on:0 period:-1396590714] gl rssi=-65 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,D/sensors_hal_Time( 1029): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1029): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1029): tsOffsetIs: Apps: 177439966029; DSPS: 5955165; Offset : -4312472859
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-65 f=2412 sc=60 link=65 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1396587688] gl rssi=-65 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-65 f=2412 sc=60 link=65 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1396587685] gl rssi=-65 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-65 f=2412 sc=60 link=65 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3005] from screen [on:0 period:-1396584656] gl rssi=-65 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-65 f=2412 sc=60 link=65 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1396584653] gl rssi=-65 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-65 f=2412 sc=60 link=65 tx=0.3, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:-1396581635] gl rssi=-65 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-65 f=2412 sc=60 link=65 tx=0.3, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1396581632] gl rssi=-65 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,V/AlarmManager( 1029): RTC_WAKEUP set : Alarm{abf5b2a type 0 when 1454597323577 com.android.vending} when 1454597323577
,V/SIM_STK ( 1029): Menu title from STK is T-Mobile
,V/GLSActivity( 2157): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2157): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 2157): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2157): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2157): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2157): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/Finsky  ( 7037): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 7037): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 7037): [1] 5.onFinished: Scheduling replication attempt 4.
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-65 f=2412 sc=60 link=65 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1396578604] gl rssi=-65 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-65 f=2412 sc=60 link=65 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1396578601] gl rssi=-65 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,V/AlarmManager( 1029): ELAPSED_WAKEUP set : Alarm{e8ec5fc type 2 when 188623 android} when 188623
,I/BooksSync( 6668): Starting books sync
,D/BooksSync( 6668): started syncMyEbooks
,V/GLSActivity( 2157): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2157): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.syncadapters.contacts, service: cp
,I/GLSUser ( 2157): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> cp without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2157): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2157): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2157): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1029): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1029): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1029): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1029): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1029): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1410): onNotificationPosted
,W/GLSActivity( 2157): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2157): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2157): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2157): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2157): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2157): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2157): 	at android.os.Binder.execTransact(Binder.java:446)
,V/GLSActivity( 2157): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ContactsSyncAdapter( 2157): innerSync failed
D/ContactsSyncAdapter( 2157): com.google.wireless.gdata2.client.AuthenticationException: unable to get auth token android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
D/ContactsSyncAdapter( 2157): 	at com.google.android.syncadapters.contacts.AuthInfo.getAuthToken(AuthInfo.java:45)
D/ContactsSyncAdapter( 2157): 	at com.google.android.syncadapters.contacts.ContactsSyncAdapter.innerPerformSync(ContactsSyncAdapter.java:263)
D/ContactsSyncAdapter( 2157): 	at com.google.android.syncadapters.contacts.ContactsSyncAdapter.onPerformLoggedSync(ContactsSyncAdapter.java:168)
D/ContactsSyncAdapter( 2157): 	at com.google.android.common.LoggingThreadedSyncAdapter.onPerformSync(LoggingThreadedSyncAdapter.java:33)
D/ContactsSyncAdapter( 2157): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
D/ContactsSyncAdapter( 2157): Caused by: android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
D/ContactsSyncAdapter( 2157): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
D/ContactsSyncAdapter( 2157): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
D/ContactsSyncAdapter( 2157): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
D/ContactsSyncAdapter( 2157): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
D/ContactsSyncAdapter( 2157): 	at android.os.Binder.execTransact(Binder.java:446)
D/SmartCoverUpdateMonitor( 1410): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1410): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1410): handleNotificationPosted(true)
D/QuickCircle( 1410): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1410): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1410): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1410): post do just update job
D/LgeQuickCoverNotificationData( 1410): showAll3
D/LgeQuickCoverNotificationData( 1410): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1410): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1410): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1410): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1410): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1410): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1410): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1410): isNotificationForCurrentUser : true
,D/LgeQuickCoverOverlayWindow( 1410): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1410): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1410): updateNotificationData: count=3
I/GLSUser ( 2157): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2157): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2157): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2157): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,D/SyncManager( 1029): failed sync operation thalitester@gmail.com u0 (com.google), com.android.contacts, LOCAL, currentRunTime 163312, reason: 10019, SyncResult: stats [ numAuthExceptions: 1]
,D/QuickStatusbarLayout( 1410): Notification difference=198
D/QuickStatusbarLayout( 1410): child = android.widget.LinearLayout{6ebc377 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
D/SyncManager( 1029): not retrying sync operation because the error is a hard error: thalitester@gmail.com u0 (com.google), com.android.contacts, LOCAL, currentRunTime 254933, reason: 10019
V/GLSActivity( 2157): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1029): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1029): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1029): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1029): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1029): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1410): onNotificationPosted
D/SmartCoverUpdateMonitor( 1410): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1410): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1410): handleNotificationPosted(true)
D/QuickCircle( 1410): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1410): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1410): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1410): post do just update job
D/LgeQuickCoverNotificationData( 1410): showAll3
D/LgeQuickCoverNotificationData( 1410): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1410): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1410): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1410): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1410): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1410): isNotificationForCurrentUser : true
W/GLSActivity( 2157): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2157): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2157): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2157): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2157): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2157): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2157): 	at android.os.Binder.execTransact(Binder.java:446)
D/LgeQuickCoverOverlayWindow( 1410): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1410): isNotificationForCurrentUser : true
E/BooksAccountManager( 6668): Authentication error
E/BooksAccountManager( 6668): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6668): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6668): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6668): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6668): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6668): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6668): null auth token
D/LgeQuickCoverOverlayWindow( 1410): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1410): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1410): updateNotificationData: count=3
,D/QuickStatusbarLayout( 1410): Notification difference=198
D/QuickStatusbarLayout( 1410): child = android.widget.LinearLayout{6ebc377 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,W/ApiaryClient( 6668): Error response from books API: {
W/ApiaryClient( 6668):  "error": {
W/ApiaryClient( 6668):   "errors": [
W/ApiaryClient( 6668):    {
W/ApiaryClient( 6668):     "domain": "global",
W/ApiaryClient( 6668):     "reason": "required",
W/ApiaryClient( 6668):     "message": "Login Required",
W/ApiaryClient( 6668):     "locationType": "header",
W/ApiaryClient( 6668):     "location": "Authorization"
W/ApiaryClient( 6668):    }
W/ApiaryClient( 6668):   ],,
W/ApiaryClient( 6668):   "code": 401,
W/ApiaryClient( 6668):   "message": "Login Required"
W/ApiaryClient( 6668):  }
W/ApiaryClient( 6668): }
,W/ApiaryClient( 6668): errCount = 1: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6668): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-4695978840488453984&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6668): Headers:
W/ApiaryClient( 6668): accept-encoding: [gzip]
W/ApiaryClient( 6668): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6668): gdata-version: 2
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-65 f=2412 sc=60 link=65 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1396575582] gl rssi=-65 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-65 f=2412 sc=60 link=65 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1396575579] gl rssi=-65 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,I/art     ( 1029): Explicit concurrent mark sweep GC freed 42511(2001KB) AllocSpace objects, 3(304KB) LOS objects, 33% free, 44MB/66MB, paused 3.627ms total 174.826ms
,V/GLSActivity( 2157): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/GLSUser ( 2157): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2157): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2157): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2157): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2157): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/NotificationService( 1029): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1029): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1029): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1029): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1029): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
W/GLSActivity( 2157): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2157): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2157): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2157): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2157): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2157): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2157): 	at android.os.Binder.execTransact(Binder.java:446)
E/BooksAccountManager( 6668): Authentication error
E/BooksAccountManager( 6668): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6668): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6668): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6668): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6668): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6668): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6668): null auth token
,D/LgeQuickCoverNLService( 1410): onNotificationPosted
,D/SmartCoverUpdateMonitor( 1410): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1410): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1410): handleNotificationPosted(true)
D/QuickCircle( 1410): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1410): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1410): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1410): post do just update job
,D/LgeQuickCoverNotificationData( 1410): showAll3
D/LgeQuickCoverNotificationData( 1410): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1410): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1410): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1410): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1410): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1410): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1410): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1410): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1410): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1410): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1410): updateNotificationData: count=3
,D/QuickStatusbarLayout( 1410): Notification difference=198
,D/QuickStatusbarLayout( 1410): child = android.widget.LinearLayout{6ebc377 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,W/ApiaryClient( 6668): Error response from books API: {
W/ApiaryClient( 6668):  "error": {
W/ApiaryClient( 6668):   "errors": [
W/ApiaryClient( 6668):    {
W/ApiaryClient( 6668):     "domain": "global",
W/ApiaryClient( 6668):     "reason": "required",
W/ApiaryClient( 6668):     "message": "Login Required",
W/ApiaryClient( 6668):     "locationType": "header",
W/ApiaryClient( 6668):     "location": "Authorization"
W/ApiaryClient( 6668):    }
W/ApiaryClient( 6668):   ],
W/ApiaryClient( 6668):   "code": 401,
W/ApiaryClient( 6668):   "message": "Login Required"
W/ApiaryClient( 6668):  }
W/ApiaryClient( 6668): }
,W/ApiaryClient( 6668): errCount = 2: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6668): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-4695978840488453984&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6668): Headers:
W/ApiaryClient( 6668): accept-encoding: [gzip]
W/ApiaryClient( 6668): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6668): gdata-version: 2
,V/GLSActivity( 2157): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2157): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2157): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2157): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 2157): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2157): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1029): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1029): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1029): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1029): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1029): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1410): onNotificationPosted
,D/SmartCoverUpdateMonitor( 1410): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1410): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1410): handleNotificationPosted(true)
D/QuickCircle( 1410): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1410): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1410): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1410): post do just update job
D/LgeQuickCoverNotificationData( 1410): showAll3
D/LgeQuickCoverNotificationData( 1410): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1410): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1410): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1410): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1410): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1410): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1410): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1410): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1410): [native noti] inex =  2
,D/LgeQuickCoverNotificationData( 1410): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1410): updateNotificationData: count=3
W/GLSActivity( 2157): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2157): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2157): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2157): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2157): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2157): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2157): 	at android.os.Binder.execTransact(Binder.java:446)
E/BooksAccountManager( 6668): Authentication error
E/BooksAccountManager( 6668): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6668): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6668): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6668): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6668): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6668): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6668): null auth token
,D/QuickStatusbarLayout( 1410): Notification difference=198
D/QuickStatusbarLayout( 1410): child = android.widget.LinearLayout{6ebc377 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
W/ApiaryClient( 6668): Error response from books API: {
W/ApiaryClient( 6668):  "error": {
W/ApiaryClient( 6668):   "errors": [
W/ApiaryClient( 6668):    {
W/ApiaryClient( 6668):     "domain": "global",
W/ApiaryClient( 6668):     "reason": "required",
W/ApiaryClient( 6668):     "message": "Login Required",
W/ApiaryClient( 6668):     "locationType": "header",
W/ApiaryClient( 6668):     "location": "Authorization"
W/ApiaryClient( 6668):    }
W/ApiaryClient( 6668):   ],
W/ApiaryClient( 6668):   "code": 401,
W/ApiaryClient( 6668):   "message": "Login Required"
W/ApiaryClient( 6668):  }
W/ApiaryClient( 6668): }
,W/ApiaryClient( 6668): errCount = 3: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6668): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-4695978840488453984&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6668): Headers:
W/ApiaryClient( 6668): accept-encoding: [gzip]
W/ApiaryClient( 6668): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6668): gdata-version: 2
,I/[SystemUI]TimeTickManager( 1464): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1464): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1464): called onTimeUpdated()
I/[SystemUI]Clock( 1464): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1464): called onTimeUpdated()
,I/[SystemUI]DateView( 1464): called onTimeUpdated()
I/[SystemUI]DateView( 1464): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1464): handleTimeUpdate
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-65 f=2412 sc=60 link=65 tx=1.4, 0.0, 0.0  rx=1.4 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1396572559] gl rssi=-65 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-65 f=2412 sc=60 link=65 tx=1.4, 0.0, 0.0  rx=1.4 bcn=0 [on:0 tx:0 rx:0 period:15] from screen [on:0 period:-1396572544] gl rssi=-65 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
E/BooksSync( 6668): Soft error: 
E/BooksSync( 6668): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 6668): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-4695978840488453984&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 6668): Headers:
E/BooksSync( 6668): accept-encoding: [gzip]
E/BooksSync( 6668): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 6668): gdata-version: 2
E/BooksSync( 6668): 
E/BooksSync( 6668): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 6668): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 6668): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 6668): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 6668): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 6668): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 6668): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 6668): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 6668): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 6668): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 6668): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 6668): {
E/BooksSync( 6668):  "error": {
E/BooksSync( 6668):   "errors": [
E/BooksSync( 6668):    {
E/BooksSync( 6668):     "domain": "global",
E/BooksSync( 6668):     "reason": "required",
E/BooksSync( 6668):     "message": "Login Required",
E/BooksSync( 6668):     "locationType": "header",
E/BooksSync( 6668):     "location": "Authorization"
E/BooksSync( 6668):    }
E/BooksSync( 6668):   ],
E/BooksSync( 6668):   "code": 401,
E/BooksSync( 6668):   "message": "Login Required"
E/BooksSync( 6668):  }
E/BooksSync( 6668): }
E/BooksSync( 6668): 
E/BooksSync( 6668): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 6668): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 6668): 	... 8 more
,E/BooksSync( 6668): Sync error
E/BooksSync( 6668): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 6668): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-4695978840488453984&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 6668): Headers:
E/BooksSync( 6668): accept-encoding: [gzip]
E/BooksSync( 6668): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 6668): gdata-version: 2
E/BooksSync( 6668): 
E/BooksSync( 6668): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 6668): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 6668): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 6668): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 6668): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 6668): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 6668): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 6668): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 6668): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 6668): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 6668): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 6668): {
E/BooksSync( 6668):  "error": {
E/BooksSync( 6668):   "errors": [
E/BooksSync( 6668):    {
E/BooksSync( 6668):     "domain": "global",
E/BooksSync( 6668):     "reason": "required",
E/BooksSync( 6668):     "message": "Login Required",
E/BooksSync( 6668):     "locationType": "header",
E/BooksSync( 6668):     "location": "Authorization"
E/BooksSync( 6668):    }
E/BooksSync( 6668):   ],
E/BooksSync( 6668):   "code": 401,
E/BooksSync( 6668):   "message": "Login Required"
E/BooksSync( 6668):  }
E/BooksSync( 6668): }
E/BooksSync( 6668): 
E/BooksSync( 6668): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 6668): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 6668): 	... 8 more
I/BooksSync( 6668): Finished books sync
D/SyncManager( 1029): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 163622, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-65 f=2412 sc=60 link=65 tx=3.2, 0.0, 0.0  rx=3.2 bcn=0 [on:0 tx:0 rx:0 period:2999] from screen [on:0 period:-1396569526] gl rssi=-65 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-65 f=2412 sc=60 link=65 tx=3.2, 0.0, 0.0  rx=3.2 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-1396569525] gl rssi=-65 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,D/sensors_hal_Time( 1029): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1029): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1029): tsOffsetIs: Apps: 197442059824; DSPS: 6610594; Offset : -4312484828
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-65 f=2412 sc=60 link=65 tx=2.1, 0.0, 0.0  rx=2.1 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:-1396566514] gl rssi=-65 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-65 f=2412 sc=60 link=65 tx=2.1, 0.0, 0.0  rx=2.1 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1396566511] gl rssi=-65 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-65 f=2412 sc=60 link=65 tx=1.1, 0.0, 0.0  rx=1.1 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1396563484] gl rssi=-65 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-65 f=2412 sc=60 link=65 tx=1.1, 0.0, 0.0  rx=1.1 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1396563481] gl rssi=-65 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-65 f=2412 sc=60 link=65 tx=1.0, 0.0, 0.0  rx=1.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1396560460] gl rssi=-65 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-65 f=2412 sc=60 link=65 tx=1.0, 0.0, 0.0  rx=1.0 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-1396560450] gl rssi=-65 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-65 f=2412 sc=60 link=65 tx=0.5, 0.0, 0.0  rx=0.5 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1396557427] gl rssi=-65 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-65 f=2412 sc=60 link=65 tx=0.5, 0.0, 0.0  rx=0.5 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1396557424] gl rssi=-65 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-65 f=2412 sc=60 link=65 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1396554400] gl rssi=-65 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-65 f=2412 sc=60 link=65 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-1396554390] gl rssi=-65 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-65 f=2412 sc=60 link=65 tx=0.9, 0.0, 0.0  rx=0.9 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1396551379] gl rssi=-65 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-65 f=2412 sc=60 link=65 tx=0.9, 0.0, 0.0  rx=0.9 bcn=0 [on:0 tx:0 rx:0 period:13] from screen [on:0 period:-1396551366] gl rssi=-65 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
D/PowerManagerServiceEx( 1029): acquireWakeLockInternal: lock=811726971, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1029
,V/AlarmManager( 1029): RTC_WAKEUP set : Alarm{3c5941ea type 0 when 1454597352423 com.android.vending} when 1454597352423
,D/[Concierge]Service( 2605): onStartCommand(). Type : 9
,D/PowerManagerServiceEx( 1029): releaseWakeLockInternal: lock=811726971 [*alarm*], flags=0x0
,V/SIM_STK ( 1029): Menu title from STK is T-Mobile
,V/GLSActivity( 2157): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2157): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 2157): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 2157): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2157): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2157): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/Finsky  ( 7037): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 7037): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 7037): [1] 5.onFinished: Scheduling replication attempt 5.
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-65 f=2412 sc=60 link=65 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:-1396548344] gl rssi=-65 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-65 f=2412 sc=60 link=65 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1396548341] gl rssi=-65 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,D/sensors_hal_Time( 1029): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1029): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1029): tsOffsetIs: Apps: 217443906900; DSPS: 7266015; Offset : -4312499038
,V/AlarmManager( 1029): ELAPSED_WAKEUP set : Alarm{1ef8cebc type 2 when 218671 android} when 218671
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-65 f=2412 sc=60 link=65 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3000] from screen [on:0 period:-1396545319] gl rssi=-65 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-65 f=2412 sc=60 link=65 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:9] from screen [on:0 period:-1396545310] gl rssi=-65 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-65 f=2412 sc=60 link=65 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1396542292] gl rssi=-65 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-65 f=2412 sc=60 link=65 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1396542289] gl rssi=-65 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-65 f=2412 sc=60 link=65 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1396539265] gl rssi=-65 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-65 f=2412 sc=60 link=65 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1396539262] gl rssi=-65 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-65 f=2412 sc=60 link=65 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:2999] from screen [on:0 period:-1396536246] gl rssi=-65 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-65 f=2412 sc=60 link=65 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-1396536245] gl rssi=-65 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-65 f=2412 sc=60 link=65 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3005] from screen [on:0 period:-1396533225] gl rssi=-65 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-65 f=2412 sc=60 link=65 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1396533222] gl rssi=-65 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-65 f=2412 sc=60 link=65 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1396530194] gl rssi=-65 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-65 f=2412 sc=60 link=65 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1396530191] gl rssi=-65 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,D/sensors_hal_Time( 1029): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1029): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1029): tsOffsetIs: Apps: 237445838298; DSPS: 7921438; Offset : -4312490352
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-65 f=2412 sc=60 link=65 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:-1396527164] gl rssi=-65 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-65 f=2412 sc=60 link=65 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1396527161] gl rssi=-65 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-65 f=2412 sc=60 link=65 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1396524135] gl rssi=-65 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-65 f=2412 sc=60 link=65 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:4] from screen [on:0 period:-1396524131] gl rssi=-65 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-65 f=2412 sc=60 link=65 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1396521112] gl rssi=-65 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-65 f=2412 sc=60 link=65 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1396521109] gl rssi=-65 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,V/AlarmManager( 1029): ELAPSED_WAKEUP set : Alarm{20557e45 type 2 when 213212 android} when 213212
,V/AlarmManager( 1029): RTC_WAKEUP set : Alarm{368c62cb type 0 when 1454597384296 com.android.vending} when 1454597384296
,V/SIM_STK ( 1029): Menu title from STK is T-Mobile
,V/GLSActivity( 2157): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2157): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 2157): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2157): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2157): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2157): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/Finsky  ( 7037): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 7037): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 7037): [1] 5.onFinished: Giving up after 6 failures.
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-65 f=2412 sc=60 link=65 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:-1396518086] gl rssi=-65 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-65 f=2412 sc=60 link=65 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1396518083] gl rssi=-65 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-65 f=2412 sc=60 link=65 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1396515058] gl rssi=-65 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-65 f=2412 sc=60 link=65 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-1396515048] gl rssi=-65 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,I/[SystemUI]TimeTickManager( 1464): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1464): called onTimeUpdated()
,I/[SystemUI]KeyguardIndicationController( 1464): called onTimeUpdated()
I/[SystemUI]Clock( 1464): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1464): called onTimeUpdated()
,I/[SystemUI]DateView( 1464): called onTimeUpdated()
,I/[SystemUI]DateView( 1464): called onTimeUpdated()
,D/KeyguardUpdateMonitor( 1464): handleTimeUpdate
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-65 f=2412 sc=60 link=65 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1396512027] gl rssi=-65 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-65 f=2412 sc=60 link=65 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:4] from screen [on:0 period:-1396512023] gl rssi=-65 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,D/PowerManagerServiceEx( 1029): acquireWakeLockInternal: lock=811726971, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1029
,V/AlarmManager( 1029): ELAPSED_WAKEUP set : Alarm{172b82b5 type 2 when 253232 android} when 253232
D/[Concierge]Service( 2605): onStartCommand(). Type : 9
,D/PowerManagerServiceEx( 1029): releaseWakeLockInternal: lock=811726971 [*alarm*], flags=0x0
,I/BooksSync( 6668): Starting books sync
,D/BooksSync( 6668): started syncMyEbooks
,V/GLSActivity( 2157): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2157): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2157): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2157): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2157): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2157): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1029): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1029): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1029): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1029): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1029): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
W/GLSActivity( 2157): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2157): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2157): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2157): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2157): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2157): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2157): 	at android.os.Binder.execTransact(Binder.java:446)
D/LgeQuickCoverNLService( 1410): onNotificationPosted
D/SmartCoverUpdateMonitor( 1410): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1410): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1410): handleNotificationPosted(true)
D/QuickCircle( 1410): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1410): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1410): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1410): post do just update job
D/LgeQuickCoverNotificationData( 1410): showAll3
D/LgeQuickCoverNotificationData( 1410): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1410): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1410): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1410): showNotificationWithSetupData: display=false
,E/BooksAccountManager( 6668): Authentication error
E/BooksAccountManager( 6668): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6668): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6668): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6668): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6668): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6668): 	at android.os.Binder.execTransact(Binder.java:446)
,E/HttpHelper( 6668): null auth token
D/LgeQuickCoverOverlayWindow( 1410): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1410): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1410): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1410): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1410): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1410): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1410): updateNotificationData: count=3
D/QuickStatusbarLayout( 1410): Notification difference=198
D/QuickStatusbarLayout( 1410): child = android.widget.LinearLayout{6ebc377 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,W/ApiaryClient( 6668): Error response from books API: {
W/ApiaryClient( 6668):  "error": {
W/ApiaryClient( 6668):   "errors": [
W/ApiaryClient( 6668):    {
W/ApiaryClient( 6668):     "domain": "global",
W/ApiaryClient( 6668):     "reason": "required",
W/ApiaryClient( 6668):     "message": "Login Required",
W/ApiaryClient( 6668):     "locationType": "header",
W/ApiaryClient( 6668):     "location": "Authorization"
W/ApiaryClient( 6668):    }
W/ApiaryClient( 6668):   ],
W/ApiaryClient( 6668):   "code": 401,
W/ApiaryClient( 6668):   "message": "Login Required"
W/ApiaryClient( 6668):  }
W/ApiaryClient( 6668): }
,W/ApiaryClient( 6668): errCount = 1: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6668): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=3841994897377923430&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6668): Headers:
W/ApiaryClient( 6668): accept-encoding: [gzip]
W/ApiaryClient( 6668): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6668): gdata-version: 2
,V/GLSActivity( 2157): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2157): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 2157): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2157): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2157): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2157): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1029): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1029): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1029): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1029): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1029): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1410): onNotificationPosted
,D/SmartCoverUpdateMonitor( 1410): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1410): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1410): handleNotificationPosted(true)
D/QuickCircle( 1410): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1410): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1410): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1410): post do just update job
D/LgeQuickCoverNotificationData( 1410): showAll3
D/LgeQuickCoverNotificationData( 1410): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1410): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1410): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1410): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1410): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1410): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1410): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1410): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1410): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1410): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1410): updateNotificationData: count=3
W/GLSActivity( 2157): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2157): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2157): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2157): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2157): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2157): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2157): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 6668): Authentication error
E/BooksAccountManager( 6668): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6668): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6668): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6668): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6668): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6668): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6668): null auth token
D/QuickStatusbarLayout( 1410): Notification difference=198
D/QuickStatusbarLayout( 1410): child = android.widget.LinearLayout{6ebc377 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
W/ApiaryClient( 6668): Error response from books API: {
W/ApiaryClient( 6668):  "error": {
W/ApiaryClient( 6668):   "errors": [
W/ApiaryClient( 6668):    {
W/ApiaryClient( 6668):     "domain": "global",
W/ApiaryClient( 6668):     "reason": "required",
W/ApiaryClient( 6668):     "message": "Login Required",
W/ApiaryClient( 6668):     "locationType": "header",
W/ApiaryClient( 6668):     "location": "Authorization"
W/ApiaryClient( 6668):    }
W/ApiaryClient( 6668):   ],
W/ApiaryClient( 6668):   "code": 401,
W/ApiaryClient( 6668):   "message": "Login Required"
W/ApiaryClient( 6668):  }
W/ApiaryClient( 6668): }
,W/ApiaryClient( 6668): errCount = 2: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6668): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=3841994897377923430&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6668): Headers:
W/ApiaryClient( 6668): accept-encoding: [gzip]
W/ApiaryClient( 6668): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6668): gdata-version: 2
,V/GLSActivity( 2157): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2157): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2157): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2157): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 2157): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2157): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1029): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1029): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1029): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1029): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1029): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1410): onNotificationPosted
,D/SmartCoverUpdateMonitor( 1410): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1410): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1410): handleNotificationPosted(true)
D/QuickCircle( 1410): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1410): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1410): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1410): post do just update job
D/LgeQuickCoverNotificationData( 1410): showAll3
D/LgeQuickCoverNotificationData( 1410): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1410): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1410): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1410): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1410): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1410): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1410): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1410): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1410): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1410): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1410): updateNotificationData: count=3
W/GLSActivity( 2157): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2157): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2157): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2157): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2157): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2157): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2157): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 6668): Authentication error
E/BooksAccountManager( 6668): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6668): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6668): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6668): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6668): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6668): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6668): null auth token
D/QuickStatusbarLayout( 1410): Notification difference=198
D/QuickStatusbarLayout( 1410): child = android.widget.LinearLayout{6ebc377 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
W/ApiaryClient( 6668): Error response from books API: {
W/ApiaryClient( 6668):  "error": {
W/ApiaryClient( 6668):   "errors": [
W/ApiaryClient( 6668):    {
W/ApiaryClient( 6668):     "domain": "global",
W/ApiaryClient( 6668):     "reason": "required",
W/ApiaryClient( 6668):     "message": "Login Required",
W/ApiaryClient( 6668):     "locationType": "header",
W/ApiaryClient( 6668):     "location": "Authorization"
W/ApiaryClient( 6668):    }
W/ApiaryClient( 6668):   ],
W/ApiaryClient( 6668):   "code": 401,
W/ApiaryClient( 6668):   "message": "Login Required"
W/ApiaryClient( 6668):  }
W/ApiaryClient( 6668): }
,W/ApiaryClient( 6668): errCount = 3: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6668): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=3841994897377923430&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6668): Headers:
W/ApiaryClient( 6668): accept-encoding: [gzip]
W/ApiaryClient( 6668): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6668): gdata-version: 2
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-65 f=2412 sc=60 link=65 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3000] from screen [on:0 period:-1396508998] gl rssi=-65 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-65 f=2412 sc=60 link=65 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:5] from screen [on:0 period:-1396508993] gl rssi=-65 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,E/BooksSync( 6668): Soft error: 
E/BooksSync( 6668): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 6668): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=3841994897377923430&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 6668): Headers:
E/BooksSync( 6668): accept-encoding: [gzip]
E/BooksSync( 6668): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 6668): gdata-version: 2
E/BooksSync( 6668): 
E/BooksSync( 6668): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 6668): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 6668): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 6668): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 6668): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 6668): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 6668): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 6668): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 6668): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 6668): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 6668): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 6668): {
E/BooksSync( 6668):  "error": {
E/BooksSync( 6668):   "errors": [
E/BooksSync( 6668):    {
E/BooksSync( 6668):     "domain": "global",
E/BooksSync( 6668):     "reason": "required",
E/BooksSync( 6668):     "message": "Login Required",
E/BooksSync( 6668):     "locationType": "header",
E/BooksSync( 6668):     "location": "Authorization"
E/BooksSync( 6668):    }
E/BooksSync( 6668):   ],
E/BooksSync( 6668):   "code": 401,
E/BooksSync( 6668):   "message": "Login Required"
E/BooksSync( 6668):  }
E/BooksSync( 6668): }
E/BooksSync( 6668): 
E/BooksSync( 6668): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 6668): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 6668): 	... 8 more
,E/BooksSync( 6668): Sync error
E/BooksSync( 6668): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 6668): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=3841994897377923430&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 6668): Headers:
E/BooksSync( 6668): accept-encoding: [gzip]
E/BooksSync( 6668): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 6668): gdata-version: 2
E/BooksSync( 6668): 
E/BooksSync( 6668): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 6668): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 6668): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 6668): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 6668): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 6668): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 6668): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 6668): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 6668): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 6668): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 6668): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 6668): {
E/BooksSync( 6668):  "error": {
E/BooksSync( 6668):   "errors": [
E/BooksSync( 6668):    {
E/BooksSync( 6668):     "domain": "global",
E/BooksSync( 6668):     "reason": "required",
E/BooksSync( 6668):     "message": "Login Required",
E/BooksSync( 6668):     "locationType": "header",
E/BooksSync( 6668):     "location": "Authorization"
E/BooksSync( 6668):    }
E/BooksSync( 6668):   ],
E/BooksSync( 6668):   "code": 401,
E/BooksSync( 6668):   "message": "Login Required"
E/BooksSync( 6668):  }
E/BooksSync( 6668): }
E/BooksSync( 6668): 
E/BooksSync( 6668): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 6668): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 6668): 	... 8 more
I/BooksSync( 6668): Finished books sync
D/SyncManager( 1029): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 253232, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/sensors_hal_Time( 1029): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1029): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1029): tsOffsetIs: Apps: 257447811676; DSPS: 8576862; Offset : -4312470229
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-65 f=2412 sc=60 link=65 tx=3.8, 0.0, 0.0  rx=4.8 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1396505974] gl rssi=-65 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-65 f=2412 sc=60 link=65 tx=3.8, 0.0, 0.0  rx=4.8 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1396505971] gl rssi=-65 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-65 f=2412 sc=60 link=65 tx=1.9, 0.0, 0.0  rx=2.4 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1396502949] gl rssi=-65 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-65 f=2412 sc=60 link=65 tx=1.9, 0.0, 0.0  rx=2.4 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-1396502939] gl rssi=-65 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-65 f=2412 sc=60 link=65 tx=1.5, 0.0, 0.0  rx=1.7 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1396499919] gl rssi=-65 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-65 f=2412 sc=60 link=65 tx=1.5, 0.0, 0.0  rx=1.7 bcn=0 [on:0 tx:0 rx:0 period:13] from screen [on:0 period:-1396499906] gl rssi=-65 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-65 f=2412 sc=60 link=65 tx=0.7, 0.0, 0.0  rx=0.9 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1396496889] gl rssi=-65 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-65 f=2412 sc=60 link=65 tx=0.7, 0.0, 0.0  rx=0.9 bcn=0 [on:0 tx:0 rx:0 period:12] from screen [on:0 period:-1396496877] gl rssi=-65 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-65 f=2412 sc=60 link=65 tx=0.9, 0.0, 0.0  rx=0.9 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1396493856] gl rssi=-65 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-65 f=2412 sc=60 link=65 tx=0.9, 0.0, 0.0  rx=0.9 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-1396493855] gl rssi=-65 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,I/jxcore-log( 6110): --= Surplus to requirements =--
I/jxcore-log( 6110): 
I/jxcore-log( 6110): ****TEST TOOK:  ms ****
I/jxcore-log( 6110): 
I/jxcore-log( 6110): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 6110): 
,D/AndroidRuntime( 7483): 
D/AndroidRuntime( 7483): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime( 7483): CheckJNI is OFF
D/AndroidRuntime( 7483): Calling main entry com.android.commands.pm.Pm
,I/ActivityManager( 1029): Force stopping com.test.thalitest appid=10311 user=-1: uninstall pkg
I/ActivityManager( 1029): Killing 6110:com.test.thalitest/u0a311 (adj 0): stop com.test.thalitest
,I/WindowState( 1029): WIN DEATH: Window{2517202 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,D/WifiService( 1029): Client connection lost with reason: 4
D/InputDispatcher( 1029): Window went away: Window{2517202 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,W/PackageSettings( 1029): Skipping PackageSetting{1df3bbb4 com.example.hello/10319} due to missing metadata
,I/ActivityManager( 1029):   Force finishing activity ActivityRecord{35a0df8f u0 com.test.thalitest/.MainActivity t4}
,E/GBMv2   (  347): DFP En is all cleared set to be enabled
,W/ActivityManager( 1029): Spurious death for ProcessRecord{2536d777 6110:com.test.thalitest/u0a311}, curProc for 6110: null
,I/ActivityManager( 1029): Force stopping com.test.thalitest appid=10311 user=0: pkg removed
I/ActivityManager( 1029):   Force finishing activity ActivityRecord{35a0df8f u0 com.test.thalitest/.MainActivity t4 f}
W/ActivityManager( 1029): Duplicate finish request for ActivityRecord{35a0df8f u0 com.test.thalitest/.MainActivity t4 f}
,I/[LGHome]EVENT( 2078): [Launcher.java:5338:onStart()]onStart
D/SplitWindowPolicy( 1958): updateActivityStateChanged: resumed=false, screenId=0, isScreenFull=false
,I/[LGHome]EVENT( 2078): [Launcher.java:903:onResume()]onResume
I/[LGHome]EVENT( 2078): [LauncherModel.java:1352:startLoader()]startLoader isLaunching=true
D/SplitWindowPolicy( 1958): topRunningActivity=ActivityInfo{2591980c co.....Launcher}, taskId=3, activityType=1, bIsSplit=false
,I/[LGHome]Launcher.Model( 2078): [LauncherModel.java:1469:loadAndBindWorkspace()]loadAndBindWorkspace=3ms
D/SplitWindowPolicy( 1958): updateActivityStateChanged: resumed=true, screenId=0, isScreenFull=false
D/SplitWindowPolicy( 1958): topRunningActivity=ActivityInfo{999555 co.....Launcher}, taskId=3, activityType=1, bIsSplit=false
I/[LGHome]GBoardWebView( 2078): [GBoardWebView.java:306:loadCacheBitmapPostDelayed()]loadCacheBitmapPostDelayed() delay:1
D/ActionManagerService( 1912): notifyUserLog: 1000003
D/LIA_Informant_ActionManagerMessageHandler( 3581): handleMessage: what(1000) actionID(0x1000003)
,I/[LGHome]LGActivityUtil( 2078): [LGActivityUtil.java:319:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
I/[LGHome]EVENT( 2078): [Launcher.java:1056:onResume()]onResume end
D/KeyguardModel( 1464): mPackageIntentReceiver, received action: android.intent.action.PACKAGE_REMOVED, sendingUserId:0
D/LIA_Service_RemotePackageHandler( 2034): onReceive action : android.intent.action.PACKAGE_REMOVED = package:com.test.thalitest
D/LIA_MrGDBLogger_PackageInfoDetector( 3581): [dreamwood]action: android.intent.action.PACKAGE_REMOVED, package: com.test.thalitest
E/LGBluetoothAvrcpQcomAdapter( 6167): [BTUI] [BTUI] onReceive()... android.intent.action.PACKAGE_REMOVED
D/LGBluetoothAvrcpQcomAdapter( 6167): [BTUI] [+] updateMediaPlayerInfo
,W/GeofencerStateMachine( 1826): Ignoring removeGeofence because network location is disabled.
I/ActivityManager( 1029): Start proc com.wsandroid.suite.lge for broadcast com.wsandroid.suite.lge/com.wavesecure.core.WSAndroidSystemIntentReceiver: pid=7514 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
I/art     ( 4282): Explicit concurrent mark sweep GC freed 21918(1270KB) AllocSpace objects, 0(0B) LOS objects, 34% free, 29MB/45MB, paused 602us total 94.204ms
,I/[LGHome]EVENT( 2078): [Launcher.java:1114:onPause()]onPause
I/InputReader( 1029): Reconfiguring input devices.  changes=0x00000010
I/[LGHome]GBoardWebView( 2078): [GBoardWebView.java:247:writeCacheBitmapPostDelayed()]writeCacheBitmapPostDelayed() delay: we don't have a change point1
,V/BoardContentProvider( 3581): query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
D/ActionManagerService( 1912): notifyUserLog: 1000004
I/[SystemUI]QSlideListController( 1464): onReceive = android.intent.action.PACKAGE_REMOVED
D/LIA_Informant_ActionManagerMessageHandler( 3581): handleMessage: what(1000) actionID(0x1000004)
I/GBoardWebViewUtils( 2078): checkExpiredAndRemoveCard() card: GBoardCard = { id: mw_initial
I/GBoardWebViewUtils( 2078): , create_time: 1430558575574
I/GBoardWebViewUtils( 2078): , expire_time: 0
I/GBoardWebViewUtils( 2078): , raw_uri: file:///system/etc/mrg_default_forms/MyWellness/initial/initial.html?id=mw_initial
I/GBoardWebViewUtils( 2078): , category: com.lge.intent.category.gboard.MYWELLNESS
I/GBoardWebViewUtils( 2078): , display: false
I/GBoardWebViewUtils( 2078): , animation: false }
I/GBoardWebViewUtils( 2078): checkExpiredAndRemoveCard() card: GBoardCard = { id: dyk000
I/GBoardWebViewUtils( 2078): , create_time: 1430558575600
I/GBoardWebViewUtils( 2078): , expire_time: 0
I/GBoardWebViewUtils( 2078): , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
I/GBoardWebViewUtils( 2078): , category: com.lge.intent.category.gboard.DOYOUKNOW
I/GBoardWebViewUtils( 2078): , display: false
I/GBoardWebViewUtils( 2078): , animation: false }
I/GBoardWebViewUtils( 2078): checkExpiredAndRemoveCard() card: GBoardCard = { id: guide_1111111111116_1453982949437
I/GBoardWebViewUtils( 2078): , create_time: 1453982950152
I/GBoardWebViewUtils( 2078): , expire_time: 0
I/GBoardWebViewUtils( 2078): , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/4/userguide.html?id=guide_1111111111116_1453982949437&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
I/GBoardWebViewUtils( 2078): , category: com.lge.intent.category.gboard.DOYOUKNOW
I/GBoardWebViewUtils( 2078): , display: false
I/GBoardWebViewUtils( 2078): , animation: false }
D/KeyguardModel( 1464): package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
D/KeyguardModel( 1464): createShortcutInfo...
D/WallpaperManager( 2078): suggestDesiredDimensions(2880, 2560) by package(com.lge.launcher2)
W/System.err( 4241): android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
,W/System.err( 4241): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
W/System.err( 4241): 	at com.lge.mlt.MptOnAppWatcher$1.onReceive(MptOnAppWatcher.java:44)
W/System.err( 4241): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:956)
W/System.err( 4241): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 4241): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 4241): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 4241): 	at android.app.ActivityThread.main(ActivityThread.java:5274)
W/System.err( 4241): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 4241): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 4241): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
W/System.err( 4241): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
D/KeyguardModel( 1464): package = com.android.mms, class = com.android.mms.ui.ConversationList
D/KeyguardModel( 1464): createShortcutInfo...
I/[SystemUI]AppWidgetPanel(QRemoteWidgetPanel)( 1464): onReceive = android.intent.action.PACKAGE_REMOVED, packageName : com.test.thalitest
D/KeyguardModel( 1464): mPackageIntentReceiver, received action: android.intent.action.PACKAGE_FULLY_REMOVED, sendingUserId:0
W/ResourcesManager( 1464): Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
W/ResourcesManager( 1464): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 1464): Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
,W/ResourcesManager( 1464): Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
I/SystemUI[Framework]( 1029): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x8000, pkg=com.android.systemui
W/ResourceType( 1464): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1464): Failure retrieving resources for com.android.mms: Resource ID #0x0
W/PhoneWindowManagerEx( 1029): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx( 1029): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx( 1029): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework]( 1029): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@982b9e2,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework]( 1029): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
D/SplitUIManager( 1878): split_name #11 / not available #0
,D/SplitUIService( 1878): removed split : 
I/[LGHome]GBoardWebView( 2078): [GBoardWebView.java:321:loadCacheBitmap()]loadCacheBitmap()
D/KeyguardModel( 1464): package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
D/KeyguardModel( 1464): createShortcutInfo...
,W/ResourcesManager( 1464): Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
W/ResourcesManager( 1464): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourceType( 1464): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1464): Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
D/KeyguardModel( 1464): package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
D/KeyguardModel( 1464): createShortcutInfo...
W/ResourcesManager( 1464): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 1464): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 1464): Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
W/ResourcesManager( 1464): Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
W/ResourceType( 1464): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1464): Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
D/KeyguardModel( 1464): package = com.lge.camera, class = com.lge.camera.CameraApp
D/KeyguardModel( 1464): createShortcutInfo...
D/SplitUIManager( 1878): split_name #11 / not available #0
I/SplitUIService( 1878): split app #11
,I/art     ( 1029): Explicit concurrent mark sweep GC freed 50303(2MB) AllocSpace objects, 9(784KB) LOS objects, 33% free, 44MB/66MB, paused 8.921ms total 208.732ms
I/art     ( 1029): WaitForGcToComplete blocked for 203.702ms for cause Explicit
,D/KeyguardModel( 1464): handleShortcutListChanged...
,D/KeyguardModel( 1464): package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
D/KeyguardModel( 1464): createShortcutInfo...
D/KeyguardModel( 1464): package = com.android.mms, class = com.android.mms.ui.ConversationList
D/KeyguardModel( 1464): createShortcutInfo...
V/SIM_STK ( 1029): Menu title from STK is T-Mobile
I/[LGHome]EVENT( 2078): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,W/ResourcesManager( 7514): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
V/SIM_STK ( 1029): Menu title from STK is T-Mobile
V/SIM_STK ( 1029): Menu title from STK is T-Mobile
I/[LGHome]EVENT( 2078): [Launcher.java:5349:onStop()]onStop
W/ResourceType( 1464): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1464): Failure retrieving resources for com.android.mms: Resource ID #0x0
D/KeyguardModel( 1464): package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
D/KeyguardModel( 1464): createShortcutInfo...
W/ResourceType( 1464): No package identifier when getting value for resource number 0x00000000
,W/PackageManager( 1464): Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
D/KeyguardModel( 1464): package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
D/KeyguardModel( 1464): createShortcutInfo...
W/ResourceType( 1464): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1464): Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
D/KeyguardModel( 1464): package = com.lge.camera, class = com.lge.camera.CameraApp
D/KeyguardModel( 1464): createShortcutInfo...
D/KeyguardModel( 1464): handleShortcutListChanged...
D/PluginManager( 7514): init()
,W/ActivityManager( 1029): getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
D/LGBluetoothAvrcpQcomAdapter( 6167): [BTUI] installed app name: Music
D/LGBluetoothAvrcpQcomAdapter( 6167): [BTUI] installed app name: Google Play Music
D/LGBluetoothAvrcpQcomAdapter( 6167): [BTUI] === MediaPlayerInfo (playerId:0) ===
D/LGBluetoothAvrcpQcomAdapter( 6167): [BTUI]          displayName: Music
D/LGBluetoothAvrcpQcomAdapter( 6167): [BTUI]          packageName: com.lge.music
D/LGBluetoothAvrcpQcomAdapter( 6167): [BTUI]          playState: 2 (PAUSED)
D/LGBluetoothAvrcpQcomAdapter( 6167): [BTUI] === MediaPlayerInfo (playerId:1) ===
D/LGBluetoothAvrcpQcomAdapter( 6167): [BTUI]          displayName: Google Play Music
D/LGBluetoothAvrcpQcomAdapter( 6167): [BTUI]          packageName: com.google.android.music
D/LGBluetoothAvrcpQcomAdapter( 6167): [BTUI]          playState: 2 (PAUSED)
D/LGBluetoothAvrcpQcomAdapter( 6167): [BTUI] [-] updateMediaPlayerInfo
D/administrator( 1029): Handling package changes for user 0
,I/[LGHome]Launcher.Model( 2078): [LauncherModel.java:2230:run()] LauncherModel bind current page shortcut
I/[LGHome]Launcher( 2078): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/[LGHome]EVENT( 2078): [Workspace.java:918:addInScreen()]Add Shortcut [Email] in screen 1 [1, 4]
I/[LGHome]EVENT( 2078): [Workspace.java:918:addInScreen()]Add Shortcut [Play Store] in screen 1 [2, 4]
I/[LGHome]EVENT( 2078): [Workspace.java:918:addInScreen()]Add Shortcut [Camera] in screen 1 [3, 4]
I/[LGHome]EVENT( 2078): [Workspace.java:918:addInScreen()]Add Shortcut [Settings] in screen 1 [4, 4]
,I/Timeline( 1029): Timeline: Activity_windows_visible id: ActivityRecord{92d7761 u0 com.lge.launcher2/.Launcher t3} time:272572
V/SIM_STK ( 1029): Menu title from STK is T-Mobile
I/[LGHome]Launcher.Model( 2078): [LauncherModel.java:2244:run()] LauncherModel bind current page shortcut
I/[LGHome]Launcher( 2078): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 2078): [LGUnreadLgeEmailsBadge.java:107:countUnreadItems()]setTotalCount : 0
I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 2078): [LGUnreadLgeEmailsBadge.java:108:countUnreadItems()]countUnreadItems() ended..
,I/[LGHome]EVENT( 2078): [Workspace.java:918:addInScreen()]Add Folder [Google] in screen 1 [0, 4]
I/[LGHome]Launcher.Model( 2078): [LauncherModel.java:2256:run()] LauncherModel bind current page widget
I/[LGHome]Launcher( 2078): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,I/[Concierge]WidgetView( 2078): ConciergeWidgetView is instantiated. sIsWidgetAttached : true
D/[Concierge]Service( 2605): onStartCommand(). Type : 8
D/[Concierge]Service( 2605): Update widget. Component : {com.lge.concierge/com.lge.concierge.ConciergeWidgetProvider}
D/[Concierge]Service( 2605): Update widget ID : 11
D/[Concierge]WidgetView( 2078): change position of spinner
I/[Concierge]WidgetView( 2078): initWebView(). Time : 1454597420797
D/[Concierge]Service( 2605): onStartCommand(). Type : 0
,I/NotificationService( 1029): action=android.intent.action.PACKAGE_REMOVED queryReplace=false
D/BackupManagerService( 1029): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/JobSchedulerService( 1029): Receieved: android.intent.action.PACKAGE_REMOVED
D/TaskPersister( 1029): removeObsoleteFile: deleting file=4_task.xml
D/PhoneStatusBar( 1464): setSystemUiVisibility vis=8000 mask=ffffffff oldVal=0 newVal=8000 diff=8000
I/[SystemUI]NavigationThemeResource( 1464): NavigationKey Color is changed(BLACK -> WHITE_WITH_SHADOW)
I/[SystemUI]NavigationThemeResource( 1464):  BarMode=4, Theme=WHITE, LightBackground=false (Transparent)
I/[SystemUI]NavigationThemeResource( 1464): , Keyguard show=false, IME shown=false, Panel expanded=false
I/[Concierge]WebView( 2078): Return exist ConciergeWebView. Reuse : 14802317
D/[Concierge]WidgetView( 2078): State Change : null -> AccInBeforeState
I/[LgeWidgetLib]LgeAppWidgetHostView( 2078): [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
I/[LgeWidgetLib]ExtViewHost( 2078): [LgeAppWidgetExtViewHost.java:136:setState()]New State = com.lge.lgewidgetlib.extview.NormalState@12d7df75
I/[LGHome]EVENT( 2078): [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.concierge.ConciergeWidgetProvider] in screen 1 [0, 0]
I/[LGHome]Launcher.Model( 2078): [LauncherModel.java:2256:run()] LauncherModel bind current page widget
I/[LGHome]Launcher( 2078): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,I/[LGHome]EVENT( 2078): [Workspace.java:918:addInScreen()]Add AppWidget [com.google.android.googlequicksearchbox.SearchWidgetProvider] in screen 1 [0, 2]
D/[Concierge]WidgetBroadcastReceiver( 2078): New receiver registered. Self-unregister old one. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
W/[Concierge]WidgetView( 2078): Widget kill message received. Destory myself. My : 1454597176198, New one : 1454597420797
,D/[Concierge]WidgetView( 2078): Unregister all receivers
W/[Concierge]WidgetBroadcastReceiver( 2078): Tried unregister broadcastReceiver which is not registered. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
D/[Concierge]WidgetView( 2078): isWidgetUpdateSkippable ? true
I/[LGHome]Launcher( 2078): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/[LGHome]EVENT( 2078): [Workspace.java:918:addInScreen()]Add Shortcut [Gallery] in screen 2 [0, 4]
I/[LGHome]EVENT( 2078): [Workspace.java:918:addInScreen()]Add Shortcut [Calendar] in screen 2 [1, 4]
I/[LGHome]EVENT( 2078): [Workspace.java:918:addInScreen()]Add Shortcut [QuickMemo+] in screen 2 [2, 4]
I/[LGHome]EVENT( 2078): [Workspace.java:918:addInScreen()]Add Shortcut [Quick Remote] in screen 2 [3, 4]
I/[LGHome]EVENT( 2078): [Workspace.java:918:addInScreen()]Add Shortcut [FM Radio] in screen 2 [4, 4]
I/[LGHome]Launcher( 2078): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/[LGHome]Launcher( 2078): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/art     ( 1029): Explicit concurrent mark sweep GC freed 8282(446KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 44MB/66MB, paused 1.733ms total 223.241ms
I/[LgeWidgetLib]LgeAppWidgetHostView( 2078): [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
,E/[LgeWidgetLib]LgeAppWidgetHostView( 2078): [LgeAppWidgetHostView.java:124:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
I/[LGHome]EVENT( 2078): [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1] in screen 2 [0, 0]
I/[LGHome]Launcher( 2078): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,I/Timeline( 2078): Timeline: Activity_idle id: android.os.BinderProxy@1b913f80 time:272741
,D/AndroidRuntime( 7483): Shutting down VM
,W/ResourcesManager( 1029): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourceType( 1029): Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
I/[LGHome]EVENT( 2078): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
W/ExternalStrings( 7514): load override strings
W/ExternalStrings( 7514): java.lang.RuntimeException: Unexpected tag, got eat-comment
W/ExternalStrings( 7514): 	at com.mcafee.plugin.af.a(Unknown Source)
W/ExternalStrings( 7514): 	at com.mcafee.plugin.ac.b(Unknown Source)
W/ExternalStrings( 7514): 	at com.mcafee.plugin.ak.d(Unknown Source)
W/ExternalStrings( 7514): 	at com.mcafee.plugin.ak.a(Unknown Source)
W/ExternalStrings( 7514): 	at com.mcafee.app.s.getClassLoader(Unknown Source)
W/ExternalStrings( 7514): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5001)
W/ExternalStrings( 7514): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4609)
W/ExternalStrings( 7514): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4549)
W/ExternalStrings( 7514): 	at android.app.ActivityThread.access$1500(ActivityThread.java:148)
W/ExternalStrings( 7514): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1344)
W/ExternalStrings( 7514): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/ExternalStrings( 7514): 	at android.os.Looper.loop(Looper.java:135)
W/ExternalStrings( 7514): 	at android.app.ActivityThread.main(ActivityThread.java:5274)
W/ExternalStrings( 7514): 	at java.lang.reflect.Method.invoke(Native Method)
W/ExternalStrings( 7514): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/ExternalStrings( 7514): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
W/ExternalStrings( 7514): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
,D/StatusProvider( 7514): onCreate
V/Signer  ( 7514): override build config not found
D/Signer  ( 7514): value of property debug is false
,D/LGMDMWrapper( 7514): Found class 'com.mcafee.lgmdm.LGMDMWrapper$DataWipe'.
D/LGMDMWrapper( 7514): Found class 'com.mcafee.lgmdm.LGMDMWrapper$DownloadMode'.
D/LGMDMWrapper( 7514): Found class 'com.mcafee.lgmdm.LGMDMWrapper$HardReset'.
D/LGMDMWrapper( 7514): Found class 'com.mcafee.lgmdm.LGMDMWrapper$HardwareKeyReset'.
D/LGMDMWrapper( 7514): Found class 'com.mcafee.lgmdm.LGMDMWrapper$RemoveDeviceAdmin'.
D/LGMDMWrapper( 7514): Found class 'com.mcafee.lgmdm.LGMDMWrapper$UnknownSourceInstallation'.
D/LGMDMWrapper( 7514): Found class 'com.mcafee.lgmdm.LGMDMWrapper$Usb'.
,D/LGMDMWrapper( 7514): Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbDebugging'.
D/LGMDMWrapper( 7514): Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbHostStorage'.
D/LGMDMWrapper( 7514): Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbMediaTransfer'.
D/LGMDMWrapper( 7514): Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbPictureTransfer'.
D/LGMDMWrapper( 7514): Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbStorage'.
D/LGMDMWrapper( 7514): Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbTethering'.
,V/LGMDMManager( 7514): Create singleton instance
D/LGMDMWrapper( 7514): LG MDM library v4.0.0 is available on this device.
I/chromium( 2078): [INFO:CONSOLE(0)] "'window.webkitStorageInfo' is deprecated. Please use 'navigator.webkitTemporaryStorage' or 'navigator.webkitPersistentStorage' instead.", source:  (0)
,I/GBoardtInterface( 2078): onReloaded()
,I/GBoardWebViewClient( 2078): onPageFinished url:file:///android_asset/www/main.html
V/BoardContentProvider( 3581): query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
D/PostponalbeReceiver( 7514): WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.intent.action.PACKAGE_REMOVED'.
W/ContextImpl( 7514): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
V/BoardContentProvider( 3581): query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
,D/ActionManagerService( 1912): notifyUserLog: 1000001
D/LIA_Informant_ActionManagerMessageHandler( 3581): handleMessage: what(1000) actionID(0x1000001)
D/LIA_Informant_Tips_SmartTipsActionManager( 3581): onEvent() : ACTION_BOARD_ENABLED
D/ActionManagerService( 1912): notifyUserLog: 1000001
,D/LIA_Informant_ActionManagerMessageHandler( 3581): handleMessage: what(1000) actionID(0x1000001)
D/LIA_Informant_Tips_SmartTipsActionManager( 3581): onEvent() : ACTION_BOARD_ENABLED
D/LIA_Informant_Tips_FormEventRepository( 3581): getSize() : size - 0
D/LIA_Informant_Tips_SmartTipsActionManager( 3581): onSettingEvent() : GBoard On - add scheduler - 0
V/BoardContentProvider( 3581): query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
D/AppUp4:PreloadHelper( 7210): added Exclude : com.test.thalitest
I/ActivityManager( 1029): Killing 6975:com.qualcomm.timeservice/1000 (adj 15): empty #17
W/ActivityThread( 7514): ClassLoader.getResources: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/libprocessgroup( 1029): failed to open /acct/uid_1000/pid_6975/cgroup.procs: No such file or directory
D/GBoardUriUtils( 2078): fileExists: file:///system/etc/mrg_default_forms/MyWellness/initial/initial2.html?id=mw_initial return true
D/GBoardWebViewUtils( 2078): changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyWellness/initial/initial2.html?id=mw_initial
E/SQLiteLog( 2257): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
D/ContactsProvider2ForLG( 2257): performBackgroundTask SQLiteDiskIOException during query
D/ContactsProvider2ForLG( 2257): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
D/ContactsProvider2ForLG( 2257): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
D/ContactsProvider2ForLG( 2257): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:560)
D/ContactsProvider2ForLG( 2257): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
D/ContactsProvider2ForLG( 2257): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
D/ContactsProvider2ForLG( 2257): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
D/ContactsProvider2ForLG( 2257): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
D/ContactsProvider2ForLG( 2257): 	at com.android.providers.contacts.ContactDirectoryManager.updateDirectoriesForPackage(ContactDirectoryManager.java:394)
D/ContactsProvider2ForLG( 2257): 	at com.android.providers.contacts.ContactDirectoryManager.onPackageChanged(ContactDirectoryManager.java:363)
D/ContactsProvider2ForLG( 2257): 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:974)
D/ContactsProvider2ForLG( 2257): 	at com.android.providers.contacts.ContactsProvider2ForLG.performBackgroundTask(ContactsProvider2ForLG.java:375)
D/ContactsProvider2ForLG( 2257): 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:748)
D/ContactsProvider2ForLG( 2257): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/ContactsProvider2ForLG( 2257): 	at android.os.Looper.loop(Looper.java:135)
D/ContactsProvider2ForLG( 2257): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,D/GBoardUriUtils( 2078): fileExists: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial2.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc] return true
D/GBoardWebViewUtils( 2078): changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial2.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
D/VoicemailCleanupService( 2257): Cleaning up data for package: com.test.thalitest
D/GBoardUriUtils( 2078): fileExists: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/4/userguide2.html?id=guide_1111111111116_1453982949437&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay return true
D/GBoardWebViewUtils( 2078): changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/4/userguide2.html?id=guide_1111111111116_1453982949437&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
E/SQLiteLog( 2257): (3850) statement aborts at 37: [DELETE FROM calls WHERE (((source_package = 'com.test.thalitest'))) AND ((type = 4))] disk I/O error

```
