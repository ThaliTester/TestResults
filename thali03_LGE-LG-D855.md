#### Test 575312438097721_thali03_LGE-LG-D855 Logs


```
--------- beginning of system
V/AlarmManager( 1030): RTC_WAKEUP set : Alarm{9f91299 type 0 when 1454429722011 com.android.vending} when 1454429722011
,--------- beginning of main
V/QRemote ( 5992): [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.wait_loading
D/QRemote ( 5992): [RemoteAppWidgetProvider.java:211:onReceive()] oooooo 140514:alarm msg received!:6412
W/ContextImpl( 4191): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 com.lge.mlt.MptOnLogDumper.run:279 <bottom of call stack> <bottom of call stack> 
V/SIM_STK ( 1030): Menu title from STK is T-Mobile
D/AndroidRuntime( 6103): 
D/AndroidRuntime( 6103): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 6103): CheckJNI is OFF
V/GLSActivity( 2138): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/GLSUser ( 2138): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 2138): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2138): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2138): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
D/AndroidRuntime( 6103): Calling main entry com.android.commands.am.Am
V/GLSActivity( 2138): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/ActivityManager( 1030): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
V/SplitWindowPolicy( 1974): checkScreen => return. sourceIntent is null or not support SplitWindow component: ComponentInfo{co..../co.....MainActivity}
D/SplitInfo( 1030): new ActivitySplitInfo : ActivitySplitInfo [screenZone=0/ flag=0/ state=NATIVE]
D/ActivityManager( 1030): setTaskToReturnTo : TaskRecord{88b2ea4 #4 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
D/ActivityManager( 1030): setTaskToReturnTo : TaskRecord{88b2ea4 #4 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
D/WindowStateEx( 1030): AppWindowTokenEx init.. 
E/GBMv2   (  343): DFP En is all cleared set to be enabled
I/ActivityManager( 1030): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6138 uid=10311 gids={50311, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
D/AndroidRuntime( 6103): Shutting down VM
D/Finsky  ( 4912): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 4912): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 4912): [1] 5.onFinished: Scheduling replication attempt 1.
D/DSDPConnection( 1867): Display #0 changed.
V/ActivityManager( 1030): Display changed displayId=0
D/SplitWindowPolicy( 1974): updateActivityStateChanged: resumed=true, screenId=1, isScreenFull=true
D/SplitWindowPolicy( 1974): topRunningActivity=ActivityInfo{1f1abdce co.....MainActivity}, taskId=4, activityType=0, bIsSplit=false
D/SplitWindowPolicy( 1974): updateActivityStateChanged: resumed=false, screenId=1, isScreenFull=true
D/SplitWindowPolicy( 1974): topRunningActivity=ActivityInfo{3f8bc4ef co.....MainActivity}, taskId=4, activityType=0, bIsSplit=false
D/ContextHelper( 6138): convertTheme. context->name=com.test.thalitest themeResourceId=16973833
,I/WebViewFactory( 6138): Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,I/LibraryLoader( 6138): Loading: webviewchromium
,I/LibraryLoader( 6138): Time to load native libraries: 4 ms (timestamps 2964-2968)
I/LibraryLoader( 6138): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 6138): Binding Chromium to main looper Looper (main, tid 1) {3f35037b}
,I/LibraryLoader( 6138): Expected native library version number "",actual native library version number ""
,I/chromium( 6138): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 6138): Initializing chromium process, renderers=0
,W/art     ( 6138): Attempt to remove local handle scope entry from IRT, ignoring
,W/chromium( 6138): [WARNING:dns_config_service_posix.cc(293)] Failed to read DnsConfig.
V/AudioPolicyService(  318): registerClient() client 0xb101dea0, uid 10311
,W/chromium( 6138): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
I/chromium( 6138): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=32 off=46780 len=2953
D/BluetoothManagerService( 1030): Message: 20
D/BluetoothManagerService( 1030): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@2e4fa7c5:true
I/chromium( 6138): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:33 off:229536 len:643667
D/BluetoothAdapter( 6138): 1019487640: getState() :  mService = null. Returning STATE_OFF
I/Adreno-EGL( 6138): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 6138): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 6138): Build Date: 12/12/14 금
I/Adreno-EGL( 6138): Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
I/Adreno-EGL( 6138): Remote Branch: 
I/Adreno-EGL( 6138): Local Patches: 
I/Adreno-EGL( 6138): Reconstruct Branch: 
,W/chromium( 6138): [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
W/chromium( 6138): [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
,W/art     ( 6138): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 6138): onDetachedFromWindow called when already detached. Ignoring
D/SystemWebViewEngine( 6138): CordovaWebView is running on device made by: LGE
,W/art     ( 6138): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 6138): Attempt to remove local handle scope entry from IRT, ignoring
,D/OpenGLRenderer( 6138): Render dirty regions requested: true
I/OpenGLRenderer( 6138): Initialized EGL, version 1.4
D/OpenGLRenderer( 6138): Enabling debug mode 0
,D/Atlas   ( 6138): Validating map...
,W/ActivityManager( 1030): Activity pause timeout for ActivityRecord{251040d u0 com.test.thalitest/.MainActivity t4}
D/SplitWindow( 1030): check instance of lgWin Window{1f87ff17 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,D/LgDataFeature( 6138): LgDataFeature() Constructor: none
D/LgDataFeature( 6138): LgDataFeature() Constructor Done, null
,I/SystemUI[Framework]( 1030): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x0, pkg=com.android.systemui
,W/PhoneWindowManagerEx( 1030): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx( 1030): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx( 1030): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework]( 1030): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@37b9922a,  pkg=WindowManager.LayoutParams
,I/SystemUI[Framework]( 1030): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
D/PhoneStatusBar( 1461): setSystemUiVisibility vis=0 mask=ffffffff oldVal=8000 newVal=0 diff=8000
I/[SystemUI]NavigationThemeResource( 1461): NavigationKey Color is changed(WHITE_WITH_SHADOW -> BLACK)
I/[SystemUI]NavigationThemeResource( 1461):  BarMode=0, Theme=WHITE, LightBackground=false (Transparent)
I/[SystemUI]NavigationThemeResource( 1461): , Keyguard show=false, IME shown=false, Panel expanded=false
I/ActivityManager( 1030): Displayed com.test.thalitest/.MainActivity: +628ms (total +744ms)
I/Timeline( 1030): Timeline: Activity_windows_visible id: ActivityRecord{251040d u0 com.test.thalitest/.MainActivity t4} time:113396
,I/Timeline( 6138): Timeline: Activity_idle id: android.os.BinderProxy@1ed824c8 time:113399
I/chromium( 6138): [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
I/chromium( 6138): 
,D/JsMessageQueue( 6138): Set native->JS mode to OnlineEventsBridgeMode
,I/chromium( 6138): [INFO:SkFontConfigInterface_android.cpp(247)] ---- failed to open </system/fonts/CutiveMono.ttf> as a font
I/chromium( 6138): 
,E/GBMv2   (  343): DFP En is all cleared set to be enabled
E/GBMv2   (  343): Set value is all cleared set the max
I/GBMv2   (  343): DFP Enabled. Ignore VFP set
,D/jxcore_app_log( 6138): JniHelper::setJavaVM(0xb487c280), pthread_self() = -1435200256,
,I/chromium( 6138): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/CloudHub( 2204): [CLIENT][CloudHubClientFactory$1|onTick] Until finished: 19986
,W/jxcore-log( 6138): Initializing JXcore engine
W/jxcore-log( 6138): JXcore engine is ready
,W/Thread-688( 6196): type=1400 audit(0.0:148): avc: denied { ioctl } for path="socket:[9335]" dev="sockfs" ino=9335 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
W/Thread-688( 6196): type=1400 audit(0.0:149): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2864 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
,W/Thread-688( 6196): type=1400 audit(0.0:150): avc: denied { ioctl } for path="socket:[10596]" dev="sockfs" ino=10596 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
W/Thread-688( 6196): type=1400 audit(0.0:151): avc: denied { ioctl } for path="/cust" dev="mmcblk0p42" ino=2 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=dir
W/Thread-688( 6196): type=1400 audit(0.0:152): avc: denied { ioctl } for path="socket:[27574]" dev="sockfs" ino=27574 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
W/jxcore-log( 6138): Starting JXcore engine
,W/jxcore-log( 6138): Platform android
W/jxcore-log( 6138): 
W/jxcore-log( 6138): Process ARCH arm
W/jxcore-log( 6138): 
,I/jxcore-log( 6138): JXcore Cordova bridge is ready!
I/jxcore-log( 6138): 
,W/jxcore-log( 6138): JXcore engine is started
,I/jxcore-log( 6138): Toggling radios to true
I/jxcore-log( 6138): 
,D/BluetoothManagerService( 1030): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1030): enable():  mBluetooth =null mBinding = false
,D/LocationManagerService( 1030): getAllProviders()=[passive, gps, network]
D/Ulp_jni ( 1030): JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
D/Ulp_jni ( 1030): JNI:system_update. Event-4
D/BluetoothManagerService( 1030): Message: 1
D/BluetoothManagerService( 1030): MESSAGE_ENABLE: mBluetooth = null
D/WifiService( 1030): New client listening to asynchronous messages
,I/ActivityManager( 1030): Start proc com.android.bluetooth for service com.android.bluetooth/.btservice.AdapterService: pid=6202 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008, 4002, 1023} abi=armeabi-v7a
D/WifiServiceImplEx( 1030): setWifiEnabled: true pid=6138, uid=10311, package= com.test.thalitest, App Lable : ThaliTest
D/WifiService( 1030): setWifiEnabled: true pid=6138, uid=10311
E/WifiService( 1030): Invoking mWifiStateMachine.setWifiEnabled
,D/LocationManagerService( 1030): getAllProviders()=[passive, gps, network]
D/Ulp_jni ( 1030): JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 1,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
D/Ulp_jni ( 1030): JNI:system_update. Event-4
,E/WifiStateMachine( 1030):  InitialState CMD_START_SUPPLICANT 0 0
I/LGFTMITEM( 1030): [GET_FTM][id=6], offset=12288
D/WifiServiceImplEx( 1030): disconnect pid=6138, uid=10311, packageName=com.test.thalitest
D/WifiServiceImplEx( 1030): reconnect pid=6138, uid=10311, packageName=com.test.thalitest
E/WifiUtil( 1030): wfc_util_ffile_check_copy(): pid[1030] pDestFName[/data/misc/wifi/WCNSS_qcom_cfg.ini] pSourceFName[/system/etc/wifi/WCNSS_qcom_cfg.ini]
E/WifiUtil( 1030): wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
E/WifiUtil( 1030): wfc_util_ffile_check_copy(): pid[1030] pDestFName[/data/misc/wifi/WCNSS_qcom_wlan_nv.bin] pSourceFName[/system/etc/wifi/WCNSS_qcom_wlan_nv.bin]
E/WifiUtil( 1030): wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
I/WifiUtil( 1030): Intf0MacAddress=C49A027B60AC
E/WifiHW  ( 1030): unknown target_country: EU , set to default
E/WifiHW  ( 1030): [wifi_ensure_config_files] default country1 = GB
E/WifiHW  ( 1030): [wifi_ensure_config_files] default country2 = GB
I/WifiUtil( 1030): gEnableBmps=1
I/jxcore-log( 6138): Radios toggled
I/jxcore-log( 6138): 
I/jxcore-log( 6138): My device name is: LGE-LG-D855
I/jxcore-log( 6138): 
,W/ResourcesManager( 6202): Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
,W/ResourcesManager( 6202): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 6202): Asset path '/system/framework/com.qcom.bluetooth.jar' does not exist or contains no resources.
W/ResourcesManager( 6202): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
D/BluetoothAdapterApp( 6202): Loading JNI Library
,D/SoftapController(  314): Softap fwReload - Ok
D/CommandListener(  314): Setting iface cfg
D/CommandListener(  314): Trying to bring down wlan0
D/CommandListener(  314): Clearing all IP addresses on wlan0
,D/Tethering( 1030): sendTetherStateChangedBroadcast 1, 0, 0
D/Tethering( 1030): InitialState.processMessage what=4
D/Tethering( 1030): sendTetherStateChangedBroadcast 0, 0, 0
D/libc-netbsd(  314): default dns: query_ipv6=0, query_ipv4=0
D/DSQN    ( 1030): DNSproblemNotiEnabled is disabled ignore DNS fail CB
,D/BluetoothAdapterApp( 6202): REFCOUNT: Constructed com.android.bluetooth.btservice.AdapterApp@377ac05f Instance Count = 1
E/WifiHW  ( 1030): Cannot open "/system/etc/wifi/autojoinconfig.txt": No such file or directory
E/WifiStateMachine( 1030): Couldn't get getWiFiOffloadingIface : 
E/WifiStateMachine( 1030): useWiFiOffloading() : false
E/WifiStateMachine( 1030): CONFIG_LGE_WLAN_PATH : true
W/wpa_supplicant( 6246): type=1400 audit(0.0:153): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6508 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
W/wpa_supplicant( 6246): type=1400 audit(0.0:154): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6508 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,I/wpa_supplicant( 6246): Successfully initialized wpa_supplicant
I/ActivityManager( 1030): Start proc com.android.settings for broadcast com.android.settings/.deviceinfo.UsbSettingsReceiver: pid=6247 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
D/WifiMonitor( 1030): startMonitoring(wlan0) with mConnected = false
D/WifiMonitor( 1030): connecting to supplicant
,D/BluetoothAdapterApp( 6202): onCreate
V/WfdStateTracker( 1974): WfdStateTracker handleDirectStateChangedEvent: 1
,D/StatusBar.NetworkController( 1461): refreshViews: Data not connected!! Set no data type icon / Roaming
I/WifiServerServiceExt( 1030): WIFI_STATE_CHANGED_ACTION [2]
I/wpa_supplicant( 6246): rfkill: Cannot open RFKILL control device
I/wpa_supplicant( 6246): [LGE_PATCH] unset P2P_CAPABLE to ifname wlan0
,D/ProfileConfigQcom( 6202): [BTUI] HeadsetService is supported
D/ProfileConfigQcom( 6202): Adding HeadsetService
D/ProfileConfigQcom( 6202): [BTUI] A2dpService is supported
D/ProfileConfigQcom( 6202): Adding A2dpService
D/ProfileConfigQcom( 6202): [BTUI] HidService is supported
,D/ProfileConfigQcom( 6202): Adding HidService
D/ProfileConfigQcom( 6202): [BTUI] HealthService is supported
D/ProfileConfigQcom( 6202): Adding HealthService
D/LGBluetoothFeatureConfig( 6202): isSupportPan() :  mTargetOp=OPEN
D/ProfileConfigQcom( 6202): [BTUI] PanService is supported
D/ProfileConfigQcom( 6202): Adding PanService
D/ProfileConfigQcom( 6202): [BTUI] GattService is supported
D/ProfileConfigQcom( 6202): Adding GattService
D/ProfileConfigQcom( 6202): [BTUI] BluetoothMapService is supported
D/ProfileConfigQcom( 6202): Adding BluetoothMapService
D/ProfileConfigQcom( 6202): [BTUI] HeadsetClientService is NOT supported
,D/BluetoothManagerService( 1030): Message: 20
D/BluetoothManagerService( 1030): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@3ba7e246:true
D/BluetoothAdapterState( 6202): make
I/LGFMServiceAdapter( 6202): [FM] LGFMServiceAdapter : create
I/bluedroid-qcom( 6202): init
I/BluetoothAdapterState( 6202): Entering OffState
,I/bte_conf( 6202): bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
I/bte_conf( 6202): bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
E/bt_osi_config( 6202): config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
I/bte_conf( 6202): bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
D/BTIF_CORE( 6202): [BTUI] lge_load_bluetooth_address
I/bluedroid-qcom( 6202): get_profile_interface socket
I/GKI_LINUX( 6202): gki_task_entry task_id=1 [BTIF] starting
W/bdaddr_loader( 6269): type=1400 audit(0.0:155): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6508 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
W/bdaddr_loader( 6269): type=1400 audit(0.0:156): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6508 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
I/bluedroid-qcom( 6202): get_profile_interface map_client
D/BluetoothAdapterProperties( 6202): Address is:58:3F:54:73:64:C0
D/lge_bdaddr_loader( 6269): [BTUI] bdaddr_loader ::: START
D/lge_bdaddr_loader( 6269): [BTUI] bluetooth_load_bdaddress
I/LGFTMITEM( 6269): [GET_FTM][id=8], offset=16384
D/lge_bdaddr_loader( 6269): [BTUI] bdaddr to set in property : 58:3F:54:73:64:C0
D/BluetoothAdapterProperties( 6202): Name is: G3-1
D/BluetoothManagerService( 1030): Bluetooth Adapter name changed to G3-1
D/BluetoothManagerService( 1030): Stored Bluetooth name: G3-1
D/BluetoothManagerService( 1030): BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
D/BluetoothManagerService( 1030): Message: 40
D/BluetoothManagerService( 1030): MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
,W/ResourcesManager( 6247): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6247): Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
W/ResourcesManager( 6247): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 6247): Asset path '/system/framework/com.lge.bluetooth.jar' does not exist or contains no resources.
W/ResourcesManager( 6247): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
W/ResourcesManager( 6247): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
I/bluedroid-qcom( 6202): config_hci_snoop_log
E/lge_bdaddr_loader( 6269): [BTUI] bluetooth_load_bdaddress : OK => 58:3F:54:73:64:C0
D/lge_bdaddr_loader( 6269): [BTUI] bdaddr_loader ::: END
D/BluetoothManagerService( 1030): Calling onBluetoothServiceUp callbacks
D/BluetoothManagerService( 1030): Broadcasting onBluetoothServiceUp() to 7 receivers.
V/LGMDMManagerInternal( 6202): Create singleton instance
,I/wpa_supplicant( 6246): rfkill: Cannot open RFKILL control device
,D/UsbSettingsReceiver( 6247): [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
,D/UsbSettingsReceiver( 6247): [AUTORUN] sys.usb.config = ptp_only,adb
D/UsbSettingsReceiver( 6247): [AUTORUN] sys.usb.state = ptp_only,adb
D/UsbSettingsReceiver( 6247): [AUTORUN] persist.sys.usb.config = ptp_only,adb
D/UsbSettingsReceiver( 6247): [AUTORUN] onReceive() : app userid = 0, current userid = 0
,D/BluetoothAdapterState( 6202): CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
D/BluetoothAdapterProperties( 6202): Setting state to 11
I/BluetoothAdapterState( 6202): Bluetooth adapter state changed: 10-> 11
,I/LGBluetoothServiceJni( 6202): classInitNative: succeeds
D/UsbSettingsControl( 6247): [AUTORUN] getUsbConnected() : connected=true
D/BluetoothManagerService( 1030): Message: 60
D/BluetoothManagerService( 1030): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
D/BluetoothManagerService( 1030): Bluetooth State Change Intent: 10 -> 11
D/UsbSettingsReceiver( 6247): [AUTORUN] onReceive() : availableList=[wlan0]
D/UsbSettingsReceiver( 6247): [AUTORUN] onReceive() : activeList=[]
D/UsbSettingsReceiver( 6247): [AUTORUN] onReceive() : errorList=[]
D/UsbSettingsControl( 6247): [AUTORUN] isAutorunTimer() : mAutorunChanging=false
D/UsbSettingsReceiver( 6247): [AUTORUN] onReceive() : TetherState Changed=wlan0
D/UsbSettingsControl( 6247): [AUTORUN] setTetherStatus() : status=false
D/LGBluetoothAPIService( 1974): [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
I/[SystemUI]BluetoothHandler( 1461): Receive : BluetoothAdapter.ACTION_STATE_CHANGED
D/BluetoothBondStateMachine( 6202): make
I/ActivityManager( 1030): Killing 5486:com.lge.appbox.client/u0a11 (adj 15): empty #17
D/BluetoothAdapterService( 6202): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@391cf1d6
D/LGBluetoothServiceAdapter( 6202): [BTUI] check adapter is available - false.
D/BluetoothAdapterService( 6202): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@391cf1d6
D/LGBluetoothServiceAdapter( 6202): [BTUI] check adapter is available - true : set adapter available.
,D/LGBluetoothSettingsDBObserver( 6202): [BTUI] register observer for LG device name DB
I/BluetoothBondStateMachine( 6202): StableState(): Entering Off State
I/wpa_supplicant( 6246): [LGE_WLAN_PATCH]P2P 5GHz support level:2(0:no 1:gconly 2:gconly_UNII1 3:full)
,I/wpa_supplicant( 6246): p2p0: CTRL-EVENT-AVOID-FREQ ranges=
I/wpa_supplicant( 6246): wlan0: CTRL-EVENT-SCAN-STARTED 
E/WifiStateMachine( 1030):  SupplicantStartingState CMD_DISCONNECT 0 0
E/WifiStateMachine( 1030):  DefaultState CMD_DISCONNECT 0 0
E/WifiStateMachine( 1030):  SupplicantStartingState CMD_RECONNECT 0 0
E/WifiStateMachine( 1030):  DefaultState CMD_RECONNECT 0 0
E/WifiStateMachine( 1030):  SupplicantStartingState CMD_SET_OPERATIONAL_MODE 1 0
E/WifiStateMachine( 1030):  SupplicantStartingState CMD_START_DRIVER 0 0
E/WifiStateMachine( 1030):  SupplicantStartingState CMD_SET_HIGH_PERF_MODE 0 0
E/WifiStateMachine( 1030):  DefaultState CMD_SET_HIGH_PERF_MODE 0 0
E/WifiStateMachine( 1030):  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1030):  DefaultState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1030):  SupplicantStartingState SUP_CONNECTION_EVENT 0 0
D/WifiNative-wlan0( 1030): doString: [DRIVER MACADDR]
D/WifiMonitor( 1030): Event [IFNAME=p2p0 CTRL-EVENT-AVOID-FREQ ranges=]
D/WifiMonitor( 1030): Dropping event because (p2p0) is stopped
D/WifiMonitor( 1030): Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
,E/WifiMonitor( 1030): WifiMonitor:wlan0 cnt=0 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1030): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1030): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
D/WifiNative-wlan0( 1030):    returned Macaddr = c4:9a:02:7b:60:ac
D/WifiStateMachine( 1030): MAC Addr from driver = c4:9a:02:7b:60:ac
D/WifiOffDelayIfNotUsed( 1030): setPowerSaveActivated(false)
I/art     ( 1030): Explicit concurrent mark sweep GC freed 28310(1427KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 43MB/65MB, paused 1.903ms total 100.743ms
,E/BluetoothAdapterService( 6202): File transfer profiles supported!!
V/BluetoothPbapReceiver( 6202): PbapReceiver onReceive 
,V/BluetoothPbapReceiver( 6202): ***********action = android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothPbapReceiver( 6202): ***********state = 11
W/libprocessgroup( 1030): failed to open /acct/uid_10011/pid_5486/cgroup.procs: No such file or directory
E/WifiStateMachine( 1030): Couldn't get getWiFiOffloadingIface : 
E/WifiStateMachine( 1030): useWiFiOffloading() : false
E/WifiStateMachine( 1030): CONFIG_LGE_WLAN_PATH : true
D/WifiNative-wlan0( 1030): doBoolean: SET update_config 1
D/WifiNative-wlan0( 1030): SET update_config 1: returned true
,D/WifiConfigStore( 1030): Loading config and enabling all networks 
D/WifiNative-wlan0( 1030): doString: [LIST_NETWORKS]
D/WifiNative-wlan0( 1030):    returned network id / ssid / bssid / flags 0	NG700	any	
E/WifiConfigStore( 1030): readNetworkVariablesFromSupplicantFile key=psk
W/Settings( 1030): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1030): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/HeadsetService( 6202): Received start request. Starting profile...
D/WfdService( 1974): Waiting for WifiP2p enabling
D/BluetoothHeadset( 1867): Proxy object connected
I/LGBluetoothHeadsetServiceJni( 6202): classInitNative: succeeds
D/BluetoothHeadset( 1867): Proxy object connected
D/BluetoothHeadset( 1867): Proxy object connected
D/StatusBar.NetworkController( 1461): refreshViews: Data not connected!! Set no data type icon / Roaming
D/LGBluetoothHfpAdapter( 6202): Version 1.6
E/BluetoothAdapterService( 6202): File transfer profiles supported!!
D/LGBluetoothFeatureConfig( 6202): isPrivacyLogsEnabled : true
D/UsbSettingsReceiver( 6247): [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
D/UsbSettingsReceiver( 6247): [AUTORUN] sys.usb.config = ptp_only,adb
D/UsbSettingsReceiver( 6247): [AUTORUN] sys.usb.state = ptp_only,adb
D/UsbSettingsReceiver( 6247): [AUTORUN] persist.sys.usb.config = ptp_only,adb
I/BluetoothHeadsetServiceJni( 6202): classInitNative: succeeds
D/HeadsetStateMachine( 6202): make
E/WifiConfigStore( 1030): readNetworkVariableFromSupplicantFile ssid=["NG700"] key=psk
E/WifiConfigStore( 1030): Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
,I/ActivityManager( 1030): Start proc com.lge.lifetracker for broadcast com.lge.lifetracker/.receiver.HealthDeviceReceiver: pid=6274 uid=10037 gids={50037, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
,D/WifiStateMachine( 1030): enableVerboseLogging : level 2
I/WifiServerServiceExt( 1030): WIFI_STATE_CHANGED_ACTION [3]
D/WifiNative-wlan0( 1030): doBoolean: SET device_name g3_global_com
D/WifiNative-wlan0( 1030): SET device_name g3_global_com: returned true
D/WifiNative-wlan0( 1030): doBoolean: SET manufacturer LGE
D/WifiNative-wlan0( 1030): SET manufacturer LGE: returned true
D/WifiNative-wlan0( 1030): doBoolean: SET model_name LG-D855
D/WifiNative-wlan0( 1030): SET model_name LG-D855: returned true
I/WifiServerServiceExt( 1030): batteryPsActivateMsgHandler : state:0 event:3
D/WifiNative-wlan0( 1030): doBoolean: SET model_number LG-D855
D/WifiNative-wlan0( 1030): SET model_number LG-D855: returned true
D/BluetoothHeadset( 1030): Proxy object connected
D/WifiNative-wlan0( 1030): doBoolean: SET serial_number LGD8553bed2d08
E/BluetoothAdapterService( 6202): File transfer profiles supported!!
D/WifiNative-wlan0( 1030): SET serial_number LGD8553bed2d08: returned true
D/WifiNative-wlan0( 1030): doBoolean: SET config_methods physical_display virtual_push_button
D/WifiNative-wlan0( 1030): SET config_methods physical_display virtual_push_button: returned true
D/UsbSettingsReceiver( 6247): [AUTORUN] onReceive() : app userid = 0, current userid = 0
D/WifiNative-wlan0( 1030): doBoolean: SET device_type 10-0050F204-5
D/WifiNative-wlan0( 1030): SET device_type 10-0050F204-5: returned true
D/WifiStateMachine( 1030): Setting OUI to DA-A1-19
D/WifiNative-wlan0( 1030): doBoolean: SCAN_INTERVAL 120
D/WifiNative-wlan0( 1030): SCAN_INTERVAL 120: returned true
D/WifiNative-HAL( 1030): Setting external_sim to 1
D/WifiNative-wlan0( 1030): doBoolean: SET external_sim 1
D/WifiNative-wlan0( 1030): SET external_sim 1: returned true
D/LgDataFeature( 6202): LgDataFeature() Constructor: none
I/WifiNative-HAL( 1030): startHal
E/wifi    ( 1030): getStaticLongField sWifiHalHandle 0x988e08dc
D/LgDataFeature( 6202): LgDataFeature() Constructor Done, null
E/WifiHAL ( 1030): Could not connect handle
D/wifi    ( 1030): halHandle = 0x0, mVM = 0xb487c280, mCls = 0x20216e
I/WifiNative-HAL( 1030): Could not start hal
D/WifiStateMachine( 1030): Setting OUI to DA-A1-19
I/WifiNative-HAL( 1030): startHal
E/wifi    ( 1030): getStaticLongField sWifiHalHandle 0x988e085c
E/WifiHAL ( 1030): Could not connect handle
D/wifi    ( 1030): halHandle = 0x0, mVM = 0xb487c280, mCls = 0x402116
I/WifiNative-HAL( 1030): Could not start hal
D/WifiNative-wlan0( 1030): doBoolean: STA_AUTOCONNECT 1
E/BluetoothAdapterService( 6202): File transfer profiles supported!!
D/WifiNative-wlan0( 1030): STA_AUTOCONNECT 1: returned true
D/WifiNative-wlan0( 1030): doBoolean: DRIVER BTCOEXSCAN-STOP
I/wpa_supplicant( 6246): wpa_driver_nl80211_ext_driver_cmd BTCOEXSCAN-STOP
D/WfdsService( 1974): Supplicant Connection state is changed : true
D/WfdsService( 1974): DefaultState - WIFI_SUPPLICANT_CONNECTED
D/WfdsService( 1974): Set the WFDS Monitor: true
D/WifiNative-wlan0( 1030): DRIVER BTCOEXSCAN-STOP: returned true
D/WfdsMonitor( 1974): WfdsMonitorThread create
D/WfdsMonitor( 1974): WFDS Monitor is created and started
D/WfdsService( 1974): WiFi: Supplicant connection re-established
,D/HeadsetStateMachine( 6202): max_hf_connections = 1
I/bluedroid-qcom( 6202): get_profile_interface handsfree
V/ToneGenerator( 6202): ToneGenerator constructor: streamType=8, volume=1.000000
I/StatusBar.NetworkController( 1461): networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1461): mWifiConnected = false, mWifiLevel = 0
V/AudioPolicyService(  318): registerClient() client 0xb101dd80, uid 1002
W/Settings( 6045): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
V/AudioPolicyManager(  318): getOutput() device 2, stream 8, samplingRate 0, format 0, channelMask 3, flags 0
V/AudioPolicyManagerEx(  318): AudioPolicyManagerEx: getOutputForDevice
V/AudioPolicyManagerEx(  318): getOutput() returns output 2
V/AudioSystem( 6202): getOutputSamplingRate() no output descriptor for output 2 in gOutputs
D/WifiHS20( 1030): hidePasspointNotification off =false
V/AudioFlinger(  318): registerClient() client 0xb1433058, pid 6202
V/ToneGenerator( 6202): Create Track: 0xb4928080
V/AudioTrack( 6202): set(): streamType 8, sampleRate 0, format 0x1, channelMask 0x1, frameCount 0, flags #4, notificationFrames 0, sessionId 0, transferType 1
V/AudioTrack( 6202): set() streamType 8, sampleRate 0, format 1, frameCount 0, flags 0004
V/AudioPolicyManager(  318): getOutputForAttr() usage=3, content=4, tag= flags=00000000
V/AudioPolicyManager(  318): getOutputForAttr() device 2, samplingRate 0, format 0, channelMask 3, flags 0
V/AudioPolicyManagerEx(  318): AudioPolicyManagerEx: getOutputForDevice
V/AudioPolicyManagerEx(  318): getOutput() returns output 2
D/StatusBar.NetworkController( 1461): refreshViews: Data not connected!! Set no data type icon / Roaming
V/AudioSystem(  318): ioConfigChanged() event 0, ioHandle 4
V/AudioSystem(  318): ioConfigChanged() opening already existing output! 4
W/Settings( 1030): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1030): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
V/AudioSystem( 1030): ioConfigChanged() event 0, ioHandle 4
V/AudioSystem( 1030): ioConfigChanged() opening already existing output! 4
D/WifiOffDelayIfNotUsed( 1030): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
V/AudioSystem( 6202): ioConfigChanged() event 0, ioHandle 4
V/AudioSystem( 6202): ioConfigChanged() new output samplingRate 48000, format 0x1 channel mask 0x3 frameCount 960 latency 80
V/AudioSystem( 1867): ioConfigChanged() event 0, ioHandle 4
V/AudioSystem( 1867): ioConfigChanged() opening already existing output! 4
V/AudioSystem( 1461): ioConfigChanged() event 0, ioHandle 4
V/AudioSystem( 1461): ioConfigChanged() opening already existing output! 4
V/AudioSystem( 6202): getOutputSamplingRate() no output descriptor for output 2 in gOutputs
V/AudioSystem( 2204): ioConfigChanged() event 0, ioHandle 4
V/AudioSystem( 2204): ioConfigChanged() opening already existing output! 4
V/AudioSystem( 3258): ioConfigChanged() event 0, ioHandle 4
V/AudioSystem( 3258): ioConfigChanged() opening already existing output! 4
V/AudioSystem(  318): ioConfigChanged() event 0, ioHandle 2
V/AudioSystem(  318): ioConfigChanged() opening already existing output! 2
V/AudioSystem( 1030): ioConfigChanged() event 0, ioHandle 2
V/AudioSystem( 1030): ioConfigChanged() opening already existing output! 2
V/AudioSystem( 1461): ioConfigChanged() event 0, ioHandle 2
V/AudioSystem( 1461): ioConfigChanged() opening already existing output! 2
V/AudioSystem( 2204): ioConfigChanged() event 0, ioHandle 2
V/AudioSystem( 2204): ioConfigChanged() opening already existing output! 2
D/WifiNative-wlan0( 1030): doBoolean: DRIVER RXFILTER-STOP
I/wpa_supplicant( 6246): wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
V/AudioSystem( 6202): ioConfigChanged() event 0, ioHandle 2
D/WifiNative-wlan0( 1030): DRIVER RXFILTER-STOP: returned true
V/AudioSystem( 6202): ioConfigChanged() new output samplingRate 48000, format 0x5 channel mask 0x3 frameCount 960 latency 50
D/WifiNative-wlan0( 1030): doBoolean: DRIVER RXFILTER-REMOVE 3
I/wpa_supplicant( 6246): wpa_driver_nl80211_ext_driver_cmd RXFILTER-REMOVE 3
E/BluetoothAdapterService( 6202): File transfer profiles supported!!
V/AudioSystem( 1867): ioConfigChanged() event 0, ioHandle 2
V/AudioSystem( 1867): ioConfigChanged() opening already existing output! 2
D/UsbSettingsControl( 6247): [AUTORUN] getUsbConnected() : connected=true
D/UsbSettingsReceiver( 6247): [AUTORUN] onReceive() : availableList=[]
D/UsbSettingsReceiver( 6247): [AUTORUN] onReceive() : activeList=[]
D/UsbSettingsReceiver( 6247): [AUTORUN] onReceive() : errorList=[]
V/AudioSystem( 3258): ioConfigChanged() event 0, ioHandle 2
V/AudioSystem( 3258): ioConfigChanged() opening already existing output! 2
D/WifiNative-wlan0( 1030): DRIVER RXFILTER-REMOVE 3: returned true
I/AudioFlinger(  318): isAudioPlaybackHookOn() false
D/WifiNative-wlan0( 1030): doBoolean: DRIVER RXFILTER-START
V/AudioPolicyManager(  318): getOutputForAttr() usage=3, content=4, tag= flags=00000000
I/wpa_supplicant( 6246): wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
V/AudioPolicyManager(  318): getOutputForAttr() device 2, samplingRate 48000, format 1, channelMask 1, flags 4
V/AudioPolicyManagerEx(  318): AudioPolicyManagerEx: getOutputForDevice
V/AudioPolicyManagerEx(  318): getOutput() returns output 2
V/AudioSystem( 6202): getLatency() output 2, latency 50
V/AudioSystem( 6202): getFrameCount() output 2, frameCount 960
V/AudioTrack( 6202): createTrack_l() output 2 afLatency 50
V/AudioFlinger(  318): [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
V/AudioFlinger(  318): [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
V/AudioFlinger(  318): [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
V/AudioFlinger(  318): [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
V/AudioFlinger(  318): createTrack() lSessionId: 16
V/AudioTrack( 6202): AUDIO_OUTPUT_FLAG_FAST successful; frameCount 480
V/AudioFlinger(  318): acquiring 16 from 6202, for 6202
V/AudioFlinger(  318):  added new entry for 16
V/ToneGenerator( 6202): ToneGenerator INIT OK, time: 117648
D/BluetoothAdapterService( 6202): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@391cf1d6
D/HeadsetStateMachine( 6202): Enter Disconnected: -2, size: 0
D/HeadsetPhoneState( 6202): [BTUI] listenForPhoneState : start = false
D/LGBluetoothHfpManager( 6202): [BTUI] listenForMultiSimPhoneState : start = false
D/HeadsetStateMachine( 6202): [BTUI] change sampling rate to 8000 when device is disconnected
D/BluetoothAdapterService( 6202): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@391cf1d6
V/AudioFlinger(  318): setParameters(): io 0, keyvalue bt_samplerate=8000, calling pid 6202
D/audio_hw_primary(  318): adev_set_parameters: enter: bt_samplerate=8000
V/voice   (  318): voice_set_parameters: enter: bt_samplerate=8000
V/compress_voip(  318): voice_extn_compress_voip_set_parameters: enter: bt_samplerate=8000
V/compress_voip(  318): voice_extn_compress_voip_set_parameters: exit
V/voice   (  318): voice_set_parameters: exit with code(0)
V/msm8974_platform_lge(  318): LGE_platform_set_parameters: enter: bt_samplerate=8000
V/msm8974_platform(  318): platform_set_parameters: enter: bt_samplerate=8000
V/msm8974_platform(  318): platform_set_parameters: exit with code(0)
V/lge_audio_loopback(  318): lge_platform_set_loopback_parameters: enter: 
V/audio_hw_primary(  318): adev_set_parameters: exit with code(0)
E/audio_a2dp_hw(  318): adev_set_parameters: ERROR: set param called even when stream out is null
V/ToneGenerator( 6202): ToneGenerator destructor
V/ToneGenerator( 6202): stopTone
V/ToneGenerator( 6202): Delete Track: 0xb4928080
V/AudioTrack( 6202): ~AudioTrack, releasing session id from 6202 on behalf of 6202
D/A2dpService( 6202): Received start request. Starting profile...
V/AudioFlinger(  318): releasing 16 from 6202 for 6202
V/AudioFlinger(  318):  decremented refcount to 0
V/AudioFlinger(  318): purging stale effects
V/AudioPolicyService(  318): AudioCommandThread() adding release output 2
V/AudioPolicyService(  318): inserting command: 6 at index 0, num commands 0
V/AudioFlinger(  318): PlaybackThread::Track destructor
V/AudioPolicyService(  318): AudioCommandThread() waking up
V/AudioFlinger(  318): removeClient_l() pid 6202, calling pid 318
V/AudioPolicyService(  318): AudioCommandThread() processing release output 2
V/AudioPolicyManager(  318): releaseOutput() 2
V/AudioPolicyService(  318): AudioCommandThread() going to sleep
I/BluetoothAvrcpServiceJni( 6202): classInitNative: succeeds
D/UsbSettingsControl( 6247): [AUTORUN] isAutorunTimer() : mAutorunChanging=false
D/UsbSettingsControl( 6247): [AUTORUN] setTetherStatus() : status=false
V/Avrcp   ( 6202): make
D/Avrcp   ( 6202): [BTUI] Use Native AVRCP : init jni
I/bluedroid-qcom( 6202): get_profile_interface avrcp
W/Process ( 1030): Unable to open /proc/6285/status
D/BluetoothA2dp( 1030): Proxy object connected
D/WifiNative-wlan0( 1030): DRIVER RXFILTER-START: returned true
D/WifiNative-wlan0( 1030): doBoolean: DRIVER RXFILTER-STOP
I/wpa_supplicant( 6246): wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
E/BluetoothAdapterService( 6202): File transfer profiles supported!!
D/WifiNative-wlan0( 1030): DRIVER RXFILTER-STOP: returned true
D/WifiNative-wlan0( 1030): doBoolean: DRIVER RXFILTER-REMOVE 2
I/wpa_supplicant( 6246): android_multicast_filter_startstop : multicast filter set
D/WifiNative-wlan0( 1030): DRIVER RXFILTER-REMOVE 2: returned true
D/WifiNative-wlan0( 1030): doBoolean: DRIVER RXFILTER-START
I/wpa_supplicant( 6246): wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
E/CtrlSupplicant( 1974): Access OK "@android:wpa_wlan0"
E/CtrlSupplicant( 1974): Succeed to open control connection
E/CtrlSupplicant( 1974): Succeed to open monitor connection
D/WifiNative-wlan0( 1030): DRIVER RXFILTER-START: returned true
E/WifiNative: ( 1030): [117,645,568 us] RECONNECT  stack:logDbg - reconnect - enter - invokeEnterMethods - performTransitions
D/WifiNative-wlan0( 1030): doBoolean: RECONNECT
D/WfdsMonitor( 1974): Supplicant connection established
D/WfdsService( 1974): Connected to the supplicant for wfds
D/WifiNative-wlan0( 1030): RECONNECT: returned true
D/WifiNative-wlan0( 1030): doString: [STATUS]
D/WifiMonitor( 1030): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
E/WifiMonitor( 1030): WifiMonitor:wlan0 cnt=1 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
D/WifiNative-wlan0( 1030):    returned wpa_state=SCANNING p2p_device_address=02:9a:02:7b:60:ac address=c4:9a:02:7b:60:ac uuid=530d3fd0-1ba3-5409-a336-ff4e42af59a2
D/WifiNative-wlan0( 1030): doBoolean: DRIVER SETSUSPENDMODE 1
I/wpa_supplicant( 6246): wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 1
D/WifiNative-wlan0( 1030): DRIVER SETSUSPENDMODE 1: returned true
D/WifiNative-wlan0( 1030): doBoolean: SET ps 1
D/WifiNative-wlan0( 1030): SET ps 1: returned true
D/LGWifiP2pService( 1030): P2pDisabledState{ when=-1ms what=131203 target=com.android.internal.util.StateMachine$SmHandler }
,D/CommandListener(  314): Setting iface cfg
D/CommandListener(  314): Trying to bring up p2p0
D/WifiMonitor( 1030): startMonitoring(p2p0) with mConnected = true
D/LGWifiP2pService( 1030): P2pEnablingState
D/LGWifiP2pService( 1030): P2pEnablingState{ when=0 what=147457 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1030): P2p socket connection successful
D/LGWifiP2pService( 1030): P2pEnabledState
D/WifiService( 1030): New client listening to asynchronous messages
I/ActivityManager( 1030): Start proc com.lge.formmanager for broadcast com.lge.formmanager/.FormServiceReceiver: pid=6294 uid=10026 gids={50026, 9997, 3003, 1028} abi=armeabi-v7a
D/LGWifiP2pService( 1030): sending p2p connection changed broadcast
E/WifiStateMachine( 1030):  DisconnectedState CMD_SET_OPERATIONAL_MODE 1 0
E/WifiStateMachine( 1030):  DisconnectedState CMD_START_DRIVER 0 0
E/WifiStateMachine( 1030):  ConnectModeState CMD_START_DRIVER 0 0
E/WifiStateMachine( 1030):  DriverStartedState CMD_START_DRIVER 0 0
E/WifiStateMachine( 1030):  DisconnectedState what:132106 1 0
E/WifiStateMachine( 1030):  ConnectModeState what:132106 1 0
E/BluetoothAdapterService( 6202): File transfer profiles supported!!
E/WifiStateMachine( 1030):  DriverStartedState what:132106 1 0
I/WifiServerServiceExt( 1030): setWifiDualbandAPConnection band : 1
E/wpa_supplicant( 6246): nWIFIDualbandAPConnection: 1
D/WifiScanningService( 1030): SCAN_AVAILABLE : 3
D/RttService( 1030): SCAN_AVAILABLE : 3
D/WifiScanningService( 1030): DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
I/WifiNative-HAL( 1030): startHal
E/wifi    ( 1030): getStaticLongField sWifiHalHandle 0x94e6799c
E/WifiHAL ( 1030): Could not connect handle
E/WifiStateMachine( 1030):  DisconnectedState what:132096 -100 0
D/wifi    ( 1030): halHandle = 0x0, mVM = 0xb487c280, mCls = 0x602076
I/WifiNative-HAL( 1030): Could not start hal
E/WifiScanningService( 1030): could not start HAL
D/RttService( 1030): DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiStateMachine( 1030):  ConnectModeState what:132096 -100 0
E/WifiStateMachine( 1030):  DriverStartedState what:132096 -100 0
I/WifiServerServiceExt( 1030): set CMD_DISCONNECT_RSSI_LVL : -100
E/wpa_supplicant( 6246): disconnect_rssi_lvl: -100
E/WifiStateMachine( 1030):  DisconnectedState CMD_SET_COUNTRY_CODE 1 0 cz
E/WifiStateMachine( 1030):  ConnectModeState CMD_SET_COUNTRY_CODE 1 0 cz
E/WifiStateMachine( 1030):  DriverStartedState CMD_SET_COUNTRY_CODE 1 0 cz
D/WifiNative-wlan0( 1030): doBoolean: DRIVER COUNTRY CZ
V/WfdStateTracker( 1974): WfdStateTracker handleDirectStateChangedEvent: 2
D/WfdsService( 1974): WifiP2pState is changed : true
I/wpa_supplicant( 6246): wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
D/WfdsService( 1974): Receive the WFDS_ENABLE Method
D/WfdsService( 1974): Set the WFDS Monitor: true
D/WfdsService( 1974): Connected to the supplicant for wfds
I/wpa_supplicant( 6246): wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
I/wpa_supplicant( 6246): [LGE_PATCH] driver_cmd() country:CZ
I/wpa_supplicant( 6246): p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
D/WifiNative-p2p0( 1030): doBoolean: SET persistent_reconnect 1
I/wpa_supplicant( 6246): p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
D/WifiMonitor( 1030): Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
E/WifiMonitor( 1030): WifiMonitor:wlan0 cnt=2 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
E/WifiMonitor( 1030): handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
E/WifiMonitor( 1030): handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
D/WifiMonitor( 1030): Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
E/WifiMonitor( 1030): WifiMonitor:p2p0 cnt=3 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
E/WifiMonitor( 1030): handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
E/WifiMonitor( 1030): handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
D/WifiMonitor( 1030): Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
E/WifiMonitor( 1030): WifiMonitor:p2p0 cnt=4 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
E/WifiMonitor( 1030): handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
E/WifiMonitor( 1030): handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
D/WfdsMonitor( 1974): Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
D/WfdsMonitor( 1974): Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
D/WfdsJNI ( 1974): doCommand: WFDS_SET TRUE
I/wpa_supplicant( 6246): WFDS: wfds_supplicant_wfds_cmd: cmd = SET TRUE
D/WfdsJNI ( 1974): doCommand: WFDS_GET_MAC_ADDRESS
I/wpa_supplicant( 6246): WFDS: wfds_supplicant_wfds_cmd: cmd = GET_MAC_ADDRESS
D/WfdsJNI ( 1974): doCommand: IFNAME=wlan0 GET_CAPABILITY channels
D/WfdsService( 1974): selectPreferredScanChannel [36]
D/WfdsService( 1974): STATE : WfdsEnabledState - enter: this device mac 02:9a:02:7b:60:ac
D/WifiNative-wlan0( 1030): DRIVER COUNTRY CZ: returned true
E/WifiStateMachine( 1030):  DisconnectedState CMD_SET_FREQUENCY_BAND 0 0
E/WifiStateMachine( 1030):  ConnectModeState CMD_SET_FREQUENCY_BAND 0 0
E/WifiStateMachine( 1030):  DriverStartedState CMD_SET_FREQUENCY_BAND 0 0
D/WifiNative-wlan0( 1030): doBoolean: DRIVER SETBAND 0
I/wpa_supplicant( 6246): wpa_driver_nl80211_ext_driver_cmd SETBAND 0 - interface name wlan0
I/wpa_supplicant( 6246): wlan0: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
V/AudioManager( 6202): registerRemoteController: size of Media player list: 0
D/WfdsService( 1974): WIFI_P2P_CONNECTION_CHANGED_ACTION
D/WifiMonitor( 1030): Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN]
E/WifiMonitor( 1030): WifiMonitor:wlan0 cnt=5 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
E/WifiMonitor( 1030): handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
E/WifiMonitor( 1030): handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
D/WifiNative-wlan0( 1030): DRIVER SETBAND 0: returned true
D/WifiNative-wlan0( 1030): doBoolean: BSS_FLUSH 0
D/WifiNative-wlan0( 1030): BSS_FLUSH 0: returned true
D/WifiNative-wlan0( 1030): doBoolean: SCAN
D/WfdsService( 1974): isConnected: false
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
E/AudioManager( 6202): No RCC entry present to update
D/LGWifiP2pService( 1030): DeviceAddress: 02:9a:02:7b:60:ac
E/RemoteController( 6202): Cannot set synchronization mode on an unregistered RemoteController
D/WifiNative-p2p0( 1030): doBoolean: P2P_FLUSH
,I/WfdStateTracker( 1974): handleP2pThisDeviceChanged
D/WfdsService( 1974): WIFI_P2P_THIS_DEVICE_CHANGED_ATCION
D/WfdsService( 1974): Update P2p Interface State: 3
D/WifiNative-p2p0( 1030): P2P_FLUSH: returned true
D/WifiNative-p2p0( 1030): doBoolean: P2P_SERVICE_FLUSH
D/WifiNative-p2p0( 1030): P2P_SERVICE_FLUSH: returned true
D/WifiNative-p2p0( 1030): doString: [LIST_NETWORKS]
D/WifiNative-p2p0( 1030):    returned network id / ssid / bssid / flags
D/WifiNative-p2p0( 1030): doBoolean: SAVE_CONFIG
I/BluetoothAvrcpQcomServiceJni( 6202): classInitQcomNative: succeeds
D/LGBluetoothAvrcpQcomAdapter( 6202): [BTUI] Use QCOM AVRCP 1.5 : init jni, browsing = false
I/BluetoothAvrcpQcomServiceJni( 6202): initQcomNative: succeeds
D/LGBluetoothAvrcpQcomAdapter( 6202): [BTUI] [+] updateMediaPlayerInfo
V/LGMDMManager( 6202): Create singleton instance
,D/WifiNative-p2p0( 1030): SAVE_CONFIG: returned true
D/LGWifiP2pService( 1030): sending p2p persistent groups changed broadcast
D/WifiNative-wlan0( 1030): SCAN: returned false
E/WifiStateMachine( 1030):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 1 0 rt=117703  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
I/BluetoothAdapterState( 6202): Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
D/LGWifiP2pService( 1030): InactiveState
,D/LGWifiP2pService( 1030): InactiveState{ when=-46ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1030): P2pEnabledState{ when=-46ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-p2p0( 1030): doBoolean: DRIVER COUNTRY CZ
I/wpa_supplicant( 6246): wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
I/wpa_supplicant( 6246): p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
E/WifiStateMachine( 1030):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 1 0 rt=117725  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
I/wpa_supplicant( 6246): [LGE_PATCH] driver_cmd() country:CZ
I/wpa_supplicant( 6246): p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
E/WifiStateMachine( 1030):  DisconnectedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
I/wpa_supplicant( 6246): p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
E/WifiStateMachine( 1030):  ConnectModeState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
E/WifiStateMachine( 1030):  DriverStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
E/WifiStateMachine( 1030):  SupplicantStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
E/WifiStateMachine( 1030):  DefaultState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
D/WifiNative-p2p0( 1030): DRIVER COUNTRY CZ: returned true
D/LGWifiP2pService( 1030): InactiveState{ when=-39ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1030): P2pEnabledState{ when=-39ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1030): InactiveState{ when=0 what=139287 arg2=1 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1030): P2pEnabledState{ when=0 what=139287 arg2=1 target=com.android.internal.util.StateMachine$SmHandler }
D/WfdsMonitor( 1974): Event [CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
D/WfdsMonitor( 1974): Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
D/WfdsMonitor( 1974): Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
D/WifiMonitor( 1030): Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
E/WifiMonitor( 1030): WifiMonitor:p2p0 cnt=6 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
E/WifiMonitor( 1030): handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
E/WifiMonitor( 1030): handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
D/WifiMonitor( 1030): Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
E/WifiMonitor( 1030): WifiMonitor:p2p0 cnt=7 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
E/WifiMonitor( 1030): handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
E/WifiMonitor( 1030): handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
D/WifiMonitor( 1030): Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
E/WifiMonitor( 1030): WifiMonitor:p2p0 cnt=8 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
E/WifiMonitor( 1030): handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
E/WifiMonitor( 1030): handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
D/LGWifiP2pService( 1030): DefaultState{ when=-4ms what=139287 arg2=1 target=com.android.internal.util.StateMachine$SmHandler }
W/Settings( 1030): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1030): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1030): NETWORK_STATE_CHANGED_ACTION [SCANNING]
D/WifiServerServiceExt( 1030): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1030): setSupplicantStateSCANNING
D/LGWifiP2pService( 1030): InactiveState{ when=-7ms what=139285 arg2=2 target=com.andro,id.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1030): P2pEnabledState{ when=-7ms what=139285 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
,D/LGWifiP2pService( 1030): DefaultState{ when=-7ms what=139285 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1030): InactiveState{ when=-7ms what=139287 arg2=1 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1030): P2pEnabledState{ when=-7ms what=139287 arg2=1 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1030): DefaultState{ when=-8ms what=139287 arg2=1 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1030): InactiveState{ when=-8ms what=139283 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
W/WfdsService( 1974): DefaultState - msg [9441285] is not handled
I/StatusBar.NetworkController( 1461): networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1461): mWifiConnected = false, mWifiLevel = 0
D/LGWifiP2pService( 1030): P2pEnabledState{ when=-8ms what=139283 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1030): DefaultState{ when=-12ms what=139283 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/StatusBar.NetworkController( 1461): refreshViews: Data not connected!! Set no data type icon / Roaming
E/WifiServerServiceExt( 1030): No p2p device connected
V/SIM_STK ( 1030): Menu title from STK is T-Mobile
V/SIM_STK ( 1030): Menu title from STK is T-Mobile
,D/sensors_hal_Time( 1030): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1030): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1030): tsOffsetIs: Apps: 117822876677; DSPS: 4001948; Offset : -4318930991
,I/ActivityManager( 1030): Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=6320 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,W/ActivityManager( 1030): getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
E/ActivityThread( 6274): Failed to find provider info for com.lge.lgaccount.provider
W/LG Account v2.2( 6274): No ProfileInfo entries
I/LG Account v2.2( 6274): isEnabled: false
I/Feature ( 6274): [Lifetracker]ver: 4.21.112(40211120)
I/Feature ( 6274): [Lifetracker]Country: EU
I/Feature ( 6274): [Lifetracker]Operator: OPEN
I/Feature ( 6274): [Lifetracker]Ranking support: false
I/Feature ( 6274): [Lifetracker]Comfort support: false
I/Feature ( 6274): [Lifetracker]Accessory: true
I/Feature ( 6274): [Lifetracker]Health device: true
I/Feature ( 6274): [Lifetracker]Extra Pedometer: false
I/Feature ( 6274): [Lifetracker]Blood glucose device: false
I/Feature ( 6274): [Lifetracker]Device Number: 3
D/LGBluetoothAvrcpQcomAdapter( 6202): [BTUI] installed app name: Music
W/FormManager( 6294): Network not available. Please check & try again.
D/LGBluetoothAvrcpQcomAdapter( 6202): [BTUI] installed app name: Google Play Music
D/LGBluetoothAvrcpQcomAdapter( 6202): [BTUI] === MediaPlayerInfo (playerId:0) ===
D/LGBluetoothAvrcpQcomAdapter( 6202): [BTUI]          displayName: Music
D/LGBluetoothAvrcpQcomAdapter( 6202): [BTUI]          packageName: com.lge.music
D/LGBluetoothAvrcpQcomAdapter( 6202): [BTUI]          playState: 2 (PAUSED)
D/LGBluetoothAvrcpQcomAdapter( 6202): [BTUI] === MediaPlayerInfo (playerId:1) ===
D/LGBluetoothAvrcpQcomAdapter( 6202): [BTUI]          displayName: Google Play Music
D/LGBluetoothAvrcpQcomAdapter( 6202): [BTUI]          packageName: com.google.android.music
D/LGBluetoothAvrcpQcomAdapter( 6202): [BTUI]          playState: 2 (PAUSED)
D/LGBluetoothAvrcpQcomAdapter( 6202): [BTUI] [-] updateMediaPlayerInfo
I/BluetoothA2dpServiceJni( 6202): classInitNative
I/BluetoothA2dpServiceJni( 6202): classInitNative: succeeds
D/A2dpStateMachine( 6202): make
,V/FormManager( 6294): Network unavailable.
I/bluedroid-qcom( 6202): get_profile_interface a2dp
I/GKI_LINUX( 6202): gki_task_entry task_id=2 [A2DP-MEDIA] starting
I/LGBluetoothA2dpServiceJni( 6202): classInitNative: succeeds
I/LGBluetoothA2dpAdapter( 6202): [BTUI] getInstance : create [LGBluetoothA2dpAdapter]
D/BluetoothAdapterService( 6202): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@391cf1d6
D/A2dpStateMachine( 6202): Enter Disconnected: -2
I/BluetoothHidServiceJni( 6202): classInitNative: succeeds
D/HidService( 6202): Received start request. Starting profile...
I/bluedroid-qcom( 6202): get_profile_interface hidhost
D/BluetoothAdapterService( 6202): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@391cf1d6
D/HeadsetStateMachine( 6202): Proxy object connected
D/LGBluetoothHfpAdapter( 6202): [BTUI] queryPhoneState
D/LGBluetoothHfpAdapter( 6202): Try to query the phonestate on bind
D/BluetoothPhoneService.BluetoothLTECall( 1867):  call mBluetoothHeadset.phoneStateChanged()
I/BluetoothHealthServiceJni( 6202): classInitNative: succeeds
W/BluetoothHeadset( 1867): Proxy not attached to service
V/FormManager( 6294): Network unavailable.
D/HealthService( 6202): Received start request. Starting profile...
D/BluetoothHeadset( 1867): java.lang.Throwable
D/BluetoothHeadset( 1867): 	at android.bluetooth.BluetoothHeadset.phoneStateChanged(BluetoothHeadset.java:826)
D/BluetoothHeadset( 1867): 	at com.android.phone.BluetoothPhoneService$BluetoothLTECall.handleQueryPhoneState(BluetoothPhoneService.java:1527)
D/BluetoothHeadset( 1867): 	at com.android.phone.BluetoothPhoneService$BluetoothLTECall.access$700(BluetoothPhoneService.java:1360)
D/BluetoothHeadset( 1867): 	at com.android.phone.BluetoothPhoneService$1.handleMessage(BluetoothPhoneService.java:268)
D/BluetoothHeadset( 1867): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/BluetoothHeadset( 1867): 	at android.os.Looper.loop(Looper.java:135)
D/BluetoothHeadset( 1867): 	at android.app.ActivityThread.main(ActivityThread.java:5274)
D/BluetoothHeadset( 1867): 	at java.lang.reflect.Method.invoke(Native Method)
D/BluetoothHeadset( 1867): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/BluetoothHeadset( 1867): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
D/BluetoothHeadset( 1867): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
I/bluedroid-qcom( 6202): get_profile_interface health
I/LGBluetoothHealthServiceJni( 6202): classInitNative: succeeds
D/BluetoothAdapterService( 6202): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@391cf1d6
I/BluetoothPanServiceJni( 6202): classInitNative(L105): succeeds
,D/PanService( 6202): Received start request. Starting profile...
D/BluetoothPanServiceJni( 6202): initializeNative(L110): pan
I/bluedroid-qcom( 6202): get_profile_interface pan
I/LGBluetoothPanAdapter( 6202): [BTUI] getInstance : create [LGBluetoothPanAdapter]
D/BluetoothAdapterService( 6202): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@391cf1d6
D/BluetoothAdapterService( 6202): Profile still not running:com.android.bluetooth.gatt.GattService
D/HeadsetStateMachine( 6202): Disconnected process message: 10, size: 0
D/HeadsetPhoneState( 6202): sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
I/BtGatt.JNI( 6202): classInitNative(L901): classInitNative: Success!
D/HeadsetStateMachine( 6202): Disconnected process message: 11, size: 0
D/BtGatt.DebugUtils( 6202): handleDebugAction() action=null
D/BtGatt.GattService( 6202): Received start request. Starting profile...
D/BtGatt.GattService( 6202): start()
I/bluedroid-qcom( 6202): get_profile_interface gatt
D/BtGatt.AdvertiseManager( 6202): advertise manager created
D/BluetoothPermissionRequest( 6247): onReceive
,D/LGBluetoothFeatureConfig( 6247):  get() - isFeatureLoaded : false
D/BluetoothAdapterService( 6202): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@391cf1d6
D/BluetoothAdapterService( 6202): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@391cf1d6
I/LGBluetoothMapAdapter( 6202): [BTUI] getInstance : create [LGBluetoothMapAdapter]
V/BluetoothMapService( 6202): BluetoothMapBinder()
D/BluetoothMapService( 6202): Received start request. Starting profile...
D/BluetoothMapService( 6202): start()
D/BluetoothMapEmailSettingsLoader( 6202): Found 0 applications
D/BluetoothMapEmailAppObserver( 6202): createReceiver()
D/BluetoothMapEmailAppObserver( 6202): initObservers()
D/BluetoothMapEmailAppObserver( 6202): getEnabledAccountItems()
D/BluetoothAdapterService( 6202): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@391cf1d6
,D/BluetoothAdapterService( 6202): Profile still not running:com.android.bluetooth.gatt.GattService
I/wpa_supplicant( 6246): [LGE_PATCH]scan interval[0] = 2 sec.
E/WifiMonitor( 1030): WifiMonitor:wlan0 cnt=9 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
E/WifiMonitor( 1030): handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
D/WifiMonitor( 1030): Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
E/WifiMonitor( 1030): WifiMonitor:wlan0 cnt=10 dispatchEvent: WPS-AP-AVAILABLE 
D/WfdsMonitor( 1974): Event [CTRL-EVENT-SCAN-RESULTS ]
D/WfdsMonitor( 1974): Event [WPS-AP-AVAILABLE ]
D/BluetoothManagerService( 1030): Message: 20
D/BluetoothManagerService( 1030): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@d9a9a56:true
D/BluetoothAdapterService( 6202): Profile still not running:com.android.bluetooth.gatt.GattService
W/WifiMonitor( 1030): couldn't identify event type - WPS-AP-AVAILABLE 
E/WifiMonitor( 1030): WifiMonitor:p2p0 cnt=11 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
E/WifiMonitor( 1030): handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
D/WifiMonitor( 1030): Event [IFNAME=p2p0 WPS-AP-AVAILABLE ]
E/WifiMonitor( 1030): WifiMonitor:p2p0 cnt=12 dispatchEvent: WPS-AP-AVAILABLE 
W/WifiMonitor( 1030): couldn't identify event type - WPS-AP-AVAILABLE 
D/LGWifiP2pService( 1030): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1030): P2pEnabledState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1030): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiStateMachine( 1030):  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=0 bcn=0
E/WifiStateMachine( 1030):  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=0 bcn=0
E/WifiStateMachine( 1030):  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=0 bcn=0
D/BluetoothAdapterService( 6202): Profile still not running:com.android.bluetooth.gatt.GattService
E/WifiStateMachine( 1030):  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=0 bcn=0
I/WifiNative-HAL( 1030): startHal
E/wifi    ( 1030): getStaticLongField sWifiHalHandle 0x988e08cc
E/WifiHAL ( 1030): Could not connect handle
D/wifi    ( 1030): halHandle = 0x0, mVM = 0xb487c280, mCls = 0x701baa
I/WifiNative-HAL( 1030): Could not start hal
D/WifiNative-wlan0( 1030): doString: [BSS RANGE=0- MASK=0x21987]
D/BluetoothAdapterService( 6202): Profile still not running:com.android.bluetooth.gatt.GattService
V/PanService( 6202): [BTUI] SIM Extra State :ABSENT
D/BluetoothAdapterService( 6202): Profile still not running:com.android.bluetooth.map.BluetoothMapService
V/BluetoothMapService( 6202): Handler(): got msg=1
,D/LGBluetoothResetSettingReceiver( 6247): return without doing reset settings.
D/BluetoothAdapterState( 6202): CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
I/bluedroid-qcom( 6202): enable
I/bt_hci_bdroid( 6202): init
I/GKI_LINUX( 6202): gki_task_entry task_id=0 [BTU] starting
I/bt-btu  ( 6202): btu_task pending for preload complete event
I/ActivityManager( 1030): Killing 5513:com.android.contacts/u0a19 (adj 15): empty #17
I/bt_vendor( 6202): bt-vendor : init
I/bt_vendor( 6202): bt-vendor : get_bt_soc_type
E/bt_vendor( 6202): get_bt_soc_type: Failed to get soc type
I/bt_vendor( 6202): init: Local BD Address : c0:64:73:54:3f:58
D/bt_userial_mct( 6202): userial_init
D/bt_hci_bdroid( 6202): set_power 1
I/bt_vendor( 6202): bt-vendor : BT_VND_OP_POWER_CTRL: On
I/bt_vendor( 6202): Starting hciattach daemon
I/bt_vendor( 6202): try to set true
,W/sh      ( 6351): type=1400 audit(0.0:157): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6508 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
W/sh      ( 6351): type=1400 audit(0.0:158): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6508 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
I/qcom-bluetooth( 6352): /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  
,D/PCSuite ( 6320): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,I/qcom-bluetooth( 6360): /system/etc/init.qcom.bt.sh: Transport : smd 
,D/LGBluetoothOppAdapter( 6202): [BTUI] getInstance : create [LGBluetoothOppAdapter]
W/libprocessgroup( 1030): failed to open /acct/uid_10019/pid_5513/cgroup.procs: No such file or directory
I/ActivityManager( 1030): Killing 5836:com.lge.email/u0a23 (adj 15): empty #17
,I/qcom-bluetooth( 6361): /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,I/qcom-bluetooth( 6363): /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,I/qcom-bluetooth( 6364): /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> 
,I/qcom-bluetooth( 6365): /system/etc/init.qcom.bt.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,I/qcom-bluetooth( 6366): /system/etc/init.qcom.bt.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> 
,I/libmdmdetect( 6368): ESOC framework not supported
E/Diag_Lib( 6368):  Diag_LSM_Init: Failed to open handle to diag driver, error = 13
,D/bthci_qcomm_linux( 6368): [BTUI] bt_hci_qcomm_pfal_get_bdaddress: Get BDADDR from bluedroid prop (58:3F:54:73:64:C0)
D/bthci_qcomm_common( 6368): [BTUI] bt_hci_qcomm_init:
D/bthci_qcomm_common( 6368): [BTUI]     BDADDR: 58:3F:54:73:64:C0
D/bthci_qcomm_common( 6368): [BTUI]     BR/EDR: Class 1
D/bthci_qcomm_common( 6368): [BTUI]     LE: Class 2
D/bthci_qcomm_common( 6368): [BTUI]     Ref Clock: 32M
D/btqsocnvmtags( 6368): [BTUI] init_riva_entries: set NORMAL power settings
,W/libprocessgroup( 1030): failed to open /acct/uid_10023/pid_5836/cgroup.procs: No such file or directory
V/BluetoothFtpReceiver( 6202): BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
,V/BluetoothSapReceiver( 6202): [BTUI] checkServiceStart
,V/BluetoothSapReceiver( 6202): [BTUI] region:EU country:EU
V/BluetoothSapReceiver( 6202): SapReceiver onReceive 
V/BluetoothSapReceiver( 6202): action = android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothSapReceiver( 6202):  Bluetooth Adapter state = 11
V/WiFiOffLoadBroadcast( 6247): WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,D/WifiService( 1030): New client listening to asynchronous messages
I/ActivityManager( 1030): Start proc com.lge.settings.easy for broadcast com.lge.settings.easy/com.lge.settings.bluetooth.LGBluetoothProfileConnectionReceiver: pid=6372 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,D/LgDataFeature( 6247): LgDataFeature() Constructor: none
D/LgDataFeature( 6247): LgDataFeature() Constructor Done, null
D/WiFiOffLoadUpdatePriority( 6247): remove : truetruetrue
,E/WifiStateMachine( 1030):  DisconnectedState CMD_GET_CONFIGURED_NETWORKS uid=1000 1000 0 num=1
E/WifiStateMachine( 1030):  ConnectModeState CMD_GET_CONFIGURED_NETWORKS uid=1000 1000 0 num=1
I/rmt_storage(  306): rmt_storage_connect_cb: clnt_h=0x5 conn_h=0xb6403090
I/rmt_storage(  306): rmt_storage_rw_iovec_cb: /boot/modem_fs2: clnt_h=0x2: req_h=0x9 msg_id=3: R/W request received
I/rmt_storage(  306): wakelock acquired: 1, error no: 42
I/rmt_storage(  306): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 Unblock worker thread (th_id: -1236806912)
E/WifiStateMachine( 1030):  DisconnectedState CMD_SAVE_CONFIG uid=1000 0 0
,E/WifiStateMachine( 1030):  ConnectModeState CMD_SAVE_CONFIG uid=1000 0 0
D/WifiNative-wlan0( 1030): doBoolean: SAVE_CONFIG
D/WifiNative-wlan0( 1030): SAVE_CONFIG: returned true
,D/WiFiOffLoadUpdatePriority( 6247): remove1
V/WiFiOffLoadSharedPrefsUtils( 6247): save remove
W/ResourcesManager( 6372): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
I/ActivityManager( 1030): Killing 5536:com.android.gallery3d/u0a27 (adj 15): empty #17
,I/rmt_storage(  306): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0x9 msg_id=3: Bytes written = 1572864
I/rmt_storage(  306): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0x9 msg_id=3: Send response: res=0 err=0
,I/rmt_storage(  306): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 About to block rmt_storage client thread (th_id: -1236806912) wakelock released: 1, error no: 0
I/rmt_storage(  306): 
I/rmt_storage(  306): rmt_storage_disconnect_cb: clnt_h=0x0x5 conn_h=0x0xb6403090
E/Diag_Lib(  876): [IMS_FATAL]| 3347 | 898 |ims-rtp-daemon ims_rtp_qmi_handler_thread_func waiting on select thread>
D/WiFiOffLoadBroadcast( 6247): mLastConnectedNetwork from SharedPrefsUtils for wifioffloading : null
D/WiFiOffLoadBroadcast( 6247): S: false, R: false
E/WifiStateMachine( 1030):  DisconnectedState CMD_GET_CONFIGURED_NETWORKS uid=1000 1000 0 num=1
E/WifiStateMachine( 1030):  ConnectModeState CMD_GET_CONFIGURED_NETWORKS uid=1000 1000 0 num=1
D/WiFiOffLoadUpdatePriority( 6247): saved SSID: "NG700"
D/WiFiOffLoadUpdatePriority( 6247): connected SSID: null
D/WiFiOffLoadUpdatePriority( 6247): private wpa: "NG700" 300
D/WifiServiceImplEx( 1030): addOrUpdateNetwork pid=6247, uid=1000, packageName=android.uid.system:1000
E/addOrUpdateNetwork( 1030):  uid = 1000 SSID "NG700" nid=0
,E/WifiStateMachine( 1030):  DisconnectedState CMD_ADD_OR_UPDATE_NETWORK uid=1000 0 0 "NG700"WPA_PSK prio=300 status=2
E/WifiStateMachine( 1030):  ConnectModeState CMD_ADD_OR_UPDATE_NETWORK uid=1000 0 0 "NG700"WPA_PSK prio=300 status=2
E/WifiConfigStore( 1030):  key="NG700"WPA_PSK netId=0 uid=0/1000
D/WifiServerServiceExt( 1030): addOrUpdateNetwork: mThisIsFirstEnableing = false
D/WifiNative-wlan0( 1030): doBoolean: SET_NETWORK 0 ssid 4e47373030
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
,E/WifiConfigStore( 1030): will read network variables netId=0
E/WifiConfigStore( 1030): writeIpAndProxyConfigurationsOnChange: "NG700" -> "NG700" path: /data/misc/wifi/ipconfig.txt
E/WifiConfigStore( 1030):  writeKnownNetworkHistory() num networks:1 needWrite=false
D/AuthorizationBluetoothService( 2138): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,W/libprocessgroup( 1030): failed to open /acct/uid_10027/pid_5536/cgroup.procs: No such file or directory
D/WiFiOffLoadUpdatePriority( 6247):  ssid "NG700" prio 300
D/WiFiOffLoadUpdatePriority( 6247): configuration updated: 0
E/WifiStateMachine( 1030):  DisconnectedState CMD_SAVE_CONFIG uid=1000 0 0
E/WifiStateMachine( 1030):  ConnectModeState CMD_SAVE_CONFIG uid=1000 0 0
D/WifiNative-wlan0( 1030): doBoolean: SAVE_CONFIG
D/WifiNative-wlan0( 1030): SAVE_CONFIG: returned true
D/WiFiOffLoadUpdatePriority( 6247): configuration saved: true
,I/ActivityManager( 1030): Killing 5208:com.wsandroid.suite.lge/1000 (adj 15): empty #17
W/libprocessgroup( 1030): failed to open /acct/uid_1000/pid_5208/cgroup.procs: No such file or directory
,D/PCSuite ( 6320): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,V/WiFiOffLoadBroadcast( 6247): WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,D/WiFiOffLoadBroadcast( 6247): MCCMNC not supported: null
W/FormManager( 6294): Network not available. Please check & try again.
,V/FormManager( 6294): Network unavailable.
V/FormManager( 6294): Network unavailable.
,D/LGDMClient( 3948): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
D/LGDMClient( 3948): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,W/ContextImpl( 3948): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
W/ContextImpl( 3948): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
D/LGDMClient( 3948): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=3, isUserType=1
,D/LGDMClient( 3948): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
D/LGDMClient( 3948): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
I/ActivityManager( 1030): Start proc com.wsandroid.suite.lge for broadcast com.wsandroid.suite.lge/com.wavesecure.core.WSAndroidSystemIntentReceiver: pid=6395 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,W/ResourcesManager( 6395): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,D/PluginManager( 6395): init()
,E/QC-QMI  ( 6368): qmi_client [6368] 13: failed to locate client data
,E/QC-QMI  (  481): qmuxd: RX on fd=32 returned error=0 errno[2:No such file or directory]
E/QC-QMI  (  481): QMUX qmux_client_id=13 not found in qmux client list, unable to remove
W/ExternalStrings( 6395): load override strings
W/ExternalStrings( 6395): java.lang.RuntimeException: Unexpected tag, got eat-comment
W/ExternalStrings( 6395): 	at com.mcafee.plugin.af.a(Unknown Source)
W/ExternalStrings( 6395): 	at com.mcafee.plugin.ac.b(Unknown Source)
W/ExternalStrings( 6395): 	at com.mcafee.plugin.ak.d(Unknown Source)
W/ExternalStrings( 6395): 	at com.mcafee.plugin.ak.a(Unknown Source)
W/ExternalStrings( 6395): 	at com.mcafee.app.s.getClassLoader(Unknown Source)
W/ExternalStrings( 6395): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5001)
W/ExternalStrings( 6395): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4609)
W/ExternalStrings( 6395): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4549)
W/ExternalStrings( 6395): 	at android.app.ActivityThread.access$1500(ActivityThread.java:148)
W/ExternalStrings( 6395): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1344)
W/ExternalStrings( 6395): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/ExternalStrings( 6395): 	at android.os.Looper.loop(Looper.java:135)
W/ExternalStrings( 6395): 	at android.app.ActivityThread.main(ActivityThread.java:5274)
W/ExternalStrings( 6395): 	at java.lang.reflect.Method.invoke(Native Method)
W/ExternalStrings( 6395): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/ExternalStrings( 6395): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
W/ExternalStrings( 6395): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
,D/StatusProvider( 6395): onCreate
I/qcom-bluetooth( 6418): /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 58:3f:54:73:64:c0 
,I/qcom-bluetooth( 6419): /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,V/Signer  ( 6395): override build config not found
D/Signer  ( 6395): value of property debug is false
D/LGMDMWrapper( 6395): Found class 'com.mcafee.lgmdm.LGMDMWrapper$DataWipe'.
D/LGMDMWrapper( 6395): Found class 'com.mcafee.lgmdm.LGMDMWrapper$DownloadMode'.
D/LGMDMWrapper( 6395): Found class 'com.mcafee.lgmdm.LGMDMWrapper$HardReset'.
D/LGMDMWrapper( 6395): Found class 'com.mcafee.lgmdm.LGMDMWrapper$HardwareKeyReset'.
D/LGMDMWrapper( 6395): Found class 'com.mcafee.lgmdm.LGMDMWrapper$RemoveDeviceAdmin'.
D/LGMDMWrapper( 6395): Found class 'com.mcafee.lgmdm.LGMDMWrapper$UnknownSourceInstallation'.
D/LGMDMWrapper( 6395): Found class 'com.mcafee.lgmdm.LGMDMWrapper$Usb'.
D/LGMDMWrapper( 6395): Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbDebugging'.
D/LGMDMWrapper( 6395): Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbHostStorage'.
D/LGMDMWrapper( 6395): Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbMediaTransfer'.
D/LGMDMWrapper( 6395): Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbPictureTransfer'.
D/LGMDMWrapper( 6395): Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbStorage'.
D/LGMDMWrapper( 6395): Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbTethering'.
I/bt_vendor( 6202): bluetooth satus is on
D/bt_hci_bdroid( 6202): preload
D/bt_userial_mct( 6202): userial_open(port:0)
I/bt_vendor( 6202): bt-vendor : BT_VND_OP_USERIAL_OPEN
I/bt_vendor( 6202): Done intiailizing UART
,I/bt_vendor( 6202): Done intiailizing UART
I/bt_userial_mct( 6202): CMD=66, EVT=66, ACL_Out=67, ACL_In=67
I/bt_vendor( 6202): Bluetooth Firmware and transport layer are initialized
D/bt_userial_mct( 6202): Entering userial_read_thread()
I/bt-btu  ( 6202): btu_task received preload complete event
W/bt-l2cap( 6202): L2CAP - L2CA_Register() called for PSM: 0x0001
W/bt-l2cap( 6202): L2CAP - L2CA_Register() called for PSM: 0x001f
W/bt-l2cap( 6202): L2CAP - L2CA_Register() called for PSM: 0x0003
I/        ( 6202): BTE_InitTraceLevels -- TRC_HCI
I/        ( 6202): BTE_InitTraceLevels -- TRC_L2CAP
I/        ( 6202): BTE_InitTraceLevels -- TRC_RFCOMM
I/        ( 6202): BTE_InitTraceLevels -- TRC_AVDT
I/        ( 6202): BTE_InitTraceLevels -- TRC_AVRC
I/        ( 6202): BTE_InitTraceLevels -- TRC_A2D
I/        ( 6202): BTE_InitTraceLevels -- TRC_BNEP
I/        ( 6202): BTE_InitTraceLevels -- TRC_BTM
I/        ( 6202): BTE_InitTraceLevels -- TRC_HID_HOST
I/        ( 6202): BTE_InitTraceLevels -- TRC_GAP
I/        ( 6202): BTE_InitTraceLevels -- TRC_PAN
I/        ( 6202): BTE_InitTraceLevels -- TRC_SDP
I/        ( 6202): BTE_InitTraceLevels -- TRC_GATT
I/        ( 6202): BTE_InitTraceLevels -- TRC_SMP
I/        ( 6202): BTE_InitTraceLevels -- TRC_BTAPP
I/        ( 6202): BTE_InitTraceLevels -- TRC_BTIF
V/LGMDMManager( 6395): Create singleton instance
,W/bt-btm  ( 6202): btm_decode_ext_features_page Secure conn Controller support Enabled
,E/bt-btm  ( 6202): BTM_SecRegister:p_cb_info->p_le_callback == 0xa015c061 
E/bt-btm  ( 6202): BTM_SecRegister: btm_cb.api.p_le_callback = 0xa015c061 
W/bt-l2cap( 6202): L2CAP - L2CA_Register() called for PSM: 0x0019
E/bt-btif ( 6202): L2CAP - L2CA_Registe
W/bt-l2cap( 6202): L2CAP - L2CA_Register() called for PSM: 0x0017
W/bt-l2cap( 6202): L2CAP - L2CA_Register() called for PSM: 0x001b
W/bt-l2cap( 6202): L2CAP - L2CA_Register() called for PSM: 0x0011
W/bt-l2cap( 6202): L2CAP - L2CA_Register() called for PSM: 0x0013
E/bt-btif ( 6202): btif_storage_get_adapter_property service_mask:0x2140040
D/BluetoothAdapterProperties( 6202): Address is:58:3F:54:73:64:C0
D/BluetoothAdapterProperties( 6202): Name is: G3-1
D/BluetoothManagerService( 1030): Bluetooth Adapter name changed to G3-1
D/BluetoothManagerService( 1030): Stored Bluetooth name: G3-1
,D/BluetoothAdapterProperties( 6202): Scan Mode:20
D/BluetoothAdapterProperties( 6202): Discoverable Timeout:120
D/bt_hci_bdroid( 6202): postload
D/bt_hci_bdroid( 6202): Used up Tx Cmd credits
W/bt-l2cap( 6202): L2CAP - L2CA_Register() called for PSM: 0x000f
D/LGMDMWrapper( 6395): LG MDM library v4.0.0 is available on this device.
D/bte_conf( 6202): Device ID record 1 : primary
D/bte_conf( 6202):   vendorId            = 00c4
D/bte_conf( 6202):   vendorIdSource      = 0001
D/bte_conf( 6202):   product             = 13a1
D/bte_conf( 6202):   version             = 1000
D/bte_conf( 6202):   clientExecutableURL = 
D/bte_conf( 6202):   serviceDescription  = 
D/bte_conf( 6202):   documentationURL    = 
D/bte_conf( 6202): bte_load_did_conf no section named DID2.
D/BluetoothPanServiceJni( 6202): control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
D/BluetoothAdapterState( 6202): CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
D/BluetoothAdapterProperties( 6202): ScanMode =  20
D/BluetoothAdapterProperties( 6202): State =  11
D/BluetoothAdapterProperties( 6202): mDiscoverableTimeout = 120
V/LGBluetoothServiceAdapter( 6202): [BTUI] state:11, scanmode:20, timeout:120
D/BluetoothAdapterProperties( 6202): Setting state to 12
I/BluetoothAdapterState( 6202): Bluetooth adapter state changed: 11-> 12
W/sh      ( 6427): type=1400 audit(0.0:159): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6508 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
W/bt-smp  ( 6202): Key(LSB ~ MSB) = 0a 3c a6 fe eb 17 6a 79 a6 1f 0a 0b f9 50 a0 5f 
W/bt-smp  ( 6202): Plain text(LSB ~ MSB) = fa 35 6a 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/sh      ( 6427): type=1400 audit(0.0:160): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6508 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
W/bt-smp  ( 6202): Encrypted text(LSB ~ MSB) = 0e bf ab 84 05 cd d5 48 58 08 53 25 bc 90 1c 8c 
W/bt-btm  ( 6202): Stopping oneshot timer
D/bt_hci_bdroid( 6202): Used up Tx Cmd credits
D/BluetoothManagerService( 1030): Message: 60
I/BluetoothAdapterState( 6202): Entering On State
D/bt_hci_bdroid( 6202): Used up Tx Cmd credits
D/bt_hci_bdroid( 6202): Used up Tx Cmd credits
D/bt_hci_bdroid( 6202): Used up Tx Cmd credits
D/btif_config_util( 6202): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt_mct  ( 6202): hci lib postload completed
D/BluetoothManagerService( 1030): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
D/LGBluetoothServiceAdapter( 6202): [BTUI] OnState
D/LGBluetoothServiceAdapter( 6202): [BTUI]         global_name: G3-1
D/BluetoothManagerService( 1030): Broadcasting onBluetoothStateChange(true) to 5 receivers.
D/LGBluetoothServiceAdapter( 6202): [BTUI]         local_name: G3-1
D/BluetoothAdapterService( 6202): [BTUI] autoConnect() : not allowed
D/BluetoothHeadset( 1867): onBluetoothStateChange: up=true
D/BluetoothA2dp( 1030): onBluetoothStateChange: up=true
D/BluetoothHeadset( 1867): onBluetoothStateChange: up=true
D/BluetoothHeadset( 1867): onBluetoothStateChange: up=true
D/BluetoothHeadset( 1030): onBluetoothStateChange: up=true
E/BluetoothManagerService( 1030): Fail to bind to: Intent { act=android.bluetooth.IQBluetooth }
D/BluetoothManagerService( 1030): Bluetooth State Change Intent: 11 -> 12
D/LGBluetoothAPIService( 1974): [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
I/[SystemUI]BluetoothHandler( 1461): Receive : BluetoothAdapter.ACTION_STATE_CHANGED
D/LGBluetoothAPIService( 1974): Message: 1
D/LGBluetoothAPIService( 1974): MESSAGE_BOOT_COMPLETED
D/BluetoothManagerService( 1030): BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
W/bt-smp  ( 6202): Key(LSB ~ MSB) = 0a 3c a6 fe eb 17 6a 79 a6 1f 0a 0b f9 50 a0 5f 
W/bt-smp  ( 6202): Plain text(LSB ~ MSB) = 4d f5 46 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 6202): Encrypted text(LSB ~ MSB) = cc 51 98 c3 67 62 80 6e cf 7c 2c dd 56 5f 9b bb 
W/bt-btm  ( 6202): Stopping oneshot timer
,D/BluetoothManagerService( 1030): Message: 40
D/BluetoothManagerService( 1030): MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
I/BluetoothMapService( 6202): onReceive: android.bluetooth.adapter.action.STATE_CHANGED
D/BluetoothMapService( 6202): STATE_ON
V/BluetoothMapService( 6202): Handler(): got msg=1
D/BluetoothMapMasInstance( 6202): Map Service startRfcommSocketListener
W/ContextImpl( 6247): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
,W/bt-smp  ( 6202): Key(LSB ~ MSB) = 0a 3c a6 fe eb 17 6a 79 a6 1f 0a 0b f9 50 a0 5f 
W/bt-smp  ( 6202): Plain text(LSB ~ MSB) = 5a d1 4e 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 6202): Encrypted text(LSB ~ MSB) = 48 83 48 fb bc 60 72 73 70 8c a7 06 9e 59 76 ab 
W/bt-btm  ( 6202): Stopping oneshot timer
I/LGBluetoothAPIService( 1974): [BTUI] LGBluetoothAPIService Binding Success
D/LGBluetoothDeviceModeControllManager( 6202): [BTUI] checkDeviceModeAndSet, sinkMode : false
D/BluetoothMapMasInstance( 6202): MAS initSocket()
D/BluetoothMapMasInstance( 6202):   masId = 00
D/BluetoothMapMasInstance( 6202):   msgTypes = 0e
D/BluetoothMapMasInstance( 6202):   masName = SMS/MMS
D/BluetoothMapMasInstance( 6202):   SDP string = 000eSMS/MMS
D/BluetoothManagerService( 1030): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
W/BluetoothAdapter( 6202): getBluetoothService() called with no BluetoothManagerCallback
W/bt-smp  ( 6202): Key(LSB ~ MSB) = 0a 3c a6 fe eb 17 6a 79 a6 1f 0a 0b f9 50 a0 5f 
,W/bt-smp  ( 6202): Plain text(LSB ~ MSB) = 88 a2 4c 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 6202): Encrypted text(LSB ~ MSB) = 8f b0 12 e4 63 36 fc 1f ba a8 80 1e 82 ec b1 bc 
W/bt-btm  ( 6202): Stopping oneshot timer
D/LGBluetoothServiceAdapter( 6202): [BTUI] createSocketChannel FD=73 mFd=0
I/qcom-bt-wlan-coex( 6442): /system/etc/init.qcom.coex.sh: btwlancoex/abtfilt not available 
V/BluetoothMapMasInstance( 6202): Succeed to create listening socket 
D/BluetoothMapMasInstance( 6202): Accepting socket connection...
D/LocalBluetoothProfileManager( 6247): Adding local A2DP profile
W/bt-smp  ( 6202): Key(LSB ~ MSB) = 0a 3c a6 fe eb 17 6a 79 a6 1f 0a 0b f9 50 a0 5f 
W/bt-smp  ( 6202): Plain text(LSB ~ MSB) = 71 b6 50 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 6202): Encrypted text(LSB ~ MSB) = a9 0f bb 35 08 ed 84 1b 3f 0f 8c 88 2d 55 32 13 
W/bt-btm  ( 6202): Stopping oneshot timer
D/BluetoothManagerService( 1030): Message: 30
D/LocalBluetoothProfileManager( 6247): Adding local HEADSET profile
D/BluetoothAdapterService( 6202): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@391cf1d6
V/BluetoothPbapService( 6202): Pbap Service onCreate
V/BluetoothPbapService( 6202): Starting PBAP service
,D/BluetoothManagerService( 1030): Message: 30
D/LGBluetoothPbapAdapter( 6202): [BTUI] getInstance : create
V/BluetoothPbapService( 6202): action: android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothPbapService( 6202): state: 12
D/BluetoothAdapterProperties( 6202): Discoverable Timeout:120
D/LGBluetoothDeviceModeControllManager( 6202): adapterPropertyChangedCallback on  LGAdapter : do nothing - 9
D/BluetoothAdapterProperties( 6202): Scan Mode:21
D/LGBluetoothDeviceModeControllManager( 6202): getDeviceMode  deviceMode 0
D/BluetoothManagerService( 1030): Message: 30
D/LGBluetoothAPIServer( 6202): [BTUI] onCreate()
D/LGBluetoothAPIServer( 6202): [BTUI] onBind()
D/BluetoothManagerService( 1030): Message: 30
D/LGBluetoothAPIService( 1974): [BTUI] LGBluetoothAPIServiceConnection: connected to LGBluetoothAPIAdapter
,D/LGBluetoothAPIService( 1974): Message: 100
D/LGBluetoothAPIService( 1974): MESSAGE_BLUETOOTH_SERVICE_CONNECTED
V/BluetoothPbapReceiver( 6202): PbapReceiver onReceive 
V/BluetoothPbapReceiver( 6202): ***********action = android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothPbapReceiver( 6202): ***********state = 12
V/BluetoothPbapService( 6202): Handler(): got msg=1
V/BluetoothPbapService( 6202): Pbap Service startRfcommSocketListener
D/LocalBluetoothProfileManager( 6247): Adding local MAP profile
V/BluetoothPbapService( 6202): Pbap Service initSocket
D/BluetoothMap( 6247): Create BluetoothMap proxy object
D/BluetoothManagerService( 1030): Message: 30
D/BluetoothManagerService( 1030): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,W/BluetoothAdapter( 6202): getBluetoothService() called with no BluetoothManagerCallback
D/LGBluetoothServiceAdapter( 6202): [BTUI] createSocketChannel FD=75 mFd=73
V/BluetoothPbapService( 6202): Succeed to create listening socket 
V/BluetoothPbapService( 6202): Accepting socket connection...
D/BluetoothManagerService( 1030): Message: 30
V/BluetoothPbapService( 6202): Pbap Service onBind
D/LocalBluetoothProfileManager( 6247): LocalBluetoothProfileManager construction complete
D/LGBluetoothUserBindClient( 6247): [BTUI] initUserBindClient
D/PostponalbeReceiver( 6395): WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,W/ContextImpl( 6247): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.android.settings.bluetooth.LGBluetoothUserBindClient.initUserBindClient:90 com.android.settings.bluetooth.LGBluetoothUserBindClient.<init>:55 com.android.settings.bluetooth.LGBluetoothUserBindClient.getInstance:47 
W/ContextImpl( 6395): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
D/DockEventReceiver( 6247): finishStartingService: stopping service
I/PCSuite ( 6320): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/BluetoothA2dp( 6247): Proxy object connected
D/A2dpProfile( 6247): Bluetooth service connected
D/PCSuite ( 6320): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 6320): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,D/BluetoothHeadset( 6247): Proxy object connected
,D/HeadsetProfile( 6247): Bluetooth service connected
D/BluetoothInputDevice( 6247): Proxy object connected
D/HidProfile( 6247): Bluetooth service connected
D/BluetoothPan( 6247): BluetoothPAN Proxy object connected
D/PanProfile( 6247): Bluetooth service connected
D/BluetoothMap( 6247): Proxy object connected
D/MapProfile( 6247): Bluetooth service connected
D/BluetoothMap( 6247): getConnectedDevices()
V/BluetoothMapService( 6202): getConnectedDevices()
D/BluetoothPbap( 6247): Proxy object connected
D/PbapServerProfile( 6247): Bluetooth service connected
D/LGBluetoothUserBindClient( 6247): [BTUI] onServiceConnected
V/WiFiOffLoadBroadcast( 6247): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6247): MCCMNC not supported: null
D/BluetoothPermissionRequest( 6247): onReceive
D/LGBluetoothFeatureConfig( 6247): isPrivacyLogsEnabled : true
D/LGBluetoothUtils( 6247): [BTUI] FileNotFound: readProperty
D/LGBluetoothResetSettingReceiver( 6247): return without doing reset settings.
I/ActivityManager( 1030): Killing 5559:com.lge.lockscreensettings/u0a80 (adj 15): empty #17
W/ActivityThread( 6395): ClassLoader.getResources: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/libprocessgroup( 1030): failed to open /acct/uid_10080/pid_5559/cgroup.procs: No such file or directory
,V/BluetoothOppReceiver( 6202): Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_ON
,I/LGBluetoothOppAdapter( 6202): [BTUI] startOppService()
D/QRemote ( 5992): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,D/QRemote ( 5992): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
V/BluetoothOppManager( 6202): restoreApplicationData! falsefalsenullnull
D/LGBluetoothFeatureConfig( 6202): isPrivacyLogsEnabled : true
V/BtOppService( 6202): onCreate
,V/BluetoothOppNotification( 6202): send message
V/BtOppService( 6202): Starting RfcommListener
D/BluetoothOppPreference( 6202): Dumping Names:  
D/BluetoothOppPreference( 6202): {}
D/BluetoothOppPreference( 6202): Dumping Channels:  
D/BluetoothOppPreference( 6202): {}
V/BtOppService( 6202): onStartCommand
V/BtOppService( 6202): pendingUpdate is true keepUpdateThread is false sListenStarted is true
,V/BluetoothFtpReceiver( 6202): BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothFtpReceiver( 6202): BluetoothFtpReceiver Start Service
V/BluetoothOppNotification( 6202): new notify threadi!
V/BluetoothOppNotification( 6202): send delay message
V/BtOppService( 6202): start RfcommListener
,V/BtOppService( 6202): Deleted complete outbound shares, number =  0
,V/BtOppService( 6202): RfcommListener started
V/BtOppService( 6202): Deleted complete inbound failed shares, number = 0
I/QRemote ( 5992): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
V/BluetoothOppProvider( 6202): starting query, database is not null; projection[0] is _id; selection is direction=1 AND status=200 AND visibility=1; selectionArgs is null; sort is _id.
V/BluetoothOppProvider( 6202): created cursor android.database.sqlite.SQLiteCursor@1dc3340 on behalf of 
V/[BNRBootReceiver]( 5970): boot receiver action = android.net.wifi.p2p.CONNECTION_STATE_CHANGE
D/BNRAndroBeam( 5970): [BnR DirectBeam] Android Direct Beam(NFC) Connection changed
V/BluetoothOppProvider( 6202): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
V/BluetoothOppProvider( 6202): starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
V/BtOppRfcommListener( 6202): Starting RFCOMM listener....
V/[BNRBootReceiver]( 5970): Boot Receiver Return
D/BluetoothManagerService( 1030): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,D/PostponalbeReceiver( 6395): WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
W/ContextImpl( 6395): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
V/BluetoothOppProvider( 6202): created cursor android.database.sqlite.SQLiteCursor@5df8279 on behalf of 
V/BluetoothOppProvider( 6202): created cursor android.database.sqlite.SQLiteCursor@3c819bbe on behalf of 
W/BluetoothAdapter( 6202): getBluetoothService() called with no BluetoothManagerCallback
V/BluetoothOppNotification( 6202): mUpdateCompleteNotification = true
D/BluetoothAdapterService( 6202): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@391cf1d6
V/BluetoothFtpService( 6202): Ftp Service onCreate
I/BluetoothFtpService( 6202): Ftp Service onCreate
V/BluetoothFtpService( 6202): Ftp Service onStartCommand
V/BluetoothFtpService( 6202): action: android.bluetooth.adapter.action.STATE_CHANGED
D/LGBluetoothServiceAdapter( 6202): [BTUI] createSocketChannel FD=80 mFd=75
V/BluetoothFtpService( 6202): Starting Listening on sockets
V/BluetoothSapReceiver( 6202): [BTUI] checkServiceStart
V/BluetoothSapReceiver( 6202): [BTUI] region:EU country:EU
V/BluetoothSapReceiver( 6202): SapReceiver onReceive 
V/BtOppRfcommListener( 6202): Started RFCOMM listener....
V/BluetoothSapReceiver( 6202): action = android.bluetooth.adapter.action.STATE_CHANGED
I/BtOppRfcommListener( 6202): Accept thread started.
V/BluetoothSapReceiver( 6202):  Bluetooth Adapter state = 12
V/BtOppRfcommListener( 6202): Accepting connection...
V/BluetoothSapReceiver( 6202): Calling SAP service start service with action = null
V/BluetoothOppProvider( 6202): starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
V/BtOppService( 6202): ContentObserver received notification
V/BtOppService( 6202): ContentObserver received notification
V/BluetoothFtpService( 6202): Handler(): got msg=1
,V/BluetoothFtpService( 6202): Ftp Service startRfcommSocketListener
V/BluetoothFtpService( 6202): Ftp Service initSocket
V/BluetoothOppProvider( 6202): created cursor android.database.sqlite.SQLiteCursor@26f1436c on behalf of 
V/BtOppService( 6202): pendingUpdate is true keepUpdateThread is false sListenStarted is true
V/BluetoothOppProvider( 6202): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
V/WiFiOffLoadBroadcast( 6247): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
V/BluetoothOppProvider( 6202): created cursor android.database.sqlite.SQLiteCursor@28cccd35 on behalf of 
V/BluetoothOppNotification( 6202): update too frequent, put in queue
V/BtOppService( 6202): pendingUpdate is false keepUpdateThread is false sListenStarted is true
D/AuthorizationBluetoothService( 2138): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
D/BluetoothManagerService( 1030): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
V/BluetoothOppNotification( 6202): outbound: succ-0  fail-0
W/BluetoothAdapter( 6202): getBluetoothService() called with no BluetoothManagerCallback
D/LGBluetoothServiceAdapter( 6202): [BTUI] createSocketChannel FD=81 mFd=80
V/BluetoothFtpService( 6202): Succeed to create listening socket on channel 20
V/BluetoothOppNotification( 6202): outbound notification was removed.
V/BluetoothOppProvider( 6202): starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
V/BluetoothOppProvider( 6202): created cursor android.database.sqlite.SQLiteCursor@31b7b5ca on behalf of 
V/BluetoothFtpService:RfcommSocketAcceptThread( 6202): Run Accept thread
V/BluetoothOppNotification( 6202): inbound: succ-0  fail-0
V/BluetoothOppNotification( 6202): inbound notification was removed.
V/BluetoothOppProvider( 6202): starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
,V/BluetoothOppProvider( 6202): created cursor android.database.sqlite.SQLiteCursor@8d8233b on behalf of 
D/WiFiOffLoadBroadcast( 6247): MCCMNC not supported: null
D/QRemote ( 5992): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 5992): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 5992): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,D/BluetoothAdapterService( 6202): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@391cf1d6
V/BluetoothSapService( 6202): Sap Service onCreate
V/WiFiOffLoadBroadcast( 6247): WiFiOffLoadBroadcast: android.net.wifi.SCAN_RESULTS
V/BluetoothSapService( 6202): action: android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothSapService( 6202): state: 12
V/BluetoothSapService( 6202): Starting SAP server process
V/BluetoothSapService( 6202): SAP Service startRfcommListenerThread
V/BluetoothSapService( 6202): Sap Service initRfcommSocket
D/BluetoothManagerService( 1030): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
W/BluetoothAdapter( 6202): getBluetoothService() called with no BluetoothManagerCallback
D/LGBluetoothServiceAdapter( 6202): [BTUI] createSocketChannel FD=82 mFd=81
V/BluetoothSapService( 6202): Succeed to create listening socket 
V/BluetoothSapService( 6202): Accepting socket connection...
D/WiFiOffLoadBroadcast( 6247): Not supported operator for automatic switch
W/sapd    ( 6472): type=1400 audit(0.0:161): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6508 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
W/sapd    ( 6472): type=1400 audit(0.0:162): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6508 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,D/PostponalbeReceiver( 6395): WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'null'.
,D/PostponalbeReceiver( 6395): WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'null'.
V/BT_SAP  ( 6472): Event pipe created
V/BT_SAP  ( 6472): create_server_socket qcom.sap.server
V/BT_SAP  ( 6472): created socket fd 6
,D/LgDataFeature( 6395): LgDataFeature() Constructor: none
D/LgDataFeature( 6395): LgDataFeature() Constructor Done, null
,I/wpa_supplicant( 6246): wlan0: CTRL-EVENT-SCAN-STARTED 
D/WifiMonitor( 1030): Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1030): WifiMonitor:wlan0 cnt=13 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1030): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1030): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
,W/ContextImpl( 6395): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.vsmandroid.gh.h:-1 com.mcafee.vsm.ext.common.a.d.a:-1 com.mcafee.vsm.ext.common.api.ExtUtils.stopApp:-1 
,D/SiteAdvisor( 6395): com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.google.android.browser/com.android.browser.BrowserActivity not supported
,D/SiteAdvisor( 6395): com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.amazon.cloud9/com.amazon.cloud9.BrowserActivity not supported
D/SiteAdvisor( 6395): com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.sec.android.app.sbrowser/com.sec.android.app.sbrowser.SBrowserMainActivity not supported
,D/SiteAdvisor( 6395): com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.sec.android.app.sbrowser/com.sec.android.app.sbrowser.SBrowserMainActivity not supported
D/SiteAdvisor( 6395): com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.htc.sense.browser/com.htc.sense.browser.BrowserActivity not supported
I/SiteAdvisor( 6395): com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Loading supported browsers: com.android.browser/com.android.browser.BrowserActivity; com.android.chrome/com.android.chrome.Main; 
D/SiteAdvisor( 6395): com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Here is the storedCurrentAppVersion: 3.1.2.1430
D/SiteAdvisor( 6395): com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Here about to commit perfs
,V/BluetoothOppNotification( 6202): new notify threadi!
,V/BluetoothOppNotification( 6202): send delay message
V/BluetoothOppProvider( 6202): starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
,V/BluetoothOppProvider( 6202): created cursor android.database.sqlite.SQLiteCursor@139bb817 on behalf of 
V/BluetoothOppNotification( 6202): mUpdateCompleteNotification = true
V/BluetoothOppProvider( 6202): starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
V/BluetoothOppProvider( 6202): created cursor android.database.sqlite.SQLiteCursor@42e9404 on behalf of 
V/BluetoothOppNotification( 6202): outbound: succ-0  fail-0
,V/BluetoothOppNotification( 6202): outbound notification was removed.
V/BluetoothOppProvider( 6202): starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
V/BluetoothOppProvider( 6202): created cursor android.database.sqlite.SQLiteCursor@38066ded on behalf of 
V/BluetoothOppNotification( 6202): inbound: succ-0  fail-0
V/BluetoothOppNotification( 6202): inbound notification was removed.
V/BluetoothOppProvider( 6202): starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
V/BluetoothOppProvider( 6202): created cursor android.database.sqlite.SQLiteCursor@2893422 on behalf of 
I/jxcore-log( 6138): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMultiplex.js
I/jxcore-log( 6138): 
,E/WifiMonitor( 1030): WifiMonitor:wlan0 cnt=14 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
E/WifiMonitor( 1030): handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
D/WifiMonitor( 1030): Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
E/WifiMonitor( 1030): WifiMonitor:wlan0 cnt=15 dispatchEvent: WPS-AP-AVAILABLE 
W/WifiMonitor( 1030): couldn't identify event type - WPS-AP-AVAILABLE 
,E/wpa_supplicant( 6246): USIM:  scard_init function
I/wpa_supplicant( 6246): Trying to associate with SSID 'NG700'
D/WifiMonitor( 1030): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
E/WifiMonitor( 1030): WifiMonitor:wlan0 cnt=16 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
E/WifiStateMachine( 1030):  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=2 known=0 got=2 bcn=0
E/WifiStateMachine( 1030):  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=2 known=0 got=2 bcn=0
E/WifiStateMachine( 1030):  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=2 known=0 got=2 bcn=0
E/WifiStateMachine( 1030):  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=2 known=0 got=2 bcn=0
,I/WifiNative-HAL( 1030): startHal
E/wifi    ( 1030): getStaticLongField sWifiHalHandle 0x988e08cc
E/WifiHAL ( 1030): Could not connect handle
D/wifi    ( 1030): halHandle = 0x0, mVM = 0xb487c280, mCls = 0x2022b2
I/WifiNative-HAL( 1030): Could not start hal
D/WifiNative-wlan0( 1030): doString: [BSS RANGE=0- MASK=0x21987]
E/WifiStateMachine( 1030):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 16 0 rt=121971  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
W/Settings( 1030): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1030): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1030): NETWORK_STATE_CHANGED_ACTION [SCANNING]
I/StatusBar.NetworkController( 1461): networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1461): mWifiConnected = false, mWifiLevel = 0
,D/StatusBar.NetworkController( 1461): refreshViews: Data not connected!! Set no data type icon / Roaming
D/PostponalbeReceiver( 6395): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
W/Settings( 1030): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1030): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1030): NETWORK_STATE_CHANGED_ACTION [CONNECTING]
E/WifiStateMachine( 1030):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 16 0 rt=121990  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
D/WifiServerServiceExt( 1030): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1030): setSupplicantStateASSOCIATING
I/StatusBar.NetworkController( 1461): networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1461): mWifiConnected = false, mWifiLevel = 0
,D/StatusBar.NetworkController( 1461): refreshViews: Data not connected!! Set no data type icon / Roaming
V/WiFiOffLoadBroadcast( 6247): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6247): MCCMNC not supported: null
D/QRemote ( 5992): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,D/QRemote ( 5992): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 5992): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
D/PostponalbeReceiver( 6395): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
V/WiFiOffLoadBroadcast( 6247): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6247): MCCMNC not supported: null
D/QRemote ( 5992): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 5992): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 5992): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
I/wpa_supplicant( 6246): wlan0: Associated with c0:ff:d4:d3:aa:48
,D/WifiMonitor( 1030): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
E/WifiMonitor( 1030): WifiMonitor:wlan0 cnt=17 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
D/WifiMonitor( 1030): Event [IFNAME=wlan0 Associated with c0:ff:d4:d3:aa:48]
E/WifiMonitor( 1030): WifiMonitor:wlan0 cnt=18 dispatchEvent: Associated with c0:ff:d4:d3:aa:48
D/WifiMonitor( 1030): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1030): WifiMonitor:wlan0 cnt=19 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/Tethering( 1030): sendTetherStateChangedBroadcast 1, 0, 0
E/WifiStateMachine( 1030):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 17 0 rt=122079  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
D/libc-netbsd(  314): default dns: query_ipv6=0, query_ipv4=0
E/WifiStateMachine( 1030):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 17 0 rt=122080  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
D/UsbSettingsReceiver( 6247): [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
D/UsbSettingsReceiver( 6247): [AUTORUN] sys.usb.config = ptp_only,adb
,D/UsbSettingsReceiver( 6247): [AUTORUN] sys.usb.state = ptp_only,adb
D/UsbSettingsReceiver( 6247): [AUTORUN] persist.sys.usb.config = ptp_only,adb
D/UsbSettingsReceiver( 6247): [AUTORUN] onReceive() : app userid = 0, current userid = 0
E/WifiStateMachine( 1030):  DisconnectedState CMD_ASSOCIATED_BSSID 18 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=122081
D/DSQN    ( 1030): DNSproblemNotiEnabled is disabled ignore DNS fail CB
E/WifiStateMachine( 1030):  ConnectModeState CMD_ASSOCIATED_BSSID 18 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=122081
E/WifiStateMachine( 1030):  DriverStartedState CMD_ASSOCIATED_BSSID 18 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=122082
E/WifiStateMachine( 1030):  SupplicantStartedState CMD_ASSOCIATED_BSSID 18 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=122082
E/WifiStateMachine( 1030):  DefaultState CMD_ASSOCIATED_BSSID 18 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=122083
,E/WifiStateMachine( 1030):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 19 0 rt=122084  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: FOUR_WAY_HANDSHAKE
I/StatusBar.NetworkController( 1461): networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1461): mWifiConnected = false, mWifiLevel = 0
D/WifiMonitor( 1030): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1030): WifiMonitor:wlan0 cnt=20 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
I/wpa_supplicant( 6246): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
W/Settings( 1030): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1030): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1030): NETWORK_STATE_CHANGED_ACTION [CONNECTING]
I/wpa_supplicant( 6246): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
D/StatusBar.NetworkController( 1461): refreshViews: Data not connected!! Set no data type icon / Roaming
E/WifiStateMachine( 1030):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 19 0 rt=122088  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: FOUR_WAY_HANDSHAKE
D/WifiMonitor( 1030): Event [IFNAME=wlan0 WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]]
E/WifiMonitor( 1030): WifiMonitor:wlan0 cnt=21 dispatchEvent: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
E/WifiStateMachine( 1030):  DisconnectedState CMD_TETHER_STATE_CHANGE 0 0
W/WifiMonitor( 1030): couldn't identify event type - WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
D/WifiMonitor( 1030): Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]]
E/WifiMonitor( 1030): WifiMonitor:wlan0 cnt=22 dispatchEvent: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
E/WifiStateMachine( 1030):  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
E/WifiMonitor( 1030): handleEvent 1  Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
E/WifiStateMachine( 1030):  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
D/WifiMonitor( 1030): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1030): WifiMonitor:wlan0 cnt=23 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
E/WifiStateMachine( 1030):  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1030):  DefaultState CMD_TETHER_STATE_CHANGE 0 0
I/StatusBar.NetworkController( 1461): networkInfo=[type: WIFI[], state: CONNECTING/AUTHENTICATING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1461): mWifiConnected = false, mWifiLevel = 0
,D/UsbSettingsControl( 6247): [AUTORUN] getUsbConnected() : connected=true
D/UsbSettingsReceiver( 6247): [AUTORUN] onReceive() : availableList=[wlan0]
D/UsbSettingsReceiver( 6247): [AUTORUN] onReceive() : activeList=[]
D/UsbSettingsReceiver( 6247): [AUTORUN] onReceive() : errorList=[]
D/UsbSettingsControl( 6247): [AUTORUN] isAutorunTimer() : mAutorunChanging=false
D/UsbSettingsReceiver( 6247): [AUTORUN] onReceive() : TetherState Changed=wlan0
D/UsbSettingsControl( 6247): [AUTORUN] setTetherStatus() : status=false
W/Settings( 1030): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1030): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1030): NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
E/WifiStateMachine( 1030):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 20 0 rt=122093  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: GROUP_HANDSHAKE
E/WifiStateMachine( 1030):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 20 0 rt=122093  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: GROUP_HANDSHAKE
D/StatusBar.NetworkController( 1461): refreshViews: Data not connected!! Set no data type icon / Roaming
E/WifiStateMachine( 1030):  DisconnectedState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=122094
E/WifiStateMachine( 1030):  ConnectModeState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=122094
D/WifiNative-wlan0( 1030): doString: [STATUS]
D/WifiMonitor( 1030): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1030): WifiMonitor:wlan0 cnt=24 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/WifiServerServiceExt( 1030): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1030): setSupplicantStateFOUR_WAY_HANDSHAKE
D/WifiNative-wlan0( 1030):    returned bssid=c0:ff:d4:d3:aa:48 ssid=NG700 id=0 mode=station pairwise_cipher=CCMP group_cipher=CCMP key_mgmt=WPA2-PSK wpa_state=COMPLETED p2p_device_address=02:9a:02:7b:60:ac address=c4:9a:02:7b:60:ac uuid=530d3fd0-1ba3-5409-a336-ff4e42af59a2
D/PostponalbeReceiver( 6395): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
I/WifiServiceExtension( 1030): setVHTCapabilityType  : false
V/WiFiOffLoadBroadcast( 6247): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6247): MCCMNC not supported: null
I/WifiServerServiceExt( 1030): wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
I/WifiServerServiceExt( 1030): setKeepAlivePacketInterval msec : 60
D/QRemote ( 5992): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,D/QRemote ( 5992): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 5992): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
W/Settings( 1030): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1030): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1030): NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
D/PostponalbeReceiver( 6395): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
I/StatusBar.NetworkController( 1461): networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1461): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1461): refreshViews: Data not connected!! Set no data type icon / Roaming
W/Settings( 1030): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1030): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1030): NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
I/StatusBar.NetworkController( 1461): networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1461): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1461): refreshViews: Data not connected!! Set no data type icon / Roaming
D/ConnectivityService( 1030): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
,D/ConnectivityService( 1030): Got NetworkAgent Messenger
D/ConnectivityService( 1030): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
D/ConnectivityService( 1030): NetworkAgent connected
E/WifiConfigStore( 1030): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/WifiNative-wlan0( 1030): doBoolean: SET_NETWORK 0 bssid any
V/WiFiOffLoadBroadcast( 6247): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WifiNative-wlan0( 1030): SET_NETWORK 0 bssid any: returned true
D/WifiNative-wlan0( 1030): doBoolean: SAVE_CONFIG
D/WiFiOffLoadBroadcast( 6247): MCCMNC not supported: null
D/WifiNative-wlan0( 1030): SAVE_CONFIG: returned true
E/WifiConfigStore( 1030): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/WifiNative-wlan0( 1030): doBoolean: SET_NETWORK 0 bssid any
D/WifiNative-wlan0( 1030): SET_NETWORK 0 bssid any: returned true
D/WifiNative-wlan0( 1030): doBoolean: SAVE_CONFIG
,D/QRemote ( 5992): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 5992): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 5992): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
D/PostponalbeReceiver( 6395): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
V/WiFiOffLoadBroadcast( 6247): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WifiNative-wlan0( 1030): SAVE_CONFIG: returned true
D/CommandListener(  314): Setting iface cfg
D/WiFiOffLoadBroadcast( 6247): MCCMNC not supported: null
,E/WifiStateMachine( 1030): Start Dhcp Watchdog 1
E/WifiStateMachine( 1030):  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 23 0 rt=122154  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine( 1030):  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 23 0 rt=122155  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine( 1030):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 23 0 rt=122155  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
D/WifiServerServiceExt( 1030): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1030): setSupplicantStateGROUP_HANDSHAKE
E/WifiStateMachine( 1030):  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 24 0 rt=122156  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine( 1030):  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 24 0 rt=122157  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine( 1030):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 24 0 rt=122157  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
D/QRemote ( 5992): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 5992): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
E/WifiStateMachine( 1030):  ObtainingIpState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:-1564176889] from screen [on:0 period:-1564176889]
I/QRemote ( 5992): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
D/DhcpStateMachine( 1030): StoppedState
D/DhcpStateMachine( 1030): StoppedState{ when=-5ms what=196609 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine( 1030): WaitBeforeStartState
E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-1564176888]
D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
D/PostponalbeReceiver( 6395): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
D/StatusBar.NetworkController( 1461): refreshViews: Data not connected!! Set no data type icon / Roaming
,D/ConnectivityService( 1030): updateNetworkScore for NetworkAgentInfo [WIFI () - 100] to 60
E/WifiStateMachine( 1030):  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1030):  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1030):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1030):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1030):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1030):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
,D/ConnectivityService( 1030): Update of LinkProperties for NetworkAgentInfo [WIFI () - 100]; created=false
V/WiFiOffLoadBroadcast( 6247): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WifiServerServiceExt( 1030): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1030): setSupplicantStateCOMPLETED
D/WifiServerServiceExt( 1030): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1030): setSupplicantStateCOMPLETED
E/WifiStateMachine( 1030):  ObtainingIpState CMD_PRE_DHCP_ACTION 0 0 txpkts=1,0,0
E/WifiStateMachine( 1030):  L2ConnectedState CMD_PRE_DHCP_ACTION 0 0 txpkts=1,0,0
D/WifiNative-wlan0( 1030): doBoolean: DRIVER SETSUSPENDMODE 0
D/WiFiOffLoadBroadcast( 6247): MCCMNC not supported: null
D/QRemote ( 5992): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,D/QRemote ( 5992): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 5992): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
I/wpa_supplicant( 6246): wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 0
,D/WifiNative-wlan0( 1030): DRIVER SETSUSPENDMODE 0: returned true
D/WifiNative-wlan0( 1030): doBoolean: SET ps 0
D/WifiNative-wlan0( 1030): SET ps 0: returned true
D/WifiNative-wlan0( 1030): doBoolean: DRIVER BTCOEXMODE 1
I/wpa_supplicant( 6246): wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 1
D/WifiNative-wlan0( 1030): DRIVER BTCOEXMODE 1: returned true
E/WifiStateMachine( 1030): CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
D/LGWifiP2pService( 1030): InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@1d0db44c target=com.android.internal.util.StateMachine$SmHandler }
V/DhcpStateMachine( 1030): Current State is mWaitBeforeStartState.
D/LGWifiP2pService( 1030): P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@1d0db44c target=com.android.internal.util.StateMachine$SmHandler }
V/LgDhcpStateMachineHelper( 1030): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
V/LgDhcpStateMachineHelper( 1030): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700" is not exist.
D/DhcpStateMachine( 1030): WaitBeforeStartState{ when=0 what=196615 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine( 1030): DHCP Start wake lock is acquired.
,I/jxcore-log( 6138): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
I/jxcore-log( 6138): 
,I/jxcore-log( 6138): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
I/jxcore-log( 6138): 
,I/jxcore-log( 6138): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js
I/jxcore-log( 6138): 
D/DhcpStateMachine( 1030): DHCPV4 request on wlan0
V/LgDhcpStateMachineHelper( 1030): [bssid] hash key :c0:ff:d4:d3:aa:48
D/LgDhcpStateMachineHelper( 1030): dhcp.ap.macaddress = c0:ff:d4:d3:aa:48
,I/jxcore-log( 6138): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
I/jxcore-log( 6138): 
W/dhcpcd  ( 6506): type=1400 audit(0.0:163): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6508 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,W/dhcpcd  ( 6506): type=1400 audit(0.0:164): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6508 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
I/dhcpcd  ( 6506): version 5.5.6 starting
E/dhcpcd  ( 6506): get_duid: m
,D/dhcpcd  ( 6506): wlan0: using ClientID 01:c4:9a:02:7b:60:ac
D/dhcpcd  ( 6506): wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason PREINIT
,D/dhcpcd  ( 6506): getUsingAPMacAddress: c0:ff:d4:d3:aa:48 , return 1
D/dhcpcd  ( 6506): [read_lease] unlink /data/misc/dhcp/dhcpcd-wlan0.lease, link /data/misc/dhcp/dhcpcd-wlan0-c0:ff:d4:d3:aa:48.lease2
D/dhcpcd  ( 6506): wlan0: reading lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
,I/dhcpcd  ( 6506): wlan0: rebinding lease of 192.168.1.141
,D/dhcpcd  ( 6506): wlan0: sending REQUEST (xid 0x45f354a7), next in 4.58 seconds
E/WifiStateMachine( 1030):  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1030):  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1030):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
,E/WifiStateMachine( 1030):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
,E/WifiStateMachine( 1030):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1030):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
D/ConnectivityService( 1030): Update of LinkProperties for NetworkAgentInfo [WIFI () - 100]; created=false
I/dhcpcd  ( 6506): wlan0: acknowledged 192.168.1.141 from 192.168.1.1
,I/dhcpcd  ( 6506): wlan0: leased 192.168.1.141 for 86400 seconds
D/dhcpcd  ( 6506): wlan0: adding IP address 192.168.1.141/24
D/dhcpcd  ( 6506): wlan0: adding route to 192.168.1.0/24
D/dhcpcd  ( 6506): wlan0: adding default route via 192.168.1.1
D/dhcpcd  ( 6506): wlan0: writing lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
D/dhcpcd  ( 6506): getUsingAPMacAddress: c0:ff:d4:d3:aa:48 , return 1
D/dhcpcd  ( 6506): write_lease_ext: /data/misc/dhcp/dhcpcd-wlan0-c0:ff:d4:d3:aa:48.lease2
D/dhcpcd  ( 6506): wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason REBOOT
,E/WifiStateMachine( 1030):  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1030):  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1030):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1030):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1030):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1030):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
,D/ConnectivityService( 1030): Update of LinkProperties for NetworkAgentInfo [WIFI () - 100]; created=false
,D/DhcpStateMachine( 1030): DHCPV4 succeeded on wlan0
,D/LgDhcpStateMachineHelper( 1030): CheckDhcpDirectory [Lease File Count] : 3
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
I/wpa_supplicant( 6246): wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
D/LGWifiP2pService( 1030): InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1030): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0( 1030): DRIVER BTCOEXMODE 2: returned true
D/WifiNative-wlan0( 1030): doBoolean: DRIVER SETSUSPENDMODE 1
I/wpa_supplicant( 6246): wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 1
D/WifiNative-wlan0( 1030): DRIVER SETSUSPENDMODE 1: returned true
D/WifiNative-wlan0( 1030): doBoolean: SET ps 1
D/WifiNative-wlan0( 1030): SET ps 1: returned true
,D/ConnectivityService( 1030): Update of LinkProperties for NetworkAgentInfo [WIFI () - 100]; created=false
E/WifiStateMachine( 1030):  ObtainingIpState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
E/WifiStateMachine( 1030):  L2ConnectedState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
E/WifiStateMachine( 1030): WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
D/ConnectivityService( 1030): ignoring duplicate network state non-change
I/StatusBar.NetworkController( 1461): networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1461): mWifiConnected = false, mWifiLevel = 0
W/Settings( 1030): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1030): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1030): NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
,D/StatusBar.NetworkController( 1461): refreshViews: Data not connected!! Set no data type icon / Roaming
D/ConnectivityService( 1030): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,I/StatusBar.NetworkController( 1461): networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1461): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1461): refreshViews: Data not connected!! Set no data type icon / Roaming
D/ConnectivityService( 1030): Adding iface wlan0 to network 100
,W/Settings( 1030): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1030): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1030): NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
E/WifiStateMachine( 1030): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
D/PostponalbeReceiver( 6395): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,D/WifiHS20( 1030): [PASSPOINT] passpointNotification: hs20AP list is checked
E/ConnectivityService( 1030): Unexpected mtu value: 0, wlan0
D/ConnectivityService( 1030): Adding Route [fe80::/64 -> :: wlan0] to network 100
W/Settings( 1030): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1030): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1030): NETWORK_STATE_CHANGED_ACTION [CONNECTED]
D/ConnectivityService( 1030): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 100
D/WifiHS20( 1030): [PASSPOINT] passpointNotification: hs20AP list is checked
D/ConnectivityService( 1030): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 100
D/ConnectivityService( 1030): addLocalRoutetoDefaultNetwork
D/ConnectivityService( 1030): defaultNAI is null or Wi-Fi no need to add Loacal route to default network. WiFi netid = 100
D/ConnectivityService( 1030): Setting Dns servers for network 100 to [/192.168.1.1]
W/Settings( 1030): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1030): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1030): NETWORK_STATE_CHANGED_ACTION [CONNECTED]
V/WfdStateTracker( 1974): handleWifiStateChangedEvent: 1
,I/StatusBar.NetworkController( 1461): networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1461): mWifiConnected = true, mWifiLevel = 2
D/StatusBar.NetworkController( 1461): refreshViews: Data not connected!! Set no data type icon / Roaming
D/Nat464Xlat( 1030): requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
D/ConnectivityService( 1030): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService( 1030): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService( 1030): rematching NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService( 1030):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService( 1030):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1030):     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
D/ConnectivityService( 1030):   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1030):     satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:true
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1030): DefaultState{ when=-1ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1030): Connected
D/ConnectivityService( 1030): currentScore = 0, newScore = 20
D/ConnectivityService( 1030):    accepting network in place of null
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1030): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1030): Checking http://clients3.google.com/generate_204 on "NG700"
,D/libc-netbsd(  314): res_queryN name = clients3.google.com, class = 1, type = 28
D/ConnectivityService( 1030): sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1030): Setting tx/rx TCP buffers to 524288,1048576,2097152,262144,524288,1048576
I/StatusBar.NetworkController( 1461): networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1461): mWifiConnected = true, mWifiLevel = 2
D/StatusBar.NetworkController( 1461): refreshViews: Data not connected!! Set no data type icon / Roaming
,D/TelephonyNetworkFactory-1( 1867): new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    ( 1030): new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    ( 1030):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/TelephonyNetworkFactory-1( 1867):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
E/ConnectivityService( 1030): [lg_data] Adding agent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::c69a:2ff:fe7b:60ac/64,192.168.1.141/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
D/CSLegacyTypeTracker( 1030): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
D/ConnectivityService( 1030): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService( 1030): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/CSLegacyTypeTracker( 1030): [e] list.add(nai) empty : false size: 1
V/WiFiOffLoadBroadcast( 6247): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/ConnectivityService( 1030): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::c69a:2ff:fe7b:60ac/64,192.168.1.141/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
D/libc-netbsd(  314): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  314): res_queryN name = 2.android.pool.ntp.org, class = 1, type = 1
,D/LocSvc_java( 1030): Sending msg: 4 arg1:1 arg2:1
D/LocSvc_java( 1030): getAGpsConnectionInfo connType - 4
D/LocSvc_java( 1030): updateNetworkState connTyp: 4 available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/libc-netbsd(  314): res_queryN name = 2.android.pool.ntp.org., class = 1, type = 1
D/LocSvc_java( 1030): ignore wifi update if we are not in OPENING or CLOSING
D/LocSvc_java( 1030): Sending msg: 5 arg1:0 arg2:1
D/DSQN    ( 1030): DNSproblemNotiEnabled is disabled ignore DNS fail CB
D/ConnectivityService( 1030): validation of new default Network = false
D/ConnectivityService( 1030): Default network via Wi-Fi connected. start DSQN
D/DSQN    ( 1030): enableDataServiceNotify 
D/DSQN    ( 1030): start dsqn bin
D/libc-netbsd(  314): default dns: query_ipv6=0, query_ipv4=1
D/WiFiOffLoadBroadcast( 6247): MCCMNC not supported: null
D/libc-netbsd(  314): res_queryN name = europe.pool.ntp.org, class = 1, type = 1
,D/libc-netbsd(  314): res_queryN name = clients3.google.com, class = 1, type = 1
D/ConnectivityService( 1030): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 100]
,D/ConnectivityService( 1030):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1030):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1030): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityManager.CallbackHandler( 1461): CM callback handler got msg 524290
W/dsqn    ( 6557): type=1400 audit(0.0:165): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6508 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
W/dsqn    ( 6557): type=1400 audit(0.0:166): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6508 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
D/QRemote ( 5992): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 5992): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
V/NetworkPolicy( 1030): [LG_RESTRICTED] checkMobilePolicy_type()
,D/TelephonyIcons( 1461): null signal icon name: drawable/stat_sys_signal_null
D/StatusBar.NetworkController( 1461): refreshViews: Data not connected!! Set no data type icon / Roaming
D/StatusBar.NetworkController( 1461): refreshViews: Data not connected!! Set no data type icon / Roaming
I/QRemote ( 5992): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
D/PostponalbeReceiver( 6395): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
E/DSQN    ( 6557): DSQN ssw
D/libc-netbsd(  314): res_queryN name = europe.pool.ntp.org succeed
,V/WiFiOffLoadBroadcast( 6247): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 6247): MCCMNC not supported: null
D/libc-netbsd(  314): res_queryN name = clients3.google.com succeed
D/QRemote ( 5992): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 5992): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 5992): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,D/PostponalbeReceiver( 6395): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
I/PCSuite ( 6320): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
D/PCSuite ( 6320): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 6247): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/LGDataListener(  314): argv[0]=dsqncommand
D/LGDataListener(  314): argv[1]=wlan0
D/LGDataListener(  314): argv[2]=1
D/LGDataListener(  314): notifyDSQN DSQN STARTMONITOR wlan0 1
D/DSQN    ( 1030): DSQM DsqnNotification wlan0  1
D/DSQN    ( 1030): start to monitor internet connection
D/WiFiOffLoadBroadcast( 6247): MCCMNC not supported: null
D/QRemote ( 5992): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 5992): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
D/QRemote ( 5992): [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
,I/QRemote ( 5992): [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
I/QRemote ( 5992): [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
D/PostponalbeReceiver( 6395): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1030): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Tue, 02 Feb 2016 16:15:38 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1454429738573], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1454429738553]}
I/PCSuite ( 6320): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1030): Don't send network conditions - lacking user consent.
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1030): Validated
D/PCSuite ( 6320): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
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
D/ConnectivityManager.CallbackHandler( 1461): CM callback handler got msg 524290
D/ConnectivityService( 1030): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
D/WIFI    ( 1030): new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    ( 1030):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/TelephonyNetworkFactory-1( 1867): new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/TelephonyNetworkFactory-1( 1867):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
V/WiFiOffLoadBroadcast( 6247): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6247): MCCMNC not supported: null
D/QRemote ( 5992): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 5992): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
D/QRemote ( 5992): [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
I/QRemote ( 5992): [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
I/QRemote ( 5992): [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
,D/TelephonyIcons( 1461): null signal icon name: drawable/stat_sys_signal_null
D/StatusBar.NetworkController( 1461): refreshViews: Data not connected!! Set no data type icon / Roaming
D/StatusBar.NetworkController( 1461): refreshViews: Data not connected!! Set no data type icon / Roaming
D/LocSvc_java( 1030): NTP server : europe.pool.ntp.org
D/LocSvc_java( 1030): NTP server returned: 1454429738466 (Tue Feb 02 17:15:38 GMT+01:00 2016) reference: 124343 certainty: 55 system time offset: -174
D/LocSvc_java( 1030): Sending msg: 10 arg1:0 arg2:1
,E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-65 f=2412 sc=60 link=65 tx=0.5, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1564173880] gl rssi=-65 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-65 f=2412 sc=60 link=65 tx=0.5, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-1564173879] gl rssi=-65 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
,D/StatusBar.NetworkController( 1461): refreshViews: Data not connected!! Set no data type icon / Roaming
V/WifiInternetCheck( 1030): Single check msg out of sync, ignoring.
,D/ConnectivityService( 1030): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering( 1030): MasterInitialState.processMessage what=3
D/libc-netbsd(  314): default dns: query_ipv6=0, query_ipv4=1
,D/libc-netbsd(  314): res_queryN name = 2.android.pool.ntp.org, class = 1, type = 1
D/libc-netbsd(  314): res_queryN name = 2.android.pool.ntp.org succeed
,D/PostponalbeReceiver( 6395): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
W/ContextImpl( 6395): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
,D/GpsLocationProvider( 1030): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
I/NetworkMonitor( 5264): type=WIFI subType= reason=null isConnected=true
,D/AlarmManagerService( 1030): Setting time of day to sec=1454429741
,W/AlarmManagerService( 1030): Unable to set rtc to 1454429741: Invalid argument
,I/[SystemUI]Clock( 1461): onReceive = android.intent.action.TIME_SET
I/SecureClockService( 1974): Intent.ACTION_TIME_CHANGED 
D/LIA_Informant_Tips_DateChangeManager( 2730): onReceive() : ACTION_TIME_CHANGED
I/LgeClockWidgetControlView( 1461): time changed, timezoneChanged : false
D/KeyguardUpdateMonitor( 1461): handleTimeUpdate
I/LIA_Informant_Tips_LogTracer( 2730): [Log Tracer - Schedule Transition] Time Change Event Received : 2016-02-02 17:15:41...... Request
I/LIA_Informant_Tips_LogTracer( 2730): [Log Tracer - Schedule Transition] UserGuide, DATE_UPDATE : working count : 6, total count : 163, new day : false...... Request
D/LIA_Informant_Tips_DateChangeManager( 2730): DateInfo : SmartTips Total Working Day Count = 163
D/LIA_Informant_Tips_DateChangeManager( 2730): DateInfo : UserGuide Working Duration Count = 6
D/LIA_Informant_Tips_DateChangeManager( 2730): DateInfo : Last Date Check Time = 2016-02-02 17:15:41
I/ActivityManager( 1030): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=6595 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
W/ActivityManager( 1030): getTasks: caller 10029 is using old GET_TASKS but privileged; allowing
I/[LGHome]LGDateChangeReceiver( 2086): [LGDateChangeReceiver.java:78:updateCalendarShortcut()]date=2 currentDate=-1 dayofweek=3 currentDayOfWeek=-1
,I/[LGHome]LGCalendarIcon( 2086): [LGCalendarIcon.java:214:makeCalendarBitmap()]Locale = en_US dayofweek= Tue date= 2
I/[LGHome]LGCalendarIcon( 2086): [LGCalendarIcon.java:214:makeCalendarBitmap()]Locale = en_US dayofweek= Tue date= 2
,I/[LGHome]Launcher( 2086): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
D/[Concierge]Service( 2629): onStartCommand(). Type : 9
,I/GoogleURLConnFactory( 2138): Using platform SSLCertificateSocketFactory
I/ActivityManager( 1030): Start proc com.google.android.apps.books for service com.google.android.apps.books/.service.SyncService: pid=6614 uid=10054 gids={50054, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/art     (  347): Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 470us total 31.215ms
,I/art     (  347): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 398us total 18.908ms
,I/AppUp4:AppBoxCP( 6595): onCreate
W/AppUp4:DB( 6595):  [AppBoxDatabaseHelper] construct
I/art     (  347): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 349us total 16.478ms
I/AppUp4:DB( 6595):  setFingerPrint start
I/AppUp4:DB( 6595):  newfinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys SDK version = 21
,I/AppUp4:DB( 6595):  beforefinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys
I/AppUp4:DB( 6595):  SDK version = 21
I/AppUp4:DB( 6595):  beforefinger == newfinger no write in DB
I/ActivityManager( 1030): Start proc com.android.gallery3d for service com.android.gallery3d/com.lge.gallery.picasa.PicasaService: pid=6634 uid=10027 gids={50027, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
,D/AppUp4:AppBoxApplication( 6595): AppBoxApplication onCreate()
I/NetworkStateForAutoUpdateMonitor( 6595): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 6595): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 6595): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 6595): [onReceive] request level :IDLE....
,I/AppUp4:CustModeStarterReceiver( 6595): onReceive
W/ResourcesManager( 6634): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6634): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 6634): Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
W/ResourcesManager( 6634): Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
,D/LgDataFeature( 6595): LgDataFeature() Constructor: none
,D/LgDataFeature( 6595): LgDataFeature() Constructor Done, null
D/AppUp4:CustFacade( 6595): Context : android.app.ReceiverRestrictedContext@e8881f1
D/AppUp4:CustFacade( 6595): isCustomizationCompleted : false
D/AppUp4:CustFacade( 6595): isPhone : true
D/AppUp4:CustModeStarterReceiver( 6595): begin check event
I/AppUp4:CustModeStarterReceiver( 6595): Event For GoodConnectivity
D/AppUp4:CustModeStarterReceiver( 6595): runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
,D/AppUp4:CustModeStarterReceiver( 6595): call method handleAsyncCustNotification.
D/AppUp4:CustModeStarterReceiver( 6595): handleAsync isTriedOnce : false
E/AppUp4:CustModeStarterReceiver( 6595): handleAsyncCustNotification do not startCustService
I/ActivityManager( 1030): Killing 5583:com.google.android.apps.plus/u0a97 (adj 15): empty #17
,D/LGDMClient( 3948): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 3948): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,W/ContextImpl( 3948): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
W/libprocessgroup( 1030): failed to open /acct/uid_10097/pid_5583/cgroup.procs: No such file or directory
I/AppConfig( 6634): Total System Memory = 2995761152
,D/SystemHelper( 6634): region [EU], country [EU], operator [OPEN], sub-operator []
I/ReaderUtils( 6614): PortraitW 1440 LandscapeW 2392 SmallestSize 1340 LargestSize 2392 textZoom 4.4999995 isTablet false Memory 256
W/ContextImpl( 3948): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,I/art     ( 1030): Explicit concurrent mark sweep GC freed 78912(3MB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 44MB/66MB, paused 1.429ms total 98.580ms
I/ActivityManager( 1030): Start proc com.android.chrome for service com.android.chrome/com.google.android.apps.chrome.sync.ChromeBrowserSyncAdapterService: pid=6659 uid=10057 gids={50057, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/LGDMClient( 3948): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=3, isUserType=1
V/DownloadManager( 3301): Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
V/DownloadManager( 3301): DownloadService onCreate
,I/DownloadManager( 3301): in removeSpuriousFiles
V/DownloadManager( 3301): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3301): created cursor android.database.sqlite.SQLiteCursor@3f4873a4 on behalf of 3301
I/DownloadManager( 3301): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGMyGuide_4.40.09_COM_COM_20150430011620058_RELG-D855.apk
I/DownloadManager( 3301): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGBackup_4.50.37_COM_COM_20150608234245157.apk
I/DownloadManager( 3301): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/CalendarProvider_4.2.8_COM_COM_20150304234552863_RELG-D855.apk
I/DownloadManager( 3301): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calendar_4.40.16_COM_COM_20150304234554754_RELG-D855.apk
I/DownloadManager( 3301): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.10_COM_COM_20150521235426173_RELG-D855.apk
I/DownloadManager( 3301): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQVoiceplusN_2.3.3_COM_COM_20150604065210803.apk
I/DownloadManager( 3301): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.11_COM_COM_v2_20150911144028620_RELG-D855_21.apk
I/DownloadManager( 3301): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQMemoplus(LG-D855_user)_20150902050954661.apk
I/DownloadManager( 3301): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/RemoteCall_4.1.10_COM_COM_20150817053748728.apk
I/DownloadManager( 3301): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/rspermlge(6713)_20150901080430397.apk
I/DownloadManager( 3301): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGBackup_4.51.57_COM_COM_8275_2_20151201044833536_RELG-D855_21.apk
I/DownloadManager( 3301): in trimDatabase
V/DownloadManager( 3301): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
V/DownloadManager( 3301): created cursor android.database.sqlite.SQLiteCursor@19ed650d on behalf of 3301
D/LGDMClient( 3948): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 3948): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
I/LGDMClient( 3948): [DmServiceProcessor.java] [processNetworkChanged()] : [91] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
,I/ActivityManager( 1030): Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=6682 uid=10023 gids={50023, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
V/DownloadManager( 3301): DownloadService onStartCommand
,V/DownloadManager( 3301): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3301): created cursor android.database.sqlite.SQLiteCursor@113e5ad3 on behalf of 3301
,V/DownloadManager( 3301): processing inserted download 1
,W/ContextImpl( 3948): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:141 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:180 android.app.IntentService$ServiceHandler.handleMessage:65 
V/DownloadManager( 3301): processing inserted download 4
V/DownloadManager( 3301): processing inserted download 7
V/DownloadManager( 3301): processing inserted download 8
V/DownloadManager( 3301): processing inserted download 9
V/DownloadManager( 3301): processing inserted download 10
V/DownloadManager( 3301): processing inserted download 16
V/DownloadManager( 3301): processing inserted download 17
V/DownloadManager( 3301): processing inserted download 18
,V/DownloadManager( 3301): processing inserted download 21
V/DownloadManager( 3301): processing inserted download 22
,E/LGDMClient( 3948): [DmNotiService.java] [onCreate()] : [148] : DmNotiService.onCreate()
D/LGDMClient( 3948): [DmNotiService.java] [onStartCommand()] : [182] : in the new onStartCommand()
D/LGDMClient( 3948): [DmNotiService.java] [handleStart()] : [203] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
,D/GpsLocationProvider( 1030): updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
V/DownloadManager( 3301): DownloadService onDestroy
,I/art     ( 2138): Explicit concurrent mark sweep GC freed 25400(1469KB) AllocSpace objects, 2(32KB) LOS objects, 51% free, 30MB/62MB, paused 943us total 22.604ms
W/ResourcesManager( 6682): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 6682): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 6682): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
W/ResourcesManager( 6682): Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
W/GAV2    ( 6614): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
E/GpsLocationProvider( 1030): No APN found to select.
,I/BooksApp( 6614): Created application version: 3.2.35 (30235)
,I/VacuumService( 2138): Vacuum at: now=1454429742230 tag=VacuumService
,I/ActivityManager( 1030): Killing 5883:com.google.android.apps.docs/u0a61 (adj 15): empty #17
E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-58 f=2412 sc=60 link=72 tx=5.2, 0.0, 0.0  rx=4.5 bcn=0 [on:0 tx:0 rx:0 period:2866] from screen [on:0 period:-1564171003] gl rssi=-58 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-58 f=2412 sc=60 link=72 tx=5.2, 0.0, 0.0  rx=4.5 bcn=0 [on:0 tx:0 rx:0 period:2] from screen [on:0 period:-1564171001] gl rssi=-58 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
W/libprocessgroup( 1030): failed to open /acct/uid_10061/pid_5883/cgroup.procs: No such file or directory
I/LGEmail ( 6682): [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,D/StatusBar.NetworkController( 1461): refreshViews: Data not connected!! Set no data type icon / Roaming
W/DriveInitializer( 2356): Background init thread started
,D/LGEmail ( 6682): user build Type == true (at Util.java isUserModeBuildType 3507)[v:6.41.18]
E/VoldCmdListener(  278): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  278): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.gms/files/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
I/BooksSync( 6614): Starting books sync
W/ContextImpl( 2356): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.gms/files
,V/GLSActivity( 2138): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/DriveInitializer( 2356): Awaiting to be initialized
,D/DelayedSyncController( 6659): Delaying sync.
I/ActivityManager( 1030): Killing 5944:com.lge.eula/1000 (adj 15): empty #17
,W/ResourceType( 6682): No package identifier when getting value for resource number 0x00000000
,D/libc-netbsd(  314): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  314): res_queryN name = www.google.com, class = 1, type = 1
,D/libc-netbsd(  314): res_queryN name = www.google.com succeed
,D/libc-netbsd(  314): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  314): res_queryN name = clients3.google.com, class = 1, type = 1
D/libc-netbsd(  314): res_queryN name = clients3.google.com succeed
W/libprocessgroup( 1030): failed to open /acct/uid_1000/pid_5944/cgroup.procs: No such file or directory
,V/WifiInternetCheck( 1030): isHttpConnectionAvailable - We got a valid response : 204
,W/DriveInitializer( 2356): Background init thread ended
,I/GoogleURLConnFactory( 2138): Using platform SSLCertificateSocketFactory
,E/Auth.Api.Credentials( 2356): [CredentialSyncAdapter] Unknown sync event.
D/LgDataFeature( 6682): LgDataFeature() Constructor: none
D/LgDataFeature( 6682): LgDataFeature() Constructor Done, null
,W/Uploader( 2138): No account for auth token provided
D/libc-netbsd(  314): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  314): res_queryN name = play.googleapis.com, class = 1, type = 1
,D/libc-netbsd(  314): res_queryN name = play.googleapis.com succeed
,D/eas_req ( 6682): ---addEventToQueue() easCode=2, requestId=0 (at EasSupport.java addEventToQueue 69)
,D/BooksSync( 6614): started syncMyEbooks
,I/HubEmail( 6682): JNI_OnLoad()
I/HubEmail( 6682): -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 6682): registerNatives()
I/HubEmail( 6682): -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 6682): registerNativeMethods()
I/HubEmail( 6682): -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
,W/art     ( 6682): JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
W/Settings( 6682): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 6682): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/LgeMiscReceiver( 3258): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 3258): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 3258): networkInfo.isConnected() = true
D/PhoneState( 3258): setPdpRejectCasuse : false
D/libc-netbsd(  314): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  314): res_queryN name = static-avc.lglime.com, class = 1, type = 1
,I/ActivityManager( 1030): Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=6750 uid=10062 gids={50062, 9997, 4002, 3003, 1028} abi=armeabi-v7a
,V/GLSActivity( 2138): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/GLSUser ( 2138): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2138): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2138): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2138): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2138): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/DrmBroadcastReceiver( 6750): Receive CONNECTIVITY_ACTION
D/DrmBroadcastReceiver( 6750): 1  network is available. Sync DRM Time with NTP
V/DrmService( 6750): Service onCreate
D/DrmService( 6750): Received new request = 2
D/libc-netbsd(  314): res_queryN name = static-avc.lglime.com succeed
I/DrmSntpClient( 6750): Start Sync process
D/DrmSntpClient( 6750): Server : 0
,D/libc-netbsd(  314): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  314): res_queryN name = pool.ntp.org, class = 1, type = 1
I/ActivityManager( 1030): Start proc com.lge.sizechangable.weather for broadcast com.lge.sizechangable.weather/.layout.WeatherWidget: pid=6770 uid=10085 gids={50085, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/libc-netbsd(  314): res_queryN name = pool.ntp.org succeed
W/Uploader( 2138): No account for auth token provided
D/DelayedSyncController( 6659): Delaying sync.
,V/FormManager( 6294): There are no updated forms. The schedule will be deleted.
V/FormManager( 6294): Alarm would be updated, because LastCheckTime has been updated.
V/NotificationService( 1030): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,D/ZenLog  ( 1030): intercepted: 0|com.google.android.gms|1|null|10005,none
V/NotificationService( 1030): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1030): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1030): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1030): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
W/GLSActivity( 2138): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2138): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2138): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2138): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2138): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2138): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2138): 	at android.os.Binder.execTransact(Binder.java:446)
I/LGDrmClient( 6750): _DRM_ServiceGet() : Bind lgdrm service
V/ILGDrmService(  324): eDRM_SetDRMTime +++
I/LGDRM   (  324): [DRM] SET TIME : YR=2016, MON=2, DAY=2
I/LGDRM   (  324): [DRM] SET TIME : HR=16, MIN=15, SEC=43
W/ResourcesManager( 1411): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 1411): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
E/BooksAccountManager( 6614): Authentication error
E/BooksAccountManager( 6614): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6614): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6614): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6614): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6614): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6614): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6614): null auth token
V/ILGDrmService(  324): eDRM_SetDRMTime ---
D/LgeQuickCoverNLService( 1411): onNotificationPosted
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
W/ResourcesManager( 1461): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
D/LgeQuickCoverOverlayWindow( 1411): [na,tive noti] inex =  2
W/ResourcesManager( 1461): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
D/LgeQuickCoverNotificationData( 1411): isNotificationForCurrentUser : true
I/ActivityManager( 1030): Killing 5387:com.google.android.gms.wearable/u0a5 (adj 15): empty #17
I/DrmSntpClient( 6750): Synched
,D/DrmService( 6750): Completed !! request = 2
D/DrmService( 6750): Request count = 0
D/libc-netbsd(  314): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  314): res_queryN name = www.googleapis.com, class = 1, type = 1
I/art     ( 6770): Almond Protected OAT
D/libc-netbsd(  314): res_queryN name = www.googleapis.com succeed
,W/libprocessgroup( 1030): failed to open /acct/uid_10005/pid_5387/cgroup.procs: No such file or directory
E/LgeQuickCoverOverlayWindow( 1411): updateNotificationData: count=3
,V/DrmService( 6750): Service onDestroy
I/ActivityManager( 1030): Killing 6045:com.google.android.talk/u0a72 (adj 15): empty #17
D/QuickStatusbarLayout( 1411): Notification difference=198
D/QuickStatusbarLayout( 1411): child = android.widget.LinearLayout{5df8279 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
D/WeatherApplication( 6770): removeAccount
,D/WeatherApplication( 6770): Account.length = 0
E/WeatherApplication( 6770): OPERATOR:OPEN
W/Uploader( 2138):  no longer exists, so no auth token.
D/WeatherAncestor( 6770): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 17:15:43
,D/Weather.Utils( 6770): 2 : the weather widgets(using time tick) are gone.
D/Weather.Utils( 6770): 2 : All the weather widget is gone.
D/UpdateThreadPoolManager( 6770): 2 : This is isUpdating : false
D/WeatherAncestor( 6770): connectivity changed - connection : true
D/WeatherService( 6770): 2 : isServiceAlived():false forecastCache:null
,D/ForecastDataCache( 6770): 2 : lastUpdatedTime: 1430558561343
D/ForecastDataCache( 6770): 2 : currentPackageVersion: 4.40.4
D/ForecastDataCache( 6770): 2 : Cache is not up-to-date, count: 0
D/Weather_cast( 6770): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherAncestor( 6770): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 17:15:43
,I/ActivityManager( 1030): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=6791 uid=10093 gids={50093, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager( 1030): Killing 2204:com.lge.music/u0a34 (adj 15): empty #17
,V/AudioFlinger(  318): 2204 died, releasing its sessions
V/AudioFlinger(  318):  pid 1867 @ 0
,V/AudioFlinger(  318):  pid 3258 @ 1
,V/AudioFlinger(  318):  pid 3258 @ 2
W/ApiaryClient( 6614): Error response from books API: {
W/ApiaryClient( 6614):  "error": {
W/ApiaryClient( 6614):   "errors": [
W/ApiaryClient( 6614):    {
W/ApiaryClient( 6614):     "domain": "global",
W/ApiaryClient( 6614):     "reason": "required",
W/ApiaryClient( 6614):     "message": "Login Required",
W/ApiaryClient( 6614):     "locationType": "header",
W/ApiaryClient( 6614):     "location": "Authorization"
W/ApiaryClient( 6614):    }
W/ApiaryClient( 6614):   ],
W/ApiaryClient( 6614):   "code": 401,
W/ApiaryClient( 6614):   "message": "Login Required"
W/ApiaryClient( 6614):  }
W/ApiaryClient( 6614): }
,W/ApiaryClient( 6614): errCount = 1: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6614): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=3733934479199700604&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6614): Headers:
W/ApiaryClient( 6614): accept-encoding: [gzip]
W/ApiaryClient( 6614): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6614): gdata-version: 2
,W/libprocessgroup( 1030): failed to open /acct/uid_10072/pid_6045/cgroup.procs: No such file or directory
,W/libprocessgroup( 1030): failed to open /acct/uid_10034/pid_2204/cgroup.procs: No such file or directory
,W/Uploader( 2138): No account for auth token provided
,I/art     ( 1030): Explicit concurrent mark sweep GC freed 28652(1275KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 44MB/66MB, paused 1.749ms total 138.740ms
,E/VoldCmdListener(  278): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  278): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6791): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
E/VoldCmdListener(  278): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  278): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6791): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
E/VoldCmdListener(  278): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  278): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6791): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
,E/VoldCmdListener(  278): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  278): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6791): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
I/ActivityManager( 1030): Start proc com.google.android.apps.plus for service com.google.android.apps.plus/.service.EsSyncAdapterService: pid=6816 uid=10097 gids={50097, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,W/ResourcesManager( 6816): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/WebViewFactory( 6791): Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,I/LibraryLoader( 6791): Loading: webviewchromium
,I/LibraryLoader( 6791): Time to load native libraries: 4 ms (timestamps 9728-9732)
I/LibraryLoader( 6791): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 6791): Binding Chromium to main looper Looper (main, tid 1) {7acc4e0}
I/LibraryLoader( 6791): Expected native library version number "",actual native library version number ""
I/chromium( 6791): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 6791): Initializing chromium process, renderers=0
,W/art     ( 6791): Attempt to remove local handle scope entry from IRT, ignoring
V/AudioPolicyService(  318): registerClient() client 0xb57bc140, uid 10093
,W/AudioManagerAndroid( 6791): Requires BLUETOOTH permission
,W/chromium( 6791): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
I/chromium( 6791): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=38 off=46780 len=2953
I/chromium( 6791): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:39 off:229536 len:643667
I/Adreno-EGL( 6791): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 6791): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 6791): Build Date: 12/12/14 금
I/Adreno-EGL( 6791): Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
I/Adreno-EGL( 6791): Remote Branch: 
I/Adreno-EGL( 6791): Local Patches: 
I/Adreno-EGL( 6791): Reconstruct Branch: 
,I/NSApplication( 6791): Starting up...
,I/ActivityManager( 1030): Killing 4912:com.android.vending/u0a44 (adj 15): empty #17
,I/GLSActivity( 2138): [ac] getting account id
I/jxcore-log( 6138): Test app app.js loaded
I/jxcore-log( 6138): 
,W/libprocessgroup( 1030): failed to open /acct/uid_10044/pid_4912/cgroup.procs: No such file or directory
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6138): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6138): 	Automate Bluetooth MAC address resolution: true, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6138): 	Provide Bluetooth MAC address timeout in milliseconds: 40000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6138): 	Bluetooth MAC address: 58:3F:54:73:64:C0, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6138): 	Discovery mode: WIFI, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6138): 	Peer expiration time in milliseconds: 60000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6138): 	Advertise mode: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6138): 	Advertise TX power level: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6138): 	Scan mode: 1
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6138): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@29e20144 added. We now have 1 listener(s),
I/chromium( 6138): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
I/jxcore-log( 6138): BLE advertisement is not supported: Bluetooth LE advertising is not supported
I/jxcore-log( 6138): 
I/GLSUser ( 2138): [t] Fetched account id for thalitester@gmail.com : 105256135866144380227
,D/libc-netbsd(  314): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  314): res_queryN name = mtalk.google.com, class = 1, type = 1
,I/iu.SyncManager( 2356): SYNC; picasa accounts
,D/NetworkLogImpl( 2356): Loaded NetworkSpeedPredictor
,I/iu.Environment( 2356): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
V/GLSActivity( 2138): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/iu.UploadsManager( 2356): num queued entries: 0
I/iu.UploadsManager( 2356): num updated entries: 0
I/iu.SyncManager( 2356): NEXT; no task
D/ChimeraCfgMgr( 2356): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/ChimeraCfgMgr( 2356): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/PostponalbeReceiver( 6395): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.intent.action.TIME_SET'.
,I/GLSUser ( 2138): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.syncadapters.contacts, service: cp
I/GLSUser ( 2138): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> cp without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2138): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2138): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
D/libc-netbsd(  314): res_queryN name = mtalk.google.com succeed
,I/ActivityManager( 1030): Start proc com.lge.clock for broadcast com.lge.clock/.alarmclock.ALBootInit: pid=6889 uid=10010 gids={50010, 9997, 3003, 1028, 4002} abi=armeabi-v7a
,V/GLSActivity( 2138): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/GLSUser ( 2138): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: ac2dm
,I/GLSUser ( 2138): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> ac2dm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2138): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2138): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2138): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     ( 2138): Explicit concurrent mark sweep GC freed 24441(1319KB) AllocSpace objects, 5(487KB) LOS objects, 50% free, 30MB/62MB, paused 8.806ms total 41.615ms
,V/NotificationService( 1030): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1030): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1030): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1030): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1030): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,W/GLSActivity( 2138): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2138): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2138): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2138): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2138): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2138): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2138): 	at android.os.Binder.execTransact(Binder.java:446)
V/NotificationService( 1030): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
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
V/NotificationService( 1030): pkg=com.google.android.gms canInterrupt=false intercept=true
D/LgeQuickCoverNotificationData( 1411): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1411): showNotificationWithSetupData: display=false
I/NotificationServiceEx( 1030): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1030): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1030): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverOverlayWindow( 1411): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1411): isNotificationForCurrentUser : true
,D/LgeQuickCoverOverlayWindow( 1411): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1411): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1411): [native noti] inex =  2
D/LgeQuickCoverNLService( 1411): onNotificationPosted
D/ContactsSyncAdapter( 2138): innerSync failed
D/ContactsSyncAdapter( 2138): com.google.wireless.gdata2.client.AuthenticationException: unable to get auth token android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
D/ContactsSyncAdapter( 2138): 	at com.google.android.syncadapters.contacts.AuthInfo.getAuthToken(AuthInfo.java:45)
D/ContactsSyncAdapter( 2138): 	at com.google.android.syncadapters.contacts.ContactsSyncAdapter.innerPerformSync(ContactsSyncAdapter.java:263)
D/ContactsSyncAdapter( 2138): 	at com.google.android.syncadapters.contacts.ContactsSyncAdapter.onPerformLoggedSync(ContactsSyncAdapter.java:168)
D/ContactsSyncAdapter( 2138): 	at com.google.android.common.LoggingThreadedSyncAdapter.onPerformSync(LoggingThreadedSyncAdapter.java:33)
D/ContactsSyncAdapter( 2138): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
D/ContactsSyncAdapter( 2138): Caused by: android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
D/ContactsSyncAdapter( 2138): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
D/ContactsSyncAdapter( 2138): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
D/ContactsSyncAdapter( 2138): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
D/ContactsSyncAdapter( 2138): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
D/ContactsSyncAdapter( 2138): 	at android.os.Binder.execTransact(Binder.java:446)
D/LgeQuickCoverNotificationData( 1411): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1411): updateNotificationData: count=3
W/Kids    ( 2356): [AccountUtils] Account not ready
W/Kids    ( 2356): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/Kids    ( 2356): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/Kids    ( 2356): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/Kids    ( 2356): 	at com.google.android.gms.auth.p.c(SourceFile:550)
W/Kids    ( 2356): 	at com.google.android.gms.auth.p.b(SourceFile:477)
W/Kids    ( 2356): 	at com.google.android.gms.kids.account.k.d(SourceFile:103)
W/Kids    ( 2356): 	at com.google.android.gms.kids.account.p.a(SourceFile:70)
W/Kids    ( 2356): 	at com.google.android.gms.kids.account.t.a(SourceFile:62)
W/Kids    ( 2356): 	at com.google.android.gms.chimera.f.run(SourceFile:179)
W/Kids    ( 2356): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Kids    ( 2356): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Kids    ( 2356): 	at java.lang.Thread.run(Thread.java:818)
,D/SyncManager( 1030): failed sync operation thalitester@gmail.com u0 (com.google), com.android.contacts, LOCAL, currentRunTime 26537, reason: 10019, SyncResult: stats [ numAuthExceptions: 1]
D/QuickStatusbarLayout( 1411): Notification difference=198
D/QuickStatusbarLayout( 1411): child = android.widget.LinearLayout{5df8279 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
D/SmartCoverUpdateMonitor( 1411): received broadcast com.lge.intent.action.NLDataPosted
D/SyncManager( 1030): not retrying sync operation because the error is a hard error: thalitester@gmail.com u0 (com.google), com.android.contacts, LOCAL, currentRunTime 162603, reason: 10019
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
D/ALBootInit( 6889): ====action==>android.intent.action.TIME_SET
D/LgeQuickCoverOverlayWindow( 1411): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1411): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1411): [native noti] inex =  2
D/ALBootInit( 6889): Alarm ALBootInit: TIME_SET
D/LgeQuickCoverNotificationData( 1411): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1411): updateNotificationData: count=3
D/Alarms  ( 6889): [setNextAlert] start
I/GLSUser ( 2138): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2138): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2138): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2138): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2138): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/Alarms  ( 6889): [setNextAlert] (1)
D/Alarms  ( 6889):  minTime  = 0
D/QuickStatusbarLayout( 1411): Notification difference=198
D/QuickStatusbarLayout( 1411): child = android.widget.LinearLayout{5df8279 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,D/Alarms  ( 6889):  -- OK multi -- 0
E/jeny.kim( 6889): [setNextAlert] setNextAlert  temp_Alarmlink + 
E/jeny.kim( 6889): [setNextAlert]setNextAlert temp_AlarmLinkText + 
V/NotificationService( 1030): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1030): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1030): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1030): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1030): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
W/GLSActivity( 2138): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2138): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2138): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2138): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2138): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2138): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2138): 	at android.os.Binder.execTransact(Binder.java:446)
I/CommonUtil( 6889): BUILD Country: EU
D/LgeQuickCoverNLService( 1411): onNotificationPosted
D/Alarms  ( 6889): broadcastToWidgetProvider : false
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
D/Alarms  ( 6889): Enter formatDayAndTime(final Context context, long timeInMiliSec)
D/LgeQuickCoverOverlayWindow( 1411): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1411): isNotificationForCurrentUser : true
E/BooksAccountManager( 6614): Authentication error
E/BooksAccountManager( 6614): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6614): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6614): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6614): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6614): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6614): 	at android.os.Binder.execTransact(Binder.java:446)
E/LgeQuickCoverOverlayWindow( 1411): updateNotificationData: count=3
E/HttpHelper( 6614): null auth token
V/SettingsProvider( 1030): call_put(system:next_alarm_formatted=) for 0 calling package = com.lge.clock
,I/DigitalAppWidgetProvider( 6889): onReceive: android.intent.action.TIME_SET
V/DigitalAppWidgetProvider( 6889): cancelAlarmOnQuarterHour android.app.ReceiverRestrictedContext@391cf1d6
V/DigitalAppWidgetProvider( 6889): startAlarmOnQuarterHour android.app.ReceiverRestrictedContext@391cf1d6
D/QuickStatusbarLayout( 1411): Notification difference=198
D/QuickStatusbarLayout( 1411): child = android.widget.LinearLayout{5df8279 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
D/QuickCoverProvider( 6889): onReceiver
,I/indal   ( 1411): SmartCoverWidgetContext createApplicationContext
I/indal   ( 1411): SmartCoverWidgetContext createApplicationContext
D/WeatherAncestor( 6770): 2 : onReceive, action: android.intent.action.TIME_SET, Time(hour:min:sec) 17:15:44
D/Weather.Utils( 6770): 2 : the weather widgets(using time tick) are gone.
D/Weather.Utils( 6770): 2 : All the weather widget is gone.
D/UpdateThreadPoolManager( 6770): 2 : This is isUpdating : false
D/WeatherService( 6770): 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@4865c57
,D/ForecastDataCache( 6770): 2 : lastUpdatedTime: 1430558561343
D/ForecastDataCache( 6770): 2 : currentPackageVersion: 4.40.4
D/ForecastDataCache( 6770): 2 : Cache is up-to-date, count: 0
D/Weather_cast( 6770): 2 : set auto-update time : 2/2 20:15
D/WeatherAncestor( 6770): 2 : onReceive has processed, action: android.intent.action.TIME_SET, Time(hour:min:sec) 17:15:44
,I/ActivityManager( 1030): Start proc com.qualcomm.timeservice for broadcast com.qualcomm.timeservice/.TimeServiceBroadcastReceiver: pid=6913 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi
,I/ActivityManager( 1030): Killing 5970:com.lge.bnr/1000 (adj 15): empty #17
,W/libprocessgroup( 1030): failed to open /acct/uid_1000/pid_5970/cgroup.procs: No such file or directory
,D/TimeService( 6913): Receivedandroid.intent.action.TIME_SET intent. Current Time is 1454429744661
D/        ( 6913): TimeServiceNative: User Time to be set is 1454429744661
D/QC-time-services( 6913): Lib:time_genoff_operation: pargs->base = 2
D/QC-time-services( 6913): Lib:time_genoff_operation: pargs->operation = 0
D/QC-time-services( 6913): Lib:time_genoff_operation: pargs->ts_val = 1454429744661
D/QC-time-services( 6913): Lib:time_genoff_operation: Send to server  passed!!
,D/QC-time-services(  356): Daemon: Connection accepted:time_genoff
D/QC-time-services(  356): Daemon:Received base = 2, unit = 1, operation = 0,value = 1454429744661
D/QC-time-services(  356): Daemon:genoff_opr: Base = 2, val = 1454429744661, operation = 0
D/QC-time-services(  356): Daemon:rtc_get: Time read from RTC -- MM/DD/YY HH:MM:SS5/12/70 9:27:51
D/QC-time-services(  356): Daemon:Value read from RTC seconds = 14030871000
D/QC-time-services(  356): Daemon:new time 1454429744661 
D/QC-time-services(  356): Daemon: delta 1440398873661 genoff 1440398873661 
D/QC-time-services(  356): Daemon:genoff_persistent_update: Writing genoff = 1440398873661 to memory
D/QC-time-services(  356): Daemon:Opening File: /data/time/ats_2
D/QC-time-services(  356): Daemon:time_persistent_memory_opr:Genoff write operation 
D/QC-time-services(  356): Updating the TOD offset
D/QC-time-services(  356): Daemon:genoff_persistent_update: Writing genoff = 1440398873661 to memory
,D/QC-time-services(  356): Daemon:Opening File: /data/time/ats_1
D/QC-time-services(  356): Daemon:time_persistent_memory_opr:Genoff write operation 
E/QC-time-services(  356): Daemon:Update to modem bit set
D/QC-time-services(  356): Daemon:genoff_send_modem: Sending data to MODEM !
D/QC-time-services(  356): Daemon: Base = 2, Value being sent to MODEM = 1124434073661
E/QC-time-services( 6913): Receive Passed == base = 2, unit = 1, operation = 0, result = 0
E/QC-time-services(  356): Daemon:tod_update_ind_cb: Got Update from modem msg_id 40
E/QC-time-services(  356): Daemon: Time-services: Waiting to acceptconnection
I/ActivityManager( 1030): Start proc com.android.calendar for broadcast com.android.calendar/.widget.CalendarAppWidgetProvider: pid=6931 uid=10013 gids={50013, 9997, 3003, 1028, 1015} abi=armeabi
W/ApiaryClient( 6614): Error response from books API: {
W/ApiaryClient( 6614):  "error": {
W/ApiaryClient( 6614):   "errors": [
W/ApiaryClient( 6614):    {
W/ApiaryClient( 6614):     "domain": "global",
W/ApiaryClient( 6614):     "reason": "required",
W/ApiaryClient( 6614):     "message": "Login Required",
W/ApiaryClient( 6614):     "locationType": "header",
W/ApiaryClient( 6614):     "location": "Authorization"
W/ApiaryClient( 6614):    }
W/ApiaryClient( 6614):   ],
W/ApiaryClient( 6614):   "code": 401,
W/ApiaryClient( 6614):   "message": "Login Required"
W/ApiaryClient( 6614):  }
W/ApiaryClient( 6614): }
,I/ActivityManager( 1030): Killing 6372:com.lge.settings.easy/1000 (adj 15): empty #17
W/ApiaryClient( 6614): errCount = 2: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6614): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=3733934479199700604&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6614): Headers:
W/ApiaryClient( 6614): accept-encoding: [gzip]
W/ApiaryClient( 6614): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6614): gdata-version: 2
W/libprocessgroup( 1030): failed to open /acct/uid_1000/pid_6372/cgroup.procs: No such file or directory
,W/ResourcesManager( 6931): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,D/CalendarApplication( 6931): CalendarApplication.onCreate()
,D/PreferenceKeysParser( 6931): [debug_displayParseInfos] preference keys.size() = 44
,D/PreferenceKeysParser( 6931): [debug_displayParseInfos] preference keys = {lg_preferences_tardis_1=com.android.calendar.adaptation.PreferenceKey$KeyData@270c2375, lg_preferences_hide_declined=com.android.calendar.adaptation.PreferenceKey$KeyData@3476ef0a, lg_preferences_default_reminder=com.android.calendar.adaptation.PreferenceKey$KeyData@3f35037b, lg_preferences_month_view_style=com.android.calendar.adaptation.PreferenceKey$KeyData@3cc42598, lg_preferences_alerts_ringtone=com.android.calendar.adaptation.PreferenceKey$KeyData@e8881f1, lg_preferences_device_tz=com.android.calendar.adaptation.PreferenceKey$KeyData@391cf1d6, lg_preferences_debug_datesearch=com.android.calendar.adaptation.PreferenceKey$KeyData@4865c57, lg_preferences_debug_country=com.android.calendar.adaptation.PreferenceKey$KeyData@1fa20344, lg_preferences_display_weather_information=com.android.calendar.adaptation.PreferenceKey$KeyData@1f924c2d, lg_preferences_alerts_vibrateWhen=com.android.calendar.adaptation.PreferenceKey$KeyData@1c4e5562, lg_preferences_debug_rtl=com.android.calendar.adaptation.PreferenceKey$KeyData@172a66f3, lg_preferences_alerts_type=com.android.calendar.adaptation.PreferenceKey$KeyData@1b5e0fb0, lg_preferrences_country_code=com.android.calendar.adaptation.PreferenceKey$KeyData@21f47e29, lg_preferences_weather_info=com.android.calendar.adaptation.PreferenceKey$KeyData@304065ae, lg_preference_holiday_calendar_ver=com.android.calendar.adaptation.PreferenceKey$KeyData@3cfa7f4f, lg_preferences_show_controls=com.android.calendar.adaptation.PreferenceKey$KeyData@f8c76dc, lg_preferences_user_select_noti_sound=com.android.calendar.adaptation.PreferenceKey$KeyData@352dd3e5, lg_preference_default_myphonebook=com.android.calendar.adaptation.PreferenceKey$KeyData@23312eba, lg_preferences_skip_setup=com.android.calendar.adaptation.PreferenceKey$KeyData@1609c16b, lg_preferred_startView=com.android.calendar.adaptation.PreferenceKey$KeyData@1ed824c8, lg_preferences_debug_operator=com.android.calendar.adaptation.PreferenceKey$KeyData@37ecc961, lg_preferences_exclude_sticker_list=com.android.calendar.adaptation.PreferenceKey$KeyData@17337c86, lg_preferences_writable_calendars_count=com.android.calendar.adaptation.PreferenceKey$KeyData@26810947, lg_preferred_detailedView=com.android.calendar.adaptation.PreferenceKey$KeyData@29aec574, lg_preferences_debug_floating=com.android.calendar.adaptation.PreferenceKey$KeyData@2b4b9a9d, lg_preferences_home_tz=com.android.calendar.adaptation.PreferenceKey$KeyData@2abadb12, lg_preferences_home_tz_enabled=com.android.calendar.adaptation.PreferenceKey$KeyData@223af2e3, lg_preference_received_provider_reminder_broadcast=com.android.calendar.adaptation.PreferenceKey$KeyData@7acc4e0, lg_preferences_default_cell_height=com.android.calendar.adaptation.PreferenceKey$KeyData@dcc4399, lg_preferences_notification_type=com.android.calendar.adaptation.PreferenceKey$KeyData@3de7965e, lg_preferences_show_week_num=com.android.calendar.adaptation.PreferenceKey$KeyData@161fda3f, lg_preferences_dont_show_again_no_online_account=com.android.calendar.adaptation.PreferenceKey$KeyData@2bc94f0c, lg_preferences_alerts_popup=com.android.calendar.adaptation.PreferenceKey$KeyData@2a148055, lg_preferences_week_start_day=com.android.calendar.adaptation.PreferenceKey$KeyData@92ba6a, lg_preferences_app_version=com.android.calendar.adaptation.PreferenceKey$KeyData@b41db5b, lg_preferences_alerts=com.android.calendar.adaptation.PreferenceKey$KeyData@1f424ff8, lg_preferences_select_aux_calendar=com.android.calendar.adaptation.PreferenceKey$KeyData@1569ccd1, lg_preferences_widget_info_calendars=com.android.calendar.adaptation.PreferenceKey$KeyData@151a1336, lg_preferences_alerts_default_ringtone=com.android.calendar.adaptation.PreferenceKey$KeyData@3fb8d237, lg_preference_defaultCalendar=com.android.calendar.adaptation.PreferenceKey$KeyData@3f4873a4, lg_preferences_alerts_vibratetype=com.android.calendar.adaptation.PreferenceKey$KeyData@19ed650d, lg_preferences_recent_timezones=com.android.calendar.adaptation.PreferenceKey$KeyData@13ec2c
,D/GeneralPreferenceUtils( 6931): [migratePrefrenceKeys] Exit: Version(44001600) >= 42001300
D/Config  ( 6931): [init]
I/Config  ( 6931): LGCalendar ver.4.40.16
I/Config  ( 6931): start check model
I/Config  ( 6931): start check native_ca
I/Config  ( 6931): Config Operator=OPEN, Country=EU
D/Config  ( 6931): [setDefaultValuesToPref]
D/Config  ( 6931): [parseProfiles]
,D/ProfilesParser( 6931): [debug_displayParseInfos] profile.country = null
,D/ProfilesParser( 6931): [debug_displayParseInfos] profile.operator = null
D/Config  ( 6931): [updateProfiletoCountryInfo]
D/GeneralPreference( 6931): [checkAndMigrateOldPreference]
E/AgendaWidgetManager( 6931): [updateWidgets] 
,I/InitNotificationRingtoneService( 6931): Start InitializeAlertRingtoneService.onHandleIntent
,I/AlertUtils( 6931): [setFormatNotificationSound] current noti URI = content://media/internal/audio/media/41
,I/AlertUtils( 6931): [getCalendarNotiSoundURIFromCursor] getCount()= 21
,I/AlertUtils( 6931): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Arpeggio.ogg
I/AlertUtils( 6931): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Country_Blues.ogg
I/AlertUtils( 6931): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Crystal.ogg
,I/AlertUtils( 6931): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Dewdrop.ogg
,W/HolidayIntentService( 6931): onHandleIntent
,D/MonthWidgetProvider( 6931): [onReceive]
D/CalendarWidgetProvider( 6931): [onReceive]
D/CalendarWidgetProvider( 6931): [CalendarWidgetProvider] got the intent: Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.android.calendar/.widget.MonthWidgetProvider }
D/CalendarTypeController( 6931): [onUpdateAndInitCalendarTime]
D/WeekWidgetProvider( 6931): [onReceive]
D/CalendarWidgetProvider( 6931): [onReceive]
D/CalendarWidgetProvider( 6931): [CalendarWidgetProvider] got the intent: Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.android.calendar/.widget.WeekWidgetProvider }
D/HolidayDataLoader( 6931): readJsonAsset : holiday.json
D/CalendarTypeController( 6931): [onUpdateAndInitCalendarTime]
I/DigitalAppWidgetProvider( 6889): onReceive: android.intent.action.ALARM_CHANGED
,D/WeatherAncestor( 6770): 2 : onReceive, action: com.lge.sizechangable.weather.action.setweathercast, Time(hour:min:sec) 17:15:45
D/Weather.Utils( 6770): 2 : the weather widgets(using time tick) are gone.
D/Weather.Utils( 6770): 2 : All the weather widget is gone.
D/UpdateThreadPoolManager( 6770): 2 : This is isUpdating : false
I/art     ( 1030): Explicit concurrent mark sweep GC freed 23283(1037KB) AllocSpace objects, 4(448KB) LOS objects, 33% free, 44MB/66MB, paused 2.759ms total 177.297ms
,D/Weather_cast( 6770): 2 : Update is Canceled by com.lge.sizechangable.weather.action.alarm
D/WeatherAncestor( 6770): 2 : onReceive has processed, action: com.lge.sizechangable.weather.action.setweathercast, Time(hour:min:sec) 17:15:45
I/AlertUtils( 6931): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Ding_Dong.ogg
I/AlertUtils( 6931): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Echo.ogg
I/AlertUtils( 6931): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Email.ogg
I/AlertUtils( 6931): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Game_Over.ogg
,I/AlertUtils( 6931): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Gayageum.ogg
I/AlertUtils( 6931): [getMediaFilepathFromContentUri] filepath = /system/media/audio/alarms/Afternoon_Walk.ogg
I/AlertUtils( 6931): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Harmonics.ogg
,E/HolidayIntentService( 6931): onHandleIntent:holiday data empty
I/AlertUtils( 6931): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Idea.ogg
I/AlertUtils( 6931): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/News.ogg
I/AlertUtils( 6931): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Pebble.ogg
,I/AlertUtils( 6931): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Schedule.ogg
I/AlertUtils( 6931): [getCalendarNotiSoundURIFromCursor] filePath = /system/media/audio/notifications/Schedule.ogg, new URI = content://media/internal/audio/media/41
I/AlertUtils( 6931): set default noti to content://media/internal/audio/media/41
I/InitNotificationRingtoneService( 6931): End InitializeAlertRingtoneService.onHandleIntent
,I/ActivityManager( 1030): Killing 6274:com.lge.lifetracker/u0a37 (adj 15): empty #17
,I/art     ( 2356): Explicit concurrent mark sweep GC freed 18071(1289KB) AllocSpace objects, 19(304KB) LOS objects, 49% free, 32MB/64MB, paused 4.218ms total 87.286ms
W/libprocessgroup( 1030): failed to open /acct/uid_10037/pid_6274/cgroup.procs: No such file or directory
,E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-53 f=2412 sc=60 link=72 tx=4.6, 0.0, 0.0  rx=3.8 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1564167990] gl rssi=-53 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-53 f=2412 sc=60 link=72 tx=4.6, 0.0, 0.0  rx=3.8 bcn=0 [on:0 tx:0 rx:0 period:2] from screen [on:0 period:-1564167988] gl rssi=-53 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
D/StatusBar.NetworkController( 1461): refreshViews: Data not connected!! Set no data type icon / Roaming
D/GCM     ( 2138): Connected
,D/GCM     ( 2138): Message class com.google.f.a.a.p
,I/ActivityManager( 1030): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.realtimechat.RequestWriter$NetworkStateReceiver: pid=6968 uid=10072 gids={50072, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,I/art     (  347): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 446us total 21.743ms
,I/art     (  347): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 374us total 18.549ms
,I/art     (  347): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 360us total 17.120ms
,W/ResourcesManager( 6968): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,D/LgDataFeature( 6968): LgDataFeature() Constructor: none
D/LgDataFeature( 6968): LgDataFeature() Constructor Done, null
,V/GLSActivity( 2138): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2138): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2138): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2138): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2138): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2138): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/Babel   ( 6968): MmsConfig: mnc/mcc: 0/0
I/Babel   ( 6968): MmsConfig.loadMmsSettings
,I/Babel   ( 6968): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D855 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D855-M3-D1.xml
I/Babel   ( 6968): MmsConfig.loadFromDatabase
,V/NotificationService( 1030): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
V/NotificationService( 1030): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1030): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1030): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1030): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,W/GLSActivity( 2138): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2138): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2138): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2138): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2138): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2138): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2138): 	at android.os.Binder.execTransact(Binder.java:446)
E/BooksAccountManager( 6614): Authentication error
E/BooksAccountManager( 6614): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6614): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6614): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6614): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6614): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6614): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6614): null auth token
D/LgeQuickCoverNLService( 1411): onNotificationPosted
D/SmartCoverUpdateMonitor( 1411): received broadcast com.lge.intent.action.NLDataPosted
,E/SmartCoverUpdateMonitor( 1411): MSG_NOTIFICATION_POSTED
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
E/Babel   ( 6968): canonicalizeMccMnc: invalid mccmnc 
I/Babel   ( 6968): MmsConfig.loadFromResources
E/Babel   ( 6968): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel   ( 6968): MmsConfig.loadMmsSettings: mUserAgent=LG-D855 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D855-M3-D1.xml
D/QuickStatusbarLayout( 1411): Notification difference=198
D/QuickStatusbarLayout( 1411): child = android.widget.LinearLayout{5df8279 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,W/Settings( 6968): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/AudioCapabilities( 6968): Unsupported mime audio/evrc
W/AudioCapabilities( 6968): Unsupported mime audio/qcelp
W/VideoCapabilities( 6968): Unrecognized profile 2130706433 for video/avc
,W/AudioCapabilities( 6968): Unsupported mime audio/amr-wb-plus
,W/AudioCapabilities( 6968): Unsupported mime audio/qcelp
W/AudioCapabilities( 6968): Unsupported mime audio/evrc
W/VideoCapabilities( 6968): Unsupported mime video/x-ms-wmv
W/ResourcesManager( 6968): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6968): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
W/VideoCapabilities( 6968): Unsupported mime video/divx
,W/VideoCapabilities( 6968): Unsupported mime video/divx311
W/VideoCapabilities( 6968): Unsupported mime video/divx4
W/VideoCapabilities( 6968): Unsupported mime video/mp4v-esdp
I/VideoCapabilities( 6968): Unsupported profile 4 for video/mp4v-es
,W/AudioCapabilities( 6968): Unsupported mime audio/eac3
W/AudioCapabilities( 6968): Unsupported mime audio/ac3
W/AudioCapabilities( 6968): Unsupported mime audio/g726
W/AudioCapabilities( 6968): Unsupported mime audio/wma-voice
W/AudioCapabilities( 6968): Unsupported mime audio/x-ms-wma
W/AudioCapabilities( 6968): Unsupported mime audio/adpcm
W/VideoCapabilities( 6968): Unsupported mime video/theora
W/VideoCapabilities( 6968): Unsupported mime video/mjpg
,V/JNIHelp ( 6968): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,W/ApiaryClient( 6614): Error response from books API: {
W/ApiaryClient( 6614):  "error": {
W/ApiaryClient( 6614):   "errors": [
W/ApiaryClient( 6614):    {
W/ApiaryClient( 6614):     "domain": "global",
W/ApiaryClient( 6614):     "reason": "required",
W/ApiaryClient( 6614):     "message": "Login Required",
W/ApiaryClient( 6614):     "locationType": "header",
W/ApiaryClient( 6614):     "location": "Authorization"
W/ApiaryClient( 6614):    }
W/ApiaryClient( 6614):   ],
W/ApiaryClient( 6614):   "code": 401,
W/ApiaryClient( 6614):   "message": "Login Required"
W/ApiaryClient( 6614):  }
W/ApiaryClient( 6614): }
W/ApiaryClient( 6614): errCount = 3: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6614): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=3733934479199700604&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6614): Headers:
W/ApiaryClient( 6614): accept-encoding: [gzip]
W/ApiaryClient( 6614): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6614): gdata-version: 2
,W/System  ( 6968): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/system/framework/com.google.android.media.effects.jar", zip file "/system/app/Hangouts/Hangouts.apk"],nativeLibraryDirectories=[/system/app/Hangouts/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,I/ProviderInstaller( 6968): Installed default security provider GmsCore_OpenSSL
I/GLSUser ( 2138): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.talk, service: oauth2:https://www.googleapis.com/auth/chat https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/hangouts https://www.googleapis.com/auth/identity.plus.page.impersonation https://www.googleapis.com/auth/chat.native
I/GLSUser ( 2138): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/chat https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/hangouts https://www.googleapis.com/auth/identity.plus.page.impersonation https://www.googleapis.com/auth/chat.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2138): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2138): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2138): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
E/Babel   ( 6968): UserRecoverableAuthException.
E/Babel   ( 6968): cfq: BadAuthentication
E/Babel   ( 6968): 	at cfn.a(Unknown Source)
E/Babel   ( 6968): 	at f.a(PG:191)
E/Babel   ( 6968): 	at ava.a(PG:88)
E/Babel   ( 6968): 	at ava.a(PG:128)
E/Babel   ( 6968): 	at bjs.a(PG:255)
E/Babel   ( 6968): 	at bep.a(PG:602)
E/Babel   ( 6968): 	at bep.a(PG:469)
E/Babel   ( 6968): 	at bpo.run(PG:1141)
E/Babel   ( 6968): Error getting auth token
,E/Babel   ( 6968): bxl
E/Babel   ( 6968): 	at f.a(PG:201)
E/Babel   ( 6968): 	at ava.a(PG:88)
E/Babel   ( 6968): 	at ava.a(PG:128)
E/Babel   ( 6968): 	at bjs.a(PG:255)
E/Babel   ( 6968): 	at bep.a(PG:602)
E/Babel   ( 6968): 	at bep.a(PG:469)
E/Babel   ( 6968): 	at bpo.run(PG:1141)
I/Babel_RequestWriter( 6968): error sending REQ[fc:8; creat:1454423865056; type:bev-957811127]; took 175 ms (error code == 100)
E/Babel   ( 6968): Account registration failedRedacted-21
E/Babel   ( 6968): bph: null -- null
E/Babel   ( 6968): 	at ava.a(PG:120)
E/Babel   ( 6968): 	at ava.a(PG:128)
E/Babel   ( 6968): 	at bjs.a(PG:255)
E/Babel   ( 6968): 	at bep.a(PG:602)
E/Babel   ( 6968): 	at bep.a(PG:469)
E/Babel   ( 6968): 	at bpo.run(PG:1141)
I/Babel   ( 6968): Account setup failed with error state:106 account:Redacted-21
I/Babel   ( 6968): Account sign in complete with state 106account: Redacted-21
I/art     ( 6968): Note: end time exceeds epoch: 
,I/GLSUser ( 2138): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.talk, service: oauth2:https://www.googleapis.com/auth/chat https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/hangouts https://www.googleapis.com/auth/identity.plus.page.impersonation https://www.googleapis.com/auth/chat.native
,I/GLSUser ( 2138): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/chat https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/hangouts https://www.googleapis.com/auth/identity.plus.page.impersonation https://www.googleapis.com/auth/chat.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2138): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2138): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2138): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/ResourcesManager( 2138): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,V/NotificationService( 1030): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1030): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1030): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1030): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1030): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
E/Babel   ( 6968): Unexpected exception while authenticating.
E/Babel   ( 6968): cfr: User intervention required. Notification has been pushed.
E/Babel   ( 6968): 	at cfn.b(Unknown Source)
E/Babel   ( 6968): 	at cfn.a(Unknown Source)
E/Babel   ( 6968): 	at f.a(PG:188)
E/Babel   ( 6968): 	at ava.b(PG:143)
E/Babel   ( 6968): 	at bnr.run(PG:5415)
E/Babel   ( 6968): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/Babel   ( 6968): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/Babel   ( 6968): 	at java.lang.Thread.run(Thread.java:818)
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
D/QuickStatusbarLayout( 1411): Notification difference=198
D/QuickStatusbarLayout( 1411): child = android.widget.LinearLayout{5df8279 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,I/ActivityManager( 1030): Start proc com.android.vending for service com.android.vending/com.google.android.finsky.services.ContentSyncService: pid=7019 uid=10044 gids={50044, 9997, 3003, 1028, 1015} abi=armeabi-v7a
V/AlarmManager( 1030): RTC_WAKEUP set : Alarm{1253f09b type 0 when 1454429747006 com.android.vending} when 1454429747006
,E/BooksSync( 6614): Soft error: 
E/BooksSync( 6614): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 6614): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=3733934479199700604&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 6614): Headers:
E/BooksSync( 6614): accept-encoding: [gzip]
E/BooksSync( 6614): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 6614): gdata-version: 2
E/BooksSync( 6614): 
E/BooksSync( 6614): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 6614): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 6614): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 6614): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 6614): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 6614): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 6614): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 6614): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 6614): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 6614): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 6614): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 6614): {
E/BooksSync( 6614):  "error": {
E/BooksSync( 6614):   "errors": [
E/BooksSync( 6614):    {
E/BooksSync( 6614):     "domain": "global",
E/BooksSync( 6614):     "reason": "required",
E/BooksSync( 6614):     "message": "Login Required",
E/BooksSync( 6614):     "locationType": "header",
E/BooksSync( 6614):     "location": "Authorization"
E/BooksSync( 6614):    }
E/BooksSync( 6614):   ],
E/BooksSync( 6614):   "code": 401,
E/BooksSync( 6614):   "message": "Login Required"
E/BooksSync( 6614):  }
E/BooksSync( 6614): }
E/BooksSync( 6614): 
E/BooksSync( 6614): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 6614): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 6614): 	... 8 more
,E/BooksSync( 6614): Sync error
E/BooksSync( 6614): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 6614): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=3733934479199700604&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 6614): Headers:
E/BooksSync( 6614): accept-encoding: [gzip]
E/BooksSync( 6614): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 6614): gdata-version: 2
E/BooksSync( 6614): 
E/BooksSync( 6614): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 6614): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 6614): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 6614): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 6614): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 6614): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 6614): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 6614): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 6614): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 6614): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 6614): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 6614): {
E/BooksSync( 6614):  "error": {
E/BooksSync( 6614):   "errors": [
E/BooksSync( 6614):    {
E/BooksSync( 6614):     "domain": "global",
E/BooksSync( 6614):     "reason": "required",
E/BooksSync( 6614):     "message": "Login Required",
E/BooksSync( 6614):     "locationType": "header",
E/BooksSync( 6614):     "location": "Authorization"
E/BooksSync( 6614):    }
E/BooksSync( 6614):   ],
E/BooksSync( 6614):   "code": 401,
E/BooksSync( 6614):   "message": "Login Required"
E/BooksSync( 6614):  }
E/BooksSync( 6614): }
E/BooksSync( 6614): 
E/BooksSync( 6614): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 6614): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 6614): 	... 8 more
,I/BooksSync( 6614): Finished books sync
,I/GAV2    ( 6614): Thread[GAThread,5,main]: No campaign data found.
I/ActivityManager( 1030): Killing 6320:com.lge.sync/1000 (adj 15): empty #17
,D/SyncManager( 1030): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 26494, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,W/libprocessgroup( 1030): failed to open /acct/uid_1000/pid_6320/cgroup.procs: No such file or directory
,D/Finsky  ( 7019): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,V/GLSActivity( 2138): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/GLSUser ( 2138): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.syncadapters.contacts, service: cp
I/GLSUser ( 2138): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> cp without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 2138): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2138): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2138): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1030): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1030): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1030): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1030): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/LgDataFeature( 7019): LgDataFeature() Constructor: none
D/LgDataFeature( 7019): LgDataFeature() Constructor Done, null
D/NotificationServiceEx( 1030): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
W/GLSActivity( 2138): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2138): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2138): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2138): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2138): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2138): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2138): 	at android.os.Binder.execTransact(Binder.java:446)
,D/ContactsSyncAdapter( 2138): innerSync failed
D/ContactsSyncAdapter( 2138): com.google.wireless.gdata2.client.AuthenticationException: unable to get auth token android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
D/ContactsSyncAdapter( 2138): 	at com.google.android.syncadapters.contacts.AuthInfo.getAuthToken(AuthInfo.java:45)
D/ContactsSyncAdapter( 2138): 	at com.google.android.syncadapters.contacts.ContactsSyncAdapter.innerPerformSync(ContactsSyncAdapter.java:263)
D/ContactsSyncAdapter( 2138): 	at com.google.android.syncadapters.contacts.ContactsSyncAdapter.onPerformLoggedSync(ContactsSyncAdapter.java:168)
D/ContactsSyncAdapter( 2138): 	at com.google.android.common.LoggingThreadedSyncAdapter.onPerformSync(LoggingThreadedSyncAdapter.java:33)
D/ContactsSyncAdapter( 2138): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
D/ContactsSyncAdapter( 2138): Caused by: android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
D/ContactsSyncAdapter( 2138): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
D/ContactsSyncAdapter( 2138): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
D/ContactsSyncAdapter( 2138): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
D/ContactsSyncAdapter( 2138): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
D/ContactsSyncAdapter( 2138): 	at android.os.Binder.execTransact(Binder.java:446)
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
,D/LgeQuickCoverOverlayWindow( 1411): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1411): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1411): updateNotificationData: count=3
D/SyncManager( 1030): failed sync operation thalitester@gmail.com u0 (com.google), com.android.contacts, LOCAL, currentRunTime 162603, reason: 10019, SyncResult: stats [ numAuthExceptions: 1]
D/QuickStatusbarLayout( 1411): Notification difference=198
D/QuickStatusbarLayout( 1411): child = android.widget.LinearLayout{5df8279 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,D/Finsky  ( 7019): [1] DailyHygiene.goMakeHygieneIfDirty: Dirty, need more hygiene.
,I/ActivityManager( 1030): Start proc com.google.android.gms:car for service com.google.android.gms/.car.CarService: pid=7075 uid=10005 gids={50005, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
,W/Settings( 7019): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 7019): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,V/DownloadManager( 3301): starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3301): created cursor android.database.sqlite.SQLiteCursor@8984509 on behalf of 7019
,W/ResourcesManager( 7075): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 7075): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,D/Finsky  ( 7019): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,D/Finsky  ( 7019): [1] 2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 7019): [1] 2.run: Finished loading 1 libraries.
,D/Finsky  ( 7019): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,I/MultiDex( 7075): VM with version 2.1.0 has multidex support
I/MultiDex( 7075): install
I/MultiDex( 7075): VM has multidex support, MultiDex support library is disabled.
V/JNIHelp ( 7075): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,V/SIM_STK ( 1030): Menu title from STK is T-Mobile
,W/ActivityThread( 7075): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 7075): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@28ad4a72: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 7075): Installed default security provider GmsCore_OpenSSL
,D/GCM     ( 2138): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,D/AuthorizationBluetoothService( 2138): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
V/GmsCoreStatsServiceLauncher( 2356): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
I/ActivityManager( 1030): Start proc com.google.android.gms.wearable for service com.google.android.gms/.wearable.service.WearableService: pid=7101 uid=10005 gids={50005, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
,D/LocationInitializer( 2356): Restart initialization of location
,W/ResourcesManager( 7101): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 7101): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/MultiDex( 7101): VM with version 2.1.0 has multidex support
I/MultiDex( 7101): install
I/MultiDex( 7101): VM has multidex support, MultiDex support library is disabled.
V/JNIHelp ( 7101): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,V/GLSActivity( 2138): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/GLSUser ( 2138): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 2138): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2138): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2138): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2138): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/Finsky  ( 7019): [1] GearheadStateMonitor.onReady: sIsProjecting:false
W/ActivityThread( 7101): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
D/Finsky  ( 7019): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
W/System  ( 7101): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@28ad4a72: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,I/ProviderInstaller( 7101): Installed default security provider GmsCore_OpenSSL
,D/Finsky  ( 7019): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 7019): [1] 5.onFinished: Scheduling replication attempt 2.
D/GCM     ( 2138): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
D/AuthorizationBluetoothService( 2138): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
V/GmsCoreStatsServiceLauncher( 2356): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,D/WearableService( 7101): callingUid 10005, callindPid: 7101
,I/ActivityManager( 1030): Killing 6247:com.android.settings/1000 (adj 15): empty #17
,D/WifiService( 1030): Client connection lost with reason: 4
,I/ActivityManager( 1030): Killing 5863:com.uei.lg.quicksetsdk.maxq616/1000 (adj 15): empty #18
,I/QRemote ( 5992): [RemoteControlManager.java:195:onServiceDisconnected()] oooooo start
W/System.err( 5992): android.os.DeadObjectException
W/System.err( 5992): 	at android.os.BinderProxy.transactNative(Native Method)
W/System.err( 5992): 	at android.os.BinderProxy.transact(Binder.java:496)
W/System.err( 5992): 	at com.uei.control.IControl.unregisterCallback(IControl.java:502)
,W/System.err( 5992): 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:199)
W/System.err( 5992): 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
W/System.err( 5992): 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
W/System.err( 5992): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 5992): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 5992): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 5992): 	at android.app.ActivityThread.main(ActivityThread.java:5274)
W/System.err( 5992): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 5992): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 5992): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
W/System.err( 5992): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
E/UEI.SmartControl( 5992): IControl.unregisterCallback error: android.os.DeadObjectException
W/System.err( 5992): android.os.DeadObjectException
W/System.err( 5992): 	at android.os.BinderProxy.transactNative(Native Method)
W/System.err( 5992): 	at android.os.BinderProxy.transact(Binder.java:496)
W/System.err( 5992): 	at com.uei.control.IControl.unregisterSetupReadyCallback(IControl.java:818)
W/System.err( 5992): 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:200)
W/System.err( 5992): 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
W/System.err( 5992): 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
W/System.err( 5992): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 5992): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 5992): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 5992): 	at android.app.ActivityThread.main(ActivityThread.java:5274)
W/System.err( 5992): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 5992): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 5992): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
W/System.err( 5992): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
E/UEI.SmartControl( 5992): IControl.unregisterSetupReadyCallback error: android.os.DeadObjectException
I/QRemote ( 5992): [RemoteControlManager.java:203:onServiceDisconnected()] oooooo Control unbind before rebinding.
E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=28.3, 0.0, 0.0  rx=22.4 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1564164979] gl rssi=-64 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=28.3, 0.0, 0.0  rx=22.4 bcn=0 [on:0 tx:0 rx:0 period:2] from screen [on:0 period:-1564164977] gl rssi=-64 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
W/libprocessgroup( 1030): failed to open /acct/uid_1000/pid_6247/cgroup.procs: No such file or directory
,W/libprocessgroup( 1030): failed to open /acct/uid_1000/pid_5863/cgroup.procs: No such file or directory
,W/ActivityManager( 1030): Scheduling restart of crashed service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service in 1000ms
D/QRemote ( 5992): [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]10
I/QRemote ( 5992): [RemoteControlManager.java:157:onBindIRService()] oooooo bind
,I/ActivityManager( 1030): Start proc com.uei.lg.quicksetsdk.maxq616 for service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service: pid=7131 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,D/LocationInitializer( 2356): Restart initialization of location
E/MDM     ( 1832): [86] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
D/QRemote ( 5992): [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
,E/MDM     ( 1832): [86] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,D/Finsky  ( 7019): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
V/AlarmManager( 1030): RTC_WAKEUP set : Alarm{38ac8f5e type 0 when 1454429748622 com.android.vending} when 1454429748622
,D/UEI.SmartControl( 7131): Quickset Services start...
,I/UEI.SmartControl( 7131): Manufacture = LGE
D/UEI.SmartControl( 7131): Id = LGNevo
D/UEI.SmartControl( 7131): File observer start...
E/UEI.SmartControl( 7131): IR Port is disabled: false
D/UEI.SmartControl( 7131): Starting file observer...
D/UEI.SmartControl( 7131): Extracting JNI libs...
D/UEI.SmartControl( 7131): --- this system supports 32-bit or 64-bit only
I/GAV4    ( 6791): Thread[GAThread,5,main]: No campaign data found.
,V/GLSActivity( 2138): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/UEI.SmartControl( 7131): --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
D/UEI.SmartControl( 7131): --- Checking lib: libqs_armeabi-v7a.zip
D/UEI.SmartControl( 7131): --- Extracting JNI libs: libqs_armeabi-v7a.zip
,I/UEI.SmartControl( 7131): --- Selecting new region: 6
,I/UEI.SmartControl( 7131): Model = LG-D855
D/UEI.SmartControl( 7131): QS Service created
I/UEI.SmartControl( 7131): Service initServices...
,D/UEI.SmartControl( 7131): QS start get config
I/art     ( 1030): Explicit concurrent mark sweep GC freed 28013(1276KB) AllocSpace objects, 6(480KB) LOS objects, 33% free, 44MB/66MB, paused 2.262ms total 132.879ms
I/GLSUser ( 2138): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 2138): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2138): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2138): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2138): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/Finsky  ( 7019): [1] 1.onErrorResponse: Unable to preload experiments: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,D/UEI.SmartControl( 7131): Loading JNI Libs...
V/GLSActivity( 2138): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/GLSUser ( 2138): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 2138): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2138): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2138): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2138): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     ( 2138): Explicit concurrent mark sweep GC freed 28437(1660KB) AllocSpace objects, 19(2MB) LOS objects, 51% free, 30MB/62MB, paused 1.592ms total 67.294ms
,V/GLSActivity( 2138): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/GLSUser ( 2138): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 2138): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2138): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2138): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2138): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/Finsky  ( 7019): [1] LibraryUpdateListener.onErrorResponse: Library replication failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,V/SIM_STK ( 1030): Menu title from STK is T-Mobile
,I/UEI.SmartControl( 7131): Supports setup maps: true
,D/UEI.SmartControl( 7131): QS start statue = true Error code = 0
I/UEI.SmartControl( 7131): QS version = v2.7.10.1_RC1
,I/UEI.SmartControl( 7131): QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
I/UEI.SmartControl( 7131): ### init IR Blaster...
D/serial_port( 7131): Configuring serial port
E/UEI.SmartControl( 7131): UEIBLaster setting for 616
I/UEI.SmartControl( 7131): Setting serial record hearder size = 2
I/UEI.SmartControl( 7131): configuring settings for MAXQ616
,I/UEI.SmartControl( 7131): Get version...
D/UEI.SmartControl( 7131): serial port data available: 21
,D/UEI.SmartControl( 7131): MAXQ616 A2-X4 software.
I/UEI.SmartControl( 7131): IR Blaster version: 256702256704300002
I/UEI.SmartControl( 7131): QS saving settings...
,D/UEI.SmartControl( 7131): IR Blaster version: 25672567
,D/UEI.SmartControl( 7131): serial port data available: 4
,W/ContextImpl( 7131): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
,E/UEI.SmartControl( 7131): Services init done
D/UEI.SmartControl( 7131): QS Service init finished
V/GLSActivity( 2138): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/UEI.SmartControl( 7131): Device manager: loading config....
D/UEI.SmartControl( 7131): QS Service version name: 2.1.91
D/UEI.SmartControl( 7131): ----------- loading internal config...
D/UEI.SmartControl( 7131): QS Service version code: 201091
D/UEI.SmartControl( 7131): Service requested: Control
,E/UEI.SmartControl( 7131): Loading SETTINGS...
D/UEI.SmartControl( 7131): Request IControl service: devices are loaded...
I/QRemote ( 5992): [RemoteControlManager.java:183:onServiceConnected()] oooooo start
I/UEI.SmartControl( 7131): ------ IControl API: 11
D/UEI.SmartControl( 7131): -- Open brand translation xml: brands_translations_ko
I/UEI.SmartControl( 7131): Registering callback...
I/UEI.SmartControl( 7131): ------ IControl API: 19
D/UEI.SmartControl( 7131): Internal service binding...
I/UEI.SmartControl( 7131): Registering Services Ready callback...
,I/GLSUser ( 2138): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 2138): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 2138): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2138): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2138): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/UEI.SmartControl( 7131): Notify AllClients services are ready: 0
I/QRemote ( 5992): [RemoteControlManager.java:660:QSSetupIsReady()] oooooo 140517:sdkIsReady callback... get functions. Result:0
D/QRemote ( 5992): [RemoteControlManager.java:388:handleMessage()] oooooo 140510:START_SESSION
D/QRemote ( 5992): [RemoteControlManager.java:394:handleMessage()] oooooo 140510:send retrieve msg
D/QRemote ( 5992): [RemoteControlManager.java:322:handleMessage()] oooooo 140510:handler call retrieveDevices
D/QRemote ( 5992): [RemoteControlManager.java:336:retrieveDevices()] oooooo retrieveDevices: start
I/UEI.SmartControl( 7131): ------ IControl API: 8
D/UEI.SmartControl( 7131): -----service ready thread exits
D/QRemote ( 5992): [RemoteControlManager.java:340:retrieveDevices()] oooooo retrieveDevices: 0
D/QRemote ( 5992): [RemoteControlManager.java:345:retrieveDevices()] oooooo retrieveDevices complete:true
,D/QRemote ( 5992): [RemoteControlManager.java:353:retrieveDevices()] oooooo retrieveDevices: notifyDataSetChanged()
D/QRemote ( 5992): [QRemoteApplication.java:145:onRemoteControlStateChanged()] oooooo onRemoteControlStateChanged called in QRemoteApp
,D/QRemote ( 5992): [QRemoteApplication.java:158:onRemoteControlStateChanged()] oooooo Widget count is [1]. send broadcast
D/QRemote ( 5992): [QRemoteApplication.java:160:onRemoteControlStateChanged()] oooooo Widget[0]:3
D/QRemote ( 5992): [QRemoteApplication.java:188:onRemoteControlStateChanged()] oooooo 140526:onRemoteControlStateChanged&sdkIsReady. stop Service
V/QRemote ( 5992): [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
D/QRemote ( 5992): [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
E/QRemote ( 5992): [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
D/QRemote ( 5992): [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
,W/Finsky  ( 7019): [1] 2.onErrorResponse: Update check failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,D/QRemote ( 5992): [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
D/QRemote ( 5992): [RemoteAppWidgetProvider.java:506:onUpdate()] oooooo 140510:RetrieveDevices complete. Start loading
D/QRemote ( 5992): [RemoteAppWidgetProvider.java:508:onUpdate()] oooooo 140510:appWidgetIds[0]:3 loading
D/QRemote ( 5992): [RemoteAppWidgetManager.java:41:startLoading()] oooooo 140518:widgetId[3] loading start at [1454429749426]
D/Finsky  ( 7019): [1] DailyHygiene.logDeviceFeaturesAndContinue: Logging device features
D/Finsky  ( 7019): [1] DailyHygiene.flushEventLogsAndContinue: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 7019): [1] DailyHygiene.reschedule: Scheduling new run in 27 minutes (failures=2)
D/QRemote ( 5992): [RemoteAppWidgetManager.java:239:doInBackground()] oooooo 140407:doinBack arr:0
V/QRemote ( 5992): [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.widget_ui_update
E/QRemote ( 5992): [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
D/QRemote ( 5992): [RemoteAppWidgetProvider.java:171:onReceive()] oooooo total:0
,D/QRemote ( 5992): [RemoteAppWidgetProvider.java:172:onReceive()] oooooo selected:0
,D/QRemote ( 5992): [RemoteAppWidgetProvider.java:173:onReceive()] oooooo arr:[]
D/QRemote ( 5992): [RemoteAppWidgetProvider.java:174:onReceive()] oooooo appWidgetId:3
D/QRemote ( 5992): [RemoteAppWidgetProvider.java:815:updateRemoteViews()] oooooo UpdateRemoteViews3:widgetId:3
D/QRemote ( 5992): [RemoteAppWidgetProvider.java:986:updateRemoteViews()] oooooo updateAppWidget5:widgetId:3]
I/ActivityManager( 1030): Killing 6294:com.lge.formmanager/u0a26 (adj 15): empty #17
,D/DeviceConnectionService( 1832): client connected with version: 7571000
,I/ActivityManager( 1030): Killing 6595:com.lge.appbox.client/u0a11 (adj 15): empty #18
,W/libprocessgroup( 1030): failed to open /acct/uid_10026/pid_6294/cgroup.procs: No such file or directory
,W/libprocessgroup( 1030): failed to open /acct/uid_10011/pid_6595/cgroup.procs: No such file or directory
,I/ActivityManager( 1030): Killing 6750:com.lge.drmservice/u0a62 (adj 15): empty #17
E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-65 f=2412 sc=60 link=65 tx=18.2, 0.0, 0.0  rx=15.7 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1564161964] gl rssi=-65 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-65 f=2412 sc=60 link=65 tx=18.2, 0.0, 0.0  rx=15.7 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-1564161963] gl rssi=-65 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
,W/libprocessgroup( 1030): failed to open /acct/uid_10062/pid_6750/cgroup.procs: No such file or directory
,D/sensors_hal_Time( 1030): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1030): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1030): tsOffsetIs: Apps: 137832256774; DSPS: 4657616; Offset : -4318956298
,I/ActivityManager( 1030): Killing 6659:com.android.chrome/u0a57 (adj 15): empty #17
,W/libprocessgroup( 1030): failed to open /acct/uid_10057/pid_6659/cgroup.procs: No such file or directory
,D/UEI.SmartControl( 7131): Internal timer expired: 1
,D/UEI.SmartControl( 7131): unbind internal service
,D/serial_port( 7131): close(fd = 25)
,I/UEI.SmartControl( 7131): Serial port is closed.
,E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-65 f=2412 sc=60 link=65 tx=10.6, 0.0, 0.0  rx=8.8 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:-1564158952] gl rssi=-65 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-65 f=2412 sc=60 link=65 tx=10.6, 0.0, 0.0  rx=8.8 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-1564158942] gl rssi=-65 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-65 f=2412 sc=60 link=65 tx=5.3, 0.0, 0.0  rx=4.4 bcn=0 [on:0 tx:0 rx:0 period:3019] from screen [on:0 period:-1564155908] gl rssi=-65 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-65 f=2412 sc=60 link=65 tx=5.3, 0.0, 0.0  rx=4.4 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-1564155907] gl rssi=-65 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
,I/[SystemUI]TimeTickManager( 1461): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1461): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1461): called onTimeUpdated()
I/[SystemUI]Clock( 1461): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1461): called onTimeUpdated()
I/[SystemUI]DateView( 1461): called onTimeUpdated()
I/[SystemUI]DateView( 1461): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1461): handleTimeUpdate
,I/[SystemUI]TimeTickManager( 1461): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1461): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1461): called onTimeUpdated()
I/[SystemUI]Clock( 1461): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1461): called onTimeUpdated()
,I/[SystemUI]DateView( 1461): called onTimeUpdated()
,I/[SystemUI]DateView( 1461): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1461): handleTimeUpdate
E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-65 f=2412 sc=60 link=65 tx=3.1, 0.0, 0.0  rx=2.7 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:-1564152888] gl rssi=-65 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-65 f=2412 sc=60 link=65 tx=3.1, 0.0, 0.0  rx=2.7 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1564152885] gl rssi=-65 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
,I/[SystemUI]QPairHandler( 1461): onReceive = android.intent.action.PACKAGE_CHANGED
,D/SplitUIService( 1884): replaced split : contains_com.google.android.talk / true
,I/InputReader( 1030): Reconfiguring input devices.  changes=0x00000010
,I/ActivityManager( 1030): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.manager.PreloadListManagerHelper: pid=7178 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
I/[SystemUI]QSlideListController( 1461): onReceive = android.intent.action.PACKAGE_CHANGED
,I/[SystemUI]AppWidgetPanel(QRemoteWidgetPanel)( 1461): onReceive = android.intent.action.PACKAGE_CHANGED, packageName : com.google.android.talk
I/[LGHome]EVENT( 2086): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.talk flg=0x4000010 (has extras) }
,W/ResourcesManager( 2086): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/[LGHome]Launcher( 2086): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
D/administrator( 1030): Handling package changes for user 0
,D/SplitUIManager( 1884): split_name #11 / not available #0
I/SplitUIService( 1884): split app #11
,I/AppUp4:AppBoxCP( 7178): onCreate
W/AppUp4:DB( 7178):  [AppBoxDatabaseHelper] construct
,I/AppUp4:DB( 7178):  setFingerPrint start
I/AppUp4:DB( 7178):  newfinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys SDK version = 21
,I/AppUp4:DB( 7178):  beforefinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys
I/AppUp4:DB( 7178):  SDK version = 21
I/AppUp4:DB( 7178):  beforefinger == newfinger no write in DB
D/AppUp4:AppBoxApplication( 7178): AppBoxApplication onCreate()
I/AppUp4:CustModeStarterReceiver( 7178): onReceive
,I/NotificationService( 1030): action=android.intent.action.PACKAGE_CHANGED queryReplace=false
D/BackupManagerService( 1030): Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.talk flg=0x4000010 (has extras) }
,W/ResourcesManager( 1030): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
D/LgDataFeature( 7178): LgDataFeature() Constructor: none
D/LgDataFeature( 7178): LgDataFeature() Constructor Done, null
,D/AppUp4:CustFacade( 7178): Context : android.app.ReceiverRestrictedContext@3476ef0a
D/AppUp4:CustFacade( 7178): isCustomizationCompleted : false
D/AppUp4:CustFacade( 7178): isPhone : true
D/AppUp4:CustModeStarterReceiver( 7178): begin check event
I/AppUp4:CustModeStarterReceiver( 7178): Event For Nothing, skip.
W/ResourcesManager( 1030): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourceType( 1030): Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
I/ActivityManager( 1030): Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=7214 uid=10019 gids={50019, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
I/ActivityManager( 1030): Killing 6791:com.google.android.apps.magazines/u0a93 (adj 15): empty #17
,W/libprocessgroup( 1030): failed to open /acct/uid_10093/pid_6791/cgroup.procs: No such file or directory
,I/[LGHome]EVENT( 2086): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
W/ResourcesManager( 7214): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7214): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 7214): Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
W/ResourcesManager( 7214): Asset path '/system/framework/lghiddenlibs.jar' does not exist or contains no resources.
W/ResourcesManager( 7214): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
,I/SystemConfig( 7214): BUILD Country: EU
I/SystemConfig( 7214): BUILD Operator: OPEN
,I/ActivityManager( 1030): Killing 6634:com.android.gallery3d/u0a27 (adj 15): empty #17
,W/libprocessgroup( 1030): failed to open /acct/uid_10027/pid_6634/cgroup.procs: No such file or directory
,I/SystemConfig( 7214): pm.hasSystemFeature(com.lge.ims.rcs) = false
,I/SystemConfig( 7214): existFile = false
I/SystemConfig( 7214): canReadFile = false
I/SystemConfig( 7214): systemFeature RCS result false
D/SystemConfig( 7214): refreshRcsSupport() :false
I/ActivityManager( 1030): Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=7237 uid=10027 gids={50027, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
,W/ResourcesManager( 7237): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7237): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 7237): Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
W/ResourcesManager( 7237): Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
,I/AppConfig( 7237): Total System Memory = 2995761152
,D/SystemHelper( 7237): region [EU], country [EU], operator [OPEN], sub-operator []
I/ActivityManager( 1030): Killing 6682:com.lge.email/u0a23 (adj 15): empty #17
,W/libprocessgroup( 1030): failed to open /acct/uid_10023/pid_6682/cgroup.procs: No such file or directory
,I/UpdateIcingCorporaServi( 4239): Updating corpora: APPS=com.google.android.talk, CONTACTS=MAYBE
,V/SIM_STK ( 1030): Menu title from STK is T-Mobile
,W/ResourcesManager( 4239): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/UpdateIcingCorporaServi( 4239): UpdateCorporaTask done [took 73 ms] updated apps [took 73 ms] 
I/ActivityManager( 1030): Start proc com.lge.lockscreensettings for broadcast com.lge.lockscreensettings/.PackageIntentReceiver: pid=7257 uid=10080 gids={50080, 9997, 1028, 1015} abi=armeabi-v7a
,I/LockScreenSettings( 7257): Wallpaper base directory = /data/data/com.lge.lockscreensettings/files/
,D/LockScreenSettings( 7257): Quick window widget present in DB = com.lge.clock.quickcover.QuickCoverSettingActivity  true
D/LockScreenSettings( 7257): Quick window widget present in DB = com.lge.camera.app.QuickWindowCameraActivity  true
D/LockScreenSettings( 7257): Quick window widget present in DB = com.android.contacts.activities.QuickCircleActivity  true
D/LockScreenSettings( 7257): Quick window widget present in DB = com.android.mms.quickcover.QuickCoverActivity  true
D/LockScreenSettings( 7257): Quick window widget present in DB = com.lge.music.MusicQuickCircle  true
D/LockScreenSettings( 7257): Quick window widget present in DB = com.lge.lifetracker.QuickCover  true
,D/PackageBroadcastService( 2356): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.talk
,I/ActivityManager( 1030): Killing 6395:com.wsandroid.suite.lge/1000 (adj 15): empty #17
W/libprocessgroup( 1030): failed to open /acct/uid_1000/pid_6395/cgroup.procs: No such file or directory
,I/PeopleContactsSync( 2356): CP2 sync disabled
,E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-65 f=2412 sc=60 link=65 tx=1.6, 0.0, 0.0  rx=1.4 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1564149860] gl rssi=-65 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-65 f=2412 sc=60 link=65 tx=1.6, 0.0, 0.0  rx=1.4 bcn=0 [on:0 tx:0 rx:0 period:8] from screen [on:0 period:-1564149852] gl rssi=-65 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-65 f=2412 sc=60 link=65 tx=1.3, 0.0, 0.0  rx=1.2 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1564146834] gl rssi=-65 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-65 f=2412 sc=60 link=65 tx=1.3, 0.0, 0.0  rx=1.2 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1564146831] gl rssi=-65 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-65 f=2412 sc=60 link=65 tx=1.1, 0.0, 0.0  rx=1.1 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1564143811] gl rssi=-65 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-65 f=2412 sc=60 link=65 tx=1.1, 0.0, 0.0  rx=1.1 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-1564143801] gl rssi=-65 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
D/PowerManagerServiceEx( 1030): acquireWakeLockInternal: lock=241109302, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1030
,V/AlarmManager( 1030): RTC_WAKEUP set : Alarm{3759618c type 0 when 1454429769089 com.android.vending} when 1454429769089
,D/[Concierge]Service( 2629): onStartCommand(). Type : 9
,D/PowerManagerServiceEx( 1030): releaseWakeLockInternal: lock=241109302 [*alarm*], flags=0x0
,V/SIM_STK ( 1030): Menu title from STK is T-Mobile
,V/GLSActivity( 2138): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2138): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 2138): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2138): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2138): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2138): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/Finsky  ( 7019): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 7019): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 7019): [1] 5.onFinished: Scheduling replication attempt 3.
,D/sensors_hal_Time( 1030): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1030): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1030): tsOffsetIs: Apps: 157833271246; DSPS: 5313009; Offset : -4318947708
,V/AlarmManager( 1030): ELAPSED_WAKEUP set : Alarm{1c61218e type 2 when 157888 android} when 157888
,E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-65 f=2412 sc=60 link=65 tx=0.6, 0.0, 0.0  rx=0.5 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1564140780] gl rssi=-65 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-65 f=2412 sc=60 link=65 tx=0.6, 0.0, 0.0  rx=0.5 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-1564140770] gl rssi=-65 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-65 f=2412 sc=60 link=65 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1564137749] gl rssi=-65 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-65 f=2412 sc=60 link=65 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1564137746] gl rssi=-65 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1030):  ConnectedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 1 0
,E/WifiStateMachine( 1030):  L2ConnectedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 1 0
,E/WifiStateMachine( 1030):  ConnectModeState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 1 0
,E/WifiStateMachine( 1030):  DriverStartedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 1 0
,E/WifiStateMachine( 1030):  SupplicantStartedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 1 0
E/WifiStateMachine( 1030):  DefaultState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 1 0
E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-65 f=2412 sc=60 link=65 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1564134720] gl rssi=-65 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-65 f=2412 sc=60 link=65 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:14] from screen [on:0 period:-1564134706] gl rssi=-65 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-65 f=2412 sc=60 link=65 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3005] from screen [on:0 period:-1564131685] gl rssi=-65 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-65 f=2412 sc=60 link=65 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:2] from screen [on:0 period:-1564131683] gl rssi=-65 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-65 f=2412 sc=60 link=65 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1564128662] gl rssi=-65 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-65 f=2412 sc=60 link=65 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:9] from screen [on:0 period:-1564128653] gl rssi=-65 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-65 f=2412 sc=60 link=65 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1564125632] gl rssi=-65 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-65 f=2412 sc=60 link=65 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:11] from screen [on:0 period:-1564125621] gl rssi=-65 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-65 f=2412 sc=60 link=65 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1564122598] gl rssi=-65 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-65 f=2412 sc=60 link=65 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1564122595] gl rssi=-65 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
,D/sensors_hal_Time( 1030): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1030): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1030): tsOffsetIs: Apps: 177835375196; DSPS: 5968438; Offset : -4318951033
,E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-65 f=2412 sc=60 link=65 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1564119570] gl rssi=-65 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-65 f=2412 sc=60 link=65 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:8] from screen [on:0 period:-1564119562] gl rssi=-65 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-65 f=2412 sc=60 link=65 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1564116541] gl rssi=-65 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-65 f=2412 sc=60 link=65 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:12] from screen [on:0 period:-1564116529] gl rssi=-65 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-65 f=2412 sc=60 link=65 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1564113515] gl rssi=-65 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-65 f=2412 sc=60 link=65 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1564113512] gl rssi=-65 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
,V/AlarmManager( 1030): RTC_WAKEUP set : Alarm{3dbe45bc type 0 when 1454429791957 com.android.vending} when 1454429791957
,V/AlarmManager( 1030): ELAPSED_WAKEUP set : Alarm{2eab2945 type 2 when 187904 android} when 187904
,V/SIM_STK ( 1030): Menu title from STK is T-Mobile
,V/GLSActivity( 2138): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2138): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 2138): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 2138): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2138): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2138): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/Finsky  ( 7019): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 7019): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 7019): [1] 5.onFinished: Scheduling replication attempt 4.
,I/BooksSync( 6614): Starting books sync
,D/BooksSync( 6614): started syncMyEbooks
,V/GLSActivity( 2138): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-65 f=2412 sc=60 link=65 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1564110488] gl rssi=-65 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-65 f=2412 sc=60 link=65 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-1564110487] gl rssi=-65 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
,I/GLSUser ( 2138): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.syncadapters.contacts, service: cp
I/GLSUser ( 2138): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> cp without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2138): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2138): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2138): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1030): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1030): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1030): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1030): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1030): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
W/GLSActivity( 2138): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2138): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2138): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2138): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2138): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2138): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2138): 	at android.os.Binder.execTransact(Binder.java:446)
D/ContactsSyncAdapter( 2138): innerSync failed
D/ContactsSyncAdapter( 2138): com.google.wireless.gdata2.client.AuthenticationException: unable to get auth token android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
D/ContactsSyncAdapter( 2138): 	at com.google.android.syncadapters.contacts.AuthInfo.getAuthToken(AuthInfo.java:45)
D/ContactsSyncAdapter( 2138): 	at com.google.android.syncadapters.contacts.ContactsSyncAdapter.innerPerformSync(ContactsSyncAdapter.java:263)
D/ContactsSyncAdapter( 2138): 	at com.google.android.syncadapters.contacts.ContactsSyncAdapter.onPerformLoggedSync(ContactsSyncAdapter.java:168)
D/ContactsSyncAdapter( 2138): 	at com.google.android.common.LoggingThreadedSyncAdapter.onPerformSync(LoggingThreadedSyncAdapter.java:33)
D/ContactsSyncAdapter( 2138): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
D/ContactsSyncAdapter( 2138): Caused by: android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
D/ContactsSyncAdapter( 2138): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
D/ContactsSyncAdapter( 2138): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
D/ContactsSyncAdapter( 2138): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
D/ContactsSyncAdapter( 2138): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
D/ContactsSyncAdapter( 2138): 	at android.os.Binder.execTransact(Binder.java:446)
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
D/LgeQuickCoverOverlayWindow( 1411): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1411): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1411): [native noti] inex =  2
,D/LgeQuickCoverNotificationData( 1411): isNotificationForCurrentUser : true
,E/LgeQuickCoverOverlayWindow( 1411): updateNotificationData: count=3
D/QuickStatusbarLayout( 1411): Notification difference=198
D/QuickStatusbarLayout( 1411): child = android.widget.LinearLayout{5df8279 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
D/SyncManager( 1030): failed sync operation thalitester@gmail.com u0 (com.google), com.android.contacts, LOCAL, currentRunTime 162603, reason: 10019, SyncResult: stats [ numAuthExceptions: 1]
D/SyncManager( 1030): not retrying sync operation because the error is a hard error: thalitester@gmail.com u0 (com.google), com.android.contacts, LOCAL, currentRunTime 253496, reason: 10019
,I/GLSUser ( 2138): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2138): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2138): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2138): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2138): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1030): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1030): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1030): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1030): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
W/GLSActivity( 2138): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2138): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2138): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2138): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2138): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2138): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2138): 	at android.os.Binder.execTransact(Binder.java:446)
D/NotificationServiceEx( 1030): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
E/BooksAccountManager( 6614): Authentication error
E/BooksAccountManager( 6614): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6614): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6614): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6614): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6614): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6614): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6614): null auth token
D/LgeQuickCoverNLService( 1411): onNotificationPosted
,D/SmartCoverUpdateMonitor( 1411): received broadcast com.lge.intent.action.NLDataPosted
,E/SmartCoverUpdateMonitor( 1411): MSG_NOTIFICATION_POSTED
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
D/QuickStatusbarLayout( 1411): child = android.widget.LinearLayout{5df8279 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,W/ApiaryClient( 6614): Error response from books API: {
W/ApiaryClient( 6614):  "error": {
W/ApiaryClient( 6614):   "errors": [
W/ApiaryClient( 6614):    {
W/ApiaryClient( 6614):     "domain": "global",
W/ApiaryClient( 6614):     "reason": "required",
W/ApiaryClient( 6614):     "message": "Login Required",
W/ApiaryClient( 6614):     "locationType": "header",
W/ApiaryClient( 6614):     "location": "Authorization"
W/ApiaryClient( 6614):    }
W/ApiaryClient( 6614):   ],
W/ApiaryClient( 6614):   "code": 401,
W/ApiaryClient( 6614):   "message": "Login Required"
W/ApiaryClient( 6614):  }
W/ApiaryClient( 6614): }
,W/ApiaryClient( 6614): errCount = 1: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6614): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-1984117918112689989&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6614): Headers:
W/ApiaryClient( 6614): accept-encoding: [gzip]
W/ApiaryClient( 6614): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6614): gdata-version: 2
,V/GLSActivity( 2138): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     ( 1030): Explicit concurrent mark sweep GC freed 43732(2017KB) AllocSpace objects, 3(304KB) LOS objects, 33% free, 44MB/66MB, paused 3.459ms total 172.880ms
,I/GLSUser ( 2138): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 2138): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2138): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2138): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2138): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1030): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1030): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1030): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1030): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1030): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
W/GLSActivity( 2138): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2138): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2138): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2138): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2138): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2138): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2138): 	at android.os.Binder.execTransact(Binder.java:446)
E/BooksAccountManager( 6614): Authentication error
E/BooksAccountManager( 6614): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6614): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6614): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6614): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6614): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6614): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6614): null auth token
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
D/LgeQuickCoverOverlayWindow( 1411): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1411): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1411): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1411): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1411): updateNotificationData: count=3
D/QuickStatusbarLayout( 1411): Notification difference=198
D/QuickStatusbarLayout( 1411): child = android.widget.LinearLayout{5df8279 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,W/ApiaryClient( 6614): Error response from books API: {
W/ApiaryClient( 6614):  "error": {
W/ApiaryClient( 6614):   "errors": [
W/ApiaryClient( 6614):    {
W/ApiaryClient( 6614):     "domain": "global",
W/ApiaryClient( 6614):     "reason": "required",
W/ApiaryClient( 6614):     "message": "Login Required",
W/ApiaryClient( 6614):     "locationType": "header",
W/ApiaryClient( 6614):     "location": "Authorization"
W/ApiaryClient( 6614):    }
W/ApiaryClient( 6614):   ],
W/ApiaryClient( 6614):   "code": 401,
W/ApiaryClient( 6614):   "message": "Login Required"
W/ApiaryClient( 6614):  }
W/ApiaryClient( 6614): }
,W/ApiaryClient( 6614): errCount = 2: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6614): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-1984117918112689989&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6614): Headers:
W/ApiaryClient( 6614): accept-encoding: [gzip]
W/ApiaryClient( 6614): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6614): gdata-version: 2
,V/GLSActivity( 2138): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2138): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2138): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2138): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2138): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2138): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1030): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1030): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1030): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1030): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1030): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1411): onNotificationPosted
D/SmartCoverUpdateMonitor( 1411): received broadcast com.lge.intent.action.NLDataPosted
,E/SmartCoverUpdateMonitor( 1411): MSG_NOTIFICATION_POSTED
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
W/GLSActivity( 2138): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2138): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2138): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2138): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2138): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2138): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2138): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 6614): Authentication error
E/BooksAccountManager( 6614): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6614): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6614): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6614): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6614): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6614): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6614): null auth token
D/QuickStatusbarLayout( 1411): Notification difference=198
D/QuickStatusbarLayout( 1411): child = android.widget.LinearLayout{5df8279 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-65 f=2412 sc=60 link=65 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3000] from screen [on:0 period:-1564107475] gl rssi=-65 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-65 f=2412 sc=60 link=65 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-1564107474] gl rssi=-65 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
,W/ApiaryClient( 6614): Error response from books API: {
W/ApiaryClient( 6614):  "error": {
W/ApiaryClient( 6614):   "errors": [
W/ApiaryClient( 6614):    {
W/ApiaryClient( 6614):     "domain": "global",
W/ApiaryClient( 6614):     "reason": "required",
W/ApiaryClient( 6614):     "message": "Login Required",
W/ApiaryClient( 6614):     "locationType": "header",
W/ApiaryClient( 6614):     "location": "Authorization"
W/ApiaryClient( 6614):    }
W/ApiaryClient( 6614):   ],
W/ApiaryClient( 6614):   "code": 401,
W/ApiaryClient( 6614):   "message": "Login Required"
W/ApiaryClient( 6614):  }
W/ApiaryClient( 6614): }
,W/ApiaryClient( 6614): errCount = 3: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6614): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-1984117918112689989&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6614): Headers:
W/ApiaryClient( 6614): accept-encoding: [gzip]
W/ApiaryClient( 6614): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6614): gdata-version: 2
,E/BooksSync( 6614): Soft error: 
E/BooksSync( 6614): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 6614): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-1984117918112689989&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 6614): Headers:
E/BooksSync( 6614): accept-encoding: [gzip]
E/BooksSync( 6614): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 6614): gdata-version: 2
E/BooksSync( 6614): 
E/BooksSync( 6614): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 6614): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 6614): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 6614): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 6614): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 6614): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 6614): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 6614): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 6614): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 6614): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 6614): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 6614): {
E/BooksSync( 6614):  "error": {
E/BooksSync( 6614):   "errors": [
E/BooksSync( 6614):    {
E/BooksSync( 6614):     "domain": "global",
E/BooksSync( 6614):     "reason": "required",
E/BooksSync( 6614):     "message": "Login Required",
E/BooksSync( 6614):     "locationType": "header",
E/BooksSync( 6614):     "location": "Authorization"
E/BooksSync( 6614):    }
E/BooksSync( 6614):   ],
E/BooksSync( 6614):   "code": 401,
E/BooksSync( 6614):   "message": "Login Required"
E/BooksSync( 6614):  }
E/BooksSync( 6614): }
E/BooksSync( 6614): 
E/BooksSync( 6614): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 6614): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 6614): 	... 8 more
,E/BooksSync( 6614): Sync error
E/BooksSync( 6614): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 6614): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-1984117918112689989&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 6614): Headers:
E/BooksSync( 6614): accept-encoding: [gzip]
E/BooksSync( 6614): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 6614): gdata-version: 2
E/BooksSync( 6614): 
E/BooksSync( 6614): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 6614): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 6614): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 6614): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 6614): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 6614): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 6614): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 6614): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 6614): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 6614): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 6614): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 6614): {
E/BooksSync( 6614):  "error": {
E/BooksSync( 6614):   "errors": [
E/BooksSync( 6614):    {
E/BooksSync( 6614):     "domain": "global",
E/BooksSync( 6614):     "reason": "required",
E/BooksSync( 6614):     "message": "Login Required",
E/BooksSync( 6614):     "locationType": "header",
E/BooksSync( 6614):     "location": "Authorization"
E/BooksSync( 6614):    }
E/BooksSync( 6614):   ],
E/BooksSync( 6614):   "code": 401,
E/BooksSync( 6614):   "message": "Login Required"
E/BooksSync( 6614):  }
E/BooksSync( 6614): }
E/BooksSync( 6614): 
E/BooksSync( 6614): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 6614): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 6614): 	... 8 more
I/BooksSync( 6614): Finished books sync
D/SyncManager( 1030): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 163365, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=4.4, 0.0, 0.0  rx=2.9 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1564104462] gl rssi=-64 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=4.4, 0.0, 0.0  rx=2.9 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-1564104452] gl rssi=-64 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=3.7, 0.0, 0.0  rx=2.9 bcn=0 [on:0 tx:0 rx:0 period:3000] from screen [on:0 period:-1564101432] gl rssi=-64 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=3.7, 0.0, 0.0  rx=2.9 bcn=0 [on:0 tx:0 rx:0 period:13] from screen [on:0 period:-1564101419] gl rssi=-64 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
,D/sensors_hal_Time( 1030): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1030): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1030): tsOffsetIs: Apps: 197837215345; DSPS: 6623858; Offset : -4318941990
,E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=2.3, 0.0, 0.0  rx=2.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1564098406] gl rssi=-64 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=2.3, 0.0, 0.0  rx=2.0 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-1564098396] gl rssi=-64 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=1.2, 0.0, 0.0  rx=1.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1564095375] gl rssi=-64 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=1.2, 0.0, 0.0  rx=1.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1564095372] gl rssi=-64 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
,I/[SystemUI]TimeTickManager( 1461): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1461): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1461): called onTimeUpdated()
,I/[SystemUI]Clock( 1461): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1461): called onTimeUpdated()
,I/[SystemUI]DateView( 1461): called onTimeUpdated()
I/[SystemUI]DateView( 1461): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1461): handleTimeUpdate
,E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=1.1, 0.0, 0.0  rx=1.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1564092350] gl rssi=-64 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=1.1, 0.0, 0.0  rx=1.0 bcn=0 [on:0 tx:0 rx:0 period:13] from screen [on:0 period:-1564092337] gl rssi=-64 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.5 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1564089316] gl rssi=-64 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.5 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1564089313] gl rssi=-64 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1564086288] gl rssi=-64 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-1564086287] gl rssi=-64 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
,D/PowerManagerServiceEx( 1030): acquireWakeLockInternal: lock=241109302, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1030
,V/AlarmManager( 1030): RTC_WAKEUP set : Alarm{286b316f type 0 when 1454429822528 com.android.vending} when 1454429822528
,D/[Concierge]Service( 2629): onStartCommand(). Type : 9
,D/PowerManagerServiceEx( 1030): releaseWakeLockInternal: lock=241109302 [*alarm*], flags=0x0
,V/SIM_STK ( 1030): Menu title from STK is T-Mobile
,V/GLSActivity( 2138): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2138): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 2138): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2138): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2138): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2138): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/Finsky  ( 7019): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 7019): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 7019): [1] 5.onFinished: Scheduling replication attempt 5.
,E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=0.9, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1564083277] gl rssi=-64 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=0.9, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:4] from screen [on:0 period:-1564083273] gl rssi=-64 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
,D/sensors_hal_Time( 1030): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1030): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1030): tsOffsetIs: Apps: 217839284920; DSPS: 7279286; Offset : -4318947612
,V/AlarmManager( 1030): ELAPSED_WAKEUP set : Alarm{12b168b9 type 2 when 218601 android} when 218601
,E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1564080258] gl rssi=-64 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:4] from screen [on:0 period:-1564080254] gl rssi=-64 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1564077230] gl rssi=-64 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-1564077220] gl rssi=-64 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1564074198] gl rssi=-64 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1564074195] gl rssi=-64 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1564071173] gl rssi=-64 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1564071170] gl rssi=-64 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=0.3, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1564068144] gl rssi=-64 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=0.3, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1564068141] gl rssi=-64 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1564065117] gl rssi=-64 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1564065114] gl rssi=-64 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1564062091] gl rssi=-64 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:9] from screen [on:0 period:-1564062082] gl rssi=-64 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
,D/sensors_hal_Time( 1030): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1030): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1030): tsOffsetIs: Apps: 237841303090; DSPS: 7934712; Offset : -4318943523
,E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1564059061] gl rssi=-64 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-1564059051] gl rssi=-64 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1564056029] gl rssi=-64 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1564056026] gl rssi=-64 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1564053000] gl rssi=-64 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:9] from screen [on:0 period:-1564052991] gl rssi=-64 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
,V/AlarmManager( 1030): ELAPSED_WAKEUP set : Alarm{3b8824fe type 2 when 211829 android} when 211829
,V/AlarmManager( 1030): RTC_WAKEUP set : Alarm{9b00eac type 0 when 1454429849993 com.android.vending} when 1454429849993
,V/SIM_STK ( 1030): Menu title from STK is T-Mobile
,V/GLSActivity( 2138): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2138): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 2138): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2138): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 2138): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2138): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/Finsky  ( 7019): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 7019): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 7019): [1] 5.onFinished: Giving up after 6 failures.
,I/[SystemUI]LGPowerUI( 1461): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1461): On Skip Timer : true
,D/LEDHandler( 1974): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1974): Battery Level Remaining: 100%
D/LEDHandler( 1974): Battery Temp: 284, mChargingStatus=5, mChargingStop=false
,D/KeyguardUpdateMonitor( 1461): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 284
,I/[SystemUI]LGPowerUI( 1461): onReceive = android.intent.action.BATTERY_CHANGED
D/WifiController( 1030): battery changed pluggedType: 2
I/[SystemUI]BatterySaverHandler( 1461): onReceive = android.intent.action.BATTERY_CHANGED
,W/Settings( 1030): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1030): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/HeadsetStateMachine( 6202): Disconnected process message: 10, size: 0
D/LGDMClient( 3948): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.intent.action.BATTERY_CHANGED
D/LGDMClient( 3948): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction,
E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1564049972] gl rssi=-64 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:17] from screen [on:0 period:-1564049955] gl rssi=-64 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1564046941] gl rssi=-64 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:12] from screen [on:0 period:-1564046929] gl rssi=-64 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
V/AlarmManager( 1030): ELAPSED_WAKEUP set : Alarm{2a85c9ae type 2 when 253405 android} when 253405
,I/BooksSync( 6614): Starting books sync
,D/BooksSync( 6614): started syncMyEbooks
,V/GLSActivity( 2138): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2138): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 2138): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2138): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2138): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2138): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
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
,D/LgeQuickCoverNotificationData( 1411): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1411): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1411): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1411): updateNotificationData: count=3
W/GLSActivity( 2138): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2138): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2138): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2138): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2138): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2138): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2138): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 6614): Authentication error
E/BooksAccountManager( 6614): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6614): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6614): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6614): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6614): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6614): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6614): null auth token
D/QuickStatusbarLayout( 1411): Notification difference=198
D/QuickStatusbarLayout( 1411): child = android.widget.LinearLayout{5df8279 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,W/ApiaryClient( 6614): Error response from books API: {
W/ApiaryClient( 6614):  "error": {
W/ApiaryClient( 6614):   "errors": [
W/ApiaryClient( 6614):    {
W/ApiaryClient( 6614):     "domain": "global",
W/ApiaryClient( 6614):     "reason": "required",
W/ApiaryClient( 6614):     "message": "Login Required",
W/ApiaryClient( 6614):     "locationType": "header",
W/ApiaryClient( 6614):     "location": "Authorization"
W/ApiaryClient( 6614):    }
W/ApiaryClient( 6614):   ],
W/ApiaryClient( 6614):   "code": 401,
W/ApiaryClient( 6614):   "message": "Login Required"
W/ApiaryClient( 6614):  }
W/ApiaryClient( 6614): }
,W/ApiaryClient( 6614): errCount = 1: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6614): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-6240726183224776830&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6614): Headers:
W/ApiaryClient( 6614): accept-encoding: [gzip]
W/ApiaryClient( 6614): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6614): gdata-version: 2
,V/GLSActivity( 2138): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2138): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2138): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2138): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2138): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2138): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
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
W/GLSActivity( 2138): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2138): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2138): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2138): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2138): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2138): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2138): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 6614): Authentication error
E/BooksAccountManager( 6614): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6614): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6614): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6614): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6614): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6614): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6614): null auth token
D/QuickStatusbarLayout( 1411): Notification difference=198
D/QuickStatusbarLayout( 1411): child = android.widget.LinearLayout{5df8279 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,W/ApiaryClient( 6614): Error response from books API: {
W/ApiaryClient( 6614):  "error": {
W/ApiaryClient( 6614):   "errors": [
W/ApiaryClient( 6614):    {
W/ApiaryClient( 6614):     "domain": "global",
W/ApiaryClient( 6614):     "reason": "required",
W/ApiaryClient( 6614):     "message": "Login Required",
W/ApiaryClient( 6614):     "locationType": "header",
W/ApiaryClient( 6614):     "location": "Authorization"
W/ApiaryClient( 6614):    }
W/ApiaryClient( 6614):   ],
W/ApiaryClient( 6614):   "code": 401,
W/ApiaryClient( 6614):   "message": "Login Required"
W/ApiaryClient( 6614):  }
W/ApiaryClient( 6614): }
,W/ApiaryClient( 6614): errCount = 2: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6614): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-6240726183224776830&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6614): Headers:
W/ApiaryClient( 6614): accept-encoding: [gzip]
W/ApiaryClient( 6614): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6614): gdata-version: 2
,E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3005] from screen [on:0 period:-1564043913] gl rssi=-64 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1564043910] gl rssi=-64 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
,V/GLSActivity( 2138): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2138): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2138): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2138): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 2138): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2138): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
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
,W/GLSActivity( 2138): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2138): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2138): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2138): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2138): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2138): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2138): 	at android.os.Binder.execTransact(Binder.java:446)
E/BooksAccountManager( 6614): Authentication error
E/BooksAccountManager( 6614): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6614): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6614): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6614): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6614): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6614): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6614): null auth token
D/QuickStatusbarLayout( 1411): Notification difference=198
D/QuickStatusbarLayout( 1411): child = android.widget.LinearLayout{5df8279 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,W/ApiaryClient( 6614): Error response from books API: {
W/ApiaryClient( 6614):  "error": {
W/ApiaryClient( 6614):   "errors": [
W/ApiaryClient( 6614):    {
W/ApiaryClient( 6614):     "domain": "global",
W/ApiaryClient( 6614):     "reason": "required",
W/ApiaryClient( 6614):     "message": "Login Required",
W/ApiaryClient( 6614):     "locationType": "header",
W/ApiaryClient( 6614):     "location": "Authorization"
W/ApiaryClient( 6614):    }
W/ApiaryClient( 6614):   ],
W/ApiaryClient( 6614):   "code": 401,
W/ApiaryClient( 6614):   "message": "Login Required"
W/ApiaryClient( 6614):  }
W/ApiaryClient( 6614): }
,W/ApiaryClient( 6614): errCount = 3: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6614): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-6240726183224776830&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6614): Headers:
W/ApiaryClient( 6614): accept-encoding: [gzip]
W/ApiaryClient( 6614): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6614): gdata-version: 2
,E/BooksSync( 6614): Soft error: 
E/BooksSync( 6614): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 6614): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-6240726183224776830&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 6614): Headers:
E/BooksSync( 6614): accept-encoding: [gzip]
E/BooksSync( 6614): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 6614): gdata-version: 2
E/BooksSync( 6614): 
E/BooksSync( 6614): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 6614): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 6614): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 6614): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 6614): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 6614): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 6614): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 6614): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 6614): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 6614): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 6614): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 6614): {
E/BooksSync( 6614):  "error": {
E/BooksSync( 6614):   "errors": [
E/BooksSync( 6614):    {
E/BooksSync( 6614):     "domain": "global",
E/BooksSync( 6614):     "reason": "required",
E/BooksSync( 6614):     "message": "Login Required",
E/BooksSync( 6614):     "locationType": "header",
E/BooksSync( 6614):     "location": "Authorization"
E/BooksSync( 6614):    }
E/BooksSync( 6614):   ],
E/BooksSync( 6614):   "code": 401,
E/BooksSync( 6614):   "message": "Login Required"
E/BooksSync( 6614):  }
E/BooksSync( 6614): }
E/BooksSync( 6614): 
E/BooksSync( 6614): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 6614): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 6614): 	... 8 more
,E/BooksSync( 6614): Sync error
E/BooksSync( 6614): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 6614): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-6240726183224776830&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 6614): Headers:
E/BooksSync( 6614): accept-encoding: [gzip]
E/BooksSync( 6614): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 6614): gdata-version: 2
E/BooksSync( 6614): 
E/BooksSync( 6614): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 6614): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 6614): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 6614): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 6614): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 6614): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 6614): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 6614): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 6614): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 6614): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 6614): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 6614): {
E/BooksSync( 6614):  "error": {
E/BooksSync( 6614):   "errors": [
E/BooksSync( 6614):    {
E/BooksSync( 6614):     "domain": "global",
E/BooksSync( 6614):     "reason": "required",
E/BooksSync( 6614):     "message": "Login Required",
E/BooksSync( 6614):     "locationType": "header",
E/BooksSync( 6614):     "location": "Authorization"
E/BooksSync( 6614):    }
E/BooksSync( 6614):   ],
E/BooksSync( 6614):   "code": 401,
E/BooksSync( 6614):   "message": "Login Required"
E/BooksSync( 6614):  }
E/BooksSync( 6614): }
E/BooksSync( 6614): 
E/BooksSync( 6614): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 6614): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 6614): 	... 8 more
I/BooksSync( 6614): Finished books sync
D/SyncManager( 1030): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 253405, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/sensors_hal_Time( 1030): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1030): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1030): tsOffsetIs: Apps: 257843007874; DSPS: 8590128; Offset : -4318947463
,E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=3.7, 0.0, 0.0  rx=2.7 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1564040891] gl rssi=-64 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=3.7, 0.0, 0.0  rx=2.7 bcn=0 [on:0 tx:0 rx:0 period:9] from screen [on:0 period:-1564040882] gl rssi=-64 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=3.4, 0.0, 0.0  rx=2.4 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1564037862] gl rssi=-64 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=3.4, 0.0, 0.0  rx=2.4 bcn=0 [on:0 tx:0 rx:0 period:11] from screen [on:0 period:-1564037851] gl rssi=-64 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=2.2, 0.0, 0.0  rx=1.7 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1564034831] gl rssi=-64 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=2.2, 0.0, 0.0  rx=1.7 bcn=0 [on:0 tx:0 rx:0 period:12] from screen [on:0 period:-1564034819] gl rssi=-64 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
I/[SystemUI]TimeTickManager( 1461): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1461): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1461): called onTimeUpdated()
I/[SystemUI]Clock( 1461): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1461): called onTimeUpdated()
I/[SystemUI]DateView( 1461): called onTimeUpdated()
I/[SystemUI]DateView( 1461): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1461): handleTimeUpdate
,E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=1.6, 0.0, 0.0  rx=1.3 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1564031804] gl rssi=-64 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=1.6, 0.0, 0.0  rx=1.3 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1564031801] gl rssi=-64 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1564028776] gl rssi=-64 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1564028773] gl rssi=-64 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=0.9, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1564025753] gl rssi=-64 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=0.9, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1564025750] gl rssi=-64 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1564022723] gl rssi=-64 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1564022720] gl rssi=-64 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
D/sensors_hal_Time( 1030): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1030): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1030): tsOffsetIs: Apps: 277844447293; DSPS: 9245535; Offset : -4318942839
,E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=3.7, 0.0, 0.0  rx=3.2 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1564019689] gl rssi=-64 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=3.7, 0.0, 0.0  rx=3.2 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1564019686] gl rssi=-64 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=1.9, 0.0, 0.0  rx=1.6 bcn=0 [on:0 tx:0 rx:0 period:3000] from screen [on:0 period:-1564016662] gl rssi=-64 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=1.9, 0.0, 0.0  rx=1.6 bcn=0 [on:0 tx:0 rx:0 period:9] from screen [on:0 period:-1564016653] gl rssi=-64 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
D/PowerManagerServiceEx( 1030): acquireWakeLockInternal: lock=241109302, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1030
,V/AlarmManager( 1030): ELAPSED_WAKEUP set : Alarm{3ad1eb28 type 2 when 283445 android} when 283445
D/[Concierge]Service( 2629): onStartCommand(). Type : 9
,D/PowerManagerServiceEx( 1030): releaseWakeLockInternal: lock=241109302 [*alarm*], flags=0x0
,E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=0.9, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1564013632] gl rssi=-64 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=0.9, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:11] from screen [on:0 period:-1564013621] gl rssi=-64 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3000] from screen [on:0 period:-1564010603] gl rssi=-64 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-1564010602] gl rssi=-64 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=0.2, 0.0, 0.0  rx=0.2 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1564007592] gl rssi=-64 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=0.2, 0.0, 0.0  rx=0.2 bcn=0 [on:0 tx:0 rx:0 period:9] from screen [on:0 period:-1564007583] gl rssi=-64 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1564004558] gl rssi=-64 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1564004555] gl rssi=-64 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1564001528] gl rssi=-64 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1564001525] gl rssi=-64 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
,D/sensors_hal_Time( 1030): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1030): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1030): tsOffsetIs: Apps: 297846351764; DSPS: 9900958; Offset : -4318960637
,E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1563998498] gl rssi=-64 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1563998495] gl rssi=-64 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=1.0, 0.0, 0.0  rx=1.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1563995471] gl rssi=-64 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=1.0, 0.0, 0.0  rx=1.0 bcn=0 [on:0 tx:0 rx:0 period:9] from screen [on:0 period:-1563995462] gl rssi=-64 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.5 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1563992442] gl rssi=-64 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.5 bcn=0 [on:0 tx:0 rx:0 period:12] from screen [on:0 period:-1563992430] gl rssi=-64 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=0.3, 0.0, 0.0  rx=0.3 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1563989410] gl rssi=-64 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=0.3, 0.0, 0.0  rx=0.3 bcn=0 [on:0 tx:0 rx:0 period:12] from screen [on:0 period:-1563989398] gl rssi=-64 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1563986376] gl rssi=-64 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1563986373] gl rssi=-64 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1563983350] gl rssi=-64 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:9] from screen [on:0 period:-1563983341] gl rssi=-64 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
,D/sensors_hal_Time( 1030): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1030): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1030): tsOffsetIs: Apps: 317848173215; DSPS: 10556377; Offset : -4318940062
,E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1563980321] gl rssi=-64 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:9] from screen [on:0 period:-1563980312] gl rssi=-64 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1563977292] gl rssi=-64 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:11] from screen [on:0 period:-1563977281] gl rssi=-64 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1563974259] gl rssi=-64 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1563974256] gl rssi=-64 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
,I/[SystemUI]TimeTickManager( 1461): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1461): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1461): called onTimeUpdated()
I/[SystemUI]Clock( 1461): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1461): called onTimeUpdated()
,I/[SystemUI]DateView( 1461): called onTimeUpdated()
,I/[SystemUI]DateView( 1461): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1461): handleTimeUpdate
,E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=1.0, 0.0, 0.0  rx=0.5 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1563971230] gl rssi=-64 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=1.0, 0.0, 0.0  rx=0.5 bcn=0 [on:0 tx:0 rx:0 period:4] from screen [on:0 period:-1563971226] gl rssi=-64 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.3 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1563968202] gl rssi=-64 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.3 bcn=0 [on:0 tx:0 rx:0 period:9] from screen [on:0 period:-1563968193] gl rssi=-64 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
I/wpa_supplicant( 6246): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=0
,D/WifiMonitor( 1030): Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=0]
E/WifiMonitor( 1030): WifiMonitor:wlan0 cnt=25 dispatchEvent: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=0
E/WifiMonitor( 1030): handleEvent 2  CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=0
D/WifiMonitor( 1030): handleNetworkStateChange: Could not parse disconnect string
E/WifiMonitor( 1030): WifiMonitor notify network disconnect: null reason=0
D/WifiMonitor( 1030): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1030): WifiMonitor:wlan0 cnt=26 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
E/WifiStateMachine( 1030):  ConnectedState NETWORK_DISCONNECTION_EVENT nid=0 reason=0 lastbssid=c0:ff:d4:d3:aa:48 freq=2412 rssi=-64 rt=332855
E/WifiStateMachine( 1030):  L2ConnectedState NETWORK_DISCONNECTION_EVENT nid=0 reason=0 lastbssid=c0:ff:d4:d3:aa:48 freq=2412 rssi=-64 rt=332855
E/WifiStateMachine( 1030):  ConnectModeState NETWORK_DISCONNECTION_EVENT nid=0 reason=0 lastbssid=c0:ff:d4:d3:aa:48 freq=2412 rssi=-64 rt=332856
E/WifiConfigStore( 1030): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/WifiNative-wlan0( 1030): doBoolean: SET_NETWORK 0 bssid any
,D/Tethering( 1030): InitialState.processMessage what=4
D/Tethering( 1030): sendTetherStateChangedBroadcast 0, 0, 0
,D/WifiNative-wlan0( 1030): SET_NETWORK 0 bssid any: returned true
D/WifiNative-wlan0( 1030): doBoolean: SAVE_CONFIG
D/WifiNative-wlan0( 1030): SAVE_CONFIG: returned true
D/WifiNative-wlan0( 1030): doBoolean: DRIVER BTCOEXMODE 2
D/LGWifiP2pService( 1030): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1030): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,I/wpa_supplicant( 6246): wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
D/WifiNative-wlan0( 1030): DRIVER BTCOEXMODE 2: returned true
D/WifiNative-wlan0( 1030): doBoolean: SET ps 1
D/WifiNative-wlan0( 1030): SET ps 1: returned true
D/CommandListener(  314): Clearing all IP addresses on wlan0
D/DhcpStateMachine( 1030): RunningState{ when=-6ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
V/NativeCrypto( 2138): Read error: ssl=0xaf4d3600: I/O error during system call, Connection timed out
,D/WifiMonitor( 1030): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
E/WifiMonitor( 1030): WifiMonitor:wlan0 cnt=27 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
I/jxcore-log( 6138): Toggling radios to false
I/jxcore-log( 6138): 
V/NativeCrypto( 2138): SSL shutdown failed: ssl=0xaf4d3600: I/O error during system call, Broken pipe
,I/wpa_supplicant( 6246): wlan0: CTRL-EVENT-SCAN-STARTED 
D/WifiMonitor( 1030): Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
,E/WifiMonitor( 1030): WifiMonitor:wlan0 cnt=28 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1030): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1030): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
,I/ActivityManager( 1030): Start proc com.android.settings for broadcast com.android.settings/.deviceinfo.UsbSettingsReceiver: pid=7429 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
D/ConnectivityService( 1030): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
D/ConnectivityService( 1030): NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 2
E/WifiStateMachine( 1030): WifiStateMachine: Leaving Connected state
D/WifiHS20( 1030): hidePasspointNotification off =false
,E/WifiStateMachine( 1030):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 26 0 rt=333031  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: DISCONNECTED
E/WifiStateMachine( 1030):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 26 0 rt=333032  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: DISCONNECTED
E/WifiStateMachine( 1030):  DisconnectedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1030):  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1030):  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1030):  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1030):  DefaultState CMD_TETHER_STATE_CHANGE 0 0
,E/WifiStateMachine( 1030):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 27 0 rt=333034  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
,D/ConnectivityService( 1030): reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10005
I/StatusBar.NetworkController( 1461): networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1461): mWifiConnected = false, mWifiLevel = 0
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1030): ValidatedState{ when=-1ms what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1030): DefaultState{ when=-1ms what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1030): Forcing reevaluation
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1030): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1030): Checking http://clients3.google.com/generate_204 on <unknown ssid>
D/StatusBar.NetworkController( 1461): refreshViews: Data not connected!! Set no data type icon / Roaming
,V/WfdStateTracker( 1974): handleWifiStateChangedEvent: 0
W/Settings( 1030): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1030): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1030): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
D/WifiHS20( 1030): hidePasspointNotification off =false
D/BluetoothManagerService( 1030): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,D/BluetoothManagerService( 1030): disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@1abb99e6 mBinding = false
E/WifiStateMachine( 1030):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 27 0 rt=333071  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
E/WifiStateMachine( 1030):  DisconnectedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1030):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1030):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1030):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1030):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
I/StatusBar.NetworkController( 1461): networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1461): mWifiConnected = false, mWifiLevel = 0
W/Settings( 1030): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1030): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1030): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
D/WifiHS20( 1030): hidePasspointNotification off =false
E/WifiStateMachine( 1030):  DisconnectedState CMD_UPDATE_LINKPROPERTIES 0 0
W/Settings( 1030): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1030): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1030): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
W/Settings( 1030): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1030): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1030): NETWORK_STATE_CHANGED_ACTION [SCANNING]
D/StatusBar.NetworkController( 1461): refreshViews: Data not connected!! Set no data type icon / Roaming
,D/ConnectivityService( 1030): Default network via Wi-Fi disconnect. stop DSQN
D/DSQN    ( 1030): disableDataServiceNotify
D/DSQN    ( 1030): stop dsqn bin
D/libc-netbsd(  314): default dns: query_ipv6=0, query_ipv4=0
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1030): Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
D/DSQN    ( 1030): DNSproblemNotiEnabled is disabled ignore DNS fail CB
I/StatusBar.NetworkController( 1461): networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1461): mWifiConnected = false, mWifiLevel = 0
E/WifiStateMachine( 1030):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1030):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1030):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1030):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
D/WifiNetworkAgent( 1030): NetworkAgent: NetworkAgent channel lost
D/StatusBar.NetworkController( 1461): refreshViews: Data not connected!! Set no data type icon / Roaming
D/ConnectivityService( 1030): notifyType LOST for NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService( 1030):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1030):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1030): sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
D/Nat464Xlat( 1030): requiresClat: netType=1, connected=false, hasIPv4Address=true, hasInternetCapability=true
D/CSLegacyTypeTracker( 1030): [lge_data] remove agent NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::c69a:2ff:fe7b:60ac/64,192.168.1.141/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} } list []  wasFirstNetwork :true
D/ConnectivityManager.CallbackHandler( 1461): CM callback handler got msg 524292
D/CSLegacyTypeTracker( 1030): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
D/ConnectivityService( 1030): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/BluetoothManagerService( 1030): Message: 2
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1030): EvaluatingState{ when=-2ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
,D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1030): DefaultState{ when=-2ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1030): Disconnected - quitting
D/BluetoothManagerService( 1030): Sending off request.
D/LocationManagerService( 1030): getAllProviders()=[passive, gps, network]
D/Ulp_jni ( 1030): JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 1,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
D/Ulp_jni ( 1030): JNI:system_update. Event-4
D/LGBluetoothServiceAdapter( 6202): [BTUI] Precleanup
I/StatusBar.NetworkController( 1461): networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1461): mWifiConnected = false, mWifiLevel = 0
D/BluetoothAdapterState( 6202): CURRENT_STATE=ON, MESSAGE = USER_TURN_OFF
D/BluetoothAdapterProperties( 6202): Setting state to 13
I/BluetoothAdapterState( 6202): Bluetooth adapter state changed: 12-> 13
D/BluetoothAdapterProperties( 6202): onBluetoothDisable()
D/StatusBar.NetworkController( 1461): refreshViews: Data not connected!! Set no data type icon / Roaming
I/BluetoothAdapterState( 6202): Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
D/WifiServiceImplEx( 1030): setWifiEnabled: false pid=6138, uid=10311, package= com.test.thalitest, App Lable : ThaliTest
D/BluetoothManagerService( 1030): Message: 60
D/WifiService( 1030): setWifiEnabled: false pid=6138, uid=10311
E/WifiService( 1030): Invoking mWifiStateMachine.setWifiEnabled
D/BluetoothManagerService( 1030): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 12, newState=13
D/BluetoothManagerService( 1030): Bluetooth State Change Intent: 12 -> 13
D/ConnectivityService( 1030): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService( 1030): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService( 1030): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService( 1030): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1030): sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/BluetoothAdapterProperties( 6202): Scan Mode:20
D/BluetoothAdapterState( 6202): CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
V/BluetoothPbapService( 6202): Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
D/btif_config_util( 6202): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
V/BluetoothMapMasInstance( 6202): Accept exception: (expected at shutdown)
V/BluetoothMapMasInstance( 6202): java.io.IOException: read failed, socket might closed or timeout, read ret: -1
V/BluetoothMapMasInstance( 6202): 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:586)
V/BluetoothMapMasInstance( 6202): 	at android.bluetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:563)
V/BluetoothMapMasInstance( 6202): 	at android.bluetooth.BluetoothSocket.accept(BluetoothSocket.java:418)
V/BluetoothMapMasInstance( 6202): 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:130)
V/BluetoothMapMasInstance( 6202): 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:116)
V/BluetoothMapMasInstance( 6202): 	at com.android.bluetooth.map.BluetoothMapMasInstance$SocketAcceptThread.run(BluetoothMapMasInstance.java:133)
D/LGBluetoothAPIService( 1974): [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
E/BtOppRfcommListener( 6202): Err,or accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
V/BluetoothFtpService:RfcommSocketAcceptThread( 6202): Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
D/NetworkManagementService( 1030): Removing idletimer
V/BluetoothSapService( 6202): Accept thread exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
D/TelephonyNetworkFactory-1( 1867): new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
W/Settings( 1030): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/bt-l2cap( 6202): L2CAP - L2CA_Deregister() called for PSM: 0x000f
W/bt-btif ( 6202): bta_dm_disable BTA_DISABLE_DELAY set to 1000 ms
D/ConnectivityService( 1030): requestNetworkTransitionWakelock: wakelock - ignore in airplane mode
D/TelephonyNetworkFactory-1( 1867):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
E/ConnectivityService( 1030): EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
D/WIFI    ( 1030): new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    ( 1030):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
W/bt-l2cap( 6202): L2CAP - L2CA_Deregister() called for PSM: 0x0019
W/bt-l2cap( 6202): L2CAP - L2CA_Deregister() called for PSM: 0x0017
W/bt-l2cap( 6202): L2CAP - L2CA_Deregister() called for PSM: 0x001b
W/bt-l2cap( 6202): L2CAP - L2CA_Deregister() called for PSM: 0x0019
W/bt-l2cap( 6202): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 6202): L2CAP - L2CA_Deregister() called for PSM: 0x0017
W/bt-l2cap( 6202): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-l2cap( 6202): L2CAP - L2CA_Deregister() called for PSM: 0x001b
W/bt-l2cap( 6202): L2CAP - PSM: 0x001b not found for deregistration
W/bt-l2cap( 6202): L2CAP - L2CA_Deregister() called for PSM: 0x0011
W/bt-l2cap( 6202): L2CAP - L2CA_Deregister() called for PSM: 0x0013
E/bt-btif ( 6202): bta_gattc_deregister Deregister Failedm unknown client cif
V/NetworkPolicy( 1030): [LG_RESTRICTED] !!!isConnected  type  :1
I/[SystemUI]BluetoothHandler( 1461): Receive : BluetoothAdapter.ACTION_STATE_CHANGED
I/BluetoothMapService( 6202): onReceive: android.bluetooth.adapter.action.STATE_CHANGED
D/BluetoothMapService( 6202): STATE_TURNING_OFF
V/BluetoothMapService( 6202): Handler(): got msg=4
D/BluetoothMapService( 6202): MAP Service closeService in
D/BluetoothMapMasInstance( 6202): MAP Service shutdown
D/LGBluetoothMapAdapter( 6202): [BTUI] LGBluetoothMapAdapter cleanup
V/BluetoothMapService( 6202): MAP Service closeService out
V/NetworkPolicy( 1030): [LG_RESTRICTED] !!!isConnected  type  :1
,V/BtOppService( 6202): Receiver DISABLED_ACTION 
I/BtOppRfcommListener( 6202): stopping Accept Thread
V/BtOppRfcommListener( 6202): close mBtServerSocket
D/LocSvc_java( 1030): Sending msg: 4 arg1:0 arg2:1
V/BtOppRfcommListener( 6202): waiting for thread to terminate
D/WifiServerServiceExt( 1030): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1030): setSupplicantStateSCANNING
D/LocSvc_java( 1030): Sending msg: 4 arg1:0 arg2:1
I/BtOppRfcommListener( 6202): BluetoothSocket listen thread finished
D/LocSvc_java( 1030): getAGpsConnectionInfo connType - 4
D/LocSvc_java( 1030): updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java( 1030): ignore wifi update if we are not in OPENING or CLOSING
D/LocSvc_java( 1030): getAGpsConnectionInfo connType - 4
D/LocSvc_java( 1030): updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java( 1030): ignore wifi update if we are not in OPENING or CLOSING
V/BtOppRfcommListener( 6202): done waiting for thread to terminate
V/BtOppService( 6202): onDestroy
D/LGBluetoothOppAdapter( 6202): [BTUI] LGBluetoothOppAdapter cleanup
,W/ResourcesManager( 7429): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7429): Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
W/ResourcesManager( 7429): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 7429): Asset path '/system/framework/com.lge.bluetooth.jar' does not exist or contains no resources.
W/ResourcesManager( 7429): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
W/ResourcesManager( 7429): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
D/TelephonyIcons( 1461): null signal icon name: drawable/stat_sys_signal_null
D/StatusBar.NetworkController( 1461): refreshViews: Data not connected!! Set no data type icon / Roaming
D/StatusBar.NetworkController( 1461): refreshViews: Data not connected!! Set no data type icon / Roaming
,D/LocationManagerService( 1030): getAllProviders()=[passive, gps, network]
I/jxcore-log( 6138): Radios toggled
I/jxcore-log( 6138): 
D/Ulp_jni ( 1030): JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
D/Ulp_jni ( 1030): JNI:system_update. Event-4
E/WifiStateMachine( 1030):  DisconnectedState CMD_STOP_SUPPLICANT 0 0
E/WifiStateMachine( 1030):  ConnectModeState CMD_STOP_SUPPLICANT 0 0
E/WifiStateMachine( 1030):  DriverStartedState CMD_STOP_SUPPLICANT 0 0
E/WifiStateMachine( 1030):  SupplicantStartedState CMD_STOP_SUPPLICANT 0 0
D/LGWifiP2pService( 1030): InactiveState{ when=0 what=131204 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiScanningService( 1030): SCAN_AVAILABLE : 1
D/LGWifiP2pService( 1030): P2pEnabledState{ when=-1ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
D/RttService( 1030): SCAN_AVAILABLE : 1
D/WifiScanningService( 1030): DefaultState got{ when=0 what=160007 target=com.android.internal.util.StateMachine$SmHandler }
D/RttService( 1030): EnabledState got{ when=-1ms what=160513 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiMonitor( 1030): stopMonitoring(p2p0) = com.android.server.wifi.p2p.LGWifiP2pServiceImpl$P2pStateMachine@768c43c
,D/LGWifiP2pService( 1030): P2pDisablingState
V/WfdStateTracker( 1974): WfdStateTracker handleDirectStateChangedEvent: 0
D/WfdsService( 1974): WifiP2pState is changed : false
D/LGWifiP2pService( 1030): P2pDisablingState{ when=-2ms what=147458 target=com.android.internal.util.StateMachine$SmHandler }
,D/WfdsService( 1974): WfdsEnabledState: Receive the WFDS_DISABLE message
D/WfdsService( 1974): Set the WFDS Monitor: false
D/LGWifiP2pService( 1030): p2p socket connection lost
D/LGWifiP2pService( 1030): P2pDisabledState
D/WfdsMonitor( 1974): WFDS Monitor is stopped
D/WfdsService( 1974): STATE : WfdsDisabledState - enter
D/CtrlSupplicant( 1974): Received on exit socket, terminate
E/CtrlSupplicant( 1974): wfds_wait_for_event: buf = CTRL-EVENT-TERMINATING  - connection closed
W/WfdsSession:Controller( 1974): DefaultState - msg [9441355] is not handled
D/WfdsMonitor( 1974): Event [CTRL-EVENT-TERMINATING  - connection closed]
D/WfdsMonitor( 1974): WfdsMonitorThread is received the interrupt - closing
W/WfdsService( 1974): DefaultState - msg [9445378] is not handled
E/WifiStateMachine( 1030):  WaitForP2pDisableState CMD_DISABLE_P2P_RSP uid=1000 0 0
D/LGWifiP2pService( 1030): P2pDisabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1030): DefaultState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0( 1030): doBoolean: DRIVER BTCOEXMODE 2
I/wpa_supplicant( 6246): wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
D/WifiNative-wlan0( 1030): DRIVER BTCOEXMODE 2: returned true
D/WifiNative-wlan0( 1030): doBoolean: SET ps 1
D/TelephonyIcons( 1461): null signal icon name: drawable/stat_sys_signal_null
D/WifiNative-wlan0( 1030): SET ps 1: returned true
D/CommandListener(  314): Clearing all IP addresses on wlan0
D/StatusBar.NetworkController( 1461): refreshViews: Data not connected!! Set no data type icon / Roaming
D/StatusBar.NetworkController( 1461): refreshViews: Data not connected!! Set no data type icon / Roaming
D/WifiHS20( 1030): hidePasspointNotification off =false
W/Settings( 1030): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1030): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1030): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
D/WifiNative-p2p0( 1030): doBoolean: TERMINATE
,D/WifiNative-p2p0( 1030): TERMINATE: returned true
E/WifiStateMachine( 1030): Couldn't get getWiFiOffloadingIface : 
E/WifiStateMachine( 1030): useWiFiOffloading() : false
E/WifiStateMachine( 1030): CONFIG_LGE_WLAN_PATH : true
D/WifiHS20( 1030): hidePasspointNotification off =false
W/Settings( 1030): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1030): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1030): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
V/WfdStateTracker( 1974): WfdStateTracker handleDirectStateChangedEvent: 6
I/WifiServerServiceExt( 1030): WIFI_STATE_CHANGED_ACTION [0]
I/StatusBar.NetworkController( 1461): networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
,I/StatusBar.NetworkController( 1461): mWifiConnected = false, mWifiLevel = 0
,D/StatusBar.NetworkController( 1461): refreshViews: Data not connected!! Set no data type icon / Roaming
I/StatusBar.NetworkController( 1461): networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1461): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1461): refreshViews: Data not connected!! Set no data type icon / Roaming
D/StatusBar.NetworkController( 1461): refreshViews: Data not connected!! Set no data type icon / Roaming
D/DhcpStateMachine( 1030): StoppedState
D/DhcpStateMachine( 1030): StoppedState{ when=-27ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiStateMachine( 1030):  SupplicantStoppingState CMD_ON_QUIT 0 0
E/WifiStateMachine( 1030):  DefaultState CMD_ON_QUIT 0 0
D/UsbSettingsReceiver( 7429): [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
D/UsbSettingsReceiver( 7429): [AUTORUN] sys.usb.config = ptp_only,adb
D/UsbSettingsReceiver( 7429): [AUTORUN] sys.usb.state = ptp_only,adb
D/UsbSettingsReceiver( 7429): [AUTORUN] persist.sys.usb.config = ptp_only,adb
D/UsbSettingsReceiver( 7429): [AUTORUN] onReceive() : app userid = 0, current userid = 0
,D/UsbSettingsControl( 7429): [AUTORUN] getUsbConnected() : connected=true
D/UsbSettingsReceiver( 7429): [AUTORUN] onReceive() : availableList=[]
D/UsbSettingsReceiver( 7429): [AUTORUN] onReceive() : activeList=[]
D/UsbSettingsReceiver( 7429): [AUTORUN] onReceive() : errorList=[]
,D/UsbSettingsControl( 7429): [AUTORUN] isAutorunTimer() : mAutorunChanging=false
D/UsbSettingsControl( 7429): [AUTORUN] setTetherStatus() : status=false
I/ActivityManager( 1030): Killing 6913:com.qualcomm.timeservice/1000 (adj 15): empty #17
W/ContextImpl( 7429): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
V/BluetoothPbapReceiver( 6202): PbapReceiver onReceive 
V/BluetoothPbapReceiver( 6202): ***********action = android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothPbapReceiver( 6202): ***********state = 13
V/BluetoothPbapReceiver( 6202): ***********Calling start service!!!! with action = null
,W/libprocessgroup( 1030): failed to open /acct/uid_1000/pid_6913/cgroup.procs: No such file or directory
V/BluetoothPbapService( 6202): action: android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothPbapService( 6202): state: 13
V/BluetoothPbapService( 6202): Pbap Service closeService in
V/BluetoothPbapService( 6202): successfully stopped pbap service
V/BluetoothPbapService( 6202): Pbap Service closeService out
V/BluetoothPbapService( 6202): Pbap Service onDestroy
V/BluetoothPbapService( 6202): Pbap Service closeService in
V/BluetoothPbapService( 6202): Pbap Service closeService out
D/LGBluetoothPbapAdapter( 6202): [BTUI] cleanup
D/BluetoothManagerService( 1030): Message: 20
D/BluetoothManagerService( 1030): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@37fadf7d:true
,I/ActivityManager( 1030): Start proc com.wsandroid.suite.lge for broadcast com.wsandroid.suite.lge/com.wavesecure.core.WSAndroidSystemIntentReceiver: pid=7474 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,D/BluetoothManagerService( 1030): Message: 30
,I/ActivityManager( 1030): Start proc com.lge.lifetracker for broadcast com.lge.lifetracker/.receiver.HealthDeviceReceiver: pid=7491 uid=10037 gids={50037, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
,D/BluetoothManagerService( 1030): Message: 30
,D/LocalBluetoothProfileManager( 7429): Adding local MAP profile
I/art     (  347): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 700us total 27.616ms
,D/BluetoothMap( 7429): Create BluetoothMap proxy object
D/BluetoothManagerService( 1030): Message: 30
W/ResourcesManager( 7474): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
D/BluetoothManagerService( 1030): Message: 30
,D/LocalBluetoothProfileManager( 7429): LocalBluetoothProfileManager construction complete
I/art     (  347): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 455us total 24.092ms
,D/LGBluetoothFeatureConfig( 7429):  get() - isFeatureLoaded : false
D/PluginManager( 7474): init()
,I/art     (  347): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 484us total 19.175ms
D/LGBluetoothUserBindClient( 7429): [BTUI] initUserBindClient
W/ContextImpl( 7429): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.android.settings.bluetooth.LGBluetoothUserBindClient.initUserBindClient:90 com.android.settings.bluetooth.LGBluetoothUserBindClient.<init>:55 com.android.settings.bluetooth.LGBluetoothUserBindClient.getInstance:47 
D/DockEventReceiver( 7429): finishStartingService: stopping service
,D/BluetoothInputDevice( 7429): Proxy object connected
D/HidProfile( 7429): Bluetooth service connected
D/BluetoothPan( 7429): BluetoothPAN Proxy object connected
D/PanProfile( 7429): Bluetooth service connected
D/BluetoothMap( 7429): Proxy object connected
D/MapProfile( 7429): Bluetooth service connected
D/BluetoothMap( 7429): getConnectedDevices()
D/BluetoothMap( 7429): Bluetooth is Not enabled
E/ActivityThread( 7491): Failed to find provider info for com.lge.lgaccount.provider
D/LGBluetoothUserBindClient( 7429): [BTUI] onServiceConnected
W/LG Account v2.2( 7491): No ProfileInfo entries
I/LG Account v2.2( 7491): isEnabled: false
I/Feature ( 7491): [Lifetracker]ver: 4.21.112(40211120)
,I/Feature ( 7491): [Lifetracker]Country: EU
I/Feature ( 7491): [Lifetracker]Operator: OPEN
I/Feature ( 7491): [Lifetracker]Ranking support: false
I/Feature ( 7491): [Lifetracker]Comfort support: false
I/Feature ( 7491): [Lifetracker]Accessory: true
I/Feature ( 7491): [Lifetracker]Health device: true
I/Feature ( 7491): [Lifetracker]Extra Pedometer: false
I/Feature ( 7491): [Lifetracker]Blood glucose device: false
I/Feature ( 7491): [Lifetracker]Device Number: 3
D/LGBluetoothAuthorization( 7429): [BTUI] cancel All Notification
,D/BluetoothPermissionRequest( 7429): onReceive
,D/LGBluetoothAuthorization( 7429): [BTUI] cancel All Notification
D/LGBluetoothResetSettingReceiver( 7429): return without doing reset settings.
I/ActivityManager( 1030): Killing 6931:com.android.calendar/u0a13 (adj 15): empty #17
,V/BluetoothOppReceiver( 6202): Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_TURNING_OFF
,W/libprocessgroup( 1030): failed to open /acct/uid_10013/pid_6931/cgroup.procs: No such file or directory
D/BluetoothOppNotification( 6202): [BTUI] cancel opp incoming file confirm notification
,D/BluetoothOppNotification( 6202): [BTUI] cancel opp active transfer file notification
V/BluetoothFtpReceiver( 6202): BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothFtpReceiver( 6202): BluetoothFtpReceiver Start Service
V/BluetoothFtpService( 6202): Ftp Service onStartCommand
V/BluetoothFtpService( 6202): action: android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothFtpService( 6202): Ftp Service closeService
E/BluetoothFtpService:RfcommSocketAcceptThread( 6202): Shutdown
V/BluetoothFtpService( 6202): successfully stopped ftp service
V/BluetoothSapReceiver( 6202): [BTUI] checkServiceStart
V/BluetoothSapReceiver( 6202): [BTUI] region:EU country:EU
,V/BluetoothSapReceiver( 6202): SapReceiver onReceive 
V/BluetoothSapReceiver( 6202): action = android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothSapReceiver( 6202):  Bluetooth Adapter state = 13
V/BluetoothSapReceiver( 6202): Calling SAP service start service with action = null
V/BluetoothFtpService( 6202): Ftp Service onDestroy
V/BluetoothFtpService( 6202): Ftp Service closeService
,I/ActivityManager( 1030): Start proc com.lge.settings.easy for broadcast com.lge.settings.easy/com.lge.settings.bluetooth.LGBluetoothProfileConnectionReceiver: pid=7517 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
V/BluetoothSapService( 6202): action: android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothSapService( 6202): state: 13
V/BluetoothSapService( 6202): Stopping SAP server process
V/BluetoothSapService( 6202): Sap Service closeSapService in
V/BluetoothSapService( 6202): Close listen Socket : 
V/BluetoothSapService( 6202): Close rfcomm Socket : 
V/BluetoothSapService( 6202): Close sapd  Socket : 
V/BluetoothSapService( 6202): Sap Service closeSapService out
V/BluetoothSapService( 6202): Sap Service onDestroy
V/BluetoothSapService( 6202): Sap Service closeSapService in
V/BluetoothSapService( 6202): Close listen Socket : 
V/BluetoothSapService( 6202): Close rfcomm Socket : 
V/BluetoothSapService( 6202): Close sapd  Socket : 
V/BluetoothSapService( 6202): Sap Service closeSapService out
,W/ResourcesManager( 7517): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,I/ActivityManager( 1030): Killing 6889:com.lge.clock/u0a10 (adj 15): empty #17
,D/AuthorizationBluetoothService( 2138): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,W/libprocessgroup( 1030): failed to open /acct/uid_10010/pid_6889/cgroup.procs: No such file or directory
,W/ExternalStrings( 7474): load override strings
W/ExternalStrings( 7474): java.lang.RuntimeException: Unexpected tag, got eat-comment
W/ExternalStrings( 7474): 	at com.mcafee.plugin.af.a(Unknown Source)
W/ExternalStrings( 7474): 	at com.mcafee.plugin.ac.b(Unknown Source)
W/ExternalStrings( 7474): 	at com.mcafee.plugin.ak.d(Unknown Source)
W/ExternalStrings( 7474): 	at com.mcafee.plugin.ak.a(Unknown Source)
W/ExternalStrings( 7474): 	at com.mcafee.app.s.getClassLoader(Unknown Source)
W/ExternalStrings( 7474): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5001)
W/ExternalStrings( 7474): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4609)
W/ExternalStrings( 7474): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4549)
W/ExternalStrings( 7474): 	at android.app.ActivityThread.access$1500(ActivityThread.java:148)
W/ExternalStrings( 7474): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1344)
W/ExternalStrings( 7474): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/ExternalStrings( 7474): 	at android.os.Looper.loop(Looper.java:135)
W/ExternalStrings( 7474): 	at android.app.ActivityThread.main(ActivityThread.java:5274)
W/ExternalStrings( 7474): 	at java.lang.reflect.Method.invoke(Native Method)
W/ExternalStrings( 7474): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/ExternalStrings( 7474): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
W/ExternalStrings( 7474): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
D/StatusProvider( 7474): onCreate
,V/Signer  ( 7474): override build config not found
,D/Signer  ( 7474): value of property debug is false
,D/LGMDMWrapper( 7474): Found class 'com.mcafee.lgmdm.LGMDMWrapper$DataWipe'.
,D/LGMDMWrapper( 7474): Found class 'com.mcafee.lgmdm.LGMDMWrapper$DownloadMode'.
,D/LGMDMWrapper( 7474): Found class 'com.mcafee.lgmdm.LGMDMWrapper$HardReset'.
D/LGMDMWrapper( 7474): Found class 'com.mcafee.lgmdm.LGMDMWrapper$HardwareKeyReset'.
D/LGMDMWrapper( 7474): Found class 'com.mcafee.lgmdm.LGMDMWrapper$RemoveDeviceAdmin'.
D/LGMDMWrapper( 7474): Found class 'com.mcafee.lgmdm.LGMDMWrapper$UnknownSourceInstallation'.
D/LGMDMWrapper( 7474): Found class 'com.mcafee.lgmdm.LGMDMWrapper$Usb'.
,D/LGMDMWrapper( 7474): Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbDebugging'.
D/LGMDMWrapper( 7474): Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbHostStorage'.
D/LGMDMWrapper( 7474): Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbMediaTransfer'.
D/LGMDMWrapper( 7474): Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbPictureTransfer'.
D/LGMDMWrapper( 7474): Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbStorage'.
D/LGMDMWrapper( 7474): Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbTethering'.
V/LGMDMManager( 7474): Create singleton instance
,E/WifiStateMachine( 1030):  SupplicantStoppingState CMD_RSSI_POLL 1 0 <unknown ssid> rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3000] from screen [on:0 period:-1563965174] gl rssi=-64 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1030):  DefaultState CMD_RSSI_POLL 1 0 <unknown ssid> rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:2] from screen [on:0 period:-1563965172] gl rssi=-64 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/LGMDMWrapper( 7474): LG MDM library v4.0.0 is available on this device.
,W/bt-btif ( 6202): ag scb idx 1 not allocated
,E/bt-btif ( 6202): BTA AG is already disabled, ignoring ...
D/bt_hci_bdroid( 6202): cleanup
W/bt-l2cap( 6202): L2CAP - L2CA_Deregister() called for PSM: 0x0019
,W/bt-l2cap( 6202): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 6202): L2CAP - L2CA_Deregister() called for PSM: 0x0017
W/bt-l2cap( 6202): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-l2cap( 6202): L2CAP - L2CA_Deregister() called for PSM: 0x001b
W/bt-l2cap( 6202): L2CAP - PSM: 0x001b not found for deregistration
W/bt-l2cap( 6202): L2CAP - L2CA_Deregister() called for PSM: 0x0019
W/bt-l2cap( 6202): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 6202): L2CAP - L2CA_Deregister() called for PSM: 0x0017
W/bt-l2cap( 6202): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-l2cap( 6202): L2CAP - L2CA_Deregister() called for PSM: 0x001b
W/bt-l2cap( 6202): L2CAP - PSM: 0x001b not found for deregistration
W/bt-l2cap( 6202): L2CAP - L2CA_Deregister() called for PSM: 0x0019
W/bt-l2cap( 6202): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 6202): L2CAP - L2CA_Deregister() called for PSM: 0x0017
,W/bt-l2cap( 6202): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-l2cap( 6202): L2CAP - L2CA_Deregister() called for PSM: 0x001b
W/bt-l2cap( 6202): L2CAP - PSM: 0x001b not found for deregistration,
E/bt-btif ( 6202): bta_gattc_deregister Deregister Failedm unknown client cif
I/bt_lpm  ( 6202): LPM is already off!!!
,I/bt_userial_mct( 6202): exiting userial_read_thread,
D/bt_userial_mct( 6202): Leaving userial_evt_read_thread()
D/bt_userial_mct( 6202): userial_close_reader Joined userial reader thread: 0
I/bt_vendor( 6202): hw_epilog_process
D/bt_hci_bdroid( 6202): cleanup Finalizing cleanup
D/bt_userial_mct( 6202): userial_close
E/bt_userial_mct( 6202): pthread_join() FAILED result:3
I/bt_vendor( 6202): bt-vendor : BT_VND_OP_USERIAL_CLOSE btSocType: 0
D/PostponalbeReceiver( 7474): WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
W/ContextImpl( 7474): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
,I/ActivityManager( 1030): Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=7546 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
I/ActivityManager( 1030): Killing 6770:com.lge.sizechangable.weather/u0a85 (adj 15): empty #17
W/ActivityThread( 7474): ClassLoader.getResources: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/libprocessgroup( 1030): failed to open /acct/uid_10085/pid_6770/cgroup.procs: No such file or directory
D/bt_hci_bdroid( 6202): set_power 0
I/bt_vendor( 6202): bt-vendor : BT_VND_OP_POWER_CTRL: Off
I/bt_vendor( 6202): bluetooth satus is on
I/bt_vendor( 6202): bt-vendor : resetting BT status
I/bt_vendor( 6202): Starting hciattach daemon
I/bt_vendor( 6202): try to set false
,I/bt_vendor( 6202): Starting hciattach daemon
I/bt_vendor( 6202): try to set false
I/bt_vendor( 6202): cleanup
I/GKI_LINUX( 6202): gki_task task_id=0 [BTU] terminating
I/GKI_LINUX( 6202): GKI_exit_task 0 done
I/GKI_LINUX( 6202): GKI_shutdown(): task [BTU] terminated
D/BluetoothAdapterState( 6202): CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
D/HeadsetService( 6202): Received stop request...Stopping profile...
,I/LGBluetoothHfpAdapter( 6202): [BTUI] LGBluetoothHfpAdapter cleanup
W/LGBluetoothHeadsetServiceJni( 6202): Cleaning up Bluetooth Handsfree callback object
D/BluetoothAdapterService( 6202): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@391cf1d6
D/HeadsetStateMachine( 6202): Exit Disconnected: -1
D/BluetoothHeadset( 1867): Proxy object disconnected
D/BluetoothHeadset( 1867): Proxy object disconnected
D/BluetoothHeadset( 1030): Proxy object disconnected
D/AudioService( 1030): onServiceDisconnected: Bluetooth profile: 1
D/BluetoothHeadset( 1867): Proxy object disconnected
D/A2dpService( 6202): Received stop request...Stopping profile...
D/A2dpStateMachine( 6202): Exit Disconnected: -1
D/LGBluetoothAvrcpQcomAdapter( 6202): [BTUI] cleanup
D/LGBluetoothA2dpAdapter( 6202): [BTUI] LGBluetoothA2dpAdapter cleanup
W/LGBluetoothA2dpServiceJni( 6202): Cleaning up Bluetooth Handsfree callback object
D/BluetoothAdapterService( 6202): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@391cf1d6
D/BluetoothA2dp( 1030): Proxy object disconnected
D/AudioService( 1030): onServiceDisconnected: Bluetooth profile: 2
D/HeadsetStateMachine( 6202): Unbinding service...
D/HeadsetPhoneState( 6202): [BTUI] listenForPhoneState : start = false
D/LGBluetoothHfpManager( 6202): [BTUI] listenForMultiSimPhoneState : start = false
D/HeadsetPhoneState( 6202): [BTUI] listenForPhoneState : start = false
D/LGBluetoothHfpManager( 6202): [BTUI] listenForMultiSimPhoneState : start = false
W/BluetoothHeadsetServiceJni( 6202): Cleaning up Bluetooth Handsfree Interface...
W/BluetoothHeadsetServiceJni( 6202): Cleaning up Bluetooth Handsfree callback object
I/LGBluetoothHfpAdapter( 6202): [BTUI] LGBluetoothHfpAdapter cleanup
D/HidService( 6202): Received stop request...Stopping profile...
D/BluetoothAdapterService( 6202): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@391cf1d6
D/BluetoothAdapterState( 6202): Stopping profile services that were post enabled
D/HealthService( 6202): Received stop request...Stopping profile...
D/BluetoothAdapterService( 6202): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@391cf1d6
D/BluetoothInputDevice( 7429): Proxy object disconnected
D/HidProfile( 7429): Bluetooth service disconnected
D/PanService( 6202): Received stop request...Stopping profile...
D/BluetoothAdapterService( 6202): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@391cf1d6
D/BluetoothPan( 7429): BluetoothPAN Proxy object disconnected
D/PanProfile( 7429): Bluetooth service disconnected
I/BluetoothA2dpServiceJni( 6202): cleanupNative
,I/GKI_LINUX( 6202): gki_task task_id=2 [A2DP-MEDIA] terminating
I/GKI_LINUX( 6202): GKI_exit_task 2 done
I/GKI_LINUX( 6202): GKI_shutdown(): task [A2DP-MEDIA] terminated
D/BtGatt.DebugUtils( 6202): handleDebugAction() action=null
D/BtGatt.GattService( 6202): Received stop request...Stopping profile...
D/BtGatt.GattService( 6202): stop()
D/BtGatt.AdvertiseManager( 6202): advertise clients cleared
D/BluetoothAdapterService( 6202): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@391cf1d6
D/BluetoothMapService( 6202): Received stop request...Stopping profile...
D/BluetoothMapService( 6202): stop()
D/BluetoothMapEmailAppObserver( 6202): deinitObservers()
D/BluetoothMapEmailAppObserver( 6202): removeReceiver()
D/BluetoothAdapterService( 6202): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@391cf1d6
W/BluetoothHidServiceJni( 6202): Cleaning up Bluetooth HID Interface...
W/BluetoothHidServiceJni( 6202): Cleaning up Bluetooth GID callback object
W/BluetoothHealthServiceJni( 6202): Cleaning up Bluetooth Health Interface...
W/BluetoothHealthServiceJni( 6202): Cleaning up Bluetooth Health object
W/LGBluetoothHealthServiceJni( 6202): Cleaning up Bluetooth Health object
W/BluetoothPanServiceJni( 6202): Cleaning up Bluetooth PAN Interface...
W/BluetoothPanServiceJni( 6202): Cleaning up Bluetooth PAN callback object
V/BluetoothMapService( 6202): Handler(): got msg=4
D/BluetoothMapService( 6202): MAP Service closeService in
D/LGBluetoothMapAdapter( 6202): [BTUI] LGBluetoothMapAdapter cleanup
V/BluetoothMapService( 6202): MAP Service closeService out
D/BluetoothMapService( 6202): cleanup()
D/BluetoothMapService( 6202): MAP Service closeService in
D/LGBluetoothMapAdapter( 6202): [BTUI] LGBluetoothMapAdapter cleanup
V/BluetoothMapService( 6202): MAP Service closeService out
D/BluetoothAdapterState( 6202): CURRENT_STATE=PENDING, MESSAGE = STOPPED, isTurningOn=false, isTurningOff=true
D/BluetoothMap( 7429): Proxy object disconnected
D/MapProfile( 7429): Bluetooth service disconnected
D/BluetoothAdapterProperties( 6202): Setting state to 10
I/BluetoothAdapterState( 6202): Bluetooth adapter state changed: 13-> 10
D/BluetoothManagerService( 1030): Message: 60
D/BluetoothManagerService( 1030): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 13, newState=10
D/BluetoothManagerService( 1030): Broadcasting onBluetoothStateChange(false) to 9 receivers.
D/BluetoothHeadset( 1867): onBluetoothStateChange: up=false
I/BluetoothAdapterState( 6202): Entering OffState
D/BluetoothPbap( 7429): onBluetoothStateChange: up=false
D/BluetoothA2dp( 1030): onBluetoothStateChange: up=false
D/BluetoothPan( 7429): onBluetoothStateChange on: false
D/BluetoothHeadset( 1867): onBluetoothStateChange: up=false
D/BluetoothMap( 7429): onBluetoothStateChange: up=false
D/BluetoothHeadset( 1867): onBluetoothStateChange: up=false
D/BluetoothHeadset( 1030): onBluetoothStateChange: up=false
D/BluetoothInputDevice( 7429): onBluetoothStateChange: up=false
D/BluetoothManagerService( 1030): Calling onBluetoothServiceDown callbacks
D/BluetoothManagerService( 1030): Broadcasting onBluetoothServiceDown() to 8 receivers.
,D/BluetoothManagerService( 1030): Calling onQBluetoothServiceDown callbacks
D/BluetoothManagerService( 1030): Broadcasting onQBluetoothServiceDown() to 0 receivers.
D/BluetoothManagerService( 1030): unbindAndFinish(): android.bluetooth.IBluetooth$Stub$Proxy@1abb99e6 mBinding = false
D/BluetoothManagerService( 1030): Sending unbind request.
D/BluetoothManagerService( 1030): Bluetooth State Change Intent: 13 -> 10
I/[SystemUI]BluetoothHandler( 1461): Receive : BluetoothAdapter.ACTION_STATE_CHANGED
D/LGBluetoothAPIService( 1974): [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
D/LGBluetoothAPIService( 1974): Message: 2
D/LGBluetoothAPIService( 1974): unbindAndFinish(): com.lge.bluetooth.ILGBluetoothAPIAdapter$Stub$Proxy@7bcb8a6 mBinding = false
D/LGBluetoothAPIService( 1974): Sending unbind request.
D/LGBluetoothFeatureConfig( 7429): isPrivacyLogsEnabled : true
E/LGBluetoothEventManager( 7429): [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_OFF
D/LGBluetoothEventManager( 7429): [BTUI] clear device connection state
W/ContextImpl( 7429): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
I/GKI_LINUX( 6202): gki_task task_id=1 [BTIF] terminating
I/GKI_LINUX( 6202): GKI_exit_task 1 done
I/GKI_LINUX( 6202): GKI_shutdown(): task [BTIF] terminated
I/BluetoothServiceJni( 6202): cleanupNative: return from cleanup
I/art     ( 6202): --- WEIRD: removing null entry 246
D/BluetoothAdapter( 1461): 643595312: getState() :  mService = null. Returning STATE_OFF
W/art     ( 6202): JNI WARNING: DeleteGlobalRef(0x2003da) failed to find entry
D/BluetoothAdapter( 1461): 643595312: getState() :  mService = null. Returning STATE_OFF
W/LGBluetoothServiceJni( 6202): Cleaning up Bluetooth Service callback object
,D/LGBluetoothSettingsDBObserver( 6202): [BTUI] unregister observer for LG device name DB
I/art     ( 6202): System.exit called, status: 0
I/AndroidRuntime( 6202): VM exiting with result code 0, cleanup skipped.
D/DockEventReceiver( 7429): finishStartingService: stopping service
V/AudioFlinger(  318): 6202 died, releasing its sessions
V/AudioFlinger(  318):  pid 1867 @ 0
V/AudioFlinger(  318):  pid 3258 @ 1
V/AudioFlinger(  318):  pid 3258 @ 2
D/LGBluetoothUserBindClient( 7429): [BTUI] onServiceDisconnected
,I/PCSuite ( 7546): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 7546): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 7546): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,I/ActivityManager( 1030): Process com.android.bluetooth (pid 6202) has died
W/ActivityManager( 1030): Scheduling restart of crashed service com.android.bluetooth/com.lge.bluetooth.app.LGBluetoothUserBindServer in 1000ms
,V/WiFiOffLoadBroadcast( 7429): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/LgDataFeature( 7429): LgDataFeature() Constructor: none
D/LgDataFeature( 7429): LgDataFeature() Constructor Done, null
,D/WiFiOffLoadBroadcast( 7429): MCCMNC not supported: null
D/LgDataFeature( 7474): LgDataFeature() Constructor: none
D/LgDataFeature( 7474): LgDataFeature() Constructor Done, null
D/BluetoothPermissionRequest( 7429): onReceive
D/LGBluetoothUtils( 7429): [BTUI] FileNotFound: readProperty
D/BluetoothDiscoverableTimeoutReceiver( 7429): cancelDiscoverableAlarm(): Enter
,D/LGBluetoothResetSettingReceiver( 7429): return without doing reset settings.
I/ActivityManager( 1030): Start proc com.android.bluetooth for broadcast com.android.bluetooth/.opp.BluetoothOppReceiver: pid=7589 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008, 4002, 1023} abi=armeabi-v7a
,I/ActivityManager( 1030): Killing 6968:com.google.android.talk/u0a72 (adj 15): empty #17
,W/ContextImpl( 7474): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.vsmandroid.gh.h:-1 com.mcafee.vsm.ext.common.a.d.a:-1 com.mcafee.vsm.ext.common.api.ExtUtils.stopApp:-1 
,W/libprocessgroup( 1030): failed to open /acct/uid_10072/pid_6968/cgroup.procs: No such file or directory
D/QRemote ( 5992): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 5992): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 5992): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
W/ResourcesManager( 7589): Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
D/PostponalbeReceiver( 7474): WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
W/ResourcesManager( 7589): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 7589): Asset path '/system/framework/com.qcom.bluetooth.jar' does not exist or contains no resources.
W/ResourcesManager( 7589): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
W/ContextImpl( 7474): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
,D/SiteAdvisor( 7474): com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.google.android.browser/com.android.browser.BrowserActivity not supported
I/PCSuite ( 7546): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 7546): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 7546): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
D/SiteAdvisor( 7474): com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.amazon.cloud9/com.amazon.cloud9.BrowserActivity not supported
V/WiFiOffLoadBroadcast( 7429): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/SiteAdvisor( 7474): com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.sec.android.app.sbrowser/com.sec.android.app.sbrowser.SBrowserMainActivity not supported
,D/SiteAdvisor( 7474): com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.sec.android.app.sbrowser/com.sec.android.app.sbrowser.SBrowserMainActivity not supported
D/SiteAdvisor( 7474): com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.htc.sense.browser/com.htc.sense.browser.BrowserActivity not supported
I/SiteAdvisor( 7474): com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Loading supported browsers: com.android.browser/com.android.browser.BrowserActivity; com.android.chrome/com.android.chrome.Main; 
D/WiFiOffLoadBroadcast( 7429): MCCMNC not supported: null
D/BluetoothAdapterApp( 7589): Loading JNI Library
D/SiteAdvisor( 7474): com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Here is the storedCurrentAppVersion: 3.1.2.1430
D/SiteAdvisor( 7474): com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Here about to commit perfs
,D/QRemote ( 5992): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 5992): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 5992): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
D/PostponalbeReceiver( 7474): WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
W/ContextImpl( 7474): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
I/PCSuite ( 7546): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 7546): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 7546): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 7429): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 7429): MCCMNC not supported: null
D/QRemote ( 5992): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,D/QRemote ( 5992): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 5992): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
D/PostponalbeReceiver( 7474): WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
W/ContextImpl( 7474): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
V/WiFiOffLoadBroadcast( 7429): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/BluetoothAdapterApp( 7589): REFCOUNT: Constructed com.android.bluetooth.btservice.AdapterApp@377ac05f Instance Count = 1
,D/WiFiOffLoadBroadcast( 7429): MCCMNC not supported: null
,D/BluetoothAdapterApp( 7589): onCreate
D/QRemote ( 5992): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 5992): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 5992): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
D/PostponalbeReceiver( 7474): WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
W/ContextImpl( 7474): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
,D/ProfileConfigQcom( 7589): [BTUI] HeadsetService is supported
D/ProfileConfigQcom( 7589): Adding HeadsetService
D/ProfileConfigQcom( 7589): [BTUI] A2dpService is supported
D/ProfileConfigQcom( 7589): Adding A2dpService
D/ProfileConfigQcom( 7589): [BTUI] HidService is supported
D/ProfileConfigQcom( 7589): Adding HidService
D/ProfileConfigQcom( 7589): [BTUI] HealthService is supported
D/ProfileConfigQcom( 7589): Adding HealthService
D/LGBluetoothFeatureConfig( 7589): isSupportPan() :  mTargetOp=OPEN
D/ProfileConfigQcom( 7589): [BTUI] PanService is supported
D/ProfileConfigQcom( 7589): Adding PanService
D/ProfileConfigQcom( 7589): [BTUI] GattService is supported
I/PCSuite ( 7546): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 7546): [StartReceiver][getUpdateNecessity]update = false
D/ProfileConfigQcom( 7589): Adding GattService
D/PCSuite ( 7546): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
D/ProfileConfigQcom( 7589): [BTUI] BluetoothMapService is supported
D/ProfileConfigQcom( 7589): Adding BluetoothMapService
D/ProfileConfigQcom( 7589): [BTUI] HeadsetClientService is NOT supported
D/LGBluetoothOppAdapter( 7589): [BTUI] getInstance : create [LGBluetoothOppAdapter]
V/WiFiOffLoadBroadcast( 7429): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,V/LGMDMManagerInternal( 7589): Create singleton instance,
D/WiFiOffLoadBroadcast( 7429): MCCMNC not supported: null
D/LGBluetoothUserBindClient( 7429): [BTUI] onServiceConnected
D/QRemote ( 5992): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 5992): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 5992): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,D/PostponalbeReceiver( 7474): WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
W/ContextImpl( 7474): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
I/PCSuite ( 7546): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 7546): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 7546): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 7429): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 7429): MCCMNC not supported: null
D/QRemote ( 5992): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 5992): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 5992): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,I/art     ( 1030): Explicit concurrent mark sweep GC freed 92782(4MB) AllocSpace objects, 7(752KB) LOS objects, 33% free, 44MB/66MB, paused 1.407ms total 103.888ms
,I/ActivityManager( 1030): Start proc com.lge.formmanager for broadcast com.lge.formmanager/.FormServiceReceiver: pid=7610 uid=10026 gids={50026, 9997, 3003, 1028} abi=armeabi-v7a
,V/BluetoothFtpReceiver( 7589): BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
,V/BluetoothSapReceiver( 7589): [BTUI] checkServiceStart
V/BluetoothSapReceiver( 7589): [BTUI] region:EU country:EU
V/BluetoothSapReceiver( 7589): SapReceiver onReceive 
V/BluetoothSapReceiver( 7589): action = android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothSapReceiver( 7589):  Bluetooth Adapter state = 10
D/LGBluetoothProfileConnectionReceiver_EasySetting( 7517): [BTUI] STATE_OFF : reset connected device information EasySettings
,I/ActivityManager( 1030): Killing 7075:com.google.android.gms:car/u0a5 (adj 15): empty #17
W/libprocessgroup( 1030): failed to open /acct/uid_10005/pid_7075/cgroup.procs: No such file or directory
D/AuthorizationBluetoothService( 2138): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,D/PCSuite ( 7546): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,V/WiFiOffLoadBroadcast( 7429): WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,D/WiFiOffLoadBroadcast( 7429): MCCMNC not supported: null
,W/FormManager( 7610): Network not available. Please check & try again.
,D/PostponalbeReceiver( 7474): WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
,V/FormManager( 7610): Network unavailable.
V/FormManager( 7610): Network unavailable.
D/PostponalbeReceiver( 7474): WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
,D/PostponalbeReceiver( 7474): WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
D/PostponalbeReceiver( 7474): WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
D/PostponalbeReceiver( 7474): WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
D/PostponalbeReceiver( 7474): WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
I/ActivityManager( 1030): Killing 7178:com.lge.appbox.client/u0a11 (adj 15): empty #17
,I/wpa_supplicant( 6246): p2p0: CTRL-EVENT-TERMINATING 
I/wpa_supplicant( 6246): monitor socket send errors count : 1
I/wpa_supplicant( 6246): CTRL_IFACE: Detach monitor /data/misc/wifi/sockets/wpa_ctrl_1974-2\x00 that cannot receive messages
W/wpa_supplicant( 6246): USIM:  scard_deinit function
D/WifiMonitor( 1030): Event [IFNAME=p2p0 CTRL-EVENT-TERMINATING ]
,D/WifiMonitor( 1030): Dropping event because (p2p0) is stopped
,D/WifiMonitor( 1030): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=0 BSSID=00:00:00:00:00:00 SSID=]
E/WifiMonitor( 1030): WifiMonitor:wlan0 cnt=29 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=0 BSSID=00:00:00:00:00:00 SSID=
E/WifiStateMachine( 1030):  SupplicantStoppingState SUPPLICANT_STATE_CHANGE_EVENT 29 0 rt=335059  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: DISCONNECTED
E/WifiStateMachine( 1030):  DefaultState SUPPLICANT_STATE_CHANGE_EVENT 29 0 rt=335061  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: DISCONNECTED
W/libprocessgroup( 1030): failed to open /acct/uid_10011/pid_7178/cgroup.procs: No such file or directory
,I/wpa_supplicant( 6246): wlan0: CTRL-EVENT-TERMINATING 
,D/WifiMonitor( 1030): Event [IFNAME=wlan0 CTRL-EVENT-TERMINATING ]
,E/WifiMonitor( 1030): WifiMonitor:wlan0 cnt=30 dispatchEvent: CTRL-EVENT-TERMINATING 
D/WifiMonitor( 1030): Disconnecting from the supplicant, no more events
E/WifiStateMachine( 1030):  SupplicantStoppingState SUP_DISCONNECTION_EVENT 30 0
D/WfdsService( 1974): Supplicant Connection state is changed : false
D/WfdsService( 1974): DefaultState - WIFI_SUPPLICANT_DISCONNECTED
D/WfdsService( 1974): Set the WFDS Monitor: false
D/WfdsMonitor( 1974): WFDS Monitor is stopped
,D/WifiOffDelayIfNotUsed( 1030): stopMonitoring
D/LGDMClient( 3948): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
E/WifiStateMachine( 1030): Couldn't get getWiFiOffloadingIface : 
E/WifiStateMachine( 1030): useWiFiOffloading() : false
E/WifiStateMachine( 1030): CONFIG_LGE_WLAN_PATH : true
D/LGDMClient( 3948): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
D/StatusBar.NetworkController( 1461): refreshViews: Data not connected!! Set no data type icon / Roaming
,V/WfdStateTracker( 1974): WfdStateTracker handleDirectStateChangedEvent: 0
,I/WifiServerServiceExt( 1030): WIFI_STATE_CHANGED_ACTION [1]
W/Settings( 1832): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/WifiServerServiceExt( 1030): batteryPsActivateMsgHandler : state:0 event:1
I/WifiServerServiceExt( 1030): batteryPsActivateMsgHandler : this is not treated
W/ContextImpl( 3948): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
W/ContextImpl( 3948): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,D/LGDMClient( 3948): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=3, isUserType=1
D/LGDMClient( 3948): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
D/LGDMClient( 3948): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
I/PCSuite ( 7546): [StartReceiver]WIFI_STATE_CHANGED_ACTION : WIFI_STATE_DISABLED
D/PCSuite ( 7546): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 7546): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 7429): WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,W/FormManager( 7610): Network not available. Please check & try again.
D/WiFiOffLoadBroadcast( 7429): MCCMNC not supported: null
V/FormManager( 7610): Network unavailable.
V/FormManager( 7610): Network unavailable.
,D/ConnectivityService( 1030): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering( 1030): MasterInitialState.processMessage what=3
D/ConnectivityService( 1030): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering( 1030): MasterInitialState.processMessage what=3
D/PostponalbeReceiver( 7474): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
,I/NetworkMonitor( 5264): type=WIFI subType= reason=null isConnected=false
,I/NetworkMonitor( 5264): type=WIFI subType= reason=null isConnected=false
D/GpsLocationProvider( 1030): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,W/ContextImpl( 7474): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
,D/GpsLocationProvider( 1030): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
I/ActivityManager( 1030): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=7650 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,D/GpsLocationProvider( 1030): updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/GpsLocationProvider( 1030): updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/AppUp4:AppBoxCP( 7650): onCreate
,W/AppUp4:DB( 7650):  [AppBoxDatabaseHelper] construct
I/AppUp4:DB( 7650):  setFingerPrint start
I/AppUp4:DB( 7650):  newfinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys SDK version = 21
,I/AppUp4:DB( 7650):  beforefinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys
I/AppUp4:DB( 7650):  SDK version = 21
I/AppUp4:DB( 7650):  beforefinger == newfinger no write in DB
D/AppUp4:AppBoxApplication( 7650): AppBoxApplication onCreate()
I/NetworkStateForAutoUpdateMonitor( 7650): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 7650): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 7650): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 7650): [onReceive] request level :IDLE....
,I/AppUp4:CustModeStarterReceiver( 7650): onReceive
,D/LgDataFeature( 7650): LgDataFeature() Constructor: none
D/LgDataFeature( 7650): LgDataFeature() Constructor Done, null
,D/AppUp4:CustFacade( 7650): Context : android.app.ReceiverRestrictedContext@e8881f1
,D/AppUp4:CustFacade( 7650): isCustomizationCompleted : false
D/AppUp4:CustFacade( 7650): isPhone : true
D/AppUp4:CustModeStarterReceiver( 7650): begin check event
I/AppUp4:CustModeStarterReceiver( 7650): Event For GoodConnectivity
D/AppUp4:CustModeStarterReceiver( 7650): runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
D/AppUp4:CustModeStarterReceiver( 7650): call method handleAsyncCustNotification.
D/AppUp4:CustModeStarterReceiver( 7650): handleAsync isTriedOnce : false
E/AppUp4:CustModeStarterReceiver( 7650): handleAsyncCustNotification do not startCustService
I/ActivityManager( 1030): Killing 7214:com.android.contacts/u0a19 (adj 15): empty #17
,D/LGDMClient( 3948): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
,W/libprocessgroup( 1030): failed to open /acct/uid_10019/pid_7214/cgroup.procs: No such file or directory
D/LGDMClient( 3948): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,W/ContextImpl( 3948): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
W/ContextImpl( 3948): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,D/LGDMClient( 3948): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=3, isUserType=1
D/LGDMClient( 3948): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMClient( 3948): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
I/ActivityManager( 1030): Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=7692 uid=10023 gids={50023, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,W/ResourcesManager( 7692): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7692): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,W/ResourcesManager( 7692): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
,W/ResourcesManager( 7692): Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
I/LGEmail ( 7692): [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,D/LGEmail ( 7692): user build Type == true (at Util.java isUserModeBuildType 3507)[v:6.41.18]
,W/ResourceType( 7692): No package identifier when getting value for resource number 0x00000000
,D/LgDataFeature( 7692): LgDataFeature() Constructor: none
D/LgDataFeature( 7692): LgDataFeature() Constructor Done, null
,D/eas_req ( 7692): ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
,V/FormManager( 7610): Network unavailable.
,V/FormManager( 7610): Network unavailable.
W/FormManager( 7610): Network not available. Please check & try again.
,I/LgeMiscReceiver( 3258): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 3258): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 3258): networkInfo.isConnected() = false
,I/HubEmail( 7692): JNI_OnLoad()
I/HubEmail( 7692): -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 7692): registerNatives()
I/HubEmail( 7692): -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 7692): registerNativeMethods()
I/HubEmail( 7692): -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
W/art     ( 7692): JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
,I/ActivityManager( 1030): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=7723 uid=10057 gids={50057, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager( 1030): Killing 7237:com.android.gallery3d/u0a27 (adj 15): empty #17
,W/libprocessgroup( 1030): failed to open /acct/uid_10027/pid_7237/cgroup.procs: No such file or directory
,W/Settings( 7692): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/ActivityManager( 1030): Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=7761 uid=10062 gids={50062, 9997, 4002, 3003, 1028} abi=armeabi-v7a
,I/ActivityManager( 1030): Killing 7257:com.lge.lockscreensettings/u0a80 (adj 15): empty #17
W/libprocessgroup( 1030): failed to open /acct/uid_10080/pid_7257/cgroup.procs: No such file or directory
,I/ActivityManager( 1030): Start proc com.lge.sizechangable.weather for broadcast com.lge.sizechangable.weather/.layout.WeatherWidget: pid=7780 uid=10085 gids={50085, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager( 1030): Killing 6816:com.google.android.apps.plus/u0a97 (adj 15): empty #17
,D/sensors_hal_Time( 1030): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1030): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1030): tsOffsetIs: Apps: 337849556645; DSPS: 11211783; Offset : -4318960076
,W/libprocessgroup( 1030): failed to open /acct/uid_10097/pid_6816/cgroup.procs: No such file or directory
I/art     ( 7780): Almond Protected OAT
,D/WeatherApplication( 7780): removeAccount
,D/WeatherApplication( 7780): Account.length = 0
,E/WeatherApplication( 7780): OPERATOR:OPEN
D/WeatherAncestor( 7780): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 17:19:12
,D/Weather.Utils( 7780): 2 : the weather widgets(using time tick) are gone.
D/Weather.Utils( 7780): 2 : All the weather widget is gone.
D/UpdateThreadPoolManager( 7780): 2 : This is isUpdating : false
D/WeatherAncestor( 7780): connectivity changed - connection : true
D/WeatherService( 7780): 2 : isServiceAlived():false forecastCache:null
,D/ForecastDataCache( 7780): 2 : lastUpdatedTime: 1430558561343
,D/ForecastDataCache( 7780): 2 : currentPackageVersion: 4.40.4
D/ForecastDataCache( 7780): 2 : Cache is not up-to-date, count: 0
,D/Weather_cast( 7780): 2 : isUpdateNeedForAlarm : no city return false
,D/WeatherAncestor( 7780): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 17:19:12
I/ActivityManager( 1030): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7799 uid=10093 gids={50093, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager( 1030): Killing 7101:com.google.android.gms.wearable/u0a5 (adj 15): empty #17
W/libprocessgroup( 1030): failed to open /acct/uid_10005/pid_7101/cgroup.procs: No such file or directory
D/LGWifiP2pService( 1030): P2pDisabledState{ when=-2ms what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1030): DefaultState{ when=-2ms what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
,E/WifiStateMachine( 1030):  InitialState CMD_STOP_SUPPLICANT_FAILED 1 0
E/WifiStateMachine( 1030):  DefaultState CMD_STOP_SUPPLICANT_FAILED 1 0
,E/VoldCmdListener(  278): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
,E/Vold    (  278): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7799): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
E/VoldCmdListener(  278): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  278): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7799): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
E/VoldCmdListener(  278): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  278): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7799): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
,E/VoldCmdListener(  278): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
,E/Vold    (  278): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7799): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
I/WebViewFactory( 7799): Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,I/LibraryLoader( 7799): Loading: webviewchromium
I/LibraryLoader( 7799): Time to load native libraries: 4 ms (timestamps 8580-8584)
I/LibraryLoader( 7799): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 7799): Binding Chromium to main looper Looper (main, tid 1) {2abadb12}
I/LibraryLoader( 7799): Expected native library version number "",actual native library version number ""
I/chromium( 7799): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 7799): Initializing chromium process, renderers=0
,W/art     ( 7799): Attempt to remove local handle scope entry from IRT, ignoring
W/chromium( 7799): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
,I/chromium( 7799): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=38 off=46780 len=2953
,I/chromium( 7799): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:39 off:229536 len:643667
V/AudioPolicyService(  318): registerClient() client 0xb57bc320, uid 10093
W/AudioManagerAndroid( 7799): Requires BLUETOOTH permission
I/Adreno-EGL( 7799): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 7799): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 7799): Build Date: 12/12/14 금
I/Adreno-EGL( 7799): Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
I/Adreno-EGL( 7799): Remote Branch: 
I/Adreno-EGL( 7799): Local Patches: 
I/Adreno-EGL( 7799): Reconstruct Branch: 
,I/NSApplication( 7799): Starting up...
,I/ActivityManager( 1030): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=7854 uid=10097 gids={50097, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
I/ActivityManager( 1030): Killing 7019:com.android.vending/u0a44 (adj 15): empty #17
,I/art     (  347): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 467us total 22.647ms
,I/art     (  347): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 440us total 20.986ms
,I/art     (  347): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 444us total 20.413ms
,W/libprocessgroup( 1030): failed to open /acct/uid_10044/pid_7019/cgroup.procs: No such file or directory
,W/ResourcesManager( 7854): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/iu.Environment( 2356): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,I/iu.UploadsManager( 2356): num queued entries: 0
I/iu.UploadsManager( 2356): num updated entries: 0
D/ChimeraCfgMgr( 2356): Loading module com.google.android.gms.kids from APK com.google.android.gms
,I/iu.SyncManager( 2356): NEXT; no task
,D/PostponalbeReceiver( 7474): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
W/ContextImpl( 7474): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
I/NetworkStateForAutoUpdateMonitor( 7650): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 7650): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 7650): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 7650): [onReceive] request level :IDLE....
,I/AppUp4:CustModeStarterReceiver( 7650): onReceive
D/AppUp4:CustFacade( 7650): Context : android.app.ReceiverRestrictedContext@e8881f1
D/AppUp4:CustFacade( 7650): isCustomizationCompleted : false
D/AppUp4:CustFacade( 7650): isPhone : true
D/AppUp4:CustModeStarterReceiver( 7650): begin check event
,I/GLSActivity( 2138): [ac] getting account id
I/AppUp4:CustModeStarterReceiver( 7650): Event For GoodConnectivity, noConnectivity : false, but skip! 
D/LGDMClient( 3948): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 3948): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
W/ContextImpl( 3948): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
I/GLSUser ( 2138): [t] Fetched account id for thalitester@gmail.com : 105256135866144380227
W/ContextImpl( 3948): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,D/LGDMClient( 3948): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=3, isUserType=1
,D/eas_req ( 7692): ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
,D/LGDMClient( 3948): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 3948): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
W/Settings( 7692): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/LgeMiscReceiver( 3258): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 3258): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 3258): networkInfo.isConnected() = false
W/FormManager( 7610): Network not available. Please check & try again.
,D/WeatherAncestor( 7780): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 17:19:13
V/FormManager( 7610): Network unavailable.
,V/FormManager( 7610): Network unavailable.
D/Weather.Utils( 7780): 2 : the weather widgets(using time tick) are gone.
D/Weather.Utils( 7780): 2 : All the weather widget is gone.
D/UpdateThreadPoolManager( 7780): 2 : This is isUpdating : false
D/WeatherAncestor( 7780): connectivity changed - connection : true
D/WeatherService( 7780): 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@4865c57
D/ForecastDataCache( 7780): 2 : lastUpdatedTime: 1430558561343
D/ForecastDataCache( 7780): 2 : currentPackageVersion: 4.40.4
D/ForecastDataCache( 7780): 2 : Cache is up-to-date, count: 0
D/Weather_cast( 7780): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherAncestor( 7780): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 17:19:13
D/ChimeraCfgMgr( 2356): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/PowerManagerServiceEx( 1030): acquireWakeLockInternal: lock=241109302, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1030
,V/AlarmManager( 1030): ELAPSED_WAKEUP set : Alarm{21f16edb type 2 when 339662 com.google.android.gms} when 339662
D/libc-netbsd(  314): default dns: query_ipv6=0, query_ipv4=0
D/DSQN    ( 1030): DNSproblemNotiEnabled is disabled ignore DNS fail CB
,D/[Concierge]Service( 2629): onStartCommand(). Type : 9
,D/PowerManagerServiceEx( 1030): releaseWakeLockInternal: lock=241109302 [*alarm*], flags=0x0
,I/GAV4    ( 7799): Thread[GAThread,5,main]: No campaign data found.
,I/ActivityManager( 1030): Killing 6614:com.google.android.apps.books/u0a54 (adj 15): empty #17
,W/libprocessgroup( 1030): failed to open /acct/uid_10054/pid_6614/cgroup.procs: No such file or directory
,D/sensors_hal_Time( 1030): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1030): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1030): tsOffsetIs: Apps: 357852346951; DSPS: 11867234; Offset : -4318946948
,D/sensors_hal_Time( 1030): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1030): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1030): tsOffsetIs: Apps: 377854508609; DSPS: 12522665; Offset : -4318952168
,V/AlarmManager( 1030): ELAPSED_WAKEUP set : Alarm{150f5cb6 type 2 when 378369 android} when 378369
,I/[SystemUI]TimeTickManager( 1461): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1461): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1461): called onTimeUpdated()
I/[SystemUI]Clock( 1461): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1461): called onTimeUpdated()
,I/[SystemUI]DateView( 1461): called onTimeUpdated()
,I/[SystemUI]DateView( 1461): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1461): handleTimeUpdate
,D/sensors_hal_Time( 1030): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1030): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1030): tsOffsetIs: Apps: 397856357143; DSPS: 13178085; Offset : -4318934558
,D/sensors_hal_Time( 1030): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1030): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1030): tsOffsetIs: Apps: 417858495938; DSPS: 13833515; Offset : -4318931992
,D/sensors_hal_Time( 1030): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1030): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1030): tsOffsetIs: Apps: 437860414316; DSPS: 14488938; Offset : -4318936379
,I/[SystemUI]TimeTickManager( 1461): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1461): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1461): called onTimeUpdated()
,I/[SystemUI]Clock( 1461): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1461): called onTimeUpdated()
,I/[SystemUI]DateView( 1461): called onTimeUpdated()
,I/[SystemUI]DateView( 1461): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1461): handleTimeUpdate
,D/sensors_hal_Time( 1030): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1030): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1030): tsOffsetIs: Apps: 457862265766; DSPS: 15144359; Offset : -4318946293
,D/sensors_hal_Time( 1030): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1030): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1030): tsOffsetIs: Apps: 477864320342; DSPS: 15799786; Offset : -4318936473
,D/sensors_hal_Time( 1030): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1030): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1030): tsOffsetIs: Apps: 497866423043; DSPS: 16455215; Offset : -4318939642
,I/[SystemUI]TimeTickManager( 1461): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1461): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1461): called onTimeUpdated()
,I/[SystemUI]Clock( 1461): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1461): called onTimeUpdated()
,I/[SystemUI]DateView( 1461): called onTimeUpdated()
I/[SystemUI]DateView( 1461): called onTimeUpdated()
,D/KeyguardUpdateMonitor( 1461): handleTimeUpdate
D/sensors_hal_Time( 1030): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1030): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1030): tsOffsetIs: Apps: 517868234337; DSPS: 17110635; Offset : -4318959324
,D/sensors_hal_Time( 1030): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1030): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1030): tsOffsetIs: Apps: 537870797820; DSPS: 17766079; Offset : -4318959317
,D/sensors_hal_Time( 1030): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1030): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1030): tsOffsetIs: Apps: 557872433957; DSPS: 18421492; Offset : -4318940612
,I/[SystemUI]TimeTickManager( 1461): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1461): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1461): called onTimeUpdated()
,I/[SystemUI]Clock( 1461): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1461): called onTimeUpdated()
I/[SystemUI]DateView( 1461): called onTimeUpdated()
I/[SystemUI]DateView( 1461): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1461): handleTimeUpdate
,D/sensors_hal_Time( 1030): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1030): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1030): tsOffsetIs: Apps: 577874472023; DSPS: 19076919; Offset : -4318947223
,D/sensors_hal_Time( 1030): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1030): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1030): tsOffsetIs: Apps: 597876542119; DSPS: 19732347; Offset : -4318952375
,D/sensors_hal_Time( 1030): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1030): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1030): tsOffsetIs: Apps: 617878634715; DSPS: 20387775; Offset : -4318935001
,I/[SystemUI]TimeTickManager( 1461): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1461): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1461): called onTimeUpdated()
I/[SystemUI]Clock( 1461): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1461): called onTimeUpdated()
I/[SystemUI]DateView( 1461): called onTimeUpdated()
I/[SystemUI]DateView( 1461): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1461): handleTimeUpdate
,D/sensors_hal_Time( 1030): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1030): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1030): tsOffsetIs: Apps: 637880650438; DSPS: 21043201; Offset : -4318933359
,I/ActivityManager( 1030): Killing 7491:com.lge.lifetracker/u0a37 (adj 15): empty #17
,W/libprocessgroup( 1030): failed to open /acct/uid_10037/pid_7491/cgroup.procs: No such file or directory
,D/sensors_hal_Time( 1030): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1030): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1030): tsOffsetIs: Apps: 657882527617; DSPS: 21698623; Offset : -4318948270
,D/sensors_hal_Time( 1030): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1030): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1030): tsOffsetIs: Apps: 677884152193; DSPS: 22354036; Offset : -4318941100
,I/[SystemUI]TimeTickManager( 1461): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1461): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1461): called onTimeUpdated()
,I/[SystemUI]Clock( 1461): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1461): called onTimeUpdated()
I/[SystemUI]DateView( 1461): called onTimeUpdated()
I/[SystemUI]DateView( 1461): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1461): handleTimeUpdate
,D/sensors_hal_Time( 1030): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1030): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1030): tsOffsetIs: Apps: 697886226039; DSPS: 23009464; Offset : -4318942319
,D/PowerManagerServiceEx( 1030): acquireWakeLockInternal: lock=241109302, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1030
,V/AlarmManager( 1030): RTC_WAKEUP set : Alarm{108e1db7 type 0 when 1454429967890 com.google.android.gms} when 1454429967890
,D/[Concierge]Service( 2629): onStartCommand(). Type : 9
,D/PowerManagerServiceEx( 1030): releaseWakeLockInternal: lock=241109302 [*alarm*], flags=0x0
,I/EventLogService( 2356): Aggregate from 1454428167852 (log), 1454428167852 (data)
,I/art     ( 2138): Explicit concurrent mark sweep GC freed 34684(2MB) AllocSpace objects, 16(2MB) LOS objects, 51% free, 30MB/62MB, paused 1.305ms total 60.859ms
,D/sensors_hal_Time( 1030): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1030): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1030): tsOffsetIs: Apps: 717888334052; DSPS: 23664893; Offset : -4318940124
,D/sensors_hal_Time( 1030): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1030): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1030): tsOffsetIs: Apps: 737891094931; DSPS: 24320344; Offset : -4318956448
,I/[SystemUI]TimeTickManager( 1461): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1461): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1461): called onTimeUpdated()
,I/[SystemUI]Clock( 1461): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1461): called onTimeUpdated()
,I/[SystemUI]DateView( 1461): called onTimeUpdated()
I/[SystemUI]DateView( 1461): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1461): handleTimeUpdate
,D/sensors_hal_Time( 1030): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1030): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1030): tsOffsetIs: Apps: 757893063360; DSPS: 24975768; Offset : -4318941143
,D/sensors_hal_Time( 1030): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1030): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1030): tsOffsetIs: Apps: 777894933873; DSPS: 25631189; Offset : -4318932229
,D/sensors_hal_Time( 1030): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1030): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1030): tsOffsetIs: Apps: 797896956314; DSPS: 26286616; Offset : -4318954440
,I/[SystemUI]TimeTickManager( 1461): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1461): called onTimeUpdated()
,I/[SystemUI]KeyguardIndicationController( 1461): called onTimeUpdated()
,I/[SystemUI]Clock( 1461): called onTimeUpdated()
I/LgeClockWidgetControlView( 1461): called onTimeUpdated()
,I/[SystemUI]DateView( 1461): called onTimeUpdated()
I/[SystemUI]DateView( 1461): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1461): handleTimeUpdate
D/sensors_hal_Time( 1030): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1030): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1030): tsOffsetIs: Apps: 817899070420; DSPS: 26942045; Offset : -4318946046,
,D/sensors_hal_Time( 1030): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1030): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1030): tsOffsetIs: Apps: 837901842704; DSPS: 27597496; Offset : -4318950837
,D/sensors_hal_Time( 1030): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1030): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1030): tsOffsetIs: Apps: 857903656864; DSPS: 28252915; Offset : -4318937031
,I/[SystemUI]TimeTickManager( 1461): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1461): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1461): called onTimeUpdated()
,I/[SystemUI]Clock( 1461): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1461): called onTimeUpdated()
,I/[SystemUI]DateView( 1461): called onTimeUpdated()
I/[SystemUI]DateView( 1461): called onTimeUpdated()
,D/KeyguardUpdateMonitor( 1461): handleTimeUpdate
D/sensors_hal_Time( 1030): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1030): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1030): tsOffsetIs: Apps: 877905658418; DSPS: 28908341; Offset : -4318949741
,D/sensors_hal_Time( 1030): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1030): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1030): tsOffsetIs: Apps: 897907688203; DSPS: 29563767; Offset : -4318934194
,I/[SystemUI]LGPowerUI( 1461): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1461): On Skip Timer : true
,D/WifiController( 1030): battery changed pluggedType: 2
,D/KeyguardUpdateMonitor( 1461): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 278
I/[SystemUI]LGPowerUI( 1461): onReceive = android.intent.action.BATTERY_CHANGED
D/LEDHandler( 1974): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1974): Battery Level Remaining: 100%
D/LEDHandler( 1974): Battery Temp: 278, mChargingStatus=5, mChargingStop=false
I/[SystemUI]BatterySaverHandler( 1461): onReceive = android.intent.action.BATTERY_CHANGED
D/LGDMClient( 3948): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.intent.action.BATTERY_CHANGED
,D/LGDMClient( 3948): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,D/sensors_hal_Time( 1030): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1030): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1030): tsOffsetIs: Apps: 917913327258; DSPS: 30219312; Offset : -4318940839
,I/[SystemUI]TimeTickManager( 1461): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1461): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1461): called onTimeUpdated()
,I/[SystemUI]Clock( 1461): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1461): called onTimeUpdated()
,I/[SystemUI]DateView( 1461): called onTimeUpdated()
,I/[SystemUI]DateView( 1461): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1461): handleTimeUpdate
,D/sensors_hal_Time( 1030): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1030): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1030): tsOffsetIs: Apps: 937915391677; DSPS: 30874740; Offset : -4318951695
,D/sensors_hal_Time( 1030): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1030): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1030): tsOffsetIs: Apps: 957917400888; DSPS: 31530166; Offset : -4318956643
,D/sensors_hal_Time( 1030): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1030): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1030): tsOffsetIs: Apps: 977919297286; DSPS: 32185588; Offset : -4318952205
,I/[SystemUI]TimeTickManager( 1461): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1461): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1461): called onTimeUpdated()
,I/[SystemUI]Clock( 1461): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1461): called onTimeUpdated()
,I/[SystemUI]DateView( 1461): called onTimeUpdated()
I/[SystemUI]DateView( 1461): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1461): handleTimeUpdate
,D/PowerManagerServiceEx( 1030): acquireWakeLockInternal: lock=241109302, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1030
,I/ActivityManager( 1030): Start proc com.lge.clock for broadcast com.lge.clock/.widget.DigitalAppWidgetProvider: pid=8023 uid=10010 gids={50010, 9997, 3003, 1028, 4002} abi=armeabi-v7a
,D/[Concierge]Service( 2629): onStartCommand(). Type : 9
,I/art     ( 1030): Explicit concurrent mark sweep GC freed 44723(2MB) AllocSpace objects, 0(0B) LOS objects, 33% free, 44MB/66MB, paused 2.389ms total 131.087ms
,I/DigitalAppWidgetProvider( 8023): onReceive: com.android.deskclock.ON_QUARTER_HOUR
V/DigitalAppWidgetProvider( 8023): startAlarmOnQuarterHour android.app.ReceiverRestrictedContext@3476ef0a
,I/ActivityManager( 1030): Killing 7131:com.uei.lg.quicksetsdk.maxq616/1000 (adj 15): empty #17
D/PowerManagerServiceEx( 1030): releaseWakeLockInternal: lock=241109302 [*alarm*], flags=0x0
I/QRemote ( 5992): [RemoteControlManager.java:195:onServiceDisconnected()] oooooo start
W/System.err( 5992): android.os.DeadObjectException
W/System.err( 5992): 	at android.os.BinderProxy.transactNative(Native Method)
W/System.err( 5992): 	at android.os.BinderProxy.transact(Binder.java:496)
W/System.err( 5992): 	at com.uei.control.IControl.unregisterCallback(IControl.java:502)
W/System.err( 5992): 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:199)
W/System.err( 5992): 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
W/System.err( 5992): 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
W/System.err( 5992): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 5992): 	at android.os.Handler.dispatchMessage(Handler.java:95)
,W/System.err( 5992): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 5992): 	at android.app.ActivityThread.main(ActivityThread.java:5274)
W/System.err( 5992): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 5992): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 5992): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
W/System.err( 5992): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
E/UEI.SmartControl( 5992): IControl.unregisterCallback error: android.os.DeadObjectException
W/System.err( 5992): android.os.DeadObjectException
W/System.err( 5992): 	at android.os.BinderProxy.transactNative(Native Method)
W/System.err( 5992): 	at android.os.BinderProxy.transact(Binder.java:496)
,W/System.err( 5992): 	at com.uei.control.IControl.unregisterSetupReadyCallback(IControl.java:818)
,W/System.err( 5992): 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:200)
W/System.err( 5992): 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
W/System.err( 5992): 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
W/System.err( 5992): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 5992): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 5992): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 5992): 	at android.app.ActivityThread.main(ActivityThread.java:5274)
W/System.err( 5992): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 5992): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 5992): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
W/System.err( 5992): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
E/UEI.SmartControl( 5992): IControl.unregisterSetupReadyCallback error: android.os.DeadObjectException
I/QRemote ( 5992): [RemoteControlManager.java:203:onServiceDisconnected()] oooooo Control unbind before rebinding.
E/lowmemorykiller(  276): Error opening /proc/7131/oom_score_adj; errno=2
,W/ActivityManager( 1030): Exception when unbinding service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service
W/ActivityManager( 1030): android.os.DeadObjectException
W/ActivityManager( 1030): 	at android.os.BinderProxy.transactNative(Native Method)
W/ActivityManager( 1030): 	at android.os.BinderProxy.transact(Binder.java:496)
W/ActivityManager( 1030): 	at android.app.ApplicationThreadProxy.scheduleUnbindService(ApplicationThreadNative.java:917)
W/ActivityManager( 1030): 	at com.android.server.am.ActiveServices.removeConnectionLocked(ActiveServices.java:1776)
W/ActivityManager( 1030): 	at com.android.server.am.ActiveServices.unbindServiceLocked(ActiveServices.java:901)
W/ActivityManager( 1030): 	at com.android.server.am.ActivityManagerService.unbindService(ActivityManagerService.java:15417)
W/ActivityManager( 1030): 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:963)
W/ActivityManager( 1030): 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:2560)
W/ActivityManager( 1030): 	at com.android.server.am.ActivityManagerServiceEx.onTransact(ActivityManagerServiceEx.java:421)
W/ActivityManager( 1030): 	at android.os.Binder.execTransact(Binder.java:446)
D/QRemote ( 5992): [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]10
I/QRemote ( 5992): [RemoteControlManager.java:157:onBindIRService()] oooooo bind
W/libprocessgroup( 1030): failed to open /acct/uid_1000/pid_7131/cgroup.procs: No such file or directory
,I/ActivityManager( 1030): Start proc com.uei.lg.quicksetsdk.maxq616 for service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service: pid=8059 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
D/QRemote ( 5992): [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
,D/UEI.SmartControl( 8059): Quickset Services start...
,I/UEI.SmartControl( 8059): Manufacture = LGE
D/UEI.SmartControl( 8059): Id = LGNevo
D/UEI.SmartControl( 8059): File observer start...
E/UEI.SmartControl( 8059): IR Port is disabled: false
D/UEI.SmartControl( 8059): Starting file observer...
D/UEI.SmartControl( 8059): Extracting JNI libs...
D/UEI.SmartControl( 8059): --- this system supports 32-bit or 64-bit only
D/UEI.SmartControl( 8059): --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
D/UEI.SmartControl( 8059): --- Checking lib: libqs_armeabi-v7a.zip
D/UEI.SmartControl( 8059): --- Extracting JNI libs: libqs_armeabi-v7a.zip
,I/UEI.SmartControl( 8059): --- Selecting new region: 6
,I/UEI.SmartControl( 8059): Model = LG-D855
D/UEI.SmartControl( 8059): QS Service created
I/UEI.SmartControl( 8059): Service initServices...
,D/UEI.SmartControl( 8059): QS start get config
D/UEI.SmartControl( 8059): Loading JNI Libs...
,I/UEI.SmartControl( 8059): Supports setup maps: true
,D/UEI.SmartControl( 8059): QS start statue = true Error code = 0
I/UEI.SmartControl( 8059): QS version = v2.7.10.1_RC1
I/UEI.SmartControl( 8059): QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
I/UEI.SmartControl( 8059): ### init IR Blaster...
,D/serial_port( 8059): Configuring serial port
E/UEI.SmartControl( 8059): UEIBLaster setting for 616
I/UEI.SmartControl( 8059): Setting serial record hearder size = 2
I/UEI.SmartControl( 8059): configuring settings for MAXQ616
I/UEI.SmartControl( 8059): Get version...
,D/UEI.SmartControl( 8059): serial port data available: 21
,D/UEI.SmartControl( 8059): MAXQ616 A2-X4 software.
,I/UEI.SmartControl( 8059): IR Blaster version: 256702256704300002
,I/UEI.SmartControl( 8059): QS saving settings...
D/UEI.SmartControl( 8059): IR Blaster version: 25672567
D/UEI.SmartControl( 8059): serial port data available: 4
,I/UEI.SmartControl( 8059): Device manager: loading config....
,D/UEI.SmartControl( 8059): ----------- loading internal config...
,W/ContextImpl( 8059): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
E/UEI.SmartControl( 8059): Services init done
D/UEI.SmartControl( 8059): QS Service init finished
D/UEI.SmartControl( 8059): QS Service version name: 2.1.91
D/UEI.SmartControl( 8059): QS Service version code: 201091
D/UEI.SmartControl( 8059): Service requested: Control
E/UEI.SmartControl( 8059): Loading SETTINGS...
,D/UEI.SmartControl( 8059): Request IControl service: devices are loaded...
I/QRemote ( 5992): [RemoteControlManager.java:183:onServiceConnected()] oooooo start
I/UEI.SmartControl( 8059): ------ IControl API: 11
I/ActivityManager( 1030): Killing 5992:com.lge.qremote/u0a112 (adj 15): empty #17
,I/UEI.SmartControl( 8059): Registering callback...
D/UEI.SmartControl( 8059): -- Open brand translation xml: brands_translations_ko
I/UEI.SmartControl( 8059): Notify AllClients services are ready: 0
,D/UEI.SmartControl( 8059): -----service ready thread exits
W/libprocessgroup( 1030): failed to open /acct/uid_10112/pid_5992/cgroup.procs: No such file or directory
D/UEI.SmartControl( 8059): Internal service binding...
,D/UEI.SmartControl( 8059): Internal timer expired: 1
,D/UEI.SmartControl( 8059): unbind internal service
D/UEI.SmartControl( 8059): Service.onUnbind: IControl
,D/UEI.SmartControl( 8059): Service.onDestroy
,D/UEI.SmartControl( 8059): Lock is in USE false
,D/UEI.SmartControl( 8059): unbind internal service
D/serial_port( 8059): close(fd = 25)
I/UEI.SmartControl( 8059): Serial port is closed.
,I/UEI.SmartControl( 8059): Serial port is closed.
I/UEI.SmartControl( 8059): Serial port is closed.
D/UEI.SmartControl( 8059): Blaster closed
D/UEI.SmartControl( 8059): Shut down QS...
D/UEI.SmartControl( 8059): Stopping QS lib
D/UEI.SmartControl( 8059): QS lib stop result = true
D/UEI.SmartControl( 8059): Stopped QS lib
D/UEI.SmartControl( 8059): Stopped file observer...
D/UEI.SmartControl( 8059): QS shutdown complete
D/sensors_hal_Time( 1030): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1030): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1030): tsOffsetIs: Apps: 997921587696; DSPS: 32841023; Offset : -4318950718
,D/sensors_hal_Time( 1030): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1030): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1030): tsOffsetIs: Apps: 1017923361438; DSPS: 33496441; Offset : -4318946917
,D/sensors_hal_Time( 1030): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1030): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1030): tsOffsetIs: Apps: 1037925376170; DSPS: 34151867; Offset : -4318946449
,I/[SystemUI]TimeTickManager( 1461): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1461): called onTimeUpdated()
,I/[SystemUI]KeyguardIndicationController( 1461): called onTimeUpdated()
I/[SystemUI]Clock( 1461): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1461): called onTimeUpdated()
I/[SystemUI]DateView( 1461): called onTimeUpdated()
I/[SystemUI]DateView( 1461): called onTimeUpdated()
,D/KeyguardUpdateMonitor( 1461): handleTimeUpdate
,D/sensors_hal_Time( 1030): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1030): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1030): tsOffsetIs: Apps: 1057927470746; DSPS: 34807296; Offset : -4318957482
,D/sensors_hal_Time( 1030): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1030): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1030): tsOffsetIs: Apps: 1077928901675; DSPS: 35462703; Offset : -4318961087
,D/sensors_hal_Time( 1030): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1030): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1030): tsOffsetIs: Apps: 1097930537241; DSPS: 36118116; Offset : -4318942588
,I/[SystemUI]TimeTickManager( 1461): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1461): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1461): called onTimeUpdated()
,I/[SystemUI]Clock( 1461): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1461): called onTimeUpdated()
,I/[SystemUI]DateView( 1461): called onTimeUpdated()
,I/[SystemUI]DateView( 1461): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1461): handleTimeUpdate
,D/sensors_hal_Time( 1030): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1030): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1030): tsOffsetIs: Apps: 1117932758588; DSPS: 36773549; Offset : -4318949234
,D/sensors_hal_Time( 1030): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1030): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1030): tsOffsetIs: Apps: 1137934602590; DSPS: 37428969; Offset : -4318936103
,D/sensors_hal_Time( 1030): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1030): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1030): tsOffsetIs: Apps: 1157936632895; DSPS: 38084396; Offset : -4318950632
,I/[SystemUI]TimeTickManager( 1461): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1461): called onTimeUpdated()
,I/[SystemUI]KeyguardIndicationController( 1461): called onTimeUpdated()
,I/[SystemUI]Clock( 1461): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1461): called onTimeUpdated()
I/[SystemUI]DateView( 1461): called onTimeUpdated()
I/[SystemUI]DateView( 1461): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1461): handleTimeUpdate
,D/sensors_hal_Time( 1030): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1030): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1030): tsOffsetIs: Apps: 1177938699658; DSPS: 38739824; Offset : -4318959117
,D/sensors_hal_Time( 1030): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1030): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1030): tsOffsetIs: Apps: 1197940880328; DSPS: 39395255; Offset : -4318945142
,D/sensors_hal_Time( 1030): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1030): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1030): tsOffsetIs: Apps: 1217942762976; DSPS: 40050677; Offset : -4318954480
,I/UsageStatsService( 1030): User[0] Flushing usage stats to disk
,I/[SystemUI]TimeTickManager( 1461): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1461): called onTimeUpdated()
,I/[SystemUI]KeyguardIndicationController( 1461): called onTimeUpdated()
,I/[SystemUI]Clock( 1461): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1461): called onTimeUpdated()
I/[SystemUI]DateView( 1461): called onTimeUpdated()
I/[SystemUI]DateView( 1461): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1461): handleTimeUpdate
,D/sensors_hal_Time( 1030): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1030): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1030): tsOffsetIs: Apps: 1237944631042; DSPS: 40706098; Offset : -4318948091
,D/sensors_hal_Time( 1030): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1030): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1030): tsOffsetIs: Apps: 1257946787075; DSPS: 41361529; Offset : -4318958858
,D/sensors_hal_Time( 1030): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1030): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1030): tsOffsetIs: Apps: 1277948887485; DSPS: 42016957; Offset : -4318933461
,I/[SystemUI]TimeTickManager( 1461): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1461): called onTimeUpdated()
,I/[SystemUI]KeyguardIndicationController( 1461): called onTimeUpdated()
,I/[SystemUI]Clock( 1461): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1461): called onTimeUpdated()
,I/[SystemUI]DateView( 1461): called onTimeUpdated()
,I/[SystemUI]DateView( 1461): called onTimeUpdated()
,D/KeyguardUpdateMonitor( 1461): handleTimeUpdate
,D/sensors_hal_Time( 1030): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1030): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1030): tsOffsetIs: Apps: 1297951000134; DSPS: 42672387; Offset : -4318957172
,I/[SystemUI]LGPowerUI( 1461): onReceive = com.lge.android.intent.action.BATTERYEX
,I/[SystemUI]LGPowerUI( 1461): On Skip Timer : true
,D/WifiController( 1030): battery changed pluggedType: 2
,D/LEDHandler( 1974): ACTION_BATTERY_CHANGED : plugged type=2
,D/LEDHandler( 1974): Battery Level Remaining: 100%
,D/LEDHandler( 1974): Battery Temp: 276, mChargingStatus=5, mChargingStop=false
D/KeyguardUpdateMonitor( 1461): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 276
I/[SystemUI]LGPowerUI( 1461): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]BatterySaverHandler( 1461): onReceive = android.intent.action.BATTERY_CHANGED
D/LGDMClient( 3948): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.intent.action.BATTERY_CHANGED
,D/LGDMClient( 3948): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
D/sensors_hal_Time( 1030): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1030): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1030): tsOffsetIs: Apps: 1317955823407; DSPS: 43327905; Offset : -4318955651
,TIME-OUT KILL (timeout was 1200000ms)
```
