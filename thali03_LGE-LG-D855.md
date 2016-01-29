#### Test 575312430087a60_thali03_LGE-LG-D855 Logs


```
--------- beginning of main
D/sensors_hal_Time( 1031): tsOffsetIs: Apps: 220321219840; DSPS: 7360155; Offset : -4305793117
,D/AndroidRuntime( 6078): 
D/AndroidRuntime( 6078): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 6078): CheckJNI is OFF
D/AndroidRuntime( 6078): Calling main entry com.android.commands.am.Am
--------- beginning of system
I/ActivityManager( 1031): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
V/SplitWindowPolicy( 1928): checkScreen => return. sourceIntent is null or not support SplitWindow component: ComponentInfo{co..../co.....MainActivity}
D/SplitInfo( 1031): new ActivitySplitInfo : ActivitySplitInfo [screenZone=0/ flag=0/ state=NATIVE]
D/ActivityManager( 1031): setTaskToReturnTo : TaskRecord{7facee3 #4 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
D/ActivityManager( 1031): setTaskToReturnTo : TaskRecord{7facee3 #4 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
D/WindowStateEx( 1031): AppWindowTokenEx init.. 
E/GBMv2   (  356): DFP En is all cleared set to be enabled
I/ActivityManager( 1031): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6098 uid=10311 gids={50311, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
D/AndroidRuntime( 6078): Shutting down VM
V/ActivityManager( 1031): Display changed displayId=0
D/DSDPConnection( 1838): Display #0 changed.
D/SplitWindowPolicy( 1928): updateActivityStateChanged: resumed=true, screenId=1, isScreenFull=true
D/SplitWindowPolicy( 1928): topRunningActivity=ActivityInfo{2800cb1a co.....MainActivity}, taskId=4, activityType=0, bIsSplit=false
D/SplitWindowPolicy( 1928): updateActivityStateChanged: resumed=false, screenId=1, isScreenFull=true
D/SplitWindowPolicy( 1928): topRunningActivity=ActivityInfo{3654964b co.....MainActivity}, taskId=4, activityType=0, bIsSplit=false
D/ContextHelper( 6098): convertTheme. context->name=com.test.thalitest themeResourceId=16973833
I/WebViewFactory( 6098): Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
I/LibraryLoader( 6098): Loading: webviewchromium
I/LibraryLoader( 6098): Time to load native libraries: 3 ms (timestamps 5567-5570)
I/LibraryLoader( 6098): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 6098): Binding Chromium to main looper Looper (main, tid 1) {2ccf9597}
I/LibraryLoader( 6098): Expected native library version number "",actual native library version number ""
I/chromium( 6098): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 6098): Initializing chromium process, renderers=0
,W/art     ( 6098): Attempt to remove local handle scope entry from IRT, ignoring
W/chromium( 6098): [WARNING:dns_config_service_posix.cc(293)] Failed to read DnsConfig.
W/chromium( 6098): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
I/chromium( 6098): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=32 off=46780 len=2953
I/chromium( 6098): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:33 off:229536 len:643667
V/AudioPolicyService(  340): registerClient() client 0xb14fd600, uid 10311
,D/BluetoothManagerService( 1031): Message: 20
D/BluetoothManagerService( 1031): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@25757c55:true
D/BluetoothAdapter( 6098): 499180420: getState() :  mService = null. Returning STATE_OFF
I/Adreno-EGL( 6098): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 6098): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 6098): Build Date: 12/12/14 금
I/Adreno-EGL( 6098): Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
I/Adreno-EGL( 6098): Remote Branch: 
I/Adreno-EGL( 6098): Local Patches: 
I/Adreno-EGL( 6098): Reconstruct Branch: 
W/chromium( 6098): [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
W/chromium( 6098): [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
W/art     ( 6098): Attempt to remove local handle scope entry from IRT, ignoring
W/AwContents( 6098): onDetachedFromWindow called when already detached. Ignoring
D/SystemWebViewEngine( 6098): CordovaWebView is running on device made by: LGE
W/art     ( 6098): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 6098): Attempt to remove local handle scope entry from IRT, ignoring
D/LgDataFeature( 6098): LgDataFeature() Constructor: none
D/LgDataFeature( 6098): LgDataFeature() Constructor Done, null
I/art     ( 1031): Explicit concurrent mark sweep GC freed 24176(1108KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 43MB/65MB, paused 2.491ms total 99.895ms
D/OpenGLRenderer( 6098): Render dirty regions requested: true
I/OpenGLRenderer( 6098): Initialized EGL, version 1.4
D/OpenGLRenderer( 6098): Enabling debug mode 0
D/Atlas   ( 6098): Validating map...
D/SplitWindow( 1031): check instance of lgWin Window{d24d327 u0 com.test.thalitest/com.test.thalitest.MainActivity}
I/SystemUI[Framework]( 1031): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x0, pkg=com.android.systemui
W/PhoneWindowManagerEx( 1031): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx( 1031): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx( 1031): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework]( 1031): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@237516f2,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework]( 1031): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
D/PhoneStatusBar( 1468): setSystemUiVisibility vis=0 mask=ffffffff oldVal=8000 newVal=0 diff=8000
I/[SystemUI]NavigationThemeResource( 1468): NavigationKey Color is changed(WHITE_WITH_SHADOW -> BLACK)
I/[SystemUI]NavigationThemeResource( 1468):  BarMode=0, Theme=WHITE, LightBackground=false (Transparent)
I/[SystemUI]NavigationThemeResource( 1468): , Keyguard show=false, IME shown=false, Panel expanded=false
I/ActivityManager( 1031): Displayed com.test.thalitest/.MainActivity: +560ms (total +633ms)
I/Timeline( 1031): Timeline: Activity_windows_visible id: ActivityRecord{376570e0 u0 com.test.thalitest/.MainActivity t4} time:226024
I/Timeline( 6098): Timeline: Activity_idle id: android.os.BinderProxy@3a6635b4 time:226025
I/chromium( 6098): [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
I/chromium( 6098): 
D/JsMessageQueue( 6098): Set native->JS mode to OnlineEventsBridgeMode
I/[SystemUI]TimeTickManager( 1468): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1468): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1468): called onTimeUpdated()
I/[SystemUI]Clock( 1468): called onTimeUpdated()
I/LgeClockWidgetControlView( 1468): called onTimeUpdated()
I/[SystemUI]DateView( 1468): called onTimeUpdated()
I/[SystemUI]DateView( 1468): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1468): handleTimeUpdate
I/chromium( 6098): [INFO:SkFontConfigInterface_android.cpp(247)] ---- failed to open </system/fonts/CutiveMono.ttf> as a font
I/chromium( 6098): 
D/jxcore_app_log( 6098): JniHelper::setJavaVM(0xb487c280), pthread_self() = -1435206912
I/chromium( 6098): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
V/AlarmManager( 1031): ELAPSED_WAKEUP set : Alarm{2f817ac3 type 2 when 180054 com.google.android.gms} when 180054
,D/libc-netbsd(  335): default dns: query_ipv6=0, query_ipv4=0
D/DSQN    ( 1031): DNSproblemNotiEnabled is disabled ignore DNS fail CB
V/AlarmManager( 1031): RTC_WAKEUP set : Alarm{2936be79 type 0 when 1454092140079 com.android.vending} when 1454092140079
D/[Concierge]Service( 2617): onStartCommand(). Type : 9
V/SIM_STK ( 1031): Menu title from STK is T-Mobile
V/GLSActivity( 2057): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/GLSUser ( 2057): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 2057): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2057): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2057): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2057): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/Finsky  ( 4850): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 4850): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 4850): [1] 5.onFinished: Scheduling replication attempt 5.
E/GBMv2   (  356): DFP En is all cleared set to be enabled
E/GBMv2   (  356): Set value is all cleared set the max
I/GBMv2   (  356): DFP Enabled. Ignore VFP set
W/jxcore-log( 6098): Initializing JXcore engine
W/jxcore-log( 6098): JXcore engine is ready
W/Thread-694( 6161): type=1400 audit(0.0:148): avc: denied { ioctl } for path="socket:[9884]" dev="sockfs" ino=9884 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
W/Thread-694( 6161): type=1400 audit(0.0:149): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3222 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
W/Thread-694( 6161): type=1400 audit(0.0:150): avc: denied { ioctl } for path="socket:[7639]" dev="sockfs" ino=7639 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
W/Thread-694( 6161): type=1400 audit(0.0:151): avc: denied { ioctl } for path="/cust" dev="mmcblk0p42" ino=2 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=dir
W/Thread-694( 6161): type=1400 audit(0.0:152): avc: denied { ioctl } for path="socket:[29628]" dev="sockfs" ino=29628 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
W/jxcore-log( 6098): Starting JXcore engine
,W/jxcore-log( 6098): Platform android
W/jxcore-log( 6098): 
W/jxcore-log( 6098): Process ARCH arm
W/jxcore-log( 6098): 
,I/jxcore-log( 6098): JXcore Cordova bridge is ready!
I/jxcore-log( 6098): 
W/jxcore-log( 6098): JXcore engine is started
,I/jxcore-log( 6098): Toggling radios to true
I/jxcore-log( 6098): 
,D/BluetoothManagerService( 1031): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,D/BluetoothManagerService( 1031): enable():  mBluetooth =null mBinding = false
,D/LocationManagerService( 1031): getAllProviders()=[passive, gps, network]
D/Ulp_jni ( 1031): JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
D/Ulp_jni ( 1031): JNI:system_update. Event-4
D/BluetoothManagerService( 1031): Message: 1
D/BluetoothManagerService( 1031): MESSAGE_ENABLE: mBluetooth = null
D/WifiService( 1031): New client listening to asynchronous messages
I/ActivityManager( 1031): Start proc com.android.bluetooth for service com.android.bluetooth/.btservice.AdapterService: pid=6188 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008, 4002, 1023} abi=armeabi-v7a
D/WifiServiceImplEx( 1031): setWifiEnabled: true pid=6098, uid=10311, package= com.test.thalitest, App Lable : ThaliTest
D/WifiService( 1031): setWifiEnabled: true pid=6098, uid=10311
E/WifiService( 1031): Invoking mWifiStateMachine.setWifiEnabled
,E/WifiStateMachine( 1031):  InitialState CMD_START_SUPPLICANT 0 0
I/LGFTMITEM( 1031): [GET_FTM][id=6], offset=12288
D/WifiServiceImplEx( 1031): disconnect pid=6098, uid=10311, packageName=com.test.thalitest
D/WifiServiceImplEx( 1031): reconnect pid=6098, uid=10311, packageName=com.test.thalitest
I/jxcore-log( 6098): Radios toggled
I/jxcore-log( 6098): 
,I/jxcore-log( 6098): My device name is: LGE-LG-D855
I/jxcore-log( 6098): 
D/LocationManagerService( 1031): getAllProviders()=[passive, gps, network]
D/Ulp_jni ( 1031): JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 1,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
D/Ulp_jni ( 1031): JNI:system_update. Event-4
E/WifiUtil( 1031): wfc_util_ffile_check_copy(): pid[1031] pDestFName[/data/misc/wifi/WCNSS_qcom_cfg.ini] pSourceFName[/system/etc/wifi/WCNSS_qcom_cfg.ini]
E/WifiUtil( 1031): wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
E/WifiUtil( 1031): wfc_util_ffile_check_copy(): pid[1031] pDestFName[/data/misc/wifi/WCNSS_qcom_wlan_nv.bin] pSourceFName[/system/etc/wifi/WCNSS_qcom_wlan_nv.bin]
E/WifiUtil( 1031): wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
I/WifiUtil( 1031): Intf0MacAddress=C49A027B60AC
E/WifiHW  ( 1031): unknown target_country: EU , set to default
E/WifiHW  ( 1031): [wifi_ensure_config_files] default country1 = GB
E/WifiHW  ( 1031): [wifi_ensure_config_files] default country2 = GB
I/WifiUtil( 1031): gEnableBmps=1
,W/ResourcesManager( 6188): Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
W/ResourcesManager( 6188): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 6188): Asset path '/system/framework/com.qcom.bluetooth.jar' does not exist or contains no resources.
W/ResourcesManager( 6188): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,D/BluetoothAdapterApp( 6188): Loading JNI Library
,D/SoftapController(  335): Softap fwReload - Ok
,D/Tethering( 1031): sendTetherStateChangedBroadcast 1, 0, 0
D/CommandListener(  335): Setting iface cfg
D/CommandListener(  335): Trying to bring down wlan0
D/libc-netbsd(  335): default dns: query_ipv6=0, query_ipv4=0
D/CommandListener(  335): Clearing all IP addresses on wlan0
D/DSQN    ( 1031): DNSproblemNotiEnabled is disabled ignore DNS fail CB
,I/ActivityManager( 1031): Start proc com.android.settings for broadcast com.android.settings/.deviceinfo.UsbSettingsReceiver: pid=6214 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,D/BluetoothAdapterApp( 6188): REFCOUNT: Constructed com.android.bluetooth.btservice.AdapterApp@28c128bb Instance Count = 1
,D/BluetoothAdapterApp( 6188): onCreate
E/WifiHW  ( 1031): Cannot open "/system/etc/wifi/autojoinconfig.txt": No such file or directory
W/wpa_supplicant( 6231): type=1400 audit(0.0:153): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
W/wpa_supplicant( 6231): type=1400 audit(0.0:154): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,D/ProfileConfigQcom( 6188): [BTUI] HeadsetService is supported
D/ProfileConfigQcom( 6188): Adding HeadsetService
D/ProfileConfigQcom( 6188): [BTUI] A2dpService is supported
D/ProfileConfigQcom( 6188): Adding A2dpService
D/ProfileConfigQcom( 6188): [BTUI] HidService is supported
D/ProfileConfigQcom( 6188): Adding HidService
D/ProfileConfigQcom( 6188): [BTUI] HealthService is supported
D/ProfileConfigQcom( 6188): Adding HealthService
D/LGBluetoothFeatureConfig( 6188): isSupportPan() :  mTargetOp=OPEN
I/wpa_supplicant( 6231): Successfully initialized wpa_supplicant
,D/ProfileConfigQcom( 6188): [BTUI] PanService is supported
D/ProfileConfigQcom( 6188): Adding PanService
D/ProfileConfigQcom( 6188): [BTUI] GattService is supported
D/ProfileConfigQcom( 6188): Adding GattService
D/ProfileConfigQcom( 6188): [BTUI] BluetoothMapService is supported
D/ProfileConfigQcom( 6188): Adding BluetoothMapService
D/ProfileConfigQcom( 6188): [BTUI] HeadsetClientService is NOT supported
W/ResourcesManager( 6214): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6214): Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
W/ResourcesManager( 6214): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 6214): Asset path '/system/framework/com.lge.bluetooth.jar' does not exist or contains no resources.
W/ResourcesManager( 6214): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
W/ResourcesManager( 6214): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
I/wpa_supplicant( 6231): rfkill: Cannot open RFKILL control device
I/wpa_supplicant( 6231): [LGE_PATCH] unset P2P_CAPABLE to ifname wlan0
,D/Tethering( 1031): InitialState.processMessage what=4
D/Tethering( 1031): sendTetherStateChangedBroadcast 0, 0, 0
D/BluetoothManagerService( 1031): Message: 20
D/BluetoothManagerService( 1031): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@775285d:true
D/BluetoothAdapterState( 6188): make
I/LGFMServiceAdapter( 6188): [FM] LGFMServiceAdapter : create
I/bluedroid-qcom( 6188): init
I/BluetoothAdapterState( 6188): Entering OffState
I/bte_conf( 6188): bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,I/bte_conf( 6188): bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
E/bt_osi_config( 6188): config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
I/bte_conf( 6188): bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
D/BTIF_CORE( 6188): [BTUI] lge_load_bluetooth_address
I/bluedroid-qcom( 6188): get_profile_interface socket
I/GKI_LINUX( 6188): gki_task_entry task_id=1 [BTIF] starting
I/bluedroid-qcom( 6188): get_profile_interface map_client
W/bdaddr_loader( 6246): type=1400 audit(0.0:155): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
W/bdaddr_loader( 6246): type=1400 audit(0.0:156): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
D/BluetoothAdapterProperties( 6188): Address is:58:3F:54:73:64:C0
D/BluetoothManagerService( 1031): Bluetooth Adapter name changed to G3-1
D/BluetoothManagerService( 1031): Stored Bluetooth name: G3-1
D/BluetoothAdapterProperties( 6188): Name is: G3-1
D/BluetoothManagerService( 1031): BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
D/BluetoothManagerService( 1031): Message: 40
D/BluetoothManagerService( 1031): MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
D/lge_bdaddr_loader( 6246): [BTUI] bdaddr_loader ::: START
D/lge_bdaddr_loader( 6246): [BTUI] bluetooth_load_bdaddress
I/LGFTMITEM( 6246): [GET_FTM][id=8], offset=16384
I/bluedroid-qcom( 6188): config_hci_snoop_log
D/BluetoothManagerService( 1031): Calling onBluetoothServiceUp callbacks
D/BluetoothManagerService( 1031): Broadcasting onBluetoothServiceUp() to 7 receivers.
D/lge_bdaddr_loader( 6246): [BTUI] bdaddr to set in property : 58:3F:54:73:64:C0
,E/lge_bdaddr_loader( 6246): [BTUI] bluetooth_load_bdaddress : OK => 58:3F:54:73:64:C0
D/lge_bdaddr_loader( 6246): [BTUI] bdaddr_loader ::: END
V/LGMDMManagerInternal( 6188): Create singleton instance
E/WifiStateMachine( 1031): Couldn't get getWiFiOffloadingIface : 
E/WifiStateMachine( 1031): useWiFiOffloading() : false
E/WifiStateMachine( 1031): CONFIG_LGE_WLAN_PATH : true
D/WifiMonitor( 1031): startMonitoring(wlan0) with mConnected = false
D/WifiMonitor( 1031): connecting to supplicant
I/WifiServerServiceExt( 1031): WIFI_STATE_CHANGED_ACTION [2]
V/WfdStateTracker( 1928): WfdStateTracker handleDirectStateChangedEvent: 1
D/StatusBar.NetworkController( 1468): refreshViews: Data not connected!! Set no data type icon / Roaming
,D/UsbSettingsReceiver( 6214): [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
D/UsbSettingsReceiver( 6214): [AUTORUN] sys.usb.config = ptp_only,adb
D/UsbSettingsReceiver( 6214): [AUTORUN] sys.usb.state = ptp_only,adb
D/UsbSettingsReceiver( 6214): [AUTORUN] persist.sys.usb.config = ptp_only,adb
D/UsbSettingsReceiver( 6214): [AUTORUN] onReceive() : app userid = 0, current userid = 0
,I/wpa_supplicant( 6231): rfkill: Cannot open RFKILL control device
D/BluetoothAdapterState( 6188): CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
D/BluetoothAdapterProperties( 6188): Setting state to 11
I/BluetoothAdapterState( 6188): Bluetooth adapter state changed: 10-> 11
D/BluetoothManagerService( 1031): Message: 60
D/BluetoothManagerService( 1031): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
,D/BluetoothManagerService( 1031): Bluetooth State Change Intent: 10 -> 11
I/LGBluetoothServiceJni( 6188): classInitNative: succeeds
D/UsbSettingsControl( 6214): [AUTORUN] getUsbConnected() : connected=true
D/LGBluetoothAPIService( 1928): [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
D/UsbSettingsReceiver( 6214): [AUTORUN] onReceive() : availableList=[wlan0]
D/UsbSettingsReceiver( 6214): [AUTORUN] onReceive() : activeList=[]
D/UsbSettingsReceiver( 6214): [AUTORUN] onReceive() : errorList=[]
D/UsbSettingsControl( 6214): [AUTORUN] isAutorunTimer() : mAutorunChanging=false
D/UsbSettingsReceiver( 6214): [AUTORUN] onReceive() : TetherState Changed=wlan0
D/UsbSettingsControl( 6214): [AUTORUN] setTetherStatus() : status=false
I/[SystemUI]BluetoothHandler( 1468): Receive : BluetoothAdapter.ACTION_STATE_CHANGED
I/ActivityManager( 1031): Killing 5453:com.android.contacts/u0a19 (adj 15): empty #17
,I/wpa_supplicant( 6231): [LGE_WLAN_PATCH]P2P 5GHz support level:2(0:no 1:gconly 2:gconly_UNII1 3:full)
,W/libprocessgroup( 1031): failed to open /acct/uid_10019/pid_5453/cgroup.procs: No such file or directory
I/wpa_supplicant( 6231): p2p0: CTRL-EVENT-AVOID-FREQ ranges=
I/wpa_supplicant( 6231): wlan0: CTRL-EVENT-SCAN-STARTED 
,D/BluetoothBondStateMachine( 6188): make
V/BluetoothPbapReceiver( 6188): PbapReceiver onReceive 
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
D/UsbSettingsReceiver( 6214): [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
D/UsbSettingsReceiver( 6214): [AUTORUN] sys.usb.config = ptp_only,adb
,D/UsbSettingsReceiver( 6214): [AUTORUN] sys.usb.state = ptp_only,adb
E/WifiStateMachine( 1031):  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
D/UsbSettingsReceiver( 6214): [AUTORUN] persist.sys.usb.config = ptp_only,adb
E/WifiStateMachine( 1031):  DefaultState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1031):  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1031):  DefaultState CMD_TETHER_STATE_CHANGE 0 0
E/WifiMonitor( 1031): WifiMonitor:wlan0 cnt=0 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiStateMachine( 1031):  SupplicantStartingState SUP_CONNECTION_EVENT 0 0
E/WifiMonitor( 1031): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1031): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
D/WifiNative-wlan0( 1031): doString: [DRIVER MACADDR]
D/UsbSettingsReceiver( 6214): [AUTORUN] onReceive() : app userid = 0, current userid = 0
V/BluetoothPbapReceiver( 6188): ***********action = android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothPbapReceiver( 6188): ***********state = 11
D/WifiNative-wlan0( 1031):    returned Macaddr = c4:9a:02:7b:60:ac
D/WifiStateMachine( 1031): MAC Addr from driver = c4:9a:02:7b:60:ac
D/WifiOffDelayIfNotUsed( 1031): setPowerSaveActivated(false)
D/BluetoothAdapterService( 6188): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@125ecfa2
D/LGBluetoothServiceAdapter( 6188): [BTUI] check adapter is available - false.
D/BluetoothAdapterService( 6188): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@125ecfa2
D/LGBluetoothServiceAdapter( 6188): [BTUI] check adapter is available - true : set adapter available.
I/BluetoothBondStateMachine( 6188): StableState(): Entering Off State
D/LGBluetoothSettingsDBObserver( 6188): [BTUI] register observer for LG device name DB
D/UsbSettingsControl( 6214): [AUTORUN] getUsbConnected() : connected=true
D/UsbSettingsReceiver( 6214): [AUTORUN] onReceive() : availableList=[]
D/UsbSettingsReceiver( 6214): [AUTORUN] onReceive() : activeList=[]
D/UsbSettingsReceiver( 6214): [AUTORUN] onReceive() : errorList=[]
D/UsbSettingsControl( 6214): [AUTORUN] isAutorunTimer() : mAutorunChanging=false
D/UsbSettingsControl( 6214): [AUTORUN] setTetherStatus() : status=false
E/BluetoothAdapterService( 6188): File transfer profiles supported!!
,I/ActivityManager( 1031): Start proc com.lge.lifetracker for broadcast com.lge.lifetracker/.receiver.HealthDeviceReceiver: pid=6253 uid=10037 gids={50037, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
E/WifiStateMachine( 1031): Couldn't get getWiFiOffloadingIface : 
E/WifiStateMachine( 1031): useWiFiOffloading() : false
E/WifiStateMachine( 1031): CONFIG_LGE_WLAN_PATH : true
,D/WifiNative-wlan0( 1031): doBoolean: SET update_config 1
W/Settings( 1031): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1031): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WfdService( 1928): Waiting for WifiP2p enabling
D/StatusBar.NetworkController( 1468): refreshViews: Data not connected!! Set no data type icon / Roaming
I/WifiServerServiceExt( 1031): WIFI_STATE_CHANGED_ACTION [3]
D/WifiNative-wlan0( 1031): SET update_config 1: returned true
D/WifiConfigStore( 1031): Loading config and enabling all networks 
D/WifiNative-wlan0( 1031): doString: [LIST_NETWORKS]
D/WifiNative-wlan0( 1031):    returned network id / ssid / bssid / flags 0	NG700	any	
I/WifiServerServiceExt( 1031): batteryPsActivateMsgHandler : state:0 event:3
E/BluetoothAdapterService( 6188): File transfer profiles supported!!
E/WifiConfigStore( 1031): readNetworkVariablesFromSupplicantFile key=psk
,E/WifiConfigStore( 1031): readNetworkVariableFromSupplicantFile ssid=["NG700"] key=psk
E/WifiConfigStore( 1031): Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
I/ActivityManager( 1031): Start proc com.lge.formmanager for broadcast com.lge.formmanager/.FormServiceReceiver: pid=6270 uid=10026 gids={50026, 9997, 3003, 1028} abi=armeabi-v7a
,D/WifiStateMachine( 1031): enableVerboseLogging : level 2
D/WifiNative-wlan0( 1031): doBoolean: SET device_name g3_global_com
D/BluetoothHeadset( 1838): Proxy object connected
D/WifiNative-wlan0( 1031): SET device_name g3_global_com: returned true
D/WifiNative-wlan0( 1031): doBoolean: SET manufacturer LGE
D/WifiNative-wlan0( 1031): SET manufacturer LGE: returned true
D/WifiNative-wlan0( 1031): doBoolean: SET model_name LG-D855
D/BluetoothHeadset( 1838): Proxy object connected
D/WifiNative-wlan0( 1031): SET model_name LG-D855: returned true
D/BluetoothHeadset( 1838): Proxy object connected
D/WifiNative-wlan0( 1031): doBoolean: SET model_number LG-D855
D/BluetoothHeadset( 1031): Proxy object connected
,D/WifiNative-wlan0( 1031): SET model_number LG-D855: returned true
D/WifiNative-wlan0( 1031): doBoolean: SET serial_number LGD8553bed2d08
D/WifiNative-wlan0( 1031): SET serial_number LGD8553bed2d08: returned true
D/HeadsetService( 6188): Received start request. Starting profile...
D/WifiNative-wlan0( 1031): doBoolean: SET config_methods physical_display virtual_push_button
D/WifiNative-wlan0( 1031): SET config_methods physical_display virtual_push_button: returned true
D/WifiNative-wlan0( 1031): doBoolean: SET device_type 10-0050F204-5
D/WifiNative-wlan0( 1031): SET device_type 10-0050F204-5: returned true
I/LGBluetoothHeadsetServiceJni( 6188): classInitNative: succeeds
D/LGBluetoothHfpAdapter( 6188): Version 1.6
E/BluetoothAdapterService( 6188): File transfer profiles supported!!
D/WifiStateMachine( 1031): Setting OUI to DA-A1-19
D/WifiNative-wlan0( 1031): doBoolean: SCAN_INTERVAL 120
D/WifiNative-wlan0( 1031): SCAN_INTERVAL 120: returned true
D/WifiNative-HAL( 1031): Setting external_sim to 1
D/WifiNative-wlan0( 1031): doBoolean: SET external_sim 1
D/WifiNative-wlan0( 1031): SET external_sim 1: returned true
I/WifiNative-HAL( 1031): startHal
E/wifi    ( 1031): getStaticLongField sWifiHalHandle 0x989338dc
E/WifiHAL ( 1031): Could not connect handle
D/wifi    ( 1031): halHandle = 0x0, mVM = 0xb487c280, mCls = 0x301cba
I/WifiNative-HAL( 1031): Could not start hal
D/WifiStateMachine( 1031): Setting OUI to DA-A1-19
I/WifiNative-HAL( 1031): startHal
,E/wifi    ( 1031): getStaticLongField sWifiHalHandle 0x9893385c
E/WifiHAL ( 1031): Could not connect handle
D/wifi    ( 1031): halHandle = 0x0, mVM = 0xb487c280, mCls = 0x201cb6
I/WifiNative-HAL( 1031): Could not start hal
D/WifiNative-wlan0( 1031): doBoolean: STA_AUTOCONNECT 1
D/WfdsService( 1928): Supplicant Connection state is changed : true
W/Settings( 5991): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WfdsService( 1928): DefaultState - WIFI_SUPPLICANT_CONNECTED
D/WfdsService( 1928): Set the WFDS Monitor: true
D/WifiNative-wlan0( 1031): STA_AUTOCONNECT 1: returned true
D/WifiNative-wlan0( 1031): doBoolean: DRIVER BTCOEXSCAN-STOP
I/wpa_supplicant( 6231): wpa_driver_nl80211_ext_driver_cmd BTCOEXSCAN-STOP
D/WifiNative-wlan0( 1031): DRIVER BTCOEXSCAN-STOP: returned true
D/WifiNative-wlan0( 1031): doBoolean: DRIVER RXFILTER-STOP
D/LGBluetoothFeatureConfig( 6188): isPrivacyLogsEnabled : true
I/wpa_supplicant( 6231): wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
D/WifiNative-wlan0( 1031): DRIVER RXFILTER-STOP: returned true
D/WifiNative-wlan0( 1031): doBoolean: DRIVER RXFILTER-REMOVE 3
I/wpa_supplicant( 6231): wpa_driver_nl80211_ext_driver_cmd RXFILTER-REMOVE 3
D/WifiNative-wlan0( 1031): DRIVER RXFILTER-REMOVE 3: returned true
D/WifiNative-wlan0( 1031): doBoolean: DRIVER RXFILTER-START
I/wpa_supplicant( 6231): wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
D/WifiHS20( 1031): hidePasspointNotification off =false
D/WifiNative-wlan0( 1031): DRIVER RXFILTER-START: returned true
D/WifiNative-wlan0( 1031): doBoolean: DRIVER RXFILTER-STOP
I/wpa_supplicant( 6231): wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
I/BluetoothHeadsetServiceJni( 6188): classInitNative: succeeds
D/WifiNative-wlan0( 1031): DRIVER RXFILTER-STOP: returned true
D/WifiNative-wlan0( 1031): doBoolean: DRIVER RXFILTER-REMOVE 2
I/wpa_supplicant( 6231): android_multicast_filter_startstop : multicast filter set
D/WfdsMonitor( 1928): WfdsMonitorThread create
D/HeadsetStateMachine( 6188): make
D/WifiNative-wlan0( 1031): DRIVER RXFILTER-REMOVE 2: returned true
D/WifiNative-wlan0( 1031): doBoolean: DRIVER RXFILTER-START
I/wpa_supplicant( 6231): wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
D/WfdsMonitor( 1928): WFDS Monitor is created and started
D/WfdsService( 1928): WiFi: Supplicant connection re-established
D/WifiNative-wlan0( 1031): DRIVER RXFILTER-START: returned true
E/BluetoothAdapterService( 6188): File transfer profiles supported!!
E/WifiNative: ( 1031): [229,333,818 us] RECONNECT  stack:logDbg - reconnect - enter - invokeEnterMethods - performTransitions
D/WifiNative-wlan0( 1031): doBoolean: RECONNECT
D/WifiNative-wlan0( 1031): RECONNECT: returned true
D/WifiNative-wlan0( 1031): doString: [STATUS]
D/WifiNative-wlan0( 1031):    returned wpa_state=SCANNING p2p_device_address=02:9a:02:7b:60:ac address=c4:9a:02:7b:60:ac uuid=530d3fd0-1ba3-5409-a336-ff4e42af59a2
D/WifiNative-wlan0( 1031): doBoolean: DRIVER SETSUSPENDMODE 1
I/wpa_supplicant( 6231): wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 1
D/WifiNative-wlan0( 1031): DRIVER SETSUSPENDMODE 1: returned true
D/WifiNative-wlan0( 1031): doBoolean: SET ps 1
D/WifiNative-wlan0( 1031): SET ps 1: returned true
D/LGWifiP2pService( 1031): P2pDisabledState{ when=0 what=131203 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiStateMachine( 1031):  DisconnectedState CMD_SET_OPERATIONAL_MODE 1 0
E/WifiStateMachine( 1031):  DisconnectedState CMD_START_DRIVER 0 0
E/WifiStateMachine( 1031):  ConnectModeState CMD_START_DRIVER 0 0
I/StatusBar.NetworkController( 1468): networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
E/CtrlSupplicant( 1928): Access OK "@android:wpa_wlan0"
I/StatusBar.NetworkController( 1468): mWifiConnected = false, mWifiLevel = 0
D/WifiMonitor( 1031): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANG,E id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
E/WifiMonitor( 1031): WifiMonitor:wlan0 cnt=1 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
E/CtrlSupplicant( 1928): Succeed to open control connection
E/CtrlSupplicant( 1928): Succeed to open monitor connection
D/WfdsMonitor( 1928): Supplicant connection established
D/WfdsService( 1928): Connected to the supplicant for wfds
W/Settings( 1031): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
E/WifiStateMachine( 1031):  DriverStartedState CMD_START_DRIVER 0 0
W/Settings( 1031): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1031): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
D/WifiScanningService( 1031): SCAN_AVAILABLE : 3
D/RttService( 1031): SCAN_AVAILABLE : 3
D/WifiScanningService( 1031): DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
I/WifiNative-HAL( 1031): startHal
E/wifi    ( 1031): getStaticLongField sWifiHalHandle 0x94f6b99c
E/WifiStateMachine( 1031):  DisconnectedState what:132106 1 0
E/WifiHAL ( 1031): Could not connect handle
D/wifi    ( 1031): halHandle = 0x0, mVM = 0xb487c280, mCls = 0x401c7e
I/WifiNative-HAL( 1031): Could not start hal
E/WifiScanningService( 1031): could not start HAL
E/WifiStateMachine( 1031):  ConnectModeState what:132106 1 0
E/WifiStateMachine( 1031):  DriverStartedState what:132106 1 0
I/WifiServerServiceExt( 1031): setWifiDualbandAPConnection band : 1
D/RttService( 1031): DefaultState got{ when=-1ms what=160512 target=com.android.internal.util.StateMachine$SmHandler }
E/wpa_supplicant( 6231): nWIFIDualbandAPConnection: 1
D/CommandListener(  335): Setting iface cfg
D/CommandListener(  335): Trying to bring up p2p0
D/WifiMonitor( 1031): startMonitoring(p2p0) with mConnected = true
D/LGWifiP2pService( 1031): P2pEnablingState
D/LGWifiP2pService( 1031): P2pEnablingState{ when=0 what=147457 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1031): P2p socket connection successful
D/LGWifiP2pService( 1031): P2pEnabledState
D/LGWifiP2pService( 1031): sending p2p connection changed broadcast
V/WfdStateTracker( 1928): WfdStateTracker handleDirectStateChangedEvent: 2
D/WfdsService( 1928): WifiP2pState is changed : true
D/WfdsService( 1928): Receive the WFDS_ENABLE Method
D/WfdsService( 1928): Set the WFDS Monitor: true
D/WfdsService( 1928): Connected to the supplicant for wfds
D/WfdsJNI ( 1928): doCommand: WFDS_SET TRUE
D/WifiNative-p2p0( 1031): doBoolean: SET persistent_reconnect 1
E/WifiStateMachine( 1031):  DisconnectedState what:132096 -100 0
I/wpa_supplicant( 6231): WFDS: wfds_supplicant_wfds_cmd: cmd = SET TRUE
E/WifiStateMachine( 1031):  ConnectModeState what:132096 -100 0
E/WifiStateMachine( 1031):  DriverStartedState what:132096 -100 0
I/WifiServerServiceExt( 1031): set CMD_DISCONNECT_RSSI_LVL : -100
E/wpa_supplicant( 6231): disconnect_rssi_lvl: -100
E/WifiStateMachine( 1031):  DisconnectedState CMD_SET_COUNTRY_CODE 1 0 cz
E/WifiStateMachine( 1031):  ConnectModeState CMD_SET_COUNTRY_CODE 1 0 cz
E/WifiStateMachine( 1031):  DriverStartedState CMD_SET_COUNTRY_CODE 1 0 cz
D/WifiNative-wlan0( 1031): doBoolean: DRIVER COUNTRY CZ
D/WifiNative-p2p0( 1031): SET persistent_reconnect 1: returned true
D/WfdsService( 1928): WIFI_P2P_CONNECTION_CHANGED_ACTION
D/WifiNative-p2p0( 1031): doBoolean: SET device_name G3-1
D/WfdsService( 1928): isConnected: false
D/WifiNative-p2p0( 1031): SET device_name G3-1: returned true
D/LGWifiP2pService( 1031): [LGE_P2P] initializeP2pSettings() check postfix
D/LGWifiP2pService( 1031): before postfix = G3-1
E/BluetoothAdapterService( 6188): File transfer profiles supported!!
D/WifiServerServiceExt( 1031): postfix byte check : 4
D/LGWifiP2pService( 1031): after postfix = G3-1
D/WifiNative-p2p0( 1031): doBoolean: SET p2p_ssid_postfix -G3-1
D/StatusBar.NetworkController( 1468): refreshViews: Data not connected!! Set no data type icon / Roaming
D/WfdsJNI ( 1928): doCommand: WFDS_GET_MAC_ADDRESS
I/wpa_supplicant( 6231): WFDS: wfds_supplicant_wfds_cmd: cmd = GET_MAC_ADDRESS
D/WfdsJNI ( 1928): doCommand: IFNAME=wlan0 GET_CAPABILITY channels
D/WfdsService( 1928): selectPreferredScanChannel [36]
D/WfdsService( 1928): STATE : WfdsEnabledState - enter: this device mac 02:9a:02:7b:60:ac
D/WifiNative-p2p0( 1031): SET p2p_ssid_postfix -G3-1: returned true
D/WifiNative-p2p0( 1031): doBoolean: SET device_type 10-0050F204-5
D/WifiNative-p2p0( 1031): SET device_type 10-0050F204-5: returned true
D/WifiNative-p2p0( 1031): doBoolean: SET config_methods virtual_push_button physical_display keypad
E/BluetoothAdapterService( 6188): File transfer profiles supported!!
D/WifiNative-p2p0( 1031): SET config_methods virtual_push_button physical_display keypad: returned true
D/WifiNative-p2p0( 1031): doBoolean: P2P_SET conc_pref p2p
E/BluetoothAdapterService( 6188): File transfer profiles supported!!
D/WifiNative-p2p0( 1031): P2P_SET conc_pref p2p: returned true
D/WifiNative-HAL( 1031): p2pGetDeviceAddress
D/WifiNative-HAL( 1031): p2pGetDeviceAddress returning 02:9a:02:7b:60:ac
I/wpa_supplicant( 6231): wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
I/wpa_supplicant( 6231): wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
,D/WifiMonitor( 1031): Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
E/WifiMonitor( 1031): WifiMonitor:wlan0 cnt=2 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
E/WifiMonitor( 1031): handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
E/WifiMonitor( 1031): handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
I/wpa_supplicant( 6231): [LGE_PATCH] driver_cmd() country:CZ
I/wpa_supplicant( 6231): p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
D/WfdsMonitor( 1928): Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
D/WifiMonitor( 1031): Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
E/WifiMonitor( 1031): WifiMonitor:p2p0 cnt=3 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
E/WifiMonitor( 1031): handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
E/WifiMonitor( 1031): handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
I/wpa_supplicant( 6231): p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
D/WfdsMonitor( 1928): Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
D/WifiMonitor( 1031): Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
E/WifiMonitor( 1031): WifiMonitor:p2p0 cnt=4 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
E/WifiMonitor( 1031): handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
E/WifiMonitor( 1031): handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
D/WifiService( 1031): New client listening to asynchronous messages
D/LgDataFeature( 6188): LgDataFeature() Constructor: none
D/LgDataFeature( 6188): LgDataFeature() Constructor Done, null
D/WifiNative-wlan0( 1031): DRIVER COUNTRY CZ: returned true
E/WifiStateMachine( 1031):  DisconnectedState CMD_SET_FREQUENCY_BAND 0 0
E/WifiStateMachine( 1031):  ConnectModeState CMD_SET_FREQUENCY_BAND 0 0
E/WifiStateMachine( 1031):  DriverStartedState CMD_SET_FREQUENCY_BAND 0 0
D/WifiNative-wlan0( 1031): doBoolean: DRIVER SETBAND 0
I/wpa_supplicant( 6231): wpa_driver_nl80211_ext_driver_cmd SETBAND 0 - interface name wlan0
I/wpa_supplicant( 6231): wlan0: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
D/WifiMonitor( 1031): Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN]
E/WifiMonitor( 1031): WifiMonitor:wlan0 cnt=5 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
E/WifiMonitor( 1031): handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
E/WifiMonitor( 1031): handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
D/WifiNative-wlan0( 1031): DRIVER SETBAND 0: returned true
D/WifiNative-wlan0( 1031): doBoolean: BSS_FLUSH 0
D/LGWifiP2pService( 1031): DeviceAddress: 02:9a:02:7b:60:ac
D/WifiNative-p2p0( 1031): doBoolean: P2P_FLUSH
D/WifiNative-wlan0( 1031): BSS_FLUSH 0: returned true
V/LGMDMManager( 6188): Create singleton instance
D/WifiNative-p2p0( 1031): P2P_FLUSH: returned true
D/WifiNative-p2p0( 1031): doBoolean: P2P_SERVICE_FLUSH
D/WifiNative-p2p0( 1031): P2P_SERVICE_FLUSH: returned true
D/WifiNative-p2p0( 1031): doString: [LIST_NETWORKS]
D/WifiNative-p2p0( 1031):    returned network id / ssid / bssid / flags
D/WifiNative-p2p0( 1031): doBoolean: SAVE_CONFIG
D/WifiNative-wlan0( 1031): doBoolean: SCAN
I/WfdStateTracker( 1928): handleP2pThisDeviceChanged
D/WfdsService( 1928): WIFI_P2P_THIS_DEVICE_CHANGED_ATCION
D/WfdsService( 1928): Update P2p Interface State: 3
D/HeadsetStateMachine( 6188): max_hf_connections = 1
I/bluedroid-qcom( 6188): get_profile_interface handsfree
I/BluetoothAdapterState( 6188): Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
V/ToneGenerator( 6188): ToneGenerator constructor: streamType=8, volume=1.000000
V/AudioPolicyService(  340): registerClient() client 0xb102abe0, uid 1002
V/AudioPolicyManager(  340): getOutput() device 2, stream 8, samplingRate 0, format 0, channelMask 3, flags 0
V/AudioPolicyManagerEx(  340): AudioPolicyManagerEx: getOutputForDevice
V/AudioPolicyManagerEx(  340): getOutput() returns output 2
V/AudioSystem( 6188): getOutputSamplingRate() no output descriptor for output 2 in gOutputs
V/AudioFlinger(  340): registerClient() client 0xb55815b0, pid 6188
V/AudioSystem(  340): ioConfigChanged() event 0, ioHandle 2
V/AudioSystem(  340): ioConfigChanged() opening already existing output! 2
V/ToneGenerator( 6188): Create Track: 0xb4927680
V/AudioTrack( 6188): set(): streamType 8, sampleRate 0, format 0x1, channelMask 0x1, frameCount 0, flags #4, notificationFrames 0, sessionId 0, transferType 1
V/AudioTrack( 6188): set() streamType 8, sampleRate 0, format 1, frameCount 0, flags 0004
V/AudioSystem( 1031): ioConfigChanged() event 0, ioHandle 2
V/AudioSystem( 1031): ioConfigChanged() opening already existing output! 2
V/AudioPolicyManager(  340): getOutputForAttr() usage=3, content=4, tag= flags=00000000
V/AudioPolicyManager(  340): getOutputForAttr() device 2, samplingRate 0, format 0, channelMask 3, flags 0
V/AudioPolicyManagerEx(  340): AudioPolicyManagerEx: getOutputForDevice
V/AudioPolicyManagerEx(  340): getOutput() returns output 2
V/AudioSystem( 6188): getOutputSamplingRate() no output descriptor for output 2 in gOutputs
V/AudioSystem( 6188): ioConfigChanged() event 0, ioHandle 2
V/AudioSystem( 6188): ioConfigChanged() new output samplingRate 48000, format 0x5 channel mask 0x3 frameCount 960 latency 50
V/AudioSystem( 3252): ioConfigChanged() event 0, ioHandle 2
V/AudioSystem( 3252): ioConfigChanged() opening already existing output! 2
V/AudioSystem(  340): ioConfigChanged() event 0, ioHandle 4
V/AudioSystem(  340): ioConfigChanged() opening already existing output! 4
V/AudioSystem( 1031): ioConfigChanged() event 0, ioHandle 4
V/AudioSystem( 1031): ioConfigChanged() opening already existing output! 4
V/AudioSystem( 1838): ioConfigChanged() event 0, ioHandle 2
V/AudioSystem( 1838): ioConfigChanged() opening already existing output! 2
V/AudioSystem( 1838): ioConfigChanged() event 0, ioHandle 4
V/AudioSystem( 1838): ioConfigChanged() opening already existing output! 4
D/WifiNative-p2p0( 1031): SAVE_CONFIG: returned true
V/AudioSystem( 1468): ioConfigChanged() event 0, ioHandle 2
V/AudioSystem( 1468): ioConfigChanged() opening already existing output! 2
V/AudioSystem( 1468): ioConfigChanged() event 0, ioHandle 4
D/LGWifiP2pService( 1031): sending p2p persistent groups changed broadcast
V/AudioSystem( 1468): ioConfigChanged() opening already existing output! 4
D/LGWifiP2pService( 1031): InactiveState
D/LGWifiP2pService( 1031): InactiveState{ when=-15ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
V/AudioSystem( 3252): ioConfigChanged() event 0, ioHandle 4
V/AudioSystem( 3252): ioConfigChanged() opening already existing output! 4
D/LGWifiP2pService( 1031): P2pEnabledState{ when=-15ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-p2p0( 1031): doBoolean: DRIVER COUNTRY CZ
V/AudioSystem( 6188): ioConfigChanged() event 0, ioHandle 4
V/AudioSystem( 6188): ioConfigChanged() new output samplingRate 48000, format 0x1 channel mask 0x3 frameCount 960 latency 80
I/wpa_supplicant( 6231): wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
I/wpa_supplicant( 6231): p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
I/wpa_supplicant( 6231): [LGE_PATCH] driver_cmd() country:CZ
I/AudioFlinger(  340): isAudioPlaybackHookOn() false
I/wpa_supplicant( 6231): p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
I/wpa_supplicant( 6231): p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
V/AudioPolicyManager(  340): getOutputForAttr() usage=3, content=4, tag= flags=00000000
V/AudioPolicyManager(  340): getOutputForAttr() device 2, samplingRate 48000, format 1, channelMask 1, flags 4
V/AudioPolicyManagerEx(  340): AudioPolicyManagerEx: getOutputForDevice
V/AudioPolicyManagerEx(  340): getOutput() returns output 2
D/WfdsMonitor( 1928): Event [CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
V/AudioSystem( 6188): getLatency() output 2, latency 50
V/AudioSystem( 6188): getFrameCount() output 2, frameCount 960
D/WfdsMonitor( 1928): Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
V/AudioTrack( 6188): createTrack_l() output 2 afLatency 50
D/WfdsMonitor( 1928): Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
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
D/LGWifiP2pService( 1031): InactiveState{ when=-16ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1031): P2pEnabledState{ when=-16ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
V/AudioFlinger(  340): [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
D/LGWifiP2pService( 1031): InactiveState{ when=-4ms what=139287 arg2=1 target=com.android.internal.util.StateMachine$SmHandler }
V/AudioFlinger(  340): [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
V/AudioFlinger(  340): [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
D/LGWifiP2pService( 1031): P2pEnabledState{ when=-4ms what=139287 arg2=1 target=com.android.internal.util.StateMachine$SmHandler }
V/AudioFlinger(  340): [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
V/AudioFlinger(  340): createTrack() lSessionId: 16
D/LGWifiP2pService( 1031): DefaultState{ when=-4ms what=139287 arg2=1 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1031): InactiveState{ when=-4ms what=139285 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1031): P2pEnabledState{ when=-4ms what=139285 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1031): DefaultState{ when=-4ms what=139285 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0( 1031): SCAN: returned false
E/WifiStateMachine( 1031):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 1 0 rt=229405  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
E/WifiStateMachine( 1031):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 1 0 rt=229406  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
D/LGWifiP2pService( 1031): InactiveState{ when=-2ms what=139287 arg2=1 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1031): P2pEnabledState{ when=-2ms what=139287 arg2=1 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1031): DefaultState{ when=-2ms what=139287 arg2=1 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1031): InactiveState{ when=-2ms what=139283 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1031): P2pEnabledState{ when=-2ms what=139283 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1031): DefaultState{ when=-2ms what=139283 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiServerServiceExt( 1031): No p2p device connected
E/WifiStateMachine( 1031):  DisconnectedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
E/WifiStateMachine( 1031):  ConnectModeState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
W/WfdsService( 1928): DefaultState - msg [9441285] is not handled
E/WifiStateMachine( 1031):  DriverStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
V/AudioTrack( 6188): AUDIO_OUTPUT_FLAG_FAST successful; frameCount 480
W/Settings( 1031): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
E/WifiStateMachine( 1031):  SupplicantStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
W/Settings( 1031): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
V/AudioFlinger(  340): acquiring 16 from 6188, for 6188
V/AudioFlinger(  340):  added new entry for 16
D/WifiOffDelayIfNotUsed( 1031): NETWORK_STATE_CHANGED_ACTION [SCANNING]
E/WifiStateMachine( 1031):  DefaultState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
V/ToneGenerator( 6188): ToneGenerator INIT OK, time: 229421
D/BluetoothAdapterService( 6188): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@125ecfa2
I/StatusBar.NetworkController( 1468): networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1468): mWifiConnected = false, mWifiLevel = 0
D/HeadsetStateMachine( 6188): Enter Disconnected: -2, size: 0
D/HeadsetPhoneState( 6188): [BTUI] listenForPhoneState : start = false
D/LGBluetoothHfpManager( 6188): [BTUI] listenForMultiSimPhoneState : start = false
D/HeadsetStateMachine( 6188): [BTUI] change sampling rate to 8000 when device is disconnected
D/BluetoothAdapterService( 6188): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@125ecfa2
D/WifiServerServiceExt( 1031): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1031): setSupplicantStateSCANNING
D/StatusBar.NetworkController( 1468): refreshViews: Data not connected!! Set no data type icon / Roaming
V/AudioFlinger(  340): setParameters(): io 0, keyvalue bt_samplerate=8000, calling pid 6188
D/BluetoothA2dp( 1031): Proxy object connected
D/A2dpService( 6188): Received start request. Starting profile...
I/BluetoothAvrcpServiceJni( 6188): classInitNative: succeeds
V/Avrcp   ( 6188): make
D/Avrcp   ( 6188): [BTUI] Use Native AVRCP : init jni
I/bluedroid-qcom( 6188): get_profile_interface avrcp
,D/audio_hw_primary(  340): adev_set_parameters: enter: bt_samplerate=8000
V/voice   (  340): voice_set_parameters: enter: bt_samplerate=8000
V/compress_voip(  340): voice_extn_compress_voip_set_parameters: enter: bt_samplerate=8000
V/compress_voip(  340): voice_extn_compress_voip_set_parameters: exit
V/voice   (  340): voice_set_parameters: exit with code(0)
V/msm8974_platform_lge(  340): LGE_platform_set_parameters: enter: bt_samplerate=8000
V/msm8974_platform(  340): platform_set_parameters: enter: bt_samplerate=8000
V/msm8974_platform(  340): platform_set_parameters: exit with code(0)
V/lge_audio_loopback(  340): lge_platform_set_loopback_parameters: enter: 
V/audio_hw_primary(  340): adev_set_parameters: exit with code(0)
E/audio_a2dp_hw(  340): adev_set_parameters: ERROR: set param called even when stream out is null
V/ToneGenerator( 6188): ToneGenerator destructor
V/ToneGenerator( 6188): stopTone
V/ToneGenerator( 6188): Delete Track: 0xb4927680
V/AudioTrack( 6188): ~AudioTrack, releasing session id from 6188 on behalf of 6188
V/AudioFlinger(  340): releasing 16 from 6188 for 6188
V/AudioPolicyService(  340): AudioCommandThread() adding release output 2
V/AudioFlinger(  340):  decremented refcount to 0
V/AudioPolicyService(  340): inserting command: 6 at index 0, num commands 0
V/AudioFlinger(  340): purging stale effects
V/AudioPolicyService(  340): AudioCommandThread() waking up
V/AudioPolicyService(  340): AudioCommandThread() processing release output 2
V/AudioPolicyManager(  340): releaseOutput() 2
V/AudioPolicyService(  340): AudioCommandThread() going to sleep
V/AudioFlinger(  340): PlaybackThread::Track destructor
V/AudioFlinger(  340): removeClient_l() pid 6188, calling pid 340
V/AudioManager( 6188): registerRemoteController: size of Media player list: 0
E/AudioManager( 6188): No RCC entry present to update
E/RemoteController( 6188): Cannot set synchronization mode on an unregistered RemoteController
I/BluetoothAvrcpQcomServiceJni( 6188): classInitQcomNative: succeeds
D/LGBluetoothAvrcpQcomAdapter( 6188): [BTUI] Use QCOM AVRCP 1.5 : init jni, browsing = false
I/BluetoothAvrcpQcomServiceJni( 6188): initQcomNative: succeeds
D/LGBluetoothAvrcpQcomAdapter( 6188): [BTUI] [+] updateMediaPlayerInfo
,E/ActivityThread( 6253): Failed to find provider info for com.lge.lgaccount.provider
,W/LG Account v2.2( 6253): No ProfileInfo entries
I/LG Account v2.2( 6253): isEnabled: false
I/Feature ( 6253): [Lifetracker]ver: 4.21.112(40211120)
I/Feature ( 6253): [Lifetracker]Country: EU
I/Feature ( 6253): [Lifetracker]Operator: OPEN
I/Feature ( 6253): [Lifetracker]Ranking support: false
I/Feature ( 6253): [Lifetracker]Comfort support: false
I/Feature ( 6253): [Lifetracker]Accessory: true
I/Feature ( 6253): [Lifetracker]Health device: true
I/Feature ( 6253): [Lifetracker]Extra Pedometer: false
I/Feature ( 6253): [Lifetracker]Blood glucose device: false
I/Feature ( 6253): [Lifetracker]Device Number: 3
V/SIM_STK ( 1031): Menu title from STK is T-Mobile
V/SIM_STK ( 1031): Menu title from STK is T-Mobile
,I/ActivityManager( 1031): Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=6299 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
W/FormManager( 6270): Network not available. Please check & try again.
D/BluetoothPermissionRequest( 6214): onReceive
,D/LGBluetoothFeatureConfig( 6214):  get() - isFeatureLoaded : false
D/BluetoothManagerService( 1031): Message: 20
D/BluetoothManagerService( 1031): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@221cc00:true
V/FormManager( 6270): Network unavailable.
,V/FormManager( 6270): Network unavailable.
D/LGBluetoothResetSettingReceiver( 6214): return without doing reset settings.
I/ActivityManager( 1031): Killing 5773:com.lge.email/u0a23 (adj 15): empty #17
E/wpa_supplicant( 6231): USIM:  scard_init function
E/WifiMonitor( 1031): WifiMonitor:wlan0 cnt=9 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
I/wpa_supplicant( 6231): Trying to associate with SSID 'NG700'
E/WifiMonitor( 1031): handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
,D/WifiMonitor( 1031): Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
E/WifiMonitor( 1031): WifiMonitor:wlan0 cnt=10 dispatchEvent: WPS-AP-AVAILABLE 
E/WifiStateMachine( 1031):  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=0 bcn=0
E/WifiStateMachine( 1031):  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=0 bcn=0
E/WifiStateMachine( 1031):  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=0 bcn=0
E/WifiStateMachine( 1031):  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=0 bcn=0
I/WifiNative-HAL( 1031): startHal
E/wifi    ( 1031): getStaticLongField sWifiHalHandle 0x989338cc
E/WifiHAL ( 1031): Could not connect handle
D/wifi    ( 1031): halHandle = 0x0, mVM = 0xb487c280, mCls = 0xa01f62
I/WifiNative-HAL( 1031): Could not start hal
D/WifiNative-wlan0( 1031): doString: [BSS RANGE=0- MASK=0x21987]
W/WifiMonitor( 1031): couldn't identify event type - WPS-AP-AVAILABLE 
D/WifiMonitor( 1031): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
E/WifiMonitor( 1031): WifiMonitor:wlan0 cnt=11 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
,W/libprocessgroup( 1031): failed to open /acct/uid_10023/pid_5773/cgroup.procs: No such file or directory
,W/ActivityManager( 1031): getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
E/WifiStateMachine( 1031):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 11 0 rt=229646  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
I/StatusBar.NetworkController( 1468): networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1468): mWifiConnected = false, mWifiLevel = 0
D/LGBluetoothAvrcpQcomAdapter( 6188): [BTUI] installed app name: Music
,W/Settings( 1031): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1031): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1031): NETWORK_STATE_CHANGED_ACTION [SCANNING]
I/ActivityManager( 1031): Killing 5478:com.android.gallery3d/u0a27 (adj 15): empty #17
D/LGBluetoothAvrcpQcomAdapter( 6188): [BTUI] installed app name: Google Play Music
D/StatusBar.NetworkController( 1468): refreshViews: Data not connected!! Set no data type icon / Roaming
D/LGBluetoothAvrcpQcomAdapter( 6188): [BTUI] === MediaPlayerInfo (playerId:0) ===
D/LGBluetoothAvrcpQcomAdapter( 6188): [BTUI]          displayName: Music
D/LGBluetoothAvrcpQcomAdapter( 6188): [BTUI]          packageName: com.lge.music
D/LGBluetoothAvrcpQcomAdapter( 6188): [BTUI]          playState: 2 (PAUSED)
D/LGBluetoothAvrcpQcomAdapter( 6188): [BTUI] === MediaPlayerInfo (playerId:1) ===
D/LGBluetoothAvrcpQcomAdapter( 6188): [BTUI]          displayName: Google Play Music
D/LGBluetoothAvrcpQcomAdapter( 6188): [BTUI]          packageName: com.google.android.music
D/LGBluetoothAvrcpQcomAdapter( 6188): [BTUI]          playState: 2 (PAUSED)
D/LGBluetoothAvrcpQcomAdapter( 6188): [BTUI] [-] updateMediaPlayerInfo
I/BluetoothA2dpServiceJni( 6188): classInitNative
I/BluetoothA2dpServiceJni( 6188): classInitNative: succeeds
D/A2dpStateMachine( 6188): make
I/bluedroid-qcom( 6188): get_profile_interface a2dp
I/GKI_LINUX( 6188): gki_task_entry task_id=2 [A2DP-MEDIA] starting
I/LGBluetoothA2dpServiceJni( 6188): classInitNative: succeeds
I/LGBluetoothA2dpAdapter( 6188): [BTUI] getInstance : create [LGBluetoothA2dpAdapter]
D/BluetoothAdapterService( 6188): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@125ecfa2
D/A2dpStateMachine( 6188): Enter Disconnected: -2
,I/BluetoothHidServiceJni( 6188): classInitNative: succeeds
D/HidService( 6188): Received start request. Starting profile...
I/bluedroid-qcom( 6188): get_profile_interface hidhost
D/BluetoothAdapterService( 6188): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@125ecfa2
I/BluetoothHealthServiceJni( 6188): classInitNative: succeeds
D/HealthService( 6188): Received start request. Starting profile...
I/bluedroid-qcom( 6188): get_profile_interface health
I/LGBluetoothHealthServiceJni( 6188): classInitNative: succeeds
D/BluetoothAdapterService( 6188): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@125ecfa2
I/BluetoothPanServiceJni( 6188): classInitNative(L105): succeeds
,D/PanService( 6188): Received start request. Starting profile...
D/BluetoothPanServiceJni( 6188): initializeNative(L110): pan
I/bluedroid-qcom( 6188): get_profile_interface pan
D/PCSuite ( 6299): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,I/wpa_supplicant( 6231): wlan0: Associated with c0:ff:d4:d3:aa:48
D/WifiMonitor( 1031): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
E/WifiMonitor( 1031): WifiMonitor:wlan0 cnt=12 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
D/WifiMonitor( 1031): Event [IFNAME=wlan0 Associated with c0:ff:d4:d3:aa:48]
E/WifiMonitor( 1031): WifiMonitor:wlan0 cnt=13 dispatchEvent: Associated with c0:ff:d4:d3:aa:48
,D/WifiMonitor( 1031): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1031): WifiMonitor:wlan0 cnt=14 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/WifiMonitor( 1031): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1031): WifiMonitor:wlan0 cnt=15 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
I/wpa_supplicant( 6231): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
D/WifiMonitor( 1031): Event [IFNAME=wlan0 WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]]
E/WifiMonitor( 1031): WifiMonitor:wlan0 cnt=16 dispatchEvent: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
W/WifiMonitor( 1031): couldn't identify event type - WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 6231): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
D/WifiMonitor( 1031): Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]]
E/WifiMonitor( 1031): WifiMonitor:wlan0 cnt=17 dispatchEvent: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
E/WifiMonitor( 1031): handleEvent 1  Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
D/WifiMonitor( 1031): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1031): WifiMonitor:wlan0 cnt=18 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
,W/libprocessgroup( 1031): failed to open /acct/uid_10027/pid_5478/cgroup.procs: No such file or directory
E/WifiStateMachine( 1031):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 11 0 rt=229759  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
E/WifiStateMachine( 1031):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 12 0 rt=229759  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
E/WifiStateMachine( 1031):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 12 0 rt=229759  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
E/WifiStateMachine( 1031):  DisconnectedState CMD_ASSOCIATED_BSSID 13 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=229760
E/WifiStateMachine( 1031):  ConnectModeState CMD_ASSOCIATED_BSSID 13 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=229760
,E/WifiStateMachine( 1031):  DriverStartedState CMD_ASSOCIATED_BSSID 13 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=229760
,E/WifiStateMachine( 1031):  SupplicantStartedState CMD_ASSOCIATED_BSSID 13 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=229761
E/WifiStateMachine( 1031):  DefaultState CMD_ASSOCIATED_BSSID 13 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=229761
E/WifiStateMachine( 1031):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 14 0 rt=229761  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: FOUR_WAY_HANDSHAKE
I/LGBluetoothPanAdapter( 6188): [BTUI] getInstance : create [LGBluetoothPanAdapter]
D/BluetoothAdapterService( 6188): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@125ecfa2
D/Tethering( 1031): sendTetherStateChangedBroadcast 1, 0, 0
I/BtGatt.JNI( 6188): classInitNative(L901): classInitNative: Success!
D/BtGatt.DebugUtils( 6188): handleDebugAction() action=null
D/BtGatt.GattService( 6188): Received start request. Starting profile...
D/BtGatt.GattService( 6188): start()
I/bluedroid-qcom( 6188): get_profile_interface gatt
D/BtGatt.AdvertiseManager( 6188): advertise manager created
I/StatusBar.NetworkController( 1468): networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1468): mWifiConnected = false, mWifiLevel = 0
W/Settings( 1031): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1031): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1031): NETWORK_STATE_CHANGED_ACTION [CONNECTING]
D/StatusBar.NetworkController( 1468): refreshViews: Data not connected!! Set no data type icon / Roaming
,E/WifiStateMachine( 1031):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 14 0 rt=229779  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: FOUR_WAY_HANDSHAKE
,E/WifiStateMachine( 1031):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 15 0 rt=229780  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: GROUP_HANDSHAKE
E/WifiStateMachine( 1031):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 15 0 rt=229780  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: GROUP_HANDSHAKE
E/WifiStateMachine( 1031):  DisconnectedState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=229780
E/WifiStateMachine( 1031):  ConnectModeState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=229781
D/WifiNative-wlan0( 1031): doString: [STATUS]
D/WifiMonitor( 1031): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1031): WifiMonitor:wlan0 cnt=19 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/WifiNative-wlan0( 1031):    returned bssid=c0:ff:d4:d3:aa:48 ssid=NG700 id=0 mode=station pairwise_cipher=CCMP group_cipher=CCMP key_mgmt=WPA2-PSK wpa_state=COMPLETED p2p_device_address=02:9a:02:7b:60:ac address=c4:9a:02:7b:60:ac uuid=530d3fd0-1ba3-5409-a336-ff4e42af59a2
D/BluetoothAdapterService( 6188): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@125ecfa2
I/WifiServiceExtension( 1031): setVHTCapabilityType  : false
I/StatusBar.NetworkController( 1468): networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1468): mWifiConnected = false, mWifiLevel = 0
D/BluetoothAdapterService( 6188): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@125ecfa2
I/LGBluetoothMapAdapter( 6188): [BTUI] getInstance : create [LGBluetoothMapAdapter]
D/StatusBar.NetworkController( 1468): refreshViews: Data not connected!! Set no data type icon / Roaming
V/BluetoothMapService( 6188): BluetoothMapBinder()
,D/BluetoothMapService( 6188): Received start request. Starting profile...
,D/BluetoothMapService( 6188): start()
W/Settings( 1031): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1031): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1031): NETWORK_STATE_CHANGED_ACTION [CONNECTING]
I/StatusBar.NetworkController( 1468): networkInfo=[type: WIFI[], state: CONNECTING/AUTHENTICATING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1468): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1468): refreshViews: Data not connected!! Set no data type icon / Roaming
W/Settings( 1031): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1031): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1031): NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
I/WifiServerServiceExt( 1031): wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
I/WifiServerServiceExt( 1031): setKeepAlivePacketInterval msec : 60
D/BluetoothMapEmailSettingsLoader( 6188): Found 0 applications
D/BluetoothMapEmailAppObserver( 6188): createReceiver()
,I/StatusBar.NetworkController( 1468): networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1468): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1468): refreshViews: Data not connected!! Set no data type icon / Roaming
W/Settings( 1031): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1031): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1031): NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
D/BluetoothMapEmailAppObserver( 6188): initObservers()
,D/BluetoothMapEmailAppObserver( 6188): getEnabledAccountItems()
D/BluetoothAdapterService( 6188): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@125ecfa2
,I/StatusBar.NetworkController( 1468): networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1468): mWifiConnected = false, mWifiLevel = 0
W/Settings( 1031): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1031): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1031): NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
D/HeadsetStateMachine( 6188): Proxy object connected
D/LGBluetoothHfpAdapter( 6188): [BTUI] queryPhoneState
D/LGBluetoothHfpAdapter( 6188): Try to query the phonestate on bind
D/StatusBar.NetworkController( 1468): refreshViews: Data not connected!! Set no data type icon / Roaming
D/BluetoothPhoneService.BluetoothLTECall( 1838):  call mBluetoothHeadset.phoneStateChanged()
W/BluetoothHeadset( 1838): Proxy not attached to service
D/BluetoothHeadset( 1838): java.lang.Throwable
D/BluetoothHeadset( 1838): 	at android.bluetooth.BluetoothHeadset.phoneStateChanged(BluetoothHeadset.java:826)
D/BluetoothHeadset( 1838): 	at com.android.phone.BluetoothPhoneService$BluetoothLTECall.handleQueryPhoneState(BluetoothPhoneService.java:1527)
D/BluetoothHeadset( 1838): 	at com.android.phone.BluetoothPhoneService$BluetoothLTECall.access$700(BluetoothPhoneService.java:1360)
D/BluetoothHeadset( 1838): 	at com.android.phone.BluetoothPhoneService$1.handleMessage(BluetoothPhoneService.java:268)
D/BluetoothHeadset( 1838): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/BluetoothHeadset( 1838): 	at android.os.Looper.loop(Looper.java:135)
D/BluetoothHeadset( 1838): 	at android.app.ActivityThread.main(ActivityThread.java:5274)
D/BluetoothHeadset( 1838): 	at java.lang.reflect.Method.invoke(Native Method)
D/BluetoothHeadset( 1838): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/BluetoothHeadset( 1838): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
D/BluetoothHeadset( 1838): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
D/ConnectivityService( 1031): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
D/BluetoothAdapterService( 6188): Profile still not running:com.android.bluetooth.gatt.GattService
D/HeadsetStateMachine( 6188): Disconnected process message: 10, size: 0
D/ConnectivityService( 1031): Got NetworkAgent Messenger
D/LGBluetoothOppAdapter( 6188): [BTUI] getInstance : create [LGBluetoothOppAdapter]
D/ConnectivityService( 1031): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
D/ConnectivityService( 1031): NetworkAgent connected
V/WiFiOffLoadBroadcast( 6214): WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
E/WifiConfigStore( 1031): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/HeadsetPhoneState( 6188): sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
D/WifiNative-wlan0( 1031): doBoolean: SET_NETWORK 0 bssid any
D/HeadsetStateMachine( 6188): Disconnected process message: 11, size: 0
D/WifiNative-wlan0( 1031): SET_NETWORK 0 bssid any: returned true
D/WifiNative-wlan0( 1031): doBoolean: SAVE_CONFIG
,D/BluetoothAdapterService( 6188): Profile still not running:com.android.bluetooth.gatt.GattService
D/BluetoothAdapterService( 6188): Profile still not running:com.android.bluetooth.gatt.GattService
D/BluetoothAdapterService( 6188): Profile still not running:com.android.bluetooth.gatt.GattService
D/BluetoothAdapterService( 6188): Profile still not running:com.android.bluetooth.gatt.GattService
D/WifiNative-wlan0( 1031): SAVE_CONFIG: returned true
V/PanService( 6188): [BTUI] SIM Extra State :ABSENT
E/WifiConfigStore( 1031): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/WifiNative-wlan0( 1031): doBoolean: SET_NETWORK 0 bssid any
D/WifiNative-wlan0( 1031): SET_NETWORK 0 bssid any: returned true
,D/WifiNative-wlan0( 1031): doBoolean: SAVE_CONFIG
D/BluetoothAdapterService( 6188): Profile still not running:com.android.bluetooth.map.BluetoothMapService
V/BluetoothMapService( 6188): Handler(): got msg=1
D/BluetoothAdapterState( 6188): CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
I/bluedroid-qcom( 6188): enable
I/GKI_LINUX( 6188): gki_task_entry task_id=0 [BTU] starting
I/bt-btu  ( 6188): btu_task pending for preload complete event
I/bt_hci_bdroid( 6188): init
D/WifiService( 1031): New client listening to asynchronous messages
D/WifiNative-wlan0( 1031): SAVE_CONFIG: returned true
,D/CommandListener(  335): Setting iface cfg
V/BluetoothFtpReceiver( 6188): BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
I/bt_vendor( 6188): bt-vendor : init
I/bt_vendor( 6188): bt-vendor : get_bt_soc_type
E/bt_vendor( 6188): get_bt_soc_type: Failed to get soc type
I/bt_vendor( 6188): init: Local BD Address : c0:64:73:54:3f:58
D/bt_userial_mct( 6188): userial_init
V/BluetoothSapReceiver( 6188): [BTUI] checkServiceStart
D/DhcpStateMachine( 1031): StoppedState
E/WifiStateMachine( 1031): Start Dhcp Watchdog 1
D/DhcpStateMachine( 1031): StoppedState{ when=0 what=196609 target=com.android.internal.util.StateMachine$SmHandler }
V/BluetoothSapReceiver( 6188): [BTUI] region:EU country:EU
D/DhcpStateMachine( 1031): WaitBeforeStartState
V/BluetoothSapReceiver( 6188): SapReceiver onReceive 
E/WifiStateMachine( 1031):  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 18 0 rt=229851  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine( 1031):  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 18 0 rt=229851  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine( 1031):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 18 0 rt=229852  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
V/BluetoothSapReceiver( 6188): action = android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothSapReceiver( 6188):  Bluetooth Adapter state = 11
D/bt_hci_bdroid( 6188): set_power 1
I/bt_vendor( 6188): bt-vendor : BT_VND_OP_POWER_CTRL: On
I/bt_vendor( 6188): Starting hciattach daemon
W/sh      ( 6336): type=1400 audit(0.0:157): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
W/sh      ( 6336): type=1400 audit(0.0:158): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
I/bt_vendor( 6188): try to set true
D/WifiServerServiceExt( 1031): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1031): setSupplicantStateASSOCIATING
,E/WifiStateMachine( 1031):  ObtainingIpState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1031):  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1031):  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1031):  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1031):  DefaultState CMD_TETHER_STATE_CHANGE 0 0
,I/qcom-bluetooth( 6337): /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  
D/LgDataFeature( 6214): LgDataFeature() Constructor: none
D/LgDataFeature( 6214): LgDataFeature() Constructor Done, null
,I/ActivityManager( 1031): Start proc com.lge.settings.easy for broadcast com.lge.settings.easy/com.lge.settings.bluetooth.LGBluetoothProfileConnectionReceiver: pid=6341 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
E/WifiStateMachine( 1031):  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 19 0 rt=229905  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine( 1031):  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 19 0 rt=229905  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine( 1031):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 19 0 rt=229906  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
D/WifiServerServiceExt( 1031): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1031): setSupplicantStateGROUP_HANDSHAKE
E/WifiStateMachine( 1031):  ObtainingIpState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:-1901769553] from screen [on:0 period:-1901769553]
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-1901769552]
,I/WifiNative-HAL( 1031): startHal
E/wifi    ( 1031): getStaticLongField sWifiHalHandle 0x989338bc
E/WifiHAL ( 1031): Could not connect handle
D/wifi    ( 1031): halHandle = 0x0, mVM = 0xb487c280, mCls = 0x901112
I/WifiNative-HAL( 1031): Could not start hal
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
D/StatusBar.NetworkController( 1468): refreshViews: Data not connected!! Set no data type icon / Roaming
D/ConnectivityService( 1031): updateNetworkScore for NetworkAgentInfo [WIFI () - 100] to 60
E/WifiStateMachine( 1031):  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1031):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1031):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1031):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1031):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
D/ConnectivityService( 1031): Update of LinkProperties for NetworkAgentInfo [WIFI () - 100]; created=false
E/WifiStateMachine( 1031):  ObtainingIpState CMD_PRE_DHCP_ACTION 0 0 txpkts=1,0,0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_PRE_DHCP_ACTION 0 0 txpkts=1,0,0
D/WifiNative-wlan0( 1031): doBoolean: DRIVER SETSUSPENDMODE 0
D/WiFiOffLoadUpdatePriority( 6214): remove : truetruetrue
I/qcom-bluetooth( 6359): /system/etc/init.qcom.bt.sh: Transport : smd 
,I/qcom-bluetooth( 6362): /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
W/ResourcesManager( 6341): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,I/wpa_supplicant( 6231): wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 0
D/WifiNative-wlan0( 1031): DRIVER SETSUSPENDMODE 0: returned true
D/WifiNative-wlan0( 1031): doBoolean: SET ps 0
D/WifiNative-wlan0( 1031): SET ps 0: returned true
D/WifiNative-wlan0( 1031): doBoolean: DRIVER BTCOEXMODE 1
I/wpa_supplicant( 6231): wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 1
D/WifiNative-wlan0( 1031): DRIVER BTCOEXMODE 1: returned true
D/LGWifiP2pService( 1031): InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@68c84b6 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiStateMachine( 1031): CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
D/LGWifiP2pService( 1031): P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@68c84b6 target=com.android.internal.util.StateMachine$SmHandler }
V/DhcpStateMachine( 1031): Current State is mWaitBeforeStartState.
D/DhcpStateMachine( 1031): WaitBeforeStartState{ when=0 what=196615 target=com.android.internal.util.StateMachine$SmHandler }
V/LgDhcpStateMachineHelper( 1031): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
V/LgDhcpStateMachineHelper( 1031): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700" is not exist.
D/DhcpStateMachine( 1031): DHCP Start wake lock is acquired.
D/WifiServerServiceExt( 1031): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1031): setSupplicantStateCOMPLETED
E/WifiStateMachine( 1031):  ObtainingIpState CMD_GET_CONFIGURED_NETWORKS uid=1000 1000 0 num=1
E/WifiStateMachine( 1031):  L2ConnectedState CMD_GET_CONFIGURED_NETWORKS uid=1000 1000 0 num=1
E/WifiStateMachine( 1031):  ConnectModeState CMD_GET_CONFIGURED_NETWORKS uid=1000 1000 0 num=1
E/WifiStateMachine( 1031):  ObtainingIpState CMD_SAVE_CONFIG uid=1000 0 0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_SAVE_CONFIG uid=1000 0 0
E/WifiStateMachine( 1031):  ConnectModeState CMD_SAVE_CONFIG uid=1000 0 0
D/WifiNative-wlan0( 1031): doBoolean: SAVE_CONFIG
I/ActivityManager( 1031): Killing 5149:com.wsandroid.suite.lge/1000 (adj 15): empty #17
,D/WifiNative-wlan0( 1031): SAVE_CONFIG: returned true
D/WiFiOffLoadUpdatePriority( 6214): remove1
V/WiFiOffLoadSharedPrefsUtils( 6214): save remove
I/qcom-bluetooth( 6364): /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
D/WiFiOffLoadBroadcast( 6214): mLastConnectedNetwork from SharedPrefsUtils for wifioffloading : null
D/WiFiOffLoadBroadcast( 6214): S: false, R: false
E/WifiStateMachine( 1031):  ObtainingIpState CMD_GET_CONFIGURED_NETWORKS uid=1000 1000 0 num=1
E/WifiStateMachine( 1031):  L2ConnectedState CMD_GET_CONFIGURED_NETWORKS uid=1000 1000 0 num=1
E/WifiStateMachine( 1031):  ConnectModeState CMD_GET_CONFIGURED_NETWORKS uid=1000 1000 0 num=1
D/WiFiOffLoadUpdatePriority( 6214): saved SSID: "NG700"
D/WiFiOffLoadUpdatePriority( 6214): connected SSID: null
D/WiFiOffLoadUpdatePriority( 6214): private wpa: "NG700" 300
D/WifiServiceImplEx( 1031): addOrUpdateNetwork pid=6214, uid=1000, packageName=android.uid.system:1000
,I/qcom-bluetooth( 6365): /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> 
E/addOrUpdateNetwork( 1031):  uid = 1000 SSID "NG700" nid=0
E/WifiStateMachine( 1031):  ObtainingIpState CMD_ADD_OR_UPDATE_NETWORK uid=1000 0 0 "NG700"WPA_PSK prio=300 status=2 any is current
E/WifiStateMachine( 1031):  L2ConnectedState CMD_ADD_OR_UPDATE_NETWORK uid=1000 0 0 "NG700"WPA_PSK prio=300 status=2 any is current
E/WifiStateMachine( 1031):  ConnectModeState CMD_ADD_OR_UPDATE_NETWORK uid=1000 0 0 "NG700"WPA_PSK prio=300 status=2 any is current
E/WifiConfigStore( 1031):  key="NG700"WPA_PSK netId=0 uid=0/1000
D/WifiServerServiceExt( 1031): addOrUpdateNetwork: mThisIsFirstEnableing = false
D/WifiNative-wlan0( 1031): doBoolean: SET_NETWORK 0 ssid 4e47373030
I/qcom-bluetooth( 6366): /system/etc/init.qcom.bt.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
D/WifiNative-wlan0( 1031): SET_NETWORK 0 ssid 4e47373030: returned true
,E/WifiConfigStore( 1031): Setting BSSID for "NG700"WPA_PSK to any
D/WifiNative-wlan0( 1031): doBoolean: SET_NETWORK 0 bssid any
I/qcom-bluetooth( 6367): /system/etc/init.qcom.bt.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> 
D/WifiNative-wlan0( 1031): SET_NETWORK 0 bssid any: returned true
D/WifiNative-wlan0( 1031): doBoolean: SET_NETWORK 0 key_mgmt WPA-PSK
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
I/libmdmdetect( 6369): ESOC framework not supported
E/Diag_Lib( 6369):  Diag_LSM_Init: Failed to open handle to diag driver, error = 13
,D/bthci_qcomm_linux( 6369): [BTUI] bt_hci_qcomm_pfal_get_bdaddress: Get BDADDR from bluedroid prop (58:3F:54:73:64:C0)
D/bthci_qcomm_common( 6369): [BTUI] bt_hci_qcomm_init:
D/bthci_qcomm_common( 6369): [BTUI]     BDADDR: 58:3F:54:73:64:C0
,D/bthci_qcomm_common( 6369): [BTUI]     BR/EDR: Class 1
D/bthci_qcomm_common( 6369): [BTUI]     LE: Class 2
D/bthci_qcomm_common( 6369): [BTUI]     Ref Clock: 32M
D/btqsocnvmtags( 6369): [BTUI] init_riva_entries: set NORMAL power settings
W/libprocessgroup( 1031): failed to open /acct/uid_1000/pid_5149/cgroup.procs: No such file or directory
,D/AuthorizationBluetoothService( 2057): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
D/WiFiOffLoadUpdatePriority( 6214):  ssid "NG700" prio 300
D/WiFiOffLoadUpdatePriority( 6214): configuration updated: 0
E/WifiStateMachine( 1031):  ObtainingIpState CMD_SAVE_CONFIG uid=1000 0 0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_SAVE_CONFIG uid=1000 0 0
E/WifiStateMachine( 1031):  ConnectModeState CMD_SAVE_CONFIG uid=1000 0 0
D/WifiNative-wlan0( 1031): doBoolean: SAVE_CONFIG
D/WifiNative-wlan0( 1031): SAVE_CONFIG: returned true
D/WiFiOffLoadUpdatePriority( 6214): configuration saved: true
,I/ActivityManager( 1031): Killing 5674:com.android.defcontainer/u0a4 (adj 15): empty #17
I/rmt_storage(  333): rmt_storage_connect_cb: clnt_h=0x5 conn_h=0xb6403090
I/rmt_storage(  333): rmt_storage_rw_iovec_cb: /boot/modem_fs2: clnt_h=0x2: req_h=0x9 msg_id=3: R/W request received
I/rmt_storage(  333): wakelock acquired: 1, error no: 42
I/rmt_storage(  333): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 Unblock worker thread (th_id: -1236806912)
,D/DhcpStateMachine( 1031): DHCPV4 request on wlan0,
,V/LgDhcpStateMachineHelper( 1031): [bssid] hash key :c0:ff:d4:d3:aa:48
D/LgDhcpStateMachineHelper( 1031): dhcp.ap.macaddress = c0:ff:d4:d3:aa:48
W/dhcpcd  ( 6371): type=1400 audit(0.0:159): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,W/dhcpcd  ( 6371): type=1400 audit(0.0:160): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
I/rmt_storage(  333): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0x9 msg_id=3: Bytes written = 1572864
I/rmt_storage(  333): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0x9 msg_id=3: Send response: res=0 err=0
,I/rmt_storage(  333): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 About to block rmt_storage client thread (th_id: -1236806912) wakelock released: 1, error no: 0
I/rmt_storage(  333): 
I/rmt_storage(  333): rmt_storage_disconnect_cb: clnt_h=0x0x5 conn_h=0x0xb6403090
E/Diag_Lib(  886): [IMS_FATAL]| 3347 | 910 |ims-rtp-daemon ims_rtp_qmi_handler_thread_func waiting on select thread>
I/dhcpcd  ( 6371): version 5.5.6 starting
E/dhcpcd  ( 6371): get_duid: m
D/dhcpcd  ( 6371): wlan0: using ClientID 01:c4:9a:02:7b:60:ac
D/dhcpcd  ( 6371): wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason PREINIT
W/libprocessgroup( 1031): failed to open /acct/uid_10004/pid_5674/cgroup.procs: No such file or directory
,D/PCSuite ( 6299): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,V/WiFiOffLoadBroadcast( 6214): WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
W/FormManager( 6270): Network not available. Please check & try again.
,D/WiFiOffLoadBroadcast( 6214): MCCMNC not supported: null
V/FormManager( 6270): Network unavailable.
D/LGDMClient( 3943): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
D/LGDMClient( 3943): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
W/ContextImpl( 3943): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,W/ContextImpl( 3943): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
V/FormManager( 6270): Network unavailable.
D/LGDMClient( 3943): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=3, isUserType=1
D/dhcpcd  ( 6371): getUsingAPMacAddress: c0:ff:d4:d3:aa:48 , return 1
D/dhcpcd  ( 6371): [read_lease] unlink /data/misc/dhcp/dhcpcd-wlan0.lease, link /data/misc/dhcp/dhcpcd-wlan0-c0:ff:d4:d3:aa:48.lease2
,D/dhcpcd  ( 6371): wlan0: reading lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
D/LGDMClient( 3943): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
D/LGDMClient( 3943): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
,I/dhcpcd  ( 6371): wlan0: rebinding lease of 192.168.1.141
D/dhcpcd  ( 6371): wlan0: sending REQUEST (xid 0x5a03f83c), next in 3.77 seconds
I/ActivityManager( 1031): Start proc com.wsandroid.suite.lge for broadcast com.wsandroid.suite.lge/com.wavesecure.core.WSAndroidSystemIntentReceiver: pid=6386 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,W/ResourcesManager( 6386): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,D/PluginManager( 6386): init()
,W/ExternalStrings( 6386): load override strings
W/ExternalStrings( 6386): java.lang.RuntimeException: Unexpected tag, got eat-comment
W/ExternalStrings( 6386): 	at com.mcafee.plugin.af.a(Unknown Source)
W/ExternalStrings( 6386): 	at com.mcafee.plugin.ac.b(Unknown Source)
W/ExternalStrings( 6386): 	at com.mcafee.plugin.ak.d(Unknown Source)
W/ExternalStrings( 6386): 	at com.mcafee.plugin.ak.a(Unknown Source)
W/ExternalStrings( 6386): 	at com.mcafee.app.s.getClassLoader(Unknown Source)
W/ExternalStrings( 6386): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5001)
W/ExternalStrings( 6386): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4609)
W/ExternalStrings( 6386): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4549)
W/ExternalStrings( 6386): 	at android.app.ActivityThread.access$1500(ActivityThread.java:148)
W/ExternalStrings( 6386): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1344)
W/ExternalStrings( 6386): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/ExternalStrings( 6386): 	at android.os.Looper.loop(Looper.java:135)
W/ExternalStrings( 6386): 	at android.app.ActivityThread.main(ActivityThread.java:5274)
W/ExternalStrings( 6386): 	at java.lang.reflect.Method.invoke(Native Method)
W/ExternalStrings( 6386): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/ExternalStrings( 6386): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
W/ExternalStrings( 6386): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
,D/StatusProvider( 6386): onCreate
V/Signer  ( 6386): override build config not found
D/Signer  ( 6386): value of property debug is false
,D/LGMDMWrapper( 6386): Found class 'com.mcafee.lgmdm.LGMDMWrapper$DataWipe'.
D/LGMDMWrapper( 6386): Found class 'com.mcafee.lgmdm.LGMDMWrapper$DownloadMode'.
D/LGMDMWrapper( 6386): Found class 'com.mcafee.lgmdm.LGMDMWrapper$HardReset'.
,D/LGMDMWrapper( 6386): Found class 'com.mcafee.lgmdm.LGMDMWrapper$HardwareKeyReset'.
D/LGMDMWrapper( 6386): Found class 'com.mcafee.lgmdm.LGMDMWrapper$RemoveDeviceAdmin'.
D/LGMDMWrapper( 6386): Found class 'com.mcafee.lgmdm.LGMDMWrapper$UnknownSourceInstallation'.
D/LGMDMWrapper( 6386): Found class 'com.mcafee.lgmdm.LGMDMWrapper$Usb'.
D/LGMDMWrapper( 6386): Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbDebugging'.
D/LGMDMWrapper( 6386): Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbHostStorage'.
D/LGMDMWrapper( 6386): Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbMediaTransfer'.
D/LGMDMWrapper( 6386): Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbPictureTransfer'.
D/LGMDMWrapper( 6386): Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbStorage'.
D/LGMDMWrapper( 6386): Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbTethering'.
V/LGMDMManager( 6386): Create singleton instance
D/LGMDMWrapper( 6386): LG MDM library v4.0.0 is available on this device.
,W/ContextImpl( 6386): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
D/PostponalbeReceiver( 6386): WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,I/PCSuite ( 6299): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
,D/PCSuite ( 6299): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 6299): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 6214): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 6214): MCCMNC not supported: null
D/QRemote ( 5941): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 5941): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 5941): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
V/[BNRBootReceiver]( 5905): boot receiver action = android.net.wifi.p2p.CONNECTION_STATE_CHANGE
D/BNRAndroBeam( 5905): [BnR DirectBeam] Android Direct Beam(NFC) Connection changed
V/[BNRBootReceiver]( 5905): Boot Receiver Return
,E/WifiStateMachine( 1031):  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1031):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1031):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1031):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1031):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
D/ConnectivityService( 1031): Update of LinkProperties for NetworkAgentInfo [WIFI () - 100]; created=false
,D/PostponalbeReceiver( 6386): WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,W/ContextImpl( 6386): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
W/ActivityThread( 6386): ClassLoader.getResources: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,V/WiFiOffLoadBroadcast( 6214): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6214): MCCMNC not supported: null
D/QRemote ( 5941): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 5941): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 5941): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
V/WiFiOffLoadBroadcast( 6214): WiFiOffLoadBroadcast: android.net.wifi.SCAN_RESULTS
D/WiFiOffLoadBroadcast( 6214): Not supported operator for automatic switch
D/PostponalbeReceiver( 6386): WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
W/ContextImpl( 6386): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
,V/WiFiOffLoadBroadcast( 6214): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 6214): MCCMNC not supported: null
D/QRemote ( 5941): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,D/QRemote ( 5941): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 5941): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
E/QC-QMI  ( 6369): qmi_client [6369] 13: failed to locate client data
E/QC-QMI  (  471): qmuxd: RX on fd=32 returned error=0 errno[2:No such file or directory]
E/QC-QMI  (  471): QMUX qmux_client_id=13 not found in qmux client list, unable to remove
D/PostponalbeReceiver( 6386): WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
W/ContextImpl( 6386): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
V/WiFiOffLoadBroadcast( 6214): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6214): MCCMNC not supported: null
D/QRemote ( 5941): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 5941): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 5941): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
D/UsbSettingsReceiver( 6214): [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
D/UsbSettingsReceiver( 6214): [AUTORUN] sys.usb.config = ptp_only,adb
D/UsbSettingsReceiver( 6214): [AUTORUN] sys.usb.state = ptp_only,adb
D/UsbSettingsReceiver( 6214): [AUTORUN] persist.sys.usb.config = ptp_only,adb
D/UsbSettingsReceiver( 6214): [AUTORUN] onReceive() : app userid = 0, current userid = 0
,D/UsbSettingsControl( 6214): [AUTORUN] getUsbConnected() : connected=true
D/UsbSettingsReceiver( 6214): [AUTORUN] onReceive() : availableList=[wlan0]
D/UsbSettingsReceiver( 6214): [AUTORUN] onReceive() : activeList=[]
D/UsbSettingsReceiver( 6214): [AUTORUN] onReceive() : errorList=[]
D/UsbSettingsControl( 6214): [AUTORUN] isAutorunTimer() : mAutorunChanging=false
D/UsbSettingsReceiver( 6214): [AUTORUN] onReceive() : TetherState Changed=wlan0
D/UsbSettingsControl( 6214): [AUTORUN] setTetherStatus() : status=false
D/PostponalbeReceiver( 6386): WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
W/ContextImpl( 6386): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
V/WiFiOffLoadBroadcast( 6214): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,I/qcom-bluetooth( 6425): /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 58:3f:54:73:64:c0 
D/WiFiOffLoadBroadcast( 6214): MCCMNC not supported: null
I/qcom-bluetooth( 6426): /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,D/QRemote ( 5941): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 5941): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 5941): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
D/PostponalbeReceiver( 6386): WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
W/ContextImpl( 6386): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
,V/WiFiOffLoadBroadcast( 6214): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6214): MCCMNC not supported: null
D/QRemote ( 5941): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 5941): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 5941): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
D/PostponalbeReceiver( 6386): WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
W/ContextImpl( 6386): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
,V/WiFiOffLoadBroadcast( 6214): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 6214): MCCMNC not supported: null
,I/bt_vendor( 6188): bluetooth satus is on
D/bt_hci_bdroid( 6188): preload
D/bt_userial_mct( 6188): userial_open(port:0)
I/bt_vendor( 6188): bt-vendor : BT_VND_OP_USERIAL_OPEN
I/bt_vendor( 6188): Done intiailizing UART
I/bt_vendor( 6188): Done intiailizing UART
I/bt_userial_mct( 6188): CMD=66, EVT=66, ACL_Out=67, ACL_In=67
I/bt_vendor( 6188): Bluetooth Firmware and transport layer are initialized
D/bt_userial_mct( 6188): Entering userial_read_thread()
I/bt-btu  ( 6188): btu_task received preload complete event
W/bt-l2cap( 6188): L2CAP - L2CA_Register() called for PSM: 0x0001
W/bt-l2cap( 6188): L2CAP - L2CA_Register() called for PSM: 0x001f
D/QRemote ( 5941): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 5941): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 5941): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
W/bt-l2cap( 6188): L2CAP - L2CA_Register() called for PSM: 0x0003
D/PostponalbeReceiver( 6386): WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
I/        ( 6188): BTE_InitTraceLevels -- TRC_HCI
I/        ( 6188): BTE_InitTraceLevels -- TRC_L2CAP
I/        ( 6188): BTE_InitTraceLevels -- TRC_RFCOMM
I/        ( 6188): BTE_InitTraceLevels -- TRC_AVDT
I/        ( 6188): BTE_InitTraceLevels -- TRC_AVRC
I/        ( 6188): BTE_InitTraceLevels -- TRC_A2D
I/        ( 6188): BTE_InitTraceLevels -- TRC_BNEP
I/        ( 6188): BTE_InitTraceLevels -- TRC_BTM
I/        ( 6188): BTE_InitTraceLevels -- TRC_HID_HOST
I/        ( 6188): BTE_InitTraceLevels -- TRC_GAP
I/        ( 6188): BTE_InitTraceLevels -- TRC_PAN
I/        ( 6188): BTE_InitTraceLevels -- TRC_SDP
I/        ( 6188): BTE_InitTraceLevels -- TRC_GATT
I/        ( 6188): BTE_InitTraceLevels -- TRC_SMP
I/        ( 6188): BTE_InitTraceLevels -- TRC_BTAPP
I/        ( 6188): BTE_InitTraceLevels -- TRC_BTIF
,W/ContextImpl( 6386): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
V/WiFiOffLoadBroadcast( 6214): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 6214): MCCMNC not supported: null
D/QRemote ( 5941): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 5941): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 5941): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,D/PostponalbeReceiver( 6386): WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'null'.
D/PostponalbeReceiver( 6386): WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'null'.
D/PostponalbeReceiver( 6386): WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'null'.
D/PostponalbeReceiver( 6386): WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'null'.
D/PostponalbeReceiver( 6386): WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'null'.
W/bt-btm  ( 6188): btm_decode_ext_features_page Secure conn Controller support Enabled
E/bt-btm  ( 6188): BTM_SecRegister:p_cb_info->p_le_callback == 0xa01ce061 
E/bt-btm  ( 6188): BTM_SecRegister: btm_cb.api.p_le_callback = 0xa01ce061 
D/PostponalbeReceiver( 6386): WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'null'.
D/PostponalbeReceiver( 6386): WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'null'.
,D/PostponalbeReceiver( 6386): WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'null'.
E/bt-btif ( 6188): Calling BTA_HhEnable
W/bt-l2cap( 6188): L2CAP - L2CA_Register() called for PSM: 0x0019
W/bt-l2cap( 6188): L2CAP - L2CA_Register() called for PSM: 0x0017
W/bt-l2cap( 6188): L2CAP - L2CA_Register() called for PSM: 0x001b
W/bt-l2cap( 6188): L2CAP - L2CA_Register() called for PSM: 0x0011
W/bt-l2cap( 6188): L2CAP - L2CA_Register() called for PSM: 0x0013
E/bt-btif ( 6188): btif_storage_get_adapter_property service_mask:0x2140040
D/BluetoothAdapterProperties( 6188): Address is:58:3F:54:73:64:C0
I/ActivityManager( 1031): Killing 5501:com.lge.lockscreensettings/u0a80 (adj 15): empty #17
W/bt-smp  ( 6188): Key(LSB ~ MSB) = 0a 3c a6 fe eb 17 6a 79 a6 1f 0a 0b f9 50 a0 5f 
W/bt-smp  ( 6188): Plain text(LSB ~ MSB) = fa f3 7e 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 6188): Encrypted text(LSB ~ MSB) = ca 67 cf 2b da 62 65 c0 e5 c6 e8 09 48 ec 9c 43 
W/bt-btm  ( 6188): Stopping oneshot timer
D/LgDataFeature( 6386): LgDataFeature() Constructor: none
D/LgDataFeature( 6386): LgDataFeature() Constructor Done, null
,I/dhcpcd  ( 6371): wlan0: acknowledged 192.168.1.141 from 192.168.1.1
,W/libprocessgroup( 1031): failed to open /acct/uid_10080/pid_5501/cgroup.procs: No such file or directory
,D/BluetoothAdapterProperties( 6188): Name is: G3-1
D/BluetoothManagerService( 1031): Bluetooth Adapter name changed to G3-1
D/BluetoothManagerService( 1031): Stored Bluetooth name: G3-1
D/BluetoothAdapterProperties( 6188): Scan Mode:20
D/BluetoothAdapterProperties( 6188): Discoverable Timeout:120
D/bt_hci_bdroid( 6188): postload
W/bt-l2cap( 6188): L2CAP - L2CA_Register() called for PSM: 0x000f
D/bt_hci_bdroid( 6188): Used up Tx Cmd credits
D/bt_hci_bdroid( 6188): Used up Tx Cmd credits
E/bt_mct  ( 6188): hci lib postload completed
D/bte_conf( 6188): Device ID record 1 : primary
D/bte_conf( 6188):   vendorId            = 00c4
D/bte_conf( 6188):   vendorIdSource      = 0001
D/bte_conf( 6188):   product             = 13a1
D/bte_conf( 6188):   version             = 1000
D/bte_conf( 6188):   clientExecutableURL = 
D/bte_conf( 6188):   serviceDescription  = 
,D/bte_conf( 6188):   documentationURL    = 
D/bte_conf( 6188): bte_load_did_conf no section named DID2.
D/BluetoothAdapterState( 6188): CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
W/sh      ( 6433): type=1400 audit(0.0:161): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
D/BluetoothAdapterProperties( 6188): ScanMode =  20
D/BluetoothAdapterProperties( 6188): State =  11
W/sh      ( 6433): type=1400 audit(0.0:162): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
D/BluetoothAdapterProperties( 6188): mDiscoverableTimeout = 120
V/LGBluetoothServiceAdapter( 6188): [BTUI] state:11, scanmode:20, timeout:120
D/BluetoothAdapterProperties( 6188): Setting state to 12
I/BluetoothAdapterState( 6188): Bluetooth adapter state changed: 11-> 12
D/BluetoothManagerService( 1031): Message: 60
D/BluetoothManagerService( 1031): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
D/BluetoothManagerService( 1031): Broadcasting onBluetoothStateChange(true) to 5 receivers.
I/BluetoothAdapterState( 6188): Entering On State
D/BluetoothPanServiceJni( 6188): control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
D/btif_config_util( 6188): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
I/dhcpcd  ( 6371): wlan0: leased 192.168.1.141 for 86400 seconds
D/dhcpcd  ( 6371): wlan0: adding IP address 192.168.1.141/24
D/dhcpcd  ( 6371): wlan0: adding route to 192.168.1.0/24
D/dhcpcd  ( 6371): wlan0: adding default route via 192.168.1.1
D/dhcpcd  ( 6371): wlan0: writing lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
D/dhcpcd  ( 6371): getUsingAPMacAddress: c0:ff:d4:d3:aa:48 , return 1
D/dhcpcd  ( 6371): write_lease_ext: /data/misc/dhcp/dhcpcd-wlan0-c0:ff:d4:d3:aa:48.lease2
D/dhcpcd  ( 6371): wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason REBOOT
D/BluetoothHeadset( 1838): onBluetoothStateChange: up=true
D/LGBluetoothServiceAdapter( 6188): [BTUI] OnState
D/LGBluetoothServiceAdapter( 6188): [BTUI]         global_name: G3-1
D/LGBluetoothServiceAdapter( 6188): [BTUI]         local_name: G3-1
,D/BluetoothAdapterService( 6188): [BTUI] autoConnect() : not allowed
E/WifiStateMachine( 1031):  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1031):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1031):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
W/ContextImpl( 6386): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.vsmandroid.gh.h:-1 com.mcafee.vsm.ext.common.a.d.a:-1 com.mcafee.vsm.ext.common.api.ExtUtils.stopApp:-1 
E/WifiStateMachine( 1031):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1031):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
D/ConnectivityService( 1031): Update of LinkProperties for NetworkAgentInfo [WIFI () - 100]; created=false
D/BluetoothHeadset( 1838): onBluetoothStateChange: up=true
D/BluetoothA2dp( 1031): onBluetoothStateChange: up=true
D/BluetoothHeadset( 1031): onBluetoothStateChange: up=true
D/BluetoothHeadset( 1838): onBluetoothStateChange: up=true
E/BluetoothManagerService( 1031): Fail to bind to: Intent { act=android.bluetooth.IQBluetooth }
D/BluetoothManagerService( 1031): Bluetooth State Change Intent: 11 -> 12
,I/[SystemUI]BluetoothHandler( 1468): Receive : BluetoothAdapter.ACTION_STATE_CHANGED
D/BluetoothAdapterProperties( 6188): Discoverable Timeout:120
D/LGBluetoothDeviceModeControllManager( 6188): adapterPropertyChangedCallback on  LGAdapter : do nothing - 9
D/BluetoothManagerService( 1031): BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
D/LGBluetoothAPIService( 1928): [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
D/LGBluetoothAPIService( 1928): Message: 1
D/LGBluetoothAPIService( 1928): MESSAGE_BOOT_COMPLETED
D/BluetoothManagerService( 1031): Message: 40
D/BluetoothManagerService( 1031): MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
,D/SiteAdvisor( 6386): com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.google.android.browser/com.android.browser.BrowserActivity not supported
I/BluetoothMapService( 6188): onReceive: android.bluetooth.adapter.action.STATE_CHANGED
D/BluetoothMapService( 6188): STATE_ON
V/BluetoothMapService( 6188): Handler(): got msg=1
D/BluetoothMapMasInstance( 6188): Map Service startRfcommSocketListener
I/qcom-bt-wlan-coex( 6446): /system/etc/init.qcom.coex.sh: btwlancoex/abtfilt not available 
D/LGBluetoothDeviceModeControllManager( 6188): [BTUI] checkDeviceModeAndSet, sinkMode : false
,D/SiteAdvisor( 6386): com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.amazon.cloud9/com.amazon.cloud9.BrowserActivity not supported
D/SiteAdvisor( 6386): com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.sec.android.app.sbrowser/com.sec.android.app.sbrowser.SBrowserMainActivity not supported
,D/BluetoothAdapterService( 6188): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@125ecfa2
V/BluetoothPbapService( 6188): Pbap Service onCreate
V/BluetoothPbapService( 6188): Starting PBAP service
D/LGBluetoothPbapAdapter( 6188): [BTUI] getInstance : create
V/BluetoothPbapService( 6188): action: android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothPbapService( 6188): state: 12
D/SiteAdvisor( 6386): com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.sec.android.app.sbrowser/com.sec.android.app.sbrowser.SBrowserMainActivity not supported
D/SiteAdvisor( 6386): com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.htc.sense.browser/com.htc.sense.browser.BrowserActivity not supported
I/SiteAdvisor( 6386): com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Loading supported browsers: com.android.browser/com.android.browser.BrowserActivity; com.android.chrome/com.android.chrome.Main; 
W/ContextImpl( 6214): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
I/LGBluetoothAPIService( 1928): [BTUI] LGBluetoothAPIService Binding Success
D/LGBluetoothAPIServer( 6188): [BTUI] onCreate()
,D/LGBluetoothAPIServer( 6188): [BTUI] onBind()
D/LGBluetoothAPIService( 1928): [BTUI] LGBluetoothAPIServiceConnection: connected to LGBluetoothAPIAdapter
V/BluetoothPbapService( 6188): Handler(): got msg=1
V/BluetoothPbapService( 6188): Pbap Service startRfcommSocketListener
V/BluetoothPbapReceiver( 6188): PbapReceiver onReceive 
V/BluetoothPbapReceiver( 6188): ***********action = android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothPbapReceiver( 6188): ***********state = 12
D/BluetoothMapMasInstance( 6188): MAS initSocket()
D/BluetoothMapMasInstance( 6188):   masId = 00
D/BluetoothMapMasInstance( 6188):   msgTypes = 0e
D/BluetoothMapMasInstance( 6188):   masName = SMS/MMS
D/BluetoothMapMasInstance( 6188):   SDP string = 000eSMS/MMS
D/BluetoothManagerService( 1031): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/LGBluetoothAPIService( 1928): Message: 100
D/LGBluetoothAPIService( 1928): MESSAGE_BLUETOOTH_SERVICE_CONNECTED
W/BluetoothAdapter( 6188): getBluetoothService() called with no BluetoothManagerCallback
V/BluetoothPbapService( 6188): Pbap Service initSocket
D/BluetoothManagerService( 1031): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
W/BluetoothAdapter( 6188): getBluetoothService() called with no BluetoothManagerCallback
D/BluetoothAdapterProperties( 6188): Scan Mode:21
D/LGBluetoothDeviceModeControllManager( 6188): getDeviceMode  deviceMode 0
D/LGBluetoothServiceAdapter( 6188): [BTUI] createSocketChannel FD=73 mFd=0
V/BluetoothMapMasInstance( 6188): Succeed to create listening socket 
D/BluetoothMapMasInstance( 6188): Accepting socket connection...
,D/SiteAdvisor( 6386): com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Here is the storedCurrentAppVersion: 3.1.2.1430
D/LGBluetoothServiceAdapter( 6188): [BTUI] createSocketChannel FD=75 mFd=73
V/BluetoothPbapService( 6188): Succeed to create listening socket 
V/BluetoothPbapService( 6188): Accepting socket connection...
D/LocalBluetoothProfileManager( 6214): Adding local A2DP profile
D/SiteAdvisor( 6386): com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Here about to commit perfs
D/BluetoothManagerService( 1031): Message: 30
D/LocalBluetoothProfileManager( 6214): Adding local HEADSET profile
,D/BluetoothManagerService( 1031): Message: 30
D/BluetoothManagerService( 1031): Message: 30
D/BluetoothManagerService( 1031): Message: 30
D/LocalBluetoothProfileManager( 6214): Adding local MAP profile
D/BluetoothMap( 6214): Create BluetoothMap proxy object
D/BluetoothManagerService( 1031): Message: 30
,D/BluetoothManagerService( 1031): Message: 30
D/LocalBluetoothProfileManager( 6214): LocalBluetoothProfileManager construction complete
V/BluetoothPbapService( 6188): Pbap Service onBind
D/LGBluetoothUserBindClient( 6214): [BTUI] initUserBindClient
W/ContextImpl( 6214): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.android.settings.bluetooth.LGBluetoothUserBindClient.initUserBindClient:90 com.android.settings.bluetooth.LGBluetoothUserBindClient.<init>:55 com.android.settings.bluetooth.LGBluetoothUserBindClient.getInstance:47 
,D/DockEventReceiver( 6214): finishStartingService: stopping service
D/BluetoothA2dp( 6214): Proxy object connected
D/A2dpProfile( 6214): Bluetooth service connected
D/BluetoothHeadset( 6214): Proxy object connected
,D/HeadsetProfile( 6214): Bluetooth service connected
D/BluetoothInputDevice( 6214): Proxy object connected
D/HidProfile( 6214): Bluetooth service connected
D/BluetoothPan( 6214): BluetoothPAN Proxy object connected
D/PanProfile( 6214): Bluetooth service connected
D/BluetoothMap( 6214): Proxy object connected
,D/MapProfile( 6214): Bluetooth service connected
D/BluetoothMap( 6214): getConnectedDevices()
V/BluetoothMapService( 6188): getConnectedDevices()
D/BluetoothPbap( 6214): Proxy object connected
D/PbapServerProfile( 6214): Bluetooth service connected
D/LGBluetoothUserBindClient( 6214): [BTUI] onServiceConnected
D/BluetoothPermissionRequest( 6214): onReceive
D/LGBluetoothFeatureConfig( 6214): isPrivacyLogsEnabled : true
D/LGBluetoothUtils( 6214): [BTUI] FileNotFound: readProperty
D/LGBluetoothResetSettingReceiver( 6214): return without doing reset settings.
,V/BluetoothOppReceiver( 6188): Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_ON
I/LGBluetoothOppAdapter( 6188): [BTUI] startOppService()
,V/BluetoothOppManager( 6188): restoreApplicationData! falsefalsenullnull
D/LGBluetoothFeatureConfig( 6188): isPrivacyLogsEnabled : true
V/BtOppService( 6188): onCreate
V/BluetoothOppNotification( 6188): send message
V/BtOppService( 6188): Starting RfcommListener
,D/BluetoothOppPreference( 6188): Dumping Names:  
D/BluetoothOppPreference( 6188): {}
D/BluetoothOppPreference( 6188): Dumping Channels:  
D/BluetoothOppPreference( 6188): {}
V/BtOppService( 6188): onStartCommand
V/BluetoothFtpReceiver( 6188): BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothFtpReceiver( 6188): BluetoothFtpReceiver Start Service
V/BtOppService( 6188): Deleted complete outbound shares, number =  0
V/BtOppService( 6188): Deleted complete inbound failed shares, number = 0
V/BluetoothOppProvider( 6188): starting query, database is not null; projection[0] is _id; selection is direction=1 AND status=200 AND visibility=1; selectionArgs is null; sort is _id.
V/BluetoothOppNotification( 6188): new notify threadi!
V/BluetoothOppProvider( 6188): created cursor android.database.sqlite.SQLiteCursor@3b1f9bac on behalf of 
V/BluetoothOppNotification( 6188): send delay message
V/BtOppService( 6188): pendingUpdate is true keepUpdateThread is false sListenStarted is true
V/BluetoothOppProvider( 6188): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
V/BluetoothOppProvider( 6188): starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
,V/BtOppService( 6188): start RfcommListener
V/BluetoothOppProvider( 6188): created cursor android.database.sqlite.SQLiteCursor@20ebe075 on behalf of 
V/BluetoothOppProvider( 6188): created cursor android.database.sqlite.SQLiteCursor@3250680a on behalf of 
V/BluetoothOppNotification( 6188): mUpdateCompleteNotification = true
V/BtOppService( 6188): RfcommListener started
V/BtOppService( 6188): ContentObserver received notification
V/BluetoothOppProvider( 6188): starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
V/BtOppRfcommListener( 6188): Starting RFCOMM listener....
V/BtOppService( 6188): pendingUpdate is true keepUpdateThread is false sListenStarted is true
V/BluetoothOppProvider( 6188): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
D/BluetoothManagerService( 1031): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
V/BluetoothOppProvider( 6188): created cursor android.database.sqlite.SQLiteCursor@2dab887b on behalf of 
W/BluetoothAdapter( 6188): getBluetoothService() called with no BluetoothManagerCallback
V/BluetoothOppNotification( 6188): outbound: succ-0  fail-0
,D/LGBluetoothServiceAdapter( 6188): [BTUI] createSocketChannel FD=78 mFd=75
V/BtOppRfcommListener( 6188): Started RFCOMM listener....
I/BtOppRfcommListener( 6188): Accept thread started.
V/BtOppRfcommListener( 6188): Accepting connection...
V/BluetoothOppProvider( 6188): created cursor android.database.sqlite.SQLiteCursor@3fc0c698 on behalf of 
V/BluetoothOppNotification( 6188): outbound notification was removed.
V/BluetoothOppProvider( 6188): starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
D/DhcpStateMachine( 1031): DHCPV4 succeeded on wlan0
V/BluetoothOppProvider( 6188): created cursor android.database.sqlite.SQLiteCursor@13270ef1 on behalf of 
D/LgDhcpStateMachineHelper( 1031): CheckDhcpDirectory [Lease File Count] : 3
V/LgDhcpStateMachineHelper( 1031): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
V/BluetoothOppNotification( 6188): inbound: succ-0  fail-0
D/LgDhcpStateMachineHelper( 1031): checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.141
V/LgDhcpStateMachineHelper( 1031): Add DhcpResults: IP address 192.168.1.141/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 86400 seconds
V/DhcpStateMachine( 1031): Current State is mWaitBeforeStartState.
V/LgDhcpStateMachineHelper( 1031): bShouldSendDhcpAction Result: true
D/DhcpStateMachine( 1031): DHCP Start/Renew wake lock is released.
D/DhcpStateMachine( 1031): RunningState
E/WifiStateMachine( 1031):  ObtainingIpState CMD_POST_DHCP_ACTION 1 0 OK  v4
E/WifiStateMachine( 1031):  L2ConnectedState CMD_POST_DHCP_ACTION 1 0 OK  v4
D/WifiNative-wlan0( 1031): doBoolean: DRIVER BTCOEXMODE 2
I/wpa_supplicant( 6231): wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
D/LGWifiP2pService( 1031): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1031): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0( 1031): DRIVER BTCOEXMODE 2: returned true
D/WifiNative-wlan0( 1031): doBoolean: DRIVER SETSUSPENDMODE 1
I/wpa_supplicant( 6231): wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 1
V/BluetoothOppNotification( 6188): inbound notification was removed.
V/BluetoothOppProvider( 6188): starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
D/WifiNative-wlan0( 1031): DRIVER SETSUSPENDMODE 1: returned true
D/WifiNative-wlan0( 1031): doBoolean: SET ps 1
V/BluetoothOppNotification( 6188): update too frequent, put in queue
V/BtOppService( 6188): pendingUpdate is false keepUpdateThread is false sListenStarted is true
V/BluetoothOppProvider( 6188): created cursor android.database.sqlite.SQLiteCursor@d94fad6 on behalf of 
D/BluetoothAdapterService( 6188): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@125ecfa2
V/BluetoothFtpService( 6188): Ftp Service onCreate
I/BluetoothFtpService( 6188): Ftp Service onCreate
V/BluetoothFtpService( 6188): Ftp Service onStartCommand
,V/BluetoothFtpService( 6188): action: android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothFtpService( 6188): Starting Listening on sockets
V/BtOppService( 6188): ContentObserver received notification
V/BluetoothSapReceiver( 6188): [BTUI] checkServiceStart
V/BluetoothSapReceiver( 6188): [BTUI] region:EU country:EU
V/BluetoothSapReceiver( 6188): SapReceiver onReceive 
V/BluetoothSapReceiver( 6188): action = android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothSapReceiver( 6188):  Bluetooth Adapter state = 12
V/BluetoothSapReceiver( 6188): Calling SAP service start service with action = null
V/BtOppService( 6188): pendingUpdate is true keepUpdateThread is false sListenStarted is true
V/BluetoothOppProvider( 6188): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
V/BluetoothFtpService( 6188): Handler(): got msg=1
V/BluetoothFtpService( 6188): Ftp Service startRfcommSocketListener
V/BluetoothFtpService( 6188): Ftp Service initSocket
D/BluetoothManagerService( 1031): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,W/BluetoothAdapter( 6188): getBluetoothService() called with no BluetoothManagerCallback
V/BluetoothOppProvider( 6188): created cursor android.database.sqlite.SQLiteCursor@2c47b444 on behalf of 
V/BluetoothOppNotification( 6188): update too frequent, put in queue
V/BtOppService( 6188): pendingUpdate is false keepUpdateThread is false sListenStarted is true
D/AuthorizationBluetoothService( 2057): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
D/LGBluetoothServiceAdapter( 6188): [BTUI] createSocketChannel FD=80 mFd=78
V/BluetoothFtpService( 6188): Succeed to create listening socket on channel 20
V/BluetoothFtpService:RfcommSocketAcceptThread( 6188): Run Accept thread
D/WifiNative-wlan0( 1031): SET ps 1: returned true
D/ConnectivityService( 1031): Update of LinkProperties for NetworkAgentInfo [WIFI () - 100]; created=false
E/WifiStateMachine( 1031):  ObtainingIpState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
E/WifiStateMachine( 1031): WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
E/WifiStateMachine( 1031): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
D/ConnectivityService( 1031): ignoring duplicate network state non-change
D/ConnectivityService( 1031): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
D/ConnectivityService( 1031): Adding iface wlan0 to network 100
,D/BluetoothAdapterService( 6188): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@125ecfa2
V/BluetoothSapService( 6188): Sap Service onCreate
V/BluetoothSapService( 6188): action: android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothSapService( 6188): state: 12
V/BluetoothSapService( 6188): Starting SAP server process
V/BluetoothSapService( 6188): SAP Service startRfcommListenerThread
V/BluetoothSapService( 6188): Sap Service initRfcommSocket
D/BluetoothManagerService( 1031): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
W/BluetoothAdapter( 6188): getBluetoothService() called with no BluetoothManagerCallback
D/LGBluetoothServiceAdapter( 6188): [BTUI] createSocketChannel FD=82 mFd=80
V/BluetoothSapService( 6188): Succeed to create listening socket 
V/BluetoothSapService( 6188): Accepting socket connection...
W/sapd    ( 6483): type=1400 audit(0.0:163): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
W/sapd    ( 6483): type=1400 audit(0.0:164): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
E/ConnectivityService( 1031): Unexpected mtu value: 0, wlan0
,D/ConnectivityService( 1031): Adding Route [fe80::/64 -> :: wlan0] to network 100
V/BT_SAP  ( 6483): Event pipe created
V/BT_SAP  ( 6483): create_server_socket qcom.sap.server
V/BT_SAP  ( 6483): created socket fd 6
D/ConnectivityService( 1031): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 100
D/ConnectivityService( 1031): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 100
D/ConnectivityService( 1031): addLocalRoutetoDefaultNetwork
D/ConnectivityService( 1031): defaultNAI is null or Wi-Fi no need to add Loacal route to default network. WiFi netid = 100
D/ConnectivityService( 1031): Setting Dns servers for network 100 to [/192.168.1.1]
D/Nat464Xlat( 1031): requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
D/ConnectivityService( 1031): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService( 1031): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService( 1031): rematching NetworkAgentInfo [WIFI () - 100]
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1031): DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1031): Connected
D/ConnectivityService( 1031):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService( 1031):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1031): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1031): Checking http://clients3.google.com/generate_204 on "NG700"
D/ConnectivityService( 1031):     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
D/ConnectivityService( 1031):   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1031):     satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:true
D/ConnectivityService( 1031): currentScore = 0, newScore = 20
D/ConnectivityService( 1031):    accepting network in place of null
D/ConnectivityService( 1031): sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/libc-netbsd(  335): res_queryN name = clients3.google.com, class = 1, type = 28
D/WIFI    ( 1031): new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    ( 1031):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService( 1031): Setting tx/rx TCP buffers to 524288,1048576,2097152,262144,524288,1048576
D/TelephonyNetworkFactory-1( 1838): new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/TelephonyNetworkFactory-1( 1838):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
E/ConnectivityService( 1031): [lg_data] Adding agent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::c69a:2ff:fe7b:60ac/64,192.168.1.141/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT,_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
D/CSLegacyTypeTracker( 1031): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
D/ConnectivityService( 1031): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,W/Settings( 1031): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1031): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1031): NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
I/StatusBar.NetworkController( 1468): networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1468): mWifiConnected = false, mWifiLevel = 0
W/Settings( 1031): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1031): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1031): NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
D/WifiHS20( 1031): [PASSPOINT] passpointNotification: hs20AP list is checked
D/StatusBar.NetworkController( 1468): refreshViews: Data not connected!! Set no data type icon / Roaming
V/WfdStateTracker( 1928): handleWifiStateChangedEvent: 1
W/Settings( 1031): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1031): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1031): NETWORK_STATE_CHANGED_ACTION [CONNECTED]
D/WifiHS20( 1031): [PASSPOINT] passpointNotification: hs20AP list is checked
I/StatusBar.NetworkController( 1468): networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1468): mWifiConnected = false, mWifiLevel = 0
,W/Settings( 1031): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1031): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/StatusBar.NetworkController( 1468): refreshViews: Data not connected!! Set no data type icon / Roaming
D/WifiOffDelayIfNotUsed( 1031): NETWORK_STATE_CHANGED_ACTION [CONNECTED]
D/ConnectivityService( 1031): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/CSLegacyTypeTracker( 1031): [e] list.add(nai) empty : false size: 1
I/StatusBar.NetworkController( 1468): networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService( 1031): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::c69a:2ff:fe7b:60ac/64,192.168.1.141/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
D/ConnectivityService( 1031): validation of new default Network = false
D/ConnectivityService( 1031): Default network via Wi-Fi connected. start DSQN
D/DSQN    ( 1031): enableDataServiceNotify 
D/DSQN    ( 1031): start dsqn bin
I/StatusBar.NetworkController( 1468): mWifiConnected = true, mWifiLevel = 2
D/LocSvc_java( 1031): Sending msg: 4 arg1:1 arg2:1
D/libc-netbsd(  335): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  335): res_queryN name = 2.android.pool.ntp.org, class = 1, type = 1
D/LocSvc_java( 1031): getAGpsConnectionInfo connType - 4
D/LocSvc_java( 1031): updateNetworkState connTyp: 4 available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java( 1031): ignore wifi update if we are not in OPENING or CLOSING
D/LocSvc_java( 1031): Sending msg: 5 arg1:0 arg2:1
D/StatusBar.NetworkController( 1468): refreshViews: Data not connected!! Set no data type icon / Roaming
D/libc-netbsd(  335): default dns: query_ipv6=0, query_ipv4=1
,D/libc-netbsd(  335): res_queryN name = europe.pool.ntp.org, class = 1, type = 1
D/ConnectivityService( 1031): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService( 1031):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1031):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1031): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityManager.CallbackHandler( 1468): CM callback handler got msg 524290
W/dsqn    ( 6491): type=1400 audit(0.0:165): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
W/dsqn    ( 6491): type=1400 audit(0.0:166): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
I/StatusBar.NetworkController( 1468): networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1468): mWifiConnected = true, mWifiLevel = 2
D/StatusBar.NetworkController( 1468): refreshViews: Data not connected!! Set no data type icon / Roaming
D/libc-netbsd(  335): res_queryN name = clients3.google.com, class = 1, type = 1
,E/DSQN    ( 6491): DSQN ssw
,D/PostponalbeReceiver( 6386): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
D/TelephonyIcons( 1468): null signal icon name: drawable/stat_sys_signal_null
D/StatusBar.NetworkController( 1468): refreshViews: Data not connected!! Set no data type icon / Roaming
D/StatusBar.NetworkController( 1468): refreshViews: Data not connected!! Set no data type icon / Roaming
V/WiFiOffLoadBroadcast( 6214): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6214): MCCMNC not supported: null
D/libc-netbsd(  335): res_queryN name = clients3.google.com succeed
D/QRemote ( 5941): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 5941): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 5941): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,D/PostponalbeReceiver( 6386): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
D/LGDataListener(  335): argv[0]=dsqncommand
D/LGDataListener(  335): argv[1]=wlan0
D/LGDataListener(  335): argv[2]=1
D/LGDataListener(  335): notifyDSQN DSQN STARTMONITOR wlan0 1
V/WiFiOffLoadBroadcast( 6214): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/DSQN    ( 1031): DSQM DsqnNotification wlan0  1
D/DSQN    ( 1031): start to monitor internet connection
D/libc-netbsd(  335): res_queryN name = 2.android.pool.ntp.org succeed
,D/libc-netbsd(  335): res_queryN name = europe.pool.ntp.org succeed
D/WiFiOffLoadBroadcast( 6214): MCCMNC not supported: null
D/QRemote ( 5941): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 5941): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 5941): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
D/PostponalbeReceiver( 6386): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1031): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Fri, 29 Jan 2016 18:29:05 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1454092145604], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1454092145581]}
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
D/WIFI    ( 1031): new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityManager.CallbackHandler( 1468): CM callback handler got msg 524290
D/WIFI    ( 1031):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService( 1031): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
D/TelephonyNetworkFactory-1( 1838): new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/TelephonyNetworkFactory-1( 1838):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
I/PCSuite ( 6299): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
D/PCSuite ( 6299): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
,V/NetworkPolicy( 1031): [LG_RESTRICTED] checkMobilePolicy_type()
V/WiFiOffLoadBroadcast( 6214): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/TelephonyIcons( 1468): null signal icon name: drawable/stat_sys_signal_null
D/StatusBar.NetworkController( 1468): refreshViews: Data not connected!! Set no data type icon / Roaming
D/WiFiOffLoadBroadcast( 6214): MCCMNC not supported: null
D/StatusBar.NetworkController( 1468): refreshViews: Data not connected!! Set no data type icon / Roaming
D/QRemote ( 5941): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 5941): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
D/QRemote ( 5941): [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
,I/QRemote ( 5941): [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
I/QRemote ( 5941): [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
D/PostponalbeReceiver( 6386): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
I/PCSuite ( 6299): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
D/PCSuite ( 6299): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 6214): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6214): MCCMNC not supported: null
,D/QRemote ( 5941): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 5941): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
D/LocSvc_java( 1031): NTP server : europe.pool.ntp.org
D/QRemote ( 5941): [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
D/LocSvc_java( 1031): NTP server returned: 1454092145457 (Fri Jan 29 19:29:05 GMT+01:00 2016) reference: 231785 certainty: 37 system time offset: -212
D/LocSvc_java( 1031): Sending msg: 10 arg1:0 arg2:1
I/QRemote ( 5941): [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
,I/QRemote ( 5941): [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
V/BluetoothOppNotification( 6188): new notify threadi!
V/BluetoothOppNotification( 6188): send delay message
,V/BluetoothOppProvider( 6188): starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
V/BluetoothOppProvider( 6188): created cursor android.database.sqlite.SQLiteCursor@b2dd0b0 on behalf of 
V/BluetoothOppNotification( 6188): mUpdateCompleteNotification = true
V/BluetoothOppProvider( 6188): starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
,I/art     ( 1031): Explicit concurrent mark sweep GC freed 80316(3MB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 44MB/66MB, paused 1.372ms total 72.667ms
,V/BluetoothOppProvider( 6188): created cursor android.database.sqlite.SQLiteCursor@1037ab29 on behalf of 
V/BluetoothOppNotification( 6188): outbound: succ-0  fail-0
,V/BluetoothOppNotification( 6188): outbound notification was removed.
V/BluetoothOppProvider( 6188): starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
V/BluetoothOppProvider( 6188): created cursor android.database.sqlite.SQLiteCursor@28908eae on behalf of 
V/BluetoothOppNotification( 6188): inbound: succ-0  fail-0
V/BluetoothOppNotification( 6188): inbound notification was removed.
V/BluetoothOppProvider( 6188): starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
V/BluetoothOppProvider( 6188): created cursor android.database.sqlite.SQLiteCursor@1999f44f on behalf of 
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3005] from screen [on:0 period:-1901766541] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:2] from screen [on:0 period:-1901766539] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,D/StatusBar.NetworkController( 1468): refreshViews: Data not connected!! Set no data type icon / Roaming
,I/jxcore-log( 6098): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMultiplex.js
I/jxcore-log( 6098): 
,I/jxcore-log( 6098): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
I/jxcore-log( 6098): 
,I/jxcore-log( 6098): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
I/jxcore-log( 6098): 
,I/jxcore-log( 6098): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js
I/jxcore-log( 6098): 
I/jxcore-log( 6098): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
I/jxcore-log( 6098): 
V/WifiInternetCheck( 1031): Single check msg out of sync, ignoring.
,D/ConnectivityService( 1031): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
D/GpsLocationProvider( 1031): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
D/Tethering( 1031): MasterInitialState.processMessage what=3
,D/AlarmManagerService( 1031): Setting time of day to sec=1454092148
W/AlarmManagerService( 1031): Unable to set rtc to 1454092148: Invalid argument
,D/PostponalbeReceiver( 6386): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
,W/ContextImpl( 6386): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
D/LIA_Informant_Tips_DateChangeManager( 2712): onReceive() : ACTION_TIME_CHANGED
I/LIA_Informant_Tips_LogTracer( 2712): [Log Tracer - Schedule Transition] Time Change Event Received : 2016-01-29 19:29:08...... Request
I/LIA_Informant_Tips_LogTracer( 2712): [Log Tracer - Schedule Transition] UserGuide, DATE_UPDATE : working count : 2, total count : 159, new day : false...... Request
D/LIA_Informant_Tips_DateChangeManager( 2712): DateInfo : SmartTips Total Working Day Count = 159
D/LIA_Informant_Tips_DateChangeManager( 2712): DateInfo : UserGuide Working Duration Count = 2
I/[SystemUI]Clock( 1468): onReceive = android.intent.action.TIME_SET
D/LIA_Informant_Tips_DateChangeManager( 2712): DateInfo : Last Date Check Time = 2016-01-29 19:29:08
,I/LgeClockWidgetControlView( 1468): time changed, timezoneChanged : false
I/SecureClockService( 1928): Intent.ACTION_TIME_CHANGED 
W/ActivityManager( 1031): getTasks: caller 10029 is using old GET_TASKS but privileged; allowing
,D/KeyguardUpdateMonitor( 1468): handleTimeUpdate
I/[LGHome]LGDateChangeReceiver( 2020): [LGDateChangeReceiver.java:78:updateCalendarShortcut()]date=29 currentDate=-1 dayofweek=6 currentDayOfWeek=-1
I/[LGHome]LGCalendarIcon( 2020): [LGCalendarIcon.java:214:makeCalendarBitmap()]Locale = en_US dayofweek= Fri date= 29
I/[LGHome]LGCalendarIcon( 2020): [LGCalendarIcon.java:214:makeCalendarBitmap()]Locale = en_US dayofweek= Fri date= 29
I/[LGHome]Launcher( 2020): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,I/NetworkMonitor( 5209): type=WIFI subType= reason=null isConnected=true
,I/ActivityManager( 1031): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=6521 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,I/art     (  360): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 205us total 9.160ms
D/[Concierge]Service( 2617): onStartCommand(). Type : 9
I/art     (  360): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 185us total 8.933ms
I/art     (  360): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 190us total 8.770ms
V/GLSActivity( 2057): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager( 1031): Start proc com.google.android.apps.books for service com.google.android.apps.books/.service.SyncService: pid=6539 uid=10054 gids={50054, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,V/AlarmManager( 1031): ELAPSED_WAKEUP set : Alarm{178e8981 type 2 when 234874 android} when 234874
I/ActivityManager( 1031): Start proc com.android.gallery3d for service com.android.gallery3d/com.lge.gallery.picasa.PicasaService: pid=6556 uid=10027 gids={50027, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
,W/ResourcesManager( 6556): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6556): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 6556): Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
W/ResourcesManager( 6556): Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
,I/AppUp4:AppBoxCP( 6521): onCreate
W/AppUp4:DB( 6521):  [AppBoxDatabaseHelper] construct
I/AppUp4:DB( 6521):  setFingerPrint start
I/AppUp4:DB( 6521):  newfinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys SDK version = 21
,I/AppUp4:DB( 6521):  beforefinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys
I/AppUp4:DB( 6521):  SDK version = 21
I/AppUp4:DB( 6521):  beforefinger == newfinger no write in DB
D/AppUp4:AppBoxApplication( 6521): AppBoxApplication onCreate()
I/NetworkStateForAutoUpdateMonitor( 6521): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 6521): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 6521): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 6521): [onReceive] request level :IDLE....
I/AppUp4:CustModeStarterReceiver( 6521): onReceive
,D/LgDataFeature( 6521): LgDataFeature() Constructor: none
,D/LgDataFeature( 6521): LgDataFeature() Constructor Done, null
D/AppUp4:CustFacade( 6521): Context : android.app.ReceiverRestrictedContext@2c8b476d
D/AppUp4:CustFacade( 6521): isCustomizationCompleted : false
D/AppUp4:CustFacade( 6521): isPhone : true
D/AppUp4:CustModeStarterReceiver( 6521): begin check event
I/AppUp4:CustModeStarterReceiver( 6521): Event For GoodConnectivity
D/AppUp4:CustModeStarterReceiver( 6521): runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
D/AppUp4:CustModeStarterReceiver( 6521): call method handleAsyncCustNotification.
D/AppUp4:CustModeStarterReceiver( 6521): handleAsync isTriedOnce : false
E/AppUp4:CustModeStarterReceiver( 6521): handleAsyncCustNotification do not startCustService
I/AppConfig( 6556): Total System Memory = 2995761152
D/LGDMClient( 3943): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 3943): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
W/ContextImpl( 3943): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
D/SystemHelper( 6556): region [EU], country [EU], operator [OPEN], sub-operator []
W/ContextImpl( 3943): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,D/LGDMClient( 3943): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=3, isUserType=1
I/LGDMClient( 3943): [DmServiceProcessor.java] [processNetworkChanged()] : [91] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
D/LGDMClient( 3943): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 3943): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
I/ReaderUtils( 6539): PortraitW 1440 LandscapeW 2392 SmallestSize 1340 LargestSize 2392 textZoom 4.4999995 isTablet false Memory 256
,V/DownloadManager( 3304): Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
V/DownloadManager( 3304): DownloadService onCreate
W/ContextImpl( 3943): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:141 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:180 android.app.IntentService$ServiceHandler.handleMessage:65 
I/DownloadManager( 3304): in removeSpuriousFiles
V/DownloadManager( 3304): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3304): created cursor android.database.sqlite.SQLiteCursor@1346c702 on behalf of 3304
I/DownloadManager( 3304): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGMyGuide_4.40.09_COM_COM_20150430011620058_RELG-D855.apk
I/DownloadManager( 3304): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGBackup_4.50.37_COM_COM_20150608234245157.apk
I/DownloadManager( 3304): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/CalendarProvider_4.2.8_COM_COM_20150304234552863_RELG-D855.apk
I/DownloadManager( 3304): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calendar_4.40.16_COM_COM_20150304234554754_RELG-D855.apk
I/DownloadManager( 3304): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.10_COM_COM_20150521235426173_RELG-D855.apk
I/DownloadManager( 3304): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQVoiceplusN_2.3.3_COM_COM_20150604065210803.apk
I/DownloadManager( 3304): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.11_COM_COM_v2_20150911144028620_RELG-D855_21.apk
I/DownloadManager( 3304): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQMemoplus(LG-D855_user)_20150902050954661.apk
I/DownloadManager( 3304): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/RemoteCall_4.1.10_COM_COM_20150817053748728.apk
I/DownloadManager( 3304): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/rspermlge(6713)_20150901080430397.apk
I/DownloadManager( 3304): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGBackup_4.51.57_COM_COM_8275_2_20151201044833536_RELG-D855_21.apk
I/DownloadManager( 3304): in trimDatabase
V/DownloadManager( 3304): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
V/DownloadManager( 3304): created cursor android.database.sqlite.SQLiteCursor@33518813 on behalf of 3304
,I/ActivityManager( 1031): Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=6585 uid=10023 gids={50023, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,V/DownloadManager( 3304): DownloadService onStartCommand
E/LGDMClient( 3943): [DmNotiService.java] [onCreate()] : [148] : DmNotiService.onCreate()
D/LGDMClient( 3943): [DmNotiService.java] [onStartCommand()] : [182] : in the new onStartCommand()
D/LGDMClient( 3943): [DmNotiService.java] [handleStart()] : [203] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
V/DownloadManager( 3304): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3304): created cursor android.database.sqlite.SQLiteCursor@de514e on behalf of 3304
V/DownloadManager( 3304): processing inserted download 1
V/DownloadManager( 3304): processing inserted download 4
V/DownloadManager( 3304): processing inserted download 7
V/DownloadManager( 3304): processing inserted download 8
V/DownloadManager( 3304): processing inserted download 9
,V/DownloadManager( 3304): processing inserted download 10
V/DownloadManager( 3304): processing inserted download 16
I/GoogleURLConnFactory( 2057): Using platform SSLCertificateSocketFactory
I/VacuumService( 2057): Vacuum at: now=1454092148784 tag=VacuumService
V/DownloadManager( 3304): processing inserted download 17
,V/DownloadManager( 3304): processing inserted download 18
V/DownloadManager( 3304): processing inserted download 21
W/Uploader( 2057): No account for auth token provided
V/DownloadManager( 3304): processing inserted download 22
I/ActivityManager( 1031): Start proc com.android.chrome for service com.android.chrome/com.google.android.apps.chrome.sync.ChromeBrowserSyncAdapterService: pid=6605 uid=10057 gids={50057, 9997, 3003, 1028, 1015} abi=armeabi-v7a
D/GpsLocationProvider( 1031): updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/DownloadManager( 3304): DownloadService onDestroy
,W/GAV2    ( 6539): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
D/libc-netbsd(  335): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  335): res_queryN name = play.googleapis.com, class = 1, type = 1
,W/ResourcesManager( 6585): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6585): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 6585): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
W/ResourcesManager( 6585): Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
,E/GpsLocationProvider( 1031): No APN found to select.
I/BooksApp( 6539): Created application version: 3.2.35 (30235)
,W/DriveInitializer( 2332): Background init thread started
,I/ActivityManager( 1031): Killing 5821:com.google.android.apps.docs/u0a61 (adj 15): empty #17
,D/libc-netbsd(  335): res_queryN name = play.googleapis.com succeed
E/VoldCmdListener(  278): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  278): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.gms/files/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 2332): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.gms/files
,W/DriveInitializer( 2332): Awaiting to be initialized
,W/libprocessgroup( 1031): failed to open /acct/uid_10061/pid_5821/cgroup.procs: No such file or directory
,I/LGEmail ( 6585): [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
D/LGEmail ( 6585): user build Type == true (at Util.java isUserModeBuildType 3507)[v:6.41.18]
,I/BooksSync( 6539): Starting books sync
,D/DelayedSyncController( 6605): Delaying sync.
I/ActivityManager( 1031): Killing 5529:com.google.android.apps.plus/u0a97 (adj 15): empty #17
,W/ResourceType( 6585): No package identifier when getting value for resource number 0x00000000
,W/libprocessgroup( 1031): failed to open /acct/uid_10097/pid_5529/cgroup.procs: No such file or directory
,W/DriveInitializer( 2332): Background init thread ended
,E/Auth.Api.Credentials( 2332): [CredentialSyncAdapter] Unknown sync event.
D/LgDataFeature( 6585): LgDataFeature() Constructor: none
D/LgDataFeature( 6585): LgDataFeature() Constructor Done, null
,W/Uploader( 2057): No account for auth token provided
D/eas_req ( 6585): ---addEventToQueue() easCode=2, requestId=0 (at EasSupport.java addEventToQueue 69)
,D/BooksSync( 6539): started syncMyEbooks
,I/HubEmail( 6585): JNI_OnLoad()
I/HubEmail( 6585): -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 6585): registerNatives()
I/HubEmail( 6585): -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 6585): registerNativeMethods()
I/HubEmail( 6585): -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
W/art     ( 6585): JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
,W/Settings( 6585): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 6585): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/LgeMiscReceiver( 3252): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
,I/LgeMiscReceiver( 3252): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 3252): networkInfo.isConnected() = true
D/PhoneState( 3252): setPdpRejectCasuse : false
D/libc-netbsd(  335): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  335): res_queryN name = static-avc.lglime.com, class = 1, type = 1
D/libc-netbsd(  335): default dns: query_ipv6=0, query_ipv4=1
,D/libc-netbsd(  335): res_queryN name = www.google.com, class = 1, type = 1
I/ActivityManager( 1031): Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=6667 uid=10062 gids={50062, 9997, 4002, 3003, 1028} abi=armeabi-v7a
,V/GLSActivity( 2057): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/Uploader( 2057):  no longer exists, so no auth token.
,I/GLSUser ( 2057): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2057): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2057): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2057): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2057): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/ThermalEngine(  350): Thermal-Server: Thermal received msg from  override
I/Thermal-Lib( 3122): Thermal-Lib-Client: Client request sent
D/libc-netbsd(  335): res_queryN name = www.google.com succeed
,D/libc-netbsd(  335): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  335): res_queryN name = clients3.google.com, class = 1, type = 1
D/libc-netbsd(  335): res_queryN name = clients3.google.com succeed
D/DrmBroadcastReceiver( 6667): Receive CONNECTIVITY_ACTION
D/DrmBroadcastReceiver( 6667): 1  network is available. Sync DRM Time with NTP
V/DrmService( 6667): Service onCreate
,D/DrmService( 6667): Received new request = 2
I/DrmSntpClient( 6667): Start Sync process
D/DrmSntpClient( 6667): Server : 0
D/libc-netbsd(  335): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  335): res_queryN name = pool.ntp.org, class = 1, type = 1
I/art     ( 2057): Explicit concurrent mark sweep GC freed 25237(1362KB) AllocSpace objects, 1(39KB) LOS objects, 51% free, 30MB/62MB, paused 578us total 35.063ms
,I/ActivityManager( 1031): Start proc com.lge.sizechangable.weather for broadcast com.lge.sizechangable.weather/.layout.WeatherWidget: pid=6690 uid=10085 gids={50085, 9997, 3003, 1028, 1015} abi=armeabi-v7a
D/libc-netbsd(  335): res_queryN name = static-avc.lglime.com succeed
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-56 f=2412 sc=60 link=72 tx=6.8, 0.0, 0.0  rx=5.5 bcn=0 [on:0 tx:0 rx:0 period:2804] from screen [on:0 period:-1901763714] gl rssi=-56 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-56 f=2412 sc=60 link=72 tx=6.8, 0.0, 0.0  rx=5.5 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-1901763713] gl rssi=-56 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
D/StatusBar.NetworkController( 1468): refreshViews: Data not connected!! Set no data type icon / Roaming
V/NotificationService( 1031): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/ZenLog  ( 1031): intercepted: 0|com.google.android.gms|1|null|10005,none
V/NotificationService( 1031): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1031): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1031): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1031): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
W/GLSActivity( 2057): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2057): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2057): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2057): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2057): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2057): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2057): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 6539): Authentication error
E/BooksAccountManager( 6539): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6539): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6539): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6539): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6539): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6539): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6539): null auth token
W/ResourcesManager( 1412): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 1412): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
W/ResourcesManager( 1468): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 1468): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
D/libc-netbsd(  335): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  335): res_queryN name = www.googleapis.com, class = 1, type = 1
D/LgeQuickCoverNLService( 1412): onNotificationPosted
V/WifiInternetCheck( 1031): isHttpConnectionAvailable - We got a valid response : 204
,D/libc-netbsd(  335): res_queryN name = www.googleapis.com succeed
,D/libc-netbsd(  335): res_queryN name = pool.ntp.org succeed
,I/art     ( 1031): Explicit concurrent mark sweep GC freed 29122(1319KB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 44MB/66MB, paused 1.076ms total 76.335ms
I/ActivityManager( 1031): Start proc com.google.android.apps.plus for service com.google.android.apps.plus/.service.EsSyncAdapterService: pid=6709 uid=10097 gids={50097, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,D/SmartCoverUpdateMonitor( 1412): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1412): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1412): handleNotificationPosted(true)
D/QuickCircle( 1412): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1412): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1412): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1412): post do add job
D/LgeQuickCoverNotificationData( 1412): add : 2
D/LgeQuickCoverNotificationData( 1412): do add job
D/LgeQuickCoverNotificationData( 1412): showAll3
D/LgeQuickCoverNotificationData( 1412): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1412): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1412): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1412): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1412): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1412): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1412): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1412): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1412): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1412): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1412): updateNotificationData: count=3
,I/LGDrmClient( 6667): _DRM_ServiceGet() : Bind lgdrm service
V/ILGDrmService(  345): eDRM_SetDRMTime +++
I/LGDRM   (  345): [DRM] SET TIME : YR=2016, MON=1, DAY=29
I/LGDRM   (  345): [DRM] SET TIME : HR=18, MIN=29, SEC=8
V/ILGDrmService(  345): eDRM_SetDRMTime ---
I/DrmSntpClient( 6667): Synched
,D/DrmService( 6667): Completed !! request = 2
D/DrmService( 6667): Request count = 0
D/QuickStatusbarLayout( 1412): Notification difference=198
D/QuickStatusbarLayout( 1412): child = android.widget.LinearLayout{20ebe075 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
V/FormManager( 6270): There are no updated forms. The schedule will be deleted.
V/FormManager( 6270): Alarm would be updated, because LastCheckTime has been updated.
V/DrmService( 6667): Service onDestroy
I/ActivityManager( 1031): Killing 5870:com.lge.eula/1000 (adj 15): empty #17
W/ResourcesManager( 6709): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/art     ( 6690): Almond Protected OAT
W/libprocessgroup( 1031): failed to open /acct/uid_1000/pid_5870/cgroup.procs: No such file or directory
,D/WeatherApplication( 6690): removeAccount
D/WeatherApplication( 6690): Account.length = 0
E/WeatherApplication( 6690): OPERATOR:OPEN
I/ActivityManager( 1031): Killing 5888:com.google.android.gms.wearable/u0a5 (adj 15): empty #17
D/WeatherAncestor( 6690): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 19:29:9
D/Weather.Utils( 6690): 2 : the weather widgets(using time tick) are gone.
D/Weather.Utils( 6690): 2 : All the weather widget is gone.
D/UpdateThreadPoolManager( 6690): 2 : This is isUpdating : false
D/WeatherAncestor( 6690): connectivity changed - connection : true
D/WeatherService( 6690): 2 : isServiceAlived():false forecastCache:null
,D/ForecastDataCache( 6690): 2 : lastUpdatedTime: 1430558561343
D/ForecastDataCache( 6690): 2 : currentPackageVersion: 4.40.4
D/ForecastDataCache( 6690): 2 : Cache is not up-to-date, count: 0
D/Weather_cast( 6690): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherAncestor( 6690): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 19:29:9
,W/ApiaryClient( 6539): Error response from books API: {
W/ApiaryClient( 6539):  "error": {
W/ApiaryClient( 6539):   "errors": [
W/ApiaryClient( 6539):    {
W/ApiaryClient( 6539):     "domain": "global",
W/ApiaryClient( 6539):     "reason": "required",
W/ApiaryClient( 6539):     "message": "Login Required",
W/ApiaryClient( 6539):     "locationType": "header",
W/ApiaryClient( 6539):     "location": "Authorization"
W/ApiaryClient( 6539):    }
W/ApiaryClient( 6539):   ],
W/ApiaryClient( 6539):   "code": 401,
W/ApiaryClient( 6539):   "message": "Login Required"
W/ApiaryClient( 6539):  }
W/ApiaryClient( 6539): }
W/ApiaryClient( 6539): errCount = 1: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6539): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=7574217007443831795&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6539): Headers:
W/ApiaryClient( 6539): accept-encoding: [gzip]
W/ApiaryClient( 6539): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6539): gdata-version: 2
,I/ActivityManager( 1031): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=6730 uid=10093 gids={50093, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager( 1031): Killing 5991:com.google.android.talk/u0a72 (adj 15): empty #17
,W/libprocessgroup( 1031): failed to open /acct/uid_10005/pid_5888/cgroup.procs: No such file or directory
,W/libprocessgroup( 1031): failed to open /acct/uid_10072/pid_5991/cgroup.procs: No such file or directory
E/VoldCmdListener(  278): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  278): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6730): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
,E/VoldCmdListener(  278): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  278): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6730): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
E/VoldCmdListener(  278): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  278): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6730): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
E/VoldCmdListener(  278): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  278): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
,W/Vold    (  278): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6730): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
I/GLSActivity( 2057): [ac] getting account id
I/GLSUser ( 2057): [t] Fetched account id for thalitester@gmail.com : 105256135866144380227
,V/GLSActivity( 2057): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2057): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.syncadapters.contacts, service: cp
I/GLSUser ( 2057): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> cp without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 2057): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2057): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2057): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/WebViewFactory( 6730): Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
I/LibraryLoader( 6730): Loading: webviewchromium
,I/LibraryLoader( 6730): Time to load native libraries: 3 ms (timestamps 6628-6631)
I/LibraryLoader( 6730): Expected native library version number "",actual native library version number ""
V/NotificationService( 1031): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
V/NotificationService( 1031): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1031): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1031): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1031): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
W/GLSActivity( 2057): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2057): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2057): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2057): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2057): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2057): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2057): 	at android.os.Binder.execTransact(Binder.java:446)
D/LgeQuickCoverNLService( 1412): onNotificationPosted
D/ContactsSyncAdapter( 2057): innerSync failed
D/ContactsSyncAdapter( 2057): com.google.wireless.gdata2.client.AuthenticationException: unable to get auth token android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
D/ContactsSyncAdapter( 2057): 	at com.google.android.syncadapters.contacts.AuthInfo.getAuthToken(AuthInfo.java:45)
D/ContactsSyncAdapter( 2057): 	at com.google.android.syncadapters.contacts.ContactsSyncAdapter.innerPerformSync(ContactsSyncAdapter.java:263)
D/ContactsSyncAdapter( 2057): 	at com.google.android.syncadapters.contacts.ContactsSyncAdapter.onPerformLoggedSync(ContactsSyncAdapter.java:168)
D/ContactsSyncAdapter( 2057): 	at com.google.android.common.LoggingThreadedSyncAdapter.onPerformSync(LoggingThreadedSyncAdapter.java:33)
D/ContactsSyncAdapter( 2057): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
D/ContactsSyncAdapter( 2057): Caused by: android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
D/ContactsSyncAdapter( 2057): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
D/ContactsSyncAdapter( 2057): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
D/ContactsSyncAdapter( 2057): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
D/ContactsSyncAdapter( 2057): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
D/ContactsSyncAdapter( 2057): 	at android.os.Binder.execTransact(Binder.java:446)
D/SmartCoverUpdateMonitor( 1412): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1412): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1412): handleNotificationPosted(true)
D/QuickCircle( 1412): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1412): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1412): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1412): post do just update job
D/LgeQuickCoverNotificationData( 1412): showAll3
D/LgeQuickCoverNotificationData( 1412): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1412): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1412): showAll() ID : 262082,0|com.lge.e,ula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1412): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1412): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1412): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1412): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1412): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1412): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1412): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1412): updateNotificationData: count=3
V/WebViewChromiumFactoryProvider( 6730): Binding Chromium to main looper Looper (main, tid 1) {576874c}
I/LibraryLoader( 6730): Expected native library version number "",actual native library version number ""
I/chromium( 6730): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
D/SyncManager( 1031): failed sync operation thalitester@gmail.com u0 (com.google), com.android.contacts, LOCAL, currentRunTime 26691, reason: 10019, SyncResult: stats [ numAuthExceptions: 1]
I/BrowserStartupController( 6730): Initializing chromium process, renderers=0
D/SyncManager( 1031): not retrying sync operation because the error is a hard error: thalitester@gmail.com u0 (com.google), com.android.contacts, LOCAL, currentRunTime 268254, reason: 10019
W/art     ( 6730): Attempt to remove local handle scope entry from IRT, ignoring
,W/chromium( 6730): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
D/QuickStatusbarLayout( 1412): Notification difference=198
D/QuickStatusbarLayout( 1412): child = android.widget.LinearLayout{20ebe075 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
I/chromium( 6730): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=38 off=46780 len=2953
I/chromium( 6730): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:39 off:229536 len:643667
I/Adreno-EGL( 6730): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 6730): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 6730): Build Date: 12/12/14 금
I/Adreno-EGL( 6730): Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
I/Adreno-EGL( 6730): Remote Branch: 
I/Adreno-EGL( 6730): Local Patches: 
I/Adreno-EGL( 6730): Reconstruct Branch: 
,V/AudioPolicyService(  340): registerClient() client 0xb14fd380, uid 10093
,W/AudioManagerAndroid( 6730): Requires BLUETOOTH permission
D/DelayedSyncController( 6605): Delaying sync.
,I/NSApplication( 6730): Starting up...
,I/ActivityManager( 1031): Killing 4850:com.android.vending/u0a44 (adj 15): empty #17
W/libprocessgroup( 1031): failed to open /acct/uid_10044/pid_4850/cgroup.procs: No such file or directory
,D/libc-netbsd(  335): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  335): res_queryN name = mtalk.google.com, class = 1, type = 1
,I/iu.SyncManager( 2332): SYNC; picasa accounts
D/NetworkLogImpl( 2332): Loaded NetworkSpeedPredictor
I/iu.Environment( 2332): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/iu.UploadsManager( 2332): num queued entries: 0
I/iu.UploadsManager( 2332): num updated entries: 0
I/iu.SyncManager( 2332): NEXT; no task
D/ChimeraCfgMgr( 2332): Loading module com.google.android.gms.kids from APK com.google.android.gms
D/ChimeraCfgMgr( 2332): Loading module com.google.android.gms.kids from APK com.google.android.gms
D/libc-netbsd(  335): res_queryN name = mtalk.google.com succeed
D/PostponalbeReceiver( 6386): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.intent.action.TIME_SET'.
,I/ActivityManager( 1031): Start proc com.lge.clock for broadcast com.lge.clock/.alarmclock.ALBootInit: pid=6808 uid=10010 gids={50010, 9997, 3003, 1028, 4002} abi=armeabi-v7a
,I/GLSUser ( 2057): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: ac2dm
I/GLSUser ( 2057): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> ac2dm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2057): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2057): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2057): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/NotificationService( 1031): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1031): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1031): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1031): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1031): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1412): onNotificationPosted
D/SmartCoverUpdateMonitor( 1412): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1412): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1412): handleNotificationPosted(true)
D/QuickCircle( 1412): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1412): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1412): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1412): post do just update job
D/LgeQuickCoverNotificationData( 1412): showAll3
D/LgeQuickCoverNotificationData( 1412): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1412): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1412): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1412): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1412): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1412): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1412): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1412): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1412): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1412): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1412): updateNotificationData: count=3
D/ALBootInit( 6808): ====action==>android.intent.action.TIME_SET
D/ALBootInit( 6808): Alarm ALBootInit: TIME_SET
,D/Alarms  ( 6808): [setNextAlert] start
W/Kids    ( 2332): [AccountUtils] Account not ready
W/Kids    ( 2332): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/Kids    ( 2332): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/Kids    ( 2332): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/Kids    ( 2332): 	at com.google.android.gms.auth.p.c(SourceFile:550)
W/Kids    ( 2332): 	at com.google.android.gms.auth.p.b(SourceFile:477)
W/Kids    ( 2332): 	at com.google.android.gms.kids.account.k.d(SourceFile:103)
W/Kids    ( 2332): 	at com.google.android.gms.kids.account.p.a(SourceFile:70)
W/Kids    ( 2332): 	at com.google.android.gms.kids.account.t.a(SourceFile:62)
W/Kids    ( 2332): 	at com.google.android.gms.chimera.f.run(SourceFile:179)
W/Kids    ( 2332): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Kids    ( 2332): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Kids    ( 2332): 	at java.lang.Thread.run(Thread.java:818)
D/Alarms  ( 6808): [setNextAlert] (1)
D/Alarms  ( 6808):  minTime  = 0
D/Alarms  ( 6808):  -- OK multi -- 0
E/jeny.kim( 6808): [setNextAlert] setNextAlert  temp_Alarmlink + 
,E/jeny.kim( 6808): [setNextAlert]setNextAlert temp_AlarmLinkText + 
D/QuickStatusbarLayout( 1412): Notification difference=198
D/QuickStatusbarLayout( 1412): child = android.widget.LinearLayout{20ebe075 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
I/CommonUtil( 6808): BUILD Country: EU
D/Alarms  ( 6808): broadcastToWidgetProvider : false
,D/Alarms  ( 6808): Enter formatDayAndTime(final Context context, long timeInMiliSec)
V/SettingsProvider( 1031): call_put(system:next_alarm_formatted=) for 0 calling package = com.lge.clock
I/DigitalAppWidgetProvider( 6808): onReceive: android.intent.action.TIME_SET
V/DigitalAppWidgetProvider( 6808): cancelAlarmOnQuarterHour android.app.ReceiverRestrictedContext@125ecfa2
V/DigitalAppWidgetProvider( 6808): startAlarmOnQuarterHour android.app.ReceiverRestrictedContext@125ecfa2
,D/QuickCoverProvider( 6808): onReceiver
I/indal   ( 1412): SmartCoverWidgetContext createApplicationContext
I/indal   ( 1412): SmartCoverWidgetContext createApplicationContext
D/WeatherAncestor( 6690): 2 : onReceive, action: android.intent.action.TIME_SET, Time(hour:min:sec) 19:29:10
D/Weather.Utils( 6690): 2 : the weather widgets(using time tick) are gone.
D/Weather.Utils( 6690): 2 : All the weather widget is gone.
D/UpdateThreadPoolManager( 6690): 2 : This is isUpdating : false
D/WeatherService( 6690): 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@2eedf433
,D/ForecastDataCache( 6690): 2 : lastUpdatedTime: 1430558561343
D/ForecastDataCache( 6690): 2 : currentPackageVersion: 4.40.4
D/ForecastDataCache( 6690): 2 : Cache is up-to-date, count: 0
D/Weather_cast( 6690): 2 : set auto-update time : 1/29 22:29
D/WeatherAncestor( 6690): 2 : onReceive has processed, action: android.intent.action.TIME_SET, Time(hour:min:sec) 19:29:10
I/ActivityManager( 1031): Start proc com.qualcomm.timeservice for broadcast com.qualcomm.timeservice/.TimeServiceBroadcastReceiver: pid=6832 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi
I/ActivityManager( 1031): Killing 5905:com.lge.bnr/1000 (adj 15): empty #17
,D/GCM     ( 2057): Connected
,W/libprocessgroup( 1031): failed to open /acct/uid_1000/pid_5905/cgroup.procs: No such file or directory
,D/GCM     ( 2057): Message class com.google.f.a.a.p
D/TimeService( 6832): Receivedandroid.intent.action.TIME_SET intent. Current Time is 1454092150858
D/        ( 6832): TimeServiceNative: User Time to be set is 1454092150858
,D/QC-time-services( 6832): Lib:time_genoff_operation: pargs->base = 2
D/QC-time-services( 6832): Lib:time_genoff_operation: pargs->operation = 0
D/QC-time-services( 6832): Lib:time_genoff_operation: pargs->ts_val = 1454092150858
D/QC-time-services( 6832): Lib:time_genoff_operation: Send to server  passed!!
D/QC-time-services(  369): Daemon: Connection accepted:time_genoff
D/QC-time-services(  369): Daemon:Received base = 2, unit = 1, operation = 0,value = 1454092150858
D/QC-time-services(  369): Daemon:genoff_opr: Base = 2, val = 1454092150858, operation = 0
D/QC-time-services(  369): Daemon:rtc_get: Time read from RTC -- MM/DD/YY HH:MM:SS5/8/70 11:41:20
D/QC-time-services(  369): Daemon:Value read from RTC seconds = 13693280000
D/QC-time-services(  369): Daemon:new time 1454092150858 
D/QC-time-services(  369): Daemon: delta 1440398870858 genoff 1440398870858 
D/QC-time-services(  369): Daemon:genoff_persistent_update: Writing genoff = 1440398870858 to memory
D/QC-time-services(  369): Daemon:Opening File: /data/time/ats_2
D/QC-time-services(  369): Daemon:time_persistent_memory_opr:Genoff write operation 
D/QC-time-services(  369): Updating the TOD offset
D/QC-time-services(  369): Daemon:genoff_persistent_update: Writing genoff = 1440398870858 to memory
D/QC-time-services(  369): Daemon:Opening File: /data/time/ats_1
,D/QC-time-services(  369): Daemon:time_persistent_memory_opr:Genoff write operation 
E/QC-time-services(  369): Daemon:Update to modem bit set
D/QC-time-services(  369): Daemon:genoff_send_modem: Sending data to MODEM !
D/QC-time-services(  369): Daemon: Base = 2, Value being sent to MODEM = 1124434070858
E/QC-time-services( 6832): Receive Passed == base = 2, unit = 1, operation = 0, result = 0
E/QC-time-services(  369): Daemon:tod_update_ind_cb: Got Update from modem msg_id 40
E/QC-time-services(  369): Daemon: Time-services: Waiting to acceptconnection
I/ActivityManager( 1031): Start proc com.android.calendar for broadcast com.android.calendar/.widget.CalendarAppWidgetProvider: pid=6853 uid=10013 gids={50013, 9997, 3003, 1028, 1015} abi=armeabi
I/ActivityManager( 1031): Killing 6253:com.lge.lifetracker/u0a37 (adj 15): empty #17
,I/art     (  360): Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 209us total 9.404ms
I/art     (  360): Explicit concurrent mark sweep GC freed 8(256B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 182us total 9.423ms
,I/art     (  360): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 181us total 9.866ms
,I/art     ( 1031): Explicit concurrent mark sweep GC freed 24283(1090KB) AllocSpace objects, 3(304KB) LOS objects, 33% free, 44MB/66MB, paused 1.559ms total 75.340ms
,W/libprocessgroup( 1031): failed to open /acct/uid_10037/pid_6253/cgroup.procs: No such file or directory
V/GLSActivity( 2057): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/ResourcesManager( 6853): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/GLSUser ( 2057): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2057): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2057): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2057): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2057): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1031): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1031): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1031): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1031): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1031): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1412): onNotificationPosted
D/SmartCoverUpdateMonitor( 1412): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1412): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1412): handleNotificationPosted(true)
D/QuickCircle( 1412): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1412): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1412): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1412): post do just update job
D/LgeQuickCoverNotificationData( 1412): showAll3
D/LgeQuickCoverNotificationData( 1412): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1412): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1412): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1412): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1412): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1412): isNotificationForCurrentUser : true
,D/LgeQuickCoverOverlayWindow( 1412): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1412): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1412): [native noti] inex =  2
W/GLSActivity( 2057): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2057): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2057): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2057): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2057): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2057): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2057): 	at android.os.Binder.execTransact(Binder.java:446)
D/LgeQuickCoverNotificationData( 1412): isNotificationForCurrentUser : true
,E/LgeQuickCoverOverlayWindow( 1412): updateNotificationData: count=3
E/BooksAccountManager( 6539): Authentication error
E/BooksAccountManager( 6539): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6539): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6539): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6539): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6539): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6539): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6539): null auth token
D/CalendarApplication( 6853): CalendarApplication.onCreate()
D/PreferenceKeysParser( 6853): [debug_displayParseInfos] preference keys.size() = 44
,D/PreferenceKeysParser( 6853): [debug_displayParseInfos] preference keys = {lg_preferences_tardis_1=com.android.calendar.adaptation.PreferenceKey$KeyData@39ec4931, lg_preferences_hide_declined=com.android.calendar.adaptation.PreferenceKey$KeyData@34ce4816, lg_preferences_default_reminder=com.android.calendar.adaptation.PreferenceKey$KeyData@2ccf9597, lg_preferences_month_view_style=com.android.calendar.adaptation.PreferenceKey$KeyData@1dc0e384, lg_preferences_alerts_ringtone=com.android.calendar.adaptation.PreferenceKey$KeyData@2c8b476d, lg_preferences_device_tz=com.android.calendar.adaptation.PreferenceKey$KeyData@125ecfa2, lg_preferences_debug_datesearch=com.android.calendar.adaptation.PreferenceKey$KeyData@2eedf433, lg_preferences_debug_country=com.android.calendar.adaptation.PreferenceKey$KeyData@e2ab3f0, lg_preferences_display_weather_information=com.android.calendar.adaptation.PreferenceKey$KeyData@26a1ed69, lg_preferences_alerts_vibrateWhen=com.android.calendar.adaptation.PreferenceKey$KeyData@117e43ee, lg_preferences_debug_rtl=com.android.calendar.adaptation.PreferenceKey$KeyData@2389a08f, lg_preferences_alerts_type=com.android.calendar.adaptation.PreferenceKey$KeyData@e1f1f1c, lg_preferrences_country_code=com.android.calendar.adaptation.PreferenceKey$KeyData@2a62f725, lg_preferences_weather_info=com.android.calendar.adaptation.PreferenceKey$KeyData@3f0eb0fa, lg_preference_holiday_calendar_ver=com.android.calendar.adaptation.PreferenceKey$KeyData@2e89b6ab, lg_preferences_show_controls=com.android.calendar.adaptation.PreferenceKey$KeyData@398d1108, lg_preferences_user_select_noti_sound=com.android.calendar.adaptation.PreferenceKey$KeyData@3070e0a1, lg_preference_default_myphonebook=com.android.calendar.adaptation.PreferenceKey$KeyData@2206e2c6, lg_preferences_skip_setup=com.android.calendar.adaptation.PreferenceKey$KeyData@12b1287, lg_preferred_startView=com.android.calendar.adaptation.PreferenceKey$KeyData@3a6635b4, lg_preferences_debug_operator=com.android.calendar.adaptation.PreferenceKey$KeyData@3f19e5dd, lg_preferences_exclude_sticker_list=com.android.calendar.adaptation.PreferenceKey$KeyData@27fe6552, lg_preferences_writable_calendars_count=com.android.calendar.adaptation.PreferenceKey$KeyData@399c5023, lg_preferred_detailedView=com.android.calendar.adaptation.PreferenceKey$KeyData@60af920, lg_preferences_debug_floating=com.android.calendar.adaptation.PreferenceKey$KeyData@395402d9, lg_preferences_home_tz=com.android.calendar.adaptation.PreferenceKey$KeyData@e79849e, lg_preferences_home_tz_enabled=com.android.calendar.adaptation.PreferenceKey$KeyData@2059cb7f, lg_preference_received_provider_reminder_broadcast=com.android.calendar.adaptation.PreferenceKey$KeyData@576874c, lg_preferences_default_cell_height=com.android.calendar.adaptation.PreferenceKey$KeyData@2178f395, lg_preferences_notification_type=com.android.calendar.adaptation.PreferenceKey$KeyData@14f54caa, lg_preferences_show_week_num=com.android.calendar.adaptation.PreferenceKey$KeyData@1f49a09b, lg_preferences_dont_show_again_no_online_account=com.android.calendar.adaptation.PreferenceKey$KeyData@142acc38, lg_preferences_alerts_popup=com.android.calendar.adaptation.PreferenceKey$KeyData@bc23411, lg_preferences_week_start_day=com.android.calendar.adaptation.PreferenceKey$KeyData@3b38976, lg_preferences_app_version=com.android.calendar.adaptation.PreferenceKey$KeyData@e97ab77, lg_preferences_alerts=com.android.calendar.adaptation.PreferenceKey$KeyData@1dc73e4, lg_preferences_select_aux_calendar=com.android.calendar.adaptation.PreferenceKey$KeyData@3c85004d, lg_preferences_widget_info_calendars=com.android.calendar.adaptation.PreferenceKey$KeyData@1346c702, lg_preferences_alerts_default_ringtone=com.android.calendar.adaptation.PreferenceKey$KeyData@33518813, lg_preference_defaultCalendar=com.android.calendar.adaptation.PreferenceKey$KeyData@2deea50, lg_preferences_alerts_vibratetype=com.android.calendar.adaptation.PreferenceKey$KeyData@2e2e5449, lg_preferences_recent_timezones=com.android.calendar.adaptation.PreferenceKey$KeyData@de514e, l
D/GeneralP,referenceUtils( 6853): [migratePrefrenceKeys] Exit: Version(44001600) >= 42001300
D/QuickStatusbarLayout( 1412): Notification difference=198
D/QuickStatusbarLayout( 1412): child = android.widget.LinearLayout{20ebe075 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
D/Config  ( 6853): [init]
,I/Config  ( 6853): LGCalendar ver.4.40.16
I/Config  ( 6853): start check model
I/Config  ( 6853): start check native_ca
I/Config  ( 6853): Config Operator=OPEN, Country=EU
D/Config  ( 6853): [setDefaultValuesToPref]
D/Config  ( 6853): [parseProfiles]
D/ProfilesParser( 6853): [debug_displayParseInfos] profile.country = null
D/ProfilesParser( 6853): [debug_displayParseInfos] profile.operator = null
D/Config  ( 6853): [updateProfiletoCountryInfo]
D/GeneralPreference( 6853): [checkAndMigrateOldPreference]
E/AgendaWidgetManager( 6853): [updateWidgets] 
,I/InitNotificationRingtoneService( 6853): Start InitializeAlertRingtoneService.onHandleIntent
I/AlertUtils( 6853): [setFormatNotificationSound] current noti URI = content://media/internal/audio/media/41
I/AlertUtils( 6853): [getCalendarNotiSoundURIFromCursor] getCount()= 21
,I/AlertUtils( 6853): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Arpeggio.ogg
,I/AlertUtils( 6853): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Country_Blues.ogg
I/AlertUtils( 6853): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Crystal.ogg
I/AlertUtils( 6853): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Dewdrop.ogg
,I/AlertUtils( 6853): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Ding_Dong.ogg
I/AlertUtils( 6853): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Echo.ogg
I/AlertUtils( 6853): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Email.ogg
I/AlertUtils( 6853): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Game_Over.ogg
,I/AlertUtils( 6853): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Gayageum.ogg
I/AlertUtils( 6853): [getMediaFilepathFromContentUri] filepath = /system/media/audio/alarms/Afternoon_Walk.ogg
I/AlertUtils( 6853): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Harmonics.ogg
I/AlertUtils( 6853): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Idea.ogg
,I/AlertUtils( 6853): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/News.ogg
W/ApiaryClient( 6539): Error response from books API: {
W/ApiaryClient( 6539):  "error": {
W/ApiaryClient( 6539):   "errors": [
W/ApiaryClient( 6539):    {
W/ApiaryClient( 6539):     "domain": "global",
W/ApiaryClient( 6539):     "reason": "required",
W/ApiaryClient( 6539):     "message": "Login Required",
W/ApiaryClient( 6539):     "locationType": "header",
W/ApiaryClient( 6539):     "location": "Authorization"
W/ApiaryClient( 6539):    }
W/ApiaryClient( 6539):   ],
W/ApiaryClient( 6539):   "code": 401,
W/ApiaryClient( 6539):   "message": "Login Required"
W/ApiaryClient( 6539):  }
W/ApiaryClient( 6539): }
W/ApiaryClient( 6539): errCount = 2: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6539): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=7574217007443831795&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6539): Headers:
W/ApiaryClient( 6539): accept-encoding: [gzip]
W/ApiaryClient( 6539): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6539): gdata-version: 2
I/AlertUtils( 6853): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Pebble.ogg
I/AlertUtils( 6853): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Schedule.ogg
I/AlertUtils( 6853): [getCalendarNotiSoundURIFromCursor] filePath = /system/media/audio/notifications/Schedule.ogg, new URI = content://media/internal/audio/media/41
I/AlertUtils( 6853): set default noti to content://media/internal/audio/media/41
D/MonthWidgetProvider( 6853): [onReceive]
,W/HolidayIntentService( 6853): onHandleIntent
D/CalendarWidgetProvider( 6853): [onReceive]
D/CalendarWidgetProvider( 6853): [CalendarWidgetProvider] got the intent: Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.android.calendar/.widget.MonthWidgetProvider }
D/HolidayDataLoader( 6853): readJsonAsset : holiday.json
D/CalendarTypeController( 6853): [onUpdateAndInitCalendarTime]
D/WeekWidgetProvider( 6853): [onReceive]
D/CalendarWidgetProvider( 6853): [onReceive]
D/CalendarWidgetProvider( 6853): [CalendarWidgetProvider] got the intent: Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.android.calendar/.widget.WeekWidgetProvider }
D/CalendarTypeController( 6853): [onUpdateAndInitCalendarTime]
I/InitNotificationRingtoneService( 6853): End InitializeAlertRingtoneService.onHandleIntent
E/HolidayIntentService( 6853): onHandleIntent:holiday data empty
,I/DigitalAppWidgetProvider( 6808): onReceive: android.intent.action.ALARM_CHANGED
D/WeatherAncestor( 6690): 2 : onReceive, action: com.lge.sizechangable.weather.action.setweathercast, Time(hour:min:sec) 19:29:11
D/Weather.Utils( 6690): 2 : the weather widgets(using time tick) are gone.
D/Weather.Utils( 6690): 2 : All the weather widget is gone.
D/UpdateThreadPoolManager( 6690): 2 : This is isUpdating : false
D/Weather_cast( 6690): 2 : Update is Canceled by com.lge.sizechangable.weather.action.alarm
D/WeatherAncestor( 6690): 2 : onReceive has processed, action: com.lge.sizechangable.weather.action.setweathercast, Time(hour:min:sec) 19:29:11
I/ActivityManager( 1031): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.realtimechat.RequestWriter$NetworkStateReceiver: pid=6883 uid=10072 gids={50072, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
I/ActivityManager( 1031): Killing 6341:com.lge.settings.easy/1000 (adj 15): empty #17
,W/libprocessgroup( 1031): failed to open /acct/uid_1000/pid_6341/cgroup.procs: No such file or directory
,W/ResourcesManager( 6883): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,D/LgDataFeature( 6883): LgDataFeature() Constructor: none
D/LgDataFeature( 6883): LgDataFeature() Constructor Done, null
,I/Babel   ( 6883): MmsConfig: mnc/mcc: 0/0
I/Babel   ( 6883): MmsConfig.loadMmsSettings
,I/Babel   ( 6883): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D855 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D855-M3-D1.xml
,I/Babel   ( 6883): MmsConfig.loadFromDatabase
,E/Babel   ( 6883): canonicalizeMccMnc: invalid mccmnc 
I/Babel   ( 6883): MmsConfig.loadFromResources
E/Babel   ( 6883): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel   ( 6883): MmsConfig.loadMmsSettings: mUserAgent=LG-D855 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D855-M3-D1.xml
W/AudioCapabilities( 6883): Unsupported mime audio/evrc
W/AudioCapabilities( 6883): Unsupported mime audio/qcelp
,W/VideoCapabilities( 6883): Unrecognized profile 2130706433 for video/avc
W/Settings( 6883): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/AudioCapabilities( 6883): Unsupported mime audio/amr-wb-plus
,W/AudioCapabilities( 6883): Unsupported mime audio/qcelp
W/AudioCapabilities( 6883): Unsupported mime audio/evrc
W/VideoCapabilities( 6883): Unsupported mime video/x-ms-wmv
W/VideoCapabilities( 6883): Unsupported mime video/divx
W/VideoCapabilities( 6883): Unsupported mime video/divx311
W/VideoCapabilities( 6883): Unsupported mime video/divx4
W/VideoCapabilities( 6883): Unsupported mime video/mp4v-esdp
,I/VideoCapabilities( 6883): Unsupported profile 4 for video/mp4v-es
,W/AudioCapabilities( 6883): Unsupported mime audio/eac3
W/AudioCapabilities( 6883): Unsupported mime audio/ac3
W/ResourcesManager( 6883): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6883): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,W/AudioCapabilities( 6883): Unsupported mime audio/g726
W/AudioCapabilities( 6883): Unsupported mime audio/wma-voice
W/AudioCapabilities( 6883): Unsupported mime audio/x-ms-wma
W/AudioCapabilities( 6883): Unsupported mime audio/adpcm
W/VideoCapabilities( 6883): Unsupported mime video/theora
W/VideoCapabilities( 6883): Unsupported mime video/mjpg
V/JNIHelp ( 6883): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,W/System  ( 6883): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/system/framework/com.google.android.media.effects.jar", zip file "/system/app/Hangouts/Hangouts.apk"],nativeLibraryDirectories=[/system/app/Hangouts/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,I/ProviderInstaller( 6883): Installed default security provider GmsCore_OpenSSL
,I/GLSUser ( 2057): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.talk, service: oauth2:https://www.googleapis.com/auth/chat https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/hangouts https://www.googleapis.com/auth/identity.plus.page.impersonation https://www.googleapis.com/auth/chat.native
I/GLSUser ( 2057): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/chat https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/hangouts https://www.googleapis.com/auth/identity.plus.page.impersonation https://www.googleapis.com/auth/chat.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 2057): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2057): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2057): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/GLSActivity( 2057): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2057): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 2057): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2057): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2057): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2057): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
E/Babel   ( 6883): UserRecoverableAuthException.
E/Babel   ( 6883): cfq: BadAuthentication
E/Babel   ( 6883): 	at cfn.a(Unknown Source)
E/Babel   ( 6883): 	at f.a(PG:191)
E/Babel   ( 6883): 	at ava.a(PG:88)
E/Babel   ( 6883): 	at ava.a(PG:128)
E/Babel   ( 6883): 	at bjs.a(PG:255)
E/Babel   ( 6883): 	at bep.a(PG:602)
E/Babel   ( 6883): 	at bep.a(PG:469)
E/Babel   ( 6883): 	at bpo.run(PG:1141)
E/Babel   ( 6883): Error getting auth token
E/Babel   ( 6883): bxl
E/Babel   ( 6883): 	at f.a(PG:201)
E/Babel   ( 6883): 	at ava.a(PG:88)
E/Babel   ( 6883): 	at ava.a(PG:128)
E/Babel   ( 6883): 	at bjs.a(PG:255)
E/Babel   ( 6883): 	at bep.a(PG:602)
E/Babel   ( 6883): 	at bep.a(PG:469)
E/Babel   ( 6883): 	at bpo.run(PG:1141)
I/Babel_RequestWriter( 6883): error sending REQ[fc:8; creat:1454091698236; type:bev-159004563]; took 177 ms (error code == 100)
E/Babel   ( 6883): Account registration failedRedacted-21
E/Babel   ( 6883): bph: null -- null
E/Babel   ( 6883): 	at ava.a(PG:120)
E/Babel   ( 6883): 	at ava.a(PG:128)
E/Babel   ( 6883): 	at bjs.a(PG:255)
E/Babel   ( 6883): 	at bep.a(PG:602)
E/Babel   ( 6883): 	at bep.a(PG:469)
E/Babel   ( 6883): 	at bpo.run(PG:1141)
I/Babel   ( 6883): Account setup failed with error state:106 account:Redacted-21
I/Babel   ( 6883): Account sign in complete with state 106account: Redacted-21
,V/NotificationService( 1031): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
V/NotificationService( 1031): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1031): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1031): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1031): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
W/GLSActivity( 2057): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2057): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2057): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2057): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2057): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2057): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2057): 	at android.os.Binder.execTransact(Binder.java:446)
D/LgeQuickCoverNLService( 1412): onNotificationPosted
I/art     ( 6883): Note: end time exceeds epoch: 
E/BooksAccountManager( 6539): Authentication error
E/BooksAccountManager( 6539): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6539): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6539): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6539): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6539): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6539): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6539): null auth token
D/SmartCoverUpdateMonitor( 1412): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1412): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1412): handleNotificationPosted(true)
D/QuickCircle( 1412): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1412): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1412): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1412): post do just update job
D/LgeQuickCoverNotificationData( 1412): showAll3
D/LgeQuickCoverNotificationData( 1412): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1412): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1412): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1412): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1412): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1412): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1412): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1412): isNotificationForCurrentUser : true
,D/LgeQuickCoverOverlayWindow( 1412): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1412): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1412): updateNotificationData: count=3
D/QuickStatusbarLayout( 1412): Notification difference=198
D/QuickStatusbarLayout( 1412): child = android.widget.LinearLayout{20ebe075 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,I/GLSUser ( 2057): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.talk, service: oauth2:https://www.googleapis.com/auth/chat https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/hangouts https://www.googleapis.com/auth/identity.plus.page.impersonation https://www.googleapis.com/auth/chat.native
I/GLSUser ( 2057): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/chat https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/hangouts https://www.googleapis.com/auth/identity.plus.page.impersonation https://www.googleapis.com/auth/chat.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2057): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2057): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2057): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/ResourcesManager( 2057): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,V/NotificationService( 1031): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
V/NotificationService( 1031): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1031): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1031): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1031): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
E/Babel   ( 6883): Unexpected exception while authenticating.
E/Babel   ( 6883): cfr: User intervention required. Notification has been pushed.
E/Babel   ( 6883): 	at cfn.b(Unknown Source)
E/Babel   ( 6883): 	at cfn.a(Unknown Source)
E/Babel   ( 6883): 	at f.a(PG:188)
E/Babel   ( 6883): 	at ava.b(PG:143)
E/Babel   ( 6883): 	at bnr.run(PG:5415)
E/Babel   ( 6883): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/Babel   ( 6883): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/Babel   ( 6883): 	at java.lang.Thread.run(Thread.java:818)
,D/LgeQuickCoverNLService( 1412): onNotificationPosted
D/SmartCoverUpdateMonitor( 1412): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1412): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1412): handleNotificationPosted(true)
D/QuickCircle( 1412): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1412): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1412): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1412): post do just update job
D/LgeQuickCoverNotificationData( 1412): showAll3
D/LgeQuickCoverNotificationData( 1412): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1412): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1412): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1412): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1412): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1412): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1412): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1412): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1412): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1412): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1412): updateNotificationData: count=3
D/QuickStatusbarLayout( 1412): Notification difference=198
D/QuickStatusbarLayout( 1412): child = android.widget.LinearLayout{20ebe075 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,W/ApiaryClient( 6539): Error response from books API: {
W/ApiaryClient( 6539):  "error": {
W/ApiaryClient( 6539):   "errors": [
W/ApiaryClient( 6539):    {
W/ApiaryClient( 6539):     "domain": "global",
W/ApiaryClient( 6539):     "reason": "required",
W/ApiaryClient( 6539):     "message": "Login Required",
W/ApiaryClient( 6539):     "locationType": "header",
W/ApiaryClient( 6539):     "location": "Authorization"
W/ApiaryClient( 6539):    }
W/ApiaryClient( 6539):   ],
W/ApiaryClient( 6539):   "code": 401,
W/ApiaryClient( 6539):   "message": "Login Required"
W/ApiaryClient( 6539):  }
W/ApiaryClient( 6539): }
W/ApiaryClient( 6539): errCount = 3: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6539): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=7574217007443831795&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6539): Headers:
W/ApiaryClient( 6539): accept-encoding: [gzip]
W/ApiaryClient( 6539): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6539): gdata-version: 2
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-50 f=2412 sc=60 link=72 tx=14.9, 0.0, 0.0  rx=10.2 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1901760707] gl rssi=-50 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-50 f=2412 sc=60 link=72 tx=14.9, 0.0, 0.0  rx=10.2 bcn=0 [on:0 tx:0 rx:0 period:0] from screen [on:0 period:-1901760707] gl rssi=-50 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
D/StatusBar.NetworkController( 1468): refreshViews: Data not connected!! Set no data type icon / Roaming
I/jxcore-log( 6098): Test app app.js loaded
I/jxcore-log( 6098): 
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6098): setDiscoveryMode: Mode set to BLE
I/jxcore-log( 6098): BLE advertisement is supported
I/jxcore-log( 6098): 
I/chromium( 6098): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,E/BooksSync( 6539): Soft error: 
E/BooksSync( 6539): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 6539): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=7574217007443831795&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 6539): Headers:
E/BooksSync( 6539): accept-encoding: [gzip]
E/BooksSync( 6539): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 6539): gdata-version: 2
E/BooksSync( 6539): 
E/BooksSync( 6539): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 6539): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 6539): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 6539): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 6539): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 6539): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 6539): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 6539): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 6539): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 6539): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 6539): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 6539): {
E/BooksSync( 6539):  "error": {
E/BooksSync( 6539):   "errors": [
E/BooksSync( 6539):    {
E/BooksSync( 6539):     "domain": "global",
E/BooksSync( 6539):     "reason": "required",
E/BooksSync( 6539):     "message": "Login Required",
E/BooksSync( 6539):     "locationType": "header",
E/BooksSync( 6539):     "location": "Authorization"
E/BooksSync( 6539):    }
E/BooksSync( 6539):   ],
E/BooksSync( 6539):   "code": 401,
E/BooksSync( 6539):   "message": "Login Required"
E/BooksSync( 6539):  }
E/BooksSync( 6539): }
E/BooksSync( 6539): 
E/BooksSync( 6539): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 6539): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 6539): 	... 8 more
E/BooksSync( 6539): Sync error
E/BooksSync( 6539): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 6539): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=7574217007443831795&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 6539): Headers:
E/BooksSync( 6539): accept-encoding: [gzip]
E/BooksSync( 6539): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 6539): gdata-version: 2
E/BooksSync( 6539): 
E/BooksSync( 6539): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 6539): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 6539): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 6539): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 6539): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 6539): 	at com.google.android.apps.books.data.NetworkTaskQ,ueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 6539): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 6539): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 6539): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 6539): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 6539): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 6539): {
E/BooksSync( 6539):  "error": {
E/BooksSync( 6539):   "errors": [
E/BooksSync( 6539):    {
E/BooksSync( 6539):     "domain": "global",
E/BooksSync( 6539):     "reason": "required",
E/BooksSync( 6539):     "message": "Login Required",
E/BooksSync( 6539):     "locationType": "header",
E/BooksSync( 6539):     "location": "Authorization"
E/BooksSync( 6539):    }
E/BooksSync( 6539):   ],
E/BooksSync( 6539):   "code": 401,
E/BooksSync( 6539):   "message": "Login Required"
E/BooksSync( 6539):  }
E/BooksSync( 6539): }
E/BooksSync( 6539): 
E/BooksSync( 6539): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 6539): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 6539): 	... 8 more
I/BooksSync( 6539): Finished books sync
,I/ActivityManager( 1031): Killing 5802:com.uei.lg.quicksetsdk.maxq616/1000 (adj 15): empty #17
,D/SyncManager( 1031): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 26659, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
I/QRemote ( 5941): [RemoteControlManager.java:195:onServiceDisconnected()] oooooo start
W/System.err( 5941): android.os.DeadObjectException
W/System.err( 5941): 	at android.os.BinderProxy.transactNative(Native Method)
W/System.err( 5941): 	at android.os.BinderProxy.transact(Binder.java:496)
W/System.err( 5941): 	at com.uei.control.IControl.unregisterCallback(IControl.java:502)
W/System.err( 5941): 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:199)
,W/System.err( 5941): 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
W/System.err( 5941): 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
W/System.err( 5941): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 5941): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 5941): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 5941): 	at android.app.ActivityThread.main(ActivityThread.java:5274)
W/System.err( 5941): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 5941): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 5941): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
W/System.err( 5941): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
E/UEI.SmartControl( 5941): IControl.unregisterCallback error: android.os.DeadObjectException
W/System.err( 5941): android.os.DeadObjectException
W/System.err( 5941): 	at android.os.BinderProxy.transactNative(Native Method)
W/System.err( 5941): 	at android.os.BinderProxy.transact(Binder.java:496)
W/System.err( 5941): 	at com.uei.control.IControl.unregisterSetupReadyCallback(IControl.java:818)
W/System.err( 5941): 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:200)
W/System.err( 5941): 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
W/System.err( 5941): 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
W/System.err( 5941): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 5941): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 5941): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 5941): 	at android.app.ActivityThread.main(ActivityThread.java:5274)
W/System.err( 5941): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 5941): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 5941): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
W/System.err( 5941): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
E/UEI.SmartControl( 5941): IControl.unregisterSetupReadyCallback error: android.os.DeadObjectException
I/QRemote ( 5941): [RemoteControlManager.java:203:onServiceDisconnected()] oooooo Control unbind before rebinding.
,I/ActivityManager( 1031): Killing 6299:com.lge.sync/1000 (adj 15): empty #18
,W/libprocessgroup( 1031): failed to open /acct/uid_1000/pid_5802/cgroup.procs: No such file or directory
W/ActivityManager( 1031): Scheduling restart of crashed service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service in 1000ms
,W/libprocessgroup( 1031): failed to open /acct/uid_1000/pid_6299/cgroup.procs: No such file or directory
D/QRemote ( 5941): [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]10
I/QRemote ( 5941): [RemoteControlManager.java:157:onBindIRService()] oooooo bind
,I/ThermalEngine(  350): Thermal-Server: Thermal received msg from  override
I/Thermal-Lib( 3122): Thermal-Lib-Client: Client request sent
I/ActivityManager( 1031): Start proc com.uei.lg.quicksetsdk.maxq616 for service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service: pid=6932 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,D/QRemote ( 5941): [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
,I/GAV2    ( 6539): Thread[GAThread,5,main]: No campaign data found.
,D/UEI.SmartControl( 6932): Quickset Services start...
I/UEI.SmartControl( 6932): Manufacture = LGE
D/UEI.SmartControl( 6932): Id = LGNevo
D/UEI.SmartControl( 6932): File observer start...
E/UEI.SmartControl( 6932): IR Port is disabled: false
D/UEI.SmartControl( 6932): Starting file observer...
D/UEI.SmartControl( 6932): Extracting JNI libs...
D/UEI.SmartControl( 6932): --- this system supports 32-bit or 64-bit only
V/GLSActivity( 2057): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2057): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.syncadapters.contacts, service: cp
I/GLSUser ( 2057): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> cp without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2057): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2057): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2057): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1031): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
V/NotificationService( 1031): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1031): LED remove() : mLights=0|com.google.android.gms|1|null|10005
,D/NotificationServiceEx( 1031): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1031): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
W/GLSActivity( 2057): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2057): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2057): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2057): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2057): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2057): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2057): 	at android.os.Binder.execTransact(Binder.java:446)
D/LgeQuickCoverNLService( 1412): onNotificationPosted
D/ContactsSyncAdapter( 2057): innerSync failed
D/ContactsSyncAdapter( 2057): com.google.wireless.gdata2.client.AuthenticationException: unable to get auth token android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
D/ContactsSyncAdapter( 2057): 	at com.google.android.syncadapters.contacts.AuthInfo.getAuthToken(AuthInfo.java:45)
D/ContactsSyncAdapter( 2057): 	at com.google.android.syncadapters.contacts.ContactsSyncAdapter.innerPerformSync(ContactsSyncAdapter.java:263)
D/ContactsSyncAdapter( 2057): 	at com.google.android.syncadapters.contacts.ContactsSyncAdapter.onPerformLoggedSync(ContactsSyncAdapter.java:168)
D/ContactsSyncAdapter( 2057): 	at com.google.android.common.LoggingThreadedSyncAdapter.onPerformSync(LoggingThreadedSyncAdapter.java:33)
D/ContactsSyncAdapter( 2057): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
D/ContactsSyncAdapter( 2057): Caused by: android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
D/ContactsSyncAdapter( 2057): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
D/ContactsSyncAdapter( 2057): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
D/ContactsSyncAdapter( 2057): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
D/ContactsSyncAdapter( 2057): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
D/ContactsSyncAdapter( 2057): 	at android.os.Binder.execTransact(Binder.java:446)
D/UEI.SmartControl( 6932): --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
D/UEI.SmartControl( 6932): --- Checking lib: libqs_armeabi-v7a.zip
D/UEI.SmartControl( 6932): --- Extracting JNI libs: libqs_armeabi-v7a.zip
,D/SmartCoverUpdateMonitor( 1412): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1412): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1412): handleNotificationPosted(true)
D/QuickCircle( 1412): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1412): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1412): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1412): post do just update job
D/LgeQuickCoverNotificationData( 1412): showAll3
D/LgeQuickCoverNotificationData( 1412): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1412): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1412): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1412): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1412): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1412): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1412): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1412): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1412): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1412): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1412): updateNotificationData: count=3
I/UEI.SmartControl( 6932): --- Selecting new region: 6
,I/UEI.SmartControl( 6932): Model = LG-D855
D/sensors_hal_Time( 1031): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1031): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1031): tsOffsetIs: Apps: 240321916892; DSPS: 8015537; Offset : -4305778885
D/QuickStatusbarLayout( 1412): Notification difference=198
D/QuickStatusbarLayout( 1412): child = android.widget.LinearLayout{20ebe075 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
D/UEI.SmartControl( 6932): QS Service created
D/SyncManager( 1031): failed sync operation thalitester@gmail.com u0 (com.google), com.android.contacts, LOCAL, currentRunTime 268254, reason: 10019, SyncResult: stats [ numAuthExceptions: 1]
I/UEI.SmartControl( 6932): Service initServices...
,D/UEI.SmartControl( 6932): QS start get config
,D/UEI.SmartControl( 6932): Loading JNI Libs...
,I/UEI.SmartControl( 6932): Supports setup maps: true
,D/UEI.SmartControl( 6932): QS start statue = true Error code = 0
,I/UEI.SmartControl( 6932): QS version = v2.7.10.1_RC1
,I/UEI.SmartControl( 6932): QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
I/UEI.SmartControl( 6932): ### init IR Blaster...
D/serial_port( 6932): Configuring serial port
E/UEI.SmartControl( 6932): UEIBLaster setting for 616
I/UEI.SmartControl( 6932): Setting serial record hearder size = 2
I/UEI.SmartControl( 6932): configuring settings for MAXQ616
I/UEI.SmartControl( 6932): Get version...
,D/UEI.SmartControl( 6932): serial port data available: 21
,D/UEI.SmartControl( 6932): MAXQ616 A2-X4 software.
I/UEI.SmartControl( 6932): IR Blaster version: 256702256704300002
,I/UEI.SmartControl( 6932): QS saving settings...
D/UEI.SmartControl( 6932): IR Blaster version: 25672567
D/UEI.SmartControl( 6932): serial port data available: 4
,W/ContextImpl( 6932): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
,I/UEI.SmartControl( 6932): Device manager: loading config....
D/UEI.SmartControl( 6932): ----------- loading internal config...
E/UEI.SmartControl( 6932): Services init done
D/UEI.SmartControl( 6932): QS Service init finished
D/UEI.SmartControl( 6932): QS Service version name: 2.1.91
D/UEI.SmartControl( 6932): QS Service version code: 201091
,D/UEI.SmartControl( 6932): Service requested: Control
E/UEI.SmartControl( 6932): Loading SETTINGS...
D/UEI.SmartControl( 6932): Request IControl service: devices are loaded...
,I/ActivityManager( 1031): Killing 6214:com.android.settings/1000 (adj 15): empty #17
I/QRemote ( 5941): [RemoteControlManager.java:183:onServiceConnected()] oooooo start
I/UEI.SmartControl( 6932): ------ IControl API: 11
I/UEI.SmartControl( 6932): Registering callback...
I/UEI.SmartControl( 6932): ------ IControl API: 19
I/UEI.SmartControl( 6932): Registering Services Ready callback...
,D/UEI.SmartControl( 6932): -- Open brand translation xml: brands_translations_ko
I/UEI.SmartControl( 6932): Notify AllClients services are ready: 0
,I/QRemote ( 5941): [RemoteControlManager.java:660:QSSetupIsReady()] oooooo 140517:sdkIsReady callback... get functions. Result:0
D/QRemote ( 5941): [RemoteControlManager.java:388:handleMessage()] oooooo 140510:START_SESSION
D/QRemote ( 5941): [RemoteControlManager.java:394:handleMessage()] oooooo 140510:send retrieve msg
D/QRemote ( 5941): [RemoteControlManager.java:322:handleMessage()] oooooo 140510:handler call retrieveDevices
D/QRemote ( 5941): [RemoteControlManager.java:336:retrieveDevices()] oooooo retrieveDevices: start
I/UEI.SmartControl( 6932): ------ IControl API: 8
D/UEI.SmartControl( 6932): -----service ready thread exits
D/QRemote ( 5941): [RemoteControlManager.java:340:retrieveDevices()] oooooo retrieveDevices: 0
D/QRemote ( 5941): [RemoteControlManager.java:345:retrieveDevices()] oooooo retrieveDevices complete:true
D/QRemote ( 5941): [RemoteControlManager.java:353:retrieveDevices()] oooooo retrieveDevices: notifyDataSetChanged()
D/QRemote ( 5941): [QRemoteApplication.java:145:onRemoteControlStateChanged()] oooooo onRemoteControlStateChanged called in QRemoteApp
D/QRemote ( 5941): [QRemoteApplication.java:158:onRemoteControlStateChanged()] oooooo Widget count is [1]. send broadcast
D/QRemote ( 5941): [QRemoteApplication.java:160:onRemoteControlStateChanged()] oooooo Widget[0]:3
D/WifiService( 1031): Client connection lost with reason: 4
,W/libprocessgroup( 1031): failed to open /acct/uid_1000/pid_6214/cgroup.procs: No such file or directory
,D/QRemote ( 5941): [QRemoteApplication.java:188:onRemoteControlStateChanged()] oooooo 140526:onRemoteControlStateChanged&sdkIsReady. stop Service
,D/UEI.SmartControl( 6932): Internal service binding...
,V/QRemote ( 5941): [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
D/QRemote ( 5941): [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
E/QRemote ( 5941): [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
D/QRemote ( 5941): [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
D/QRemote ( 5941): [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
D/QRemote ( 5941): [RemoteAppWidgetProvider.java:506:onUpdate()] oooooo 140510:RetrieveDevices complete. Start loading
D/QRemote ( 5941): [RemoteAppWidgetProvider.java:508:onUpdate()] oooooo 140510:appWidgetIds[0]:3 loading
D/QRemote ( 5941): [RemoteAppWidgetManager.java:41:startLoading()] oooooo 140518:widgetId[3] loading start at [1454092154665]
D/QRemote ( 5941): [RemoteAppWidgetManager.java:239:doInBackground()] oooooo 140407:doinBack arr:0
,V/QRemote ( 5941): [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.widget_ui_update
E/QRemote ( 5941): [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
D/QRemote ( 5941): [RemoteAppWidgetProvider.java:171:onReceive()] oooooo total:0
D/QRemote ( 5941): [RemoteAppWidgetProvider.java:172:onReceive()] oooooo selected:0
D/QRemote ( 5941): [RemoteAppWidgetProvider.java:173:onReceive()] oooooo arr:[]
D/QRemote ( 5941): [RemoteAppWidgetProvider.java:174:onReceive()] oooooo appWidgetId:3
D/QRemote ( 5941): [RemoteAppWidgetProvider.java:815:updateRemoteViews()] oooooo UpdateRemoteViews3:widgetId:3
D/QRemote ( 5941): [RemoteAppWidgetProvider.java:986:updateRemoteViews()] oooooo updateAppWidget5:widgetId:3]
,I/ActivityManager( 1031): Killing 6521:com.lge.appbox.client/u0a11 (adj 15): empty #17
,W/libprocessgroup( 1031): failed to open /acct/uid_10011/pid_6521/cgroup.procs: No such file or directory
,I/GAV4    ( 6730): Thread[GAThread,5,main]: No campaign data found.
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=23.4, 0.0, 0.0  rx=22.1 bcn=0 [on:0 tx:0 rx:0 period:3005] from screen [on:0 period:-1901757698] gl rssi=-57 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=23.4, 0.0, 0.0  rx=22.1 bcn=0 [on:0 tx:0 rx:0 period:13] from screen [on:0 period:-1901757685] gl rssi=-57 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,I/ActivityManager( 1031): Killing 6270:com.lge.formmanager/u0a26 (adj 15): empty #17
W/libprocessgroup( 1031): failed to open /acct/uid_10026/pid_6270/cgroup.procs: No such file or directory
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=15.2, 0.0, 0.0  rx=14.1 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1901754669] gl rssi=-57 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=15.2, 0.0, 0.0  rx=14.1 bcn=0 [on:0 tx:0 rx:0 period:11] from screen [on:0 period:-1901754658] gl rssi=-57 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
D/UEI.SmartControl( 6932): Internal timer expired: 1
D/UEI.SmartControl( 6932): unbind internal service
,D/serial_port( 6932): close(fd = 25)
,I/UEI.SmartControl( 6932): Serial port is closed.
I/ActivityManager( 1031): Start proc com.android.vending for service com.android.vending/com.google.android.finsky.services.ContentSyncService: pid=6981 uid=10044 gids={50044, 9997, 3003, 1028, 1015} abi=armeabi-v7a
V/AlarmManager( 1031): RTC_WAKEUP set : Alarm{81c2468 type 0 when 1454092160843 com.android.vending} when 1454092160843
,D/Finsky  ( 6981): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,D/LgDataFeature( 6981): LgDataFeature() Constructor: none
D/LgDataFeature( 6981): LgDataFeature() Constructor Done, null
,D/Finsky  ( 6981): [1] DailyHygiene.goMakeHygieneIfDirty: Dirty, need more hygiene.
,I/ActivityManager( 1031): Start proc com.google.android.gms:car for service com.google.android.gms/.car.CarService: pid=7022 uid=10005 gids={50005, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
,W/Settings( 6981): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
W/Settings( 6981): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/ResourcesManager( 7022): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 7022): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
V/DownloadManager( 3304): starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; selection is null; selectionArgs is null; sort is null.
,I/MultiDex( 7022): VM with version 2.1.0 has multidex support
I/MultiDex( 7022): install
I/MultiDex( 7022): VM has multidex support, MultiDex support library is disabled.
,V/JNIHelp ( 7022): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
W/ActivityThread( 7022): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 7022): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@c27a9fe: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,I/ProviderInstaller( 7022): Installed default security provider GmsCore_OpenSSL
D/GCM     ( 2057): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
D/AuthorizationBluetoothService( 2057): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,V/GmsCoreStatsServiceLauncher( 2332): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,I/art     ( 1031): Explicit concurrent mark sweep GC freed 28309(1389KB) AllocSpace objects, 7(624KB) LOS objects, 33% free, 44MB/66MB, paused 1.834ms total 110.957ms
,V/DownloadManager( 3304): created cursor android.database.sqlite.SQLiteCursor@3afeec05 on behalf of 6981
I/ActivityManager( 1031): Start proc com.google.android.gms.wearable for service com.google.android.gms/.wearable.service.WearableService: pid=7057 uid=10005 gids={50005, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
,D/LocationInitializer( 2332): Restart initialization of location
,D/Finsky  ( 6981): [1] 2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 6981): [1] 2.run: Finished loading 1 libraries.
D/Finsky  ( 6981): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,W/ResourcesManager( 7057): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 7057): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/art     ( 2057): Explicit concurrent mark sweep GC freed 28393(1681KB) AllocSpace objects, 20(2MB) LOS objects, 51% free, 30MB/62MB, paused 913us total 50.365ms
,D/Finsky  ( 6981): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
I/MultiDex( 7057): VM with version 2.1.0 has multidex support
I/MultiDex( 7057): install
I/MultiDex( 7057): VM has multidex support, MultiDex support library is disabled.
,V/JNIHelp ( 7057): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,V/SIM_STK ( 1031): Menu title from STK is T-Mobile
W/ActivityThread( 7057): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 7057): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@c27a9fe: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 7057): Installed default security provider GmsCore_OpenSSL
V/Finsky  ( 6981): [1] GearheadStateMonitor.onReady: sIsProjecting:false
D/WearableService( 7057): callingUid 10005, callindPid: 7057
,E/MDM     ( 1803): [86] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,D/GCM     ( 2057): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,D/AuthorizationBluetoothService( 2057): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=8.6, 0.0, 0.0  rx=7.5 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:-1901751636] gl rssi=-57 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=8.6, 0.0, 0.0  rx=7.5 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-1901751635] gl rssi=-57 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
V/GmsCoreStatsServiceLauncher( 2332): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
E/MDM     ( 1803): [87] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,D/LocationInitializer( 2332): Restart initialization of location
,V/GLSActivity( 2057): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2057): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 2057): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 2057): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2057): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2057): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/Finsky  ( 6981): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 6981): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 6981): [1] 5.onFinished: Giving up after 6 failures.
I/ActivityManager( 1031): Killing 6667:com.lge.drmservice/u0a62 (adj 15): empty #17
,W/libprocessgroup( 1031): failed to open /acct/uid_10062/pid_6667/cgroup.procs: No such file or directory
,V/AlarmManager( 1031): RTC_WAKEUP set : Alarm{1abe943f type 0 when 1454092162230 com.android.vending} when 1454092162230
,D/Finsky  ( 6981): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
V/GLSActivity( 2057): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2057): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 2057): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2057): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2057): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2057): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/Finsky  ( 6981): [1] 1.onErrorResponse: Unable to preload experiments: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,V/GLSActivity( 2057): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/GLSUser ( 2057): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 2057): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2057): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2057): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2057): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 2057): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2057): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 2057): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2057): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2057): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2057): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/Finsky  ( 6981): [1] LibraryUpdateListener.onErrorResponse: Library replication failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,V/SIM_STK ( 1031): Menu title from STK is T-Mobile
,V/GLSActivity( 2057): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2057): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 2057): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 2057): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2057): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2057): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/Finsky  ( 6981): [1] 2.onErrorResponse: Update check failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,D/Finsky  ( 6981): [1] DailyHygiene.logDeviceFeaturesAndContinue: Logging device features
D/Finsky  ( 6981): [1] DailyHygiene.flushEventLogsAndContinue: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 6981): [1] DailyHygiene.reschedule: Scheduling new run in 88 minutes (failures=3)
D/DeviceConnectionService( 1803): client connected with version: 7571000
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=4.3, 0.0, 0.0  rx=3.8 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:-1901748620] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=4.3, 0.0, 0.0  rx=3.8 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1901748617] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
I/ActivityManager( 1031): Killing 6730:com.google.android.apps.magazines/u0a93 (adj 15): empty #17
,W/libprocessgroup( 1031): failed to open /acct/uid_10093/pid_6730/cgroup.procs: No such file or directory
,I/ActivityManager( 1031): Killing 6556:com.android.gallery3d/u0a27 (adj 15): empty #17
,W/libprocessgroup( 1031): failed to open /acct/uid_10027/pid_6556/cgroup.procs: No such file or directory
,I/[SystemUI]QPairHandler( 1468): onReceive = android.intent.action.PACKAGE_CHANGED
,D/SplitUIService( 1855): replaced split : contains_com.google.android.talk / true
,I/InputReader( 1031): Reconfiguring input devices.  changes=0x00000010
,I/ActivityManager( 1031): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.manager.PreloadListManagerHelper: pid=7120 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,I/[SystemUI]QSlideListController( 1468): onReceive = android.intent.action.PACKAGE_CHANGED
I/[SystemUI]AppWidgetPanel(QRemoteWidgetPanel)( 1468): onReceive = android.intent.action.PACKAGE_CHANGED, packageName : com.google.android.talk
D/SplitUIManager( 1855): split_name #11 / not available #0
I/SplitUIService( 1855): split app #11
,I/[LGHome]EVENT( 2020): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.talk flg=0x4000010 (has extras) }
,D/administrator( 1031): Handling package changes for user 0
W/ResourcesManager( 2020): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/[LGHome]Launcher( 2020): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume,
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=2.2, 0.0, 0.0  rx=1.9 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1901745589] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=2.2, 0.0, 0.0  rx=1.9 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-1901745588] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,I/AppUp4:AppBoxCP( 7120): onCreate
,W/AppUp4:DB( 7120):  [AppBoxDatabaseHelper] construct
I/AppUp4:DB( 7120):  setFingerPrint start
I/AppUp4:DB( 7120):  newfinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys SDK version = 21
I/AppUp4:DB( 7120):  beforefinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys
I/AppUp4:DB( 7120):  SDK version = 21
I/AppUp4:DB( 7120):  beforefinger == newfinger no write in DB
D/AppUp4:AppBoxApplication( 7120): AppBoxApplication onCreate()
I/AppUp4:CustModeStarterReceiver( 7120): onReceive
,D/LgDataFeature( 7120): LgDataFeature() Constructor: none
D/LgDataFeature( 7120): LgDataFeature() Constructor Done, null
,D/AppUp4:CustFacade( 7120): Context : android.app.ReceiverRestrictedContext@34ce4816
D/AppUp4:CustFacade( 7120): isCustomizationCompleted : false
D/AppUp4:CustFacade( 7120): isPhone : true
D/AppUp4:CustModeStarterReceiver( 7120): begin check event
I/AppUp4:CustModeStarterReceiver( 7120): Event For Nothing, skip.
I/NotificationService( 1031): action=android.intent.action.PACKAGE_CHANGED queryReplace=false
D/BackupManagerService( 1031): Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.talk flg=0x4000010 (has extras) }
,W/ResourcesManager( 1031): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
I/ActivityManager( 1031): Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=7156 uid=10019 gids={50019, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
,I/ActivityManager( 1031): Killing 6605:com.android.chrome/u0a57 (adj 15): empty #17
W/ResourcesManager( 1031): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourceType( 1031): Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
W/libprocessgroup( 1031): failed to open /acct/uid_10057/pid_6605/cgroup.procs: No such file or directory
,I/[LGHome]EVENT( 2020): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
,W/ResourcesManager( 7156): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 7156): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,W/ResourcesManager( 7156): Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
W/ResourcesManager( 7156): Asset path '/system/framework/lghiddenlibs.jar' does not exist or contains no resources.
W/ResourcesManager( 7156): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
I/SystemConfig( 7156): BUILD Country: EU
I/SystemConfig( 7156): BUILD Operator: OPEN
,I/ActivityManager( 1031): Killing 6709:com.google.android.apps.plus/u0a97 (adj 15): empty #17
,W/libprocessgroup( 1031): failed to open /acct/uid_10097/pid_6709/cgroup.procs: No such file or directory
,I/ActivityManager( 1031): Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=7185 uid=10027 gids={50027, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
,I/SystemConfig( 7156): pm.hasSystemFeature(com.lge.ims.rcs) = false
,I/SystemConfig( 7156): existFile = false
I/SystemConfig( 7156): canReadFile = false
I/SystemConfig( 7156): systemFeature RCS result false
D/SystemConfig( 7156): refreshRcsSupport() :false
,W/ResourcesManager( 7185): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 7185): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 7185): Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
W/ResourcesManager( 7185): Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
I/AppConfig( 7185): Total System Memory = 2995761152
,D/SystemHelper( 7185): region [EU], country [EU], operator [OPEN], sub-operator []
I/ActivityManager( 1031): Killing 6585:com.lge.email/u0a23 (adj 15): empty #17
,W/libprocessgroup( 1031): failed to open /acct/uid_10023/pid_6585/cgroup.procs: No such file or directory
,I/UpdateIcingCorporaServi( 4227): Updating corpora: APPS=com.google.android.talk, CONTACTS=MAYBE
,I/ActivityManager( 1031): Start proc com.lge.lockscreensettings for broadcast com.lge.lockscreensettings/.PackageIntentReceiver: pid=7211 uid=10080 gids={50080, 9997, 1028, 1015} abi=armeabi-v7a
,V/SIM_STK ( 1031): Menu title from STK is T-Mobile
,W/ResourcesManager( 4227): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/UpdateIcingCorporaServi( 4227): UpdateCorporaTask done [took 109 ms] updated apps [took 109 ms] 
I/LockScreenSettings( 7211): Wallpaper base directory = /data/data/com.lge.lockscreensettings/files/
,D/LockScreenSettings( 7211): Quick window widget present in DB = com.lge.clock.quickcover.QuickCoverSettingActivity  true
,D/LockScreenSettings( 7211): Quick window widget present in DB = com.lge.camera.app.QuickWindowCameraActivity  true
D/LockScreenSettings( 7211): Quick window widget present in DB = com.android.contacts.activities.QuickCircleActivity  true
D/LockScreenSettings( 7211): Quick window widget present in DB = com.android.mms.quickcover.QuickCoverActivity  true
D/LockScreenSettings( 7211): Quick window widget present in DB = com.lge.music.MusicQuickCircle  true
D/LockScreenSettings( 7211): Quick window widget present in DB = com.lge.lifetracker.QuickCover  true
,I/ActivityManager( 1031): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=7234 uid=10097 gids={50097, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager( 1031): Killing 6386:com.wsandroid.suite.lge/1000 (adj 15): empty #17
W/libprocessgroup( 1031): failed to open /acct/uid_1000/pid_6386/cgroup.procs: No such file or directory
,W/ResourcesManager( 7234): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,D/PackageBroadcastService( 2332): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.talk
,I/PeopleContactsSync( 2332): CP2 sync disabled
,I/GLSActivity( 2057): [ac] getting account id
,I/GLSUser ( 2057): [t] Fetched account id for thalitester@gmail.com : 105256135866144380227
,I/art     ( 1031): Explicit concurrent mark sweep GC freed 23920(1090KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 44MB/66MB, paused 2.798ms total 122.547ms
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=1.1, 0.0, 0.0  rx=0.9 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:-1901742573] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=1.1, 0.0, 0.0  rx=0.9 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1901742570] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.5 bcn=0 [on:0 tx:0 rx:0 period:2999] from screen [on:0 period:-1901739548] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.5 bcn=0 [on:0 tx:0 rx:0 period:5] from screen [on:0 period:-1901739543] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
D/sensors_hal_Time( 1031): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1031): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1031): tsOffsetIs: Apps: 260323291260; DSPS: 8670942; Offset : -4305777782
,I/ActivityManager( 1031): Killing 6832:com.qualcomm.timeservice/1000 (adj 15): empty #17
,W/libprocessgroup( 1031): failed to open /acct/uid_1000/pid_6832/cgroup.procs: No such file or directory
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=0.3, 0.0, 0.0  rx=0.2 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:-1901736527] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=0.3, 0.0, 0.0  rx=0.2 bcn=0 [on:0 tx:0 rx:0 period:4] from screen [on:0 period:-1901736523] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,V/AlarmManager( 1031): RTC_WAKEUP set : Alarm{38214251 type 0 when 1454092177490 com.android.vending} when 1454092177490
,V/SIM_STK ( 1031): Menu title from STK is T-Mobile
,V/GLSActivity( 2057): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2057): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 2057): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2057): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 2057): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2057): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/Finsky  ( 6981): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 6981): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 6981): [1] 5.onFinished: Scheduling replication attempt 1.
,V/AlarmManager( 1031): ELAPSED_WAKEUP set : Alarm{3cbcacb type 2 when 265140 android} when 265140
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1901733498] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:5] from screen [on:0 period:-1901733493] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=1.1, 0.0, 0.0  rx=1.1 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1901730465] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=1.1, 0.0, 0.0  rx=1.1 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1901730462] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 1 0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 1 0
E/WifiStateMachine( 1031):  ConnectModeState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 1 0
E/WifiStateMachine( 1031):  DriverStartedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 1 0
,E/WifiStateMachine( 1031):  SupplicantStartedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 1 0
E/WifiStateMachine( 1031):  DefaultState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 1 0
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.5 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1901727438] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.5 bcn=0 [on:0 tx:0 rx:0 period:15] from screen [on:0 period:-1901727423] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=0.3, 0.0, 0.0  rx=0.3 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1901724403] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=0.3, 0.0, 0.0  rx=0.3 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1901724400] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:-1901721374] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1901721371] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,D/sensors_hal_Time( 1031): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1031): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1031): tsOffsetIs: Apps: 280324758023; DSPS: 9326351; Offset : -4305806432
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:2996] from screen [on:0 period:-1901718329] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:11] from screen [on:0 period:-1901718318] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:-1901715296] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1901715293] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,V/AlarmManager( 1031): RTC_WAKEUP set : Alarm{24e661c1 type 0 when 1454092198550 com.android.vending} when 1454092198550
,V/SIM_STK ( 1031): Menu title from STK is T-Mobile
,I/[SystemUI]TimeTickManager( 1468): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1468): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1468): called onTimeUpdated()
I/[SystemUI]Clock( 1468): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1468): called onTimeUpdated()
I/[SystemUI]DateView( 1468): called onTimeUpdated()
I/[SystemUI]DateView( 1468): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1468): handleTimeUpdate
V/GLSActivity( 2057): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/[SystemUI]TimeTickManager( 1468): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1468): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1468): called onTimeUpdated()
I/[SystemUI]Clock( 1468): called onTimeUpdated()
I/LgeClockWidgetControlView( 1468): called onTimeUpdated()
I/[SystemUI]DateView( 1468): called onTimeUpdated()
I/[SystemUI]DateView( 1468): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1468): handleTimeUpdate
I/GLSUser ( 2057): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 2057): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2057): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2057): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2057): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 6981): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 6981): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 6981): [1] 5.onFinished: Scheduling replication attempt 2.
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1901712264] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1901712261] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,D/PowerManagerServiceEx( 1031): acquireWakeLockInternal: lock=398724214, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1031
,D/[Concierge]Service( 2617): onStartCommand(). Type : 9
,I/DigitalAppWidgetProvider( 6808): onReceive: com.android.deskclock.ON_QUARTER_HOUR
,V/DigitalAppWidgetProvider( 6808): startAlarmOnQuarterHour android.app.ReceiverRestrictedContext@125ecfa2
D/PowerManagerServiceEx( 1031): releaseWakeLockInternal: lock=398724214 [*alarm*], flags=0x0
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1901709230] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:2] from screen [on:0 period:-1901709228] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=1.0, 0.0, 0.0  rx=0.5 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1901706199] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=1.0, 0.0, 0.0  rx=0.5 bcn=0 [on:0 tx:0 rx:0 period:12] from screen [on:0 period:-1901706187] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
V/AlarmManager( 1031): ELAPSED_WAKEUP set : Alarm{11c8fcbb type 2 when 295162 android} when 295162
,I/BooksSync( 6539): Starting books sync
,D/BooksSync( 6539): started syncMyEbooks
,V/GLSActivity( 2057): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2057): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2057): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2057): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2057): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2057): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1031): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1031): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1031): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1031): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1031): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1412): onNotificationPosted
W/GLSActivity( 2057): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2057): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2057): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2057): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2057): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2057): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2057): 	at android.os.Binder.execTransact(Binder.java:446)
,D/SmartCoverUpdateMonitor( 1412): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1412): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1412): handleNotificationPosted(true)
D/QuickCircle( 1412): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1412): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1412): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1412): post do just update job
D/LgeQuickCoverNotificationData( 1412): showAll3
D/LgeQuickCoverNotificationData( 1412): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1412): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1412): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1412): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1412): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1412): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1412): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1412): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1412): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1412): isNotificationForCurrentUser : true
E/BooksAccountManager( 6539): Authentication error
E/BooksAccountManager( 6539): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6539): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6539): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6539): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6539): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6539): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6539): null auth token
E/LgeQuickCoverOverlayWindow( 1412): updateNotificationData: count=3
D/QuickStatusbarLayout( 1412): Notification difference=198
D/QuickStatusbarLayout( 1412): child = android.widget.LinearLayout{20ebe075 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,I/GLSUser ( 2057): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.syncadapters.contacts, service: cp
I/GLSUser ( 2057): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> cp without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2057): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2057): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2057): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1031): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1031): pkg=com.google.android.gms canInterrupt=false intercept=true
,I/NotificationServiceEx( 1031): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1031): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1031): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
W/GLSActivity( 2057): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2057): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2057): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2057): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2057): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2057): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2057): 	at android.os.Binder.execTransact(Binder.java:446)
D/LgeQuickCoverNLService( 1412): onNotificationPosted
D/SmartCoverUpdateMonitor( 1412): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1412): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1412): handleNotificationPosted(true)
D/QuickCircle( 1412): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1412): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1412): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1412): post do just update job
D/LgeQuickCoverNotificationData( 1412): showAll3
D/LgeQuickCoverNotificationData( 1412): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1412): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1412): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1412): showNotificationWithSetupData: display=false
D/ContactsSyncAdapter( 2057): innerSync failed
D/ContactsSyncAdapter( 2057): com.google.wireless.gdata2.client.AuthenticationException: unable to get auth token android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
D/ContactsSyncAdapter( 2057): 	at com.google.android.syncadapters.contacts.AuthInfo.getAuthToken(AuthInfo.java:45)
D/ContactsSyncAdapter( 2057): 	at com.google.android.syncadapters.contacts.ContactsSyncAdapter.innerPerformSync(ContactsSyncAdapter.java:263)
D/ContactsSyncAdapter( 2057): 	at com.google.android.syncadapters.contacts.ContactsSyncAdapter.onPerformLoggedSync(ContactsSyncAdapter.java:168)
D/ContactsSyncAdapter( 2057): 	at com.google.android.common.LoggingThreadedSyncAdapter.onPerformSync(LoggingThreadedSyncAdapter.java:33)
D/ContactsSyncAdapter( 2057): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
D/ContactsSyncAdapter( 2057): Caused by: android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
D/ContactsSyncAdapter( 2057): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
D/ContactsSyncAdapter( 2057): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
D/ContactsSyncAdapter( 2057): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
D/ContactsSyncAdapter( 2057): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
D/ContactsSyncAdapter( 2057): 	at android.os.Binder.execTransact(Binder.java:446)
D/LgeQuickCoverOverlayWindow( 1412): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1412): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1412): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1412): isNotificationForCurrentUser : true
,D/LgeQuickCoverOverlayWindow( 1412): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1412): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1412): updateNotificationData: count=3
D/SyncManager( 1031): failed sync operation thalitester@gmail.com u0 (com.google), com.android.contacts, LOCAL, currentRunTime 268254, reason: 10019, SyncResult: stats [ numAuthExceptions: 1]
D/SyncManager( 1031): not retrying sync operation because the error is a hard error: thalitester@gmail.com u0 (com.google), com.android.contacts, LOCAL, currentRunTime 358778, reason: 10019
W/ApiaryClient( 6539): Error response from books API: {
W/ApiaryClient( 6539):  "error": {
W/ApiaryClient( 6539):   "errors": [
W/ApiaryClient( 6539):    {
W/ApiaryClient( 6539):     "domain": "global",
W/ApiaryClient( 6539):     "reason": "required",
W/ApiaryClient( 6539):     "message": "Login Required",
W/ApiaryClient( 6539):     "locationType": "header",
W/ApiaryClient( 6539):     "location": "Authorization"
W/ApiaryClient( 6539):    }
W/ApiaryClient( 6539):   ],
W/ApiaryClient( 6539):   "code": 401,
W/ApiaryClient( 6539):   "message": "Login Required"
W/ApiaryClient( 6539):  }
W/ApiaryClient( 6539): }
W/ApiaryClient( 6539): errCount = 1: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6539): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=8919119144795398527&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6539): Headers:
W/ApiaryClient( 6539): accept-encoding: [gzip]
W/ApiaryClient( 6539): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6539): gdata-version: 2
D/QuickStatusbarLayout( 1412): Notification difference=198
D/QuickStatusbarLayout( 1412): child = android.widget.LinearLayout{20ebe075 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.3 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1901703164] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.3 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1901703161] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,V/GLSActivity( 2057): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2057): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2057): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2057): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 2057): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2057): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1031): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1031): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1031): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1031): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1031): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1412): onNotificationPosted
,D/SmartCoverUpdateMonitor( 1412): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1412): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1412): handleNotificationPosted(true)
D/QuickCircle( 1412): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1412): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1412): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1412): post do just update job
D/LgeQuickCoverNotificationData( 1412): showAll3
D/LgeQuickCoverNotificationData( 1412): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1412): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1412): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1412): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1412): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1412): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1412): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1412): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1412): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1412): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1412): updateNotificationData: count=3
W/GLSActivity( 2057): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2057): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2057): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2057): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2057): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2057): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2057): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 6539): Authentication error
E/BooksAccountManager( 6539): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6539): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6539): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6539): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6539): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6539): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6539): null auth token
D/QuickStatusbarLayout( 1412): Notification difference=198
D/QuickStatusbarLayout( 1412): child = android.widget.LinearLayout{20ebe075 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,W/ApiaryClient( 6539): Error response from books API: {
W/ApiaryClient( 6539):  "error": {
W/ApiaryClient( 6539):   "errors": [
W/ApiaryClient( 6539):    {
W/ApiaryClient( 6539):     "domain": "global",
W/ApiaryClient( 6539):     "reason": "required",
W/ApiaryClient( 6539):     "message": "Login Required",
W/ApiaryClient( 6539):     "locationType": "header",
W/ApiaryClient( 6539):     "location": "Authorization"
W/ApiaryClient( 6539):    }
W/ApiaryClient( 6539):   ],
W/ApiaryClient( 6539):   "code": 401,
W/ApiaryClient( 6539):   "message": "Login Required"
W/ApiaryClient( 6539):  }
W/ApiaryClient( 6539): }
,W/ApiaryClient( 6539): errCount = 2: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6539): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=8919119144795398527&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6539): Headers:
W/ApiaryClient( 6539): accept-encoding: [gzip]
W/ApiaryClient( 6539): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6539): gdata-version: 2
V/GLSActivity( 2057): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2057): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 2057): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2057): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2057): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2057): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1031): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1031): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1031): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1031): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1031): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1412): onNotificationPosted
,D/SmartCoverUpdateMonitor( 1412): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1412): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1412): handleNotificationPosted(true)
D/QuickCircle( 1412): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1412): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1412): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1412): post do just update job
D/LgeQuickCoverNotificationData( 1412): showAll3
D/LgeQuickCoverNotificationData( 1412): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1412): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1412): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1412): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1412): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1412): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1412): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1412): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1412): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1412): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1412): updateNotificationData: count=3
W/GLSActivity( 2057): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2057): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2057): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2057): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2057): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2057): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2057): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 6539): Authentication error
E/BooksAccountManager( 6539): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6539): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6539): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6539): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6539): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6539): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6539): null auth token
D/QuickStatusbarLayout( 1412): Notification difference=198
D/QuickStatusbarLayout( 1412): child = android.widget.LinearLayout{20ebe075 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
W/ApiaryClient( 6539): Error response from books API: {
W/ApiaryClient( 6539):  "error": {
W/ApiaryClient( 6539):   "errors": [
W/ApiaryClient( 6539):    {
W/ApiaryClient( 6539):     "domain": "global",
W/ApiaryClient( 6539):     "reason": "required",
W/ApiaryClient( 6539):     "message": "Login Required",
W/ApiaryClient( 6539):     "locationType": "header",
W/ApiaryClient( 6539):     "location": "Authorization"
W/ApiaryClient( 6539):    }
W/ApiaryClient( 6539):   ],
W/ApiaryClient( 6539):   "code": 401,
W/ApiaryClient( 6539):   "message": "Login Required"
W/ApiaryClient( 6539):  }
W/ApiaryClient( 6539): }
,W/ApiaryClient( 6539): errCount = 3: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6539): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=8919119144795398527&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6539): Headers:
W/ApiaryClient( 6539): accept-encoding: [gzip]
W/ApiaryClient( 6539): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6539): gdata-version: 2
E/BooksSync( 6539): Soft error: 
E/BooksSync( 6539): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 6539): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=8919119144795398527&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 6539): Headers:
E/BooksSync( 6539): accept-encoding: [gzip]
E/BooksSync( 6539): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 6539): gdata-version: 2
E/BooksSync( 6539): 
E/BooksSync( 6539): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 6539): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 6539): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 6539): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 6539): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 6539): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 6539): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 6539): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 6539): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 6539): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 6539): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 6539): {
E/BooksSync( 6539):  "error": {
E/BooksSync( 6539):   "errors": [
E/BooksSync( 6539):    {
E/BooksSync( 6539):     "domain": "global",
E/BooksSync( 6539):     "reason": "required",
E/BooksSync( 6539):     "message": "Login Required",
E/BooksSync( 6539):     "locationType": "header",
E/BooksSync( 6539):     "location": "Authorization"
E/BooksSync( 6539):    }
E/BooksSync( 6539):   ],
E/BooksSync( 6539):   "code": 401,
E/BooksSync( 6539):   "message": "Login Required"
E/BooksSync( 6539):  }
E/BooksSync( 6539): }
E/BooksSync( 6539): 
E/BooksSync( 6539): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 6539): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 6539): 	... 8 more
,E/BooksSync( 6539): Sync error
E/BooksSync( 6539): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 6539): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=8919119144795398527&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 6539): Headers:
E/BooksSync( 6539): accept-encoding: [gzip]
E/BooksSync( 6539): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 6539): gdata-version: 2
E/BooksSync( 6539): 
E/BooksSync( 6539): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 6539): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 6539): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 6539): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 6539): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 6539): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 6539): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 6539): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 6539): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 6539): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 6539): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 6539): {
E/BooksSync( 6539):  "error": {
E/BooksSync( 6539):   "errors": [
E/BooksSync( 6539):    {
E/BooksSync( 6539):     "domain": "global",
E/BooksSync( 6539):     "reason": "required",
E/BooksSync( 6539):     "message": "Login Required",
E/BooksSync( 6539):     "locationType": "header",
E/BooksSync( 6539):     "location": "Authorization"
E/BooksSync( 6539):    }
E/BooksSync( 6539):   ],
E/BooksSync( 6539):   "code": 401,
E/BooksSync( 6539):   "message": "Login Required"
E/BooksSync( 6539):  }
E/BooksSync( 6539): }
E/BooksSync( 6539): 
E/BooksSync( 6539): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 6539): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 6539): 	... 8 more
I/BooksSync( 6539): Finished books sync
D/SyncManager( 1031): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 271571, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=1.8, 0.0, 0.0  rx=1.6 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1901700139] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=1.8, 0.0, 0.0  rx=1.6 bcn=0 [on:0 tx:0 rx:0 period:13] from screen [on:0 period:-1901700126] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
D/sensors_hal_Time( 1031): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1031): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1031): tsOffsetIs: Apps: 300326549057; DSPS: 9981769; Offset : -4305785626
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=4.4, 0.0, 0.0  rx=4.3 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1901697110] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=4.4, 0.0, 0.0  rx=4.3 bcn=0 [on:0 tx:0 rx:0 period:12] from screen [on:0 period:-1901697098] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=2.2, 0.0, 0.0  rx=2.2 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1901694083] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=2.2, 0.0, 0.0  rx=2.2 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1901694080] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=1.1, 0.0, 0.0  rx=1.1 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1901691054] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=1.1, 0.0, 0.0  rx=1.1 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1901691051] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,V/AlarmManager( 1031): RTC_WAKEUP set : Alarm{364c7467 type 0 when 1454092220081 com.android.vending} when 1454092220081
,V/SIM_STK ( 1031): Menu title from STK is T-Mobile
,V/GLSActivity( 2057): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     ( 2057): Explicit concurrent mark sweep GC freed 30410(1788KB) AllocSpace objects, 10(1440KB) LOS objects, 51% free, 30MB/62MB, paused 1.552ms total 39.237ms
,I/GLSUser ( 2057): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 2057): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2057): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2057): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2057): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/Finsky  ( 6981): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 6981): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 6981): [1] 5.onFinished: Scheduling replication attempt 3.
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.5 bcn=0 [on:0 tx:0 rx:0 period:2994] from screen [on:0 period:-1901688025] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.5 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1901688022] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=0.3, 0.0, 0.0  rx=0.3 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1901684998] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=0.3, 0.0, 0.0  rx=0.3 bcn=0 [on:0 tx:0 rx:0 period:12] from screen [on:0 period:-1901684986] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1901681966] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1901681963] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,D/sensors_hal_Time( 1031): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1031): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1031): tsOffsetIs: Apps: 320331946758; DSPS: 10637306; Offset : -4305789615
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=1.1, 0.0, 0.0  rx=0.6 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1901678938] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=1.1, 0.0, 0.0  rx=0.6 bcn=0 [on:0 tx:0 rx:0 period:13] from screen [on:0 period:-1901678925] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.3 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1901675904] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.3 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1901675901] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,V/AlarmManager( 1031): ELAPSED_WAKEUP set : Alarm{2df902f1 type 2 when 325235 android} when 325235
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=0.3, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1901672878] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=0.3, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:13] from screen [on:0 period:-1901672865] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1901669844] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1901669841] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1901666817] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1901666814] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1901663786] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1901663783] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1901660758] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:13] from screen [on:0 period:-1901660745] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
D/sensors_hal_Time( 1031): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1031): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1031): tsOffsetIs: Apps: 340333176490; DSPS: 11292706; Offset : -4305780377
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1901657724] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1901657721] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=1.0, 0.0, 0.0  rx=0.5 bcn=0 [on:0 tx:0 rx:0 period:3000] from screen [on:0 period:-1901654699] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=1.0, 0.0, 0.0  rx=0.5 bcn=0 [on:0 tx:0 rx:0 period:12] from screen [on:0 period:-1901654687] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
V/AlarmManager( 1031): RTC_WAKEUP set : Alarm{39454557 type 0 when 1454092243870 com.android.vending} when 1454092243870
,V/SIM_STK ( 1031): Menu title from STK is T-Mobile
,V/GLSActivity( 2057): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2057): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 2057): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2057): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2057): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2057): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/Finsky  ( 6981): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 6981): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 6981): [1] 5.onFinished: Scheduling replication attempt 4.
I/[SystemUI]TimeTickManager( 1468): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1468): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1468): called onTimeUpdated()
I/[SystemUI]Clock( 1468): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1468): called onTimeUpdated()
I/[SystemUI]DateView( 1468): called onTimeUpdated()
I/[SystemUI]DateView( 1468): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1468): handleTimeUpdate
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.3 bcn=0 [on:0 tx:0 rx:0 period:2999] from screen [on:0 period:-1901651668] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.3 bcn=0 [on:0 tx:0 rx:0 period:13] from screen [on:0 period:-1901651655] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=0.3, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1901648637] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=0.3, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1901648634] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1901645610] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:11] from screen [on:0 period:-1901645599] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1901642578] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:12] from screen [on:0 period:-1901642566] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3000] from screen [on:0 period:-1901639544] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1901639541] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,D/sensors_hal_Time( 1031): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1031): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1031): tsOffsetIs: Apps: 360335019659; DSPS: 11948127; Offset : -4305798754
,D/PowerManagerServiceEx( 1031): acquireWakeLockInternal: lock=398724214, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1031
,V/AlarmManager( 1031): ELAPSED_WAKEUP set : Alarm{8ff8a61 type 2 when 362546 android} when 362546
D/[Concierge]Service( 2617): onStartCommand(). Type : 9
,D/PowerManagerServiceEx( 1031): releaseWakeLockInternal: lock=398724214 [*alarm*], flags=0x0
,I/BooksSync( 6539): Starting books sync
,D/BooksSync( 6539): started syncMyEbooks
,I/art     ( 1031): Explicit concurrent mark sweep GC freed 56382(2MB) AllocSpace objects, 6(608KB) LOS objects, 33% free, 44MB/66MB, paused 2.342ms total 109.637ms
,V/GLSActivity( 2057): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/GLSUser ( 2057): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2057): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2057): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2057): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2057): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1031): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1031): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1031): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1031): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1031): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1412): onNotificationPosted
D/SmartCoverUpdateMonitor( 1412): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1412): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1412): handleNotificationPosted(true)
D/QuickCircle( 1412): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1412): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1412): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1412): post do just update job
D/LgeQuickCoverNotificationData( 1412): showAll3
D/LgeQuickCoverNotificationData( 1412): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1412): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1412): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1412): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1412): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1412): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1412): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1412): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1412): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1412): isNotificationForCurrentUser : true
,E/LgeQuickCoverOverlayWindow( 1412): updateNotificationData: count=3
W/GLSActivity( 2057): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2057): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2057): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2057): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2057): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2057): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2057): 	at android.os.Binder.execTransact(Binder.java:446)
E/BooksAccountManager( 6539): Authentication error
E/BooksAccountManager( 6539): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6539): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6539): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6539): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6539): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6539): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6539): null auth token
D/QuickStatusbarLayout( 1412): Notification difference=198
D/QuickStatusbarLayout( 1412): child = android.widget.LinearLayout{20ebe075 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,W/ApiaryClient( 6539): Error response from books API: {
W/ApiaryClient( 6539):  "error": {
W/ApiaryClient( 6539):   "errors": [
W/ApiaryClient( 6539):    {
W/ApiaryClient( 6539):     "domain": "global",
W/ApiaryClient( 6539):     "reason": "required",
W/ApiaryClient( 6539):     "message": "Login Required",
W/ApiaryClient( 6539):     "locationType": "header",
W/ApiaryClient( 6539):     "location": "Authorization"
W/ApiaryClient( 6539):    }
W/ApiaryClient( 6539):   ],
W/ApiaryClient( 6539):   "code": 401,
W/ApiaryClient( 6539):   "message": "Login Required"
W/ApiaryClient( 6539):  }
W/ApiaryClient( 6539): }
,W/ApiaryClient( 6539): errCount = 1: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6539): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-8420838090226548437&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6539): Headers:
W/ApiaryClient( 6539): accept-encoding: [gzip]
W/ApiaryClient( 6539): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6539): gdata-version: 2
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:-1901636520] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:4] from screen [on:0 period:-1901636516] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,V/GLSActivity( 2057): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,I/GLSUser ( 2057): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2057): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2057): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2057): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2057): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1031): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1031): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1031): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1031): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1031): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1412): onNotificationPosted
,D/SmartCoverUpdateMonitor( 1412): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1412): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1412): handleNotificationPosted(true)
D/QuickCircle( 1412): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1412): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1412): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1412): post do just update job
D/LgeQuickCoverNotificationData( 1412): showAll3
D/LgeQuickCoverNotificationData( 1412): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1412): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1412): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1412): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1412): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1412): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1412): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1412): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1412): [native noti] inex =  2
,D/LgeQuickCoverNotificationData( 1412): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1412): updateNotificationData: count=3
,W/GLSActivity( 2057): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2057): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2057): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2057): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2057): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2057): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2057): 	at android.os.Binder.execTransact(Binder.java:446)
D/QuickStatusbarLayout( 1412): Notification difference=198
D/QuickStatusbarLayout( 1412): child = android.widget.LinearLayout{20ebe075 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,E/BooksAccountManager( 6539): Authentication error
E/BooksAccountManager( 6539): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6539): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6539): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6539): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6539): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6539): 	at android.os.Binder.execTransact(Binder.java:446)
,E/HttpHelper( 6539): null auth token
W/ApiaryClient( 6539): Error response from books API: {
W/ApiaryClient( 6539):  "error": {
W/ApiaryClient( 6539):   "errors": [
W/ApiaryClient( 6539):    {
W/ApiaryClient( 6539):     "domain": "global",
W/ApiaryClient( 6539):     "reason": "required",
W/ApiaryClient( 6539):     "message": "Login Required",
W/ApiaryClient( 6539):     "locationType": "header",
W/ApiaryClient( 6539):     "location": "Authorization"
W/ApiaryClient( 6539):    }
W/ApiaryClient( 6539):   ],
W/ApiaryClient( 6539):   "code": 401,
W/ApiaryClient( 6539):   "message": "Login Required"
W/ApiaryClient( 6539):  }
W/ApiaryClient( 6539): }
W/ApiaryClient( 6539): errCount = 2: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6539): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-8420838090226548437&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6539): Headers:
W/ApiaryClient( 6539): accept-encoding: [gzip]
W/ApiaryClient( 6539): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6539): gdata-version: 2
,V/GLSActivity( 2057): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2057): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2057): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2057): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 2057): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2057): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1031): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1031): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1031): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1031): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1031): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1412): onNotificationPosted
D/SmartCoverUpdateMonitor( 1412): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1412): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1412): handleNotificationPosted(true)
D/QuickCircle( 1412): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1412): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1412): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1412): post do just update job
D/LgeQuickCoverNotificationData( 1412): showAll3
D/LgeQuickCoverNotificationData( 1412): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1412): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1412): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1412): showNotificationWithSetupData: display=false
,D/LgeQuickCoverOverlayWindow( 1412): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1412): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1412): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1412): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1412): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1412): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1412): updateNotificationData: count=3
W/GLSActivity( 2057): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2057): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2057): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2057): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2057): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2057): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2057): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 6539): Authentication error
E/BooksAccountManager( 6539): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6539): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6539): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6539): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6539): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6539): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6539): null auth token
D/QuickStatusbarLayout( 1412): Notification difference=198
D/QuickStatusbarLayout( 1412): child = android.widget.LinearLayout{20ebe075 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,W/ApiaryClient( 6539): Error response from books API: {
W/ApiaryClient( 6539):  "error": {
W/ApiaryClient( 6539):   "errors": [
W/ApiaryClient( 6539):    {
W/ApiaryClient( 6539):     "domain": "global",
W/ApiaryClient( 6539):     "reason": "required",
W/ApiaryClient( 6539):     "message": "Login Required",
W/ApiaryClient( 6539):     "locationType": "header",
W/ApiaryClient( 6539):     "location": "Authorization"
W/ApiaryClient( 6539):    }
W/ApiaryClient( 6539):   ],
W/ApiaryClient( 6539):   "code": 401,
W/ApiaryClient( 6539):   "message": "Login Required"
W/ApiaryClient( 6539):  }
W/ApiaryClient( 6539): }
,W/ApiaryClient( 6539): errCount = 3: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6539): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-8420838090226548437&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6539): Headers:
W/ApiaryClient( 6539): accept-encoding: [gzip]
W/ApiaryClient( 6539): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6539): gdata-version: 2
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=1.5, 0.0, 0.0  rx=1.0 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:-1901633498] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=1.5, 0.0, 0.0  rx=1.0 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-1901633488] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
E/BooksSync( 6539): Soft error: 
E/BooksSync( 6539): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 6539): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-8420838090226548437&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 6539): Headers:
E/BooksSync( 6539): accept-encoding: [gzip]
E/BooksSync( 6539): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 6539): gdata-version: 2
E/BooksSync( 6539): 
E/BooksSync( 6539): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 6539): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 6539): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 6539): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 6539): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 6539): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 6539): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 6539): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 6539): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 6539): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 6539): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 6539): {
E/BooksSync( 6539):  "error": {
E/BooksSync( 6539):   "errors": [
E/BooksSync( 6539):    {
E/BooksSync( 6539):     "domain": "global",
E/BooksSync( 6539):     "reason": "required",
E/BooksSync( 6539):     "message": "Login Required",
E/BooksSync( 6539):     "locationType": "header",
E/BooksSync( 6539):     "location": "Authorization"
E/BooksSync( 6539):    }
E/BooksSync( 6539):   ],
E/BooksSync( 6539):   "code": 401,
E/BooksSync( 6539):   "message": "Login Required"
E/BooksSync( 6539):  }
E/BooksSync( 6539): }
E/BooksSync( 6539): 
E/BooksSync( 6539): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 6539): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 6539): 	... 8 more
,E/BooksSync( 6539): Sync error
E/BooksSync( 6539): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 6539): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-8420838090226548437&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 6539): Headers:
E/BooksSync( 6539): accept-encoding: [gzip]
E/BooksSync( 6539): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 6539): gdata-version: 2
E/BooksSync( 6539): 
E/BooksSync( 6539): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 6539): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 6539): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 6539): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 6539): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 6539): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 6539): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 6539): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 6539): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 6539): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 6539): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 6539): {
E/BooksSync( 6539):  "error": {
E/BooksSync( 6539):   "errors": [
E/BooksSync( 6539):    {
E/BooksSync( 6539):     "domain": "global",
E/BooksSync( 6539):     "reason": "required",
E/BooksSync( 6539):     "message": "Login Required",
E/BooksSync( 6539):     "locationType": "header",
E/BooksSync( 6539):     "location": "Authorization"
E/BooksSync( 6539):    }
E/BooksSync( 6539):   ],
E/BooksSync( 6539):   "code": 401,
E/BooksSync( 6539):   "message": "Login Required"
E/BooksSync( 6539):  }
E/BooksSync( 6539): }
E/BooksSync( 6539): 
E/BooksSync( 6539): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 6539): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 6539): 	... 8 more
I/BooksSync( 6539): Finished books sync
D/SyncManager( 1031): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 362546, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=4.8, 0.0, 0.0  rx=3.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1901630466] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=4.8, 0.0, 0.0  rx=3.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1901630463] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=2.4, 0.0, 0.0  rx=1.5 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1901627437] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=2.4, 0.0, 0.0  rx=1.5 bcn=0 [on:0 tx:0 rx:0 period:4] from screen [on:0 period:-1901627433] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=1.2, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1901624406] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=1.2, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1901624403] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,V/AlarmManager( 1031): RTC_WAKEUP set : Alarm{e937840 type 0 when 1454092279143 com.android.vending} when 1454092279143
,V/SIM_STK ( 1031): Menu title from STK is T-Mobile
,V/GLSActivity( 2057): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2057): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 2057): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2057): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2057): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2057): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/Finsky  ( 6981): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 6981): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 6981): [1] 5.onFinished: Scheduling replication attempt 5.
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=0.6, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1901621378] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=0.6, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:11] from screen [on:0 period:-1901621367] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
D/sensors_hal_Time( 1031): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1031): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1031): tsOffsetIs: Apps: 380336599703; DSPS: 12603539; Offset : -4305805520
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=0.3, 0.0, 0.0  rx=0.2 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1901618344] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=0.3, 0.0, 0.0  rx=0.2 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1901618341] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1901615315] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1901615312] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1901612286] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1901612283] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:-1901609255] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-1901609254] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,V/AlarmManager( 1031): ELAPSED_WAKEUP set : Alarm{1924f122 type 2 when 392746 android} when 392746
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=1.0, 0.0, 0.0  rx=0.5 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1901606240] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=1.0, 0.0, 0.0  rx=0.5 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-1901606230] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.3 bcn=0 [on:0 tx:0 rx:0 period:3000] from screen [on:0 period:-1901603209] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.3 bcn=0 [on:0 tx:0 rx:0 period:9] from screen [on:0 period:-1901603200] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=0.3, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1901600178] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=0.3, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:11] from screen [on:0 period:-1901600167] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
D/sensors_hal_Time( 1031): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1031): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1031): tsOffsetIs: Apps: 400338181206; DSPS: 13258950; Offset : -4305780544
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1901597146] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1901597143] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,V/AlarmManager( 1031): RTC_WAKEUP set : Alarm{38957170 type 0 when 1454092309484 com.android.vending} when 1454092309484
,V/SIM_STK ( 1031): Menu title from STK is T-Mobile
,V/GLSActivity( 2057): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2057): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 2057): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2057): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2057): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2057): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/Finsky  ( 6981): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 6981): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 6981): [1] 5.onFinished: Giving up after 6 failures.
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-56 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1901594119] gl rssi=-56 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-56 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:11] from screen [on:0 period:-1901594108] gl rssi=-56 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
I/[SystemUI]TimeTickManager( 1468): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1468): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1468): called onTimeUpdated()
I/[SystemUI]Clock( 1468): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1468): called onTimeUpdated()
I/[SystemUI]DateView( 1468): called onTimeUpdated()
,I/[SystemUI]DateView( 1468): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1468): handleTimeUpdate
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-56 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1901591084] gl rssi=-56 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-56 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1901591081] gl rssi=-56 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-56 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1901588057] gl rssi=-56 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-56 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:4] from screen [on:0 period:-1901588053] gl rssi=-56 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-56 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1901585029] gl rssi=-56 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-56 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:9] from screen [on:0 period:-1901585020] gl rssi=-56 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-56 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:2999] from screen [on:0 period:-1901582001] gl rssi=-56 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-56 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:2] from screen [on:0 period:-1901581999] gl rssi=-56 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,D/sensors_hal_Time( 1031): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1031): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1031): tsOffsetIs: Apps: 420339992657; DSPS: 13914370; Offset : -4305800174
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-56 f=2412 sc=60 link=72 tx=1.0, 0.0, 0.0  rx=0.5 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1901578979] gl rssi=-56 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-56 f=2412 sc=60 link=72 tx=1.0, 0.0, 0.0  rx=0.5 bcn=0 [on:0 tx:0 rx:0 period:9] from screen [on:0 period:-1901578970] gl rssi=-56 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-56 f=2412 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.3 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1901575949] gl rssi=-56 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-56 f=2412 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.3 bcn=0 [on:0 tx:0 rx:0 period:9] from screen [on:0 period:-1901575940] gl rssi=-56 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-56 f=2412 sc=60 link=72 tx=0.3, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3000] from screen [on:0 period:-1901572920] gl rssi=-56 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-56 f=2412 sc=60 link=72 tx=0.3, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-1901572910] gl rssi=-56 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-56 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1901569890] gl rssi=-56 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-56 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:9] from screen [on:0 period:-1901569881] gl rssi=-56 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-56 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1901566860] gl rssi=-56 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-56 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:11] from screen [on:0 period:-1901566849] gl rssi=-56 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-56 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1901563829] gl rssi=-56 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-56 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-1901563819] gl rssi=-56 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-56 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1901560799] gl rssi=-56 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-56 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:9] from screen [on:0 period:-1901560790] gl rssi=-56 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
D/sensors_hal_Time( 1031): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1031): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1031): tsOffsetIs: Apps: 440341610983; DSPS: 14569783; Offset : -4305799175
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-56 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1901557777] gl rssi=-56 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-56 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1901557774] gl rssi=-56 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-56 f=2412 sc=60 link=72 tx=1.0, 0.0, 0.0  rx=0.5 bcn=0 [on:0 tx:0 rx:0 period:3000] from screen [on:0 period:-1901554750] gl rssi=-56 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-56 f=2412 sc=60 link=72 tx=1.0, 0.0, 0.0  rx=0.5 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-1901554740] gl rssi=-56 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-56 f=2412 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.3 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1901551721] gl rssi=-56 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-56 f=2412 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.3 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1901551718] gl rssi=-56 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-56 f=2412 sc=60 link=72 tx=0.3, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1901548692] gl rssi=-56 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-56 f=2412 sc=60 link=72 tx=0.3, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1901548689] gl rssi=-56 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-56 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1901545662] gl rssi=-56 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-56 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1901545659] gl rssi=-56 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-56 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1901542634] gl rssi=-56 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-56 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1901542631] gl rssi=-56 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-56 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3008] from screen [on:0 period:-1901539600] gl rssi=-56 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-56 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-1901539590] gl rssi=-56 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
D/sensors_hal_Time( 1031): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1031): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1031): tsOffsetIs: Apps: 460343150766; DSPS: 15225193; Offset : -4305785297
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-56 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1901536573] gl rssi=-56 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-56 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1901536570] gl rssi=-56 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-56 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1901533544] gl rssi=-56 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-56 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1901533541] gl rssi=-56 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,I/[SystemUI]TimeTickManager( 1468): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1468): called onTimeUpdated()
,I/[SystemUI]KeyguardIndicationController( 1468): called onTimeUpdated()
,I/[SystemUI]Clock( 1468): called onTimeUpdated()
I/LgeClockWidgetControlView( 1468): called onTimeUpdated()
I/[SystemUI]DateView( 1468): called onTimeUpdated()
,I/[SystemUI]DateView( 1468): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1468): handleTimeUpdate
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-56 f=2412 sc=60 link=72 tx=1.0, 0.0, 0.0  rx=0.5 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1901530514] gl rssi=-56 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-56 f=2412 sc=60 link=72 tx=1.0, 0.0, 0.0  rx=0.5 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1901530511] gl rssi=-56 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-56 f=2412 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.3 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1901527484] gl rssi=-56 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-56 f=2412 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.3 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1901527481] gl rssi=-56 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-56 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=1.1 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:-1901524461] gl rssi=-56 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-56 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=1.1 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1901524458] gl rssi=-56 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-56 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.6 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1901521431] gl rssi=-56 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-56 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.6 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1901521428] gl rssi=-56 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,D/sensors_hal_Time( 1031): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1031): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1031): tsOffsetIs: Apps: 480344729457; DSPS: 15880605; Offset : -4305793520
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-56 f=2412 sc=60 link=72 tx=2.7, 0.0, 0.0  rx=3.8 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1901518401] gl rssi=-56 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-56 f=2412 sc=60 link=72 tx=2.7, 0.0, 0.0  rx=3.8 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1901518398] gl rssi=-56 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-56 f=2412 sc=60 link=72 tx=1.3, 0.0, 0.0  rx=1.9 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1901515372] gl rssi=-56 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-56 f=2412 sc=60 link=72 tx=1.3, 0.0, 0.0  rx=1.9 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1901515369] gl rssi=-56 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-56 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.9 bcn=0 [on:0 tx:0 rx:0 period:3000] from screen [on:0 period:-1901512340] gl rssi=-56 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-56 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.9 bcn=0 [on:0 tx:0 rx:0 period:9] from screen [on:0 period:-1901512331] gl rssi=-56 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
I/[SystemUI]LGPowerUI( 1468): onReceive = com.lge.android.intent.action.BATTERYEX
,I/[SystemUI]LGPowerUI( 1468): On Skip Timer : true
D/KeyguardUpdateMonitor( 1468): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 285
D/WifiController( 1031): battery changed pluggedType: 2
D/LEDHandler( 1928): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1928): Battery Level Remaining: 100%
D/LEDHandler( 1928): Battery Temp: 285, mChargingStatus=5, mChargingStop=false
,I/[SystemUI]LGPowerUI( 1468): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]BatterySaverHandler( 1468): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings( 1031): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1031): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/HeadsetStateMachine( 6188): Disconnected process message: 10, size: 0
D/LGDMClient( 3943): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.intent.action.BATTERY_CHANGED
D/LGDMClient( 3943): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=0.3, 0.0, 0.0  rx=0.5 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1901509307] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=0.3, 0.0, 0.0  rx=0.5 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1901509304] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,D/PowerManagerServiceEx( 1031): acquireWakeLockInternal: lock=398724214, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1031
,V/AlarmManager( 1031): ELAPSED_WAKEUP set : Alarm{2b4fe6d2 type 2 when 493292 android} when 493292
D/[Concierge]Service( 2617): onStartCommand(). Type : 9
,D/PowerManagerServiceEx( 1031): releaseWakeLockInternal: lock=398724214 [*alarm*], flags=0x0
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=1.2, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:2999] from screen [on:0 period:-1901506290] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=1.2, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-1901506289] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,I/BooksSync( 6539): Starting books sync
,D/BooksSync( 6539): started syncMyEbooks
,V/GLSActivity( 2057): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2057): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2057): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2057): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2057): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2057): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1031): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1031): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1031): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1031): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1031): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1412): onNotificationPosted
,D/SmartCoverUpdateMonitor( 1412): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1412): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1412): handleNotificationPosted(true)
D/QuickCircle( 1412): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1412): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1412): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1412): post do just update job
D/LgeQuickCoverNotificationData( 1412): showAll3
D/LgeQuickCoverNotificationData( 1412): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1412): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1412): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1412): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1412): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1412): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1412): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1412): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1412): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1412): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1412): updateNotificationData: count=3
W/GLSActivity( 2057): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2057): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2057): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2057): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2057): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2057): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2057): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 6539): Authentication error
E/BooksAccountManager( 6539): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6539): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6539): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6539): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6539): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6539): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6539): null auth token
D/QuickStatusbarLayout( 1412): Notification difference=198
D/QuickStatusbarLayout( 1412): child = android.widget.LinearLayout{20ebe075 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,W/ApiaryClient( 6539): Error response from books API: {
W/ApiaryClient( 6539):  "error": {
W/ApiaryClient( 6539):   "errors": [
W/ApiaryClient( 6539):    {
W/ApiaryClient( 6539):     "domain": "global",
W/ApiaryClient( 6539):     "reason": "required",
W/ApiaryClient( 6539):     "message": "Login Required",
W/ApiaryClient( 6539):     "locationType": "header",
W/ApiaryClient( 6539):     "location": "Authorization"
W/ApiaryClient( 6539):    }
W/ApiaryClient( 6539):   ],
W/ApiaryClient( 6539):   "code": 401,
W/ApiaryClient( 6539):   "message": "Login Required"
W/ApiaryClient( 6539):  }
W/ApiaryClient( 6539): }
,W/ApiaryClient( 6539): errCount = 1: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6539): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=5023212558254606546&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6539): Headers:
W/ApiaryClient( 6539): accept-encoding: [gzip]
W/ApiaryClient( 6539): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6539): gdata-version: 2
V/GLSActivity( 2057): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2057): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2057): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2057): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2057): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2057): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1031): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1031): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1031): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1031): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1031): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1412): onNotificationPosted
D/SmartCoverUpdateMonitor( 1412): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1412): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1412): handleNotificationPosted(true)
D/QuickCircle( 1412): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1412): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1412): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1412): post do just update job
D/LgeQuickCoverNotificationData( 1412): showAll3
D/LgeQuickCoverNotificationData( 1412): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1412): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1412): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1412): showNotificationWithSetupData: display=false
,D/LgeQuickCoverOverlayWindow( 1412): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1412): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1412): [native noti] inex =  1
,D/LgeQuickCoverNotificationData( 1412): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1412): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1412): isNotificationForCurrentUser : true
,E/LgeQuickCoverOverlayWindow( 1412): updateNotificationData: count=3
D/QuickStatusbarLayout( 1412): Notification difference=198
D/QuickStatusbarLayout( 1412): child = android.widget.LinearLayout{20ebe075 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
W/GLSActivity( 2057): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2057): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2057): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2057): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2057): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2057): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2057): 	at android.os.Binder.execTransact(Binder.java:446)
E/BooksAccountManager( 6539): Authentication error
E/BooksAccountManager( 6539): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6539): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6539): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6539): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6539): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6539): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6539): null auth token
,I/art     ( 1412): Background sticky concurrent mark sweep GC freed 28119(1647KB) AllocSpace objects, 21(2MB) LOS objects, 7% free, 54MB/58MB, paused 5.351ms total 63.501ms
,W/ApiaryClient( 6539): Error response from books API: {
W/ApiaryClient( 6539):  "error": {
W/ApiaryClient( 6539):   "errors": [
W/ApiaryClient( 6539):    {
W/ApiaryClient( 6539):     "domain": "global",
W/ApiaryClient( 6539):     "reason": "required",
W/ApiaryClient( 6539):     "message": "Login Required",
W/ApiaryClient( 6539):     "locationType": "header",
W/ApiaryClient( 6539):     "location": "Authorization"
W/ApiaryClient( 6539):    }
W/ApiaryClient( 6539):   ],
W/ApiaryClient( 6539):   "code": 401,
W/ApiaryClient( 6539):   "message": "Login Required"
W/ApiaryClient( 6539):  }
W/ApiaryClient( 6539): }
,W/ApiaryClient( 6539): errCount = 2: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6539): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=5023212558254606546&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6539): Headers:
W/ApiaryClient( 6539): accept-encoding: [gzip]
W/ApiaryClient( 6539): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6539): gdata-version: 2
,V/GLSActivity( 2057): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2057): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2057): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2057): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2057): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2057): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1031): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1031): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1031): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1031): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1031): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
W/ResourcesManager( 1412): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/GLSActivity( 2057): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2057): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2057): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2057): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2057): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2057): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2057): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 6539): Authentication error
E/BooksAccountManager( 6539): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6539): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6539): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6539): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6539): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6539): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6539): null auth token
W/ResourcesManager( 1412): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
D/LgeQuickCoverNLService( 1412): onNotificationPosted
D/SmartCoverUpdateMonitor( 1412): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1412): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1412): handleNotificationPosted(true)
D/QuickCircle( 1412): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1412): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1412): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1412): post do just update job
D/LgeQuickCoverNotificationData( 1412): showAll3
D/LgeQuickCoverNotificationData( 1412): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1412): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1412): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1412): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1412): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1412): isNotificationForCurrentUser : true
,W/ResourcesManager( 1412): Asset path '/system/framework/com.lge.systemui.jar' does not exist or contains no resources.
W/ResourcesManager( 1412): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
D/LgeQuickCoverOverlayWindow( 1412): [native noti] inex =  1
,D/LgeQuickCoverNotificationData( 1412): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1412): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1412): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1412): updateNotificationData: count=3
,D/QuickStatusbarLayout( 1412): Notification difference=198
D/QuickStatusbarLayout( 1412): child = android.widget.LinearLayout{20ebe075 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
W/ApiaryClient( 6539): Error response from books API: {
W/ApiaryClient( 6539):  "error": {
W/ApiaryClient( 6539):   "errors": [
W/ApiaryClient( 6539):    {
W/ApiaryClient( 6539):     "domain": "global",
W/ApiaryClient( 6539):     "reason": "required",
W/ApiaryClient( 6539):     "message": "Login Required",
W/ApiaryClient( 6539):     "locationType": "header",
W/ApiaryClient( 6539):     "location": "Authorization"
W/ApiaryClient( 6539):    }
W/ApiaryClient( 6539):   ],
W/ApiaryClient( 6539):   "code": 401,
W/ApiaryClient( 6539):   "message": "Login Required"
W/ApiaryClient( 6539):  }
W/ApiaryClient( 6539): }
,W/ApiaryClient( 6539): errCount = 3: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6539): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=5023212558254606546&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6539): Headers:
W/ApiaryClient( 6539): accept-encoding: [gzip]
W/ApiaryClient( 6539): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6539): gdata-version: 2
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=0.6, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1901503273] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=0.6, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1901503270] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/BooksSync( 6539): Soft error: 
E/BooksSync( 6539): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 6539): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=5023212558254606546&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 6539): Headers:
E/BooksSync( 6539): accept-encoding: [gzip]
E/BooksSync( 6539): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 6539): gdata-version: 2
E/BooksSync( 6539): 
E/BooksSync( 6539): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 6539): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 6539): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 6539): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 6539): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 6539): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 6539): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 6539): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 6539): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 6539): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 6539): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 6539): {
E/BooksSync( 6539):  "error": {
E/BooksSync( 6539):   "errors": [
E/BooksSync( 6539):    {
E/BooksSync( 6539):     "domain": "global",
E/BooksSync( 6539):     "reason": "required",
E/BooksSync( 6539):     "message": "Login Required",
E/BooksSync( 6539):     "locationType": "header",
E/BooksSync( 6539):     "location": "Authorization"
E/BooksSync( 6539):    }
E/BooksSync( 6539):   ],
E/BooksSync( 6539):   "code": 401,
E/BooksSync( 6539):   "message": "Login Required"
E/BooksSync( 6539):  }
E/BooksSync( 6539): }
E/BooksSync( 6539): 
E/BooksSync( 6539): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 6539): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 6539): 	... 8 more
,E/BooksSync( 6539): Sync error
E/BooksSync( 6539): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 6539): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=5023212558254606546&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 6539): Headers:
E/BooksSync( 6539): accept-encoding: [gzip]
E/BooksSync( 6539): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 6539): gdata-version: 2
E/BooksSync( 6539): 
E/BooksSync( 6539): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 6539): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 6539): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 6539): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 6539): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 6539): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 6539): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 6539): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 6539): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 6539): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 6539): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 6539): {
E/BooksSync( 6539):  "error": {
E/BooksSync( 6539):   "errors": [
E/BooksSync( 6539):    {
E/BooksSync( 6539):     "domain": "global",
E/BooksSync( 6539):     "reason": "required",
E/BooksSync( 6539):     "message": "Login Required",
E/BooksSync( 6539):     "locationType": "header",
E/BooksSync( 6539):     "location": "Authorization"
E/BooksSync( 6539):    }
E/BooksSync( 6539):   ],
E/BooksSync( 6539):   "code": 401,
E/BooksSync( 6539):   "message": "Login Required"
E/BooksSync( 6539):  }
E/BooksSync( 6539): }
E/BooksSync( 6539): 
E/BooksSync( 6539): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 6539): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 6539): 	... 8 more
I/BooksSync( 6539): Finished books sync
D/SyncManager( 1031): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 493292, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=4.8, 0.0, 0.0  rx=3.2 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1901500252] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=4.8, 0.0, 0.0  rx=3.2 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1901500249] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,D/sensors_hal_Time( 1031): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1031): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1031): tsOffsetIs: Apps: 500346590855; DSPS: 16536026; Offset : -4305793747
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=2.4, 0.0, 0.0  rx=1.6 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1901497224] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=2.4, 0.0, 0.0  rx=1.6 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1901497221] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=1.2, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3000] from screen [on:0 period:-1901494199] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=1.2, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:14] from screen [on:0 period:-1901494185] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=0.6, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1901491165] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=0.6, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:2] from screen [on:0 period:-1901491163] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=0.3, 0.0, 0.0  rx=0.2 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1901488135] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=0.3, 0.0, 0.0  rx=0.2 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1901488132] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1901485107] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1901485104] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1901482078] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-1901482068] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
D/sensors_hal_Time( 1031): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1031): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1031): tsOffsetIs: Apps: 520348199494; DSPS: 17191439; Offset : -4305802539
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=1.0, 0.0, 0.0  rx=0.5 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:-1901479045] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=1.0, 0.0, 0.0  rx=0.5 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1901479042] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,V/AlarmManager( 1031): ELAPSED_WAKEUP set : Alarm{3151d12c type 2 when 523516 android} when 523516,
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.3 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1901476018] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.3 bcn=0 [on:0 tx:0 rx:0 period:9] from screen [on:0 period:-1901476009] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
I/[SystemUI]TimeTickManager( 1468): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1468): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1468): called onTimeUpdated()
I/[SystemUI]Clock( 1468): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1468): called onTimeUpdated()
I/[SystemUI]DateView( 1468): called onTimeUpdated()
I/[SystemUI]DateView( 1468): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1468): handleTimeUpdate
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=0.3, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3000] from screen [on:0 period:-1901472997] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=0.3, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:4] from screen [on:0 period:-1901472993] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1901469966] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0,
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:4] from screen [on:0 period:-1901469962] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1901466936] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1901466933] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3000] from screen [on:0 period:-1901463909] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-1901463899] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1901460878] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:9] from screen [on:0 period:-1901460869] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
D/sensors_hal_Time( 1031): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1031): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1031): tsOffsetIs: Apps: 540350822872; DSPS: 17846885; Offset : -4305803752
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1901457849] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:8] from screen [on:0 period:-1901457841] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=1.0, 0.0, 0.0  rx=0.5 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1901454821] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=1.0, 0.0, 0.0  rx=0.5 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1901454818] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
V/GLSActivity( 2057): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2057): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 2057): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2057): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2057): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2057): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1031): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1031): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1031): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1031): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1031): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1412): onNotificationPosted
,D/SmartCoverUpdateMonitor( 1412): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1412): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1412): handleNotificationPosted(true)
D/QuickCircle( 1412): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1412): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1412): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1412): post do just update job
D/LgeQuickCoverNotificationData( 1412): showAll3
D/LgeQuickCoverNotificationData( 1412): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1412): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1412): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1412): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1412): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1412): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1412): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1412): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1412): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1412): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1412): updateNotificationData: count=3
,W/GLSActivity( 2057): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2057): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2057): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2057): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2057): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2057): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2057): 	at android.os.Binder.execTransact(Binder.java:446)
E/PlayEventLogger( 6981): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 6981): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 6981): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/PlayEventLogger( 6981): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 6981): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/PlayEventLogger( 6981): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 6981): 	at android.os.Binder.execTransact(Binder.java:446)
,D/QuickStatusbarLayout( 1412): Notification difference=198
D/QuickStatusbarLayout( 1412): child = android.widget.LinearLayout{20ebe075 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
W/System  ( 6981): Ignoring header User-Agent because its value was null.
,D/libc-netbsd(  335): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  335): res_queryN name = play.googleapis.com, class = 1, type = 1
D/libc-netbsd(  335): res_queryN name = play.googleapis.com succeed
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.3 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1901451790] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.3 bcn=0 [on:0 tx:0 rx:0 period:4] from screen [on:0 period:-1901451786] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=2.3, 0.0, 0.0  rx=1.1 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:-1901448777] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=2.3, 0.0, 0.0  rx=1.1 bcn=0 [on:0 tx:0 rx:0 period:4] from screen [on:0 period:-1901448773] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=4.6, 0.0, 0.0  rx=4.6 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1901445748] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=4.6, 0.0, 0.0  rx=4.6 bcn=0 [on:0 tx:0 rx:0 period:11] from screen [on:0 period:-1901445737] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=2.3, 0.0, 0.0  rx=2.3 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1901442717] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=2.3, 0.0, 0.0  rx=2.3 bcn=0 [on:0 tx:0 rx:0 period:4] from screen [on:0 period:-1901442713] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=1.2, 0.0, 0.0  rx=1.1 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1901439688] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=1.2, 0.0, 0.0  rx=1.1 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-1901439678] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
D/sensors_hal_Time( 1031): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1031): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1031): tsOffsetIs: Apps: 560351926979; DSPS: 18502281; Offset : -4305798095
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=0.6, 0.0, 0.0  rx=0.6 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1901436656] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=0.6, 0.0, 0.0  rx=0.6 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1901436653] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=0.3, 0.0, 0.0  rx=0.3 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1901433626] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=0.3, 0.0, 0.0  rx=0.3 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1901433623] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=1.1, 0.0, 0.0  rx=0.6 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1901430599] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=1.1, 0.0, 0.0  rx=0.6 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-1901430589] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=0.6, 0.0, 0.0  rx=0.3 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1901427569] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=0.6, 0.0, 0.0  rx=0.3 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-1901427559] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=0.3, 0.0, 0.0  rx=0.2 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1901424536] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=0.3, 0.0, 0.0  rx=0.2 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1901424533] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1901421507] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:4] from screen [on:0 period:-1901421503] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,D/sensors_hal_Time( 1031): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1031): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1031): tsOffsetIs: Apps: 580353740357; DSPS: 19157700; Offset : -4305785280
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1901418477] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1901418474] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1901415450] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1901415447] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
I/[SystemUI]TimeTickManager( 1468): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1468): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1468): called onTimeUpdated()
I/[SystemUI]Clock( 1468): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1468): called onTimeUpdated()
I/[SystemUI]DateView( 1468): called onTimeUpdated()
I/[SystemUI]DateView( 1468): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1468): handleTimeUpdate
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1901412421] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1901412418] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3006] from screen [on:0 period:-1901409386] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-1901409385] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=1.0, 0.0, 0.0  rx=0.5 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:-1901406373] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=1.0, 0.0, 0.0  rx=0.5 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1901406370] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.3 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1901403344] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.3 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1901403341] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-56 f=2412 sc=60 link=72 tx=0.3, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1901400317] gl rssi=-56 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-56 f=2412 sc=60 link=72 tx=0.3, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1901400314] gl rssi=-56 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,D/sensors_hal_Time( 1031): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1031): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1031): tsOffsetIs: Apps: 600355480140; DSPS: 19813117; Offset : -4305785025
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-56 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1901397288] gl rssi=-56 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-56 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:8] from screen [on:0 period:-1901397280] gl rssi=-56 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-56 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1901394259] gl rssi=-56 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-56 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-1901394249] gl rssi=-56 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-56 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1901391230] gl rssi=-56 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-56 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-1901391220] gl rssi=-56 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-56 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1901388199] gl rssi=-56 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-56 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:9] from screen [on:0 period:-1901388190] gl rssi=-56 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-56 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3000] from screen [on:0 period:-1901385170] gl rssi=-56 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-56 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-1901385160] gl rssi=-56 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-56 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3000] from screen [on:0 period:-1901382141] gl rssi=-56 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-56 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1901382138] gl rssi=-56 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
D/sensors_hal_Time( 1031): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1031): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1031): tsOffsetIs: Apps: 620357285549; DSPS: 20468536; Offset : -4305780283
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-56 f=2412 sc=60 link=72 tx=1.0, 0.0, 0.0  rx=0.5 bcn=0 [on:0 tx:0 rx:0 period:2999] from screen [on:0 period:-1901379110] gl rssi=-56 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-56 f=2412 sc=60 link=72 tx=1.0, 0.0, 0.0  rx=0.5 bcn=0 [on:0 tx:0 rx:0 period:9] from screen [on:0 period:-1901379101] gl rssi=-56 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-56 f=2412 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.3 bcn=0 [on:0 tx:0 rx:0 period:3000] from screen [on:0 period:-1901376082] gl rssi=-56 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-56 f=2412 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.3 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1901376079] gl rssi=-56 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-56 f=2412 sc=60 link=72 tx=0.3, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1901373053] gl rssi=-56 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-56 f=2412 sc=60 link=72 tx=0.3, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1901373050] gl rssi=-56 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-56 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1901370024] gl rssi=-56 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-56 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1901370021] gl rssi=-56 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-56 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1901366995] gl rssi=-56 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-56 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1901366992] gl rssi=-56 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-56 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1901363967] gl rssi=-56 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-56 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1901363964] gl rssi=-56 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-56 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1901360938] gl rssi=-56 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-56 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-1901360928] gl rssi=-56 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
D/sensors_hal_Time( 1031): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1031): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1031): tsOffsetIs: Apps: 640362681376; DSPS: 21124073; Offset : -4305786015
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-56 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1901357908] gl rssi=-56 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-56 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:8] from screen [on:0 period:-1901357900] gl rssi=-56 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-56 f=2412 sc=60 link=72 tx=1.0, 0.0, 0.0  rx=0.5 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1901354879] gl rssi=-56 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-56 f=2412 sc=60 link=72 tx=1.0, 0.0, 0.0  rx=0.5 bcn=0 [on:0 tx:0 rx:0 period:11] from screen [on:0 period:-1901354868] gl rssi=-56 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
I/[SystemUI]TimeTickManager( 1468): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1468): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1468): called onTimeUpdated()
I/[SystemUI]Clock( 1468): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1468): called onTimeUpdated()
I/[SystemUI]DateView( 1468): called onTimeUpdated()
I/[SystemUI]DateView( 1468): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1468): handleTimeUpdate
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-56 f=2412 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.3 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1901351846] gl rssi=-56 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-56 f=2412 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.3 bcn=0 [on:0 tx:0 rx:0 period:4] from screen [on:0 period:-1901351842] gl rssi=-56 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-56 f=2412 sc=60 link=72 tx=0.3, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1901348818] gl rssi=-56 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-56 f=2412 sc=60 link=72 tx=0.3, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-1901348808] gl rssi=-56 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-56 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:2999] from screen [on:0 period:-1901345790] gl rssi=-56 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-56 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-1901345789] gl rssi=-56 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-56 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1901342770] gl rssi=-56 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-56 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1901342767] gl rssi=-56 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1901339737] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1901339734] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,D/sensors_hal_Time( 1031): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1031): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1031): tsOffsetIs: Apps: 660364214388; DSPS: 21779483; Offset : -4305778908
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1901336706] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1901336703] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1901333679] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:9] from screen [on:0 period:-1901333670] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=1.0, 0.0, 0.0  rx=0.5 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1901330650] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=1.0, 0.0, 0.0  rx=0.5 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-1901330640] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.3 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1901327619] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.3 bcn=0 [on:0 tx:0 rx:0 period:9] from screen [on:0 period:-1901327610] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=0.3, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1901324589] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=0.3, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:9] from screen [on:0 period:-1901324580] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1901321559] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:9] from screen [on:0 period:-1901321550] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
D/sensors_hal_Time( 1031): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1031): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1031): tsOffsetIs: Apps: 680365879693; DSPS: 22434898; Offset : -4305791992
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1901318529] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:9] from screen [on:0 period:-1901318520] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1901315500] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1901315497] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3000] from screen [on:0 period:-1901312472] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1901312469] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1901309445] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1901309442] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1901306418] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:9] from screen [on:0 period:-1901306409] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=1.0, 0.0, 0.0  rx=0.5 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1901303388] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=1.0, 0.0, 0.0  rx=0.5 bcn=0 [on:0 tx:0 rx:0 period:9] from screen [on:0 period:-1901303379] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.3 bcn=0 [on:0 tx:0 rx:0 period:3000] from screen [on:0 period:-1901300359] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.3 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-1901300349] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
D/sensors_hal_Time( 1031): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1031): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1031): tsOffsetIs: Apps: 700367665310; DSPS: 23090317; Offset : -4305806964
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=0.3, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1901297327] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=0.3, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:4] from screen [on:0 period:-1901297323] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3000] from screen [on:0 period:-1901294300] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-1901294290] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
I/[SystemUI]TimeTickManager( 1468): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1468): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1468): called onTimeUpdated()
I/[SystemUI]Clock( 1468): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1468): called onTimeUpdated()
I/[SystemUI]DateView( 1468): called onTimeUpdated()
I/[SystemUI]DateView( 1468): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1468): handleTimeUpdate
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1901291270] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:9] from screen [on:0 period:-1901291261] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1901288240] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1901288237] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1901285210] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-1901285200] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1901282183] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1901282180] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,D/sensors_hal_Time( 1031): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1031): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1031): tsOffsetIs: Apps: 720369270303; DSPS: 23745729; Offset : -4305788781
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=1.0, 0.0, 0.0  rx=0.5 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1901279155] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=1.0, 0.0, 0.0  rx=0.5 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1901279152] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.3 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1901276128] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.3 bcn=0 [on:0 tx:0 rx:0 period:4] from screen [on:0 period:-1901276124] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=0.3, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1901273099] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=0.3, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:8] from screen [on:0 period:-1901273091] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3000] from screen [on:0 period:-1901270079] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-1901270069] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1901267046] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1901267043] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:-1901264015] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:2] from screen [on:0 period:-1901264013] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1901260986] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1901260983] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,D/sensors_hal_Time( 1031): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1031): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1031): tsOffsetIs: Apps: 740371416233; DSPS: 24401159; Offset : -4305779264
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=1.5, 0.0, 0.0  rx=2.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1901257958] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=1.5, 0.0, 0.0  rx=2.0 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-1901257948] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=1.8, 0.0, 0.0  rx=1.5 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1901254928] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=1.8, 0.0, 0.0  rx=1.5 bcn=0 [on:0 tx:0 rx:0 period:13] from screen [on:0 period:-1901254915] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=0.9, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1901251895] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=0.9, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1901251892] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1901248865] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1901248862] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=0.2, 0.0, 0.0  rx=0.2 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1901245837] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=0.2, 0.0, 0.0  rx=0.2 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1901245834] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1901242810] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:8] from screen [on:0 period:-1901242802] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1901239780] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:9] from screen [on:0 period:-1901239771] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
D/sensors_hal_Time( 1031): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1031): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1031): tsOffsetIs: Apps: 760373122267; DSPS: 25056575; Offset : -4305782058
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3000] from screen [on:0 period:-1901236751] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1901236748] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3005] from screen [on:0 period:-1901233719] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0,
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:19] from screen [on:0 period:-1901233700] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,I/[SystemUI]TimeTickManager( 1468): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1468): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1468): called onTimeUpdated()
I/[SystemUI]Clock( 1468): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1468): called onTimeUpdated()
I/[SystemUI]DateView( 1468): called onTimeUpdated()
I/[SystemUI]DateView( 1468): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1468): handleTimeUpdate
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=1.0, 0.0, 0.0  rx=0.5 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1901230682] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=1.0, 0.0, 0.0  rx=0.5 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1901230679] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.3 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1901227654] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.3 bcn=0 [on:0 tx:0 rx:0 period:4] from screen [on:0 period:-1901227650] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,I/[SystemUI]LGPowerUI( 1468): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1468): On Skip Timer : true
,D/LEDHandler( 1928): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1928): Battery Level Remaining: 100%
D/LEDHandler( 1928): Battery Temp: 281, mChargingStatus=5, mChargingStop=false
,D/KeyguardUpdateMonitor( 1468): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 281
I/[SystemUI]LGPowerUI( 1468): onReceive = android.intent.action.BATTERY_CHANGED
D/WifiController( 1031): battery changed pluggedType: 2
I/[SystemUI]BatterySaverHandler( 1468): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings( 1031): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1031): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/HeadsetStateMachine( 6188): Disconnected process message: 10, size: 0
D/LGDMClient( 3943): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.intent.action.BATTERY_CHANGED
D/LGDMClient( 3943): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=0.3, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1901224623] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=0.3, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1901224620] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:-1901221594] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1901221591] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,D/sensors_hal_Time( 1031): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1031): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1031): tsOffsetIs: Apps: 780374952936; DSPS: 25711995; Offset : -4305782601
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1901218566] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1901218563] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,D/PowerManagerServiceEx( 1031): acquireWakeLockInternal: lock=398724214, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1031
,V/AlarmManager( 1031): ELAPSED_WAKEUP set : Alarm{316cc82e type 2 when 750608 android} when 750608
V/AlarmManager( 1031): RTC_WAKEUP set : Alarm{31e36fcf type 0 when 1454092356077 com.google.android.gms} when 1454092356077
D/[Concierge]Service( 2617): onStartCommand(). Type : 9
,D/PowerManagerServiceEx( 1031): releaseWakeLockInternal: lock=398724214 [*alarm*], flags=0x0
,I/EventLogService( 2332): Aggregate from 1454090555934 (log), 1454090555934 (data)
,I/BooksSync( 6539): Starting books sync
,I/art     ( 1031): Explicit concurrent mark sweep GC freed 139274(6MB) AllocSpace objects, 9(1040KB) LOS objects, 33% free, 44MB/67MB, paused 2.930ms total 166.166ms
,D/BooksSync( 6539): started syncMyEbooks
,V/GLSActivity( 2057): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/GLSUser ( 2057): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 2057): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2057): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2057): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2057): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1031): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1031): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1031): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1031): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1031): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
W/GLSActivity( 2057): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2057): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2057): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2057): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2057): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2057): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2057): 	at android.os.Binder.execTransact(Binder.java:446)
E/BooksAccountManager( 6539): Authentication error
E/BooksAccountManager( 6539): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6539): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6539): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6539): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6539): 	,at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6539): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6539): null auth token
,D/LgeQuickCoverNLService( 1412): onNotificationPosted
D/SmartCoverUpdateMonitor( 1412): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1412): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1412): handleNotificationPosted(true)
D/QuickCircle( 1412): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1412): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1412): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1412): post do just update job
D/LgeQuickCoverNotificationData( 1412): showAll3
D/LgeQuickCoverNotificationData( 1412): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1412): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1412): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1412): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1412): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1412): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1412): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1412): isNotificationForCurrentUser : true
D/libc-netbsd(  335): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  335): res_queryN name = www.googleapis.com, class = 1, type = 1
D/LgeQuickCoverOverlayWindow( 1412): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1412): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1412): updateNotificationData: count=3
D/QuickStatusbarLayout( 1412): Notification difference=198
D/QuickStatusbarLayout( 1412): child = android.widget.LinearLayout{20ebe075 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,D/libc-netbsd(  335): res_queryN name = www.googleapis.com succeed
,W/ApiaryClient( 6539): Error response from books API: {
W/ApiaryClient( 6539):  "error": {
W/ApiaryClient( 6539):   "errors": [
W/ApiaryClient( 6539):    {
W/ApiaryClient( 6539):     "domain": "global",
W/ApiaryClient( 6539):     "reason": "required",
W/ApiaryClient( 6539):     "message": "Login Required",
W/ApiaryClient( 6539):     "locationType": "header",
W/ApiaryClient( 6539):     "location": "Authorization"
W/ApiaryClient( 6539):    }
W/ApiaryClient( 6539):   ],
W/ApiaryClient( 6539):   "code": 401,
W/ApiaryClient( 6539):   "message": "Login Required"
W/ApiaryClient( 6539):  }
W/ApiaryClient( 6539): }
,W/ApiaryClient( 6539): errCount = 1: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6539): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-5069095493592214798&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6539): Headers:
W/ApiaryClient( 6539): accept-encoding: [gzip]
W/ApiaryClient( 6539): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6539): gdata-version: 2
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1901215537] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1901215534] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,V/GLSActivity( 2057): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2057): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2057): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2057): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2057): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2057): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1031): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1031): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1031): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1031): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1031): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1412): onNotificationPosted
,D/SmartCoverUpdateMonitor( 1412): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1412): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1412): handleNotificationPosted(true)
D/QuickCircle( 1412): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1412): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1412): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1412): post do just update job
D/LgeQuickCoverNotificationData( 1412): showAll3
D/LgeQuickCoverNotificationData( 1412): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1412): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1412): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1412): showNotificationWithSetupData: display=false
,D/LgeQuickCoverOverlayWindow( 1412): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1412): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1412): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1412): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1412): [native noti] inex =  2
,D/LgeQuickCoverNotificationData( 1412): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1412): updateNotificationData: count=3
W/GLSActivity( 2057): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2057): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2057): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2057): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2057): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2057): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2057): 	at android.os.Binder.execTransact(Binder.java:446)
,D/QuickStatusbarLayout( 1412): Notification difference=198
D/QuickStatusbarLayout( 1412): child = android.widget.LinearLayout{20ebe075 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
E/BooksAccountManager( 6539): Authentication error
E/BooksAccountManager( 6539): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6539): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6539): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6539): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6539): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6539): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6539): null auth token
W/ApiaryClient( 6539): Error response from books API: {
W/ApiaryClient( 6539):  "error": {
W/ApiaryClient( 6539):   "errors": [
W/ApiaryClient( 6539):    {
W/ApiaryClient( 6539):     "domain": "global",
W/ApiaryClient( 6539):     "reason": "required",
W/ApiaryClient( 6539):     "message": "Login Required",
W/ApiaryClient( 6539):     "locationType": "header",
W/ApiaryClient( 6539):     "location": "Authorization"
W/ApiaryClient( 6539):    }
W/ApiaryClient( 6539):   ],
W/ApiaryClient( 6539):   "code": 401,
W/ApiaryClient( 6539):   "message": "Login Required"
W/ApiaryClient( 6539):  }
W/ApiaryClient( 6539): }
,W/ApiaryClient( 6539): errCount = 2: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6539): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-5069095493592214798&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6539): Headers:
W/ApiaryClient( 6539): accept-encoding: [gzip]
W/ApiaryClient( 6539): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6539): gdata-version: 2
V/GLSActivity( 2057): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2057): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2057): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2057): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2057): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2057): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     ( 2057): Explicit concurrent mark sweep GC freed 34543(2MB) AllocSpace objects, 19(2MB) LOS objects, 50% free, 30MB/62MB, paused 2.250ms total 59.397ms
,V/NotificationService( 1031): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1031): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1031): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1031): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1031): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1412): onNotificationPosted
D/SmartCoverUpdateMonitor( 1412): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1412): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1412): handleNotificationPosted(true)
D/QuickCircle( 1412): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1412): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1412): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1412): post do just update job
D/LgeQuickCoverNotificationData( 1412): showAll3
D/LgeQuickCoverNotificationData( 1412): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1412): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1412): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1412): showNotificationWithSetupData: display=false
,D/LgeQuickCoverOverlayWindow( 1412): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1412): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1412): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1412): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1412): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1412): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1412): updateNotificationData: count=3
W/GLSActivity( 2057): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2057): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2057): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2057): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2057): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2057): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2057): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 6539): Authentication error
E/BooksAccountManager( 6539): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6539): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6539): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6539): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6539): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6539): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6539): null auth token
D/QuickStatusbarLayout( 1412): Notification difference=198
D/QuickStatusbarLayout( 1412): child = android.widget.LinearLayout{20ebe075 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,W/ApiaryClient( 6539): Error response from books API: {
W/ApiaryClient( 6539):  "error": {
W/ApiaryClient( 6539):   "errors": [
W/ApiaryClient( 6539):    {
W/ApiaryClient( 6539):     "domain": "global",
W/ApiaryClient( 6539):     "reason": "required",
W/ApiaryClient( 6539):     "message": "Login Required",
W/ApiaryClient( 6539):     "locationType": "header",
W/ApiaryClient( 6539):     "location": "Authorization"
W/ApiaryClient( 6539):    }
W/ApiaryClient( 6539):   ],
W/ApiaryClient( 6539):   "code": 401,
W/ApiaryClient( 6539):   "message": "Login Required"
W/ApiaryClient( 6539):  }
W/ApiaryClient( 6539): }
W/ApiaryClient( 6539): errCount = 3: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6539): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-5069095493592214798&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6539): Headers:
W/ApiaryClient( 6539): accept-encoding: [gzip]
W/ApiaryClient( 6539): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6539): gdata-version: 2
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=4.5, 0.0, 0.0  rx=4.5 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1901212508] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=4.5, 0.0, 0.0  rx=4.5 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-1901212498] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
E/BooksSync( 6539): Soft error: 
E/BooksSync( 6539): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 6539): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-5069095493592214798&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 6539): Headers:
E/BooksSync( 6539): accept-encoding: [gzip]
E/BooksSync( 6539): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 6539): gdata-version: 2
E/BooksSync( 6539): 
E/BooksSync( 6539): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 6539): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 6539): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 6539): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 6539): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 6539): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 6539): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 6539): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 6539): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 6539): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 6539): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 6539): {
E/BooksSync( 6539):  "error": {
E/BooksSync( 6539):   "errors": [
E/BooksSync( 6539):    {
E/BooksSync( 6539):     "domain": "global",
E/BooksSync( 6539):     "reason": "required",
E/BooksSync( 6539):     "message": "Login Required",
E/BooksSync( 6539):     "locationType": "header",
E/BooksSync( 6539):     "location": "Authorization"
E/BooksSync( 6539):    }
E/BooksSync( 6539):   ],
E/BooksSync( 6539):   "code": 401,
E/BooksSync( 6539):   "message": "Login Required"
E/BooksSync( 6539):  }
E/BooksSync( 6539): }
E/BooksSync( 6539): 
E/BooksSync( 6539): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 6539): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 6539): 	... 8 more
,E/BooksSync( 6539): Sync error
E/BooksSync( 6539): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 6539): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-5069095493592214798&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 6539): Headers:
E/BooksSync( 6539): accept-encoding: [gzip]
E/BooksSync( 6539): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 6539): gdata-version: 2
E/BooksSync( 6539): 
E/BooksSync( 6539): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 6539): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 6539): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 6539): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 6539): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 6539): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 6539): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 6539): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 6539): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 6539): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 6539): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 6539): {
E/BooksSync( 6539):  "error": {
E/BooksSync( 6539):   "errors": [
E/BooksSync( 6539):    {
E/BooksSync( 6539):     "domain": "global",
E/BooksSync( 6539):     "reason": "required",
E/BooksSync( 6539):     "message": "Login Required",
E/BooksSync( 6539):     "locationType": "header",
E/BooksSync( 6539):     "location": "Authorization"
E/BooksSync( 6539):    }
E/BooksSync( 6539):   ],
E/BooksSync( 6539):   "code": 401,
E/BooksSync( 6539):   "message": "Login Required"
E/BooksSync( 6539):  }
E/BooksSync( 6539): }
E/BooksSync( 6539): 
E/BooksSync( 6539): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 6539): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 6539): 	... 8 more
I/BooksSync( 6539): Finished books sync
D/SyncManager( 1031): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 750608, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=4.3, 0.0, 0.0  rx=4.3 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1901209475] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=4.3, 0.0, 0.0  rx=4.3 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1901209472] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=4.1, 0.0, 0.0  rx=4.6 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1901206453] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=4.1, 0.0, 0.0  rx=4.6 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1901206450] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=3.1, 0.0, 0.0  rx=2.8 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1901203427] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=3.1, 0.0, 0.0  rx=2.8 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1901203424] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=1.5, 0.0, 0.0  rx=1.4 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1901200401] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=1.5, 0.0, 0.0  rx=1.4 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1901200398] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,D/sensors_hal_Time( 1031): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1031): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1031): tsOffsetIs: Apps: 800376535533; DSPS: 26367407; Offset : -4305787048
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1901197370] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:9] from screen [on:0 period:-1901197361] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1901194340] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:9] from screen [on:0 period:-1901194331] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-58 f=2412 sc=60 link=72 tx=0.2, 0.0, 0.0  rx=0.2 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1901191308] gl rssi=-58 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-58 f=2412 sc=60 link=72 tx=0.2, 0.0, 0.0  rx=0.2 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-1901191298] gl rssi=-58 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-58 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1901188277] gl rssi=-58 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-58 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:4] from screen [on:0 period:-1901188273] gl rssi=-58 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,V/AlarmManager( 1031): ELAPSED_WAKEUP set : Alarm{39d63ef9 type 2 when 813007 android} when 813007
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-58 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1901185246] gl rssi=-58 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-58 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1901185243] gl rssi=-58 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-58 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1901182217] gl rssi=-58 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-58 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:4] from screen [on:0 period:-1901182213] gl rssi=-58 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,D/sensors_hal_Time( 1031): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1031): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1031): tsOffsetIs: Apps: 820378107765; DSPS: 27022819; Offset : -4305801704
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-58 f=2412 sc=60 link=72 tx=1.0, 0.0, 0.0  rx=0.5 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1901179188] gl rssi=-58 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-58 f=2412 sc=60 link=72 tx=1.0, 0.0, 0.0  rx=0.5 bcn=0 [on:0 tx:0 rx:0 period:4] from screen [on:0 period:-1901179184] gl rssi=-58 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-58 f=2412 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.3 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1901176163] gl rssi=-58 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-58 f=2412 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.3 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1901176160] gl rssi=-58 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,I/[SystemUI]TimeTickManager( 1468): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1468): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1468): called onTimeUpdated()
I/[SystemUI]Clock( 1468): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1468): called onTimeUpdated()
I/[SystemUI]DateView( 1468): called onTimeUpdated()
I/[SystemUI]DateView( 1468): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1468): handleTimeUpdate
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-58 f=2412 sc=60 link=72 tx=0.3, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1901173133] gl rssi=-58 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-58 f=2412 sc=60 link=72 tx=0.3, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1901173130] gl rssi=-58 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-58 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1901170105] gl rssi=-58 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-58 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1901170102] gl rssi=-58 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-58 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1901167085] gl rssi=-58 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-58 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1901167082] gl rssi=-58 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-58 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1901164055] gl rssi=-58 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-58 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1901164052] gl rssi=-58 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-58 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3008] from screen [on:0 period:-1901161021] gl rssi=-58 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-58 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:11] from screen [on:0 period:-1901161010] gl rssi=-58 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
D/sensors_hal_Time( 1031): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1031): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1031): tsOffsetIs: Apps: 840379490101; DSPS: 27678224; Offset : -4305792502
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-58 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1901157988] gl rssi=-58 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-58 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-1901157978] gl rssi=-58 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
D/PowerManagerServiceEx( 1031): acquireWakeLockInternal: lock=398724214, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1031
,V/AlarmManager( 1031): ELAPSED_WAKEUP set : Alarm{14fede3e type 2 when 843030 android} when 843030
D/[Concierge]Service( 2617): onStartCommand(). Type : 9
,D/PowerManagerServiceEx( 1031): releaseWakeLockInternal: lock=398724214 [*alarm*], flags=0x0
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-58 f=2412 sc=60 link=72 tx=1.0, 0.0, 0.0  rx=0.5 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1901154960] gl rssi=-58 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-58 f=2412 sc=60 link=72 tx=1.0, 0.0, 0.0  rx=0.5 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1901154957] gl rssi=-58 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-58 f=2412 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.3 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1901151929] gl rssi=-58 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-58 f=2412 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.3 bcn=0 [on:0 tx:0 rx:0 period:9] from screen [on:0 period:-1901151920] gl rssi=-58 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-58 f=2412 sc=60 link=72 tx=0.3, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1901148898] gl rssi=-58 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-58 f=2412 sc=60 link=72 tx=0.3, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:11] from screen [on:0 period:-1901148887] gl rssi=-58 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-58 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1901145866] gl rssi=-58 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-58 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1901145863] gl rssi=-58 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-58 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1901142837] gl rssi=-58 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-58 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1901142834] gl rssi=-58 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-58 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1901139809] gl rssi=-58 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-58 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-1901139799] gl rssi=-58 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
D/sensors_hal_Time( 1031): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1031): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1031): tsOffsetIs: Apps: 860381197229; DSPS: 28333640; Offset : -4305794202
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-58 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1901136779] gl rssi=-58 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-58 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:9] from screen [on:0 period:-1901136770] gl rssi=-58 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-58 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1901133750] gl rssi=-58 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-58 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:9] from screen [on:0 period:-1901133741] gl rssi=-58 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-58 f=2412 sc=60 link=72 tx=1.0, 0.0, 0.0  rx=0.5 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1901130726] gl rssi=-58 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-58 f=2412 sc=60 link=72 tx=1.0, 0.0, 0.0  rx=0.5 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1901130723] gl rssi=-58 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-58 f=2412 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.3 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1901127694] gl rssi=-58 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-58 f=2412 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.3 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1901127691] gl rssi=-58 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-58 f=2412 sc=60 link=72 tx=0.3, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1901124664] gl rssi=-58 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-58 f=2412 sc=60 link=72 tx=0.3, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1901124661] gl rssi=-58 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-58 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1901121635] gl rssi=-58 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-58 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1901121632] gl rssi=-58 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,D/sensors_hal_Time( 1031): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1031): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1031): tsOffsetIs: Apps: 880383035659; DSPS: 28989060; Offset : -4305787035
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-58 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1901118607] gl rssi=-58 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-58 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1901118604] gl rssi=-58 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-58 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1901115579] gl rssi=-58 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-58 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:8] from screen [on:0 period:-1901115571] gl rssi=-58 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
I/[SystemUI]TimeTickManager( 1468): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1468): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1468): called onTimeUpdated()
I/[SystemUI]Clock( 1468): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1468): called onTimeUpdated()
I/[SystemUI]DateView( 1468): called onTimeUpdated()
I/[SystemUI]DateView( 1468): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1468): handleTimeUpdate
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-58 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1901112551] gl rssi=-58 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-58 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1901112548] gl rssi=-58 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-58 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1901109521] gl rssi=-58 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-58 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1901109518] gl rssi=-58 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-58 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1901106492] gl rssi=-58 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-58 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1901106489] gl rssi=-58 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-58 f=2412 sc=60 link=72 tx=1.0, 0.0, 0.0  rx=0.5 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1901103464] gl rssi=-58 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-58 f=2412 sc=60 link=72 tx=1.0, 0.0, 0.0  rx=0.5 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1901103461] gl rssi=-58 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-58 f=2412 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.3 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1901100434] gl rssi=-58 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-58 f=2412 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.3 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1901100431] gl rssi=-58 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,D/sensors_hal_Time( 1031): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1031): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1031): tsOffsetIs: Apps: 900384391589; DSPS: 29644465; Offset : -4305804423
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-58 f=2412 sc=60 link=72 tx=0.3, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1901097406] gl rssi=-58 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-58 f=2412 sc=60 link=72 tx=0.3, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1901097403] gl rssi=-58 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3000] from screen [on:0 period:-1901094379] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-1901094369] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1901091349] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:9] from screen [on:0 period:-1901091340] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1901088319] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:11] from screen [on:0 period:-1901088308] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1901085288] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:4] from screen [on:0 period:-1901085284] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1901082260] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-1901082250] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
D/sensors_hal_Time( 1031): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1031): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1031): tsOffsetIs: Apps: 920386177258; DSPS: 30299883; Offset : -4305788928
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=1.0, 0.0, 0.0  rx=0.5 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1901079228] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=1.0, 0.0, 0.0  rx=0.5 bcn=0 [on:0 tx:0 rx:0 period:8] from screen [on:0 period:-1901079220] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.3 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1901076200] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.3 bcn=0 [on:0 tx:0 rx:0 period:9] from screen [on:0 period:-1901076191] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=0.3, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1901073170] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=0.3, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:9] from screen [on:0 period:-1901073161] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3000] from screen [on:0 period:-1901070142] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1901070139] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3000] from screen [on:0 period:-1901067114] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1901067111] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1901064086] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1901064083] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1901061056] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1901061053] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,D/sensors_hal_Time( 1031): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1031): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1031): tsOffsetIs: Apps: 940387526625; DSPS: 30955287; Offset : -4305782284
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1901058028] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:13] from screen [on:0 period:-1901058015] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=1.0, 0.0, 0.0  rx=0.5 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1901054995] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=1.0, 0.0, 0.0  rx=0.5 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1901054992] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,I/[SystemUI]TimeTickManager( 1468): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1468): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1468): called onTimeUpdated()
I/[SystemUI]Clock( 1468): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1468): called onTimeUpdated()
I/[SystemUI]DateView( 1468): called onTimeUpdated()
I/[SystemUI]DateView( 1468): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1468): handleTimeUpdate
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.3 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1901051966] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.3 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1901051963] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=0.3, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1901048938] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=0.3, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-1901048928] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3000] from screen [on:0 period:-1901045909] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:9] from screen [on:0 period:-1901045900] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1901042880] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:9] from screen [on:0 period:-1901042871] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1901039851] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1901039848] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,D/sensors_hal_Time( 1031): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1031): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1031): tsOffsetIs: Apps: 960389401045; DSPS: 31610709; Offset : -4305799720
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1901036823] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1901036820] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1901033793] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1901033790] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=1.0, 0.0, 0.0  rx=0.5 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1901030773] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=1.0, 0.0, 0.0  rx=0.5 bcn=0 [on:0 tx:0 rx:0 period:4] from screen [on:0 period:-1901030769] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.3 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1901027744] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.3 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1901027741] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=0.3, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1901024715] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=0.3, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1901024712] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3000] from screen [on:0 period:-1901021689] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:9] from screen [on:0 period:-1901021680] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
D/sensors_hal_Time( 1031): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1031): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1031): tsOffsetIs: Apps: 980391222392; DSPS: 32266129; Offset : -4305809505
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1901018660] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:9] from screen [on:0 period:-1901018651] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3000] from screen [on:0 period:-1901015632] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1901015629] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1901012603] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1901012600] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1901009575] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1901009572] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1901006546] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1901006543] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=1.0, 0.0, 0.0  rx=0.5 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1901003521] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=1.0, 0.0, 0.0  rx=0.5 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1901003518] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.3 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1901000491] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.3 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1901000488] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,D/sensors_hal_Time( 1031): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1031): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1031): tsOffsetIs: Apps: 1000392867123; DSPS: 32921542; Offset : -4305782023
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=0.3, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3000] from screen [on:0 period:-1900997463] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=0.3, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1900997460] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1900994434] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1900994431] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,I/[SystemUI]TimeTickManager( 1468): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1468): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1468): called onTimeUpdated()
I/[SystemUI]Clock( 1468): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1468): called onTimeUpdated()
I/[SystemUI]DateView( 1468): called onTimeUpdated()
I/[SystemUI]DateView( 1468): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1468): handleTimeUpdate
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1900991405] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1900991402] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3000] from screen [on:0 period:-1900988378] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:11] from screen [on:0 period:-1900988367] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1900985346] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1900985343] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1900982317] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:4] from screen [on:0 period:-1900982313] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=1.0, 0.0, 0.0  rx=0.5 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1900979288] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/sensors_hal_Time( 1031): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1031): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1031): tsOffsetIs: Apps: 1020396422532; DSPS: 33577019; Offset : -4305797380
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=1.0, 0.0, 0.0  rx=0.5 bcn=0 [on:0 tx:0 rx:0 period:14] from screen [on:0 period:-1900979274] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.3 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1900976252] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.3 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1900976249] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=0.3, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1900973222] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=0.3, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1900973219] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1900970198] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-1900970188] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=0.6, 0.0, 0.0  rx=1.0 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:-1900967165] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=0.6, 0.0, 0.0  rx=1.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1900967162] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=0.3, 0.0, 0.0  rx=0.5 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1900964136] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=0.3, 0.0, 0.0  rx=0.5 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1900964133] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.3 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1900961108] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.3 bcn=0 [on:0 tx:0 rx:0 period:9] from screen [on:0 period:-1900961099] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
D/sensors_hal_Time( 1031): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1031): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1031): tsOffsetIs: Apps: 1040397962420; DSPS: 34232429; Offset : -4305783422
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1900958080] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1900958077] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=1.0, 0.0, 0.0  rx=0.6 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1900955050] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=1.0, 0.0, 0.0  rx=0.6 bcn=0 [on:0 tx:0 rx:0 period:9] from screen [on:0 period:-1900955041] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.3 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1900952019] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.3 bcn=0 [on:0 tx:0 rx:0 period:9] from screen [on:0 period:-1900952010] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=0.3, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1900948989] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=0.3, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:9] from screen [on:0 period:-1900948980] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1900945957] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1900945954] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1900942929] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:8] from screen [on:0 period:-1900942921] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1900939900] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1900939897] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
D/sensors_hal_Time( 1031): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1031): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1031): tsOffsetIs: Apps: 1060399600694; DSPS: 34887843; Offset : -4305792915
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1900936870] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1900936867] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1900933842] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1900933839] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,I/[SystemUI]TimeTickManager( 1468): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1468): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1468): called onTimeUpdated()
I/[SystemUI]Clock( 1468): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1468): called onTimeUpdated()
I/[SystemUI]DateView( 1468): called onTimeUpdated()
I/[SystemUI]DateView( 1468): called onTimeUpdated()
,D/KeyguardUpdateMonitor( 1468): handleTimeUpdate
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=1.0, 0.0, 0.0  rx=0.5 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1900930821] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=1.0, 0.0, 0.0  rx=0.5 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1900930818] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.3 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1900927792] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.3 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1900927789] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=0.3, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1900924764] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=0.3, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1900924761] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1900921736] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1900921733] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,D/sensors_hal_Time( 1031): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1031): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1031): tsOffsetIs: Apps: 1080402011989; DSPS: 35543282; Offset : -4305792430
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1900918708] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:9] from screen [on:0 period:-1900918699] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1900915678] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:11] from screen [on:0 period:-1900915667] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1900912649] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:11] from screen [on:0 period:-1900912638] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1900909618] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:15] from screen [on:0 period:-1900909603] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1900906582] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-1900906581] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=1.0, 0.0, 0.0  rx=0.5 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1900903564] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=1.0, 0.0, 0.0  rx=0.5 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1900903561] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.3 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1900900536] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.3 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1900900533] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,D/sensors_hal_Time( 1031): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1031): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1031): tsOffsetIs: Apps: 1100403357241; DSPS: 36198686; Offset : -4305790291
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=0.3, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1900897506] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=0.3, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1900897503] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3000] from screen [on:0 period:-1900894479] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-1900894469] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1900891450] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:9] from screen [on:0 period:-1900891441] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1900888419] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:9] from screen [on:0 period:-1900888410] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1900885388] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:9] from screen [on:0 period:-1900885379] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1900882359] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-1900882349] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=1.0, 0.0, 0.0  rx=0.5 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1900879329] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=1.0, 0.0, 0.0  rx=0.5 bcn=0 [on:0 tx:0 rx:0 period:9] from screen [on:0 period:-1900879320] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
D/sensors_hal_Time( 1031): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1031): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1031): tsOffsetIs: Apps: 1120405057338; DSPS: 36854102; Offset : -4305799074
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.3 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1900876299] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.3 bcn=0 [on:0 tx:0 rx:0 period:9] from screen [on:0 period:-1900876290] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=0.3, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3000] from screen [on:0 period:-1900873271] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=0.3, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1900873268] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,I/[SystemUI]TimeTickManager( 1468): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1468): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1468): called onTimeUpdated()
I/[SystemUI]Clock( 1468): called onTimeUpdated()
I/LgeClockWidgetControlView( 1468): called onTimeUpdated()
I/[SystemUI]DateView( 1468): called onTimeUpdated()
I/[SystemUI]DateView( 1468): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1468): handleTimeUpdate
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1900870226] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1900870223] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,D/PowerManagerServiceEx( 1031): acquireWakeLockInternal: lock=398724214, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1031
,V/AlarmManager( 1031): ELAPSED_WAKEUP set : Alarm{3a2fb49f type 2 when 1131167 com.android.bluetooth} when 1131167
,W/bt-smp  ( 6188): Key(LSB ~ MSB) = 0a 3c a6 fe eb 17 6a 79 a6 1f 0a 0b f9 50 a0 5f 
W/bt-smp  ( 6188): Plain text(LSB ~ MSB) = 05 e4 42 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 6188): Encrypted text(LSB ~ MSB) = 64 44 b1 53 fa 05 92 71 de f2 03 9e 20 b1 b0 3d 
W/bt-btm  ( 6188): Stopping oneshot timer
D/[Concierge]Service( 2617): onStartCommand(). Type : 9
,D/PowerManagerServiceEx( 1031): releaseWakeLockInternal: lock=398724214 [*alarm*], flags=0x0
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1900867194] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1900867191] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1900864164] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1900864161] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1900861135] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1900861132] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,D/sensors_hal_Time( 1031): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1031): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1031): tsOffsetIs: Apps: 1140406607330; DSPS: 37509513; Offset : -4305805426
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1900858105] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:2] from screen [on:0 period:-1900858103] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,V/AlarmManager( 1031): ELAPSED_WAKEUP set : Alarm{215289ec type 2 when 1137181 com.google.android.gms} when 1137181
,D/GCM     ( 2057): Message class com.google.f.a.a.i
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=1.0, 0.0, 0.0  rx=0.5 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1900855075] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=1.0, 0.0, 0.0  rx=0.5 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1900855072] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=1.5, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1900852046] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=1.5, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1900852043] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1900849017] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:4] from screen [on:0 period:-1900849013] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.2 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1900845987] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.2 bcn=0 [on:0 tx:0 rx:0 period:4] from screen [on:0 period:-1900845983] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=0.2, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1900842958] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=0.2, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:9] from screen [on:0 period:-1900842949] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:-1900839926] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1900839923] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,D/sensors_hal_Time( 1031): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1031): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1031): tsOffsetIs: Apps: 1160408417583; DSPS: 38164932; Offset : -4305795789
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1900836896] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1900836893] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1900833866] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1900833863] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=1.0, 0.0, 0.0  rx=0.5 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1900830841] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=1.0, 0.0, 0.0  rx=0.5 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1900830838] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.3 bcn=0 [on:0 tx:0 rx:0 period:3000] from screen [on:0 period:-1900827814] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.3 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1900827811] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=0.3, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3000] from screen [on:0 period:-1900824786] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=0.3, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1900824783] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1900821761] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1900821758] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,D/sensors_hal_Time( 1031): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1031): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1031): tsOffsetIs: Apps: 1180409834398; DSPS: 38820338; Offset : -4305782625
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1900818730] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:8] from screen [on:0 period:-1900818722] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1900815700] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:9] from screen [on:0 period:-1900815691] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
I/[SystemUI]TimeTickManager( 1468): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1468): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1468): called onTimeUpdated()
I/[SystemUI]Clock( 1468): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1468): called onTimeUpdated()
I/[SystemUI]DateView( 1468): called onTimeUpdated()
I/[SystemUI]DateView( 1468): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1468): handleTimeUpdate
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1900812670] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-1900812660] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
D/PowerManagerServiceEx( 1031): acquireWakeLockInternal: lock=398724214, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1031
,D/[Concierge]Service( 2617): onStartCommand(). Type : 9
,I/DigitalAppWidgetProvider( 6808): onReceive: com.android.deskclock.ON_QUARTER_HOUR
,V/DigitalAppWidgetProvider( 6808): startAlarmOnQuarterHour android.app.ReceiverRestrictedContext@125ecfa2
D/PowerManagerServiceEx( 1031): releaseWakeLockInternal: lock=398724214 [*alarm*], flags=0x0
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1900809639] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-1900809629] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1900806608] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-1900806598] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=1.0, 0.0, 0.0  rx=0.5 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:-1900803576] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=1.0, 0.0, 0.0  rx=0.5 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1900803573] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.3 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1900800548] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.3 bcn=0 [on:0 tx:0 rx:0 period:9] from screen [on:0 period:-1900800539] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
D/sensors_hal_Time( 1031): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1031): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1031): tsOffsetIs: Apps: 1200412288453; DSPS: 39475779; Offset : -4305800573
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=0.3, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1900797521] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=0.3, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1900797518] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1900794492] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1900794489] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3000] from screen [on:0 period:-1900791469] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:9] from screen [on:0 period:-1900791460] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1900788439] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-1900788429] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3000] from screen [on:0 period:-1900785409] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-1900785399] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1900782379] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-1900782369] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=1.0, 0.0, 0.0  rx=0.5 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1900779348] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=1.0, 0.0, 0.0  rx=0.5 bcn=0 [on:0 tx:0 rx:0 period:4] from screen [on:0 period:-1900779344] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,D/sensors_hal_Time( 1031): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1031): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1031): tsOffsetIs: Apps: 1220413927561; DSPS: 40131192; Offset : -4305779000
,I/UsageStatsService( 1031): User[0] Flushing usage stats to disk
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.3 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1900776319] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.3 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-1900776309] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=0.3, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1900773289] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=0.3, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:9] from screen [on:0 period:-1900773280] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1900770259] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:9] from screen [on:0 period:-1900770250] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1900767231] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1900767228] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1900764198] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:8] from screen [on:0 period:-1900764190] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1900761169] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:9] from screen [on:0 period:-1900761160] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
D/sensors_hal_Time( 1031): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1031): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1031): tsOffsetIs: Apps: 1240415725573; DSPS: 40786611; Offset : -4305781395
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1900758138] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-1900758128] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=1.0, 0.0, 0.0  rx=0.5 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1900755108] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=1.0, 0.0, 0.0  rx=0.5 bcn=0 [on:0 tx:0 rx:0 period:9] from screen [on:0 period:-1900755099] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
I/[SystemUI]TimeTickManager( 1468): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1468): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1468): called onTimeUpdated()
I/[SystemUI]Clock( 1468): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1468): called onTimeUpdated()
I/[SystemUI]DateView( 1468): called onTimeUpdated()
I/[SystemUI]DateView( 1468): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1468): handleTimeUpdate
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.3 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1900752079] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.3 bcn=0 [on:0 tx:0 rx:0 period:9] from screen [on:0 period:-1900752070] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=0.3, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1900749049] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=0.3, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-1900749039] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3005] from screen [on:0 period:-1900746015] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-1900746005] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1900742990] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:9] from screen [on:0 period:-1900742981] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1900739959] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:9] from screen [on:0 period:-1900739950] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
D/sensors_hal_Time( 1031): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1031): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1031): tsOffsetIs: Apps: 1260417544263; DSPS: 41442031; Offset : -4305793708
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1900736928] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:9] from screen [on:0 period:-1900736919] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1900733899] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-1900733889] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1900730869] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-1900730859] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=1.0, 0.0, 0.0  rx=0.5 bcn=0 [on:0 tx:0 rx:0 period:3000] from screen [on:0 period:-1900727840] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=1.0, 0.0, 0.0  rx=0.5 bcn=0 [on:0 tx:0 rx:0 period:9] from screen [on:0 period:-1900727831] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.3 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1900724808] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.3 bcn=0 [on:0 tx:0 rx:0 period:9] from screen [on:0 period:-1900724799] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=0.3, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1900721779] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=0.3, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-1900721769] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
D/sensors_hal_Time( 1031): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1031): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1031): tsOffsetIs: Apps: 1280419101391; DSPS: 42097442; Offset : -4305793132
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1900718747] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1900718744] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1900715718] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:9] from screen [on:0 period:-1900715709] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1900712689] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-1900712679] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1900709658] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-1900709648] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1900706632] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1900706629] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,D/PowerManagerServiceEx( 1031): acquireWakeLockInternal: lock=398724214, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1031
,V/AlarmManager( 1031): ELAPSED_WAKEUP set : Alarm{2eb2d1b5 type 2 when 1294003 android} when 1294003
D/[Concierge]Service( 2617): onStartCommand(). Type : 9
,D/PowerManagerServiceEx( 1031): releaseWakeLockInternal: lock=398724214 [*alarm*], flags=0x0
,I/BooksSync( 6539): Starting books sync
,D/BooksSync( 6539): started syncMyEbooks
V/GLSActivity( 2057): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2057): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2057): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2057): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2057): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2057): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1031): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1031): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1031): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1031): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1031): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1412): onNotificationPosted
D/SmartCoverUpdateMonitor( 1412): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1412): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1412): handleNotificationPosted(true)
D/QuickCircle( 1412): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1412): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1412): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1412): post do just update job
D/LgeQuickCoverNotificationData( 1412): showAll3
D/LgeQuickCoverNotificationData( 1412): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1412): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1412): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1412): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1412): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1412): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1412): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1412): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1412): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1412): isNotificationForCurrentUser : true
,E/LgeQuickCoverOverlayWindow( 1412): updateNotificationData: count=3
W/GLSActivity( 2057): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2057): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2057): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2057): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2057): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2057): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2057): 	at android.os.Binder.execTransact(Binder.java:446)
E/BooksAccountManager( 6539): Authentication error
E/BooksAccountManager( 6539): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6539): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6539): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6539): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6539): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6539): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6539): null auth token
D/QuickStatusbarLayout( 1412): Notification difference=198
D/QuickStatusbarLayout( 1412): child = android.widget.LinearLayout{20ebe075 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,D/libc-netbsd(  335): default dns: query_ipv6=0, query_ipv4=1
,D/libc-netbsd(  335): res_queryN name = www.googleapis.com, class = 1, type = 1
D/libc-netbsd(  335): res_queryN name = www.googleapis.com succeed
,W/ApiaryClient( 6539): Error response from books API: {
W/ApiaryClient( 6539):  "error": {
W/ApiaryClient( 6539):   "errors": [
W/ApiaryClient( 6539):    {
W/ApiaryClient( 6539):     "domain": "global",
W/ApiaryClient( 6539):     "reason": "required",
W/ApiaryClient( 6539):     "message": "Login Required",
W/ApiaryClient( 6539):     "locationType": "header",
W/ApiaryClient( 6539):     "location": "Authorization"
,W/ApiaryClient( 6539):    }
W/ApiaryClient( 6539):   ],
W/ApiaryClient( 6539):   "code": 401,
W/ApiaryClient( 6539):   "message": "Login Required"
W/ApiaryClient( 6539):  }
W/ApiaryClient( 6539): }
,W/ApiaryClient( 6539): errCount = 1: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6539): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-427591857351604557&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6539): Headers:
W/ApiaryClient( 6539): accept-encoding: [gzip]
W/ApiaryClient( 6539): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6539): gdata-version: 2
V/GLSActivity( 2057): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2057): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2057): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2057): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 2057): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2057): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1031): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1031): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1031): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1031): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1031): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1412): onNotificationPosted
,D/SmartCoverUpdateMonitor( 1412): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1412): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1412): handleNotificationPosted(true)
D/QuickCircle( 1412): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1412): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1412): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1412): post do just update job
D/LgeQuickCoverNotificationData( 1412): showAll3
D/LgeQuickCoverNotificationData( 1412): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1412): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1412): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1412): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1412): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1412): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1412): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1412): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1412): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1412): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1412): updateNotificationData: count=3
W/GLSActivity( 2057): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2057): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2057): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2057): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2057): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2057): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2057): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 6539): Authentication error
E/BooksAccountManager( 6539): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6539): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6539): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6539): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6539): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6539): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6539): null auth token
D/QuickStatusbarLayout( 1412): Notification difference=198
D/QuickStatusbarLayout( 1412): child = android.widget.LinearLayout{20ebe075 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
W/ApiaryClient( 6539): Error response from books API: {
W/ApiaryClient( 6539):  "error": {
W/ApiaryClient( 6539):   "errors": [
W/ApiaryClient( 6539):    {
W/ApiaryClient( 6539):     "domain": "global",
W/ApiaryClient( 6539):     "reason": "required",
W/ApiaryClient( 6539):     "message": "Login Required",
W/ApiaryClient( 6539):     "locationType": "header",
W/ApiaryClient( 6539):     "location": "Authorization"
W/ApiaryClient( 6539):    }
W/ApiaryClient( 6539):   ],
W/ApiaryClient( 6539):   "code": 401,
W/ApiaryClient( 6539):   "message": "Login Required"
W/ApiaryClient( 6539):  }
W/ApiaryClient( 6539): }
,W/ApiaryClient( 6539): errCount = 2: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6539): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-427591857351604557&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6539): Headers:
W/ApiaryClient( 6539): accept-encoding: [gzip]
W/ApiaryClient( 6539): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6539): gdata-version: 2
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=1.0, 0.0, 0.0  rx=0.5 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1900703603] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=1.0, 0.0, 0.0  rx=0.5 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-1900703593] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
V/GLSActivity( 2057): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2057): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2057): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2057): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2057): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2057): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1031): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1031): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1031): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1031): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1031): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1412): onNotificationPosted
,D/SmartCoverUpdateMonitor( 1412): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1412): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1412): handleNotificationPosted(true)
D/QuickCircle( 1412): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1412): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1412): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1412): post do just update job
D/LgeQuickCoverNotificationData( 1412): showAll3
D/LgeQuickCoverNotificationData( 1412): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1412): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1412): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1412): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1412): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1412): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1412): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1412): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1412): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1412): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1412): updateNotificationData: count=3
W/GLSActivity( 2057): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2057): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2057): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2057): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2057): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2057): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2057): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 6539): Authentication error
E/BooksAccountManager( 6539): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6539): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6539): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6539): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6539): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6539): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6539): null auth token
D/QuickStatusbarLayout( 1412): Notification difference=198
D/QuickStatusbarLayout( 1412): child = android.widget.LinearLayout{20ebe075 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,W/ApiaryClient( 6539): Error response from books API: {
W/ApiaryClient( 6539):  "error": {
W/ApiaryClient( 6539):   "errors": [
W/ApiaryClient( 6539):    {
W/ApiaryClient( 6539):     "domain": "global",
W/ApiaryClient( 6539):     "reason": "required",
W/ApiaryClient( 6539):     "message": "Login Required",
W/ApiaryClient( 6539):     "locationType": "header",
W/ApiaryClient( 6539):     "location": "Authorization"
W/ApiaryClient( 6539):    }
W/ApiaryClient( 6539):   ],
W/ApiaryClient( 6539):   "code": 401,
W/ApiaryClient( 6539):   "message": "Login Required"
W/ApiaryClient( 6539):  }
W/ApiaryClient( 6539): }
,W/ApiaryClient( 6539): errCount = 3: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6539): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-427591857351604557&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6539): Headers:
W/ApiaryClient( 6539): accept-encoding: [gzip]
W/ApiaryClient( 6539): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6539): gdata-version: 2
E/BooksSync( 6539): Soft error: 
E/BooksSync( 6539): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 6539): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-427591857351604557&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 6539): Headers:
E/BooksSync( 6539): accept-encoding: [gzip]
E/BooksSync( 6539): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 6539): gdata-version: 2
E/BooksSync( 6539): 
E/BooksSync( 6539): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 6539): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 6539): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 6539): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 6539): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 6539): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 6539): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 6539): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 6539): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 6539): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 6539): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 6539): {
E/BooksSync( 6539):  "error": {
E/BooksSync( 6539):   "errors": [
E/BooksSync( 6539):    {
E/BooksSync( 6539):     "domain": "global",
E/BooksSync( 6539):     "reason": "required",
E/BooksSync( 6539):     "message": "Login Required",
E/BooksSync( 6539):     "locationType": "header",
E/BooksSync( 6539):     "location": "Authorization"
E/BooksSync( 6539):    }
E/BooksSync( 6539):   ],
E/BooksSync( 6539):   "code": 401,
E/BooksSync( 6539):   "message": "Login Required"
E/BooksSync( 6539):  }
E/BooksSync( 6539): }
E/BooksSync( 6539): 
E/BooksSync( 6539): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 6539): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 6539): 	... 8 more
,E/BooksSync( 6539): Sync error
E/BooksSync( 6539): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 6539): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-427591857351604557&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 6539): Headers:
E/BooksSync( 6539): accept-encoding: [gzip]
E/BooksSync( 6539): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 6539): gdata-version: 2
E/BooksSync( 6539): 
E/BooksSync( 6539): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 6539): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 6539): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 6539): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 6539): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 6539): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 6539): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 6539): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 6539): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 6539): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 6539): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 6539): {
E/BooksSync( 6539):  "error": {
E/BooksSync( 6539):   "errors": [
E/BooksSync( 6539):    {
E/BooksSync( 6539):     "domain": "global",
E/BooksSync( 6539):     "reason": "required",
E/BooksSync( 6539):     "message": "Login Required",
E/BooksSync( 6539):     "locationType": "header",
E/BooksSync( 6539):     "location": "Authorization"
E/BooksSync( 6539):    }
E/BooksSync( 6539):   ],
E/BooksSync( 6539):   "code": 401,
E/BooksSync( 6539):   "message": "Login Required"
E/BooksSync( 6539):  }
E/BooksSync( 6539): }
E/BooksSync( 6539): 
E/BooksSync( 6539): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 6539): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 6539): 	... 8 more
I/BooksSync( 6539): Finished books sync
D/SyncManager( 1031): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 1294003, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=7.5, 0.0, 0.0  rx=5.3 bcn=0 [on:0 tx:0 rx:0 period:3000] from screen [on:0 period:-1900700582] gl rssi=-57 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=7.5, 0.0, 0.0  rx=5.3 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-1900700581] gl rssi=-57 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,D/sensors_hal_Time( 1031): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1031): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1031): tsOffsetIs: Apps: 1300420678415; DSPS: 42752854; Offset : -4305802970
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=5.8, 0.0, 0.0  rx=3.6 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1900697562] gl rssi=-57 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=5.8, 0.0, 0.0  rx=3.6 bcn=0 [on:0 tx:0 rx:0 period:4] from screen [on:0 period:-1900697558] gl rssi=-57 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=2.9, 0.0, 0.0  rx=1.8 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1900694534] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=2.9, 0.0, 0.0  rx=1.8 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1900694531] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,I/[SystemUI]TimeTickManager( 1468): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1468): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1468): called onTimeUpdated()
I/[SystemUI]Clock( 1468): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1468): called onTimeUpdated()
I/[SystemUI]DateView( 1468): called onTimeUpdated()
I/[SystemUI]DateView( 1468): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1468): handleTimeUpdate
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=1.9, 0.0, 0.0  rx=0.9 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1900691505] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=1.9, 0.0, 0.0  rx=0.9 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1900691502] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=1.0, 0.0, 0.0  rx=0.5 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1900688475] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=1.0, 0.0, 0.0  rx=0.5 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1900688472] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=1.0, 0.0, 0.0  rx=0.2 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:-1900685444] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=1.0, 0.0, 0.0  rx=0.2 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1900685441] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1900682416] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1900682413] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=1.2, 0.0, 0.0  rx=0.6 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1900679389] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=1.2, 0.0, 0.0  rx=0.6 bcn=0 [on:0 tx:0 rx:0 period:9] from screen [on:0 period:-1900679380] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
D/sensors_hal_Time( 1031): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1031): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1031): tsOffsetIs: Apps: 1320422347262; DSPS: 43408268; Offset : -4305781708
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=0.6, 0.0, 0.0  rx=0.3 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1900676359] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=0.6, 0.0, 0.0  rx=0.3 bcn=0 [on:0 tx:0 rx:0 period:9] from screen [on:0 period:-1900676350] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
D/PowerManagerServiceEx( 1031): acquireWakeLockInternal: lock=398724214, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1031
,V/AlarmManager( 1031): ELAPSED_WAKEUP set : Alarm{24e32e77 type 2 when 1324371 android} when 1324371
D/[Concierge]Service( 2617): onStartCommand(). Type : 9
,D/PowerManagerServiceEx( 1031): releaseWakeLockInternal: lock=398724214 [*alarm*], flags=0x0
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=0.3, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1900673330] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=0.3, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-1900673320] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:-1900670306] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1900670303] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=0.3, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:2999] from screen [on:0 period:-1900667270] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=0.3, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-1900667260] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=0.2, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1900664239] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=0.2, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-1900664229] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1900661208] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:5] from screen [on:0 period:-1900661203] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,D/sensors_hal_Time( 1031): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1031): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1031): tsOffsetIs: Apps: 1340424144025; DSPS: 44063687; Offset : -4305785874
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1900658178] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-1900658168] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=1.0, 0.0, 0.0  rx=0.5 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1900655146] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=1.0, 0.0, 0.0  rx=0.5 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1900655143] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.3 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1900652118] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.3 bcn=0 [on:0 tx:0 rx:0 period:9] from screen [on:0 period:-1900652109] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=0.3, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1900649087] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=0.3, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:4] from screen [on:0 period:-1900649083] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1900646056] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1900646053] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3000] from screen [on:0 period:-1900643030] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:9] from screen [on:0 period:-1900643021] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1900640002] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1900639999] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,D/sensors_hal_Time( 1031): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1031): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1031): tsOffsetIs: Apps: 1360425789902; DSPS: 44719101; Offset : -4305787893
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1900636973] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1900636970] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=0.3, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1900633945] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=0.3, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1900633942] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,I/[SystemUI]TimeTickManager( 1468): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1468): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1468): called onTimeUpdated()
I/[SystemUI]Clock( 1468): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1468): called onTimeUpdated()
I/[SystemUI]DateView( 1468): called onTimeUpdated()
I/[SystemUI]DateView( 1468): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1468): handleTimeUpdate
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3000] from screen [on:0 period:-1900630917] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:4] from screen [on:0 period:-1900630913] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=1.1, 0.0, 0.0  rx=0.5 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1900627889] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=1.1, 0.0, 0.0  rx=0.5 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-1900627879] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.3 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1900624859] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.3 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-1900624849] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=0.3, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1900621828] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=0.3, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:9] from screen [on:0 period:-1900621819] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
D/sensors_hal_Time( 1031): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1031): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1031): tsOffsetIs: Apps: 1380427492967; DSPS: 45374517; Offset : -4305793786
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1900618799] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:9] from screen [on:0 period:-1900618790] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1900615769] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:9] from screen [on:0 period:-1900615760] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1900612739] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:9] from screen [on:0 period:-1900612730] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1900609711] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1900609708] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,I/[SystemUI]LGPowerUI( 1468): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1468): On Skip Timer : true
,D/WifiController( 1031): battery changed pluggedType: 2
,D/LEDHandler( 1928): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1928): Battery Level Remaining: 100%
D/LEDHandler( 1928): Battery Temp: 278, mChargingStatus=5, mChargingStop=false
D/KeyguardUpdateMonitor( 1468): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 278
I/[SystemUI]LGPowerUI( 1468): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings( 1031): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1031): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/HeadsetStateMachine( 6188): Disconnected process message: 10, size: 0
I/[SystemUI]BatterySaverHandler( 1468): onReceive = android.intent.action.BATTERY_CHANGED
D/LGDMClient( 3943): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.intent.action.BATTERY_CHANGED
D/LGDMClient( 3943): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1900606680] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-1900606670] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=1.0, 0.0, 0.0  rx=0.5 bcn=0 [on:0 tx:0 rx:0 period:3000] from screen [on:0 period:-1900603650] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=1.0, 0.0, 0.0  rx=0.5 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-1900603640] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.3 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1900600620] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.3 bcn=0 [on:0 tx:0 rx:0 period:9] from screen [on:0 period:-1900600611] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
D/sensors_hal_Time( 1031): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1031): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1031): tsOffsetIs: Apps: 1400429030564; DSPS: 46029927; Offset : -4305782250
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=0.3, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3005] from screen [on:0 period:-1900597586] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=0.3, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1900597583] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:-1900594554] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1900594551] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1900591525] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1900591522] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1900588497] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1900588494] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3005] from screen [on:0 period:-1900585462] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1900585459] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1900582433] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1900582430] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=1.0, 0.0, 0.0  rx=0.5 bcn=0 [on:0 tx:0 rx:0 period:3009] from screen [on:0 period:-1900579396] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=1.0, 0.0, 0.0  rx=0.5 bcn=0 [on:0 tx:0 rx:0 period:11] from screen [on:0 period:-1900579385] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
D/sensors_hal_Time( 1031): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1031): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1031): tsOffsetIs: Apps: 1420431841130; DSPS: 46685380; Offset : -4305809741
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.3 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1900576370] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.3 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1900576367] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=0.3, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3000] from screen [on:0 period:-1900573343] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=0.3, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1900573340] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,I/[SystemUI]TimeTickManager( 1468): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1468): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1468): called onTimeUpdated()
I/[SystemUI]Clock( 1468): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1468): called onTimeUpdated()
I/[SystemUI]DateView( 1468): called onTimeUpdated()
I/[SystemUI]DateView( 1468): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1468): handleTimeUpdate
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1900570314] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:4] from screen [on:0 period:-1900570310] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,I/wpa_supplicant( 6231): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=0
,D/WifiMonitor( 1031): Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=0]
E/WifiMonitor( 1031): WifiMonitor:wlan0 cnt=20 dispatchEvent: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=0
E/WifiMonitor( 1031): handleEvent 2  CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=0
D/WifiMonitor( 1031): handleNetworkStateChange: Could not parse disconnect string
E/WifiMonitor( 1031): WifiMonitor notify network disconnect: null reason=0
,D/Tethering( 1031): InitialState.processMessage what=4
D/Tethering( 1031): sendTetherStateChangedBroadcast 0, 0, 0
,E/WifiStateMachine( 1031):  ConnectedState NETWORK_DISCONNECTION_EVENT nid=0 reason=0 lastbssid=c0:ff:d4:d3:aa:48 freq=2412 rssi=-57 rt=1429998
E/WifiStateMachine( 1031):  L2ConnectedState NETWORK_DISCONNECTION_EVENT nid=0 reason=0 lastbssid=c0:ff:d4:d3:aa:48 freq=2412 rssi=-57 rt=1429998
E/WifiStateMachine( 1031):  ConnectModeState NETWORK_DISCONNECTION_EVENT nid=0 reason=0 lastbssid=c0:ff:d4:d3:aa:48 freq=2412 rssi=-57 rt=1429999
E/WifiConfigStore( 1031): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/WifiNative-wlan0( 1031): doBoolean: SET_NETWORK 0 bssid any
,D/WifiMonitor( 1031): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1031): WifiMonitor:wlan0 cnt=21 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/WifiNative-wlan0( 1031): SET_NETWORK 0 bssid any: returned true
D/WifiNative-wlan0( 1031): doBoolean: SAVE_CONFIG
D/WifiNative-wlan0( 1031): SAVE_CONFIG: returned true
D/WifiNative-wlan0( 1031): doBoolean: DRIVER BTCOEXMODE 2
D/LGWifiP2pService( 1031): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1031): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 6231): wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
D/WifiNative-wlan0( 1031): DRIVER BTCOEXMODE 2: returned true
D/WifiNative-wlan0( 1031): doBoolean: SET ps 1
D/WifiNative-wlan0( 1031): SET ps 1: returned true
D/CommandListener(  335): Clearing all IP addresses on wlan0
,D/DhcpStateMachine( 1031): RunningState{ when=-8ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiMonitor( 1031): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
E/WifiMonitor( 1031): WifiMonitor:wlan0 cnt=22 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
,V/NativeCrypto( 2057): Read error: ssl=0xaf459a00: I/O error during system call, Connection timed out
,V/NativeCrypto( 2057): SSL shutdown failed: ssl=0xaf459a00: I/O error during system call, Broken pipe
I/jxcore-log( 6098): Toggling radios to false
I/jxcore-log( 6098): 
,I/ActivityManager( 1031): Start proc com.android.settings for broadcast com.android.settings/.deviceinfo.UsbSettingsReceiver: pid=7649 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,I/wpa_supplicant( 6231): wlan0: CTRL-EVENT-SCAN-STARTED 
D/BluetoothManagerService( 1031): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1031): disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@13ed3ae4 mBinding = false
,E/WifiStateMachine( 1031): WifiStateMachine: Leaving Connected state
D/ConnectivityService( 1031): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
D/ConnectivityService( 1031): ignoring duplicate network state non-change
D/ConnectivityService( 1031): NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 2
D/WifiHS20( 1031): hidePasspointNotification off =false
W/Settings( 1031): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1031): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1031): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
D/WifiHS20( 1031): hidePasspointNotification off =false
,W/Settings( 1031): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1031): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/art     (  360): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 452us total 45.873ms
D/WifiOffDelayIfNotUsed( 1031): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
I/StatusBar.NetworkController( 1468): networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1468): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1468): refreshViews: Data not connected!! Set no data type icon / Roaming
I/StatusBar.NetworkController( 1468): networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1468): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1468): refreshViews: Data not connected!! Set no data type icon / Roaming
V/WfdStateTracker( 1928): handleWifiStateChangedEvent: 0
D/WifiMonitor( 1031): Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1031): WifiMonitor:wlan0 cnt=23 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1031): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1031): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
E/WifiStateMachine( 1031):  DisconnectedState CMD_TETHER_STATE_CHANGE 0 0
,E/WifiStateMachine( 1031):  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1031):  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1031):  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1031):  DefaultState CMD_TETHER_STATE_CHANGE 0 0
I/art     (  360): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 430us total 20.581ms
D/LocationManagerService( 1031): getAllProviders()=[passive, gps, network]
D/Ulp_jni ( 1031): JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 1,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
D/Ulp_jni ( 1031): JNI:system_update. Event-4
D/BluetoothManagerService( 1031): Message: 2
D/BluetoothManagerService( 1031): Sending off request.
D/LGBluetoothServiceAdapter( 6188): [BTUI] Precleanup
D/BluetoothAdapterState( 6188): CURRENT_STATE=ON, MESSAGE = USER_TURN_OFF
D/BluetoothAdapterProperties( 6188): Setting state to 13
I/BluetoothAdapterState( 6188): Bluetooth adapter state changed: 12-> 13
D/BluetoothAdapterProperties( 6188): onBluetoothDisable()
I/BluetoothAdapterState( 6188): Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
D/BluetoothAdapterProperties( 6188): Scan Mode:20
D/BluetoothAdapterState( 6188): CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
D/btif_config_util( 6188): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
V/BluetoothMapMasInstance( 6188): Accept exception: (expected at shutdown)
V/BluetoothMapMasInstance( 6188): java.io.IOException: read failed, socket might closed or timeout, read ret: -1
V/BluetoothMapMasInstance( 6188): 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:586)
V/BluetoothMapMasInstance( 6188): 	at android.bluetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:563)
V/BluetoothMapMasInstance( 6188): 	at android.bluetooth.BluetoothSocket.accept(BluetoothSocket.java:418)
V/BluetoothMapMasInstance( 6188): 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:130)
V/BluetoothMapMasInstance( 6188): 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:116)
V/BluetoothMapMasInstance( 6188): 	at com.android.bluetooth.map.BluetoothMapMasInstance$SocketAcceptThread.run(BluetoothMapMasInstance.java:133)
,E/BtOppRfcommListener( 6188): Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
V/BluetoothFtpService:RfcommSocketAcceptThread( 6188): Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
V/BluetoothSapService( 6188): Accept thread exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
V/BluetoothPbapService( 6188): Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
W/bt-l2cap( 6188): L2CAP - L2CA_Deregister() called for PSM: 0x000f
W/bt-btif ( 6188): bta_dm_disable BTA_DISABLE_DELAY set to 1000 ms
W/bt-l2cap( 6188): L2CAP - L2CA_Deregister() called for PSM: 0x0019
W/bt-l2cap( 6188): L2CAP - L2CA_Deregister() called for PSM: 0x0017
W/bt-l2cap( 6188): L2CAP - L2CA_Deregister() called for PSM: 0x001b
W/bt-l2cap( 6188): L2CAP - L2CA_Deregister() called for PSM: 0x0019
W/bt-l2cap( 6188): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 6188): L2CAP - L2CA_Deregister() called for PSM: 0x0017
W/bt-l2cap( 6188): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-l2cap( 6188): L2CAP - L2CA_Deregister() called for PSM: 0x001b
W/bt-l2cap( 6188): L2CAP - PSM: 0x001b not found for deregistration
W/bt-l2cap( 6188): L2CAP - L2CA_Deregister() called for PSM: 0x0011
W/bt-l2cap( 6188): L2CAP - L2CA_Deregister() called for PSM: 0x0013
E/bt-btif ( 6188): bta_gattc_deregister Deregister Failedm unknown client cif
D/BluetoothManagerService( 1031): Message: 60
D/BluetoothManagerService( 1031): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 12, newState=13
D/BluetoothManagerService( 1031): Bluetooth State Change Intent: 12 -> 13
D/LGBluetoothAPIService( 1928): [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
I/art     (  360): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 402us total 20.791ms
,I/BluetoothMapService( 6188): onReceive: android.bluetooth.adapter.action.STATE_CHANGED
D/BluetoothMapService( 6188): STATE_TURNING_OFF
V/BluetoothMapService( 6188): Handler(): got msg=4
,D/BluetoothMapService( 6188): MAP Service closeService in
D/BluetoothMapMasInstance( 6188): MAP Service shutdown
D/LGBluetoothMapAdapter( 6188): [BTUI] LGBluetoothMapAdapter cleanup
V/BluetoothMapService( 6188): MAP Service closeService out
V/BtOppService( 6188): Receiver DISABLED_ACTION 
I/BtOppRfcommListener( 6188): stopping Accept Thread
V/BtOppRfcommListener( 6188): close mBtServerSocket
V/BtOppRfcommListener( 6188): waiting for thread to terminate
I/BtOppRfcommListener( 6188): BluetoothSocket listen thread finished
V/BtOppRfcommListener( 6188): done waiting for thread to terminate
V/BtOppService( 6188): onDestroy
D/LGBluetoothOppAdapter( 6188): [BTUI] LGBluetoothOppAdapter cleanup
D/WifiServiceImplEx( 1031): setWifiEnabled: false pid=6098, uid=10311, package= com.test.thalitest, App Lable : ThaliTest
D/WifiService( 1031): setWifiEnabled: false pid=6098, uid=10311
E/WifiService( 1031): Invoking mWifiStateMachine.setWifiEnabled
I/[SystemUI]BluetoothHandler( 1468): Receive : BluetoothAdapter.ACTION_STATE_CHANGED
E/WifiStateMachine( 1031):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 21 0 rt=1430175  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: DISCONNECTED
E/WifiStateMachine( 1031):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 21 0 rt=1430209  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: DISCONNECTED
E/WifiStateMachine( 1031):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 22 0 rt=1430210  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
,D/WifiHS20( 1031): hidePasspointNotification off =false
W/Settings( 1031): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1031): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1031): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
D/LocationManagerService( 1031): getAllProviders()=[passive, gps, network]
D/Ulp_jni ( 1031): JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
D/Ulp_jni ( 1031): JNI:system_update. Event-4
D/ConnectivityService( 1031): reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10005
I/jxcore-log( 6098): Radios toggled
I/jxcore-log( 6098): 
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1031): ValidatedState{ when=-1ms what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1031): DefaultState{ when=-1ms what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1031): Forcing reevaluation
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1031): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1031): Checking http://clients3.google.com/generate_204 on <unknown ssid>
E/WifiStateMachine( 1031):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 22 0 rt=1430230  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
D/ConnectivityService( 1031): Default network via Wi-Fi disconnect. stop DSQN
E/WifiStateMachine( 1031):  DisconnectedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1031):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
,E/WifiStateMachine( 1031):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1031):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
W/Settings( 1031): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
E/WifiStateMachine( 1031):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
W/Settings( 1031): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1031): NETWORK_STATE_CHANGED_ACTION [SCANNING]
E/WifiStateMachine( 1031):  DisconnectedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1031):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1031):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
D/DSQN    ( 1031): disableDataServiceNotify
D/DSQN    ( 1031): stop dsqn bin
E/WifiStateMachine( 1031):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1031):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
D/WifiNetworkAgent( 1031): NetworkAgent: NetworkAgent channel lost
D/WifiServerServiceExt( 1031): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1031): setSupplicantStateDISCONNECTED
E/WifiStateMachine( 1031):  DisconnectedState CMD_STOP_SUPPLICANT 0 0
E/WifiStateMachine( 1031):  ConnectModeState CMD_STOP_SUPPLICANT 0 0
E/WifiStateMachine( 1031):  DriverStartedState CMD_STOP_SUPPLICANT 0 0
E/WifiStateMachine( 1031):  SupplicantStartedState CMD_STOP_SUPPLICANT 0 0
D/libc-netbsd(  335): default dns: query_ipv6=0, query_ipv4=0
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1031): Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
D/DSQN    ( 1031): DNSproblemNotiEnabled is disabled ignore DNS fail CB
D/LGWifiP2pService( 1031): InactiveState{ when=0 what=131204 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1031): P2pEnabledState{ when=0 what=131204 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiScanningService( 1031): SCAN_AVAILABLE : 1
D/WifiMonitor( 1031): stopMonitoring(p2p0) = com.android.server.wifi.p2p.LGWifiP2pServiceImpl$P2pStateMachine@1d5ef468
D/RttService( 1031): SCAN_AVAILABLE : 1
D/WifiScanningService( 1031): DefaultState got{ when=-1ms what=160007 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1031): P2pDisablingState
D/RttService( 1031): EnabledState got{ when=-1ms what=160513 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1031): P2pDisablingState{ when=-1ms what=147458 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1031): p2p socket connection lost
D/LGWifiP2pService( 1031): P2pDisabledState
D/WifiServerServiceExt( 1031): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1031): setSupplicantStateSCANNING
V/WfdStateTracker( 1928): WfdStateTracker handleDirectStateChangedEvent: 0
D/WfdsService( 1928): WifiP2pState is changed : false
D/WfdsService( 1928): WfdsEnabledState: Receive the WFDS_DISABLE message
D/WfdsService( 1928): Set the WFDS Monitor: false
E/WifiStateMachine( 1031):  WaitForP2pDisableState CMD_DISABLE_P2P_RSP uid=1000 0 0
D/WfdsMonitor( 1928): WFDS Monitor is stopped
D/WfdsService( 1928): STATE : WfdsDisabledState - enter
W/WfdsSession:Controller( 1928): DefaultState - msg [9441355] is not handled
D/CtrlSupplicant( 1928): Received on exit socket, terminate
E/CtrlSupplicant( 1928): wfds_wait_for_event: buf = CTRL-EVENT-TERMINATING  - connection closed
D/LGWifiP2pService( 1031): P2pDisabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WfdsMonitor( 1928): Event [CTRL-EVENT-TERMINATING  - connection closed]
D/LGWifiP2pService( 1031): DefaultState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WfdsMonitor( 1928): WfdsMonitorThread is received the interrupt - closing,
D/WifiNative-wlan0( 1031): doBoolean: DRIVER BTCOEXMODE 2
I/wpa_supplicant( 6231): wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
D/WifiNative-wlan0( 1031): DRIVER BTCOEXMODE 2: returned true
D/WifiNative-wlan0( 1031): doBoolean: SET ps 1
W/WfdsService( 1928): DefaultState - msg [9445378] is not handled
D/WifiNative-wlan0( 1031): SET ps 1: returned true
D/CommandListener(  335): Clearing all IP addresses on wlan0
D/WifiHS20( 1031): hidePasspointNotification off =false
W/Settings( 1031): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1031): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1031): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
D/WifiNative-p2p0( 1031): doBoolean: TERMINATE
D/WifiNative-p2p0( 1031): TERMINATE: returned true
E/WifiStateMachine( 1031): Couldn't get getWiFiOffloadingIface : 
E/WifiStateMachine( 1031): useWiFiOffloading() : false
E/WifiStateMachine( 1031): CONFIG_LGE_WLAN_PATH : true
D/WifiHS20( 1031): hidePasspointNotification off =false
W/Settings( 1031): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1031): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1031): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
V/WfdStateTracker( 1928): WfdStateTracker handleDirectStateChangedEvent: 6
I/WifiServerServiceExt( 1031): WIFI_STATE_CHANGED_ACTION [0]
I/StatusBar.NetworkController( 1468): networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1468): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1468): refreshViews: Data not connected!! Set no data type icon / Roaming
W/ResourcesManager( 7649): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7649): Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
I/StatusBar.NetworkController( 1468): networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1468): mWifiConnected = false, mWifiLevel = 0
W/ResourcesManager( 7649): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 7649): Asset path '/system/framework/com.lge.bluetooth.jar' does not exist or contains no resources.
W/ResourcesManager( 7649): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
D/StatusBar.NetworkController( 1468): refreshViews: Data not connected!! Set no data type icon / Roaming
W/ResourcesManager( 7649): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
I/StatusBar.NetworkController( 1468): networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1468): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1468): refreshViews: Data not connected!! Set no data type icon / Roaming
I/StatusBar.NetworkController( 1468): networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1468): mWifiConnected = false, mWifiLevel = 0
D/ConnectivityService( 1031): notifyType LOST for NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService( 1031):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1031):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/StatusBar.NetworkController( 1468): refreshViews: Data not connected!! Set no data type icon / Roaming
D/ConnectivityService( 1031): sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
D/Nat464Xlat( 1031): requiresClat: netType=1, connected=false, hasIPv4Address=true, hasInternetCapability=true
D/ConnectivityManager.CallbackHandler( 1468): CM callback handler got msg 524292
D/CSLegacyTypeTracker( 1031): [lge_data] remove agent NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::c69a:2ff:fe7b:60ac/64,192.168.1.141/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} } list []  wasFirstNetwork :true
D/CSLegacyTypeTracker( 1031): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
D/ConnectivityService( 1031): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/StatusBar.NetworkController( 1468): refreshViews: Data not connected!! Set no data type icon / Roaming
D/ConnectivityService( 1031): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService( 1031): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService( 1031): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService( 1031): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1031): sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/NetworkManagementService( 1031): Removing idletimer
D/TelephonyNetworkFactory-1( 1838): new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
W/Settings( 1031): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/TelephonyNetworkFactory-1( 1838):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
D/ConnectivityService( 1031): requestNetworkTransitionWakelock: wakelock - ignore in airplane mode
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1031): EvaluatingState{ when=-2ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1031): DefaultState{ when=-2ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1031): Disconnected - quitting
D/WIFI    ( 1031): new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    ( 1031):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
V/NetworkPolicy( 1031): [LG_RESTRICTED] !!!isConnected  type  :1
V/NetworkPolicy( 1031): [LG_RESTRICTED] !!!isConnected  type  :1
D/LocSvc_java( 1031): Sending msg: 4 arg1:0 arg2:1
D/LocSvc_java( 1031): Sending msg: 4 arg1:0 arg2:1
D/LocSvc_java( 1031): getAGpsConnectionInfo connType - 4
D/LocSvc_java( 1031): updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java( 1031): ignore wifi update if we are not in OPENING or CLOSING
D/LocSvc_java( 1031): getAGpsConnectionInfo connType - 4
D/LocSvc_java( 1031): updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java( 1031): ignore wifi update if we are not in OPENING or CLOSING
,D/TelephonyIcons( 1468): null signal icon name: drawable/stat_sys_signal_null
D/StatusBar.NetworkController( 1468): refreshViews: Data not connected!! Set no data type icon / Roaming
D/StatusBar.NetworkController( 1468): refreshViews: Data not connected!! Set no data type icon / Roaming
D/TelephonyIcons( 1468): null signal icon name: drawable/stat_sys_signal_null
D/StatusBar.NetworkController( 1468): refreshViews: Data not connected!! Set no data type icon / Roaming
D/StatusBar.NetworkController( 1468): refreshViews: Data not connected!! Set no data type icon / Roaming
,W/ContextImpl( 7649): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
,V/BluetoothPbapReceiver( 6188): PbapReceiver onReceive 
D/UsbSettingsReceiver( 7649): [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
V/BluetoothPbapReceiver( 6188): ***********action = android.bluetooth.adapter.action.STATE_CHANGED
D/UsbSettingsReceiver( 7649): [AUTORUN] sys.usb.config = ptp_only,adb
V/BluetoothPbapReceiver( 6188): ***********state = 13
D/UsbSettingsReceiver( 7649): [AUTORUN] sys.usb.state = ptp_only,adb
D/UsbSettingsReceiver( 7649): [AUTORUN] persist.sys.usb.config = ptp_only,adb
D/UsbSettingsReceiver( 7649): [AUTORUN] onReceive() : app userid = 0, current userid = 0
V/BluetoothPbapReceiver( 6188): ***********Calling start service!!!! with action = null
V/BluetoothPbapService( 6188): action: android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothPbapService( 6188): state: 13
V/BluetoothPbapService( 6188): Pbap Service closeService in
I/ActivityManager( 1031): Start proc com.lge.lifetracker for broadcast com.lge.lifetracker/.receiver.HealthDeviceReceiver: pid=7693 uid=10037 gids={50037, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
,V/BluetoothPbapService( 6188): successfully stopped pbap service
V/BluetoothPbapService( 6188): Pbap Service closeService out
V/BluetoothPbapService( 6188): Pbap Service onDestroy
V/BluetoothPbapService( 6188): Pbap Service closeService in
V/BluetoothPbapService( 6188): Pbap Service closeService out
D/LGBluetoothPbapAdapter( 6188): [BTUI] cleanup
D/UsbSettingsControl( 7649): [AUTORUN] getUsbConnected() : connected=true
D/UsbSettingsReceiver( 7649): [AUTORUN] onReceive() : availableList=[]
D/UsbSettingsReceiver( 7649): [AUTORUN] onReceive() : activeList=[]
D/UsbSettingsReceiver( 7649): [AUTORUN] onReceive() : errorList=[]
D/UsbSettingsControl( 7649): [AUTORUN] isAutorunTimer() : mAutorunChanging=false
D/UsbSettingsControl( 7649): [AUTORUN] setTetherStatus() : status=false
D/BluetoothManagerService( 1031): Message: 20
D/BluetoothManagerService( 1031): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@32b52150:true
,D/DhcpStateMachine( 1031): StoppedState
D/DhcpStateMachine( 1031): StoppedState{ when=-182ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
,I/ActivityManager( 1031): Start proc com.wsandroid.suite.lge for broadcast com.wsandroid.suite.lge/com.wavesecure.core.WSAndroidSystemIntentReceiver: pid=7712 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,E/WifiStateMachine( 1031):  SupplicantStoppingState CMD_ON_QUIT 0 0
E/WifiStateMachine( 1031):  DefaultState CMD_ON_QUIT 0 0
D/BluetoothManagerService( 1031): Message: 30
D/BluetoothManagerService( 1031): Message: 30
,D/LocalBluetoothProfileManager( 7649): Adding local MAP profile
D/BluetoothMap( 7649): Create BluetoothMap proxy object
D/BluetoothManagerService( 1031): Message: 30
D/BluetoothManagerService( 1031): Message: 30
D/LocalBluetoothProfileManager( 7649): LocalBluetoothProfileManager construction complete
D/LGBluetoothFeatureConfig( 7649):  get() - isFeatureLoaded : false
,D/LGBluetoothUserBindClient( 7649): [BTUI] initUserBindClient
,W/ResourcesManager( 7712): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ContextImpl( 7649): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.android.settings.bluetooth.LGBluetoothUserBindClient.initUserBindClient:90 com.android.settings.bluetooth.LGBluetoothUserBindClient.<init>:55 com.android.settings.bluetooth.LGBluetoothUserBindClient.getInstance:47 
D/DockEventReceiver( 7649): finishStartingService: stopping service
D/BluetoothInputDevice( 7649): Proxy object connected
,D/HidProfile( 7649): Bluetooth service connected
D/BluetoothPan( 7649): BluetoothPAN Proxy object connected
D/PanProfile( 7649): Bluetooth service connected
D/BluetoothMap( 7649): Proxy object connected
D/MapProfile( 7649): Bluetooth service connected
D/BluetoothMap( 7649): getConnectedDevices()
D/BluetoothMap( 7649): Bluetooth is Not enabled
D/LGBluetoothUserBindClient( 7649): [BTUI] onServiceConnected
I/ActivityManager( 1031): Killing 6853:com.android.calendar/u0a13 (adj 15): empty #17
D/PluginManager( 7712): init()
W/libprocessgroup( 1031): failed to open /acct/uid_10013/pid_6853/cgroup.procs: No such file or directory
,E/ActivityThread( 7693): Failed to find provider info for com.lge.lgaccount.provider
W/LG Account v2.2( 7693): No ProfileInfo entries
I/LG Account v2.2( 7693): isEnabled: false
I/Feature ( 7693): [Lifetracker]ver: 4.21.112(40211120)
,I/Feature ( 7693): [Lifetracker]Country: EU
I/Feature ( 7693): [Lifetracker]Operator: OPEN
I/Feature ( 7693): [Lifetracker]Ranking support: false
I/Feature ( 7693): [Lifetracker]Comfort support: false
I/Feature ( 7693): [Lifetracker]Accessory: true
I/Feature ( 7693): [Lifetracker]Health device: true
I/Feature ( 7693): [Lifetracker]Extra Pedometer: false
I/Feature ( 7693): [Lifetracker]Blood glucose device: false
I/Feature ( 7693): [Lifetracker]Device Number: 3
D/LGBluetoothAuthorization( 7649): [BTUI] cancel All Notification
,D/BluetoothPermissionRequest( 7649): onReceive
D/LGBluetoothAuthorization( 7649): [BTUI] cancel All Notification
,D/LGBluetoothResetSettingReceiver( 7649): return without doing reset settings.
I/ActivityManager( 1031): Killing 6690:com.lge.sizechangable.weather/u0a85 (adj 15): empty #17
,V/BluetoothOppReceiver( 6188): Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_TURNING_OFF
W/libprocessgroup( 1031): failed to open /acct/uid_10085/pid_6690/cgroup.procs: No such file or directory
D/BluetoothOppNotification( 6188): [BTUI] cancel opp incoming file confirm notification
D/BluetoothOppNotification( 6188): [BTUI] cancel opp active transfer file notification
,V/BluetoothFtpReceiver( 6188): BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
,V/BluetoothFtpReceiver( 6188): BluetoothFtpReceiver Start Service
V/BluetoothFtpService( 6188): Ftp Service onStartCommand
V/BluetoothFtpService( 6188): action: android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothFtpService( 6188): Ftp Service closeService
E/BluetoothFtpService:RfcommSocketAcceptThread( 6188): Shutdown
V/BluetoothFtpService( 6188): successfully stopped ftp service
V/BluetoothSapReceiver( 6188): [BTUI] checkServiceStart
V/BluetoothSapReceiver( 6188): [BTUI] region:EU country:EU
V/BluetoothSapReceiver( 6188): SapReceiver onReceive 
V/BluetoothSapReceiver( 6188): action = android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothSapReceiver( 6188):  Bluetooth Adapter state = 13
V/BluetoothSapReceiver( 6188): Calling SAP service start service with action = null
V/BluetoothFtpService( 6188): Ftp Service onDestroy
V/BluetoothFtpService( 6188): Ftp Service closeService
,I/ActivityManager( 1031): Start proc com.lge.settings.easy for broadcast com.lge.settings.easy/com.lge.settings.bluetooth.LGBluetoothProfileConnectionReceiver: pid=7738 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
V/BluetoothSapService( 6188): action: android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothSapService( 6188): state: 13
V/BluetoothSapService( 6188): Stopping SAP server process
,V/BluetoothSapService( 6188): Sap Service closeSapService in
V/BluetoothSapService( 6188): Close listen Socket : 
V/BluetoothSapService( 6188): Close rfcomm Socket : 
V/BluetoothSapService( 6188): Close sapd  Socket : 
V/BluetoothSapService( 6188): Sap Service closeSapService out
V/BluetoothSapService( 6188): Sap Service onDestroy
V/BluetoothSapService( 6188): Sap Service closeSapService in
V/BluetoothSapService( 6188): Close listen Socket : 
V/BluetoothSapService( 6188): Close rfcomm Socket : 
V/BluetoothSapService( 6188): Close sapd  Socket : 
V/BluetoothSapService( 6188): Sap Service closeSapService out
,W/ResourcesManager( 7738): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,I/ActivityManager( 1031): Killing 6883:com.google.android.talk/u0a72 (adj 15): empty #17
,D/AuthorizationBluetoothService( 2057): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,W/libprocessgroup( 1031): failed to open /acct/uid_10072/pid_6883/cgroup.procs: No such file or directory
,W/ExternalStrings( 7712): load override strings
W/ExternalStrings( 7712): java.lang.RuntimeException: Unexpected tag, got eat-comment
W/ExternalStrings( 7712): 	at com.mcafee.plugin.af.a(Unknown Source)
W/ExternalStrings( 7712): 	at com.mcafee.plugin.ac.b(Unknown Source)
W/ExternalStrings( 7712): 	at com.mcafee.plugin.ak.d(Unknown Source)
W/ExternalStrings( 7712): 	at com.mcafee.plugin.ak.a(Unknown Source)
W/ExternalStrings( 7712): 	at com.mcafee.app.s.getClassLoader(Unknown Source)
W/ExternalStrings( 7712): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5001)
W/ExternalStrings( 7712): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4609)
W/ExternalStrings( 7712): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4549)
W/ExternalStrings( 7712): 	at android.app.ActivityThread.access$1500(ActivityThread.java:148)
W/ExternalStrings( 7712): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1344)
W/ExternalStrings( 7712): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/ExternalStrings( 7712): 	at android.os.Looper.loop(Looper.java:135)
W/ExternalStrings( 7712): 	at android.app.ActivityThread.main(ActivityThread.java:5274)
W/ExternalStrings( 7712): 	at java.lang.reflect.Method.invoke(Native Method)
W/ExternalStrings( 7712): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/ExternalStrings( 7712): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
W/ExternalStrings( 7712): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
,D/StatusProvider( 7712): onCreate
V/Signer  ( 7712): override build config not found
D/Signer  ( 7712): value of property debug is false
,D/LGMDMWrapper( 7712): Found class 'com.mcafee.lgmdm.LGMDMWrapper$DataWipe'.
,D/LGMDMWrapper( 7712): Found class 'com.mcafee.lgmdm.LGMDMWrapper$DownloadMode'.
D/LGMDMWrapper( 7712): Found class 'com.mcafee.lgmdm.LGMDMWrapper$HardReset'.
,D/LGMDMWrapper( 7712): Found class 'com.mcafee.lgmdm.LGMDMWrapper$HardwareKeyReset'.
D/LGMDMWrapper( 7712): Found class 'com.mcafee.lgmdm.LGMDMWrapper$RemoveDeviceAdmin'.
D/LGMDMWrapper( 7712): Found class 'com.mcafee.lgmdm.LGMDMWrapper$UnknownSourceInstallation'.
D/LGMDMWrapper( 7712): Found class 'com.mcafee.lgmdm.LGMDMWrapper$Usb'.
D/LGMDMWrapper( 7712): Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbDebugging'.
D/LGMDMWrapper( 7712): Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbHostStorage'.
D/LGMDMWrapper( 7712): Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbMediaTransfer'.
D/LGMDMWrapper( 7712): Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbPictureTransfer'.
D/LGMDMWrapper( 7712): Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbStorage'.
D/LGMDMWrapper( 7712): Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbTethering'.
,D/bt_hci_bdroid( 6188): cleanup
I/bt_lpm  ( 6188): LPM is already off!!!
I/bt_userial_mct( 6188): exiting userial_read_thread
,D/bt_userial_mct( 6188): Leaving userial_evt_read_thread()
D/bt_userial_mct( 6188): userial_close_reader Joined userial reader thread: 0
I/bt_vendor( 6188): hw_epilog_process
W/bt-btif ( 6188): ag scb idx 1 not allocated
E/bt-btif ( 6188): BTA AG is already disabled, ignoring ...
W/bt-l2cap( 6188): L2CAP - L2CA_Deregister() called for PSM: 0x0019
W/bt-l2cap( 6188): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 6188): L2CAP - L2CA_Deregister() called for PSM: 0x0017
W/bt-l2cap( 6188): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-l2cap( 6188): L2CAP - L2CA_Deregister() called for PSM: 0x001b
W/bt-l2cap( 6188): L2CAP - PSM: 0x001b not found for deregistration
W/bt-l2cap( 6188): L2CAP - L2CA_Deregister() called for PSM: 0x0019
W/bt-l2cap( 6188): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 6188): L2CAP - L2CA_Deregister() called for PSM: 0x0017
W/bt-l2cap( 6188): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-l2cap( 6188): L2CAP - L2CA_Deregister() called for PSM: 0x001b
W/bt-l2cap( 6188): L2CAP - PSM: 0x001b not found for deregistration
W/bt-l2cap( 6188): L2CAP - L2CA_Deregister() called for PSM: 0x0019
W/bt-l2cap( 6188): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 6188): L2CAP - L2CA_Deregister() called for PSM: 0x0017
W/bt-l2cap( 6188): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-l2cap( 6188): L2CAP - L2CA_Deregister() called for PSM: 0x001b
W/bt-l2cap( 6188): L2CAP - PSM: 0x001b not found for deregistration
E/bt-btif ( 6188): bta_gattc_deregister Deregister Failedm unknown client cif
D/bt_hci_bdroid( 6188): cleanup Finalizing cleanup
D/bt_userial_mct( 6188): userial_close
E/bt_userial_mct( 6188): pthread_join() FAILED result:3
I/bt_vendor( 6188): bt-vendor : BT_VND_OP_USERIAL_CLOSE btSocType: 0
V/LGMDMManager( 7712): Create singleton instance
,D/bt_hci_bdroid( 6188): set_power 0
I/bt_vendor( 6188): bt-vendor : BT_VND_OP_POWER_CTRL: Off
I/bt_vendor( 6188): bluetooth satus is on
I/bt_vendor( 6188): bt-vendor : resetting BT status
I/bt_vendor( 6188): Starting hciattach daemon
I/bt_vendor( 6188): try to set false
I/bt_vendor( 6188): Starting hciattach daemon
I/bt_vendor( 6188): try to set false
,I/bt_vendor( 6188): cleanup
I/GKI_LINUX( 6188): gki_task task_id=0 [BTU] terminating
I/GKI_LINUX( 6188): GKI_exit_task 0 done
I/GKI_LINUX( 6188): GKI_shutdown(): task [BTU] terminated
D/BluetoothAdapterState( 6188): CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
D/HeadsetService( 6188): Received stop request...Stopping profile...
D/LGMDMWrapper( 7712): LG MDM library v4.0.0 is available on this device.
,I/LGBluetoothHfpAdapter( 6188): [BTUI] LGBluetoothHfpAdapter cleanup
W/LGBluetoothHeadsetServiceJni( 6188): Cleaning up Bluetooth Handsfree callback object
D/BluetoothAdapterService( 6188): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@125ecfa2
D/HeadsetStateMachine( 6188): Exit Disconnected: -1
D/BluetoothHeadset( 1031): Proxy object disconnected
D/AudioService( 1031): onServiceDisconnected: Bluetooth profile: 1
D/BluetoothHeadset( 1838): Proxy object disconnected
D/BluetoothHeadset( 1838): Proxy object disconnected
D/A2dpService( 6188): Received stop request...Stopping profile...
D/A2dpStateMachine( 6188): Exit Disconnected: -1
D/BluetoothHeadset( 1838): Proxy object disconnected
D/BluetoothAdapterState( 6188): Stopping profile services that were post enabled
D/LGBluetoothAvrcpQcomAdapter( 6188): [BTUI] cleanup
D/LGBluetoothA2dpAdapter( 6188): [BTUI] LGBluetoothA2dpAdapter cleanup
W/LGBluetoothA2dpServiceJni( 6188): Cleaning up Bluetooth Handsfree callback object
D/BluetoothAdapterService( 6188): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@125ecfa2
D/BluetoothA2dp( 1031): Proxy object disconnected
D/AudioService( 1031): onServiceDisconnected: Bluetooth profile: 2
D/HidService( 6188): Received stop request...Stopping profile...
D/BluetoothAdapterService( 6188): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@125ecfa2
D/BluetoothInputDevice( 7649): Proxy object disconnected
D/HidProfile( 7649): Bluetooth service disconnected
,D/HeadsetStateMachine( 6188): Unbinding service...
D/HeadsetPhoneState( 6188): [BTUI] listenForPhoneState : start = false
D/LGBluetoothHfpManager( 6188): [BTUI] listenForMultiSimPhoneState : start = false
D/HeadsetPhoneState( 6188): [BTUI] listenForPhoneState : start = false
D/LGBluetoothHfpManager( 6188): [BTUI] listenForMultiSimPhoneState : start = false
W/BluetoothHeadsetServiceJni( 6188): Cleaning up Bluetooth Handsfree Interface...
W/BluetoothHeadsetServiceJni( 6188): Cleaning up Bluetooth Handsfree callback object
I/LGBluetoothHfpAdapter( 6188): [BTUI] LGBluetoothHfpAdapter cleanup
D/HealthService( 6188): Received stop request...Stopping profile...
D/BluetoothAdapterService( 6188): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@125ecfa2
D/PanService( 6188): Received stop request...Stopping profile...
D/BluetoothAdapterService( 6188): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@125ecfa2
D/BtGatt.DebugUtils( 6188): handleDebugAction() action=null
D/BtGatt.GattService( 6188): Received stop request...Stopping profile...
D/BtGatt.GattService( 6188): stop()
D/BluetoothPan( 7649): BluetoothPAN Proxy object disconnected
D/PanProfile( 7649): Bluetooth service disconnected
D/BtGatt.AdvertiseManager( 6188): advertise clients cleared
D/BluetoothAdapterService( 6188): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@125ecfa2
D/BluetoothMapService( 6188): Received stop request...Stopping profile...
D/BluetoothMapService( 6188): stop()
D/BluetoothMapEmailAppObserver( 6188): deinitObservers()
D/BluetoothMapEmailAppObserver( 6188): removeReceiver()
D/BluetoothAdapterService( 6188): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@125ecfa2
D/BluetoothMap( 7649): Proxy object disconnected
,I/BluetoothA2dpServiceJni( 6188): cleanupNative
D/MapProfile( 7649): Bluetooth service disconnected
I/GKI_LINUX( 6188): gki_task task_id=2 [A2DP-MEDIA] terminating
I/GKI_LINUX( 6188): GKI_exit_task 2 done
I/GKI_LINUX( 6188): GKI_shutdown(): task [A2DP-MEDIA] terminated
W/BluetoothHidServiceJni( 6188): Cleaning up Bluetooth HID Interface...
W/BluetoothHidServiceJni( 6188): Cleaning up Bluetooth GID callback object
W/BluetoothHealthServiceJni( 6188): Cleaning up Bluetooth Health Interface...
W/BluetoothHealthServiceJni( 6188): Cleaning up Bluetooth Health object
W/LGBluetoothHealthServiceJni( 6188): Cleaning up Bluetooth Health object
W/BluetoothPanServiceJni( 6188): Cleaning up Bluetooth PAN Interface...
W/BluetoothPanServiceJni( 6188): Cleaning up Bluetooth PAN callback object
V/BluetoothMapService( 6188): Handler(): got msg=4
D/BluetoothMapService( 6188): MAP Service closeService in
D/LGBluetoothMapAdapter( 6188): [BTUI] LGBluetoothMapAdapter cleanup
V/BluetoothMapService( 6188): MAP Service closeService out
D/BluetoothAdapterState( 6188): CURRENT_STATE=PENDING, MESSAGE = STOPPED, isTurningOn=false, isTurningOff=true
D/BluetoothAdapterProperties( 6188): Setting state to 10
I/BluetoothAdapterState( 6188): Bluetooth adapter state changed: 13-> 10
D/BluetoothMapService( 6188): cleanup()
D/BluetoothMapService( 6188): MAP Service closeService in
D/LGBluetoothMapAdapter( 6188): [BTUI] LGBluetoothMapAdapter cleanup
V/BluetoothMapService( 6188): MAP Service closeService out
D/BluetoothManagerService( 1031): Message: 60
D/BluetoothManagerService( 1031): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 13, newState=10
D/BluetoothManagerService( 1031): Broadcasting onBluetoothStateChange(false) to 9 receivers.
D/BluetoothPbap( 7649): onBluetoothStateChange: up=false
I/BluetoothAdapterState( 6188): Entering OffState
D/BluetoothHeadset( 1838): onBluetoothStateChange: up=false
D/BluetoothPan( 7649): onBluetoothStateChange on: false
D/BluetoothHeadset( 1838): onBluetoothStateChange: up=false
D/BluetoothMap( 7649): onBluetoothStateChange: up=false
D/BluetoothA2dp( 1031): onBluetoothStateChange: up=false
D/BluetoothHeadset( 1031): onBluetoothStateChange: up=false
D/BluetoothInputDevice( 7649): onBluetoothStateChange: up=false
D/BluetoothHeadset( 1838): onBluetoothStateChange: up=false
D/BluetoothManagerService( 1031): Calling onBluetoothServiceDown callbacks
D/BluetoothManagerService( 1031): Broadcasting onBluetoothServiceDown() to 8 receivers.
D/BluetoothManagerService( 1031): Calling onQBluetoothServiceDown callbacks
D/BluetoothManagerService( 1031): Broadcasting onQBluetoothServiceDown() to 0 receivers.
D/BluetoothManagerService( 1031): unbindAndFinish(): android.bluetooth.IBluetooth$Stub$Proxy@13ed3ae4 mBinding = false
,D/BluetoothManagerService( 1031): Sending unbind request.
D/BluetoothManagerService( 1031): Bluetooth State Change Intent: 13 -> 10
D/LGBluetoothAPIService( 1928): [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
D/LGBluetoothAPIService( 1928): Message: 2
D/LGBluetoothAPIService( 1928): unbindAndFinish(): com.lge.bluetooth.ILGBluetoothAPIAdapter$Stub$Proxy@195a372 mBinding = false
,I/GKI_LINUX( 6188): gki_task task_id=1 [BTIF] terminating
I/[SystemUI]BluetoothHandler( 1468): Receive : BluetoothAdapter.ACTION_STATE_CHANGED
I/GKI_LINUX( 6188): GKI_exit_task 1 done
I/GKI_LINUX( 6188): GKI_shutdown(): task [BTIF] terminated
I/BluetoothServiceJni( 6188): cleanupNative: return from cleanup
I/art     ( 6188): --- WEIRD: removing null entry 246
W/art     ( 6188): JNI WARNING: DeleteGlobalRef(0x2003da) failed to find entry
W/LGBluetoothServiceJni( 6188): Cleaning up Bluetooth Service callback object
D/LGBluetoothFeatureConfig( 7649): isPrivacyLogsEnabled : true
D/LGBluetoothSettingsDBObserver( 6188): [BTUI] unregister observer for LG device name DB
E/LGBluetoothEventManager( 7649): [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_OFF
D/LGBluetoothEventManager( 7649): [BTUI] clear device connection state
D/LGBluetoothAPIService( 1928): Sending unbind request.
W/ContextImpl( 7649): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
I/art     ( 6188): System.exit called, status: 0
I/AndroidRuntime( 6188): VM exiting with result code 0, cleanup skipped.
D/BluetoothAdapter( 1468): 28260730: getState() :  mService = null. Returning STATE_OFF
D/BluetoothAdapter( 1468): 28260730: getState() :  mService = null. Returning STATE_OFF
,D/DockEventReceiver( 7649): finishStartingService: stopping service
,V/AudioFlinger(  340): 6188 died, releasing its sessions
,V/AudioFlinger(  340):  pid 1838 @ 0
V/AudioFlinger(  340):  pid 3252 @ 1
V/AudioFlinger(  340):  pid 3252 @ 2
D/LGBluetoothUserBindClient( 7649): [BTUI] onServiceDisconnected
D/PostponalbeReceiver( 7712): WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,W/ContextImpl( 7712): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
,I/ActivityManager( 1031): Process com.android.bluetooth (pid 6188) has died
W/ActivityManager( 1031): Scheduling restart of crashed service com.android.bluetooth/com.lge.bluetooth.app.LGBluetoothUserBindServer in 1000ms
,I/ActivityManager( 1031): Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=7780 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
I/ActivityManager( 1031): Killing 6932:com.uei.lg.quicksetsdk.maxq616/1000 (adj 15): empty #17
,I/QRemote ( 5941): [RemoteControlManager.java:195:onServiceDisconnected()] oooooo start
W/System.err( 5941): android.os.DeadObjectException
W/System.err( 5941): 	at android.os.BinderProxy.transactNative(Native Method)
W/System.err( 5941): 	at android.os.BinderProxy.transact(Binder.java:496)
W/System.err( 5941): 	at com.uei.control.IControl.unregisterCallback(IControl.java:502)
W/System.err( 5941): 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:199)
,W/System.err( 5941): 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
W/System.err( 5941): 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
W/System.err( 5941): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 5941): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 5941): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 5941): 	at android.app.ActivityThread.main(ActivityThread.java:5274)
W/System.err( 5941): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 5941): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 5941): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
W/System.err( 5941): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
E/UEI.SmartControl( 5941): IControl.unregisterCallback error: android.os.DeadObjectException
W/System.err( 5941): android.os.DeadObjectException
W/System.err( 5941): 	at android.os.BinderProxy.transactNative(Native Method)
W/System.err( 5941): 	at android.os.BinderProxy.transact(Binder.java:496)
W/System.err( 5941): 	at com.uei.control.IControl.unregisterSetupReadyCallback(IControl.java:818)
W/System.err( 5941): 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:200)
W/System.err( 5941): 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
W/System.err( 5941): 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
W/System.err( 5941): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 5941): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 5941): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 5941): 	at android.app.ActivityThread.main(ActivityThread.java:5274)
W/System.err( 5941): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 5941): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 5941): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
W/System.err( 5941): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
E/UEI.SmartControl( 5941): IControl.unregisterSetupReadyCallback error: android.os.DeadObjectException
I/QRemote ( 5941): [RemoteControlManager.java:203:onServiceDisconnected()] oooooo Control unbind before rebinding.
,W/ActivityThread( 7712): ClassLoader.getResources: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/libprocessgroup( 1031): failed to open /acct/uid_1000/pid_6932/cgroup.procs: No such file or directory
,W/ActivityManager( 1031): Scheduling restart of crashed service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service in 10741ms
,D/QRemote ( 5941): [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]10
I/QRemote ( 5941): [RemoteControlManager.java:157:onBindIRService()] oooooo bind
,I/ActivityManager( 1031): Start proc com.uei.lg.quicksetsdk.maxq616 for service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service: pid=7805 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
D/QRemote ( 5941): [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
,D/BluetoothPermissionRequest( 7649): onReceive
D/LGBluetoothUtils( 7649): [BTUI] FileNotFound: readProperty
D/BluetoothDiscoverableTimeoutReceiver( 7649): cancelDiscoverableAlarm(): Enter
D/LGBluetoothResetSettingReceiver( 7649): return without doing reset settings.
I/PCSuite ( 7780): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
,D/PCSuite ( 7780): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 7780): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
I/ActivityManager( 1031): Start proc com.android.bluetooth for broadcast com.android.bluetooth/.opp.BluetoothOppReceiver: pid=7826 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008, 4002, 1023} abi=armeabi-v7a
V/WiFiOffLoadBroadcast( 7649): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,W/ResourcesManager( 7826): Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
W/ResourcesManager( 7826): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 7826): Asset path '/system/framework/com.qcom.bluetooth.jar' does not exist or contains no resources.
W/ResourcesManager( 7826): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
D/UEI.SmartControl( 7805): Quickset Services start...
,I/UEI.SmartControl( 7805): Manufacture = LGE
D/UEI.SmartControl( 7805): Id = LGNevo
D/UEI.SmartControl( 7805): File observer start...
E/UEI.SmartControl( 7805): IR Port is disabled: false
D/UEI.SmartControl( 7805): Starting file observer...
D/UEI.SmartControl( 7805): Extracting JNI libs...
D/UEI.SmartControl( 7805): --- this system supports 32-bit or 64-bit only
D/LgDataFeature( 7712): LgDataFeature() Constructor: none
D/LgDataFeature( 7712): LgDataFeature() Constructor Done, null
,D/BluetoothAdapterApp( 7826): Loading JNI Library
,D/LgDataFeature( 7649): LgDataFeature() Constructor: none
D/LgDataFeature( 7649): LgDataFeature() Constructor Done, null
,D/WiFiOffLoadBroadcast( 7649): MCCMNC not supported: null
D/BluetoothAdapterApp( 7826): REFCOUNT: Constructed com.android.bluetooth.btservice.AdapterApp@28c128bb Instance Count = 1
D/QRemote ( 5941): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 5941): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
D/BluetoothAdapterApp( 7826): onCreate
I/QRemote ( 5941): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
D/PostponalbeReceiver( 7712): WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
W/ContextImpl( 7712): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
,I/PCSuite ( 7780): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 7780): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 7780): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 7649): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 7649): MCCMNC not supported: null
D/ProfileConfigQcom( 7826): [BTUI] HeadsetService is supported
D/ProfileConfigQcom( 7826): Adding HeadsetService
D/ProfileConfigQcom( 7826): [BTUI] A2dpService is supported
D/ProfileConfigQcom( 7826): Adding A2dpService
D/ProfileConfigQcom( 7826): [BTUI] HidService is supported
D/ProfileConfigQcom( 7826): Adding HidService
D/ProfileConfigQcom( 7826): [BTUI] HealthService is supported
D/ProfileConfigQcom( 7826): Adding HealthService
,D/LGBluetoothFeatureConfig( 7826): isSupportPan() :  mTargetOp=OPEN
D/QRemote ( 5941): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 5941): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
D/ProfileConfigQcom( 7826): [BTUI] PanService is supported
D/ProfileConfigQcom( 7826): Adding PanService
D/ProfileConfigQcom( 7826): [BTUI] GattService is supported
D/ProfileConfigQcom( 7826): Adding GattService
D/ProfileConfigQcom( 7826): [BTUI] BluetoothMapService is supported
D/ProfileConfigQcom( 7826): Adding BluetoothMapService
I/QRemote ( 5941): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
D/ProfileConfigQcom( 7826): [BTUI] HeadsetClientService is NOT supported
D/LGBluetoothOppAdapter( 7826): [BTUI] getInstance : create [LGBluetoothOppAdapter]
D/PostponalbeReceiver( 7712): WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
W/ContextImpl( 7712): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
D/LGBluetoothUserBindClient( 7649): [BTUI] onServiceConnected
V/LGMDMManagerInternal( 7826): Create singleton instance
I/PCSuite ( 7780): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 7780): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 7780): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 7649): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 7649): MCCMNC not supported: null
D/QRemote ( 5941): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,D/QRemote ( 5941): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 5941): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
D/PostponalbeReceiver( 7712): WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
W/ContextImpl( 7712): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
V/WiFiOffLoadBroadcast( 7649): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 7649): MCCMNC not supported: null
,D/QRemote ( 5941): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 5941): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 5941): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
D/UEI.SmartControl( 7805): --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
D/UEI.SmartControl( 7805): --- Checking lib: libqs_armeabi-v7a.zip
D/UEI.SmartControl( 7805): --- Extracting JNI libs: libqs_armeabi-v7a.zip
D/PostponalbeReceiver( 7712): WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
W/ContextImpl( 7712): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
,I/PCSuite ( 7780): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 7780): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 7780): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 7649): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
W/ContextImpl( 7712): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.vsmandroid.gh.h:-1 com.mcafee.vsm.ext.common.a.d.a:-1 com.mcafee.vsm.ext.common.api.ExtUtils.stopApp:-1 
D/WiFiOffLoadBroadcast( 7649): MCCMNC not supported: null
D/QRemote ( 5941): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 5941): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 5941): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
V/BluetoothFtpReceiver( 7826): BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
,D/PostponalbeReceiver( 7712): WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
W/ContextImpl( 7712): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
V/BluetoothSapReceiver( 7826): [BTUI] checkServiceStart
V/BluetoothSapReceiver( 7826): [BTUI] region:EU country:EU
V/BluetoothSapReceiver( 7826): SapReceiver onReceive 
V/BluetoothSapReceiver( 7826): action = android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothSapReceiver( 7826):  Bluetooth Adapter state = 10
D/SiteAdvisor( 7712): com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.google.android.browser/com.android.browser.BrowserActivity not supported
I/PCSuite ( 7780): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 7780): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 7780): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
D/LGBluetoothProfileConnectionReceiver_EasySetting( 7738): [BTUI] STATE_OFF : reset connected device information EasySettings
V/WiFiOffLoadBroadcast( 7649): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/SiteAdvisor( 7712): com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.amazon.cloud9/com.amazon.cloud9.BrowserActivity not supported
D/AuthorizationBluetoothService( 2057): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,D/SiteAdvisor( 7712): com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.sec.android.app.sbrowser/com.sec.android.app.sbrowser.SBrowserMainActivity not supported
D/SiteAdvisor( 7712): com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.sec.android.app.sbrowser/com.sec.android.app.sbrowser.SBrowserMainActivity not supported
I/UEI.SmartControl( 7805): --- Selecting new region: 6
D/SiteAdvisor( 7712): com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.htc.sense.browser/com.htc.sense.browser.BrowserActivity not supported
I/SiteAdvisor( 7712): com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Loading supported browsers: com.android.browser/com.android.browser.BrowserActivity; com.android.chrome/com.android.chrome.Main; 
I/UEI.SmartControl( 7805): Model = LG-D855
D/WiFiOffLoadBroadcast( 7649): MCCMNC not supported: null
D/SiteAdvisor( 7712): com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Here is the storedCurrentAppVersion: 3.1.2.1430
D/UEI.SmartControl( 7805): QS Service created
D/SiteAdvisor( 7712): com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Here about to commit perfs
I/ActivityManager( 1031): Killing 7022:com.google.android.gms:car/u0a5 (adj 15): empty #17
I/UEI.SmartControl( 7805): Service initServices...
,D/UEI.SmartControl( 7805): QS start get config
D/UEI.SmartControl( 7805): Loading JNI Libs...
,W/libprocessgroup( 1031): failed to open /acct/uid_10005/pid_7022/cgroup.procs: No such file or directory
D/QRemote ( 5941): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 5941): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 5941): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,I/ActivityManager( 1031): Start proc com.lge.formmanager for broadcast com.lge.formmanager/.FormServiceReceiver: pid=7851 uid=10026 gids={50026, 9997, 3003, 1028} abi=armeabi-v7a
I/ActivityManager( 1031): Killing 7120:com.lge.appbox.client/u0a11 (adj 15): empty #17
,I/wpa_supplicant( 6231): p2p0: CTRL-EVENT-TERMINATING 
,I/wpa_supplicant( 6231): monitor socket send errors count : 1
I/wpa_supplicant( 6231): CTRL_IFACE: Detach monitor /data/misc/wifi/sockets/wpa_ctrl_1928-2\x00 that cannot receive messages
W/wpa_supplicant( 6231): USIM:  scard_deinit function
D/WifiMonitor( 1031): Event [IFNAME=p2p0 CTRL-EVENT-TERMINATING ]
D/WifiMonitor( 1031): Dropping event because (p2p0) is stopped
D/WifiMonitor( 1031): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=0 BSSID=00:00:00:00:00:00 SSID=]
E/WifiMonitor( 1031): WifiMonitor:wlan0 cnt=24 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=0 BSSID=00:00:00:00:00:00 SSID=
E/WifiStateMachine( 1031):  SupplicantStoppingState SUPPLICANT_STATE_CHANGE_EVENT 24 0 rt=1432249  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: DISCONNECTED
E/WifiStateMachine( 1031):  DefaultState SUPPLICANT_STATE_CHANGE_EVENT 24 0 rt=1432249  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: DISCONNECTED
I/UEI.SmartControl( 7805): Supports setup maps: true
,D/UEI.SmartControl( 7805): QS start statue = true Error code = 0
,I/UEI.SmartControl( 7805): QS version = v2.7.10.1_RC1
I/UEI.SmartControl( 7805): QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
I/UEI.SmartControl( 7805): ### init IR Blaster...
D/serial_port( 7805): Configuring serial port
E/UEI.SmartControl( 7805): UEIBLaster setting for 616
I/UEI.SmartControl( 7805): Setting serial record hearder size = 2
I/UEI.SmartControl( 7805): configuring settings for MAXQ616
I/UEI.SmartControl( 7805): Get version...
,I/art     ( 1031): Explicit concurrent mark sweep GC freed 222473(10MB) AllocSpace objects, 12(960KB) LOS objects, 33% free, 45MB/67MB, paused 1.982ms total 160.613ms
,W/libprocessgroup( 1031): failed to open /acct/uid_10011/pid_7120/cgroup.procs: No such file or directory
D/UEI.SmartControl( 7805): serial port data available: 21
,D/PCSuite ( 7780): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 7649): WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,W/FormManager( 7851): Network not available. Please check & try again.
D/WiFiOffLoadBroadcast( 7649): MCCMNC not supported: null
D/UEI.SmartControl( 7805): MAXQ616 A2-X4 software.
I/UEI.SmartControl( 7805): IR Blaster version: 256702256704300002
I/UEI.SmartControl( 7805): QS saving settings...
E/WifiStateMachine( 1031):  SupplicantStoppingState CMD_RSSI_POLL 1 0 <unknown ssid> rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:2998] from screen [on:0 period:-1900567288] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  DefaultState CMD_RSSI_POLL 1 0 <unknown ssid> rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-1900567287] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/UEI.SmartControl( 7805): IR Blaster version: 25672567
V/FormManager( 7851): Network unavailable.
,D/PostponalbeReceiver( 7712): WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'null'.
,V/FormManager( 7851): Network unavailable.
D/PostponalbeReceiver( 7712): WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'null'.
D/PostponalbeReceiver( 7712): WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'null'.
D/PostponalbeReceiver( 7712): WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'null'.
D/PostponalbeReceiver( 7712): WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'null'.
D/PostponalbeReceiver( 7712): WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'null'.
D/UEI.SmartControl( 7805): serial port data available: 4
I/ActivityManager( 1031): Killing 7156:com.android.contacts/u0a19 (adj 15): empty #17
,I/wpa_supplicant( 6231): wlan0: CTRL-EVENT-TERMINATING 
D/WifiMonitor( 1031): Event [IFNAME=wlan0 CTRL-EVENT-TERMINATING ]
E/WifiMonitor( 1031): WifiMonitor:wlan0 cnt=25 dispatchEvent: CTRL-EVENT-TERMINATING 
D/WifiMonitor( 1031): Disconnecting from the supplicant, no more events
E/WifiStateMachine( 1031):  SupplicantStoppingState SUP_DISCONNECTION_EVENT 25 0
W/libprocessgroup( 1031): failed to open /acct/uid_10019/pid_7156/cgroup.procs: No such file or directory
,I/UEI.SmartControl( 7805): Device manager: loading config....
D/UEI.SmartControl( 7805): ----------- loading internal config...
W/ContextImpl( 7805): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
E/UEI.SmartControl( 7805): Services init done
D/UEI.SmartControl( 7805): QS Service init finished
D/UEI.SmartControl( 7805): QS Service version name: 2.1.91
D/UEI.SmartControl( 7805): QS Service version code: 201091
D/UEI.SmartControl( 7805): Service requested: Control
E/UEI.SmartControl( 7805): Loading SETTINGS...
D/UEI.SmartControl( 7805): Request IControl service: devices are loaded...
,I/QRemote ( 5941): [RemoteControlManager.java:183:onServiceConnected()] oooooo start
I/ActivityManager( 1031): Killing 7185:com.android.gallery3d/u0a27 (adj 15): empty #17
I/UEI.SmartControl( 7805): ------ IControl API: 11
I/UEI.SmartControl( 7805): Registering callback...
I/UEI.SmartControl( 7805): ------ IControl API: 19
I/UEI.SmartControl( 7805): Registering Services Ready callback...
D/UEI.SmartControl( 7805): -- Open brand translation xml: brands_translations_ko
I/UEI.SmartControl( 7805): Notify AllClients services are ready: 0
,D/UEI.SmartControl( 7805): -----service ready thread exits
,I/QRemote ( 5941): [RemoteControlManager.java:660:QSSetupIsReady()] oooooo 140517:sdkIsReady callback... get functions. Result:0
D/QRemote ( 5941): [RemoteControlManager.java:388:handleMessage()] oooooo 140510:START_SESSION
D/QRemote ( 5941): [RemoteControlManager.java:394:handleMessage()] oooooo 140510:send retrieve msg
D/QRemote ( 5941): [RemoteControlManager.java:322:handleMessage()] oooooo 140510:handler call retrieveDevices
D/QRemote ( 5941): [RemoteControlManager.java:336:retrieveDevices()] oooooo retrieveDevices: start
I/UEI.SmartControl( 7805): ------ IControl API: 8
D/QRemote ( 5941): [RemoteControlManager.java:340:retrieveDevices()] oooooo retrieveDevices: 0
D/QRemote ( 5941): [RemoteControlManager.java:345:retrieveDevices()] oooooo retrieveDevices complete:true
D/QRemote ( 5941): [RemoteControlManager.java:353:retrieveDevices()] oooooo retrieveDevices: notifyDataSetChanged()
D/QRemote ( 5941): [QRemoteApplication.java:145:onRemoteControlStateChanged()] oooooo onRemoteControlStateChanged called in QRemoteApp
D/QRemote ( 5941): [QRemoteApplication.java:158:onRemoteControlStateChanged()] oooooo Widget count is [1]. send broadcast
D/QRemote ( 5941): [QRemoteApplication.java:160:onRemoteControlStateChanged()] oooooo Widget[0]:3
W/libprocessgroup( 1031): failed to open /acct/uid_10027/pid_7185/cgroup.procs: No such file or directory
D/UEI.SmartControl( 7805): Internal service binding...
,D/QRemote ( 5941): [QRemoteApplication.java:188:onRemoteControlStateChanged()] oooooo 140526:onRemoteControlStateChanged&sdkIsReady. stop Service
V/QRemote ( 5941): [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
D/QRemote ( 5941): [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
E/QRemote ( 5941): [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
D/QRemote ( 5941): [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
D/QRemote ( 5941): [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
D/QRemote ( 5941): [RemoteAppWidgetProvider.java:506:onUpdate()] oooooo 140510:RetrieveDevices complete. Start loading
D/QRemote ( 5941): [RemoteAppWidgetProvider.java:508:onUpdate()] oooooo 140510:appWidgetIds[0]:3 loading
D/QRemote ( 5941): [RemoteAppWidgetManager.java:41:startLoading()] oooooo 140518:widgetId[3] loading start at [1454093346159]
D/QRemote ( 5941): [RemoteAppWidgetManager.java:239:doInBackground()] oooooo 140407:doinBack arr:0
,V/QRemote ( 5941): [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.widget_ui_update
,E/QRemote ( 5941): [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
D/QRemote ( 5941): [RemoteAppWidgetProvider.java:171:onReceive()] oooooo total:0
D/QRemote ( 5941): [RemoteAppWidgetProvider.java:172:onReceive()] oooooo selected:0
D/QRemote ( 5941): [RemoteAppWidgetProvider.java:173:onReceive()] oooooo arr:[]
D/QRemote ( 5941): [RemoteAppWidgetProvider.java:174:onReceive()] oooooo appWidgetId:3
D/QRemote ( 5941): [RemoteAppWidgetProvider.java:815:updateRemoteViews()] oooooo UpdateRemoteViews3:widgetId:3
D/QRemote ( 5941): [RemoteAppWidgetProvider.java:986:updateRemoteViews()] oooooo updateAppWidget5:widgetId:3]
D/WfdsService( 1928): Supplicant Connection state is changed : false
D/WfdsService( 1928): DefaultState - WIFI_SUPPLICANT_DISCONNECTED
D/WfdsService( 1928): Set the WFDS Monitor: false
D/WfdsMonitor( 1928): WFDS Monitor is stopped
D/WifiOffDelayIfNotUsed( 1031): stopMonitoring
E/WifiStateMachine( 1031): Couldn't get getWiFiOffloadingIface : 
E/WifiStateMachine( 1031): useWiFiOffloading() : false
E/WifiStateMachine( 1031): CONFIG_LGE_WLAN_PATH : true
,D/LGDMClient( 3943): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
,D/LGDMClient( 3943): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
D/StatusBar.NetworkController( 1468): refreshViews: Data not connected!! Set no data type icon / Roaming
W/ContextImpl( 3943): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
I/WifiServerServiceExt( 1031): WIFI_STATE_CHANGED_ACTION [1]
I/WifiServerServiceExt( 1031): batteryPsActivateMsgHandler : state:0 event:1
I/WifiServerServiceExt( 1031): batteryPsActivateMsgHandler : this is not treated
V/WfdStateTracker( 1928): WfdStateTracker handleDirectStateChangedEvent: 0
W/Settings( 1803): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/ContextImpl( 3943): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
D/LGDMClient( 3943): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=3, isUserType=1
,I/PCSuite ( 7780): [StartReceiver]WIFI_STATE_CHANGED_ACTION : WIFI_STATE_DISABLED
,D/PCSuite ( 7780): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 7780): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 7649): WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
D/LGDMClient( 3943): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
D/LGDMClient( 3943): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
,D/WiFiOffLoadBroadcast( 7649): MCCMNC not supported: null
W/FormManager( 7851): Network not available. Please check & try again.
V/FormManager( 7851): Network unavailable.
V/FormManager( 7851): Network unavailable.
,D/ConnectivityService( 1031): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering( 1031): MasterInitialState.processMessage what=3
,D/GpsLocationProvider( 1031): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,D/ConnectivityService( 1031): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
D/Tethering( 1031): MasterInitialState.processMessage what=3
D/PostponalbeReceiver( 7712): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
,I/NetworkMonitor( 5209): type=WIFI subType= reason=null isConnected=false
,I/NetworkMonitor( 5209): type=WIFI subType= reason=null isConnected=false
D/GpsLocationProvider( 1031): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
D/GpsLocationProvider( 1031): updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/GpsLocationProvider( 1031): updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,W/ContextImpl( 7712): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
,I/ActivityManager( 1031): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=7896 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,I/AppUp4:AppBoxCP( 7896): onCreate
W/AppUp4:DB( 7896):  [AppBoxDatabaseHelper] construct
,I/AppUp4:DB( 7896):  setFingerPrint start
I/AppUp4:DB( 7896):  newfinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys SDK version = 21
I/AppUp4:DB( 7896):  beforefinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys
I/AppUp4:DB( 7896):  SDK version = 21
I/AppUp4:DB( 7896):  beforefinger == newfinger no write in DB
,D/AppUp4:AppBoxApplication( 7896): AppBoxApplication onCreate()
I/NetworkStateForAutoUpdateMonitor( 7896): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 7896): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 7896): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 7896): [onReceive] request level :IDLE....
I/AppUp4:CustModeStarterReceiver( 7896): onReceive
,D/LgDataFeature( 7896): LgDataFeature() Constructor: none
D/LgDataFeature( 7896): LgDataFeature() Constructor Done, null
,D/AppUp4:CustFacade( 7896): Context : android.app.ReceiverRestrictedContext@2c8b476d
,D/AppUp4:CustFacade( 7896): isCustomizationCompleted : false
D/AppUp4:CustFacade( 7896): isPhone : true
D/AppUp4:CustModeStarterReceiver( 7896): begin check event
I/AppUp4:CustModeStarterReceiver( 7896): Event For GoodConnectivity
D/AppUp4:CustModeStarterReceiver( 7896): runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
D/AppUp4:CustModeStarterReceiver( 7896): call method handleAsyncCustNotification.
,D/AppUp4:CustModeStarterReceiver( 7896): handleAsync isTriedOnce : false
E/AppUp4:CustModeStarterReceiver( 7896): handleAsyncCustNotification do not startCustService
,I/ActivityManager( 1031): Killing 7211:com.lge.lockscreensettings/u0a80 (adj 15): empty #17
D/LGDMClient( 3943): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
W/libprocessgroup( 1031): failed to open /acct/uid_10080/pid_7211/cgroup.procs: No such file or directory
,D/LGDMClient( 3943): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
W/ContextImpl( 3943): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
W/ContextImpl( 3943): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
D/LGDMClient( 3943): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=3, isUserType=1
,D/LGDMClient( 3943): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 3943): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
I/ActivityManager( 1031): Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=7929 uid=10023 gids={50023, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,W/ResourcesManager( 7929): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 7929): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,W/ResourcesManager( 7929): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
W/ResourcesManager( 7929): Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
I/LGEmail ( 7929): [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,D/LGEmail ( 7929): user build Type == true (at Util.java isUserModeBuildType 3507)[v:6.41.18]
,W/ResourceType( 7929): No package identifier when getting value for resource number 0x00000000
,D/LgDataFeature( 7929): LgDataFeature() Constructor: none
,D/LgDataFeature( 7929): LgDataFeature() Constructor Done, null
,D/eas_req ( 7929): ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
,V/FormManager( 7851): Network unavailable.
,V/FormManager( 7851): Network unavailable.
W/FormManager( 7851): Network not available. Please check & try again.
I/LgeMiscReceiver( 3252): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 3252): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 3252): networkInfo.isConnected() = false
,I/HubEmail( 7929): JNI_OnLoad()
I/HubEmail( 7929): -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 7929): registerNatives()
I/HubEmail( 7929): -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 7929): registerNativeMethods()
I/HubEmail( 7929): -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
W/art     ( 7929): JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
,I/ActivityManager( 1031): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=7962 uid=10057 gids={50057, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager( 1031): Killing 7057:com.google.android.gms.wearable/u0a5 (adj 15): empty #17
,W/Settings( 7929): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/libprocessgroup( 1031): failed to open /acct/uid_10005/pid_7057/cgroup.procs: No such file or directory
I/ActivityManager( 1031): Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=8000 uid=10062 gids={50062, 9997, 4002, 3003, 1028} abi=armeabi-v7a
I/ActivityManager( 1031): Killing 7234:com.google.android.apps.plus/u0a97 (adj 15): empty #17
,I/art     (  360): Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 466us total 23.059ms
,I/art     (  360): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 447us total 20.835ms
,I/art     (  360): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 414us total 19.660ms
,W/libprocessgroup( 1031): failed to open /acct/uid_10097/pid_7234/cgroup.procs: No such file or directory
,I/ActivityManager( 1031): Start proc com.lge.sizechangable.weather for broadcast com.lge.sizechangable.weather/.layout.WeatherWidget: pid=8021 uid=10085 gids={50085, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager( 1031): Killing 6981:com.android.vending/u0a44 (adj 15): empty #17
,W/libprocessgroup( 1031): failed to open /acct/uid_10044/pid_6981/cgroup.procs: No such file or directory
,I/art     ( 8021): Almond Protected OAT
,D/WeatherApplication( 8021): removeAccount
D/WeatherApplication( 8021): Account.length = 0
,E/WeatherApplication( 8021): OPERATOR:OPEN
,D/WeatherAncestor( 8021): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 19:49:8
,D/Weather.Utils( 8021): 2 : the weather widgets(using time tick) are gone.
,D/Weather.Utils( 8021): 2 : All the weather widget is gone.
D/UpdateThreadPoolManager( 8021): 2 : This is isUpdating : false
D/WeatherAncestor( 8021): connectivity changed - connection : true
,D/WeatherService( 8021): 2 : isServiceAlived():false forecastCache:null
,D/ForecastDataCache( 8021): 2 : lastUpdatedTime: 1430558561343
D/ForecastDataCache( 8021): 2 : currentPackageVersion: 4.40.4
D/ForecastDataCache( 8021): 2 : Cache is not up-to-date, count: 0
,D/LGWifiP2pService( 1031): P2pDisabledState{ when=-5ms what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
,D/LGWifiP2pService( 1031): DefaultState{ when=-5ms what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiStateMachine( 1031):  InitialState CMD_STOP_SUPPLICANT_FAILED 1 0
E/WifiStateMachine( 1031):  DefaultState CMD_STOP_SUPPLICANT_FAILED 1 0
,D/Weather_cast( 8021): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherAncestor( 8021): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 19:49:8
I/ActivityManager( 1031): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=8044 uid=10093 gids={50093, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager( 1031): Killing 2332:com.google.android.gms/u0a5 (adj 15): empty #17
,W/libprocessgroup( 1031): failed to open /acct/uid_10005/pid_2332/cgroup.procs: No such file or directory
,E/VoldCmdListener(  278): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  278): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 8044): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
E/VoldCmdListener(  278): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  278): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 8044): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
E/VoldCmdListener(  278): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  278): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 8044): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
E/VoldCmdListener(  278): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  278): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
,W/Vold    (  278): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 8044): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
I/ActivityManager( 1031): Start proc com.google.android.gms for service com.google.android.gms/.ads.identifier.service.AdvertisingIdService: pid=8082 uid=10005 gids={50005, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
,I/WebViewFactory( 8044): Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,I/LibraryLoader( 8044): Loading: webviewchromium
,I/LibraryLoader( 8044): Time to load native libraries: 6 ms (timestamps 5895-5901)
I/LibraryLoader( 8044): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 8044): Binding Chromium to main looper Looper (main, tid 1) {e79849e}
I/LibraryLoader( 8044): Expected native library version number "",actual native library version number ""
I/chromium( 8044): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 8044): Initializing chromium process, renderers=0
,W/art     ( 8044): Attempt to remove local handle scope entry from IRT, ignoring
W/chromium( 8044): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
I/chromium( 8044): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=38 off=46780 len=2953
I/chromium( 8044): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:39 off:229536 len:643667
,W/ResourcesManager( 8082): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 8082): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
V/AudioPolicyService(  340): registerClient() client 0xb14fd9e0, uid 10093
I/Adreno-EGL( 8044): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 8044): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 8044): Build Date: 12/12/14 금
I/Adreno-EGL( 8044): Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
I/Adreno-EGL( 8044): Remote Branch: 
I/Adreno-EGL( 8044): Local Patches: 
I/Adreno-EGL( 8044): Reconstruct Branch: 
,W/AudioManagerAndroid( 8044): Requires BLUETOOTH permission
,I/MultiDex( 8082): VM with version 2.1.0 has multidex support
,I/MultiDex( 8082): install
,I/MultiDex( 8082): VM has multidex support, MultiDex support library is disabled.
I/NSApplication( 8044): Starting up...
,I/ActivityManager( 1031): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=8125 uid=10097 gids={50097, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
I/ActivityManager( 1031): Killing 6808:com.lge.clock/u0a10 (adj 15): empty #17
W/libprocessgroup( 1031): failed to open /acct/uid_10010/pid_6808/cgroup.procs: No such file or directory
,W/ResourcesManager( 8125): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,V/JNIHelp ( 8082): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,W/ActivityThread( 8082): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 8082): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@42a600c: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 8082): Installed default security provider GmsCore_OpenSSL
,I/ActivityManager( 1031): Killing 6539:com.google.android.apps.books/u0a54 (adj 15): empty #17
W/libprocessgroup( 1031): failed to open /acct/uid_10054/pid_6539/cgroup.procs: No such file or directory
,I/GLSActivity( 2057): [ac] getting account id
,I/GLSUser ( 2057): [t] Fetched account id for thalitester@gmail.com : 105256135866144380227
I/iu.SyncManager( 8082): SYNC; picasa accounts
,D/NetworkLogImpl( 8082): Loaded NetworkSpeedPredictor
D/ChimeraCfgMgr( 8082): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/PostponalbeReceiver( 7712): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
,W/ContextImpl( 7712): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
I/NetworkStateForAutoUpdateMonitor( 7896): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 7896): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 7896): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 7896): [onReceive] request level :IDLE....
I/AppUp4:CustModeStarterReceiver( 7896): onReceive
D/AppUp4:CustFacade( 7896): Context : android.app.ReceiverRestrictedContext@2c8b476d
,D/AppUp4:CustFacade( 7896): isCustomizationCompleted : false
,D/AppUp4:CustFacade( 7896): isPhone : true
D/AppUp4:CustModeStarterReceiver( 7896): begin check event
I/AppUp4:CustModeStarterReceiver( 7896): Event For GoodConnectivity, noConnectivity : false, but skip! 
D/LGDMClient( 3943): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 3943): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
W/ContextImpl( 3943): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
W/ContextImpl( 3943): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,D/LGDMClient( 3943): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=3, isUserType=1
D/eas_req ( 7929): ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
D/LGDMClient( 3943): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 3943): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
I/art     ( 3304): Explicit concurrent mark sweep GC freed 4935(362KB) AllocSpace objects, 0(0B) LOS objects, 36% free, 27MB/43MB, paused 790us total 54.756ms
,I/LgeMiscReceiver( 3252): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 3252): action = android.net.conn.CONNECTIVITY_CHANGE
,I/LgeMiscReceiver( 3252): networkInfo.isConnected() = false
,W/Settings( 7929): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/FormManager( 7851): Network not available. Please check & try again.
V/FormManager( 7851): Network unavailable.
D/WeatherAncestor( 8021): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 19:49:10
,V/FormManager( 7851): Network unavailable.
D/Weather.Utils( 8021): 2 : the weather widgets(using time tick) are gone.
,D/Weather.Utils( 8021): 2 : All the weather widget is gone.
D/UpdateThreadPoolManager( 8021): 2 : This is isUpdating : false
D/WeatherAncestor( 8021): connectivity changed - connection : true
D/WeatherService( 8021): 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@2eedf433
D/ForecastDataCache( 8021): 2 : lastUpdatedTime: 1430558561343
D/ForecastDataCache( 8021): 2 : currentPackageVersion: 4.40.4
,D/ForecastDataCache( 8021): 2 : Cache is up-to-date, count: 0
D/Weather_cast( 8021): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherAncestor( 8021): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 19:49:10
D/ChimeraCfgMgr( 8082): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/GCM     ( 2057): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,D/AuthorizationBluetoothService( 2057): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,V/GmsCoreStatsServiceLauncher( 8082): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,I/ActivityManager( 1031): Start proc com.google.android.gms.wearable for service com.google.android.gms/.wearable.service.WearableService: pid=8175 uid=10005 gids={50005, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
,W/ResourcesManager( 8175): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 8175): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
I/art     ( 1031): Explicit concurrent mark sweep GC freed 46704(2MB) AllocSpace objects, 0(0B) LOS objects, 33% free, 44MB/66MB, paused 1.951ms total 164.352ms
,I/MultiDex( 8175): VM with version 2.1.0 has multidex support
I/MultiDex( 8175): install
I/MultiDex( 8175): VM has multidex support, MultiDex support library is disabled.
,V/JNIHelp ( 8175): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,D/LocationInitializer( 8082): Restart initialization of location
,W/ActivityThread( 8175): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 8175): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@c27a9fe: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 8175): Installed default security provider GmsCore_OpenSSL
D/GCM     ( 2057): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
D/AuthorizationBluetoothService( 2057): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
V/GmsCoreStatsServiceLauncher( 8082): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,D/WearableService( 8175): callingUid 10005, callindPid: 8175
,D/LocationInitializer( 8082): Restart initialization of location
E/MDM     ( 1803): [98] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,E/MDM     ( 1803): [98] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
D/UEI.SmartControl( 7805): Internal timer expired: 1
,D/UEI.SmartControl( 7805): unbind internal service
D/serial_port( 7805): close(fd = 25)
,TIME-OUT KILL (timeout was 1200000ms),I/UEI.SmartControl( 7805): Serial port is closed.
D/PowerManagerServiceEx( 1031): acquireWakeLockInternal: lock=398724214, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1031
V/AlarmManager( 1031): ELAPSED_WAKEUP set : Alarm{249edad0 type 2 when 1439360 com.google.android.gms} when 1439360
D/[Concierge]Service( 2617): onStartCommand(). Type : 9
D/libc-netbsd(  335): default dns: query_ipv6=0, query_ipv4=0
D/DSQN    ( 1031): DNSproblemNotiEnabled is disabled ignore DNS fail CB
D/PowerManagerServiceEx( 1031): releaseWakeLockInternal: lock=398724214 [*alarm*], flags=0x0
D/sensors_hal_Time( 1031): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1031): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1031): tsOffsetIs: Apps: 1440432983570; DSPS: 47340777; Offset : -4305796374
I/GAv4-SVC( 8082): Google Analytics 7.8.99 is starting up.
I/GAV4    ( 8044): Thread[GAThread,5,main]: No campaign data found.
I/ActivityManager( 1031): Killing 7693:com.lge.lifetracker/u0a37 (adj 15): empty #17
W/libprocessgroup( 1031): failed to open /acct/uid_10037/pid_7693/cgroup.procs: No such file or directory
I/ActivityManager( 1031): Killing 7738:com.lge.settings.easy/1000 (adj 15): empty #17
W/libprocessgroup( 1031): failed to open /acct/uid_1000/pid_7738/cgroup.procs: No such file or directory
D/AndroidRuntime( 8222): 
D/AndroidRuntime( 8222): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 8222): CheckJNI is OFF
D/AndroidRuntime( 8222): Calling main entry com.android.commands.pm.Pm
I/ActivityManager( 1031): Force stopping com.test.thalitest appid=10311 user=-1: uninstall pkg
I/ActivityManager( 1031): Killing 6098:com.test.thalitest/u0a311 (adj 0): stop com.test.thalitest
I/WindowState( 1031): WIN DEATH: Window{d24d327 u0 com.test.thalitest/com.test.thalitest.MainActivity}
D/WifiService( 1031): Client connection lost with reason: 4
W/PackageSettings( 1031): Skipping PackageSetting{3b60725a com.example.hello/10319} due to missing metadata
D/InputDispatcher( 1031): Window went away: Window{d24d327 u0 com.test.thalitest/com.test.thalitest.MainActivity}
I/ActivityManager( 1031):   Force finishing activity ActivityRecord{376570e0 u0 com.test.thalitest/.MainActivity t4}
E/GBMv2   (  356): DFP En is all cleared set to be enabled
W/ActivityManager( 1031): Spurious death for ProcessRecord{145ed3fc 6098:com.test.thalitest/u0a311}, curProc for 6098: null
I/ActivityManager( 1031): Force stopping com.test.thalitest appid=10311 user=0: pkg removed
I/ActivityManager( 1031):   Force finishing activity ActivityRecord{376570e0 u0 com.test.thalitest/.MainActivity t4 f}
W/ActivityManager( 1031): Duplicate finish request for ActivityRecord{376570e0 u0 com.test.thalitest/.MainActivity t4 f}
I/art     ( 4227): Explicit concurrent mark sweep GC freed 23796(1335KB) AllocSpace objects, 0(0B) LOS objects, 35% free, 29MB/45MB, paused 505us total 41.643ms
I/[LGHome]EVENT( 2020): [Launcher.java:5338:onStart()]onStart
D/SplitWindowPolicy( 1928): updateActivityStateChanged: resumed=false, screenId=0, isScreenFull=false
D/SplitWindowPolicy( 1928): topRunningActivity=ActivityInfo{20af83c3 co.....Launcher}, taskId=3, activityType=1, bIsSplit=false
I/[LGHome]EVENT( 2020): [Launcher.java:903:onResume()]onResume
D/SplitWindowPolicy( 1928): updateActivityStateChanged: resumed=true, screenId=0, isScreenFull=false
D/SplitWindowPolicy( 1928): topRunningActivity=ActivityInfo{10b2b440 co.....Launcher}, taskId=3, activityType=1, bIsSplit=false
D/KeyguardModel( 1468): mPackageIntentReceiver, received action: android.intent.action.PACKAGE_REMOVED, sendingUserId:0
I/[LGHome]EVENT( 2020): [LauncherModel.java:1352:startLoader()]startLoader isLaunching=true
I/[LGHome]Launcher.Model( 2020): [LauncherModel.java:1469:loadAndBindWorkspace()]loadAndBindWorkspace=0ms
W/GeofencerStateMachine( 1803): Ignoring removeGeofence because network location is disabled.
D/LIA_Service_RemotePackageHandler( 1983): onReceive action : android.intent.action.PACKAGE_REMOVED = package:com.test.thalitest
D/LIA_MrGDBLogger_PackageInfoDetector( 2712): [dreamwood]action: android.intent.action.PACKAGE_REMOVED, package: com.test.thalitest
I/InputReader( 1031): Reconfiguring input devices.  changes=0x00000010
D/PostponalbeReceiver( 7712): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.intent.action.PACKAGE_REMOVED'.
W/System.err( 4185): android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
W/System.err( 4185): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
W/System.err( 4185): 	at com.lge.mlt.MptOnAppWatcher$1.onReceive(MptOnAppWatcher.java:44)
W/System.err( 4185): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:956)
W/System.err( 4185): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 4185): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 4185): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 4185): 	at android.app.ActivityThread.main(ActivityThread.java:5274)
W/System.err( 4185): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 4185): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 4185): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
W/System.err( 4185): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
I/ActivityManager( 1031): Start proc com.lge.lockscreensettings for content provider com.lge.lockscreensettings/.LockSettingsProvider: pid=8251 uid=10080 gids={50080, 9997, 1028, 1015} abi=armeabi-v7a
D/ActionManagerService( 1892): notifyUserLog: 1000003
D/LIA_Informant_ActionManagerMessageHandler( 2712): handleMessage: what(1000) actionID(0x1000003)
I/[LGHome]GBoardWebView( 2020): [GBoardWebView.java:306:loadCacheBitmapPostDelayed()]loadCacheBitmapPostDelayed() delay:1
I/art     ( 1031): Explicit concurrent mark sweep GC freed 12542(947KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 44MB/66MB, paused 3.261ms total 129.273ms
I/art     ( 1031): WaitForGcToComplete blocked for 83.137ms for cause Explicit
I/[LGHome]LGActivityUtil( 2020): [LGActivityUtil.java:319:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
I/[SystemUI]QSlideListController( 1468): onReceive = android.intent.action.PACKAGE_REMOVED
I/[LGHome]EVENT( 2020): [Launcher.java:1056:onResume()]onResume end
I/[LGHome]EVENT( 2020): [Launcher.java:1114:onPause()]onPause
V/SIM_STK ( 1031): Menu title from STK is T-Mobile
D/SplitUIManager( 1855): split_name #11 / not available #0
D/SplitUIService( 1855): removed split : 
I/[LGHome]GBoardWebView( 2020): [GBoardWebView.java:247:writeCacheBitmapPostDelayed()]writeCacheBitmapPostDelayed() delay: we don't have a change point1
D/ActionManagerService( 1892): notifyUserLog: 1000004
V/BoardContentProvider( 2712): query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
D/LIA_Informant_ActionManagerMessageHandler( 2712): handleMessage: what(1000) actionID(0x1000004)
I/GBoardWebViewUtils( 2020): checkExpiredAndRemoveCard() card: GBoardCard = { id: mw_initial
I/GBoardWebViewUtils( 2020): , create_time: 1430558575574
I/GBoardWebViewUtils( 2020): , expire_time: 0
I/GBoardWebViewUtils( 2020): , raw_uri: file:///system/etc/mrg_default_forms/MyWellness/initial/initial.html?id=mw_initial
I/GBoardWebViewUtils( 2020): , category: com.lge.intent.category.gboard.MYWELLNESS
I/GBoardWebViewUtils( 2020): , display: false
I/GBoardWebViewUtils( 2020): , animation: false }
I/GBoardWebViewUtils( 2020): checkExpiredAndRemoveCard() card: GBoardCard = { id: dyk000
I/GBoardWebViewUtils( 2020): , create_time: 1430558575600
I/GBoardWebViewUtils( 2020): , expire_time: 0
I/GBoardWebViewUtils( 2020): , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
I/GBoardWebViewUtils( 2020): , category: com.lge.intent.category.gboard.DOYOUKNOW
I/GBoardWebViewUtils( 2020): , display: false
I/GBoardWebViewUtils( 2020): , animation: false }
I/GBoardWebViewUtils( 2020): checkExpiredAndRemoveCard() card: GBoardCard = { id: guide_1111111111116_1453982949437
I/GBoardWebViewUtils( 2020): , create_time: 1453982950152
I/GBoardWebViewUtils( 2020): , expire_time: 0
I/GBoardWebViewUtils( 2020): , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/4/userguide.html?id=guide_1111111111116_1453982949437&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
I/GBoardWebViewUtils( 2020): , category: com.lge.intent.category.gboard.DOYOUKNOW
I/GBoardWebViewUtils( 2020): , display: false
I/GBoardWebViewUtils( 2020): , animation: false }
I/[SystemUI]AppWidgetPanel(QRemoteWidgetPanel)( 1468): onReceive = android.intent.action.PACKAGE_REMOVED, packageName : com.test.thalitest
D/KeyguardModel( 1468): mPackageIntentReceiver, received action: android.intent.action.PACKAGE_FULLY_REMOVED, sendingUserId:0
D/administrator( 1031): Handling package changes for user 0
D/WallpaperManager( 2020): suggestDesiredDimensions(2880, 2560) by package(com.lge.launcher2)
I/SystemUI[Framework]( 1031): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x8000, pkg=com.android.systemui
D/SplitUIManager( 1855): split_name #11 / not available #0
I/SplitUIService( 1855): split app #11
W/PhoneWindowManagerEx( 1031): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx( 1031): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx( 1031): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework]( 1031): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@237516f2,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework]( 1031): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
I/LockScreenSettings( 8251): Wallpaper base directory = /data/user/0/com.lge.lockscreensettings/files/
D/AppUp4:PreloadHelper( 7896): added Exclude : com.test.thalitest
I/[LGHome]EVENT( 2020): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
I/[LGHome]GBoardWebView( 2020): [GBoardWebView.java:321:loadCacheBitmap()]loadCacheBitmap()
I/ActivityManager( 1031): Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=8274 uid=10019 gids={50019, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
D/KeyguardModel( 1468): package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
D/KeyguardModel( 1468): createShortcutInfo...
D/KeyguardModel( 1468): package = com.android.mms, class = com.android.mms.ui.ConversationList
D/KeyguardModel( 1468): createShortcutInfo...
W/ResourcesManager( 1468): Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
W/ResourcesManager( 1468): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 1468): Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
W/ResourcesManager( 1468): Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
W/ResourceType( 1468): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1468): Failure retrieving resources for com.android.mms: Resource ID #0x0
D/KeyguardModel( 1468): package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
D/KeyguardModel( 1468): createShortcutInfo...
I/[LGHome]EVENT( 2020): [Launcher.java:5349:onStop()]onStop
W/ResourcesManager( 1468): Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
W/ResourcesManager( 1468): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourceType( 1468): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1468): Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
D/KeyguardModel( 1468): package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
D/KeyguardModel( 1468): createShortcutInfo...
V/SIM_STK ( 1031): Menu title from STK is T-Mobile
W/ResourcesManager( 1468): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 1468): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 1468): Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
W/ResourcesManager( 1468): Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
W/ResourceType( 1468): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1468): Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
D/KeyguardModel( 1468): package = com.lge.camera, class = com.lge.camera.CameraApp
D/KeyguardModel( 1468): createShortcutInfo...
I/ActivityManager( 1031): Killing 7805:com.uei.lg.quicksetsdk.maxq616/1000 (adj 15): empty #17
W/ResourcesManager( 8274): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 8274): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 8274): Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
W/ResourcesManager( 8274): Asset path '/system/framework/lghiddenlibs.jar' does not exist or contains no resources.
W/ResourcesManager( 8274): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
I/NotificationService( 1031): action=android.intent.action.PACKAGE_REMOVED queryReplace=false
D/BackupManagerService( 1031): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/JobSchedulerService( 1031): Receieved: android.intent.action.PACKAGE_REMOVED
I/QRemote ( 5941): [RemoteControlManager.java:195:onServiceDisconnected()] oooooo start
W/System.err( 5941): android.os.DeadObjectException
W/System.err( 5941): 	at android.os.BinderProxy.transactNative(Native Method)
W/System.err( 5941): 	at android.os.BinderProxy.transact(Binder.java:496)
W/System.err( 5941): 	at com.uei.control.IControl.unregisterCallback(IControl.java:502)
W/System.err( 5941): 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:199)
W/System.err( 5941): 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
W/System.err( 5941): 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
W/System.err( 5941): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 5941): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 5941): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 5941): 	at android.app.ActivityThread.main(ActivityThread.java:5274)
W/System.err( 5941): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 5941): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 5941): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
W/System.err( 5941): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
E/UEI.SmartControl( 5941): IControl.unregisterCallback error: android.os.DeadObjectException
W/System.err( 5941): android.os.DeadObjectException
W/System.err( 5941): 	at android.os.BinderProxy.transactNative(Native Method)
W/System.err( 5941): 	at android.os.BinderProxy.transact(Binder.java:496)
W/System.err( 5941): 	at com.uei.control.IControl.unregisterSetupReadyCallback(IControl.java:818)
W/System.err( 5941): 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:200)
W/System.err( 5941): 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
W/System.err( 5941): 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
W/System.err( 5941): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 5941): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 5941): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 5941): 	at android.app.ActivityThread.main(ActivityThread.java:5274)
W/System.err( 5941): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 5941): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 5941): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
W/System.err( 5941): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
E/UEI.SmartControl( 5941): IControl.unregisterSetupReadyCallback error: android.os.DeadObjectException
I/QRemote ( 5941): [RemoteControlManager.java:203:onServiceDisconnected()] oooooo Control unbind before rebinding.
I/[LGHome]Launcher.Model( 2020): [LauncherModel.java:2230:run()] LauncherModel bind current page shortcut
I/[LGHome]Launcher( 2020): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/[LGHome]EVENT( 2020): [Workspace.java:918:addInScreen()]Add Shortcut [Email] in screen 1 [1, 4]
I/[LGHome]EVENT( 2020): [Workspace.java:918:addInScreen()]Add Shortcut [Play Store] in screen 1 [2, 4]
I/[LGHome]EVENT( 2020): [Workspace.java:918:addInScreen()]Add Shortcut [Camera] in screen 1 [3, 4]
I/[LGHome]EVENT( 2020): [Workspace.java:918:addInScreen()]Add Shortcut [Settings] in screen 1 [4, 4]
I/[LGHome]Launcher.Model( 2020): [LauncherModel.java:2244:run()] LauncherModel bind current page shortcut
I/[LGHome]Launcher( 2020): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 2020): [LGUnreadLgeEmailsBadge.java:107:countUnreadItems()]setTotalCount : 0
I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 2020): [LGUnreadLgeEmailsBadge.java:108:countUnreadItems()]countUnreadItems() ended..
I/[LGHome]EVENT( 2020): [Workspace.java:918:addInScreen()]Add Folder [Google] in screen 1 [0, 4]
I/[LGHome]Launcher.Model( 2020): [LauncherModel.java:2256:run()] LauncherModel bind current page widget
I/[LGHome]Launcher( 2020): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/art     ( 1031): Explicit concurrent mark sweep GC freed 9876(525KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 44MB/66MB, paused 2.119ms total 261.259ms
I/[Concierge]WidgetView( 2020): ConciergeWidgetView is instantiated. sIsWidgetAttached : true
W/ResourcesManager( 1031): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourceType( 1031): Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
D/AndroidRuntime( 8222): Shutting down VM
E/libprocessgroup( 1031): failed to kill 1 processes for processgroup 7805
D/KeyguardModel( 1468): handleShortcutListChanged...
D/PhoneStatusBar( 1468): setSystemUiVisibility vis=8000 mask=ffffffff oldVal=0 newVal=8000 diff=8000
I/[SystemUI]NavigationThemeResource( 1468): NavigationKey Color is changed(BLACK -> WHITE_WITH_SHADOW)
I/[SystemUI]NavigationThemeResource( 1468):  BarMode=4, Theme=WHITE, LightBackground=false (Transparent)
I/[SystemUI]NavigationThemeResource( 1468): , Keyguard show=false, IME shown=false, Panel expanded=false
W/ActivityManager( 1031): Scheduling restart of crashed service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service in 1000ms
D/QRemote ( 5941): [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]10
I/QRemote ( 5941): [RemoteControlManager.java:157:onBindIRService()] oooooo bind
D/[Concierge]Service( 2617): onStartCommand(). Type : 8
D/[Concierge]Service( 2617): Update widget. Component : {com.lge.concierge/com.lge.concierge.ConciergeWidgetProvider}
I/Timeline( 1031): Timeline: Activity_windows_visible id: ActivityRecord{1f5672e0 u0 com.lge.launcher2/.Launcher t3} time:1446750
D/[Concierge]Service( 2617): Update widget ID : 11
D/TaskPersister( 1031): removeObsoleteFile: deleting file=4_task.xml
D/KeyguardModel( 1468): package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
D/KeyguardModel( 1468): createShortcutInfo...
D/KeyguardModel( 1468): package = com.android.mms, class = com.android.mms.ui.ConversationList
D/KeyguardModel( 1468): createShortcutInfo...
W/ResourceType( 1468): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1468): Failure retrieving resources for com.android.mms: Resource ID #0x0
D/[Concierge]WidgetView( 2020): change position of spinner
D/KeyguardModel( 1468): package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
D/KeyguardModel( 1468): createShortcutInfo...
W/ResourceType( 1468): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1468): Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
D/KeyguardModel( 1468): package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
D/KeyguardModel( 1468): createShortcutInfo...
W/ResourceType( 1468): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1468): Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
D/KeyguardModel( 1468): package = com.lge.camera, class = com.lge.camera.CameraApp
D/KeyguardModel( 1468): createShortcutInfo...
I/SystemConfig( 8274): BUILD Country: EU
I/SystemConfig( 8274): BUILD Operator: OPEN
I/ActivityManager( 1031): Start proc com.uei.lg.quicksetsdk.maxq616 for service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service: pid=8294 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
D/QRemote ( 5941): [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
D/[Concierge]Service( 2617): onStartCommand(). Type : 0
I/[Concierge]WidgetView( 2020): initWebView(). Time : 1454093360473
D/KeyguardModel( 1468): handleShortcutListChanged...
I/[Concierge]WebView( 2020): Return exist ConciergeWebView. Reuse : 157058199
D/[Concierge]WidgetView( 2020): State Change : null -> AccInBeforeState
I/[LgeWidgetLib]LgeAppWidgetHostView( 2020): [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
I/[LgeWidgetLib]ExtViewHost( 2020): [LgeAppWidgetExtViewHost.java:136:setState()]New State = com.lge.lgewidgetlib.extview.NormalState@12ad5f5b
I/[LGHome]EVENT( 2020): [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.concierge.ConciergeWidgetProvider] in screen 1 [0, 0]
I/[LGHome]Launcher.Model( 2020): [LauncherModel.java:2256:run()] LauncherModel bind current page widget
I/[LGHome]Launcher( 2020): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/[LGHome]EVENT( 2020): [Workspace.java:918:addInScreen()]Add AppWidget [com.google.android.googlequicksearchbox.SearchWidgetProvider] in screen 1 [0, 2]
D/[Concierge]WidgetView( 2020): isWidgetUpdateSkippable ? true
I/[LGHome]EVENT( 2020): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
D/[Concierge]WidgetBroadcastReceiver( 2020): New receiver registered. Self-unregister old one. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
W/[Concierge]WidgetView( 2020): Widget kill message received. Destory myself. My : 1454091942303, New one : 1454093360473
D/[Concierge]WidgetView( 2020): Unregister all receivers
W/[Concierge]WidgetBroadcastReceiver( 2020): Tried unregister broadcastReceiver which is not registered. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
I/[LGHome]Launcher( 2020): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/[LGHome]EVENT( 2020): [Workspace.java:918:addInScreen()]Add Shortcut [Gallery] in screen 2 [0, 4]
I/[LGHome]EVENT( 2020): [Workspace.java:918:addInScreen()]Add Shortcut [Calendar] in screen 2 [1, 4]
I/[LGHome]EVENT( 2020): [Workspace.java:918:addInScreen()]Add Shortcut [QuickMemo+] in screen 2 [2, 4]
I/[LGHome]EVENT( 2020): [Workspace.java:918:addInScreen()]Add Shortcut [Quick Remote] in screen 2 [3, 4]
I/[LGHome]EVENT( 2020): [Workspace.java:918:addInScreen()]Add Shortcut [FM Radio] in screen 2 [4, 4]
I/[LGHome]Launcher( 2020): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
D/UEI.SmartControl( 8294): Quickset Services start...
I/[LGHome]Launcher( 2020): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/UEI.SmartControl( 8294): Manufacture = LGE
D/UEI.SmartControl( 8294): Id = LGNevo
D/UEI.SmartControl( 8294): File observer start...
E/UEI.SmartControl( 8294): IR Port is disabled: false
D/UEI.SmartControl( 8294): Starting file observer...
D/UEI.SmartControl( 8294): Extracting JNI libs...
D/UEI.SmartControl( 8294): --- this system supports 32-bit or 64-bit only
I/ActivityManager( 1031): Killing 5941:com.lge.qremote/u0a112 (adj 15): empty #17
I/[LgeWidgetLib]LgeAppWidgetHostView( 2020): [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
E/[LgeWidgetLib]LgeAppWidgetHostView( 2020): [LgeAppWidgetHostView.java:124:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
I/[LGHome]EVENT( 2020): [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1] in screen 2 [0, 0]
I/[LGHome]Launcher( 2020): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
D/UEI.SmartControl( 8294): --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
D/UEI.SmartControl( 8294): --- Checking lib: libqs_armeabi-v7a.zip
D/UEI.SmartControl( 8294): --- Extracting JNI libs: libqs_armeabi-v7a.zip
I/Timeline( 2020): Timeline: Activity_idle id: android.os.BinderProxy@37a2b674 time:1446930
W/libprocessgroup( 1031): failed to open /acct/uid_10112/pid_5941/cgroup.procs: No such file or directory
I/SystemConfig( 8274): pm.hasSystemFeature(com.lge.ims.rcs) = false
I/SystemConfig( 8274): existFile = false
I/SystemConfig( 8274): canReadFile = false
I/SystemConfig( 8274): systemFeature RCS result false
D/SystemConfig( 8274): refreshRcsSupport() :false
I/PackageChangeReceiver( 7929): intent action : android.intent.action.PACKAGE_REMOVED (at PackageChangeReceiver.java onReceive 20)
I/UEI.SmartControl( 8294): --- Selecting new region: 6
I/UEI.SmartControl( 8294): Model = LG-D855
D/UEI.SmartControl( 8294): QS Service created
D/VoicemailCleanupService( 2357): Cleaning up data for package: com.test.thalitest
E/SQLiteLog( 2357): (2570) os_unix.c:31441: (30) unlink(/data/user/0/com.android.providers.contacts/databases/contacts2.db-mj142E559EB) - 
D/ContactsProvider2ForLG( 2357): performBackgroundTask SQLiteDiskIOException during query
D/ContactsProvider2ForLG( 2357): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 2570)
D/ContactsProvider2ForLG( 2357): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
D/ContactsProvider2ForLG( 2357): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:560)
D/ContactsProvider2ForLG( 2357): 	at android.database.sqlite.SQLiteSession.endTransactionUnchecked(SQLiteSession.java:437)
D/ContactsProvider2ForLG( 2357): 	at android.database.sqlite.SQLiteSession.endTransaction(SQLiteSession.java:401)
D/ContactsProvider2ForLG( 2357): 	at android.database.sqlite.SQLiteDatabase.endTransaction(SQLiteDatabase.java:525)
D/ContactsProvider2ForLG( 2357): 	at com.android.providers.contacts.ContactDirectoryManager.updateDirectoriesForPackage(ContactDirectoryManager.java:414)
D/ContactsProvider2ForLG( 2357): 	at com.android.providers.contacts.ContactDirectoryManager.onPackageChanged(ContactDirectoryManager.java:363)
D/ContactsProvider2ForLG( 2357): 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:974)
D/ContactsProvider2ForLG( 2357): 	at com.android.providers.contacts.ContactsProvider2ForLG.performBackgroundTask(ContactsProvider2ForLG.java:375)
D/ContactsProvider2ForLG( 2357): 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:748)
D/ContactsProvider2ForLG( 2357): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/ContactsProvider2ForLG( 2357): 	at android.os.Looper.loop(Looper.java:135)
D/ContactsProvider2ForLG( 2357): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/SQLiteLog( 2357): (3850) statement aborts at 37: [DELETE FROM calls WHERE (((source_package = 'com.test.thalitest'))) AND ((type = 4))] disk I/O error
--------- beginning of crash
E/AndroidRuntime( 2357): FATAL EXCEPTION: IntentService[VoicemailCleanupService]
E/AndroidRuntime( 2357): Process: android.process.acore, PID: 2357
E/AndroidRuntime( 2357): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 2357): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/AndroidRuntime( 2357): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:739)
E/AndroidRuntime( 2357): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:892)
E/AndroidRuntime( 2357): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/AndroidRuntime( 2357): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1600)
E/AndroidRuntime( 2357): 	at com.android.providers.contacts.util.DbModifierWithNotification.delete(DbModifierWithNotification.java:161)
E/AndroidRuntime( 2357): 	at com.android.providers.contacts.voicemail.VoicemailContentTable.delete(VoicemailContentTable.java:229)
E/AndroidRuntime( 2357): 	at com.android.providers.contacts.voicemail.VoicemailContentProvider.delete(VoicemailContentProvider.java:135)
E/AndroidRuntime( 2357): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:312)
E/AndroidRuntime( 2357): 	at android.content.ContentResolver.delete(ContentResolver.java:1315)
E/AndroidRuntime( 2357): 	at com.android.providers.contacts.voicemail.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
E/AndroidRuntime( 2357): 	at com.android.providers.contacts.voicemail.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
E/AndroidRuntime( 2357): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 2357): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 2357): 	at android.os.Looper.loop(Looper.java:135)
E/AndroidRuntime( 2357): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ActivityManager( 1031): Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=8316 uid=10027 gids={50027, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
E/DropBoxManagerService( 1031): Can't write: system_app_crash
E/DropBoxManagerService( 1031): java.io.FileNotFoundException: /data/system/dropbox/drop113.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 1031): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/DropBoxManagerService( 1031): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/DropBoxManagerService( 1031): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/DropBoxManagerService( 1031): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
E/DropBoxManagerService( 1031): 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
E/DropBoxManagerService( 1031): 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12437)
E/DropBoxManagerService( 1031): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 1031): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 1031): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/DropBoxManagerService( 1031): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/DropBoxManagerService( 1031): 	... 5 more
I/Process ( 2357): Sending signal. PID: 2357 SIG: 9
E/SQLiteLog( 4185): (3850) statement aborts at 13: [INSERT INTO t001(f004,f005,f002,f003,f006) VALUES (?,?,?,?,?)] disk I/O error
E/SQLiteDatabase( 4185): Error inserting f004=13 f005=8316 f002=1454093360679 f003=com.android.gallery3d f006=10027
E/SQLiteDatabase( 4185): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 4185): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 4185): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:787)
E/SQLiteDatabase( 4185): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:926)
E/SQLiteDatabase( 4185): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 4185): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1572)
E/SQLiteDatabase( 4185): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1442)
E/SQLiteDatabase( 4185): 	at com.lge.mlt.MptCommonLogProvider.insert(MptCommonLogProvider.java:706)
E/SQLiteDatabase( 4185): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:238)
E/SQLiteDatabase( 4185): 	at android.content.ContentResolver.insert(ContentResolver.java:1223)
E/SQLiteDatabase( 4185): 	at com.lge.mlt.MltMonitorService.insertProcessInfoLog(MltMonitorService.java:2584)
E/SQLiteDatabase( 4185): 	at com.lge.mlt.MltMonitorService.access$2700(MltMonitorService.java:38)
E/SQLiteDatabase( 4185): 	at com.lge.mlt.MltMonitorService$DbFlushManager$1.handleMessage(MltMonitorService.java:3409)
E/SQLiteDatabase( 4185): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4185): 	at android.os.Looper.loop(Looper.java:135)
E/SQLiteDatabase( 4185): 	at com.lge.mlt.MltMonitorService$DbFlushManager.run(MltMonitorService.java:3518)
I/UEI.SmartControl( 8294): Service initServices...

```
