#### Test 50650278b28a87a_thali03_LGE-LG-D855 Logs


```
--------- beginning of main
D/sensors_hal_Time( 1029): tsOffsetIs: Apps: 266308262630; DSPS: 8867121; Offset : -4305839422
,D/AndroidRuntime( 6012): 
D/AndroidRuntime( 6012): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 6012): CheckJNI is OFF
D/AndroidRuntime( 6012): Calling main entry com.android.commands.am.Am
--------- beginning of system
I/ActivityManager( 1029): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
V/SplitWindowPolicy( 1964): checkScreen => return. sourceIntent is null or not support SplitWindow component: ComponentInfo{co..../co.....MainActivity}
D/SplitInfo( 1029): new ActivitySplitInfo : ActivitySplitInfo [screenZone=0/ flag=0/ state=NATIVE]
D/ActivityManager( 1029): setTaskToReturnTo : TaskRecord{5362c35 #4 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
D/ActivityManager( 1029): setTaskToReturnTo : TaskRecord{5362c35 #4 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
D/WindowStateEx( 1029): AppWindowTokenEx init.. 
E/GBMv2   (  342): DFP En is all cleared set to be enabled
I/ActivityManager( 1029): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6033 uid=10311 gids={50311, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
D/AndroidRuntime( 6012): Shutting down VM
I/art     (  353): Explicit concurrent mark sweep GC freed 707(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 196us total 13.581ms
I/art     (  353): Explicit concurrent mark sweep GC freed 7(240B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 189us total 9.347ms
I/art     (  353): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 184us total 9.798ms
V/ActivityManager( 1029): Display changed displayId=0
D/DSDPConnection( 1871): Display #0 changed.
D/SplitWindowPolicy( 1964): updateActivityStateChanged: resumed=true, screenId=1, isScreenFull=true
D/SplitWindowPolicy( 1964): topRunningActivity=ActivityInfo{2e2acc5d co.....MainActivity}, taskId=4, activityType=0, bIsSplit=false
D/SplitWindowPolicy( 1964): updateActivityStateChanged: resumed=false, screenId=1, isScreenFull=true
D/SplitWindowPolicy( 1964): topRunningActivity=ActivityInfo{1f6b89d2 co.....MainActivity}, taskId=4, activityType=0, bIsSplit=false
D/ContextHelper( 6033): convertTheme. context->name=com.test.thalitest themeResourceId=16973833
I/WebViewFactory( 6033): Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,I/LibraryLoader( 6033): Loading: webviewchromium
,I/LibraryLoader( 6033): Time to load native libraries: 4 ms (timestamps 9699-9703)
I/LibraryLoader( 6033): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 6033): Binding Chromium to main looper Looper (main, tid 1) {3949484e}
I/LibraryLoader( 6033): Expected native library version number "",actual native library version number ""
I/chromium( 6033): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 6033): Initializing chromium process, renderers=0
W/art     ( 6033): Attempt to remove local handle scope entry from IRT, ignoring
W/chromium( 6033): [WARNING:dns_config_service_posix.cc(293)] Failed to read DnsConfig.
,V/AudioPolicyService(  327): registerClient() client 0xb1427da0, uid 10311
,W/chromium( 6033): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
I/chromium( 6033): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=32 off=46780 len=2953
I/chromium( 6033): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:33 off:229536 len:643667
D/BluetoothManagerService( 1029): Message: 20
D/BluetoothManagerService( 1029): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@29621f17:true
,D/BluetoothAdapter( 6033): 848280943: getState() :  mService = null. Returning STATE_OFF
,I/Adreno-EGL( 6033): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 6033): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 6033): Build Date: 12/12/14 금
I/Adreno-EGL( 6033): Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
I/Adreno-EGL( 6033): Remote Branch: 
I/Adreno-EGL( 6033): Local Patches: 
I/Adreno-EGL( 6033): Reconstruct Branch: 
,W/chromium( 6033): [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
,W/chromium( 6033): [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
W/art     ( 6033): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 6033): onDetachedFromWindow called when already detached. Ignoring
D/SystemWebViewEngine( 6033): CordovaWebView is running on device made by: LGE
,W/art     ( 6033): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 6033): Attempt to remove local handle scope entry from IRT, ignoring
,D/LgDataFeature( 6033): LgDataFeature() Constructor: none
D/LgDataFeature( 6033): LgDataFeature() Constructor Done, null
,W/ActivityManager( 1029): Activity pause timeout for ActivityRecord{1f8728ca u0 com.test.thalitest/.MainActivity t4}
,I/art     ( 1029): Explicit concurrent mark sweep GC freed 25629(1163KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 43MB/65MB, paused 2.299ms total 145.881ms
,D/OpenGLRenderer( 6033): Render dirty regions requested: true
I/OpenGLRenderer( 6033): Initialized EGL, version 1.4
D/OpenGLRenderer( 6033): Enabling debug mode 0
D/Atlas   ( 6033): Validating map...
,D/SplitWindow( 1029): check instance of lgWin Window{2c60a059 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,I/SystemUI[Framework]( 1029): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x0, pkg=com.android.systemui
,D/PhoneStatusBar( 1462): setSystemUiVisibility vis=0 mask=ffffffff oldVal=8000 newVal=0 diff=8000
W/PhoneWindowManagerEx( 1029): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx( 1029): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx( 1029): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework]( 1029): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@259acbf0,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework]( 1029): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
I/[SystemUI]NavigationThemeResource( 1462): NavigationKey Color is changed(WHITE_WITH_SHADOW -> BLACK)
I/[SystemUI]NavigationThemeResource( 1462):  BarMode=0, Theme=WHITE, LightBackground=false (Transparent)
I/[SystemUI]NavigationThemeResource( 1462): , Keyguard show=false, IME shown=false, Panel expanded=false
I/Timeline( 6033): Timeline: Activity_idle id: android.os.BinderProxy@110e05f time:280223
,I/ActivityManager( 1029): Displayed com.test.thalitest/.MainActivity: +694ms (total +789ms)
,I/Timeline( 1029): Timeline: Activity_windows_visible id: ActivityRecord{1f8728ca u0 com.test.thalitest/.MainActivity t4} time:280246
D/JsMessageQueue( 6033): Set native->JS mode to OnlineEventsBridgeMode
,I/chromium( 6033): [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
I/chromium( 6033): 
,I/chromium( 6033): [INFO:SkFontConfigInterface_android.cpp(247)] ---- failed to open </system/fonts/CutiveMono.ttf> as a font
I/chromium( 6033): 
,D/jxcore_app_log( 6033): JniHelper::setJavaVM(0xb487c280), pthread_self() = -1434888448
,D/JX-Cordova( 6033): jxcore cordova android initializing
E/GBMv2   (  342): DFP En is all cleared set to be enabled
E/GBMv2   (  342): Set value is all cleared set the max
I/GBMv2   (  342): DFP Enabled. Ignore VFP set
,W/jxcore-log( 6033): Initializing JXcore engine
W/jxcore-log( 6033): JXcore engine is ready
,W/jxcore-log( 6033): Starting JXcore engine
I/art     ( 6033): Background sticky concurrent mark sweep GC freed 123920(12MB) AllocSpace objects, 23(7MB) LOS objects, 28% free, 39MB/55MB, paused 950us total 103.017ms
,W/.test.thalitest( 6033): type=1400 audit(0.0:148): avc: denied { ioctl } for path="socket:[7522]" dev="sockfs" ino=7522 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
,W/.test.thalitest( 6033): type=1400 audit(0.0:149): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3222 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
W/.test.thalitest( 6033): type=1400 audit(0.0:150): avc: denied { ioctl } for path="socket:[10390]" dev="sockfs" ino=10390 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
W/.test.thalitest( 6033): type=1400 audit(0.0:151): avc: denied { ioctl } for path="/cust" dev="mmcblk0p42" ino=2 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=dir
W/.test.thalitest( 6033): type=1400 audit(0.0:152): avc: denied { ioctl } for path="socket:[29399]" dev="sockfs" ino=29399 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
W/jxcore-log( 6033): Platform android
W/jxcore-log( 6033): 
W/jxcore-log( 6033): Process ARCH arm
W/jxcore-log( 6033): 
,I/jxcore-log( 6033): JXcore Cordova bridge is ready!
I/jxcore-log( 6033): 
W/jxcore-log( 6033): JXcore engine is started
,I/jxcore-log( 6033): Toggling radios to true
I/jxcore-log( 6033): 
,D/BluetoothManagerService( 1029): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1029): enable():  mBluetooth =null mBinding = false
,D/LocationManagerService( 1029): getAllProviders()=[passive, gps, network]
D/BluetoothManagerService( 1029): Message: 1
D/Ulp_jni ( 1029): JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
D/Ulp_jni ( 1029): JNI:system_update. Event-4
D/BluetoothManagerService( 1029): MESSAGE_ENABLE: mBluetooth = null
D/WifiService( 1029): New client listening to asynchronous messages
I/ActivityManager( 1029): Start proc com.android.bluetooth for service com.android.bluetooth/.btservice.AdapterService: pid=6103 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008, 4002, 1023} abi=armeabi-v7a
D/WifiServiceImplEx( 1029): setWifiEnabled: true pid=6033, uid=10311, package= com.test.thalitest, App Lable : ThaliTest
,D/WifiService( 1029): setWifiEnabled: true pid=6033, uid=10311
E/WifiService( 1029): Invoking mWifiStateMachine.setWifiEnabled
D/LocationManagerService( 1029): getAllProviders()=[passive, gps, network]
D/WifiServiceImplEx( 1029): disconnect pid=6033, uid=10311, packageName=com.test.thalitest
D/Ulp_jni ( 1029): JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 1,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
,D/Ulp_jni ( 1029): JNI:system_update. Event-4
E/WifiStateMachine( 1029):  InitialState CMD_DISCONNECT 0 0
E/WifiStateMachine( 1029):  DefaultState CMD_DISCONNECT 0 0
D/WifiServiceImplEx( 1029): reconnect pid=6033, uid=10311, packageName=com.test.thalitest
I/jxcore-log( 6033): Radios toggled
I/jxcore-log( 6033): 
D/BluetoothManagerService( 1029): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
E/WifiStateMachine( 1029):  InitialState CMD_START_SUPPLICANT 0 0
I/LGFTMITEM( 1029): [GET_FTM][id=6], offset=12288
I/jxcore-log( 6033): Got Device Bluetooth address: 58:3F:54:73:64:C0
I/jxcore-log( 6033): 
I/jxcore-log( 6033): Perf Test app loaded loaded
I/jxcore-log( 6033): 
E/WifiUtil( 1029): wfc_util_ffile_check_copy(): pid[1029] pDestFName[/data/misc/wifi/WCNSS_qcom_cfg.ini] pSourceFName[/system/etc/wifi/WCNSS_qcom_cfg.ini]
E/WifiUtil( 1029): wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
E/WifiUtil( 1029): wfc_util_ffile_check_copy(): pid[1029] pDestFName[/data/misc/wifi/WCNSS_qcom_wlan_nv.bin] pSourceFName[/system/etc/wifi/WCNSS_qcom_wlan_nv.bin]
E/WifiUtil( 1029): wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
I/WifiUtil( 1029): Intf0MacAddress=C49A027B60AC
E/WifiHW  ( 1029): unknown target_country: EU , set to default
E/WifiHW  ( 1029): [wifi_ensure_config_files] default country1 = GB
E/WifiHW  ( 1029): [wifi_ensure_config_files] default country2 = GB
I/WifiUtil( 1029): gEnableBmps=1
,I/jxcore-log( 6033): check test folder
I/jxcore-log( 6033): 
,I/jxcore-log( 6033): found test : ./testFindPeers.js
I/jxcore-log( 6033): 
W/ResourcesManager( 6103): Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
W/ResourcesManager( 6103): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 6103): Asset path '/system/framework/com.qcom.bluetooth.jar' does not exist or contains no resources.
W/ResourcesManager( 6103): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,I/jxcore-log( 6033): found test : ./testSendData.js
I/jxcore-log( 6033): 
,D/BluetoothAdapterApp( 6103): Loading JNI Library
,D/Tethering( 1029): sendTetherStateChangedBroadcast 1, 0, 0
,D/SoftapController(  323): Softap fwReload - Ok
D/libc-netbsd(  323): default dns: query_ipv6=0, query_ipv4=0
D/CommandListener(  323): Setting iface cfg
D/CommandListener(  323): Trying to bring down wlan0
D/CommandListener(  323): Clearing all IP addresses on wlan0
,I/Choreographer( 6033): Skipped 78 frames!  The application may be doing too much work on its main thread.
D/Tethering( 1029): InitialState.processMessage what=4
I/ActivityManager( 1029): Start proc com.android.settings for broadcast com.android.settings/.deviceinfo.UsbSettingsReceiver: pid=6141 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
D/Tethering( 1029): sendTetherStateChangedBroadcast 0, 0, 0
E/WifiHW  ( 1029): Cannot open "/system/etc/wifi/autojoinconfig.txt": No such file or directory
D/DSQN    ( 1029): DNSproblemNotiEnabled is disabled ignore DNS fail CB
W/wpa_supplicant( 6150): type=1400 audit(0.0:153): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
W/wpa_supplicant( 6150): type=1400 audit(0.0:154): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,E/WifiStateMachine( 1029): Couldn't get getWiFiOffloadingIface : 
E/WifiStateMachine( 1029): useWiFiOffloading() : false
E/WifiStateMachine( 1029): CONFIG_LGE_WLAN_PATH : true
V/WfdStateTracker( 1964): WfdStateTracker handleDirectStateChangedEvent: 1
D/StatusBar.NetworkController( 1462): refreshViews: Data not connected!! Set no data type icon / Roaming
I/WifiServerServiceExt( 1029): WIFI_STATE_CHANGED_ACTION [2]
D/WifiMonitor( 1029): startMonitoring(wlan0) with mConnected = false
D/WifiMonitor( 1029): connecting to supplicant
I/chromium( 6033): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,I/wpa_supplicant( 6150): Successfully initialized wpa_supplicant
I/chromium( 6033): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
D/BluetoothAdapterApp( 6103): REFCOUNT: Constructed com.android.bluetooth.btservice.AdapterApp@a204e02 Instance Count = 1
,I/wpa_supplicant( 6150): rfkill: Cannot open RFKILL control device
D/BluetoothAdapterApp( 6103): onCreate
I/wpa_supplicant( 6150): [LGE_PATCH] unset P2P_CAPABLE to ifname wlan0
D/ProfileConfigQcom( 6103): [BTUI] HeadsetService is supported
D/ProfileConfigQcom( 6103): Adding HeadsetService
D/ProfileConfigQcom( 6103): [BTUI] A2dpService is supported
D/ProfileConfigQcom( 6103): Adding A2dpService
D/ProfileConfigQcom( 6103): [BTUI] HidService is supported
D/ProfileConfigQcom( 6103): Adding HidService
D/ProfileConfigQcom( 6103): [BTUI] HealthService is supported
D/ProfileConfigQcom( 6103): Adding HealthService
D/LGBluetoothFeatureConfig( 6103): isSupportPan() :  mTargetOp=OPEN
,D/ProfileConfigQcom( 6103): [BTUI] PanService is supported
D/ProfileConfigQcom( 6103): Adding PanService
D/ProfileConfigQcom( 6103): [BTUI] GattService is supported
D/ProfileConfigQcom( 6103): Adding GattService
D/ProfileConfigQcom( 6103): [BTUI] BluetoothMapService is supported
D/ProfileConfigQcom( 6103): Adding BluetoothMapService
D/ProfileConfigQcom( 6103): [BTUI] HeadsetClientService is NOT supported
W/ResourcesManager( 6141): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6141): Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
W/ResourcesManager( 6141): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 6141): Asset path '/system/framework/com.lge.bluetooth.jar' does not exist or contains no resources.
W/ResourcesManager( 6141): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
W/ResourcesManager( 6141): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
D/BluetoothManagerService( 1029): Message: 20
D/BluetoothManagerService( 1029): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@159d6dd0:true
,D/BluetoothAdapterState( 6103): make
I/LGFMServiceAdapter( 6103): [FM] LGFMServiceAdapter : create
I/bluedroid-qcom( 6103): init
I/BluetoothAdapterState( 6103): Entering OffState
I/bte_conf( 6103): bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
I/bte_conf( 6103): bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
E/bt_osi_config( 6103): config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
I/bte_conf( 6103): bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
D/BTIF_CORE( 6103): [BTUI] lge_load_bluetooth_address
I/bluedroid-qcom( 6103): get_profile_interface socket
I/bluedroid-qcom( 6103): get_profile_interface map_client
I/GKI_LINUX( 6103): gki_task_entry task_id=1 [BTIF] starting
W/bdaddr_loader( 6164): type=1400 audit(0.0:155): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
W/bdaddr_loader( 6164): type=1400 audit(0.0:156): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,I/wpa_supplicant( 6150): rfkill: Cannot open RFKILL control device
D/BluetoothManagerService( 1029): BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
D/BluetoothManagerService( 1029): Message: 40
D/BluetoothManagerService( 1029): MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
D/BluetoothAdapterProperties( 6103): Address is:58:3F:54:73:64:C0
D/lge_bdaddr_loader( 6164): [BTUI] bdaddr_loader ::: START
D/lge_bdaddr_loader( 6164): [BTUI] bluetooth_load_bdaddress
I/LGFTMITEM( 6164): [GET_FTM][id=8], offset=16384
D/BluetoothAdapterProperties( 6103): Name is: G3-1
D/lge_bdaddr_loader( 6164): [BTUI] bdaddr to set in property : 58:3F:54:73:64:C0
D/BluetoothManagerService( 1029): Bluetooth Adapter name changed to G3-1
D/BluetoothManagerService( 1029): Stored Bluetooth name: G3-1
I/bluedroid-qcom( 6103): config_hci_snoop_log
D/BluetoothManagerService( 1029): Calling onBluetoothServiceUp callbacks
D/BluetoothManagerService( 1029): Broadcasting onBluetoothServiceUp() to 7 receivers.
V/LGMDMManagerInternal( 6103): Create singleton instance
,E/lge_bdaddr_loader( 6164): [BTUI] bluetooth_load_bdaddress : OK => 58:3F:54:73:64:C0
D/lge_bdaddr_loader( 6164): [BTUI] bdaddr_loader ::: END
D/UsbSettingsReceiver( 6141): [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
D/UsbSettingsReceiver( 6141): [AUTORUN] sys.usb.config = ptp_only,adb
,D/UsbSettingsReceiver( 6141): [AUTORUN] sys.usb.state = ptp_only,adb
D/UsbSettingsReceiver( 6141): [AUTORUN] persist.sys.usb.config = ptp_only,adb
D/UsbSettingsReceiver( 6141): [AUTORUN] onReceive() : app userid = 0, current userid = 0
D/BluetoothAdapterState( 6103): CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
D/BluetoothAdapterProperties( 6103): Setting state to 11
I/BluetoothAdapterState( 6103): Bluetooth adapter state changed: 10-> 11
D/BluetoothManagerService( 1029): Message: 60
D/BluetoothManagerService( 1029): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
D/BluetoothManagerService( 1029): Bluetooth State Change Intent: 10 -> 11
I/LGBluetoothServiceJni( 6103): classInitNative: succeeds
I/[SystemUI]BluetoothHandler( 1462): Receive : BluetoothAdapter.ACTION_STATE_CHANGED
D/LGBluetoothAPIService( 1964): [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
D/UsbSettingsControl( 6141): [AUTORUN] getUsbConnected() : connected=true
D/UsbSettingsReceiver( 6141): [AUTORUN] onReceive() : availableList=[wlan0]
D/UsbSettingsReceiver( 6141): [AUTORUN] onReceive() : activeList=[]
D/UsbSettingsReceiver( 6141): [AUTORUN] onReceive() : errorList=[]
D/UsbSettingsControl( 6141): [AUTORUN] isAutorunTimer() : mAutorunChanging=false
D/UsbSettingsReceiver( 6141): [AUTORUN] onReceive() : TetherState Changed=wlan0
D/UsbSettingsControl( 6141): [AUTORUN] setTetherStatus() : status=false
,I/wpa_supplicant( 6150): [LGE_WLAN_PATCH]P2P 5GHz support level:2(0:no 1:gconly 2:gconly_UNII1 3:full)
I/ActivityManager( 1029): Killing 5393:com.lge.appbox.client/u0a11 (adj 15): empty #17
D/BluetoothBondStateMachine( 6103): make
D/BluetoothAdapterService( 6103): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@7038f05
D/LGBluetoothServiceAdapter( 6103): [BTUI] check adapter is available - false.
D/BluetoothAdapterService( 6103): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@7038f05
D/LGBluetoothServiceAdapter( 6103): [BTUI] check adapter is available - true : set adapter available.
D/LGBluetoothSettingsDBObserver( 6103): [BTUI] register observer for LG device name DB
I/BluetoothBondStateMachine( 6103): StableState(): Entering Off State
I/wpa_supplicant( 6150): wlan0: CTRL-EVENT-SCAN-STARTED 
I/wpa_supplicant( 6150): p2p0: CTRL-EVENT-AVOID-FREQ ranges=
,E/BluetoothAdapterService( 6103): File transfer profiles supported!!
E/WifiStateMachine( 1029):  SupplicantStartingState CMD_SET_OPERATIONAL_MODE 1 0
D/WifiMonitor( 1029): Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
E/WifiStateMachine( 1029):  SupplicantStartingState CMD_START_DRIVER 0 0
E/WifiMonitor( 1029): WifiMonitor:wlan0 cnt=0 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1029): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1029): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
E/WifiStateMachine( 1029):  SupplicantStartingState CMD_SET_HIGH_PERF_MODE 0 0
D/WifiMonitor( 1029): Event [IFNAME=p2p0 CTRL-EVENT-AVOID-FREQ ranges=]
D/WifiMonitor( 1029): Dropping event because (p2p0) is stopped
E/WifiStateMachine( 1029):  DefaultState CMD_SET_HIGH_PERF_MODE 0 0
E/WifiStateMachine( 1029):  SupplicantStartingState CMD_RECONNECT 0 0
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
V/BluetoothPbapReceiver( 6103): PbapReceiver onReceive 
,V/BluetoothPbapReceiver( 6103): ***********action = android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothPbapReceiver( 6103): ***********state = 11
W/libprocessgroup( 1029): failed to open /acct/uid_10011/pid_5393/cgroup.procs: No such file or directory
D/BluetoothHeadset( 1029): Proxy object connected
D/HeadsetService( 6103): Received start request. Starting profile...
D/BluetoothHeadset( 1871): Proxy object connected
D/BluetoothHeadset( 1871): Proxy object connected
D/BluetoothHeadset( 1871): Proxy object connected
I/LGBluetoothHeadsetServiceJni( 6103): classInitNative: succeeds
,E/BluetoothAdapterService( 6103): File transfer profiles supported!!
D/LGBluetoothHfpAdapter( 6103): Version 1.6
,E/WifiStateMachine( 1029): Couldn't get getWiFiOffloadingIface : 
E/WifiStateMachine( 1029): useWiFiOffloading() : false
E/WifiStateMachine( 1029): CONFIG_LGE_WLAN_PATH : true
,D/UsbSettingsReceiver( 6141): [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
D/UsbSettingsReceiver( 6141): [AUTORUN] sys.usb.config = ptp_only,adb
D/UsbSettingsReceiver( 6141): [AUTORUN] sys.usb.state = ptp_only,adb
D/UsbSettingsReceiver( 6141): [AUTORUN] persist.sys.usb.config = ptp_only,adb
D/LGBluetoothFeatureConfig( 6103): isPrivacyLogsEnabled : true
I/BluetoothHeadsetServiceJni( 6103): classInitNative: succeeds
D/HeadsetStateMachine( 6103): make
D/LgDataFeature( 6103): LgDataFeature() Constructor: none
D/LgDataFeature( 6103): LgDataFeature() Constructor Done, null
,I/ActivityManager( 1029): Start proc com.lge.lifetracker for broadcast com.lge.lifetracker/.receiver.HealthDeviceReceiver: pid=6169 uid=10037 gids={50037, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
,D/WifiNative-wlan0( 1029): doBoolean: SET update_config 1
W/Settings( 1029): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1029): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/StatusBar.NetworkController( 1462): refreshViews: Data not connected!! Set no data type icon / Roaming
D/WifiNative-wlan0( 1029): SET update_config 1: returned true
D/WifiConfigStore( 1029): Loading config and enabling all networks 
D/WifiNative-wlan0( 1029): doString: [LIST_NETWORKS]
D/WfdService( 1964): Waiting for WifiP2p enabling
D/WifiNative-wlan0( 1029):    returned network id / ssid / bssid / flags 0	NG700	any	
D/HeadsetStateMachine( 6103): max_hf_connections = 1
I/bluedroid-qcom( 6103): get_profile_interface handsfree
I/WifiServerServiceExt( 1029): WIFI_STATE_CHANGED_ACTION [3]
I/WifiServerServiceExt( 1029): batteryPsActivateMsgHandler : state:0 event:3
E/WifiConfigStore( 1029): readNetworkVariablesFromSupplicantFile key=psk
,V/ToneGenerator( 6103): ToneGenerator constructor: streamType=8, volume=1.000000
V/AudioPolicyService(  327): registerClient() client 0xb152b220, uid 1002
V/AudioPolicyManager(  327): getOutput() device 2, stream 8, samplingRate 0, format 0, channelMask 3, flags 0
V/AudioPolicyManagerEx(  327): AudioPolicyManagerEx: getOutputForDevice
V/AudioPolicyManagerEx(  327): getOutput() returns output 2
V/AudioSystem( 6103): getOutputSamplingRate() no output descriptor for output 2 in gOutputs
V/AudioFlinger(  327): registerClient() client 0xb1244520, pid 6103
D/UsbSettingsReceiver( 6141): [AUTORUN] onReceive() : app userid = 0, current userid = 0
V/AudioSystem(  327): ioConfigChanged() event 0, ioHandle 2
V/AudioSystem(  327): ioConfigChanged() opening already existing output! 2
E/BluetoothAdapterService( 6103): File transfer profiles supported!!
V/AudioSystem( 1029): ioConfigChanged() event 0, ioHandle 2
V/AudioSystem( 1029): ioConfigChanged() opening already existing output! 2
V/AudioSystem( 6103): ioConfigChanged() event 0, ioHandle 2
V/AudioSystem( 6103): ioConfigChanged() new output samplingRate 48000, format 0x5 channel mask 0x3 frameCount 960 latency 50
V/AudioSystem( 1462): ioConfigChanged() event 0, ioHandle 2
V/AudioSystem( 1462): ioConfigChanged() opening already existing output! 2
V/AudioSystem( 1871): ioConfigChanged() event 0, ioHandle 2
V/ToneGenerator( 6103): Create Track: 0xb4928a80
V/AudioSystem( 1871): ioConfigChanged() opening already existing output! 2
V/AudioTrack( 6103): set(): streamType 8, sampleRate 0, format 0x1, channelMask 0x1, frameCount 0, flags #4, notificationFrames 0, sessionId 0, transferType 1
V/AudioTrack( 6103): set() streamType 8, sampleRate 0, format 1, frameCount 0, flags 0004
V/AudioPolicyManager(  327): getOutputForAttr() usage=3, content=4, tag= flags=00000000
V/AudioPolicyManager(  327): getOutputForAttr() device 2, samplingRate 0, format 0, channelMask 3, flags 0
V/AudioPolicyManagerEx(  327): AudioPolicyManagerEx: getOutputForDevice
,V/AudioPolicyManagerEx(  327): getOutput() returns output 2
V/AudioSystem(  327): ioConfigChanged() event 0, ioHandle 4
V/AudioSystem(  327): ioConfigChanged() opening already existing output! 4
V/AudioSystem( 1029): ioConfigChanged() event 0, ioHandle 4
V/AudioSystem( 1029): ioConfigChanged() opening already existing output! 4
I/AudioFlinger(  327): isAudioPlaybackHookOn() false
V/AudioSystem( 6103): ioConfigChanged() event 0, ioHandle 4
V/AudioSystem( 6103): ioConfigChanged() new output samplingRate 48000, format 0x1 channel mask 0x3 frameCount 960 latency 80
V/AudioPolicyManager(  327): getOutputForAttr() usage=3, content=4, tag= flags=00000000
V/AudioPolicyManager(  327): getOutputForAttr() device 2, samplingRate 48000, format 1, channelMask 1, flags 4
V/AudioPolicyManagerEx(  327): AudioPolicyManagerEx: getOutputForDevice
V/AudioSystem( 1871): ioConfigChanged() event 0, ioHandle 4
V/AudioPolicyManagerEx(  327): getOutput() returns output 2
V/AudioSystem( 1871): ioConfigChanged() opening already existing output! 4
V/AudioSystem( 6103): getLatency() output 2, latency 50
V/AudioSystem( 6103): getFrameCount() output 2, frameCount 960
V/AudioTrack( 6103): createTrack_l() output 2 afLatency 50
V/AudioSystem( 3187): ioConfigChanged() event 0, ioHandle 2
V/AudioFlinger(  327): [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
V/AudioSystem( 3187): ioConfigChanged() opening already existing output! 2
V/AudioFlinger(  327): [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
V/AudioFlinger(  327): [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
V/AudioFlinger(  327): [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
V/AudioFlinger(  327): createTrack() lSessionId: 16
V/AudioSystem( 3187): ioConfigChanged() event 0, ioHandle 4
V/AudioSystem( 3187): ioConfigChanged() opening already existing output! 4
D/UsbSettingsControl( 6141): [AUTORUN] getUsbConnected() : connected=true
D/UsbSettingsReceiver( 6141): [AUTORUN] onReceive() : availableList=[]
D/UsbSettingsReceiver( 6141): [AUTORUN] onReceive() : activeList=[]
D/UsbSettingsReceiver( 6141): [AUTORUN] onReceive() : errorList=[]
V/AudioTrack( 6103): AUDIO_OUTPUT_FLAG_FAST successful; frameCount 480
D/UsbSettingsControl( 6141): [AUTORUN] isAutorunTimer() : mAutorunChanging=false
V/AudioSystem( 1462): ioConfigChanged() event 0, ioHandle 4
V/AudioSystem( 1462): ioConfigChanged() opening already existing output! 4
V/AudioFlinger(  327): acquiring 16 from 6103, for 6103
V/AudioFlinger(  327):  added new entry for 16
V/ToneGenerator( 6103): ToneGenerator INIT OK, time: 284076
D/BluetoothAdapterService( 6103): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@7038f05
E/WifiConfigStore( 1029): readNetworkVariableFromSupplicantFile ssid=["NG700"] key=psk
E/WifiConfigStore( 1029): Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
D/HeadsetStateMachine( 6103): Enter Disconnected: -2, size: 0
D/HeadsetPhoneState( 6103): [BTUI] listenForPhoneState : start = false
D/LGBluetoothHfpManager( 6103): [BTUI] listenForMultiSimPhoneState : start = false
D/HeadsetStateMachine( 6103): [BTUI] change sampling rate to 8000 when device is disconnected
V/AudioFlinger(  327): setParameters(): io 0, keyvalue bt_samplerate=8000, calling pid 6103
D/UsbSettingsControl( 6141): [AUTORUN] setTetherStatus() : status=false
D/audio_hw_primary(  327): adev_set_parameters: enter: bt_samplerate=8000
V/voice   (  327): voice_set_parameters: enter: bt_samplerate=8000
V/compress_voip(  327): voice_extn_compress_voip_set_parameters: enter: bt_samplerate=8000
V/compress_voip(  327): voice_extn_compress_voip_set_parameters: exit
V/voice   (  327): voice_set_parameters: exit with code(0)
V/msm8974_platform_lge(  327): LGE_platform_set_parameters: enter: bt_samplerate=8000
V/msm8974_platform(  327): platform_set_parameters: enter: bt_samplerate=8000
V/msm8974_platform(  327): platform_set_parameters: exit with code(0)
V/lge_audio_loopback(  327): lge_platform_set_loopback_parameters: enter: 
V/audio_hw_primary(  327): adev_set_parameters: exit with code(0)
E/audio_a2dp_hw(  327): adev_set_parameters: ERROR: set param called even when stream out is null
V/ToneGenerator( 6103): ToneGenerator destructor
V/ToneGenerator( 6103): stopTone
V/ToneGenerator( 6103): Delete Track: 0xb4928a80
D/BluetoothAdapterService( 6103): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@7038f05
D/WifiStateMachine( 1029): enableVerboseLogging : level 2
D/WifiNative-wlan0( 1029): doBoolean: SET device_name g3_global_com
D/WifiNative-wlan0( 1029): SET device_name g3_global_com: returned true
D/WifiNative-wlan0( 1029): doBoolean: SET manufacturer LGE
V/AudioTrack( 6103): ~AudioTrack, releasing session id from 6103 on behalf of 6103
V/AudioFlinger(  327): releasing 16 from 6103 for 6103
V/AudioFlinger(  327):  decremented refcount to 0
V/AudioFlinger(  327): purging stale effects
E/BluetoothAdapterService( 6103): File transfer profiles supported!!
V/AudioPolicyService(  327): AudioCommandThread() adding release output 2
D/WifiNative-wlan0( 1029): SET manufacturer LGE: returned true
V/AudioPolicyService(  327): inserting command: 6 at index 0, num commands 0
D/WifiNative-wlan0( 1029): doBoolean: SET model_name LG-D855
V/AudioPolicyService(  327): AudioCommandThread() waking up
V/AudioPolicyService(  327): AudioCommandThread() processing release output 2
V/AudioPolicyManager(  327): releaseOutput() 2
V/AudioPolicyService(  327): AudioCommandThread() going to sleep
D/WifiNative-wlan0( 1029): SET model_name LG-D855: returned true
V/AudioFlinger(  327): PlaybackThread::Track destructor
V/AudioFlinger(  327): removeClient_l() pid 6103, calling pid 327
D/WifiNative-wlan0( 1029): doBoolean: SET model_number LG-D855
,D/WifiNative-wlan0( 1029): SET model_number LG-D855: returned true
D/WifiNative-wlan0( 1029): doBoolean: SET serial_number LGD8553bed2d08
D/WifiNative-wlan0( 1029): SET serial_number LGD8553bed2d08: returned true
D/WifiNative-wlan0( 1029): doBoolean: SET config_methods physical_display virtual_push_button
D/WifiNative-wlan0( 1029): SET config_methods physical_display virtual_push_button: returned true
D/WifiNative-wlan0( 1029): doBoolean: SET device_type 10-0050F204-5
D/WifiNative-wlan0( 1029): SET device_type 10-0050F204-5: returned true
I/ActivityManager( 1029): Start proc com.lge.formmanager for broadcast com.lge.formmanager/.FormServiceReceiver: pid=6187 uid=10026 gids={50026, 9997, 3003, 1028} abi=armeabi-v7a
D/BluetoothA2dp( 1029): Proxy object connected
D/WifiStateMachine( 1029): Setting OUI to DA-A1-19
D/WifiNative-wlan0( 1029): doBoolean: SCAN_INTERVAL 120
D/WifiNative-wlan0( 1029): SCAN_INTERVAL 120: returned true
D/WifiNative-HAL( 1029): Setting external_sim to 1
D/WifiNative-wlan0( 1029): doBoolean: SET external_sim 1
D/WifiNative-wlan0( 1029): SET external_sim 1: returned true
I/WifiNative-HAL( 1029): startHal
E/wifi    ( 1029): getStaticLongField sWifiHalHandle 0x989338dc
E/WifiHAL ( 1029): Could not connect handle
D/wifi    ( 1029): halHandle = 0x0, mVM = 0xb487c280, mCls = 0x201f76
I/WifiNative-HAL( 1029): Could not start hal
D/WifiStateMachine( 1029): Setting OUI to DA-A1-19
I/WifiNative-HAL( 1029): startHal
E/wifi    ( 1029): getStaticLongField sWifiHalHandle 0x9893385c
E/WifiHAL ( 1029): Could not connect handle
D/wifi    ( 1029): halHandle = 0x0, mVM = 0xb487c280, mCls = 0x701f6a
I/WifiNative-HAL( 1029): Could not start hal
D/WifiNative-wlan0( 1029): doBoolean: STA_AUTOCONNECT 1
D/WifiNative-wlan0( 1029): STA_AUTOCONNECT 1: returned true
D/WifiNative-wlan0( 1029): doBoolean: DRIVER BTCOEXSCAN-STOP
I/wpa_supplicant( 6150): wpa_driver_nl80211_ext_driver_cmd BTCOEXSCAN-STOP
D/WifiNative-wlan0( 1029): DRIVER BTCOEXSCAN-STOP: returned true
D/A2dpService( 6103): Received start request. Starting profile...
I/BluetoothAvrcpServiceJni( 6103): classInitNative: succeeds
V/Avrcp   ( 6103): make
D/Avrcp   ( 6103): [BTUI] Use Native AVRCP : init jni
I/bluedroid-qcom( 6103): get_profile_interface avrcp
W/Settings( 5910): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WfdsService( 1964): Supplicant Connection state is changed : true
D/WfdsService( 1964): DefaultState - WIFI_SUPPLICANT_CONNECTED
D/WfdsService( 1964): Set the WFDS Monitor: true
D/WifiNative-wlan0( 1029): doBoolean: DRIVER RXFILTER-STOP
I/wpa_supplicant( 6150): wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
,D/WifiHS20( 1029): hidePasspointNotification off =false
E/BluetoothAdapterService( 6103): File transfer profiles supported!!
W/Settings( 1029): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiNative-wlan0( 1029): DRIVER RXFILTER-STOP: returned true
W/Settings( 1029): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiNative-wlan0( 1029): doBoolean: DRIVER RXFILTER-REMOVE 3
D/WifiOffDelayIfNotUsed( 1029): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
I/wpa_supplicant( 6150): wpa_driver_nl80211_ext_driver_cmd RXFILTER-REMOVE 3
D/WfdsMonitor( 1964): WfdsMonitorThread create
D/WfdsMonitor( 1964): WFDS Monitor is created and started
D/WfdsService( 1964): WiFi: Supplicant connection re-established
D/WifiNative-wlan0( 1029): DRIVER RXFILTER-REMOVE 3: returned true
D/WifiNative-wlan0( 1029): doBoolean: DRIVER RXFILTER-START
I/wpa_supplicant( 6150): wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
D/WifiNative-wlan0( 1029): DRIVER RXFILTER-START: returned true
D/WifiNative-wlan0( 1029): doBoolean: DRIVER RXFILTER-STOP
I/wpa_supplicant( 6150): wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
D/WifiNative-wlan0( 1029): DRIVER RXFILTER-STOP: returned true
D/WifiNative-wlan0( 1029): doBoolean: DRIVER RXFILTER-REMOVE 2
I/wpa_supplicant( 6150): android_multicast_filter_startstop : multicast filter set
D/WifiNative-wlan0( 1029): DRIVER RXFILTER-REMOVE 2: returned true
D/WifiNative-wlan0( 1029): doBoolean: DRIVER RXFILTER-START
I/wpa_supplicant( 6150): wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
D/WifiNative-wlan0( 1029): DRIVER RXFILTER-START: returned true
E/WifiNative: ( 1029): [284,142,040 us] RECONNECT  stack:logDbg - reconnect - enter - invokeEnterMethods - performTransitions
D/WifiNative-wlan0( 1029): doBoolean: RECONNECT
E/BluetoothAdapterService( 6103): File transfer profiles supported!!
V/AudioManager( 6103): registerRemoteController: size of Media player list: 0
D/WifiNative-wlan0( 1029): RECONNECT: returned true
D/WifiNative-wlan0( 1029): doString: [STATUS]
,D/WifiMonitor( 1029): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
D/WifiNative-wlan0( 1029):    returned wpa_state=SCANNING p2p_device_address=02:9a:02:7b:60:ac address=c4:9a:02:7b:60:ac uuid=530d3fd0-1ba3-5409-a336-ff4e42af59a2
E/WifiMonitor( 1029): WifiMonitor:wlan0 cnt=1 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
D/WifiNative-wlan0( 1029): doBoolean: DRIVER SETSUSPENDMODE 1
I/wpa_supplicant( 6150): wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 1
D/WifiNative-wlan0( 1029): DRIVER SETSUSPENDMODE 1: returned true
D/WifiNative-wlan0( 1029): doBoolean: SET ps 1
D/WifiNative-wlan0( 1029): SET ps 1: returned true
D/LGWifiP2pService( 1029): P2pDisabledState{ when=0 what=131203 target=com.android.internal.util.StateMachine$SmHandler }
D/CommandListener(  323): Setting iface cfg
D/CommandListener(  323): Trying to bring up p2p0
D/WifiMonitor( 1029): startMonitoring(p2p0) with mConnected = true
D/LGWifiP2pService( 1029): P2pEnablingState
D/LGWifiP2pService( 1029): P2pEnablingState{ when=-1ms what=147457 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1029): P2p socket connection successful
D/LGWifiP2pService( 1029): P2pEnabledState
E/AudioManager( 6103): No RCC entry present to update
E/RemoteController( 6103): Cannot set synchronization mode on an unregistered RemoteController
D/WifiScanningService( 1029): SCAN_AVAILABLE : 3
D/RttService( 1029): SCAN_AVAILABLE : 3
D/WifiScanningService( 1029): DefaultState got{ when=-1ms what=160006 target=com.android.internal.util.StateMachine$SmHandler }
I/WifiNative-HAL( 1029): startHal
E/wifi    ( 1029): getStaticLongField sWifiHalHandle 0x94f6b99c
E/WifiHAL ( 1029): Could not connect handle
D/wifi    ( 1029): halHandle = 0x0, mVM = 0xb487c280, mCls = 0x201ebe
I/WifiNative-HAL( 1029): Could not start hal
E/WifiScanningService( 1029): could not start HAL
I/BluetoothAvrcpQcomServiceJni( 6103): classInitQcomNative: succeeds
D/RttService( 1029): DefaultState got{ when=-2ms what=160512 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1029): sending p2p connection changed broadcast
D/LGBluetoothAvrcpQcomAdapter( 6103): [BTUI] Use QCOM AVRCP 1.5 : init jni, browsing = false
I/BluetoothAvrcpQcomServiceJni( 6103): initQcomNative: succeeds
D/WifiNative-p2p0( 1029): doBoolean: SET persistent_reconnect 1
,I/StatusBar.NetworkController( 1462): networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/WifiNative-p2p0( 1029): SET persistent_reconnect 1: returned true
I/StatusBar.NetworkController( 1462): mWifiConnected = false, mWifiLevel = 0
D/WifiNative-p2p0( 1029): doBoolean: SET device_name G3-1
V/WfdStateTracker( 1964): WfdStateTracker handleDirectStateChangedEvent: 2
D/WifiNative-p2p0( 1029): SET device_name G3-1: returned true
D/LGWifiP2pService( 1029): [LGE_P2P] initializeP2pSettings() check postfix
D/WfdsService( 1964): WifiP2pState is changed : true
D/LGWifiP2pService( 1029): before postfix = G3-1
D/WifiService( 1029): New client listening to asynchronous messages
D/WifiServerServiceExt( 1029): postfix byte check : 4
D/LGWifiP2pService( 1029): after postfix = G3-1
D/WifiNative-p2p0( 1029): doBoolean: SET p2p_ssid_postfix -G3-1
D/WifiNative-p2p0( 1029): SET p2p_ssid_postfix -G3-1: returned true
D/WifiNative-p2p0( 1029): doBoolean: SET device_type 10-0050F204-5
D/WfdsService( 1964): Receive the WFDS_ENABLE Method
D/WfdsService( 1964): Set the WFDS Monitor: true
D/WfdsService( 1964): Connected to the supplicant for wfds
D/WifiNative-p2p0( 1029): SET device_type 10-0050F204-5: returned true
D/WfdsJNI ( 1964): doCommand: WFDS_SET TRUE
E/CtrlSupplicant( 1964): Not connected to wap_supplicant - "WFDS_SET TRUE" command dropped.
D/WfdsJNI ( 1964): wfds_send_command: [WFDS_SET TRUE] failed
D/WifiNative-p2p0( 1029): doBoolean: SET config_methods virtual_push_button physical_display keypad
D/WfdsJNI ( 1964): doCommand: WFDS_GET_MAC_ADDRESS
E/CtrlSupplicant( 1964): Not connected to wap_supplicant - "WFDS_GET_MAC_ADDRESS" command dropped.
D/WfdsJNI ( 1964): wfds_send_command: [WFDS_GET_MAC_ADDRESS] failed
D/LGBluetoothAvrcpQcomAdapter( 6103): [BTUI] [+] updateMediaPlayerInfo
D/WfdsJNI ( 1964): doCommand: IFNAME=wlan0 GET_CAPABILITY channels
E/CtrlSupplicant( 1964): Not connected to wap_supplicant - "IFNAME=wlan0 GET_CAPABILITY channels" command dropped.
D/WfdsJNI ( 1964): wfds_send_command: [IFNAME=wlan0 GET_CAPABILITY channels] failed
E/BluetoothAdapterService( 6103): File transfer profiles supported!!
D/WfdsService( 1964): selectPreferredScanChannel [0]
D/WifiNative-p2p0( 1029): SET config_methods virtual_push_button physical_display keypad: returned true
D/WfdsService( 1964): STATE : WfdsEnabledState - enter: this device mac null
D/WifiNative-p2p0( 1029): doBoolean: P2P_SET conc_pref p2p
E/WifiStateMachine( 1029):  DisconnectedState CMD_SET_OPERATIONAL_MODE 1 0
E/WifiStateMachine( 1029):  DisconnectedState CMD_START_DRIVER 0 0
E/WifiStateMachine( 1029):  ConnectModeState CMD_START_DRIVER 0 0
E/WifiStateMachine( 1029):  DriverStartedState CMD_START_DRIVER 0 0
E/WifiStateMachine( 1029):  DisconnectedState what:132106 1 0
D/StatusBar.NetworkController( 1462): refreshViews: Data not connected!! Set no data type icon / Roaming
E/WifiStateMachine( 1029):  ConnectModeState what:132106 1 0
E/WifiStateMachine( 1029):  DriverStartedState what:132106 1 0
I/WifiServerServiceExt( 1029): setWifiDualbandAPConnection band : 1
E/wpa_supplicant( 6150): nWIFIDualbandAPConnection: 1
D/WifiNative-p2p0( 1029): P2P_SET conc_pref p2p: returned true
D/WifiNative-HAL( 1029): p2pGetDeviceAddress
D/WifiNative-HAL( 1029): p2pGetDeviceAddress returning 
E/WifiStateMachine( 1029):  DisconnectedState what:132096 -100 0
E/WifiStateMachine( 1029):  ConnectModeState what:132096 -100 0
E/WifiStateMachine( 1029):  DriverStartedState what:132096 -100 0
I/WifiServerServiceExt( 1029): set CMD_DISCONNECT_RSSI_LVL : -100
E/wpa_supplicant( 6150): disconnect_rssi_lvl: -100
E/WifiStateMachine( 1029):  DisconnectedState CMD_SET_COUNTRY_CODE 1 0 cz
D/WfdsService( 1964): WIFI_P2P_CONNECTION_CHANGED_ACTION
E/WifiStateMachine( 1029):  ConnectModeState CMD_SET_COUNTRY_CODE 1 0 cz
E/WifiStateMachine( 1029):  DriverStartedState CMD_SET_COUNTRY_CODE 1 0 cz
D/WifiNative-wlan0( 1029),: doBoolean: DRIVER COUNTRY CZ
D/WfdsService( 1964): isConnected: false
I/wpa_supplicant( 6150): wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
,I/wpa_supplicant( 6150): wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
E/CtrlSupplicant( 1964): Access OK "@android:wpa_wlan0"
D/WifiMonitor( 1029): Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
E/WifiMonitor( 1029): WifiMonitor:wlan0 cnt=2 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
E/WifiMonitor( 1029): handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
E/WifiMonitor( 1029): handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
I/wpa_supplicant( 6150): [LGE_PATCH] driver_cmd() country:CZ
I/wpa_supplicant( 6150): p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
D/WifiMonitor( 1029): Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
E/WifiMonitor( 1029): WifiMonitor:p2p0 cnt=3 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
E/WifiMonitor( 1029): handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
E/WifiMonitor( 1029): handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
I/wpa_supplicant( 6150): p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
D/WifiMonitor( 1029): Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
E/WifiMonitor( 1029): WifiMonitor:p2p0 cnt=4 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
E/WifiMonitor( 1029): handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
E/WifiMonitor( 1029): handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
D/WifiNative-wlan0( 1029): DRIVER COUNTRY CZ: returned true
E/WifiStateMachine( 1029):  DisconnectedState CMD_SET_FREQUENCY_BAND 0 0
E/WifiStateMachine( 1029):  ConnectModeState CMD_SET_FREQUENCY_BAND 0 0
E/WifiStateMachine( 1029):  DriverStartedState CMD_SET_FREQUENCY_BAND 0 0
D/WifiNative-wlan0( 1029): doBoolean: DRIVER SETBAND 0
I/wpa_supplicant( 6150): wpa_driver_nl80211_ext_driver_cmd SETBAND 0 - interface name wlan0
I/wpa_supplicant( 6150): wlan0: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
D/WifiNative-wlan0( 1029): DRIVER SETBAND 0: returned true
D/WifiMonitor( 1029): Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN]
D/WifiNative-wlan0( 1029): doBoolean: BSS_FLUSH 0
E/WifiMonitor( 1029): WifiMonitor:wlan0 cnt=5 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
E/WifiMonitor( 1029): handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
E/WifiMonitor( 1029): handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
D/WifiNative-wlan0( 1029): BSS_FLUSH 0: returned true
D/WifiNative-wlan0( 1029): doBoolean: SCAN
E/CtrlSupplicant( 1964): Succeed to open control connection
D/WifiNative-wlan0( 1029): SCAN: returned false
E/CtrlSupplicant( 1964): Succeed to open monitor connection
D/WfdsMonitor( 1964): Supplicant connection established
D/WfdsService( 1964): Received the Event that WfdsMonitor is connected to supplicant
E/WifiStateMachine( 1029):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 1 0 rt=284176  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
D/LGWifiP2pService( 1029): DeviceAddress: 
D/WifiNative-p2p0( 1029): doBoolean: P2P_FLUSH
,E/WifiStateMachine( 1029):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 1 0 rt=284205  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
E/WifiStateMachine( 1029):  DisconnectedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
E/WifiStateMachine( 1029):  ConnectModeState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
E/WifiStateMachine( 1029):  DriverStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
E/WifiStateMachine( 1029):  SupplicantStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
E/WifiStateMachine( 1029):  DefaultState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
I/WfdStateTracker( 1964): handleP2pThisDeviceChanged
D/WfdsService( 1964): WIFI_P2P_THIS_DEVICE_CHANGED_ATCION
D/WfdsService( 1964): Update P2p Interface State: 3
I/StatusBar.NetworkController( 1462): networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1462): mWifiConnected = false, mWifiLevel = 0
W/Settings( 1029): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1029): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1029): NETWORK_STATE_CHANGED_ACTION [SCANNING]
D/WifiNative-p2p0( 1029): P2P_FLUSH: returned true
D/WifiNative-p2p0( 1029): doBoolean: P2P_SERVICE_FLUSH
D/StatusBar.NetworkController( 1462): refreshViews: Data not connected!! Set no data type icon / Roaming
D/WifiNative-p2p0( 1029): P2P_SERVICE_FLUSH: returned true
D/WifiNative-p2p0( 1029): doString: [LIST_NETWORKS]
D/WifiNative-p2p0( 1029):    returned network id / ssid / bssid / flags
D/WifiNative-p2p0( 1029): doBoolean: SAVE_CONFIG
D/WifiServerServiceExt( 1029): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1029): setSupplicantStateSCANNING
,V/LGMDMManager( 6103): Create singleton instance
I/BluetoothAdapterState( 6103): Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
D/WifiNative-p2p0( 1029): SAVE_CONFIG: returned true
D/LGWifiP2pService( 1029): sending p2p persistent groups changed broadcast
D/LGWifiP2pService( 1029): InactiveState
D/LGWifiP2pService( 1029): InactiveState{ when=-61ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1029): P2pEnabledState{ when=-61ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-p2p0( 1029): doBoolean: DRIVER COUNTRY CZ
I/wpa_supplicant( 6150): wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
I/wpa_supplicant( 6150): p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
,I/wpa_supplicant( 6150): [LGE_PATCH] driver_cmd() country:CZ
I/wpa_supplicant( 6150): p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
D/WifiNative-p2p0( 1029): DRIVER COUNTRY CZ: returned true
I/wpa_supplicant( 6150): p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
D/LGWifiP2pService( 1029): InactiveState{ when=-23ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1029): P2pEnabledState{ when=-23ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1029): InactiveState{ when=-2ms what=139287 arg2=1 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1029): P2pEnabledState{ when=-2ms what=139287 arg2=1 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1029): DefaultState{ when=-2ms what=139287 arg2=1 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1029): InactiveState{ when=-3ms what=139285 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1029): P2pEnabledState{ when=-3ms what=139285 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1029): DefaultState{ when=-3ms what=139285 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1029): InactiveState{ when=-1ms what=139287 arg2=1 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1029): P2pEnabledState{ when=-1ms what=139287 arg2=1 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1029): DefaultState{ when=-1ms what=139287 arg2=1 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1029): InactiveState{ when=-1ms what=139283 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1029): P2pEnabledState{ when=-1ms what=139283 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1029): DefaultState{ when=-1ms what=139283 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiServerServiceExt( 1029): No p2p device connected
D/WfdsMonitor( 1964): Event [CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
D/WfdsMonitor( 1964): Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
D/WfdsMonitor( 1964): Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
D/WifiMonitor( 1029): Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
E/WifiMonitor( 1029): WifiMonitor:p2p0 cnt=6 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
W/WfdsService( 1964): DefaultState - msg [9441285] is not handled
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
V/SIM_STK ( 1029): Menu title from STK is T-Mobile
V/SIM_STK ( 1029): Menu title from STK is T-Mobile
,E/WifiMonitor( 1029): WifiMonitor:wlan0 cnt=9 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
E/wpa_supplicant( 6150): USIM:  scard_init function
E/WifiMonitor( 1029): handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
D/WifiMonitor( 1029): Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
E/WifiMonitor( 1029): WifiMonitor:wlan0 cnt=10 dispatchEvent: WPS-AP-AVAILABLE 
I/wpa_supplicant( 6150): Trying to associate with SSID 'NG700'
W/WifiMonitor( 1029): couldn't identify event type - WPS-AP-AVAILABLE 
D/WifiMonitor( 1029): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
E/WifiMonitor( 1029): WifiMonitor:wlan0 cnt=11 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
,E/WifiStateMachine( 1029):  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=0 bcn=0
E/WifiStateMachine( 1029):  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=0 bcn=0
E/WifiStateMachine( 1029):  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=0 bcn=0
E/WifiStateMachine( 1029):  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=0 bcn=0
I/WifiNative-HAL( 1029): startHal
E/wifi    ( 1029): getStaticLongField sWifiHalHandle 0x989338cc
E/WifiHAL ( 1029): Could not connect handle
D/wifi    ( 1029): halHandle = 0x0, mVM = 0xb487c280, mCls = 0x501c56
I/WifiNative-HAL( 1029): Could not start hal
D/WifiNative-wlan0( 1029): doString: [BSS RANGE=0- MASK=0x21987]
,I/ActivityManager( 1029): Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=6215 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
E/ActivityThread( 6169): Failed to find provider info for com.lge.lgaccount.provider
W/LG Account v2.2( 6169): No ProfileInfo entries
I/LG Account v2.2( 6169): isEnabled: false
I/Feature ( 6169): [Lifetracker]ver: 4.21.112(40211120)
I/Feature ( 6169): [Lifetracker]Country: EU
I/Feature ( 6169): [Lifetracker]Operator: OPEN
I/Feature ( 6169): [Lifetracker]Ranking support: false
I/Feature ( 6169): [Lifetracker]Comfort support: false
I/Feature ( 6169): [Lifetracker]Accessory: true
I/Feature ( 6169): [Lifetracker]Health device: true
I/Feature ( 6169): [Lifetracker]Extra Pedometer: false
I/Feature ( 6169): [Lifetracker]Blood glucose device: false
I/Feature ( 6169): [Lifetracker]Device Number: 3
E/WifiStateMachine( 1029):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 11 0 rt=284296  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
W/Settings( 1029): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1029): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1029): NETWORK_STATE_CHANGED_ACTION [SCANNING]
I/StatusBar.NetworkController( 1462): networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1462): mWifiConnected = false, mWifiLevel = 0
E/WifiStateMachine( 1029):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 11 0 rt=284299  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
D/StatusBar.NetworkController( 1462): refreshViews: Data not connected!! Set no data type icon / Roaming
I/StatusBar.NetworkController( 1462): networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1462): mWifiConnected = false, mWifiLevel = 0
W/Settings( 1029): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1029): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1029): NETWORK_STATE_CHANGED_ACTION [CONNECTING]
D/StatusBar.NetworkController( 1462): refreshViews: Data not connected!! Set no data type icon / Roaming
D/WifiServerServiceExt( 1029): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1029): setSupplicantStateASSOCIATING
W/FormManager( 6187): Network not available. Please check & try again.
V/FormManager( 6187): Network unavailable.
V/FormManager( 6187): Network unavailable.
D/BluetoothPermissionRequest( 6141): onReceive
,D/LGBluetoothFeatureConfig( 6141):  get() - isFeatureLoaded : false
I/ActivityManager( 1029): Killing 5415:com.android.contacts/u0a19 (adj 15): empty #17
D/PCSuite ( 6215): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,W/ActivityManager( 1029): getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
,W/libprocessgroup( 1029): failed to open /acct/uid_10019/pid_5415/cgroup.procs: No such file or directory
D/BluetoothManagerService( 1029): Message: 20
I/ActivityManager( 1029): Killing 5743:com.lge.email/u0a23 (adj 15): empty #17
D/BluetoothManagerService( 1029): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@1359adcf:true
D/LGBluetoothAvrcpQcomAdapter( 6103): [BTUI] installed app name: Music
I/wpa_supplicant( 6150): wlan0: Associated with c0:ff:d4:d3:aa:48
D/WifiMonitor( 1029): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
E/WifiMonitor( 1029): WifiMonitor:wlan0 cnt=12 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
,D/WifiMonitor( 1029): Event [IFNAME=wlan0 Associated with c0:ff:d4:d3:aa:48]
E/WifiMonitor( 1029): WifiMonitor:wlan0 cnt=13 dispatchEvent: Associated with c0:ff:d4:d3:aa:48
E/WifiStateMachine( 1029):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 12 0 rt=284383  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
D/WifiMonitor( 1029): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1029): WifiMonitor:wlan0 cnt=14 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
E/WifiStateMachine( 1029):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 12 0 rt=284384  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
E/WifiStateMachine( 1029):  DisconnectedState CMD_ASSOCIATED_BSSID 13 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=284384
E/WifiStateMachine( 1029):  ConnectModeState CMD_ASSOCIATED_BSSID 13 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=284385
E/WifiStateMachine( 1029):  DriverStartedState CMD_ASSOCIATED_BSSID 13 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=284385
D/LGBluetoothAvrcpQcomAdapter( 6103): [BTUI] installed app name: Google Play Music
E/WifiStateMachine( 1029):  SupplicantStartedState CMD_ASSOCIATED_BSSID 13 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=284385
E/WifiStateMachine( 1029):  DefaultState CMD_ASSOCIATED_BSSID 13 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=284385
D/LGBluetoothAvrcpQcomAdapter( 6103): [BTUI] === MediaPlayerInfo (playerId:0) ===
D/LGBluetoothAvrcpQcomAdapter( 6103): [BTUI]          displayName: Music
D/LGBluetoothAvrcpQcomAdapter( 6103): [BTUI]          packageName: com.lge.music
E/WifiStateMachine( 1029):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 14 0 rt=284386  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: FOUR_WAY_HANDSHAKE
D/LGBluetoothAvrcpQcomAdapter( 6103): [BTUI]          playState: 2 (PAUSED)
D/LGBluetoothAvrcpQcomAdapter( 6103): [BTUI] === MediaPlayerInfo (playerId:1) ===
D/LGBluetoothAvrcpQcomAdapter( 6103): [BTUI]          displayName: Google Play Music
D/LGBluetoothAvrcpQcomAdapter( 6103): [BTUI]          packageName: com.google.android.music
D/LGBluetoothAvrcpQcomAdapter( 6103): [BTUI]          playState: 2 (PAUSED)
D/LGBluetoothAvrcpQcomAdapter( 6103): [BTUI] [-] updateMediaPlayerInfo
I/BluetoothA2dpServiceJni( 6103): classInitNative
I/BluetoothA2dpServiceJni( 6103): classInitNative: succeeds
D/A2dpStateMachine( 6103): make
I/bluedroid-qcom( 6103): get_profile_interface a2dp
I/GKI_LINUX( 6103): gki_task_entry task_id=2 [A2DP-MEDIA] starting
I/wpa_supplicant( 6150): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 6150): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
I/LGBluetoothA2dpServiceJni( 6103): classInitNative: succeeds
I/LGBluetoothA2dpAdapter( 6103): [BTUI] getInstance : create [LGBluetoothA2dpAdapter]
D/WifiMonitor( 1029): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1029): WifiMonitor:wlan0 cnt=15 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/WifiMonitor( 1029): Event [IFNAME=wlan0 WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]]
E/WifiMonitor( 1029): WifiMonitor:wlan0 cnt=16 dispatchEvent: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
W/WifiMonitor( 1029): couldn't identify event type - WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
D/WifiMonitor( 1029): Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]]
E/WifiMonitor( 1029): WifiMonitor:wlan0 cnt=17 dispatchEvent: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
E/WifiMonitor( 1029): handleEvent 1  Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
D/WifiMonitor( 1029): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor(, 1029): WifiMonitor:wlan0 cnt=18 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/BluetoothAdapterService( 6103): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@7038f05
D/HeadsetStateMachine( 6103): Proxy object connected
D/A2dpStateMachine( 6103): Enter Disconnected: -2
D/LGBluetoothHfpAdapter( 6103): [BTUI] queryPhoneState
D/LGBluetoothHfpAdapter( 6103): Try to query the phonestate on bind
D/BluetoothPhoneService.BluetoothLTECall( 1871):  call mBluetoothHeadset.phoneStateChanged()
W/BluetoothHeadset( 1871): Proxy not attached to service
I/BluetoothHidServiceJni( 6103): classInitNative: succeeds
D/BluetoothHeadset( 1871): java.lang.Throwable
D/BluetoothHeadset( 1871): 	at android.bluetooth.BluetoothHeadset.phoneStateChanged(BluetoothHeadset.java:826)
D/BluetoothHeadset( 1871): 	at com.android.phone.BluetoothPhoneService$BluetoothLTECall.handleQueryPhoneState(BluetoothPhoneService.java:1527)
D/BluetoothHeadset( 1871): 	at com.android.phone.BluetoothPhoneService$BluetoothLTECall.access$700(BluetoothPhoneService.java:1360)
D/BluetoothHeadset( 1871): 	at com.android.phone.BluetoothPhoneService$1.handleMessage(BluetoothPhoneService.java:268)
D/BluetoothHeadset( 1871): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/BluetoothHeadset( 1871): 	at android.os.Looper.loop(Looper.java:135)
D/BluetoothHeadset( 1871): 	at android.app.ActivityThread.main(ActivityThread.java:5274)
D/BluetoothHeadset( 1871): 	at java.lang.reflect.Method.invoke(Native Method)
D/BluetoothHeadset( 1871): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/BluetoothHeadset( 1871): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
D/BluetoothHeadset( 1871): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
D/HidService( 6103): Received start request. Starting profile...
I/bluedroid-qcom( 6103): get_profile_interface hidhost
D/BluetoothAdapterService( 6103): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@7038f05
D/BluetoothAdapterService( 6103): Profile still not running:com.android.bluetooth.gatt.GattService
I/BluetoothHealthServiceJni( 6103): classInitNative: succeeds
D/HeadsetStateMachine( 6103): Disconnected process message: 10, size: 0
D/HeadsetPhoneState( 6103): sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
D/HeadsetStateMachine( 6103): Disconnected process message: 11, size: 0
D/HealthService( 6103): Received start request. Starting profile...
I/bluedroid-qcom( 6103): get_profile_interface health
I/LGBluetoothHealthServiceJni( 6103): classInitNative: succeeds
D/BluetoothAdapterService( 6103): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@7038f05
I/BluetoothPanServiceJni( 6103): classInitNative(L105): succeeds
D/PanService( 6103): Received start request. Starting profile...
D/BluetoothPanServiceJni( 6103): initializeNative(L110): pan
I/bluedroid-qcom( 6103): get_profile_interface pan
D/Tethering( 1029): sendTetherStateChangedBroadcast 1, 0, 0
W/libprocessgroup( 1029): failed to open /acct/uid_10023/pid_5743/cgroup.procs: No such file or directory
I/LGBluetoothPanAdapter( 6103): [BTUI] getInstance : create [LGBluetoothPanAdapter]
D/BluetoothAdapterService( 6103): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@7038f05
I/BtGatt.JNI( 6103): classInitNative(L901): classInitNative: Success!
,W/Settings( 1029): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1029): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1029): NETWORK_STATE_CHANGED_ACTION [CONNECTING]
I/StatusBar.NetworkController( 1462): networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1462): mWifiConnected = false, mWifiLevel = 0
D/BtGatt.DebugUtils( 6103): handleDebugAction() action=null
D/StatusBar.NetworkController( 1462): refreshViews: Data not connected!! Set no data type icon / Roaming
D/BtGatt.GattService( 6103): Received start request. Starting profile...
D/BtGatt.GattService( 6103): start()
I/bluedroid-qcom( 6103): get_profile_interface gatt
D/BtGatt.AdvertiseManager( 6103): advertise manager created
E/WifiStateMachine( 1029):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 14 0 rt=284422  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: FOUR_WAY_HANDSHAKE
I/StatusBar.NetworkController( 1462): networkInfo=[type: WIFI[], state: CONNECTING/AUTHENTICATING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1462): mWifiConnected = false, mWifiLevel = 0
W/Settings( 1029): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1029): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1029): NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
D/StatusBar.NetworkController( 1462): refreshViews: Data not connected!! Set no data type icon / Roaming
V/WiFiOffLoadBroadcast( 6141): WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
D/BluetoothAdapterService( 6103): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@7038f05
D/WifiServerServiceExt( 1029): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1029): setSupplicantStateASSOCIATED
D/BluetoothAdapterService( 6103): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@7038f05
E/WifiStateMachine( 1029):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 15 0 rt=284428  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: GROUP_HANDSHAKE
I/LGBluetoothMapAdapter( 6103): [BTUI] getInstance : create [LGBluetoothMapAdapter]
E/WifiStateMachine( 1029):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 15 0 rt=284428  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: GROUP_HANDSHAKE
V/BluetoothMapService( 6103): BluetoothMapBinder()
E/WifiStateMachine( 1029):  DisconnectedState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=284430
E/WifiStateMachine( 1029):  ConnectModeState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=284430
D/WifiNative-wlan0( 1029): doString: [STATUS]
D/WifiMonitor( 1029): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1029): WifiMonitor:wlan0 cnt=19 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/BluetoothMapService( 6103): Received start request. Starting profile...
D/BluetoothMapService( 6103): start()
D/WifiService( 1029): New client listening to asynchronous messages
D/WifiNative-wlan0( 1029):    returned bssid=c0:ff:d4:d3:aa:48 ssid=NG700 id=0 mode=station pairwise_cipher=CCMP group_cipher=CCMP key_mgmt=WPA2-PSK wpa_state=COMPLETED p2p_device_address=02:9a:02:7b:60:ac address=c4:9a:02:7b:60:ac uuid=530d3fd0-1ba3-5409-a336-ff4e42af59a2
D/BluetoothMapEmailSettingsLoader( 6103): Found 0 applications
D/BluetoothMapEmailAppObserver( 6103): createReceiver()
I/WifiServiceExtension( 1029): s,etVHTCapabilityType  : false
D/BluetoothMapEmailAppObserver( 6103): initObservers()
D/BluetoothMapEmailAppObserver( 6103): getEnabledAccountItems()
D/BluetoothAdapterService( 6103): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@7038f05
I/WifiServerServiceExt( 1029): wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
I/WifiServerServiceExt( 1029): setKeepAlivePacketInterval msec : 60
D/BluetoothAdapterService( 6103): Profile still not running:com.android.bluetooth.gatt.GattService
I/StatusBar.NetworkController( 1462): networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1462): mWifiConnected = false, mWifiLevel = 0
V/AlarmManager( 1029): ELAPSED_WAKEUP set : Alarm{33f811db type 2 when 237430 android} when 237430
W/Settings( 1029): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1029): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/StatusBar.NetworkController( 1462): refreshViews: Data not connected!! Set no data type icon / Roaming
D/WifiOffDelayIfNotUsed( 1029): NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
W/Settings( 1029): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1029): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1029): NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
D/BluetoothAdapterService( 6103): Profile still not running:com.android.bluetooth.gatt.GattService
I/StatusBar.NetworkController( 1462): networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1462): mWifiConnected = false, mWifiLevel = 0
V/AlarmManager( 1029): RTC_WAKEUP set : Alarm{1fdbf0b7 type 0 when 1449671415933 com.android.vending} when 1449671415933
D/BluetoothAdapterService( 6103): Profile still not running:com.android.bluetooth.gatt.GattService
V/AlarmManager( 1029): RTC_WAKEUP set : Alarm{3c569fbc type 0 when 1449671416370 com.google.android.gms} when 1449671416370
V/AlarmManager( 1029): ELAPSED_WAKEUP set : Alarm{1cf57b45 type 2 when 275289 com.google.android.gms} when 275289
D/StatusBar.NetworkController( 1462): refreshViews: Data not connected!! Set no data type icon / Roaming
D/ConnectivityService( 1029): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
D/ConnectivityService( 1029): Got NetworkAgent Messenger
D/ConnectivityService( 1029): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
D/ConnectivityService( 1029): NetworkAgent connected
E/WifiConfigStore( 1029): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/WifiNative-wlan0( 1029): doBoolean: SET_NETWORK 0 bssid any
D/WifiNative-wlan0( 1029): SET_NETWORK 0 bssid any: returned true
D/WifiNative-wlan0( 1029): doBoolean: SAVE_CONFIG
D/BluetoothAdapterService( 6103): Profile still not running:com.android.bluetooth.gatt.GattService
V/PanService( 6103): [BTUI] SIM Extra State :ABSENT
D/BluetoothAdapterService( 6103): Profile still not running:com.android.bluetooth.map.BluetoothMapService
V/BluetoothMapService( 6103): Handler(): got msg=1
D/BluetoothAdapterState( 6103): CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
I/bluedroid-qcom( 6103): enable
I/GKI_LINUX( 6103): gki_task_entry task_id=0 [BTU] starting
I/bt_hci_bdroid( 6103): init
I/bt-btu  ( 6103): btu_task pending for preload complete event
D/LgDataFeature( 6141): LgDataFeature() Constructor: none
D/LgDataFeature( 6141): LgDataFeature() Constructor Done, null
I/bt_vendor( 6103): bt-vendor : init
I/bt_vendor( 6103): bt-vendor : get_bt_soc_type
E/bt_vendor( 6103): get_bt_soc_type: Failed to get soc type
I/bt_vendor( 6103): init: Local BD Address : c0:64:73:54:3f:58
D/bt_userial_mct( 6103): userial_init
D/bt_hci_bdroid( 6103): set_power 1
I/bt_vendor( 6103): bt-vendor : BT_VND_OP_POWER_CTRL: On
I/bt_vendor( 6103): Starting hciattach daemon
I/bt_vendor( 6103): try to set true
D/WiFiOffLoadUpdatePriority( 6141): remove : truetruetrue
,W/sh      ( 6250): type=1400 audit(0.0:157): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
W/sh      ( 6250): type=1400 audit(0.0:158): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
D/WifiNative-wlan0( 1029): SAVE_CONFIG: returned true
E/WifiConfigStore( 1029): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/WifiNative-wlan0( 1029): doBoolean: SET_NETWORK 0 bssid any
D/WifiNative-wlan0( 1029): SET_NETWORK 0 bssid any: returned true
D/WifiNative-wlan0( 1029): doBoolean: SAVE_CONFIG
I/qcom-bluetooth( 6252): /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  
D/WifiNative-wlan0( 1029): SAVE_CONFIG: returned true
D/CommandListener(  323): Setting iface cfg
D/DhcpStateMachine( 1029): StoppedState
E/WifiStateMachine( 1029): Start Dhcp Watchdog 1
D/DhcpStateMachine( 1029): StoppedState{ when=-1ms what=196609 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine( 1029): WaitBeforeStartState
E/WifiStateMachine( 1029):  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 18 0 rt=284499  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine( 1029):  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 18 0 rt=284500  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine( 1029):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 18 0 rt=284500  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine( 1029):  ObtainingIpState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1029):  L2ConnectedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1029):  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1029):  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1029):  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1029):  DefaultState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1029):  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 19 0 rt=284504  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine( 1029):  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 19 0 rt=284504  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine( 1029):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 19 0 rt=284505  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
D/WifiServerServiceExt( 1029): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1029): setSupplicantStateGROUP_HANDSHAKE
E/WifiStateMachine( 1029):  ObtainingIpState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:-2027508501] from screen [on:0 period:-2027508501]
E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:2] from screen [on:0 period:-2027508499]
I/WifiNative-HAL( 1029): startHal
E/wifi    ( 1029): getStaticLongField sWifiHalHandle 0x989338bc
E/WifiHAL ( 1029): Could not connect handle
D/wifi    ( 1029): halHandle = 0x0, mVM = 0xb487c280, mCls = 0x601a76
I/WifiNative-HAL( 1029): Could not start hal
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
D/StatusBar.NetworkController( 1462): refreshViews: Data not connected!! Set no data type icon / Roaming
,D/ConnectivityService( 1029): updateNetworkScore for NetworkAgentInfo [WIFI () - 100] to 60
E/WifiStateMachine( 1029):  ObtainingIpState CMD_GET_CONFIGURED_NETWORKS uid=1000 1000 0 num=1
E/WifiStateMachine( 1029):  L2ConnectedState CMD_GET_CONFIGURED_NETWORKS uid=1000 1000 0 num=1
E/WifiStateMachine( 1029):  ConnectModeState CMD_GET_CONFIGURED_NETWORKS uid=1000 1000 0 num=1
E/WifiStateMachine( 1029):  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1029):  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1029):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1029):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1029):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1029):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
D/ConnectivityService( 1029): Update of LinkProperties for NetworkAgentInfo [WIFI () - 100]; created=false
E/WifiStateMachine( 1029):  ObtainingIpState CMD_PRE_DHCP_ACTION 0 0 txpkts=1,0,0
E/WifiStateMachine( 1029):  L2ConnectedState CMD_PRE_DHCP_ACTION 0 0 txpkts=1,0,0
D/WifiNative-wlan0( 1029): doBoolean: DRIVER SETSUSPENDMODE 0
V/SIM_STK ( 1029): Menu title from STK is T-Mobile
I/qcom-bluetooth( 6259): /system/etc/init.qcom.bt.sh: Transport : smd 
,I/qcom-bluetooth( 6260): /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
I/wpa_supplicant( 6150): wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 0
,D/WifiNative-wlan0( 1029): DRIVER SETSUSPENDMODE 0: returned true
D/WifiNative-wlan0( 1029): doBoolean: SET ps 0
D/WifiNative-wlan0( 1029): SET ps 0: returned true
D/WifiNative-wlan0( 1029): doBoolean: DRIVER BTCOEXMODE 1
I/wpa_supplicant( 6150): wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 1
D/WifiNative-wlan0( 1029): DRIVER BTCOEXMODE 1: returned true
E/WifiStateMachine( 1029): CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
D/LGWifiP2pService( 1029): InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@21cbd43e target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1029): P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@21cbd43e target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine( 1029): WaitBeforeStartState{ when=0 what=196615 target=com.android.internal.util.StateMachine$SmHandler }
V/DhcpStateMachine( 1029): Current State is mWaitBeforeStartState.
D/DhcpStateMachine( 1029): DHCP Start wake lock is acquired.
V/LgDhcpStateMachineHelper( 1029): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
V/LgDhcpStateMachineHelper( 1029): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700" is not exist.
D/WifiServerServiceExt( 1029): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1029): setSupplicantStateCOMPLETED
D/WifiServerServiceExt( 1029): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1029): setSupplicantStateCOMPLETED
I/qcom-bluetooth( 6262): /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
E/WifiStateMachine( 1029):  ObtainingIpState CMD_SAVE_CONFIG uid=1000 0 0
E/WifiStateMachine( 1029):  L2ConnectedState CMD_SAVE_CONFIG uid=1000 0 0
E/WifiStateMachine( 1029):  ConnectModeState CMD_SAVE_CONFIG uid=1000 0 0
D/WifiNative-wlan0( 1029): doBoolean: SAVE_CONFIG
I/qcom-bluetooth( 6263): /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> 
,I/qcom-bluetooth( 6264): /system/etc/init.qcom.bt.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
D/WifiNative-wlan0( 1029): SAVE_CONFIG: returned true
D/WiFiOffLoadUpdatePriority( 6141): remove1
V/WiFiOffLoadSharedPrefsUtils( 6141): save remove
I/qcom-bluetooth( 6265): /system/etc/init.qcom.bt.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> 
,D/WiFiOffLoadBroadcast( 6141): mLastConnectedNetwork from SharedPrefsUtils for wifioffloading : null
D/WiFiOffLoadBroadcast( 6141): S: false, R: false
E/WifiStateMachine( 1029):  ObtainingIpState CMD_GET_CONFIGURED_NETWORKS uid=1000 1000 0 num=1
E/WifiStateMachine( 1029):  L2ConnectedState CMD_GET_CONFIGURED_NETWORKS uid=1000 1000 0 num=1
E/WifiStateMachine( 1029):  ConnectModeState CMD_GET_CONFIGURED_NETWORKS uid=1000 1000 0 num=1
D/WiFiOffLoadUpdatePriority( 6141): saved SSID: "NG700"
D/WiFiOffLoadUpdatePriority( 6141): connected SSID: null
D/WiFiOffLoadUpdatePriority( 6141): private wpa: "NG700" 300
D/WifiServiceImplEx( 1029): addOrUpdateNetwork pid=6141, uid=1000, packageName=android.uid.system:1000
E/addOrUpdateNetwork( 1029):  uid = 1000 SSID "NG700" nid=0
E/WifiStateMachine( 1029):  ObtainingIpState CMD_ADD_OR_UPDATE_NETWORK uid=1000 0 0 "NG700"WPA_PSK prio=300 status=2 any is current
,E/WifiStateMachine( 1029):  L2ConnectedState CMD_ADD_OR_UPDATE_NETWORK uid=1000 0 0 "NG700"WPA_PSK prio=300 status=2 any is current
E/WifiStateMachine( 1029):  ConnectModeState CMD_ADD_OR_UPDATE_NETWORK uid=1000 0 0 "NG700"WPA_PSK prio=300 status=2 any is current
E/WifiConfigStore( 1029):  key="NG700"WPA_PSK netId=0 uid=0/1000
D/WifiServerServiceExt( 1029): addOrUpdateNetwork: mThisIsFirstEnableing = false
D/WifiNative-wlan0( 1029): doBoolean: SET_NETWORK 0 ssid 4e47373030
I/libmdmdetect( 6267): ESOC framework not supported
E/Diag_Lib( 6267):  Diag_LSM_Init: Failed to open handle to diag driver, error = 13
,D/bthci_qcomm_linux( 6267): [BTUI] bt_hci_qcomm_pfal_get_bdaddress: Get BDADDR from bluedroid prop (58:3F:54:73:64:C0)
D/bthci_qcomm_common( 6267): [BTUI] bt_hci_qcomm_init:
D/bthci_qcomm_common( 6267): [BTUI]     BDADDR: 58:3F:54:73:64:C0
D/bthci_qcomm_common( 6267): [BTUI]     BR/EDR: Class 1
D/bthci_qcomm_common( 6267): [BTUI]     LE: Class 2
D/bthci_qcomm_common( 6267): [BTUI]     Ref Clock: 32M
D/btqsocnvmtags( 6267): [BTUI] init_riva_entries: set NORMAL power settings
D/WifiNative-wlan0( 1029): SET_NETWORK 0 ssid 4e47373030: returned true
E/WifiConfigStore( 1029): Setting BSSID for "NG700"WPA_PSK to any
D/WifiNative-wlan0( 1029): doBoolean: SET_NETWORK 0 bssid any
D/WifiNative-wlan0( 1029): SET_NETWORK 0 bssid any: returned true
D/WifiNative-wlan0( 1029): doBoolean: SET_NETWORK 0 key_mgmt WPA-PSK
,D/WifiNative-wlan0( 1029): SET_NETWORK 0 key_mgmt WPA-PSK: returned true
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
D/WiFiOffLoadUpdatePriority( 6141):  ssid "NG700" prio 300
D/WiFiOffLoadUpdatePriority( 6141): configuration updated: 0
E/WifiStateMachine( 1029):  ObtainingIpState CMD_SAVE_CONFIG uid=1000 0 0
E/WifiStateMachine( 1029):  L2ConnectedState CMD_SAVE_CONFIG uid=1000 0 0
E/WifiStateMachine( 1029):  ConnectModeState CMD_SAVE_CONFIG uid=1000 0 0
D/WifiNative-wlan0( 1029): doBoolean: SAVE_CONFIG
D/WifiNative-wlan0( 1029): SAVE_CONFIG: returned true
,D/WiFiOffLoadUpdatePriority( 6141): configuration saved: true
D/LGBluetoothResetSettingReceiver( 6141): return without doing reset settings.
D/LGBluetoothOppAdapter( 6103): [BTUI] getInstance : create [LGBluetoothOppAdapter]
D/PCSuite ( 6215): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 6141): WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
V/BluetoothFtpReceiver( 6103): BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
,V/BluetoothSapReceiver( 6103): [BTUI] checkServiceStart
V/BluetoothSapReceiver( 6103): [BTUI] region:EU country:EU
V/BluetoothSapReceiver( 6103): SapReceiver onReceive 
D/WiFiOffLoadBroadcast( 6141): MCCMNC not supported: null
V/BluetoothSapReceiver( 6103): action = android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothSapReceiver( 6103):  Bluetooth Adapter state = 11
D/LGDMClient( 2966): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
D/LGDMClient( 2966): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
W/ContextImpl( 2966): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
I/ActivityManager( 1029): Start proc com.lge.settings.easy for broadcast com.lge.settings.easy/com.lge.settings.bluetooth.LGBluetoothProfileConnectionReceiver: pid=6273 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,W/ContextImpl( 2966): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
V/GLSActivity( 2130): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/FormManager( 6187): Network not available. Please check & try again.
I/rmt_storage(  319): rmt_storage_connect_cb: clnt_h=0x5 conn_h=0xb6403090
I/rmt_storage(  319): rmt_storage_rw_iovec_cb: /boot/modem_fs1: clnt_h=0x1: req_h=0x9 msg_id=3: R/W request received
I/rmt_storage(  319): wakelock acquired: 1, error no: 42
I/rmt_storage(  319): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 Unblock worker thread (th_id: -1236807552)
D/LGDMClient( 2966): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=3, isUserType=1
D/LGDMClient( 2966): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
D/LGDMClient( 2966): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
V/FormManager( 6187): Network unavailable.
,V/FormManager( 6187): Network unavailable.
D/PostponalbeReceiver( 5113): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
I/PCSuite ( 6215): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 6215): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 6215): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 6141): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
I/GLSUser ( 2130): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 2130): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2130): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2130): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2130): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/ResourcesManager( 6273): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
D/WiFiOffLoadBroadcast( 6141): MCCMNC not supported: null
D/DhcpStateMachine( 1029): DHCPV4 request on wlan0
V/LgDhcpStateMachineHelper( 1029): [bssid] hash key :c0:ff:d4:d3:aa:48
,D/LgDhcpStateMachineHelper( 1029): dhcp.ap.macaddress = c0:ff:d4:d3:aa:48
I/ActivityManager( 1029): Start proc com.lge.qremote for broadcast com.lge.qremote/.settings.WiFiStateReceiver: pid=6295 uid=10112 gids={50112, 9997, 1028, 1015, 3003, 3002} abi=armeabi
,I/ActivityManager( 1029): Killing 5441:com.android.gallery3d/u0a27 (adj 15): empty #17
I/rmt_storage(  319): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0x9 msg_id=3: Bytes written = 1572864
I/rmt_storage(  319): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0x9 msg_id=3: Send response: res=0 err=0
I/rmt_storage(  319): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 About to block rmt_storage client thread (th_id: -1236807552) wakelock released: 1, error no: 22
I/rmt_storage(  319): 
,I/rmt_storage(  319): rmt_storage_disconnect_cb: clnt_h=0x0x5 conn_h=0x0xb6403090
W/dhcpcd  ( 6294): type=1400 audit(0.0:159): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
E/Diag_Lib(  888): [IMS_FATAL]| 3347 | 913 |ims-rtp-daemon ims_rtp_qmi_handler_thread_func waiting on select thread>
W/dhcpcd  ( 6294): type=1400 audit(0.0:160): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
I/dhcpcd  ( 6294): version 5.5.6 starting
E/dhcpcd  ( 6294): get_duid: m
D/dhcpcd  ( 6294): wlan0: using ClientID 01:c4:9a:02:7b:60:ac
D/dhcpcd  ( 6294): wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason PREINIT
,D/AuthorizationBluetoothService( 2130): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
W/libprocessgroup( 1029): failed to open /acct/uid_10027/pid_5441/cgroup.procs: No such file or directory
D/Finsky  ( 4849): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 4849): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 4849): [1] 5.onFinished: Giving up after 6 failures.
,D/[Concierge]Service( 2608): onStartCommand(). Type : 9
I/ActivityManager( 1029): Killing 5645:com.android.defcontainer/u0a4 (adj 15): empty #17
,W/ResourcesManager( 6295): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/libprocessgroup( 1029): failed to open /acct/uid_10004/pid_5645/cgroup.procs: No such file or directory
,D/QRemote ( 6295): [QRemoteApplication.java:230:onCreate()] oooooo QRemoteApp onCreate....
,D/QRemote ( 6295): [CarrierUtils.java:858:getHardwareSettings()] oooooo qremote android.os.Build.MODEL = LG-D855
I/QRemote ( 6295): [CarrierUtils.java:859:getHardwareSettings()] oooooo getCountry :: EU
I/QRemote ( 6295): [CarrierUtils.java:860:getHardwareSettings()] oooooo getCarrier :: OPEN
,I/QRemote ( 6295): [CarrierUtils.java:861:getHardwareSettings()] oooooo getArea :: COM
,D/QRemote ( 6295): [CarrierUtils.java:862:getHardwareSettings()] oooooo Loading Config...
D/QRemote ( 6295): [CarrierUtils.java:876:getHardwareSettings()] oooooo qremote configuration file = R.xml.qremote_conf
D/QRemote ( 6295): [QRemoteApplication.java:701:updateWidget()] oooooo Widget count is [1]. send broadcast
D/QRemote ( 6295): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6295): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,D/dhcpcd  ( 6294): getUsingAPMacAddress: c0:ff:d4:d3:aa:48 , return 1
,D/dhcpcd  ( 6294): [read_lease] unlink /data/misc/dhcp/dhcpcd-wlan0.lease, link /data/misc/dhcp/dhcpcd-wlan0-c0:ff:d4:d3:aa:48.lease2
D/dhcpcd  ( 6294): wlan0: reading lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
,I/dhcpcd  ( 6294): wlan0: rebinding lease of 192.168.1.125
D/dhcpcd  ( 6294): wlan0: sending REQUEST (xid 0x6f2e3bfe), next in 4.35 seconds
I/QRemote ( 6295): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
V/[BNRBootReceiver]( 5846): boot receiver action = android.net.wifi.p2p.CONNECTION_STATE_CHANGE
D/QRemote ( 6295): [QRemoteService.java:196:onCreate()] oooooo 140526:onCreate
D/BNRAndroBeam( 5846): [BnR DirectBeam] Android Direct Beam(NFC) Connection changed
D/QRemote ( 6295): [QRemoteService.java:217:onStartCommand()] oooooo 140526:onStartCommand:action:action.application.oncreate. startId:1, flags:0
,V/[BNRBootReceiver]( 5846): Boot Receiver Return
D/PostponalbeReceiver( 5113): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
V/WiFiOffLoadBroadcast( 6141): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6141): MCCMNC not supported: null
D/QRemote ( 6295): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6295): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 6295): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
V/WiFiOffLoadBroadcast( 6141): WiFiOffLoadBroadcast: android.net.wifi.SCAN_RESULTS
D/WiFiOffLoadBroadcast( 6141): Not supported operator for automatic switch
D/PostponalbeReceiver( 5113): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,V/WiFiOffLoadBroadcast( 6141): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 6141): MCCMNC not supported: null
D/QRemote ( 6295): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,D/QRemote ( 6295): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 6295): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
D/PostponalbeReceiver( 5113): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
V/WiFiOffLoadBroadcast( 6141): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6141): MCCMNC not supported: null
D/QRemote ( 6295): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6295): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 6295): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
D/UsbSettingsReceiver( 6141): [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
D/UsbSettingsReceiver( 6141): [AUTORUN] sys.usb.config = ptp_only,adb
D/UsbSettingsReceiver( 6141): [AUTORUN] sys.usb.state = ptp_only,adb
D/UsbSettingsReceiver( 6141): [AUTORUN] persist.sys.usb.config = ptp_only,adb
D/UsbSettingsReceiver( 6141): [AUTORUN] onReceive() : app userid = 0, current userid = 0
D/UsbSettingsControl( 6141): [AUTORUN] getUsbConnected() : connected=true
D/UsbSettingsReceiver( 6141): [AUTORUN] onReceive() : availableList=[wlan0]
D/UsbSettingsReceiver( 6141): [AUTORUN] onReceive() : activeList=[]
D/UsbSettingsReceiver( 6141): [AUTORUN] onReceive() : errorList=[]
D/UsbSettingsControl( 6141): [AUTORUN] isAutorunTimer() : mAutorunChanging=false
D/UsbSettingsReceiver( 6141): [AUTORUN] onReceive() : TetherState Changed=wlan0
D/UsbSettingsControl( 6141): [AUTORUN] setTetherStatus() : status=false
D/PostponalbeReceiver( 5113): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,V/WiFiOffLoadBroadcast( 6141): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 6141): MCCMNC not supported: null
D/QRemote ( 6295): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,D/QRemote ( 6295): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 6295): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
D/PostponalbeReceiver( 5113): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
V/WiFiOffLoadBroadcast( 6141): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6141): MCCMNC not supported: null
,D/QRemote ( 6295): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,D/QRemote ( 6295): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 6295): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
D/PostponalbeReceiver( 5113): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
V/WiFiOffLoadBroadcast( 6141): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6141): MCCMNC not supported: null
D/QRemote ( 6295): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6295): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 6295): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
D/PostponalbeReceiver( 5113): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,V/WiFiOffLoadBroadcast( 6141): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6141): MCCMNC not supported: null
D/QRemote ( 6295): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6295): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 6295): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
D/libc-netbsd(  323): default dns: query_ipv6=0, query_ipv4=0
,D/DSQN    ( 1029): DNSproblemNotiEnabled is disabled ignore DNS fail CB
V/QRemote ( 6295): [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
D/QRemote ( 6295): [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
D/QRemote ( 6295): [QRemoteApplication.java:86:getControlManager()] oooooo mControlManager is null. make new RemoteControlManager
,I/EventLogService( 2363): Aggregate from 1449669616327 (log), 1449669616327 (data)
D/LgDataFeature( 6295): LgDataFeature() Constructor: none
D/LgDataFeature( 6295): LgDataFeature() Constructor Done, null
,V/SoundPool( 6295): SoundPool constructor: maxChannels=2, attr.usage=13, attr.flags=0x0, attr.tags=
V/SoundPool( 6295): load: fd=30, offset=10857164, length=17813, priority=1
V/SoundPool( 6295): create sampleID=1, fd=32, offset=17813 length=10857164
V/SoundPool( 6295): doLoad: loading sample sampleID=1
I/QRemote ( 6295): [RemoteControlManager.java:157:onBindIRService()] oooooo bind
V/SoundPool( 6295): Start decode
V/MediaPlayer[Native]( 6295): decode(32, 10857164, 17813)
,V/MediaPlayerService(  327): decode(24, 10857164, 17813)
W/BrunchPlayerTypeImpl(  327): [SelectPlayer] LocalType
W/BrunchPlayerTypeImpl(  327): [getMediaType] EXTEND_MEDIA_MIMETYPE = application/ogg
W/BrunchPlayerTypeImpl(  327): [FindUsePlayer] type = [application/ogg]
W/BrunchPlayerTypeImpl(  327): [FindUsePlayer] componentName = [9101]
W/MediaPlayerFactory(  327): [getPlayerType:fd] nType = 3
V/MediaPlayerService(  327): player type = 3
V/AwesomePlayer(  327): AwesomePlayer create()
V/AwesomePlayer(  327): reset_l() 
V/AwesomePlayer(  327): cancelPlayerEvents
V/AwesomePlayer(  327): setAudioSink() 
V/AwesomePlayer(  327): reset_l() 
V/AudioCache(  327): notify(0xb1163840, 8, 0, 0)
V/AudioCache(  327): ignored
V/AwesomePlayer(  327): cancelPlayerEvents
D/Utils   (  327): printFileName fd(25) -> /data/preload/LGQRemote/LGQRemote.apk
V/AwesomePlayer(  327): setDataSource_l dataSource
V/LGParserOSAL(  327): SniffLGParser start
V/LGParserOSAL(  327): MainType:5, SubType=0
V/LGParserOSAL(  327): #### check Mime : application/ogg
V/LGParserOSAL(  327): Detector mimeType:application/ogg, Confidence=1.000000
E/MediaExtractor(  327): Use LGExtractor :application/ogg 
D/UEI.SmartControl( 5791): QS Service created
D/QRemote ( 6295): [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
,E/QRemote ( 6295): [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
D/QRemote ( 6295): [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
,I/UEI.SmartControl( 5791): Service initServices...
D/UEI.SmartControl( 5791): QS start get config
V/LGMDMManager( 6295): Create singleton instance
V/LGParserOSAL(  327): supported mime: application/ogg
,V/AwesomePlayer(  327): setDataSource_l() extractor countTracks=1
V/AwesomePlayer(  327): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer(  327): mBitrate = -1 bits/sec
V/AwesomePlayer(  327): AudioTrack Setting
V/AwesomePlayer(  327): AudioTrack Setting channelCount = 2
V/AwesomePlayer(  327): setAudioSource() 
V/MediaPlayerService(  327): prepare
V/AwesomePlayer(  327): prepareAsync_l() 
V/MediaPlayerService(  327): wait for prepare
V/AwesomePlayer(  327): onPrepareAsyncEvent() 
V/AwesomePlayer(  327): initAudioDecoder() 
W/Utils   (  327): bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
V/AudioSystem(  327): isOffloadSupported()
V/AudioPolicyManager(  327): isOffloadSupported: SR=48000, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
D/AudioPolicyManager(  327): isOffloadSupported: stream_type != MUSIC, returning false
I/AudioFlinger(  327): isAudioPlaybackHookOn() false
V/AwesomePlayer(  327): getUseOffload() = 0 
V/OMXCodec(  327): OMXCodec::Create
V/OMXCodec(  327): findMatchingCodecs()
V/OMXCodec(  327): matching 'OMX.google.vorbis.decoder' quirks 0x00000000
V/OMXCodec(  327): matchingCodecs.size()=1
V/OMXCodec(  327): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
D/OMXCodec(  327): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
V/LGCodecAdapter(  327): LG Codec Adapter start
V/OMXCodec(  327): OMXCodec Createtor
V/OMXCodec(  327): setComponentRole
V/OMXCodec(  327): configureCodec protected=0
V/LGCodecAdapter(  327): called getLGCodecSpecificData
V/LGCodecOSAL(  327): Called LGgetCodecSpecificDataMETA
V/LGCodecOSAL(  327): Called LGconfigureCodecMETA
V/LGCodecOSAL(  327): Called LGconfigureCodecMSG
V/LGCodecOSAL(  327): Not support LGCodec
V/OMXCodec(  327): [OMX.google.vorbis.decoder] initOutputFormat()
V/OMXCodec(  327): Codec outputs a different number of channels than the input stream contains (contains 2 channels, codec outputs 1 channels).
V/OMXCodec(  327): Codec outputs at different sampling rate than what the input stream contains (contains data at 48000 Hz, codec outputs 44100 Hz)
I/AwesomePlayer(  327): Could not offload audio decode, try pcm offload
W/Utils   (  327): bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
V/AudioSystem(  327): isOffloadSupported()
V/AudioPolicyManager(  327): isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
D/AudioPolicyManager(  327): isOffloadSupported: stream_type != MUSIC, returning false
V/OMXCodec(  327): [OMX.google.vorbis.decoder] start mState=1
V/OMXCodec(  327): init()
V/OMXCodec(  327): [OMX.google.vorbis.decoder] setState mState=1 , newState=2
V/OMXCodec(  327): allocateBuffers
V/OMXCodec(  327): allocateBuffersOnPort portIndex=0
V/OMXCodec(  327): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
V/OMXCodec(  327): [OMX.google.vorbis.decoder] allocated buffer 0xb1434420 on input port
V/OMXCodec(  327): [OMX.google.vorbis.decoder] allocated buffer 0xb1434470 on input port
V/OMXCodec(  327): [OMX.google.vorbis.decoder] allocated buffer 0xb14344c0 on input port
V/OMXCodec(  327): [OMX.google.vorbis.decoder] allocated buffer 0xb1434510 on input port
V/OMXCodec(  327): allocateBuffersOnPort portIndex=1
V/OMXCodec(  327): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
V/OMXCodec(  327): [OMX.google.vorbis.decoder] allocated buffer 0xb1434560 on output port
V/OMXCodec(  327): [OMX.google.vorbis.decoder] allocated buffer 0xb14346a0 on output port
V/OMXCodec(  327): [OMX.google.vorbis.decoder] allocated buffer 0xb14346f0 on output port
V/OMXCodec(  327): [OMX.google.vorbis.decoder] allocated buffer 0xb1434880 on output port
V/OMXCodec(  327): in,it() mAsyncCompletion wait!!! 
V/OMXCodec(  327): [OMX.google.vorbis.decoder] onStateChange 2
V/OMXCodec(  327): [OMX.google.vorbis.decoder] Now Idle.
V/OMXCodec(  327): [OMX.google.vorbis.decoder] setState mState=2 , newState=3
V/OMXCodec(  327): [OMX.google.vorbis.decoder] onStateChange 3
V/OMXCodec(  327): [OMX.google.vorbis.decoder] Now Executing.
V/OMXCodec(  327): [OMX.google.vorbis.decoder] setState mState=3 , newState=4
V/OMXCodec(  327): init() mAsyncCompletion wait free! 
V/AwesomePlayer(  327): finishAsyncPrepare_l() 
V/AudioCache(  327): notify(0xb1163840, 5, 0, 0)
V/AudioCache(  327): ignored
V/AudioCache(  327): notify(0xb1163840, 1, 0, 0)
V/AudioCache(  327): prepared
V/AudioCache(  327): wait - success
V/MediaPlayerService(  327): start
V/AwesomePlayer(  327): play_l() 
V/AwesomePlayer(  327): play_l m_isDivXDRM=0, bpurchasefile:0
V/AwesomePlayer(  327): createAudioPlayer_l
V/AwesomePlayer(  327): seekAudioIfNecessary_l() 
V/AwesomePlayer(  327): startAudioPlayer_l() 
D/AudioPlayer(  327): start of Playback, useOffload 0
V/OMXCodec(  327): [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
V/OMXCodec(  327): [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
V/OMXCodec(  327): [OMX.google.vorbis.decoder] OMX_EventPortSettingsChanged(port=1, data2=0x00000000)
V/OMXCodec(  327): [OMX.google.vorbis.decoder] PORT_SETTINGS_CHANGED(1)
V/OMXCodec(  327): [OMX.google.vorbis.decoder] setState mState=4 , newState=7
V/OMXCodec(  327): [OMX.google.vorbis.decoder] disablePortAsync portIndex=1
V/OMXCodec(  327): [OMX.google.vorbis.decoder] sending OMX_CommandPortDisable(1)
V/OMXCodec(  327): [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
V/OMXCodec(  327): [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2973975904
V/OMXCodec(  327): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
V/OMXCodec(  327): [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2973976224
V/OMXCodec(  327): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
V/OMXCodec(  327): [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2973976304
V/OMXCodec(  327): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
V/OMXCodec(  327): [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2973976704
V/OMXCodec(  327): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
V/OMXCodec(  327): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
V/OMXCodec(  327): [OMX.google.vorbis.decoder] initOutputFormat()
V/OMXCodec(  327): [OMX.google.vorbis.decoder] reconfig handling, formatHasNotablyChanged
V/OMXCodec(  327): [OMX.google.vorbis.decoder] enablePortAsync portIndex=1
V/OMXCodec(  327): [OMX.google.vorbis.decoder] sending OMX_CommandPortEnable(1)
V/OMXCodec(  327): allocateBuffersOnPort portIndex=1
V/OMXCodec(  327): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
V/OMXCodec(  327): [OMX.google.vorbis.decoder] allocated buffer 0xb14346f0 on output port
V/OMXCodec(  327): [OMX.google.vorbis.decoder] allocated buffer 0xb14346a0 on output port
V/OMXCodec(  327): [OMX.google.vorbis.decoder] allocated buffer 0xb1434560 on output port
V/OMXCodec(  327): [OMX.google.vorbis.decoder] allocated buffer 0xb119a1a0 on output port
V/OMXCodec(  327): [OMX.google.vorbis.decoder] PORT_ENABLED(1)
V/OMXCodec(  327): [OMX.google.vorbis.decoder] setState mState=7 , newState=4
V/AudioCache(  327): open(48000, 2, 0x0, 1, 4)
V/AudioCache(  327): notify(0xb1163840, 6, 0, 0)
V/AudioCache(  327): ignored
V/MediaPlayerService(  327): wait for playback complete
V/AudioCache(  327): write(0xb57bf000, 4096)
V/AudioCache(  327): memcpy(0xaf406000, 0xb57bf000, 4096)
V/AudioCache(  327): write(0xb57bf000, 4096)
V/AudioCache(  327): memcpy(0xaf407000, 0xb57bf000, 4096)
V/AudioCache(  327): write(0xb57bf000, 4096)
V/AudioCache(  327): memcpy(0xaf408000, 0xb57bf000, 4096)
V/AudioCache(  327): write(0xb57bf000, 4096)
V/AudioCache(  327): memcpy(0xaf409000, 0xb57bf000, 4096)
V/AudioCache(  327): write(0xb57bf000, 4096)
V/AudioCache(  327): memcpy(0xaf40a000, 0xb57bf000, 4096)
V/AudioCache(  327): write(0xb57bf000, 4096)
V/AudioCache(  327): memcpy(0xaf40b000, 0xb57bf000, 4096)
V/AudioCache(  327): write(0xb57bf000, 4096)
V/AudioCache(  327): memcpy(0xaf40c000, 0xb57bf000, 4096)
V/AudioCache(  327): write(0xb57bf000, 4096)
V/AudioCache(  327): memcpy(0xaf40d000, 0xb57bf000, 4096)
V/AudioCache(  327): write(0xb57bf000, 4096)
V/AudioCache(  327): memcpy(0xaf40e000, 0xb57bf000, 4096)
V/AudioCache(  327): write(0xb57bf000, 4096)
V/AudioCache(  327): memcpy(0xaf40f000, 0xb57bf000, 4096)
V/AudioCache(  327): write(0xb57bf000, 4096)
V/AudioCache(  327): memcpy(0xaf410000, 0xb57bf000, 4096)
V/AudioCache(  327): write(0xb57bf000, 4096)
V/AudioCache(  327): memcpy(0xaf411000, 0xb57bf000, 4096)
V/AudioCache(  327): write(0xb57bf000, 4096)
V/AudioCache(  327): memcpy(0xaf412000, 0xb57bf000, 4096)
V/AudioCache(  327): write(0xb57bf000, 4096)
V/AudioCache(  327): memcpy(0xaf413000, 0xb57bf000, 4096)
V/AudioCache(  327): write(0xb57bf000, 4096)
V/AudioCache(  327): memcpy(0xaf414000, 0xb57bf000, 4096)
V/AudioCache(  327): write(0xb57bf000, 4096)
V/AudioCache(  327): memcpy(0xaf415000, 0xb57bf000, 4096)
V/AudioCache(  327): write(0xb57bf000, 4096)
V/AudioCache(  327): memcpy(0xaf416000, 0xb57bf000, 4096)
V/AudioCache(  327): write(0xb57bf000, 4096)
V/AudioCache(  327): memcpy(0xaf417000, 0xb57bf000, 4096)
V/AudioCache(  327): write(0xb57bf000, 4096)
V/AudioCache(  327): memcpy(0xaf418000, 0xb57bf000, 4096)
V/AudioCache(  327): write(0xb57bf000, 4096)
V/AudioCache(  327): memcpy(0xaf419000, 0xb57bf000, 4096)
V/AudioCache(  327): write(0xb57bf000, 4096)
V/AudioCache(  327): memcpy(0xaf41a000, 0xb57bf000, 4096)
V/AudioCache(  327): write(0xb57bf000, 4096)
V/AudioCache(  327): memcpy(0xaf41b000, 0xb57bf000, 4096)
V/AudioCache(  327): write(0xb57bf000, 4096)
V/AudioCache(  327): memcpy(0xaf41c000, 0xb57bf000, 4096)
V/AudioCache(  327): write(0xb57bf000, 4096)
V/AudioCache(  327): memcpy(0xaf41d000, 0xb57bf000, 4096)
V/AudioCache(  327): write(0xb57bf000, 4096)
V/AudioCache(  327): memcpy(0xaf41e000, 0xb57bf000, 4096)
V/AudioCache(  327): write(0xb57bf000, 4096)
V/AudioCache(  327): memcpy(0xaf41f000, 0xb57bf000, 4096)
V/AudioCache(  327): write(0xb57bf000, 4096)
V/AudioCache(  327): memcpy(0xaf420000, 0xb57bf000, 4096)
V/AudioCache(  327): write(0xb57bf000, 4096)
V/AudioCache(  327): memcpy(0xaf421000, 0xb57bf000, 4096)
V/AudioCache(  327): write(0xb57bf000, 4096)
V/AudioCache(  327): memcpy(0xaf422000, 0xb57bf000, 4096)
V/AudioCache(  327): write(0xb57bf000, 4096)
V/AudioCache(  327): memcpy(0xaf423000, 0xb57bf000, 4096)
V/AudioCache(  327): write(0xb57bf000, 4096)
V/AudioCache(  327): memcpy(0xaf424000, 0xb57bf000, 4096)
V/AudioCache(  327): write(0xb57bf000, 4096)
V/AudioCache(  327): memcpy(0xaf425000, 0xb57bf000, 4096)
V/AudioCache(  327): write(0xb57bf000, 4096)
V/AudioCache(  327): memcpy(0xaf426000, 0xb57bf000, 4096)
V/AudioCache(  327): write(0xb57bf000, 4096)
V/AudioCache(  327): memcpy(0xaf427000, 0xb57bf000, 4096)
V/AudioCache(  327): write(0xb57bf000, 4096)
V/AudioCache(  327): memcpy(0xaf428000, 0xb57bf000, 4096)
V/AudioCache(  327): write(0xb57bf000, 4096)
V/AudioCache(  327): memcpy(0xaf429000, 0xb57bf000, 4096)
V/AudioCache(  327): write(0xb57bf000, 4096)
V/AudioCache(  327): memcpy(0xaf42a000, 0xb57bf000, 4096)
V/AudioCache(  327): write(0xb57bf000, 4096)
V/AudioCache(  327): memcpy(0xaf42b000, 0xb57bf000, 4096)
V/AudioCache(  327): write(0xb57bf000, 4096)
V/AudioCache(  327): memcpy(0xaf42c000, 0xb57bf000, 4096)
V/AudioCache(  327): write(0xb57bf000, 4096)
V/AudioCache(  327): memcpy(0xaf42d000, 0xb57bf000, 4096)
V/AudioCache(  327): write(0xb57bf000, 4096)
V/AudioCache(  327): memcpy(0xaf42e000, 0xb57bf000, 4096)
V/AudioCache(  327): write(0xb57bf000, 4096)
,V/AudioCache(  327): memcpy(0xaf42f000, 0xb57bf000, 4096)
V/AudioCache(  327): write(0xb57bf000, 4096)
V/AudioCache(  327): memcpy(0xaf430000, 0xb57bf000, 4096)
V/AudioCache(  327): write(0xb57bf000, 4096)
V/AudioCache(  327): memcpy(0xaf431000, 0xb57bf000, 4096)
V/AudioCache(  327): write(0xb57bf000, 4096)
V/AudioCache(  327): memcpy(0xaf432000, 0xb57bf000, 4096)
V/AudioCache(  327): write(0xb57bf000, 4096)
V/AudioCache(  327): memcpy(0xaf433000, 0xb57bf000, 4096)
V/AudioCache(  327): write(0xb57bf000, 4096)
V/AudioCache(  327): memcpy(0xaf434000, 0xb57bf000, 4096)
V/AudioCache(  327): write(0xb57bf000, 4096)
V/AudioCache(  327): memcpy(0xaf435000, 0xb57bf000, 4096)
V/AudioCache(  327): write(0xb57bf000, 4096)
V/AudioCache(  327): memcpy(0xaf436000, 0xb57bf000, 4096)
V/AudioCache(  327): write(0xb57bf000, 4096)
V/AudioCache(  327): memcpy(0xaf437000, 0xb57bf000, 4096)
V/OMXCodec(  327): [OMX.google.vorbis.decoder] No more output data.
V/OMXCodec(  327): [OMX.google.vorbis.decoder] There is no more output data available, not calling fillOutputBuffer
V/AwesomePlayer(  327): postAudioEOS() 
V/AudioCache(  327): write(0xb57bf000, 280)
V/AudioCache(  327): memcpy(0xaf438000, 0xb57bf000, 280)
V/AwesomePlayer(  327): postStreamDoneEvent_l() -> status:-1011 
V/AwesomePlayer(  327): onStreamDone
V/AwesomePlayer(  327): MEDIA_PLAYBACK_COMPLETE
V/AudioCache(  327): notify(0xb1163840, 2, 0, 0)
V/AudioCache(  327): playback complete
V/AwesomePlayer(  327): pause_l() 
V/AudioCache(  327): notify(0xb1163840, 7, 0, 0)
V/AudioCache(  327): ignored
V/AwesomePlayer(  327): cancelPlayerEvents
V/AudioCache(  327): wait - success
V/MediaPlayerService(  327): return size 205080, sampleRate=48000, channelCount = 2, format = 1
D/AudioPlayer(  327): Pause Playback at 1068125
V/AwesomePlayer(  327): reset_l() 
V/AudioCache(  327): notify(0xb1163840, 8, 0, 0)
V/AudioCache(  327): ignored
V/AwesomePlayer(  327): cancelPlayerEvents
D/AudioPlayer(  327): reset: mPlaying=0 mReachedEOS=1 useOffload=0
V/OMXCodec(  327): [OMX.google.vorbis.decoder] stop mState=4
V/OMXCodec(  327): [OMX.google.vorbis.decoder] stopOmxComponent_l mState=4
V/OMXCodec(  327): [OMX.google.vorbis.decoder] setState mState=4 , newState=5
V/OMXCodec(  327): [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
V/OMXCodec(  327): [OMX.google.vorbis.decoder] onStateChange 2
V/OMXCodec(  327): [OMX.google.vorbis.decoder] Now Idle.
V/OMXCodec(  327): [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=0
V/OMXCodec(  327): [OMX.google.vorbis.decoder] freeing buffer 0xb1434510 on port 0
V/OMXCodec(  327): [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=3
V/OMXCodec(  327): [OMX.google.vorbis.decoder] freeing buffer 0xb14344c0 on port 0
V/OMXCodec(  327): [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=2
V/OMXCodec(  327): [OMX.google.vorbis.decoder] freeing buffer 0xb1434470 on port 0
V/OMXCodec(  327): [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=1
V/OMXCodec(  327): [OMX.google.vorbis.decoder] freeing buffer 0xb1434420 on port 0
V/OMXCodec(  327): [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=0
V/OMXCodec(  327): [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
V/OMXCodec(  327): [OMX.google.vorbis.decoder] freeing buffer 0xb119a1a0 on port 1
V/OMXCodec(  327): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=3
V/OMXCodec(  327): [OMX.google.vorbis.decoder] freeing buffer 0xb1434560 on port 1
V/OMXCodec(  327): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=2
V/OMXCodec(  327): [OMX.google.vorbis.decoder] freeing buffer 0xb14346a0 on port 1
V/OMXCodec(  327): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=1
V/OMXCodec(  327): [OMX.google.vorbis.decoder] freeing buffer 0xb14346f0 on port 1
V/OMXCodec(  327): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
V/OMXCodec(  327): [OMX.google.vorbis.decoder] setState mState=5 , newState=6
V/OMXCodec(  327): [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
V/OMXCodec(  327): [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
V/OMXCodec(  327): [OMX.google.vorbis.decoder] onStateChange 1
V/OMXCodec(  327): [OMX.google.vorbis.decoder] Now Loaded.
V/OMXCodec(  327): [OMX.google.vorbis.decoder] setState mState=6 , newState=1
V/OMXCodec(  327): [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
V/OMXCodec(  327): [OMX.google.vorbis.decoder] stopped in state 1
V/OMXCodec(  327): [OMX.google.vorbis.decoder] ~OMXCodec mstate =1
V/OMXCodec(  327): [OMX.google.vorbis.decoder] setState mState=1 , newState=0
D/AudioPlayer(  327): AudioPlayer releasing audio source
D/AudioPlayer(  327): AudioPlayer done releasing audio source
V/AwesomePlayer(  327): reset_l() 
V/AwesomePlayer(  327): cancelPlayerEvents
V/AwesomePlayer(  327): ~AwesomePlayer call
V/AwesomePlayer(  327): reset_l() 
V/AwesomePlayer(  327): cancelPlayerEvents
V/SoundPool( 6295): close(32)
V/SoundPool( 6295): pointer = 0x9ff37000, size = 205080, sampleRate = 48000, numChannels = 2
D/QRemote ( 6295): [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
D/QRemote ( 6295): [RemoteAppWidgetProvider.java:486:onUpdate()] oooooo 140510:RetrieveDevices is not complete. Just waiting
,D/QRemote ( 6295): [RemoteAppWidgetProvider.java:499:onUpdate()] oooooo 140514:alarm set after 5000ms:2876
I/UEI.SmartControl( 5791): Supports setup maps: true
E/QC-QMI  ( 6267): qmi_client [6267] 13: failed to locate client data
E/QC-QMI  (  481): qmuxd: RX on fd=32 returned error=0 errno[2:No such file or directory]
,E/QC-QMI  (  481): QMUX qmux_client_id=13 not found in qmux client list, unable to remove
,D/UEI.SmartControl( 5791): QS start statue = true Error code = 0
I/UEI.SmartControl( 5791): QS version = v2.7.10.1_RC1,
I/UEI.SmartControl( 5791): QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
I/UEI.SmartControl( 5791): ### init IR Blaster...
,D/serial_port( 5791): Configuring serial port
,E/UEI.SmartControl( 5791): UEIBLaster setting for 616
I/UEI.SmartControl( 5791): Setting serial record hearder size = 2
I/UEI.SmartControl( 5791): configuring settings for MAXQ616
I/UEI.SmartControl( 5791): Get version...
I/qcom-bluetooth( 6355): /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 58:3f:54:73:64:c0 
,D/UEI.SmartControl( 5791): serial port data available: 21
I/qcom-bluetooth( 6356): /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,D/UEI.SmartControl( 5791): MAXQ616 A2-X4 software.
I/UEI.SmartControl( 5791): IR Blaster version: 256702256704300002
,I/UEI.SmartControl( 5791): QS saving settings...
D/UEI.SmartControl( 5791): IR Blaster version: 25672567
D/UEI.SmartControl( 5791): serial port data available: 4
,I/bt_vendor( 6103): bluetooth satus is on
D/bt_hci_bdroid( 6103): preload
,D/bt_userial_mct( 6103): userial_open(port:0)
I/bt_vendor( 6103): bt-vendor : BT_VND_OP_USERIAL_OPEN
I/bt_vendor( 6103): Done intiailizing UART
I/bt_vendor( 6103): Done intiailizing UART
I/bt_userial_mct( 6103): CMD=66, EVT=66, ACL_Out=67, ACL_In=67
I/bt_vendor( 6103): Bluetooth Firmware and transport layer are initialized
D/bt_userial_mct( 6103): Entering userial_read_thread()
I/bt-btu  ( 6103): btu_task received preload complete event
W/bt-l2cap( 6103): L2CAP - L2CA_Register() called for PSM: 0x0001
W/bt-l2cap( 6103): L2CAP - L2CA_Register() called for PSM: 0x001f
I/UEI.SmartControl( 5791): Device manager: loading config....
,W/bt-l2cap( 6103): L2CAP - L2CA_Register() called for PSM: 0x0003
D/UEI.SmartControl( 5791): ----------- loading internal config...
W/ContextImpl( 5791): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
,E/UEI.SmartControl( 5791): Services init done
D/UEI.SmartControl( 5791): QS Service init finished
I/        ( 6103): BTE_InitTraceLevels -- TRC_HCI
I/        ( 6103): BTE_InitTraceLevels -- TRC_L2CAP
I/        ( 6103): BTE_InitTraceLevels -- TRC_RFCOMM
I/        ( 6103): BTE_InitTraceLevels -- TRC_AVDT
I/        ( 6103): BTE_InitTraceLevels -- TRC_AVRC
I/        ( 6103): BTE_InitTraceLevels -- TRC_A2D
I/        ( 6103): BTE_InitTraceLevels -- TRC_BNEP
I/        ( 6103): BTE_InitTraceLevels -- TRC_BTM
I/        ( 6103): BTE_InitTraceLevels -- TRC_HID_HOST
I/        ( 6103): BTE_InitTraceLevels -- TRC_GAP
I/        ( 6103): BTE_InitTraceLevels -- TRC_PAN
I/        ( 6103): BTE_InitTraceLevels -- TRC_SDP
I/        ( 6103): BTE_InitTraceLevels -- TRC_GATT
I/        ( 6103): BTE_InitTraceLevels -- TRC_SMP
I/        ( 6103): BTE_InitTraceLevels -- TRC_BTAPP
I/        ( 6103): BTE_InitTraceLevels -- TRC_BTIF
D/UEI.SmartControl( 5791): QS Service version name: 2.1.91
D/UEI.SmartControl( 5791): QS Service version code: 201091
D/UEI.SmartControl( 5791): Service requested: Control
E/UEI.SmartControl( 5791): Loading SETTINGS...
D/UEI.SmartControl( 5791): Request IControl service: devices are loaded...
I/QRemote ( 6295): [RemoteControlManager.java:183:onServiceConnected()] oooooo start
,D/UEI.SmartControl( 5791): Internal service binding...
I/UEI.SmartControl( 5791): ------ IControl API: 11
D/UEI.SmartControl( 5791): File observer start...
E/UEI.SmartControl( 5791): IR Port is disabled: false
D/UEI.SmartControl( 5791): Starting file observer...
I/UEI.SmartControl( 5791): Registering callback...
I/UEI.SmartControl( 5791): ------ IControl API: 19
I/UEI.SmartControl( 5791): Registering Services Ready callback...
D/UEI.SmartControl( 5791): -- Open brand translation xml: brands_translations_ko
W/bt-btm  ( 6103): btm_decode_ext_features_page Secure conn Controller support Enabled
E/bt-btm  ( 6103): BTM_SecRegister:p_cb_info->p_le_callback == 0xa01d1061 
E/bt-btm  ( 6103): BTM_SecRegister: btm_cb.api.p_le_callback = 0xa01d1061 
,E/bt-btif ( 6103): Calling BTA_HhEnable
E/bt-btif ( 6103): btif_storage_get_adapter_property service_mask:0x2140040
D/BluetoothAdapterProperties( 6103): Address is:58:3F:54:73:64:C0
D/BluetoothManagerService( 1029): Bluetooth Adapter name changed to G3-1
D/BluetoothAdapterProperties( 6103): Name is: G3-1
D/BluetoothManagerService( 1029): Stored Bluetooth name: G3-1
W/bt-l2cap( 6103): L2CAP - L2CA_Register() called for PSM: 0x0019
W/bt-l2cap( 6103): L2CAP - L2CA_Register() called for PSM: 0x0017
W/bt-l2cap( 6103): L2CAP - L2CA_Register() called for PSM: 0x001b
W/bt-l2cap( 6103): L2CAP - L2CA_Register() called for PSM: 0x0011
W/bt-l2cap( 6103): L2CAP - L2CA_Register() called for PSM: 0x0013
D/BluetoothAdapterProperties( 6103): Scan Mode:20
D/BluetoothAdapterProperties( 6103): Discoverable Timeout:120
D/bt_hci_bdroid( 6103): postload
D/bt_hci_bdroid( 6103): Used up Tx Cmd credits
D/bt_hci_bdroid( 6103): Used up Tx Cmd credits
D/bt_hci_bdroid( 6103): Used up Tx Cmd credits
W/bt-l2cap( 6103): L2CAP - L2CA_Register() called for PSM: 0x000f
D/bt_hci_bdroid( 6103): Used up Tx Cmd credits
E/bt_mct  ( 6103): hci lib postload completed
,W/bt-smp  ( 6103): Key(LSB ~ MSB) = 0a 3c a6 fe eb 17 6a 79 a6 1f 0a 0b f9 50 a0 5f 
W/bt-smp  ( 6103): Plain text(LSB ~ MSB) = a6 60 5f 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 6103): Encrypted text(LSB ~ MSB) = 23 59 d1 7d 9e 70 2a ca 59 fa 09 e7 ea c0 23 e6 
W/bt-btm  ( 6103): Stopping oneshot timer
D/bte_conf( 6103): Device ID record 1 : primary
D/bte_conf( 6103):   vendorId            = 00c4
D/bte_conf( 6103):   vendorIdSource      = 0001
D/bte_conf( 6103):   product             = 13a1
D/bte_conf( 6103):   version             = 1000
D/bte_conf( 6103):   clientExecutableURL = 
D/bte_conf( 6103):   serviceDescription  = 
D/bte_conf( 6103):   documentationURL    = 
D/bte_conf( 6103): bte_load_did_conf no section named DID2.
I/UEI.SmartControl( 5791): Notify AllClients services are ready: 0
I/QRemote ( 6295): [RemoteControlManager.java:660:QSSetupIsReady()] oooooo 140517:sdkIsReady callback... get functions. Result:0
D/BluetoothPanServiceJni( 6103): control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
D/BluetoothAdapterState( 6103): CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
D/BluetoothAdapterProperties( 6103): ScanMode =  20
D/BluetoothAdapterProperties( 6103): State =  11
D/BluetoothAdapterProperties( 6103): mDiscoverableTimeout = 120
V/LGBluetoothServiceAdapter( 6103): [BTUI] state:11, scanmode:20, timeout:120
D/BluetoothAdapterProperties( 6103): Setting state to 12
I/BluetoothAdapterState( 6103): Bluetooth adapter state changed: 11-> 12
,W/sh      ( 6364): type=1400 audit(0.0:161): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
W/sh      ( 6364): type=1400 audit(0.0:162): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
D/BluetoothManagerService( 1029): Message: 60
D/BluetoothManagerService( 1029): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
D/BluetoothManagerService( 1029): Broadcasting onBluetoothStateChange(true) to 5 receivers.
D/BluetoothHeadset( 1029): onBluetoothStateChange: up=true
D/btif_config_util( 6103): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,D/QRemote ( 6295): [RemoteControlManager.java:388:handleMessage()] oooooo 140510:START_SESSION
D/QRemote ( 6295): [RemoteControlManager.java:394:handleMessage()] oooooo 140510:send retrieve msg
D/QRemote ( 6295): [RemoteControlManager.java:322:handleMessage()] oooooo 140510:handler call retrieveDevices
D/QRemote ( 6295): [RemoteControlManager.java:336:retrieveDevices()] oooooo retrieveDevices: start
I/UEI.SmartControl( 5791): ------ IControl API: 8
,I/BluetoothAdapterState( 6103): Entering On State
W/bt-smp  ( 6103): Key(LSB ~ MSB) = 0a 3c a6 fe eb 17 6a 79 a6 1f 0a 0b f9 50 a0 5f 
W/bt-smp  ( 6103): Plain text(LSB ~ MSB) = be aa 50 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 6103): Encrypted text(LSB ~ MSB) = a3 6f 06 3d 2f e2 d3 be 70 3e 4d ae 97 ae 8c 16 
W/bt-btm  ( 6103): Stopping oneshot timer
D/QRemote ( 6295): [RemoteControlManager.java:340:retrieveDevices()] oooooo retrieveDevices: 0
D/QRemote ( 6295): [RemoteControlManager.java:345:retrieveDevices()] oooooo retrieveDevices complete:true
D/QRemote ( 6295): [RemoteControlManager.java:353:retrieveDevices()] oooooo retrieveDevices: notifyDataSetChanged()
D/QRemote ( 6295): [QRemoteApplication.java:145:onRemoteControlStateChanged()] oooooo onRemoteControlStateChanged called in QRemoteApp
D/BluetoothHeadset( 1871): onBluetoothStateChange: up=true
D/UEI.SmartControl( 5791): -----service ready thread exits
D/BluetoothHeadset( 1871): onBluetoothStateChange: up=true
D/BluetoothA2dp( 1029): onBluetoothStateChange: up=true
D/BluetoothHeadset( 1871): onBluetoothStateChange: up=true
D/LGBluetoothServiceAdapter( 6103): [BTUI] OnState
D/LGBluetoothServiceAdapter( 6103): [BTUI]         global_name: G3-1
D/LGBluetoothServiceAdapter( 6103): [BTUI]         local_name: G3-1
D/BluetoothAdapterService( 6103): [BTUI] autoConnect() : not allowed
D/QRemote ( 6295): [QRemoteApplication.java:158:onRemoteControlStateChanged()] oooooo Widget count is [1]. send broadcast
D/QRemote ( 6295): [QRemoteApplication.java:160:onRemoteControlStateChanged()] oooooo Widget[0]:3
E/BluetoothManagerService( 1029): Fail to bind to: Intent { act=android.bluetooth.IQBluetooth }
D/BluetoothManagerService( 1029): BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
,D/BluetoothManagerService( 1029): Bluetooth State Change Intent: 11 -> 12
W/bt-smp  ( 6103): Key(LSB ~ MSB) = 0a 3c a6 fe eb 17 6a 79 a6 1f 0a 0b f9 50 a0 5f 
W/bt-smp  ( 6103): Plain text(LSB ~ MSB) = dd be 63 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 6103): Encrypted text(LSB ~ MSB) = 06 40 58 44 cb 91 b7 44 6f 3c 18 13 79 3f 84 88 
W/bt-btm  ( 6103): Stopping oneshot timer
D/BluetoothManagerService( 1029): Message: 40
D/BluetoothManagerService( 1029): MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
D/LGBluetoothAPIService( 1964): [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
D/LGBluetoothAPIService( 1964): Message: 1
D/LGBluetoothAPIService( 1964): MESSAGE_BOOT_COMPLETED
I/[SystemUI]BluetoothHandler( 1462): Receive : BluetoothAdapter.ACTION_STATE_CHANGED
D/QRemote ( 6295): [QRemoteApplication.java:188:onRemoteControlStateChanged()] oooooo 140526:onRemoteControlStateChanged&sdkIsReady. stop Service
,I/BluetoothMapService( 6103): onReceive: android.bluetooth.adapter.action.STATE_CHANGED
D/BluetoothMapService( 6103): STATE_ON
,D/LGBluetoothDeviceModeControllManager( 6103): [BTUI] checkDeviceModeAndSet, sinkMode : false
V/QRemote ( 6295): [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
D/QRemote ( 6295): [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
E/QRemote ( 6295): [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
D/QRemote ( 6295): [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
,D/QRemote ( 6295): [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
I/LGBluetoothAPIService( 1964): [BTUI] LGBluetoothAPIService Binding Success
W/bt-smp  ( 6103): Key(LSB ~ MSB) = 0a 3c a6 fe eb 17 6a 79 a6 1f 0a 0b f9 50 a0 5f 
W/bt-smp  ( 6103): Plain text(LSB ~ MSB) = 62 45 71 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 6103): Encrypted text(LSB ~ MSB) = 9a 8c 0f 46 54 f8 ab 2d d1 4c ee 79 c9 4a 68 e5 
W/bt-btm  ( 6103): Stopping oneshot timer
D/QRemote ( 6295): [RemoteAppWidgetProvider.java:506:onUpdate()] oooooo 140510:RetrieveDevices complete. Start loading
D/QRemote ( 6295): [RemoteAppWidgetProvider.java:508:onUpdate()] oooooo 140510:appWidgetIds[0]:3 loading
D/QRemote ( 6295): [RemoteAppWidgetManager.java:41:startLoading()] oooooo 140518:widgetId[3] loading start at [1449671438960]
D/LGBluetoothAPIServer( 6103): [BTUI] onCreate()
D/LGBluetoothAPIServer( 6103): [BTUI] onBind()
V/BluetoothMapService( 6103): Handler(): got msg=1
D/LGBluetoothAPIService( 1964): [BTUI] LGBluetoothAPIServiceConnection: connected to LGBluetoothAPIAdapter
D/LGBluetoothAPIService( 1964): Message: 100
D/LGBluetoothAPIService( 1964): MESSAGE_BLUETOOTH_SERVICE_CONNECTED
D/BluetoothMapMasInstance( 6103): Map Service startRfcommSocketListener
D/QRemote ( 6295): [QRemoteService.java:207:onDestroy()] oooooo 140526:onDestroy
I/qcom-bt-wlan-coex( 6376): /system/etc/init.qcom.coex.sh: btwlancoex/abtfilt not available 
D/BluetoothMapMasInstance( 6103): MAS initSocket()
D/BluetoothMapMasInstance( 6103):   masId = 00
D/BluetoothMapMasInstance( 6103):   msgTypes = 0e
D/BluetoothMapMasInstance( 6103):   masName = SMS/MMS
D/BluetoothMapMasInstance( 6103):   SDP string = 000eSMS/MMS
,D/BluetoothManagerService( 1029): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
W/ContextImpl( 6141): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
W/BluetoothAdapter( 6103): getBluetoothService() called with no BluetoothManagerCallback
W/bt-smp  ( 6103): Key(LSB ~ MSB) = 0a 3c a6 fe eb 17 6a 79 a6 1f 0a 0b f9 50 a0 5f 
W/bt-smp  ( 6103): Plain text(LSB ~ MSB) = 4f 84 6f 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 6103): Encrypted text(LSB ~ MSB) = b5 8e e8 89 d1 d7 6c 8f da 28 02 8b 17 99 6c 2e 
W/bt-btm  ( 6103): Stopping oneshot timer
D/LGBluetoothServiceAdapter( 6103): [BTUI] createSocketChannel FD=73 mFd=0
V/BluetoothMapMasInstance( 6103): Succeed to create listening socket 
D/BluetoothMapMasInstance( 6103): Accepting socket connection...
D/BluetoothAdapterService( 6103): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@7038f05
,V/BluetoothPbapService( 6103): Pbap Service onCreate
V/BluetoothPbapService( 6103): Starting PBAP service
D/LGBluetoothPbapAdapter( 6103): [BTUI] getInstance : create
V/BluetoothPbapService( 6103): action: android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothPbapService( 6103): state: 12
V/BluetoothPbapReceiver( 6103): PbapReceiver onReceive 
V/BluetoothPbapReceiver( 6103): ***********action = android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothPbapReceiver( 6103): ***********state = 12
V/BluetoothPbapService( 6103): Handler(): got msg=1
V/BluetoothPbapService( 6103): Pbap Service startRfcommSocketListener
V/BluetoothPbapService( 6103): Pbap Service initSocket
D/BluetoothManagerService( 1029): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
W/BluetoothAdapter( 6103): getBluetoothService() called with no BluetoothManagerCallback
D/QRemote ( 6295): [RemoteAppWidgetManager.java:239:doInBackground()] oooooo 140407:doinBack arr:0
,D/LGBluetoothServiceAdapter( 6103): [BTUI] createSocketChannel FD=75 mFd=73
V/BluetoothPbapService( 6103): Succeed to create listening socket 
V/BluetoothPbapService( 6103): Accepting socket connection...
V/QRemote ( 6295): [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.widget_ui_update
E/QRemote ( 6295): [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
D/QRemote ( 6295): [RemoteAppWidgetProvider.java:171:onReceive()] oooooo total:0
D/QRemote ( 6295): [RemoteAppWidgetProvider.java:172:onReceive()] oooooo selected:0
D/QRemote ( 6295): [RemoteAppWidgetProvider.java:173:onReceive()] oooooo arr:[]
D/QRemote ( 6295): [RemoteAppWidgetProvider.java:174:onReceive()] oooooo appWidgetId:3
D/QRemote ( 6295): [RemoteAppWidgetProvider.java:815:updateRemoteViews()] oooooo UpdateRemoteViews3:widgetId:3
D/QRemote ( 6295): [RemoteAppWidgetProvider.java:986:updateRemoteViews()] oooooo updateAppWidget5:widgetId:3]
,D/LocalBluetoothProfileManager( 6141): Adding local A2DP profile
D/BluetoothManagerService( 1029): Message: 30
D/LocalBluetoothProfileManager( 6141): Adding local HEADSET profile
D/BluetoothManagerService( 1029): Message: 30
D/BluetoothManagerService( 1029): Message: 30
I/dhcpcd  ( 6294): wlan0: acknowledged 192.168.1.125 from 192.168.1.1
,D/BluetoothManagerService( 1029): Message: 30
D/LocalBluetoothProfileManager( 6141): Adding local MAP profile
D/BluetoothMap( 6141): Create BluetoothMap proxy object
D/BluetoothManagerService( 1029): Message: 30
D/BluetoothManagerService( 1029): Message: 30
,D/LocalBluetoothProfileManager( 6141): LocalBluetoothProfileManager construction complete
V/BluetoothPbapService( 6103): Pbap Service onBind
I/dhcpcd  ( 6294): wlan0: leased 192.168.1.125 for 86400 seconds
D/dhcpcd  ( 6294): wlan0: adding IP address 192.168.1.125/24
D/dhcpcd  ( 6294): wlan0: adding route to 192.168.1.0/24
D/dhcpcd  ( 6294): wlan0: adding default route via 192.168.1.1
D/LGBluetoothUserBindClient( 6141): [BTUI] initUserBindClient
E/WifiStateMachine( 1029):  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
D/dhcpcd  ( 6294): wlan0: writing lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
E/WifiStateMachine( 1029):  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1029):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1029):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
D/dhcpcd  ( 6294): getUsingAPMacAddress: c0:ff:d4:d3:aa:48 , return 1
D/dhcpcd  ( 6294): write_lease_ext: /data/misc/dhcp/dhcpcd-wlan0-c0:ff:d4:d3:aa:48.lease2
D/dhcpcd  ( 6294): wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason REBOOT
E/WifiStateMachine( 1029):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1029):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
D/ConnectivityService( 1029): Update of LinkProperties for NetworkAgentInfo [WIFI () - 100]; created=false
D/BluetoothAdapterProperties( 6103): Discoverable Timeout:120
D/LGBluetoothDeviceModeControllManager( 6103): adapterPropertyChangedCallback on  LGAdapter : do nothing - 9
W/ContextImpl( 6141): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.android.settings.bluetooth.LGBluetoothUserBindClient.initUserBindClient:90 com.android.settings.bluetooth.LGBluetoothUserBindClient.<init>:55 com.android.settings.bluetooth.LGBluetoothUserBindClient.getInstance:47 
D/BluetoothAdapterProperties( 6103): Scan Mode:21
D/LGBluetoothDeviceModeControllManager( 6103): getDeviceMode  deviceMode 0
D/DockEventReceiver( 6141): finishStartingService: stopping service
,D/BluetoothA2dp( 6141): Proxy object connected
D/A2dpProfile( 6141): Bluetooth service connected
D/BluetoothHeadset( 6141): Proxy object connected
D/HeadsetProfile( 6141): Bluetooth service connected
D/BluetoothInputDevice( 6141): Proxy object connected
D/HidProfile( 6141): Bluetooth service connected
D/BluetoothPan( 6141): BluetoothPAN Proxy object connected
D/PanProfile( 6141): Bluetooth service connected
D/BluetoothMap( 6141): Proxy object connected
D/MapProfile( 6141): Bluetooth service connected
D/BluetoothMap( 6141): getConnectedDevices()
V/BluetoothMapService( 6103): getConnectedDevices()
D/BluetoothPbap( 6141): Proxy object connected
D/PbapServerProfile( 6141): Bluetooth service connected
D/LGBluetoothUserBindClient( 6141): [BTUI] onServiceConnected
D/BluetoothPermissionRequest( 6141): onReceive
D/LGBluetoothFeatureConfig( 6141): isPrivacyLogsEnabled : true
D/LGBluetoothUtils( 6141): [BTUI] FileNotFound: readProperty
,D/LGBluetoothResetSettingReceiver( 6141): return without doing reset settings.
I/ActivityManager( 1029): Killing 5771:com.google.android.apps.docs/u0a61 (adj 15): empty #17
W/libprocessgroup( 1029): failed to open /acct/uid_10061/pid_5771/cgroup.procs: No such file or directory
V/BluetoothOppReceiver( 6103): Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_ON
,I/LGBluetoothOppAdapter( 6103): [BTUI] startOppService()
V/BluetoothOppManager( 6103): restoreApplicationData! falsefalsenullnull
,D/LGBluetoothFeatureConfig( 6103): isPrivacyLogsEnabled : true
,V/BtOppService( 6103): onCreate
V/BluetoothOppNotification( 6103): send message
,V/BtOppService( 6103): Starting RfcommListener
,D/BluetoothOppPreference( 6103): Dumping Names:  
D/BluetoothOppPreference( 6103): {}
D/BluetoothOppPreference( 6103): Dumping Channels:  
D/BluetoothOppPreference( 6103): {}
V/BtOppService( 6103): onStartCommand
,V/BluetoothFtpReceiver( 6103): BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothFtpReceiver( 6103): BluetoothFtpReceiver Start Service
V/BluetoothOppNotification( 6103): new notify threadi!
V/BluetoothOppNotification( 6103): send delay message
V/BtOppService( 6103): start RfcommListener
V/BtOppService( 6103): pendingUpdate is true keepUpdateThread is false sListenStarted is true
V/BluetoothOppProvider( 6103): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
V/BluetoothOppProvider( 6103): starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
,V/BtOppService( 6103): Deleted complete outbound shares, number =  0
V/BtOppService( 6103): RfcommListener started
V/BtOppRfcommListener( 6103): Starting RFCOMM listener....
D/BluetoothManagerService( 1029): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
V/BluetoothOppProvider( 6103): created cursor android.database.sqlite.SQLiteCursor@982f237 on behalf of 
W/BluetoothAdapter( 6103): getBluetoothService() called with no BluetoothManagerCallback
D/LGBluetoothServiceAdapter( 6103): [BTUI] createSocketChannel FD=79 mFd=75
V/BtOppRfcommListener( 6103): Started RFCOMM listener....
I/BtOppRfcommListener( 6103): Accept thread started.
V/BtOppRfcommListener( 6103): Accepting connection...
V/BtOppService( 6103): Deleted complete inbound failed shares, number = 0
V/BluetoothOppProvider( 6103): created cursor android.database.sqlite.SQLiteCursor@1813a4 on behalf of 
V/BluetoothOppProvider( 6103): starting query, database is not null; projection[0] is _id; selection is direction=1 AND status=200 AND visibility=1; selectionArgs is null; sort is _id.
V/BtOppService( 6103): pendingUpdate is false keepUpdateThread is false sListenStarted is true
,V/BluetoothOppProvider( 6103): created cursor android.database.sqlite.SQLiteCursor@3514850d on behalf of 
V/BluetoothOppNotification( 6103): mUpdateCompleteNotification = true
V/BluetoothOppProvider( 6103): starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
V/BluetoothOppProvider( 6103): created cursor android.database.sqlite.SQLiteCursor@f54ccc2 on behalf of 
V/BluetoothOppNotification( 6103): outbound: succ-0  fail-0
D/BluetoothAdapterService( 6103): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@7038f05
V/BluetoothFtpService( 6103): Ftp Service onCreate
I/BluetoothFtpService( 6103): Ftp Service onCreate
V/BluetoothFtpService( 6103): Ftp Service onStartCommand
V/BluetoothFtpService( 6103): action: android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothFtpService( 6103): Starting Listening on sockets
V/BluetoothSapReceiver( 6103): [BTUI] checkServiceStart
V/BluetoothSapReceiver( 6103): [BTUI] region:EU country:EU
,V/BluetoothSapReceiver( 6103): SapReceiver onReceive 
V/BluetoothSapReceiver( 6103): action = android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothSapReceiver( 6103):  Bluetooth Adapter state = 12
V/BluetoothSapReceiver( 6103): Calling SAP service start service with action = null
V/BluetoothOppNotification( 6103): outbound notification was removed.
,V/BluetoothOppProvider( 6103): starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
V/BtOppService( 6103): ContentObserver received notification
V/BtOppService( 6103): ContentObserver received notification
V/BluetoothFtpService( 6103): Handler(): got msg=1
V/BtOppService( 6103): pendingUpdate is true keepUpdateThread is false sListenStarted is true
V/BluetoothFtpService( 6103): Ftp Service startRfcommSocketListener
V/BluetoothFtpService( 6103): Ftp Service initSocket
V/BluetoothOppProvider( 6103): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
D/AuthorizationBluetoothService( 2130): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
V/BluetoothOppProvider( 6103): created cursor android.database.sqlite.SQLiteCursor@3794c610 on behalf of 
V/BluetoothOppNotification( 6103): inbound: succ-0  fail-0
D/BluetoothManagerService( 1029): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,W/BluetoothAdapter( 6103): getBluetoothService() called with no BluetoothManagerCallback
V/BluetoothOppProvider( 6103): created cursor android.database.sqlite.SQLiteCursor@3f116509 on behalf of 
D/LGBluetoothServiceAdapter( 6103): [BTUI] createSocketChannel FD=82 mFd=79
V/BluetoothOppNotification( 6103): update too frequent, put in queue
,V/BluetoothFtpService( 6103): Succeed to create listening socket on channel 20
V/BtOppService( 6103): pendingUpdate is false keepUpdateThread is false sListenStarted is true
V/BluetoothOppNotification( 6103): inbound notification was removed.
V/BluetoothOppProvider( 6103): starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
V/BluetoothFtpService:RfcommSocketAcceptThread( 6103): Run Accept thread
,D/BluetoothAdapterService( 6103): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@7038f05
V/BluetoothSapService( 6103): Sap Service onCreate
D/sensors_hal_Time( 1029): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1029): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1029): tsOffsetIs: Apps: 286309826768; DSPS: 9522534; Offset : -4305892376
,I/art     ( 1029): Explicit concurrent mark sweep GC freed 52226(2MB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 44MB/66MB, paused 1.897ms total 88.759ms
,V/BluetoothOppProvider( 6103): created cursor android.database.sqlite.SQLiteCursor@19e8333c on behalf of 
V/BluetoothSapService( 6103): action: android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothSapService( 6103): state: 12
V/BluetoothSapService( 6103): Starting SAP server process
V/BluetoothSapService( 6103): SAP Service startRfcommListenerThread
,W/sapd    ( 6416): type=1400 audit(0.0:163): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
W/sapd    ( 6416): type=1400 audit(0.0:164): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
V/BluetoothSapService( 6103): Sap Service initRfcommSocket
E/WifiStateMachine( 1029):  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0 v4
D/BluetoothManagerService( 1029): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
E/WifiStateMachine( 1029):  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4
W/BluetoothAdapter( 6103): getBluetoothService() called with no BluetoothManagerCallback
E/WifiStateMachine( 1029):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0 v4
E/WifiStateMachine( 1029):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4
V/BT_SAP  ( 6416): Event pipe created
V/BT_SAP  ( 6416): create_server_socket qcom.sap.server
V/BT_SAP  ( 6416): created socket fd 6
E/WifiStateMachine( 1029):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4
V/BluetoothSapService( 6103): Succeed to create listening socket 
V/BluetoothSapService( 6103): Accepting socket connection...
,E/WifiStateMachine( 1029):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0 v4
D/ConnectivityService( 1029): Update of LinkProperties for NetworkAgentInfo [WIFI () - 100]; created=false
D/DhcpStateMachine( 1029): DHCPV4 succeeded on wlan0
,D/LgDhcpStateMachineHelper( 1029): CheckDhcpDirectory [Lease File Count] : 3
,V/LgDhcpStateMachineHelper( 1029): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
,D/LgDhcpStateMachineHelper( 1029): checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.125
V/LgDhcpStateMachineHelper( 1029): Add DhcpResults: IP address 192.168.1.125/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 86400 seconds
V/DhcpStateMachine( 1029): Current State is mWaitBeforeStartState.
V/LgDhcpStateMachineHelper( 1029): bShouldSendDhcpAction Result: true
D/DhcpStateMachine( 1029): DHCP Start/Renew wake lock is released.
D/DhcpStateMachine( 1029): RunningState
E/WifiStateMachine( 1029):  ObtainingIpState CMD_POST_DHCP_ACTION 1 0 OK  v4
E/WifiStateMachine( 1029):  L2ConnectedState CMD_POST_DHCP_ACTION 1 0 OK  v4
D/WifiNative-wlan0( 1029): doBoolean: DRIVER BTCOEXMODE 2
I/wpa_supplicant( 6150): wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
D/WifiNative-wlan0( 1029): DRIVER BTCOEXMODE 2: returned true
D/WifiNative-wlan0( 1029): doBoolean: DRIVER SETSUSPENDMODE 1
I/wpa_supplicant( 6150): wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 1
D/LGWifiP2pService( 1029): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1029): P2pEnabledState{ when=-2ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0( 1029): DRIVER SETSUSPENDMODE 1: returned true
D/WifiNative-wlan0( 1029): doBoolean: SET ps 1
D/WifiNative-wlan0( 1029): SET ps 1: returned true
D/ConnectivityService( 1029): Update of LinkProperties for NetworkAgentInfo [WIFI () - 100]; created=false
,E/WifiStateMachine( 1029):  ObtainingIpState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
E/WifiStateMachine( 1029):  L2ConnectedState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
E/WifiStateMachine( 1029): WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
D/ConnectivityService( 1029): ignoring duplicate network state non-change
W/Settings( 1029): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1029): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1029): NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
D/ConnectivityService( 1029): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
I/StatusBar.NetworkController( 1462): networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1462): mWifiConnected = false, mWifiLevel = 0
,D/ConnectivityService( 1029): Adding iface wlan0 to network 100
E/WifiStateMachine( 1029): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
D/StatusBar.NetworkController( 1462): refreshViews: Data not connected!! Set no data type icon / Roaming
I/StatusBar.NetworkController( 1462): networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1462): mWifiConnected = false, mWifiLevel = 0
W/Settings( 1029): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1029): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1029): NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
D/WifiHS20( 1029): [PASSPOINT] passpointNotification: hs20AP list is checked
,D/StatusBar.NetworkController( 1462): refreshViews: Data not connected!! Set no data type icon / Roaming
,W/Settings( 1029): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1029): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1029): NETWORK_STATE_CHANGED_ACTION [CONNECTED]
D/WifiHS20( 1029): [PASSPOINT] passpointNotification: hs20AP list is checked
D/PostponalbeReceiver( 5113): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
I/StatusBar.NetworkController( 1462): networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
V/WfdStateTracker( 1964): handleWifiStateChangedEvent: 1
I/StatusBar.NetworkController( 1462): mWifiConnected = true, mWifiLevel = 3
W/Settings( 1029): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1029): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1029): NETWORK_STATE_CHANGED_ACTION [CONNECTED]
,D/StatusBar.NetworkController( 1462): refreshViews: Data not connected!! Set no data type icon / Roaming
,E/ConnectivityService( 1029): Unexpected mtu value: 0, wlan0
D/ConnectivityService( 1029): Adding Route [fe80::/64 -> :: wlan0] to network 100
D/ConnectivityService( 1029): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 100
D/ConnectivityService( 1029): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 100
D/ConnectivityService( 1029): addLocalRoutetoDefaultNetwork
D/ConnectivityService( 1029): defaultNAI is null or Wi-Fi no need to add Loacal route to default network. WiFi netid = 100
D/ConnectivityService( 1029): Setting Dns servers for network 100 to [/192.168.1.1]
D/Nat464Xlat( 1029): requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
D/ConnectivityService( 1029): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService( 1029): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 100]
,D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1029): DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1029): Connected
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1029): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1029): Checking http://clients3.google.com/generate_204 on "NG700"
I/StatusBar.NetworkController( 1462): networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1462): mWifiConnected = true, mWifiLevel = 3
D/StatusBar.NetworkController( 1462): refreshViews: Data not connected!! Set no data type icon / Roaming
D/ConnectivityService( 1029): rematching NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService( 1029):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService( 1029):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1029):     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
D/ConnectivityService( 1029):   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1029):     satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:true
D/ConnectivityService( 1029): currentScore = 0, newScore = 20
D/ConnectivityService( 1029):    accepting network in place of null
D/ConnectivityService( 1029): sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/libc-netbsd(  323): res_queryN name = clients3.google.com, class = 1, type = 28
D/ConnectivityService( 1029): Setting tx/rx TCP buffers to 524288,1048576,2097152,262144,524288,1048576
D/TelephonyNetworkFactory-1( 1871): new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/TelephonyNetworkFactory-1( 1871):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
D/WIFI    ( 1029): new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    ( 1029):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
V/WiFiOffLoadBroadcast( 6141): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
E/ConnectivityService( 1029): [lg_data] Adding agent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.125/24,fe80::c69a:2ff:fe7b:60ac/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
,D/CSLegacyTypeTracker( 1029): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
D/ConnectivityService( 1029): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/LocSvc_java( 1029): Sending msg: 4 arg1:1 arg2:1
D/LocSvc_java( 1029): getAGpsConnectionInfo connType - 4
D/LocSvc_java( 1029): updateNetworkState connTyp: 4 available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java( 1029): ignore wifi update if we are not in OPENING or CLOSING
D/LocSvc_java( 1029): Sending msg: 5 arg1:0 arg2:1
D/libc-netbsd(  323): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  323): res_queryN name = 2.android.pool.ntp.org, class = 1, type = 1
D/libc-netbsd(  323): res_queryN name = 2.android.pool.ntp.org., class = 1, type = 1
D/ConnectivityService( 1029): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/CSLegacyTypeTracker( 1029): [e] list.add(nai) empty : false size: 1
D/ConnectivityService( 1029): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.125/24,fe80::c69a:2ff:fe7b:60ac/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
D/DSQN    ( 1029): DNSproblemNotiEnabled is disabled ignore DNS fail CB
D/ConnectivityService( 1029): validation of new default Network = false
D/ConnectivityService( 1029): Default network via Wi-Fi connected. start DSQN
D/DSQN    ( 1029): enableDataServiceNotify 
D/DSQN    ( 1029): start dsqn bin
D/libc-netbsd(  323): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  323): res_queryN name = europe.pool.ntp.org, class = 1, type = 1
D/WiFiOffLoadBroadcast( 6141): MCCMNC not supported: null
D/ConnectivityService( 1029): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService( 1029):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1029):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1029): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityManager.CallbackHandler( 1462): CM callback handler got msg 524290
W/dsqn    ( 6425): type=1400 audit(0.0:165): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
W/dsqn    ( 6425): type=1400 audit(0.0:166): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,V/NetworkPolicy( 1029): [LG_RESTRICTED] checkMobilePolicy_type()
,D/QRemote ( 6295): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6295): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 6295): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
E/DSQN    ( 6425): DSQN ssw
,D/PostponalbeReceiver( 5113): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
D/TelephonyIcons( 1462): null signal icon name: drawable/stat_sys_signal_null
D/StatusBar.NetworkController( 1462): refreshViews: Data not connected!! Set no data type icon / Roaming
D/StatusBar.NetworkController( 1462): refreshViews: Data not connected!! Set no data type icon / Roaming
D/libc-netbsd(  323): res_queryN name = clients3.google.com, class = 1, type = 1
V/WiFiOffLoadBroadcast( 6141): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6141): MCCMNC not supported: null
D/QRemote ( 6295): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6295): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 6295): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
D/PostponalbeReceiver( 5113): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,I/PCSuite ( 6215): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
D/PCSuite ( 6215): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 6141): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/libc-netbsd(  323): res_queryN name = clients3.google.com succeed
D/WiFiOffLoadBroadcast( 6141): MCCMNC not supported: null
,D/QRemote ( 6295): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6295): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,D/QRemote ( 6295): [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
,I/QRemote ( 6295): [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
I/QRemote ( 6295): [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
D/LGDataListener(  323): argv[0]=dsqncommand
D/LGDataListener(  323): argv[1]=wlan0
D/LGDataListener(  323): argv[2]=1
D/LGDataListener(  323): notifyDSQN DSQN STARTMONITOR wlan0 1
D/DSQN    ( 1029): DSQM DsqnNotification wlan0  1
D/DSQN    ( 1029): start to monitor internet connection
D/PostponalbeReceiver( 5113): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
D/libc-netbsd(  323): res_queryN name = europe.pool.ntp.org succeed
I/PCSuite ( 6215): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
,D/PCSuite ( 6215): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 6141): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1029): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Wed, 09 Dec 2015 14:30:40 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1449671439613], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1449671439593]}
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1029): Don't send network conditions - lacking user consent.
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1029): Validated
,D/ConnectivityService( 1029): Validated NetworkAgentInfo [WIFI () - 100]
D/WiFiOffLoadBroadcast( 6141): MCCMNC not supported: null
D/ConnectivityService( 1029): rematching NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService( 1029):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService( 1029):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1029):     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
D/ConnectivityService( 1029): Network NetworkAgentInfo [WIFI () - 100] was already satisfying request 1. No change.
D/ConnectivityService( 1029): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService( 1029):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1029):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1029): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityManager.CallbackHandler( 1462): CM callback handler got msg 524290
D/ConnectivityService( 1029): sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    ( 1029): new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1029): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
D/WIFI    ( 1029):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/TelephonyNetworkFactory-1( 1871): new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/TelephonyNetworkFactory-1( 1871):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
D/QRemote ( 6295): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,D/QRemote ( 6295): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
D/QRemote ( 6295): [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
I/QRemote ( 6295): [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
I/QRemote ( 6295): [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
D/LocSvc_java( 1029): NTP server : europe.pool.ntp.org
D/LocSvc_java( 1029): NTP server returned: 1449671440579 (Wed Dec 09 15:30:40 GMT+01:00 2015) reference: 286607 certainty: 24 system time offset: 930
D/LocSvc_java( 1029): Sending msg: 10 arg1:0 arg2:1
,D/LocSvc_java( 1029): reportXtraServer 
D/LocSvc_java( 1029):  server1=http://xtra2.gpsOneXTRA.net/xtra2.bin
D/LocSvc_java( 1029):  server2=http://xtra3.gpsOneXTRA.net/xtra2.bin
D/LocSvc_java( 1029):  server3=
D/LocSvc_java( 1029): xtraDownloadRequest
D/LocSvc_java( 1029): Sending msg: 6 arg1:0 arg2:1
,D/TelephonyIcons( 1462): null signal icon name: drawable/stat_sys_signal_null
D/StatusBar.NetworkController( 1462): refreshViews: Data not connected!! Set no data type icon / Roaming
D/StatusBar.NetworkController( 1462): refreshViews: Data not connected!! Set no data type icon / Roaming
,D/libc-netbsd(  323): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  323): res_queryN name = xtra2.gpsOneXTRA.net, class = 1, type = 1
D/libc-netbsd(  323): res_queryN name = xtra2.gpsOneXTRA.net succeed
,D/LocSvc_java( 1029): calling native_inject_xtra_data
D/LocSvc_java( 1029): Sending msg: 11 arg1:0 arg2:1
,V/BluetoothOppNotification( 6103): new notify threadi!
V/BluetoothOppNotification( 6103): send delay message
,V/BluetoothOppProvider( 6103): starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
I/jxcore-log( 6033): Connected to the server!
I/jxcore-log( 6033): 
I/chromium( 6033): [INFO:CONSOLE(63)] "logCallback Connected to the server", source: file:///android_asset/www/js/thali_main.js (63)
,V/BluetoothOppProvider( 6103): created cursor android.database.sqlite.SQLiteCursor@6e3321a on behalf of 
V/BluetoothOppNotification( 6103): mUpdateCompleteNotification = true
V/BluetoothOppProvider( 6103): starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
,V/BluetoothOppProvider( 6103): created cursor android.database.sqlite.SQLiteCursor@21c714b on behalf of 
V/BluetoothOppNotification( 6103): outbound: succ-0  fail-0
V/BluetoothOppNotification( 6103): outbound notification was removed.
V/BluetoothOppProvider( 6103): starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
V/BluetoothOppProvider( 6103): created cursor android.database.sqlite.SQLiteCursor@3ba34728 on behalf of 
V/BluetoothOppNotification( 6103): inbound: succ-0  fail-0
V/BluetoothOppNotification( 6103): inbound notification was removed.
V/BluetoothOppProvider( 6103): starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
V/BluetoothOppProvider( 6103): created cursor android.database.sqlite.SQLiteCursor@1523ac41 on behalf of 
E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-43 f=2412 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-2027505490] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-43 f=2412 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:13] from screen [on:0 period:-2027505477] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
D/StatusBar.NetworkController( 1462): refreshViews: Data not connected!! Set no data type icon / Roaming
,I/jxcore-log( 6033): BLE advertisement not supported: MultipleAdvertisement not supported
I/jxcore-log( 6033): 
,V/WifiInternetCheck( 1029): Single check msg out of sync, ignoring.
,D/ConnectivityService( 1029): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering( 1029): MasterInitialState.processMessage what=3
,D/GpsLocationProvider( 1029): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,D/libc-netbsd(  323): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  323): res_queryN name = 2.android.pool.ntp.org, class = 1, type = 1
D/PostponalbeReceiver( 5113): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
,W/ContextImpl( 5113): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
I/NetworkMonitor( 5181): type=WIFI subType= reason=null isConnected=true
,D/libc-netbsd(  323): res_queryN name = 2.android.pool.ntp.org succeed
,I/ActivityManager( 1029): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=6463 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,D/AlarmManagerService( 1029): Setting time of day to sec=1449671443
W/AlarmManagerService( 1029): Unable to set rtc to 1449671443: Invalid argument
,D/LIA_Informant_Tips_DateChangeManager( 2720): onReceive() : ACTION_TIME_CHANGED
I/LIA_Informant_Tips_LogTracer( 2720): [Log Tracer - Schedule Transition] Time Change Event Received : 2015-12-09 15:30:43...... Request
I/LIA_Informant_Tips_LogTracer( 2720): [Log Tracer - Schedule Transition] UserGuide, DATE_UPDATE : working count : 7, total count : 108, new day : false...... Request
D/LIA_Informant_Tips_DateChangeManager( 2720): DateInfo : SmartTips Total Working Day Count = 108
D/LIA_Informant_Tips_DateChangeManager( 2720): DateInfo : UserGuide Working Duration Count = 7
I/SecureClockService( 1964): Intent.ACTION_TIME_CHANGED 
D/LIA_Informant_Tips_DateChangeManager( 2720): DateInfo : Last Date Check Time = 2015-12-09 15:30:43
,I/[SystemUI]Clock( 1462): onReceive = android.intent.action.TIME_SET
I/LgeClockWidgetControlView( 1462): time changed, timezoneChanged : false
D/KeyguardUpdateMonitor( 1462): handleTimeUpdate
W/ActivityManager( 1029): getTasks: caller 10029 is using old GET_TASKS but privileged; allowing
I/[LGHome]LGDateChangeReceiver( 2086): [LGDateChangeReceiver.java:78:updateCalendarShortcut()]date=9 currentDate=-1 dayofweek=4 currentDayOfWeek=-1
,I/[LGHome]LGCalendarIcon( 2086): [LGCalendarIcon.java:214:makeCalendarBitmap()]Locale = en_US dayofweek= Wed date= 9
I/[LGHome]LGCalendarIcon( 2086): [LGCalendarIcon.java:214:makeCalendarBitmap()]Locale = en_US dayofweek= Wed date= 9
I/[LGHome]Launcher( 2086): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,I/AppUp4:AppBoxCP( 6463): onCreate
W/AppUp4:DB( 6463):  [AppBoxDatabaseHelper] construct
I/ActivityManager( 1029): Start proc com.google.android.apps.books for service com.google.android.apps.books/.service.SyncService: pid=6498 uid=10054 gids={50054, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/[Concierge]Service( 2608): onStartCommand(). Type : 9
I/AppUp4:DB( 6463):  setFingerPrint start
I/AppUp4:DB( 6463):  newfinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys SDK version = 21
I/AppUp4:DB( 6463):  beforefinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys
,I/AppUp4:DB( 6463):  SDK version = 21
I/AppUp4:DB( 6463):  beforefinger == newfinger no write in DB
,I/ActivityManager( 1029): Start proc com.android.gallery3d for service com.android.gallery3d/com.lge.gallery.picasa.PicasaService: pid=6516 uid=10027 gids={50027, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
,D/AppUp4:AppBoxApplication( 6463): AppBoxApplication onCreate()
I/NetworkStateForAutoUpdateMonitor( 6463): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 6463): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 6463): [onReceive] connect :true
,I/NetworkStateForAutoUpdateMonitor( 6463): [onReceive] request level :IDLE....
I/AppUp4:CustModeStarterReceiver( 6463): onReceive
,I/GoogleURLConnFactory( 2130): Using platform SSLCertificateSocketFactory
,V/GLSActivity( 2130): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ResourcesManager( 6516): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6516): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 6516): Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
,W/ResourcesManager( 6516): Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
D/LgDataFeature( 6463): LgDataFeature() Constructor: none
D/LgDataFeature( 6463): LgDataFeature() Constructor Done, null
D/AppUp4:CustFacade( 6463): Context : android.app.ReceiverRestrictedContext@5c5aa7c
D/AppUp4:CustFacade( 6463): isCustomizationCompleted : false
D/AppUp4:CustFacade( 6463): isPhone : true
,D/AppUp4:CustModeStarterReceiver( 6463): begin check event
I/AppUp4:CustModeStarterReceiver( 6463): Event For GoodConnectivity
D/AppUp4:CustModeStarterReceiver( 6463): runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
D/AppUp4:CustModeStarterReceiver( 6463): call method handleAsyncCustNotification.
D/AppUp4:CustModeStarterReceiver( 6463): handleAsync isTriedOnce : false
E/AppUp4:CustModeStarterReceiver( 6463): handleAsyncCustNotification do not startCustService
,D/LGDMClient( 2966): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 2966): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
W/ContextImpl( 2966): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
W/ContextImpl( 2966): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
V/DownloadManager( 3299): Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 2966): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=3, isUserType=1
V/DownloadManager( 3299): DownloadService onCreate
I/LGDMClient( 2966): [DmServiceProcessor.java] [processNetworkChanged()] : [91] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
D/LGDMClient( 2966): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 2966): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
,I/AppConfig( 6516): Total System Memory = 2995761152
,I/DownloadManager( 3299): in removeSpuriousFiles
D/SystemHelper( 6516): region [EU], country [EU], operator [OPEN], sub-operator []
V/DownloadManager( 3299): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3299): created cursor android.database.sqlite.SQLiteCursor@2929e16b on behalf of 3299
I/DownloadManager( 3299): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGMyGuide_4.40.09_COM_COM_20150430011620058_RELG-D855.apk
I/DownloadManager( 3299): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGBackup_4.50.37_COM_COM_20150608234245157.apk
I/DownloadManager( 3299): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/CalendarProvider_4.2.8_COM_COM_20150304234552863_RELG-D855.apk
I/DownloadManager( 3299): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calendar_4.40.16_COM_COM_20150304234554754_RELG-D855.apk
I/DownloadManager( 3299): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.10_COM_COM_20150521235426173_RELG-D855.apk
I/DownloadManager( 3299): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQVoiceplusN_2.3.3_COM_COM_20150604065210803.apk
I/DownloadManager( 3299): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.11_COM_COM_v2_20150911144028620_RELG-D855_21.apk
I/DownloadManager( 3299): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQMemoplus(LG-D855_user)_20150902050954661.apk
I/DownloadManager( 3299): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/RemoteCall_4.1.10_COM_COM_20150817053748728.apk
I/DownloadManager( 3299): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/rspermlge(6713)_20150901080430397.apk
I/DownloadManager( 3299): in trimDatabase
V/DownloadManager( 3299): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
,V/DownloadManager( 3299): created cursor android.database.sqlite.SQLiteCursor@d45c4c8 on behalf of 3299
,I/ActivityManager( 1029): Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=6546 uid=10023 gids={50023, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,V/DownloadManager( 3299): DownloadService onStartCommand
V/DownloadManager( 3299): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
W/ContextImpl( 2966): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:141 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:180 android.app.IntentService$ServiceHandler.handleMessage:65 
V/DownloadManager( 3299): created cursor android.database.sqlite.SQLiteCursor@146a1c86 on behalf of 3299
E/LGDMClient( 2966): [DmNotiService.java] [onCreate()] : [148] : DmNotiService.onCreate()
D/LGDMClient( 2966): [DmNotiService.java] [onStartCommand()] : [182] : in the new onStartCommand()
D/LGDMClient( 2966): [DmNotiService.java] [handleStart()] : [203] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
I/art     (  353): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 189us total 9.606ms
,V/DownloadManager( 3299): processing inserted download 1
V/DownloadManager( 3299): processing inserted download 4
V/DownloadManager( 3299): processing inserted download 7
V/DownloadManager( 3299): processing inserted download 8
V/DownloadManager( 3299): processing inserted download 9
V/DownloadManager( 3299): processing inserted download 10
V/DownloadManager( 3299): processing inserted download 16
V/DownloadManager( 3299): processing inserted download 17
V/DownloadManager( 3299): processing inserted download 18
V/DownloadManager( 3299): processing inserted download 21
I/art     (  353): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 184us total 9.573ms
V/DownloadManager( 3299): DownloadService onDestroy
I/art     (  353): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 192us total 9.239ms
,W/ResourcesManager( 6546): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 6546): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 6546): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
W/ResourcesManager( 6546): Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
,I/ActivityManager( 1029): Start proc com.android.chrome for service com.android.chrome/com.google.android.apps.chrome.sync.ChromeBrowserSyncAdapterService: pid=6564 uid=10057 gids={50057, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ReaderUtils( 6498): PortraitW 1440 LandscapeW 2392 SmallestSize 1340 LargestSize 2392 textZoom 4.4999995 isTablet false Memory 256
I/LGEmail ( 6546): [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
W/DriveInitializer( 2363): Background init thread started
,E/VoldCmdListener(  279): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  279): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.gms/files/
W/Vold    (  279): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 2363): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.gms/files
,D/LGEmail ( 6546): user build Type == true (at Util.java isUserModeBuildType 3507)[v:6.41.18]
,I/VacuumService( 2130): Vacuum at: now=1449671444174 tag=VacuumService
I/GLSUser ( 2130): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/ads_measurement
,I/GLSUser ( 2130): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/ads_measurement without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 2130): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2130): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2130): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/GAV2    ( 6498): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,I/BooksApp( 6498): Created application version: 3.2.35 (30235)
,W/DriveInitializer( 2363): Background init thread ended
W/ResourceType( 6546): No package identifier when getting value for resource number 0x00000000
,D/GpsLocationProvider( 1029): updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/LgDataFeature( 6546): LgDataFeature() Constructor: none
D/LgDataFeature( 6546): LgDataFeature() Constructor Done, null
,E/GpsLocationProvider( 1029): No APN found to select.
I/art     ( 2130): Explicit concurrent mark sweep GC freed 19943(1145KB) AllocSpace objects, 2(32KB) LOS objects, 51% free, 30MB/62MB, paused 850us total 27.656ms
I/BooksSync( 6498): Starting books sync
,I/ActivityManager( 1029): Killing 5461:com.lge.lockscreensettings/u0a80 (adj 15): empty #17
,W/libprocessgroup( 1029): failed to open /acct/uid_10080/pid_5461/cgroup.procs: No such file or directory
,E/Ads     ( 2363): [JAMS] Failed to get OAuth token: com.google.android.gms.auth.ad: BadAuthentication
,D/DelayedSyncController( 6564): Delaying sync.
,E/Auth.Api.Credentials( 2363): [CredentialSyncAdapter] Unknown sync event.
,I/ActivityManager( 1029): Killing 5490:com.google.android.apps.plus/u0a97 (adj 15): empty #17
D/eas_req ( 6546): ---addEventToQueue() easCode=2, requestId=0 (at EasSupport.java addEventToQueue 69)
,W/libprocessgroup( 1029): failed to open /acct/uid_10097/pid_5490/cgroup.procs: No such file or directory
,I/HubEmail( 6546): JNI_OnLoad()
I/HubEmail( 6546): -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 6546): registerNatives()
I/HubEmail( 6546): -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 6546): registerNativeMethods()
I/HubEmail( 6546): -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
W/art     ( 6546): JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
D/BooksSync( 6498): started syncMyEbooks
I/art     ( 1029): Explicit concurrent mark sweep GC freed 49656(2MB) AllocSpace objects, 4(105KB) LOS objects, 33% free, 44MB/66MB, paused 1.698ms total 79.926ms
,W/Settings( 6546): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-43 f=2412 sc=60 link=72 tx=32.8, 0.0, 0.0  rx=29.5 bcn=0 [on:0 tx:0 rx:0 period:3983] from screen [on:0 period:-2027501478] gl rssi=-43 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-43 f=2412 sc=60 link=72 tx=32.8, 0.0, 0.0  rx=29.5 bcn=0 [on:0 tx:0 rx:0 period:5] from screen [on:0 period:-2027501473] gl rssi=-43 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
I/LgeMiscReceiver( 3187): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 3187): action = android.net.conn.CONNECTIVITY_CHANGE
I/GoogleURLConnFactory( 2130): Using platform SSLCertificateSocketFactory
,I/LgeMiscReceiver( 3187): networkInfo.isConnected() = true
D/PhoneState( 3187): setPdpRejectCasuse : false
W/Settings( 6546): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Uploader( 2130): No account for auth token provided
,D/libc-netbsd(  323): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  323): res_queryN name = static-avc.lglime.com, class = 1, type = 1
,I/ActivityManager( 1029): Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=6630 uid=10062 gids={50062, 9997, 4002, 3003, 1028} abi=armeabi-v7a
,D/libc-netbsd(  323): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  323): res_queryN name = www.google.com, class = 1, type = 1
,D/DrmBroadcastReceiver( 6630): Receive CONNECTIVITY_ACTION
,D/DrmBroadcastReceiver( 6630): 1  network is available. Sync DRM Time with NTP
D/libc-netbsd(  323): res_queryN name = static-avc.lglime.com succeed
D/libc-netbsd(  323): res_queryN name = www.google.com succeed
D/libc-netbsd(  323): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  323): res_queryN name = clients3.google.com, class = 1, type = 1
D/libc-netbsd(  323): res_queryN name = clients3.google.com succeed
V/DrmService( 6630): Service onCreate
,D/DrmService( 6630): Received new request = 2
I/DrmSntpClient( 6630): Start Sync process
D/DrmSntpClient( 6630): Server : 0
D/libc-netbsd(  323): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  323): res_queryN name = pool.ntp.org, class = 1, type = 1
,I/ActivityManager( 1029): Start proc com.lge.sizechangable.weather for broadcast com.lge.sizechangable.weather/.layout.WeatherWidget: pid=6652 uid=10085 gids={50085, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,V/WifiInternetCheck( 1029): isHttpConnectionAvailable - We got a valid response : 204
,V/GLSActivity( 2130): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/libc-netbsd(  323): res_queryN name = pool.ntp.org succeed
V/FormManager( 6187): There are no updated forms. The schedule will be deleted.
V/FormManager( 6187): Alarm would be updated, because LastCheckTime has been updated.
D/libc-netbsd(  323): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  323): res_queryN name = play.googleapis.com, class = 1, type = 1
,I/ActivityManager( 1029): Killing 5823:com.lge.eula/1000 (adj 15): empty #17
,I/GLSUser ( 2130): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 2130): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2130): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2130): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
D/UEI.SmartControl( 5791): Internal timer expired: 2
D/UEI.SmartControl( 5791): unbind internal service
D/libc-netbsd(  323): res_queryN name = play.googleapis.com succeed
,W/libprocessgroup( 1029): failed to open /acct/uid_1000/pid_5823/cgroup.procs: No such file or directory
V/GLSActivity( 2130): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/art     ( 6652): Almond Protected OAT
,D/serial_port( 5791): close(fd = 24)
,I/UEI.SmartControl( 5791): Serial port is closed.
V/NotificationService( 1029): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,D/ZenLog  ( 1029): intercepted: 0|com.google.android.gms|1|null|10005,none
V/NotificationService( 1029): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1029): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1029): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1029): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,W/GLSActivity( 2130): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2130): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2130): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2130): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2130): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2130): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2130): 	at android.os.Binder.execTransact(Binder.java:446)
E/BooksAccountManager( 6498): Authentication error
E/BooksAccountManager( 6498): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6498): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6498): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6498): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6498): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6498): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6498): null auth token
W/ResourcesManager( 1462): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 1462): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
D/libc-netbsd(  323): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  323): res_queryN name = www.googleapis.com, class = 1, type = 1
W/ResourcesManager( 1414): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 1414): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,D/LgeQuickCoverNLService( 1414): onNotificationPosted
D/SmartCoverUpdateMonitor( 1414): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1414): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1414): handleNotificationPosted(true)
D/QuickCircle( 1414): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1414): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1414): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1414): post do add job
D/LgeQuickCoverNotificationData( 1414): add : 2
D/LgeQuickCoverNotificationData( 1414): do add job
D/LgeQuickCoverNotificationData( 1414): showAll3
D/LgeQuickCoverNotificationData( 1414): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1414): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1414): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1414): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1414): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1414): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1414): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1414): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1414): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1414): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1414): updateNotificationData: count=3
,D/QuickStatusbarLayout( 1414): Notification difference=198
D/QuickStatusbarLayout( 1414): child = android.widget.LinearLayout{1813a4 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
D/libc-netbsd(  323): res_queryN name = www.googleapis.com succeed
,D/WeatherApplication( 6652): removeAccount
D/WeatherApplication( 6652): Account.length = 0
E/WeatherApplication( 6652): OPERATOR:OPEN
D/WeatherAncestor( 6652): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 15:30:44
V/GLSActivity( 2130): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/Weather.Utils( 6652): 2 : the weather widgets(using time tick) are gone.
D/Weather.Utils( 6652): 2 : All the weather widget is gone.
D/UpdateThreadPoolManager( 6652): 2 : This is isUpdating : false
D/WeatherAncestor( 6652): connectivity changed - connection : true
D/WeatherService( 6652): 2 : isServiceAlived():false forecastCache:null
D/ForecastDataCache( 6652): 2 : lastUpdatedTime: 1430558561343
D/ForecastDataCache( 6652): 2 : currentPackageVersion: 4.40.4
D/ForecastDataCache( 6652): 2 : Cache is not up-to-date, count: 0
,I/GLSUser ( 2130): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.syncadapters.contacts, service: cp
I/GLSUser ( 2130): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> cp without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2130): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2130): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2130): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/Weather_cast( 6652): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherAncestor( 6652): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 15:30:44
,V/NotificationService( 1029): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
V/NotificationService( 1029): pkg=com.google.android.gms canInterrupt=false intercept=true
W/GLSActivity( 2130): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2130): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2130): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2130): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2130): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2130): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2130): 	at android.os.Binder.execTransact(Binder.java:446)
I/ActivityManager( 1029): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=6675 uid=10093 gids={50093, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager( 1029): Killing 5866:com.google.android.gms.wearable/u0a5 (adj 15): empty #17
W/libprocessgroup( 1029): failed to open /acct/uid_10005/pid_5866/cgroup.procs: No such file or directory
,D/ContactsSyncAdapter( 2130): innerSync failed
D/ContactsSyncAdapter( 2130): com.google.wireless.gdata2.client.AuthenticationException: unable to get auth token android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
D/ContactsSyncAdapter( 2130): 	at com.google.android.syncadapters.contacts.AuthInfo.getAuthToken(AuthInfo.java:45)
D/ContactsSyncAdapter( 2130): 	at com.google.android.syncadapters.contacts.ContactsSyncAdapter.innerPerformSync(ContactsSyncAdapter.java:263)
D/ContactsSyncAdapter( 2130): 	at com.google.android.syncadapters.contacts.ContactsSyncAdapter.onPerformLoggedSync(ContactsSyncAdapter.java:168)
D/ContactsSyncAdapter( 2130): 	at com.google.android.common.LoggingThreadedSyncAdapter.onPerformSync(LoggingThreadedSyncAdapter.java:33)
D/ContactsSyncAdapter( 2130): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
D/ContactsSyncAdapter( 2130): Caused by: android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
D/ContactsSyncAdapter( 2130): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
D/ContactsSyncAdapter( 2130): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
D/ContactsSyncAdapter( 2130): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
D/ContactsSyncAdapter( 2130): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
D/ContactsSyncAdapter( 2130): 	at android.os.Binder.execTransact(Binder.java:446)
,I/NotificationServiceEx( 1029): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1029): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1029): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1414): onNotificationPosted
D/SmartCoverUpdateMonitor( 1414): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1414): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1414): handleNotificationPosted(true)
D/QuickCircle( 1414): onNotificationPosted() : isPosted true
,D/LgeQuickCoverNotificationData( 1414): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1414): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1414): post do just update job
D/LgeQuickCoverNotificationData( 1414): showAll3
D/LgeQuickCoverNotificationData( 1414): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1414): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1414): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1414): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1414): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1414): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1414): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1414): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1414): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1414): isNotificationForCurrentUser : true
,D/SyncManager( 1029): failed sync operation thalitester@gmail.com u0 (com.google), com.android.contacts, LOCAL, currentRunTime 26373, reason: 10019, SyncResult: stats [ numAuthExceptions: 1]
E/LgeQuickCoverOverlayWindow( 1414): updateNotificationData: count=3
D/SyncManager( 1029): not retrying sync operation because the error is a hard error: thalitester@gmail.com u0 (com.google), com.android.contacts, LOCAL, currentRunTime 322101, reason: 10019
D/QuickStatusbarLayout( 1414): Notification difference=198
D/QuickStatusbarLayout( 1414): child = android.widget.LinearLayout{1813a4 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,W/Uploader( 2130): No account for auth token provided
W/ApiaryClient( 6498): Error response from books API: {
W/ApiaryClient( 6498):  "error": {
W/ApiaryClient( 6498):   "errors": [
W/ApiaryClient( 6498):    {
W/ApiaryClient( 6498):     "domain": "global",
W/ApiaryClient( 6498):     "reason": "required",
W/ApiaryClient( 6498):     "message": "Login Required",
W/ApiaryClient( 6498):     "locationType": "header",
W/ApiaryClient( 6498):     "location": "Authorization"
W/ApiaryClient( 6498):    }
W/ApiaryClient( 6498):   ],
W/ApiaryClient( 6498):   "code": 401,
W/ApiaryClient( 6498):   "message": "Login Required"
W/ApiaryClient( 6498):  }
W/ApiaryClient( 6498): }
,W/ApiaryClient( 6498): errCount = 1: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6498): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-900266509079114087&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6498): Headers:
W/ApiaryClient( 6498): accept-encoding: [gzip]
W/ApiaryClient( 6498): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6498): gdata-version: 2
,D/DelayedSyncController( 6564): Delaying sync.
,W/Uploader( 2130): No account for auth token provided
,E/VoldCmdListener(  279): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  279): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  279): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6675): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
E/VoldCmdListener(  279): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  279): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  279): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6675): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
E/VoldCmdListener(  279): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  279): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  279): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6675): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
E/VoldCmdListener(  279): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  279): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  279): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6675): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
,W/Uploader( 2130): No account for auth token provided
,W/Uploader( 2130):  no longer exists, so no auth token.
,I/ActivityManager( 1029): Start proc com.google.android.apps.plus for service com.google.android.apps.plus/.service.EsSyncAdapterService: pid=6703 uid=10097 gids={50097, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,W/Uploader( 2130): No account for auth token provided
,W/ResourcesManager( 6703): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/WebViewFactory( 6675): Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,I/LibraryLoader( 6675): Loading: webviewchromium
I/LibraryLoader( 6675): Time to load native libraries: 3 ms (timestamps 1514-1517)
I/LibraryLoader( 6675): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 6675): Binding Chromium to main looper Looper (main, tid 1) {26c07c57}
I/LibraryLoader( 6675): Expected native library version number "",actual native library version number ""
I/chromium( 6675): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 6675): Initializing chromium process, renderers=0
,W/art     ( 6675): Attempt to remove local handle scope entry from IRT, ignoring
W/chromium( 6675): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
,V/AudioPolicyService(  327): registerClient() client 0xb1427be0, uid 10093
I/chromium( 6675): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=38 off=46780 len=2953
I/chromium( 6675): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:39 off:229536 len:643667
W/AudioManagerAndroid( 6675): Requires BLUETOOTH permission
I/Adreno-EGL( 6675): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 6675): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 6675): Build Date: 12/12/14 금
I/Adreno-EGL( 6675): Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
I/Adreno-EGL( 6675): Remote Branch: 
I/Adreno-EGL( 6675): Local Patches: 
I/Adreno-EGL( 6675): Reconstruct Branch: 
,I/NSApplication( 6675): Starting up...
,I/ActivityManager( 1029): Killing 4849:com.android.vending/u0a44 (adj 15): empty #17
,W/libprocessgroup( 1029): failed to open /acct/uid_10044/pid_4849/cgroup.procs: No such file or directory
,I/GLSActivity( 2130): [ac] getting account id
,I/GLSUser ( 2130): [t] Fetched account id for thalitester@gmail.com : 105256135866144380227
,D/libc-netbsd(  323): default dns: query_ipv6=0, query_ipv4=1
,D/libc-netbsd(  323): res_queryN name = mtalk.google.com, class = 1, type = 1
I/iu.SyncManager( 2363): SYNC; picasa accounts
,D/libc-netbsd(  323): res_queryN name = mtalk.google.com succeed
D/NetworkLogImpl( 2363): Loaded NetworkSpeedPredictor
,I/iu.Environment( 2363): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
I/GLSUser ( 2130): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/gcm
I/GLSUser ( 2130): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/gcm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2130): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 2130): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
I/iu.UploadsManager( 2363): num queued entries: 0
I/iu.UploadsManager( 2363): num updated entries: 0
V/GLSActivity( 2130): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/iu.SyncManager( 2363): NEXT; no task
,D/ChimeraCfgMgr( 2363): Loading module com.google.android.gms.kids from APK com.google.android.gms
I/GcmGroups( 2363): Failed to subscribe to group.
I/GcmGroups( 2363): com.google.android.gms.auth.ad: BadAuthentication
I/GcmGroups( 2363): 	at com.google.android.gms.auth.p.b(SourceFile:442)
I/GcmGroups( 2363): 	at com.google.android.gms.auth.p.a(SourceFile:365)
I/GcmGroups( 2363): 	at com.google.android.gms.auth.p.a(SourceFile:318)
I/GcmGroups( 2363): 	at com.google.android.gms.gcm.gmsproc.b.a(SourceFile:443)
I/GcmGroups( 2363): 	at com.google.android.gms.gcm.gmsproc.b.a(SourceFile:333)
I/GcmGroups( 2363): 	at com.google.android.gms.gcm.gmsproc.b.a(SourceFile:240)
I/GcmGroups( 2363): 	at com.google.android.gms.gcm.gmsproc.GcmReceiverService.onHandleIntent(SourceFile:50)
I/GcmGroups( 2363): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
I/GcmGroups( 2363): 	at android.os.Handler.dispatchMessage(Handler.java:102)
I/GcmGroups( 2363): 	at android.os.Looper.loop(Looper.java:135)
I/GcmGroups( 2363): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,D/ChimeraCfgMgr( 2363): Loading module com.google.android.gms.kids from APK com.google.android.gms
I/GcmGroups( 2363): Groups upload failed, retrying in 24000:00:00
D/PostponalbeReceiver( 5113): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.intent.action.TIME_SET'.
I/ActivityManager( 1029): Start proc com.lge.clock for broadcast com.lge.clock/.alarmclock.ALBootInit: pid=6774 uid=10010 gids={50010, 9997, 3003, 1028, 4002} abi=armeabi-v7a
,I/GLSUser ( 2130): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: ac2dm
I/GLSUser ( 2130): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> ac2dm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2130): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2130): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2130): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1029): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1029): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1029): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1029): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1029): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1414): onNotificationPosted
D/SmartCoverUpdateMonitor( 1414): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1414): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1414): handleNotificationPosted(true)
D/QuickCircle( 1414): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1414): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1414): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1414): post do just update job
D/LgeQuickCoverNotificationData( 1414): showAll3
D/LgeQuickCoverNotificationData( 1414): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1414): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1414): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1414): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1414): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1414): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1414): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1414): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1414): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1414): isNotificationForCurrentUser : true
W/Kids    ( 2363): [AccountUtils] Account not ready
W/Kids    ( 2363): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/Kids    ( 2363): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/Kids    ( 2363): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/Kids    ( 2363): 	at com.google.android.gms.auth.p.c(SourceFile:550)
W/Kids    ( 2363): 	at com.google.android.gms.auth.p.b(SourceFile:477)
W/Kids    ( 2363): 	at com.google.android.gms.kids.account.k.d(SourceFile:103)
W/Kids    ( 2363): 	at com.google.android.gms.kids.account.p.a(SourceFile:70)
W/Kids    ( 2363): 	at com.google.android.gms.kids.account.t.a(SourceFile:62)
W/Kids    ( 2363): 	at com.google.android.gms.chimera.f.run(SourceFile:179)
W/Kids    ( 2363): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Kids    ( 2363): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Kids    ( 2363): 	at java.lang.Thread.run(Thread.java:818)
E/LgeQuickCoverOverlayWindow( 1414): updateNotificationData: count=3
,D/QuickStatusbarLayout( 1414): Notification difference=198
D/QuickStatusbarLayout( 1414): child = android.widget.LinearLayout{1813a4 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
I/art     ( 1029): Explicit concurrent mark sweep GC freed 28289(1257KB) AllocSpace objects, 4(192KB) LOS objects, 33% free, 44MB/66MB, paused 1.993ms total 116.530ms
,D/ALBootInit( 6774): ====action==>android.intent.action.TIME_SET
D/ALBootInit( 6774): Alarm ALBootInit: TIME_SET
D/Alarms  ( 6774): [setNextAlert] start
D/Alarms  ( 6774): [setNextAlert] (1)
,D/Alarms  ( 6774):  minTime  = 0
D/GCM     ( 2130): Connected
D/Alarms  ( 6774):  -- OK multi -- 0
E/jeny.kim( 6774): [setNextAlert] setNextAlert  temp_Alarmlink + 
E/jeny.kim( 6774): [setNextAlert]setNextAlert temp_AlarmLinkText + 
,D/GCM     ( 2130): Message class com.google.f.a.a.p
,I/CommonUtil( 6774): BUILD Country: EU
D/Alarms  ( 6774): broadcastToWidgetProvider : false
D/Alarms  ( 6774): Enter formatDayAndTime(final Context context, long timeInMiliSec)
,V/SettingsProvider( 1029): call_put(system:next_alarm_formatted=) for 0 calling package = com.lge.clock
I/DigitalAppWidgetProvider( 6774): onReceive: android.intent.action.TIME_SET
V/DigitalAppWidgetProvider( 6774): cancelAlarmOnQuarterHour android.app.ReceiverRestrictedContext@7038f05
V/DigitalAppWidgetProvider( 6774): startAlarmOnQuarterHour android.app.ReceiverRestrictedContext@7038f05
D/QuickCoverProvider( 6774): onReceiver
,I/indal   ( 1414): SmartCoverWidgetContext createApplicationContext
I/indal   ( 1414): SmartCoverWidgetContext createApplicationContext
D/WeatherAncestor( 6652): 2 : onReceive, action: android.intent.action.TIME_SET, Time(hour:min:sec) 15:30:46
,D/Weather.Utils( 6652): 2 : the weather widgets(using time tick) are gone.
D/Weather.Utils( 6652): 2 : All the weather widget is gone.
D/UpdateThreadPoolManager( 6652): 2 : This is isUpdating : false
D/WeatherService( 6652): 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@34f59b5a
D/ForecastDataCache( 6652): 2 : lastUpdatedTime: 1430558561343
D/ForecastDataCache( 6652): 2 : currentPackageVersion: 4.40.4
D/ForecastDataCache( 6652): 2 : Cache is up-to-date, count: 0
D/Weather_cast( 6652): 2 : set auto-update time : 12/9 18:30
D/WeatherAncestor( 6652): 2 : onReceive has processed, action: android.intent.action.TIME_SET, Time(hour:min:sec) 15:30:46
,I/ActivityManager( 1029): Start proc com.qualcomm.timeservice for broadcast com.qualcomm.timeservice/.TimeServiceBroadcastReceiver: pid=6799 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
I/ActivityManager( 1029): Killing 5846:com.lge.bnr/1000 (adj 15): empty #17
,W/libprocessgroup( 1029): failed to open /acct/uid_1000/pid_5846/cgroup.procs: No such file or directory
,V/GLSActivity( 2130): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/GLSUser ( 2130): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2130): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2130): [GLSUser] Extracting token using key: Auth
,D/TimeService( 6799): Receivedandroid.intent.action.TIME_SET intent. Current Time is 1449671446343
D/        ( 6799): TimeServiceNative: User Time to be set is 1449671446343
D/QC-time-services( 6799): Lib:time_genoff_operation: pargs->base = 2
D/QC-time-services( 6799): Lib:time_genoff_operation: pargs->operation = 0
D/QC-time-services( 6799): Lib:time_genoff_operation: pargs->ts_val = 1449671446343
D/QC-time-services( 6799): Lib:time_genoff_operation: Send to server  passed!!
D/QC-time-services(  415): Daemon: Connection accepted:time_genoff
W/GLSActivity( 2130): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
D/QC-time-services(  415): Daemon:Received base = 2, unit = 1, operation = 0,value = 1449671446343
D/QC-time-services(  415): Daemon:genoff_opr: Base = 2, val = 1449671446343, operation = 0
D/QC-time-services(  415): Daemon:rtc_get: Time read from RTC -- MM/DD/YY HH:MM:SS3/18/70 7:43:29
D/QC-time-services(  415): Daemon:Value read from RTC seconds = 9272609000
D/QC-time-services(  415): Daemon:new time 1449671446343 
D/QC-time-services(  415): Daemon: delta 1440398837343 genoff 1440398837343 
D/QC-time-services(  415): Daemon:genoff_persistent_update: Writing genoff = 1440398837343 to memory
D/QC-time-services(  415): Daemon:Opening File: /data/time/ats_2
D/QC-time-services(  415): Daemon:time_persistent_memory_opr:Genoff write operation 
V/GLSActivity( 2130): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/QC-time-services(  415): Updating the TOD offset
D/QC-time-services(  415): Daemon:genoff_persistent_update: Writing genoff = 1440398837343 to memory
D/QC-time-services(  415): Daemon:Opening File: /data/time/ats_1
D/QC-time-services(  415): Daemon:time_persistent_memory_opr:Genoff write operation 
E/QC-time-services(  415): Daemon:Update to modem bit set
D/QC-time-services(  415): Daemon:genoff_send_modem: Sending data to MODEM !
D/QC-time-services(  415): Daemon: Base = 2, Value being sent to MODEM = 1124434037343
E/QC-time-services( 6799): Receive Passed == base = 2, unit = 1, operation = 0, result = 0
E/QC-time-services(  415): Daemon:tod_update_ind_cb: Got Update from modem msg_id 40
E/QC-time-services(  415): Daemon: Time-services: Waiting to acceptconnection
I/ActivityManager( 1029): Start proc com.android.calendar for broadcast com.android.calendar/.widget.CalendarAppWidgetProvider: pid=6820 uid=10013 gids={50013, 9997, 3003, 1028, 1015} abi=armeabi
I/ActivityManager( 1029): Killing 5910:com.google.android.talk/u0a72 (adj 15): empty #17
,W/libprocessgroup( 1029): failed to open /acct/uid_10072/pid_5910/cgroup.procs: No such file or directory
W/ResourcesManager( 6820): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,V/NotificationService( 1029): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1029): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1029): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1029): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1029): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1414): onNotificationPosted
W/GLSActivity( 2130): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2130): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2130): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2130): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2130): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2130): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2130): 	at android.os.Binder.execTransact(Binder.java:446)
D/SmartCoverUpdateMonitor( 1414): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1414): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1414): handleNotificationPosted(true)
D/QuickCircle( 1414): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1414): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1414): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1414): post do just update job
D/LgeQuickCoverNotificationData( 1414): showAll3
D/LgeQuickCoverNotificationData( 1414): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1414): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1414): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1414): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1414): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1414): isNotificationForCurrentUser : true
,D/LgeQuickCoverOverlayWindow( 1414): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1414): isNotificationForCurrentUser : true
E/BooksAccountManager( 6498): Authentication error
E/BooksAccountManager( 6498): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6498): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6498): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6498): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6498): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6498): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6498): null auth token
D/LgeQuickCoverOverlayWindow( 1414): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1414): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1414): updateNotificationData: count=3
D/QuickStatusbarLayout( 1414): Notification difference=198
D/QuickStatusbarLayout( 1414): child = android.widget.LinearLayout{1813a4 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,D/CalendarApplication( 6820): CalendarApplication.onCreate()
,D/PreferenceKeysParser( 6820): [debug_displayParseInfos] preference keys.size() = 44
D/PreferenceKeysParser( 6820): [debug_displayParseInfos] preference keys = {lg_preferences_tardis_1=com.android.calendar.adaptation.PreferenceKey$KeyData@b4d4950, lg_preferences_hide_declined=com.android.calendar.adaptation.PreferenceKey$KeyData@201ec749, lg_preferences_default_reminder=com.android.calendar.adaptation.PreferenceKey$KeyData@3949484e, lg_preferences_month_view_style=com.android.calendar.adaptation.PreferenceKey$KeyData@328fbd6f, lg_preferences_alerts_ringtone=com.android.calendar.adaptation.PreferenceKey$KeyData@5c5aa7c, lg_preferences_device_tz=com.android.calendar.adaptation.PreferenceKey$KeyData@7038f05, lg_preferences_debug_datesearch=com.android.calendar.adaptation.PreferenceKey$KeyData@34f59b5a, lg_preferences_debug_country=com.android.calendar.adaptation.PreferenceKey$KeyData@2384c18b, lg_preferences_display_weather_information=com.android.calendar.adaptation.PreferenceKey$KeyData@f00f268, lg_preferences_alerts_vibrateWhen=com.android.calendar.adaptation.PreferenceKey$KeyData@11b31681, lg_preferences_debug_rtl=com.android.calendar.adaptation.PreferenceKey$KeyData@2e21326, lg_preferences_alerts_type=com.android.calendar.adaptation.PreferenceKey$KeyData@117beb67, lg_preferrences_country_code=com.android.calendar.adaptation.PreferenceKey$KeyData@2c26cd14, lg_preferences_weather_info=com.android.calendar.adaptation.PreferenceKey$KeyData@107999bd, lg_preference_holiday_calendar_ver=com.android.calendar.adaptation.PreferenceKey$KeyData@35cc3bb2, lg_preferences_show_controls=com.android.calendar.adaptation.PreferenceKey$KeyData@3fd1d703, lg_preferences_user_select_noti_sound=com.android.calendar.adaptation.PreferenceKey$KeyData@2b2da680, lg_preference_default_myphonebook=com.android.calendar.adaptation.PreferenceKey$KeyData@122b14b9, lg_preferences_skip_setup=com.android.calendar.adaptation.PreferenceKey$KeyData@1cbe60fe, lg_preferred_startView=com.android.calendar.adaptation.PreferenceKey$KeyData@110e05f, lg_preferences_debug_operator=com.android.calendar.adaptation.PreferenceKey$KeyData@106aaac, lg_preferences_exclude_sticker_list=com.android.calendar.adaptation.PreferenceKey$KeyData@24df4375, lg_preferences_writable_calendars_count=com.android.calendar.adaptation.PreferenceKey$KeyData@1b1b8f0a, lg_preferred_detailedView=com.android.calendar.adaptation.PreferenceKey$KeyData@1c0d237b, lg_preferences_debug_floating=com.android.calendar.adaptation.PreferenceKey$KeyData@1e89c598, lg_preferences_home_tz=com.android.calendar.adaptation.PreferenceKey$KeyData@266da1f1, lg_preferences_home_tz_enabled=com.android.calendar.adaptation.PreferenceKey$KeyData@356b91d6, lg_preference_received_provider_reminder_broadcast=com.android.calendar.adaptation.PreferenceKey$KeyData@26c07c57, lg_preferences_default_cell_height=com.android.calendar.adaptation.PreferenceKey$KeyData@2821a344, lg_preferences_notification_type=com.android.calendar.adaptation.PreferenceKey$KeyData@20a96c2d, lg_preferences_show_week_num=com.android.calendar.adaptation.PreferenceKey$KeyData@1ee6f562, lg_preferences_dont_show_again_no_online_account=com.android.calendar.adaptation.PreferenceKey$KeyData@32e686f3, lg_preferences_alerts_popup=com.android.calendar.adaptation.PreferenceKey$KeyData@3c37afb0, lg_preferences_week_start_day=com.android.calendar.adaptation.PreferenceKey$KeyData@2d5d9e29, lg_preferences_app_version=com.android.calendar.adaptation.PreferenceKey$KeyData@13c305ae, lg_preferences_alerts=com.android.calendar.adaptation.PreferenceKey$KeyData@28589f4f, lg_preferences_select_aux_calendar=com.android.calendar.adaptation.PreferenceKey$KeyData@346016dc, lg_preferences_widget_info_calendars=com.android.calendar.adaptation.PreferenceKey$KeyData@1e08f3e5, lg_preferences_alerts_default_ringtone=com.android.calendar.adaptation.PreferenceKey$KeyData@c3dceba, lg_preference_defaultCalendar=com.android.calendar.adaptation.PreferenceKey$KeyData@2929e16b, lg_preferences_alerts_vibratetype=com.android.calendar.adaptation.PreferenceKey$KeyData@d45c4c8, lg_preferences_rece,nt_timezones=com.android.calendar.adaptation.PreferenceKey$KeyData@2359e96
D/GeneralPreferenceUtils( 6820): [migratePrefrenceKeys] Exit: Version(44001600) >= 42001300
D/Config  ( 6820): [init]
,I/Config  ( 6820): LGCalendar ver.4.40.16
I/Config  ( 6820): start check model
I/Config  ( 6820): start check native_ca
I/Config  ( 6820): Config Operator=OPEN, Country=EU
D/Config  ( 6820): [setDefaultValuesToPref]
D/Config  ( 6820): [parseProfiles]
D/ProfilesParser( 6820): [debug_displayParseInfos] profile.country = null
D/ProfilesParser( 6820): [debug_displayParseInfos] profile.operator = null
D/Config  ( 6820): [updateProfiletoCountryInfo]
D/GeneralPreference( 6820): [checkAndMigrateOldPreference]
W/ApiaryClient( 6498): Error response from books API: {
W/ApiaryClient( 6498):  "error": {
W/ApiaryClient( 6498):   "errors": [
W/ApiaryClient( 6498):    {
W/ApiaryClient( 6498):     "domain": "global",
W/ApiaryClient( 6498):     "reason": "required",
W/ApiaryClient( 6498):     "message": "Login Required",
W/ApiaryClient( 6498):     "locationType": "header",
W/ApiaryClient( 6498):     "location": "Authorization"
W/ApiaryClient( 6498):    }
W/ApiaryClient( 6498):   ],
W/ApiaryClient( 6498):   "code": 401,
W/ApiaryClient( 6498):   "message": "Login Required"
W/ApiaryClient( 6498):  }
W/ApiaryClient( 6498): }
W/ApiaryClient( 6498): errCount = 2: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6498): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-900266509079114087&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6498): Headers:
W/ApiaryClient( 6498): accept-encoding: [gzip]
W/ApiaryClient( 6498): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6498): gdata-version: 2
,E/AgendaWidgetManager( 6820): [updateWidgets] 
I/InitNotificationRingtoneService( 6820): Start InitializeAlertRingtoneService.onHandleIntent
,I/AlertUtils( 6820): [setFormatNotificationSound] current noti URI = content://media/internal/audio/media/41
I/AlertUtils( 6820): [getCalendarNotiSoundURIFromCursor] getCount()= 21
,I/AlertUtils( 6820): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Arpeggio.ogg
I/AlertUtils( 6820): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Country_Blues.ogg
,I/AlertUtils( 6820): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Crystal.ogg
I/AlertUtils( 6820): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Dewdrop.ogg
,I/AlertUtils( 6820): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Ding_Dong.ogg
I/AlertUtils( 6820): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Echo.ogg
I/AlertUtils( 6820): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Email.ogg
,I/AlertUtils( 6820): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Game_Over.ogg
I/AlertUtils( 6820): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Gayageum.ogg
I/AlertUtils( 6820): [getMediaFilepathFromContentUri] filepath = /system/media/audio/alarms/Afternoon_Walk.ogg
,I/AlertUtils( 6820): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Harmonics.ogg
I/AlertUtils( 6820): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Idea.ogg
I/AlertUtils( 6820): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/News.ogg
,I/AlertUtils( 6820): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Pebble.ogg
I/AlertUtils( 6820): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Schedule.ogg
I/AlertUtils( 6820): [getCalendarNotiSoundURIFromCursor] filePath = /system/media/audio/notifications/Schedule.ogg, new URI = content://media/internal/audio/media/41
I/AlertUtils( 6820): set default noti to content://media/internal/audio/media/41
,I/InitNotificationRingtoneService( 6820): End InitializeAlertRingtoneService.onHandleIntent
D/MonthWidgetProvider( 6820): [onReceive]
D/CalendarWidgetProvider( 6820): [onReceive]
,D/CalendarWidgetProvider( 6820): [CalendarWidgetProvider] got the intent: Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.android.calendar/.widget.MonthWidgetProvider }
W/HolidayIntentService( 6820): onHandleIntent
D/HolidayDataLoader( 6820): readJsonAsset : holiday.json
D/CalendarTypeController( 6820): [onUpdateAndInitCalendarTime]
D/WeekWidgetProvider( 6820): [onReceive]
D/CalendarWidgetProvider( 6820): [onReceive]
D/CalendarWidgetProvider( 6820): [CalendarWidgetProvider] got the intent: Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.android.calendar/.widget.WeekWidgetProvider }
D/CalendarTypeController( 6820): [onUpdateAndInitCalendarTime]
,E/HolidayIntentService( 6820): onHandleIntent:holiday data empty
,I/ActivityManager( 1029): Killing 6169:com.lge.lifetracker/u0a37 (adj 15): empty #17
I/art     ( 2363): Explicit concurrent mark sweep GC freed 14689(1251KB) AllocSpace objects, 25(400KB) LOS objects, 49% free, 32MB/64MB, paused 1.848ms total 74.030ms
,W/libprocessgroup( 1029): failed to open /acct/uid_10037/pid_6169/cgroup.procs: No such file or directory
,D/GCM     ( 2130): GcmService start Intent { act=com.google.android.gcm.intent.SEND flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.gcm.intent.SEND
,I/ActivityManager( 1029): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.realtimechat.RequestWriter$NetworkStateReceiver: pid=6844 uid=10072 gids={50072, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,W/ResourcesManager( 6844): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,D/LgDataFeature( 6844): LgDataFeature() Constructor: none
D/LgDataFeature( 6844): LgDataFeature() Constructor Done, null
,I/Babel   ( 6844): MmsConfig: mnc/mcc: 0/0
I/Babel   ( 6844): MmsConfig.loadMmsSettings
I/Babel   ( 6844): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D855 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D855-M3-D1.xml
I/Babel   ( 6844): MmsConfig.loadFromDatabase
,E/Babel   ( 6844): canonicalizeMccMnc: invalid mccmnc 
I/Babel   ( 6844): MmsConfig.loadFromResources
E/Babel   ( 6844): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel   ( 6844): MmsConfig.loadMmsSettings: mUserAgent=LG-D855 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D855-M3-D1.xml
,W/Settings( 6844): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/AudioCapabilities( 6844): Unsupported mime audio/evrc
,W/AudioCapabilities( 6844): Unsupported mime audio/qcelp
,W/VideoCapabilities( 6844): Unrecognized profile 2130706433 for video/avc
I/DigitalAppWidgetProvider( 6774): onReceive: android.intent.action.ALARM_CHANGED
,W/AudioCapabilities( 6844): Unsupported mime audio/amr-wb-plus
D/WeatherAncestor( 6652): 2 : onReceive, action: com.lge.sizechangable.weather.action.setweathercast, Time(hour:min:sec) 15:30:47
W/AudioCapabilities( 6844): Unsupported mime audio/qcelp
D/Weather.Utils( 6652): 2 : the weather widgets(using time tick) are gone.
D/Weather.Utils( 6652): 2 : All the weather widget is gone.
D/UpdateThreadPoolManager( 6652): 2 : This is isUpdating : false
W/AudioCapabilities( 6844): Unsupported mime audio/evrc
D/Weather_cast( 6652): 2 : Update is Canceled by com.lge.sizechangable.weather.action.alarm
D/WeatherAncestor( 6652): 2 : onReceive has processed, action: com.lge.sizechangable.weather.action.setweathercast, Time(hour:min:sec) 15:30:47
W/VideoCapabilities( 6844): Unsupported mime video/x-ms-wmv
,W/VideoCapabilities( 6844): Unsupported mime video/divx
W/VideoCapabilities( 6844): Unsupported mime video/divx311
W/ResourcesManager( 6844): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6844): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
W/VideoCapabilities( 6844): Unsupported mime video/divx4
W/VideoCapabilities( 6844): Unsupported mime video/mp4v-esdp
,I/VideoCapabilities( 6844): Unsupported profile 4 for video/mp4v-es
,W/AudioCapabilities( 6844): Unsupported mime audio/eac3
W/AudioCapabilities( 6844): Unsupported mime audio/ac3
W/AudioCapabilities( 6844): Unsupported mime audio/g726
W/AudioCapabilities( 6844): Unsupported mime audio/wma-voice
W/AudioCapabilities( 6844): Unsupported mime audio/x-ms-wma
W/AudioCapabilities( 6844): Unsupported mime audio/adpcm
W/VideoCapabilities( 6844): Unsupported mime video/theora
W/VideoCapabilities( 6844): Unsupported mime video/mjpg
V/JNIHelp ( 6844): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,W/System  ( 6844): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/system/framework/com.google.android.media.effects.jar", zip file "/system/app/Hangouts/Hangouts.apk"],nativeLibraryDirectories=[/system/app/Hangouts/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6844): Installed default security provider GmsCore_OpenSSL
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-43 f=2412 sc=60 link=72 tx=18.4, 0.0, 0.0  rx=16.2 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-2027498466] gl rssi=-43 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-43 f=2412 sc=60 link=72 tx=18.4, 0.0, 0.0  rx=16.2 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-2027498465] gl rssi=-43 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,V/GLSActivity( 2130): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/GLSUser ( 2130): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2130): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 2130): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2130): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2130): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1029): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1029): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1029): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1029): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1029): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
W/GLSActivity( 2130): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2130): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2130): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2130): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2130): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2130): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2130): 	at android.os.Binder.execTransact(Binder.java:446)
E/BooksAccountManager( 6498): Authentication error
E/BooksAccountManager( 6498): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6498): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6498): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6498): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6498): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6498): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6498): null auth token
D/LgeQuickCoverNLService( 1414): onNotificationPosted
,D/SmartCoverUpdateMonitor( 1414): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1414): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1414): handleNotificationPosted(true)
D/QuickCircle( 1414): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1414): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1414): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1414): post do just update job
D/LgeQuickCoverNotificationData( 1414): showAll3
D/LgeQuickCoverNotificationData( 1414): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1414): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1414): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1414): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1414): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1414): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1414): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1414): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1414): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1414): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1414): updateNotificationData: count=3
I/GLSUser ( 2130): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.talk, service: oauth2:https://www.googleapis.com/auth/chat https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/hangouts https://www.googleapis.com/auth/identity.plus.page.impersonation https://www.googleapis.com/auth/chat.native
I/GLSUser ( 2130): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/chat https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/hangouts https://www.googleapis.com/auth/identity.plus.page.impersonation https://www.googleapis.com/auth/chat.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2130): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2130): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2130): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/QuickStatusbarLayout( 1414): Notification difference=198
D/QuickStatusbarLayout( 1414): child = android.widget.LinearLayout{1813a4 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
W/ApiaryClient( 6498): Error response from books API: {
W/ApiaryClient( 6498):  "error": {
W/ApiaryClient( 6498):   "errors": [
W/ApiaryClient( 6498):    {
W/ApiaryClient( 6498):     "domain": "global",
W/ApiaryClient( 6498):     "reason": "required",
W/ApiaryClient( 6498):     "message": "Login Required",
W/ApiaryClient( 6498):     "locationType": "header",
W/ApiaryClient( 6498):     "location": "Authorization"
W/ApiaryClient( 6498):    }
W/ApiaryClient( 6498):   ],
W/ApiaryClient( 6498):   "code": 401,
W/ApiaryClient( 6498):   "message": "Login Required"
W/ApiaryClient( 6498):  }
W/ApiaryClient( 6498): }
,W/ApiaryClient( 6498): errCount = 3: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6498): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-900266509079114087&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6498): Headers:
W/ApiaryClient( 6498): accept-encoding: [gzip]
W/ApiaryClient( 6498): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6498): gdata-version: 2
I/art     ( 2130): Explicit concurrent mark sweep GC freed 46772(2MB) AllocSpace objects, 17(1959KB) LOS objects, 50% free, 30MB/62MB, paused 1.338ms total 67.138ms
,E/Babel   ( 6844): UserRecoverableAuthException.
E/Babel   ( 6844): cfq: BadAuthentication
E/Babel   ( 6844): 	at cfn.a(Unknown Source)
E/Babel   ( 6844): 	at f.a(PG:191)
E/Babel   ( 6844): 	at ava.a(PG:88)
E/Babel   ( 6844): 	at ava.a(PG:128)
E/Babel   ( 6844): 	at bjs.a(PG:255)
E/Babel   ( 6844): 	at bep.a(PG:602)
E/Babel   ( 6844): 	at bep.a(PG:469)
E/Babel   ( 6844): 	at bpo.run(PG:1141)
,E/Babel   ( 6844): Error getting auth token
E/Babel   ( 6844): bxl
E/Babel   ( 6844): 	at f.a(PG:201)
E/Babel   ( 6844): 	at ava.a(PG:88)
E/Babel   ( 6844): 	at ava.a(PG:128)
E/Babel   ( 6844): 	at bjs.a(PG:255)
E/Babel   ( 6844): 	at bep.a(PG:602)
E/Babel   ( 6844): 	at bep.a(PG:469)
E/Babel   ( 6844): 	at bpo.run(PG:1141)
I/Babel_RequestWriter( 6844): error sending REQ[fc:44; creat:1449594882351; type:bev-259309803]; took 183 ms (error code == 100)
E/Babel   ( 6844): Account registration failedRedacted-21
,E/Babel   ( 6844): bph: null -- null
E/Babel   ( 6844): 	at ava.a(PG:120)
E/Babel   ( 6844): 	at ava.a(PG:128)
E/Babel   ( 6844): 	at bjs.a(PG:255)
E/Babel   ( 6844): 	at bep.a(PG:602)
E/Babel   ( 6844): 	at bep.a(PG:469)
E/Babel   ( 6844): 	at bpo.run(PG:1141)
I/Babel   ( 6844): Account setup failed with error state:106 account:Redacted-21
I/Babel   ( 6844): Account sign in complete with state 106account: Redacted-21
I/art     ( 6844): Note: end time exceeds epoch: 
I/GLSUser ( 2130): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.talk, service: oauth2:https://www.googleapis.com/auth/chat https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/hangouts https://www.googleapis.com/auth/identity.plus.page.impersonation https://www.googleapis.com/auth/chat.native
I/GLSUser ( 2130): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/chat https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/hangouts https://www.googleapis.com/auth/identity.plus.page.impersonation https://www.googleapis.com/auth/chat.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 2130): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2130): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2130): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/ResourcesManager( 2130): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
V/NotificationService( 1029): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1029): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1029): LED remove() : mLights=0|com.google.android.gms|1|null|10005
,D/NotificationServiceEx( 1029): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1029): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1414): onNotificationPosted
D/SmartCoverUpdateMonitor( 1414): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1414): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1414): handleNotificationPosted(true)
D/QuickCircle( 1414): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1414): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1414): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1414): post do just update job
D/LgeQuickCoverNotificationData( 1414): showAll3
D/LgeQuickCoverNotificationData( 1414): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1414): showAll() ID : 1,0|com.google.android.gms|1|null|10005
E/Babel   ( 6844): Unexpected exception while authenticating.
D/LgeQuickCoverNotificationData( 1414): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1414): showNotificationWithSetupData: display=false
E/Babel   ( 6844): cfr: User intervention required. Notification has been pushed.
E/Babel   ( 6844): 	at cfn.b(Unknown Source)
E/Babel   ( 6844): 	at cfn.a(Unknown Source)
E/Babel   ( 6844): 	at f.a(PG:188)
E/Babel   ( 6844): 	at ava.b(PG:143)
E/Babel   ( 6844): 	at bnr.run(PG:5415)
E/Babel   ( 6844): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/Babel   ( 6844): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/Babel   ( 6844): 	at java.lang.Thread.run(Thread.java:818)
D/LgeQuickCoverOverlayWindow( 1414): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1414): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1414): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1414): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1414): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1414): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1414): updateNotificationData: count=3
D/QuickStatusbarLayout( 1414): Notification difference=198
D/QuickStatusbarLayout( 1414): child = android.widget.LinearLayout{1813a4 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,E/BooksSync( 6498): Soft error: ,
E/BooksSync( 6498): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 6498): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-900266509079114087&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 6498): Headers:
E/BooksSync( 6498): accept-encoding: [gzip]
E/BooksSync( 6498): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 6498): gdata-version: 2
E/BooksSync( 6498): 
E/BooksSync( 6498): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 6498): ,	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 6498): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 6498): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 6498): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 6498): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 6498): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 6498): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 6498): ,	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 6498): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 6498): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 6498): {
E/BooksSync( 6498):  "error": {
E/BooksSync( 6498):   "errors": [
E/BooksSync( 6498):    {
E/BooksSync( 6498):     "domain": "global",
E/BooksSync( 6498):     "reason": "required",
E/BooksSync( 6498):     "message": "Login Required",
E/BooksSync( 6498):     "locationType": "header",
E/BooksSync( 6498):     "location": "Authorization"
,E/BooksSync( 6498):    }
E/BooksSync( 6498):   ],
E/BooksSync( 6498):   "code": 401,
E/BooksSync( 6498):   "message": "Login Required"
E/BooksSync( 6498):  }
E/BooksSync( 6498): }
E/BooksSync( 6498): 
E/BooksSync( 6498): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 6498): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 6498): 	... 8 more
,E/BooksSync( 6498): Sync error
E/BooksSync( 6498): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 6498): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-900266509079114087&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 6498): Headers:
E/BooksSync( 6498): accept-encoding: [gzip]
E/BooksSync( 6498): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 6498): gdata-version: 2
E/BooksSync( 6498): 
E/BooksSync( 6498): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 6498): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 6498): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 6498): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 6498): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 6498): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 6498): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 6498): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 6498): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 6498): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 6498): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 6498): {
E/BooksSync( 6498):  "error": {
E/BooksSync( 6498):   "errors": [
E/BooksSync( 6498):    {
E/BooksSync( 6498):     "domain": "global",
E/BooksSync( 6498):     "reason": "required",
E/BooksSync( 6498):     "message": "Login Required",
E/BooksSync( 6498):     "locationType": "header",
E/BooksSync( 6498):     "location": "Authorization"
E/BooksSync( 6498):    }
E/BooksSync( 6498):   ],
E/BooksSync( 6498):   "code": 401,
E/BooksSync( 6498):   "message": "Login Required"
E/BooksSync( 6498):  }
E/BooksSync( 6498): }
E/BooksSync( 6498): 
E/BooksSync( 6498): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 6498): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 6498): 	... 8 more
I/BooksSync( 6498): Finished books sync
,I/ActivityManager( 1029): Killing 6273:com.lge.settings.easy/1000 (adj 15): empty #17
,D/SyncManager( 1029): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 26365, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,W/libprocessgroup( 1029): failed to open /acct/uid_1000/pid_6273/cgroup.procs: No such file or directory
,V/GLSActivity( 2130): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2130): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.syncadapters.contacts, service: cp
,I/GLSUser ( 2130): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> cp without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2130): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2130): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2130): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/NotificationService( 1029): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1029): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1029): LED remove() : mLights=0|com.google.android.gms|1|null|10005,
D/NotificationServiceEx( 1029): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
,D/NotificationServiceEx( 1029): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
W/GLSActivity( 2130): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2130): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2130): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2130): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2130): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2130): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2130): 	at android.os.Binder.execTransact(Binder.java:446)
D/LgeQuickCoverNLService( 1414): onNotificationPosted
,D/SmartCoverUpdateMonitor( 1414): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1414): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1414): handleNotificationPosted(true)
D/QuickCircle( 1414): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1414): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1414): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1414): post do just update job
D/LgeQuickCoverNotificationData( 1414): showAll3
D/LgeQuickCoverNotificationData( 1414): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1414): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1414): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1414): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1414): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1414): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1414): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1414): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1414): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1414): isNotificationForCurrentUser : true
,E/LgeQuickCoverOverlayWindow( 1414): updateNotificationData: count=3
D/ContactsSyncAdapter( 2130): innerSync failed
D/ContactsSyncAdapter( 2130): com.google.wireless.gdata2.client.AuthenticationException: unable to get auth token android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
D/ContactsSyncAdapter( 2130): 	at com.google.android.syncadapters.contacts.AuthInfo.getAuthToken(AuthInfo.java:45)
D/ContactsSyncAdapter( 2130): 	at com.google.android.syncadapters.contacts.ContactsSyncAdapter.innerPerformSync(ContactsSyncAdapter.java:263)
D/ContactsSyncAdapter( 2130): 	at com.google.android.syncadapters.contacts.ContactsSyncAdapter.onPerformLoggedSync(ContactsSyncAdapter.java:168)
D/ContactsSyncAdapter( 2130): 	at com.google.android.common.LoggingThreadedSyncAdapter.onPerformSync(LoggingThreadedSyncAdapter.java:33)
D/ContactsSyncAdapter( 2130): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
D/ContactsSyncAdapter( 2130): Caused by: android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
D/ContactsSyncAdapter( 2130): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
D/ContactsSyncAdapter( 2130): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
D/ContactsSyncAdapter( 2130): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
D/ContactsSyncAdapter( 2130): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
D/ContactsSyncAdapter( 2130): 	at android.os.Binder.execTransact(Binder.java:446)
,D/SyncManager( 1029): failed sync operation thalitester@gmail.com u0 (com.google), com.android.contacts, LOCAL, currentRunTime 322101, reason: 10019, SyncResult: stats [ numAuthExceptions: 1]
D/QuickStatusbarLayout( 1414): Notification difference=198
D/QuickStatusbarLayout( 1414): child = android.widget.LinearLayout{1813a4 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,I/GAV2    ( 6498): Thread[GAThread,5,main]: No campaign data found.
,I/ActivityManager( 1029): Killing 6215:com.lge.sync/1000 (adj 15): empty #17
,W/libprocessgroup( 1029): failed to open /acct/uid_1000/pid_6215/cgroup.procs: No such file or directory
,I/GAV4    ( 6675): Thread[GAThread,5,main]: No campaign data found.
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=38.2, 0.0, 0.0  rx=31.6 bcn=0 [on:0 tx:0 rx:0 period:3005] from screen [on:0 period:-2027495448] gl rssi=-44 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=38.2, 0.0, 0.0  rx=31.6 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-2027495445] gl rssi=-44 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,I/ActivityManager( 1029): Killing 5791:com.uei.lg.quicksetsdk.maxq616/1000 (adj 15): empty #17
,I/QRemote ( 6295): [RemoteControlManager.java:195:onServiceDisconnected()] oooooo start
W/System.err( 6295): android.os.DeadObjectException
,W/System.err( 6295): 	at android.os.BinderProxy.transactNative(Native Method)
W/System.err( 6295): 	at android.os.BinderProxy.transact(Binder.java:496)
W/System.err( 6295): 	at com.uei.control.IControl.unregisterCallback(IControl.java:502)
W/System.err( 6295): 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:199)
W/System.err( 6295): 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
W/System.err( 6295): 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
W/System.err( 6295): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 6295): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 6295): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 6295): 	at android.app.ActivityThread.main(ActivityThread.java:5274)
W/System.err( 6295): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 6295): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 6295): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
W/System.err( 6295): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
E/UEI.SmartControl( 6295): IControl.unregisterCallback error: android.os.DeadObjectException
W/System.err( 6295): android.os.DeadObjectException
W/System.err( 6295): 	at android.os.BinderProxy.transactNative(Native Method)
W/System.err( 6295): 	at android.os.BinderProxy.transact(Binder.java:496)
W/System.err( 6295): 	at com.uei.control.IControl.unregisterSetupReadyCallback(IControl.java:818)
W/System.err( 6295): 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:200)
W/System.err( 6295): 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
W/System.err( 6295): 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
W/System.err( 6295): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 6295): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 6295): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 6295): 	at android.app.ActivityThread.main(ActivityThread.java:5274)
W/System.err( 6295): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 6295): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 6295): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
W/System.err( 6295): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
E/UEI.SmartControl( 6295): IControl.unregisterSetupReadyCallback error: android.os.DeadObjectException
I/QRemote ( 6295): [RemoteControlManager.java:203:onServiceDisconnected()] oooooo Control unbind before rebinding.
W/libprocessgroup( 1029): failed to open /acct/uid_1000/pid_5791/cgroup.procs: No such file or directory
W/ActivityManager( 1029): Scheduling restart of crashed service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service in 1000ms
,D/QRemote ( 6295): [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]10
I/QRemote ( 6295): [RemoteControlManager.java:157:onBindIRService()] oooooo bind
I/ActivityManager( 1029): Start proc com.uei.lg.quicksetsdk.maxq616 for service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service: pid=6925 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
D/QRemote ( 6295): [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
,D/UEI.SmartControl( 6925): Quickset Services start...
,I/UEI.SmartControl( 6925): Manufacture = LGE
D/UEI.SmartControl( 6925): Id = LGNevo
D/UEI.SmartControl( 6925): File observer start...
E/UEI.SmartControl( 6925): IR Port is disabled: false
D/UEI.SmartControl( 6925): Starting file observer...
D/UEI.SmartControl( 6925): Extracting JNI libs...
D/UEI.SmartControl( 6925): --- this system supports 32-bit or 64-bit only
D/UEI.SmartControl( 6925): --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
,D/UEI.SmartControl( 6925): --- Checking lib: libqs_armeabi-v7a.zip
D/UEI.SmartControl( 6925): --- Extracting JNI libs: libqs_armeabi-v7a.zip
I/UEI.SmartControl( 6925): --- Selecting new region: 6
,I/UEI.SmartControl( 6925): Model = LG-D855
D/UEI.SmartControl( 6925): QS Service created
I/UEI.SmartControl( 6925): Service initServices...
,D/UEI.SmartControl( 6925): QS start get config
D/UEI.SmartControl( 6925): Loading JNI Libs...
,I/UEI.SmartControl( 6925): Supports setup maps: true
,D/UEI.SmartControl( 6925): QS start statue = true Error code = 0
I/UEI.SmartControl( 6925): QS version = v2.7.10.1_RC1
I/UEI.SmartControl( 6925): QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
I/UEI.SmartControl( 6925): ### init IR Blaster...
,D/serial_port( 6925): Configuring serial port
E/UEI.SmartControl( 6925): UEIBLaster setting for 616
,I/UEI.SmartControl( 6925): Setting serial record hearder size = 2
I/UEI.SmartControl( 6925): configuring settings for MAXQ616
I/UEI.SmartControl( 6925): Get version...
D/UEI.SmartControl( 6925): serial port data available: 21
,D/UEI.SmartControl( 6925): MAXQ616 A2-X4 software.
,I/UEI.SmartControl( 6925): IR Blaster version: 256702256704300002
I/UEI.SmartControl( 6925): QS saving settings...
D/UEI.SmartControl( 6925): IR Blaster version: 25672567
,D/UEI.SmartControl( 6925): serial port data available: 4
,I/UEI.SmartControl( 6925): Device manager: loading config....
D/UEI.SmartControl( 6925): ----------- loading internal config...
,W/ContextImpl( 6925): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
E/UEI.SmartControl( 6925): Services init done
D/UEI.SmartControl( 6925): QS Service init finished
D/UEI.SmartControl( 6925): QS Service version name: 2.1.91
,D/UEI.SmartControl( 6925): QS Service version code: 201091
D/UEI.SmartControl( 6925): Service requested: Control
E/UEI.SmartControl( 6925): Loading SETTINGS...
D/UEI.SmartControl( 6925): Request IControl service: devices are loaded...
,I/ActivityManager( 1029): Killing 6141:com.android.settings/1000 (adj 15): empty #17
I/QRemote ( 6295): [RemoteControlManager.java:183:onServiceConnected()] oooooo start
I/UEI.SmartControl( 6925): ------ IControl API: 11
I/UEI.SmartControl( 6925): Registering callback...
I/UEI.SmartControl( 6925): ------ IControl API: 19
I/UEI.SmartControl( 6925): Registering Services Ready callback...
D/UEI.SmartControl( 6925): -- Open brand translation xml: brands_translations_ko
,D/WifiService( 1029): Client connection lost with reason: 4
I/UEI.SmartControl( 6925): Notify AllClients services are ready: 0
,I/QRemote ( 6295): [RemoteControlManager.java:660:QSSetupIsReady()] oooooo 140517:sdkIsReady callback... get functions. Result:0
D/QRemote ( 6295): [RemoteControlManager.java:388:handleMessage()] oooooo 140510:START_SESSION
D/UEI.SmartControl( 6925): -----service ready thread exits
D/QRemote ( 6295): [RemoteControlManager.java:394:handleMessage()] oooooo 140510:send retrieve msg
D/QRemote ( 6295): [RemoteControlManager.java:322:handleMessage()] oooooo 140510:handler call retrieveDevices
D/QRemote ( 6295): [RemoteControlManager.java:336:retrieveDevices()] oooooo retrieveDevices: start
I/UEI.SmartControl( 6925): ------ IControl API: 8
D/QRemote ( 6295): [RemoteControlManager.java:340:retrieveDevices()] oooooo retrieveDevices: 0
D/QRemote ( 6295): [RemoteControlManager.java:345:retrieveDevices()] oooooo retrieveDevices complete:true
D/QRemote ( 6295): [RemoteControlManager.java:353:retrieveDevices()] oooooo retrieveDevices: notifyDataSetChanged()
D/QRemote ( 6295): [QRemoteApplication.java:145:onRemoteControlStateChanged()] oooooo onRemoteControlStateChanged called in QRemoteApp
D/QRemote ( 6295): [QRemoteApplication.java:158:onRemoteControlStateChanged()] oooooo Widget count is [1]. send broadcast
D/QRemote ( 6295): [QRemoteApplication.java:160:onRemoteControlStateChanged()] oooooo Widget[0]:3
D/UEI.SmartControl( 6925): Internal service binding...
W/libprocessgroup( 1029): failed to open /acct/uid_1000/pid_6141/cgroup.procs: No such file or directory
,D/QRemote ( 6295): [QRemoteApplication.java:188:onRemoteControlStateChanged()] oooooo 140526:onRemoteControlStateChanged&sdkIsReady. stop Service
V/QRemote ( 6295): [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
D/QRemote ( 6295): [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
,E/QRemote ( 6295): [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
,D/QRemote ( 6295): [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
D/QRemote ( 6295): [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
D/QRemote ( 6295): [RemoteAppWidgetProvider.java:506:onUpdate()] oooooo 140510:RetrieveDevices complete. Start loading
D/QRemote ( 6295): [RemoteAppWidgetProvider.java:508:onUpdate()] oooooo 140510:appWidgetIds[0]:3 loading
D/QRemote ( 6295): [RemoteAppWidgetManager.java:41:startLoading()] oooooo 140518:widgetId[3] loading start at [1449671451579]
,I/art     ( 1029): Explicit concurrent mark sweep GC freed 20986(1064KB) AllocSpace objects, 7(752KB) LOS objects, 33% free, 44MB/66MB, paused 2.575ms total 156.180ms
,D/QRemote ( 6295): [RemoteAppWidgetManager.java:239:doInBackground()] oooooo 140407:doinBack arr:0
V/QRemote ( 6295): [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.widget_ui_update
,E/QRemote ( 6295): [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
D/QRemote ( 6295): [RemoteAppWidgetProvider.java:171:onReceive()] oooooo total:0
D/QRemote ( 6295): [RemoteAppWidgetProvider.java:172:onReceive()] oooooo selected:0
D/QRemote ( 6295): [RemoteAppWidgetProvider.java:173:onReceive()] oooooo arr:[]
D/QRemote ( 6295): [RemoteAppWidgetProvider.java:174:onReceive()] oooooo appWidgetId:3
D/QRemote ( 6295): [RemoteAppWidgetProvider.java:815:updateRemoteViews()] oooooo UpdateRemoteViews3:widgetId:3
D/QRemote ( 6295): [RemoteAppWidgetProvider.java:986:updateRemoteViews()] oooooo updateAppWidget5:widgetId:3]
,I/ActivityManager( 1029): Killing 6463:com.lge.appbox.client/u0a11 (adj 15): empty #17
W/libprocessgroup( 1029): failed to open /acct/uid_10011/pid_6463/cgroup.procs: No such file or directory
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-43 f=2412 sc=60 link=72 tx=20.6, 0.0, 0.0  rx=16.8 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-2027492420] gl rssi=-43 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-43 f=2412 sc=60 link=72 tx=20.6, 0.0, 0.0  rx=16.8 bcn=0 [on:0 tx:0 rx:0 period:12] from screen [on:0 period:-2027492408] gl rssi=-43 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
W/System.err( 6630): java.net.SocketTimeoutException
,W/System.err( 6630): 	at libcore.io.IoBridge.maybeThrowAfterRecvfrom(IoBridge.java:598)
W/System.err( 6630): 	at libcore.io.IoBridge.recvfrom(IoBridge.java:556)
W/System.err( 6630): 	at java.net.PlainDatagramSocketImpl.doRecv(PlainDatagramSocketImpl.java:163)
W/System.err( 6630): 	at java.net.PlainDatagramSocketImpl.receive(PlainDatagramSocketImpl.java:171)
W/System.err( 6630): 	at java.net.DatagramSocket.receive(DatagramSocket.java:274)
W/System.err( 6630): 	at com.lge.drmservice.activation.DrmSntpClient.processRequest(DrmSntpClient.java:257)
W/System.err( 6630): 	at com.lge.drmservice.activation.DrmSntpClient.run(DrmSntpClient.java:127)
W/System.err( 6630): Caused by: android.system.ErrnoException: recvfrom failed: EAGAIN (Try again)
W/System.err( 6630): 	at libcore.io.Posix.recvfromBytes(Native Method)
W/System.err( 6630): 	at libcore.io.Posix.recvfrom(Posix.java:161)
W/System.err( 6630): 	at libcore.io.BlockGuardOs.recvfrom(BlockGuardOs.java:250)
W/System.err( 6630): 	at libcore.io.IoBridge.recvfrom(IoBridge.java:553)
W/System.err( 6630): 	... 5 more
D/DrmSntpClient( 6630): Server : 1
,D/libc-netbsd(  323): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  323): res_queryN name = nist1-la.ustiming.org, class = 1, type = 1
D/libc-netbsd(  323): res_queryN name = nist1-la.ustiming.org., class = 1, type = 1
,D/DSQN    ( 1029): Dns fail occured do internet check.
,D/DSQN    ( 1029): EVENT_INTERNET_CHECK_REQUEST received
D/DSQN    ( 1029): try Internet connection check
W/System.err( 6630): java.net.UnknownHostException: Unable to resolve host "nist1-la.ustiming.org": No address associated with hostname
,W/System.err( 6630): 	at java.net.InetAddress.lookupHostByName(InetAddress.java:462)
W/System.err( 6630): 	at java.net.InetAddress.getAllByNameImpl(InetAddress.java:252)
W/System.err( 6630): 	at java.net.InetAddress.getByName(InetAddress.java:305)
W/System.err( 6630): 	at com.lge.drmservice.activation.DrmSntpClient.processRequest(DrmSntpClient.java:231)
D/libc-netbsd(  323): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  323): res_queryN name = clients3.google.com, class = 1, type = 1
D/libc-netbsd(  323): res_queryN name = clients3.google.com succeed
D/DSQN    ( 1029): ThreadTCPConnectionCheck connect try to216.58.209.46
W/System.err( 6630): 	at com.lge.drmservice.activation.DrmSntpClient.run(DrmSntpClient.java:127)
W/System.err( 6630): Caused by: android.system.GaiException: android_getaddrinfo failed: EAI_NODATA (No address associated with hostname)
W/System.err( 6630): 	at libcore.io.Posix.android_getaddrinfo(Native Method)
W/System.err( 6630): 	at libcore.io.ForwardingOs.android_getaddrinfo(ForwardingOs.java:55)
W/System.err( 6630): 	at java.net.InetAddress.lookupHostByName(InetAddress.java:443)
W/System.err( 6630): 	... 4 more
D/DrmSntpClient( 6630): Server : 2
D/libc-netbsd(  323): default dns: query_ipv6=0, query_ipv4=1
,D/libc-netbsd(  323): res_queryN name = time-nw.nist.gov, class = 1, type = 1
D/DSQN    ( 1029): ThreadInternetCheck internet check OK 
,D/libc-netbsd(  323): res_queryN name = time-nw.nist.gov succeed
,I/LGDrmClient( 6630): _DRM_ServiceGet() : Bind lgdrm service
,V/ILGDrmService(  332): eDRM_SetDRMTime +++
I/LGDRM   (  332): [DRM] SET TIME : YR=2015, MON=12, DAY=9
I/LGDRM   (  332): [DRM] SET TIME : HR=14, MIN=30, SEC=55
V/ILGDrmService(  332): eDRM_SetDRMTime ---
,I/DrmSntpClient( 6630): Synched
D/DrmService( 6630): Completed !! request = 2
D/DrmService( 6630): Request count = 0
V/DrmService( 6630): Service onDestroy
I/ActivityManager( 1029): Killing 6187:com.lge.formmanager/u0a26 (adj 15): empty #17
W/libprocessgroup( 1029): failed to open /acct/uid_10026/pid_6187/cgroup.procs: No such file or directory
,D/DSQN    ( 1029): EVENT_INTERNET_CHECK_ENABLE received
,D/UEI.SmartControl( 6925): Internal timer expired: 1
D/UEI.SmartControl( 6925): unbind internal service
,D/serial_port( 6925): close(fd = 25)
I/UEI.SmartControl( 6925): Serial port is closed.
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-43 f=2412 sc=60 link=72 tx=10.3, 0.0, 0.0  rx=8.4 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-2027489384] gl rssi=-43 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-43 f=2412 sc=60 link=72 tx=10.3, 0.0, 0.0  rx=8.4 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-2027489381] gl rssi=-43 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=11.1, 0.0, 0.0  rx=8.7 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-2027486352] gl rssi=-44 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=11.1, 0.0, 0.0  rx=8.7 bcn=0 [on:0 tx:0 rx:0 period:13] from screen [on:0 period:-2027486339] gl rssi=-44 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
D/PowerManagerServiceEx( 1029): acquireWakeLockInternal: lock=518109269, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1029
,D/[Concierge]Service( 2608): onStartCommand(). Type : 9
,V/QRemote ( 6295): [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.wait_loading
,D/QRemote ( 6295): [RemoteAppWidgetProvider.java:211:onReceive()] oooooo 140514:alarm msg received!:2876
D/PowerManagerServiceEx( 1029): releaseWakeLockInternal: lock=518109269 [*alarm*], flags=0x0
D/sensors_hal_Time( 1029): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1029): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1029): tsOffsetIs: Apps: 306312179157; DSPS: 10177971; Offset : -4305895076
,I/[SystemUI]TimeTickManager( 1462): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1462): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1462): called onTimeUpdated()
I/[SystemUI]Clock( 1462): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1462): called onTimeUpdated()
I/[SystemUI]DateView( 1462): called onTimeUpdated()
I/[SystemUI]DateView( 1462): called onTimeUpdated()
,D/KeyguardUpdateMonitor( 1462): handleTimeUpdate
E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=5.6, 0.0, 0.0  rx=4.4 bcn=0 [on:0 tx:0 rx:0 period:3005] from screen [on:0 period:-2027483316] gl rssi=-44 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=5.6, 0.0, 0.0  rx=4.4 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-2027483313] gl rssi=-44 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,I/[SystemUI]QPairHandler( 1462): onReceive = android.intent.action.PACKAGE_CHANGED
,I/InputReader( 1029): Reconfiguring input devices.  changes=0x00000010
,D/SplitUIService( 1888): replaced split : contains_com.google.android.talk / true
I/art     (  353): Background concurrent mark sweep GC freed 788(33KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 5.844ms total 34.779ms
,I/ActivityManager( 1029): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.manager.PreloadListManagerHelper: pid=6973 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,I/[SystemUI]QSlideListController( 1462): onReceive = android.intent.action.PACKAGE_CHANGED
I/[SystemUI]AppWidgetPanel(QRemoteWidgetPanel)( 1462): onReceive = android.intent.action.PACKAGE_CHANGED, packageName : com.google.android.talk
D/SplitUIManager( 1888): split_name #11 / not available #0
I/SplitUIService( 1888): split app #11
I/art     (  353): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 1.368ms total 42.991ms
,D/administrator( 1029): Handling package changes for user 0
I/art     (  353): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 429us total 21.002ms
,I/[LGHome]EVENT( 2086): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.talk flg=0x4000010 (has extras) }
W/ResourcesManager( 2086): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/art     (  353): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 401us total 19.443ms
I/[LGHome]Launcher( 2086): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,I/AppUp4:AppBoxCP( 6973): onCreate
W/AppUp4:DB( 6973):  [AppBoxDatabaseHelper] construct
,I/AppUp4:DB( 6973):  setFingerPrint start
I/AppUp4:DB( 6973):  newfinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys SDK version = 21
I/NotificationService( 1029): action=android.intent.action.PACKAGE_CHANGED queryReplace=false
D/BackupManagerService( 1029): Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.talk flg=0x4000010 (has extras) }
I/AppUp4:DB( 6973):  beforefinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys
I/AppUp4:DB( 6973):  SDK version = 21
,I/AppUp4:DB( 6973):  beforefinger == newfinger no write in DB
,W/ResourcesManager( 1029): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
D/AppUp4:AppBoxApplication( 6973): AppBoxApplication onCreate()
,I/AppUp4:CustModeStarterReceiver( 6973): onReceive
D/LgDataFeature( 6973): LgDataFeature() Constructor: none
D/LgDataFeature( 6973): LgDataFeature() Constructor Done, null
,D/AppUp4:CustFacade( 6973): Context : android.app.ReceiverRestrictedContext@201ec749
D/AppUp4:CustFacade( 6973): isCustomizationCompleted : false
D/AppUp4:CustFacade( 6973): isPhone : true
D/AppUp4:CustModeStarterReceiver( 6973): begin check event
I/AppUp4:CustModeStarterReceiver( 6973): Event For Nothing, skip.
W/ResourcesManager( 1029): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourceType( 1029): Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
,I/ActivityManager( 1029): Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=7010 uid=10019 gids={50019, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
,I/ActivityManager( 1029): Killing 6630:com.lge.drmservice/u0a62 (adj 15): empty #17
W/libprocessgroup( 1029): failed to open /acct/uid_10062/pid_6630/cgroup.procs: No such file or directory
,I/[LGHome]EVENT( 2086): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
W/ResourcesManager( 7010): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 7010): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 7010): Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
W/ResourcesManager( 7010): Asset path '/system/framework/lghiddenlibs.jar' does not exist or contains no resources.
W/ResourcesManager( 7010): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
I/SystemConfig( 7010): BUILD Country: EU
I/SystemConfig( 7010): BUILD Operator: OPEN
,I/ActivityManager( 1029): Killing 6675:com.google.android.apps.magazines/u0a93 (adj 15): empty #17
,W/libprocessgroup( 1029): failed to open /acct/uid_10093/pid_6675/cgroup.procs: No such file or directory
,I/SystemConfig( 7010): pm.hasSystemFeature(com.lge.ims.rcs) = false
I/SystemConfig( 7010): existFile = false
I/SystemConfig( 7010): canReadFile = false
I/SystemConfig( 7010): systemFeature RCS result false
,D/SystemConfig( 7010): refreshRcsSupport() :false
,I/UpdateIcingCorporaServi( 4193): Updating corpora: APPS=com.google.android.talk, CONTACTS=MAYBE
,I/ActivityManager( 1029): Start proc com.lge.lockscreensettings for broadcast com.lge.lockscreensettings/.PackageIntentReceiver: pid=7052 uid=10080 gids={50080, 9997, 1028, 1015} abi=armeabi-v7a
,V/SIM_STK ( 1029): Menu title from STK is T-Mobile
,I/LockScreenSettings( 7052): Wallpaper base directory = /data/data/com.lge.lockscreensettings/files/
,W/ResourcesManager( 4193): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/UpdateIcingCorporaServi( 4193): UpdateCorporaTask done [took 137 ms] updated apps [took 137 ms] 
D/LockScreenSettings( 7052): Quick window widget present in DB = com.lge.clock.quickcover.QuickCoverSettingActivity  true
D/LockScreenSettings( 7052): Quick window widget present in DB = com.lge.camera.app.QuickWindowCameraActivity  true
D/LockScreenSettings( 7052): Quick window widget present in DB = com.android.contacts.activities.QuickCircleActivity  true
D/LockScreenSettings( 7052): Quick window widget present in DB = com.android.mms.quickcover.QuickCoverActivity  true
D/LockScreenSettings( 7052): Quick window widget present in DB = com.lge.music.MusicQuickCircle  true
D/LockScreenSettings( 7052): Quick window widget present in DB = com.lge.lifetracker.QuickCover  true
I/ActivityManager( 1029): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=7082 uid=10044 gids={50044, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager( 1029): Killing 6564:com.android.chrome/u0a57 (adj 15): empty #17
W/libprocessgroup( 1029): failed to open /acct/uid_10057/pid_6564/cgroup.procs: No such file or directory
,D/Finsky  ( 7082): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,D/LgDataFeature( 7082): LgDataFeature() Constructor: none
,D/LgDataFeature( 7082): LgDataFeature() Constructor Done, null
,D/Finsky  ( 7082): [1] DailyHygiene.goMakeHygieneIfDirty: Dirty, need more hygiene.
,I/ActivityManager( 1029): Start proc com.google.android.gms:car for service com.google.android.gms/.car.CarService: pid=7125 uid=10005 gids={50005, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
,W/Settings( 7082): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
W/Settings( 7082): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/ResourcesManager( 7125): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 7125): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/DownloadManager( 3299): starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3299): created cursor android.database.sqlite.SQLiteCursor@21566574 on behalf of 7082
I/MultiDex( 7125): VM with version 2.1.0 has multidex support
,I/MultiDex( 7125): install
I/MultiDex( 7125): VM has multidex support, MultiDex support library is disabled.
,D/Finsky  ( 7082): [1] 2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 7082): [1] 2.run: Finished loading 1 libraries.
,D/Finsky  ( 7082): [1] GmsCoreHelper.cleanupNlp: result=false type=4
D/PackageBroadcastService( 2363): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.talk
,V/JNIHelp ( 7125): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
D/Finsky  ( 7082): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
I/ActivityManager( 1029): Start proc com.google.android.gms.wearable for service com.google.android.gms/.wearable.service.WearableControlService: pid=7160 uid=10005 gids={50005, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
,I/PeopleContactsSync( 2363): CP2 sync disabled
,W/ActivityThread( 7125): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 7125): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@65eecd1: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 7125): Installed default security provider GmsCore_OpenSSL
I/ActivityManager( 1029): Killing 6546:com.lge.email/u0a23 (adj 15): empty #17
,D/GCM     ( 2130): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,W/libprocessgroup( 1029): failed to open /acct/uid_10023/pid_6546/cgroup.procs: No such file or directory
D/AuthorizationBluetoothService( 2130): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,V/GmsCoreStatsServiceLauncher( 2363): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
W/ResourcesManager( 7160): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 7160): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,D/LocationInitializer( 2363): Restart initialization of location
I/MultiDex( 7160): VM with version 2.1.0 has multidex support
I/MultiDex( 7160): install
I/MultiDex( 7160): VM has multidex support, MultiDex support library is disabled.
,V/JNIHelp ( 7160): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,W/ActivityThread( 7160): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 7160): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@65eecd1: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 7160): Installed default security provider GmsCore_OpenSSL
,W/NativeLibraryUtils( 7160): Install did not work
W/NativeLibraryUtils( 7160): java.io.IOException: fcntl failed: EAGAIN (Try again)
W/NativeLibraryUtils( 7160): 	at java.nio.FileChannelImpl.basicLock(FileChannelImpl.java:123)
W/NativeLibraryUtils( 7160): 	at java.nio.FileChannelImpl.tryLock(FileChannelImpl.java:181)
W/NativeLibraryUtils( 7160): 	at java.nio.channels.FileChannel.tryLock(FileChannel.java:584)
W/NativeLibraryUtils( 7160): 	at com.google.android.gms.common.util.ax.a(SourceFile:314)
W/NativeLibraryUtils( 7160): 	at com.google.android.gms.common.app.a.run(SourceFile:136)
W/NativeLibraryUtils( 7160): Caused by: android.system.ErrnoException: fcntl failed: EAGAIN (Try again)
W/NativeLibraryUtils( 7160): 	at libcore.io.Posix.fcntlFlock(Native Method)
W/NativeLibraryUtils( 7160): 	at libcore.io.ForwardingOs.fcntlFlock(ForwardingOs.java:70)
W/NativeLibraryUtils( 7160): 	at java.nio.FileChannelImpl.basicLock(FileChannelImpl.java:121)
W/NativeLibraryUtils( 7160): 	... 4 more
,D/WearableService( 7160): callingUid 10005, callindPid: 7160
E/MDM     ( 1836): [86] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,D/GCM     ( 2130): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
D/AuthorizationBluetoothService( 2130): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,V/GmsCoreStatsServiceLauncher( 2363): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,E/MDM     ( 1836): [87] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
D/LocationInitializer( 2363): Restart initialization of location
,V/Finsky  ( 7082): [1] GearheadStateMonitor.onReady: sIsProjecting:false
,D/Finsky  ( 7082): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
,V/AlarmManager( 1029): RTC_WAKEUP set : Alarm{31d6aa78 type 0 when 1449671465297 com.android.vending} when 1449671465297
V/GLSActivity( 2130): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2130): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 2130): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2130): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2130): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2130): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/Finsky  ( 7082): [1] 1.onErrorResponse: Unable to preload experiments: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,V/GLSActivity( 2130): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/GLSUser ( 2130): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 2130): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 2130): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2130): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2130): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/GLSActivity( 2130): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2130): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 2130): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2130): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2130): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2130): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/Finsky  ( 7082): [1] LibraryUpdateListener.onErrorResponse: Library replication failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,V/SIM_STK ( 1029): Menu title from STK is T-Mobile
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=2.8, 0.0, 0.0  rx=2.2 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-2027480293] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=2.8, 0.0, 0.0  rx=2.2 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-2027480292] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,V/GLSActivity( 2130): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2130): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 2130): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2130): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2130): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2130): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/Finsky  ( 7082): [1] 2.onErrorResponse: Update check failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,D/Finsky  ( 7082): [1] DailyHygiene.logDeviceFeaturesAndContinue: Logging device features
D/Finsky  ( 7082): [1] DailyHygiene.flushEventLogsAndContinue: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 7082): [1] DailyHygiene.reschedule: Scheduling new run in 84 minutes (failures=3)
,D/DeviceConnectionService( 1836): client connected with version: 7571000
E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=1.4, 0.0, 0.0  rx=1.1 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:-2027477273] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=1.4, 0.0, 0.0  rx=1.1 bcn=0 [on:0 tx:0 rx:0 period:16] from screen [on:0 period:-2027477257] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
I/ActivityManager( 1029): Killing 5113:com.wsandroid.suite.lge/1000 (adj 15): empty #17
,W/libprocessgroup( 1029): failed to open /acct/uid_1000/pid_5113/cgroup.procs: No such file or directory
,I/ActivityManager( 1029): Killing 6799:com.qualcomm.timeservice/1000 (adj 15): empty #17
,W/libprocessgroup( 1029): failed to open /acct/uid_1000/pid_6799/cgroup.procs: No such file or directory
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-43 f=2412 sc=60 link=72 tx=1.7, 0.0, 0.0  rx=1.5 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:-2027474240] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-43 f=2412 sc=60 link=72 tx=1.7, 0.0, 0.0  rx=1.5 bcn=0 [on:0 tx:0 rx:0 period:14] from screen [on:0 period:-2027474226] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
V/AlarmManager( 1029): ELAPSED_WAKEUP set : Alarm{1f69e5ab type 2 when 320099 android} when 320099
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-43 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-2027471206] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-43 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-2027471203] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-43 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-2027468173] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-43 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-2027468170] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1029):  ConnectedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 1 0
E/WifiStateMachine( 1029):  L2ConnectedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 1 0
E/WifiStateMachine( 1029):  ConnectModeState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 1 0
E/WifiStateMachine( 1029):  DriverStartedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 1 0
E/WifiStateMachine( 1029):  SupplicantStartedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 1 0
E/WifiStateMachine( 1029):  DefaultState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 1 0
,D/sensors_hal_Time( 1029): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1029): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1029): tsOffsetIs: Apps: 326314023733; DSPS: 10833392; Offset : -4305912150
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.2, 0.0, 0.0  rx=0.2 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:-2027465138] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.2, 0.0, 0.0  rx=0.2 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-2027465135] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,V/AlarmManager( 1029): RTC_WAKEUP set : Alarm{16aa27a1 type 0 when 1449671480569 com.android.vending} when 1449671480569
,V/SIM_STK ( 1029): Menu title from STK is T-Mobile
,V/GLSActivity( 2130): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2130): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 2130): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2130): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2130): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2130): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/Finsky  ( 7082): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 7082): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 7082): [1] 5.onFinished: Scheduling replication attempt 1.
E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-2027462109] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-2027462106] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-2027459081] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:14] from screen [on:0 period:-2027459067] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-2027456045] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-2027456035] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-2027453020] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-2027453017] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=1.5, 0.0, 0.0  rx=1.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-2027449990] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=1.5, 0.0, 0.0  rx=1.0 bcn=0 [on:0 tx:0 rx:0 period:13] from screen [on:0 period:-2027449977] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.5 bcn=0 [on:0 tx:0 rx:0 period:3000] from screen [on:0 period:-2027446957] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.5 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-2027446954] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,D/sensors_hal_Time( 1029): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1029): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1029): tsOffsetIs: Apps: 346316061069; DSPS: 11488819; Offset : -4305919414
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.3 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-2027443933] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.3 bcn=0 [on:0 tx:0 rx:0 period:13] from screen [on:0 period:-2027443920] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
V/AlarmManager( 1029): RTC_WAKEUP set : Alarm{26f78f38 type 0 when 1449671502162 com.android.vending} when 1449671502162
,V/SIM_STK ( 1029): Menu title from STK is T-Mobile
,V/GLSActivity( 2130): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     ( 1029): Explicit concurrent mark sweep GC freed 47575(2MB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 44MB/66MB, paused 2.355ms total 134.301ms
,I/GLSUser ( 2130): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 2130): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2130): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2130): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2130): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/Finsky  ( 7082): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 7082): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 7082): [1] 5.onFinished: Scheduling replication attempt 2.
,V/AlarmManager( 1029): ELAPSED_WAKEUP set : Alarm{28b3f5a type 2 when 350131 android} when 350131
,I/BooksSync( 6498): Starting books sync
D/BooksSync( 6498): started syncMyEbooks
,I/art     ( 2130): Explicit concurrent mark sweep GC freed 24671(1396KB) AllocSpace objects, 6(864KB) LOS objects, 51% free, 30MB/62MB, paused 2.055ms total 91.807ms
,V/GLSActivity( 2130): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/GLSUser ( 2130): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 2130): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2130): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2130): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2130): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1029): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1029): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1029): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1029): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1029): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
W/GLSActivity( 2130): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2130): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2130): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2130): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2130): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2130): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2130): 	at android.os.Binder.execTransact(Binder.java:446)
D/LgeQuickCoverNLService( 1414): onNotificationPosted
D/SmartCoverUpdateMonitor( 1414): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1414): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1414): handleNotificationPosted(true)
D/QuickCircle( 1414): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1414): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1414): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1414): post do just update job
D/LgeQuickCoverNotificationData( 1414): showAll3
D/LgeQuickCoverNotificationData( 1414): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1414): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1414): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1414): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1414): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1414): isNotificationForCurrentUser : true
,D/LgeQuickCoverOverlayWindow( 1414): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1414): isNotificationForCurrentUser : true
E/BooksAccountManager( 6498): Authentication error
E/BooksAccountManager( 6498): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6498): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6498): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6498): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6498): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6498): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6498): null auth token
D/LgeQuickCoverOverlayWindow( 1414): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1414): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1414): updateNotificationData: count=3
D/QuickStatusbarLayout( 1414): Notification difference=198
D/QuickStatusbarLayout( 1414): child = android.widget.LinearLayout{1813a4 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,V/GLSActivity( 2130): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2130): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.syncadapters.contacts, service: cp
I/GLSUser ( 2130): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> cp without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2130): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2130): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2130): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ApiaryClient( 6498): Error response from books API: {
W/ApiaryClient( 6498):  "error": {
W/ApiaryClient( 6498):   "errors": [
W/ApiaryClient( 6498):    {
W/ApiaryClient( 6498):     "domain": "global",
W/ApiaryClient( 6498):     "reason": "required",
W/ApiaryClient( 6498):     "message": "Login Required",
W/ApiaryClient( 6498):     "locationType": "header",
W/ApiaryClient( 6498):     "location": "Authorization"
W/ApiaryClient( 6498):    }
W/ApiaryClient( 6498):   ],
W/ApiaryClient( 6498):   "code": 401,
W/ApiaryClient( 6498):   "message": "Login Required"
W/ApiaryClient( 6498):  }
W/ApiaryClient( 6498): }
,W/ApiaryClient( 6498): errCount = 1: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6498): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=6773339652298031869&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6498): Headers:
W/ApiaryClient( 6498): accept-encoding: [gzip]
W/ApiaryClient( 6498): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6498): gdata-version: 2
V/NotificationService( 1029): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
V/NotificationService( 1029): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1029): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1029): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1029): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
W/GLSActivity( 2130): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2130): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2130): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2130): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2130): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2130): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2130): 	at android.os.Binder.execTransact(Binder.java:446)
,D/ContactsSyncAdapter( 2130): innerSync failed
D/ContactsSyncAdapter( 2130): com.google.wireless.gdata2.client.AuthenticationException: unable to get auth token android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
D/ContactsSyncAdapter( 2130): 	at com.google.android.syncadapters.contacts.AuthInfo.getAuthToken(AuthInfo.java:45)
D/ContactsSyncAdapter( 2130): 	at com.google.android.syncadapters.contacts.ContactsSyncAdapter.innerPerformSync(ContactsSyncAdapter.java:263)
D/ContactsSyncAdapter( 2130): 	at com.google.android.syncadapters.contacts.ContactsSyncAdapter.onPerformLoggedSync(ContactsSyncAdapter.java:168)
D/ContactsSyncAdapter( 2130): 	at com.google.android.common.LoggingThreadedSyncAdapter.onPerformSync(LoggingThreadedSyncAdapter.java:33)
D/ContactsSyncAdapter( 2130): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
D/ContactsSyncAdapter( 2130): Caused by: android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
D/ContactsSyncAdapter( 2130): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
D/ContactsSyncAdapter( 2130): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
D/ContactsSyncAdapter( 2130): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
D/ContactsSyncAdapter( 2130): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
D/ContactsSyncAdapter( 2130): 	at android.os.Binder.execTransact(Binder.java:446)
D/LgeQuickCoverNLService( 1414): onNotificationPosted
D/SmartCoverUpdateMonitor( 1414): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1414): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1414): handleNotificationPosted(true)
D/QuickCircle( 1414): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1414): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1414): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1414): post do just update job
D/LgeQuickCoverNotificationData( 1414): showAll3
D/LgeQuickCoverNotificationData( 1414): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1414): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1414): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1414): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1414): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1414): isNotificationForCurrentUser : true
,D/LgeQuickCoverOverlayWindow( 1414): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1414): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1414): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1414): isNotificationForCurrentUser : true
D/SyncManager( 1029): failed sync operation thalitester@gmail.com u0 (com.google), com.android.contacts, LOCAL, currentRunTime 322101, reason: 10019, SyncResult: stats [ numAuthExceptions: 1]
D/SyncManager( 1029): not retrying sync operation because the error is a hard error: thalitester@gmail.com u0 (com.google), com.android.contacts, LOCAL, currentRunTime 412560, reason: 10019
E/LgeQuickCoverOverlayWindow( 1414): updateNotificationData: count=3
,D/QuickStatusbarLayout( 1414): Notification difference=198
,D/QuickStatusbarLayout( 1414): child = android.widget.LinearLayout{1813a4 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.2, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-2027440898] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.2, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-2027440895] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,V/GLSActivity( 2130): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2130): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2130): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2130): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2130): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2130): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1029): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1029): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1029): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1029): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1029): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1414): onNotificationPosted
,D/SmartCoverUpdateMonitor( 1414): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1414): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1414): handleNotificationPosted(true)
D/QuickCircle( 1414): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1414): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1414): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1414): post do just update job
D/LgeQuickCoverNotificationData( 1414): showAll3
D/LgeQuickCoverNotificationData( 1414): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1414): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1414): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1414): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1414): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1414): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1414): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1414): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1414): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1414): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1414): updateNotificationData: count=3
,W/GLSActivity( 2130): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2130): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2130): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2130): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2130): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2130): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2130): 	at android.os.Binder.execTransact(Binder.java:446)
E/BooksAccountManager( 6498): Authentication error
E/BooksAccountManager( 6498): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6498): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6498): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6498): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6498): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6498): 	at android.os.Binder.execTransact(Binder.java:446)
,E/HttpHelper( 6498): null auth token
D/QuickStatusbarLayout( 1414): Notification difference=198
D/QuickStatusbarLayout( 1414): child = android.widget.LinearLayout{1813a4 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
W/ApiaryClient( 6498): Error response from books API: {
W/ApiaryClient( 6498):  "error": {
W/ApiaryClient( 6498):   "errors": [
W/ApiaryClient( 6498):    {
W/ApiaryClient( 6498):     "domain": "global",
W/ApiaryClient( 6498):     "reason": "required",
W/ApiaryClient( 6498):     "message": "Login Required",
W/ApiaryClient( 6498):     "locationType": "header",
W/ApiaryClient( 6498):     "location": "Authorization"
W/ApiaryClient( 6498):    }
W/ApiaryClient( 6498):   ],
W/ApiaryClient( 6498):   "code": 401,
W/ApiaryClient( 6498):   "message": "Login Required"
W/ApiaryClient( 6498):  }
W/ApiaryClient( 6498): }
,W/ApiaryClient( 6498): errCount = 2: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6498): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=6773339652298031869&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6498): Headers:
W/ApiaryClient( 6498): accept-encoding: [gzip]
W/ApiaryClient( 6498): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6498): gdata-version: 2
V/GLSActivity( 2130): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2130): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2130): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 2130): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2130): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2130): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1029): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1029): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1029): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1029): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1029): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1414): onNotificationPosted
,D/SmartCoverUpdateMonitor( 1414): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1414): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1414): handleNotificationPosted(true)
D/QuickCircle( 1414): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1414): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1414): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1414): post do just update job
D/LgeQuickCoverNotificationData( 1414): showAll3
D/LgeQuickCoverNotificationData( 1414): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1414): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1414): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1414): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1414): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1414): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1414): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1414): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1414): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1414): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1414): updateNotificationData: count=3
W/GLSActivity( 2130): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2130): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2130): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2130): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2130): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2130): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2130): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 6498): Authentication error
E/BooksAccountManager( 6498): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6498): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6498): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6498): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6498): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6498): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6498): null auth token
D/QuickStatusbarLayout( 1414): Notification difference=198
D/QuickStatusbarLayout( 1414): child = android.widget.LinearLayout{1813a4 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,W/ApiaryClient( 6498): Error response from books API: {
W/ApiaryClient( 6498):  "error": {
W/ApiaryClient( 6498):   "errors": [
W/ApiaryClient( 6498):    {
W/ApiaryClient( 6498):     "domain": "global",
W/ApiaryClient( 6498):     "reason": "required",
W/ApiaryClient( 6498):     "message": "Login Required",
W/ApiaryClient( 6498):     "locationType": "header",
W/ApiaryClient( 6498):     "location": "Authorization"
W/ApiaryClient( 6498):    }
W/ApiaryClient( 6498):   ],
W/ApiaryClient( 6498):   "code": 401,
W/ApiaryClient( 6498):   "message": "Login Required"
W/ApiaryClient( 6498):  }
W/ApiaryClient( 6498): }
,W/ApiaryClient( 6498): errCount = 3: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6498): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=6773339652298031869&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6498): Headers:
W/ApiaryClient( 6498): accept-encoding: [gzip]
W/ApiaryClient( 6498): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6498): gdata-version: 2
E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=1.1, 0.0, 0.0  rx=1.1 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-2027437864] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=1.1, 0.0, 0.0  rx=1.1 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-2027437861] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,E/BooksSync( 6498): Soft error: 
E/BooksSync( 6498): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 6498): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=6773339652298031869&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 6498): Headers:
E/BooksSync( 6498): accept-encoding: [gzip]
E/BooksSync( 6498): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 6498): gdata-version: 2
E/BooksSync( 6498): 
E/BooksSync( 6498): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 6498): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 6498): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 6498): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 6498): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 6498): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 6498): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 6498): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 6498): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 6498): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 6498): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 6498): {
E/BooksSync( 6498):  "error": {
E/BooksSync( 6498):   "errors": [
E/BooksSync( 6498):    {
E/BooksSync( 6498):     "domain": "global",
E/BooksSync( 6498):     "reason": "required",
E/BooksSync( 6498):     "message": "Login Required",
E/BooksSync( 6498):     "locationType": "header",
E/BooksSync( 6498):     "location": "Authorization"
E/BooksSync( 6498):    }
E/BooksSync( 6498):   ],
E/BooksSync( 6498):   "code": 401,
E/BooksSync( 6498):   "message": "Login Required"
E/BooksSync( 6498):  }
E/BooksSync( 6498): }
E/BooksSync( 6498): 
E/BooksSync( 6498): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 6498): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 6498): 	... 8 more
,E/BooksSync( 6498): Sync error
E/BooksSync( 6498): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 6498): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=6773339652298031869&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 6498): Headers:
E/BooksSync( 6498): accept-encoding: [gzip]
E/BooksSync( 6498): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 6498): gdata-version: 2
E/BooksSync( 6498): 
E/BooksSync( 6498): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 6498): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 6498): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 6498): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 6498): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 6498): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 6498): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 6498): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 6498): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 6498): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 6498): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 6498): {
E/BooksSync( 6498):  "error": {
E/BooksSync( 6498):   "errors": [
E/BooksSync( 6498):    {
E/BooksSync( 6498):     "domain": "global",
E/BooksSync( 6498):     "reason": "required",
E/BooksSync( 6498):     "message": "Login Required",
E/BooksSync( 6498):     "locationType": "header",
E/BooksSync( 6498):     "location": "Authorization"
E/BooksSync( 6498):    }
E/BooksSync( 6498):   ],
E/BooksSync( 6498):   "code": 401,
E/BooksSync( 6498):   "message": "Login Required"
E/BooksSync( 6498):  }
E/BooksSync( 6498): }
E/BooksSync( 6498): 
E/BooksSync( 6498): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 6498): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 6498): 	... 8 more
I/BooksSync( 6498): Finished books sync
,D/SyncManager( 1029): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 326919, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=4.0, 0.0, 0.0  rx=4.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-2027434841] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=4.0, 0.0, 0.0  rx=4.0 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-2027434831] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=2.0, 0.0, 0.0  rx=2.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-2027431804] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=2.0, 0.0, 0.0  rx=2.0 bcn=0 [on:0 tx:0 rx:0 period:12] from screen [on:0 period:-2027431792] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=1.0, 0.0, 0.0  rx=1.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-2027428772] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=1.0, 0.0, 0.0  rx=1.0 bcn=0 [on:0 tx:0 rx:0 period:9] from screen [on:0 period:-2027428763] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
I/[SystemUI]TimeTickManager( 1462): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1462): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1462): called onTimeUpdated()
I/[SystemUI]Clock( 1462): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1462): called onTimeUpdated()
I/[SystemUI]DateView( 1462): called onTimeUpdated()
I/[SystemUI]DateView( 1462): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1462): handleTimeUpdate
E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=1.5, 0.0, 0.0  rx=1.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-2027425746] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=1.5, 0.0, 0.0  rx=1.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-2027425743] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,D/sensors_hal_Time( 1029): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1029): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1029): tsOffsetIs: Apps: 366320848405; DSPS: 12144335; Offset : -4305892820
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.5 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-2027422705] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.5 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-2027422702] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.3 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-2027419677] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.3 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-2027419674] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.2, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-2027416648] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.2, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-2027416645] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-2027413619] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-2027413616] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,D/PowerManagerServiceEx( 1029): acquireWakeLockInternal: lock=518109269, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1029
,V/AlarmManager( 1029): ELAPSED_WAKEUP set : Alarm{3d2fcf5b type 2 when 380192 android} when 380192
V/AlarmManager( 1029): RTC_WAKEUP set : Alarm{1ccae0d1 type 0 when 1449671522859 com.android.vending} when 1449671522859
,D/[Concierge]Service( 2608): onStartCommand(). Type : 9
,D/PowerManagerServiceEx( 1029): releaseWakeLockInternal: lock=518109269 [*alarm*], flags=0x0
,V/SIM_STK ( 1029): Menu title from STK is T-Mobile
,V/GLSActivity( 2130): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2130): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 2130): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 2130): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2130): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2130): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/Finsky  ( 7082): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 7082): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 7082): [1] 5.onFinished: Scheduling replication attempt 3.
E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-2027410596] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-2027410593] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-2027407566] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-2027407563] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,D/sensors_hal_Time( 1029): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1029): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1029): tsOffsetIs: Apps: 386322722304; DSPS: 12799757; Offset : -4305911089
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-2027404536] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-2027404533] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3000] from screen [on:0 period:-2027401507] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-2027401506] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.5 bcn=0 [on:0 tx:0 rx:0 period:3005] from screen [on:0 period:-2027398487] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.5 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-2027398484] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.3 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-2027395466] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.3 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-2027395463] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.2, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-2027392441] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.2, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-2027392431] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-2027389411] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:11] from screen [on:0 period:-2027389400] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=3.0, 0.0, 0.0  rx=3.5 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-2027386386] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=3.0, 0.0, 0.0  rx=3.5 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-2027386383] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,D/sensors_hal_Time( 1029): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1029): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1029): tsOffsetIs: Apps: 406324637765; DSPS: 13455180; Offset : -4305918183
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=2.5, 0.0, 0.0  rx=2.8 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-2027383359] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=2.5, 0.0, 0.0  rx=2.8 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-2027383356] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=1.8, 0.0, 0.0  rx=1.9 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-2027380331] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=1.8, 0.0, 0.0  rx=1.9 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-2027380321] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
V/AlarmManager( 1029): RTC_WAKEUP set : Alarm{3e8f8b28 type 0 when 1449671555148 com.android.vending} when 1449671555148
,V/SIM_STK ( 1029): Menu title from STK is T-Mobile
,V/GLSActivity( 2130): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2130): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure,
I/GLSUser ( 2130): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2130): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 2130): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2130): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 7082): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 7082): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 7082): [1] 5.onFinished: Scheduling replication attempt 4.
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.9, 0.0, 0.0  rx=0.9 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-2027377299] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.9, 0.0, 0.0  rx=0.9 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-2027377296] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.9, 0.0, 0.0  rx=1.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-2027374271] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.9, 0.0, 0.0  rx=1.0 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-2027374261] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
V/AlarmManager( 1029): ELAPSED_WAKEUP set : Alarm{1786f9ca type 2 when 418586 android} when 418586
,I/BooksSync( 6498): Starting books sync
,D/BooksSync( 6498): started syncMyEbooks
,V/GLSActivity( 2130): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2130): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 2130): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2130): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2130): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2130): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1029): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1029): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1029): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1029): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1029): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1414): onNotificationPosted
D/SmartCoverUpdateMonitor( 1414): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1414): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1414): handleNotificationPosted(true)
D/QuickCircle( 1414): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1414): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1414): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1414): post do just update job
D/LgeQuickCoverNotificationData( 1414): showAll3
D/LgeQuickCoverNotificationData( 1414): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1414): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1414): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1414): showNotificationWithSetupData: display=false
,D/LgeQuickCoverOverlayWindow( 1414): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1414): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1414): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1414): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1414): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1414): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1414): updateNotificationData: count=3
W/GLSActivity( 2130): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2130): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2130): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2130): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2130): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2130): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2130): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 6498): Authentication error
E/BooksAccountManager( 6498): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6498): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6498): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6498): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6498): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6498): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6498): null auth token
,D/QuickStatusbarLayout( 1414): Notification difference=198
D/QuickStatusbarLayout( 1414): child = android.widget.LinearLayout{1813a4 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,W/ApiaryClient( 6498): Error response from books API: {
W/ApiaryClient( 6498):  "error": {
,W/ApiaryClient( 6498):   "errors": [
W/ApiaryClient( 6498):    {
W/ApiaryClient( 6498):     "domain": "global",
W/ApiaryClient( 6498):     "reason": "required",
W/ApiaryClient( 6498):     "message": "Login Required",
W/ApiaryClient( 6498):     "locationType": "header",
W/ApiaryClient( 6498):     "location": "Authorization"
W/ApiaryClient( 6498):    }
W/ApiaryClient( 6498):   ],
W/ApiaryClient( 6498):   "code": 401,
W/ApiaryClient( 6498):   "message": "Login Required"
W/ApiaryClient( 6498):  }
W/ApiaryClient( 6498): }
,W/ApiaryClient( 6498): errCount = 1: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6498): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-7623702319001126060&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6498): Headers:
W/ApiaryClient( 6498): accept-encoding: [gzip]
W/ApiaryClient( 6498): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6498): gdata-version: 2
V/GLSActivity( 2130): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2130): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2130): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2130): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 2130): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2130): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1029): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1029): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1029): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1029): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1029): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1414): onNotificationPosted
,D/SmartCoverUpdateMonitor( 1414): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1414): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1414): handleNotificationPosted(true)
D/QuickCircle( 1414): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1414): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1414): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1414): post do just update job
D/LgeQuickCoverNotificationData( 1414): showAll3
D/LgeQuickCoverNotificationData( 1414): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1414): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1414): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1414): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1414): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1414): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1414): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1414): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1414): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1414): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1414): updateNotificationData: count=3
W/GLSActivity( 2130): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2130): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2130): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2130): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2130): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2130): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2130): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 6498): Authentication error
E/BooksAccountManager( 6498): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6498): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6498): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6498): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6498): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6498): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6498): null auth token
D/QuickStatusbarLayout( 1414): Notification difference=198
D/QuickStatusbarLayout( 1414): child = android.widget.LinearLayout{1813a4 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
W/ApiaryClient( 6498): Error response from books API: {
W/ApiaryClient( 6498):  "error": {
W/ApiaryClient( 6498):   "errors": [
W/ApiaryClient( 6498):    {
W/ApiaryClient( 6498):     "domain": "global",
W/ApiaryClient( 6498):     "reason": "required",
W/ApiaryClient( 6498):     "message": "Login Required",
W/ApiaryClient( 6498):     "locationType": "header",
W/ApiaryClient( 6498):     "location": "Authorization"
W/ApiaryClient( 6498):    }
W/ApiaryClient( 6498):   ],
W/ApiaryClient( 6498):   "code": 401,
W/ApiaryClient( 6498):   "message": "Login Required"
W/ApiaryClient( 6498):  }
W/ApiaryClient( 6498): }
,W/ApiaryClient( 6498): errCount = 2: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6498): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-7623702319001126060&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6498): Headers:
W/ApiaryClient( 6498): accept-encoding: [gzip]
W/ApiaryClient( 6498): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6498): gdata-version: 2
E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=1.0, 0.0, 0.0  rx=1.0 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:-2027371238] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=1.0, 0.0, 0.0  rx=1.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-2027371235] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,V/GLSActivity( 2130): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2130): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2130): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2130): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2130): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2130): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1029): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1029): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1029): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1029): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1029): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1414): onNotificationPosted
,D/SmartCoverUpdateMonitor( 1414): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1414): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1414): handleNotificationPosted(true)
D/QuickCircle( 1414): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1414): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1414): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1414): post do just update job
D/LgeQuickCoverNotificationData( 1414): showAll3
D/LgeQuickCoverNotificationData( 1414): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1414): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1414): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1414): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1414): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1414): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1414): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1414): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1414): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1414): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1414): updateNotificationData: count=3
W/GLSActivity( 2130): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2130): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2130): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2130): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2130): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2130): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2130): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 6498): Authentication error
E/BooksAccountManager( 6498): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6498): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6498): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6498): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6498): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6498): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6498): null auth token
D/QuickStatusbarLayout( 1414): Notification difference=198
D/QuickStatusbarLayout( 1414): child = android.widget.LinearLayout{1813a4 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,W/ApiaryClient( 6498): Error response from books API: {
W/ApiaryClient( 6498):  "error": {
W/ApiaryClient( 6498):   "errors": [
W/ApiaryClient( 6498):    {
W/ApiaryClient( 6498):     "domain": "global",
W/ApiaryClient( 6498):     "reason": "required",
W/ApiaryClient( 6498):     "message": "Login Required",
W/ApiaryClient( 6498):     "locationType": "header",
W/ApiaryClient( 6498):     "location": "Authorization"
W/ApiaryClient( 6498):    }
W/ApiaryClient( 6498):   ],
W/ApiaryClient( 6498):   "code": 401,
W/ApiaryClient( 6498):   "message": "Login Required"
W/ApiaryClient( 6498):  }
W/ApiaryClient( 6498): }
,W/ApiaryClient( 6498): errCount = 3: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6498): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-7623702319001126060&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6498): Headers:
W/ApiaryClient( 6498): accept-encoding: [gzip]
W/ApiaryClient( 6498): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6498): gdata-version: 2
,E/BooksSync( 6498): Soft error: 
E/BooksSync( 6498): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 6498): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-7623702319001126060&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 6498): Headers:
E/BooksSync( 6498): accept-encoding: [gzip]
E/BooksSync( 6498): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 6498): gdata-version: 2
E/BooksSync( 6498): 
E/BooksSync( 6498): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 6498): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 6498): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 6498): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 6498): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 6498): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 6498): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 6498): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 6498): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 6498): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 6498): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 6498): {
E/BooksSync( 6498):  "error": {
E/BooksSync( 6498):   "errors": [
E/BooksSync( 6498):    {
E/BooksSync( 6498):     "domain": "global",
E/BooksSync( 6498):     "reason": "required",
E/BooksSync( 6498):     "message": "Login Required",
E/BooksSync( 6498):     "locationType": "header",
E/BooksSync( 6498):     "location": "Authorization"
E/BooksSync( 6498):    }
E/BooksSync( 6498):   ],
E/BooksSync( 6498):   "code": 401,
E/BooksSync( 6498):   "message": "Login Required"
E/BooksSync( 6498):  }
E/BooksSync( 6498): }
E/BooksSync( 6498): 
E/BooksSync( 6498): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 6498): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 6498): 	... 8 more
,E/BooksSync( 6498): Sync error
E/BooksSync( 6498): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 6498): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-7623702319001126060&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 6498): Headers:
E/BooksSync( 6498): accept-encoding: [gzip]
E/BooksSync( 6498): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 6498): gdata-version: 2
E/BooksSync( 6498): 
E/BooksSync( 6498): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 6498): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 6498): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 6498): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 6498): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 6498): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 6498): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 6498): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 6498): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 6498): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 6498): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 6498): {
E/BooksSync( 6498):  "error": {
E/BooksSync( 6498):   "errors": [
E/BooksSync( 6498):    {
E/BooksSync( 6498):     "domain": "global",
E/BooksSync( 6498):     "reason": "required",
E/BooksSync( 6498):     "message": "Login Required",
E/BooksSync( 6498):     "locationType": "header",
E/BooksSync( 6498):     "location": "Authorization"
E/BooksSync( 6498):    }
E/BooksSync( 6498):   ],
E/BooksSync( 6498):   "code": 401,
E/BooksSync( 6498):   "message": "Login Required"
E/BooksSync( 6498):  }
E/BooksSync( 6498): }
E/BooksSync( 6498): 
E/BooksSync( 6498): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 6498): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 6498): 	... 8 more
I/BooksSync( 6498): Finished books sync
D/SyncManager( 1029): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 418586, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=3.5, 0.0, 0.0  rx=2.5 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-2027368208] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=3.5, 0.0, 0.0  rx=2.5 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-2027368205] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,I/[SystemUI]TimeTickManager( 1462): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1462): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1462): called onTimeUpdated()
I/[SystemUI]Clock( 1462): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1462): called onTimeUpdated()
I/[SystemUI]DateView( 1462): called onTimeUpdated()
I/[SystemUI]DateView( 1462): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1462): handleTimeUpdate
,D/sensors_hal_Time( 1029): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1029): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1029): tsOffsetIs: Apps: 426326507653; DSPS: 14110601; Offset : -4305909763
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=3.7, 0.0, 0.0  rx=2.7 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-2027365181] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=3.7, 0.0, 0.0  rx=2.7 bcn=0 [on:0 tx:0 rx:0 period:9] from screen [on:0 period:-2027365172] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=1.9, 0.0, 0.0  rx=1.4 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-2027362150] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=1.9, 0.0, 0.0  rx=1.4 bcn=0 [on:0 tx:0 rx:0 period:11] from screen [on:0 period:-2027362139] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=1.4, 0.0, 0.0  rx=1.2 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-2027359117] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=1.4, 0.0, 0.0  rx=1.2 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-2027359114] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=1.2, 0.0, 0.0  rx=1.1 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-2027356086] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=1.2, 0.0, 0.0  rx=1.1 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-2027356083] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,D/PowerManagerServiceEx( 1029): acquireWakeLockInternal: lock=518109269, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1029
,V/AlarmManager( 1029): RTC_WAKEUP set : Alarm{1fc269f6 type 0 when 1449671587721 com.android.vending} when 1449671587721
,D/[Concierge]Service( 2608): onStartCommand(). Type : 9
,D/PowerManagerServiceEx( 1029): releaseWakeLockInternal: lock=518109269 [*alarm*], flags=0x0
,V/SIM_STK ( 1029): Menu title from STK is T-Mobile
,I/art     ( 1029): Explicit concurrent mark sweep GC freed 59285(2MB) AllocSpace objects, 10(1056KB) LOS objects, 33% free, 44MB/66MB, paused 1.879ms total 107.227ms
,V/GLSActivity( 2130): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/GLSUser ( 2130): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 2130): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2130): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2130): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2130): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/Finsky  ( 7082): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 7082): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 7082): [1] 5.onFinished: Scheduling replication attempt 5.
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.6, 0.0, 0.0  rx=0.5 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:-2027353055] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.6, 0.0, 0.0  rx=0.5 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-2027353052] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3009] from screen [on:0 period:-2027350021] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:12] from screen [on:0 period:-2027350009] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:-2027346992] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-2027346982] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
D/sensors_hal_Time( 1029): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1029): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1029): tsOffsetIs: Apps: 446328693374; DSPS: 14766032; Offset : -4305890921
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-2027343961] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:11] from screen [on:0 period:-2027343950] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
V/AlarmManager( 1029): ELAPSED_WAKEUP set : Alarm{27d89fe8 type 2 when 448634 android} when 448634
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.9, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-2027340928] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.9, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-2027340925] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-2027337899] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-2027337896] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-2027334871] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-2027334861] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3000] from screen [on:0 period:-2027331841] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:12] from screen [on:0 period:-2027331829] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-2027328808] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-2027328805] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,V/AlarmManager( 1029): RTC_WAKEUP set : Alarm{3cb73ca6 type 0 when 1449671611137 com.android.vending} when 1449671611137
,V/SIM_STK ( 1029): Menu title from STK is T-Mobile
,V/GLSActivity( 2130): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,I/GLSUser ( 2130): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 2130): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2130): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2130): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2130): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 7082): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 7082): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 7082): [1] 5.onFinished: Giving up after 6 failures.
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3000] from screen [on:0 period:-2027325777] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-2027325774] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,D/sensors_hal_Time( 1029): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1029): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1029): tsOffsetIs: Apps: 466331634721; DSPS: 15421489; Offset : -4305909884
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-2027322747] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-2027322744] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-2027319722] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:11] from screen [on:0 period:-2027319711] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-2027316690] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:15] from screen [on:0 period:-2027316675] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-2027313657] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-2027313654] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-2027310627] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-2027310624] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-2027307598] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-2027307595] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,I/[SystemUI]TimeTickManager( 1462): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1462): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1462): called onTimeUpdated()
I/[SystemUI]Clock( 1462): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1462): called onTimeUpdated()
I/[SystemUI]DateView( 1462): called onTimeUpdated()
I/[SystemUI]DateView( 1462): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1462): handleTimeUpdate
D/sensors_hal_Time( 1029): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1029): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1029): tsOffsetIs: Apps: 486333699193; DSPS: 16076917; Offset : -4305920581
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-2027304567] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-2027304564] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-2027301538] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-2027301535] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-2027298509] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-2027298506] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-43 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-2027295480] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-43 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:9] from screen [on:0 period:-2027295471] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-43 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-2027292450] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-43 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-2027292447] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-43 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3000] from screen [on:0 period:-2027289421] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-43 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:11] from screen [on:0 period:-2027289410] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-2027286388] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-2027286385] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,D/sensors_hal_Time( 1029): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1029): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1029): tsOffsetIs: Apps: 506335839602; DSPS: 16732347; Offset : -4305916272
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-2027283358] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-2027283355] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-2027280328] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-2027280325] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-2027277299] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-2027277296] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-2027274275] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-2027274272] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-2027271244] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-2027271241] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-2027268214] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0,
,E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:4] from screen [on:0 period:-2027268210] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
D/sensors_hal_Time( 1029): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1029): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1029): tsOffsetIs: Apps: 526337593604; DSPS: 17387764; Offset : -4305901746
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-2027265181] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:9] from screen [on:0 period:-2027265172] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-2027262152] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:11] from screen [on:0 period:-2027262141] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=2.2, 0.0, 0.0  rx=2.7 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:-2027259119] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=2.2, 0.0, 0.0  rx=2.7 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-2027259116] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=1.1, 0.0, 0.0  rx=1.4 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-2027256089] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=1.1, 0.0, 0.0  rx=1.4 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-2027256086] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=4.6, 0.0, 0.0  rx=5.7 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-2027253061] gl rssi=-44 ag=0 hr ticks 0,0,0 ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=4.6, 0.0, 0.0  rx=5.7 bcn=0 [on:0 tx:0 rx:0 period:12] from screen [on:0 period:-2027253049] gl rssi=-44 ag=0 hr ticks 0,0,0 ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-43 f=2412 sc=60 link=72 tx=2.8, 0.0, 0.0  rx=3.3 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-2027250030] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-43 f=2412 sc=60 link=72 tx=2.8, 0.0, 0.0  rx=3.3 bcn=0 [on:0 tx:0 rx:0 period:14] from screen [on:0 period:-2027250016] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-43 f=2412 sc=60 link=72 tx=1.4, 0.0, 0.0  rx=1.7 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:-2027246997] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-43 f=2412 sc=60 link=72 tx=1.4, 0.0, 0.0  rx=1.7 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-2027246994] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,I/[SystemUI]TimeTickManager( 1462): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1462): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1462): called onTimeUpdated()
I/[SystemUI]Clock( 1462): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1462): called onTimeUpdated()
I/[SystemUI]DateView( 1462): called onTimeUpdated()
I/[SystemUI]DateView( 1462): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1462): handleTimeUpdate
,D/sensors_hal_Time( 1029): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1029): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1029): tsOffsetIs: Apps: 546339741045; DSPS: 18043195; Offset : -4305921235
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-43 f=2412 sc=60 link=72 tx=1.2, 0.0, 0.0  rx=1.3 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-2027243967] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-43 f=2412 sc=60 link=72 tx=1.2, 0.0, 0.0  rx=1.3 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-2027243964] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,I/[SystemUI]LGPowerUI( 1462): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1462): On Skip Timer : true
,D/KeyguardUpdateMonitor( 1462): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 285
I/[SystemUI]LGPowerUI( 1462): onReceive = android.intent.action.BATTERY_CHANGED
D/WifiController( 1029): battery changed pluggedType: 2
D/LEDHandler( 1964): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1964): Battery Level Remaining: 100%
D/LEDHandler( 1964): Battery Temp: 285, mChargingStatus=5, mChargingStop=false
,I/[SystemUI]BatterySaverHandler( 1462): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings( 1029): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1029): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/HeadsetStateMachine( 6103): Disconnected process message: 10, size: 0
D/LGDMClient( 2966): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.intent.action.BATTERY_CHANGED
D/LGDMClient( 2966): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
D/PowerManagerServiceEx( 1029): acquireWakeLockInternal: lock=518109269, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1029
,V/AlarmManager( 1029): ELAPSED_WAKEUP set : Alarm{1167d318 type 2 when 550894 android} when 550894
D/[Concierge]Service( 2608): onStartCommand(). Type : 9
,D/PowerManagerServiceEx( 1029): releaseWakeLockInternal: lock=518109269 [*alarm*], flags=0x0
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-43 f=2412 sc=60 link=72 tx=1.1, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-2027240935] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-43 f=2412 sc=60 link=72 tx=1.1, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-2027240932] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,I/BooksSync( 6498): Starting books sync
,D/BooksSync( 6498): started syncMyEbooks
,V/GLSActivity( 2130): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2130): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2130): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2130): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2130): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2130): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1029): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1029): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1029): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1029): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1029): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
W/GLSActivity( 2130): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2130): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2130): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2130): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2130): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2130): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2130): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 6498): Authentication error
E/BooksAccountManager( 6498): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6498): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6498): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6498): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6498): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6498): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6498): null auth token
D/LgeQuickCoverNLService( 1414): onNotificationPosted
D/SmartCoverUpdateMonitor( 1414): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1414): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1414): handleNotificationPosted(true)
D/QuickCircle( 1414): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1414): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1414): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
,D/LgeQuickCoverNotificationData( 1414): post do just update job
D/LgeQuickCoverNotificationData( 1414): showAll3
D/LgeQuickCoverNotificationData( 1414): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1414): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1414): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1414): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1414): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1414): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1414): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1414): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1414): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1414): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1414): updateNotificationData: count=3
D/QuickStatusbarLayout( 1414): Notification difference=198
D/QuickStatusbarLayout( 1414): child = android.widget.LinearLayout{1813a4 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,W/ApiaryClient( 6498): Error response from books API: {
W/ApiaryClient( 6498):  "error": {
W/ApiaryClient( 6498):   "errors": [
W/ApiaryClient( 6498):    {
W/ApiaryClient( 6498):     "domain": "global",
W/ApiaryClient( 6498):     "reason": "required",
W/ApiaryClient( 6498):     "message": "Login Required",
W/ApiaryClient( 6498):     "locationType": "header",
W/ApiaryClient( 6498):     "location": "Authorization"
W/ApiaryClient( 6498):    }
W/ApiaryClient( 6498):   ],
W/ApiaryClient( 6498):   "code": 401,
W/ApiaryClient( 6498):   "message": "Login Required"
W/ApiaryClient( 6498):  }
W/ApiaryClient( 6498): }
W/ApiaryClient( 6498): errCount = 1: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6498): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=2117672473940203309&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6498): Headers:
W/ApiaryClient( 6498): accept-encoding: [gzip]
W/ApiaryClient( 6498): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6498): gdata-version: 2
,V/GLSActivity( 2130): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2130): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2130): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 2130): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2130): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2130): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1029): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1029): pkg=com.google.android.gms canInterrupt=false intercept=true
,I/NotificationServiceEx( 1029): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1029): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1029): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1414): onNotificationPosted
,D/SmartCoverUpdateMonitor( 1414): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1414): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1414): handleNotificationPosted(true)
D/QuickCircle( 1414): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1414): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1414): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1414): post do just update job
D/LgeQuickCoverNotificationData( 1414): showAll3
D/LgeQuickCoverNotificationData( 1414): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1414): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1414): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1414): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1414): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1414): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1414): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1414): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1414): [native noti] inex =  2
,D/LgeQuickCoverNotificationData( 1414): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1414): updateNotificationData: count=3
D/QuickStatusbarLayout( 1414): Notification difference=198
D/QuickStatusbarLayout( 1414): child = android.widget.LinearLayout{1813a4 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,W/GLSActivity( 2130): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2130): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2130): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2130): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2130): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2130): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2130): 	at android.os.Binder.execTransact(Binder.java:446)
E/BooksAccountManager( 6498): Authentication error
E/BooksAccountManager( 6498): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6498): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6498): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6498): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6498): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6498): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6498): null auth token
W/ApiaryClient( 6498): Error response from books API: {
W/ApiaryClient( 6498):  "error": {
W/ApiaryClient( 6498):   "errors": [
W/ApiaryClient( 6498):    {
W/ApiaryClient( 6498):     "domain": "global",
W/ApiaryClient( 6498):     "reason": "required",
W/ApiaryClient( 6498):     "message": "Login Required",
W/ApiaryClient( 6498):     "locationType": "header",
W/ApiaryClient( 6498):     "location": "Authorization"
W/ApiaryClient( 6498):    }
W/ApiaryClient( 6498):   ],
W/ApiaryClient( 6498):   "code": 401,
W/ApiaryClient( 6498):   "message": "Login Required"
W/ApiaryClient( 6498):  }
W/ApiaryClient( 6498): }
,W/ApiaryClient( 6498): errCount = 2: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6498): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=2117672473940203309&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6498): Headers:
W/ApiaryClient( 6498): accept-encoding: [gzip]
W/ApiaryClient( 6498): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6498): gdata-version: 2
V/GLSActivity( 2130): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2130): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2130): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2130): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2130): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2130): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1029): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1029): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1029): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1029): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1029): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
W/GLSActivity( 2130): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2130): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2130): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2130): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2130): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2130): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2130): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 6498): Authentication error
E/BooksAccountManager( 6498): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6498): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6498): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6498): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6498): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6498): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6498): null auth token
W/ResourcesManager( 1414): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 1414): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
D/LgeQuickCoverNLService( 1414): onNotificationPosted
D/SmartCoverUpdateMonitor( 1414): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1414): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1414): handleNotificationPosted(true)
D/QuickCircle( 1414): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1414): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1414): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1414): post do just update job
D/LgeQuickCoverNotificationData( 1414): showAll3
D/LgeQuickCoverNotificationData( 1414): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1414): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1414): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1414): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1414): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1414): isNotificationForCurrentUser : true
W/ResourcesManager( 1414): Asset path '/system/framework/com.lge.systemui.jar' does not exist or contains no resources.
W/ResourcesManager( 1414): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,D/LgeQuickCoverOverlayWindow( 1414): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1414): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1414): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1414): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1414): updateNotificationData: count=3
,D/QuickStatusbarLayout( 1414): Notification difference=198
D/QuickStatusbarLayout( 1414): child = android.widget.LinearLayout{1813a4 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
W/ApiaryClient( 6498): Error response from books API: {
W/ApiaryClient( 6498):  "error": {
W/ApiaryClient( 6498):   "errors": [
W/ApiaryClient( 6498):    {
W/ApiaryClient( 6498):     "domain": "global",
W/ApiaryClient( 6498):     "reason": "required",
W/ApiaryClient( 6498):     "message": "Login Required",
W/ApiaryClient( 6498):     "locationType": "header",
W/ApiaryClient( 6498):     "location": "Authorization"
W/ApiaryClient( 6498):    }
W/ApiaryClient( 6498):   ],
W/ApiaryClient( 6498):   "code": 401,
W/ApiaryClient( 6498):   "message": "Login Required"
W/ApiaryClient( 6498):  }
W/ApiaryClient( 6498): }
W/ApiaryClient( 6498): errCount = 3: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6498): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=2117672473940203309&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6498): Headers:
W/ApiaryClient( 6498): accept-encoding: [gzip]
W/ApiaryClient( 6498): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6498): gdata-version: 2
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-43 f=2412 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:-2027237916] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-43 f=2412 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-2027237913] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
E/BooksSync( 6498): Soft error: 
E/BooksSync( 6498): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 6498): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=2117672473940203309&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 6498): Headers:
E/BooksSync( 6498): accept-encoding: [gzip]
E/BooksSync( 6498): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 6498): gdata-version: 2
E/BooksSync( 6498): 
E/BooksSync( 6498): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 6498): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 6498): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 6498): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 6498): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 6498): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 6498): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 6498): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 6498): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 6498): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 6498): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 6498): {
E/BooksSync( 6498):  "error": {
E/BooksSync( 6498):   "errors": [
E/BooksSync( 6498):    {
E/BooksSync( 6498):     "domain": "global",
E/BooksSync( 6498):     "reason": "required",
E/BooksSync( 6498):     "message": "Login Required",
E/BooksSync( 6498):     "locationType": "header",
E/BooksSync( 6498):     "location": "Authorization"
E/BooksSync( 6498):    }
E/BooksSync( 6498):   ],
E/BooksSync( 6498):   "code": 401,
E/BooksSync( 6498):   "message": "Login Required"
E/BooksSync( 6498):  }
E/BooksSync( 6498): }
E/BooksSync( 6498): 
E/BooksSync( 6498): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 6498): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 6498): 	... 8 more
,E/BooksSync( 6498): Sync error
E/BooksSync( 6498): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 6498): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=2117672473940203309&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 6498): Headers:
E/BooksSync( 6498): accept-encoding: [gzip]
E/BooksSync( 6498): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 6498): gdata-version: 2
E/BooksSync( 6498): 
E/BooksSync( 6498): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 6498): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 6498): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 6498): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 6498): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 6498): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 6498): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 6498): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 6498): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 6498): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 6498): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 6498): {
E/BooksSync( 6498):  "error": {
E/BooksSync( 6498):   "errors": [
E/BooksSync( 6498):    {
E/BooksSync( 6498):     "domain": "global",
E/BooksSync( 6498):     "reason": "required",
E/BooksSync( 6498):     "message": "Login Required",
E/BooksSync( 6498):     "locationType": "header",
E/BooksSync( 6498):     "location": "Authorization"
E/BooksSync( 6498):    }
E/BooksSync( 6498):   ],
E/BooksSync( 6498):   "code": 401,
E/BooksSync( 6498):   "message": "Login Required"
E/BooksSync( 6498):  }
E/BooksSync( 6498): }
E/BooksSync( 6498): 
E/BooksSync( 6498): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 6498): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 6498): 	... 8 more
I/BooksSync( 6498): Finished books sync
D/SyncManager( 1029): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 550894, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-43 f=2412 sc=60 link=72 tx=5.3, 0.0, 0.0  rx=3.9 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-2027234901] gl rssi=-43 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-43 f=2412 sc=60 link=72 tx=5.3, 0.0, 0.0  rx=3.9 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-2027234891] gl rssi=-43 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-43 f=2412 sc=60 link=72 tx=2.6, 0.0, 0.0  rx=2.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-2027231870] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-43 f=2412 sc=60 link=72 tx=2.6, 0.0, 0.0  rx=2.0 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-2027231860] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-43 f=2412 sc=60 link=72 tx=1.8, 0.0, 0.0  rx=1.5 bcn=0 [on:0 tx:0 rx:0 period:3006] from screen [on:0 period:-2027228838] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-43 f=2412 sc=60 link=72 tx=1.8, 0.0, 0.0  rx=1.5 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-2027228835] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-43 f=2412 sc=60 link=72 tx=1.4, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-2027225811] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-43 f=2412 sc=60 link=72 tx=1.4, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:8] from screen [on:0 period:-2027225803] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
D/sensors_hal_Time( 1029): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1029): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1029): tsOffsetIs: Apps: 566341993798; DSPS: 18698628; Offset : -4305896187
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-43 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.9 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-2027222784] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-43 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.9 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-2027222781] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-43 f=2412 sc=60 link=72 tx=0.9, 0.0, 0.0  rx=0.9 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-2027219752] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-43 f=2412 sc=60 link=72 tx=0.9, 0.0, 0.0  rx=0.9 bcn=0 [on:0 tx:0 rx:0 period:13] from screen [on:0 period:-2027219739] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-43 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.5 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-2027216719] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-43 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.5 bcn=0 [on:0 tx:0 rx:0 period:4] from screen [on:0 period:-2027216715] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-43 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-2027213691] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-43 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:7] from screen [on:0 period:-2027213684] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
V/AlarmManager( 1029): ELAPSED_WAKEUP set : Alarm{8552e42 type 2 when 581121 android} when 581121
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-43 f=2412 sc=60 link=72 tx=0.9, 0.0, 0.0  rx=0.9 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-2027210673] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-43 f=2412 sc=60 link=72 tx=0.9, 0.0, 0.0  rx=0.9 bcn=0 [on:0 tx:0 rx:0 period:8] from screen [on:0 period:-2027210665] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-43 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-2027207644] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-43 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-2027207641] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,D/sensors_hal_Time( 1029): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1029): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1029): tsOffsetIs: Apps: 586344091446; DSPS: 19354057; Offset : -4305904356
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-43 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-2027204615] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-43 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-2027204612] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-43 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-2027201586] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-43 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-2027201583] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-43 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:2998] from screen [on:0 period:-2027198559] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-43 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-2027198558] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-43 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-2027195547] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-43 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-2027195544] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-43 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-2027192518] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-43 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-2027192515] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-43 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-2027189492] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-43 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:8] from screen [on:0 period:-2027189484] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-43 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-2027186463] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-43 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-2027186460] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
I/[SystemUI]TimeTickManager( 1462): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1462): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1462): called onTimeUpdated()
I/[SystemUI]Clock( 1462): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1462): called onTimeUpdated()
I/[SystemUI]DateView( 1462): called onTimeUpdated()
I/[SystemUI]DateView( 1462): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1462): handleTimeUpdate
D/sensors_hal_Time( 1029): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1029): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1029): tsOffsetIs: Apps: 606345692324; DSPS: 20009469; Offset : -4305890393
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-43 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-2027183433] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-43 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:9] from screen [on:0 period:-2027183424] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
V/GLSActivity( 2130): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2130): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 2130): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2130): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2130): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2130): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1029): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1029): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1029): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1029): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1029): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1414): onNotificationPosted
,D/SmartCoverUpdateMonitor( 1414): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1414): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1414): handleNotificationPosted(true)
D/QuickCircle( 1414): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1414): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1414): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1414): post do just update job
D/LgeQuickCoverNotificationData( 1414): showAll3
D/LgeQuickCoverNotificationData( 1414): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1414): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1414): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1414): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1414): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1414): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1414): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1414): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1414): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1414): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1414): updateNotificationData: count=3
,W/GLSActivity( 2130): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2130): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2130): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2130): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2130): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2130): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2130): 	at android.os.Binder.execTransact(Binder.java:446)
E/PlayEventLogger( 7082): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 7082): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 7082): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/PlayEventLogger( 7082): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 7082): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/PlayEventLogger( 7082): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 7082): 	at android.os.Binder.execTransact(Binder.java:446)
D/QuickStatusbarLayout( 1414): Notification difference=198
,D/QuickStatusbarLayout( 1414): child = android.widget.LinearLayout{1813a4 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
W/System  ( 7082): Ignoring header User-Agent because its value was null.
,D/libc-netbsd(  323): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  323): res_queryN name = play.googleapis.com, class = 1, type = 1
D/libc-netbsd(  323): res_queryN name = play.googleapis.com succeed
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-43 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-2027180409] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-43 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-2027180399] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-43 f=2412 sc=60 link=72 tx=5.9, 0.0, 0.0  rx=5.4 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-2027177378] gl rssi=-43 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-43 f=2412 sc=60 link=72 tx=5.9, 0.0, 0.0  rx=5.4 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-2027177375] gl rssi=-43 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-43 f=2412 sc=60 link=72 tx=3.5, 0.0, 0.0  rx=3.2 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-2027174348] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-43 f=2412 sc=60 link=72 tx=3.5, 0.0, 0.0  rx=3.2 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-2027174345] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-43 f=2412 sc=60 link=72 tx=1.7, 0.0, 0.0  rx=1.6 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-2027171322] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-43 f=2412 sc=60 link=72 tx=1.7, 0.0, 0.0  rx=1.6 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-2027171312] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-43 f=2412 sc=60 link=72 tx=1.4, 0.0, 0.0  rx=1.3 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-2027168291] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-43 f=2412 sc=60 link=72 tx=1.4, 0.0, 0.0  rx=1.3 bcn=0 [on:0 tx:0 rx:0 period:12] from screen [on:0 period:-2027168279] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
D/sensors_hal_Time( 1029): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1029): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1029): tsOffsetIs: Apps: 626347886378; DSPS: 20664901; Offset : -4305893577
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-43 f=2412 sc=60 link=72 tx=1.2, 0.0, 0.0  rx=1.2 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-2027165266] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-43 f=2412 sc=60 link=72 tx=1.2, 0.0, 0.0  rx=1.2 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-2027165263] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-43 f=2412 sc=60 link=72 tx=0.6, 0.0, 0.0  rx=0.6 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-2027162237] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-43 f=2412 sc=60 link=72 tx=0.6, 0.0, 0.0  rx=0.6 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-2027162234] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-43 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-2027159206] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-43 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:9] from screen [on:0 period:-2027159197] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-43 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-2027156175] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-43 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-2027156172] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-43 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-2027153145] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-43 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-2027153142] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-43 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:-2027150124] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-43 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-2027150121] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,D/PowerManagerServiceEx( 1029): acquireWakeLockInternal: lock=518109269, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1029
,D/[Concierge]Service( 2608): onStartCommand(). Type : 9
,D/PowerManagerServiceEx( 1029): releaseWakeLockInternal: lock=518109269 [*alarm*], flags=0x0
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-43 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-2027147095] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-43 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-2027147092] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,D/sensors_hal_Time( 1029): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1029): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1029): tsOffsetIs: Apps: 646349942777; DSPS: 21320329; Offset : -4305912296
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-43 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-2027144064] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-43 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-2027144061] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-43 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-2027141034] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-43 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-2027141031] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-43 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-2027138004] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-43 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-2027138001] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-43 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-2027134982] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-43 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-2027134972] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-2027131950] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:4] from screen [on:0 period:-2027131946] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-2027128924] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-2027128921] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,I/[SystemUI]TimeTickManager( 1462): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1462): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1462): called onTimeUpdated()
I/[SystemUI]Clock( 1462): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1462): called onTimeUpdated()
I/[SystemUI]DateView( 1462): called onTimeUpdated()
I/[SystemUI]DateView( 1462): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1462): handleTimeUpdate
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-2027125894] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-2027125891] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,D/sensors_hal_Time( 1029): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1029): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1029): tsOffsetIs: Apps: 666352801937; DSPS: 21975783; Offset : -4305921893
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-2027122864] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-2027122861] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-2027119844] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-2027119841] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-2027116816] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-2027116813] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-2027113787] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:4] from screen [on:0 period:-2027113783] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-2027110756] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-2027110753] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-2027107727] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:4] from screen [on:0 period:-2027107723] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,D/sensors_hal_Time( 1029): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1029): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1029): tsOffsetIs: Apps: 686354967762; DSPS: 22631213; Offset : -4305892221
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-2027104706] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-2027104703] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:-2027101677] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-2027101674] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-2027098647] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-2027098644] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-2027095618] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-2027095615] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-2027092591] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:12] from screen [on:0 period:-2027092579] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-2027089566] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-2027089563] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-2027086536] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-2027086533] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,D/sensors_hal_Time( 1029): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1029): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1029): tsOffsetIs: Apps: 706356969682; DSPS: 23286639; Offset : -4305904565
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-2027083506] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-2027083503] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-43 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:2999] from screen [on:0 period:-2027080478] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-43 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-2027080475] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-43 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-2027077447] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-43 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-2027077444] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-43 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-2027074425] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-43 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-2027074422] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-43 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-2027071396] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-43 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-2027071393] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-43 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-2027068366] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-43 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-2027068363] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,I/[SystemUI]TimeTickManager( 1462): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1462): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1462): called onTimeUpdated()
I/[SystemUI]Clock( 1462): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1462): called onTimeUpdated()
I/[SystemUI]DateView( 1462): called onTimeUpdated()
I/[SystemUI]DateView( 1462): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1462): handleTimeUpdate
,D/sensors_hal_Time( 1029): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1029): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1029): tsOffsetIs: Apps: 726359117069; DSPS: 23942069; Offset : -4305893304
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-43 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-2027065338] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-43 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-2027065335] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-43 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-2027062309] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-43 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-2027062299] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-43 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:-2027059284] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-43 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-2027059281] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-43 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-2027056254] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-43 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-2027056251] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-43 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-2027053234] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-43 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-2027053231] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-43 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-2027050204] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-43 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-2027050201] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-43 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-2027047174] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-43 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-2027047171] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,D/sensors_hal_Time( 1029): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1029): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1029): tsOffsetIs: Apps: 746361311906; DSPS: 24597501; Offset : -4305895863
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-43 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-2027044152] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-43 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-2027044142] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-43 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-2027041121] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-43 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:11] from screen [on:0 period:-2027041110] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-43 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-2027038090] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-43 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-2027038087] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-2027035062] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:9] from screen [on:0 period:-2027035053] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-43 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-2027032031] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-43 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:11] from screen [on:0 period:-2027032020] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-2027028998] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-2027028995] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-2027025968] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-2027025965] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,D/sensors_hal_Time( 1029): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1029): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1029): tsOffsetIs: Apps: 766363212784; DSPS: 25252924; Offset : -4305917462
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-2027022937] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-2027022934] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-2027019906] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-2027019903] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-2027016877] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-2027016874] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-2027013851] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:9] from screen [on:0 period:-2027013842] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3000] from screen [on:0 period:-2027010817] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-2027010814] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-2027007791] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:9] from screen [on:0 period:-2027007782] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
D/PowerManagerServiceEx( 1029): acquireWakeLockInternal: lock=518109269, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1029
,V/AlarmManager( 1029): ELAPSED_WAKEUP set : Alarm{d203354 type 2 when 784992 android} when 784992
D/[Concierge]Service( 2608): onStartCommand(). Type : 9
,D/PowerManagerServiceEx( 1029): releaseWakeLockInternal: lock=518109269 [*alarm*], flags=0x0
,I/[SystemUI]TimeTickManager( 1462): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1462): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1462): called onTimeUpdated()
I/[SystemUI]Clock( 1462): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1462): called onTimeUpdated()
I/[SystemUI]DateView( 1462): called onTimeUpdated()
I/[SystemUI]DateView( 1462): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1462): handleTimeUpdate
,D/sensors_hal_Time( 1029): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1029): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1029): tsOffsetIs: Apps: 786364977828; DSPS: 25908341; Offset : -4305891972
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-2027004762] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:8] from screen [on:0 period:-2027004754] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-2027001733] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:11] from screen [on:0 period:-2027001722] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-2026998699] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-2026998696] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:-2026995671] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:12] from screen [on:0 period:-2026995659] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=1.7, 0.0, 0.0  rx=2.2 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-2026992636] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=1.7, 0.0, 0.0  rx=2.2 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-2026992633] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.9, 0.0, 0.0  rx=1.1 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-2026989606] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.9, 0.0, 0.0  rx=1.1 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-2026989603] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.9, 0.0, 0.0  rx=1.1 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-2026986577] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.9, 0.0, 0.0  rx=1.1 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-2026986574] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,D/sensors_hal_Time( 1029): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1029): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1029): tsOffsetIs: Apps: 806376644434; DSPS: 26564084; Offset : -4305913599
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=1.0, 0.0, 0.0  rx=1.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-2026983547] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=1.0, 0.0, 0.0  rx=1.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-2026983544] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.5 bcn=0 [on:0 tx:0 rx:0 period:3000] from screen [on:0 period:-2026980519] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.5 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-2026980516] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-2026977493] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:8] from screen [on:0 period:-2026977485] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
D/PowerManagerServiceEx( 1029): acquireWakeLockInternal: lock=518109269, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1029
,V/AlarmManager( 1029): ELAPSED_WAKEUP set : Alarm{2d51a2fd type 2 when 815177 android} when 815177
D/[Concierge]Service( 2608): onStartCommand(). Type : 9
,D/PowerManagerServiceEx( 1029): releaseWakeLockInternal: lock=518109269 [*alarm*], flags=0x0
,I/BooksSync( 6498): Starting books sync
,D/BooksSync( 6498): started syncMyEbooks
,V/GLSActivity( 2130): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     ( 2130): Explicit concurrent mark sweep GC freed 38353(2MB) AllocSpace objects, 25(3MB) LOS objects, 51% free, 30MB/62MB, paused 1.250ms total 72.352ms
,I/GLSUser ( 2130): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2130): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 2130): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2130): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2130): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1029): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
V/NotificationService( 1029): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1029): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1029): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1029): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,W/GLSActivity( 2130): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2130): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2130): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2130): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2130): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2130): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2130): 	at android.os.Binder.execTransact(Binder.java:446)
E/BooksAccountManager( 6498): Authentication error
E/BooksAccountManager( 6498): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6498): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6498): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6498): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6498): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6498): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6498): null auth token
D/libc-netbsd(  323): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  323): res_queryN name = www.googleapis.com, class = 1, type = 1
,D/LgeQuickCoverNLService( 1414): onNotificationPosted
,D/SmartCoverUpdateMonitor( 1414): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1414): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1414): handleNotificationPosted(true)
D/QuickCircle( 1414): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1414): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1414): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1414): post do just update job
D/LgeQuickCoverNotificationData( 1414): showAll3
D/LgeQuickCoverNotificationData( 1414): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1414): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1414): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1414): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1414): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1414): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1414): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1414): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1414): [native noti] inex =  2
,D/LgeQuickCoverNotificationData( 1414): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1414): updateNotificationData: count=3
D/QuickStatusbarLayout( 1414): Notification difference=198
D/QuickStatusbarLayout( 1414): child = android.widget.LinearLayout{1813a4 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,D/libc-netbsd(  323): res_queryN name = www.googleapis.com succeed
,W/ApiaryClient( 6498): Error response from books API: {
W/ApiaryClient( 6498):  "error": {
W/ApiaryClient( 6498):   "errors": [
W/ApiaryClient( 6498):    {
W/ApiaryClient( 6498):     "domain": "global",
W/ApiaryClient( 6498):     "reason": "required",
W/ApiaryClient( 6498):     "message": "Login Required",
W/ApiaryClient( 6498):     "locationType": "header",
W/ApiaryClient( 6498):     "location": "Authorization"
W/ApiaryClient( 6498):    }
W/ApiaryClient( 6498):   ],
W/ApiaryClient( 6498):   "code": 401,
W/ApiaryClient( 6498):   "message": "Login Required"
W/ApiaryClient( 6498):  }
W/ApiaryClient( 6498): }
,W/ApiaryClient( 6498): errCount = 1: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6498): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=861787641622835240&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6498): Headers:
W/ApiaryClient( 6498): accept-encoding: [gzip]
W/ApiaryClient( 6498): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6498): gdata-version: 2
V/GLSActivity( 2130): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2130): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2130): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2130): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2130): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2130): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1029): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1029): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1029): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1029): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1029): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1414): onNotificationPosted
,D/SmartCoverUpdateMonitor( 1414): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1414): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1414): handleNotificationPosted(true)
D/QuickCircle( 1414): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1414): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1414): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1414): post do just update job
D/LgeQuickCoverNotificationData( 1414): showAll3
D/LgeQuickCoverNotificationData( 1414): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1414): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1414): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1414): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1414): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1414): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1414): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1414): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1414): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1414): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1414): updateNotificationData: count=3
W/GLSActivity( 2130): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2130): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2130): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2130): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2130): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2130): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2130): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 6498): Authentication error
E/BooksAccountManager( 6498): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6498): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6498): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6498): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6498): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6498): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6498): null auth token
D/QuickStatusbarLayout( 1414): Notification difference=198
D/QuickStatusbarLayout( 1414): child = android.widget.LinearLayout{1813a4 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,W/ApiaryClient( 6498): Error response from books API: {
W/ApiaryClient( 6498):  "error": {
W/ApiaryClient( 6498):   "errors": [
W/ApiaryClient( 6498):    {
W/ApiaryClient( 6498):     "domain": "global",
W/ApiaryClient( 6498):     "reason": "required",
W/ApiaryClient( 6498):     "message": "Login Required",
W/ApiaryClient( 6498):     "locationType": "header",
W/ApiaryClient( 6498):     "location": "Authorization"
W/ApiaryClient( 6498):    }
W/ApiaryClient( 6498):   ],
W/ApiaryClient( 6498):   "code": 401,
W/ApiaryClient( 6498):   "message": "Login Required"
W/ApiaryClient( 6498):  }
W/ApiaryClient( 6498): }
,W/ApiaryClient( 6498): errCount = 2: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6498): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=861787641622835240&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6498): Headers:
W/ApiaryClient( 6498): accept-encoding: [gzip]
W/ApiaryClient( 6498): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6498): gdata-version: 2
E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-2026974464] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-2026974461] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,V/GLSActivity( 2130): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2130): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2130): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2130): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2130): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2130): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1029): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1029): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1029): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1029): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1029): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1414): onNotificationPosted
,D/SmartCoverUpdateMonitor( 1414): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1414): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1414): handleNotificationPosted(true)
D/QuickCircle( 1414): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1414): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1414): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1414): post do just update job
D/LgeQuickCoverNotificationData( 1414): showAll3
D/LgeQuickCoverNotificationData( 1414): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1414): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1414): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1414): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1414): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1414): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1414): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1414): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1414): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1414): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1414): updateNotificationData: count=3
W/GLSActivity( 2130): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2130): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2130): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2130): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2130): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2130): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2130): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 6498): Authentication error
E/BooksAccountManager( 6498): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6498): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6498): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6498): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6498): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6498): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6498): null auth token
D/QuickStatusbarLayout( 1414): Notification difference=198
D/QuickStatusbarLayout( 1414): child = android.widget.LinearLayout{1813a4 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
W/ApiaryClient( 6498): Error response from books API: {
W/ApiaryClient( 6498):  "error": {
W/ApiaryClient( 6498):   "errors": [
W/ApiaryClient( 6498):    {
W/ApiaryClient( 6498):     "domain": "global",
W/ApiaryClient( 6498):     "reason": "required",
W/ApiaryClient( 6498):     "message": "Login Required",
W/ApiaryClient( 6498):     "locationType": "header",
W/ApiaryClient( 6498):     "location": "Authorization"
W/ApiaryClient( 6498):    }
W/ApiaryClient( 6498):   ],
W/ApiaryClient( 6498):   "code": 401,
W/ApiaryClient( 6498):   "message": "Login Required"
W/ApiaryClient( 6498):  }
W/ApiaryClient( 6498): }
,W/ApiaryClient( 6498): errCount = 3: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6498): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=861787641622835240&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6498): Headers:
W/ApiaryClient( 6498): accept-encoding: [gzip]
W/ApiaryClient( 6498): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6498): gdata-version: 2
E/BooksSync( 6498): Soft error: 
E/BooksSync( 6498): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 6498): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=861787641622835240&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 6498): Headers:
E/BooksSync( 6498): accept-encoding: [gzip]
E/BooksSync( 6498): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 6498): gdata-version: 2
E/BooksSync( 6498): 
E/BooksSync( 6498): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 6498): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 6498): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 6498): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 6498): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 6498): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 6498): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 6498): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 6498): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 6498): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 6498): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 6498): {
E/BooksSync( 6498):  "error": {
E/BooksSync( 6498):   "errors": [
E/BooksSync( 6498):    {
E/BooksSync( 6498):     "domain": "global",
E/BooksSync( 6498):     "reason": "required",
E/BooksSync( 6498):     "message": "Login Required",
E/BooksSync( 6498):     "locationType": "header",
E/BooksSync( 6498):     "location": "Authorization"
E/BooksSync( 6498):    }
E/BooksSync( 6498):   ],
E/BooksSync( 6498):   "code": 401,
E/BooksSync( 6498):   "message": "Login Required"
E/BooksSync( 6498):  }
E/BooksSync( 6498): }
E/BooksSync( 6498): 
E/BooksSync( 6498): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 6498): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 6498): 	... 8 more
,E/BooksSync( 6498): Sync error
E/BooksSync( 6498): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 6498): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=861787641622835240&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 6498): Headers:
E/BooksSync( 6498): accept-encoding: [gzip]
E/BooksSync( 6498): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 6498): gdata-version: 2
E/BooksSync( 6498): 
E/BooksSync( 6498): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 6498): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 6498): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 6498): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 6498): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 6498): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 6498): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 6498): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 6498): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 6498): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 6498): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 6498): {
E/BooksSync( 6498):  "error": {
E/BooksSync( 6498):   "errors": [
E/BooksSync( 6498):    {
E/BooksSync( 6498):     "domain": "global",
E/BooksSync( 6498):     "reason": "required",
E/BooksSync( 6498):     "message": "Login Required",
E/BooksSync( 6498):     "locationType": "header",
E/BooksSync( 6498):     "location": "Authorization"
E/BooksSync( 6498):    }
E/BooksSync( 6498):   ],
E/BooksSync( 6498):   "code": 401,
E/BooksSync( 6498):   "message": "Login Required"
E/BooksSync( 6498):  }
E/BooksSync( 6498): }
E/BooksSync( 6498): 
E/BooksSync( 6498): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 6498): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 6498): 	... 8 more
I/BooksSync( 6498): Finished books sync
D/SyncManager( 1029): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 811902, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=6.2, 0.0, 0.0  rx=6.2 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-2026971433] gl rssi=-44 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=6.2, 0.0, 0.0  rx=6.2 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-2026971430] gl rssi=-44 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=4.6, 0.0, 0.0  rx=4.6 bcn=0 [on:0 tx:0 rx:0 period:3000] from screen [on:0 period:-2026968404] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=4.6, 0.0, 0.0  rx=4.6 bcn=0 [on:0 tx:0 rx:0 period:4] from screen [on:0 period:-2026968400] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,D/sensors_hal_Time( 1029): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1029): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1029): tsOffsetIs: Apps: 826378661615; DSPS: 27219510; Offset : -4305910734
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=2.3, 0.0, 0.0  rx=2.3 bcn=0 [on:0 tx:0 rx:0 period:3000] from screen [on:0 period:-2026965375] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=2.3, 0.0, 0.0  rx=2.3 bcn=0 [on:0 tx:0 rx:0 period:4] from screen [on:0 period:-2026965371] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=1.6, 0.0, 0.0  rx=1.6 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-2026962350] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=1.6, 0.0, 0.0  rx=1.6 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-2026962347] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-2026959320] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-2026959310] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.9, 0.0, 0.0  rx=0.9 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:-2026956287] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.9, 0.0, 0.0  rx=0.9 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-2026956284] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-43 f=2412 sc=60 link=72 tx=1.0, 0.0, 0.0  rx=1.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-2026953257] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-43 f=2412 sc=60 link=72 tx=1.0, 0.0, 0.0  rx=1.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-2026953254] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-43 f=2412 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.5 bcn=0 [on:0 tx:0 rx:0 period:3009] from screen [on:0 period:-2026950220] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-43 f=2412 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.5 bcn=0 [on:0 tx:0 rx:0 period:12] from screen [on:0 period:-2026950208] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-43 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-2026947193] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-43 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-2026947183] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
V/AlarmManager( 1029): ELAPSED_WAKEUP set : Alarm{4dc597f type 2 when 845267 android} when 845267
,I/[SystemUI]TimeTickManager( 1462): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1462): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1462): called onTimeUpdated()
I/[SystemUI]Clock( 1462): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1462): called onTimeUpdated()
I/[SystemUI]DateView( 1462): called onTimeUpdated()
I/[SystemUI]DateView( 1462): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1462): handleTimeUpdate
D/sensors_hal_Time( 1029): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1029): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1029): tsOffsetIs: Apps: 846381156660; DSPS: 27874952; Offset : -4305917947
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-43 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-2026944163] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-43 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:8] from screen [on:0 period:-2026944155] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-2026941133] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-2026941130] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-2026938101] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-2026938091] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=1.4, 0.0, 0.0  rx=1.9 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-2026935068] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=1.4, 0.0, 0.0  rx=1.9 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-2026935065] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-43 f=2412 sc=60 link=72 tx=1.2, 0.0, 0.0  rx=1.5 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-2026932038] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-43 f=2412 sc=60 link=72 tx=1.2, 0.0, 0.0  rx=1.5 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-2026932035] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-43 f=2412 sc=60 link=72 tx=0.6, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-2026929013] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-43 f=2412 sc=60 link=72 tx=0.6, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-2026929010] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-43 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.9 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-2026925981] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-43 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.9 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-2026925971] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
D/sensors_hal_Time( 1029): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1029): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1029): tsOffsetIs: Apps: 866383337590; DSPS: 28530383; Offset : -4305903791
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-43 f=2412 sc=60 link=72 tx=0.9, 0.0, 0.0  rx=0.9 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-2026922950] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-43 f=2412 sc=60 link=72 tx=0.9, 0.0, 0.0  rx=0.9 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-2026922940] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-43 f=2412 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.5 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-2026919920] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-43 f=2412 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.5 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-2026919910] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-43 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-2026916888] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-43 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-2026916885] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-43 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-2026913860] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-43 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-2026913850] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-43 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-2026910826] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-43 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-2026910823] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-2026907797] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-2026907794] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,D/sensors_hal_Time( 1029): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1029): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1029): tsOffsetIs: Apps: 886385506488; DSPS: 29185814; Offset : -4305901537
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:-2026904766] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-2026904763] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-2026901736] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-2026901733] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-2026898710] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:11] from screen [on:0 period:-2026898699] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3005] from screen [on:0 period:-2026895676] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-2026895673] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3000] from screen [on:0 period:-2026892647] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-2026892644] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-2026889617] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-2026889614] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-2026886587] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-2026886584] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,I/[SystemUI]TimeTickManager( 1462): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1462): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1462): called onTimeUpdated()
I/[SystemUI]Clock( 1462): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1462): called onTimeUpdated()
I/[SystemUI]DateView( 1462): called onTimeUpdated()
I/[SystemUI]DateView( 1462): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1462): handleTimeUpdate
D/sensors_hal_Time( 1029): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1029): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1029): tsOffsetIs: Apps: 906388943407; DSPS: 29841287; Offset : -4305913183
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-2026883556] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-2026883553] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-2026880527] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-2026880524] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-2026877498] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-2026877495] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-2026874469] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-2026874466] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-2026871439] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-2026871436] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-2026868411] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:11] from screen [on:0 period:-2026868400] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
D/sensors_hal_Time( 1029): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1029): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1029): tsOffsetIs: Apps: 926391532098; DSPS: 30496732; Offset : -4305918434
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-2026865379] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-2026865376] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-2026862351] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:9] from screen [on:0 period:-2026862342] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-2026859321] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:12] from screen [on:0 period:-2026859309] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-2026856287] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-2026856284] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3000] from screen [on:0 period:-2026853259] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-2026853256] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3000] from screen [on:0 period:-2026850231] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-2026850230] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:-2026847208] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-2026847205] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,D/sensors_hal_Time( 1029): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1029): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1029): tsOffsetIs: Apps: 946393458913; DSPS: 31152155; Offset : -4305914356
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:-2026844177] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-2026844167] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-2026841145] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-2026841142] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.9, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-2026838116] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.9, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-2026838113] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-2026835086] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-2026835083] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-43 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-2026832057] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-43 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-2026832054] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-43 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-2026829028] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-43 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-2026829025] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-2026825999] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:2] from screen [on:0 period:-2026825997] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,I/[SystemUI]TimeTickManager( 1462): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1462): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1462): called onTimeUpdated()
I/[SystemUI]Clock( 1462): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1462): called onTimeUpdated()
I/[SystemUI]DateView( 1462): called onTimeUpdated()
I/[SystemUI]DateView( 1462): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1462): handleTimeUpdate
D/sensors_hal_Time( 1029): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1029): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1029): tsOffsetIs: Apps: 966395360415; DSPS: 31807577; Offset : -4305904892
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.9 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-2026822982] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.9 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-2026822972] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-2026819950] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:11] from screen [on:0 period:-2026819939] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-2026816918] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-2026816915] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-43 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-2026813888] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-43 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-2026813885] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-43 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-2026810858] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-43 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-2026810855] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-43 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-2026807837] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-43 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-2026807834] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,D/sensors_hal_Time( 1029): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1029): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1029): tsOffsetIs: Apps: 986397165356; DSPS: 32462996; Offset : -4305900280
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-43 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-2026804810] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-43 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:4] from screen [on:0 period:-2026804806] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-2026801781] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:11] from screen [on:0 period:-2026801770] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-2026798744] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-2026798741] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-2026795713] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:9] from screen [on:0 period:-2026795704] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-2026792689] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-2026792686] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3000] from screen [on:0 period:-2026789661] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-2026789651] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-2026786630] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:4] from screen [on:0 period:-2026786626] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,D/sensors_hal_Time( 1029): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1029): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1029): tsOffsetIs: Apps: 1006399041494; DSPS: 33118418; Offset : -4305916492
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-2026783601] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-2026783591] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-2026780570] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-2026780560] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-2026777546] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-2026777543] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-2026774516] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-2026774513] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-2026771486] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-2026771483] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-2026768457] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-2026768454] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,I/[SystemUI]TimeTickManager( 1462): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1462): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1462): called onTimeUpdated()
I/[SystemUI]Clock( 1462): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1462): called onTimeUpdated()
,I/[SystemUI]DateView( 1462): called onTimeUpdated()
I/[SystemUI]DateView( 1462): called onTimeUpdated()
,D/KeyguardUpdateMonitor( 1462): handleTimeUpdate
D/sensors_hal_Time( 1029): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1029): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1029): tsOffsetIs: Apps: 1026412499352; DSPS: 33774219; Offset : -4305916913
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-2026765426] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:4] from screen [on:0 period:-2026765422] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-2026762404] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-2026762401] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-2026759376] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-2026759373] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-2026756347] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-2026756344] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-2026753318] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-2026753315] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-2026750289] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-2026750286] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-2026747267] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-2026747264] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,D/sensors_hal_Time( 1029): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1029): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1029): tsOffsetIs: Apps: 1046414128042; DSPS: 34429632; Offset : -4305905551
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-2026744238] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-2026744235] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3000] from screen [on:0 period:-2026741211] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-2026741201] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-43 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-2026738179] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-43 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-2026738176] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-43 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-2026735148] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-43 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-2026735145] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-43 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-2026732127] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-43 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-2026732124] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-43 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-2026729098] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-43 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-2026729095] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-43 f=2412 sc=60 link=72 tx=3.2, 0.0, 0.0  rx=3.7 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-2026726071] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-43 f=2412 sc=60 link=72 tx=3.2, 0.0, 0.0  rx=3.7 bcn=0 [on:0 tx:0 rx:0 period:9] from screen [on:0 period:-2026726062] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
D/sensors_hal_Time( 1029): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1029): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1029): tsOffsetIs: Apps: 1066415983554; DSPS: 35085053; Offset : -4305911663
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-43 f=2412 sc=60 link=72 tx=1.6, 0.0, 0.0  rx=1.9 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-2026723046] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-43 f=2412 sc=60 link=72 tx=1.6, 0.0, 0.0  rx=1.9 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-2026723043] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-43 f=2412 sc=60 link=72 tx=1.3, 0.0, 0.0  rx=1.4 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-2026720019] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-43 f=2412 sc=60 link=72 tx=1.3, 0.0, 0.0  rx=1.4 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-2026720009] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-43 f=2412 sc=60 link=72 tx=1.2, 0.0, 0.0  rx=1.2 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-2026716995] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-43 f=2412 sc=60 link=72 tx=1.2, 0.0, 0.0  rx=1.2 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-2026716992] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-43 f=2412 sc=60 link=72 tx=0.6, 0.0, 0.0  rx=0.6 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-2026713965] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-43 f=2412 sc=60 link=72 tx=0.6, 0.0, 0.0  rx=0.6 bcn=0 [on:0 tx:0 rx:0 period:4] from screen [on:0 period:-2026713961] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-43 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-2026710937] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-43 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-2026710934] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-43 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-2026707908] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-43 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-2026707905] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,I/[SystemUI]TimeTickManager( 1462): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1462): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1462): called onTimeUpdated()
I/[SystemUI]Clock( 1462): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1462): called onTimeUpdated()
I/[SystemUI]DateView( 1462): called onTimeUpdated()
I/[SystemUI]DateView( 1462): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1462): handleTimeUpdate
D/sensors_hal_Time( 1029): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1029): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1029): tsOffsetIs: Apps: 1086418119172; DSPS: 35740483; Offset : -4305912301
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-43 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-2026704880] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-43 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-2026704870] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-43 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.9 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-2026701856] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-43 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.9 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-2026701853] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-43 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3000] from screen [on:0 period:-2026698827] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-43 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-2026698824] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-43 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-2026695798] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-43 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-2026695795] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-43 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-2026692769] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-43 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-2026692766] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-43 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-2026689747] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-43 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-2026689744] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-43 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-2026686725] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-43 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-2026686722] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,D/sensors_hal_Time( 1029): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1029): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1029): tsOffsetIs: Apps: 1106419732549; DSPS: 36395896; Offset : -4305916225
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-43 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-2026683696] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-43 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-2026683693] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-43 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-2026680666] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-43 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-2026680663] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-43 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-2026677636] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-43 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-2026677633] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-43 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-2026674606] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-43 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-2026674603] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-43 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-2026671585] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-43 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-2026671582] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-43 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-2026668556] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-43 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-2026668553] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,D/sensors_hal_Time( 1029): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1029): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1029): tsOffsetIs: Apps: 1126422600615; DSPS: 37051350; Offset : -4305916915
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-43 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-2026665527] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-43 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-2026665524] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-2026662497] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-2026662494] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-2026659467] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-2026659464] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-2026656435] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-2026656432] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-2026653406] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-2026653403] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-2026650377] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-2026650374] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-2026647348] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:4] from screen [on:0 period:-2026647344] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,I/[SystemUI]TimeTickManager( 1462): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1462): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1462): called onTimeUpdated()
I/[SystemUI]Clock( 1462): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1462): called onTimeUpdated()
I/[SystemUI]DateView( 1462): called onTimeUpdated()
I/[SystemUI]DateView( 1462): called onTimeUpdated()
,D/KeyguardUpdateMonitor( 1462): handleTimeUpdate
D/sensors_hal_Time( 1029): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1029): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1029): tsOffsetIs: Apps: 1146424534410; DSPS: 37706773; Offset : -4305905754
,D/PowerManagerServiceEx( 1029): acquireWakeLockInternal: lock=518109269, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1029
,D/[Concierge]Service( 2608): onStartCommand(). Type : 9
,I/DigitalAppWidgetProvider( 6774): onReceive: com.android.deskclock.ON_QUARTER_HOUR
,V/DigitalAppWidgetProvider( 6774): startAlarmOnQuarterHour android.app.ReceiverRestrictedContext@7038f05
D/PowerManagerServiceEx( 1029): releaseWakeLockInternal: lock=518109269 [*alarm*], flags=0x0
E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:-2026644319] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-2026644316] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-2026641293] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-2026641283] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-2026638263] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:11] from screen [on:0 period:-2026638252] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-2026635234] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-2026635231] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-2026632205] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-2026632202] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-2026629174] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-2026629171] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-2026626142] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:8] from screen [on:0 period:-2026626134] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
D/sensors_hal_Time( 1029): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1029): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1029): tsOffsetIs: Apps: 1166426692631; DSPS: 38362204; Offset : -4305914204
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-2026623113] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-2026623110] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-2026620083] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-2026620080] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0,
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3000] from screen [on:0 period:-2026617055] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:4] from screen [on:0 period:-2026617051] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-2026614024] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-2026614021] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-2026610995] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-2026610992] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-2026607965] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:11] from screen [on:0 period:-2026607954] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
V/AlarmManager( 1029): ELAPSED_WAKEUP set : Alarm{2c50fd4c type 2 when 1185803 com.android.bluetooth} when 1185803
,W/bt-smp  ( 6103): Key(LSB ~ MSB) = 0a 3c a6 fe eb 17 6a 79 a6 1f 0a 0b f9 50 a0 5f 
W/bt-smp  ( 6103): Plain text(LSB ~ MSB) = 44 ae 41 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 6103): Encrypted text(LSB ~ MSB) = 80 32 17 29 9a c6 8f 57 36 ce 3f e9 aa 1e 09 3a 
W/bt-btm  ( 6103): Stopping oneshot timer
D/sensors_hal_Time( 1029): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1029): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1029): tsOffsetIs: Apps: 1186428636165; DSPS: 39017627; Offset : -4305893302
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-2026604936] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-2026604933] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-2026601906] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-2026601903] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:-2026598884] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-2026598881] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-2026595855] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:4] from screen [on:0 period:-2026595851] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-2026592826] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-2026592823] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-2026589796] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-2026589793] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-43 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-2026586767] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-43 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-2026586764] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,I/[SystemUI]TimeTickManager( 1462): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1462): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1462): called onTimeUpdated()
I/[SystemUI]Clock( 1462): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1462): called onTimeUpdated()
I/[SystemUI]DateView( 1462): called onTimeUpdated()
I/[SystemUI]DateView( 1462): called onTimeUpdated()
,D/KeyguardUpdateMonitor( 1462): handleTimeUpdate
D/sensors_hal_Time( 1029): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1029): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1029): tsOffsetIs: Apps: 1206431514647; DSPS: 39673082; Offset : -4305914017
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-43 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-2026583736] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-43 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-2026583733] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-43 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3000] from screen [on:0 period:-2026580708] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-43 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-2026580705] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-43 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-2026577679] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-43 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-2026577676] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-43 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-2026574651] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-43 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:9] from screen [on:0 period:-2026574642] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
I/UsageStatsService( 1029): User[0] Flushing usage stats to disk
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-43 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-2026571621] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-43 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-2026571611] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-43 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-2026568589] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-43 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-2026568586] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,D/sensors_hal_Time( 1029): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1029): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1029): tsOffsetIs: Apps: 1226433580733; DSPS: 40328510; Offset : -4305923229
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-2026565559] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:9] from screen [on:0 period:-2026565550] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-2026562527] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-2026562524] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:-2026559497] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-2026559494] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:-2026556466] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-2026556463] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-2026553442] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-2026553432] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-2026550409] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-2026550406] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-2026547378] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:4] from screen [on:0 period:-2026547374] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,D/sensors_hal_Time( 1029): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1029): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1029): tsOffsetIs: Apps: 1246435665153; DSPS: 40983938; Offset : -4305913797
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-2026544348] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-2026544345] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-2026541320] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-2026541310] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-2026538288] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-2026538285] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-2026535258] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-2026535255] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-2026532228] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-2026532225] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-2026529198] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-2026529195] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-2026526169] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-2026526166] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,I/[SystemUI]TimeTickManager( 1462): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1462): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1462): called onTimeUpdated()
I/[SystemUI]Clock( 1462): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1462): called onTimeUpdated()
I/[SystemUI]DateView( 1462): called onTimeUpdated()
I/[SystemUI]DateView( 1462): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1462): handleTimeUpdate
,D/sensors_hal_Time( 1029): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1029): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1029): tsOffsetIs: Apps: 1266437828530; DSPS: 41639369; Offset : -4305917142
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-2026523141] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-2026523131] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-2026520111] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:11] from screen [on:0 period:-2026520100] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-2026517078] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:4] from screen [on:0 period:-2026517074] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-2026514047] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-2026514044] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-2026511020] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:11] from screen [on:0 period:-2026511009] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-2026507992] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-2026507982] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
D/sensors_hal_Time( 1029): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1029): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1029): tsOffsetIs: Apps: 1286439998678; DSPS: 42294800; Offset : -4305913820
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-2026504960] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-2026504957] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-2026501931] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:11] from screen [on:0 period:-2026501920] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-2026498898] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-2026498895] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-2026495869] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-2026495866] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-2026492839] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-2026492836] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-2026489810] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-2026489800] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-2026486778] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-2026486775] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,D/sensors_hal_Time( 1029): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1029): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1029): tsOffsetIs: Apps: 1306441888203; DSPS: 42950222; Offset : -4305916490
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-2026483746] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-2026483743] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.9, 0.0, 0.0  rx=0.9 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-2026480718] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.9, 0.0, 0.0  rx=0.9 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-2026480715] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:-2026477686] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-2026477683] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-2026474657] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-2026474654] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-2026471627] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-2026471624] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-2026468597] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-2026468594] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,I/[SystemUI]TimeTickManager( 1462): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1462): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1462): called onTimeUpdated()
I/[SystemUI]Clock( 1462): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1462): called onTimeUpdated()
I/[SystemUI]DateView( 1462): called onTimeUpdated()
I/[SystemUI]DateView( 1462): called onTimeUpdated()
,D/KeyguardUpdateMonitor( 1462): handleTimeUpdate
D/sensors_hal_Time( 1029): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1029): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1029): tsOffsetIs: Apps: 1326444027414; DSPS: 43605652; Offset : -4305913405
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-2026465575] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-2026465572] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-2026462547] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-2026462544] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-2026459516] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-2026459513] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,D/PowerManagerServiceEx( 1029): acquireWakeLockInternal: lock=518109269, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1029
,V/AlarmManager( 1029): ELAPSED_WAKEUP set : Alarm{713195 type 2 when 1333245 android} when 1333245
D/[Concierge]Service( 2608): onStartCommand(). Type : 9
,D/PowerManagerServiceEx( 1029): releaseWakeLockInternal: lock=518109269 [*alarm*], flags=0x0
,I/BooksSync( 6498): Starting books sync
,I/GoogleURLConnFactory( 2363): Using platform SSLCertificateSocketFactory
D/BooksSync( 6498): started syncMyEbooks
,I/art     ( 1029): Explicit concurrent mark sweep GC freed 258359(12MB) AllocSpace objects, 30(1376KB) LOS objects, 33% free, 44MB/67MB, paused 2.408ms total 144.051ms
,V/GLSActivity( 2130): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/GLSUser ( 2130): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: mail
I/GLSUser ( 2130): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> mail without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2130): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2130): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2130): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1029): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1029): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1029): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1029): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1029): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
W/GLSActivity( 2130): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2130): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2130): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2130): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2130): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2130): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2130): 	at android.os.Binder.execTransact(Binder.java:446)
D/LgeQuickCoverNLService( 1414): onNotificationPosted
,W/SubscribedFeeds( 2363): Hard error
D/SmartCoverUpdateMonitor( 1414): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1414): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1414): handleNotificationPosted(true)
D/QuickCircle( 1414): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1414): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1414): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1414): post do just update job
D/LgeQuickCoverNotificationData( 1414): showAll3
D/LgeQuickCoverNotificationData( 1414): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1414): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1414): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1414): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1414): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1414): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1414): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1414): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1414): [native noti] inex =  2,
D/LgeQuickCoverNotificationData( 1414): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1414): updateNotificationData: count=3
I/GLSUser ( 2130): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 2130): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2130): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2130): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
D/SyncManager( 1029): failed sync operation thalitester@gmail.com u0 (com.google), subscribedfeeds, PERIODIC, currentRunTime 1333624, reason: Periodic, SyncResult: stats [ numAuthExceptions: 1]
D/QuickStatusbarLayout( 1414): Notification difference=198
D/QuickStatusbarLayout( 1414): child = android.widget.LinearLayout{1813a4 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
D/SyncManager( 1029): not retrying sync operation because the error is a hard error: thalitester@gmail.com u0 (com.google), subscribedfeeds, PERIODIC, currentRunTime 1365907, reason: Periodic
V/GLSActivity( 2130): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager( 1029): Start proc com.google.android.syncadapters.calendar for service com.google.android.syncadapters.calendar/.CalendarSyncAdapterService: pid=7607 uid=10069 gids={50069, 9997, 3003} abi=armeabi-v7a
,V/NotificationService( 1029): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
V/NotificationService( 1029): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1029): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1029): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
,D/NotificationServiceEx( 1029): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1414): onNotificationPosted
D/SmartCoverUpdateMonitor( 1414): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1414): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1414): handleNotificationPosted(true)
D/QuickCircle( 1414): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1414): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1414): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1414): post do just update job
D/LgeQuickCoverNotificationData( 1414): showAll3
D/LgeQuickCoverNotificationData( 1414): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1414): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1414): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1414): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1414): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1414): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1414): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1414): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1414): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1414): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1414): updateNotificationData: count=3
W/GLSActivity( 2130): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2130): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2130): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2130): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2130): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2130): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2130): 	at android.os.Binder.execTransact(Binder.java:446)
E/BooksAccountManager( 6498): Authentication error
E/BooksAccountManager( 6498): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6498): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6498): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6498): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6498): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6498): 	at android.os.Binder.execTransact(Binder.java:446)
,E/HttpHelper( 6498): null auth token
D/libc-netbsd(  323): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  323): res_queryN name = www.googleapis.com, class = 1, type = 1
D/QuickStatusbarLayout( 1414): Notification difference=198
D/QuickStatusbarLayout( 1414): child = android.widget.LinearLayout{1813a4 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,D/libc-netbsd(  323): res_queryN name = www.googleapis.com succeed
,W/AbstractGoogleClient( 7607): Application name is not set. Call Builder#setApplicationName.
,I/ActivityManager( 1029): Start proc com.android.providers.calendar for content provider com.android.providers.calendar/.CalendarProvider2: pid=7632 uid=10014 gids={50014, 9997, 3003, 1028, 1015} abi=armeabi
,W/ApiaryClient( 6498): Error response from books API: {
W/ApiaryClient( 6498):  "error": {
W/ApiaryClient( 6498):   "errors": [
W/ApiaryClient( 6498):    {
W/ApiaryClient( 6498):     "domain": "global",
W/ApiaryClient( 6498):     "reason": "required",
W/ApiaryClient( 6498):     "message": "Login Required",
W/ApiaryClient( 6498):     "locationType": "header",
W/ApiaryClient( 6498):     "location": "Authorization"
W/ApiaryClient( 6498):    }
W/ApiaryClient( 6498):   ],
W/ApiaryClient( 6498):   "code": 401,
W/ApiaryClient( 6498):   "message": "Login Required"
W/ApiaryClient( 6498):  }
W/ApiaryClient( 6498): }
W/ApiaryClient( 6498): errCount = 1: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6498): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-7869753712989766188&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6498): Headers:
W/ApiaryClient( 6498): accept-encoding: [gzip]
W/ApiaryClient( 6498): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6498): gdata-version: 2
,W/ResourcesManager( 7632): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,D/CalendarProvider2( 7632): [initialize] mInstance = com.android.providers.calendar.CalendarProvider2@a204e02
,D/CalendarProvider2( 7632): [getOrCreateCalendarAlarmManager]
,I/CalendarProvider2( 7632): Created com.android.providers.calendar.CalendarAlarmManager@328fbd6f(com.android.providers.calendar.CalendarProvider2@a204e02)
,I/GLSUser ( 2130): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.syncadapters.calendar, service: oauth2:https://www.googleapis.com/auth/calendar
I/GLSUser ( 2130): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/calendar without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2130): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2130): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2130): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1029): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1029): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1029): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1029): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1029): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1414): onNotificationPosted
,D/SmartCoverUpdateMonitor( 1414): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1414): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1414): handleNotificationPosted(true)
D/QuickCircle( 1414): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1414): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1414): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1414): post do just update job
D/LgeQuickCoverNotificationData( 1414): showAll3
D/LgeQuickCoverNotificationData( 1414): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1414): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1414): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1414): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1414): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1414): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1414): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1414): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1414): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1414): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1414): updateNotificationData: count=3
,E/CalendarSyncAdapter( 7607): Exception in onPerformLoggedSync 
E/CalendarSyncAdapter( 7607): com.google.android.apiary.AuthenticationException: Could not get an auth token
E/CalendarSyncAdapter( 7607): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(GoogleRequestInitializer.java:152)
E/CalendarSyncAdapter( 7607): 	at com.google.android.apiary.GoogleRequestInitializer.intercept(GoogleRequestInitializer.java:89)
E/CalendarSyncAdapter( 7607): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:858)
E/CalendarSyncAdapter( 7607): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(AbstractGoogleClientRequest.java:410)
E/CalendarSyncAdapter( 7607): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(AbstractGoogleClientRequest.java:343)
E/CalendarSyncAdapter( 7607): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(AbstractGoogleClientRequest.java:460)
E/CalendarSyncAdapter( 7607): 	at com.google.android.syncadapters.calendar.CalendarSyncAdapterApiary.processAccountCalendars(CalendarSyncAdapterApiary.java:1510)
E/CalendarSyncAdapter( 7607): 	at com.google.android.syncadapters.calendar.CalendarSyncAdapterApiary.updateCalendarsFromServerFeed(CalendarSyncAdapterApiary.java:1024)
E/CalendarSyncAdapter( 7607): 	at com.google.android.syncadapters.calendar.CalendarSyncAdapterApiary.getServerDiffs(CalendarSyncAdapterApiary.java:906)
E/CalendarSyncAdapter( 7607): 	at com.google.android.syncadapters.calendar.CalendarSyncAdapterApiary.performSync(CalendarSyncAdapterApiary.java:430)
E/CalendarSyncAdapter( 7607): 	at com.google.android.syncadapters.calendar.CalendarSyncAdapterApiary.onPerformLoggedSync(CalendarSyncAdapterApiary.java:335)
E/CalendarSyncAdapter( 7607): 	at com.google.android.common.LoggingThreadedSyncAdapter.onPerformSync(LoggingThreadedSyncAdapter.java:33)
E/CalendarSyncAdapter( 7607): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/CalendarSyncAdapter( 7607): Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/CalendarSyncAdapter( 7607): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/CalendarSyncAdapter( 7607): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/CalendarSyncAdapter( 7607): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(GoogleRequestInitializer.java:140)
E/CalendarSyncAdapter( 7607): 	... 12 more
D/QuickStatusbarLayout( 1414): Notification difference=198
D/QuickStatusbarLayout( 1414): child = android.widget.LinearLayout{1813a4 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
I/ActivityManager( 1029): Killing 6820:com.android.calendar/u0a13 (adj 15): empty #17
D/SyncManager( 1029): failed sync operation thalitester@gmail.com u0 (com.google), com.android.calendar, PERIODIC, currentRunTime 1333637, reason: Periodic, SyncResult: stats [ numAuthExceptions: 1]
,D/SyncManager( 1029): not retrying sync operation because the error is a hard error: thalitester@gmail.com u0 (com.google), com.android.calendar, PERIODIC, currentRunTime 1367336, reason: Periodic
W/libprocessgroup( 1029): failed to open /acct/uid_10013/pid_6820/cgroup.procs: No such file or directory
,I/GCoreUlr( 1836): Uploading GCM registration ID for account#2#
,W/BaseAppContext( 1836): Using Auth Proxy for data requests.
,I/GLSUser ( 1836): [ChannelManager] Attempting to channel bind connection HttpClient.,
,I/GLSUser ( 1836): [ChannelManager] Checking whether channelId is enabled. isEnabledGmsCore? false, isEnabledSdk? true, isAtLeastKitKat? true
,I/GLSUser ( 2130): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/userlocation.reporting
I/GLSUser ( 2130): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/userlocation.reporting without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2130): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2130): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2130): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
E/GCoreUlr( 1836): 
E/GCoreUlr( 1836): com.google.android.gms.auth.ad: BadAuthentication
E/GCoreUlr( 1836): 	at com.google.android.gms.auth.p.b(SourceFile:442)
E/GCoreUlr( 1836): 	at com.google.android.gms.auth.p.a(SourceFile:365)
E/GCoreUlr( 1836): 	at com.google.android.gms.auth.p.a(SourceFile:310)
E/GCoreUlr( 1836): 	at com.google.android.gms.common.server.a.a.b(SourceFile:97)
E/GCoreUlr( 1836): 	at com.google.android.gms.common.server.c.b(SourceFile:109)
E/GCoreUlr( 1836): 	at com.google.android.gms.common.server.o.b(SourceFile:30)
E/GCoreUlr( 1836): 	at com.google.android.gms.common.server.o.b(SourceFile:370)
E/GCoreUlr( 1836): 	at com.google.android.gms.common.server.o.a(SourceFile:340)
E/GCoreUlr( 1836): 	at com.google.android.gms.common.server.o.a(SourceFile:319)
E/GCoreUlr( 1836): 	at com.google.android.location.reporting.c.c.a(SourceFile:166)
E/GCoreUlr( 1836): 	at com.google.android.location.reporting.c.g.a(SourceFile:111)
E/GCoreUlr( 1836): 	at com.google.android.location.reporting.service.t.b(SourceFile:220)
E/GCoreUlr( 1836): 	at com.google.android.location.reporting.service.t.a(SourceFile:173)
E/GCoreUlr( 1836): 	at com.google.android.location.reporting.service.s.onPerformSync(SourceFile:149)
E/GCoreUlr( 1836): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
,D/SyncManager( 1029): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.location.reporting, PERIODIC, currentRunTime 1333641, reason: Periodic, SyncResult: stats [ numAuthExceptions: 1]
,D/SyncManager( 1029): not retrying sync operation because the error is a hard error: thalitester@gmail.com u0 (com.google), com.google.android.location.reporting, PERIODIC, currentRunTime 1365611, reason: Periodic
,I/ActivityManager( 1029): Start proc com.google.android.gm for service com.google.android.gm/.provider.MailSyncAdapterService: pid=7664 uid=10064 gids={50064, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,V/GLSActivity( 2130): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2130): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2130): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2130): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 2130): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2130): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1029): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1029): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1029): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1029): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1029): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
W/GLSActivity( 2130): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2130): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2130): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2130): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2130): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2130): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2130): 	at android.os.Binder.execTransact(Binder.java:446)
E/BooksAccountManager( 6498): Authentication error
E/BooksAccountManager( 6498): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6498): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6498): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6498): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6498): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6498): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6498): null auth token
D/LgeQuickCoverNLService( 1414): onNotificationPosted
,D/SmartCoverUpdateMonitor( 1414): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1414): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1414): handleNotificationPosted(true)
D/QuickCircle( 1414): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1414): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1414): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1414): post do just update job
D/LgeQuickCoverNotificationData( 1414): showAll3
D/LgeQuickCoverNotificationData( 1414): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1414): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1414): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1414): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1414): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1414): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1414): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1414): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1414): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1414): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1414): updateNotificationData: count=3
D/QuickStatusbarLayout( 1414): Notification difference=198
D/QuickStatusbarLayout( 1414): child = android.widget.LinearLayout{1813a4 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,W/ApiaryClient( 6498): Error response from books API: {
W/ApiaryClient( 6498):  "error": {
W/ApiaryClient( 6498):   "errors": [
W/ApiaryClient( 6498):    {
W/ApiaryClient( 6498):     "domain": "global",
W/ApiaryClient( 6498):     "reason": "required",
W/ApiaryClient( 6498):     "message": "Login Required",
W/ApiaryClient( 6498):     "locationType": "header",
W/ApiaryClient( 6498):     "location": "Authorization"
W/ApiaryClient( 6498):    }
W/ApiaryClient( 6498):   ],
W/ApiaryClient( 6498):   "code": 401,
W/ApiaryClient( 6498):   "message": "Login Required"
W/ApiaryClient( 6498):  }
W/ApiaryClient( 6498): }
,W/ApiaryClient( 6498): errCount = 2: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6498): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-7869753712989766188&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6498): Headers:
W/ApiaryClient( 6498): accept-encoding: [gzip]
W/ApiaryClient( 6498): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6498): gdata-version: 2
E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3000] from screen [on:0 period:-2026456489] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-2026456488] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,W/ActivityManager( 1029): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,D/ActivityThread( 7664): Loading provider com.google.android.gmail.provider;com.android.mail.notifier;com.google.android.gm.email.provider;com.google.android.gm.email.notifier: com.android.email.provider.EmailProvider
W/ActivityManager( 1029): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
I/Gmail   ( 7664): getAccountsCursor
,V/GLSActivity( 2130): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/ActivityManager( 1029): Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
,W/ActivityManager( 1029): Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
W/ActivityManager( 1029): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
I/Gmail   ( 7664): Observing account changes for notifications
,W/ActivityManager( 1029): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,W/GAV2    ( 7664): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,W/ActivityManager( 1029): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,W/Gmail   ( 7664): Sync started for account: account:61035162
,E/Gmail   ( 7664): Error finding the version of the Email provider.....
E/Gmail   ( 7664): android.content.pm.PackageManager$NameNotFoundException: com.google.android.email
E/Gmail   ( 7664): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
E/Gmail   ( 7664): 	at com.google.android.gm.EmailMigrationService.aU(SourceFile:1235)
E/Gmail   ( 7664): 	at com.google.android.gm.EmailMigrationService.onHandleIntent(SourceFile:187)
E/Gmail   ( 7664): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/Gmail   ( 7664): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/Gmail   ( 7664): 	at android.os.Looper.loop(Looper.java:135)
E/Gmail   ( 7664): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,W/EmailMigration( 7664): We do not support migrating this version of the Email provider.
I/Gmail   ( 7664): getAccountsCursor
V/GLSActivity( 2130): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/SQLiteLog( 7664): (283) recovered 702 frames from WAL file /data/data/com.google.android.gm/databases/mailstore.thalitester@gmail.com.db-wal
,I/Gmail   ( 7664): notifyAccountChanged
,I/Gmail   ( 7664): notifyAccountChanged
I/Gmail   ( 7664): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,I/Gmail   ( 7664): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,I/Gmail   ( 7664): calculateUnknownSyncRationalesAndPurgeInBackground: running
,I/Gmail   ( 7664): calculateUnknownSyncRationalesAndPurgeInBackground: running
,I/art     ( 1029): Explicit concurrent mark sweep GC freed 33508(1518KB) AllocSpace objects, 5(592KB) LOS objects, 33% free, 44MB/66MB, paused 3.378ms total 161.752ms
,V/GLSActivity( 2130): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Gmail   ( 7664): getAccountsCursor
,V/GLSActivity( 2130): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/Gmail   ( 7664): getAccountsCursor
,V/GLSActivity( 2130): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/Gmail   ( 7664): MainSyncRequestProto: lowestBkwdConvoId: 0, highestHandledServerOp: 5310, normalSync: true
,I/art     ( 2130): Explicit concurrent mark sweep GC freed 22694(1338KB) AllocSpace objects, 17(2MB) LOS objects, 51% free, 30MB/62MB, paused 1.877ms total 50.588ms
,W/ResourcesManager( 7664): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 7664): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 7664): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,W/System  ( 7664): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[directory "."],nativeLibraryDirectories=[/vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,I/ProviderInstaller( 7664): Installed default security provider GmsCore_OpenSSL
V/GLSActivity( 2130): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/GLSUser ( 2130): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gm, service: mail
I/GLSUser ( 2130): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> mail without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2130): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2130): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2130): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/NotificationService( 1029): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1029): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1029): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1029): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1029): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1414): onNotificationPosted
D/SmartCoverUpdateMonitor( 1414): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1414): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1414): handleNotificationPosted(true)
D/QuickCircle( 1414): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1414): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1414): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1414): post do just update job
D/LgeQuickCoverNotificationData( 1414): showAll3
D/LgeQuickCoverNotificationData( 1414): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1414): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1414): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1414): showNotificationWithSetupData: display=false
W/GLSActivity( 2130): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2130): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2130): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2130): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2130): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2130): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2130): 	at android.os.Binder.execTransact(Binder.java:446)
D/LgeQuickCoverOverlayWindow( 1414): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1414): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1414): [native noti] inex =  1
,D/LgeQuickCoverNotificationData( 1414): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1414): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1414): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1414): updateNotificationData: count=3
D/QuickStatusbarLayout( 1414): Notification difference=198
D/QuickStatusbarLayout( 1414): child = android.widget.LinearLayout{1813a4 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,I/GLSUser ( 2130): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 2130): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2130): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2130): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2130): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1029): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1029): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1029): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1029): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1029): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1414): onNotificationPosted
,D/SmartCoverUpdateMonitor( 1414): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1414): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1414): handleNotificationPosted(true)
D/QuickCircle( 1414): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1414): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1414): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1414): post do just update job
D/LgeQuickCoverNotificationData( 1414): showAll3
D/LgeQuickCoverNotificationData( 1414): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1414): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1414): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1414): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1414): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1414): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1414): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1414): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1414): [native noti] inex =  2
,W/GLSActivity( 2130): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2130): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2130): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2130): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2130): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2130): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2130): 	at android.os.Binder.execTransact(Binder.java:446)
D/LgeQuickCoverNotificationData( 1414): isNotificationForCurrentUser : true
,E/BooksAccountManager( 6498): Authentication error
E/BooksAccountManager( 6498): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6498): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6498): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6498): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6498): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6498): 	at android.os.Binder.execTransact(Binder.java:446)
,E/HttpHelper( 6498): null auth token
E/LgeQuickCoverOverlayWindow( 1414): updateNotificationData: count=3
D/QuickStatusbarLayout( 1414): Notification difference=198
D/QuickStatusbarLayout( 1414): child = android.widget.LinearLayout{1813a4 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
I/GLSUser ( 2130): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gm, service: mail
I/GLSUser ( 2130): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> mail without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2130): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2130): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2130): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1029): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,W/ApiaryClient( 6498): Error response from books API: {
W/ApiaryClient( 6498):  "error": {
W/ApiaryClient( 6498):   "errors": [
W/ApiaryClient( 6498):    {
W/ApiaryClient( 6498):     "domain": "global",
W/ApiaryClient( 6498):     "reason": "required",
W/ApiaryClient( 6498):     "message": "Login Required",
W/ApiaryClient( 6498):     "locationType": "header",
W/ApiaryClient( 6498):     "location": "Authorization"
W/ApiaryClient( 6498):    }
W/ApiaryClient( 6498):   ],
W/ApiaryClient( 6498):   "code": 401,
W/ApiaryClient( 6498):   "message": "Login Required"
W/ApiaryClient( 6498):  }
W/ApiaryClient( 6498): }
V/NotificationService( 1029): pkg=com.google.android.gms canInterrupt=false intercept=true
,W/ApiaryClient( 6498): errCount = 3: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6498): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-7869753712989766188&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6498): Headers:
W/ApiaryClient( 6498): accept-encoding: [gzip]
W/ApiaryClient( 6498): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6498): gdata-version: 2
I/NotificationServiceEx( 1029): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1029): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1029): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
W/GLSActivity( 2130): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2130): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2130): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2130): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2130): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2130): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2130): 	at android.os.Binder.execTransact(Binder.java:446)
D/LgeQuickCoverNLService( 1414): onNotificationPosted
D/SmartCoverUpdateMonitor( 1414): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1414): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1414): handleNotificationPosted(true)
D/QuickCircle( 1414): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1414): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1414): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1414): post do just update job
D/LgeQuickCoverNotificationData( 1414): showAll3
D/LgeQuickCoverNotificationData( 1414): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1414): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1414): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1414): showNotificationWithSetupData: display=false
,D/LgeQuickCoverOverlayWindow( 1414): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1414): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1414): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1414): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1414): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1414): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1414): updateNotificationData: count=3
I/Gmail   ( 7664): notifyAccountChanged
I/Gmail   ( 7664): getAccountsCursor
V/GLSActivity( 2130): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/QuickStatusbarLayout( 1414): Notification difference=198
D/QuickStatusbarLayout( 1414): child = android.widget.LinearLayout{1813a4 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
I/Gmail   ( 7664): notifyAccountChanged
,I/Gmail   ( 7664): getAccountsCursor
W/Gmail   ( 7664): Sync complete for account: account:61035162
V/GLSActivity( 2130): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/SyncManager( 1029): failed sync operation thalitester@gmail.com u0 (com.google), gmail-ls, PERIODIC, currentRunTime 1333653, reason: Periodic, SyncResult: stats [ numAuthExceptions: 1]
,D/SyncManager( 1029): not retrying sync operation because the error is a hard error: thalitester@gmail.com u0 (com.google), gmail-ls, PERIODIC, currentRunTime 1368537, reason: Periodic
,V/GLSActivity( 2130): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2130): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.syncadapters.contacts, service: cp
,I/GLSUser ( 2130): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> cp without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2130): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2130): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2130): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1029): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
V/NotificationService( 1029): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1029): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1029): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1029): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,W/GLSActivity( 2130): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2130): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2130): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2130): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2130): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2130): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2130): 	at android.os.Binder.execTransact(Binder.java:446)
D/LgeQuickCoverNLService( 1414): onNotificationPosted
,D/SmartCoverUpdateMonitor( 1414): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1414): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1414): handleNotificationPosted(true)
D/QuickCircle( 1414): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1414): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1414): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1414): post do just update job
D/LgeQuickCoverNotificationData( 1414): showAll3
D/LgeQuickCoverNotificationData( 1414): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1414): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1414): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1414): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1414): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1414): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1414): [native noti] inex =  1
D/ContactsSyncAdapter( 2130): innerSync failed
D/ContactsSyncAdapter( 2130): com.google.wireless.gdata2.client.AuthenticationException: unable to get auth token android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
D/ContactsSyncAdapter( 2130): 	at com.google.android.syncadapters.contacts.AuthInfo.getAuthToken(AuthInfo.java:45)
D/ContactsSyncAdapter( 2130): 	at com.google.android.syncadapters.contacts.ContactsSyncAdapter.innerPerformSync(ContactsSyncAdapter.java:263)
D/ContactsSyncAdapter( 2130): 	at com.google.android.syncadapters.contacts.ContactsSyncAdapter.onPerformLoggedSync(ContactsSyncAdapter.java:168)
D/ContactsSyncAdapter( 2130): 	at com.google.android.common.LoggingThreadedSyncAdapter.onPerformSync(LoggingThreadedSyncAdapter.java:33)
D/ContactsSyncAdapter( 2130): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
D/ContactsSyncAdapter( 2130): Caused by: android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
D/ContactsSyncAdapter( 2130): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
D/ContactsSyncAdapter( 2130): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
D/ContactsSyncAdapter( 2130): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
D/ContactsSyncAdapter( 2130): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
D/ContactsSyncAdapter( 2130): 	at android.os.Binder.execTransact(Binder.java:446)
D/LgeQuickCoverNotificationData( 1414): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1414): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1414): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1414): updateNotificationData: count=3
D/SyncManager( 1029): failed sync operation thalitester@gmail.com u0 (com.google), com.android.contacts, PERIODIC, currentRunTime 1333670, reason: Periodic, SyncResult: stats [ numAuthExceptions: 1]
D/SyncManager( 1029): not retrying sync operation because the error is a hard error: thalitester@gmail.com u0 (com.google), com.android.contacts, PERIODIC, currentRunTime 1461082, reason: Periodic
,D/QuickStatusbarLayout( 1414): Notification difference=198
D/QuickStatusbarLayout( 1414): child = android.widget.LinearLayout{1813a4 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,I/GLSUser ( 2130): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/reminders
,I/GLSUser ( 2130): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/reminders without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2130): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2130): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2130): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/ReminderSync( 2363): AuthError [T SyncAdapterThread-1:id=280:priority=5:group=main]
,D/SyncManager( 1029): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.gms.reminders, PERIODIC, currentRunTime 1333679, reason: Periodic, SyncResult: stats [ numAuthExceptions: 1]
,D/SyncManager( 1029): not retrying sync operation because the error is a hard error: thalitester@gmail.com u0 (com.google), com.google.android.gms.reminders, PERIODIC, currentRunTime 1367617, reason: Periodic
,I/ActivityManager( 1029): Start proc com.google.android.apps.docs for service com.google.android.apps.docs/.sync.syncadapter.DocsSyncAdapterService: pid=7720 uid=10061 gids={50061, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/DocsApplication( 7720): Installing DEX configuration.
,D/DexInstaller( 7720): Dex configuration file eager_dex_configuration.xml not found. Skipping dex installation.
,I/PackageInfoHelper( 7720): Provided clientMode=RELEASE, packageInfo=PackageInfo{a204e02 com.google.android.apps.docs}
,D/TAG     ( 7720): onCreate()
,D/CrossAppStateProvider( 7720): Initialized StateProvider with authority: com.google.android.apps.docs.statesyncer
E/BooksSync( 6498): Soft error: 
E/BooksSync( 6498): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 6498): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-7869753712989766188&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 6498): Headers:
E/BooksSync( 6498): accept-encoding: [gzip]
E/BooksSync( 6498): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 6498): gdata-version: 2
E/BooksSync( 6498): 
E/BooksSync( 6498): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 6498): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 6498): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 6498): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 6498): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 6498): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 6498): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 6498): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 6498): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 6498): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 6498): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 6498): {
E/BooksSync( 6498):  "error": {
E/BooksSync( 6498):   "errors": [
E/BooksSync( 6498):    {
E/BooksSync( 6498):     "domain": "global",
E/BooksSync( 6498):     "reason": "required",
E/BooksSync( 6498):     "message": "Login Required",
E/BooksSync( 6498):     "locationType": "header",
E/BooksSync( 6498):     "location": "Authorization"
E/BooksSync( 6498):    }
E/BooksSync( 6498):   ],
E/BooksSync( 6498):   "code": 401,
E/BooksSync( 6498):   "message": "Login Required"
E/BooksSync( 6498):  }
E/BooksSync( 6498): }
E/BooksSync( 6498): 
E/BooksSync( 6498): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 6498): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 6498): 	... 8 more
E/BooksSync( 6498): Sync error
E/BooksSync( 6498): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 6498): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-7869753712989766188&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 6498): Headers:
E/BooksSync( 6498): accept-encoding: [gzip]
E/BooksSync( 6498): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 6498): gdata-version: 2
E/BooksSync( 6498): 
E/BooksSync( 6498): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 6498): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 6498): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 6498): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 6498): 	at com.google.android.apps.books.data.MyEbooksSubcon,troller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 6498): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 6498): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 6498): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 6498): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 6498): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 6498): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 6498): {
E/BooksSync( 6498):  "error": {
E/BooksSync( 6498):   "errors": [
E/BooksSync( 6498):    {
E/BooksSync( 6498):     "domain": "global",
E/BooksSync( 6498):     "reason": "required",
E/BooksSync( 6498):     "message": "Login Required",
E/BooksSync( 6498):     "locationType": "header",
E/BooksSync( 6498):     "location": "Authorization"
E/BooksSync( 6498):    }
E/BooksSync( 6498):   ],
E/BooksSync( 6498):   "code": 401,
E/BooksSync( 6498):   "message": "Login Required"
E/BooksSync( 6498):  }
E/BooksSync( 6498): }
E/BooksSync( 6498): 
E/BooksSync( 6498): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 6498): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 6498): 	... 8 more
I/BooksSync( 6498): Finished books sync
,D/SyncManager( 1029): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 1333245, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,I/ActivityManager( 1029): Killing 6844:com.google.android.talk/u0a72 (adj 15): empty #17
,W/libprocessgroup( 1029): failed to open /acct/uid_10072/pid_6844/cgroup.procs: No such file or directory
,I/ActivityManager( 1029): Start proc com.google.android.apps.magazines for service com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.service.SyncAdapterService: pid=7737 uid=10093 gids={50093, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,E/VoldCmdListener(  279): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  279): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  279): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7737): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
,E/VoldCmdListener(  279): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  279): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  279): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7737): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
E/VoldCmdListener(  279): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  279): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  279): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7737): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
E/VoldCmdListener(  279): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  279): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  279): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7737): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
I/WebViewFactory( 7737): Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,I/LibraryLoader( 7737): Loading: webviewchromium
I/LibraryLoader( 7737): Time to load native libraries: 4 ms (timestamps 8392-8396)
,I/LibraryLoader( 7737): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 7737): Binding Chromium to main looper Looper (main, tid 1) {26c07c57}
I/LibraryLoader( 7737): Expected native library version number "",actual native library version number ""
I/chromium( 7737): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 7737): Initializing chromium process, renderers=0
,W/art     ( 7737): Attempt to remove local handle scope entry from IRT, ignoring
W/chromium( 7737): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
,I/chromium( 7737): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=38 off=46780 len=2953
I/chromium( 7737): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:39 off:229536 len:643667
V/AudioPolicyService(  327): registerClient() client 0xb1427e00, uid 10093
W/AudioManagerAndroid( 7737): Requires BLUETOOTH permission
I/Adreno-EGL( 7737): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 7737): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 7737): Build Date: 12/12/14 금
I/Adreno-EGL( 7737): Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
I/Adreno-EGL( 7737): Remote Branch: 
I/Adreno-EGL( 7737): Local Patches: 
I/Adreno-EGL( 7737): Reconstruct Branch: 
,I/NSApplication( 7737): Starting up...
,I/SyncAdapterService( 7737): Ignoring sync request for non-current account
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=7.7, 0.0, 0.0  rx=5.7 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-2026453479] gl rssi=-44 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=7.7, 0.0, 0.0  rx=5.7 bcn=0 [on:0 tx:0 rx:0 period:0] from screen [on:0 period:-2026453479] gl rssi=-44 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
I/ActivityManager( 1029): Killing 6652:com.lge.sizechangable.weather/u0a85 (adj 15): empty #17
,W/libprocessgroup( 1029): failed to open /acct/uid_10085/pid_6652/cgroup.procs: No such file or directory
,I/ActivityManager( 1029): Start proc com.android.chrome for service com.android.chrome/com.google.android.apps.chrome.sync.ChromeBrowserSyncAdapterService: pid=7794 uid=10057 gids={50057, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/art     (  353): Explicit concurrent mark sweep GC freed 707(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 191us total 10.384ms
I/art     (  353): Explicit concurrent mark sweep GC freed 7(240B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 184us total 8.805ms
,I/art     (  353): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 188us total 9.430ms
,I/art     ( 1029): Explicit concurrent mark sweep GC freed 28442(1235KB) AllocSpace objects, 7(624KB) LOS objects, 33% free, 44MB/66MB, paused 2.888ms total 136.076ms
I/art     ( 1029): WaitForGcToComplete blocked for 21.346ms for cause HeapTrim
,D/LgDataFeature( 7720): LgDataFeature() Constructor: none
D/LgDataFeature( 7720): LgDataFeature() Constructor Done, null
,D/DelayedSyncController( 7794): Delaying sync.
,I/ActivityManager( 1029): Killing 6925:com.uei.lg.quicksetsdk.maxq616/1000 (adj 15): empty #17
I/QRemote ( 6295): [RemoteControlManager.java:195:onServiceDisconnected()] oooooo start
W/System.err( 6295): android.os.DeadObjectException
,W/System.err( 6295): 	at android.os.BinderProxy.transactNative(Native Method)
,W/System.err( 6295): 	at android.os.BinderProxy.transact(Binder.java:496)
W/System.err( 6295): 	at com.uei.control.IControl.unregisterCallback(IControl.java:502)
W/System.err( 6295): 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:199)
W/System.err( 6295): 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
W/System.err( 6295): 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
W/System.err( 6295): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 6295): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 6295): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 6295): 	at android.app.ActivityThread.main(ActivityThread.java:5274)
W/System.err( 6295): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 6295): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 6295): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
W/System.err( 6295): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
E/UEI.SmartControl( 6295): IControl.unregisterCallback error: android.os.DeadObjectException
W/System.err( 6295): android.os.DeadObjectException
W/System.err( 6295): 	at android.os.BinderProxy.transactNative(Native Method)
W/System.err( 6295): 	at android.os.BinderProxy.transact(Binder.java:496)
W/System.err( 6295): 	at com.uei.control.IControl.unregisterSetupReadyCallback(IControl.java:818)
W/System.err( 6295): 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:200)
W/System.err( 6295): 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
W/System.err( 6295): 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
W/System.err( 6295): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 6295): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 6295): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 6295): 	at android.app.ActivityThread.main(ActivityThread.java:5274)
W/System.err( 6295): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 6295): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 6295): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
W/System.err( 6295): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
E/UEI.SmartControl( 6295): IControl.unregisterSetupReadyCallback error: android.os.DeadObjectException
I/QRemote ( 6295): [RemoteControlManager.java:203:onServiceDisconnected()] oooooo Control unbind before rebinding.
W/libprocessgroup( 1029): failed to open /acct/uid_1000/pid_6925/cgroup.procs: No such file or directory
W/ActivityManager( 1029): Scheduling restart of crashed service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service in 1000ms
,D/QRemote ( 6295): [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]10
I/QRemote ( 6295): [RemoteControlManager.java:157:onBindIRService()] oooooo bind
I/ActivityManager( 1029): Start proc com.uei.lg.quicksetsdk.maxq616 for service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service: pid=7819 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,D/QRemote ( 6295): [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
W/GAV2    ( 7720): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,W/BaseAppContext( 2363): Using Auth Proxy for data requests.
,W/BaseAppContext( 2363): Using Auth Proxy for data requests.
W/BaseAppContext( 2363): Using Auth Proxy for data requests.
,W/BaseAppContext( 2363): Using Auth Proxy for data requests.
,D/WifiService( 1029): acquireWifiLockLocked: WifiLock{SyncManager type=1 binder=android.os.BinderProxy@1391c220}
W/BaseAppContext( 2363): Using Auth Proxy for data requests.
,D/UEI.SmartControl( 7819): Quickset Services start...
I/UEI.SmartControl( 7819): Manufacture = LGE
D/UEI.SmartControl( 7819): Id = LGNevo
W/BaseAppContext( 2363): Using Auth Proxy for data requests.
D/UEI.SmartControl( 7819): File observer start...
,E/UEI.SmartControl( 7819): IR Port is disabled: false
D/UEI.SmartControl( 7819): Starting file observer...
D/UEI.SmartControl( 7819): Extracting JNI libs...
D/UEI.SmartControl( 7819): --- this system supports 32-bit or 64-bit only
D/libc-netbsd(  323): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  323): res_queryN name = ssl.gstatic.com, class = 1, type = 1
,I/art     ( 2130): Explicit concurrent mark sweep GC freed 15985(925KB) AllocSpace objects, 11(1584KB) LOS objects, 50% free, 30MB/62MB, paused 1.106ms total 43.548ms
W/BaseAppContext( 2363): Using Auth Proxy for data requests.
,D/libc-netbsd(  323): res_queryN name = ssl.gstatic.com succeed
,D/UEI.SmartControl( 7819): --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
D/UEI.SmartControl( 7819): --- Checking lib: libqs_armeabi-v7a.zip
D/UEI.SmartControl( 7819): --- Extracting JNI libs: libqs_armeabi-v7a.zip
I/UEI.SmartControl( 7819): --- Selecting new region: 6
I/UEI.SmartControl( 7819): Model = LG-D855
D/UEI.SmartControl( 7819): QS Service created
,I/UEI.SmartControl( 7819): Service initServices...
D/UEI.SmartControl( 7819): QS start get config
,D/UEI.SmartControl( 7819): Loading JNI Libs...
,I/GoogleHttpClient( 5181): Falling back to old http client 0 java.lang.NoSuchMethodException: <init> [class android.content.Context, class java.lang.String, boolean, boolean]
,V/GLSActivity( 2130): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/UEI.SmartControl( 7819): Supports setup maps: true
D/UEI.SmartControl( 7819): QS start statue = true Error code = 0
I/UEI.SmartControl( 7819): QS version = v2.7.10.1_RC1
I/UEI.SmartControl( 7819): QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
I/UEI.SmartControl( 7819): ### init IR Blaster...
D/serial_port( 7819): Configuring serial port
,E/UEI.SmartControl( 7819): UEIBLaster setting for 616
,I/UEI.SmartControl( 7819): Setting serial record hearder size = 2
I/UEI.SmartControl( 7819): configuring settings for MAXQ616
I/UEI.SmartControl( 7819): Get version...
I/GLSUser ( 2130): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.music, service: sj
I/GLSUser ( 2130): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> sj without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2130): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2130): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2130): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/UEI.SmartControl( 7819): serial port data available: 21
,V/NotificationService( 1029): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1029): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1029): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1029): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1029): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
W/GLSActivity( 2130): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2130): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2130): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2130): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2130): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2130): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2130): 	at android.os.Binder.execTransact(Binder.java:446)
D/LgeQuickCoverNLService( 1414): onNotificationPosted
D/SmartCoverUpdateMonitor( 1414): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1414): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1414): handleNotificationPosted(true)
D/QuickCircle( 1414): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1414): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1414): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1414): post do just update job
D/LgeQuickCoverNotificationData( 1414): showAll3
D/LgeQuickCoverNotificationData( 1414): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1414): showAll() ID : 1,0|com.google.android.gms|1|null|10005
W/MusicSyncAdapter( 5181): Sync failed due to an authentication issue.
D/LgeQuickCoverNotificationData( 1414): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1414): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1414): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1414): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1414): [native noti] inex =  1
,D/LgeQuickCoverNotificationData( 1414): isNotificationForCurrentUser : true
D/UEI.SmartControl( 7819): MAXQ616 A2-X4 software.
I/UEI.SmartControl( 7819): IR Blaster version: 256702256704300002
I/UEI.SmartControl( 7819): QS saving settings...
D/LgeQuickCoverOverlayWindow( 1414): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1414): isNotificationForCurrentUser : true
D/UEI.SmartControl( 7819): IR Blaster version: 25672567
E/LgeQuickCoverOverlayWindow( 1414): updateNotificationData: count=3
I/GLSUser ( 2130): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.docs, service: oauth2: https://www.googleapis.com/auth/drive
I/GLSUser ( 2130): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2: https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2130): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2130): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
D/QuickStatusbarLayout( 1414): Notification difference=198
D/QuickStatusbarLayout( 1414): child = android.widget.LinearLayout{1813a4 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
D/SyncManager( 1029): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.music.MusicContent, PERIODIC, currentRunTime 1333702, reason: Periodic, SyncResult: stats [ numAuthExceptions: 1]
V/GLSActivity( 2130): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/SyncManager( 1029): not retrying sync operation because the error is a hard error: thalitester@gmail.com u0 (com.google), com.google.android.music.MusicContent, PERIODIC, currentRunTime 1372412, reason: Periodic
D/UEI.SmartControl( 7819): serial port data available: 4
E/VoldCmdListener(  279): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  279): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  279): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 5181): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
,E/VoldCmdListener(  279): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  279): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  279): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 5181): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
E/VoldCmdListener(  279): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  279): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  279): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 5181): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
E/VoldCmdListener(  279): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  279): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  279): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 5181): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
W/ArtDownloadService( 5181): Setting cache size 0
I/UEI.SmartControl( 7819): Device manager: loading config....
D/UEI.SmartControl( 7819): ----------- loading internal config...
V/NotificationService( 1029): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
V/NotificationService( 1029): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1029): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1029): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
,D/NotificationServiceEx( 1029): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1414): onNotificationPosted
D/SmartCoverUpdateMonitor( 1414): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1414): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1414): handleNotificationPosted(true)
D/QuickCircle( 1414): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1414): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1414): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1414): post do just update job
D/LgeQuickCoverNotificationData( 1414): showAll3
D/LgeQuickCoverNotificationData( 1414): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1414): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1414): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1414): showNotificationWithSetupData: display=false
W/ContextImpl( 7819): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
D/LgeQuickCoverOverlayWindow( 1414): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1414): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1414): [native noti] inex =  1
E/UEI.SmartControl( 7819): Services init done
D/UEI.SmartControl( 7819): QS Service init finished
D/LgeQuickCoverNotificationData( 1414): isNotificationForCurrentUser : true
,D/UEI.SmartControl( 7819): QS Service version name: 2.1.91
D/LgeQuickCoverOverlayWindow( 1414): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1414): isNotificationForCurrentUser : true
D/UEI.SmartControl( 7819): QS Service version code: 201091
E/LgeQuickCoverOverlayWindow( 1414): updateNotificationData: count=3
D/UEI.SmartControl( 7819): Service requested: Control
E/UEI.SmartControl( 7819): Loading SETTINGS...
I/QRemote ( 6295): [RemoteControlManager.java:183:onServiceConnected()] oooooo start
I/UEI.SmartControl( 7819): ------ IControl API: 11
I/ActivityManager( 1029): Killing 6295:com.lge.qremote/u0a112 (adj 15): empty #17
I/UEI.SmartControl( 7819): Registering callback...
W/ArtDownloadService( 5181): Setting cache size 0
W/GLSActivity( 2130): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2130): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2130): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2130): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2130): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2130): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2130): 	at android.os.Binder.execTransact(Binder.java:446)
D/UEI.SmartControl( 7819): -- Open brand translation xml: brands_translations_ko
,D/QuickStatusbarLayout( 1414): Notification difference=198
D/QuickStatusbarLayout( 1414): child = android.widget.LinearLayout{1813a4 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
I/UEI.SmartControl( 7819): Notify AllClients services are ready: 0
D/UEI.SmartControl( 7819): -----service ready thread exits
,D/UEI.SmartControl( 7819): Internal service binding...
,W/PsynchoHelperImpl( 7720): Error fetching or saving configuration
W/PsynchoHelperImpl( 7720): java.io.IOException: android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
W/PsynchoHelperImpl( 7720): 	at Op.a(ApiaryPsynchoConfigurationAccessor.java:145)
W/PsynchoHelperImpl( 7720): 	at Op.a(ApiaryPsynchoConfigurationAccessor.java:215)
W/PsynchoHelperImpl( 7720): 	at OQ.a(PsynchoHelperImpl.java:60)
W/PsynchoHelperImpl( 7720): 	at agr.a(DriveSpecificSyncManager.java:27)
W/PsynchoHelperImpl( 7720): 	at agO.a(LegacySyncManager.java:678)
W/PsynchoHelperImpl( 7720): 	at agO.b(LegacySyncManager.java:582)
W/PsynchoHelperImpl( 7720): 	at agO.a(LegacySyncManager.java:467)
W/PsynchoHelperImpl( 7720): 	at agO.a(LegacySyncManager.java:97)
W/PsynchoHelperImpl( 7720): 	at agQ.run(LegacySyncManager.java:419)
W/PsynchoHelperImpl( 7720): 	at ami.a(NetworkUtilitiesImpl.java:31)
W/PsynchoHelperImpl( 7720): 	at agP.run(LegacySyncManager.java:416)
W/PsynchoHelperImpl( 7720): Caused by: android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
W/PsynchoHelperImpl( 7720): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
W/PsynchoHelperImpl( 7720): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
W/PsynchoHelperImpl( 7720): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
W/PsynchoHelperImpl( 7720): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
W/PsynchoHelperImpl( 7720): 	at android.os.Binder.execTransact(Binder.java:446)
,W/libprocessgroup( 1029): failed to open /acct/uid_10112/pid_6295/cgroup.procs: No such file or directory
I/ActivityManager( 1029): Killing 6973:com.lge.appbox.client/u0a11 (adj 15): empty #17
,I/MusicLeanback( 5181): Conditions not met for autocaching.
I/MusicLeanback( 5181): Stop autocaching.
W/libprocessgroup( 1029): failed to open /acct/uid_10011/pid_6973/cgroup.procs: No such file or directory
,V/GLSActivity( 2130): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/ActivityManager( 1029): Start proc com.google.android.videos for service com.google.android.videos/.store.SyncService: pid=7875 uid=10103 gids={50103, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,D/WearableService( 7160): callingUid 10005, callindPid: 7160
I/GLSUser ( 2130): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.docs, service: writely
I/GLSUser ( 2130): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> writely without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2130): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2130): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2130): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/WearableClient( 5181): WearableClientImpl.onPostInitHandler: done
,D/WearableClient( 5181): WearableClientImpl.onPostInitHandler: done
E/GmsUtils( 5181): Failed to connect to Google API client: ConnectionResult{statusCode=unknown status code 16, resolution=null}
E/VoldCmdListener(  279): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  279): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/cache/
W/Vold    (  279): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 5181): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/cache
V/NotificationService( 1029): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1029): pkg=com.google.android.gms canInterrupt=false intercept=true
,I/NotificationServiceEx( 1029): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1029): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1029): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
E/VoldCmdListener(  279): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  279): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/cache/
W/Vold    (  279): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 5181): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/cache
D/LgeQuickCoverNLService( 1414): onNotificationPosted
D/SmartCoverUpdateMonitor( 1414): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1414): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1414): handleNotificationPosted(true)
D/QuickCircle( 1414): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1414): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1414): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1414): post do just update job
D/LgeQuickCoverNotificationData( 1414): showAll3
D/LgeQuickCoverNotificationData( 1414): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1414): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1414): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1414): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1414): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1414): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1414): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1414): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1414): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1414): isNotificationForCurrentUser : true
,E/LgeQuickCoverOverlayWindow( 1414): updateNotificationData: count=3
W/GLSActivity( 2130): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2130): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2130): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2130): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2130): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2130): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2130): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpIssuerBase( 7720): Attempt to consume entity of HttpIssuer when no request is executing.
E/HttpIssuerBase( 7720): Attempt to close HttpIssuer when no request is executing.
E/HttpIssuerBase( 7720): java.io.IOException
E/HttpIssuerBase( 7720): 	at TG.b(HttpIssuerBase.java:188)
E/HttpIssuerBase( 7720): 	at Tj.b(DefaultAuthenticatedHttpIssuer.java:151)
E/HttpIssuerBase( 7720): 	at afE.a(AccountMetadataUpdater.java:227)
E/HttpIssuerBase( 7720): 	at afE.a(AccountMetadataUpdater.java:140)
E/HttpIssuerBase( 7720): 	at agO.a(LegacySyncManager.java:828)
E/HttpIssuerBase( 7720): 	at agO.b(LegacySyncManager.java:588)
E/HttpIssuerBase( 7720): 	at agO.a(LegacySyncManager.java:467)
E/HttpIssuerBase( 7720): 	at agO.a(LegacySyncManager.java:97)
E/HttpIssuerBase( 7720): 	at agQ.run(LegacySyncManager.java:419)
E/HttpIssuerBase( 7720): 	at ami.a(NetworkUtilitiesImpl.java:31)
E/HttpIssuerBase( 7720): 	at agP.run(LegacySyncManager.java:416)
E/SyncManager( 7720): AuthenticatorException
E/SyncManager( 7720): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/SyncManager( 7720): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/SyncManager( 7720): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/SyncManager( 7720): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/SyncManager( 7720): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/SyncManager( 7720): 	at android.os.Binder.execTransact(Binder.java:446)
W/GAV2    ( 7720): SyncManager-thalitester@gmail.com: dispatch call queued.  Need to call GAServiceManager.getInstance().initialize().
D/WifiService( 1029): releaseWifiLockLocked: WifiLock{SyncManager type=1 binder=android.os.BinderProxy@1391c220}
W/ResourcesManager( 7875): Asset path '/system/framework/com.google.widevine.software.drm.jar' does not exist or contains no resources.
D/QuickStatusbarLayout( 1414): Notification difference=198
D/QuickStatusbarLayout( 1414): child = android.widget.LinearLayout{1813a4 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,D/SyncManager( 1029): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.docs, PERIODIC, currentRunTime 1333684, reason: Periodic, SyncResult: stats [ numAuthExceptions: 1]
D/SyncManager( 1029): not retrying sync operation because the error is a hard error: thalitester@gmail.com u0 (com.google), com.google.android.apps.docs, PERIODIC, currentRunTime 1370945, reason: Periodic
,E/Auth.Api.Credentials( 2363): [CredentialSyncAdapter] Unknown sync event.
,D/LgDataFeature( 7875): LgDataFeature() Constructor: none
D/LgDataFeature( 7875): LgDataFeature() Constructor Done, null
,D/PlayMovies( 7875): PersistentCache.cleanup:103 Cache is below limit, no need to shrink: [size=0, limit=5242880]
,D/PlayMovies( 7875): TransferService.onCreate:52 creating transfer service
,I/GAV2    ( 7664): Thread[GAThread,5,main]: No campaign data found.
W/AudioCapabilities( 7875): Unsupported mime audio/evrc
W/AudioCapabilities( 7875): Unsupported mime audio/qcelp
E/VoldCmdListener(  279): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  279): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.videos/files/Movies/
W/Vold    (  279): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7875): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.videos/files/Movies
,W/VideoCapabilities( 7875): Unrecognized profile 2130706433 for video/avc
,W/AudioCapabilities( 7875): Unsupported mime audio/amr-wb-plus
W/AudioCapabilities( 7875): Unsupported mime audio/qcelp
W/AudioCapabilities( 7875): Unsupported mime audio/evrc
V/AlarmManager( 1029): ELAPSED_WAKEUP set : Alarm{32f14927 type 2 when 1192091 com.google.android.gms} when 1192091
,W/VideoCapabilities( 7875): Unsupported mime video/x-ms-wmv
,I/GLSUser ( 2130): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.videos, service: oauth2:https://www.googleapis.com/auth/android_video https://www.googleapis.com/auth/youtube https://www.googleapis.com/auth/pos
W/VideoCapabilities( 7875): Unsupported mime video/divx
I/GLSUser ( 2130): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/android_video https://www.googleapis.com/auth/youtube https://www.googleapis.com/auth/pos without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2130): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2130): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
W/VideoCapabilities( 7875): Unsupported mime video/divx311
W/VideoCapabilities( 7875): Unsupported mime video/divx4
V/GLSActivity( 2130): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/VideoCapabilities( 7875): Unsupported mime video/mp4v-esdp
,W/ResourcesManager( 2363): Asset path '/system/framework/com.google.widevine.software.drm.jar' does not exist or contains no resources.
,I/VideoCapabilities( 7875): Unsupported profile 4 for video/mp4v-es
I/GCM     ( 2363): Message from null null
E/GCM     ( 2363): Dropping message from null
W/AudioCapabilities( 7875): Unsupported mime audio/eac3
W/AudioCapabilities( 7875): Unsupported mime audio/ac3
W/AudioCapabilities( 7875): Unsupported mime audio/g726
,D/GCM     ( 2130): Message class com.google.f.a.a.i
W/AudioCapabilities( 7875): Unsupported mime audio/wma-voice
W/AudioCapabilities( 7875): Unsupported mime audio/x-ms-wma
,W/AudioCapabilities( 7875): Unsupported mime audio/adpcm
W/VideoCapabilities( 7875): Unsupported mime video/theora
,W/VideoCapabilities( 7875): Unsupported mime video/mjpg
V/NotificationService( 1029): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1029): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1029): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1029): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1029): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1414): onNotificationPosted
D/SmartCoverUpdateMonitor( 1414): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1414): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1414): handleNotificationPosted(true)
D/QuickCircle( 1414): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1414): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1414): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1414): post do just update job
D/LgeQuickCoverNotificationData( 1414): showAll3
D/LgeQuickCoverNotificationData( 1414): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1414): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1414): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1414): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1414): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1414): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1414): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1414): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1414): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1414): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1414): updateNotificationData: count=3
E/PlayMovies( 7875): GmsAccountManagerWrapper.blockingGetAuthTokenInternal:100 Cannot get user auth
E/PlayMovies( 7875): com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/PlayMovies( 7875): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/PlayMovies( 7875): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/PlayMovies( 7875): 	at com.google.android.videos.accounts.GmsAccountManagerWrapper.blockingGetAuthTokenInternal(GmsAccountManagerWrapper.java:85)
E/PlayMovies( 7875): 	at com.google.android.videos.accounts.AccountManagerWrapper.blockingGetAuthToken(AccountManagerWrapper.java:186)
E/PlayMovies( 7875): 	at com.google.android.videos.accounts.AccountManagerWrapper.blockingAuthenticate(AccountManagerWrapper.java:162)
E/PlayMovies( 7875): 	at com.google.android.videos.store.SyncService$SyncAdapter.onPerformSync(SyncService.java:225)
E/PlayMovies( 7875): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
D/SyncManager( 1029): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.videos.sync, PERIODIC, currentRunTime 1333707, reason: Periodic, SyncResult: stats [ numAuthExceptions: 1]
,D/SyncManager( 1029): not retrying sync operation because the error is a hard error: thalitester@gmail.com u0 (com.google), com.google.android.videos.sync, PERIODIC, currentRunTime 1373241, reason: Periodic
I/ActivityManager( 1029): Killing 7010:com.android.contacts/u0a19 (adj 15): empty #17
D/QuickStatusbarLayout( 1414): Notification difference=198
D/QuickStatusbarLayout( 1414): child = android.widget.LinearLayout{1813a4 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
W/libprocessgroup( 1029): failed to open /acct/uid_10019/pid_7010/cgroup.procs: No such file or directory
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=6.3, 0.0, 0.0  rx=4.3 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-2026450471] gl rssi=-44 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=6.3, 0.0, 0.0  rx=4.3 bcn=0 [on:0 tx:0 rx:0 period:11] from screen [on:0 period:-2026450460] gl rssi=-44 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
I/GAV4    ( 7737): Thread[GAThread,5,main]: No campaign data found.
,I/GAV2    ( 7720): Thread[GAThread,5,main]: No campaign data found.
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=13.2, 0.0, 0.0  rx=10.2 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:-2026447437] gl rssi=-44 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=13.2, 0.0, 0.0  rx=10.2 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-2026447434] gl rssi=-44 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,D/UEI.SmartControl( 7819): Internal timer expired: 1
,D/UEI.SmartControl( 7819): unbind internal service
D/UEI.SmartControl( 7819): Service.onUnbind: IControl
,D/UEI.SmartControl( 7819): Service.onDestroy
D/UEI.SmartControl( 7819): Lock is in USE false
D/UEI.SmartControl( 7819): unbind internal service
W/System.err( 7819): java.lang.IllegalArgumentException: Service not registered: com.uei.control.g@f00f268
W/System.err( 7819): 	at android.app.LoadedApk.forgetServiceDispatcher(LoadedApk.java:1119)
W/System.err( 7819): 	at android.app.ContextImpl.unbindService(ContextImpl.java:1873)
W/System.err( 7819): 	at android.content.ContextWrapper.unbindService(ContextWrapper.java:550)
W/System.err( 7819): 	at com.uei.control.Service.c(Unknown Source)
W/System.err( 7819): 	at com.uei.control.Service.onDestroy(Unknown Source)
W/System.err( 7819): 	at android.app.ActivityThread.handleStopService(ActivityThread.java:2901)
W/System.err( 7819): 	at android.app.ActivityThread.access$2200(ActivityThread.java:148)
W/System.err( 7819): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1386)
W/System.err( 7819): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 7819): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 7819): 	at android.app.ActivityThread.main(ActivityThread.java:5274)
W/System.err( 7819): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 7819): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 7819): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
W/System.err( 7819): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
E/UEI.SmartControl( 7819): java.lang.IllegalArgumentException: Service not registered: com.uei.control.g@f00f268
D/serial_port( 7819): close(fd = 25)
I/UEI.SmartControl( 7819): Serial port is closed.
I/UEI.SmartControl( 7819): Serial port is closed.
D/UEI.SmartControl( 7819): Blaster closed
D/UEI.SmartControl( 7819): Shut down QS...
D/UEI.SmartControl( 7819): Stopping QS lib
D/UEI.SmartControl( 7819): QS lib stop result = true
,D/UEI.SmartControl( 7819): Stopped QS lib
D/UEI.SmartControl( 7819): Stopped file observer...
D/UEI.SmartControl( 7819): QS shutdown complete
I/ActivityManager( 1029): Killing 7052:com.lge.lockscreensettings/u0a80 (adj 15): empty #17
,W/libprocessgroup( 1029): failed to open /acct/uid_10080/pid_7052/cgroup.procs: No such file or directory
,D/sensors_hal_Time( 1029): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1029): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1029): tsOffsetIs: Apps: 1346445908344; DSPS: 44261073; Offset : -4305893838
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=7.1, 0.0, 0.0  rx=5.6 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-2026444407] gl rssi=-44 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=7.1, 0.0, 0.0  rx=5.6 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-2026444404] gl rssi=-44 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=3.5, 0.0, 0.0  rx=2.8 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-2026441377] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=3.5, 0.0, 0.0  rx=2.8 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-2026441374] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,I/[SystemUI]QPairHandler( 1462): onReceive = android.intent.action.PACKAGE_CHANGED
,I/InputReader( 1029): Reconfiguring input devices.  changes=0x00000010
,I/ActivityManager( 1029): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.manager.PreloadListManagerHelper: pid=7951 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,I/[LGHome]EVENT( 2086): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.videos flg=0x4000010 (has extras) }
,I/[SystemUI]QSlideListController( 1462): onReceive = android.intent.action.PACKAGE_CHANGED
,D/administrator( 1029): Handling package changes for user 0
I/[SystemUI]AppWidgetPanel(QRemoteWidgetPanel)( 1462): onReceive = android.intent.action.PACKAGE_CHANGED, packageName : com.google.android.videos
,I/[LGHome]Launcher( 2086): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,I/NotificationService( 1029): action=android.intent.action.PACKAGE_CHANGED queryReplace=false
D/BackupManagerService( 1029): Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.videos flg=0x4000010 (has extras) }
,I/art     ( 1029): Explicit concurrent mark sweep GC freed 36596(1733KB) AllocSpace objects, 9(656KB) LOS objects, 33% free, 44MB/67MB, paused 3.137ms total 139.889ms
,I/AppUp4:AppBoxCP( 7951): onCreate
W/AppUp4:DB( 7951):  [AppBoxDatabaseHelper] construct
,I/AppUp4:DB( 7951):  setFingerPrint start
I/AppUp4:DB( 7951):  newfinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys SDK version = 21
I/AppUp4:DB( 7951):  beforefinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys
I/AppUp4:DB( 7951):  SDK version = 21
I/AppUp4:DB( 7951):  beforefinger == newfinger no write in DB
D/AppUp4:AppBoxApplication( 7951): AppBoxApplication onCreate()
I/AppUp4:CustModeStarterReceiver( 7951): onReceive
,D/LgDataFeature( 7951): LgDataFeature() Constructor: none
,D/LgDataFeature( 7951): LgDataFeature() Constructor Done, null
,D/AppUp4:CustFacade( 7951): Context : android.app.ReceiverRestrictedContext@201ec749
D/AppUp4:CustFacade( 7951): isCustomizationCompleted : false
D/AppUp4:CustFacade( 7951): isPhone : true
D/AppUp4:CustModeStarterReceiver( 7951): begin check event
I/AppUp4:CustModeStarterReceiver( 7951): Event For Nothing, skip.
W/ResourcesManager( 1029): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourceType( 1029): Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
I/ActivityManager( 1029): Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=7989 uid=10019 gids={50019, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
I/ActivityManager( 1029): Killing 7125:com.google.android.gms:car/u0a5 (adj 15): empty #17
,W/libprocessgroup( 1029): failed to open /acct/uid_10005/pid_7125/cgroup.procs: No such file or directory
,I/[LGHome]EVENT( 2086): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
,W/ResourcesManager( 7989): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 7989): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 7989): Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
W/ResourcesManager( 7989): Asset path '/system/framework/lghiddenlibs.jar' does not exist or contains no resources.
W/ResourcesManager( 7989): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
I/SystemConfig( 7989): BUILD Country: EU
,I/SystemConfig( 7989): BUILD Operator: OPEN
I/ActivityManager( 1029): Killing 7082:com.android.vending/u0a44 (adj 15): empty #17
,W/libprocessgroup( 1029): failed to open /acct/uid_10044/pid_7082/cgroup.procs: No such file or directory
,I/SystemConfig( 7989): pm.hasSystemFeature(com.lge.ims.rcs) = false
I/SystemConfig( 7989): existFile = false
I/SystemConfig( 7989): canReadFile = false
I/SystemConfig( 7989): systemFeature RCS result false
D/SystemConfig( 7989): refreshRcsSupport() :false
I/UpdateIcingCorporaServi( 4193): Updating corpora: APPS=com.google.android.videos, CONTACTS=MAYBE
,V/SIM_STK ( 1029): Menu title from STK is T-Mobile
,I/ActivityManager( 1029): Start proc com.lge.lockscreensettings for broadcast com.lge.lockscreensettings/.PackageIntentReceiver: pid=8015 uid=10080 gids={50080, 9997, 1028, 1015} abi=armeabi-v7a
,I/UpdateIcingCorporaServi( 4193): UpdateCorporaTask done [took 121 ms] updated apps [took 121 ms] 
,I/LockScreenSettings( 8015): Wallpaper base directory = /data/data/com.lge.lockscreensettings/files/
,D/LockScreenSettings( 8015): Quick window widget present in DB = com.lge.clock.quickcover.QuickCoverSettingActivity  true
D/LockScreenSettings( 8015): Quick window widget present in DB = com.lge.camera.app.QuickWindowCameraActivity  true
D/LockScreenSettings( 8015): Quick window widget present in DB = com.android.contacts.activities.QuickCircleActivity  true
D/LockScreenSettings( 8015): Quick window widget present in DB = com.android.mms.quickcover.QuickCoverActivity  true
D/LockScreenSettings( 8015): Quick window widget present in DB = com.lge.music.MusicQuickCircle  true
D/LockScreenSettings( 8015): Quick window widget present in DB = com.lge.lifetracker.QuickCover  true
,I/ActivityManager( 1029): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=8039 uid=10044 gids={50044, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager( 1029): Killing 6774:com.lge.clock/u0a10 (adj 15): empty #17
,W/libprocessgroup( 1029): failed to open /acct/uid_10010/pid_6774/cgroup.procs: No such file or directory
,D/Finsky  ( 8039): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,D/LgDataFeature( 8039): LgDataFeature() Constructor: none
,D/LgDataFeature( 8039): LgDataFeature() Constructor Done, null
,D/Finsky  ( 8039): [1] DailyHygiene.goMakeHygieneIfDirty: Dirty, need more hygiene.
,I/ActivityManager( 1029): Start proc com.google.android.gms:car for service com.google.android.gms/.car.CarService: pid=8085 uid=10005 gids={50005, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
,W/Settings( 8039): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
W/Settings( 8039): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/ResourcesManager( 8085): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 8085): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/DownloadManager( 3299): starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3299): created cursor android.database.sqlite.SQLiteCursor@306aba9d on behalf of 8039
I/MultiDex( 8085): VM with version 2.1.0 has multidex support
I/MultiDex( 8085): install
I/MultiDex( 8085): VM has multidex support, MultiDex support library is disabled.
,D/Finsky  ( 8039): [1] 2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 8039): [1] 2.run: Finished loading 1 libraries.
D/Finsky  ( 8039): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,V/JNIHelp ( 8085): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,D/Finsky  ( 8039): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
D/PackageBroadcastService( 2363): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.videos
I/PeopleContactsSync( 2363): CP2 sync disabled
,I/ActivityManager( 1029): Killing 7632:com.android.providers.calendar/u0a14 (adj 15): empty #17
W/ActivityThread( 8085): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 8085): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@65eecd1: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 8085): Installed default security provider GmsCore_OpenSSL
,W/libprocessgroup( 1029): failed to open /acct/uid_10014/pid_7632/cgroup.procs: No such file or directory
,D/GCM     ( 2130): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,D/AuthorizationBluetoothService( 2130): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,V/GmsCoreStatsServiceLauncher( 2363): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
D/WearableService( 7160): callingUid 10005, callindPid: 7160
,E/MDM     ( 1836): [97] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,D/LocationInitializer( 2363): Restart initialization of location
,V/Finsky  ( 8039): [1] GearheadStateMonitor.onReady: sIsProjecting:false
,V/AlarmManager( 1029): RTC_WAKEUP set : Alarm{f284289 type 0 when 1449672507410 com.android.vending} when 1449672507410
,D/Finsky  ( 8039): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
V/GLSActivity( 2130): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2130): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 2130): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2130): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2130): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2130): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/Finsky  ( 8039): [1] 1.onErrorResponse: Unable to preload experiments: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,V/GLSActivity( 2130): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2130): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 2130): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2130): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2130): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2130): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/GLSActivity( 2130): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2130): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 2130): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2130): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2130): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=2.8, 0.0, 0.0  rx=1.9 bcn=0 [on:0 tx:0 rx:0 period:3000] from screen [on:0 period:-2026438349] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=2.8, 0.0, 0.0  rx=1.9 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-2026438348] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
V/GLSActivity( 2130): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/Finsky  ( 8039): [1] LibraryUpdateListener.onErrorResponse: Library replication failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,V/SIM_STK ( 1029): Menu title from STK is T-Mobile
,V/GLSActivity( 2130): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2130): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 2130): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2130): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2130): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2130): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/Finsky  ( 8039): [1] 2.onErrorResponse: Update check failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,D/Finsky  ( 8039): [1] DailyHygiene.logDeviceFeaturesAndContinue: Logging device features
D/Finsky  ( 8039): [1] DailyHygiene.flushEventLogsAndContinue: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 8039): [1] DailyHygiene.reschedule: Scheduling new run in 285 minutes (failures=4)
,D/DeviceConnectionService( 1836): client connected with version: 7571000
,I/art     ( 1836): Explicit concurrent mark sweep GC freed 16559(973KB) AllocSpace objects, 6(96KB) LOS objects, 50% free, 31MB/63MB, paused 2.079ms total 83.394ms
,E/DataBuffer( 1836): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@31159432)
,E/DataBuffer( 1836): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@a038583)
E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=3.9, 0.0, 0.0  rx=1.4 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-2026435336] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=3.9, 0.0, 0.0  rx=1.4 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-2026435333] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,I/ActivityManager( 1029): Killing 7607:com.google.android.syncadapters.calendar/u0a69 (adj 15): empty #17
,W/libprocessgroup( 1029): failed to open /acct/uid_10069/pid_7607/cgroup.procs: No such file or directory
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=2.4, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-2026432307] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=2.4, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-2026432304] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=2.2, 0.0, 0.0  rx=0.9 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-2026429279] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=2.2, 0.0, 0.0  rx=0.9 bcn=0 [on:0 tx:0 rx:0 period:4] from screen [on:0 period:-2026429275] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,V/AlarmManager( 1029): ELAPSED_WAKEUP set : Alarm{2dc57520 type 2 when 1363754 android} when 1363754
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=1.6, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-2026426247] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=1.6, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-2026426244] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,D/sensors_hal_Time( 1029): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1029): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1029): tsOffsetIs: Apps: 1366448105003; DSPS: 44916505; Offset : -4305894654
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=1.8, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-2026423227] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=1.8, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:4] from screen [on:0 period:-2026423223] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,I/art     ( 2130): Explicit concurrent mark sweep GC freed 22365(1283KB) AllocSpace objects, 11(1584KB) LOS objects, 50% free, 30MB/62MB, paused 2.348ms total 60.481ms
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=1.4, 0.0, 0.0  rx=0.9 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:-2026420214] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=1.4, 0.0, 0.0  rx=0.9 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-2026420211] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-2026417187] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:4] from screen [on:0 period:-2026417183] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,V/AlarmManager( 1029): RTC_WAKEUP set : Alarm{13ba0c4d type 0 when 1449672522729 com.android.vending} when 1449672522729
,V/SIM_STK ( 1029): Menu title from STK is T-Mobile
,V/GLSActivity( 2130): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2130): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 2130): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2130): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2130): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2130): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 8039): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 8039): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 8039): [1] 5.onFinished: Scheduling replication attempt 1.
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.9, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-2026414162] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.9, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-2026414152] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-2026411131] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:11] from screen [on:0 period:-2026411120] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=1.2, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-2026408098] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=1.2, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-2026408095] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,I/[SystemUI]TimeTickManager( 1462): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1462): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1462): called onTimeUpdated()
I/[SystemUI]Clock( 1462): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1462): called onTimeUpdated()
I/[SystemUI]DateView( 1462): called onTimeUpdated()
I/[SystemUI]DateView( 1462): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1462): handleTimeUpdate
D/sensors_hal_Time( 1029): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1029): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1029): tsOffsetIs: Apps: 1386452876558; DSPS: 45572022; Offset : -4305913968
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=1.1, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:-2026405074] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=1.1, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-2026405071] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.6, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-2026402046] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.6, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-2026402043] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-2026399020] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:11] from screen [on:0 period:-2026399009] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.9, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-2026395986] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.9, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-2026395983] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,D/PowerManagerServiceEx( 1029): acquireWakeLockInternal: lock=518109269, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1029
,V/AlarmManager( 1029): RTC_WAKEUP set : Alarm{240f5a14 type 0 when 1449672549766 com.android.vending} when 1449672549766
,D/[Concierge]Service( 2608): onStartCommand(). Type : 9
,D/PowerManagerServiceEx( 1029): releaseWakeLockInternal: lock=518109269 [*alarm*], flags=0x0
,V/SIM_STK ( 1029): Menu title from STK is T-Mobile
,V/GLSActivity( 2130): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2130): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 2130): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2130): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2130): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2130): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 8039): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 8039): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 8039): [1] 5.onFinished: Scheduling replication attempt 2.
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.9, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-2026392955] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.9, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-2026392952] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,V/AlarmManager( 1029): ELAPSED_WAKEUP set : Alarm{234756d6 type 2 when 1399394 android} when 1399394
,I/art     ( 1029): Explicit concurrent mark sweep GC freed 41140(1823KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 44MB/67MB, paused 3.429ms total 167.991ms
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=1.0, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-2026389934] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=1.0, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:11] from screen [on:0 period:-2026389923] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-2026386902] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-2026386892] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
D/sensors_hal_Time( 1029): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1029): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1029): tsOffsetIs: Apps: 1406455016863; DSPS: 46227452; Offset : -4305910206
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-2026383872] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-2026383862] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.9, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-2026380836] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.9, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-2026380833] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.9, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-2026377813] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.9, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-2026377810] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=1.0, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3000] from screen [on:0 period:-2026374792] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=1.0, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:11] from screen [on:0 period:-2026374781] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:-2026371758] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-2026371748] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-2026368732] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-2026368722] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-2026365701] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:11] from screen [on:0 period:-2026365690] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
D/sensors_hal_Time( 1029): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1029): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1029): tsOffsetIs: Apps: 1426456921594; DSPS: 46882874; Offset : -4305897564
,V/AlarmManager( 1029): RTC_WAKEUP set : Alarm{12ed4cb0 type 0 when 1449672571714 com.android.vending} when 1449672571714
,V/SIM_STK ( 1029): Menu title from STK is T-Mobile
,V/GLSActivity( 2130): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2130): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 2130): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2130): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2130): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2130): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/Finsky  ( 8039): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 8039): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 8039): [1] 5.onFinished: Scheduling replication attempt 3.
E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:2999] from screen [on:0 period:-2026362672] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:0] from screen [on:0 period:-2026362672] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,V/AlarmManager( 1029): ELAPSED_WAKEUP set : Alarm{e7dd012 type 2 when 1429471 android} when 1429471
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-2026359661] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-2026359651] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-2026356629] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-2026356626] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-2026353601] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:9] from screen [on:0 period:-2026353592] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-2026350567] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-2026350564] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-2026347541] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-2026347531] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
I/[SystemUI]TimeTickManager( 1462): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1462): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1462): called onTimeUpdated()
I/[SystemUI]Clock( 1462): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1462): called onTimeUpdated()
I/[SystemUI]DateView( 1462): called onTimeUpdated()
I/[SystemUI]DateView( 1462): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1462): handleTimeUpdate
D/sensors_hal_Time( 1029): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1029): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1029): tsOffsetIs: Apps: 1446458709659; DSPS: 47538293; Offset : -4305910088
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-2026344517] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-2026344514] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-2026341488] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-2026341485] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-2026338458] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-2026338455] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-2026335427] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-2026335424] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,D/PowerManagerServiceEx( 1029): acquireWakeLockInternal: lock=518109269, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1029
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-2026332406] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:4] from screen [on:0 period:-2026332402] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
V/AlarmManager( 1029): RTC_WAKEUP set : Alarm{40541e0 type 0 when 1449672603346 com.android.vending} when 1449672603346
D/[Concierge]Service( 2608): onStartCommand(). Type : 9
,D/PowerManagerServiceEx( 1029): releaseWakeLockInternal: lock=518109269 [*alarm*], flags=0x0
,V/SIM_STK ( 1029): Menu title from STK is T-Mobile
,V/GLSActivity( 2130): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2130): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 2130): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2130): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2130): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2130): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/Finsky  ( 8039): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 8039): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 8039): [1] 5.onFinished: Scheduling replication attempt 4.
E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:-2026329386] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-2026329383] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-2026326357] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:4] from screen [on:0 period:-2026326353] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,D/sensors_hal_Time( 1029): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1029): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1029): tsOffsetIs: Apps: 1466460919340; DSPS: 48193725; Offset : -4305897752
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-2026323331] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:9] from screen [on:0 period:-2026323322] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-2026320300] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:11] from screen [on:0 period:-2026320289] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-2026317270] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:11] from screen [on:0 period:-2026317259] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-2026314238] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-2026314235] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-2026311208] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-2026311205] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-2026308176] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-2026308173] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,D/sensors_hal_Time( 1029): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1029): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1029): tsOffsetIs: Apps: 1486463031676; DSPS: 48849154; Offset : -4305891102
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-2026305146] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-2026305143] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-2026302117] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-2026302114] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,V/AlarmManager( 1029): RTC_WAKEUP set : Alarm{71cebd3 type 0 when 1449672634116 com.android.vending} when 1449672634116
,V/SIM_STK ( 1029): Menu title from STK is T-Mobile
,V/GLSActivity( 2130): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2130): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 2130): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2130): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 2130): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2130): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/Finsky  ( 8039): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 8039): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 8039): [1] 5.onFinished: Scheduling replication attempt 5.
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-2026299087] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-2026299084] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3000] from screen [on:0 period:-2026296058] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:4] from screen [on:0 period:-2026296054] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:-2026293037] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-2026293034] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-2026290007] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-2026290004] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3005] from screen [on:0 period:-2026286981] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-2026286971] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
I/[SystemUI]TimeTickManager( 1462): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1462): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1462): called onTimeUpdated()
I/[SystemUI]Clock( 1462): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1462): called onTimeUpdated()
I/[SystemUI]DateView( 1462): called onTimeUpdated()
I/[SystemUI]DateView( 1462): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1462): handleTimeUpdate
,D/sensors_hal_Time( 1029): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1029): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1029): tsOffsetIs: Apps: 1506465158282; DSPS: 49504584; Offset : -4305900779
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-2026283950] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-2026283940] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:-2026280916] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-2026280913] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-2026277884] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-2026277881] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,D/PowerManagerServiceEx( 1029): acquireWakeLockInternal: lock=518109269, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1029
,V/AlarmManager( 1029): RTC_WAKEUP set : Alarm{2f0ebf72 type 0 when 1449672665204 com.android.vending} when 1449672665204
,D/[Concierge]Service( 2608): onStartCommand(). Type : 9
,D/PowerManagerServiceEx( 1029): releaseWakeLockInternal: lock=518109269 [*alarm*], flags=0x0
,V/SIM_STK ( 1029): Menu title from STK is T-Mobile
,V/GLSActivity( 2130): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2130): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 2130): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2130): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2130): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2130): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/Finsky  ( 8039): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 8039): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 8039): [1] 5.onFinished: Giving up after 6 failures.
E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-2026274855] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-2026274852] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-2026271825] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-2026271822] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-2026268800] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-2026268797] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-2026265770] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-2026265760] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
D/sensors_hal_Time( 1029): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1029): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1029): tsOffsetIs: Apps: 1526466953848; DSPS: 50160003; Offset : -4305905672
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-2026262737] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:2] from screen [on:0 period:-2026262735] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-2026259710] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-2026259707] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-2026256680] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:11] from screen [on:0 period:-2026256669] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-2026253648] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-2026253645] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3000] from screen [on:0 period:-2026250620] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:4] from screen [on:0 period:-2026250616] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:-2026247599] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-2026247596] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,D/sensors_hal_Time( 1029): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1029): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1029): tsOffsetIs: Apps: 1546469127694; DSPS: 50815434; Offset : -4305898417
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-2026244569] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-2026244566] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-2026241548] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-2026241545] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-2026238522] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-2026238512] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-2026235492] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:11] from screen [on:0 period:-2026235481] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-2026232460] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:11] from screen [on:0 period:-2026232449] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-2026229428] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-2026229425] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-2026226401] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-2026226391] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
I/[SystemUI]TimeTickManager( 1462): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1462): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1462): called onTimeUpdated()
I/[SystemUI]Clock( 1462): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1462): called onTimeUpdated()
I/[SystemUI]DateView( 1462): called onTimeUpdated()
I/[SystemUI]DateView( 1462): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1462): handleTimeUpdate
,D/sensors_hal_Time( 1029): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1029): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1029): tsOffsetIs: Apps: 1566471606802; DSPS: 51470876; Offset : -4305921986
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-2026223369] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-2026223366] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-2026220339] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-2026220336] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-2026217308] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-2026217305] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-2026214278] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-2026214275] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-2026211249] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-2026211246] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=3.3, 0.0, 0.0  rx=4.3 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-2026208219] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=3.3, 0.0, 0.0  rx=4.3 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-2026208216] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,D/sensors_hal_Time( 1029): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1029): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1029): tsOffsetIs: Apps: 1586473734711; DSPS: 52126305; Offset : -4305899555
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=1.7, 0.0, 0.0  rx=2.2 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-2026205190] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=1.7, 0.0, 0.0  rx=2.2 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-2026205180] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=1.3, 0.0, 0.0  rx=1.6 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-2026202158] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=1.3, 0.0, 0.0  rx=1.6 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-2026202155] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-2026199128] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-2026199125] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.9 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-2026196101] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.9 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-2026196091] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.9, 0.0, 0.0  rx=0.9 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-2026193070] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.9, 0.0, 0.0  rx=0.9 bcn=0 [on:0 tx:0 rx:0 period:11] from screen [on:0 period:-2026193059] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.5 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-2026190036] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.5 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-2026190033] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-2026187011] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-2026187001] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
D/sensors_hal_Time( 1029): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1029): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1029): tsOffsetIs: Apps: 1606475632723; DSPS: 52781727; Offset : -4305893736
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-2026183981] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:9] from screen [on:0 period:-2026183972] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-2026180952] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-2026180942] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-2026177920] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:11] from screen [on:0 period:-2026177909] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-2026174887] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-2026174884] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-2026171859] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-2026171856] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-2026168829] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-2026168826] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,I/[SystemUI]TimeTickManager( 1462): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1462): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1462): called onTimeUpdated()
I/[SystemUI]Clock( 1462): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1462): called onTimeUpdated()
I/[SystemUI]DateView( 1462): called onTimeUpdated()
I/[SystemUI]DateView( 1462): called onTimeUpdated()
,D/KeyguardUpdateMonitor( 1462): handleTimeUpdate
E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-2026165801] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:12] from screen [on:0 period:-2026165789] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
D/sensors_hal_Time( 1029): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1029): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1029): tsOffsetIs: Apps: 1626477643237; DSPS: 53437153; Offset : -4305897384
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-2026162768] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-2026162765] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-2026159739] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-2026159736] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-2026156711] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-2026156701] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-2026153681] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:12] from screen [on:0 period:-2026153669] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-2026150656] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-2026150653] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-2026147629] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-2026147626] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,D/sensors_hal_Time( 1029): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1029): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1029): tsOffsetIs: Apps: 1646479675937; DSPS: 54092580; Offset : -4305909413
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-2026144599] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-2026144596] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-2026141569] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-2026141566] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,V/GLSActivity( 2130): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2130): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 2130): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2130): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2130): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2130): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1029): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1029): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1029): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1029): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1029): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1414): onNotificationPosted
D/SmartCoverUpdateMonitor( 1414): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1414): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1414): handleNotificationPosted(true)
D/QuickCircle( 1414): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1414): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1414): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1414): post do just update job
D/LgeQuickCoverNotificationData( 1414): showAll3
D/LgeQuickCoverNotificationData( 1414): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1414): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1414): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1414): showNotificationWithSetupData: display=false
,D/LgeQuickCoverOverlayWindow( 1414): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1414): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1414): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1414): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1414): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1414): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1414): updateNotificationData: count=3
,W/GLSActivity( 2130): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2130): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2130): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2130): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2130): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2130): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2130): 	at android.os.Binder.execTransact(Binder.java:446)
E/PlayEventLogger( 8039): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 8039): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 8039): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/PlayEventLogger( 8039): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 8039): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/PlayEventLogger( 8039): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 8039): 	at android.os.Binder.execTransact(Binder.java:446)
D/QuickStatusbarLayout( 1414): Notification difference=198
D/QuickStatusbarLayout( 1414): child = android.widget.LinearLayout{1813a4 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,W/System  ( 8039): Ignoring header User-Agent because its value was null.
,D/libc-netbsd(  323): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  323): res_queryN name = play.googleapis.com, class = 1, type = 1
D/libc-netbsd(  323): res_queryN name = play.googleapis.com succeed
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-2026138538] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-2026138535] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=6.2, 0.0, 0.0  rx=5.7 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-2026135509] gl rssi=-44 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=6.2, 0.0, 0.0  rx=5.7 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-2026135506] gl rssi=-44 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=3.6, 0.0, 0.0  rx=3.3 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-2026132479] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=3.6, 0.0, 0.0  rx=3.3 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-2026132476] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=1.8, 0.0, 0.0  rx=1.7 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-2026129450] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=1.8, 0.0, 0.0  rx=1.7 bcn=0 [on:0 tx:0 rx:0 period:17] from screen [on:0 period:-2026129433] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=1.4, 0.0, 0.0  rx=1.3 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-2026126410] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=1.4, 0.0, 0.0  rx=1.3 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-2026126407] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,D/sensors_hal_Time( 1029): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1029): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1029): tsOffsetIs: Apps: 1666481660149; DSPS: 54748005; Offset : -4305908843
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-2026123381] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:9] from screen [on:0 period:-2026123372] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-2026120352] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:11] from screen [on:0 period:-2026120341] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.9, 0.0, 0.0  rx=0.9 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-2026117322] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.9, 0.0, 0.0  rx=0.9 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-2026117312] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.5 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-2026114292] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.5 bcn=0 [on:0 tx:0 rx:0 period:12] from screen [on:0 period:-2026114280] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-2026111260] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-2026111257] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.9, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-2026108226] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.9, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-2026108223] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,I/[SystemUI]TimeTickManager( 1462): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1462): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1462): called onTimeUpdated()
I/[SystemUI]Clock( 1462): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1462): called onTimeUpdated()
I/[SystemUI]DateView( 1462): called onTimeUpdated()
I/[SystemUI]DateView( 1462): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1462): handleTimeUpdate
D/sensors_hal_Time( 1029): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1029): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1029): tsOffsetIs: Apps: 1686483720558; DSPS: 55403432; Offset : -4305893243
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-2026105204] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-2026105201] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-2026102176] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-2026102173] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-2026099146] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-2026099143] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-2026096116] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:11] from screen [on:0 period:-2026096105] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.9 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-2026093094] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.9 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-2026093091] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-2026090065] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-2026090062] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-2026087035] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-2026087032] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,D/sensors_hal_Time( 1029): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1029): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1029): tsOffsetIs: Apps: 1706485588206; DSPS: 56058854; Offset : -4305917605
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-43 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-2026084007] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-43 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-2026084004] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-43 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-2026080977] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-43 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-2026080974] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-2026077956] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-2026077953] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-2026074927] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-2026074924] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-2026071898] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-2026071895] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-2026068869] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-2026068866] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-2026065840] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:11] from screen [on:0 period:-2026065829] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
D/sensors_hal_Time( 1029): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1029): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1029): tsOffsetIs: Apps: 1726487774083; DSPS: 56714285; Offset : -4305898426
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-2026062816] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-2026062813] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-2026059795] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:4] from screen [on:0 period:-2026059791] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-2026056768] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-2026056765] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-2026053740] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-2026053737] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-2026050708] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-2026050705] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-2026047687] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-2026047684] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,I/[SystemUI]TimeTickManager( 1462): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1462): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1462): called onTimeUpdated()
I/[SystemUI]Clock( 1462): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1462): called onTimeUpdated()
I/[SystemUI]DateView( 1462): called onTimeUpdated()
I/[SystemUI]DateView( 1462): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1462): handleTimeUpdate
,D/sensors_hal_Time( 1029): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1029): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1029): tsOffsetIs: Apps: 1746489918972; DSPS: 57369716; Offset : -4305920284
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-2026044656] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-2026044653] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-2026041628] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-2026041625] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:-2026038597] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-2026038594] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-2026035566] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-2026035563] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:2997] from screen [on:0 period:-2026032545] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-2026032542] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-2026029516] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-2026029513] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-2026026488] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-2026026485] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,D/sensors_hal_Time( 1029): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1029): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1029): tsOffsetIs: Apps: 1766494736725; DSPS: 58025233; Offset : -4305893869
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-2026023460] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-2026023457] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-2026020431] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:11] from screen [on:0 period:-2026020420] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-2026017407] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-2026017404] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-2026014378] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-2026014375] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-2026011351] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:9] from screen [on:0 period:-2026011342] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-2026008319] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-2026008316] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,D/sensors_hal_Time( 1029): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1029): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1029): tsOffsetIs: Apps: 1786496196145; DSPS: 58680641; Offset : -4305897470
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-2026005290] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-2026005280] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-2026002268] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-2026002265] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-2025999237] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-2025999234] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-2025996208] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-2025996205] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-2025993178] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-2025993175] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-2025990146] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-2025990143] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3000] from screen [on:0 period:-2025987127] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-2025987124] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,I/[SystemUI]TimeTickManager( 1462): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1462): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1462): called onTimeUpdated()
I/[SystemUI]Clock( 1462): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1462): called onTimeUpdated()
I/[SystemUI]DateView( 1462): called onTimeUpdated()
I/[SystemUI]DateView( 1462): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1462): handleTimeUpdate
D/sensors_hal_Time( 1029): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1029): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1029): tsOffsetIs: Apps: 1806498492491; DSPS: 59336076; Offset : -4305891764
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-2025984096] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-2025984093] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-2025981067] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-2025981064] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:-2025978035] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-2025978032] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-2025975009] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-2025975006] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-2025971987] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-2025971984] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-2025968956] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-2025968953] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-2025965926] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-2025965923] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,D/sensors_hal_Time( 1029): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1029): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1029): tsOffsetIs: Apps: 1826501338421; DSPS: 59991530; Offset : -4305914487
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-2025962897] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:4] from screen [on:0 period:-2025962893] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-2025959876] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-2025959873] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-2025956846] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-2025956843] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-2025953818] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-2025953815] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-2025950787] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-2025950784] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-2025947757] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-2025947754] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,D/sensors_hal_Time( 1029): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1029): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1029): tsOffsetIs: Apps: 1846503263049; DSPS: 60646953; Offset : -4305912493
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-2025944728] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-2025944725] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-2025941697] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-2025941694] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-2025938670] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:11] from screen [on:0 period:-2025938659] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-2025935639] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-2025935636] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-2025932608] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-2025932605] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-2025929586] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-2025929583] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-2025926556] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-2025926553] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,I/[SystemUI]TimeTickManager( 1462): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1462): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1462): called onTimeUpdated()
I/[SystemUI]Clock( 1462): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1462): called onTimeUpdated()
I/[SystemUI]DateView( 1462): called onTimeUpdated()
I/[SystemUI]DateView( 1462): called onTimeUpdated()
,D/KeyguardUpdateMonitor( 1462): handleTimeUpdate
D/sensors_hal_Time( 1029): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1029): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1029): tsOffsetIs: Apps: 1866505645801; DSPS: 61302391; Offset : -4305910059
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-2025923528] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-2025923525] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-2025920498] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-2025920495] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-2025917469] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:4] from screen [on:0 period:-2025917465] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-2025914441] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:11] from screen [on:0 period:-2025914430] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-2025911409] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-2025911406] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-2025908380] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-2025908370] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
D/sensors_hal_Time( 1029): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1029): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1029): tsOffsetIs: Apps: 1886507404543; DSPS: 61957809; Offset : -4305921259
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-2025905349] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-2025905346] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-2025902321] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-2025902311] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3000] from screen [on:0 period:-2025899291] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:12] from screen [on:0 period:-2025899279] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-2025896258] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-2025896255] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=1.9, 0.0, 0.0  rx=2.4 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-2025893229] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=1.9, 0.0, 0.0  rx=2.4 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-2025893226] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=1.5, 0.0, 0.0  rx=1.7 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-2025890201] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=1.5, 0.0, 0.0  rx=1.7 bcn=0 [on:0 tx:0 rx:0 period:5] from screen [on:0 period:-2025890196] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.9 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-2025887179] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.9 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-2025887176] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,D/sensors_hal_Time( 1029): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1029): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1029): tsOffsetIs: Apps: 1906509363755; DSPS: 62613233; Offset : -4305915276
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.9, 0.0, 0.0  rx=0.9 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-2025884152] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.9, 0.0, 0.0  rx=0.9 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-2025884142] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.9, 0.0, 0.0  rx=1.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-2025881121] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.9, 0.0, 0.0  rx=1.0 bcn=0 [on:0 tx:0 rx:0 period:11] from screen [on:0 period:-2025881110] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.5 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-2025878087] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.5 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-2025878084] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-2025875057] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-2025875054] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-2025872026] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-2025872023] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-2025868995] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:4] from screen [on:0 period:-2025868991] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,I/[SystemUI]TimeTickManager( 1462): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1462): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1462): called onTimeUpdated()
I/[SystemUI]Clock( 1462): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1462): called onTimeUpdated()
I/[SystemUI]DateView( 1462): called onTimeUpdated()
I/[SystemUI]DateView( 1462): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1462): handleTimeUpdate
E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3022] from screen [on:0 period:-2025865950] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:12] from screen [on:0 period:-2025865938] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
D/sensors_hal_Time( 1029): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1029): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1029): tsOffsetIs: Apps: 1926511707081; DSPS: 63268669; Offset : -4305891338
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-2025862923] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-2025862920] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-2025859892] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:11] from screen [on:0 period:-2025859881] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-2025856859] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:11] from screen [on:0 period:-2025856848] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-2025853827] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-2025853824] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,I/ProcessStatsService( 1029): Prepared write state in 21ms
,I/ProcessStatsService( 1029): Pruning old procstats: /data/system/procstats/state-2015-12-08-19-46-30.bin
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-2025850797] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-2025850794] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-2025847771] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-2025847761] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
D/sensors_hal_Time( 1029): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1029): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1029): tsOffsetIs: Apps: 1946513566657; DSPS: 63924090; Offset : -4305893309
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-2025844738] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-2025844735] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-2025841709] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-2025841706] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-2025838681] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:11] from screen [on:0 period:-2025838670] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-2025835649] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-2025835646] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-2025832620] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-2025832617] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-2025829592] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-2025829582] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-2025826561] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:11] from screen [on:0 period:-2025826550] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
D/sensors_hal_Time( 1029): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1029): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1029): tsOffsetIs: Apps: 1966515718003; DSPS: 64579521; Offset : -4305908710
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-2025823529] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-2025823526] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-2025820501] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-2025820491] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-43 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-2025817470] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-43 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:11] from screen [on:0 period:-2025817459] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-43 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-2025814438] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-43 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-2025814435] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-43 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-2025811408] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-43 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-2025811405] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-43 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-2025808379] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-43 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-2025808376] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,I/[SystemUI]TimeTickManager( 1462): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1462): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1462): called onTimeUpdated()
I/[SystemUI]Clock( 1462): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1462): called onTimeUpdated()
I/[SystemUI]DateView( 1462): called onTimeUpdated()
I/[SystemUI]DateView( 1462): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1462): handleTimeUpdate
,D/sensors_hal_Time( 1029): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1029): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1029): tsOffsetIs: Apps: 1986517919870; DSPS: 65234953; Offset : -4305904031
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-43 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-2025805351] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-43 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:9] from screen [on:0 period:-2025805342] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-43 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-2025802321] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-43 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:11] from screen [on:0 period:-2025802310] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-43 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3005] from screen [on:0 period:-2025799286] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-43 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-2025799283] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-43 f=2412 sc=60 link=72 tx=0.9, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-2025796253] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-43 f=2412 sc=60 link=72 tx=0.9, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-2025796250] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-43 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-2025793222] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-43 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-2025793212] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-43 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-2025790191] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-43 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:11] from screen [on:0 period:-2025790180] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-43 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-2025787163] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-43 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-2025787160] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,D/sensors_hal_Time( 1029): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1029): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1029): tsOffsetIs: Apps: 2006519832779; DSPS: 65890376; Offset : -4305913391
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-43 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-2025784131] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-43 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-2025784130] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-43 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.9 bcn=0 [on:0 tx:0 rx:0 period:3005] from screen [on:0 period:-2025781109] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-43 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.9 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-2025781106] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-43 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-2025778081] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-43 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-2025778071] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-43 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-2025775049] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-43 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-2025775046] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-43 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-2025772020] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-43 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:4] from screen [on:0 period:-2025772016] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-43 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-2025768991] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-43 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-2025768990] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-43 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:-2025765977] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-43 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-2025765974] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,D/sensors_hal_Time( 1029): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1029): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1029): tsOffsetIs: Apps: 2026522601418; DSPS: 66545827; Offset : -4305922295
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-43 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-2025762946] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-43 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:2] from screen [on:0 period:-2025762944] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-43 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-2025759918] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-43 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-2025759915] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-43 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-2025756890] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-43 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:4] from screen [on:0 period:-2025756886] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-43 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:2999] from screen [on:0 period:-2025753862] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-43 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-2025753861] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-43 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:-2025750849] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-43 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-2025750846] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-43 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-2025747821] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-43 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-2025747811] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
I/[SystemUI]TimeTickManager( 1462): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1462): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1462): called onTimeUpdated()
I/[SystemUI]Clock( 1462): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1462): called onTimeUpdated()
I/[SystemUI]DateView( 1462): called onTimeUpdated()
I/[SystemUI]DateView( 1462): called onTimeUpdated()
,D/KeyguardUpdateMonitor( 1462): handleTimeUpdate
D/sensors_hal_Time( 1029): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1029): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1029): tsOffsetIs: Apps: 2046524477451; DSPS: 67201248; Offset : -4305907781
,D/PowerManagerServiceEx( 1029): acquireWakeLockInternal: lock=518109269, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1029
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-43 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3020] from screen [on:0 period:-2025744771] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,I/ActivityManager( 1029): Start proc com.lge.clock for broadcast com.lge.clock/.widget.DigitalAppWidgetProvider: pid=8330 uid=10010 gids={50010, 9997, 3003, 1028, 4002} abi=armeabi-v7a
D/[Concierge]Service( 2608): onStartCommand(). Type : 9
,E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-43 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:27] from screen [on:0 period:-2025744744] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,I/DigitalAppWidgetProvider( 8330): onReceive: com.android.deskclock.ON_QUARTER_HOUR
,V/DigitalAppWidgetProvider( 8330): startAlarmOnQuarterHour android.app.ReceiverRestrictedContext@201ec749
D/PowerManagerServiceEx( 1029): releaseWakeLockInternal: lock=518109269 [*alarm*], flags=0x0
I/ActivityManager( 1029): Killing 7664:com.google.android.gm/u0a64 (adj 15): empty #17
W/libprocessgroup( 1029): failed to open /acct/uid_10064/pid_7664/cgroup.procs: No such file or directory
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-43 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-2025741691] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-43 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-2025741681] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-43 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-2025738660] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-43 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:11] from screen [on:0 period:-2025738649] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-43 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-2025735637] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-43 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-2025735634] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-43 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-2025732607] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-43 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:4] from screen [on:0 period:-2025732603] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-43 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-2025729577] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-43 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-2025729574] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-43 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-2025726547] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-43 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-2025726544] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,D/sensors_hal_Time( 1029): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1029): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1029): tsOffsetIs: Apps: 2066526671923; DSPS: 67856680; Offset : -4305910524
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-43 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-2025723517] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-43 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-2025723514] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-43 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-2025720495] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-43 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-2025720492] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-43 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3000] from screen [on:0 period:-2025717467] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-43 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-2025717464] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-43 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-2025714437] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-43 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-2025714434] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-43 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-2025711407] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-43 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-2025711404] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-43 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-2025708378] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-43 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:4] from screen [on:0 period:-2025708374] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,V/AlarmManager( 1029): RTC_WAKEUP set : Alarm{2b36c446 type 0 when 1449673238454 com.google.android.gms} when 1449673238454
,D/LocationManagerService( 1029): getAllProviders()=[passive, gps, network]
,I/GLSUser ( 2130): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2: email
,I/GLSUser ( 2130): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2: email without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 2130): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2130): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2130): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/EventLogService( 2363): Aggregate from 1449671438321 (log), 1449671438321 (data)
,V/DownloadManager( 3299): starting query, database is not null; projection[0] is _id; projection[1] is _data AS local_filename; projection[2] is mediaprovider_uri; projection[3] is destination; projection[4] is title; projection[5] is description; projection[6] is uri; projection[7] is status; projection[8] is hint; projection[9] is mimetype AS media_type; projection[10] is total_bytes AS total_size; projection[11] is lastmod AS last_modified_timestamp; projection[12] is current_bytes AS bytes_so_far; projection[13] is allow_write; projection[14] is 'placeholder' AS local_uri; projection[15] is 'placeholder' AS reason; projection[16] is drm_status; selection is status='190' OR status='192' OR status='193' OR status='194' OR status='195' OR status='196' OR status='197' OR status='200' AND deleted != '1'; selectionArgs is null; sort is lastmod DESC.
V/DownloadManager( 3299): created cursor android.database.sqlite.SQLiteCursor@14bb7b12 on behalf of 2363
V/DownloadManager( 3299): starting query, database is not null; projection[0] is _id; projection[1] is _data AS local_filename; projection[2] is mediaprovider_uri; projection[3] is destination; projection[4] is title; projection[5] is description; projection[6] is uri; projection[7] is status; projection[8] is hint; projection[9] is mimetype AS media_type; projection[10] is total_bytes AS total_size; projection[11] is lastmod AS last_modified_timestamp; projection[12] is current_bytes AS bytes_so_far; projection[13] is allow_write; projection[14] is 'placeholder' AS local_uri; projection[15] is 'placeholder' AS reason; projection[16] is drm_status; selection is (status>='400' AND status<'600') AND deleted != '1'; selectionArgs is null; sort is lastmod DESC.
V/DownloadManager( 3299): created cursor android.database.sqlite.SQLiteCursor@353f12e3 on behalf of 2363
,V/DownloadManager( 3299): starting query, database is not null; projection[0] is _id; projection[1] is _data AS local_filename; projection[2] is mediaprovider_uri; projection[3] is destination; projection[4] is title; projection[5] is description; projection[6] is uri; projection[7] is status; projection[8] is hint; projection[9] is mimetype AS media_type; projection[10] is total_bytes AS total_size; projection[11] is lastmod AS last_modified_timestamp; projection[12] is current_bytes AS bytes_so_far; projection[13] is allow_write; projection[14] is 'placeholder' AS local_uri; projection[15] is 'placeholder' AS reason; projection[16] is drm_status; selection is status='200' AND deleted != '1'; selectionArgs is null; sort is lastmod DESC.
V/DownloadManager( 3299): created cursor android.database.sqlite.SQLiteCursor@222e64e0 on behalf of 2363
V/AlarmManager( 1029): ELAPSED_WAKEUP set : Alarm{2024a082 type 2 when 2085822 com.android.bluetooth} when 2085822
,W/bt-smp  ( 6103): Key(LSB ~ MSB) = 0a 3c a6 fe eb 17 6a 79 a6 1f 0a 0b f9 50 a0 5f 
W/bt-smp  ( 6103): Plain text(LSB ~ MSB) = 3e 08 6b 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 6103): Encrypted text(LSB ~ MSB) = bc 88 94 0f f0 77 59 d1 c0 b7 69 28 60 a7 92 0d 
W/bt-btm  ( 6103): Stopping oneshot timer
D/sensors_hal_Time( 1029): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1029): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1029): tsOffsetIs: Apps: 2086528809623; DSPS: 68512110; Offset : -4305908976
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-43 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:-2025705354] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-43 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-2025705351] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-43 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3000] from screen [on:0 period:-2025702327] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-43 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-2025702326] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-43 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-2025699308] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-43 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-2025699305] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-43 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-2025696282] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-43 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-2025696272] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-43 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-2025693249] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-43 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-2025693246] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-43 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-2025690228] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-43 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:4] from screen [on:0 period:-2025690224] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-2025687198] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-2025687195] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,I/[SystemUI]TimeTickManager( 1462): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1462): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1462): called onTimeUpdated()
I/[SystemUI]Clock( 1462): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1462): called onTimeUpdated()
I/[SystemUI]DateView( 1462): called onTimeUpdated()
I/[SystemUI]DateView( 1462): called onTimeUpdated()
,D/KeyguardUpdateMonitor( 1462): handleTimeUpdate
D/sensors_hal_Time( 1029): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1029): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1029): tsOffsetIs: Apps: 2106531556231; DSPS: 69167560; Offset : -4305909184
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-2025684169] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:4] from screen [on:0 period:-2025684165] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-43 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-2025681138] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-43 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-2025681135] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-43 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-2025678109] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-43 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-2025678106] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-43 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-2025675087] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-43 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-2025675084] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,TIME-OUT KILL (timeout was 1800000ms)
```
