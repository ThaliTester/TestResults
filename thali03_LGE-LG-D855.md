#### Test 58135655c662d33_thali03_LGE-LG-D855 Logs


```
--------- beginning of system
D/PowerManagerServiceEx( 1032): acquireWakeLockInternal: lock=58637760, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1032
,V/AlarmManager( 1032): RTC_WAKEUP set : Alarm{147d6a3e type 0 when 1454523187322 com.android.vending} when 1454523187322
--------- beginning of main
D/[Concierge]Service( 2591): onStartCommand(). Type : 9
D/PowerManagerServiceEx( 1032): releaseWakeLockInternal: lock=58637760 [*alarm*], flags=0x0
W/ContextImpl( 4169): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 com.lge.mlt.MptOnLogDumper.run:279 <bottom of call stack> <bottom of call stack> 
V/SIM_STK ( 1032): Menu title from STK is T-Mobile
D/AndroidRuntime( 6028): 
D/AndroidRuntime( 6028): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 6028): CheckJNI is OFF
D/AndroidRuntime( 6028): Calling main entry com.android.commands.am.Am
I/ActivityManager( 1032): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
V/SplitWindowPolicy( 1915): checkScreen => return. sourceIntent is null or not support SplitWindow component: ComponentInfo{co..../co.....MainActivity}
D/SplitInfo( 1032): new ActivitySplitInfo : ActivitySplitInfo [screenZone=0/ flag=0/ state=NATIVE]
D/ActivityManager( 1032): setTaskToReturnTo : TaskRecord{19b9509f #4 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
D/ActivityManager( 1032): setTaskToReturnTo : TaskRecord{19b9509f #4 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
D/WindowStateEx( 1032): AppWindowTokenEx init.. 
E/GBMv2   (  342): DFP En is all cleared set to be enabled
I/ActivityManager( 1032): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6067 uid=10311 gids={50311, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
D/AndroidRuntime( 6028): Shutting down VM
V/GLSActivity( 2063): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/ActivityManager( 1032): Display changed displayId=0
D/DSDPConnection( 1825): Display #0 changed.
D/SplitWindowPolicy( 1915): updateActivityStateChanged: resumed=true, screenId=1, isScreenFull=true
D/SplitWindowPolicy( 1915): topRunningActivity=ActivityInfo{3d845b81 co.....MainActivity}, taskId=4, activityType=0, bIsSplit=false
D/SplitWindowPolicy( 1915): updateActivityStateChanged: resumed=false, screenId=1, isScreenFull=true
D/SplitWindowPolicy( 1915): topRunningActivity=ActivityInfo{c027426 co.....MainActivity}, taskId=4, activityType=0, bIsSplit=false
I/GLSUser ( 2063): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 2063): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2063): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2063): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2063): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/Finsky  ( 4869): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 4869): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 4869): [1] 5.onFinished: Scheduling replication attempt 1.
D/ContextHelper( 6067): convertTheme. context->name=com.test.thalitest themeResourceId=16973833
I/WebViewFactory( 6067): Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,I/LibraryLoader( 6067): Loading: webviewchromium
I/LibraryLoader( 6067): Time to load native libraries: 3 ms (timestamps 2952-2955)
I/LibraryLoader( 6067): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 6067): Binding Chromium to main looper Looper (main, tid 1) {3a1928e2}
,I/LibraryLoader( 6067): Expected native library version number "",actual native library version number ""
I/chromium( 6067): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 6067): Initializing chromium process, renderers=0
,W/art     ( 6067): Attempt to remove local handle scope entry from IRT, ignoring
W/chromium( 6067): [WARNING:dns_config_service_posix.cc(293)] Failed to read DnsConfig.
V/AudioPolicyService(  317): registerClient() client 0xb1427900, uid 10311
,W/chromium( 6067): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
,I/chromium( 6067): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=32 off=46780 len=2953
I/chromium( 6067): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:33 off:229536 len:643667
D/BluetoothManagerService( 1032): Message: 20
D/BluetoothManagerService( 1032): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@2af5fbfa:true
D/BluetoothAdapter( 6067): 670528627: getState() :  mService = null. Returning STATE_OFF
I/Adreno-EGL( 6067): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 6067): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 6067): Build Date: 12/12/14 금
I/Adreno-EGL( 6067): Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
I/Adreno-EGL( 6067): Remote Branch: 
I/Adreno-EGL( 6067): Local Patches: 
I/Adreno-EGL( 6067): Reconstruct Branch: 
,W/chromium( 6067): [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
,W/chromium( 6067): [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
W/art     ( 6067): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 6067): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine( 6067): CordovaWebView is running on device made by: LGE
,W/art     ( 6067): Attempt to remove local handle scope entry from IRT, ignoring
,W/art     ( 6067): Attempt to remove local handle scope entry from IRT, ignoring
,D/OpenGLRenderer( 6067): Render dirty regions requested: true
I/OpenGLRenderer( 6067): Initialized EGL, version 1.4
D/OpenGLRenderer( 6067): Enabling debug mode 0
,D/Atlas   ( 6067): Validating map...
D/SplitWindow( 1032): check instance of lgWin Window{20f426e4 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,I/SystemUI[Framework]( 1032): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x0, pkg=com.android.systemui
W/PhoneWindowManagerEx( 1032): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx( 1032): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx( 1032): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework]( 1032): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@14e4efda,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework]( 1032): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
,D/PhoneStatusBar( 1447): setSystemUiVisibility vis=0 mask=ffffffff oldVal=8000 newVal=0 diff=8000
I/[SystemUI]NavigationThemeResource( 1447): NavigationKey Color is changed(WHITE_WITH_SHADOW -> BLACK)
I/[SystemUI]NavigationThemeResource( 1447):  BarMode=0, Theme=WHITE, LightBackground=false (Transparent)
I/[SystemUI]NavigationThemeResource( 1447): , Keyguard show=false, IME shown=false, Panel expanded=false
D/LgDataFeature( 6067): LgDataFeature() Constructor: none
D/LgDataFeature( 6067): LgDataFeature() Constructor Done, null
,I/Timeline( 6067): Timeline: Activity_idle id: android.os.BinderProxy@25266063 time:113361
,I/ActivityManager( 1032): Displayed com.test.thalitest/.MainActivity: +566ms (total +677ms)
,I/Timeline( 1032): Timeline: Activity_windows_visible id: ActivityRecord{2471f5ec u0 com.test.thalitest/.MainActivity t4} time:113367
D/JsMessageQueue( 6067): Set native->JS mode to OnlineEventsBridgeMode
,I/chromium( 6067): [INFO:SkFontConfigInterface_android.cpp(247)] ---- failed to open </system/fonts/CutiveMono.ttf> as a font
I/chromium( 6067): 
,D/jxcore_app_log( 6067): JniHelper::setJavaVM(0xb487c280), pthread_self() = -1435218048
,I/chromium( 6067): [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
I/chromium( 6067): 
,I/chromium( 6067): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
E/GBMv2   (  342): DFP En is all cleared set to be enabled
,E/GBMv2   (  342): Set value is all cleared set the max
I/GBMv2   (  342): DFP Enabled. Ignore VFP set
I/CloudHub( 2112): [CLIENT][CloudHubClientFactory$1|onTick] Until finished: 19984
,W/jxcore-log( 6067): Initializing JXcore engine
W/jxcore-log( 6067): JXcore engine is ready
,W/Thread-689( 6125): type=1400 audit(0.0:146): avc: denied { ioctl } for path="socket:[8501]" dev="sockfs" ino=8501 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
W/Thread-689( 6125): type=1400 audit(0.0:147): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3222 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
W/Thread-689( 6125): type=1400 audit(0.0:148): avc: denied { ioctl } for path="socket:[8654]" dev="sockfs" ino=8654 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
W/Thread-689( 6125): type=1400 audit(0.0:149): avc: denied { ioctl } for path="/cust" dev="mmcblk0p42" ino=2 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=dir
W/Thread-689( 6125): type=1400 audit(0.0:150): avc: denied { ioctl } for path="socket:[29816]" dev="sockfs" ino=29816 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
,W/jxcore-log( 6067): Starting JXcore engine
W/jxcore-log( 6067): Platform android
W/jxcore-log( 6067): 
W/jxcore-log( 6067): Process ARCH arm
W/jxcore-log( 6067): 
,I/jxcore-log( 6067): JXcore Cordova bridge is ready!
I/jxcore-log( 6067): 
,W/jxcore-log( 6067): JXcore engine is started
,I/jxcore-log( 6067): Toggling radios to true
I/jxcore-log( 6067): 
,D/BluetoothManagerService( 1032): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1032): enable():  mBluetooth =null mBinding = false
,D/LocationManagerService( 1032): getAllProviders()=[passive, gps, network]
D/Ulp_jni ( 1032): JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
D/Ulp_jni ( 1032): JNI:system_update. Event-4
D/BluetoothManagerService( 1032): Message: 1
D/BluetoothManagerService( 1032): MESSAGE_ENABLE: mBluetooth = null
D/WifiService( 1032): New client listening to asynchronous messages
I/ActivityManager( 1032): Start proc com.android.bluetooth for service com.android.bluetooth/.btservice.AdapterService: pid=6128 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008, 4002, 1023} abi=armeabi-v7a
,D/WifiServiceImplEx( 1032): setWifiEnabled: true pid=6067, uid=10311, package= com.test.thalitest, App Lable : ThaliTest
D/WifiService( 1032): setWifiEnabled: true pid=6067, uid=10311
E/WifiService( 1032): Invoking mWifiStateMachine.setWifiEnabled
,D/LocationManagerService( 1032): getAllProviders()=[passive, gps, network]
D/Ulp_jni ( 1032): JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 1,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
D/Ulp_jni ( 1032): JNI:system_update. Event-4
E/WifiStateMachine( 1032):  InitialState CMD_START_SUPPLICANT 0 0
I/LGFTMITEM( 1032): [GET_FTM][id=6], offset=12288
D/WifiServiceImplEx( 1032): disconnect pid=6067, uid=10311, packageName=com.test.thalitest
D/WifiServiceImplEx( 1032): reconnect pid=6067, uid=10311, packageName=com.test.thalitest
I/jxcore-log( 6067): Radios toggled
I/jxcore-log( 6067): 
I/jxcore-log( 6067): My device name is: LGE-LG-D855
I/jxcore-log( 6067): 
E/WifiUtil( 1032): wfc_util_ffile_check_copy(): pid[1032] pDestFName[/data/misc/wifi/WCNSS_qcom_cfg.ini] pSourceFName[/system/etc/wifi/WCNSS_qcom_cfg.ini]
E/WifiUtil( 1032): wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
E/WifiUtil( 1032): wfc_util_ffile_check_copy(): pid[1032] pDestFName[/data/misc/wifi/WCNSS_qcom_wlan_nv.bin] pSourceFName[/system/etc/wifi/WCNSS_qcom_wlan_nv.bin]
E/WifiUtil( 1032): wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
I/WifiUtil( 1032): Intf0MacAddress=C49A027B60AC
E/WifiHW  ( 1032): unknown target_country: EU , set to default
E/WifiHW  ( 1032): [wifi_ensure_config_files] default country1 = GB
E/WifiHW  ( 1032): [wifi_ensure_config_files] default country2 = GB
I/WifiUtil( 1032): gEnableBmps=1
,W/ResourcesManager( 6128): Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
,W/ResourcesManager( 6128): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 6128): Asset path '/system/framework/com.qcom.bluetooth.jar' does not exist or contains no resources.
W/ResourcesManager( 6128): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
D/BluetoothAdapterApp( 6128): Loading JNI Library
,D/SoftapController(  313): Softap fwReload - Ok
,D/Tethering( 1032): sendTetherStateChangedBroadcast 1, 0, 0
D/libc-netbsd(  313): default dns: query_ipv6=0, query_ipv4=0
D/DSQN    ( 1032): DNSproblemNotiEnabled is disabled ignore DNS fail CB
,D/CommandListener(  313): Setting iface cfg
D/CommandListener(  313): Trying to bring down wlan0
D/CommandListener(  313): Clearing all IP addresses on wlan0
E/WifiHW  ( 1032): Cannot open "/system/etc/wifi/autojoinconfig.txt": No such file or directory
,E/WifiStateMachine( 1032): Couldn't get getWiFiOffloadingIface : 
E/WifiStateMachine( 1032): useWiFiOffloading() : false
E/WifiStateMachine( 1032): CONFIG_LGE_WLAN_PATH : true
I/ActivityManager( 1032): Start proc com.android.settings for broadcast com.android.settings/.deviceinfo.UsbSettingsReceiver: pid=6167 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
D/WifiMonitor( 1032): startMonitoring(wlan0) with mConnected = false
D/WifiMonitor( 1032): connecting to supplicant
I/WifiServerServiceExt( 1032): WIFI_STATE_CHANGED_ACTION [2]
W/wpa_supplicant( 6166): type=1400 audit(0.0:151): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6843 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
W/wpa_supplicant( 6166): type=1400 audit(0.0:152): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6843 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,V/WfdStateTracker( 1915): WfdStateTracker handleDirectStateChangedEvent: 1
D/StatusBar.NetworkController( 1447): refreshViews: Data not connected!! Set no data type icon / Roaming
D/BluetoothAdapterApp( 6128): REFCOUNT: Constructed com.android.bluetooth.btservice.AdapterApp@22f98d56 Instance Count = 1
,I/wpa_supplicant( 6166): Successfully initialized wpa_supplicant
D/BluetoothAdapterApp( 6128): onCreate
I/wpa_supplicant( 6166): rfkill: Cannot open RFKILL control device
I/wpa_supplicant( 6166): [LGE_PATCH] unset P2P_CAPABLE to ifname wlan0
D/Tethering( 1032): InitialState.processMessage what=4
D/Tethering( 1032): sendTetherStateChangedBroadcast 0, 0, 0
,D/ProfileConfigQcom( 6128): [BTUI] HeadsetService is supported
D/ProfileConfigQcom( 6128): Adding HeadsetService
D/ProfileConfigQcom( 6128): [BTUI] A2dpService is supported
D/ProfileConfigQcom( 6128): Adding A2dpService
D/ProfileConfigQcom( 6128): [BTUI] HidService is supported
D/ProfileConfigQcom( 6128): Adding HidService
D/ProfileConfigQcom( 6128): [BTUI] HealthService is supported
D/ProfileConfigQcom( 6128): Adding HealthService
D/LGBluetoothFeatureConfig( 6128): isSupportPan() :  mTargetOp=OPEN
D/ProfileConfigQcom( 6128): [BTUI] PanService is supported
D/ProfileConfigQcom( 6128): Adding PanService
D/ProfileConfigQcom( 6128): [BTUI] GattService is supported
D/ProfileConfigQcom( 6128): Adding GattService
D/ProfileConfigQcom( 6128): [BTUI] BluetoothMapService is supported
D/ProfileConfigQcom( 6128): Adding BluetoothMapService
D/ProfileConfigQcom( 6128): [BTUI] HeadsetClientService is NOT supported
W/ResourcesManager( 6167): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6167): Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
W/ResourcesManager( 6167): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 6167): Asset path '/system/framework/com.lge.bluetooth.jar' does not exist or contains no resources.
,W/ResourcesManager( 6167): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
W/ResourcesManager( 6167): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
D/BluetoothManagerService( 1032): Message: 20
D/BluetoothManagerService( 1032): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@35a4bf67:true
D/BluetoothAdapterState( 6128): make
I/LGFMServiceAdapter( 6128): [FM] LGFMServiceAdapter : create
,I/bluedroid-qcom( 6128): init
I/BluetoothAdapterState( 6128): Entering OffState
I/bte_conf( 6128): bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
I/bte_conf( 6128): bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
E/bt_osi_config( 6128): config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
I/bte_conf( 6128): bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
D/BTIF_CORE( 6128): [BTUI] lge_load_bluetooth_address
I/bluedroid-qcom( 6128): get_profile_interface socket
I/GKI_LINUX( 6128): gki_task_entry task_id=1 [BTIF] starting
I/bluedroid-qcom( 6128): get_profile_interface map_client
W/bdaddr_loader( 6189): type=1400 audit(0.0:153): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6843 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
W/bdaddr_loader( 6189): type=1400 audit(0.0:154): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6843 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
D/BluetoothAdapterProperties( 6128): Address is:58:3F:54:73:64:C0
D/BluetoothManagerService( 1032): Bluetooth Adapter name changed to G3-1
D/BluetoothManagerService( 1032): Stored Bluetooth name: G3-1
,D/lge_bdaddr_loader( 6189): [BTUI] bdaddr_loader ::: START
D/lge_bdaddr_loader( 6189): [BTUI] bluetooth_load_bdaddress
I/LGFTMITEM( 6189): [GET_FTM][id=8], offset=16384
D/lge_bdaddr_loader( 6189): [BTUI] bdaddr to set in property : 58:3F:54:73:64:C0
D/BluetoothAdapterProperties( 6128): Name is: G3-1
D/BluetoothManagerService( 1032): BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
D/BluetoothManagerService( 1032): Message: 40
D/BluetoothManagerService( 1032): MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
I/bluedroid-qcom( 6128): config_hci_snoop_log
D/BluetoothManagerService( 1032): Calling onBluetoothServiceUp callbacks
D/BluetoothManagerService( 1032): Broadcasting onBluetoothServiceUp() to 7 receivers.
E/lge_bdaddr_loader( 6189): [BTUI] bluetooth_load_bdaddress : OK => 58:3F:54:73:64:C0
D/lge_bdaddr_loader( 6189): [BTUI] bdaddr_loader ::: END
V/LGMDMManagerInternal( 6128): Create singleton instance
,D/BluetoothAdapterState( 6128): CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
D/BluetoothAdapterProperties( 6128): Setting state to 11
I/BluetoothAdapterState( 6128): Bluetooth adapter state changed: 10-> 11
,D/BluetoothManagerService( 1032): Message: 60
D/BluetoothManagerService( 1032): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
D/BluetoothManagerService( 1032): Bluetooth State Change Intent: 10 -> 11
I/LGBluetoothServiceJni( 6128): classInitNative: succeeds
I/wpa_supplicant( 6166): rfkill: Cannot open RFKILL control device
D/LGBluetoothAPIService( 1915): [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
I/[SystemUI]BluetoothHandler( 1447): Receive : BluetoothAdapter.ACTION_STATE_CHANGED
D/BluetoothBondStateMachine( 6128): make
D/BluetoothAdapterService( 6128): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2b2e07a9
D/LGBluetoothServiceAdapter( 6128): [BTUI] check adapter is available - false.
D/BluetoothAdapterService( 6128): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2b2e07a9
D/LGBluetoothServiceAdapter( 6128): [BTUI] check adapter is available - true : set adapter available.
D/LGBluetoothSettingsDBObserver( 6128): [BTUI] register observer for LG device name DB
I/BluetoothBondStateMachine( 6128): StableState(): Entering Off State
E/BluetoothAdapterService( 6128): File transfer profiles supported!!
,E/BluetoothAdapterService( 6128): File transfer profiles supported!!
D/BluetoothHeadset( 1032): Proxy object connected
D/BluetoothHeadset( 1825): Proxy object connected
D/BluetoothHeadset( 1825): Proxy object connected
D/BluetoothHeadset( 1825): Proxy object connected
D/HeadsetService( 6128): Received start request. Starting profile...
I/LGBluetoothHeadsetServiceJni( 6128): classInitNative: succeeds
D/LGBluetoothHfpAdapter( 6128): Version 1.6
E/BluetoothAdapterService( 6128): File transfer profiles supported!!
D/LGBluetoothFeatureConfig( 6128): isPrivacyLogsEnabled : true
I/BluetoothHeadsetServiceJni( 6128): classInitNative: succeeds
D/HeadsetStateMachine( 6128): make
E/BluetoothAdapterService( 6128): File transfer profiles supported!!
,E/BluetoothAdapterService( 6128): File transfer profiles supported!!
E/BluetoothAdapterService( 6128): File transfer profiles supported!!
E/BluetoothAdapterService( 6128): File transfer profiles supported!!
D/LgDataFeature( 6128): LgDataFeature() Constructor: none
D/LgDataFeature( 6128): LgDataFeature() Constructor Done, null
,D/HeadsetStateMachine( 6128): max_hf_connections = 1
I/bluedroid-qcom( 6128): get_profile_interface handsfree
V/ToneGenerator( 6128): ToneGenerator constructor: streamType=8, volume=1.000000
V/AudioPolicyService(  317): registerClient() client 0xb14275a0, uid 1002
V/AudioPolicyManager(  317): getOutput() device 2, stream 8, samplingRate 0, format 0, channelMask 3, flags 0
V/AudioPolicyManagerEx(  317): AudioPolicyManagerEx: getOutputForDevice
V/AudioPolicyManagerEx(  317): getOutput() returns output 2
V/AudioSystem( 6128): getOutputSamplingRate() no output descriptor for output 2 in gOutputs
V/AudioFlinger(  317): registerClient() client 0xb57bb700, pid 6128
V/AudioSystem(  317): ioConfigChanged() event 0, ioHandle 4
V/AudioSystem(  317): ioConfigChanged() opening already existing output! 4
V/AudioSystem( 2112): ioConfigChanged() event 0, ioHandle 4
V/AudioSystem( 2112): ioConfigChanged() opening already existing output! 4
V/AudioSystem( 1447): ioConfigChanged() event 0, ioHandle 4
V/AudioSystem( 1447): ioConfigChanged() opening already existing output! 4
V/AudioSystem( 1825): ioConfigChanged() event 0, ioHandle 4
V/AudioSystem( 1825): ioConfigChanged() opening already existing output! 4
V/AudioSystem(  317): ioConfigChanged() event 0, ioHandle 2
V/AudioSystem(  317): ioConfigChanged() opening already existing output! 2
V/AudioSystem( 1032): ioConfigChanged() event 0, ioHandle 4
V/AudioSystem( 1032): ioConfigChanged() opening already existing output! 4
V/AudioSystem( 1032): ioConfigChanged() event 0, ioHandle 2
V/AudioSystem( 1032): ioConfigChanged() opening already existing output! 2
V/AudioSystem( 1447): ioConfigChanged() event 0, ioHandle 2
V/AudioSystem( 1447): ioConfigChanged() opening already existing output! 2
V/AudioSystem( 1825): ioConfigChanged() event 0, ioHandle 2
V/AudioSystem( 1825): ioConfigChanged() opening already existing output! 2
V/AudioSystem( 2112): ioConfigChanged() event 0, ioHandle 2
V/AudioSystem( 2112): ioConfigChanged() opening already existing output! 2
V/AudioSystem( 6128): ioConfigChanged() event 0, ioHandle 4
V/AudioSystem( 6128): ioConfigChanged() new output samplingRate 48000, format 0x1 channel mask 0x3 frameCount 960 latency 80
V/AudioSystem( 6128): ioConfigChanged() event 0, ioHandle 2
V/AudioSystem( 6128): ioConfigChanged() new output samplingRate 48000, format 0x5 channel mask 0x3 frameCount 960 latency 50
V/ToneGenerator( 6128): Create Track: 0xb4928a80
V/AudioTrack( 6128): set(): streamType 8, sampleRate 0, format 0x1, channelMask 0x1, frameCount 0, flags #4, notificationFrames 0, sessionId 0, transferType 1
V/AudioTrack( 6128): set() streamType 8, sampleRate 0, format 1, frameCount 0, flags 0004
V/AudioPolicyManager(  317): getOutputForAttr() usage=3, content=4, tag= flags=00000000
V/AudioPolicyManager(  317): getOutputForAttr() device 2, samplingRate 0, format 0, channelMask 3, flags 0
V/AudioPolicyManagerEx(  317): AudioPolicyManagerEx: getOutputForDevice
V/AudioPolicyManagerEx(  317): getOutput() returns output 2
I/AudioFlinger(  317): isAudioPlaybackHookOn() false
V/AudioPolicyManager(  317): getOutputForAttr() usage=3, content=4, tag= flags=00000000
V/AudioPolicyManager(  317): getOutputForAttr() device 2, samplingRate 48000, format 1, channelMask 1, flags 4
V/AudioPolicyManagerEx(  317): AudioPolicyManagerEx: getOutputForDevice
V/AudioPolicyManagerEx(  317): getOutput() returns output 2
V/AudioSystem( 6128): getLatency() output 2, latency 50
V/AudioSystem( 6128): getFrameCount() output 2, frameCount 960
V/AudioTrack( 6128): createTrack_l() output 2 afLatency 50
V/AudioFlinger(  317): [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
V/AudioSystem( 3268): ioConfigChanged() event 0, ioHandle 4
V/AudioFlinger(  317): [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
V/AudioSystem( 3268): ioConfigChanged() opening already existing output! 4
V/AudioFlinger(  317): [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
V/AudioFlinger(  317): [MABL_AudioFlinger] PlaybackThread::setMABLCo,ntrol(), curLvl = 31 
V/AudioFlinger(  317): createTrack() lSessionId: 16
V/AudioSystem( 3268): ioConfigChanged() event 0, ioHandle 2
V/AudioSystem( 3268): ioConfigChanged() opening already existing output! 2
D/UsbSettingsReceiver( 6167): [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
V/AudioTrack( 6128): AUDIO_OUTPUT_FLAG_FAST successful; frameCount 480
D/UsbSettingsReceiver( 6167): [AUTORUN] sys.usb.config = ptp_only,adb
D/UsbSettingsReceiver( 6167): [AUTORUN] sys.usb.state = ptp_only,adb
V/AudioFlinger(  317): acquiring 16 from 6128, for 6128
V/AudioFlinger(  317):  added new entry for 16
D/UsbSettingsReceiver( 6167): [AUTORUN] persist.sys.usb.config = ptp_only,adb
V/ToneGenerator( 6128): ToneGenerator INIT OK, time: 116517
D/BluetoothAdapterService( 6128): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2b2e07a9
D/UsbSettingsReceiver( 6167): [AUTORUN] onReceive() : app userid = 0, current userid = 0
D/HeadsetStateMachine( 6128): Enter Disconnected: -2, size: 0
D/HeadsetPhoneState( 6128): [BTUI] listenForPhoneState : start = false
D/LGBluetoothHfpManager( 6128): [BTUI] listenForMultiSimPhoneState : start = false
D/HeadsetStateMachine( 6128): [BTUI] change sampling rate to 8000 when device is disconnected
D/BluetoothAdapterService( 6128): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2b2e07a9
V/AudioFlinger(  317): setParameters(): io 0, keyvalue bt_samplerate=8000, calling pid 6128
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
D/BluetoothA2dp( 1032): Proxy object connected
D/A2dpService( 6128): Received start request. Starting profile...
I/BluetoothAvrcpServiceJni( 6128): classInitNative: succeeds
V/Avrcp   ( 6128): make
V/ToneGenerator( 6128): ToneGenerator destructor
V/ToneGenerator( 6128): stopTone
V/ToneGenerator( 6128): Delete Track: 0xb4928a80
V/AudioTrack( 6128): ~AudioTrack, releasing session id from 6128 on behalf of 6128
V/AudioPolicyService(  317): AudioCommandThread() adding release output 2
V/AudioPolicyService(  317): inserting command: 6 at index 0, num commands 0
V/AudioPolicyService(  317): AudioCommandThread() waking up
V/AudioPolicyService(  317): AudioCommandThread() processing release output 2
V/AudioPolicyManager(  317): releaseOutput() 2
V/AudioPolicyService(  317): AudioCommandThread() going to sleep
V/AudioFlinger(  317): PlaybackThread::Track destructor
V/AudioFlinger(  317): removeClient_l() pid 6128, calling pid 317
V/AudioFlinger(  317): releasing 16 from 6128 for 6128
,V/AudioFlinger(  317):  decremented refcount to 0
V/AudioFlinger(  317): purging stale effects
D/Avrcp   ( 6128): [BTUI] Use Native AVRCP : init jni
I/bluedroid-qcom( 6128): get_profile_interface avrcp
V/LGMDMManager( 6128): Create singleton instance
W/Process ( 1032): Unable to open /proc/6193/status
I/BluetoothAdapterState( 6128): Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
D/UsbSettingsControl( 6167): [AUTORUN] getUsbConnected() : connected=true
D/UsbSettingsReceiver( 6167): [AUTORUN] onReceive() : availableList=[wlan0]
D/UsbSettingsReceiver( 6167): [AUTORUN] onReceive() : activeList=[]
D/UsbSettingsReceiver( 6167): [AUTORUN] onReceive() : errorList=[]
D/UsbSettingsControl( 6167): [AUTORUN] isAutorunTimer() : mAutorunChanging=false
D/UsbSettingsReceiver( 6167): [AUTORUN] onReceive() : TetherState Changed=wlan0
D/UsbSettingsControl( 6167): [AUTORUN] setTetherStatus() : status=false
I/ActivityManager( 1032): Killing 5691:com.android.defcontainer/u0a4 (adj 15): empty #17
V/AudioManager( 6128): registerRemoteController: size of Media player list: 0
E/AudioManager( 6128): No RCC entry present to update
E/RemoteController( 6128): Cannot set synchronization mode on an unregistered RemoteController
I/BluetoothAvrcpQcomServiceJni( 6128): classInitQcomNative: succeeds
D/LGBluetoothAvrcpQcomAdapter( 6128): [BTUI] Use QCOM AVRCP 1.5 : init jni, browsing = false
I/BluetoothAvrcpQcomServiceJni( 6128): initQcomNative: succeeds
,I/wpa_supplicant( 6166): [LGE_WLAN_PATCH]P2P 5GHz support level:2(0:no 1:gconly 2:gconly_UNII1 3:full)
I/wpa_supplicant( 6166): p2p0: CTRL-EVENT-AVOID-FREQ ranges=
I/wpa_supplicant( 6166): wlan0: CTRL-EVENT-SCAN-STARTED 
E/WifiStateMachine( 1032):  SupplicantStartingState CMD_SET_OPERATIONAL_MODE 1 0
,D/WifiMonitor( 1032): Event [IFNAME=p2p0 CTRL-EVENT-AVOID-FREQ ranges=]
D/WifiMonitor( 1032): Dropping event because (p2p0) is stopped
D/WifiMonitor( 1032): Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
,E/WifiStateMachine( 1032):  SupplicantStartingState CMD_START_DRIVER 0 0
E/WifiMonitor( 1032): WifiMonitor:wlan0 cnt=0 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1032): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1032): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
E/WifiStateMachine( 1032):  SupplicantStartingState CMD_SET_HIGH_PERF_MODE 0 0
E/WifiStateMachine( 1032):  DefaultState CMD_SET_HIGH_PERF_MODE 0 0
E/WifiStateMachine( 1032):  SupplicantStartingState CMD_DISCONNECT 0 0
E/WifiStateMachine( 1032):  DefaultState CMD_DISCONNECT 0 0
E/WifiStateMachine( 1032):  SupplicantStartingState CMD_RECONNECT 0 0
E/WifiStateMachine( 1032):  DefaultState CMD_RECONNECT 0 0
E/WifiStateMachine( 1032):  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1032):  DefaultState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1032):  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1032):  DefaultState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1032):  SupplicantStartingState SUP_CONNECTION_EVENT 0 0
D/WifiNative-wlan0( 1032): doString: [DRIVER MACADDR]
D/WifiNative-wlan0( 1032):    returned Macaddr = c4:9a:02:7b:60:ac
D/WifiStateMachine( 1032): MAC Addr from driver = c4:9a:02:7b:60:ac
D/WifiOffDelayIfNotUsed( 1032): setPowerSaveActivated(false)
I/ActivityManager( 1032): Start proc com.lge.formmanager for broadcast com.lge.formmanager/.FormServiceReceiver: pid=6198 uid=10026 gids={50026, 9997, 3003, 1028} abi=armeabi-v7a
W/libprocessgroup( 1032): failed to open /acct/uid_10004/pid_5691/cgroup.procs: No such file or directory
,E/WifiStateMachine( 1032): Couldn't get getWiFiOffloadingIface : 
E/WifiStateMachine( 1032): useWiFiOffloading() : false
E/WifiStateMachine( 1032): CONFIG_LGE_WLAN_PATH : true
D/LGBluetoothAvrcpQcomAdapter( 6128): [BTUI] [+] updateMediaPlayerInfo
D/WifiNative-wlan0( 1032): doBoolean: SET update_config 1
W/Settings( 1032): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1032): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiNative-wlan0( 1032): SET update_config 1: returned true
D/WifiConfigStore( 1032): Loading config and enabling all networks 
D/WifiNative-wlan0( 1032): doString: [LIST_NETWORKS]
D/WifiNative-wlan0( 1032):    returned network id / ssid / bssid / flags 0	NG700	any	
D/StatusBar.NetworkController( 1447): refreshViews: Data not connected!! Set no data type icon / Roaming
D/WfdService( 1915): Waiting for WifiP2p enabling
E/WifiConfigStore( 1032): readNetworkVariablesFromSupplicantFile key=psk
,E/WifiConfigStore( 1032): readNetworkVariableFromSupplicantFile ssid=["NG700"] key=psk
,E/WifiConfigStore( 1032): Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
I/WifiServerServiceExt( 1032): WIFI_STATE_CHANGED_ACTION [3]
,I/WifiServerServiceExt( 1032): batteryPsActivateMsgHandler : state:0 event:3
D/WifiStateMachine( 1032): enableVerboseLogging : level 2
,D/WifiNative-wlan0( 1032): doBoolean: SET device_name g3_global_com
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
,D/WifiNative-wlan0( 1032): SET config_methods physical_display virtual_push_button: returned true
D/WifiNative-wlan0( 1032): doBoolean: SET device_type 10-0050F204-5
D/WifiNative-wlan0( 1032): SET device_type 10-0050F204-5: returned true
D/WifiStateMachine( 1032): Setting OUI to DA-A1-19
D/WfdsService( 1915): Supplicant Connection state is changed : true
D/WifiNative-wlan0( 1032): doBoolean: SCAN_INTERVAL 120
D/WfdsService( 1915): DefaultState - WIFI_SUPPLICANT_CONNECTED
D/WfdsService( 1915): Set the WFDS Monitor: true
D/WifiNative-wlan0( 1032): SCAN_INTERVAL 120: returned true
D/WifiNative-HAL( 1032): Setting external_sim to 1
D/WifiNative-wlan0( 1032): doBoolean: SET external_sim 1
D/WifiNative-wlan0( 1032): SET external_sim 1: returned true
I/WifiNative-HAL( 1032): startHal
E/wifi    ( 1032): getStaticLongField sWifiHalHandle 0x9892e8dc
D/WfdsMonitor( 1915): WfdsMonitorThread create
D/WfdsMonitor( 1915): WFDS Monitor is created and started
D/WfdsService( 1915): WiFi: Supplicant connection re-established
E/WifiHAL ( 1032): Could not connect handle
,D/wifi    ( 1032): halHandle = 0x0, mVM = 0xb487c280, mCls = 0x1022c2
I/WifiNative-HAL( 1032): Could not start hal
D/WifiStateMachine( 1032): Setting OUI to DA-A1-19
I/WifiNative-HAL( 1032): startHal
E/wifi    ( 1032): getStaticLongField sWifiHalHandle 0x9892e85c
E/WifiHAL ( 1032): Could not connect handle
D/wifi    ( 1032): halHandle = 0x0, mVM = 0xb487c280, mCls = 0x1022c6
I/WifiNative-HAL( 1032): Could not start hal
D/WifiNative-wlan0( 1032): doBoolean: STA_AUTOCONNECT 1
D/WifiNative-wlan0( 1032): STA_AUTOCONNECT 1: returned true
D/WifiNative-wlan0( 1032): doBoolean: DRIVER BTCOEXSCAN-STOP
E/CtrlSupplicant( 1915): Access OK "@android:wpa_wlan0"
I/wpa_supplicant( 6166): wpa_driver_nl80211_ext_driver_cmd BTCOEXSCAN-STOP
D/WifiNative-wlan0( 1032): DRIVER BTCOEXSCAN-STOP: returned true
E/CtrlSupplicant( 1915): Succeed to open control connection
D/WifiNative-wlan0( 1032): doBoolean: DRIVER RXFILTER-STOP
I/wpa_supplicant( 6166): wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
D/WifiNative-wlan0( 1032): DRIVER RXFILTER-STOP: returned true
D/WifiNative-wlan0( 1032): doBoolean: DRIVER RXFILTER-REMOVE 3
I/wpa_supplicant( 6166): wpa_driver_nl80211_ext_driver_cmd RXFILTER-REMOVE 3
D/WifiNative-wlan0( 1032): DRIVER RXFILTER-REMOVE 3: returned true
D/WifiNative-wlan0( 1032): doBoolean: DRIVER RXFILTER-START
I/wpa_supplicant( 6166): wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
D/WifiNative-wlan0( 1032): DRIVER RXFILTER-START: returned true
D/WifiNative-wlan0( 1032): doBoolean: DRIVER RXFILTER-STOP
I/wpa_supplicant( 6166): wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
D/WifiNative-wlan0( 1032): DRIVER RXFILTER-STOP: returned true
D/WifiNative-wlan0( 1032): doBoolean: DRIVER RXFILTER-REMOVE 2
I/wpa_supplicant( 6166): android_multicast_filter_startstop : multicast filter set
D/WifiNative-wlan0( 1032): DRIVER RXFILTER-REMOVE 2: returned true
D/WifiNative-wlan0( 1032): doBoolean: DRIVER RXFILTER-START
I/wpa_supplicant( 6166): wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
,D/WifiNative-wlan0( 1032): DRIVER RXFILTER-START: returned true
E/WifiNative: ( 1032): [116,748,219 us] RECONNECT  stack:logDbg - reconnect - enter - invokeEnterMethods - performTransitions
D/WifiNative-wlan0( 1032): doBoolean: RECONNECT
D/WifiNative-wlan0( 1032): RECONNECT: returned true
D/WifiNative-wlan0( 1032): doString: [STATUS]
D/WifiMonitor( 1032): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
E/WifiMonitor( 1032): WifiMonitor:wlan0 cnt=1 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
D/WifiNative-wlan0( 1032):    returned wpa_state=SCANNING p2p_device_address=02:9a:02:7b:60:ac address=c4:9a:02:7b:60:ac uuid=530d3fd0-1ba3-5409-a336-ff4e42af59a2
D/WifiNative-wlan0( 1032): doBoolean: DRIVER SETSUSPENDMODE 1
I/wpa_supplicant( 6166): wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 1
D/WifiNative-wlan0( 1032): DRIVER SETSUSPENDMODE 1: returned true
D/WifiNative-wlan0( 1032): doBoolean: SET ps 1
I/StatusBar.NetworkController( 1447): networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1447): mWifiConnected = false, mWifiLevel = 0
D/WifiNative-wlan0( 1032): SET ps 1: returned true
D/LGWifiP2pService( 1032): P2pDisabledState{ when=0 what=131203 target=com.android.internal.util.StateMachine$SmHandler }
D/CommandListener(  313): Setting iface cfg
D/CommandListener(  313): Trying to bring up p2p0
D/WifiMonitor( 1032): startMonitoring(p2p0) with mConnected = true
D/LGWifiP2pService( 1032): P2pEnablingState
D/LGWifiP2pService( 1032): P2pEnablingState{ when=-1ms what=147457 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1032): P2p socket connection successful
D/LGWifiP2pService( 1032): P2pEnabledState
D/WifiHS20( 1032): hidePasspointNotification off =false
E/CtrlSupplicant( 1915): Succeed to open monitor connection
D/WfdsMonitor( 1915): Supplicant connection established
D/WfdsService( 1915): Connected to the supplicant for wfds
,W/Settings( 1032): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1032): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1032): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
E/WifiStateMachine( 1032):  DisconnectedState CMD_SET_OPERATIONAL_MODE 1 0
E/WifiStateMachine( 1032):  DisconnectedState CMD_START_DRIVER 0 0
D/StatusBar.NetworkController( 1447): refreshViews: Data not connected!! Set no data type icon / Roaming
E/WifiStateMachine( 1032):  ConnectModeState CMD_START_DRIVER 0 0
D/LGWifiP2pService( 1032): sending p2p connection changed broadcast
D/WifiNative-p2p0( 1032): doBoolean: SET persistent_reconnect 1
D/WifiNative-p2p0( 1032): SET persistent_reconnect 1: returned true
D/WifiNative-p2p0( 1032): doBoolean: SET device_name G3-1
D/WifiNative-p2p0( 1032): SET device_name G3-1: returned true
D/LGWifiP2pService( 1032): [LGE_P2P] initializeP2pSettings() check postfix
D/LGWifiP2pService( 1032): before postfix = G3-1
D/WifiServerServiceExt( 1032): postfix byte check : 4
D/LGWifiP2pService( 1032): after postfix = G3-1
D/WifiNative-p2p0( 1032): doBoolean: SET p2p_ssid_postfix -G3-1
E/WifiStateMachine( 1032):  DriverStartedState CMD_START_DRIVER 0 0
E/WifiStateMachine( 1032):  DisconnectedState what:132106 1 0
E/WifiStateMachine( 1032):  ConnectModeState what:132106 1 0
E/WifiStateMachine( 1032):  DriverStartedState what:132106 1 0
I/WifiServerServiceExt( 1032): setWifiDualbandAPConnection band : 1
E/wpa_supplicant( 6166): nWIFIDualbandAPConnection: 1
D/WifiScanningService( 1032): SCAN_AVAILABLE : 3
D/RttService( 1032): SCAN_AVAILABLE : 3
D/WifiScanningService( 1032): DefaultState got{ when=-1ms what=160006 target=com.android.internal.util.StateMachine$SmHandler }
I/WifiNative-HAL( 1032): startHal
D/RttService( 1032): DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-p2p0( 1032): SET p2p_ssid_postfix -G3-1: returned true
V/WfdStateTracker( 1915): WfdStateTracker handleDirectStateChangedEvent: 2
,E/wifi    ( 1032): getStaticLongField sWifiHalHandle 0x9650999c
E/WifiHAL ( 1032): Could not connect handle
D/wifi    ( 1032): halHandle = 0x0, mVM = 0xb487c280, mCls = 0x1022ca
I/WifiNative-HAL( 1032): Could not start hal
E/WifiScanningService( 1032): could not start HAL
D/WifiNative-p2p0( 1032): doBoolean: SET device_type 10-0050F204-5
D/WifiNative-p2p0( 1032): SET device_type 10-0050F204-5: returned true
D/WifiNative-p2p0( 1032): doBoolean: SET config_methods virtual_push_button physical_display keypad
D/WifiNative-p2p0( 1032): SET config_methods virtual_push_button physical_display keypad: returned true
D/WifiNative-p2p0( 1032): doBoolean: P2P_SET conc_pref p2p
D/WifiNative-p2p0( 1032): P2P_SET conc_pref p2p: returned true
D/WifiNative-HAL( 1032): p2pGetDeviceAddress
E/WifiStateMachine( 1032):  DisconnectedState what:132096 -100 0
D/WfdsService( 1915): WifiP2pState is changed : true
E/WifiStateMachine( 1032):  ConnectModeState what:132096 -100 0
D/WfdsService( 1915): Receive the WFDS_ENABLE Method
D/WfdsService( 1915): Set the WFDS Monitor: true
D/WfdsService( 1915): Connected to the supplicant for wfds
D/WfdsJNI ( 1915): doCommand: WFDS_SET TRUE
I/wpa_supplicant( 6166): WFDS: wfds_supplicant_wfds_cmd: cmd = SET TRUE
E/WifiStateMachine( 1032):  DriverStartedState what:132096 -100 0
I/WifiServerServiceExt( 1032): set CMD_DISCONNECT_RSSI_LVL : -100
E/wpa_supplicant( 6166): disconnect_rssi_lvl: -100
E/WifiStateMachine( 1032):  DisconnectedState CMD_SET_COUNTRY_CODE 1 0 cz
D/WfdsJNI ( 1915): doCommand: WFDS_GET_MAC_ADDRESS
I/wpa_supplicant( 6166): WFDS: wfds_supplicant_wfds_cmd: cmd = GET_MAC_ADDRESS
E/WifiStateMachine( 1032):  ConnectModeState CMD_SET_COUNTRY_CODE 1 0 cz
E/WifiStateMachine( 1032):  DriverStartedState CMD_SET_COUNTRY_CODE 1 0 cz
D/WifiNative-wlan0( 1032): doBoolean: DRIVER COUNTRY CZ
D/WfdsJNI ( 1915): doCommand: IFNAME=wlan0 GET_CAPABILITY channels
D/WfdsService( 1915): selectPreferredScanChannel [36]
D/WfdsService( 1915): STATE : WfdsEnabledState - enter: this device mac 02:9a:02:7b:60:ac
D/WifiNative-HAL( 1032): p2pGetDeviceAddress returning 
D/LGWifiP2pService( 1032): DeviceAddress: 
D/WifiNative-p2p0( 1032): doBoolean: P2P_FLUSH
D/WifiNative-p2p0( 1032): P2P_FLUSH: returned true
D/WifiNative-p2p0( 1032): doBoolean: P2P_SERVICE_FLUSH
D/WfdsService( 1915): WIFI_P2P_CONNECTION_CHANGED_ACTION
D/WifiNative-p2p0( 1032): P2P_SERVICE_FLUSH: returned true
D/WifiNative-p2p0( 1032): doString: [LIST_NETWORKS]
D/WifiNative-p2p0( 1032):    returned network id / ssid / bssid / flags
D/WifiNative-p2p0( 1032): doBoolean: SAVE_CONFIG
D/WfdsService( 1915): isConnected: false
I/WfdStateTracker( 1915): handleP2pThisDeviceChanged
D/WfdsService( 1915): WIFI_P2P_THIS_DEVICE_CHANGED_ATCION
,D/WfdsService( 1915): Update P2p Interface State: 3
D/WifiNative-p2p0( 1032): SAVE_CONFIG: returned true
I/wpa_supplicant( 6166): wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
I/wpa_supplicant( 6166): wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
I/wpa_supplicant( 6166): [LGE_PATCH] driver_cmd() country:CZ
I/wpa_supplicant( 6166): p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
I/wpa_supplicant( 6166): p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
D/LGWifiP2pService( 1032): sending p2p persistent groups changed broadcast
D/LGWifiP2pService( 1032): InactiveState
D/LGWifiP2pService( 1032): InactiveState{ when=-12ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1032): P2pEnabledState{ when=-12ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-p2p0( 1032): doBoolean: DRIVER COUNTRY CZ
D/WfdsMonitor( 1915): Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
D/WfdsMonitor( 1915): Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
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
E/WifiMonitor( 1032): handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
D/WifiNative-wlan0( 1032): DRIVER COUNTRY CZ: returned true
I/wpa_supplicant( 6166): wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
E/WifiStateMachine( 1032):  DisconnectedState CMD_SET_FREQUENCY_BAND 0 0
E/WifiStateMachine( 1032):  ConnectModeState CMD_SET_FREQUENCY_BAND 0 0
I/wpa_supplicant( 6166): p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
E/WifiStateMachine( 1032):  DriverStartedState CMD_SET_FREQUENCY_BAND 0 0
D/WifiNative-wlan0( 1032): doBoolean: DRIVER SETBAND 0
D/WfdsMonitor( 1915): Event [CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
D/WifiMonitor( 1032): Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
E/WifiMonitor( 1032): WifiMonitor:p2p0 cnt=5 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
E/WifiMonitor( 1032): handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
I/wpa_supplicant( 6166): [LGE_PATCH] driver_cmd() country:CZ
E/WifiMonitor( 1032): handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
I/wpa_supplicant( 6166): p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
D/WfdsMonitor( 1915): Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
D/WifiMonitor( 1032): Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
E/WifiMonitor( 1032): WifiMonitor:p2p0 cnt=6 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
E/WifiMonitor( 1032): handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
E/WifiMonitor( 1032): handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
I/wpa_supplicant( 6166): p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
D/WfdsMonitor( 1915): Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
,D/WifiMonitor( 1032): Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
E/WifiMonitor( 1032): WifiMonitor:p2p0 cnt=7 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
E/WifiMonitor( 1032): handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
E/WifiMonitor( 1032): handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
D/WifiNative-p2p0( 1032): DRIVER COUNTRY CZ: returned true
D/LGWifiP2pService( 1032): InactiveState{ when=-3ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1032): P2pEnabledState{ when=-3ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1032): InactiveState{ when=0 what=139287 arg2=1 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1032): P2pEnabledState{ when=0 what=139287 arg2=1 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 6166): wpa_driver_nl80211_ext_driver_cmd SETBAND 0 - interface name wlan0
I/wpa_supplicant( 6166): wlan0: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
D/WifiNative-wlan0( 1032): DRIVER SETBAND 0: returned true
D/WifiNative-wlan0( 1032): doBoolean: BSS_FLUSH 0
D/WifiNative-wlan0( 1032): BSS_FLUSH 0: returned true
D/WifiNative-wlan0( 1032): doBoolean: SCAN
D/WifiMonitor( 1032): Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN]
E/WifiMonitor( 1032): WifiMonitor:wlan0 cnt=8 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
E/WifiMonitor( 1032): handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
E/WifiMonitor( 1032): handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
D/WifiNative-wlan0( 1032): SCAN: returned false
E/WifiStateMachine( 1032):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 1 0 rt=116801  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
I/StatusBar.NetworkController( 1447): networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1447): mWifiConnected = false, mWifiLevel = 0
E/WifiStateMachine( 1032):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 1 0 rt=116803  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
D/StatusBar.NetworkController( 1447): refreshViews: Data not connected!! Set no data type icon / Roaming
W/Settings( 1032): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1032): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1032): NETWORK_STATE_CHANGED_ACTION [SCANNING]
D/LGWifiP2pService( 1032): DefaultState{ when=0 what=139287 arg2=1 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1032): InactiveState{ when=-5ms what=139287 arg2=1 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1032): P2pEnabledState{ when=-5ms what=139287 arg2=1 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1032): DefaultState{ when=-5ms what=139287 arg2=1 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1032): InactiveState{ when=-5ms what=139283 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1032): P2pEnabledState{ when=-5ms what=139283 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1032): DefaultState{ when=-5ms what=139283 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1032): InactiveState{ when=-6ms what=139285 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1032): P2pEnabledState{ when=-6ms what=139285 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1032): DefaultSta,te{ when=-6ms what=139285 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
W/WfdsService( 1915): DefaultState - msg [9441285] is not handled
E/WifiServerServiceExt( 1032): No p2p device connected
E/WifiStateMachine( 1032):  DisconnectedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
E/WifiStateMachine( 1032):  ConnectModeState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
E/WifiStateMachine( 1032):  DriverStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
E/WifiStateMachine( 1032):  SupplicantStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
E/WifiStateMachine( 1032):  DefaultState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
D/WifiServerServiceExt( 1032): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1032): setSupplicantStateSCANNING
,V/SIM_STK ( 1032): Menu title from STK is T-Mobile
V/SIM_STK ( 1032): Menu title from STK is T-Mobile
W/ActivityManager( 1032): getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
D/LGBluetoothAvrcpQcomAdapter( 6128): [BTUI] installed app name: Music
D/LGBluetoothAvrcpQcomAdapter( 6128): [BTUI] installed app name: Google Play Music
D/LGBluetoothAvrcpQcomAdapter( 6128): [BTUI] === MediaPlayerInfo (playerId:0) ===
D/LGBluetoothAvrcpQcomAdapter( 6128): [BTUI]          displayName: Music
D/LGBluetoothAvrcpQcomAdapter( 6128): [BTUI]          packageName: com.lge.music
D/LGBluetoothAvrcpQcomAdapter( 6128): [BTUI]          playState: 2 (PAUSED)
D/LGBluetoothAvrcpQcomAdapter( 6128): [BTUI] === MediaPlayerInfo (playerId:1) ===
D/LGBluetoothAvrcpQcomAdapter( 6128): [BTUI]          displayName: Google Play Music
D/LGBluetoothAvrcpQcomAdapter( 6128): [BTUI]          packageName: com.google.android.music
D/LGBluetoothAvrcpQcomAdapter( 6128): [BTUI]          playState: 2 (PAUSED)
D/LGBluetoothAvrcpQcomAdapter( 6128): [BTUI] [-] updateMediaPlayerInfo
I/BluetoothA2dpServiceJni( 6128): classInitNative
I/BluetoothA2dpServiceJni( 6128): classInitNative: succeeds
,D/A2dpStateMachine( 6128): make
I/bluedroid-qcom( 6128): get_profile_interface a2dp
I/GKI_LINUX( 6128): gki_task_entry task_id=2 [A2DP-MEDIA] starting
I/LGBluetoothA2dpServiceJni( 6128): classInitNative: succeeds
I/LGBluetoothA2dpAdapter( 6128): [BTUI] getInstance : create [LGBluetoothA2dpAdapter]
D/BluetoothAdapterService( 6128): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2b2e07a9
D/A2dpStateMachine( 6128): Enter Disconnected: -2
I/BluetoothHidServiceJni( 6128): classInitNative: succeeds
,D/HidService( 6128): Received start request. Starting profile...
I/bluedroid-qcom( 6128): get_profile_interface hidhost
D/BluetoothAdapterService( 6128): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2b2e07a9
I/BluetoothHealthServiceJni( 6128): classInitNative: succeeds
D/HealthService( 6128): Received start request. Starting profile...
I/bluedroid-qcom( 6128): get_profile_interface health
I/LGBluetoothHealthServiceJni( 6128): classInitNative: succeeds
D/BluetoothAdapterService( 6128): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2b2e07a9
,I/BluetoothPanServiceJni( 6128): classInitNative(L105): succeeds
D/PanService( 6128): Received start request. Starting profile...
D/BluetoothPanServiceJni( 6128): initializeNative(L110): pan
I/bluedroid-qcom( 6128): get_profile_interface pan
I/art     ( 1032): Explicit concurrent mark sweep GC freed 38417(1963KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 44MB/66MB, paused 2.437ms total 125.095ms
I/LGBluetoothPanAdapter( 6128): [BTUI] getInstance : create [LGBluetoothPanAdapter]
D/WifiService( 1032): New client listening to asynchronous messages
D/BluetoothAdapterService( 6128): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2b2e07a9
,I/BtGatt.JNI( 6128): classInitNative(L901): classInitNative: Success!
D/BtGatt.DebugUtils( 6128): handleDebugAction() action=null
D/BtGatt.GattService( 6128): Received start request. Starting profile...
D/BtGatt.GattService( 6128): start()
I/bluedroid-qcom( 6128): get_profile_interface gatt
D/BtGatt.AdvertiseManager( 6128): advertise manager created
I/ActivityManager( 1032): Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=6228 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,D/BluetoothAdapterService( 6128): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2b2e07a9
D/BluetoothAdapterService( 6128): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2b2e07a9
I/LGBluetoothMapAdapter( 6128): [BTUI] getInstance : create [LGBluetoothMapAdapter]
V/BluetoothMapService( 6128): BluetoothMapBinder()
D/BluetoothMapService( 6128): Received start request. Starting profile...
D/BluetoothMapService( 6128): start()
D/BluetoothMapEmailSettingsLoader( 6128): Found 0 applications
D/BluetoothMapEmailAppObserver( 6128): createReceiver()
D/BluetoothMapEmailAppObserver( 6128): initObservers()
D/BluetoothMapEmailAppObserver( 6128): getEnabledAccountItems()
,D/BluetoothAdapterService( 6128): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2b2e07a9
D/HeadsetStateMachine( 6128): Proxy object connected
D/LGBluetoothHfpAdapter( 6128): [BTUI] queryPhoneState
D/LGBluetoothHfpAdapter( 6128): Try to query the phonestate on bind
D/BluetoothPhoneService.BluetoothLTECall( 1825):  call mBluetoothHeadset.phoneStateChanged()
I/wpa_supplicant( 6166): [LGE_PATCH]scan interval[0] = 2 sec.
,W/BluetoothHeadset( 1825): Proxy not attached to service
D/WfdsMonitor( 1915): Event [CTRL-EVENT-SCAN-RESULTS ]
D/WfdsMonitor( 1915): Event [WPS-AP-AVAILABLE ]
E/WifiMonitor( 1032): WifiMonitor:wlan0 cnt=9 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
E/WifiMonitor( 1032): handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
D/WifiMonitor( 1032): Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
E/WifiMonitor( 1032): WifiMonitor:wlan0 cnt=10 dispatchEvent: WPS-AP-AVAILABLE 
D/BluetoothHeadset( 1825): java.lang.Throwable
D/BluetoothHeadset( 1825): 	at android.bluetooth.BluetoothHeadset.phoneStateChanged(BluetoothHeadset.java:826)
D/BluetoothHeadset( 1825): 	at com.android.phone.BluetoothPhoneService$BluetoothLTECall.handleQueryPhoneState(BluetoothPhoneService.java:1527)
D/BluetoothHeadset( 1825): 	at com.android.phone.BluetoothPhoneService$BluetoothLTECall.access$700(BluetoothPhoneService.java:1360)
D/BluetoothHeadset( 1825): 	at com.android.phone.BluetoothPhoneService$1.handleMessage(BluetoothPhoneService.java:268)
D/BluetoothHeadset( 1825): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/BluetoothHeadset( 1825): 	at android.os.Looper.loop(Looper.java:135)
D/BluetoothHeadset( 1825): 	at android.app.ActivityThread.main(ActivityThread.java:5274)
D/BluetoothHeadset( 1825): 	at java.lang.reflect.Method.invoke(Native Method)
D/BluetoothHeadset( 1825): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/BluetoothHeadset( 1825): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
D/BluetoothHeadset( 1825): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
W/WifiMonitor( 1032): couldn't identify event type - WPS-AP-AVAILABLE 
E/WifiMonitor( 1032): WifiMonitor:p2p0 cnt=11 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
E/WifiMonitor( 1032): handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
D/WifiMonitor( 1032): Event [IFNAME=p2p0 WPS-AP-AVAILABLE ]
E/WifiMonitor( 1032): WifiMonitor:p2p0 cnt=12 dispatchEvent: WPS-AP-AVAILABLE 
W/WifiMonitor( 1032): couldn't identify event type - WPS-AP-AVAILABLE 
E/WifiStateMachine( 1032):  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=0 bcn=0
E/WifiStateMachine( 1032):  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=0 bcn=0
E/WifiStateMachine( 1032):  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=0 bcn=0
E/WifiStateMachine( 1032):  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=0 bcn=0
I/WifiNative-HAL( 1032): startHal
E/wifi    ( 1032): getStaticLongField sWifiHalHandle 0x9892e8cc
E/WifiHAL ( 1032): Could not connect handle
D/wifi    ( 1032): halHandle = 0x0, mVM = 0xb487c280, mCls = 0x502186
I/WifiNative-HAL( 1032): Could not start hal
D/WifiNative-wlan0( 1032): doString: [BSS RANGE=0- MASK=0x21987]
D/LGWifiP2pService( 1032): InactiveState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1032): P2pEnabledState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1032): DefaultState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/BluetoothAdapterService( 6128): Profile still not running:com.android.bluetooth.gatt.GattService
D/HeadsetStateMachine( 6128): Disconnected process message: 10, size: 0
D/HeadsetPhoneState( 6128): sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
D/HeadsetStateMachine( 6128): Disconnected process message: 11, size: 0
V/BluetoothPbapReceiver( 6128): PbapReceiver onReceive 
V/BluetoothPbapReceiver( 6128): ***********action = android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothPbapReceiver( 6128): ***********state = 11
V/FormManager( 6198): Network unavailable.
W/FormManager( 6198): Network not available. Please check & try again.
,D/BluetoothAdapterService( 6128): Profile still not running:com.android.bluetooth.gatt.GattService
D/BluetoothAdapterService( 6128): Profile still not running:com.android.bluetooth.gatt.GattService
D/BluetoothAdapterService( 6128): Profile still not running:com.android.bluetooth.gatt.GattService
D/BluetoothAdapterService( 6128): Profile still not running:com.android.bluetooth.gatt.GattService
V/PanService( 6128): [BTUI] SIM Extra State :ABSENT
D/BluetoothAdapterService( 6128): Profile still not running:com.android.bluetooth.map.BluetoothMapService
V/BluetoothMapService( 6128): Handler(): got msg=1
D/BluetoothAdapterState( 6128): CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
I/bluedroid-qcom( 6128): enable
I/GKI_LINUX( 6128): gki_task_entry task_id=0 [BTU] starting
I/bt-btu  ( 6128): btu_task pending for preload complete event
I/bt_hci_bdroid( 6128): init
I/bt_vendor( 6128): bt-vendor : init
I/bt_vendor( 6128): bt-vendor : get_bt_soc_type
E/bt_vendor( 6128): get_bt_soc_type: Failed to get soc type
I/bt_vendor( 6128): init: Local BD Address : c0:64:73:54:3f:58
D/bt_userial_mct( 6128): userial_init
D/bt_hci_bdroid( 6128): set_power 1
I/bt_vendor( 6128): bt-vendor : BT_VND_OP_POWER_CTRL: On
I/bt_vendor( 6128): Starting hciattach daemon
I/bt_vendor( 6128): try to set true
,W/sh      ( 6250): type=1400 audit(0.0:155): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6843 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
W/sh      ( 6250): type=1400 audit(0.0:156): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6843 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
I/ActivityManager( 1032): Start proc com.lge.lifetracker for broadcast com.lge.lifetracker/.receiver.HealthDeviceReceiver: pid=6251 uid=10037 gids={50037, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
V/FormManager( 6198): Network unavailable.
,I/qcom-bluetooth( 6260): /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  
I/ActivityManager( 1032): Killing 5824:com.google.android.partnersetup/u0a8 (adj 15): empty #17
,I/qcom-bluetooth( 6275): /system/etc/init.qcom.bt.sh: Transport : smd 
,D/PCSuite ( 6228): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
I/qcom-bluetooth( 6277): /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,I/qcom-bluetooth( 6279): /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,I/qcom-bluetooth( 6280): /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> 
I/qcom-bluetooth( 6281): /system/etc/init.qcom.bt.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,I/qcom-bluetooth( 6282): /system/etc/init.qcom.bt.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> 
,W/libprocessgroup( 1032): failed to open /acct/uid_10008/pid_5824/cgroup.procs: No such file or directory
I/libmdmdetect( 6284): ESOC framework not supported
E/Diag_Lib( 6284):  Diag_LSM_Init: Failed to open handle to diag driver, error = 13
,D/bthci_qcomm_linux( 6284): [BTUI] bt_hci_qcomm_pfal_get_bdaddress: Get BDADDR from bluedroid prop (58:3F:54:73:64:C0)
D/bthci_qcomm_common( 6284): [BTUI] bt_hci_qcomm_init:
D/bthci_qcomm_common( 6284): [BTUI]     BDADDR: 58:3F:54:73:64:C0
D/bthci_qcomm_common( 6284): [BTUI]     BR/EDR: Class 1
D/bthci_qcomm_common( 6284): [BTUI]     LE: Class 2
D/bthci_qcomm_common( 6284): [BTUI]     Ref Clock: 32M
D/btqsocnvmtags( 6284): [BTUI] init_riva_entries: set NORMAL power settings
V/WiFiOffLoadBroadcast( 6167): WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
D/WifiService( 1032): New client listening to asynchronous messages
,E/ActivityThread( 6251): Failed to find provider info for com.lge.lgaccount.provider
W/LG Account v2.2( 6251): No ProfileInfo entries
I/LG Account v2.2( 6251): isEnabled: false
I/Feature ( 6251): [Lifetracker]ver: 4.21.112(40211120)
I/Feature ( 6251): [Lifetracker]Country: EU
I/Feature ( 6251): [Lifetracker]Operator: OPEN
I/Feature ( 6251): [Lifetracker]Ranking support: false
I/Feature ( 6251): [Lifetracker]Comfort support: false
I/Feature ( 6251): [Lifetracker]Accessory: true
I/Feature ( 6251): [Lifetracker]Health device: true
I/Feature ( 6251): [Lifetracker]Extra Pedometer: false
I/Feature ( 6251): [Lifetracker]Blood glucose device: false
I/Feature ( 6251): [Lifetracker]Device Number: 3
,I/ActivityManager( 1032): Killing 5511:com.lge.appbox.client/u0a11 (adj 15): empty #17
D/LgDataFeature( 6167): LgDataFeature() Constructor: none
D/LgDataFeature( 6167): LgDataFeature() Constructor Done, null
D/WiFiOffLoadUpdatePriority( 6167): remove : truetruetrue
,E/WifiStateMachine( 1032):  DisconnectedState CMD_GET_CONFIGURED_NETWORKS uid=1000 1000 0 num=1
E/WifiStateMachine( 1032):  ConnectModeState CMD_GET_CONFIGURED_NETWORKS uid=1000 1000 0 num=1
E/WifiStateMachine( 1032):  DisconnectedState CMD_SAVE_CONFIG uid=1000 0 0
E/WifiStateMachine( 1032):  ConnectModeState CMD_SAVE_CONFIG uid=1000 0 0
D/WifiNative-wlan0( 1032): doBoolean: SAVE_CONFIG
D/WifiNative-wlan0( 1032): SAVE_CONFIG: returned true
,D/WiFiOffLoadUpdatePriority( 6167): remove1
V/WiFiOffLoadSharedPrefsUtils( 6167): save remove
D/WiFiOffLoadBroadcast( 6167): mLastConnectedNetwork from SharedPrefsUtils for wifioffloading : null
D/WiFiOffLoadBroadcast( 6167): S: false, R: false
E/WifiStateMachine( 1032):  DisconnectedState CMD_GET_CONFIGURED_NETWORKS uid=1000 1000 0 num=1
E/WifiStateMachine( 1032):  ConnectModeState CMD_GET_CONFIGURED_NETWORKS uid=1000 1000 0 num=1
,D/WiFiOffLoadUpdatePriority( 6167): saved SSID: "NG700"
D/WiFiOffLoadUpdatePriority( 6167): connected SSID: null
D/WiFiOffLoadUpdatePriority( 6167): private wpa: "NG700" 300
D/WifiServiceImplEx( 1032): addOrUpdateNetwork pid=6167, uid=1000, packageName=android.uid.system:1000
E/addOrUpdateNetwork( 1032):  uid = 1000 SSID "NG700" nid=0
E/WifiStateMachine( 1032):  DisconnectedState CMD_ADD_OR_UPDATE_NETWORK uid=1000 0 0 "NG700"WPA_PSK prio=300 status=2
E/WifiStateMachine( 1032):  ConnectModeState CMD_ADD_OR_UPDATE_NETWORK uid=1000 0 0 "NG700"WPA_PSK prio=300 status=2
E/WifiConfigStore( 1032):  key="NG700"WPA_PSK netId=0 uid=0/1000
D/WifiServerServiceExt( 1032): addOrUpdateNetwork: mThisIsFirstEnableing = false
D/WifiNative-wlan0( 1032): doBoolean: SET_NETWORK 0 ssid 4e47373030
I/rmt_storage(  310): rmt_storage_connect_cb: clnt_h=0x5 conn_h=0xb6403090
I/rmt_storage(  310): rmt_storage_rw_iovec_cb: /boot/modem_fs2: clnt_h=0x2: req_h=0x9 msg_id=3: R/W request received
I/rmt_storage(  310): wakelock acquired: 1, error no: 42
I/rmt_storage(  310): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 Unblock worker thread (th_id: -1236806912)
,D/WifiNative-wlan0( 1032): SET_NETWORK 0 ssid 4e47373030: returned true
,D/WifiNative-wlan0( 1032): doBoolean: SET_NETWORK 0 key_mgmt WPA-PSK
D/WifiNative-wlan0( 1032): SET_NETWORK 0 key_mgmt WPA-PSK: returned true
D/WifiNative-wlan0( 1032): doBoolean: SET_NETWORK 0 proto WPA RSN
D/WifiNative-wlan0( 1032): SET_NETWORK 0 proto WPA RSN: returned true
D/WifiNative-wlan0( 1032): doBoolean: SET_NETWORK 0 pairwise TKIP CCMP
D/WifiNative-wlan0( 1032): SET_NETWORK 0 pairwise TKIP CCMP: returned true
D/WifiNative-wlan0( 1032): doBoolean: SET_NETWORK 0 group WEP40 WEP104 TKIP CCMP
D/WifiNative-wlan0( 1032): SET_NETWORK 0 group WEP40 WEP104 TKIP CCMP: returned true
D/WifiNative-wlan0( 1032): doBoolean: SET_NETWORK 0 priority 300
,D/WifiNative-wlan0( 1032): SET_NETWORK 0 priority 300: returned true
E/WifiConfigStore( 1032): will read network variables netId=0
E/WifiConfigStore( 1032): writeIpAndProxyConfigurationsOnChange: "NG700" -> "NG700" path: /data/misc/wifi/ipconfig.txt
E/WifiConfigStore( 1032):  writeKnownNetworkHistory() num networks:1 needWrite=false
W/libprocessgroup( 1032): failed to open /acct/uid_10011/pid_5511/cgroup.procs: No such file or directory
D/WiFiOffLoadUpdatePriority( 6167):  ssid "NG700" prio 300
D/WiFiOffLoadUpdatePriority( 6167): configuration updated: 0
,E/WifiStateMachine( 1032):  DisconnectedState CMD_SAVE_CONFIG uid=1000 0 0
E/WifiStateMachine( 1032):  ConnectModeState CMD_SAVE_CONFIG uid=1000 0 0
D/WifiNative-wlan0( 1032): doBoolean: SAVE_CONFIG
I/rmt_storage(  310): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0x9 msg_id=3: Bytes written = 1572864
I/rmt_storage(  310): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0x9 msg_id=3: Send response: res=0 err=0
I/rmt_storage(  310): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 About to block rmt_storage client thread (th_id: -1236806912) wakelock released: 1, error no: 0
I/rmt_storage(  310): 
,I/rmt_storage(  310): rmt_storage_disconnect_cb: clnt_h=0x0x5 conn_h=0x0xb6403090
E/Diag_Lib(  898): [IMS_FATAL]| 3347 | 907 |ims-rtp-daemon ims_rtp_qmi_handler_thread_func waiting on select thread>
D/WifiNative-wlan0( 1032): SAVE_CONFIG: returned true
D/WiFiOffLoadUpdatePriority( 6167): configuration saved: true
D/BluetoothPermissionRequest( 6167): onReceive
,D/LGBluetoothFeatureConfig( 6167):  get() - isFeatureLoaded : false
D/BluetoothManagerService( 1032): Message: 20
D/BluetoothManagerService( 1032): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@280a790d:true
,I/ActivityManager( 1032): Killing 5533:com.android.contacts/u0a19 (adj 15): empty #17
D/sensors_hal_Time( 1032): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1032): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1032): tsOffsetIs: Apps: 117502314854; DSPS: 3991115; Offset : -4309774795
D/LGBluetoothResetSettingReceiver( 6167): return without doing reset settings.
D/LGBluetoothOppAdapter( 6128): [BTUI] getInstance : create [LGBluetoothOppAdapter]
,W/libprocessgroup( 1032): failed to open /acct/uid_10019/pid_5533/cgroup.procs: No such file or directory
V/BluetoothFtpReceiver( 6128): BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
,V/BluetoothSapReceiver( 6128): [BTUI] checkServiceStart
V/BluetoothSapReceiver( 6128): [BTUI] region:EU country:EU
V/BluetoothSapReceiver( 6128): SapReceiver onReceive 
V/BluetoothSapReceiver( 6128): action = android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothSapReceiver( 6128):  Bluetooth Adapter state = 11
,D/UsbSettingsReceiver( 6167): [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
D/UsbSettingsReceiver( 6167): [AUTORUN] sys.usb.config = ptp_only,adb
D/UsbSettingsReceiver( 6167): [AUTORUN] sys.usb.state = ptp_only,adb
D/UsbSettingsReceiver( 6167): [AUTORUN] persist.sys.usb.config = ptp_only,adb
I/ActivityManager( 1032): Start proc com.lge.settings.easy for broadcast com.lge.settings.easy/com.lge.settings.bluetooth.LGBluetoothProfileConnectionReceiver: pid=6297 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,D/UsbSettingsReceiver( 6167): [AUTORUN] onReceive() : app userid = 0, current userid = 0
D/UsbSettingsControl( 6167): [AUTORUN] getUsbConnected() : connected=true
D/UsbSettingsReceiver( 6167): [AUTORUN] onReceive() : availableList=[]
D/UsbSettingsReceiver( 6167): [AUTORUN] onReceive() : activeList=[]
D/UsbSettingsReceiver( 6167): [AUTORUN] onReceive() : errorList=[]
D/UsbSettingsControl( 6167): [AUTORUN] isAutorunTimer() : mAutorunChanging=false
D/UsbSettingsControl( 6167): [AUTORUN] setTetherStatus() : status=false
D/PCSuite ( 6228): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,V/WiFiOffLoadBroadcast( 6167): WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,V/FormManager( 6198): Network unavailable.
V/FormManager( 6198): Network unavailable.
,W/FormManager( 6198): Network not available. Please check & try again.
,D/WiFiOffLoadBroadcast( 6167): MCCMNC not supported: null
D/LGDMClient( 3937): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
,D/LGDMClient( 3937): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
W/ContextImpl( 3937): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
W/ContextImpl( 3937): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
W/ResourcesManager( 6297): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
D/LGDMClient( 3937): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=3, isUserType=1
,D/LGDMClient( 3937): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
D/LGDMClient( 3937): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
D/AuthorizationBluetoothService( 2063): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
D/PostponalbeReceiver( 5168): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
I/PCSuite ( 6228): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
,D/PCSuite ( 6228): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 6228): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 6167): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6167): MCCMNC not supported: null
I/ActivityManager( 1032): Start proc com.lge.qremote for broadcast com.lge.qremote/.settings.WiFiStateReceiver: pid=6325 uid=10112 gids={50112, 9997, 1028, 1015, 3003, 3002} abi=armeabi
I/ActivityManager( 1032): Killing 5846:com.lge.email/u0a23 (adj 15): empty #17
,W/libprocessgroup( 1032): failed to open /acct/uid_10023/pid_5846/cgroup.procs: No such file or directory
,W/ResourcesManager( 6325): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,D/QRemote ( 6325): [QRemoteApplication.java:230:onCreate()] oooooo QRemoteApp onCreate....
,D/QRemote ( 6325): [CarrierUtils.java:858:getHardwareSettings()] oooooo qremote android.os.Build.MODEL = LG-D855
,I/QRemote ( 6325): [CarrierUtils.java:859:getHardwareSettings()] oooooo getCountry :: EU
I/QRemote ( 6325): [CarrierUtils.java:860:getHardwareSettings()] oooooo getCarrier :: OPEN
I/QRemote ( 6325): [CarrierUtils.java:861:getHardwareSettings()] oooooo getArea :: COM
D/QRemote ( 6325): [CarrierUtils.java:862:getHardwareSettings()] oooooo Loading Config...
D/QRemote ( 6325): [CarrierUtils.java:876:getHardwareSettings()] oooooo qremote configuration file = R.xml.qremote_conf
D/QRemote ( 6325): [QRemoteApplication.java:701:updateWidget()] oooooo Widget count is [1]. send broadcast
D/QRemote ( 6325): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,D/QRemote ( 6325): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 6325): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,V/[BNRBootReceiver]( 5987): boot receiver action = android.net.wifi.p2p.CONNECTION_STATE_CHANGE
D/BNRAndroBeam( 5987): [BnR DirectBeam] Android Direct Beam(NFC) Connection changed
V/[BNRBootReceiver]( 5987): Boot Receiver Return
D/QRemote ( 6325): [QRemoteService.java:196:onCreate()] oooooo 140526:onCreate
D/PostponalbeReceiver( 5168): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
D/QRemote ( 6325): [QRemoteService.java:217:onStartCommand()] oooooo 140526:onStartCommand:action:action.application.oncreate. startId:1, flags:0
,V/WiFiOffLoadBroadcast( 6167): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6167): MCCMNC not supported: null
D/QRemote ( 6325): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6325): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 6325): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
V/WiFiOffLoadBroadcast( 6167): WiFiOffLoadBroadcast: android.net.wifi.SCAN_RESULTS
,D/WiFiOffLoadBroadcast( 6167): Not supported operator for automatic switch
V/QRemote ( 6325): [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
D/QRemote ( 6325): [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
D/QRemote ( 6325): [QRemoteApplication.java:86:getControlManager()] oooooo mControlManager is null. make new RemoteControlManager
E/QC-QMI  ( 6284): qmi_client [6284] 13: failed to locate client data
,E/QC-QMI  (  460): qmuxd: RX on fd=32 returned error=0 errno[2:No such file or directory]
E/QC-QMI  (  460): QMUX qmux_client_id=13 not found in qmux client list, unable to remove
D/LgDataFeature( 6325): LgDataFeature() Constructor: none
,D/LgDataFeature( 6325): LgDataFeature() Constructor Done, null
V/SoundPool( 6325): SoundPool constructor: maxChannels=2, attr.usage=13, attr.flags=0x0, attr.tags=
V/SoundPool( 6325): load: fd=30, offset=10857164, length=17813, priority=1
V/SoundPool( 6325): create sampleID=1, fd=31, offset=17813 length=10857164
V/SoundPool( 6325): doLoad: loading sample sampleID=1
V/SoundPool( 6325): Start decode
V/MediaPlayer[Native]( 6325): decode(31, 10857164, 17813)
V/MediaPlayerService(  317): decode(24, 10857164, 17813)
W/BrunchPlayerTypeImpl(  317): [SelectPlayer] LocalType
W/BrunchPlayerTypeImpl(  317): [getMediaType] EXTEND_MEDIA_MIMETYPE = application/ogg
W/BrunchPlayerTypeImpl(  317): [FindUsePlayer] type = [application/ogg]
W/BrunchPlayerTypeImpl(  317): [FindUsePlayer] componentName = [9101]
W/MediaPlayerFactory(  317): [getPlayerType:fd] nType = 3
V/MediaPlayerService(  317): player type = 3
V/AwesomePlayer(  317): AwesomePlayer create()
I/QRemote ( 6325): [RemoteControlManager.java:157:onBindIRService()] oooooo bind
V/AwesomePlayer(  317): reset_l() 
V/AwesomePlayer(  317): cancelPlayerEvents
V/AwesomePlayer(  317): setAudioSink() 
V/AwesomePlayer(  317): reset_l() 
V/AudioCache(  317): notify(0xb1187300, 8, 0, 0)
V/AudioCache(  317): ignored
V/AwesomePlayer(  317): cancelPlayerEvents
D/Utils   (  317): printFileName fd(25) -> /data/preload/LGQRemote/LGQRemote.apk
V/AwesomePlayer(  317): setDataSource_l dataSource
V/LGParserOSAL(  317): SniffLGParser start
V/LGParserOSAL(  317): MainType:5, SubType=0
V/LGParserOSAL(  317): #### check Mime : application/ogg
V/LGParserOSAL(  317): Detector mimeType:application/ogg, Confidence=1.000000
E/MediaExtractor(  317): Use LGExtractor :application/ogg 
D/UEI.SmartControl( 5873): QS Service created
,D/QRemote ( 6325): [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
E/QRemote ( 6325): [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
D/QRemote ( 6325): [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
V/LGMDMManager( 6325): Create singleton instance
I/UEI.SmartControl( 5873): Service initServices...
D/UEI.SmartControl( 5873): QS start get config
,V/LGParserOSAL(  317): supported mime: application/ogg
V/AwesomePlayer(  317): setDataSource_l() extractor countTracks=1
V/AwesomePlayer(  317): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer(  317): mBitrate = -1 bits/sec
V/AwesomePlayer(  317): AudioTrack Setting
V/AwesomePlayer(  317): AudioTrack Setting channelCount = 2
V/AwesomePlayer(  317): setAudioSource() 
V/MediaPlayerService(  317): prepare
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
V/OMXCodec(  317): [OMX.google.vorbis.decoder] allocated buffer 0xb1434740 on input port
V/OMXCodec(  317): [OMX.google.vorbis.decoder] allocated buffer 0xb1434790 on input port
V/OMXCodec(  317): [OMX.google.vorbis.decoder] allocated buffer 0xb1434830 on input port
V/OMXCodec(  317): [OMX.google.vorbis.decoder] allocated buffer 0xb1434880 on input port
V/OMXCodec(  317): allocateBuffersOnPort portIndex=1
V/OMXCodec(  317): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
V/OMXCodec(  317): [OMX.google.vorbis.decoder] allocated buffer 0xb1434d30 on output port
V/OMXCodec(  317): [OMX.google.vorbis.decoder] allocated buffer 0xb1434fb0 on output port
V/OMXCodec(  317): [OMX.google.vorbis.decoder] allocated buffer 0xb15040b0 on output port
V/OMXCodec(  317): [OMX.google.vorbis.decoder] allocated, buffer 0xb1504150 on output port
V/OMXCodec(  317): init() mAsyncCompletion wait!!! 
V/OMXCodec(  317): [OMX.google.vorbis.decoder] onStateChange 2
V/OMXCodec(  317): [OMX.google.vorbis.decoder] Now Idle.
V/OMXCodec(  317): [OMX.google.vorbis.decoder] setState mState=2 , newState=3
V/OMXCodec(  317): init() mAsyncCompletion wait!!! 
V/OMXCodec(  317): [OMX.google.vorbis.decoder] onStateChange 3
V/OMXCodec(  317): [OMX.google.vorbis.decoder] Now Executing.
V/OMXCodec(  317): [OMX.google.vorbis.decoder] setState mState=3 , newState=4
V/OMXCodec(  317): init() mAsyncCompletion wait free! 
V/AwesomePlayer(  317): finishAsyncPrepare_l() 
V/AudioCache(  317): notify(0xb1187300, 5, 0, 0)
V/AudioCache(  317): ignored
V/AudioCache(  317): notify(0xb1187300, 1, 0, 0)
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
V/OMXCodec(  317): [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2973977904
V/OMXCodec(  317): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
V/OMXCodec(  317): [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2973978544
V/OMXCodec(  317): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
V/OMXCodec(  317): [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2974826672
V/OMXCodec(  317): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
V/OMXCodec(  317): [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2974826832
V/OMXCodec(  317): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
V/OMXCodec(  317): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
V/OMXCodec(  317): [OMX.google.vorbis.decoder] initOutputFormat()
V/OMXCodec(  317): [OMX.google.vorbis.decoder] reconfig handling, formatHasNotablyChanged
V/OMXCodec(  317): [OMX.google.vorbis.decoder] enablePortAsync portIndex=1
V/OMXCodec(  317): [OMX.google.vorbis.decoder] sending OMX_CommandPortEnable(1)
V/OMXCodec(  317): allocateBuffersOnPort portIndex=1
V/OMXCodec(  317): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
V/OMXCodec(  317): [OMX.google.vorbis.decoder] allocated buffer 0xb15040b0 on output port
V/OMXCodec(  317): [OMX.google.vorbis.decoder] allocated buffer 0xb1434fb0 on output port
V/OMXCodec(  317): [OMX.google.vorbis.decoder] allocated buffer 0xb1434d30 on output port
V/OMXCodec(  317): [OMX.google.vorbis.decoder] allocated buffer 0xb15042e0 on output port
V/OMXCodec(  317): [OMX.google.vorbis.decoder] PORT_ENABLED(1)
V/OMXCodec(  317): [OMX.google.vorbis.decoder] setState mState=7 , newState=4
V/AudioCache(  317): open(48000, 2, 0x0, 1, 4)
V/AudioCache(  317): notify(0xb1187300, 6, 0, 0)
V/AudioCache(  317): ignored
V/MediaPlayerService(  317): wait for playback complete
V/AudioCache(  317): write(0xb57c4000, 4096)
V/AudioCache(  317): memcpy(0xae504000, 0xb57c4000, 4096)
V/AudioCache(  317): write(0xb57c4000, 4096)
V/AudioCache(  317): memcpy(0xae505000, 0xb57c4000, 4096)
V/AudioCache(  317): write(0xb57c4000, 4096)
V/AudioCache(  317): memcpy(0xae506000, 0xb57c4000, 4096)
V/AudioCache(  317): write(0xb57c4000, 4096)
V/AudioCache(  317): memcpy(0xae507000, 0xb57c4000, 4096)
V/AudioCache(  317): write(0xb57c4000, 4096)
V/AudioCache(  317): memcpy(0xae508000, 0xb57c4000, 4096)
V/AudioCache(  317): write(0xb57c4000, 4096)
V/AudioCache(  317): memcpy(0xae509000, 0xb57c4000, 4096)
V/AudioCache(  317): write(0xb57c4000, 4096)
V/AudioCache(  317): memcpy(0xae50a000, 0xb57c4000, 4096)
V/AudioCache(  317): write(0xb57c4000, 4096)
V/AudioCache(  317): memcpy(0xae50b000, 0xb57c4000, 4096)
V/AudioCache(  317): write(0xb57c4000, 4096)
V/AudioCache(  317): memcpy(0xae50c000, 0xb57c4000, 4096)
V/AudioCache(  317): write(0xb57c4000, 4096)
V/AudioCache(  317): memcpy(0xae50d000, 0xb57c4000, 4096)
V/AudioCache(  317): write(0xb57c4000, 4096)
V/AudioCache(  317): memcpy(0xae50e000, 0xb57c4000, 4096)
V/AudioCache(  317): write(0xb57c4000, 4096)
V/AudioCache(  317): memcpy(0xae50f000, 0xb57c4000, 4096)
V/AudioCache(  317): write(0xb57c4000, 4096)
V/AudioCache(  317): memcpy(0xae510000, 0xb57c4000, 4096)
I/qcom-bluetooth( 6360): /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 58:3f:54:73:64:c0 
V/AudioCache(  317): write(0xb57c4000, 4096)
V/AudioCache(  317): memcpy(0xae511000, 0xb57c4000, 4096)
V/AudioCache(  317): write(0xb57c4000, 4096)
V/AudioCache(  317): memcpy(0xae512000, 0xb57c4000, 4096)
V/AudioCache(  317): write(0xb57c4000, 4096)
V/AudioCache(  317): memcpy(0xae513000, 0xb57c4000, 4096)
V/AudioCache(  317): write(0xb57c4000, 4096)
V/AudioCache(  317): memcpy(0xae514000, 0xb57c4000, 4096)
V/AudioCache(  317): write(0xb57c4000, 4096)
V/AudioCache(  317): memcpy(0xae515000, 0xb57c4000, 4096)
V/AudioCache(  317): write(0xb57c4000, 4096)
V/AudioCache(  317): memcpy(0xae516000, 0xb57c4000, 4096)
V/AudioCache(  317): write(0xb57c4000, 4096)
V/AudioCache(  317): memcpy(0xae517000, 0xb57c4000, 4096)
V/AudioCache(  317): write(0xb57c4000, 4096)
V/AudioCache(  317): memcpy(0xae518000, 0xb57c4000, 4096)
V/AudioCache(  317): write(0xb57c4000, 4096)
V/AudioCache(  317): memcpy(0xae519000, 0xb57c4000, 4096)
V/AudioCache(  317): write(0xb57c4000, 4096)
V/AudioCache(  317): memcpy(0xae51a000, 0xb57c4000, 4096)
I/qcom-bluetooth( 6361): /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
V/AudioCache(  317): write(0xb57c4000, 4096)
V/AudioCache(  317): memcpy(0xae51b000, 0xb57c4000, 4096)
V/AudioCache(  317): write(0xb57c4000, 4096)
V/AudioCache(  317): memcpy(0xae51c000, 0xb57c4000, 4096)
V/AudioCache(  317): write(0xb57c4000, 4096)
V/AudioCache(  317): memcpy(0xae51d000, 0xb57c4000, 4096)
V/AudioCache(  317): write(0xb57c4000, 4096)
V/AudioCache(  317): memcpy(0xae51e000, 0xb57c4000, 4096)
V/AudioCache(  317): write(0xb57c4000, 4096)
V/AudioCache(  317): memcpy(0xae51f000, 0xb57c4000, 4096)
V/AudioCache(  317): write(0xb57c4000, 4096)
V/AudioCache(  317): memcpy(0xae520000, 0xb57c4000, 4096)
V/AudioCache(  317): write(0xb57c4000, 4096)
V/AudioCache(  317): memcpy(0xae521000, 0xb57c4000, 4096)
V/AudioCache(  317): write(0xb57c4000, 4096)
V/AudioCache(  317): memcpy(0xae522000, 0xb57c4000, 4096)
V/AudioCache(  317): write(0xb57c4000, 4096)
V/AudioCache(  317): memcpy(0xae523000, 0xb57c4000, 4096)
V/AudioCache(  317): write(0xb57c4000, 4096)
V/AudioCache(  317): memcpy(0xae524000, 0xb57c4000, 4096)
V/AudioCache(  317): write(0xb57c4000, 4096)
V/AudioCache(  317): memcpy(0xae525000, 0xb57c4000, 4096)
V/AudioCache(  317): write(0xb57c4000, 4096)
V/AudioCache(  317): memcpy(0xae526000, 0xb57c4000, 4096)
V/AudioCache(  317): write(0xb57c4000, 4096)
V/AudioCache(  317): memcpy(0xae527000, 0xb57c4000, 4096)
V/AudioCache(  317): write(0xb57c4000, 4096)
V/AudioCache(  317): memcpy(0xae528000, 0xb57c4000, 4096)
V/AudioCache(  317): write(0xb57c4000, 4096)
V/AudioCache(  317): memcpy(0xae529000, 0xb57c4000, 4096)
V/AudioCache(  317): write(0xb57c4000, 4096)
V/AudioCache(  317): memcpy(0xae52a000, 0xb57c4000, 4096)
V/AudioCache(  317): write(0xb57c4000, 4096)
V/AudioCache(  317): memcpy(0xae52b000, 0xb57c4000, 4096)
V/AudioCache(  317): write(0xb57c4000, 4096)
V/AudioCache(  317): memcpy(0xae52c000, 0xb57c4000, 4096)
V/AudioCache(  317): write(0xb57c4000, 4096)
V/AudioCache(  317): memcpy(0xae52d000, 0xb57c4000, 4096)
V/AudioCache(  317): write(0xb57c4000, 4096)
V/AudioCache(  317): memcpy(0xae52e000, 0xb57c4000, 4096)
V/AudioCache(  317): write(0xb57c4000, 4096)
V/AudioCache(  317): memcpy(0xae52f000, 0xb57c4000, 4096)
V/AudioCache(  317): write(0xb57c4000, 4096)
V/AudioCache(  317): memcpy(0xae530000, 0xb57c4000, 4096)
V/AudioCache(  317): write(0xb57c4000, 4096)
V/AudioCache(  317): memcpy(0xae531000, 0xb57c4000, 4096)
V/AudioCache(  317): write(0xb57c4000, 4096)
V/AudioCache(  317): memcpy(0xae532000, 0xb57c4000, 4096)
V/AudioCache(  317): write(0xb57c4000, 4096)
V/AudioCache(  317): memcpy(0xae533000, 0xb57c4000, 4096)
V/AudioCache(  317): write(0xb57c4000, 4096)
V/AudioCache(  317): memcpy(0xae534000, 0xb57c4000, 4096)
,V/OMXCodec(  317): [OMX.google.vorbis.decoder] No more output data.
V/AudioCache(  317): write(0xb57c4000, 4096)
V/AudioCache(  317): memcpy(0xae535000, 0xb57c4000, 4096)
V/OMXCodec(  317): [OMX.google.vorbis.decoder] There is no more output data available, not calling fillOutputBuffer
V/OMXCodec(  317): [OMX.google.vorbis.decoder] There is no more output data available, not calling fillOutputBuffer
V/AwesomePlayer(  317): postAudioEOS() 
V/AudioCache(  317): write(0xb57c4000, 280)
V/AudioCache(  317): memcpy(0xae536000, 0xb57c4000, 280)
V/AwesomePlayer(  317): postStreamDoneEvent_l() -> status:-1011 
V/AwesomePlayer(  317): onStreamDone
V/AwesomePlayer(  317): MEDIA_PLAYBACK_COMPLETE
V/AudioCache(  317): notify(0xb1187300, 2, 0, 0)
V/AudioCache(  317): playback complete
V/AwesomePlayer(  317): pause_l() 
V/AudioCache(  317): notify(0xb1187300, 7, 0, 0)
V/AudioCache(  317): ignored
V/AwesomePlayer(  317): cancelPlayerEvents
V/AudioCache(  317): wait - success
V/MediaPlayerService(  317): return size 205080, sampleRate=48000, channelCount = 2, format = 1
D/AudioPlayer(  317): Pause Playback at 1068125
V/AwesomePlayer(  317): reset_l() 
V/AudioCache(  317): notify(0xb1187300, 8, 0, 0)
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
V/OMXCodec(  317): [OMX.google.vorbis.decoder] freeing buffer 0xb1434880 on port 0
V/OMXCodec(  317): [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=3
V/OMXCodec(  317): [OMX.google.vorbis.decoder] freeing buffer 0xb1434830 on port 0
V/OMXCodec(  317): [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=2
V/OMXCodec(  317): [OMX.google.vorbis.decoder] freeing buffer 0xb1434790 on port 0
V/OMXCodec(  317): [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=1
V/OMXCodec(  317): [OMX.google.vorbis.decoder] freeing buffer 0xb1434740 on port 0
V/OMXCodec(  317): [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=0
V/OMXCodec(  317): [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
V/OMXCodec(  317): [OMX.google.vorbis.decoder] freeing buffer 0xb15042e0 on port 1
V/OMXCodec(  317): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=3
V/OMXCodec(  317): [OMX.google.vorbis.decoder] freeing buffer 0xb1434d30 on port 1
V/OMXCodec(  317): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=2
V/OMXCodec(  317): [OMX.google.vorbis.decoder] freeing buffer 0xb1434fb0 on port 1
V/OMXCodec(  317): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=1
V/OMXCodec(  317): [OMX.google.vorbis.decoder] freeing buffer 0xb15040b0 on port 1
V/OMXCodec(  317): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
V/OMXCodec(  317): [OMX.google.vorbis.decoder] setState mState=5 , newState=6
V/OMXCodec(  317): [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
V/OMXCodec(  317): [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
V/OMXCodec(  317): [OMX.google.vorbis.decoder] onStateChange 1
V/OMXCodec(  317): [OMX.google.vorbis.decoder] Now Loaded.
V/OMXCodec(  317): [OMX.google.vorbis.decoder] setState mState=6 , newState=1
V/OMXCodec(  317): [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
V/OMXCodec(  317): [OMX.google.vorbis.decoder] stopped in state 1
V/OMXCodec(  317): [OMX.google.vorbis.decoder] ~OMXCodec mstate =1
V/OMXCodec(  317): [OMX.google.vorbis.decoder] setState mState=1 , newState=0
D/AudioPlayer(  317): AudioPlayer releasing audio source
D/AudioPlayer(  317): AudioPlayer done releasing audio source
V/AwesomePlayer(  317): reset_l() 
V/AwesomePlayer(  317): cancelPlayerEvents
V/AwesomePlayer(  317): ~AwesomePlayer call
V/AwesomePlayer(  317): reset_l() 
V/AwesomePlayer(  317): cancelPlayerEvents
V/SoundPool( 6325): close(31)
V/SoundPool( 6325): pointer = 0x9ff31000, size = 205080, sampleRate = 48000, numChannels = 2
I/bt_vendor( 6128): bluetooth satus is on
D/bt_hci_bdroid( 6128): preload
D/bt_userial_mct( 6128): userial_open(port:0)
I/bt_vendor( 6128): bt-vendor : BT_VND_OP_USERIAL_OPEN
I/bt_vendor( 6128): Done intiailizing UART
I/bt_vendor( 6128): Done intiailizing UART
I/bt_userial_mct( 6128): CMD=66, EVT=66, ACL_Out=67, ACL_In=67
I/bt_vendor( 6128): Bluetooth Firmware and transport layer are initialized
I/bt-btu  ( 6128): btu_task received preload complete event
W/bt-l2cap( 6128): L2CAP - L2CA_Register() called for PSM: 0x0001
W/bt-l2cap( 6128): L2CAP - L2CA_Register() called for PSM: 0x001f
W/bt-l2cap( 6128): L2CAP - L2CA_Register() called for PSM: 0x0003
I/        ( 6128): BTE_InitTraceLevels -- TRC_HCI
I/        ( 6128): BTE_InitTraceLevels -- TRC_L2CAP
I/        ( 6128): BTE_InitTraceLevels -- TRC_RFCOMM
I/        ( 6128): BTE_InitTraceLevels -- TRC_AVDT
I/        ( 6128): BTE_InitTraceLevels -- TRC_AVRC
I/        ( 6128): BTE_InitTraceLevels -- TRC_A2D
I/        ( 6128): BTE_InitTraceLevels -- TRC_BNEP
I/        ( 6128): BTE_InitTraceLevels -- TRC_BTM
I/        ( 6128): BTE_InitTraceLevels -- TRC_HID_HOST
I/        ( 6128): BTE_InitTraceLevels -- TRC_GAP
I/        ( 6128): BTE_InitTraceLevels -- TRC_PAN
I/        ( 6128): BTE_InitTraceLevels -- TRC_SDP
I/        ( 6128): BTE_InitTraceLevels -- TRC_GATT
I/        ( 6128): BTE_InitTraceLevels -- TRC_SMP
I/        ( 6128): BTE_InitTraceLevels -- TRC_BTAPP
I/        ( 6128): BTE_InitTraceLevels -- TRC_BTIF
D/bt_userial_mct( 6128): Entering userial_read_thread()
D/QRemote ( 6325): [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
,D/QRemote ( 6325): [RemoteAppWidgetProvider.java:486:onUpdate()] oooooo 140510:RetrieveDevices is not complete. Just waiting
D/QRemote ( 6325): [RemoteAppWidgetProvider.java:499:onUpdate()] oooooo 140514:alarm set after 5000ms:4084
W/bt-btm  ( 6128): btm_decode_ext_features_page Secure conn Controller support Enabled
E/bt-btm  ( 6128): BTM_SecRegister:p_cb_info->p_le_callback == 0xa01c9061 
E/bt-btm  ( 6128): BTM_SecRegister: btm_cb.api.p_le_callback = 0xa01c9061 
,E/bt-btif ( 6128): Calling BTA_HhEnable
,E/bt-btif ( 6128): btif_storage_get_adapter_property service_mask:0x2140040
W/bt-l2cap( 6128): L2CAP - L2CA_Register() called for PSM: 0x0019
W/bt-l2cap( 6128): L2CAP - L2CA_Register() called for PSM: 0x0017
W/bt-l2cap( 6128): L2CAP - L2CA_Register() called for PSM: 0x001b
D/BluetoothAdapterProperties( 6128): Address is:58:3F:54:73:64:C0
W/bt-l2cap( 6128): L2CAP - L2CA_Register() called for PSM: 0x0011
W/bt-l2cap( 6128): L2CAP - L2CA_Register() called for PSM: 0x0013
,D/BluetoothManagerService( 1032): Bluetooth Adapter name changed to G3-1
D/BluetoothAdapterProperties( 6128): Name is: G3-1
D/BluetoothManagerService( 1032): Stored Bluetooth name: G3-1
D/BluetoothAdapterProperties( 6128): Scan Mode:20
D/BluetoothAdapterProperties( 6128): Discoverable Timeout:120
D/bt_hci_bdroid( 6128): postload
D/bt_hci_bdroid( 6128): Used up Tx Cmd credits
W/bt-l2cap( 6128): L2CAP - L2CA_Register() called for PSM: 0x000f
D/bt_hci_bdroid( 6128): Used up Tx Cmd credits
D/bt_hci_bdroid( 6128): Used up Tx Cmd credits
D/bt_hci_bdroid( 6128): Used up Tx Cmd credits
D/bt_hci_bdroid( 6128): Used up Tx Cmd credits
E/bt_mct  ( 6128): hci lib postload completed
D/bte_conf( 6128): Device ID record 1 : primary
D/bte_conf( 6128):   vendorId            = 00c4
D/bte_conf( 6128):   vendorIdSource      = 0001
D/bte_conf( 6128):   product             = 13a1
D/bte_conf( 6128):   version             = 1000
D/bte_conf( 6128):   clientExecutableURL = 
D/bte_conf( 6128):   serviceDescription  = 
D/bte_conf( 6128):   documentationURL    = 
D/bte_conf( 6128): bte_load_did_conf no section named DID2.
D/BluetoothPanServiceJni( 6128): control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
D/BluetoothAdapterState( 6128): CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
D/BluetoothAdapterProperties( 6128): ScanMode =  20
D/BluetoothAdapterProperties( 6128): State =  11
D/BluetoothAdapterProperties( 6128): mDiscoverableTimeout = 120
W/bt-smp  ( 6128): Key(LSB ~ MSB) = 0a 3c a6 fe eb 17 6a 79 a6 1f 0a 0b f9 50 a0 5f 
W/bt-smp  ( 6128): Plain text(LSB ~ MSB) = 34 67 4a 00 00 00 00 00 00 00 00 00 00 00 00 00 
V/LGBluetoothServiceAdapter( 6128): [BTUI] state:11, scanmode:20, timeout:120
W/bt-smp  ( 6128): Encrypted text(LSB ~ MSB) = 3f 5d 60 ac ae 4a 88 7f 84 06 24 99 f9 d8 7c ce 
D/BluetoothAdapterProperties( 6128): Setting state to 12
I/BluetoothAdapterState( 6128): Bluetooth adapter state changed: 11-> 12
D/BluetoothManagerService( 1032): Message: 60
D/BluetoothManagerService( 1032): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
D/BluetoothManagerService( 1032): Broadcasting onBluetoothStateChange(true) to 5 receivers.
W/bt-btm  ( 6128): Stopping oneshot timer
I/BluetoothAdapterState( 6128): Entering On State
W/sh      ( 6366): type=1400 audit(0.0:157): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6843 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,W/sh      ( 6366): type=1400 audit(0.0:158): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6843 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
D/btif_config_util( 6128): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
D/BluetoothHeadset( 1825): onBluetoothStateChange: up=true
D/BluetoothHeadset( 1032): onBluetoothStateChange: up=true
D/BluetoothA2dp( 1032): onBluetoothStateChange: up=true
D/BluetoothHeadset( 1825): onBluetoothStateChange: up=true
D/LGBluetoothServiceAdapter( 6128): [BTUI] OnState
D/BluetoothHeadset( 1825): onBluetoothStateChange: up=true
D/LGBluetoothServiceAdapter( 6128): [BTUI]         global_name: G3-1
D/LGBluetoothServiceAdapter( 6128): [BTUI]         local_name: G3-1
E/BluetoothManagerService( 1032): Fail to bind to: Intent { act=android.bluetooth.IQBluetooth }
D/BluetoothManagerService( 1032): Bluetooth State Change Intent: 11 -> 12
D/BluetoothAdapterService( 6128): [BTUI] autoConnect() : not allowed
I/[SystemUI]BluetoothHandler( 1447): Receive : BluetoothAdapter.ACTION_STATE_CHANGED
D/LGBluetoothAPIService( 1915): [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
D/LGBluetoothAPIService( 1915): Message: 1
D/LGBluetoothAPIService( 1915): MESSAGE_BOOT_COMPLETED
D/BluetoothManagerService( 1032): BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
D/BluetoothManagerService( 1032): Message: 40
D/BluetoothManagerService( 1032): MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
,I/LGBluetoothAPIService( 1915): [BTUI] LGBluetoothAPIService Binding Success
I/BluetoothMapService( 6128): onReceive: android.bluetooth.adapter.action.STATE_CHANGED
D/BluetoothMapService( 6128): STATE_ON
W/bt-smp  ( 6128): Key(LSB ~ MSB) = 0a 3c a6 fe eb 17 6a 79 a6 1f 0a 0b f9 50 a0 5f 
W/bt-smp  ( 6128): Plain text(LSB ~ MSB) = 73 de 49 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 6128): Encrypted text(LSB ~ MSB) = 6a 0a b3 fb 7e 59 43 53 0c 94 97 64 47 41 4e 2c 
W/bt-btm  ( 6128): Stopping oneshot timer
,W/ContextImpl( 6167): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
D/LGBluetoothAPIServer( 6128): [BTUI] onCreate()
D/LGBluetoothAPIServer( 6128): [BTUI] onBind()
D/LGBluetoothAPIService( 1915): [BTUI] LGBluetoothAPIServiceConnection: connected to LGBluetoothAPIAdapter
D/LGBluetoothAPIService( 1915): Message: 100
D/LGBluetoothAPIService( 1915): MESSAGE_BLUETOOTH_SERVICE_CONNECTED
W/bt-smp  ( 6128): Key(LSB ~ MSB) = 0a 3c a6 fe eb 17 6a 79 a6 1f 0a 0b f9 50 a0 5f 
W/bt-smp  ( 6128): Plain text(LSB ~ MSB) = 1d b5 6d 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 6128): Encrypted text(LSB ~ MSB) = bc dc 50 76 4e c5 89 40 a7 9d 0f a4 91 59 ec 55 
W/bt-btm  ( 6128): Stopping oneshot timer
,D/LGBluetoothDeviceModeControllManager( 6128): [BTUI] checkDeviceModeAndSet, sinkMode : false
I/qcom-bt-wlan-coex( 6373): /system/etc/init.qcom.coex.sh: btwlancoex/abtfilt not available 
W/bt-smp  ( 6128): Key(LSB ~ MSB) = 0a 3c a6 fe eb 17 6a 79 a6 1f 0a 0b f9 50 a0 5f 
W/bt-smp  ( 6128): Plain text(LSB ~ MSB) = f6 92 7f 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 6128): Encrypted text(LSB ~ MSB) = 3b 39 e1 86 3c 0e d6 5d df bf 67 2e fc 89 03 1a 
W/bt-btm  ( 6128): Stopping oneshot timer
D/LocalBluetoothProfileManager( 6167): Adding local A2DP profile
D/BluetoothManagerService( 1032): Message: 30
,D/BluetoothAdapterService( 6128): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2b2e07a9
V/BluetoothPbapService( 6128): Pbap Service onCreate
V/BluetoothPbapService( 6128): Starting PBAP service
D/LGBluetoothPbapAdapter( 6128): [BTUI] getInstance : create
V/BluetoothPbapService( 6128): action: android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothPbapService( 6128): state: 12
V/BluetoothMapService( 6128): Handler(): got msg=1
D/BluetoothMapMasInstance( 6128): Map Service startRfcommSocketListener
W/bt-smp  ( 6128): Key(LSB ~ MSB) = 0a 3c a6 fe eb 17 6a 79 a6 1f 0a 0b f9 50 a0 5f 
W/bt-smp  ( 6128): Plain text(LSB ~ MSB) = 15 0f 62 00 00 00 00 00 00 00 00 00 00 00 00 00 
V/BluetoothPbapReceiver( 6128): PbapReceiver onReceive 
W/bt-smp  ( 6128): Encrypted text(LSB ~ MSB) = 86 ae e7 e7 1b 72 d0 71 4a 00 ab 55 ca bf 16 33 
V/BluetoothPbapReceiver( 6128): ***********action = android.bluetooth.adapter.action.STATE_CHANGED
W/bt-btm  ( 6128): Stopping oneshot timer
V/BluetoothPbapReceiver( 6128): ***********state = 12
V/BluetoothPbapService( 6128): Handler(): got msg=1
D/LocalBluetoothProfileManager( 6167): Adding local HEADSET profile
V/BluetoothPbapService( 6128): Pbap Service startRfcommSocketListener
V/BluetoothPbapService( 6128): Pbap Service initSocket
D/BluetoothMapMasInstance( 6128): MAS initSocket()
D/BluetoothMapMasInstance( 6128):   masId = 00
D/BluetoothMapMasInstance( 6128):   msgTypes = 0e
D/BluetoothMapMasInstance( 6128):   masName = SMS/MMS
D/BluetoothMapMasInstance( 6128):   SDP string = 000eSMS/MMS
D/BluetoothManagerService( 1032): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1032): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
W/BluetoothAdapter( 6128): getBluetoothService() called with no BluetoothManagerCallback
W/BluetoothAdapter( 6128): getBluetoothService() called with no BluetoothManagerCallback
D/LGBluetoothServiceAdapter( 6128): [BTUI] createSocketChannel FD=73 mFd=0
V/BluetoothPbapService( 6128): Succeed to create listening socket 
V/BluetoothPbapService( 6128): Accepting socket connection...
D/LGBluetoothServiceAdapter( 6128): [BTUI] createSocketChannel FD=75 mFd=73
V/BluetoothMapMasInstance( 6128): Succeed to create listening socket 
D/BluetoothMapMasInstance( 6128): Accepting socket connection...
D/BluetoothManagerService( 1032): Message: 30
D/BluetoothManagerService( 1032): Message: 30
,D/BluetoothManagerService( 1032): Message: 30
D/LocalBluetoothProfileManager( 6167): Adding local MAP profile
D/BluetoothMap( 6167): Create BluetoothMap proxy object
D/BluetoothManagerService( 1032): Message: 30
D/BluetoothManagerService( 1032): Message: 30
,V/BluetoothPbapService( 6128): Pbap Service onBind
D/LocalBluetoothProfileManager( 6167): LocalBluetoothProfileManager construction complete
D/LGBluetoothUserBindClient( 6167): [BTUI] initUserBindClient
W/ContextImpl( 6167): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.android.settings.bluetooth.LGBluetoothUserBindClient.initUserBindClient:90 com.android.settings.bluetooth.LGBluetoothUserBindClient.<init>:55 com.android.settings.bluetooth.LGBluetoothUserBindClient.getInstance:47 
D/DockEventReceiver( 6167): finishStartingService: stopping service
D/BluetoothA2dp( 6167): Proxy object connected
D/A2dpProfile( 6167): Bluetooth service connected
,D/BluetoothHeadset( 6167): Proxy object connected
D/HeadsetProfile( 6167): Bluetooth service connected
,D/BluetoothInputDevice( 6167): Proxy object connected
D/HidProfile( 6167): Bluetooth service connected
D/BluetoothAdapterProperties( 6128): Discoverable Timeout:120
D/LGBluetoothDeviceModeControllManager( 6128): adapterPropertyChangedCallback on  LGAdapter : do nothing - 9
D/BluetoothAdapterProperties( 6128): Scan Mode:21
D/LGBluetoothDeviceModeControllManager( 6128): getDeviceMode  deviceMode 0
D/BluetoothPan( 6167): BluetoothPAN Proxy object connected
D/PanProfile( 6167): Bluetooth service connected
D/BluetoothMap( 6167): Proxy object connected
D/MapProfile( 6167): Bluetooth service connected
D/BluetoothMap( 6167): getConnectedDevices()
,V/BluetoothMapService( 6128): getConnectedDevices()
D/BluetoothPbap( 6167): Proxy object connected
D/PbapServerProfile( 6167): Bluetooth service connected
D/LGBluetoothUserBindClient( 6167): [BTUI] onServiceConnected
D/BluetoothPermissionRequest( 6167): onReceive
D/LGBluetoothFeatureConfig( 6167): isPrivacyLogsEnabled : true
D/LGBluetoothUtils( 6167): [BTUI] FileNotFound: readProperty
D/LGBluetoothResetSettingReceiver( 6167): return without doing reset settings.
V/BluetoothOppReceiver( 6128): Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_ON
I/LGBluetoothOppAdapter( 6128): [BTUI] startOppService()
V/BluetoothOppManager( 6128): restoreApplicationData! falsefalsenullnull
,D/LGBluetoothFeatureConfig( 6128): isPrivacyLogsEnabled : true
,V/BtOppService( 6128): onCreate
V/BluetoothOppNotification( 6128): send message
V/BtOppService( 6128): Starting RfcommListener
D/BluetoothOppPreference( 6128): Dumping Names:  
D/BluetoothOppPreference( 6128): {}
,D/BluetoothOppPreference( 6128): Dumping Channels:  
D/BluetoothOppPreference( 6128): {}
V/BtOppService( 6128): onStartCommand
V/BtOppService( 6128): pendingUpdate is true keepUpdateThread is false sListenStarted is true
V/BluetoothFtpReceiver( 6128): BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothFtpReceiver( 6128): BluetoothFtpReceiver Start Service
V/BluetoothOppNotification( 6128): new notify threadi!
V/BluetoothOppNotification( 6128): send delay message
V/BtOppService( 6128): start RfcommListener
V/BtOppService( 6128): Deleted complete outbound shares, number =  0
V/BtOppService( 6128): RfcommListener started
V/BtOppRfcommListener( 6128): Starting RFCOMM listener....
D/BluetoothManagerService( 1032): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
V/BtOppService( 6128): Deleted complete inbound failed shares, number = 0
W/BluetoothAdapter( 6128): getBluetoothService() called with no BluetoothManagerCallback
V/BluetoothOppProvider( 6128): starting query, database is not null; projection[0] is _id; selection is direction=1 AND status=200 AND visibility=1; selectionArgs is null; sort is _id.
,V/BluetoothOppProvider( 6128): created cursor android.database.sqlite.SQLiteCursor@183080bb on behalf of 
D/LGBluetoothServiceAdapter( 6128): [BTUI] createSocketChannel FD=79 mFd=75
V/BluetoothOppProvider( 6128): starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
V/BtOppRfcommListener( 6128): Started RFCOMM listener....
I/BtOppRfcommListener( 6128): Accept thread started.
V/BluetoothOppProvider( 6128): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
V/BtOppRfcommListener( 6128): Accepting connection...
D/BluetoothAdapterService( 6128): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2b2e07a9
V/BluetoothFtpService( 6128): Ftp Service onCreate
I/BluetoothFtpService( 6128): Ftp Service onCreate
V/BluetoothFtpService( 6128): Ftp Service onStartCommand
V/BluetoothFtpService( 6128): action: android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothFtpService( 6128): Starting Listening on sockets
V/BtOppService( 6128): ContentObserver received notification
V/BtOppService( 6128): ContentObserver received notification
V/BluetoothSapReceiver( 6128): [BTUI] checkServiceStart
V/BluetoothSapReceiver( 6128): [BTUI] region:EU country:EU
V/BluetoothSapReceiver( 6128): SapReceiver onReceive 
V/BluetoothSapReceiver( 6128): action = android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothSapReceiver( 6128):  Bluetooth Adapter state = 12
V/BluetoothSapReceiver( 6128): Calling SAP service start service with action = null
V/BluetoothFtpService( 6128): Handler(): got msg=1
V/BluetoothFtpService( 6128): Ftp Service startRfcommSocketListener
V/BluetoothFtpService( 6128): Ftp Service initSocket
V/BluetoothOppProvider( 6128): created cursor android.database.sqlite.SQLiteCursor@19876131 on behalf of 
V/BluetoothOppProvider( 6128): created cursor android.database.sqlite.SQLiteCursor@3b278016 on behalf of 
D/BluetoothManagerService( 1032): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
V/BluetoothOppNotification( 6128): mUpdateCompleteNotification = true
W/BluetoothAdapter( 6128): getBluetoothService() called with no BluetoothManagerCallback
V/BtOppService( 6128): pendingUpdate is true keepUpdateThread is false sListenStarted is true
V/BluetoothOppProvider( 6128): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
V/BluetoothOppProvider( 6128): starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
,D/AuthorizationBluetoothService( 2063): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
D/LGBluetoothServiceAdapter( 6128): [BTUI] createSocketChannel FD=80 mFd=79
V/BluetoothFtpService( 6128): Succeed to create listening socket on channel 20
V/BluetoothFtpService:RfcommSocketAcceptThread( 6128): Run Accept thread
V/BluetoothOppProvider( 6128): created cursor android.database.sqlite.SQLiteCursor@1fdc6d97 on behalf of 
V/BluetoothOppNotification( 6128): update too frequent, put in queue
V/BluetoothOppProvider( 6128): created cursor android.database.sqlite.SQLiteCursor@1408db84 on behalf of 
V/BtOppService( 6128): pendingUpdate is false keepUpdateThread is false sListenStarted is true
V/BluetoothOppNotification( 6128): outbound: succ-0  fail-0
V/BluetoothOppNotification( 6128): outbound notification was removed.
V/BluetoothOppProvider( 6128): starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
D/BluetoothAdapterService( 6128): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2b2e07a9
V/BluetoothSapService( 6128): Sap Service onCreate
V/BluetoothSapService( 6128): action: android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothSapService( 6128): state: 12
V/BluetoothSapService( 6128): Starting SAP server process
V/BluetoothOppProvider( 6128): created cursor android.database.sqlite.SQLiteCursor@2cfa2bf0 on behalf of 
,V/BluetoothOppNotification( 6128): inbound: succ-0  fail-0
V/BluetoothSapService( 6128): SAP Service startRfcommListenerThread
V/BluetoothSapService( 6128): Sap Service initRfcommSocket
V/BluetoothOppNotification( 6128): inbound notification was removed.
,V/BluetoothOppProvider( 6128): starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
D/BluetoothManagerService( 1032): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
W/BluetoothAdapter( 6128): getBluetoothService() called with no BluetoothManagerCallback
W/sapd    ( 6389): type=1400 audit(0.0:159): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6843 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
W/sapd    ( 6389): type=1400 audit(0.0:160): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6843 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
V/BluetoothOppProvider( 6128): created cursor android.database.sqlite.SQLiteCursor@b880569 on behalf of 
D/LGBluetoothServiceAdapter( 6128): [BTUI] createSocketChannel FD=83 mFd=80
V/BluetoothSapService( 6128): Succeed to create listening socket 
V/BluetoothSapService( 6128): Accepting socket connection...
V/BT_SAP  ( 6389): Event pipe created
V/BT_SAP  ( 6389): create_server_socket qcom.sap.server
V/BT_SAP  ( 6389): created socket fd 6
I/UEI.SmartControl( 5873): Supports setup maps: true
,D/UEI.SmartControl( 5873): QS start statue = true Error code = 0
,I/UEI.SmartControl( 5873): QS version = v2.7.10.1_RC1,
I/UEI.SmartControl( 5873): QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
I/UEI.SmartControl( 5873): ### init IR Blaster...
D/serial_port( 5873): Configuring serial port
,E/UEI.SmartControl( 5873): UEIBLaster setting for 616
I/UEI.SmartControl( 5873): Setting serial record hearder size = 2
I/UEI.SmartControl( 5873): configuring settings for MAXQ616
,I/UEI.SmartControl( 5873): Get version...
D/UEI.SmartControl( 5873): serial port data available: 21
,D/UEI.SmartControl( 5873): MAXQ616 A2-X4 software.
I/UEI.SmartControl( 5873): IR Blaster version: 256702256704300002
I/UEI.SmartControl( 5873): QS saving settings...
D/UEI.SmartControl( 5873): IR Blaster version: 25672567
,D/UEI.SmartControl( 5873): serial port data available: 4
,I/UEI.SmartControl( 5873): Device manager: loading config....
,W/ContextImpl( 5873): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
E/UEI.SmartControl( 5873): Services init done
,D/UEI.SmartControl( 5873): QS Service init finished
D/UEI.SmartControl( 5873): ----------- loading internal config...
D/UEI.SmartControl( 5873): QS Service version name: 2.1.91
D/UEI.SmartControl( 5873): QS Service version code: 201091
D/UEI.SmartControl( 5873): Service requested: Control
E/UEI.SmartControl( 5873): Loading SETTINGS...
D/UEI.SmartControl( 5873): Request IControl service: devices are loaded...
,I/QRemote ( 6325): [RemoteControlManager.java:183:onServiceConnected()] oooooo start
D/UEI.SmartControl( 5873): Internal service binding...
I/UEI.SmartControl( 5873): ------ IControl API: 11
D/UEI.SmartControl( 5873): File observer start...
,E/UEI.SmartControl( 5873): IR Port is disabled: false
D/UEI.SmartControl( 5873): Starting file observer...
D/UEI.SmartControl( 5873): -- Open brand translation xml: brands_translations_ko
I/UEI.SmartControl( 5873): Registering callback...
I/UEI.SmartControl( 5873): ------ IControl API: 19
I/UEI.SmartControl( 5873): Registering Services Ready callback...
I/UEI.SmartControl( 5873): Notify AllClients services are ready: 0
D/UEI.SmartControl( 5873): -----service ready thread exits
I/QRemote ( 6325): [RemoteControlManager.java:660:QSSetupIsReady()] oooooo 140517:sdkIsReady callback... get functions. Result:0
,D/QRemote ( 6325): [RemoteControlManager.java:388:handleMessage()] oooooo 140510:START_SESSION
D/QRemote ( 6325): [RemoteControlManager.java:394:handleMessage()] oooooo 140510:send retrieve msg
D/QRemote ( 6325): [RemoteControlManager.java:322:handleMessage()] oooooo 140510:handler call retrieveDevices
D/QRemote ( 6325): [RemoteControlManager.java:336:retrieveDevices()] oooooo retrieveDevices: start
I/UEI.SmartControl( 5873): ------ IControl API: 8
D/QRemote ( 6325): [RemoteControlManager.java:340:retrieveDevices()] oooooo retrieveDevices: 0
D/QRemote ( 6325): [RemoteControlManager.java:345:retrieveDevices()] oooooo retrieveDevices complete:true
,D/QRemote ( 6325): [RemoteControlManager.java:353:retrieveDevices()] oooooo retrieveDevices: notifyDataSetChanged()
D/QRemote ( 6325): [QRemoteApplication.java:145:onRemoteControlStateChanged()] oooooo onRemoteControlStateChanged called in QRemoteApp
D/QRemote ( 6325): [QRemoteApplication.java:158:onRemoteControlStateChanged()] oooooo Widget count is [1]. send broadcast
D/QRemote ( 6325): [QRemoteApplication.java:160:onRemoteControlStateChanged()] oooooo Widget[0]:3
,D/QRemote ( 6325): [QRemoteApplication.java:188:onRemoteControlStateChanged()] oooooo 140526:onRemoteControlStateChanged&sdkIsReady. stop Service
V/QRemote ( 6325): [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
D/QRemote ( 6325): [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
E/QRemote ( 6325): [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
D/QRemote ( 6325): [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
D/QRemote ( 6325): [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
,D/QRemote ( 6325): [RemoteAppWidgetProvider.java:506:onUpdate()] oooooo 140510:RetrieveDevices complete. Start loading
D/QRemote ( 6325): [RemoteAppWidgetProvider.java:508:onUpdate()] oooooo 140510:appWidgetIds[0]:3 loading
D/QRemote ( 6325): [RemoteAppWidgetManager.java:41:startLoading()] oooooo 140518:widgetId[3] loading start at [1454523196307]
D/QRemote ( 6325): [QRemoteService.java:207:onDestroy()] oooooo 140526:onDestroy
I/ActivityManager( 1032): Killing 5557:com.android.gallery3d/u0a27 (adj 15): empty #17
,D/QRemote ( 6325): [RemoteAppWidgetManager.java:239:doInBackground()] oooooo 140407:doinBack arr:0
,I/wpa_supplicant( 6166): wlan0: CTRL-EVENT-SCAN-STARTED 
,D/WifiMonitor( 1032): Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1032): WifiMonitor:wlan0 cnt=13 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1032): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1032): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
,W/libprocessgroup( 1032): failed to open /acct/uid_10027/pid_5557/cgroup.procs: No such file or directory
V/QRemote ( 6325): [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.widget_ui_update
,E/QRemote ( 6325): [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
D/QRemote ( 6325): [RemoteAppWidgetProvider.java:171:onReceive()] oooooo total:0
D/QRemote ( 6325): [RemoteAppWidgetProvider.java:172:onReceive()] oooooo selected:0
D/QRemote ( 6325): [RemoteAppWidgetProvider.java:173:onReceive()] oooooo arr:[]
D/QRemote ( 6325): [RemoteAppWidgetProvider.java:174:onReceive()] oooooo appWidgetId:3
D/QRemote ( 6325): [RemoteAppWidgetProvider.java:815:updateRemoteViews()] oooooo UpdateRemoteViews3:widgetId:3
D/QRemote ( 6325): [RemoteAppWidgetProvider.java:986:updateRemoteViews()] oooooo updateAppWidget5:widgetId:3]
,V/BluetoothOppNotification( 6128): new notify threadi!
V/BluetoothOppNotification( 6128): send delay message
,V/BluetoothOppProvider( 6128): starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
V/BluetoothOppProvider( 6128): created cursor android.database.sqlite.SQLiteCursor@32c67bee on behalf of 
V/BluetoothOppNotification( 6128): mUpdateCompleteNotification = true
V/BluetoothOppProvider( 6128): starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
V/BluetoothOppProvider( 6128): created cursor android.database.sqlite.SQLiteCursor@2059788f on behalf of 
V/BluetoothOppNotification( 6128): outbound: succ-0  fail-0
V/BluetoothOppNotification( 6128): outbound notification was removed.
V/BluetoothOppProvider( 6128): starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
V/BluetoothOppProvider( 6128): created cursor android.database.sqlite.SQLiteCursor@166e171c on behalf of 
V/BluetoothOppNotification( 6128): inbound: succ-0  fail-0
,V/BluetoothOppNotification( 6128): inbound notification was removed.
V/BluetoothOppProvider( 6128): starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
V/BluetoothOppProvider( 6128): created cursor android.database.sqlite.SQLiteCursor@13928f25 on behalf of 
E/wpa_supplicant( 6166): USIM:  scard_init function
I/wpa_supplicant( 6166): Trying to associate with SSID 'NG700'
E/WifiMonitor( 1032): WifiMonitor:wlan0 cnt=14 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
E/WifiMonitor( 1032): handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
D/WifiMonitor( 1032): Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
E/WifiMonitor( 1032): WifiMonitor:wlan0 cnt=15 dispatchEvent: WPS-AP-AVAILABLE 
W/WifiMonitor( 1032): couldn't identify event type - WPS-AP-AVAILABLE 
D/WifiMonitor( 1032): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
E/WifiMonitor( 1032): WifiMonitor:wlan0 cnt=16 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
E/WifiStateMachine( 1032):  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=2 known=0 got=2 bcn=0
E/WifiStateMachine( 1032):  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=2 known=0 got=2 bcn=0
E/WifiStateMachine( 1032):  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=2 known=0 got=2 bcn=0
E/WifiStateMachine( 1032):  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=2 known=0 got=2 bcn=0
I/WifiNative-HAL( 1032): startHal
E/wifi    ( 1032): getStaticLongField sWifiHalHandle 0x9892e8cc
E/WifiHAL ( 1032): Could not connect handle
D/wifi    ( 1032): halHandle = 0x0, mVM = 0xb487c280, mCls = 0x80176a
I/WifiNative-HAL( 1032): Could not start hal
D/WifiNative-wlan0( 1032): doString: [BSS RANGE=0- MASK=0x21987]
E/WifiStateMachine( 1032):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 16 0 rt=121087  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
E/WifiStateMachine( 1032):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 16 0 rt=121088  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
I/StatusBar.NetworkController( 1447): networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1447): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1447): refreshViews: Data not connected!! Set no data type icon / Roaming
W/Settings( 1032): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1032): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1032): NETWORK_STATE_CHANGED_ACTION [SCANNING]
W/Settings( 1032): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1032): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1032): NETWORK_STATE_CHANGED_ACTION [CONNECTING]
D/WifiServerServiceExt( 1032): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1032): setSupplicantStateASSOCIATING
I/StatusBar.NetworkController( 1447): networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1447): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1447): refreshViews: Data not connected!! Set no data type icon / Roaming
D/PostponalbeReceiver( 5168): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
V/WiFiOffLoadBroadcast( 6167): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 6167): MCCMNC not supported: null
D/QRemote ( 6325): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6325): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 6325): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
D/PostponalbeReceiver( 5168): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
V/WiFiOffLoadBroadcast( 6167): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 6167): MCCMNC not supported: null
,I/jxcore-log( 6067): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMultiplex.js
I/jxcore-log( 6067): 
,D/QRemote ( 6325): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6325): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 6325): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
I/jxcore-log( 6067): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
I/jxcore-log( 6067): 
,I/jxcore-log( 6067): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
I/jxcore-log( 6067): 
,I/jxcore-log( 6067): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliCryptoManager.js
I/jxcore-log( 6067): 
I/jxcore-log( 6067): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliEmitter.js
I/jxcore-log( 6067): 
,I/jxcore-log( 6067): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNativeLayer.js
I/jxcore-log( 6067): 
,I/jxcore-log( 6067): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationManager.js
I/jxcore-log( 6067): 
,I/jxcore-log( 6067): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
I/jxcore-log( 6067): 
I/wpa_supplicant( 6166): wlan0: CTRL-EVENT-ASSOC-REJECT bssid=c0:ff:d4:d3:aa:48 status_code=1
D/WifiMonitor( 1032): Event [IFNAME=wlan0 CTRL-EVENT-ASSOC-REJECT bssid=c0:ff:d4:d3:aa:48 status_code=1]
E/WifiMonitor( 1032): WifiMonitor:wlan0 cnt=17 dispatchEvent: CTRL-EVENT-ASSOC-REJECT bssid=c0:ff:d4:d3:aa:48 status_code=1
D/WifiMonitor( 1032): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=00:00:00:00:00:00 SSID=NG700]
E/WifiMonitor( 1032): WifiMonitor:wlan0 cnt=18 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=00:00:00:00:00:00 SSID=NG700
E/WifiStateMachine( 1032):  DisconnectedState ASSOCIATION_REJECTION_EVENT 17 1 c0:ff:d4:d3:aa:48 blacklist=false rt=123147
E/WifiStateMachine( 1032):  ConnectModeState ASSOCIATION_REJECTION_EVENT 17 1 c0:ff:d4:d3:aa:48 blacklist=false rt=123147
,E/WifiStateMachine( 1032):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 18 0 rt=123152  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: DISCONNECTED
E/WifiStateMachine( 1032):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 18 0 rt=123153  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: DISCONNECTED
D/WifiHS20( 1032): hidePasspointNotification off =false
I/StatusBar.NetworkController( 1447): networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1447): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1447): refreshViews: Data not connected!! Set no data type icon / Roaming
,W/Settings( 1032): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1032): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1032): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
D/WifiServerServiceExt( 1032): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1032): setSupplicantStateDISCONNECTED
D/PostponalbeReceiver( 5168): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
I/PCSuite ( 6228): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 6228): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 6228): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,V/WiFiOffLoadBroadcast( 6167): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 6167): MCCMNC not supported: null
D/QRemote ( 6325): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6325): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 6325): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,I/wpa_supplicant( 6166): wlan0: CTRL-EVENT-SCAN-STARTED 
,D/WifiMonitor( 1032): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
E/WifiMonitor( 1032): WifiMonitor:wlan0 cnt=19 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
D/WifiMonitor( 1032): Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1032): WifiMonitor:wlan0 cnt=20 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1032): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1032): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
E/WifiStateMachine( 1032):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 19 0 rt=123250  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
D/WifiHS20( 1032): hidePasspointNotification off =false
W/Settings( 1032): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1032): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1032): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
D/PostponalbeReceiver( 5168): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
I/StatusBar.NetworkController( 1447): networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1447): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1447): refreshViews: Data not connected!! Set no data type icon / Roaming
,I/PCSuite ( 6228): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
,D/PCSuite ( 6228): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 6228): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
E/WifiStateMachine( 1032):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 19 0 rt=123270  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
I/StatusBar.NetworkController( 1447): networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1447): mWifiConnected = false, mWifiLevel = 0
W/Settings( 1032): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1032): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1032): NETWORK_STATE_CHANGED_ACTION [SCANNING]
D/StatusBar.NetworkController( 1447): refreshViews: Data not connected!! Set no data type icon / Roaming
V/WiFiOffLoadBroadcast( 6167): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WifiServerServiceExt( 1032): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1032): setSupplicantStateSCANNING
,D/WiFiOffLoadBroadcast( 6167): MCCMNC not supported: null
D/QRemote ( 6325): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6325): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 6325): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
D/PostponalbeReceiver( 5168): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,V/WiFiOffLoadBroadcast( 6167): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 6167): MCCMNC not supported: null
D/QRemote ( 6325): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,D/QRemote ( 6325): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 6325): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
D/UEI.SmartControl( 5873): Internal timer expired: 2
D/UEI.SmartControl( 5873): unbind internal service
,D/serial_port( 5873): close(fd = 24)
,I/UEI.SmartControl( 5873): Serial port is closed.
,I/wpa_supplicant( 6166): Trying to associate with SSID 'NG700'
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
E/WifiStateMachine( 1032):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 23 0 rt=125321  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
W/Settings( 1032): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1032): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1032): NETWORK_STATE_CHANGED_ACTION [SCANNING]
,I/StatusBar.NetworkController( 1447): networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1447): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1447): refreshViews: Data not connected!! Set no data type icon / Roaming
W/Settings( 1032): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1032): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1032): NETWORK_STATE_CHANGED_ACTION [CONNECTING]
,I/StatusBar.NetworkController( 1447): networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1447): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1447): refreshViews: Data not connected!! Set no data type icon / Roaming
E/WifiStateMachine( 1032):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 23 0 rt=125351  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
D/WifiServerServiceExt( 1032): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1032): setSupplicantStateASSOCIATING
D/PostponalbeReceiver( 5168): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
V/WiFiOffLoadBroadcast( 6167): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6167): MCCMNC not supported: null
D/QRemote ( 6325): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6325): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 6325): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,D/PostponalbeReceiver( 5168): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
V/WiFiOffLoadBroadcast( 6167): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6167): MCCMNC not supported: null
D/QRemote ( 6325): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6325): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 6325): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,I/wpa_supplicant( 6166): wlan0: Associated with c0:ff:d4:d3:aa:48
,D/WifiMonitor( 1032): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
E/WifiMonitor( 1032): WifiMonitor:wlan0 cnt=24 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
I/wpa_supplicant( 6166): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 6166): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
D/WifiMonitor( 1032): Event [IFNAME=wlan0 Associated with c0:ff:d4:d3:aa:48]
E/WifiMonitor( 1032): WifiMonitor:wlan0 cnt=25 dispatchEvent: Associated with c0:ff:d4:d3:aa:48
D/WifiMonitor( 1032): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1032): WifiMonitor:wlan0 cnt=26 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
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
,E/WifiStateMachine( 1032):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 24 0 rt=126663  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
E/WifiStateMachine( 1032):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 24 0 rt=126664  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
E/WifiStateMachine( 1032):  DisconnectedState CMD_ASSOCIATED_BSSID 25 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=126666
E/WifiStateMachine( 1032):  ConnectModeState CMD_ASSOCIATED_BSSID 25 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=126666
D/Tethering( 1032): sendTetherStateChangedBroadcast 1, 0, 0
D/UsbSettingsReceiver( 6167): [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
D/UsbSettingsReceiver( 6167): [AUTORUN] sys.usb.config = ptp_only,adb
D/UsbSettingsReceiver( 6167): [AUTORUN] sys.usb.state = ptp_only,adb
D/UsbSettingsReceiver( 6167): [AUTORUN] persist.sys.usb.config = ptp_only,adb
,E/WifiStateMachine( 1032):  DriverStartedState CMD_ASSOCIATED_BSSID 25 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=126676
E/WifiStateMachine( 1032):  SupplicantStartedState CMD_ASSOCIATED_BSSID 25 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=126677
E/WifiStateMachine( 1032):  DefaultState CMD_ASSOCIATED_BSSID 25 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=126677
E/WifiStateMachine( 1032):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 26 0 rt=126678  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: FOUR_WAY_HANDSHAKE
D/libc-netbsd(  313): default dns: query_ipv6=0, query_ipv4=0
D/DSQN    ( 1032): DNSproblemNotiEnabled is disabled ignore DNS fail CB
,W/Settings( 1032): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1032): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1032): NETWORK_STATE_CHANGED_ACTION [CONNECTING]
,I/StatusBar.NetworkController( 1447): networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
E/WifiStateMachine( 1032):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 26 0 rt=126714  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: FOUR_WAY_HANDSHAKE
E/WifiStateMachine( 1032):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 27 0 rt=126715  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: GROUP_HANDSHAKE
E/WifiStateMachine( 1032):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 27 0 rt=126716  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: GROUP_HANDSHAKE
E/WifiStateMachine( 1032):  DisconnectedState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=126716
I/StatusBar.NetworkController( 1447): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1447): refreshViews: Data not connected!! Set no data type icon / Roaming
,W/Settings( 1032): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1032): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1032): NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
I/StatusBar.NetworkController( 1447): networkInfo=[type: WIFI[], state: CONNECTING/AUTHENTICATING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1447): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1447): refreshViews: Data not connected!! Set no data type icon / Roaming
E/WifiStateMachine( 1032):  ConnectModeState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=126731
D/WifiNative-wlan0( 1032): doString: [STATUS]
D/WifiMonitor( 1032): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1032): WifiMonitor:wlan0 cnt=31 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/WifiNative-wlan0( 1032):    returned bssid=c0:ff:d4:d3:aa:48 ssid=NG700 id=0 mode=station pairwise_cipher=CCMP group_cipher=CCMP key_mgmt=WPA2-PSK wpa_state=COMPLETED p2p_device_address=02:9a:02:7b:60:ac address=c4:9a:02:7b:60:ac uuid=530d3fd0-1ba3-5409-a336-ff4e42af59a2
I/WifiServiceExtension( 1032): setVHTCapabilityType  : false
I/WifiServerServiceExt( 1032): wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
I/WifiServerServiceExt( 1032): setKeepAlivePacketInterval msec : 60
,D/UsbSettingsReceiver( 6167): [AUTORUN] onReceive() : app userid = 0, current userid = 0
W/Settings( 1032): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1032): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1032): NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
I/StatusBar.NetworkController( 1447): networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1447): mWifiConnected = false, mWifiLevel = 0
,D/StatusBar.NetworkController( 1447): refreshViews: Data not connected!! Set no data type icon / Roaming
W/Settings( 1032): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1032): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1032): NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
,I/StatusBar.NetworkController( 1447): networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1447): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1447): refreshViews: Data not connected!! Set no data type icon / Roaming
V/AlarmManager( 1032): ELAPSED_WAKEUP set : Alarm{ae67acd type 2 when 117585 com.google.android.gms} when 117585
D/UsbSettingsControl( 6167): [AUTORUN] getUsbConnected() : connected=true
D/UsbSettingsReceiver( 6167): [AUTORUN] onReceive() : availableList=[wlan0]
D/UsbSettingsReceiver( 6167): [AUTORUN] onReceive() : activeList=[]
D/UsbSettingsReceiver( 6167): [AUTORUN] onReceive() : errorList=[]
D/UsbSettingsControl( 6167): [AUTORUN] isAutorunTimer() : mAutorunChanging=false
D/UsbSettingsReceiver( 6167): [AUTORUN] onReceive() : TetherState Changed=wlan0
D/UsbSettingsControl( 6167): [AUTORUN] setTetherStatus() : status=false
,D/PostponalbeReceiver( 5168): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
D/ConnectivityService( 1032): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
E/WifiConfigStore( 1032): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/WifiNative-wlan0( 1032): doBoolean: SET_NETWORK 0 bssid any
D/ConnectivityService( 1032): Got NetworkAgent Messenger
V/WiFiOffLoadBroadcast( 6167): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/ConnectivityService( 1032): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
D/ConnectivityService( 1032): NetworkAgent connected
D/WifiNative-wlan0( 1032): SET_NETWORK 0 bssid any: returned true
D/WifiNative-wlan0( 1032): doBoolean: SAVE_CONFIG
,D/WifiNative-wlan0( 1032): SAVE_CONFIG: returned true
E/WifiConfigStore( 1032): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/WifiNative-wlan0( 1032): doBoolean: SET_NETWORK 0 bssid any
D/WifiNative-wlan0( 1032): SET_NETWORK 0 bssid any: returned true
D/WifiNative-wlan0( 1032): doBoolean: SAVE_CONFIG
D/WiFiOffLoadBroadcast( 6167): MCCMNC not supported: null
D/WifiNative-wlan0( 1032): SAVE_CONFIG: returned true
D/CommandListener(  313): Setting iface cfg
,D/DhcpStateMachine( 1032): StoppedState
E/WifiStateMachine( 1032): Start Dhcp Watchdog 1
D/DhcpStateMachine( 1032): StoppedState{ when=0 what=196609 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine( 1032): WaitBeforeStartState
E/WifiStateMachine( 1032):  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 30 0 rt=126823  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine( 1032):  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 30 0 rt=126823  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine( 1032):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 30 0 rt=126824  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
D/WifiServerServiceExt( 1032): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1032): setSupplicantStateASSOCIATED
E/WifiStateMachine( 1032):  ObtainingIpState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1032):  L2ConnectedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1032):  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1032):  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1032):  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1032):  DefaultState CMD_TETHER_STATE_CHANGE 0 0
D/WifiServerServiceExt( 1032): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1032): setSupplicantStateFOUR_WAY_HANDSHAKE
,D/WifiServerServiceExt( 1032): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1032): setSupplicantStateGROUP_HANDSHAKE
D/QRemote ( 6325): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
E/WifiStateMachine( 1032):  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 31 0 rt=126830  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
D/QRemote ( 6325): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 6325): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
E/WifiStateMachine( 1032):  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 31 0 rt=126831  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
D/PostponalbeReceiver( 5168): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
E/WifiStateMachine( 1032):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 31 0 rt=126833  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine( 1032):  ObtainingIpState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:-1470709036] from screen [on:0 period:-1470709036]
V/WiFiOffLoadBroadcast( 6167): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
E/WifiStateMachine( 1032):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-1470709035]
,D/WifiNative-wlan0( 1032): doString: [SIGNAL_POLL]
D/StatusBar.NetworkController( 1447): refreshViews: Data not connected!! Set no data type icon / Roaming
D/WiFiOffLoadBroadcast( 6167): MCCMNC not supported: null
D/ConnectivityService( 1032): updateNetworkScore for NetworkAgentInfo [WIFI () - 100] to 60
E/WifiStateMachine( 1032):  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1032):  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1032):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
D/QRemote ( 6325): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6325): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 6325): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,E/WifiStateMachine( 1032):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
D/PostponalbeReceiver( 5168): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
E/WifiStateMachine( 1032):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1032):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
D/ConnectivityService( 1032): Update of LinkProperties for NetworkAgentInfo [WIFI () - 100]; created=false
E/WifiStateMachine( 1032):  ObtainingIpState CMD_PRE_DHCP_ACTION 0 0 txpkts=1,0,0
E/WifiStateMachine( 1032):  L2ConnectedState CMD_PRE_DHCP_ACTION 0 0 txpkts=1,0,0
D/WifiNative-wlan0( 1032): doBoolean: DRIVER SETSUSPENDMODE 0
V/WiFiOffLoadBroadcast( 6167): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 6167): MCCMNC not supported: null
D/QRemote ( 6325): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,D/QRemote ( 6325): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 6325): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
D/PostponalbeReceiver( 5168): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
V/WiFiOffLoadBroadcast( 6167): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
I/wpa_supplicant( 6166): wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 0
D/WifiNative-wlan0( 1032): DRIVER SETSUSPENDMODE 0: returned true
D/WifiNative-wlan0( 1032): doBoolean: SET ps 0
D/WifiNative-wlan0( 1032): SET ps 0: returned true
D/WifiNative-wlan0( 1032): doBoolean: DRIVER BTCOEXMODE 1
,D/WiFiOffLoadBroadcast( 6167): MCCMNC not supported: null
I/wpa_supplicant( 6166): wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 1
D/WifiNative-wlan0( 1032): DRIVER BTCOEXMODE 1: returned true
E/WifiStateMachine( 1032): CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
D/LGWifiP2pService( 1032): InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@3c00a02c target=com.android.internal.util.StateMachine$SmHandler }
V/DhcpStateMachine( 1032): Current State is mWaitBeforeStartState.
D/LGWifiP2pService( 1032): P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@3c00a02c target=com.android.internal.util.StateMachine$SmHandler }
V/LgDhcpStateMachineHelper( 1032): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
V/LgDhcpStateMachineHelper( 1032): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700" is not exist.
D/DhcpStateMachine( 1032): WaitBeforeStartState{ when=-1ms what=196615 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine( 1032): DHCP Start wake lock is acquired.
D/WifiServerServiceExt( 1032): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1032): setSupplicantStateCOMPLETED
D/WifiServerServiceExt( 1032): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1032): setSupplicantStateCOMPLETED
D/QRemote ( 6325): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6325): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 6325): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
V/QRemote ( 6325): [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.wait_loading
D/QRemote ( 6325): [RemoteAppWidgetProvider.java:211:onReceive()] oooooo 140514:alarm msg received!:4084
D/libc-netbsd(  313): default dns: query_ipv6=0, query_ipv4=0
,D/DSQN    ( 1032): DNSproblemNotiEnabled is disabled ignore DNS fail CB
I/ActivityManager( 1032): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.realtimechat.RequestWriter$NetworkStateReceiver: pid=6487 uid=10072 gids={50072, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,W/ResourcesManager( 6487): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,D/DhcpStateMachine( 1032): DHCPV4 request on wlan0
V/LgDhcpStateMachineHelper( 1032): [bssid] hash key :c0:ff:d4:d3:aa:48
D/LgDhcpStateMachineHelper( 1032): dhcp.ap.macaddress = c0:ff:d4:d3:aa:48
,W/dhcpcd  ( 6506): type=1400 audit(0.0:161): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6843 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
W/dhcpcd  ( 6506): type=1400 audit(0.0:162): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6843 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,I/dhcpcd  ( 6506): version 5.5.6 starting
,E/dhcpcd  ( 6506): get_duid: m
D/dhcpcd  ( 6506): wlan0: using ClientID 01:c4:9a:02:7b:60:ac
D/dhcpcd  ( 6506): wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason PREINIT
D/LgDataFeature( 6487): LgDataFeature() Constructor: none
D/LgDataFeature( 6487): LgDataFeature() Constructor Done, null
,D/dhcpcd  ( 6506): getUsingAPMacAddress: c0:ff:d4:d3:aa:48 , return 1
D/dhcpcd  ( 6506): [read_lease] unlink /data/misc/dhcp/dhcpcd-wlan0.lease, link /data/misc/dhcp/dhcpcd-wlan0-c0:ff:d4:d3:aa:48.lease2
,D/dhcpcd  ( 6506): wlan0: reading lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
I/dhcpcd  ( 6506): wlan0: rebinding lease of 192.168.1.141
D/dhcpcd  ( 6506): wlan0: sending REQUEST (xid 0x8f359854), next in 4.88 seconds
,I/Babel   ( 6487): MmsConfig: mnc/mcc: 0/0
I/Babel   ( 6487): MmsConfig.loadMmsSettings
,I/Babel   ( 6487): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D855 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D855-M3-D1.xml
I/Babel   ( 6487): MmsConfig.loadFromDatabase
,E/Babel   ( 6487): canonicalizeMccMnc: invalid mccmnc 
I/Babel   ( 6487): MmsConfig.loadFromResources
E/Babel   ( 6487): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel   ( 6487): MmsConfig.loadMmsSettings: mUserAgent=LG-D855 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D855-M3-D1.xml
,W/Settings( 6487): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/AudioCapabilities( 6487): Unsupported mime audio/evrc
W/AudioCapabilities( 6487): Unsupported mime audio/qcelp
,W/VideoCapabilities( 6487): Unrecognized profile 2130706433 for video/avc
W/AudioCapabilities( 6487): Unsupported mime audio/amr-wb-plus
,W/AudioCapabilities( 6487): Unsupported mime audio/qcelp
W/AudioCapabilities( 6487): Unsupported mime audio/evrc
W/VideoCapabilities( 6487): Unsupported mime video/x-ms-wmv
,W/VideoCapabilities( 6487): Unsupported mime video/divx
W/VideoCapabilities( 6487): Unsupported mime video/divx311
W/VideoCapabilities( 6487): Unsupported mime video/divx4
W/VideoCapabilities( 6487): Unsupported mime video/mp4v-esdp
,I/ActivityManager( 1032): Killing 5577:com.lge.lockscreensettings/u0a80 (adj 15): empty #17
I/VideoCapabilities( 6487): Unsupported profile 4 for video/mp4v-es
,W/AudioCapabilities( 6487): Unsupported mime audio/eac3
W/AudioCapabilities( 6487): Unsupported mime audio/ac3
W/AudioCapabilities( 6487): Unsupported mime audio/g726
W/AudioCapabilities( 6487): Unsupported mime audio/wma-voice
W/AudioCapabilities( 6487): Unsupported mime audio/x-ms-wma
W/AudioCapabilities( 6487): Unsupported mime audio/adpcm
W/VideoCapabilities( 6487): Unsupported mime video/theora
W/VideoCapabilities( 6487): Unsupported mime video/mjpg
,W/libprocessgroup( 1032): failed to open /acct/uid_10080/pid_5577/cgroup.procs: No such file or directory
,E/WifiStateMachine( 1032):  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1032):  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1032):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1032):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
,E/WifiStateMachine( 1032):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1032):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
D/ConnectivityService( 1032): Update of LinkProperties for NetworkAgentInfo [WIFI () - 100]; created=false
I/dhcpcd  ( 6506): wlan0: acknowledged 192.168.1.141 from 192.168.1.1
,I/dhcpcd  ( 6506): wlan0: leased 192.168.1.141 for 86400 seconds
D/dhcpcd  ( 6506): wlan0: adding IP address 192.168.1.141/24
D/dhcpcd  ( 6506): wlan0: adding route to 192.168.1.0/24
D/dhcpcd  ( 6506): wlan0: adding default route via 192.168.1.1
D/dhcpcd  ( 6506): wlan0: writing lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
D/dhcpcd  ( 6506): getUsingAPMacAddress: c0:ff:d4:d3:aa:48 , return 1
D/dhcpcd  ( 6506): write_lease_ext: /data/misc/dhcp/dhcpcd-wlan0-c0:ff:d4:d3:aa:48.lease2
D/dhcpcd  ( 6506): wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason REBOOT
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
D/LGWifiP2pService( 1032): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0( 1032): doBoolean: DRIVER BTCOEXMODE 2
D/LGWifiP2pService( 1032): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 6166): wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
,D/DhcpStateMachine( 1032): DHCP Start/Renew wake lock is released.
,D/DhcpStateMachine( 1032): RunningState
D/WifiNative-wlan0( 1032): DRIVER BTCOEXMODE 2: returned true
D/WifiNative-wlan0( 1032): doBoolean: DRIVER SETSUSPENDMODE 1
I/jxcore-log( 6067): Test app app.js loaded
I/jxcore-log( 6067): 
I/wpa_supplicant( 6166): wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 1
D/WifiNative-wlan0( 1032): DRIVER SETSUSPENDMODE 1: returned true
D/WifiNative-wlan0( 1032): doBoolean: SET ps 1
I/chromium( 6067): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,D/WifiNative-wlan0( 1032): SET ps 1: returned true
D/ConnectivityService( 1032): Update of LinkProperties for NetworkAgentInfo [WIFI () - 100]; created=false
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6067): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6067): 	Automate Bluetooth MAC address resolution: true, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6067): 	Provide Bluetooth MAC address timeout in milliseconds: 40000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6067): 	Bluetooth MAC address: 58:3F:54:73:64:C0, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6067): 	Discovery mode: WIFI, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6067): 	Peer expiration time in milliseconds: 60000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6067): 	Advertise mode: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6067): 	Advertise TX power level: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6067): 	Scan mode: 1
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6067): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@36798da9 added. We now have 1 listener(s)
E/WifiStateMachine( 1032):  ObtainingIpState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
E/WifiStateMachine( 1032):  L2ConnectedState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
E/WifiStateMachine( 1032): WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
I/jxcore-log( 6067): BLE advertisement is not supported: Bluetooth LE advertising is not supported
I/jxcore-log( 6067): 
D/ConnectivityService( 1032): ignoring duplicate network state non-change
W/Settings( 1032): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1032): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1032): NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
,D/PostponalbeReceiver( 5168): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
I/StatusBar.NetworkController( 1447): networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1447): mWifiConnected = false, mWifiLevel = 0
D/ConnectivityService( 1032): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
D/ConnectivityService( 1032): Adding iface wlan0 to network 100
W/Settings( 1032): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1032): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1032): NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
,E/WifiStateMachine( 1032): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
E/ConnectivityService( 1032): Unexpected mtu value: 0, wlan0
D/ConnectivityService( 1032): Adding Route [fe80::/64 -> :: wlan0] to network 100
D/ConnectivityService( 1032): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 100
D/ConnectivityService( 1032): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 100
D/ConnectivityService( 1032): addLocalRoutetoDefaultNetwork
D/ConnectivityService( 1032): defaultNAI is null or Wi-Fi no need to add Loacal route to default network. WiFi netid = 100
D/ConnectivityService( 1032): Setting Dns servers for network 100 to [/192.168.1.1]
D/WifiHS20( 1032): [PASSPOINT] passpointNotification: hs20AP list is checked
,V/WfdStateTracker( 1915): handleWifiStateChangedEvent: 1
W/Settings( 1032): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1032): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1032): NETWORK_STATE_CHANGED_ACTION [CONNECTED]
D/StatusBar.NetworkController( 1447): refreshViews: Data not connected!! Set no data type icon / Roaming
D/WifiHS20( 1032): [PASSPOINT] passpointNotification: hs20AP list is checked
I/StatusBar.NetworkController( 1447): networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,W/Settings( 1032): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1032): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1032): NETWORK_STATE_CHANGED_ACTION [CONNECTED]
D/Nat464Xlat( 1032): requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
D/ConnectivityService( 1032): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService( 1032): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 100]
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1032): DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService( 1032): rematching NetworkAgentInfo [WIFI () - 100]
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1032): Connected
D/ConnectivityService( 1032):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1032): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService( 1032):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
I/StatusBar.NetworkController( 1447): mWifiConnected = false, mWifiLevel = 0
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1032): Checking http://clients3.google.com/generate_204 on "NG700"
D/ConnectivityService( 1032):     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
D/ConnectivityService( 1032):   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1032):     satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:true
D/ConnectivityService( 1032): currentScore = 0, newScore = 20
D/ConnectivityService( 1032):    accepting network in place of null
D/ConnectivityService( 1032): sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1032): Setting tx/rx TCP buffers to 524288,1048576,2097152,262144,524288,1048576
D/TelephonyNetworkFactory-1( 1825): new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/TelephonyNetworkFactory-1( 1825):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
D/WIFI    ( 1032): new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    ( 1032):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/StatusBar.NetworkController( 1447): refreshViews: Data not connected!! Set no data type icon / Roaming
D/libc-netbsd(  313): res_queryN name = clients3.google.com, class = 1, type = 28
E/ConnectivityService( 1032): [lg_data] Adding agent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::c69a:2ff:fe7b:60ac/64,192.168.1.141/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} ,created{true} explicitlySelected{false} } for legacy network type 1
D/CSLegacyTypeTracker( 1032): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
D/ConnectivityService( 1032): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService( 1032): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
,D/LocSvc_java( 1032): Sending msg: 4 arg1:1 arg2:1
D/LocSvc_java( 1032): getAGpsConnectionInfo connType - 4
D/LocSvc_java( 1032): updateNetworkState connTyp: 4 available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java( 1032): ignore wifi update if we are not in OPENING or CLOSING
D/LocSvc_java( 1032): Sending msg: 5 arg1:0 arg2:1
D/libc-netbsd(  313): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  313): res_queryN name = 2.android.pool.ntp.org, class = 1, type = 1
I/StatusBar.NetworkController( 1447): networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/libc-netbsd(  313): res_queryN name = 2.android.pool.ntp.org., class = 1, type = 1
D/DSQN    ( 1032): DNSproblemNotiEnabled is disabled ignore DNS fail CB
D/CSLegacyTypeTracker( 1032): [e] list.add(nai) empty : false size: 1
D/ConnectivityService( 1032): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::c69a:2ff:fe7b:60ac/64,192.168.1.141/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
D/ConnectivityService( 1032): validation of new default Network = false
D/ConnectivityService( 1032): Default network via Wi-Fi connected. start DSQN
D/DSQN    ( 1032): enableDataServiceNotify 
D/DSQN    ( 1032): start dsqn bin
I/StatusBar.NetworkController( 1447): mWifiConnected = true, mWifiLevel = 2
D/StatusBar.NetworkController( 1447): refreshViews: Data not connected!! Set no data type icon / Roaming
D/libc-netbsd(  313): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  313): res_queryN name = europe.pool.ntp.org, class = 1, type = 1
,V/WiFiOffLoadBroadcast( 6167): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
V/NetworkPolicy( 1032): [LG_RESTRICTED] checkMobilePolicy_type()
D/WiFiOffLoadBroadcast( 6167): MCCMNC not supported: null
,I/StatusBar.NetworkController( 1447): networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1447): mWifiConnected = true, mWifiLevel = 2
D/StatusBar.NetworkController( 1447): refreshViews: Data not connected!! Set no data type icon / Roaming
D/ConnectivityService( 1032): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService( 1032):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1032):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1032): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
W/dsqn    ( 6571): type=1400 audit(0.0:163): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6843 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
W/dsqn    ( 6571): type=1400 audit(0.0:164): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6843 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
D/ConnectivityManager.CallbackHandler( 1447): CM callback handler got msg 524290
,D/QRemote ( 6325): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6325): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 6325): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
D/libc-netbsd(  313): res_queryN name = clients3.google.com, class = 1, type = 1
D/PostponalbeReceiver( 5168): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,V/WiFiOffLoadBroadcast( 6167): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 6167): MCCMNC not supported: null
E/DSQN    ( 6571): DSQN ssw
,D/QRemote ( 6325): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6325): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 6325): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
D/TelephonyIcons( 1447): null signal icon name: drawable/stat_sys_signal_null
D/StatusBar.NetworkController( 1447): refreshViews: Data not connected!! Set no data type icon / Roaming
D/PostponalbeReceiver( 5168): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
D/StatusBar.NetworkController( 1447): refreshViews: Data not connected!! Set no data type icon / Roaming
I/PCSuite ( 6228): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
,D/PCSuite ( 6228): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 6167): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 6167): MCCMNC not supported: null
D/libc-netbsd(  313): res_queryN name = clients3.google.com succeed
D/QRemote ( 6325): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,D/QRemote ( 6325): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
D/QRemote ( 6325): [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
I/QRemote ( 6325): [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
I/QRemote ( 6325): [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
D/PostponalbeReceiver( 5168): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
I/PCSuite ( 6228): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
D/PCSuite ( 6228): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
,V/WiFiOffLoadBroadcast( 6167): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/LGDataListener(  313): argv[0]=dsqncommand
D/LGDataListener(  313): argv[1]=wlan0
D/LGDataListener(  313): argv[2]=1
D/LGDataListener(  313): notifyDSQN DSQN STARTMONITOR wlan0 1
D/DSQN    ( 1032): DSQM DsqnNotification wlan0  1
D/DSQN    ( 1032): start to monitor internet connection
,D/WiFiOffLoadBroadcast( 6167): MCCMNC not supported: null
D/QRemote ( 6325): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6325): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
D/QRemote ( 6325): [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
,I/QRemote ( 6325): [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
,I/QRemote ( 6325): [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
D/libc-netbsd(  313): res_queryN name = europe.pool.ntp.org succeed
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1032): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Wed, 03 Feb 2016 18:13:27 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1454523206593], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1454523206566]}
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1032): Don't send network conditions - lacking user consent.
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1032): Validated
D/ConnectivityService( 1032): Validated NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService( 1032): rematching NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService( 1032):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService( 1032):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1032):     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
,D/ConnectivityService( 1032): Network NetworkAgentInfo [WIFI () - 100] was already satisfying request 1. No change.
D/ConnectivityService( 1032): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService( 1032):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1032):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1032): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1032): sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityManager.CallbackHandler( 1447): CM callback handler got msg 524290
D/ConnectivityService( 1032): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
D/WIFI    ( 1032): new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/TelephonyNetworkFactory-1( 1825): new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    ( 1032):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/TelephonyNetworkFactory-1( 1825):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
,D/TelephonyIcons( 1447): null signal icon name: drawable/stat_sys_signal_null
D/StatusBar.NetworkController( 1447): refreshViews: Data not connected!! Set no data type icon / Roaming
D/StatusBar.NetworkController( 1447): refreshViews: Data not connected!! Set no data type icon / Roaming
E/WifiStateMachine( 1032):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1470706029] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1032):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-1470706028] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1032): doString: [SIGNAL_POLL]
,D/StatusBar.NetworkController( 1447): refreshViews: Data not connected!! Set no data type icon / Roaming
,V/WifiInternetCheck( 1032): Single check msg out of sync, ignoring.
,D/ConnectivityService( 1032): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering( 1032): MasterInitialState.processMessage what=3
,D/libc-netbsd(  313): default dns: query_ipv6=0, query_ipv4=1
,D/libc-netbsd(  313): res_queryN name = 2.android.pool.ntp.org, class = 1, type = 1
D/PostponalbeReceiver( 5168): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
,D/GpsLocationProvider( 1032): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
D/libc-netbsd(  313): res_queryN name = 2.android.pool.ntp.org succeed
W/ContextImpl( 5168): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
,D/AlarmManagerService( 1032): Setting time of day to sec=1454523210
W/AlarmManagerService( 1032): Unable to set rtc to 1454523210: Invalid argument
D/KeyguardUpdateMonitor( 1447): handleTimeUpdate
,I/SecureClockService( 1915): Intent.ACTION_TIME_CHANGED 
I/[SystemUI]Clock( 1447): onReceive = android.intent.action.TIME_SET
D/LIA_Informant_Tips_DateChangeManager( 2703): onReceive() : ACTION_TIME_CHANGED
I/LIA_Informant_Tips_LogTracer( 2703): [Log Tracer - Schedule Transition] Time Change Event Received : 2016-02-03 19:13:30...... Request
I/LIA_Informant_Tips_LogTracer( 2703): [Log Tracer - Schedule Transition] UserGuide, DATE_UPDATE : working count : 7, total count : 164, new day : false...... Request
D/LIA_Informant_Tips_DateChangeManager( 2703): DateInfo : SmartTips Total Working Day Count = 164
D/LIA_Informant_Tips_DateChangeManager( 2703): DateInfo : UserGuide Working Duration Count = 7
D/LIA_Informant_Tips_DateChangeManager( 2703): DateInfo : Last Date Check Time = 2016-02-03 19:13:30
W/ActivityManager( 1032): getTasks: caller 10029 is using old GET_TASKS but privileged; allowing
,I/LgeClockWidgetControlView( 1447): time changed, timezoneChanged : false
I/[LGHome]LGDateChangeReceiver( 2005): [LGDateChangeReceiver.java:78:updateCalendarShortcut()]date=3 currentDate=-1 dayofweek=4 currentDayOfWeek=-1
,I/[LGHome]LGCalendarIcon( 2005): [LGCalendarIcon.java:214:makeCalendarBitmap()]Locale = en_US dayofweek= Wed date= 3
I/NetworkMonitor( 5218): type=WIFI subType= reason=null isConnected=true
I/[LGHome]LGCalendarIcon( 2005): [LGCalendarIcon.java:214:makeCalendarBitmap()]Locale = en_US dayofweek= Wed date= 3
,I/[LGHome]Launcher( 2005): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
V/AlarmManager( 1032): RTC_WAKEUP set : Alarm{36798da9 type 0 when 1454523210320 com.android.vending} when 1454523210320
,I/ActivityManager( 1032): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=6608 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,D/[Concierge]Service( 2591): onStartCommand(). Type : 9
I/art     (  347): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 497us total 21.550ms
,V/SIM_STK ( 1032): Menu title from STK is T-Mobile
,I/art     (  347): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 421us total 18.670ms
I/AppUp4:AppBoxCP( 6608): onCreate
I/art     (  347): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 406us total 18.354ms
W/AppUp4:DB( 6608):  [AppBoxDatabaseHelper] construct
,I/AppUp4:DB( 6608):  setFingerPrint start
I/AppUp4:DB( 6608):  newfinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys SDK version = 21
I/AppUp4:DB( 6608):  beforefinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys
I/AppUp4:DB( 6608):  SDK version = 21
I/AppUp4:DB( 6608):  beforefinger == newfinger no write in DB
,I/ActivityManager( 1032): Start proc com.google.android.apps.books for service com.google.android.apps.books/.service.SyncService: pid=6629 uid=10054 gids={50054, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/AppUp4:AppBoxApplication( 6608): AppBoxApplication onCreate()
I/NetworkStateForAutoUpdateMonitor( 6608): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 6608): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 6608): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 6608): [onReceive] request level :IDLE....
I/GoogleURLConnFactory( 2063): Using platform SSLCertificateSocketFactory
I/AppUp4:CustModeStarterReceiver( 6608): onReceive
,I/ActivityManager( 1032): Start proc com.android.gallery3d for service com.android.gallery3d/com.lge.gallery.picasa.PicasaService: pid=6650 uid=10027 gids={50027, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
,D/LgDataFeature( 6608): LgDataFeature() Constructor: none
D/LgDataFeature( 6608): LgDataFeature() Constructor Done, null
,D/AppUp4:CustFacade( 6608): Context : android.app.ReceiverRestrictedContext@2dc9cf30
,D/AppUp4:CustFacade( 6608): isCustomizationCompleted : false
D/AppUp4:CustFacade( 6608): isPhone : true
D/AppUp4:CustModeStarterReceiver( 6608): begin check event
I/AppUp4:CustModeStarterReceiver( 6608): Event For GoodConnectivity
D/AppUp4:CustModeStarterReceiver( 6608): runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
W/ResourcesManager( 6650): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6650): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 6650): Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
D/AppUp4:CustModeStarterReceiver( 6608): call method handleAsyncCustNotification.
D/AppUp4:CustModeStarterReceiver( 6608): handleAsync isTriedOnce : false
W/ResourcesManager( 6650): Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
,E/AppUp4:CustModeStarterReceiver( 6608): handleAsyncCustNotification do not startCustService
D/LGDMClient( 3937): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 3937): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
W/ContextImpl( 3937): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
W/ContextImpl( 3937): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
V/DownloadManager( 3320): Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
,V/DownloadManager( 3320): DownloadService onCreate
D/LGDMClient( 3937): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 3937): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
I/DownloadManager( 3320): in removeSpuriousFiles
V/DownloadManager( 3320): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
D/LGDMClient( 3937): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=3, isUserType=1
V/DownloadManager( 3320): created cursor android.database.sqlite.SQLiteCursor@22548e89 on behalf of 3320
I/DownloadManager( 3320): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGMyGuide_4.40.09_COM_COM_20150430011620058_RELG-D855.apk
I/DownloadManager( 3320): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGBackup_4.50.37_COM_COM_20150608234245157.apk
I/DownloadManager( 3320): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/CalendarProvider_4.2.8_COM_COM_20150304234552863_RELG-D855.apk
I/DownloadManager( 3320): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calendar_4.40.16_COM_COM_20150304234554754_RELG-D855.apk
I/DownloadManager( 3320): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.10_COM_COM_20150521235426173_RELG-D855.apk
I/DownloadManager( 3320): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQVoiceplusN_2.3.3_COM_COM_20150604065210803.apk
I/DownloadManager( 3320): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.11_COM_COM_v2_20150911144028620_RELG-D855_21.apk
I/DownloadManager( 3320): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQMemoplus(LG-D855_user)_20150902050954661.apk
I/DownloadManager( 3320): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/RemoteCall_4.1.10_COM_COM_20150817053748728.apk
I/DownloadManager( 3320): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/rspermlge(6713)_20150901080430397.apk
I/DownloadManager( 3320): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGBackup_4.51.57_COM_COM_8275_2_20151201044833536_RELG-D855_21.apk
I/LGDMClient( 3937): [DmServiceProcessor.java] [processNetworkChanged()] : [91] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
I/DownloadManager( 3320): in trimDatabase
V/DownloadManager( 3320): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
V/DownloadManager( 3320): created cursor android.database.sqlite.SQLiteCursor@28649e8e on behalf of 3320
I/ActivityManager( 1032): Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=6674 uid=10023 gids={50023, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,V/DownloadManager( 3320): DownloadService onStartCommand
V/DownloadManager( 3320): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
W/ContextImpl( 3937): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:141 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:180 android.app.IntentService$ServiceHandler.handleMessage:65 
E/LGDMClient( 3937): [DmNotiService.java] [onCreate()] : [148] : DmNotiService.onCreate()
D/LGDMClient( 3937): [DmNotiService.java] [onStartCommand()] : [182] : in the new onStartCommand()
D/LGDMClient( 3937): [DmNotiService.java] [handleStart()] : [203] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
V/DownloadManager( 3320): created cursor android.database.sqlite.SQLiteCursor@5ee8a45 on behalf of 3320
V/DownloadManager( 3320): processing inserted download 1
V/DownloadManager( 3320): processing inserted download 4
V/DownloadManager( 3320): processing inserted download 7
,V/DownloadManager( 3320): processing inserted download 8
V/DownloadManager( 3320): processing inserted download 9
V/DownloadManager( 3320): processing inserted download 10
V/DownloadManager( 3320): processing inserted download 16
V/DownloadManager( 3320): processing inserted download 17
V/DownloadManager( 3320): processing inserted download 18
V/DownloadManager( 3320): processing inserted download 21
V/DownloadManager( 3320): processing inserted download 22
V/DownloadManager( 3320): DownloadService onDestroy
,I/AppConfig( 6650): Total System Memory = 2995761152
D/SystemHelper( 6650): region [EU], country [EU], operator [OPEN], sub-operator []
W/ResourcesManager( 6674): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6674): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 6674): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
,W/ResourcesManager( 6674): Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
,I/art     ( 2063): Explicit concurrent mark sweep GC freed 21634(1248KB) AllocSpace objects, 2(32KB) LOS objects, 51% free, 30MB/62MB, paused 896us total 21.910ms
,I/ActivityManager( 1032): Start proc com.android.chrome for service com.android.chrome/com.google.android.apps.chrome.sync.ChromeBrowserSyncAdapterService: pid=6693 uid=10057 gids={50057, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ReaderUtils( 6629): PortraitW 1440 LandscapeW 2392 SmallestSize 1340 LargestSize 2392 textZoom 4.4999995 isTablet false Memory 256
I/art     ( 1032): Explicit concurrent mark sweep GC freed 76538(3MB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 44MB/66MB, paused 1.418ms total 79.201ms
D/GpsLocationProvider( 1032): updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/LGEmail ( 6674): [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
D/LGEmail ( 6674): user build Type == true (at Util.java isUserModeBuildType 3507)[v:6.41.18]
,E/GpsLocationProvider( 1032): No APN found to select.
,I/ActivityManager( 1032): Killing 5893:com.google.android.apps.docs/u0a61 (adj 15): empty #17
,W/ResourceType( 6674): No package identifier when getting value for resource number 0x00000000
,W/libprocessgroup( 1032): failed to open /acct/uid_10061/pid_5893/cgroup.procs: No such file or directory
,W/DriveInitializer( 2316): Background init thread started
,V/GLSActivity( 2063): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/GAV2    ( 6629): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
I/BooksApp( 6629): Created application version: 3.2.35 (30235)
,W/DriveInitializer( 2316): Awaiting to be initialized
D/LgDataFeature( 6674): LgDataFeature() Constructor: none
D/LgDataFeature( 6674): LgDataFeature() Constructor Done, null
,E/VoldCmdListener(  280): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  280): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.gms/files/
W/Vold    (  280): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 2316): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.gms/files
E/Auth.Api.Credentials( 2316): [CredentialSyncAdapter] Unknown sync event.
,I/BooksSync( 6629): Starting books sync
E/WifiStateMachine( 1032):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-58 f=2412 sc=60 link=72 tx=5.2, 0.0, 0.0  rx=3.5 bcn=0 [on:0 tx:0 rx:0 period:3647] from screen [on:0 period:-1470702372] gl rssi=-58 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
E/WifiStateMachine( 1032):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-58 f=2412 sc=60 link=72 tx=5.2, 0.0, 0.0  rx=3.5 bcn=0 [on:0 tx:0 rx:0 period:0] from screen [on:0 period:-1470702372] gl rssi=-58 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
D/WifiNative-wlan0( 1032): doString: [SIGNAL_POLL]
,W/DriveInitializer( 2316): Background init thread ended
I/VacuumService( 2063): Vacuum at: now=1454523210988 tag=VacuumService
,I/GLSUser ( 2063): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 2063): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2063): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2063): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2063): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/DelayedSyncController( 6693): Delaying sync.
I/ActivityManager( 1032): Killing 5601:com.google.android.apps.plus/u0a97 (adj 15): empty #17
,W/libprocessgroup( 1032): failed to open /acct/uid_10097/pid_5601/cgroup.procs: No such file or directory
,D/Finsky  ( 4869): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 4869): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 4869): [1] 5.onFinished: Scheduling replication attempt 2.
D/eas_req ( 6674): ---addEventToQueue() easCode=2, requestId=0 (at EasSupport.java addEventToQueue 69)
,I/ActivityManager( 1032): Killing 5962:com.lge.eula/1000 (adj 15): empty #17
D/BooksSync( 6629): started syncMyEbooks
,W/libprocessgroup( 1032): failed to open /acct/uid_1000/pid_5962/cgroup.procs: No such file or directory
,I/LgeMiscReceiver( 3268): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 3268): action = android.net.conn.CONNECTIVITY_CHANGE
I/HubEmail( 6674): JNI_OnLoad()
I/HubEmail( 6674): -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 6674): registerNatives()
I/HubEmail( 6674): -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
,I/HubEmail( 6674): registerNativeMethods()
I/HubEmail( 6674): -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
W/art     ( 6674): JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
I/LgeMiscReceiver( 3268): networkInfo.isConnected() = true
D/PhoneState( 3268): setPdpRejectCasuse : false
W/Settings( 6674): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/libc-netbsd(  313): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  313): res_queryN name = static-avc.lglime.com, class = 1, type = 1
,I/ActivityManager( 1032): Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=6758 uid=10062 gids={50062, 9997, 4002, 3003, 1028} abi=armeabi-v7a
,V/GLSActivity( 2063): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/Settings( 6674): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/GLSUser ( 2063): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/ads_measurement
I/GLSUser ( 2063): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/ads_measurement without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2063): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2063): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2063): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/Ads     ( 2316): [JAMS] Failed to get OAuth token: com.google.android.gms.auth.ad: BadAuthentication
,I/GLSUser ( 2063): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2063): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2063): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2063): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2063): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/libc-netbsd(  313): res_queryN name = static-avc.lglime.com succeed
,D/DrmBroadcastReceiver( 6758): Receive CONNECTIVITY_ACTION
D/DrmBroadcastReceiver( 6758): 1  network is available. Sync DRM Time with NTP
V/DrmService( 6758): Service onCreate
D/DrmService( 6758): Received new request = 2
,V/NotificationService( 1032): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
V/NotificationService( 1032): pkg=com.google.android.gms canInterrupt=false intercept=true
D/libc-netbsd(  313): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  313): res_queryN name = www.google.com, class = 1, type = 1
W/GLSActivity( 2063): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2063): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2063): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2063): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2063): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2063): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2063): 	at android.os.Binder.execTransact(Binder.java:446)
I/DrmSntpClient( 6758): Start Sync process
D/DrmSntpClient( 6758): Server : 0
V/FormManager( 6198): There are no updated forms. The schedule will be deleted.
V/FormManager( 6198): Alarm would be updated, because LastCheckTime has been updated.
D/libc-netbsd(  313): default dns: query_ipv6=0, query_ipv4=1
,D/libc-netbsd(  313): res_queryN name = pool.ntp.org, class = 1, type = 1
D/libc-netbsd(  313): res_queryN name = www.google.com succeed
,D/libc-netbsd(  313): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  313): res_queryN name = clients3.google.com, class = 1, type = 1
D/libc-netbsd(  313): res_queryN name = clients3.google.com succeed
D/libc-netbsd(  313): res_queryN name = pool.ntp.org succeed
I/ActivityManager( 1032): Start proc com.lge.sizechangable.weather for broadcast com.lge.sizechangable.weather/.layout.WeatherWidget: pid=6779 uid=10085 gids={50085, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/NotificationServiceEx( 1032): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1032): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1032): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
E/BooksAccountManager( 6629): Authentication error
E/BooksAccountManager( 6629): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6629): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6629): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6629): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6629): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6629): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6629): null auth token
D/LgeQuickCoverNLService( 1398): onNotificationPosted
,D/SmartCoverUpdateMonitor( 1398): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1398): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1398): handleNotificationPosted(true)
D/QuickCircle( 1398): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1398): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1398): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1398): post do just update job
D/LgeQuickCoverNotificationData( 1398): showAll3
D/LgeQuickCoverNotificationData( 1398): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1398): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1398): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1398): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1398): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1398): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1398): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1398): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1398): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1398): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1398): updateNotificationData: count=3
,D/DelayedSyncController( 6693): Delaying sync.
,V/WifiInternetCheck( 1032): isHttpConnectionAvailable - We got a valid response : 204
,D/QuickStatusbarLayout( 1398): Notification difference=198
D/QuickStatusbarLayout( 1398): child = android.widget.LinearLayout{1f81f9d8 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
D/libc-netbsd(  313): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  313): res_queryN name = www.googleapis.com, class = 1, type = 1
I/LGDrmClient( 6758): _DRM_ServiceGet() : Bind lgdrm service
,I/ActivityManager( 1032): Killing 5381:com.google.android.gms.wearable/u0a5 (adj 15): empty #17
V/ILGDrmService(  323): eDRM_SetDRMTime +++
I/LGDRM   (  323): [DRM] SET TIME : YR=2016, MON=2, DAY=3
I/LGDRM   (  323): [DRM] SET TIME : HR=18, MIN=13, SEC=31
V/ILGDrmService(  323): eDRM_SetDRMTime ---
I/DrmSntpClient( 6758): Synched
D/DrmService( 6758): Completed !! request = 2
D/DrmService( 6758): Request count = 0
,D/libc-netbsd(  313): res_queryN name = www.googleapis.com succeed
W/libprocessgroup( 1032): failed to open /acct/uid_10005/pid_5381/cgroup.procs: No such file or directory
V/DrmService( 6758): Service onDestroy
I/ActivityManager( 1032): Killing 2112:com.lge.music/u0a34 (adj 15): empty #17
I/art     ( 6779): Almond Protected OAT
,V/AudioFlinger(  317): 2112 died, releasing its sessions
V/AudioFlinger(  317):  pid 1825 @ 0
,V/AudioFlinger(  317):  pid 3268 @ 1
V/AudioFlinger(  317):  pid 3268 @ 2
W/libprocessgroup( 1032): failed to open /acct/uid_10034/pid_2112/cgroup.procs: No such file or directory
,D/WeatherApplication( 6779): removeAccount
D/WeatherApplication( 6779): Account.length = 0
E/WeatherApplication( 6779): OPERATOR:OPEN
D/WeatherAncestor( 6779): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 19:13:31
I/GoogleURLConnFactory( 2063): Using platform SSLCertificateSocketFactory
,D/Weather.Utils( 6779): 2 : the weather widgets(using time tick) are gone.
D/Weather.Utils( 6779): 2 : All the weather widget is gone.
D/UpdateThreadPoolManager( 6779): 2 : This is isUpdating : false
D/WeatherAncestor( 6779): connectivity changed - connection : true
D/WeatherService( 6779): 2 : isServiceAlived():false forecastCache:null
,D/ForecastDataCache( 6779): 2 : lastUpdatedTime: 1430558561343
D/ForecastDataCache( 6779): 2 : currentPackageVersion: 4.40.4
D/ForecastDataCache( 6779): 2 : Cache is not up-to-date, count: 0
W/Uploader( 2063): No account for auth token provided
D/libc-netbsd(  313): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  313): res_queryN name = play.googleapis.com, class = 1, type = 1
,D/Weather_cast( 6779): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherAncestor( 6779): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 19:13:31
,D/libc-netbsd(  313): res_queryN name = play.googleapis.com succeed
I/ActivityManager( 1032): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=6806 uid=10093 gids={50093, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager( 1032): Killing 5987:com.lge.bnr/1000 (adj 15): empty #17
,W/libprocessgroup( 1032): failed to open /acct/uid_1000/pid_5987/cgroup.procs: No such file or directory
,W/ApiaryClient( 6629): Error response from books API: {
W/ApiaryClient( 6629):  "error": {
W/ApiaryClient( 6629):   "errors": [
W/ApiaryClient( 6629):    {
W/ApiaryClient( 6629):     "domain": "global",
W/ApiaryClient( 6629):     "reason": "required",
W/ApiaryClient( 6629):     "message": "Login Required",
W/ApiaryClient( 6629):     "locationType": "header",
W/ApiaryClient( 6629):     "location": "Authorization"
W/ApiaryClient( 6629):    }
W/ApiaryClient( 6629):   ],
W/ApiaryClient( 6629):   "code": 401,
W/ApiaryClient( 6629):   "message": "Login Required"
W/ApiaryClient( 6629):  }
W/ApiaryClient( 6629): }
,W/ApiaryClient( 6629): errCount = 1: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6629): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-2683712148980154641&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6629): Headers:
W/ApiaryClient( 6629): accept-encoding: [gzip]
W/ApiaryClient( 6629): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6629): gdata-version: 2
I/art     ( 1032): Explicit concurrent mark sweep GC freed 32874(1438KB) AllocSpace objects, 5(208KB) LOS objects, 33% free, 44MB/66MB, paused 2.589ms total 119.694ms
,V/GLSActivity( 2063): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/VoldCmdListener(  280): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  280): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  280): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6806): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
E/VoldCmdListener(  280): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  280): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  280): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6806): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
E/VoldCmdListener(  280): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  280): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  280): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6806): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
E/VoldCmdListener(  280): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  280): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  280): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6806): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
I/GLSUser ( 2063): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.syncadapters.contacts, service: cp
I/GLSUser ( 2063): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> cp without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2063): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2063): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2063): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1032): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1032): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1032): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1032): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1032): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
W/Uploader( 2063): No account for auth token provided
W/GLSActivity( 2063): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2063): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2063): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2063): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2063): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2063): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2063): 	at android.os.Binder.execTransact(Binder.java:446)
D/LgeQuickCoverNLService( 1398): onNotificationPosted
D/ContactsSyncAdapter( 2063): innerSync failed
D/ContactsSyncAdapter( 2063): com.google.wireless.gdata2.client.AuthenticationException: unable to get auth token android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
D/ContactsSyncAdapter( 2063): 	at com.google.android.syncadapters.contacts.AuthInfo.getAuthToken(AuthInfo.java:45)
D/ContactsSyncAdapter( 2063): 	at com.google.android.syncadapters.contacts.ContactsSyncAdapter.innerPerformSync(ContactsSyncAdapter.java:263)
D/ContactsSyncAdapter( 2063): 	at com.google.android.syncadapters.contacts.ContactsSyncAdapter.onPerformLoggedSync(ContactsSyncAdapter.java:168)
D/ContactsSyncAdapter( 2063): 	at com.google.android.common.LoggingThreadedSyncAdapter.onPerformSync(LoggingThreadedSyncAdapter.java:33)
D/ContactsSyncAdapter( 2063): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
D/ContactsSyncAdapter( 2063): Caused by: android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
D/ContactsSyncAdapter( 2063): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
D/ContactsSyncAdapter( 2063): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
D/ContactsSyncAdapter( 2063): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
D/ContactsSyncAdapter( 2063): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
D/ContactsSyncAdapter( 2063): 	at android.os.Binder.execTransact(Binder.java:446)
D/SmartCoverUpdateMonitor( 1398): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1398): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1398): handleNotificationPosted(true)
D/QuickCircle( 1398): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1398): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1398): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
,D/LgeQuickCoverNotificationData( 1398): post do just update job
D/LgeQuickCoverNotificationData( 1398): showAll3
D/LgeQuickCoverNotificationData( 1398): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1398): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1398): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1398): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1398): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1398): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1398): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1398): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1398): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1398): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1398): updateNotificationData: count=3
D/SyncManager( 1032): failed sync operation thalitester@gmail.com u0 (com.google), com.android.contacts, LOCAL, currentRunTime 26480, reason: 10019, SyncResult: stats [ numAuthExceptions: 1]
D/SyncManager( 1032): not retrying sync operation because the error is a hard error: thalitester@gmail.com u0 (com.google), com.android.contacts, LOCAL, currentRunTime 166709, reason: 10019
,D/QuickStatusbarLayout( 1398): Notification difference=198
,D/QuickStatusbarLayout( 1398): child = android.widget.LinearLayout{1f81f9d8 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
I/GoogleURLConnFactory( 2316): Using platform SSLCertificateSocketFactory
,I/art     ( 2063): Explicit concurrent mark sweep GC freed 28024(1554KB) AllocSpace objects, 8(919KB) LOS objects, 51% free, 30MB/62MB, paused 983us total 57.016ms
,W/Uploader( 2063):  no longer exists, so no auth token.
,I/art     ( 2316): Explicit concurrent mark sweep GC freed 17872(1300KB) AllocSpace objects, 20(320KB) LOS objects, 49% free, 32MB/64MB, paused 1.418ms total 64.484ms
,V/GLSActivity( 2063): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2063): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: mail
,I/GLSUser ( 2063): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> mail without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2063): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2063): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2063): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/WebViewFactory( 6806): Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,V/NotificationService( 1032): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
V/NotificationService( 1032): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1032): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1032): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1032): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
W/GLSActivity( 2063): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2063): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2063): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2063): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2063): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2063): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2063): 	at android.os.Binder.execTransact(Binder.java:446)
W/SubscribedFeeds( 2316): Hard error
D/LgeQuickCoverNLService( 1398): onNotificationPosted
D/SmartCoverUpdateMonitor( 1398): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1398): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1398): handleNotificationPosted(true)
D/QuickCircle( 1398): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1398): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1398): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1398): post do just update job
D/LgeQuickCoverNotificationData( 1398): showAll3
D/LgeQuickCoverNotificationData( 1398): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1398): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1398): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1398): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1398): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1398): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1398): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1398): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1398): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1398): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1398): updateNotificationData: count=3
I/LibraryLoader( 6806): Loading: webviewchromium
,I/LibraryLoader( 6806): Time to load native libraries: 9 ms (timestamps 4034-4043)
I/LibraryLoader( 6806): Expected native library version number "",actual native library version number ""
W/Uploader( 2063): No account for auth token provided
V/WebViewChromiumFactoryProvider( 6806): Binding Chromium to main looper Looper (main, tid 1) {77d78db}
I/LibraryLoader( 6806): Expected native library version number "",actual native library version number ""
D/SyncManager( 1032): failed sync operation thalitester@gmail.com u0 (com.google), subscribedfeeds, PERIODIC, currentRunTime 40022, reason: Periodic, SyncResult: stats [ numAuthExceptions: 1]
I/chromium( 6806): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
D/SyncManager( 1032): not retrying sync operation because the error is a hard error: thalitester@gmail.com u0 (com.google), subscribedfeeds, PERIODIC, currentRunTime 165974, reason: Periodic
,D/QuickStatusbarLayout( 1398): Notification difference=198
D/QuickStatusbarLayout( 1398): child = android.widget.LinearLayout{1f81f9d8 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
I/BrowserStartupController( 6806): Initializing chromium process, renderers=0
W/art     ( 6806): Attempt to remove local handle scope entry from IRT, ignoring
,W/chromium( 6806): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
I/chromium( 6806): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=38 off=46780 len=2953
I/chromium( 6806): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:39 off:229536 len:643667
V/AudioPolicyService(  317): registerClient() client 0xb14274e0, uid 10093
W/AudioManagerAndroid( 6806): Requires BLUETOOTH permission
,I/Adreno-EGL( 6806): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 6806): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 6806): Build Date: 12/12/14 금
I/Adreno-EGL( 6806): Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
I/Adreno-EGL( 6806): Remote Branch: 
I/Adreno-EGL( 6806): Local Patches: 
I/Adreno-EGL( 6806): Reconstruct Branch: 
,I/ActivityManager( 1032): Start proc com.google.android.syncadapters.calendar for service com.google.android.syncadapters.calendar/.CalendarSyncAdapterService: pid=6860 uid=10069 gids={50069, 9997, 3003} abi=armeabi-v7a
,W/Uploader( 2063): No account for auth token provided
,I/NSApplication( 6806): Starting up...
,I/ActivityManager( 1032): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=6882 uid=10097 gids={50097, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager( 1032): Killing 6251:com.lge.lifetracker/u0a37 (adj 15): empty #17
W/libprocessgroup( 1032): failed to open /acct/uid_10037/pid_6251/cgroup.procs: No such file or directory
,W/Uploader( 2063): No account for auth token provided
,W/ResourcesManager( 6882): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/AbstractGoogleClient( 6860): Application name is not set. Call Builder#setApplicationName.
,I/ActivityManager( 1032): Start proc com.android.providers.calendar for content provider com.android.providers.calendar/.CalendarProvider2: pid=6902 uid=10014 gids={50014, 9997, 3003, 1028, 1015} abi=armeabi
,W/ResourcesManager( 6902): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,D/CalendarProvider2( 6902): [initialize] mInstance = com.android.providers.calendar.CalendarProvider2@22f98d56
,D/CalendarProvider2( 6902): [getOrCreateCalendarAlarmManager]
,I/CalendarProvider2( 6902): Created com.android.providers.calendar.CalendarAlarmManager@27f77473(com.android.providers.calendar.CalendarProvider2@22f98d56)
D/libc-netbsd(  313): default dns: query_ipv6=0, query_ipv4=1
,D/libc-netbsd(  313): res_queryN name = mtalk.google.com, class = 1, type = 1
V/GLSActivity( 2063): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSActivity( 2063): [ac] getting account id
,I/iu.SyncManager( 2316): SYNC; picasa accounts
,I/GLSUser ( 2063): [t] Fetched account id for thalitester@gmail.com : 105256135866144380227
D/NetworkLogImpl( 2316): Loaded NetworkSpeedPredictor
,D/libc-netbsd(  313): res_queryN name = mtalk.google.com succeed
I/iu.Environment( 2316): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
I/GLSUser ( 2063): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2063): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2063): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2063): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2063): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/iu.UploadsManager( 2316): num queued entries: 0
I/iu.UploadsManager( 2316): num updated entries: 0
I/iu.SyncManager( 2316): NEXT; no task
I/GLSUser ( 2063): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/gcm
,I/GLSUser ( 2063): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/gcm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2063): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2063): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2063): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/ChimeraCfgMgr( 2316): Loading module com.google.android.gms.kids from APK com.google.android.gms
D/ChimeraCfgMgr( 2316): Loading module com.google.android.gms.kids from APK com.google.android.gms
D/PostponalbeReceiver( 5168): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.intent.action.TIME_SET'.
,I/GcmGroups( 2316): Failed to subscribe to group.
I/GcmGroups( 2316): com.google.android.gms.auth.ad: BadAuthentication
I/GcmGroups( 2316): 	at com.google.android.gms.auth.p.b(SourceFile:442)
I/GcmGroups( 2316): 	at com.google.android.gms.auth.p.a(SourceFile:365)
I/GcmGroups( 2316): 	at com.google.android.gms.auth.p.a(SourceFile:318)
I/GcmGroups( 2316): 	at com.google.android.gms.gcm.gmsproc.b.a(SourceFile:443)
I/GcmGroups( 2316): 	at com.google.android.gms.gcm.gmsproc.b.a(SourceFile:333)
I/GcmGroups( 2316): 	at com.google.android.gms.gcm.gmsproc.b.a(SourceFile:240)
I/GcmGroups( 2316): 	at com.google.android.gms.gcm.gmsproc.GcmReceiverService.onHandleIntent(SourceFile:50)
I/GcmGroups( 2316): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
I/GcmGroups( 2316): 	at android.os.Handler.dispatchMessage(Handler.java:102)
I/GcmGroups( 2316): 	at android.os.Looper.loop(Looper.java:135)
I/GcmGroups( 2316): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,V/NotificationService( 1032): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
V/NotificationService( 1032): pkg=com.google.android.gms canInterrupt=false intercept=true
W/GLSActivity( 2063): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2063): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2063): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2063): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2063): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2063): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2063): 	at android.os.Binder.execTransact(Binder.java:446)
I/ActivityManager( 1032): Start proc com.lge.clock for broadcast com.lge.clock/.alarmclock.ALBootInit: pid=6933 uid=10010 gids={50010, 9997, 3003, 1028, 4002} abi=armeabi-v7a
,I/NotificationServiceEx( 1032): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1032): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1032): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
E/BooksAccountManager( 6629): Authentication error
E/BooksAccountManager( 6629): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6629): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6629): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6629): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6629): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6629): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6629): null auth token
I/GcmGroups( 2316): Groups upload failed, retrying in 24000:00:00
,D/LgeQuickCoverNLService( 1398): onNotificationPosted
D/SmartCoverUpdateMonitor( 1398): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1398): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1398): handleNotificationPosted(true)
D/QuickCircle( 1398): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1398): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1398): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1398): post do just update job
D/LgeQuickCoverNotificationData( 1398): showAll3
D/LgeQuickCoverNotificationData( 1398): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1398): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1398): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1398): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1398): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1398): isNotificationForCurrentUser : true
I/art     (  347): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 438us total 20.068ms
D/LgeQuickCoverOverlayWindow( 1398): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1398): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1398): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1398): isNotificationForCurrentUser : true
,E/LgeQuickCoverOverlayWindow( 1398): updateNotificationData: count=3
,D/QuickStatusbarLayout( 1398): Notification difference=198
D/QuickStatusbarLayout( 1398): child = android.widget.LinearLayout{1f81f9d8 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
I/art     (  347): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 412us total 19.361ms
I/GLSUser ( 2063): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: ac2dm
I/GLSUser ( 2063): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> ac2dm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2063): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2063): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2063): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/GLSUser ( 2063): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.syncadapters.calendar, service: oauth2:https://www.googleapis.com/auth/calendar
I/GLSUser ( 2063): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/calendar without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2063): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2063): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/art     (  347): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 417us total 18.154ms
V/NotificationService( 1032): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
V/GLSActivity( 2063): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1032): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1032): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1032): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1032): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1398): onNotificationPosted
,D/SmartCoverUpdateMonitor( 1398): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1398): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1398): handleNotificationPosted(true)
D/QuickCircle( 1398): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1398): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1398): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1398): post do just update job
D/LgeQuickCoverNotificationData( 1398): showAll3
D/LgeQuickCoverNotificationData( 1398): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1398): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1398): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1398): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1398): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1398): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1398): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1398): isNotificationForCurrentUser : true
W/Kids    ( 2316): [AccountUtils] Account not ready
W/Kids    ( 2316): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/Kids    ( 2316): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/Kids    ( 2316): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/Kids    ( 2316): 	at com.google.android.gms.auth.p.c(SourceFile:550)
W/Kids    ( 2316): 	at com.google.android.gms.auth.p.b(SourceFile:477)
W/Kids    ( 2316): 	at com.google.android.gms.kids.account.k.d(SourceFile:103)
W/Kids    ( 2316): 	at com.google.android.gms.kids.account.p.a(SourceFile:70)
W/Kids    ( 2316): 	at com.google.android.gms.kids.account.t.a(SourceFile:62)
W/Kids    ( 2316): 	at com.google.android.gms.chimera.f.run(SourceFile:179)
W/Kids    ( 2316): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Kids    ( 2316): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Kids    ( 2316): 	at java.lang.Thread.run(Thread.java:818)
D/LgeQuickCoverOverlayWindow( 1398): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1398): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1398): updateNotificationData: count=3
D/QuickStatusbarLayout( 1398): Notification difference=198
D/QuickStatusbarLayout( 1398): child = android.widget.LinearLayout{1f81f9d8 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,D/ALBootInit( 6933): ====action==>android.intent.action.TIME_SET
D/ALBootInit( 6933): Alarm ALBootInit: TIME_SET
D/Alarms  ( 6933): [setNextAlert] start
V/NotificationService( 1032): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1032): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1032): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1032): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1032): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1398): onNotificationPosted
W/ApiaryClient( 6629): Error response from books API: {
W/ApiaryClient( 6629):  "error": {
W/ApiaryClient( 6629):   "errors": [
W/ApiaryClient( 6629):    {
W/ApiaryClient( 6629):     "domain": "global",
W/ApiaryClient( 6629):     "reason": "required",
W/ApiaryClient( 6629):     "message": "Login Required",
W/ApiaryClient( 6629):     "locationType": "header",
W/ApiaryClient( 6629):     "location": "Authorization"
W/ApiaryClient( 6629):    }
W/ApiaryClient( 6629):   ],
W/ApiaryClient( 6629):   "code": 401,
W/ApiaryClient( 6629):   "message": "Login Required"
W/ApiaryClient( 6629):  }
W/ApiaryClient( 6629): }
W/ApiaryClient( 6629): errCount = 2: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6629): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-2683712148980154641&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6629): Headers:
W/ApiaryClient( 6629): accept-encoding: [gzip]
W/ApiaryClient( 6629): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6629): gdata-version: 2
,I/art     ( 1032): Explicit concurrent mark sweep GC freed 23248(1057KB) AllocSpace objects, 5(720KB) LOS objects, 33% free, 44MB/66MB, paused 1.572ms total 91.245ms
,D/SmartCoverUpdateMonitor( 1398): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1398): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1398): handleNotificationPosted(true)
D/QuickCircle( 1398): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1398): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1398): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1398): post do just update job
D/LgeQuickCoverNotificationData( 1398): showAll3
D/LgeQuickCoverNotificationData( 1398): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1398): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1398): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1398): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1398): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1398): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1398): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1398): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1398): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1398): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1398): updateNotificationData: count=3
D/Alarms  ( 6933): [setNextAlert] (1)
D/Alarms  ( 6933):  minTime  = 0
D/GCM     ( 2063): Connected
,D/Alarms  ( 6933):  -- OK multi -- 0
D/QuickStatusbarLayout( 1398): Notification difference=198
D/QuickStatusbarLayout( 1398): child = android.widget.LinearLayout{1f81f9d8 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
E/jeny.kim( 6933): [setNextAlert] setNextAlert  temp_Alarmlink + 
E/jeny.kim( 6933): [setNextAlert]setNextAlert temp_AlarmLinkText + 
E/CalendarSyncAdapter( 6860): Exception in onPerformLoggedSync 
E/CalendarSyncAdapter( 6860): com.google.android.apiary.AuthenticationException: Could not get an auth token
E/CalendarSyncAdapter( 6860): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(GoogleRequestInitializer.java:152)
E/CalendarSyncAdapter( 6860): 	at com.google.android.apiary.GoogleRequestInitializer.intercept(GoogleRequestInitializer.java:89)
E/CalendarSyncAdapter( 6860): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:858)
E/CalendarSyncAdapter( 6860): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(AbstractGoogleClientRequest.java:410)
E/CalendarSyncAdapter( 6860): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(AbstractGoogleClientRequest.java:343)
E/CalendarSyncAdapter( 6860): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(AbstractGoogleClientRequest.java:460)
E/CalendarSyncAdapter( 6860): 	at com.google.android.syncadapters.calendar.CalendarSyncAdapterApiary.processAccountCalendars(CalendarSyncAdapterApiary.java:1510)
E/CalendarSyncAdapter( 6860): 	at com.google.android.syncadapters.calendar.CalendarSyncAdapterApiary.updateCalendarsFromServerFeed(CalendarSyncAdapterApiary.java:1024)
E/CalendarSyncAdapter( 6860): 	at com.google.android.syncadapters.calendar.CalendarSyncAdapterApiary.getServerDiffs(CalendarSyncAdapterApiary.java:906)
E/CalendarSyncAdapter( 6860): 	at com.google.android.syncadapters.calendar.CalendarSyncAdapterApiary.performSync(CalendarSyncAdapterApiary.java:430)
E/CalendarSyncAdapter( 6860): 	at com.google.android.syncadapters.calendar.CalendarSyncAdapterApiary.onPerformLoggedSync(CalendarSyncAdapterApiary.java:335)
E/CalendarSyncAdapter( 6860): 	at com.google.android.common.LoggingThreadedSyncAdapter.onPerformSync(LoggingThreadedSyncAdapter.java:33)
E/CalendarSyncAdapter( 6860): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/CalendarSyncAdapter( 6860): Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/CalendarSyncAdapter( 6860): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/CalendarSyncAdapter( 6860): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/CalendarSyncAdapter( 6860): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(GoogleRequestInitializer.java:140)
E/CalendarSyncAdapter( 6860): 	... 12 more
,I/ActivityManager( 1032): Killing 6297:com.lge.settings.easy/1000 (adj 15): empty #17
,I/CommonUtil( 6933): BUILD Country: EU
D/GCM     ( 2063): Message class com.google.f.a.a.p
W/libprocessgroup( 1032): failed to open /acct/uid_1000/pid_6297/cgroup.procs: No such file or directory
,D/Alarms  ( 6933): broadcastToWidgetProvider : false
D/SyncManager( 1032): failed sync operation thalitester@gmail.com u0 (com.google), com.android.calendar, PERIODIC, currentRunTime 40080, reason: Periodic, SyncResult: stats [ numAuthExceptions: 1]
I/ActivityManager( 1032): Killing 6487:com.google.android.talk/u0a72 (adj 15): empty #17
D/SyncManager( 1032): not retrying sync operation because the error is a hard error: thalitester@gmail.com u0 (com.google), com.android.calendar, PERIODIC, currentRunTime 166516, reason: Periodic
W/libprocessgroup( 1032): failed to open /acct/uid_10072/pid_6487/cgroup.procs: No such file or directory
,D/Alarms  ( 6933): Enter formatDayAndTime(final Context context, long timeInMiliSec)
V/SettingsProvider( 1032): call_put(system:next_alarm_formatted=) for 0 calling package = com.lge.clock
,I/DigitalAppWidgetProvider( 6933): onReceive: android.intent.action.TIME_SET
V/DigitalAppWidgetProvider( 6933): cancelAlarmOnQuarterHour android.app.ReceiverRestrictedContext@2b2e07a9
,V/DigitalAppWidgetProvider( 6933): startAlarmOnQuarterHour android.app.ReceiverRestrictedContext@2b2e07a9
D/QuickCoverProvider( 6933): onReceiver
I/indal   ( 1398): SmartCoverWidgetContext createApplicationContext
I/indal   ( 1398): SmartCoverWidgetContext createApplicationContext
,D/WeatherAncestor( 6779): 2 : onReceive, action: android.intent.action.TIME_SET, Time(hour:min:sec) 19:13:33
,D/Weather.Utils( 6779): 2 : the weather widgets(using time tick) are gone.
D/Weather.Utils( 6779): 2 : All the weather widget is gone.
D/UpdateThreadPoolManager( 6779): 2 : This is isUpdating : false
D/WeatherService( 6779): 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@3ea4f12e
D/ForecastDataCache( 6779): 2 : lastUpdatedTime: 1430558561343
D/ForecastDataCache( 6779): 2 : currentPackageVersion: 4.40.4
D/ForecastDataCache( 6779): 2 : Cache is up-to-date, count: 0
D/Weather_cast( 6779): 2 : set auto-update time : 2/3 22:13
,D/WeatherAncestor( 6779): 2 : onReceive has processed, action: android.intent.action.TIME_SET, Time(hour:min:sec) 19:13:33
I/ActivityManager( 1032): Start proc com.qualcomm.timeservice for broadcast com.qualcomm.timeservice/.TimeServiceBroadcastReceiver: pid=6963 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,I/ActivityManager( 1032): Killing 6228:com.lge.sync/1000 (adj 15): empty #17
W/libprocessgroup( 1032): failed to open /acct/uid_1000/pid_6228/cgroup.procs: No such file or directory
,D/TimeService( 6963): Receivedandroid.intent.action.TIME_SET intent. Current Time is 1454523213414
D/        ( 6963): TimeServiceNative: User Time to be set is 1454523213414
,D/QC-time-services( 6963): Lib:time_genoff_operation: pargs->base = 2
D/QC-time-services( 6963): Lib:time_genoff_operation: pargs->operation = 0
D/QC-time-services( 6963): Lib:time_genoff_operation: pargs->ts_val = 1454523213414
D/QC-time-services( 6963): Lib:time_genoff_operation: Send to server  passed!!
D/QC-time-services(  359): Daemon: Connection accepted:time_genoff
D/QC-time-services(  359): Daemon:Received base = 2, unit = 1, operation = 0,value = 1454523213414
D/QC-time-services(  359): Daemon:genoff_opr: Base = 2, val = 1454523213414, operation = 0
D/QC-time-services(  359): Daemon:rtc_get: Time read from RTC -- MM/DD/YY HH:MM:SS5/13/70 11:25:39
D/QC-time-services(  359): Daemon:Value read from RTC seconds = 14124339000
D/QC-time-services(  359): Daemon:new time 1454523213414 
D/QC-time-services(  359): Daemon: delta 1440398874414 genoff 1440398874414 
D/QC-time-services(  359): Daemon:genoff_persistent_update: Writing genoff = 1440398874414 to memory
D/QC-time-services(  359): Daemon:Opening File: /data/time/ats_2
D/QC-time-services(  359): Daemon:time_persistent_memory_opr:Genoff write operation 
D/QC-time-services(  359): Updating the TOD offset
D/QC-time-services(  359): Daemon:genoff_persistent_update: Writing genoff = 1440398874414 to memory
D/QC-time-services(  359): Daemon:Opening File: /data/time/ats_1
D/QC-time-services(  359): Daemon:time_persistent_memory_opr:Genoff write operation 
E/QC-time-services(  359): Daemon:Update to modem bit set
,D/QC-time-services(  359): Daemon:genoff_send_modem: Sending data to MODEM !
D/QC-time-services(  359): Daemon: Base = 2, Value being sent to MODEM = 1124434074414
E/QC-time-services( 6963): Receive Passed == base = 2, unit = 1, operation = 0, result = 0
,E/QC-time-services(  359): Daemon:tod_update_ind_cb: Got Update from modem msg_id 40
E/QC-time-services(  359): Daemon: Time-services: Waiting to acceptconnection
I/GCoreUlr( 1790): Uploading GCM registration ID for account#2#
I/ActivityManager( 1032): Start proc com.android.calendar for broadcast com.android.calendar/.widget.CalendarAppWidgetProvider: pid=6986 uid=10013 gids={50013, 9997, 3003, 1028, 1015} abi=armeabi
,I/ActivityManager( 1032): Killing 5873:com.uei.lg.quicksetsdk.maxq616/1000 (adj 15): empty #17
I/QRemote ( 6325): [RemoteControlManager.java:195:onServiceDisconnected()] oooooo start
W/System.err( 6325): android.os.DeadObjectException
,W/System.err( 6325): 	at android.os.BinderProxy.transactNative(Native Method)
W/System.err( 6325): 	at android.os.BinderProxy.transact(Binder.java:496)
,W/System.err( 6325): 	at com.uei.control.IControl.unregisterCallback(IControl.java:502)
,W/System.err( 6325): 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:199)
W/System.err( 6325): 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
W/System.err( 6325): 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
W/System.err( 6325): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 6325): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 6325): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 6325): 	at android.app.ActivityThread.main(ActivityThread.java:5274)
,W/System.err( 6325): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 6325): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 6325): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
W/System.err( 6325): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
E/UEI.SmartControl( 6325): IControl.unregisterCallback error: android.os.DeadObjectException
W/System.err( 6325): android.os.DeadObjectException
W/System.err( 6325): 	at android.os.BinderProxy.transactNative(Native Method)
W/System.err( 6325): 	at android.os.BinderProxy.transact(Binder.java:496)
W/System.err( 6325): 	at com.uei.control.IControl.unregisterSetupReadyCallback(IControl.java:818)
W/System.err( 6325): 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:200)
W/System.err( 6325): 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
W/System.err( 6325): 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
W/System.err( 6325): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 6325): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 6325): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 6325): 	at android.app.ActivityThread.main(ActivityThread.java:5274)
W/System.err( 6325): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 6325): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 6325): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
W/System.err( 6325): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
E/UEI.SmartControl( 6325): IControl.unregisterSetupReadyCallback error: android.os.DeadObjectException
I/QRemote ( 6325): [RemoteControlManager.java:203:onServiceDisconnected()] oooooo Control unbind before rebinding.
W/libprocessgroup( 1032): failed to open /acct/uid_1000/pid_5873/cgroup.procs: No such file or directory
W/ActivityManager( 1032): Scheduling restart of crashed service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service in 1000ms
,D/QRemote ( 6325): [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]10
I/QRemote ( 6325): [RemoteControlManager.java:157:onBindIRService()] oooooo bind
W/ResourcesManager( 6986): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/ActivityManager( 1032): Start proc com.uei.lg.quicksetsdk.maxq616 for service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service: pid=7006 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
D/QRemote ( 6325): [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
,W/BaseAppContext( 1790): Using Auth Proxy for data requests.
,D/CalendarApplication( 6986): CalendarApplication.onCreate()
D/PreferenceKeysParser( 6986): [debug_displayParseInfos] preference keys.size() = 44
D/PreferenceKeysParser( 6986): [debug_displayParseInfos] preference keys = {lg_preferences_tardis_1=com.android.calendar.adaptation.PreferenceKey$KeyData@27a8cac4, lg_preferences_hide_declined=com.android.calendar.adaptation.PreferenceKey$KeyData@283e3dad, lg_preferences_default_reminder=com.android.calendar.adaptation.PreferenceKey$KeyData@3a1928e2, lg_preferences_month_view_style=com.android.calendar.adaptation.PreferenceKey$KeyData@27f77473, lg_preferences_alerts_ringtone=com.android.calendar.adaptation.PreferenceKey$KeyData@2dc9cf30, lg_preferences_device_tz=com.android.calendar.adaptation.PreferenceKey$KeyData@2b2e07a9, lg_preferences_debug_datesearch=com.android.calendar.adaptation.PreferenceKey$KeyData@3ea4f12e, lg_preferences_debug_country=com.android.calendar.adaptation.PreferenceKey$KeyData@254ae4cf, lg_preferences_display_weather_information=com.android.calendar.adaptation.PreferenceKey$KeyData@39b4ae5c, lg_preferences_alerts_vibrateWhen=com.android.calendar.adaptation.PreferenceKey$KeyData@16367565, lg_preferences_debug_rtl=com.android.calendar.adaptation.PreferenceKey$KeyData@3e12f23a, lg_preferences_alerts_type=com.android.calendar.adaptation.PreferenceKey$KeyData@6bafeeb, lg_preferrences_country_code=com.android.calendar.adaptation.PreferenceKey$KeyData@2c0c5448, lg_preferences_weather_info=com.android.calendar.adaptation.PreferenceKey$KeyData@3a9e02e1, lg_preference_holiday_calendar_ver=com.android.calendar.adaptation.PreferenceKey$KeyData@352df806, lg_preferences_show_controls=com.android.calendar.adaptation.PreferenceKey$KeyData@c89ec7, lg_preferences_user_select_noti_sound=com.android.calendar.adaptation.PreferenceKey$KeyData@ab66cf4, lg_preference_default_myphonebook=com.android.calendar.adaptation.PreferenceKey$KeyData@1d96ec1d, lg_preferences_skip_setup=com.android.calendar.adaptation.PreferenceKey$KeyData@10a18e92, lg_preferred_startView=com.android.calendar.adaptation.PreferenceKey$KeyData@25266063, lg_preferences_debug_operator=com.android.calendar.adaptation.PreferenceKey$KeyData@32476460, lg_preferences_exclude_sticker_list=com.android.calendar.adaptation.PreferenceKey$KeyData@2b3b2d19, lg_preferences_writable_calendars_count=com.android.calendar.adaptation.PreferenceKey$KeyData@2a4601de, lg_preferred_detailedView=com.android.calendar.adaptation.PreferenceKey$KeyData@24149fbf, lg_preferences_debug_floating=com.android.calendar.adaptation.PreferenceKey$KeyData@322e668c, lg_preferences_home_tz=com.android.calendar.adaptation.PreferenceKey$KeyData@1d4881d5, lg_preferences_home_tz_enabled=com.android.calendar.adaptation.PreferenceKey$KeyData@f2c5dea, lg_preference_received_provider_reminder_broadcast=com.android.calendar.adaptation.PreferenceKey$KeyData@77d78db, lg_preferences_default_cell_height=com.android.calendar.adaptation.PreferenceKey$KeyData@3fa15f78, lg_preferences_notification_type=com.android.calendar.adaptation.PreferenceKey$KeyData@119c6651, lg_preferences_show_week_num=com.android.calendar.adaptation.PreferenceKey$KeyData@1a6a6eb6, lg_preferences_dont_show_again_no_online_account=com.android.calendar.adaptation.PreferenceKey$KeyData@3d0c7b7, lg_preferences_alerts_popup=com.android.calendar.adaptation.PreferenceKey$KeyData@2b48fb24, lg_preferences_week_start_day=com.android.calendar.adaptation.PreferenceKey$KeyData@c70168d, lg_preferences_app_version=com.android.calendar.adaptation.PreferenceKey$KeyData@30a6c042, lg_preferences_alerts=com.android.calendar.adaptation.PreferenceKey$KeyData@3aa02853, lg_preferences_select_aux_calendar=com.android.calendar.adaptation.PreferenceKey$KeyData@5aca590, lg_preferences_widget_info_calendars=com.android.calendar.adaptation.PreferenceKey$KeyData@22548e89, lg_preferences_alerts_default_ringtone=com.android.calendar.adaptation.PreferenceKey$KeyData@28649e8e, lg_preference_defaultCalendar=com.android.calendar.adaptation.PreferenceKey$KeyData@afaf6af, lg_preferences_alerts_vibratetype=com.android.calendar.a,daptation.PreferenceKey$KeyData@1e5e8abc, lg_preferences_recent_timezones=com.android.calendar.adaptation.PreferenceKey$KeyData@5ee8a45,
,D/GeneralPreferenceUtils( 6986): [migratePrefrenceKeys] Exit: Version(44001600) >= 42001300
D/UEI.SmartControl( 7006): Quickset Services start...
I/UEI.SmartControl( 7006): Manufacture = LGE
D/UEI.SmartControl( 7006): Id = LGNevo
D/UEI.SmartControl( 7006): File observer start...
E/UEI.SmartControl( 7006): IR Port is disabled: false
D/UEI.SmartControl( 7006): Starting file observer...
D/UEI.SmartControl( 7006): Extracting JNI libs...
D/UEI.SmartControl( 7006): --- this system supports 32-bit or 64-bit only
D/Config  ( 6986): [init]
I/Config  ( 6986): LGCalendar ver.4.40.16
I/GLSUser ( 1790): [ChannelManager] Attempting to channel bind connection HttpClient.
I/Config  ( 6986): start check model
I/Config  ( 6986): start check native_ca
I/Config  ( 6986): Config Operator=OPEN, Country=EU
D/Config  ( 6986): [setDefaultValuesToPref]
D/Config  ( 6986): [parseProfiles]
,D/ProfilesParser( 6986): [debug_displayParseInfos] profile.country = null
D/ProfilesParser( 6986): [debug_displayParseInfos] profile.operator = null
D/Config  ( 6986): [updateProfiletoCountryInfo]
D/GeneralPreference( 6986): [checkAndMigrateOldPreference]
E/AgendaWidgetManager( 6986): [updateWidgets] 
,I/GLSUser ( 1790): [ChannelManager] Checking whether channelId is enabled. isEnabledGmsCore? false, isEnabledSdk? true, isAtLeastKitKat? true
I/GLSUser ( 2063): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/userlocation.reporting
I/GLSUser ( 2063): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/userlocation.reporting without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 2063): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2063): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2063): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/UEI.SmartControl( 7006): --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
D/UEI.SmartControl( 7006): --- Checking lib: libqs_armeabi-v7a.zip
D/UEI.SmartControl( 7006): --- Extracting JNI libs: libqs_armeabi-v7a.zip
,E/WifiStateMachine( 1032):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=5.1, 0.0, 0.0  rx=3.8 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1470699358] gl rssi=-63 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
E/WifiStateMachine( 1032):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=5.1, 0.0, 0.0  rx=3.8 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-1470699357] gl rssi=-63 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
D/WifiNative-wlan0( 1032): doString: [SIGNAL_POLL]
V/GLSActivity( 2063): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
E/GCoreUlr( 1790): 
E/GCoreUlr( 1790): com.google.android.gms.auth.ad: BadAuthentication
E/GCoreUlr( 1790): 	at com.google.android.gms.auth.p.b(SourceFile:442)
E/GCoreUlr( 1790): 	at com.google.android.gms.auth.p.a(SourceFile:365)
E/GCoreUlr( 1790): 	at com.google.android.gms.auth.p.a(SourceFile:310)
E/GCoreUlr( 1790): 	at com.google.android.gms.common.server.a.a.b(SourceFile:97)
E/GCoreUlr( 1790): 	at com.google.android.gms.common.server.c.b(SourceFile:109)
E/GCoreUlr( 1790): 	at com.google.android.gms.common.server.o.b(SourceFile:30)
E/GCoreUlr( 1790): 	at com.google.android.gms.common.server.o.b(SourceFile:370)
E/GCoreUlr( 1790): 	at com.google.android.gms.common.server.o.a(SourceFile:340)
E/GCoreUlr( 1790): 	at com.google.android.gms.common.server.o.a(SourceFile:319)
E/GCoreUlr( 1790): 	at com.google.android.location.reporting.c.c.a(SourceFile:166)
E/GCoreUlr( 1790): 	at com.google.android.location.reporting.c.g.a(SourceFile:111)
E/GCoreUlr( 1790): 	at com.google.android.location.reporting.service.t.b(SourceFile:220)
E/GCoreUlr( 1790): 	at com.google.android.location.reporting.service.t.a(SourceFile:173)
E/GCoreUlr( 1790): 	at com.google.android.location.reporting.service.s.onPerformSync(SourceFile:149)
E/GCoreUlr( 1790): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
,I/UEI.SmartControl( 7006): --- Selecting new region: 6
,I/UEI.SmartControl( 7006): Model = LG-D855
D/UEI.SmartControl( 7006): QS Service created
I/UEI.SmartControl( 7006): Service initServices...
,I/GLSUser ( 2063): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2063): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2063): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2063): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
D/UEI.SmartControl( 7006): QS start get config
D/SyncManager( 1032): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.location.reporting, PERIODIC, currentRunTime 40091, reason: Periodic, SyncResult: stats [ numAuthExceptions: 1]
D/SyncManager( 1032): not retrying sync operation because the error is a hard error: thalitester@gmail.com u0 (com.google), com.google.android.location.reporting, PERIODIC, currentRunTime 167307, reason: Periodic
,V/GLSActivity( 2063): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1032): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1032): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1032): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1032): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1032): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
W/GLSActivity( 2063): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2063): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2063): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2063): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2063): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2063): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2063): 	at android.os.Binder.execTransact(Binder.java:446)
E/BooksAccountManager( 6629): Authentication error
E/BooksAccountManager( 6629): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6629): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6629): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6629): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6629): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6629): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6629): null auth token
D/LgeQuickCoverNLService( 1398): onNotificationPosted
D/SmartCoverUpdateMonitor( 1398): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1398): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1398): handleNotificationPosted(true)
D/QuickCircle( 1398): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1398): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1398): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1398): post do just update job
D/LgeQuickCoverNotificationData( 1398): showAll3
D/LgeQuickCoverNotificationData( 1398): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1398): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1398): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1398): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1398): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1398): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1398): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1398): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1398): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1398): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1398): updateNotificationData: count=3
I/InitNotificationRingtoneService( 6986): Start InitializeAlertRingtoneService.onHandleIntent
D/MonthWidgetProvider( 6986): [onReceive]
D/CalendarWidgetProvider( 6986): [onReceive]
D/CalendarWidgetProvider( 6986): [CalendarWidgetProvider] got the intent: Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.android.calendar/.widget.MonthWidgetProvider }
W/HolidayIntentService( 6986): onHandleIntent
,D/CalendarTypeController( 6986): [onUpdateAndInitCalendarTime]
,I/AlertUtils( 6986): [setFormatNotificationSound] current noti URI = content://media/internal/audio/media/41
D/HolidayDataLoader( 6986): readJsonAsset : holiday.json
D/WeekWidgetProvider( 6986): [onReceive]
D/CalendarWidgetProvider( 6986): [onReceive]
D/CalendarWidgetProvider( 6986): [CalendarWidgetProvider] got the intent: Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.android.calendar/.widget.WeekWidgetProvider }
D/CalendarTypeController( 6986): [onUpdateAndInitCalendarTime]
D/QuickStatusbarLayout( 1398): Notification difference=198
D/QuickStatusbarLayout( 1398): child = android.widget.LinearLayout{1f81f9d8 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,I/AlertUtils( 6986): [getCalendarNotiSoundURIFromCursor] getCount()= 21
D/UEI.SmartControl( 7006): Loading JNI Libs...
I/AlertUtils( 6986): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Arpeggio.ogg
,I/AlertUtils( 6986): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Country_Blues.ogg
,E/HolidayIntentService( 6986): onHandleIntent:holiday data empty
I/AlertUtils( 6986): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Crystal.ogg
I/AlertUtils( 6986): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Dewdrop.ogg
,I/AlertUtils( 6986): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Ding_Dong.ogg
I/AlertUtils( 6986): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Echo.ogg
I/AlertUtils( 6986): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Email.ogg
I/AlertUtils( 6986): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Game_Over.ogg
,I/AlertUtils( 6986): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Gayageum.ogg
I/AlertUtils( 6986): [getMediaFilepathFromContentUri] filepath = /system/media/audio/alarms/Afternoon_Walk.ogg
I/AlertUtils( 6986): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Harmonics.ogg
I/AlertUtils( 6986): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Idea.ogg
,D/GCM     ( 2063): GcmService start Intent { act=com.google.android.gcm.intent.SEND flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.gcm.intent.SEND
I/AlertUtils( 6986): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/News.ogg
I/AlertUtils( 6986): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Pebble.ogg
I/AlertUtils( 6986): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Schedule.ogg
I/AlertUtils( 6986): [getCalendarNotiSoundURIFromCursor] filePath = /system/media/audio/notifications/Schedule.ogg, new URI = content://media/internal/audio/media/41
I/ActivityManager( 1032): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.realtimechat.RequestWriter$NetworkStateReceiver: pid=7048 uid=10072 gids={50072, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
I/AlertUtils( 6986): set default noti to content://media/internal/audio/media/41
,W/ApiaryClient( 6629): Error response from books API: {
W/ApiaryClient( 6629):  "error": {
W/ApiaryClient( 6629):   "errors": [
W/ApiaryClient( 6629):    {
W/ApiaryClient( 6629):     "domain": "global",
W/ApiaryClient( 6629):     "reason": "required",
W/ApiaryClient( 6629):     "message": "Login Required",
W/ApiaryClient( 6629):     "locationType": "header",
W/ApiaryClient( 6629):     "location": "Authorization"
W/ApiaryClient( 6629):    }
W/ApiaryClient( 6629):   ],
W/ApiaryClient( 6629):   "code": 401,
W/ApiaryClient( 6629):   "message": "Login Required"
W/ApiaryClient( 6629):  }
W/ApiaryClient( 6629): }
W/ApiaryClient( 6629): errCount = 3: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6629): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-2683712148980154641&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6629): Headers:
W/ApiaryClient( 6629): accept-encoding: [gzip]
W/ApiaryClient( 6629): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6629): gdata-version: 2
I/InitNotificationRingtoneService( 6986): End InitializeAlertRingtoneService.onHandleIntent
,I/ActivityManager( 1032): Killing 6167:com.android.settings/1000 (adj 15): empty #17
D/WifiService( 1032): Client connection lost with reason: 4
,W/libprocessgroup( 1032): failed to open /acct/uid_1000/pid_6167/cgroup.procs: No such file or directory
W/ResourcesManager( 7048): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/UEI.SmartControl( 7006): Supports setup maps: true,
,D/UEI.SmartControl( 7006): QS start statue = true Error code = 0
I/UEI.SmartControl( 7006): QS version = v2.7.10.1_RC1
I/UEI.SmartControl( 7006): QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
I/UEI.SmartControl( 7006): ### init IR Blaster...
D/serial_port( 7006): Configuring serial port
,E/UEI.SmartControl( 7006): UEIBLaster setting for 616
I/UEI.SmartControl( 7006): Setting serial record hearder size = 2
,I/UEI.SmartControl( 7006): configuring settings for MAXQ616
I/UEI.SmartControl( 7006): Get version...
D/UEI.SmartControl( 7006): serial port data available: 21
,I/ActivityManager( 1032): Start proc com.google.android.gm for service com.google.android.gm/.provider.MailSyncAdapterService: pid=7068 uid=10064 gids={50064, 9997, 3003, 1028, 1015} abi=armeabi-v7a
D/UEI.SmartControl( 7006): MAXQ616 A2-X4 software.
,I/UEI.SmartControl( 7006): IR Blaster version: 256702256704300002
I/UEI.SmartControl( 7006): QS saving settings...
D/UEI.SmartControl( 7006): IR Blaster version: 25672567
,D/UEI.SmartControl( 7006): serial port data available: 4
D/LgDataFeature( 7048): LgDataFeature() Constructor: none
D/LgDataFeature( 7048): LgDataFeature() Constructor Done, null
I/UEI.SmartControl( 7006): Device manager: loading config....
W/ContextImpl( 7006): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
D/UEI.SmartControl( 7006): ----------- loading internal config...
E/UEI.SmartControl( 7006): Services init done
D/UEI.SmartControl( 7006): QS Service init finished
,D/UEI.SmartControl( 7006): QS Service version name: 2.1.91
D/UEI.SmartControl( 7006): QS Service version code: 201091
D/UEI.SmartControl( 7006): Service requested: Control
E/UEI.SmartControl( 7006): Loading SETTINGS...
D/UEI.SmartControl( 7006): -- Open brand translation xml: brands_translations_ko
D/UEI.SmartControl( 7006): Request IControl service: devices are loaded...
,I/UEI.SmartControl( 7006): Notify AllClients services are ready: 0
D/UEI.SmartControl( 7006): -----service ready thread exits
I/ActivityManager( 1032): Killing 6325:com.lge.qremote/u0a112 (adj 15): empty #17
,I/Babel   ( 7048): MmsConfig: mnc/mcc: 0/0
I/Babel   ( 7048): MmsConfig.loadMmsSettings
W/libprocessgroup( 1032): failed to open /acct/uid_10112/pid_6325/cgroup.procs: No such file or directory
D/UEI.SmartControl( 7006): Internal service binding...
W/ActivityManager( 1032): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,D/ActivityThread( 7068): Loading provider com.google.android.gmail.provider;com.android.mail.notifier;com.google.android.gm.email.provider;com.google.android.gm.email.notifier: com.android.email.provider.EmailProvider
W/ActivityManager( 1032): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
I/Babel   ( 7048): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D855 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D855-M3-D1.xml
I/Babel   ( 7048): MmsConfig.loadFromDatabase
,W/Settings( 7048): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
E/Babel   ( 7048): canonicalizeMccMnc: invalid mccmnc 
I/Babel   ( 7048): MmsConfig.loadFromResources
E/Babel   ( 7048): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel   ( 7048): MmsConfig.loadMmsSettings: mUserAgent=LG-D855 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D855-M3-D1.xml
,W/AudioCapabilities( 7048): Unsupported mime audio/evrc
W/AudioCapabilities( 7048): Unsupported mime audio/qcelp
W/VideoCapabilities( 7048): Unrecognized profile 2130706433 for video/avc
I/DigitalAppWidgetProvider( 6933): onReceive: android.intent.action.ALARM_CHANGED
,D/WeatherAncestor( 6779): 2 : onReceive, action: com.lge.sizechangable.weather.action.setweathercast, Time(hour:min:sec) 19:13:34
D/Weather.Utils( 6779): 2 : the weather widgets(using time tick) are gone.
D/Weather.Utils( 6779): 2 : All the weather widget is gone.
D/UpdateThreadPoolManager( 6779): 2 : This is isUpdating : false
D/Weather_cast( 6779): 2 : Update is Canceled by com.lge.sizechangable.weather.action.alarm
D/WeatherAncestor( 6779): 2 : onReceive has processed, action: com.lge.sizechangable.weather.action.setweathercast, Time(hour:min:sec) 19:13:34
W/AudioCapabilities( 7048): Unsupported mime audio/amr-wb-plus
W/AudioCapabilities( 7048): Unsupported mime audio/qcelp
W/AudioCapabilities( 7048): Unsupported mime audio/evrc
W/ResourcesManager( 7048): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/VideoCapabilities( 7048): Unsupported mime video/x-ms-wmv
W/ResourcesManager( 7048): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
W/VideoCapabilities( 7048): Unsupported mime video/divx
W/VideoCapabilities( 7048): Unsupported mime video/divx311
W/VideoCapabilities( 7048): Unsupported mime video/divx4
,W/VideoCapabilities( 7048): Unsupported mime video/mp4v-esdp
I/Gmail   ( 7068): getAccountsCursor
,W/ActivityManager( 1032): Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
W/ActivityManager( 1032): Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
I/VideoCapabilities( 7048): Unsupported profile 4 for video/mp4v-es
W/ActivityManager( 1032): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,W/GAV2    ( 7068): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,W/AudioCapabilities( 7048): Unsupported mime audio/eac3
W/AudioCapabilities( 7048): Unsupported mime audio/ac3
V/GLSActivity( 2063): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/ActivityManager( 1032): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,I/Gmail   ( 7068): Observing account changes for notifications
W/AudioCapabilities( 7048): Unsupported mime audio/g726
W/AudioCapabilities( 7048): Unsupported mime audio/wma-voice
,W/AudioCapabilities( 7048): Unsupported mime audio/x-ms-wma
W/AudioCapabilities( 7048): Unsupported mime audio/adpcm
W/VideoCapabilities( 7048): Unsupported mime video/theora
W/VideoCapabilities( 7048): Unsupported mime video/mjpg
,V/JNIHelp ( 7048): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
W/System  ( 7048): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/system/framework/com.google.android.media.effects.jar", zip file "/system/app/Hangouts/Hangouts.apk"],nativeLibraryDirectories=[/system/app/Hangouts/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 7048): Installed default security provider GmsCore_OpenSSL
,I/art     ( 1032): Explicit concurrent mark sweep GC freed 17927(812KB) AllocSpace objects, 2(160KB) LOS objects, 33% free, 44MB/66MB, paused 1.268ms total 81.629ms
,W/ActivityManager( 1032): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
E/Gmail   ( 7068): Error finding the version of the Email provider.....
E/Gmail   ( 7068): android.content.pm.PackageManager$NameNotFoundException: com.google.android.email
E/Gmail   ( 7068): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
E/Gmail   ( 7068): 	at com.google.android.gm.EmailMigrationService.aU(SourceFile:1235)
E/Gmail   ( 7068): 	at com.google.android.gm.EmailMigrationService.onHandleIntent(SourceFile:187)
E/Gmail   ( 7068): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/Gmail   ( 7068): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/Gmail   ( 7068): 	at android.os.Looper.loop(Looper.java:135)
E/Gmail   ( 7068): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/EmailMigration( 7068): We do not support migrating this version of the Email provider.
,W/Gmail   ( 7068): Sync started for account: account:61035162
I/Gmail   ( 7068): getAccountsCursor
V/GLSActivity( 2063): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/GLSActivity( 2063): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/SQLiteLog( 7068): (283) recovered 1458 frames from WAL file /data/data/com.google.android.gm/databases/mailstore.thalitester@gmail.com.db-wal
,I/GLSUser ( 2063): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.talk, service: oauth2:https://www.googleapis.com/auth/chat https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/hangouts https://www.googleapis.com/auth/identity.plus.page.impersonation https://www.googleapis.com/auth/chat.native
I/GLSUser ( 2063): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/chat https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/hangouts https://www.googleapis.com/auth/identity.plus.page.impersonation https://www.googleapis.com/auth/chat.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2063): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2063): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2063): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/art     ( 2063): Explicit concurrent mark sweep GC freed 34996(1973KB) AllocSpace objects, 15(1904KB) LOS objects, 50% free, 30MB/62MB, paused 816us total 29.658ms
,E/Babel   ( 7048): UserRecoverableAuthException.
E/Babel   ( 7048): cfq: BadAuthentication
E/Babel   ( 7048): 	at cfn.a(Unknown Source)
E/Babel   ( 7048): 	at f.a(PG:191)
E/Babel   ( 7048): 	at ava.a(PG:88)
E/Babel   ( 7048): 	at ava.a(PG:128)
E/Babel   ( 7048): 	at bjs.a(PG:255)
E/Babel   ( 7048): 	at bep.a(PG:602)
E/Babel   ( 7048): 	at bep.a(PG:469)
E/Babel   ( 7048): 	at bpo.run(PG:1141)
E/Babel   ( 7048): Error getting auth token
E/Babel   ( 7048): bxl
E/Babel   ( 7048): 	at f.a(PG:201)
E/Babel   ( 7048): 	at ava.a(PG:88)
E/Babel   ( 7048): 	at ava.a(PG:128)
E/Babel   ( 7048): 	at bjs.a(PG:255)
E/Babel   ( 7048): 	at bep.a(PG:602)
E/Babel   ( 7048): 	at bep.a(PG:469)
E/Babel   ( 7048): 	at bpo.run(PG:1141)
I/Babel_RequestWriter( 7048): error sending REQ[fc:8; creat:1454461440466; type:bev-841561102]; took 139 ms (error code == 100)
E/Babel   ( 7048): Account registration failedRedacted-21
E/Babel   ( 7048): bph: null -- null
E/Babel   ( 7048): 	at ava.a(PG:120)
E/Babel   ( 7048): 	at ava.a(PG:128)
E/Babel   ( 7048): 	at bjs.a(PG:255)
E/Babel   ( 7048): 	at bep.a(PG:602)
E/Babel   ( 7048): 	at bep.a(PG:469)
E/Babel   ( 7048): 	at bpo.run(PG:1141)
I/Babel   ( 7048): Account setup failed with error state:106 account:Redacted-21
I/Babel   ( 7048): Account sign in complete with state 106account: Redacted-21
,I/GLSUser ( 2063): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.talk, service: oauth2:https://www.googleapis.com/auth/chat https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/hangouts https://www.googleapis.com/auth/identity.plus.page.impersonation https://www.googleapis.com/auth/chat.native
,I/GLSUser ( 2063): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/chat https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/hangouts https://www.googleapis.com/auth/identity.plus.page.impersonation https://www.googleapis.com/auth/chat.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2063): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2063): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2063): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/ResourcesManager( 2063): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/art     ( 7048): Note: end time exceeds epoch: 
V/NotificationService( 1032): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
V/NotificationService( 1032): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1032): LED remove() : mLights=0|com.google.android.gms|1|null|10005
,D/NotificationServiceEx( 1032): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1032): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,E/Babel   ( 7048): Unexpected exception while authenticating.
,E/Babel   ( 7048): cfr: User intervention required. Notification has been pushed.
E/Babel   ( 7048): 	at cfn.b(Unknown Source)
E/Babel   ( 7048): 	at cfn.a(Unknown Source)
E/Babel   ( 7048): 	at f.a(PG:188)
E/Babel   ( 7048): 	at ava.b(PG:143)
E/Babel   ( 7048): 	at bnr.run(PG:5415)
E/Babel   ( 7048): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/Babel   ( 7048): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/Babel   ( 7048): 	at java.lang.Thread.run(Thread.java:818)
D/LgeQuickCoverNLService( 1398): onNotificationPosted
D/SmartCoverUpdateMonitor( 1398): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1398): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1398): handleNotificationPosted(true)
D/QuickCircle( 1398): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1398): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1398): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1398): post do just update job
D/LgeQuickCoverNotificationData( 1398): showAll3
D/LgeQuickCoverNotificationData( 1398): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1398): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1398): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1398): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1398): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1398): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1398): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1398): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1398): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1398): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1398): updateNotificationData: count=3
D/QuickStatusbarLayout( 1398): Notification difference=198
D/QuickStatusbarLayout( 1398): child = android.widget.LinearLayout{1f81f9d8 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,I/Gmail   ( 7068): notifyAccountChanged
I/Gmail   ( 7068): getAccountsCursor
I/Gmail   ( 7068): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
I/Gmail   ( 7068): notifyAccountChanged
V/GLSActivity( 2063): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Gmail   ( 7068): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
I/Gmail   ( 7068): calculateUnknownSyncRationalesAndPurgeInBackground: running
I/Gmail   ( 7068): calculateUnknownSyncRationalesAndPurgeInBackground: running
I/Gmail   ( 7068): getAccountsCursor
,I/Gmail   ( 7068): MainSyncRequestProto: lowestBkwdConvoId: 0, highestHandledServerOp: 5310, normalSync: true
V/GLSActivity( 2063): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/ResourcesManager( 7068): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 7068): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 7068): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,E/BooksSync( 6629): Soft error: 
E/BooksSync( 6629): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 6629): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-2683712148980154641&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 6629): Headers:
E/BooksSync( 6629): accept-encoding: [gzip]
E/BooksSync( 6629): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 6629): gdata-version: 2
E/BooksSync( 6629): 
E/BooksSync( 6629): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 6629): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 6629): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 6629): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 6629): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 6629): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 6629): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 6629): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 6629): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 6629): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 6629): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 6629): {
E/BooksSync( 6629):  "error": {
E/BooksSync( 6629):   "errors": [
E/BooksSync( 6629):    {
E/BooksSync( 6629):     "domain": "global",
E/BooksSync( 6629):     "reason": "required",
E/BooksSync( 6629):     "message": "Login Required",
E/BooksSync( 6629):     "locationType": "header",
E/BooksSync( 6629):     "location": "Authorization"
E/BooksSync( 6629):    }
E/BooksSync( 6629):   ],
E/BooksSync( 6629):   "code": 401,
E/BooksSync( 6629):   "message": "Login Required"
E/BooksSync( 6629):  }
E/BooksSync( 6629): }
E/BooksSync( 6629): 
E/BooksSync( 6629): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 6629): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 6629): 	... 8 more
,E/BooksSync( 6629): Sync error
E/BooksSync( 6629): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 6629): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-2683712148980154641&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 6629): Headers:
E/BooksSync( 6629): accept-encoding: [gzip]
E/BooksSync( 6629): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 6629): gdata-version: 2
E/BooksSync( 6629): 
E/BooksSync( 6629): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 6629): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 6629): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 6629): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 6629): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 6629): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 6629): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 6629): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 6629): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 6629): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 6629): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 6629): {
E/BooksSync( 6629):  "error": {
E/BooksSync( 6629):   "errors": [
E/BooksSync( 6629):    {
E/BooksSync( 6629):     "domain": "global",
E/BooksSync( 6629):     "reason": "required",
E/BooksSync( 6629):     "message": "Login Required",
E/BooksSync( 6629):     "locationType": "header",
E/BooksSync( 6629):     "location": "Authorization"
E/BooksSync( 6629):    }
E/BooksSync( 6629):   ],
E/BooksSync( 6629):   "code": 401,
E/BooksSync( 6629):   "message": "Login Required"
E/BooksSync( 6629):  }
E/BooksSync( 6629): }
E/BooksSync( 6629): 
E/BooksSync( 6629): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 6629): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 6629): 	... 8 more
I/BooksSync( 6629): Finished books sync
W/System  ( 7068): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[directory "."],nativeLibraryDirectories=[/vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 7068): Installed default security provider GmsCore_OpenSSL
V/GLSActivity( 2063): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/SyncManager( 1032): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 26450, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,I/ActivityManager( 1032): Killing 4869:com.android.vending/u0a44 (adj 15): empty #17
W/libprocessgroup( 1032): failed to open /acct/uid_10044/pid_4869/cgroup.procs: No such file or directory
,I/GLSUser ( 2063): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gm, service: mail
I/GLSUser ( 2063): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> mail without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2063): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2063): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2063): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1032): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1032): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1032): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1032): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1032): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
W/GLSActivity( 2063): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2063): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2063): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2063): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2063): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2063): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2063): 	at android.os.Binder.execTransact(Binder.java:446)
D/LgeQuickCoverNLService( 1398): onNotificationPosted
,D/SmartCoverUpdateMonitor( 1398): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1398): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1398): handleNotificationPosted(true)
D/QuickCircle( 1398): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1398): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1398): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1398): post do just update job
D/LgeQuickCoverNotificationData( 1398): showAll3
D/LgeQuickCoverNotificationData( 1398): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1398): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1398): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1398): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1398): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1398): isNotificationForCurrentUser : true
V/GLSActivity( 2063): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/LgeQuickCoverOverlayWindow( 1398): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1398): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1398): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1398): isNotificationForCurrentUser : true
,E/LgeQuickCoverOverlayWindow( 1398): updateNotificationData: count=3
D/QuickStatusbarLayout( 1398): Notification difference=198
D/QuickStatusbarLayout( 1398): child = android.widget.LinearLayout{1f81f9d8 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,I/GLSUser ( 2063): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gm, service: mail
,I/GLSUser ( 2063): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> mail without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2063): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2063): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2063): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/NotificationService( 1032): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1032): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1032): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1032): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1032): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1398): onNotificationPosted
W/GLSActivity( 2063): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2063): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2063): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2063): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2063): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2063): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2063): 	at android.os.Binder.execTransact(Binder.java:446)
,D/SmartCoverUpdateMonitor( 1398): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1398): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1398): handleNotificationPosted(true)
D/QuickCircle( 1398): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1398): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1398): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1398): post do just update job
D/LgeQuickCoverNotificationData( 1398): showAll3
D/LgeQuickCoverNotificationData( 1398): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1398): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1398): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1398): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1398): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1398): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1398): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1398): isNotificationForCurrentUser : true
I/Gmail   ( 7068): notifyAccountChanged
I/Gmail   ( 7068): getAccountsCursor
,D/LgeQuickCoverOverlayWindow( 1398): [native noti] inex =  2
I/Gmail   ( 7068): notifyAccountChanged
D/LgeQuickCoverNotificationData( 1398): isNotificationForCurrentUser : true
,V/GLSActivity( 2063): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/Gmail   ( 7068): Sync complete for account: account:61035162
E/LgeQuickCoverOverlayWindow( 1398): updateNotificationData: count=3
D/QuickStatusbarLayout( 1398): Notification difference=198
D/QuickStatusbarLayout( 1398): child = android.widget.LinearLayout{1f81f9d8 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
I/Gmail   ( 7068): getAccountsCursor
D/SyncManager( 1032): failed sync operation thalitester@gmail.com u0 (com.google), gmail-ls, PERIODIC, currentRunTime 40191, reason: Periodic, SyncResult: stats [ numAuthExceptions: 1]
,D/SyncManager( 1032): not retrying sync operation because the error is a hard error: thalitester@gmail.com u0 (com.google), gmail-ls, PERIODIC, currentRunTime 168439, reason: Periodic
D/sensors_hal_Time( 1032): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1032): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1032): tsOffsetIs: Apps: 137504755057; DSPS: 4646555; Offset : -4309783030
V/GLSActivity( 2063): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager( 1032): Start proc com.google.android.apps.docs for service com.google.android.apps.docs/.sync.syncadapter.DocsSyncAdapterService: pid=7150 uid=10061 gids={50061, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager( 1032): Killing 6608:com.lge.appbox.client/u0a11 (adj 15): empty #17
,W/libprocessgroup( 1032): failed to open /acct/uid_10011/pid_6608/cgroup.procs: No such file or directory
,D/DocsApplication( 7150): Installing DEX configuration.
,D/DexInstaller( 7150): Dex configuration file eager_dex_configuration.xml not found. Skipping dex installation.
I/PackageInfoHelper( 7150): Provided clientMode=RELEASE, packageInfo=PackageInfo{22f98d56 com.google.android.apps.docs}
,D/TAG     ( 7150): onCreate()
D/CrossAppStateProvider( 7150): Initialized StateProvider with authority: com.google.android.apps.docs.statesyncer
,I/GAV2    ( 6629): Thread[GAThread,5,main]: No campaign data found.
,I/GLSUser ( 2063): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/reminders
,I/GLSUser ( 2063): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/reminders without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2063): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2063): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2063): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
E/ReminderSync( 2316): AuthError [T SyncAdapterThread-1:id=265:priority=5:group=main]
,D/SyncManager( 1032): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.gms.reminders, PERIODIC, currentRunTime 40287, reason: Periodic, SyncResult: stats [ numAuthExceptions: 1]
D/SyncManager( 1032): not retrying sync operation because the error is a hard error: thalitester@gmail.com u0 (com.google), com.google.android.gms.reminders, PERIODIC, currentRunTime 170702, reason: Periodic
,I/SyncAdapterService( 6806): Ignoring sync request for non-current account
,W/BaseAppContext( 2316): Using Auth Proxy for data requests.
,W/BaseAppContext( 2316): Using Auth Proxy for data requests.
W/BaseAppContext( 2316): Using Auth Proxy for data requests.
,W/BaseAppContext( 2316): Using Auth Proxy for data requests.
,W/BaseAppContext( 2316): Using Auth Proxy for data requests.
,I/art     ( 2063): Explicit concurrent mark sweep GC freed 14143(788KB) AllocSpace objects, 8(1152KB) LOS objects, 51% free, 30MB/62MB, paused 1.590ms total 59.103ms
,W/BaseAppContext( 2316): Using Auth Proxy for data requests.
,W/BaseAppContext( 2316): Using Auth Proxy for data requests.
,D/ChimeraCfgMgr( 2316): Loading module com.google.android.gms.games from APK com.google.android.gms
,I/GoogleHttpClient( 5218): Falling back to old http client 0 java.lang.NoSuchMethodException: <init> [class android.content.Context, class java.lang.String, boolean, boolean]
,I/art     ( 1032): Explicit concurrent mark sweep GC freed 24894(1056KB) AllocSpace objects, 6(480KB) LOS objects, 33% free, 44MB/66MB, paused 2.810ms total 123.091ms
,V/GLSActivity( 2063): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2063): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.music, service: sj
,I/GLSUser ( 2063): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> sj without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2063): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2063): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2063): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1032): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1032): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1032): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1032): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
,D/NotificationServiceEx( 1032): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1398): onNotificationPosted
W/GLSActivity( 2063): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2063): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2063): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2063): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2063): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2063): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2063): 	at android.os.Binder.execTransact(Binder.java:446)
D/SmartCoverUpdateMonitor( 1398): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1398): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1398): handleNotificationPosted(true)
D/QuickCircle( 1398): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1398): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1398): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1398): post do just update job
D/LgeQuickCoverNotificationData( 1398): showAll3
D/LgeQuickCoverNotificationData( 1398): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1398): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1398): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1398): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1398): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1398): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1398): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1398): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1398): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1398): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1398): updateNotificationData: count=3
W/MusicSyncAdapter( 5218): Sync failed due to an authentication issue.
,D/QuickStatusbarLayout( 1398): Notification difference=198
D/QuickStatusbarLayout( 1398): child = android.widget.LinearLayout{1f81f9d8 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
D/SyncManager( 1032): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.music.MusicContent, PERIODIC, currentRunTime 40360, reason: Periodic, SyncResult: stats [ numAuthExceptions: 1]
,D/SyncManager( 1032): not retrying sync operation because the error is a hard error: thalitester@gmail.com u0 (com.google), com.google.android.music.MusicContent, PERIODIC, currentRunTime 171280, reason: Periodic
E/VoldCmdListener(  280): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  280): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  280): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 5218): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
E/VoldCmdListener(  280): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  280): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  280): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 5218): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
E/VoldCmdListener(  280): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  280): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  280): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 5218): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
E/VoldCmdListener(  280): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  280): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  280): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 5218): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
I/ActivityManager( 1032): Start proc com.google.android.videos for service com.google.android.videos/.store.SyncService: pid=7194 uid=10103 gids={50103, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,W/ArtDownloadService( 5218): Setting cache size 0
,W/ArtDownloadService( 5218): Setting cache size 0
I/MusicLeanback( 5218): Conditions not met for autocaching.
I/MusicLeanback( 5218): Stop autocaching.
,I/GAV4    ( 6806): Thread[GAThread,5,main]: No campaign data found.
W/ResourcesManager( 7194): Asset path '/system/framework/com.google.widevine.software.drm.jar' does not exist or contains no resources.
I/ActivityManager( 1032): Start proc com.google.android.gms.wearable for service com.google.android.gms/.wearable.service.WearableService: pid=7215 uid=10005 gids={50005, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
,E/VoldCmdListener(  280): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  280): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/cache/
W/Vold    (  280): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 5218): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/cache
E/VoldCmdListener(  280): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  280): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/cache/
W/Vold    (  280): Returning OperationFailed - no handler for errno 0
,W/ResourcesManager( 7215): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 7215): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
W/ContextImpl( 5218): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/cache
E/WifiStateMachine( 1032):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=33.1, 0.0, 0.0  rx=28.9 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1470696350] gl rssi=-63 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
E/WifiStateMachine( 1032):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=33.1, 0.0, 0.0  rx=28.9 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-1470696349] gl rssi=-63 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
D/WifiNative-wlan0( 1032): doString: [SIGNAL_POLL]
,I/MultiDex( 7215): VM with version 2.1.0 has multidex support
I/MultiDex( 7215): install
I/MultiDex( 7215): VM has multidex support, MultiDex support library is disabled.
D/LgDataFeature( 7150): LgDataFeature() Constructor: none
D/LgDataFeature( 7194): LgDataFeature() Constructor: none
D/LgDataFeature( 7150): LgDataFeature() Constructor Done, null
D/LgDataFeature( 7194): LgDataFeature() Constructor Done, null
,V/JNIHelp ( 7215): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
W/ActivityThread( 7215): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 7215): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@b1f8eb5: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 7215): Installed default security provider GmsCore_OpenSSL
,D/GCM     ( 2063): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
D/AuthorizationBluetoothService( 2063): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
V/GmsCoreStatsServiceLauncher( 2316): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,D/WearableService( 7215): callingUid 10005, callindPid: 7215
W/GAV2    ( 7150): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
D/LocationInitializer( 2316): Restart initialization of location
,D/WearableClient( 5218): WearableClientImpl.onPostInitHandler: done
,E/MDM     ( 1790): [85] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
D/WearableClient( 5218): WearableClientImpl.onPostInitHandler: done
E/GmsUtils( 5218): Failed to connect to Google API client: ConnectionResult{statusCode=unknown status code 16, resolution=null}
D/PlayMovies( 7194): PersistentCache.cleanup:103 Cache is below limit, no need to shrink: [size=0, limit=5242880]
,D/PlayMovies( 7194): TransferService.onCreate:52 creating transfer service
,D/WifiService( 1032): acquireWifiLockLocked: WifiLock{SyncManager type=1 binder=android.os.BinderProxy@3e08b4e7}
,D/LocSvc_java( 1032): requestTime failed
D/LocSvc_java( 1032): Sending msg: 10 arg1:0 arg2:1
,W/AudioCapabilities( 7194): Unsupported mime audio/evrc
E/VoldCmdListener(  280): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  280): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.videos/files/Movies/
W/Vold    (  280): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7194): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.videos/files/Movies
,W/AudioCapabilities( 7194): Unsupported mime audio/qcelp
W/VideoCapabilities( 7194): Unrecognized profile 2130706433 for video/avc
W/AudioCapabilities( 7194): Unsupported mime audio/amr-wb-plus
,W/AudioCapabilities( 7194): Unsupported mime audio/qcelp
W/AudioCapabilities( 7194): Unsupported mime audio/evrc
W/VideoCapabilities( 7194): Unsupported mime video/x-ms-wmv
W/VideoCapabilities( 7194): Unsupported mime video/divx
W/VideoCapabilities( 7194): Unsupported mime video/divx311
W/VideoCapabilities( 7194): Unsupported mime video/divx4
W/VideoCapabilities( 7194): Unsupported mime video/mp4v-esdp
,D/libc-netbsd(  313): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  313): res_queryN name = ssl.gstatic.com, class = 1, type = 1
I/VideoCapabilities( 7194): Unsupported profile 4 for video/mp4v-es
W/AudioCapabilities( 7194): Unsupported mime audio/eac3
,W/AudioCapabilities( 7194): Unsupported mime audio/ac3
W/AudioCapabilities( 7194): Unsupported mime audio/g726
W/AudioCapabilities( 7194): Unsupported mime audio/wma-voice
W/AudioCapabilities( 7194): Unsupported mime audio/x-ms-wma
W/AudioCapabilities( 7194): Unsupported mime audio/adpcm
W/VideoCapabilities( 7194): Unsupported mime video/theora
W/VideoCapabilities( 7194): Unsupported mime video/mjpg
I/GLSUser ( 2063): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.videos, service: oauth2:https://www.googleapis.com/auth/android_video https://www.googleapis.com/auth/youtube https://www.googleapis.com/auth/pos
I/GLSUser ( 2063): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/android_video https://www.googleapis.com/auth/youtube https://www.googleapis.com/auth/pos without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2063): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2063): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2063): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/ResourcesManager( 2316): Asset path '/system/framework/com.google.widevine.software.drm.jar' does not exist or contains no resources.
V/NotificationService( 1032): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1032): pkg=com.google.android.gms canInterrupt=false intercept=true
,I/NotificationServiceEx( 1032): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1032): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1032): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1398): onNotificationPosted
D/SmartCoverUpdateMonitor( 1398): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1398): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1398): handleNotificationPosted(true)
D/QuickCircle( 1398): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1398): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1398): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1398): post do just update job
D/LgeQuickCoverNotificationData( 1398): showAll3
D/LgeQuickCoverNotificationData( 1398): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1398): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1398): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1398): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1398): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1398): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1398): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1398): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1398): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1398): isNotificationForCurrentUser : true
E/PlayMovies( 7194): GmsAccountManagerWrapper.blockingGetAuthTokenInternal:100 Cannot get user auth
E/PlayMovies( 7194): com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/PlayMovies( 7194): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/PlayMovies( 7194): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/PlayMovies( 7194): 	at com.google.android.videos.accounts.GmsAccountManagerWrapper.blockingGetAuthTokenInternal(GmsAccountManagerWrapper.java:85)
E/PlayMovies( 7194): 	at com.google.android.videos.accounts.AccountManagerWrapper.blockingGetAuthToken(AccountManagerWrapper.java:186)
E/PlayMovies( 7194): 	at com.google.android.videos.accounts.AccountManagerWrapper.blockingAuthenticate(AccountManagerWrapper.java:162)
E/PlayMovies( 7194): 	at com.google.android.videos.store.SyncService$SyncAdapter.onPerformSync(SyncService.java:225)
E/PlayMovies( 7194): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/LgeQuickCoverOverlayWindow( 1398): updateNotificationData: count=3
,I/ActivityManager( 1032): Killing 6198:com.lge.formmanager/u0a26 (adj 15): empty #17
D/SyncManager( 1032): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.videos.sync, PERIODIC, currentRunTime 40368, reason: Periodic, SyncResult: stats [ numAuthExceptions: 1]
D/SyncManager( 1032): not retrying sync operation because the error is a hard error: thalitester@gmail.com u0 (com.google), com.google.android.videos.sync, PERIODIC, currentRunTime 170667, reason: Periodic
D/QuickStatusbarLayout( 1398): Notification difference=198
D/QuickStatusbarLayout( 1398): child = android.widget.LinearLayout{1f81f9d8 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,D/libc-netbsd(  313): res_queryN name = ssl.gstatic.com succeed
,W/libprocessgroup( 1032): failed to open /acct/uid_10026/pid_6198/cgroup.procs: No such file or directory
,E/Auth.Api.Credentials( 2316): [CredentialSyncAdapter] Unknown sync event.
,V/GLSActivity( 2063): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2063): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.syncadapters.contacts, service: cp
,I/GLSUser ( 2063): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> cp without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2063): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2063): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2063): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1032): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
V/NotificationService( 1032): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1032): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1032): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1032): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,W/GLSActivity( 2063): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2063): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2063): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2063): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2063): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2063): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2063): 	at android.os.Binder.execTransact(Binder.java:446)
D/ContactsSyncAdapter( 2063): innerSync failed
D/ContactsSyncAdapter( 2063): com.google.wireless.gdata2.client.AuthenticationException: unable to get auth token android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
D/ContactsSyncAdapter( 2063): 	at com.google.android.syncadapters.contacts.AuthInfo.getAuthToken(AuthInfo.java:45)
D/ContactsSyncAdapter( 2063): 	at com.google.android.syncadapters.contacts.ContactsSyncAdapter.innerPerformSync(ContactsSyncAdapter.java:263)
D/ContactsSyncAdapter( 2063): 	at com.google.android.syncadapters.contacts.ContactsSyncAdapter.onPerformLoggedSync(ContactsSyncAdapter.java:168)
D/ContactsSyncAdapter( 2063): 	at com.google.android.common.LoggingThreadedSyncAdapter.onPerformSync(LoggingThreadedSyncAdapter.java:33)
D/ContactsSyncAdapter( 2063): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
D/ContactsSyncAdapter( 2063): Caused by: android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
D/ContactsSyncAdapter( 2063): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
D/ContactsSyncAdapter( 2063): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
D/ContactsSyncAdapter( 2063): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
D/ContactsSyncAdapter( 2063): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
D/ContactsSyncAdapter( 2063): 	at android.os.Binder.execTransact(Binder.java:446)
D/LgeQuickCoverNLService( 1398): onNotificationPosted
D/SmartCoverUpdateMonitor( 1398): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1398): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1398): handleNotificationPosted(true)
D/QuickCircle( 1398): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1398): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1398): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1398): post do just update job
D/LgeQuickCoverNotificationData( 1398): showAll3
,D/LgeQuickCoverNotificationData( 1398): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1398): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1398): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1398): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1398): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1398): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1398): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1398): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1398): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1398): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1398): updateNotificationData: count=3
D/SyncManager( 1032): failed sync operation thalitester@gmail.com u0 (com.google), com.android.contacts, LOCAL, currentRunTime 166709, reason: 10019, SyncResult: stats [ numAuthExceptions: 1]
,D/QuickStatusbarLayout( 1398): Notification difference=198
D/QuickStatusbarLayout( 1398): child = android.widget.LinearLayout{1f81f9d8 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
I/ActivityManager( 1032): Killing 6758:com.lge.drmservice/u0a62 (adj 15): empty #17
,W/libprocessgroup( 1032): failed to open /acct/uid_10062/pid_6758/cgroup.procs: No such file or directory
,V/GLSActivity( 2063): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2063): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.docs, service: oauth2: https://www.googleapis.com/auth/drive
,I/GLSUser ( 2063): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2: https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2063): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2063): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2063): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1032): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1032): pkg=com.google.android.gms canInterrupt=false intercept=true
,I/NotificationServiceEx( 1032): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1032): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1032): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
W/GLSActivity( 2063): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2063): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2063): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2063): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2063): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2063): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2063): 	at android.os.Binder.execTransact(Binder.java:446)
D/LgeQuickCoverNLService( 1398): onNotificationPosted
,D/SmartCoverUpdateMonitor( 1398): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1398): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1398): handleNotificationPosted(true)
D/QuickCircle( 1398): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1398): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1398): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1398): post do just update job
D/LgeQuickCoverNotificationData( 1398): showAll3
D/LgeQuickCoverNotificationData( 1398): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1398): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1398): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1398): showNotificationWithSetupData: display=false
W/PsynchoHelperImpl( 7150): Error fetching or saving configuration
W/PsynchoHelperImpl( 7150): java.io.IOException: android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
W/PsynchoHelperImpl( 7150): 	at Op.a(ApiaryPsynchoConfigurationAccessor.java:145)
W/PsynchoHelperImpl( 7150): 	at Op.a(ApiaryPsynchoConfigurationAccessor.java:215)
W/PsynchoHelperImpl( 7150): 	at OQ.a(PsynchoHelperImpl.java:60)
W/PsynchoHelperImpl( 7150): 	at agr.a(DriveSpecificSyncManager.java:27)
W/PsynchoHelperImpl( 7150): 	at agO.a(LegacySyncManager.java:678)
W/PsynchoHelperImpl( 7150): 	at agO.b(LegacySyncManager.java:582)
W/PsynchoHelperImpl( 7150): 	at agO.a(LegacySyncManager.java:467)
W/PsynchoHelperImpl( 7150): 	at agO.a(LegacySyncManager.java:97)
W/PsynchoHelperImpl( 7150): 	at agQ.run(LegacySyncManager.java:419)
W/PsynchoHelperImpl( 7150): 	at ami.a(NetworkUtilitiesImpl.java:31)
W/PsynchoHelperImpl( 7150): 	at agP.run(LegacySyncManager.java:416)
W/PsynchoHelperImpl( 7150): Caused by: android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
W/PsynchoHelperImpl( 7150): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
W/PsynchoHelperImpl( 7150): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
W/PsynchoHelperImpl( 7150): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
W/PsynchoHelperImpl( 7150): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
W/PsynchoHelperImpl( 7150): 	at android.os.Binder.execTransact(Binder.java:446)
D/LgeQuickCoverOverlayWindow( 1398): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1398): isNotificationForCurrentUser : true
,D/LgeQuickCoverOverlayWindow( 1398): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1398): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1398): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1398): isNotificationForCurrentUser : true
V/GLSActivity( 2063): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
E/LgeQuickCoverOverlayWindow( 1398): updateNotificationData: count=3
D/QuickStatusbarLayout( 1398): Notification difference=198
D/QuickStatusbarLayout( 1398): child = android.widget.LinearLayout{1f81f9d8 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,I/GLSUser ( 2063): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.docs, service: writely
I/GLSUser ( 2063): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> writely without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2063): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2063): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2063): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/NotificationService( 1032): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1032): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1032): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1032): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1032): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1398): onNotificationPosted
W/GLSActivity( 2063): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2063): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2063): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2063): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2063): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2063): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2063): 	at android.os.Binder.execTransact(Binder.java:446)
,E/HttpIssuerBase( 7150): Attempt to consume entity of HttpIssuer when no request is executing.
E/HttpIssuerBase( 7150): Attempt to close HttpIssuer when no request is executing.
E/HttpIssuerBase( 7150): java.io.IOException
E/HttpIssuerBase( 7150): 	at TG.b(HttpIssuerBase.java:188)
E/HttpIssuerBase( 7150): 	at Tj.b(DefaultAuthenticatedHttpIssuer.java:151)
E/HttpIssuerBase( 7150): 	at afE.a(AccountMetadataUpdater.java:227)
E/HttpIssuerBase( 7150): 	at afE.a(AccountMetadataUpdater.java:140)
E/HttpIssuerBase( 7150): 	at agO.a(LegacySyncManager.java:828)
E/HttpIssuerBase( 7150): 	at agO.b(LegacySyncManager.java:588)
E/HttpIssuerBase( 7150): 	at agO.a(LegacySyncManager.java:467)
E/HttpIssuerBase( 7150): 	at agO.a(LegacySyncManager.java:97)
E/HttpIssuerBase( 7150): 	at agQ.run(LegacySyncManager.java:419)
E/HttpIssuerBase( 7150): 	at ami.a(NetworkUtilitiesImpl.java:31)
E/HttpIssuerBase( 7150): 	at agP.run(LegacySyncManager.java:416)
D/SmartCoverUpdateMonitor( 1398): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1398): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1398): handleNotificationPosted(true)
D/QuickCircle( 1398): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1398): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1398): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1398): post do just update job
D/LgeQuickCoverNotificationData( 1398): showAll3
D/LgeQuickCoverNotificationData( 1398): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1398): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1398): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1398): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1398): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1398): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1398): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1398): isNotificationForCurrentUser : true
E/SyncManager( 7150): AuthenticatorException
E/SyncManager( 7150): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/SyncManager( 7150): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/SyncManager( 7150): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/SyncManager( 7150): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/SyncManager( 7150): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/SyncManager( 7150): 	at android.os.Binder.execTransact(Binder.java:446)
D/LgeQuickCoverOverlayWindow( 1398): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1398): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1398): updateNotificationData: count=3
W/GAV2    ( 7150): SyncManager-thalitester@gmail.com: dispatch call queued.  Need to call GAServiceManager.getInstance().initialize().
,D/WifiService( 1032): releaseWifiLockLocked: WifiLock{SyncManager type=1 binder=android.os.BinderProxy@3e08b4e7}
D/QuickStatusbarLayout( 1398): Notification difference=198
D/QuickStatusbarLayout( 1398): child = android.widget.LinearLayout{1f81f9d8 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
D/SyncManager( 1032): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.docs, PERIODIC, currentRunTime 40297, reason: Periodic, SyncResult: stats [ numAuthExceptions: 1]
,D/SyncManager( 1032): not retrying sync operation because the error is a hard error: thalitester@gmail.com u0 (com.google), com.google.android.apps.docs, PERIODIC, currentRunTime 172495, reason: Periodic
I/ActivityManager( 1032): Killing 6693:com.android.chrome/u0a57 (adj 15): empty #17
I/art     ( 1032): Explicit concurrent mark sweep GC freed 29091(1413KB) AllocSpace objects, 11(816KB) LOS objects, 33% free, 44MB/66MB, paused 2.167ms total 138.516ms
,W/libprocessgroup( 1032): failed to open /acct/uid_10057/pid_6693/cgroup.procs: No such file or directory
,D/UEI.SmartControl( 7006): Internal timer expired: 1
D/UEI.SmartControl( 7006): unbind internal service
,D/UEI.SmartControl( 7006): Service.onUnbind: IControl
D/serial_port( 7006): close(fd = 25)
D/UEI.SmartControl( 7006): Service.onDestroy
D/UEI.SmartControl( 7006): Lock is in USE false
D/UEI.SmartControl( 7006): unbind internal service
W/System.err( 7006): java.lang.IllegalArgumentException: Service not registered: com.uei.control.g@39b4ae5c
W/System.err( 7006): 	at android.app.LoadedApk.forgetServiceDispatcher(LoadedApk.java:1119)
W/System.err( 7006): 	at android.app.ContextImpl.unbindService(ContextImpl.java:1873)
W/System.err( 7006): 	at android.content.ContextWrapper.unbindService(ContextWrapper.java:550)
W/System.err( 7006): 	at com.uei.control.Service.c(Unknown Source)
W/System.err( 7006): 	at com.uei.control.Service.onDestroy(Unknown Source)
W/System.err( 7006): 	at android.app.ActivityThread.handleStopService(ActivityThread.java:2901)
W/System.err( 7006): 	at android.app.ActivityThread.access$2200(ActivityThread.java:148)
W/System.err( 7006): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1386)
W/System.err( 7006): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 7006): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 7006): 	at android.app.ActivityThread.main(ActivityThread.java:5274)
W/System.err( 7006): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 7006): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 7006): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
W/System.err( 7006): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
E/UEI.SmartControl( 7006): java.lang.IllegalArgumentException: Service not registered: com.uei.control.g@39b4ae5c
,I/UEI.SmartControl( 7006): Serial port is closed.
I/UEI.SmartControl( 7006): Serial port is closed.
I/UEI.SmartControl( 7006): Serial port is closed.
D/UEI.SmartControl( 7006): Blaster closed
D/UEI.SmartControl( 7006): Shut down QS...
D/UEI.SmartControl( 7006): Stopping QS lib
D/UEI.SmartControl( 7006): QS lib stop result = true
D/UEI.SmartControl( 7006): Stopped QS lib
D/UEI.SmartControl( 7006): Stopped file observer...
D/UEI.SmartControl( 7006): QS shutdown complete
I/GAV2    ( 7068): Thread[GAThread,5,main]: No campaign data found.
,E/WifiStateMachine( 1032):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=20.0, 0.0, 0.0  rx=16.9 bcn=0 [on:0 tx:0 rx:0 period:3015] from screen [on:0 period:-1470693324] gl rssi=-63 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,E/WifiStateMachine( 1032):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=20.0, 0.0, 0.0  rx=16.9 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-1470693314] gl rssi=-63 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
D/WifiNative-wlan0( 1032): doString: [SIGNAL_POLL]
,I/ActivityManager( 1032): Killing 6650:com.android.gallery3d/u0a27 (adj 15): empty #17
W/libprocessgroup( 1032): failed to open /acct/uid_10027/pid_6650/cgroup.procs: No such file or directory
,I/GAV2    ( 7150): Thread[GAThread,5,main]: No campaign data found.
,I/ActivityManager( 1032): Killing 6902:com.android.providers.calendar/u0a14 (adj 15): empty #17
,W/libprocessgroup( 1032): failed to open /acct/uid_10014/pid_6902/cgroup.procs: No such file or directory
,E/WifiStateMachine( 1032):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=19.5, 0.0, 0.0  rx=16.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1470690295] gl rssi=-63 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,E/WifiStateMachine( 1032):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=19.5, 0.0, 0.0  rx=16.0 bcn=0 [on:0 tx:0 rx:0 period:12] from screen [on:0 period:-1470690283] gl rssi=-63 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,D/WifiNative-wlan0( 1032): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1032):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=10.3, 0.0, 0.0  rx=8.5 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1470687261] gl rssi=-63 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,E/WifiStateMachine( 1032):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=10.3, 0.0, 0.0  rx=8.5 bcn=0 [on:0 tx:0 rx:0 period:12] from screen [on:0 period:-1470687249] gl rssi=-63 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
D/WifiNative-wlan0( 1032): doString: [SIGNAL_POLL]
I/[SystemUI]QPairHandler( 1447): onReceive = android.intent.action.PACKAGE_CHANGED
,D/SplitUIService( 1842): replaced split : contains_com.google.android.talk / true
I/InputReader( 1032): Reconfiguring input devices.  changes=0x00000010
,I/[LGHome]EVENT( 2005): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.talk flg=0x4000010 (has extras) }
,I/ActivityManager( 1032): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.manager.PreloadListManagerHelper: pid=7318 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
I/InputReader( 1032): Reconfiguring input devices.  changes=0x00000010
,I/[LGHome]EVENT( 2005): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.videos flg=0x4000010 (has extras) }
D/SplitUIManager( 1842): split_name #11 / not available #0
I/SplitUIService( 1842): split app #11
I/[SystemUI]QSlideListController( 1447): onReceive = android.intent.action.PACKAGE_CHANGED
W/ResourcesManager( 2005): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,D/administrator( 1032): Handling package changes for user 0
,I/[SystemUI]AppWidgetPanel(QRemoteWidgetPanel)( 1447): onReceive = android.intent.action.PACKAGE_CHANGED, packageName : com.google.android.talk
I/[SystemUI]QPairHandler( 1447): onReceive = android.intent.action.PACKAGE_CHANGED
I/[SystemUI]QSlideListController( 1447): onReceive = android.intent.action.PACKAGE_CHANGED
I/[SystemUI]AppWidgetPanel(QRemoteWidgetPanel)( 1447): onReceive = android.intent.action.PACKAGE_CHANGED, packageName : com.google.android.videos
,I/[LGHome]Launcher( 2005): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/[LGHome]Launcher( 2005): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,I/AppUp4:AppBoxCP( 7318): onCreate
W/AppUp4:DB( 7318):  [AppBoxDatabaseHelper] construct
,I/AppUp4:DB( 7318):  setFingerPrint start
,I/AppUp4:DB( 7318):  newfinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys SDK version = 21
I/AppUp4:DB( 7318):  beforefinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys
I/AppUp4:DB( 7318):  SDK version = 21
I/AppUp4:DB( 7318):  beforefinger == newfinger no write in DB
,D/AppUp4:AppBoxApplication( 7318): AppBoxApplication onCreate()
I/AppUp4:CustModeStarterReceiver( 7318): onReceive
I/NotificationService( 1032): action=android.intent.action.PACKAGE_CHANGED queryReplace=false
D/BackupManagerService( 1032): Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.talk flg=0x4000010 (has extras) }
,D/LgDataFeature( 7318): LgDataFeature() Constructor: none
D/LgDataFeature( 7318): LgDataFeature() Constructor Done, null
D/AppUp4:CustFacade( 7318): Context : android.app.ReceiverRestrictedContext@283e3dad
D/AppUp4:CustFacade( 7318): isCustomizationCompleted : false
D/AppUp4:CustFacade( 7318): isPhone : true
D/AppUp4:CustModeStarterReceiver( 7318): begin check event
I/AppUp4:CustModeStarterReceiver( 7318): Event For Nothing, skip.
W/ResourcesManager( 1032): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,W/ResourcesManager( 1032): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/ActivityManager( 1032): Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=7346 uid=10019 gids={50019, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
I/ActivityManager( 1032): Killing 6860:com.google.android.syncadapters.calendar/u0a69 (adj 15): empty #17
W/ResourceType( 1032): Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
W/libprocessgroup( 1032): failed to open /acct/uid_10069/pid_6860/cgroup.procs: No such file or directory
,D/administrator( 1032): Handling package changes for user 0
I/NotificationService( 1032): action=android.intent.action.PACKAGE_CHANGED queryReplace=false
D/BackupManagerService( 1032): Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.videos flg=0x4000010 (has extras) }
,I/[LGHome]EVENT( 2005): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
,W/ResourcesManager( 7346): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 7346): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,W/ResourcesManager( 7346): Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
W/ResourcesManager( 7346): Asset path '/system/framework/lghiddenlibs.jar' does not exist or contains no resources.
W/ResourcesManager( 7346): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
W/ResourceType( 1032): Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
,I/[LGHome]EVENT( 2005): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
I/SystemConfig( 7346): BUILD Country: EU
,I/SystemConfig( 7346): BUILD Operator: OPEN
,I/ActivityManager( 1032): Killing 6674:com.lge.email/u0a23 (adj 15): empty #17
,W/libprocessgroup( 1032): failed to open /acct/uid_10023/pid_6674/cgroup.procs: No such file or directory
,I/SystemConfig( 7346): pm.hasSystemFeature(com.lge.ims.rcs) = false
I/SystemConfig( 7346): existFile = false
I/SystemConfig( 7346): canReadFile = false
I/SystemConfig( 7346): systemFeature RCS result false
D/SystemConfig( 7346): refreshRcsSupport() :false
I/ActivityManager( 1032): Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=7371 uid=10027 gids={50027, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
,I/art     (  347): Explicit concurrent mark sweep GC freed 707(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 479us total 24.555ms
,I/art     (  347): Explicit concurrent mark sweep GC freed 7(240B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 446us total 21.092ms
,I/art     (  347): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 449us total 20.597ms
,W/ResourcesManager( 7371): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 7371): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 7371): Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
W/ResourcesManager( 7371): Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
I/AppConfig( 7371): Total System Memory = 2995761152
,D/SystemHelper( 7371): region [EU], country [EU], operator [OPEN], sub-operator []
,I/ActivityManager( 1032): Killing 5168:com.wsandroid.suite.lge/1000 (adj 15): empty #17
,W/libprocessgroup( 1032): failed to open /acct/uid_1000/pid_5168/cgroup.procs: No such file or directory
,I/UpdateIcingCorporaServi( 4214): Updating corpora: APPS=com.google.android.talk, CONTACTS=MAYBE
,I/ActivityManager( 1032): Start proc com.lge.lockscreensettings for broadcast com.lge.lockscreensettings/.PackageIntentReceiver: pid=7397 uid=10080 gids={50080, 9997, 1028, 1015} abi=armeabi-v7a
V/SIM_STK ( 1032): Menu title from STK is T-Mobile
W/ResourcesManager( 4214): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/UpdateIcingCorporaServi( 4214): UpdateCorporaTask done [took 78 ms] updated apps [took 77 ms] 
,I/LockScreenSettings( 7397): Wallpaper base directory = /data/data/com.lge.lockscreensettings/files/
,D/LockScreenSettings( 7397): Quick window widget present in DB = com.lge.clock.quickcover.QuickCoverSettingActivity  true
,D/LockScreenSettings( 7397): Quick window widget present in DB = com.lge.camera.app.QuickWindowCameraActivity  true
D/LockScreenSettings( 7397): Quick window widget present in DB = com.android.contacts.activities.QuickCircleActivity  true
D/LockScreenSettings( 7397): Quick window widget present in DB = com.android.mms.quickcover.QuickCoverActivity  true
D/LockScreenSettings( 7397): Quick window widget present in DB = com.lge.music.MusicQuickCircle  true
,D/LockScreenSettings( 7397): Quick window widget present in DB = com.lge.lifetracker.QuickCover  true
,I/ActivityManager( 1032): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=7415 uid=10044 gids={50044, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager( 1032): Killing 6963:com.qualcomm.timeservice/1000 (adj 15): empty #17
,W/libprocessgroup( 1032): failed to open /acct/uid_1000/pid_6963/cgroup.procs: No such file or directory
,D/Finsky  ( 7415): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,D/LgDataFeature( 7415): LgDataFeature() Constructor: none
,D/LgDataFeature( 7415): LgDataFeature() Constructor Done, null
,D/Finsky  ( 7415): [1] DailyHygiene.goMakeHygieneIfDirty: Dirty, need more hygiene.
,E/WifiStateMachine( 1032):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=5.6, 0.0, 0.0  rx=4.7 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1470684226] gl rssi=-63 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
E/WifiStateMachine( 1032):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=5.6, 0.0, 0.0  rx=4.7 bcn=0 [on:0 tx:0 rx:0 period:2] from screen [on:0 period:-1470684224] gl rssi=-63 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
D/WifiNative-wlan0( 1032): doString: [SIGNAL_POLL]
,I/ActivityManager( 1032): Start proc com.google.android.gms:car for service com.google.android.gms/.car.CarService: pid=7454 uid=10005 gids={50005, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
,W/Settings( 7415): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
W/Settings( 7415): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/ResourcesManager( 7454): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 7454): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/DownloadManager( 3320): starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 3320): created cursor android.database.sqlite.SQLiteCursor@b8a4ecb on behalf of 7415
D/Finsky  ( 7415): [1] 2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
I/MultiDex( 7454): VM with version 2.1.0 has multidex support
I/MultiDex( 7454): install
I/MultiDex( 7454): VM has multidex support, MultiDex support library is disabled.
D/Finsky  ( 7415): [1] 2.run: Finished loading 1 libraries.
,D/Finsky  ( 7415): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,V/JNIHelp ( 7454): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,D/PackageBroadcastService( 2316): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.talk
,I/AppUp4:CustModeStarterReceiver( 7318): onReceive
D/AppUp4:CustFacade( 7318): Context : android.app.ReceiverRestrictedContext@283e3dad
D/AppUp4:CustFacade( 7318): isCustomizationCompleted : false
D/AppUp4:CustFacade( 7318): isPhone : true
D/AppUp4:CustModeStarterReceiver( 7318): begin check event
I/AppUp4:CustModeStarterReceiver( 7318): Event For Nothing, skip.
D/Finsky  ( 7415): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,I/PeopleContactsSync( 2316): CP2 sync disabled
,I/ActivityManager( 1032): Killing 7006:com.uei.lg.quicksetsdk.maxq616/1000 (adj 15): empty #17
,W/ActivityThread( 7454): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 7454): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@b1f8eb5: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 7454): Installed default security provider GmsCore_OpenSSL
W/libprocessgroup( 1032): failed to open /acct/uid_1000/pid_7006/cgroup.procs: No such file or directory
,I/UpdateIcingCorporaServi( 4214): Updating corpora: APPS=com.google.android.videos, CONTACTS=MAYBE
,D/LockScreenSettings( 7397): Quick window widget present in DB = com.lge.clock.quickcover.QuickCoverSettingActivity  true
D/LockScreenSettings( 7397): Quick window widget present in DB = com.lge.camera.app.QuickWindowCameraActivity  true
D/LockScreenSettings( 7397): Quick window widget present in DB = com.android.contacts.activities.QuickCircleActivity  true
D/LockScreenSettings( 7397): Quick window widget present in DB = com.android.mms.quickcover.QuickCoverActivity  true
D/LockScreenSettings( 7397): Quick window widget present in DB = com.lge.music.MusicQuickCircle  true
D/LockScreenSettings( 7397): Quick window widget present in DB = com.lge.lifetracker.QuickCover  true
D/PackageBroadcastService( 2316): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.videos
D/GCM     ( 2063): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,D/AuthorizationBluetoothService( 2063): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
V/SIM_STK ( 1032): Menu title from STK is T-Mobile
,I/PeopleContactsSync( 2316): CP2 sync disabled
V/GmsCoreStatsServiceLauncher( 2316): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
D/WearableService( 7215): callingUid 10005, callindPid: 7215
,E/MDM     ( 1790): [86] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,D/LocationInitializer( 2316): Restart initialization of location
,I/UpdateIcingCorporaServi( 4214): UpdateCorporaTask done [took 121 ms] updated apps [took 121 ms] 
,I/art     ( 2063): Explicit concurrent mark sweep GC freed 17406(1024KB) AllocSpace objects, 14(2016KB) LOS objects, 50% free, 30MB/62MB, paused 1.554ms total 54.253ms
,V/Finsky  ( 7415): [1] GearheadStateMonitor.onReady: sIsProjecting:false
,V/AlarmManager( 1032): RTC_WAKEUP set : Alarm{257947d type 0 when 1454523230007 com.android.vending} when 1454523230007
,D/Finsky  ( 7415): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
V/GLSActivity( 2063): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2063): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 2063): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2063): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2063): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2063): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/Finsky  ( 7415): [1] 1.onErrorResponse: Unable to preload experiments: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,V/GLSActivity( 2063): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/GLSUser ( 2063): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 2063): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2063): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2063): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2063): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/GLSActivity( 2063): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2063): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 2063): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2063): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2063): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2063): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/Finsky  ( 7415): [1] LibraryUpdateListener.onErrorResponse: Library replication failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,V/SIM_STK ( 1032): Menu title from STK is T-Mobile
,V/GLSActivity( 2063): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2063): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 2063): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2063): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2063): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2063): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/Finsky  ( 7415): [1] 2.onErrorResponse: Update check failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,D/Finsky  ( 7415): [1] DailyHygiene.logDeviceFeaturesAndContinue: Logging device features
D/Finsky  ( 7415): [1] DailyHygiene.flushEventLogsAndContinue: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 7415): [1] DailyHygiene.reschedule: Scheduling new run in 10 minutes (failures=1)
,D/DeviceConnectionService( 1790): client connected with version: 7571000
,E/WifiStateMachine( 1032):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=2.8, 0.0, 0.0  rx=2.4 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1470681204] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1032):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=2.8, 0.0, 0.0  rx=2.4 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1470681201] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1032): doString: [SIGNAL_POLL]
,I/ActivityManager( 1032): Killing 6986:com.android.calendar/u0a13 (adj 15): empty #17
,W/libprocessgroup( 1032): failed to open /acct/uid_10013/pid_6986/cgroup.procs: No such file or directory
,E/WifiStateMachine( 1032):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=1.9, 0.0, 0.0  rx=1.7 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1470678180] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1032):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=1.9, 0.0, 0.0  rx=1.7 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-1470678170] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1032): doString: [SIGNAL_POLL]
D/sensors_hal_Time( 1032): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1032): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1032): tsOffsetIs: Apps: 157506471663; DSPS: 5301971; Offset : -4309775851
,E/WifiStateMachine( 1032):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-62 f=2412 sc=60 link=72 tx=1.0, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1470675149] gl rssi=-62 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1032):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-62 f=2412 sc=60 link=72 tx=1.0, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:9] from screen [on:0 period:-1470675140] gl rssi=-62 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1032): doString: [SIGNAL_POLL]
I/[SystemUI]TimeTickManager( 1447): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1447): called onTimeUpdated()
,I/[SystemUI]KeyguardIndicationController( 1447): called onTimeUpdated()
I/[SystemUI]Clock( 1447): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1447): called onTimeUpdated()
I/[SystemUI]DateView( 1447): called onTimeUpdated()
I/[SystemUI]DateView( 1447): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1447): handleTimeUpdate
,D/PowerManagerServiceEx( 1032): acquireWakeLockInternal: lock=58637760, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1032
,V/AlarmManager( 1032): ELAPSED_WAKEUP set : Alarm{10c31164 type 2 when 162675 android} when 162675
D/[Concierge]Service( 2591): onStartCommand(). Type : 9
,D/PowerManagerServiceEx( 1032): releaseWakeLockInternal: lock=58637760 [*alarm*], flags=0x0
,E/WifiStateMachine( 1032):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-62 f=2412 sc=60 link=72 tx=1.0, 0.0, 0.0  rx=0.9 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1470672119] gl rssi=-62 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1032):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-62 f=2412 sc=60 link=72 tx=1.0, 0.0, 0.0  rx=0.9 bcn=0 [on:0 tx:0 rx:0 period:9] from screen [on:0 period:-1470672110] gl rssi=-62 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1032): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1032):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=1.0, 0.0, 0.0  rx=1.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1470669088] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1032):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=1.0, 0.0, 0.0  rx=1.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1470669085] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1032): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1032):  ConnectedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 1 0
,E/WifiStateMachine( 1032):  L2ConnectedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 1 0
,E/WifiStateMachine( 1032):  ConnectModeState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 1 0
E/WifiStateMachine( 1032):  DriverStartedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 1 0
E/WifiStateMachine( 1032):  SupplicantStartedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 1 0
E/WifiStateMachine( 1032):  DefaultState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 1 0
E/WifiStateMachine( 1032):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.5 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1470666058] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1032):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.5 bcn=0 [on:0 tx:0 rx:0 period:2] from screen [on:0 period:-1470666056] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1032): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1032):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1470663038] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1032):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1470663035] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1032): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1032):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1470660009] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1032):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:4] from screen [on:0 period:-1470660005] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1032): doString: [SIGNAL_POLL]
,D/sensors_hal_Time( 1032): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1032): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1032): tsOffsetIs: Apps: 177508627593; DSPS: 5957401; Offset : -4309756178
,E/WifiStateMachine( 1032):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1470656981] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1032):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-1470656971] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1032): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1032):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1470653951] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1032):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:11] from screen [on:0 period:-1470653940] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1032): doString: [SIGNAL_POLL]
V/AlarmManager( 1032): RTC_WAKEUP set : Alarm{5c03b01 type 0 when 1454523250367 com.android.vending} when 1454523250367
,V/SIM_STK ( 1032): Menu title from STK is T-Mobile
,V/GLSActivity( 2063): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2063): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 2063): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2063): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2063): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2063): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/WifiStateMachine( 1032):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1470650918] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1032):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-1470650917] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1032): doString: [SIGNAL_POLL]
,I/art     ( 1032): Explicit concurrent mark sweep GC freed 48526(2MB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 44MB/66MB, paused 2.012ms total 116.578ms
,D/Finsky  ( 7415): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 7415): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 7415): [1] 5.onFinished: Scheduling replication attempt 3.
E/WifiStateMachine( 1032):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1470647902] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1032):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:13] from screen [on:0 period:-1470647889] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1032): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1032):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1470644867] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1032):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1470644864] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1032): doString: [SIGNAL_POLL]
,V/AlarmManager( 1032): ELAPSED_WAKEUP set : Alarm{172cb3fb type 2 when 192796 android} when 192796
,I/BooksSync( 6629): Starting books sync
,D/BooksSync( 6629): started syncMyEbooks
,V/GLSActivity( 2063): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2063): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.syncadapters.contacts, service: cp
,I/GLSUser ( 2063): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> cp without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2063): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2063): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2063): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1032): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1032): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1032): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1032): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1032): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
W/GLSActivity( 2063): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2063): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2063): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2063): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2063): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2063): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2063): 	at android.os.Binder.execTransact(Binder.java:446)
,D/ContactsSyncAdapter( 2063): innerSync failed
D/ContactsSyncAdapter( 2063): com.google.wireless.gdata2.client.AuthenticationException: unable to get auth token android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
D/ContactsSyncAdapter( 2063): 	at com.google.android.syncadapters.contacts.AuthInfo.getAuthToken(AuthInfo.java:45)
D/ContactsSyncAdapter( 2063): 	at com.google.android.syncadapters.contacts.ContactsSyncAdapter.innerPerformSync(ContactsSyncAdapter.java:263)
D/ContactsSyncAdapter( 2063): 	at com.google.android.syncadapters.contacts.ContactsSyncAdapter.onPerformLoggedSync(ContactsSyncAdapter.java:168)
D/ContactsSyncAdapter( 2063): 	at com.google.android.common.LoggingThreadedSyncAdapter.onPerformSync(LoggingThreadedSyncAdapter.java:33)
D/ContactsSyncAdapter( 2063): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
D/ContactsSyncAdapter( 2063): Caused by: android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
D/ContactsSyncAdapter( 2063): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
D/ContactsSyncAdapter( 2063): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
D/ContactsSyncAdapter( 2063): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
D/ContactsSyncAdapter( 2063): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
D/ContactsSyncAdapter( 2063): 	at android.os.Binder.execTransact(Binder.java:446)
,W/ResourcesManager( 1398): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 1398): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
D/LgeQuickCoverNLService( 1398): onNotificationPosted
D/SmartCoverUpdateMonitor( 1398): received broadcast com.lge.intent.action.NLDataPosted
,E/SmartCoverUpdateMonitor( 1398): MSG_NOTIFICATION_POSTED
,D/SmartCoverUpdateMonitor( 1398): handleNotificationPosted(true)
D/QuickCircle( 1398): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1398): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1398): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1398): post do just update job
D/LgeQuickCoverNotificationData( 1398): showAll3
D/LgeQuickCoverNotificationData( 1398): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1398): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1398): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1398): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1398): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1398): isNotificationForCurrentUser : true
W/ResourcesManager( 1398): Asset path '/system/framework/com.lge.systemui.jar' does not exist or contains no resources.
W/ResourcesManager( 1398): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
D/LgeQuickCoverOverlayWindow( 1398): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1398): isNotificationForCurrentUser : true
,D/LgeQuickCoverOverlayWindow( 1398): [native noti] inex =  2
D/SyncManager( 1032): failed sync operation thalitester@gmail.com u0 (com.google), com.android.contacts, LOCAL, currentRunTime 166709, reason: 10019, SyncResult: stats [ numAuthExceptions: 1]
D/LgeQuickCoverNotificationData( 1398): isNotificationForCurrentUser : true
D/SyncManager( 1032): not retrying sync operation because the error is a hard error: thalitester@gmail.com u0 (com.google), com.android.contacts, LOCAL, currentRunTime 258858, reason: 10019
I/GLSUser ( 2063): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2063): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2063): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2063): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,E/LgeQuickCoverOverlayWindow( 1398): updateNotificationData: count=3
,D/QuickStatusbarLayout( 1398): Notification difference=198
D/QuickStatusbarLayout( 1398): child = android.widget.LinearLayout{1f81f9d8 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
V/GLSActivity( 2063): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/NotificationService( 1032): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
V/NotificationService( 1032): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1032): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1032): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1032): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
W/GLSActivity( 2063): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2063): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2063): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2063): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2063): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2063): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2063): 	at android.os.Binder.execTransact(Binder.java:446)
E/BooksAccountManager( 6629): Authentication error
E/BooksAccountManager( 6629): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6629): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6629): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6629): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6629): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6629): 	at android.os.Binder.execTransact(Binder.java:446)
,E/HttpHelper( 6629): null auth token
D/LgeQuickCoverNLService( 1398): onNotificationPosted
D/SmartCoverUpdateMonitor( 1398): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1398): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1398): handleNotificationPosted(true)
D/QuickCircle( 1398): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1398): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1398): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1398): post do just update job
D/LgeQuickCoverNotificationData( 1398): showAll3
D/LgeQuickCoverNotificationData( 1398): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1398): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1398): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1398): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1398): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1398): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1398): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1398): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1398): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1398): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1398): updateNotificationData: count=3
D/QuickStatusbarLayout( 1398): Notification difference=198
D/QuickStatusbarLayout( 1398): child = android.widget.LinearLayout{1f81f9d8 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,W/ApiaryClient( 6629): Error response from books API: {
W/ApiaryClient( 6629):  "error": {
W/ApiaryClient( 6629):   "errors": [
W/ApiaryClient( 6629):    {
W/ApiaryClient( 6629):     "domain": "global",
W/ApiaryClient( 6629):     "reason": "required",
W/ApiaryClient( 6629):     "message": "Login Required",
W/ApiaryClient( 6629):     "locationType": "header",
W/ApiaryClient( 6629):     "location": "Authorization"
W/ApiaryClient( 6629):    }
W/ApiaryClient( 6629):   ],
W/ApiaryClient( 6629):   "code": 401,
W/ApiaryClient( 6629):   "message": "Login Required"
W/ApiaryClient( 6629):  }
W/ApiaryClient( 6629): }
,W/ApiaryClient( 6629): errCount = 1: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6629): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-7026376509154276594&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6629): Headers:
W/ApiaryClient( 6629): accept-encoding: [gzip]
W/ApiaryClient( 6629): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6629): gdata-version: 2
,E/WifiStateMachine( 1032):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3005] from screen [on:0 period:-1470641837] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1032):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:4] from screen [on:0 period:-1470641833] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1032): doString: [SIGNAL_POLL]
V/GLSActivity( 2063): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2063): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 2063): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2063): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2063): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2063): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1032): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1032): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1032): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1032): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1032): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1398): onNotificationPosted
D/SmartCoverUpdateMonitor( 1398): received broadcast com.lge.intent.action.NLDataPosted
,E/SmartCoverUpdateMonitor( 1398): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1398): handleNotificationPosted(true)
D/QuickCircle( 1398): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1398): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1398): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1398): post do just update job
D/LgeQuickCoverNotificationData( 1398): showAll3
D/LgeQuickCoverNotificationData( 1398): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1398): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1398): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1398): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1398): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1398): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1398): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1398): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1398): [native noti] inex =  2
,D/LgeQuickCoverNotificationData( 1398): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1398): updateNotificationData: count=3
D/QuickStatusbarLayout( 1398): Notification difference=198
D/QuickStatusbarLayout( 1398): child = android.widget.LinearLayout{1f81f9d8 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,W/GLSActivity( 2063): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2063): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2063): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2063): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2063): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2063): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2063): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 6629): Authentication error
E/BooksAccountManager( 6629): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6629): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6629): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6629): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6629): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6629): 	at android.os.Binder.execTransact(Binder.java:446)
,E/HttpHelper( 6629): null auth token
W/ApiaryClient( 6629): Error response from books API: {
W/ApiaryClient( 6629):  "error": {
W/ApiaryClient( 6629):   "errors": [
W/ApiaryClient( 6629):    {
W/ApiaryClient( 6629):     "domain": "global",
W/ApiaryClient( 6629):     "reason": "required",
W/ApiaryClient( 6629):     "message": "Login Required",
W/ApiaryClient( 6629):     "locationType": "header",
W/ApiaryClient( 6629):     "location": "Authorization"
W/ApiaryClient( 6629):    }
W/ApiaryClient( 6629):   ],
W/ApiaryClient( 6629):   "code": 401,
W/ApiaryClient( 6629):   "message": "Login Required"
W/ApiaryClient( 6629):  }
W/ApiaryClient( 6629): }
,W/ApiaryClient( 6629): errCount = 2: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6629): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-7026376509154276594&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6629): Headers:
W/ApiaryClient( 6629): accept-encoding: [gzip]
W/ApiaryClient( 6629): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6629): gdata-version: 2
V/GLSActivity( 2063): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2063): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2063): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2063): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2063): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2063): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1032): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1032): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1032): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1032): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1032): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1398): onNotificationPosted
,D/SmartCoverUpdateMonitor( 1398): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1398): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1398): handleNotificationPosted(true)
D/QuickCircle( 1398): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1398): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1398): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1398): post do just update job
D/LgeQuickCoverNotificationData( 1398): showAll3
D/LgeQuickCoverNotificationData( 1398): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1398): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1398): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1398): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1398): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1398): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1398): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1398): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1398): [native noti] inex =  2
,D/LgeQuickCoverNotificationData( 1398): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1398): updateNotificationData: count=3
W/GLSActivity( 2063): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2063): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2063): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2063): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2063): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2063): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2063): 	at android.os.Binder.execTransact(Binder.java:446)
E/BooksAccountManager( 6629): Authentication error
E/BooksAccountManager( 6629): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6629): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6629): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6629): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6629): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6629): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6629): null auth token
,D/QuickStatusbarLayout( 1398): Notification difference=198
D/QuickStatusbarLayout( 1398): child = android.widget.LinearLayout{1f81f9d8 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
W/ApiaryClient( 6629): Error response from books API: {
W/ApiaryClient( 6629):  "error": {
W/ApiaryClient( 6629):   "errors": [
W/ApiaryClient( 6629):    {
W/ApiaryClient( 6629):     "domain": "global",
W/ApiaryClient( 6629):     "reason": "required",
W/ApiaryClient( 6629):     "message": "Login Required",
W/ApiaryClient( 6629):     "locationType": "header",
W/ApiaryClient( 6629):     "location": "Authorization"
W/ApiaryClient( 6629):    }
W/ApiaryClient( 6629):   ],
W/ApiaryClient( 6629):   "code": 401,
W/ApiaryClient( 6629):   "message": "Login Required"
W/ApiaryClient( 6629):  }
W/ApiaryClient( 6629): }
,W/ApiaryClient( 6629): errCount = 3: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6629): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-7026376509154276594&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6629): Headers:
W/ApiaryClient( 6629): accept-encoding: [gzip]
W/ApiaryClient( 6629): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6629): gdata-version: 2
,E/WifiStateMachine( 1032):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=2.3, 0.0, 0.0  rx=1.8 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1470638821] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1032):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=2.3, 0.0, 0.0  rx=1.8 bcn=0 [on:0 tx:0 rx:0 period:11] from screen [on:0 period:-1470638810] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1032): doString: [SIGNAL_POLL]
E/BooksSync( 6629): Soft error: 
E/BooksSync( 6629): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 6629): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-7026376509154276594&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 6629): Headers:
E/BooksSync( 6629): accept-encoding: [gzip]
E/BooksSync( 6629): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 6629): gdata-version: 2
E/BooksSync( 6629): 
E/BooksSync( 6629): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 6629): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 6629): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 6629): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 6629): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 6629): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 6629): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 6629): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 6629): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 6629): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 6629): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 6629): {
E/BooksSync( 6629):  "error": {
E/BooksSync( 6629):   "errors": [
E/BooksSync( 6629):    {
E/BooksSync( 6629):     "domain": "global",
E/BooksSync( 6629):     "reason": "required",
E/BooksSync( 6629):     "message": "Login Required",
E/BooksSync( 6629):     "locationType": "header",
E/BooksSync( 6629):     "location": "Authorization"
E/BooksSync( 6629):    }
E/BooksSync( 6629):   ],
E/BooksSync( 6629):   "code": 401,
E/BooksSync( 6629):   "message": "Login Required"
E/BooksSync( 6629):  }
E/BooksSync( 6629): }
E/BooksSync( 6629): 
E/BooksSync( 6629): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 6629): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 6629): 	... 8 more
,E/BooksSync( 6629): Sync error
E/BooksSync( 6629): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 6629): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-7026376509154276594&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 6629): Headers:
E/BooksSync( 6629): accept-encoding: [gzip]
E/BooksSync( 6629): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 6629): gdata-version: 2
E/BooksSync( 6629): 
E/BooksSync( 6629): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 6629): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 6629): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 6629): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 6629): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 6629): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 6629): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 6629): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 6629): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 6629): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 6629): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 6629): {
E/BooksSync( 6629):  "error": {
E/BooksSync( 6629):   "errors": [
E/BooksSync( 6629):    {
E/BooksSync( 6629):     "domain": "global",
E/BooksSync( 6629):     "reason": "required",
E/BooksSync( 6629):     "message": "Login Required",
E/BooksSync( 6629):     "locationType": "header",
E/BooksSync( 6629):     "location": "Authorization"
E/BooksSync( 6629):    }
E/BooksSync( 6629):   ],
E/BooksSync( 6629):   "code": 401,
E/BooksSync( 6629):   "message": "Login Required"
E/BooksSync( 6629):  }
E/BooksSync( 6629): }
E/BooksSync( 6629): 
E/BooksSync( 6629): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 6629): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 6629): 	... 8 more
I/BooksSync( 6629): Finished books sync
D/SyncManager( 1032): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 168494, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/sensors_hal_Time( 1032): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1032): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1032): tsOffsetIs: Apps: 197510711180; DSPS: 6612830; Offset : -4309778539
,E/WifiStateMachine( 1032):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=4.2, 0.0, 0.0  rx=2.9 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:-1470635787] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1032):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=4.2, 0.0, 0.0  rx=2.9 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1470635784] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1032): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1032):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=2.6, 0.0, 0.0  rx=2.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1470632762] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1032):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=2.6, 0.0, 0.0  rx=2.0 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-1470632752] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1032): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1032):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=1.3, 0.0, 0.0  rx=1.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1470629732] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1032):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=1.3, 0.0, 0.0  rx=1.0 bcn=0 [on:0 tx:0 rx:0 period:12] from screen [on:0 period:-1470629720] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1032): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1032):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=1.1, 0.0, 0.0  rx=1.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1470626698] gl rssi=-64 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1032):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=1.1, 0.0, 0.0  rx=1.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1470626695] gl rssi=-64 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1032): doString: [SIGNAL_POLL]
,V/AlarmManager( 1032): RTC_WAKEUP set : Alarm{3bb98c9f type 0 when 1454523282524 com.android.vending} when 1454523282524
,V/SIM_STK ( 1032): Menu title from STK is T-Mobile
,V/GLSActivity( 2063): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2063): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 2063): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2063): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 2063): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2063): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/Finsky  ( 7415): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 7415): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 7415): [1] 5.onFinished: Scheduling replication attempt 4.
,E/WifiStateMachine( 1032):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=1.1, 0.0, 0.0  rx=1.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1470623668] gl rssi=-64 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1032):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=1.1, 0.0, 0.0  rx=1.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1470623665] gl rssi=-64 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1032): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1032):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.5 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1470620638] gl rssi=-64 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1032):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.5 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1470620635] gl rssi=-64 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1032): doString: [SIGNAL_POLL]
,D/sensors_hal_Time( 1032): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1032): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1032): tsOffsetIs: Apps: 217512792109; DSPS: 7268258; Offset : -4309772518
,E/WifiStateMachine( 1032):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1470617610] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1032):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:9] from screen [on:0 period:-1470617601] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1032): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1032):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1470614581] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1032):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:12] from screen [on:0 period:-1470614569] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1032): doString: [SIGNAL_POLL]
I/[SystemUI]TimeTickManager( 1447): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1447): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1447): called onTimeUpdated()
I/[SystemUI]Clock( 1447): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1447): called onTimeUpdated()
I/[SystemUI]DateView( 1447): called onTimeUpdated()
I/[SystemUI]DateView( 1447): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1447): handleTimeUpdate
,D/PowerManagerServiceEx( 1032): acquireWakeLockInternal: lock=58637760, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1032
,V/AlarmManager( 1032): ELAPSED_WAKEUP set : Alarm{290df069 type 2 when 222853 android} when 222853
D/[Concierge]Service( 2591): onStartCommand(). Type : 9
,D/PowerManagerServiceEx( 1032): releaseWakeLockInternal: lock=58637760 [*alarm*], flags=0x0
,E/WifiStateMachine( 1032):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1470611548] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1032):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1470611545] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1032): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1032):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1470608514] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1032):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1470608511] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1032): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1032):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1470605485] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1032):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1470605482] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1032): doString: [SIGNAL_POLL]
,V/AlarmManager( 1032): ELAPSED_WAKEUP set : Alarm{14658aee type 2 when 214070 android} when 214070
,V/AlarmManager( 1032): RTC_WAKEUP set : Alarm{db13e1c type 0 when 1454523308706 com.android.vending} when 1454523308706
,I/DigitalAppWidgetProvider( 6933): onReceive: com.android.deskclock.ON_QUARTER_HOUR
,V/DigitalAppWidgetProvider( 6933): startAlarmOnQuarterHour android.app.ReceiverRestrictedContext@2b2e07a9
V/SIM_STK ( 1032): Menu title from STK is T-Mobile
,V/GLSActivity( 2063): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2063): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 2063): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2063): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2063): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2063): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 7415): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 7415): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 7415): [1] 5.onFinished: Scheduling replication attempt 5.
,E/WifiStateMachine( 1032):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1470602462] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1032):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1470602459] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1032): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1032):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1470599431] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1032):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:11] from screen [on:0 period:-1470599420] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1032): doString: [SIGNAL_POLL]
,D/sensors_hal_Time( 1032): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1032): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1032): tsOffsetIs: Apps: 237514642934; DSPS: 7923679; Offset : -4309783265
,E/WifiStateMachine( 1032):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1470596400] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1032):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:11] from screen [on:0 period:-1470596389] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1032): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1032):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1470593367] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1032):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1470593364] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1032): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1032):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1470590338] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1032):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1470590335] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1032): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1032):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1470587310] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1032):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-1470587300] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1032): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1032):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1470584280] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1032):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:12] from screen [on:0 period:-1470584268] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1032): doString: [SIGNAL_POLL]
I/jxcore-log( 6067): --= Surplus to requirements =--
I/jxcore-log( 6067): 
,I/jxcore-log( 6067): ****TEST TOOK:  ms ****
I/jxcore-log( 6067): 
,I/jxcore-log( 6067): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 6067): 
E/WifiStateMachine( 1032):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1470581246] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1032):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1470581243] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1032): doString: [SIGNAL_POLL]
,D/AndroidRuntime( 7644): 
D/AndroidRuntime( 7644): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime( 7644): CheckJNI is OFF
D/AndroidRuntime( 7644): Calling main entry com.android.commands.pm.Pm
,I/ActivityManager( 1032): Force stopping com.test.thalitest appid=10311 user=-1: uninstall pkg
I/ActivityManager( 1032): Killing 6067:com.test.thalitest/u0a311 (adj 0): stop com.test.thalitest
,I/WindowState( 1032): WIN DEATH: Window{20f426e4 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,D/WifiService( 1032): Client connection lost with reason: 4
D/InputDispatcher( 1032): Window went away: Window{20f426e4 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,W/PackageSettings( 1032): Skipping PackageSetting{20065bc1 com.example.hello/10319} due to missing metadata
,I/ActivityManager( 1032):   Force finishing activity ActivityRecord{2471f5ec u0 com.test.thalitest/.MainActivity t4}
,E/GBMv2   (  342): DFP En is all cleared set to be enabled
,W/ActivityManager( 1032): Spurious death for ProcessRecord{29408b9e 6067:com.test.thalitest/u0a311}, curProc for 6067: null
I/ActivityManager( 1032): Force stopping com.test.thalitest appid=10311 user=0: pkg removed
,I/ActivityManager( 1032):   Force finishing activity ActivityRecord{2471f5ec u0 com.test.thalitest/.MainActivity t4 f}
W/ActivityManager( 1032): Duplicate finish request for ActivityRecord{2471f5ec u0 com.test.thalitest/.MainActivity t4 f}
I/[LGHome]EVENT( 2005): [Launcher.java:5338:onStart()]onStart
I/[LGHome]EVENT( 2005): [Launcher.java:903:onResume()]onResume
,D/SplitWindowPolicy( 1915): updateActivityStateChanged: resumed=false, screenId=0, isScreenFull=false
D/SplitWindowPolicy( 1915): topRunningActivity=ActivityInfo{1764cd5f co.....Launcher}, taskId=3, activityType=1, bIsSplit=false
D/SplitWindowPolicy( 1915): updateActivityStateChanged: resumed=true, screenId=0, isScreenFull=false
I/[LGHome]EVENT( 2005): [LauncherModel.java:1352:startLoader()]startLoader isLaunching=true
D/SplitWindowPolicy( 1915): topRunningActivity=ActivityInfo{22f893ac co.....Launcher}, taskId=3, activityType=1, bIsSplit=false
I/[LGHome]Launcher.Model( 2005): [LauncherModel.java:1469:loadAndBindWorkspace()]loadAndBindWorkspace=0ms
D/KeyguardModel( 1447): mPackageIntentReceiver, received action: android.intent.action.PACKAGE_REMOVED, sendingUserId:0
I/InputReader( 1032): Reconfiguring input devices.  changes=0x00000010
,W/GeofencerStateMachine( 1790): Ignoring removeGeofence because network location is disabled.
D/LIA_MrGDBLogger_PackageInfoDetector( 2703): [dreamwood]action: android.intent.action.PACKAGE_REMOVED, package: com.test.thalitest
D/LIA_Service_RemotePackageHandler( 1969): onReceive action : android.intent.action.PACKAGE_REMOVED = package:com.test.thalitest
E/LGBluetoothAvrcpQcomAdapter( 6128): [BTUI] [BTUI] onReceive()... android.intent.action.PACKAGE_REMOVED
D/LGBluetoothAvrcpQcomAdapter( 6128): [BTUI] [+] updateMediaPlayerInfo
,I/ActivityManager( 1032): Start proc com.wsandroid.suite.lge for broadcast com.wsandroid.suite.lge/com.wavesecure.core.WSAndroidSystemIntentReceiver: pid=7675 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,I/[LGHome]GBoardWebView( 2005): [GBoardWebView.java:306:loadCacheBitmapPostDelayed()]loadCacheBitmapPostDelayed() delay:1
,I/[LGHome]LGActivityUtil( 2005): [LGActivityUtil.java:319:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
I/[SystemUI]QSlideListController( 1447): onReceive = android.intent.action.PACKAGE_REMOVED
I/art     ( 4214): Explicit concurrent mark sweep GC freed 31098(1836KB) AllocSpace objects, 0(0B) LOS objects, 34% free, 29MB/45MB, paused 441us total 106.520ms
D/ActionManagerService( 1879): notifyUserLog: 1000003
I/[LGHome]EVENT( 2005): [Launcher.java:1056:onResume()]onResume end
D/LIA_Informant_ActionManagerMessageHandler( 2703): handleMessage: what(1000) actionID(0x1000003)
I/[LGHome]EVENT( 2005): [Launcher.java:1114:onPause()]onPause
,I/[LGHome]GBoardWebView( 2005): [GBoardWebView.java:247:writeCacheBitmapPostDelayed()]writeCacheBitmapPostDelayed() delay: we don't have a change point1
,D/KeyguardModel( 1447): package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
D/KeyguardModel( 1447): createShortcutInfo...
,W/System.err( 4169): android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
W/System.err( 4169): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
W/System.err( 4169): 	at com.lge.mlt.MptOnAppWatcher$1.onReceive(MptOnAppWatcher.java:44)
W/System.err( 4169): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:956)
W/System.err( 4169): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 4169): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 4169): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 4169): 	at android.app.ActivityThread.main(ActivityThread.java:5274)
W/System.err( 4169): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 4169): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 4169): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
W/System.err( 4169): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
D/ActionManagerService( 1879): notifyUserLog: 1000004
D/LIA_Informant_ActionManagerMessageHandler( 2703): handleMessage: what(1000) actionID(0x1000004)
V/BoardContentProvider( 2703): query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
I/GBoardWebViewUtils( 2005): checkExpiredAndRemoveCard() card: GBoardCard = { id: mw_initial
I/GBoardWebViewUtils( 2005): , create_time: 1430558575574
I/GBoardWebViewUtils( 2005): , expire_time: 0
I/GBoardWebViewUtils( 2005): , raw_uri: file:///system/etc/mrg_default_forms/MyWellness/initial/initial.html?id=mw_initial
I/GBoardWebViewUtils( 2005): , category: com.lge.intent.category.gboard.MYWELLNESS
I/GBoardWebViewUtils( 2005): , display: false
I/GBoardWebViewUtils( 2005): , animation: false }
I/GBoardWebViewUtils( 2005): checkExpiredAndRemoveCard() card: GBoardCard = { id: dyk000
I/GBoardWebViewUtils( 2005): , create_time: 1430558575600
I/GBoardWebViewUtils( 2005): , expire_time: 0
I/GBoardWebViewUtils( 2005): , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
I/GBoardWebViewUtils( 2005): , category: com.lge.intent.category.gboard.DOYOUKNOW
I/GBoardWebViewUtils( 2005): , display: false
I/GBoardWebViewUtils( 2005): , animation: false }
I/GBoardWebViewUtils( 2005): checkExpiredAndRemoveCard() card: GBoardCard = { id: guide_1111111111116_1453982949437
I/GBoardWebViewUtils( 2005): , create_time: 1453982950152
I/GBoardWebViewUtils( 2005): , expire_time: 0
I/GBoardWebViewUtils( 2005): , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/4/userguide.html?id=guide_1111111111116_1453982949437&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
I/GBoardWebViewUtils( 2005): , category: com.lge.intent.category.gboard.DOYOUKNOW
I/GBoardWebViewUtils( 2005): , display: false
I/GBoardWebViewUtils( 2005): , animation: false }
D/KeyguardModel( 1447): package = com.android.mms, class = com.android.mms.ui.ConversationList
D/KeyguardModel( 1447): createShortcutInfo...
I/[SystemUI]AppWidgetPanel(QRemoteWidgetPanel)( 1447): onReceive = android.intent.action.PACKAGE_REMOVED, packageName : com.test.thalitest
D/KeyguardModel( 1447): mPackageIntentReceiver, received action: android.intent.action.PACKAGE_FULLY_REMOVED, sendingUserId:0
W/ResourcesManager( 1447): Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
W/ResourcesManager( 1447): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 1447): Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
W/ResourcesManager( 1447): Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
,D/SplitUIManager( 1842): split_name #11 / not available #0
D/SplitUIService( 1842): removed split : 
W/ResourceType( 1447): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1447): Failure retrieving resources for com.android.mms: Resource ID #0x0
I/SystemUI[Framework]( 1032): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x8000, pkg=com.android.systemui
W/PhoneWindowManagerEx( 1032): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx( 1032): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx( 1032): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework]( 1032): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@14e4efda,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework]( 1032): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
D/WallpaperManager( 2005): suggestDesiredDimensions(2880, 2560) by package(com.lge.launcher2)
D/KeyguardModel( 1447): package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
D/KeyguardModel( 1447): createShortcutInfo...
I/[LGHome]EVENT( 2005): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
I/[LGHome]GBoardWebView( 2005): [GBoardWebView.java:321:loadCacheBitmap()]loadCacheBitmap()
V/SIM_STK ( 1032): Menu title from STK is T-Mobile
,W/ResourcesManager( 1447): Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
D/SplitUIManager( 1842): split_name #11 / not available #0
I/SplitUIService( 1842): split app #11
W/ResourcesManager( 1447): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourceType( 1447): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1447): Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
D/KeyguardModel( 1447): package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
D/KeyguardModel( 1447): createShortcutInfo...
,W/ResourcesManager( 1447): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 1447): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 1447): Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
W/ResourcesManager( 1447): Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
W/ResourceType( 1447): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1447): Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
D/KeyguardModel( 1447): package = com.lge.camera, class = com.lge.camera.CameraApp
D/KeyguardModel( 1447): createShortcutInfo...
D/KeyguardModel( 1447): handleShortcutListChanged...
D/KeyguardModel( 1447): package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
D/KeyguardModel( 1447): createShortcutInfo...
D/KeyguardModel( 1447): package = com.android.mms, class = com.android.mms.ui.ConversationList
D/KeyguardModel( 1447): createShortcutInfo...
W/ResourceType( 1447): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1447): Failure retrieving resources for com.android.mms: Resource ID #0x0
D/KeyguardModel( 1447): package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
D/KeyguardModel( 1447): createShortcutInfo...
,W/ResourcesManager( 7675): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourceType( 1447): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1447): Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
I/[LGHome]EVENT( 2005): [Launcher.java:5349:onStop()]onStop
,D/KeyguardModel( 1447): package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
D/KeyguardModel( 1447): createShortcutInfo...
W/ResourceType( 1447): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1447): Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
,D/KeyguardModel( 1447): package = com.lge.camera, class = com.lge.camera.CameraApp
D/KeyguardModel( 1447): createShortcutInfo...
I/art     ( 1032): Explicit concurrent mark sweep GC freed 50700(2MB) AllocSpace objects, 7(624KB) LOS objects, 33% free, 44MB/66MB, paused 1.967ms total 257.473ms
I/art     ( 1032): WaitForGcToComplete blocked for 247.205ms for cause Explicit
V/SIM_STK ( 1032): Menu title from STK is T-Mobile
V/SIM_STK ( 1032): Menu title from STK is T-Mobile
,D/KeyguardModel( 1447): handleShortcutListChanged...
,D/PluginManager( 7675): init()
,D/administrator( 1032): Handling package changes for user 0
V/SIM_STK ( 1032): Menu title from STK is T-Mobile
W/ActivityManager( 1032): getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
,D/LGBluetoothAvrcpQcomAdapter( 6128): [BTUI] installed app name: Music
D/LGBluetoothAvrcpQcomAdapter( 6128): [BTUI] installed app name: Google Play Music
D/LGBluetoothAvrcpQcomAdapter( 6128): [BTUI] === MediaPlayerInfo (playerId:0) ===
D/LGBluetoothAvrcpQcomAdapter( 6128): [BTUI]          displayName: Music
D/LGBluetoothAvrcpQcomAdapter( 6128): [BTUI]          packageName: com.lge.music
D/LGBluetoothAvrcpQcomAdapter( 6128): [BTUI]          playState: 2 (PAUSED)
D/LGBluetoothAvrcpQcomAdapter( 6128): [BTUI] === MediaPlayerInfo (playerId:1) ===
D/LGBluetoothAvrcpQcomAdapter( 6128): [BTUI]          displayName: Google Play Music
D/LGBluetoothAvrcpQcomAdapter( 6128): [BTUI]          packageName: com.google.android.music
D/LGBluetoothAvrcpQcomAdapter( 6128): [BTUI]          playState: 2 (PAUSED)
D/LGBluetoothAvrcpQcomAdapter( 6128): [BTUI] [-] updateMediaPlayerInfo
I/[LGHome]Launcher.Model( 2005): [LauncherModel.java:2230:run()] LauncherModel bind current page shortcut
I/[LGHome]Launcher( 2005): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,I/[LGHome]EVENT( 2005): [Workspace.java:918:addInScreen()]Add Shortcut [Email] in screen 1 [1, 4]
I/[LGHome]EVENT( 2005): [Workspace.java:918:addInScreen()]Add Shortcut [Play Store] in screen 1 [2, 4]
I/[LGHome]EVENT( 2005): [Workspace.java:918:addInScreen()]Add Shortcut [Camera] in screen 1 [3, 4]
I/[LGHome]EVENT( 2005): [Workspace.java:918:addInScreen()]Add Shortcut [Settings] in screen 1 [4, 4]
,I/Timeline( 1032): Timeline: Activity_windows_visible id: ActivityRecord{1872715a u0 com.lge.launcher2/.Launcher t3} time:255270
I/[LGHome]Launcher.Model( 2005): [LauncherModel.java:2244:run()] LauncherModel bind current page shortcut
I/[LGHome]Launcher( 2005): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 2005): [LGUnreadLgeEmailsBadge.java:107:countUnreadItems()]setTotalCount : 0
I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 2005): [LGUnreadLgeEmailsBadge.java:108:countUnreadItems()]countUnreadItems() ended..
,I/[LGHome]EVENT( 2005): [Workspace.java:918:addInScreen()]Add Folder [Google] in screen 1 [0, 4]
I/[LGHome]Launcher.Model( 2005): [LauncherModel.java:2256:run()] LauncherModel bind current page widget
,I/[LGHome]Launcher( 2005): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/[Concierge]WidgetView( 2005): ConciergeWidgetView is instantiated. sIsWidgetAttached : true
D/[Concierge]Service( 2591): onStartCommand(). Type : 8
D/[Concierge]Service( 2591): Update widget. Component : {com.lge.concierge/com.lge.concierge.ConciergeWidgetProvider}
D/[Concierge]Service( 2591): Update widget ID : 11
D/[Concierge]WidgetView( 2005): change position of spinner
,I/[Concierge]WidgetView( 2005): initWebView(). Time : 1454523333416
D/[Concierge]Service( 2591): onStartCommand(). Type : 0
I/NotificationService( 1032): action=android.intent.action.PACKAGE_REMOVED queryReplace=false
D/BackupManagerService( 1032): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/JobSchedulerService( 1032): Receieved: android.intent.action.PACKAGE_REMOVED
,D/PhoneStatusBar( 1447): setSystemUiVisibility vis=8000 mask=ffffffff oldVal=0 newVal=8000 diff=8000
D/TaskPersister( 1032): removeObsoleteFile: deleting file=4_task.xml
I/[SystemUI]NavigationThemeResource( 1447): NavigationKey Color is changed(BLACK -> WHITE_WITH_SHADOW)
I/[SystemUI]NavigationThemeResource( 1447):  BarMode=4, Theme=WHITE, LightBackground=false (Transparent)
I/[SystemUI]NavigationThemeResource( 1447): , Keyguard show=false, IME shown=false, Panel expanded=false
I/[Concierge]WebView( 2005): Return exist ConciergeWebView. Reuse : 26037562
D/[Concierge]WidgetView( 2005): State Change : null -> AccInBeforeState
I/[LgeWidgetLib]LgeAppWidgetHostView( 2005): [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
I/[LgeWidgetLib]ExtViewHost( 2005): [LgeAppWidgetExtViewHost.java:136:setState()]New State = com.lge.lgewidgetlib.extview.NormalState@27dc779b
I/[LGHome]EVENT( 2005): [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.concierge.ConciergeWidgetProvider] in screen 1 [0, 0]
I/[LGHome]Launcher.Model( 2005): [LauncherModel.java:2256:run()] LauncherModel bind current page widget
I/[LGHome]Launcher( 2005): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/[LGHome]EVENT( 2005): [Workspace.java:918:addInScreen()]Add AppWidget [com.google.android.googlequicksearchbox.SearchWidgetProvider] in screen 1 [0, 2]
D/[Concierge]WidgetBroadcastReceiver( 2005): New receiver registered. Self-unregister old one. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
W/[Concierge]WidgetView( 2005): Widget kill message received. Destory myself. My : 1454523105525, New one : 1454523333416
D/[Concierge]WidgetView( 2005): Unregister all receivers
W/[Concierge]WidgetBroadcastReceiver( 2005): Tried unregister broadcastReceiver which is not registered. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
,D/[Concierge]WidgetView( 2005): isWidgetUpdateSkippable ? true
I/[LGHome]Launcher( 2005): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/[LGHome]EVENT( 2005): [Workspace.java:918:addInScreen()]Add Shortcut [Gallery] in screen 2 [0, 4]
I/[LGHome]EVENT( 2005): [Workspace.java:918:addInScreen()]Add Shortcut [Calendar] in screen 2 [1, 4]
I/[LGHome]EVENT( 2005): [Workspace.java:918:addInScreen()]Add Shortcut [QuickMemo+] in screen 2 [2, 4]
I/[LGHome]EVENT( 2005): [Workspace.java:918:addInScreen()]Add Shortcut [Quick Remote] in screen 2 [3, 4]
I/[LGHome]EVENT( 2005): [Workspace.java:918:addInScreen()]Add Shortcut [FM Radio] in screen 2 [4, 4]
I/[LGHome]Launcher( 2005): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/[LGHome]Launcher( 2005): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/[LgeWidgetLib]LgeAppWidgetHostView( 2005): [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
W/ResourcesManager( 1032): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourceType( 1032): Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
E/[LgeWidgetLib]LgeAppWidgetHostView( 2005): [LgeAppWidgetHostView.java:124:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
I/[LGHome]EVENT( 2005): [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1] in screen 2 [0, 0]
,I/[LGHome]Launcher( 2005): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/[LGHome]EVENT( 2005): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
,I/Timeline( 2005): Timeline: Activity_idle id: android.os.BinderProxy@3ba47ddd time:255431
I/art     ( 1032): Explicit concurrent mark sweep GC freed 8249(431KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 44MB/66MB, paused 3.839ms total 270.845ms
D/AndroidRuntime( 7644): Shutting down VM
,W/ExternalStrings( 7675): load override strings
W/ExternalStrings( 7675): java.lang.RuntimeException: Unexpected tag, got eat-comment
W/ExternalStrings( 7675): 	at com.mcafee.plugin.af.a(Unknown Source)
W/ExternalStrings( 7675): 	at com.mcafee.plugin.ac.b(Unknown Source)
W/ExternalStrings( 7675): 	at com.mcafee.plugin.ak.d(Unknown Source)
W/ExternalStrings( 7675): 	at com.mcafee.plugin.ak.a(Unknown Source)
W/ExternalStrings( 7675): 	at com.mcafee.app.s.getClassLoader(Unknown Source)
W/ExternalStrings( 7675): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5001)
W/ExternalStrings( 7675): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4609)
W/ExternalStrings( 7675): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4549)
W/ExternalStrings( 7675): 	at android.app.ActivityThread.access$1500(ActivityThread.java:148)
W/ExternalStrings( 7675): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1344)
W/ExternalStrings( 7675): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/ExternalStrings( 7675): 	at android.os.Looper.loop(Looper.java:135)
W/ExternalStrings( 7675): 	at android.app.ActivityThread.main(ActivityThread.java:5274)
W/ExternalStrings( 7675): 	at java.lang.reflect.Method.invoke(Native Method)
W/ExternalStrings( 7675): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/ExternalStrings( 7675): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
W/ExternalStrings( 7675): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
D/StatusProvider( 7675): onCreate
I/chromium( 2005): [INFO:CONSOLE(0)] "'window.webkitStorageInfo' is deprecated. Please use 'navigator.webkitTemporaryStorage' or 'navigator.webkitPersistentStorage' instead.", source:  (0)
,V/Signer  ( 7675): override build config not found
D/Signer  ( 7675): value of property debug is false
,D/LGMDMWrapper( 7675): Found class 'com.mcafee.lgmdm.LGMDMWrapper$DataWipe'.
,D/LGMDMWrapper( 7675): Found class 'com.mcafee.lgmdm.LGMDMWrapper$DownloadMode'.
D/LGMDMWrapper( 7675): Found class 'com.mcafee.lgmdm.LGMDMWrapper$HardReset'.
D/LGMDMWrapper( 7675): Found class 'com.mcafee.lgmdm.LGMDMWrapper$HardwareKeyReset'.
,D/LGMDMWrapper( 7675): Found class 'com.mcafee.lgmdm.LGMDMWrapper$RemoveDeviceAdmin'.
D/LGMDMWrapper( 7675): Found class 'com.mcafee.lgmdm.LGMDMWrapper$UnknownSourceInstallation'.
D/LGMDMWrapper( 7675): Found class 'com.mcafee.lgmdm.LGMDMWrapper$Usb'.
D/LGMDMWrapper( 7675): Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbDebugging'.
I/GBoardtInterface( 2005): onReloaded()
D/LGMDMWrapper( 7675): Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbHostStorage'.
D/LGMDMWrapper( 7675): Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbMediaTransfer'.
D/LGMDMWrapper( 7675): Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbPictureTransfer'.
D/LGMDMWrapper( 7675): Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbStorage'.
D/LGMDMWrapper( 7675): Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbTethering'.
I/GBoardWebViewClient( 2005): onPageFinished url:file:///android_asset/www/main.html
V/BoardContentProvider( 2703): query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
V/BoardContentProvider( 2703): query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
V/LGMDMManager( 7675): Create singleton instance
D/ActionManagerService( 1879): notifyUserLog: 1000001
,D/LIA_Informant_ActionManagerMessageHandler( 2703): handleMessage: what(1000) actionID(0x1000001)
D/LIA_Informant_Tips_SmartTipsActionManager( 2703): onEvent() : ACTION_BOARD_ENABLED
D/ActionManagerService( 1879): notifyUserLog: 1000001
D/LIA_Informant_ActionManagerMessageHandler( 2703): handleMessage: what(1000) actionID(0x1000001)
D/LIA_Informant_Tips_SmartTipsActionManager( 2703): onEvent() : ACTION_BOARD_ENABLED
D/LIA_Informant_Tips_FormEventRepository( 2703): getSize() : size - 0
D/LIA_Informant_Tips_SmartTipsActionManager( 2703): onSettingEvent() : GBoard On - add scheduler - 0
V/BoardContentProvider( 2703): query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
D/GBoardUriUtils( 2005): fileExists: file:///system/etc/mrg_default_forms/MyWellness/initial/initial2.html?id=mw_initial return true
D/GBoardWebViewUtils( 2005): changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyWellness/initial/initial2.html?id=mw_initial
D/GBoardUriUtils( 2005): fileExists: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial2.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc] return true
D/GBoardWebViewUtils( 2005): changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial2.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
D/GBoardUriUtils( 2005): fileExists: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/4/userguide2.html?id=guide_1111111111116_1453982949437&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay return true
D/GBoardWebViewUtils( 2005): changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/4/userguide2.html?id=guide_1111111111116_1453982949437&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
,D/LGMDMWrapper( 7675): LG MDM library v4.0.0 is available on this device.
,D/PostponalbeReceiver( 7675): WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.intent.action.PACKAGE_REMOVED'.
,W/ContextImpl( 7675): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
D/AppUp4:PreloadHelper( 7318): added Exclude : com.test.thalitest
,I/ActivityManager( 1032): Killing 7048:com.google.android.talk/u0a72 (adj 15): empty #17
W/ActivityThread( 7675): ClassLoader.getResources: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/libprocessgroup( 1032): failed to open /acct/uid_10072/pid_7048/cgroup.procs: No such file or directory
,V/AlarmManager( 1032): RTC_WAKEUP set : Alarm{2fb0ba72 type 0 when 1454523330553 com.android.vending} when 1454523330553
D/VoicemailCleanupService( 2346): Cleaning up data for package: com.test.thalitest
E/SQLiteLog( 2346): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
D/ContactsProvider2ForLG( 2346): performBackgroundTask SQLiteDiskIOException during query
D/ContactsProvider2ForLG( 2346): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
D/ContactsProvider2ForLG( 2346): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
D/ContactsProvider2ForLG( 2346): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:560)
D/ContactsProvider2ForLG( 2346): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
D/ContactsProvider2ForLG( 2346): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
D/ContactsProvider2ForLG( 2346): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
D/ContactsProvider2ForLG( 2346): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
D/ContactsProvider2ForLG( 2346): 	at com.android.providers.contacts.ContactDirectoryManager.updateDirectoriesForPackage(ContactDirectoryManager.java:394)
D/ContactsProvider2ForLG( 2346): 	at com.android.providers.contacts.ContactDirectoryManager.onPackageChanged(ContactDirectoryManager.java:363)
D/ContactsProvider2ForLG( 2346): 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:974)
D/ContactsProvider2ForLG( 2346): 	at com.android.providers.contacts.ContactsProvider2ForLG.performBackgroundTask(ContactsProvider2ForLG.java:375)
D/ContactsProvider2ForLG( 2346): 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:748)
D/ContactsProvider2ForLG( 2346): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/ContactsProvider2ForLG( 2346): 	at android.os.Looper.loop(Looper.java:135)
D/ContactsProvider2ForLG( 2346): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/SQLiteLog( 2346): (3850) statement aborts at 37: [DELETE FROM calls WHERE (((source_package = 'com.test.thalitest'))) AND ((type = 4))] disk I/O error
--------- beginning of crash
E/AndroidRuntime( 2346): FATAL EXCEPTION: IntentService[VoicemailCleanupService]
E/AndroidRuntime( 2346): Process: android.process.acore, PID: 2346
E/AndroidRuntime( 2346): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 2346): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/AndroidRuntime( 2346): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:739)
E/AndroidRuntime( 2346): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:892)
E/AndroidRuntime( 2346): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/AndroidRuntime( 2346): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1600)
E/AndroidRuntime( 2346): 	at com.android.providers.contacts.util.DbModifierWithNotification.delete(DbModifierWithNotification.java:161)
E/AndroidRuntime( 2346): 	at com.android.providers.contacts.voicemail.VoicemailContentTable.delete(VoicemailContentTable.java:229)
E/AndroidRuntime( 2346): 	at com.android.providers.contacts.voicemail.VoicemailContentProvider.delete(VoicemailContentProvider.java:135)
E/AndroidRuntime( 2346): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:312)
E/AndroidRuntime( 2346): 	at android.content.ContentResolver.delete(ContentResolver.java:1315)
E/AndroidRuntime( 2346): 	at com.android.providers.contacts.voicemail.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
E/AndroidRuntime( 2346): 	at com.android.providers.contacts.voicemail.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
E/AndroidRuntime( 2346): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 2346): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 2346): 	at android.os.Looper.loop(Looper.java:135)
E/AndroidRuntime( 2346): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,V/SIM_STK ( 1032): Menu title from STK is T-Mobile
I/ActivityManager( 1032): Start proc com.lge.email for broadcast com.lge.email/.receiver.PackageChangeReceiver: pid=7708 uid=10023 gids={50023, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,I/Process ( 2346): Sending signal. PID: 2346 SIG: 9
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
,E/SQLiteDatabase( 7675): Failed to open database '/data/data/com.wsandroid.suite.lge/databases/WSAndroid'.
E/SQLiteDatabase( 7675): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 7675): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 7675): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 7675): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 7675): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 7675): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 7675): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 7675): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:907)
E/SQLiteDatabase( 7675): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:892)
E/SQLiteDatabase( 7675): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:795)
E/SQLiteDatabase( 7675): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1213)
E/SQLiteDatabase( 7675): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 7675): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 7675): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 7675): 	at com.mcafee.wsstorage.b.a(Unknown Source)
E/SQLiteDatabase( 7675): 	at com.mcafee.wsstorage.a.m(Unknown Source)
E/SQLiteDatabase( 7675): 	at com.mcafee.wsstorage.a.a(Unknown Source)
E/SQLiteDatabase( 7675): 	at com.mcafee.wsstorage.a.b(Unknown Source)
E/SQLiteDatabase( 7675): 	at com.mcafee.wsstorage.ConfigManager.g(Unknown Source)
E/SQLiteDatabase( 7675): 	at com.mcafee.wsstorage.ConfigManager.c(Unknown Source)
E/SQLiteDatabase( 7675): 	at com.mcafee.wsstorage.ConfigManager.ab(Unknown Source)
E/SQLiteDatabase( 7675): 	at com.mcafee.fw.ws.WSLicenseService.a(Unknown Source)
E/SQLiteDatabase( 7675): 	at com.mcafee.g.b.a(Unknown Source)
E/SQLiteDatabase( 7675): 	at com.mcafee.applock.AppLockComponent.a_(Unknown Source)
E/SQLiteDatabase( 7675): 	at com.mcafee.applock.AppLockComponent.a(Unknown Source)
E/SQLiteDatabase( 7675): 	at com.mcafee.c.b.b(Unknown Source)
E/SQLiteDatabase( 7675): 	at com.mcafee.framework.b.a(Unknown Source)
E/SQLiteDatabase( 7675): 	at com.mcafee.app.t.run(Unknown Source)
E/SQLiteDatabase( 7675): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/SQLiteDatabase( 7675): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 7675): 	at com.mcafee.d.f.run(Unknown Source)
E/SQLiteDatabase( 7675): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 7675): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 7675): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteDatabase( 7675): 	at com.mcafee.d.c.run(Unknown Source)
E/GBMv2   (  342): DFP En is all cleared set to be enabled
E/GBMv2   (  342): Set value is all cleared set the max
I/GBMv2   (  342): DFP Enabled. Ignore VFP set
E/SQLiteDatabase( 7675): Failed to open database '/data/data/com.wsandroid.suite.lge/databases/lockedapplications'.
E/SQLiteDatabase( 7675): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 7675): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 7675): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 7675): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 7675): 	at android.database.sqlite.SQLiteConnectionP,ool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 7675): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 7675): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 7675): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:907)
E/SQLiteDatabase( 7675): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:892)
E/SQLiteDatabase( 7675): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:795)
E/SQLiteDatabase( 7675): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1213)
E/SQLiteDatabase( 7675): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 7675): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 7675): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteDatabase( 7675): 	at com.mcafee.applock.a.a(Unknown Source)
E/SQLiteDatabase( 7675): 	at com.mcafee.applock.d.d(Unknown Source)
E/SQLiteDatabase( 7675): 	at com.mcafee.applock.d.<init>(Unknown Source)
E/SQLiteDatabase( 7675): 	at com.mcafee.applock.d.a(Unknown Source)
E/SQLiteDatabase( 7675): 	at com.mcafee.modes.adapt.a.<init>(Unknown Source)
E/SQLiteDatabase( 7675): 	at com.mcafee.modes.adapt.a.a(Unknown Source)
E/SQLiteDatabase( 7675): 	at com.mcafee.modes.adapt.ModesLockHelper.a(Unknown Source)
E/SQLiteDatabase( 7675): 	at com.mcafee.applock.h.<init>(Unknown Source)
E/SQLiteDatabase( 7675): 	at com.mcafee.applock.f.<init>(Unknown Source)
E/SQLiteDatabase( 7675): 	at com.mcafee.applock.f.a(Unknown Source)
E/SQLiteDatabase( 7675): 	at com.mcafee.applock.AppLockComponent.d(Unknown Source)
E/SQLiteDatabase( 7675): 	at com.mcafee.applock.AppLockComponent.a_(Unknown Source)
E/SQLiteDatabase( 7675): 	at com.mcafee.applock.AppLockComponent.a(Unknown Source)
E/SQLiteDatabase( 7675): 	at com.mcafee.c.b.b(Unknown Source)
E/SQLiteDatabase( 7675): 	at com.mcafee.framework.b.a(Unknown Source)
E/SQLiteDatabase( 7675): 	at com.mcafee.app.t.run(Unknown Source)
E/SQLiteDatabase( 7675): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/SQLiteDatabase( 7675): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 7675): 	at com.mcafee.d.f.run(Unknown Source)
E/SQLiteDatabase( 7675): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 7675): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 7675): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteDatabase( 7675): 	at com.mcafee.d.c.run(Unknown Source)
E/SQLiteOpenHelper( 7675): Couldn't open lockedapplications for writing (will try read-only):
E/SQLiteOpenHelper( 7675): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 7675): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 7675): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteOpenHelper( 7675): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteOpenHelper( 7675): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 7675): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 7675): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 7675): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:907)
E/SQLiteOpenHelper( 7675): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:892)
E/SQLiteOpenHelper( 7675): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:795)
E/SQLiteOpenHelper( 7675): 	at android.app.ContextImpl.o,penOrCreateDatabase(ContextImpl.java:1213)
E/SQLiteOpenHelper( 7675): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteOpenHelper( 7675): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteOpenHelper( 7675): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteOpenHelper( 7675): 	at com.mcafee.applock.a.a(Unknown Source)
E/SQLiteOpenHelper( 7675): 	at com.mcafee.applock.d.d(Unknown Source)
E/SQLiteOpenHelper( 7675): 	at com.mcafee.applock.d.<init>(Unknown Source)
E/SQLiteOpenHelper( 7675): 	at com.mcafee.applock.d.a(Unknown Source)
E/SQLiteOpenHelper( 7675): 	at com.mcafee.modes.adapt.a.<init>(Unknown Source)
E/SQLiteOpenHelper( 7675): 	at com.mcafee.modes.adapt.a.a(Unknown Source)
E/SQLiteOpenHelper( 7675): 	at com.mcafee.modes.adapt.ModesLockHelper.a(Unknown Source)
E/SQLiteOpenHelper( 7675): 	at com.mcafee.applock.h.<init>(Unknown Source)
E/SQLiteOpenHelper( 7675): 	at com.mcafee.applock.f.<init>(Unknown Source)
E/SQLiteOpenHelper( 7675): 	at com.mcafee.applock.f.a(Unknown Source)
E/SQLiteOpenHelper( 7675): 	at com.mcafee.applock.AppLockComponent.d(Unknown Source)
E/SQLiteOpenHelper( 7675): 	at com.mcafee.applock.AppLockComponent.a_(Unknown Source)
E/SQLiteOpenHelper( 7675): 	at com.mcafee.applock.AppLockComponent.a(Unknown Source)
E/SQLiteOpenHelper( 7675): 	at com.mcafee.c.b.b(Unknown Source)
E/SQLiteOpenHelper( 7675): 	at com.mcafee.framework.b.a(Unknown Source)
E/SQLiteOpenHelper( 7675): 	at com.mcafee.app.t.run(Unknown Source)
E/SQLiteOpenHelper( 7675): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/SQLiteOpenHelper( 7675): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteOpenHelper( 7675): 	at com.mcafee.d.f.run(Unknown Source)
E/SQLiteOpenHelper( 7675): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteOpenHelper( 7675): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteOpenHelper( 7675): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteOpenHelper( 7675): 	at com.mcafee.d.c.run(Unknown Source)
W/SQLiteOpenHelper( 7675): Opened lockedapplications in read-only mode
I/ActivityManager( 1032): Process android.process.acore (pid 2346) has died
W/ActivityManager( 1032): Scheduling restart of crashed service com.android.providers.contacts/com.lge.providers.contacts.AliveAcoreService in 1000ms
W/ActivityManager( 1032): Scheduling restart of crashed service com.android.providers.contacts/.voicemail.VoicemailCleanupService in 11000ms
E/SQLiteDatabase( 7675): Failed to open database '/data/data/com.wsandroid.suite.lge/databases/WSAndroid'.
E/SQLiteDatabase( 7675): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 7675): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 7675): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 7675): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 7675): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 7675): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 7675): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 7675): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:907)
E/SQLiteDatabase( 7675): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:892)
E/SQLiteDatabase( 7675): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:795)
E/SQLiteDatabase( 7675): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1213)
E/SQLiteDatabase( 7675): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 7675): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 7675): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 7675): 	at com.mcafee.wsstorage.b.a(Unknown Source)
E/SQLiteDatabase( 7675): 	at com.mcafee.wsstorage.a.m(Unknown Source)
E/SQLiteDatabase( 7675): 	at com.mcafee.wsstorage.a.a(Unknown Source)
E/SQLiteDatabase( 7675): 	at com.mcafee.wsstorage.a.b(Unknown Source)
E/SQLiteDatabase( 7675): 	at com.mcafee.wsstorage.ConfigManager.g(Unknown Source)
E/SQLiteDatabase( 7675): 	at com.mcafee.wsstorage.ConfigManager.b(Unknown Source)
E/SQLiteDatabase( 7675): 	at com.mcafee.notificationtray.e.<init>(Unknown Source)
E/SQLiteDatabase( 7675): 	at com.mcafee.notificationtray.e.a(Unknown Source)
E/SQLiteDatabase( 7675): 	at com.mcafee.notificationtray.NotificationComponent.a(Unknown Source)
E/SQLiteDatabase( 7675): 	at com.mcafee.c.b.b(Unknown Source)
E/SQLiteDatabase( 7675): 	at com.mcafee.framework.b.a(Unknown Source)
E/SQLiteDatabase( 7675): 	at com.mcafee.app.t.run(Unknown Source)
E/SQLiteDatabase( 7675): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/SQLiteDatabase( 7675): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 7675): 	at com.mcafee.d.f.run(Unknown Source)
E/SQLiteDatabase( 7675): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 7675): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 7675): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteDatabase( 7675): 	at com.mcafee.d.c.run(Unknown Source)
,E/SQLiteDatabase( 7675): Failed to open database '/data/data/com.wsandroid.suite.lge/databases/WSAndroid'.
E/SQLiteDatabase( 7675): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 7675): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 7675): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 7675): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 7675): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 7675): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 7675): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 7675): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:907)
E/SQLiteDatabase( 7675): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:892)
E/SQLiteDatabase( 7675): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:795)
E/SQLiteDatabase( 7675): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1213)
E/SQLiteDatabase( 7675): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 7675): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 7675): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 7675): 	at com.mcafee.wsstorage.b.a(Unknown Source)
E/SQLiteDatabase( 7675): 	at com.mcafee.wsstorage.a.m(Unknown Source)
E/SQLiteDatabase( 7675): 	at com.mcafee.wsstorage.a.a(Unknown Source)
E/SQLiteDatabase( 7675): 	at com.mcafee.wsstorage.a.b(Unknown Source)
E/SQLiteDatabase( 7675): 	at com.mcafee.wsstorage.ConfigManager.a(Unknown Source)
E/SQLiteDatabase( 7675): 	at com.wavesecure.utils.CommonPhoneUtils.o(Unknown Source)
E/SQLiteDatabase( 7675): 	at com.wavesecure.utils.y.v(Unknown Source)
E/SQLiteDatabase( 7675): 	at com.wavesecure.core.WSComponent.a(Unknown Source)
E/SQLiteDatabase( 7675): 	at com.mcafee.c.b.b(Unknown Source)
E/SQLiteDatabase( 7675): 	at com.mcafee.framework.b.a(Unknown Source)
E/SQLiteDatabase( 7675): 	at com.mcafee.app.t.run(Unknown Source)
E/SQLiteDatabase( 7675): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/SQLiteDatabase( 7675): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 7675): 	at com.mcafee.d.f.run(Unknown Source)
E/SQLiteDatabase( 7675): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 7675): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 7675): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteDatabase( 7675): 	at com.mcafee.d.c.run(Unknown Source)
W/ResourcesManager( 7708): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7708): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 7708): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
W/ResourcesManager( 7708): Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
E/SQLiteDatabase( 7675): Failed to open database '/data/data/com.wsandroid.suite.lge/databases/WSAndroid'.
E/SQLiteDatabase( 7675): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 7675): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 7675): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 7675): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 7675): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 7675): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 7675): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 7675): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:907)
E/SQLiteDatabase( 7675): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:892)
E/SQLiteDatabase( 7675): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:795)
E/SQLiteDatabase( 7675): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1213)
E/SQLiteDatabase( 7675): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 7675): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 7675): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 7675): 	at com.mcafee.wsstorage.b.a(Unknown Source)
E/SQLiteDatabase( 7675): 	at com.mcafee.wsstorage.a.m(Unknown Source)
E/SQLiteDatabase( 7675): 	at com.mcafee.wsstorage.a.a(Unknown Source)
E/SQLiteDatabase( 7675): 	at com.mcafee.wsstorage.a.b(Unknown Source)
E/SQLiteDatabase( 7675): 	at com.mcafee.wsstorage.ConfigManager.g(Unknown Source)
E/SQLiteDatabase( 7675): 	at com.mcafee.wsstorage.ConfigManager.d(Unknown Source)
E/SQLiteDatabase( 7675): 	at com.wavesecure.utils.CommonPhoneUtils.o(Unknown Source)
E/SQLiteDatabase( 7675): 	at com.wavesecure.utils.y.v(Unknown Source)
E/SQLiteDatabase( 7675): 	at com.wavesecure.core.WSComponent.a(Unknown Source)
E/SQLiteDatabase( 7675): 	at com.mcafee.c.b.b(Unknown Source)
E/SQLiteDatabase( 7675): 	at com.mcafee.framework.b.a(Unknown Source)
E/SQLiteDatabase( 7675): 	at com.mcafee.app.t.run(Unknown Source)
E/SQLiteDatabase( 7675): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/SQLiteDatabase( 7675): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 7675): 	at com.mcafee.d.f.run(Unknown Source)
E/SQLiteDatabase( 7675): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 7675): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 7675): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteDatabase( 7675): 	at com.mcafee.d.c.run(Unknown Source)
E/SQLiteDatabase( 7675): Failed to open database '/data/data/com.wsandroid.suite.lge/databases/WSAndroid'.
E/SQLiteDatabase( 7675): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 7675): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 7675): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 7675): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 7675): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 7675): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 7675): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 7675): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:907)
E/SQLiteDatabase( 7675): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:892)
E/SQLiteDatabase( 7675): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:795)
E/SQLiteDatabase( 7675): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1213)
E/SQLiteDatabase( 7675): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 7675): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 7675): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 7675): 	at com.mcafee.wsstorage.b.a(Unknown Source)
E/SQLiteDatabase( 7675): 	at com.mcafee.wsstorage.a.m(Unknown Source)
E/SQLiteDatabase( 7675): 	at com.mcafee.wsstorage.a.a(Unknown Source)
E/SQLiteDatabase( 7675): 	at com.mcafee.wsstorage.a.b(Unknown Source)
E/SQLiteDatabase( 7675): 	at com.mcafee.wsstorage.ConfigManager.g(Unknown Source)
E/SQLiteDatabase( 7675): 	at com.mcafee.wsstorage.ConfigManager.c(Unknown Source)
E/SQLiteDatabase( 7675): 	at com.mcafee.wsstorage.ConfigManager.m(Unknown Source)
E/SQLiteDatabase( 7675): 	at com.wavesecure.core.WSComponent.a(Unknown Source)
E/SQLiteDatabase( 7675): 	at com.mcafee.c.b.b(Unknown Source)
E/SQLiteDatabase( 7675): 	at com.mcafee.framework.b.a(Unknown Source)
E/SQLiteDatabase( 7675): 	at com.mcafee.app.t.run(Unknown Source)
E/SQLiteDatabase( 7675): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/SQLiteDatabase( 7675): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 7675): 	at com.mcafee.d.f.run(Unknown Source)
E/SQLiteDatabase( 7675): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 7675): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 7675): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteDatabase( 7675): 	at com.mcafee.d.c.run(Unknown Source)
E/SQLiteDatabase( 7675): Failed to open database '/data/data/com.wsandroid.suite.lge/databases/WSAndroid'.
E/SQLiteDatabase( 7675): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 7675): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 7675): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 7675): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 7675): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 7675): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 7675): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 7675): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:907)
E/SQLiteDatabase( 7675): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:892)
E/SQLiteDatabase( 7675): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:795)
E/SQLiteDatabase( 7675): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1213)
E/SQLiteDatabase( 7675): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 7675): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 7675): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 7675): 	at com.mcafee.wsstorage.b.a(Unknown Source)
E/SQLiteDatabase( 7675): 	at com.mcafee.wsstorage.a.m(Unknown Source)
E/SQLiteDatabase( 7675): 	at com.mcafee.wsstorage.a.a(Unknown Source)
E/SQLiteDatabase( 7675): 	at com.mcafee.wsstorage.a.b(Unknown Source)
E/SQLiteDatabase( 7675): 	at com.mcafee.wsstorage.ConfigManager.g(Unknown Source)
E/SQLiteDatabase( 7675): 	at com.mcafee.wsstorage.ConfigManager.c(Unknown Source)
E/SQLiteDatabase( 7675): 	at com.wavesecure.c2dm.a.d(Unknown Source)
E/SQLiteDatabase( 7675): 	at com.wavesecure.c2dm.a.c(Unknown Source)
E/SQLiteDatabase( 7675): 	at com.wavesecure.notification.g.a(Unknown Source)
E/SQLiteDatabase( 7675): 	at com.wavesecure.core.WSComponent.a(Unknown Source)
E/SQLiteDatabase( 7675): 	at com.mcafee.c.b.b(Unknown Source)
E/SQLiteDatabase( 7675): 	at com.mcafee.framework.b.a(Unknown Source)
E/SQLiteDatabase( 7675): 	at com.mcafee.app.t.run(Unknown Source)
E/SQLiteDatabase( 7675): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/SQLiteDatabase( 7675): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 7675): 	at com.mcafee.d.f.run(Unknown Source)
E/SQLiteDatabase( 7675): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 7675): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 7675): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteDatabase( 7675): 	at com.mcafee.d.c.run(Unknown Source)
I/GBoardtInterface( 2005): exportHTML()
D/LgDataFeature( 7675): LgDataFeature() Constructor: none
D/LgDataFeature( 7675): LgDataFeature() Constructor Done, null
,E/SQLiteDatabase( 7675): Failed to open database '/data/data/com.wsandroid.suite.lge/databases/WSAndroid'.
E/SQLiteDatabase( 7675): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 7675): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 7675): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 7675): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 7675): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 7675): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 7675): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 7675): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:907)
E/SQLiteDatabase( 7675): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:892)
E/SQLiteDatabase( 7675): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:795)
E/SQLiteDatabase( 7675): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1213)
E/SQLiteDatabase( 7675): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 7675): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 7675): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 7675): 	at com.mcafee.wsstorage.b.a(Unknown Source)
E/SQLiteDatabase( 7675): 	at com.mcafee.wsstorage.a.m(Unknown Source)
E/SQLiteDatabase( 7675): 	at com.mcafee.wsstorage.a.a(Unknown Source)
E/SQLiteDatabase( 7675): 	at com.mcafee.wsstorage.a.b(Unknown Source)
E/SQLiteDatabase( 7675): 	at com.mcafee.wsstorage.ConfigManager.a(Unknown Source)
E/SQLiteDatabase( 7675): 	at com.mcafee.wsstorage.ConfigManager.b(Unknown Source)
E/SQLiteDatabase( 7675): 	at com.mcafee.wsstorage.ConfigManager.J(Unknown Source)
E/SQLiteDatabase( 7675): 	at com.wavesecure.c2dm.a.d(Unknown Source)
E/SQLiteDatabase( 7675): 	at com.wavesecure.c2dm.a.c(Unknown Source)
E/SQLiteDatabase( 7675): 	at com.wavesecure.notification.g.a(Unknown Source)
E/SQLiteDatabase( 7675): 	at com.wavesecure.core.WSComponent.a(Unknown Source)
E/SQLiteDatabase( 7675): 	at com.mcafee.c.b.b(Unknown Source)
E/SQLiteDatabase( 7675): 	at com.mcafee.framework.b.a(Unknown Source)
E/SQLiteDatabase( 7675): 	at com.mcafee.app.t.run(Unknown Source)
E/SQLiteDatabase( 7675): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/SQLiteDatabase( 7675): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 7675): 	at com.mcafee.d.f.run(Unknown Source)
E/SQLiteDatabase( 7675): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 7675): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 7675): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteDatabase( 7675): 	at com.mcafee.d.c.run(Unknown Source)
E/SQLiteDatabase( 7675): Failed to open database '/data/data/com.wsandroid.suite.lge/databases/WSAndroid'.
E/SQLiteDatabase( 7675): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 7675): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 7675): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 7675): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 7675): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 7675): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 7675): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 7675): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:907)
E/SQLiteDatabase( 7675): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:892)
E/SQLiteDatabase( 7675): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:795)
E/SQLiteDatabase( 7675): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1213)
E/SQLiteDatabase( 7675): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 7675): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 7675): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 7675): 	at com.mcafee.wsstorage.b.a(Unknown Source)
E/SQLiteDatabase( 7675): 	at com.mcafee.wsstorage.a.m(Unknown Source)
E/SQLiteDatabase( 7675): 	at com.mcafee.wsstorage.a.a(Unknown Source)
E/SQLiteDatabase( 7675): 	at com.mcafee.wsstorage.a.b(Unknown Source)
E/SQLiteDatabase( 7675): 	at com.mcafee.wsstorage.ConfigManager.g(Unknown Source)
E/SQLiteDatabase( 7675): 	at com.mcafee.wsstorage.ConfigManager.d(Unknown Source)
E/SQLiteDatabase( 7675): 	at com.mcafee.wsstorage.ConfigManager.r(Unknown Source)
E/SQLiteDatabase( 7675): 	at com.wavesecure.notification.c.a(Unknown Source)
E/SQLiteDatabase( 7675): 	at com.wavesecure.core.WSComponent.a(Unknown Source)
E/SQLiteDatabase( 7675): 	at com.mcafee.c.b.b(Unknown Source)
E/SQLiteDatabase( 7675): 	at com.mcafee.framework.b.a(Unknown Source)
E/SQLiteDatabase( 7675): 	at com.mcafee.app.t.run(Unknown Source)
E/SQLiteDatabase( 7675): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/SQLiteDatabase( 7675): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 7675): 	at com.mcafee.d.f.run(Unknown Source)
E/SQLiteDatabase( 7675): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 7675): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 7675): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteDatabase( 7675): 	at com.mcafee.d.c.run(Unknown Source)
E/SQLiteDatabase( 7675): Failed to open database '/data/data/com.wsandroid.suite.lge/databases/WSAndroid'.
E/SQLiteDatabase( 7675): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 7675): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 7675): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 7675): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 7675): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 7675): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 7675): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 7675): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:907)
E/SQLiteDatabase( 7675): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:892)
E/SQLiteDatabase( 7675): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:795)
E/SQLiteDatabase( 7675): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1213)
E/SQLiteDatabase( 7675): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 7675): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 7675): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 7675): 	at com.mcafee.wsstorage.b.a(Unknown Source)
E/SQLiteDatabase( 7675): 	at com.mcafee.wsstorage.a.m(Unknown Source)
E/SQLiteDatabase( 7675): 	at com.mcafee.wsstorage.a.a(Unknown Source)
E/SQLiteDatabase( 7675): 	at com.mcafee.wsstorage.a.b(Unknown Source)
E/SQLiteDatabase( 7675): 	at com.mcafee.wsstorage.ConfigManager.g(Unknown Source)
E/SQLiteDatabase( 7675): 	at com.mcafee.wsstorage.ConfigManager.c(Unknown Source)
E/SQLiteDatabase( 7675): 	at com.wavesecure.notification.r.a(Unknown Source)
E/SQLiteDatabase( 7675): 	at com.wavesecure.core.WSComponent.a(Unknown Source)
E/SQLiteDatabase( 7675): 	at com.mcafee.c.b.b(Unknown Source)
E/SQLiteDatabase( 7675): 	at com.mcafee.framework.b.a(Unknown Source)
E/SQLiteDatabase( 7675): 	at com.mcafee.app.t.run(Unknown Source)
E/SQLiteDatabase( 7675): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/SQLiteDatabase( 7675): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 7675): 	at com.mcafee.d.f.run(Unknown Source)
E/SQLiteDatabase( 7675): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 7675): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 7675): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteDatabase( 7675): 	at com.mcafee.d.c.run(Unknown Source)
I/GBoardtInterface( 2005): exportHTML()
E/SQLiteDatabase( 7675): Failed to open database '/data/data/com.wsandroid.suite.lge/databases/WSAndroid'.
E/SQLiteDatabase( 7675): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 7675): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 7675): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 7675): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 7675): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 7675): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 7675): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 7675): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:907)
E/SQLiteDatabase( 7675): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:892)
E/SQLiteDatabase( 7675): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:795)
E/SQLiteDatabase( 7675): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1213)
E/SQLiteDatabase( 7675): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 7675): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 7675): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 7675): 	at com.mcafee.wsstorage.b.a(Unknown Source)
E/SQLiteDatabase( 7675): 	at com.mcafee.wsstorage.a.m(Unknown Source)
E/SQLiteDatabase( 7675): 	at com.mcafee.wsstorage.a.a(Unknown Source)
E/SQLiteDatabase( 7675): 	at com.mcafee.wsstorage.a.b(Unknown Source)
E/SQLiteDatabase( 7675): 	at com.mcafee.wsstorage.ConfigManager.g(Unknown Source)
E/SQLiteDatabase( 7675): 	at com.mcafee.wsstorage.ConfigManager.c(Unknown Source)
E/SQLiteDatabase( 7675): 	at com.wavesecure.notification.o.d(Unknown Source)
E/SQLiteDatabase( 7675): 	at com.mcafee.notificationtray.a.b.b(Unknown Source)
E/SQLiteDatabase( 7675): 	at com.mcafee.notificationtray.a.b.a(Unknown Source)
E/SQLiteDatabase( 7675): 	at com.mcafee.notificationtray.a.c.run(Unknown Source)
E/SQLiteDatabase( 7675): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/SQLiteDatabase( 7675): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 7675): 	at com.mcafee.d.f.run(Unknown Source)
E/SQLiteDatabase( 7675): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 7675): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 7675): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteDatabase( 7675): 	at com.mcafee.d.c.run(Unknown Source)
E/SQLiteDatabase( 7675): Failed to open database '/data/data/com.wsandroid.suite.lge/databases/WSAndroid'.
E/SQLiteDatabase( 7675): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 7675): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 7675): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 7675): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 7675): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 7675): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 7675): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 7675): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:907)
E/SQLiteDatabase( 7675): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:892)
E/SQLiteDatabase( 7675): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:795)
E/SQLiteDatabase( 7675): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1213)
E/SQLiteDatabase( 7675): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 7675): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 7675): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 7675): 	at com.mcafee.wsstorage.b.a(Unknown Source)
E/SQLiteDatabase( 7675): 	at com.mcafee.wsstorage.a.m(Unknown Source)
E/SQLiteDatabase( 7675): 	at com.mcafee.wsstorage.a.a(Unknown Source)
E/SQLiteDatabase( 7675): 	at com.mcafee.wsstorage.a.b(Unknown Source)
E/SQLiteDatabase( 7675): 	at com.mcafee.wsstorage.ConfigManager.g(Unknown Source)
E/SQLiteDatabase( 7675): 	at com.mcafee.wsstorage.ConfigManager.c(Unknown Source)
E/SQLiteDatabase( 7675): 	at com.wavesecure.notification.q.a(Unknown Source)
E/SQLiteDatabase( 7675): 	at com.wavesecure.core.WSComponent.a(Unknown Source)
E/SQLiteDatabase( 7675): 	at com.mcafee.c.b.b(Unknown Source)
E/SQLiteDatabase( 7675): 	at com.mcafee.framework.b.a(Unknown Source)
E/SQLiteDatabase( 7675): 	at com.mcafee.app.t.run(Unknown Source)
E/SQLiteDatabase( 7675): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/SQLiteDatabase( 7675): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 7675): 	at com.mcafee.d.f.run(Unknown Source)
E/SQLiteDatabase( 7675): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 7675): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 7675): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteDatabase( 7675): 	at com.mcafee.d.c.run(Unknown Source)
E/SQLiteDatabase( 7675): Failed to open database '/data/data/com.wsandroid.suite.lge/databases/WSAndroid'.
E/SQLiteDatabase( 7675): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 7675): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 7675): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 7675): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 7675): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 7675): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 7675): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 7675): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:907)
E/SQLiteDatabase( 7675): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:892)
E/SQLiteDatabase( 7675): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:795)
E/SQLiteDatabase( 7675): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1213)
E/SQLiteDatabase( 7675): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 7675): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 7675): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 7675): 	at com.mcafee.wsstorage.b.a(Unknown Source)
E/SQLiteDatabase( 7675): 	at com.mcafee.wsstorage.a.m(Unknown Source)
E/SQLiteDatabase( 7675): 	at com.mcafee.wsstorage.a.a(Unknown Source)
E/SQLiteDatabase( 7675): 	at com.mcafee.wsstorage.a.b(Unknown Source)
E/SQLiteDatabase( 7675): 	at com.mcafee.wsstorage.ConfigManager.g(Unknown Source)
E/SQLiteDatabase( 7675): 	at com.mcafee.wsstorage.ConfigManager.b(Unknown Source)
E/SQLiteDatabase( 7675): 	at com.mcafee.wsstorage.ConfigManager.aq(Unknown Source)
E/SQLiteDatabase( 7675): 	at com.mcafee.wsstorage.ConfigManager.g(Unknown Source)
E/SQLiteDatabase( 7675): 	at com.mcafee.wsstorage.MSSComponentConfig.a(Unknown Source)
E/SQLiteDatabase( 7675): 	at com.wavesecure.dataStorage.WSFeatureConfig.a(Unknown Source)
E/SQLiteDatabase( 7675): 	at com.wavesecure.backup.BaseBackup.b(Unknown Source)
E/SQLiteDatabase( 7675): 	at com.wavesecure.core.WSComponent.c(Unknown Source)
E/SQLiteDatabase( 7675): 	at com.wavesecure.core.WSComponent.a(Unknown Source)
E/SQLiteDatabase( 7675): 	at com.mcafee.c.b.b(Unknown Source)
E/SQLiteDatabase( 7675): 	at com.mcafee.framework.b.a(Unknown Source)
E/SQLiteDatabase( 7675): 	at com.mcafee.app.t.run(Unknown Source)
E/SQLiteDatabase( 7675): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/SQLiteDatabase( 7675): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 7675): 	at com.mcafee.d.f.run(Unknown Source)
E/SQLiteDatabase( 7675): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 7675): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 7675): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteDatabase( 7675): 	at com.mcafee.d.c.run(Unknown Source)
E/SQLiteDatabase( 7675): Failed to open database '/data/data/com.wsandroid.suite.lge/databases/WSAndroid'.
E/SQLiteDatabase( 7675): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 7675): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 7675): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 7675): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 7675): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 7675): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 7675): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 7675): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:907)
E/SQLiteDatabase( 7675): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:892)
E/SQLiteDatabase( 7675): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:795)
E/SQLiteDatabase( 7675): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1213)
E/SQLiteDatabase( 7675): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 7675): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 7675): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 7675): 	at com.mcafee.wsstorage.b.a(Unknown Source)
E/SQLiteDatabase( 7675): 	at com.mcafee.wsstorage.a.m(Unknown Source)
E/SQLiteDatabase( 7675): 	at com.mcafee.wsstorage.a.a(Unknown Source)
E/SQLiteDatabase( 7675): 	at com.mcafee.wsstorage.a.b(Unknown Source)
E/SQLiteDatabase( 7675): 	at com.mcafee.wsstorage.ConfigManager.a(Unknown Source)
E/SQLiteDatabase( 7675): 	at com.mcafee.wsstorage.ConfigManager.g(Unknown Source)
E/SQLiteDatabase( 7675): 	at com.mcafee.wsstorage.MSSComponentConfig.a(Unknown Source)
E/SQLiteDatabase( 7675): 	at com.wavesecure.dataStorage.WSFeatureConfig.a(Unknown Source)
E/SQLiteDatabase( 7675): 	at com.wavesecure.backup.BaseBackup.b(Unknown Source)
E/SQLiteDatabase( 7675): 	at com.wavesecure.core.WSComponent.c(Unknown Source)
E/SQLiteDatabase( 7675): 	at com.wavesecure.core.WSComponent.a(Unknown Source)
E/SQLiteDatabase( 7675): 	at com.mcafee.c.b.b(Unknown Source)
E/SQLiteDatabase( 7675): 	at com.mcafee.framework.b.a(Unknown Source)
E/SQLiteDatabase( 7675): 	at com.mcafee.app.t.run(Unknown Source)
E/SQLiteDatabase( 7675): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/SQLiteDatabase( 7675): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 7675): 	at com.mcafee.d.f.run(Unknown Source)
E/SQLiteDatabase( 7675): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 7675): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 7675): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteDatabase( 7675): 	at com.mcafee.d.c.run(Unknown Source)
E/SQLiteDatabase( 7675): Failed to open database '/data/data/com.wsandroid.suite.lge/databases/WSAndroid'.
E/SQLiteDatabase( 7675): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 7675): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 7675): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 7675): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 7675): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 7675): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 7675): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 7675): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:907)
E/SQLiteDatabase( 7675): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:892)
E/SQLiteDatabase( 7675): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:795)
E/SQLiteDatabase( 7675): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1213)
E/SQLiteDatabase( 7675): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 7675): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 7675): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 7675): 	at com.mcafee.wsstorage.b.a(Unknown Source)
E/SQLiteDatabase( 7675): 	at com.mcafee.wsstorage.a.m(Unknown Source)
E/SQLiteDatabase( 7675): 	at com.mcafee.wsstorage.a.a(Unknown Source)
E/SQLiteDatabase( 7675): 	at com.mcafee.wsstorage.a.b(Unknown Source)
E/SQLiteDatabase( 7675): 	at com.mcafee.wsstorage.ConfigManager.g(Unknown Source)
E/SQLiteDatabase( 7675): 	at com.mcafee.wsstorage.ConfigManager.e(Unknown Source)
E/SQLiteDatabase( 7675): 	at com.mcafee.wsstorage.ConfigManager.d(Unknown Source)
E/SQLiteDatabase( 7675): 	at com.wavesecure.dataStorage.WSFeatureConfig.a(Unknown Source)
E/SQLiteDatabase( 7675): 	at com.wavesecure.backup.BaseBackup.b(Unknown Source)
E/SQLiteDatabase( 7675): 	at com.wavesecure.core.WSComponent.c(Unknown Source)
E/SQLiteDatabase( 7675): 	at com.wavesecure.core.WSComponent.a(Unknown Source)
E/SQLiteDatabase( 7675): 	at com.mcafee.c.b.b(Unknown Source)
E/SQLiteDatabase( 7675): 	at com.mcafee.framework.b.a(Unknown Source)
E/SQLiteDatabase( 7675): 	at com.mcafee.app.t.run(Unknown Source)
E/SQLiteDatabase( 7675): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/SQLiteDatabase( 7675): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 7675): 	at com.mcafee.d.f.run(Unknown Source)
E/SQLiteDatabase( 7675): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 7675): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 7675): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteDatabase( 7675): 	at com.mcafee.d.c.run(Unknown Source)
E/SQLiteDatabase( 7675): Failed to open database '/data/data/com.wsandroid.suite.lge/databases/WSAndroid'.
E/SQLiteDatabase( 7675): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 7675): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 7675): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 7675): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 7675): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 7675): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 7675): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 7675): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:907)
E/SQLiteDatabase( 7675): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:892)
E/SQLiteDatabase( 7675): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:795)
E/SQLiteDatabase( 7675): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1213)
E/SQLiteDatabase( 7675): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 7675): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 7675): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 7675): 	at com.mcafee.wsstorage.b.a(Unknown Source)
E/SQLiteDatabase( 7675): 	at com.mcafee.wsstorage.a.m(Unknown Source)
E/SQLiteDatabase( 7675): 	at com.mcafee.wsstorage.a.a(Unknown Source)
E/SQLiteDatabase( 7675): 	at com.mcafee.wsstorage.a.b(Unknown Source)
E/SQLiteDatabase( 7675): 	at com.mcafee.wsstorage.ConfigManager.g(Unknown Source)
E/SQLiteDatabase( 7675): 	at com.mcafee.wsstorage.ConfigManager.c(Unknown Source)
E/SQLiteDatabase( 7675): 	at com.mcafee.wsstorage.ConfigManager.N(Unknown Source)
E/SQLiteDatabase( 7675): 	at com.mcafee.wsstorage.ConfigManager.d(Unknown Source)
E/SQLiteDatabase( 7675): 	at com.wavesecure.dataStorage.WSFeatureConfig.a(Unknown Source)
E/SQLiteDatabase( 7675): 	at com.wavesecure.backup.BaseBackup.b(Unknown Source)
E/SQLiteDatabase( 7675): 	at com.wavesecure.core.WSComponent.c(Unknown Source)
E/SQLiteDatabase( 7675): 	at com.wavesecure.core.WSComponent.a(Unknown Source)
E/SQLiteDatabase( 7675): 	at com.mcafee.c.b.b(Unknown Source)
E/SQLiteDatabase( 7675): 	at com.mcafee.framework.b.a(Unknown Source)
E/SQLiteDatabase( 7675): 	at com.mcafee.app.t.run(Unknown Source)
E/SQLiteDatabase( 7675): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/SQLiteDatabase( 7675): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 7675): 	at com.mcafee.d.f.run(Unknown Source)
E/SQLiteDatabase( 7675): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 7675): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 7675): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteDatabase( 7675): 	at com.mcafee.d.c.run(Unknown Source)
E/SQLiteDatabase( 7675): Failed to open database '/data/data/com.wsandroid.suite.lge/databases/WSAndroid'.
E/SQLiteDatabase( 7675): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 7675): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 7675): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 7675): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 7675): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 7675): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 7675): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 7675): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:907)
E/SQLiteDatabase( 7675): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:892)
E/SQLiteDatabase( 7675): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:795)
E/SQLiteDatabase( 7675): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1213)
E/SQLiteDatabase( 7675): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 7675): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 7675): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 7675): 	at com.mcafee.wsstorage.b.a(Unknown Source)
E/SQLiteDatabase( 7675): 	at com.mcafee.wsstorage.a.m(Unknown Source)
E/SQLiteDatabase( 7675): 	at com.mcafee.wsstorage.a.a(Unknown Source)
E/SQLiteDatabase( 7675): 	at com.mcafee.wsstorage.a.b(Unknown Source)
E/SQLiteDatabase( 7675): 	at com.mcafee.wsstorage.ConfigManager.g(Unknown Source)
E/SQLiteDatabase( 7675): 	at com.mcafee.wsstorage.ConfigManager.b(Unknown Source)
E/SQLiteDatabase( 7675): 	at com.wavesecure.core.WSComponent.a(Unknown Source)
E/SQLiteDatabase( 7675): 	at com.wavesecure.core.WSComponent.a(Unknown Source)
E/SQLiteDatabase( 7675): 	at com.mcafee.c.b.b(Unknown Source)
E/SQLiteDatabase( 7675): 	at com.mcafee.framework.b.a(Unknown Source)
E/SQLiteDatabase( 7675): 	at com.mcafee.app.t.run(Unknown Source)
E/SQLiteDatabase( 7675): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/SQLiteDatabase( 7675): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 7675): 	at com.mcafee.d.f.run(Unknown Source)
E/SQLiteDatabase( 7675): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 7675): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 7675): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteDatabase( 7675): 	at com.mcafee.d.c.run(Unknown Source)
E/SQLiteDatabase( 7675): Failed to open database '/data/data/com.wsandroid.suite.lge/databases/WSAndroid'.
E/SQLiteDatabase( 7675): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 7675): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 7675): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 7675): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 7675): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 7675): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 7675): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 7675): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:907)
E/SQLiteDatabase( 7675): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:892)
E/SQLiteDatabase( 7675): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:795)
E/SQLiteDatabase( 7675): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1213)
E/SQLiteDatabase( 7675): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 7675): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 7675): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 7675): 	at com.mcafee.wsstorage.b.a(Unknown Source)
E/SQLiteDatabase( 7675): 	at com.mcafee.wsstorage.a.m(Unknown Source)
E/SQLiteDatabase( 7675): 	at com.mcafee.wsstorage.a.a(Unknown Source)
E/SQLiteDatabase( 7675): 	at com.mcafee.wsstorage.a.b(Unknown Source)
E/SQLiteDatabase( 7675): 	at com.mcafee.wsstorage.ConfigManager.g(Unknown Source)
E/SQLiteDatabase( 7675): 	at com.mcafee.wsstorage.ConfigManager.c(Unknown Source)
E/SQLiteDatabase( 7675): 	at com.wavesecure.core.WSComponent.a(Unknown Source)
E/SQLiteDatabase( 7675): 	at com.wavesecure.core.WSComponent.a(Unknown Source)
E/SQLiteDatabase( 7675): 	at com.mcafee.c.b.b(Unknown Source)
E/SQLiteDatabase( 7675): 	at com.mcafee.framework.b.a(Unknown Source)
E/SQLiteDatabase( 7675): 	at com.mcafee.app.t.run(Unknown Source)
E/SQLiteDatabase( 7675): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/SQLiteDatabase( 7675): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 7675): 	at com.mcafee.d.f.run(Unknown Source)
E/SQLiteDatabase( 7675): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 7675): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 7675): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteDatabase( 7675): 	at com.mcafee.d.c.run(Unknown Source)
I/GBoardtInterface( 2005): exportHTML()
W/ContextImpl( 7675): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.vsmandroid.gh.h:-1 com.mcafee.vsm.ext.common.a.d.a:-1 com.mcafee.vsm.ext.common.api.ExtUtils.stopApp:-1 
,E/SiteAdvisor( 7675): com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Unable to copy asset file during initialization.
E/SiteAdvisor( 7675): java.io.FileNotFoundException: /data/data/com.wsandroid.suite.lge/files/sa_oem.txt: open failed: EROFS (Read-only file system)
E/SiteAdvisor( 7675): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/SiteAdvisor( 7675): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/SiteAdvisor( 7675): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/SiteAdvisor( 7675): 	at java.io.FileWriter.<init>(FileWriter.java:42)
E/SiteAdvisor( 7675): 	at com.mcafee.android.a.c.<init>(Unknown Source)
E/SiteAdvisor( 7675): 	at com.mcafee.android.a.c.<init>(Unknown Source)
E/SiteAdvisor( 7675): 	at com.mcafee.android.a.a.<init>(Unknown Source)
E/SiteAdvisor( 7675): 	at com.mcafee.android.a.a.a(Unknown Source)
E/SiteAdvisor( 7675): 	at com.mcafee.android.mmssuite.SAComponent.a(Unknown Source)
E/SiteAdvisor( 7675): 	at com.mcafee.c.b.b(Unknown Source)
E/SiteAdvisor( 7675): 	at com.mcafee.framework.b.a(Unknown Source)
E/SiteAdvisor( 7675): 	at com.mcafee.app.t.run(Unknown Source)
E/SiteAdvisor( 7675): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/SiteAdvisor( 7675): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SiteAdvisor( 7675): 	at com.mcafee.d.f.run(Unknown Source)
E/SiteAdvisor( 7675): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SiteAdvisor( 7675): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SiteAdvisor( 7675): 	at java.lang.Thread.run(Thread.java:818)
E/SiteAdvisor( 7675): 	at com.mcafee.d.c.run(Unknown Source)
E/SiteAdvisor( 7675): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/SiteAdvisor( 7675): 	at libcore.io.Posix.open(Native Method)
E/SiteAdvisor( 7675): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/SiteAdvisor( 7675): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/SiteAdvisor( 7675): 	... 18 more
D/SiteAdvisor( 7675): com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.google.android.browser/com.android.browser.BrowserActivity not supported
D/SiteAdvisor( 7675): com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.amazon.cloud9/com.amazon.cloud9.BrowserActivity not supported
D/SiteAdvisor( 7675): com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.sec.android.app.sbrowser/com.sec.android.app.sbrowser.SBrowserMainActivity not supported
D/SiteAdvisor( 7675): com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.sec.android.app.sbrowser/com.sec.android.app.sbrowser.SBrowserMainActivity not supported
D/SiteAdvisor( 7675): com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.htc.sense.browser/com.htc.sense.browser.BrowserActivity not supported
I/SiteAdvisor( 7675): com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Loading supported browsers: com.android.browser/com.android.browser.BrowserActivity; com.android.chrome/com.android.chrome.Main; 
D/SiteAdvisor( 7675): com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Here is the storedCurrentAppVersion: 3.1.2.1430
E/SQLiteDatabase( 7708): Failed to open database '/data/data/com.lge.email/databases/Downloads.db'.
E/SQLiteDatabase( 7708): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 7708): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 7708): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 7708): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 7708): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 7708): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 7708): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 7708): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:907)
E/SQLiteDatabase( 7708): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:892)
E/SQLiteDatabase( 7708): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:795)
E/SQLiteDatabase( 7708): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1213)
E/SQLiteDatabase( 7708): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 7708): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 7708): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 7708): 	at com.lge.email.ui.largefile.DownloadProvider.onCreate(DownloadProvider.java:51)
E/SQLiteDatabase( 7708): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1714)
E/SQLiteDatabase( 7708): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1683)
E/SQLiteDatabase( 7708): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5014)
E/SQLiteDatabase( 7708): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4609)
E/SQLiteDatabase( 7708): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4549)
E/SQLiteDatabase( 7708): 	at android.app.ActivityThread.access$1500(ActivityThread.java:148)
E/SQLiteDatabase( 7708): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1344)
E/SQLiteDatabase( 7708): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 7708): 	at android.os.Looper.loop(Looper.java:135)
E/SQLiteDatabase( 7708): 	at android.app.ActivityThread.main(ActivityThread.java:5274)
E/SQLiteDatabase( 7708): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteDatabase( 7708): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteDatabase( 7708): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
E/SQLiteDatabase( 7708): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
W/System.err( 7708): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
W/System.err( 7708): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
W/System.err( 7708): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
W/System.err( 7708): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
W/System.err( 7708): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
W/System.err( 7708): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
W/System.err( 7708): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
W/System.err( 7708): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:907)
W/System.err( 7708): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:892)
,W/System.err( 7708): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:795)
W/System.err( 7708): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1213)
W/System.err( 7708): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
W/System.err( 7708): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
W/System.err( 7708): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
W/System.err( 7708): 	at com.lge.email.ui.largefile.DownloadProvider.onCreate(DownloadProvider.java:51)
W/System.err( 7708): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1714)
W/System.err( 7708): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1683)
W/System.err( 7708): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5014)
W/System.err( 7708): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4609)
W/System.err( 7708): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4549)
W/System.err( 7708): 	at android.app.ActivityThread.access$1500(ActivityThread.java:148)
W/System.err( 7708): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1344)
W/System.err( 7708): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 7708): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 7708): 	at android.app.ActivityThread.main(ActivityThread.java:5274)
W/System.err( 7708): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 7708): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 7708): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
W/System.err( 7708): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
D/SiteAdvisor( 7675): com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Here about to commit perfs
E/SQLiteDatabase( 7708): Failed to open database '/data/data/com.lge.email/databases/sqt.db'.
E/SQLiteDatabase( 7708): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 7708): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 7708): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 7708): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 7708): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 7708): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 7708): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 7708): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:907)
E/SQLiteDatabase( 7708): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:892)
E/SQLiteDatabase( 7708): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:795)
E/SQLiteDatabase( 7708): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1213)
E/SQLiteDatabase( 7708): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 7708): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 7708): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 7708): 	at com.lge.email.providers.sqt.SqtProvider.onCreate(SqtProvider.java:155)
E/SQLiteDatabase( 7708): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1714)
E/SQLiteDatabase( 7708): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1683)
E/SQLiteDatabase( 7708): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5014)
E/SQLiteDatabase( 7708): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4609)
E/SQLiteDatabase( 7708): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4549)
E/SQLiteDatabase( 7708): 	at android.app.ActivityThread.access$1500(ActivityThread.java:148)
E/SQLiteDatabase( 7708): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1344)
E/SQLiteDatabase( 7708): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 7708): 	at android.os.Looper.loop(Looper.java:135)
E/SQLiteDatabase( 7708): 	at android.app.ActivityThread.main(ActivityThread.java:5274)
E/SQLiteDatabase( 7708): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteDatabase( 7708): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteDatabase( 7708): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
E/SQLiteDatabase( 7708): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
D/AndroidRuntime( 7708): Shutting down VM
E/AndroidRuntime( 7708): FATAL EXCEPTION: main
E/AndroidRuntime( 7708): Process: com.lge.email, PID: 7708
E/AndroidRuntime( 7708): java.lang.RuntimeException: Unable to get provider com.lge.email.providers.sqt.SqtProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 7708): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5017)
E/AndroidRuntime( 7708): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4609)
E/AndroidRuntime( 7708): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4549)
E/AndroidRuntime( 7708): 	at android.app.ActivityThread.access$1500(ActivityThread.java:148)
E/AndroidRuntime( 7708): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1344)
E/AndroidRuntime( 7708): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 7708): 	at android.os.Looper.loop(Looper.java:135)
E/AndroidRuntime( 7708): 	at android.app.ActivityThread.main(ActivityThread.java:5274)
E/AndroidRuntime( 7708): 	at java.lang.reflect.Method.invoke(Native Method)
E/AndroidRuntime( 7708): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/AndroidRuntime( 7708): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
E/AndroidRuntime( 7708): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
E/AndroidRuntime( 7708): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 7708): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 7708): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/AndroidRuntime( 7708): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/AndroidRuntime( 7708): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 7708): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 7708): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 7708): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:907)
E/AndroidRuntime( 7708): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:892)
E/AndroidRuntime( 7708): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:795)
E/AndroidRuntime( 7708): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1213)
E/AndroidRuntime( 7708): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/AndroidRuntime( 7708): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/AndroidRuntime( 7708): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/AndroidRuntime( 7708): 	at com.lge.email.providers.sqt.SqtProvider.onCreate(SqtProvider.java:155)
E/AndroidRuntime( 7708): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1714)
E/AndroidRuntime( 7708): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1683)
E/AndroidRuntime( 7708): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5014)
E/AndroidRuntime( 7708): 	... 11 more
E/SQLiteDatabase( 7675): Failed to open database '/data/data/com.wsandroid.suite.lge/databases/csf_call_log'.
E/SQLiteDatabase( 7675): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 7675): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 7675): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 7675): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 7675): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 7675): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 7675): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 7675): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:907)
E/SQLiteDatabase( 7675): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:892)
E/SQLiteDatabase( 7675): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:795)
E/SQLiteDatabase( 7675): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1213)
E/SQLiteDatabase( 7675): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 7675): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 7675): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteDatabase( 7675): 	at com.mcafee.utils.d.a.d(Unknown Source)
E/SQLiteDatabase( 7675): 	at com.mcafee.utils.d.a.<init>(Unknown Source)
E/SQLiteDatabase( 7675): 	at com.mcafee.csf.frame.e.a(Unknown Source)
E/SQLiteDatabase( 7675): 	at com.mcafee.csf.frame.l.a(Unknown Source)
E/SQLiteDatabase( 7675): 	at com.mcafee.csf.frame.r.a(Unknown Source)
E/SQLiteDatabase( 7675): 	at com.mcafee.csf.frame.s.b(Unknown Source)
E/SQLiteDatabase( 7675): 	at com.mcafee.csf.frame.FirewallFrame.c(Unknown Source)
E/SQLiteDatabase( 7675): 	at com.mcafee.csf.frame.FirewallFrame.a(Unknown Source)
E/SQLiteDatabase( 7675): 	at com.mcafee.csf.frame.y.a(Unknown Source)
E/SQLiteDatabase( 7675): 	at com.mcafee.csf.frame.r.a(Unknown Source)
E/SQLiteDatabase( 7675): 	at com.mcafee.csf.frame.s.run(Unknown Source)
E/SQLiteDatabase( 7675): 	at android.os.Handler.handleCallback(Handler.java:739)
E/SQLiteDatabase( 7675): 	at android.os.Handler.dispatchMessage(Handler.java:95)
E/SQLiteDatabase( 7675): 	at com.mcafee.d.e.dispatchMessage(Unknown Source)
E/SQLiteDatabase( 7675): 	at android.os.Looper.loop(Looper.java:135)
E/SQLiteDatabase( 7675): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/SQLiteDatabase( 7675): 	at com.mcafee.csf.frame.q.run(Unknown Source)
E/SQLiteOpenHelper( 7675): Couldn't open csf_call_log for writing (will try read-only):
E/SQLiteOpenHelper( 7675): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 7675): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 7675): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteOpenHelper( 7675): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteOpenHelper( 7675): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 7675): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 7675): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 7675): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:907)
E/SQLiteOpenHelper( 7675): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:892)
E/SQLiteOpenHelper( 7675): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:795)
E/SQLiteOpenHelper( 7675): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1213)
E/SQLiteOpenHelper( 7675): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteOpenHelper( 7675): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteOpenHelper( 7675): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteOpenHelper( 7675): 	at com.mcafee.utils.d.a.d(Unknown Source)
E/SQLiteOpenHelper( 7675): 	at com.mcafee.utils.d.a.<init>(Unknown Source)
E/SQLiteOpenHelper( 7675): 	at com.mcafee.csf.frame.e.a(Unknown Source)
E/SQLiteOpenHelper( 7675): 	at com.mcafee.csf.frame.l.a(Unknown Source)
E/SQLiteOpenHelper( 7675): 	at com.mcafee.csf.frame.r.a(Unknown Source)
E/SQLiteOpenHelper( 7675): 	at com.mcafee.csf.frame.s.b(Unknown Source)
E/SQLiteOpenHelper( 7675): 	at com.mcafee.csf.frame.FirewallFrame.c(Unknown Source)
E/SQLiteOpenHelper( 7675): 	at com.mcafee.csf.frame.FirewallFrame.a(Unknown Source)
E/SQLiteOpenHelper( 7675): 	at com.mcafee.csf.frame.y.a(Unknown Source)
E/SQLiteOpenHelper( 7675): 	at com.mcafee.csf.frame.r.a(Unknown Source)
E/SQLiteOpenHelper( 7675): 	at com.mcafee.csf.frame.s.run(Unknown Source)
E/SQLiteOpenHelper( 7675): 	at android.os.Handler.handleCallback(Handler.java:739)
E/SQLiteOpenHelper( 7675): 	at android.os.Handler.dispatchMessage(Handler.java:95)
E/SQLiteOpenHelper( 7675): 	at com.mcafee.d.e.dispatchMessage(Unknown Source)
E/SQLiteOpenHelper( 7675): 	at android.os.Looper.loop(Looper.java:135)
E/SQLiteOpenHelper( 7675): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/SQLiteOpenHelper( 7675): 	at com.mcafee.csf.frame.q.run(Unknown Source)
W/SQLiteOpenHelper( 7675): Opened csf_call_log in read-only mode

```
